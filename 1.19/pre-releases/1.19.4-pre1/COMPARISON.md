## Comparison with [23w06a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w06a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w06a</th><th>1.19.4-pre1</th></tr><tr><td>ResourcePack version</td><td><pre>12</pre></td><td><pre>13</pre></td></tr><tr><td>World version</td><td><pre>3326</pre></td><td><pre>3330</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741942</pre></td><td><pre>1073741944</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">23w06a</th><th>1.19.4-pre1</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>5.0.28</pre></td><td><pre>6.0.6</pre></td></tr></table>
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
+ decorated_pot_patterns.txt
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:cherry_button
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wall_hanging_sign
+ minecraft:cherry_wall_sign
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:potted_cherry_sapling
+ minecraft:potted_torchflower
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
+ minecraft:torchflower
+ minecraft:torchflower_crop
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:decorated_pot
+ minecraft:suspicious_sand
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:heightmap
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:interaction
+ minecraft:sniffer
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:brush
+ minecraft:cherry_boat
+ minecraft:cherry_button
+ minecraft:cherry_chest_boat
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:pottery_shard_archer
+ minecraft:pottery_shard_arms_up
+ minecraft:pottery_shard_prize
+ minecraft:pottery_shard_skull
+ minecraft:sniffer_spawn_egg
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
+ minecraft:torchflower
+ minecraft:torchflower_seeds
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:sniffer_digging
+ minecraft:sniffer_explored_positions
+ minecraft:sniffer_happy
+ minecraft:sniffer_sniffing_target
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:dripping_cherry_leaves
+ minecraft:falling_cherry_leaves
+ minecraft:landing_cherry_leaves
```

</details>
<details>
<summary>
recipe_serializer
</summary>

```diff
+ minecraft:crafting_decorated_pot
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.cherry_leaves.break
+ minecraft:block.cherry_leaves.fall
+ minecraft:block.cherry_leaves.hit
+ minecraft:block.cherry_leaves.place
+ minecraft:block.cherry_leaves.step
+ minecraft:block.cherry_sapling.break
+ minecraft:block.cherry_sapling.fall
+ minecraft:block.cherry_sapling.hit
+ minecraft:block.cherry_sapling.place
+ minecraft:block.cherry_sapling.step
+ minecraft:block.cherry_wood_button.click_off
+ minecraft:block.cherry_wood_button.click_on
+ minecraft:block.cherry_wood_door.close
+ minecraft:block.cherry_wood_door.open
+ minecraft:block.cherry_wood_fence_gate.close
+ minecraft:block.cherry_wood_fence_gate.open
+ minecraft:block.cherry_wood_hanging_sign.break
+ minecraft:block.cherry_wood_hanging_sign.fall
+ minecraft:block.cherry_wood_hanging_sign.hit
+ minecraft:block.cherry_wood_hanging_sign.place
+ minecraft:block.cherry_wood_hanging_sign.step
+ minecraft:block.cherry_wood_pressure_plate.click_off
+ minecraft:block.cherry_wood_pressure_plate.click_on
+ minecraft:block.cherry_wood_trapdoor.close
+ minecraft:block.cherry_wood_trapdoor.open
+ minecraft:block.cherry_wood.break
+ minecraft:block.cherry_wood.fall
+ minecraft:block.cherry_wood.hit
+ minecraft:block.cherry_wood.place
+ minecraft:block.cherry_wood.step
+ minecraft:block.decorated_pot.break
+ minecraft:block.decorated_pot.fall
+ minecraft:block.decorated_pot.hit
+ minecraft:block.decorated_pot.place
+ minecraft:block.decorated_pot.shatter
+ minecraft:block.decorated_pot.step
+ minecraft:block.pink_petals.break
+ minecraft:block.pink_petals.fall
+ minecraft:block.pink_petals.hit
+ minecraft:block.pink_petals.place
+ minecraft:block.pink_petals.step
+ minecraft:block.suspicious_sand.break
+ minecraft:block.suspicious_sand.fall
+ minecraft:block.suspicious_sand.hit
+ minecraft:block.suspicious_sand.place
+ minecraft:block.suspicious_sand.step
+ minecraft:entity.sniffer.death
+ minecraft:entity.sniffer.digging
+ minecraft:entity.sniffer.digging_stop
+ minecraft:entity.sniffer.drop_seed
+ minecraft:entity.sniffer.eat
+ minecraft:entity.sniffer.happy
+ minecraft:entity.sniffer.hurt
+ minecraft:entity.sniffer.idle
+ minecraft:entity.sniffer.scenting
+ minecraft:entity.sniffer.searching
+ minecraft:entity.sniffer.sniffing
+ minecraft:entity.sniffer.step
+ minecraft:intentionally_empty
+ minecraft:item.brush.brush_sand_completed
+ minecraft:item.brush.brushing
+ minecraft:music.overworld.cherry_grove
```

</details>
<details>
<summary>
worldgen/foliage_placer_type
</summary>

```diff
+ minecraft:cherry_foliage_placer
```

</details>
<details>
<summary>
worldgen/trunk_placer_type
</summary>

```diff
+ minecraft:cherry_trunk_placer
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
+ universal_tags/decorated_pot_patterns.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:cherry_button
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wall_hanging_sign
+ minecraft:cherry_wall_sign
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:potted_cherry_sapling
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:potted_torchflower
+ minecraft:torchflower
+ minecraft:torchflower_crop
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:interaction
+ minecraft:sniffer
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:sniffer
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:cherry_button
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:potted_cherry_sapling
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:cherry_button
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wall_hanging_sign
+ minecraft:cherry_wall_sign
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:potted_cherry_sapling
+ minecraft:potted_torchflower
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
+ minecraft:torchflower
+ minecraft:torchflower_crop
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:decorated_pot
+ minecraft:suspicious_sand
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:heightmap
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:interaction
+ minecraft:sniffer
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:brush
+ minecraft:cherry_boat
+ minecraft:cherry_button
+ minecraft:cherry_chest_boat
+ minecraft:cherry_door
+ minecraft:cherry_fence
+ minecraft:cherry_fence_gate
+ minecraft:cherry_hanging_sign
+ minecraft:cherry_leaves
+ minecraft:cherry_log
+ minecraft:cherry_planks
+ minecraft:cherry_pressure_plate
+ minecraft:cherry_sapling
+ minecraft:cherry_sign
+ minecraft:cherry_slab
+ minecraft:cherry_stairs
+ minecraft:cherry_trapdoor
+ minecraft:cherry_wood
+ minecraft:decorated_pot
+ minecraft:pink_petals
+ minecraft:pottery_shard_archer
+ minecraft:pottery_shard_arms_up
+ minecraft:pottery_shard_prize
+ minecraft:pottery_shard_skull
+ minecraft:sniffer_spawn_egg
+ minecraft:stripped_cherry_log
+ minecraft:stripped_cherry_wood
+ minecraft:suspicious_sand
+ minecraft:torchflower
+ minecraft:torchflower_seeds
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:sniffer_digging
+ minecraft:sniffer_explored_positions
+ minecraft:sniffer_happy
+ minecraft:sniffer_sniffing_target
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:dripping_cherry_leaves
+ minecraft:falling_cherry_leaves
+ minecraft:landing_cherry_leaves
```

</details>
<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
+ minecraft:crafting_decorated_pot
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.cherry_leaves.break
+ minecraft:block.cherry_leaves.fall
+ minecraft:block.cherry_leaves.hit
+ minecraft:block.cherry_leaves.place
+ minecraft:block.cherry_leaves.step
+ minecraft:block.cherry_sapling.break
+ minecraft:block.cherry_sapling.fall
+ minecraft:block.cherry_sapling.hit
+ minecraft:block.cherry_sapling.place
+ minecraft:block.cherry_sapling.step
+ minecraft:block.cherry_wood_button.click_off
+ minecraft:block.cherry_wood_button.click_on
+ minecraft:block.cherry_wood_door.close
+ minecraft:block.cherry_wood_door.open
+ minecraft:block.cherry_wood_fence_gate.close
+ minecraft:block.cherry_wood_fence_gate.open
+ minecraft:block.cherry_wood_hanging_sign.break
+ minecraft:block.cherry_wood_hanging_sign.fall
+ minecraft:block.cherry_wood_hanging_sign.hit
+ minecraft:block.cherry_wood_hanging_sign.place
+ minecraft:block.cherry_wood_hanging_sign.step
+ minecraft:block.cherry_wood_pressure_plate.click_off
+ minecraft:block.cherry_wood_pressure_plate.click_on
+ minecraft:block.cherry_wood_trapdoor.close
+ minecraft:block.cherry_wood_trapdoor.open
+ minecraft:block.cherry_wood.break
+ minecraft:block.cherry_wood.fall
+ minecraft:block.cherry_wood.hit
+ minecraft:block.cherry_wood.place
+ minecraft:block.cherry_wood.step
+ minecraft:block.decorated_pot.break
+ minecraft:block.decorated_pot.fall
+ minecraft:block.decorated_pot.hit
+ minecraft:block.decorated_pot.place
+ minecraft:block.decorated_pot.shatter
+ minecraft:block.decorated_pot.step
+ minecraft:block.pink_petals.break
+ minecraft:block.pink_petals.fall
+ minecraft:block.pink_petals.hit
+ minecraft:block.pink_petals.place
+ minecraft:block.pink_petals.step
+ minecraft:block.suspicious_sand.break
+ minecraft:block.suspicious_sand.fall
+ minecraft:block.suspicious_sand.hit
+ minecraft:block.suspicious_sand.place
+ minecraft:block.suspicious_sand.step
+ minecraft:entity.sniffer.death
+ minecraft:entity.sniffer.digging
+ minecraft:entity.sniffer.digging_stop
+ minecraft:entity.sniffer.drop_seed
+ minecraft:entity.sniffer.eat
+ minecraft:entity.sniffer.happy
+ minecraft:entity.sniffer.hurt
+ minecraft:entity.sniffer.idle
+ minecraft:entity.sniffer.scenting
+ minecraft:entity.sniffer.searching
+ minecraft:entity.sniffer.sniffing
+ minecraft:entity.sniffer.step
+ minecraft:intentionally_empty
+ minecraft:item.brush.brush_sand_completed
+ minecraft:item.brush.brushing
+ minecraft:music.overworld.cherry_grove
```

</details>
<details>
<summary>
universal_tags/worldgen/foliage_placer_type.json
</summary>

```diff
+ minecraft:cherry_foliage_placer
```

</details>
<details>
<summary>
universal_tags/worldgen/trunk_placer_type.json
</summary>

