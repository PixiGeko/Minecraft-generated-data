## Comparison with [25w14craftmine](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w14craftmine)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Items (models)](#items-(models))
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>DataPack version</td><td><pre>71</pre></td><td><pre>72</pre></td></tr><tr><td>ResourcePack version</td><td><pre>55</pre></td><td><pre>56</pre></td></tr><tr><td>World version</td><td><pre>4323</pre></td><td><pre>4422</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742068</pre></td><td><pre>1073742069</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- mine_event_type.txt
- player_unlock.txt
- special_mine.txt
- world_effect_set.txt
- world_effect.txt
```

</details>
<details>
<summary>
activity
</summary>

```diff
- minecraft:acting
```

</details>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:camera_distance
- minecraft:experience_gain_modifier
- minecraft:max_jumps
- minecraft:pickup_area_size
+ minecraft:waypoint_receive_range
+ minecraft:waypoint_transmit_range
```

</details>
<details>
<summary>
block
</summary>

```diff
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal
+ minecraft:end_portal_frame
- minecraft:mine_crafter
- minecraft:mine_revisitor
- minecraft:mine_travelling_block
- minecraft:mob_trophy
- minecraft:shimmering_door
- minecraft:sky
- minecraft:trophy
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:end_portal
- minecraft:mine_crafter
- minecraft:mine_travelling_block
- minecraft:mob_trophy
```

</details>
<details>
<summary>
block_type
</summary>

```diff
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal
+ minecraft:end_portal_frame
- minecraft:mine_crafter
- minecraft:mine_revisitor_block
- minecraft:mine_travelling_block
- minecraft:mob_trophy
- minecraft:shimmering_door
- minecraft:terracotta
- minecraft:trophy
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:hex_color
```

</details>
<details>
<summary>
custom_stat
</summary>

```diff
+ minecraft:happy_ghast_one_cm
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
- minecraft:dimension_id
- minecraft:exchange_value
- minecraft:instant_room
- minecraft:mine_active
- minecraft:mine_completed
- minecraft:mob_trophy/type
- minecraft:sky
- minecraft:special_mine
- minecraft:trophy/type
- minecraft:world_effect_uhint
- minecraft:world_effect_unlock
- minecraft:world_modifiers
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:angry_ghast
+ minecraft:happy_ghast
- minecraft:pet_armadillo
- minecraft:pet_axolotl
- minecraft:pet_bee
- minecraft:pet_cat
- minecraft:pet_chicken
- minecraft:pet_cow
- minecraft:pet_creeper
- minecraft:pet_fox
- minecraft:pet_frog
- minecraft:pet_mooshroom
- minecraft:pet_polar_bear
- minecraft:pet_slime
- minecraft:pet_turtle
- minecraft:pet_wolf
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:black_harness
+ minecraft:blue_harness
+ minecraft:brown_harness
+ minecraft:cyan_harness
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal_frame
+ minecraft:ender_eye
- minecraft:exit_eye
- minecraft:fire_wand
- minecraft:grave_advancement
+ minecraft:gray_harness
+ minecraft:green_harness
+ minecraft:happy_ghast_spawn_egg
+ minecraft:light_blue_harness
+ minecraft:light_gray_harness
+ minecraft:lime_harness
+ minecraft:magenta_harness
- minecraft:mine
- minecraft:mine_crafter
- minecraft:mine_ingredient
- minecraft:mine_revisitor
- minecraft:mob_trophy
- minecraft:music_disc_and_action
+ minecraft:orange_harness
+ minecraft:pink_harness
+ minecraft:purple_harness
+ minecraft:red_harness
- minecraft:shazboots
- minecraft:shimmering_door
- minecraft:shimmering_key
- minecraft:sky
- minecraft:sky_box
- minecraft:teleportation_wand
- minecraft:trophy
+ minecraft:white_harness
- minecraft:wind_wand
+ minecraft:yellow_harness
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
- minecraft:acting_stage
```

</details>
<details>
<summary>
menu
</summary>

```diff
- minecraft:dimension_control
- minecraft:map_making
```

</details>
<details>
<summary>
mob_effect
</summary>

```diff
- minecraft:shazboots
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
- minecraft:mine_travel
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:happy_ghast_temptations
+ minecraft:nearest_adult_any_type
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.dried_ghast.ambient
+ minecraft:block.dried_ghast.ambient_water
+ minecraft:block.dried_ghast.break
+ minecraft:block.dried_ghast.fall
+ minecraft:block.dried_ghast.hit
+ minecraft:block.dried_ghast.place
+ minecraft:block.dried_ghast.place_in_water
+ minecraft:block.dried_ghast.step
+ minecraft:block.dried_ghast.transition
+ minecraft:block.dry_grass.ambient
- minecraft:block.sand.wind
+ minecraft:entity.ghastling.ambient
+ minecraft:entity.ghastling.death
+ minecraft:entity.ghastling.hurt
+ minecraft:entity.ghastling.spawn
+ minecraft:entity.happy_ghast.ambient
+ minecraft:entity.happy_ghast.death
+ minecraft:entity.happy_ghast.equip
+ minecraft:entity.happy_ghast.harness_goggles_down
+ minecraft:entity.happy_ghast.harness_goggles_up
+ minecraft:entity.happy_ghast.hurt
+ minecraft:entity.happy_ghast.riding
+ minecraft:entity.happy_ghast.unequip
- nothingtoseehere:and_action
- nothingtoseehere:crowd_cheer
- nothingtoseehere:crowd_start
- nothingtoseehere:crowd_waiting
- nothingtoseehere:ui.player_unlock_fail
- nothingtoseehere:ui.player_unlock_success
```

</details>
<details>
<summary>
trigger_type
</summary>

```diff
- minecraft:consume_poisonous_potatoes
- minecraft:inventory_cashed_in
- minecraft:level_completed
- minecraft:level_failed
- minecraft:mine_crafter_upgraded
- minecraft:mine_revisitor_activated
- minecraft:player_unlock_bought
- minecraft:player_unlock_unlocked
- minecraft:special_mine_completed
+ minecraft:used_ender_eye
- minecraft:used_exit_eye
```

</details>
<details>
<summary>
villager_profession
</summary>

```diff
- minecraft:traitor
```

</details>
<details>
<summary>
worldgen/chunk_generator
</summary>

```diff
- minecraft:hub
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:place_template
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
- universal_tags/mine_event_type.json
- universal_tags/player_unlock.json
- universal_tags/special_mine.json
- universal_tags/world_effect_set.json
- universal_tags/world_effect.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:end_portal
+ minecraft:end_portal_frame
- minecraft:mine_travelling_block
- minecraft:shimmering_door
- minecraft:sky
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:dimension_control
+ minecraft:dried_ghast
- minecraft:mine_crafter
- minecraft:mine_revisitor
- minecraft:mob_trophy
- minecraft:trophy
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
- minecraft:angry_ghast
- minecraft:cat
+ minecraft:happy_ghast
- minecraft:pet_armadillo
- minecraft:pet_axolotl
- minecraft:pet_bee
- minecraft:pet_chicken
- minecraft:pet_cow
- minecraft:pet_creeper
- minecraft:pet_fox
- minecraft:pet_frog
- minecraft:pet_mooshroom
- minecraft:pet_slime
- minecraft:pet_turtle
- minecraft:pet_wolf
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:cat
- minecraft:pet_cat
- minecraft:pet_polar_bear
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
- minecraft:angry_ghast
- minecraft:cat
+ minecraft:happy_ghast
- minecraft:pet_armadillo
- minecraft:pet_axolotl
- minecraft:pet_bee
- minecraft:pet_chicken
- minecraft:pet_cow
- minecraft:pet_creeper
- minecraft:pet_fox
- minecraft:pet_frog
- minecraft:pet_mooshroom
- minecraft:pet_slime
- minecraft:pet_turtle
- minecraft:pet_wolf
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
- minecraft:acting
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:camera_distance
- minecraft:experience_gain_modifier
- minecraft:max_jumps
- minecraft:pickup_area_size
+ minecraft:waypoint_receive_range
+ minecraft:waypoint_transmit_range
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal
+ minecraft:end_portal_frame
- minecraft:mine_crafter
- minecraft:mine_revisitor
- minecraft:mine_travelling_block
- minecraft:mob_trophy
- minecraft:shimmering_door
- minecraft:sky
- minecraft:trophy
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:end_portal
- minecraft:mine_crafter
- minecraft:mine_travelling_block
- minecraft:mob_trophy
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal
+ minecraft:end_portal_frame
- minecraft:mine_crafter
- minecraft:mine_revisitor_block
- minecraft:mine_travelling_block
- minecraft:mob_trophy
- minecraft:shimmering_door
- minecraft:terracotta
- minecraft:trophy
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:hex_color
```

</details>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
+ minecraft:happy_ghast_one_cm
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
- minecraft:dimension_id
- minecraft:exchange_value
- minecraft:instant_room
- minecraft:mine_active
- minecraft:mine_completed
- minecraft:mob_trophy/type
- minecraft:sky
- minecraft:special_mine
- minecraft:trophy/type
- minecraft:world_effect_uhint
- minecraft:world_effect_unlock
- minecraft:world_modifiers
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:angry_ghast
+ minecraft:happy_ghast
- minecraft:pet_armadillo
- minecraft:pet_axolotl
- minecraft:pet_bee
- minecraft:pet_cat
- minecraft:pet_chicken
- minecraft:pet_cow
- minecraft:pet_creeper
- minecraft:pet_fox
- minecraft:pet_frog
- minecraft:pet_mooshroom
- minecraft:pet_polar_bear
- minecraft:pet_slime
- minecraft:pet_turtle
- minecraft:pet_wolf
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:black_harness
+ minecraft:blue_harness
+ minecraft:brown_harness
+ minecraft:cyan_harness
- minecraft:dimension_control
+ minecraft:dried_ghast
+ minecraft:end_portal_frame
+ minecraft:ender_eye
- minecraft:exit_eye
- minecraft:fire_wand
- minecraft:grave_advancement
+ minecraft:gray_harness
+ minecraft:green_harness
+ minecraft:happy_ghast_spawn_egg
+ minecraft:light_blue_harness
+ minecraft:light_gray_harness
+ minecraft:lime_harness
+ minecraft:magenta_harness
- minecraft:mine
- minecraft:mine_crafter
- minecraft:mine_ingredient
- minecraft:mine_revisitor
- minecraft:mob_trophy
- minecraft:music_disc_and_action
+ minecraft:orange_harness
+ minecraft:pink_harness
+ minecraft:purple_harness
+ minecraft:red_harness
- minecraft:shazboots
- minecraft:shimmering_door
- minecraft:shimmering_key
- minecraft:sky
- minecraft:sky_box
- minecraft:teleportation_wand
- minecraft:trophy
+ minecraft:white_harness
- minecraft:wind_wand
+ minecraft:yellow_harness
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
- minecraft:acting_stage
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
- minecraft:dimension_control
- minecraft:map_making
```

</details>
<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
- minecraft:shazboots
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
- minecraft:mine_travel
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:happy_ghast_temptations
+ minecraft:nearest_adult_any_type
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.dried_ghast.ambient
+ minecraft:block.dried_ghast.ambient_water
+ minecraft:block.dried_ghast.break
+ minecraft:block.dried_ghast.fall
+ minecraft:block.dried_ghast.hit
+ minecraft:block.dried_ghast.place
+ minecraft:block.dried_ghast.place_in_water
+ minecraft:block.dried_ghast.step
+ minecraft:block.dried_ghast.transition
+ minecraft:block.dry_grass.ambient
- minecraft:block.sand.wind
+ minecraft:entity.ghastling.ambient
+ minecraft:entity.ghastling.death
+ minecraft:entity.ghastling.hurt
+ minecraft:entity.ghastling.spawn
+ minecraft:entity.happy_ghast.ambient
+ minecraft:entity.happy_ghast.death
+ minecraft:entity.happy_ghast.equip
+ minecraft:entity.happy_ghast.harness_goggles_down
+ minecraft:entity.happy_ghast.harness_goggles_up
+ minecraft:entity.happy_ghast.hurt
+ minecraft:entity.happy_ghast.riding
+ minecraft:entity.happy_ghast.unequip
- nothingtoseehere:and_action
- nothingtoseehere:crowd_cheer
- nothingtoseehere:crowd_start
- nothingtoseehere:crowd_waiting
- nothingtoseehere:ui.player_unlock_fail
- nothingtoseehere:ui.player_unlock_success
```

</details>
<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
- minecraft:consume_poisonous_potatoes
- minecraft:inventory_cashed_in
- minecraft:level_completed
- minecraft:level_failed
- minecraft:mine_crafter_upgraded
- minecraft:mine_revisitor_activated
- minecraft:player_unlock_bought
- minecraft:player_unlock_unlocked
- minecraft:special_mine_completed
+ minecraft:used_ender_eye
- minecraft:used_exit_eye
```

</details>
<details>
<summary>
universal_tags/villager_profession.json
</summary>

```diff
- minecraft:traitor
```

</details>
<details>
<summary>
universal_tags/worldgen/chunk_generator.json
</summary>

```diff
- minecraft:hub
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:place_template
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
+ black_harness.json
+ blue_harness.json
+ brown_harness.json
+ cyan_harness.json
- dimension_control.json
+ dried_ghast.json
+ end_portal_frame.json
+ ender_eye.json
- exit_eye.json
- fire_wand.json
- grave_advancement.json
+ gray_harness.json
+ green_harness.json
+ happy_ghast_spawn_egg.json
+ light_blue_harness.json
+ light_gray_harness.json
+ lime_harness.json
+ magenta_harness.json
- mine_crafter.json
- mine_ingredient.json
- mine_revisitor.json
- mine.json
- mob_trophy.json
- music_disc_and_action.json
+ orange_harness.json
+ pink_harness.json
+ purple_harness.json
+ red_harness.json
- shazboots.json
- shimmering_door.json
- shimmering_key.json
- sky_box.json
- sky.json
- teleportation_wand.json
- trophy.json
+ white_harness.json
- wind_wand.json
+ yellow_harness.json
```

</details>
<details>
<summary>
acacia_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allay_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
angler_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
archer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armor_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arms_up_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
baked_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:consumable</td><td><pre>{}</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 2,
  "saturation": 0.4
}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_chest_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_soup
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.13</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blade_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.7</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.90000004</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bogged_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bolt_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.022222223</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_meal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bordure_indented_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bowl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bread
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
burn_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.89</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
camel_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.7</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 4,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 4,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
charcoal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.07</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.18</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
closed_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.45000002</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coast_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa_beans
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cookie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cow_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.003</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_heart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crossbow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.90000004</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
danger_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.71999997</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.99</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
debug_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>4</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>8</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 8,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": 0,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 11,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 11,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>7</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>3</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
disc_fragment_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.11111111</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.19</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dolphin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
donkey_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_breath
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>100</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.26999998</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.16</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
drowned_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dune_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
echo_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elder_guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elytra
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>4.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>4.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enderman_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
endermite_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>4.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_dragon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_pearl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.6</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_crystal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.7</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
evoker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
experience_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
explorer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.90000004</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
eye_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
feather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fermented_spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
field_masoned_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
filled_map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firefly_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_rocket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fishing_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint_and_steel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fox_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
friend_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frog_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.16</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_tear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glistering_melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
globe_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone_dust
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_horn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.16</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.32</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.19999999</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 7,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 7,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.28</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.0044444446</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gunpowder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heartbreak_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_of_the_sea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_core
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.19</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
host_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
howl_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
husk_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.0999999046325684,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.0999999046325684,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.24</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.14999999</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -1,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.21</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.0033333332</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
knowledge_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.014</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>3.6000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_lazuli
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lead
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leaf_litter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.049999997</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.07</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lingering_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:potion_duration_scale</td><td><pre>0.3</pre></td><td><pre>0.25</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>10</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cream
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cube_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.0022222223</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
milk_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
miner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mojang_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mooshroom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mourner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mule_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_11
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_13
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_blocks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_cat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_chirp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator_music_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_far
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mellohi
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_otherside
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_pigstep
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_precipice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_relic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_stal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_strad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_wait
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_ward
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
name_tag
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nautilus_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 9,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 9,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>18</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>6</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.boots",
    "operation": "add_value",
    "slot": "feet"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>12</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 8,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.chestplate",
    "operation": "add_value",
    "slot": "chest"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>7.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": 0,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>10.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  },
  {
    "type": "minecraft:knockback_resistance",
    "amount": 0.10000000149011612,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.leggings",
    "operation": "add_value",
    "slot": "legs"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>4.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_scrap
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 5.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>3</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 7,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 7,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_upgrade_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>10</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ocelot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
open_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.90000004</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
painting
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_hanging_moss
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
panda_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
paper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
parrot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_membrane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_brute_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pig_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pillager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_pod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
plenty_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poisonous_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "can_always_eat": true,
  "nutrition": 2,
  "saturation": 1.2
}</pre></td><td><pre>{
  "nutrition": 2,
  "saturation": 1.2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polar_bear_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
popped_chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.07</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.71999997</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_crystals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prize_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_pie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.55</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.4</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_foot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_hide
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raiser_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ravager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
recovery_compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.26999998</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.38</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.32</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_clump
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rib_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rotten_flesh
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
saddle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scrape_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sentry_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shaper_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheaf_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shears
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.07</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheep_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelter_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shield
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.07</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silence_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silverfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.18</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.8</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snort_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snout_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snowball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.2</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spectral_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spire_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
splash_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.025</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spyglass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.002</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.200000047683716,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.200000047683716,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.06</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 2,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 2.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 2.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 4,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stray_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
strider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
string
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_instance_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tide_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tipped_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.3</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.23</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
totem_of_undying
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trader_llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.16</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.9000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 8,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.9000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 2,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.helmet",
    "operation": "add_value",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vindicator_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wandering_trader_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warden_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ward_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.089999996</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.12</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.17999999</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.90000004</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1.8000001</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.04</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.005</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wildflowers
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wild_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.9</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wind_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.5</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
witch_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 11,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:armor",
    "amount": 11,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  },
  {
    "type": "minecraft:armor_toughness",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:armor.body",
    "operation": "add_value",
    "slot": "body"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.200000047683716,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 6,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3.200000047683716,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 0,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.015</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.799999952316284,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1.5,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 1.5,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.01</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td><td><pre>[
  {
    "type": "minecraft:attack_damage",
    "amount": 3,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_damage",
    "operation": "add_value",
    "slot": "mainhand"
  },
  {
    "type": "minecraft:attack_speed",
    "amount": -2.4000000953674316,
    "display": {
      "type": "default"
    },
    "id": "minecraft:base_attack_speed",
    "operation": "add_value",
    "slot": "mainhand"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
writable_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
written_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.122</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.08</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.03</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.1</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.05</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0.02</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>2</pre></td><td><pre>/</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
  {
    "type": "minecraft:waypoint_transmit_range",
    "amount": -1,
    "display": {
      "type": "hidden"
    },
    "id": "minecraft:waypoint_transmit_range_hide",
    "operation": "add_multiplied_total",
    "slot": "head"
  }
]</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombified_piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>minecraft:exchange_value</td><td><pre>0</pre></td><td><pre>/</pre></td></tr></table>
<br/>
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
- minecraft:composite
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
- dimension_control.json
+ dried_ghast.json
+ end_portal_frame.json
+ end_portal.json
- mine_crafter.json
- mine_revisitor.json
- mine_travelling_block.json
- mob_trophy.json
- shimmering_door.json
- sky.json
- trophy.json
```

</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">25w14craftmine</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ version.txt
+ waypoint.txt
```

</details>
<details>
<summary>
datapack
</summary>

```diff
+ datapack create <id: string> <description: component>
```

</details>
<details>
<summary>
gamerule
</summary>

```diff
+ gamerule useLocatorBar <value: bool>
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
+ black_harness.json
+ blue_harness.json
+ brown_harness.json
+ cyan_harness.json
+ dried_ghast.json
+ dye_black_harness.json
+ dye_blue_harness.json
+ dye_brown_harness.json
+ dye_cyan_harness.json
+ dye_gray_harness.json
+ dye_green_harness.json
+ dye_light_blue_harness.json
+ dye_light_gray_harness.json
+ dye_lime_harness.json
+ dye_magenta_harness.json
+ dye_orange_harness.json
+ dye_pink_harness.json
+ dye_purple_harness.json
+ dye_red_harness.json
+ dye_white_harness.json
+ dye_yellow_harness.json
+ ender_eye.json
- exit_eye.json
+ gray_harness.json
+ green_harness.json
+ light_blue_harness.json
+ light_gray_harness.json
+ lime_harness.json
+ magenta_harness.json
+ orange_harness.json
+ pink_harness.json
+ purple_harness.json
+ red_harness.json
+ white_harness.json
+ yellow_harness.json
```

</details>
<details>
<summary>
dispenser.json
</summary>

```
A: #stone_tool_materials
B: bow
C: cobblestone
D: redstone

Previous pattern:
[A | A | A]
[A | B | A]
[A | D | A]

New pattern:
[C | C | C]
[C | B | C]
[C | D | C]
```

</details>
<details>
<summary>
dropper.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: redstone

Previous pattern:
[A | A | A]
[A |   | A]
[A | C | A]

New pattern:
[B | B | B]
[B |   | B]
[B | C | B]
```

</details>
<details>
<summary>
ender_chest.json
</summary>

```
A: ender_eye
B: exit_eye
C: obsidian

Previous pattern:
[C | C | C]
[C | B | C]
[C | C | C]

New pattern:
[C | C | C]
[C | A | C]
[C | C | C]
```

</details>
<details>
<summary>
end_crystal.json
</summary>

```
A: ender_eye
B: exit_eye
C: ghast_tear
D: glass

Previous pattern:
[D | D | D]
[D | B | D]
[D | C | D]

New pattern:
[D | D | D]
[D | A | D]
[D | C | D]
```

</details>
<details>
<summary>
lever.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: stick

Previous pattern:
[C]
[A]

New pattern:
[C]
[B]
```

</details>
<details>
<summary>
observer.json
</summary>

```
A: #stone_tool_materials
B: cobblestone
C: quartz
D: redstone

Previous pattern:
[A | A | A]
[D | D | C]
[A | A | A]

New pattern:
[B | B | B]
[D | D | C]
[B | B | B]
```

</details>
<details>
<summary>
piston.json
</summary>

```
A: #planks
B: #stone_tool_materials
C: cobblestone
D: iron_ingot
E: redstone

Previous pattern:
[A | A | A]
[B | D | B]
[B | E | B]

