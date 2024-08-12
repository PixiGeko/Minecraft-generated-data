## Comparison with [1.19.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.2)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.19.2</th><th>22w42a</th></tr><tr><td>ResourcePack version</td><td><code>9</code></td><td><code>11</code></td></tr><tr><td>World version</td><td><code>3120</code></td><td><code>3205</code></td></tr><tr><td>Protocol version</td><td><code>760</code></td><td><code>1073741928</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
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
block_entity_type.txt
</summary>

```diff
+ minecraft:chiseled_bookshelf
+ minecraft:hanging_sign
```

</details>



<details>
<summary>
command_argument_type.txt
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
entity_type.txt
</summary>

```diff
+ minecraft:camel
```

</details>







<details>
<summary>
item.txt
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
memory_module_type.txt
</summary>

```diff
+ minecraft:gaze_cooldown_ticks
```

</details>












<details>
<summary>
sensor_type.txt
</summary>

```diff
+ minecraft:camel_temptations
```

</details>
<details>
<summary>
sound_event.txt
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
<details><summary>Tags</summary>
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
<details><summary>Commands</summary>
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
<details><summary>Recipes</summary>
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
<details><summary>Translations</summary>
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

```
chat.tag.not_secure: This message is not secure, which means that it might have been modified by the serverUnverified message. Cannot be reported.
chat.tag.modified: This message has beenMessage modified by the server. Original:
resourcePack.vanilla.description: The default resources forlook and feel of Minecraft
itemGroup.redstone: Redstone Blocks
itemGroup.tools: Tools & Utilities
```