```diff
+ minecraft:cherry_trunk_placer
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
+ cherry_button.json
+ cherry_door.json
+ cherry_fence_gate.json
+ cherry_fence.json
+ cherry_hanging_sign.json
+ cherry_leaves.json
+ cherry_log.json
+ cherry_planks.json
+ cherry_pressure_plate.json
+ cherry_sapling.json
+ cherry_sign.json
+ cherry_slab.json
+ cherry_stairs.json
+ cherry_trapdoor.json
+ cherry_wall_hanging_sign.json
+ cherry_wall_sign.json
+ cherry_wood.json
+ decorated_pot.json
+ pink_petals.json
+ potted_cherry_sapling.json
+ potted_torchflower.json
+ stripped_cherry_log.json
+ stripped_cherry_wood.json
+ suspicious_sand.json
+ torchflower_crop.json
+ torchflower.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
execute
</summary>

```diff
+ execute positioned over <heightmap: heightmap>
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
+ biome.minecraft.cherry_grove: Cherry Grove
+ block.minecraft.cherry_button: Cherry Button
+ block.minecraft.cherry_door: Cherry Door
+ block.minecraft.cherry_fence_gate: Cherry Fence Gate
+ block.minecraft.cherry_fence: Cherry Fence
+ block.minecraft.cherry_hanging_sign: Cherry Hanging Sign
+ block.minecraft.cherry_leaves: Cherry Leaves
+ block.minecraft.cherry_log: Cherry Log
+ block.minecraft.cherry_planks: Cherry Planks
+ block.minecraft.cherry_pressure_plate: Cherry Pressure Plate
+ block.minecraft.cherry_sapling: Cherry Sapling
+ block.minecraft.cherry_sign: Cherry Sign
+ block.minecraft.cherry_slab: Cherry Slab
+ block.minecraft.cherry_stairs: Cherry Stairs
+ block.minecraft.cherry_trapdoor: Cherry Trapdoor
+ block.minecraft.cherry_wall_hanging_sign: Cherry Wall Hanging Sign
+ block.minecraft.cherry_wall_sign: Cherry Wall Sign
+ block.minecraft.cherry_wood: Cherry Wood
+ block.minecraft.decorated_pot: Decorated Pot
+ block.minecraft.pink_petals: Pink Petals
+ block.minecraft.potted_cherry_sapling: Potted Cherry Sapling
+ block.minecraft.potted_torchflower: Potted Torchflower
+ block.minecraft.stripped_cherry_log: Stripped Cherry Log
+ block.minecraft.stripped_cherry_wood: Stripped Cherry Wood
+ block.minecraft.suspicious_sand: Suspicious Sand
+ block.minecraft.torchflower_crop: Torchflower Crop
+ block.minecraft.torchflower: Torchflower
+ entity.minecraft.falling_block_type: Falling %s
+ entity.minecraft.interaction: Interaction
+ entity.minecraft.sniffer: Sniffer
+ gui.banned.reason.defamation_impersonation_false_information: Impersonation or sharing information to exploit or mislead others
+ gui.banned.reason.drugs: References to illegal drugs
+ gui.banned.reason.extreme_violence_or_gore: Depictions of real-life excessive violence or gore
+ gui.banned.reason.false_reporting: Excessive false or inaccurate reports
+ gui.banned.reason.fraud: Fraudulent acquisition or use of content
+ gui.banned.reason.generic_violation: Violating Community Standards
+ gui.banned.reason.harassment_or_bullying: Abusive language used in a directed, harmful manner
+ gui.banned.reason.hate_speech: Hate speech or discrimination
+ gui.banned.reason.hate_terrorism_notorious_figure: References to hate groups, terrorist organizations, or notorious figures
+ gui.banned.reason.imminent_harm_to_person_or_property: Intent to cause real-life harm to persons or property
+ gui.banned.reason.nudity_or_pornography: Displaying lewd or pornographic material
+ gui.banned.reason.sexually_inappropriate: Topics or content of a sexual nature
+ gui.banned.reason.spam_or_advertising: Spam or advertising
+ item.minecraft.brush: Brush
+ item.minecraft.cherry_boat: Cherry Boat
+ item.minecraft.cherry_chest_boat: Cherry Boat with Chest
+ item.minecraft.pottery_shard_archer: Archer Pottery Shard
+ item.minecraft.pottery_shard_arms_up: Arms Up Pottery Shard
+ item.minecraft.pottery_shard_prize: Prize Pottery Shard
+ item.minecraft.pottery_shard_skull: Skull Pottery Shard
+ item.minecraft.sniffer_spawn_egg: Sniffer Spawn Egg
+ item.minecraft.torchflower_seeds: Torchflower Seeds
+ mco.notification.dismiss: Dismiss
+ mco.notification.visitUrl.buttonText.default: Open link
+ mco.notification.visitUrl.message.default: Please visit the link below
+ narration.tab_navigation.usage: Press Ctrl and Tab to switch between tabs
+ narrator.position.tab: Selected tab %s out of %s
+ options.accessibility.high_contrast: High Contrast
+ options.accessibility.high_contrast.tooltip: Enhances the contrast of UI elements
+ resourcePack.high_contrast.name: High Contrast
+ subtitles.block.decorated_pot.shatter: Pot shatters
+ subtitles.entity.sniffer.death: Sniffer dies
+ subtitles.entity.sniffer.digging_stop: Sniffer stands up
+ subtitles.entity.sniffer.digging: Sniffer digs
+ subtitles.entity.sniffer.drop_seed: Sniffer drops seed
+ subtitles.entity.sniffer.eat: Sniffer eats
+ subtitles.entity.sniffer.happy: Sniffer delights
+ subtitles.entity.sniffer.hurt: Sniffer hurts
+ subtitles.entity.sniffer.idle: Sniffer grunts
+ subtitles.entity.sniffer.scenting: Sniffer scents
+ subtitles.entity.sniffer.searching: Sniffer searches
+ subtitles.entity.sniffer.sniffing: Sniffer sniffs
+ subtitles.entity.sniffer.step: Sniffer steps
+ subtitles.item.brush.brush_sand_completed: Brushing sand completed
+ subtitles.item.brush.brushing: Brushing
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>23w06a</th><th>1.19.4-pre1</th></tr>
<tr><th align="left"><div style="width:290px">options.realmsNotifications</div></th><td>Realms Notifications</td><td>Realms News & Invites</td></tr>
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
+ reports/biome_parameters/minecraft/overworld_update_1_20.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/adventure/adventuring_time.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/cherry_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/cherry_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/cherry_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/building_blocks/stripped_cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/cherry_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/cherry_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/cherry_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/decorations/decorated_pot_simple.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/misc/orange_dye_from_torchflower.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/misc/pink_dye_from_pink_petals.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/cherry_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/cherry_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/cherry_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/cherry_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/redstone/cherry_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/tools/brush.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/transportation/cherry_boat.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/recipes/transportation/cherry_chest_boat.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/archaeology/desert_pyramid.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/archaeology/desert_well.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_leaves.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_log.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_sapling.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/decorated_pot.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/pink_petals.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/potted_cherry_sapling.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/potted_torchflower.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/stripped_cherry_log.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/stripped_cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/suspicious_sand.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/torchflower_crop.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/torchflower.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/entities/sniffer.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/brush.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_boat.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_button.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_chest_boat.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_door.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_fence_gate.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_fence.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_hanging_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_planks.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_pressure_plate.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_sign.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_slab.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_stairs.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_trapdoor.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/decorated_pot_simple.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/decorated_pot.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/orange_dye_from_torchflower.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/pink_dye_from_pink_petals.json
+ minecraft/datapacks/update_1_20/data/minecraft/recipes/stripped_cherry_wood.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/cherry_logs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/crops.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/flower_pots.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/flowers.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/inside_step_sound_blocks.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/leaves.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/logs_that_burn.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/mineable/hoe.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/overworld_natural_logs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/sand.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/saplings.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/small_flowers.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/sniffer_diggable_block.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/breaks_decorated_pots.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/buttons.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/cherry_logs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/decorated_pot_shards.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/doors.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/fences.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/flowers.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/leaves.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/logs_that_burn.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/sand.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/saplings.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/slabs.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/small_flowers.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/items/sniffer_food.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/stairs.json
- minecraft/datapacks/update_1_20/data/minecraft/tags/items/trapdoors.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/worldgen/biome/is_mountain.json
+ minecraft/datapacks/update_1_20/data/minecraft/worldgen/biome/cherry_grove.json
+ minecraft/datapacks/update_1_20/data/minecraft/worldgen/multi_noise_biome_source_parameter_list/overworld.json
+ minecraft/loot_tables/blocks/cherry_button.json
+ minecraft/loot_tables/blocks/cherry_door.json
+ minecraft/loot_tables/blocks/cherry_fence_gate.json
+ minecraft/loot_tables/blocks/cherry_fence.json
+ minecraft/loot_tables/blocks/cherry_hanging_sign.json
+ minecraft/loot_tables/blocks/cherry_leaves.json
+ minecraft/loot_tables/blocks/cherry_log.json
+ minecraft/loot_tables/blocks/cherry_planks.json
+ minecraft/loot_tables/blocks/cherry_pressure_plate.json
+ minecraft/loot_tables/blocks/cherry_sapling.json
+ minecraft/loot_tables/blocks/cherry_sign.json
+ minecraft/loot_tables/blocks/cherry_slab.json
+ minecraft/loot_tables/blocks/cherry_stairs.json
+ minecraft/loot_tables/blocks/cherry_trapdoor.json
+ minecraft/loot_tables/blocks/cherry_wood.json
+ minecraft/loot_tables/blocks/decorated_pot.json
+ minecraft/loot_tables/blocks/pink_petals.json
+ minecraft/loot_tables/blocks/potted_cherry_sapling.json
+ minecraft/loot_tables/blocks/potted_torchflower.json
+ minecraft/loot_tables/blocks/stripped_cherry_log.json
+ minecraft/loot_tables/blocks/stripped_cherry_wood.json
+ minecraft/loot_tables/blocks/suspicious_sand.json
+ minecraft/loot_tables/blocks/torchflower_crop.json
+ minecraft/loot_tables/blocks/torchflower.json
+ minecraft/loot_tables/entities/sniffer.json
+ minecraft/tags/blocks/smelts_to_glass.json
+ minecraft/tags/damage_type/always_hurts_ender_dragons.json
+ minecraft/tags/entity_types/fall_damage_immune.json
+ minecraft/tags/items/axes.json
+ minecraft/tags/items/hoes.json
+ minecraft/tags/items/pickaxes.json
+ minecraft/tags/items/shovels.json
+ minecraft/tags/items/smelts_to_glass.json
+ minecraft/tags/items/swords.json
+ minecraft/tags/items/tools.json
+ minecraft/worldgen/configured_feature/cherry_bees_005.json
+ minecraft/worldgen/configured_feature/cherry.json
+ minecraft/worldgen/configured_feature/flower_cherry.json
+ minecraft/worldgen/multi_noise_biome_source_parameter_list/nether.json
+ minecraft/worldgen/multi_noise_biome_source_parameter_list/overworld.json
+ minecraft/worldgen/placed_feature/cherry_bees_005.json
+ minecraft/worldgen/placed_feature/cherry_checked.json
+ minecraft/worldgen/placed_feature/flower_cherry.json
+ minecraft/worldgen/placed_feature/trees_cherry.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/atlases/decorated_pot.json
+ minecraft/blockstates/cherry_button.json
+ minecraft/blockstates/cherry_door.json
+ minecraft/blockstates/cherry_fence_gate.json
+ minecraft/blockstates/cherry_fence.json
+ minecraft/blockstates/cherry_hanging_sign.json
+ minecraft/blockstates/cherry_leaves.json
+ minecraft/blockstates/cherry_log.json
+ minecraft/blockstates/cherry_planks.json
+ minecraft/blockstates/cherry_pressure_plate.json
+ minecraft/blockstates/cherry_sapling.json
+ minecraft/blockstates/cherry_sign.json
+ minecraft/blockstates/cherry_slab.json
+ minecraft/blockstates/cherry_stairs.json
+ minecraft/blockstates/cherry_trapdoor.json
+ minecraft/blockstates/cherry_wall_hanging_sign.json
+ minecraft/blockstates/cherry_wall_sign.json
+ minecraft/blockstates/cherry_wood.json
+ minecraft/blockstates/decorated_pot.json
+ minecraft/blockstates/pink_petals.json
+ minecraft/blockstates/potted_cherry_sapling.json
+ minecraft/blockstates/potted_torchflower.json
+ minecraft/blockstates/stripped_cherry_log.json
+ minecraft/blockstates/stripped_cherry_wood.json
+ minecraft/blockstates/suspicious_sand.json
+ minecraft/blockstates/torchflower_crop.json
+ minecraft/blockstates/torchflower.json
+ minecraft/models/block/cherry_button_inventory.json
+ minecraft/models/block/cherry_button_pressed.json
+ minecraft/models/block/cherry_button.json
+ minecraft/models/block/cherry_door_bottom_left_open.json
+ minecraft/models/block/cherry_door_bottom_left.json
+ minecraft/models/block/cherry_door_bottom_right_open.json
+ minecraft/models/block/cherry_door_bottom_right.json
+ minecraft/models/block/cherry_door_top_left_open.json
+ minecraft/models/block/cherry_door_top_left.json
+ minecraft/models/block/cherry_door_top_right_open.json
+ minecraft/models/block/cherry_door_top_right.json
+ minecraft/models/block/cherry_fence_gate_open.json
+ minecraft/models/block/cherry_fence_gate_wall_open.json
+ minecraft/models/block/cherry_fence_gate_wall.json
+ minecraft/models/block/cherry_fence_gate.json
+ minecraft/models/block/cherry_fence_inventory.json
+ minecraft/models/block/cherry_fence_post.json
+ minecraft/models/block/cherry_fence_side.json
+ minecraft/models/block/cherry_hanging_sign.json
+ minecraft/models/block/cherry_leaves.json
+ minecraft/models/block/cherry_log_x.json
+ minecraft/models/block/cherry_log_y.json
+ minecraft/models/block/cherry_log_z.json
+ minecraft/models/block/cherry_log.json
+ minecraft/models/block/cherry_planks.json
+ minecraft/models/block/cherry_pressure_plate_down.json
+ minecraft/models/block/cherry_pressure_plate.json
+ minecraft/models/block/cherry_sapling.json
+ minecraft/models/block/cherry_sign.json
+ minecraft/models/block/cherry_slab_top.json
+ minecraft/models/block/cherry_slab.json
+ minecraft/models/block/cherry_stairs_inner.json
+ minecraft/models/block/cherry_stairs_outer.json
+ minecraft/models/block/cherry_stairs.json
+ minecraft/models/block/cherry_trapdoor_bottom.json
+ minecraft/models/block/cherry_trapdoor_open.json
+ minecraft/models/block/cherry_trapdoor_top.json
+ minecraft/models/block/cherry_wood.json
+ minecraft/models/block/decorated_pot.json
+ minecraft/models/block/flowerbed_1.json
+ minecraft/models/block/flowerbed_2.json
+ minecraft/models/block/flowerbed_3.json
+ minecraft/models/block/flowerbed_4.json
+ minecraft/models/block/pink_petals_1.json
+ minecraft/models/block/pink_petals_2.json
+ minecraft/models/block/pink_petals_3.json
+ minecraft/models/block/pink_petals_4.json
+ minecraft/models/block/potted_cherry_sapling.json
+ minecraft/models/block/potted_torchflower.json
+ minecraft/models/block/stripped_cherry_log_x.json
+ minecraft/models/block/stripped_cherry_log_y.json
+ minecraft/models/block/stripped_cherry_log_z.json
+ minecraft/models/block/stripped_cherry_log.json
+ minecraft/models/block/stripped_cherry_wood.json
+ minecraft/models/block/suspicious_sand_0.json
+ minecraft/models/block/suspicious_sand_1.json
+ minecraft/models/block/suspicious_sand_2.json
+ minecraft/models/block/suspicious_sand_3.json
+ minecraft/models/block/torchflower_crop_stage0.json
+ minecraft/models/block/torchflower_crop_stage1.json
+ minecraft/models/block/torchflower_crop_stage2.json
+ minecraft/models/block/torchflower.json
+ minecraft/models/item/brush_brushing_0.json
+ minecraft/models/item/brush_brushing_1.json
+ minecraft/models/item/brush_brushing_2.json
+ minecraft/models/item/brush.json
+ minecraft/models/item/cherry_boat.json
+ minecraft/models/item/cherry_button.json
+ minecraft/models/item/cherry_chest_boat.json
+ minecraft/models/item/cherry_door.json
+ minecraft/models/item/cherry_fence_gate.json
+ minecraft/models/item/cherry_fence.json
+ minecraft/models/item/cherry_hanging_sign.json
+ minecraft/models/item/cherry_leaves.json
+ minecraft/models/item/cherry_log.json
+ minecraft/models/item/cherry_planks.json
+ minecraft/models/item/cherry_pressure_plate.json
+ minecraft/models/item/cherry_sapling.json
+ minecraft/models/item/cherry_sign.json
+ minecraft/models/item/cherry_slab.json
+ minecraft/models/item/cherry_stairs.json
+ minecraft/models/item/cherry_trapdoor.json
+ minecraft/models/item/cherry_wood.json
+ minecraft/models/item/decorated_pot.json
+ minecraft/models/item/pink_petals.json
+ minecraft/models/item/pottery_shard_archer.json
+ minecraft/models/item/pottery_shard_arms_up.json
+ minecraft/models/item/pottery_shard_prize.json
+ minecraft/models/item/pottery_shard_skull.json
+ minecraft/models/item/sniffer_spawn_egg.json
+ minecraft/models/item/stripped_cherry_log.json
+ minecraft/models/item/stripped_cherry_wood.json
+ minecraft/models/item/suspicious_sand.json
+ minecraft/models/item/torchflower_seeds.json
+ minecraft/models/item/torchflower.json
+ minecraft/particles/dripping_cherry_leaves.json
+ minecraft/particles/falling_cherry_leaves.json
+ minecraft/particles/landing_cherry_leaves.json
+ minecraft/textures/block/cherry_door_bottom.png
+ minecraft/textures/block/cherry_door_top.png
+ minecraft/textures/block/cherry_leaves.png
+ minecraft/textures/block/cherry_log_top.png
+ minecraft/textures/block/cherry_log.png
+ minecraft/textures/block/cherry_planks.png
+ minecraft/textures/block/cherry_sapling.png
+ minecraft/textures/block/cherry_trapdoor.png
+ minecraft/textures/block/pink_petals_stem.png
+ minecraft/textures/block/pink_petals.png
+ minecraft/textures/block/stripped_cherry_log_top.png
+ minecraft/textures/block/stripped_cherry_log.png
+ minecraft/textures/block/suspicious_sand_0.png
+ minecraft/textures/block/suspicious_sand_1.png
+ minecraft/textures/block/suspicious_sand_2.png
+ minecraft/textures/block/suspicious_sand_3.png
+ minecraft/textures/block/torchflower_crop_stage0.png
+ minecraft/textures/block/torchflower_crop_stage1.png
+ minecraft/textures/block/torchflower_crop_stage2.png
+ minecraft/textures/block/torchflower.png
+ minecraft/textures/entity/boat/cherry.png
+ minecraft/textures/entity/chest_boat/cherry.png
+ minecraft/textures/entity/decorated_pot/decorated_pot_base.png
+ minecraft/textures/entity/decorated_pot/decorated_pot_side.png
+ minecraft/textures/entity/decorated_pot/pottery_pattern_archer.png
+ minecraft/textures/entity/decorated_pot/pottery_pattern_arms_up.png
+ minecraft/textures/entity/decorated_pot/pottery_pattern_prize.png
+ minecraft/textures/entity/decorated_pot/pottery_pattern_skull.png
+ minecraft/textures/entity/signs/cherry.png
+ minecraft/textures/entity/signs/hanging/cherry.png
+ minecraft/textures/entity/sniffer/sniffer.png
+ minecraft/textures/gui/footer_separator.png
+ minecraft/textures/gui/hanging_signs/cherry.png
+ minecraft/textures/gui/header_separator.png
+ minecraft/textures/gui/info_icon.png
+ minecraft/textures/gui/light_dirt_background.png
+ minecraft/textures/gui/tab_button.png
+ minecraft/textures/gui/unseen_notification.png
+ minecraft/textures/item/brush.png
+ minecraft/textures/item/cherry_boat.png
+ minecraft/textures/item/cherry_chest_boat.png
+ minecraft/textures/item/cherry_door.png
+ minecraft/textures/item/cherry_hanging_sign.png
+ minecraft/textures/item/cherry_sign.png
+ minecraft/textures/item/pink_petals.png
+ minecraft/textures/item/pottery_shard_archer.png
+ minecraft/textures/item/pottery_shard_arms_up.png
+ minecraft/textures/item/pottery_shard_prize.png
+ minecraft/textures/item/pottery_shard_skull.png
+ minecraft/textures/item/torchflower_seeds.png
+ minecraft/textures/misc/enchanted_glint_entity.png
+ minecraft/textures/misc/enchanted_glint_item.png
- minecraft/textures/misc/enchanted_item_glint.png
- realms/textures/gui/realms/configure_icon.png
- realms/textures/gui/realms/leave_icon.png
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
+ minecraft:heightmap
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
+ net.minecraft.SharedConstants$1
- net.minecraft.SystemReport
+ net.minecraft.Util
- net.minecraft.Util$1
+ net.minecraft.Util$10
- net.minecraft.Util$11
+ net.minecraft.Util$2
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.WorldVersion
- XXX.advancements.critereon.AbstractCriterionTriggerInstance
+ XXX.advancements.critereon.BeeNestDestroyedTrigger
- XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ XXX.advancements.critereon.BlockPredicate
- XXX.advancements.critereon.BlockPredicate$Builder
+ XXX.advancements.critereon.BredAnimalsTrigger
- XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ XXX.advancements.critereon.BrewedPotionTrigger
- XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChangeDimensionTrigger
- XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChanneledLightningTrigger
- XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
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
- XXX.advancements.critereon.EntityPredicate$Composite
+ XXX.advancements.critereon.EntitySubPredicate
- XXX.advancements.critereon.EntitySubPredicate$1
+ XXX.advancements.critereon.EntitySubPredicate$Type
- XXX.advancements.critereon.EntitySubPredicate$Types
+ XXX.advancements.critereon.EntityTypePredicate
- XXX.advancements.critereon.EntityTypePredicate$1
+ XXX.advancements.critereon.EntityTypePredicate$TagPredicate
- XXX.advancements.critereon.EntityTypePredicate$TypePredicate
+ XXX.advancements.critereon.EntityVariantPredicate
- XXX.advancements.critereon.EntityVariantPredicate$1
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingHookPredicate
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemInteractWithBlockTrigger
+ XXX.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LighthingBoltPredicate
+ XXX.advancements.critereon.LightningStrikeTrigger
- XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LootTableTrigger
- XXX.advancements.critereon.LootTableTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Doubles
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PickedUpItemTrigger
- XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
+ XXX.advancements.critereon.PlacedBlockTrigger
- XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.PlayerTrigger
+ XXX.advancements.critereon.PlayerTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SerializationContext
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.SlimePredicate
+ XXX.advancements.critereon.StartRidingTrigger
- XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TagPredicate
+ XXX.advancements.critereon.TameAnimalTrigger
- XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.advancements.packs.package-info
- XXX.advancements.packs.UpdateOneTwentyAdventureAdvancements
+ XXX.advancements.packs.UpdateOneTwentyHusbandryAdvancements
- XXX.advancements.packs.UpdateOneTwentyVanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
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
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.OneShot
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PoiCompetitorScan
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.PrepareRamNearestTarget
+ XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
- XXX.ai.behavior.RamTarget
+ XXX.ai.behavior.RandomLookAround
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetEntityLookTargetSometimes
+ XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
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
+ XXX.ai.behavior.TriggerGate
- XXX.ai.behavior.TryFindLand
+ XXX.ai.behavior.TryFindLandNearWater
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.TryLaySpawnOnWaterNearLand
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.UseBonemeal
- XXX.ai.behavior.ValidateNearbyPoi
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
- XXX.ai.goal.package-info
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.RandomLookAroundGoal
+ XXX.ai.goal.RandomStandGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
- XXX.ai.memory.NearestVisibleLivingEntities
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.AmphibiousPathNavigation
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.AdultSensor
- XXX.ai.sensing.AxolotlAttackablesSensor
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.NearestVisibleLivingEntitySensor
- XXX.ai.sensing.package-info
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.TemptingSensor
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.sensing.WardenEntitySensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
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
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$AllayVibrationListenerConfig
+ XXX.animal.allay.Allay$JukeboxListener
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.axolotl.Axolotl
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
- XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
- XXX.animal.sniffer.SnifferAi$1
- XXX.animal.sniffer.SnifferAi$FeelingHappy
- XXX.animal.sniffer.SnifferAi$Scenting
- XXX.animal.sniffer.SnifferAi$Sniffing
- XXX.behavior.declarative.BehaviorBuilder
+ XXX.behavior.declarative.BehaviorBuilder$1
- XXX.behavior.declarative.BehaviorBuilder$Constant
+ XXX.behavior.declarative.BehaviorBuilder$Constant$1
- XXX.behavior.declarative.BehaviorBuilder$Instance
+ XXX.behavior.declarative.BehaviorBuilder$Instance$1
- XXX.behavior.declarative.BehaviorBuilder$Instance$2
+ XXX.behavior.declarative.BehaviorBuilder$Instance$3
- XXX.behavior.declarative.BehaviorBuilder$Instance$4
+ XXX.behavior.declarative.BehaviorBuilder$Instance$5
- XXX.behavior.declarative.BehaviorBuilder$Instance$Mu
+ XXX.behavior.declarative.BehaviorBuilder$Mu
- XXX.behavior.declarative.BehaviorBuilder$PureMemory
+ XXX.behavior.declarative.BehaviorBuilder$PureMemory$1
- XXX.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper
- XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ XXX.behavior.declarative.MemoryAccessor
- XXX.behavior.declarative.MemoryCondition
+ XXX.behavior.declarative.MemoryCondition$Absent
- XXX.behavior.declarative.MemoryCondition$Present
+ XXX.behavior.declarative.MemoryCondition$Registered
+ XXX.behavior.declarative.package-info
- XXX.behavior.declarative.Trigger
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
- XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.package-info
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.CherryTreeGrower
- XXX.block.state.BlockBehaviour$OffsetType
+ XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StateArgumentPredicate
+ XXX.block.state.BlockBehaviour$StatePredicate
- XXX.block.state.BlockState
- XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.block.state.StateHolder$1
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
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
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$SubProviderEntry
+ XXX.data.loot.LootTableSubProvider
- XXX.data.loot.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ItemModelGenerators$TrimModelData
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.CraftingRecipeBuilder
+ XXX.data.recipes.CraftingRecipeBuilder$1
- XXX.data.recipes.CraftingRecipeBuilder$CraftingResult
+ XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.LegacyUpgradeRecipeBuilder
+ XXX.data.recipes.LegacyUpgradeRecipeBuilder$Result
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeCategory
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SmithingTransformRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder$Result
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SmithingTrimRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.UpdateOneTwentyRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
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
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
- XXX.data.tags.UpdateOneTwentyBiomeTagsProvider
+ XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.SavedDataVillageCropFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimpleRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WeaponSmithChestLootTableFix
+ XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_6$1
+ XXX.datafix.schemas.V1451_6$2
- XXX.datafix.schemas.V3327
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
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
- XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToHiveGoal
+ XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
- XXX.entity.animal.Bee$BeeGrowCropGoal
+ XXX.entity.animal.Bee$BeeHurtByOtherGoal
- XXX.entity.animal.Bee$BeeLocateHiveGoal
+ XXX.entity.animal.Bee$BeeLookControl
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Bucketable
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.CatVariant
- XXX.entity.animal.Chicken
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.Dolphin
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.FrogVariant
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.IronGolem$Crackiness
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
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
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
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
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$1
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$1
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
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
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecart$1
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestBoat$1
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
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
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.LegacyUpgradeRecipe
- XXX.item.crafting.LegacyUpgradeRecipe$Serializer
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
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
+ XXX.item.crafting.SimpleCraftingRecipeSerializer
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
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
- XXX.item.enchantment.EnchantmentCategory
+ XXX.item.enchantment.EnchantmentCategory$1
- XXX.item.enchantment.EnchantmentCategory$10
+ XXX.item.enchantment.EnchantmentCategory$11
- XXX.item.enchantment.EnchantmentCategory$12
+ XXX.item.enchantment.EnchantmentCategory$13
- XXX.item.enchantment.EnchantmentCategory$14
+ XXX.item.enchantment.EnchantmentCategory$2
- XXX.item.enchantment.EnchantmentCategory$3
+ XXX.item.enchantment.EnchantmentCategory$4
- XXX.item.enchantment.EnchantmentCategory$5
+ XXX.item.enchantment.EnchantmentCategory$6
- XXX.item.enchantment.EnchantmentCategory$7
+ XXX.item.enchantment.EnchantmentCategory$8
- XXX.item.enchantment.EnchantmentCategory$9
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.FireAspectEnchantment
- XXX.item.enchantment.FishingSpeedEnchantment
+ XXX.item.enchantment.FrostWalkerEnchantment
- XXX.item.enchantment.KnockbackEnchantment
+ XXX.item.enchantment.LootBonusEnchantment
- XXX.item.enchantment.MendingEnchantment
+ XXX.item.enchantment.MultiShotEnchantment
- XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.ProtectionEnchantment
- XXX.item.enchantment.ProtectionEnchantment$Type
+ XXX.item.enchantment.QuickChargeEnchantment
- XXX.item.enchantment.SoulSpeedEnchantment
+ XXX.item.enchantment.SweepingEdgeEnchantment
- XXX.item.enchantment.SwiftSneakEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
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
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.NetworkPacketSummary
+ XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.jfr.stats.TimeStamped
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
+ XXX.level.biome.MultiNoiseBiomeSource$Preset
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
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
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BambooStalkBlock
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
+ XXX.level.block.ChainBlock
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.CherryLeavesBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DirtPathBlock
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
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
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
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GravelBlock
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
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PinkPetalsBlock
- XXX.level.block.SuspiciousSandBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.loot.packs.package-info
- XXX.loot.packs.UpdateOneTwentyChestLoot
+ XXX.loot.packs.UpdateOneTwentyEntityLoot
- XXX.loot.packs.UpdateOneTwentyFishingLoot
+ XXX.loot.packs.UpdateOneTwentyLootTableProvider
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
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
- XXX.minecraft.advancements.AdvancementList
+ XXX.minecraft.advancements.AdvancementList$Listener
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementProgress$Serializer
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.FrameType
+ XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.RequirementsStrategy
+ XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$1
+ XXX.minecraft.commands.CommandBuildContext$2
- XXX.minecraft.commands.CommandBuildContext$2$1
+ XXX.minecraft.commands.CommandBuildContext$3
- XXX.minecraft.commands.CommandBuildContext$Configurable
+ XXX.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
- XXX.minecraft.commands.CommandFunction
+ XXX.minecraft.commands.CommandFunction$CacheableFunction
- XXX.minecraft.commands.CommandFunction$CommandEntry
+ XXX.minecraft.commands.CommandFunction$Entry
- XXX.minecraft.commands.CommandFunction$FunctionEntry
+ XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$1
- XXX.minecraft.commands.Commands$1$1
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.CommandSigningContext
+ XXX.minecraft.commands.CommandSigningContext$1
- XXX.minecraft.commands.CommandSigningContext$SignedArguments
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.data.package-info
+ XXX.minecraft.util.package-info
- XXX.minecraft.world.BossEvent
+ XXX.minecraft.world.BossEvent$BossBarColor
- XXX.minecraft.world.BossEvent$BossBarOverlay
+ XXX.minecraft.world.Clearable
- XXX.minecraft.world.CompoundContainer
+ XXX.minecraft.world.Container
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplate$JsonFactory
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
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
+ XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
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
- XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockSetType
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.package-info
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
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
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
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsoptionMobEffect
- XXX.world.effect.AttackDamageMobEffect
+ XXX.world.effect.HealthBoostMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffectCategory
+ XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffectInstance$FactorData
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Interaction
- XXX.world.entity.package-info
- XXX.world.entity.Targeting
+ XXX.world.entity.TraceableEntity
- XXX.world.entity.VariantHolder
+ XXX.world.entity.WalkAnimationState
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
+ XXX.world.inventory.LegacySmithingMenu
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
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.package-info
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorResolver
+ XXX.world.level.CommonLevelAccessor
- XXX.world.level.CustomSpawner
+ XXX.world.level.DataPackConfig
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
- XXX.world.level.Level$2
+ XXX.world.level.Level$ExplosionInteraction
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelHeightAccessor
- XXX.world.level.LevelHeightAccessor$1
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.LocalMobCapCalculator
+ XXX.world.level.LocalMobCapCalculator$MobCounts
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
- XXX.world.ticks.ContainerSingleItem
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
net.minecraft.FileUtil +4M
```
```
XXX.commands.arguments.StringRepresentableArgument +1M
```
```
XXX.minecraft.core.Registry +16M -12M
```
```
XXX.minecraft.core.RegistrySynchronization +8M -7M
```
```
XXX.minecraft.core.Vec3i +2M -3M
```
```
XXX.core.registries.BuiltInRegistries +1P
```
```
XXX.core.registries.Registries +2P
```
```
XXX.minecraft.data.BlockFamilies +1P
```
```
XXX.loot.packs.UpdateOneTwentyBlockLoot +3M
```
```
XXX.data.tags.UpdateOneTwentyItemTagsProvider +1M -1M
```
```
XXX.data.tags.VanillaItemTagsProvider +1M -1M
```
```
XXX.worldgen.biome.OverworldBiomes +2M -2M
```
```
XXX.worldgen.features.TreeFeatures +1M | +2P
```
```
XXX.worldgen.placement.VegetationPlacements +2P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.minecraft.nbt.CompoundTag +4M -3M
```
```
XXX.minecraft.nbt.NbtOps +30M -17M
```
```
XXX.protocol.status.ClientboundStatusResponsePacket +4M -2M | -1P
```
```
XXX.minecraft.resources.RegistryFileCodec +9M -5M
```
```
XXX.minecraft.resources.RegistryOps +11M -7M
```
```
XXX.server.level.ChunkMap +3M -1M
```
```
XXX.server.level.ServerPlayer -2M
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.minecraft.util.CommonColors +2P
```
```
XXX.minecraft.util.ExtraCodecs$1 +1M
```
```
XXX.minecraft.util.ExtraCodecs$4 +1M
```
```
XXX.minecraft.util.ExtraCodecs$XorCodec +2M -1M
```
```
XXX.minecraft.util.Mth +1M -1M
```
```
XXX.util.datafix.DataFixTypes -1M | +1P
```
```
XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix +3M -2M
```
```
XXX.datafix.fixes.ChunkStructuresTemplateRenameFix +4M -3M
```
```
XXX.datafix.fixes.IglooMetadataRemovalFix +4M -3M
```
```
XXX.datafix.fixes.SavedDataFeaturePoolElementFix +1M
```
```
XXX.datafix.schemas.V1460 +4M -5M
```
```
XXX.world.entity.Display +1M -1M | +1P
```
```
XXX.world.entity.Entity +5M -1M
```
```
XXX.world.entity.EntityEvent +1P
```
```
XXX.world.entity.FlyingMob -1M
```
```
XXX.world.entity.ItemBasedSteering +3M | -1P
```
```
XXX.world.entity.LivingEntity +6M -1M | +1P -1P
```
```
XXX.world.entity.Mob -1M
```
```
XXX.animal.horse.AbstractHorse +19M -11M | +9P
```
```
XXX.world.item.PotionItem -1M
```
```
XXX.world.item.UseAnim +1P
```
```
XXX.level.biome.OverworldBiomeBuilder +1M | +1P
```
```
XXX.level.block.PressurePlateBlock +1M -3M | -2P
```
```
XXX.level.block.SoundType +7P
```
```
XXX.level.block.TrapDoorBlock +1M -1M | +1P -2P
```
```
XXX.block.entity.BlockEntityType +2P
```
```
XXX.block.entity.JukeboxBlockEntity +16M -7M | +2P -1P
```
```
XXX.block.state.BlockBehaviour$1 +1P
```
```
XXX.state.properties.Property +3M -2M
```
```
XXX.level.chunk.LevelChunk +1M
```
```
XXX.level.chunk.LevelChunkSection +1M
```
```
XXX.level.chunk.PalettedContainer +7M -5M
```
```
XXX.levelgen.feature.DesertWellFeature +4M
```
```
XXX.feature.foliageplacers.FancyFoliagePlacer +1M -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +2M -1M
```
```
XXX.levelgen.presets.WorldPreset +1M
```
```
XXX.levelgen.presets.WorldPresets$Bootstrap +2M -1M | +1P
```
```
XXX.structure.placement.RandomSpreadStructurePlacement +2M -1M
```
```
XXX.structure.structures.DesertPyramidPiece +8M | +1P
```
```
XXX.structure.templatesystem.StructureTemplate -1P
```
```
XXX.loot.parameters.LootContextParamSets +1M | +1P
```
```
XXX.world.phys.AABB +1M
```
```
XXX.world.phys.Vec3 +2M
```

</details>
<details>
<summary>
net.minecraft.FileUtil
</summary>

```diff
- String lambda$decomposePath$0(String)
- String lambda$decomposePath$1(String)
- String lambda$decomposePath$2(String,String)
- String lambda$decomposePath$3(String,String)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.StringRepresentableArgument
</summary>

