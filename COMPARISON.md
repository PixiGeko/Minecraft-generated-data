## Comparison with [1.13.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13.2)

- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)

<hr/>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ drop.json
+ schedule.json
```

</details>







<details>
<summary>
data
</summary>

```diff
- data get block <pos: block_pos> <path: nbt_path> <scale: double>
+ data get block <targetPos: block_pos> <path: nbt_path> <scale: double>
- data merge block <pos: block_pos> <nbt: nbt>
+ data merge block <targetPos: block_pos> <nbt: nbt_compound_tag>
+ data merge entity <target: entity> <nbt: nbt_compound_tag>
- data merge entity <target: entity> <nbt: nbt>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> append from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> append from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> append value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> merge from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> merge from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> merge value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> prepend value <value: nbt_tag>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> set from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> set from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> set value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> append from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> append from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> append value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> merge from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> merge from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> merge value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> set from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> set from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> set value <value: nbt_tag>
- data remove block <pos: block_pos> <path: nbt_path>
+ data remove block <targetPos: block_pos> <path: nbt_path>
```

</details>







<details>
<summary>
execute
</summary>

```diff
+ execute if data block <sourcePos: block_pos> <path: nbt_path>
+ execute if data entity <source: entity> <path: nbt_path>
- execute store result block <pos: block_pos> <path: nbt_path> byte <scale: double>
- execute store result block <pos: block_pos> <path: nbt_path> double <scale: double>
- execute store result block <pos: block_pos> <path: nbt_path> float <scale: double>
- execute store result block <pos: block_pos> <path: nbt_path> int <scale: double>
- execute store result block <pos: block_pos> <path: nbt_path> long <scale: double>
- execute store result block <pos: block_pos> <path: nbt_path> short <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> byte <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> double <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> float <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> int <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> long <scale: double>
+ execute store result block <targetPos: block_pos> <path: nbt_path> short <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> byte <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> double <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> float <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> int <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> long <scale: double>
- execute store success block <pos: block_pos> <path: nbt_path> short <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> byte <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> double <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> float <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> int <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> long <scale: double>
+ execute store success block <targetPos: block_pos> <path: nbt_path> short <scale: double>
+ execute unless data block <sourcePos: block_pos> <path: nbt_path>
+ execute unless data entity <source: entity> <path: nbt_path>
```

</details>




































<details>
<summary>
summon
</summary>

```diff
+ summon <entity: entity_summon> <pos: vec3> <nbt: nbt_compound_tag>
- summon <entity: entity_summon> <pos: vec3> <nbt: nbt>
```

</details>





<details>
<summary>
time
</summary>

```diff
- time add <time: integer>
+ time add <time: time>
- time set <time: integer>
+ time set <time: time>
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ acacia_sign.json
+ andesite_slab.json
+ andesite_stairs.json
+ andesite_wall.json
- banner_add_pattern.json
+ birch_sign.json
+ black_carpet_from_white_carpet.json
+ black_dye_from_wither_rose.json
+ black_dye.json
+ black_stained_glass_pane_from_glass_pane.json
+ blue_carpet_from_white_carpet.json
+ blue_dye_from_cornflower.json
+ blue_dye.json
+ blue_stained_glass_pane_from_glass_pane.json
+ brick_wall.json
+ brown_carpet_from_white_carpet.json
+ brown_dye.json
+ brown_stained_glass_pane_from_glass_pane.json
- cactus_green.json
+ creeper_banner_pattern.json
+ crossbow.json
+ cyan_carpet_from_white_carpet.json
+ cyan_stained_glass_pane_from_glass_pane.json
+ dark_oak_sign.json
+ diorite_slab.json
+ diorite_stairs.json
+ diorite_wall.json
+ end_stone_brick_slab.json
+ end_stone_brick_stairs.json
+ end_stone_brick_wall.json
+ flower_banner_pattern.json
+ granite_slab.json
+ granite_stairs.json
+ granite_wall.json
+ gray_carpet_from_white_carpet.json
+ gray_stained_glass_pane_from_glass_pane.json
+ green_carpet_from_white_carpet.json
+ green_dye.json
+ green_stained_glass_pane_from_glass_pane.json
+ jungle_sign.json
+ light_blue_carpet_from_white_carpet.json
+ light_blue_dye_from_blue_white_dye.json
- light_blue_dye_from_lapis_bonemeal.json
+ light_blue_stained_glass_pane_from_glass_pane.json
+ light_gray_carpet_from_white_carpet.json
+ light_gray_dye_from_black_white_dye.json
- light_gray_dye_from_gray_bonemeal.json
+ light_gray_dye_from_gray_white_dye.json
- light_gray_dye_from_ink_bonemeal.json
+ light_gray_stained_glass_pane_from_glass_pane.json
+ lime_carpet_from_white_carpet.json
+ lime_stained_glass_pane_from_glass_pane.json
+ loom.json
+ magenta_carpet_from_white_carpet.json
+ magenta_dye_from_blue_red_pink.json
+ magenta_dye_from_blue_red_white_dye.json
- magenta_dye_from_lapis_ink_bonemeal.json
- magenta_dye_from_lapis_red_pink.json
+ magenta_stained_glass_pane_from_glass_pane.json
+ mojang_banner_pattern.json
+ mossy_cobblestone_slab.json
+ mossy_cobblestone_stairs.json
+ mossy_stone_brick_slab.json
+ mossy_stone_brick_stairs.json
+ mossy_stone_brick_wall.json
+ nether_brick_wall.json
+ oak_sign.json
+ orange_carpet_from_white_carpet.json
+ orange_stained_glass_pane_from_glass_pane.json
+ pink_carpet_from_white_carpet.json
- pink_dye_from_red_bonemeal.json
+ pink_dye_from_red_white_dye.json
+ pink_stained_glass_pane_from_glass_pane.json
+ polished_andesite_slab.json
+ polished_andesite_stairs.json
+ polished_diorite_slab.json
+ polished_diorite_stairs.json
+ polished_granite_slab.json
+ polished_granite_stairs.json
+ prismarine_wall.json
+ purple_carpet_from_white_carpet.json
+ purple_stained_glass_pane_from_glass_pane.json
+ red_carpet_from_white_carpet.json
+ red_nether_brick_slab.json
+ red_nether_brick_stairs.json
+ red_nether_brick_wall.json
+ red_sandstone_wall.json
+ red_stained_glass_pane_from_glass_pane.json
+ sandstone_wall.json
- sign.json
+ skull_banner_pattern.json
+ smooth_quartz_slab.json
+ smooth_quartz_stairs.json
+ smooth_quartz.json
+ smooth_red_sandstone_slab.json
+ smooth_red_sandstone_stairs.json
+ smooth_red_sandstone.json
+ smooth_sandstone_slab.json
+ smooth_sandstone_stairs.json
+ smooth_sandstone.json
+ smooth_stone_slab.json
+ smooth_stone.json
+ spruce_sign.json
+ stick_from_bamboo_item.json
+ stone_brick_wall.json
+ stone_stairs.json
+ suspicious_stew.json
+ white_dye_from_lily_of_the_valley.json
+ white_dye.json
+ white_stained_glass_pane_from_glass_pane.json
+ yellow_carpet_from_white_carpet.json
+ yellow_stained_glass_pane_from_glass_pane.json
```

</details>




















<details>
<summary>
beetroot_soup.json
</summary>

```
Type: crafting_shaped -> crafting_shapeless
```

</details>





































































































































































































































































































































































































<details>
<summary>
rabbit_stew_from_brown_mushroom.json
</summary>

```
Type: crafting_shaped -> crafting_shapeless
```

</details>
<details>
<summary>
rabbit_stew_from_red_mushroom.json
</summary>

```
Type: crafting_shaped -> crafting_shapeless
```

</details>











<details>
<summary>
red_dye_from_beetroot.json
</summary>

```
Result: rose_red x1 -> red_dye x1
```

</details>
<details>
<summary>
red_dye_from_poppy.json
</summary>

```
Result: rose_red x1 -> red_dye x1
```

</details>
<details>
<summary>
red_dye_from_rose_bush.json
</summary>

```
Result: rose_red x2 -> red_dye x2
```

</details>
<details>
<summary>
red_dye_from_tulip.json
</summary>

```
Result: rose_red x1 -> red_dye x1
```

</details>





































<details>
<summary>
stick.json
</summary>

```
Group: none -> sticks
```

</details>











































<details>
<summary>
yellow_dye_from_dandelion.json
</summary>

```
Result: dandelion_yellow x1 -> yellow_dye x1
```

</details>
<details>
<summary>
yellow_dye_from_sunflower.json
</summary>

```
Result: dandelion_yellow x2 -> yellow_dye x2
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.arbalistic.description: Kill five unique mobs with one crossbow shot
+ advancements.adventure.arbalistic.title: Arbalistic
+ advancements.adventure.ol_betsy.description: Shoot a crossbow
+ advancements.adventure.ol_betsy.title: Ol' Betsy
+ advancements.adventure.two_birds_one_arrow.description: Kill two Phantoms with a piercing arrow
+ advancements.adventure.two_birds_one_arrow.title: Two Birds, One Arrow
+ advancements.adventure.whos_the_pillager_now.description: Give a Pillager a taste of their own medicine
+ advancements.adventure.whos_the_pillager_now.title: Who's the Pillager Now?
- argument.nbt.invalid: Invalid NBT: %s
+ argument.time.invalid_unit: Invalid unit
+ argument.time.not_nonnegative_integer: Not a non-negative integer: %s
- arguments.nbtpath.child.invalid: Can't access child '%s', either doesn't exist or parent isn't a compound
- arguments.nbtpath.element.invalid: Can't access element %s, either doesn't exist or parent isn't a list
+ arguments.nbtpath.nothing_found: Found no elements matching %s
+ biome.minecraft.bamboo_jungle_hills: Bamboo Jungle Hills
+ biome.minecraft.bamboo_jungle: Bamboo Jungle
+ block.minecraft.acacia_sign: Acacia Sign
+ block.minecraft.acacia_wall_sign: Acacia Wall Sign
+ block.minecraft.andesite_slab: Andesite Slab
+ block.minecraft.andesite_stairs: Andesite Stairs
+ block.minecraft.andesite_wall: Andesite Wall
+ block.minecraft.bamboo_sapling: Bamboo Sapling
+ block.minecraft.bamboo: Bamboo
+ block.minecraft.birch_sign: Birch Sign
+ block.minecraft.birch_wall_sign: Birch Wall Sign
+ block.minecraft.brick_wall: Brick Wall
+ block.minecraft.cornflower: Cornflower
+ block.minecraft.dark_oak_sign: Dark Oak Sign
+ block.minecraft.dark_oak_wall_sign: Dark Oak Wall Sign
+ block.minecraft.diorite_slab: Diorite Slab
+ block.minecraft.diorite_stairs: Diorite Stairs
+ block.minecraft.diorite_wall: Diorite Wall
+ block.minecraft.end_stone_brick_slab: End Stone Brick Slab
+ block.minecraft.end_stone_brick_stairs: End Stone Brick Stairs
+ block.minecraft.end_stone_brick_wall: End Stone Brick Wall
+ block.minecraft.granite_slab: Granite Slab
+ block.minecraft.granite_stairs: Granite Stairs
+ block.minecraft.granite_wall: Granite Wall
+ block.minecraft.jungle_sign: Jungle Sign
+ block.minecraft.jungle_wall_sign: Jungle Wall Sign
+ block.minecraft.lily_of_the_valley: Lily of the Valley
+ block.minecraft.loom: Loom
+ block.minecraft.mossy_cobblestone_slab: Mossy Cobblestone Slab
+ block.minecraft.mossy_cobblestone_stairs: Mossy Cobblestone Stairs
+ block.minecraft.mossy_stone_brick_slab: Mossy Stone Brick Slab
+ block.minecraft.mossy_stone_brick_stairs: Mossy Stone Brick Stairs
+ block.minecraft.mossy_stone_brick_wall: Mossy Stone Brick Wall
+ block.minecraft.nether_brick_wall: Nether Brick Wall
+ block.minecraft.oak_sign: Oak Sign
+ block.minecraft.oak_wall_sign: Oak Wall Sign
+ block.minecraft.polished_andesite_slab: Polished Andesite Slab
+ block.minecraft.polished_andesite_stairs: Polished Andesite Stairs
+ block.minecraft.polished_diorite_slab: Polished Diorite Slab
+ block.minecraft.polished_diorite_stairs: Polished Diorite Stairs
+ block.minecraft.polished_granite_slab: Polished Granite Slab
+ block.minecraft.polished_granite_stairs: Polished Granite Stairs
+ block.minecraft.potted_bamboo: Potted Bamboo
+ block.minecraft.potted_cornflower: Potted Cornflower
+ block.minecraft.potted_lily_of_the_valley: Potted Lily of the Valley
+ block.minecraft.potted_wither_rose: Potted Wither Rose
+ block.minecraft.prismarine_wall: Prismarine Wall
+ block.minecraft.red_nether_brick_slab: Red Nether Brick Slab
+ block.minecraft.red_nether_brick_stairs: Red Nether Brick Stairs
+ block.minecraft.red_nether_brick_wall: Red Nether Brick Wall
+ block.minecraft.red_sandstone_wall: Red Sandstone Wall
+ block.minecraft.sandstone_wall: Sandstone Wall
- block.minecraft.sign: Sign
+ block.minecraft.smooth_quartz_slab: Smooth Quartz Slab
+ block.minecraft.smooth_quartz_stairs: Smooth Quartz Stairs
+ block.minecraft.smooth_red_sandstone_slab: Smooth Red Sandstone Slab
+ block.minecraft.smooth_red_sandstone_stairs: Smooth Red Sandstone Stairs
+ block.minecraft.smooth_sandstone_slab: Smooth Sandstone Slab
+ block.minecraft.smooth_sandstone_stairs: Smooth Sandstone Stairs
+ block.minecraft.smooth_stone_slab: Smooth Stone Slab
+ block.minecraft.spruce_sign: Spruce Sign
+ block.minecraft.spruce_wall_sign: Spruce Wall Sign
+ block.minecraft.stone_brick_wall: Stone Brick Wall
+ block.minecraft.stone_stairs: Stone Stairs
- block.minecraft.wall_sign: Wall Sign
+ block.minecraft.wither_rose: Wither Rose
+ commands.data.get.multiple: This argument accepts a single NBT value
+ commands.data.modify.expected_list: Expected list, got: %s
+ commands.data.modify.expected_object: Expected object, got: %s
+ commands.drop.no_held_items: Entity can't hold any items
+ commands.drop.no_loot_table: Entity %s has no loot table
+ commands.drop.success.multiple_with_table: Dropped %s items from loot table %s
+ commands.drop.success.multiple: Dropped %s items
+ commands.drop.success.single_with_table: Dropped %s * %s from loot table %s
+ commands.drop.success.single: Dropped %s * %s
+ commands.schedule.created.function: Scheduled function '%s' in %s ticks at gametime %s
+ commands.schedule.created.tag: Scheduled tag '%s' in %s ticks at gametime %s
+ commands.schedule.same_tick: Can't schedule for current tick
+ container.loom: Loom
+ enchantment.minecraft.multishot: Multishot
+ enchantment.minecraft.piercing: Piercing
+ enchantment.minecraft.quick_charge: Quick Charge
+ entity.minecraft.illager_beast: Illager Beast
+ entity.minecraft.panda: Panda
+ entity.minecraft.pillager: Pillager
+ item.minecraft.black_dye: Black Dye
+ item.minecraft.blue_dye: Blue Dye
+ item.minecraft.brown_dye: Brown Dye
- item.minecraft.cactus_green: Cactus Green
+ item.minecraft.creeper_banner_pattern: Banner Pattern
+ item.minecraft.creeper_banner_pattern.desc: Creeper Charge
+ item.minecraft.crossbow: Crossbow
- item.minecraft.dandelion_yellow: Dandelion Yellow
+ item.minecraft.flower_banner_pattern: Banner Pattern
+ item.minecraft.flower_banner_pattern.desc: Flower Charge
+ item.minecraft.green_dye: Green Dye
+ item.minecraft.illager_beast_spawn_egg: Illager Beast Spawn Egg
+ item.minecraft.mojang_banner_pattern: Banner Pattern
+ item.minecraft.mojang_banner_pattern.desc: Thing
+ item.minecraft.panda_spawn_egg: Panda Spawn Egg
+ item.minecraft.pillager_spawn_egg: Pillager Spawn Egg
+ item.minecraft.red_dye: Red Dye
- item.minecraft.rose_red: Rose Red
+ item.minecraft.skull_banner_pattern: Banner Pattern
+ item.minecraft.skull_banner_pattern.desc: Skull Charge
+ item.minecraft.suspicious_stew: Suspicious Stew
+ item.minecraft.white_dye: White Dye
+ item.minecraft.yellow_dye: Yellow Dye
+ menu.reportBugs: Report Bugs
+ menu.sendFeedback: Give Feedback
+ subtitles.entity.illager_beast.ambient: Illager Beast grunts
+ subtitles.entity.illager_beast.attack: Illager Beast bites
+ subtitles.entity.illager_beast.death: Illager Beast dies
+ subtitles.entity.illager_beast.hurt: Illager Beast hurts
+ subtitles.entity.illager_beast.roar: Illager Beast roars
+ subtitles.entity.illager_beast.step: Illager Beast steps
+ subtitles.entity.illager_beast.stunned: Illager Beast stunned
+ subtitles.entity.panda.aggressive_ambient: Panda huffs
+ subtitles.entity.panda.ambient: Panda pants
+ subtitles.entity.panda.bite: Panda bites
+ subtitles.entity.panda.cant_breed: Panda bleats
+ subtitles.entity.panda.death: Panda dies
+ subtitles.entity.panda.eat: Panda eats
+ subtitles.entity.panda.hurt: Panda hurts
+ subtitles.entity.panda.pre_sneeze: Panda's nose tickles
+ subtitles.entity.panda.sneeze: Panda sneezes
+ subtitles.entity.panda.step: Panda steps
+ subtitles.entity.panda.worried_ambient: Panda whimpers
+ subtitles.entity.pillager.ambient: Pillager murmurs
+ subtitles.entity.pillager.death: Pillager dies
+ subtitles.entity.pillager.hurt: Pillager hurts
+ subtitles.item.crossbow.charge: Crossbow charges up
+ subtitles.item.crossbow.hit: Arrow hits
+ subtitles.item.crossbow.load: Crossbow loads
+ subtitles.item.crossbow.shoot: Crossbow fires
```

</details>
<details>
<summary>
Changes
</summary>

```
block.minecraft.redstone_wire: Redstone DustWire
item.minecraft.redstone: Redstone Dust
arguments.nbtpath.node.invalid: Invalid NBT path, expected element name or index element
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/adventure/arbalistic.json
+ minecraft/advancements/adventure/ol_betsy.json
+ minecraft/advancements/adventure/two_birds_one_arrow.json
+ minecraft/advancements/adventure/whos_the_pillager_now.json
+ minecraft/advancements/recipes/building_blocks/andesite_slab.json
+ minecraft/advancements/recipes/building_blocks/andesite_stairs.json
+ minecraft/advancements/recipes/building_blocks/andesite_wall.json
+ minecraft/advancements/recipes/building_blocks/brick_wall.json
+ minecraft/advancements/recipes/building_blocks/diorite_slab.json
+ minecraft/advancements/recipes/building_blocks/diorite_stairs.json
+ minecraft/advancements/recipes/building_blocks/diorite_wall.json
+ minecraft/advancements/recipes/building_blocks/end_stone_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/end_stone_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/end_stone_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/granite_slab.json
+ minecraft/advancements/recipes/building_blocks/granite_stairs.json
+ minecraft/advancements/recipes/building_blocks/granite_wall.json
+ minecraft/advancements/recipes/building_blocks/mossy_cobblestone_slab.json
+ minecraft/advancements/recipes/building_blocks/mossy_cobblestone_stairs.json
+ minecraft/advancements/recipes/building_blocks/mossy_stone_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/mossy_stone_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/nether_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/polished_andesite_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_andesite_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_diorite_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_diorite_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_granite_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_granite_stairs.json
+ minecraft/advancements/recipes/building_blocks/prismarine_wall.json
+ minecraft/advancements/recipes/building_blocks/red_nether_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/red_nether_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/red_nether_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/red_sandstone_wall.json
+ minecraft/advancements/recipes/building_blocks/sandstone_wall.json
+ minecraft/advancements/recipes/building_blocks/smooth_quartz_slab.json
+ minecraft/advancements/recipes/building_blocks/smooth_quartz_stairs.json
+ minecraft/advancements/recipes/building_blocks/smooth_quartz.json
+ minecraft/advancements/recipes/building_blocks/smooth_red_sandstone_slab.json
+ minecraft/advancements/recipes/building_blocks/smooth_red_sandstone_stairs.json
+ minecraft/advancements/recipes/building_blocks/smooth_red_sandstone.json
+ minecraft/advancements/recipes/building_blocks/smooth_sandstone_slab.json
+ minecraft/advancements/recipes/building_blocks/smooth_sandstone_stairs.json
+ minecraft/advancements/recipes/building_blocks/smooth_sandstone.json
+ minecraft/advancements/recipes/building_blocks/smooth_stone_slab.json
+ minecraft/advancements/recipes/building_blocks/smooth_stone.json
+ minecraft/advancements/recipes/building_blocks/stone_brick_wall.json
+ minecraft/advancements/recipes/building_blocks/stone_stairs.json
+ minecraft/advancements/recipes/combat/crossbow.json
+ minecraft/advancements/recipes/decorations/acacia_sign.json
+ minecraft/advancements/recipes/decorations/birch_sign.json
+ minecraft/advancements/recipes/decorations/black_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/black_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/blue_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/blue_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/brown_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/brown_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/cyan_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/cyan_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/dark_oak_sign.json
+ minecraft/advancements/recipes/decorations/gray_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/gray_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/green_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/green_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/jungle_sign.json
+ minecraft/advancements/recipes/decorations/light_blue_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/light_blue_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/light_gray_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/light_gray_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/lime_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/lime_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/loom.json
+ minecraft/advancements/recipes/decorations/magenta_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/magenta_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/oak_sign.json
+ minecraft/advancements/recipes/decorations/orange_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/orange_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/pink_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/pink_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/purple_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/purple_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/red_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/red_stained_glass_pane_from_glass_pane.json
- minecraft/advancements/recipes/decorations/sign.json
+ minecraft/advancements/recipes/decorations/spruce_sign.json
+ minecraft/advancements/recipes/decorations/white_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/decorations/yellow_carpet_from_white_carpet.json
+ minecraft/advancements/recipes/decorations/yellow_stained_glass_pane_from_glass_pane.json
+ minecraft/advancements/recipes/misc/black_dye_from_wither_rose.json
+ minecraft/advancements/recipes/misc/black_dye.json
+ minecraft/advancements/recipes/misc/blue_dye_from_cornflower.json
+ minecraft/advancements/recipes/misc/blue_dye.json
+ minecraft/advancements/recipes/misc/brown_dye.json
- minecraft/advancements/recipes/misc/cactus_green.json
+ minecraft/advancements/recipes/misc/creeper_banner_pattern.json
+ minecraft/advancements/recipes/misc/flower_banner_pattern.json
+ minecraft/advancements/recipes/misc/green_dye.json
+ minecraft/advancements/recipes/misc/light_blue_dye_from_blue_white_dye.json
- minecraft/advancements/recipes/misc/light_blue_dye_from_lapis_bonemeal.json
+ minecraft/advancements/recipes/misc/light_gray_dye_from_black_white_dye.json
- minecraft/advancements/recipes/misc/light_gray_dye_from_gray_bonemeal.json
+ minecraft/advancements/recipes/misc/light_gray_dye_from_gray_white_dye.json
- minecraft/advancements/recipes/misc/light_gray_dye_from_ink_bonemeal.json
+ minecraft/advancements/recipes/misc/magenta_dye_from_blue_red_pink.json
+ minecraft/advancements/recipes/misc/magenta_dye_from_blue_red_white_dye.json
- minecraft/advancements/recipes/misc/magenta_dye_from_lapis_ink_bonemeal.json
- minecraft/advancements/recipes/misc/magenta_dye_from_lapis_red_pink.json
+ minecraft/advancements/recipes/misc/mojang_banner_pattern.json
- minecraft/advancements/recipes/misc/pink_dye_from_red_bonemeal.json
+ minecraft/advancements/recipes/misc/pink_dye_from_red_white_dye.json
+ minecraft/advancements/recipes/misc/skull_banner_pattern.json
+ minecraft/advancements/recipes/misc/stick_from_bamboo_item.json
+ minecraft/advancements/recipes/misc/white_dye_from_lily_of_the_valley.json
+ minecraft/advancements/recipes/misc/white_dye.json
+ minecraft/loot_tables/blocks/acacia_button.json
+ minecraft/loot_tables/blocks/acacia_door.json
+ minecraft/loot_tables/blocks/acacia_fence_gate.json
+ minecraft/loot_tables/blocks/acacia_fence.json
+ minecraft/loot_tables/blocks/acacia_leaves.json
+ minecraft/loot_tables/blocks/acacia_log.json
+ minecraft/loot_tables/blocks/acacia_planks.json
+ minecraft/loot_tables/blocks/acacia_pressure_plate.json
+ minecraft/loot_tables/blocks/acacia_sapling.json
+ minecraft/loot_tables/blocks/acacia_sign.json
+ minecraft/loot_tables/blocks/acacia_slab.json
+ minecraft/loot_tables/blocks/acacia_stairs.json
+ minecraft/loot_tables/blocks/acacia_trapdoor.json
+ minecraft/loot_tables/blocks/acacia_wood.json
+ minecraft/loot_tables/blocks/activator_rail.json
+ minecraft/loot_tables/blocks/allium.json
+ minecraft/loot_tables/blocks/andesite_slab.json
+ minecraft/loot_tables/blocks/andesite_stairs.json
+ minecraft/loot_tables/blocks/andesite_wall.json
+ minecraft/loot_tables/blocks/andesite.json
+ minecraft/loot_tables/blocks/anvil.json
+ minecraft/loot_tables/blocks/attached_melon_stem.json
+ minecraft/loot_tables/blocks/attached_pumpkin_stem.json
+ minecraft/loot_tables/blocks/azure_bluet.json
+ minecraft/loot_tables/blocks/bamboo_sapling.json
+ minecraft/loot_tables/blocks/bamboo.json
+ minecraft/loot_tables/blocks/beacon.json
+ minecraft/loot_tables/blocks/beetroots.json
+ minecraft/loot_tables/blocks/birch_button.json
+ minecraft/loot_tables/blocks/birch_door.json
+ minecraft/loot_tables/blocks/birch_fence_gate.json
+ minecraft/loot_tables/blocks/birch_fence.json
+ minecraft/loot_tables/blocks/birch_leaves.json
+ minecraft/loot_tables/blocks/birch_log.json
+ minecraft/loot_tables/blocks/birch_planks.json
+ minecraft/loot_tables/blocks/birch_pressure_plate.json
+ minecraft/loot_tables/blocks/birch_sapling.json
+ minecraft/loot_tables/blocks/birch_sign.json
+ minecraft/loot_tables/blocks/birch_slab.json
+ minecraft/loot_tables/blocks/birch_stairs.json
+ minecraft/loot_tables/blocks/birch_trapdoor.json
+ minecraft/loot_tables/blocks/birch_wood.json
+ minecraft/loot_tables/blocks/black_banner.json
+ minecraft/loot_tables/blocks/black_bed.json
+ minecraft/loot_tables/blocks/black_carpet.json
+ minecraft/loot_tables/blocks/black_concrete_powder.json
+ minecraft/loot_tables/blocks/black_concrete.json
+ minecraft/loot_tables/blocks/black_glazed_terracotta.json
+ minecraft/loot_tables/blocks/black_shulker_box.json
+ minecraft/loot_tables/blocks/black_stained_glass_pane.json
+ minecraft/loot_tables/blocks/black_stained_glass.json
+ minecraft/loot_tables/blocks/black_terracotta.json
+ minecraft/loot_tables/blocks/black_wool.json
+ minecraft/loot_tables/blocks/blue_banner.json
+ minecraft/loot_tables/blocks/blue_bed.json
+ minecraft/loot_tables/blocks/blue_carpet.json
+ minecraft/loot_tables/blocks/blue_concrete_powder.json
+ minecraft/loot_tables/blocks/blue_concrete.json
+ minecraft/loot_tables/blocks/blue_glazed_terracotta.json
+ minecraft/loot_tables/blocks/blue_ice.json
+ minecraft/loot_tables/blocks/blue_orchid.json
+ minecraft/loot_tables/blocks/blue_shulker_box.json
+ minecraft/loot_tables/blocks/blue_stained_glass_pane.json
+ minecraft/loot_tables/blocks/blue_stained_glass.json
+ minecraft/loot_tables/blocks/blue_terracotta.json
+ minecraft/loot_tables/blocks/blue_wool.json
+ minecraft/loot_tables/blocks/bone_block.json
+ minecraft/loot_tables/blocks/bookshelf.json
+ minecraft/loot_tables/blocks/brain_coral_block.json
+ minecraft/loot_tables/blocks/brain_coral_fan.json
+ minecraft/loot_tables/blocks/brain_coral.json
+ minecraft/loot_tables/blocks/brewing_stand.json
+ minecraft/loot_tables/blocks/brick_slab.json
+ minecraft/loot_tables/blocks/brick_stairs.json
+ minecraft/loot_tables/blocks/brick_wall.json
+ minecraft/loot_tables/blocks/bricks.json
+ minecraft/loot_tables/blocks/brown_banner.json
+ minecraft/loot_tables/blocks/brown_bed.json
+ minecraft/loot_tables/blocks/brown_carpet.json
+ minecraft/loot_tables/blocks/brown_concrete_powder.json
+ minecraft/loot_tables/blocks/brown_concrete.json
+ minecraft/loot_tables/blocks/brown_glazed_terracotta.json
+ minecraft/loot_tables/blocks/brown_mushroom_block.json
+ minecraft/loot_tables/blocks/brown_mushroom.json
+ minecraft/loot_tables/blocks/brown_shulker_box.json
+ minecraft/loot_tables/blocks/brown_stained_glass_pane.json
+ minecraft/loot_tables/blocks/brown_stained_glass.json
+ minecraft/loot_tables/blocks/brown_terracotta.json
+ minecraft/loot_tables/blocks/brown_wool.json
+ minecraft/loot_tables/blocks/bubble_coral_block.json
+ minecraft/loot_tables/blocks/bubble_coral_fan.json
+ minecraft/loot_tables/blocks/bubble_coral.json
+ minecraft/loot_tables/blocks/cactus.json
+ minecraft/loot_tables/blocks/cake.json
+ minecraft/loot_tables/blocks/carrots.json
+ minecraft/loot_tables/blocks/carved_pumpkin.json
+ minecraft/loot_tables/blocks/cauldron.json
+ minecraft/loot_tables/blocks/chest.json
+ minecraft/loot_tables/blocks/chipped_anvil.json
+ minecraft/loot_tables/blocks/chiseled_quartz_block.json
+ minecraft/loot_tables/blocks/chiseled_red_sandstone.json
+ minecraft/loot_tables/blocks/chiseled_sandstone.json
+ minecraft/loot_tables/blocks/chiseled_stone_bricks.json
+ minecraft/loot_tables/blocks/chorus_flower.json
+ minecraft/loot_tables/blocks/chorus_plant.json
+ minecraft/loot_tables/blocks/clay.json
+ minecraft/loot_tables/blocks/coal_block.json
+ minecraft/loot_tables/blocks/coal_ore.json
+ minecraft/loot_tables/blocks/coarse_dirt.json
+ minecraft/loot_tables/blocks/cobblestone_slab.json
+ minecraft/loot_tables/blocks/cobblestone_stairs.json
+ minecraft/loot_tables/blocks/cobblestone_wall.json
+ minecraft/loot_tables/blocks/cobblestone.json
+ minecraft/loot_tables/blocks/cobweb.json
+ minecraft/loot_tables/blocks/cocoa.json
+ minecraft/loot_tables/blocks/comparator.json
+ minecraft/loot_tables/blocks/conduit.json
+ minecraft/loot_tables/blocks/cornflower.json
+ minecraft/loot_tables/blocks/cracked_stone_bricks.json
+ minecraft/loot_tables/blocks/crafting_table.json
+ minecraft/loot_tables/blocks/creeper_head.json
+ minecraft/loot_tables/blocks/cut_red_sandstone.json
+ minecraft/loot_tables/blocks/cut_sandstone.json
+ minecraft/loot_tables/blocks/cyan_banner.json
+ minecraft/loot_tables/blocks/cyan_bed.json
+ minecraft/loot_tables/blocks/cyan_carpet.json
+ minecraft/loot_tables/blocks/cyan_concrete_powder.json
+ minecraft/loot_tables/blocks/cyan_concrete.json
+ minecraft/loot_tables/blocks/cyan_glazed_terracotta.json
+ minecraft/loot_tables/blocks/cyan_shulker_box.json
+ minecraft/loot_tables/blocks/cyan_stained_glass_pane.json
+ minecraft/loot_tables/blocks/cyan_stained_glass.json
+ minecraft/loot_tables/blocks/cyan_terracotta.json
+ minecraft/loot_tables/blocks/cyan_wool.json
+ minecraft/loot_tables/blocks/damaged_anvil.json
+ minecraft/loot_tables/blocks/dandelion.json
+ minecraft/loot_tables/blocks/dark_oak_button.json
+ minecraft/loot_tables/blocks/dark_oak_door.json
+ minecraft/loot_tables/blocks/dark_oak_fence_gate.json
+ minecraft/loot_tables/blocks/dark_oak_fence.json
+ minecraft/loot_tables/blocks/dark_oak_leaves.json
+ minecraft/loot_tables/blocks/dark_oak_log.json
+ minecraft/loot_tables/blocks/dark_oak_planks.json
+ minecraft/loot_tables/blocks/dark_oak_pressure_plate.json
+ minecraft/loot_tables/blocks/dark_oak_sapling.json
+ minecraft/loot_tables/blocks/dark_oak_sign.json
+ minecraft/loot_tables/blocks/dark_oak_slab.json
+ minecraft/loot_tables/blocks/dark_oak_stairs.json
+ minecraft/loot_tables/blocks/dark_oak_trapdoor.json
+ minecraft/loot_tables/blocks/dark_oak_wood.json
+ minecraft/loot_tables/blocks/dark_prismarine_slab.json
+ minecraft/loot_tables/blocks/dark_prismarine_stairs.json
+ minecraft/loot_tables/blocks/dark_prismarine.json
+ minecraft/loot_tables/blocks/daylight_detector.json
+ minecraft/loot_tables/blocks/dead_brain_coral_block.json
+ minecraft/loot_tables/blocks/dead_brain_coral_fan.json
+ minecraft/loot_tables/blocks/dead_brain_coral.json
+ minecraft/loot_tables/blocks/dead_bubble_coral_block.json
+ minecraft/loot_tables/blocks/dead_bubble_coral_fan.json
+ minecraft/loot_tables/blocks/dead_bubble_coral.json
+ minecraft/loot_tables/blocks/dead_bush.json
+ minecraft/loot_tables/blocks/dead_fire_coral_block.json
+ minecraft/loot_tables/blocks/dead_fire_coral_fan.json
+ minecraft/loot_tables/blocks/dead_fire_coral.json
+ minecraft/loot_tables/blocks/dead_horn_coral_block.json
+ minecraft/loot_tables/blocks/dead_horn_coral_fan.json
+ minecraft/loot_tables/blocks/dead_horn_coral.json
+ minecraft/loot_tables/blocks/dead_tube_coral_block.json
+ minecraft/loot_tables/blocks/dead_tube_coral_fan.json
+ minecraft/loot_tables/blocks/dead_tube_coral.json
+ minecraft/loot_tables/blocks/detector_rail.json
+ minecraft/loot_tables/blocks/diamond_block.json
+ minecraft/loot_tables/blocks/diamond_ore.json
+ minecraft/loot_tables/blocks/diorite_slab.json
+ minecraft/loot_tables/blocks/diorite_stairs.json
+ minecraft/loot_tables/blocks/diorite_wall.json
+ minecraft/loot_tables/blocks/diorite.json
+ minecraft/loot_tables/blocks/dirt.json
+ minecraft/loot_tables/blocks/dispenser.json
+ minecraft/loot_tables/blocks/dragon_egg.json
+ minecraft/loot_tables/blocks/dragon_head.json
+ minecraft/loot_tables/blocks/dried_kelp_block.json
+ minecraft/loot_tables/blocks/dropper.json
+ minecraft/loot_tables/blocks/emerald_block.json
+ minecraft/loot_tables/blocks/emerald_ore.json
+ minecraft/loot_tables/blocks/enchanting_table.json
+ minecraft/loot_tables/blocks/end_rod.json
+ minecraft/loot_tables/blocks/end_stone_brick_slab.json
+ minecraft/loot_tables/blocks/end_stone_brick_stairs.json
+ minecraft/loot_tables/blocks/end_stone_brick_wall.json
+ minecraft/loot_tables/blocks/end_stone_bricks.json
+ minecraft/loot_tables/blocks/end_stone.json
+ minecraft/loot_tables/blocks/ender_chest.json
+ minecraft/loot_tables/blocks/farmland.json
+ minecraft/loot_tables/blocks/fern.json
+ minecraft/loot_tables/blocks/fire_coral_block.json
+ minecraft/loot_tables/blocks/fire_coral_fan.json
+ minecraft/loot_tables/blocks/fire_coral.json
+ minecraft/loot_tables/blocks/flower_pot.json
+ minecraft/loot_tables/blocks/frosted_ice.json
+ minecraft/loot_tables/blocks/furnace.json
+ minecraft/loot_tables/blocks/glass_pane.json
+ minecraft/loot_tables/blocks/glass.json
+ minecraft/loot_tables/blocks/glowstone.json
+ minecraft/loot_tables/blocks/gold_block.json
+ minecraft/loot_tables/blocks/gold_ore.json
+ minecraft/loot_tables/blocks/granite_slab.json
+ minecraft/loot_tables/blocks/granite_stairs.json
+ minecraft/loot_tables/blocks/granite_wall.json
+ minecraft/loot_tables/blocks/granite.json
+ minecraft/loot_tables/blocks/grass_block.json
+ minecraft/loot_tables/blocks/grass_path.json
+ minecraft/loot_tables/blocks/grass.json
+ minecraft/loot_tables/blocks/gravel.json
+ minecraft/loot_tables/blocks/gray_banner.json
+ minecraft/loot_tables/blocks/gray_bed.json
+ minecraft/loot_tables/blocks/gray_carpet.json
+ minecraft/loot_tables/blocks/gray_concrete_powder.json
+ minecraft/loot_tables/blocks/gray_concrete.json
+ minecraft/loot_tables/blocks/gray_glazed_terracotta.json
+ minecraft/loot_tables/blocks/gray_shulker_box.json
+ minecraft/loot_tables/blocks/gray_stained_glass_pane.json
+ minecraft/loot_tables/blocks/gray_stained_glass.json
+ minecraft/loot_tables/blocks/gray_terracotta.json
+ minecraft/loot_tables/blocks/gray_wool.json
+ minecraft/loot_tables/blocks/green_banner.json
+ minecraft/loot_tables/blocks/green_bed.json
+ minecraft/loot_tables/blocks/green_carpet.json
+ minecraft/loot_tables/blocks/green_concrete_powder.json
+ minecraft/loot_tables/blocks/green_concrete.json
+ minecraft/loot_tables/blocks/green_glazed_terracotta.json
+ minecraft/loot_tables/blocks/green_shulker_box.json
+ minecraft/loot_tables/blocks/green_stained_glass_pane.json
+ minecraft/loot_tables/blocks/green_stained_glass.json
+ minecraft/loot_tables/blocks/green_terracotta.json
+ minecraft/loot_tables/blocks/green_wool.json
+ minecraft/loot_tables/blocks/hay_block.json
+ minecraft/loot_tables/blocks/heavy_weighted_pressure_plate.json
+ minecraft/loot_tables/blocks/hopper.json
+ minecraft/loot_tables/blocks/horn_coral_block.json
+ minecraft/loot_tables/blocks/horn_coral_fan.json
+ minecraft/loot_tables/blocks/horn_coral.json
+ minecraft/loot_tables/blocks/ice.json
+ minecraft/loot_tables/blocks/infested_chiseled_stone_bricks.json
+ minecraft/loot_tables/blocks/infested_cobblestone.json
+ minecraft/loot_tables/blocks/infested_cracked_stone_bricks.json
+ minecraft/loot_tables/blocks/infested_mossy_stone_bricks.json
+ minecraft/loot_tables/blocks/infested_stone_bricks.json
+ minecraft/loot_tables/blocks/infested_stone.json
+ minecraft/loot_tables/blocks/iron_bars.json
+ minecraft/loot_tables/blocks/iron_block.json
+ minecraft/loot_tables/blocks/iron_door.json
+ minecraft/loot_tables/blocks/iron_ore.json
+ minecraft/loot_tables/blocks/iron_trapdoor.json
+ minecraft/loot_tables/blocks/jack_o_lantern.json
+ minecraft/loot_tables/blocks/jukebox.json
+ minecraft/loot_tables/blocks/jungle_button.json
+ minecraft/loot_tables/blocks/jungle_door.json
+ minecraft/loot_tables/blocks/jungle_fence_gate.json
+ minecraft/loot_tables/blocks/jungle_fence.json
+ minecraft/loot_tables/blocks/jungle_leaves.json
+ minecraft/loot_tables/blocks/jungle_log.json
+ minecraft/loot_tables/blocks/jungle_planks.json
+ minecraft/loot_tables/blocks/jungle_pressure_plate.json
+ minecraft/loot_tables/blocks/jungle_sapling.json
+ minecraft/loot_tables/blocks/jungle_sign.json
+ minecraft/loot_tables/blocks/jungle_slab.json
+ minecraft/loot_tables/blocks/jungle_stairs.json
+ minecraft/loot_tables/blocks/jungle_trapdoor.json
+ minecraft/loot_tables/blocks/jungle_wood.json
+ minecraft/loot_tables/blocks/kelp_plant.json
+ minecraft/loot_tables/blocks/kelp.json
+ minecraft/loot_tables/blocks/ladder.json
+ minecraft/loot_tables/blocks/lapis_block.json
+ minecraft/loot_tables/blocks/lapis_ore.json
+ minecraft/loot_tables/blocks/large_fern.json
+ minecraft/loot_tables/blocks/lever.json
+ minecraft/loot_tables/blocks/light_blue_banner.json
+ minecraft/loot_tables/blocks/light_blue_bed.json
+ minecraft/loot_tables/blocks/light_blue_carpet.json
+ minecraft/loot_tables/blocks/light_blue_concrete_powder.json
+ minecraft/loot_tables/blocks/light_blue_concrete.json
+ minecraft/loot_tables/blocks/light_blue_glazed_terracotta.json
+ minecraft/loot_tables/blocks/light_blue_shulker_box.json
+ minecraft/loot_tables/blocks/light_blue_stained_glass_pane.json
+ minecraft/loot_tables/blocks/light_blue_stained_glass.json
+ minecraft/loot_tables/blocks/light_blue_terracotta.json
+ minecraft/loot_tables/blocks/light_blue_wool.json
+ minecraft/loot_tables/blocks/light_gray_banner.json
+ minecraft/loot_tables/blocks/light_gray_bed.json
+ minecraft/loot_tables/blocks/light_gray_carpet.json
+ minecraft/loot_tables/blocks/light_gray_concrete_powder.json
+ minecraft/loot_tables/blocks/light_gray_concrete.json
+ minecraft/loot_tables/blocks/light_gray_glazed_terracotta.json
+ minecraft/loot_tables/blocks/light_gray_shulker_box.json
+ minecraft/loot_tables/blocks/light_gray_stained_glass_pane.json
+ minecraft/loot_tables/blocks/light_gray_stained_glass.json
+ minecraft/loot_tables/blocks/light_gray_terracotta.json
+ minecraft/loot_tables/blocks/light_gray_wool.json
+ minecraft/loot_tables/blocks/light_weighted_pressure_plate.json
+ minecraft/loot_tables/blocks/lilac.json
+ minecraft/loot_tables/blocks/lily_of_the_valley.json
+ minecraft/loot_tables/blocks/lily_pad.json
+ minecraft/loot_tables/blocks/lime_banner.json
+ minecraft/loot_tables/blocks/lime_bed.json
+ minecraft/loot_tables/blocks/lime_carpet.json
+ minecraft/loot_tables/blocks/lime_concrete_powder.json
+ minecraft/loot_tables/blocks/lime_concrete.json
+ minecraft/loot_tables/blocks/lime_glazed_terracotta.json
+ minecraft/loot_tables/blocks/lime_shulker_box.json
+ minecraft/loot_tables/blocks/lime_stained_glass_pane.json
+ minecraft/loot_tables/blocks/lime_stained_glass.json
+ minecraft/loot_tables/blocks/lime_terracotta.json
+ minecraft/loot_tables/blocks/lime_wool.json
+ minecraft/loot_tables/blocks/loom.json
+ minecraft/loot_tables/blocks/magenta_banner.json
+ minecraft/loot_tables/blocks/magenta_bed.json
+ minecraft/loot_tables/blocks/magenta_carpet.json
+ minecraft/loot_tables/blocks/magenta_concrete_powder.json
+ minecraft/loot_tables/blocks/magenta_concrete.json
+ minecraft/loot_tables/blocks/magenta_glazed_terracotta.json
+ minecraft/loot_tables/blocks/magenta_shulker_box.json
+ minecraft/loot_tables/blocks/magenta_stained_glass_pane.json
+ minecraft/loot_tables/blocks/magenta_stained_glass.json
+ minecraft/loot_tables/blocks/magenta_terracotta.json
+ minecraft/loot_tables/blocks/magenta_wool.json
+ minecraft/loot_tables/blocks/magma_block.json
+ minecraft/loot_tables/blocks/melon_stem.json
+ minecraft/loot_tables/blocks/melon.json
+ minecraft/loot_tables/blocks/mossy_cobblestone_slab.json
+ minecraft/loot_tables/blocks/mossy_cobblestone_stairs.json
+ minecraft/loot_tables/blocks/mossy_cobblestone_wall.json
+ minecraft/loot_tables/blocks/mossy_cobblestone.json
+ minecraft/loot_tables/blocks/mossy_stone_brick_slab.json
+ minecraft/loot_tables/blocks/mossy_stone_brick_stairs.json
+ minecraft/loot_tables/blocks/mossy_stone_brick_wall.json
+ minecraft/loot_tables/blocks/mossy_stone_bricks.json
+ minecraft/loot_tables/blocks/mushroom_stem.json
+ minecraft/loot_tables/blocks/mycelium.json
+ minecraft/loot_tables/blocks/nether_brick_fence.json
+ minecraft/loot_tables/blocks/nether_brick_slab.json
+ minecraft/loot_tables/blocks/nether_brick_stairs.json
+ minecraft/loot_tables/blocks/nether_brick_wall.json
+ minecraft/loot_tables/blocks/nether_bricks.json
+ minecraft/loot_tables/blocks/nether_quartz_ore.json
+ minecraft/loot_tables/blocks/nether_wart_block.json
+ minecraft/loot_tables/blocks/nether_wart.json
+ minecraft/loot_tables/blocks/netherrack.json
+ minecraft/loot_tables/blocks/note_block.json
+ minecraft/loot_tables/blocks/oak_button.json
+ minecraft/loot_tables/blocks/oak_door.json
+ minecraft/loot_tables/blocks/oak_fence_gate.json
+ minecraft/loot_tables/blocks/oak_fence.json
+ minecraft/loot_tables/blocks/oak_leaves.json
+ minecraft/loot_tables/blocks/oak_log.json
+ minecraft/loot_tables/blocks/oak_planks.json
+ minecraft/loot_tables/blocks/oak_pressure_plate.json
+ minecraft/loot_tables/blocks/oak_sapling.json
+ minecraft/loot_tables/blocks/oak_sign.json
+ minecraft/loot_tables/blocks/oak_slab.json
+ minecraft/loot_tables/blocks/oak_stairs.json
+ minecraft/loot_tables/blocks/oak_trapdoor.json
+ minecraft/loot_tables/blocks/oak_wood.json
+ minecraft/loot_tables/blocks/observer.json
+ minecraft/loot_tables/blocks/obsidian.json
+ minecraft/loot_tables/blocks/orange_banner.json
+ minecraft/loot_tables/blocks/orange_bed.json
+ minecraft/loot_tables/blocks/orange_carpet.json
+ minecraft/loot_tables/blocks/orange_concrete_powder.json
+ minecraft/loot_tables/blocks/orange_concrete.json
+ minecraft/loot_tables/blocks/orange_glazed_terracotta.json
+ minecraft/loot_tables/blocks/orange_shulker_box.json
+ minecraft/loot_tables/blocks/orange_stained_glass_pane.json
+ minecraft/loot_tables/blocks/orange_stained_glass.json
+ minecraft/loot_tables/blocks/orange_terracotta.json
+ minecraft/loot_tables/blocks/orange_tulip.json
+ minecraft/loot_tables/blocks/orange_wool.json
+ minecraft/loot_tables/blocks/oxeye_daisy.json
+ minecraft/loot_tables/blocks/packed_ice.json
+ minecraft/loot_tables/blocks/peony.json
+ minecraft/loot_tables/blocks/petrified_oak_slab.json
+ minecraft/loot_tables/blocks/pink_banner.json
+ minecraft/loot_tables/blocks/pink_bed.json
+ minecraft/loot_tables/blocks/pink_carpet.json
+ minecraft/loot_tables/blocks/pink_concrete_powder.json
+ minecraft/loot_tables/blocks/pink_concrete.json
+ minecraft/loot_tables/blocks/pink_glazed_terracotta.json
+ minecraft/loot_tables/blocks/pink_shulker_box.json
+ minecraft/loot_tables/blocks/pink_stained_glass_pane.json
+ minecraft/loot_tables/blocks/pink_stained_glass.json
+ minecraft/loot_tables/blocks/pink_terracotta.json
+ minecraft/loot_tables/blocks/pink_tulip.json
+ minecraft/loot_tables/blocks/pink_wool.json
+ minecraft/loot_tables/blocks/piston.json
+ minecraft/loot_tables/blocks/player_head.json
+ minecraft/loot_tables/blocks/podzol.json
+ minecraft/loot_tables/blocks/polished_andesite_slab.json
+ minecraft/loot_tables/blocks/polished_andesite_stairs.json
+ minecraft/loot_tables/blocks/polished_andesite.json
+ minecraft/loot_tables/blocks/polished_diorite_slab.json
+ minecraft/loot_tables/blocks/polished_diorite_stairs.json
+ minecraft/loot_tables/blocks/polished_diorite.json
+ minecraft/loot_tables/blocks/polished_granite_slab.json
+ minecraft/loot_tables/blocks/polished_granite_stairs.json
+ minecraft/loot_tables/blocks/polished_granite.json
+ minecraft/loot_tables/blocks/poppy.json
+ minecraft/loot_tables/blocks/potatoes.json
+ minecraft/loot_tables/blocks/potted_acacia_sapling.json
+ minecraft/loot_tables/blocks/potted_allium.json
+ minecraft/loot_tables/blocks/potted_azure_bluet.json
+ minecraft/loot_tables/blocks/potted_bamboo.json
+ minecraft/loot_tables/blocks/potted_birch_sapling.json
+ minecraft/loot_tables/blocks/potted_blue_orchid.json
+ minecraft/loot_tables/blocks/potted_brown_mushroom.json
+ minecraft/loot_tables/blocks/potted_cactus.json
+ minecraft/loot_tables/blocks/potted_cornflower.json
+ minecraft/loot_tables/blocks/potted_dandelion.json
+ minecraft/loot_tables/blocks/potted_dark_oak_sapling.json
+ minecraft/loot_tables/blocks/potted_dead_bush.json
+ minecraft/loot_tables/blocks/potted_fern.json
+ minecraft/loot_tables/blocks/potted_jungle_sapling.json
+ minecraft/loot_tables/blocks/potted_lily_of_the_valley.json
+ minecraft/loot_tables/blocks/potted_oak_sapling.json
+ minecraft/loot_tables/blocks/potted_orange_tulip.json
+ minecraft/loot_tables/blocks/potted_oxeye_daisy.json
+ minecraft/loot_tables/blocks/potted_pink_tulip.json
+ minecraft/loot_tables/blocks/potted_poppy.json
+ minecraft/loot_tables/blocks/potted_red_mushroom.json
+ minecraft/loot_tables/blocks/potted_red_tulip.json
+ minecraft/loot_tables/blocks/potted_spruce_sapling.json
+ minecraft/loot_tables/blocks/potted_white_tulip.json
+ minecraft/loot_tables/blocks/potted_wither_rose.json
+ minecraft/loot_tables/blocks/powered_rail.json
+ minecraft/loot_tables/blocks/prismarine_brick_slab.json
+ minecraft/loot_tables/blocks/prismarine_brick_stairs.json
+ minecraft/loot_tables/blocks/prismarine_bricks.json
+ minecraft/loot_tables/blocks/prismarine_slab.json
+ minecraft/loot_tables/blocks/prismarine_stairs.json
+ minecraft/loot_tables/blocks/prismarine_wall.json
+ minecraft/loot_tables/blocks/prismarine.json
+ minecraft/loot_tables/blocks/pumpkin_stem.json
+ minecraft/loot_tables/blocks/pumpkin.json
+ minecraft/loot_tables/blocks/purple_banner.json
+ minecraft/loot_tables/blocks/purple_bed.json
+ minecraft/loot_tables/blocks/purple_carpet.json
+ minecraft/loot_tables/blocks/purple_concrete_powder.json
+ minecraft/loot_tables/blocks/purple_concrete.json
+ minecraft/loot_tables/blocks/purple_glazed_terracotta.json
+ minecraft/loot_tables/blocks/purple_shulker_box.json
+ minecraft/loot_tables/blocks/purple_stained_glass_pane.json
+ minecraft/loot_tables/blocks/purple_stained_glass.json
+ minecraft/loot_tables/blocks/purple_terracotta.json
+ minecraft/loot_tables/blocks/purple_wool.json
+ minecraft/loot_tables/blocks/purpur_block.json
+ minecraft/loot_tables/blocks/purpur_pillar.json
+ minecraft/loot_tables/blocks/purpur_slab.json
+ minecraft/loot_tables/blocks/purpur_stairs.json
+ minecraft/loot_tables/blocks/quartz_block.json
+ minecraft/loot_tables/blocks/quartz_pillar.json
+ minecraft/loot_tables/blocks/quartz_slab.json
+ minecraft/loot_tables/blocks/quartz_stairs.json
+ minecraft/loot_tables/blocks/rail.json
+ minecraft/loot_tables/blocks/red_banner.json
+ minecraft/loot_tables/blocks/red_bed.json
+ minecraft/loot_tables/blocks/red_carpet.json
+ minecraft/loot_tables/blocks/red_concrete_powder.json
+ minecraft/loot_tables/blocks/red_concrete.json
+ minecraft/loot_tables/blocks/red_glazed_terracotta.json
+ minecraft/loot_tables/blocks/red_mushroom_block.json
+ minecraft/loot_tables/blocks/red_mushroom.json
+ minecraft/loot_tables/blocks/red_nether_brick_slab.json
+ minecraft/loot_tables/blocks/red_nether_brick_stairs.json
+ minecraft/loot_tables/blocks/red_nether_brick_wall.json
+ minecraft/loot_tables/blocks/red_nether_bricks.json
+ minecraft/loot_tables/blocks/red_sand.json
+ minecraft/loot_tables/blocks/red_sandstone_slab.json
+ minecraft/loot_tables/blocks/red_sandstone_stairs.json
+ minecraft/loot_tables/blocks/red_sandstone_wall.json
+ minecraft/loot_tables/blocks/red_sandstone.json
+ minecraft/loot_tables/blocks/red_shulker_box.json
+ minecraft/loot_tables/blocks/red_stained_glass_pane.json
+ minecraft/loot_tables/blocks/red_stained_glass.json
+ minecraft/loot_tables/blocks/red_terracotta.json
+ minecraft/loot_tables/blocks/red_tulip.json
+ minecraft/loot_tables/blocks/red_wool.json
+ minecraft/loot_tables/blocks/redstone_block.json
+ minecraft/loot_tables/blocks/redstone_lamp.json
+ minecraft/loot_tables/blocks/redstone_ore.json
+ minecraft/loot_tables/blocks/redstone_torch.json
+ minecraft/loot_tables/blocks/redstone_wire.json
+ minecraft/loot_tables/blocks/repeater.json
+ minecraft/loot_tables/blocks/rose_bush.json
+ minecraft/loot_tables/blocks/sand.json
+ minecraft/loot_tables/blocks/sandstone_slab.json
+ minecraft/loot_tables/blocks/sandstone_stairs.json
+ minecraft/loot_tables/blocks/sandstone_wall.json
+ minecraft/loot_tables/blocks/sandstone.json
+ minecraft/loot_tables/blocks/sea_lantern.json
+ minecraft/loot_tables/blocks/sea_pickle.json
+ minecraft/loot_tables/blocks/seagrass.json
+ minecraft/loot_tables/blocks/shulker_box.json
+ minecraft/loot_tables/blocks/skeleton_skull.json
+ minecraft/loot_tables/blocks/slime_block.json
+ minecraft/loot_tables/blocks/smooth_quartz_slab.json
+ minecraft/loot_tables/blocks/smooth_quartz_stairs.json
+ minecraft/loot_tables/blocks/smooth_quartz.json
+ minecraft/loot_tables/blocks/smooth_red_sandstone_slab.json
+ minecraft/loot_tables/blocks/smooth_red_sandstone_stairs.json
+ minecraft/loot_tables/blocks/smooth_red_sandstone.json
+ minecraft/loot_tables/blocks/smooth_sandstone_slab.json
+ minecraft/loot_tables/blocks/smooth_sandstone_stairs.json
+ minecraft/loot_tables/blocks/smooth_sandstone.json
+ minecraft/loot_tables/blocks/smooth_stone_slab.json
+ minecraft/loot_tables/blocks/smooth_stone.json
+ minecraft/loot_tables/blocks/snow_block.json
+ minecraft/loot_tables/blocks/snow.json
+ minecraft/loot_tables/blocks/soul_sand.json
+ minecraft/loot_tables/blocks/spawner.json
+ minecraft/loot_tables/blocks/sponge.json
+ minecraft/loot_tables/blocks/spruce_button.json
+ minecraft/loot_tables/blocks/spruce_door.json
+ minecraft/loot_tables/blocks/spruce_fence_gate.json
+ minecraft/loot_tables/blocks/spruce_fence.json
+ minecraft/loot_tables/blocks/spruce_leaves.json
+ minecraft/loot_tables/blocks/spruce_log.json
+ minecraft/loot_tables/blocks/spruce_planks.json
+ minecraft/loot_tables/blocks/spruce_pressure_plate.json
+ minecraft/loot_tables/blocks/spruce_sapling.json
+ minecraft/loot_tables/blocks/spruce_sign.json
+ minecraft/loot_tables/blocks/spruce_slab.json
+ minecraft/loot_tables/blocks/spruce_stairs.json
+ minecraft/loot_tables/blocks/spruce_trapdoor.json
+ minecraft/loot_tables/blocks/spruce_wood.json
+ minecraft/loot_tables/blocks/sticky_piston.json
+ minecraft/loot_tables/blocks/stone_brick_slab.json
+ minecraft/loot_tables/blocks/stone_brick_stairs.json
+ minecraft/loot_tables/blocks/stone_brick_wall.json
+ minecraft/loot_tables/blocks/stone_bricks.json
+ minecraft/loot_tables/blocks/stone_button.json
+ minecraft/loot_tables/blocks/stone_pressure_plate.json
+ minecraft/loot_tables/blocks/stone_slab.json
+ minecraft/loot_tables/blocks/stone_stairs.json
+ minecraft/loot_tables/blocks/stone.json
+ minecraft/loot_tables/blocks/stripped_acacia_log.json
+ minecraft/loot_tables/blocks/stripped_acacia_wood.json
+ minecraft/loot_tables/blocks/stripped_birch_log.json
+ minecraft/loot_tables/blocks/stripped_birch_wood.json
+ minecraft/loot_tables/blocks/stripped_dark_oak_log.json
+ minecraft/loot_tables/blocks/stripped_dark_oak_wood.json
+ minecraft/loot_tables/blocks/stripped_jungle_log.json
+ minecraft/loot_tables/blocks/stripped_jungle_wood.json
+ minecraft/loot_tables/blocks/stripped_oak_log.json
+ minecraft/loot_tables/blocks/stripped_oak_wood.json
+ minecraft/loot_tables/blocks/stripped_spruce_log.json
+ minecraft/loot_tables/blocks/stripped_spruce_wood.json
+ minecraft/loot_tables/blocks/sugar_cane.json
+ minecraft/loot_tables/blocks/sunflower.json
+ minecraft/loot_tables/blocks/tall_grass.json
+ minecraft/loot_tables/blocks/tall_seagrass.json
+ minecraft/loot_tables/blocks/terracotta.json
+ minecraft/loot_tables/blocks/tnt.json
+ minecraft/loot_tables/blocks/torch.json
+ minecraft/loot_tables/blocks/trapped_chest.json
+ minecraft/loot_tables/blocks/tripwire_hook.json
+ minecraft/loot_tables/blocks/tripwire.json
+ minecraft/loot_tables/blocks/tube_coral_block.json
+ minecraft/loot_tables/blocks/tube_coral_fan.json
+ minecraft/loot_tables/blocks/tube_coral.json
+ minecraft/loot_tables/blocks/turtle_egg.json
+ minecraft/loot_tables/blocks/vine.json
+ minecraft/loot_tables/blocks/wet_sponge.json
+ minecraft/loot_tables/blocks/wheat.json
+ minecraft/loot_tables/blocks/white_banner.json
+ minecraft/loot_tables/blocks/white_bed.json
+ minecraft/loot_tables/blocks/white_carpet.json
+ minecraft/loot_tables/blocks/white_concrete_powder.json
+ minecraft/loot_tables/blocks/white_concrete.json
+ minecraft/loot_tables/blocks/white_glazed_terracotta.json
+ minecraft/loot_tables/blocks/white_shulker_box.json
+ minecraft/loot_tables/blocks/white_stained_glass_pane.json
+ minecraft/loot_tables/blocks/white_stained_glass.json
+ minecraft/loot_tables/blocks/white_terracotta.json
+ minecraft/loot_tables/blocks/white_tulip.json
+ minecraft/loot_tables/blocks/white_wool.json
+ minecraft/loot_tables/blocks/wither_rose.json
+ minecraft/loot_tables/blocks/wither_skeleton_skull.json
+ minecraft/loot_tables/blocks/yellow_banner.json
+ minecraft/loot_tables/blocks/yellow_bed.json
+ minecraft/loot_tables/blocks/yellow_carpet.json
+ minecraft/loot_tables/blocks/yellow_concrete_powder.json
+ minecraft/loot_tables/blocks/yellow_concrete.json
+ minecraft/loot_tables/blocks/yellow_glazed_terracotta.json
+ minecraft/loot_tables/blocks/yellow_shulker_box.json
+ minecraft/loot_tables/blocks/yellow_stained_glass_pane.json
+ minecraft/loot_tables/blocks/yellow_stained_glass.json
+ minecraft/loot_tables/blocks/yellow_terracotta.json
+ minecraft/loot_tables/blocks/yellow_wool.json
+ minecraft/loot_tables/blocks/zombie_head.json
- minecraft/loot_tables/empty.json
+ minecraft/loot_tables/entities/illager_beast.json
+ minecraft/loot_tables/entities/panda.json
+ minecraft/recipes/acacia_sign.json
+ minecraft/recipes/andesite_slab.json
+ minecraft/recipes/andesite_stairs.json
+ minecraft/recipes/andesite_wall.json
- minecraft/recipes/banner_add_pattern.json
+ minecraft/recipes/birch_sign.json
+ minecraft/recipes/black_carpet_from_white_carpet.json
+ minecraft/recipes/black_dye_from_wither_rose.json
+ minecraft/recipes/black_dye.json
+ minecraft/recipes/black_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/blue_carpet_from_white_carpet.json
+ minecraft/recipes/blue_dye_from_cornflower.json
+ minecraft/recipes/blue_dye.json
+ minecraft/recipes/blue_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/brick_wall.json
+ minecraft/recipes/brown_carpet_from_white_carpet.json
+ minecraft/recipes/brown_dye.json
+ minecraft/recipes/brown_stained_glass_pane_from_glass_pane.json
- minecraft/recipes/cactus_green.json
+ minecraft/recipes/creeper_banner_pattern.json
+ minecraft/recipes/crossbow.json
+ minecraft/recipes/cyan_carpet_from_white_carpet.json
+ minecraft/recipes/cyan_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/dark_oak_sign.json
+ minecraft/recipes/diorite_slab.json
+ minecraft/recipes/diorite_stairs.json
+ minecraft/recipes/diorite_wall.json
+ minecraft/recipes/end_stone_brick_slab.json
+ minecraft/recipes/end_stone_brick_stairs.json
+ minecraft/recipes/end_stone_brick_wall.json
+ minecraft/recipes/flower_banner_pattern.json
+ minecraft/recipes/granite_slab.json
+ minecraft/recipes/granite_stairs.json
+ minecraft/recipes/granite_wall.json
+ minecraft/recipes/gray_carpet_from_white_carpet.json
+ minecraft/recipes/gray_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/green_carpet_from_white_carpet.json
+ minecraft/recipes/green_dye.json
+ minecraft/recipes/green_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/jungle_sign.json
+ minecraft/recipes/light_blue_carpet_from_white_carpet.json
+ minecraft/recipes/light_blue_dye_from_blue_white_dye.json
- minecraft/recipes/light_blue_dye_from_lapis_bonemeal.json
+ minecraft/recipes/light_blue_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/light_gray_carpet_from_white_carpet.json
+ minecraft/recipes/light_gray_dye_from_black_white_dye.json
- minecraft/recipes/light_gray_dye_from_gray_bonemeal.json
+ minecraft/recipes/light_gray_dye_from_gray_white_dye.json
- minecraft/recipes/light_gray_dye_from_ink_bonemeal.json
+ minecraft/recipes/light_gray_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/lime_carpet_from_white_carpet.json
+ minecraft/recipes/lime_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/loom.json
+ minecraft/recipes/magenta_carpet_from_white_carpet.json
+ minecraft/recipes/magenta_dye_from_blue_red_pink.json
+ minecraft/recipes/magenta_dye_from_blue_red_white_dye.json
- minecraft/recipes/magenta_dye_from_lapis_ink_bonemeal.json
- minecraft/recipes/magenta_dye_from_lapis_red_pink.json
+ minecraft/recipes/magenta_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/mojang_banner_pattern.json
+ minecraft/recipes/mossy_cobblestone_slab.json
+ minecraft/recipes/mossy_cobblestone_stairs.json
+ minecraft/recipes/mossy_stone_brick_slab.json
+ minecraft/recipes/mossy_stone_brick_stairs.json
+ minecraft/recipes/mossy_stone_brick_wall.json
+ minecraft/recipes/nether_brick_wall.json
+ minecraft/recipes/oak_sign.json
+ minecraft/recipes/orange_carpet_from_white_carpet.json
+ minecraft/recipes/orange_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/pink_carpet_from_white_carpet.json
- minecraft/recipes/pink_dye_from_red_bonemeal.json
+ minecraft/recipes/pink_dye_from_red_white_dye.json
+ minecraft/recipes/pink_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/polished_andesite_slab.json
+ minecraft/recipes/polished_andesite_stairs.json
+ minecraft/recipes/polished_diorite_slab.json
+ minecraft/recipes/polished_diorite_stairs.json
+ minecraft/recipes/polished_granite_slab.json
+ minecraft/recipes/polished_granite_stairs.json
+ minecraft/recipes/prismarine_wall.json
+ minecraft/recipes/purple_carpet_from_white_carpet.json
+ minecraft/recipes/purple_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/red_carpet_from_white_carpet.json
+ minecraft/recipes/red_nether_brick_slab.json
+ minecraft/recipes/red_nether_brick_stairs.json
+ minecraft/recipes/red_nether_brick_wall.json
+ minecraft/recipes/red_sandstone_wall.json
+ minecraft/recipes/red_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/sandstone_wall.json
- minecraft/recipes/sign.json
+ minecraft/recipes/skull_banner_pattern.json
+ minecraft/recipes/smooth_quartz_slab.json
+ minecraft/recipes/smooth_quartz_stairs.json
+ minecraft/recipes/smooth_quartz.json
+ minecraft/recipes/smooth_red_sandstone_slab.json
+ minecraft/recipes/smooth_red_sandstone_stairs.json
+ minecraft/recipes/smooth_red_sandstone.json
+ minecraft/recipes/smooth_sandstone_slab.json
+ minecraft/recipes/smooth_sandstone_stairs.json
+ minecraft/recipes/smooth_sandstone.json
+ minecraft/recipes/smooth_stone_slab.json
+ minecraft/recipes/smooth_stone.json
+ minecraft/recipes/spruce_sign.json
+ minecraft/recipes/stick_from_bamboo_item.json
+ minecraft/recipes/stone_brick_wall.json
+ minecraft/recipes/stone_stairs.json
+ minecraft/recipes/suspicious_stew.json
+ minecraft/recipes/white_dye_from_lily_of_the_valley.json
+ minecraft/recipes/white_dye.json
+ minecraft/recipes/white_stained_glass_pane_from_glass_pane.json
+ minecraft/recipes/yellow_carpet_from_white_carpet.json
+ minecraft/recipes/yellow_stained_glass_pane_from_glass_pane.json
+ minecraft/tags/blocks/bamboo_plantable_on.json
+ minecraft/tags/blocks/dirt_like.json
+ minecraft/tags/blocks/signs.json
+ minecraft/tags/blocks/small_flowers.json
+ minecraft/tags/blocks/standing_signs.json
+ minecraft/tags/blocks/wall_signs.json
+ minecraft/tags/blocks/walls.json
+ minecraft/tags/entity_types/skeletons.json
+ minecraft/tags/items/music_discs.json
+ minecraft/tags/items/signs.json
+ minecraft/tags/items/small_flowers.json
+ minecraft/tags/items/walls.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/acacia_sign.json
+ minecraft/blockstates/acacia_wall_sign.json
+ minecraft/blockstates/andesite_slab.json
+ minecraft/blockstates/andesite_stairs.json
+ minecraft/blockstates/andesite_wall.json
+ minecraft/blockstates/bamboo_sapling.json
+ minecraft/blockstates/bamboo.json
+ minecraft/blockstates/birch_sign.json
+ minecraft/blockstates/birch_wall_sign.json
+ minecraft/blockstates/brick_wall.json
+ minecraft/blockstates/cornflower.json
+ minecraft/blockstates/dark_oak_sign.json
+ minecraft/blockstates/dark_oak_wall_sign.json
+ minecraft/blockstates/diorite_slab.json
+ minecraft/blockstates/diorite_stairs.json
+ minecraft/blockstates/diorite_wall.json
+ minecraft/blockstates/end_stone_brick_slab.json
+ minecraft/blockstates/end_stone_brick_stairs.json
+ minecraft/blockstates/end_stone_brick_wall.json
+ minecraft/blockstates/granite_slab.json
+ minecraft/blockstates/granite_stairs.json
+ minecraft/blockstates/granite_wall.json
+ minecraft/blockstates/jungle_sign.json
+ minecraft/blockstates/jungle_wall_sign.json
+ minecraft/blockstates/lily_of_the_valley.json
+ minecraft/blockstates/loom.json
+ minecraft/blockstates/mossy_cobblestone_slab.json
+ minecraft/blockstates/mossy_cobblestone_stairs.json
+ minecraft/blockstates/mossy_stone_brick_slab.json
+ minecraft/blockstates/mossy_stone_brick_stairs.json
+ minecraft/blockstates/mossy_stone_brick_wall.json
+ minecraft/blockstates/nether_brick_wall.json
+ minecraft/blockstates/oak_sign.json
+ minecraft/blockstates/oak_wall_sign.json
+ minecraft/blockstates/polished_andesite_slab.json
+ minecraft/blockstates/polished_andesite_stairs.json
+ minecraft/blockstates/polished_diorite_slab.json
+ minecraft/blockstates/polished_diorite_stairs.json
+ minecraft/blockstates/polished_granite_slab.json
+ minecraft/blockstates/polished_granite_stairs.json
+ minecraft/blockstates/potted_bamboo.json
+ minecraft/blockstates/potted_cornflower.json
+ minecraft/blockstates/potted_lily_of_the_valley.json
+ minecraft/blockstates/potted_wither_rose.json
+ minecraft/blockstates/prismarine_wall.json
+ minecraft/blockstates/red_nether_brick_slab.json
+ minecraft/blockstates/red_nether_brick_stairs.json
+ minecraft/blockstates/red_nether_brick_wall.json
+ minecraft/blockstates/red_sandstone_wall.json
+ minecraft/blockstates/sandstone_wall.json
- minecraft/blockstates/sign.json
+ minecraft/blockstates/smooth_quartz_slab.json
+ minecraft/blockstates/smooth_quartz_stairs.json
+ minecraft/blockstates/smooth_red_sandstone_slab.json
+ minecraft/blockstates/smooth_red_sandstone_stairs.json
+ minecraft/blockstates/smooth_sandstone_slab.json
+ minecraft/blockstates/smooth_sandstone_stairs.json
+ minecraft/blockstates/smooth_stone_slab.json
+ minecraft/blockstates/spruce_sign.json
+ minecraft/blockstates/spruce_wall_sign.json
+ minecraft/blockstates/stone_brick_wall.json
+ minecraft/blockstates/stone_stairs.json
- minecraft/blockstates/wall_sign.json
+ minecraft/blockstates/wither_rose.json
+ minecraft/models/block/acacia_sign.json
+ minecraft/models/block/andesite_slab_top.json
+ minecraft/models/block/andesite_slab.json
+ minecraft/models/block/andesite_stairs_inner.json
+ minecraft/models/block/andesite_stairs_outer.json
+ minecraft/models/block/andesite_stairs.json
+ minecraft/models/block/andesite_wall_inventory.json
+ minecraft/models/block/andesite_wall_post.json
+ minecraft/models/block/andesite_wall_side.json
+ minecraft/models/block/bamboo_large_leaves.json
+ minecraft/models/block/bamboo_sapling.json
+ minecraft/models/block/bamboo_small_leaves.json
+ minecraft/models/block/bamboo1_age0.json
+ minecraft/models/block/bamboo1_age1.json
+ minecraft/models/block/bamboo2_age0.json
+ minecraft/models/block/bamboo2_age1.json
+ minecraft/models/block/bamboo3_age0.json
+ minecraft/models/block/bamboo3_age1.json
+ minecraft/models/block/bamboo4_age0.json
+ minecraft/models/block/bamboo4_age1.json
+ minecraft/models/block/birch_sign.json
+ minecraft/models/block/brick_wall_inventory.json
+ minecraft/models/block/brick_wall_post.json
+ minecraft/models/block/brick_wall_side.json
+ minecraft/models/block/cornflower.json
+ minecraft/models/block/dark_oak_sign.json
+ minecraft/models/block/diorite_slab_top.json
+ minecraft/models/block/diorite_slab.json
+ minecraft/models/block/diorite_stairs_inner.json
+ minecraft/models/block/diorite_stairs_outer.json
+ minecraft/models/block/diorite_stairs.json
+ minecraft/models/block/diorite_wall_inventory.json
+ minecraft/models/block/diorite_wall_post.json
+ minecraft/models/block/diorite_wall_side.json
+ minecraft/models/block/end_stone_brick_slab_top.json
+ minecraft/models/block/end_stone_brick_slab.json
+ minecraft/models/block/end_stone_brick_stairs_inner.json
+ minecraft/models/block/end_stone_brick_stairs_outer.json
+ minecraft/models/block/end_stone_brick_stairs.json
+ minecraft/models/block/end_stone_brick_wall_inventory.json
+ minecraft/models/block/end_stone_brick_wall_post.json
+ minecraft/models/block/end_stone_brick_wall_side.json
+ minecraft/models/block/granite_slab_top.json
+ minecraft/models/block/granite_slab.json
+ minecraft/models/block/granite_stairs_inner.json
+ minecraft/models/block/granite_stairs_outer.json
+ minecraft/models/block/granite_stairs.json
+ minecraft/models/block/granite_wall_inventory.json
+ minecraft/models/block/granite_wall_post.json
+ minecraft/models/block/granite_wall_side.json
+ minecraft/models/block/jungle_sign.json
+ minecraft/models/block/lily_of_the_valley.json
+ minecraft/models/block/loom.json
+ minecraft/models/block/mossy_cobblestone_slab_top.json
+ minecraft/models/block/mossy_cobblestone_slab.json
+ minecraft/models/block/mossy_cobblestone_stairs_inner.json
+ minecraft/models/block/mossy_cobblestone_stairs_outer.json
+ minecraft/models/block/mossy_cobblestone_stairs.json
+ minecraft/models/block/mossy_stone_brick_slab_top.json
+ minecraft/models/block/mossy_stone_brick_slab.json
+ minecraft/models/block/mossy_stone_brick_stairs_inner.json
+ minecraft/models/block/mossy_stone_brick_stairs_outer.json
+ minecraft/models/block/mossy_stone_brick_stairs.json
+ minecraft/models/block/mossy_stone_brick_wall_inventory.json
+ minecraft/models/block/mossy_stone_brick_wall_post.json
+ minecraft/models/block/mossy_stone_brick_wall_side.json
+ minecraft/models/block/nether_brick_wall_inventory.json
+ minecraft/models/block/nether_brick_wall_post.json
+ minecraft/models/block/nether_brick_wall_side.json
+ minecraft/models/block/oak_sign.json
+ minecraft/models/block/polished_andesite_slab_top.json
+ minecraft/models/block/polished_andesite_slab.json
+ minecraft/models/block/polished_andesite_stairs_inner.json
+ minecraft/models/block/polished_andesite_stairs_outer.json
+ minecraft/models/block/polished_andesite_stairs.json
+ minecraft/models/block/polished_diorite_slab_top.json
+ minecraft/models/block/polished_diorite_slab.json
+ minecraft/models/block/polished_diorite_stairs_inner.json
+ minecraft/models/block/polished_diorite_stairs_outer.json
+ minecraft/models/block/polished_diorite_stairs.json
+ minecraft/models/block/polished_granite_slab_top.json
+ minecraft/models/block/polished_granite_slab.json
+ minecraft/models/block/polished_granite_stairs_inner.json
+ minecraft/models/block/polished_granite_stairs_outer.json
+ minecraft/models/block/polished_granite_stairs.json
+ minecraft/models/block/potted_bamboo.json
+ minecraft/models/block/potted_cornflower.json
+ minecraft/models/block/potted_lily_of_the_valley.json
+ minecraft/models/block/potted_wither_rose.json
+ minecraft/models/block/prismarine_wall_inventory.json
+ minecraft/models/block/prismarine_wall_post.json
+ minecraft/models/block/prismarine_wall_side.json
+ minecraft/models/block/red_nether_brick_slab_top.json
+ minecraft/models/block/red_nether_brick_slab.json
+ minecraft/models/block/red_nether_brick_stairs_inner.json
+ minecraft/models/block/red_nether_brick_stairs_outer.json
+ minecraft/models/block/red_nether_brick_stairs.json
+ minecraft/models/block/red_nether_brick_wall_inventory.json
+ minecraft/models/block/red_nether_brick_wall_post.json
+ minecraft/models/block/red_nether_brick_wall_side.json
+ minecraft/models/block/red_sandstone_wall_inventory.json
+ minecraft/models/block/red_sandstone_wall_post.json
+ minecraft/models/block/red_sandstone_wall_side.json
+ minecraft/models/block/sandstone_wall_inventory.json
+ minecraft/models/block/sandstone_wall_post.json
+ minecraft/models/block/sandstone_wall_side.json
- minecraft/models/block/sign.json
+ minecraft/models/block/smooth_quartz_slab_top.json
+ minecraft/models/block/smooth_quartz_slab.json
+ minecraft/models/block/smooth_quartz_stairs_inner.json
+ minecraft/models/block/smooth_quartz_stairs_outer.json
+ minecraft/models/block/smooth_quartz_stairs.json
+ minecraft/models/block/smooth_red_sandstone_slab_top.json
+ minecraft/models/block/smooth_red_sandstone_slab.json
+ minecraft/models/block/smooth_red_sandstone_stairs_inner.json
+ minecraft/models/block/smooth_red_sandstone_stairs_outer.json
+ minecraft/models/block/smooth_red_sandstone_stairs.json
+ minecraft/models/block/smooth_sandstone_slab_top.json
+ minecraft/models/block/smooth_sandstone_slab.json
+ minecraft/models/block/smooth_sandstone_stairs_inner.json
+ minecraft/models/block/smooth_sandstone_stairs_outer.json
+ minecraft/models/block/smooth_sandstone_stairs.json
+ minecraft/models/block/smooth_stone_slab_double.json
+ minecraft/models/block/smooth_stone_slab_top.json
+ minecraft/models/block/smooth_stone_slab.json
+ minecraft/models/block/spruce_sign.json
+ minecraft/models/block/stone_brick_wall_inventory.json
+ minecraft/models/block/stone_brick_wall_post.json
+ minecraft/models/block/stone_brick_wall_side.json
- minecraft/models/block/stone_slab_double.json
+ minecraft/models/block/stone_stairs_inner.json
+ minecraft/models/block/stone_stairs_outer.json
+ minecraft/models/block/stone_stairs.json
+ minecraft/models/block/wither_rose.json
+ minecraft/models/item/acacia_sign.json
+ minecraft/models/item/andesite_slab.json
+ minecraft/models/item/andesite_stairs.json
+ minecraft/models/item/andesite_wall.json
+ minecraft/models/item/bamboo.json
+ minecraft/models/item/birch_sign.json
+ minecraft/models/item/black_dye.json
+ minecraft/models/item/blue_dye.json
+ minecraft/models/item/brick_wall.json
+ minecraft/models/item/brown_dye.json
- minecraft/models/item/cactus_green.json
+ minecraft/models/item/cornflower.json
+ minecraft/models/item/creeper_banner_pattern.json
+ minecraft/models/item/crossbow_arrow.json
+ minecraft/models/item/crossbow_firework.json
+ minecraft/models/item/crossbow_pulling_0.json
+ minecraft/models/item/crossbow_pulling_1.json
+ minecraft/models/item/crossbow_pulling_2.json
+ minecraft/models/item/crossbow.json
- minecraft/models/item/dandelion_yellow.json
+ minecraft/models/item/dark_oak_sign.json
+ minecraft/models/item/diorite_slab.json
+ minecraft/models/item/diorite_stairs.json
+ minecraft/models/item/diorite_wall.json
+ minecraft/models/item/end_stone_brick_slab.json
+ minecraft/models/item/end_stone_brick_stairs.json
+ minecraft/models/item/end_stone_brick_wall.json
+ minecraft/models/item/flower_banner_pattern.json
+ minecraft/models/item/granite_slab.json
+ minecraft/models/item/granite_stairs.json
+ minecraft/models/item/granite_wall.json
+ minecraft/models/item/green_dye.json
+ minecraft/models/item/illager_beast_spawn_egg.json
+ minecraft/models/item/jungle_sign.json
+ minecraft/models/item/lily_of_the_valley.json
+ minecraft/models/item/loom.json
+ minecraft/models/item/mojang_banner_pattern.json
+ minecraft/models/item/mossy_cobblestone_slab.json
+ minecraft/models/item/mossy_cobblestone_stairs.json
+ minecraft/models/item/mossy_stone_brick_slab.json
+ minecraft/models/item/mossy_stone_brick_stairs.json
+ minecraft/models/item/mossy_stone_brick_wall.json
+ minecraft/models/item/nether_brick_wall.json
+ minecraft/models/item/oak_sign.json
+ minecraft/models/item/panda_spawn_egg.json
+ minecraft/models/item/pillager_spawn_egg.json
+ minecraft/models/item/polished_andesite_slab.json
+ minecraft/models/item/polished_andesite_stairs.json
+ minecraft/models/item/polished_diorite_slab.json
+ minecraft/models/item/polished_diorite_stairs.json
+ minecraft/models/item/polished_granite_slab.json
+ minecraft/models/item/polished_granite_stairs.json
+ minecraft/models/item/prismarine_wall.json
+ minecraft/models/item/red_dye.json
+ minecraft/models/item/red_nether_brick_slab.json
+ minecraft/models/item/red_nether_brick_stairs.json
+ minecraft/models/item/red_nether_brick_wall.json
+ minecraft/models/item/red_sandstone_wall.json
- minecraft/models/item/rose_red.json
+ minecraft/models/item/sandstone_wall.json
- minecraft/models/item/sign.json
+ minecraft/models/item/skull_banner_pattern.json
+ minecraft/models/item/smooth_quartz_slab.json
+ minecraft/models/item/smooth_quartz_stairs.json
+ minecraft/models/item/smooth_red_sandstone_slab.json
+ minecraft/models/item/smooth_red_sandstone_stairs.json
+ minecraft/models/item/smooth_sandstone_slab.json
+ minecraft/models/item/smooth_sandstone_stairs.json
+ minecraft/models/item/smooth_stone_slab.json
+ minecraft/models/item/spruce_sign.json
+ minecraft/models/item/stone_brick_wall.json
+ minecraft/models/item/stone_stairs.json
+ minecraft/models/item/suspicious_stew.json
+ minecraft/models/item/white_dye.json
+ minecraft/models/item/wither_rose.json
+ minecraft/models/item/yellow_dye.json
+ minecraft/textures/block/bamboo_large_leaves.png
+ minecraft/textures/block/bamboo_singleleaf.png
+ minecraft/textures/block/bamboo_small_leaves.png
+ minecraft/textures/block/bamboo_stage0.png
+ minecraft/textures/block/bamboo_stalk.png
+ minecraft/textures/block/cornflower.png
+ minecraft/textures/block/lily_of_the_valley.png
+ minecraft/textures/block/loom_bottom.png
+ minecraft/textures/block/loom_front.png
+ minecraft/textures/block/loom_side.png
+ minecraft/textures/block/loom_top.png
+ minecraft/textures/block/smooth_stone_slab_side.png
+ minecraft/textures/block/smooth_stone.png
- minecraft/textures/block/stone_slab_side.png
- minecraft/textures/block/stone_slab_top.png
+ minecraft/textures/block/wither_rose.png
+ minecraft/textures/entity/illager/beast.png
+ minecraft/textures/entity/illager/pillager.png
+ minecraft/textures/entity/panda/aggressive_panda.png
+ minecraft/textures/entity/panda/brown_panda.png
+ minecraft/textures/entity/panda/lazy_panda.png
+ minecraft/textures/entity/panda/panda.png
+ minecraft/textures/entity/panda/playful_panda.png
+ minecraft/textures/entity/panda/weak_panda.png
+ minecraft/textures/entity/panda/worried_panda.png
- minecraft/textures/entity/sign.png
+ minecraft/textures/entity/signs/acacia.png
+ minecraft/textures/entity/signs/birch.png
+ minecraft/textures/entity/signs/dark_oak.png
+ minecraft/textures/entity/signs/jungle.png
+ minecraft/textures/entity/signs/oak.png
+ minecraft/textures/entity/signs/spruce.png
+ minecraft/textures/gui/container/loom.png
+ minecraft/textures/item/acacia_sign.png
+ minecraft/textures/item/bamboo.png
+ minecraft/textures/item/birch_sign.png
+ minecraft/textures/item/black_dye.png
+ minecraft/textures/item/blue_dye.png
+ minecraft/textures/item/brown_dye.png
- minecraft/textures/item/cactus_green.png
+ minecraft/textures/item/creeper_banner_pattern.png
+ minecraft/textures/item/crossbow_arrow.png
+ minecraft/textures/item/crossbow_firework.png
+ minecraft/textures/item/crossbow_pulling_0.png
+ minecraft/textures/item/crossbow_pulling_1.png
+ minecraft/textures/item/crossbow_pulling_2.png
+ minecraft/textures/item/crossbow_standby.png
- minecraft/textures/item/dandelion_yellow.png
+ minecraft/textures/item/dark_oak_sign.png
+ minecraft/textures/item/flower_banner_pattern.png
+ minecraft/textures/item/green_dye.png
+ minecraft/textures/item/jungle_sign.png
+ minecraft/textures/item/mojang_banner_pattern.png
+ minecraft/textures/item/oak_sign.png
+ minecraft/textures/item/red_dye.png
- minecraft/textures/item/rose_red.png
- minecraft/textures/item/sign.png
+ minecraft/textures/item/skull_banner_pattern.png
+ minecraft/textures/item/spruce_sign.png
+ minecraft/textures/item/suspicious_stew.png
+ minecraft/textures/item/white_dye.png
+ minecraft/textures/item/yellow_dye.png
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
parsers
</summary>

```diff
- minecraft:nbt
+ minecraft:nbt_compound_tag
+ minecraft:nbt_tag
+ minecraft:time
```

</details>
</details>