</details>
</details>
<details><summary>File structure</summary>
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
<details><summary>Misc</summary>
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
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceArgument
- net.minecraft.commands.arguments.ResourceArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$TagResult
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.package-info
+ net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
- net.minecraft.core.dispenser.BoatDispenseItemBehavior
+ net.minecraft.core.dispenser.DefaultDispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior$1
- net.minecraft.core.dispenser.DispenseItemBehavior$10
+ net.minecraft.core.dispenser.DispenseItemBehavior$11
- net.minecraft.core.dispenser.DispenseItemBehavior$12
+ net.minecraft.core.dispenser.DispenseItemBehavior$13
- net.minecraft.core.dispenser.DispenseItemBehavior$14
+ net.minecraft.core.dispenser.DispenseItemBehavior$15
- net.minecraft.core.dispenser.DispenseItemBehavior$16
+ net.minecraft.core.dispenser.DispenseItemBehavior$17
- net.minecraft.core.dispenser.DispenseItemBehavior$18
+ net.minecraft.core.dispenser.DispenseItemBehavior$19
- net.minecraft.core.dispenser.DispenseItemBehavior$2
+ net.minecraft.core.dispenser.DispenseItemBehavior$20
- net.minecraft.core.dispenser.DispenseItemBehavior$21
+ net.minecraft.core.dispenser.DispenseItemBehavior$22
- net.minecraft.core.dispenser.DispenseItemBehavior$23
+ net.minecraft.core.dispenser.DispenseItemBehavior$24
- net.minecraft.core.dispenser.DispenseItemBehavior$25
+ net.minecraft.core.dispenser.DispenseItemBehavior$26
- net.minecraft.core.dispenser.DispenseItemBehavior$27
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShearsDispenseItemBehavior
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.HolderSet
+ net.minecraft.core.HolderSet$Direct
- net.minecraft.core.HolderSet$ListBacked
+ net.minecraft.core.HolderSet$Named
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.LayeredRegistryAccess
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
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
- net.minecraft.core.RegistryAccess$Frozen
+ net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$WritableRegistryAccess
+ net.minecraft.core.RegistryCodecs$1
- net.minecraft.core.RegistryCodecs$RegistryEntry
- net.minecraft.core.RegistrySynchronization$NetworkedRegistryData
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.UUIDUtil
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
- net.minecraft.data.advancements.AdvancementSubProvider
+ net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.packs.package-info
- net.minecraft.data.advancements.packs.VanillaAdvancementProvider
- net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaStoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.BuiltinRegistries
- net.minecraft.data.BuiltinRegistries$RegistryBootstrap
+ net.minecraft.data.CachedOutput
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$PathProvider
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.HashCache$CacheUpdater
- net.minecraft.data.HashCache$ProviderCache
+ net.minecraft.data.info.BiomeParametersDumpReport
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.info.WorldgenRegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.BlockLootSubProvider
+ net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableSubProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyBlockLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$Target
- net.minecraft.data.recipes.CraftingRecipeBuilder$1
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.packs.package-info
- net.minecraft.data.recipes.packs.UpdateOneTwentyRecipeProvider
+ net.minecraft.data.recipes.RecipeBuilder
- net.minecraft.data.recipes.RecipeCategory
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.CatVariantTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.InstrumentTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.PaintingVariantTagsProvider
- net.minecraft.data.tags.PoiTypeTagsProvider
+ net.minecraft.data.tags.StructureTagsProvider
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.UpdateOneTwentyBlockTagsProvider
- net.minecraft.data.tags.VanillaBlockTagsProvider
- net.minecraft.data.tags.WorldPresetTagsProvider
- net.minecraft.data.worldgen.AncientCityStructurePieces
+ net.minecraft.data.worldgen.AncientCityStructurePools
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
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
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$HeterogenousListCollector
- net.minecraft.nbt.NbtOps$InitialListCollector
- net.minecraft.nbt.NbtOps$ListCollector
+ net.minecraft.network.chat.ChatPreviewCache
+ net.minecraft.network.chat.ChatPreviewThrottler
+ net.minecraft.network.chat.ChatSender
+ net.minecraft.network.chat.LastSeenMessages$Entry
- net.minecraft.network.chat.LastSeenMessages$Packed
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenMessagesValidator$ErrorCondition
- net.minecraft.network.chat.LocalChatSession
- net.minecraft.network.chat.MessageSignature$Packed
- net.minecraft.network.chat.MessageSignature$Unpacker
+ net.minecraft.network.chat.MessageSigner
- net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingPlayerChatMessage
+ net.minecraft.network.chat.OutgoingPlayerChatMessage$Tracked
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.PreviewableCommand
- net.minecraft.network.chat.RemoteChatSession$Data
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageChain$Link
+ net.minecraft.network.chat.SignedMessageValidator$State
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ net.minecraft.network.protocol.game.ClientboundSetDisplayChatPreviewPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundPongPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
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
+ net.minecraft.network.protocol.game.VecDeltaCodec
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializer$1
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryLoader$Bound
+ net.minecraft.resources.RegistryResourceAccess$1
+ net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
+ net.minecraft.resources.RegistryResourceAccess$ParsedEntry
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
- net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
- net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.repository.Pack$Info
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$ResourcesSupplier
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.PackSource$1
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
- net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
+ net.minecraft.server.packs.resources.Resource$IoSupplier
- net.minecraft.server.packs.resources.ResourceFilterSection
+ net.minecraft.server.packs.resources.ResourceFilterSection$1
- net.minecraft.server.packs.VanillaPackResourcesBuilder
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RegistryLayer
- net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimpleRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VariantRenameFix
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
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
- net.minecraft.util.datafix.schemas.V3203
- net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.RandomLookAround
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
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
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
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.animal.camel.Camel$1
- net.minecraft.world.entity.animal.camel.CamelAi
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
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
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
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
- net.minecraft.world.entity.animal.package-info
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
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
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
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
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
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenAi$1
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
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
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.flag.FeatureFlag
- net.minecraft.world.flag.FeatureFlagRegistry$Builder
- net.minecraft.world.flag.FeatureFlagUniverse
- net.minecraft.world.flag.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
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
+ net.minecraft.world.item.AdventureModeCheck
- net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
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
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CreativeModeTabs$10
- net.minecraft.world.item.CreativeModeTabs$12
- net.minecraft.world.item.CreativeModeTabs$3
- net.minecraft.world.item.CreativeModeTabs$5
- net.minecraft.world.item.CreativeModeTabs$7
- net.minecraft.world.item.CreativeModeTabs$9
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Instrument
- net.minecraft.world.item.InstrumentItem
+ net.minecraft.world.item.Instruments
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
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
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
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
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
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
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BigDripleafBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
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
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
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
- net.minecraft.world.level.block.ChiseledBookShelfBlock
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
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
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
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
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
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
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
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.InfestedRotatedPillarBlock
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
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangrovePropaguleBlock
+ net.minecraft.world.level.block.MangroveRootsBlock
- net.minecraft.world.level.block.MelonBlock
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
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
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
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
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
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
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
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
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
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
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
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
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
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
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
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
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
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
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
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.MaterialColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
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
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
- net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.WorldGenLevel
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

















































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.blaze3d.platform.PngInfo
+ com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ net.minecraft.client.animation.AnimationChannel
- net.minecraft.client.animation.AnimationChannel$Interpolation
+ net.minecraft.client.animation.AnimationChannel$Interpolations
- net.minecraft.client.animation.AnimationChannel$Target
+ net.minecraft.client.animation.AnimationChannel$Targets
- net.minecraft.client.animation.AnimationDefinition
+ net.minecraft.client.animation.AnimationDefinition$Builder
- net.minecraft.client.animation.definitions.CamelAnimation
- net.minecraft.client.animation.Keyframe
+ net.minecraft.client.animation.KeyframeAnimations
- net.minecraft.client.ClientTelemetryManager
+ net.minecraft.client.ClientTelemetryManager$1
- net.minecraft.client.ClientTelemetryManager$PlayerInfo
+ net.minecraft.client.CloudStatus
- net.minecraft.client.ComponentCollector
+ net.minecraft.client.DebugQueryHandler
- net.minecraft.client.Game
+ net.minecraft.client.Game$Metrics
- net.minecraft.client.GameNarrator
+ net.minecraft.client.GraphicsStatus
- net.minecraft.client.GraphicsStatus$1
+ net.minecraft.client.gui.chat.ChatPreviewAnimator
+ net.minecraft.client.gui.chat.ChatPreviewRequests
+ net.minecraft.client.gui.chat.ChatPreviewRequests$QueryIdGenerator
+ net.minecraft.client.gui.chat.ClientChatPreview$Preview
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.CycleButton
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.MultiLineEditBox
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.MultilineTextField
- net.minecraft.client.gui.components.MultilineTextField$1
+ net.minecraft.client.gui.components.MultilineTextField$StringView
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.PlainTextButton
+ net.minecraft.client.gui.components.PlayerFaceRenderer
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.SubtitleOverlay
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.TooltipAccessor
+ net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
- net.minecraft.client.gui.narration.NarratableEntry
+ net.minecraft.client.gui.narration.NarratableEntry$NarrationPriority
- net.minecraft.client.gui.narration.NarratedElementType
+ net.minecraft.client.gui.narration.NarrationElementOutput
- net.minecraft.client.gui.narration.NarrationSupplier
+ net.minecraft.client.gui.narration.NarrationThunk
+ net.minecraft.client.gui.narration.package-info
- net.minecraft.client.gui.narration.ScreenNarrationCollector
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$1
- net.minecraft.client.gui.narration.ScreenNarrationCollector$EntryKey
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$NarrationEntry
- net.minecraft.client.gui.narration.ScreenNarrationCollector$Output
- net.minecraft.client.gui.package-info
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
+ net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.achievement.StatsUpdateListener
+ net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
- net.minecraft.client.gui.screens.advancements.package-info
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.BanNoticeScreen
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.KeyBindsList
+ net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
- net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry$1
+ net.minecraft.client.gui.screens.controls.KeyBindsList$Entry
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
+ net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.KeyBindsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DatapackLoadFailureScreen
- net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.debug.package-info
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.GenericWaitingScreen
- net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
- net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
+ net.minecraft.client.gui.screens.inventory.HopperScreen
- net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
+ net.minecraft.client.gui.screens.inventory.InventoryScreen
- net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.LecternScreen
- net.minecraft.client.gui.screens.inventory.LecternScreen$1
+ net.minecraft.client.gui.screens.inventory.LoomScreen
- net.minecraft.client.gui.screens.inventory.MenuAccess
+ net.minecraft.client.gui.screens.inventory.MerchantScreen
- net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
+ net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.package-info
- net.minecraft.client.gui.screens.inventory.PageButton
+ net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
- net.minecraft.client.gui.screens.inventory.SignEditScreen
+ net.minecraft.client.gui.screens.inventory.SmithingScreen
- net.minecraft.client.gui.screens.inventory.SmokerScreen
+ net.minecraft.client.gui.screens.inventory.StonecutterScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTextTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingDotsText
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.multiplayer.ChatPreviewWarningScreen
+ net.minecraft.client.gui.screens.OnlineOptionsScreen
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PopupScreen
- net.minecraft.client.gui.screens.PopupScreen$ButtonOption
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.reporting.ChatLogSegmenter$MessageType
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen
- net.minecraft.client.gui.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen$SubmitButtonTooltip
- net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller
+ net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller$Output
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
+ net.minecraft.client.gui.screens.reporting.package-info
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$NarratableSearchResult
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SimpleOptionsSubScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.social.package-info
- net.minecraft.client.gui.screens.social.PlayerEntry
+ net.minecraft.client.gui.screens.social.PlayerEntry$1
- net.minecraft.client.gui.screens.social.PlayerEntry$2
+ net.minecraft.client.gui.screens.social.PlayerEntry$3
- net.minecraft.client.gui.screens.social.PlayerEntry$4
+ net.minecraft.client.gui.screens.social.PlayerEntry$5
- net.minecraft.client.gui.screens.social.PlayerEntry$6
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.TitleScreen$1
- net.minecraft.client.gui.screens.TitleScreen$WarningLabel
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.WinScreen$CreditsReader
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
- net.minecraft.client.gui.screens.worldselection.package-info
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext$OptionsModifier
+ net.minecraft.client.gui.screens.worldselection.WorldCreationContext$Updater
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$Entry
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$LoadingHeader
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
- net.minecraft.client.gui.spectator.categories.package-info
- net.minecraft.client.gui.spectator.categories.SpectatorPage
+ net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ net.minecraft.client.gui.spectator.package-info
+ net.minecraft.client.gui.spectator.PlayerMenuItem
- net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenu
- net.minecraft.client.gui.spectator.SpectatorMenu$1
+ net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
- net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuListener
+ net.minecraft.client.GuiMessage
- net.minecraft.client.GuiMessage$Line
+ net.minecraft.client.GuiMessageTag
- net.minecraft.client.GuiMessageTag$Icon
+ net.minecraft.client.HotbarManager
+ net.minecraft.client.KeyboardHandler
- net.minecraft.client.KeyboardHandler$1
- net.minecraft.client.KeyMapping
- net.minecraft.client.main.GameConfig
+ net.minecraft.client.main.GameConfig$FolderData
- net.minecraft.client.main.GameConfig$GameData
+ net.minecraft.client.main.GameConfig$ServerData
- net.minecraft.client.main.GameConfig$UserData
+ net.minecraft.client.main.Main
- net.minecraft.client.main.Main$1
+ net.minecraft.client.main.Main$2
- net.minecraft.client.main.Main$3
- net.minecraft.client.main.package-info
+ net.minecraft.client.main.SilentInitException
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$ChatStatus
- net.minecraft.client.Minecraft$ChatStatus$1
+ net.minecraft.client.Minecraft$ChatStatus$2
- net.minecraft.client.Minecraft$ChatStatus$3
+ net.minecraft.client.Minecraft$ChatStatus$4
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableListModel
+ net.minecraft.client.model.AllayModel
- net.minecraft.client.model.AnimationUtils
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.AxolotlModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BookModel
- net.minecraft.client.model.CamelModel
- net.minecraft.client.model.ChestBoatModel
- net.minecraft.client.model.RaftModel
+ net.minecraft.client.model.RavagerModel
- net.minecraft.client.model.SalmonModel
+ net.minecraft.client.model.SheepFurModel
- net.minecraft.client.model.SheepModel
+ net.minecraft.client.model.ShieldModel
- net.minecraft.client.model.ShulkerBulletModel
+ net.minecraft.client.model.ShulkerModel
- net.minecraft.client.model.SilverfishModel
+ net.minecraft.client.model.SkeletonModel
- net.minecraft.client.model.SkullModel
+ net.minecraft.client.model.SkullModelBase
- net.minecraft.client.model.SlimeModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.StriderModel
+ net.minecraft.client.model.TadpoleModel
- net.minecraft.client.model.TridentModel
+ net.minecraft.client.model.TropicalFishModelA
- net.minecraft.client.model.TropicalFishModelB
+ net.minecraft.client.model.TurtleModel
- net.minecraft.client.model.VexModel
+ net.minecraft.client.model.VillagerHeadModel
- net.minecraft.client.model.VillagerModel
+ net.minecraft.client.model.WardenModel
- net.minecraft.client.model.WaterPatchModel
- net.minecraft.client.MouseHandler
- net.minecraft.client.multiplayer.chat.ChatListener
+ net.minecraft.client.multiplayer.chat.ChatListener$1
+ net.minecraft.client.multiplayer.chat.ChatListener$Message
- net.minecraft.client.multiplayer.chat.ChatLog
+ net.minecraft.client.multiplayer.chat.ChatLog$1
+ net.minecraft.client.multiplayer.chat.ChatLog$Selection
+ net.minecraft.client.multiplayer.chat.ChatTrustLevel
- net.minecraft.client.multiplayer.chat.ChatTrustLevel$1
+ net.minecraft.client.multiplayer.chat.LoggedChatEvent
- net.minecraft.client.multiplayer.chat.LoggedChatMessage
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage$Player
- net.minecraft.client.multiplayer.chat.LoggedChatMessage$System
+ net.minecraft.client.multiplayer.chat.LoggedChatMessageLink
+ net.minecraft.client.multiplayer.chat.report.ChatReportBuilder$ReferencedMessageVisitor
- net.minecraft.client.multiplayer.chat.report.ChatReportBuilder$Result
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Collector
+ net.minecraft.client.multiplayer.chat.RollingMemoryChatLog
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.ClientSuggestionProvider$1
- net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ProfileKeyPairManager
+ net.minecraft.client.multiplayer.ProfileKeyPairManager$Result
+ net.minecraft.client.multiplayer.ServerData$ChatPreview
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.NarratorStatus
- net.minecraft.client.OptionInstance
+ net.minecraft.client.OptionInstance$AltEnum
- net.minecraft.client.OptionInstance$CaptionBasedToString
+ net.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
- net.minecraft.client.OptionInstance$CycleableValueSet
+ net.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
- net.minecraft.client.OptionInstance$Enum
+ net.minecraft.client.OptionInstance$IntRange
- net.minecraft.client.OptionInstance$IntRangeBase
+ net.minecraft.client.OptionInstance$IntRangeBase$1
- net.minecraft.client.OptionInstance$LazyEnum
+ net.minecraft.client.OptionInstance$OptionInstanceSliderButton
- net.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ net.minecraft.client.OptionInstance$SliderableValueSet
- net.minecraft.client.OptionInstance$TooltipSupplier
+ net.minecraft.client.OptionInstance$TooltipSupplierFactory
- net.minecraft.client.OptionInstance$UnitDouble
+ net.minecraft.client.OptionInstance$UnitDouble$1
- net.minecraft.client.OptionInstance$ValueSet
+ net.minecraft.client.Options
- net.minecraft.client.Options$1
+ net.minecraft.client.Options$2
- net.minecraft.client.Options$3
+ net.minecraft.client.Options$4
- net.minecraft.client.Options$FieldAccess
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
+ net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
- net.minecraft.client.particle.ParticleProvider
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.particle.PlayerCloudParticle
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.PortalParticle$Provider
+ net.minecraft.client.particle.ReversePortalParticle
- net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
+ net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SculkChargeParticle
+ net.minecraft.client.particle.SculkChargeParticle$Provider
- net.minecraft.client.particle.SculkChargePopParticle
+ net.minecraft.client.particle.SculkChargePopParticle$Provider
- net.minecraft.client.particle.ShriekParticle
+ net.minecraft.client.particle.ShriekParticle$Provider
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SmokeParticle
+ net.minecraft.client.particle.SmokeParticle$Provider
- net.minecraft.client.particle.SnowflakeParticle
+ net.minecraft.client.particle.SnowflakeParticle$Provider
- net.minecraft.client.particle.SonicBoomParticle
+ net.minecraft.client.particle.SonicBoomParticle$Provider
- net.minecraft.client.particle.SoulParticle
+ net.minecraft.client.particle.SoulParticle$EmissiveProvider
- net.minecraft.client.particle.SoulParticle$Provider
+ net.minecraft.client.particle.SpellParticle
- net.minecraft.client.particle.SpellParticle$AmbientMobProvider
+ net.minecraft.client.particle.SpellParticle$InstantProvider
- net.minecraft.client.particle.SpellParticle$MobProvider
+ net.minecraft.client.particle.SpellParticle$Provider
- net.minecraft.client.particle.SpellParticle$WitchProvider
+ net.minecraft.client.particle.SpitParticle
- net.minecraft.client.particle.SpitParticle$Provider
+ net.minecraft.client.particle.SplashParticle
- net.minecraft.client.particle.SplashParticle$Provider
+ net.minecraft.client.particle.SpriteSet
- net.minecraft.client.particle.SquidInkParticle
+ net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
- net.minecraft.client.particle.SquidInkParticle$Provider
+ net.minecraft.client.particle.SuspendedParticle
- net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
+ net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
- net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
- net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
+ net.minecraft.client.particle.SuspendedTownParticle
- net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
+ net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.VibrationSignalParticle
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
+ net.minecraft.client.ParticleStatus
- net.minecraft.client.PeriodicNotificationManager
+ net.minecraft.client.PeriodicNotificationManager$Notification
- net.minecraft.client.PeriodicNotificationManager$NotificationTask
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.PrioritizeChunkUpdates
+ net.minecraft.client.profiling.ClientMetricsSamplersProvider
- net.minecraft.client.profiling.package-info
- net.minecraft.client.Realms32BitWarningStatus
+ net.minecraft.client.RecipeBookCategories
- net.minecraft.client.RecipeBookCategories$1
+ net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.LiquidBlockRenderer$1
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverride$Predicate
+ net.minecraft.client.renderer.block.model.ItemOverrides
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
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.blockentity.BannerRenderer
- net.minecraft.client.renderer.blockentity.BeaconRenderer
+ net.minecraft.client.renderer.blockentity.BedRenderer
- net.minecraft.client.renderer.blockentity.BellRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
- net.minecraft.client.renderer.blockentity.BlockEntityRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderers
- net.minecraft.client.renderer.blockentity.BrightnessCombiner
+ net.minecraft.client.renderer.blockentity.CampfireRenderer
- net.minecraft.client.renderer.blockentity.ChestRenderer
+ net.minecraft.client.renderer.blockentity.ConduitRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ net.minecraft.client.renderer.blockentity.LecternRenderer
- net.minecraft.client.renderer.blockentity.package-info
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.blockentity.SkullBlockRenderer
+ net.minecraft.client.renderer.blockentity.SpawnerRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
- net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
+ net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunk
+ net.minecraft.client.renderer.chunk.RenderChunkRegion
- net.minecraft.client.renderer.chunk.RenderRegionCache
+ net.minecraft.client.renderer.chunk.RenderRegionCache$ChunkInfo
- net.minecraft.client.renderer.chunk.VisGraph
+ net.minecraft.client.renderer.chunk.VisGraph$1
- net.minecraft.client.renderer.chunk.VisibilitySet
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
- net.minecraft.client.renderer.culling.Frustum
+ net.minecraft.client.renderer.culling.package-info
- net.minecraft.client.renderer.debug.BeeDebugRenderer
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
- net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
+ net.minecraft.client.renderer.debug.BrainDebugRenderer
- net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
- net.minecraft.client.renderer.debug.ChunkBorderRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
+ net.minecraft.client.renderer.debug.CollisionBoxRenderer
- net.minecraft.client.renderer.debug.DebugRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ net.minecraft.client.renderer.debug.HeightMapRenderer
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AllayRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
- net.minecraft.client.renderer.FogRenderer$DarknessFogFunction
+ net.minecraft.client.renderer.FogRenderer$FogData
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.FogRenderer$MobEffectFogFunction
- net.minecraft.client.renderer.GameRenderer
- net.minecraft.client.renderer.GameRenderer$ResourceCache
+ net.minecraft.client.renderer.GpuWarnlistManager
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LevelRenderer$RenderChunkStorage
+ net.minecraft.client.renderer.LevelRenderer$RenderInfoMap
- net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
+ net.minecraft.client.renderer.LightTexture
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.ShaderInstance
+ net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
- net.minecraft.client.renderer.texture.PreloadedTexture
+ net.minecraft.client.renderer.texture.SimpleTexture
- net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
- net.minecraft.client.renderer.texture.SpriteContents$AnimatedTexture
- net.minecraft.client.renderer.texture.SpriteContents$InterpolationData
- net.minecraft.client.renderer.texture.SpriteLoader
- net.minecraft.client.renderer.texture.SpriteTicker
+ net.minecraft.client.renderer.texture.Stitcher
- net.minecraft.client.renderer.texture.Stitcher$Entry
+ net.minecraft.client.renderer.texture.TextureAtlas$Preparations
- net.minecraft.client.renderer.texture.TextureAtlasSprite
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$AnimatedTexture
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Ticker
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.client.ResourceLoadStateTracker
- net.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ net.minecraft.client.ResourceLoadStateTracker$ReloadReason
- net.minecraft.client.ResourceLoadStateTracker$ReloadState
+ net.minecraft.client.resources.ClientPackSource$2
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DownloadedPackSource
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.LegacyPackResourcesAdapter
- net.minecraft.client.resources.LegacyStuffWrapper
- net.minecraft.client.resources.metadata.animation.FrameSize
- net.minecraft.client.resources.metadata.animation.package-info
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
+ net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSection
- net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.language.package-info
- net.minecraft.client.resources.metadata.package-info
+ net.minecraft.client.resources.metadata.texture.package-info
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSection
- net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
- net.minecraft.client.resources.model.AtlasSet
- net.minecraft.client.resources.model.AtlasSet$ResourceLister
- net.minecraft.client.resources.model.BakedModel
+ net.minecraft.client.resources.model.BlockModelRotation
- net.minecraft.client.resources.model.BuiltInModel
+ net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelBaker
- net.minecraft.client.resources.model.ModelBakery$BakedCacheKey
+ net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
- net.minecraft.client.resources.model.ModelBakery$LoadedJson
- net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
+ net.minecraft.client.resources.model.ModelManager
- net.minecraft.client.resources.model.ModelManager$ReloadState
+ net.minecraft.client.Screenshot
- net.minecraft.client.Session
+ net.minecraft.client.StringSplitter
- net.minecraft.client.StringSplitter$1
+ net.minecraft.client.StringSplitter$FlatComponents
- net.minecraft.client.StringSplitter$LineBreakFinder
+ net.minecraft.client.StringSplitter$LineComponent
- net.minecraft.client.StringSplitter$LinePosConsumer
+ net.minecraft.client.StringSplitter$Span
+ net.minecraft.client.StringSplitter$WidthLimitedCharSink
- net.minecraft.client.StringSplitter$WidthProvider
+ net.minecraft.client.Timer
- net.minecraft.client.ToggleKeyMapping
+ net.minecraft.client.User
- net.minecraft.client.User$Type
+ net.minecraft.commands.arguments.EntitySummonArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument$ChatMessage
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.PreviewedArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Result
- net.minecraft.core.cauldron.CauldronInteraction
+ net.minecraft.core.cauldron.package-info
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
+ net.minecraft.core.dispenser.DispenseItemBehavior$25
- net.minecraft.core.dispenser.DispenseItemBehavior$26
+ net.minecraft.core.dispenser.DispenseItemBehavior$27
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
- net.minecraft.core.HolderLookup$RegistryLookup$1
+ net.minecraft.core.HolderSet
- net.minecraft.core.HolderSet$Direct
+ net.minecraft.core.HolderSet$ListBacked
- net.minecraft.core.HolderSet$Named
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleGroup
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SculkChargeParticleOptions
- net.minecraft.core.particles.SculkChargeParticleOptions$1
+ net.minecraft.core.particles.ShriekParticleOption
- net.minecraft.core.particles.ShriekParticleOption$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.core.RegistryAccess$1FrozenAccess
+ net.minecraft.core.RegistryAccess$Frozen
- net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryData
+ net.minecraft.core.RegistryAccess$Writable
+ net.minecraft.core.RegistryCodecs$RegistryEntry
- net.minecraft.core.RegistrySynchronization
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.UUIDUtil
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaNetherAdvancements
- net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
+ net.minecraft.data.BlockFamily$Variant
- net.minecraft.data.BuiltinRegistries
+ net.minecraft.data.BuiltinRegistries$RegistryBootstrap
- net.minecraft.data.CachedOutput
+ net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$Target
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.HashCache$CacheUpdater
+ net.minecraft.data.HashCache$ProviderCache
- net.minecraft.data.info.BiomeParametersDumpReport
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.UpdateOneTwentyLootTableProvider
- net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.Main
- net.minecraft.data.metadata.package-info
- net.minecraft.data.PackOutput$PathProvider
- net.minecraft.data.recipes.CraftingRecipeBuilder
- net.minecraft.data.recipes.CraftingRecipeBuilder$CraftingResult
+ net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.packs.BundleRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.tags.CatVariantTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.InstrumentTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
- net.minecraft.data.tags.PaintingVariantTagsProvider
+ net.minecraft.data.tags.PoiTypeTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.UpdateOneTwentyItemTagsProvider
- net.minecraft.data.tags.VanillaItemTagsProvider
+ net.minecraft.data.tags.WorldPresetTagsProvider
+ net.minecraft.data.worldgen.AncientCityStructurePieces
- net.minecraft.data.worldgen.AncientCityStructurePools
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.BuiltinRegistriesDatapackGenerator
- net.minecraft.gametest.framework.GameTestHelper$2
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.GlobalTestReporter
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
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
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtIo$1
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$ByteListCollector
- net.minecraft.nbt.NbtOps$HomogenousListCollector
- net.minecraft.nbt.NbtOps$IntListCollector
- net.minecraft.nbt.NbtOps$LongListCollector
+ net.minecraft.network.chat.ChatMessageContent
+ net.minecraft.network.chat.ChatPreviewCache$Result
+ net.minecraft.network.chat.ChatPreviewThrottler$Request
- net.minecraft.network.chat.LastSeenMessagesTracker$Update
+ net.minecraft.network.chat.LastSeenMessagesValidator
- net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.MessageSignature$Packer
- net.minecraft.network.chat.MessageSignatureCache
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.OutgoingPlayerChatMessage$NotTracked
+ net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.PreviewableCommand$Argument
- net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageHeader
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator$Unsigned
+ net.minecraft.network.protocol.game.ClientboundChatPreviewPacket
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerChatHeaderPacket
- net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
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
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundSystemChatPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateEnabledFeaturesPacket
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundChatPreviewPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
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
+ net.minecraft.network.protocol.game.ServerboundPongPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$1
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryLoader$Bound
+ net.minecraft.resources.RegistryResourceAccess$1
+ net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
+ net.minecraft.resources.RegistryResourceAccess$ParsedEntry
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
- net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
- net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PathPackResources
- net.minecraft.server.packs.repository.Pack$Info
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$ResourcesSupplier
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.PackSource$1
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
- net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
+ net.minecraft.server.packs.resources.Resource$IoSupplier
- net.minecraft.server.packs.resources.ResourceFilterSection
+ net.minecraft.server.packs.resources.ResourceFilterSection$1
- net.minecraft.server.packs.VanillaPackResourcesBuilder
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RegistryLayer
- net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimpleRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VariantRenameFix
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
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
- net.minecraft.util.datafix.schemas.V3203
- net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.RandomLookAround
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
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
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
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.animal.camel.Camel$1
- net.minecraft.world.entity.animal.camel.CamelAi
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
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
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
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
- net.minecraft.world.entity.animal.package-info
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
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
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
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
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
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenAi$1
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
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
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.flag.FeatureFlag
- net.minecraft.world.flag.FeatureFlagRegistry$Builder
- net.minecraft.world.flag.FeatureFlagUniverse
- net.minecraft.world.flag.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
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
+ net.minecraft.world.item.AdventureModeCheck
- net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
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
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CreativeModeTabs$10
- net.minecraft.world.item.CreativeModeTabs$12
- net.minecraft.world.item.CreativeModeTabs$3
- net.minecraft.world.item.CreativeModeTabs$5
- net.minecraft.world.item.CreativeModeTabs$7
- net.minecraft.world.item.CreativeModeTabs$9
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Instrument
- net.minecraft.world.item.InstrumentItem
+ net.minecraft.world.item.Instruments
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
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
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
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
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
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
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BigDripleafBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
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
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
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
- net.minecraft.world.level.block.ChiseledBookShelfBlock
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
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
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
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
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
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
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
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.MangroveTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.InfestedRotatedPillarBlock
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
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangrovePropaguleBlock
+ net.minecraft.world.level.block.MangroveRootsBlock
- net.minecraft.world.level.block.MelonBlock
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
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
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
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
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
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
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
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
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
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
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
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
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
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
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
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
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
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
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
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.MaterialColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
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
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
- net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.WorldGenLevel
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