```diff
- String convertId(String)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ DataResult lambda$byNameCodec$0(ResourceLocation)
+ DataResult lambda$byNameCodec$2(Object)
- DataResult lambda$byNameCodec$2(ResourceLocation)
+ DataResult lambda$byNameCodec$3(Object)
- DataResult lambda$byNameCodec$4(Object)
- DataResult lambda$byNameCodec$5(Object)
- DataResult lambda$holderByNameCodec$11(Holder)
- DataResult lambda$holderByNameCodec$12(Holder)
+ DataResult lambda$holderByNameCodec$5(ResourceLocation)
+ DataResult lambda$holderByNameCodec$6(ResourceLocation)
+ DataResult lambda$holderByNameCodec$7(Holder)
+ DataResult lambda$holderByNameCodec$8(Holder)
- DataResult lambda$holderByNameCodec$8(ResourceLocation)
- DataResult lambda$holderByNameCodec$9(ResourceLocation)
+ IllegalStateException lambda$getHolderOrThrow$12(ResourceKey)
- IllegalStateException lambda$getHolderOrThrow$16(ResourceKey)
+ int lambda$byNameCodec$4(Object)
- int lambda$byNameCodec$6(Object)
+ Lifecycle lambda$holderByNameCodec$10(Holder)
- Lifecycle lambda$holderByNameCodec$13(Holder)
- Lifecycle lambda$holderByNameCodec$14(Holder)
+ Lifecycle lambda$holderByNameCodec$9(Holder)
+ Object lambda$keys$11(DynamicOps,ResourceLocation)
- Object lambda$keys$15(DynamicOps,ResourceLocation)
- String lambda$byNameCodec$0(ResourceLocation)
- String lambda$byNameCodec$3(Object)
- String lambda$holderByNameCodec$10(Holder)
- String lambda$holderByNameCodec$7(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.core.RegistrySynchronization
</summary>

```diff
+ Codec lambda$makeNetworkCodec$5(ResourceKey,Codec)
- Codec lambda$makeNetworkCodec$6(ResourceKey,Codec)
+ DataResult lambda$getNetworkCodec$3(ResourceKey)
- DataResult lambda$getNetworkCodec$4(ResourceKey)
+ DataResult lambda$makeNetworkCodec$4(Registry)
- DataResult lambda$makeNetworkCodec$5(Registry)
+ DataResult lambda$makeNetworkCodec$6(ResourceKey)
- DataResult lambda$makeNetworkCodec$7(ResourceKey)
- Map lambda$captureMap$10(RegistryAccess)
+ Map lambda$captureMap$9(RegistryAccess)
+ Registry lambda$captureMap$8(RegistryAccess$RegistryEntry)
- Registry lambda$captureMap$9(RegistryAccess$RegistryEntry)
+ ResourceKey lambda$captureMap$7(RegistryAccess$RegistryEntry)
- ResourceKey lambda$captureMap$8(RegistryAccess$RegistryEntry)
- String lambda$getNetworkCodec$3(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
+ DataResult lambda$offsetCodec$3(int,Vec3i)
- DataResult lambda$offsetCodec$4(int,Vec3i)
- String lambda$offsetCodec$3(int,Vec3i)
+ Vec3i offset(double,double,double)
+ void <init>(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.UpdateOneTwentyBlockLoot
</summary>

```diff
- LootTable$Builder lambda$generate$3(UpdateOneTwentyBlockLoot,Block)
- LootTable$Builder lambda$generate$4(UpdateOneTwentyBlockLoot,Block)
- LootTable$Builder lambda$generate$5(Block)
```

</details>
<details>
<summary>
net.minecraft.data.tags.UpdateOneTwentyItemTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture,CompletableFuture,CompletableFuture)
+ void <init>(PackOutput,CompletableFuture,TagsProvider)
```

</details>
<details>
<summary>
net.minecraft.data.tags.VanillaItemTagsProvider
</summary>

```diff
- void <init>(PackOutput,CompletableFuture,CompletableFuture)
+ void <init>(PackOutput,CompletableFuture,TagsProvider)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.OverworldBiomes
</summary>

```diff
- Biome biome(boolean,float,float,int,int,Integer,Integer,MobSpawnSettings$Builder,BiomeGenerationSettings$Builder,Music)
+ Biome biome(boolean,float,float,int,int,MobSpawnSettings$Builder,BiomeGenerationSettings$Builder,Music)
+ Biome meadow(HolderGetter,HolderGetter)
- Biome meadowOrCherryGrove(HolderGetter,HolderGetter,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.TreeFeatures
</summary>

```diff
- TreeConfiguration$TreeConfigurationBuilder cherry()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void continuouslyUse(BlockPos,Player,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
+ DataResult lambda$static$0(Dynamic)
- DataResult lambda$static$1(Dynamic)
+ Dynamic lambda$static$1(CompoundTag)
- Dynamic lambda$static$2(CompoundTag)
+ String lambda$createReport$2(String)
- String lambda$createReport$3(String)
- String lambda$static$0(Tag)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtOps
</summary>

```diff
+ boolean lambda$remove$15(String,String)
- boolean lambda$remove$28(String,String)
+ DataResult lambda$mergeToList$0(Tag,NbtOps$ListCollector)
+ DataResult lambda$mergeToList$1(Tag)
+ DataResult lambda$mergeToList$2(List,NbtOps$ListCollector)
- DataResult lambda$mergeToList$2(Tag,NbtOps$ListCollector)
+ DataResult lambda$mergeToList$3(Tag)
- DataResult lambda$mergeToList$4(Tag)
- DataResult lambda$mergeToList$5(List,NbtOps$ListCollector)
- DataResult lambda$mergeToList$7(Tag)
- Pair lambda$getMapValues$15(CompoundTag,String)
+ Pair lambda$getMapValues$7(CompoundTag,String)
- String lambda$getList$27(Tag)
- String lambda$getMap$20(Tag)
- String lambda$getMapEntries$19(Tag)
- String lambda$getMapValues$16(Tag)
- String lambda$getNumberValue$0()
- String lambda$getStream$24()
- String lambda$getStringValue$1()
- String lambda$mergeToList$3(Tag)
- String lambda$mergeToList$6(Tag)
- String lambda$mergeToMap$11(Tag)
- String lambda$mergeToMap$14(List)
- String lambda$mergeToMap$8(Tag)
- String lambda$mergeToMap$9(Tag)
+ Tag lambda$getStream$11(Tag)
+ Tag lambda$getStream$12(Tag)
- Tag lambda$getStream$22(Tag)
- Tag lambda$getStream$23(Tag)
+ void lambda$createMap$10(CompoundTag,Pair)
- void lambda$createMap$21(CompoundTag,Pair)
+ void lambda$getList$13(Consumer,Tag)
+ void lambda$getList$14(ListTag,Consumer)
- void lambda$getList$25(Consumer,Tag)
- void lambda$getList$26(ListTag,Consumer)
- void lambda$getMapEntries$17(BiConsumer,CompoundTag,String)
- void lambda$getMapEntries$18(CompoundTag,BiConsumer)
+ void lambda$getMapEntries$8(BiConsumer,CompoundTag,String)
+ void lambda$getMapEntries$9(CompoundTag,BiConsumer)
- void lambda$mergeToMap$10(CompoundTag,CompoundTag,String)
- void lambda$mergeToMap$12(CompoundTag,CompoundTag,String)
- void lambda$mergeToMap$13(List,CompoundTag,Pair)
+ void lambda$mergeToMap$4(CompoundTag,CompoundTag,String)
+ void lambda$mergeToMap$5(CompoundTag,CompoundTag,String)
+ void lambda$mergeToMap$6(List,CompoundTag,Pair)
+ void lambda$remove$16(CompoundTag,CompoundTag,String)
- void lambda$remove$29(CompoundTag,CompoundTag,String)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
</summary>

```diff
- boolean equals(Object)
- int hashCode()
+ ServerStatus getStatus()
- ServerStatus status()
- String toString()
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryFileCodec
</summary>

```diff
+ DataResult lambda$decode$3(ResourceKey)
- DataResult lambda$decode$7(ResourceKey)
+ DataResult lambda$encode$0(DynamicOps,Object,ResourceKey)
+ DataResult lambda$encode$1(DynamicOps,Object,Object)
- DataResult lambda$encode$1(DynamicOps,Object,ResourceKey)
- DataResult lambda$encode$2(DynamicOps,Object,Object)
+ Pair lambda$decode$2(Pair)
+ Pair lambda$decode$4(Pair,Holder$Reference)
- Pair lambda$decode$8(Pair,Holder$Reference)
- Pair lambda$decode$9(Pair)
- String lambda$decode$3()
- String lambda$decode$4()
- String lambda$decode$6(ResourceKey)
- String lambda$encode$0(Holder)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryOps
</summary>

```diff
- DataResult lambda$retrieveElement$10(ResourceKey,ResourceKey,DynamicOps)
+ DataResult lambda$retrieveElement$5(ResourceKey)
+ DataResult lambda$retrieveElement$6(ResourceKey,ResourceKey,DynamicOps)
- DataResult lambda$retrieveElement$8(ResourceKey)
+ DataResult lambda$retrieveGetter$1(ResourceKey)
+ DataResult lambda$retrieveGetter$2(ResourceKey,DynamicOps)
- DataResult lambda$retrieveGetter$2(ResourceKey)
- DataResult lambda$retrieveGetter$4(ResourceKey,DynamicOps)
- Holder$Reference lambda$retrieveElement$11(Object)
+ Holder$Reference lambda$retrieveElement$7(Object)
+ HolderGetter lambda$retrieveGetter$3(Object)
- HolderGetter lambda$retrieveGetter$5(Object)
+ Optional lambda$retrieveElement$4(ResourceKey,RegistryOps$RegistryInfo)
- Optional lambda$retrieveElement$6(ResourceKey,RegistryOps$RegistryInfo)
- String lambda$retrieveElement$7(ResourceKey)
- String lambda$retrieveElement$9()
- String lambda$retrieveGetter$1(ResourceKey)
- String lambda$retrieveGetter$3()
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- List lambda$resendBiomesForChunks$56(ServerPlayer)
- void lambda$resendBiomesForChunks$57(ServerPlayer,List)
- void resendBiomesForChunks(List)
+ void resendChunk(ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean startRiding(Entity,boolean)
+ void stopRiding()
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$1
</summary>

```diff
- String lambda$apply$0(MutableObject)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$4
</summary>

```diff
- String lambda$decode$0(Object,Exception)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$XorCodec
</summary>

```diff
+ DataResult lambda$encode$2(DynamicOps,Object,Object)
- DataResult lambda$encode$4(DynamicOps,Object,Object)
- String lambda$decode$2(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
+ int lerp(float,int,int)
- int lerpInt(float,int,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.DataFixTypes
</summary>

```diff
+ DSL$TypeReference getType()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
</summary>

```diff
+ Integer lambda$cap$2(Dynamic)
- Map lambda$cap$2(Dynamic,int,int,int,int,long)
+ Typed lambda$cap$4(OpticFinder,OpticFinder,Type,Typed)
- Typed lambda$cap$5(OpticFinder,OpticFinder,Type,Typed)
- void lambda$cap$4(List,Type,Dynamic,Map)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
</summary>

```diff
- Dynamic fixChildren(Dynamic)
- Dynamic lambda$fixChildren$1(Dynamic,Dynamic)
- Dynamic lambda$fixChildren$2(Dynamic,Dynamic)
+ Dynamic lambda$makeRule$0(Typed,Dynamic)
- Typed lambda$makeRule$0(Typed)
+ Typed lambda$makeRule$1(Typed,Typed)
+ Typed lambda$makeRule$2(OpticFinder,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
</summary>

```diff
+ Boolean lambda$fixTag$0(Stream)
- Boolean lambda$fixTag$1(Stream)
+ boolean lambda$removeIglooPieces$1(Dynamic)
- boolean lambda$removeIglooPieces$2(Dynamic)
+ Stream lambda$removeIglooPieces$2(Stream)
- Stream lambda$removeIglooPieces$3(Stream)
- Typed lambda$makeRule$0(Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
</summary>

```diff
- String lambda$get$2(int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1460
</summary>

```diff
- TypeTemplate lambda$registerTypes$41(Map)
+ TypeTemplate lambda$registerTypes$41(Schema)
+ TypeTemplate lambda$registerTypes$42(Map)
- TypeTemplate lambda$registerTypes$42(Schema)
- TypeTemplate lambda$registerTypes$44()
+ TypeTemplate lambda$registerTypes$44(Schema)
+ TypeTemplate lambda$registerTypes$46()
- TypeTemplate lambda$registerTypes$46(Schema)
+ TypeTemplate lambda$registerTypes$47(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Display
</summary>

```diff
- float calculateInterpolationProgress(float)
+ float calculateInterpolationProgress(long,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean canBeHitByProjectile()
- boolean isEffectiveAi()
+ Entity getControllingPassenger()
- float maxUpStep()
- LivingEntity getControllingPassenger()
- void setMaxUpStep(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.FlyingMob
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ItemBasedSteering
</summary>

```diff
- float boostFactor()
- int boostTimeTotal()
- void tickBoost()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ boolean isEffectiveAi()
- float getFlyingSpeed()
- float getRiddenSpeed(LivingEntity)
- LivingEntity getLastAttacker()
- Vec3 getRiddenInput(LivingEntity,Vec3)
- void tickRidden(LivingEntity,Vec3)
- void travelRidden(LivingEntity,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
+ boolean isControlledByLocalInstance()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ boolean lambda$getSlot$1(ItemStack)
+ boolean lambda$getSlot$2(ItemStack)
- boolean lambda$getSlot$7(ItemStack)
- boolean lambda$getSlot$8(ItemStack)
+ boolean lambda$static$0(LivingEntity)
- boolean lambda$static$6(LivingEntity)
+ boolean mountIgnoresControllerInput(LivingEntity)
- double createOffspringAttribute(double,double,double,double,RandomSource)
- double generateJumpStrength(DoubleSupplier)
+ double generateRandomJumpStrength(RandomSource)
+ double generateRandomSpeed(RandomSource)
- double generateSpeed(DoubleSupplier)
- double lambda$static$0()
- double lambda$static$1()
- double lambda$static$2()
- double lambda$static$3()
+ Entity getControllingPassenger()
- float generateMaxHealth(IntUnaryOperator)
+ float generateRandomMaxHealth(RandomSource)
+ float getDrivenMovementSpeed(LivingEntity)
- float getRiddenSpeed(LivingEntity)
- int lambda$static$4(int)
- int lambda$static$5(int)
- Vec2 getRiddenRotation(LivingEntity)
- Vec3 getRiddenInput(LivingEntity,Vec3)
+ void executeRidersJump(float,float,float)
- void executeRidersJump(float,Vec3)
- void setOffspringAttribute(AgeableMob,AbstractHorse,Attribute,double,double)
- void tickRidden(LivingEntity,Vec3)
+ void travel(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.item.PotionItem
</summary>

```diff
+ boolean isFoil(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeBuilder
</summary>

```diff
- void <init>(OverworldBiomeBuilder$Modifier)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PressurePlateBlock
</summary>

```diff
- void <init>(PressurePlateBlock$Sensitivity,BlockBehaviour$Properties,BlockSetType)
+ void <init>(PressurePlateBlock$Sensitivity,BlockBehaviour$Properties,SoundEvent,SoundEvent)
+ void playOffSound(LevelAccessor,BlockPos)
+ void playOnSound(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,BlockSetType)
+ void <init>(BlockBehaviour$Properties,SoundEvent,SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.JukeboxBlockEntity
</summary>

```diff
- boolean canPlaceItem(int,ItemStack)
- boolean canTakeItem(Container,int,ItemStack)
- boolean isRecordPlaying()
+ boolean recordIsPlaying(BlockState,JukeboxBlockEntity)
+ boolean recordShouldStopPlaying(JukeboxBlockEntity,RecordItem)
- boolean shouldRecordStopPlaying(RecordItem)
- boolean shouldSendJukeboxPlayingEvent()
+ boolean shouldSendJukeboxPlayingEvent(JukeboxBlockEntity)
- boolean stillValid(Player)
- int getMaxStackSize()
- ItemStack getItem(int)
+ ItemStack getRecord()
- ItemStack removeItem(int,int)
+ void clearContent()
+ void playRecord()
- void popOutRecord()
- void setHasRecordBlockState(Entity,boolean)
- void setItem(int,ItemStack)
+ void setRecord(ItemStack)
- void setRecordWithoutPlaying(ItemStack)
- void startPlaying()
- void stopPlaying()
- void tick(Level,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.Property
</summary>

```diff
+ DataResult lambda$new$0(String)
- DataResult lambda$new$2(String)
+ StateHolder lambda$parseValue$2(StateHolder,Comparable)
- StateHolder lambda$parseValue$3(StateHolder,Comparable)
- String lambda$new$0(String)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
- void replaceBiomes(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.LevelChunkSection
</summary>

```diff
- void readBiomes(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
- int lambda$pack$11(HashMapPalette,int)
+ int lambda$pack$9(HashMapPalette,int)
+ int lambda$unpack$7(int,Object)
+ int lambda$unpack$8(IdMap,Palette,int)
- int lambda$unpack$8(int,Object)
- int lambda$unpack$9(IdMap,Palette,int)
- String lambda$unpack$10(SimpleBitStorage$InitializationException)
- String lambda$unpack$7()
+ void lambda$count$10(Int2IntOpenHashMap,int)
+ void lambda$count$11(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$count$12(Int2IntOpenHashMap,int)
- void lambda$count$13(PalettedContainer$CountConsumer,Int2IntMap$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertWellFeature
</summary>

```diff
- void lambda$placeSandFloor$0(BlockPos,ObjectArrayList)
- void lambda$placeSandFloor$1(BlockPos,SuspiciousSandBlockEntity)
- void lambda$placeSandFloor$2(MutableInt,WorldGenLevel,BlockPos)
- void placeSandFloor(WorldGenLevel,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
+ boolean lambda$updateLayers$5(BlockState)
- boolean lambda$updateLayers$6(BlockState)
- String lambda$validateHeight$5()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPreset
</summary>

```diff
- String lambda$requireOverworld$3()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
</summary>

```diff
- void bootstrap()
- void registerOverworlds(BiomeSource)
+ void run()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
</summary>

```diff
+ DataResult lambda$static$1(RandomSpreadStructurePlacement)
- DataResult lambda$static$2(RandomSpreadStructurePlacement)
- String lambda$static$1()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
</summary>

```diff
- List getPotentialSuspiciousSandWorldPositions()
- void addCellar(WorldGenLevel,BoundingBox)
- void addCellarRoom(BlockPos,WorldGenLevel,BoundingBox)
- void addCellarStairs(BlockPos,WorldGenLevel,BoundingBox)
- void placeCollapsedRoof(WorldGenLevel,BoundingBox,int,int,int,int,int)
- void placeCollapsedRoofPiece(WorldGenLevel,int,int,int,BoundingBox)
- void placeSand(int,int,int,BoundingBox)
- void placeSandBox(BoundingBox,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
</summary>

```diff
- void lambda$static$12(LootContextParamSet$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
- double distanceToSqr(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.phys.Vec3
</summary>

```diff
- Vec3 atLowerCornerWithOffset(Vec3i,double,double,double)
- Vec3 offsetRandom(RandomSource,float)
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
+ net.minecraft.package-info
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- XXX.advancements.packs.UpdateOneTwentyAdventureAdvancements
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
+ XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue
+ XXX.animal.frog.ShootTongue$1
- XXX.animal.frog.ShootTongue$State
+ XXX.animal.frog.Tadpole
- XXX.animal.frog.TadpoleAi
- XXX.animal.goat.Goat
+ XXX.animal.goat.GoatAi
- XXX.animal.goat.package-info
+ XXX.animal.horse.AbstractChestedHorse
- XXX.animal.horse.AbstractChestedHorse$1
+ XXX.animal.horse.AbstractHorse
- XXX.animal.horse.AbstractHorse$1
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
- XXX.animal.sniffer.Sniffer$1
- XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Searching
+ XXX.animation.definitions.package-info
- XXX.animation.definitions.WardenAnimation
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.BlockStateParser$BlockResult
- XXX.arguments.blocks.BlockStateParser$TagResult
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemParser$TagResult
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
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
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
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
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity
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
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.SuspiciousSandBlockEntity
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.MangroveTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
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
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.LiteralContents
+ XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
- XXX.chat.report.ChatReportBuilder
+ XXX.chat.report.ChatReportBuilder$CannotBuildReason
- XXX.chat.report.ChatReportBuilder$ChatReport
+ XXX.chat.report.ChatReportBuilder$Result
- XXX.chat.report.ChatReportContextBuilder
+ XXX.chat.report.ChatReportContextBuilder$Collector
- XXX.chat.report.ChatReportContextBuilder$Handler
+ XXX.chat.report.package-info
+ XXX.chat.report.ReportEnvironment
- XXX.chat.report.ReportEnvironment$Server
+ XXX.chat.report.ReportEnvironment$Server$Realm
- XXX.chat.report.ReportEnvironment$Server$ThirdParty
- XXX.chat.report.ReportingContext
+ XXX.chat.report.ReportReason
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.client.animation.package-info
- XXX.client.gui.ComponentPath
+ XXX.client.gui.ComponentPath$Leaf
- XXX.client.gui.ComponentPath$Path
+ XXX.client.gui.Font
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
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
+ XXX.client.model.CatModel
- XXX.client.model.ChestBoatModel
- XXX.client.model.ChestedHorseModel
+ XXX.client.model.ChestRaftModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColorableAgeableListModel
- XXX.client.model.ColorableHierarchicalModel
+ XXX.client.model.CowModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.FrogModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GoatModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HierarchicalModel
- XXX.client.model.HoglinModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidArmorModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$1
+ XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.IllagerModel
+ XXX.client.model.IronGolemModel
- XXX.client.model.LavaSlimeModel
+ XXX.client.model.LeashKnotModel
- XXX.client.model.ListModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.ModelUtils
- XXX.client.model.OcelotModel
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$1
- XXX.client.model.ParrotModel$State
+ XXX.client.model.PhantomModel
+ XXX.client.model.PiglinHeadModel
- XXX.client.model.PiglinModel
- XXX.client.model.PigModel
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
- XXX.client.multiplayer.package-info
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BaseAshSmokeParticle
- XXX.client.particle.BlockMarker
+ XXX.client.particle.BlockMarker$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$Provider
- XXX.client.particle.BubbleParticle
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$Provider
- XXX.client.particle.CampfireSmokeParticle
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
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
+ XXX.client.particle.DripParticle$DripstoneLavaHangProvider
+ XXX.client.particle.DripParticle$DripstoneWaterHangProvider
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DripParticle$HoneyFallProvider
+ XXX.client.particle.DripParticle$HoneyLandProvider
+ XXX.client.particle.DripParticle$LavaHangProvider
+ XXX.client.particle.DripParticle$NectarFallProvider
+ XXX.client.particle.DripParticle$ObsidianTearHangProvider
+ XXX.client.particle.DripParticle$SporeBlossomFallProvider
+ XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.package-info
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
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SonicBoomParticle
- XXX.client.particle.SonicBoomParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$AmbientMobProvider
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobProvider
- XXX.client.particle.SpellParticle$Provider
+ XXX.client.particle.SpellParticle$WitchProvider
- XXX.client.particle.SpitParticle
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$Provider
- XXX.client.particle.SpriteSet
+ XXX.client.particle.SquidInkParticle
- XXX.client.particle.SquidInkParticle$GlowInkProvider
+ XXX.client.particle.SquidInkParticle$Provider
- XXX.client.particle.SuspendedParticle
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
- XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
- XXX.client.particle.SuspendedTownParticle$Provider
+ XXX.client.particle.TerrainParticle
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
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
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
+ XXX.client.player.package-info
- XXX.client.player.RemotePlayer
- XXX.client.profiling.ClientMetricsSamplersProvider
+ XXX.client.profiling.package-info
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.BlockEntityWithoutLevelRenderer
- XXX.client.renderer.ChunkBufferBuilderPack
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
- XXX.client.renderer.LevelRenderer$RenderChunkInfo
+ XXX.client.renderer.LevelRenderer$RenderChunkStorage
- XXX.client.renderer.LevelRenderer$RenderInfoMap
+ XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
+ XXX.client.renderer.PanoramaRenderer
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostPass
- XXX.client.renderer.Rect2i
+ XXX.client.renderer.RenderBuffers
- XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
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
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DefaultPlayerSkin$ModelType
+ XXX.client.resources.DefaultPlayerSkin$SkinType
- XXX.client.resources.DownloadedPackSource
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.IndexedAssetSource
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.package-info
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$2
- XXX.client.resources.SkinManager$SkinTextureCallback
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
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
+ XXX.commands.arguments.package-info
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
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TemplateMirrorArgument
+ XXX.commands.arguments.TemplateRotationArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.TimeArgument$Info
- XXX.commands.arguments.TimeArgument$Info$Template
+ XXX.commands.arguments.UuidArgument
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
+ XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypeInfos
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SingletonArgumentInfo
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.tabs.GridLayoutTab
+ XXX.components.tabs.package-info
+ XXX.components.tabs.Tab
- XXX.components.tabs.TabManager
+ XXX.components.tabs.TabNavigationBar
- XXX.components.tabs.TabNavigationBar$Builder
- XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastIds
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
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
- XXX.core.registries.BuiltInRegistries
+ XXX.core.registries.BuiltInRegistries$RegistryBootstrap
+ XXX.core.registries.package-info
- XXX.core.registries.Registries
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
- XXX.data.tags.package-info
- XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.UpdateOneTwentyBiomeTagsProvider
+ XXX.data.tags.UpdateOneTwentyBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyItemTagsProvider
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
- XXX.data.worldgen.BootstapContext
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
- XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
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
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockRenameFixWithJigsaw
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
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
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingFieldsRenameFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.SavedDataVillageCropFix
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
- XXX.datafix.schemas.V3328
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.entity.animal.package-info
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.CapeLayer
- XXX.entity.layers.CarriedBlockLayer
+ XXX.entity.layers.CatCollarLayer
- XXX.entity.layers.CreeperPowerLayer
+ XXX.entity.layers.CrossedArmsItemLayer
- XXX.entity.layers.CustomHeadLayer
+ XXX.entity.layers.Deadmau5EarsLayer
- XXX.entity.layers.DolphinCarryingItemLayer
+ XXX.entity.layers.DrownedOuterLayer
- XXX.entity.layers.ElytraLayer
+ XXX.entity.layers.EnderEyesLayer
- XXX.entity.layers.EnergySwirlLayer
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseArmorLayer
- XXX.entity.layers.HorseMarkingLayer
+ XXX.entity.layers.HumanoidArmorLayer
- XXX.entity.layers.HumanoidArmorLayer$1
+ XXX.entity.layers.IronGolemCrackinessLayer
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.package-info
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SaddleLayer
- XXX.entity.layers.SheepFurLayer
+ XXX.entity.layers.ShulkerHeadLayer
- XXX.entity.layers.SlimeOuterLayer
+ XXX.entity.layers.SnowGolemHeadLayer
- XXX.entity.layers.SpiderEyesLayer
+ XXX.entity.layers.SpinAttackEffectLayer
- XXX.entity.layers.StrayClothingLayer
+ XXX.entity.layers.StuckInBodyLayer
- XXX.entity.layers.TropicalFishPatternLayer
+ XXX.entity.layers.TropicalFishPatternLayer$1
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WardenEmissiveLayer
- XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
+ XXX.entity.layers.WardenEmissiveLayer$DrawSelector
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfCollarLayer
- XXX.entity.player.package-info
+ XXX.entity.player.PlayerRenderer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
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
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$1
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Builder
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
- XXX.font.providers.GlyphProviderBuilder
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.LegacyUnicodeBitmapsProvider
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Sheet
- XXX.font.providers.package-info
+ XXX.font.providers.TrueTypeGlyphProviderBuilder
+ XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationListener
+ XXX.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
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
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollWidget
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractStringWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.AccessibilityOnboardingTextWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.BossHealthOverlay$1
- XXX.gui.components.Button
+ XXX.gui.components.Button$Builder
- XXX.gui.components.Button$CreateNarration
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.ChatComponent
+ XXX.gui.components.ChatComponent$DelayedMessageDeletion
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.CommonButtons
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$1
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
+ XXX.gui.components.package-info
- XXX.gui.components.TabOrderedElement
+ XXX.gui.components.TextAndImageButton
- XXX.gui.components.TextAndImageButton$Builder
+ XXX.gui.components.Tooltip
- XXX.gui.components.Whence
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontSet$GlyphInfoFilter
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$Node
+ XXX.gui.font.package-info
- XXX.gui.font.TextFieldHelper
+ XXX.gui.font.TextFieldHelper$1
- XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.layouts.AbstractLayout
- XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
+ XXX.gui.layouts.FrameLayout
- XXX.gui.layouts.FrameLayout$ChildContainer
+ XXX.gui.layouts.GridLayout
- XXX.gui.layouts.GridLayout$CellInhabitant
+ XXX.gui.layouts.GridLayout$RowHelper
- XXX.gui.layouts.HeaderAndFooterLayout
+ XXX.gui.layouts.Layout
- XXX.gui.layouts.LayoutElement
+ XXX.gui.layouts.LayoutSettings
- XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
+ XXX.gui.layouts.LinearLayout
- XXX.gui.layouts.LinearLayout$1
+ XXX.gui.layouts.LinearLayout$ChildContainer
- XXX.gui.layouts.LinearLayout$Orientation
- XXX.gui.layouts.package-info
+ XXX.gui.layouts.SpacerElement
+ XXX.gui.narration.NarratableEntry
- XXX.gui.narration.NarratableEntry$NarrationPriority
+ XXX.gui.narration.NarratedElementType
- XXX.gui.narration.NarrationElementOutput
+ XXX.gui.narration.NarrationSupplier
- XXX.gui.narration.NarrationThunk
- XXX.gui.narration.package-info
+ XXX.gui.narration.ScreenNarrationCollector
- XXX.gui.narration.ScreenNarrationCollector$1
+ XXX.gui.narration.ScreenNarrationCollector$EntryKey
- XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
+ XXX.gui.narration.ScreenNarrationCollector$Output
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenAxis$1
+ XXX.gui.navigation.ScreenDirection
- XXX.gui.navigation.ScreenDirection$1
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.BanNoticeScreen
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DeathScreen$TitleConfirmScreen
+ XXX.gui.screens.package-info
- XXX.gui.screens.RealmsNotificationsScreen$3
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$1
+ XXX.gui.screens.RealmsPendingInvitesScreen$2
- XXX.gui.screens.RealmsPendingInvitesScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPlayerScreen
- XXX.gui.screens.RealmsPlayerScreen$Entry
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- XXX.gui.screens.RealmsPlayerScreen$UserAction
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$Builder
- XXX.gui.task.DataFetcher
+ XXX.gui.task.DataFetcher$ComputationResult
- XXX.gui.task.DataFetcher$SubscribedTask
+ XXX.gui.task.DataFetcher$Subscription
- XXX.gui.task.DataFetcher$SuccessfulComputationResult
+ XXX.gui.task.DataFetcher$Task
+ XXX.gui.task.package-info
- XXX.gui.task.RepeatedDelayStrategy
+ XXX.gui.task.RepeatedDelayStrategy$1
- XXX.gui.task.RepeatedDelayStrategy$2
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
- XXX.item.armortrim.TrimMaterial
+ XXX.item.armortrim.TrimMaterials
- XXX.item.armortrim.TrimPattern
+ XXX.item.armortrim.TrimPatterns
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
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.level.biome.MultiNoiseBiomeSource$Preset
- XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$3
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
- XXX.level.biome.OverworldBiomeBuilder$Modifier
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
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
- XXX.level.block.package-info
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
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SuspiciousEffectHolder
- XXX.level.block.TorchflowerCropBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
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
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$TicksToSave
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LevelChunkSection$1BlockCounter
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
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
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
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListenerRegistry
- XXX.level.gameevent.GameEventListenerRegistry$1
+ XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.Aquifer
+ XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$FluidPicker
+ XXX.level.levelgen.Aquifer$FluidStatus
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Beardifier$1
+ XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.BelowZeroRetrogen
+ XXX.level.levelgen.BelowZeroRetrogen$1
- XXX.level.levelgen.BitRandomSource
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Density
+ XXX.level.levelgen.DensityFunction
- XXX.level.levelgen.DensityFunction$ContextProvider
+ XXX.level.levelgen.DensityFunction$FunctionContext
- XXX.level.levelgen.DensityFunction$NoiseHolder
+ XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$SinglePointContext
+ XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions
+ XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$HolderHolder
- XXX.level.levelgen.DensityFunctions$Mapped
+ XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker
+ XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MarkerOrMarked
+ XXX.level.levelgen.DensityFunctions$MulOrAdd
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
+ XXX.level.levelgen.DensityFunctions$Noise
- XXX.level.levelgen.DensityFunctions$PureTransformer
+ XXX.level.levelgen.DensityFunctions$RangeChoice
- XXX.level.levelgen.DensityFunctions$Shift
+ XXX.level.levelgen.DensityFunctions$ShiftA
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
+ XXX.level.levelgen.DensityFunctions$ShiftNoise
+ XXX.level.levelgen.DensityFunctions$Spline
- XXX.level.levelgen.DensityFunctions$Spline$Coordinate
+ XXX.level.levelgen.DensityFunctions$Spline$Point
- XXX.level.levelgen.DensityFunctions$TransformerWithContext
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ XXX.level.levelgen.DensityFunctions$YClampedGradient
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
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
+ XXX.level.levelgen.WorldDimensions$1Entry
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.WorldOptions
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
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
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.MaterialColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
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
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
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
+ XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
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
- XXX.levelgen.placement.CarvingMaskPlacement
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CountOnEveryLayerPlacement
+ XXX.levelgen.placement.CountPlacement
- XXX.levelgen.placement.EnvironmentScanPlacement
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
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureType
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.TerrainAdjustment
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetInstrumentFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetPotionFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.packs.UpdateOneTwentyBlockLoot
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
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
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.minecraft.client.package-info
- XXX.minecraft.commands.package-info
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
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedMappedRegistry
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$1
+ XXX.minecraft.core.Direction$Axis
- XXX.minecraft.core.Direction$Axis$1
+ XXX.minecraft.core.Direction$Axis$2
- XXX.minecraft.core.Direction$Axis$3
+ XXX.minecraft.core.Direction$AxisDirection
- XXX.minecraft.core.Direction$Plane
+ XXX.minecraft.core.Direction8
- XXX.minecraft.core.FrontAndTop
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.Holder
+ XXX.minecraft.core.Holder$Direct
- XXX.minecraft.core.Holder$Kind
+ XXX.minecraft.core.Holder$Reference
- XXX.minecraft.core.Holder$Reference$Type
+ XXX.minecraft.core.HolderGetter
- XXX.minecraft.core.HolderGetter$Provider
+ XXX.minecraft.core.HolderLookup
- XXX.minecraft.core.HolderLookup$1
+ XXX.minecraft.core.HolderLookup$Delegate
- XXX.minecraft.core.HolderLookup$Provider
+ XXX.minecraft.core.HolderLookup$Provider$1
- XXX.minecraft.core.HolderLookup$Provider$2
+ XXX.minecraft.core.HolderLookup$RegistryLookup
- XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ XXX.minecraft.core.HolderOwner
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LayeredRegistryAccess
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.MappedRegistry$1
+ XXX.minecraft.core.MappedRegistry$2
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$2
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$CompositeOwner
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents$1
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$NetworkedRegistryData
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
- XXX.minecraft.data.CachedOutput
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataGenerator$PackGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.DataProvider$Factory
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.HashCache$ProviderCacheBuilder
+ XXX.minecraft.data.HashCache$UpdateFunction
- XXX.minecraft.data.HashCache$UpdateResult
+ XXX.minecraft.data.Main
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
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
+ XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
- XXX.minecraft.nbt.NbtOps$HomogenousListCollector
+ XXX.minecraft.nbt.NbtOps$InitialListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.FriendlyByteBuf$1
+ XXX.minecraft.network.FriendlyByteBuf$Reader
- XXX.minecraft.network.FriendlyByteBuf$Writer
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.PacketSendListener$1
- XXX.minecraft.network.PacketSendListener$2
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
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
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$1
+ XXX.minecraft.resources.RegistryOps$2
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Dummy
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
- XXX.minecraft.server.package-info
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
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
- XXX.minecraft.tags.package-info
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
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
- XXX.minecraft.util.ByIdMap$1
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CommonColors
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
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$EitherCodec
+ XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.ExtraCodecs$XorCodec
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ABGR32
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.ResourceLocationPattern
- XXX.minecraft.util.SegmentedAnglePrecision
+ XXX.minecraft.util.SignatureUpdater
- XXX.minecraft.util.SignatureUpdater$Output
+ XXX.minecraft.util.SignatureValidator
- XXX.minecraft.util.Signer
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SingleKeyCache
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.SpawnUtil
- XXX.minecraft.util.SpawnUtil$Strategy
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$DelayedTask
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
- XXX.minecraft.world.package-info
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
- XXX.mojang.realmsclient.package-info
- XXX.mojang.realmsclient.RealmsMainScreen$ButtonEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
- XXX.mojang.realmsclient.RealmsMainScreen$CrossButton
+ XXX.mojang.realmsclient.RealmsMainScreen$HoveredElement
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmsCall
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ XXX.mojang.realmsclient.Unit
+ XXX.multiplayer.prediction.BlockStatePredictionHandler
- XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- XXX.multiplayer.prediction.package-info
+ XXX.multiplayer.prediction.PredictiveAction
+ XXX.multiplayer.resolver.AddressCheck
- XXX.multiplayer.resolver.AddressCheck$1
+ XXX.multiplayer.resolver.package-info
+ XXX.multiplayer.resolver.ResolvedServerAddress
- XXX.multiplayer.resolver.ResolvedServerAddress$1
+ XXX.multiplayer.resolver.ServerAddress
- XXX.multiplayer.resolver.ServerAddressResolver
+ XXX.multiplayer.resolver.ServerNameResolver
- XXX.multiplayer.resolver.ServerRedirectHandler
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
- XXX.network.chat.ChatDecorator
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Bound
+ XXX.network.chat.ChatType$BoundNetwork
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$1
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
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenTrackedEntry
- XXX.network.chat.LocalChatSession
+ XXX.network.chat.MessageSignature
- XXX.network.chat.MessageSignature$Packed
+ XXX.network.chat.MessageSignatureCache
- XXX.network.chat.MutableComponent
+ XXX.network.chat.OutgoingChatMessage
- XXX.network.chat.OutgoingChatMessage$Disguised
+ XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.RemoteChatSession
- XXX.network.chat.RemoteChatSession$Data
+ XXX.network.chat.SignableCommand
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
+ XXX.network.chat.SignedMessageChain
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
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$2
+ XXX.network.protocol.BundlerInfo$2$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.BundlerInfo$Provider
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
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
- XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
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
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$Info
+ XXX.packs.repository.Pack$Position
- XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
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
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
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
- XXX.protocol.game.ClientboundBundlePacket
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket
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
- XXX.protocol.game.ClientboundDamageEventPacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundDisguisedChatPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
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
- XXX.protocol.game.ClientboundPingPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerChatPacket
- XXX.protocol.game.ClientboundPlayerCombatEndPacket
+ XXX.protocol.game.ClientboundPlayerCombatEnterPacket
- XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoRemovePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundServerDataPacket
- XXX.protocol.game.ClientboundSetActionBarTextPacket
+ XXX.protocol.game.ClientboundSetBorderCenterPacket
- XXX.protocol.game.ClientboundSetBorderLerpSizePacket
+ XXX.protocol.game.ClientboundSetBorderSizePacket
- XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
+ XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
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
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
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
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
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
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
- XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
- XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
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
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
- XXX.realmsclient.dto.Backup
+ XXX.realmsclient.dto.BackupList
- XXX.realmsclient.dto.GuardedSerializer
+ XXX.realmsclient.dto.Ops
- XXX.realmsclient.dto.PendingInvite
+ XXX.realmsclient.dto.PendingInvitesList
- XXX.realmsclient.dto.PingResult
+ XXX.realmsclient.dto.PlayerInfo
- XXX.realmsclient.dto.RealmsDescriptionDto
+ XXX.realmsclient.dto.RealmsNews
- XXX.realmsclient.dto.RealmsNotification
- XXX.realmsclient.dto.RealmsServer
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPing
+ XXX.realmsclient.dto.RealmsServerPlayerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.util.JsonUtils
- XXX.realmsclient.util.LevelType
- XXX.realmsclient.util.package-info
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.RealmsUtil$1
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.realmsclient.util.WorldGenerationInfo
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
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.SuspiciousSandRenderer$1
- XXX.renderer.entity.package-info
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
+ XXX.renderer.entity.WitchRenderer
- XXX.renderer.entity.WitherBossRenderer
+ XXX.renderer.entity.WitherSkeletonRenderer
- XXX.renderer.entity.WitherSkullRenderer
+ XXX.renderer.entity.WolfRenderer
- XXX.renderer.entity.ZoglinRenderer
+ XXX.renderer.entity.ZombieRenderer
- XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.item.ClampedItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
- XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
+ XXX.renderer.item.ItemProperties
- XXX.renderer.item.ItemProperties$1
+ XXX.renderer.item.ItemPropertyFunction
- XXX.renderer.item.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.SpriteContents
- XXX.renderer.texture.SpriteContents$AnimatedTexture
+ XXX.renderer.texture.SpriteContents$FrameInfo
- XXX.renderer.texture.SpriteContents$InterpolationData
+ XXX.renderer.texture.SpriteContents$Ticker
- XXX.renderer.texture.SpriteLoader
+ XXX.renderer.texture.SpriteLoader$Preparations
- XXX.renderer.texture.SpriteTicker
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Entry
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$Ticker
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.Tickable
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
- XXX.resources.sounds.AbstractSoundInstance
+ XXX.resources.sounds.AbstractTickableSoundInstance
- XXX.resources.sounds.AmbientSoundHandler
+ XXX.resources.sounds.BeeAggressiveSoundInstance
- XXX.resources.sounds.BeeFlyingSoundInstance
+ XXX.resources.sounds.BeeSoundInstance
- XXX.resources.sounds.BiomeAmbientSoundsHandler
+ XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- XXX.resources.sounds.BubbleColumnAmbientSoundHandler
+ XXX.resources.sounds.ElytraOnPlayerSoundInstance
- XXX.resources.sounds.EntityBoundSoundInstance
+ XXX.resources.sounds.GuardianAttackSoundInstance
- XXX.resources.sounds.MinecartSoundInstance
+ XXX.resources.sounds.RidingMinecartSoundInstance
- XXX.resources.sounds.SimpleSoundInstance
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
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
- XXX.server.commands.DebugCommand$Tracer
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
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
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ResetChunksCommand
- XXX.server.commands.RideCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
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
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
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
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$FullChunkStatus
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
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
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerGamePacketListenerImpl$2
+ XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilterClient
- XXX.server.network.TextFilterClient$IgnoreStrategy
+ XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
- XXX.server.network.TextFilterClient$MessageEncoder
+ XXX.server.network.TextFilterClient$PlayerContext
- XXX.server.network.TextFilterClient$RequestFailedException
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.BuiltInMetadata
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResourcesBuilder
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
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ChestType$1
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
+ XXX.structure.pieces.package-info
+ XXX.structure.pieces.PieceGenerator
- XXX.structure.pieces.PieceGenerator$Context
+ XXX.structure.pieces.PieceGeneratorSupplier
- XXX.structure.pieces.PieceGeneratorSupplier$Context
+ XXX.structure.pieces.PiecesContainer
- XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceSerializationContext
+ XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$ContextlessType
+ XXX.structure.pieces.StructurePieceType$StructureTemplateType
- XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
+ XXX.structure.placement.RandomSpreadStructurePlacement
- XXX.structure.placement.RandomSpreadType
+ XXX.structure.placement.RandomSpreadType$1
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
+ XXX.structure.pools.FeaturePoolElement
- XXX.structure.pools.JigsawJunction
+ XXX.structure.pools.JigsawPlacement
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
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
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
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
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
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
- XXX.texture.atlas.package-info
+ XXX.texture.atlas.SpriteResourceLoader
- XXX.texture.atlas.SpriteResourceLoader$1
+ XXX.texture.atlas.SpriteSource
- XXX.texture.atlas.SpriteSource$Output
+ XXX.texture.atlas.SpriteSource$SpriteSupplier
+ XXX.texture.atlas.SpriteSources
- XXX.texture.atlas.SpriteSourceType
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.PackedBitStorage
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
- XXX.util.task.package-info
+ XXX.util.task.ResettingGeneratedWorldTask
- XXX.util.task.ResettingTemplateWorldTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
+ XXX.util.task.WorldCreationTask
- XXX.world.entity.Attackable
+ XXX.world.entity.Display
- XXX.world.entity.Display$1
+ XXX.world.entity.Display$2
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$ColorInterpolator
+ XXX.world.entity.Display$FloatInterpolator
- XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$Interpolator
+ XXX.world.entity.Display$InterpolatorSet
+ XXX.world.entity.Display$IntInterpolator
- XXX.world.entity.Display$ItemDisplay
+ XXX.world.entity.Display$ItemDisplay$1
- XXX.world.entity.Display$TextDisplay
+ XXX.world.entity.Display$TextDisplay$Align
- XXX.world.entity.Display$TextDisplay$CachedInfo
+ XXX.world.entity.Display$TextDisplay$CachedLine
- XXX.world.entity.Display$TextDisplay$LineSplitter
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction$PlayerAction
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LerpingModel
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
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
- XXX.world.entity.RiderShieldingMount
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
- XXX.world.item.BrushItem
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeableArmorItem
- XXX.world.item.DyeableHorseArmorItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.Equipable
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkRocketItem$Shape
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
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
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
+ XXX.world.item.ItemStackLinkedSet
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
- XXX.world.item.Vanishable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.package-info
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.worldgen.biome.Biomes
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
XXX.blaze3d.platform.NativeImage +1M -1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen +36M -29M | +10P -7P
```
```
XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList +1M -1M
```
```
XXX.minecraft.client.Minecraft +33M -30M
```
```
XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange +2M -1M
```
```
XXX.gui.screens.OptionsScreen +1M -1M
```
```
XXX.gui.screens.Screen +1M
```
```
XXX.screens.advancements.AdvancementTab +2M -2M
```
```
XXX.screens.controls.KeyBindsList$KeyEntry -2M
```
```
XXX.screens.inventory.AbstractContainerScreen +1M -1M
```
```
XXX.screens.inventory.InventoryScreen +2M -2M
```
```
XXX.screens.inventory.LegacySmithingScreen -1M
```
```
XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry +1M -1M | +1P -1P
```
```
XXX.screens.packs.PackSelectionModel +1M
```
```
XXX.screens.packs.PackSelectionModel$EntryBase +1M
```
```
XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent +1M
```
```
XXX.screens.recipebook.RecipeBookTabButton +1M -1M
```
```
XXX.screens.worldselection.CreateWorldScreen +11M -14M | +2P
```
```
XXX.screens.worldselection.ExperimentsScreen -1M
```
```
XXX.client.main.Main -1M
```
```
XXX.model.geom.ModelLayers +3P
```
```
XXX.model.geom.ModelPart$Cube +1M -1M
```
```
XXX.model.geom.PartNames +2P
```
```
XXX.geom.builders.CubeDefinition +1M -1M | +1P
```
```
XXX.geom.builders.CubeListBuilder +2M | +1P
```
```
XXX.client.multiplayer.ClientChunkCache +1M
```
```
XXX.multiplayer.chat.ChatLog +3M -2M
```
```
XXX.client.particle.ParticleEngine +13M -10M
```
```
XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer -1P
```
```
XXX.client.sounds.SoundManager +3P
```
```
XXX.advancements.packs.VanillaAdventureAdvancements +1M
```
```
XXX.advancements.packs.VanillaNetherAdvancements -1P
```
```
XXX.data.info.BiomeParametersDumpReport +1M -1M | +2P
```
```
XXX.loot.packs.VanillaBlockLoot +16M -15M
```
```
XXX.data.models.BlockModelGenerators +41M -36M
```
```
XXX.models.model.ModelTemplates +4P
```
```
XXX.models.model.TextureSlot +1P
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M | +1P
```
```
XXX.data.registries.VanillaRegistries +1M
```
```
XXX.data.tags.IntrinsicHolderTagsProvider +1M
```
```
XXX.data.tags.ItemTagsProvider +7M -1M | +2P -1P
```
```
XXX.data.tags.TagsProvider +14M -6M | +2P -1P
```
```
XXX.protocol.status.ServerStatus$Version +8M -2M | +1P
```
```
XXX.util.datafix.DataFixers +1M -1M | -1P
```
```
XXX.util.valueproviders.BiasedToBottomInt +2M -1M
```
```
XXX.util.valueproviders.ClampedNormalFloat +2M -1M
```
```
XXX.util.valueproviders.FloatProvider +3M -1M
```
```
XXX.util.valueproviders.IntProvider +4M -1M
```
```
XXX.util.valueproviders.TrapezoidFloat +3M -1M
```
```
XXX.util.valueproviders.UniformInt +2M -1M
```
```
XXX.minecraft.world.Container +3M | +1P
```
```
XXX.entity.ai.Brain$1 +5M -4M
```
```
XXX.ai.behavior.StayCloseToTarget +4M -4M
```
```
XXX.entity.ambient.Bat -1M
```
```
XXX.entity.animal.Cat -1M
```
```
XXX.animal.allay.Allay -1M
```
```
XXX.animal.camel.Camel +5M -4M
```
```
XXX.boss.enderdragon.EnderDragon +1M
```
```
XXX.boss.wither.WitherBoss -1M
```
```
XXX.entity.item.FallingBlockEntity +2M
```
```
XXX.entity.monster.MagmaCube -1M
```
```
XXX.entity.monster.Phantom +1M
```
```
XXX.entity.monster.Ravager +2M -2M
```
```
XXX.entity.monster.Strider +4M -6M | +2P -1P
```
```
XXX.entity.npc.VillagerTrades +1P
```
```
XXX.entity.vehicle.Boat +2M -1M
```
```
XXX.item.crafting.Recipe +1M
```
```
XXX.item.crafting.RecipeSerializer +1P
```
```
XXX.item.crafting.ShapedRecipe +2M | +1P
```
```
XXX.item.enchantment.EnchantmentHelper +1M
```
```
XXX.level.biome.BiomeSource +2M -2M | +2P -1P
```
```
XXX.level.biome.Biomes +1P
```
```
XXX.level.biome.Climate$Parameter +3M -2M
```
```
XXX.level.biome.FixedBiomeSource +1M
```
```
XXX.level.biome.MobSpawnSettings$SpawnerData +2M
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M | +1P -2P
```
```
XXX.level.block.ButtonBlock +1M -1M | +1P -2P
```
```
XXX.level.block.DoorBlock +1M -1M | +1P -2P
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.LevelEvent +3P -1P
```
```
XXX.block.state.BlockBehaviour$Properties +4M -5M | +1P -1P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1M -1M
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1M -1M
```
```
XXX.feature.stateproviders.WeightedStateProvider +1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.NativeImage
</summary>

```diff
+ NativeImage fromBase64(String)
- NativeImage read(byte[])
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
- boolean lambda$dismissNotification$26(UUID,RealmsNotification)
+ boolean lambda$removeServer$18(RealmsServer,RealmsMainScreen$Entry)
- boolean lambda$removeServer$24(RealmsServer,RealmsMainScreen$Entry)
+ boolean lambda$updateTeaserImages$20(ResourceLocation)
+ boolean lambda$updateTeaserImages$21(ResourceLocation)
- boolean lambda$updateTeaserImages$29(ResourceLocation)
- boolean lambda$updateTeaserImages$30(ResourceLocation)
- boolean shouldConfigureButtonBeActive(RealmsServer)
+ boolean shouldConfigureButtonBeVisible(RealmsServer)
- boolean shouldLeaveButtonBeActive(RealmsServer)
+ boolean shouldLeaveButtonBeVisible(RealmsServer)
- Font access$1400(RealmsMainScreen)
+ Font access$1600(RealmsMainScreen)
- Font access$1900(RealmsMainScreen)
+ Font access$2100(RealmsMainScreen)
+ Font access$2900(RealmsMainScreen)
+ Minecraft access$1400(RealmsMainScreen)
- Minecraft access$1600(RealmsMainScreen)
+ Minecraft access$3000(RealmsMainScreen)
+ Minecraft access$3100(RealmsMainScreen)
- Object lambda$callRealmsClient$18(RealmsMainScreen$RealmsCall,Minecraft)
- Object lambda$dismissNotification$25(UUID,RealmsClient)
- Object lambda$refreshRealmsSelectionList$20(List,RealmsClient)
+ void access$1900(RealmsMainScreen,Component)
- void access$2100(RealmsMainScreen,Component)
+ void access$3200(RealmsMainScreen,Component)
+ void addBottomButtons()
- void addEntriesForNotification(RealmsMainScreen$RealmSelectionList,RealmsNotification)
- void addFooterButtons()
- void callRealmsClient(RealmsMainScreen$RealmsCall,Consumer)
- void dismissNotification(UUID)
+ void drawConfigure(PoseStack,int,int,int,int)
+ void drawLeave(PoseStack,int,int,int,int)
+ void lambda$addBottomButtons$10(Button)
+ void lambda$addBottomButtons$6(Button)
+ void lambda$addBottomButtons$7(Button)
+ void lambda$addBottomButtons$8(Button)
+ void lambda$addBottomButtons$9(Button)
- void lambda$addFooterButtons$10(Button)
- void lambda$addFooterButtons$11(RealmsMainScreen,GuiEventListener)
- void lambda$addFooterButtons$6(Button)
- void lambda$addFooterButtons$7(Button)
- void lambda$addFooterButtons$8(Button)
- void lambda$addFooterButtons$9(Button)
- Void lambda$callRealmsClient$19(Throwable)
+ void lambda$charTyped$19(char,KeyCombo)
- void lambda$charTyped$28(char,KeyCombo)
- void lambda$dismissNotification$27(UUID,Object)
+ void lambda$initDataFetcher$11(List)
+ void lambda$initDataFetcher$12(Integer)
- void lambda$initDataFetcher$12(List)
+ void lambda$initDataFetcher$13(Boolean)
- void lambda$initDataFetcher$13(List)
- void lambda$initDataFetcher$14(Integer)
+ void lambda$initDataFetcher$14(RealmsServerPlayerLists)
- void lambda$initDataFetcher$15(Boolean)
+ void lambda$initDataFetcher$15(RealmsDataFetcher,RealmsNews)
- void lambda$initDataFetcher$16(RealmsServerPlayerLists)
- void lambda$initDataFetcher$17(RealmsDataFetcher,RealmsNews)
+ void lambda$leaveClicked$17(RealmsServer,boolean)
- void lambda$leaveClicked$23(RealmsServer,boolean)
+ void lambda$pingRegions$16()
- void lambda$pingRegions$22()
- void lambda$refreshRealmsSelectionList$21(List,Object)
- void refreshRealmsSelectionList()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
</summary>

```diff
- void itemClicked(int,int,double,double,int,int)
+ void itemClicked(int,int,double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ boolean lambda$tick$39()
- boolean lambda$tick$40()
+ ChunkProgressListener lambda$doWorldLoad$40(int)
- ChunkProgressListener lambda$doWorldLoad$41(int)
+ CompletionStage lambda$delayTextureReload$51(CompletableFuture)
- CompletionStage lambda$delayTextureReload$52(CompletableFuture)
+ IntegratedServer lambda$doWorldLoad$41(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
- IntegratedServer lambda$doWorldLoad$42(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
+ String lambda$doWorldLoad$42(WorldStem)
- String lambda$doWorldLoad$43(WorldStem)
+ String lambda$fillSystemReport$44(String)
+ String lambda$fillSystemReport$45(Minecraft)
- String lambda$fillSystemReport$45(String)
+ String lambda$fillSystemReport$46()
- String lambda$fillSystemReport$46(Minecraft)
- String lambda$fillSystemReport$49()
+ String lambda$fillSystemReport$49(Options)
+ String lambda$fillSystemReport$50(LanguageManager)
- String lambda$fillSystemReport$50(Options)
- String lambda$fillSystemReport$51(LanguageManager)
+ Style lambda$debugClientMetricsStart$30(Path,Style)
- Style lambda$debugClientMetricsStart$31(Path,Style)
+ Style lambda$grabHugeScreenshot$54(File,Style)
- Style lambda$grabHugeScreenshot$55(File,Style)
+ Style lambda$grabPanoramixScreenshot$53(File,Style)
- Style lambda$grabPanoramixScreenshot$54(File,Style)
- void abortResourcePackRecovery()
- void addResourcePackLoadFailToast(Component)
+ void lambda$debugClientMetricsStart$28(Consumer,double,int)
- void lambda$debugClientMetricsStart$29(Consumer,double,int)
+ void lambda$debugClientMetricsStart$29(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$30(Consumer,ProfileResults)
+ void lambda$debugClientMetricsStart$31(Consumer,Component)
- void lambda$debugClientMetricsStart$32(Consumer,Component)
+ void lambda$debugClientMetricsStart$32(Consumer,Path)
- void lambda$debugClientMetricsStart$33(Consumer,Path)
+ void lambda$debugClientMetricsStart$33(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$34(Consumer,Path)
- void lambda$debugClientMetricsStart$34(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$35(Consumer,CompletableFuture,CompletableFuture)
- void lambda$debugClientMetricsStart$35(Consumer,Path)
- void lambda$debugClientMetricsStart$36(Consumer,CompletableFuture,CompletableFuture)
+ void lambda$debugClientMetricsStart$36(ProfileResults)
+ void lambda$debugClientMetricsStart$37(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$37(ProfileResults)
- void lambda$debugClientMetricsStart$38(Consumer,ProfileResults)
+ void lambda$doWorldLoad$43(Component)
- void lambda$doWorldLoad$44(Component)
+ void lambda$grabPanoramixScreenshot$52(Component)
- void lambda$grabPanoramixScreenshot$53(Component)
+ void lambda$openChatScreen$25(boolean)
- void lambda$openChatScreen$26(boolean)
- void lambda$reloadResourcePacks$23(boolean,Throwable)
+ void lambda$reloadResourcePacks$23(CompletableFuture)
+ void lambda$reloadResourcePacks$24(CompletableFuture,Optional)
- void lambda$reloadResourcePacks$24(CompletableFuture)
- void lambda$reloadResourcePacks$25(boolean,CompletableFuture,Optional)
+ void lambda$runTick$26(CompletableFuture)
- void lambda$runTick$27(CompletableFuture)
+ void lambda$runTick$27(TimerQuery)
- void lambda$runTick$28(TimerQuery)
+ void lambda$tick$38()
- void lambda$tick$39()
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
</summary>

```diff
+ DataResult lambda$codec$0(Integer)
- DataResult lambda$codec$1(Integer)
- String lambda$codec$0(Integer,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.OptionsScreen
</summary>

```diff
- void applyPacks(PackRepository)
+ void updatePackList(PackRepository)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.Screen
</summary>

```diff
- void added()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementTab
</summary>

```diff
- void drawContents(PoseStack,int,int)
+ void drawContents(PoseStack)
+ void drawIcon(int,int,ItemRenderer)
- void drawIcon(PoseStack,int,int,ItemRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
</summary>

```diff
+ boolean mouseClicked(double,double,int)
+ boolean mouseReleased(double,double,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
+ void renderFloatingItem(ItemStack,int,int,String)
- void renderFloatingItem(PoseStack,ItemStack,int,int,String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.InventoryScreen
</summary>

```diff
+ void renderEntityInInventory(int,int,int,Quaternionf,Quaternionf,LivingEntity)
- void renderEntityInInventory(PoseStack,int,int,int,Quaternionf,Quaternionf,LivingEntity)
+ void renderEntityInInventoryFollowsMouse(int,int,int,float,float,LivingEntity)
- void renderEntityInInventoryFollowsMouse(PoseStack,int,int,int,float,float,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.LegacySmithingScreen
</summary>

```diff
+ void renderLabels(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
</summary>

```diff
- boolean uploadServerIcon(byte[])
+ boolean uploadServerIcon(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionModel
</summary>

```diff
- void updateRepoSelectedList()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
</summary>

```diff
- void updateHighContrastOptionInstance()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
</summary>

```diff
- boolean lambda$setupGhostRecipe$0(Item)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
</summary>

```diff
+ void renderIcon(ItemRenderer)
- void renderIcon(PoseStack,ItemRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
- boolean lambda$createNewWorldDirectory$19(Path)
+ boolean lambda$createNewWorldDirectory$23(Path)
- boolean lambda$createTempDataPackDirFromExistingWorld$21(Path,Path)
+ boolean lambda$createTempDataPackDirFromExistingWorld$25(Path,Path)
- DataResult lambda$applyNewPackConfig$13(DynamicOps,JsonElement)
+ DataResult lambda$applyNewPackConfig$15(DynamicOps,JsonElement)
- Object lambda$applyNewPackConfig$17(Consumer,Void,Throwable)
+ Object lambda$applyNewPackConfig$21(Consumer,Void,Throwable)
+ void lambda$applyNewPackConfig$14()
- void lambda$applyNewPackConfig$16(Consumer,boolean)
+ void lambda$applyNewPackConfig$18(Consumer,boolean)
+ void lambda$applyNewPackConfig$19(Consumer)
+ void lambda$applyNewPackConfig$20()
- void lambda$createNewWorldDirectory$20(Path,Path)
+ void lambda$createNewWorldDirectory$24(Path,Path)
- void lambda$createTempDataPackDirFromExistingWorld$22(MutableObject,Path,Path)
+ void lambda$createTempDataPackDirFromExistingWorld$26(MutableObject,Path,Path)
- void lambda$removeTempDataPackDir$18(Path)
+ void lambda$removeTempDataPackDir$22(Path)
+ void lambda$tryApplyNewDataPacks$13(PackRepository,WorldDataConfiguration,Consumer)
- void renderDirtBackground(PoseStack)
- WorldCreationContext lambda$applyNewPackConfig$15(CloseableResourceManager,ReloadableServerResources,LayeredRegistryAccess,CreateWorldScreen$DataPackReloadCookie)
+ WorldCreationContext lambda$applyNewPackConfig$17(CloseableResourceManager,ReloadableServerResources,LayeredRegistryAccess,CreateWorldScreen$DataPackReloadCookie)
- WorldLoader$DataLoadOutput lambda$applyNewPackConfig$14(WorldLoader$DataLoadContext)
+ WorldLoader$DataLoadOutput lambda$applyNewPackConfig$16(WorldLoader$DataLoadContext)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
</summary>

```diff
+ void popScreen()
```

</details>
<details>
<summary>
net.minecraft.client.main.Main
</summary>

```diff
+ void run(String[],boolean)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart$Cube
</summary>

```diff
- void <init>(int,int,float,float,float,float,float,float,float,float,float,boolean,float,float,Set)
+ void <init>(int,int,float,float,float,float,float,float,float,float,float,boolean,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.builders.CubeDefinition
</summary>

```diff
- void <init>(String,float,float,float,float,float,float,float,float,CubeDeformation,boolean,float,float,Set)
+ void <init>(String,float,float,float,float,float,float,float,float,CubeDeformation,boolean,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.builders.CubeListBuilder
</summary>

```diff
- CubeListBuilder addBox(float,float,float,float,float,float,Set)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
- void replaceBiomes(int,int,FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.chat.ChatLog
</summary>

```diff
+ DataResult lambda$codec$0(int,List)
- DataResult lambda$codec$1(int,List)
+ LoggedChatEvent[] lambda$new$1(int,int)
- LoggedChatEvent[] lambda$new$2(int,int)
- String lambda$codec$0(int,int)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleEngine
</summary>

```diff
+ CompletionStage lambda$reload$3(Executor,Map)
- CompletionStage lambda$reload$5(Executor,Map)
+ Map lambda$reload$0(ResourceManager)
- Map lambda$reload$2(ResourceManager)
- Particle lambda$register$0(ParticleProvider$Sprite,SpriteSet,ParticleOptions,ClientLevel,double,double,double,double,double,double)
+ ParticleEngine$1ParticleDefinition lambda$reload$1(ResourceLocation,Resource)
- ParticleEngine$1ParticleDefinition lambda$reload$3(ResourceLocation,Resource)
- ParticleProvider lambda$register$1(ParticleProvider$Sprite,SpriteSet)
+ Queue lambda$tick$7(ParticleRenderType)
- Queue lambda$tick$9(ParticleRenderType)
- void lambda$destroy$11(BlockPos,BlockState,double,double,double,double,double,double)
+ void lambda$destroy$9(BlockPos,BlockState,double,double,double,double,double,double)
+ void lambda$reload$2(List,Executor,ResourceLocation,Resource)
- void lambda$reload$4(List,Executor,ResourceLocation,Resource)
+ void lambda$reload$4(SpriteLoader$Preparations,Set,TextureAtlasSprite,ParticleEngine$1ParticleDefinition)
+ void lambda$reload$5(ProfilerFiller,CompletableFuture,CompletableFuture,Void)
- void lambda$reload$6(SpriteLoader$Preparations,Set,TextureAtlasSprite,ParticleEngine$1ParticleDefinition)
- void lambda$reload$7(ProfilerFiller,CompletableFuture,CompletableFuture,Void)
+ void lambda$tick$6(ParticleRenderType,Queue)
- void lambda$tick$8(ParticleRenderType,Queue)
- void lambda$tickParticleList$10(ParticleGroup)
+ void lambda$tickParticleList$8(ParticleGroup)
- void register(ParticleType,ParticleProvider$Sprite)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
</summary>

```diff
- void createAdventuringTime(Consumer,Advancement,MultiNoiseBiomeSourceParameterList$Preset)
```

</details>
<details>
<summary>
net.minecraft.data.info.BiomeParametersDumpReport
</summary>

```diff
+ CompletableFuture lambda$run$0(HolderGetter,CachedOutput,DynamicOps,Pair)
- void lambda$run$0(List,CachedOutput,DynamicOps,MultiNoiseBiomeSourceParameterList$Preset,Climate$ParameterList)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
+ LootPoolEntryContainer$Builder lambda$generate$223(Block,Integer)
- LootPoolEntryContainer$Builder lambda$generate$225(Block,Integer)
- LootTable$Builder lambda$generate$190(Block)
+ LootTable$Builder lambda$generate$190(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$192(Block)
- LootTable$Builder lambda$generate$192(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$197(Block)
+ LootTable$Builder lambda$generate$197(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$199(Block)
- LootTable$Builder lambda$generate$199(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$201(Block)
+ LootTable$Builder lambda$generate$201(ItemLike)
+ LootTable$Builder lambda$generate$204(Block)
- LootTable$Builder lambda$generate$204(ItemLike)
- LootTable$Builder lambda$generate$205(Block)
+ LootTable$Builder lambda$generate$205(ItemLike)
- LootTable$Builder lambda$generate$207(ItemLike)
+ LootTable$Builder lambda$generate$207(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$208(Block)
- LootTable$Builder lambda$generate$208(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$215(Block)
+ LootTable$Builder lambda$generate$215(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$217(Block)
- LootTable$Builder lambda$generate$217(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$219(Block)
+ LootTable$Builder lambda$generate$219(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$221(Block)
- LootTable$Builder lambda$generate$221(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$223(Block)
+ LootTable$Builder lambda$generate$225(Block)
- LootTable$Builder lambda$generate$231(Block)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ List lambda$createTurtleEgg$35(Integer,Integer)
- List lambda$createTurtleEgg$37(Integer,Integer)
+ ResourceLocation lambda$addBookSlotModel$47(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- ResourceLocation lambda$addBookSlotModel$49(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
+ ResourceLocation lambda$createCropBlock$11(Block,int,int)
- ResourceLocation lambda$createCropBlock$13(Block,int,int)
+ TextureMapping lambda$createChorusFlower$14(TextureMapping,ResourceLocation)
- TextureMapping lambda$createChorusFlower$16(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createCommandBlock$7(TextureMapping,ResourceLocation)
- TextureMapping lambda$createCommandBlock$9(TextureMapping,ResourceLocation)
+ Variant lambda$createActiveRail$6(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
- Variant lambda$createActiveRail$8(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
- Variant lambda$createBambooModels$10(String,int)
+ Variant lambda$createBambooModels$8(String,int)
+ Variant lambda$createCropBlock$12(int[],Int2ObjectMap,Block,Integer)
- Variant lambda$createCropBlock$14(int[],Int2ObjectMap,Block,Integer)
- Variant lambda$createCrossBlock$6(int[],Block,BlockModelGenerators$TintState,Integer)
+ Variant lambda$createEmptyOrFullDispatch$10(Comparable,Variant,Variant,Comparable)
- Variant lambda$createEmptyOrFullDispatch$12(Comparable,Variant,Variant,Comparable)
+ Variant lambda$createFire$16(Variant)
+ Variant lambda$createFire$17(Variant)
- Variant lambda$createFire$22(Variant)
- Variant lambda$createFire$23(Variant)
+ Variant lambda$createJigsaw$49(FrontAndTop)
- Variant lambda$createJigsaw$51(FrontAndTop)
+ Variant lambda$createRepeater$30(Integer,Boolean,Boolean)
- Variant lambda$createRepeater$32(Integer,Boolean,Boolean)
+ Variant lambda$createRespawnAnchor$48(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$50(ResourceLocation[],Integer)
+ Variant lambda$createSculkCatalyst$44(ResourceLocation,ResourceLocation,Boolean)
- Variant lambda$createSculkCatalyst$46(ResourceLocation,ResourceLocation,Boolean)
+ Variant lambda$createSculkSensor$29(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createSculkSensor$31(ResourceLocation,ResourceLocation,SculkSensorPhase)
+ Variant lambda$createSnowBlocks$31(ResourceLocation,Integer)
- Variant lambda$createSnowBlocks$33(ResourceLocation,Integer)
+ Variant lambda$createSoulFire$22(Variant)
+ Variant lambda$createSoulFire$23(Variant)
- Variant lambda$createSoulFire$27(Variant)
- Variant lambda$createSoulFire$28(Variant)
+ Variant lambda$createStems$5(Block,TextureMapping,Integer)
- Variant lambda$createStems$7(Block,TextureMapping,Integer)
+ Variant lambda$createStructureBlock$32(StructureMode)
- Variant lambda$createStructureBlock$34(StructureMode)
- Variant lambda$createSuspiciousSandBlock$5(Integer)
+ Variant lambda$createSweetBerryBush$33(Integer)
- Variant lambda$createSweetBerryBush$35(Integer)
+ Variant lambda$createTripwireHook$34(Boolean,Boolean)
- Variant lambda$createTripwireHook$36(Boolean,Boolean)
+ Variant lambda$static$36(ResourceLocation)
+ Variant lambda$static$37(ResourceLocation)
- Variant lambda$static$42(ResourceLocation)
- Variant lambda$static$43(ResourceLocation)
+ Variant lambda$wrapModels$15(ResourceLocation)
- Variant lambda$wrapModels$17(ResourceLocation)
- void createCrossBlock(Block,BlockModelGenerators$TintState,Property,int[])
- void createFlowerBed(Block)
- void createSuspiciousSandBlock()
+ void lambda$addSlotStateAndRotationVariants$46(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,BooleanProperty,ModelTemplate)
- void lambda$addSlotStateAndRotationVariants$48(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,BooleanProperty,ModelTemplate)
- void lambda$createBarrel$11(ResourceLocation,TextureMapping)
+ void lambda$createBarrel$9(ResourceLocation,TextureMapping)
+ void lambda$createChiseledBookshelf$45(MultiPartGenerator,ResourceLocation,Direction,VariantProperties$Rotation)
- void lambda$createChiseledBookshelf$47(MultiPartGenerator,ResourceLocation,Direction,VariantProperties$Rotation)
+ void lambda$createFurnace$13(ResourceLocation,TextureMapping)
- void lambda$createFurnace$15(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$27(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$28(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$29(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$30(ResourceLocation,TextureMapping)
+ void lambda$createMultiface$42(Block,Condition$TerminalCondition,BooleanProperty)
+ void lambda$createMultiface$43(Block,Condition$TerminalCondition)
- void lambda$createMultiface$44(Block,Condition$TerminalCondition,BooleanProperty)
- void lambda$createMultiface$45(Block,Condition$TerminalCondition)
+ void lambda$run$50(BlockFamily)
+ void lambda$run$51(SpawnEggItem)
- void lambda$run$52(BlockFamily)
- void lambda$run$53(SpawnEggItem)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean)
+ void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.data.registries.VanillaRegistries
</summary>

```diff
- void validateThatAllBiomeFeaturesHaveBiomeFilter(HolderGetter,HolderLookup)
```

</details>
<details>
<summary>
net.minecraft.data.tags.IntrinsicHolderTagsProvider
</summary>

```diff
- void <init>(PackOutput,ResourceKey,CompletableFuture,CompletableFuture,Function)
```

</details>
<details>
<summary>
net.minecraft.data.tags.ItemTagsProvider
</summary>

```diff
- CompletableFuture contentsProvider()
- HolderLookup$Provider lambda$contentsProvider$4(HolderLookup$Provider,TagsProvider$TagLookup)
- IllegalStateException lambda$contentsProvider$2(TagKey)
- ResourceKey lambda$new$1(Item)
- void <init>(PackOutput,CompletableFuture,CompletableFuture,CompletableFuture)
- void <init>(PackOutput,CompletableFuture,CompletableFuture)
+ void <init>(PackOutput,CompletableFuture,TagsProvider)
- void lambda$contentsProvider$3(TagsProvider$TagLookup,TagKey,TagKey)
```

</details>
<details>
<summary>
net.minecraft.data.tags.TagsProvider
</summary>

```diff
+ boolean lambda$run$0(HolderLookup$RegistryLookup,ResourceLocation)
+ boolean lambda$run$1(Predicate,TagEntry)
- boolean lambda$run$2(HolderLookup$RegistryLookup,ResourceLocation)
- boolean lambda$run$3(TagsProvider$1CombinedData,ResourceLocation)
- boolean lambda$run$4(Predicate,Predicate,TagEntry)
- CompletableFuture contentsGetter()
- CompletableFuture contentsProvider()
+ CompletableFuture lambda$run$2(Predicate,CachedOutput,Map$Entry)
- CompletableFuture lambda$run$5(Predicate,Predicate,CachedOutput,Map$Entry)
+ CompletableFuture[] lambda$run$3(int)
- CompletableFuture[] lambda$run$6(int)
+ CompletionStage lambda$run$4(CachedOutput,HolderLookup$Provider)
- CompletionStage lambda$run$7(CachedOutput,TagsProvider$1CombinedData)
- HolderLookup$Provider lambda$new$0(HolderLookup$Provider)
- Optional lambda$contentsGetter$9(TagKey)
+ TagBuilder lambda$getOrCreateRawBuilder$5(ResourceLocation)
- TagBuilder lambda$getOrCreateRawBuilder$8(ResourceLocation)
- TagsProvider$1CombinedData lambda$run$1(HolderLookup$Provider,TagsProvider$TagLookup)
- TagsProvider$TagLookup lambda$contentsGetter$10(HolderLookup$Provider)
- void <init>(PackOutput,ResourceKey,CompletableFuture,CompletableFuture)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.status.ServerStatus$Version
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ int getProtocol()
- int hashCode()
- int protocol()
- ServerStatus$Version current()
+ String getName()
- String name()
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.DataFixers
</summary>

```diff
+ DataFixer createFixerUpper()
- DataFixer createFixerUpper(Set)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.BiasedToBottomInt
</summary>

```diff
+ DataResult lambda$static$3(BiasedToBottomInt)
- DataResult lambda$static$4(BiasedToBottomInt)
- String lambda$static$3(BiasedToBottomInt)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.ClampedNormalFloat
</summary>

```diff
+ DataResult lambda$static$5(ClampedNormalFloat)
- DataResult lambda$static$6(ClampedNormalFloat)
- String lambda$static$5(ClampedNormalFloat)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.FloatProvider
</summary>

```diff
+ DataResult lambda$codec$3(float,float,FloatProvider)
- DataResult lambda$codec$5(float,float,FloatProvider)
- String lambda$codec$3(float,FloatProvider)
- String lambda$codec$4(float,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.IntProvider
</summary>

```diff
- Codec codec(int,int,Codec)
+ DataResult lambda$codec$3(int,int,IntProvider)
- DataResult lambda$codec$5(int,int,IntProvider)
- String lambda$codec$3(int,IntProvider)
- String lambda$codec$4(int,IntProvider)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.TrapezoidFloat
</summary>

```diff
+ DataResult lambda$static$4(TrapezoidFloat)
- DataResult lambda$static$6(TrapezoidFloat)
- String lambda$static$4(TrapezoidFloat)
- String lambda$static$5(TrapezoidFloat)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.UniformInt
</summary>

```diff
+ DataResult lambda$static$3(UniformInt)
- DataResult lambda$static$4(UniformInt)
- String lambda$static$3(UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.Container
</summary>

```diff
- boolean canTakeItem(Container,int,ItemStack)
- boolean stillValidBlockEntity(BlockEntity,Player,int)
- boolean stillValidBlockEntity(BlockEntity,Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.Brain$1
</summary>

```diff
+ Brain$MemoryValue lambda$captureRead$7(MemoryModuleType,ExpirableValue)
- Brain$MemoryValue lambda$captureRead$8(MemoryModuleType,ExpirableValue)
+ DataResult lambda$captureRead$5(MemoryModuleType)
+ DataResult lambda$captureRead$6(DynamicOps,Object,Codec)
- DataResult lambda$captureRead$6(MemoryModuleType)
- DataResult lambda$captureRead$7(DynamicOps,Object,Codec)
- String lambda$captureRead$5(MemoryModuleType)
+ void lambda$encode$8(DynamicOps,RecordBuilder,Brain$MemoryValue)
- void lambda$encode$9(DynamicOps,RecordBuilder,Brain$MemoryValue)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.StayCloseToTarget
</summary>

```diff
+ App lambda$create$2(Function,int,float,int,BehaviorBuilder$Instance)
- App lambda$create$2(Function,Predicate,int,float,int,BehaviorBuilder$Instance)
+ BehaviorControl create(Function,int,int,float)
- BehaviorControl create(Function,Predicate,int,int,float)
+ boolean lambda$create$0(Function,int,MemoryAccessor,MemoryAccessor,float,int,ServerLevel,LivingEntity,long)
- boolean lambda$create$0(Function,Predicate,int,MemoryAccessor,MemoryAccessor,float,int,ServerLevel,LivingEntity,long)
+ Trigger lambda$create$1(Function,int,float,int,MemoryAccessor,MemoryAccessor)
- Trigger lambda$create$1(Function,Predicate,int,float,int,MemoryAccessor,MemoryAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ambient.Bat
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
+ boolean mountIgnoresControllerInput(LivingEntity)
+ Entity getControllingPassenger()
+ float getDrivenMovementSpeed(LivingEntity)
- float getRiddenSpeed(LivingEntity)
- Vec2 getRiddenRotation(LivingEntity)
- Vec3 getRiddenInput(LivingEntity,Vec3)
+ void executeRidersJump(float,float,float)
- void executeRidersJump(float,Vec3)
- void tickRidden(LivingEntity,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
- double getPassengersRidingOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.FallingBlockEntity
</summary>

```diff
- Component getTypeName()
- void disableDrop()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.MagmaCube
</summary>

```diff
+ boolean causeFallDamage(float,float,DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- double getPassengersRidingOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ravager
</summary>

```diff
+ boolean canBeControlledBy(Entity)
+ Entity getControllingPassenger()
- float getFlyingSpeed()
- LivingEntity getControllingPassenger()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
+ boolean canBeControlledBy(Entity)
+ Entity getControllingPassenger()
+ float getMoveSpeed()
- float getRiddenSpeed(LivingEntity)
+ float getSteeringSpeed()
- LivingEntity getControllingPassenger()
- Vec3 getRiddenInput(LivingEntity,Vec3)
- void tickRidden(LivingEntity,Vec3)
+ void travel(Vec3)
+ void travelWithInput(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
- boolean hasEnoughSpaceFor(Entity)
+ Entity getControllingPassenger()
- LivingEntity getControllingPassenger()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Recipe
</summary>

```diff
- boolean showNotification()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe
</summary>

```diff
- boolean showNotification()
- void <init>(ResourceLocation,String,CraftingBookCategory,int,int,NonNullList,ItemStack,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
- boolean hasSilkTouch(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
- Set lambda$new$0()
- void <init>()
+ void <init>(List)
+ void <init>(Stream)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Climate$Parameter
</summary>

```diff
+ DataResult lambda$static$0(Float,Float)
- DataResult lambda$static$1(Float,Float)
+ Float lambda$static$1(Climate$Parameter)
- Float lambda$static$3(Climate$Parameter)
- String lambda$static$0(Float,Float)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.FixedBiomeSource
</summary>

```diff
- Stream collectPossibleBiomes()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
</summary>

```diff
- DataResult lambda$static$5(MobSpawnSettings$SpawnerData)
- String lambda$static$4()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,BlockSetType)
+ void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,BlockSetType,int,boolean)
+ void <init>(BlockBehaviour$Properties,int,boolean,SoundEvent,SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,BlockSetType)
+ void <init>(BlockBehaviour$Properties,SoundEvent,SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- void checkPoweredState(Level,BlockPos,BlockState,int)
+ void checkPoweredState(Level,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
+ BlockBehaviour$OffsetType lambda$new$6(BlockState)
+ BlockBehaviour$OffsetType lambda$offsetType$9(BlockBehaviour$OffsetType,BlockState)
+ BlockBehaviour$Properties offsetType(Function)
- MaterialColor lambda$color$7(MaterialColor,BlockState)
+ MaterialColor lambda$color$8(MaterialColor,BlockState)
- MaterialColor lambda$new$6(MaterialColor,BlockState)
+ MaterialColor lambda$new$7(MaterialColor,BlockState)
- Vec3 lambda$offsetType$8(BlockState,BlockGetter,BlockPos)
- Vec3 lambda$offsetType$9(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
+ void createFoliage(LevelSimulatedReader,BiConsumer,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
- void createFoliage(LevelSimulatedReader,FoliagePlacer$FoliageSetter,RandomSource,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
</summary>

```diff
- String lambda$create$1()
```

</details>
</details>
<hr/>