## Comparison with [1.21.5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.5)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Items (models)](#items-(models))
> - [Blocks](#blocks)
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
<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>World version</td><td><pre>4325</pre></td><td><pre>4323</pre></td></tr><tr><td>Protocol version</td><td><pre>770</pre></td><td><pre>1073742068</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ mine_event_type.txt
+ player_unlock.txt
+ special_mine.txt
+ world_effect_set.txt
+ world_effect.txt
```

</details>
<details>
<summary>
activity
</summary>

```diff
+ minecraft:acting
```

</details>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:experience_gain_modifier
+ minecraft:max_jumps
+ minecraft:pickup_area_size
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal
- minecraft:end_portal_frame
+ minecraft:mine_crafter
+ minecraft:mine_revisitor
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
+ minecraft:shimmering_door
+ minecraft:sky
+ minecraft:trophy
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
- minecraft:end_portal
+ minecraft:mine_crafter
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal
- minecraft:end_portal_frame
+ minecraft:mine_crafter
+ minecraft:mine_revisitor_block
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
+ minecraft:shimmering_door
+ minecraft:trophy
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:dimension_id
+ minecraft:exchange_value
+ minecraft:instant_room
+ minecraft:mine_active
+ minecraft:mine_completed
+ minecraft:mob_trophy/type
+ minecraft:sky
+ minecraft:special_mine
+ minecraft:trophy/type
+ minecraft:world_effect_uhint
+ minecraft:world_effect_unlock
+ minecraft:world_modifiers
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:angry_ghast
+ minecraft:pet_armadillo
+ minecraft:pet_axolotl
+ minecraft:pet_bee
+ minecraft:pet_cat
+ minecraft:pet_chicken
+ minecraft:pet_cow
+ minecraft:pet_creeper
+ minecraft:pet_fox
+ minecraft:pet_frog
+ minecraft:pet_mooshroom
+ minecraft:pet_polar_bear
+ minecraft:pet_slime
+ minecraft:pet_turtle
+ minecraft:pet_wolf
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal_frame
- minecraft:ender_eye
+ minecraft:exit_eye
+ minecraft:fire_wand
+ minecraft:grave_advancement
+ minecraft:mine
+ minecraft:mine_crafter
+ minecraft:mine_ingredient
+ minecraft:mine_revisitor
+ minecraft:mob_trophy
+ minecraft:music_disc_and_action
+ minecraft:shazboots
+ minecraft:shimmering_door
+ minecraft:shimmering_key
+ minecraft:sky
+ minecraft:sky_box
+ minecraft:teleportation_wand
+ minecraft:trophy
+ minecraft:wind_wand
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:acting_stage
```

</details>
<details>
<summary>
menu
</summary>

```diff
+ minecraft:dimension_control
+ minecraft:map_making
```

</details>
<details>
<summary>
mob_effect
</summary>

```diff
+ minecraft:shazboots
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:mine_travel
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ nothingtoseehere:and_action
+ nothingtoseehere:crowd_cheer
+ nothingtoseehere:crowd_start
+ nothingtoseehere:crowd_waiting
+ nothingtoseehere:ui.player_unlock_fail
+ nothingtoseehere:ui.player_unlock_success
```

</details>
<details>
<summary>
trigger_type
</summary>

```diff
+ minecraft:consume_poisonous_potatoes
+ minecraft:inventory_cashed_in
+ minecraft:level_completed
+ minecraft:level_failed
+ minecraft:mine_crafter_upgraded
+ minecraft:mine_revisitor_activated
+ minecraft:player_unlock_bought
+ minecraft:player_unlock_unlocked
+ minecraft:special_mine_completed
- minecraft:used_ender_eye
+ minecraft:used_exit_eye
```

</details>
<details>
<summary>
villager_profession
</summary>

```diff
+ minecraft:traitor
```

</details>
<details>
<summary>
worldgen/chunk_generator
</summary>

```diff
+ minecraft:hub
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
+ minecraft:place_template
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
+ universal_tags/mine_event_type.json
+ universal_tags/player_unlock.json
+ universal_tags/special_mine.json
+ universal_tags/world_effect_set.json
+ universal_tags/world_effect.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:end_portal
- minecraft:end_portal_frame
+ minecraft:mine_travelling_block
+ minecraft:shimmering_door
+ minecraft:sky
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:dimension_control
+ minecraft:mine_crafter
+ minecraft:mine_revisitor
+ minecraft:mob_trophy
+ minecraft:trophy
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:angry_ghast
+ minecraft:cat
+ minecraft:pet_armadillo
+ minecraft:pet_axolotl
+ minecraft:pet_bee
+ minecraft:pet_chicken
+ minecraft:pet_cow
+ minecraft:pet_creeper
+ minecraft:pet_fox
+ minecraft:pet_frog
+ minecraft:pet_mooshroom
+ minecraft:pet_slime
+ minecraft:pet_turtle
+ minecraft:pet_wolf
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:cat
+ minecraft:pet_cat
+ minecraft:pet_polar_bear
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:angry_ghast
+ minecraft:cat
+ minecraft:pet_armadillo
+ minecraft:pet_axolotl
+ minecraft:pet_bee
+ minecraft:pet_chicken
+ minecraft:pet_cow
+ minecraft:pet_creeper
+ minecraft:pet_fox
+ minecraft:pet_frog
+ minecraft:pet_mooshroom
+ minecraft:pet_slime
+ minecraft:pet_turtle
+ minecraft:pet_wolf
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:acting
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:experience_gain_modifier
+ minecraft:max_jumps
+ minecraft:pickup_area_size
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal
- minecraft:end_portal_frame
+ minecraft:mine_crafter
+ minecraft:mine_revisitor
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
+ minecraft:shimmering_door
+ minecraft:sky
+ minecraft:trophy
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
- minecraft:end_portal
+ minecraft:mine_crafter
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal
- minecraft:end_portal_frame
+ minecraft:mine_crafter
+ minecraft:mine_revisitor_block
+ minecraft:mine_travelling_block
+ minecraft:mob_trophy
+ minecraft:shimmering_door
+ minecraft:trophy
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:dimension_id
+ minecraft:exchange_value
+ minecraft:instant_room
+ minecraft:mine_active
+ minecraft:mine_completed
+ minecraft:mob_trophy/type
+ minecraft:sky
+ minecraft:special_mine
+ minecraft:trophy/type
+ minecraft:world_effect_uhint
+ minecraft:world_effect_unlock
+ minecraft:world_modifiers
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:angry_ghast
+ minecraft:pet_armadillo
+ minecraft:pet_axolotl
+ minecraft:pet_bee
+ minecraft:pet_cat
+ minecraft:pet_chicken
+ minecraft:pet_cow
+ minecraft:pet_creeper
+ minecraft:pet_fox
+ minecraft:pet_frog
+ minecraft:pet_mooshroom
+ minecraft:pet_polar_bear
+ minecraft:pet_slime
+ minecraft:pet_turtle
+ minecraft:pet_wolf
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:dimension_control
- minecraft:end_portal_frame
- minecraft:ender_eye
+ minecraft:exit_eye
+ minecraft:fire_wand
+ minecraft:grave_advancement
+ minecraft:mine
+ minecraft:mine_crafter
+ minecraft:mine_ingredient
+ minecraft:mine_revisitor
+ minecraft:mob_trophy
+ minecraft:music_disc_and_action
+ minecraft:shazboots
+ minecraft:shimmering_door
+ minecraft:shimmering_key
+ minecraft:sky
+ minecraft:sky_box
+ minecraft:teleportation_wand
+ minecraft:trophy
+ minecraft:wind_wand
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:acting_stage
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
+ minecraft:dimension_control
+ minecraft:map_making
```

</details>
<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
+ minecraft:shazboots
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:mine_travel
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ nothingtoseehere:and_action
+ nothingtoseehere:crowd_cheer
+ nothingtoseehere:crowd_start
+ nothingtoseehere:crowd_waiting
+ nothingtoseehere:ui.player_unlock_fail
+ nothingtoseehere:ui.player_unlock_success
```

</details>
<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
+ minecraft:consume_poisonous_potatoes
+ minecraft:inventory_cashed_in
+ minecraft:level_completed
+ minecraft:level_failed
+ minecraft:mine_crafter_upgraded
+ minecraft:mine_revisitor_activated
+ minecraft:player_unlock_bought
+ minecraft:player_unlock_unlocked
+ minecraft:special_mine_completed
- minecraft:used_ender_eye
+ minecraft:used_exit_eye
```

</details>
<details>
<summary>
universal_tags/villager_profession.json
</summary>

```diff
+ minecraft:traitor
```

</details>
<details>
<summary>
universal_tags/worldgen/chunk_generator.json
</summary>

```diff
+ minecraft:hub
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:place_template
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
+ dimension_control.json
- end_portal_frame.json
- ender_eye.json
+ exit_eye.json
+ fire_wand.json
+ grave_advancement.json
+ mine_crafter.json
+ mine_ingredient.json
+ mine_revisitor.json
+ mine.json
+ mob_trophy.json
+ music_disc_and_action.json
+ shazboots.json
+ shimmering_door.json
+ shimmering_key.json
+ sky_box.json
+ sky.json
+ teleportation_wand.json
+ trophy.json
+ wind_wand.json
```

</details>
<details>
<summary>
acacia_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allay_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
angler_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
archer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armor_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arms_up_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
baked_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr><tr><td>minecraft:food</td><td><pre>/</pre></td><td><pre>{
  "nutrition": 2,
  "saturation": 0.4
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_chest_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_soup
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.13</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blade_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.7</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.90000004</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bogged_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bolt_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.022222223</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_meal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bordure_indented_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bowl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bread
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
burn_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.89</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
camel_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.7</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
charcoal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.07</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.18</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
closed_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.45000002</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coast_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa_beans
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cookie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cow_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.003</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_heart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crossbow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.90000004</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
danger_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.71999997</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.99</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
debug_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>7</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
disc_fragment_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.11111111</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.19</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dolphin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
donkey_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_breath
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>100</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.26999998</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.16</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
drowned_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dune_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
echo_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elder_guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elytra
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>4.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>4.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enderman_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
endermite_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>4.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_dragon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_pearl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.6</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_crystal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.7</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
evoker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
experience_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
explorer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.90000004</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
eye_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
feather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fermented_spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
field_masoned_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
filled_map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firefly_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_rocket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fishing_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint_and_steel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fox_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
friend_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frog_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.16</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_tear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glistering_melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
globe_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone_dust
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_horn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.16</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.32</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.19999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.28</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.0044444446</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gunpowder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heartbreak_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_of_the_sea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_core
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.19</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
host_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
howl_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
husk_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.24</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.14999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.21</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.0033333332</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
knowledge_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.014</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>3.6000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_lazuli
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lead
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leaf_litter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.049999997</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.07</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lingering_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr><tr><td>minecraft:potion_duration_scale</td><td><pre>0.25</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>10</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cream
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cube_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.0022222223</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
milk_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
miner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mojang_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mooshroom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mourner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mule_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_11
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_13
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_blocks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_cat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_chirp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator_music_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_far
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mellohi
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_otherside
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_pigstep
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_precipice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_relic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_stal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_strad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_wait
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_ward
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
name_tag
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nautilus_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>18</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>6</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>7.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>10.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>4.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_scrap
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_upgrade_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>10</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ocelot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
open_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.90000004</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
painting
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_hanging_moss
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
panda_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
paper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
parrot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_membrane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_brute_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pig_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pillager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_pod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
plenty_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poisonous_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 2,
  "saturation": 1.2
}</pre></td><td><pre>{
  "can_always_eat": true,
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
popped_chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.07</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.71999997</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_crystals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prize_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_pie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.55</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.4</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_foot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_hide
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raiser_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ravager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
recovery_compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.26999998</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.38</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.32</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_clump
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rib_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rotten_flesh
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
saddle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scrape_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sentry_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shaper_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheaf_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shears
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.07</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheep_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelter_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shield
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.07</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silence_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silverfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.18</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.8</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snort_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snout_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snowball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spectral_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spire_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
splash_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.025</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spyglass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.002</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.06</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stray_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
strider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
string
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_instance_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tide_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tipped_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.3</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.23</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
totem_of_undying
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trader_llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.16</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vindicator_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wandering_trader_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warden_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ward_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.089999996</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.12</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.17999999</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.90000004</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1.8000001</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.04</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.005</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wildflowers
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wild_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.9</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wind_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.5</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
witch_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.015</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.01</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
writable_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
written_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.122</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.08</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.03</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.1</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.05</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0.02</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>2</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombified_piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w14craftmine</th></tr><tr><td>minecraft:exchange_value</td><td><pre>/</pre></td><td><pre>0</pre></td></tr></table>
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
+ dimension_control.json
- end_portal_frame.json
- end_portal.json
+ mine_crafter.json
+ mine_revisitor.json
+ mine_travelling_block.json
+ mob_trophy.json
+ shimmering_door.json
+ sky.json
+ trophy.json
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
- ender_eye.json
+ exit_eye.json
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
[C | C | C]
[C | B | C]
[C | D | C]

New pattern:
[A | A | A]
[A | B | A]
[A | D | A]
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
[B | B | B]
[B |   | B]
[B | C | B]

New pattern:
[A | A | A]
[A |   | A]
[A | C | A]
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
[C | A | C]
[C | C | C]

New pattern:
[C | C | C]
[C | B | C]
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
[D | A | D]
[D | C | D]

New pattern:
[D | D | D]
[D | B | D]
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
[B]

New pattern:
[C]
[A]
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
[B | B | B]
[D | D | C]
[B | B | B]

New pattern:
[A | A | A]
[D | D | C]
[A | A | A]
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
[C | D | C]
[C | E | C]

New pattern:
[A | A | A]
[B | D | B]
[B | E | B]
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
+ minecraft:mine_event_type
+ minecraft:player_unlock
+ minecraft:special_mine
+ minecraft:world_effect
+ minecraft:world_effect_set
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
+ advancements.adventure.deluge.description: Complete a Mine while the Water World and Eternal Rain effects are active
+ advancements.adventure.deluge.title: Shall we wait for the drizzle to subside?
+ advancements.adventure.enter_a_mine.description: Enter a Mine
+ advancements.adventure.enter_a_mine.title: Down the Hatch
+ advancements.adventure.level_failed.description: Fail a Mine
+ advancements.adventure.level_failed.title: Oops
+ advancements.adventure.level.description: Complete your first Mine
+ advancements.adventure.level.title: It Begins
+ advancements.adventure.mine_crafter_upgraded.description: Upgrade the Mine Crafter so you can keep mining and crafting
+ advancements.adventure.mine_crafter_upgraded.title: Further beyond
+ advancements.adventure.mine_revisitor_activated.description: Activate a Mine Revisitor
+ advancements.adventure.mine_revisitor_activated.title: Nostalgic
+ advancements.adventure.special_mine_completed.description: Complete a Special Encounter Mine
+ advancements.adventure.special_mine_completed.title: A Challenger Approaches
+ advancements.adventure.water_cave.description: Complete a Mine with Water World and Cave World active
+ advancements.adventure.water_cave.title: The Depths
+ advancements.adventure.water_world.description: Complete a Mine with Water World active
+ advancements.adventure.water_world.title: Quit Smoking
+ advancements.feats.angry_ghast.description: Defeat the Angry Ghast special event
+ advancements.feats.angry_ghast.title: The Baloonslayer
+ advancements.feats.crystal.description: Obtain a crystal to unlock the Warden Special Event
+ advancements.feats.crystal.title: Crystaline
+ advancements.feats.eat_your_veggies.description: Eat 100 Poisonous Potatoes
+ advancements.feats.eat_your_veggies.title: Certified Spud Chomper
+ advancements.feats.end_world.description: Complete a Mine with End Biomes to unlock the Ender Dragon special event
+ advancements.feats.end_world.title: The Beginning of the End
+ advancements.feats.ender_dragon.description: Defeat the Ender Dragon special event
+ advancements.feats.ender_dragon.title: At the Rim of the Sky
+ advancements.feats.enderman.description: Defeat the Enderman special event
+ advancements.feats.enderman.title: Endedman
+ advancements.feats.kill_pillager.description: Kill a Pillager to unlock the Raid special event
+ advancements.feats.kill_pillager.title: Raid the Raiders
+ advancements.feats.kill_skeleton.description: Kill a Skeleton to unlock the Spooky Scary Skeletons special event
+ advancements.feats.kill_skeleton.title: Feel it in my Bones
+ advancements.feats.kuiper_world.description: Defeat the Kuiper World special event
+ advancements.feats.kuiper_world.title: Spaaaaace!
+ advancements.feats.raid.description: Defeat the Raid special event
+ advancements.feats.raid.title: The Pillagers are Coming!
+ advancements.feats.root.description: Feats of Prowess
+ advancements.feats.root.title: Feats
+ advancements.feats.shimmering_key.description: Acquire a Shimmering Key
+ advancements.feats.shimmering_key.title: Master Key
+ advancements.feats.small_but_deadly.description: Defeat the Small but Deadly special event
+ advancements.feats.small_but_deadly.title: Small But Dead
+ advancements.feats.spooky_scary_skeletons.description: Defeat the Spooky Scary Skeletons special event
+ advancements.feats.spooky_scary_skeletons.title: Clattered
+ advancements.feats.warden.description: Defeat the Warden special event
+ advancements.feats.warden.title: Warded
+ advancements.feats.wither_skeleton_skull.description: Acquire a Wither Skeleton Skull to unlock the Wither special event
+ advancements.feats.wither_skeleton_skull.title: Withering
+ advancements.feats.wither.description: Defeat the Wither special event
+ advancements.feats.wither.title: Withered
+ advancements.mine.cash_in.description: Bring a Mine Ingredient to the exit of a Mine to cash it in
+ advancements.mine.cash_in.title: Cash In!
+ advancements.mine.get_mine_ingredient.description: Pick up a Mine Ingredient in a Mine
+ advancements.mine.get_mine_ingredient.title: New Frontiers
+ advancements.mines.all_mine_ingredients.description: Complete at least one Mine with each possible Mine Ingredient
+ advancements.mines.all_mine_ingredients.title: The Ultimate Miner
+ advancements.mines.all_special_mines_completed.description: Complete all Special Encounter Mines
+ advancements.mines.all_special_mines_completed.title: Yes, Boss
- advancements.story.follow_ender_eye.description: Follow an Eye of Ender
- advancements.story.follow_ender_eye.title: Eye Spy
+ advancements.story.follow_exit_eye.description: Craft an Eye of Exit
+ advancements.story.follow_exit_eye.title: Spy Eye
+ advancements.unlocks.all_combatant.description: Complete the 'Combat' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_combatant.title: The Combat Upd... Unlocks
+ advancements.unlocks.all_crafting.description: Complete the 'Crafting' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_crafting.title: The Crafter
+ advancements.unlocks.all_exploration.description: Complete the 'Exploration' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_exploration.title: Adventuring Time
+ advancements.unlocks.all_gatherer.description: Complete the 'Gatherer' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_gatherer.title: The Miner
+ advancements.unlocks.all_pets.description: Complete the 'Pets' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_pets.title: Crazy Cat Kai
+ advancements.unlocks.all_school_of_hard_knocks.description: Complete the 'School of Hard Knocks' Player Unlock tree and then beat a special event Mine
+ advancements.unlocks.all_school_of_hard_knocks.title: An Exercise in Futility
+ advancements.unlocks.free_sticks.description: Is this really spellt like that? Beat a level while having all three wands unlocked
+ advancements.unlocks.free_sticks.title: Free Sticks
+ advancements.unlocks.in_it_together.description: Beat a special Mine with the 'Soul Link' effect active
+ advancements.unlocks.in_it_together.title: In It Together
+ advancements.unlocks.jump_king.description: Obtain the maximum amount of jumps
+ advancements.unlocks.jump_king.title: Jump King
+ advancements.unlocks.player_unlock_bought.description: Buy a player unlock and get better at being you
+ advancements.unlocks.player_unlock_bought.title: Kaizen
+ advancements.unlocks.player_unlock_unlocked.description: Unlock a player unlock so you can unlock more unlocks
+ advancements.unlocks.player_unlock_unlocked.title: How do I unlock that?
+ advancements.unlocks.root.description: Ah, the noble pursuit of self-improvement
+ advancements.unlocks.root.title: Unlocks
+ advancements.unlocks.sigma_grindset.description: Complete the 'Knowledge' Player Unlock tree
+ advancements.unlocks.sigma_grindset.title: Sigma Grindset
+ attribute.name.experience_gain_modifier: Experience Gain Modifier
+ attribute.name.max_jumps: Max Jumps
+ attribute.name.pickup_area_size: Pickup Area Size
+ block.minecraft.bed.no_sleep_for_you: No sleep for you, not today!
+ block.minecraft.dimension_control: Dimension Control
+ block.minecraft.enter_mine_gateway: Enter Mine Gateway
+ block.minecraft.mine_crafter: Mine Crafter
+ block.minecraft.mine_revisitor: Mine Revisitor
+ block.minecraft.mine_travelling_block: Mine Travelling Block
+ block.minecraft.mob_trophy: Trophy
+ block.minecraft.shimmering_door: Shimmering Door
+ block.minecraft.sky: Sky
+ block.minecraft.trophy: Trophy
+ commands.level.success: Created level %s
+ container.dimension_control: Dimension Control
+ container.mine_crafter: Craft your Mine
+ container.mine_crafter.active: Go go go!
+ container.mine_crafter.donate: DONATE
Use %s of your experience to work towards upgrading the Minecrafter Table
+ container.mine_crafter.drawer: Mine Effects
+ container.mine_crafter.fail: Better Luck Next Time
+ container.mine_crafter.hints: Undiscovered
+ container.mine_crafter.level: Level: %s  %s / %s
+ container.mine_crafter.no_hints: You did it!!!
+ container.mine_crafter.won: Mine Successful!
+ death.attack.devour: %1$s was devoured
+ death.attack.devour.item: %1$s was devoured by %2$s using %3$s
+ death.attack.devour.player: %1$s was devoured by %2$s
+ deathScreen.respawn.hardcore: Accept Defeat
+ deathScreen.respawn.inMap: Accept Defeat
+ door.say_the_thing: Doors yearn for the keys!
+ effect.minecraft.shazboots: Shazboots!
+ entity.minecraft.angry_ghast: Angry Ghast
+ entity.minecraft.pet_armadillo: Pet Armadillo
+ entity.minecraft.pet_axolotl: Pet Axolotl
+ entity.minecraft.pet_bee: Pet Bee
+ entity.minecraft.pet_cat: Pet Cat
+ entity.minecraft.pet_chicken: Pet Chicken
+ entity.minecraft.pet_cow: Pet Cow
+ entity.minecraft.pet_creeper: Pet Creeper
+ entity.minecraft.pet_fox: Pet Fox
+ entity.minecraft.pet_frog: Pet Frog
+ entity.minecraft.pet_mooshroom: Pet Mooshroom
+ entity.minecraft.pet_polar_bear: Pet Polar Bear
+ entity.minecraft.pet_slime: Pet Slime
+ entity.minecraft.pet_turtle: Pet Turtle
+ entity.minecraft.pet_wolf: Pet Wolf
+ entity.minecraft.villager.traitor: Traitor
+ gamerule.allBlocksBouncy: All blocks are bouncy
+ gamerule.icyLevel: All blocks are bouncy
+ gui.door: Door
+ gui.door.field.active_door: The Door You Just Clicked
+ gui.door.field.error: Something Wrong
+ gui.door.field.existing_door: Existing door
+ gui.door.field.existing_wall: Existing wall
+ gui.door.field.new_door: Door
+ gui.door.field.new_room: Room
+ gui.door.field.new_wall: Wall
+ gui.door.next: Next
+ gui.door.open: Open
+ gui.door.previous: Previous
+ gui.unlocks: Player Unlocks
+ item.exchange_value: Value: %s
- item.minecraft.ender_eye: Eye of Ender
+ item.minecraft.exit_eye: Eye of Exit
+ item.minecraft.fire_wand: Fire Wand
+ item.minecraft.fire_wand.lore: 'Tiwaz Raido'
+ item.minecraft.grave_advancement: Grave
+ item.minecraft.level_ingredient: Level Ingredient
+ item.minecraft.level: Level
+ item.minecraft.mine_ingredient: Mine Ingredient
+ item.minecraft.mine_ingredient.desc: Mine Ingredient: %s
+ item.minecraft.mine: Mine
+ item.minecraft.mob_trophy.entity: Contents: 1 × Minecraft %s
+ item.minecraft.mob_trophy.grade: Grade: %s
+ item.minecraft.mob_trophy.grade.diamond: Diamond
+ item.minecraft.mob_trophy.grade.gold: Gold
+ item.minecraft.mob_trophy.grade.grass: Grass
+ item.minecraft.mob_trophy.grade.netherite: Netherite
+ item.minecraft.mob_trophy.grade.stone: Stone
+ item.minecraft.mob_trophy.shiny: Oooh, shiny!
+ item.minecraft.music_disc_and_action: Music Disc
+ item.minecraft.music_disc_and_action.desc: Tone Deaf Rebellion - And Action!
+ item.minecraft.shazboots: Shazboots!
+ item.minecraft.shimmering_key: Shimmering Key
+ item.minecraft.shimmering_key.room: Opens "%s"
+ item.minecraft.sky_box: Sky Box
+ item.minecraft.teleportation_wand: Displacement Wand
+ item.minecraft.teleportation_wand.lore: 'Jera Isaz Berkanan'
+ item.minecraft.wind_wand: Wind Wand
+ item.minecraft.wind_wand.lore: 'Kaunan Wunjo Perth Thurisaz'
+ jukebox_song.minecraft.and_action: Tone Deaf Rebellion - And Action!
+ key.unlocks: Unlocks
+ level.gained: You've levelled up to level %s!
+ level.unlock_hint: Press %s to spend levels on unlocks
+ mine.angry_ghast_boss.description: This one's not happy with you
+ mine.angry_ghast_boss.name: Angry Ghast
+ mine.ender_dragon_boss.description: This seems to be the end
+ mine.ender_dragon_boss.name: Ender Dragon
+ mine.enderman_boss.description: That Enderman in particular
+ mine.enderman_boss.name: The Enderman
+ mine.enter: Entering Mine in: %s seconds
+ mine.enter.aborted: No longer entering Mine
+ mine.enter.started: Entering Mine...
+ mine.kuiper_belt.description: Igloo in spaaaaace!
+ mine.kuiper_belt.name: Kuiper World
+ mine.leave: Leaving Mine in: %s seconds
+ mine.leave.aborted: No longer leaving Mine
+ mine.leave.started: Leaving Mine...
+ mine.lost: MINE FAILED
+ mine.raid.description: Defend the village!
+ mine.raid.name: Raid
+ mine.small_but_deadly_boss.description: Better have good aim
+ mine.small_but_deadly_boss.name: Small but Deadly
+ mine.spooky_scary_skeletons_boss.description: Shrieking skulls will shock your soul
+ mine.spooky_scary_skeletons_boss.name: Spooky Scary Skeletons
+ mine.warden_boss.description: Get your groove on
+ mine.warden_boss.name: Warden
+ mine.wither_boss.description: DANGER DANGER
+ mine.wither_boss.name: Wither
+ mine.won: MINE COMPLETED SUCCESSFULLY
+ mine.won.rewards: %s earned %s exp
+ minecraftlike.pack_name: Level %s
+ multiplayer.enteringMap.0: Entering mine...
+ multiplayer.enteringMap.1: Doing something very important...
+ multiplayer.enteringMap.10: Absolutely placing the entire world one block at a time...
+ multiplayer.enteringMap.11: All your blocks are exactly where you left them
+ multiplayer.enteringMap.12: Poisoning potatoes...
+ multiplayer.enteringMap.13: Voting for mobs...
+ multiplayer.enteringMap.14: Infinitely creating dimensions...
+ multiplayer.enteringMap.15: Travelling back to the 90's...
+ multiplayer.enteringMap.16: Increasing texture details...
+ multiplayer.enteringMap.17: Making a portable console...
+ multiplayer.enteringMap.18: Following the trends...
+ multiplayer.enteringMap.19: Adding sugar, spice and everything that is nice...
+ multiplayer.enteringMap.2: Placing all of the little blocks in the world..
+ multiplayer.enteringMap.20: Turning players into villagers...
+ multiplayer.enteringMap.21: Making collabs...
+ multiplayer.enteringMap.22: Acquiring MineCoins[tm]...
+ multiplayer.enteringMap.23: Now in 4D!
+ multiplayer.enteringMap.24: It’s now NOT safe to turn off your computer
+ multiplayer.enteringMap.25: Reticulating splines...
+ multiplayer.enteringMap.26: Filling up to the line on a cup...
+ multiplayer.enteringMap.27: Smoking these blocks...
+ multiplayer.enteringMap.28: Adding seven mountains and seven seas...
+ multiplayer.enteringMap.29: Reheating old jokes...
+ multiplayer.enteringMap.3: Hiding stuff...
+ multiplayer.enteringMap.30: Letting the cat out...
+ multiplayer.enteringMap.31: Letting the cat in...
+ multiplayer.enteringMap.32: Making everyone confused...
+ multiplayer.enteringMap.33: Not incrementing the version...
+ multiplayer.enteringMap.34: Looking under the couch cushions for extra features...
+ multiplayer.enteringMap.35: Checking if everything Works As Intended...
+ multiplayer.enteringMap.36: Simulating epic histories of underground kingdoms...
+ multiplayer.enteringMap.37: Spreading the rumors...
+ multiplayer.enteringMap.38: Sprinkling just a pinch of extra blocks on the top...
+ multiplayer.enteringMap.39: Turning the lights on...
+ multiplayer.enteringMap.4: Making a mess...
+ multiplayer.enteringMap.40: Just wasting time until I remember what to do next...
+ multiplayer.enteringMap.41: Displaying this message...
+ multiplayer.enteringMap.42: Forgetting about something important...
+ multiplayer.enteringMap.43: Ruining the game...
+ multiplayer.enteringMap.44: Walking 500 miles...
+ multiplayer.enteringMap.45: Walking 500 more...
+ multiplayer.enteringMap.46: Finding a Programmer to get some Art made...
+ multiplayer.enteringMap.47: Breaking some farms...
+ multiplayer.enteringMap.48: Spilling out lava from buckets...
+ multiplayer.enteringMap.49: Changing my mind and removing some blocks again...
+ multiplayer.enteringMap.5: Trying my best...
+ multiplayer.enteringMap.6: Forgot something, probably not important...
+ multiplayer.enteringMap.7: Turning off and back on again...
+ multiplayer.enteringMap.8: Don't worry about it...
+ multiplayer.enteringMap.9: Introducing jank...
+ player.kick.too_long: Too slow, try connecting again
+ room.minecraft.barrels: Storage (barrels)
+ room.minecraft.boiler: Boiler Room
+ room.minecraft.carpet: Relax Room
+ room.minecraft.corridor_simple: Boring Corridor
+ room.minecraft.fountain: Fountain
+ room.minecraft.grassy_h: Junction (grass)
+ room.minecraft.hanging: Storage (hanging barrels)
+ room.minecraft.house: Wow, A Whole House? At This Price?
+ room.minecraft.labyrinth: Labyrinth
+ room.minecraft.pool: Deep Pool
+ room.minecraft.ship: Ship
+ room.minecraft.simple: Test Room Please Ignore
+ room.minecraft.stairs: Stairs
+ room.minecraft.storage1: Storage (simple)
+ room.minecraft.storage2: Storage (less simple)
+ room.minecraft.sugar_h: Junction (cane)
+ room.minecraft.tree: Tree
+ room.minecraft.trophy: Vintage Trophy Room
+ room.minecraft.tunnel: Line
+ room.minecraft.useless: Useless Room
+ room.minecraft.wheat_h: Junction (wheat)
+ room.minecraft.workshop: Workshop
+ sky.actual_sky: True Sky
+ sky.atlas: Bad Idea
+ sky.classic_hub: Hub (classic)
+ sky.code: Dev Mode
+ sky.end: The End
+ sky.missing: Missing
+ sky.overworld: Overworld
+ sky.panorama: Smol
+ sky.tooltip: Sky: %s
+ subtitles.entity.villager.work_traitor: Traitor works
+ trophy.gold: Golden Cup
+ trophy.mega_spud: Mega Spud
+ trophy.no_medal: "Close But No" Medal
+ unlocks.player.unlocked: 🔓 %s unlocked %s
+ unlocks.screen.active: Active | Unlocked
+ unlocks.screen.hint: Hint: %s
+ unlocks.screen.inactive: Inactive | Unlocked
+ unlocks.screen.locked: Cost: %s
+ unlocks.screen.points: Levels: %s
+ unlocks.screen.unlocked: Unlocked
+ unlocks.unlock.alchemy.description: A brewing stand for all your brewing needs
+ unlocks.unlock.alchemy.name: Alchemy
+ unlocks.unlock.allez_cuisine.description: Add a little flair to your brewing
+ unlocks.unlock.allez_cuisine.name: Allez Cuisine!
+ unlocks.unlock.amphibian.description: Fast as the fish!
+ unlocks.unlock.amphibian.name: Amphibian
+ unlocks.unlock.apprentice_shoveler.description: Working your way up in the shoveling business
+ unlocks.unlock.apprentice_shoveler.name: Apprentice Shoveler
+ unlocks.unlock.archer.description: We would've called this unlock sagittarii but someone said it sounded weird and that no one speaks Latin anymore
+ unlocks.unlock.archer.name: Archer
+ unlocks.unlock.armaments.description: Sticks and stones may break your bones, but they probably shouldn't
+ unlocks.unlock.armaments.name: Armaments
+ unlocks.unlock.arrowverse.description: Shoot to your heart's content. Don't forget your bow!
+ unlocks.unlock.arrowverse.name: Arrowverse
+ unlocks.unlock.berserker.description: What's better than one Diamond Axe?
+ unlocks.unlock.berserker.name: Berserker
+ unlocks.unlock.best_starter_sword.description: Definitely worth the investment!
+ unlocks.unlock.best_starter_sword.name: No Nether Needed
+ unlocks.unlock.better_starter_sword.description: I can't believe they're just handing these out!
+ unlocks.unlock.better_starter_sword.name: Shiny Sword
+ unlocks.unlock.bundle_of_fortune.description: Here's a bundle of random stuff, don't question it
+ unlocks.unlock.bundle_of_fortune.name: Bundle of Fortune
+ unlocks.unlock.campfire.description: You get a Campfire to start with
+ unlocks.unlock.campfire.name: Starter Campfire
+ unlocks.unlock.chopper.description: Works for trees and limbs
+ unlocks.unlock.chopper.name: Chopper
+ unlocks.unlock.combatant.description: Gain an advantage in battle
+ unlocks.unlock.combatant.name: Combat
+ unlocks.unlock.crafting_efficiency.description: Are you sure you need all of these materials?
+ unlocks.unlock.crafting_efficiency.hint: You can never have too many crafting tables
+ unlocks.unlock.crafting_efficiency.name: Artisan Crafting
+ unlocks.unlock.crafting.description: Imagine taking two things and combining them into one!
+ unlocks.unlock.crafting.name: Crafting
+ unlocks.unlock.crusher.description: Made from the heaviest matter in the universe
+ unlocks.unlock.crusher.name: The Natural Evolution of a Shield
+ unlocks.unlock.decked_out.description: Made from the finest leather
+ unlocks.unlock.decked_out.name: Decked out
+ unlocks.unlock.dirt_connoisseur.description: I wonder if it tastes like butter as well?
+ unlocks.unlock.dirt_connoisseur.name: Dirt Connoisseur
+ unlocks.unlock.dirt_destroyer_1.description: Carve through dirt like butter!
+ unlocks.unlock.dirt_destroyer_1.name: Dirt is Butter
+ unlocks.unlock.dirt_destroyer_2.description: I crave more!
+ unlocks.unlock.dirt_destroyer_2.name: Mmmmm Dirt Butter
+ unlocks.unlock.dirt_destroyer.description: Carve through dirt like butter!
+ unlocks.unlock.dirt_destroyer.name: Dirt is Butter
+ unlocks.unlock.dirt_enjoyer_1.description: You appreciate the value of Dirt
+ unlocks.unlock.dirt_enjoyer_1.name: Dirt Enjoyer
+ unlocks.unlock.dirt_enjoyer_2.description: You enjoy Dirt more than others
+ unlocks.unlock.dirt_enjoyer_2.name: Dirt Fanatic
+ unlocks.unlock.dirt_enjoyer_3.description: I love Dirt, Dirt loves me back?
+ unlocks.unlock.dirt_enjoyer_3.name: Dirt Lover
+ unlocks.unlock.dragon_fire.description: Add a bit of draconic flair to your fireballs
+ unlocks.unlock.dragon_fire.hint: Get some first hand experience with dragon fire after unlocking the spellbook
+ unlocks.unlock.dragon_fire.name: Dragon Fire
+ unlocks.unlock.efficient_enchanting.description: By combining the aether-flux with quantum displacement while clamping the manifold parameters required to channel the arcane infusion hex we may temporarily fold this plane of existence to subvert the requirement of equivalence of exchange
+ unlocks.unlock.efficient_enchanting.name: Efficient Enchanting
+ unlocks.unlock.elytra.description: A singular one
+ unlocks.unlock.elytra.name: Elytron
+ unlocks.unlock.enchanting.description: Heh, imagine wasting experience points on this
+ unlocks.unlock.enchanting.name: Enchanting
+ unlocks.unlock.ender_pearl_starter.description: Best mode of transportaion!
+ unlocks.unlock.ender_pearl_starter.hint: Pooof, and it's somewhere else?
+ unlocks.unlock.ender_pearl_starter.name: Let's get Pearling
+ unlocks.unlock.expert_shoveler.description: No mound is safe
+ unlocks.unlock.expert_shoveler.name: Expert Shoveler
+ unlocks.unlock.exploration.description: Get off to a flying start!
+ unlocks.unlock.exploration.name: Exploration
+ unlocks.unlock.extra_firepower.description: Enhances fires near (and on) you
+ unlocks.unlock.extra_firepower.name: Extra Firepower
+ unlocks.unlock.fire_shield.description: Your shield now comes with complimentary fire immunity
+ unlocks.unlock.fire_shield.hint: Maybe DO touch the campfire after unlocking the spellbook
+ unlocks.unlock.fire_shield.name: Fire Shield
+ unlocks.unlock.fire_wand.description: I'm pretty sure this is misnamed
+ unlocks.unlock.fire_wand.hint: Defeat a fiery flying enemy
+ unlocks.unlock.fire_wand.name: Leaf
+ unlocks.unlock.fishing_rod.description: Were you catching fish with your hands?
+ unlocks.unlock.fishing_rod.name: Angler
+ unlocks.unlock.fishing.description: Increases your luck while fishing
+ unlocks.unlock.fishing.name: The Mining of the Sea
+ unlocks.unlock.fletcher.description: Wouldn't it be nice if you had somewhere to make more arrows? No? Alright, these will have to do then
+ unlocks.unlock.fletcher.name: Fletcher
+ unlocks.unlock.full_metal.description: A full suit of armour, no alchemy needed
+ unlocks.unlock.full_metal.name: Full Metal
+ unlocks.unlock.gatherer.description: Crops, berry bushes and bee hives have a chance of dropping extra loot
+ unlocks.unlock.gatherer.name: Gatherer
+ unlocks.unlock.golden_starter_apples.description: Bring a feast with you
+ unlocks.unlock.golden_starter_apples.name: Golden Apples
+ unlocks.unlock.hunter.description: Aren't these supposed to be the other way? Anyways, animals killed have a chance of dropping extra loot
+ unlocks.unlock.hunter.name: Hunter
+ unlocks.unlock.inventory_crafting_3x3.description: No need for a crafting table
+ unlocks.unlock.inventory_crafting_3x3.hint: Have you tried crafting yet? It's pretty cool!
+ unlocks.unlock.inventory_crafting_3x3.name: 3x3 Inventory Crafting
+ unlocks.unlock.inventory_crafting.description: Ability to craft in the inventory!
+ unlocks.unlock.inventory_crafting.name: Inventory Crafting
+ unlocks.unlock.inventory_slots_1.description: Maybe you shouldn't hold all of those blocks in your hands
+ unlocks.unlock.inventory_slots_1.name: Pockets
+ unlocks.unlock.inventory_slots_2.description: Wouldn't it be nice if you had some more slots?
+ unlocks.unlock.inventory_slots_2.name: Deeper Pockets
+ unlocks.unlock.inventory_slots_3.description: Surely you wouldn't need any more slots?
+ unlocks.unlock.inventory_slots_3.name: Deepest Pockets
+ unlocks.unlock.journeyman_shoveler.description: It's hard work, but someone has to do it
+ unlocks.unlock.journeyman_shoveler.name: Journeyman Shoveler
+ unlocks.unlock.jump_king_10.description: You won't get any higher than this
+ unlocks.unlock.jump_king_10.name: +1 jump
+ unlocks.unlock.jump_king_2.description: What could go wrong?
+ unlocks.unlock.jump_king_2.name: +1 jump
+ unlocks.unlock.jump_king_3.description: A valuable trove
+ unlocks.unlock.jump_king_3.name: +1 jump
+ unlocks.unlock.jump_king_4.description: I have to save the princess!
+ unlocks.unlock.jump_king_4.name: +1 jump
+ unlocks.unlock.jump_king_5.description: Imagine falling from this
+ unlocks.unlock.jump_king_5.name: +1 jump
+ unlocks.unlock.jump_king_6.description: What comes up, ...
+ unlocks.unlock.jump_king_6.name: +1 jump
+ unlocks.unlock.jump_king_7.description: Gotta reach the top of the castle
+ unlocks.unlock.jump_king_7.name: +1 jump
+ unlocks.unlock.jump_king_8.description: Not scared of heights are you?
+ unlocks.unlock.jump_king_8.name: +1 jump
+ unlocks.unlock.jump_king_9.description: Don't look down
+ unlocks.unlock.jump_king_9.name: +1 jump
+ unlocks.unlock.jump_king.description: Reach new heights!
+ unlocks.unlock.jump_king.name: +1 jump
+ unlocks.unlock.learning_1.description: Get more experience after each Mine
+ unlocks.unlock.learning_1.name: Learning
+ unlocks.unlock.learning_10.description: Get more experience after each Mine
+ unlocks.unlock.learning_10.name: Learning 10
+ unlocks.unlock.learning_11.description: Get more experience after each Mine
+ unlocks.unlock.learning_11.name: Learning 11
+ unlocks.unlock.learning_12.description: Get more experience after each Mine
+ unlocks.unlock.learning_12.name: Learning 12
+ unlocks.unlock.learning_13.description: Get more experience after each Mine
+ unlocks.unlock.learning_13.name: Learning 13
+ unlocks.unlock.learning_14.description: Get more experience after each Mine
+ unlocks.unlock.learning_14.name: Learning 14
+ unlocks.unlock.learning_15.description: Get more experience after each Mine
+ unlocks.unlock.learning_15.name: Learning 15
+ unlocks.unlock.learning_16.description: Get more experience after each Mine
+ unlocks.unlock.learning_16.name: Learning 16
+ unlocks.unlock.learning_17.description: Get more experience after each Mine
+ unlocks.unlock.learning_17.name: Learning 17
+ unlocks.unlock.learning_18.description: Get more experience after each Mine
+ unlocks.unlock.learning_18.name: Learning 18
+ unlocks.unlock.learning_19.description: Get more experience after each Mine
+ unlocks.unlock.learning_19.name: Learning 19
+ unlocks.unlock.learning_2.description: Get more experience after each Mine
+ unlocks.unlock.learning_2.name: Learning 2
+ unlocks.unlock.learning_20.description: Get more experience after each Mine
+ unlocks.unlock.learning_20.name: Learning 20
+ unlocks.unlock.learning_3.description: Get more experience after each Mine
+ unlocks.unlock.learning_3.name: Learning 3
+ unlocks.unlock.learning_4.description: Get more experience after each Mine
+ unlocks.unlock.learning_4.name: Learning 4
+ unlocks.unlock.learning_5.description: Get more experience after each Mine
+ unlocks.unlock.learning_5.name: Learning 5
+ unlocks.unlock.learning_6.description: Get more experience after each Mine
+ unlocks.unlock.learning_6.name: Learning 6
+ unlocks.unlock.learning_7.description: Get more experience after each Mine
+ unlocks.unlock.learning_7.name: Learning 7
+ unlocks.unlock.learning_8.description: Get more experience after each Mine
+ unlocks.unlock.learning_8.name: Learning 8
+ unlocks.unlock.learning_9.description: Get more experience after each Mine
+ unlocks.unlock.learning_9.name: Learning 9
+ unlocks.unlock.lodestone_exits.description: Compasses point to the nearest exit
+ unlocks.unlock.lodestone_exits.name: Lodestone Exits
+ unlocks.unlock.lucky_pick.description: Ore more?
+ unlocks.unlock.lucky_pick.name: Lucky pick
+ unlocks.unlock.magic_master_kit.description: We grant you a seat at the council, but we do not grant you the rank of master
+ unlocks.unlock.magic_master_kit.name: Master Magic Kit
+ unlocks.unlock.magic_starter_kit.description: Every apprentice needs this
+ unlocks.unlock.magic_starter_kit.name: Magic Kit
+ unlocks.unlock.mass_production.description: Now you're cooking
+ unlocks.unlock.mass_production.name: Haute cuisine
+ unlocks.unlock.master_shoveler.description: A tool fit for the Dirt Master
+ unlocks.unlock.master_shoveler.name: Master Shoveler
+ unlocks.unlock.mega_jump.description: Where did the gravity go?!
+ unlocks.unlock.mega_jump.hint: Some things jump high
+ unlocks.unlock.mega_jump.name: MEGA JUMP
+ unlocks.unlock.mining_efficiency_2.description: Dig, dig, dig
+ unlocks.unlock.mining_efficiency_2.name: Mining effeicenter
+ unlocks.unlock.mining_efficiency_3.description: Dig, dig, dig, and dig
+ unlocks.unlock.mining_efficiency_3.name: Mining effeicentest
+ unlocks.unlock.mining_efficiency.description: Dig, dig
+ unlocks.unlock.mining_efficiency.name: Mining effeicency
+ unlocks.unlock.mining.description: What it's all about
+ unlocks.unlock.mining.name: Mining
+ unlocks.unlock.mise_en_place.description: Mommy never had to face the dinner rush
+ unlocks.unlock.mise_en_place.name: Mise en place
+ unlocks.unlock.more_more_pearls.description: PEARLOMANIAC
+ unlocks.unlock.more_more_pearls.name: When yhou just can't get enough!
+ unlocks.unlock.more_pearls.description: Gimme more, MORE!
+ unlocks.unlock.more_pearls.name: Pearltastic
+ unlocks.unlock.more_starter_apples.description: Bring a meal with you
+ unlocks.unlock.more_starter_apples.name: More Apples
+ unlocks.unlock.movement_boost.description: Gotta go faster!
+ unlocks.unlock.movement_boost.name: Speedrun
+ unlocks.unlock.ore_seeker_1.description: More for ore!
+ unlocks.unlock.ore_seeker_1.name: Ore Seeker
+ unlocks.unlock.ore_seeker_2.description: Even more, more for ore!
+ unlocks.unlock.ore_seeker_2.name: Ore Seeker: 2
+ unlocks.unlock.pathfinder.description: Stop hitting yourself (when using Eye of Exit)
+ unlocks.unlock.pathfinder.name: Pathfinder
+ unlocks.unlock.pet_armadillo.description: Rollout!
+ unlocks.unlock.pet_armadillo.name: Pet Armadillo
+ unlocks.unlock.pet_axolotl.description: He likes you a lotl
+ unlocks.unlock.pet_axolotl.name: Pet Axolotl
+ unlocks.unlock.pet_bee.description: Bzzzzzzzzzzz
+ unlocks.unlock.pet_bee.name: Pet Bee
+ unlocks.unlock.pet_cat.description: Pawsitiviely Purrrrfect
+ unlocks.unlock.pet_cat.name: Pet Cat
+ unlocks.unlock.pet_chicken.description: More courageous than you think
+ unlocks.unlock.pet_chicken.name: Pet Chicken
+ unlocks.unlock.pet_cow.description: The cow says: "Moooooo"
+ unlocks.unlock.pet_cow.name: Pet Cow
+ unlocks.unlock.pet_creeper.description: This one is more "Aww cute!" than "Aww man!"
+ unlocks.unlock.pet_creeper.name: Pet Creeper
+ unlocks.unlock.pet_fox.description: What does it say?
+ unlocks.unlock.pet_fox.name: Pet Fox
+ unlocks.unlock.pet_frog.description: This one won't turn into a prince
+ unlocks.unlock.pet_frog.name: Pet Frog
+ unlocks.unlock.pet_mooshroom.description: The hivemind echoes in your head: "MOOOOOO"
+ unlocks.unlock.pet_mooshroom.name: Pet Mooshroom
+ unlocks.unlock.pet_polar_bear.description: Nice kitty!
+ unlocks.unlock.pet_polar_bear.name: Pet Polar Bear
+ unlocks.unlock.pet_slime.description: Sticky!
+ unlocks.unlock.pet_slime.name: Pet Slime
+ unlocks.unlock.pet_the_animal.description: Can I pet that DAWG?
+ unlocks.unlock.pet_the_animal.name: Pet your pets
+ unlocks.unlock.pet_turtle.description: A shell of protection
+ unlocks.unlock.pet_turtle.name: Pet Turtle
+ unlocks.unlock.pet_wolf_armored.description: Always wear protection
+ unlocks.unlock.pet_wolf_armored.name: Armor up
+ unlocks.unlock.pet_wolf_big.description: The bigger the better
+ unlocks.unlock.pet_wolf_big.name: Direwolf
+ unlocks.unlock.pet_wolf_sword.description: Voracious like no other
+ unlocks.unlock.pet_wolf_sword.name: Descendant of Sif
+ unlocks.unlock.pet_wolf.description: Who's a good boy?
+ unlocks.unlock.pet_wolf.name: Pet Wolf
+ unlocks.unlock.pet.description: The game is better with a friend
+ unlocks.unlock.pet.name: Pets
+ unlocks.unlock.pets.description: This one's just here to annoy you
+ unlocks.unlock.pets.name: Pets
+ unlocks.unlock.pickup_area_size.description: Now those are some long arms!
+ unlocks.unlock.pickup_area_size.name: Collector
+ unlocks.unlock.poseidon.description: Might as well run with it
+ unlocks.unlock.poseidon.name: Poseidon
+ unlocks.unlock.proper_walking_pace.description: Why the rush?
+ unlocks.unlock.proper_walking_pace.name: Proper Walking Pace
+ unlocks.unlock.quiver.description: Hey, you forgot these
+ unlocks.unlock.quiver.name: Quiver
+ unlocks.unlock.rare_earth_specialist.description: You yearn for rare earth materials
+ unlocks.unlock.rare_earth_specialist.name: Rare Earth Specialist
+ unlocks.unlock.rewrite_in_rust.description: Rewrite your gear in rust
+ unlocks.unlock.rewrite_in_rust.name: Rewrite in Rust
+ unlocks.unlock.rockets.description: The state of the art mode of transportation, totally safe!
+ unlocks.unlock.rockets.name: Booster
+ unlocks.unlock.runemaster.description: A PhD in Enchanting? In this job market?
+ unlocks.unlock.runemaster.name: Runemaster
+ unlocks.unlock.safe_falling.description: This might help now
+ unlocks.unlock.safe_falling.name: Safe Falling
+ unlocks.unlock.school_of_actual_hard_knocks.description: Take your time when mining
+ unlocks.unlock.school_of_actual_hard_knocks.name: School of Actual Hard Knocks
+ unlocks.unlock.school_of_hard_knocks.description: Take your time when learning
+ unlocks.unlock.school_of_hard_knocks.name: School of Hard Knocks
+ unlocks.unlock.shazboots.description: Terrain permitting, practice skiing if you can. VGS!
+ unlocks.unlock.shazboots.name: Shazboots!
+ unlocks.unlock.shield_bash.description: You know, I never knew you could just put this in your main hand
+ unlocks.unlock.shield_bash.name: Shield Bash
+ unlocks.unlock.silky_pick.description: More ore?
+ unlocks.unlock.silky_pick.name: Silky pick
+ unlocks.unlock.smelt_value_1.description: Gain more experience from things smelted
+ unlocks.unlock.smelt_value_1.name: Heart of gold
+ unlocks.unlock.smelt_value_2.description: Gain even more experience from things smelted
+ unlocks.unlock.smelt_value_2.name: Heart of Netherite?
+ unlocks.unlock.smelter_1.description: You dabble in smelting
+ unlocks.unlock.smelter_1.name: Apprentice Smelter
+ unlocks.unlock.smelter_2.description: You have mastered the art of smelting
+ unlocks.unlock.smelter_2.name: Master Smelter
+ unlocks.unlock.sneak_1.description: Sneak as fast as when holding both 'w' and 'a' or 'd'
+ unlocks.unlock.sneak_1.name: Swift sneaking
+ unlocks.unlock.sneak_2.description: Now this is possibly even faster than running?
+ unlocks.unlock.sneak_2.name: Swiftest sneak
+ unlocks.unlock.sorcerer_supreme.description: Endless possibility... with the right tools!
+ unlocks.unlock.sorcerer_supreme.name: Spellbook
+ unlocks.unlock.speed_1.description: Amazing game, and super fast!
+ unlocks.unlock.speed_1.name: Need for speed
+ unlocks.unlock.speed_2.description: Wow, and this is even better
+ unlocks.unlock.speed_2.name: Need for speed: II
+ unlocks.unlock.speed_3.description: Maybe this is as good as it gets?
+ unlocks.unlock.speed_3.name: Hot Pursuit
+ unlocks.unlock.starter_apples.description: Bring a snack with you
+ unlocks.unlock.starter_apples.name: Doctors order
+ unlocks.unlock.starter_compass.description: Gives a starter compass, how handy!
+ unlocks.unlock.starter_compass.name: Starter Compass
+ unlocks.unlock.starter_crafting.description: This might come in handy to always have
+ unlocks.unlock.starter_crafting.name: Crafting table
+ unlocks.unlock.starter_pick.description: Look at that, imagine starting with that
+ unlocks.unlock.starter_pick.name: Starting pickaxe
+ unlocks.unlock.starter_shield.description: Better safe than sorry
+ unlocks.unlock.starter_shield.name: Warded
+ unlocks.unlock.starter_sword_iron.description: Upgrade your starter sword
+ unlocks.unlock.starter_sword_iron.name: You call that a knoife?
+ unlocks.unlock.starter_sword.description: It might not be much, but it's yours
+ unlocks.unlock.starter_sword.name: Training Sword
+ unlocks.unlock.sub_mining_efficiency.description: Submerged mining efficiency
+ unlocks.unlock.sub_mining_efficiency.hint: Win a map in a place where water is everything
+ unlocks.unlock.sub_mining_efficiency.name: Underwater miner
+ unlocks.unlock.teleportation_wand.description: There and back again
+ unlocks.unlock.teleportation_wand.hint: Defeat a terrifying teleporting enemy
+ unlocks.unlock.teleportation_wand.name: Enigma
+ unlocks.unlock.thorns_plus_plus.description: Make sure to report any bugs to /dev/null
+ unlocks.unlock.thorns_plus_plus.name: Thorns++
+ unlocks.unlock.tracker.description: They're not getting away
+ unlocks.unlock.tracker.name: Tracker
+ unlocks.unlock.trident.description: Are you sure this is the right tree?
+ unlocks.unlock.trident.name: Spearfishing
+ unlocks.unlock.varangian.description: These trees will rue the day they crossed you
+ unlocks.unlock.varangian.name: Varangian
+ unlocks.unlock.viking.description: This woodcutter is also good at sailing
+ unlocks.unlock.viking.name: Viking
+ unlocks.unlock.wind_wand.description: Watch out for the wind!
+ unlocks.unlock.wind_wand.hint: Defeat a bouncy breezy enemy
+ unlocks.unlock.wind_wand.name: Heart of the Oak
+ unlocks.unlock.wing_guardian_lift_off_to_the_sky.description: Feathers can help you reach for the sky
+ unlocks.unlock.wing_guardian_lift_off_to_the_sky.hint: The first pioneers of flight weren't always successful, maybe you can do better after unlocking the spellbook
+ unlocks.unlock.wing_guardian_lift_off_to_the_sky.name: Wing Guardian Leaf In Ocean
+ unlocks.unlock.you_are_the_campfire.description: Do I need to say it again? You are the campfire!
+ unlocks.unlock.you_are_the_campfire.name: You Are the Campfire
+ world.effect.amplified.description: What... up THERE?
+ world.effect.amplified.hint: Place a block high up in the world
+ world.effect.amplified.name: Amplified World
+ world.effect.angry_ghast_boss_fight.description: This one's not happy with you
+ world.effect.angry_ghast_boss_fight.hint: Give a Ghast a taste of its own medicine
+ world.effect.angry_ghast_boss_fight.name: Angry Ghast Boss
+ world.effect.armadillos.description: Careful, you might scare them
+ world.effect.armadillos.hint: They like being brushed
+ world.effect.armadillos.name: Armadillos
+ world.effect.axolotls.description: Anybody got a bucket?
+ world.effect.axolotls.hint: Slippery!
+ world.effect.axolotls.name: Axolotls
+ world.effect.badlands.description: Lands took a turn for the bad
+ world.effect.badlands.hint: Play in the mud
+ world.effect.badlands.name: Badlands Biomes
+ world.effect.base_andesite.description: The mountains are made of Andesite
+ world.effect.base_andesite.hint: Mine Andesite
+ world.effect.base_andesite.name: Base rock type: Andesite
+ world.effect.base_blackstone.description: The mountains are made of Blackstone
+ world.effect.base_blackstone.hint: Mine Blackstone
+ world.effect.base_blackstone.name: Base rock type: Blackstone
+ world.effect.base_deepslate.description: The mountains are made of Deepslate
+ world.effect.base_deepslate.hint: Mine Deepslate
+ world.effect.base_deepslate.name: Base rock type: Deepslate
+ world.effect.base_diorite.description: The mountains are made of Diorite
+ world.effect.base_diorite.hint: Mine Diorite
+ world.effect.base_diorite.name: Base rock type: Diorite
+ world.effect.base_end_stone.description: The mountains are made of End Stone
+ world.effect.base_end_stone.hint: Mine End Stone
+ world.effect.base_end_stone.name: Base rock type: End Stone
+ world.effect.base_granite.description: The mountains are made of Granite
+ world.effect.base_granite.hint: Mine Granite
+ world.effect.base_granite.name: Base rock type: Granite
+ world.effect.base_stone.description: The mountains are made of Stone
+ world.effect.base_stone.name: Base rock type: Stone
+ world.effect.base_tuff.description: The mountains are made of Tuff
+ world.effect.base_tuff.hint: Mine Tuff
+ world.effect.base_tuff.name: Base rock type: Tuff
+ world.effect.bees.description: No, not the bees! NOT THE BEES!
+ world.effect.bees.hint: You've killed their brother. Now they're out for revenge.
+ world.effect.bees.name: Bees
+ world.effect.blazes.description: They're all the hotness right now!
+ world.effect.blazes.hint: Go mining in a Nether biome
+ world.effect.blazes.name: Blazes
+ world.effect.bouncy.description: Release your inner slime
+ world.effect.bouncy.hint: Find and kill some Slime
+ world.effect.bouncy.name: Bouncy Blocks
+ world.effect.breezes.description: These ones should be a breeze!
+ world.effect.breezes.hint: Trial spawners might have something to unlock this
+ world.effect.breezes.name: Breezes
+ world.effect.cave_exits.description: Mine Exits are found in caves
+ world.effect.cave_exits.hint: Unlock Cave Mines or test your luck with Deepslate
+ world.effect.cave_exits.name: Cave Exits
+ world.effect.cave_spiders.description: Perilous Poisonous Pests
+ world.effect.cave_spiders.hint: From Spiders
+ world.effect.cave_spiders.name: Cave Spiders
+ world.effect.cave_world.description: And they call it a Mine? A Mine!
+ world.effect.cave_world.hint: Break a block deep down in the world
+ world.effect.cave_world.name: Cave World
+ world.effect.chickens.description: Who came first? Clearly the chicken, in this mine
+ world.effect.chickens.name: Chickens
+ world.effect.convert: Bring this item to the Mine exit to convert to experience
+ world.effect.cows.description: Moo
+ world.effect.cows.name: Cows
+ world.effect.creepers.description: Tssssssssss
+ world.effect.creepers.hint: I sense a theme, found while slaying monsters!
+ world.effect.creepers.name: Creepers
+ world.effect.dark_cave_world.description: Hello? Who turned off the lights?
+ world.effect.dark_cave_world.hint: Win a Special Encounter Mine
+ world.effect.dark_cave_world.name: Dark Cave World
+ world.effect.dark_forests.description: Can't see the forests for all the trees
+ world.effect.dark_forests.hint: Again!? Search among the leaves!
+ world.effect.dark_forests.name: Dark Forest Biomes
+ world.effect.deep_dark.description: The (maybe not so) Deep (and also maybe not entirely) Dark
+ world.effect.deep_dark.hint: Search among blocks in a dark place...
+ world.effect.deep_dark.name: Deep Dark Biome
+ world.effect.desert.description: It's getting hot in here
+ world.effect.desert.hint: Play in the sand
+ world.effect.desert.name: Desert Biome
+ world.effect.dry_land.description: Gronk thirsty. Gronk drink ALL water!
+ world.effect.dry_land.hint: Try to get even warmer in the Badlands
+ world.effect.dry_land.name: Dry Land
+ world.effect.end.description: How did we End up here?
+ world.effect.end.hint: What creatures do you usually kill to get to the end?
+ world.effect.end.name: End Biomes
+ world.effect.ender_dragon_boss_fight.description: You already know this one
+ world.effect.ender_dragon_boss_fight.hint: Complete a Mine with an End biome
+ world.effect.ender_dragon_boss_fight.name: Ender Dragon Boss
+ world.effect.endermen.description: Look at me when I'm talking to you! Actually, wait...
+ world.effect.endermen.hint: How many monster do you have to Slay!?
+ world.effect.endermen.name: Endermen
+ world.effect.endermites.description: Literally bugs in the game
+ world.effect.endermites.hint: Found in the end stone
+ world.effect.endermites.name: Endermites
+ world.effect.eternal_lightning.description: Very, very frightening!
+ world.effect.eternal_lightning.hint: Escape a Mine that will just not stop raining.
+ world.effect.eternal_lightning.name: Eternal Lightning
+ world.effect.eternal_night.description: It's dark in here isn't it?
+ world.effect.eternal_night.hint: Unlocked after a while, I guess?
+ world.effect.eternal_night.name: Eternal Night
+ world.effect.eternal_rain.description: Blimey rainy innit?!
+ world.effect.eternal_rain.hint: Win an eternally dark Mine
+ world.effect.eternal_rain.name: Eternal Rain
+ world.effect.event_exit.description: Complete the event to spawn the exit
+ world.effect.event_exit.name: Event Mine
+ world.effect.evokers.description: Wololo
+ world.effect.evokers.hint: Buy it from a villager. The Lodestone will guide your way!
+ world.effect.evokers.name: Evokers
+ world.effect.experience_modifier: %s (x%s XP)
+ world.effect.explosive_traps.description: Watch your step
+ world.effect.explosive_traps.hint: Play a while..
+ world.effect.explosive_traps.name: Explosive Traps
+ world.effect.fish_out_of_water.description: Just keep swimming
+ world.effect.fish_out_of_water.hint: Fish!
+ world.effect.fish_out_of_water.name: Fish Out of Water
+ world.effect.floating_islands_world.description: How can it be a Mine if it's not even solid?
+ world.effect.floating_islands_world.hint: Win a Mine
+ world.effect.floating_islands_world.name: Floating Islands
+ world.effect.forests.description: Now with raised trees
+ world.effect.forests.hint: Search among the Leaves
+ world.effect.forests.name: Forest Biomes
+ world.effect.foxes.description: What does the fox say?
+ world.effect.foxes.hint: Berries
+ world.effect.foxes.name: Foxes
+ world.effect.frogs.description: Heralds of change
+ world.effect.frogs.name: Frogs
+ world.effect.ghasts.description: No, they're not happy
+ world.effect.ghasts.hint: Probably dried out among fossils
+ world.effect.ghasts.name: Ghasts
+ world.effect.goats.description: Mischevious horned menace of the mountain
+ world.effect.goats.hint: Go mining in the mountains
+ world.effect.goats.name: Goats
+ world.effect.grid_world.description: Linear. Orderly.
+ world.effect.grid_world.hint: Win a Special Encounter Mine
+ world.effect.grid_world.name: Grid World
+ world.effect.guardians.description: Protectors of the deep
+ world.effect.guardians.hint: Slaying creatures of the water will anger the Guardians
+ world.effect.guardians.name: Guardians
+ world.effect.hoglins.description: The whole hog
+ world.effect.hoglins.hint: Through the death of many Pigs
+ world.effect.hoglins.name: Hoglins
+ world.effect.ice_spikes.description: Cool
+ world.effect.ice_spikes.hint: Win a snowy Mine
+ world.effect.ice_spikes.name: Ice Spikes Biome
+ world.effect.icy.description: Might be a little slippery...
+ world.effect.icy.hint: Take a boat ride
+ world.effect.icy.name: Icy Surfaces
+ world.effect.illusioners.description: It's not even in the game
+ world.effect.illusioners.hint: Buy it from a villager. The Lodestone will guide your way!
+ world.effect.illusioners.name: Illusioners
+ world.effect.insomniacs.description: No rest, no respite
+ world.effect.insomniacs.hint: Win a Mine that never sees the light of day
+ world.effect.insomniacs.name: Insomniacs
+ world.effect.jungles.description: In the Jungle, the Miney Jungle
+ world.effect.jungles.hint: Do not leave the leaves alone!
+ world.effect.jungles.name: Jungle Biomes
+ world.effect.kuiper_world.description: Igloo in spaaaaace!
+ world.effect.kuiper_world.name: Kuiper World
+ world.effect.magma_cubes.description: Squishy and stompy and hot at the same time
+ world.effect.magma_cubes.hint: Get some Magma
+ world.effect.magma_cubes.name: Magma Cubes
+ world.effect.mooshrooms.description: These mushrooms moo
+ world.effect.mooshrooms.hint: Go pick mushrooms
+ world.effect.mooshrooms.name: Mooshrooms
+ world.effect.mushroom_fields.description: Mushroom islands, except not only islands
+ world.effect.mushroom_fields.hint: Collect Mushrooms and you might get lucky
+ world.effect.mushroom_fields.name: Mushroom Fields Biome
+ world.effect.nether_barrens.description: Things are heating up!
+ world.effect.nether_barrens.hint: The Ice Bucket Challenge
+ world.effect.nether_barrens.name: Barren Nether Biomes
+ world.effect.nether_forests.description: Can't see the forest for the... fungi?
+ world.effect.nether_forests.hint: Found while slaying Endermen
+ world.effect.nether_forests.name: Nether Forest Biomes
+ world.effect.no_drops.description: Who needs it?
+ world.effect.no_drops.hint: Found by chance
+ world.effect.no_drops.name: No drops?
+ world.effect.ocelots.description: Kitty!
+ world.effect.ocelots.hint: Whiskers!
+ world.effect.ocelots.name: Ocelots
+ world.effect.one_hp.description: There is only one heart.
+ world.effect.one_hp.hint: Kill something while having only one heart
+ world.effect.one_hp.name: One HP
+ world.effect.pandas.description: Cute and clumsy
+ world.effect.pandas.hint: Eat some bamboo
+ world.effect.pandas.name: Pandas
+ world.effect.parrots.description: Tssssss sharp
+ world.effect.parrots.hint: Eat a cookie, the Parrot doesn't want it anyway
+ world.effect.parrots.name: Parrots
+ world.effect.piglins.description: Pigs that love gold... and violence
+ world.effect.piglins.hint: Feed some gold to a pig
+ world.effect.piglins.name: Piglins
+ world.effect.pigs.description: Pork-u-pines, except without the pines?
+ world.effect.pigs.name: Pigs
+ world.effect.pillagers.description: Villager, Illager, Pillager - what's the difference?
+ world.effect.pillagers.hint: Buy it from a villager. The Lodestone will guide your way!
+ world.effect.pillagers.name: Pillagers
+ world.effect.plains.description: Quite plain
+ world.effect.plains.name: Plains Biomes
+ world.effect.rabbits.description: Jumpy meals
+ world.effect.rabbits.hint: Jump... from really high up
+ world.effect.rabbits.name: Rabbits
+ world.effect.raid.description: They're coming for your loot
+ world.effect.raid.hint: Slay a Pillager
+ world.effect.raid.name: Raid!
+ world.effect.rare_surface_exits.description: Mine Exits are found on the surface, but it might be a trek to get to one
+ world.effect.rare_surface_exits.hint: Craft an item that helps you locate Mine Exits
+ world.effect.rare_surface_exits.name: Rare Surface Exits
+ world.effect.ravagers.description: Rawr
+ world.effect.ravagers.hint: Buy it from a villager. The Lodestone will guide your way!
+ world.effect.ravagers.name: Ravagers
+ world.effect.savannas.description: On the great wide savanna steppes...
+ world.effect.savannas.name: Savanna Biomes
+ world.effect.shattered_blocks_world.description: Shattered world made of big blocks with large gaps
+ world.effect.shattered_blocks_world.hint: Win a Special Encounter Mine
+ world.effect.shattered_blocks_world.name: Shattered Blocks World
+ world.effect.sheep.description: Fluffy mine
+ world.effect.sheep.name: Sheep
+ world.effect.shulkers.description: Box material
+ world.effect.shulkers.hint: Stomp out bugs from their natural environment
+ world.effect.shulkers.name: Shulkers
+ world.effect.skeletons.description: Feel it in my bones
+ world.effect.skeletons.hint: A chance while slaying monsters
+ world.effect.skeletons.name: Skeletons
+ world.effect.slimes.description: Get slimed!
+ world.effect.slimes.hint: You guessed it - Slay monsters!
+ world.effect.slimes.name: Slimes
+ world.effect.small_but_deadly_boss_fight.description: Tiny (not so) friendly critters
+ world.effect.small_but_deadly_boss_fight.hint: Just play the game!
+ world.effect.small_but_deadly_boss_fight.name: Small But Deadly Boss Fight
+ world.effect.sniffers.description: Let the gentle giants roam the Mines once more
+ world.effect.sniffers.hint: They like flowers
+ world.effect.sniffers.name: Sniffers
+ world.effect.snowy.description: Let it snow, let it snow, let it snow
+ world.effect.snowy.hint: Search cold Blocks
+ world.effect.snowy.name: Snowy Biomes
+ world.effect.soul_link.description: Every player takes damage if one player is hurt
+ world.effect.soul_link.hint: Win a mine with the "One HP" ingredient
+ world.effect.soul_link.name: Soul Link
+ world.effect.spiders.description: So many years of bad luck from this one
+ world.effect.spiders.hint: Slay Slay, slay...
+ world.effect.spiders.name: Spiders
+ world.effect.striders.description: You better make the mine have some warm cozy lava
+ world.effect.striders.hint: Prepare to go riding
+ world.effect.striders.name: Striders
+ world.effect.surface_exits.description: Mine Exits are found on the surface
+ world.effect.surface_exits.name: Surface Exits
+ world.effect.surface_world.description: World above the Mines. Like... an aboveworld
+ world.effect.surface_world.name: Surface World
+ world.effect.swamps.description: Get ready to get your boots wet
+ world.effect.swamps.hint: Find the source of the smallest creature
+ world.effect.swamps.name: Swamp Biomes
+ world.effect.taigas.description: Don't step on the pine cones
+ world.effect.taigas.hint: Found somewhere in the trees
+ world.effect.taigas.name: Taiga Biomes
+ world.effect.the_enderman_boss_fight.description: THIS Enderman
+ world.effect.the_enderman_boss_fight.hint: Just play the game!
+ world.effect.the_enderman_boss_fight.name: The Enderman Boss Fight
+ world.effect.ultrawarm.description: It's getting hot in here
+ world.effect.ultrawarm.hint: Stand in lava... if you dare
+ world.effect.ultrawarm.name: Ultrawarm
+ world.effect.universal_anger.description: Every neutral mob is hostile
+ world.effect.universal_anger.hint: Win a mine with the "Bees" ingredient
+ world.effect.universal_anger.name: (Near) Universal Anger
+ world.effect.unlock: Bring this item to the Mine exit to unlock as a Mine ingredient
+ world.effect.unlocked: Unlocked new Mine Ingredient: %s
+ world.effect.vindicators.description: Here's Johnny!
+ world.effect.vindicators.hint: Buy it from a villager. The Lodestone will guide your way!
+ world.effect.vindicators.name: Vindicators
+ world.effect.void_world.description: It stares also into you
+ world.effect.void_world.name: Void World
+ world.effect.warden_boss_fight.description: Warden wards off the competition
+ world.effect.warden_boss_fight.hint: Walk on this block and give of a chime, it's a nice crystal but not even worth a dime
+ world.effect.warden_boss_fight.name: Warden Boss Fight
+ world.effect.water_world.description: Like the hit film from Cavin' Costner
+ world.effect.water_world.hint: Win a dry Mine
+ world.effect.water_world.name: Water World
+ world.effect.wednesday_frogs.description: Heralds of doom
+ world.effect.wednesday_frogs.hint: Might be trickier to find than you might think
+ world.effect.wednesday_frogs.name: Wednesday Frogs
+ world.effect.witches.description: Double, double toil and trouble
+ world.effect.witches.hint: You would have never guessed it! Slay monsters to find this one! :D
+ world.effect.witches.name: Witches
+ world.effect.wither_boss_fight.description: They say this one's harder when it's standing on Bedrock
+ world.effect.wither_boss_fight.hint: Obtain a Wither Skull
+ world.effect.wither_boss_fight.name: Wither Boss Fight
+ world.effect.wither_skeletons.description: Wither, Blister, Burn & Peel
+ world.effect.wither_skeletons.hint: Hidden among the regular Skeletons
+ world.effect.wither_skeletons.name: Wither Skeletons
+ world.effect.zoglins.description: So angry
+ world.effect.zoglins.hint: Kill a zombie on the turf of the Piglins
+ world.effect.zoglins.name: Zoglins
+ world.effect.zombies.description: Braaaaaiiiinsss
+ world.effect.zombies.hint: Go on a monster hunt!
+ world.effect.zombies.name: Zombies
+ world.effect.zombified_piglins.description: These pigs seem quite easily angered
+ world.effect.zombified_piglins.hint: Somehow related to pigs in the fires of the nether
+ world.effect.zombified_piglins.name: Zombified Piglins
+ world.event.angry_ghast: Angry Ghast Spawns
+ world.event.ender_dragon: Ender Dragon Spawns
+ world.event.enderman: The Enderman Spawns
+ world.event.next_wave: Next Wave
+ world.event.remaining: Mobs Remaining
+ world.event.warden: Warden Spawns
+ world.event.wither: Wither Spawns
+ world.mine: Mine %s
+ world.mine.base: Mine %s Base
+ world.mine.next: Next Mine
+ world.mine.revisit.lost: Revisiting old Mine that sadly was lost
+ world.mine.revisit.won: Revisiting old Mine that was won
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.21.5</th><th>25w14craftmine</th></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.return_to_sender.description</div></th><td>Destroy a Ghast with a fireball</td><td>Destroy a Ghast with a fireball to unlock the Angry Ghast special event</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.set_spawn</div></th><td>Respawn point set</td><td>You didn't think this would work, did you?</td></tr>
<tr><th align="left"><div style="width:290px">entity.minecraft.eye_of_ender</div></th><td>Eye of Ender</td><td>Eye of Exit</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.gameMode.survival.info</div></th><td>Explore a mysterious world where you build, collect, craft, and fight monsters.</td><td>Craft and explore mines, unlock more ingredients, craft some more - and watch out for the special encounters!</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.end_portal_frame.fill</div></th><td>Eye of Ender attaches</td><td>Eye of Exit attaches</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.end_portal.spawn</div></th><td>End Portal opens</td><td>Portal sounds</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ender_eye.death</div></th><td>Eye of Ender falls</td><td>Eye of Exit falls</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ender_eye.launch</div></th><td>Eye of Ender shoots</td><td>Eye of Exit shoots</td></tr>
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
+ minecraft:change_dimension_type
+ minecraft:open_door_packet
- minecraft:open_screen
+ minecraft:open_window
+ minecraft:player_unlocks
+ minecraft:update_screen
+ minecraft:update_unlocked_effects
```

</details>
<details>
<summary>
[server] play
</summary>

```diff
+ minecraft:player_buy_unlock
+ minecraft:player_donate_experience
+ minecraft:player_reactivate_unlock
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
+ reports/biome_parameters/minecraft/endish.json
```

</details>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancement/adventure/adventuring_time.json
- minecraft/advancement/adventure/arbalistic.json
- minecraft/advancement/adventure/avoid_vibration.json
- minecraft/advancement/adventure/blowback.json
- minecraft/advancement/adventure/brush_armadillo.json
- minecraft/advancement/adventure/bullseye.json
- minecraft/advancement/adventure/craft_decorated_pot_using_only_sherds.json
- minecraft/advancement/adventure/crafters_crafting_crafters.json
- minecraft/advancement/adventure/fall_from_world_height.json
- minecraft/advancement/adventure/hero_of_the_village.json
- minecraft/advancement/adventure/honey_block_slide.json
- minecraft/advancement/adventure/kill_a_mob.json
- minecraft/advancement/adventure/kill_all_mobs.json
- minecraft/advancement/adventure/kill_mob_near_sculk_catalyst.json
- minecraft/advancement/adventure/lighten_up.json
- minecraft/advancement/adventure/lightning_rod_with_villager_no_fire.json
- minecraft/advancement/adventure/minecraft_trials_edition.json
- minecraft/advancement/adventure/ol_betsy.json
- minecraft/advancement/adventure/overoverkill.json
- minecraft/advancement/adventure/play_jukebox_in_meadows.json
- minecraft/advancement/adventure/read_power_of_chiseled_bookshelf.json
- minecraft/advancement/adventure/revaulting.json
- minecraft/advancement/adventure/root.json
- minecraft/advancement/adventure/salvage_sherd.json
- minecraft/advancement/adventure/shoot_arrow.json
- minecraft/advancement/adventure/sleep_in_bed.json
- minecraft/advancement/adventure/sniper_duel.json
- minecraft/advancement/adventure/spyglass_at_dragon.json
- minecraft/advancement/adventure/spyglass_at_ghast.json
- minecraft/advancement/adventure/spyglass_at_parrot.json
- minecraft/advancement/adventure/summon_iron_golem.json
- minecraft/advancement/adventure/throw_trident.json
- minecraft/advancement/adventure/totem_of_undying.json
- minecraft/advancement/adventure/trade_at_world_height.json
- minecraft/advancement/adventure/trade.json
- minecraft/advancement/adventure/trim_with_all_exclusive_armor_patterns.json
- minecraft/advancement/adventure/trim_with_any_armor_pattern.json
- minecraft/advancement/adventure/two_birds_one_arrow.json
- minecraft/advancement/adventure/under_lock_and_key.json
- minecraft/advancement/adventure/use_lodestone.json
- minecraft/advancement/adventure/very_very_frightening.json
- minecraft/advancement/adventure/voluntary_exile.json
- minecraft/advancement/adventure/walk_on_powder_snow_with_leather_boots.json
- minecraft/advancement/adventure/who_needs_rockets.json
- minecraft/advancement/adventure/whos_the_pillager_now.json
- minecraft/advancement/end/dragon_breath.json
- minecraft/advancement/end/dragon_egg.json
- minecraft/advancement/end/elytra.json
- minecraft/advancement/end/enter_end_gateway.json
- minecraft/advancement/end/find_end_city.json
- minecraft/advancement/end/kill_dragon.json
- minecraft/advancement/end/levitate.json
- minecraft/advancement/end/respawn_dragon.json
- minecraft/advancement/end/root.json
+ minecraft/advancement/feats/angry_ghast.json
+ minecraft/advancement/feats/crystal.json
+ minecraft/advancement/feats/dragon_breath.json
+ minecraft/advancement/feats/end_world.json
+ minecraft/advancement/feats/ender_dragon.json
+ minecraft/advancement/feats/enderman.json
+ minecraft/advancement/feats/kill_pillager.json
+ minecraft/advancement/feats/kill_skeleton.json
+ minecraft/advancement/feats/kuiper_world.json
+ minecraft/advancement/feats/raid.json
+ minecraft/advancement/feats/return_to_sender.json
+ minecraft/advancement/feats/root.json
+ minecraft/advancement/feats/small_but_deadly.json
+ minecraft/advancement/feats/spooky_scary_skeletons.json
+ minecraft/advancement/feats/warden.json
+ minecraft/advancement/feats/wither_skeleton_skull.json
+ minecraft/advancement/feats/wither.json
- minecraft/advancement/husbandry/allay_deliver_cake_to_note_block.json
- minecraft/advancement/husbandry/allay_deliver_item_to_player.json
- minecraft/advancement/husbandry/axolotl_in_a_bucket.json
- minecraft/advancement/husbandry/balanced_diet.json
- minecraft/advancement/husbandry/bred_all_animals.json
- minecraft/advancement/husbandry/breed_an_animal.json
- minecraft/advancement/husbandry/complete_catalogue.json
- minecraft/advancement/husbandry/feed_snifflet.json
- minecraft/advancement/husbandry/fishy_business.json
- minecraft/advancement/husbandry/froglights.json
- minecraft/advancement/husbandry/kill_axolotl_target.json
- minecraft/advancement/husbandry/leash_all_frog_variants.json
- minecraft/advancement/husbandry/make_a_sign_glow.json
- minecraft/advancement/husbandry/obtain_netherite_hoe.json
- minecraft/advancement/husbandry/obtain_sniffer_egg.json
- minecraft/advancement/husbandry/plant_any_sniffer_seed.json
- minecraft/advancement/husbandry/plant_seed.json
- minecraft/advancement/husbandry/remove_wolf_armor.json
- minecraft/advancement/husbandry/repair_wolf_armor.json
- minecraft/advancement/husbandry/ride_a_boat_with_a_goat.json
- minecraft/advancement/husbandry/root.json
- minecraft/advancement/husbandry/safely_harvest_honey.json
- minecraft/advancement/husbandry/silk_touch_nest.json
- minecraft/advancement/husbandry/tactical_fishing.json
- minecraft/advancement/husbandry/tadpole_in_a_bucket.json
- minecraft/advancement/husbandry/tame_an_animal.json
- minecraft/advancement/husbandry/wax_off.json
- minecraft/advancement/husbandry/wax_on.json
- minecraft/advancement/husbandry/whole_pack.json
+ minecraft/advancement/mines/all_mine_ingredients.json
+ minecraft/advancement/mines/all_special_mines_completed.json
+ minecraft/advancement/mines/cash_in_mine_ingredient.json
+ minecraft/advancement/mines/complete_deluge_level.json
+ minecraft/advancement/mines/complete_water_cave_level.json
+ minecraft/advancement/mines/complete_water_world_level.json
+ minecraft/advancement/mines/eat_your_veggies.json
+ minecraft/advancement/mines/enter_a_mine.json
+ minecraft/advancement/mines/get_mine_ingredient.json
+ minecraft/advancement/mines/level_completed.json
+ minecraft/advancement/mines/mine_crafter_upgraded.json
+ minecraft/advancement/mines/mine_revisitor_activated.json
+ minecraft/advancement/mines/player_failed_level.json
+ minecraft/advancement/mines/shimmering_key.json
+ minecraft/advancement/mines/special_mine_completed.json
- minecraft/advancement/nether/all_effects.json
- minecraft/advancement/nether/all_potions.json
- minecraft/advancement/nether/brew_potion.json
- minecraft/advancement/nether/charge_respawn_anchor.json
- minecraft/advancement/nether/create_beacon.json
- minecraft/advancement/nether/create_full_beacon.json
- minecraft/advancement/nether/distract_piglin.json
- minecraft/advancement/nether/explore_nether.json
- minecraft/advancement/nether/fast_travel.json
- minecraft/advancement/nether/find_bastion.json
- minecraft/advancement/nether/find_fortress.json
- minecraft/advancement/nether/get_wither_skull.json
- minecraft/advancement/nether/loot_bastion.json
- minecraft/advancement/nether/netherite_armor.json
- minecraft/advancement/nether/obtain_ancient_debris.json
- minecraft/advancement/nether/obtain_blaze_rod.json
- minecraft/advancement/nether/obtain_crying_obsidian.json
- minecraft/advancement/nether/return_to_sender.json
- minecraft/advancement/nether/ride_strider_in_overworld_lava.json
- minecraft/advancement/nether/ride_strider.json
- minecraft/advancement/nether/root.json
- minecraft/advancement/nether/summon_wither.json
- minecraft/advancement/nether/uneasy_alliance.json
- minecraft/advancement/recipes/misc/ender_eye.json
+ minecraft/advancement/recipes/misc/exit_eye.json
- minecraft/advancement/story/cure_zombie_villager.json
- minecraft/advancement/story/enchant_item.json
- minecraft/advancement/story/enter_the_end.json
- minecraft/advancement/story/enter_the_nether.json
- minecraft/advancement/story/follow_ender_eye.json
+ minecraft/advancement/story/follow_exit_eye.json
- minecraft/advancement/story/form_obsidian.json
- minecraft/advancement/story/lava_bucket.json
+ minecraft/advancement/unlocks/all_combatant.json
+ minecraft/advancement/unlocks/all_crafting.json
+ minecraft/advancement/unlocks/all_exploration.json
+ minecraft/advancement/unlocks/all_gatherer.json
+ minecraft/advancement/unlocks/all_school_of_hard_knocks.json
+ minecraft/advancement/unlocks/free_sticks.json
+ minecraft/advancement/unlocks/how_do_i_unlock_that.json
+ minecraft/advancement/unlocks/in_it_together.json
+ minecraft/advancement/unlocks/jump_king.json
+ minecraft/advancement/unlocks/kaizen.json
+ minecraft/advancement/unlocks/root.json
+ minecraft/advancement/unlocks/sigma_grindset.json
+ minecraft/damage_type/devour.json
+ minecraft/dimension_type/generated.json
+ minecraft/jukebox_song/and_action.json
+ minecraft/loot_table/blocks/dimension_control.json
+ minecraft/loot_table/blocks/mine_crafter.json
+ minecraft/loot_table/blocks/mine_revisitor.json
+ minecraft/loot_table/blocks/mob_trophy.json
+ minecraft/loot_table/blocks/trophy.json
+ minecraft/loot_table/entities/angry_ghast.json
+ minecraft/loot_table/entities/pet_armadillo.json
+ minecraft/loot_table/entities/pet_axolotl.json
+ minecraft/loot_table/entities/pet_bee.json
+ minecraft/loot_table/entities/pet_cat.json
+ minecraft/loot_table/entities/pet_chicken.json
+ minecraft/loot_table/entities/pet_cow.json
+ minecraft/loot_table/entities/pet_creeper.json
+ minecraft/loot_table/entities/pet_fox.json
+ minecraft/loot_table/entities/pet_frog.json
+ minecraft/loot_table/entities/pet_mooshroom.json
+ minecraft/loot_table/entities/pet_polar_bear.json
+ minecraft/loot_table/entities/pet_slime.json
+ minecraft/loot_table/entities/pet_turtle.json
+ minecraft/loot_table/entities/pet_wolf.json
+ minecraft/loot_table/gameplay/room_rewards.json
+ minecraft/loot_table/mines/eat_your_veggies.json
- minecraft/recipe/ender_eye.json
+ minecraft/recipe/exit_eye.json
+ minecraft/structure/hub/center_base.nbt
+ minecraft/structure/hub/center_hat.nbt
+ minecraft/structure/hub/corridor_base.nbt
+ minecraft/structure/hub/corridor_hat.nbt
+ minecraft/structure/hub/room/barrels.nbt
+ minecraft/structure/hub/room/boiler.nbt
+ minecraft/structure/hub/room/carpet.nbt
+ minecraft/structure/hub/room/corridor_simple.nbt
+ minecraft/structure/hub/room/fountain.nbt
+ minecraft/structure/hub/room/grassy_h.nbt
+ minecraft/structure/hub/room/hanging.nbt
+ minecraft/structure/hub/room/house.nbt
+ minecraft/structure/hub/room/labyrinth.nbt
+ minecraft/structure/hub/room/pool.nbt
+ minecraft/structure/hub/room/ship.nbt
+ minecraft/structure/hub/room/simple.nbt
+ minecraft/structure/hub/room/stairs.nbt
+ minecraft/structure/hub/room/storage1.nbt
+ minecraft/structure/hub/room/storage2.nbt
+ minecraft/structure/hub/room/sugar_h.nbt
+ minecraft/structure/hub/room/test.nbt
+ minecraft/structure/hub/room/tree.nbt
+ minecraft/structure/hub/room/trophy.nbt
+ minecraft/structure/hub/room/tunnel.nbt
+ minecraft/structure/hub/room/useless.nbt
+ minecraft/structure/hub/room/wheat_h.nbt
+ minecraft/structure/hub/room/workshop.nbt
+ minecraft/structure/mine_exits/exit_01.nbt
+ minecraft/structure/mine_exits/root.nbt
+ minecraft/structure/mines/dirty_ice_ball_fox.nbt
+ minecraft/structure/mines/dirty_ice_ball_golems.nbt
+ minecraft/structure/mines/dirty_ice_ball.nbt
+ minecraft/structure/mines/space_igloo.nbt
+ minecraft/structure/mines/start_platform.nbt
+ minecraft/structure/mines/warden_arena.nbt
+ minecraft/tags/item/amethyst_crystals.json
+ minecraft/tags/item/carry_over.json
+ minecraft/tags/item/ingot.json
+ minecraft/tags/item/ore.json
+ minecraft/tags/worldgen/structure/mine_exit.json
+ minecraft/worldgen/biome/hub.json
+ minecraft/worldgen/configured_feature/dirty_ice_ball_fox.json
+ minecraft/worldgen/configured_feature/dirty_ice_ball_golems.json
+ minecraft/worldgen/configured_feature/dirty_ice_ball.json
+ minecraft/worldgen/configured_feature/mine_start.json
+ minecraft/worldgen/configured_feature/ore_stone.json
+ minecraft/worldgen/configured_feature/space_igloo.json
+ minecraft/worldgen/configured_feature/warden_arena.json
- minecraft/worldgen/density_function/overworld_large_biomes/continents.json
- minecraft/worldgen/density_function/overworld_large_biomes/depth.json
- minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
- minecraft/worldgen/density_function/overworld_large_biomes/factor.json
- minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
- minecraft/worldgen/density_function/overworld_large_biomes/offset.json
- minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
+ minecraft/worldgen/multi_noise_biome_source_parameter_list/endish.json
- minecraft/worldgen/noise_settings/large_biomes.json
- minecraft/worldgen/noise/continentalness_large.json
- minecraft/worldgen/noise/erosion_large.json
- minecraft/worldgen/noise/temperature_large.json
- minecraft/worldgen/noise/vegetation_large.json
+ minecraft/worldgen/placed_feature/ore_stone_lower.json
+ minecraft/worldgen/placed_feature/ore_stone_upper.json
+ minecraft/worldgen/structure_set/cave_mine_exits.json
+ minecraft/worldgen/structure_set/rare_surface_mine_exits.json
+ minecraft/worldgen/structure_set/surface_mine_exits.json
+ minecraft/worldgen/structure/cave_mine_exit.json
+ minecraft/worldgen/structure/rare_surface_mine_exit.json
+ minecraft/worldgen/structure/surface_mine_exit.json
+ minecraft/worldgen/template_pool/mine_exits/root.json
+ minecraft/worldgen/template_pool/mine_exits/starts.json
- minecraft/worldgen/world_preset/debug_all_block_states.json
- minecraft/worldgen/world_preset/large_biomes.json
- minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/dimension_control.json
- minecraft/blockstates/end_portal_frame.json
- minecraft/blockstates/end_portal.json
+ minecraft/blockstates/mine_crafter.json
+ minecraft/blockstates/mine_revisitor.json
+ minecraft/blockstates/mine_travelling_block.json
+ minecraft/blockstates/mob_trophy.json
+ minecraft/blockstates/shimmering_door.json
+ minecraft/blockstates/sky.json
+ minecraft/blockstates/trophy.json
+ minecraft/items/amplified.json
+ minecraft/items/cave_exits.json
+ minecraft/items/cave_world.json
+ minecraft/items/dark_cave_world.json
+ minecraft/items/dimension_control.json
- minecraft/items/end_portal_frame.json
- minecraft/items/ender_eye.json
+ minecraft/items/exit_eye.json
+ minecraft/items/fire_wand.json
+ minecraft/items/floating_islands_world.json
+ minecraft/items/grave_advancement.json
+ minecraft/items/grid_world.json
+ minecraft/items/illusioners.json
+ minecraft/items/kuiper_world.json
+ minecraft/items/mine_crafter.json
+ minecraft/items/mine_ingredient.json
+ minecraft/items/mine_revisitor.json
+ minecraft/items/mine.json
+ minecraft/items/mob_trophy.json
+ minecraft/items/music_disc_and_action.json
+ minecraft/items/pets_icon.json
+ minecraft/items/rare_surface_exits.json
+ minecraft/items/shattered_blocks.json
+ minecraft/items/shazboots.json
+ minecraft/items/shimmering_door.json
+ minecraft/items/shimmering_key.json
+ minecraft/items/sky_box.json
+ minecraft/items/sky.json
+ minecraft/items/surface_exits.json
+ minecraft/items/surface_world.json
+ minecraft/items/teleportation_wand.json
+ minecraft/items/trophy.json
+ minecraft/items/water_mining.json
+ minecraft/items/wind_wand.json
+ minecraft/models/block/block_generated.json
+ minecraft/models/block/dimension_control.json
- minecraft/models/block/end_portal.json
+ minecraft/models/block/mine_crafter.json
+ minecraft/models/block/mine_revisitor.json
+ minecraft/models/block/mine_travelling_block.json
+ minecraft/models/block/mob_trophy.json
+ minecraft/models/block/shimmering_door_bottom_left_open.json
+ minecraft/models/block/shimmering_door_bottom_left.json
+ minecraft/models/block/shimmering_door_bottom_right_open.json
+ minecraft/models/block/shimmering_door_bottom_right.json
+ minecraft/models/block/shimmering_door_top_left_open.json
+ minecraft/models/block/shimmering_door_top_left.json
+ minecraft/models/block/shimmering_door_top_right_open.json
+ minecraft/models/block/shimmering_door_top_right.json
+ minecraft/models/block/sky.json
+ minecraft/models/block/template_mine_crafter.json
+ minecraft/models/block/template_mine_revisitor.json
+ minecraft/models/block/trophy_gold.json
+ minecraft/models/block/trophy_mega_spud.json
+ minecraft/models/block/trophy_no_medal.json
+ minecraft/models/item/amplified.json
+ minecraft/models/item/cave_exits.json
+ minecraft/models/item/cave_world.json
+ minecraft/models/item/dark_cave_world.json
- minecraft/models/item/ender_eye.json
+ minecraft/models/item/exit_eye.json
+ minecraft/models/item/fire_wand.json
+ minecraft/models/item/floating_islands_world.json
+ minecraft/models/item/grave_advancement.json
+ minecraft/models/item/grid_world.json
+ minecraft/models/item/illusioners.json
+ minecraft/models/item/kuiper_world.json
+ minecraft/models/item/mine_ingredient.json
+ minecraft/models/item/mine.json
+ minecraft/models/item/music_disc_and_action.json
+ minecraft/models/item/pets_icon.json
+ minecraft/models/item/rare_surface_exits.json
+ minecraft/models/item/shattered_blocks.json
+ minecraft/models/item/shazboots.json
+ minecraft/models/item/shimmering_door.json
+ minecraft/models/item/shimmering_key.json
+ minecraft/models/item/sky_box.json
+ minecraft/models/item/surface_exits.json
+ minecraft/models/item/surface_world.json
+ minecraft/models/item/teleportation_wand.json
+ minecraft/models/item/water_mining.json
+ minecraft/models/item/wind_wand.json
+ minecraft/particles/mine_travel.json
+ minecraft/shaders/core/rain.fsh
+ minecraft/shaders/core/sky_block.fsh
+ minecraft/shaders/core/sky_block.vsh
+ minecraft/shaders/core/title_rain.fsh
+ minecraft/textures/block/box_back_0.png
+ minecraft/textures/block/box_base.png
+ minecraft/textures/block/box_bottom.png
+ minecraft/textures/block/box_front_0.png
+ minecraft/textures/block/box_side_0.png
+ minecraft/textures/block/cube_side_1.png
+ minecraft/textures/block/mine_crafter_active_inner_top.png
+ minecraft/textures/block/mine_crafter_active_inner_top.png.mcmeta
+ minecraft/textures/block/mine_crafter_bottom.png
+ minecraft/textures/block/mine_crafter_inner_top.png
+ minecraft/textures/block/mine_crafter_inner_top.png.mcmeta
+ minecraft/textures/block/mine_crafter_side.png
+ minecraft/textures/block/mine_crafter_top.png
+ minecraft/textures/block/mine_revisitor_active_inner_top.png
+ minecraft/textures/block/mine_revisitor_active_inner_top.png.mcmeta
+ minecraft/textures/block/mine_revisitor_bottom.png
+ minecraft/textures/block/mine_revisitor_inner_top.png
+ minecraft/textures/block/mine_revisitor_inner_top.png.mcmeta
+ minecraft/textures/block/mine_revisitor_side.png
+ minecraft/textures/block/mine_revisitor_top.png
+ minecraft/textures/block/mine_travelling_block.png
+ minecraft/textures/block/shimmering_door_bottom.png
+ minecraft/textures/block/shimmering_door_top.png
+ minecraft/textures/block/sky.png
+ minecraft/textures/block/trophy_gold.png
+ minecraft/textures/block/trophy_mega_spud.png
+ minecraft/textures/block/trophy_no_medal.png
+ minecraft/textures/entity/angry_ghast/ghast_shooting.png
+ minecraft/textures/entity/angry_ghast/ghast.png
+ minecraft/textures/entity/villager/profession/traitor.png
+ minecraft/textures/entity/zombie_villager/profession/traitor.png
+ minecraft/textures/environment/skynorama/panorama_0.png
+ minecraft/textures/environment/skynorama/panorama_1.png
+ minecraft/textures/environment/skynorama/panorama_2.png
+ minecraft/textures/environment/skynorama/panorama_3.png
+ minecraft/textures/environment/skynorama/panorama_4.png
+ minecraft/textures/environment/skynorama/panorama_5.png
+ minecraft/textures/font/code.png
- minecraft/textures/gui/advancements/backgrounds/end.png
+ minecraft/textures/gui/advancements/backgrounds/feats.png
- minecraft/textures/gui/advancements/backgrounds/husbandry.png
+ minecraft/textures/gui/advancements/backgrounds/mines.png
- minecraft/textures/gui/advancements/backgrounds/nether.png
+ minecraft/textures/gui/advancements/backgrounds/unlocks.png
+ minecraft/textures/gui/container/dimension_control.png
+ minecraft/textures/gui/container/inventory_3x3.png
+ minecraft/textures/gui/container/inventory_no_crafting.png
+ minecraft/textures/gui/container/mine_crafter_active.png
+ minecraft/textures/gui/container/mine_crafter_boss_active.png
+ minecraft/textures/gui/container/mine_crafter_boss.png
+ minecraft/textures/gui/container/mine_crafter_donate.png
+ minecraft/textures/gui/container/mine_crafter_fail.png
+ minecraft/textures/gui/container/mine_crafter_hints.png
+ minecraft/textures/gui/container/mine_crafter_won.png
+ minecraft/textures/gui/container/mine_crafter.png
+ minecraft/textures/gui/door.png
+ minecraft/textures/gui/sprites/advancements/box_obtained_active.png
+ minecraft/textures/gui/sprites/advancements/box_obtained_active.png.mcmeta
+ minecraft/textures/gui/sprites/advancements/box_unobtained_locked.png
+ minecraft/textures/gui/sprites/advancements/box_unobtained_locked.png.mcmeta
+ minecraft/textures/gui/sprites/advancements/challenge_frame_unobtained_locked.png
+ minecraft/textures/gui/sprites/advancements/task_frame_obtained_active.png
+ minecraft/textures/gui/sprites/advancements/task_frame_unobtained_locked.png
+ minecraft/textures/gui/sprites/container/crafter/all_unlocked.png
+ minecraft/textures/gui/sprites/container/slot/level.png
+ minecraft/textures/gui/sprites/icon/donate_experience.png
+ minecraft/textures/gui/sprites/icon/player_unlocks.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/combatant.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/combatant.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/crafting.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/crafting.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/end.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/end.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/exploration.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/exploration.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/gatherer.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/gatherer.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/mining.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/mining.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/pets.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/pets.png.mcmeta
+ minecraft/textures/gui/sprites/unlock_backgrounds/school_of_hard_knocks.png
+ minecraft/textures/gui/sprites/unlock_backgrounds/school_of_hard_knocks.png.mcmeta
+ minecraft/textures/gui/sprites/widget/window.png
+ minecraft/textures/gui/sprites/widget/window.png.mcmeta
+ minecraft/textures/item/amplified.png
+ minecraft/textures/item/cave_exits.png
+ minecraft/textures/item/cave_world.png
+ minecraft/textures/item/dark_cave_world.png
- minecraft/textures/item/ender_eye.png
+ minecraft/textures/item/exit_eye.png
+ minecraft/textures/item/floating_islands_world.png
+ minecraft/textures/item/grave_advancement.png
+ minecraft/textures/item/grid_world.png
+ minecraft/textures/item/illusioners.png
+ minecraft/textures/item/kuiper_world.png
+ minecraft/textures/item/mine_ingredient.png
+ minecraft/textures/item/mine.png
+ minecraft/textures/item/music_disc_and_action.png
+ minecraft/textures/item/pets_icon.png
+ minecraft/textures/item/rare_surface_exits.png
+ minecraft/textures/item/shattered_blocks.png
+ minecraft/textures/item/shazboots.png
+ minecraft/textures/item/shimmering_door.png
+ minecraft/textures/item/shimmering_key.png
+ minecraft/textures/item/sky_box.png
+ minecraft/textures/item/surface_exits.png
+ minecraft/textures/item/surface_world.png
+ minecraft/textures/item/void_world.png
+ minecraft/textures/item/water_mining.png
+ minecraft/textures/misc/map_lost_glint.png
+ minecraft/textures/misc/map_lost_glint.png.mcmeta
+ minecraft/textures/misc/map_won_glint.png
+ minecraft/textures/misc/map_won_glint.png.mcmeta
+ minecraft/textures/mob_effect/shazboots.png
+ nothingtoseehere/sounds.json
+ nothingtoseehere/sounds/and_action/and_action.ogg
+ nothingtoseehere/sounds/villager_crowd/crowd_cheer.ogg
+ nothingtoseehere/sounds/villager_crowd/crowd_start.ogg
+ nothingtoseehere/sounds/villager_crowd/crowd_waiting.ogg
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
- ...!
- .party()!
- "Almost never" is an interesting concept!
- "Autological" is!
- [this splash text is now available]
- §1C§2o§3l§4o§5r§6m§7a§8t§9i§ac
- §kFUNKY LOL
- /give @a hugs 64
- #minecraftfarms
- <3 Max & 99 & Ducky!
+ <loud portal sounds>
- 1% sugar!
- 10 years of Mining and Crafting!
- 100% pure!
- 12 herbs and spices!
- 12345 is a bad password!
- 150 bpm for 400000 minutes!
- 150% hyperbole!
- 20 GOTO 10!
- 4815162342 lines of code!
- 90% bug free!
- 90210!
+ 99% less starch!
- A riddle, wrapped in a mystery!
- A skeleton popped out!
- Absolutely fixed relatively broken coordinates
- Absolutely no memes!
- Afraid of the big, black bat!
- Age of Wonders is better!
- Ahhhhhh!
- All inclusive!
- All is full of love!
- All rumors are true!
- Also try Braid!
- Also try Limbo!
- Also try Minecraft Dungeons!
- Also try Mount And Blade!
- Also try Pixeljunk Shooter!
- Also try Project Zomboid!
- Also try Super Meat Boy!
- Also try Terraria!
- Also try VVVVVV!
- Also try World of Goo!
- Amplify and listen to BIPOC voices!
- An illusion! What are you hiding?
- And my pickaxe!
+ And they call it a Mine? A MINE!
- Any computer is a laptop if you're brave enough!
+ As a large language model...
- As seen on TV!
- Ask your doctor!
- Autonomous!
- Awesome community!
- Awesome game design right there!
- Awesome!
- Aww man!
- Be anti-racist!
- Bees, bees, bees, bees!
- Bekarton guards the gate!
- Best in class!
- Big Pointy Teeth!
- Bigger than a bread box!
- Black lives matter!
- Blue warrior shot the food!
- Board game version also available!
- Boats FTW
- Boots with the fur!
- Bread is pain!
- Bring it on!
- Bring me Ray Cokes!
- Bringing home the bacon!
- BTAF used to be good!
- Buckets of lava!
- Bushy eyebrows!
- Buzzy Bees!
- Call your mother!
- Casual gaming!
- Ceci n'est pas une title screen!
- Check it out!
- Check out the far lands!
+ Check out this mine of mine!
- Child's play!
- Classy!
+ Clearly not made with AI!
- Closed source!
- Cloud computing!
- Cogito ergo sum!
- Collaborate and listen!
+ Comparable with leading brands!
- Complex cellular automata!
- Consummate V's!
+ Contains collectibles!
- Contains infinite genders!
- Contains simulated goats!
- Conventional!
+ Copyright Mojang AB. Do not distribute!
- Cough or sneeze into your elbow!
- Cow Tools!
+ Craft a Mine and then Mine and Craft!
+ Craft mines in Minecraft!
+ Craft the Earth! In Minecraft!
+ Craftable Mines!
- Create!
- Croak team!
- Cruising streets for gold!
- Cześć Polsko!
- Déjà vu!
- Déjà vu!
+ Deleting Overworld!
- Do it all, everything!
- Do not distribute!
+ Do you Mine?
- Do you want to join my server?
- Does barrel rolls!
- Doesn't avoid double negatives!
- Doesn't use the U-word!
- Don't bother with the clones!
- Don't feed avocados to parrots!
- Don't feed chocolate to parrots!
- Don't look directly at the bugs!
- Don’t touch your face!
- Don't worry, be happy!
- doot doot
- Double buffered!
+ Download more RAM!
- DRR! DRR! DRR!
- Dungeon!
- DungeonQuest is unfair!
- Edit is a name!
- Educate your friends on anti-racism!
- Engage!
- Enhanced!
+ Enter The Mine!
- Envision! Create! Share!
- Eple (original edit)!
- Euclidian!
- Everybody do the Leif!
- Excitement!
- Exclusive!
- Exploding creepers!
- Extra things!
- Fabulous graphics!
- Falling off cliffs!
- Falling with style!
+ Famously unfinished!
- Fan fiction!
- Fantasy!
- Fat free!
- Feature packed!
- Finally complete!
- Finally with ladders!
- Find your claw!
- Finger-licking!
- Flashing letters!
- Flavor with no seasoning!
- Flaxkikare!
- Flower forest TM perfume
- Fnord!
- Follow the train, CJ!
- Freaky!
- Free dental!
- From free range developers!
- From the streets of Södermalm!
- Full of stars!
- Funk soul brother!
- Gamers unite – separately in your own homes!
- Gargamel plays it!
- Gasp!
- Get to the coppah!
- Ghoughpteighbteau tchoghs!
- Give us Gordon!
- GNU Terry Pratchett
- Go to the dentist!
- Google anlyticsed!
- Got your nose!
- GOTY!
- Guaranteed!
- Haha, LOL!
- Haley loves Elan!
- Hampsterdance!
- Han shot first!
- Hang out with your friends online!
- Hard to label!
- Has an ending!
- Has working bookshelves!
+ Has working fletching tables!
- Hat Fridays!
- Haunted!
- Heaps of hits on YouTube!
- Helo Cymru!
- Herregud!
- Holy cow, man!
- Home-made!
- Homeomorphic to a 3-sphere!
- Honey, I grew the bees!
- Honey, I waxed the copper!
- Hot tamale, hot hot tamale!
- Hotter than the sun!
+ How do I dig for mine?
- HURNERJSGER?
- I have a suggestion.
- I miss ADOM!
- I need more context.
- I see your vocabulary has improved!
- I'm glad you're here!
- idspispopd!
- if not ok then return end
- In case it isn't obvious, foxes aren't players.
- Indev!
- Indie!
+ Infinity 2.0: Now more finite!
- Information wants to be free!
- Ingots!
- Inspirational!
- Internet enabled!
+ Is that... is that a sphere!?
- It came from space.
- It swings, it jives!
- It's a game!
- It's finished!
- It's groundbreaking!
- It's here!
- Jag känner en bot!
- Jason! Jason! Jason!
- Java 16 + 1 + 4 = 21!
- Javalicious edition
- Jeb has amazing hair!
- Joel is neat!
- Joule is neat too!
- Jump up, jump up, and get down!
+ Just one more Mine
- Kaaneeeedaaaa!
- Keyboard compatible!
- Khaaaaaaaaan!
- Kick it root down!
- Kind of dragon free!
- Kinda like Lemmings!
- Kiss the sky!
- l33t!
- Larger than Earth!
- Learn about allyship!
- Legal in Finland!
- Lennart lennart = new Lennart();
- Less addictive than TV Tropes!
- Let our battle's begin!
- Let's danec!
- Leveraging synergy!
- Limited edition!
- Lives in a pineapple under the sea!
- Livestreamed!
- Look mum, I'm in a splash!
- Lots of truthiness!
- Loved by millions!
- Macroscopic!
- Made by "real" people!
- Made by Jeb!
- Made in Sweden!
- Made with lave!
- Make me a table, a funky table!
- MAP11 has two names!
- Matt Damon!
- May contain nuts!
- May contain traces of citrus!
- Meeting expectations!
- Menger sponge!
- Millions of peaches!
+ Mine your own business
+ Mine, you fools!
+ Minecraft À La Carte!
- Minecraft Java Edition presents: Disgusting Bugs
- Minecraft!
+ Minecraftlike!
- Minors welcome!
- Mmmph, mmph!
- Moderately attractive!
- Monster infighting!
- More addictive than lemonade!
- More Digital!
- More polygons!
- More than 500 sold!
- Music by C418!
- Music by Lena Raine!
- My life for Aiur!
- Never dig down!
- Nice to meet you!
- Nooooooooooooo!
- Not as cool as Spock!
- Not linear!
- Not on steam!
- Now contains 32 random daily cats!
- Now in 3D!
- Now on OpenGL 3.2 core profile!
- Now supports åäö!
- Now with additional stuff!
- Now with difficulty!
+ Now with even less realism!
- Now with extra hugs!
+ Now with magic!
+ Now with many more Mines!
- Now With Multiplayer!
+ Now with sphere-like objects!
- Now you are thinking with pistons!
- NP is not in P!
- Octagonal!
- Oh man!
- Oh, ok, Pigmen!
- OICU812!
- Omnipotent!
- One day, somewhere in the future, my work will be quoted!
- One of a kind!
+ Over 3 new items!
+ Participation awards!
- PC gaming since 1873!
- Peter Griffin!
- Ph1lza had a good run!
- Phobos anomaly!
- Ping the human!
- Pixels!
- Place ALL the blocks!
- Place hanging sign here
- Plant a tree!
- Plant-based light sources!
- Play him off, keyboard cat!
- Play Minecraft, Watch Topgear, Get Pig!
- Played by cowboys!
- pls rt
- Plz reply to my tweet!
- Pneumatic!
- Polynomial!
- Prepare, but don’t hoard!
- Pretty scary!
- Pretty!
+ Programmer Art without extra packs!
- Pumpa kungen!
- Pumpkinhead!
- Punching wood!
- Put a little fence around it!
- Put that cookie down!
- Rainbow turtle?
- Random splash!
- Read more books!
+ Reduced quality!
- Reference implementation!
- Regional resources!
- Remember to brush your... ...teeth
- Replaced molten cheese with blood?
- Representing Edsbyn!
- Reticulating splines!
- RIBBIT!
- Ride the pig!
- Rise from your grave!
- Rita is the new top dog!
- Rule #1: it's never my fault
- Run, coward! I hunger!
- Ryan also has amazing hair!
- Save the world – stay inside!
- Scary!
- Scientific!
+ Screens full of excitement!
+ Secret Tuesday update!
- See you next Friday or so!
- Seecret Friday update!
- Sensational!
- Shop for your elders!
- Should not be played while driving
- Shriek like a Sculk Shrieker!
- Singleplayer!
- Sniff sniff...
- So fresh, so clean!
- So sweet, like a nice bon bon!
- Soap and water!
- Something funny!
- Something's not quite right...
- Speak OUT against injustice and UP for equality!
- Spiders everywhere!
- sqrt(-1) love you!
- Stand up for equality in your community!
- Stay a while and listen!
- Stay a while, stay forever!
- Stay home and play games!
- Stay safe!
- Stay strong!
- Stop being reasonable, this is the Internet!
- Stop, hammertime!
- Strange, but not a stranger!
- Sublime!
- Supercalifragilisticexpialidocious!
- Support elderly relatives and friends!
- Support local businesses!
- Support the BIPOC community and creators!
- Survive!
- SWM forever!
- Swords for everyone!
- Synecdoche!
- Take an eggbeater and beat it against a skillet!
- Take frequent breaks!
- Take her pillow!
- Take the elevator to the mezzanine!
+ Talent trees!
- Technically good!
- Technoblade never dies!
- Technologic!
- Teetsuuuuoooo!
- Tell your friends!
- Terrestrial!
- Testificates!
- Thank you for the fish!
- That's no moon!
- That's Numberwang!
- That's super!
- The bee's knees!
- The creeper is a spy!
- The cutest predator you'll ever meet!
- The sky is the limit!
- The true meaning of covfefe
- Thematic!
- There's <<a cat on ,my keyboard!~
- There's no stopping the Trollmaso
- This is good for Realms.
- This is my true form!
- This message will never appear on the splash screen, isn't that weird?
- This parrot is no more! It has ceased to be!
- This sand is sus
- This text is hard to read if you play the game at the default resolution, but at 1080p it's fine!
- Thousands of colors!
- Throw a blanket over it!
- Throw yourself at the ground and miss
- Tip your waiter!
- Tougher than diamonds, rich like cream!
- Treatment for your rash!
- Truly gone fishing!
- Try it!
- Try the mushroom stew!
- Try the Nether!
- Turing complete!
- Twittered about!
- Tyrion would love it!
- Ultimate edition!
- umop-apisdn!
- Undefeated!
- Une baguette!
- Uninflammable!
+ Unlock ALL the things!
+ Unlockable!
- Uses LWJGL!
- Vanilla!
- Verlet integration!
- Very fun!
- Very influential in its circle!
- Vote for net neutrality!
- Warning! A huge battleship "STEVE" is approaching fast!
- Wash your hands!
- Water bottle!
- Water proof!
+ We joked every other year, but this time we are FOR REAL!
- Welcome to your Doom!
- What do you expect?
- What's the question?
- What's up, Doc?
- Where there is not light, there can spider!
- Who let the frogs out?
- Who put it there?
- Whoa, dude!
- Woah.
- Woo, 2pp!
- Woo, facepunch!
- Woo, reddit!
- Woo, somethingawful!
- Woo, tigsource!
- Woo, worldofminecraft!
+ Working as intended!
- Wow!
- Yaaay!
- Yay, puppies for everyone!
- Yes, sir!
- You are valid!
- You are welcome here!
- You can't explain that!
+ You RAM is the limit!
- You're going too fast!
- You've got a brand new key!
- Your gender is valid!
- Zoglin!?
- Γεια σου Ελλάδα!
- 한국 안녕하세요!
- 你好中国！
- 日本ハロー！
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
- XXX.advancements.critereon.UnlockPredicate
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedExitEyeTrigger
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaMineAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.advancements.packs.VanillaUnlockAdvancements
- XXX.ai.goal.package-info
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
- XXX.block.entity.MineTravellingBlockEntity
+ XXX.block.entity.package-info
- XXX.block.entity.PotDecorations
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SkullBlockEntity$1
- XXX.block.entity.SkullBlockEntity$2
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$1
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TestBlockEntity
- XXX.block.entity.TestInstanceBlockEntity
+ XXX.block.entity.TestInstanceBlockEntity$1
- XXX.block.entity.TestInstanceBlockEntity$Data
+ XXX.block.entity.TestInstanceBlockEntity$Status
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
- XXX.block.entity.TrialSpawnerBlockEntity
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
- XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.sounds.AmbientDesertBlockSoundsPlayer
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetFunction
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
- XXX.boss.enderdragon.DragonFlightHistory
+ XXX.boss.enderdragon.DragonFlightHistory$Sample
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
- XXX.commands.arguments.ResourceOrIdArgument
+ XXX.commands.arguments.ResourceOrIdArgument$LootModifierArgument
- XXX.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
+ XXX.commands.arguments.ResourceOrIdArgument$LootTableArgument
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
- XXX.commands.arguments.ResourceSelectorArgument
+ XXX.commands.arguments.ResourceSelectorArgument$Info
- XXX.commands.arguments.ResourceSelectorArgument$Info$Template
- XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Info
+ XXX.commands.arguments.ScoreHolderArgument$Info$Template
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.SignedArgument
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.SlotsArgument
- XXX.commands.arguments.StringRepresentableArgument
+ XXX.commands.arguments.StyleArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TemplateMirrorArgument
- XXX.commands.arguments.TemplateRotationArgument
+ XXX.commands.arguments.TimeArgument
- XXX.commands.arguments.TimeArgument$Info
+ XXX.commands.arguments.TimeArgument$Info$Template
- XXX.commands.arguments.UuidArgument
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.DataCommands$StringProcessor
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
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
- XXX.data.worldgen.MineExitPools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractBlockPropertyFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributeIdPrefixFix
- XXX.datafix.fixes.AttributeModifierIdFix
+ XXX.datafix.fixes.AttributesRenameFix
- XXX.datafix.fixes.AttributesRenameLegacy
+ XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
- XXX.datafix.fixes.BannerPatternFormatFix
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehiveFieldRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockPropertyRenameAndFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.BoatSplitFix
- XXX.datafix.fixes.CarvingStepRemoveFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkDeleteLightFix
+ XXX.datafix.fixes.ChunkHeightAndBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkTicketUnpackPosFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.CustomModelDataExpandFix
+ XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
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
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.InlineBlockPosFormatFix
+ XXX.datafix.fixes.InvalidBlockEntityLockFix
- XXX.datafix.fixes.InvalidLockComponentFix
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
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LegacyHoverEventFix
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
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerEquipmentFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.ProjectileStoredWeaponFix
- XXX.datafix.fixes.RaidRenamesDataFix
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.References$1
+ XXX.datafix.fixes.RemapChunkStatusFix
- XXX.datafix.fixes.RemoveEmptyItemInBrushableBlockFix
+ XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.RenameEnchantmentsFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SaddleEquipmentSlotFix
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.ScoreboardDisplayNameFix
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
+ XXX.datafix.fixes.TextComponentStrictJsonFix
- XXX.datafix.fixes.TextComponentStringifiedFlagsFix
+ XXX.datafix.fixes.ThrownPotionSplitFix
- XXX.datafix.fixes.ThrownPotionSplitFix$ItemIdFinder
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TooltipDisplayComponentFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.TrialSpawnerConfigFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
- XXX.datafix.fixes.UnflattenTextComponentFix
+ XXX.datafix.fixes.VariantRenameFix
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerSetCanPickUpLootFix
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
- XXX.datafix.schemas.V1458
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1488
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1925
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2511_1
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
+ XXX.datafix.schemas.V3439
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
- XXX.datafix.schemas.V4317
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
- XXX.entity.ai.package-info
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
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.AngryGhast$AngryGhastLookGoal
- XXX.entity.monster.AngryGhast$AngryGhastShootFireballGoal
- XXX.entity.pets.PetArmadillo
- XXX.entity.pets.PetArmadillo$2
- XXX.entity.pets.PetAxolotl$AnimationState
- XXX.entity.pets.PetAxolotl$AxolotlLookControl
- XXX.entity.pets.PetBee
- XXX.entity.pets.PetBee$BaseBeeGoal
- XXX.entity.pets.PetBee$BeeHurtByOtherGoal
- XXX.entity.pets.PetCat
- XXX.entity.pets.PetCow
- XXX.entity.pets.PetFox
- XXX.entity.pets.PetFox$FoxLookControl
- XXX.entity.pets.PetFrog
- XXX.entity.pets.PetFrog$FrogNodeEvaluator
- XXX.entity.pets.PetMushroomCow
- XXX.entity.pets.PetPolarBear$PolarBearAttackPlayersGoal
- XXX.entity.pets.PetPolarBear$PolarBearMeleeAttackGoal
- XXX.entity.pets.PetSlime$SlimeFloatGoal
- XXX.entity.pets.PetSlime$SlimeMoveControl
- XXX.entity.pets.PetTurtle$PetTurtlePathNavigation
- XXX.entity.pets.PetTurtle$TurtleRandomStrollGoal
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
- XXX.entity.trialspawner.package-info
- XXX.entity.trialspawner.PlayerDetector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
- XXX.entity.trialspawner.TrialSpawner
+ XXX.entity.trialspawner.TrialSpawner$FlameParticle
- XXX.entity.trialspawner.TrialSpawner$StateAccessor
+ XXX.entity.trialspawner.TrialSpawnerConfig
- XXX.entity.trialspawner.TrialSpawnerConfig$Builder
+ XXX.entity.trialspawner.TrialSpawnerConfigs
- XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
+ XXX.entity.trialspawner.TrialSpawnerData
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
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
- XXX.entity.vault.package-info
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
+ XXX.entity.vault.VaultState$LightLevel
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
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.PlaceTemplateConfiguration
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
+ XXX.feature.treedecorators.AttachedToLogsDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.CreakingHeartDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.PaleMossDecorator
+ XXX.feature.treedecorators.PlaceOnGroundDecorator
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
+ XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents
+ XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.ItemExchangeValue
- XXX.item.component.RoomerinoComponentino
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
+ XXX.item.component.Weapon
- XXX.item.component.WorldModifiers
+ XXX.level.biome.AmbientAdditionsSettings
- XXX.level.biome.AmbientMoodSettings
+ XXX.level.biome.AmbientParticleSettings
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$ClimateSettings
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$TemperatureModifier
- XXX.level.biome.Biome$TemperatureModifier$1
+ XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeBuilder
- XXX.level.biome.BiomeModificationBuilder
+ XXX.level.biome.BiomeResolver
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSources
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeSpecialEffects$ExitType
- XXX.level.biome.ClimateSettings
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
+ XXX.level.biome.MultiNoiseBiomeSourceParameterLists
- XXX.level.biome.OverworldBiomeBuilder
- XXX.level.biome.package-info
+ XXX.level.biome.TheEndBiomeSource
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractCandleBlock
+ XXX.level.block.AbstractCauldronBlock
- XXX.level.block.AbstractChestBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock
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
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BigDripleafBlock
- XXX.level.block.BigDripleafStemBlock
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
- XXX.level.block.CactusBlock
+ XXX.level.block.CactusFlowerBlock
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
+ XXX.level.block.ChangeOverTimeBlock
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
+ XXX.level.block.ColoredFallingBlock
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CopperBulbBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CrafterBlock
- XXX.level.block.CrafterBlock$1
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CreakingHeartBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.MineRevisitorBlock
- XXX.level.block.Mirror
- XXX.level.block.MobTrophyBlock$Grade
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
+ XXX.level.block.package-info
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
- XXX.level.block.TrophyBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
+ XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$DistancePerDirection
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$PackedTicks
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
- XXX.level.dimension.DimensionSpecialEffects
- XXX.level.dimension.DimensionSpecialEffects$CubeSky
- XXX.level.dimension.DimensionSpecialEffects$FogScaler
- XXX.level.dimension.DimensionSpecialEffects$FogScaler$2
- XXX.level.dimension.DimensionSpecialEffects$OverworldSky
- XXX.level.dimension.DimensionSpecialEffects$Sky
- XXX.level.levelgen.HubLevelSource
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
- XXX.level.levelgen.NoiseGeneratorSettings$Builder
- XXX.level.levelgen.package-info
- XXX.level.mines.Battle$Builder
- XXX.level.mines.Battle$SpawnGroup$Builder
- XXX.level.mines.Battle$SpawnStrategy$Builder
- XXX.level.mines.Battle$Wave
- XXX.level.mines.CustomIcons
- XXX.level.mines.MineEvent
- XXX.level.mines.MineEventData
- XXX.level.mines.RaidEvent
- XXX.level.mines.SpecialMine
- XXX.level.mines.SpecialMines
- XXX.level.mines.WorldEffect
- XXX.level.mines.WorldEffectComponent
- XXX.level.mines.WorldEffects
- XXX.level.mines.WorldGenBuilder$ChunkGeneratorGenerator
- XXX.level.mines.WorldGenBuilder$Processor
- XXX.level.mines.WorldGenEffect$AddBiome
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.Path$DebugData
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.PathfindingContext
- XXX.level.pathfinder.PathType
+ XXX.level.pathfinder.PathTypeCache
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator$1
- XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalShape
- XXX.level.portal.TeleportTransition
+ XXX.level.portal.TeleportTransition$PostTeleportTransition
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
+ XXX.level.redstone.DefaultRedstoneWireEvaluator
- XXX.level.redstone.ExperimentalRedstoneUtils
+ XXX.level.redstone.ExperimentalRedstoneWireEvaluator
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.Orientation
+ XXX.level.redstone.Orientation$SideBias
- XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.redstone.RedstoneWireEvaluator
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Context
+ XXX.level.saveddata.SavedDataType
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
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.level.validation.ContentValidationException
- XXX.level.validation.DirectoryValidator
+ XXX.level.validation.DirectoryValidator$1
- XXX.level.validation.ForbiddenSymlinkInfo
- XXX.level.validation.package-info
+ XXX.level.validation.PathAllowList
- XXX.level.validation.PathAllowList$ConfigEntry
+ XXX.level.validation.PathAllowList$EntryType
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PlaceTemplateFeature
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
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CountOnEveryLayerPlacement
+ XXX.levelgen.placement.CountPlacement
- XXX.levelgen.placement.EnvironmentScanPlacement
+ XXX.levelgen.placement.FixedPlacement
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
- XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
- XXX.levelgen.structure.Structure
+ XXX.levelgen.structure.Structure$GenerationContext
- XXX.levelgen.structure.Structure$GenerationStub
+ XXX.levelgen.structure.Structure$StructureSettings
- XXX.levelgen.structure.Structure$StructureSettings$Builder
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
- XXX.loot.packs.package-info
- XXX.loot.packs.VanillaHubRewardLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
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
- XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.TreeNodePosition
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
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$WorldReloader
+ XXX.minecraft.server.package-info
- XXX.minecraft.server.ServerPlayerUnlocks$Data
- XXX.minecraft.server.TheGame
- XXX.minecraft.server.TheGame$ReloadableResources
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
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
+ XXX.minecraft.tags.DamageTypeTags
- XXX.minecraft.tags.EnchantmentTags
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
+ XXX.minecraft.tags.TagLoader$ElementLookup
- XXX.minecraft.tags.TagLoader$EntryWithSource
+ XXX.minecraft.tags.TagLoader$LoadResult
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer
+ XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.AbstractListBuilder
+ XXX.minecraft.util.ARGB
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
+ XXX.minecraft.util.FileSystemUtil
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FutureChain
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.GsonHelper$CountedAppendable
+ XXX.minecraft.util.HashOps
- XXX.minecraft.util.HashOps$ListHashBuilder
+ XXX.minecraft.util.HashOps$MapHashBuilder
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.HttpUtil$DownloadProgressListener
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.ListAndDeque
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.NullOps
+ XXX.minecraft.util.NullOps$NullListBuilder
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.PlaceholderLookupProvider
- XXX.minecraft.util.PlaceholderLookupProvider$1
+ XXX.minecraft.util.PlaceholderLookupProvider$2
- XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
+ XXX.minecraft.util.PngInfo
- XXX.minecraft.util.ProblemReporter
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
- XXX.minecraft.util.RegistryContextSwapper
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
- XXX.minecraft.util.StaticCache2D
+ XXX.minecraft.util.StaticCache2D$Initializer
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.MineData$MineState
+ XXX.minecraft.world.package-info
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
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
+ XXX.pools.alias.DirectPoolAlias
+ XXX.pools.alias.package-info
- XXX.pools.alias.PoolAliasBinding
+ XXX.pools.alias.PoolAliasBindings
- XXX.pools.alias.PoolAliasLookup
+ XXX.pools.alias.RandomGroupPoolAlias
- XXX.pools.alias.RandomPoolAlias
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.package-info
+ XXX.projectile.windcharge.WindCharge
- XXX.protocol.game.ClientboundChangeDimensionTypePacket
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
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveMinecartPacket
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenDoorPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundOpenWindowPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateUnlockedEffectsPacket
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatCommandSignedPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundChunkBatchReceivedPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientTickEndPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
- XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQueryPacket
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemFromBlockPacket
- XXX.protocol.game.ServerboundPickItemFromEntityPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerDonateExperiencePacket
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundPlayerLoadedPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
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
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$Runner
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
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
+ XXX.server.commands.FillCommand$Affector
- XXX.server.commands.FillCommand$Filter
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.FillCommand$NullableCommandFunction
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$1
- XXX.server.commands.FunctionCommand$1Accumulator
+ XXX.server.commands.FunctionCommand$2
- XXX.server.commands.FunctionCommand$3
+ XXX.server.commands.FunctionCommand$4
- XXX.server.commands.FunctionCommand$5
+ XXX.server.commands.FunctionCommand$Callbacks
- XXX.server.commands.FunctionCommand$FunctionCustomExecutor
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.InCommandFunction
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.package-info
- XXX.server.commands.RotateCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- XXX.server.commands.SeedCommand
+ XXX.server.commands.ServerPackCommand
- XXX.server.commands.SetBlockCommand
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
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TickCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TransferCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.UnlockCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkGenerationTask
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskDispatcher
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DimensionGenerator
- XXX.server.level.DimensionGenerator$FakeLevelStem
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
- XXX.server.level.LoadingChunkTracker
+ XXX.server.level.package-info
+ XXX.server.level.ParticleStatus
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerEntityGetter
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$1$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayer$RespawnConfig
+ XXX.server.level.ServerPlayer$RespawnPosAngle
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.SimulationChunkTracker
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.ThrottlingChunkTaskDispatcher
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TicketType$TicketUse
- XXX.server.level.WorldGenRegion
- XXX.server.network.CommonListenerCookie
+ XXX.server.network.ConfigurationTask
- XXX.server.network.ConfigurationTask$Type
+ XXX.server.network.Filterable
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.LegacyTextFilter
- XXX.server.network.LegacyTextFilter$1
+ XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.PlayerSafetyServiceTextFilter
+ XXX.server.network.ServerCommonPacketListenerImpl
- XXX.server.network.ServerConfigurationPacketListenerImpl
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
- XXX.server.network.ServerHibernateConfigPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.ServerTextFilter
- XXX.server.network.ServerTextFilter$IgnoreStrategy
+ XXX.server.network.ServerTextFilter$MessageEncoder
- XXX.server.network.ServerTextFilter$PlayerContext
+ XXX.server.network.ServerTextFilter$RequestFailedException
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
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
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.PlayerUnlock
- XXX.server.players.PlayerUnlock$UnlockVisibility
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
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockSetType
+ XXX.state.properties.BlockSetType$PressurePlateSensitivity
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.CreakingHeartState
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
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
+ XXX.state.properties.TestBlockMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
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
- XXX.structure.placement.package-info
+ XXX.structure.placement.RandomSpreadStructurePlacement
- XXX.structure.placement.RandomSpreadType
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
+ XXX.structure.placement.StructurePlacement$FrequencyReducer
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
+ XXX.structure.placement.StructurePlacementType
+ XXX.structure.pools.DimensionPadding
- XXX.structure.pools.EmptyPoolElement
+ XXX.structure.pools.FeaturePoolElement
- XXX.structure.pools.JigsawJunction
+ XXX.structure.pools.JigsawPlacement
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
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
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.LiquidSettings
+ XXX.structure.templatesystem.NopProcessor
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
- XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.StructureTemplateManager$SourceType
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
+ XXX.util.context.ContextKey
- XXX.util.context.ContextKeySet
+ XXX.util.context.ContextKeySet$Builder
- XXX.util.context.ContextMap
+ XXX.util.context.ContextMap$Builder
- XXX.util.context.package-info
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.LegacyComponentDataFixUtils
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
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
- XXX.warden.Stages.StageFour
- XXX.warden.Stages.StageOne
- XXX.warden.Stages.StageTwo
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
- XXX.world.inventory.AbstractCraftingMenu$2
- XXX.world.inventory.AbstractFurnaceMenu$2
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$1
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
- XXX.world.inventory.DimensionControlMenu
- XXX.world.inventory.DimensionControlMenu$2
- XXX.world.inventory.DoorMenu
- XXX.world.inventory.DoorMenu$FieldType
- XXX.world.inventory.DoorMenu$PlacementInfo
- XXX.world.inventory.GhettoSpline$Entry
- XXX.world.inventory.InventoryMenu$2
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
- XXX.world.inventory.MineCraftingDrawerSlot
- XXX.world.inventory.MineCraftingMenu
- XXX.world.inventory.MineCraftingSlot
+ XXX.world.inventory.package-info
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
- XXX.world.item.ExperienceBottleItem
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
- XXX.world.item.ShimmeringKeyItem
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
- XXX.world.item.TeleportationWandItem
- XXX.world.item.WindWandItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.package-info
- XXX.world.level.UnlockCondition
- XXX.world.level.UnlockCondition$10
- XXX.world.level.UnlockCondition$12
- XXX.world.level.UnlockCondition$14
- XXX.world.level.UnlockCondition$16
- XXX.world.level.UnlockCondition$18
- XXX.world.level.UnlockCondition$2
- XXX.world.level.UnlockCondition$3
- XXX.world.level.UnlockCondition$5
- XXX.world.level.UnlockCondition$7
- XXX.world.level.UnlockCondition$9
+ XXX.world.level.WorldDataConfiguration
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.AABB$Builder
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
- XXX.world.scores.Objective$Packed
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.PlayerTeam$Packed
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.ScoreAccess
- XXX.world.scores.Scoreboard
+ XXX.world.scores.Scoreboard$1
- XXX.world.scores.Scoreboard$PackedScore
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.ScoreboardSaveData$Packed
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
net.minecraft.SharedConstants +1P
```
```
XXX.minecraft.advancements.CriteriaTriggers +10P -1P
```
```
XXX.minecraft.advancements.DisplayInfo +2M -1M | +1P
```
```
XXX.loot.packs.VanillaBlockLoot +27M -25M
```
```
XXX.worldgen.placement.MiscOverworldPlacements +2P
```
```
XXX.worldgen.placement.OrePlacements +2P
```
```
XXX.gametest.framework.GameTestServer$1 +1M -1M
```
```
XXX.network.chat.Style$Serializer +3M -1M
```
```
XXX.protocol.game.ClientGamePacketListener +6P -1P
```
```
XXX.minecraft.server.Main +6M -1M
```
```
XXX.minecraft.server.MinecraftServer +49M -98M | +7P -18P
```
```
XXX.minecraft.server.ServerFunctionManager +1M -1M | +1P -1P
```
```
XXX.server.commands.PerfCommand +2M -2M
```
```
XXX.server.players.OldUsersConverter +1M -1M
```
```
XXX.util.debugchart.RemoteSampleLogger +3M
```
```
XXX.util.random.WeightedList$Builder +1M
```
```
XXX.util.worldupdate.WorldUpgrader +1P
```
```
XXX.minecraft.world.Container +1M
```
```
XXX.minecraft.world.MenuProvider +1M
```
```
XXX.world.damagesource.DamageSources +1M
```
```
XXX.world.damagesource.DamageTypes +1P
```
```
XXX.world.entity.Entity +1M -1M
```
```
XXX.world.entity.EntityType +15P
```
```
XXX.monster.warden.Warden +2M | +6P
```
```
XXX.entity.npc.VillagerProfession +1P
```
```
XXX.world.inventory.AbstractCraftingMenu +4M -3M
```
```
XXX.world.inventory.AbstractFurnaceMenu +1P
```
```
XXX.world.inventory.EnchantmentMenu +1M -1M
```
```
XXX.world.inventory.HopperMenu +1M -1M
```
```
XXX.world.inventory.InventoryMenu +3M
```
```
XXX.item.component.LodestoneTracker +4M -2M | +1P
```
```
XXX.item.component.WrittenBookContent +1M -1M
```
```
XXX.item.equipment.ArmorMaterial +2M -1M | +1P
```
```
XXX.equipment.trim.ArmorTrim +1M -1M
```
```
XXX.world.level.GameRules +8M -8M
```
```
XXX.world.level.GameRules$IntegerValue +4M -4M
```
```
XXX.world.level.Level +9M -1M | +6P
```
```
XXX.level.biome.MobSpawnSettings +3M
```
```
XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset +1P
```
```
XXX.level.block.SlimeBlock +1M -1M
```
```
XXX.block.entity.BlockEntityType +3P -1P
```
```
XXX.level.dimension.BuiltinDimensionTypes +2P
```
```
XXX.level.dimension.DimensionType +7M -2M | +2P -1P
```
```
XXX.level.dimension.LevelStem +9M -2M | +5P -3P
```
```
XXX.dimension.end.EndDragonFight$Data +1M -2M | -1P
```
```
XXX.level.levelgen.NoiseRouterData +1M -1M | -7P
```
```
XXX.level.levelgen.SurfaceRules$BiomeConditionSource +2M
```
```
XXX.level.levelgen.SurfaceRules$ConditionSource +1M
```
```
XXX.level.levelgen.SurfaceRules$RuleSource +1M
```
```
XXX.level.levelgen.SurfaceRules$SequenceRuleSource +2M
```
```
XXX.level.levelgen.SurfaceRules$TestRuleSource +1M
```
```
XXX.level.levelgen.WorldDimensions +7M -8M
```
```
XXX.levelgen.feature.Feature +1P
```

</details>
<details>
<summary>
net.minecraft.advancements.DisplayInfo
</summary>

```diff
- Component getHint()
- void <init>(ItemStack,Component,Component,Component,Optional,AdvancementType,boolean,boolean,boolean)
+ void <init>(ItemStack,Component,Component,Optional,AdvancementType,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$260(Integer)
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$261(Integer)
+ LootPoolEntryContainer$Builder lambda$generate$252(Block,Integer)
- LootPoolEntryContainer$Builder lambda$generate$254(Block,Integer)
- LootTable$Builder lambda$generate$204(Block)
+ LootTable$Builder lambda$generate$204(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$205(Block)
- LootTable$Builder lambda$generate$205(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$214(Block)
+ LootTable$Builder lambda$generate$214(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$216(Block)
- LootTable$Builder lambda$generate$216(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$220(Block)
+ LootTable$Builder lambda$generate$220(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$221(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$221(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$223(Block)
- LootTable$Builder lambda$generate$223(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$225(Block)
+ LootTable$Builder lambda$generate$225(VanillaBlockLoot,ItemLike)
+ LootTable$Builder lambda$generate$231(Block)
- LootTable$Builder lambda$generate$231(VanillaBlockLoot,ItemLike)
- LootTable$Builder lambda$generate$232(Block)
+ LootTable$Builder lambda$generate$232(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$233(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$233(VanillaBlockLoot,ItemLike)
+ LootTable$Builder lambda$generate$235(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$235(VanillaBlockLoot,ItemLike)
+ LootTable$Builder lambda$generate$236(Block)
- LootTable$Builder lambda$generate$236(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$243(Block)
+ LootTable$Builder lambda$generate$243(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$245(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$245(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$247(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$247(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$249(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$249(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$252(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$254(Block)
- LootTable$Builder lambda$generate$255(Block)
+ LootTable$Builder lambda$generate$255(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$256(Block)
- LootTable$Builder lambda$generate$256(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$257(Block)
+ LootTable$Builder lambda$generate$257(HolderLookup$RegistryLookup,Block)
+ LootTable$Builder lambda$generate$258(Block)
- LootTable$Builder lambda$generate$258(HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$259(Block)
+ LootTable$Builder lambda$generate$259(HolderLookup$RegistryLookup,HolderLookup$RegistryLookup,Block)
- LootTable$Builder lambda$generate$260(HolderLookup$RegistryLookup,HolderLookup$RegistryLookup,Block)
- void addTrophies()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer$1
</summary>

```diff
+ void <init>(GameTestServer,MinecraftServer,LayeredRegistryAccess,PlayerDataStorage,int)
- void <init>(GameTestServer,TheGame,PlayerDataStorage,int)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style$Serializer
</summary>

```diff
+ App lambda$static$11(RecordCodecBuilder$Instance)
- App lambda$static$13(RecordCodecBuilder$Instance)
- Optional lambda$static$11(Style)
- Optional lambda$static$12(Style)
```

</details>
<details>
<summary>
net.minecraft.server.Main
</summary>

```diff
- CompletableFuture lambda$createWorldReloader$5(WorldLoader$InitConfig,Dynamic,Executor)
- DedicatedServer lambda$main$3(LevelStorageSource$LevelStorageAccess,DedicatedServerSettings,Services,OptionSet,OptionSpec,OptionSpec,OptionSpec,OptionSpec,OptionSpec,Thread)
+ DedicatedServer lambda$main$3(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,DedicatedServerSettings,Services,OptionSet,OptionSpec,OptionSpec,OptionSpec,OptionSpec,OptionSpec,Thread)
- MinecraftServer$WorldReloader createWorldReloader(DedicatedServerSettings)
- WorldLoader$DataLoadOutput lambda$createWorldReloader$4(Dynamic,WorldLoader$DataLoadContext)
- WorldLoader$InitConfig createInitialConfig(WorldLoader$PackConfig,DedicatedServerProperties)
- WorldStem lambda$createWorldReloader$6(DedicatedServerSettings,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
+ boolean isHardcore()
- boolean isHardcore(TheGame)
+ boolean isSpawningMonsters()
- boolean isSpawningMonsters(TheGame)
+ boolean lambda$getSelectedPacks$30(Collection,String)
- boolean lambda$innerServerLoopWowo$6(Connection)
- boolean lambda$innerServerLoopWowo$7()
- boolean lambda$loadStatusIcon$10(Path)
+ boolean lambda$loadStatusIcon$12(Path)
- boolean lambda$managedBlock$8(BooleanSupplier)
+ boolean lambda$managedBlock$9(BooleanSupplier)
+ boolean lambda$runServer$8()
+ boolean lambda$stopServer$6(ServerLevel)
+ boolean lambda$stopServer$7()
- boolean lambda$stopTheGame$4(ServerLevel)
- boolean lambda$stopTheGame$5()
+ boolean lambda$waitUntilNextTick$10()
- boolean lambda$waitUntilNextTick$9()
+ boolean pollTaskInternal()
- boolean pollTaskInternal(TheGame)
+ boolean publishServer(GameType,boolean,int)
- boolean publishServer(TheGame,GameType,boolean,int)
+ boolean saveAllChunks(boolean,boolean,boolean)
+ boolean saveEverything(boolean,boolean,boolean)
- boolean saveEverything(TheGame,boolean,boolean,boolean)
+ Commands getCommands()
+ CommandSourceStack createCommandSourceStack()
+ CommandStorage getCommandStorage()
+ CompletableFuture reloadResources(Collection)
- CompletableFuture sayGoodbye()
+ CompletionStage lambda$reloadResources$28(ImmutableList)
+ CustomBossEvents getCustomBossEvents()
+ DataPackConfig getSelectedPacks(PackRepository,boolean)
- Executor taskExecutor()
+ FuelValues fuelValues()
+ GameRules getGameRules()
+ GameType getDefaultGameType()
+ GameType getForcedGameType()
- GameType getForcedGameType(TheGame)
+ ImmutableList lambda$reloadResources$25(Collection)
+ int computeNextAutosaveInterval()
- int computeNextAutosaveInterval(TheGame)
+ Iterable getAllLevels()
+ LayeredRegistryAccess registries()
+ MinecraftServer spin(Function)
- MinecraftServer spin(PackRepository,WorldStem,MinecraftServer$WorldReloader,ChunkProgressListenerFactory,Function)
+ MinecraftServer$ReloadableResources lambda$reloadResources$27(CloseableResourceManager,ReloadableServerResources)
- Optional lambda$loadStatusIcon$12()
+ Optional lambda$loadStatusIcon$13()
- Optional lambda$loadStatusIcon$13(Path)
+ Optional lambda$loadStatusIcon$14(Path)
+ Optional lambda$setInitialSpawn$4(Registry)
+ PackRepository getPackRepository()
+ PlayerList getPlayerList()
+ PotionBrewing potionBrewing()
+ RecipeManager getRecipeManager()
+ RegistryAccess$Frozen registryAccess()
+ ReloadableServerRegistries$Holder reloadableRegistries()
+ ResourceManager getResourceManager()
+ ServerAdvancementManager getAdvancements()
+ ServerFunctionManager getFunctions()
+ ServerLevel getLevel(ResourceKey)
+ ServerLevel overworld()
+ ServerScoreboard getScoreboard()
+ ServerStatus buildServerStatus()
- ServerStatus buildServerStatus(TheGame)
+ ServerStatus$Players buildPlayerStatus()
- ServerStatus$Players buildPlayerStatus(PlayerList)
+ ServerTickRateManager tickRateManager()
+ Set levelKeys()
- String lambda$dumpNativeModules$19(NativeModuleLister$NativeModuleInfo)
+ String lambda$dumpNativeModules$31(NativeModuleLister$NativeModuleInfo)
- String lambda$fillSystemReport$16()
+ String lambda$fillSystemReport$17()
- String lambda$fillSystemReport$17(PlayerList)
+ String lambda$fillSystemReport$19()
+ String lambda$fillSystemReport$20()
+ String lambda$fillSystemReport$21()
+ String lambda$fillSystemReport$22()
+ String lambda$fillSystemReport$23()
+ String lambda$fillSystemReport$24()
- String lambda$storeChunkIoError$23(RegionStorageInfo)
+ String lambda$storeChunkIoError$35(RegionStorageInfo)
- String lambda$tickChildren$15(ServerLevel)
+ String lambda$tickChildren$16(ServerLevel)
+ String[] getPlayerNames()
+ StructureTemplateManager getStructureManager()
- TheGame theGame()
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Proxy,DataFixer,Services,ChunkProgressListenerFactory)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,Proxy,DataFixer,Services)
+ void autoSave()
- void autoSave(TheGame)
+ void createLevels(ChunkProgressListener)
+ void dumpGameRules(Path)
+ void enableForcedFeaturePacks(PackRepository,FeatureFlagSet)
+ void forceDifficulty()
- void forceDifficulty(TheGame)
+ void forceTimeSynchronization()
- void innerServerLoopWowo(TheGame)
- void lambda$createProfiler$20(Path)
- void lambda$createProfiler$21(Path)
+ void lambda$createProfiler$32(Path)
+ void lambda$createProfiler$33(Path)
+ void lambda$reloadResources$26(CloseableResourceManager,ReloadableServerResources,Throwable)
+ void lambda$reloadResources$29(Collection,MinecraftServer$ReloadableResources)
+ void lambda$setInitialSpawn$5(ServerLevel,ServerChunkCache,ServerLevelData,Holder$Reference)
- void lambda$spin$2(AtomicReference,PackRepository,WorldStem,MinecraftServer$WorldReloader,ChunkProgressListenerFactory)
+ void lambda$spin$2(AtomicReference)
- void lambda$startRecordingMetrics$22(Consumer,ProfileResults)
+ void lambda$startRecordingMetrics$34(Consumer,ProfileResults)
- void lambda$storeChunkIoError$24(RegionStorageInfo,CrashReport,ChunkPos)
+ void lambda$storeChunkIoError$36(RegionStorageInfo,CrashReport,ChunkPos)
- void lambda$tickChildren$14(ServerPlayer)
+ void lambda$tickChildren$15(ServerPlayer)
+ void loadLevel()
+ void onTickRateChanged()
- void onTickRateChanged(TheGame)
+ void prepareLevels(ChunkProgressListener)
+ void readScoreboard(DimensionDataStorage)
- void restoreAllPlayersConfigPlayers(TheGame)
- void runNextTickNow()
+ void runServer()
- void runServer(PackRepository,WorldStem,MinecraftServer$WorldReloader,ChunkProgressListenerFactory)
- void runTicksDuringServerPrepare()
+ void sendDifficultyUpdate(ServerPlayer)
+ void setDefaultGameType(GameType)
- void setDefaultGameType(TheGame,GameType)
+ void setDifficulty(Difficulty,boolean)
+ void setDifficultyLocked(boolean)
+ void setInitialSpawn(ServerLevel,ServerLevelData,boolean,boolean)
+ void setPlayerIdleTimeout(int)
- void setPlayerIdleTimeout(TheGame,int)
+ void setPlayerList(PlayerList)
+ void setupDebugLevel(WorldData)
+ void stopServer()
- void stopServer(TheGame)
- void stopTheGame(TheGame)
+ void synchronizeTime(ServerLevel)
+ void tickChildren(BooleanSupplier)
- void tickChildren(TheGame,BooleanSupplier)
+ void tickServer(BooleanSupplier)
- void tickServer(TheGame,BooleanSupplier)
+ void updateMobSpawningFlags()
- void waitForPlayersToEnterConfig()
+ WorldData getWorldData()
+ WorldDataConfiguration configurePackRepository(PackRepository,WorldDataConfiguration,boolean,boolean)
+ WorldDataConfiguration configureRepositoryWithSelection(PackRepository,Collection,FeatureFlagSet,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionManager
</summary>

```diff
+ void <init>(MinecraftServer,ServerFunctionLibrary)
- void <init>(TheGame,ServerFunctionLibrary)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PerfCommand
</summary>

```diff
+ void lambda$startProfilingDedicatedServer$4(CommandSourceStack,MinecraftServer,Path)
- void lambda$startProfilingDedicatedServer$4(CommandSourceStack,Path)
+ void saveResults(CommandSourceStack,Path,MinecraftServer)
- void saveResults(CommandSourceStack,Path,TheGame)
```

</details>
<details>
<summary>
net.minecraft.server.players.OldUsersConverter
</summary>

```diff
+ UUID convertMobOwnerIfNecessary(MinecraftServer,String)
- UUID convertMobOwnerIfNecessary(TheGame,String)
```

</details>
<details>
<summary>
net.minecraft.util.debugchart.RemoteSampleLogger
</summary>

```diff
- boolean isEnabled()
- void subscribe(ServerPlayer,RemoteDebugSampleType)
- void tick(int)
```

</details>
<details>
<summary>
net.minecraft.util.random.WeightedList$Builder
</summary>

```diff
- WeightedList$Builder clear()
```

</details>
<details>
<summary>
net.minecraft.world.Container
</summary>

```diff
- Player getPlayer()
```

</details>
<details>
<summary>
net.minecraft.world.MenuProvider
</summary>

```diff
- List getAdditionalData()
```

</details>
<details>
<summary>
net.minecraft.world.damagesource.DamageSources
</summary>

```diff
- DamageSource devour(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ MinecraftServer getServer()
- TheGame theGame()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
- void lambda$stopActing$1(Player)
- void stopActing()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractCraftingMenu
</summary>

```diff
+ int getGridHeight()
- int getGridHeight(Player)
+ int getGridWidth()
- int getGridWidth(Player)
+ void addCraftingGridSlots(int,int)
- void addCraftingGridSlots(Player,int,int)
- void adjustCraftingGridSlotsPosition(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.EnchantmentMenu
</summary>

```diff
- void <init>(int,Inventory,List)
+ void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.HopperMenu
</summary>

```diff
- void <init>(int,Inventory,List)
+ void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.InventoryMenu
</summary>

```diff
- int getGridHeight(Player)
- int getGridWidth(Player)
- void menuTick(Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.LodestoneTracker
</summary>

```diff
- boolean exits()
- LodestoneTracker getExitTracker(BlockPos,ServerLevel)
- LodestoneTracker tick(BlockPos,ServerLevel)
+ LodestoneTracker tick(ServerLevel)
- void <init>(Optional,boolean,boolean)
+ void <init>(Optional,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.WrittenBookContent
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.equipment.ArmorMaterial
</summary>

```diff
- float experienceExchangeValue()
- void <init>(int,Map,int,Holder,float,float,TagKey,ResourceKey,float)
+ void <init>(int,Map,int,Holder,float,float,TagKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.equipment.trim.ArmorTrim
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
+ void assignCap(GameRules$Key,GameRules,MinecraftServer)
- void assignCap(GameRules$Key,GameRules,TheGame)
+ void assignFrom(GameRules,MinecraftServer)
- void assignFrom(GameRules,TheGame)
+ void lambda$assignFrom$18(GameRules,MinecraftServer,GameRules$Key)
- void lambda$assignFrom$18(GameRules,TheGame,GameRules$Key)
+ void lambda$static$10(MinecraftServer,GameRules$IntegerValue)
- void lambda$static$10(TheGame,GameRules$IntegerValue)
+ void lambda$static$11(MinecraftServer,GameRules$IntegerValue)
- void lambda$static$11(TheGame,GameRules$IntegerValue)
+ void lambda$static$7(MinecraftServer,GameRules$BooleanValue)
- void lambda$static$7(TheGame,GameRules$BooleanValue)
+ void lambda$static$8(MinecraftServer,GameRules$BooleanValue)
- void lambda$static$8(TheGame,GameRules$BooleanValue)
+ void lambda$static$9(MinecraftServer,GameRules$BooleanValue)
- void lambda$static$9(TheGame,GameRules$BooleanValue)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$IntegerValue
</summary>

```diff
+ void lambda$create$3(MinecraftServer,GameRules$IntegerValue)
- void lambda$create$3(TheGame,GameRules$IntegerValue)
+ void set(int,MinecraftServer)
- void set(int,TheGame)
+ void setFrom(GameRules$IntegerValue,MinecraftServer)
- void setFrom(GameRules$IntegerValue,TheGame)
+ void setFrom(GameRules$Value,MinecraftServer)
- void setFrom(GameRules$Value,TheGame)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- boolean getIsBouncy()
- boolean getIsIcy()
- boolean isActive(WorldEffect)
- boolean isEffectUnlocked(WorldEffect)
- boolean isMine()
- List getActiveEffects()
- List getUnlockedEffects()
+ MinecraftServer getServer()
- TheGame theGame()
- void setDimensionType(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- MobSpawnSettings$Builder asBuilder()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
+ void updateEntityMovementAfterFallOn(BlockGetter,Entity)
- void updateEntityMovementAfterFallOn(Level,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.DimensionType
</summary>

```diff
- DimensionSpecialEffects dimensionSpecialEffects()
- DimensionType asPiglinSafe()
- DimensionType madeUltrawarm()
- DimensionType withAmbientLight()
- DimensionType withSpecialEffects(DimensionSpecialEffects)
- DimensionType withSpecialEffects(UnaryOperator)
+ ResourceLocation effectsLocation()
- void <init>(OptionalLong,boolean,boolean,boolean,boolean,double,boolean,boolean,int,int,int,TagKey,DimensionSpecialEffects,float,DimensionType$MonsterSettings)
+ void <init>(OptionalLong,boolean,boolean,boolean,boolean,double,boolean,boolean,int,int,int,TagKey,ResourceLocation,float,DimensionType$MonsterSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.LevelStem
</summary>

```diff
+ ChunkGenerator generator()
- ChunkGenerator generator(HolderLookup$Provider,Holder$Reference)
- List effects()
- MineSpawnStrategy spawn()
- MutableObject generatorCache()
- Optional generator()
- Optional mine()
+ void <init>(Holder,ChunkGenerator)
- void <init>(Holder,Optional,List,Optional,MineSpawnStrategy,MutableObject)
- void <init>(Holder,Optional,List,Optional,MineSpawnStrategy)
- void lambda$generator$1(WorldGenBuilder,WorldGenEffect)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.end.EndDragonFight$Data
</summary>

```diff
+ Optional gateways()
+ void <init>(boolean,boolean,boolean,boolean,Optional,Optional,Optional)
- void <init>(boolean,boolean,boolean,boolean,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
- DensityFunction underground(HolderGetter,HolderGetter,DensityFunction,boolean)
+ DensityFunction underground(HolderGetter,HolderGetter,DensityFunction)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
</summary>

```diff
- ResourceKey lambda$mapBiomes$1(Map,ResourceKey)
- SurfaceRules$ConditionSource mapBiomes(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
</summary>

```diff
- SurfaceRules$ConditionSource mapBiomes(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
</summary>

```diff
- SurfaceRules$RuleSource mapBiomes(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
</summary>

```diff
- SurfaceRules$RuleSource lambda$mapBiomes$0(Map,SurfaceRules$RuleSource)
- SurfaceRules$RuleSource mapBiomes(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
</summary>

```diff
- SurfaceRules$RuleSource mapBiomes(Map)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldDimensions
</summary>

```diff
+ boolean isStableEnd(LevelStem)
+ boolean isStableNether(LevelStem)
+ boolean isStableOverworld(LevelStem)
- boolean lambda$stripGenerated$2(Map$Entry)
+ Optional lambda$bake$3(ResourceKey)
- Optional lambda$bake$4(ResourceKey)
+ PrimaryLevelData$SpecialWorldProperty lambda$specialWorldProperty$2(LevelStem)
- PrimaryLevelData$SpecialWorldProperty lambda$specialWorldProperty$3(LevelStem)
+ void lambda$bake$4(List,ResourceKey,LevelStem)
- void lambda$bake$5(List,ResourceKey,LevelStem)
+ void lambda$bake$5(Registry,List,ResourceKey)
- void lambda$bake$6(Registry,List,ResourceKey)
+ void lambda$bake$6(WritableRegistry,WorldDimensions$1Entry)
- void lambda$bake$7(WritableRegistry,WorldDimensions$1Entry)
- WorldDimensions stripGenerated()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
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
- XXX.advancements.critereon.UnlockPredicate$Builder
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedExitEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaFeatsAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.ai.goal.package-info
- XXX.ai.goal.PetWolfBegGoal
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
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.CreakingAnimation
+ XXX.animation.definitions.FrogAnimation
- XXX.animation.definitions.package-info
- XXX.animation.definitions.SnifferAnimation
+ XXX.animation.definitions.WardenAnimation
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
- XXX.atlas.sources.DirectoryLister
+ XXX.atlas.sources.LazyLoadedImage
+ XXX.atlas.sources.package-info
- XXX.atlas.sources.PalettedPermutations
+ XXX.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
- XXX.atlas.sources.SingleFile
+ XXX.atlas.sources.SourceFilter
- XXX.atlas.sources.Unstitcher
+ XXX.atlas.sources.Unstitcher$Region
- XXX.atlas.sources.Unstitcher$RegionInstance
- XXX.block.entity.MineCrafterBlockEntity
- XXX.block.entity.MobTrophyBlockEntity
- XXX.block.entity.package-info
+ XXX.block.entity.PotDecorations
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SkullBlockEntity$1
+ XXX.block.entity.SkullBlockEntity$2
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TestBlockEntity
+ XXX.block.entity.TestInstanceBlockEntity
- XXX.block.entity.TestInstanceBlockEntity$1
+ XXX.block.entity.TestInstanceBlockEntity$Data
- XXX.block.entity.TestInstanceBlockEntity$Status
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.entity.TrialSpawnerBlockEntity
+ XXX.block.grower.package-info
- XXX.block.grower.TreeGrower
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementFace$UVs
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$MultiPartDefinition
+ XXX.block.model.BlockModelDefinition$SimpleModelSelectors
- XXX.block.model.BlockModelPart
+ XXX.block.model.BlockModelPart$Unbaked
- XXX.block.model.BlockStateModel
+ XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot
- XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot$1
+ XXX.block.model.BlockStateModel$Unbaked
- XXX.block.model.BlockStateModel$UnbakedRoot
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.package-info
+ XXX.block.model.SimpleModelWrapper
- XXX.block.model.SimpleUnbakedGeometry
+ XXX.block.model.SingleVariant
- XXX.block.model.SingleVariant$Unbaked
+ XXX.block.model.TextureSlots
- XXX.block.model.TextureSlots$Data
+ XXX.block.model.TextureSlots$Data$Builder
- XXX.block.model.TextureSlots$Reference
+ XXX.block.model.TextureSlots$Resolver
- XXX.block.model.TextureSlots$SlotContents
+ XXX.block.model.TextureSlots$Value
- XXX.block.model.Variant
+ XXX.block.model.Variant$SimpleModelState
- XXX.block.model.VariantMutator
+ XXX.block.model.VariantMutator$VariantProperty
- XXX.block.model.VariantSelector
+ XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.sounds.AmbientDesertBlockSoundsPlayer
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
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
+ XXX.client.animation.package-info
+ XXX.client.gui.package-info
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
+ XXX.client.model.AllayModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmadilloModel
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.ArrowModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BabyModelTransform
- XXX.client.model.BannerFlagModel
+ XXX.client.model.BannerModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BeeStingerModel
+ XXX.client.model.BellModel
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BoggedModel
+ XXX.client.model.BookModel
- XXX.client.model.BreezeModel
+ XXX.client.model.CamelModel
- XXX.client.model.CamelSaddleModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColdChickenModel
- XXX.client.model.ColdCowModel
+ XXX.client.model.ColdPigModel
- XXX.client.model.CowModel
+ XXX.client.model.CreakingModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DonkeyModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndCrystalModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EquineSaddleModel
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
+ XXX.client.model.package-info
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
- XXX.client.model.WarmCowModel
+ XXX.client.model.WindChargeModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.model.ZombifiedPiglinModel
- XXX.client.multiplayer.AccountProfileKeyPairManager
+ XXX.client.multiplayer.CacheSlot
- XXX.client.multiplayer.CacheSlot$Cleaner
+ XXX.client.multiplayer.ChunkBatchSizeCalculator
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientCommonPacketListenerImpl
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
- XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl$1
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientPlayerUnlocks
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
+ XXX.client.particle.FireflyParticle
- XXX.client.particle.FireflyParticle$FireflyProvider
+ XXX.client.particle.FireworkParticles
- XXX.client.particle.FireworkParticles$1
+ XXX.client.particle.FireworkParticles$FlashProvider
- XXX.client.particle.FireworkParticles$OverlayParticle
+ XXX.client.particle.FireworkParticles$SparkParticle
- XXX.client.particle.FireworkParticles$SparkProvider
+ XXX.client.particle.FireworkParticles$Starter
- XXX.client.particle.FlameParticle
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.FlyStraightTowardsParticle
- XXX.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
+ XXX.client.particle.FlyTowardsPositionParticle
- XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider
+ XXX.client.particle.FlyTowardsPositionParticle$NautilusProvider
- XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.GustParticle
- XXX.client.particle.GustParticle$Provider
+ XXX.client.particle.GustParticle$SmallProvider
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
- XXX.client.particle.MineTravelParticle
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$Provider
- XXX.client.particle.NoRenderParticle
+ XXX.client.particle.NoteParticle
- XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.package-info
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
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobEffectProvider
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
+ XXX.client.particle.SuspendedTownParticle$EggCrackProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$CrumblingProvider
- XXX.client.particle.TerrainParticle$DustPillarProvider
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
- XXX.client.particle.TrailParticle
+ XXX.client.particle.TrailParticle$Provider
- XXX.client.particle.TrialSpawnerDetectionParticle
+ XXX.client.particle.TrialSpawnerDetectionParticle$Provider
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
- XXX.client.particle.WhiteSmokeParticle
+ XXX.client.particle.WhiteSmokeParticle$Provider
+ XXX.client.player.AbstractClientPlayer
- XXX.client.player.ClientInput
+ XXX.client.player.KeyboardInput
- XXX.client.player.LocalPlayer
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.profiling.ClientMetricsSamplersProvider
- XXX.client.profiling.package-info
+ XXX.client.quickplay.package-info
+ XXX.client.quickplay.QuickPlay
- XXX.client.quickplay.QuickPlayLog
+ XXX.client.quickplay.QuickPlayLog$1
- XXX.client.quickplay.QuickPlayLog$QuickPlayEntry
+ XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
- XXX.client.quickplay.QuickPlayLog$Type
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.CloudRenderer
- XXX.client.renderer.CloudRenderer$RelativeCameraPos
+ XXX.client.renderer.CloudRenderer$TextureData
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$SkyType
- XXX.client.renderer.package-info
- XXX.client.renderer.RenderStateShard$SkyTextureStateShard
+ XXX.client.renderer.RenderStateShard$TextureStateShard
- XXX.client.renderer.RenderStateShard$TexturingStateShard
+ XXX.client.renderer.RenderType
- XXX.client.renderer.RenderType$1
- XXX.client.renderer.SkyRenderer$CachedCubeSky
+ XXX.client.renderer.SpecialBlockModelRenderer
- XXX.client.renderer.SpriteCoordinateExpander
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.client.renderer.WeatherEffectRenderer
- XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
+ XXX.client.renderer.WorldBorderRenderer
+ XXX.client.resources.ClientPackSource
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DryFoliageColorReloadListener
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.IndexedAssetSource
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MapDecorationTextureManager
+ XXX.client.resources.MapTextureManager
- XXX.client.resources.MapTextureManager$MapInstance
+ XXX.client.resources.MobEffectTextureManager
- XXX.client.resources.package-info
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.PlayerSkin
- XXX.client.resources.PlayerSkin$Model
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$2
- XXX.client.resources.SkinManager$CacheKey
+ XXX.client.resources.SkinManager$TextureCache
- XXX.client.resources.SplashManager
+ XXX.client.resources.TextureAtlasHolder
+ XXX.client.searchtree.FullTextSearchTree
- XXX.client.searchtree.IdSearchTree
+ XXX.client.searchtree.IntersectionIterator
- XXX.client.searchtree.MergingUniqueIterator
- XXX.client.searchtree.package-info
+ XXX.client.searchtree.ResourceLocationSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree$1
+ XXX.client.searchtree.ResourceLocationSearchTree$2
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
- XXX.client.sounds.ChunkedSampleByteBuf
+ XXX.client.sounds.FiniteAudioStream
- XXX.client.sounds.FloatSampleSource
+ XXX.client.sounds.JOrbisAudioStream
- XXX.client.sounds.LoopingAudioStream
+ XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
- XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
+ XXX.client.sounds.MusicInfo
- XXX.client.sounds.MusicManager
+ XXX.client.sounds.package-info
+ XXX.client.sounds.SoundBufferLibrary
- XXX.client.sounds.SoundEngine
+ XXX.client.sounds.SoundEngine$DeviceCheckState
- XXX.client.sounds.SoundEngineExecutor
+ XXX.client.sounds.SoundEventListener
- XXX.client.sounds.SoundManager
+ XXX.client.sounds.SoundManager$1
- XXX.client.sounds.SoundManager$2
+ XXX.client.sounds.SoundManager$Preparations
- XXX.client.sounds.SoundManager$Preparations$1
+ XXX.client.sounds.WeighedSoundEvents
- XXX.client.sounds.Weighted
- XXX.client.telemetry.ClientTelemetryManager
+ XXX.client.telemetry.package-info
+ XXX.client.telemetry.TelemetryEventInstance
- XXX.client.telemetry.TelemetryEventLog
+ XXX.client.telemetry.TelemetryEventLogger
- XXX.client.telemetry.TelemetryEventSender
+ XXX.client.telemetry.TelemetryEventType
- XXX.client.telemetry.TelemetryEventType$Builder
+ XXX.client.telemetry.TelemetryLogManager
- XXX.client.telemetry.TelemetryProperty
+ XXX.client.telemetry.TelemetryProperty$Exporter
- XXX.client.telemetry.TelemetryProperty$GameMode
+ XXX.client.telemetry.TelemetryProperty$ServerType
- XXX.client.telemetry.TelemetryPropertyMap
+ XXX.client.telemetry.TelemetryPropertyMap$1
- XXX.client.telemetry.TelemetryPropertyMap$Builder
+ XXX.client.telemetry.WorldSessionTelemetryManager
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$CacheData
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.Constant
+ XXX.color.item.CustomModelDataSource
- XXX.color.item.Dye
+ XXX.color.item.Firework
- XXX.color.item.GradeColor
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
- XXX.commands.arguments.MessageArgument
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.package-info
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceArgument
+ XXX.commands.arguments.ResourceArgument$Info
- XXX.commands.arguments.ResourceArgument$Info$Template
+ XXX.commands.arguments.ResourceKeyArgument
- XXX.commands.arguments.ResourceKeyArgument$Info
+ XXX.commands.arguments.ResourceKeyArgument$Info$Template
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ResourceOrIdArgument
- XXX.commands.arguments.ResourceOrIdArgument$LootModifierArgument
+ XXX.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
- XXX.commands.arguments.ResourceOrIdArgument$LootTableArgument
+ XXX.commands.arguments.ResourceOrTagArgument
- XXX.commands.arguments.ResourceOrTagArgument$Info
+ XXX.commands.arguments.ResourceOrTagArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagArgument$ResourceResult
+ XXX.commands.arguments.ResourceOrTagArgument$Result
- XXX.commands.arguments.ResourceOrTagArgument$TagResult
+ XXX.commands.arguments.ResourceOrTagKeyArgument
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Result
- XXX.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ XXX.commands.arguments.ResourceSelectorArgument
- XXX.commands.arguments.ResourceSelectorArgument$Info
+ XXX.commands.arguments.ResourceSelectorArgument$Info$Template
+ XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.SignedArgument
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.SlotsArgument
+ XXX.commands.arguments.StringRepresentableArgument
- XXX.commands.arguments.StyleArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TemplateMirrorArgument
+ XXX.commands.arguments.TemplateRotationArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.TimeArgument$Info
- XXX.commands.arguments.TimeArgument$Info$Template
+ XXX.commands.arguments.UuidArgument
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
- XXX.components.toasts.LevelUpToast
+ XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.RecipeToast$Entry
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastId
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastManager
- XXX.components.toasts.ToastManager$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
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
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractBlockPropertyFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.AreaEffectCloudPotionFix
- XXX.datafix.fixes.AttributeIdPrefixFix
+ XXX.datafix.fixes.AttributeModifierIdFix
- XXX.datafix.fixes.AttributesRenameFix
+ XXX.datafix.fixes.AttributesRenameLegacy
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.BannerPatternFormatFix
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehiveFieldRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
+ XXX.datafix.fixes.BlockPropertyRenameAndFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.BoatSplitFix
+ XXX.datafix.fixes.CarvingStepRemoveFix
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
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkTicketUnpackPosFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.CustomModelDataExpandFix
- XXX.datafix.fixes.DataComponentRemainderFix
+ XXX.datafix.fixes.DecoratedPotFieldRenameFix
- XXX.datafix.fixes.DropChancesFormatFix
+ XXX.datafix.fixes.DropInvalidSignDataFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EffectDurationFix
- XXX.datafix.fixes.EmptyItemInHotbarFix
+ XXX.datafix.fixes.EmptyItemInVillagerTradeFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityAttributeBaseValueFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
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
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.EquipmentFormatFix
- XXX.datafix.fixes.EquippableAssetRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
+ XXX.datafix.fixes.FixProjectileStoredItem
- XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
+ XXX.datafix.fixes.FixWolfHealth
- XXX.datafix.fixes.FoodToConsumableFix
- XXX.datafix.fixes.ForcedChunkToTicketFix
+ XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.InlineBlockPosFormatFix
- XXX.datafix.fixes.InvalidBlockEntityLockFix
+ XXX.datafix.fixes.InvalidLockComponentFix
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
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTagRemainderFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LegacyDragonFightFix
- XXX.datafix.fixes.LegacyHoverEventFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.LockComponentPredicateFix
- XXX.datafix.fixes.LodestoneCompassComponentFix
+ XXX.datafix.fixes.MapBannerBlockPosFormatFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobEffectIdFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityConvertUncheckedFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRarityFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsMenuBlurrinessFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.ParticleUnflatteningFix
- XXX.datafix.fixes.PlayerEquipmentFix
+ XXX.datafix.fixes.PlayerHeadBlockProfileFix
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.PrimedTntBlockStateFixer
- XXX.datafix.fixes.ProjectileStoredWeaponFix
+ XXX.datafix.fixes.RaidRenamesDataFix
- XXX.datafix.fixes.RandomSequenceSettingsFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.References$1
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.RemoveEmptyItemInBrushableBlockFix
- XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.RenameEnchantmentsFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SaddleEquipmentSlotFix
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.ScoreboardDisplayNameFix
+ XXX.datafix.fixes.ScoreboardDisplaySlotFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsCounterFix$StatType
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TextComponentHoverAndClickEventFix
- XXX.datafix.fixes.TextComponentStrictJsonFix
+ XXX.datafix.fixes.TextComponentStringifiedFlagsFix
- XXX.datafix.fixes.ThrownPotionSplitFix
+ XXX.datafix.fixes.ThrownPotionSplitFix$ItemIdFinder
- XXX.datafix.fixes.TippedArrowPotionToItemFix
+ XXX.datafix.fixes.TooltipDisplayComponentFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
+ XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix
- XXX.datafix.fixes.TrialSpawnerConfigInRegistryFix$VanillaTrialChambers
+ XXX.datafix.fixes.UnflattenTextComponentFix
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerSetCanPickUpLootFix
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
+ XXX.datafix.schemas.V1458
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1488
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1925
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2511_1
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
- XXX.datafix.schemas.V3439
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
+ XXX.entity.ai.package-info
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
+ XXX.entity.layers.package-info
- XXX.entity.layers.WolfHeldItemLayer
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.AngryGhast
- XXX.entity.monster.AngryGhast$AngryGhastMoveControl
- XXX.entity.monster.AngryGhast$FloatTowardsPlayerGoal
- XXX.entity.pets.AbstractPet
- XXX.entity.pets.PetArmadillo$1
- XXX.entity.pets.PetAxolotl
- XXX.entity.pets.PetAxolotl$AxolotlGroupData
- XXX.entity.pets.PetAxolotl$AxolotlMoveControl
- XXX.entity.pets.PetBee$1
- XXX.entity.pets.PetBee$BeeBecomeAngryTargetGoal
- XXX.entity.pets.PetBee$BeeLookControl
- XXX.entity.pets.PetChicken
- XXX.entity.pets.PetCreeper
- XXX.entity.pets.PetFox$FoxGroupData
- XXX.entity.pets.PetFox$FoxMoveControl
- XXX.entity.pets.PetFrog$FrogLookControl
- XXX.entity.pets.PetFrog$FrogPathNavigation
- XXX.entity.pets.PetPolarBear
- XXX.entity.pets.PetPolarBear$PolarBearHurtByTargetGoal
- XXX.entity.pets.PetSlime
- XXX.entity.pets.PetSlime$SlimeKeepOnJumpingGoal
- XXX.entity.pets.PetTurtle
- XXX.entity.pets.PetTurtle$TurtleMoveControl
- XXX.entity.pets.PetWolf
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Input
- XXX.entity.player.Input$1
+ XXX.entity.player.Inventory
+ XXX.entity.player.package-info
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerEquipment
+ XXX.entity.player.PlayerModelPart
+ XXX.entity.player.PlayerRenderer
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
+ XXX.entity.state.AllayRenderState
- XXX.entity.state.ArmadilloRenderState
+ XXX.entity.state.ArmedEntityRenderState
- XXX.entity.state.ArmorStandRenderState
+ XXX.entity.state.ArrowRenderState
- XXX.entity.state.AxolotlRenderState
+ XXX.entity.state.BatRenderState
- XXX.entity.state.BeeRenderState
+ XXX.entity.state.BlockDisplayEntityRenderState
- XXX.entity.state.BoatRenderState
+ XXX.entity.state.BoggedRenderState
- XXX.entity.state.BreezeRenderState
+ XXX.entity.state.CamelRenderState
- XXX.entity.state.CatRenderState
+ XXX.entity.state.ChickenRenderState
- XXX.entity.state.CowRenderState
+ XXX.entity.state.CreakingRenderState
- XXX.entity.state.CreeperRenderState
+ XXX.entity.state.DisplayEntityRenderState
- XXX.entity.state.DolphinRenderState
+ XXX.entity.state.DonkeyRenderState
- XXX.entity.state.EndCrystalRenderState
+ XXX.entity.state.EnderDragonRenderState
- XXX.entity.state.EndermanRenderState
+ XXX.entity.state.EntityRenderState
- XXX.entity.state.EntityRenderState$LeashState
+ XXX.entity.state.EquineRenderState
- XXX.entity.state.EvokerFangsRenderState
+ XXX.entity.state.EvokerRenderState
- XXX.entity.state.ExperienceOrbRenderState
+ XXX.entity.state.FallingBlockRenderState
- XXX.entity.state.FelineRenderState
+ XXX.entity.state.FireworkRocketRenderState
- XXX.entity.state.FishingHookRenderState
+ XXX.entity.state.FoxRenderState
- XXX.entity.state.FrogRenderState
+ XXX.entity.state.GhastRenderState
- XXX.entity.state.GoatRenderState
+ XXX.entity.state.GuardianRenderState
+ XXX.entity.state.HitboxesRenderState
- XXX.entity.state.HitboxRenderState
- XXX.entity.state.HoglinRenderState
+ XXX.entity.state.HoldingEntityRenderState
- XXX.entity.state.HorseRenderState
+ XXX.entity.state.HumanoidRenderState
- XXX.entity.state.IllagerRenderState
+ XXX.entity.state.IllusionerRenderState
- XXX.entity.state.IronGolemRenderState
+ XXX.entity.state.ItemClusterRenderState
- XXX.entity.state.ItemDisplayEntityRenderState
+ XXX.entity.state.ItemEntityRenderState
- XXX.entity.state.ItemFrameRenderState
+ XXX.entity.state.LightningBoltRenderState
- XXX.entity.state.LivingEntityRenderState
+ XXX.entity.state.LlamaRenderState
- XXX.entity.state.LlamaSpitRenderState
+ XXX.entity.state.MinecartRenderState
- XXX.entity.state.MinecartTntRenderState
+ XXX.entity.state.MushroomCowRenderState
- XXX.entity.state.package-info
- XXX.entity.state.PaintingRenderState
+ XXX.entity.state.PandaRenderState
- XXX.entity.state.ParrotRenderState
+ XXX.entity.state.PhantomRenderState
+ XXX.entity.state.PiglinRenderState
- XXX.entity.state.PigRenderState
- XXX.entity.state.PlayerRenderState
+ XXX.entity.state.PolarBearRenderState
- XXX.entity.state.PufferfishRenderState
+ XXX.entity.state.RabbitRenderState
- XXX.entity.state.RavagerRenderState
+ XXX.entity.state.SalmonRenderState
- XXX.entity.state.ServerHitboxesRenderState
+ XXX.entity.state.SheepRenderState
- XXX.entity.state.ShulkerBulletRenderState
+ XXX.entity.state.ShulkerRenderState
- XXX.entity.state.SkeletonRenderState
+ XXX.entity.state.SlimeRenderState
- XXX.entity.state.SnifferRenderState
+ XXX.entity.state.SnowGolemRenderState
- XXX.entity.state.SquidRenderState
+ XXX.entity.state.StriderRenderState
- XXX.entity.state.TextDisplayEntityRenderState
+ XXX.entity.state.ThrownItemRenderState
- XXX.entity.state.ThrownTridentRenderState
+ XXX.entity.state.TippableArrowRenderState
- XXX.entity.state.TntRenderState
+ XXX.entity.state.TropicalFishRenderState
- XXX.entity.state.TurtleRenderState
+ XXX.entity.state.VexRenderState
- XXX.entity.state.VillagerDataHolderRenderState
+ XXX.entity.state.VillagerRenderState
- XXX.entity.state.WardenRenderState
+ XXX.entity.state.WitchRenderState
- XXX.entity.state.WitherRenderState
+ XXX.entity.state.WitherSkullRenderState
- XXX.entity.state.WolfRenderState
+ XXX.entity.state.ZombieRenderState
- XXX.entity.state.ZombieVillagerRenderState
+ XXX.entity.state.ZombifiedPiglinRenderState
+ XXX.entity.trialspawner.package-info
+ XXX.entity.trialspawner.PlayerDetector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
+ XXX.entity.trialspawner.TrialSpawner
- XXX.entity.trialspawner.TrialSpawner$FlameParticle
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerConfig$Builder
- XXX.entity.trialspawner.TrialSpawnerConfigs
+ XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
- XXX.entity.trialspawner.TrialSpawnerData
+ XXX.entity.trialspawner.TrialSpawnerState
- XXX.entity.trialspawner.TrialSpawnerState$LightLevel
+ XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
- XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
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
+ XXX.entity.vault.package-info
- XXX.entity.vault.VaultBlockEntity
+ XXX.entity.vault.VaultBlockEntity$Client
- XXX.entity.vault.VaultBlockEntity$Server
+ XXX.entity.vault.VaultClientData
- XXX.entity.vault.VaultConfig
+ XXX.entity.vault.VaultServerData
- XXX.entity.vault.VaultSharedData
+ XXX.entity.vault.VaultState
- XXX.entity.vault.VaultState$1
+ XXX.entity.vault.VaultState$2
- XXX.entity.vault.VaultState$3
+ XXX.entity.vault.VaultState$4
- XXX.entity.vault.VaultState$LightLevel
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
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.CherryFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.package-info
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.AttachedToLeavesDecorator
- XXX.feature.treedecorators.AttachedToLogsDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.CreakingHeartDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.PaleMossDecorator
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
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.BakedGlyph$GlyphInstance
- XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Definition
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
- XXX.font.providers.FreeTypeUtil
+ XXX.font.providers.GlyphProviderDefinition
- XXX.font.providers.GlyphProviderDefinition$Conditional
+ XXX.font.providers.GlyphProviderDefinition$Loader
- XXX.font.providers.GlyphProviderDefinition$Reference
+ XXX.font.providers.GlyphProviderType
- XXX.font.providers.package-info
- XXX.font.providers.ProviderReferenceDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ XXX.font.providers.UnihexProvider
- XXX.font.providers.UnihexProvider$ByteContents
+ XXX.font.providers.UnihexProvider$Definition
- XXX.font.providers.UnihexProvider$Dimensions
+ XXX.font.providers.UnihexProvider$Glyph
- XXX.font.providers.UnihexProvider$Glyph$1
+ XXX.font.providers.UnihexProvider$IntContents
- XXX.font.providers.UnihexProvider$LineData
+ XXX.font.providers.UnihexProvider$OverrideRange
- XXX.font.providers.UnihexProvider$ReaderOutput
+ XXX.font.providers.UnihexProvider$ShortContents
- XXX.geom.builders.CubeDefinition
+ XXX.geom.builders.CubeDeformation
- XXX.geom.builders.CubeListBuilder
+ XXX.geom.builders.LayerDefinition
- XXX.geom.builders.MaterialDefinition
+ XXX.geom.builders.MeshDefinition
- XXX.geom.builders.MeshTransformer
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
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
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.CodepointMap
- XXX.gui.font.CodepointMap$Output
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$BuilderId
+ XXX.gui.font.FontManager$BuilderResult
- XXX.gui.font.FontManager$FontDefinitionFile
+ XXX.gui.font.FontManager$Preparation
- XXX.gui.font.FontManager$UnresolvedBuilderBundle
+ XXX.gui.font.FontOption
- XXX.gui.font.FontOption$Filter
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
+ XXX.gui.font.GlyphRenderTypes
- XXX.gui.font.GlyphRenderTypes$1
+ XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.layouts.AbstractLayout
- XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
+ XXX.gui.layouts.CommonLayouts
- XXX.gui.layouts.EqualSpacingLayout
+ XXX.gui.layouts.EqualSpacingLayout$ChildContainer
- XXX.gui.layouts.EqualSpacingLayout$Orientation
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
+ XXX.gui.navigation.CommonInputs
- XXX.gui.navigation.FocusNavigationEvent
+ XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
- XXX.gui.navigation.FocusNavigationEvent$InitialFocus
+ XXX.gui.navigation.FocusNavigationEvent$TabNavigation
- XXX.gui.navigation.package-info
- XXX.gui.navigation.ScreenAxis
+ XXX.gui.navigation.ScreenDirection
- XXX.gui.navigation.ScreenPosition
+ XXX.gui.navigation.ScreenPosition$1
- XXX.gui.navigation.ScreenRectangle
+ XXX.gui.navigation.ScreenRectangle$1
- XXX.gui.screens.AccessibilityOnboardingScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.BanNoticeScreens
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.ConnectScreen$2
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.CreditsAndAttributionScreen
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DeathScreen$TitleConfirmScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.FaviconTexture
- XXX.gui.screens.GenericMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LevelLoadingScreen
- XXX.gui.screens.LoadingDotsText
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.NoticeWithLinkScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
+ XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PauseScreen$FeedbackSubScreen
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.ReceivingLevelScreen$Reason
- XXX.gui.screens.RecoverWorldDataScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.Screen$DeferredTooltipRendering
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.TitleScreen
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
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SuspiciousStewEffects
- XXX.item.component.SuspiciousStewEffects$Entry
+ XXX.item.component.Tool
- XXX.item.component.Tool$Rule
+ XXX.item.component.TooltipDisplay
- XXX.item.component.TooltipProvider
+ XXX.item.component.UseCooldown
- XXX.item.component.UseRemainder
+ XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.component.Weapon
- XXX.item.properties.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.ClimateSettings$Builder
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$3
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
- XXX.level.block.BaseTorchBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$ShapePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BlockTypes
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BonemealableBlock$Type
+ XXX.level.block.BonemealableFeaturePlacerBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BrushableBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BuddingAmethystBlock
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.CactusBlock
- XXX.level.block.CactusFlowerBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CalibratedSculkSensorBlock
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
+ XXX.level.block.CreakingHeartBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DecoratedPotBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DimensionControlBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.MineCrafterBlock
- XXX.level.block.MineTravellingBlock
+ XXX.level.block.Mirror
- XXX.level.block.MobTrophyBlock
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
- XXX.level.block.package-info
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
- XXX.level.block.ShimmeringDoorBlock
- XXX.level.block.TrophyType
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$DistancePerDirection
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.GridChunkGenerator
- XXX.level.dimension.DimensionSpecialEffects$CodeSky
- XXX.level.dimension.DimensionSpecialEffects$EndSky
- XXX.level.dimension.DimensionSpecialEffects$FogScaler$1
- XXX.level.dimension.DimensionSpecialEffects$FogScaler$3
- XXX.level.dimension.DimensionSpecialEffects$Panorama
- XXX.level.dimension.DimensionSpecialEffects$SkyType
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
+ XXX.level.levelgen.package-info
- XXX.level.mines.Battle
- XXX.level.mines.Battle$SpawnGroup
- XXX.level.mines.Battle$SpawnStrategy
- XXX.level.mines.Battle$SpawnType
- XXX.level.mines.Battle$Wave$Builder
- XXX.level.mines.EndDragonBattle
- XXX.level.mines.MineEvent$Status
- XXX.level.mines.MineSpawnStrategy
- XXX.level.mines.package-info
- XXX.level.mines.RandomizationMode
- XXX.level.mines.SpecialMine$Builder
- XXX.level.mines.UnlockMode
- XXX.level.mines.WorldEffect$Builder
- XXX.level.mines.WorldEffectSet
- XXX.level.mines.WorldGenBuilder
- XXX.level.mines.WorldGenBuilder$ModifiedBiome
- XXX.level.mines.WorldGenEffect
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
- XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Context
- XXX.level.saveddata.SavedDataType
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
- XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
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
- XXX.levelgen.feature.package-info
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
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.NestedLootTable
- XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyComponentsFunction
+ XXX.loot.functions.CopyComponentsFunction$Builder
- XXX.loot.functions.CopyComponentsFunction$Source
+ XXX.loot.functions.CopyCustomDataFunction
- XXX.loot.functions.CopyCustomDataFunction$Builder
+ XXX.loot.functions.CopyCustomDataFunction$CopyOperation
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.EnchantedCountIncreaseFunction
+ XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FilteredFunction
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.ListOperation
- XXX.loot.functions.ListOperation$Append
+ XXX.loot.functions.ListOperation$Insert
- XXX.loot.functions.ListOperation$ReplaceAll
+ XXX.loot.functions.ListOperation$ReplaceSection
- XXX.loot.functions.ListOperation$StandAlone
+ XXX.loot.functions.ListOperation$Type
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.ModifyContainerContents
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
+ XXX.loot.functions.SetCustomModelDataFunction
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetFireworkExplosionFunction
+ XXX.loot.functions.SetFireworksFunction
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
+ XXX.loot.packs.package-info
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
- XXX.loot.parameters.LootContextParams
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
- XXX.loot.predicates.EnchantmentActiveCheck
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.FrameSize
+ XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetadataSection
- XXX.metadata.animation.VillagerMetadataSection$Hat
- XXX.metadata.gui.GuiMetadataSection
+ XXX.metadata.gui.GuiSpriteScaling
- XXX.metadata.gui.GuiSpriteScaling$NineSlice
+ XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border
- XXX.metadata.gui.GuiSpriteScaling$Stretch
+ XXX.metadata.gui.GuiSpriteScaling$Tile
- XXX.metadata.gui.GuiSpriteScaling$Type
+ XXX.metadata.gui.package-info
- XXX.metadata.language.LanguageMetadataSection
+ XXX.metadata.language.package-info
- XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.minecraft.advancements.DisplayInfo$Builder
+ XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.Camera$NearPlane
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBootstrap
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.CommandHistory
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.DeltaTracker
- XXX.minecraft.client.DeltaTracker$DefaultValue
+ XXX.minecraft.client.DeltaTracker$Timer
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GameNarrator$NarratorInitException
- XXX.minecraft.client.GraphicsStatus
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.InactivityFpsLimit
+ XXX.minecraft.client.InputType
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$2
- XXX.minecraft.client.Minecraft$ChatStatus
+ XXX.minecraft.client.Minecraft$ChatStatus$1
- XXX.minecraft.client.Minecraft$ChatStatus$2
+ XXX.minecraft.client.Minecraft$ChatStatus$3
- XXX.minecraft.client.Minecraft$ChatStatus$4
+ XXX.minecraft.client.Minecraft$GameLoadCookie
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
+ XXX.minecraft.client.OptionInstance$UnitDouble
- XXX.minecraft.client.OptionInstance$UnitDouble$1
+ XXX.minecraft.client.OptionInstance$ValueSet
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.Options$3
- XXX.minecraft.client.Options$4
+ XXX.minecraft.client.Options$5
- XXX.minecraft.client.Options$FieldAccess
+ XXX.minecraft.client.Options$OptionAccess
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.PeriodicNotificationManager
+ XXX.minecraft.client.PeriodicNotificationManager$Notification
- XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
+ XXX.minecraft.client.PrioritizeChunkUpdates
- XXX.minecraft.client.ResourceLoadStateTracker
+ XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.ScrollWheelHandler
- XXX.minecraft.client.StringSplitter
+ XXX.minecraft.client.StringSplitter$1
- XXX.minecraft.client.StringSplitter$FlatComponents
+ XXX.minecraft.client.StringSplitter$LineBreakFinder
- XXX.minecraft.client.StringSplitter$LineComponent
+ XXX.minecraft.client.StringSplitter$LinePosConsumer
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
+ XXX.minecraft.client.StringSplitter$WidthProvider
- XXX.minecraft.client.ToggleKeyMapping
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
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
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.package-info
- XXX.minecraft.server.PackStuff
- XXX.minecraft.server.ServerPlayerUnlocks
- XXX.minecraft.server.TheGame$1
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
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
+ XXX.minecraft.util.AbstractListBuilder
- XXX.minecraft.util.ARGB
- XXX.minecraft.util.ArrayListDeque
+ XXX.minecraft.util.ArrayListDeque$DescendingIterator
- XXX.minecraft.util.ArrayListDeque$ReversedView
+ XXX.minecraft.util.BinaryAnimator
- XXX.minecraft.util.BinaryAnimator$EasingFunction
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
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
- XXX.minecraft.util.EncoderCache
+ XXX.minecraft.util.EncoderCache$1
- XXX.minecraft.util.EncoderCache$2
+ XXX.minecraft.util.EncoderCache$Key
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$5
- XXX.minecraft.util.ExtraCodecs$6
+ XXX.minecraft.util.ExtraCodecs$7
- XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
+ XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FileSystemUtil
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.GsonHelper$CountedAppendable
- XXX.minecraft.util.HashOps
+ XXX.minecraft.util.HashOps$ListHashBuilder
- XXX.minecraft.util.HashOps$MapHashBuilder
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.ListAndDeque
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.NullOps
- XXX.minecraft.util.NullOps$NullListBuilder
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$Collector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.ResourceLocationPattern
+ XXX.minecraft.util.SegmentedAnglePrecision
- XXX.minecraft.util.SequencedPriorityIterator
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
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TaskChainer
- XXX.minecraft.util.TaskChainer$1
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TickThrottler
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.util.TriState
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.MineData
- XXX.minecraft.world.package-info
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.EnderDragonModel
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
- XXX.model.geom.package-info
- XXX.model.geom.PartNames
+ XXX.model.geom.PartPose
+ XXX.model.multipart.CombinedCondition
- XXX.model.multipart.CombinedCondition$Operation
+ XXX.model.multipart.CombinedCondition$Operation$1
- XXX.model.multipart.CombinedCondition$Operation$2
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.KeyValueCondition$Term
- XXX.model.multipart.KeyValueCondition$Terms
+ XXX.model.multipart.MultiPartModel
- XXX.model.multipart.MultiPartModel$Selector
+ XXX.model.multipart.MultiPartModel$SharedBakedState
- XXX.model.multipart.MultiPartModel$Unbaked
+ XXX.model.multipart.MultiPartModel$Unbaked$1
- XXX.model.multipart.MultiPartModel$Unbaked$1Key
- XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
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
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
- XXX.options.controls.ControlsScreen
+ XXX.options.controls.KeyBindsList
- XXX.options.controls.KeyBindsList$CategoryEntry
+ XXX.options.controls.KeyBindsList$CategoryEntry$1
- XXX.options.controls.KeyBindsList$Entry
+ XXX.options.controls.KeyBindsList$KeyEntry
- XXX.options.controls.KeyBindsScreen
+ XXX.options.controls.package-info
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
- XXX.phys.shapes.MinecartCollisionContext
+ XXX.phys.shapes.MinecartCollisionContext$1
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
- XXX.pools.alias.DirectPoolAlias
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.RandomGroupPoolAlias
+ XXX.pools.alias.RandomPoolAlias
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
- XXX.properties.conditional.Broken
+ XXX.properties.conditional.BundleHasSelectedItem
- XXX.properties.conditional.ComponentMatches
+ XXX.properties.conditional.ConditionalItemModelProperties
- XXX.properties.conditional.ConditionalItemModelProperty
+ XXX.properties.conditional.CustomModelDataProperty
- XXX.properties.conditional.Damaged
+ XXX.properties.conditional.ExtendedView
- XXX.properties.conditional.FishingRodCast
+ XXX.properties.conditional.HasComponent
- XXX.properties.conditional.IsCarried
+ XXX.properties.conditional.IsKeybindDown
- XXX.properties.conditional.IsSelected
+ XXX.properties.conditional.IsUsingItem
- XXX.properties.conditional.IsViewEntity
+ XXX.properties.conditional.ItemModelPropertyTest
- XXX.properties.conditional.package-info
+ XXX.properties.numeric.BundleFullness
- XXX.properties.numeric.CompassAngle
+ XXX.properties.numeric.CompassAngleState
- XXX.properties.numeric.CompassAngleState$CompassTarget
+ XXX.properties.numeric.CompassAngleState$CompassTarget$1
- XXX.properties.numeric.CompassAngleState$CompassTarget$2
+ XXX.properties.numeric.CompassAngleState$CompassTarget$3
- XXX.properties.numeric.CompassAngleState$CompassTarget$4
+ XXX.properties.numeric.Cooldown
- XXX.properties.numeric.Count
+ XXX.properties.numeric.CrossbowPull
- XXX.properties.numeric.CustomModelDataProperty
+ XXX.properties.numeric.Damage
- XXX.properties.numeric.NeedleDirectionHelper
+ XXX.properties.numeric.NeedleDirectionHelper$1
- XXX.properties.numeric.NeedleDirectionHelper$2
+ XXX.properties.numeric.NeedleDirectionHelper$Wobbler
+ XXX.properties.numeric.package-info
- XXX.properties.numeric.RangeSelectItemModelProperties
+ XXX.properties.numeric.RangeSelectItemModelProperty
- XXX.properties.numeric.Time
+ XXX.properties.numeric.Time$TimeSource
- XXX.properties.numeric.Time$TimeSource$1
+ XXX.properties.numeric.Time$TimeSource$2
- XXX.properties.numeric.Time$TimeSource$3
+ XXX.properties.numeric.UseCycle
- XXX.properties.numeric.UseDuration
+ XXX.properties.select.Charge
- XXX.properties.select.ComponentContents
+ XXX.properties.select.ContextDimension
- XXX.properties.select.ContextEntityType
+ XXX.properties.select.CustomModelDataProperty
- XXX.properties.select.DisplayContext
+ XXX.properties.select.ItemBlockState
- XXX.properties.select.LocalTime
+ XXX.properties.select.LocalTime$Data
- XXX.properties.select.MainHand
+ XXX.properties.select.package-info
+ XXX.properties.select.SelectItemModelProperties
- XXX.properties.select.SelectItemModelProperty
+ XXX.properties.select.SelectItemModelProperty$Type
- XXX.properties.select.TrimMaterialProperty
- XXX.protocol.game.ClientboundChunkBatchFinishedPacket
+ XXX.protocol.game.ClientboundChunkBatchStartPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundDamageEventPacket
+ XXX.protocol.game.ClientboundDebugSamplePacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisguisedChatPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundEntityPositionSyncPacket
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
- XXX.protocol.game.ClientboundMoveMinecartPacket
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundUpdatePlayerUnlocksPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateScreenPacket
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
+ XXX.protocol.game.GameProtocols$1
- XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientTickEndPacket
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
- XXX.protocol.game.ServerboundPickItemFromBlockPacket
+ XXX.protocol.game.ServerboundPickItemFromEntityPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerBuyUnlockPacket
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
- XXX.protocol.game.ServerboundPlayerReactivateUnlockPacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue
- XXX.providers.number.EnchantmentLevelProvider
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.StorageValue
- XXX.providers.number.UniformGenerator
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$Runner
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionRenderStorage
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$CommonRenderStorage
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.AbstractSignRenderer
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BlockEntityRendererProvider
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
- XXX.renderer.blockentity.BlockEntityRenderers
+ XXX.renderer.blockentity.BlockEntityWithBoundingBoxRenderer
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.BrushableBlockRenderer
- XXX.renderer.blockentity.BrushableBlockRenderer$1
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
- XXX.renderer.blockentity.HangingSignRenderer$ModelKey
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.MineTravellingBlockEntityRenderer
+ XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$Models
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SkullBlockRenderer$1
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.TestInstanceRenderer
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.blockentity.TrialSpawnerRenderer
- XXX.renderer.blockentity.VaultRenderer
- XXX.renderer.chunk.CompileTaskDynamicQueue
+ XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunk
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
+ XXX.renderer.chunk.SectionCompiler
- XXX.renderer.chunk.SectionCompiler$Results
+ XXX.renderer.chunk.SectionRenderDispatcher
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection
+ XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$2
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
+ XXX.renderer.chunk.SectionRenderDispatcher$SectionBuffers
- XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
+ XXX.renderer.chunk.SectionRenderDispatcher$TranslucencyPointOfView
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.BeeDebugRenderer
+ XXX.renderer.debug.BeeDebugRenderer$HiveDebugInfo
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BrainDebugRenderer$PoiInfo
- XXX.renderer.debug.BreezeDebugRenderer
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkCullingDebugRenderer
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
+ XXX.renderer.debug.LightSectionDebugRenderer$SectionData
- XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.OctreeDebugRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.RedstoneWireOrientationsRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.SupportBlockRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractBoatRenderer
+ XXX.renderer.entity.AbstractHoglinRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractMinecartRenderer
- XXX.renderer.entity.AbstractSkeletonRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AgeableMobRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.AngryGhastRenderer
- XXX.renderer.entity.package-info
- XXX.renderer.entity.PetAxolotlRenderer
- XXX.renderer.entity.PetCatRenderer
- XXX.renderer.entity.PetCowRenderer
- XXX.renderer.entity.PetFoxRenderer
- XXX.renderer.entity.PetMushroomCowRenderer
- XXX.renderer.entity.PetSlimeRenderer
- XXX.renderer.entity.PetWolfRenderer
+ XXX.renderer.item.BlockModelWrapper
- XXX.renderer.item.BlockModelWrapper$Unbaked
+ XXX.renderer.item.BundleSelectedItemSpecialRenderer
- XXX.renderer.item.BundleSelectedItemSpecialRenderer$Unbaked
+ XXX.renderer.item.ClientItem
- XXX.renderer.item.ClientItem$Properties
+ XXX.renderer.item.CompositeModel
- XXX.renderer.item.CompositeModel$Unbaked
+ XXX.renderer.item.ConditionalItemModel
- XXX.renderer.item.ConditionalItemModel$Unbaked
+ XXX.renderer.item.EmptyModel
- XXX.renderer.item.EmptyModel$Unbaked
+ XXX.renderer.item.ItemModel
- XXX.renderer.item.ItemModel$BakingContext
+ XXX.renderer.item.ItemModel$Unbaked
- XXX.renderer.item.ItemModelResolver
+ XXX.renderer.item.ItemModels
- XXX.renderer.item.ItemStackRenderState
+ XXX.renderer.item.ItemStackRenderState$FoilType
- XXX.renderer.item.ItemStackRenderState$LayerRenderState
- XXX.renderer.item.MineIngredientModel$Unbaked
+ XXX.renderer.item.MissingItemModel
- XXX.renderer.item.ModelRenderProperties
+ XXX.renderer.item.package-info
+ XXX.renderer.item.RangeSelectItemModel
- XXX.renderer.item.RangeSelectItemModel$Entry
+ XXX.renderer.item.RangeSelectItemModel$Unbaked
- XXX.renderer.item.SelectItemModel
+ XXX.renderer.item.SelectItemModel$ModelSelector
- XXX.renderer.item.SelectItemModel$SwitchCase
+ XXX.renderer.item.SelectItemModel$Unbaked
- XXX.renderer.item.SelectItemModel$UnbakedSwitch
+ XXX.renderer.item.SpecialModelWrapper
- XXX.renderer.item.SpecialModelWrapper$Unbaked
+ XXX.renderer.special.BannerSpecialRenderer
- XXX.renderer.special.BannerSpecialRenderer$Unbaked
+ XXX.renderer.special.BedSpecialRenderer
- XXX.renderer.special.BedSpecialRenderer$Unbaked
+ XXX.renderer.special.ChestSpecialRenderer
- XXX.renderer.special.ChestSpecialRenderer$Unbaked
+ XXX.renderer.special.ConduitSpecialRenderer
- XXX.renderer.special.ConduitSpecialRenderer$Unbaked
+ XXX.renderer.special.DecoratedPotSpecialRenderer
- XXX.renderer.special.DecoratedPotSpecialRenderer$Unbaked
+ XXX.renderer.special.HangingSignSpecialRenderer
- XXX.renderer.special.HangingSignSpecialRenderer$Unbaked
- XXX.renderer.special.MobTrophySpecialRenderer$Unbaked
+ XXX.renderer.special.NoDataSpecialModelRenderer
+ XXX.renderer.special.package-info
- XXX.renderer.special.ShieldSpecialRenderer
+ XXX.renderer.special.ShieldSpecialRenderer$Unbaked
- XXX.renderer.special.ShulkerBoxSpecialRenderer
+ XXX.renderer.special.ShulkerBoxSpecialRenderer$Unbaked
- XXX.renderer.special.SkullSpecialRenderer
+ XXX.renderer.special.SkullSpecialRenderer$Unbaked
- XXX.renderer.special.SpecialModelRenderer
+ XXX.renderer.special.SpecialModelRenderer$Unbaked
- XXX.renderer.special.SpecialModelRenderers
+ XXX.renderer.special.StandingSignSpecialRenderer
- XXX.renderer.special.StandingSignSpecialRenderer$Unbaked
+ XXX.renderer.special.TridentSpecialRenderer
- XXX.renderer.special.TridentSpecialRenderer$Unbaked
- XXX.renderer.state.MapRenderState
+ XXX.renderer.state.MapRenderState$MapDecorationRenderState
- XXX.renderer.state.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.Dumpable
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.MipmapGenerator
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
+ XXX.renderer.texture.ReloadableTexture
- XXX.renderer.texture.SimpleTexture
+ XXX.renderer.texture.SkinTextureDownloader
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
- XXX.renderer.texture.TextureContents
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.TextureManager$PendingReload
+ XXX.renderer.texture.Tickable
- XXX.resources.language.ClientLanguage
+ XXX.resources.language.FormattedBidiReorder
- XXX.resources.language.I18n
+ XXX.resources.language.LanguageInfo
- XXX.resources.language.LanguageManager
+ XXX.resources.language.package-info
- XXX.resources.metadata.package-info
+ XXX.resources.model.AtlasIds
- XXX.resources.model.AtlasSet
+ XXX.resources.model.AtlasSet$AtlasEntry
- XXX.resources.model.AtlasSet$StitchResult
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BlockModelRotation$WithUvLock
+ XXX.resources.model.BlockStateDefinitions
- XXX.resources.model.BlockStateModelLoader
+ XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
- XXX.resources.model.BlockStateModelLoader$LoadedModels
+ XXX.resources.model.ClientItemInfoLoader
- XXX.resources.model.ClientItemInfoLoader$LoadedClientInfos
+ XXX.resources.model.ClientItemInfoLoader$PendingLoad
- XXX.resources.model.EquipmentAssetManager
+ XXX.resources.model.EquipmentClientInfo
- XXX.resources.model.EquipmentClientInfo$Builder
+ XXX.resources.model.EquipmentClientInfo$Dyeable
- XXX.resources.model.EquipmentClientInfo$Layer
+ XXX.resources.model.EquipmentClientInfo$LayerType
- XXX.resources.model.Material
+ XXX.resources.model.MissingBlockModel
- XXX.resources.model.ModelBaker
+ XXX.resources.model.ModelBaker$SharedOperationKey
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BakingResult
- XXX.resources.model.ModelBakery$MissingModels
+ XXX.resources.model.ModelBakery$MissingModels$1
- XXX.resources.model.ModelBakery$ModelBakerImpl
+ XXX.resources.model.ModelDebugName
- XXX.resources.model.ModelDiscovery
+ XXX.resources.model.ModelDiscovery$ModelWrapper
- XXX.resources.model.ModelDiscovery$Slot
+ XXX.resources.model.ModelGroupCollector
- XXX.resources.model.ModelGroupCollector$GroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelManager$1
+ XXX.resources.model.ModelManager$ReloadState
- XXX.resources.model.ModelManager$ResolvedModels
+ XXX.resources.model.ModelState
+ XXX.resources.model.package-info
- XXX.resources.model.QuadCollection
+ XXX.resources.model.QuadCollection$Builder
- XXX.resources.model.ResolvableModel
+ XXX.resources.model.ResolvableModel$Resolver
- XXX.resources.model.ResolvedModel
+ XXX.resources.model.SpriteGetter
- XXX.resources.model.UnbakedGeometry
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.UnbakedModel$GuiLight
+ XXX.resources.model.WeightedVariants
- XXX.resources.model.WeightedVariants$Unbaked
+ XXX.resources.server.DownloadedPackSource
- XXX.resources.server.DownloadedPackSource$1
+ XXX.resources.server.DownloadedPackSource$2
- XXX.resources.server.DownloadedPackSource$3
+ XXX.resources.server.DownloadedPackSource$4
- XXX.resources.server.DownloadedPackSource$5
+ XXX.resources.server.DownloadedPackSource$6
- XXX.resources.server.DownloadedPackSource$7
+ XXX.resources.server.DownloadedPackSource$8
- XXX.resources.server.package-info
- XXX.resources.server.PackDownloader
+ XXX.resources.server.PackLoadFeedback
- XXX.resources.server.PackLoadFeedback$FinalResult
+ XXX.resources.server.PackLoadFeedback$Update
- XXX.resources.server.PackReloadConfig
+ XXX.resources.server.PackReloadConfig$Callbacks
- XXX.resources.server.PackReloadConfig$IdAndPath
+ XXX.resources.server.ServerPackManager
- XXX.resources.server.ServerPackManager$1
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
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$Sprites
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.AdvancementWidgetType$1
- XXX.screens.advancements.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AbstractRecipeBookScreen
+ XXX.screens.inventory.AbstractSignEditScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconButton
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CrafterScreen
+ XXX.screens.inventory.CrafterScreen$1
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.CyclingSlotBackground
- XXX.screens.inventory.DoorScreen$DisplayWidget
- XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.inventory.TestBlockEditScreen
+ XXX.screens.inventory.TestInstanceBlockEditScreen
- XXX.screens.inventory.TestInstanceBlockEditScreen$1
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
- XXX.screens.unlocks.package-info
- XXX.screens.unlocks.PlayerUnlocksScreen
- XXX.screens.unlocks.PlayerUnlocksTree
- XXX.screens.unlocks.PlayerUnlockWidget
- XXX.screens.unlocks.RadialLayerLayout
- XXX.screens.unlocks.UnlockTabType
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ XXX.screens.worldselection.CreateWorldCallback
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
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
- XXX.server.commands.FillCommand$Affector
+ XXX.server.commands.FillCommand$Filter
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.FillCommand$NullableCommandFunction
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
+ XXX.server.commands.InCommandFunction
- XXX.server.commands.ItemCommands
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.LevelCommand
- XXX.server.commands.package-info
- XXX.server.commands.RoomCommand
+ XXX.server.commands.RotateCommand
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
- XXX.server.commands.UnlockWorldEffectCommand
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
- XXX.server.level.DimensionGenerator$DimensionPackMetadata
- XXX.server.level.DimensionGenerator$GeneratedDimension
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.GeneratingChunkMap
- XXX.server.level.GenerationChunkHolder
+ XXX.server.level.LoadingChunkTracker
- XXX.server.level.package-info
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerEntityGetter
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$1
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$1$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayer$3
+ XXX.server.level.ServerPlayer$RespawnConfig
- XXX.server.level.ServerPlayer$RespawnPosAngle
+ XXX.server.level.ServerPlayerGameMode
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
- XXX.server.network.ServerLessCommonPacketListenerImpl
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
- XXX.server.packs.GeneratedMarkerMetadataSection
- XXX.server.players.package-info
- XXX.server.players.PetUpgrades
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
- XXX.server.players.PlayerUnlock$Builder
- XXX.server.players.PlayerUnlocks
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
+ XXX.state.properties.CreakingHeartState
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
- XXX.state.properties.package-info
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
- XXX.state.properties.TestBlockMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators
+ XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$2
+ XXX.storage.loot.ContainerComponentManipulators$3
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootParams
+ XXX.storage.loot.LootParams$Builder
- XXX.storage.loot.LootParams$DynamicDrop
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
+ XXX.storage.loot.ValidationContext
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
- XXX.telemetry.events.AggregatedTelemetryEvent
+ XXX.telemetry.events.GameLoadTimesEvent
- XXX.telemetry.events.GameLoadTimesEvent$Measurement
- XXX.telemetry.events.package-info
+ XXX.telemetry.events.PerformanceMetricsEvent
- XXX.telemetry.events.WorldLoadEvent
+ XXX.telemetry.events.WorldLoadEvent$1
- XXX.telemetry.events.WorldLoadTimesEvent
+ XXX.telemetry.events.WorldUnloadEvent
+ XXX.texture.atlas.package-info
- XXX.texture.atlas.SpriteResourceLoader
+ XXX.texture.atlas.SpriteSource
- XXX.texture.atlas.SpriteSource$Output
+ XXX.texture.atlas.SpriteSource$SpriteSupplier
- XXX.texture.atlas.SpriteSourceList
+ XXX.texture.atlas.SpriteSourceList$1
- XXX.texture.atlas.SpriteSources
- XXX.util.context.ContextKey
+ XXX.util.context.ContextKeySet
- XXX.util.context.ContextKeySet$Builder
+ XXX.util.context.ContextMap
- XXX.util.context.ContextMap$Builder
+ XXX.util.context.package-info
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
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
- XXX.warden.Stages.StageMinusOne
- XXX.warden.Stages.StageThree
- XXX.warden.Stages.StageZero
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
- XXX.world.inventory.AbstractContainerMenu$2
- XXX.world.inventory.AbstractCraftingMenu$3
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$2
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
- XXX.world.inventory.DimensionControlMenu$1
- XXX.world.inventory.DoorMenu$1
- XXX.world.inventory.DoorMenu$Layout
- XXX.world.inventory.DoorMenu$Rect
- XXX.world.inventory.GhettoSpline
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
- XXX.world.inventory.MineCraftingHintSlot
- XXX.world.inventory.MineCraftingResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerHubInventory
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
+ XXX.world.item.EnderEyeItem
- XXX.world.item.ExitEyeItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FeatherItem
- XXX.world.item.FireWandItem
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
- XXX.world.item.MobTrophyInfo
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
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
+ XXX.world.level.package-info
- XXX.world.level.UnlockCondition$1
- XXX.world.level.UnlockCondition$11
- XXX.world.level.UnlockCondition$13
- XXX.world.level.UnlockCondition$15
- XXX.world.level.UnlockCondition$17
- XXX.world.level.UnlockCondition$19
- XXX.world.level.UnlockCondition$20
- XXX.world.level.UnlockCondition$4
- XXX.world.level.UnlockCondition$6
- XXX.world.level.UnlockCondition$8
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
+ XXX.world.phys.AABB
- XXX.world.phys.AABB$Builder
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.phys.Vec3$1
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
+ XXX.world.scores.Objective$Packed
- XXX.world.scores.package-info
- XXX.world.scores.PlayerScoreEntry
+ XXX.world.scores.PlayerScores
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.PlayerTeam$Packed
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.Scoreboard$PackedScore
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreboardSaveData$Packed
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
XXX.realmsclient.util.LevelType -1P
```
```
XXX.minecraft.advancements.AdvancementRewards +2M -2M
```
```
XXX.minecraft.advancements.AdvancementType +3M -1M | +1P
```
```
XXX.data.models.BlockModelGenerators +6M -2M
```
```
XXX.data.models.ItemModelGenerators +2M
```
```
XXX.data.models.ItemModelOutput +1P
```
```
XXX.models.model.ModelTemplates +3P
```
```
XXX.client.gui.GuiGraphics +1M | +1P
```
```
XXX.gui.components.SpriteIconButton$Builder +1M | +1P
```
```
XXX.screens.worldselection.CreateWorldScreen$GameTab -1M
```
```
XXX.client.renderer.LevelTargetBundle +2P
```
```
XXX.client.renderer.RenderStateShard +3M -1M | +3P
```
```
XXX.renderer.entity.ChickenRenderer +2M
```
```
XXX.renderer.entity.CowRenderer +2M
```
```
XXX.renderer.entity.EntityRenderDispatcher +1M
```
```
XXX.renderer.entity.PigRenderer +2M
```
```
XXX.data.worldgen.NoiseData -1M
```
```
XXX.worldgen.biome.OverworldBiomes +1M
```
```
XXX.worldgen.features.MiscOverworldFeatures +6P
```
```
XXX.worldgen.features.OreFeatures +1P
```
```
XXX.gametest.framework.GameTestHelper$2 +1M -1M
```
```
XXX.gametest.framework.GameTestMainUtil +2M -1M
```
```
XXX.gametest.framework.GameTestServer +11M -9M | -1P
```
```
XXX.gametest.framework.StructureUtils +2P
```
```
XXX.minecraft.network.Connection +1M
```
```
XXX.network.chat.Style +6M -2M | +2P
```
```
XXX.minecraft.server.ServerScoreboard +1M -1M | +1P -1P
```
```
XXX.minecraft.server.ServerTickRateManager +1M -1M | +1P -1P
```
```
XXX.world.effect.MobEffects +1P
```
```
XXX.world.entity.ExperienceOrb +3M | +1P
```
```
XXX.world.entity.LivingEntity +2M -1M | +1P
```
```
XXX.ai.attributes.Attributes +3P
```
```
XXX.monster.piglin.PiglinAi +1M -1M
```
```
XXX.monster.warden.WardenAi +1M
```
```
XXX.entity.npc.Villager +1M -1M
```
```
XXX.world.inventory.AbstractCraftingMenu$1 +2M -4M | +1P -1P
```
```
XXX.world.inventory.AbstractFurnaceMenu$1 +2M -5M | +2P -3P
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
XXX.world.inventory.InventoryMenu$1 +3M -3M | +1P
```
```
XXX.world.item.ShieldItem +1M
```
```
XXX.world.item.ToolMaterial +2M -1M | +1P
```
```
XXX.item.component.ItemLore +1M -1M
```
```
XXX.item.component.OminousBottleAmplifier +1M -1M
```
```
XXX.item.enchantment.ItemEnchantments +1M -1M
```
```
XXX.world.level.GameRules$BooleanValue +4M -4M
```
```
XXX.world.level.GameRules$Value +1M -1M | +1P -1P
```
```
XXX.world.level.LevelAccessor -1P
```
```
XXX.level.biome.BiomeGenerationSettings +3M
```
```
XXX.level.biome.Biomes +1P
```
```
XXX.level.biome.MobSpawnSettings$Builder +1M
```
```
XXX.level.biome.MultiNoiseBiomeSourceParameterList +6M -3M
```
```
XXX.level.block.TntBlock +1M
```
```
XXX.block.entity.AbstractFurnaceBlockEntity +2P
```
```
XXX.block.entity.BannerPatternLayers +1M -1M
```
```
XXX.level.dimension.DimensionType$MonsterSettings +1M
```
```
XXX.dimension.end.DragonRespawnAnimation +1M
```
```
XXX.dimension.end.EndDragonFight +4M -7M | -1P
```
```
XXX.level.levelgen.Noises -4P
```
```
XXX.level.levelgen.PhantomSpawner +1P
```
```
XXX.level.levelgen.SurfaceRules$NotConditionSource +1M
```

</details>
<details>
<summary>
net.minecraft.advancements.AdvancementRewards
</summary>

```diff
+ Optional lambda$grant$1(MinecraftServer,CacheableFunction)
- Optional lambda$grant$1(ServerFunctionManager,CacheableFunction)
+ void lambda$grant$2(MinecraftServer,ServerPlayer,CommandFunction)
- void lambda$grant$2(ServerFunctionManager,ServerPlayer,CommandFunction)
```

</details>
<details>
<summary>
net.minecraft.advancements.AdvancementType
</summary>

```diff
- Component createAnnouncement(AdvancementHolder,ServerPlayer)
- Component createPlayerUnlockAnnouncement(Holder,ServerPlayer)
+ MutableComponent createAnnouncement(AdvancementHolder,ServerPlayer)
- Style lambda$createPlayerUnlockAnnouncement$0(Component,Style)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.BlockModelGenerators
</summary>

```diff
+ void createCraftingTableLike(Block,Block,BiFunction)
- void createCraftingTableLike(Block,Block,Block,BiFunction)
+ void createEndPortalFrame()
- void createMineCraftingTable()
- void createMobTrophy()
- void createRevisitorBlock()
- void createTrophyBlock()
- void generateFlatTrophy(TrophyType)
```

</details>
<details>
<summary>
net.minecraft.client.data.models.ItemModelGenerators
</summary>

```diff
- void generateLevelIngredient(Item)
- void generateTrophies()
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiGraphics
</summary>

```diff
- DeltaTracker getDeltaTracker()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.SpriteIconButton$Builder
</summary>

```diff
- SpriteIconButton$Builder tooltip(Tooltip)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$GameTab
</summary>

```diff
+ void lambda$new$9(Button)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderStateShard
</summary>

```diff
+ RenderTarget lambda$static$11()
- RenderTarget lambda$static$17()
- RenderTarget lambda$static$18()
- void lambda$static$11()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ChickenRenderer
</summary>

```diff
- ChickenRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
- EntityRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CowRenderer
</summary>

```diff
- CowRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
- EntityRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderDispatcher
</summary>

```diff
- EntityRenderer getRenderer(EntityType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PigRenderer
</summary>

```diff
- EntityRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
- PigRenderState createSpecialRenderStateBecauseImLazyMojangDevAndItsTimeToHack(Level)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.NoiseData
</summary>

```diff
+ void registerBiomeNoises(BootstrapContext,int,ResourceKey,ResourceKey,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.biome.OverworldBiomes
</summary>

```diff
- Biome hub(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper$2
</summary>

```diff
+ void <init>(GameTestHelper,MinecraftServer,ServerLevel,GameProfile,ClientInformation)
- void <init>(GameTestHelper,TheGame,ServerLevel,GameProfile,ClientInformation)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestMainUtil
</summary>

```diff
+ GameTestServer lambda$runGameTestServer$0(LevelStorageSource$LevelStorageAccess,PackRepository,OptionSet,Thread)
- GameTestServer lambda$runGameTestServer$1(LevelStorageSource$LevelStorageAccess,OptionSet,Thread)
- WorldStem lambda$runGameTestServer$0(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ boolean isHardcore()
- boolean isHardcore(TheGame)
+ boolean isTickTimeLoggingEnabled()
+ boolean lambda$evaluateTestsToRun$2(Holder$Reference)
- boolean lambda$evaluateTestsToRun$4(Holder$Reference)
+ CompletableFuture lambda$create$1(WorldLoader$InitConfig,LevelSettings,Executor)
- CompletableFuture lambda$createWorldStem$1(WorldLoader$InitConfig,LevelSettings,Executor)
- GameTestServer create(Thread,LevelStorageSource$LevelStorageAccess,Optional,boolean)
+ GameTestServer create(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,Optional,boolean)
- PlayerList lambda$initGame$2(TheGame)
+ SampleLogger getTickTimeLogger()
- SampleLogger getTickTimeLoggerIfEnabled()
- TheGame initGame(PackRepository,WorldStem,ChunkProgressListenerFactory)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,Optional,boolean)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Optional,boolean)
+ void tickServer(BooleanSupplier)
- void tickServer(TheGame,BooleanSupplier)
+ WorldLoader$DataLoadOutput lambda$create$0(LevelSettings,WorldLoader$DataLoadContext)
- WorldLoader$DataLoadOutput lambda$createWorldStem$0(LevelSettings,WorldLoader$DataLoadContext)
- WorldStem createWorldStem(PackRepository)
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
- void replaceListener(PacketListener)
```

</details>
<details>
<summary>
net.minecraft.network.chat.Style
</summary>

```diff
- boolean isMega()
- Float getScale()
- Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ Style create(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
- Style withMEGA(Boolean)
- Style withScale(Float)
- void <init>(TextColor,Integer,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation,Boolean,Float)
+ void <init>(TextColor,Integer,Boolean,Boolean,Boolean,Boolean,Boolean,ClickEvent,HoverEvent,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.server.ServerScoreboard
</summary>

```diff
- void <init>(Consumer)
+ void <init>(MinecraftServer)
```

</details>
<details>
<summary>
net.minecraft.server.ServerTickRateManager
</summary>

```diff
+ void <init>(MinecraftServer)
- void <init>(TheGame)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
- boolean isOfAge()
- void <init>(Level,Vec3,Vec3,int)
- void awardWithDirection(ServerLevel,Vec3,Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean canJumpInAir()
- ItemEntity drop(ItemStack,boolean,boolean,boolean)
+ ItemEntity drop(ItemStack,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
+ List getBarterResponseItems(Piglin)
- List getBarterResponseItems(ServerLevel,Piglin)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.WardenAi
</summary>

```diff
- void initStageActivity(Brain)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ void lambda$releasePoi$5(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$releasePoi$5(TheGame,MemoryModuleType,GlobalPos)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractCraftingMenu$1
</summary>

```diff
- boolean isActive()
+ boolean recipeMatches(RecipeHolder)
- void <init>(AbstractCraftingMenu,Player,CraftingContainer,Container,int,int,int,Player)
+ void <init>(AbstractCraftingMenu)
+ void clearCraftingContent()
+ void fillCraftSlotsStackedContents(StackedItemContents)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu$1
</summary>

```diff
+ boolean recipeMatches(RecipeHolder)
- void <init>(AbstractFurnaceMenu,Container,int,int,int,Inventory,ContainerData)
+ void <init>(AbstractFurnaceMenu,List,ServerLevel)
+ void clearCraftingContent()
+ void fillCraftSlotsStackedContents(StackedItemContents)
+ void lambda$clearCraftingContent$0(Slot)
- void setByPlayer(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.DispenserMenu
</summary>

```diff
- void <init>(int,Inventory,List)
+ void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.FurnaceMenu
</summary>

```diff
- void <init>(int,Inventory,List)
+ void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
- void <init>(int,Inventory,List)
+ void <init>(int,Inventory)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.InventoryMenu$1
</summary>

```diff
- boolean isActive()
- boolean mayPlace(ItemStack)
+ ResourceLocation getNoItemIcon()
+ void <init>(InventoryMenu,Container,int,int,int,Player)
- void <init>(InventoryMenu,Container,LivingEntity,EquipmentSlot,int,int,int,ResourceLocation,Player,EquipmentSlot)
+ void setByPlayer(ItemStack,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.item.ToolMaterial
</summary>

```diff
- float exchangeValue()
- void <init>(TagKey,int,float,float,int,TagKey,float)
+ void <init>(TagKey,int,float,float,int,TagKey)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.ItemLore
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.OminousBottleAmplifier
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.ItemEnchantments
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$BooleanValue
</summary>

```diff
+ void lambda$create$1(MinecraftServer,GameRules$BooleanValue)
- void lambda$create$1(TheGame,GameRules$BooleanValue)
+ void set(boolean,MinecraftServer)
- void set(boolean,TheGame)
+ void setFrom(GameRules$BooleanValue,MinecraftServer)
- void setFrom(GameRules$BooleanValue,TheGame)
+ void setFrom(GameRules$Value,MinecraftServer)
- void setFrom(GameRules$Value,TheGame)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules$Value
</summary>

```diff
+ void onChanged(MinecraftServer)
- void onChanged(TheGame)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings
</summary>

```diff
- BiomeGenerationSettings$PlainBuilder asBuilder()
- boolean equals(Object)
- int hashCode()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$Builder
</summary>

```diff
- MobSpawnSettings$Builder clearSpawns(MobCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
</summary>

```diff
- boolean lambda$new$3(List,Pair)
+ Climate$ParameterList lambda$knownPresets$4(MultiNoiseBiomeSourceParameterList$Preset)
- Climate$ParameterList lambda$knownPresets$6(MultiNoiseBiomeSourceParameterList$Preset)
- Holder lambda$new$2(Map,HolderGetter,ResourceKey)
+ MultiNoiseBiomeSourceParameterList$Preset lambda$knownPresets$2(MultiNoiseBiomeSourceParameterList$Preset)
- MultiNoiseBiomeSourceParameterList$Preset lambda$knownPresets$4(MultiNoiseBiomeSourceParameterList$Preset)
+ ResourceKey lambda$knownPresets$3(ResourceKey)
- ResourceKey lambda$knownPresets$5(ResourceKey)
- void <init>(List,Map,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
- boolean prime(Level,BlockPos,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerPatternLayers
</summary>

```diff
+ void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,DataComponentGetter)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag,Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.DimensionType$MonsterSettings
</summary>

```diff
- DimensionType$MonsterSettings asPiglinSafe()
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.end.DragonRespawnAnimation
</summary>

```diff
- BlockPos getPosAbovePortal(EndDragonFight)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.end.EndDragonFight
</summary>

```diff
- BlockPos spawnExitPortal(boolean)
- boolean lambda$setDragonKilled$0(MineEvent)
- EndDragonBattle lambda$setDragonKilled$1(MineEvent)
+ List lambda$new$0(long)
+ Optional lambda$spawnNewGateway$1(Registry)
- void forceRespawn()
+ void lambda$spawnNewGateway$2(BlockPos,Holder$Reference)
+ void removeAllGateways()
+ void spawnExitPortal(boolean)
+ void spawnNewGateway()
+ void spawnNewGateway(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
</summary>

```diff
- SurfaceRules$ConditionSource mapBiomes(Map)
```

</details>
</details>
<hr/>