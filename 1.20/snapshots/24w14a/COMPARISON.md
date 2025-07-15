## Comparison with [24w14potato](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w14potato)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
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
<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>DataPack version</td><td><pre>36</pre></td><td><pre>38</pre></td></tr><tr><td>ResourcePack version</td><td><pre>30</pre></td><td><pre>31</pre></td></tr><tr><td>World version</td><td><pre>3824</pre></td><td><pre>3827</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742007</pre></td><td><pre>1073742008</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ org.lwjgl:lwjgl-freetype (natives-macos-patch) V3.3.3
- org.lwjgl:lwjgl-freetype (natives-macos) V3.3.2
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>6.0.12</pre></td><td><pre>7.0.13</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-freetype (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-linux)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-macos-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-arm64)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr><tr><td>org.lwjgl:lwjgl (natives-windows-x86)</td><td><pre>3.3.2</pre></td><td><pre>3.3.3</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
armor_material
</summary>

```diff
- minecraft:potato
```

</details>
<details>
<summary>
block
</summary>

```diff
- minecraft:amber_block
- minecraft:baked_potato_brick_slab
- minecraft:baked_potato_brick_stairs
- minecraft:baked_potato_brick_wall
- minecraft:baked_potato_bricks
- minecraft:big_brain
- minecraft:black_potato_peels_block
- minecraft:blue_potato_peels_block
- minecraft:brown_potato_peels_block
- minecraft:charred_baked_potato_brick_slab
- minecraft:charred_baked_potato_brick_stairs
- minecraft:charred_baked_potato_brick_wall
- minecraft:charred_baked_potato_bricks
- minecraft:compressed_poisonous_potato_block
- minecraft:corrupted_peelgrass_block
- minecraft:corrupted_potato_peels_block
- minecraft:cyan_potato_peels_block
- minecraft:deepslate_poisonous_potato_ore
- minecraft:double_compressed_poisonous_potato_block
- minecraft:expired_baked_potato_brick_slab
- minecraft:expired_baked_potato_brick_stairs
- minecraft:expired_baked_potato_brick_wall
- minecraft:expired_baked_potato_bricks
- minecraft:floatater
- minecraft:floatato
- minecraft:frying_table
- minecraft:gravtater
- minecraft:gray_potato_peels_block
- minecraft:green_potato_peels_block
- minecraft:light_blue_potato_peels_block
- minecraft:light_gray_potato_peels_block
- minecraft:lime_potato_peels_block
- minecraft:magenta_potato_peels_block
- minecraft:orange_potato_peels_block
- minecraft:pedestal
- minecraft:peelgrass_block
- minecraft:pink_potato_peels_block
- minecraft:poison_farmland
- minecraft:poison_path
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_potato_block
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_ore
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:potato_battery
- minecraft:potato_bud
- minecraft:potato_button
- minecraft:potato_door
- minecraft:potato_fence
- minecraft:potato_fence_gate
- minecraft:potato_flower
- minecraft:potato_fruit
- minecraft:potato_hanging_sign
- minecraft:potato_leaves
- minecraft:potato_pedicule
- minecraft:potato_peels_block
- minecraft:potato_planks
- minecraft:potato_portal
- minecraft:potato_pressure_plate
- minecraft:potato_refinery
- minecraft:potato_sign
- minecraft:potato_slab
- minecraft:potato_sprouts
- minecraft:potato_stairs
- minecraft:potato_stem
- minecraft:potato_trapdoor
- minecraft:potato_wall_hanging_sign
- minecraft:potato_wall_sign
- minecraft:potone
- minecraft:potone_copper_ore
- minecraft:potone_diamond_ore
- minecraft:potone_gold_ore
- minecraft:potone_iron_ore
- minecraft:potone_lapis_ore
- minecraft:potone_redstone_ore
- minecraft:potone_slab
- minecraft:potone_stairs
- minecraft:potone_wall
- minecraft:potted_potato_flower
- minecraft:powerful_potato
- minecraft:purple_potato_peels_block
- minecraft:quadruple_compressed_poisonous_potato_block
- minecraft:red_potato_peels_block
- minecraft:resin_ore
- minecraft:strong_roots
- minecraft:taterstone
- minecraft:taterstone_slab
- minecraft:taterstone_stairs
- minecraft:taterstone_wall
- minecraft:terredepomme
- minecraft:triple_compressed_poisonous_potato_block
- minecraft:vicious_potato
- minecraft:weak_roots
- minecraft:yellow_potato_peels_block
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
- minecraft:big_brain
- minecraft:fletching
- minecraft:potato_refinery
```

</details>
<details>
<summary>
block_type
</summary>

```diff
- minecraft:big_brain
- minecraft:corrupted_potato_peels
- minecraft:drop_experience_transparent
- minecraft:floatater
- minecraft:pedestal
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:potato_battery
- minecraft:potato_peels
- minecraft:potato_portal
- minecraft:potato_refinery
- minecraft:potato_sprouts
- minecraft:powerful_potato
- minecraft:strong_roots
- minecraft:vicious_potato
- minecraft:weak_roots
```

</details>
<details>
<summary>
creative_mode_tab
</summary>

```diff
- minecraft:potatoes
```

</details>
<details>
<summary>
custom_stat
</summary>

```diff
- minecraft:get_peeled
- minecraft:interact_with_fletching
- minecraft:potato_quest_time
- minecraft:said_potato
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
- minecraft:clicks
- minecraft:contacts_messages
- minecraft:explicit_foil
- minecraft:fletching
- minecraft:heat
- minecraft:hovered
+ minecraft:item_name
- minecraft:lubrication
+ minecraft:ominous_bottle_amplifier
- minecraft:potato_bane
- minecraft:resin
- minecraft:secret_message
- minecraft:snek
- minecraft:undercover_id
- minecraft:views
- minecraft:xp
```

</details>
<details>
<summary>
enchantment
</summary>

```diff
+ minecraft:breach
+ minecraft:density
- minecraft:potatofication
+ minecraft:wind_burst
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
- minecraft:potato
+ minecraft:raider
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:batato
- minecraft:eye_of_potato
- minecraft:grid_carrier
- minecraft:lashing_potato_hook
- minecraft:mega_spud
+ minecraft:ominous_item_spawner
- minecraft:plaguewhale
- minecraft:poisonous_potato_zombie
- minecraft:toxifin
- minecraft:vine_projectile
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:amber_block
- minecraft:amber_gem
- minecraft:baked_potato_brick_slab
- minecraft:baked_potato_brick_stairs
- minecraft:baked_potato_brick_wall
- minecraft:baked_potato_bricks
- minecraft:batato_spawn_egg
- minecraft:big_brain
- minecraft:black_potato_peels
- minecraft:black_potato_peels_block
- minecraft:blue_potato_peels
- minecraft:blue_potato_peels_block
- minecraft:brown_potato_peels
- minecraft:brown_potato_peels_block
- minecraft:charred_baked_potato_brick_slab
- minecraft:charred_baked_potato_brick_stairs
- minecraft:charred_baked_potato_brick_wall
- minecraft:charred_baked_potato_bricks
- minecraft:compressed_poisonous_potato_block
- minecraft:corrupted_peelgrass_block
- minecraft:corrupted_potato_peels
- minecraft:corrupted_potato_peels_block
- minecraft:cyan_potato_peels
- minecraft:cyan_potato_peels_block
- minecraft:deepslate_poisonous_potato_ore
- minecraft:dent
- minecraft:double_compressed_poisonous_potato_block
- minecraft:enchanted_golden_poisonous_potato
- minecraft:expired_baked_potato_brick_slab
- minecraft:expired_baked_potato_brick_stairs
- minecraft:expired_baked_potato_brick_wall
- minecraft:expired_baked_potato_bricks
- minecraft:floatater
- minecraft:floatato
- minecraft:frying_table
- minecraft:golden_poisonous_potato
- minecraft:gravtater
- minecraft:gray_potato_peels
- minecraft:gray_potato_peels_block
- minecraft:green_potato_peels
- minecraft:green_potato_peels_block
- minecraft:hash_browns
- minecraft:hot_potato
- minecraft:lashing_potato
- minecraft:light_blue_potato_peels
- minecraft:light_blue_potato_peels_block
- minecraft:light_gray_potato_peels
- minecraft:light_gray_potato_peels_block
- minecraft:lime_potato_peels
- minecraft:lime_potato_peels_block
- minecraft:magenta_potato_peels
- minecraft:magenta_potato_peels_block
- minecraft:mega_spud_spawn_egg
+ minecraft:ominous_bottle
+ minecraft:ominous_trial_key
- minecraft:orange_potato_peels
- minecraft:orange_potato_peels_block
- minecraft:pedestal
- minecraft:peelgrass_block
- minecraft:pink_potato_peels
- minecraft:pink_potato_peels_block
- minecraft:plaguewhale_spawn_egg
- minecraft:poison_farmland
- minecraft:poison_path
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_polytra
- minecraft:poisonous_pota_toes
- minecraft:poisonous_potato_block
- minecraft:poisonous_potato_chestplate
- minecraft:poisonous_potato_chips
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_fries
- minecraft:poisonous_potato_oil
- minecraft:poisonous_potato_ore
- minecraft:poisonous_potato_plant
- minecraft:poisonous_potato_slices
- minecraft:poisonous_potato_sticks
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:poisonous_potato_zombie_spawn_egg
- minecraft:potato_battery
- minecraft:potato_bud
- minecraft:potato_button
- minecraft:potato_door
- minecraft:potato_eye
- minecraft:potato_fence
- minecraft:potato_fence_gate
- minecraft:potato_flower
- minecraft:potato_fruit
- minecraft:potato_hammer
- minecraft:potato_hanging_sign
- minecraft:potato_leaves
- minecraft:potato_of_knowledge
- minecraft:potato_oil
- minecraft:potato_pedicule
- minecraft:potato_peeler
- minecraft:potato_peels
- minecraft:potato_peels_block
- minecraft:potato_planks
- minecraft:potato_portal
- minecraft:potato_pressure_plate
- minecraft:potato_refinery
- minecraft:potato_sign
- minecraft:potato_slab
- minecraft:potato_sprouts
- minecraft:potato_staff
- minecraft:potato_stairs
- minecraft:potato_stem
- minecraft:potato_trapdoor
- minecraft:potone
- minecraft:potone_copper_ore
- minecraft:potone_diamond_ore
- minecraft:potone_gold_ore
- minecraft:potone_iron_ore
- minecraft:potone_lapis_ore
- minecraft:potone_redstone_ore
- minecraft:potone_slab
- minecraft:potone_stairs
- minecraft:potone_wall
- minecraft:powerful_potato
- minecraft:purple_potato_peels
- minecraft:purple_potato_peels_block
- minecraft:quadruple_compressed_poisonous_potato_block
- minecraft:red_potato_peels
- minecraft:red_potato_peels_block
- minecraft:resin_ore
- minecraft:snektato
- minecraft:strong_roots
- minecraft:taterstone
- minecraft:taterstone_slab
- minecraft:taterstone_stairs
- minecraft:taterstone_wall
- minecraft:terredepomme
- minecraft:toxic_beam
- minecraft:toxic_resin
- minecraft:toxifin_spawn_egg
- minecraft:triple_compressed_poisonous_potato_block
- minecraft:vicious_potato
- minecraft:weak_roots
- minecraft:yellow_potato_peels
- minecraft:yellow_potato_peels_block
```

</details>
<details>
<summary>
loot_condition_type
</summary>

```diff
- minecraft:killer_main_hand_tool
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
+ minecraft:set_ominous_bottle_amplifier
```

</details>
<details>
<summary>
menu
</summary>

```diff
- minecraft:fletching
- minecraft:poisonous_potato_cutter
- minecraft:potato_refinery
```

</details>
<details>
<summary>
mob_effect
</summary>

```diff
+ minecraft:infested
+ minecraft:oozing
- minecraft:potato_oil
+ minecraft:raid_omen
- minecraft:sticky
+ minecraft:trial_omen
+ minecraft:weaving
+ minecraft:wind_charged
```

</details>
<details>
<summary>
painting_variant
</summary>

```diff
- minecraft:abstractato
- minecraft:burning_potato
- minecraft:ceci
- minecraft:mr_potato
- minecraft:poisonous_potato
- minecraft:potatoe
- minecraft:ubiquitato
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:dust_pillar
- minecraft:falling_poison
- minecraft:footstep
+ minecraft:infested
+ minecraft:item_cobweb
- minecraft:lightning
+ minecraft:ominous_spawning
+ minecraft:raid_omen
- minecraft:reverse_lightning
+ minecraft:small_gust
+ minecraft:trial_omen
+ minecraft:trial_spawner_detection_ominous
```

</details>
<details>
<summary>
point_of_interest_type
</summary>

```diff
- minecraft:pedestal
- minecraft:potato_portal
```

</details>
<details>
<summary>
potion
</summary>

```diff
+ minecraft:infested
+ minecraft:oozing
- minecraft:poisonous_potato_oil
- minecraft:potato_oil
- minecraft:sticky
+ minecraft:weaving
+ minecraft:wind_charged
```

</details>
<details>
<summary>
recipe_serializer
</summary>

```diff
- minecraft:poisonous_potato_cutting
- minecraft:potato_refinement
```

</details>
<details>
<summary>
recipe_type
</summary>

```diff
- minecraft:poisonous_potato_cutting
- minecraft:potato_refinement
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.cobweb.break
+ minecraft:block.cobweb.fall
+ minecraft:block.cobweb.hit
+ minecraft:block.cobweb.place
+ minecraft:block.cobweb.step
+ minecraft:block.trial_spawner.about_to_spawn_item
+ minecraft:block.trial_spawner.ambient_charged
+ minecraft:block.trial_spawner.charge_activate
+ minecraft:block.trial_spawner.spawn_item
+ minecraft:block.trial_spawner.spawn_item_begin
+ minecraft:event.mob_effect.bad_omen
+ minecraft:event.mob_effect.raid_omen
+ minecraft:event.mob_effect.trial_omen
+ minecraft:item.ominous_bottle.dispose
- nothingtoseeheremovealong:ambient.arboretum.loop
- nothingtoseeheremovealong:ambient.corruption.loop
- nothingtoseeheremovealong:ambient.fields.loop
- nothingtoseeheremovealong:ambient.hash.loop
- nothingtoseeheremovealong:ambient.wasteland.loop
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.break
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.fall
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.hit
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.place
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.step
- nothingtoseeheremovealong:block.gravtater.break
- nothingtoseeheremovealong:block.gravtater.fall
- nothingtoseeheremovealong:block.gravtater.hit
- nothingtoseeheremovealong:block.gravtater.place
- nothingtoseeheremovealong:block.gravtater.step
- nothingtoseeheremovealong:block.peelgrass_block.break
- nothingtoseeheremovealong:block.peelgrass_block.fall
- nothingtoseeheremovealong:block.peelgrass_block.hit
- nothingtoseeheremovealong:block.peelgrass_block.place
- nothingtoseeheremovealong:block.peelgrass_block.step
- nothingtoseeheremovealong:block.potato_battery.zap
- nothingtoseeheremovealong:block.potone.break
- nothingtoseeheremovealong:block.potone.fall
- nothingtoseeheremovealong:block.potone.hit
- nothingtoseeheremovealong:block.potone.place
- nothingtoseeheremovealong:block.potone.step
- nothingtoseeheremovealong:block.terredepomme.break
- nothingtoseeheremovealong:block.terredepomme.fall
- nothingtoseeheremovealong:block.terredepomme.hit
- nothingtoseeheremovealong:block.terredepomme.place
- nothingtoseeheremovealong:block.terredepomme.step
- nothingtoseeheremovealong:entity.megaspud.challenge
- nothingtoseeheremovealong:entity.megaspud.death
- nothingtoseeheremovealong:entity.megaspud.fireball
- nothingtoseeheremovealong:entity.megaspud.hurt
- nothingtoseeheremovealong:entity.megaspud.idle
- nothingtoseeheremovealong:entity.megaspud.jump
- nothingtoseeheremovealong:entity.megaspud.jump_hi
- nothingtoseeheremovealong:entity.megaspud.summon
- nothingtoseeheremovealong:entity.megaspud.upset
- nothingtoseeheremovealong:entity.plaguewhale.ambient
- nothingtoseeheremovealong:entity.plaguewhale.ambient_land
- nothingtoseeheremovealong:entity.plaguewhale.death
- nothingtoseeheremovealong:entity.plaguewhale.death_land
- nothingtoseeheremovealong:entity.plaguewhale.flop
- nothingtoseeheremovealong:entity.plaguewhale.hurt
- nothingtoseeheremovealong:entity.plaguewhale.hurt_land
- nothingtoseeheremovealong:entity.player.sprout_respawn
- nothingtoseeheremovealong:entity.player.sprout_respawn_one
- nothingtoseeheremovealong:entity.player.sprout_respawn_two
- nothingtoseeheremovealong:entity.potato.chips
- nothingtoseeheremovealong:entity.potato.peel
- nothingtoseeheremovealong:entity.toxifin.ambient
- nothingtoseeheremovealong:entity.toxifin.ambient_land
- nothingtoseeheremovealong:entity.toxifin.attack
- nothingtoseeheremovealong:entity.toxifin.death
- nothingtoseeheremovealong:entity.toxifin.death_land
- nothingtoseeheremovealong:entity.toxifin.flop
- nothingtoseeheremovealong:entity.toxifin.hurt
- nothingtoseeheremovealong:entity.toxifin.hurt_land
- nothingtoseeheremovealong:entity.zombie_potato.ambient
- nothingtoseeheremovealong:entity.zombie_potato.attack_iron_door
- nothingtoseeheremovealong:entity.zombie_potato.death
- nothingtoseeheremovealong:entity.zombie_potato.hurt
- nothingtoseeheremovealong:entity.zombie_potato.infect
- nothingtoseeheremovealong:entity.zombie_potato.step
- nothingtoseeheremovealong:intentionally_empty
- nothingtoseeheremovealong:ooof
- nothingtoseeheremovealong:the_joke
```

</details>
<details>
<summary>
trigger_type
</summary>

```diff
- minecraft:bring_home_corruption
- minecraft:compost_staff
- minecraft:eat_armor
- minecraft:get_peeled
- minecraft:peel_block
- minecraft:peel_potato_armor
- minecraft:peel_potato_sheep
- minecraft:potato_refined
- minecraft:rumble_plant
- minecraft:said_potato
- minecraft:throw_lubricated
```

</details>
<details>
<summary>
villager_type
</summary>

```diff
- minecraft:potato
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:cloud
- minecraft:hash_well
- minecraft:park_lane
- minecraft:park_lane_surface
- minecraft:potato_buds
- minecraft:potato_field
- minecraft:twisted_potato
```

</details>
<details>
<summary>
worldgen/placement_modifier_type
</summary>

```diff
- minecraft:cloud
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
- minecraft:pedestal
- minecraft:potato_portal
- minecraft:potato_wall_hanging_sign
- minecraft:potato_wall_sign
- minecraft:strong_roots
- minecraft:weak_roots
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:amber_block
- minecraft:baked_potato_brick_slab
- minecraft:baked_potato_brick_stairs
- minecraft:baked_potato_brick_wall
- minecraft:baked_potato_bricks
- minecraft:big_brain
- minecraft:black_potato_peels_block
- minecraft:blue_potato_peels_block
- minecraft:brown_potato_peels_block
- minecraft:charred_baked_potato_brick_slab
- minecraft:charred_baked_potato_brick_stairs
- minecraft:charred_baked_potato_brick_wall
- minecraft:charred_baked_potato_bricks
- minecraft:compressed_poisonous_potato_block
- minecraft:corrupted_peelgrass_block
- minecraft:corrupted_potato_peels_block
- minecraft:cyan_potato_peels_block
- minecraft:deepslate_poisonous_potato_ore
- minecraft:double_compressed_poisonous_potato_block
- minecraft:expired_baked_potato_brick_slab
- minecraft:expired_baked_potato_brick_stairs
- minecraft:expired_baked_potato_brick_wall
- minecraft:expired_baked_potato_bricks
- minecraft:floatater
- minecraft:floatato
- minecraft:frying_table
- minecraft:gravtater
- minecraft:gray_potato_peels_block
- minecraft:green_potato_peels_block
- minecraft:light_blue_potato_peels_block
- minecraft:light_gray_potato_peels_block
- minecraft:lime_potato_peels_block
- minecraft:magenta_potato_peels_block
- minecraft:orange_potato_peels_block
- minecraft:peelgrass_block
- minecraft:pink_potato_peels_block
- minecraft:poison_farmland
- minecraft:poison_path
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_potato_block
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_ore
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:potato_battery
- minecraft:potato_bud
- minecraft:potato_button
- minecraft:potato_door
- minecraft:potato_fence
- minecraft:potato_fence_gate
- minecraft:potato_flower
- minecraft:potato_fruit
- minecraft:potato_hanging_sign
- minecraft:potato_leaves
- minecraft:potato_pedicule
- minecraft:potato_peels_block
- minecraft:potato_planks
- minecraft:potato_pressure_plate
- minecraft:potato_refinery
- minecraft:potato_sign
- minecraft:potato_slab
- minecraft:potato_sprouts
- minecraft:potato_stairs
- minecraft:potato_stem
- minecraft:potato_trapdoor
- minecraft:potone
- minecraft:potone_copper_ore
- minecraft:potone_diamond_ore
- minecraft:potone_gold_ore
- minecraft:potone_iron_ore
- minecraft:potone_lapis_ore
- minecraft:potone_redstone_ore
- minecraft:potone_slab
- minecraft:potone_stairs
- minecraft:potone_wall
- minecraft:potted_potato_flower
- minecraft:powerful_potato
- minecraft:purple_potato_peels_block
- minecraft:quadruple_compressed_poisonous_potato_block
- minecraft:red_potato_peels_block
- minecraft:resin_ore
- minecraft:taterstone
- minecraft:taterstone_slab
- minecraft:taterstone_stairs
- minecraft:taterstone_wall
- minecraft:terredepomme
- minecraft:triple_compressed_poisonous_potato_block
- minecraft:vicious_potato
- minecraft:yellow_potato_peels_block
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:bee
+ minecraft:bogged
- minecraft:eye_of_potato
- minecraft:grid_carrier
- minecraft:lashing_potato_hook
+ minecraft:ominous_item_spawner
- minecraft:vine_projectile
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:batato
- minecraft:bee
- minecraft:bogged
- minecraft:mega_spud
- minecraft:plaguewhale
- minecraft:poisonous_potato_zombie
- minecraft:toxifin
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:bee
+ minecraft:bogged
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
- minecraft:pedestal
- minecraft:potato_portal
- minecraft:strong_roots
- minecraft:weak_roots
```

</details>
<details>
<summary>
universal_tags/armor_material.json
</summary>

```diff
- minecraft:potato
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:amber_block
- minecraft:baked_potato_brick_slab
- minecraft:baked_potato_brick_stairs
- minecraft:baked_potato_brick_wall
- minecraft:baked_potato_bricks
- minecraft:big_brain
- minecraft:black_potato_peels_block
- minecraft:blue_potato_peels_block
- minecraft:brown_potato_peels_block
- minecraft:charred_baked_potato_brick_slab
- minecraft:charred_baked_potato_brick_stairs
- minecraft:charred_baked_potato_brick_wall
- minecraft:charred_baked_potato_bricks
- minecraft:compressed_poisonous_potato_block
- minecraft:corrupted_peelgrass_block
- minecraft:corrupted_potato_peels_block
- minecraft:cyan_potato_peels_block
- minecraft:deepslate_poisonous_potato_ore
- minecraft:double_compressed_poisonous_potato_block
- minecraft:expired_baked_potato_brick_slab
- minecraft:expired_baked_potato_brick_stairs
- minecraft:expired_baked_potato_brick_wall
- minecraft:expired_baked_potato_bricks
- minecraft:floatater
- minecraft:floatato
- minecraft:frying_table
- minecraft:gravtater
- minecraft:gray_potato_peels_block
- minecraft:green_potato_peels_block
- minecraft:light_blue_potato_peels_block
- minecraft:light_gray_potato_peels_block
- minecraft:lime_potato_peels_block
- minecraft:magenta_potato_peels_block
- minecraft:orange_potato_peels_block
- minecraft:pedestal
- minecraft:peelgrass_block
- minecraft:pink_potato_peels_block
- minecraft:poison_farmland
- minecraft:poison_path
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_potato_block
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_ore
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:potato_battery
- minecraft:potato_bud
- minecraft:potato_button
- minecraft:potato_door
- minecraft:potato_fence
- minecraft:potato_fence_gate
- minecraft:potato_flower
- minecraft:potato_fruit
- minecraft:potato_hanging_sign
- minecraft:potato_leaves
- minecraft:potato_pedicule
- minecraft:potato_peels_block
- minecraft:potato_planks
- minecraft:potato_portal
- minecraft:potato_pressure_plate
- minecraft:potato_refinery
- minecraft:potato_sign
- minecraft:potato_slab
- minecraft:potato_sprouts
- minecraft:potato_stairs
- minecraft:potato_stem
- minecraft:potato_trapdoor
- minecraft:potato_wall_hanging_sign
- minecraft:potato_wall_sign
- minecraft:potone
- minecraft:potone_copper_ore
- minecraft:potone_diamond_ore
- minecraft:potone_gold_ore
- minecraft:potone_iron_ore
- minecraft:potone_lapis_ore
- minecraft:potone_redstone_ore
- minecraft:potone_slab
- minecraft:potone_stairs
- minecraft:potone_wall
- minecraft:potted_potato_flower
- minecraft:powerful_potato
- minecraft:purple_potato_peels_block
- minecraft:quadruple_compressed_poisonous_potato_block
- minecraft:red_potato_peels_block
- minecraft:resin_ore
- minecraft:strong_roots
- minecraft:taterstone
- minecraft:taterstone_slab
- minecraft:taterstone_stairs
- minecraft:taterstone_wall
- minecraft:terredepomme
- minecraft:triple_compressed_poisonous_potato_block
- minecraft:vicious_potato
- minecraft:weak_roots
- minecraft:yellow_potato_peels_block
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
- minecraft:big_brain
- minecraft:fletching
- minecraft:potato_refinery
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
- minecraft:big_brain
- minecraft:corrupted_potato_peels
- minecraft:drop_experience_transparent
- minecraft:floatater
- minecraft:pedestal
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:potato_battery
- minecraft:potato_peels
- minecraft:potato_portal
- minecraft:potato_refinery
- minecraft:potato_sprouts
- minecraft:powerful_potato
- minecraft:strong_roots
- minecraft:vicious_potato
- minecraft:weak_roots
```

</details>
<details>
<summary>
universal_tags/creative_mode_tab.json
</summary>

```diff
- minecraft:potatoes
```

</details>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
- minecraft:get_peeled
- minecraft:interact_with_fletching
- minecraft:potato_quest_time
- minecraft:said_potato
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
- minecraft:clicks
- minecraft:contacts_messages
- minecraft:explicit_foil
- minecraft:fletching
- minecraft:heat
- minecraft:hovered
+ minecraft:item_name
- minecraft:lubrication
+ minecraft:ominous_bottle_amplifier
- minecraft:potato_bane
- minecraft:resin
- minecraft:secret_message
- minecraft:snek
- minecraft:undercover_id
- minecraft:views
- minecraft:xp
```

</details>
<details>
<summary>
universal_tags/enchantment.json
</summary>

```diff
+ minecraft:breach
+ minecraft:density
- minecraft:potatofication
+ minecraft:wind_burst
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
- minecraft:potato
+ minecraft:raider
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:batato
- minecraft:eye_of_potato
- minecraft:grid_carrier
- minecraft:lashing_potato_hook
- minecraft:mega_spud
+ minecraft:ominous_item_spawner
- minecraft:plaguewhale
- minecraft:poisonous_potato_zombie
- minecraft:toxifin
- minecraft:vine_projectile
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:amber_block
- minecraft:amber_gem
- minecraft:baked_potato_brick_slab
- minecraft:baked_potato_brick_stairs
- minecraft:baked_potato_brick_wall
- minecraft:baked_potato_bricks
- minecraft:batato_spawn_egg
- minecraft:big_brain
- minecraft:black_potato_peels
- minecraft:black_potato_peels_block
- minecraft:blue_potato_peels
- minecraft:blue_potato_peels_block
- minecraft:brown_potato_peels
- minecraft:brown_potato_peels_block
- minecraft:charred_baked_potato_brick_slab
- minecraft:charred_baked_potato_brick_stairs
- minecraft:charred_baked_potato_brick_wall
- minecraft:charred_baked_potato_bricks
- minecraft:compressed_poisonous_potato_block
- minecraft:corrupted_peelgrass_block
- minecraft:corrupted_potato_peels
- minecraft:corrupted_potato_peels_block
- minecraft:cyan_potato_peels
- minecraft:cyan_potato_peels_block
- minecraft:deepslate_poisonous_potato_ore
- minecraft:dent
- minecraft:double_compressed_poisonous_potato_block
- minecraft:enchanted_golden_poisonous_potato
- minecraft:expired_baked_potato_brick_slab
- minecraft:expired_baked_potato_brick_stairs
- minecraft:expired_baked_potato_brick_wall
- minecraft:expired_baked_potato_bricks
- minecraft:floatater
- minecraft:floatato
- minecraft:frying_table
- minecraft:golden_poisonous_potato
- minecraft:gravtater
- minecraft:gray_potato_peels
- minecraft:gray_potato_peels_block
- minecraft:green_potato_peels
- minecraft:green_potato_peels_block
- minecraft:hash_browns
- minecraft:hot_potato
- minecraft:lashing_potato
- minecraft:light_blue_potato_peels
- minecraft:light_blue_potato_peels_block
- minecraft:light_gray_potato_peels
- minecraft:light_gray_potato_peels_block
- minecraft:lime_potato_peels
- minecraft:lime_potato_peels_block
- minecraft:magenta_potato_peels
- minecraft:magenta_potato_peels_block
- minecraft:mega_spud_spawn_egg
+ minecraft:ominous_bottle
+ minecraft:ominous_trial_key
- minecraft:orange_potato_peels
- minecraft:orange_potato_peels_block
- minecraft:pedestal
- minecraft:peelgrass_block
- minecraft:pink_potato_peels
- minecraft:pink_potato_peels_block
- minecraft:plaguewhale_spawn_egg
- minecraft:poison_farmland
- minecraft:poison_path
- minecraft:poisonous_mashed_potato
- minecraft:poisonous_polytra
- minecraft:poisonous_pota_toes
- minecraft:poisonous_potato_block
- minecraft:poisonous_potato_chestplate
- minecraft:poisonous_potato_chips
- minecraft:poisonous_potato_cutter
- minecraft:poisonous_potato_fries
- minecraft:poisonous_potato_oil
- minecraft:poisonous_potato_ore
- minecraft:poisonous_potato_plant
- minecraft:poisonous_potato_slices
- minecraft:poisonous_potato_sticks
- minecraft:poisonous_potato_zombie_head_block
- minecraft:poisonous_potato_zombie_head_hat
- minecraft:poisonous_potato_zombie_spawn_egg
- minecraft:potato_battery
- minecraft:potato_bud
- minecraft:potato_button
- minecraft:potato_door
- minecraft:potato_eye
- minecraft:potato_fence
- minecraft:potato_fence_gate
- minecraft:potato_flower
- minecraft:potato_fruit
- minecraft:potato_hammer
- minecraft:potato_hanging_sign
- minecraft:potato_leaves
- minecraft:potato_of_knowledge
- minecraft:potato_oil
- minecraft:potato_pedicule
- minecraft:potato_peeler
- minecraft:potato_peels
- minecraft:potato_peels_block
- minecraft:potato_planks
- minecraft:potato_portal
- minecraft:potato_pressure_plate
- minecraft:potato_refinery
- minecraft:potato_sign
- minecraft:potato_slab
- minecraft:potato_sprouts
- minecraft:potato_staff
- minecraft:potato_stairs
- minecraft:potato_stem
- minecraft:potato_trapdoor
- minecraft:potone
- minecraft:potone_copper_ore
- minecraft:potone_diamond_ore
- minecraft:potone_gold_ore
- minecraft:potone_iron_ore
- minecraft:potone_lapis_ore
- minecraft:potone_redstone_ore
- minecraft:potone_slab
- minecraft:potone_stairs
- minecraft:potone_wall
- minecraft:powerful_potato
- minecraft:purple_potato_peels
- minecraft:purple_potato_peels_block
- minecraft:quadruple_compressed_poisonous_potato_block
- minecraft:red_potato_peels
- minecraft:red_potato_peels_block
- minecraft:resin_ore
- minecraft:snektato
- minecraft:strong_roots
- minecraft:taterstone
- minecraft:taterstone_slab
- minecraft:taterstone_stairs
- minecraft:taterstone_wall
- minecraft:terredepomme
- minecraft:toxic_beam
- minecraft:toxic_resin
- minecraft:toxifin_spawn_egg
- minecraft:triple_compressed_poisonous_potato_block
- minecraft:vicious_potato
- minecraft:weak_roots
- minecraft:yellow_potato_peels
- minecraft:yellow_potato_peels_block
```

</details>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
- minecraft:killer_main_hand_tool
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:set_ominous_bottle_amplifier
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
- minecraft:fletching
- minecraft:poisonous_potato_cutter
- minecraft:potato_refinery
```

</details>
<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
+ minecraft:infested
+ minecraft:oozing
- minecraft:potato_oil
+ minecraft:raid_omen
- minecraft:sticky
+ minecraft:trial_omen
+ minecraft:weaving
+ minecraft:wind_charged
```

</details>
<details>
<summary>
universal_tags/painting_variant.json
</summary>

```diff
- minecraft:abstractato
- minecraft:burning_potato
- minecraft:ceci
- minecraft:mr_potato
- minecraft:poisonous_potato
- minecraft:potatoe
- minecraft:ubiquitato
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:dust_pillar
- minecraft:falling_poison
- minecraft:footstep
+ minecraft:infested
+ minecraft:item_cobweb
- minecraft:lightning
+ minecraft:ominous_spawning
+ minecraft:raid_omen
- minecraft:reverse_lightning
+ minecraft:small_gust
+ minecraft:trial_omen
+ minecraft:trial_spawner_detection_ominous
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
- minecraft:pedestal
- minecraft:potato_portal
```

</details>
<details>
<summary>
universal_tags/potion.json
</summary>

```diff
+ minecraft:infested
+ minecraft:oozing
- minecraft:poisonous_potato_oil
- minecraft:potato_oil
- minecraft:sticky
+ minecraft:weaving
+ minecraft:wind_charged
```

</details>
<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
- minecraft:poisonous_potato_cutting
- minecraft:potato_refinement
```

</details>
<details>
<summary>
universal_tags/recipe_type.json
</summary>

```diff
- minecraft:poisonous_potato_cutting
- minecraft:potato_refinement
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.cobweb.break
+ minecraft:block.cobweb.fall
+ minecraft:block.cobweb.hit
+ minecraft:block.cobweb.place
+ minecraft:block.cobweb.step
+ minecraft:block.trial_spawner.about_to_spawn_item
+ minecraft:block.trial_spawner.ambient_charged
+ minecraft:block.trial_spawner.charge_activate
+ minecraft:block.trial_spawner.spawn_item
+ minecraft:block.trial_spawner.spawn_item_begin
+ minecraft:event.mob_effect.bad_omen
+ minecraft:event.mob_effect.raid_omen
+ minecraft:event.mob_effect.trial_omen
+ minecraft:item.ominous_bottle.dispose
- nothingtoseeheremovealong:ambient.arboretum.loop
- nothingtoseeheremovealong:ambient.corruption.loop
- nothingtoseeheremovealong:ambient.fields.loop
- nothingtoseeheremovealong:ambient.hash.loop
- nothingtoseeheremovealong:ambient.wasteland.loop
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.break
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.fall
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.hit
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.place
- nothingtoseeheremovealong:block.corrupted_peelgrass_block.step
- nothingtoseeheremovealong:block.gravtater.break
- nothingtoseeheremovealong:block.gravtater.fall
- nothingtoseeheremovealong:block.gravtater.hit
- nothingtoseeheremovealong:block.gravtater.place
- nothingtoseeheremovealong:block.gravtater.step
- nothingtoseeheremovealong:block.peelgrass_block.break
- nothingtoseeheremovealong:block.peelgrass_block.fall
- nothingtoseeheremovealong:block.peelgrass_block.hit
- nothingtoseeheremovealong:block.peelgrass_block.place
- nothingtoseeheremovealong:block.peelgrass_block.step
- nothingtoseeheremovealong:block.potato_battery.zap
- nothingtoseeheremovealong:block.potone.break
- nothingtoseeheremovealong:block.potone.fall
- nothingtoseeheremovealong:block.potone.hit
- nothingtoseeheremovealong:block.potone.place
- nothingtoseeheremovealong:block.potone.step
- nothingtoseeheremovealong:block.terredepomme.break
- nothingtoseeheremovealong:block.terredepomme.fall
- nothingtoseeheremovealong:block.terredepomme.hit
- nothingtoseeheremovealong:block.terredepomme.place
- nothingtoseeheremovealong:block.terredepomme.step
- nothingtoseeheremovealong:entity.megaspud.challenge
- nothingtoseeheremovealong:entity.megaspud.death
- nothingtoseeheremovealong:entity.megaspud.fireball
- nothingtoseeheremovealong:entity.megaspud.hurt
- nothingtoseeheremovealong:entity.megaspud.idle
- nothingtoseeheremovealong:entity.megaspud.jump
- nothingtoseeheremovealong:entity.megaspud.jump_hi
- nothingtoseeheremovealong:entity.megaspud.summon
- nothingtoseeheremovealong:entity.megaspud.upset
- nothingtoseeheremovealong:entity.plaguewhale.ambient
- nothingtoseeheremovealong:entity.plaguewhale.ambient_land
- nothingtoseeheremovealong:entity.plaguewhale.death
- nothingtoseeheremovealong:entity.plaguewhale.death_land
- nothingtoseeheremovealong:entity.plaguewhale.flop
- nothingtoseeheremovealong:entity.plaguewhale.hurt
- nothingtoseeheremovealong:entity.plaguewhale.hurt_land
- nothingtoseeheremovealong:entity.player.sprout_respawn
- nothingtoseeheremovealong:entity.player.sprout_respawn_one
- nothingtoseeheremovealong:entity.player.sprout_respawn_two
- nothingtoseeheremovealong:entity.potato.chips
- nothingtoseeheremovealong:entity.potato.peel
- nothingtoseeheremovealong:entity.toxifin.ambient
- nothingtoseeheremovealong:entity.toxifin.ambient_land
- nothingtoseeheremovealong:entity.toxifin.attack
- nothingtoseeheremovealong:entity.toxifin.death
- nothingtoseeheremovealong:entity.toxifin.death_land
- nothingtoseeheremovealong:entity.toxifin.flop
- nothingtoseeheremovealong:entity.toxifin.hurt
- nothingtoseeheremovealong:entity.toxifin.hurt_land
- nothingtoseeheremovealong:entity.zombie_potato.ambient
- nothingtoseeheremovealong:entity.zombie_potato.attack_iron_door
- nothingtoseeheremovealong:entity.zombie_potato.death
- nothingtoseeheremovealong:entity.zombie_potato.hurt
- nothingtoseeheremovealong:entity.zombie_potato.infect
- nothingtoseeheremovealong:entity.zombie_potato.step
- nothingtoseeheremovealong:intentionally_empty
- nothingtoseeheremovealong:ooof
- nothingtoseeheremovealong:the_joke
```

</details>
<details>
<summary>
universal_tags/trigger_type.json
</summary>

```diff
- minecraft:bring_home_corruption
- minecraft:compost_staff
- minecraft:eat_armor
- minecraft:get_peeled
- minecraft:peel_block
- minecraft:peel_potato_armor
- minecraft:peel_potato_sheep
- minecraft:potato_refined
- minecraft:rumble_plant
- minecraft:said_potato
- minecraft:throw_lubricated
```

</details>
<details>
<summary>
universal_tags/villager_type.json
</summary>

```diff
- minecraft:potato
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:cloud
- minecraft:hash_well
- minecraft:park_lane
- minecraft:park_lane_surface
- minecraft:potato_buds
- minecraft:potato_field
- minecraft:twisted_potato
```

</details>
<details>
<summary>
universal_tags/worldgen/placement_modifier_type.json
</summary>

```diff
- minecraft:cloud
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
- amber_block.json
- amber_gem.json
- baked_potato_brick_slab.json
- baked_potato_brick_stairs.json
- baked_potato_brick_wall.json
- baked_potato_bricks.json
- batato_spawn_egg.json
- big_brain.json
- black_potato_peels_block.json
- black_potato_peels.json
- blue_potato_peels_block.json
- blue_potato_peels.json
- brown_potato_peels_block.json
- brown_potato_peels.json
- charred_baked_potato_brick_slab.json
- charred_baked_potato_brick_stairs.json
- charred_baked_potato_brick_wall.json
- charred_baked_potato_bricks.json
- compressed_poisonous_potato_block.json
- corrupted_peelgrass_block.json
- corrupted_potato_peels_block.json
- corrupted_potato_peels.json
- cyan_potato_peels_block.json
- cyan_potato_peels.json
- deepslate_poisonous_potato_ore.json
- dent.json
- double_compressed_poisonous_potato_block.json
- enchanted_golden_poisonous_potato.json
- expired_baked_potato_brick_slab.json
- expired_baked_potato_brick_stairs.json
- expired_baked_potato_brick_wall.json
- expired_baked_potato_bricks.json
- floatater.json
- floatato.json
- frying_table.json
- golden_poisonous_potato.json
- gravtater.json
- gray_potato_peels_block.json
- gray_potato_peels.json
- green_potato_peels_block.json
- green_potato_peels.json
- hash_browns.json
- hot_potato.json
- lashing_potato.json
- light_blue_potato_peels_block.json
- light_blue_potato_peels.json
- light_gray_potato_peels_block.json
- light_gray_potato_peels.json
- lime_potato_peels_block.json
- lime_potato_peels.json
- magenta_potato_peels_block.json
- magenta_potato_peels.json
- mega_spud_spawn_egg.json
+ ominous_bottle.json
+ ominous_trial_key.json
- orange_potato_peels_block.json
- orange_potato_peels.json
- pedestal.json
- peelgrass_block.json
- pink_potato_peels_block.json
- pink_potato_peels.json
- plaguewhale_spawn_egg.json
- poison_farmland.json
- poison_path.json
- poisonous_mashed_potato.json
- poisonous_polytra.json
- poisonous_pota_toes.json
- poisonous_potato_block.json
- poisonous_potato_chestplate.json
- poisonous_potato_chips.json
- poisonous_potato_cutter.json
- poisonous_potato_fries.json
- poisonous_potato_oil.json
- poisonous_potato_ore.json
- poisonous_potato_plant.json
- poisonous_potato_slices.json
- poisonous_potato_sticks.json
- poisonous_potato_zombie_head_block.json
- poisonous_potato_zombie_head_hat.json
- poisonous_potato_zombie_spawn_egg.json
- potato_battery.json
- potato_bud.json
- potato_button.json
- potato_door.json
- potato_eye.json
- potato_fence_gate.json
- potato_fence.json
- potato_flower.json
- potato_fruit.json
- potato_hammer.json
- potato_hanging_sign.json
- potato_leaves.json
- potato_of_knowledge.json
- potato_oil.json
- potato_pedicule.json
- potato_peeler.json
- potato_peels_block.json
- potato_peels.json
- potato_planks.json
- potato_portal.json
- potato_pressure_plate.json
- potato_refinery.json
- potato_sign.json
- potato_slab.json
- potato_sprouts.json
- potato_staff.json
- potato_stairs.json
- potato_stem.json
- potato_trapdoor.json
- potone_copper_ore.json
- potone_diamond_ore.json
- potone_gold_ore.json
- potone_iron_ore.json
- potone_lapis_ore.json
- potone_redstone_ore.json
- potone_slab.json
- potone_stairs.json
- potone_wall.json
- potone.json
- powerful_potato.json
- purple_potato_peels_block.json
- purple_potato_peels.json
- quadruple_compressed_poisonous_potato_block.json
- red_potato_peels_block.json
- red_potato_peels.json
- resin_ore.json
- snektato.json
- strong_roots.json
- taterstone_slab.json
- taterstone_stairs.json
- taterstone_wall.json
- taterstone.json
- terredepomme.json
- toxic_beam.json
- toxic_resin.json
- toxifin_spawn_egg.json
- triple_compressed_poisonous_potato_block.json
- vicious_potato.json
- weak_roots.json
- yellow_potato_peels_block.json
- yellow_potato_peels.json
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
- amber_block.json
- baked_potato_brick_slab.json
- baked_potato_brick_stairs.json
- baked_potato_brick_wall.json
- baked_potato_bricks.json
- big_brain.json
- black_potato_peels_block.json
- blue_potato_peels_block.json
- brown_potato_peels_block.json
- charred_baked_potato_brick_slab.json
- charred_baked_potato_brick_stairs.json
- charred_baked_potato_brick_wall.json
- charred_baked_potato_bricks.json
- compressed_poisonous_potato_block.json
- corrupted_peelgrass_block.json
- corrupted_potato_peels_block.json
- cyan_potato_peels_block.json
- deepslate_poisonous_potato_ore.json
- double_compressed_poisonous_potato_block.json
- expired_baked_potato_brick_slab.json
- expired_baked_potato_brick_stairs.json
- expired_baked_potato_brick_wall.json
- expired_baked_potato_bricks.json
- floatater.json
- floatato.json
- frying_table.json
- gravtater.json
- gray_potato_peels_block.json
- green_potato_peels_block.json
- light_blue_potato_peels_block.json
- light_gray_potato_peels_block.json
- lime_potato_peels_block.json
- magenta_potato_peels_block.json
- orange_potato_peels_block.json
- pedestal.json
- peelgrass_block.json
- pink_potato_peels_block.json
- poison_farmland.json
- poison_path.json
- poisonous_mashed_potato.json
- poisonous_potato_block.json
- poisonous_potato_cutter.json
- poisonous_potato_ore.json
- poisonous_potato_zombie_head_block.json
- poisonous_potato_zombie_head_hat.json
- potato_battery.json
- potato_bud.json
- potato_button.json
- potato_door.json
- potato_fence_gate.json
- potato_fence.json
- potato_flower.json
- potato_fruit.json
- potato_hanging_sign.json
- potato_leaves.json
- potato_pedicule.json
- potato_peels_block.json
- potato_planks.json
- potato_portal.json
- potato_pressure_plate.json
- potato_refinery.json
- potato_sign.json
- potato_slab.json
- potato_sprouts.json
- potato_stairs.json
- potato_stem.json
- potato_trapdoor.json
- potato_wall_hanging_sign.json
- potato_wall_sign.json
- potone_copper_ore.json
- potone_diamond_ore.json
- potone_gold_ore.json
- potone_iron_ore.json
- potone_lapis_ore.json
- potone_redstone_ore.json
- potone_slab.json
- potone_stairs.json
- potone_wall.json
- potone.json
- potted_potato_flower.json
- powerful_potato.json
- purple_potato_peels_block.json
- quadruple_compressed_poisonous_potato_block.json
- red_potato_peels_block.json
- resin_ore.json
- strong_roots.json
- taterstone_slab.json
- taterstone_stairs.json
- taterstone_wall.json
- taterstone.json
- terredepomme.json
- triple_compressed_poisonous_potato_block.json
- vicious_potato.json
- weak_roots.json
- yellow_potato_peels_block.json
```

</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 2,
    "min_inclusive": 0
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 2,
  "min_inclusive": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 2,
    "min_inclusive": 0
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 2,
  "min_inclusive": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 7,
    "min_inclusive": 3
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 7,
  "min_inclusive": 3
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 1,
    "min_inclusive": 0
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 1,
  "min_inclusive": 0
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>experience</td><td><pre>{
  "type": "minecraft:uniform",
  "value": {
    "max_inclusive": 5,
    "min_inclusive": 2
  }
}</pre></td><td><pre>{
  "type": "minecraft:uniform",
  "max_inclusive": 5,
  "min_inclusive": 2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">24w14potato</th><th>24w14a</th></tr><tr><td>organic</td><td><pre>false</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
gamerule
</summary>

```diff
- gamerule floataterSizeLimit <value: integer>
- gamerule neverEatArmor <value: bool>
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
- amber_block.json
- amber_gem.json
- baked_potato_brick_slab_from_baked_potato_bricks_stonecutting.json
- baked_potato_brick_slab.json
- baked_potato_brick_stairs_from_baked_potato_bricks_stonecutting.json
- baked_potato_brick_stairs.json
- baked_potato_brick_wall_from_baked_potato_bricks_stonecutting.json
- baked_potato_brick_wall.json
- baked_potato_bricks_from_terredepomme.json
- baked_potato_bricks.json
- big_brain.json
- black_potato_peels_block.json
- black_potato_peels.json
- blue_potato_peels_block.json
- blue_potato_peels.json
- brown_potato_peels_block.json
- brown_potato_peels.json
- charred_baked_potato_brick_slab_from_charred_baked_potato_bricks_stonecutting.json
- charred_baked_potato_brick_slab.json
- charred_baked_potato_brick_stairs_from_charred_baked_potato_bricks_stonecutting.json
- charred_baked_potato_brick_stairs.json
- charred_baked_potato_brick_wall_from_charred_baked_potato_bricks_stonecutting.json
- charred_baked_potato_brick_wall.json
- charred_baked_potato_bricks.json
- compressed_poisonous_potato_block_from_double_compressed_poisonous_potato_block_unpacking.json
- compressed_poisonous_potato_block.json
- corrupted_potato_peels_block.json
- corrupted_potato_peels.json
- cyan_potato_peels_block.json
- cyan_potato_peels.json
- double_compressed_poisonous_potato_block_from_triple_compressed_poisonous_potato_block_unpacking.json
- double_compressed_poisonous_potato_block.json
- enchanted_golden_poisonous_potato.json
- expired_baked_potato_brick_slab_from_expired_baked_potato_bricks_stonecutting.json
- expired_baked_potato_brick_slab.json
- expired_baked_potato_brick_stairs_from_expired_baked_potato_bricks_stonecutting.json
- expired_baked_potato_brick_stairs.json
- expired_baked_potato_brick_wall_from_expired_baked_potato_bricks_stonecutting.json
- expired_baked_potato_brick_wall.json
- expired_baked_potato_bricks.json
- floatater.json
- floatato.json
- frying_table.json
- golden_poisonous_potato.json
- gray_potato_peels_block.json
- gray_potato_peels.json
- green_potato_peels_block.json
- green_potato_peels.json
- hash_browns_from_campfire_cooking.json
- hot_potato.json
- lashing_potato.json
- light_blue_potato_peels_block.json
- light_blue_potato_peels.json
- light_gray_potato_peels_block.json
- light_gray_potato_peels.json
- lime_potato_peels_block.json
- lime_potato_peels.json
- magenta_potato_peels_block.json
- magenta_potato_peels.json
- orange_potato_peels_block.json
- orange_potato_peels.json
- overcooked_potatoes.json
- pink_potato_peels_block.json
- pink_potato_peels.json
- poisonous_polytra.json
- poisonous_pota_toes.json
- poisonous_potato_block_from_compressed_poisonous_potato_block_unpacking.json
- poisonous_potato_block.json
- poisonous_potato_chestplate.json
- poisonous_potato_chips_from_campfire_cooking.json
- poisonous_potato_chips_from_smoking.json
- poisonous_potato_chips.json
- poisonous_potato_cutter.json
- poisonous_potato_fries_from_campfire_cooking.json
- poisonous_potato_fries_from_smoking.json
- poisonous_potato_fries.json
- poisonous_potato_from_poisonous_potato_block_unpacking.json
- poisonous_potato_oil_with_poisonous_potato_oil_from_potato_refinement.json
- poisonous_potato_slices_from_poisonous_potato_poisonous_potato_cutting.json
- poisonous_potato_sticks_from_poisonous_potato_poisonous_potato_cutting.json
- potato_battery.json
- potato_button.json
- potato_door.json
- potato_eye.json
- potato_fence_gate.json
- potato_fence.json
- potato_hammer.json
- potato_hanging_sign.json
- potato_oil_with_potato_oil_from_potato_refinement.json
- potato_peeler.json
- potato_peels_block.json
- potato_peels.json
- potato_planks.json
- potato_pressure_plate.json
- potato_refinery.json
- potato_sign.json
- potato_slab.json
- potato_stairs.json
- potato_trapdoor.json
- potone_slab_from_potone_stonecutting.json
- potone_slab.json
- potone_stairs_from_potone_stonecutting.json
- potone_stairs.json
- potone_wall_from_potone_stonecutting.json
- potone_wall.json
- potone.json
- purple_potato_peels_block.json
- purple_potato_peels.json
- quadruple_compressed_poisonous_potato_block.json
- red_potato_peels_block.json
- red_potato_peels.json
- taterstone_slab_from_taterstone_stonecutting.json
- taterstone_slab.json
- taterstone_stairs_from_taterstone_stonecutting.json
- taterstone_stairs.json
- taterstone_wall_from_taterstone_stonecutting.json
- taterstone_wall.json
- toxic_resin.json
- trident.json
- triple_compressed_poisonous_potato_block_from_quadruple_compressed_poisonous_potato_block_unpacking.json
- triple_compressed_poisonous_potato_block.json
- vicious_potato.json
- yellow_potato_peels_block.json
- yellow_potato_peels.json
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
- advancements.potato.all_potatoed.description: Visit all the Potato Biomes
- advancements.potato.all_potatoed.title: Around the Potato in 80 Days
- advancements.potato.bring_home_the_corruption.description: See the corruption and be like: Hey, I want that in my garden!
- advancements.potato.bring_home_the_corruption.title: Bring Home the Corruption
- advancements.potato.craft_poisonous_potato_chips.description: Chips vs Crisps. Let the debate begin.
- advancements.potato.craft_poisonous_potato_chips.title: A salty snack
- advancements.potato.craft_poisonous_potato_fries.description: Eat some Poisonous Potato Fries
- advancements.potato.craft_poisonous_potato_fries.title: Finally some fast food!
- advancements.potato.craft_poisonous_potato_slices.description: Eat some Poisonous Potato Slices
- advancements.potato.craft_poisonous_potato_slices.title: Sliced to perfection
- advancements.potato.craft_poisonous_potato_sticks.description: Eat some Poisonous Potato Sticks
- advancements.potato.craft_poisonous_potato_sticks.title: A bit undercooked
- advancements.potato.eat_armor.description: Avoid getting hungry by eating your worn Poisonous Potato Chestplate
- advancements.potato.eat_armor.title: I'm so hungry I could eat my shirt!
- advancements.potato.enter_the_potato.description: Enter the Potato Dimension
- advancements.potato.enter_the_potato.title: Non Plus Ultra
- advancements.potato.get_oily.description: Refine a potato into Potato Oil
- advancements.potato.get_oily.title: Get oily
- advancements.potato.get_peeled.description: Get peeled by another player using a Potato Peeler while wearing a Poisonous Potato Chestplate
- advancements.potato.get_peeled.title: Get Peeled!
- advancements.potato.good_plant.description: Do as the P.P.P. demands
- advancements.potato.good_plant.title: Good Plant
- advancements.potato.lubricate_boots.description: ...sliding. And that's just what they'll do!
- advancements.potato.lubricate_boots.title: These boots were made for...
- advancements.potato.lubricate_whee.description: Throw a lubricated item and watch it slide!
- advancements.potato.lubricate_whee.title: Whee!
- advancements.potato.lubricate.description: Lubricate an item with Potato Oil in the Potato Refinery
- advancements.potato.lubricate.title: So slippery!
- advancements.potato.mega_lubricate_whee.description: How far can you go?
- advancements.potato.mega_lubricate_whee.title: WHEEEEEEEEE!
- advancements.potato.mega_lubricate.description: Lubricate an item ten times!
- advancements.potato.mega_lubricate.title: Lubrication Bonanza
- advancements.potato.peel_all_the_things.description: Peel a block. Peel a potato sheep. Peel the Poisonous Potato Chestplate of an entity.
- advancements.potato.peel_all_the_things.title: Peel all the things!
- advancements.potato.poisonous_potato_gourmet.description: Eat Poisonous Potato Sticks, Slices, Fries and Chips.
- advancements.potato.poisonous_potato_gourmet.title: Poisonous Potato Gourmet
- advancements.potato.poisonous_potato_taster.description: Eat some raw Poisonous Potato Sticks and Slices
- advancements.potato.poisonous_potato_taster.title: Poisonous Potato Taster
- advancements.potato.potato_peeler.description: Craft the Potato Peeler
- advancements.potato.potato_peeler.title: Peeling Good
- advancements.potato.root.description: The world is your potato
- advancements.potato.root.title: Poisonous Potato Saga
- advancements.potato.rumbled.description: Place a Poisonous Potato Plant on your head to reveal the truth
- advancements.potato.rumbled.title: On Closer Inspection...
- advancements.potato.sweet_potato_talker.description: Said 'potato' over 99 times
- advancements.potato.sweet_potato_talker.title: Sweet Potato Talker!
- advancements.potato.well_done.description: Reheat potatoes too many times
- advancements.potato.well_done.title: Well Done
- baseColor.tooltip: Color: %s
- biome.minecraft.arboretum: Arboretum
- biome.minecraft.corruption: Curruption
- biome.minecraft.fields: Fields
- biome.minecraft.hash: Hash
- biome.minecraft.wasteland: Wasteland
- block.minecraft.amber_block: Block of Amber
- block.minecraft.baked_potato_brick_slab: Baked Potato Brick Slab
- block.minecraft.baked_potato_brick_stairs: Baked Potato Brick Stairs
- block.minecraft.baked_potato_brick_wall: Baked Potato Brick Wall
- block.minecraft.baked_potato_bricks: Baked Potato Bricks
- block.minecraft.big_brain: Big Brain
- block.minecraft.black_potato_peels_block: Block of Black Potato Peels
- block.minecraft.blue_potato_peels_block: Block of Blue Potato Peels
- block.minecraft.brown_potato_peels_block: Block of Brown Potato Peels
- block.minecraft.charred_baked_potato_brick_slab: Charred Baked Potato Brick Slab
- block.minecraft.charred_baked_potato_brick_stairs: Charred Baked Potato Brick Stairs
- block.minecraft.charred_baked_potato_brick_wall: Charred Baked Potato Brick Wall
- block.minecraft.charred_baked_potato_bricks: Charred Baked Potato Bricks
- block.minecraft.compressed_poisonous_potato_block: Compressed Poisonous Potato Block
- block.minecraft.corrupted_peelgrass_block: Corrupted Peelgrass Block
- block.minecraft.corrupted_potato_peels_block: Block of Corrupted Potato Peels
- block.minecraft.cyan_potato_peels_block: Block of Cyan Potato Peels
- block.minecraft.deepslate_poisonous_potato_ore: Deepslate Poisonous Potato Ore
- block.minecraft.double_compressed_poisonous_potato_block: Double Compressed Poisonous Potato Block
- block.minecraft.expired_baked_potato_brick_slab: Expired Baked Potato Brick Slab
- block.minecraft.expired_baked_potato_brick_stairs: Expired Baked Potato Brick Stairs
- block.minecraft.expired_baked_potato_brick_wall: Expired Baked Potato Brick Wall
- block.minecraft.expired_baked_potato_bricks: Expired Baked Potato Bricks
- block.minecraft.fletching_table.from: Requires:
- block.minecraft.fletching_table.to: Produces:
- block.minecraft.floatater: Floatater
- block.minecraft.floatato: Floatato
- block.minecraft.frying_table: Frying Table
- block.minecraft.gravtater: Gravtater
- block.minecraft.gray_potato_peels_block: Block of Gray Potato Peels
- block.minecraft.green_potato_peels_block: Block of Green Potato Peels
- block.minecraft.light_blue_potato_peels_block: Block of Light Blue Potato Peels
- block.minecraft.light_gray_potato_peels_block: Block of Light Gray Potato Peels
- block.minecraft.lime_potato_peels_block: Block of Lime Potato Peels
- block.minecraft.magenta_potato_peels_block: Block of Magenta Potato Peels
- block.minecraft.orange_potato_peels_block: Block of Orange Potato Peels
- block.minecraft.pedestal: Pedestal
- block.minecraft.peelgrass_block: Peelgrass Block
- block.minecraft.pink_potato_peels_block: Block of Pink Potato Peels
- block.minecraft.poison_farmland: Poison Farmland
- block.minecraft.poison_path: Poison Path
- block.minecraft.poisonous_mashed_potato: Poisonous Mashed Potato
- block.minecraft.poisonous_potato_block: Poisonous Potato Block
- block.minecraft.poisonous_potato_cutter: Poisonous Potato Cutter
- block.minecraft.poisonous_potato_ore: Poisonous Potato Ore
- block.minecraft.poisonous_potato_zombie_head_block: Poisonous Potato Head Block
- block.minecraft.poisonous_potato_zombie_head_hat: Poisonous Potato Headpiece
- block.minecraft.potato_battery: Potato Battery
- block.minecraft.potato_bud: Potato Bud
- block.minecraft.potato_button: Potato Button
- block.minecraft.potato_door: Potato Door
- block.minecraft.potato_fence_gate: Potato Fence Gate
- block.minecraft.potato_fence: Potato Fence
- block.minecraft.potato_flower: Potato flower
- block.minecraft.potato_fruit: Potato Fruit
- block.minecraft.potato_hanging_sign: Potato Hanging Sign
- block.minecraft.potato_leaves: Potato Leaves
- block.minecraft.potato_pedicule: Potato Pedicule
- block.minecraft.potato_peels_block: Block of Potato Peels
- block.minecraft.potato_planks: Potato Planks
- block.minecraft.potato_portal: Potato Portal
- block.minecraft.potato_pressure_plate: Potato Pressure Plate
- block.minecraft.potato_refinery: Potato Refinery
- block.minecraft.potato_sign: Potato Sign
- block.minecraft.potato_slab: Potato Slab
- block.minecraft.potato_sprouts: Potato Sprouts
- block.minecraft.potato_stairs: Potato Stairs
- block.minecraft.potato_stem: Potato Stem
- block.minecraft.potato_trapdoor: Potato Trapdoor
- block.minecraft.potone_copper_ore: Potone Copper Ore
- block.minecraft.potone_diamond_ore: Potone Diamond Ore
- block.minecraft.potone_gold_ore: Potone Gold Ore
- block.minecraft.potone_iron_ore: Potone Iron Ore
- block.minecraft.potone_lapis_ore: Potone Lapis Lazuli Ore
- block.minecraft.potone_redstone_ore: Potone Redstone Ore
- block.minecraft.potone_slab: Potone Slab
- block.minecraft.potone_stairs: Potone Stairs
- block.minecraft.potone_wall: Potone Wall
- block.minecraft.potone: Potone
- block.minecraft.potted_potato_flower: Potted Potato flower
- block.minecraft.powerful_potato: Powerful Potato
- block.minecraft.purple_potato_peels_block: Block of Purple Potato Peels
- block.minecraft.quadruple_compressed_poisonous_potato_block: Quadruple Compressed Poisonous Potato Block
- block.minecraft.red_potato_peels_block: Block of Red Potato Peels
- block.minecraft.resin_ore: Resin Ore
- block.minecraft.strong_roots: Strong Roots
- block.minecraft.taterstone_slab: Taterstone Slab
- block.minecraft.taterstone_stairs: Taterstone Stairs
- block.minecraft.taterstone_wall: Taterstone Wall
- block.minecraft.taterstone: Taterstone
- block.minecraft.terredepomme: Terre de Pomme
- block.minecraft.triple_compressed_poisonous_potato_block: Triple Compressed Poisonous Potato Block
- block.minecraft.vicious_potato: Vicious Potato
- block.minecraft.weak_roots: Weak Roots
- block.minecraft.yellow_potato_peels_block: Block of Yellow Potato Peels
+ chat.disabled.invalid_command_signature: Command had unexpected or missing command argument signatures.
+ chat.disabled.invalid_signature: Chat had an invalid signature. Please try reconnecting.
+ chat.disabled.out_of_order_chat: Chat received out-of-order. Did your system time change?
- container.poisonous_potato_cutter: Poisonous Potato Cutter
- container.potato_refinery: Potato Refinery
- death.attack.potato_heat: %1$s held the hot potato for too long.
- death.attack.potato_magic: %1$s was killed by a bad-tempered potato
+ effect.minecraft.infested: Infested
+ effect.minecraft.oozing: Oozing
- effect.minecraft.potato_oil: It's very slippery
+ effect.minecraft.raid_omen: Raid Omen
- effect.minecraft.sticky: Sticky
+ effect.minecraft.trial_omen: Trial Omen
+ effect.minecraft.weaving: Weaving
+ effect.minecraft.wind_charged: Wind Charged
+ enchantment.minecraft.breach: Breach
+ enchantment.minecraft.density: Density
- enchantment.minecraft.potatofication: Potatofication
+ enchantment.minecraft.wind_burst: Wind Burst
- entity.minecraft.batato: Batato
- entity.minecraft.eye_of_potato: Eye of Potato
- entity.minecraft.grid_carrier: Super Extra Magic
- entity.minecraft.lashing_potato_hook: Lashing Potato Hook
- entity.minecraft.mega_spud: Mega Spud, Potatolord of the Fried Legion
- entity.minecraft.mega_spud.armadillo: Mega Spud the Toxic Talon Talus
- entity.minecraft.mega_spud.chicken: Mega Spud the Clucky Contaminator
- entity.minecraft.mega_spud.creeper: Mega Spud the Creeper Kingpin
- entity.minecraft.mega_spud.frog: Mega Spud the Frogspawn Foreman
- entity.minecraft.mega_spud.ghast: Mega Spud the Ghastly Ghoulmaster
- entity.minecraft.mega_spud.giant: Mega Spud the Giant Green Globule
- entity.minecraft.mega_spud.piglin_brute: Mega Spud the Poisonous Piglin Potentate
- entity.minecraft.mega_spud.plaguewhale: Mega Spud the Plaguewhale Patriarch
- entity.minecraft.mega_spud.poisonous_potato_zombie: Mega Spud the Venomous Vagabond
- entity.minecraft.mega_spud.spider: Mega Spud the Arachnid Administrator
- entity.minecraft.mega_spud.stray: Mega Spud the Spud Scavenger Stray
+ entity.minecraft.ominous_item_spawner: Ominous Item Spawner
- entity.minecraft.plaguewhale: Plaguewhale Slab
- entity.minecraft.poisonous_potato_zombie: Posionous Potato Zombie
- entity.minecraft.toxifin: Toxifin Slab
- entity.minecraft.vine_projectile: Vine
- gamerule.floataterSizeLimit: Floatater size limit
- gamerule.floataterSizeLimit.description: Floatater structures can be at maximum NxNxN blocks in size.
- gamerule.neverEatArmor: Never eat armor when hungry. Even if it looks delicious.
- item.minecraft.amber_gem: Amber Gem
- item.minecraft.batato_spawn_egg: Batato Spawn Egg
- item.minecraft.corrupted_potato_peels: Corrupted Potato Peels
- item.minecraft.dent: Dent
- item.minecraft.enchanted_golden_poisonous_potato: Enchanted Golden Poisonous Potato
- item.minecraft.golden_poisonous_potato: Golden Poisonous Potato
- item.minecraft.hash_browns: Hash Browns
- item.minecraft.hot_potato: Hot potato
- item.minecraft.lashing_potato: Lashing Potato
+ item.minecraft.lingering_potion.effect.infested: Lingering Potion of Infestation
+ item.minecraft.lingering_potion.effect.oozing: Lingering Potion of Oozing
- item.minecraft.lingering_potion.effect.poisonous_potato_oil: Lingering Poisonous Potato Oil
- item.minecraft.lingering_potion.effect.potato_oil: Lingering Potato Oil
- item.minecraft.lingering_potion.effect.sticky: Lingering Potion of Sticky
+ item.minecraft.lingering_potion.effect.weaving: Lingering Potion of Weaving
+ item.minecraft.lingering_potion.effect.wind_charged: Lingering Potion of Wind Charging
- item.minecraft.mega_spud_spawn_egg: Mega Spud Spawn Egg
+ item.minecraft.ominous_bottle: Ominous Bottle
+ item.minecraft.ominous_trial_key: Ominous Trial Key
- item.minecraft.paper.secret.0: Are you a plant?
- item.minecraft.paper.secret.1: Do you think %s knows?
- item.minecraft.paper.secret.2: I think they know
- item.minecraft.paper.secret.3: Let's stay quiet
- item.minecraft.paper.secret.4: Destroy this message after reading
- item.minecraft.plaguewhale_spawn_egg: Plaguewhale Slab Spawn Egg
- item.minecraft.poisonous_polytra: Poisonous Polytra
- item.minecraft.poisonous_pota_toes: Poisonous Pota-Toes
- item.minecraft.poisonous_potato_chestplate: Poisonous Potato Chestplate
- item.minecraft.poisonous_potato_chips: Poisonous Potato Chips
- item.minecraft.poisonous_potato_fries: Poisonous Potato Fries
- item.minecraft.poisonous_potato_oil: Poisonous Potato Oil
- item.minecraft.poisonous_potato_oil.effect.poisonous_potato_oil: Poisonous Potato Oil
- item.minecraft.poisonous_potato_plant: Poisonous Potato Plant
- item.minecraft.poisonous_potato_plant.rumbled.line1: On closer inspection this
- item.minecraft.poisonous_potato_plant.rumbled.line2: %s is a plant.
- item.minecraft.poisonous_potato_slices: Poisonous Potato Slices
- item.minecraft.poisonous_potato_sticks: Poisonous Potato Sticks
- item.minecraft.poisonous_potato_zombie_spawn_egg: Poisonous Potato Zombie Spawn Egg
- item.minecraft.potato_eye: Potato Eye
- item.minecraft.potato_hammer: Poisonous Potato Hammer
- item.minecraft.potato_of_knowledge: Potato of Knowledge
- item.minecraft.potato_of_knowledge.amount: Amount: %s
- item.minecraft.potato_oil: Potato Oil
- item.minecraft.potato_oil.effect.potato_oil: Potato Oil
- item.minecraft.potato_peeler: Potato Peeler
- item.minecraft.potato_peels.black: Black Potato Peels
- item.minecraft.potato_peels.blue: Blue Potato Peels
- item.minecraft.potato_peels.brown: Brown Potato Peels
- item.minecraft.potato_peels.cyan: Cyan Potato Peels
- item.minecraft.potato_peels.gray: Gray Potato Peels
- item.minecraft.potato_peels.green: Green Potato Peels
- item.minecraft.potato_peels.light_blue: Light Blue Potato Peels
- item.minecraft.potato_peels.light_gray: Light Gray Potato Peels
- item.minecraft.potato_peels.lime: Lime Potato Peels
- item.minecraft.potato_peels.magenta: Magenta Potato Peels
- item.minecraft.potato_peels.orange: Orange Potato Peels
- item.minecraft.potato_peels.pink: Pink Potato Peels
- item.minecraft.potato_peels.purple: Purple Potato Peels
- item.minecraft.potato_peels.red: Red Potato Peels
- item.minecraft.potato_peels.white: Potato Peels
- item.minecraft.potato_peels.yellow: Yellow Potato Peels
- item.minecraft.potato_portal: Potato Portal
- item.minecraft.potato_staff: Potatiesh, Greatstaff of the Peasant
- item.minecraft.potato_staff.unworthy: %s was unworthy of Potatiesh, Greatstaff of the Peasant
+ item.minecraft.potion.effect.infested: Potion of Infestation
+ item.minecraft.potion.effect.oozing: Potion of Oozing
- item.minecraft.potion.effect.poisonous_potato_oil: Poisonous Potato Oil
- item.minecraft.potion.effect.potato_oil: Potato Oil
- item.minecraft.potion.effect.sticky: Potion of Sticky
+ item.minecraft.potion.effect.weaving: Potion of Weaving
+ item.minecraft.potion.effect.wind_charged: Potion of Wind Charging
- item.minecraft.snektato: Potato
- item.minecraft.snektato.revealed: Venomous Potato
+ item.minecraft.splash_potion.effect.infested: Splash Potion of Infestation
+ item.minecraft.splash_potion.effect.oozing: Splash Potion of Oozing
- item.minecraft.splash_potion.effect.poisonous_potato_oil: Splash Poisonous Potato Oil
- item.minecraft.splash_potion.effect.potato_oil: Splash Potato Oil
- item.minecraft.splash_potion.effect.sticky: Splash Potion of Sticky
+ item.minecraft.splash_potion.effect.weaving: Splash Potion of Weaving
+ item.minecraft.splash_potion.effect.wind_charged: Splash Potion of Wind Charging
+ item.minecraft.tipped_arrow.effect.infested: Arrow of Infestation
+ item.minecraft.tipped_arrow.effect.oozing: Arrow of Oozing
- item.minecraft.tipped_arrow.effect.poisonous_potato_oil: Arrow of Deadly Oilyness
- item.minecraft.tipped_arrow.effect.potato_oil: Arrow of Oilyness
- item.minecraft.tipped_arrow.effect.sticky: Arrow of Sticky
+ item.minecraft.tipped_arrow.effect.weaving: Arrow of Weaving
+ item.minecraft.tipped_arrow.effect.wind_charged: Arrow of Wind Charging
- item.minecraft.toxic_beam: Toxic Beam
- item.minecraft.toxic_resin: Toxic Resin
- item.minecraft.toxifin_spawn_egg: Toxifin Slab Spawn Egg
- item.resin.clarity.adjective.a: Abysmal
- item.resin.clarity.adjective.b: Blemished
- item.resin.clarity.adjective.c: Clouded
- item.resin.clarity.adjective.d: Dull
- item.resin.clarity.adjective.e: Eventual
- item.resin.clarity.adjective.f: Faint
- item.resin.clarity.adjective.g: Glimmering
- item.resin.clarity.adjective.h: Hazy
- item.resin.clarity.adjective.i: Icy
- item.resin.clarity.adjective.j: Jewel
- item.resin.impurities: %s Impurities
- item.resin.impurity.adjective.a: Air Bubble
- item.resin.impurity.adjective.b: Bug
- item.resin.impurity.adjective.c: Chemical
- item.resin.impurity.adjective.d: Diorite
- item.resin.impurity.adjective.e: Ender
- item.resin.impurity.adjective.f: Fishy
- item.resin.impurity.adjective.g: Galactic
- item.resin.impurity.adjective.h: Honey
- item.resin.impurity.adjective.i: Insect
- item.resin.impurity.adjective.j: Jinn
- item.resin.impurity.adjective.k: Kraken
- item.resin.impurity.adjective.l: Lunar
- item.resin.impurity.adjective.m: Metallic
- item.resin.impurity.adjective.n: Nether
- item.resin.impurity.adjective.o: Organic
- item.resin.impurity.adjective.p: Pigment
- item.resin.impurity.adjective.unknown: ¯\_(ツ)_/¯
- item.resin.quality: %s Clarity
- item.resin.quality.0: Opaque
- item.resin.quality.1: Murky
- item.resin.quality.10: Celestial
- item.resin.quality.2: Cloudy
- item.resin.quality.3: Clear
- item.resin.quality.4: Pure
- item.resin.quality.5: Flawless
- item.resin.quality.6: Perfect
- item.resin.quality.7: Transcendent
- item.resin.quality.8: Divine
- item.resin.quality.9: Ethereal
- item.resin.quality.comment: Comment on ^: These are nice, but I can't find a use for them [G]. Leave a like, leave a comment, and subscribe!, and see you in the next one, bye!
- itemGroup.potatoes: Potatoes
- key.potato: Potato
- lubrication.tooltip.lubricated_times: Lubricated! x%s
- lubrication.tooltip.lubricated: Lubricated!
+ options.telemetry.disabled: Telemetry is disabled.
- painting.minecraft.abstractato.author: Mr. Potato
- painting.minecraft.abstractato.title: Tasty Shapes
- painting.minecraft.burning_potato.author: Mr. Potato
- painting.minecraft.burning_potato.title: Hot Potato
- painting.minecraft.ceci.author: Mr. Potato
- painting.minecraft.ceci.title: This is not a potato
- painting.minecraft.mr_potato.author: Mr. Potato
- painting.minecraft.mr_potato.title: Self-portrait
- painting.minecraft.poisonous_potato.author: Mr. Potato
- painting.minecraft.poisonous_potato.title: The Treachery of Potatoes
- painting.minecraft.potatoe.author: Cris B
- painting.minecraft.potatoe.title: Potato
- painting.minecraft.ubiquitato.author: Mr. Potato
- painting.minecraft.ubiquitato.title: In The Spotlight
- paper.thoughts: Write your thoughts on the April Fools' Snapshot
- potato_bane.tooltip.damage_boost: +%s Damage to Potato Mobs
- potato.quest.anvil_dropped.jump.0: There, that should do it.
- potato.quest.anvil_dropped.jump.1: Use that Anvil to write your thoughts on the Paper.
- potato.quest.book.author: P.P.P.
- potato.quest.book.page.0: • Ice cream scoops
• Filthy rags
• Emerald Horse Armor
• Sunglasses
• Many spiders
• More spiders
• Lots of spiders
• Too many spiders
• Ice cream spiders
• Tiny fishing rods
• Boots that don't fly off my feet when I am running
- potato.quest.book.page.1: • Boots that don't fly off my feet, kicking me in my own nose, when I am running
• Emerald Horses
• Moonglasses
• X-ray glasses
• Four course meals
• Smaller Salmon
• Toothbrushes (to help with dental hygiene)
- potato.quest.book.page.2: • One of those chocolate eggs that you'd find in a cave, but you cannot pick it up, you must unwrap its foil there on the ground, and eat it immediately, leaving the trash behind
• More things made of Stone
• Ray from last years' April Fools'
- potato.quest.book.title: My Minecraft Ideas
- potato.quest.composted_staff.jump.0: Wow I can't believe you fell for that.
- potato.quest.composted_staff.jump.1: Potatiesh really is the ultimate Staff.
- potato.quest.composted_staff.jump.2: And now it's half-way composted into Bonemeal.
- potato.quest.composted_staff.jump.3: Congratulations.
- potato.quest.composted_staff.jump.4: I made a fool out of you %1$s.
- potato.quest.composted_staff.jump.5: April Fools'!
- potato.quest.crafted_eyes.jump.0: Wow nice crafting. Have you played Minecraft before?
- potato.quest.crafted_eyes.jump.1: Now we're going to go on a little adventure.
- potato.quest.crafted_eyes.jump.2: Throw the Potato Eye into the air.
- potato.quest.crafted_eyes.jump.3: When I say "throw" I don't mean "drop".
- potato.quest.crafted_eyes.jump.4: It's something to do with "Using" the Potato Eye with %3$s.
- potato.quest.crafted_eyes.jump.5: Look into the sky and use the Potato Eye with %3$s.
- potato.quest.dimension.jump.0: At last. The Potato Dimension.
- potato.quest.dimension.jump.1: Does something smell...Starchy to you?
- potato.quest.dimension.jump.10: Anyhow, we should find a Potato Village.
- potato.quest.dimension.jump.11: There should be a Potato Village around here somewhere...
- potato.quest.dimension.jump.2: I think you need to change your shampoo.
- potato.quest.dimension.jump.3: I am feeling quite greasy up here.
- potato.quest.dimension.jump.4: Let's focus on the task at hand.
- potato.quest.dimension.jump.5: ...
- potato.quest.dimension.jump.6: This place is looking rather tragic.
- potato.quest.dimension.jump.7: Have you seen the animals?
- potato.quest.dimension.jump.8: The Minecraft Pig is looking pretty cheeky.
- potato.quest.dimension.jump.9: And so is the Cow.
Very cheeky.
- potato.quest.found_colosseum.jump.0: The Potato Eye is pointing around here.
- potato.quest.found_colosseum.jump.1: That means we're near the right place!
- potato.quest.found_colosseum.jump.2: Let's start digging until we find the structure.
- potato.quest.found_colosseum.jump.3: Come on, %1$s. Time to put the MINE into Minecraft.
- potato.quest.found_colosseum.jump.4: ...
- potato.quest.found_colosseum.jump.5: What I'm trying to say is: Start digging.
- potato.quest.found_colosseum.jump.6: Mine your way into the structure.
- potato.quest.found_portal.jump.0: Is that the portal?
- potato.quest.found_portal.jump.1: It seems a little...Worse for wear.
- potato.quest.found_portal.jump.2: I see a Pedestal in the middle.
- potato.quest.found_portal.jump.3: Have you got a spare Poisonous Potato with you?
- potato.quest.found_portal.jump.4: Try using a Poisonous Potato with the Pedestal.
- potato.quest.got_book.jump.0: I've written my best Minecraft ideas in this book.
- potato.quest.got_book.jump.1: They are very original ideas.
- potato.quest.got_book.jump.10: Spoiler alert: It is the ultimate item in this April Fools' Snapshot.
- potato.quest.got_book.jump.11: You need to acquire Potatiesh, Greatstaff of the Peasant.
- potato.quest.got_book.jump.2: If the Developers don't use them then I could make a mod.
- potato.quest.got_book.jump.3: Or maybe they could give me a job?
- potato.quest.got_book.jump.4: I could start by making everyone coffee.
- potato.quest.got_book.jump.5: I'd tell jokes about drinking coffee and writing Java code.
- potato.quest.got_book.jump.6: They probably only hire Minecraft experts.
- potato.quest.got_book.jump.7: %1$s! We should become Minecraft experts!
- potato.quest.got_book.jump.8: And I know the perfect way to do that.
- potato.quest.got_book.jump.9: Our intelligence tells us of a legendary Greatstaff: Potatiesh.
- potato.quest.got_paper.jump.0: You should hopefully have some Paper on you.
- potato.quest.got_paper.jump.1: Oh wait, you need an Anvil too.
- potato.quest.got_paper.jump.2: 
- potato.quest.got_staff.jump.0: This is Potatiesh, Greatstaff of the Peasant!
- potato.quest.got_staff.jump.1: Now I need you to follow my instructions very carefully.
- potato.quest.got_staff.jump.2: Place Potatiesh into a Composter.
- potato.quest.got_staff.jump.3: Trust me. I will definitely NOT betray you.
- potato.quest.got_staff.jump.4: Find a Composter, and pop Potatiesh in there.
- potato.quest.got_staff.jump.5: It would be super cool if you closed your eyes afterwards.
- potato.quest.got_staff.jump.6: Just pop Potatiesh into a Composter, and then close your eyes.
- potato.quest.got_staff.jump.7: It's a really real thing that you can definitely do.
- potato.quest.got_staff.jump.8: Find a Composter, and use Potatiesh with it.
- potato.quest.got_sword.jump.0: Defend yourself. I'll watch your back!
- potato.quest.got_sword.jump.1: Look out!
- potato.quest.got_sword.jump.10: Place some blocks!
- potato.quest.got_sword.jump.11: Throw a blanket over it!
- potato.quest.got_sword.jump.12: Try spinning really fast!
- potato.quest.got_sword.jump.13: 
- potato.quest.got_sword.jump.2: Try a critical hit!
- potato.quest.got_sword.jump.3: Swing faster!
- potato.quest.got_sword.jump.4: No, don't do that!
- potato.quest.got_sword.jump.5: Is that TNT?
- potato.quest.got_sword.jump.6: If only you were wearing a Helmet.
- potato.quest.got_sword.jump.7: Go that way!
- potato.quest.got_sword.jump.8: Go the other way!
- potato.quest.got_sword.jump.9: Try unplugging your mouse and swinging it!
- potato.quest.in_village.0: There should be a Bed around here that we can take.
- potato.quest.inside_colosseum.jump.0: Woah. I think we're here.
- potato.quest.inside_colosseum.jump.1: This looks like some kind of Colosseum.
- potato.quest.inside_colosseum.jump.2: I think you'll need this Wooden Sword.
- potato.quest.inside_colosseum.jump.3: 
- potato.quest.intro.jump.0: Well, well, well. It looks like you found us.
(Press [%2$s] to acknowledge)
- potato.quest.intro.jump.1: Woah, steady on your feet there %1$s.
- potato.quest.intro.jump.10: We had to write tens of lines of code by rolling on the keys
and hoping for the best.
- potato.quest.intro.jump.11: And now that I have finally infiltrated Minecraft:
You pranced on over, picked me up, and plopped me on your head.
- potato.quest.intro.jump.12: I must say, you have incredible balance keeping me up here.
- potato.quest.intro.jump.13: Especially considering you're jumping so much.
- potato.quest.intro.jump.14: Why are you jumping? Are you being startled?
- potato.quest.intro.jump.15: I don't see much to be startled by around here.
- potato.quest.intro.jump.16: Then again, I have no eyes as I am a Poisonous Potato.
- potato.quest.intro.jump.17: So really I'm not going to see much at all.
- potato.quest.intro.jump.18: Although the little sprouts growing out of me are also called eyes.
- potato.quest.intro.jump.19: Perhaps if I squint hard enough I can see where we're at.
- potato.quest.intro.jump.2: You're probably thinking: "What's the deal with this guy?"
- potato.quest.intro.jump.20: Watch out! There's a block over there! Try not to be startled by it!
- potato.quest.intro.jump.21: Maybe you need a moment to breathe and relax.
This world is very startling, afterall.
- potato.quest.intro.jump.22: If we can find a Village we could take one of those Beds and rest.
- potato.quest.intro.jump.23: Let's find a Minecraft Village.
- potato.quest.intro.jump.3: I invite you to take a moment to consider my situation.
- potato.quest.intro.jump.4: We've been planning on infiltrating Minecraft for weeks.
- potato.quest.intro.jump.5: But all we could manage is sneaking into this April Fools' Snapshot.
- potato.quest.intro.jump.6: And now you've discovered us.
- potato.quest.intro.jump.7: Do you have any idea how difficult it is to write Java code?
- potato.quest.intro.jump.8: It's not as simple as copying samples from the internet.
- potato.quest.intro.jump.9: There's also a lot of pasting involved.
- potato.quest.leaving_village.jump.0: Woah, woah, woah. You need to rest your tired feet, remember?
- potato.quest.leaving_village.jump.1: Let's go back to that Village and take a Bed.
- potato.quest.meta_one.jump.0: By the way-
- potato.quest.meta_one.jump.1: What do you think of this year's April Fools' joke?
- potato.quest.meta_one.jump.10: And then you jump every now and then.
- potato.quest.meta_one.jump.11: I am only assuming that jumping is a sign of acknowledgement.
- potato.quest.meta_one.jump.12: Perhaps I can modify your inventory...
- potato.quest.meta_one.jump.13: 
- potato.quest.meta_one.jump.2: I preferred the one where you could only pick up a single Block.
- potato.quest.meta_one.jump.3: But this year I think they nailed it.
- potato.quest.meta_one.jump.4: Potatoes!
- potato.quest.meta_one.jump.5: Hilarious.
- potato.quest.meta_one.jump.6: Anyways. I am genuinely interested in your thoughts.
- potato.quest.meta_one.jump.7: ...
- potato.quest.meta_one.jump.8: I'm trying to read your thoughts,
but I don't think we are communicating with telepathy.
- potato.quest.meta_one.jump.9: At least, two-way telepathy. This feels rather unidirectional.
- potato.quest.portal_opened.jump.0: Just as I thought. A portal.
- potato.quest.portal_opened.jump.1: I think you know what happens next.
- potato.quest.portal_opened.jump.2: You're going to waltz on in there, find a Dragon,
and destroy some Potato themed crystals.
- potato.quest.portal_opened.jump.3: This Snapshot is dripping with creativity.
- potato.quest.portal_opened.jump.4: Lucky that I am here to provide commentary and context.
- potato.quest.potato_village.jump.0: Awesome, you're in a Potato Village.
- potato.quest.potato_village.jump.1: This will be our base of operations from here on out.
- potato.quest.potato_village.jump.2: Familiarize yourself with the Villagers.
- potato.quest.potato_village.jump.3: Steal their loot, etc. The usual Minecraft stuff.
- potato.quest.potato_village.jump.4: There's some neat stuff around here.
- potato.quest.potato_village.jump.5: Most of it is Potato themed.
- potato.quest.potato_village.jump.6: But as long as you think Potatoes are neat.
You'll be right at home.
- potato.quest.potato_village.jump.7: Once you're ready:
Throw another one of those Potato Eyes.
- potato.quest.slept_in_bed.jump.0: I'm pretty sure I said TAKE a Bed.
- potato.quest.slept_in_bed.jump.1: Sleeping in a Bed is not the same as taking a Bed.
- potato.quest.slept_in_bed.jump.2: If I had meant that, I would have said:
"Hey %1$s. You should TAKE a nap".
- potato.quest.slept_in_bed.jump.3: 
- potato.quest.thrown_eye_part_two.jump.0: On the road, once again.
- potato.quest.thrown_eye_part_two.jump.1: This time we're looking for a dangerous place.
- potato.quest.thrown_eye_part_two.jump.2: It'll be a battle against the ultimate Potato.
- potato.quest.thrown_eye_part_two.jump.3: That's all the information I have.
- potato.quest.thrown_eye_part_two.jump.4: If I were to guess: It's probably a Maris Piper.
- potato.quest.thrown_eye_part_two.jump.5: Known to be the most versatile of the Potatoes.
- potato.quest.thrown_eye_part_two.jump.6: It's worth going in with the right tools.
- potato.quest.thrown_eye_part_two.jump.7: Sharpen up some swords, boil up some potions.
- potato.quest.thrown_eye_part_two.jump.8: Don't forget to also cook up some potatoes.
- potato.quest.thrown_eye_part_two.jump.9: We're certainly not lacking for potatoes here.
- potato.quest.thrown_eye.jump.0: Excellent.
- potato.quest.thrown_eye.jump.1: It looks like a developer copy-pasted the Ender Eye code for this.
- potato.quest.thrown_eye.jump.10: Do you think the Developers are hiding somewhere in this Snapshot?
- potato.quest.thrown_eye.jump.11: Maybe we will meet one!
- potato.quest.thrown_eye.jump.12: You should take my Minecraft ideas to show them.
- potato.quest.thrown_eye.jump.13: 
- potato.quest.thrown_eye.jump.2: That means there's a chance these Potato Eyes could break.
- potato.quest.thrown_eye.jump.3: Remember to craft more if you lose a Potato Eye.
- potato.quest.thrown_eye.jump.4: Wow a Minecraft adventure. This is exciting.
- potato.quest.thrown_eye.jump.5: I wonder what the deal is with the Potatoes?
- potato.quest.thrown_eye.jump.6: Perhaps the Developers REALLY like Potatoes.
- potato.quest.thrown_eye.jump.7: At least, the Poisonous ones.
- potato.quest.thrown_eye.jump.8: Poisonous Potatoes, that is.
- potato.quest.thrown_eye.jump.9: Not Poisonous Developers.
- potato.quest.took_bed.jump.0: Did I say take a Bed? I think I meant to say "Take a nap".
- potato.quest.took_bed.jump.1: 
- potato.quest.wrote_thoughts.jump.0: I don't think I can read this Paper.
- potato.quest.wrote_thoughts.jump.1: My Potato eyes aren't suitable for reading.
- potato.quest.wrote_thoughts.jump.10: And I think that page was the appendix.
- potato.quest.wrote_thoughts.jump.11: The first item in the appendix will be your take on this Snapshot.
- potato.quest.wrote_thoughts.jump.12: You must be wondering what this report is about.
- potato.quest.wrote_thoughts.jump.13: It pertains as to why I am here in Minecraft.
- potato.quest.wrote_thoughts.jump.14: And that information is CLASSIFIED.
- potato.quest.wrote_thoughts.jump.15: But I will hint that it involves the Poisonous Potato.
- potato.quest.wrote_thoughts.jump.16: We believe there is some significance to the Poisonous Potato.
- potato.quest.wrote_thoughts.jump.17: And from analysis of the Minecraft code...
- potato.quest.wrote_thoughts.jump.18: We believe you should try cutting out the eyes.
- potato.quest.wrote_thoughts.jump.19: Or more accurately: Craft out the Potato Eyes.
- potato.quest.wrote_thoughts.jump.2: Remember what I said about not being able to see?
- potato.quest.wrote_thoughts.jump.20: Go on %1$s.
Craft Potato Eyes from a Poisonous Potato.
- potato.quest.wrote_thoughts.jump.3: Nothing has changed in that department.
- potato.quest.wrote_thoughts.jump.4: I will assume that you are VERY enthusiastic about the Snapshot.
- potato.quest.wrote_thoughts.jump.5: It will be on page 1 of my report.
- potato.quest.wrote_thoughts.jump.6: "%1$s really likes the Poisonous Potato themed jokes."
- potato.quest.wrote_thoughts.jump.7: There. It's in my report.
- potato.quest.wrote_thoughts.jump.8: Actually I might need that Paper back.
- potato.quest.wrote_thoughts.jump.9: I tore it from the back of my report.
- screen.fletching.title: Fletching %s into %s
- stat.minecraft.get_peeled: Times Peeled
- stat.minecraft.interact_with_fletching: Interactions with Fletching Table
- stat.minecraft.potato_quest_time_format: Completion Time: %s
- stat.minecraft.potato_quest_time: Potato Quest Time
- stat.minecraft.said_potato: "Potato" utterances
+ subtitles.block.trial_spawner.about_to_spawn_item: Ominous item prepares
+ subtitles.block.trial_spawner.ambient_charged: Ominous Trial Spawner crackles
+ subtitles.block.trial_spawner.charge_activate: Omen engulfs Trial Spawner
+ subtitles.block.trial_spawner.spawn_item_begin: Ominous item appears
+ subtitles.block.trial_spawner.spawn_item: Ominous item drops
- subtitles.entity.megaspud.challenge: Mega Spud challenges you
- subtitles.entity.megaspud.death: Mega Spud peels away
- subtitles.entity.megaspud.fireball: Mega Spud fires
- subtitles.entity.megaspud.hurt: Mega Spud is peeled
- subtitles.entity.megaspud.idle: Mega Spud plays big
- subtitles.entity.megaspud.squish: Mega Spud flops
- subtitles.entity.megaspud.step: Mega Spud stomps
- subtitles.entity.megaspud.summon: Mega Spud spawns minions
- subtitles.entity.megaspud.upset: Mega Spud is upset
- subtitles.entity.plaguewhale.ambient_land: Plaguewhale Slab slaps
- subtitles.entity.plaguewhale.ambient: Plaguewhale Slab zooms
- subtitles.entity.plaguewhale.curse: Plaguewhale Slab curses
- subtitles.entity.plaguewhale.death: Plaguewhale Slab dies
- subtitles.entity.plaguewhale.flop: Plaguewhale Slab flips
- subtitles.entity.plaguewhale.hurt: Plaguewhale Slab hurts
- subtitles.entity.player.sprout_respawn_one: Ground rumbles...
- subtitles.entity.player.sprout_respawn_two: Player sprouts out of the ground!
- subtitles.entity.player.sprout_respawn: Player sprouts out of the ground!
- subtitles.entity.toxifin.ambient_land: Toxifin Slab slaps
- subtitles.entity.toxifin.ambient: Toxifin Slab zooms
- subtitles.entity.toxifin.attack: Toxifin Slab zaps
- subtitles.entity.toxifin.death: Toxifin Slab dies
- subtitles.entity.toxifin.flop: Toxifin Slab flips
- subtitles.entity.toxifin.hurt: Toxifin Slab hurts
- subtitles.entity.zombie_potato.ambient: Potato Zombie groans
- subtitles.entity.zombie_potato.attack_iron_door: Potato Zombie breaks Iron Door
- subtitles.entity.zombie_potato.death: Potato Zombie dies
- subtitles.entity.zombie_potato.hurt: Potato Zombie hurts
- subtitles.entity.zombie_potato.infect: Potato Zombie infects
- subtitles.entity.zombie_potato.step: Potato Zombie steps
+ subtitles.event.mob_effect.bad_omen: Omen takes hold
+ subtitles.event.mob_effect.raid_omen: Raid looms nearby
+ subtitles.event.mob_effect.trial_omen: Ominous trial looms nearby
+ subtitles.item.ominous_bottle.dispose: Bottle breaks
- subtitles.item.potato.chips: Crispy crunch!
- subtitles.item.potato.peel: Potato gets peeled
- the.player: the Player
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>24w14potato</th><th>24w14a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.under_lock_and_key.description</div></th><td>Use a Trial Key on a Vault</td><td>Unlock a Vault with a Trial Key</td></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.who_needs_rockets.description</div></th><td>Use a Wind Charge to launch yourself upward 7 blocks</td><td>Use a Wind Charge to launch yourself upward 8 blocks</td></tr>
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
- reports/biome_parameters/minecraft/potato.json
```

</details>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancements/potato/all_potatoed.json
- minecraft/advancements/potato/bring_home_the_corruption.json
- minecraft/advancements/potato/craft_poisonous_potato_chips.json
- minecraft/advancements/potato/craft_poisonous_potato_fries.json
- minecraft/advancements/potato/craft_poisonous_potato_slices.json
- minecraft/advancements/potato/craft_poisonous_potato_sticks.json
- minecraft/advancements/potato/eat_armor.json
- minecraft/advancements/potato/enter_the_potato.json
- minecraft/advancements/potato/get_oily.json
- minecraft/advancements/potato/get_peeled.json
- minecraft/advancements/potato/good_plant.json
- minecraft/advancements/potato/lubricate_boots.json
- minecraft/advancements/potato/lubricate_whee.json
- minecraft/advancements/potato/lubricate.json
- minecraft/advancements/potato/mega_lubricate_whee.json
- minecraft/advancements/potato/mega_lubricate.json
- minecraft/advancements/potato/peel_all_the_things.json
- minecraft/advancements/potato/poisonous_potato_gourmet.json
- minecraft/advancements/potato/poisonous_potato_taster.json
- minecraft/advancements/potato/potato_peeler.json
- minecraft/advancements/potato/root.json
- minecraft/advancements/potato/rumbled.json
- minecraft/advancements/potato/sweet_potato_talker.json
- minecraft/advancements/potato/well_done.json
- minecraft/advancements/recipes/building_blocks/amber_block.json
- minecraft/advancements/recipes/building_blocks/baked_potato_brick_slab_from_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/baked_potato_brick_slab.json
- minecraft/advancements/recipes/building_blocks/baked_potato_brick_stairs_from_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/baked_potato_brick_stairs.json
- minecraft/advancements/recipes/building_blocks/baked_potato_brick_wall_from_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/baked_potato_bricks.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_brick_slab_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_brick_slab.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_brick_stairs_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_brick_stairs.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_brick_wall_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/charred_baked_potato_bricks.json
- minecraft/advancements/recipes/building_blocks/compressed_poisonous_potato_block.json
- minecraft/advancements/recipes/building_blocks/double_compressed_poisonous_potato_block.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_brick_slab_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_brick_slab.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_brick_stairs_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_brick_stairs.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_brick_wall_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/expired_baked_potato_bricks.json
- minecraft/advancements/recipes/building_blocks/floatato.json
- minecraft/advancements/recipes/building_blocks/poisonous_potato_block.json
- minecraft/advancements/recipes/building_blocks/potato_planks.json
- minecraft/advancements/recipes/building_blocks/potato_slab.json
- minecraft/advancements/recipes/building_blocks/potato_stairs.json
- minecraft/advancements/recipes/building_blocks/potone_slab_from_potone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/potone_slab.json
- minecraft/advancements/recipes/building_blocks/potone_stairs_from_potone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/potone_stairs.json
- minecraft/advancements/recipes/building_blocks/potone_wall_from_potone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/potone.json
- minecraft/advancements/recipes/building_blocks/quadruple_compressed_poisonous_potato_block.json
- minecraft/advancements/recipes/building_blocks/taterstone_slab_from_taterstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/taterstone_slab.json
- minecraft/advancements/recipes/building_blocks/taterstone_stairs_from_taterstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/taterstone_stairs.json
- minecraft/advancements/recipes/building_blocks/taterstone_wall_from_taterstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/triple_compressed_poisonous_potato_block.json
- minecraft/advancements/recipes/combat/big_brain.json
- minecraft/advancements/recipes/combat/poisonous_pota_toes.json
- minecraft/advancements/recipes/combat/poisonous_potato_chestplate.json
- minecraft/advancements/recipes/combat/vicious_potato.json
- minecraft/advancements/recipes/decorations/baked_potato_brick_wall.json
- minecraft/advancements/recipes/decorations/charred_baked_potato_brick_wall.json
- minecraft/advancements/recipes/decorations/expired_baked_potato_brick_wall.json
- minecraft/advancements/recipes/decorations/poisonous_potato_cutter.json
- minecraft/advancements/recipes/decorations/potato_fence.json
- minecraft/advancements/recipes/decorations/potato_hanging_sign.json
- minecraft/advancements/recipes/decorations/potato_sign.json
- minecraft/advancements/recipes/decorations/potone_wall.json
- minecraft/advancements/recipes/decorations/taterstone_wall.json
- minecraft/advancements/recipes/food/baked_potato_bricks_from_terredepomme.json
- minecraft/advancements/recipes/food/compressed_poisonous_potato_block_from_double_compressed_poisonous_potato_block_unpacking.json
- minecraft/advancements/recipes/food/double_compressed_poisonous_potato_block_from_triple_compressed_poisonous_potato_block_unpacking.json
- minecraft/advancements/recipes/food/enchanted_golden_poisonous_potato.json
- minecraft/advancements/recipes/food/golden_poisonous_potato.json
- minecraft/advancements/recipes/food/hash_browns_from_campfire_cooking.json
- minecraft/advancements/recipes/food/hot_potato.json
- minecraft/advancements/recipes/food/poisonous_potato_block_from_compressed_poisonous_potato_block_unpacking.json
- minecraft/advancements/recipes/food/poisonous_potato_chips_from_campfire_cooking.json
- minecraft/advancements/recipes/food/poisonous_potato_chips_from_smoking.json
- minecraft/advancements/recipes/food/poisonous_potato_chips.json
- minecraft/advancements/recipes/food/poisonous_potato_fries_from_campfire_cooking.json
- minecraft/advancements/recipes/food/poisonous_potato_fries_from_smoking.json
- minecraft/advancements/recipes/food/poisonous_potato_fries.json
- minecraft/advancements/recipes/food/poisonous_potato_from_poisonous_potato_block_unpacking.json
- minecraft/advancements/recipes/food/poisonous_potato_slices_from_poisonous_potato_poisonous_potato_cutting.json
- minecraft/advancements/recipes/food/poisonous_potato_sticks_from_poisonous_potato_poisonous_potato_cutting.json
- minecraft/advancements/recipes/food/triple_compressed_poisonous_potato_block_from_quadruple_compressed_poisonous_potato_block_unpacking.json
- minecraft/advancements/recipes/misc/amber_gem.json
- minecraft/advancements/recipes/misc/black_potato_peels_block.json
- minecraft/advancements/recipes/misc/black_potato_peels.json
- minecraft/advancements/recipes/misc/blue_potato_peels_block.json
- minecraft/advancements/recipes/misc/blue_potato_peels.json
- minecraft/advancements/recipes/misc/brown_potato_peels_block.json
- minecraft/advancements/recipes/misc/brown_potato_peels.json
- minecraft/advancements/recipes/misc/corrupted_potato_peels.json
- minecraft/advancements/recipes/misc/cyan_potato_peels_block.json
- minecraft/advancements/recipes/misc/cyan_potato_peels.json
- minecraft/advancements/recipes/misc/gray_potato_peels_block.json
- minecraft/advancements/recipes/misc/gray_potato_peels.json
- minecraft/advancements/recipes/misc/green_potato_peels_block.json
- minecraft/advancements/recipes/misc/green_potato_peels.json
- minecraft/advancements/recipes/misc/light_blue_potato_peels_block.json
- minecraft/advancements/recipes/misc/light_blue_potato_peels.json
- minecraft/advancements/recipes/misc/light_gray_potato_peels_block.json
- minecraft/advancements/recipes/misc/light_gray_potato_peels.json
- minecraft/advancements/recipes/misc/lime_potato_peels_block.json
- minecraft/advancements/recipes/misc/lime_potato_peels.json
- minecraft/advancements/recipes/misc/magenta_potato_peels_block.json
- minecraft/advancements/recipes/misc/magenta_potato_peels.json
- minecraft/advancements/recipes/misc/orange_potato_peels_block.json
- minecraft/advancements/recipes/misc/orange_potato_peels.json
- minecraft/advancements/recipes/misc/overcooked_potatoes.json
- minecraft/advancements/recipes/misc/pink_potato_peels_block.json
- minecraft/advancements/recipes/misc/pink_potato_peels.json
- minecraft/advancements/recipes/misc/poisonous_polytra.json
- minecraft/advancements/recipes/misc/potato_eye.json
- minecraft/advancements/recipes/misc/potato_hammer.json
- minecraft/advancements/recipes/misc/potato_peels_block.json
- minecraft/advancements/recipes/misc/potato_peels.json
- minecraft/advancements/recipes/misc/purple_potato_peels_block.json
- minecraft/advancements/recipes/misc/purple_potato_peels.json
- minecraft/advancements/recipes/misc/red_potato_peels_block.json
- minecraft/advancements/recipes/misc/red_potato_peels.json
- minecraft/advancements/recipes/misc/toxic_resin.json
- minecraft/advancements/recipes/misc/yellow_potato_peels_block.json
- minecraft/advancements/recipes/misc/yellow_potato_peels.json
- minecraft/advancements/recipes/redstone/floatater.json
- minecraft/advancements/recipes/redstone/potato_battery.json
- minecraft/advancements/recipes/redstone/potato_button.json
- minecraft/advancements/recipes/redstone/potato_door.json
- minecraft/advancements/recipes/redstone/potato_fence_gate.json
- minecraft/advancements/recipes/redstone/potato_pressure_plate.json
- minecraft/advancements/recipes/redstone/potato_trapdoor.json
- minecraft/advancements/recipes/tools/corrupted_potato_peels_block.json
- minecraft/advancements/recipes/tools/frying_table.json
- minecraft/advancements/recipes/tools/lashing_potato.json
- minecraft/advancements/recipes/tools/potato_peeler.json
- minecraft/advancements/recipes/tools/potato_refinery.json
- minecraft/advancements/recipes/tools/trident.json
- minecraft/damage_type/potato_heat.json
- minecraft/damage_type/potato_magic.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/chests/trial_chambers/reward_ominous_common.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/chests/trial_chambers/reward_ominous_rare.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/chests/trial_chambers/reward_ominous_unique.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/chests/trial_chambers/reward_ominous.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/entities/pillager.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/equipment/trial_chamber.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/spawners/ominous/trial_chamber/consumables.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/spawners/ominous/trial_chamber/key.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/spawners/trial_chamber/items_to_drop_when_ominous.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/entity_types/immune_to_infested.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/entity_types/immune_to_oozing.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/enchantable/durability.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/enchantable/fire_aspect.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/enchantable/mace.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/enchantable/vanishing.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/enchantable/weapon.json
+ minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/atrium.json
+ minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/chamber/eruption.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/corridor/first.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/corridor/first/straight.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/corridor/second.json
+ minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/corridor/slices.json
+ minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/reward/ominous_vault.json
- minecraft/dimension_type/potato.json
- minecraft/loot_tables/blocks/amber_block.json
- minecraft/loot_tables/blocks/baked_potato_brick_slab.json
- minecraft/loot_tables/blocks/baked_potato_brick_stairs.json
- minecraft/loot_tables/blocks/baked_potato_brick_wall.json
- minecraft/loot_tables/blocks/baked_potato_bricks.json
- minecraft/loot_tables/blocks/big_brain.json
- minecraft/loot_tables/blocks/black_potato_peels_block.json
- minecraft/loot_tables/blocks/blue_potato_peels_block.json
- minecraft/loot_tables/blocks/brown_potato_peels_block.json
- minecraft/loot_tables/blocks/charred_baked_potato_brick_slab.json
- minecraft/loot_tables/blocks/charred_baked_potato_brick_stairs.json
- minecraft/loot_tables/blocks/charred_baked_potato_brick_wall.json
- minecraft/loot_tables/blocks/charred_baked_potato_bricks.json
- minecraft/loot_tables/blocks/compressed_poisonous_potato_block.json
- minecraft/loot_tables/blocks/corrupted_peelgrass_block.json
- minecraft/loot_tables/blocks/corrupted_potato_peels_block.json
- minecraft/loot_tables/blocks/cyan_potato_peels_block.json
- minecraft/loot_tables/blocks/deepslate_poisonous_potato_ore.json
- minecraft/loot_tables/blocks/double_compressed_poisonous_potato_block.json
- minecraft/loot_tables/blocks/expired_baked_potato_brick_slab.json
- minecraft/loot_tables/blocks/expired_baked_potato_brick_stairs.json
- minecraft/loot_tables/blocks/expired_baked_potato_brick_wall.json
- minecraft/loot_tables/blocks/expired_baked_potato_bricks.json
- minecraft/loot_tables/blocks/floatater.json
- minecraft/loot_tables/blocks/floatato.json
- minecraft/loot_tables/blocks/frying_table.json
- minecraft/loot_tables/blocks/gravtater.json
- minecraft/loot_tables/blocks/gray_potato_peels_block.json
- minecraft/loot_tables/blocks/green_potato_peels_block.json
- minecraft/loot_tables/blocks/light_blue_potato_peels_block.json
- minecraft/loot_tables/blocks/light_gray_potato_peels_block.json
- minecraft/loot_tables/blocks/lime_potato_peels_block.json
- minecraft/loot_tables/blocks/magenta_potato_peels_block.json
- minecraft/loot_tables/blocks/orange_potato_peels_block.json
- minecraft/loot_tables/blocks/pedestal.json
- minecraft/loot_tables/blocks/peelgrass_block.json
- minecraft/loot_tables/blocks/pink_potato_peels_block.json
- minecraft/loot_tables/blocks/poison_farmland.json
- minecraft/loot_tables/blocks/poison_path.json
- minecraft/loot_tables/blocks/poisonous_mashed_potato.json
- minecraft/loot_tables/blocks/poisonous_potato_block.json
- minecraft/loot_tables/blocks/poisonous_potato_cutter.json
- minecraft/loot_tables/blocks/poisonous_potato_ore.json
- minecraft/loot_tables/blocks/poisonous_potato_zombie_head_block.json
- minecraft/loot_tables/blocks/poisonous_potato_zombie_head_hat.json
- minecraft/loot_tables/blocks/potato_battery.json
- minecraft/loot_tables/blocks/potato_bud.json
- minecraft/loot_tables/blocks/potato_button.json
- minecraft/loot_tables/blocks/potato_door.json
- minecraft/loot_tables/blocks/potato_fence_gate.json
- minecraft/loot_tables/blocks/potato_fence.json
- minecraft/loot_tables/blocks/potato_flower.json
- minecraft/loot_tables/blocks/potato_fruit.json
- minecraft/loot_tables/blocks/potato_hanging_sign.json
- minecraft/loot_tables/blocks/potato_leaves.json
- minecraft/loot_tables/blocks/potato_pedicule.json
- minecraft/loot_tables/blocks/potato_peels_block.json
- minecraft/loot_tables/blocks/potato_planks.json
- minecraft/loot_tables/blocks/potato_portal.json
- minecraft/loot_tables/blocks/potato_pressure_plate.json
- minecraft/loot_tables/blocks/potato_refinery.json
- minecraft/loot_tables/blocks/potato_sign.json
- minecraft/loot_tables/blocks/potato_slab.json
- minecraft/loot_tables/blocks/potato_sprouts.json
- minecraft/loot_tables/blocks/potato_stairs.json
- minecraft/loot_tables/blocks/potato_stem.json
- minecraft/loot_tables/blocks/potato_trapdoor.json
- minecraft/loot_tables/blocks/potone_copper_ore.json
- minecraft/loot_tables/blocks/potone_diamond_ore.json
- minecraft/loot_tables/blocks/potone_gold_ore.json
- minecraft/loot_tables/blocks/potone_iron_ore.json
- minecraft/loot_tables/blocks/potone_lapis_ore.json
- minecraft/loot_tables/blocks/potone_redstone_ore.json
- minecraft/loot_tables/blocks/potone_slab.json
- minecraft/loot_tables/blocks/potone_stairs.json
- minecraft/loot_tables/blocks/potone_wall.json
- minecraft/loot_tables/blocks/potone.json
- minecraft/loot_tables/blocks/potted_potato_flower.json
- minecraft/loot_tables/blocks/powerful_potato.json
- minecraft/loot_tables/blocks/purple_potato_peels_block.json
- minecraft/loot_tables/blocks/quadruple_compressed_poisonous_potato_block.json
- minecraft/loot_tables/blocks/red_potato_peels_block.json
- minecraft/loot_tables/blocks/resin_ore.json
- minecraft/loot_tables/blocks/strong_roots.json
- minecraft/loot_tables/blocks/taterstone_slab.json
- minecraft/loot_tables/blocks/taterstone_stairs.json
- minecraft/loot_tables/blocks/taterstone_wall.json
- minecraft/loot_tables/blocks/taterstone.json
- minecraft/loot_tables/blocks/terredepomme.json
- minecraft/loot_tables/blocks/triple_compressed_poisonous_potato_block.json
- minecraft/loot_tables/blocks/vicious_potato.json
- minecraft/loot_tables/blocks/weak_roots.json
- minecraft/loot_tables/blocks/yellow_potato_peels_block.json
- minecraft/loot_tables/chests/ruined_portatol.json
- minecraft/loot_tables/chests/simple_dungeon_potato.json
+ minecraft/loot_tables/chests/trial_chambers/reward_ominous_common.json
+ minecraft/loot_tables/chests/trial_chambers/reward_ominous_rare.json
+ minecraft/loot_tables/chests/trial_chambers/reward_ominous_unique.json
+ minecraft/loot_tables/chests/trial_chambers/reward_ominous.json
- minecraft/loot_tables/chests/village/village_potato_house.json
- minecraft/loot_tables/entities/batato.json
- minecraft/loot_tables/entities/mega_spud.json
- minecraft/loot_tables/entities/plaguewhale.json
- minecraft/loot_tables/entities/poisonous_potato_zombie.json
- minecraft/loot_tables/entities/sheep/potato/black.json
- minecraft/loot_tables/entities/sheep/potato/blue.json
- minecraft/loot_tables/entities/sheep/potato/brown.json
- minecraft/loot_tables/entities/sheep/potato/cyan.json
- minecraft/loot_tables/entities/sheep/potato/gray.json
- minecraft/loot_tables/entities/sheep/potato/green.json
- minecraft/loot_tables/entities/sheep/potato/light_blue.json
- minecraft/loot_tables/entities/sheep/potato/light_gray.json
- minecraft/loot_tables/entities/sheep/potato/lime.json
- minecraft/loot_tables/entities/sheep/potato/magenta.json
- minecraft/loot_tables/entities/sheep/potato/orange.json
- minecraft/loot_tables/entities/sheep/potato/pink.json
- minecraft/loot_tables/entities/sheep/potato/purple.json
- minecraft/loot_tables/entities/sheep/potato/red.json
- minecraft/loot_tables/entities/sheep/potato/white.json
- minecraft/loot_tables/entities/sheep/potato/yellow.json
- minecraft/loot_tables/entities/toxifin.json
+ minecraft/loot_tables/equipment/trial_chamber.json
+ minecraft/loot_tables/spawners/ominous/trial_chamber/consumables.json
+ minecraft/loot_tables/spawners/ominous/trial_chamber/key.json
+ minecraft/loot_tables/spawners/trial_chamber/items_to_drop_when_ominous.json
- minecraft/recipes/amber_block.json
- minecraft/recipes/amber_gem.json
- minecraft/recipes/baked_potato_brick_slab_from_baked_potato_bricks_stonecutting.json
- minecraft/recipes/baked_potato_brick_slab.json
- minecraft/recipes/baked_potato_brick_stairs_from_baked_potato_bricks_stonecutting.json
- minecraft/recipes/baked_potato_brick_stairs.json
- minecraft/recipes/baked_potato_brick_wall_from_baked_potato_bricks_stonecutting.json
- minecraft/recipes/baked_potato_brick_wall.json
- minecraft/recipes/baked_potato_bricks_from_terredepomme.json
- minecraft/recipes/baked_potato_bricks.json
- minecraft/recipes/big_brain.json
- minecraft/recipes/black_potato_peels_block.json
- minecraft/recipes/black_potato_peels.json
- minecraft/recipes/blue_potato_peels_block.json
- minecraft/recipes/blue_potato_peels.json
- minecraft/recipes/brown_potato_peels_block.json
- minecraft/recipes/brown_potato_peels.json
- minecraft/recipes/charred_baked_potato_brick_slab_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/recipes/charred_baked_potato_brick_slab.json
- minecraft/recipes/charred_baked_potato_brick_stairs_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/recipes/charred_baked_potato_brick_stairs.json
- minecraft/recipes/charred_baked_potato_brick_wall_from_charred_baked_potato_bricks_stonecutting.json
- minecraft/recipes/charred_baked_potato_brick_wall.json
- minecraft/recipes/charred_baked_potato_bricks.json
- minecraft/recipes/compressed_poisonous_potato_block_from_double_compressed_poisonous_potato_block_unpacking.json
- minecraft/recipes/compressed_poisonous_potato_block.json
- minecraft/recipes/corrupted_potato_peels_block.json
- minecraft/recipes/corrupted_potato_peels.json
- minecraft/recipes/cyan_potato_peels_block.json
- minecraft/recipes/cyan_potato_peels.json
- minecraft/recipes/double_compressed_poisonous_potato_block_from_triple_compressed_poisonous_potato_block_unpacking.json
- minecraft/recipes/double_compressed_poisonous_potato_block.json
- minecraft/recipes/enchanted_golden_poisonous_potato.json
- minecraft/recipes/expired_baked_potato_brick_slab_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/recipes/expired_baked_potato_brick_slab.json
- minecraft/recipes/expired_baked_potato_brick_stairs_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/recipes/expired_baked_potato_brick_stairs.json
- minecraft/recipes/expired_baked_potato_brick_wall_from_expired_baked_potato_bricks_stonecutting.json
- minecraft/recipes/expired_baked_potato_brick_wall.json
- minecraft/recipes/expired_baked_potato_bricks.json
- minecraft/recipes/floatater.json
- minecraft/recipes/floatato.json
- minecraft/recipes/frying_table.json
- minecraft/recipes/golden_poisonous_potato.json
- minecraft/recipes/gray_potato_peels_block.json
- minecraft/recipes/gray_potato_peels.json
- minecraft/recipes/green_potato_peels_block.json
- minecraft/recipes/green_potato_peels.json
- minecraft/recipes/hash_browns_from_campfire_cooking.json
- minecraft/recipes/hot_potato.json
- minecraft/recipes/lashing_potato.json
- minecraft/recipes/light_blue_potato_peels_block.json
- minecraft/recipes/light_blue_potato_peels.json
- minecraft/recipes/light_gray_potato_peels_block.json
- minecraft/recipes/light_gray_potato_peels.json
- minecraft/recipes/lime_potato_peels_block.json
- minecraft/recipes/lime_potato_peels.json
- minecraft/recipes/magenta_potato_peels_block.json
- minecraft/recipes/magenta_potato_peels.json
- minecraft/recipes/orange_potato_peels_block.json
- minecraft/recipes/orange_potato_peels.json
- minecraft/recipes/overcooked_potatoes.json
- minecraft/recipes/pink_potato_peels_block.json
- minecraft/recipes/pink_potato_peels.json
- minecraft/recipes/poisonous_polytra.json
- minecraft/recipes/poisonous_pota_toes.json
- minecraft/recipes/poisonous_potato_block_from_compressed_poisonous_potato_block_unpacking.json
- minecraft/recipes/poisonous_potato_block.json
- minecraft/recipes/poisonous_potato_chestplate.json
- minecraft/recipes/poisonous_potato_chips_from_campfire_cooking.json
- minecraft/recipes/poisonous_potato_chips_from_smoking.json
- minecraft/recipes/poisonous_potato_chips.json
- minecraft/recipes/poisonous_potato_cutter.json
- minecraft/recipes/poisonous_potato_fries_from_campfire_cooking.json
- minecraft/recipes/poisonous_potato_fries_from_smoking.json
- minecraft/recipes/poisonous_potato_fries.json
- minecraft/recipes/poisonous_potato_from_poisonous_potato_block_unpacking.json
- minecraft/recipes/poisonous_potato_oil_with_poisonous_potato_oil_from_potato_refinement.json
- minecraft/recipes/poisonous_potato_slices_from_poisonous_potato_poisonous_potato_cutting.json
- minecraft/recipes/poisonous_potato_sticks_from_poisonous_potato_poisonous_potato_cutting.json
- minecraft/recipes/potato_battery.json
- minecraft/recipes/potato_button.json
- minecraft/recipes/potato_door.json
- minecraft/recipes/potato_eye.json
- minecraft/recipes/potato_fence_gate.json
- minecraft/recipes/potato_fence.json
- minecraft/recipes/potato_hammer.json
- minecraft/recipes/potato_hanging_sign.json
- minecraft/recipes/potato_oil_with_potato_oil_from_potato_refinement.json
- minecraft/recipes/potato_peeler.json
- minecraft/recipes/potato_peels_block.json
- minecraft/recipes/potato_peels.json
- minecraft/recipes/potato_planks.json
- minecraft/recipes/potato_pressure_plate.json
- minecraft/recipes/potato_refinery.json
- minecraft/recipes/potato_sign.json
- minecraft/recipes/potato_slab.json
- minecraft/recipes/potato_stairs.json
- minecraft/recipes/potato_trapdoor.json
- minecraft/recipes/potone_slab_from_potone_stonecutting.json
- minecraft/recipes/potone_slab.json
- minecraft/recipes/potone_stairs_from_potone_stonecutting.json
- minecraft/recipes/potone_stairs.json
- minecraft/recipes/potone_wall_from_potone_stonecutting.json
- minecraft/recipes/potone_wall.json
- minecraft/recipes/potone.json
- minecraft/recipes/purple_potato_peels_block.json
- minecraft/recipes/purple_potato_peels.json
- minecraft/recipes/quadruple_compressed_poisonous_potato_block.json
- minecraft/recipes/red_potato_peels_block.json
- minecraft/recipes/red_potato_peels.json
- minecraft/recipes/taterstone_slab_from_taterstone_stonecutting.json
- minecraft/recipes/taterstone_slab.json
- minecraft/recipes/taterstone_stairs_from_taterstone_stonecutting.json
- minecraft/recipes/taterstone_stairs.json
- minecraft/recipes/taterstone_wall_from_taterstone_stonecutting.json
- minecraft/recipes/taterstone_wall.json
- minecraft/recipes/toxic_resin.json
- minecraft/recipes/trident.json
- minecraft/recipes/triple_compressed_poisonous_potato_block_from_quadruple_compressed_poisonous_potato_block_unpacking.json
- minecraft/recipes/triple_compressed_poisonous_potato_block.json
- minecraft/recipes/vicious_potato.json
- minecraft/recipes/yellow_potato_peels_block.json
- minecraft/recipes/yellow_potato_peels.json
- minecraft/structures/colosseum/mobs/mega_spud.nbt
- minecraft/structures/colosseum/mobs/plaguewhale.nbt
- minecraft/structures/colosseum/mobs/toxifin.nbt
- minecraft/structures/colosseum/treasure/bases/centers/center_0.nbt
- minecraft/structures/colosseum/treasure/bases/centers/center_1.nbt
- minecraft/structures/colosseum/treasure/bases/centers/center_2.nbt
- minecraft/structures/colosseum/treasure/bases/centers/center_3.nbt
- minecraft/structures/colosseum/treasure/bases/lava_basin.nbt
- minecraft/structures/colosseum/treasure/big_air_full.nbt
- minecraft/structures/colosseum/treasure/brains/center_brain.nbt
- minecraft/structures/colosseum/treasure/connectors/center_to_wall_middle.nbt
- minecraft/structures/colosseum/treasure/connectors/center_to_wall_top_entrance.nbt
- minecraft/structures/colosseum/treasure/connectors/center_to_wall_top.nbt
- minecraft/structures/colosseum/treasure/corners/bottom/corner_0.nbt
- minecraft/structures/colosseum/treasure/corners/bottom/corner_1.nbt
- minecraft/structures/colosseum/treasure/corners/edges/bottom.nbt
- minecraft/structures/colosseum/treasure/corners/edges/middle.nbt
- minecraft/structures/colosseum/treasure/corners/edges/top.nbt
- minecraft/structures/colosseum/treasure/corners/middle/corner_0.nbt
- minecraft/structures/colosseum/treasure/corners/middle/corner_1.nbt
- minecraft/structures/colosseum/treasure/corners/top/corner_0.nbt
- minecraft/structures/colosseum/treasure/corners/top/corner_1.nbt
- minecraft/structures/colosseum/treasure/extensions/empty.nbt
- minecraft/structures/colosseum/treasure/extensions/fire_room.nbt
- minecraft/structures/colosseum/treasure/extensions/house_0.nbt
- minecraft/structures/colosseum/treasure/extensions/house_1.nbt
- minecraft/structures/colosseum/treasure/extensions/large_bridge_0.nbt
- minecraft/structures/colosseum/treasure/extensions/large_bridge_1.nbt
- minecraft/structures/colosseum/treasure/extensions/large_bridge_2.nbt
- minecraft/structures/colosseum/treasure/extensions/large_bridge_3.nbt
- minecraft/structures/colosseum/treasure/extensions/roofed_bridge.nbt
- minecraft/structures/colosseum/treasure/extensions/small_bridge_0.nbt
- minecraft/structures/colosseum/treasure/extensions/small_bridge_1.nbt
- minecraft/structures/colosseum/treasure/extensions/small_bridge_2.nbt
- minecraft/structures/colosseum/treasure/extensions/small_bridge_3.nbt
- minecraft/structures/colosseum/treasure/roofs/center_roof.nbt
- minecraft/structures/colosseum/treasure/roofs/corner_roof.nbt
- minecraft/structures/colosseum/treasure/roofs/wall_roof.nbt
- minecraft/structures/colosseum/treasure/stairs/lower_stairs.nbt
- minecraft/structures/colosseum/treasure/walls/bottom/wall_0.nbt
- minecraft/structures/colosseum/treasure/walls/bottom/wall_1.nbt
- minecraft/structures/colosseum/treasure/walls/bottom/wall_2.nbt
- minecraft/structures/colosseum/treasure/walls/bottom/wall_3.nbt
- minecraft/structures/colosseum/treasure/walls/entrance_wall.nbt
- minecraft/structures/colosseum/treasure/walls/lava_wall.nbt
- minecraft/structures/colosseum/treasure/walls/mid/wall_0.nbt
- minecraft/structures/colosseum/treasure/walls/mid/wall_1.nbt
- minecraft/structures/colosseum/treasure/walls/mid/wall_2.nbt
- minecraft/structures/colosseum/treasure/walls/outer/bottom_corner.nbt
- minecraft/structures/colosseum/treasure/walls/outer/medium_outer_wall.nbt
- minecraft/structures/colosseum/treasure/walls/outer/mid_corner.nbt
- minecraft/structures/colosseum/treasure/walls/outer/outer_wall.nbt
- minecraft/structures/colosseum/treasure/walls/outer/tall_outer_wall.nbt
- minecraft/structures/colosseum/treasure/walls/outer/top_corner.nbt
- minecraft/structures/colosseum/treasure/walls/top/main_entrance.nbt
- minecraft/structures/colosseum/treasure/walls/top/wall_0.nbt
- minecraft/structures/colosseum/treasure/walls/top/wall_1.nbt
- minecraft/structures/ruined_portatol/giant_portal_1.nbt
- minecraft/structures/ruined_portatol/giant_portal_2.nbt
- minecraft/structures/ruined_portatol/giant_portal_3.nbt
- minecraft/structures/ruined_portatol/portal_1.nbt
- minecraft/structures/ruined_portatol/portal_10.nbt
- minecraft/structures/ruined_portatol/portal_2.nbt
- minecraft/structures/ruined_portatol/portal_3.nbt
- minecraft/structures/ruined_portatol/portal_4.nbt
- minecraft/structures/ruined_portatol/portal_5.nbt
- minecraft/structures/ruined_portatol/portal_6.nbt
- minecraft/structures/ruined_portatol/portal_7.nbt
- minecraft/structures/ruined_portatol/portal_8.nbt
- minecraft/structures/ruined_portatol/portal_9.nbt
- minecraft/structures/trial_chambers/chamber/chamber_5.nbt
+ minecraft/structures/trial_chambers/chamber/eruption.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/breeze_slice_1.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/center_1.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/quadrant_1.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/quadrant_2.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/quadrant_3.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/quadrant_4.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/quadrant_5.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/slice_1.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/slice_2.nbt
+ minecraft/structures/trial_chambers/chamber/eruption/slice_3.nbt
+ minecraft/structures/trial_chambers/chamber/pedestal/ominous_slice_1.nbt
+ minecraft/structures/trial_chambers/chamber/slanted/ominous_upper_arm_1.nbt
+ minecraft/structures/trial_chambers/corridor/atrium_1.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/bogged_relief.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/breeze_relief.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/grand_staircase_1.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/grand_staircase_2.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/grand_staircase_3.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/spider_relief.nbt
+ minecraft/structures/trial_chambers/corridor/atrium/spiral_relief.nbt
- minecraft/structures/trial_chambers/reward/connectors/default.nbt
- minecraft/structures/trial_chambers/reward/default.nbt
+ minecraft/structures/trial_chambers/reward/ominous_vault.nbt
+ minecraft/structures/trial_chambers/reward/vault.nbt
- minecraft/structures/village/potato/frying_table_1.nbt
- minecraft/structures/village/potato/houses/plains_accessory_1.nbt
- minecraft/structures/village/potato/houses/plains_animal_pen_1.nbt
- minecraft/structures/village/potato/houses/plains_animal_pen_2.nbt
- minecraft/structures/village/potato/houses/plains_animal_pen_3.nbt
- minecraft/structures/village/potato/houses/plains_armorer_house_1.nbt
- minecraft/structures/village/potato/houses/plains_big_house_1.nbt
- minecraft/structures/village/potato/houses/plains_butcher_shop_1.nbt
- minecraft/structures/village/potato/houses/plains_butcher_shop_2.nbt
- minecraft/structures/village/potato/houses/plains_cartographer_1.nbt
- minecraft/structures/village/potato/houses/plains_fisher_cottage_1.nbt
- minecraft/structures/village/potato/houses/plains_fletcher_house_1.nbt
- minecraft/structures/village/potato/houses/plains_large_farm_1.nbt
- minecraft/structures/village/potato/houses/plains_library_1.nbt
- minecraft/structures/village/potato/houses/plains_library_2.nbt
- minecraft/structures/village/potato/houses/plains_masons_house_1.nbt
- minecraft/structures/village/potato/houses/plains_medium_house_1.nbt
- minecraft/structures/village/potato/houses/plains_medium_house_2.nbt
- minecraft/structures/village/potato/houses/plains_meeting_point_4.nbt
- minecraft/structures/village/potato/houses/plains_meeting_point_5.nbt
- minecraft/structures/village/potato/houses/plains_shepherds_house_1.nbt
- minecraft/structures/village/potato/houses/plains_small_farm_1.nbt
- minecraft/structures/village/potato/houses/plains_small_house_1.nbt
- minecraft/structures/village/potato/houses/plains_small_house_2.nbt
- minecraft/structures/village/potato/houses/plains_small_house_3.nbt
- minecraft/structures/village/potato/houses/plains_small_house_4.nbt
- minecraft/structures/village/potato/houses/plains_small_house_5.nbt
- minecraft/structures/village/potato/houses/plains_small_house_6.nbt
- minecraft/structures/village/potato/houses/plains_small_house_7.nbt
- minecraft/structures/village/potato/houses/plains_small_house_8.nbt
- minecraft/structures/village/potato/houses/plains_stable_1.nbt
- minecraft/structures/village/potato/houses/plains_stable_2.nbt
- minecraft/structures/village/potato/houses/plains_tannery_1.nbt
- minecraft/structures/village/potato/houses/plains_temple_3.nbt
- minecraft/structures/village/potato/houses/plains_temple_4.nbt
- minecraft/structures/village/potato/houses/plains_tool_smith_1.nbt
- minecraft/structures/village/potato/houses/plains_weaponsmith_1.nbt
- minecraft/structures/village/potato/houses/potato_maze.nbt
- minecraft/structures/village/potato/plains_lamp_1.nbt
- minecraft/structures/village/potato/streets/corner_01.nbt
- minecraft/structures/village/potato/streets/corner_02.nbt
- minecraft/structures/village/potato/streets/corner_03.nbt
- minecraft/structures/village/potato/streets/crossroad_01.nbt
- minecraft/structures/village/potato/streets/crossroad_02.nbt
- minecraft/structures/village/potato/streets/crossroad_03.nbt
- minecraft/structures/village/potato/streets/crossroad_04.nbt
- minecraft/structures/village/potato/streets/crossroad_05.nbt
- minecraft/structures/village/potato/streets/crossroad_06.nbt
- minecraft/structures/village/potato/streets/straight_01.nbt
- minecraft/structures/village/potato/streets/straight_02.nbt
- minecraft/structures/village/potato/streets/straight_03.nbt
- minecraft/structures/village/potato/streets/straight_04.nbt
- minecraft/structures/village/potato/streets/straight_05.nbt
- minecraft/structures/village/potato/streets/straight_06.nbt
- minecraft/structures/village/potato/streets/turn_01.nbt
- minecraft/structures/village/potato/terminators/terminator_01.nbt
- minecraft/structures/village/potato/terminators/terminator_02.nbt
- minecraft/structures/village/potato/terminators/terminator_03.nbt
- minecraft/structures/village/potato/terminators/terminator_04.nbt
- minecraft/structures/village/potato/town_centers/plains_fountain_01.nbt
- minecraft/structures/village/potato/town_centers/plains_meeting_point_1.nbt
- minecraft/structures/village/potato/town_centers/plains_meeting_point_2.nbt
- minecraft/structures/village/potato/town_centers/plains_meeting_point_3.nbt
- minecraft/structures/village/potato/villagers/baby.nbt
- minecraft/structures/village/potato/villagers/nitwit.nbt
- minecraft/structures/village/potato/villagers/unemployed.nbt
- minecraft/structures/village/potato/well_bottom.nbt
- minecraft/structures/village/potato/zombie/houses/plains_animal_pen_3.nbt
- minecraft/structures/village/potato/zombie/houses/plains_big_house_1.nbt
- minecraft/structures/village/potato/zombie/houses/plains_butcher_shop_2.nbt
- minecraft/structures/village/potato/zombie/houses/plains_fletcher_house_1.nbt
- minecraft/structures/village/potato/zombie/houses/plains_medium_house_1.nbt
- minecraft/structures/village/potato/zombie/houses/plains_medium_house_2.nbt
- minecraft/structures/village/potato/zombie/houses/plains_meeting_point_4.nbt
- minecraft/structures/village/potato/zombie/houses/plains_meeting_point_5.nbt
- minecraft/structures/village/potato/zombie/houses/plains_shepherds_house_1.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_1.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_2.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_3.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_4.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_5.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_6.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_7.nbt
- minecraft/structures/village/potato/zombie/houses/plains_small_house_8.nbt
- minecraft/structures/village/potato/zombie/houses/plains_stable_1.nbt
- minecraft/structures/village/potato/zombie/streets/corner_01.nbt
- minecraft/structures/village/potato/zombie/streets/corner_02.nbt
- minecraft/structures/village/potato/zombie/streets/corner_03.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_01.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_02.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_03.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_04.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_05.nbt
- minecraft/structures/village/potato/zombie/streets/crossroad_06.nbt
- minecraft/structures/village/potato/zombie/streets/straight_01.nbt
- minecraft/structures/village/potato/zombie/streets/straight_02.nbt
- minecraft/structures/village/potato/zombie/streets/straight_03.nbt
- minecraft/structures/village/potato/zombie/streets/straight_04.nbt
- minecraft/structures/village/potato/zombie/streets/straight_05.nbt
- minecraft/structures/village/potato/zombie/streets/straight_06.nbt
- minecraft/structures/village/potato/zombie/streets/turn_01.nbt
- minecraft/structures/village/potato/zombie/town_centers/plains_fountain_01.nbt
- minecraft/structures/village/potato/zombie/town_centers/plains_meeting_point_1.nbt
- minecraft/structures/village/potato/zombie/town_centers/plains_meeting_point_2.nbt
- minecraft/structures/village/potato/zombie/town_centers/plains_meeting_point_3.nbt
- minecraft/structures/village/potato/zombie/villagers/nitwit.nbt
- minecraft/structures/village/potato/zombie/villagers/unemployed.nbt
- minecraft/tags/blocks/grows_potatoes.json
- minecraft/tags/blocks/mineable/potone.json
- minecraft/tags/blocks/poisonous_potato_ores.json
- minecraft/tags/blocks/potatostone_base.json
+ minecraft/tags/damage_type/is_player_attack.json
+ minecraft/tags/items/enchantable/fire_aspect.json
+ minecraft/tags/items/enchantable/sharp_weapon.json
- minecraft/tags/items/heatable_potatos.json
- minecraft/tags/painting_variant/potato.json
- minecraft/tags/worldgen/biome/has_structure/colosseum.json
- minecraft/tags/worldgen/biome/has_structure/ruined_portatols.json
- minecraft/tags/worldgen/biome/has_structure/village_potato.json
- minecraft/tags/worldgen/biome/is_potato.json
- minecraft/tags/worldgen/structure/colosseum.json
- minecraft/tags/worldgen/structure/ruined_portatol.json
- minecraft/trim_material/amber.json
- minecraft/worldgen/biome/arboretum.json
- minecraft/worldgen/biome/corruption.json
- minecraft/worldgen/biome/fields.json
- minecraft/worldgen/biome/hash.json
- minecraft/worldgen/biome/wasteland.json
- minecraft/worldgen/configured_feature/arboretum_trees.json
- minecraft/worldgen/configured_feature/corrputed_buds.json
- minecraft/worldgen/configured_feature/hash_well.json
- minecraft/worldgen/configured_feature/large_potato_columns.json
- minecraft/worldgen/configured_feature/large_potatostone.json
- minecraft/worldgen/configured_feature/leaf_pile.json
- minecraft/worldgen/configured_feature/mother_potato_tree.json
- minecraft/worldgen/configured_feature/ore_amber.json
- minecraft/worldgen/configured_feature/ore_gravtater.json
- minecraft/worldgen/configured_feature/ore_poisonous_potato.json
- minecraft/worldgen/configured_feature/ore_taterstone.json
- minecraft/worldgen/configured_feature/park_lane_surface.json
- minecraft/worldgen/configured_feature/park_lane.json
- minecraft/worldgen/configured_feature/patch_potato.json
- minecraft/worldgen/configured_feature/pile_potato_fruit.json
- minecraft/worldgen/configured_feature/poison.json
- minecraft/worldgen/configured_feature/potato_cloud.json
- minecraft/worldgen/configured_feature/potato_field.json
- minecraft/worldgen/configured_feature/potato_geode.json
- minecraft/worldgen/configured_feature/potato_leaf.json
- minecraft/worldgen/configured_feature/potato_sprouts.json
- minecraft/worldgen/configured_feature/potato_tree_tall.json
- minecraft/worldgen/configured_feature/potato_tree.json
- minecraft/worldgen/configured_feature/small_debris_columns.json
- minecraft/worldgen/configured_feature/twisted_potato.json
- minecraft/worldgen/configured_feature/venomous_column.json
- minecraft/worldgen/multi_noise_biome_source_parameter_list/potato.json
- minecraft/worldgen/noise_settings/potato.json
- minecraft/worldgen/placed_feature/arboretum_trees.json
- minecraft/worldgen/placed_feature/corrupted_buds.json
- minecraft/worldgen/placed_feature/hash_well.json
- minecraft/worldgen/placed_feature/large_potato_columns.json
- minecraft/worldgen/placed_feature/large_potatostone.json
- minecraft/worldgen/placed_feature/leaf_pile_hash.json
- minecraft/worldgen/placed_feature/mother_potato_checked.json
- minecraft/worldgen/placed_feature/mother_potato_tree.json
- minecraft/worldgen/placed_feature/ore_amber.json
- minecraft/worldgen/placed_feature/ore_copper_small.json
- minecraft/worldgen/placed_feature/ore_gold_above_zero.json
- minecraft/worldgen/placed_feature/ore_gravtater.json
- minecraft/worldgen/placed_feature/ore_poisonous_potato.json
- minecraft/worldgen/placed_feature/ore_tatterstone.json
- minecraft/worldgen/placed_feature/park_lane_surface.json
- minecraft/worldgen/placed_feature/park_lane.json
- minecraft/worldgen/placed_feature/patch_dead_bush_2_all_levels.json
- minecraft/worldgen/placed_feature/patch_potato_sparse.json
- minecraft/worldgen/placed_feature/patch_potato.json
- minecraft/worldgen/placed_feature/pile_potato_fruit.json
- minecraft/worldgen/placed_feature/poison_pool.json
- minecraft/worldgen/placed_feature/potato_checked.json
- minecraft/worldgen/placed_feature/potato_cloud.json
- minecraft/worldgen/placed_feature/potato_field.json
- minecraft/worldgen/placed_feature/potato_geode.json
- minecraft/worldgen/placed_feature/potato_leaf.json
- minecraft/worldgen/placed_feature/potato_sprouts.json
- minecraft/worldgen/placed_feature/potato_tree_tall.json
- minecraft/worldgen/placed_feature/potato_tree.json
- minecraft/worldgen/placed_feature/potato.json
- minecraft/worldgen/placed_feature/small_debris_columns.json
- minecraft/worldgen/placed_feature/twisted_potato.json
- minecraft/worldgen/placed_feature/venomous_column_hash.json
- minecraft/worldgen/processor_list/colosseum_veins.json
- minecraft/worldgen/processor_list/farm_potato.json
- minecraft/worldgen/processor_list/spoil_10_percent.json
- minecraft/worldgen/processor_list/spoil_20_percent.json
- minecraft/worldgen/processor_list/spoil_70_percent.json
- minecraft/worldgen/processor_list/street_potato.json
- minecraft/worldgen/processor_list/zombie_potato.json
- minecraft/worldgen/structure_set/colossea.json
- minecraft/worldgen/structure_set/ruined_portatols.json
- minecraft/worldgen/structure/colosseum.json
- minecraft/worldgen/structure/mineshaft_potato.json
- minecraft/worldgen/structure/ruined_portatol.json
- minecraft/worldgen/structure/village_potato.json
- minecraft/worldgen/template_pool/colosseum/mobs/mega_spud.json
- minecraft/worldgen/template_pool/colosseum/mobs/plaguewhale.json
- minecraft/worldgen/template_pool/colosseum/mobs/toxifin.json
- minecraft/worldgen/template_pool/colosseum/starts.json
- minecraft/worldgen/template_pool/colosseum/treasure/bases.json
- minecraft/worldgen/template_pool/colosseum/treasure/bases/centers.json
- minecraft/worldgen/template_pool/colosseum/treasure/brains.json
- minecraft/worldgen/template_pool/colosseum/treasure/connectors.json
- minecraft/worldgen/template_pool/colosseum/treasure/corners/bottom.json
- minecraft/worldgen/template_pool/colosseum/treasure/corners/edges.json
- minecraft/worldgen/template_pool/colosseum/treasure/corners/middle.json
- minecraft/worldgen/template_pool/colosseum/treasure/corners/top.json
- minecraft/worldgen/template_pool/colosseum/treasure/extensions/houses.json
- minecraft/worldgen/template_pool/colosseum/treasure/extensions/large_pool.json
- minecraft/worldgen/template_pool/colosseum/treasure/extensions/small_pool.json
- minecraft/worldgen/template_pool/colosseum/treasure/roofs.json
- minecraft/worldgen/template_pool/colosseum/treasure/stairs.json
- minecraft/worldgen/template_pool/colosseum/treasure/walls.json
- minecraft/worldgen/template_pool/colosseum/treasure/walls/bottom.json
- minecraft/worldgen/template_pool/colosseum/treasure/walls/mid.json
- minecraft/worldgen/template_pool/colosseum/treasure/walls/outer.json
- minecraft/worldgen/template_pool/colosseum/treasure/walls/top.json
- minecraft/worldgen/template_pool/village/potato/decor.json
- minecraft/worldgen/template_pool/village/potato/houses.json
- minecraft/worldgen/template_pool/village/potato/streets.json
- minecraft/worldgen/template_pool/village/potato/terminators.json
- minecraft/worldgen/template_pool/village/potato/town_centers.json
- minecraft/worldgen/template_pool/village/potato/trees.json
- minecraft/worldgen/template_pool/village/potato/villagers.json
- minecraft/worldgen/template_pool/village/potato/well_bottoms.json
- minecraft/worldgen/template_pool/village/potato/zombie/decor.json
- minecraft/worldgen/template_pool/village/potato/zombie/houses.json
- minecraft/worldgen/template_pool/village/potato/zombie/streets.json
- minecraft/worldgen/template_pool/village/potato/zombie/villagers.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/amber_block.json
- minecraft/blockstates/baked_potato_brick_slab.json
- minecraft/blockstates/baked_potato_brick_stairs.json
- minecraft/blockstates/baked_potato_brick_wall.json
- minecraft/blockstates/baked_potato_bricks.json
- minecraft/blockstates/big_brain.json
- minecraft/blockstates/black_potato_peels_block.json
- minecraft/blockstates/blue_potato_peels_block.json
- minecraft/blockstates/brown_potato_peels_block.json
- minecraft/blockstates/charred_baked_potato_brick_slab.json
- minecraft/blockstates/charred_baked_potato_brick_stairs.json
- minecraft/blockstates/charred_baked_potato_brick_wall.json
- minecraft/blockstates/charred_baked_potato_bricks.json
- minecraft/blockstates/compressed_poisonous_potato_block.json
- minecraft/blockstates/corrupted_peelgrass_block.json
- minecraft/blockstates/corrupted_potato_peels_block.json
- minecraft/blockstates/cyan_potato_peels_block.json
- minecraft/blockstates/deepslate_poisonous_potato_ore.json
- minecraft/blockstates/double_compressed_poisonous_potato_block.json
- minecraft/blockstates/expired_baked_potato_brick_slab.json
- minecraft/blockstates/expired_baked_potato_brick_stairs.json
- minecraft/blockstates/expired_baked_potato_brick_wall.json
- minecraft/blockstates/expired_baked_potato_bricks.json
- minecraft/blockstates/floatater.json
- minecraft/blockstates/floatato.json
- minecraft/blockstates/frying_table.json
- minecraft/blockstates/gravtater.json
- minecraft/blockstates/gray_potato_peels_block.json
- minecraft/blockstates/green_potato_peels_block.json
- minecraft/blockstates/light_blue_potato_peels_block.json
- minecraft/blockstates/light_gray_potato_peels_block.json
- minecraft/blockstates/lime_potato_peels_block.json
- minecraft/blockstates/magenta_potato_peels_block.json
- minecraft/blockstates/orange_potato_peels_block.json
- minecraft/blockstates/pedestal.json
- minecraft/blockstates/peelgrass_block.json
- minecraft/blockstates/pink_potato_peels_block.json
- minecraft/blockstates/poison_farmland.json
- minecraft/blockstates/poison_path.json
- minecraft/blockstates/poisonous_mashed_potato.json
- minecraft/blockstates/poisonous_potato_block.json
- minecraft/blockstates/poisonous_potato_cutter.json
- minecraft/blockstates/poisonous_potato_ore.json
- minecraft/blockstates/poisonous_potato_zombie_head_block.json
- minecraft/blockstates/poisonous_potato_zombie_head_hat.json
- minecraft/blockstates/potato_battery.json
- minecraft/blockstates/potato_bud.json
- minecraft/blockstates/potato_button.json
- minecraft/blockstates/potato_door.json
- minecraft/blockstates/potato_fence_gate.json
- minecraft/blockstates/potato_fence.json
- minecraft/blockstates/potato_flower.json
- minecraft/blockstates/potato_fruit.json
- minecraft/blockstates/potato_hanging_sign.json
- minecraft/blockstates/potato_leaves.json
- minecraft/blockstates/potato_pedicule.json
- minecraft/blockstates/potato_peels_block.json
- minecraft/blockstates/potato_planks.json
- minecraft/blockstates/potato_portal.json
- minecraft/blockstates/potato_pressure_plate.json
- minecraft/blockstates/potato_refinery.json
- minecraft/blockstates/potato_sign.json
- minecraft/blockstates/potato_slab.json
- minecraft/blockstates/potato_sprouts.json
- minecraft/blockstates/potato_stairs.json
- minecraft/blockstates/potato_stem.json
- minecraft/blockstates/potato_trapdoor.json
- minecraft/blockstates/potato_wall_hanging_sign.json
- minecraft/blockstates/potato_wall_sign.json
- minecraft/blockstates/potone_copper_ore.json
- minecraft/blockstates/potone_diamond_ore.json
- minecraft/blockstates/potone_gold_ore.json
- minecraft/blockstates/potone_iron_ore.json
- minecraft/blockstates/potone_lapis_ore.json
- minecraft/blockstates/potone_redstone_ore.json
- minecraft/blockstates/potone_slab.json
- minecraft/blockstates/potone_stairs.json
- minecraft/blockstates/potone_wall.json
- minecraft/blockstates/potone.json
- minecraft/blockstates/potted_potato_flower.json
- minecraft/blockstates/powerful_potato.json
- minecraft/blockstates/purple_potato_peels_block.json
- minecraft/blockstates/quadruple_compressed_poisonous_potato_block.json
- minecraft/blockstates/red_potato_peels_block.json
- minecraft/blockstates/resin_ore.json
- minecraft/blockstates/strong_roots.json
- minecraft/blockstates/taterstone_slab.json
- minecraft/blockstates/taterstone_stairs.json
- minecraft/blockstates/taterstone_wall.json
- minecraft/blockstates/taterstone.json
- minecraft/blockstates/terredepomme.json
- minecraft/blockstates/triple_compressed_poisonous_potato_block.json
- minecraft/blockstates/vicious_potato.json
- minecraft/blockstates/weak_roots.json
- minecraft/blockstates/yellow_potato_peels_block.json
- minecraft/models/block/amber_block.json
- minecraft/models/block/baked_potato_brick_slab_top.json
- minecraft/models/block/baked_potato_brick_slab.json
- minecraft/models/block/baked_potato_brick_stairs_inner.json
- minecraft/models/block/baked_potato_brick_stairs_outer.json
- minecraft/models/block/baked_potato_brick_stairs.json
- minecraft/models/block/baked_potato_brick_wall_inventory.json
- minecraft/models/block/baked_potato_brick_wall_post.json
- minecraft/models/block/baked_potato_brick_wall_side_tall.json
- minecraft/models/block/baked_potato_brick_wall_side.json
- minecraft/models/block/baked_potato_bricks.json
- minecraft/models/block/big_brain.json
- minecraft/models/block/black_potato_peels_block.json
- minecraft/models/block/blue_potato_peels_block.json
- minecraft/models/block/brown_potato_peels_block.json
- minecraft/models/block/charred_baked_potato_brick_slab_top.json
- minecraft/models/block/charred_baked_potato_brick_slab.json
- minecraft/models/block/charred_baked_potato_brick_stairs_inner.json
- minecraft/models/block/charred_baked_potato_brick_stairs_outer.json
- minecraft/models/block/charred_baked_potato_brick_stairs.json
- minecraft/models/block/charred_baked_potato_brick_wall_inventory.json
- minecraft/models/block/charred_baked_potato_brick_wall_post.json
- minecraft/models/block/charred_baked_potato_brick_wall_side_tall.json
- minecraft/models/block/charred_baked_potato_brick_wall_side.json
- minecraft/models/block/charred_baked_potato_bricks.json
- minecraft/models/block/compressed_poisonous_potato_block.json
- minecraft/models/block/corrupted_peelgrass_block.json
- minecraft/models/block/corrupted_potato_peels_block.json
- minecraft/models/block/cyan_potato_peels_block.json
- minecraft/models/block/deepslate_poisonous_potato_ore.json
- minecraft/models/block/double_compressed_poisonous_potato_block.json
- minecraft/models/block/expired_baked_potato_brick_slab_top.json
- minecraft/models/block/expired_baked_potato_brick_slab.json
- minecraft/models/block/expired_baked_potato_brick_stairs_inner.json
- minecraft/models/block/expired_baked_potato_brick_stairs_outer.json
- minecraft/models/block/expired_baked_potato_brick_stairs.json
- minecraft/models/block/expired_baked_potato_brick_wall_inventory.json
- minecraft/models/block/expired_baked_potato_brick_wall_post.json
- minecraft/models/block/expired_baked_potato_brick_wall_side_tall.json
- minecraft/models/block/expired_baked_potato_brick_wall_side.json
- minecraft/models/block/expired_baked_potato_bricks.json
- minecraft/models/block/floatater_triggered.json
- minecraft/models/block/floatater.json
- minecraft/models/block/floatato.json
- minecraft/models/block/frying_table_lit.json
- minecraft/models/block/frying_table.json
- minecraft/models/block/gravtater.json
- minecraft/models/block/gray_potato_peels_block.json
- minecraft/models/block/green_potato_peels_block.json
- minecraft/models/block/light_blue_potato_peels_block.json
- minecraft/models/block/light_gray_potato_peels_block.json
- minecraft/models/block/lime_potato_peels_block.json
- minecraft/models/block/magenta_potato_peels_block.json
- minecraft/models/block/orange_potato_peels_block.json
- minecraft/models/block/pedestal.json
- minecraft/models/block/peelgrass_block_snow.json
- minecraft/models/block/peelgrass_block.json
- minecraft/models/block/pink_potato_peels_block.json
- minecraft/models/block/poison_farmland_moist.json
- minecraft/models/block/poison_farmland.json
- minecraft/models/block/poison_path.json
- minecraft/models/block/poisonous_mashed_potato_height10.json
- minecraft/models/block/poisonous_mashed_potato_height12.json
- minecraft/models/block/poisonous_mashed_potato_height14.json
- minecraft/models/block/poisonous_mashed_potato_height2.json
- minecraft/models/block/poisonous_mashed_potato_height4.json
- minecraft/models/block/poisonous_mashed_potato_height6.json
- minecraft/models/block/poisonous_mashed_potato_height8.json
- minecraft/models/block/poisonous_mashed_potato.json
- minecraft/models/block/poisonous_potato_block.json
- minecraft/models/block/poisonous_potato_cutter.json
- minecraft/models/block/poisonous_potato_ore.json
- minecraft/models/block/poisonous_potato_zombie_head_block.json
- minecraft/models/block/poisonous_potato_zombie_head_hat.json
- minecraft/models/block/potato_battery_inverted.json
- minecraft/models/block/potato_battery.json
- minecraft/models/block/potato_bud_down_base.json
- minecraft/models/block/potato_bud_down_frustum.json
- minecraft/models/block/potato_bud_down_middle.json
- minecraft/models/block/potato_bud_down_tip_merge.json
- minecraft/models/block/potato_bud_down_tip.json
- minecraft/models/block/potato_bud_up_base.json
- minecraft/models/block/potato_bud_up_frustum.json
- minecraft/models/block/potato_bud_up_middle.json
- minecraft/models/block/potato_bud_up_tip_merge.json
- minecraft/models/block/potato_bud_up_tip.json
- minecraft/models/block/potato_button_inventory.json
- minecraft/models/block/potato_button_pressed.json
- minecraft/models/block/potato_button.json
- minecraft/models/block/potato_door_bottom_left_open.json
- minecraft/models/block/potato_door_bottom_left.json
- minecraft/models/block/potato_door_bottom_right_open.json
- minecraft/models/block/potato_door_bottom_right.json
- minecraft/models/block/potato_door_top_left_open.json
- minecraft/models/block/potato_door_top_left.json
- minecraft/models/block/potato_door_top_right_open.json
- minecraft/models/block/potato_door_top_right.json
- minecraft/models/block/potato_fence_gate_open.json
- minecraft/models/block/potato_fence_gate_wall_open.json
- minecraft/models/block/potato_fence_gate_wall.json
- minecraft/models/block/potato_fence_gate.json
- minecraft/models/block/potato_fence_inventory.json
- minecraft/models/block/potato_fence_post.json
- minecraft/models/block/potato_fence_side.json
- minecraft/models/block/potato_flower.json
- minecraft/models/block/potato_fruit.json
- minecraft/models/block/potato_hanging_sign.json
- minecraft/models/block/potato_leaves.json
- minecraft/models/block/potato_pedicule.json
- minecraft/models/block/potato_peels_block.json
- minecraft/models/block/potato_planks.json
- minecraft/models/block/potato_portal.json
- minecraft/models/block/potato_pressure_plate_down.json
- minecraft/models/block/potato_pressure_plate.json
- minecraft/models/block/potato_refinery_on.json
- minecraft/models/block/potato_refinery.json
- minecraft/models/block/potato_sign.json
- minecraft/models/block/potato_slab_top.json
- minecraft/models/block/potato_slab.json
- minecraft/models/block/potato_sprouts.json
- minecraft/models/block/potato_stairs_inner.json
- minecraft/models/block/potato_stairs_outer.json
- minecraft/models/block/potato_stairs.json
- minecraft/models/block/potato_stem.json
- minecraft/models/block/potato_trapdoor_bottom.json
- minecraft/models/block/potato_trapdoor_open.json
- minecraft/models/block/potato_trapdoor_top.json
- minecraft/models/block/potone_copper_ore.json
- minecraft/models/block/potone_diamond_ore.json
- minecraft/models/block/potone_gold_ore.json
- minecraft/models/block/potone_iron_ore.json
- minecraft/models/block/potone_lapis_ore.json
- minecraft/models/block/potone_mirrored.json
- minecraft/models/block/potone_redstone_ore.json
- minecraft/models/block/potone_slab_top.json
- minecraft/models/block/potone_slab.json
- minecraft/models/block/potone_stairs_inner.json
- minecraft/models/block/potone_stairs_outer.json
- minecraft/models/block/potone_stairs.json
- minecraft/models/block/potone_wall_inventory.json
- minecraft/models/block/potone_wall_post.json
- minecraft/models/block/potone_wall_side_tall.json
- minecraft/models/block/potone_wall_side.json
- minecraft/models/block/potone.json
- minecraft/models/block/potted_potato_flower.json
- minecraft/models/block/powerful_potato.json
- minecraft/models/block/purple_potato_peels_block.json
- minecraft/models/block/quadruple_compressed_poisonous_potato_block.json
- minecraft/models/block/red_potato_peels_block.json
- minecraft/models/block/resin_ore.json
- minecraft/models/block/strong_roots_noside.json
- minecraft/models/block/strong_roots_side.json
- minecraft/models/block/strong_roots.json
- minecraft/models/block/taterstone_slab_top.json
- minecraft/models/block/taterstone_slab.json
- minecraft/models/block/taterstone_stairs_inner.json
- minecraft/models/block/taterstone_stairs_outer.json
- minecraft/models/block/taterstone_stairs.json
- minecraft/models/block/taterstone_wall_inventory.json
- minecraft/models/block/taterstone_wall_post.json
- minecraft/models/block/taterstone_wall_side_tall.json
- minecraft/models/block/taterstone_wall_side.json
- minecraft/models/block/taterstone.json
- minecraft/models/block/template_layered_height10.json
- minecraft/models/block/template_layered_height12.json
- minecraft/models/block/template_layered_height14.json
- minecraft/models/block/template_layered_height2.json
- minecraft/models/block/template_layered_height4.json
- minecraft/models/block/template_layered_height6.json
- minecraft/models/block/template_layered_height8.json
- minecraft/models/block/template_roots_noside.json
- minecraft/models/block/template_roots_side.json
- minecraft/models/block/template_roots.json
- minecraft/models/block/terredepomme.json
+ minecraft/models/block/trial_spawner_active_ominous.json
+ minecraft/models/block/trial_spawner_ejecting_reward_ominous.json
+ minecraft/models/block/trial_spawner_inactive_ominous.json
- minecraft/models/block/triple_compressed_poisonous_potato_block.json
+ minecraft/models/block/vault_active_ominous.json
+ minecraft/models/block/vault_ejecting_reward_ominous.json
+ minecraft/models/block/vault_ominous.json
+ minecraft/models/block/vault_unlocking_ominous.json
- minecraft/models/block/vicious_potato_enabled.json
- minecraft/models/block/vicious_potato.json
- minecraft/models/block/weak_roots_noside.json
- minecraft/models/block/weak_roots_side.json
- minecraft/models/block/weak_roots.json
- minecraft/models/block/yellow_potato_peels_block.json
- minecraft/models/item/amber_block.json
- minecraft/models/item/amber_gem.json
- minecraft/models/item/baked_potato_brick_slab.json
- minecraft/models/item/baked_potato_brick_stairs.json
- minecraft/models/item/baked_potato_brick_wall.json
- minecraft/models/item/baked_potato_bricks.json
- minecraft/models/item/batato_spawn_egg.json
- minecraft/models/item/big_brain.json
- minecraft/models/item/black_potato_peels_block.json
- minecraft/models/item/black_potato_peels.json
- minecraft/models/item/blue_potato_peels_block.json
- minecraft/models/item/blue_potato_peels.json
- minecraft/models/item/brown_potato_peels_block.json
- minecraft/models/item/brown_potato_peels.json
- minecraft/models/item/chainmail_boots_amber_trim.json
- minecraft/models/item/chainmail_chestplate_amber_trim.json
- minecraft/models/item/chainmail_helmet_amber_trim.json
- minecraft/models/item/chainmail_leggings_amber_trim.json
- minecraft/models/item/charred_baked_potato_brick_slab.json
- minecraft/models/item/charred_baked_potato_brick_stairs.json
- minecraft/models/item/charred_baked_potato_brick_wall.json
- minecraft/models/item/charred_baked_potato_bricks.json
- minecraft/models/item/compressed_poisonous_potato_block.json
- minecraft/models/item/corrupted_peelgrass_block.json
- minecraft/models/item/corrupted_potato_peels_block.json
- minecraft/models/item/corrupted_potato_peels.json
- minecraft/models/item/cyan_potato_peels_block.json
- minecraft/models/item/cyan_potato_peels.json
- minecraft/models/item/deepslate_poisonous_potato_ore.json
- minecraft/models/item/dent.json
- minecraft/models/item/diamond_boots_amber_trim.json
- minecraft/models/item/diamond_chestplate_amber_trim.json
- minecraft/models/item/diamond_helmet_amber_trim.json
- minecraft/models/item/diamond_leggings_amber_trim.json
- minecraft/models/item/double_compressed_poisonous_potato_block.json
- minecraft/models/item/enchanted_golden_poisonous_potato.json
- minecraft/models/item/expired_baked_potato_brick_slab.json
- minecraft/models/item/expired_baked_potato_brick_stairs.json
- minecraft/models/item/expired_baked_potato_brick_wall.json
- minecraft/models/item/expired_baked_potato_bricks.json
- minecraft/models/item/floatater.json
- minecraft/models/item/floatato.json
- minecraft/models/item/frying_table.json
- minecraft/models/item/golden_boots_amber_trim.json
- minecraft/models/item/golden_chestplate_amber_trim.json
- minecraft/models/item/golden_helmet_amber_trim.json
- minecraft/models/item/golden_leggings_amber_trim.json
- minecraft/models/item/golden_poisonous_potato.json
- minecraft/models/item/gravtater.json
- minecraft/models/item/gray_potato_peels_block.json
- minecraft/models/item/gray_potato_peels.json
- minecraft/models/item/green_potato_peels_block.json
- minecraft/models/item/green_potato_peels.json
- minecraft/models/item/hash_browns.json
- minecraft/models/item/hot_potato.json
- minecraft/models/item/iron_boots_amber_trim.json
- minecraft/models/item/iron_chestplate_amber_trim.json
- minecraft/models/item/iron_helmet_amber_trim.json
- minecraft/models/item/iron_leggings_amber_trim.json
- minecraft/models/item/lashing_potato_extended.json
- minecraft/models/item/lashing_potato.json
- minecraft/models/item/leather_boots_amber_trim.json
- minecraft/models/item/leather_chestplate_amber_trim.json
- minecraft/models/item/leather_helmet_amber_trim.json
- minecraft/models/item/leather_leggings_amber_trim.json
- minecraft/models/item/light_blue_potato_peels_block.json
- minecraft/models/item/light_blue_potato_peels.json
- minecraft/models/item/light_gray_potato_peels_block.json
- minecraft/models/item/light_gray_potato_peels.json
- minecraft/models/item/lime_potato_peels_block.json
- minecraft/models/item/lime_potato_peels.json
- minecraft/models/item/magenta_potato_peels_block.json
- minecraft/models/item/magenta_potato_peels.json
- minecraft/models/item/mega_spud_spawn_egg.json
- minecraft/models/item/netherite_boots_amber_trim.json
- minecraft/models/item/netherite_chestplate_amber_trim.json
- minecraft/models/item/netherite_helmet_amber_trim.json
- minecraft/models/item/netherite_leggings_amber_trim.json
+ minecraft/models/item/ominous_bottle.json
+ minecraft/models/item/ominous_trial_key.json
- minecraft/models/item/orange_potato_peels_block.json
- minecraft/models/item/orange_potato_peels.json
- minecraft/models/item/pedestal.json
- minecraft/models/item/peelgrass_block.json
- minecraft/models/item/pink_potato_peels_block.json
- minecraft/models/item/pink_potato_peels.json
- minecraft/models/item/plaguewhale_spawn_egg.json
- minecraft/models/item/poison_farmland.json
- minecraft/models/item/poison_path.json
- minecraft/models/item/poisonous_mashed_potato.json
- minecraft/models/item/poisonous_polytra.json
- minecraft/models/item/poisonous_pota_toes_amber_trim.json
- minecraft/models/item/poisonous_pota_toes_amethyst_trim.json
- minecraft/models/item/poisonous_pota_toes_copper_trim.json
- minecraft/models/item/poisonous_pota_toes_diamond_trim.json
- minecraft/models/item/poisonous_pota_toes_emerald_trim.json
- minecraft/models/item/poisonous_pota_toes_gold_trim.json
- minecraft/models/item/poisonous_pota_toes_iron_trim.json
- minecraft/models/item/poisonous_pota_toes_lapis_trim.json
- minecraft/models/item/poisonous_pota_toes_netherite_trim.json
- minecraft/models/item/poisonous_pota_toes_quartz_trim.json
- minecraft/models/item/poisonous_pota_toes_redstone_trim.json
- minecraft/models/item/poisonous_pota_toes.json
- minecraft/models/item/poisonous_potato_block.json
- minecraft/models/item/poisonous_potato_chestplate_amber_trim.json
- minecraft/models/item/poisonous_potato_chestplate_amethyst_trim.json
- minecraft/models/item/poisonous_potato_chestplate_copper_trim.json
- minecraft/models/item/poisonous_potato_chestplate_diamond_trim.json
- minecraft/models/item/poisonous_potato_chestplate_emerald_trim.json
- minecraft/models/item/poisonous_potato_chestplate_gold_trim.json
- minecraft/models/item/poisonous_potato_chestplate_iron_trim.json
- minecraft/models/item/poisonous_potato_chestplate_lapis_trim.json
- minecraft/models/item/poisonous_potato_chestplate_netherite_trim.json
- minecraft/models/item/poisonous_potato_chestplate_quartz_trim.json
- minecraft/models/item/poisonous_potato_chestplate_redstone_trim.json
- minecraft/models/item/poisonous_potato_chestplate.json
- minecraft/models/item/poisonous_potato_chips.json
- minecraft/models/item/poisonous_potato_cutter.json
- minecraft/models/item/poisonous_potato_fries.json
- minecraft/models/item/poisonous_potato_oil.json
- minecraft/models/item/poisonous_potato_ore.json
- minecraft/models/item/poisonous_potato_plant_unmasked.json
- minecraft/models/item/poisonous_potato_plant.json
- minecraft/models/item/poisonous_potato_slices.json
- minecraft/models/item/poisonous_potato_sticks.json
- minecraft/models/item/poisonous_potato_zombie_head_block.json
- minecraft/models/item/poisonous_potato_zombie_head_hat.json
- minecraft/models/item/poisonous_potato_zombie_spawn_egg.json
- minecraft/models/item/potato_battery.json
- minecraft/models/item/potato_bud.json
- minecraft/models/item/potato_button.json
- minecraft/models/item/potato_door.json
- minecraft/models/item/potato_eye.json
- minecraft/models/item/potato_fence_gate.json
- minecraft/models/item/potato_fence.json
- minecraft/models/item/potato_flower.json
- minecraft/models/item/potato_fruit.json
- minecraft/models/item/potato_hammer.json
- minecraft/models/item/potato_hanging_sign.json
- minecraft/models/item/potato_leaves.json
- minecraft/models/item/potato_of_knowledge.json
- minecraft/models/item/potato_oil.json
- minecraft/models/item/potato_pedicule.json
- minecraft/models/item/potato_peeler.json
- minecraft/models/item/potato_peels_block.json
- minecraft/models/item/potato_peels.json
- minecraft/models/item/potato_planks.json
- minecraft/models/item/potato_portal.json
- minecraft/models/item/potato_pressure_plate.json
- minecraft/models/item/potato_refinery.json
- minecraft/models/item/potato_sign.json
- minecraft/models/item/potato_slab.json
- minecraft/models/item/potato_sprouts.json
- minecraft/models/item/potato_staff.json
- minecraft/models/item/potato_stairs.json
- minecraft/models/item/potato_stem.json
- minecraft/models/item/potato_trapdoor.json
- minecraft/models/item/potone_copper_ore.json
- minecraft/models/item/potone_diamond_ore.json
- minecraft/models/item/potone_gold_ore.json
- minecraft/models/item/potone_iron_ore.json
- minecraft/models/item/potone_lapis_ore.json
- minecraft/models/item/potone_redstone_ore.json
- minecraft/models/item/potone_slab.json
- minecraft/models/item/potone_stairs.json
- minecraft/models/item/potone_wall.json
- minecraft/models/item/potone.json
- minecraft/models/item/powerful_potato.json
- minecraft/models/item/purple_potato_peels_block.json
- minecraft/models/item/purple_potato_peels.json
- minecraft/models/item/quadruple_compressed_poisonous_potato_block.json
- minecraft/models/item/red_potato_peels_block.json
- minecraft/models/item/red_potato_peels.json
- minecraft/models/item/resin_ore.json
- minecraft/models/item/snektato.json
- minecraft/models/item/strong_roots.json
- minecraft/models/item/taterstone_slab.json
- minecraft/models/item/taterstone_stairs.json
- minecraft/models/item/taterstone_wall.json
- minecraft/models/item/taterstone.json
- minecraft/models/item/terredepomme.json
- minecraft/models/item/toxic_beam.json
- minecraft/models/item/toxic_resin.json
- minecraft/models/item/toxifin_spawn_egg.json
- minecraft/models/item/triple_compressed_poisonous_potato_block.json
- minecraft/models/item/turtle_helmet_amber_trim.json
- minecraft/models/item/vicious_potato.json
- minecraft/models/item/weak_roots.json
- minecraft/models/item/yellow_potato_peels_block.json
- minecraft/models/item/yellow_potato_peels.json
- minecraft/particles/falling_poison.json
- minecraft/particles/footstep.json
+ minecraft/particles/infested.json
- minecraft/particles/lightning.json
+ minecraft/particles/ominous_spawning.json
+ minecraft/particles/raid_omen.json
- minecraft/particles/reverse_lightning.json
+ minecraft/particles/small_gust.json
+ minecraft/particles/trial_omen.json
+ minecraft/particles/trial_spawner_detection_ominous.json
- minecraft/texts/potato.txt
- minecraft/textures/block/amber_block.png
- minecraft/textures/block/baked_potato_bricks.png
- minecraft/textures/block/big_brain_front_back.png
- minecraft/textures/block/big_brain_left_right.png
- minecraft/textures/block/big_brain_top_bottom.png
- minecraft/textures/block/black_potato_peels_block.png
- minecraft/textures/block/blue_potato_peels_block.png
- minecraft/textures/block/brown_potato_peels_block.png
- minecraft/textures/block/charred_baked_potato_bricks.png
- minecraft/textures/block/compressed_poisonous_potato_block.png
- minecraft/textures/block/corrupted_peelgrass_block_side.png
- minecraft/textures/block/corrupted_peelgrass_block.png
- minecraft/textures/block/corrupted_potato_peels_block.png
- minecraft/textures/block/cyan_potato_peels_block.png
- minecraft/textures/block/deepslate_poisonous_potato_ore.png
- minecraft/textures/block/double_compressed_poisonous_potato_block.png
- minecraft/textures/block/expired_baked_potato_bricks.png
- minecraft/textures/block/floatater_back_triggered.png
- minecraft/textures/block/floatater_back.png
- minecraft/textures/block/floatater_front.png
- minecraft/textures/block/floatater_side.png
- minecraft/textures/block/floatato.png
- minecraft/textures/block/frying_table.png
- minecraft/textures/block/gravtater.png
- minecraft/textures/block/gray_potato_peels_block.png
- minecraft/textures/block/green_potato_peels_block.png
- minecraft/textures/block/light_blue_potato_peels_block.png
- minecraft/textures/block/light_gray_potato_peels_block.png
- minecraft/textures/block/lime_potato_peels_block.png
- minecraft/textures/block/magenta_potato_peels_block.png
- minecraft/textures/block/orange_potato_peels_block.png
- minecraft/textures/block/pedestal.png
- minecraft/textures/block/peelgrass_block_side.png
- minecraft/textures/block/peelgrass_block_snow.png
- minecraft/textures/block/peelgrass_block_top.png
- minecraft/textures/block/pink_potato_peels_block.png
- minecraft/textures/block/poison_farmland_moist.png
- minecraft/textures/block/poison_farmland.png
- minecraft/textures/block/poison_path_side.png
- minecraft/textures/block/poison_path_top.png
- minecraft/textures/block/poisonous_mashed_potato.png
- minecraft/textures/block/poisonous_potato_block.png
- minecraft/textures/block/poisonous_potato_ore.png
- minecraft/textures/block/poisonous_potato_zombie_head_block_side.png
- minecraft/textures/block/poisonous_potato_zombie_head_block_top.png
- minecraft/textures/block/poisonous_potato_zombie_head_hat.png
- minecraft/textures/block/potato_battery_inverted_top.png
- minecraft/textures/block/potato_battery_side.png
- minecraft/textures/block/potato_battery_top.png
- minecraft/textures/block/potato_bud_down_base.png
- minecraft/textures/block/potato_bud_down_frustum.png
- minecraft/textures/block/potato_bud_down_middle.png
- minecraft/textures/block/potato_bud_down_tip_merge.png
- minecraft/textures/block/potato_bud_down_tip.png
- minecraft/textures/block/potato_bud_up_base.png
- minecraft/textures/block/potato_bud_up_frustum.png
- minecraft/textures/block/potato_bud_up_middle.png
- minecraft/textures/block/potato_bud_up_tip_merge.png
- minecraft/textures/block/potato_bud_up_tip.png
- minecraft/textures/block/potato_cutter_bottom.png
- minecraft/textures/block/potato_cutter_saw.png
- minecraft/textures/block/potato_cutter_saw.png.mcmeta
- minecraft/textures/block/potato_cutter_side.png
- minecraft/textures/block/potato_cutter_top.png
- minecraft/textures/block/potato_door_bottom.png
- minecraft/textures/block/potato_door_top.png
- minecraft/textures/block/potato_flower.png
- minecraft/textures/block/potato_fruit_bottom.png
- minecraft/textures/block/potato_fruit_bottom.png.mcmeta
- minecraft/textures/block/potato_fruit_side.png
- minecraft/textures/block/potato_fruit_side.png.mcmeta
- minecraft/textures/block/potato_fruit_top.png
- minecraft/textures/block/potato_fruit_top.png.mcmeta
- minecraft/textures/block/potato_leaves.png
- minecraft/textures/block/potato_pedicule.png
- minecraft/textures/block/potato_peels_block.png
- minecraft/textures/block/potato_planks.png
- minecraft/textures/block/potato_portal.png
- minecraft/textures/block/potato_portal.png.mcmeta
- minecraft/textures/block/potato_refinery_front_on.png
- minecraft/textures/block/potato_refinery_front.png
- minecraft/textures/block/potato_refinery_side.png
- minecraft/textures/block/potato_refinery_top.png
- minecraft/textures/block/potato_sprouts.png
- minecraft/textures/block/potato_stem_top.png
- minecraft/textures/block/potato_stem.png
- minecraft/textures/block/potato_stem.png.mcmeta
- minecraft/textures/block/potato_trapdoor.png
- minecraft/textures/block/potone_copper_ore.png
- minecraft/textures/block/potone_diamond_ore.png
- minecraft/textures/block/potone_gold_ore.png
- minecraft/textures/block/potone_iron_ore.png
- minecraft/textures/block/potone_lapis_ore.png
- minecraft/textures/block/potone_redstone_ore.png
- minecraft/textures/block/potone.png
- minecraft/textures/block/powerful_potato.png
- minecraft/textures/block/purple_potato_peels_block.png
- minecraft/textures/block/quadruple_compressed_poisonous_potato_block.png
- minecraft/textures/block/red_potato_peels_block.png
- minecraft/textures/block/resin_ore.png
- minecraft/textures/block/strong_roots.png
- minecraft/textures/block/tater.png
- minecraft/textures/block/taterstone.png
- minecraft/textures/block/terredepomme.png
+ minecraft/textures/block/trial_spawner_side_active_ominous.png
+ minecraft/textures/block/trial_spawner_side_inactive_ominous.png
+ minecraft/textures/block/trial_spawner_top_active_ominous.png
+ minecraft/textures/block/trial_spawner_top_ejecting_reward_ominous.png
+ minecraft/textures/block/trial_spawner_top_inactive_ominous.png
- minecraft/textures/block/triple_compressed_poisonous_potato_block.png
+ minecraft/textures/block/vault_bottom_ominous.png
+ minecraft/textures/block/vault_front_ejecting_ominous.png
+ minecraft/textures/block/vault_front_off_ominous.png
+ minecraft/textures/block/vault_front_on_ominous.png
+ minecraft/textures/block/vault_side_off_ominous.png
+ minecraft/textures/block/vault_side_on_ominous.png
+ minecraft/textures/block/vault_top_ejecting_ominous.png
+ minecraft/textures/block/vault_top_ominous.png
- minecraft/textures/block/vicious_potato_enabled.png
- minecraft/textures/block/vicious_potato.png
- minecraft/textures/block/weak_roots.png
- minecraft/textures/block/yellow_potato_peels_block.png
- minecraft/textures/entity/armadillo_potato.png
- minecraft/textures/entity/batato.png
- minecraft/textures/entity/bee/bee_angry_nectar_potato.png
- minecraft/textures/entity/bee/bee_angry_potato.png
- minecraft/textures/entity/bee/bee_nectar_potato.png
- minecraft/textures/entity/bee/bee_potato.png
- minecraft/textures/entity/bee/bee_stinger_potato.png
- minecraft/textures/entity/chicken_potato.png
- minecraft/textures/entity/cow/cow_potato.png
- minecraft/textures/entity/creeper/creeper_potato.png
- minecraft/textures/entity/enderman/enderman_potato.png
- minecraft/textures/entity/pig/pig_hwat_potato.png
- minecraft/textures/entity/pig/pig_potato.png
- minecraft/textures/entity/plaguewhale.png
- minecraft/textures/entity/poisonous_polytra.png
- minecraft/textures/entity/sheep/sheep_fur_potato.png
- minecraft/textures/entity/sheep/sheep_potato.png
- minecraft/textures/entity/signs/hanging/potato.png
- minecraft/textures/entity/signs/potato.png
- minecraft/textures/entity/skeleton/skeleton_potato.png
- minecraft/textures/entity/slime/mega_spud.png
- minecraft/textures/entity/spider/spider_potato.png
- minecraft/textures/entity/toxifin_beam.png
- minecraft/textures/entity/toxifin.png
- minecraft/textures/entity/villager/profession/armorer_potato.png
- minecraft/textures/entity/villager/profession/butcher_potato.png
- minecraft/textures/entity/villager/profession/butcher_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/cartographer_potato.png
- minecraft/textures/entity/villager/profession/cleric_potato.png
- minecraft/textures/entity/villager/profession/farmer_potato.png
- minecraft/textures/entity/villager/profession/farmer_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/fisherman_potato.png
- minecraft/textures/entity/villager/profession/fisherman_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/fletcher_potato.png
- minecraft/textures/entity/villager/profession/fletcher_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/leatherworker_potato.png
- minecraft/textures/entity/villager/profession/librarian_potato.png
- minecraft/textures/entity/villager/profession/librarian_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/mason_potato.png
- minecraft/textures/entity/villager/profession/nitwit_potato.png
- minecraft/textures/entity/villager/profession/shepard_potato.png
- minecraft/textures/entity/villager/profession/shepherd_potato.png.mcmeta
- minecraft/textures/entity/villager/profession/toolsmith_potato.png
- minecraft/textures/entity/villager/profession/weaponsmith_potato.png
- minecraft/textures/entity/villager/type/potato.png
- minecraft/textures/entity/villager/villager_potato.png
- minecraft/textures/entity/zombie_villager/type/potato.png
- minecraft/textures/entity/zombie/husk_potato.png
- minecraft/textures/entity/zombie/poisonous_potato_zombie.png
- minecraft/textures/entity/zombie/zombie_potato.png
- minecraft/textures/environment/poisonus_sun.png
- minecraft/textures/environment/rain_potato.png
- minecraft/textures/font/potato.png
- minecraft/textures/gui/advancements/backgrounds/potato.png
- minecraft/textures/gui/container/fletching.png
- minecraft/textures/gui/container/potato_refinery.png
- minecraft/textures/gui/hanging_signs/potato.png
- minecraft/textures/gui/sprites/container/creative_inventory/tab_top_selected_8.png
- minecraft/textures/gui/sprites/container/creative_inventory/tab_top_unselected_8.png
- minecraft/textures/gui/sprites/container/fletching/progresss.png
- minecraft/textures/gui/sprites/container/potato_refinery/burn_progress.png
- minecraft/textures/gui/sprites/container/potato_refinery/lit_progress.png
- minecraft/textures/item/amber_gem.png
- minecraft/textures/item/black_potato_peels.png
- minecraft/textures/item/blue_potato_peels.png
- minecraft/textures/item/brown_potato_peels.png
- minecraft/textures/item/corrupted_potato_peels.png
- minecraft/textures/item/cyan_potato_peels.png
- minecraft/textures/item/dent.png
- minecraft/textures/item/golden_poisonous_potato.png
- minecraft/textures/item/gray_potato_peels.png
- minecraft/textures/item/green_potato_peels.png
- minecraft/textures/item/hash_browns.png
- minecraft/textures/item/hot_potato.png
- minecraft/textures/item/imposter.png
- minecraft/textures/item/lashing_potato_extended.png
- minecraft/textures/item/lashing_potato.png
- minecraft/textures/item/light_blue_potato_peels.png
- minecraft/textures/item/light_gray_potato_peels.png
- minecraft/textures/item/lime_potato_peels.png
- minecraft/textures/item/magenta_potato_peels.png
+ minecraft/textures/item/ominous_bottle.png
+ minecraft/textures/item/ominous_trial_key.png
- minecraft/textures/item/orange_potato_peels.png
- minecraft/textures/item/pink_potato_peels.png
- minecraft/textures/item/poisonous_polytra.png
- minecraft/textures/item/poisonous_pota_toes.png
- minecraft/textures/item/poisonous_potato_chestplate.png
- minecraft/textures/item/poisonous_potato_chips.png
- minecraft/textures/item/poisonous_potato_fries.png
- minecraft/textures/item/poisonous_potato_slices.png
- minecraft/textures/item/poisonous_potato_sticks.png
- minecraft/textures/item/potato_bud.png
- minecraft/textures/item/potato_door.png
- minecraft/textures/item/potato_eye.png
- minecraft/textures/item/potato_hammer.png
- minecraft/textures/item/potato_hanging_sign.png
- minecraft/textures/item/potato_of_knowledge.png
- minecraft/textures/item/potato_pedicule.png
- minecraft/textures/item/potato_peeler.png
- minecraft/textures/item/potato_peels.png
- minecraft/textures/item/potato_sign.png
- minecraft/textures/item/potato_staff.png
- minecraft/textures/item/purple_potato_peels.png
- minecraft/textures/item/red_potato_peels.png
- minecraft/textures/item/toxic_beam.png
- minecraft/textures/item/toxic_resin.png
- minecraft/textures/item/venomous_potato.png
- minecraft/textures/item/yellow_potato_peels.png
+ minecraft/textures/mob_effect/bad_omen_121.png
+ minecraft/textures/mob_effect/infested.png
+ minecraft/textures/mob_effect/oozing.png
+ minecraft/textures/mob_effect/raid_omen.png
- minecraft/textures/mob_effect/sticky.png
+ minecraft/textures/mob_effect/trial_omen.png
+ minecraft/textures/mob_effect/weaving.png
+ minecraft/textures/mob_effect/wind_charged.png
- minecraft/textures/models/armor/potato_layer_1.png
- minecraft/textures/painting/abstractato.png
- minecraft/textures/painting/burning_potato.png
- minecraft/textures/painting/ceci.png
- minecraft/textures/painting/mr_potato.png
- minecraft/textures/painting/poisonous_potato.png
- minecraft/textures/painting/potatoe.png
- minecraft/textures/painting/ubiquitato.png
- minecraft/textures/particle/footprint.png
+ minecraft/textures/particle/infested.png
- minecraft/textures/particle/lightning_0.png
- minecraft/textures/particle/lightning_1.png
- minecraft/textures/particle/lightning_2.png
- minecraft/textures/particle/lightning_3.png
- minecraft/textures/particle/lightning_4.png
- minecraft/textures/particle/lightning_5.png
- minecraft/textures/particle/lightning_6.png
- minecraft/textures/particle/lightning_7.png
- minecraft/textures/particle/lightning_potato.png
+ minecraft/textures/particle/ominous_spawning.png
+ minecraft/textures/particle/raid_omen.png
+ minecraft/textures/particle/small_gust_0.png
+ minecraft/textures/particle/small_gust_1.png
+ minecraft/textures/particle/small_gust_2.png
+ minecraft/textures/particle/small_gust_3.png
+ minecraft/textures/particle/small_gust_4.png
+ minecraft/textures/particle/small_gust_5.png
+ minecraft/textures/particle/small_gust_6.png
+ minecraft/textures/particle/trial_omen.png
+ minecraft/textures/particle/trial_spawner_detection_ominous_0.png
+ minecraft/textures/particle/trial_spawner_detection_ominous_1.png
+ minecraft/textures/particle/trial_spawner_detection_ominous_2.png
+ minecraft/textures/particle/trial_spawner_detection_ominous_3.png
+ minecraft/textures/particle/trial_spawner_detection_ominous_4.png
- minecraft/textures/trims/color_palettes/amber.png
- nothingtoseeheremovealong/gui/menu_background.png
- nothingtoseeheremovealong/sounds.json
- nothingtoseeheremovealong/sounds/ambient/potato/arboretum.ogg
- nothingtoseeheremovealong/sounds/ambient/potato/corruption.ogg
- nothingtoseeheremovealong/sounds/ambient/potato/fields.ogg
- nothingtoseeheremovealong/sounds/ambient/potato/hash.ogg
- nothingtoseeheremovealong/sounds/ambient/potato/wasteland.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break1.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break2.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break3.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break4.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break5.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/break6.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step1.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step2.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step3.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step4.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step5.ogg
- nothingtoseeheremovealong/sounds/block/corrupted_peelgrass_block/step6.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/break1.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/break2.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/break3.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/break4.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/step1.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/step2.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/step3.ogg
- nothingtoseeheremovealong/sounds/block/gravtater/step4.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/break1.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/break2.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/break3.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/break4.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step1.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step2.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step3.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step4.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step5.ogg
- nothingtoseeheremovealong/sounds/block/peelgrass_block/step6.ogg
- nothingtoseeheremovealong/sounds/block/potone/break1.ogg
- nothingtoseeheremovealong/sounds/block/potone/break2.ogg
- nothingtoseeheremovealong/sounds/block/potone/break3.ogg
- nothingtoseeheremovealong/sounds/block/potone/break4.ogg
- nothingtoseeheremovealong/sounds/block/potone/step1.ogg
- nothingtoseeheremovealong/sounds/block/potone/step2.ogg
- nothingtoseeheremovealong/sounds/block/potone/step3.ogg
- nothingtoseeheremovealong/sounds/block/potone/step4.ogg
- nothingtoseeheremovealong/sounds/block/potone/step5.ogg
- nothingtoseeheremovealong/sounds/block/potone/step6.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/break1.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/break2.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/break3.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/break4.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/step1.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/step2.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/step3.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/step4.ogg
- nothingtoseeheremovealong/sounds/block/terredepomme/step5.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/big1.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/big2.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/big3.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/big4.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/boss_spawn.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/death.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/fireball.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hit1_pitch.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hit2_pitch.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hurt1.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hurt2.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hurt3.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/hurt4.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/idle1.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/idle2.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/idle3.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/idle4.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/mega_spud.ogg
- nothingtoseeheremovealong/sounds/entity/megaspud/summon.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_death.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_hit1.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_hit2.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_hit3.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_hit4.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_idle1.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_idle2.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_idle3.ogg
- nothingtoseeheremovealong/sounds/entity/plaguewhale/elder_idle4.ogg
- nothingtoseeheremovealong/sounds/entity/player/sprout_respawn_1.ogg
- nothingtoseeheremovealong/sounds/entity/player/sprout_respawn_2.ogg
- nothingtoseeheremovealong/sounds/entity/player/sprout_respawn.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/ambient1.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/ambient2.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/ambient3.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/ambient4.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/attack_loop.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/death.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/flop1.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/flop2.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/flop3.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/flop4.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/hit1.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/hit2.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/hit3.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/hit4.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_death.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_hit1.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_hit2.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_hit3.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_hit4.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_idle1.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_idle2.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_idle3.ogg
- nothingtoseeheremovealong/sounds/entity/toxifin/land_idle4.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/death.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/hurt1.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/hurt2.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/infect.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/metal1.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/metal2.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/metal3.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/remedy.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/say1.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/say2.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/say3.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/step1.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/step2.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/step3.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/step4.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/step5.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/unfect.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/wood1.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/wood2.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/wood3.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/wood4.ogg
- nothingtoseeheremovealong/sounds/entity/zombie_potato/woodbreak.ogg
- nothingtoseeheremovealong/sounds/item/potato/eat_chips_1.ogg
- nothingtoseeheremovealong/sounds/item/potato/eat_chips_2.ogg
- nothingtoseeheremovealong/sounds/item/potato/eat_chips_3.ogg
- nothingtoseeheremovealong/sounds/item/potato/eat_chips_4.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_1.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_2.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_3.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_4.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_5.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel_6.ogg
- nothingtoseeheremovealong/sounds/item/potato/peel.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad1.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad2.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad3.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad4.ogg
- nothingtoseeheremovealong/textures/gui/title/background/panorama_0.png
- nothingtoseeheremovealong/textures/gui/title/background/panorama_1.png
- nothingtoseeheremovealong/textures/gui/title/background/panorama_2.png
- nothingtoseeheremovealong/textures/gui/title/background/panorama_3.png
- nothingtoseeheremovealong/textures/gui/title/background/panorama_4.png
- nothingtoseeheremovealong/textures/gui/title/background/panorama_5.png
- nothingtoseeheremovealong/textures/gui/title/poisonous_potato_logo.png
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
- 🥔!
- 🥔🥔!
- 🥔🥔🥔!
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
- A potato a day keeps the doctor away
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
+ As seen on TV!
+ Ask your doctor!
+ Autonomous!
+ Awesome community!
+ Awesome game design right there!
+ Awesome!
+ Aww man!
- Banners and mash
+ Be anti-racist!
- Become one with the spud
+ Bees, bees, bees, bees!
+ Bekarton guards the gate!
+ Best in class!
+ Big Pointy Teeth!
+ Bigger than a bread box!
+ Black lives matter!
+ Blue warrior shot the food!
+ Board game version also available!
+ Boats FTW
- Boil 'em mash 'em stick 'em in a Suspicious Stew
+ Boots with the fur!
+ Bread is pain!
+ Bring it on!
+ Bring me Ray Cokes!
+ Bringing home the bacon!
+ BTAF used to be good!
+ Buckets of lava!
+ Bushy eyebrows!
+ Buzzy Bees!
- By potatoes, for potatoes
+ Call your mother!
- Can you eat the skin?
+ Casual gaming!
+ Ceci n'est pas une title screen!
+ Check it out!
+ Check out the far lands!
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
+ Create!
- Crispy
+ Croak team!
+ Cruising streets for gold!
+ Cześć Polsko!
+ Déjà vu!
+ Déjà vu!
- Dinnerpotato
+ Do it all, everything!
+ Do not distribute!
+ Do you want to join my server?
+ Does barrel rolls!
+ Doesn't avoid double negatives!
+ Doesn't use the U-word!
- Don't be a hater, have a tater
+ Don't bother with the clones!
+ Don't feed avocados to parrots!
+ Don't feed chocolate to parrots!
+ Don't look directly at the bugs!
+ Don’t touch your face!
+ Don't worry, be happy!
+ doot doot
+ Double buffered!
+ DRR! DRR! DRR!
- Dude, Where's My Potato?
+ Dungeon!
+ DungeonQuest is unfair!
- eau de potato
+ Edit is a name!
+ Educate your friends on anti-racism!
+ Engage!
+ Enhanced!
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
- Faster than other brands of potatoes
+ Fat free!
- Fear the Mega Spud
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
- Food for thought
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
+ HURNERJSGER?
+ I have a suggestion.
- I have potato blood in my veins
- I love the smell of potatoes in the morning
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
- It's a perennial, duh
+ It's finished!
+ It's groundbreaking!
+ It's here!
- It's tater time!
+ Jag känner en bot!
+ Jason! Jason! Jason!
+ Java 16 + 1 + 4 = 21!
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
+ Minecraft Java Edition presents: Disgusting Bugs
+ Minecraft!
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
- My life is potato
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
+ Now with extra hugs!
+ Now With Multiplayer!
+ Now you are thinking with pistons!
+ NP is not in P!
+ Octagonal!
- Oh hi! So, how are you holding up? BECAUSE I'M A POTATO!
+ Oh man!
+ Oh, ok, Pigmen!
+ OICU812!
- Old spud, new tricks
+ Omnipotent!
+ One day, somewhere in the future, my work will be quoted!
+ One of a kind!
- Optimized for potato PC's
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
- Po-tech-toes from the future!
+ Polynomial!
- Potato quality!
- Potato, potato?
- Potato! Potato! My kingdom for a 'tato!
+ Prepare, but don’t hoard!
+ Pretty scary!
+ Pretty!
+ Pumpa kungen!
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
+ Shop for your elders!
+ Should not be played while driving
+ Shriek like a Sculk Shrieker!
+ Singleplayer!
- Sliced potatoes and limes
+ Slow acting portals!
+ Sniff sniff...
+ So fresh, so clean!
+ So sweet, like a nice bon bon!
+ Soap and water!
- Solanum tuberosum
+ Something funny!
+ Something's not quite right...
- Somewhat starchy
+ Speak OUT against injustice and UP for equality!
+ Spiders everywhere!
+ sqrt(-1) love you!
+ Stand up for equality in your community!
+ Stay a while and listen!
+ Stay a while, stay forever!
+ Stay home and play games!
+ Stay safe!
+ Stay strong!
- Stick 'em in a stew!
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
- The french fry was invented by Steve in 1805
+ The sky is the limit!
- The starch must flow!
+ The sum of its parts!
+ The true meaning of covfefe
+ Thematic!
+ There's <<a cat on ,my keyboard!~
+ There's no stopping the Trollmaso
- They grow underground, like diamonds
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
- Try eating it raw
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
+ Water bottle!
+ Water proof!
- We got feels for the peels
+ Welcome to your Doom!
+ What do you expect?
+ What's the question?
+ What's up, Doc?
- Whatever you do, don't parboil
+ Where there is not light, there can spider!
+ Who let the frogs out?
+ Who put it there?
- Who says you can't mine a potato?
+ Whoa, dude!
+ Woah.
+ Woo, 2pp!
+ Woo, facepunch!
+ Woo, reddit!
+ Woo, somethingawful!
+ Woo, tigsource!
+ Woo, worldofminecraft!
+ Wow!
+ Yaaay!
+ Yay, puppies for everyone!
+ Yes, sir!
+ You are valid!
+ You are welcome here!
+ You can't explain that!
- You know what they call a potato in Paris?
- You seem to have a potato chip on your shoulder
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
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.Maybe
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.Optionull
- net.minecraft.ReportedException
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.SystemReport
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
- XXX.advancements.critereon.EntitySubPredicate
+ XXX.advancements.critereon.EntitySubPredicates
- XXX.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType
+ XXX.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType$Instance
- XXX.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType
+ XXX.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType$Instance
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
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
+ XXX.advancements.critereon.ItemCustomDataPredicate
- XXX.advancements.critereon.ItemDamagePredicate
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemEnchantmentsPredicate
- XXX.advancements.critereon.ItemEnchantmentsPredicate$Enchantments
+ XXX.advancements.critereon.ItemEnchantmentsPredicate$StoredEnchantments
- XXX.advancements.critereon.ItemPotionsPredicate
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemSubPredicate
- XXX.advancements.critereon.ItemSubPredicate$Type
+ XXX.advancements.critereon.ItemSubPredicates
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
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
- XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.package-info
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
+ XXX.advancements.critereon.PotatoPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$ItemStackPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$StandardItemStackPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$Type
- XXX.advancements.critereon.RecipeCraftedTrigger
+ XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
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
+ XXX.advancements.critereon.ThrowLubricatedTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.advancements.packs.package-info
+ XXX.advancements.packs.PoisonousPotatoAdvancements$ExtendedBuilder
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
- XXX.animal.frog.package-info
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
+ XXX.animal.sniffer.Sniffer
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
+ XXX.arguments.selector.package-info
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
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BeehiveBlockEntity$Occupant
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BigBrainBlockEntity
- XXX.block.entity.BlockEntity$ComponentHelper
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
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
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FletchingBlockEntity
+ XXX.block.entity.FletchingBlockEntity$Fletching
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.HangingSignBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.InventoryHeatComponent
+ XXX.block.entity.LubricationComponent
+ XXX.block.entity.PotatoBaneComponent
+ XXX.block.entity.PotatoRefineryBlockEntity$1
+ XXX.block.entity.PotatoRefineryBlockEntity$NormalRecipe
+ XXX.block.entity.PotatoRefineryBlockEntity$SomeKindOfRecipe
- XXX.block.entity.PotDecorations
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SkullBlockEntity$1
- XXX.block.entity.SkullBlockEntity$2
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
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
- XXX.core.component.DataComponentPatch$SplitResult
+ XXX.core.component.DataComponentPredicate
- XXX.core.component.DataComponentPredicate$Builder
- XXX.core.component.DataComponents
+ XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder
+ XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.package-info
+ XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent
+ XXX.core.component.TypedDataComponent$1
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$23
+ XXX.core.dispenser.DispenseItemBehavior$25
+ XXX.core.dispenser.DispenseItemBehavior$27
+ XXX.core.dispenser.DispenseItemBehavior$29
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$30
+ XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ProjectileDispenseBehavior
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.ColorParticleOption
- XXX.core.particles.ColorParticleOption$1
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
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.UpdateOneTwentyOneRegistries
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
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceStructureTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBannerPatternTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneBiomeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyOneDamageTypes
+ XXX.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneItemTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneStructureTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
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
+ XXX.data.worldgen.ColosseumMobs
+ XXX.data.worldgen.ColosseumPools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.Structures
- XXX.data.worldgen.StructureSets
- XXX.data.worldgen.SurfaceRuleData
+ XXX.data.worldgen.TaigaVillagePools
- XXX.data.worldgen.TerrainProvider
+ XXX.data.worldgen.TrailRuinsStructurePools
- XXX.data.worldgen.TrialChambersStructurePools
+ XXX.data.worldgen.UpdateOneTwentyOnePools
- XXX.data.worldgen.UpdateOneTwentyOneProcessorLists
- XXX.data.worldgen.UpdateOneTwentyOneStructures
+ XXX.data.worldgen.UpdateOneTwentyOneStructureSets
+ XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
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
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
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
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FixProjectileStoredItem
- XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
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
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackComponentRemainderFix
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
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
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
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
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
+ XXX.entity.animal.Pig$1
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
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
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
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
- XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.entity.animal.WolfVariant
- XXX.entity.animal.WolfVariants
+ XXX.entity.monster.Guardian$2
+ XXX.entity.monster.Guardian$4
+ XXX.entity.monster.Guardian$6
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.MegaSpud
+ XXX.entity.monster.MegaSpud$GhastShootFireballGoal
+ XXX.entity.monster.MegaSpud$SlimeMoveControl
+ XXX.entity.monster.MegaSpud$Stage
- XXX.entity.monster.package-info
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
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
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
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.LashingPotatoHook
- XXX.entity.projectile.LlamaSpit
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
+ XXX.entity.projectile.VineProjectile
- XXX.entity.trialspawner.TrialSpawner$FlameParticle
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerData
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$1
- XXX.entity.vault.package-info
+ XXX.entity.vault.VaultState$LightLevel
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
- XXX.entity.vehicle.package-info
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
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
+ XXX.item.armortrim.TrimMaterial
- XXX.item.armortrim.TrimMaterials
+ XXX.item.armortrim.TrimPattern
- XXX.item.armortrim.TrimPatterns
+ XXX.item.armortrim.UpdateOneTwentyOneArmorTrims
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BookContent
+ XXX.item.component.BundleContents
- XXX.item.component.BundleContents$Mutable
+ XXX.item.component.ChargedProjectiles
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
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
+ XXX.item.component.package-info
+ XXX.item.component.ResolvableProfile
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SnekComponent
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
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
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.PotatoRefinementRecipe
- XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator
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
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$3
+ XXX.level.block.BigBrainBlock
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
+ XXX.level.block.CrafterBlock
- XXX.level.block.CrafterBlock$1
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
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
+ XXX.level.block.FloataterBlock
+ XXX.level.block.Mirror
+ XXX.level.block.package-info
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PinkPetalsBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBatteryBlock
- XXX.level.block.PotatoBlock
+ XXX.level.block.PotatoPeelsBlock
+ XXX.level.block.PotatoRefineryBlock
+ XXX.level.block.PotatoZombieHeadBlock
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
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
+ XXX.level.block.StrongRootsBlock$FoundPos
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SuspiciousEffectHolder
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
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
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VaultBlock
+ XXX.level.block.WeakRootsBlock
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
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.ChunkSkyLightSources
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$ConstantLayer
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
+ XXX.level.pathfinder.PathfindingContext
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
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Factory
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
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
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
+ XXX.levelgen.feature.DripstoneUtilsFlex
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
+ XXX.levelgen.feature.ParkLaneSurfaceFeature
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.PotatoBudsFeature
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
+ XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.placement.CloudPlacement
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
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
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
+ XXX.loot.functions.CopyComponentsFunction$1
- XXX.loot.functions.SetNameFunction$Target
+ XXX.loot.packs.package-info
+ XXX.loot.packs.TradeRebalanceChestLoot
- XXX.loot.packs.TradeRebalanceLootTableProvider
+ XXX.loot.packs.UpdateOneTwentyOneBlockLoot
- XXX.loot.packs.UpdateOneTwentyOneChestLoot
+ XXX.loot.packs.UpdateOneTwentyOneEntityLoot
- XXX.loot.packs.UpdateOneTwentyOneEquipmentLoot
- XXX.loot.packs.VanillaFishingLoot
+ XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
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
- XXX.minecraft.core.Cloner
+ XXX.minecraft.core.Cloner$Factory
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedMappedRegistry
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.package-info
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
- XXX.minecraft.server.package-info
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
- XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
+ XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerInfo
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.ServerTickRateManager
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$1
+ XXX.minecraft.util.ExtraCodecs$9
+ XXX.minecraft.util.ExtraCodecs$RecursiveCodec
+ XXX.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ABGR32
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.JavaOps$1
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
+ XXX.minecraft.util.PngInfo
- XXX.minecraft.util.ProblemReporter
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
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
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TaskChainer
- XXX.minecraft.util.TaskChainer$1
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
+ XXX.minecraft.world.RandomizableContainer
- XXX.minecraft.world.RandomSequence
+ XXX.minecraft.world.RandomSequences
- XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.TickRateManager
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
+ XXX.network.chat.HoverEvent$Action$1
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
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
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$4
+ XXX.network.codec.ByteBufCodecs$5
- XXX.network.codec.ByteBufCodecs$6
+ XXX.network.codec.ByteBufCodecs$7
- XXX.network.codec.ByteBufCodecs$8
+ XXX.network.codec.ByteBufCodecs$9
- XXX.network.codec.IdDispatchCodec
+ XXX.network.codec.IdDispatchCodec$Builder
- XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
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
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
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
+ XXX.protocol.game.ClientboundAddSubGridPacket
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateCenterAndRadiusOperation
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
+ XXX.protocol.game.ClientboundSoundSequencePacket$DelayedSound
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.package-info
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
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntent$1
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
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
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
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
+ XXX.server.level.package-info
+ XXX.server.level.ServerLevel$1Builder
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
+ XXX.server.network.Filterable
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
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
+ XXX.state.properties.ChestType$1
+ XXX.storage.loot.BuiltInLootTables
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
+ XXX.storage.loot.ValidationContext
- XXX.structure.placement.package-info
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
- XXX.util.datafix.ComponentDataFixUtils
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.FixWolfHealth
- XXX.util.datafix.PackedBitStorage
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
- XXX.world.effect.InfestedMobEffect
- XXX.world.effect.OozingMobEffect
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RaidOmenMobEffect
- XXX.world.effect.WindChargedMobEffect
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
- XXX.world.entity.EquipmentSlotGroup$1
+ XXX.world.entity.ExperienceOrb$PlayerTarget
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
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
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
- XXX.world.entity.package-info
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
+ XXX.world.food.FoodProperties$PossibleEffect
- XXX.world.food.Foods
+ XXX.world.food.package-info
+ XXX.world.grid.GridCarrier
+ XXX.world.grid.SubGrid
+ XXX.world.grid.SubGridBlocks$1
+ XXX.world.grid.SubGridLightEngine
+ XXX.world.grid.SubGridMovementCollider
+ XXX.world.inventory.FletchingMenu
+ XXX.world.inventory.FletchingMenu$IngredientsSlot
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
- XXX.world.inventory.ItemCombinerMenu$3
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
+ XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.PoisonousPotatoCutterMenu
+ XXX.world.inventory.PoisonousPotatoCutterMenu$2
+ XXX.world.inventory.PotatoRefineryMenu$FuelSlot
+ XXX.world.inventory.RecipeBookMenu
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
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorItem$Type
+ XXX.world.item.ArmorMaterial
- XXX.world.item.ArmorMaterial$Layer
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
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
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
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
+ XXX.world.item.HotPotatoItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$2
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.OminousBottleItem
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
+ XXX.world.item.PoisonousPotatoPlantItem
+ XXX.world.item.PotatoEyeItem
+ XXX.world.item.PotatoOfKnowledgeItem
+ XXX.world.item.PotatoPeelerItem
- XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
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
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
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
- XXX.worldgen.biome.BiomeData
+ XXX.worldgen.biome.EndBiomes
- XXX.worldgen.biome.NetherBiomes
+ XXX.worldgen.biome.OverworldBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.RegistryAccess$1FrozenAccess -1P
```
```
XXX.core.component.DataComponentMap$Builder +2M
```
```
XXX.core.component.DataComponentPatch +3M
```
```
XXX.core.dispenser.DispenseItemBehavior -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$10 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$12 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$14 +2M -1M | +1P
```
```
XXX.core.dispenser.DispenseItemBehavior$16 +1M
```
```
XXX.core.dispenser.DispenseItemBehavior$5 +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$7 +1M -1M | +1P
```
```
XXX.loot.packs.VanillaBlockLoot +46M -64M
```
```
XXX.loot.packs.VanillaEntityLoot -1M
```
```
XXX.worldgen.features.CaveFeatures -4P
```
```
XXX.worldgen.features.NetherFeatures -5P
```
```
XXX.worldgen.features.PileFeatures -1P
```
```
XXX.worldgen.features.VegetationFeatures -7P
```
```
XXX.worldgen.placement.CavePlacements -4P
```
```
XXX.worldgen.placement.MiscOverworldPlacements -2P
```
```
XXX.worldgen.placement.OrePlacements -6P
```
```
XXX.worldgen.placement.TreePlacements -5P
```
```
XXX.worldgen.placement.VillagePlacements -2P
```
```
XXX.gametest.framework.GameTestHelper$1 -1P
```
```
XXX.gametest.framework.MultipleTestTracker$1 -1P
```
```
XXX.minecraft.nbt.NbtOps$NbtRecordBuilder -1P
```
```
XXX.minecraft.network.Connection$2 -1P
```
```
XXX.network.chat.FilterMask +3P -3P
```
```
XXX.network.chat.SignedMessageChain$DecodeException +2M -2M | +5P -1P
```
```
XXX.network.chat.Style$1Collector -1P
```
```
XXX.network.codec.ByteBufCodecs -1P
```
```
XXX.network.codec.ByteBufCodecs$10 +1M -1M | -1P
```
```
XXX.network.codec.ByteBufCodecs$12 +3M -3M | +1P -1P
```
```
XXX.network.codec.ByteBufCodecs$14 +3M -5M | -2P
```
```
XXX.network.codec.ByteBufCodecs$16 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$18 +3M -3M | +3P -1P
```
```
XXX.network.codec.ByteBufCodecs$21 +3M -5M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$23 +3M -3M | +2P -1P
```
```
XXX.network.codec.ByteBufCodecs$25 +5M -3M | +4P -3P
```
```
XXX.network.codec.ByteBufCodecs$27 +1M -5M | +1P
```
```
XXX.protocol.configuration.ClientConfigurationPacketListener +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket -1M
```
```
XXX.protocol.game.ClientboundBossEventPacket$AddOperation -2P
```
```
XXX.protocol.game.GamePacketTypes +2P -2P
```
```
XXX.protocol.game.ServerGamePacketListener +1P
```
```
XXX.protocol.game.ServerboundChatCommandPacket +1M -5M | -4P
```
```
XXX.minecraft.resources.RegistryDataLoader -2M
```
```
XXX.minecraft.server.PlayerAdvancements -1M
```
```
XXX.server.commands.RaidCommand +2M -2M
```
```
XXX.server.dedicated.ServerWatchdog$1 -1P
```
```
XXX.server.gui.MinecraftServerGui$2 -1P
```
```
XXX.server.level.ServerBossEvent -2M
```
```
XXX.minecraft.stats.StatFormatter -1M | -1P
```
```
XXX.minecraft.stats.Stats -4P
```
```
XXX.minecraft.tags.BiomeTags -4P
```
```
XXX.minecraft.tags.EntityTypeTags +2P
```
```
XXX.minecraft.tags.PaintingVariantTags -1P
```
```
XXX.minecraft.tags.StructureTags -2P
```
```
XXX.minecraft.util.ExtraCodecs +50M -93M | -1P
```
```
XXX.minecraft.util.ExtraCodecs$7 +6M -7M | +1P -5P
```
```
XXX.minecraft.util.KeyDispatchDataCodec +2M -3M | +1P -1P
```
```
XXX.datafix.fixes.References +1M -37M
```
```
XXX.datafix.schemas.V99 +1M -1M
```
```
XXX.util.valueproviders.BiasedToBottomInt +1P -1P
```
```
XXX.util.valueproviders.ClampedNormalFloat +1P -1P
```
```
XXX.util.valueproviders.ConstantFloat +1P -1P
```
```
XXX.util.valueproviders.IntProvider +5M -4M
```
```
XXX.util.valueproviders.TrapezoidFloat +1P -1P
```
```
XXX.util.valueproviders.UniformInt +1P -1P
```
```
XXX.minecraft.world.BossEvent +1M -4M | -2P
```
```
XXX.minecraft.world.ContainerHelper -1M
```
```
XXX.world.effect.MobEffect +8M -1M | +2P
```
```
XXX.world.entity.AreaEffectCloud -1M | -1P
```
```
XXX.world.entity.EntityEvent -1P
```
```
XXX.world.entity.ExperienceOrb -2M | +1P -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$1 -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$3 -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$5 -1P
```
```
XXX.ai.goal.ZombieAttackGoal +1M -1M | +1P -1P
```
```
XXX.entity.decoration.PaintingVariants -7P
```
```
XXX.entity.monster.Bogged -1M
```
```
XXX.entity.monster.Creeper -1M
```
```
XXX.entity.monster.EnderMan -1M
```
```
XXX.entity.monster.Guardian +1M -16M | -3P
```
```
XXX.entity.monster.Phantom$PhantomLookControl -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -1M | +1P
```
```
XXX.entity.raid.Raid +4M -4M | +2P -2P
```
```
XXX.entity.raid.Raider +2M
```
```
XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal -1P
```
```
XXX.world.inventory.BeaconMenu$PaymentSlot -1P
```
```
XXX.world.inventory.CartographyTableMenu$4 -1P
```
```
XXX.world.inventory.EnchantmentMenu +1M -1M
```
```
XXX.world.inventory.EnchantmentMenu$2 -1P
```
```
XXX.world.item.HoneyBottleItem +1M
```
```
XXX.world.item.MaceItem +6M -5M | +2P -1P
```
```
XXX.world.item.MobBucketItem +1M -1M
```
```
XXX.world.item.PotionItem +1M -1M
```
```
XXX.world.item.Rarity -1P
```
```
XXX.world.item.ShieldItem +1M -1M
```
```
XXX.world.item.SmithingTemplateItem +1M -1M
```
```
XXX.world.item.SpectralArrowItem +1M
```
```
XXX.world.item.SuspiciousStewItem +1M -1M
```
```
XXX.world.item.ThrowablePotionItem +2M
```
```
XXX.world.item.TippedArrowItem +1M -1M
```
```
XXX.item.crafting.RecipeType -2P
```
```
XXX.item.crafting.ShapedRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.ShapelessRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SimpleCraftingRecipeSerializer +1M -1M | +1P -2P
```
```
XXX.item.crafting.SingleItemRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SmithingTransformRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SmithingTrimRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.enchantment.EnchantmentHelper +5M -3M
```
```
XXX.world.level.EmptyBlockGetter -1M
```
```
XXX.world.level.EntityGetter -1M
```
```
XXX.world.level.GameRules -2P
```
```
XXX.world.level.Level -6M | -6P
```
```
XXX.level.biome.MultiNoiseBiomeSourceParameterLists -1P
```
```
XXX.level.biome.TheEndBiomeSource +1M -1M | +1P -1P
```
```
XXX.level.block.ChestBlock$2$1 -1P
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.level.block.SpawnerBlock +1M -1M
```
```
XXX.block.entity.BlockEntity +19M -7M | +1P
```
```
XXX.block.entity.LecternBlockEntity +1M -1M
```
```
XXX.block.entity.SculkCatalystBlockEntity +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity +2M -2M
```
```
XXX.block.entity.SculkShriekerBlockEntity +2M -2M
```
```
XXX.block.entity.ShulkerBoxBlockEntity +1M -1M
```
```
XXX.block.entity.SpawnerBlockEntity +1M -1M
```
```
XXX.block.entity.StructureBlockEntity +1M -1M
```
```
XXX.block.entity.TheEndGatewayBlockEntity +2M -2M
```
```
XXX.block.entity.TrialSpawnerBlockEntity +3M -3M
```
```
XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission +4M -4M | +1P -1P
```
```
XXX.entity.vault.VaultBlockEntity$Client +3M -3M
```
```
XXX.entity.vault.VaultState +2M -2M
```
```
XXX.entity.vault.VaultState$2 +1M -1M
```
```
XXX.entity.vault.VaultState$4 +1M -1M
```
```
XXX.level.chunk.ChunkAccess -1M | -1P
```
```
XXX.level.chunk.ChunkGenerator +1P -1P
```
```
XXX.level.chunk.ChunkGenerators +1M -1M
```
```
XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper -1P
```
```
XXX.level.chunk.LevelChunkSection$1BlockCounter -1P
```
```
XXX.level.entity.LevelEntityGetter -2M | -1P
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M | +1P -1P
```
```
XXX.level.levelgen.NoiseGeneratorSettings +1M -3M | -2P
```
```
XXX.level.levelgen.NoiseRouterData -3M
```
```
XXX.level.levelgen.NoiseSettings +1M -1M | -1P
```
```
XXX.level.levelgen.RandomState$1 -1P
```
```
XXX.level.levelgen.SurfaceRules$ConditionSource +2M -2M
```
```
XXX.level.levelgen.SurfaceRules$RuleSource +2M -2M
```
```
XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition -1P
```
```
XXX.level.levelgen.SurfaceSystem$1 -1P
```
```
XXX.level.levelgen.VerticalAnchor -1M
```
```
XXX.level.levelgen.WorldDimensions -1M
```
```
XXX.levelgen.blockpredicates.AnyOfPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.BlockPredicateType +2M -2M | +1P -1P
```
```
XXX.levelgen.blockpredicates.HasSturdyFacePredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.MatchingBlockTagPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.MatchingFluidsPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.ReplaceablePredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.WouldSurvivePredicate +1P -1P
```
```
XXX.levelgen.carver.WorldCarver +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.Feature +1M -1M | +1P -8P
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +3M -5M | -1P
```
```
XXX.feature.featuresize.FeatureSizeType +3M -3M | +1P -1P
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +1P -1P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1P -1P
```
```
XXX.feature.stateproviders.BlockStateProviderType +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.NoiseThresholdProvider +1P -1P
```
```
XXX.feature.stateproviders.RotatedBlockProvider +1P -1P
```
```
XXX.feature.stateproviders.WeightedStateProvider +1P -1P
```
```
XXX.feature.treedecorators.AlterGroundDecorator +1P -1P
```
```
XXX.feature.treedecorators.BeehiveDecorator +7M -9M | +1P -2P
```
```
XXX.feature.treedecorators.LeaveVineDecorator +1P -1P
```
```
XXX.feature.treedecorators.TrunkVineDecorator +1P -1P
```
```
XXX.feature.trunkplacers.BendingTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.DarkOakTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.GiantTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.StraightTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.TrunkPlacerType +3M -3M | +1P -1P
```
```
XXX.levelgen.heightproviders.ConstantHeight +1P -1P
```
```
XXX.levelgen.heightproviders.HeightProviderType +2M -2M | +1P -1P
```
```
XXX.levelgen.heightproviders.UniformHeight +1P -1P
```
```
XXX.levelgen.heightproviders.WeightedListHeight +1P -1P
```
```
XXX.levelgen.placement.BiomeFilter +1P -1P
```
```
XXX.levelgen.placement.CarvingMaskPlacement +1P -1P
```
```
XXX.levelgen.structure.Structure$GenerationContext +2M -3M | -1P
```
```
XXX.levelgen.structure.Structure$StructureSettings +1M -2M | -1P
```
```
XXX.structure.placement.ConcentricRingsStructurePlacement +1P -1P
```
```
XXX.loot.functions.CopyNameFunction +1P -1P
```
```
XXX.loot.functions.EnchantRandomlyFunction +5M -4M | +1P -1P
```
```
XXX.loot.functions.EnchantWithLevelsFunction +1P -1P
```
```
XXX.loot.functions.ExplorationMapFunction +1P -1P
```
```
XXX.loot.functions.FillPlayerHead +1P -1P
```
```
XXX.loot.functions.ListOperation +1M -1M
```
```
XXX.loot.functions.LootItemFunctions +1M -1M | +1P
```
```
XXX.loot.functions.SetAttributesFunction +6M -4M | +2P -1P
```
```
XXX.loot.functions.SetBannerPatternFunction +1P -1P
```
```
XXX.loot.functions.SetBookCoverFunction +1P -1P
```
```
XXX.loot.functions.SetContainerContents +1P -1P
```
```
XXX.loot.functions.SetContainerLootTable +1P -1P
```
```
XXX.loot.functions.SetEnchantmentsFunction +1P -1P
```
```
XXX.loot.functions.SetFireworkExplosionFunction +1P -1P
```
```
XXX.loot.functions.SetInstrumentFunction +1P -1P
```
```
XXX.loot.functions.SetItemDamageFunction +1P -1P
```
```
XXX.loot.functions.SetPotionFunction +1P -1P
```
```
XXX.loot.functions.SetWritableBookPagesFunction +1P -1P
```
```
XXX.loot.functions.SmeltItemFunction +1P -1P
```
```
XXX.loot.predicates.AllOfCondition +1P -1P
```
```
XXX.loot.predicates.AnyOfCondition +1P -1P
```
```
XXX.loot.predicates.BonusLevelTableCondition +1P -1P
```
```
XXX.loot.predicates.EntityHasScoreCondition +1P -1P
```
```
XXX.loot.predicates.ExplosionCondition +1P -1P
```
```
XXX.loot.predicates.LocationCheck +1P -1P
```
```
XXX.loot.predicates.LootItemConditions +1M -1M | -1P
```
```
XXX.loot.predicates.LootItemKilledByPlayerCondition +1P -1P
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentMap$Builder
</summary>

```diff
- DataComponentMap buildFromMapTrusted(Map)
- void setUnchecked(DataComponentType,Object)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentPatch
</summary>

```diff
- DataComponentPatch forget(Predicate)
- DataComponentPatch$SplitResult split()
- void lambda$split$2(DataComponentMap$Builder,Set,DataComponentType,Optional)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior
</summary>

```diff
+ Vec3 getEntityPokingOutOfBlockPos(BlockSource,EntityType,Direction)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$10
</summary>

```diff
+ void lambda$execute$0(Direction,ArmorStand)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$12
</summary>

```diff
+ boolean lambda$execute$0(AbstractHorse)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$14
</summary>

```diff
- boolean lambda$execute$0(BlockBehaviour$BlockStateBase)
- ItemStack takeLiquid(BlockSource,ItemStack,ItemStack)
+ void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$16
</summary>

```diff
- void lambda$execute$0(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$5
</summary>

```diff
- boolean lambda$execute$0(AbstractChestedHorse)
- ItemStack execute(BlockSource,ItemStack)
+ Projectile getProjectile(Level,Position,ItemStack)
+ void lambda$getProjectile$0(ItemStack,Snowball)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$7
</summary>

```diff
+ ItemStack dispense(BlockSource,ItemStack)
- ItemStack execute(BlockSource,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
+ LootItemCondition$Builder taterBoost(int)
- LootItemFunction$Builder lambda$generate$107(Block,Integer)
+ LootItemFunction$Builder lambda$generate$112(Block,Integer)
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$238(Integer)
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$255(Integer)
- LootPoolEntryContainer$Builder lambda$generate$230(Block,Integer)
- LootPoolEntryContainer$Builder lambda$generate$231(Block,Integer)
+ LootPoolEntryContainer$Builder lambda$generate$247(Block,Integer)
+ LootPoolEntryContainer$Builder lambda$generate$248(Block,Integer)
+ LootTable$Builder lambda$generate$107(Block)
- LootTable$Builder lambda$generate$112(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$113(Block)
- LootTable$Builder lambda$generate$113(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$114(Block)
- LootTable$Builder lambda$generate$114(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$115(Block)
- LootTable$Builder lambda$generate$115(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$116(Block)
- LootTable$Builder lambda$generate$116(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$17(Block)
- LootTable$Builder lambda$generate$17(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$174(Block)
+ LootTable$Builder lambda$generate$174(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$175(Block)
+ LootTable$Builder lambda$generate$175(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$176(Block)
+ LootTable$Builder lambda$generate$176(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$177(Block)
+ LootTable$Builder lambda$generate$177(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$178(Block)
+ LootTable$Builder lambda$generate$178(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$179(Block)
+ LootTable$Builder lambda$generate$179(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$18(Block)
- LootTable$Builder lambda$generate$18(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$180(Block)
+ LootTable$Builder lambda$generate$180(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$19(Block)
- LootTable$Builder lambda$generate$19(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$197(Block)
- LootTable$Builder lambda$generate$197(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$198(Block)
- LootTable$Builder lambda$generate$198(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$204(Block)
- LootTable$Builder lambda$generate$204(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$206(Block)
+ LootTable$Builder lambda$generate$206(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$208(Block)
- LootTable$Builder lambda$generate$208(ItemLike)
- LootTable$Builder lambda$generate$209(ItemLike)
+ LootTable$Builder lambda$generate$209(LootPool$Builder,Block)
- LootTable$Builder lambda$generate$210(ItemLike)
+ LootTable$Builder lambda$generate$210(LootPool$Builder,Block)
+ LootTable$Builder lambda$generate$212(Block)
- LootTable$Builder lambda$generate$212(ItemLike)
+ LootTable$Builder lambda$generate$213(Block)
- LootTable$Builder lambda$generate$213(ItemLike)
- LootTable$Builder lambda$generate$215(Block)
+ LootTable$Builder lambda$generate$215(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$219(Block)
+ LootTable$Builder lambda$generate$219(ItemLike)
- LootTable$Builder lambda$generate$220(Block)
+ LootTable$Builder lambda$generate$220(ItemLike)
- LootTable$Builder lambda$generate$221(Block)
+ LootTable$Builder lambda$generate$221(ItemLike)
+ LootTable$Builder lambda$generate$222(Block)
- LootTable$Builder lambda$generate$222(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$223(ItemLike)
- LootTable$Builder lambda$generate$223(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$224(Block)
+ LootTable$Builder lambda$generate$224(ItemLike)
- LootTable$Builder lambda$generate$225(Block)
+ LootTable$Builder lambda$generate$225(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$226(Block)
- LootTable$Builder lambda$generate$226(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$227(Block)
- LootTable$Builder lambda$generate$227(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$230(Block)
+ LootTable$Builder lambda$generate$231(Block)
- LootTable$Builder lambda$generate$233(Block)
+ LootTable$Builder lambda$generate$233(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$234(Block)
+ LootTable$Builder lambda$generate$234(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$237(Block)
+ LootTable$Builder lambda$generate$237(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$238(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$239(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$240(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$241(Block)
+ LootTable$Builder lambda$generate$242(Block)
+ LootTable$Builder lambda$generate$243(Block)
+ LootTable$Builder lambda$generate$244(VanillaBlockLoot,Block)
+ LootTable$Builder lambda$generate$245(Block)
+ LootTable$Builder lambda$generate$246(Block)
+ LootTable$Builder lambda$generate$249(Block)
+ LootTable$Builder lambda$generate$250(Block)
+ LootTable$Builder lambda$generate$251(Block)
+ LootTable$Builder lambda$generate$252(Block)
+ LootTable$Builder lambda$generate$253(Block)
+ LootTable$Builder lambda$generate$254(Block)
- LootTable$Builder lambda$generate$86(Block)
+ LootTable$Builder lambda$generate$86(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$87(Block)
+ LootTable$Builder lambda$generate$87(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$88(Block)
+ LootTable$Builder lambda$generate$88(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$89(Block)
+ LootTable$Builder lambda$generate$89(VanillaBlockLoot,Block)
- LootTable$Builder lambda$generate$90(Block)
+ LootTable$Builder lambda$generate$90(VanillaBlockLoot,Block)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaEntityLoot
</summary>

```diff
+ LootPoolEntryContainer$Builder potatoPeelIfPotato(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageChain$DecodeException
</summary>

```diff
+ boolean shouldDisconnect()
- void <clinit>()
+ void <init>(Component,boolean)
- void <init>(Component)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$10
</summary>

```diff
- void <init>()
+ void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$12
</summary>

```diff
+ String decode(ByteBuf)
- Tag decode(ByteBuf)
+ void <init>(int)
- void <init>(Supplier)
+ void encode(ByteBuf,String)
- void encode(ByteBuf,Tag)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$14
</summary>

```diff
+ DecoderException lambda$decode$0(Tag,String)
+ EncoderException lambda$encode$1(Object,String)
+ Object decode(RegistryFriendlyByteBuf)
- Optional decode(ByteBuf)
- void <init>()
+ void <init>(StreamCodec,Codec)
- void encode(ByteBuf,Optional)
+ void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$16
</summary>

```diff
- Quaternionf decode(ByteBuf)
+ Vector3f decode(ByteBuf)
- void encode(ByteBuf,Quaternionf)
+ void encode(ByteBuf,Vector3f)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$18
</summary>

```diff
- Collection decode(ByteBuf)
+ Optional decode(ByteBuf)
- void <init>(int,IntFunction,StreamCodec)
+ void <init>(StreamCodec)
- void encode(ByteBuf,Collection)
+ void encode(ByteBuf,Optional)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$21
</summary>

```diff
+ Either decode(ByteBuf)
- Object decode(ByteBuf)
- void <init>(IntFunction,ToIntFunction)
+ void <init>(StreamCodec,StreamCodec)
+ void encode(ByteBuf,Either)
- void encode(ByteBuf,Object)
+ void lambda$encode$0(ByteBuf,StreamCodec,Object)
+ void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$23
</summary>

```diff
- Holder decode(RegistryFriendlyByteBuf)
+ Object decode(RegistryFriendlyByteBuf)
+ void <init>(Function,ResourceKey)
- void <init>(ResourceKey,StreamCodec)
- void encode(RegistryFriendlyByteBuf,Holder)
+ void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$25
</summary>

```diff
+ HolderSet decode(RegistryFriendlyByteBuf)
- PropertyMap decode(ByteBuf)
- String lambda$decode$0(ByteBuf)
- void <init>()
+ void <init>(ResourceKey)
- void encode(ByteBuf,PropertyMap)
+ void encode(RegistryFriendlyByteBuf,HolderSet)
- void lambda$encode$1(ByteBuf,String)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$27
</summary>

```diff
+ GameProfile decode(ByteBuf)
+ Object decode(Object)
- void <clinit>()
+ void <init>()
+ void encode(ByteBuf,GameProfile)
+ void encode(Object,Object)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket
</summary>

```diff
+ ClientboundBossEventPacket createUpdatePositionPacket(BossEvent)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundChatCommandPacket
</summary>

```diff
+ ArgumentSignatures argumentSignatures()
+ Instant timeStamp()
+ LastSeenMessages$Update lastSeenMessages()
+ long salt()
+ void <init>(String,Instant,long,ArgumentSignatures,LastSeenMessages$Update)
- void <init>(String)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryDataLoader
</summary>

```diff
+ void lambda$loadContentsFromNetwork$14(String)
+ void lambda$loadElementFromResource$13(String)
```

</details>
<details>
<summary>
net.minecraft.server.PlayerAdvancements
</summary>

```diff
+ AdvancementTree getTree()
```

</details>
<details>
<summary>
net.minecraft.server.commands.RaidCommand
</summary>

```diff
+ Component lambda$setBadOmenLevel$8(int,int)
- Component lambda$setRaidOmenLevel$8(int,int)
+ int setBadOmenLevel(CommandSourceStack,int)
- int setRaidOmenLevel(CommandSourceStack,int)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerBossEvent
</summary>

```diff
+ void <init>(Entity,BossEvent$BossBarColor,BossEvent$BossBarOverlay)
+ void setLocation(Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.stats.StatFormatter
</summary>

```diff
+ String lambda$static$4(int)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- App lambda$static$60(RecordCodecBuilder$Instance)
- App lambda$static$68(RecordCodecBuilder$Instance)
+ App lambda$static$69(RecordCodecBuilder$Instance)
- App lambda$static$71(RecordCodecBuilder$Instance)
+ App lambda$static$77(RecordCodecBuilder$Instance)
+ App lambda$static$80(RecordCodecBuilder$Instance)
- BitSet lambda$static$56(LongStream)
+ BitSet lambda$static$65(LongStream)
+ Codec int2IntMap()
+ Codec intIntPair()
+ Codec lambda$lazyInitializedCodec$48(Supplier,Codec)
+ Codec lazyInitializedCodec(Supplier)
+ Codec recursive(String,Function)
+ Codec sizeLimitedList(Codec,int)
+ Codec sizeLimitedString(int,int)
+ Codec stringResolverCodec(Function,Function)
+ Codec unboundedDispatchMap(Codec,Function)
+ Codec validate(Codec,Function)
+ Codec withAlternative(Codec,Codec,Function)
+ Codec withAlternative(Codec,Codec)
+ Codec xor(Codec,Codec)
- DataResult lambda$ensureHomogenous$43(Function,Collection)
+ DataResult lambda$ensureHomogenous$52(Function,Collection)
- DataResult lambda$floatRangeMinExclusiveWithMessage$36(float,float,Function,Float)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
- DataResult lambda$intRangeWithMessage$31(int,int,Function,Integer)
+ DataResult lambda$intRangeWithMessage$37(int,int,Function,Integer)
- DataResult lambda$nonEmptyHolderSet$41(HolderSet)
+ DataResult lambda$nonEmptyHolderSet$47(HolderSet)
- DataResult lambda$nonEmptyList$39(List)
+ DataResult lambda$nonEmptyList$45(List)
+ DataResult lambda$sizeLimitedList$90(int,List)
- DataResult lambda$sizeLimitedMap$77(int,Map)
+ DataResult lambda$sizeLimitedMap$92(int,Map)
+ DataResult lambda$sizeLimitedString$87(int,int,String)
- DataResult lambda$static$45(String)
- DataResult lambda$static$48(String)
- DataResult lambda$static$50(String)
- DataResult lambda$static$53(String)
+ DataResult lambda$static$54(String)
+ DataResult lambda$static$57(String)
+ DataResult lambda$static$59(String)
+ DataResult lambda$static$62(String)
- DataResult lambda$static$67(String)
- DataResult lambda$static$73(String)
- DataResult lambda$static$75(String)
+ DataResult lambda$static$76(String)
- DataResult lambda$static$79(String)
+ DataResult lambda$static$82(String)
+ DataResult lambda$static$84(String)
+ DataResult lambda$static$94(String)
+ DataResult lambda$stringResolverCodec$31(String)
+ DataResult lambda$stringResolverCodec$32(Function,String)
+ DataResult lambda$stringResolverCodec$34(Object)
+ DataResult lambda$stringResolverCodec$35(Function,Object)
- DataResult lambda$temporalCodec$46(DateTimeFormatter,String)
+ DataResult lambda$temporalCodec$55(DateTimeFormatter,String)
- Either lambda$static$65(PropertyMap)
+ Either lambda$static$74(PropertyMap)
+ ExtraCodecs$EitherCodec either(Codec,Codec)
- ExtraCodecs$TagOrElementLocation lambda$static$51(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$52(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$60(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$61(ResourceLocation)
- GameProfile lambda$static$70(GameProfile,PropertyMap)
+ GameProfile lambda$static$79(GameProfile,PropertyMap)
+ Int2IntMap lambda$int2IntMap$101(LongStream)
+ IntIntPair lambda$intIntPair$104(Long)
+ List lambda$sizeLimitedList$89(List,int)
+ Long lambda$intIntPair$105(IntIntPair)
+ LongStream lambda$int2IntMap$103(Int2IntMap)
- LongStream lambda$static$57(BitSet)
+ LongStream lambda$static$66(BitSet)
+ MapCodec recursiveMap(String,Function)
+ MapCodec strictOptionalField(Codec,String,Object)
+ MapCodec strictOptionalField(Codec,String)
+ MapCodec validate(MapCodec,Function)
+ Object lambda$strictOptionalField$49(Object,Optional)
+ Object lambda$withAlternative$95(Object)
+ Object lambda$withAlternative$96(Object)
+ Object lambda$withAlternative$97(Either)
+ Object lambda$withAlternative$98(Object)
+ Object lambda$withAlternative$99(Function,Either)
- Optional lambda$static$55(OptionalLong)
- Optional lambda$static$58(Property)
+ Optional lambda$static$64(OptionalLong)
+ Optional lambda$static$67(Property)
+ Optional lambda$strictOptionalField$50(Object,Object)
- OptionalLong lambda$static$54(Optional)
+ OptionalLong lambda$static$63(Optional)
- Property lambda$static$59(String,String,Optional)
+ Property lambda$static$68(String,String,Optional)
- PropertyMap lambda$static$64(Either)
+ PropertyMap lambda$static$73(Either)
- String lambda$ensureHomogenous$42(Object,Object,Object)
+ String lambda$ensureHomogenous$51(Object,Object,Object)
- String lambda$floatRangeMinExclusiveWithMessage$35(Function,Float)
+ String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
- String lambda$intRange$34(int,int,Integer)
+ String lambda$intRange$40(int,int,Integer)
- String lambda$intRangeWithMessage$30(Function,Integer)
+ String lambda$intRangeWithMessage$36(Function,Integer)
- String lambda$nonEmptyHolderSet$40()
+ String lambda$nonEmptyHolderSet$46()
- String lambda$nonEmptyList$38()
+ String lambda$nonEmptyList$44()
+ String lambda$sizeLimitedList$88(List,int)
- String lambda$sizeLimitedMap$76(Map,int)
+ String lambda$sizeLimitedMap$91(Map,int)
+ String lambda$sizeLimitedString$85(String,int,int,int)
+ String lambda$sizeLimitedString$86(String,int,int,int)
- String lambda$static$32(Integer)
- String lambda$static$33(Integer)
- String lambda$static$37(Float)
+ String lambda$static$38(Integer)
+ String lambda$static$39(Integer)
+ String lambda$static$43(Float)
- String lambda$static$44(String,PatternSyntaxException)
- String lambda$static$47()
- String lambda$static$49(byte[])
+ String lambda$static$53(String,PatternSyntaxException)
+ String lambda$static$56()
+ String lambda$static$58(byte[])
- String lambda$static$66(String)
- String lambda$static$72()
- String lambda$static$74(String)
+ String lambda$static$75(String)
- String lambda$static$78(String)
+ String lambda$static$81()
+ String lambda$static$83(String)
+ String lambda$static$93(String)
+ String lambda$stringResolverCodec$30(String)
+ String lambda$stringResolverCodec$33(Object)
+ void lambda$int2IntMap$100(Int2IntMap,long)
+ void lambda$int2IntMap$102(LongList,Integer,Integer)
- void lambda$static$61(PropertyMap,String,List)
- void lambda$static$62(PropertyMap,Map)
- void lambda$static$63(PropertyMap,List)
- void lambda$static$69(GameProfile,String,Property)
+ void lambda$static$70(PropertyMap,String,List)
+ void lambda$static$71(PropertyMap,Map)
+ void lambda$static$72(PropertyMap,List)
+ void lambda$static$78(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$7
</summary>

```diff
- boolean isEmptyMap(DynamicOps,Object)
+ DataResult decode(DynamicOps,MapLike)
- DataResult decode(DynamicOps,Object)
+ DataResult encode(Codec,Object,DynamicOps)
- DataResult encode(Object,DynamicOps,Object)
- DataResult encode(Optional,DynamicOps,Object)
+ DataResult lambda$decode$1(MapLike,String,DynamicOps,Function,Pair)
- Pair lambda$decode$0(Pair)
+ RecordBuilder encode(Object,DynamicOps,RecordBuilder)
+ Stream keys(DynamicOps)
+ String lambda$decode$0(String,MapLike)
- void <init>(Codec)
+ void <init>(String,String,Codec,Function,Function)
```

</details>
<details>
<summary>
net.minecraft.util.KeyDispatchDataCodec
</summary>

```diff
+ Codec codec()
+ KeyDispatchDataCodec of(Codec)
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- DSL$TypeReference reference(String)
+ String lambda$static$0()
+ String lambda$static$1()
+ String lambda$static$10()
+ String lambda$static$11()
+ String lambda$static$12()
+ String lambda$static$13()
+ String lambda$static$14()
+ String lambda$static$15()
+ String lambda$static$16()
+ String lambda$static$17()
+ String lambda$static$18()
+ String lambda$static$19()
+ String lambda$static$2()
+ String lambda$static$20()
+ String lambda$static$21()
+ String lambda$static$22()
+ String lambda$static$23()
+ String lambda$static$24()
+ String lambda$static$25()
+ String lambda$static$26()
+ String lambda$static$27()
+ String lambda$static$28()
+ String lambda$static$29()
+ String lambda$static$3()
+ String lambda$static$30()
+ String lambda$static$31()
+ String lambda$static$32()
+ String lambda$static$33()
+ String lambda$static$34()
+ String lambda$static$35()
+ String lambda$static$36()
+ String lambda$static$4()
+ String lambda$static$5()
+ String lambda$static$6()
+ String lambda$static$7()
+ String lambda$static$8()
+ String lambda$static$9()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
+ TypeTemplate lambda$registerTypes$24(Map)
- TypeTemplate lambda$registerTypes$24(Schema,Map)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.IntProvider
</summary>

```diff
+ Codec codec(int,int,Codec)
- Codec validateCodec(int,int,Codec)
+ DataResult lambda$codec$5(int,int,IntProvider)
- DataResult lambda$validateCodec$3(int,int,IntProvider)
- DataResult validate(int,int,IntProvider)
+ String lambda$codec$3(int,IntProvider)
+ String lambda$codec$4(int,IntProvider)
- String lambda$validate$4(int,IntProvider)
- String lambda$validate$5(int,IntProvider)
```

</details>
<details>
<summary>
net.minecraft.world.BossEvent
</summary>

```diff
+ int getRadius()
+ Vec3 getCenter()
+ void <init>(UUID,Component,BossEvent$BossBarColor,BossEvent$BossBarOverlay,Vec3,int)
- void <init>(UUID,Component,BossEvent$BossBarColor,BossEvent$BossBarOverlay)
+ void setLocation(Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.world.ContainerHelper
</summary>

```diff
+ int tryAddItem(Container,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffect
</summary>

```diff
- FeatureFlagSet requiredFeatures()
- MobEffect requiredFeatures(FeatureFlag[])
- MobEffect withSoundOnAdded(SoundEvent)
+ void lambda$createModifiers$2(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
- void lambda$createModifiers$3(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
- void lambda$onEffectAdded$2(LivingEntity,SoundEvent)
- void onEffectAdded(LivingEntity,int)
- void onMobHurt(LivingEntity,int,DamageSource,float)
- void onMobRemoved(LivingEntity,int,Entity$RemovalReason)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ int getColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
+ int getTotalValue()
+ void targetBlock(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.ZombieAttackGoal
</summary>

```diff
+ void <init>(PathfinderMob,double,boolean)
- void <init>(Zombie,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Bogged
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Creeper
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ BodyRotationControl createBodyControl()
+ boolean canJump()
+ boolean checkSpawnRules(LevelAccessor,MobSpawnType)
+ boolean isBuddy(Entity)
+ boolean isToxic()
+ double guardianStackRidingOffset()
+ Guardian createNormal(EntityType,Level)
+ Guardian createToxic(EntityType,Level)
+ LivingEntity getControllingPassenger()
+ RandomSource access$000(Guardian)
+ RandomSource access$100(Guardian)
+ Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void <init>(EntityType,Level,boolean)
- void <init>(EntityType,Level)
+ void actuallyHurt(DamageSource,float)
+ void applyPoisonFromWaterContact()
+ void lambda$actuallyHurt$0(Entity,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ void lerpMotion(double,double,double)
- void onDeflection()
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raid
</summary>

```diff
- boolean absorbRaidOmen(ServerPlayer)
+ int getBadOmenLevel()
+ int getMaxBadOmenLevel()
- int getMaxRaidOmenLevel()
- int getRaidOmenLevel()
+ void absorbBadOmen(Player)
+ void setBadOmenLevel(int)
- void setRaidOmenLevel(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raider
</summary>

```diff
- boolean hasRaid()
- boolean isCaptain()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.EnchantmentMenu
</summary>

```diff
- List getEnchantmentList(FeatureFlagSet,ItemStack,int,int)
+ List getEnchantmentList(ItemStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoneyBottleItem
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.item.MaceItem
</summary>

```diff
+ boolean isEnchantable(ItemStack)
+ boolean lambda$knockback$0(Player,Entity,LivingEntity)
- boolean lambda$knockbackPredicate$1(Player,Entity,LivingEntity)
- double getKnockbackPower(Player,LivingEntity,Vec3)
- int getEnchantmentValue()
- ItemAttributeModifiers createAttributes()
+ Multimap getDefaultAttributeModifiers(EquipmentSlot)
- Predicate knockbackPredicate(Player,Entity)
+ void <clinit>()
- void lambda$knockback$0(Entity,Player,LivingEntity)
+ void lambda$knockback$1(Entity,Level,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.MobBucketItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.PotionItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.SmithingTemplateItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.SpectralArrowItem
</summary>

```diff
- Projectile asProjectile(Level,Position,ItemStack,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.item.SuspiciousStewItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ThrowablePotionItem
</summary>

```diff
- Projectile asProjectile(Level,Position,ItemStack,Direction)
- ProjectileItem$DispenseConfig createDispenseConfig()
```

</details>
<details>
<summary>
net.minecraft.world.item.TippedArrowItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
- float calculateArmorBreach(Entity,float)
- ItemStack enchantItem(FeatureFlagSet,RandomSource,ItemStack,int,boolean)
+ ItemStack enchantItem(RandomSource,ItemStack,int,boolean)
- List getAvailableEnchantmentResults(FeatureFlagSet,int,ItemStack,boolean)
+ List getAvailableEnchantmentResults(int,ItemStack,boolean)
- List selectEnchantment(FeatureFlagSet,RandomSource,ItemStack,int,boolean)
+ List selectEnchantment(RandomSource,ItemStack,int,boolean)
- void doPostItemStackHurtEffects(LivingEntity,Entity,ItemEnchantments)
```

</details>
<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
+ boolean isPotato()
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
+ Player getNearestPlayer(BlockPos,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean isPotato()
+ boolean noCollision(Entity,AABB,boolean)
+ float adjustPreciptiationToClouds(float,double)
+ float getRainLevel(float,double)
+ float getThunderLevel(float,double)
+ SubGrid createSubGrid(GridCarrier)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.TheEndBiomeSource
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntity
</summary>

```diff
+ BlockEntity lambda$loadStatic$0(BlockPos,BlockState,String,BlockEntityType)
+ BlockEntity lambda$loadStatic$1(CompoundTag,HolderLookup$Provider,String,BlockEntity)
+ BlockEntity lambda$loadStatic$2(String)
- BlockEntity lambda$loadStatic$4(BlockPos,BlockState,String,BlockEntityType)
- BlockEntity lambda$loadStatic$5(CompoundTag,HolderLookup$Provider,String,BlockEntity)
- BlockEntity lambda$loadStatic$6(String)
- CompoundTag saveCustomAndMetadata(HolderLookup$Provider)
- CompoundTag saveCustomOnly(HolderLookup$Provider)
- DataComponentMap components()
+ String lambda$fillCrashReportCategory$3()
- String lambda$fillCrashReportCategory$7()
- void applyComponents(DataComponentMap,DataComponentPatch)
+ void applyComponents(DataComponentMap)
- void applyComponentsFromItemStack(ItemStack)
- void applyImplicitComponents(BlockEntity$DataComponentInput)
+ void collectComponents(DataComponentMap$Builder)
- void collectImplicitComponents(DataComponentMap$Builder)
- void lambda$loadWithComponents$0(String)
- void lambda$loadWithComponents$1(DataComponentMap)
- void lambda$saveWithoutMetadata$2(String)
- void lambda$saveWithoutMetadata$3(CompoundTag,Tag)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
- void loadCustomOnly(CompoundTag,HolderLookup$Provider)
- void loadWithComponents(CompoundTag,HolderLookup$Provider)
- void setComponents(DataComponentMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.LecternBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity
</summary>

```diff
+ void lambda$load$0(VibrationSystem$Data)
- void lambda$loadAdditional$0(VibrationSystem$Data)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
</summary>

```diff
+ void lambda$load$1(VibrationSystem$Data)
- void lambda$loadAdditional$1(VibrationSystem$Data)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
</summary>

```diff
+ void lambda$load$0(BlockPos)
- void lambda$loadAdditional$0(BlockPos)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
</summary>

```diff
+ void lambda$load$0(TrialSpawner)
- void lambda$loadAdditional$0(TrialSpawner)
- void lambda$saveAdditional$2(DataResult$Error)
+ void lambda$saveAdditional$2(DataResult$PartialResult)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
</summary>

```diff
- void lambda$static$0(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$0(Level,RandomSource,BlockPos)
- void lambda$static$1(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$1(Level,RandomSource,BlockPos)
- void lambda$static$2(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$2(Level,RandomSource,BlockPos)
- void lambda$static$3(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$3(Level,RandomSource,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
</summary>

```diff
- void emitActivationParticles(Level,BlockPos,BlockState,VaultSharedData,ParticleOptions)
+ void emitActivationParticles(Level,BlockPos,BlockState,VaultSharedData)
- void emitDeactivationParticles(Level,BlockPos,ParticleOptions)
+ void emitDeactivationParticles(Level,BlockPos)
- void emitIdleParticles(Level,BlockPos,VaultSharedData,ParticleOptions)
+ void emitIdleParticles(Level,BlockPos,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
- void onTransition(ServerLevel,BlockPos,VaultState,VaultConfig,VaultSharedData,boolean)
+ void onTransition(ServerLevel,BlockPos,VaultState,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState$2
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState$4
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ boolean isPotato()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerators
</summary>

```diff
+ Codec bootstrap(Registry)
- MapCodec bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.LevelEntityGetter
</summary>

```diff
+ LevelEntityGetter empty()
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
+ int bottomGenerationPadding()
+ NoiseGeneratorSettings potato(BootstrapContext)
- void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,boolean,boolean,boolean,boolean)
+ void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,int,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
+ DensityFunction slidePotato(HolderGetter)
+ NoiseRouter noNewCavesWithExtraZing(HolderGetter,HolderGetter,DensityFunction)
+ NoiseRouter potato(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSettings
</summary>

```diff
- void lambda$create$4(DataResult$Error)
+ void lambda$create$4(DataResult$PartialResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
</summary>

```diff
+ Codec bootstrap(Registry)
+ Codec lambda$static$0(SurfaceRules$ConditionSource)
- MapCodec bootstrap(Registry)
- MapCodec lambda$static$0(SurfaceRules$ConditionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
</summary>

```diff
+ Codec bootstrap(Registry)
+ Codec lambda$static$0(SurfaceRules$RuleSource)
- MapCodec bootstrap(Registry)
- MapCodec lambda$static$0(SurfaceRules$RuleSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor
</summary>

```diff
+ Record lambda$merge$0(Either)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldDimensions
</summary>

```diff
+ boolean isStablePotato(LevelStem)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
</summary>

```diff
+ BlockPredicateType register(String,Codec)
- BlockPredicateType register(String,MapCodec)
+ Codec lambda$register$0(Codec)
- MapCodec lambda$register$0(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ Codec configuredCodec()
- MapCodec configuredCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.Feature
</summary>

```diff
+ Codec configuredCodec()
- MapCodec configuredCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$3(RecordCodecBuilder$Instance)
+ BlockState lambda$static$0(ColumnFeatureConfiguration)
+ BlockState state()
- IntProvider lambda$static$0(ColumnFeatureConfiguration)
+ IntProvider lambda$static$2(ColumnFeatureConfiguration)
+ void <init>(BlockState,IntProvider,IntProvider)
- void <init>(IntProvider,IntProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
</summary>

```diff
+ Codec codec()
+ FeatureSizeType register(String,Codec)
- FeatureSizeType register(String,MapCodec)
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
</summary>

```diff
+ BlockStateProviderType register(String,Codec)
- BlockStateProviderType register(String,MapCodec)
+ Codec codec()
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
</summary>

```diff
+ App lambda$static$2(RecordCodecBuilder$Instance)
- boolean lambda$place$3(int,BlockPos)
+ boolean lambda$place$5(int,BlockPos)
- boolean lambda$place$5(TreeDecorator$Context,BlockPos)
+ boolean lambda$place$7(TreeDecorator$Context,BlockPos)
+ Boolean lambda$static$1(BeehiveDecorator)
- boolean lambda$static$1(Direction)
+ boolean lambda$static$3(Direction)
- Direction[] lambda$static$2(int)
+ Direction[] lambda$static$4(int)
- Stream lambda$place$4(BlockPos)
+ Stream lambda$place$6(BlockPos)
+ void <init>(float,boolean)
- void <init>(float)
- void lambda$place$6(RandomSource,BeehiveBlockEntity)
+ void lambda$place$8(RandomSource,BeehiveBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
</summary>

```diff
+ Codec codec()
- MapCodec codec()
+ TrunkPlacerType register(String,Codec)
- TrunkPlacerType register(String,MapCodec)
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
</summary>

```diff
+ Codec lambda$register$0(Codec)
+ HeightProviderType register(String,Codec)
- HeightProviderType register(String,MapCodec)
- MapCodec lambda$register$0(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
</summary>

```diff
+ List densityChecks()
+ void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,long,ChunkPos,LevelHeightAccessor,Predicate,List)
- void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,long,ChunkPos,LevelHeightAccessor,Predicate)
+ void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,WorldgenRandom,long,ChunkPos,LevelHeightAccessor,Predicate,List)
- void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,WorldgenRandom,long,ChunkPos,LevelHeightAccessor,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
</summary>

```diff
+ List densityChecks()
+ void <init>(HolderSet,List,Map,GenerationStep$Decoration,TerrainAdjustment)
- void <init>(HolderSet,Map,GenerationStep$Decoration,TerrainAdjustment)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ boolean lambda$run$4(Holder$Reference)
- boolean lambda$run$4(LootContext,Holder$Reference)
+ boolean lambda$run$5(boolean,ItemStack,Holder$Reference)
- boolean lambda$run$5(Holder$Reference)
- boolean lambda$run$6(boolean,ItemStack,Holder$Reference)
+ LootItemFunction lambda$randomApplicableEnchantment$7(List)
- LootItemFunction lambda$randomApplicableEnchantment$8(List)
+ Optional lambda$run$6(ItemStack,RandomSource)
- Optional lambda$run$7(ItemStack,LootContext,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ListOperation
</summary>

```diff
+ Codec lambda$codec$0(ListOperation$Type)
- MapCodec lambda$codec$0(ListOperation$Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootItemFunctions
</summary>

```diff
+ LootItemFunctionType register(String,Codec)
- LootItemFunctionType register(String,MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
+ App lambda$static$1(RecordCodecBuilder$Instance)
- App lambda$static$2(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(SetAttributesFunction)
+ ItemAttributeModifiers lambda$run$3(LootContext,ItemAttributeModifiers)
- ItemAttributeModifiers lambda$run$4(LootContext,ItemStack,ItemAttributeModifiers)
- ItemAttributeModifiers updateModifiers(LootContext,ItemAttributeModifiers)
+ Stream lambda$getReferencedContextParams$2(SetAttributesFunction$Modifier)
- Stream lambda$getReferencedContextParams$3(SetAttributesFunction$Modifier)
- void <init>(List,List,boolean)
+ void <init>(List,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemConditions
</summary>

```diff
+ LootItemConditionType register(String,Codec)
- LootItemConditionType register(String,MapCodec)
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
+ net.minecraft.Maybe
+ XXX.advancements.critereon.PotatoPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$ItemStackPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$StandardItemStackPredicate
+ XXX.advancements.critereon.PotatoRefinementTrigger$Type
- XXX.advancements.critereon.RaiderPredicate
+ XXX.advancements.critereon.ThrowLubricatedTrigger$TriggerInstance
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.PoisonousPotatoAdvancements
+ XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$JukeboxListener
+ XXX.animal.allay.Allay$VibrationUser
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.armadillo.Armadillo
+ XXX.animal.armadillo.Armadillo$1
- XXX.animal.frog.package-info
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
+ XXX.animal.sniffer.Sniffer
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
- XXX.arguments.selector.package-info
+ XXX.blaze3d.vertex.package-info
+ XXX.blaze3d.vertex.VertexFormat$IndexType
- XXX.blaze3d.vertex.VertexFormat$Mode
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$ClearState
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
+ XXX.blaze3d.vertex.VertexSorting
- XXX.blaze3d.vertex.VertexSorting$DistanceFunction
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
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BeehiveBlockEntity$Occupant
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BigBrainBlockEntity
- XXX.block.entity.BlockEntity$ComponentHelper
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
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
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FletchingBlockEntity
+ XXX.block.entity.FletchingBlockEntity$Fletching
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.HangingSignBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.InventoryHeatComponent
+ XXX.block.entity.LubricationComponent
+ XXX.block.entity.PotatoBaneComponent
+ XXX.block.entity.PotatoRefineryBlockEntity$1
+ XXX.block.entity.PotatoRefineryBlockEntity$NormalRecipe
+ XXX.block.entity.PotatoRefineryBlockEntity$SomeKindOfRecipe
- XXX.block.entity.PotDecorations
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SkullBlockEntity$1
- XXX.block.entity.SkullBlockEntity$2
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
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
+ XXX.client.grid.ClientSubGrid
+ XXX.client.grid.SubGridMeshBuilder$BlockView
+ XXX.client.grid.SubGridRenderer
+ XXX.client.gui.GuiGraphics$DrawString
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$QuickPlayData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableHierarchicalModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AllayModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmadilloModel
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BatModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
+ XXX.client.model.ParrotModel$1
- XXX.client.model.ParrotModel$State
+ XXX.client.model.PhantomModel
+ XXX.client.model.PiglinHeadModel
- XXX.client.model.PiglinModel
- XXX.client.model.PigModel
+ XXX.client.model.PlayerModel
+ XXX.client.multiplayer.LevelLoadStatusManager$1
- XXX.client.multiplayer.LevelLoadStatusManager$Status
+ XXX.client.multiplayer.MultiPlayerGameMode
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
- XXX.client.particle.FlyStraightTowardsParticle
- XXX.client.particle.FlyTowardsPositionParticle
+ XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider
- XXX.client.particle.FlyTowardsPositionParticle$NautilusProvider
+ XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
+ XXX.client.particle.FootprintParticle$Provider
- XXX.client.particle.GlowParticle
+ XXX.client.particle.GlowParticle$ElectricSparkProvider
- XXX.client.particle.GlowParticle$GlowSquidProvider
+ XXX.client.particle.GlowParticle$ScrapeProvider
- XXX.client.particle.GlowParticle$WaxOffProvider
+ XXX.client.particle.GlowParticle$WaxOnProvider
- XXX.client.particle.GustParticle
+ XXX.client.particle.GustParticle$Provider
- XXX.client.particle.GustParticle$SmallProvider
- XXX.client.particle.package-info
- XXX.client.particle.TerrainParticle$DustPillarProvider
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
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
- XXX.client.player.Input
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
+ XXX.client.renderer.BlockEntityWithoutLevelRenderer
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
+ XXX.client.renderer.DimensionSpecialEffects$PotatoEffects
- XXX.client.searchtree.FullTextSearchTree
+ XXX.client.searchtree.IdSearchTree
- XXX.client.searchtree.IntersectionIterator
+ XXX.client.searchtree.MergingUniqueIterator
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.PlainTextSearchTree
+ XXX.client.searchtree.RefreshableSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree$1
- XXX.client.searchtree.ResourceLocationSearchTree$2
+ XXX.client.searchtree.SearchRegistry
- XXX.client.searchtree.SearchRegistry$Key
+ XXX.client.searchtree.SearchRegistry$TreeBuilderSupplier
- XXX.client.searchtree.SearchRegistry$TreeEntry
+ XXX.client.searchtree.SearchTree
- XXX.client.searchtree.SuffixArray
- XXX.client.server.IntegratedPlayerList
+ XXX.client.server.IntegratedServer
- XXX.client.server.LanServer
+ XXX.client.server.LanServerDetection
- XXX.client.server.LanServerDetection$LanServerDetector
+ XXX.client.server.LanServerDetection$LanServerList
- XXX.client.server.LanServerPinger
+ XXX.client.server.package-info
- XXX.client.sounds.AudioStream
+ XXX.client.sounds.ChannelAccess
- XXX.client.sounds.ChannelAccess$ChannelHandle
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
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
- XXX.client.tutorial.BundleTutorial
+ XXX.client.tutorial.CompletedTutorialStepInstance
- XXX.client.tutorial.CraftPlanksTutorialStep
+ XXX.client.tutorial.FindTreeTutorialStepInstance
- XXX.client.tutorial.MovementTutorialStepInstance
+ XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
- XXX.client.tutorial.PunchTreeTutorialStepInstance
+ XXX.client.tutorial.Tutorial
- XXX.client.tutorial.Tutorial$TimedToast
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
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
- XXX.commands.arguments.package-info
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
- XXX.components.debugchart.AbstractDebugChart
+ XXX.components.debugchart.BandwidthDebugChart
- XXX.components.debugchart.FpsDebugChart
+ XXX.components.debugchart.PingDebugChart
- XXX.components.debugchart.TpsDebugChart
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
+ XXX.components.toasts.SystemToast$SystemToastId
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
- XXX.core.component.DataComponentPredicate
+ XXX.core.component.DataComponentPredicate$Builder
+ XXX.core.component.DataComponents
- XXX.core.component.DataComponentType
+ XXX.core.component.DataComponentType$Builder
- XXX.core.component.DataComponentType$Builder$SimpleType
+ XXX.core.component.package-info
- XXX.core.component.PatchedDataComponentMap
+ XXX.core.component.TypedDataComponent
- XXX.core.component.TypedDataComponent$1
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$22
+ XXX.core.dispenser.DispenseItemBehavior$24
+ XXX.core.dispenser.DispenseItemBehavior$26
+ XXX.core.dispenser.DispenseItemBehavior$28
+ XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.ColorParticleOption
+ XXX.core.particles.ColorParticleOption$1
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
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
+ XXX.data.info.ItemListReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLootSubProvider
+ XXX.data.loot.EntityLootSubProvider
- XXX.data.loot.LootTableProvider
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
+ XXX.data.tags.UpdateOneTwentyOneBannerPatternTagsProvider
- XXX.data.tags.UpdateOneTwentyOneBiomeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneBlockTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneDamageTypes
- XXX.data.tags.UpdateOneTwentyOneDamageTypeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneItemTagsProvider
- XXX.data.tags.UpdateOneTwentyOneStructureTagsProvider
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
+ XXX.data.worldgen.ColosseumPieces
+ XXX.data.worldgen.PotatoVillagePools
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
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
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
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
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
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FixProjectileStoredItem
- XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
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
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackComponentRemainderFix
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
+ XXX.datafix.fixes.TippedArrowPotionToItemFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.TrialSpawnerConfigFix
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
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
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
+ XXX.entity.animal.Pig$1
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
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
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
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
- XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.entity.animal.WolfVariant
- XXX.entity.animal.WolfVariants
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.BreezeEyesLayer
- XXX.entity.layers.BreezeWindLayer
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
+ XXX.entity.layers.MegaSpudArmorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.monster.Guardian$2
+ XXX.entity.monster.Guardian$4
+ XXX.entity.monster.Guardian$6
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.MegaSpud
+ XXX.entity.monster.MegaSpud$GhastShootFireballGoal
+ XXX.entity.monster.MegaSpud$SlimeMoveControl
+ XXX.entity.monster.MegaSpud$Stage
- XXX.entity.monster.package-info
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
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$2
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
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.LashingPotatoHook
- XXX.entity.projectile.LlamaSpit
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
+ XXX.entity.projectile.VineProjectile
- XXX.entity.trialspawner.TrialSpawner$FlameParticle
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerData
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$1
- XXX.entity.vault.package-info
+ XXX.entity.vault.VaultState$LightLevel
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
- XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.VehicleEntity
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
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
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
+ XXX.gui.components.MultiLineLabel$TextWithWidth
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
+ XXX.gui.components.package-info
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerSkinWidget
+ XXX.gui.components.PlayerSkinWidget$Model
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$HealthState
- XXX.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ XXX.gui.components.PopupScreen
- XXX.gui.components.PopupScreen$Builder
+ XXX.gui.components.PopupScreen$ButtonOption
- XXX.gui.components.Renderable
+ XXX.gui.components.SplashRenderer
- XXX.gui.components.SpriteIconButton
+ XXX.gui.components.SpriteIconButton$Builder
- XXX.gui.components.SpriteIconButton$CenteredIcon
+ XXX.gui.components.SpriteIconButton$TextAndIcon
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.StringWidget
- XXX.gui.components.SubtitleOverlay
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
- XXX.gui.font.TextFieldHelper
+ XXX.gui.font.TextFieldHelper$1
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
+ XXX.gui.navigation.ScreenDirection
+ XXX.gui.screens.package-info
+ XXX.gui.screens.PotatoPoemScreen$CreditsReader
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
+ XXX.gui.screens.RealmsLongConfirmationScreen
- XXX.gui.screens.RealmsLongConfirmationScreen$Type
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
- XXX.gui.screens.RealmsPopupScreen
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
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.SproutRespawnScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$WarningLabel
- XXX.gui.screens.UnsupportedGraphicsWarningScreen
+ XXX.gui.screens.UnsupportedGraphicsWarningScreen$ButtonOption
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$Builder
- XXX.gui.screens.VideoSettingsScreen
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
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
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
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
+ XXX.item.armortrim.TrimMaterial
- XXX.item.armortrim.TrimMaterials
+ XXX.item.armortrim.TrimPattern
- XXX.item.armortrim.TrimPatterns
+ XXX.item.armortrim.UpdateOneTwentyOneArmorTrims
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BookContent
+ XXX.item.component.BundleContents
- XXX.item.component.BundleContents$Mutable
+ XXX.item.component.ChargedProjectiles
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
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
+ XXX.item.component.package-info
+ XXX.item.component.ResolvableProfile
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SnekComponent
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
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
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.PotatoRefinementRecipe
- XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator
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
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$3
+ XXX.level.block.BigBrainBlock
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
+ XXX.level.block.CrafterBlock
- XXX.level.block.CrafterBlock$1
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
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
+ XXX.level.block.FloataterBlock
+ XXX.level.block.Mirror
+ XXX.level.block.package-info
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PinkPetalsBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBatteryBlock
- XXX.level.block.PotatoBlock
+ XXX.level.block.PotatoPeelsBlock
+ XXX.level.block.PotatoRefineryBlock
+ XXX.level.block.PotatoZombieHeadBlock
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
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
+ XXX.level.block.StrongRootsBlock$FoundPos
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SuspiciousEffectHolder
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
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
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VaultBlock
+ XXX.level.block.WeakRootsBlock
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
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.ChunkSkyLightSources
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$ConstantLayer
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
+ XXX.level.pathfinder.PathfindingContext
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
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Factory
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
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
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
+ XXX.levelgen.feature.DripstoneUtilsFlex
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
+ XXX.levelgen.feature.ParkLaneSurfaceFeature
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.PotatoBudsFeature
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
+ XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.placement.CloudPlacement
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
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
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
+ XXX.loot.functions.CopyComponentsFunction$1
- XXX.loot.functions.SetNameFunction$Target
- XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneBlockLoot
+ XXX.loot.packs.UpdateOneTwentyOneChestLoot
- XXX.loot.packs.UpdateOneTwentyOneEntityLoot
- XXX.loot.packs.VanillaEquipmentLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.minecraft.client.GraphicsStatus$1
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.GuiMessage$Line
- XXX.minecraft.client.GuiMessageTag
+ XXX.minecraft.client.GuiMessageTag$Icon
- XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.InputType
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
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.PeriodicNotificationManager
+ XXX.minecraft.client.PeriodicNotificationManager$Notification
- XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
+ XXX.minecraft.client.PrioritizeChunkUpdates
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
+ XXX.minecraft.core.Cloner
- XXX.minecraft.core.Cloner$Factory
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedMappedRegistry
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
+ XXX.minecraft.core.package-info
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
- XXX.minecraft.server.package-info
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
- XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
+ XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerInfo
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.ServerTickRateManager
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$1
+ XXX.minecraft.util.ExtraCodecs$9
+ XXX.minecraft.util.ExtraCodecs$RecursiveCodec
+ XXX.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ABGR32
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.JavaOps$1
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
+ XXX.minecraft.util.PngInfo
- XXX.minecraft.util.ProblemReporter
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
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
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
+ XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TaskChainer
- XXX.minecraft.util.TaskChainer$1
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
+ XXX.minecraft.world.RandomizableContainer
- XXX.minecraft.world.RandomSequence
+ XXX.minecraft.world.RandomSequences
- XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.TickRateManager
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
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
- XXX.mojang.math.Axis
+ XXX.mojang.math.Constants
- XXX.mojang.math.Divisor
+ XXX.mojang.math.FieldsAreNonnullByDefault
- XXX.mojang.math.GivensParameters
+ XXX.mojang.math.MatrixUtil
- XXX.mojang.math.MethodsReturnNonnullByDefault
+ XXX.mojang.math.OctahedralGroup
- XXX.mojang.math.OctahedralGroup$1
+ XXX.mojang.math.package-info
+ XXX.mojang.math.SymmetricGroup3
- XXX.mojang.math.Transformation
- XXX.mojang.realmsclient.package-info
- XXX.mojang.realmsclient.RealmsAvailability
+ XXX.mojang.realmsclient.RealmsAvailability$1
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
+ XXX.network.chat.FilterMask$1
- XXX.network.chat.FilterMask$Type
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$Action$1
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.HoverEvent$LegacyConverter
- XXX.network.chat.HoverEvent$TypedHoverEvent
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
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.RemoteChatSession
- XXX.network.chat.RemoteChatSession$Data
+ XXX.network.chat.SignableCommand
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
+ XXX.network.chat.SignedMessageChain
- XXX.network.chat.SignedMessageChain$1
+ XXX.network.codec.ByteBufCodecs$28
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
- XXX.network.codec.StreamCodec
+ XXX.network.codec.StreamCodec$1
- XXX.network.codec.StreamCodec$10
+ XXX.network.codec.StreamCodec$11
- XXX.network.codec.StreamCodec$12
+ XXX.network.codec.StreamCodec$13
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
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
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
- XXX.pools.alias.Direct
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.Random
+ XXX.pools.alias.RandomGroup
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
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
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundBundleDelimiterPacket
- XXX.protocol.game.ClientboundBundlePacket
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
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
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
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
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundSoundSequencePacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
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
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
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
+ XXX.protocol.handshake.ClientIntent
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.realmsclient.gui.package-info
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
+ XXX.realmsclient.util.JsonUtils
- XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.TextRenderingUtils
+ XXX.realmsclient.util.TextRenderingUtils$Line
- XXX.realmsclient.util.TextRenderingUtils$LineSegment
+ XXX.realmsclient.util.UploadTokenCache
- XXX.realmsclient.util.WorldGenerationInfo
+ XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
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
+ XXX.renderer.entity.BatatoRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.GridCarrierEntityRenderer
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
+ XXX.renderer.entity.MegaSpudRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NoopRenderer
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.PoisonousPotatoZombieRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RabbitRenderer$1
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnifferRenderer
- XXX.renderer.entity.SnowGolemRenderer
+ XXX.renderer.entity.SpectralArrowRenderer
- XXX.renderer.entity.SpiderRenderer
+ XXX.renderer.entity.SquidRenderer
- XXX.renderer.entity.StrayRenderer
+ XXX.renderer.entity.StriderRenderer
- XXX.renderer.entity.TadpoleRenderer
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TropicalFishRenderer$1
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
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
+ XXX.resources.server.package-info
+ XXX.resources.server.ServerPackManager$2
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
+ XXX.resources.sounds.package-info
+ XXX.resources.sounds.RidingMinecartSoundInstance
- XXX.resources.sounds.SimpleSoundInstance
+ XXX.resources.sounds.SnifferSoundInstance
- XXX.resources.sounds.Sound
+ XXX.resources.sounds.Sound$Type
- XXX.resources.sounds.SoundEventRegistration
+ XXX.resources.sounds.SoundEventRegistrationSerializer
- XXX.resources.sounds.SoundInstance
+ XXX.resources.sounds.SoundInstance$Attenuation
- XXX.resources.sounds.TickableSoundInstance
+ XXX.resources.sounds.UnderwaterAmbientSoundHandler
- XXX.resources.sounds.UnderwaterAmbientSoundInstances
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
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
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
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
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HangingSignEditScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
+ XXX.screens.inventory.PotatoRefineryScreen
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.social.package-info
+ XXX.screens.social.SocialInteractionsScreen$2
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
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ XXX.screens.worldselection.CreateWorldScreen$GameTab
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
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
+ XXX.screens.worldselection.ExperimentsScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
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
+ XXX.server.level.package-info
+ XXX.server.level.ServerLevel$1Builder
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
+ XXX.server.network.Filterable
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
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
+ XXX.state.properties.ChestType$1
+ XXX.storage.loot.BuiltInLootTables
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
+ XXX.storage.loot.ValidationContext
- XXX.structure.placement.package-info
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
- XXX.util.datafix.ComponentDataFixUtils
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.FixWolfHealth
- XXX.util.datafix.PackedBitStorage
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.CreateSnapshotRealmTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
- XXX.util.task.package-info
+ XXX.util.task.RealmCreationTask
- XXX.util.task.ResettingGeneratedWorldTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
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
- XXX.world.effect.InfestedMobEffect
- XXX.world.effect.OozingMobEffect
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RaidOmenMobEffect
- XXX.world.effect.WindChargedMobEffect
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
- XXX.world.entity.EquipmentSlotGroup$1
+ XXX.world.entity.ExperienceOrb$PlayerTarget
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
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
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
- XXX.world.entity.package-info
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
+ XXX.world.food.FoodProperties$PossibleEffect
- XXX.world.food.Foods
+ XXX.world.food.package-info
+ XXX.world.grid.GridCarrier
+ XXX.world.grid.SubGrid
+ XXX.world.grid.SubGridBlocks$1
+ XXX.world.grid.SubGridLightEngine
+ XXX.world.grid.SubGridMovementCollider
+ XXX.world.inventory.FletchingMenu
+ XXX.world.inventory.FletchingMenu$IngredientsSlot
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
- XXX.world.inventory.ItemCombinerMenu$3
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
+ XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.PoisonousPotatoCutterMenu
+ XXX.world.inventory.PoisonousPotatoCutterMenu$2
+ XXX.world.inventory.PotatoRefineryMenu$FuelSlot
+ XXX.world.inventory.RecipeBookMenu
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
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorItem$Type
+ XXX.world.item.ArmorMaterial
- XXX.world.item.ArmorMaterial$Layer
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
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
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
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
+ XXX.world.item.HotPotatoItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$2
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.OminousBottleItem
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
+ XXX.world.item.PoisonousPotatoPlantItem
+ XXX.world.item.PotatoEyeItem
+ XXX.world.item.PotatoOfKnowledgeItem
+ XXX.world.item.PotatoPeelerItem
- XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
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
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
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
+ XXX.worldgen.biome.BiomeData
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.PotatoBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.EntitySubPredicates +1P -1P
```
```
XXX.minecraft.client.StringSplitter$1 -1P
```
```
XXX.client.gui.Gui -1M | -2P
```
```
XXX.gui.components.BossHealthOverlay$1 +1M -2M
```
```
XXX.gui.narration.ScreenNarrationCollector$1 -1P
```
```
XXX.gui.screens.DeathScreen +1M
```
```
XXX.gui.screens.OptionsScreen +1P
```
```
XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos -1P
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry -1P
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry -1P
```
```
XXX.client.multiplayer.AccountProfileKeyPairManager +2M -4M
```
```
XXX.client.multiplayer.ClientConfigurationPacketListenerImpl +1M | +1P
```
```
XXX.client.multiplayer.CommonListenerCookie +2M -1M | +1P
```
```
XXX.multiplayer.chat.LoggedChatMessage$System +1P -1P
```
```
XXX.client.particle.PortalParticle$Provider +1M -1M | -3P
```
```
XXX.client.particle.ReversePortalParticle$ReversePortalProvider +1M -1M | -3P
```
```
XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1 -1P
```
```
XXX.client.renderer.LevelRenderer -2M | -2P
```
```
XXX.client.renderer.ShaderInstance -1M
```
```
XXX.renderer.block.BlockRenderDispatcher +1M -1M
```
```
XXX.renderer.block.LiquidBlockRenderer +1M -1M
```
```
XXX.renderer.entity.ElderGuardianRenderer +1M -1M | -1P
```
```
XXX.renderer.entity.EntityRenderers +2M -7M
```
```
XXX.renderer.entity.LivingEntityRenderer -2M
```
```
XXX.entity.layers.SheepFurLayer -1P
```
```
XXX.renderer.item.ItemProperties -4M
```
```
XXX.texture.atlas.SpriteSourceList$1 -1P
```
```
XXX.texture.atlas.SpriteSources +1M -1M
```
```
XXX.atlas.sources.DirectoryLister +1P -1P
```
```
XXX.atlas.sources.PalettedPermutations +1P -1P
```
```
XXX.atlas.sources.SingleFile +1P -1P
```
```
XXX.atlas.sources.Unstitcher +1P -1P
```
```
XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border +1M -2M
```
```
XXX.metadata.gui.GuiSpriteScaling$Tile +1P -1P
```
```
XXX.minecraft.core.UUIDUtil -6M
```
```
XXX.core.component.DataComponentMap +2M -1M | +1P
```
```
XXX.core.dispenser.DispenseItemBehavior$1 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$11 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$13 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$15 -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$17 -1P
```
```
XXX.core.dispenser.DispenseItemBehavior$4 +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$6 +1M -4M | +1P
```
```
XXX.worldgen.features.MiscOverworldFeatures -2P
```
```
XXX.worldgen.features.OreFeatures -4P
```
```
XXX.worldgen.features.TreeFeatures -3P
```
```
XXX.worldgen.placement.NetherPlacements -5P
```
```
XXX.worldgen.placement.VegetationPlacements -9P
```
```
XXX.gametest.framework.GameTestHelper$2 -1P
```
```
XXX.gametest.framework.GameTestServer$1 -1P
```
```
XXX.network.chat.ComponentSerialization +5M -6M
```
```
XXX.network.chat.SignedMessageChain$Decoder +1M
```
```
XXX.chat.numbers.NumberFormatTypes -1M
```
```
XXX.network.codec.ByteBufCodecs$11 +3M -3M | +1P
```
```
XXX.network.codec.ByteBufCodecs$13 +5M -3M | +2P -1P
```
```
XXX.network.codec.ByteBufCodecs$15 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$17 +3M -3M | +1P
```
```
XXX.network.codec.ByteBufCodecs$19 +4M -3M | +2P -1P
```
```
XXX.network.codec.ByteBufCodecs$20 +5M -4M | +2P -4P
```
```
XXX.network.codec.ByteBufCodecs$22 +4M -3M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$24 +3M -4M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$26 +2M -4M | -4P
```
```
XXX.protocol.game.ClientboundBossEventPacket$Handler +1M -2M
```
```
XXX.protocol.game.ClientboundBossEventPacket$OperationType -1P
```
```
XXX.protocol.game.CommonPlayerSpawnInfo +1M -2M | -1P
```
```
XXX.minecraft.resources.RegistryDataLoader -2M
```
```
XXX.minecraft.server.PlayerAdvancements -1M
```
```
XXX.server.commands.RaidCommand +2M -2M
```
```
XXX.server.dedicated.ServerWatchdog$1 -1P
```
```
XXX.server.gui.MinecraftServerGui$2 -1P
```
```
XXX.server.level.ServerBossEvent -2M
```
```
XXX.minecraft.stats.StatFormatter -1M | -1P
```
```
XXX.minecraft.stats.Stats -4P
```
```
XXX.minecraft.tags.BiomeTags -4P
```
```
XXX.minecraft.tags.EntityTypeTags +2P
```
```
XXX.minecraft.tags.PaintingVariantTags -1P
```
```
XXX.minecraft.tags.StructureTags -2P
```
```
XXX.minecraft.util.ExtraCodecs +50M -93M | -1P
```
```
XXX.minecraft.util.ExtraCodecs$7 +6M -7M | +1P -5P
```
```
XXX.minecraft.util.KeyDispatchDataCodec +2M -3M | +1P -1P
```
```
XXX.datafix.fixes.References +1M -37M
```
```
XXX.datafix.schemas.V99 +1M -1M
```
```
XXX.util.valueproviders.BiasedToBottomInt +1P -1P
```
```
XXX.util.valueproviders.ClampedNormalFloat +1P -1P
```
```
XXX.util.valueproviders.ConstantFloat +1P -1P
```
```
XXX.util.valueproviders.IntProvider +5M -4M
```
```
XXX.util.valueproviders.TrapezoidFloat +1P -1P
```
```
XXX.util.valueproviders.UniformInt +1P -1P
```
```
XXX.minecraft.world.BossEvent +1M -4M | -2P
```
```
XXX.minecraft.world.ContainerHelper -1M
```
```
XXX.world.effect.MobEffect +8M -1M | +2P
```
```
XXX.world.entity.AreaEffectCloud -1M | -1P
```
```
XXX.world.entity.EntityEvent -1P
```
```
XXX.world.entity.ExperienceOrb -2M | +1P -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$1 -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$3 -1P
```
```
XXX.behavior.declarative.BehaviorBuilder$Instance$5 -1P
```
```
XXX.ai.goal.ZombieAttackGoal +1M -1M | +1P -1P
```
```
XXX.entity.decoration.PaintingVariants -7P
```
```
XXX.entity.monster.Bogged -1M
```
```
XXX.entity.monster.Creeper -1M
```
```
XXX.entity.monster.EnderMan -1M
```
```
XXX.entity.monster.Guardian +1M -16M | -3P
```
```
XXX.entity.monster.Phantom$PhantomLookControl -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -1M | +1P
```
```
XXX.entity.raid.Raid +4M -4M | +2P -2P
```
```
XXX.entity.raid.Raider +2M
```
```
XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal -1P
```
```
XXX.world.inventory.BeaconMenu$PaymentSlot -1P
```
```
XXX.world.inventory.CartographyTableMenu$4 -1P
```
```
XXX.world.inventory.EnchantmentMenu +1M -1M
```
```
XXX.world.inventory.EnchantmentMenu$2 -1P
```
```
XXX.world.item.HoneyBottleItem +1M
```
```
XXX.world.item.MaceItem +6M -5M | +2P -1P
```
```
XXX.world.item.MobBucketItem +1M -1M
```
```
XXX.world.item.PotionItem +1M -1M
```
```
XXX.world.item.Rarity -1P
```
```
XXX.world.item.ShieldItem +1M -1M
```
```
XXX.world.item.SmithingTemplateItem +1M -1M
```
```
XXX.world.item.SpectralArrowItem +1M
```
```
XXX.world.item.SuspiciousStewItem +1M -1M
```
```
XXX.world.item.ThrowablePotionItem +2M
```
```
XXX.world.item.TippedArrowItem +1M -1M
```
```
XXX.item.crafting.RecipeType -2P
```
```
XXX.item.crafting.ShapedRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.ShapelessRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SimpleCraftingRecipeSerializer +1M -1M | +1P -2P
```
```
XXX.item.crafting.SingleItemRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SmithingTransformRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.crafting.SmithingTrimRecipe$Serializer +1M -1M | +1P -1P
```
```
XXX.item.enchantment.EnchantmentHelper +5M -3M
```
```
XXX.world.level.EmptyBlockGetter -1M
```
```
XXX.world.level.EntityGetter -1M
```
```
XXX.world.level.GameRules -2P
```
```
XXX.world.level.Level -6M | -6P
```
```
XXX.level.biome.MultiNoiseBiomeSourceParameterLists -1P
```
```
XXX.level.biome.TheEndBiomeSource +1M -1M | +1P -1P
```
```
XXX.level.block.ChestBlock$2$1 -1P
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.level.block.SpawnerBlock +1M -1M
```
```
XXX.block.entity.BlockEntity +19M -7M | +1P
```
```
XXX.block.entity.LecternBlockEntity +1M -1M
```
```
XXX.block.entity.SculkCatalystBlockEntity +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity +2M -2M
```
```
XXX.block.entity.SculkShriekerBlockEntity +2M -2M
```
```
XXX.block.entity.ShulkerBoxBlockEntity +1M -1M
```
```
XXX.block.entity.SpawnerBlockEntity +1M -1M
```
```
XXX.block.entity.StructureBlockEntity +1M -1M
```
```
XXX.block.entity.TheEndGatewayBlockEntity +2M -2M
```
```
XXX.block.entity.TrialSpawnerBlockEntity +3M -3M
```
```
XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission +4M -4M | +1P -1P
```
```
XXX.entity.vault.VaultBlockEntity$Client +3M -3M
```
```
XXX.entity.vault.VaultState +2M -2M
```
```
XXX.entity.vault.VaultState$2 +1M -1M
```
```
XXX.entity.vault.VaultState$4 +1M -1M
```
```
XXX.level.chunk.ChunkAccess -1M | -1P
```
```
XXX.level.chunk.ChunkGenerator +1P -1P
```
```
XXX.level.chunk.ChunkGenerators +1M -1M
```
```
XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper -1P
```
```
XXX.level.chunk.LevelChunkSection$1BlockCounter -1P
```
```
XXX.level.entity.LevelEntityGetter -2M | -1P
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M | +1P -1P
```
```
XXX.level.levelgen.NoiseGeneratorSettings +1M -3M | -2P
```
```
XXX.level.levelgen.NoiseRouterData -3M
```
```
XXX.level.levelgen.NoiseSettings +1M -1M | -1P
```
```
XXX.level.levelgen.RandomState$1 -1P
```
```
XXX.level.levelgen.SurfaceRules$ConditionSource +2M -2M
```
```
XXX.level.levelgen.SurfaceRules$RuleSource +2M -2M
```
```
XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition -1P
```
```
XXX.level.levelgen.SurfaceSystem$1 -1P
```
```
XXX.level.levelgen.VerticalAnchor -1M
```
```
XXX.level.levelgen.WorldDimensions -1M
```
```
XXX.levelgen.blockpredicates.AnyOfPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.BlockPredicateType +2M -2M | +1P -1P
```
```
XXX.levelgen.blockpredicates.HasSturdyFacePredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.MatchingBlockTagPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.MatchingFluidsPredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.ReplaceablePredicate +1P -1P
```
```
XXX.levelgen.blockpredicates.WouldSurvivePredicate +1P -1P
```
```
XXX.levelgen.carver.WorldCarver +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.Feature +1M -1M | +1P -8P
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +3M -5M | -1P
```
```
XXX.feature.featuresize.FeatureSizeType +3M -3M | +1P -1P
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +1P -1P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +1P -1P
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +1P -1P
```
```
XXX.feature.stateproviders.BlockStateProviderType +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.NoiseThresholdProvider +1P -1P
```
```
XXX.feature.stateproviders.RotatedBlockProvider +1P -1P
```
```
XXX.feature.stateproviders.WeightedStateProvider +1P -1P
```
```
XXX.feature.treedecorators.AlterGroundDecorator +1P -1P
```
```
XXX.feature.treedecorators.BeehiveDecorator +7M -9M | +1P -2P
```
```
XXX.feature.treedecorators.LeaveVineDecorator +1P -1P
```
```
XXX.feature.treedecorators.TrunkVineDecorator +1P -1P
```
```
XXX.feature.trunkplacers.BendingTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.DarkOakTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.GiantTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.StraightTrunkPlacer +1P -1P
```
```
XXX.feature.trunkplacers.TrunkPlacerType +3M -3M | +1P -1P
```
```
XXX.levelgen.heightproviders.ConstantHeight +1P -1P
```
```
XXX.levelgen.heightproviders.HeightProviderType +2M -2M | +1P -1P
```
```
XXX.levelgen.heightproviders.UniformHeight +1P -1P
```
```
XXX.levelgen.heightproviders.WeightedListHeight +1P -1P
```
```
XXX.levelgen.placement.BiomeFilter +1P -1P
```
```
XXX.levelgen.placement.CarvingMaskPlacement +1P -1P
```
```
XXX.levelgen.structure.Structure$GenerationContext +2M -3M | -1P
```
```
XXX.levelgen.structure.Structure$StructureSettings +1M -2M | -1P
```
```
XXX.structure.placement.ConcentricRingsStructurePlacement +1P -1P
```
```
XXX.loot.functions.CopyNameFunction +1P -1P
```
```
XXX.loot.functions.EnchantRandomlyFunction +5M -4M | +1P -1P
```
```
XXX.loot.functions.EnchantWithLevelsFunction +1P -1P
```
```
XXX.loot.functions.ExplorationMapFunction +1P -1P
```
```
XXX.loot.functions.FillPlayerHead +1P -1P
```
```
XXX.loot.functions.ListOperation +1M -1M
```
```
XXX.loot.functions.LootItemFunctions +1M -1M | +1P
```
```
XXX.loot.functions.SetAttributesFunction +6M -4M | +2P -1P
```
```
XXX.loot.functions.SetBannerPatternFunction +1P -1P
```
```
XXX.loot.functions.SetBookCoverFunction +1P -1P
```
```
XXX.loot.functions.SetContainerContents +1P -1P
```
```
XXX.loot.functions.SetContainerLootTable +1P -1P
```
```
XXX.loot.functions.SetEnchantmentsFunction +1P -1P
```
```
XXX.loot.functions.SetFireworkExplosionFunction +1P -1P
```
```
XXX.loot.functions.SetInstrumentFunction +1P -1P
```
```
XXX.loot.functions.SetItemDamageFunction +1P -1P
```
```
XXX.loot.functions.SetPotionFunction +1P -1P
```
```
XXX.loot.functions.SetWritableBookPagesFunction +1P -1P
```
```
XXX.loot.functions.SmeltItemFunction +1P -1P
```
```
XXX.loot.predicates.AllOfCondition +1P -1P
```
```
XXX.loot.predicates.AnyOfCondition +1P -1P
```
```
XXX.loot.predicates.BonusLevelTableCondition +1P -1P
```
```
XXX.loot.predicates.EntityHasScoreCondition +1P -1P
```
```
XXX.loot.predicates.ExplosionCondition +1P -1P
```
```
XXX.loot.predicates.LocationCheck +1P -1P
```
```
XXX.loot.predicates.LootItemConditions +1M -1M | -1P
```
```
XXX.loot.predicates.LootItemKilledByPlayerCondition +1P -1P
```

</details>
<details>
<summary>
net.minecraft.client.gui.Gui
</summary>

```diff
+ void renderMissionDialogue(GuiGraphics,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay$1
</summary>

```diff
+ void add(UUID,Component,float,BossEvent$BossBarColor,BossEvent$BossBarOverlay,boolean,boolean,boolean,Vec3,int)
- void add(UUID,Component,float,BossEvent$BossBarColor,BossEvent$BossBarOverlay,boolean,boolean,boolean)
+ void updateLocation(UUID,Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DeathScreen
</summary>

```diff
- void renderDeathBackground(GuiGraphics,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.AccountProfileKeyPairManager
</summary>

```diff
+ boolean lambda$new$0(ProfileKeyPair)
+ Optional lambda$new$1()
- Optional lambda$readOrFetchProfileKeyPair$0(Optional)
+ Optional lambda$readOrFetchProfileKeyPair$2(Optional)
- void lambda$writeProfileKeyPair$1(JsonElement)
+ void lambda$writeProfileKeyPair$3(JsonElement)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientConfigurationPacketListenerImpl
</summary>

```diff
- void handleResetChat(ClientboundResetChatPacket)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.CommonListenerCookie
</summary>

```diff
- ChatComponent$State chatState()
- void <init>(GameProfile,WorldSessionTelemetryManager,RegistryAccess$Frozen,FeatureFlagSet,String,ServerData,Screen,Map,ChatComponent$State)
+ void <init>(GameProfile,WorldSessionTelemetryManager,RegistryAccess$Frozen,FeatureFlagSet,String,ServerData,Screen,Map)
```

</details>
<details>
<summary>
net.minecraft.client.particle.PortalParticle$Provider
</summary>

```diff
+ void <init>(SpriteSet,float,float,float)
- void <init>(SpriteSet)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
</summary>

```diff
+ void <init>(SpriteSet,float,float,float)
- void <init>(SpriteSet)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer
</summary>

```diff
+ void drawGrids(Matrix4f,Matrix4f,float,double,double,double,Frustum,boolean)
+ void potionEvent(int,BlockPos,int,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ShaderInstance
</summary>

```diff
+ void setDefaultUniforms(VertexFormat$Mode,Matrix4f,Matrix4f,Window)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.BlockRenderDispatcher
</summary>

```diff
+ void renderLiquid(BlockPos,BlockAndTintGetter,VertexConsumer,BlockState,FluidState,int,int,int)
- void renderLiquid(BlockPos,BlockAndTintGetter,VertexConsumer,BlockState,FluidState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.LiquidBlockRenderer
</summary>

```diff
+ void tesselate(BlockAndTintGetter,BlockPos,VertexConsumer,BlockState,FluidState,double,double,double)
- void tesselate(BlockAndTintGetter,BlockPos,VertexConsumer,BlockState,FluidState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ElderGuardianRenderer
</summary>

```diff
+ void <init>(EntityRendererProvider$Context,ModelLayerLocation)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderers
</summary>

```diff
+ EntityRenderer lambda$static$26(EntityRendererProvider$Context)
+ EntityRenderer lambda$static$27(EntityRendererProvider$Context)
+ EntityRenderer lambda$static$28(EntityRendererProvider$Context)
+ EntityRenderer lambda$static$29(EntityRendererProvider$Context)
+ EntityRenderer lambda$static$30(EntityRendererProvider$Context)
- void lambda$createEntityRenderers$26(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
+ void lambda$createEntityRenderers$31(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
- void lambda$createPlayerRenderers$27(ImmutableMap$Builder,EntityRendererProvider$Context,PlayerSkin$Model,EntityRendererProvider)
+ void lambda$createPlayerRenderers$32(ImmutableMap$Builder,EntityRendererProvider$Context,PlayerSkin$Model,EntityRendererProvider)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LivingEntityRenderer
</summary>

```diff
+ ResourceLocation potatoify(ResourceLocation)
+ String lambda$potatoify$0(String)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemProperties
</summary>

```diff
+ float lambda$static$23(ItemStack,ClientLevel,LivingEntity,int)
+ float lambda$static$24(ItemStack,ClientLevel,LivingEntity,int)
+ float lambda$static$25(ItemStack,ClientLevel,LivingEntity,int)
+ float lambda$static$26(ItemStack,ClientLevel,LivingEntity,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.atlas.SpriteSources
</summary>

```diff
+ SpriteSourceType register(String,Codec)
- SpriteSourceType register(String,MapCodec)
```

</details>
<details>
<summary>
net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice$Border
</summary>

```diff
- Either lambda$static$4(GuiSpriteScaling$NineSlice$Border)
+ Either lambda$static$5(GuiSpriteScaling$NineSlice$Border)
+ GuiSpriteScaling$NineSlice$Border lambda$static$4(Either)
```

</details>
<details>
<summary>
net.minecraft.core.UUIDUtil
</summary>

```diff
+ UUID lambda$static$10(UUID)
+ UUID lambda$static$11(Either)
+ UUID lambda$static$6(UUID)
+ UUID lambda$static$7(UUID)
+ UUID lambda$static$8(Either)
+ UUID lambda$static$9(UUID)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentMap
</summary>

```diff
- DataResult lambda$static$0(DataComponentMap)
+ TypedDataComponent lambda$iterator$0(DataComponentType)
- TypedDataComponent lambda$iterator$1(DataComponentType)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$1
</summary>

```diff
- ItemStack execute(BlockSource,ItemStack)
+ Projectile getProjectile(Level,Position,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$11
</summary>

```diff
+ boolean lambda$execute$0(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$13
</summary>

```diff
+ boolean lambda$execute$0(AbstractChestedHorse)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$15
</summary>

```diff
+ void lambda$execute$0(ItemStack,SmallFireball)
+ void playSound(BlockSource)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$4
</summary>

```diff
- boolean lambda$execute$0(AbstractHorse)
- ItemStack execute(BlockSource,ItemStack)
+ Projectile getProjectile(Level,Position,ItemStack)
+ void lambda$getProjectile$0(ItemStack,ThrownEgg)
```

</details>
<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$6
</summary>

```diff
+ float getPower()
+ float getUncertainty()
- ItemStack execute(BlockSource,ItemStack)
+ Projectile getProjectile(Level,Position,ItemStack)
+ void lambda$getProjectile$0(ItemStack,ThrownExperienceBottle)
```

</details>
<details>
<summary>
net.minecraft.network.chat.ComponentSerialization
</summary>

```diff
- App lambda$createCodec$2(MapCodec,Codec,RecordCodecBuilder$Instance)
+ App lambda$createCodec$3(MapCodec,Codec,RecordCodecBuilder$Instance)
+ Codec lambda$createLegacyComponentMatcher$2(Function,StringRepresentable)
- Component lambda$createCodec$3(Either)
- Component lambda$createCodec$4(Component)
+ Component lambda$createCodec$4(Either)
+ Component lambda$createCodec$5(Component)
- Component lambda$createCodec$5(Either)
+ Component lambda$createCodec$6(Either)
- Either lambda$createCodec$6(Component)
+ Either lambda$createCodec$7(Component)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageChain$Decoder
</summary>

```diff
- void setChainBroken()
```

</details>
<details>
<summary>
net.minecraft.network.chat.numbers.NumberFormatTypes
</summary>

```diff
+ Codec lambda$static$0(NumberFormatType)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$11
</summary>

```diff
+ byte[] decode(ByteBuf)
- String decode(ByteBuf)
+ void <init>()
- void <init>(int)
+ void encode(ByteBuf,byte[])
- void encode(ByteBuf,String)
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
+ Tag decode(ByteBuf)
- void <init>(StreamCodec,Codec)
+ void <init>(Supplier)
+ void encode(ByteBuf,Tag)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$15
</summary>

```diff
+ Optional decode(ByteBuf)
- Vector3f decode(ByteBuf)
+ void encode(ByteBuf,Optional)
- void encode(ByteBuf,Vector3f)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$17
</summary>

```diff
- Optional decode(ByteBuf)
+ Quaternionf decode(ByteBuf)
+ void <init>()
- void <init>(StreamCodec)
- void encode(ByteBuf,Optional)
+ void encode(ByteBuf,Quaternionf)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$19
</summary>

```diff
+ Collection decode(ByteBuf)
- Map decode(ByteBuf)
+ void <init>(int,IntFunction,StreamCodec)
- void <init>(int,StreamCodec,StreamCodec,IntFunction)
+ void encode(ByteBuf,Collection)
- void encode(ByteBuf,Map)
- void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$20
</summary>

```diff
- Either decode(ByteBuf)
+ Map decode(ByteBuf)
+ void <init>(int,StreamCodec,StreamCodec,IntFunction)
- void <init>(StreamCodec,StreamCodec)
- void encode(ByteBuf,Either)
+ void encode(ByteBuf,Map)
- void lambda$encode$0(ByteBuf,StreamCodec,Object)
+ void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
- void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$22
</summary>

```diff
- IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
+ Object decode(ByteBuf)
- Object decode(RegistryFriendlyByteBuf)
- void <init>(Function,ResourceKey)
+ void <init>(IntFunction,ToIntFunction)
+ void encode(ByteBuf,Object)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$24
</summary>

```diff
+ Holder decode(RegistryFriendlyByteBuf)
- HolderSet decode(RegistryFriendlyByteBuf)
+ IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
+ void <init>(ResourceKey,StreamCodec)
- void <init>(ResourceKey)
+ void encode(RegistryFriendlyByteBuf,Holder)
- void encode(RegistryFriendlyByteBuf,HolderSet)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$26
</summary>

```diff
- GameProfile decode(ByteBuf)
+ PropertyMap decode(ByteBuf)
+ String lambda$decode$0(ByteBuf)
- void encode(ByteBuf,GameProfile)
+ void encode(ByteBuf,PropertyMap)
+ void lambda$encode$1(ByteBuf,String)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
</summary>

```diff
+ void add(UUID,Component,float,BossEvent$BossBarColor,BossEvent$BossBarOverlay,boolean,boolean,boolean,Vec3,int)
- void add(UUID,Component,float,BossEvent$BossBarColor,BossEvent$BossBarOverlay,boolean,boolean,boolean)
+ void updateLocation(UUID,Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
</summary>

```diff
+ UUID waitForGrid()
+ void <init>(Holder,ResourceKey,long,GameType,GameType,boolean,boolean,Optional,int,UUID)
- void <init>(Holder,ResourceKey,long,GameType,GameType,boolean,boolean,Optional,int)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryDataLoader
</summary>

```diff
+ void lambda$loadContentsFromNetwork$14(String)
+ void lambda$loadElementFromResource$13(String)
```

</details>
<details>
<summary>
net.minecraft.server.PlayerAdvancements
</summary>

```diff
+ AdvancementTree getTree()
```

</details>
<details>
<summary>
net.minecraft.server.commands.RaidCommand
</summary>

```diff
+ Component lambda$setBadOmenLevel$8(int,int)
- Component lambda$setRaidOmenLevel$8(int,int)
+ int setBadOmenLevel(CommandSourceStack,int)
- int setRaidOmenLevel(CommandSourceStack,int)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerBossEvent
</summary>

```diff
+ void <init>(Entity,BossEvent$BossBarColor,BossEvent$BossBarOverlay)
+ void setLocation(Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.stats.StatFormatter
</summary>

```diff
+ String lambda$static$4(int)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- App lambda$static$60(RecordCodecBuilder$Instance)
- App lambda$static$68(RecordCodecBuilder$Instance)
+ App lambda$static$69(RecordCodecBuilder$Instance)
- App lambda$static$71(RecordCodecBuilder$Instance)
+ App lambda$static$77(RecordCodecBuilder$Instance)
+ App lambda$static$80(RecordCodecBuilder$Instance)
- BitSet lambda$static$56(LongStream)
+ BitSet lambda$static$65(LongStream)
+ Codec int2IntMap()
+ Codec intIntPair()
+ Codec lambda$lazyInitializedCodec$48(Supplier,Codec)
+ Codec lazyInitializedCodec(Supplier)
+ Codec recursive(String,Function)
+ Codec sizeLimitedList(Codec,int)
+ Codec sizeLimitedString(int,int)
+ Codec stringResolverCodec(Function,Function)
+ Codec unboundedDispatchMap(Codec,Function)
+ Codec validate(Codec,Function)
+ Codec withAlternative(Codec,Codec,Function)
+ Codec withAlternative(Codec,Codec)
+ Codec xor(Codec,Codec)
- DataResult lambda$ensureHomogenous$43(Function,Collection)
+ DataResult lambda$ensureHomogenous$52(Function,Collection)
- DataResult lambda$floatRangeMinExclusiveWithMessage$36(float,float,Function,Float)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
- DataResult lambda$intRangeWithMessage$31(int,int,Function,Integer)
+ DataResult lambda$intRangeWithMessage$37(int,int,Function,Integer)
- DataResult lambda$nonEmptyHolderSet$41(HolderSet)
+ DataResult lambda$nonEmptyHolderSet$47(HolderSet)
- DataResult lambda$nonEmptyList$39(List)
+ DataResult lambda$nonEmptyList$45(List)
+ DataResult lambda$sizeLimitedList$90(int,List)
- DataResult lambda$sizeLimitedMap$77(int,Map)
+ DataResult lambda$sizeLimitedMap$92(int,Map)
+ DataResult lambda$sizeLimitedString$87(int,int,String)
- DataResult lambda$static$45(String)
- DataResult lambda$static$48(String)
- DataResult lambda$static$50(String)
- DataResult lambda$static$53(String)
+ DataResult lambda$static$54(String)
+ DataResult lambda$static$57(String)
+ DataResult lambda$static$59(String)
+ DataResult lambda$static$62(String)
- DataResult lambda$static$67(String)
- DataResult lambda$static$73(String)
- DataResult lambda$static$75(String)
+ DataResult lambda$static$76(String)
- DataResult lambda$static$79(String)
+ DataResult lambda$static$82(String)
+ DataResult lambda$static$84(String)
+ DataResult lambda$static$94(String)
+ DataResult lambda$stringResolverCodec$31(String)
+ DataResult lambda$stringResolverCodec$32(Function,String)
+ DataResult lambda$stringResolverCodec$34(Object)
+ DataResult lambda$stringResolverCodec$35(Function,Object)
- DataResult lambda$temporalCodec$46(DateTimeFormatter,String)
+ DataResult lambda$temporalCodec$55(DateTimeFormatter,String)
- Either lambda$static$65(PropertyMap)
+ Either lambda$static$74(PropertyMap)
+ ExtraCodecs$EitherCodec either(Codec,Codec)
- ExtraCodecs$TagOrElementLocation lambda$static$51(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$52(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$60(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$61(ResourceLocation)
- GameProfile lambda$static$70(GameProfile,PropertyMap)
+ GameProfile lambda$static$79(GameProfile,PropertyMap)
+ Int2IntMap lambda$int2IntMap$101(LongStream)
+ IntIntPair lambda$intIntPair$104(Long)
+ List lambda$sizeLimitedList$89(List,int)
+ Long lambda$intIntPair$105(IntIntPair)
+ LongStream lambda$int2IntMap$103(Int2IntMap)
- LongStream lambda$static$57(BitSet)
+ LongStream lambda$static$66(BitSet)
+ MapCodec recursiveMap(String,Function)
+ MapCodec strictOptionalField(Codec,String,Object)
+ MapCodec strictOptionalField(Codec,String)
+ MapCodec validate(MapCodec,Function)
+ Object lambda$strictOptionalField$49(Object,Optional)
+ Object lambda$withAlternative$95(Object)
+ Object lambda$withAlternative$96(Object)
+ Object lambda$withAlternative$97(Either)
+ Object lambda$withAlternative$98(Object)
+ Object lambda$withAlternative$99(Function,Either)
- Optional lambda$static$55(OptionalLong)
- Optional lambda$static$58(Property)
+ Optional lambda$static$64(OptionalLong)
+ Optional lambda$static$67(Property)
+ Optional lambda$strictOptionalField$50(Object,Object)
- OptionalLong lambda$static$54(Optional)
+ OptionalLong lambda$static$63(Optional)
- Property lambda$static$59(String,String,Optional)
+ Property lambda$static$68(String,String,Optional)
- PropertyMap lambda$static$64(Either)
+ PropertyMap lambda$static$73(Either)
- String lambda$ensureHomogenous$42(Object,Object,Object)
+ String lambda$ensureHomogenous$51(Object,Object,Object)
- String lambda$floatRangeMinExclusiveWithMessage$35(Function,Float)
+ String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
- String lambda$intRange$34(int,int,Integer)
+ String lambda$intRange$40(int,int,Integer)
- String lambda$intRangeWithMessage$30(Function,Integer)
+ String lambda$intRangeWithMessage$36(Function,Integer)
- String lambda$nonEmptyHolderSet$40()
+ String lambda$nonEmptyHolderSet$46()
- String lambda$nonEmptyList$38()
+ String lambda$nonEmptyList$44()
+ String lambda$sizeLimitedList$88(List,int)
- String lambda$sizeLimitedMap$76(Map,int)
+ String lambda$sizeLimitedMap$91(Map,int)
+ String lambda$sizeLimitedString$85(String,int,int,int)
+ String lambda$sizeLimitedString$86(String,int,int,int)
- String lambda$static$32(Integer)
- String lambda$static$33(Integer)
- String lambda$static$37(Float)
+ String lambda$static$38(Integer)
+ String lambda$static$39(Integer)
+ String lambda$static$43(Float)
- String lambda$static$44(String,PatternSyntaxException)
- String lambda$static$47()
- String lambda$static$49(byte[])
+ String lambda$static$53(String,PatternSyntaxException)
+ String lambda$static$56()
+ String lambda$static$58(byte[])
- String lambda$static$66(String)
- String lambda$static$72()
- String lambda$static$74(String)
+ String lambda$static$75(String)
- String lambda$static$78(String)
+ String lambda$static$81()
+ String lambda$static$83(String)
+ String lambda$static$93(String)
+ String lambda$stringResolverCodec$30(String)
+ String lambda$stringResolverCodec$33(Object)
+ void lambda$int2IntMap$100(Int2IntMap,long)
+ void lambda$int2IntMap$102(LongList,Integer,Integer)
- void lambda$static$61(PropertyMap,String,List)
- void lambda$static$62(PropertyMap,Map)
- void lambda$static$63(PropertyMap,List)
- void lambda$static$69(GameProfile,String,Property)
+ void lambda$static$70(PropertyMap,String,List)
+ void lambda$static$71(PropertyMap,Map)
+ void lambda$static$72(PropertyMap,List)
+ void lambda$static$78(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs$7
</summary>

```diff
- boolean isEmptyMap(DynamicOps,Object)
+ DataResult decode(DynamicOps,MapLike)
- DataResult decode(DynamicOps,Object)
+ DataResult encode(Codec,Object,DynamicOps)
- DataResult encode(Object,DynamicOps,Object)
- DataResult encode(Optional,DynamicOps,Object)
+ DataResult lambda$decode$1(MapLike,String,DynamicOps,Function,Pair)
- Pair lambda$decode$0(Pair)
+ RecordBuilder encode(Object,DynamicOps,RecordBuilder)
+ Stream keys(DynamicOps)
+ String lambda$decode$0(String,MapLike)
- void <init>(Codec)
+ void <init>(String,String,Codec,Function,Function)
```

</details>
<details>
<summary>
net.minecraft.util.KeyDispatchDataCodec
</summary>

```diff
+ Codec codec()
+ KeyDispatchDataCodec of(Codec)
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- DSL$TypeReference reference(String)
+ String lambda$static$0()
+ String lambda$static$1()
+ String lambda$static$10()
+ String lambda$static$11()
+ String lambda$static$12()
+ String lambda$static$13()
+ String lambda$static$14()
+ String lambda$static$15()
+ String lambda$static$16()
+ String lambda$static$17()
+ String lambda$static$18()
+ String lambda$static$19()
+ String lambda$static$2()
+ String lambda$static$20()
+ String lambda$static$21()
+ String lambda$static$22()
+ String lambda$static$23()
+ String lambda$static$24()
+ String lambda$static$25()
+ String lambda$static$26()
+ String lambda$static$27()
+ String lambda$static$28()
+ String lambda$static$29()
+ String lambda$static$3()
+ String lambda$static$30()
+ String lambda$static$31()
+ String lambda$static$32()
+ String lambda$static$33()
+ String lambda$static$34()
+ String lambda$static$35()
+ String lambda$static$36()
+ String lambda$static$4()
+ String lambda$static$5()
+ String lambda$static$6()
+ String lambda$static$7()
+ String lambda$static$8()
+ String lambda$static$9()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
+ TypeTemplate lambda$registerTypes$24(Map)
- TypeTemplate lambda$registerTypes$24(Schema,Map)
```

</details>
<details>
<summary>
net.minecraft.util.valueproviders.IntProvider
</summary>

```diff
+ Codec codec(int,int,Codec)
- Codec validateCodec(int,int,Codec)
+ DataResult lambda$codec$5(int,int,IntProvider)
- DataResult lambda$validateCodec$3(int,int,IntProvider)
- DataResult validate(int,int,IntProvider)
+ String lambda$codec$3(int,IntProvider)
+ String lambda$codec$4(int,IntProvider)
- String lambda$validate$4(int,IntProvider)
- String lambda$validate$5(int,IntProvider)
```

</details>
<details>
<summary>
net.minecraft.world.BossEvent
</summary>

```diff
+ int getRadius()
+ Vec3 getCenter()
+ void <init>(UUID,Component,BossEvent$BossBarColor,BossEvent$BossBarOverlay,Vec3,int)
- void <init>(UUID,Component,BossEvent$BossBarColor,BossEvent$BossBarOverlay)
+ void setLocation(Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.world.ContainerHelper
</summary>

```diff
+ int tryAddItem(Container,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffect
</summary>

```diff
- FeatureFlagSet requiredFeatures()
- MobEffect requiredFeatures(FeatureFlag[])
- MobEffect withSoundOnAdded(SoundEvent)
+ void lambda$createModifiers$2(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
- void lambda$createModifiers$3(BiConsumer,int,Holder,MobEffect$AttributeTemplate)
- void lambda$onEffectAdded$2(LivingEntity,SoundEvent)
- void onEffectAdded(LivingEntity,int)
- void onMobHurt(LivingEntity,int,DamageSource,float)
- void onMobRemoved(LivingEntity,int,Entity$RemovalReason)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ int getColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
+ int getTotalValue()
+ void targetBlock(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.ZombieAttackGoal
</summary>

```diff
+ void <init>(PathfinderMob,double,boolean)
- void <init>(Zombie,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Bogged
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Creeper
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan
</summary>

```diff
+ boolean hasPotatoVariant()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Guardian
</summary>

```diff
+ BodyRotationControl createBodyControl()
+ boolean canJump()
+ boolean checkSpawnRules(LevelAccessor,MobSpawnType)
+ boolean isBuddy(Entity)
+ boolean isToxic()
+ double guardianStackRidingOffset()
+ Guardian createNormal(EntityType,Level)
+ Guardian createToxic(EntityType,Level)
+ LivingEntity getControllingPassenger()
+ RandomSource access$000(Guardian)
+ RandomSource access$100(Guardian)
+ Vec3 getPassengerAttachmentPoint(Entity,EntityDimensions,float)
+ void <init>(EntityType,Level,boolean)
- void <init>(EntityType,Level)
+ void actuallyHurt(DamageSource,float)
+ void applyPoisonFromWaterContact()
+ void lambda$actuallyHurt$0(Entity,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ void lerpMotion(double,double,double)
- void onDeflection()
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raid
</summary>

```diff
- boolean absorbRaidOmen(ServerPlayer)
+ int getBadOmenLevel()
+ int getMaxBadOmenLevel()
- int getMaxRaidOmenLevel()
- int getRaidOmenLevel()
+ void absorbBadOmen(Player)
+ void setBadOmenLevel(int)
- void setRaidOmenLevel(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raider
</summary>

```diff
- boolean hasRaid()
- boolean isCaptain()
```

</details>
<details>
<summary>
net.minecraft.world.inventory.EnchantmentMenu
</summary>

```diff
- List getEnchantmentList(FeatureFlagSet,ItemStack,int,int)
+ List getEnchantmentList(ItemStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoneyBottleItem
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.item.MaceItem
</summary>

```diff
+ boolean isEnchantable(ItemStack)
+ boolean lambda$knockback$0(Player,Entity,LivingEntity)
- boolean lambda$knockbackPredicate$1(Player,Entity,LivingEntity)
- double getKnockbackPower(Player,LivingEntity,Vec3)
- int getEnchantmentValue()
- ItemAttributeModifiers createAttributes()
+ Multimap getDefaultAttributeModifiers(EquipmentSlot)
- Predicate knockbackPredicate(Player,Entity)
+ void <clinit>()
- void lambda$knockback$0(Entity,Player,LivingEntity)
+ void lambda$knockback$1(Entity,Level,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.MobBucketItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.PotionItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.SmithingTemplateItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.SpectralArrowItem
</summary>

```diff
- Projectile asProjectile(Level,Position,ItemStack,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.item.SuspiciousStewItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.ThrowablePotionItem
</summary>

```diff
- Projectile asProjectile(Level,Position,ItemStack,Direction)
- ProjectileItem$DispenseConfig createDispenseConfig()
```

</details>
<details>
<summary>
net.minecraft.world.item.TippedArrowItem
</summary>

```diff
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
- float calculateArmorBreach(Entity,float)
- ItemStack enchantItem(FeatureFlagSet,RandomSource,ItemStack,int,boolean)
+ ItemStack enchantItem(RandomSource,ItemStack,int,boolean)
- List getAvailableEnchantmentResults(FeatureFlagSet,int,ItemStack,boolean)
+ List getAvailableEnchantmentResults(int,ItemStack,boolean)
- List selectEnchantment(FeatureFlagSet,RandomSource,ItemStack,int,boolean)
+ List selectEnchantment(RandomSource,ItemStack,int,boolean)
- void doPostItemStackHurtEffects(LivingEntity,Entity,ItemEnchantments)
```

</details>
<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
+ boolean isPotato()
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
+ Player getNearestPlayer(BlockPos,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean isPotato()
+ boolean noCollision(Entity,AABB,boolean)
+ float adjustPreciptiationToClouds(float,double)
+ float getRainLevel(float,double)
+ float getThunderLevel(float,double)
+ SubGrid createSubGrid(GridCarrier)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.TheEndBiomeSource
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ void appendHoverText(ItemStack,BlockGetter,List,TooltipFlag,RegistryAccess)
- void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntity
</summary>

```diff
+ BlockEntity lambda$loadStatic$0(BlockPos,BlockState,String,BlockEntityType)
+ BlockEntity lambda$loadStatic$1(CompoundTag,HolderLookup$Provider,String,BlockEntity)
+ BlockEntity lambda$loadStatic$2(String)
- BlockEntity lambda$loadStatic$4(BlockPos,BlockState,String,BlockEntityType)
- BlockEntity lambda$loadStatic$5(CompoundTag,HolderLookup$Provider,String,BlockEntity)
- BlockEntity lambda$loadStatic$6(String)
- CompoundTag saveCustomAndMetadata(HolderLookup$Provider)
- CompoundTag saveCustomOnly(HolderLookup$Provider)
- DataComponentMap components()
+ String lambda$fillCrashReportCategory$3()
- String lambda$fillCrashReportCategory$7()
- void applyComponents(DataComponentMap,DataComponentPatch)
+ void applyComponents(DataComponentMap)
- void applyComponentsFromItemStack(ItemStack)
- void applyImplicitComponents(BlockEntity$DataComponentInput)
+ void collectComponents(DataComponentMap$Builder)
- void collectImplicitComponents(DataComponentMap$Builder)
- void lambda$loadWithComponents$0(String)
- void lambda$loadWithComponents$1(DataComponentMap)
- void lambda$saveWithoutMetadata$2(String)
- void lambda$saveWithoutMetadata$3(CompoundTag,Tag)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
- void loadCustomOnly(CompoundTag,HolderLookup$Provider)
- void loadWithComponents(CompoundTag,HolderLookup$Provider)
- void setComponents(DataComponentMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.LecternBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity
</summary>

```diff
+ void lambda$load$0(VibrationSystem$Data)
- void lambda$loadAdditional$0(VibrationSystem$Data)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
</summary>

```diff
+ void lambda$load$1(VibrationSystem$Data)
- void lambda$loadAdditional$1(VibrationSystem$Data)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
</summary>

```diff
+ void lambda$load$0(BlockPos)
- void lambda$loadAdditional$0(BlockPos)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
</summary>

```diff
+ void lambda$load$0(TrialSpawner)
- void lambda$loadAdditional$0(TrialSpawner)
- void lambda$saveAdditional$2(DataResult$Error)
+ void lambda$saveAdditional$2(DataResult$PartialResult)
+ void load(CompoundTag,HolderLookup$Provider)
- void loadAdditional(CompoundTag,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
</summary>

```diff
- void lambda$static$0(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$0(Level,RandomSource,BlockPos)
- void lambda$static$1(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$1(Level,RandomSource,BlockPos)
- void lambda$static$2(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$2(Level,RandomSource,BlockPos)
- void lambda$static$3(Level,RandomSource,BlockPos,boolean)
+ void lambda$static$3(Level,RandomSource,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
</summary>

```diff
- void emitActivationParticles(Level,BlockPos,BlockState,VaultSharedData,ParticleOptions)
+ void emitActivationParticles(Level,BlockPos,BlockState,VaultSharedData)
- void emitDeactivationParticles(Level,BlockPos,ParticleOptions)
+ void emitDeactivationParticles(Level,BlockPos)
- void emitIdleParticles(Level,BlockPos,VaultSharedData,ParticleOptions)
+ void emitIdleParticles(Level,BlockPos,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
- void onTransition(ServerLevel,BlockPos,VaultState,VaultConfig,VaultSharedData,boolean)
+ void onTransition(ServerLevel,BlockPos,VaultState,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState$2
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.vault.VaultState$4
</summary>

```diff
- void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData,boolean)
+ void onEnter(ServerLevel,BlockPos,VaultConfig,VaultSharedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ boolean isPotato()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerators
</summary>

```diff
+ Codec bootstrap(Registry)
- MapCodec bootstrap(Registry)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.LevelEntityGetter
</summary>

```diff
+ LevelEntityGetter empty()
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ Codec codec()
- MapCodec codec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
+ int bottomGenerationPadding()
+ NoiseGeneratorSettings potato(BootstrapContext)
- void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,boolean,boolean,boolean,boolean)
+ void <init>(NoiseSettings,BlockState,BlockState,NoiseRouter,SurfaceRules$RuleSource,List,int,int,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
+ DensityFunction slidePotato(HolderGetter)
+ NoiseRouter noNewCavesWithExtraZing(HolderGetter,HolderGetter,DensityFunction)
+ NoiseRouter potato(HolderGetter,HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSettings
</summary>

```diff
- void lambda$create$4(DataResult$Error)
+ void lambda$create$4(DataResult$PartialResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
</summary>

```diff
+ Codec bootstrap(Registry)
+ Codec lambda$static$0(SurfaceRules$ConditionSource)
- MapCodec bootstrap(Registry)
- MapCodec lambda$static$0(SurfaceRules$ConditionSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
</summary>

```diff
+ Codec bootstrap(Registry)
+ Codec lambda$static$0(SurfaceRules$RuleSource)
- MapCodec bootstrap(Registry)
- MapCodec lambda$static$0(SurfaceRules$RuleSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor
</summary>

```diff
+ Record lambda$merge$0(Either)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldDimensions
</summary>

```diff
+ boolean isStablePotato(LevelStem)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
</summary>

```diff
+ BlockPredicateType register(String,Codec)
- BlockPredicateType register(String,MapCodec)
+ Codec lambda$register$0(Codec)
- MapCodec lambda$register$0(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ Codec configuredCodec()
- MapCodec configuredCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.Feature
</summary>

```diff
+ Codec configuredCodec()
- MapCodec configuredCodec()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$3(RecordCodecBuilder$Instance)
+ BlockState lambda$static$0(ColumnFeatureConfiguration)
+ BlockState state()
- IntProvider lambda$static$0(ColumnFeatureConfiguration)
+ IntProvider lambda$static$2(ColumnFeatureConfiguration)
+ void <init>(BlockState,IntProvider,IntProvider)
- void <init>(IntProvider,IntProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
</summary>

```diff
+ Codec codec()
+ FeatureSizeType register(String,Codec)
- FeatureSizeType register(String,MapCodec)
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
</summary>

```diff
+ BlockStateProviderType register(String,Codec)
- BlockStateProviderType register(String,MapCodec)
+ Codec codec()
- MapCodec codec()
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
</summary>

```diff
+ App lambda$static$2(RecordCodecBuilder$Instance)
- boolean lambda$place$3(int,BlockPos)
+ boolean lambda$place$5(int,BlockPos)
- boolean lambda$place$5(TreeDecorator$Context,BlockPos)
+ boolean lambda$place$7(TreeDecorator$Context,BlockPos)
+ Boolean lambda$static$1(BeehiveDecorator)
- boolean lambda$static$1(Direction)
+ boolean lambda$static$3(Direction)
- Direction[] lambda$static$2(int)
+ Direction[] lambda$static$4(int)
- Stream lambda$place$4(BlockPos)
+ Stream lambda$place$6(BlockPos)
+ void <init>(float,boolean)
- void <init>(float)
- void lambda$place$6(RandomSource,BeehiveBlockEntity)
+ void lambda$place$8(RandomSource,BeehiveBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
</summary>

```diff
+ Codec codec()
- MapCodec codec()
+ TrunkPlacerType register(String,Codec)
- TrunkPlacerType register(String,MapCodec)
+ void <init>(Codec)
- void <init>(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
</summary>

```diff
+ Codec lambda$register$0(Codec)
+ HeightProviderType register(String,Codec)
- HeightProviderType register(String,MapCodec)
- MapCodec lambda$register$0(MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
</summary>

```diff
+ List densityChecks()
+ void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,long,ChunkPos,LevelHeightAccessor,Predicate,List)
- void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,long,ChunkPos,LevelHeightAccessor,Predicate)
+ void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,WorldgenRandom,long,ChunkPos,LevelHeightAccessor,Predicate,List)
- void <init>(RegistryAccess,ChunkGenerator,BiomeSource,RandomState,StructureTemplateManager,WorldgenRandom,long,ChunkPos,LevelHeightAccessor,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
</summary>

```diff
+ List densityChecks()
+ void <init>(HolderSet,List,Map,GenerationStep$Decoration,TerrainAdjustment)
- void <init>(HolderSet,Map,GenerationStep$Decoration,TerrainAdjustment)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
</summary>

```diff
+ boolean lambda$run$4(Holder$Reference)
- boolean lambda$run$4(LootContext,Holder$Reference)
+ boolean lambda$run$5(boolean,ItemStack,Holder$Reference)
- boolean lambda$run$5(Holder$Reference)
- boolean lambda$run$6(boolean,ItemStack,Holder$Reference)
+ LootItemFunction lambda$randomApplicableEnchantment$7(List)
- LootItemFunction lambda$randomApplicableEnchantment$8(List)
+ Optional lambda$run$6(ItemStack,RandomSource)
- Optional lambda$run$7(ItemStack,LootContext,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ListOperation
</summary>

```diff
+ Codec lambda$codec$0(ListOperation$Type)
- MapCodec lambda$codec$0(ListOperation$Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootItemFunctions
</summary>

```diff
+ LootItemFunctionType register(String,Codec)
- LootItemFunctionType register(String,MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
+ App lambda$static$1(RecordCodecBuilder$Instance)
- App lambda$static$2(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(SetAttributesFunction)
+ ItemAttributeModifiers lambda$run$3(LootContext,ItemAttributeModifiers)
- ItemAttributeModifiers lambda$run$4(LootContext,ItemStack,ItemAttributeModifiers)
- ItemAttributeModifiers updateModifiers(LootContext,ItemAttributeModifiers)
+ Stream lambda$getReferencedContextParams$2(SetAttributesFunction$Modifier)
- Stream lambda$getReferencedContextParams$3(SetAttributesFunction$Modifier)
- void <init>(List,List,boolean)
+ void <init>(List,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemConditions
</summary>

```diff
+ LootItemConditionType register(String,Codec)
- LootItemConditionType register(String,MapCodec)
```

</details>
</details>
<hr/>