New pattern:
[A | A | A]
[C | D | C]
[C | E | C]
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
- minecraft:mine_event_type
- minecraft:player_unlock
- minecraft:special_mine
- minecraft:world_effect
- minecraft:world_effect_set
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
- advancements.adventure.deluge.description: Complete a Mine while the Water World and Eternal Rain effects are active
- advancements.adventure.deluge.title: Shall we wait for the drizzle to subside?
- advancements.adventure.enter_a_mine.description: Enter a Mine
- advancements.adventure.enter_a_mine.title: Down the Hatch
+ advancements.adventure.heart_transplanter.description: Place a Creaking Heart with the correct alignment between two Pale Oak Log blocks
+ advancements.adventure.heart_transplanter.title: Heart Transplanter
- advancements.adventure.level_failed.description: Fail a Mine
- advancements.adventure.level_failed.title: Oops
- advancements.adventure.level.description: Complete your first Mine
- advancements.adventure.level.title: It Begins
- advancements.adventure.mine_crafter_upgraded.description: Upgrade the Mine Crafter so you can keep mining and crafting
- advancements.adventure.mine_crafter_upgraded.title: Further beyond
- advancements.adventure.mine_revisitor_activated.description: Activate a Mine Revisitor
- advancements.adventure.mine_revisitor_activated.title: Nostalgic
- advancements.adventure.special_mine_completed.description: Complete a Special Encounter Mine
- advancements.adventure.special_mine_completed.title: A Challenger Approaches
- advancements.adventure.water_cave.description: Complete a Mine with Water World and Cave World active
- advancements.adventure.water_cave.title: The Depths
- advancements.adventure.water_world.description: Complete a Mine with Water World active
- advancements.adventure.water_world.title: Quit Smoking
- advancements.feats.angry_ghast.description: Defeat the Angry Ghast special event
- advancements.feats.angry_ghast.title: The Baloonslayer
- advancements.feats.crystal.description: Obtain a crystal to unlock the Warden Special Event
- advancements.feats.crystal.title: Crystaline
- advancements.feats.eat_your_veggies.description: Eat 100 Poisonous Potatoes
- advancements.feats.eat_your_veggies.title: Certified Spud Chomper
- advancements.feats.end_world.description: Complete a Mine with End Biomes to unlock the Ender Dragon special event
- advancements.feats.end_world.title: The Beginning of the End
- advancements.feats.ender_dragon.description: Defeat the Ender Dragon special event
- advancements.feats.ender_dragon.title: At the Rim of the Sky
- advancements.feats.enderman.description: Defeat the Enderman special event
- advancements.feats.enderman.title: Endedman
- advancements.feats.kill_pillager.description: Kill a Pillager to unlock the Raid special event
- advancements.feats.kill_pillager.title: Raid the Raiders
- advancements.feats.kill_skeleton.description: Kill a Skeleton to unlock the Spooky Scary Skeletons special event
- advancements.feats.kill_skeleton.title: Feel it in my Bones
- advancements.feats.kuiper_world.description: Defeat the Kuiper World special event
- advancements.feats.kuiper_world.title: Spaaaaace!
- advancements.feats.raid.description: Defeat the Raid special event
- advancements.feats.raid.title: The Pillagers are Coming!
- advancements.feats.root.description: Feats of Prowess
- advancements.feats.root.title: Feats
- advancements.feats.shimmering_key.description: Acquire a Shimmering Key
- advancements.feats.shimmering_key.title: Master Key
- advancements.feats.small_but_deadly.description: Defeat the Small but Deadly special event
- advancements.feats.small_but_deadly.title: Small But Dead
- advancements.feats.spooky_scary_skeletons.description: Defeat the Spooky Scary Skeletons special event
- advancements.feats.spooky_scary_skeletons.title: Clattered
- advancements.feats.warden.description: Defeat the Warden special event
- advancements.feats.warden.title: Warded
- advancements.feats.wither_skeleton_skull.description: Acquire a Wither Skeleton Skull to unlock the Wither special event
- advancements.feats.wither_skeleton_skull.title: Withering
- advancements.feats.wither.description: Defeat the Wither special event
- advancements.feats.wither.title: Withered
+ advancements.husbandry.place_dried_ghast_in_water.description: Place a Dried Ghast block into water
+ advancements.husbandry.place_dried_ghast_in_water.title: Stay Hydrated!
- advancements.mine.cash_in.description: Bring a Mine Ingredient to the exit of a Mine to cash it in
- advancements.mine.cash_in.title: Cash In!
- advancements.mine.get_mine_ingredient.description: Pick up a Mine Ingredient in a Mine
- advancements.mine.get_mine_ingredient.title: New Frontiers
- advancements.mines.all_mine_ingredients.description: Complete at least one Mine with each possible Mine Ingredient
- advancements.mines.all_mine_ingredients.title: The Ultimate Miner
- advancements.mines.all_special_mines_completed.description: Complete all Special Encounter Mines
- advancements.mines.all_special_mines_completed.title: Yes, Boss
+ advancements.story.follow_ender_eye.description: Follow an Eye of Ender
+ advancements.story.follow_ender_eye.title: Eye Spy
- advancements.story.follow_exit_eye.description: Craft an Eye of Exit
- advancements.story.follow_exit_eye.title: Spy Eye
- advancements.unlocks.all_combatant.description: Complete the 'Combat' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_combatant.title: The Combat Upd... Unlocks
- advancements.unlocks.all_crafting.description: Complete the 'Crafting' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_crafting.title: The Crafter
- advancements.unlocks.all_exploration.description: Complete the 'Exploration' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_exploration.title: Adventuring Time
- advancements.unlocks.all_gatherer.description: Complete the 'Gatherer' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_gatherer.title: The Miner
- advancements.unlocks.all_pets.description: Complete the 'Pets' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_pets.title: Crazy Cat Kai
- advancements.unlocks.all_school_of_hard_knocks.description: Complete the 'School of Hard Knocks' Player Unlock tree and then beat a special event Mine
- advancements.unlocks.all_school_of_hard_knocks.title: An Exercise in Futility
- advancements.unlocks.free_sticks.description: Is this really spellt like that? Beat a level while having all three wands unlocked
- advancements.unlocks.free_sticks.title: Free Sticks
- advancements.unlocks.in_it_together.description: Beat a special Mine with the 'Soul Link' effect active
- advancements.unlocks.in_it_together.title: In It Together
- advancements.unlocks.jump_king.description: Obtain the maximum amount of jumps
- advancements.unlocks.jump_king.title: Jump King
- advancements.unlocks.player_unlock_bought.description: Buy a player unlock and get better at being you
- advancements.unlocks.player_unlock_bought.title: Kaizen
- advancements.unlocks.player_unlock_unlocked.description: Unlock a player unlock so you can unlock more unlocks
- advancements.unlocks.player_unlock_unlocked.title: How do I unlock that?
- advancements.unlocks.root.description: Ah, the noble pursuit of self-improvement
- advancements.unlocks.root.title: Unlocks
- advancements.unlocks.sigma_grindset.description: Complete the 'Knowledge' Player Unlock tree
- advancements.unlocks.sigma_grindset.title: Sigma Grindset
+ argument.hexcolor.invalid: Invalid hex color code '%s'
+ argument.waypoint.invalid: Selected entity is not a waypoint
+ attribute.name.camera_distance: Camera Distance
- attribute.name.experience_gain_modifier: Experience Gain Modifier
- attribute.name.max_jumps: Max Jumps
- attribute.name.pickup_area_size: Pickup Area Size
+ attribute.name.waypoint_receive_range: Waypoint Receive Range
+ attribute.name.waypoint_transmit_range: Waypoint Transmit Range
- block.minecraft.bed.no_sleep_for_you: No sleep for you, not today!
- block.minecraft.dimension_control: Dimension Control
+ block.minecraft.dried_ghast: Dried Ghast
- block.minecraft.enter_mine_gateway: Enter Mine Gateway
- block.minecraft.mine_crafter: Mine Crafter
- block.minecraft.mine_revisitor: Mine Revisitor
- block.minecraft.mine_travelling_block: Mine Travelling Block
- block.minecraft.mob_trophy: Trophy
- block.minecraft.shimmering_door: Shimmering Door
- block.minecraft.sky: Sky
- block.minecraft.trophy: Trophy
+ commands.datapack.create.already_exists: Pack with name '%s' already exists
+ commands.datapack.create.invalid_name: Invalid characters in new pack name '%s'
+ commands.datapack.create.io_failure: Can't create pack with name '%s', check logs
+ commands.datapack.create.metadata_encode_failure: Failed to encode metadata for pack with name '%s': %s
+ commands.datapack.create.success: Created new empty pack with name '%s'
- commands.level.success: Created level %s
+ commands.version.build_time: build_time = %s
+ commands.version.data: data = %s
+ commands.version.header: Server version info:
+ commands.version.id: id = %s
+ commands.version.name: name = %s
+ commands.version.pack.data: pack_data = %s
+ commands.version.pack.resource: pack_resource = %s
+ commands.version.protocol: protocol = %s (%s)
+ commands.version.series: series = %s
+ commands.version.stable.no: stable = no
+ commands.version.stable.yes: stable = yes
+ commands.waypoint.list.empty: No waypoints in %s
+ commands.waypoint.list.success: %s waypoint(s) in %s: %s
+ commands.waypoint.modify.color: Waypoint color is now %s
+ commands.waypoint.modify.color.reset: Reset waypoint color
+ commands.waypoint.modify.fade: Waypoint fade changed
- container.dimension_control: Dimension Control
- container.mine_crafter: Craft your Mine
- container.mine_crafter.active: Go go go!
- container.mine_crafter.donate: DONATE
Use %s of your experience to work towards upgrading the Minecrafter Table
- container.mine_crafter.drawer: Mine Effects
- container.mine_crafter.fail: Better Luck Next Time
- container.mine_crafter.hints: Undiscovered
- container.mine_crafter.level: Level: %s  %s / %s
- container.mine_crafter.no_hints: You did it!!!
- container.mine_crafter.won: Mine Successful!
+ dataPack.locator_bar.description: Show the direction of other players in multiplayer
+ dataPack.locator_bar.name: Locator Bar
- death.attack.devour: %1$s was devoured
- death.attack.devour.item: %1$s was devoured by %2$s using %3$s
- death.attack.devour.player: %1$s was devoured by %2$s
- deathScreen.respawn.hardcore: Accept Defeat
- deathScreen.respawn.inMap: Accept Defeat
+ debug.version.header: Client version info:
+ debug.version.help: F3 + V = Client version info
- door.say_the_thing: Doors yearn for the keys!
- effect.minecraft.shazboots: Shazboots!
- entity.minecraft.angry_ghast: Angry Ghast
+ entity.minecraft.happy_ghast: Happy Ghast
- entity.minecraft.pet_armadillo: Pet Armadillo
- entity.minecraft.pet_axolotl: Pet Axolotl
- entity.minecraft.pet_bee: Pet Bee
- entity.minecraft.pet_cat: Pet Cat
- entity.minecraft.pet_chicken: Pet Chicken
- entity.minecraft.pet_cow: Pet Cow
- entity.minecraft.pet_creeper: Pet Creeper
- entity.minecraft.pet_fox: Pet Fox
- entity.minecraft.pet_frog: Pet Frog
- entity.minecraft.pet_mooshroom: Pet Mooshroom
- entity.minecraft.pet_polar_bear: Pet Polar Bear
- entity.minecraft.pet_slime: Pet Slime
- entity.minecraft.pet_turtle: Pet Turtle
- entity.minecraft.pet_wolf: Pet Wolf
- entity.minecraft.villager.traitor: Traitor
- gamerule.allBlocksBouncy: All blocks are bouncy
- gamerule.icyLevel: All blocks are bouncy
+ gamerule.useLocatorBar: Use player Locator Bar
+ gamerule.useLocatorBar.description: When enabled, a bar is shown on the screen to indicate the direction of players.
- gui.door: Door
- gui.door.field.active_door: The Door You Just Clicked
- gui.door.field.error: Something Wrong
- gui.door.field.existing_door: Existing door
- gui.door.field.existing_wall: Existing wall
- gui.door.field.new_door: Door
- gui.door.field.new_room: Room
- gui.door.field.new_wall: Wall
- gui.door.next: Next
- gui.door.open: Open
- gui.door.previous: Previous
+ gui.experience.level: %s
- gui.unlocks: Player Unlocks
- item.exchange_value: Value: %s
+ item.minecraft.black_harness: Black Harness
+ item.minecraft.blue_harness: Blue Harness
+ item.minecraft.brown_harness: Brown Harness
+ item.minecraft.cyan_harness: Cyan Harness
+ item.minecraft.ender_eye: Eye of Ender
- item.minecraft.exit_eye: Eye of Exit
- item.minecraft.fire_wand: Fire Wand
- item.minecraft.fire_wand.lore: 'Tiwaz Raido'
- item.minecraft.grave_advancement: Grave
+ item.minecraft.gray_harness: Gray Harness
+ item.minecraft.green_harness: Green Harness
+ item.minecraft.happy_ghast_spawn_egg: Happy Ghast Spawn Egg
+ item.minecraft.harness: Harness
- item.minecraft.level_ingredient: Level Ingredient
- item.minecraft.level: Level
+ item.minecraft.light_blue_harness: Light Blue Harness
+ item.minecraft.light_gray_harness: Light Gray Harness
+ item.minecraft.lime_harness: Lime Harness
+ item.minecraft.magenta_harness: Magenta Harness
- item.minecraft.mine_ingredient: Mine Ingredient
- item.minecraft.mine_ingredient.desc: Mine Ingredient: %s
- item.minecraft.mine: Mine
- item.minecraft.mob_trophy.entity: Contents: 1 × Minecraft %s
- item.minecraft.mob_trophy.grade: Grade: %s
- item.minecraft.mob_trophy.grade.diamond: Diamond
- item.minecraft.mob_trophy.grade.gold: Gold
- item.minecraft.mob_trophy.grade.grass: Grass
- item.minecraft.mob_trophy.grade.netherite: Netherite
- item.minecraft.mob_trophy.grade.stone: Stone
- item.minecraft.mob_trophy.shiny: Oooh, shiny!
- item.minecraft.music_disc_and_action: Music Disc
- item.minecraft.music_disc_and_action.desc: Tone Deaf Rebellion - And Action!
+ item.minecraft.orange_harness: Orange Harness
+ item.minecraft.pink_harness: Pink Harness
+ item.minecraft.purple_harness: Purple Harness
+ item.minecraft.red_harness: Red Harness
- item.minecraft.shazboots: Shazboots!
- item.minecraft.shimmering_key: Shimmering Key
- item.minecraft.shimmering_key.room: Opens "%s"
- item.minecraft.sky_box: Sky Box
- item.minecraft.teleportation_wand: Displacement Wand
- item.minecraft.teleportation_wand.lore: 'Jera Isaz Berkanan'
+ item.minecraft.white_harness: White Harness
- item.minecraft.wind_wand: Wind Wand
- item.minecraft.wind_wand.lore: 'Kaunan Wunjo Perth Thurisaz'
+ item.minecraft.yellow_harness: Yellow Harness
- jukebox_song.minecraft.and_action: Tone Deaf Rebellion - And Action!
- key.unlocks: Unlocks
- level.gained: You've levelled up to level %s!
- level.unlock_hint: Press %s to spend levels on unlocks
- mine.angry_ghast_boss.description: This one's not happy with you
- mine.angry_ghast_boss.name: Angry Ghast
- mine.ender_dragon_boss.description: This seems to be the end
- mine.ender_dragon_boss.name: Ender Dragon
- mine.enderman_boss.description: That Enderman in particular
- mine.enderman_boss.name: The Enderman
- mine.enter: Entering Mine in: %s seconds
- mine.enter.aborted: No longer entering Mine
- mine.enter.started: Entering Mine...
- mine.kuiper_belt.description: Igloo in spaaaaace!
- mine.kuiper_belt.name: Kuiper World
- mine.leave: Leaving Mine in: %s seconds
- mine.leave.aborted: No longer leaving Mine
- mine.leave.started: Leaving Mine...
- mine.lost: MINE FAILED
- mine.raid.description: Defend the village!
- mine.raid.name: Raid
- mine.small_but_deadly_boss.description: Better have good aim
- mine.small_but_deadly_boss.name: Small but Deadly
- mine.spooky_scary_skeletons_boss.description: Shrieking skulls will shock your soul
- mine.spooky_scary_skeletons_boss.name: Spooky Scary Skeletons
- mine.warden_boss.description: Get your groove on
- mine.warden_boss.name: Warden
- mine.wither_boss.description: DANGER DANGER
- mine.wither_boss.name: Wither
- mine.won: MINE COMPLETED SUCCESSFULLY
- mine.won.rewards: %s earned %s exp
- minecraftlike.pack_name: Level %s
- multiplayer.enteringMap.0: Entering mine...
- multiplayer.enteringMap.1: Doing something very important...
- multiplayer.enteringMap.10: Absolutely placing the entire world one block at a time...
- multiplayer.enteringMap.11: All your blocks are exactly where you left them
- multiplayer.enteringMap.12: Poisoning potatoes...
- multiplayer.enteringMap.13: Voting for mobs...
- multiplayer.enteringMap.14: Infinitely creating dimensions...
- multiplayer.enteringMap.15: Travelling back to the 90's...
- multiplayer.enteringMap.16: Increasing texture details...
- multiplayer.enteringMap.17: Making a portable console...
- multiplayer.enteringMap.18: Following the trends...
- multiplayer.enteringMap.19: Adding sugar, spice and everything that is nice...
- multiplayer.enteringMap.2: Placing all of the little blocks in the world..
- multiplayer.enteringMap.20: Turning players into villagers...
- multiplayer.enteringMap.21: Making collabs...
- multiplayer.enteringMap.22: Acquiring MineCoins[tm]...
- multiplayer.enteringMap.23: Now in 4D!
- multiplayer.enteringMap.24: It’s now NOT safe to turn off your computer
- multiplayer.enteringMap.25: Reticulating splines...
- multiplayer.enteringMap.26: Filling up to the line on a cup...
- multiplayer.enteringMap.27: Smoking these blocks...
- multiplayer.enteringMap.28: Adding seven mountains and seven seas...
- multiplayer.enteringMap.29: Reheating old jokes...
- multiplayer.enteringMap.3: Hiding stuff...
- multiplayer.enteringMap.30: Letting the cat out...
- multiplayer.enteringMap.31: Letting the cat in...
- multiplayer.enteringMap.32: Making everyone confused...
- multiplayer.enteringMap.33: Not incrementing the version...
- multiplayer.enteringMap.34: Looking under the couch cushions for extra features...
- multiplayer.enteringMap.35: Checking if everything Works As Intended...
- multiplayer.enteringMap.36: Simulating epic histories of underground kingdoms...
- multiplayer.enteringMap.37: Spreading the rumors...
- multiplayer.enteringMap.38: Sprinkling just a pinch of extra blocks on the top...
- multiplayer.enteringMap.39: Turning the lights on...
- multiplayer.enteringMap.4: Making a mess...
- multiplayer.enteringMap.40: Just wasting time until I remember what to do next...
- multiplayer.enteringMap.41: Displaying this message...
- multiplayer.enteringMap.42: Forgetting about something important...
- multiplayer.enteringMap.43: Ruining the game...
- multiplayer.enteringMap.44: Walking 500 miles...
- multiplayer.enteringMap.45: Walking 500 more...
- multiplayer.enteringMap.46: Finding a Programmer to get some Art made...
- multiplayer.enteringMap.47: Breaking some farms...
- multiplayer.enteringMap.48: Spilling out lava from buckets...
- multiplayer.enteringMap.49: Changing my mind and removing some blocks again...
- multiplayer.enteringMap.5: Trying my best...
- multiplayer.enteringMap.6: Forgot something, probably not important...
- multiplayer.enteringMap.7: Turning off and back on again...
- multiplayer.enteringMap.8: Don't worry about it...
- multiplayer.enteringMap.9: Introducing jank...
- player.kick.too_long: Too slow, try connecting again
- room.minecraft.barrels: Storage (barrels)
- room.minecraft.boiler: Boiler Room
- room.minecraft.carpet: Relax Room
- room.minecraft.corridor_simple: Boring Corridor
- room.minecraft.fountain: Fountain
- room.minecraft.grassy_h: Junction (grass)
- room.minecraft.hanging: Storage (hanging barrels)
- room.minecraft.house: Wow, A Whole House? At This Price?
- room.minecraft.labyrinth: Labyrinth
- room.minecraft.pool: Deep Pool
- room.minecraft.ship: Ship
- room.minecraft.simple: Test Room Please Ignore
- room.minecraft.stairs: Stairs
- room.minecraft.storage1: Storage (simple)
- room.minecraft.storage2: Storage (less simple)
- room.minecraft.sugar_h: Junction (cane)
- room.minecraft.tree: Tree
- room.minecraft.trophy: Vintage Trophy Room
- room.minecraft.tunnel: Line
- room.minecraft.useless: Useless Room
- room.minecraft.wheat_h: Junction (wheat)
- room.minecraft.workshop: Workshop
- sky.actual_sky: True Sky
- sky.atlas: Bad Idea
- sky.classic_hub: Hub (classic)
- sky.code: Dev Mode
- sky.end: The End
- sky.missing: Missing
- sky.overworld: Overworld
- sky.panorama: Smol
- sky.tooltip: Sky: %s
+ stat.minecraft.happy_ghast_one_cm: Distance by Happy Ghast
+ subtitles.block.dried_ghast.ambient_water: Dried Ghast rehydrates
+ subtitles.block.dried_ghast.ambient: Dried Ghast wheezes
+ subtitles.block.dried_ghast.place_in_water: Dried Ghast soaks
+ subtitles.block.dried_ghast.transition: Dried Ghast feels better
+ subtitles.block.dry_grass.ambient: Windy sounds
+ subtitles.block.trapdoor.close: Trapdoor closes
+ subtitles.block.trapdoor.open: Trapdoor opens
+ subtitles.entity.ghastling.ambient: Ghastling coos
+ subtitles.entity.ghastling.death: Ghastling dies
+ subtitles.entity.ghastling.hurt: Ghastling hurts
+ subtitles.entity.ghastling.spawn: Ghastling appears
+ subtitles.entity.happy_ghast.ambient: Happy Ghast croons
+ subtitles.entity.happy_ghast.death: Happy Ghast dies
+ subtitles.entity.happy_ghast.equip: Harness equips
+ subtitles.entity.happy_ghast.harness_goggles_down: Happy Ghast is ready
+ subtitles.entity.happy_ghast.harness_goggles_up: Happy Ghast stops
+ subtitles.entity.happy_ghast.hurt: Happy Ghast hurts
+ subtitles.entity.happy_ghast.unequip: Harness unequips
- subtitles.entity.villager.work_traitor: Traitor works
- trophy.gold: Golden Cup
- trophy.mega_spud: Mega Spud
- trophy.no_medal: "Close But No" Medal
- unlocks.player.unlocked: 🔓 %s unlocked %s
- unlocks.screen.active: Active | Unlocked
- unlocks.screen.hint: Hint: %s
- unlocks.screen.inactive: Inactive | Unlocked
- unlocks.screen.locked: Cost: %s
- unlocks.screen.points: Levels: %s
- unlocks.screen.unlocked: Unlocked
- unlocks.unlock.alchemy.description: A brewing stand for all your brewing needs
- unlocks.unlock.alchemy.name: Alchemy
- unlocks.unlock.allez_cuisine.description: Add a little flair to your brewing
- unlocks.unlock.allez_cuisine.name: Allez Cuisine!
- unlocks.unlock.amphibian.description: Fast as the fish!
- unlocks.unlock.amphibian.name: Amphibian
- unlocks.unlock.apprentice_shoveler.description: Working your way up in the shoveling business
- unlocks.unlock.apprentice_shoveler.name: Apprentice Shoveler
- unlocks.unlock.archer.description: We would've called this unlock sagittarii but someone said it sounded weird and that no one speaks Latin anymore
- unlocks.unlock.archer.name: Archer
- unlocks.unlock.armaments.description: Sticks and stones may break your bones, but they probably shouldn't
- unlocks.unlock.armaments.name: Armaments
- unlocks.unlock.arrowverse.description: Shoot to your heart's content. Don't forget your bow!
- unlocks.unlock.arrowverse.name: Arrowverse
- unlocks.unlock.berserker.description: What's better than one Diamond Axe?
- unlocks.unlock.berserker.name: Berserker
- unlocks.unlock.best_starter_sword.description: Definitely worth the investment!
- unlocks.unlock.best_starter_sword.name: No Nether Needed
- unlocks.unlock.better_starter_sword.description: I can't believe they're just handing these out!
- unlocks.unlock.better_starter_sword.name: Shiny Sword
- unlocks.unlock.bundle_of_fortune.description: Here's a bundle of random stuff, don't question it
- unlocks.unlock.bundle_of_fortune.name: Bundle of Fortune
- unlocks.unlock.campfire.description: You get a Campfire to start with
- unlocks.unlock.campfire.name: Starter Campfire
- unlocks.unlock.chopper.description: Works for trees and limbs
- unlocks.unlock.chopper.name: Chopper
- unlocks.unlock.combatant.description: Gain an advantage in battle
- unlocks.unlock.combatant.name: Combat
- unlocks.unlock.crafting_efficiency.description: Are you sure you need all of these materials?
- unlocks.unlock.crafting_efficiency.hint: You can never have too many crafting tables
- unlocks.unlock.crafting_efficiency.name: Artisan Crafting
- unlocks.unlock.crafting.description: Imagine taking two things and combining them into one!
- unlocks.unlock.crafting.name: Crafting
- unlocks.unlock.crusher.description: Made from the heaviest matter in the universe
- unlocks.unlock.crusher.name: The Natural Evolution of a Shield
- unlocks.unlock.decked_out.description: Made from the finest leather
- unlocks.unlock.decked_out.name: Decked out
- unlocks.unlock.dirt_connoisseur.description: I wonder if it tastes like butter as well?
- unlocks.unlock.dirt_connoisseur.name: Dirt Connoisseur
- unlocks.unlock.dirt_destroyer_1.description: Carve through dirt like butter!
- unlocks.unlock.dirt_destroyer_1.name: Dirt is Butter
- unlocks.unlock.dirt_destroyer_2.description: I crave more!
- unlocks.unlock.dirt_destroyer_2.name: Mmmmm Dirt Butter
- unlocks.unlock.dirt_destroyer.description: Carve through dirt like butter!
- unlocks.unlock.dirt_destroyer.name: Dirt is Butter
- unlocks.unlock.dirt_enjoyer_1.description: You appreciate the value of Dirt
- unlocks.unlock.dirt_enjoyer_1.name: Dirt Enjoyer
- unlocks.unlock.dirt_enjoyer_2.description: You enjoy Dirt more than others
- unlocks.unlock.dirt_enjoyer_2.name: Dirt Fanatic
- unlocks.unlock.dirt_enjoyer_3.description: I love Dirt, Dirt loves me back?
- unlocks.unlock.dirt_enjoyer_3.name: Dirt Lover
- unlocks.unlock.dragon_fire.description: Add a bit of draconic flair to your fireballs
- unlocks.unlock.dragon_fire.hint: Get some first hand experience with dragon fire after unlocking the spellbook
- unlocks.unlock.dragon_fire.name: Dragon Fire
- unlocks.unlock.efficient_enchanting.description: By combining the aether-flux with quantum displacement while clamping the manifold parameters required to channel the arcane infusion hex we may temporarily fold this plane of existence to subvert the requirement of equivalence of exchange
- unlocks.unlock.efficient_enchanting.name: Efficient Enchanting
- unlocks.unlock.elytra.description: A singular one
- unlocks.unlock.elytra.name: Elytron
- unlocks.unlock.enchanting.description: Heh, imagine wasting experience points on this
- unlocks.unlock.enchanting.name: Enchanting
- unlocks.unlock.ender_pearl_starter.description: Best mode of transportaion!
- unlocks.unlock.ender_pearl_starter.hint: Pooof, and it's somewhere else?
- unlocks.unlock.ender_pearl_starter.name: Let's get Pearling
- unlocks.unlock.expert_shoveler.description: No mound is safe
- unlocks.unlock.expert_shoveler.name: Expert Shoveler
- unlocks.unlock.exploration.description: Get off to a flying start!
- unlocks.unlock.exploration.name: Exploration
- unlocks.unlock.extra_firepower.description: Enhances fires near (and on) you
- unlocks.unlock.extra_firepower.name: Extra Firepower
- unlocks.unlock.fire_shield.description: Your shield now comes with complimentary fire immunity
- unlocks.unlock.fire_shield.hint: Maybe DO touch the campfire after unlocking the spellbook
- unlocks.unlock.fire_shield.name: Fire Shield
- unlocks.unlock.fire_wand.description: I'm pretty sure this is misnamed
- unlocks.unlock.fire_wand.hint: Defeat a fiery flying enemy
- unlocks.unlock.fire_wand.name: Leaf
- unlocks.unlock.fishing_rod.description: Were you catching fish with your hands?
- unlocks.unlock.fishing_rod.name: Angler
- unlocks.unlock.fishing.description: Increases your luck while fishing
- unlocks.unlock.fishing.name: The Mining of the Sea
- unlocks.unlock.fletcher.description: Wouldn't it be nice if you had somewhere to make more arrows? No? Alright, these will have to do then
- unlocks.unlock.fletcher.name: Fletcher
- unlocks.unlock.full_metal.description: A full suit of armour, no alchemy needed
- unlocks.unlock.full_metal.name: Full Metal
- unlocks.unlock.gatherer.description: Crops, berry bushes and bee hives have a chance of dropping extra loot
- unlocks.unlock.gatherer.name: Gatherer
- unlocks.unlock.golden_starter_apples.description: Bring a feast with you
- unlocks.unlock.golden_starter_apples.name: Golden Apples
- unlocks.unlock.hunter.description: Aren't these supposed to be the other way? Anyways, animals killed have a chance of dropping extra loot
- unlocks.unlock.hunter.name: Hunter
- unlocks.unlock.inventory_crafting_3x3.description: No need for a crafting table
- unlocks.unlock.inventory_crafting_3x3.hint: Have you tried crafting yet? It's pretty cool!
- unlocks.unlock.inventory_crafting_3x3.name: 3x3 Inventory Crafting
- unlocks.unlock.inventory_crafting.description: Ability to craft in the inventory!
- unlocks.unlock.inventory_crafting.name: Inventory Crafting
- unlocks.unlock.inventory_slots_1.description: Maybe you shouldn't hold all of those blocks in your hands
- unlocks.unlock.inventory_slots_1.name: Pockets
- unlocks.unlock.inventory_slots_2.description: Wouldn't it be nice if you had some more slots?
- unlocks.unlock.inventory_slots_2.name: Deeper Pockets
- unlocks.unlock.inventory_slots_3.description: Surely you wouldn't need any more slots?
- unlocks.unlock.inventory_slots_3.name: Deepest Pockets
- unlocks.unlock.journeyman_shoveler.description: It's hard work, but someone has to do it
- unlocks.unlock.journeyman_shoveler.name: Journeyman Shoveler
- unlocks.unlock.jump_king_10.description: You won't get any higher than this
- unlocks.unlock.jump_king_10.name: +1 jump
- unlocks.unlock.jump_king_2.description: What could go wrong?
- unlocks.unlock.jump_king_2.name: +1 jump
- unlocks.unlock.jump_king_3.description: A valuable trove
- unlocks.unlock.jump_king_3.name: +1 jump
- unlocks.unlock.jump_king_4.description: I have to save the princess!
- unlocks.unlock.jump_king_4.name: +1 jump
- unlocks.unlock.jump_king_5.description: Imagine falling from this
- unlocks.unlock.jump_king_5.name: +1 jump
- unlocks.unlock.jump_king_6.description: What comes up, ...
- unlocks.unlock.jump_king_6.name: +1 jump
- unlocks.unlock.jump_king_7.description: Gotta reach the top of the castle
- unlocks.unlock.jump_king_7.name: +1 jump
- unlocks.unlock.jump_king_8.description: Not scared of heights are you?
- unlocks.unlock.jump_king_8.name: +1 jump
- unlocks.unlock.jump_king_9.description: Don't look down
- unlocks.unlock.jump_king_9.name: +1 jump
- unlocks.unlock.jump_king.description: Reach new heights!
- unlocks.unlock.jump_king.name: +1 jump
- unlocks.unlock.learning_1.description: Get more experience after each Mine
- unlocks.unlock.learning_1.name: Learning
- unlocks.unlock.learning_10.description: Get more experience after each Mine
- unlocks.unlock.learning_10.name: Learning 10
- unlocks.unlock.learning_11.description: Get more experience after each Mine
- unlocks.unlock.learning_11.name: Learning 11
- unlocks.unlock.learning_12.description: Get more experience after each Mine
- unlocks.unlock.learning_12.name: Learning 12
- unlocks.unlock.learning_13.description: Get more experience after each Mine
- unlocks.unlock.learning_13.name: Learning 13
- unlocks.unlock.learning_14.description: Get more experience after each Mine
- unlocks.unlock.learning_14.name: Learning 14
- unlocks.unlock.learning_15.description: Get more experience after each Mine
- unlocks.unlock.learning_15.name: Learning 15
- unlocks.unlock.learning_16.description: Get more experience after each Mine
- unlocks.unlock.learning_16.name: Learning 16
- unlocks.unlock.learning_17.description: Get more experience after each Mine
- unlocks.unlock.learning_17.name: Learning 17
- unlocks.unlock.learning_18.description: Get more experience after each Mine
- unlocks.unlock.learning_18.name: Learning 18
- unlocks.unlock.learning_19.description: Get more experience after each Mine
- unlocks.unlock.learning_19.name: Learning 19
- unlocks.unlock.learning_2.description: Get more experience after each Mine
- unlocks.unlock.learning_2.name: Learning 2
- unlocks.unlock.learning_20.description: Get more experience after each Mine
- unlocks.unlock.learning_20.name: Learning 20
- unlocks.unlock.learning_3.description: Get more experience after each Mine
- unlocks.unlock.learning_3.name: Learning 3
- unlocks.unlock.learning_4.description: Get more experience after each Mine
- unlocks.unlock.learning_4.name: Learning 4
- unlocks.unlock.learning_5.description: Get more experience after each Mine
- unlocks.unlock.learning_5.name: Learning 5
- unlocks.unlock.learning_6.description: Get more experience after each Mine
- unlocks.unlock.learning_6.name: Learning 6
- unlocks.unlock.learning_7.description: Get more experience after each Mine
- unlocks.unlock.learning_7.name: Learning 7
- unlocks.unlock.learning_8.description: Get more experience after each Mine
- unlocks.unlock.learning_8.name: Learning 8
- unlocks.unlock.learning_9.description: Get more experience after each Mine
- unlocks.unlock.learning_9.name: Learning 9
- unlocks.unlock.lodestone_exits.description: Compasses point to the nearest exit
- unlocks.unlock.lodestone_exits.name: Lodestone Exits
- unlocks.unlock.lucky_pick.description: Ore more?
- unlocks.unlock.lucky_pick.name: Lucky pick
- unlocks.unlock.magic_master_kit.description: We grant you a seat at the council, but we do not grant you the rank of master
- unlocks.unlock.magic_master_kit.name: Master Magic Kit
- unlocks.unlock.magic_starter_kit.description: Every apprentice needs this
- unlocks.unlock.magic_starter_kit.name: Magic Kit
- unlocks.unlock.mass_production.description: Now you're cooking
- unlocks.unlock.mass_production.name: Haute cuisine
- unlocks.unlock.master_shoveler.description: A tool fit for the Dirt Master
- unlocks.unlock.master_shoveler.name: Master Shoveler
- unlocks.unlock.mega_jump.description: Where did the gravity go?!
- unlocks.unlock.mega_jump.hint: Some things jump high
- unlocks.unlock.mega_jump.name: MEGA JUMP
- unlocks.unlock.mining_efficiency_2.description: Dig, dig, dig
- unlocks.unlock.mining_efficiency_2.name: Mining effeicenter
- unlocks.unlock.mining_efficiency_3.description: Dig, dig, dig, and dig
- unlocks.unlock.mining_efficiency_3.name: Mining effeicentest
- unlocks.unlock.mining_efficiency.description: Dig, dig
- unlocks.unlock.mining_efficiency.name: Mining effeicency
- unlocks.unlock.mining.description: What it's all about
- unlocks.unlock.mining.name: Mining
- unlocks.unlock.mise_en_place.description: Mommy never had to face the dinner rush
- unlocks.unlock.mise_en_place.name: Mise en place
- unlocks.unlock.more_more_pearls.description: PEARLOMANIAC
- unlocks.unlock.more_more_pearls.name: When yhou just can't get enough!
- unlocks.unlock.more_pearls.description: Gimme more, MORE!
- unlocks.unlock.more_pearls.name: Pearltastic
- unlocks.unlock.more_starter_apples.description: Bring a meal with you
- unlocks.unlock.more_starter_apples.name: More Apples
- unlocks.unlock.movement_boost.description: Gotta go faster!
- unlocks.unlock.movement_boost.name: Speedrun
- unlocks.unlock.ore_seeker_1.description: More for ore!
- unlocks.unlock.ore_seeker_1.name: Ore Seeker
- unlocks.unlock.ore_seeker_2.description: Even more, more for ore!
- unlocks.unlock.ore_seeker_2.name: Ore Seeker: 2
- unlocks.unlock.pathfinder.description: Stop hitting yourself (when using Eye of Exit)
- unlocks.unlock.pathfinder.name: Pathfinder
- unlocks.unlock.pet_armadillo.description: Rollout!
- unlocks.unlock.pet_armadillo.name: Pet Armadillo
- unlocks.unlock.pet_axolotl.description: He likes you a lotl
- unlocks.unlock.pet_axolotl.name: Pet Axolotl
- unlocks.unlock.pet_bee.description: Bzzzzzzzzzzz
- unlocks.unlock.pet_bee.name: Pet Bee
- unlocks.unlock.pet_cat.description: Pawsitiviely Purrrrfect
- unlocks.unlock.pet_cat.name: Pet Cat
- unlocks.unlock.pet_chicken.description: More courageous than you think
- unlocks.unlock.pet_chicken.name: Pet Chicken
- unlocks.unlock.pet_cow.description: The cow says: "Moooooo"
- unlocks.unlock.pet_cow.name: Pet Cow
- unlocks.unlock.pet_creeper.description: This one is more "Aww cute!" than "Aww man!"
- unlocks.unlock.pet_creeper.name: Pet Creeper
- unlocks.unlock.pet_fox.description: What does it say?
- unlocks.unlock.pet_fox.name: Pet Fox
- unlocks.unlock.pet_frog.description: This one won't turn into a prince
- unlocks.unlock.pet_frog.name: Pet Frog
- unlocks.unlock.pet_mooshroom.description: The hivemind echoes in your head: "MOOOOOO"
- unlocks.unlock.pet_mooshroom.name: Pet Mooshroom
- unlocks.unlock.pet_polar_bear.description: Nice kitty!
- unlocks.unlock.pet_polar_bear.name: Pet Polar Bear
- unlocks.unlock.pet_slime.description: Sticky!
- unlocks.unlock.pet_slime.name: Pet Slime
- unlocks.unlock.pet_the_animal.description: Can I pet that DAWG?
- unlocks.unlock.pet_the_animal.name: Pet your pets
- unlocks.unlock.pet_turtle.description: A shell of protection
- unlocks.unlock.pet_turtle.name: Pet Turtle
- unlocks.unlock.pet_wolf_armored.description: Always wear protection
- unlocks.unlock.pet_wolf_armored.name: Armor up
- unlocks.unlock.pet_wolf_big.description: The bigger the better
- unlocks.unlock.pet_wolf_big.name: Direwolf
- unlocks.unlock.pet_wolf_sword.description: Voracious like no other
- unlocks.unlock.pet_wolf_sword.name: Descendant of Sif
- unlocks.unlock.pet_wolf.description: Who's a good boy?
- unlocks.unlock.pet_wolf.name: Pet Wolf
- unlocks.unlock.pet.description: The game is better with a friend
- unlocks.unlock.pet.name: Pets
- unlocks.unlock.pets.description: This one's just here to annoy you
- unlocks.unlock.pets.name: Pets
- unlocks.unlock.pickup_area_size.description: Now those are some long arms!
- unlocks.unlock.pickup_area_size.name: Collector
- unlocks.unlock.poseidon.description: Might as well run with it
- unlocks.unlock.poseidon.name: Poseidon
- unlocks.unlock.proper_walking_pace.description: Why the rush?
- unlocks.unlock.proper_walking_pace.name: Proper Walking Pace
- unlocks.unlock.quiver.description: Hey, you forgot these
- unlocks.unlock.quiver.name: Quiver
- unlocks.unlock.rare_earth_specialist.description: You yearn for rare earth materials
- unlocks.unlock.rare_earth_specialist.name: Rare Earth Specialist
- unlocks.unlock.rewrite_in_rust.description: Rewrite your gear in rust
- unlocks.unlock.rewrite_in_rust.name: Rewrite in Rust
- unlocks.unlock.rockets.description: The state of the art mode of transportation, totally safe!
- unlocks.unlock.rockets.name: Booster
- unlocks.unlock.runemaster.description: A PhD in Enchanting? In this job market?
- unlocks.unlock.runemaster.name: Runemaster
- unlocks.unlock.safe_falling.description: This might help now
- unlocks.unlock.safe_falling.name: Safe Falling
- unlocks.unlock.school_of_actual_hard_knocks.description: Take your time when mining
- unlocks.unlock.school_of_actual_hard_knocks.name: School of Actual Hard Knocks
- unlocks.unlock.school_of_hard_knocks.description: Take your time when learning
- unlocks.unlock.school_of_hard_knocks.name: School of Hard Knocks
- unlocks.unlock.shazboots.description: Terrain permitting, practice skiing if you can. VGS!
- unlocks.unlock.shazboots.name: Shazboots!
- unlocks.unlock.shield_bash.description: You know, I never knew you could just put this in your main hand
- unlocks.unlock.shield_bash.name: Shield Bash
- unlocks.unlock.silky_pick.description: More ore?
- unlocks.unlock.silky_pick.name: Silky pick
- unlocks.unlock.smelt_value_1.description: Gain more experience from things smelted
- unlocks.unlock.smelt_value_1.name: Heart of gold
- unlocks.unlock.smelt_value_2.description: Gain even more experience from things smelted
- unlocks.unlock.smelt_value_2.name: Heart of Netherite?
- unlocks.unlock.smelter_1.description: You dabble in smelting
- unlocks.unlock.smelter_1.name: Apprentice Smelter
- unlocks.unlock.smelter_2.description: You have mastered the art of smelting
- unlocks.unlock.smelter_2.name: Master Smelter
- unlocks.unlock.sneak_1.description: Sneak as fast as when holding both 'w' and 'a' or 'd'
- unlocks.unlock.sneak_1.name: Swift sneaking
- unlocks.unlock.sneak_2.description: Now this is possibly even faster than running?
- unlocks.unlock.sneak_2.name: Swiftest sneak
- unlocks.unlock.sorcerer_supreme.description: Endless possibility... with the right tools!
- unlocks.unlock.sorcerer_supreme.name: Spellbook
- unlocks.unlock.speed_1.description: Amazing game, and super fast!
- unlocks.unlock.speed_1.name: Need for speed
- unlocks.unlock.speed_2.description: Wow, and this is even better
- unlocks.unlock.speed_2.name: Need for speed: II
- unlocks.unlock.speed_3.description: Maybe this is as good as it gets?
- unlocks.unlock.speed_3.name: Hot Pursuit
- unlocks.unlock.starter_apples.description: Bring a snack with you
- unlocks.unlock.starter_apples.name: Doctors order
- unlocks.unlock.starter_compass.description: Gives a starter compass, how handy!
- unlocks.unlock.starter_compass.name: Starter Compass
- unlocks.unlock.starter_crafting.description: This might come in handy to always have
- unlocks.unlock.starter_crafting.name: Crafting table
- unlocks.unlock.starter_pick.description: Look at that, imagine starting with that
- unlocks.unlock.starter_pick.name: Starting pickaxe
- unlocks.unlock.starter_shield.description: Better safe than sorry
- unlocks.unlock.starter_shield.name: Warded
- unlocks.unlock.starter_sword_iron.description: Upgrade your starter sword
- unlocks.unlock.starter_sword_iron.name: You call that a knoife?
- unlocks.unlock.starter_sword.description: It might not be much, but it's yours
- unlocks.unlock.starter_sword.name: Training Sword
- unlocks.unlock.sub_mining_efficiency.description: Submerged mining efficiency
- unlocks.unlock.sub_mining_efficiency.hint: Win a map in a place where water is everything
- unlocks.unlock.sub_mining_efficiency.name: Underwater miner
- unlocks.unlock.teleportation_wand.description: There and back again
- unlocks.unlock.teleportation_wand.hint: Defeat a terrifying teleporting enemy
- unlocks.unlock.teleportation_wand.name: Enigma
- unlocks.unlock.thorns_plus_plus.description: Make sure to report any bugs to /dev/null
- unlocks.unlock.thorns_plus_plus.name: Thorns++
- unlocks.unlock.tracker.description: They're not getting away
- unlocks.unlock.tracker.name: Tracker
- unlocks.unlock.trident.description: Are you sure this is the right tree?
- unlocks.unlock.trident.name: Spearfishing
- unlocks.unlock.varangian.description: These trees will rue the day they crossed you
- unlocks.unlock.varangian.name: Varangian
- unlocks.unlock.viking.description: This woodcutter is also good at sailing
- unlocks.unlock.viking.name: Viking
- unlocks.unlock.wind_wand.description: Watch out for the wind!
- unlocks.unlock.wind_wand.hint: Defeat a bouncy breezy enemy
- unlocks.unlock.wind_wand.name: Heart of the Oak
- unlocks.unlock.wing_guardian_lift_off_to_the_sky.description: Feathers can help you reach for the sky
- unlocks.unlock.wing_guardian_lift_off_to_the_sky.hint: The first pioneers of flight weren't always successful, maybe you can do better after unlocking the spellbook
- unlocks.unlock.wing_guardian_lift_off_to_the_sky.name: Wing Guardian Leaf In Ocean
- unlocks.unlock.you_are_the_campfire.description: Do I need to say it again? You are the campfire!
- unlocks.unlock.you_are_the_campfire.name: You Are the Campfire
- world.effect.amplified.description: What... up THERE?
- world.effect.amplified.hint: Place a block high up in the world
- world.effect.amplified.name: Amplified World
- world.effect.angry_ghast_boss_fight.description: This one's not happy with you
- world.effect.angry_ghast_boss_fight.hint: Give a Ghast a taste of its own medicine
- world.effect.angry_ghast_boss_fight.name: Angry Ghast Boss
- world.effect.armadillos.description: Careful, you might scare them
- world.effect.armadillos.hint: They like being brushed
- world.effect.armadillos.name: Armadillos
- world.effect.axolotls.description: Anybody got a bucket?
- world.effect.axolotls.hint: Slippery!
- world.effect.axolotls.name: Axolotls
- world.effect.badlands.description: Lands took a turn for the bad
- world.effect.badlands.hint: Play in the mud
- world.effect.badlands.name: Badlands Biomes
- world.effect.base_andesite.description: The mountains are made of Andesite
- world.effect.base_andesite.hint: Mine Andesite
- world.effect.base_andesite.name: Base rock type: Andesite
- world.effect.base_blackstone.description: The mountains are made of Blackstone
- world.effect.base_blackstone.hint: Mine Blackstone
- world.effect.base_blackstone.name: Base rock type: Blackstone
- world.effect.base_deepslate.description: The mountains are made of Deepslate
- world.effect.base_deepslate.hint: Mine Deepslate
- world.effect.base_deepslate.name: Base rock type: Deepslate
- world.effect.base_diorite.description: The mountains are made of Diorite
- world.effect.base_diorite.hint: Mine Diorite
- world.effect.base_diorite.name: Base rock type: Diorite
- world.effect.base_end_stone.description: The mountains are made of End Stone
- world.effect.base_end_stone.hint: Mine End Stone
- world.effect.base_end_stone.name: Base rock type: End Stone
- world.effect.base_granite.description: The mountains are made of Granite
- world.effect.base_granite.hint: Mine Granite
- world.effect.base_granite.name: Base rock type: Granite
- world.effect.base_stone.description: The mountains are made of Stone
- world.effect.base_stone.name: Base rock type: Stone
- world.effect.base_tuff.description: The mountains are made of Tuff
- world.effect.base_tuff.hint: Mine Tuff
- world.effect.base_tuff.name: Base rock type: Tuff
- world.effect.bees.description: No, not the bees! NOT THE BEES!
- world.effect.bees.hint: You've killed their brother. Now they're out for revenge.
- world.effect.bees.name: Bees
- world.effect.blazes.description: They're all the hotness right now!
- world.effect.blazes.hint: Go mining in a Nether biome
- world.effect.blazes.name: Blazes
- world.effect.bouncy.description: Release your inner slime
- world.effect.bouncy.hint: Find and kill some Slime
- world.effect.bouncy.name: Bouncy Blocks
- world.effect.breezes.description: These ones should be a breeze!
- world.effect.breezes.hint: Trial spawners might have something to unlock this
- world.effect.breezes.name: Breezes
- world.effect.cave_exits.description: Mine Exits are found in caves
- world.effect.cave_exits.hint: Unlock Cave Mines or test your luck with Deepslate
- world.effect.cave_exits.name: Cave Exits
- world.effect.cave_spiders.description: Perilous Poisonous Pests
- world.effect.cave_spiders.hint: From Spiders
- world.effect.cave_spiders.name: Cave Spiders
- world.effect.cave_world.description: And they call it a Mine? A Mine!
- world.effect.cave_world.hint: Break a block deep down in the world
- world.effect.cave_world.name: Cave World
- world.effect.chickens.description: Who came first? Clearly the chicken, in this mine
- world.effect.chickens.name: Chickens
- world.effect.convert: Bring this item to the Mine exit to convert to experience
- world.effect.cows.description: Moo
- world.effect.cows.name: Cows
- world.effect.creepers.description: Tssssssssss
- world.effect.creepers.hint: I sense a theme, found while slaying monsters!
- world.effect.creepers.name: Creepers
- world.effect.dark_cave_world.description: Hello? Who turned off the lights?
- world.effect.dark_cave_world.hint: Win a Special Encounter Mine
- world.effect.dark_cave_world.name: Dark Cave World
- world.effect.dark_forests.description: Can't see the forests for all the trees
- world.effect.dark_forests.hint: Again!? Search among the leaves!
- world.effect.dark_forests.name: Dark Forest Biomes
- world.effect.deep_dark.description: The (maybe not so) Deep (and also maybe not entirely) Dark
- world.effect.deep_dark.hint: Search among blocks in a dark place...
- world.effect.deep_dark.name: Deep Dark Biome
- world.effect.desert.description: It's getting hot in here
- world.effect.desert.hint: Play in the sand
- world.effect.desert.name: Desert Biome
- world.effect.dry_land.description: Gronk thirsty. Gronk drink ALL water!
- world.effect.dry_land.hint: Try to get even warmer in the Badlands
- world.effect.dry_land.name: Dry Land
- world.effect.end.description: How did we End up here?
- world.effect.end.hint: What creatures do you usually kill to get to the end?
- world.effect.end.name: End Biomes
- world.effect.ender_dragon_boss_fight.description: You already know this one
- world.effect.ender_dragon_boss_fight.hint: Complete a Mine with an End biome
- world.effect.ender_dragon_boss_fight.name: Ender Dragon Boss
- world.effect.endermen.description: Look at me when I'm talking to you! Actually, wait...
- world.effect.endermen.hint: How many monster do you have to Slay!?
- world.effect.endermen.name: Endermen
- world.effect.endermites.description: Literally bugs in the game
- world.effect.endermites.hint: Found in the end stone
- world.effect.endermites.name: Endermites
- world.effect.eternal_lightning.description: Very, very frightening!
- world.effect.eternal_lightning.hint: Escape a Mine that will just not stop raining.
- world.effect.eternal_lightning.name: Eternal Lightning
- world.effect.eternal_night.description: It's dark in here isn't it?
- world.effect.eternal_night.hint: Unlocked after a while, I guess?
- world.effect.eternal_night.name: Eternal Night
- world.effect.eternal_rain.description: Blimey rainy innit?!
- world.effect.eternal_rain.hint: Win an eternally dark Mine
- world.effect.eternal_rain.name: Eternal Rain
- world.effect.event_exit.description: Complete the event to spawn the exit
- world.effect.event_exit.name: Event Mine
- world.effect.evokers.description: Wololo
- world.effect.evokers.hint: Buy it from a villager. The Lodestone will guide your way!
- world.effect.evokers.name: Evokers
- world.effect.experience_modifier: %s (x%s XP)
- world.effect.explosive_traps.description: Watch your step
- world.effect.explosive_traps.hint: Play a while..
- world.effect.explosive_traps.name: Explosive Traps
- world.effect.fish_out_of_water.description: Just keep swimming
- world.effect.fish_out_of_water.hint: Fish!
- world.effect.fish_out_of_water.name: Fish Out of Water
- world.effect.floating_islands_world.description: How can it be a Mine if it's not even solid?
- world.effect.floating_islands_world.hint: Win a Mine
- world.effect.floating_islands_world.name: Floating Islands
- world.effect.forests.description: Now with raised trees
- world.effect.forests.hint: Search among the Leaves
- world.effect.forests.name: Forest Biomes
- world.effect.foxes.description: What does the fox say?
- world.effect.foxes.hint: Berries
- world.effect.foxes.name: Foxes
- world.effect.frogs.description: Heralds of change
- world.effect.frogs.name: Frogs
- world.effect.ghasts.description: No, they're not happy
- world.effect.ghasts.hint: Probably dried out among fossils
- world.effect.ghasts.name: Ghasts
- world.effect.goats.description: Mischevious horned menace of the mountain
- world.effect.goats.hint: Go mining in the mountains
- world.effect.goats.name: Goats
- world.effect.grid_world.description: Linear. Orderly.
- world.effect.grid_world.hint: Win a Special Encounter Mine
- world.effect.grid_world.name: Grid World
- world.effect.guardians.description: Protectors of the deep
- world.effect.guardians.hint: Slaying creatures of the water will anger the Guardians
- world.effect.guardians.name: Guardians
- world.effect.hoglins.description: The whole hog
- world.effect.hoglins.hint: Through the death of many Pigs
- world.effect.hoglins.name: Hoglins
- world.effect.ice_spikes.description: Cool
- world.effect.ice_spikes.hint: Win a snowy Mine
- world.effect.ice_spikes.name: Ice Spikes Biome
- world.effect.icy.description: Might be a little slippery...
- world.effect.icy.hint: Take a boat ride
- world.effect.icy.name: Icy Surfaces
- world.effect.illusioners.description: It's not even in the game
- world.effect.illusioners.hint: Buy it from a villager. The Lodestone will guide your way!
- world.effect.illusioners.name: Illusioners
- world.effect.insomniacs.description: No rest, no respite
- world.effect.insomniacs.hint: Win a Mine that never sees the light of day
- world.effect.insomniacs.name: Insomniacs
- world.effect.jungles.description: In the Jungle, the Miney Jungle
- world.effect.jungles.hint: Do not leave the leaves alone!
- world.effect.jungles.name: Jungle Biomes
- world.effect.kuiper_world.description: Igloo in spaaaaace!
- world.effect.kuiper_world.name: Kuiper World
- world.effect.magma_cubes.description: Squishy and stompy and hot at the same time
- world.effect.magma_cubes.hint: Get some Magma
- world.effect.magma_cubes.name: Magma Cubes
- world.effect.mooshrooms.description: These mushrooms moo
- world.effect.mooshrooms.hint: Go pick mushrooms
- world.effect.mooshrooms.name: Mooshrooms
- world.effect.mushroom_fields.description: Mushroom islands, except not only islands
- world.effect.mushroom_fields.hint: Collect Mushrooms and you might get lucky
- world.effect.mushroom_fields.name: Mushroom Fields Biome
- world.effect.nether_barrens.description: Things are heating up!
- world.effect.nether_barrens.hint: The Ice Bucket Challenge
- world.effect.nether_barrens.name: Barren Nether Biomes
- world.effect.nether_forests.description: Can't see the forest for the... fungi?
- world.effect.nether_forests.hint: Found while slaying Endermen
- world.effect.nether_forests.name: Nether Forest Biomes
- world.effect.no_drops.description: Who needs it?
- world.effect.no_drops.hint: Found by chance
- world.effect.no_drops.name: No drops?
- world.effect.ocelots.description: Kitty!
- world.effect.ocelots.hint: Whiskers!
- world.effect.ocelots.name: Ocelots
- world.effect.one_hp.description: There is only one heart.
- world.effect.one_hp.hint: Kill something while having only one heart
- world.effect.one_hp.name: One HP
- world.effect.pandas.description: Cute and clumsy
- world.effect.pandas.hint: Eat some bamboo
- world.effect.pandas.name: Pandas
- world.effect.parrots.description: Tssssss sharp
- world.effect.parrots.hint: Eat a cookie, the Parrot doesn't want it anyway
- world.effect.parrots.name: Parrots
- world.effect.piglins.description: Pigs that love gold... and violence
- world.effect.piglins.hint: Feed some gold to a pig
- world.effect.piglins.name: Piglins
- world.effect.pigs.description: Pork-u-pines, except without the pines?
- world.effect.pigs.name: Pigs
- world.effect.pillagers.description: Villager, Illager, Pillager - what's the difference?
- world.effect.pillagers.hint: Buy it from a villager. The Lodestone will guide your way!
- world.effect.pillagers.name: Pillagers
- world.effect.plains.description: Quite plain
- world.effect.plains.name: Plains Biomes
- world.effect.rabbits.description: Jumpy meals
- world.effect.rabbits.hint: Jump... from really high up
- world.effect.rabbits.name: Rabbits
- world.effect.raid.description: They're coming for your loot
- world.effect.raid.hint: Slay a Pillager
- world.effect.raid.name: Raid!
- world.effect.rare_surface_exits.description: Mine Exits are found on the surface, but it might be a trek to get to one
- world.effect.rare_surface_exits.hint: Craft an item that helps you locate Mine Exits
- world.effect.rare_surface_exits.name: Rare Surface Exits
- world.effect.ravagers.description: Rawr
- world.effect.ravagers.hint: Buy it from a villager. The Lodestone will guide your way!
- world.effect.ravagers.name: Ravagers
- world.effect.savannas.description: On the great wide savanna steppes...
- world.effect.savannas.name: Savanna Biomes
- world.effect.shattered_blocks_world.description: Shattered world made of big blocks with large gaps
- world.effect.shattered_blocks_world.hint: Win a Special Encounter Mine
- world.effect.shattered_blocks_world.name: Shattered Blocks World
- world.effect.sheep.description: Fluffy mine
- world.effect.sheep.name: Sheep
- world.effect.shulkers.description: Box material
- world.effect.shulkers.hint: Stomp out bugs from their natural environment
- world.effect.shulkers.name: Shulkers
- world.effect.skeletons.description: Feel it in my bones
- world.effect.skeletons.hint: A chance while slaying monsters
- world.effect.skeletons.name: Skeletons
- world.effect.slimes.description: Get slimed!
- world.effect.slimes.hint: You guessed it - Slay monsters!
- world.effect.slimes.name: Slimes
- world.effect.small_but_deadly_boss_fight.description: Tiny (not so) friendly critters
- world.effect.small_but_deadly_boss_fight.hint: Just play the game!
- world.effect.small_but_deadly_boss_fight.name: Small But Deadly Boss Fight
- world.effect.sniffers.description: Let the gentle giants roam the Mines once more
- world.effect.sniffers.hint: They like flowers
- world.effect.sniffers.name: Sniffers
- world.effect.snowy.description: Let it snow, let it snow, let it snow
- world.effect.snowy.hint: Search cold Blocks
- world.effect.snowy.name: Snowy Biomes
- world.effect.soul_link.description: Every player takes damage if one player is hurt
- world.effect.soul_link.hint: Win a mine with the "One HP" ingredient
- world.effect.soul_link.name: Soul Link
- world.effect.spiders.description: So many years of bad luck from this one
- world.effect.spiders.hint: Slay Slay, slay...
- world.effect.spiders.name: Spiders
- world.effect.striders.description: You better make the mine have some warm cozy lava
- world.effect.striders.hint: Prepare to go riding
- world.effect.striders.name: Striders
- world.effect.surface_exits.description: Mine Exits are found on the surface
- world.effect.surface_exits.name: Surface Exits
- world.effect.surface_world.description: World above the Mines. Like... an aboveworld
- world.effect.surface_world.name: Surface World
- world.effect.swamps.description: Get ready to get your boots wet
- world.effect.swamps.hint: Find the source of the smallest creature
- world.effect.swamps.name: Swamp Biomes
- world.effect.taigas.description: Don't step on the pine cones
- world.effect.taigas.hint: Found somewhere in the trees
- world.effect.taigas.name: Taiga Biomes
- world.effect.the_enderman_boss_fight.description: THIS Enderman
- world.effect.the_enderman_boss_fight.hint: Just play the game!
- world.effect.the_enderman_boss_fight.name: The Enderman Boss Fight
- world.effect.ultrawarm.description: It's getting hot in here
- world.effect.ultrawarm.hint: Stand in lava... if you dare
- world.effect.ultrawarm.name: Ultrawarm
- world.effect.universal_anger.description: Every neutral mob is hostile
- world.effect.universal_anger.hint: Win a mine with the "Bees" ingredient
- world.effect.universal_anger.name: (Near) Universal Anger
- world.effect.unlock: Bring this item to the Mine exit to unlock as a Mine ingredient
- world.effect.unlocked: Unlocked new Mine Ingredient: %s
- world.effect.vindicators.description: Here's Johnny!
- world.effect.vindicators.hint: Buy it from a villager. The Lodestone will guide your way!
- world.effect.vindicators.name: Vindicators
- world.effect.void_world.description: It stares also into you
- world.effect.void_world.name: Void World
- world.effect.warden_boss_fight.description: Warden wards off the competition
- world.effect.warden_boss_fight.hint: Walk on this block and give of a chime, it's a nice crystal but not even worth a dime
- world.effect.warden_boss_fight.name: Warden Boss Fight
- world.effect.water_world.description: Like the hit film from Cavin' Costner
- world.effect.water_world.hint: Win a dry Mine
- world.effect.water_world.name: Water World
- world.effect.wednesday_frogs.description: Heralds of doom
- world.effect.wednesday_frogs.hint: Might be trickier to find than you might think
- world.effect.wednesday_frogs.name: Wednesday Frogs
- world.effect.witches.description: Double, double toil and trouble
- world.effect.witches.hint: You would have never guessed it! Slay monsters to find this one! :D
- world.effect.witches.name: Witches
- world.effect.wither_boss_fight.description: They say this one's harder when it's standing on Bedrock
- world.effect.wither_boss_fight.hint: Obtain a Wither Skull
- world.effect.wither_boss_fight.name: Wither Boss Fight
- world.effect.wither_skeletons.description: Wither, Blister, Burn & Peel
- world.effect.wither_skeletons.hint: Hidden among the regular Skeletons
- world.effect.wither_skeletons.name: Wither Skeletons
- world.effect.zoglins.description: So angry
- world.effect.zoglins.hint: Kill a zombie on the turf of the Piglins
- world.effect.zoglins.name: Zoglins
- world.effect.zombies.description: Braaaaaiiiinsss
- world.effect.zombies.hint: Go on a monster hunt!
- world.effect.zombies.name: Zombies
- world.effect.zombified_piglins.description: These pigs seem quite easily angered
- world.effect.zombified_piglins.hint: Somehow related to pigs in the fires of the nether
- world.effect.zombified_piglins.name: Zombified Piglins
- world.event.angry_ghast: Angry Ghast Spawns
- world.event.ender_dragon: Ender Dragon Spawns
- world.event.enderman: The Enderman Spawns
- world.event.next_wave: Next Wave
- world.event.remaining: Mobs Remaining
- world.event.warden: Warden Spawns
- world.event.wither: Wither Spawns
- world.mine: Mine %s
- world.mine.base: Mine %s Base
- world.mine.next: Next Mine
- world.mine.revisit.lost: Revisiting old Mine that sadly was lost
- world.mine.revisit.won: Revisiting old Mine that was won
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>25w14craftmine</th><th>25w15a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.return_to_sender.description</div></th><td>Destroy a Ghast with a fireball to unlock the Angry Ghast special event</td><td>Destroy a Ghast with a fireball</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.set_spawn</div></th><td>You didn't think this would work, did you?</td><td>Respawn point set</td></tr>
<tr><th align="left"><div style="width:290px">entity.minecraft.eye_of_ender</div></th><td>Eye of Exit</td><td>Eye of Ender</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.gameMode.survival.info</div></th><td>Craft and explore mines, unlock more ingredients, craft some more - and watch out for the special encounters!</td><td>Explore a mysterious world where you build, collect, craft, and fight monsters.</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.end_portal_frame.fill</div></th><td>Eye of Exit attaches</td><td>Eye of Ender attaches</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.end_portal.spawn</div></th><td>Portal sounds</td><td>End Portal opens</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ender_eye.death</div></th><td>Eye of Exit falls</td><td>Eye of Ender falls</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ender_eye.launch</div></th><td>Eye of Exit shoots</td><td>Eye of Ender shoots</td></tr>
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
- minecraft:change_dimension_type
- minecraft:open_door_packet
+ minecraft:open_screen
- minecraft:open_window
- minecraft:player_unlocks
- minecraft:update_screen
- minecraft:update_unlocked_effects
+ minecraft:waypoint
```

</details>
<details>
<summary>
[server] play
</summary>

```diff
- minecraft:player_buy_unlock
- minecraft:player_donate_experience
- minecraft:player_reactivate_unlock
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
- reports/biome_parameters/minecraft/endish.json
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
+ minecraft/advancement/adventure/blowback.json
+ minecraft/advancement/adventure/brush_armadillo.json
+ minecraft/advancement/adventure/bullseye.json
+ minecraft/advancement/adventure/craft_decorated_pot_using_only_sherds.json
+ minecraft/advancement/adventure/crafters_crafting_crafters.json
+ minecraft/advancement/adventure/fall_from_world_height.json
+ minecraft/advancement/adventure/heart_transplanter.json
+ minecraft/advancement/adventure/hero_of_the_village.json
+ minecraft/advancement/adventure/honey_block_slide.json
+ minecraft/advancement/adventure/kill_a_mob.json
+ minecraft/advancement/adventure/kill_all_mobs.json
+ minecraft/advancement/adventure/kill_mob_near_sculk_catalyst.json
+ minecraft/advancement/adventure/lighten_up.json
+ minecraft/advancement/adventure/lightning_rod_with_villager_no_fire.json
+ minecraft/advancement/adventure/minecraft_trials_edition.json
+ minecraft/advancement/adventure/ol_betsy.json
+ minecraft/advancement/adventure/overoverkill.json
+ minecraft/advancement/adventure/play_jukebox_in_meadows.json
+ minecraft/advancement/adventure/read_power_of_chiseled_bookshelf.json
+ minecraft/advancement/adventure/revaulting.json
+ minecraft/advancement/adventure/root.json
+ minecraft/advancement/adventure/salvage_sherd.json
+ minecraft/advancement/adventure/shoot_arrow.json
+ minecraft/advancement/adventure/sleep_in_bed.json
+ minecraft/advancement/adventure/sniper_duel.json
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
+ minecraft/advancement/end/dragon_breath.json
+ minecraft/advancement/end/dragon_egg.json
+ minecraft/advancement/end/elytra.json
+ minecraft/advancement/end/enter_end_gateway.json
+ minecraft/advancement/end/find_end_city.json
+ minecraft/advancement/end/kill_dragon.json
+ minecraft/advancement/end/levitate.json
+ minecraft/advancement/end/respawn_dragon.json
+ minecraft/advancement/end/root.json
- minecraft/advancement/feats/angry_ghast.json
- minecraft/advancement/feats/crystal.json
- minecraft/advancement/feats/dragon_breath.json
- minecraft/advancement/feats/end_world.json
- minecraft/advancement/feats/ender_dragon.json
- minecraft/advancement/feats/enderman.json
- minecraft/advancement/feats/kill_pillager.json
- minecraft/advancement/feats/kill_skeleton.json
- minecraft/advancement/feats/kuiper_world.json
- minecraft/advancement/feats/raid.json
- minecraft/advancement/feats/return_to_sender.json
- minecraft/advancement/feats/root.json
- minecraft/advancement/feats/small_but_deadly.json
- minecraft/advancement/feats/spooky_scary_skeletons.json
- minecraft/advancement/feats/warden.json
- minecraft/advancement/feats/wither_skeleton_skull.json
- minecraft/advancement/feats/wither.json
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
- minecraft/advancement/mines/all_mine_ingredients.json
- minecraft/advancement/mines/all_special_mines_completed.json
- minecraft/advancement/mines/cash_in_mine_ingredient.json
- minecraft/advancement/mines/complete_deluge_level.json
- minecraft/advancement/mines/complete_water_cave_level.json
- minecraft/advancement/mines/complete_water_world_level.json
- minecraft/advancement/mines/eat_your_veggies.json
- minecraft/advancement/mines/enter_a_mine.json
- minecraft/advancement/mines/get_mine_ingredient.json
- minecraft/advancement/mines/level_completed.json
- minecraft/advancement/mines/mine_crafter_upgraded.json
- minecraft/advancement/mines/mine_revisitor_activated.json
- minecraft/advancement/mines/player_failed_level.json
- minecraft/advancement/mines/shimmering_key.json
- minecraft/advancement/mines/special_mine_completed.json
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
+ minecraft/advancement/recipes/building_blocks/dried_ghast.json
+ minecraft/advancement/recipes/building_blocks/dye_black_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_blue_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_brown_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_cyan_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_gray_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_green_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_light_blue_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_light_gray_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_lime_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_magenta_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_orange_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_pink_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_purple_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_red_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_white_harness.json
+ minecraft/advancement/recipes/building_blocks/dye_yellow_harness.json
+ minecraft/advancement/recipes/misc/ender_eye.json
- minecraft/advancement/recipes/misc/exit_eye.json
+ minecraft/advancement/recipes/transportation/black_harness.json
+ minecraft/advancement/recipes/transportation/blue_harness.json
+ minecraft/advancement/recipes/transportation/brown_harness.json
+ minecraft/advancement/recipes/transportation/cyan_harness.json
+ minecraft/advancement/recipes/transportation/gray_harness.json
+ minecraft/advancement/recipes/transportation/green_harness.json
+ minecraft/advancement/recipes/transportation/light_blue_harness.json
+ minecraft/advancement/recipes/transportation/light_gray_harness.json
+ minecraft/advancement/recipes/transportation/lime_harness.json
+ minecraft/advancement/recipes/transportation/magenta_harness.json
+ minecraft/advancement/recipes/transportation/orange_harness.json
+ minecraft/advancement/recipes/transportation/pink_harness.json
+ minecraft/advancement/recipes/transportation/purple_harness.json
+ minecraft/advancement/recipes/transportation/red_harness.json
+ minecraft/advancement/recipes/transportation/white_harness.json
+ minecraft/advancement/recipes/transportation/yellow_harness.json
+ minecraft/advancement/story/cure_zombie_villager.json
+ minecraft/advancement/story/enchant_item.json
+ minecraft/advancement/story/enter_the_end.json
+ minecraft/advancement/story/enter_the_nether.json
+ minecraft/advancement/story/follow_ender_eye.json
- minecraft/advancement/story/follow_exit_eye.json
+ minecraft/advancement/story/form_obsidian.json
+ minecraft/advancement/story/lava_bucket.json
- minecraft/advancement/unlocks/all_combatant.json
- minecraft/advancement/unlocks/all_crafting.json
- minecraft/advancement/unlocks/all_exploration.json
- minecraft/advancement/unlocks/all_gatherer.json
- minecraft/advancement/unlocks/all_school_of_hard_knocks.json
- minecraft/advancement/unlocks/free_sticks.json
- minecraft/advancement/unlocks/how_do_i_unlock_that.json
- minecraft/advancement/unlocks/in_it_together.json
- minecraft/advancement/unlocks/jump_king.json
- minecraft/advancement/unlocks/kaizen.json
- minecraft/advancement/unlocks/root.json
- minecraft/advancement/unlocks/sigma_grindset.json
- minecraft/damage_type/devour.json
+ minecraft/datapacks/locator_bar/pack.mcmeta
- minecraft/dimension_type/generated.json
- minecraft/jukebox_song/and_action.json
- minecraft/loot_table/blocks/dimension_control.json
+ minecraft/loot_table/blocks/dried_ghast.json
- minecraft/loot_table/blocks/mine_crafter.json
- minecraft/loot_table/blocks/mine_revisitor.json
- minecraft/loot_table/blocks/mob_trophy.json
- minecraft/loot_table/blocks/trophy.json
- minecraft/loot_table/entities/angry_ghast.json
+ minecraft/loot_table/entities/happy_ghast.json
- minecraft/loot_table/entities/pet_armadillo.json
- minecraft/loot_table/entities/pet_axolotl.json
- minecraft/loot_table/entities/pet_bee.json
- minecraft/loot_table/entities/pet_cat.json
- minecraft/loot_table/entities/pet_chicken.json
- minecraft/loot_table/entities/pet_cow.json
- minecraft/loot_table/entities/pet_creeper.json
- minecraft/loot_table/entities/pet_fox.json
- minecraft/loot_table/entities/pet_frog.json
- minecraft/loot_table/entities/pet_mooshroom.json
- minecraft/loot_table/entities/pet_polar_bear.json
- minecraft/loot_table/entities/pet_slime.json
- minecraft/loot_table/entities/pet_turtle.json
- minecraft/loot_table/entities/pet_wolf.json
- minecraft/loot_table/gameplay/room_rewards.json
- minecraft/loot_table/mines/eat_your_veggies.json
+ minecraft/recipe/black_harness.json
+ minecraft/recipe/blue_harness.json
+ minecraft/recipe/brown_harness.json
+ minecraft/recipe/cyan_harness.json
+ minecraft/recipe/dried_ghast.json
+ minecraft/recipe/dye_black_harness.json
+ minecraft/recipe/dye_blue_harness.json
+ minecraft/recipe/dye_brown_harness.json
+ minecraft/recipe/dye_cyan_harness.json
+ minecraft/recipe/dye_gray_harness.json
+ minecraft/recipe/dye_green_harness.json
+ minecraft/recipe/dye_light_blue_harness.json
+ minecraft/recipe/dye_light_gray_harness.json
+ minecraft/recipe/dye_lime_harness.json
+ minecraft/recipe/dye_magenta_harness.json
+ minecraft/recipe/dye_orange_harness.json
+ minecraft/recipe/dye_pink_harness.json
+ minecraft/recipe/dye_purple_harness.json
+ minecraft/recipe/dye_red_harness.json
+ minecraft/recipe/dye_white_harness.json
+ minecraft/recipe/dye_yellow_harness.json
+ minecraft/recipe/ender_eye.json
- minecraft/recipe/exit_eye.json
+ minecraft/recipe/gray_harness.json
+ minecraft/recipe/green_harness.json
+ minecraft/recipe/light_blue_harness.json
+ minecraft/recipe/light_gray_harness.json
+ minecraft/recipe/lime_harness.json
+ minecraft/recipe/magenta_harness.json
+ minecraft/recipe/orange_harness.json
+ minecraft/recipe/pink_harness.json
+ minecraft/recipe/purple_harness.json
+ minecraft/recipe/red_harness.json
+ minecraft/recipe/white_harness.json
+ minecraft/recipe/yellow_harness.json
- minecraft/structure/hub/center_base.nbt
- minecraft/structure/hub/center_hat.nbt
- minecraft/structure/hub/corridor_base.nbt
- minecraft/structure/hub/corridor_hat.nbt
- minecraft/structure/hub/room/barrels.nbt
- minecraft/structure/hub/room/boiler.nbt
- minecraft/structure/hub/room/carpet.nbt
- minecraft/structure/hub/room/corridor_simple.nbt
- minecraft/structure/hub/room/fountain.nbt
- minecraft/structure/hub/room/grassy_h.nbt
- minecraft/structure/hub/room/hanging.nbt
- minecraft/structure/hub/room/house.nbt
- minecraft/structure/hub/room/labyrinth.nbt
- minecraft/structure/hub/room/pool.nbt
- minecraft/structure/hub/room/ship.nbt
- minecraft/structure/hub/room/simple.nbt
- minecraft/structure/hub/room/stairs.nbt
- minecraft/structure/hub/room/storage1.nbt
- minecraft/structure/hub/room/storage2.nbt
- minecraft/structure/hub/room/sugar_h.nbt
- minecraft/structure/hub/room/test.nbt
- minecraft/structure/hub/room/tree.nbt
- minecraft/structure/hub/room/trophy.nbt
- minecraft/structure/hub/room/tunnel.nbt
- minecraft/structure/hub/room/useless.nbt
- minecraft/structure/hub/room/wheat_h.nbt
- minecraft/structure/hub/room/workshop.nbt
- minecraft/structure/mine_exits/exit_01.nbt
- minecraft/structure/mine_exits/root.nbt
- minecraft/structure/mines/dirty_ice_ball_fox.nbt
- minecraft/structure/mines/dirty_ice_ball_golems.nbt
- minecraft/structure/mines/dirty_ice_ball.nbt
- minecraft/structure/mines/space_igloo.nbt
- minecraft/structure/mines/start_platform.nbt
- minecraft/structure/mines/warden_arena.nbt
- minecraft/tags/block/plays_ambient_desert_block_sounds.json
+ minecraft/tags/block/triggers_ambient_desert_dry_vegetation_block_sounds.json
+ minecraft/tags/block/triggers_ambient_desert_sand_block_sounds.json
+ minecraft/tags/entity_type/can_equip_harness.json
+ minecraft/tags/entity_type/followable_friendly_mobs.json
- minecraft/tags/item/amethyst_crystals.json
- minecraft/tags/item/carry_over.json
+ minecraft/tags/item/happy_ghast_food.json
+ minecraft/tags/item/happy_ghast_tempt_items.json
+ minecraft/tags/item/harnesses.json
- minecraft/tags/item/ingot.json
- minecraft/tags/item/ore.json
- minecraft/tags/worldgen/structure/mine_exit.json
- minecraft/worldgen/biome/hub.json
- minecraft/worldgen/configured_feature/dirty_ice_ball_fox.json
- minecraft/worldgen/configured_feature/dirty_ice_ball_golems.json
- minecraft/worldgen/configured_feature/dirty_ice_ball.json
- minecraft/worldgen/configured_feature/mine_start.json
- minecraft/worldgen/configured_feature/ore_stone.json
- minecraft/worldgen/configured_feature/space_igloo.json
- minecraft/worldgen/configured_feature/warden_arena.json
+ minecraft/worldgen/density_function/overworld_large_biomes/continents.json
+ minecraft/worldgen/density_function/overworld_large_biomes/depth.json
+ minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
+ minecraft/worldgen/density_function/overworld_large_biomes/factor.json
+ minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
+ minecraft/worldgen/density_function/overworld_large_biomes/offset.json
+ minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
- minecraft/worldgen/multi_noise_biome_source_parameter_list/endish.json
+ minecraft/worldgen/noise_settings/large_biomes.json
+ minecraft/worldgen/noise/continentalness_large.json
+ minecraft/worldgen/noise/erosion_large.json
+ minecraft/worldgen/noise/temperature_large.json
+ minecraft/worldgen/noise/vegetation_large.json
- minecraft/worldgen/placed_feature/ore_stone_lower.json
- minecraft/worldgen/placed_feature/ore_stone_upper.json
- minecraft/worldgen/structure_set/cave_mine_exits.json
- minecraft/worldgen/structure_set/rare_surface_mine_exits.json
- minecraft/worldgen/structure_set/surface_mine_exits.json
- minecraft/worldgen/structure/cave_mine_exit.json
- minecraft/worldgen/structure/rare_surface_mine_exit.json
- minecraft/worldgen/structure/surface_mine_exit.json
- minecraft/worldgen/template_pool/mine_exits/root.json
- minecraft/worldgen/template_pool/mine_exits/starts.json
+ minecraft/worldgen/world_preset/debug_all_block_states.json
+ minecraft/worldgen/world_preset/large_biomes.json
+ minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/dimension_control.json
+ minecraft/blockstates/dried_ghast.json
+ minecraft/blockstates/end_portal_frame.json
+ minecraft/blockstates/end_portal.json
- minecraft/blockstates/mine_crafter.json
- minecraft/blockstates/mine_revisitor.json
- minecraft/blockstates/mine_travelling_block.json
- minecraft/blockstates/mob_trophy.json
- minecraft/blockstates/shimmering_door.json
- minecraft/blockstates/sky.json
- minecraft/blockstates/trophy.json
+ minecraft/equipment/black_harness.json
+ minecraft/equipment/blue_harness.json
+ minecraft/equipment/brown_harness.json
+ minecraft/equipment/cyan_harness.json
+ minecraft/equipment/gray_harness.json
+ minecraft/equipment/green_harness.json
+ minecraft/equipment/light_blue_harness.json
+ minecraft/equipment/light_gray_harness.json
+ minecraft/equipment/lime_harness.json
+ minecraft/equipment/magenta_harness.json
+ minecraft/equipment/orange_harness.json
+ minecraft/equipment/pink_harness.json
+ minecraft/equipment/purple_harness.json
+ minecraft/equipment/red_harness.json
+ minecraft/equipment/white_harness.json
+ minecraft/equipment/yellow_harness.json
- minecraft/items/amplified.json
+ minecraft/items/black_harness.json
+ minecraft/items/blue_harness.json
+ minecraft/items/brown_harness.json
- minecraft/items/cave_exits.json
- minecraft/items/cave_world.json
+ minecraft/items/cyan_harness.json
- minecraft/items/dark_cave_world.json
- minecraft/items/dimension_control.json
+ minecraft/items/dried_ghast.json
+ minecraft/items/end_portal_frame.json
+ minecraft/items/ender_eye.json
- minecraft/items/exit_eye.json
- minecraft/items/fire_wand.json
- minecraft/items/floating_islands_world.json
- minecraft/items/grave_advancement.json
+ minecraft/items/gray_harness.json
+ minecraft/items/green_harness.json
- minecraft/items/grid_world.json
+ minecraft/items/happy_ghast_spawn_egg.json
- minecraft/items/illusioners.json
- minecraft/items/kuiper_world.json
+ minecraft/items/light_blue_harness.json
+ minecraft/items/light_gray_harness.json
+ minecraft/items/lime_harness.json
+ minecraft/items/magenta_harness.json
- minecraft/items/mine_crafter.json
- minecraft/items/mine_ingredient.json
- minecraft/items/mine_revisitor.json
- minecraft/items/mine.json
- minecraft/items/mob_trophy.json
- minecraft/items/music_disc_and_action.json
+ minecraft/items/orange_harness.json
- minecraft/items/pets_icon.json
+ minecraft/items/pink_harness.json
+ minecraft/items/purple_harness.json
- minecraft/items/rare_surface_exits.json
+ minecraft/items/red_harness.json
- minecraft/items/shattered_blocks.json
- minecraft/items/shazboots.json
- minecraft/items/shimmering_door.json
- minecraft/items/shimmering_key.json
- minecraft/items/sky_box.json
- minecraft/items/sky.json
- minecraft/items/surface_exits.json
- minecraft/items/surface_world.json
- minecraft/items/teleportation_wand.json
- minecraft/items/trophy.json
- minecraft/items/water_mining.json
+ minecraft/items/white_harness.json
- minecraft/items/wind_wand.json
+ minecraft/items/yellow_harness.json
- minecraft/models/block/block_generated.json
- minecraft/models/block/dimension_control.json
+ minecraft/models/block/dried_ghast_hydration_0.json
+ minecraft/models/block/dried_ghast_hydration_1.json
+ minecraft/models/block/dried_ghast_hydration_2.json
+ minecraft/models/block/dried_ghast_hydration_3.json
+ minecraft/models/block/dried_ghast.json
+ minecraft/models/block/end_portal.json
- minecraft/models/block/mine_crafter.json
- minecraft/models/block/mine_revisitor.json
- minecraft/models/block/mine_travelling_block.json
- minecraft/models/block/mob_trophy.json
- minecraft/models/block/shimmering_door_bottom_left_open.json
- minecraft/models/block/shimmering_door_bottom_left.json
- minecraft/models/block/shimmering_door_bottom_right_open.json
- minecraft/models/block/shimmering_door_bottom_right.json
- minecraft/models/block/shimmering_door_top_left_open.json
- minecraft/models/block/shimmering_door_top_left.json
- minecraft/models/block/shimmering_door_top_right_open.json
- minecraft/models/block/shimmering_door_top_right.json
- minecraft/models/block/sky.json
- minecraft/models/block/template_mine_crafter.json
- minecraft/models/block/template_mine_revisitor.json
- minecraft/models/block/trophy_gold.json
- minecraft/models/block/trophy_mega_spud.json
- minecraft/models/block/trophy_no_medal.json
- minecraft/models/item/amplified.json
+ minecraft/models/item/black_harness.json
+ minecraft/models/item/blue_harness.json
+ minecraft/models/item/brown_harness.json
- minecraft/models/item/cave_exits.json
- minecraft/models/item/cave_world.json
+ minecraft/models/item/cyan_harness.json
- minecraft/models/item/dark_cave_world.json
+ minecraft/models/item/ender_eye.json
- minecraft/models/item/exit_eye.json
- minecraft/models/item/fire_wand.json
- minecraft/models/item/floating_islands_world.json
- minecraft/models/item/grave_advancement.json
+ minecraft/models/item/gray_harness.json
+ minecraft/models/item/green_harness.json
- minecraft/models/item/grid_world.json
+ minecraft/models/item/happy_ghast_spawn_egg.json
- minecraft/models/item/illusioners.json
- minecraft/models/item/kuiper_world.json
+ minecraft/models/item/light_blue_harness.json
+ minecraft/models/item/light_gray_harness.json
+ minecraft/models/item/lime_harness.json
+ minecraft/models/item/magenta_harness.json
- minecraft/models/item/mine_ingredient.json
- minecraft/models/item/mine.json
- minecraft/models/item/music_disc_and_action.json
+ minecraft/models/item/orange_harness.json
- minecraft/models/item/pets_icon.json
+ minecraft/models/item/pink_harness.json
+ minecraft/models/item/purple_harness.json
- minecraft/models/item/rare_surface_exits.json
+ minecraft/models/item/red_harness.json
- minecraft/models/item/shattered_blocks.json
- minecraft/models/item/shazboots.json
- minecraft/models/item/shimmering_door.json
- minecraft/models/item/shimmering_key.json
- minecraft/models/item/sky_box.json
- minecraft/models/item/surface_exits.json
- minecraft/models/item/surface_world.json
- minecraft/models/item/teleportation_wand.json
- minecraft/models/item/water_mining.json
+ minecraft/models/item/white_harness.json
- minecraft/models/item/wind_wand.json
+ minecraft/models/item/yellow_harness.json
- minecraft/particles/mine_travel.json
- minecraft/shaders/core/rain.fsh
- minecraft/shaders/core/sky_block.fsh
- minecraft/shaders/core/sky_block.vsh
- minecraft/shaders/core/title_rain.fsh
- minecraft/textures/block/box_back_0.png
- minecraft/textures/block/box_base.png
- minecraft/textures/block/box_bottom.png
- minecraft/textures/block/box_front_0.png
- minecraft/textures/block/box_side_0.png
- minecraft/textures/block/cube_side_1.png
+ minecraft/textures/block/dried_ghast_hydration_0_bottom.png
+ minecraft/textures/block/dried_ghast_hydration_0_east.png
+ minecraft/textures/block/dried_ghast_hydration_0_north.png
+ minecraft/textures/block/dried_ghast_hydration_0_south.png
+ minecraft/textures/block/dried_ghast_hydration_0_tentacles.png
+ minecraft/textures/block/dried_ghast_hydration_0_top.png
+ minecraft/textures/block/dried_ghast_hydration_0_west.png
+ minecraft/textures/block/dried_ghast_hydration_1_bottom.png
+ minecraft/textures/block/dried_ghast_hydration_1_east.png
+ minecraft/textures/block/dried_ghast_hydration_1_north.png
+ minecraft/textures/block/dried_ghast_hydration_1_south.png
+ minecraft/textures/block/dried_ghast_hydration_1_tentacles.png
+ minecraft/textures/block/dried_ghast_hydration_1_top.png
+ minecraft/textures/block/dried_ghast_hydration_1_west.png
+ minecraft/textures/block/dried_ghast_hydration_2_bottom.png
+ minecraft/textures/block/dried_ghast_hydration_2_east.png
+ minecraft/textures/block/dried_ghast_hydration_2_north.png
+ minecraft/textures/block/dried_ghast_hydration_2_south.png
+ minecraft/textures/block/dried_ghast_hydration_2_tentacles.png
+ minecraft/textures/block/dried_ghast_hydration_2_top.png
+ minecraft/textures/block/dried_ghast_hydration_2_west.png
+ minecraft/textures/block/dried_ghast_hydration_3_bottom.png
+ minecraft/textures/block/dried_ghast_hydration_3_east.png
+ minecraft/textures/block/dried_ghast_hydration_3_north.png
+ minecraft/textures/block/dried_ghast_hydration_3_south.png
+ minecraft/textures/block/dried_ghast_hydration_3_tentacles.png
+ minecraft/textures/block/dried_ghast_hydration_3_top.png
+ minecraft/textures/block/dried_ghast_hydration_3_west.png
- minecraft/textures/block/mine_crafter_active_inner_top.png
- minecraft/textures/block/mine_crafter_active_inner_top.png.mcmeta
- minecraft/textures/block/mine_crafter_bottom.png
- minecraft/textures/block/mine_crafter_inner_top.png
- minecraft/textures/block/mine_crafter_inner_top.png.mcmeta
- minecraft/textures/block/mine_crafter_side.png
- minecraft/textures/block/mine_crafter_top.png
- minecraft/textures/block/mine_revisitor_active_inner_top.png
- minecraft/textures/block/mine_revisitor_active_inner_top.png.mcmeta
- minecraft/textures/block/mine_revisitor_bottom.png
- minecraft/textures/block/mine_revisitor_inner_top.png
- minecraft/textures/block/mine_revisitor_inner_top.png.mcmeta
- minecraft/textures/block/mine_revisitor_side.png
- minecraft/textures/block/mine_revisitor_top.png
- minecraft/textures/block/mine_travelling_block.png
- minecraft/textures/block/shimmering_door_bottom.png
- minecraft/textures/block/shimmering_door_top.png
- minecraft/textures/block/sky.png
- minecraft/textures/block/trophy_gold.png
- minecraft/textures/block/trophy_mega_spud.png
- minecraft/textures/block/trophy_no_medal.png
- minecraft/textures/entity/angry_ghast/ghast_shooting.png
- minecraft/textures/entity/angry_ghast/ghast.png
+ minecraft/textures/entity/equipment/happy_ghast_body/black_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/blue_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/brown_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/cyan_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/gray_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/green_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/light_blue_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/light_gray_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/lime_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/magenta_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/orange_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/pink_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/purple_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/red_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/white_harness.png
+ minecraft/textures/entity/equipment/happy_ghast_body/yellow_harness.png
+ minecraft/textures/entity/ghast/happy_ghast_baby.png
+ minecraft/textures/entity/ghast/happy_ghast.png
- minecraft/textures/entity/villager/profession/traitor.png
- minecraft/textures/entity/zombie_villager/profession/traitor.png
- minecraft/textures/environment/skynorama/panorama_0.png
- minecraft/textures/environment/skynorama/panorama_1.png
- minecraft/textures/environment/skynorama/panorama_2.png
- minecraft/textures/environment/skynorama/panorama_3.png
- minecraft/textures/environment/skynorama/panorama_4.png
- minecraft/textures/environment/skynorama/panorama_5.png
- minecraft/textures/font/code.png
+ minecraft/textures/gui/advancements/backgrounds/end.png
- minecraft/textures/gui/advancements/backgrounds/feats.png
+ minecraft/textures/gui/advancements/backgrounds/husbandry.png
- minecraft/textures/gui/advancements/backgrounds/mines.png
+ minecraft/textures/gui/advancements/backgrounds/nether.png
- minecraft/textures/gui/advancements/backgrounds/unlocks.png
- minecraft/textures/gui/container/dimension_control.png
- minecraft/textures/gui/container/inventory_3x3.png
- minecraft/textures/gui/container/inventory_no_crafting.png
- minecraft/textures/gui/container/mine_crafter_active.png
- minecraft/textures/gui/container/mine_crafter_boss_active.png
- minecraft/textures/gui/container/mine_crafter_boss.png
- minecraft/textures/gui/container/mine_crafter_donate.png
- minecraft/textures/gui/container/mine_crafter_fail.png
- minecraft/textures/gui/container/mine_crafter_hints.png
- minecraft/textures/gui/container/mine_crafter_won.png
- minecraft/textures/gui/container/mine_crafter.png
- minecraft/textures/gui/door.png
- minecraft/textures/gui/sprites/advancements/box_obtained_active.png
- minecraft/textures/gui/sprites/advancements/box_obtained_active.png.mcmeta
- minecraft/textures/gui/sprites/advancements/box_unobtained_locked.png
- minecraft/textures/gui/sprites/advancements/box_unobtained_locked.png.mcmeta
- minecraft/textures/gui/sprites/advancements/challenge_frame_unobtained_locked.png
- minecraft/textures/gui/sprites/advancements/task_frame_obtained_active.png
- minecraft/textures/gui/sprites/advancements/task_frame_unobtained_locked.png
- minecraft/textures/gui/sprites/container/crafter/all_unlocked.png
- minecraft/textures/gui/sprites/container/slot/level.png
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_down.png
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_down.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_up.png
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_up.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_background.png
+ minecraft/textures/gui/sprites/hud/locator_bar_background.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_player.png
- minecraft/textures/gui/sprites/icon/donate_experience.png
- minecraft/textures/gui/sprites/icon/player_unlocks.png
- minecraft/textures/gui/sprites/unlock_backgrounds/combatant.png
- minecraft/textures/gui/sprites/unlock_backgrounds/combatant.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/crafting.png
- minecraft/textures/gui/sprites/unlock_backgrounds/crafting.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/end.png
- minecraft/textures/gui/sprites/unlock_backgrounds/end.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/exploration.png
- minecraft/textures/gui/sprites/unlock_backgrounds/exploration.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/gatherer.png
- minecraft/textures/gui/sprites/unlock_backgrounds/gatherer.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/mining.png
- minecraft/textures/gui/sprites/unlock_backgrounds/mining.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/pets.png
- minecraft/textures/gui/sprites/unlock_backgrounds/pets.png.mcmeta
- minecraft/textures/gui/sprites/unlock_backgrounds/school_of_hard_knocks.png
- minecraft/textures/gui/sprites/unlock_backgrounds/school_of_hard_knocks.png.mcmeta
- minecraft/textures/gui/sprites/widget/window.png
- minecraft/textures/gui/sprites/widget/window.png.mcmeta
- minecraft/textures/gui/title/edition.png.mcmeta
- minecraft/textures/gui/title/minceraft.png.mcmeta
- minecraft/textures/gui/title/minecraft.png.mcmeta
- minecraft/textures/gui/title/realms.png.mcmeta
- minecraft/textures/item/amplified.png
+ minecraft/textures/item/black_harness.png
+ minecraft/textures/item/blue_harness.png
+ minecraft/textures/item/brown_harness.png
- minecraft/textures/item/cave_exits.png
- minecraft/textures/item/cave_world.png
+ minecraft/textures/item/cyan_harness.png
- minecraft/textures/item/dark_cave_world.png
+ minecraft/textures/item/ender_eye.png
- minecraft/textures/item/exit_eye.png
- minecraft/textures/item/floating_islands_world.png
- minecraft/textures/item/grave_advancement.png
+ minecraft/textures/item/gray_harness.png
+ minecraft/textures/item/green_harness.png
- minecraft/textures/item/grid_world.png
+ minecraft/textures/item/happy_ghast_spawn_egg.png
- minecraft/textures/item/illusioners.png
- minecraft/textures/item/kuiper_world.png
+ minecraft/textures/item/light_blue_harness.png
+ minecraft/textures/item/light_gray_harness.png
+ minecraft/textures/item/lime_harness.png
+ minecraft/textures/item/magenta_harness.png
- minecraft/textures/item/mine_ingredient.png
- minecraft/textures/item/mine.png
- minecraft/textures/item/music_disc_and_action.png
+ minecraft/textures/item/orange_harness.png
- minecraft/textures/item/pets_icon.png
+ minecraft/textures/item/pink_harness.png
+ minecraft/textures/item/purple_harness.png
- minecraft/textures/item/rare_surface_exits.png
+ minecraft/textures/item/red_harness.png
- minecraft/textures/item/shattered_blocks.png
- minecraft/textures/item/shazboots.png
- minecraft/textures/item/shimmering_door.png
- minecraft/textures/item/shimmering_key.png
- minecraft/textures/item/sky_box.png
- minecraft/textures/item/surface_exits.png
- minecraft/textures/item/surface_world.png
- minecraft/textures/item/void_world.png
- minecraft/textures/item/water_mining.png
+ minecraft/textures/item/white_harness.png
+ minecraft/textures/item/yellow_harness.png
- minecraft/textures/misc/map_lost_glint.png
- minecraft/textures/misc/map_lost_glint.png.mcmeta
- minecraft/textures/misc/map_won_glint.png
- minecraft/textures/misc/map_won_glint.png.mcmeta
- minecraft/textures/mob_effect/shazboots.png
- nothingtoseehere/sounds.json
- nothingtoseehere/sounds/and_action/and_action.ogg
- nothingtoseehere/sounds/villager_crowd/crowd_cheer.ogg
- nothingtoseehere/sounds/villager_crowd/crowd_start.ogg
- nothingtoseehere/sounds/villager_crowd/crowd_waiting.ogg
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
- <loud portal sounds>
+ 1% sugar!
+ 10 years of Mining and Crafting!
+ 100% pure!
+ 12 herbs and spices!
+ 12345 is a bad password!
+ 150 bpm for 400000 minutes!
+ 150% hyperbole!
+ 20 GOTO 10!
+ 4815162342 lines of code!
+ 90% bug free!
+ 90210!
- 99% less starch!
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
- And they call it a Mine? A MINE!
+ Any computer is a laptop if you're brave enough!
- As a large language model...
+ As seen on TV!
+ Ask your doctor!
+ Autonomous!
+ Awesome community!
+ Awesome game design right there!
+ Awesome!
+ Aww man!
+ Be anti-racist!
+ Bees, bees, bees, bees!
+ Bekarton guards the gate!
+ Best in class!
+ Big Pointy Teeth!
+ Bigger than a bread box!
+ Black lives matter!
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
- Check out this mine of mine!
+ Child's play!
+ Classy!
- Clearly not made with AI!
+ Closed source!
+ Cloud computing!
+ Cogito ergo sum!
+ Collaborate and listen!
- Comparable with leading brands!
+ Complex cellular automata!
+ Consummate V's!
- Contains collectibles!
+ Contains infinite genders!
+ Contains simulated goats!
+ Conventional!
- Copyright Mojang AB. Do not distribute!
+ Cough or sneeze into your elbow!
+ Cow Tools!
- Craft a Mine and then Mine and Craft!
- Craft mines in Minecraft!
- Craft the Earth! In Minecraft!
- Craftable Mines!
+ Create!
+ Croak team!
+ Cruising streets for gold!
+ Cześć Polsko!
+ Déjà vu!
+ Déjà vu!
- Deleting Overworld!
+ Do it all, everything!
+ Do not distribute!
- Do you Mine?
+ Do you want to join my server?
+ Does barrel rolls!
+ Doesn't avoid double negatives!
+ Doesn't use the U-word!
+ Don't bother with the clones!
+ Don't feed avocados to parrots!
+ Don't feed chocolate to parrots!
+ Don't look directly at the bugs!
+ Don’t touch your face!
+ Don't worry, be happy!
+ doot doot
+ Double buffered!
- Download more RAM!
+ DRR! DRR! DRR!
+ Dungeon!
+ DungeonQuest is unfair!
+ Edit is a name!
+ Educate your friends on anti-racism!
+ Engage!
+ Enhanced!
- Enter The Mine!
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
- Famously unfinished!
+ Fan fiction!
+ Fantasy!
+ Fat free!
+ Feature packed!
+ Finally complete!
+ Finally with ladders!
+ Find your claw!
+ Finger-licking!
+ Flashing letters!
+ Flavor with no seasoning!
+ Flaxkikare!
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
- Has working fletching tables!
+ Hat Fridays!
+ Haunted!
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
- How do I dig for mine?
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
- Infinity 2.0: Now more finite!
+ Information wants to be free!
+ Ingots!
+ Inspirational!
+ Internet enabled!
- Is that... is that a sphere!?
+ It came from space.
+ It swings, it jives!
+ It's a game!
+ It's finished!
+ It's groundbreaking!
+ It's here!
+ Jag känner en bot!
+ Jason! Jason! Jason!
+ Java 16 + 1 + 4 = 21!
+ Javalicious edition
+ Jeb has amazing hair!
+ Joel is neat!
+ Joule is neat too!
+ Jump up, jump up, and get down!
- Just one more Mine
+ Kaaneeeedaaaa!
+ Keyboard compatible!
+ Khaaaaaaaaan!
+ Kick it root down!
+ Kind of dragon free!
+ Kinda like Lemmings!
+ Kiss the sky!
+ l33t!
+ Larger than Earth!
+ Learn about allyship!
+ Legal in Finland!
+ Lennart lennart = new Lennart();
+ Less addictive than TV Tropes!
+ Let our battle's begin!
+ Let's danec!
+ Leveraging synergy!
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
+ Matt Damon!
+ May contain nuts!
+ May contain traces of citrus!
+ Meeting expectations!
+ Menger sponge!
+ Millions of peaches!
- Mine your own business
- Mine, you fools!
- Minecraft À La Carte!
+ Minecraft Java Edition presents: Disgusting Bugs
+ Minecraft!
- Minecraftlike!
+ Minors welcome!
+ Mmmph, mmph!
+ Moderately attractive!
+ Monster infighting!
+ More addictive than lemonade!
+ More Digital!
+ More polygons!
+ More than 500 sold!
+ Music by C418!
+ Music by Lena Raine!
+ My life for Aiur!
+ Never dig down!
+ Nice to meet you!
+ Nooooooooooooo!
+ Not as cool as Spock!
+ Not linear!
+ Not on steam!
+ Now contains 32 random daily cats!
+ Now in 3D!
+ Now on OpenGL 3.2 core profile!
+ Now supports åäö!
+ Now with additional stuff!
+ Now with difficulty!
- Now with even less realism!
+ Now with extra hugs!
- Now with magic!
- Now with many more Mines!
+ Now With Multiplayer!
- Now with sphere-like objects!
+ Now you are thinking with pistons!
+ NP is not in P!
+ Octagonal!
+ Oh man!
+ Oh, ok, Pigmen!
+ OICU812!
+ Omnipotent!
+ One day, somewhere in the future, my work will be quoted!
+ One of a kind!
- Over 3 new items!
- Participation awards!
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
+ Polynomial!
+ Prepare, but don’t hoard!
+ Pretty scary!
+ Pretty!
- Programmer Art without extra packs!
+ Pumpa kungen!
+ Pumpkinhead!
+ Punching wood!
+ Put a little fence around it!
+ Put that cookie down!
+ Rainbow turtle?
+ Random splash!
+ Read more books!
- Reduced quality!
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
- Screens full of excitement!
- Secret Tuesday update!
+ See you next Friday or so!
+ Seecret Friday update!
+ Sensational!
+ Shop for your elders!
+ Should not be played while driving
+ Shriek like a Sculk Shrieker!
+ Singleplayer!
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
- Talent trees!
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
+ The true meaning of covfefe
+ Thematic!
+ There's <<a cat on ,my keyboard!~
+ There's no stopping the Trollmaso
+ This is good for Realms.
+ This is my true form!
+ This message will never appear on the splash screen, isn't that weird?
+ This parrot is no more! It has ceased to be!
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
- Unlock ALL the things!
- Unlockable!
+ Uses LWJGL!
+ Vanilla!
+ Verlet integration!
+ Very fun!
+ Very influential in its circle!
+ Vote for net neutrality!
+ Warning! A huge battleship "STEVE" is approaching fast!
+ Wash your hands!
+ Water bottle!
+ Water proof!
- We joked every other year, but this time we are FOR REAL!
+ Welcome to your Doom!
+ What do you expect?
+ What's the question?
+ What's up, Doc?
+ Where there is not light, there can spider!
+ Who let the frogs out?
+ Who put it there?
+ Whoa, dude!
+ Woah.
+ Woo, 2pp!
+ Woo, facepunch!
+ Woo, reddit!
+ Woo, somethingawful!
+ Woo, tigsource!
+ Woo, worldofminecraft!
- Working as intended!
+ Wow!
+ Yaaay!
+ Yay, puppies for everyone!
+ Yes, sir!
+ You are valid!
+ You are welcome here!
+ You can't explain that!
- You RAM is the limit!
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
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:hex_color
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
- net.minecraft.WorldVersion$1
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
- XXX.advancements.critereon.DataComponentMatchers
+ XXX.advancements.critereon.DataComponentMatchers$Builder
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
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
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
+ XXX.advancements.critereon.MinMaxBounds$1
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Doubles
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$Builder
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.MovementPredicate
- XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PickedUpItemTrigger
- XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.PlayerPredicate$StatMatcher
+ XXX.advancements.critereon.PlayerTrigger
- XXX.advancements.critereon.PlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.RaiderPredicate
- XXX.advancements.critereon.RecipeCraftedTrigger
+ XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SheepPredicate
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
+ XXX.advancements.critereon.SingleComponentItemPredicate
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.SlimePredicate
+ XXX.advancements.critereon.SlotsPredicate
- XXX.advancements.critereon.StartRidingTrigger
+ XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TagPredicate
+ XXX.advancements.critereon.TameAnimalTrigger
- XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UnlockPredicate
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedExitEyeTrigger
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaMineAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
+ XXX.advancements.packs.VanillaUnlockAdvancements
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.Attribute$Sentiment
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.AttributeReceiver
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
- XXX.ai.goal.TemptGoal$ForNonPathfinders
- XXX.ai.sensing.AdultSensorAnyType
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
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$JukeboxListener
+ XXX.animal.allay.Allay$VibrationUser
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.armadillo.Armadillo
+ XXX.animal.armadillo.Armadillo$1
- XXX.animal.armadillo.Armadillo$ArmadilloState
+ XXX.animal.armadillo.Armadillo$ArmadilloState$1
- XXX.animal.armadillo.Armadillo$ArmadilloState$2
+ XXX.animal.armadillo.Armadillo$ArmadilloState$3
- XXX.animal.armadillo.Armadillo$ArmadilloState$4
+ XXX.animal.armadillo.ArmadilloAi
- XXX.animal.armadillo.ArmadilloAi$1
+ XXX.animal.armadillo.ArmadilloAi$ArmadilloBallUp
- XXX.animal.armadillo.ArmadilloAi$ArmadilloPanic
+ XXX.animal.armadillo.package-info
- XXX.animal.axolotl.Axolotl
+ XXX.animal.axolotl.Axolotl$AnimationState
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
+ XXX.animal.frog.FrogVariant
- XXX.animal.frog.FrogVariants
+ XXX.animal.frog.package-info
+ XXX.animal.frog.ShootTongue
- XXX.animal.frog.ShootTongue$State
+ XXX.animal.frog.Tadpole
- XXX.animal.frog.TadpoleAi
- XXX.animal.goat.Goat
+ XXX.animal.goat.GoatAi
- XXX.animal.goat.package-info
+ XXX.animal.horse.AbstractChestedHorse
- XXX.animal.horse.AbstractChestedHorse$1
+ XXX.animal.horse.AbstractHorse
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Llama$Variant
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
- XXX.animal.sheep.package-info
- XXX.animal.sheep.Sheep
+ XXX.animal.sheep.SheepColorSpawnRules
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
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
+ XXX.animal.wolf.package-info
- XXX.animal.wolf.Wolf
+ XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
- XXX.animal.wolf.Wolf$WolfPackData
+ XXX.animal.wolf.WolfSoundVariant
- XXX.animal.wolf.WolfSoundVariants
+ XXX.animal.wolf.WolfSoundVariants$SoundSet
- XXX.animal.wolf.WolfVariant
+ XXX.animal.wolf.WolfVariant$AssetInfo
- XXX.animal.wolf.WolfVariants
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
+ XXX.arguments.item.ComponentPredicateParser
- XXX.arguments.item.ComponentPredicateParser$ComponentLookupRule
+ XXX.arguments.item.ComponentPredicateParser$Context
- XXX.arguments.item.ComponentPredicateParser$ElementLookupRule
+ XXX.arguments.item.ComponentPredicateParser$PredicateLookupRule
- XXX.arguments.item.ComponentPredicateParser$TagLookupRule
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemParser$1
+ XXX.arguments.item.ItemParser$ItemResult
- XXX.arguments.item.ItemParser$State
+ XXX.arguments.item.ItemParser$SuggestionsVisitor
- XXX.arguments.item.ItemParser$Visitor
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ComponentWrapper
+ XXX.arguments.item.ItemPredicateArgument$Context
- XXX.arguments.item.ItemPredicateArgument$PredicateWrapper
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
+ XXX.arguments.selector.SelectorPattern
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPatternLayers
+ XXX.block.entity.BannerPatternLayers$Builder
- XXX.block.entity.BannerPatternLayers$Layer
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBeamOwner
- XXX.block.entity.BeaconBeamOwner$Section
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BeehiveBlockEntity$Occupant
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntity$1
+ XXX.block.entity.BlockEntity$ComponentHelper
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BoundingBoxRenderable
- XXX.block.entity.BoundingBoxRenderable$Mode
+ XXX.block.entity.BoundingBoxRenderable$RenderableBox
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.CrafterBlockEntity
+ XXX.block.entity.CrafterBlockEntity$1
- XXX.block.entity.CreakingHeartBlockEntity
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
- XXX.block.entity.DecoratedPotPattern
+ XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantingTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FuelValues
- XXX.block.entity.FuelValues$Builder
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
+ XXX.block.entity.MineTravellingBlockEntity
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chunk.status.ChunkDependencies
- XXX.chunk.status.ChunkPyramid
+ XXX.chunk.status.ChunkPyramid$Builder
- XXX.chunk.status.ChunkStatus
+ XXX.chunk.status.ChunkStatusTask
- XXX.chunk.status.ChunkStatusTasks
+ XXX.chunk.status.ChunkStep
- XXX.chunk.status.ChunkStep$Builder
+ XXX.chunk.status.ChunkType
+ XXX.chunk.status.package-info
- XXX.chunk.status.WorldGenContext
- XXX.chunk.storage.ChunkIOErrorReporter
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.IOWorker$ThrowingSupplier
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
+ XXX.chunk.storage.SectionStorage$PackedChunk
- XXX.chunk.storage.SerializableChunkData
+ XXX.chunk.storage.SerializableChunkData$ChunkReadException
- XXX.chunk.storage.SerializableChunkData$SectionData
+ XXX.chunk.storage.SimpleRegionStorage
+ XXX.commands.arguments.AngleArgument
- XXX.commands.arguments.AngleArgument$SingleAngle
+ XXX.commands.arguments.ArgumentSignatures
- XXX.commands.arguments.ArgumentSignatures$Entry
+ XXX.commands.arguments.ArgumentSignatures$Signer
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Info
- XXX.commands.arguments.EntityArgument$Info$Template
+ XXX.commands.arguments.GameModeArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.HeightmapTypeArgument
- XXX.commands.arguments.HexColorArgument
+ XXX.commands.arguments.package-info
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
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.component.predicates.AttributeModifiersPredicate
+ XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
- XXX.component.predicates.BundlePredicate
+ XXX.component.predicates.ContainerPredicate
- XXX.component.predicates.CustomDataPredicate
+ XXX.component.predicates.DamagePredicate
- XXX.component.predicates.DataComponentPredicate
+ XXX.component.predicates.DataComponentPredicate$Single
- XXX.component.predicates.DataComponentPredicate$Type
+ XXX.component.predicates.DataComponentPredicates
- XXX.component.predicates.EnchantmentsPredicate
+ XXX.component.predicates.EnchantmentsPredicate$Enchantments
- XXX.component.predicates.EnchantmentsPredicate$StoredEnchantments
+ XXX.component.predicates.FireworkExplosionPredicate
- XXX.component.predicates.FireworkExplosionPredicate$FireworkPredicate
+ XXX.component.predicates.FireworksPredicate
- XXX.component.predicates.JukeboxPlayablePredicate
+ XXX.component.predicates.package-info
+ XXX.component.predicates.PotionsPredicate
- XXX.component.predicates.TrimPredicate
+ XXX.component.predicates.WritableBookPredicate
- XXX.component.predicates.WritableBookPredicate$PagePredicate
+ XXX.component.predicates.WrittenBookPredicate
- XXX.component.predicates.WrittenBookPredicate$PagePredicate
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.CauldronInteraction$InteractionMap
+ XXX.core.cauldron.package-info
- XXX.core.component.DataComponentExactPredicate
+ XXX.core.component.DataComponentExactPredicate$Builder
- XXX.core.component.DataComponentGetter
+ XXX.core.component.DataComponentHolder
- XXX.core.component.DataComponentMap
+ XXX.core.component.DataComponentMap$1
- XXX.core.component.DataComponentMap$2
+ XXX.core.component.DataComponentMap$3
- XXX.core.component.DataComponentMap$Builder
+ XXX.core.component.DataComponentMap$Builder$SimpleMap
- XXX.core.component.DataComponentPatch
+ XXX.core.component.DataComponentPatch$1
- XXX.core.component.DataComponentPatch$2
+ XXX.core.component.DataComponentPatch$3
- XXX.core.component.DataComponentPatch$Builder
+ XXX.core.component.DataComponentPatch$CodecGetter
- XXX.core.component.DataComponentPatch$PatchKey
+ XXX.core.component.DataComponentPatch$SplitResult
+ XXX.core.component.DataComponents
- XXX.core.component.DataComponentType
+ XXX.core.component.DataComponentType$Builder
- XXX.core.component.DataComponentType$Builder$SimpleType
+ XXX.core.component.package-info
- XXX.core.component.PatchedDataComponentMap
+ XXX.core.component.TypedDataComponent
- XXX.core.component.TypedDataComponent$1
- XXX.core.dispenser.BlockSource
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
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.EquipmentDispenseItemBehavior
- XXX.core.dispenser.MinecartDispenseItemBehavior
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ProjectileDispenseBehavior
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.ColorParticleOption
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.ItemParticleOption
+ XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.ScalableParticleOptionsBase
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.ShriekParticleOption
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.TrailParticleOption
- XXX.core.particles.VibrationParticleOption
- XXX.core.registries.BuiltInRegistries
+ XXX.core.registries.BuiltInRegistries$RegistryBootstrap
+ XXX.core.registries.package-info
- XXX.core.registries.Registries
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
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
+ XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeBuilder$1
+ XXX.data.recipes.RecipeCategory
- XXX.data.recipes.RecipeOutput
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.RecipeProvider$FamilyRecipeProvider
+ XXX.data.recipes.RecipeProvider$Runner
- XXX.data.recipes.RecipeProvider$Runner$1
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SmithingTransformRecipeBuilder
- XXX.data.recipes.SmithingTrimRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.TransmuteRecipeBuilder
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.RegistryPatchGenerator
- XXX.data.registries.TradeRebalanceRegistries
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
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EnchantmentTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1CombinedData
- XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.tags.TagsProvider$TagLookup
- XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaEnchantmentTagsProvider
+ XXX.data.tags.VanillaItemTagsProvider
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
+ XXX.data.worldgen.BootstrapContext
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.DimensionTypes
+ XXX.data.worldgen.MineExitPools
- XXX.datafix.schemas.V3439_1
+ XXX.datafix.schemas.V3448
- XXX.datafix.schemas.V3682
+ XXX.datafix.schemas.V3683
- XXX.datafix.schemas.V3685
+ XXX.datafix.schemas.V3689
- XXX.datafix.schemas.V3799
+ XXX.datafix.schemas.V3807
- XXX.datafix.schemas.V3808
+ XXX.datafix.schemas.V3808_1
- XXX.datafix.schemas.V3808_2
+ XXX.datafix.schemas.V3813
- XXX.datafix.schemas.V3816
+ XXX.datafix.schemas.V3818
- XXX.datafix.schemas.V3818_3
+ XXX.datafix.schemas.V3818_4
- XXX.datafix.schemas.V3818_5
+ XXX.datafix.schemas.V3825
- XXX.datafix.schemas.V3938
+ XXX.datafix.schemas.V4059
- XXX.datafix.schemas.V4067
+ XXX.datafix.schemas.V4070
- XXX.datafix.schemas.V4071
+ XXX.datafix.schemas.V4290
- XXX.datafix.schemas.V4292
+ XXX.datafix.schemas.V4300
- XXX.datafix.schemas.V4301
+ XXX.datafix.schemas.V4302
- XXX.datafix.schemas.V4306
+ XXX.datafix.schemas.V4307
- XXX.datafix.schemas.V4312
+ XXX.datafix.schemas.V4317
- XXX.datafix.schemas.V4421
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
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
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractCow
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.AgeableWaterCreature
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
- XXX.entity.animal.Bee$ValidateFlowerGoal
+ XXX.entity.animal.Bee$ValidateHiveGoal
- XXX.entity.animal.Bucketable
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.CatVariant
- XXX.entity.animal.CatVariants
+ XXX.entity.animal.Chicken
- XXX.entity.animal.ChickenVariant
+ XXX.entity.animal.ChickenVariant$ModelType
- XXX.entity.animal.ChickenVariants
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.CowVariant
- XXX.entity.animal.CowVariant$ModelType
+ XXX.entity.animal.CowVariants
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
- XXX.entity.animal.HappyGhast
- XXX.entity.animal.HappyGhast$HappyGhastBodyRotationControl
- XXX.entity.animal.HappyGhast$HappyGhastLookControl
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$Variant
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
+ XXX.entity.animal.package-info
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
- XXX.entity.animal.PigVariant
+ XXX.entity.animal.PigVariant$ModelType
- XXX.entity.animal.PigVariants
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
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
- XXX.entity.animal.Salmon$Variant
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TemperatureVariants
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
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.BlockAttachedEntity
+ XXX.entity.decoration.GlowItemFrame
- XXX.entity.decoration.HangingEntity
+ XXX.entity.decoration.HangingEntity$1
- XXX.entity.decoration.ItemFrame
+ XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
+ XXX.entity.decoration.PaintingVariant
- XXX.entity.decoration.PaintingVariants
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
+ XXX.entity.item.PrimedTnt$1
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.AngryGhast$AngryGhastLookGoal
+ XXX.entity.monster.AngryGhast$AngryGhastShootFireballGoal
+ XXX.entity.pets.PetArmadillo
+ XXX.entity.pets.PetArmadillo$2
+ XXX.entity.pets.PetAxolotl$AnimationState
+ XXX.entity.pets.PetAxolotl$AxolotlLookControl
+ XXX.entity.pets.PetBee
+ XXX.entity.pets.PetBee$BaseBeeGoal
+ XXX.entity.pets.PetBee$BeeHurtByOtherGoal
+ XXX.entity.pets.PetCat
+ XXX.entity.pets.PetCow
+ XXX.entity.pets.PetFox
+ XXX.entity.pets.PetFox$FoxLookControl
+ XXX.entity.pets.PetFrog
+ XXX.entity.pets.PetFrog$FrogNodeEvaluator
+ XXX.entity.pets.PetMushroomCow
+ XXX.entity.pets.PetPolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.pets.PetPolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.pets.PetSlime$SlimeFloatGoal
+ XXX.entity.pets.PetSlime$SlimeMoveControl
+ XXX.entity.pets.PetTurtle$PetTurtlePathNavigation
+ XXX.entity.pets.PetTurtle$TurtleRandomStrollGoal
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Input
- XXX.entity.player.Input$1
+ XXX.entity.player.Inventory
+ XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerEquipment
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
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
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
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
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
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.variant.BiomeCheck
- XXX.entity.variant.ModelAndTexture
+ XXX.entity.variant.MoonBrightnessCheck
- XXX.entity.variant.package-info
- XXX.entity.variant.PriorityProvider
+ XXX.entity.variant.PriorityProvider$Selector
- XXX.entity.variant.PriorityProvider$SelectorCondition
+ XXX.entity.variant.PriorityProvider$UnpackedEntry
- XXX.entity.variant.SpawnCondition
+ XXX.entity.variant.SpawnConditions
- XXX.entity.variant.SpawnContext
+ XXX.entity.variant.SpawnPrioritySelectors
- XXX.entity.variant.StructureCheck
+ XXX.entity.variant.VariantUtils
+ XXX.entity.vehicle.AbstractBoat
- XXX.entity.vehicle.AbstractBoat$Status
+ XXX.entity.vehicle.AbstractChestBoat
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestRaft
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartBehavior
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
+ XXX.entity.vehicle.NewMinecartBehavior$1
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
+ XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
+ XXX.entity.vehicle.OldMinecartBehavior
- XXX.entity.vehicle.OldMinecartBehavior$1
+ XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.Raft
- XXX.entity.vehicle.VehicleEntity
+ XXX.equipment.trim.ArmorTrim
- XXX.equipment.trim.MaterialAssetGroup
+ XXX.equipment.trim.MaterialAssetGroup$AssetInfo
- XXX.equipment.trim.package-info
- XXX.equipment.trim.TrimMaterial
+ XXX.equipment.trim.TrimMaterials
- XXX.equipment.trim.TrimPattern
+ XXX.equipment.trim.TrimPatterns
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
+ XXX.feature.configurations.FallenTreeConfiguration
- XXX.feature.configurations.FallenTreeConfiguration$FallenTreeConfigurationBuilder
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
+ XXX.feature.configurations.PlaceTemplateConfiguration
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Builder
+ XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.PotionContents
+ XXX.item.alchemy.Potions
+ XXX.item.component.Bees
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BlocksAttacks
- XXX.item.component.BlocksAttacks$DamageReduction
+ XXX.item.component.BlocksAttacks$ItemDamageFunction
- XXX.item.component.BookContent
+ XXX.item.component.BundleContents
- XXX.item.component.BundleContents$Mutable
+ XXX.item.component.ChargedProjectiles
- XXX.item.component.Consumable
+ XXX.item.component.Consumable$Builder
- XXX.item.component.Consumable$OverrideConsumeSound
+ XXX.item.component.ConsumableListener
- XXX.item.component.Consumables
+ XXX.item.component.CustomData
- XXX.item.component.CustomModelData
+ XXX.item.component.DamageResistant
- XXX.item.component.DeathProtection
+ XXX.item.component.DebugStickState
- XXX.item.component.DyedItemColor
+ XXX.item.component.FireworkExplosion
- XXX.item.component.FireworkExplosion$Shape
+ XXX.item.component.Fireworks
- XXX.item.component.InstrumentComponent
+ XXX.item.component.ItemAttributeModifiers
- XXX.item.component.ItemAttributeModifiers$1
+ XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$Type
+ XXX.item.component.ItemExchangeValue
- XXX.item.component.ItemLore
+ XXX.item.component.LodestoneTracker
- XXX.item.component.MapDecorations
+ XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapItemColor
+ XXX.item.component.MapPostProcessing
- XXX.item.component.OminousBottleAmplifier
- XXX.item.component.package-info
+ XXX.item.component.ProvidesTrimMaterial
- XXX.item.component.ResolvableProfile
+ XXX.item.component.RoomerinoComponentino
+ XXX.item.component.WorldModifiers
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
+ XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
+ XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.consume_effects.TeleportRandomlyConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.AbstractCookingRecipe$Serializer
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BlastingRecipe$1
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CraftingRecipe$1
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.CustomRecipe$Serializer
+ XXX.item.crafting.CustomRecipe$Serializer$Factory
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.ExtendedRecipeBookCategory
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeAccess
+ XXX.item.crafting.RecipeBookCategories
- XXX.item.crafting.RecipeBookCategory
+ XXX.item.crafting.RecipeCache
- XXX.item.crafting.RecipeCache$Entry
+ XXX.item.crafting.RecipeHolder
- XXX.item.crafting.RecipeInput
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeManager$IngredientCollector
+ XXX.item.crafting.RecipeManager$IngredientExtractor
- XXX.item.crafting.RecipeManager$ServerDisplayInfo
+ XXX.item.crafting.RecipeMap
- XXX.item.crafting.RecipePropertySet
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.SelectableRecipe
- XXX.item.crafting.SelectableRecipe$SingleInputEntry
+ XXX.item.crafting.SelectableRecipe$SingleInputSet
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleRecipeInput
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmeltingRecipe$1
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingRecipeInput
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.TippedArrowRecipe
- XXX.item.crafting.TransmuteRecipe
+ XXX.item.crafting.TransmuteRecipe$Serializer
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
- XXX.item.equipment.AllowedEntitiesProvider
+ XXX.item.equipment.ArmorMaterial
- XXX.item.equipment.ArmorMaterials
+ XXX.item.equipment.ArmorType
- XXX.item.equipment.EquipmentAsset
+ XXX.item.equipment.EquipmentAssets
- XXX.item.equipment.Equippable
+ XXX.item.equipment.Equippable$Builder
- XXX.item.equipment.package-info
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.BiomeBuilder
- XXX.level.biome.BiomeGenerationSettings
+ XXX.level.biome.BiomeGenerationSettings$Builder
- XXX.level.biome.BiomeGenerationSettings$PlainBuilder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeModificationBuilder
- XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSpecialEffects$ExitType
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ XXX.level.biome.CheckerboardColumnBiomeSource
- XXX.level.biome.Climate
+ XXX.level.biome.Climate$DistanceMetric
- XXX.level.biome.Climate$Parameter
+ XXX.level.biome.Climate$ParameterList
- XXX.level.biome.Climate$ParameterPoint
+ XXX.level.biome.Climate$RTree
- XXX.level.biome.Climate$RTree$Leaf
+ XXX.level.biome.Climate$RTree$Node
- XXX.level.biome.Climate$RTree$SubTree
+ XXX.level.biome.Climate$Sampler
- XXX.level.biome.Climate$SpawnFinder
+ XXX.level.biome.Climate$SpawnFinder$Result
- XXX.level.biome.Climate$TargetPoint
+ XXX.level.biome.ClimateSettings
+ XXX.level.biome.FeatureSorter
- XXX.level.biome.FeatureSorter$1FeatureData
+ XXX.level.biome.FeatureSorter$StepFeatureData
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSourceParameterList
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
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
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.MineRevisitorBlock
+ XXX.level.block.Mirror
+ XXX.level.block.MobTrophyBlock$Grade
- XXX.level.block.MossyCarpetBlock
+ XXX.level.block.MossyCarpetBlock$1
- XXX.level.block.MudBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MultifaceSpreadeableBlock
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
- XXX.level.block.PipeBlock
+ XXX.level.block.PitcherCropBlock
- XXX.level.block.PitcherCropBlock$1
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$1
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.Portal
- XXX.level.block.Portal$Transition
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
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
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
+ XXX.level.block.SegmentableBlock
+ XXX.level.block.TerracottaBlock
- XXX.level.block.TestBlock
+ XXX.level.block.TestInstanceBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TintedParticleLeavesBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TorchflowerCropBlock
+ XXX.level.block.TransparentBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TrialSpawnerBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TrophyBlock
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.UntintedParticleLeavesBlock
+ XXX.level.block.VaultBlock
- XXX.level.block.VegetationBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallHangingSignBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WaterloggedTransparentBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperBulbBlock
+ XXX.level.block.WeatheringCopperDoorBlock
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperGrateBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WeatheringCopperTrapDoorBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunk$UnsavedListener
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
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionSpecialEffects
+ XXX.level.dimension.DimensionSpecialEffects$CubeSky
+ XXX.level.dimension.DimensionSpecialEffects$FogScaler
+ XXX.level.dimension.DimensionSpecialEffects$FogScaler$2
+ XXX.level.dimension.DimensionSpecialEffects$OverworldSky
+ XXX.level.dimension.DimensionSpecialEffects$Sky
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
- XXX.level.entity.UniquelyIdentifyable
+ XXX.level.entity.UUIDLookup
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
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.HubLevelSource
+ XXX.level.levelgen.NoiseGeneratorSettings$Builder
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
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
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.ChunkSkyLightSources
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$SectionState
+ XXX.level.lighting.LayerLightSectionStorage$SectionType
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEngine
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.FlowingFluid$BlockStatePairKey
+ XXX.level.material.FlowingFluid$SpreadContext
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.mines.Battle$Builder
+ XXX.level.mines.Battle$SpawnGroup$Builder
+ XXX.level.mines.Battle$SpawnStrategy$Builder
+ XXX.level.mines.Battle$Wave
+ XXX.level.mines.CustomIcons
+ XXX.level.mines.MineEvent
+ XXX.level.mines.MineEventData
+ XXX.level.mines.RaidEvent
+ XXX.level.mines.SpecialMine
+ XXX.level.mines.SpecialMines
+ XXX.level.mines.WorldEffect
+ XXX.level.mines.WorldEffectComponent
+ XXX.level.mines.WorldEffects
+ XXX.level.mines.WorldGenBuilder$ChunkGeneratorGenerator
+ XXX.level.mines.WorldGenBuilder$Processor
+ XXX.level.mines.WorldGenEffect$AddBiome
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.BlendingData$Packed
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
- XXX.levelgen.blockpredicates.package-info
- XXX.levelgen.blockpredicates.ReplaceablePredicate
+ XXX.levelgen.blockpredicates.SolidPredicate
- XXX.levelgen.blockpredicates.StateTestingPredicate
+ XXX.levelgen.blockpredicates.TrueBlockPredicate
- XXX.levelgen.blockpredicates.UnobstructedPredicate
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
- XXX.levelgen.feature.EndPlatformFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FallenTreeFeature
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
+ XXX.levelgen.feature.PlaceTemplateFeature
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
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.packs.package-info
+ XXX.loot.packs.VanillaHubRewardLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
+ XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CacheableFunction
- XXX.minecraft.commands.CommandBuildContext
+ XXX.minecraft.commands.CommandBuildContext$1
- XXX.minecraft.commands.CommandResultCallback
+ XXX.minecraft.commands.CommandResultCallback$1
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
+ XXX.minecraft.commands.ExecutionCommandSource
- XXX.minecraft.commands.FunctionInstantiationException
- XXX.minecraft.commands.package-info
+ XXX.minecraft.commands.ParserUtils
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockBox
+ XXX.minecraft.core.BlockBox$1
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$6
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockPos$TraversalNodeStatus
- XXX.minecraft.core.ClientAsset
+ XXX.minecraft.core.Cloner
- XXX.minecraft.core.Cloner$Factory
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedMappedRegistry
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
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
- XXX.minecraft.core.HolderLookup$Provider
+ XXX.minecraft.core.HolderLookup$Provider$1
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
+ XXX.minecraft.core.MappedRegistry$3
- XXX.minecraft.core.MappedRegistry$TagSet
+ XXX.minecraft.core.MappedRegistry$TagSet$1
- XXX.minecraft.core.MappedRegistry$TagSet$2
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.RegistrationInfo
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Registry$1
+ XXX.minecraft.core.Registry$PendingTags
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
- XXX.minecraft.data.HashCache$1
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.HashCache$ProviderCacheBuilder
- XXX.minecraft.data.HashCache$UpdateFunction
+ XXX.minecraft.data.HashCache$UpdateResult
- XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.network.package-info
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipeHelper
- XXX.minecraft.recipebook.PlaceRecipeHelper$Output
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe$CraftingMenuAccess
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.references.package-info
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.DelegatingOps$DelegateListBuilder
+ XXX.minecraft.resources.DelegatingOps$DelegateRecordBuilder
- XXX.minecraft.resources.DependantName
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
+ XXX.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$HolderLookupAdapter
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
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
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.MinecraftServer$WorldReloader
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$Data
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerRegistries
+ XXX.minecraft.server.ReloadableServerRegistries$Holder
- XXX.minecraft.server.ReloadableServerRegistries$LoadResult
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerInfo
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerLinks
+ XXX.minecraft.server.ServerLinks$Entry
- XXX.minecraft.server.ServerLinks$KnownLinkType
+ XXX.minecraft.server.ServerLinks$UntrustedEntry
+ XXX.minecraft.server.ServerPlayerUnlocks$Data
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TheGame
+ XXX.minecraft.server.TheGame$ReloadableResources
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
+ XXX.minecraft.world.MineData$MineState
- XXX.network.codec.ByteBufCodecs$33
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$DontDecorateException
- XXX.network.codec.IdDispatchCodec$Entry
- XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
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
- XXX.network.protocol.CodecModifier
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketType
- XXX.network.protocol.PacketUtils
+ XXX.network.protocol.ProtocolCodecBuilder
- XXX.network.protocol.ProtocolInfoBuilder
+ XXX.network.protocol.ProtocolInfoBuilder$1
- XXX.network.protocol.ProtocolInfoBuilder$2
+ XXX.network.protocol.ProtocolInfoBuilder$3
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
- XXX.network.protocol.SimpleUnboundProtocol
+ XXX.network.protocol.UnboundProtocol
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
- XXX.packs.metadata.MetadataSectionType
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
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
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
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
+ XXX.protocol.configuration.ConfigurationPacketTypes
- XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
+ XXX.protocol.configuration.ServerConfigurationPacketListener
- XXX.protocol.cookie.ClientboundCookieRequestPacket
+ XXX.protocol.cookie.ClientCookiePacketListener
+ XXX.protocol.cookie.CookiePacketTypes
- XXX.protocol.cookie.package-info
+ XXX.protocol.cookie.ServerboundCookieResponsePacket
- XXX.protocol.cookie.ServerCookiePacketListener
- XXX.protocol.game.ClientboundAddEntityPacket
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
+ XXX.protocol.game.ClientboundChangeDimensionTypePacket
+ XXX.protocol.game.ClientboundOpenDoorPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenWindowPacket
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
+ XXX.protocol.game.ClientboundPlayerRotationPacket
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
+ XXX.protocol.game.ClientboundRecipeBookRemovePacket
- XXX.protocol.game.ClientboundRecipeBookSettingsPacket
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
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetCursorItemPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetHeldSlotPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerInventoryPacket
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
+ XXX.protocol.game.ClientboundTestInstanceBlockStatus
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateUnlockedEffectsPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerDonateExperiencePacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectBundleItemPacket
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSetTestBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntent
- XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.HandshakePacketTypes
- XXX.protocol.handshake.HandshakeProtocols
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientboundLoginFinishedPacket
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
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$Runner
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$Modifier
- XXX.selector.options.EntitySelectorOptions$Option
+ XXX.selector.options.package-info
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvent$Packed
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
+ XXX.server.commands.CloneCommands$CloneBlockEntityInfo
- XXX.server.commands.CloneCommands$CloneBlockInfo
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
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$1UpdatedPosition
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LookAt
- XXX.server.commands.LookAt$LookAtEntity
+ XXX.server.commands.LookAt$LookAtPosition
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RandomCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ReturnCommand
- XXX.server.commands.ReturnCommand$ReturnFailCustomExecutor
+ XXX.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
- XXX.server.commands.ReturnCommand$ReturnValueCustomExecutor
+ XXX.server.commands.RideCommand
+ XXX.server.commands.UnlockCommand
- XXX.server.commands.VersionCommand
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WaypointCommand
+ XXX.server.level.DimensionGenerator
+ XXX.server.level.DimensionGenerator$FakeLevelStem
+ XXX.server.network.ServerHibernateConfigPacketListenerImpl
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
+ XXX.server.players.PlayerUnlock
+ XXX.server.players.PlayerUnlock$UnlockVisibility
- XXX.server.waypoints.ServerWaypointManager
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.StructureTemplateManager$SourceType
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
+ XXX.warden.Stages.StageFour
+ XXX.warden.Stages.StageOne
+ XXX.warden.Stages.StageTwo
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.InsideBlockEffectApplier
- XXX.world.entity.InsideBlockEffectApplier$1
+ XXX.world.entity.InsideBlockEffectApplier$StepBasedCollector
- XXX.world.entity.InsideBlockEffectType
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
+ XXX.world.entity.InterpolationHandler
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
- XXX.world.entity.Mob$2
+ XXX.world.entity.MobCategory
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OminousItemSpawner
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.PortalProcessor
- XXX.world.entity.Pose
+ XXX.world.entity.PositionMoveRotation
- XXX.world.entity.Relative
+ XXX.world.entity.ReputationEventHandler
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
+ XXX.world.inventory.AbstractCraftingMenu$2
+ XXX.world.inventory.AbstractFurnaceMenu$2
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$1
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
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DimensionControlMenu
+ XXX.world.inventory.DimensionControlMenu$2
+ XXX.world.inventory.DoorMenu
+ XXX.world.inventory.DoorMenu$FieldType
+ XXX.world.inventory.DoorMenu$PlacementInfo
+ XXX.world.inventory.GhettoSpline$Entry
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenu$4
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
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
+ XXX.world.inventory.MineCraftingDrawerSlot
+ XXX.world.inventory.MineCraftingMenu
+ XXX.world.inventory.MineCraftingSlot
- XXX.world.inventory.package-info
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.RemoteSlot
- XXX.world.inventory.RemoteSlot$1
+ XXX.world.inventory.RemoteSlot$Synchronized
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
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.BundleItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CreativeModeTab
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
+ XXX.world.item.CrossbowItem$ChargeType
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireworkRocketItem
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
+ XXX.world.item.package-info
+ XXX.world.item.ShimmeringKeyItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.TeleportationWandItem
+ XXX.world.item.WindWandItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.BlockGetter$BlockStepVisitor
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ChunkPos$2
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorMapColorUtil
- XXX.world.level.ColorResolver
+ XXX.world.level.CommonLevelAccessor
- XXX.world.level.CustomSpawner
+ XXX.world.level.DataPackConfig
- XXX.world.level.DryFoliageColor
+ XXX.world.level.EmptyBlockAndTintGetter
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
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
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ScheduledTickAccess
- XXX.world.level.ServerExplosion
+ XXX.world.level.ServerExplosion$StackCollector
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SignalGetter
- XXX.world.level.SimpleExplosionDamageCalculator
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.Spawner
- XXX.world.level.StructureManager
+ XXX.world.level.TicketStorage
- XXX.world.level.TicketStorage$ChunkUpdated
+ XXX.world.level.UnlockCondition
+ XXX.world.level.UnlockCondition$10
+ XXX.world.level.UnlockCondition$12
+ XXX.world.level.UnlockCondition$14
+ XXX.world.level.UnlockCondition$16
+ XXX.world.level.UnlockCondition$18
+ XXX.world.level.UnlockCondition$2
+ XXX.world.level.UnlockCondition$3
+ XXX.world.level.UnlockCondition$5
+ XXX.world.level.UnlockCondition$7
+ XXX.world.level.UnlockCondition$9
- XXX.world.waypoints.TrackedWaypoint
- XXX.world.waypoints.TrackedWaypoint$ChunkWaypoint
- XXX.world.waypoints.TrackedWaypoint$Projector
- XXX.world.waypoints.TrackedWaypoint$Vec3iWaypoint
- XXX.world.waypoints.Waypoint
- XXX.world.waypoints.Waypoint$Icon$Fade
- XXX.world.waypoints.WaypointTransmitter
- XXX.world.waypoints.WaypointTransmitter$ChunkConnection
- XXX.world.waypoints.WaypointTransmitter$EntityAzimuthConnection
- XXX.world.waypoints.WaypointTransmitter$EntityChunkConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.DetectedVersion +2M -8M | -8P
```
```
net.minecraft.SharedConstants +1P -1P
```
```
XXX.minecraft.advancements.CriteriaTriggers +1P -10P
```
```
XXX.minecraft.advancements.DisplayInfo +1M -2M | -1P
```
```
XXX.loot.packs.VanillaBlockLoot +25M -27M
```
```
XXX.worldgen.placement.MiscOverworldPlacements -2P
```
```
XXX.worldgen.placement.OrePlacements -2P
```
```
XXX.gametest.framework.GameTestServer$1 +1M -1M
```
```
XXX.network.chat.Style$Serializer +1M -3M
```
```
XXX.protocol.game.GamePacketTypes +2P -9P
```
```
XXX.protocol.game.ServerGamePacketListener -3P
```
```
XXX.server.dedicated.DedicatedPlayerList +3M -1M | -1P
```
```
XXX.server.dedicated.ServerWatchdog +1M -1M | +1P -2P
```
```
XXX.server.level.ServerLevel +25M -83M | +2P -11P
```
```
XXX.server.level.WorldGenRegion +1M
```
```
XXX.server.network.ServerConfigurationPacketListenerImpl +2M -3M
```
```
XXX.server.network.ServerGamePacketListenerImpl +3M -7M
```
```
XXX.server.network.ServerHandshakePacketListenerImpl -1P
```
```
XXX.server.network.ServerLoginPacketListenerImpl +2M -2M | +1P -1P
```
```
XXX.server.players.PlayerList +7M -9M | +2P -2P
```
```
XXX.server.rcon.RconConsoleSource +1M -1M
```
```
XXX.minecraft.tags.BlockTags +2P -1P
```
```
XXX.minecraft.tags.ItemTags +3P -4P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.datafix.fixes.ItemRemoveBlockEntityTagFix +4M -2M | +1P -1P
```
```
XXX.util.debugchart.RemoteSampleLogger -3M
```
```
XXX.util.random.WeightedList$Builder -1M
```
```
XXX.util.worldupdate.WorldUpgrader -1P
```
```
XXX.minecraft.world.Container -1M
```
```
XXX.minecraft.world.MenuProvider -1M
```
```
XXX.world.damagesource.DamageSources -1M
```
```
XXX.world.damagesource.DamageTypes -1P
```
```
XXX.world.entity.Entity +6M -2M | +1P
```
```
XXX.world.entity.EntityType +1P -15P
```
```
XXX.ai.behavior.AnimalPanic +10M -4M | +1P
```
```
XXX.ai.behavior.BabyFollowAdult +3M -3M
```
```
XXX.ai.behavior.FollowTemptation +1M | +1P
```
```
XXX.ai.memory.MemoryModuleType -1P
```
```
XXX.ai.navigation.FlyingPathNavigation +1M -1M
```
```
XXX.ai.navigation.PathNavigation +1M | +1P
```
```
XXX.ai.navigation.WaterBoundPathNavigation +1M
```
```
XXX.entity.monster.Drowned +1M -1M | -2P
```
```
XXX.entity.monster.Ghast +4M | +1P
```
```
XXX.entity.monster.Ghast$GhastMoveControl +1M -1M | +3P -1P
```
```
XXX.entity.monster.Ghast$RandomFloatAroundGoal +6M -1M | +3P -1P
```
```
XXX.entity.monster.Phantom +3M
```
```
XXX.monster.warden.Warden -2M | -6P
```
```
XXX.entity.npc.VillagerProfession -1P
```
```
XXX.world.inventory.AbstractCraftingMenu +3M -4M
```
```
XXX.world.inventory.AbstractFurnaceMenu -1P
```
```
XXX.world.inventory.EnchantmentMenu +1M -1M
```
```
XXX.world.inventory.HopperMenu +1M -1M
```
```
XXX.world.inventory.InventoryMenu -3M
```
```
XXX.item.component.ItemContainerContents +1M -1M
```
```
XXX.item.component.SuspiciousStewEffects +1M -1M
```
```
XXX.level.biome.Biome +4M -6M | +1P -1P
```
```
XXX.level.biome.BiomeSpecialEffects +2M -7M | -1P
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.Block +2M -3M
```
```
XXX.level.block.DryVegetationBlock -2P
```
```
XXX.level.block.ShortDryGrassBlock +1M
```
```
XXX.level.block.SlimeBlock +1M -1M
```
```
XXX.block.entity.PotDecorations +1M -1M
```
```
XXX.block.sounds.AmbientDesertBlockSoundsPlayer +7M -3M | +6P -2P
```
```
XXX.state.properties.BlockStateProperties +1P -1P
```
```
XXX.level.chunk.ChunkGenerator -1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M
```
```
XXX.levelgen.presets.WorldPresets$Bootstrap +1M | +2P
```
```
XXX.levelgen.structure.BuiltinStructureSets -3P
```
```
XXX.levelgen.structure.Structure +2M -3M
```
```
XXX.levelgen.structure.Structure$StructureSettings$Builder -1M | +1P -1P
```
```
XXX.structure.structures.NetherFossilPieces$NetherFossilPiece +1M
```
```
XXX.structure.templatesystem.StructureTemplate -1M
```
```
XXX.saveddata.maps.MapId +1M -1M
```
```
XXX.level.storage.DataVersion +5M -4M
```
```
XXX.level.storage.LevelResource -1P
```
```
XXX.level.storage.LevelStorageSource -1M
```
```
XXX.level.storage.PrimaryLevelData +2M -23M | -9P
```
```
XXX.level.storage.ServerLevelData -11P
```
```
XXX.loot.parameters.LootContextParamSets -1M | -1P
```
```
XXX.level.timers.FunctionCallback +1M -1M
```

</details>
<details>
<summary>
net.minecraft.DetectedVersion
</summary>

```diff
+ boolean isStable()
+ DataVersion getDataVersion()
+ Date getBuildTime()
+ int getPackVersion(PackType)
+ int getProtocolVersion()
+ String getId()
+ String getName()
+ void <init>(JsonObject)
- WorldVersion createFromConstants()
- WorldVersion createFromJson(JsonObject)
```

</details>
<details>
<summary>
net.minecraft.advancements.DisplayInfo
</summary>

```diff
+ Component getHint()
+ void <init>(ItemStack,Component,Component,Component,Optional,AdvancementType,boolean,boolean,boolean)
- void <init>(ItemStack,Component,Component,Optional,AdvancementType,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$260(Integer)
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$261(Integer)
- LootPoolEntryContainer$Builder lambda$generate$252(Block,Integer)
+ LootPoolEntryContainer$Builder lambda$generate$254(Block,Integer)
+ LootTable$Builder lambda$generate$204(Block)
- LootTable$Builder lambda$generate$204(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$205(Block)
+ LootTable$Builder lambda$generate$205(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$214(Block)
- LootTable$Builder lambda$generate$214(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$216(Block)
+ LootTable$Builder lambda$generate$216(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$220(Block)
- LootTable$Builder lambda$generate$220(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$221(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$221(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$223(Block)
+ LootTable$Builder lambda$generate$223(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$225(Block)
- LootTable$Builder lambda$generate$225(VanillaBlockLoot,ItemLike)
- LootTable$Builder lambda$generate$231(Block)
+ LootTable$Builder lambda$generate$231(VanillaBlockLoot,ItemLike)
+ LootTable$Builder lambda$generate$232(Block)
- LootTable$Builder lambda$generate$232(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$233(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$233(VanillaBlockLoot,ItemLike)
- LootTable$Builder lambda$generate$235(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$235(VanillaBlockLoot,ItemLike)
- LootTable$Builder lambda$generate$236(Block)
+ LootTable$Builder lambda$generate$236(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$243(Block)
- LootTable$Builder lambda$generate$243(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$245(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$245(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$247(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$247(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$249(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$249(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$252(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$254(Block)
+ LootTable$Builder lambda$generate$255(Block)
- LootTable$Builder lambda$generate$255(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$256(Block)
+ LootTable$Builder lambda$generate$256(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$257(Block)
- LootTable$Builder lambda$generate$257(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$258(Block)
+ LootTable$Builder lambda$generate$258(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$259(Block)
- LootTable$Builder lambda$generate$259(HolderLookup$RegistryLookup,HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$260(HolderLookup$RegistryLookup,HolderLookup$RegistryLookup,Block)
+ void addTrophies()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer$1
</summary>

```diff
- void <init>(GameTestServer,MinecraftServer,LayeredRegistryAccess,PlayerDataStorage,int)
+ void <init>(GameTestServer,TheGame,PlayerDataStorage,int)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style$Serializer
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
+ App lambda$static$13(RecordCodecBuilder$Instance)
+ Optional lambda$static$11(Style)
+ Optional lambda$static$12(Style)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
- DedicatedServer getServer()
- MinecraftServer getServer()
- void <init>(DedicatedServer,LayeredRegistryAccess,PlayerDataStorage)
+ void <init>(DedicatedServer,TheGame,PlayerDataStorage)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.ServerWatchdog
</summary>

```diff
- void <init>(DedicatedServer)
+ void <init>(TheGame,long)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$10(Predicate,List,int,Entity)
+ AbortableIterationConsumer$Continuation lambda$getEntities$26(Predicate,List,int,Entity)
+ BlockableEventLoop eventLoop()
+ BlockPos lambda$findLightningRod$22(BlockPos)
- BlockPos lambda$findLightningRod$6(BlockPos)
+ boolean isActive(WorldEffect)
+ boolean isEffectUnlocked(WorldEffect)
+ boolean isMine()
+ boolean isMineCompleted()
+ boolean isMineWon()
+ boolean isSpecialMine()
+ boolean isSpecialMineUnlocked(SpecialMine)
- boolean lambda$clearBlockEvents$16(BoundingBox,BlockEventData)
+ boolean lambda$clearBlockEvents$32(BoundingBox,BlockEventData)
+ boolean lambda$dropUnlockEffect$18(WorldEffect,ItemStack)
+ boolean lambda$findLightningRod$20(Holder)
+ boolean lambda$findLightningRod$21(BlockPos)
- boolean lambda$findLightningRod$4(Holder)
- boolean lambda$findLightningRod$5(BlockPos)
+ boolean lambda$findLightningTargetAround$23(LivingEntity)
- boolean lambda$findLightningTargetAround$7(LivingEntity)
+ boolean lambda$new$1(MineEvent)
+ boolean lambda$teleportAllPlayersToMine$14(Holder)
+ boolean lambda$tickEvents$5(MineEvent)
+ boolean lambda$tickEvents$6(MineEvent)
+ boolean lambda$tickEvents$7(MineEvent)
+ ChunkIOErrorReporter chunkIOErrorReporter()
- DimensionDataStorage lambda$new$0(MinecraftServer)
+ DimensionDataStorage lambda$new$0(TheGame)
+ int getMineCrafterExp()
+ int getMineCrafterLevel()
+ List events()
+ List getActiveEffects()
+ List getRewardKeys(BlockPos)
+ List getUnlockedEffects()
- MinecraftServer getServer()
+ Optional getNextSpecialMine()
+ Optional specialMine()
+ PlayerList getPlayerList()
- RandomSequences lambda$new$1()
+ RandomSequences lambda$new$2()
+ ServerTickRateManager tickRateManager()
- ServerWaypointManager getWaypointManager()
- String lambda$fillReportDetails$20()
+ String lambda$fillReportDetails$36()
- String lambda$getTypeCount$18(Object2IntMap$Entry)
+ String lambda$getTypeCount$34(Object2IntMap$Entry)
- String lambda$getWatchdogStats$17(Entity)
+ String lambda$getWatchdogStats$33(Entity)
+ String lambda$tickNonPassenger$24(Entity)
- String lambda$tickNonPassenger$8(Entity)
+ String lambda$tickPassenger$25(Entity)
- String lambda$tickPassenger$9(Entity)
+ TeleportTransition getHubTeleport()
+ TheGame theGame()
- void <init>(MinecraftServer,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,ResourceKey,LevelStem,ChunkProgressListener,boolean,long,List,boolean,RandomSequences)
+ void <init>(TheGame,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,ResourceKey,Holder,ChunkProgressListener,boolean,long,List,boolean,RandomSequences)
+ void addExperienceToMineCrafter(int)
+ void cleanInventoryAndReward(ServerPlayer,float)
+ void dropRewards(BlockPos)
+ void dropUnlockEffect(Vec3,WorldEffect,ServerPlayer)
+ void handleCompletedMine()
+ void handleInProgressMine()
+ void handleMineCountDown(Consumer)
+ void handleMineLoss()
+ void handleMineWin(BlockPos)
- void lambda$globalLevelEvent$11(BlockPos,int,int,ServerPlayer)
+ void lambda$globalLevelEvent$27(BlockPos,int,int,ServerPlayer)
+ void lambda$handleCompletedMine$11(ServerPlayer)
+ void lambda$handleCompletedMine$12(ServerPlayer)
+ void lambda$handleInProgressMine$8(BlockPos)
+ void lambda$handleMineLoss$9(ServerPlayer)
+ void lambda$handleMineWin$10(ServerPlayer)
+ void lambda$leaveForMine$13(ResourceKey,boolean,Optional,MinecraftServer)
+ void lambda$markMineCompleted$16(ServerPlayer,boolean,SpecialMine)
+ void lambda$markMineCompleted$17(boolean,MineEvent)
- void lambda$onStructureStartsAvailable$19(ChunkAccess)
+ void lambda$onStructureStartsAvailable$35(ChunkAccess)
+ void lambda$setDimensionType$37(Holder,ServerPlayer)
+ void lambda$teleportAllPlayersToMine$15(StructureStart,ChunkGenerator,ChunkPos)
- void lambda$tick$2(TickRateManager,ProfilerFiller,Entity)
+ void lambda$tick$3(TickRateManager,ProfilerFiller,Entity)
+ void lambda$tickEvents$4(MineEvent)
- void lambda$updatePOIOnBlockStateChange$12(BlockPos)
- void lambda$updatePOIOnBlockStateChange$13(BlockPos,Holder)
- void lambda$updatePOIOnBlockStateChange$14(BlockPos,Holder)
- void lambda$updatePOIOnBlockStateChange$15(BlockPos,Holder)
+ void lambda$updatePOIOnBlockStateChange$28(BlockPos)
+ void lambda$updatePOIOnBlockStateChange$29(BlockPos,Holder)
+ void lambda$updatePOIOnBlockStateChange$30(BlockPos,Holder)
+ void lambda$updatePOIOnBlockStateChange$31(BlockPos,Holder)
+ void lambda$wakeUpAllPlayers$19(ServerPlayer)
- void lambda$wakeUpAllPlayers$3(ServerPlayer)
+ void leaveForMine(BlockPos,boolean,Optional)
+ void markMineCompleted(boolean)
+ void onMineEntered()
+ void onMineLeave()
+ void respawnPlayerIntoHub(ServerPlayer,Consumer)
+ void respawnPlayersIntoHub(Consumer)
+ void setDimensionType(Holder)
+ void startEvent(MineEvent)
+ void syncContainerMenuData(MenuType,List)
+ void teleportAllPlayersToMine(boolean,Optional)
+ void tickEvents()
+ void toggledMineTravellingBlock(BlockPos)
+ void unlockEffect(WorldEffect)
+ void unlockSpecialMine(SpecialMine)
- void updateNeighboursOnBlockSet(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- MinecraftServer getServer()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerConfigurationPacketListenerImpl
</summary>

```diff
+ Stream lambda$queueRegistrySynchronizationTask$0(PackResources)
- Stream lambda$startConfiguration$0(PackResources)
- void <init>(MinecraftServer,Connection,CommonListenerCookie)
+ void <init>(TheGame,Connection,CommonListenerCookie)
+ void queueRegistrySynchronizationTask()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void <init>(MinecraftServer,Connection,ServerPlayer,CommonListenerCookie)
+ void <init>(TheGame,Connection,ServerPlayer,CommonListenerCookie)
+ void handleBuyUnlock(ServerboundPlayerBuyUnlockPacket)
+ void handlePlayerDonateExperience(ServerboundPlayerDonateExperiencePacket)
+ void handleReactivateUnlock(ServerboundPlayerReactivateUnlockPacket)
+ void lambda$handleClientCommand$11(ServerPlayer)
- void lambda$handleSignUpdate$11(ServerboundSignUpdatePacket,List)
+ void lambda$handleSignUpdate$12(ServerboundSignUpdatePacket,List)
- void lambda$resetPlayerChatState$12(RemoteChatSession)
+ void lambda$resetPlayerChatState$13(RemoteChatSession)
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerLoginPacketListenerImpl
</summary>

```diff
- void <init>(MinecraftServer,Connection,boolean)
+ void <init>(TheGame,Connection,boolean)
- void lambda$verifyLoginAndFinishConnectionSetup$0()
+ void lambda$verifyLoginAndFinishConnectionSetup$0(int)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- Component lambda$broadcastSystemMessage$3(Component,ServerPlayer)
+ Component lambda$broadcastSystemMessage$4(Component,ServerPlayer)
- MinecraftServer getServer()
- ServerPlayer getPlayerForLogin(GameProfile,ClientInformation)
+ ServerPlayer respawn(ServerPlayer,boolean,Entity$RemovalReason,Optional)
- ServerPlayer respawn(ServerPlayer,boolean,Entity$RemovalReason)
+ ServerPlayerUnlocks getPlayerUnlocks(ServerPlayer)
- ServerStatsCounter getPlayerStats(Player)
+ ServerStatsCounter getPlayerStats(ServerPlayer)
+ TeleportTransition lambda$respawn$3(ServerPlayer,boolean)
+ TheGame theGame()
- void <init>(MinecraftServer,LayeredRegistryAccess,PlayerDataStorage,int)
+ void <init>(TheGame,PlayerDataStorage,int)
- void reloadResources()
+ void reloadResources(TheGame)
+ void syncContainerMenuData(MenuType,List)
```

</details>
<details>
<summary>
net.minecraft.server.rcon.RconConsoleSource
</summary>

```diff
- CommandSourceStack createCommandSourceStack()
+ CommandSourceStack createCommandSourceStack(TheGame)
```

</details>
<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- int smallestSquareSide(int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
</summary>

```diff
- Dynamic lambda$makeRule$0(Dynamic)
+ Typed lambda$makeRule$0(OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$1(OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,OpticFinder,Typed)
+ void <init>(Schema,boolean,Set)
- void <init>(Schema,Set)
```

</details>
<details>
<summary>
net.minecraft.util.debugchart.RemoteSampleLogger
</summary>

```diff
+ boolean isEnabled()
+ void subscribe(ServerPlayer,RemoteDebugSampleType)
+ void tick(int)
```

</details>
<details>
<summary>
net.minecraft.util.random.WeightedList$Builder
</summary>

```diff
+ WeightedList$Builder clear()
```

</details>
<details>
<summary>
net.minecraft.world.Container
</summary>

```diff
+ Player getPlayer()
```

</details>
<details>
<summary>
net.minecraft.world.MenuProvider
</summary>

```diff
+ List getAdditionalData()
```

</details>
<details>
<summary>
net.minecraft.world.damagesource.DamageSources
</summary>

```diff
+ DamageSource devour(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean getRequiresPrecisePosition()
- boolean isInClouds()
- Entity teleportCrossDimension(ServerLevel,ServerLevel,TeleportTransition)
+ Entity teleportCrossDimension(ServerLevel,TeleportTransition)
- MinecraftServer getServer()
+ TheGame theGame()
- void setRequiresPrecisePosition(boolean)
- void teleportSpectators(TeleportTransition,ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.AnimalPanic
</summary>

```diff
+ Boolean lambda$checkExtraStartConditions$1(PathfinderMob,DamageSource)
- Boolean lambda$checkExtraStartConditions$5(PathfinderMob,DamageSource)
+ boolean lambda$lookForWater$2(BlockGetter,BlockPos)
+ boolean lambda$lookForWater$3(BlockGetter,BlockPos)
+ boolean lambda$lookForWater$4(BlockGetter,BlockPos)
- boolean lambda$lookForWater$6(BlockGetter,BlockPos)
- boolean lambda$lookForWater$7(BlockGetter,BlockPos)
- boolean lambda$lookForWater$8(BlockGetter,BlockPos)
- TagKey lambda$new$2(PathfinderMob)
- Vec3 lambda$new$1(PathfinderMob)
- Vec3 lambda$new$3(int,PathfinderMob)
- Vec3 lambda$new$4(PathfinderMob)
- void <init>(float,Function,Function)
- void <init>(float,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.BabyFollowAdult
</summary>

```diff
- App lambda$create$3(MemoryModuleType,UniformInt,Function,BehaviorBuilder$Instance)
+ App lambda$create$3(UniformInt,Function,BehaviorBuilder$Instance)
+ boolean lambda$create$1(BehaviorBuilder$Instance,MemoryAccessor,UniformInt,Function,MemoryAccessor,MemoryAccessor,ServerLevel,AgeableMob,long)
- boolean lambda$create$1(BehaviorBuilder$Instance,MemoryAccessor,UniformInt,Function,MemoryAccessor,MemoryAccessor,ServerLevel,LivingEntity,long)
- OneShot create(UniformInt,Function,MemoryModuleType)
+ OneShot create(UniformInt,Function)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.FollowTemptation
</summary>

```diff
- void <init>(Function,Function,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
</summary>

```diff
- boolean canNavigateGround()
+ void setCanOpenDoors(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.PathNavigation
</summary>

```diff
- void setCanOpenDoors(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
</summary>

```diff
- boolean canNavigateGround()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
+ PathNavigation access$002(Drowned,PathNavigation)
- PathNavigation createNavigation(Level)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ghast
</summary>

```diff
- boolean onClimbable()
- void checkFallDamage(double,boolean,BlockState,BlockPos)
- void faceMovementDirection(Mob)
- void travel(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ghast$GhastMoveControl
</summary>

```diff
+ void <init>(Ghast)
- void <init>(Mob,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
</summary>

```diff
- boolean isGoodTarget(Level,Vec3,int)
- Vec3 chooseRandomPosition(Vec3,RandomSource)
- Vec3 chooseRandomPositionWithRestriction(Mob,Vec3,RandomSource)
- Vec3 getSuitableFlyToPosition(Mob,int)
+ void <init>(Ghast)
- void <init>(Mob,int)
- void <init>(Mob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- boolean onClimbable()
- void checkFallDamage(double,boolean,BlockState,BlockPos)
- void travel(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
+ void lambda$stopActing$1(Player)
+ void stopActing()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractCraftingMenu
</summary>

```diff
- int getGridHeight()
+ int getGridHeight(Player)
- int getGridWidth()
+ int getGridWidth(Player)
- void addCraftingGridSlots(int,int)
+ void addCraftingGridSlots(Player,int,int)
+ void adjustCraftingGridSlotsPosition(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.EnchantmentMenu
</summary>

```diff
+ void <init>(int,Inventory,List)
- void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.HopperMenu
</summary>

```diff
+ void <init>(int,Inventory,List)
- void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.InventoryMenu
</summary>

```diff
+ int getGridHeight(Player)
+ int getGridWidth(Player)
+ void menuTick(Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.ItemContainerContents
</summary>

```diff
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.SuspiciousStewEffects
</summary>

```diff
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- Biome lambda$static$7(Biome$ClimateSettings,BiomeSpecialEffects)
+ Biome lambda$static$7(ClimateSettings,BiomeSpecialEffects)
- Biome$ClimateSettings lambda$static$0(Biome)
- Biome$ClimateSettings lambda$static$5(Biome)
+ BiomeBuilder asBuilder()
+ boolean equals(Object)
+ ClimateSettings lambda$static$0(Biome)
+ ClimateSettings lambda$static$5(Biome)
- void <init>(Biome$ClimateSettings,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings)
+ void <init>(ClimateSettings,BiomeSpecialEffects,BiomeGenerationSettings,MobSpawnSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- App lambda$static$14(RecordCodecBuilder$Instance)
+ App lambda$static$15(RecordCodecBuilder$Instance)
+ BiomeSpecialEffects$Builder asBuilder()
+ BiomeSpecialEffects$ExitType getExitType()
+ BiomeSpecialEffects$ExitType lambda$static$14(BiomeSpecialEffects)
+ boolean equals(Object)
+ int hashCode()
+ void <init>(int,int,int,int,Optional,Optional,Optional,BiomeSpecialEffects$GrassColorModifier,Optional,Optional,Optional,Optional,Optional,float,BiomeSpecialEffects$ExitType)
- void <init>(int,int,int,int,Optional,Optional,Optional,BiomeSpecialEffects$GrassColorModifier,Optional,Optional,Optional,Optional,Optional,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
+ void updateEntityMovementAfterFallOn(Level,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- float getFriction()
+ float getFriction(boolean)
+ void bounceUp(Entity)
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
+ void updateEntityMovementAfterFallOn(Level,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShortDryGrassBlock
</summary>

```diff
- void animateTick(BlockState,Level,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
+ void updateEntityMovementAfterFallOn(Level,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.PotDecorations
</summary>

```diff
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.sounds.AmbientDesertBlockSoundsPlayer
</summary>

```diff
- boolean canTriggerAmbientDesertSandSounds(BlockState)
- boolean columnContainsTriggeringBlock(Level,BlockPos$MutableBlockPos)
+ boolean isInAmbientSoundBiome(Holder)
- boolean shouldPlayAmbientSandSound(Level,BlockPos)
+ boolean shouldPlayAmbientSound(Level,BlockPos)
- boolean shouldPlayDesertDryVegetationBlockSounds(Level,BlockPos)
+ void playAmbientBlockSounds(BlockState,Level,BlockPos,RandomSource)
- void playAmbientDeadBushSounds(Level,BlockPos,RandomSource)
- void playAmbientDryGrassSounds(Level,BlockPos,RandomSource)
- void playAmbientSandSounds(Level,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ NoiseGeneratorSettings getNoiseGeneratorSettings()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- Holder generatorSettings()
+ NoiseGeneratorSettings getNoiseGeneratorSettings()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
</summary>

```diff
- void registerOverworlds(BiomeSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure
</summary>

```diff
+ boolean lambda$filteredBiomes$2(Holder)
- boolean lambda$findValidGenerationPoint$2(Structure$GenerationContext,Structure$GenerationStub)
+ boolean lambda$findValidGenerationPoint$3(Structure$GenerationContext,Structure$GenerationStub)
- HolderSet biomes()
+ HolderSet filteredBiomes(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$StructureSettings$Builder
</summary>

```diff
+ void <init>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
</summary>

```diff
- void placeDriedGhast(WorldGenLevel,RandomSource,BoundingBox,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
</summary>

```diff
+ ObjectArrayList getBlocks(BlockPos,StructurePlaceSettings,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapId
</summary>

```diff
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DataVersion
</summary>

```diff
- boolean equals(Object)
+ int getVersion()
- int hashCode()
- int version()
+ String getSeries()
- String series()
- String toString()
+ void <clinit>()
+ void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
+ LevelDataAndDimensions getLevelDataAndDimensions(Dynamic,WorldDataConfiguration,Registry,HolderLookup$Provider,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.PrimaryLevelData
</summary>

```diff
+ boolean isEffectUnlocked(WorldEffect)
+ boolean isSpecialMineLevel(int)
+ boolean isSpecialMineUnlocked(SpecialMine)
+ boolean lambda$getNextSpecialMine$7(SpecialMine)
+ int getLevelCount()
+ int getMineCrafterExp()
+ int getMineCrafterLevel()
+ int incrementAndGetLevelCount()
+ Iterable getUnlockedEffects()
+ Map events()
+ Optional getNextSpecialMine(RandomSource)
+ Optional hubDimensionType()
+ Stream lambda$parse$2(Dynamic)
+ Stream lambda$parse$3(Dynamic)
+ Stream lambda$parse$4(Dynamic)
- void <init>(CompoundTag,boolean,BlockPos,float,long,long,int,int,int,boolean,int,boolean,boolean,boolean,WorldBorder$Settings,int,int,UUID,Set,Set,TimerQueue,CompoundTag,EndDragonFight$Data,LevelSettings,WorldOptions,PrimaryLevelData$SpecialWorldProperty,Lifecycle)
+ void <init>(CompoundTag,boolean,BlockPos,float,long,long,int,int,int,boolean,int,boolean,boolean,boolean,WorldBorder$Settings,int,int,UUID,Set,Set,TimerQueue,CompoundTag,EndDragonFight$Data,LevelSettings,WorldOptions,PrimaryLevelData$SpecialWorldProperty,Optional,Lifecycle,List,List,List,Object2IntOpenHashMap,int,int,int,Map)
+ void addExperienceToMineCrafter(int)
- void lambda$setTagData$2(CompoundTag,Tag)
+ void lambda$setTagData$5(CompoundTag,Tag)
+ void lambda$setTagData$6(CompoundTag,Holder)
+ void mineCompleted(Optional,boolean)
+ void setHubDimensionType(Holder)
+ void unlockEffect(WorldEffect)
+ void unlockSpecialMine(SpecialMine)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
</summary>

```diff
+ void lambda$static$26(ContextKeySet$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.level.timers.FunctionCallback
</summary>

```diff
- void handle(MinecraftServer,TimerQueue,long)
+ void handle(TheGame,TimerQueue,long)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- net.minecraft.WorldVersion$Simple
+ XXX.advancements.critereon.AnyBlockInteractionTrigger
- XXX.advancements.critereon.AnyBlockInteractionTrigger$TriggerInstance
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
+ XXX.advancements.critereon.CollectionContentsPredicate
- XXX.advancements.critereon.CollectionContentsPredicate$Multiple
+ XXX.advancements.critereon.CollectionContentsPredicate$Single
- XXX.advancements.critereon.CollectionContentsPredicate$Zero
+ XXX.advancements.critereon.CollectionCountsPredicate
- XXX.advancements.critereon.CollectionCountsPredicate$Entry
+ XXX.advancements.critereon.CollectionCountsPredicate$Multiple
- XXX.advancements.critereon.CollectionCountsPredicate$Single
+ XXX.advancements.critereon.CollectionCountsPredicate$Zero
- XXX.advancements.critereon.CollectionPredicate
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.ContextAwarePredicate
- XXX.advancements.critereon.CriterionValidator
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DataComponentMatchers
- XXX.advancements.critereon.DataComponentMatchers$Builder
+ XXX.advancements.critereon.DefaultBlockInteractionTrigger
- XXX.advancements.critereon.DefaultBlockInteractionTrigger$TriggerInstance
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.DistanceTrigger
+ XXX.advancements.critereon.DistanceTrigger$TriggerInstance
- XXX.advancements.critereon.EffectsChangedTrigger
+ XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantedItemTrigger
+ XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantmentPredicate
+ XXX.advancements.critereon.EnterBlockTrigger
- XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityEquipmentPredicate
- XXX.advancements.critereon.EntityEquipmentPredicate$Builder
+ XXX.advancements.critereon.EntityFlagsPredicate
- XXX.advancements.critereon.EntityFlagsPredicate$Builder
+ XXX.advancements.critereon.EntityHurtPlayerTrigger
- XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityPredicate
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$LocationWrapper
- XXX.advancements.critereon.EntitySubPredicate
+ XXX.advancements.critereon.EntitySubPredicates
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.FallAfterExplosionTrigger
- XXX.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingHookPredicate
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.GameTypePredicate
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InputPredicate
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger
- XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByArrowTrigger
- XXX.advancements.critereon.KilledByArrowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightningBoltPredicate
- XXX.advancements.critereon.LightningStrikeTrigger
+ XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationPredicate$PositionPredicate
+ XXX.advancements.critereon.LootTableTrigger
- XXX.advancements.critereon.LootTableTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$1
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
+ XXX.advancements.critereon.UnlockPredicate$Builder
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedExitEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaFeatsAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.goal.PetWolfBegGoal
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
- XXX.ai.sensing.AxolotlAttackablesSensor
+ XXX.ai.sensing.BreezeAttackEntitySensor
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.FrogAttackablesSensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HoglinSpecificSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.IsInWaterSensor
- XXX.ai.sensing.MobSensor
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
+ XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
- XXX.ai.targeting.TargetingConditions$Selector
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
- XXX.animal.frog.FrogVariant
+ XXX.animal.frog.FrogVariants
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
+ XXX.animal.sheep.package-info
+ XXX.animal.sheep.Sheep
- XXX.animal.sheep.SheepColorSpawnRules
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
- XXX.animal.sniffer.package-info
- XXX.animal.sniffer.Sniffer
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
- XXX.animal.wolf.package-info
+ XXX.animal.wolf.Wolf
- XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
+ XXX.animal.wolf.Wolf$WolfPackData
- XXX.animal.wolf.WolfSoundVariant
+ XXX.animal.wolf.WolfSoundVariants
- XXX.animal.wolf.WolfSoundVariants$SoundSet
+ XXX.animal.wolf.WolfVariant
- XXX.animal.wolf.WolfVariant$AssetInfo
+ XXX.animal.wolf.WolfVariants
+ XXX.animation.definitions.ArmadilloAnimation
- XXX.animation.definitions.BatAnimation
+ XXX.animation.definitions.BreezeAnimation
- XXX.animation.definitions.CamelAnimation
+ XXX.animation.definitions.CreakingAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
- XXX.animation.definitions.WardenAnimation
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
- XXX.arguments.item.ComponentPredicateParser
+ XXX.arguments.item.ComponentPredicateParser$ComponentLookupRule
- XXX.arguments.item.ComponentPredicateParser$Context
+ XXX.arguments.item.ComponentPredicateParser$ElementLookupRule
- XXX.arguments.item.ComponentPredicateParser$PredicateLookupRule
+ XXX.arguments.item.ComponentPredicateParser$TagLookupRule
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemParser$1
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemParser$State
- XXX.arguments.item.ItemParser$SuggestionsVisitor
+ XXX.arguments.item.ItemParser$Visitor
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ComponentWrapper
- XXX.arguments.item.ItemPredicateArgument$Context
+ XXX.arguments.item.ItemPredicateArgument$PredicateWrapper
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelector$1
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
- XXX.arguments.selector.SelectorPattern
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
- XXX.blaze3d.opengl.GlRenderPass$ScissorState
+ XXX.blaze3d.opengl.GlRenderPipeline
- XXX.blaze3d.opengl.GlShaderModule
+ XXX.blaze3d.opengl.GlStateManager
- XXX.blaze3d.opengl.GlStateManager$BlendState
+ XXX.blaze3d.opengl.GlStateManager$BooleanState
- XXX.blaze3d.opengl.GlStateManager$ColorLogicState
+ XXX.blaze3d.opengl.GlStateManager$ColorMask
- XXX.blaze3d.opengl.GlStateManager$CullState
+ XXX.blaze3d.opengl.GlStateManager$DepthState
- XXX.blaze3d.opengl.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.opengl.GlStateManager$ScissorState
- XXX.blaze3d.opengl.GlStateManager$TextureState
+ XXX.blaze3d.opengl.GlTexture
- XXX.blaze3d.opengl.GlTexture$1
- XXX.blaze3d.opengl.package-info
+ XXX.blaze3d.opengl.Uniform
- XXX.blaze3d.opengl.Uniform$1
+ XXX.blaze3d.opengl.VertexArrayCache
- XXX.blaze3d.opengl.VertexArrayCache$1
+ XXX.blaze3d.opengl.VertexArrayCache$Emulated
- XXX.blaze3d.opengl.VertexArrayCache$Separate
+ XXX.blaze3d.opengl.VertexArrayCache$VertexArray
- XXX.blaze3d.pipeline.BlendFunction
+ XXX.blaze3d.pipeline.CompiledRenderPipeline
- XXX.blaze3d.pipeline.MainTarget
+ XXX.blaze3d.pipeline.MainTarget$Dimension
- XXX.blaze3d.pipeline.package-info
- XXX.blaze3d.pipeline.RenderPipeline
+ XXX.blaze3d.pipeline.RenderPipeline$Builder
- XXX.blaze3d.pipeline.RenderPipeline$Snippet
+ XXX.blaze3d.pipeline.RenderPipeline$UniformDescription
- XXX.blaze3d.pipeline.RenderTarget
+ XXX.blaze3d.pipeline.TextureTarget
+ XXX.blaze3d.platform.ClientShutdownWatchdog
- XXX.blaze3d.platform.ClipboardManager
+ XXX.blaze3d.platform.DebugMemoryUntracker
- XXX.blaze3d.platform.DepthTestFunction
+ XXX.blaze3d.platform.DestFactor
- XXX.blaze3d.platform.DisplayData
+ XXX.blaze3d.platform.FramerateLimitTracker
- XXX.blaze3d.platform.FramerateLimitTracker$FramerateThrottleReason
+ XXX.blaze3d.platform.GLX
- XXX.blaze3d.platform.IconSet
+ XXX.blaze3d.platform.InputConstants
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.LogicOp
- XXX.blaze3d.platform.MacosUtil
+ XXX.blaze3d.platform.Monitor
- XXX.blaze3d.platform.MonitorCreator
+ XXX.blaze3d.platform.NativeImage
- XXX.blaze3d.platform.NativeImage$Format
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.PolygonMode
+ XXX.blaze3d.platform.ScreenManager
- XXX.blaze3d.platform.SourceFactor
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
- XXX.blaze3d.shaders.FogShape
+ XXX.blaze3d.shaders.package-info
+ XXX.blaze3d.shaders.ShaderType
- XXX.blaze3d.shaders.UniformType
- XXX.blaze3d.systems.CommandEncoder
+ XXX.blaze3d.systems.GpuDevice
- XXX.blaze3d.systems.RenderPass
+ XXX.blaze3d.systems.RenderPass$Draw
- XXX.blaze3d.systems.RenderPass$UniformUploader
+ XXX.blaze3d.systems.RenderSystem
- XXX.blaze3d.systems.RenderSystem$1
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
+ XXX.blaze3d.systems.RenderSystem$GpuAsyncTask
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPatternLayers
- XXX.block.entity.BannerPatternLayers$Builder
+ XXX.block.entity.BannerPatternLayers$Layer
- XXX.block.entity.BannerPatterns
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBeamOwner
+ XXX.block.entity.BeaconBeamOwner$Section
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BeehiveBlockEntity$Occupant
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntity$1
- XXX.block.entity.BlockEntity$ComponentHelper
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BoundingBoxRenderable
+ XXX.block.entity.BoundingBoxRenderable$Mode
- XXX.block.entity.BoundingBoxRenderable$RenderableBox
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
+ XXX.block.entity.CreakingHeartBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPattern
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantingTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FuelValues
+ XXX.block.entity.FuelValues$Builder
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.HangingSignBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.MineCrafterBlockEntity
+ XXX.block.entity.MobTrophyBlockEntity
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementFace$UVs
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$MultiPartDefinition
- XXX.block.model.BlockModelDefinition$SimpleModelSelectors
+ XXX.block.model.BlockModelPart
- XXX.block.model.BlockModelPart$Unbaked
+ XXX.block.model.BlockStateModel
- XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot
+ XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot$1
- XXX.block.model.BlockStateModel$Unbaked
+ XXX.block.model.BlockStateModel$UnbakedRoot
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.package-info
- XXX.block.model.SimpleModelWrapper
+ XXX.block.model.SimpleUnbakedGeometry
- XXX.block.model.SingleVariant
+ XXX.block.model.SingleVariant$Unbaked
- XXX.block.model.TextureSlots
+ XXX.block.model.TextureSlots$Data
- XXX.block.model.TextureSlots$Data$Builder
+ XXX.block.model.TextureSlots$Reference
- XXX.block.model.TextureSlots$Resolver
+ XXX.block.model.TextureSlots$SlotContents
- XXX.block.model.TextureSlots$Value
+ XXX.block.model.Variant
- XXX.block.model.Variant$SimpleModelState
+ XXX.block.model.VariantMutator
- XXX.block.model.VariantMutator$VariantProperty
+ XXX.block.model.VariantSelector
- XXX.boss.enderdragon.DragonFlightHistory
+ XXX.boss.enderdragon.DragonFlightHistory$Sample
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
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
+ XXX.chat.report.package-info
+ XXX.chat.report.Report
- XXX.chat.report.Report$Builder
+ XXX.chat.report.Report$CannotBuildReason
- XXX.chat.report.Report$Result
+ XXX.chat.report.ReportEnvironment
- XXX.chat.report.ReportEnvironment$Server
+ XXX.chat.report.ReportEnvironment$Server$Realm
- XXX.chat.report.ReportEnvironment$Server$ThirdParty
- XXX.chat.report.ReportingContext
+ XXX.chat.report.ReportReason
- XXX.chat.report.ReportReason$1
+ XXX.chat.report.ReportType
+ XXX.chat.report.SkinReport
- XXX.chat.report.SkinReport$Builder
- XXX.chunk.status.ChunkDependencies
+ XXX.chunk.status.ChunkPyramid
- XXX.chunk.status.ChunkPyramid$Builder
+ XXX.chunk.status.ChunkStatus
- XXX.chunk.status.ChunkStatusTask
+ XXX.chunk.status.ChunkStatusTasks
- XXX.chunk.status.ChunkStep
+ XXX.chunk.status.ChunkStep$Builder
- XXX.chunk.status.ChunkType
- XXX.chunk.status.package-info
+ XXX.chunk.status.WorldGenContext
+ XXX.chunk.storage.ChunkIOErrorReporter
- XXX.chunk.storage.ChunkScanAccess
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.IOWorker$ThrowingSupplier
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RecreatingChunkStorage
- XXX.chunk.storage.RecreatingSimpleRegionStorage
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.RegionStorageInfo
+ XXX.chunk.storage.SectionStorage
- XXX.chunk.storage.SectionStorage$PackedChunk
+ XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$ChunkReadException
+ XXX.chunk.storage.SerializableChunkData$SectionData
- XXX.chunk.storage.SimpleRegionStorage
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
- XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiGraphics$ScissorStack
+ XXX.client.gui.GuiSpriteManager
- XXX.client.gui.ItemSlotMouseAction
+ XXX.client.gui.LayeredDraw
+ XXX.client.main.GameConfig
- XXX.client.main.GameConfig$FolderData
+ XXX.client.main.GameConfig$GameData
- XXX.client.main.GameConfig$QuickPlayData
+ XXX.client.main.GameConfig$UserData
- XXX.client.main.Main
+ XXX.client.main.Main$1
- XXX.client.main.Main$2
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractBoatModel
- XXX.client.model.AbstractEquineModel
+ XXX.client.model.AbstractPiglinModel
- XXX.client.model.AbstractZombieModel
+ XXX.client.model.AdultAndBabyModelPair
- XXX.client.model.AllayModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmadilloModel
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.ArrowModel
+ XXX.client.model.AxolotlModel
- XXX.client.model.BabyModelTransform
+ XXX.client.model.BannerFlagModel
- XXX.client.model.BannerModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BeeStingerModel
- XXX.client.model.BellModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BoggedModel
- XXX.client.model.BookModel
+ XXX.client.model.BreezeModel
- XXX.client.model.CamelModel
+ XXX.client.model.CamelSaddleModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColdChickenModel
+ XXX.client.model.ColdCowModel
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
- XXX.client.model.EquineSaddleModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FelineModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
- XXX.client.model.HappyGhastModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HoglinModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidArmorModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.Model$Simple
- XXX.client.model.OcelotModel
- XXX.client.model.package-info
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$Pose
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerCapeModel
+ XXX.client.model.PlayerEarsModel
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
+ XXX.client.model.SpinAttackEffectModel
- XXX.client.model.SquidModel
+ XXX.client.model.StriderModel
- XXX.client.model.TadpoleModel
+ XXX.client.model.TridentModel
- XXX.client.model.TropicalFishModelA
+ XXX.client.model.TropicalFishModelB
- XXX.client.model.TurtleModel
+ XXX.client.model.VexModel
- XXX.client.model.VillagerLikeModel
+ XXX.client.model.VillagerModel
- XXX.client.model.WardenModel
+ XXX.client.model.WarmCowModel
- XXX.client.model.WindChargeModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.model.ZombifiedPiglinModel
+ XXX.client.multiplayer.AccountProfileKeyPairManager
- XXX.client.multiplayer.CacheSlot
+ XXX.client.multiplayer.CacheSlot$Cleaner
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
- XXX.client.multiplayer.ClientConfigurationPacketListenerImpl$1
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientLevel$ClientLevelData
- XXX.client.multiplayer.ClientLevel$EntityCallbacks
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientPlayerUnlocks
+ XXX.client.multiplayer.ClientRecipeContainer
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.CommonListenerCookie
- XXX.client.multiplayer.DebugSampleSubscriber
+ XXX.client.multiplayer.KnownPacksManager
- XXX.client.multiplayer.LegacyServerPinger
+ XXX.client.multiplayer.LegacyServerPinger$Output
- XXX.client.multiplayer.LevelLoadStatusManager
+ XXX.client.multiplayer.LevelLoadStatusManager$Status
- XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PingDebugMonitor
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ProfileKeyPairManager
- XXX.client.multiplayer.ProfileKeyPairManager$1
+ XXX.client.multiplayer.RegistryDataCollector
- XXX.client.multiplayer.RegistryDataCollector$ContentsCollector
+ XXX.client.multiplayer.RegistryDataCollector$TagCollector
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerData$State
+ XXX.client.multiplayer.ServerData$Type
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.SessionSearchTrees
+ XXX.client.multiplayer.SessionSearchTrees$Key
- XXX.client.multiplayer.TransferState
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BaseAshSmokeParticle
- XXX.client.particle.BlockMarker
+ XXX.client.particle.BlockMarker$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$CobwebProvider
- XXX.client.particle.BreakingItemParticle$ItemParticleProvider
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
- XXX.client.particle.FallingLeavesParticle
+ XXX.client.particle.FallingLeavesParticle$CherryProvider
- XXX.client.particle.FallingLeavesParticle$PaleOakProvider
+ XXX.client.particle.FallingLeavesParticle$TintedLeavesProvider
- XXX.client.particle.FireflyParticle
+ XXX.client.particle.FireflyParticle$FireflyProvider
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
- XXX.client.particle.FlyStraightTowardsParticle
+ XXX.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
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
- XXX.client.particle.GustParticle$SmallProvider
+ XXX.client.particle.GustSeedParticle
- XXX.client.particle.GustSeedParticle$Provider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MineTravelParticle
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.Particle$LifetimeAlpha
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1ParticleDefinition
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleProvider$Sprite
+ XXX.client.particle.ParticleRenderType
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
- XXX.client.particle.SingleQuadParticle$FacingCameraMode
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
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobEffectProvider
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
- XXX.client.particle.TerrainParticle$CrumblingProvider
+ XXX.client.particle.TerrainParticle$DustPillarProvider
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.TrailParticle
- XXX.client.particle.TrailParticle$Provider
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
+ XXX.client.player.ClientInput
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
- XXX.client.renderer.CloudRenderer
+ XXX.client.renderer.CloudRenderer$RelativeCameraPos
- XXX.client.renderer.CloudRenderer$TextureData
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.package-info
+ XXX.client.renderer.RenderStateShard$SkyTextureStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$1
+ XXX.client.renderer.SkyRenderer$CachedCubeSky
- XXX.client.renderer.SpecialBlockModelRenderer
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.client.renderer.WeatherEffectRenderer
+ XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
- XXX.client.renderer.WorldBorderRenderer
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DryFoliageColorReloadListener
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.IndexedAssetSource
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MapDecorationTextureManager
- XXX.client.resources.MapTextureManager
+ XXX.client.resources.MapTextureManager$MapInstance
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
- XXX.client.waypoints.ClientWaypointManager
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
+ XXX.color.item.GradeColor
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
- XXX.commands.arguments.package-info
- XXX.commands.arguments.WaypointArgument
- XXX.commands.execution.ChainModifiers
+ XXX.commands.execution.CommandQueueEntry
- XXX.commands.execution.CustomCommandExecutor
+ XXX.commands.execution.CustomCommandExecutor$CommandAdapter
- XXX.commands.execution.CustomCommandExecutor$WithErrorHandling
+ XXX.commands.execution.CustomModifierExecutor
- XXX.commands.execution.CustomModifierExecutor$ModifierAdapter
+ XXX.commands.execution.EntryAction
- XXX.commands.execution.ExecutionContext
+ XXX.commands.execution.ExecutionControl
- XXX.commands.execution.ExecutionControl$1
+ XXX.commands.execution.Frame
- XXX.commands.execution.Frame$FrameControl
+ XXX.commands.execution.package-info
+ XXX.commands.execution.TraceCallbacks
- XXX.commands.execution.UnboundEntryAction
+ XXX.commands.functions.CommandFunction
- XXX.commands.functions.FunctionBuilder
+ XXX.commands.functions.InstantiatedFunction
- XXX.commands.functions.MacroFunction
+ XXX.commands.functions.MacroFunction$Entry
- XXX.commands.functions.MacroFunction$MacroEntry
+ XXX.commands.functions.MacroFunction$PlainTextEntry
- XXX.commands.functions.package-info
- XXX.commands.functions.PlainTextFunction
+ XXX.commands.functions.StringTemplate
- XXX.commands.synchronization.ArgumentTypeInfo
+ XXX.commands.synchronization.ArgumentTypeInfo$Template
- XXX.commands.synchronization.ArgumentTypeInfos
+ XXX.commands.synchronization.ArgumentUtils
- XXX.commands.synchronization.package-info
- XXX.commands.synchronization.SingletonArgumentInfo
+ XXX.commands.synchronization.SingletonArgumentInfo$Template
- XXX.commands.synchronization.SuggestionProviders
+ XXX.commands.synchronization.SuggestionProviders$Wrapper
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
+ XXX.component.predicates.AttributeModifiersPredicate
- XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
+ XXX.component.predicates.BundlePredicate
- XXX.component.predicates.ContainerPredicate
+ XXX.component.predicates.CustomDataPredicate
- XXX.component.predicates.DamagePredicate
+ XXX.component.predicates.DataComponentPredicate
- XXX.component.predicates.DataComponentPredicate$Single
+ XXX.component.predicates.DataComponentPredicate$Type
- XXX.component.predicates.DataComponentPredicates
+ XXX.component.predicates.EnchantmentsPredicate
- XXX.component.predicates.EnchantmentsPredicate$Enchantments
+ XXX.component.predicates.EnchantmentsPredicate$StoredEnchantments
- XXX.component.predicates.FireworkExplosionPredicate
+ XXX.component.predicates.FireworkExplosionPredicate$FireworkPredicate
- XXX.component.predicates.FireworksPredicate
+ XXX.component.predicates.JukeboxPlayablePredicate
- XXX.component.predicates.package-info
- XXX.component.predicates.PotionsPredicate
+ XXX.component.predicates.TrimPredicate
- XXX.component.predicates.WritableBookPredicate
+ XXX.component.predicates.WritableBookPredicate$PagePredicate
- XXX.component.predicates.WrittenBookPredicate
+ XXX.component.predicates.WrittenBookPredicate$PagePredicate
+ XXX.components.toasts.LevelUpToast
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
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.CauldronInteraction$InteractionMap
- XXX.core.cauldron.package-info
+ XXX.core.component.DataComponentExactPredicate
- XXX.core.component.DataComponentExactPredicate$Builder
+ XXX.core.component.DataComponentGetter
- XXX.core.component.DataComponentHolder
+ XXX.core.component.DataComponentMap
- XXX.core.component.DataComponentMap$1
+ XXX.core.component.DataComponentMap$2
- XXX.core.component.DataComponentMap$3
+ XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentMap$Builder$SimpleMap
+ XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$1
+ XXX.core.component.DataComponentPatch$2
- XXX.core.component.DataComponentPatch$3
+ XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPatch$CodecGetter
+ XXX.core.component.DataComponentPatch$PatchKey
- XXX.core.component.DataComponentPatch$SplitResult
- XXX.core.component.DataComponents
+ XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder
+ XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.package-info
+ XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent
+ XXX.core.component.TypedDataComponent$1
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
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.EquipmentDispenseItemBehavior
+ XXX.core.dispenser.MinecartDispenseItemBehavior
- XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
+ XXX.core.dispenser.ProjectileDispenseBehavior
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.ColorParticleOption
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.ItemParticleOption
- XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.ScalableParticleOptionsBase
+ XXX.core.particles.SculkChargeParticleOptions
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.TrailParticleOption
+ XXX.core.particles.VibrationParticleOption
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
- XXX.crafting.display.DisplayContentsFactory
+ XXX.crafting.display.DisplayContentsFactory$ForRemainders
- XXX.crafting.display.DisplayContentsFactory$ForStacks
+ XXX.crafting.display.FurnaceRecipeDisplay
- XXX.crafting.display.package-info
- XXX.crafting.display.RecipeDisplay
+ XXX.crafting.display.RecipeDisplay$Type
- XXX.crafting.display.RecipeDisplayEntry
+ XXX.crafting.display.RecipeDisplayId
- XXX.crafting.display.RecipeDisplays
+ XXX.crafting.display.ShapedCraftingRecipeDisplay
- XXX.crafting.display.ShapelessCraftingRecipeDisplay
+ XXX.crafting.display.SlotDisplay
- XXX.crafting.display.SlotDisplay$AnyFuel
+ XXX.crafting.display.SlotDisplay$Composite
- XXX.crafting.display.SlotDisplay$Empty
+ XXX.crafting.display.SlotDisplay$ItemSlotDisplay
- XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
+ XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
- XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
+ XXX.crafting.display.SlotDisplay$TagSlotDisplay
- XXX.crafting.display.SlotDisplay$Type
+ XXX.crafting.display.SlotDisplay$WithRemainder
- XXX.crafting.display.SlotDisplayContext
+ XXX.crafting.display.SlotDisplays
- XXX.crafting.display.SmithingRecipeDisplay
+ XXX.crafting.display.StonecutterRecipeDisplay
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
- XXX.data.metadata.package-info
+ XXX.data.metadata.PackMetadataGenerator
- XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$FamilyRecipeProvider
- XXX.data.recipes.RecipeProvider$Runner
+ XXX.data.recipes.RecipeProvider$Runner$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.TransmuteRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.TradeRebalanceRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtDatafixer
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.DamageTypeTagsProvider
+ XXX.data.tags.EnchantmentTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
+ XXX.data.tags.VanillaEnchantmentTagsProvider
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
- XXX.datafix.schemas.V3448
+ XXX.datafix.schemas.V3682
- XXX.datafix.schemas.V3683
+ XXX.datafix.schemas.V3685
- XXX.datafix.schemas.V3689
+ XXX.datafix.schemas.V3799
- XXX.datafix.schemas.V3807
+ XXX.datafix.schemas.V3808
- XXX.datafix.schemas.V3808_1
+ XXX.datafix.schemas.V3808_2
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
+ XXX.datafix.schemas.V4292
- XXX.datafix.schemas.V4300
+ XXX.datafix.schemas.V4301
- XXX.datafix.schemas.V4302
+ XXX.datafix.schemas.V4306
- XXX.datafix.schemas.V4307
+ XXX.datafix.schemas.V4312
- XXX.datafix.schemas.V4420
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
- XXX.enchantment.effects.AddValue
+ XXX.enchantment.effects.AllOf
- XXX.enchantment.effects.AllOf$EntityEffects
+ XXX.enchantment.effects.AllOf$LocationBasedEffects
- XXX.enchantment.effects.AllOf$ValueEffects
+ XXX.enchantment.effects.ApplyMobEffect
- XXX.enchantment.effects.ChangeItemDamage
+ XXX.enchantment.effects.DamageEntity
- XXX.enchantment.effects.DamageImmunity
+ XXX.enchantment.effects.EnchantmentAttributeEffect
- XXX.enchantment.effects.EnchantmentEntityEffect
+ XXX.enchantment.effects.EnchantmentLocationBasedEffect
- XXX.enchantment.effects.EnchantmentValueEffect
+ XXX.enchantment.effects.ExplodeEffect
- XXX.enchantment.effects.Ignite
+ XXX.enchantment.effects.MultiplyValue
+ XXX.enchantment.effects.package-info
- XXX.enchantment.effects.PlaySoundEffect
+ XXX.enchantment.effects.RemoveBinomial
- XXX.enchantment.effects.ReplaceBlock
+ XXX.enchantment.effects.ReplaceDisk
- XXX.enchantment.effects.RunFunction
+ XXX.enchantment.effects.SetBlockProperties
- XXX.enchantment.effects.SetValue
+ XXX.enchantment.effects.SpawnParticlesEffect
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
+ XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
- XXX.enchantment.effects.SummonEntityEffect
+ XXX.enchantment.providers.EnchantmentProvider
- XXX.enchantment.providers.EnchantmentProviderTypes
+ XXX.enchantment.providers.EnchantmentsByCost
- XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
- XXX.enchantment.providers.package-info
+ XXX.enchantment.providers.SingleEnchantment
- XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
+ XXX.enchantment.providers.VanillaEnchantmentProviders
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
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractCow
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
+ XXX.entity.animal.CatVariants
- XXX.entity.animal.Chicken
+ XXX.entity.animal.ChickenVariant
- XXX.entity.animal.ChickenVariant$ModelType
+ XXX.entity.animal.ChickenVariants
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.CowVariant
+ XXX.entity.animal.CowVariant$ModelType
- XXX.entity.animal.CowVariants
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
- XXX.entity.animal.Fox$Variant
- XXX.entity.animal.HappyGhast$BabyFlyingPathNavigation
- XXX.entity.animal.HappyGhast$HappyGhastFloatGoal
- XXX.entity.animal.HappyGhastAi
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
+ XXX.entity.animal.PigVariant
- XXX.entity.animal.PigVariant$ModelType
+ XXX.entity.animal.PigVariants
- XXX.entity.animal.PolarBear
+ XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
- XXX.entity.animal.Rabbit$RabbitGroupData
+ XXX.entity.animal.Rabbit$RabbitJumpControl
- XXX.entity.animal.Rabbit$RabbitMoveControl
+ XXX.entity.animal.Rabbit$RabbitPanicGoal
- XXX.entity.animal.Rabbit$RaidGardenGoal
+ XXX.entity.animal.Rabbit$Variant
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Salmon$Variant
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TemperatureVariants
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
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
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
- XXX.entity.layers.CustomHeadLayer$Transforms
+ XXX.entity.layers.Deadmau5EarsLayer
- XXX.entity.layers.DolphinCarryingItemLayer
+ XXX.entity.layers.DrownedOuterLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EquipmentLayerRenderer
+ XXX.entity.layers.EquipmentLayerRenderer$LayerTextureKey
- XXX.entity.layers.EquipmentLayerRenderer$TrimSpriteKey
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LivingEntityEmissiveLayer
- XXX.entity.layers.LivingEntityEmissiveLayer$AlphaFunction
+ XXX.entity.layers.LivingEntityEmissiveLayer$DrawSelector
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SheepWoolLayer
- XXX.entity.layers.SheepWoolUndercoatLayer
+ XXX.entity.layers.SimpleEquipmentLayer
- XXX.entity.layers.SkeletonClothingLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StuckInBodyLayer
- XXX.entity.layers.StuckInBodyLayer$PlacementStyle
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.TropicalFishPatternLayer$1
+ XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.layers.WingsLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfArmorLayer
- XXX.entity.layers.WolfCollarLayer
+ XXX.entity.layers.WolfHeldItemLayer
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.AngryGhast
+ XXX.entity.monster.AngryGhast$AngryGhastMoveControl
+ XXX.entity.monster.AngryGhast$FloatTowardsPlayerGoal
+ XXX.entity.pets.AbstractPet
+ XXX.entity.pets.PetArmadillo$1
+ XXX.entity.pets.PetAxolotl
+ XXX.entity.pets.PetAxolotl$AxolotlGroupData
+ XXX.entity.pets.PetAxolotl$AxolotlMoveControl
+ XXX.entity.pets.PetBee$1
+ XXX.entity.pets.PetBee$BeeBecomeAngryTargetGoal
+ XXX.entity.pets.PetBee$BeeLookControl
+ XXX.entity.pets.PetChicken
+ XXX.entity.pets.PetCreeper
+ XXX.entity.pets.PetFox$FoxGroupData
+ XXX.entity.pets.PetFox$FoxMoveControl
+ XXX.entity.pets.PetFrog$FrogLookControl
+ XXX.entity.pets.PetFrog$FrogPathNavigation
+ XXX.entity.pets.PetPolarBear
+ XXX.entity.pets.PetPolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.pets.PetSlime
+ XXX.entity.pets.PetSlime$SlimeKeepOnJumpingGoal
+ XXX.entity.pets.PetTurtle
+ XXX.entity.pets.PetTurtle$TurtleMoveControl
+ XXX.entity.pets.PetWolf
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
- XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerEquipment
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$IngredientInfo
+ XXX.entity.player.StackedContents$Output
- XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.player.StackedItemContents
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.AbstractThrownPotion
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
- XXX.entity.projectile.package-info
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
- XXX.entity.projectile.ThrownLingeringPotion
+ XXX.entity.projectile.ThrownSplashPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
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
+ XXX.entity.raid.Raids$RaidWithId
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.state.HappyGhastRenderState
- XXX.entity.state.HitboxesRenderState
+ XXX.entity.state.HitboxRenderState
+ XXX.entity.state.HoglinRenderState
- XXX.entity.state.HoldingEntityRenderState
+ XXX.entity.state.HorseRenderState
- XXX.entity.state.HumanoidRenderState
+ XXX.entity.state.IllagerRenderState
- XXX.entity.state.IllusionerRenderState
+ XXX.entity.state.IronGolemRenderState
- XXX.entity.state.ItemClusterRenderState
+ XXX.entity.state.ItemDisplayEntityRenderState
- XXX.entity.state.ItemEntityRenderState
+ XXX.entity.state.ItemFrameRenderState
- XXX.entity.state.LightningBoltRenderState
+ XXX.entity.state.LivingEntityRenderState
- XXX.entity.state.LlamaRenderState
+ XXX.entity.state.LlamaSpitRenderState
- XXX.entity.state.MinecartRenderState
+ XXX.entity.state.MinecartTntRenderState
- XXX.entity.state.MushroomCowRenderState
+ XXX.entity.state.package-info
+ XXX.entity.state.PaintingRenderState
- XXX.entity.state.PandaRenderState
+ XXX.entity.state.ParrotRenderState
- XXX.entity.state.PhantomRenderState
- XXX.entity.state.PiglinRenderState
+ XXX.entity.state.PigRenderState
+ XXX.entity.state.PlayerRenderState
- XXX.entity.state.PolarBearRenderState
+ XXX.entity.state.PufferfishRenderState
- XXX.entity.state.RabbitRenderState
+ XXX.entity.state.RavagerRenderState
- XXX.entity.state.SalmonRenderState
+ XXX.entity.state.ServerHitboxesRenderState
- XXX.entity.state.SheepRenderState
+ XXX.entity.state.ShulkerBulletRenderState
- XXX.entity.state.ShulkerRenderState
+ XXX.entity.state.SkeletonRenderState
- XXX.entity.state.SlimeRenderState
+ XXX.entity.state.SnifferRenderState
- XXX.entity.state.SnowGolemRenderState
+ XXX.entity.state.SquidRenderState
- XXX.entity.state.StriderRenderState
+ XXX.entity.state.TextDisplayEntityRenderState
- XXX.entity.state.ThrownItemRenderState
+ XXX.entity.state.ThrownTridentRenderState
- XXX.entity.state.TippableArrowRenderState
+ XXX.entity.state.TntRenderState
- XXX.entity.state.TropicalFishRenderState
+ XXX.entity.state.TurtleRenderState
- XXX.entity.state.VexRenderState
+ XXX.entity.state.VillagerDataHolderRenderState
- XXX.entity.state.VillagerRenderState
+ XXX.entity.state.WardenRenderState
- XXX.entity.state.WitchRenderState
+ XXX.entity.state.WitherRenderState
- XXX.entity.state.WitherSkullRenderState
+ XXX.entity.state.WolfRenderState
- XXX.entity.state.ZombieRenderState
+ XXX.entity.state.ZombieVillagerRenderState
- XXX.entity.state.ZombifiedPiglinRenderState
- XXX.entity.variant.BiomeCheck
+ XXX.entity.variant.ModelAndTexture
- XXX.entity.variant.MoonBrightnessCheck
+ XXX.entity.variant.package-info
+ XXX.entity.variant.PriorityProvider
- XXX.entity.variant.PriorityProvider$Selector
+ XXX.entity.variant.PriorityProvider$SelectorCondition
- XXX.entity.variant.PriorityProvider$UnpackedEntry
+ XXX.entity.variant.SpawnCondition
- XXX.entity.variant.SpawnConditions
+ XXX.entity.variant.SpawnContext
- XXX.entity.variant.SpawnPrioritySelectors
+ XXX.entity.variant.StructureCheck
- XXX.entity.variant.VariantUtils
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
+ XXX.equipment.trim.MaterialAssetGroup
- XXX.equipment.trim.MaterialAssetGroup$AssetInfo
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
- XXX.execution.tasks.BuildContexts
+ XXX.execution.tasks.BuildContexts$Continuation
- XXX.execution.tasks.BuildContexts$TopLevel
+ XXX.execution.tasks.BuildContexts$Unbound
- XXX.execution.tasks.CallFunction
+ XXX.execution.tasks.ContinuationTask
- XXX.execution.tasks.ContinuationTask$TaskProvider
+ XXX.execution.tasks.ExecuteCommand
- XXX.execution.tasks.FallthroughTask
+ XXX.execution.tasks.IsolatedCall
- XXX.execution.tasks.package-info
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FallenTreeConfiguration
+ XXX.feature.configurations.FallenTreeConfiguration$FallenTreeConfigurationBuilder
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
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
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractContainerWidget
+ XXX.gui.components.AbstractOptionSliderButton
- XXX.gui.components.AbstractScrollArea
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractStringWidget
+ XXX.gui.components.AbstractTextAreaWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$Builder
+ XXX.gui.components.Button$CreateNarration
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.ChatComponent$State
- XXX.gui.components.Checkbox
+ XXX.gui.components.Checkbox$Builder
- XXX.gui.components.Checkbox$OnValueChange
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
- XXX.gui.components.FittingMultiLineTextWidget
+ XXX.gui.components.FocusableTextWidget
- XXX.gui.components.ImageButton
+ XXX.gui.components.ImageWidget
- XXX.gui.components.ImageWidget$Sprite
+ XXX.gui.components.ImageWidget$Texture
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LoadingDotsWidget
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.LogoRenderer
+ XXX.gui.components.MultiLineEditBox
- XXX.gui.components.MultiLineLabel
+ XXX.gui.components.MultiLineLabel$1
- XXX.gui.components.MultiLineLabel$2
+ XXX.gui.components.MultiLineLabel$TextAndWidth
- XXX.gui.components.MultilineTextField
+ XXX.gui.components.MultilineTextField$1
- XXX.gui.components.MultilineTextField$StringView
- XXX.gui.components.MultiLineTextWidget
+ XXX.gui.components.MultiLineTextWidget$CacheKey
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.OptionsList$OptionEntry
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerSkinWidget
+ XXX.gui.components.PlayerSkinWidget$Model
- XXX.gui.contextualbar.ContextualBarRenderer$1
- XXX.gui.contextualbar.JumpableVehicleBarRenderer
- XXX.gui.render.GuiLayer
- XXX.gui.render.GuiRenderer$AtlasPosition
- XXX.gui.render.TextureSetup
+ XXX.gui.screens.AccessibilityOnboardingScreen
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
- XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PauseScreen$FeedbackSubScreen
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.ReceivingLevelScreen$Reason
+ XXX.gui.screens.RecoverWorldDataScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$DeferredTooltipRendering
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
- XXX.gui.spectator.package-info
- XXX.gui.spectator.PlayerMenuItem
+ XXX.gui.spectator.RootSpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenu
+ XXX.gui.spectator.SpectatorMenu$1
- XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
- XXX.gui.spectator.SpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenuItem
- XXX.gui.spectator.SpectatorMenuListener
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.ClientActivePlayersTooltip
+ XXX.inventory.tooltip.ClientActivePlayersTooltip$ActivePlayersTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.ClientTooltipPositioner
- XXX.inventory.tooltip.DefaultTooltipPositioner
+ XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.inventory.tooltip.TooltipRenderUtil
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
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
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
- XXX.item.component.ItemAttributeModifiers$Display$Default
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
+ XXX.item.component.package-info
- XXX.item.component.ProvidesTrimMaterial
+ XXX.item.component.ResolvableProfile
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect$Type
+ XXX.item.consume_effects.package-info
- XXX.item.consume_effects.PlaySoundConsumeEffect
+ XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
+ XXX.item.crafting.AbstractCookingRecipe$Serializer
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BlastingRecipe$1
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CraftingRecipe$1
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.CustomRecipe$Serializer
- XXX.item.crafting.CustomRecipe$Serializer$Factory
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.ExtendedRecipeBookCategory
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
+ XXX.item.crafting.PlacementInfo
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeAccess
- XXX.item.crafting.RecipeBookCategories
+ XXX.item.crafting.RecipeBookCategory
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeInput
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeManager$IngredientCollector
- XXX.item.crafting.RecipeManager$IngredientExtractor
+ XXX.item.crafting.RecipeManager$ServerDisplayInfo
- XXX.item.crafting.RecipeMap
+ XXX.item.crafting.RecipePropertySet
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.SelectableRecipe
+ XXX.item.crafting.SelectableRecipe$SingleInputEntry
- XXX.item.crafting.SelectableRecipe$SingleInputSet
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapedRecipePattern
- XXX.item.crafting.ShapedRecipePattern$Data
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Factory
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleRecipeInput
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmeltingRecipe$1
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingRecipeInput
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.TransmuteRecipe
- XXX.item.crafting.TransmuteRecipe$Serializer
+ XXX.item.crafting.TransmuteResult
- XXX.item.enchantment.ConditionalEffect
+ XXX.item.enchantment.Enchantable
- XXX.item.enchantment.EnchantedItemInUse
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$1
+ XXX.item.enchantment.Enchantment$Builder
- XXX.item.enchantment.Enchantment$Cost
+ XXX.item.enchantment.Enchantment$EnchantmentDefinition
- XXX.item.enchantment.EnchantmentEffectComponents
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.EnchantmentTarget
+ XXX.item.enchantment.ItemEnchantments
- XXX.item.enchantment.ItemEnchantments$Mutable
+ XXX.item.enchantment.LevelBasedValue
- XXX.item.enchantment.LevelBasedValue$Clamped
+ XXX.item.enchantment.LevelBasedValue$Constant
- XXX.item.enchantment.LevelBasedValue$Fraction
+ XXX.item.enchantment.LevelBasedValue$LevelsSquared
- XXX.item.enchantment.LevelBasedValue$Linear
+ XXX.item.enchantment.LevelBasedValue$Lookup
- XXX.item.enchantment.package-info
- XXX.item.enchantment.Repairable
+ XXX.item.enchantment.TargetedConditionalEffect
+ XXX.item.equipment.AllowedEntitiesProvider
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.properties.package-info
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
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
+ XXX.level.biome.ClimateSettings$Builder
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
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$3
+ XXX.level.block.DimensionControlBlock
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
- XXX.level.block.DriedGhastBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.MineCrafterBlock
+ XXX.level.block.MineTravellingBlock
- XXX.level.block.Mirror
+ XXX.level.block.MobTrophyBlock
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
- XXX.level.block.PiglinWallSkullBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
+ XXX.level.block.PitcherCropBlock$1
- XXX.level.block.PitcherCropBlock$PosAndState
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
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
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.SandBlock
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
- XXX.level.block.SegmentableBlock
+ XXX.level.block.ShimmeringDoorBlock
+ XXX.level.block.TestBlock
- XXX.level.block.TestInstanceBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TintedParticleLeavesBlock
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
+ XXX.level.block.TrophyType
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.UntintedParticleLeavesBlock
- XXX.level.block.VaultBlock
+ XXX.level.block.VegetationBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
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
+ XXX.level.chunk.GridChunkGenerator
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$PostLoadProcessor
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunk$UnsavedListener
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LevelChunkSection$1BlockCounter
+ XXX.level.chunk.LightChunk
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.MissingPaletteEntryException
+ XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
- XXX.level.chunk.Palette$Factory
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$Configuration
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainer$Strategy
+ XXX.level.chunk.PalettedContainer$Strategy$1
- XXX.level.chunk.PalettedContainer$Strategy$2
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.StructureAccess
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionSpecialEffects$CodeSky
+ XXX.level.dimension.DimensionSpecialEffects$EndSky
+ XXX.level.dimension.DimensionSpecialEffects$FogScaler$1
+ XXX.level.dimension.DimensionSpecialEffects$FogScaler$3
+ XXX.level.dimension.DimensionSpecialEffects$Panorama
+ XXX.level.dimension.DimensionSpecialEffects$SkyType
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.DimensionType$MonsterSettings
- XXX.level.dimension.LevelStem
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
+ XXX.level.entity.EntityTypeTest$2
- XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetter
- XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.UniquelyIdentifyable
- XXX.level.entity.UUIDLookup
- XXX.level.entity.Visibility
- XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.BlockPositionSource$Type
- XXX.level.gameevent.DynamicGameEventListener
+ XXX.level.gameevent.EntityPositionSource
- XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry
- XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListener$Provider
- XXX.level.gameevent.GameEventListenerRegistry
+ XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
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
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
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
+ XXX.level.mines.Battle
+ XXX.level.mines.Battle$SpawnGroup
+ XXX.level.mines.Battle$SpawnStrategy
+ XXX.level.mines.Battle$SpawnType
+ XXX.level.mines.Battle$Wave$Builder
+ XXX.level.mines.EndDragonBattle
+ XXX.level.mines.MineEvent$Status
+ XXX.level.mines.MineSpawnStrategy
+ XXX.level.mines.package-info
+ XXX.level.mines.RandomizationMode
+ XXX.level.mines.SpecialMine$Builder
+ XXX.level.mines.UnlockMode
+ XXX.level.mines.WorldEffect$Builder
+ XXX.level.mines.WorldEffectSet
+ XXX.level.mines.WorldGenBuilder
+ XXX.level.mines.WorldGenBuilder$ModifiedBiome
+ XXX.level.mines.WorldGenEffect
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.BlendingData$Packed
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
+ XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.UnobstructedPredicate
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
+ XXX.levelgen.feature.EndPlatformFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.FallenTreeFeature
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
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TreeFeature$1
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
- XXX.loot.packs.package-info
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
- XXX.metadata.animation.VillagerMetadataSection
+ XXX.metadata.animation.VillagerMetadataSection$Hat
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
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.minecraft.advancements.DisplayInfo$Builder
- XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.TreeNodePosition
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
- XXX.minecraft.client.package-info
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
+ XXX.minecraft.commands.package-info
- XXX.minecraft.commands.ParserUtils
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.core.AxisCycle
- XXX.minecraft.core.AxisCycle$1
+ XXX.minecraft.core.AxisCycle$2
- XXX.minecraft.core.AxisCycle$3
+ XXX.minecraft.core.BlockBox
- XXX.minecraft.core.BlockBox$1
+ XXX.minecraft.core.BlockMath
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$4
+ XXX.minecraft.core.BlockPos$5
- XXX.minecraft.core.BlockPos$6
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockPos$TraversalNodeStatus
+ XXX.minecraft.core.ClientAsset
- XXX.minecraft.core.Cloner
+ XXX.minecraft.core.Cloner$Factory
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedMappedRegistry
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
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
+ XXX.minecraft.core.HolderLookup$RegistryLookup
- XXX.minecraft.core.HolderLookup$RegistryLookup$1
+ XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
- XXX.minecraft.core.HolderOwner
+ XXX.minecraft.core.HolderSet
- XXX.minecraft.core.HolderSet$1
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LayeredRegistryAccess
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.MappedRegistry$1
+ XXX.minecraft.core.MappedRegistry$2
- XXX.minecraft.core.MappedRegistry$3
+ XXX.minecraft.core.MappedRegistry$TagSet
- XXX.minecraft.core.MappedRegistry$TagSet$1
+ XXX.minecraft.core.MappedRegistry$TagSet$2
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.QuartPos
+ XXX.minecraft.core.RegistrationInfo
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$PendingTags
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistrySetBuilder
+ XXX.minecraft.core.RegistrySetBuilder$1
- XXX.minecraft.core.RegistrySetBuilder$1Entry
+ XXX.minecraft.core.RegistrySetBuilder$2
- XXX.minecraft.core.RegistrySetBuilder$3
+ XXX.minecraft.core.RegistrySetBuilder$3$1
- XXX.minecraft.core.RegistrySetBuilder$BuildState
+ XXX.minecraft.core.RegistrySetBuilder$BuildState$1
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
+ XXX.minecraft.core.RegistrySetBuilder$LazyHolder
- XXX.minecraft.core.RegistrySetBuilder$PatchedRegistries
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryStub
+ XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
- XXX.minecraft.core.RegistrySetBuilder$UniversalOwner
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$PackedRegistryEntry
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.Rotations$1
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.UUIDUtil
+ XXX.minecraft.core.UUIDUtil$1
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
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
+ XXX.minecraft.data.package-info
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
- XXX.minecraft.network.package-info
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipeHelper
+ XXX.minecraft.recipebook.PlaceRecipeHelper$Output
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe$CraftingMenuAccess
+ XXX.minecraft.references.Blocks
- XXX.minecraft.references.Items
+ XXX.minecraft.references.package-info
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.DelegatingOps$DelegateListBuilder
- XXX.minecraft.resources.DelegatingOps$DelegateRecordBuilder
+ XXX.minecraft.resources.DependantName
- XXX.minecraft.resources.FileToIdConverter
+ XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader
+ XXX.minecraft.resources.RegistryDataLoader$1
- XXX.minecraft.resources.RegistryDataLoader$Loader
+ XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
- XXX.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$HolderLookupAdapter
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
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
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.PackStuff
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$Data
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerRegistries
- XXX.minecraft.server.ReloadableServerRegistries$Holder
+ XXX.minecraft.server.ReloadableServerRegistries$LoadResult
- XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerInfo
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerLinks
- XXX.minecraft.server.ServerLinks$Entry
+ XXX.minecraft.server.ServerLinks$KnownLinkType
- XXX.minecraft.server.ServerLinks$UntrustedEntry
+ XXX.minecraft.server.ServerPlayerUnlocks
+ XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.TheGame$1
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
+ XXX.minecraft.world.MineData
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
- XXX.model.multipart.CombinedCondition
+ XXX.model.multipart.CombinedCondition$Operation
- XXX.model.multipart.CombinedCondition$Operation$1
+ XXX.model.multipart.CombinedCondition$Operation$2
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.KeyValueCondition$Term
+ XXX.model.multipart.KeyValueCondition$Terms
- XXX.model.multipart.MultiPartModel
+ XXX.model.multipart.MultiPartModel$Selector
- XXX.model.multipart.MultiPartModel$SharedBakedState
+ XXX.model.multipart.MultiPartModel$Unbaked
- XXX.model.multipart.MultiPartModel$Unbaked$1
+ XXX.model.multipart.MultiPartModel$Unbaked$1Key
+ XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.mojang.blaze3d.package-info
+ XXX.multiplayer.chat.ChatListener
- XXX.multiplayer.chat.ChatListener$Message
+ XXX.multiplayer.chat.ChatLog
- XXX.multiplayer.chat.ChatTrustLevel
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatEvent$Type
+ XXX.multiplayer.chat.LoggedChatMessage
- XXX.multiplayer.chat.LoggedChatMessage$Player
+ XXX.multiplayer.chat.LoggedChatMessage$System
- XXX.multiplayer.chat.package-info
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
- XXX.network.codec.ByteBufCodecs$4
+ XXX.network.codec.ByteBufCodecs$5
- XXX.network.codec.ByteBufCodecs$6
+ XXX.network.codec.ByteBufCodecs$7
- XXX.network.codec.ByteBufCodecs$8
+ XXX.network.codec.ByteBufCodecs$9
- XXX.network.codec.IdDispatchCodec
+ XXX.network.codec.IdDispatchCodec$Builder
- XXX.network.codec.IdDispatchCodec$DontDecorateException
+ XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.package-info
- XXX.network.codec.StreamCodec
+ XXX.network.codec.StreamCodec$1
- XXX.network.codec.StreamCodec$10
+ XXX.network.codec.StreamCodec$11
- XXX.network.codec.StreamCodec$12
+ XXX.network.codec.StreamCodec$13
- XXX.network.codec.StreamCodec$14
+ XXX.network.codec.StreamCodec$15
- XXX.network.codec.StreamCodec$16
+ XXX.network.codec.StreamCodec$2
- XXX.network.codec.StreamCodec$3
+ XXX.network.codec.StreamCodec$4
- XXX.network.codec.StreamCodec$5
+ XXX.network.codec.StreamCodec$6
- XXX.network.codec.StreamCodec$7
+ XXX.network.codec.StreamCodec$8
- XXX.network.codec.StreamCodec$9
+ XXX.network.codec.StreamCodec$CodecOperation
- XXX.network.codec.StreamDecoder
+ XXX.network.codec.StreamEncoder
- XXX.network.codec.StreamMemberEncoder
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$1$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.CodecModifier
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$2
- XXX.network.protocol.ProtocolInfoBuilder$3
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.network.protocol.SimpleUnboundProtocol
- XXX.network.protocol.UnboundProtocol
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.package-info
+ XXX.network.syncher.SyncedDataHolder
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$Builder
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
+ XXX.options.controls.ControlsScreen
- XXX.options.controls.KeyBindsList
+ XXX.options.controls.KeyBindsList$CategoryEntry
- XXX.options.controls.KeyBindsList$CategoryEntry$1
+ XXX.options.controls.KeyBindsList$Entry
- XXX.options.controls.KeyBindsList$KeyEntry
+ XXX.options.controls.KeyBindsScreen
- XXX.options.controls.package-info
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
+ XXX.player.inventory.Hotbar
- XXX.player.inventory.package-info
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.package-info
+ XXX.projectile.windcharge.WindCharge
+ XXX.properties.conditional.Broken
- XXX.properties.conditional.BundleHasSelectedItem
+ XXX.properties.conditional.ComponentMatches
- XXX.properties.conditional.ConditionalItemModelProperties
+ XXX.properties.conditional.ConditionalItemModelProperty
- XXX.properties.conditional.CustomModelDataProperty
+ XXX.properties.conditional.Damaged
- XXX.properties.conditional.ExtendedView
+ XXX.properties.conditional.FishingRodCast
- XXX.properties.conditional.HasComponent
+ XXX.properties.conditional.IsCarried
- XXX.properties.conditional.IsKeybindDown
+ XXX.properties.conditional.IsSelected
- XXX.properties.conditional.IsUsingItem
+ XXX.properties.conditional.IsViewEntity
- XXX.properties.conditional.ItemModelPropertyTest
+ XXX.properties.conditional.package-info
- XXX.properties.numeric.BundleFullness
+ XXX.properties.numeric.CompassAngle
- XXX.properties.numeric.CompassAngleState
+ XXX.properties.numeric.CompassAngleState$CompassTarget
- XXX.properties.numeric.CompassAngleState$CompassTarget$1
+ XXX.properties.numeric.CompassAngleState$CompassTarget$2
- XXX.properties.numeric.CompassAngleState$CompassTarget$3
+ XXX.properties.numeric.CompassAngleState$CompassTarget$4
- XXX.properties.numeric.Cooldown
+ XXX.properties.numeric.Count
- XXX.properties.numeric.CrossbowPull
+ XXX.properties.numeric.CustomModelDataProperty
- XXX.properties.numeric.Damage
+ XXX.properties.numeric.NeedleDirectionHelper
- XXX.properties.numeric.NeedleDirectionHelper$1
+ XXX.properties.numeric.NeedleDirectionHelper$2
- XXX.properties.numeric.NeedleDirectionHelper$Wobbler
- XXX.properties.numeric.package-info
+ XXX.properties.numeric.RangeSelectItemModelProperties
- XXX.properties.numeric.RangeSelectItemModelProperty
+ XXX.properties.numeric.Time
- XXX.properties.numeric.Time$TimeSource
+ XXX.properties.numeric.Time$TimeSource$1
- XXX.properties.numeric.Time$TimeSource$2
+ XXX.properties.numeric.Time$TimeSource$3
- XXX.properties.numeric.UseCycle
+ XXX.properties.numeric.UseDuration
- XXX.properties.select.Charge
+ XXX.properties.select.ComponentContents
- XXX.properties.select.ContextDimension
+ XXX.properties.select.ContextEntityType
- XXX.properties.select.CustomModelDataProperty
+ XXX.properties.select.DisplayContext
- XXX.properties.select.ItemBlockState
+ XXX.properties.select.LocalTime
- XXX.properties.select.LocalTime$Data
+ XXX.properties.select.MainHand
- XXX.properties.select.package-info
- XXX.properties.select.SelectItemModelProperties
+ XXX.properties.select.SelectItemModelProperty
- XXX.properties.select.SelectItemModelProperty$Type
+ XXX.properties.select.TrimMaterialProperty
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
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockChangedAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$AddOperation
- XXX.protocol.game.ClientboundBossEventPacket$Handler
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundBossEventPacket$OperationType
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundBundleDelimiterPacket
- XXX.protocol.game.ClientboundBundlePacket
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
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
- XXX.protocol.game.ClientboundPlayerRotationPacket
+ XXX.protocol.game.ClientboundProjectilePowerPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
- XXX.protocol.game.ClientboundRecipeBookRemovePacket
+ XXX.protocol.game.ClientboundRecipeBookSettingsPacket
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResetScorePacket
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
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetCursorItemPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetHeldSlotPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerInventoryPacket
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
+ XXX.protocol.game.ClientboundStartConfigurationPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundTestInstanceBlockStatus
+ XXX.protocol.game.ClientboundTickingStatePacket
- XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdatePlayerUnlocksPacket
+ XXX.protocol.game.ClientboundUpdateScreenPacket
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundPlayerBuyUnlockPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerReactivateUnlockPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectBundleItemPacket
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSetTestBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.HandshakePacketTypes
+ XXX.protocol.handshake.HandshakeProtocols
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientboundLoginFinishedPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.LoginPacketTypes
+ XXX.protocol.login.LoginProtocols
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryAnswerPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerboundLoginAcknowledgedPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.ping.ClientboundPongResponsePacket
- XXX.protocol.ping.ClientPongPacketListener
+ XXX.protocol.ping.package-info
- XXX.protocol.ping.PingPacketTypes
- XXX.protocol.ping.ServerboundPingRequestPacket
+ XXX.protocol.ping.ServerPingPacketListener
+ XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.protocol.status.StatusPacketTypes
+ XXX.protocol.status.StatusProtocols
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$Runner
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.render.pip.GuiBannerResultRenderer
- XXX.render.pip.GuiEntityRenderer
- XXX.render.pip.GuiSignRenderer
- XXX.render.pip.PictureInPictureRenderer
- XXX.render.state.BlitRenderState
- XXX.render.state.GlyphRenderState
- XXX.render.state.GuiItemRenderState
- XXX.render.state.GuiTextRenderState
- XXX.render.state.package-info
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.LiquidBlockRenderer
- XXX.renderer.block.LiquidBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionRenderStorage
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$CommonRenderStorage
- XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.AbstractSignRenderer
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider
- XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.blockentity.BlockEntityRenderers
- XXX.renderer.blockentity.BlockEntityWithBoundingBoxRenderer
+ XXX.renderer.blockentity.BrightnessCombiner
- XXX.renderer.blockentity.BrushableBlockRenderer
+ XXX.renderer.blockentity.BrushableBlockRenderer$1
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
+ XXX.renderer.blockentity.HangingSignRenderer$ModelKey
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.MineTravellingBlockEntityRenderer
- XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$Models
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SkullBlockRenderer$1
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.TestInstanceRenderer
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.blockentity.TrialSpawnerRenderer
+ XXX.renderer.blockentity.VaultRenderer
+ XXX.renderer.chunk.CompileTaskDynamicQueue
- XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunk
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderRegionCache$ChunkInfo
- XXX.renderer.chunk.SectionCompiler
+ XXX.renderer.chunk.SectionCompiler$Results
- XXX.renderer.chunk.SectionRenderDispatcher
+ XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
+ XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$2
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
- XXX.renderer.chunk.SectionRenderDispatcher$SectionBuffers
+ XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
- XXX.renderer.chunk.SectionRenderDispatcher$TranslucencyPointOfView
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
+ XXX.renderer.debug.ChunkCullingDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.LightSectionDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer$SectionData
+ XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.OctreeDebugRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.RedstoneWireOrientationsRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.SupportBlockRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractBoatRenderer
- XXX.renderer.entity.AbstractHoglinRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractMinecartRenderer
+ XXX.renderer.entity.AbstractSkeletonRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AgeableMobRenderer
- XXX.renderer.entity.AllayRenderer
+ XXX.renderer.entity.AngryGhastRenderer
- XXX.renderer.entity.HoglinRenderer
+ XXX.renderer.entity.HorseRenderer
- XXX.renderer.entity.HumanoidMobRenderer
+ XXX.renderer.entity.HuskRenderer
- XXX.renderer.entity.IllagerRenderer
+ XXX.renderer.entity.IllusionerRenderer
- XXX.renderer.entity.IllusionerRenderer$1
+ XXX.renderer.entity.IronGolemRenderer
- XXX.renderer.entity.ItemEntityRenderer
+ XXX.renderer.entity.ItemFrameRenderer
- XXX.renderer.entity.ItemRenderer
+ XXX.renderer.entity.LeashKnotRenderer
- XXX.renderer.entity.LightningBoltRenderer
+ XXX.renderer.entity.LivingEntityRenderer
- XXX.renderer.entity.LivingEntityRenderer$1
+ XXX.renderer.entity.LlamaRenderer
- XXX.renderer.entity.LlamaRenderer$1
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.OminousItemSpawnerRenderer
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PaintingRenderer$1
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PetAxolotlRenderer
+ XXX.renderer.entity.PetCatRenderer
+ XXX.renderer.entity.PetCowRenderer
+ XXX.renderer.entity.PetFoxRenderer
+ XXX.renderer.entity.PetMushroomCowRenderer
+ XXX.renderer.entity.PetSlimeRenderer
+ XXX.renderer.entity.PetWolfRenderer
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RabbitRenderer$1
- XXX.renderer.entity.RaftRenderer
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
+ XXX.renderer.entity.UndeadHorseRenderer$Type
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WardenRenderer
- XXX.renderer.entity.WindChargeRenderer
+ XXX.renderer.entity.WitchRenderer
- XXX.renderer.entity.WitherBossRenderer
+ XXX.renderer.entity.WitherSkeletonRenderer
- XXX.renderer.entity.WitherSkullRenderer
+ XXX.renderer.entity.WolfRenderer
- XXX.renderer.entity.ZoglinRenderer
+ XXX.renderer.entity.ZombieRenderer
- XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.entity.ZombifiedPiglinRenderer
- XXX.renderer.item.BlockModelWrapper
+ XXX.renderer.item.BlockModelWrapper$Unbaked
- XXX.renderer.item.BundleSelectedItemSpecialRenderer
+ XXX.renderer.item.BundleSelectedItemSpecialRenderer$Unbaked
- XXX.renderer.item.ClientItem
+ XXX.renderer.item.ClientItem$Properties
- XXX.renderer.item.CompositeModel
+ XXX.renderer.item.CompositeModel$Unbaked
- XXX.renderer.item.ConditionalItemModel
+ XXX.renderer.item.ConditionalItemModel$Unbaked
- XXX.renderer.item.EmptyModel
+ XXX.renderer.item.EmptyModel$Unbaked
- XXX.renderer.item.ItemModel
+ XXX.renderer.item.ItemModel$BakingContext
- XXX.renderer.item.ItemModel$Unbaked
+ XXX.renderer.item.ItemModelResolver
- XXX.renderer.item.ItemModels
+ XXX.renderer.item.ItemStackRenderState
- XXX.renderer.item.ItemStackRenderState$FoilType
+ XXX.renderer.item.ItemStackRenderState$LayerRenderState
+ XXX.renderer.item.MineIngredientModel$Unbaked
- XXX.renderer.item.MissingItemModel
+ XXX.renderer.item.ModelRenderProperties
- XXX.renderer.item.package-info
- XXX.renderer.item.RangeSelectItemModel
+ XXX.renderer.item.RangeSelectItemModel$Entry
- XXX.renderer.item.RangeSelectItemModel$Unbaked
+ XXX.renderer.item.SelectItemModel
- XXX.renderer.item.SelectItemModel$ModelSelector
+ XXX.renderer.item.SelectItemModel$SwitchCase
- XXX.renderer.item.SelectItemModel$Unbaked
+ XXX.renderer.item.SelectItemModel$UnbakedSwitch
- XXX.renderer.item.SpecialModelWrapper
+ XXX.renderer.item.SpecialModelWrapper$Unbaked
- XXX.renderer.special.BannerSpecialRenderer
+ XXX.renderer.special.BannerSpecialRenderer$Unbaked
- XXX.renderer.special.BedSpecialRenderer
+ XXX.renderer.special.BedSpecialRenderer$Unbaked
- XXX.renderer.special.ChestSpecialRenderer
+ XXX.renderer.special.ChestSpecialRenderer$Unbaked
- XXX.renderer.special.ConduitSpecialRenderer
+ XXX.renderer.special.ConduitSpecialRenderer$Unbaked
- XXX.renderer.special.DecoratedPotSpecialRenderer
+ XXX.renderer.special.DecoratedPotSpecialRenderer$Unbaked
- XXX.renderer.special.HangingSignSpecialRenderer
+ XXX.renderer.special.HangingSignSpecialRenderer$Unbaked
+ XXX.renderer.special.MobTrophySpecialRenderer$Unbaked
- XXX.renderer.special.NoDataSpecialModelRenderer
- XXX.renderer.special.package-info
+ XXX.renderer.special.ShieldSpecialRenderer
- XXX.renderer.special.ShieldSpecialRenderer$Unbaked
+ XXX.renderer.special.ShulkerBoxSpecialRenderer
- XXX.renderer.special.ShulkerBoxSpecialRenderer$Unbaked
+ XXX.renderer.special.SkullSpecialRenderer
- XXX.renderer.special.SkullSpecialRenderer$Unbaked
+ XXX.renderer.special.SpecialModelRenderer
- XXX.renderer.special.SpecialModelRenderer$Unbaked
+ XXX.renderer.special.SpecialModelRenderers
- XXX.renderer.special.StandingSignSpecialRenderer
+ XXX.renderer.special.StandingSignSpecialRenderer$Unbaked
- XXX.renderer.special.TridentSpecialRenderer
+ XXX.renderer.special.TridentSpecialRenderer$Unbaked
+ XXX.renderer.state.MapRenderState
- XXX.renderer.state.MapRenderState$MapDecorationRenderState
+ XXX.renderer.state.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.Dumpable
- XXX.renderer.texture.DynamicTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
- XXX.renderer.texture.ReloadableTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SkinTextureDownloader
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
+ XXX.renderer.texture.TextureContents
- XXX.renderer.texture.TextureManager
+ XXX.renderer.texture.TextureManager$PendingReload
- XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
- XXX.resources.model.AtlasIds
+ XXX.resources.model.AtlasSet
- XXX.resources.model.AtlasSet$AtlasEntry
+ XXX.resources.model.AtlasSet$StitchResult
- XXX.resources.model.BlockModelRotation
+ XXX.resources.model.BlockModelRotation$WithUvLock
- XXX.resources.model.BlockStateDefinitions
+ XXX.resources.model.BlockStateModelLoader
- XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
+ XXX.resources.model.BlockStateModelLoader$LoadedModels
- XXX.resources.model.ClientItemInfoLoader
+ XXX.resources.model.ClientItemInfoLoader$LoadedClientInfos
- XXX.resources.model.ClientItemInfoLoader$PendingLoad
+ XXX.resources.model.EquipmentAssetManager
- XXX.resources.model.EquipmentClientInfo
+ XXX.resources.model.EquipmentClientInfo$Builder
- XXX.resources.model.EquipmentClientInfo$Dyeable
+ XXX.resources.model.EquipmentClientInfo$Layer
- XXX.resources.model.EquipmentClientInfo$LayerType
+ XXX.resources.model.Material
- XXX.resources.model.MissingBlockModel
+ XXX.resources.model.ModelBaker
- XXX.resources.model.ModelBaker$SharedOperationKey
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BakingResult
+ XXX.resources.model.ModelBakery$MissingModels
- XXX.resources.model.ModelBakery$MissingModels$1
+ XXX.resources.model.ModelBakery$ModelBakerImpl
- XXX.resources.model.ModelDebugName
+ XXX.resources.model.ModelDiscovery
- XXX.resources.model.ModelDiscovery$ModelWrapper
+ XXX.resources.model.ModelDiscovery$Slot
- XXX.resources.model.ModelGroupCollector
+ XXX.resources.model.ModelGroupCollector$GroupKey
- XXX.resources.model.ModelManager
+ XXX.resources.model.ModelManager$1
- XXX.resources.model.ModelManager$ReloadState
+ XXX.resources.model.ModelManager$ResolvedModels
- XXX.resources.model.ModelState
- XXX.resources.model.package-info
+ XXX.resources.model.QuadCollection
- XXX.resources.model.QuadCollection$Builder
+ XXX.resources.model.ResolvableModel
- XXX.resources.model.ResolvableModel$Resolver
+ XXX.resources.model.ResolvedModel
- XXX.resources.model.SpriteGetter
+ XXX.resources.model.UnbakedGeometry
- XXX.resources.model.UnbakedModel
+ XXX.resources.model.UnbakedModel$GuiLight
- XXX.resources.model.WeightedVariants
+ XXX.resources.model.WeightedVariants$Unbaked
- XXX.resources.server.DownloadedPackSource
+ XXX.resources.server.DownloadedPackSource$1
- XXX.resources.server.DownloadedPackSource$2
+ XXX.resources.server.DownloadedPackSource$3
- XXX.resources.server.DownloadedPackSource$4
+ XXX.resources.server.DownloadedPackSource$5
- XXX.resources.server.DownloadedPackSource$6
+ XXX.resources.server.DownloadedPackSource$7
- XXX.resources.server.DownloadedPackSource$8
+ XXX.resources.server.package-info
+ XXX.resources.server.PackDownloader
- XXX.resources.server.PackLoadFeedback
+ XXX.resources.server.PackLoadFeedback$FinalResult
- XXX.resources.server.PackLoadFeedback$Update
+ XXX.resources.server.PackReloadConfig
- XXX.resources.server.PackReloadConfig$Callbacks
+ XXX.resources.server.PackReloadConfig$IdAndPath
- XXX.resources.server.ServerPackManager
+ XXX.resources.server.ServerPackManager$1
- XXX.resources.server.ServerPackManager$ActivationStatus
+ XXX.resources.server.ServerPackManager$PackDownloadStatus
- XXX.resources.server.ServerPackManager$PackPromptStatus
+ XXX.resources.server.ServerPackManager$RemovalReason
- XXX.resources.server.ServerPackManager$ServerPackData
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
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
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
+ XXX.screens.inventory.DoorScreen$DisplayWidget
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.inventory.TestBlockEditScreen
- XXX.screens.inventory.TestInstanceBlockEditScreen
+ XXX.screens.inventory.TestInstanceBlockEditScreen$1
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerLinksScreen
+ XXX.screens.multiplayer.ServerLinksScreen$LinkList
- XXX.screens.multiplayer.ServerLinksScreen$LinkListEntry
+ XXX.screens.multiplayer.ServerReconfigScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$1
- XXX.screens.multiplayer.ServerSelectionList$Entry
+ XXX.screens.multiplayer.ServerSelectionList$LANHeader
- XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.multiplayer.WarningScreen
- XXX.screens.options.AccessibilityOptionsScreen
+ XXX.screens.options.ChatOptionsScreen
- XXX.screens.options.FontOptionsScreen
+ XXX.screens.options.LanguageSelectScreen
- XXX.screens.options.LanguageSelectScreen$LanguageSelectionList
+ XXX.screens.options.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.screens.options.MouseSettingsScreen
+ XXX.screens.options.OnlineOptionsScreen
- XXX.screens.options.OptionsScreen
+ XXX.screens.options.OptionsSubScreen
+ XXX.screens.options.package-info
- XXX.screens.options.SkinCustomizationScreen
+ XXX.screens.options.SoundOptionsScreen
- XXX.screens.options.UnsupportedGraphicsWarningScreen
+ XXX.screens.options.UnsupportedGraphicsWarningScreen$ButtonOption
- XXX.screens.options.VideoSettingsScreen
+ XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel
- XXX.screens.packs.PackSelectionModel$Entry
+ XXX.screens.packs.PackSelectionModel$EntryBase
- XXX.screens.packs.PackSelectionModel$SelectedPackEntry
+ XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
- XXX.screens.packs.PackSelectionScreen
+ XXX.screens.packs.PackSelectionScreen$1
- XXX.screens.packs.PackSelectionScreen$Watcher
+ XXX.screens.packs.TransferableSelectionList
- XXX.screens.packs.TransferableSelectionList$PackEntry
- XXX.screens.recipebook.CraftingRecipeBookComponent
+ XXX.screens.recipebook.FurnaceRecipeBookComponent
- XXX.screens.recipebook.GhostSlots
+ XXX.screens.recipebook.GhostSlots$GhostSlot
- XXX.screens.recipebook.OverlayRecipeComponent
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayCraftingRecipeButton
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookComponent$TabInfo
+ XXX.screens.recipebook.RecipeBookPage
- XXX.screens.recipebook.RecipeBookTabButton
+ XXX.screens.recipebook.RecipeButton
- XXX.screens.recipebook.RecipeButton$ResolvedEntry
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeCollection$CraftableStatus
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SearchRecipeBookCategory
+ XXX.screens.recipebook.SlotSelectTime
+ XXX.screens.reporting.AbstractReportScreen
- XXX.screens.reporting.AbstractReportScreen$DiscardReportWarningScreen
+ XXX.screens.reporting.ChatReportScreen
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
- XXX.screens.reporting.NameReportScreen
- XXX.screens.reporting.package-info
+ XXX.screens.reporting.ReportPlayerScreen
- XXX.screens.reporting.ReportReasonSelectionScreen
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ XXX.screens.reporting.SkinReportScreen
- XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerEntry$3
+ XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsPlayerList
+ XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$1
+ XXX.screens.social.SocialInteractionsScreen$Page
+ XXX.screens.telemetry.package-info
+ XXX.screens.telemetry.TelemetryEventWidget
- XXX.screens.telemetry.TelemetryEventWidget$Content
+ XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
- XXX.screens.telemetry.TelemetryInfoScreen
+ XXX.screens.unlocks.package-info
+ XXX.screens.unlocks.PlayerUnlocksScreen
+ XXX.screens.unlocks.PlayerUnlocksTree
+ XXX.screens.unlocks.PlayerUnlockWidget
+ XXX.screens.unlocks.RadialLayerLayout
+ XXX.screens.unlocks.UnlockTabType
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
- XXX.screens.worldselection.CreateWorldCallback
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
+ XXX.screens.worldselection.DataPackReloadCookie
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.ExperimentsScreen$ScrollArea
+ XXX.screens.worldselection.InitialWorldCreationOptions
- XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.PresetEditor
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.SwitchGrid
- XXX.screens.worldselection.SwitchGrid$Builder
+ XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- XXX.screens.worldselection.SwitchGrid$LabeledSwitch
+ XXX.screens.worldselection.SwitchGrid$SwitchBuilder
- XXX.screens.worldselection.WorldCreationContext
+ XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
- XXX.screens.worldselection.WorldCreationContext$OptionsModifier
+ XXX.screens.worldselection.WorldCreationContextMapper
- XXX.screens.worldselection.WorldCreationUiState
+ XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
- XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
+ XXX.screens.worldselection.WorldOpenFlows
- XXX.screens.worldselection.WorldOpenFlows$1Data
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$Entry
+ XXX.screens.worldselection.WorldSelectionList$LoadingHeader
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvent$Packed
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.chase.ChaseClient
+ XXX.server.chase.ChaseClient$TeleportTarget
- XXX.server.chase.ChaseServer
+ XXX.server.chase.ChaseServer$PlayerPosition
- XXX.server.chase.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ChaseCommand
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockEntityInfo
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$TraceCustomExecutor
- XXX.server.commands.DebugCommand$TraceCustomExecutor$1
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugConfigCommand
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- XXX.server.commands.ExecuteCommand$IntBiPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.LevelCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LookAt
+ XXX.server.commands.LookAt$LookAtEntity
- XXX.server.commands.LookAt$LookAtPosition
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
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
- XXX.server.commands.ReturnCommand
+ XXX.server.commands.ReturnCommand$ReturnFailCustomExecutor
- XXX.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ XXX.server.commands.ReturnCommand$ReturnValueCustomExecutor
- XXX.server.commands.RideCommand
+ XXX.server.commands.RoomCommand
+ XXX.server.commands.UnlockWorldEffectCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.level.DimensionGenerator$DimensionPackMetadata
+ XXX.server.level.DimensionGenerator$GeneratedDimension
+ XXX.server.network.ServerLessCommonPacketListenerImpl
+ XXX.server.packs.GeneratedMarkerMetadataSection
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
+ XXX.server.players.PetUpgrades
+ XXX.server.players.PlayerUnlock$Builder
+ XXX.server.players.PlayerUnlocks
- XXX.server.waypoints.ServerWaypointManager$NullWaypointManager
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- XXX.state.pip.GuiBookModelRenderState
- XXX.state.pip.GuiProfilerChartRenderState
- XXX.state.pip.GuiSkinRenderState
- XXX.state.pip.package-info
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.TagMatchTest
- XXX.synchronization.brigadier.DoubleArgumentInfo
+ XXX.synchronization.brigadier.DoubleArgumentInfo$Template
- XXX.synchronization.brigadier.FloatArgumentInfo
+ XXX.synchronization.brigadier.FloatArgumentInfo$Template
- XXX.synchronization.brigadier.IntegerArgumentInfo
+ XXX.synchronization.brigadier.IntegerArgumentInfo$Template
- XXX.synchronization.brigadier.LongArgumentInfo
+ XXX.synchronization.brigadier.LongArgumentInfo$Template
+ XXX.synchronization.brigadier.package-info
- XXX.synchronization.brigadier.StringArgumentSerializer
+ XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.synchronization.brigadier.StringArgumentSerializer$Template
- XXX.texture.atlas.package-info
+ XXX.texture.atlas.SpriteResourceLoader
- XXX.texture.atlas.SpriteSource
+ XXX.texture.atlas.SpriteSource$Output
- XXX.texture.atlas.SpriteSource$SpriteSupplier
+ XXX.texture.atlas.SpriteSourceList
- XXX.texture.atlas.SpriteSourceList$1
+ XXX.texture.atlas.SpriteSources
- XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiRecord$Packed
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiSection$Packed
- XXX.village.poi.PoiType
+ XXX.village.poi.PoiTypes
+ XXX.warden.Stages.StageMinusOne
+ XXX.warden.Stages.StageThree
+ XXX.warden.Stages.StageZero
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.InsideBlockEffectApplier
+ XXX.world.entity.InsideBlockEffectApplier$1
- XXX.world.entity.InsideBlockEffectApplier$StepBasedCollector
+ XXX.world.entity.InsideBlockEffectType
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.InterpolationHandler
+ XXX.world.entity.InterpolationHandler$InterpolationData
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.Leashable
+ XXX.world.entity.Leashable$LeashData
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.Mob$2
- XXX.world.entity.MobCategory
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OminousItemSpawner
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.PortalProcessor
+ XXX.world.entity.Pose
- XXX.world.entity.PositionMoveRotation
+ XXX.world.entity.Relative
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SlotAccess$4
+ XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacementType
+ XXX.world.entity.SpawnPlacementTypes
- XXX.world.entity.SpawnPlacementTypes$1
- XXX.world.entity.TamableAnimal
+ XXX.world.entity.TamableAnimal$TamableAnimalPanicGoal
- XXX.world.entity.Targeting
+ XXX.world.entity.TraceableEntity
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
+ XXX.world.inventory.AbstractContainerMenu$2
+ XXX.world.inventory.AbstractCraftingMenu$3
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$2
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
+ XXX.world.inventory.DimensionControlMenu$1
+ XXX.world.inventory.DoorMenu$1
+ XXX.world.inventory.DoorMenu$Layout
+ XXX.world.inventory.DoorMenu$Rect
+ XXX.world.inventory.GhettoSpline
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
+ XXX.world.inventory.MineCraftingHintSlot
+ XXX.world.inventory.MineCraftingResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerHubInventory
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.RemoteSlot
+ XXX.world.inventory.RemoteSlot$1
- XXX.world.inventory.RemoteSlot$Synchronized
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SlotRange
- XXX.world.inventory.SlotRange$1
+ XXX.world.inventory.SlotRanges
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.inventory.TransientCraftingContainer
+ XXX.world.item.AdventureModePredicate
- XXX.world.item.AirItem
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.BundleItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CreativeModeTab
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
- XXX.world.item.CrossbowItem$ChargeType
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
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
+ XXX.world.item.ExitEyeItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FeatherItem
+ XXX.world.item.FireWandItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
+ XXX.world.item.Item$TooltipContext$1
- XXX.world.item.Item$TooltipContext$2
+ XXX.world.item.Item$TooltipContext$3
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUseAnimation
- XXX.world.item.ItemUtils
- XXX.world.item.JukeboxPlayable
+ XXX.world.item.JukeboxSong
- XXX.world.item.JukeboxSongPlayer
+ XXX.world.item.JukeboxSongPlayer$OnSongChanged
- XXX.world.item.JukeboxSongs
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MaceItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
+ XXX.world.item.MinecartItem
- XXX.world.item.MobBucketItem
+ XXX.world.item.MobTrophyInfo
- XXX.world.item.package-info
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
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
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ScheduledTickAccess
+ XXX.world.level.ServerExplosion
- XXX.world.level.ServerExplosion$StackCollector
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SimpleExplosionDamageCalculator
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.TicketStorage
+ XXX.world.level.TicketStorage$ChunkUpdated
+ XXX.world.level.UnlockCondition$1
+ XXX.world.level.UnlockCondition$11
+ XXX.world.level.UnlockCondition$13
+ XXX.world.level.UnlockCondition$15
+ XXX.world.level.UnlockCondition$17
+ XXX.world.level.UnlockCondition$19
+ XXX.world.level.UnlockCondition$20
+ XXX.world.level.UnlockCondition$4
+ XXX.world.level.UnlockCondition$6
+ XXX.world.level.UnlockCondition$8
- XXX.world.waypoints.TrackedWaypoint$AzimuthWaypoint
- XXX.world.waypoints.TrackedWaypoint$EmptyWaypoint
- XXX.world.waypoints.TrackedWaypoint$Type
- XXX.world.waypoints.TrackedWaypointManager
- XXX.world.waypoints.Waypoint$Icon
- XXX.world.waypoints.WaypointManager
- XXX.world.waypoints.WaypointTransmitter$BlockConnection
- XXX.world.waypoints.WaypointTransmitter$Connection
- XXX.world.waypoints.WaypointTransmitter$EntityBlockConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.opengl.GlCommandEncoder +4M
```
```
XXX.blaze3d.textures.GpuTexture +1M
```
```
XXX.realmsclient.util.LevelType +1P
```
```
net.minecraft.WorldVersion +7P -7P
```
```
XXX.minecraft.advancements.AdvancementRewards +2M -2M
```
```
XXX.minecraft.advancements.AdvancementType +1M -3M | -1P
```
```
XXX.data.models.BlockModelGenerators +20M -21M
```
```
XXX.data.models.ItemModelGenerators +1M -3M
```
```
XXX.data.models.ItemModelOutput -1P
```
```
XXX.models.model.ModelTemplates +1P -3P
```
```
XXX.models.model.TextureSlot +1P
```
```
XXX.client.gui.Font +14M -8M
```
```
XXX.client.gui.Font$StringRenderOutput +5M -4M | -2P
```
```
XXX.client.gui.GuiGraphics +44M -40M | +6P -6P
```
```
XXX.gui.components.SpriteIconButton$Builder -1M | -1P
```
```
XXX.components.debugchart.ProfilerPieChart -1M | +1P -1P
```
```
XXX.gui.navigation.ScreenRectangle +1M -1M
```
```
XXX.screens.inventory.HangingSignEditScreen +1M -1M
```
```
XXX.screens.worldselection.CreateWorldScreen$GameTab +1M
```
```
XXX.client.renderer.LevelTargetBundle -2P
```
```
XXX.client.renderer.RenderStateShard +1M -3M | -3P
```
```
XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Entry +1M -2M | -1P
```
```
XXX.client.renderer.ScreenEffectRenderer +6M -2M | +7P
```
```
XXX.renderer.entity.ChickenRenderer -2M
```
```
XXX.renderer.entity.CowRenderer -2M
```
```
XXX.renderer.entity.EntityRenderDispatcher -1M
```
```
XXX.client.server.IntegratedServer +16M -17M
```
```
XXX.data.worldgen.NoiseData +1M
```
```
XXX.worldgen.biome.OverworldBiomes -1M
```
```
XXX.worldgen.features.MiscOverworldFeatures -6P
```
```
XXX.worldgen.features.OreFeatures -1P
```
```
XXX.gametest.framework.GameTestHelper$2 +1M -1M
```
```
XXX.gametest.framework.GameTestMainUtil +1M -2M
```
```
XXX.gametest.framework.GameTestServer +9M -11M | +1P
```
```
XXX.gametest.framework.StructureUtils -2P
```
```
XXX.minecraft.network.Connection -1M
```
```
XXX.minecraft.network.FriendlyByteBuf +4M
```
```
XXX.network.chat.Style +2M -6M | -2P
```
```
XXX.network.codec.ByteBufCodecs +1P
```
```
XXX.network.codec.ByteBufCodecs$32 +5M -1M | -1P
```
```
XXX.protocol.game.CommonPlayerSpawnInfo +1M -4M | -3P
```
```
XXX.minecraft.server.ServerTickRateManager +1M -1M | +1P -1P
```
```
XXX.server.dedicated.DedicatedServer +16M -16M | +1P
```
```
XXX.server.level.ServerPlayer +20M -32M | +2P -6P
```
```
XXX.server.network.ServerCommonPacketListenerImpl +17M -3M | +15P -1P
```
```
XXX.minecraft.sounds.SoundEvents +22P -7P
```
```
XXX.minecraft.stats.Stats +1P
```
```
XXX.minecraft.tags.EntityTypeTags +2P
```
```
XXX.minecraft.tags.StructureTags -1P
```
```
XXX.minecraft.util.ARGB +1M
```
```
XXX.util.datafix.DataFixTypes -1P
```
```
XXX.datafix.fixes.References -1P
```
```
XXX.datafix.schemas.V3439 -1M
```
```
XXX.world.effect.MobEffects -1P
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P
```
```
XXX.world.entity.ExperienceOrb -3M | -1P
```
```
XXX.ai.attributes.Attributes +3P -3P
```
```
XXX.ai.control.MoveControl +1M
```
```
XXX.ai.navigation.AmphibiousPathNavigation +1M
```
```
XXX.ai.navigation.GroundPathNavigation +1M -1M
```
```
XXX.ai.sensing.AdultSensor +3M -4M
```
```
XXX.entity.monster.Ghast$GhastLookGoal +1M -1M | +1P -1P
```
```
XXX.monster.piglin.PiglinAi +1M -1M
```
```
XXX.monster.warden.WardenAi -1M
```
```
XXX.entity.npc.Villager +1M -1M
```
```
XXX.world.inventory.AbstractCraftingMenu$1 +4M -2M | +1P -1P
```
```
XXX.world.inventory.AbstractFurnaceMenu$1 +5M -2M | +3P -2P
```
```
XXX.world.inventory.DispenserMenu +1M -1M
```
```
XXX.world.inventory.FurnaceMenu +1M -1M
```
```
XXX.world.inventory.GrindstoneMenu +1M -1M
```
```
XXX.world.inventory.InventoryMenu$1 +3M -3M | -1P
```
```
XXX.world.item.ShieldItem -1M
```
```
XXX.world.item.ToolMaterial +1M -2M | -1P
```
```
XXX.item.component.ItemAttributeModifiers$Entry +2M | +1P
```
```
XXX.item.component.SeededContainerLoot +1M -1M
```
```
XXX.item.component.TooltipProvider +1P -1P
```
```
XXX.level.biome.BiomeSpecialEffects$Builder -1M | -1P
```
```
XXX.level.biome.MultiNoiseBiomeSourceParameterLists -1P
```
```
XXX.level.block.Blocks +10M -13M | +3P -8P
```
```
XXX.level.block.CropBlock -1M
```
```
XXX.level.block.SoundType +1P
```
```
XXX.level.block.TallDryGrassBlock +1M
```
```
XXX.block.entity.TheEndPortalBlockEntity +1M
```
```
XXX.level.chunk.ChunkGeneratorStructureState +1M -1M
```
```
XXX.level.levelgen.NoiseGeneratorSettings +2M -4M | +1P -1P
```
```
XXX.levelgen.feature.SpikeFeature +2M -1M | +1P
```
```
XXX.levelgen.presets.WorldPresets +1P
```
```
XXX.levelgen.structure.BuiltinStructures -3P
```
```
XXX.levelgen.structure.Structure$StructureSettings +2M -4M | +1P -2P
```
```
XXX.structure.pools.JigsawPlacement +3M -4M
```
```
XXX.structure.structures.JigsawStructure +7M -9M | -1P
```
```
XXX.structure.templatesystem.StructureTemplateManager +9M -16M
```
```
XXX.structure.templatesystem.StructureTemplateManager$Source +1M -2M | -1P
```
```
XXX.level.storage.DerivedLevelData -11M
```
```
XXX.level.storage.WorldData -13P
```
```
XXX.storage.loot.BuiltInLootTables -2P
```
```
XXX.level.timers.FunctionTagCallback +1M -1M
```
```
XXX.world.phys.Vec3 +1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.GlCommandEncoder
</summary>

```diff
- void clearColorAndDepthTextures(GpuTexture,int,GpuTexture,double,int,int,int,int)
- void verifyColorTexture(GpuTexture)
- void verifyDepthTexture(GpuTexture)
- void verifyRegion(GpuTexture,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.textures.GpuTexture
</summary>

```diff
- void setUseMipmaps(boolean)
```

</details>
<details>
<summary>
net.minecraft.advancements.AdvancementRewards
</summary>

```diff
- Optional lambda$grant$1(MinecraftServer,CacheableFunction)
+ Optional lambda$grant$1(ServerFunctionManager,CacheableFunction)
- void lambda$grant$2(MinecraftServer,ServerPlayer,CommandFunction)
+ void lambda$grant$2(ServerFunctionManager,ServerPlayer,CommandFunction)
```

</details>
<details>
<summary>
net.minecraft.advancements.AdvancementType
</summary>

```diff
+ Component createAnnouncement(AdvancementHolder,ServerPlayer)
+ Component createPlayerUnlockAnnouncement(Holder,ServerPlayer)
- MutableComponent createAnnouncement(AdvancementHolder,ServerPlayer)
+ Style lambda$createPlayerUnlockAnnouncement$0(Component,Style)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.BlockModelGenerators
</summary>

```diff
- MultiVariant lambda$createDriedGhastBlock$45(Function,Integer)
+ MultiVariant lambda$createHangingMoss$52(Block,Boolean)
- MultiVariant lambda$createHangingMoss$54(Block,Boolean)
+ MultiVariant lambda$createRespawnAnchor$57(ResourceLocation[],Integer)
- MultiVariant lambda$createRespawnAnchor$59(ResourceLocation[],Integer)
+ MultiVariant lambda$createSculkCatalyst$53(MultiVariant,MultiVariant,Boolean)
- MultiVariant lambda$createSculkCatalyst$55(MultiVariant,MultiVariant,Boolean)
+ MultiVariant lambda$createSnifferEgg$44(Integer)
- MultiVariant lambda$createSnifferEgg$46(Integer)
+ ResourceLocation lambda$addBookSlotModel$56(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- ResourceLocation lambda$addBookSlotModel$58(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- ResourceLocation lambda$createDriedGhastBlock$44(Integer)
- void createCraftingTableLike(Block,Block,BiFunction)
+ void createCraftingTableLike(Block,Block,Block,BiFunction)
- void createDriedGhastBlock()
- void createEndPortalFrame()
+ void createMineCraftingTable()
+ void createMobTrophy()
+ void createRevisitorBlock()
+ void createTrophyBlock()
+ void generateFlatTrophy(TrophyType)
+ void lambda$addSlotStateAndRotationVariants$55(MultiPartGenerator,Condition,VariantMutator,Pair)
- void lambda$addSlotStateAndRotationVariants$57(MultiPartGenerator,Condition,VariantMutator,Pair)
+ void lambda$createChiseledBookshelf$54(MultiPartGenerator,MultiVariant,Pair)
- void lambda$createChiseledBookshelf$56(MultiPartGenerator,MultiVariant,Pair)
+ void lambda$createMossyCarpet$48(ConditionBuilder,Property,VariantMutator)
+ void lambda$createMossyCarpet$49(Block,TextureMapping)
+ void lambda$createMossyCarpet$50(Block,TextureMapping)
- void lambda$createMossyCarpet$50(ConditionBuilder,Property,VariantMutator)
- void lambda$createMossyCarpet$51(Block,TextureMapping)
+ void lambda$createMossyCarpet$51(MultiPartGenerator,MultiVariant,MultiVariant,ConditionBuilder,Property,VariantMutator)
- void lambda$createMossyCarpet$52(Block,TextureMapping)
- void lambda$createMossyCarpet$53(MultiPartGenerator,MultiVariant,MultiVariant,ConditionBuilder,Property,VariantMutator)
+ void lambda$createMultifaceBlockStates$46(ConditionBuilder,Property,VariantMutator)
+ void lambda$createMultifaceBlockStates$47(MultiPartGenerator,MultiVariant,ConditionBuilder,Property,VariantMutator)
- void lambda$createMultifaceBlockStates$48(ConditionBuilder,Property,VariantMutator)
- void lambda$createMultifaceBlockStates$49(MultiPartGenerator,MultiVariant,ConditionBuilder,Property,VariantMutator)
+ void lambda$run$58(BlockFamily)
- void lambda$run$60(BlockFamily)
+ void lambda$selectMultifaceProperties$45(Function,StateHolder,ImmutableMap$Builder,Direction,VariantMutator)
- void lambda$selectMultifaceProperties$47(Function,StateHolder,ImmutableMap$Builder,Direction,VariantMutator)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.ItemModelGenerators
</summary>

```diff
+ void generateLevelIngredient(Item)
+ void generateTrophies()
- void generateTwoLayerDyedItem(Item)
+ void generateWolfArmor(Item)
```

</details>
<details>
<summary>
net.minecraft.client.gui.Font
</summary>

```diff
+ float renderText(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
+ float renderText(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
+ int drawInBatch(Component,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
+ int drawInBatch(Component,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
+ int drawInBatch(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
+ int drawInBatch(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
+ int drawInternal(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
+ int drawInternal(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
- TextRenderState extractInternal(FormattedCharSequence,float,float,int,boolean,Font$DisplayMode,int,int,boolean)
- TextRenderState extractInternal(String,float,float,int,boolean,Font$DisplayMode,int,int,boolean)
- TextRenderState extractText(FormattedCharSequence,float,float,int,boolean,Font$DisplayMode,int,int,boolean)
- TextRenderState extractText(String,float,float,int,boolean,Font$DisplayMode,int,int,boolean)
- TextRenderState extractTextRenderState(FormattedCharSequence,float,float,int,boolean,Font$DisplayMode,int,int)
- TextRenderState extractTextRenderState(String,float,float,int,boolean,Font$DisplayMode,int,int)
- void drawInBatch(Component,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
- void drawInBatch(Component,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
- void drawInBatch(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
- void drawInBatch(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int)
- void drawInternal(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
- void drawInternal(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
- void renderText(FormattedCharSequence,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
- void renderText(String,float,float,int,boolean,Matrix4f,MultiBufferSource,Font$DisplayMode,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.Font$StringRenderOutput
</summary>

```diff
+ float finish(float)
- TextRenderState extract()
- void <init>(Font,float,float,int,boolean,Font$DisplayMode,int)
- void <init>(Font,float,float,int,int,boolean,Font$DisplayMode,int,boolean)
+ void <init>(Font,MultiBufferSource,float,float,int,boolean,Matrix4f,Font$DisplayMode,int)
+ void <init>(Font,MultiBufferSource,float,float,int,int,boolean,Matrix4f,Font$DisplayMode,int,boolean)
- void finish(float,MultiBufferSource,Matrix4f)
+ void renderCharacters()
- void renderCharacters(MultiBufferSource,Matrix4f)
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiGraphics
</summary>

```diff
+ DeltaTracker getDeltaTracker()
- float getNextDepth()
+ int drawString(Font,Component,int,int,int,boolean)
+ int drawString(Font,Component,int,int,int)
+ int drawString(Font,FormattedCharSequence,int,int,int,boolean)
+ int drawString(Font,FormattedCharSequence,int,int,int)
+ int drawString(Font,String,int,int,int,boolean)
+ int drawString(Font,String,int,int,int)
+ int drawStringWithBackdrop(Font,Component,int,int,int,int)
- Matrix3x2fStack pose()
+ PoseStack pose()
- void <init>(Minecraft,GuiRenderState)
- void <init>(Minecraft,Matrix3x2fStack,GuiRenderState)
+ void <init>(Minecraft,MultiBufferSource$BufferSource)
+ void <init>(Minecraft,PoseStack,MultiBufferSource$BufferSource)
+ void applyScissor(ScreenRectangle)
+ void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int,int,int)
+ void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int,int)
+ void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int)
+ void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int)
- void blit(RenderPipeline,ResourceLocation,int,int,float,float,int,int,int,int,int,int,int)
- void blit(RenderPipeline,ResourceLocation,int,int,float,float,int,int,int,int,int,int)
- void blit(RenderPipeline,ResourceLocation,int,int,float,float,int,int,int,int,int)
- void blit(RenderPipeline,ResourceLocation,int,int,float,float,int,int,int,int)
- void blit(ResourceLocation,int,int,int,int,float,float,float,float)
+ void blitNineSlicedSprite(Function,TextureAtlasSprite,GuiSpriteScaling$NineSlice,int,int,int,int,int)
- void blitNineSlicedSprite(RenderPipeline,TextureAtlasSprite,GuiSpriteScaling$NineSlice,int,int,int,int,int)
+ void blitNineSliceInnerSegment(Function,GuiSpriteScaling$NineSlice,TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
- void blitNineSliceInnerSegment(RenderPipeline,GuiSpriteScaling$NineSlice,TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
+ void blitSprite(Function,ResourceLocation,int,int,int,int,int,int,int,int)
+ void blitSprite(Function,ResourceLocation,int,int,int,int,int)
+ void blitSprite(Function,ResourceLocation,int,int,int,int)
+ void blitSprite(Function,TextureAtlasSprite,int,int,int,int,int,int,int,int,int)
+ void blitSprite(Function,TextureAtlasSprite,int,int,int,int,int)
+ void blitSprite(Function,TextureAtlasSprite,int,int,int,int)
- void blitSprite(RenderPipeline,ResourceLocation,int,int,int,int,int,int,int,int,int)
- void blitSprite(RenderPipeline,ResourceLocation,int,int,int,int,int,int,int,int)
- void blitSprite(RenderPipeline,ResourceLocation,int,int,int,int,int)
- void blitSprite(RenderPipeline,ResourceLocation,int,int,int,int)
- void blitSprite(RenderPipeline,TextureAtlasSprite,int,int,int,int,int,int,int,int,int)
- void blitSprite(RenderPipeline,TextureAtlasSprite,int,int,int,int,int)
- void blitSprite(RenderPipeline,TextureAtlasSprite,int,int,int,int)
+ void blitTiledSprite(Function,TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
- void blitTiledSprite(RenderPipeline,TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
+ void drawSpecial(Consumer)
- void drawString(Font,Component,int,int,int,boolean)
- void drawString(Font,Component,int,int,int)
- void drawString(Font,FormattedCharSequence,int,int,int,boolean)
- void drawString(Font,FormattedCharSequence,int,int,int)
- void drawString(Font,String,int,int,int,boolean)
- void drawString(Font,String,int,int,int)
- void drawStringWithBackdrop(Font,Component,int,int,int,int)
+ void fill(int,int,int,int,int,int)
- void fill(RenderPipeline,int,int,int,int,int)
- void fill(RenderPipeline,TextureSetup,int,int,int,int)
+ void fill(RenderType,int,int,int,int,int,int)
+ void fill(RenderType,int,int,int,int,int)
+ void fillGradient(int,int,int,int,int,int,int)
+ void fillGradient(RenderType,int,int,int,int,int,int,int)
+ void fillGradient(VertexConsumer,int,int,int,int,int,int,int)
+ void fillRenderType(RenderType,int,int,int,int,int)
+ void flush()
+ void hLine(RenderType,int,int,int,int)
+ void innerBlit(Function,ResourceLocation,int,int,int,int,float,float,float,float,int)
- void innerBlit(RenderPipeline,ResourceLocation,int,int,int,int,float,float,float,float,int)
- void popGuiLayer()
- void popPushGuiLayer(GuiLayer)
- void pushGuiLayer(GuiLayer)
+ void renderItem(ItemStack,int,int,int,int)
+ void renderItem(LivingEntity,Level,ItemStack,int,int,int,int)
+ void renderItemDecorations(Font,ItemStack,int,int,String)
- void renderItemDecorations(GuiGraphics$ItemSlotContext,Font,ItemStack,int,int,String)
- void renderItemDecorations(GuiGraphics$ItemSlotContext,Font,ItemStack,int,int)
- void submitBannerPatternRenderState(ModelPart,DyeColor,BannerPatternLayers,int,int,int,int)
- void submitBlit(RenderPipeline,GpuTexture,int,int,int,int,float,float,float,float,int)
- void submitBookModelRenderState(BookModel,ResourceLocation,float,float,float,int,int,int,int)
- void submitColoredRectangle(RenderPipeline,TextureSetup,int,int,int,int,int,Integer)
- void submitEntityRenderState(EntityRenderState,float,Vector3f,Quaternionf,Quaternionf,int,int,int,int)
- void submitMapRenderState(MapRenderState)
- void submitProfilerChartRenderState(List,int,int,int,int)
- void submitSignRenderState(Model,float,WoodType,int,int,int,int)
- void submitSkinRenderState(PlayerModel,ResourceLocation,float,float,float,float,int,int,int,int)
- void submitText(TextRenderState,int,int)
+ void vLine(RenderType,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.SpriteIconButton$Builder
</summary>

```diff
+ SpriteIconButton$Builder tooltip(Tooltip)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.debugchart.ProfilerPieChart
</summary>

```diff
+ void lambda$render$0(List,GuiGraphics,int,int,MultiBufferSource)
```

</details>
<details>
<summary>
net.minecraft.client.gui.navigation.ScreenRectangle
</summary>

```diff
- ScreenRectangle transformAxisAligned(Matrix3x2f)
+ ScreenRectangle transformAxisAligned(Matrix4f)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
</summary>

```diff
- float getSignYOffset()
+ void offsetSign(GuiGraphics,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$GameTab
</summary>

```diff
- void lambda$new$9(Button)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderStateShard
</summary>

```diff
- RenderTarget lambda$static$11()
+ RenderTarget lambda$static$17()
+ RenderTarget lambda$static$18()
+ void lambda$static$11()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Entry
</summary>

```diff
+ boolean blur()
+ void <init>(ResourceLocation,boolean,boolean)
- void <init>(ResourceLocation,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ScreenEffectRenderer
</summary>

```diff
+ void <init>()
- void <init>(Minecraft,MultiBufferSource)
- void displayItemActivation(ItemStack,RandomSource)
- void renderItemActivationAnimation(PoseStack,float)
- void renderScreenEffect(boolean,float)
+ void renderScreenEffect(Minecraft,PoseStack,MultiBufferSource)
- void resetItemActivation()
- void tick()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ChickenRenderer
</summary>

```diff
+ ChickenRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
+ EntityRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CowRenderer
</summary>

```diff
+ CowRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
+ EntityRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderDispatcher
</summary>

```diff
+ EntityRenderer getRenderer(EntityType)
```

</details>
<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- boolean isTickTimeLoggingEnabled()
- boolean publishServer(GameType,boolean,int)
+ boolean publishServer(TheGame,GameType,boolean,int)
- boolean saveEverything(boolean,boolean,boolean)
+ boolean saveEverything(TheGame,boolean,boolean,boolean)
- GameType getForcedGameType()
+ GameType getForcedGameType(TheGame)
- LocalSampleLogger getTickTimeLogger()
+ LocalSampleLogger getTickTimeLoggerIfEnabled()
+ PlayerList lambda$initGame$0(TheGame)
- SampleLogger getTickTimeLogger()
+ SampleLogger getTickTimeLoggerIfEnabled()
- String lambda$fillServerSystemReport$0()
+ String lambda$fillServerSystemReport$1()
+ TheGame initGame(PackRepository,WorldStem,ChunkProgressListenerFactory)
- void <init>(Thread,Minecraft,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,ChunkProgressListenerFactory)
+ void <init>(Thread,Minecraft,LevelStorageSource$LevelStorageAccess,Services)
- void lambda$halt$1()
+ void lambda$halt$2()
- void lambda$reportChunkLoadFailure$3(ChunkPos)
+ void lambda$reportChunkLoadFailure$4(ChunkPos)
- void lambda$reportChunkSaveFailure$4(ChunkPos)
+ void lambda$reportChunkSaveFailure$5(ChunkPos)
- void lambda$warnOnLowDiskSpace$2()
+ void lambda$warnOnLowDiskSpace$3()
- void setDefaultGameType(GameType)
+ void setDefaultGameType(TheGame,GameType)
- void stopServer()
+ void stopServer(TheGame)
- void tickPaused()
+ void tickPaused(TheGame)
- void tickServer(BooleanSupplier)
+ void tickServer(TheGame,BooleanSupplier)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.NoiseData
</summary>

```diff
- void registerBiomeNoises(BootstrapContext,int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.OverworldBiomes
</summary>

```diff
+ Biome hub(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$2
</summary>

```diff
- void <init>(GameTestHelper,MinecraftServer,ServerLevel,GameProfile,ClientInformation)
+ void <init>(GameTestHelper,TheGame,ServerLevel,GameProfile,ClientInformation)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestMainUtil
</summary>

```diff
- GameTestServer lambda$runGameTestServer$0(LevelStorageSource$LevelStorageAccess,PackRepository,OptionSet,Thread)
+ GameTestServer lambda$runGameTestServer$1(LevelStorageSource$LevelStorageAccess,OptionSet,Thread)
+ WorldStem lambda$runGameTestServer$0(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
- boolean isHardcore()
+ boolean isHardcore(TheGame)
- boolean isTickTimeLoggingEnabled()
- boolean lambda$evaluateTestsToRun$2(Holder$Reference)
+ boolean lambda$evaluateTestsToRun$4(Holder$Reference)
- CompletableFuture lambda$create$1(WorldLoader$InitConfig,LevelSettings,Executor)
+ CompletableFuture lambda$createWorldStem$1(WorldLoader$InitConfig,LevelSettings,Executor)
+ GameTestServer create(Thread,LevelStorageSource$LevelStorageAccess,Optional,boolean)
- GameTestServer create(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,Optional,boolean)
+ PlayerList lambda$initGame$2(TheGame)
- SampleLogger getTickTimeLogger()
+ SampleLogger getTickTimeLoggerIfEnabled()
+ TheGame initGame(PackRepository,WorldStem,ChunkProgressListenerFactory)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,Optional,boolean)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Optional,boolean)
- void tickServer(BooleanSupplier)
+ void tickServer(TheGame,BooleanSupplier)
- WorldLoader$DataLoadOutput lambda$create$0(LevelSettings,WorldLoader$DataLoadContext)
+ WorldLoader$DataLoadOutput lambda$createWorldStem$0(LevelSettings,WorldLoader$DataLoadContext)
+ WorldStem createWorldStem(PackRepository)
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
+ void replaceListener(PacketListener)
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Either readEither(StreamDecoder,StreamDecoder)
- void lambda$writeEither$6(StreamEncoder,Object)
- void lambda$writeEither$7(StreamEncoder,Object)
- void writeEither(Either,StreamEncoder,StreamEncoder)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style
</summary>

```diff
+ boolean isMega()
+ Float getScale()
+ Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
- Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ Style withMEGA(Boolean)
+ Style withScale(Float)
+ void <init>(TextColor,Integer,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation,Boolean,Float)
- void <init>(TextColor,Integer,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$32
</summary>

```diff
- Integer decode(ByteBuf)
- Object decode(Object)
+ void <clinit>()
- void <init>()
- void encode(ByteBuf,Integer)
- void encode(Object,Object)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
</summary>

```diff
+ boolean isMap()
+ List activeEffects()
+ List unlockedEffects()
+ void <init>(Holder,ResourceKey,long,GameType,GameType,boolean,boolean,Optional,int,int,boolean,List,List)
- void <init>(Holder,ResourceKey,long,GameType,GameType,boolean,boolean,Optional,int,int)
```

</details>
<details>
<summary>
net.minecraft.server.ServerTickRateManager
</summary>

```diff
- void <init>(MinecraftServer)
+ void <init>(TheGame)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- boolean isSpawningMonsters()
+ boolean isSpawningMonsters(TheGame)
- boolean isTickTimeLoggingEnabled()
- DedicatedPlayerList getPlayerList()
- DedicatedServerProperties lambda$setPlayerIdleTimeout$2(int,DedicatedServerProperties)
+ DedicatedServerProperties lambda$setPlayerIdleTimeout$3(TheGame,int,DedicatedServerProperties)
- DedicatedServerProperties lambda$storeUsingWhiteList$4(boolean,DedicatedServerProperties)
+ DedicatedServerProperties lambda$storeUsingWhiteList$5(TheGame,boolean,DedicatedServerProperties)
- GameType getForcedGameType()
+ GameType getForcedGameType(TheGame)
- PlayerList getPlayerList()
+ PlayerList lambda$initGame$0(TheGame)
- SampleLogger getTickTimeLogger()
+ SampleLogger getTickTimeLoggerIfEnabled()
- ServerLinks lambda$createServerLinks$5(URI)
+ ServerLinks lambda$createServerLinks$6(URI)
- String lambda$fillServerSystemReport$0()
+ String lambda$fillServerSystemReport$2()
+ String[] getPlayerNames()
+ TheGame initGame(PackRepository,WorldStem,ChunkProgressListenerFactory)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,DedicatedServerSettings,DataFixer,Services)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,DedicatedServerSettings,DataFixer,Services,ChunkProgressListenerFactory)
- void forceDifficulty()
+ void forceDifficulty(TheGame)
- void lambda$runCommand$3(String)
+ void lambda$runCommand$4(String)
- void setPlayerIdleTimeout(int)
+ void setPlayerIdleTimeout(TheGame,int)
- void stopServer()
+ void stopServer(TheGame)
- void storeUsingWhiteList(boolean)
+ void storeUsingWhiteList(TheGame,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean buyUnlock(Holder)
+ boolean donateExperienceToMineCrafter()
+ boolean isActive(Holder)
- boolean isReceivingWaypoints()
+ boolean isRevisiting()
+ boolean isUnlocked(Holder)
- boolean lambda$startSleepInBed$15(Monster)
- boolean lambda$tellNeutralMobsThatIDied$11(Mob)
+ boolean lambda$tellNeutralMobsThatIDied$12(Mob)
- Entity lambda$loadAndSpawnEnderPearl$7(ServerLevel,Entity)
+ Entity lambda$loadAndSpawnEnderPearl$8(ServerLevel,Entity)
- Entity lambda$loadAndSpawnParentVehicle$5(ServerLevel,Entity)
+ Entity lambda$loadAndSpawnParentVehicle$6(ServerLevel,Entity)
+ ItemEntity drop(ItemStack,boolean,boolean,boolean)
- ItemEntity drop(ItemStack,boolean,boolean)
- Packet lambda$die$10(Component)
+ Packet lambda$die$11(Component)
+ Packet lambda$sendSystemMessage$18(Component)
- Packet lambda$sendSystemMessage$19(Component)
- ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$13(BlockPos,Vec3)
+ ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$15(BlockPos,Vec3)
+ Stream lambda$awardRecipesByKey$17(ResourceKey)
- Stream lambda$awardRecipesByKey$18(ResourceKey)
+ Style lambda$die$10(Component,Style)
- Style lambda$die$9(Component,Style)
+ TheGame theGame()
- void <init>(MinecraftServer,ServerLevel,GameProfile,ClientInformation)
+ void <init>(TheGame,ServerLevel,GameProfile,ClientInformation)
+ void addHubReward(ItemStack)
+ void forceUnlock(Holder)
+ void lambda$awardStat$16(int,ScoreAccess)
- void lambda$awardStat$17(int,ScoreAccess)
+ void lambda$drop$19(Inventory,int)
- void lambda$drop$20(Inventory,int)
- void lambda$loadAndSpawnEnderPearls$6(ListTag)
+ void lambda$loadAndSpawnEnderPearls$7(ListTag)
- void lambda$new$0(MinecraftServer,ResourceKey,Consumer)
+ void lambda$new$0(TheGame,ResourceKey,Consumer)
+ void lambda$readAdditionalSaveData$5(ListTag)
- void lambda$startSleepInBed$16(Unit)
- void lambda$tellNeutralMobsThatIDied$12(Mob)
+ void lambda$tellNeutralMobsThatIDied$13(Mob)
- void lambda$updateScoreForCriteria$8(int,ScoreAccess)
+ void lambda$updateScoreForCriteria$9(int,ScoreAccess)
+ void makeVisibile(Holder)
- void onAttributeModified(AttributeInstance)
+ void onMineEntered()
+ void openDoor(ItemStack,BlockPos,Direction,DoubleBlockHalf)
+ void reactivateUnlock(Holder)
+ void setRevisiting(boolean)
+ void swapInventoryFromHub()
+ void swapInventoryToHub()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerCommonPacketListenerImpl
</summary>

```diff
- boolean checkIfClosed(long)
+ boolean shouldFLush()
- CommonListenerCookie createCookie(ClientInformation)
- GameProfile getOwner()
- int latency()
- String lambda$send$0(Packet)
- void <clinit>()
- void <init>(MinecraftServer,Connection,CommonListenerCookie)
+ void <init>(TheGame,Connection,CommonListenerCookie)
- void close()
- void disconnect(Component)
- void handleCookieResponse(ServerboundCookieResponsePacket)
- void handleCustomPayload(ServerboundCustomPayloadPacket)
- void handleKeepAlive(ServerboundKeepAlivePacket)
- void handlePong(ServerboundPongPacket)
- void keepConnectionAlive()
+ void lambda$disconnect$0(DisconnectionDetails)
- void lambda$disconnect$1(DisconnectionDetails)
- void send(Packet,PacketSendListener)
- void send(Packet)
```

</details>
<details>
<summary>
net.minecraft.util.ARGB
</summary>

```diff
- int setBrightness(int,float)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V3439
</summary>

```diff
+ TypeTemplate lambda$registerBlockEntities$1(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
- void setCustomParticle(ParticleOptions)
+ void setParticle(ParticleOptions)
+ void updateColor()
- void updateParticle()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
+ boolean isOfAge()
+ void <init>(Level,Vec3,Vec3,int)
+ void awardWithDirection(ServerLevel,Vec3,Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.control.MoveControl
</summary>

```diff
- void setWait()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
</summary>

```diff
- boolean canNavigateGround()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.GroundPathNavigation
</summary>

```diff
- boolean canNavigateGround()
+ void setCanOpenDoors(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.AdultSensor
</summary>

```diff
+ boolean lambda$setNearestVisibleAdult$1(AgeableMob,LivingEntity)
- boolean lambda$setNearestVisibleAdult$1(LivingEntity,LivingEntity)
+ void doTick(ServerLevel,AgeableMob)
+ void lambda$doTick$0(AgeableMob,NearestVisibleLivingEntities)
- void lambda$doTick$0(LivingEntity,NearestVisibleLivingEntities)
+ void setNearestVisibleAdult(AgeableMob,NearestVisibleLivingEntities)
- void setNearestVisibleAdult(LivingEntity,NearestVisibleLivingEntities)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Ghast$GhastLookGoal
</summary>

```diff
+ void <init>(Ghast)
- void <init>(Mob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
- List getBarterResponseItems(Piglin)
+ List getBarterResponseItems(ServerLevel,Piglin)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.WardenAi
</summary>

```diff
+ void initStageActivity(Brain)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
- void lambda$releasePoi$5(MinecraftServer,MemoryModuleType,GlobalPos)
+ void lambda$releasePoi$5(TheGame,MemoryModuleType,GlobalPos)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractCraftingMenu$1
</summary>

```diff
+ boolean isActive()
- boolean recipeMatches(RecipeHolder)
+ void <init>(AbstractCraftingMenu,Player,CraftingContainer,Container,int,int,int,Player)
- void <init>(AbstractCraftingMenu)
- void clearCraftingContent()
- void fillCraftSlotsStackedContents(StackedItemContents)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu$1
</summary>

```diff
- boolean recipeMatches(RecipeHolder)
+ void <init>(AbstractFurnaceMenu,Container,int,int,int,Inventory,ContainerData)
- void <init>(AbstractFurnaceMenu,List,ServerLevel)
- void clearCraftingContent()
- void fillCraftSlotsStackedContents(StackedItemContents)
- void lambda$clearCraftingContent$0(Slot)
+ void setByPlayer(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.DispenserMenu
</summary>

```diff
+ void <init>(int,Inventory,List)
- void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.FurnaceMenu
</summary>

```diff
+ void <init>(int,Inventory,List)
- void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ void <init>(int,Inventory,List)
- void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.InventoryMenu$1
</summary>

```diff
+ boolean isActive()
+ boolean mayPlace(ItemStack)
- ResourceLocation getNoItemIcon()
- void <init>(InventoryMenu,Container,int,int,int,Player)
+ void <init>(InventoryMenu,Container,LivingEntity,EquipmentSlot,int,int,int,ResourceLocation,Player,EquipmentSlot)
- void setByPlayer(ItemStack,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
+ InteractionResult use(Level,Player,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.item.ToolMaterial
</summary>

```diff
+ float exchangeValue()
+ void <init>(TagKey,int,float,float,int,TagKey,float)
- void <init>(TagKey,int,float,float,int,TagKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.ItemAttributeModifiers$Entry
</summary>

```diff
- ItemAttributeModifiers$Display display()
- void <init>(Holder,AttributeModifier,EquipmentSlotGroup,ItemAttributeModifiers$Display)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.SeededContainerLoot
</summary>

```diff
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
</summary>

```diff
+ BiomeSpecialEffects$Builder withExitType(BiomeSpecialEffects$ExitType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ Block lambda$static$174(BlockBehaviour$Properties)
+ Block lambda$static$175(BlockBehaviour$Properties)
- Block lambda$static$176(BlockBehaviour$Properties)
+ Block lambda$static$178(BlockBehaviour$Properties)
- Block lambda$static$179(BlockBehaviour$Properties)
+ Block lambda$static$181(BlockBehaviour$Properties)
- Block lambda$static$248(BlockBehaviour$Properties)
+ Block lambda$static$250(BlockBehaviour$Properties)
- Block lambda$static$315(BlockBehaviour$Properties)
- Block lambda$static$318(BlockBehaviour$Properties)
+ Block lambda$static$502(BlockBehaviour$Properties)
- int lambda$static$174(BlockState)
- int lambda$static$175(BlockState)
+ int lambda$static$176(BlockState)
- int lambda$static$178(BlockState)
+ int lambda$static$179(BlockState)
- int lambda$static$181(BlockState)
+ int lambda$static$248(BlockState)
- int lambda$static$250(BlockState)
+ int lambda$static$315(BlockState)
+ int lambda$static$318(BlockState)
+ int lambda$static$503(BlockState)
+ int lambda$static$504(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CropBlock
</summary>

```diff
+ void playerDestroy(Level,Player,BlockPos,BlockState,BlockEntity,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TallDryGrassBlock
</summary>

```diff
- void animateTick(BlockState,Level,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
</summary>

```diff
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGeneratorStructureState
</summary>

```diff
+ Stream lambda$hasBiomesForStructureSet$2(BiomeSource,StructureSet$StructureSelectionEntry)
- Stream lambda$hasBiomesForStructureSet$2(StructureSet$StructureSelectionEntry)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
+ long salt()
- NoiseGeneratorSettings overworld(BootstrapContext,boolean,boolean)
+ NoiseGeneratorSettings overworld(BootstrapContext,boolean)
+ NoiseGeneratorSettings$Builder asBuilder()
+ void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,boolean,boolean,boolean,boolean,long)
- void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature
</summary>

```diff
+ List getSpikesForLevel(ServerLevel)
- List getSpikesForLevel(WorldGenLevel)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
</summary>

```diff
+ BiomeSpecialEffects$ExitType requiredExitType()
- HolderSet biomes()
+ Optional biomes()
+ void <init>(BiomeSpecialEffects$ExitType)
- void <init>(HolderSet,Map,GenerationStep$Decoration,TerrainAdjustment)
+ void <init>(Optional,BiomeSpecialEffects$ExitType,Map,GenerationStep$Decoration,TerrainAdjustment)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
</summary>

```diff
+ boolean generateJigsaw(ServerLevel,Holder,Optional,int,BlockPos,boolean)
- boolean generateJigsaw(ServerLevel,Holder,ResourceLocation,int,BlockPos,boolean)
+ boolean isOkSpawnPos(NoiseColumn,int)
+ Optional addPieces(Structure$GenerationContext,Holder,Optional,int,BlockPos,boolean,Optional,boolean,int,PoolAliasLookup,DimensionPadding,LiquidSettings)
- Optional addPieces(Structure$GenerationContext,Holder,Optional,int,BlockPos,boolean,Optional,int,PoolAliasLookup,DimensionPadding,LiquidSettings)
+ void lambda$addPieces$2(PoolElementStructurePiece,int,int,int,int,int,DimensionPadding,int,LevelHeightAccessor,BoundingBox,Structure$GenerationContext,boolean,ChunkGenerator,StructureTemplateManager,WorldgenRandom,Registry,PoolAliasLookup,LiquidSettings,StructurePiecesBuilder)
- void lambda$addPieces$2(PoolElementStructurePiece,int,int,int,int,LevelHeightAccessor,DimensionPadding,int,BoundingBox,Structure$GenerationContext,boolean,ChunkGenerator,StructureTemplateManager,WorldgenRandom,Registry,PoolAliasLookup,LiquidSettings,StructurePiecesBuilder)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
</summary>

```diff
- App lambda$static$10(RecordCodecBuilder$Instance)
+ App lambda$static$11(RecordCodecBuilder$Instance)
+ Boolean lambda$static$6(JigsawStructure)
- DimensionPadding lambda$static$8(JigsawStructure)
+ DimensionPadding lambda$static$9(JigsawStructure)
- Integer lambda$static$6(JigsawStructure)
+ Integer lambda$static$7(JigsawStructure)
+ LiquidSettings lambda$static$10(JigsawStructure)
- LiquidSettings lambda$static$9(JigsawStructure)
- List lambda$static$7(JigsawStructure)
+ List lambda$static$8(JigsawStructure)
- String lambda$verifyRange$11()
+ String lambda$verifyRange$12()
+ void <init>(Structure$StructureSettings,Holder,int,HeightProvider,boolean,boolean)
+ void <init>(Structure$StructureSettings,Holder,Optional,int,HeightProvider,boolean,Optional,boolean,int,List,DimensionPadding,LiquidSettings)
- void <init>(Structure$StructureSettings,Holder,Optional,int,HeightProvider,boolean,Optional,int,List,DimensionPadding,LiquidSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
</summary>

```diff
+ boolean lambda$listFolderContents$11(String,Path,BasicFileAttributes)
- boolean lambda$listFolderContents$7(String,Path,BasicFileAttributes)
- boolean lambda$listGenerated$5(Path)
+ boolean lambda$listGenerated$9(Path)
+ boolean lambda$listTemplates$3(StructureTemplateManager$SourceType,StructureTemplateManager$Source)
+ Component lambda$copyToFinal$0(Path,Path)
+ Component lambda$copyToFinal$1()
- InputStream lambda$loadFromGenerated$3(Path)
+ InputStream lambda$loadFromGenerated$7(Path)
- InputStream lambda$loadFromResource$1(ResourceLocation)
+ InputStream lambda$loadFromResource$5(ResourceLocation)
+ Path createAndValidatePathToDatapackStructure(ResourceLocation,String)
- Stream lambda$listTemplates$0(StructureTemplateManager$Source)
+ Stream lambda$listTemplates$2(StructureTemplateManager$Source)
+ Stream lambda$listTemplates$4(StructureTemplateManager$Source)
+ Stream listTemplates(StructureTemplateManager$SourceType)
+ String lambda$listFolderContents$10(int,String)
- String lambda$listFolderContents$6(int,String)
+ void copyToFinal(CommandSourceStack,ResourceLocation)
+ void lambda$listFolderContents$12(Consumer,String,Function,Path,Path)
- void lambda$listFolderContents$8(Consumer,String,Function,Path,Path)
- void lambda$loadFromGenerated$4(Path,Throwable)
+ void lambda$loadFromGenerated$8(Path,Throwable)
- void lambda$loadFromResource$2(ResourceLocation,Throwable)
+ void lambda$loadFromResource$6(ResourceLocation,Throwable)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
</summary>

```diff
+ StructureTemplateManager$SourceType type()
- void <init>(Function,Supplier)
+ void <init>(StructureTemplateManager$SourceType,Function,Supplier)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
+ boolean isEffectUnlocked(WorldEffect)
+ boolean isSpecialMineUnlocked(SpecialMine)
+ int getLevelCount()
+ int getMineCrafterExp()
+ int getMineCrafterLevel()
+ int incrementAndGetLevelCount()
+ Optional getNextSpecialMine(RandomSource)
+ void addExperienceToMineCrafter(int)
+ void mineCompleted(Optional,boolean)
+ void unlockEffect(WorldEffect)
+ void unlockSpecialMine(SpecialMine)
```

</details>
<details>
<summary>
net.minecraft.world.level.timers.FunctionTagCallback
</summary>

```diff
- void handle(MinecraftServer,TimerQueue,long)
+ void handle(TheGame,TimerQueue,long)
```

</details>
<details>
<summary>
net.minecraft.world.phys.Vec3
</summary>

```diff
- Vec3 rotateClockwise90()
```

</details>
</details>
<hr/>