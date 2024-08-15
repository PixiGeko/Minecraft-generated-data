## Comparison with [1.21.1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.1)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Items](#items)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>DataPack version</td><td><code>48</code></td><td><code>49</code></td></tr><tr><td>ResourcePack version</td><td><code>34</code></td><td><code>35</code></td></tr><tr><td>World version</td><td><code>3955</code></td><td><code>4058</code></td></tr><tr><td>Protocol version</td><td><code>767</code></td><td><code>1073742029</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
- instrument.txt
```

</details>


<details>
<summary>
attribute.txt
</summary>

```diff
+ minecraft:armor
+ minecraft:armor_toughness
+ minecraft:attack_damage
+ minecraft:attack_knockback
+ minecraft:attack_speed
+ minecraft:block_break_speed
+ minecraft:block_interaction_range
+ minecraft:burning_time
+ minecraft:entity_interaction_range
+ minecraft:explosion_knockback_resistance
+ minecraft:fall_damage_multiplier
+ minecraft:flying_speed
+ minecraft:follow_range
- minecraft:generic.armor
- minecraft:generic.armor_toughness
- minecraft:generic.attack_damage
- minecraft:generic.attack_knockback
- minecraft:generic.attack_speed
- minecraft:generic.burning_time
- minecraft:generic.explosion_knockback_resistance
- minecraft:generic.fall_damage_multiplier
- minecraft:generic.flying_speed
- minecraft:generic.follow_range
- minecraft:generic.gravity
- minecraft:generic.jump_strength
- minecraft:generic.knockback_resistance
- minecraft:generic.luck
- minecraft:generic.max_absorption
- minecraft:generic.max_health
- minecraft:generic.movement_efficiency
- minecraft:generic.movement_speed
- minecraft:generic.oxygen_bonus
- minecraft:generic.safe_fall_distance
- minecraft:generic.scale
- minecraft:generic.step_height
- minecraft:generic.water_movement_efficiency
+ minecraft:gravity
+ minecraft:jump_strength
+ minecraft:knockback_resistance
+ minecraft:luck
+ minecraft:max_absorption
+ minecraft:max_health
+ minecraft:mining_efficiency
+ minecraft:movement_efficiency
+ minecraft:movement_speed
+ minecraft:oxygen_bonus
- minecraft:player.block_break_speed
- minecraft:player.block_interaction_range
- minecraft:player.entity_interaction_range
- minecraft:player.mining_efficiency
- minecraft:player.sneaking_speed
- minecraft:player.submerged_mining_speed
- minecraft:player.sweeping_damage_ratio
+ minecraft:safe_fall_distance
+ minecraft:scale
+ minecraft:sneaking_speed
+ minecraft:spawn_reinforcements
+ minecraft:step_height
+ minecraft:submerged_mining_speed
+ minecraft:sweeping_damage_ratio
+ minecraft:tempt_range
+ minecraft:water_movement_efficiency
- minecraft:zombie.spawn_reinforcements
```

</details>









<details>
<summary>
data_component_type.txt
</summary>

```diff
+ minecraft:enchantable
+ minecraft:repairable
```

</details>















<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:bordure_indented_banner_pattern
+ minecraft:field_masoned_banner_pattern
```

</details>

















<details>
<summary>
recipe_serializer.txt
</summary>

```diff
- minecraft:crafting_special_suspiciousstew
```

</details>





<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.spawner.break
+ minecraft:block.spawner.fall
+ minecraft:block.spawner.hit
+ minecraft:block.spawner.place
+ minecraft:block.spawner.step
+ minecraft:item.bundle.insert_fail
```

</details>














<details>
<summary>
worldgen/placement_modifier_type.txt
</summary>

```diff
- minecraft:carving_mask
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
- universal_tags/instrument.json
```

</details>








<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:armor
+ minecraft:armor_toughness
+ minecraft:attack_damage
+ minecraft:attack_knockback
+ minecraft:attack_speed
+ minecraft:block_break_speed
+ minecraft:block_interaction_range
+ minecraft:burning_time
+ minecraft:entity_interaction_range
+ minecraft:explosion_knockback_resistance
+ minecraft:fall_damage_multiplier
+ minecraft:flying_speed
+ minecraft:follow_range
- minecraft:generic.armor
- minecraft:generic.armor_toughness
- minecraft:generic.attack_damage
- minecraft:generic.attack_knockback
- minecraft:generic.attack_speed
- minecraft:generic.burning_time
- minecraft:generic.explosion_knockback_resistance
- minecraft:generic.fall_damage_multiplier
- minecraft:generic.flying_speed
- minecraft:generic.follow_range
- minecraft:generic.gravity
- minecraft:generic.jump_strength
- minecraft:generic.knockback_resistance
- minecraft:generic.luck
- minecraft:generic.max_absorption
- minecraft:generic.max_health
- minecraft:generic.movement_efficiency
- minecraft:generic.movement_speed
- minecraft:generic.oxygen_bonus
- minecraft:generic.safe_fall_distance
- minecraft:generic.scale
- minecraft:generic.step_height
- minecraft:generic.water_movement_efficiency
+ minecraft:gravity
+ minecraft:jump_strength
+ minecraft:knockback_resistance
+ minecraft:luck
+ minecraft:max_absorption
+ minecraft:max_health
+ minecraft:mining_efficiency
+ minecraft:movement_efficiency
+ minecraft:movement_speed
+ minecraft:oxygen_bonus
- minecraft:player.block_break_speed
- minecraft:player.block_interaction_range
- minecraft:player.entity_interaction_range
- minecraft:player.mining_efficiency
- minecraft:player.sneaking_speed
- minecraft:player.submerged_mining_speed
- minecraft:player.sweeping_damage_ratio
+ minecraft:safe_fall_distance
+ minecraft:scale
+ minecraft:sneaking_speed
+ minecraft:spawn_reinforcements
+ minecraft:step_height
+ minecraft:submerged_mining_speed
+ minecraft:sweeping_damage_ratio
+ minecraft:tempt_range
+ minecraft:water_movement_efficiency
- minecraft:zombie.spawn_reinforcements
```

</details>









<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:enchantable
+ minecraft:repairable
```

</details>















<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:bordure_indented_banner_pattern
+ minecraft:field_masoned_banner_pattern
```

</details>

















<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
- minecraft:crafting_special_suspiciousstew
```

</details>





<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.spawner.break
+ minecraft:block.spawner.fall
+ minecraft:block.spawner.hit
+ minecraft:block.spawner.place
+ minecraft:block.spawner.step
+ minecraft:item.bundle.insert_fail
```

</details>














<details>
<summary>
universal_tags/worldgen/placement_modifier_type.json
</summary>

```diff
- minecraft:carving_mask
```

</details>
</details>
<details><summary>Items</summary>
<details>
<summary>
List
</summary>

```diff
+ bordure_indented_banner_pattern.json
+ field_masoned_banner_pattern.json
```

</details>
<table><tr><th colspan="3">angler_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">archer_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">arms_up_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">blade_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">bolt_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">brewer_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">burn_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">chainmail_boots.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">chainmail_chestplate.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">chainmail_helmet.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">chainmail_leggings.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">coast_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">conduit.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">danger_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">disc_fragment_5.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">dragon_head.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>uncommon</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">dune_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">echo_shard.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">elytra.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>uncommon</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">enchanted_golden_apple.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>epic</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">end_crystal.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">explorer_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">eye_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">flow_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">flow_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">friend_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">goat_horn.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">golden_apple.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>common</code></td></tr></table>
<table><tr><th colspan="3">guster_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">heartbreak_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">heart_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">host_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">howl_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">miner_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">mojang_banner_pattern.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>epic</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">mourner_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_11.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_13.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_5.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_blocks.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_cat.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_chirp.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_creator_music_box.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_far.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_mall.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_mellohi.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_precipice.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_relic.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_stal.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_strad.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_wait.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">music_disc_ward.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>rare</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">nautilus_shell.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">netherite_upgrade_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">nether_star.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>uncommon</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">ominous_bottle.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">plenty_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">prize_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">raiser_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">recovery_compass.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">rib_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">scrape_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">sentry_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">shaper_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">sheaf_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">shelter_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">silence_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>epic</code></td></tr></table>
<table><tr><th colspan="3">skull_banner_pattern.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>uncommon</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">skull_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">sniffer_egg.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">snort_pottery_sherd.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">snout_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">spire_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">tide_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">trident.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>epic</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">vex_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">ward_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>rare</code></td></tr></table>
<table><tr><th colspan="3">wayfinder_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">wild_armor_trim_smithing_template.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>common</code></td><td><code>uncommon</code></td></tr></table>
<table><tr><th colspan="3">wither_skeleton_skull.json</th></tr><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><code>uncommon</code></td><td><code>rare</code></td></tr></table>
</details>
<details><summary>Commands</summary>
<details>
<summary>
experience
</summary>

```diff
+ experience add <target: entity> <amount: integer> levels
+ experience add <target: entity> <amount: integer> points
- experience add <targets: entity> <amount: integer> levels
- experience add <targets: entity> <amount: integer> points
+ experience query <target: entity> levels
+ experience query <target: entity> points
- experience query <targets: entity> levels
- experience query <targets: entity> points
+ experience set <target: entity> <amount: integer> levels
+ experience set <target: entity> <amount: integer> points
- experience set <targets: entity> <amount: integer> levels
- experience set <targets: entity> <amount: integer> points
```

</details>





<details>
<summary>
gamerule
</summary>

```diff
+ gamerule minecartMaxSpeed <value: integer>
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ bordure_indented_banner_pattern.json
+ field_masoned_banner_pattern.json
+ suspicious_stew_from_allium.json
+ suspicious_stew_from_azure_bluet.json
+ suspicious_stew_from_blue_orchid.json
+ suspicious_stew_from_cornflower.json
+ suspicious_stew_from_dandelion.json
+ suspicious_stew_from_lily_of_the_valley.json
+ suspicious_stew_from_orange_tulip.json
+ suspicious_stew_from_oxeye_daisy.json
+ suspicious_stew_from_pink_tulip.json
+ suspicious_stew_from_poppy.json
+ suspicious_stew_from_red_tulip.json
+ suspicious_stew_from_torchflower.json
+ suspicious_stew_from_white_tulip.json
+ suspicious_stew_from_wither_rose.json
- suspicious_stew.json
```

</details>




































































































































































































































































































































































<details>
<summary>
diamond_axe.json
</summary>

```
A: #diamond_tool_materials
B: diamond
C: stick

Previous pattern:
[B | B]
[B | C]
[  | C]

New pattern:
[A | A]
[A | C]
[  | C]
```

</details>








<details>
<summary>
diamond_hoe.json
</summary>

```
A: #diamond_tool_materials
B: diamond
C: stick

Previous pattern:
[B | B]
[  | C]
[  | C]

New pattern:
[A | A]
[  | C]
[  | C]
```

</details>

<details>
<summary>
diamond_pickaxe.json
</summary>

```
A: #diamond_tool_materials
B: diamond
C: stick

Previous pattern:
[B | B | B]
[  | C |  ]
[  | C |  ]

New pattern:
[A | A | A]
[  | C |  ]
[  | C |  ]
```

</details>
<details>
<summary>
diamond_shovel.json
</summary>

```
A: #diamond_tool_materials
B: diamond
C: stick

Previous pattern:
[B]
[C]
[C]

New pattern:
[A]
[C]
[C]
```

</details>
<details>
<summary>
diamond_sword.json
</summary>

```
A: #diamond_tool_materials
B: diamond
C: stick

Previous pattern:
[B]
[B]
[C]

New pattern:
[A]
[A]
[C]
```

</details>





























































































































<details>
<summary>
golden_axe.json
</summary>

```
A: #gold_tool_materials
B: gold_ingot
C: stick

Previous pattern:
[B | B]
[B | C]
[  | C]

New pattern:
[A | A]
[A | C]
[  | C]
```

</details>




<details>
<summary>
golden_hoe.json
</summary>

```
A: #gold_tool_materials
B: gold_ingot
C: stick

Previous pattern:
[B | B]
[  | C]
[  | C]

New pattern:
[A | A]
[  | C]
[  | C]
```

</details>

<details>
<summary>
golden_pickaxe.json
</summary>

```
A: #gold_tool_materials
B: gold_ingot
C: stick

Previous pattern:
[B | B | B]
[  | C |  ]
[  | C |  ]

New pattern:
[A | A | A]
[  | C |  ]
[  | C |  ]
```

</details>
<details>
<summary>
golden_shovel.json
</summary>

```
A: #gold_tool_materials
B: gold_ingot
C: stick

Previous pattern:
[B]
[C]
[C]

New pattern:
[A]
[C]
[C]
```

</details>
<details>
<summary>
golden_sword.json
</summary>

```
A: #gold_tool_materials
B: gold_ingot
C: stick

Previous pattern:
[B]
[B]
[C]

New pattern:
[A]
[A]
[C]
```

</details>





















































<details>
<summary>
iron_axe.json
</summary>

```
A: #iron_tool_materials
B: iron_ingot
C: stick

Previous pattern:
[B | B]
[B | C]
[  | C]

New pattern:
[A | A]
[A | C]
[  | C]
```

</details>






<details>
<summary>
iron_hoe.json
</summary>

```
A: #iron_tool_materials
B: iron_ingot
C: stick

Previous pattern:
[B | B]
[  | C]
[  | C]

New pattern:
[A | A]
[  | C]
[  | C]
```

</details>












<details>
<summary>
iron_pickaxe.json
</summary>

```
A: #iron_tool_materials
B: iron_ingot
C: stick

Previous pattern:
[B | B | B]
[  | C |  ]
[  | C |  ]

New pattern:
[A | A | A]
[  | C |  ]
[  | C |  ]
```

</details>
<details>
<summary>
iron_shovel.json
</summary>

```
A: #iron_tool_materials
B: iron_ingot
C: stick

Previous pattern:
[B]
[C]
[C]

New pattern:
[A]
[C]
[C]
```

</details>
<details>
<summary>
iron_sword.json
</summary>

```
A: #iron_tool_materials
B: iron_ingot
C: stick

Previous pattern:
[B]
[B]
[C]

New pattern:
[A]
[A]
[C]
```

</details>



































































































































































































































































































































































































































<details>
<summary>
shield.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: iron_ingot

Previous pattern:
[A | C | A]
[A | A | A]
[  | A |  ]

New pattern:
[B | C | B]
[B | B | B]
[  | B |  ]
```

</details>














































































































































































































































































<details>
<summary>
wooden_axe.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: stick

Previous pattern:
[A | A]
[A | C]
[  | C]

New pattern:
[B | B]
[B | C]
[  | C]
```

</details>
<details>
<summary>
wooden_hoe.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: stick

Previous pattern:
[A | A]
[  | C]
[  | C]

New pattern:
[B | B]
[  | C]
[  | C]
```

</details>
<details>
<summary>
wooden_pickaxe.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: stick

Previous pattern:
[A | A | A]
[  | C |  ]
[  | C |  ]

New pattern:
[B | B | B]
[  | C |  ]
[  | C |  ]
```

</details>
<details>
<summary>
wooden_shovel.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: stick

Previous pattern:
[A]
[C]
[C]

New pattern:
[B]
[C]
[C]
```

</details>
<details>
<summary>
wooden_sword.json
</summary>

```
A: #planks
B: #wooden_tool_materials
C: stick

Previous pattern:
[A]
[A]
[C]

New pattern:
[B]
[B]
[C]
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- addServer.hideAddress: Hide Address
- advMode.allEntities: Use "@e" to target all entities
- advMode.allPlayers: Use "@a" to target all players
- advMode.nearestPlayer: Use "@p" to target nearest player
- advMode.randomPlayer: Use "@r" to target random player
- advMode.self: Use "@s" to target the executing entity
+ attribute.name.armor_toughness: Armor Toughness
+ attribute.name.armor: Armor
+ attribute.name.attack_damage: Attack Damage
+ attribute.name.attack_knockback: Attack Knockback
+ attribute.name.attack_speed: Attack Speed
+ attribute.name.block_break_speed: Block Break Speed
+ attribute.name.block_interaction_range: Block Interaction Range
+ attribute.name.burning_time: Burning Time
+ attribute.name.entity_interaction_range: Entity Interaction Range
+ attribute.name.explosion_knockback_resistance: Explosion Knockback Resistance
+ attribute.name.fall_damage_multiplier: Fall Damage Multiplier
+ attribute.name.flying_speed: Flying Speed
+ attribute.name.follow_range: Mob Follow Range
+ attribute.name.gravity: Gravity
+ attribute.name.jump_strength: Jump Strength
+ attribute.name.knockback_resistance: Knockback Resistance
+ attribute.name.luck: Luck
+ attribute.name.max_absorption: Max Absorption
+ attribute.name.max_health: Max Health
+ attribute.name.mining_efficiency: Mining Efficiency
+ attribute.name.movement_efficiency: Movement Efficiency
+ attribute.name.movement_speed: Speed
+ attribute.name.oxygen_bonus: Oxygen Bonus
+ attribute.name.safe_fall_distance: Safe Fall Distance
+ attribute.name.scale: Scale
+ attribute.name.sneaking_speed: Sneaking Speed
+ attribute.name.spawn_reinforcements: Zombie Reinforcements
+ attribute.name.step_height: Step Height
+ attribute.name.submerged_mining_speed: Submerged Mining Speed
+ attribute.name.sweeping_damage_ratio: Sweeping Damage Ratio
+ attribute.name.tempt_range: Mob Tempt Range
+ attribute.name.water_movement_efficiency: Water Movement Efficiency
- commands.advancement.advancementNotFound: No advancement was found by the name '%1$s'
+ commands.schedule.macro: Can't schedule a macro
+ commands.setidletimeout.success.disabled: The player idle timeout is now disabled
- createWorld.customize.custom.baseSize: Depth Base Size
- createWorld.customize.custom.biomeDepthOffset: Biome Depth Offset
- createWorld.customize.custom.biomeDepthWeight: Biome Depth Weight
- createWorld.customize.custom.biomeScaleOffset: Biome Scale Offset
- createWorld.customize.custom.biomeScaleWeight: Biome Scale Weight
- createWorld.customize.custom.biomeSize: Biome Size
- createWorld.customize.custom.center: Center Height
- createWorld.customize.custom.confirm1: This will overwrite your current
- createWorld.customize.custom.confirm2: settings and cannot be undone.
- createWorld.customize.custom.confirmTitle: Warning!
- createWorld.customize.custom.coordinateScale: Coordinate Scale
- createWorld.customize.custom.count: Spawn Tries
- createWorld.customize.custom.defaults: Defaults
- createWorld.customize.custom.depthNoiseScaleExponent: Depth Noise Exponent
- createWorld.customize.custom.depthNoiseScaleX: Depth Noise Scale X
- createWorld.customize.custom.depthNoiseScaleZ: Depth Noise Scale Z
- createWorld.customize.custom.dungeonChance: Dungeon Count
- createWorld.customize.custom.fixedBiome: Biome
- createWorld.customize.custom.heightScale: Height Scale
- createWorld.customize.custom.lavaLakeChance: Lava Lake Rarity
- createWorld.customize.custom.lowerLimitScale: Lower Limit Scale
- createWorld.customize.custom.mainNoiseScaleX: Main Noise Scale X
- createWorld.customize.custom.mainNoiseScaleY: Main Noise Scale Y
- createWorld.customize.custom.mainNoiseScaleZ: Main Noise Scale Z
- createWorld.customize.custom.maxHeight: Max. Height
- createWorld.customize.custom.minHeight: Min. Height
- createWorld.customize.custom.next: Next Page
- createWorld.customize.custom.page0: Basic Settings
- createWorld.customize.custom.page1: Ore Settings
- createWorld.customize.custom.page2: Advanced Settings (Expert Users Only!)
- createWorld.customize.custom.page3: Extra Advanced Settings (Expert Users Only!)
- createWorld.customize.custom.preset.caveChaos: Caves of Chaos
- createWorld.customize.custom.preset.caveDelight: Caver's Delight
- createWorld.customize.custom.preset.drought: Drought
- createWorld.customize.custom.preset.goodLuck: Good Luck
- createWorld.customize.custom.preset.isleLand: Isle Land
- createWorld.customize.custom.preset.mountains: Mountain Madness
- createWorld.customize.custom.preset.waterWorld: Water World
- createWorld.customize.custom.presets: Presets
- createWorld.customize.custom.presets.title: Customize World Presets
- createWorld.customize.custom.prev: Previous Page
- createWorld.customize.custom.randomize: Randomize
- createWorld.customize.custom.riverSize: River Size
- createWorld.customize.custom.seaLevel: Sea Level
- createWorld.customize.custom.size: Spawn Size
- createWorld.customize.custom.spread: Spread Height
- createWorld.customize.custom.stretchY: Height Stretch
- createWorld.customize.custom.upperLimitScale: Upper Limit Scale
- createWorld.customize.custom.useCaves: Caves
- createWorld.customize.custom.useDungeons: Dungeons
- createWorld.customize.custom.useLavaLakes: Lava Lakes
- createWorld.customize.custom.useLavaOceans: Lava Oceans
- createWorld.customize.custom.useMansions: Woodland Mansions
- createWorld.customize.custom.useMineShafts: Mineshafts
- createWorld.customize.custom.useMonuments: Ocean Monuments
- createWorld.customize.custom.useOceanRuins: Ocean Ruins
- createWorld.customize.custom.useRavines: Ravines
- createWorld.customize.custom.useStrongholds: Strongholds
- createWorld.customize.custom.useTemples: Temples
- createWorld.customize.custom.useVillages: Villages
- createWorld.customize.custom.useWaterLakes: Water Lakes
- createWorld.customize.custom.waterLakeChance: Water Lake Rarity
+ dataPack.minecart_improvements.description: Improved movement for Minecarts
+ dataPack.minecart_improvements.name: Minecart Improvements
+ dataPack.redstone_experiments.description: Experimental Redstone changes
+ dataPack.redstone_experiments.name: Redstone Experiments
+ death.attack.mace_smash: %1$s was smashed by %2$s
+ death.attack.mace_smash.item: %1$s was smashed by %2$s with %3$s
- disconnect.closed: Connection closed
- disconnect.disconnected: Disconnected by Server
- disconnect.kicked: Was kicked from the game
- disconnect.loginFailed: Failed to log in
- disconnect.overflow: Buffer overflow
- disconnect.quitting: Quitting
+ gamerule.minecartMaxSpeed: Minecart max speed
+ gamerule.minecartMaxSpeed.description: Maximum default speed of a moving Minecart on land
+ gui.abuseReport.name.comment_box_label: Please describe why you want to report this name:
+ gui.abuseReport.reason.sexually_inappropriate: Sexually inappropriate
+ gui.abuseReport.reason.sexually_inappropriate.description: Skins that are graphic in nature relating to sexual acts, sexual organs, and sexual violence.
+ item.minecraft.bolt_armor_trim_smithing_template.new: Bolt Armor Trim
+ item.minecraft.bordure_indented_banner_pattern: Bordure Indented Banner Pattern
+ item.minecraft.bundle.empty: Empty
+ item.minecraft.bundle.empty.description: Can hold a mixed stack of items
+ item.minecraft.bundle.full: Full
+ item.minecraft.coast_armor_trim_smithing_template.new: Coast Armor Trim
+ item.minecraft.creeper_banner_pattern.new: Creeper Charge Banner Pattern
+ item.minecraft.dune_armor_trim_smithing_template.new: Dune Armor Trim
+ item.minecraft.eye_armor_trim_smithing_template.new: Eye Armor Trim
+ item.minecraft.field_masoned_banner_pattern: Field Masoned Banner Pattern
+ item.minecraft.flow_armor_trim_smithing_template.new: Flow Armor Trim
+ item.minecraft.flow_banner_pattern.new: Flow Banner Pattern
+ item.minecraft.flower_banner_pattern.new: Flower Charge Banner Pattern
+ item.minecraft.globe_banner_pattern.new: Globe Banner Pattern
+ item.minecraft.guster_banner_pattern.new: Guster Banner Pattern
+ item.minecraft.host_armor_trim_smithing_template.new: Host Armor Trim
+ item.minecraft.mojang_banner_pattern.new: Thing Banner Pattern
+ item.minecraft.netherite_upgrade_smithing_template.new: Netherite Upgrade
+ item.minecraft.piglin_banner_pattern.new: Snout Banner Pattern
+ item.minecraft.raiser_armor_trim_smithing_template.new: Raiser Armor Trim
+ item.minecraft.rib_armor_trim_smithing_template.new: Rib Armor Trim
+ item.minecraft.sentry_armor_trim_smithing_template.new: Sentry Armor Trim
+ item.minecraft.shaper_armor_trim_smithing_template.new: Shaper Armor Trim
+ item.minecraft.silence_armor_trim_smithing_template.new: Silence Armor Trim
+ item.minecraft.skull_banner_pattern.new: Skull Charge Banner Pattern
+ item.minecraft.snout_armor_trim_smithing_template.new: Snout Armor Trim
+ item.minecraft.spire_armor_trim_smithing_template.new: Spire Armor Trim
+ item.minecraft.tide_armor_trim_smithing_template.new: Tide Armor Trim
+ item.minecraft.vex_armor_trim_smithing_template.new: Vex Armor Trim
+ item.minecraft.ward_armor_trim_smithing_template.new: Ward Armor Trim
+ item.minecraft.wayfinder_armor_trim_smithing_template.new: Wayfinder Armor Trim
+ item.minecraft.wild_armor_trim_smithing_template.new: Wild Armor Trim
- menu.convertingLevel: Converting world
- menu.generatingLevel: Generating world
- menu.generatingTerrain: Building terrain
- menu.loadingForcedChunks: Loading forced chunks for dimension %s
- menu.loadingLevel: Loading world
- menu.respawning: Respawning
- merchant.current_level: Trader's current level
- merchant.next_level: Trader's next level
+ optimizeWorld.confirm.proceed: Create Backup and Optimize
- options.customizeTitle: Customize World Settings
+ options.inactivityFpsLimit: Reduce FPS when
+ options.inactivityFpsLimit.afk: AFK
+ options.inactivityFpsLimit.afk.tooltip: Limits framerate to 30 when the game is not getting any player input for more than a minute. Further limits it to 10 after 9 more minutes.
+ options.inactivityFpsLimit.minimized: Minimized
+ options.inactivityFpsLimit.minimized.tooltip: Limits framerate only when the game window is minimized.
+ options.rotateWithMinecart: Rotate with Minecarts
+ options.rotateWithMinecart.tooltip: If the player's view should rotate with a turning Minecart. Only available in worlds with the 'Minecart Improvements' experimental setting turned on.
- realms.missing.module.error.text: Realms could not be opened right now, please try again later
- selectServer.title: Select Server
- selectWorld.createDemo: Play New Demo World
- stat.minecraft.junk_fished: Junk Fished
- stat.minecraft.ring_bell: Bells Rung
- stat.minecraft.treasure_fished: Treasure Fished
- stats.tooltip.type.statistic: Statistic
+ subtitles.item.bundle.insert_fail: Bundle full
```

</details>
<details>
<summary>
Changes
</summary>

```
advancements.adventure.trim_with_any_armor_pattern.description: Craft a trimmed armor at a Smithing Table
advancements.husbandry.repair_wolf_armor.description: RFully repair a damaged Wolf Armor using Armadillo Scutes
chat.queue: [+%s pending lines(s)]
commands.debug.stopped: Stopped tick profiling after %s seconds(s) and %s ticks(s) (%s ticks(s) per second)
commands.schedule.created.tag: Scheduled tag '%s' in %s ticks(s) at gametime %s
commands.spreadplayers.success.entities: Spread %s player(s)entity/entities around %s, %s with an average distance of %s blocks(s) apart
commands.spreadplayers.success.teams: Spread %s team(s) around %s, %s with an average distance of %s blocks(s) apart
gui.abuseReport.name.title: Report Inappropriate Player Name
gui.abuseReport.report_sent_msg: We’'ve successfully received your report. Thank you!\n\nOur team will review it as soon as possible.
gui.banned.description.permanent: Your account is permanently banned, which means you can’'t play online or join Realms.
gui.banned.description.temporary: %s Until then, you can’'t play online or join Realms.
gui.chatReport.report_sent_msg: We’'ve successfully received your report. Thank you!\n\nOur team will review it as soon as possible.
gui.fileDropFailure.detail: Rejected %ds files
key.back: Walk Backwards
key.forward: Walk Forwards
mco.account.privacy.information: Mojang implements certain procedures to help protect children and their privacy including complying with the Children’'s Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).\n\nYou may need to obtain parental consent before accessing your Realms account.
mco.account.privacyinfo: Mojang implements certain procedures to help protect children and their privacy including complying with the Children’'s Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).\n\nYou may need to obtain parental consent before accessing your Realms account.\n\nIf you have an older Minecraft account (you log in with your username), you need to migrate the account to a Mojang account in order to access Realms.
narration.suggestion: Selected suggestion %ds out of %ds: %s
narration.suggestion.tooltip: Selected suggestion %ds out of %ds: %s (%s)
options.chat.delay: Chat Delay: %s seconds(s)
telemetry.event.world_load_times.description: It’'s important for us to understand how long it takes to join a world, and how that changes over time. For example, when we add new features or do larger technical changes, we need to see what impact that had on load times.
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
+ reports/datapack.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/food/suspicious_stew_from_allium.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_azure_bluet.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_blue_orchid.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_cornflower.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_dandelion.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_lily_of_the_valley.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_orange_tulip.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_oxeye_daisy.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_pink_tulip.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_poppy.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_red_tulip.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_torchflower.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_white_tulip.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_wither_rose.json
+ minecraft/advancement/recipes/misc/bordure_indented_banner_pattern.json
+ minecraft/advancement/recipes/misc/field_masoned_banner_pattern.json
+ minecraft/damage_type/ender_pearl.json
+ minecraft/damage_type/mace_smash.json
+ minecraft/datapacks/minecart_improvements/pack.mcmeta
+ minecraft/datapacks/redstone_experiments/pack.mcmeta
+ minecraft/instrument/admire_goat_horn.json
+ minecraft/instrument/call_goat_horn.json
+ minecraft/instrument/dream_goat_horn.json
+ minecraft/instrument/feel_goat_horn.json
+ minecraft/instrument/ponder_goat_horn.json
+ minecraft/instrument/seek_goat_horn.json
+ minecraft/instrument/sing_goat_horn.json
+ minecraft/instrument/yearn_goat_horn.json
+ minecraft/loot_table/shearing/mooshroom/brown.json
+ minecraft/loot_table/shearing/mooshroom/red.json
+ minecraft/loot_table/shearing/sheep/black.json
+ minecraft/loot_table/shearing/sheep/blue.json
+ minecraft/loot_table/shearing/sheep/brown.json
+ minecraft/loot_table/shearing/sheep/cyan.json
+ minecraft/loot_table/shearing/sheep/gray.json
+ minecraft/loot_table/shearing/sheep/green.json
+ minecraft/loot_table/shearing/sheep/light_blue.json
+ minecraft/loot_table/shearing/sheep/light_gray.json
+ minecraft/loot_table/shearing/sheep/lime.json
+ minecraft/loot_table/shearing/sheep/magenta.json
+ minecraft/loot_table/shearing/sheep/orange.json
+ minecraft/loot_table/shearing/sheep/pink.json
+ minecraft/loot_table/shearing/sheep/purple.json
+ minecraft/loot_table/shearing/sheep/red.json
+ minecraft/loot_table/shearing/sheep/white.json
+ minecraft/loot_table/shearing/sheep/yellow.json
+ minecraft/loot_table/shearing/snow_golem.json
+ minecraft/recipe/bordure_indented_banner_pattern.json
+ minecraft/recipe/field_masoned_banner_pattern.json
+ minecraft/recipe/suspicious_stew_from_allium.json
+ minecraft/recipe/suspicious_stew_from_azure_bluet.json
+ minecraft/recipe/suspicious_stew_from_blue_orchid.json
+ minecraft/recipe/suspicious_stew_from_cornflower.json
+ minecraft/recipe/suspicious_stew_from_dandelion.json
+ minecraft/recipe/suspicious_stew_from_lily_of_the_valley.json
+ minecraft/recipe/suspicious_stew_from_orange_tulip.json
+ minecraft/recipe/suspicious_stew_from_oxeye_daisy.json
+ minecraft/recipe/suspicious_stew_from_pink_tulip.json
+ minecraft/recipe/suspicious_stew_from_poppy.json
+ minecraft/recipe/suspicious_stew_from_red_tulip.json
+ minecraft/recipe/suspicious_stew_from_torchflower.json
+ minecraft/recipe/suspicious_stew_from_white_tulip.json
+ minecraft/recipe/suspicious_stew_from_wither_rose.json
- minecraft/recipe/suspicious_stew.json
- minecraft/structure/trial_chambers/chamber/slanted/hallway_4.nbt
- minecraft/structure/trial_chambers/chamber/slanted/hallway_5.nbt
+ minecraft/structure/trial_chambers/decor/black_bed.nbt
+ minecraft/structure/trial_chambers/decor/blue_bed.nbt
+ minecraft/structure/trial_chambers/decor/brown_bed.nbt
+ minecraft/structure/trial_chambers/decor/cyan_bed.nbt
+ minecraft/structure/trial_chambers/decor/disposal.nbt
+ minecraft/structure/trial_chambers/decor/gray_bed.nbt
+ minecraft/structure/trial_chambers/decor/green_bed.nbt
+ minecraft/structure/trial_chambers/decor/light_blue_bed.nbt
+ minecraft/structure/trial_chambers/decor/light_gray_bed.nbt
+ minecraft/structure/trial_chambers/decor/lime_bed.nbt
+ minecraft/structure/trial_chambers/decor/magenta_bed.nbt
+ minecraft/structure/trial_chambers/decor/orange_bed.nbt
+ minecraft/structure/trial_chambers/decor/pink_bed.nbt
+ minecraft/structure/trial_chambers/decor/purple_bed.nbt
+ minecraft/structure/trial_chambers/decor/red_bed.nbt
+ minecraft/structure/trial_chambers/decor/white_bed.nbt
+ minecraft/structure/trial_chambers/decor/yellow_bed.nbt
+ minecraft/structure/trial_chambers/hallway/encounter_1.nbt
+ minecraft/structure/trial_chambers/hallway/encounter_2.nbt
+ minecraft/structure/trial_chambers/hallway/encounter_3.nbt
+ minecraft/structure/trial_chambers/hallway/encounter_4.nbt
+ minecraft/structure/trial_chambers/hallway/encounter_5.nbt
+ minecraft/structure/trial_chambers/hallway/trapped_staircase.nbt
+ minecraft/tags/banner_pattern/pattern_item/bordure_indented.json
+ minecraft/tags/banner_pattern/pattern_item/field_masoned.json
+ minecraft/tags/damage_type/mace_smash.json
+ minecraft/tags/item/diamond_tool_materials.json
+ minecraft/tags/item/furnace_minecart_fuel.json
+ minecraft/tags/item/gold_tool_materials.json
+ minecraft/tags/item/iron_tool_materials.json
+ minecraft/tags/item/netherite_tool_materials.json
+ minecraft/tags/item/villager_picks_up.json
+ minecraft/tags/item/wooden_tool_materials.json
- minecraft/worldgen/configured_feature/seagrass_simple.json
- minecraft/worldgen/placed_feature/seagrass_simple.json
+ minecraft/worldgen/template_pool/trial_chambers/decor/bed.json
+ minecraft/worldgen/template_pool/trial_chambers/decor/disposal.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/lang/deprecated.json
+ minecraft/models/block/template_redstone_torch_wall.json
+ minecraft/models/block/template_redstone_torch.json
+ minecraft/models/item/bordure_indented_banner_pattern.json
- minecraft/models/item/bundle_filled.json
+ minecraft/models/item/bundle_open_back.json
+ minecraft/models/item/bundle_open_front.json
+ minecraft/models/item/field_masoned_banner_pattern.json
+ minecraft/shaders/core/lightmap.fsh
+ minecraft/shaders/core/lightmap.json
- minecraft/textures/gui/sprites/container/bundle/background.png
- minecraft/textures/gui/sprites/container/bundle/background.png.mcmeta
- minecraft/textures/gui/sprites/container/bundle/blocked_slot.png
+ minecraft/textures/gui/sprites/container/bundle/bundle_progressbar_border.png
+ minecraft/textures/gui/sprites/container/bundle/bundle_progressbar_border.png.mcmeta
- minecraft/textures/gui/sprites/container/bundle/slot.png
+ minecraft/textures/item/bordure_indented_banner_pattern.png
- minecraft/textures/item/bundle_filled.png
+ minecraft/textures/item/bundle_open_back.png
+ minecraft/textures/item/bundle_open_front.png
+ minecraft/textures/item/field_masoned_banner_pattern.png
+ minecraft/textures/misc/enchanted_glint_entity.png.mcmeta
+ minecraft/textures/misc/enchanted_glint_item.png.mcmeta
- minecraft/textures/misc/enchanted_item_glint.png.mcmeta
+ minecraft/textures/misc/nausea.png.mcmeta
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
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
- net.minecraft.commands.arguments.selector.options.package-info
+ net.minecraft.commands.arguments.selector.package-info
- net.minecraft.commands.arguments.selector.SelectorPattern
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
- net.minecraft.core.Cloner
+ net.minecraft.core.Cloner$Factory
- net.minecraft.core.Cursor3D
+ net.minecraft.core.DefaultedMappedRegistry
- net.minecraft.core.DefaultedRegistry
+ net.minecraft.core.Direction
- net.minecraft.core.Direction$Axis
+ net.minecraft.core.Direction$Axis$1
- net.minecraft.core.Direction$Axis$2
+ net.minecraft.core.Direction$Axis$3
- net.minecraft.core.Direction$AxisDirection
+ net.minecraft.core.Direction$Plane
- net.minecraft.core.Direction8
+ net.minecraft.core.FrontAndTop
- net.minecraft.core.GlobalPos
+ net.minecraft.core.Holder
- net.minecraft.core.Holder$Direct
+ net.minecraft.core.Holder$Kind
- net.minecraft.core.Holder$Reference
+ net.minecraft.core.Holder$Reference$Type
- net.minecraft.core.HolderGetter
+ net.minecraft.core.HolderGetter$Provider
- net.minecraft.core.HolderLookup
+ net.minecraft.core.HolderLookup$Provider
- net.minecraft.core.HolderLookup$Provider$1
+ net.minecraft.core.HolderLookup$Provider$2
- net.minecraft.core.HolderLookup$RegistryLookup
+ net.minecraft.core.HolderLookup$RegistryLookup$1
- net.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ net.minecraft.core.HolderOwner
- net.minecraft.core.HolderSet
+ net.minecraft.core.HolderSet$1
- net.minecraft.core.HolderSet$Direct
+ net.minecraft.core.HolderSet$ListBacked
- net.minecraft.core.HolderSet$Named
+ net.minecraft.core.IdMap
- net.minecraft.core.IdMapper
+ net.minecraft.core.LayeredRegistryAccess
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.MappedRegistry$1
- net.minecraft.core.MappedRegistry$2
- net.minecraft.core.MappedRegistry$4
- net.minecraft.core.MappedRegistry$TagSet$1
+ net.minecraft.core.Registry$2
- net.minecraft.core.Registry$PendingTags
- net.minecraft.data.info.DatapackStructureReport
- net.minecraft.data.info.DatapackStructureReport$Entry
- net.minecraft.data.info.DatapackStructureReport$Report
+ net.minecraft.data.info.ItemListReport
- net.minecraft.data.info.package-info
- net.minecraft.data.info.PacketReport
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLootSubProvider
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableProvider$SubProviderEntry
+ net.minecraft.data.loot.LootTableSubProvider
- net.minecraft.data.loot.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider$Runner
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider$Runner
+ net.minecraft.data.recipes.RecipeProvider$1
- net.minecraft.data.recipes.RecipeProvider$FamilyRecipeProvider
- net.minecraft.data.recipes.RecipeProvider$Runner$1
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
- net.minecraft.network.codec.ByteBufCodecs$29
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
- net.minecraft.network.package-info
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$1$1
- net.minecraft.network.protocol.BundlerInfo$Bundler
+ net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ClientboundCustomReportDetailsPacket
+ net.minecraft.network.protocol.common.ClientboundDisconnectPacket
- net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ClientboundPingPacket
- net.minecraft.network.protocol.common.ClientboundResourcePackPopPacket
+ net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
- net.minecraft.network.protocol.common.ClientboundServerLinksPacket
+ net.minecraft.network.protocol.common.ClientboundStoreCookiePacket
- net.minecraft.network.protocol.common.ClientboundTransferPacket
+ net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.common.ClientCommonPacketListener
- net.minecraft.network.protocol.common.CommonPacketTypes
- net.minecraft.network.protocol.common.custom.BeeDebugPayload
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
- net.minecraft.network.protocol.common.custom.BrainDebugPayload
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
- net.minecraft.network.protocol.common.custom.BrandPayload
+ net.minecraft.network.protocol.common.custom.BreezeDebugPayload
- net.minecraft.network.protocol.common.custom.BreezeDebugPayload$BreezeInfo
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$1
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$FallbackProvider
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$Type
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$TypeAndCodec
- net.minecraft.network.protocol.common.custom.DiscardedPayload
+ net.minecraft.network.protocol.common.custom.GameEventDebugPayload
- net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload
- net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
+ net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
+ net.minecraft.network.protocol.common.custom.package-info
- net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
- net.minecraft.network.protocol.common.custom.RaidsDebugPayload
- net.minecraft.network.protocol.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
+ net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
- net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
- net.minecraft.network.protocol.common.package-info
- net.minecraft.network.protocol.common.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ServerboundPongPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.common.ServerCommonPacketListener
- net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
- net.minecraft.network.protocol.configuration.ClientboundResetChatPacket
+ net.minecraft.network.protocol.configuration.ClientboundSelectKnownPacks
- net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
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
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetHeldSlotPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
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
- net.minecraft.network.protocol.game.ServerboundSelectBundleItemPacket
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketType
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.ProtocolCodecBuilder
- net.minecraft.network.protocol.ProtocolInfoBuilder
+ net.minecraft.network.protocol.ProtocolInfoBuilder$1
- net.minecraft.network.protocol.ProtocolInfoBuilder$CodecEntry
+ net.minecraft.network.protocol.ProtocolInfoBuilder$Implementation
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.PlaceRecipeHelper
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
+ net.minecraft.resources.RegistryDataLoader$RegistryData
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryOps$HolderLookupAdapter
- net.minecraft.resources.RegistryOps$RegistryInfo
+ net.minecraft.resources.RegistryOps$RegistryInfoLookup
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceKey$InternKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.CloneCommands$CloneBlockEntityInfo
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$CommandFunction
- net.minecraft.server.commands.CloneCommands$DimensionAndPosition
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DamageCommand
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
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugConfigCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandGetter
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$1Accumulator
+ net.minecraft.server.commands.FunctionCommand$2
- net.minecraft.server.commands.FunctionCommand$3
+ net.minecraft.server.commands.FunctionCommand$4
- net.minecraft.server.commands.FunctionCommand$5
+ net.minecraft.server.commands.FunctionCommand$Callbacks
- net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RandomCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
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
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
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
+ net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkGenerationTask
- net.minecraft.server.level.ChunkHolder
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
+ net.minecraft.server.level.GeneratingChunkMap
- net.minecraft.server.level.GenerationChunkHolder
- net.minecraft.server.level.package-info
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayer$RespawnPosAngle
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.CommonListenerCookie
- net.minecraft.server.network.ConfigurationTask
+ net.minecraft.server.network.ConfigurationTask$Type
- net.minecraft.server.network.Filterable
+ net.minecraft.server.network.FilteredText
- net.minecraft.server.network.LegacyProtocolUtils
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.LegacyTextFilter
- net.minecraft.server.network.LegacyTextFilter$JoinOrLeaveEncoder
- net.minecraft.server.network.ServerCommonPacketListenerImpl
+ net.minecraft.server.network.ServerConfigurationPacketListenerImpl
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerGamePacketListenerImpl$2
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.ServerTextFilter
- net.minecraft.server.network.ServerTextFilter$MessageEncoder
- net.minecraft.server.network.ServerTextFilter$RequestFailedException
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$Data
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerRegistries
+ net.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- net.minecraft.server.ReloadableServerRegistries$LoadResult
+ net.minecraft.server.ReloadableServerResources
+ net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- net.minecraft.server.SuppressedExceptionCollector
- net.minecraft.server.SuppressedExceptionCollector$ShortEntry
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
- net.minecraft.tags.TagLoader$LoadResult
+ net.minecraft.tags.TagLoader$SortingEntry
+ net.minecraft.tags.TagManager$LoadResult
- net.minecraft.tags.TagNetworkSerialization
+ net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.util.AbortableIterationConsumer
- net.minecraft.util.AbortableIterationConsumer$Continuation
- net.minecraft.util.ARGB
+ net.minecraft.util.ArrayListDeque
- net.minecraft.util.ArrayListDeque$DescendingIterator
+ net.minecraft.util.ArrayListDeque$ReversedView
- net.minecraft.util.BinaryAnimator
- net.minecraft.util.BitStorage
+ net.minecraft.util.Brightness
- net.minecraft.util.ByIdMap
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
- net.minecraft.util.datafix.fixes.AttributesRenameLegacy
+ net.minecraft.util.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
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
- net.minecraft.util.datafix.fixes.CarvingStepRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ net.minecraft.util.datafix.fixes.ChunkRenamesFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.CriteriaRenameFix
- net.minecraft.util.datafix.fixes.DecoratedPotFieldRenameFix
+ net.minecraft.util.datafix.fixes.DropInvalidSignDataFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EffectDurationFix
- net.minecraft.util.datafix.fixes.EmptyItemInHotbarFix
+ net.minecraft.util.datafix.fixes.EmptyItemInVillagerTradeFix
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
+ net.minecraft.util.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTagFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.JukeboxTicksSinceSongStartedFix
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
+ net.minecraft.util.datafix.FixWolfHealth
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DelegateDataOutput
+ net.minecraft.util.DependencySorter
- net.minecraft.util.DependencySorter$Entry
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.EncoderCache
- net.minecraft.util.EncoderCache$1
+ net.minecraft.util.EncoderCache$2
- net.minecraft.util.EncoderCache$Key
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
+ net.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- net.minecraft.util.ExtraCodecs$TagOrElementLocation
+ net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor$ABGR32
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.ZeroBitStorage
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.Attribute$Sentiment
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorControl
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
+ net.minecraft.world.entity.ai.behavior.declarative.package-info
- net.minecraft.world.entity.ai.behavior.declarative.Trigger
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
+ net.minecraft.world.entity.ai.behavior.LongJumpUtil
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.OneShot
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
+ net.minecraft.world.entity.ai.behavior.RandomLookAround
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
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
+ net.minecraft.world.entity.ai.behavior.TriggerGate
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
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
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
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
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.MobSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiRecord$Packed
- net.minecraft.world.entity.ai.village.poi.PoiSection$Packed
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AnimationState
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee$ValidateHiveGoal
+ net.minecraft.world.entity.animal.camel.Camel
- net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
- net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
+ net.minecraft.world.entity.animal.camel.CamelAi
- net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
+ net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
- net.minecraft.world.entity.animal.camel.package-info
+ net.minecraft.world.entity.animal.frog.Frog
- net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
+ net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
- net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
+ net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
- net.minecraft.world.entity.animal.frog.ShootTongue
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
- net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Salmon$Variant
+ net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.sniffer.package-info
+ net.minecraft.world.entity.animal.sniffer.Sniffer
- net.minecraft.world.entity.animal.sniffer.Sniffer$State
+ net.minecraft.world.entity.animal.sniffer.SnifferAi
- net.minecraft.world.entity.animal.sniffer.SnifferAi$1
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$2
- net.minecraft.world.entity.animal.sniffer.SnifferAi$3
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Digging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$FeelingHappy
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$FinishedDigging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Scenting
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Searching
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Sniffing
- net.minecraft.world.entity.boss.enderdragon.DragonFlightHistory$Sample
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.BlockAttachedEntity
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityAttachment
- net.minecraft.world.entity.EntityAttachment$Fallback
+ net.minecraft.world.entity.EntityAttachments
- net.minecraft.world.entity.EntityAttachments$Builder
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.item.PrimedTnt$1
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
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
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
- net.minecraft.world.entity.player.StackedContents$Output
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.player.StackedItemContents
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile$ProjectileFactory
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
+ net.minecraft.world.entity.projectile.windcharge.BreezeWindCharge
- net.minecraft.world.entity.projectile.windcharge.WindCharge
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
- net.minecraft.world.entity.SlotAccess$4
+ net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacementType
+ net.minecraft.world.entity.SpawnPlacementTypes
- net.minecraft.world.entity.SpawnPlacementTypes$1
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.entity.TamableAnimal$TamableAnimalPanicGoal
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.NewMinecartBehavior
- net.minecraft.world.entity.vehicle.NewMinecartBehavior$MinecartStep
- net.minecraft.world.entity.vehicle.NewMinecartBehavior$TrackIteration
- net.minecraft.world.entity.vehicle.OldMinecartBehavior$1
+ net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.InteractionResult$Fail
- net.minecraft.world.InteractionResult$Pass
- net.minecraft.world.InteractionResult$SwingSource
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.AbstractCraftingMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.ArmorSlot
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
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu$3
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.NonInteractiveResultSlot
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.PlacementInfo$SlotInfo
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeCache
+ net.minecraft.world.item.crafting.RecipeCache$Entry
- net.minecraft.world.item.crafting.RecipeHolder
+ net.minecraft.world.item.crafting.RecipeInput
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
+ net.minecraft.world.item.crafting.SingleRecipeInput
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmithingRecipe
- net.minecraft.world.item.crafting.SmithingRecipeInput
+ net.minecraft.world.item.crafting.SmithingTransformRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
+ net.minecraft.world.item.crafting.SmithingTrimRecipe
- net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$Builder
- net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
+ net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTab$Row
+ net.minecraft.world.item.CreativeModeTab$TabVisibility
- net.minecraft.world.item.CreativeModeTab$Type
+ net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.CrossbowItem$ChargingSounds
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.EitherHolder
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.enchantment.Enchantable
+ net.minecraft.world.item.enchantment.EnchantedItemInUse
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$1
- net.minecraft.world.item.enchantment.Enchantment$Builder
+ net.minecraft.world.item.enchantment.Enchantment$Cost
- net.minecraft.world.item.enchantment.Enchantment$EnchantmentDefinition
+ net.minecraft.world.item.enchantment.EnchantmentEffectComponents
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.EnchantmentTarget
- net.minecraft.world.item.enchantment.ItemEnchantments
+ net.minecraft.world.item.enchantment.ItemEnchantments$Mutable
- net.minecraft.world.item.enchantment.LevelBasedValue
+ net.minecraft.world.item.enchantment.LevelBasedValue$Clamped
- net.minecraft.world.item.enchantment.LevelBasedValue$Constant
+ net.minecraft.world.item.enchantment.LevelBasedValue$Fraction
- net.minecraft.world.item.enchantment.LevelBasedValue$LevelsSquared
+ net.minecraft.world.item.enchantment.LevelBasedValue$Linear
- net.minecraft.world.item.enchantment.LevelBasedValue$Lookup
+ net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.ToolMaterial
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
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
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BambooStalkBlock
+ net.minecraft.world.level.block.BannerBlock
- net.minecraft.world.level.block.BarrelBlock
+ net.minecraft.world.level.block.BarrierBlock
- net.minecraft.world.level.block.BaseCoralFanBlock
+ net.minecraft.world.level.block.BaseCoralPlantBlock
- net.minecraft.world.level.block.BaseCoralPlantTypeBlock
+ net.minecraft.world.level.block.BaseCoralWallFanBlock
- net.minecraft.world.level.block.BaseEntityBlock
+ net.minecraft.world.level.block.BaseFireBlock
- net.minecraft.world.level.block.BasePressurePlateBlock
+ net.minecraft.world.level.block.BaseRailBlock
- net.minecraft.world.level.block.BaseRailBlock$1
+ net.minecraft.world.level.block.BaseTorchBlock
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
- net.minecraft.world.level.block.Block$ShapePairKey
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.BrushableBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.CrafterBlockEntity
+ net.minecraft.world.level.block.entity.CrafterBlockEntity$1
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ net.minecraft.world.level.block.entity.DecoratedPotPattern
- net.minecraft.world.level.block.entity.DecoratedPotPatterns
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantingTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FuelValues
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
- net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.PotDecorations
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SignText
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity$1
+ net.minecraft.world.level.block.entity.SkullBlockEntity$2
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.entity.trialspawner.package-info
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$1
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$2
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawner$FlameParticle
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawner$StateAccessor
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerData
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$LightLevel
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$SpinningMob
+ net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
- net.minecraft.world.level.block.entity.vault.package-info
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
- net.minecraft.world.level.block.entity.vault.VaultClientData
+ net.minecraft.world.level.block.entity.vault.VaultConfig
- net.minecraft.world.level.block.entity.vault.VaultServerData
+ net.minecraft.world.level.block.entity.vault.VaultSharedData
- net.minecraft.world.level.block.entity.vault.VaultState
+ net.minecraft.world.level.block.entity.vault.VaultState$1
- net.minecraft.world.level.block.entity.vault.VaultState$2
+ net.minecraft.world.level.block.entity.vault.VaultState$3
- net.minecraft.world.level.block.entity.vault.VaultState$4
+ net.minecraft.world.level.block.entity.vault.VaultState$LightLevel
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.package-info
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
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.CarvingMask$Mask
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkGenerators
+ net.minecraft.world.level.chunk.ChunkGeneratorStructureState
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
+ net.minecraft.world.level.chunk.LightChunk
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.MissingPaletteEntryException
+ net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.Palette$Factory
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$Configuration
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PalettedContainer$Data
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
+ net.minecraft.world.level.chunk.PalettedContainerRO
- net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
+ net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.SingleValuePalette
- net.minecraft.world.level.chunk.status.ChunkDependencies
+ net.minecraft.world.level.chunk.status.ChunkPyramid
- net.minecraft.world.level.chunk.status.ChunkPyramid$Builder
+ net.minecraft.world.level.chunk.status.ChunkStatus
- net.minecraft.world.level.chunk.status.ChunkStatusTask
+ net.minecraft.world.level.chunk.status.ChunkStatusTasks
- net.minecraft.world.level.chunk.status.ChunkStep
+ net.minecraft.world.level.chunk.status.ChunkStep$Builder
- net.minecraft.world.level.chunk.status.ChunkType
- net.minecraft.world.level.chunk.status.package-info
+ net.minecraft.world.level.chunk.status.WorldGenContext
+ net.minecraft.world.level.chunk.storage.ChunkIOErrorReporter
- net.minecraft.world.level.chunk.storage.ChunkScanAccess
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
+ net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.RegionStorageInfo
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.storage.SerializableChunkData
- net.minecraft.world.level.chunk.storage.SerializableChunkData$SectionData
+ net.minecraft.world.level.chunk.storage.SimpleRegionStorage
- net.minecraft.world.level.chunk.StructureAccess
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.dimension.BuiltinDimensionTypes
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.DimensionType$MonsterSettings
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.EndDragonFight$Data
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockAndTintGetter
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.EntityTypeTest$2
+ net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetter
+ net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
+ net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
+ net.minecraft.world.level.gameevent.DynamicGameEventListener
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- net.minecraft.world.level.gameevent.GameEvent
+ net.minecraft.world.level.gameevent.GameEvent$Context
- net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
+ net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListener$Provider
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationInfo
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.Level$ExplosionInteraction
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Beardifier$1
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen
- net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
+ net.minecraft.world.level.levelgen.BitRandomSource
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
- net.minecraft.world.level.levelgen.blockpredicates.package-info
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
- net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.UnobstructedPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Density
- net.minecraft.world.level.levelgen.DensityFunction
+ net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
+ net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
+ net.minecraft.world.level.levelgen.DensityFunctions
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
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockColumnFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
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
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneUtils
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPlatformFeature
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
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.placement.BiomeFilter
+ net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.material.FlowingFluid$SpreadContext
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.MapColor
+ net.minecraft.world.level.material.MapColor$Brightness
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.Path$DebugData
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.PathfindingContext
+ net.minecraft.world.level.pathfinder.PathType
- net.minecraft.world.level.pathfinder.PathTypeCache
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.portal.DimensionTransition
- net.minecraft.world.level.portal.DimensionTransition$PostDimensionTransition
+ net.minecraft.world.level.portal.package-info
+ net.minecraft.world.level.portal.PortalForcer
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.DefaultRedstoneWireEvaluator
- net.minecraft.world.level.redstone.ExperimentalRedstoneWireEvaluator
- net.minecraft.world.level.redstone.Orientation$SideBias
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.RedstoneWireEvaluator
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecorationType
- net.minecraft.world.level.saveddata.maps.MapDecorationTypes
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapId
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapDecorationLocation
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
- net.minecraft.world.level.ServerExplosion$StackCollector
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SimpleExplosionDamageCalculator
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.Spawner
+ net.minecraft.world.level.StructureManager
- net.minecraft.world.level.WorldDataConfiguration
+ net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerScoreEntry
- net.minecraft.world.scores.PlayerScores
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.ReadOnlyScoreInfo
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.ScoreAccess
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.Scoreboard$1
+ net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.ScoreHolder
- net.minecraft.world.scores.ScoreHolder$1
+ net.minecraft.world.scores.ScoreHolder$2
- net.minecraft.world.scores.ScoreHolder$3
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.ticks.BlackholeTickAccess
- net.minecraft.world.ticks.BlackholeTickAccess$1
+ net.minecraft.world.ticks.BlackholeTickAccess$2
- net.minecraft.world.ticks.ContainerSingleItem
+ net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.BlockPredicate$Builder +3M -3M
```
```
XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.EntityPredicate$Builder +2M -2M | -2P
```
```
XXX.advancements.critereon.EntityTypePredicate +2M -2M
```
```
XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance +1M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +7M -6M
```
```
XXX.minecraft.core.Registry -1M | +1P -4P
```
```
XXX.minecraft.core.RegistrySetBuilder$3 +1M -1M
```
```
XXX.minecraft.core.RegistrySynchronization +1M
```
```
XXX.core.cauldron.CauldronInteraction +16M -15M | +1P -7P
```
```
XXX.core.component.DataComponents +2M | +2P
```
```
XXX.advancements.packs.VanillaHusbandryAdvancements +9M -9M
```
```
XXX.data.recipes.RecipeOutput +1P
```
```
XXX.data.recipes.ShapelessRecipeBuilder +4M -3M | +3P -3P
```
```
XXX.worldgen.features.AquaticFeatures -1P
```
```
XXX.worldgen.placement.AquaticPlacements -1P
```
```
XXX.gametest.framework.GameTestHelper +4M -2M
```
```
XXX.network.chat.Component +2M -1M
```
```
XXX.chat.contents.SelectorContents +3M -5M | +1P -3P
```
```
XXX.network.codec.ByteBufCodecs +1P
```
```
XXX.network.codec.ByteBufCodecs$18 +3M -3M | -1P
```
```
XXX.network.codec.ByteBufCodecs$21 +4M -5M | +4P -2P
```
```
XXX.network.codec.ByteBufCodecs$23 +3M -4M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$25 +4M -3M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$27 +4M -2M | +4P
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action +2M | +1P
```
```
XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder +1P
```
```
XXX.protocol.game.GamePacketTypes +6P -1P
```
```
XXX.protocol.game.ServerGamePacketListener +2P
```
```
XXX.minecraft.resources.RegistryDataLoader +6M -6M
```
```
XXX.minecraft.server.ServerFunctionLibrary +1M -1M
```
```
XXX.server.level.ServerChunkCache +5M -2M | +3P -1P
```
```
XXX.server.level.ServerLevel +9M -6M
```
```
XXX.server.network.TextFilter$1 -2M
```
```
XXX.minecraft.stats.RecipeBook -1M
```
```
XXX.minecraft.tags.ItemTags +7P
```
```
XXX.minecraft.util.Mth +5M -1M
```
```
XXX.minecraft.util.SpawnUtil +1M -1M
```
```
XXX.util.thread.BlockableEventLoop +1M | +1P
```
```
XXX.util.worldupdate.WorldUpgrader +1M | +6P -6P
```
```
XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader +1M
```
```
XXX.world.entity.Display +1M | +1P
```
```
XXX.world.entity.EntityType +11M -11M
```
```
XXX.world.entity.GlowSquid +2M -1M
```
```
XXX.entity.animal.Animal +3M -1M
```
```
XXX.entity.animal.Bee$BeeWanderGoal +1M | -1P
```
```
XXX.entity.animal.Cat +3M -3M | +1P
```
```
XXX.entity.animal.Dolphin +5M -1M | +1P
```
```
XXX.entity.animal.Fox$FoxGroupData +1M -1M | +1P -1P
```
```
XXX.entity.animal.MushroomCow +7M -6M
```
```
XXX.entity.animal.Ocelot +2M -2M
```
```
XXX.entity.animal.Parrot +2M -2M
```
```
XXX.entity.animal.Squid +2M
```
```
XXX.entity.animal.Turtle +2M -2M
```
```
XXX.entity.animal.WaterAnimal +1M -1M | +1P
```
```
XXX.animal.allay.Allay +5M -4M | +1P -1P
```
```
XXX.entity.projectile.AbstractArrow +2M -2M
```
```
XXX.entity.projectile.EyeOfEnder +1P
```
```
XXX.entity.vehicle.Minecart +2M | +2P
```
```
XXX.world.inventory.AbstractContainerMenu +4M | +2P
```
```
XXX.world.inventory.AbstractFurnaceMenu +3M -8M
```
```
XXX.world.item.ArmorItem +1M -1M
```
```
XXX.world.item.AxeItem +1M -1M
```
```
XXX.world.item.BannerPatternItem -2M
```
```
XXX.world.item.EnderEyeItem +1M -1M
```
```
XXX.world.item.Equipable +1M -1M
```
```
XXX.world.item.HangingEntityItem +2M -3M
```
```
XXX.world.item.HoeItem +1M -1M
```
```
XXX.world.item.Instrument +3M -2M | +2P -1P
```
```
XXX.world.item.Instruments +2M -1M | +1P -1P
```
```
XXX.world.item.Item$Properties +3M
```
```
XXX.world.item.ItemStack +17M -9M | -1P
```
```
XXX.world.item.Items +2P
```
```
XXX.world.item.KnowledgeBookItem +1M -1M
```
```
XXX.world.item.LingeringPotionItem +1M -1M
```
```
XXX.world.item.MilkBucketItem +1M -1M
```
```
XXX.world.item.PickaxeItem +1M -1M
```
```
XXX.world.item.ProjectileWeaponItem +1M -1M
```
```
XXX.world.item.ShieldItem +1M -2M
```
```
XXX.world.item.SmithingTemplateItem +3M -4M | +1P -2P
```
```
XXX.world.item.SpyglassItem +1M -1M
```
```
XXX.world.item.ThrowablePotionItem +1M -1M
```
```
XXX.world.item.WritableBookItem +1M -1M
```
```
XXX.item.component.BundleContents$Mutable +1M | +1P
```
```
XXX.item.component.Tool$Rule +3M -7M
```
```
XXX.item.crafting.CraftingInput +1M -1M | +1P -1P
```
```
XXX.item.crafting.Ingredient +13M -22M | +4P -5P
```
```
XXX.level.block.Blocks -1M
```
```
XXX.level.block.BushBlock +1M -1M
```
```
XXX.level.block.CakeBlock +1M -1M
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.level.block.CandleCakeBlock +1M -1M
```
```
XXX.level.block.ChiseledBookShelfBlock +1M -1M
```
```
XXX.level.block.CrafterBlock +1M -1M
```
```
XXX.level.block.CrossCollisionBlock +1M -1M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DoorBlock +2M -2M
```
```
XXX.level.block.FenceGateBlock +3M -3M
```
```
XXX.level.block.GlowLichenBlock +1M -1M
```
```
XXX.level.block.HeavyCoreBlock +1P
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.LecternBlock +2M -2M
```
```
XXX.level.block.PipeBlock +1M -1M
```
```
XXX.level.block.PowderSnowBlock -1M
```
```
XXX.level.block.PumpkinBlock +1M -1M
```
```
XXX.level.block.RedStoneWireBlock +6M -6M | +2P -1P
```
```
XXX.level.block.RedstoneLampBlock +1M -1M
```
```
XXX.level.block.RespawnAnchorBlock +1M -1M
```
```
XXX.level.block.SculkShriekerBlock +1M -1M
```
```
XXX.level.block.SlimeBlock +1M -1M
```
```
XXX.level.block.SoundType +1P
```
```
XXX.level.block.SpongeBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.TintedGlassBlock +2M -2M
```
```
XXX.level.block.TransparentBlock +1M -1M
```
```
XXX.level.block.VaultBlock +1M -1M
```
```
XXX.level.block.WallBlock +1M -1M
```
```
XXX.level.block.WallHangingSignBlock +1M -1M
```
```
XXX.block.entity.BlastFurnaceBlockEntity +1M -1M
```
```
XXX.block.entity.BlockEntityType +2M -2M | -1P
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M
```
```
XXX.level.levelgen.SurfaceRules$Context +1M
```
```
XXX.level.levelgen.SurfaceSystem +1M
```
```
XXX.levelgen.blending.Blender +3M -4M
```
```
XXX.levelgen.placement.PlacementModifierType -1P
```
```
XXX.levelgen.presets.WorldPresets +2M -2M
```
```
XXX.structure.pools.JigsawPlacement +1P
```
```
XXX.structure.structures.RuinedPortalStructure +2M -2M
```
```
XXX.level.lighting.LevelLightEngine +2M | +1P
```
```
XXX.level.material.FlowingFluid +8M -11M
```
```
XXX.level.redstone.NeighborUpdater +2M -2M | +2P -2P
```
```
XXX.level.storage.DimensionDataStorage +13M -4M | +2P -1P
```
```
XXX.level.storage.LevelStorageSource +1M -1M
```
```
XXX.world.phys.AABB +2M -1M
```
```
XXX.world.phys.Vec3 +4M | +1P
```

</details>




































<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate$Builder
</summary>

```diff
+ BlockPredicate$Builder of(Block[])
+ BlockPredicate$Builder of(Collection)
- BlockPredicate$Builder of(HolderGetter,Block[])
- BlockPredicate$Builder of(HolderGetter,Collection)
- BlockPredicate$Builder of(HolderGetter,TagKey)
+ BlockPredicate$Builder of(TagKey)
```

</details>










<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
</summary>

```diff
- Criterion usedItem(HolderGetter,ItemLike)
+ Criterion usedItem(ItemLike)
```

</details>













<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate$Builder
</summary>

```diff
+ EntityPredicate$Builder of(EntityType)
- EntityPredicate$Builder of(HolderGetter,EntityType)
- EntityPredicate$Builder of(HolderGetter,TagKey)
+ EntityPredicate$Builder of(TagKey)
```

</details>



<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
+ EntityTypePredicate of(EntityType)
- EntityTypePredicate of(HolderGetter,EntityType)
- EntityTypePredicate of(HolderGetter,TagKey)
+ EntityTypePredicate of(TagKey)
```

</details>












































<details>
<summary>
net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
</summary>

```diff
- Criterion shotCrossbow(HolderGetter,ItemLike)
+ Criterion shotCrossbow(ItemLike)
```

</details>













<details>
<summary>
net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
</summary>

```diff
- Criterion usedTotem(HolderGetter,ItemLike)
+ Criterion usedTotem(ItemLike)
```

</details>












<details>
<summary>
net.minecraft.commands.SharedSuggestionProvider
</summary>

```diff
+ boolean lambda$suggest$5(String,String)
- boolean lambda$suggest$6(String,String)
- ResourceLocation lambda$suggestRegistryElements$0(HolderSet$Named)
+ ResourceLocation lambda$suggestResource$0(ResourceLocation)
- ResourceLocation lambda$suggestResource$1(ResourceLocation)
+ ResourceLocation lambda$suggestResource$2(ResourceLocation)
- ResourceLocation lambda$suggestResource$3(ResourceLocation)
+ void lambda$suggestResource$1(SuggestionsBuilder,String,ResourceLocation)
- void lambda$suggestResource$2(SuggestionsBuilder,String,ResourceLocation)
+ void lambda$suggestResource$3(SuggestionsBuilder,ResourceLocation)
+ void lambda$suggestResource$4(SuggestionsBuilder,Function,Function,Object)
- void lambda$suggestResource$4(SuggestionsBuilder,ResourceLocation)
- void lambda$suggestResource$5(SuggestionsBuilder,Function,Function,Object)
```

</details>




































































<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ HolderLookup$RegistryLookup asTagAddingLookup()
```

</details>





<details>
<summary>
net.minecraft.core.RegistrySetBuilder$3
</summary>

```diff
+ Stream listRegistries()
- Stream listRegistryKeys()
```

</details>







<details>
<summary>
net.minecraft.core.RegistrySynchronization
</summary>

```diff
- boolean isNetworkable(ResourceKey)
```

</details>




<details>
<summary>
net.minecraft.core.cauldron.CauldronInteraction
</summary>

```diff
- boolean isUnderWater(Level,BlockPos)
- InteractionResult bannerInteraction(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult dyedItemIteration(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
- InteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
- InteractionResult fillLavaInteraction(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult fillPowderSnowInteraction(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult fillWaterInteraction(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
- InteractionResult shulkerBoxInteraction(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult emptyBucket(Level,BlockPos,Player,InteractionHand,ItemStack,BlockState,SoundEvent)
+ ItemInteractionResult fillBucket(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack,ItemStack,Predicate,SoundEvent)
+ ItemInteractionResult lambda$bootStrap$1(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$bootStrap$3(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$bootStrap$4(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$bootStrap$5(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$bootStrap$7(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$bootStrap$9(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$newInteractionMap$0(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$10(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$11(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$12(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$13(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$14(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
+ ItemInteractionResult lambda$static$15(BlockState,Level,BlockPos,Player,InteractionHand,ItemStack)
```

</details>









<details>
<summary>
net.minecraft.core.component.DataComponents
</summary>

```diff
- DataComponentType$Builder lambda$static$57(DataComponentType$Builder)
- DataComponentType$Builder lambda$static$58(DataComponentType$Builder)
```

</details>






































<details>
<summary>
net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
</summary>

```diff
- Advancement$Builder addBreedable(Advancement$Builder,Stream,HolderGetter,Stream)
+ Advancement$Builder addBreedable(Advancement$Builder,Stream,Stream)
- Advancement$Builder addFish(Advancement$Builder,HolderGetter)
+ Advancement$Builder addFish(Advancement$Builder)
- Advancement$Builder addFishBuckets(Advancement$Builder,HolderGetter)
+ Advancement$Builder addFishBuckets(Advancement$Builder)
- Advancement$Builder addFood(Advancement$Builder,HolderGetter)
+ Advancement$Builder addFood(Advancement$Builder)
+ Advancement$Builder addLeashedFrogVariants(Advancement$Builder)
- Advancement$Builder addLeashedFrogVariants(HolderGetter,HolderGetter,Advancement$Builder)
- AdvancementHolder createBreedAllAnimalsAdvancement(AdvancementHolder,Consumer,HolderGetter,Stream,Stream)
+ AdvancementHolder createBreedAllAnimalsAdvancement(AdvancementHolder,Consumer,Stream,Stream)
+ void lambda$addBreedable$1(Advancement$Builder,EntityType)
- void lambda$addBreedable$1(Advancement$Builder,HolderGetter,EntityType)
+ void lambda$addBreedable$2(Advancement$Builder,EntityType)
- void lambda$addBreedable$2(Advancement$Builder,HolderGetter,EntityType)
+ void lambda$addLeashedFrogVariants$0(Advancement$Builder,Holder$Reference)
- void lambda$addLeashedFrogVariants$0(Advancement$Builder,HolderGetter,HolderGetter,Holder$Reference)
```

</details>





































<details>
<summary>
net.minecraft.data.recipes.ShapelessRecipeBuilder
</summary>

```diff
- ShapelessRecipeBuilder shapeless(HolderGetter,RecipeCategory,ItemLike,int)
- ShapelessRecipeBuilder shapeless(HolderGetter,RecipeCategory,ItemLike)
- ShapelessRecipeBuilder shapeless(HolderGetter,RecipeCategory,ItemStack)
+ ShapelessRecipeBuilder shapeless(RecipeCategory,ItemLike,int)
+ ShapelessRecipeBuilder shapeless(RecipeCategory,ItemLike)
- void <init>(HolderGetter,RecipeCategory,ItemStack)
+ void <init>(RecipeCategory,ItemLike,int)
```

</details>

























































<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- AABB absoluteAABB(AABB)
- AABB relativeAABB(AABB)
- void assertEntityNotPresent(EntityType,AABB)
+ void assertEntityNotPresent(EntityType,Vec3,Vec3)
- void assertEntityPresent(EntityType,AABB)
+ void assertEntityPresent(EntityType,Vec3,Vec3)
```

</details>




































































<details>
<summary>
net.minecraft.network.chat.Component
</summary>

```diff
- MutableComponent score(SelectorPattern,String)
- MutableComponent selector(SelectorPattern,Optional)
+ MutableComponent selector(String,Optional)
```

</details>




































<details>
<summary>
net.minecraft.network.chat.contents.SelectorContents
</summary>

```diff
+ EntitySelector getSelector()
+ EntitySelector parseSelector(String)
+ Optional getSeparator()
- Optional separator()
- SelectorPattern selector()
+ String getPattern()
- void <init>(SelectorPattern,Optional)
+ void <init>(String,Optional)
```

</details>












<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$18
</summary>

```diff
- Integer decode(ByteBuf)
+ Optional decode(ByteBuf)
- void <init>()
+ void <init>(StreamCodec)
- void encode(ByteBuf,Integer)
+ void encode(ByteBuf,Optional)
```

</details>

<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$21
</summary>

```diff
+ Either decode(ByteBuf)
- Map decode(ByteBuf)
- void <init>(int,StreamCodec,StreamCodec,IntFunction)
+ void <init>(StreamCodec,StreamCodec)
+ void encode(ByteBuf,Either)
- void encode(ByteBuf,Map)
+ void lambda$encode$0(ByteBuf,StreamCodec,Object)
- void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
+ void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$23
</summary>

```diff
+ IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
- Object decode(ByteBuf)
+ Object decode(RegistryFriendlyByteBuf)
+ void <init>(Function,ResourceKey)
- void <init>(IntFunction,ToIntFunction)
- void encode(ByteBuf,Object)
+ void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$25
</summary>

```diff
- Holder decode(RegistryFriendlyByteBuf)
+ HolderSet decode(RegistryFriendlyByteBuf)
- IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
- void <init>(ResourceKey,StreamCodec)
+ void <init>(ResourceKey)
- void encode(RegistryFriendlyByteBuf,Holder)
+ void encode(RegistryFriendlyByteBuf,HolderSet)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$27
</summary>

```diff
+ GameProfile decode(ByteBuf)
- PropertyMap decode(ByteBuf)
- String lambda$decode$0(ByteBuf)
+ void encode(ByteBuf,GameProfile)
- void encode(ByteBuf,PropertyMap)
- void lambda$encode$1(ByteBuf,String)
```

</details>






<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
</summary>

```diff
- void lambda$static$12(ClientboundPlayerInfoUpdatePacket$EntryBuilder,RegistryFriendlyByteBuf)
- void lambda$static$13(RegistryFriendlyByteBuf,ClientboundPlayerInfoUpdatePacket$Entry)
```

</details>














































































<details>
<summary>
net.minecraft.resources.RegistryDataLoader
</summary>

```diff
- RegistryAccess$Frozen load(Map,ResourceProvider,List,List)
+ RegistryAccess$Frozen load(Map,ResourceProvider,RegistryAccess,List)
- RegistryAccess$Frozen load(RegistryDataLoader$LoadingFunction,List,List)
+ RegistryAccess$Frozen load(RegistryDataLoader$LoadingFunction,RegistryAccess,List)
- RegistryAccess$Frozen load(ResourceManager,List,List)
+ RegistryAccess$Frozen load(ResourceManager,RegistryAccess,List)
- RegistryOps$RegistryInfo createInfoForContextRegistry(HolderLookup$RegistryLookup)
+ RegistryOps$RegistryInfo createInfoForContextRegistry(Registry)
- RegistryOps$RegistryInfoLookup createContext(List,List)
+ RegistryOps$RegistryInfoLookup createContext(RegistryAccess,List)
- void lambda$createContext$7(Map,HolderLookup$RegistryLookup)
+ void lambda$createContext$7(Map,RegistryAccess$RegistryEntry)
```

</details>


<details>
<summary>
net.minecraft.server.ServerFunctionLibrary
</summary>

```diff
+ Collection getTag(ResourceLocation)
- List getTag(ResourceLocation)
```

</details>







<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
- void broadcastChangedChunks(ProfilerFiller)
- void collectTickingChunks(List)
- void lambda$collectTickingChunks$3(List,ChunkHolder)
+ void lambda$tickChunks$3(ServerChunkCache$ChunkAndHolder)
+ void setSpawnSettings(boolean,boolean)
- void setSpawnSettings(boolean)
- void tickChunks(ProfilerFiller,long,List)
```

</details>

<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ boolean shouldDiscardEntity(Entity)
+ Explosion explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction,ParticleOptions,ParticleOptions,Holder)
- Explosion$BlockInteraction getDestroyType(GameRules$Key)
- FuelValues fuelValues()
- int getSeaLevel()
- void explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction,ParticleOptions,ParticleOptions,Holder)
+ void neighborChanged(BlockPos,Block,BlockPos)
- void neighborChanged(BlockPos,Block,Orientation)
+ void neighborChanged(BlockState,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,BlockPos,Block,Orientation,boolean)
+ void saveLevelData()
- void saveLevelData(boolean)
- void updateNeighborsAt(BlockPos,Block,Orientation)
- void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction,Orientation)
+ void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction)
```

</details>

<details>
<summary>
net.minecraft.server.network.TextFilter$1
</summary>

```diff
+ void join()
+ void leave()
```

</details>










































































<details>
<summary>
net.minecraft.stats.RecipeBook
</summary>

```diff
+ boolean isFiltering(RecipeBookMenu)
```

</details>


























<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float easeInOutSine(float)
- float length(float,float)
- float rotLerpRad(float,float,float)
- float wrapDegrees(long)
+ int color(float,float,float)
- Vec3 lerp(double,Vec3,Vec3)
```

</details>












<details>
<summary>
net.minecraft.util.SpawnUtil
</summary>

```diff
- Optional trySpawnMob(EntityType,EntitySpawnReason,ServerLevel,BlockPos,int,int,int,SpawnUtil$Strategy)
+ Optional trySpawnMob(EntityType,MobSpawnType,ServerLevel,BlockPos,int,int,int,SpawnUtil$Strategy)
```

</details>

















































































































































































<details>
<summary>
net.minecraft.util.thread.BlockableEventLoop
</summary>

```diff
- boolean isNonRecoverable(Throwable)
```

</details>













<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader
</summary>

```diff
- void close()
```

</details>
<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
</summary>

```diff
- CompoundTag lambda$tryProcessOnePosition$1(CompoundTag)
```

</details>





































<details>
<summary>
net.minecraft.world.entity.Display
</summary>

```diff
- boolean affectedByCulling()
```

</details>










<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
- Entity create(Level,EntitySpawnReason)
+ Entity create(Level)
- Entity create(ServerLevel,Consumer,BlockPos,EntitySpawnReason,boolean,boolean)
+ Entity create(ServerLevel,Consumer,BlockPos,MobSpawnType,boolean,boolean)
- Entity lambda$create$4(Level,EntitySpawnReason,EntityType)
+ Entity lambda$create$4(Level,EntityType)
- Entity lambda$loadEntityRecursive$7(CompoundTag,Level,EntitySpawnReason,Function,Entity)
+ Entity lambda$loadEntityRecursive$7(CompoundTag,Level,Function,Entity)
- Entity loadEntityRecursive(CompoundTag,Level,EntitySpawnReason,Function)
+ Entity loadEntityRecursive(CompoundTag,Level,Function)
- Entity spawn(ServerLevel,BlockPos,EntitySpawnReason)
+ Entity spawn(ServerLevel,BlockPos,MobSpawnType)
- Entity spawn(ServerLevel,Consumer,BlockPos,EntitySpawnReason,boolean,boolean)
+ Entity spawn(ServerLevel,Consumer,BlockPos,MobSpawnType,boolean,boolean)
- Entity spawn(ServerLevel,ItemStack,Player,BlockPos,EntitySpawnReason,boolean,boolean)
+ Entity spawn(ServerLevel,ItemStack,Player,BlockPos,MobSpawnType,boolean,boolean)
- Optional create(CompoundTag,Level,EntitySpawnReason)
+ Optional create(CompoundTag,Level)
- Optional loadStaticEntity(CompoundTag,Level,EntitySpawnReason)
+ Optional loadStaticEntity(CompoundTag,Level)
- Stream loadEntitiesRecursive(List,Level,EntitySpawnReason)
+ Stream loadEntitiesRecursive(List,Level)
```

</details>





<details>
<summary>
net.minecraft.world.entity.GlowSquid
</summary>

```diff
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- boolean checkGlowSquidSpawnRules(EntityType,ServerLevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkGlowSquidSpawnRules(EntityType,ServerLevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.Animal
</summary>

```diff
- AttributeSupplier$Builder createAnimalAttributes()
- boolean checkAnimalSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkAnimalSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- void playEatingSound()
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeWanderGoal
</summary>

```diff
- int getWanderThreshold()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
- boolean isLyingOnTopOfSleepingPlayer()
+ ResourceLocation getTextureId()
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- void playEatingSound()
+ void usePlayerItem(Player,InteractionHand,ItemStack)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Dolphin
</summary>

```diff
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- boolean canAttack(LivingEntity)
- Dolphin getBreedOffspring(ServerLevel,AgeableMob)
- float getAgeScale()
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Fox$FoxGroupData
</summary>

```diff
+ void <init>(Fox$Type)
- void <init>(Fox$Variant)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
- boolean checkMushroomSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkMushroomSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
+ MushroomCow$MushroomType getOffspringType(MushroomCow)
+ MushroomCow$MushroomType getVariant()
- MushroomCow$Variant getOffspringVariant(MushroomCow)
- MushroomCow$Variant getVariant()
+ void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
+ void lambda$readAdditionalSaveData$1(SuspiciousStewEffects)
- void lambda$readAdditionalSaveData$2(SuspiciousStewEffects)
- void lambda$shear$0(ItemStack)
+ void setVariant(MushroomCow$MushroomType)
- void setVariant(MushroomCow$Variant)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- boolean checkOcelotSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkOcelotSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- boolean checkParrotSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkParrotSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>










<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
- boolean checkTurtleSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkTurtleSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.WaterAnimal
</summary>

```diff
- boolean checkSurfaceWaterAnimalSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkSurfaceWaterAnimalSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- boolean lambda$static$0(ItemStack)
+ void lambda$addAdditionalSaveData$0(String)
+ void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
- void lambda$addAdditionalSaveData$1(String)
- void lambda$addAdditionalSaveData$2(CompoundTag,Tag)
+ void lambda$readAdditionalSaveData$2(String)
- void lambda$readAdditionalSaveData$3(String)
+ void lambda$readAdditionalSaveData$3(VibrationSystem$Data)
- void lambda$readAdditionalSaveData$4(VibrationSystem$Data)
```

</details>








<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- void lambda$hitBlockEnchantmentEffects$0(Item)
+ void lambda$hitBlockEnchantmentEffects$1(Item)
+ void lambda$new$0(Item)
- void onItemBreak(Item)
```

</details>












<details>
<summary>
net.minecraft.world.entity.vehicle.Minecart
</summary>

```diff
- void positionRider(Entity,Entity$MoveFunction)
- void tick()
```

</details>








<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
- void addInventoryExtendedSlots(Container,int,int)
- void addInventoryHotbarSlots(Container,int,int)
- void addStandardInventorySlots(Container,int,int)
- void setSelectedBundleItemIndex(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu
</summary>

```diff
+ boolean recipeMatches(RecipeHolder)
+ boolean shouldMoveToInventory(int)
+ int getGridHeight()
+ int getGridWidth()
+ int getResultSlotIndex()
+ int getSize()
- RecipeBookMenu$PostPlaceAction handlePlacement(boolean,boolean,RecipeHolder,Inventory)
- Slot getResultSlot()
+ void clearCraftingContent()
+ void fillCraftSlotsStackedContents(StackedContents)
- void fillCraftSlotsStackedContents(StackedItemContents)
```

</details>













<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>



<details>
<summary>
net.minecraft.world.item.AxeItem
</summary>

```diff
+ void <init>(Tier,Item$Properties)
- void <init>(ToolMaterial,float,float,Item$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.item.BannerPatternItem
</summary>

```diff
+ MutableComponent getDisplayName()
+ void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
```

</details>


<details>
<summary>
net.minecraft.world.item.EnderEyeItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.item.Equipable
</summary>

```diff
- InteractionResult swapWithEquipmentSlot(Item,Level,Player,InteractionHand)
+ InteractionResultHolder swapWithEquipmentSlot(Item,Level,Player,InteractionHand)
```

</details>




<details>
<summary>
net.minecraft.world.item.HangingEntityItem
</summary>

```diff
- void lambda$appendHoverText$0(List,Holder)
+ void lambda$appendHoverText$0(List,ResourceKey)
+ void lambda$appendHoverText$1(List,Holder)
- void lambda$appendHoverText$1(List)
+ void lambda$appendHoverText$2(List)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ void <init>(Tier,Item$Properties)
- void <init>(ToolMaterial,float,float,Item$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.item.Instrument
</summary>

```diff
- Component description()
- float useDuration()
+ int useDuration()
- void <init>(Holder,float,float,Component)
+ void <init>(Holder,int,float)
```

</details>
<details>
<summary>
net.minecraft.world.item.Instruments
</summary>

```diff
+ Instrument bootstrap(Registry)
- void bootstrap(BootstrapContext)
- void register(BootstrapContext,ResourceKey,Holder,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
- Item$Properties enchantable(int)
- Item$Properties repairable(Item)
- Item$Properties repairable(TagKey)
```

</details>




<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- boolean hurtEnemy(LivingEntity,LivingEntity)
+ boolean hurtEnemy(LivingEntity,Player)
- boolean isBroken()
- boolean isValidRepairItem(ItemStack)
- int getEnchantmentValue()
- int processDurabilityChange(int,ServerLevel,ServerPlayer)
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
+ ItemStack lambda$lenientOptionalFieldOf$17(Optional)
- ItemStack lambda$lenientOptionalFieldOf$18(Optional)
+ Optional lambda$lenientOptionalFieldOf$18(ItemStack)
- Optional lambda$lenientOptionalFieldOf$19(ItemStack)
+ Style lambda$getDisplayName$21(Style)
- Style lambda$getDisplayName$22(Style)
- void applyDamage(int,ServerPlayer,Consumer)
- void clearComponents()
- void hurtWithoutBreaking(int,Player)
+ void lambda$addAttributeTooltips$19(MutableBoolean,Consumer,EquipmentSlotGroup,Player,Holder,AttributeModifier)
- void lambda$addAttributeTooltips$20(MutableBoolean,Consumer,EquipmentSlotGroup,Player,Holder,AttributeModifier)
+ void lambda$enchant$20(Holder,int,ItemEnchantments$Mutable)
- void lambda$enchant$21(Holder,int,ItemEnchantments$Mutable)
+ void lambda$hurtAndBreak$16(LivingEntity,EquipmentSlot,Item)
- void lambda$hurtAndBreak$17(LivingEntity,EquipmentSlot,Item)
- void lambda$hurtWithoutBreaking$16(Item)
- void postHurtEnemy(LivingEntity,LivingEntity)
+ void postHurtEnemy(LivingEntity,Player)
```

</details>






<details>
<summary>
net.minecraft.world.item.KnowledgeBookItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.item.LingeringPotionItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>

<details>
<summary>
net.minecraft.world.item.MilkBucketItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>


<details>
<summary>
net.minecraft.world.item.PickaxeItem
</summary>

```diff
+ void <init>(Tier,Item$Properties)
- void <init>(ToolMaterial,float,float,Item$Properties)
```

</details>



<details>
<summary>
net.minecraft.world.item.ProjectileWeaponItem
</summary>

```diff
+ int getEnchantmentValue()
- void lambda$shoot$2(LivingEntity,int,float,float,float,LivingEntity,Projectile)
```

</details>


<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
+ boolean isValidRepairItem(ItemStack,ItemStack)
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>

<details>
<summary>
net.minecraft.world.item.SmithingTemplateItem
</summary>

```diff
- SmithingTemplateItem createArmorTrimTemplate(Item$Properties,FeatureFlag[])
+ SmithingTemplateItem createArmorTrimTemplate(ResourceKey,FeatureFlag[])
+ SmithingTemplateItem createArmorTrimTemplate(ResourceLocation,FeatureFlag[])
+ SmithingTemplateItem createNetheriteUpgradeTemplate()
- SmithingTemplateItem createNetheriteUpgradeTemplate(Item$Properties)
+ void <init>(Component,Component,Component,Component,Component,List,List,FeatureFlag[])
- void <init>(Item$Properties,Component,Component,Component,Component,List,List,FeatureFlag[])
```

</details>


<details>
<summary>
net.minecraft.world.item.SpyglassItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>

<details>
<summary>
net.minecraft.world.item.ThrowablePotionItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>


<details>
<summary>
net.minecraft.world.item.WritableBookItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>








<details>
<summary>
net.minecraft.world.item.component.BundleContents$Mutable
</summary>

```diff
- void setSelectedItem(int)
```

</details>












<details>
<summary>
net.minecraft.world.item.component.Tool$Rule
</summary>

```diff
- Tool$Rule deniesDrops(HolderSet)
+ Tool$Rule deniesDrops(TagKey)
+ Tool$Rule forBlocks(List,Optional,Optional)
+ Tool$Rule forTag(TagKey,Optional,Optional)
- Tool$Rule minesAndDrops(HolderSet,float)
+ Tool$Rule minesAndDrops(List,float)
+ Tool$Rule minesAndDrops(TagKey,float)
- Tool$Rule overrideSpeed(HolderSet,float)
+ Tool$Rule overrideSpeed(List,float)
+ Tool$Rule overrideSpeed(TagKey,float)
```

</details>









<details>
<summary>
net.minecraft.world.item.crafting.CraftingInput
</summary>

```diff
+ StackedContents stackedContents()
- StackedItemContents stackedContents()
```

</details>



<details>
<summary>
net.minecraft.world.item.crafting.Ingredient
</summary>

```diff
+ boolean isEmpty()
+ boolean lambda$of$5(ItemStack)
- Boolean lambda$testOptionalIngredient$6(ItemStack,Ingredient)
- boolean testOptionalIngredient(Optional,ItemStack)
+ Codec codec(boolean)
+ DataResult lambda$codec$11(boolean,Ingredient)
+ DataResult lambda$codec$7(boolean,List)
- Holder$Reference lambda$of$7(ItemLike)
- HolderSet lambda$static$0(Ingredient)
- HolderSet lambda$static$2(Ingredient)
- HolderSet lambda$static$3(Optional)
- HolderSet lambda$static$4(Ingredient)
+ Ingredient fromValues(Stream)
+ Ingredient lambda$codec$8(Ingredient$Value)
+ Ingredient lambda$codec$9(Either)
+ Ingredient lambda$static$0(List)
+ Ingredient of()
- Ingredient of(HolderSet)
- Ingredient of(ItemLike)
+ Ingredient of(ItemStack[])
+ Ingredient of(TagKey)
+ Ingredient$Value[] lambda$new$2(int)
+ IntList getStackingIds()
+ ItemStack[] getItems()
+ ItemStack[] lambda$getItems$4(int)
- List items()
+ List lambda$static$1(Ingredient)
- Optional lambda$static$1(HolderSet)
+ Stream lambda$getItems$3(Ingredient$Value)
+ String lambda$codec$10()
+ String lambda$codec$6()
- void <init>(HolderSet)
+ void <init>(Ingredient$Value[])
+ void <init>(Stream)
- void lambda$new$5(List)
```

</details>

































<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ void rebuildCache()
```

</details>



<details>
<summary>
net.minecraft.world.level.block.BushBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CakeBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleCakeBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.CrafterBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CrossCollisionBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
+ void onExplosionHit(BlockState,Level,BlockPos,Explosion,BiConsumer)
- void onExplosionHit(BlockState,ServerLevel,BlockPos,Explosion,BiConsumer)
```

</details>












<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
+ void onExplosionHit(BlockState,Level,BlockPos,Explosion,BiConsumer)
- void onExplosionHit(BlockState,ServerLevel,BlockPos,Explosion,BiConsumer)
+ VoxelShape getOcclusionShape(BlockState,BlockGetter,BlockPos)
- VoxelShape getOcclusionShape(BlockState)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.GlowLichenBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ VoxelShape getOcclusionShape(BlockState,BlockGetter,BlockPos)
- VoxelShape getOcclusionShape(BlockState)
```

</details>



















<details>
<summary>
net.minecraft.world.level.block.PipeBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.PowderSnowBlock
</summary>

```diff
+ VoxelShape getOcclusionShape(BlockState,BlockGetter,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.PumpkinBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
- boolean useExperimentalEvaluator(Level)
+ int calculateTargetStrength(Level,BlockPos)
- int getBlockSignal(Level,BlockPos)
+ int getWireSignal(BlockState)
+ void lambda$static$0(Vec3[])
- void lambda$static$0(Vector3f[])
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
+ void spawnParticlesAlongLine(Level,RandomSource,BlockPos,Vec3,Direction,Direction,float,float)
- void spawnParticlesAlongLine(Level,RandomSource,BlockPos,Vector3f,Direction,Direction,float,float)
- void updatePowerStrength(Level,BlockPos,BlockState,Orientation)
+ void updatePowerStrength(Level,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedstoneLampBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
+ VoxelShape getOcclusionShape(BlockState,BlockGetter,BlockPos)
- VoxelShape getOcclusionShape(BlockState)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
+ void updateEntityAfterFallOn(BlockGetter,Entity)
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.SpongeBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.TintedGlassBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
+ int getLightBlock(BlockState,BlockGetter,BlockPos)
- int getLightBlock(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.TransparentBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.VaultBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.WallBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallHangingSignBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>






















<details>
<summary>
net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
</summary>

```diff
- int getBurnDuration(FuelValues,ItemStack)
+ int getBurnDuration(ItemStack)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntityType
</summary>

```diff
- BlockEntityType register(String,BlockEntityType$BlockEntitySupplier,Block[])
+ BlockEntityType register(String,BlockEntityType$Builder)
+ void <init>(BlockEntityType$BlockEntitySupplier,Set,Type)
- void <init>(BlockEntityType$BlockEntitySupplier,Set)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess)
```

</details>


















<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$Context
</summary>

```diff
- int getSeaLevel()
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceSystem
</summary>

```diff
- int getSeaLevel()
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.blending.Blender
</summary>

```diff
- double lambda$makeOffsetOldChunkDistanceGetter$10(double,double,double,double,double,double,double)
+ double lambda$makeOffsetOldChunkDistanceGetter$11(double,double,double,double,double,double,double)
+ double lambda$makeOldChunkDistanceGetter$10(List,double,double,double)
- double lambda$makeOldChunkDistanceGetter$9(List,double,double,double)
+ void lambda$addAroundOldChunksCarvingMaskFilter$8(CarvingMask$Mask,CarvingMask)
- void lambda$makeOldChunkDistanceGetter$8(List,Direction8,BlendingData)
+ void lambda$makeOldChunkDistanceGetter$9(List,Direction8,BlendingData)
```

</details>















<details>
<summary>
net.minecraft.world.level.levelgen.presets.WorldPresets
</summary>

```diff
- LevelStem getNormalOverworld(HolderLookup$Provider)
+ LevelStem getNormalOverworld(RegistryAccess)
- WorldDimensions createNormalWorldDimensions(HolderLookup$Provider)
+ WorldDimensions createNormalWorldDimensions(RegistryAccess)
```

</details>
















































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
</summary>

```diff
- boolean isCold(BlockPos,Holder,int)
+ boolean isCold(BlockPos,Holder)
- void lambda$findGenerationPoint$2(RuinedPortalStructure$Setup,RuinedPortalPiece$Properties,BlockPos,Structure$GenerationContext,RandomState,ChunkGenerator,ResourceLocation,StructureTemplate,Rotation,Mirror,BlockPos,StructurePiecesBuilder)
+ void lambda$findGenerationPoint$2(RuinedPortalStructure$Setup,RuinedPortalPiece$Properties,BlockPos,Structure$GenerationContext,RandomState,ResourceLocation,StructureTemplate,Rotation,Mirror,BlockPos,StructurePiecesBuilder)
```

</details>






















































<details>
<summary>
net.minecraft.world.level.lighting.LevelLightEngine
</summary>

```diff
- void <clinit>()
- void <init>()
```

</details>






<details>
<summary>
net.minecraft.world.level.material.FlowingFluid
</summary>

```diff
- boolean canHoldAnyFluid(BlockState)
- boolean canHoldSpecificFluid(BlockGetter,BlockPos,BlockState,Fluid)
- boolean canMaybePassThrough(BlockGetter,BlockPos,BlockState,Direction,BlockPos,BlockState,FluidState)
+ boolean canSpreadTo(BlockGetter,BlockPos,BlockState,Direction,BlockPos,BlockState,FluidState,Fluid)
- boolean isWaterHole(BlockGetter,BlockPos,BlockState,BlockPos,BlockState)
+ boolean isWaterHole(BlockGetter,Fluid,BlockPos,BlockState,BlockPos,BlockState)
+ boolean lambda$getSlopeDistance$2(BlockPos,LevelReader,BlockState,short)
+ boolean lambda$getSpread$4(Level,BlockPos,BlockPos,BlockState,short)
+ int getSlopeDistance(LevelReader,BlockPos,int,Direction,BlockState,BlockPos,Short2ObjectMap,Short2BooleanMap)
- int getSlopeDistance(LevelReader,BlockPos,int,Direction,BlockState,FlowingFluid$SpreadContext)
+ Pair lambda$getSlopeDistance$1(LevelReader,BlockPos,short)
+ Pair lambda$getSpread$3(Level,BlockPos,short)
+ short getCacheKey(BlockPos,BlockPos)
- void spread(Level,BlockPos,BlockState,FluidState)
+ void spread(Level,BlockPos,FluidState)
- void tick(Level,BlockPos,BlockState,FluidState)
+ void tick(Level,BlockPos,FluidState)
- VoxelShape lambda$getShape$1(BlockGetter,BlockPos,FluidState)
+ VoxelShape lambda$getShape$5(BlockGetter,BlockPos,FluidState)
```

</details>
<details>
<summary>
net.minecraft.world.level.redstone.NeighborUpdater
</summary>

```diff
+ void executeUpdate(Level,BlockState,BlockPos,Block,BlockPos,boolean)
- void executeUpdate(Level,BlockState,BlockPos,Block,Orientation,boolean)
- void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction,Orientation)
+ void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.DimensionDataStorage
</summary>

```diff
- CompletableFuture lambda$scheduleSave$0(Map$Entry)
- CompletableFuture scheduleSave()
- CompletableFuture tryWriteAsync(Path,CompoundTag)
- CompletableFuture[] lambda$scheduleSave$1(int)
- CompletionStage lambda$scheduleSave$2(Map,Object)
+ File getDataFile(String)
- Map collectDirtyTagsToSave()
- Path getDataFile(String)
+ void <init>(File,DataFixer,HolderLookup$Provider)
- void <init>(Path,DataFixer,HolderLookup$Provider)
- void close()
- void lambda$collectDirtyTagsToSave$3(Map,String,SavedData)
- void lambda$collectDirtyTagsToSave$4(Map,String,Optional)
+ void lambda$save$0(String,SavedData)
- void lambda$tryWriteAsync$5(CompoundTag,Path)
+ void save()
- void saveAndJoin()
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
- LevelDataAndDimensions getLevelDataAndDimensions(Dynamic,WorldDataConfiguration,Registry,HolderLookup$Provider)
+ LevelDataAndDimensions getLevelDataAndDimensions(Dynamic,WorldDataConfiguration,Registry,RegistryAccess$Frozen)
```

</details>























































































































<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
- Direction getDirection(double,double,double,double,double,double,Vec3,double[],Direction,double,double,double)
- Optional clip(double,double,double,double,double,double,Vec3,Vec3)
+ Vec3 getBottomCenter()
```

</details>


<details>
<summary>
net.minecraft.world.phys.Vec3
</summary>

```diff
- Vec3 add(double)
- Vec3 horizontal()
- Vec3 subtract(double)
- void <init>(Vec3i)
```

</details>
<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.blaze3d.font.package-info
- com.mojang.blaze3d.framegraph.FrameGraphBuilder$ExternalResource
- com.mojang.blaze3d.framegraph.FrameGraphBuilder$Inspector
- com.mojang.blaze3d.framegraph.FrameGraphBuilder$InternalVirtualResource
- com.mojang.blaze3d.framegraph.FrameGraphBuilder$VirtualResource
- com.mojang.blaze3d.framegraph.package-info
+ com.mojang.blaze3d.package-info
- com.mojang.blaze3d.pipeline.MainTarget
+ com.mojang.blaze3d.pipeline.MainTarget$AttachmentState
- com.mojang.blaze3d.pipeline.MainTarget$Dimension
+ com.mojang.blaze3d.pipeline.RenderCall
- com.mojang.blaze3d.platform.ClipboardManager
+ com.mojang.blaze3d.platform.DebugMemoryUntracker
- com.mojang.blaze3d.platform.DisplayData
- com.mojang.blaze3d.platform.GlStateManager$FramebufferState
+ com.mojang.blaze3d.platform.GlStateManager$LogicOp
- com.mojang.blaze3d.platform.GlStateManager$PolygonOffsetState
+ com.mojang.blaze3d.platform.GlStateManager$ScissorState
- com.mojang.blaze3d.platform.GlStateManager$SourceFactor
+ com.mojang.blaze3d.platform.GlStateManager$StencilFunc
- com.mojang.blaze3d.platform.GlStateManager$StencilState
+ com.mojang.blaze3d.platform.GlStateManager$TextureState
- com.mojang.blaze3d.platform.GlStateManager$Viewport
+ com.mojang.blaze3d.platform.GlUtil
- com.mojang.blaze3d.platform.IconSet
+ com.mojang.blaze3d.platform.InputConstants
- com.mojang.blaze3d.platform.InputConstants$Key
+ com.mojang.blaze3d.platform.InputConstants$Type
- com.mojang.blaze3d.platform.Lighting
+ com.mojang.blaze3d.platform.MacosUtil
- com.mojang.blaze3d.platform.Monitor
+ com.mojang.blaze3d.platform.MonitorCreator
- com.mojang.blaze3d.platform.NativeImage
+ com.mojang.blaze3d.platform.NativeImage$Format
- com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
+ com.mojang.blaze3d.platform.NativeImage$WriteCallback
- com.mojang.blaze3d.platform.package-info
- com.mojang.blaze3d.platform.ScreenManager
+ com.mojang.blaze3d.platform.TextureUtil
- com.mojang.blaze3d.platform.VideoMode
+ com.mojang.blaze3d.platform.Window
- com.mojang.blaze3d.platform.Window$WindowInitFailed
+ com.mojang.blaze3d.platform.WindowEventHandler
+ com.mojang.blaze3d.preprocessor.GlslPreprocessor
- com.mojang.blaze3d.preprocessor.GlslPreprocessor$Context
+ com.mojang.blaze3d.preprocessor.package-info
- com.mojang.blaze3d.resource.CrossFrameResourcePool
- com.mojang.blaze3d.resource.GraphicsResourceAllocator
- com.mojang.blaze3d.resource.RenderTargetDescriptor
- com.mojang.blaze3d.resource.ResourceHandle
- com.mojang.blaze3d.shaders.AbstractUniform
+ com.mojang.blaze3d.shaders.BlendMode
- com.mojang.blaze3d.shaders.Effect
+ com.mojang.blaze3d.shaders.EffectProgram
- com.mojang.blaze3d.shaders.EffectProgram$1
+ com.mojang.blaze3d.shaders.FogShape
+ com.mojang.blaze3d.shaders.package-info
- com.mojang.blaze3d.shaders.Program
+ com.mojang.blaze3d.shaders.Program$Type
- com.mojang.blaze3d.shaders.ProgramManager
+ com.mojang.blaze3d.shaders.Shader
- com.mojang.blaze3d.shaders.Uniform
+ com.mojang.blaze3d.systems.package-info
- com.mojang.blaze3d.systems.RenderSystem
+ com.mojang.blaze3d.systems.RenderSystem$1
- com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- com.mojang.blaze3d.systems.TimerQuery
+ com.mojang.blaze3d.systems.TimerQuery$FrameProfile
- com.mojang.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferUploader
- com.mojang.blaze3d.vertex.ByteBufferBuilder
+ com.mojang.blaze3d.vertex.ByteBufferBuilder$Result
- com.mojang.blaze3d.vertex.DefaultVertexFormat
+ com.mojang.blaze3d.vertex.MeshData
- com.mojang.blaze3d.vertex.MeshData$1
+ com.mojang.blaze3d.vertex.MeshData$DrawState
- com.mojang.blaze3d.vertex.MeshData$SortState
+ com.mojang.blaze3d.vertex.package-info
+ com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexBuffer$Usage
+ com.mojang.blaze3d.vertex.VertexConsumer
- com.mojang.blaze3d.vertex.VertexFormat
+ com.mojang.blaze3d.vertex.VertexFormat$Builder
- com.mojang.blaze3d.vertex.VertexFormat$IndexType
+ com.mojang.blaze3d.vertex.VertexFormat$Mode
- com.mojang.blaze3d.vertex.VertexFormatElement
+ com.mojang.blaze3d.vertex.VertexFormatElement$Type
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- com.mojang.blaze3d.vertex.VertexMultiConsumer
+ com.mojang.blaze3d.vertex.VertexMultiConsumer$Double
- com.mojang.blaze3d.vertex.VertexMultiConsumer$Multiple
+ com.mojang.blaze3d.vertex.VertexSorting
- com.mojang.blaze3d.vertex.VertexSorting$DistanceFunction
- com.mojang.math.Axis
+ com.mojang.math.Constants
- com.mojang.math.Divisor
+ com.mojang.math.FieldsAreNonnullByDefault
- com.mojang.math.GivensParameters
+ com.mojang.math.MatrixUtil
- com.mojang.math.MethodsReturnNonnullByDefault
+ com.mojang.math.OctahedralGroup
- com.mojang.math.OctahedralGroup$1
+ com.mojang.math.package-info
+ com.mojang.math.SymmetricGroup3
- com.mojang.math.Transformation
+ com.mojang.realmsclient.client.FileDownload
- com.mojang.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ com.mojang.realmsclient.client.FileDownload$ProgressListener
- com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
+ com.mojang.realmsclient.client.FileUpload
- com.mojang.realmsclient.client.FileUpload$CustomInputStreamEntity
- com.mojang.realmsclient.client.package-info
+ com.mojang.realmsclient.client.Ping
- com.mojang.realmsclient.client.Ping$Region
+ com.mojang.realmsclient.client.RealmsClient
- com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ com.mojang.realmsclient.client.RealmsClient$Environment
- com.mojang.realmsclient.client.RealmsClientConfig
+ com.mojang.realmsclient.client.RealmsError
- com.mojang.realmsclient.client.RealmsError$AuthenticationError
+ com.mojang.realmsclient.client.RealmsError$CustomError
- com.mojang.realmsclient.client.RealmsError$ErrorWithJsonPayload
+ com.mojang.realmsclient.client.RealmsError$ErrorWithRawPayload
- com.mojang.realmsclient.client.Request
+ com.mojang.realmsclient.client.Request$Delete
- com.mojang.realmsclient.client.Request$Get
+ com.mojang.realmsclient.client.Request$Post
- com.mojang.realmsclient.client.Request$Put
+ com.mojang.realmsclient.client.UploadStatus
+ com.mojang.realmsclient.dto.Backup
- com.mojang.realmsclient.dto.BackupList
+ com.mojang.realmsclient.dto.GuardedSerializer
- com.mojang.realmsclient.dto.Ops
- com.mojang.realmsclient.dto.package-info
+ com.mojang.realmsclient.dto.PendingInvite
- com.mojang.realmsclient.dto.PendingInvitesList
+ com.mojang.realmsclient.dto.PingResult
- com.mojang.realmsclient.dto.PlayerInfo
+ com.mojang.realmsclient.dto.RealmsDescriptionDto
- com.mojang.realmsclient.dto.RealmsNews
+ com.mojang.realmsclient.dto.RealmsNotification
- com.mojang.realmsclient.dto.RealmsNotification$InfoPopup
+ com.mojang.realmsclient.dto.RealmsNotification$UrlButton
- com.mojang.realmsclient.dto.RealmsNotification$VisitUrl
+ com.mojang.realmsclient.dto.RealmsServer
- com.mojang.realmsclient.dto.RealmsServer$Compatibility
+ com.mojang.realmsclient.dto.RealmsServer$McoServerComparator
- com.mojang.realmsclient.dto.RealmsServer$State
+ com.mojang.realmsclient.dto.RealmsServer$WorldType
- com.mojang.realmsclient.dto.RealmsServerAddress
+ com.mojang.realmsclient.dto.RealmsServerList
- com.mojang.realmsclient.dto.RealmsServerPlayerLists
+ com.mojang.realmsclient.dto.RealmsText
- com.mojang.realmsclient.dto.RealmsWorldOptions
+ com.mojang.realmsclient.dto.RealmsWorldResetDto
- com.mojang.realmsclient.dto.ReflectionBasedSerialization
+ com.mojang.realmsclient.dto.RegionPingResult
- com.mojang.realmsclient.dto.ServerActivity
+ com.mojang.realmsclient.dto.ServerActivityList
- com.mojang.realmsclient.dto.Subscription
+ com.mojang.realmsclient.dto.Subscription$SubscriptionType
- com.mojang.realmsclient.dto.UploadInfo
+ com.mojang.realmsclient.dto.ValueObject
- com.mojang.realmsclient.dto.WorldDownload
+ com.mojang.realmsclient.dto.WorldTemplate
- com.mojang.realmsclient.dto.WorldTemplate$WorldTemplateType
+ com.mojang.realmsclient.dto.WorldTemplatePaginatedList
+ com.mojang.realmsclient.exception.package-info
+ com.mojang.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- com.mojang.realmsclient.exception.RealmsHttpException
+ com.mojang.realmsclient.exception.RealmsServiceException
- com.mojang.realmsclient.exception.RetryCallException
- com.mojang.realmsclient.gui.package-info
- com.mojang.realmsclient.gui.RealmsDataFetcher
+ com.mojang.realmsclient.gui.RealmsDataFetcher$ServerListData
- com.mojang.realmsclient.gui.RealmsNewsManager
+ com.mojang.realmsclient.gui.RealmsServerList
- com.mojang.realmsclient.gui.RealmsWorldSlotButton
+ com.mojang.realmsclient.gui.RealmsWorldSlotButton$Action
- com.mojang.realmsclient.gui.RealmsWorldSlotButton$State
+ com.mojang.realmsclient.gui.RowButton
+ com.mojang.realmsclient.gui.screens.AddRealmPopupScreen
- com.mojang.realmsclient.gui.screens.package-info
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfirmScreen
- com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
+ com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
- com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen$ErrorMessage
+ com.mojang.realmsclient.gui.screens.RealmsInviteScreen
- com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
+ com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTickTaskScreen
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$1
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
- com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsPopups
- com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
+ com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$1
- com.mojang.realmsclient.gui.screens.RealmsTermsScreen
+ com.mojang.realmsclient.gui.screens.RealmsUploadScreen
- com.mojang.realmsclient.gui.screens.UploadResult
+ com.mojang.realmsclient.gui.screens.UploadResult$Builder
+ com.mojang.realmsclient.gui.task.DataFetcher
- com.mojang.realmsclient.gui.task.DataFetcher$ComputationResult
+ com.mojang.realmsclient.gui.task.DataFetcher$SubscribedTask
- com.mojang.realmsclient.gui.task.DataFetcher$Subscription
+ com.mojang.realmsclient.gui.task.DataFetcher$SuccessfulComputationResult
- com.mojang.realmsclient.gui.task.DataFetcher$Task
- com.mojang.realmsclient.gui.task.package-info
+ com.mojang.realmsclient.gui.task.RepeatedDelayStrategy
- com.mojang.realmsclient.gui.task.RepeatedDelayStrategy$1
+ com.mojang.realmsclient.gui.task.RepeatedDelayStrategy$2
+ com.mojang.realmsclient.package-info
- com.mojang.realmsclient.RealmsAvailability
+ com.mojang.realmsclient.RealmsAvailability$Result
- com.mojang.realmsclient.RealmsAvailability$Type
+ com.mojang.realmsclient.RealmsMainScreen
- com.mojang.realmsclient.RealmsMainScreen$1
+ com.mojang.realmsclient.RealmsMainScreen$2
- com.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry
+ com.mojang.realmsclient.RealmsMainScreen$ButtonEntry
- com.mojang.realmsclient.RealmsMainScreen$CrossButton
+ com.mojang.realmsclient.RealmsMainScreen$EmptyEntry
- com.mojang.realmsclient.RealmsMainScreen$Entry
+ com.mojang.realmsclient.RealmsMainScreen$LayoutState
- com.mojang.realmsclient.RealmsMainScreen$NotificationButton
+ com.mojang.realmsclient.RealmsMainScreen$NotificationMessageEntry
- com.mojang.realmsclient.RealmsMainScreen$ParentEntry
- com.mojang.realmsclient.RealmsMainScreen$RealmsCall
+ com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ com.mojang.realmsclient.RealmsMainScreen$ServerEntry
- com.mojang.realmsclient.Unit
- com.mojang.realmsclient.util.JsonUtils
+ com.mojang.realmsclient.util.LevelType
- com.mojang.realmsclient.util.package-info
- com.mojang.realmsclient.util.RealmsPersistence
+ com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- com.mojang.realmsclient.util.RealmsTextureManager
+ com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
- com.mojang.realmsclient.util.RealmsUtil
+ com.mojang.realmsclient.util.task.CloseServerTask
- com.mojang.realmsclient.util.task.ConnectTask
+ com.mojang.realmsclient.util.task.CreateSnapshotRealmTask
- com.mojang.realmsclient.util.task.DownloadTask
+ com.mojang.realmsclient.util.task.GetServerDetailsTask
- com.mojang.realmsclient.util.task.LongRunningTask
+ com.mojang.realmsclient.util.task.OpenServerTask
+ com.mojang.realmsclient.util.task.package-info
- com.mojang.realmsclient.util.task.RealmCreationTask
+ com.mojang.realmsclient.util.task.ResettingGeneratedWorldTask
- com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
+ com.mojang.realmsclient.util.task.ResettingWorldTask
- com.mojang.realmsclient.util.task.RestoreTask
+ com.mojang.realmsclient.util.task.SwitchMinigameTask
- com.mojang.realmsclient.util.task.SwitchSlotTask
+ com.mojang.realmsclient.util.TextRenderingUtils
- com.mojang.realmsclient.util.TextRenderingUtils$Line
+ com.mojang.realmsclient.util.TextRenderingUtils$LineSegment
- com.mojang.realmsclient.util.UploadTokenCache
+ com.mojang.realmsclient.util.WorldGenerationInfo
+ net.minecraft.advancements.Advancement
- net.minecraft.advancements.Advancement$Builder
+ net.minecraft.advancements.AdvancementHolder
- net.minecraft.advancements.AdvancementNode
+ net.minecraft.advancements.AdvancementProgress
- net.minecraft.advancements.AdvancementRequirements
+ net.minecraft.advancements.AdvancementRequirements$Strategy
- net.minecraft.advancements.AdvancementRewards
+ net.minecraft.advancements.AdvancementRewards$Builder
- net.minecraft.advancements.AdvancementTree
+ net.minecraft.advancements.AdvancementTree$Listener
- net.minecraft.advancements.AdvancementType
+ net.minecraft.advancements.critereon.AnyBlockInteractionTrigger
- net.minecraft.advancements.critereon.AnyBlockInteractionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BlockPredicate
- net.minecraft.advancements.critereon.BlockPredicate$Builder
+ net.minecraft.advancements.critereon.BredAnimalsTrigger
- net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BrewedPotionTrigger
- net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger
- net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger
- net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.CollectionContentsPredicate
- net.minecraft.advancements.critereon.CollectionContentsPredicate$Multiple
+ net.minecraft.advancements.critereon.CollectionContentsPredicate$Single
- net.minecraft.advancements.critereon.CollectionContentsPredicate$Zero
+ net.minecraft.advancements.critereon.CollectionCountsPredicate
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Entry
+ net.minecraft.advancements.critereon.CollectionCountsPredicate$Multiple
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Single
+ net.minecraft.advancements.critereon.CollectionCountsPredicate$Zero
- net.minecraft.advancements.critereon.CollectionPredicate
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger
- net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConsumeItemTrigger
- net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ContextAwarePredicate
- net.minecraft.advancements.critereon.CriterionValidator
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DamagePredicate
- net.minecraft.advancements.critereon.DamagePredicate$Builder
+ net.minecraft.advancements.critereon.DamageSourcePredicate
- net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
+ net.minecraft.advancements.critereon.DefaultBlockInteractionTrigger
- net.minecraft.advancements.critereon.DefaultBlockInteractionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DistancePredicate
- net.minecraft.advancements.critereon.DistanceTrigger
+ net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EffectsChangedTrigger
+ net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantedItemTrigger
+ net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EnchantmentPredicate
+ net.minecraft.advancements.critereon.EnterBlockTrigger
- net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate
- net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
+ net.minecraft.advancements.critereon.EntityFlagsPredicate
- net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EntityPredicate
- net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.EntityPredicate$LocationWrapper
- net.minecraft.advancements.critereon.EntitySubPredicate
+ net.minecraft.advancements.critereon.EntitySubPredicates
- net.minecraft.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType
+ net.minecraft.advancements.critereon.EntitySubPredicates$EntityHolderVariantPredicateType$Instance
- net.minecraft.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType
+ net.minecraft.advancements.critereon.EntitySubPredicates$EntityVariantPredicateType$Instance
- net.minecraft.advancements.critereon.EntityTypePredicate
+ net.minecraft.advancements.critereon.FallAfterExplosionTrigger
- net.minecraft.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FilledBucketTrigger
- net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FishingHookPredicate
- net.minecraft.advancements.critereon.FishingRodHookedTrigger
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FluidPredicate
+ net.minecraft.advancements.critereon.FluidPredicate$Builder
- net.minecraft.advancements.critereon.GameTypePredicate
+ net.minecraft.advancements.critereon.ImpossibleTrigger
- net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger
- net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
- net.minecraft.advancements.critereon.ItemAttributeModifiersPredicate
+ net.minecraft.advancements.critereon.ItemAttributeModifiersPredicate$EntryPredicate
- net.minecraft.advancements.critereon.ItemBundlePredicate
+ net.minecraft.advancements.critereon.ItemContainerPredicate
- net.minecraft.advancements.critereon.ItemCustomDataPredicate
+ net.minecraft.advancements.critereon.ItemDamagePredicate
- net.minecraft.advancements.critereon.ItemDurabilityTrigger
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemEnchantmentsPredicate
+ net.minecraft.advancements.critereon.ItemEnchantmentsPredicate$Enchantments
- net.minecraft.advancements.critereon.ItemEnchantmentsPredicate$StoredEnchantments
+ net.minecraft.advancements.critereon.ItemFireworkExplosionPredicate
- net.minecraft.advancements.critereon.ItemFireworkExplosionPredicate$FireworkPredicate
+ net.minecraft.advancements.critereon.ItemFireworksPredicate
- net.minecraft.advancements.critereon.ItemJukeboxPlayablePredicate
+ net.minecraft.advancements.critereon.ItemPotionsPredicate
- net.minecraft.advancements.critereon.ItemPredicate
+ net.minecraft.advancements.critereon.ItemPredicate$Builder
- net.minecraft.advancements.critereon.ItemSubPredicate
+ net.minecraft.advancements.critereon.ItemSubPredicate$Type
- net.minecraft.advancements.critereon.ItemSubPredicates
+ net.minecraft.advancements.critereon.ItemTrimPredicate
- net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger
+ net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ItemWritableBookPredicate
+ net.minecraft.advancements.critereon.ItemWritableBookPredicate$PagePredicate
- net.minecraft.advancements.critereon.ItemWrittenBookPredicate
+ net.minecraft.advancements.critereon.ItemWrittenBookPredicate$PagePredicate
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.KilledTrigger
+ net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LevitationTrigger
+ net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LightningBoltPredicate
+ net.minecraft.advancements.critereon.LightningStrikeTrigger
- net.minecraft.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.LightPredicate
+ net.minecraft.advancements.critereon.LightPredicate$Builder
+ net.minecraft.advancements.critereon.LocationPredicate
- net.minecraft.advancements.critereon.LocationPredicate$Builder
+ net.minecraft.advancements.critereon.LocationPredicate$PositionPredicate
- net.minecraft.advancements.critereon.LootTableTrigger
+ net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
- net.minecraft.advancements.critereon.MinMaxBounds
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$Doubles
- net.minecraft.advancements.critereon.MinMaxBounds$Ints
+ net.minecraft.advancements.critereon.MobEffectsPredicate
- net.minecraft.advancements.critereon.MobEffectsPredicate$Builder
+ net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- net.minecraft.advancements.critereon.MovementPredicate
+ net.minecraft.advancements.critereon.NbtPredicate
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PickedUpItemTrigger
+ net.minecraft.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerInteractTrigger
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
- net.minecraft.advancements.critereon.PlayerPredicate$Builder
+ net.minecraft.advancements.critereon.PlayerPredicate$StatMatcher
- net.minecraft.advancements.critereon.PlayerTrigger
+ net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.RaiderPredicate
+ net.minecraft.advancements.critereon.RecipeCraftedTrigger
- net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger
- net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.SimpleCriterionTrigger
- net.minecraft.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
+ net.minecraft.advancements.critereon.SingleComponentItemPredicate
- net.minecraft.advancements.critereon.SlideDownBlockTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SlimePredicate
+ net.minecraft.advancements.critereon.SlotsPredicate
- net.minecraft.advancements.critereon.StartRidingTrigger
+ net.minecraft.advancements.critereon.StartRidingTrigger$TriggerInstance
- net.minecraft.advancements.critereon.StatePropertiesPredicate
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
- net.minecraft.advancements.critereon.SummonedEntityTrigger
+ net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TagPredicate
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsingItemTrigger
- net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
+ net.minecraft.advancements.package-info
- net.minecraft.advancements.TreeNodePosition
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.client.animation.AnimationChannel
- net.minecraft.client.animation.AnimationChannel$Interpolation
+ net.minecraft.client.animation.AnimationChannel$Interpolations
- net.minecraft.client.animation.AnimationChannel$Target
+ net.minecraft.client.animation.AnimationChannel$Targets
- net.minecraft.client.animation.AnimationDefinition
+ net.minecraft.client.animation.AnimationDefinition$Builder
- net.minecraft.client.animation.definitions.ArmadilloAnimation
+ net.minecraft.client.animation.definitions.BatAnimation
- net.minecraft.client.animation.definitions.BreezeAnimation
+ net.minecraft.client.animation.definitions.CamelAnimation
- net.minecraft.client.animation.definitions.FrogAnimation
+ net.minecraft.client.animation.definitions.package-info
+ net.minecraft.client.animation.definitions.SnifferAnimation
- net.minecraft.client.animation.definitions.WardenAnimation
- net.minecraft.client.animation.Keyframe
+ net.minecraft.client.animation.KeyframeAnimations
- net.minecraft.client.animation.package-info
- net.minecraft.client.AttackIndicatorStatus
+ net.minecraft.client.Camera
- net.minecraft.client.Camera$NearPlane
+ net.minecraft.client.CameraType
- net.minecraft.client.ClientBrandRetriever
+ net.minecraft.client.ClientRecipeBook
- net.minecraft.client.ClientRecipeBook$1
+ net.minecraft.client.CloudStatus
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$CacheData
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
- net.minecraft.client.CommandHistory
+ net.minecraft.client.ComponentCollector
- net.minecraft.client.DebugQueryHandler
+ net.minecraft.client.DeltaTracker
- net.minecraft.client.DeltaTracker$DefaultValue
+ net.minecraft.client.DeltaTracker$Timer
- net.minecraft.client.GameNarrator
+ net.minecraft.client.GameNarrator$NarratorInitException
- net.minecraft.client.GraphicsStatus
- net.minecraft.client.gui.BundleMouseActions
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractContainerWidget
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractScrollWidget
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractStringWidget
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$Builder
+ net.minecraft.client.gui.components.Button$CreateNarration
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.ChatComponent$State
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.Checkbox$Builder
- net.minecraft.client.gui.components.Checkbox$OnValueChange
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.CommonButtons
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$1
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.CycleButton
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.debugchart.AbstractDebugChart
- net.minecraft.client.gui.components.debugchart.BandwidthDebugChart
+ net.minecraft.client.gui.components.debugchart.FpsDebugChart
- net.minecraft.client.gui.components.debugchart.PingDebugChart
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.FittingMultiLineTextWidget
+ net.minecraft.client.gui.components.FocusableTextWidget
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.ImageWidget
- net.minecraft.client.gui.components.ImageWidget$Sprite
+ net.minecraft.client.gui.components.ImageWidget$Texture
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LoadingDotsWidget
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.LogoRenderer
+ net.minecraft.client.gui.components.MultiLineEditBox
- net.minecraft.client.gui.components.MultiLineLabel
+ net.minecraft.client.gui.components.MultiLineLabel$1
- net.minecraft.client.gui.components.MultiLineLabel$2
+ net.minecraft.client.gui.components.MultiLineLabel$TextAndWidth
- net.minecraft.client.gui.components.MultilineTextField
+ net.minecraft.client.gui.components.MultilineTextField$1
- net.minecraft.client.gui.components.MultilineTextField$StringView
- net.minecraft.client.gui.components.MultiLineTextWidget
+ net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.OptionsList$OptionEntry
- net.minecraft.client.gui.components.PlainTextButton
+ net.minecraft.client.gui.components.PlayerFaceRenderer
- net.minecraft.client.gui.components.PlayerSkinWidget
+ net.minecraft.client.gui.components.PlayerSkinWidget$Model
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
- net.minecraft.client.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ net.minecraft.client.gui.components.PopupScreen
- net.minecraft.client.gui.components.PopupScreen$Builder
+ net.minecraft.client.gui.components.PopupScreen$ButtonOption
- net.minecraft.client.gui.components.Renderable
+ net.minecraft.client.gui.components.SplashRenderer
- net.minecraft.client.gui.components.SpriteIconButton
+ net.minecraft.client.gui.components.SpriteIconButton$Builder
- net.minecraft.client.gui.components.SpriteIconButton$CenteredIcon
+ net.minecraft.client.gui.components.SpriteIconButton$TextAndIcon
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.StringWidget
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$SoundPlayedAt
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.TabButton
- net.minecraft.client.gui.components.TabOrderedElement
+ net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast$RecipeDisplayItems
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastId
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastManager$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
+ net.minecraft.client.gui.components.Tooltip
- net.minecraft.client.gui.components.Whence
+ net.minecraft.client.gui.components.WidgetSprites
- net.minecraft.client.gui.components.WidgetTooltipHolder
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.CodepointMap
- net.minecraft.client.gui.font.CodepointMap$Output
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$BuilderId
+ net.minecraft.client.gui.font.FontManager$BuilderResult
- net.minecraft.client.gui.font.FontManager$FontDefinitionFile
+ net.minecraft.client.gui.font.FontManager$Preparation
- net.minecraft.client.gui.font.FontManager$UnresolvedBuilderBundle
+ net.minecraft.client.gui.font.FontOption
- net.minecraft.client.gui.font.FontOption$Filter
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontSet$GlyphInfoFilter
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.GlyphRenderTypes
- net.minecraft.client.gui.font.GlyphRenderTypes$1
+ net.minecraft.client.gui.font.glyphs.BakedGlyph
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs$1
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$Definition
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.FreeTypeUtil
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Conditional
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Loader
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Reference
- net.minecraft.client.gui.font.providers.GlyphProviderType
+ net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.ProviderReferenceDefinition
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition$Shift
- net.minecraft.client.gui.font.providers.UnihexProvider
+ net.minecraft.client.gui.font.providers.UnihexProvider$ByteContents
- net.minecraft.client.gui.font.providers.UnihexProvider$Definition
+ net.minecraft.client.gui.font.providers.UnihexProvider$Dimensions
- net.minecraft.client.gui.font.providers.UnihexProvider$Glyph
+ net.minecraft.client.gui.font.providers.UnihexProvider$Glyph$1
- net.minecraft.client.gui.font.providers.UnihexProvider$IntContents
+ net.minecraft.client.gui.font.providers.UnihexProvider$LineData
- net.minecraft.client.gui.font.providers.UnihexProvider$OverrideRange
+ net.minecraft.client.gui.font.providers.UnihexProvider$ReaderOutput
- net.minecraft.client.gui.font.providers.UnihexProvider$ShortContents
+ net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.font.TextFieldHelper$CursorStep
- net.minecraft.client.gui.LayeredDraw
+ net.minecraft.client.gui.LayeredDraw$Layer
- net.minecraft.client.gui.layouts.AbstractLayout
+ net.minecraft.client.gui.layouts.AbstractLayout$AbstractChildWrapper
- net.minecraft.client.gui.layouts.CommonLayouts
+ net.minecraft.client.gui.layouts.EqualSpacingLayout
- net.minecraft.client.gui.layouts.EqualSpacingLayout$ChildContainer
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$Orientation
- net.minecraft.client.gui.layouts.FrameLayout
+ net.minecraft.client.gui.layouts.FrameLayout$ChildContainer
- net.minecraft.client.gui.layouts.GridLayout
+ net.minecraft.client.gui.layouts.GridLayout$CellInhabitant
- net.minecraft.client.gui.layouts.GridLayout$RowHelper
+ net.minecraft.client.gui.layouts.HeaderAndFooterLayout
- net.minecraft.client.gui.layouts.Layout
+ net.minecraft.client.gui.layouts.LayoutElement
- net.minecraft.client.gui.layouts.LayoutSettings
+ net.minecraft.client.gui.layouts.LayoutSettings$LayoutSettingsImpl
- net.minecraft.client.gui.layouts.LinearLayout
+ net.minecraft.client.gui.layouts.LinearLayout$Orientation
+ net.minecraft.client.gui.layouts.package-info
- net.minecraft.client.gui.layouts.SpacerElement
+ net.minecraft.client.gui.MapRenderer$MapInstance
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
- net.minecraft.client.gui.navigation.CommonInputs
+ net.minecraft.client.gui.navigation.FocusNavigationEvent
- net.minecraft.client.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$InitialFocus
- net.minecraft.client.gui.navigation.FocusNavigationEvent$TabNavigation
+ net.minecraft.client.gui.navigation.package-info
+ net.minecraft.client.gui.navigation.ScreenAxis
- net.minecraft.client.gui.navigation.ScreenDirection
+ net.minecraft.client.gui.navigation.ScreenPosition
- net.minecraft.client.gui.navigation.ScreenPosition$1
+ net.minecraft.client.gui.navigation.ScreenRectangle
- net.minecraft.client.gui.navigation.ScreenRectangle$1
- net.minecraft.client.gui.package-info
+ net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
+ net.minecraft.client.gui.screens.achievement.package-info
+ net.minecraft.client.gui.screens.achievement.StatsScreen
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$Sprites
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType$1
+ net.minecraft.client.gui.screens.advancements.package-info
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.BanNoticeScreens
- net.minecraft.client.gui.screens.ChatScreen
+ net.minecraft.client.gui.screens.ChatScreen$1
- net.minecraft.client.gui.screens.ConfirmLinkScreen
+ net.minecraft.client.gui.screens.ConfirmScreen
- net.minecraft.client.gui.screens.ConnectScreen
+ net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.ConnectScreen$2
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.CreditsAndAttributionScreen
- net.minecraft.client.gui.screens.DatapackLoadFailureScreen
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.DeathScreen$TitleConfirmScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
- net.minecraft.client.gui.screens.debug.package-info
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.FaviconTexture
+ net.minecraft.client.gui.screens.GenericMessageScreen
- net.minecraft.client.gui.screens.GenericWaitingScreen
+ net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
- net.minecraft.client.gui.screens.inventory.AnvilScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen$1
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
- net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
+ net.minecraft.client.gui.screens.inventory.BookViewScreen
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CrafterScreen
+ net.minecraft.client.gui.screens.inventory.CrafterScreen$1
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.CyclingSlotBackground
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmithingScreen
+ net.minecraft.client.gui.screens.inventory.SmokerScreen
- net.minecraft.client.gui.screens.inventory.StonecutterScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.ClientActivePlayersTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientActivePlayersTooltip$ActivePlayersTooltip
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingDotsText
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.NoticeWithLinkScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PauseScreen$FeedbackSubScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen$Reason
+ net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.CraftingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe
- net.minecraft.client.gui.screens.recipebook.GhostSlots
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- net.minecraft.client.gui.screens.recipebook.package-info
+ net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.RecipeBookPage
+ net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
- net.minecraft.client.gui.screens.recipebook.RecipeButton
+ net.minecraft.client.gui.screens.recipebook.RecipeCollection
- net.minecraft.client.gui.screens.recipebook.RecipeCollection$CraftableStatus
+ net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
+ net.minecraft.client.gui.screens.RecoverWorldDataScreen
+ net.minecraft.client.gui.screens.reporting.AbstractReportScreen
- net.minecraft.client.gui.screens.reporting.AbstractReportScreen$DiscardReportWarningScreen
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen
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
- net.minecraft.client.gui.screens.reporting.NameReportScreen
- net.minecraft.client.gui.screens.reporting.package-info
+ net.minecraft.client.gui.screens.reporting.ReportPlayerScreen
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ net.minecraft.client.gui.screens.reporting.SkinReportScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$DeferredTooltipRendering
- net.minecraft.client.gui.screens.Screen$NarratableSearchResult
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.social.package-info
+ net.minecraft.client.gui.screens.social.PlayerEntry
- net.minecraft.client.gui.screens.social.PlayerEntry$1
+ net.minecraft.client.gui.screens.social.PlayerEntry$2
- net.minecraft.client.gui.screens.social.PlayerEntry$3
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.telemetry.package-info
+ net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$Content
+ net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$ContentBuilder
- net.minecraft.client.gui.screens.telemetry.TelemetryInfoScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.WinScreen
- net.minecraft.client.gui.screens.WinScreen$CreditsReader
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$GameTab
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$MoreTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$1
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$2
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
+ net.minecraft.client.gui.screens.worldselection.EditWorldScreen
- net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
+ net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
+ net.minecraft.client.gui.screens.worldselection.package-info
- net.minecraft.client.gui.screens.worldselection.PresetEditor
+ net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
- net.minecraft.client.gui.screens.worldselection.SwitchGrid
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$Builder
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$InfoUnderneathSettings
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$LabeledSwitch
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$SwitchBuilder
+ net.minecraft.client.gui.screens.worldselection.WorldCreationContext
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext$DimensionsUpdater
+ net.minecraft.client.gui.screens.worldselection.WorldCreationContext$OptionsModifier
- net.minecraft.client.gui.screens.worldselection.WorldCreationUiState
+ net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$SelectedGameMode
- net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$WorldTypeEntry
+ net.minecraft.client.gui.screens.worldselection.WorldOpenFlows
- net.minecraft.client.gui.screens.worldselection.WorldOpenFlows$1Data
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$Entry
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$LoadingHeader
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
+ net.minecraft.client.gui.spectator.categories.package-info
+ net.minecraft.client.gui.spectator.categories.SpectatorPage
- net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- net.minecraft.client.gui.spectator.package-info
- net.minecraft.client.gui.spectator.PlayerMenuItem
+ net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenu
+ net.minecraft.client.gui.spectator.SpectatorMenu$1
- net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuListener
+ net.minecraft.client.GuiMessage
- net.minecraft.client.GuiMessage$Line
+ net.minecraft.client.GuiMessageTag
- net.minecraft.client.GuiMessageTag$Icon
+ net.minecraft.client.HotbarManager
- net.minecraft.client.InactivityFpsLimit
+ net.minecraft.client.main.GameConfig
- net.minecraft.client.main.GameConfig$FolderData
+ net.minecraft.client.main.GameConfig$GameData
- net.minecraft.client.main.GameConfig$QuickPlayData
+ net.minecraft.client.main.GameConfig$UserData
- net.minecraft.client.main.Main
+ net.minecraft.client.main.Main$1
- net.minecraft.client.main.Main$2
- net.minecraft.client.main.package-info
+ net.minecraft.client.main.SilentInitException
- net.minecraft.client.Minecraft$ChatStatus
+ net.minecraft.client.Minecraft$ChatStatus$1
- net.minecraft.client.Minecraft$ChatStatus$2
+ net.minecraft.client.Minecraft$ChatStatus$3
- net.minecraft.client.Minecraft$ChatStatus$4
+ net.minecraft.client.Minecraft$GameLoadCookie
- net.minecraft.client.model.AbstractPiglinModel
+ net.minecraft.client.model.AbstractZombieModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AllayModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmadilloModel
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.ArrowModel
- net.minecraft.client.model.BabyModelTransform
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BellModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BoggedModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.BreezeModel
- net.minecraft.client.model.CamelModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestModel
+ net.minecraft.client.model.ChestRaftModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.DonkeyModel
- net.minecraft.client.model.dragon.EnderDragonModel
+ net.minecraft.client.model.dragon.package-info
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FelineModel
+ net.minecraft.client.model.geom.builders.CubeDefinition
- net.minecraft.client.model.geom.builders.CubeDeformation
+ net.minecraft.client.model.geom.builders.CubeListBuilder
- net.minecraft.client.model.geom.builders.LayerDefinition
+ net.minecraft.client.model.geom.builders.MaterialDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
- net.minecraft.client.model.geom.EntityModelSet
+ net.minecraft.client.model.geom.LayerDefinitions
- net.minecraft.client.model.geom.ModelLayerLocation
+ net.minecraft.client.model.geom.ModelLayers
- net.minecraft.client.model.geom.ModelPart
+ net.minecraft.client.model.geom.ModelPart$Cube
- net.minecraft.client.model.geom.ModelPart$Polygon
+ net.minecraft.client.model.geom.ModelPart$Vertex
- net.minecraft.client.model.geom.ModelPart$Visitor
+ net.minecraft.client.model.geom.PartNames
- net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.HierarchicalModel
- net.minecraft.client.model.HoglinModel
+ net.minecraft.client.model.HorseModel
- net.minecraft.client.model.HumanoidArmorModel
+ net.minecraft.client.model.HumanoidModel
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.PlayerCapeModel
+ net.minecraft.client.model.WaterPatchModel
- net.minecraft.client.model.WindChargeModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.model.ZombifiedPiglinModel
- net.minecraft.client.MouseHandler
+ net.minecraft.client.multiplayer.chat.report.package-info
- net.minecraft.client.multiplayer.chat.report.ReportingContext
- net.minecraft.client.multiplayer.chat.report.ReportReason$1
+ net.minecraft.client.multiplayer.chat.report.ReportType
+ net.minecraft.client.multiplayer.chat.report.SkinReport
- net.minecraft.client.multiplayer.chat.report.SkinReport$Builder
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- net.minecraft.client.multiplayer.prediction.package-info
+ net.minecraft.client.multiplayer.prediction.PredictiveAction
+ net.minecraft.client.multiplayer.resolver.AddressCheck
- net.minecraft.client.multiplayer.resolver.AddressCheck$1
+ net.minecraft.client.multiplayer.resolver.package-info
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
+ net.minecraft.client.multiplayer.resolver.ServerAddress
- net.minecraft.client.multiplayer.resolver.ServerAddressResolver
+ net.minecraft.client.multiplayer.resolver.ServerNameResolver
- net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerData$State
+ net.minecraft.client.multiplayer.ServerData$Type
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.SessionSearchTrees
+ net.minecraft.client.multiplayer.SessionSearchTrees$Key
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
+ net.minecraft.client.OptionInstance$UnitDouble
- net.minecraft.client.OptionInstance$UnitDouble$1
+ net.minecraft.client.OptionInstance$ValueSet
- net.minecraft.client.Options
+ net.minecraft.client.Options$1
- net.minecraft.client.Options$2
+ net.minecraft.client.Options$3
- net.minecraft.client.Options$4
+ net.minecraft.client.Options$5
- net.minecraft.client.Options$FieldAccess
+ net.minecraft.client.Options$OptionAccess
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BaseAshSmokeParticle
- net.minecraft.client.particle.BlockMarker
+ net.minecraft.client.particle.BlockMarker$Provider
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$CobwebProvider
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CherryParticle
+ net.minecraft.client.particle.CritParticle
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
+ net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallAndLandParticle
+ net.minecraft.client.particle.DripParticle$FallingParticle
- net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
+ net.minecraft.client.particle.DustColorTransitionParticle
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.DustParticleBase
- net.minecraft.client.particle.DustPlumeParticle
+ net.minecraft.client.particle.DustPlumeParticle$Provider
- net.minecraft.client.particle.EndRodParticle
+ net.minecraft.client.particle.EndRodParticle$Provider
- net.minecraft.client.particle.ExplodeParticle
+ net.minecraft.client.particle.ExplodeParticle$Provider
- net.minecraft.client.particle.FallingDustParticle
+ net.minecraft.client.particle.FallingDustParticle$Provider
- net.minecraft.client.particle.FireworkParticles
+ net.minecraft.client.particle.FireworkParticles$1
- net.minecraft.client.particle.FireworkParticles$FlashProvider
+ net.minecraft.client.particle.FireworkParticles$OverlayParticle
- net.minecraft.client.particle.FireworkParticles$SparkParticle
+ net.minecraft.client.particle.FireworkParticles$SparkProvider
- net.minecraft.client.particle.FireworkParticles$Starter
+ net.minecraft.client.particle.FlameParticle
- net.minecraft.client.particle.FlameParticle$Provider
+ net.minecraft.client.particle.FlameParticle$SmallFlameProvider
- net.minecraft.client.particle.FlyStraightTowardsParticle
+ net.minecraft.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
- net.minecraft.client.particle.FlyTowardsPositionParticle
+ net.minecraft.client.particle.FlyTowardsPositionParticle$EnchantProvider
- net.minecraft.client.particle.FlyTowardsPositionParticle$NautilusProvider
+ net.minecraft.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
- net.minecraft.client.particle.GlowParticle
+ net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
- net.minecraft.client.particle.GlowParticle$GlowSquidProvider
+ net.minecraft.client.particle.GlowParticle$ScrapeProvider
- net.minecraft.client.particle.GlowParticle$WaxOffProvider
+ net.minecraft.client.particle.GlowParticle$WaxOnProvider
- net.minecraft.client.particle.GustParticle
+ net.minecraft.client.particle.GustParticle$Provider
- net.minecraft.client.particle.GustParticle$SmallProvider
+ net.minecraft.client.particle.GustSeedParticle
- net.minecraft.client.particle.GustSeedParticle$Provider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.Particle$LifetimeAlpha
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
- net.minecraft.client.particle.ParticleEngine$1ParticleDefinition
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleProvider$Sprite
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.LiquidBlockRenderer$1
- net.minecraft.client.renderer.block.model.BakedQuad
+ net.minecraft.client.renderer.block.model.BlockElement
- net.minecraft.client.renderer.block.model.BlockElement$1
+ net.minecraft.client.renderer.block.model.BlockElement$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementFace
+ net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementRotation
+ net.minecraft.client.renderer.block.model.BlockFaceUV
- net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel
- net.minecraft.client.renderer.block.model.BlockModel$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel$GuiLight
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.multipart.MultiPart$1Key
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.UnbakedBlockStateModel
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ net.minecraft.client.renderer.blockentity.LecternRenderer
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
- net.minecraft.client.renderer.blockentity.SignRenderer$Models
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.CloudRenderer$RelativeCameraPos
- net.minecraft.client.renderer.CubeMap
- net.minecraft.client.renderer.debug.ChunkDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
- net.minecraft.client.renderer.debug.CollisionBoxRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer
- net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
- net.minecraft.client.renderer.debug.GameTestDebugRenderer
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer
- net.minecraft.client.renderer.debug.LightSectionDebugRenderer$SectionData
+ net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.PathfindingRenderer
+ net.minecraft.client.renderer.debug.RaidDebugRenderer
- net.minecraft.client.renderer.debug.RedstoneWireOrientationsRenderer
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.entity.AbstractHoglinRenderer
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractMinecartRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.BoggedRenderer
+ net.minecraft.client.renderer.entity.BreezeRenderer
- net.minecraft.client.renderer.entity.CamelRenderer
+ net.minecraft.client.renderer.entity.CatRenderer
- net.minecraft.client.renderer.entity.CaveSpiderRenderer
+ net.minecraft.client.renderer.entity.ChestedHorseRenderer
- net.minecraft.client.renderer.entity.DragonFireballRenderer
+ net.minecraft.client.renderer.entity.DrownedRenderer
- net.minecraft.client.renderer.entity.ElderGuardianRenderer
+ net.minecraft.client.renderer.entity.EndCrystalRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer$Transforms
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
- net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SaddleLayer
- net.minecraft.client.renderer.entity.layers.SheepWoolLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer$1
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$AlphaFunction
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$DrawSelector
- net.minecraft.client.renderer.entity.layers.WitchItemLayer
+ net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.layers.WolfArmorLayer
+ net.minecraft.client.renderer.entity.layers.WolfCollarLayer
+ net.minecraft.client.renderer.entity.package-info
- net.minecraft.client.renderer.entity.PaintingRenderer$1
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer$1
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer$1
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnifferRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.state.AllayRenderState
- net.minecraft.client.renderer.entity.state.ArmorStandRenderState
- net.minecraft.client.renderer.entity.state.AxolotlRenderState
- net.minecraft.client.renderer.entity.state.BeeRenderState
- net.minecraft.client.renderer.entity.state.BoatRenderState
- net.minecraft.client.renderer.entity.state.BreezeRenderState
- net.minecraft.client.renderer.entity.state.CatRenderState
- net.minecraft.client.renderer.entity.state.CreeperRenderState
- net.minecraft.client.renderer.entity.state.DolphinRenderState
- net.minecraft.client.renderer.entity.state.EndCrystalRenderState
- net.minecraft.client.renderer.entity.state.EndermanRenderState
- net.minecraft.client.renderer.entity.state.EntityRenderState$LeashState
- net.minecraft.client.renderer.entity.state.EvokerFangsRenderState
- net.minecraft.client.renderer.entity.state.ExperienceOrbRenderState
- net.minecraft.client.renderer.entity.state.FelineRenderState
- net.minecraft.client.renderer.entity.state.FishingHookRenderState
- net.minecraft.client.renderer.entity.state.FrogRenderState
- net.minecraft.client.renderer.entity.state.GoatRenderState
- net.minecraft.client.renderer.entity.state.HoglinRenderState
- net.minecraft.client.renderer.entity.state.HumanoidRenderState
- net.minecraft.client.renderer.entity.state.IllusionerRenderState
- net.minecraft.client.renderer.entity.state.ItemDisplayEntityRenderState
- net.minecraft.client.renderer.entity.state.ItemFrameRenderState
- net.minecraft.client.renderer.entity.state.LivingEntityRenderState
- net.minecraft.client.renderer.entity.state.LlamaSpitRenderState
- net.minecraft.client.renderer.entity.state.MinecartTntRenderState
- net.minecraft.client.renderer.entity.state.OminousItemSpawnerRenderState
- net.minecraft.client.renderer.entity.state.PandaRenderState
- net.minecraft.client.renderer.entity.state.PhantomRenderState
- net.minecraft.client.renderer.entity.state.PiglinRenderState
- net.minecraft.client.renderer.entity.state.PlayerRenderState$HandState
- net.minecraft.client.renderer.entity.state.PufferfishRenderState
- net.minecraft.client.renderer.entity.state.RavagerRenderState
- net.minecraft.client.renderer.entity.state.SalmonRenderState
- net.minecraft.client.renderer.entity.state.ShulkerBulletRenderState
- net.minecraft.client.renderer.entity.state.SkeletonRenderState
- net.minecraft.client.renderer.entity.state.SnifferRenderState
- net.minecraft.client.renderer.entity.state.StriderRenderState
- net.minecraft.client.renderer.entity.state.ThrownItemRenderState
- net.minecraft.client.renderer.entity.state.TippableArrowRenderState
- net.minecraft.client.renderer.entity.state.TropicalFishRenderState
- net.minecraft.client.renderer.entity.state.VexRenderState
- net.minecraft.client.renderer.entity.state.VillagerRenderState
- net.minecraft.client.renderer.entity.state.WitchRenderState
- net.minecraft.client.renderer.entity.state.WitherSkullRenderState
- net.minecraft.client.renderer.entity.state.ZombieRenderState
- net.minecraft.client.renderer.entity.state.ZombifiedPiglinRenderState
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.TadpoleRenderer
+ net.minecraft.client.renderer.entity.ThrownItemRenderer
- net.minecraft.client.renderer.entity.ThrownTridentRenderer
+ net.minecraft.client.renderer.entity.TippableArrowRenderer
- net.minecraft.client.renderer.entity.TntMinecartRenderer
+ net.minecraft.client.renderer.entity.TntRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer$1
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WardenRenderer
- net.minecraft.client.renderer.entity.WindChargeRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogParameters
- net.minecraft.client.renderer.item.ClampedItemPropertyFunction
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction
- net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassTarget
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassWobble
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$1
- net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostChain$TargetBundle
- net.minecraft.client.renderer.PostChainConfig
- net.minecraft.client.renderer.PostChainConfig$FullScreenTarget
- net.minecraft.client.renderer.PostChainConfig$InternalTarget
- net.minecraft.client.renderer.PostChainConfig$TargetInput
- net.minecraft.client.renderer.PostChainConfig$Uniform
- net.minecraft.client.renderer.PostPass$Input
- net.minecraft.client.renderer.PostPass$TextureInput
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$ColorLogicStateShard
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
+ net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
- net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
+ net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$OutputStateShard
- net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
+ net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
+ net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
- net.minecraft.client.renderer.RenderType
+ net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.RenderType$OutlineProperty
+ net.minecraft.client.renderer.RunningTrimmedMean
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.SectionBufferBuilderPack
- net.minecraft.client.renderer.SectionBufferBuilderPool
+ net.minecraft.client.renderer.SectionOcclusionGraph
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphEvents
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphState
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphStorage
+ net.minecraft.client.renderer.SectionOcclusionGraph$Node
- net.minecraft.client.renderer.SectionOcclusionGraph$SectionToNodeMap
+ net.minecraft.client.renderer.ShaderInstance
- net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.ShapeRenderer$1
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.state.MapRenderState$MapDecorationRenderState
- net.minecraft.client.renderer.WeatherEffectRenderer$ColumnInstance
- net.minecraft.client.resources.MapTextureManager$MapInstance
+ net.minecraft.client.resources.model.BlockStateModelLoader$BlockStateDefinitionException
- net.minecraft.client.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
+ net.minecraft.client.resources.model.BlockStateModelLoader$LoadedModel
- net.minecraft.client.resources.model.BlockStateModelLoader$LoadedModels
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelDiscovery$ResolverImpl
- net.minecraft.client.resources.model.ModelGroupCollector$GroupKey
+ net.minecraft.client.resources.model.package-info
- net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.UnbakedModel$Resolver
+ net.minecraft.client.resources.model.WeightedBakedModel
- net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.package-info
+ net.minecraft.client.resources.server.DownloadedPackSource
- net.minecraft.client.resources.server.DownloadedPackSource$1
+ net.minecraft.client.resources.server.DownloadedPackSource$2
- net.minecraft.client.resources.server.DownloadedPackSource$3
+ net.minecraft.client.resources.server.DownloadedPackSource$4
- net.minecraft.client.resources.server.DownloadedPackSource$5
+ net.minecraft.client.resources.server.DownloadedPackSource$6
- net.minecraft.client.resources.server.DownloadedPackSource$7
+ net.minecraft.client.resources.server.DownloadedPackSource$8
- net.minecraft.client.resources.server.package-info
- net.minecraft.client.resources.server.PackDownloader
+ net.minecraft.client.resources.server.PackLoadFeedback
- net.minecraft.client.resources.server.PackLoadFeedback$FinalResult
+ net.minecraft.client.resources.server.PackLoadFeedback$Update
- net.minecraft.client.resources.server.PackReloadConfig
+ net.minecraft.client.resources.server.PackReloadConfig$Callbacks
- net.minecraft.client.resources.server.PackReloadConfig$IdAndPath
+ net.minecraft.client.resources.server.ServerPackManager
- net.minecraft.client.resources.server.ServerPackManager$1
+ net.minecraft.client.resources.server.ServerPackManager$ActivationStatus
- net.minecraft.client.resources.server.ServerPackManager$PackDownloadStatus
+ net.minecraft.client.resources.server.ServerPackManager$PackPromptStatus
- net.minecraft.client.resources.server.ServerPackManager$RemovalReason
+ net.minecraft.client.resources.server.ServerPackManager$ServerPackData
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
+ net.minecraft.client.searchtree.FullTextSearchTree
- net.minecraft.client.searchtree.IdSearchTree
+ net.minecraft.client.searchtree.IntersectionIterator
- net.minecraft.client.searchtree.MergingUniqueIterator
- net.minecraft.client.searchtree.package-info
+ net.minecraft.client.searchtree.ResourceLocationSearchTree
- net.minecraft.client.searchtree.ResourceLocationSearchTree$1
+ net.minecraft.client.searchtree.ResourceLocationSearchTree$2
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
- net.minecraft.client.sounds.ChunkedSampleByteBuf
+ net.minecraft.client.sounds.FiniteAudioStream
- net.minecraft.client.sounds.FloatSampleSource
+ net.minecraft.client.sounds.JOrbisAudioStream
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
- net.minecraft.client.StringSplitter
+ net.minecraft.client.StringSplitter$1
- net.minecraft.client.StringSplitter$FlatComponents
+ net.minecraft.client.StringSplitter$LineBreakFinder
- net.minecraft.client.StringSplitter$LineComponent
+ net.minecraft.client.StringSplitter$LinePosConsumer
- net.minecraft.client.StringSplitter$WidthLimitedCharSink
+ net.minecraft.client.StringSplitter$WidthProvider
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
- net.minecraft.client.ToggleKeyMapping
+ net.minecraft.client.tutorial.BundleTutorial
- net.minecraft.client.tutorial.package-info
+ net.minecraft.client.tutorial.Tutorial$TimedToast
- net.minecraft.client.tutorial.TutorialStepInstance
+ net.minecraft.client.tutorial.TutorialSteps
+ net.minecraft.client.User
- net.minecraft.client.User$Type
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
+ net.minecraft.commands.arguments.item.ComponentPredicateParser
- net.minecraft.commands.arguments.item.ComponentPredicateParser$ComponentLookupRule
+ net.minecraft.commands.arguments.item.ComponentPredicateParser$Context
- net.minecraft.commands.arguments.item.ComponentPredicateParser$ElementLookupRule
+ net.minecraft.commands.arguments.item.ComponentPredicateParser$PredicateLookupRule
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
+ net.minecraft.commands.arguments.item.ItemParser$SuggestionsVisitor
- net.minecraft.commands.arguments.item.ItemParser$Visitor
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ComponentWrapper
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Context
- net.minecraft.commands.arguments.item.ItemPredicateArgument$PredicateWrapper
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
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
+ net.minecraft.commands.arguments.ResourceOrIdArgument$LootModifierArgument
- net.minecraft.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
+ net.minecraft.commands.arguments.ResourceOrIdArgument$LootTableArgument
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
- net.minecraft.commands.ExecutionCommandSource
+ net.minecraft.commands.FunctionInstantiationException
- net.minecraft.commands.ParserUtils
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.cauldron.CauldronInteraction$InteractionMap
+ net.minecraft.core.cauldron.package-info
- net.minecraft.core.component.DataComponentHolder
+ net.minecraft.core.component.DataComponentMap
- net.minecraft.core.component.DataComponentMap$1
+ net.minecraft.core.component.DataComponentMap$2
- net.minecraft.core.component.DataComponentMap$3
+ net.minecraft.core.component.DataComponentMap$Builder
- net.minecraft.core.component.DataComponentMap$Builder$SimpleMap
+ net.minecraft.core.component.DataComponentPatch
- net.minecraft.core.component.DataComponentPatch$1
+ net.minecraft.core.component.DataComponentPatch$Builder
- net.minecraft.core.component.DataComponentPatch$PatchKey
+ net.minecraft.core.component.DataComponentPatch$SplitResult
- net.minecraft.core.component.DataComponentPredicate
+ net.minecraft.core.component.DataComponentPredicate$Builder
+ net.minecraft.core.component.DataComponents
- net.minecraft.core.component.DataComponentType
+ net.minecraft.core.component.DataComponentType$Builder
- net.minecraft.core.component.DataComponentType$Builder$SimpleType
+ net.minecraft.core.component.package-info
- net.minecraft.core.component.PatchedDataComponentMap
+ net.minecraft.core.component.TypedDataComponent
- net.minecraft.core.component.TypedDataComponent$1
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
- net.minecraft.core.dispenser.DispenseItemBehavior$2
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ProjectileDispenseBehavior
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.MappedRegistry$3
- net.minecraft.core.MappedRegistry$TagSet
- net.minecraft.core.MappedRegistry$TagSet$2
+ net.minecraft.core.NonNullList
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.ColorParticleOption
- net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleGroup
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.ScalableParticleOptionsBase
+ net.minecraft.core.particles.SculkChargeParticleOptions
- net.minecraft.core.particles.ShriekParticleOption
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.Position
+ net.minecraft.core.QuartPos
- net.minecraft.core.RegistrationInfo
- net.minecraft.core.registries.BuiltInRegistries
+ net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
+ net.minecraft.core.registries.package-info
- net.minecraft.core.registries.Registries
+ net.minecraft.core.Registry
- net.minecraft.core.Registry$1
+ net.minecraft.core.Registry$2
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$1
- net.minecraft.core.RegistryAccess$1FrozenAccess
+ net.minecraft.core.RegistryAccess$Frozen
- net.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryEntry
- net.minecraft.core.RegistryCodecs
+ net.minecraft.core.RegistrySetBuilder
- net.minecraft.core.RegistrySetBuilder$1
+ net.minecraft.core.RegistrySetBuilder$1Entry
- net.minecraft.core.RegistrySetBuilder$2
+ net.minecraft.core.RegistrySetBuilder$3
- net.minecraft.core.RegistrySetBuilder$3$1
+ net.minecraft.core.RegistrySetBuilder$BuildState
- net.minecraft.core.RegistrySetBuilder$BuildState$1
+ net.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- net.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
+ net.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
- net.minecraft.core.RegistrySetBuilder$LazyHolder
+ net.minecraft.core.RegistrySetBuilder$PatchedRegistries
- net.minecraft.core.RegistrySetBuilder$RegisteredValue
+ net.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- net.minecraft.core.RegistrySetBuilder$RegistryContents
+ net.minecraft.core.RegistrySetBuilder$RegistryStub
- net.minecraft.core.RegistrySetBuilder$UniversalLookup
+ net.minecraft.core.RegistrySetBuilder$UniversalOwner
- net.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ net.minecraft.core.RegistrySynchronization
- net.minecraft.core.RegistrySynchronization$PackedRegistryEntry
+ net.minecraft.core.Rotations
- net.minecraft.core.Rotations$1
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.UUIDUtil
- net.minecraft.core.UUIDUtil$1
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdvancementSubProvider
- net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.packs.package-info
+ net.minecraft.data.advancements.packs.VanillaAdvancementProvider
- net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaNetherAdvancements
+ net.minecraft.data.advancements.packs.VanillaStoryAdvancements
- net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
+ net.minecraft.data.BlockFamily$Variant
- net.minecraft.data.CachedOutput
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataGenerator$PackGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.DataProvider$Factory
+ net.minecraft.data.HashCache
- net.minecraft.data.HashCache$1
+ net.minecraft.data.HashCache$CacheUpdater
- net.minecraft.data.HashCache$ProviderCache
+ net.minecraft.data.HashCache$ProviderCacheBuilder
- net.minecraft.data.HashCache$UpdateFunction
+ net.minecraft.data.HashCache$UpdateResult
- net.minecraft.data.info.BiomeParametersDumpReport
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.DatapackStructureReport$CustomPackEntry
- net.minecraft.data.info.DatapackStructureReport$Format
- net.minecraft.data.loot.packs.LootData
+ net.minecraft.data.loot.packs.package-info
+ net.minecraft.data.loot.packs.TradeRebalanceChestLoot
- net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
+ net.minecraft.data.loot.packs.VanillaArchaeologyLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaEquipmentLoot
- net.minecraft.data.loot.packs.VanillaFishingLoot
+ net.minecraft.data.loot.packs.VanillaGiftLoot
- net.minecraft.data.loot.packs.VanillaLootTableProvider
+ net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
- net.minecraft.data.loot.packs.VanillaShearingLoot
- net.minecraft.data.Main
+ net.minecraft.data.metadata.package-info
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$C1
- net.minecraft.data.models.blockstates.PropertyDispatch$C2
+ net.minecraft.data.models.blockstates.PropertyDispatch$C3
- net.minecraft.data.models.blockstates.PropertyDispatch$C4
+ net.minecraft.data.models.blockstates.PropertyDispatch$C5
- net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.ItemModelGenerators$TrimModelData
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplate$JsonFactory
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
+ net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$PathProvider
+ net.minecraft.data.PackOutput$Target
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider
+ net.minecraft.data.recipes.packs.package-info
- net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeBuilder$1
- net.minecraft.data.recipes.RecipeCategory
+ net.minecraft.data.recipes.RecipeOutput
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.RecipeProvider$1
- net.minecraft.data.recipes.RecipeProvider$Runner
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SmithingTransformRecipeBuilder
+ net.minecraft.data.recipes.SmithingTrimRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.registries.package-info
- net.minecraft.data.registries.RegistriesDatapackGenerator
+ net.minecraft.data.registries.RegistryPatchGenerator
- net.minecraft.data.registries.TradeRebalanceRegistries
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
+ net.minecraft.data.tags.EnchantmentTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.InstrumentTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.PaintingVariantTagsProvider
+ net.minecraft.data.tags.PoiTypeTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1CombinedData
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.TagsProvider$TagLookup
+ net.minecraft.data.tags.TradeRebalanceEnchantmentTagsProvider
- net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
+ net.minecraft.data.tags.VanillaBlockTagsProvider
- net.minecraft.data.tags.VanillaEnchantmentTagsProvider
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
+ net.minecraft.data.worldgen.VillagePools
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
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
- net.minecraft.gametest.framework.GameTestHelper$3
- net.minecraft.locale.DeprecatedTranslationsInfo
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.MethodsReturnNonnullByDefault
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
- net.minecraft.network.chat.ChatDecorator
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ChatType$Bound
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.Component$SerializerAdapter
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$Type
- net.minecraft.network.chat.ComponentSerialization
+ net.minecraft.network.chat.ComponentSerialization$1
- net.minecraft.network.chat.ComponentSerialization$FuzzyCodec
+ net.minecraft.network.chat.ComponentSerialization$StrictEither
- net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.BlockDataSource
+ net.minecraft.network.chat.contents.DataSource
- net.minecraft.network.chat.contents.DataSource$Type
+ net.minecraft.network.chat.contents.EntityDataSource
- net.minecraft.network.chat.contents.KeybindContents
+ net.minecraft.network.chat.contents.KeybindResolver
- net.minecraft.network.chat.contents.NbtContents
+ net.minecraft.network.chat.contents.package-info
+ net.minecraft.network.chat.contents.PlainTextContents
- net.minecraft.network.chat.contents.PlainTextContents$1
+ net.minecraft.network.chat.contents.PlainTextContents$LiteralContents
- net.minecraft.network.chat.contents.ScoreContents
+ net.minecraft.network.chat.contents.SelectorContents
- net.minecraft.network.chat.contents.StorageDataSource
+ net.minecraft.network.chat.contents.TranslatableContents
- net.minecraft.network.chat.contents.TranslatableFormatException
+ net.minecraft.network.chat.FilterMask
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
- net.minecraft.network.chat.numbers.BlankFormat
+ net.minecraft.network.chat.numbers.BlankFormat$1
- net.minecraft.network.chat.numbers.FixedFormat
+ net.minecraft.network.chat.numbers.FixedFormat$1
- net.minecraft.network.chat.numbers.NumberFormat
+ net.minecraft.network.chat.numbers.NumberFormatType
- net.minecraft.network.chat.numbers.NumberFormatTypes
+ net.minecraft.network.chat.numbers.package-info
+ net.minecraft.network.chat.numbers.StyledFormat
- net.minecraft.network.chat.numbers.StyledFormat$1
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$1
+ net.minecraft.network.chat.SignedMessageChain$DecodeException
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator
- net.minecraft.network.chat.SignedMessageValidator$KeyBased
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$1Collector
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.ClientboundPacketListener
+ net.minecraft.network.codec.ByteBufCodecs
- net.minecraft.network.codec.ByteBufCodecs$1
+ net.minecraft.network.codec.ByteBufCodecs$10
- net.minecraft.network.codec.ByteBufCodecs$11
+ net.minecraft.network.codec.ByteBufCodecs$12
- net.minecraft.network.codec.ByteBufCodecs$13
+ net.minecraft.network.codec.ByteBufCodecs$14
- net.minecraft.network.codec.ByteBufCodecs$15
+ net.minecraft.network.codec.ByteBufCodecs$16
- net.minecraft.network.codec.ByteBufCodecs$17
+ net.minecraft.network.codec.ByteBufCodecs$18
- net.minecraft.network.codec.ByteBufCodecs$19
+ net.minecraft.network.codec.ByteBufCodecs$2
- net.minecraft.network.codec.ByteBufCodecs$20
+ net.minecraft.network.codec.ByteBufCodecs$21
- net.minecraft.network.codec.ByteBufCodecs$22
+ net.minecraft.network.codec.ByteBufCodecs$23
- net.minecraft.network.codec.ByteBufCodecs$24
+ net.minecraft.network.codec.ByteBufCodecs$25
- net.minecraft.network.codec.ByteBufCodecs$26
+ net.minecraft.network.codec.ByteBufCodecs$27
- net.minecraft.network.codec.ByteBufCodecs$28
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$3
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.DisconnectionDetails
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.HandlerNames
- net.minecraft.network.MonitorFrameDecoder
+ net.minecraft.network.NoOpFrameDecoder
- net.minecraft.network.NoOpFrameEncoder
+ net.minecraft.network.PacketBundlePacker
- net.minecraft.network.PacketBundleUnpacker
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.PacketSendListener
+ net.minecraft.network.PacketSendListener$1
- net.minecraft.network.PacketSendListener$2
- net.minecraft.network.protocol.common.custom.RedstoneWireOrientationsDebugPayload
- net.minecraft.network.protocol.game.ClientboundMoveMinecartPacket
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
- net.minecraft.network.protocol.game.ClientboundProjectilePowerPacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResetScorePacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundServerDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCursorItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerInventoryPacket
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
- net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundSystemChatPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTickingStatePacket
- net.minecraft.network.protocol.game.ClientboundTickingStepPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.GamePacketTypes
- net.minecraft.network.protocol.game.GameProtocols
- net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQueryPacket
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatAckPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandPacket
- net.minecraft.network.protocol.game.ServerboundChatCommandSignedPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientTickEndPacket
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
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
+ net.minecraft.network.protocol.game.VecDeltaCodec
+ net.minecraft.network.protocol.handshake.ClientIntent
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.HandshakePacketTypes
- net.minecraft.network.protocol.handshake.HandshakeProtocols
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.CustomQueryPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
- net.minecraft.network.protocol.login.custom.package-info
+ net.minecraft.network.protocol.login.LoginPacketTypes
- net.minecraft.network.protocol.login.LoginProtocols
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.ping.ClientPongPacketListener
- net.minecraft.network.protocol.ping.package-info
+ net.minecraft.network.protocol.ping.PingPacketTypes
+ net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
- net.minecraft.network.protocol.ping.ServerPingPacketListener
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Favicon
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.protocol.status.StatusPacketTypes
- net.minecraft.network.protocol.status.StatusProtocols
+ net.minecraft.network.ProtocolInfo
- net.minecraft.network.ProtocolInfo$Unbound
+ net.minecraft.network.ProtocolInfo$Unbound$PacketVisitor
- net.minecraft.network.ProtocolSwapHandler
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.RegistryFriendlyByteBuf
+ net.minecraft.network.ServerboundPacketListener
- net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SyncedDataHolder
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$Builder
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
+ net.minecraft.network.TickablePacketListener
- net.minecraft.network.UnconfiguredPipelineHandler
+ net.minecraft.network.UnconfiguredPipelineHandler$Inbound
- net.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ net.minecraft.network.UnconfiguredPipelineHandler$Outbound
- net.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ net.minecraft.network.Utf8String
- net.minecraft.network.VarInt
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.network.VarLong
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
+ net.minecraft.Optionull
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipeHelper
+ net.minecraft.references.Blocks
- net.minecraft.references.Items
+ net.minecraft.ReportedException
- net.minecraft.ReportType
- net.minecraft.ResourceLocationException
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
+ net.minecraft.resources.RegistryDataLoader$LoadingFunction
- net.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.network.config.JoinWorldTask
- net.minecraft.server.network.config.package-info
- net.minecraft.server.network.config.ServerResourcePackConfigurationTask
+ net.minecraft.server.network.config.SynchronizeRegistriesTask
- net.minecraft.server.network.LegacyTextFilter
- net.minecraft.server.network.LegacyTextFilter$JoinOrLeaveEncoder
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
- net.minecraft.server.network.PlayerChunkSender
- net.minecraft.server.network.ServerTextFilter
- net.minecraft.server.network.ServerTextFilter$MessageEncoder
- net.minecraft.server.network.ServerTextFilter$RequestFailedException
+ net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilter$1
+ net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$PlayerContext
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
+ net.minecraft.server.ReloadableServerRegistries$Holder
- net.minecraft.server.ReloadableServerRegistries$LoadResult
+ net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ net.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerInfo
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerLinks
+ net.minecraft.server.ServerLinks$Entry
- net.minecraft.server.ServerLinks$KnownLinkType
+ net.minecraft.server.ServerLinks$UntrustedEntry
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.ServerTickRateManager
+ net.minecraft.server.Services
- net.minecraft.server.SuppressedExceptionCollector
- net.minecraft.server.SuppressedExceptionCollector$ShortEntry
+ net.minecraft.SharedConstants
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
- net.minecraft.SystemReport
+ net.minecraft.tags.BannerPatternTags
- net.minecraft.tags.BiomeTags
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.CatVariantTags
+ net.minecraft.tags.DamageTypeTags
- net.minecraft.tags.EnchantmentTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FlatLevelGeneratorPresetTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.InstrumentTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.PaintingVariantTags
- net.minecraft.tags.PoiTypeTags
+ net.minecraft.tags.StructureTags
- net.minecraft.tags.TagBuilder
+ net.minecraft.tags.TagEntry
- net.minecraft.tags.TagEntry$Lookup
+ net.minecraft.tags.TagFile
- net.minecraft.tags.TagKey
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagLoader$1
+ net.minecraft.tags.TagLoader$EntryWithSource
- net.minecraft.tags.TagLoader$LoadResult
+ net.minecraft.tags.TagManager
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.tags.WorldPresetTags
+ net.minecraft.Util
- net.minecraft.util.ARGB
- net.minecraft.util.BinaryAnimator
- net.minecraft.util.datafix.fixes.AttributeModifierIdFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.AttributesRenameLegacy
- net.minecraft.util.datafix.fixes.CarvingStepRemoveFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
+ net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- net.minecraft.util.datafix.fixes.ChunkDeleteLightFix
+ net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsMenuBlurrinessFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.ParticleUnflatteningFix
+ net.minecraft.util.datafix.fixes.PlayerHeadBlockProfileFix
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
+ net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
- net.minecraft.util.datafix.fixes.ProjectileStoredWeaponFix
+ net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.References$1
+ net.minecraft.util.datafix.fixes.RemapChunkStatusFix
- net.minecraft.util.datafix.fixes.RemoveEmptyItemInBrushableBlockFix
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
- net.minecraft.util.datafix.fixes.TrialSpawnerConfigFix
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
+ net.minecraft.util.datafix.schemas.package-info
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
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.datafix.schemas.V2568
- net.minecraft.util.datafix.schemas.V2571
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
+ net.minecraft.util.datafix.schemas.V3325
- net.minecraft.util.datafix.schemas.V3326
+ net.minecraft.util.datafix.schemas.V3327
- net.minecraft.util.datafix.schemas.V3328
+ net.minecraft.util.datafix.schemas.V3438
- net.minecraft.util.datafix.schemas.V3448
+ net.minecraft.util.datafix.schemas.V3682
- net.minecraft.util.datafix.schemas.V3683
+ net.minecraft.util.datafix.schemas.V3685
- net.minecraft.util.datafix.schemas.V3689
+ net.minecraft.util.datafix.schemas.V3799
- net.minecraft.util.datafix.schemas.V3807
+ net.minecraft.util.datafix.schemas.V3808
- net.minecraft.util.datafix.schemas.V3808_1
+ net.minecraft.util.datafix.schemas.V3808_2
- net.minecraft.util.datafix.schemas.V3816
+ net.minecraft.util.datafix.schemas.V3818
- net.minecraft.util.datafix.schemas.V3818_3
+ net.minecraft.util.datafix.schemas.V3818_4
- net.minecraft.util.datafix.schemas.V3818_5
+ net.minecraft.util.datafix.schemas.V3825
- net.minecraft.util.datafix.schemas.V3938
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.debugchart.AbstractSampleLogger
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- net.minecraft.util.debugchart.LocalSampleLogger
+ net.minecraft.util.debugchart.RemoteDebugSampleType
- net.minecraft.util.debugchart.RemoteSampleLogger
+ net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.debugchart.SampleStorage
+ net.minecraft.util.debugchart.TpsDebugDimensions
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.FastColor
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FileZipper
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FutureChain
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.HttpUtil$DownloadProgressListener
- net.minecraft.util.InclusiveRange
+ net.minecraft.util.KeyDispatchDataCodec
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.ListAndDeque
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.ModCheck
+ net.minecraft.util.ModCheck$Confidence
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.NullOps
+ net.minecraft.util.NullOps$NullMapBuilder
- net.minecraft.util.OptionEnum
- net.minecraft.util.package-info
+ net.minecraft.util.parsing.package-info
- net.minecraft.util.parsing.packrat.Atom
+ net.minecraft.util.parsing.packrat.commands.Grammar
- net.minecraft.util.parsing.packrat.commands.package-info
- net.minecraft.util.parsing.packrat.commands.ResourceLocationParseRule
+ net.minecraft.util.parsing.packrat.commands.ResourceLookupRule
- net.minecraft.util.parsing.packrat.commands.ResourceSuggestion
+ net.minecraft.util.parsing.packrat.commands.StringReaderParserState
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms
+ net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalCharacter
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalWord
+ net.minecraft.util.parsing.packrat.commands.TagParseRule
+ net.minecraft.util.parsing.packrat.Control
- net.minecraft.util.parsing.packrat.Dictionary
+ net.minecraft.util.parsing.packrat.ErrorCollector
- net.minecraft.util.parsing.packrat.ErrorCollector$LongestOnly
+ net.minecraft.util.parsing.packrat.ErrorEntry
+ net.minecraft.util.parsing.packrat.package-info
- net.minecraft.util.parsing.packrat.ParseState
+ net.minecraft.util.parsing.packrat.ParseState$CacheEntry
- net.minecraft.util.parsing.packrat.ParseState$CacheKey
+ net.minecraft.util.parsing.packrat.Rule
- net.minecraft.util.parsing.packrat.Rule$RuleAction
+ net.minecraft.util.parsing.packrat.Rule$SimpleRuleAction
- net.minecraft.util.parsing.packrat.Rule$WrappedTerm
+ net.minecraft.util.parsing.packrat.Scope
- net.minecraft.util.parsing.packrat.SuggestionSupplier
+ net.minecraft.util.parsing.packrat.Term
- net.minecraft.util.parsing.packrat.Term$1
+ net.minecraft.util.parsing.packrat.Term$2
- net.minecraft.util.parsing.packrat.Term$Alternative
+ net.minecraft.util.parsing.packrat.Term$Marker
- net.minecraft.util.parsing.packrat.Term$Maybe
+ net.minecraft.util.parsing.packrat.Term$Reference
- net.minecraft.util.parsing.packrat.Term$Sequence
+ net.minecraft.util.ParticleUtils
- net.minecraft.util.PngInfo
+ net.minecraft.util.ProblemReporter
- net.minecraft.util.ProblemReporter$Collector
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.ChunkIdentification
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.IoSummary
- net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.PacketIdentification
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.ProgressListener
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.RandomSource
+ net.minecraft.util.ResourceLocationPattern
- net.minecraft.util.SegmentedAnglePrecision
+ net.minecraft.util.SequencedPriorityIterator
- net.minecraft.util.SignatureUpdater
+ net.minecraft.util.SignatureUpdater$Output
- net.minecraft.util.SignatureValidator
+ net.minecraft.util.Signer
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SingleKeyCache
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.SpawnUtil
+ net.minecraft.util.SpawnUtil$Strategy
- net.minecraft.util.StaticCache2D
+ net.minecraft.util.StaticCache2D$Initializer
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$EnumCodec
- net.minecraft.util.StringRepresentable$StringRepresentableCodec
+ net.minecraft.util.StringUtil
- net.minecraft.util.TaskChainer
+ net.minecraft.util.TaskChainer$1
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeSource
- net.minecraft.util.TimeSource$NanoTimeSource
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.ToFloatFunction$1
- net.minecraft.util.ToFloatFunction$2
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- net.minecraft.Util$1
+ net.minecraft.Util$10
- net.minecraft.Util$11
+ net.minecraft.Util$2
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
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
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.BadOmenMobEffect
+ net.minecraft.world.effect.HealOrHarmMobEffect
- net.minecraft.world.effect.HungerMobEffect
+ net.minecraft.world.effect.InfestedMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$AttributeTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$BlendState
- net.minecraft.world.effect.MobEffectInstance$Details
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.OozingMobEffect
- net.minecraft.world.effect.OozingMobEffect$NearbySlimes
- net.minecraft.world.effect.package-info
+ net.minecraft.world.effect.PoisonMobEffect
- net.minecraft.world.effect.RaidOmenMobEffect
+ net.minecraft.world.effect.RegenerationMobEffect
- net.minecraft.world.effect.SaturationMobEffect
+ net.minecraft.world.effect.WeavingMobEffect
- net.minecraft.world.effect.WindChargedMobEffect
+ net.minecraft.world.effect.WitherMobEffect
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.village.poi.PoiRecord$Packed
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiSection$Packed
- net.minecraft.world.entity.animal.allay.Allay
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.Allay$VibrationUser
+ net.minecraft.world.entity.animal.allay.AllayAi
- net.minecraft.world.entity.animal.allay.package-info
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.armadillo.Armadillo
- net.minecraft.world.entity.animal.armadillo.Armadillo$1
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
- net.minecraft.world.entity.animal.axolotl.Axolotl$AnimationState
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
- net.minecraft.world.entity.animal.Bee$ValidateHiveGoal
+ net.minecraft.world.entity.animal.Bucketable
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
- net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
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
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Rabbit$Variant
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Salmon$Variant
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.ShoulderRidingEntity
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
- net.minecraft.world.entity.animal.WolfVariant
+ net.minecraft.world.entity.animal.WolfVariants
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
- net.minecraft.world.entity.boss.enderdragon.DragonFlightHistory$Sample
- net.minecraft.world.entity.Crackiness
+ net.minecraft.world.entity.Crackiness$Level
- net.minecraft.world.entity.Display
+ net.minecraft.world.entity.Display$BillboardConstraints
- net.minecraft.world.entity.Display$BlockDisplay
+ net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
- net.minecraft.world.entity.Display$ColorInterpolator
+ net.minecraft.world.entity.Display$FloatInterpolator
- net.minecraft.world.entity.Display$GenericInterpolator
+ net.minecraft.world.entity.Display$IntInterpolator
- net.minecraft.world.entity.Display$ItemDisplay
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
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.EquipmentSlotGroup
+ net.minecraft.world.entity.EquipmentSlotGroup$1
- net.minecraft.world.entity.EquipmentTable
+ net.minecraft.world.entity.EquipmentUser
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.Leashable
- net.minecraft.world.entity.Leashable$LeashData
+ net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OminousItemSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.StackedContents$Output
- net.minecraft.world.entity.player.StackedItemContents
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.PortalProcessor
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.Projectile$ProjectileFactory
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.ChestBoat
- net.minecraft.world.entity.vehicle.ChestBoat$1
+ net.minecraft.world.entity.vehicle.ContainerEntity
- net.minecraft.world.entity.vehicle.ContainerEntity$1
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.NewMinecartBehavior
- net.minecraft.world.entity.vehicle.NewMinecartBehavior$MinecartStep
- net.minecraft.world.entity.vehicle.NewMinecartBehavior$TrackIteration
- net.minecraft.world.entity.vehicle.OldMinecartBehavior$1
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.entity.vehicle.VehicleEntity
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
+ net.minecraft.world.food.FoodProperties$PossibleEffect
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResult$Fail
- net.minecraft.world.InteractionResult$Pass
- net.minecraft.world.InteractionResult$SwingSource
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractCraftingMenu
- net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.package-info
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
- net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Builder
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.PotionContents
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.AnimalArmorItem
+ net.minecraft.world.item.AnimalArmorItem$BodyType
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterial$Layer
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.armortrim.ArmorTrim
- net.minecraft.world.item.armortrim.package-info
- net.minecraft.world.item.armortrim.TrimMaterial
+ net.minecraft.world.item.armortrim.TrimMaterials
- net.minecraft.world.item.armortrim.TrimPattern
+ net.minecraft.world.item.armortrim.TrimPatterns
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BoneMealItem$1
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
+ net.minecraft.world.item.component.Tool
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
- net.minecraft.world.item.crafting.CraftingInput
+ net.minecraft.world.item.crafting.CraftingInput$Positioned
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.DecoratedPotRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.PlacementInfo$SlotInfo
+ net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.enchantment.ConditionalEffect
+ net.minecraft.world.item.enchantment.effects.AddValue
- net.minecraft.world.item.enchantment.effects.AllOf
+ net.minecraft.world.item.enchantment.effects.AllOf$EntityEffects
- net.minecraft.world.item.enchantment.effects.AllOf$LocationBasedEffects
+ net.minecraft.world.item.enchantment.effects.AllOf$ValueEffects
- net.minecraft.world.item.enchantment.effects.ApplyMobEffect
+ net.minecraft.world.item.enchantment.effects.DamageEntity
- net.minecraft.world.item.enchantment.effects.DamageImmunity
+ net.minecraft.world.item.enchantment.effects.DamageItem
- net.minecraft.world.item.enchantment.effects.EnchantmentAttributeEffect
+ net.minecraft.world.item.enchantment.effects.EnchantmentEntityEffect
- net.minecraft.world.item.enchantment.effects.EnchantmentLocationBasedEffect
+ net.minecraft.world.item.enchantment.effects.EnchantmentValueEffect
- net.minecraft.world.item.enchantment.effects.ExplodeEffect
+ net.minecraft.world.item.enchantment.effects.Ignite
- net.minecraft.world.item.enchantment.effects.MultiplyValue
- net.minecraft.world.item.enchantment.effects.package-info
+ net.minecraft.world.item.enchantment.effects.PlaySoundEffect
- net.minecraft.world.item.enchantment.effects.RemoveBinomial
+ net.minecraft.world.item.enchantment.effects.ReplaceBlock
- net.minecraft.world.item.enchantment.effects.ReplaceDisk
+ net.minecraft.world.item.enchantment.effects.RunFunction
- net.minecraft.world.item.enchantment.effects.SetBlockProperties
+ net.minecraft.world.item.enchantment.effects.SetValue
- net.minecraft.world.item.enchantment.effects.SpawnParticlesEffect
+ net.minecraft.world.item.enchantment.effects.SpawnParticlesEffect$PositionSource
- net.minecraft.world.item.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ net.minecraft.world.item.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- net.minecraft.world.item.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ net.minecraft.world.item.enchantment.effects.SummonEntityEffect
- net.minecraft.world.item.enchantment.Enchantable
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.providers.EnchantmentProvider
+ net.minecraft.world.item.enchantment.providers.EnchantmentProviderTypes
- net.minecraft.world.item.enchantment.providers.EnchantmentsByCost
+ net.minecraft.world.item.enchantment.providers.EnchantmentsByCostWithDifficulty
+ net.minecraft.world.item.enchantment.providers.package-info
- net.minecraft.world.item.enchantment.providers.SingleEnchantment
+ net.minecraft.world.item.enchantment.providers.TradeRebalanceEnchantmentProviders
- net.minecraft.world.item.enchantment.providers.VanillaEnchantmentProviders
- net.minecraft.world.item.enchantment.TargetedConditionalEffect
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
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.Item$TooltipContext
- net.minecraft.world.item.Item$TooltipContext$1
+ net.minecraft.world.item.Item$TooltipContext$2
- net.minecraft.world.item.Item$TooltipContext$3
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemDisplayContext
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$1
- net.minecraft.world.item.ItemStack$2
+ net.minecraft.world.item.ItemStack$3
- net.minecraft.world.item.ItemStack$4
+ net.minecraft.world.item.ItemStackLinkedSet
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.JukeboxPlayable
- net.minecraft.world.item.JukeboxSong
+ net.minecraft.world.item.JukeboxSongPlayer
- net.minecraft.world.item.JukeboxSongPlayer$OnSongChanged
+ net.minecraft.world.item.JukeboxSongs
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
+ net.minecraft.world.item.OminousBottleItem
- net.minecraft.world.item.package-info
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileItem
+ net.minecraft.world.item.ProjectileItem$DispenseConfig
- net.minecraft.world.item.ProjectileItem$DispenseConfig$Builder
+ net.minecraft.world.item.ProjectileItem$PositionFunction
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
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
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.ToolMaterial
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.trading.ItemCost
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.WindChargeItem
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.ItemInteractionResult
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.block.Block$ShapePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BlockTypes
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BonemealableBlock$Type
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BrushableBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CalibratedSculkSensorBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVines
+ net.minecraft.world.level.block.CaveVinesBlock
- net.minecraft.world.level.block.CaveVinesPlantBlock
+ net.minecraft.world.level.block.CeilingHangingSignBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeBlock
+ net.minecraft.world.level.block.CherryLeavesBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChiseledBookShelfBlock
+ net.minecraft.world.level.block.ChiseledBookShelfBlock$1
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.ColoredFallingBlock
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CopperBulbBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CrafterBlock
+ net.minecraft.world.level.block.CrafterBlock$1
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DecoratedPotBlock
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
- net.minecraft.world.level.block.EnchantingTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPatternLayers
- net.minecraft.world.level.block.entity.BannerPatternLayers$Builder
+ net.minecraft.world.level.block.entity.BannerPatternLayers$Layer
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
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$Occupant
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntity$1
+ net.minecraft.world.level.block.entity.BlockEntity$ComponentHelper
- net.minecraft.world.level.block.entity.BlockEntity$DataComponentInput
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.FuelValues
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrogspawnBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HeavyCoreBlock
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
- net.minecraft.world.level.block.Mirror
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
- net.minecraft.world.level.block.PiglinWallSkullBlock
+ net.minecraft.world.level.block.PinkPetalsBlock
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.PitcherCropBlock
- net.minecraft.world.level.block.PitcherCropBlock$PosAndState
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.Portal
- net.minecraft.world.level.block.Portal$Transition
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
- net.minecraft.world.level.block.SnifferEggBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SuspiciousEffectHolder
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TorchflowerCropBlock
- net.minecraft.world.level.block.TransparentBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TrialSpawnerBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VaultBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WaterloggedTransparentBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperBulbBlock
- net.minecraft.world.level.block.WeatheringCopperDoorBlock
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperGrateBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.chunk.storage.ChunkSerializer$ChunkReadException
- net.minecraft.world.level.chunk.storage.SerializableChunkData
- net.minecraft.world.level.chunk.storage.SerializableChunkData$SectionData
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
- net.minecraft.world.level.EmptyBlockAndTintGetter
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeCrackSettings
+ net.minecraft.world.level.levelgen.GeodeLayerSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$1
+ net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouter
+ net.minecraft.world.level.levelgen.NoiseRouterData
- net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
- net.minecraft.world.level.levelgen.placement.FixedPlacement
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
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.package-info
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.RandomState
+ net.minecraft.world.level.levelgen.RandomState$1
- net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuiltinStructures
+ net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
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
+ net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.pools.alias.Direct
- net.minecraft.world.level.levelgen.structure.pools.alias.package-info
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
- net.minecraft.world.level.levelgen.structure.pools.alias.Random
+ net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
- net.minecraft.world.level.levelgen.structure.pools.DimensionPadding
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
+ net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings$Builder
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.package-info
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.LiquidSettings
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
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
- net.minecraft.world.level.levelgen.SurfaceRules
+ net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
- net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$Condition
+ net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$Context
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Hole
- net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$StateRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Steep
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Temperature
- net.minecraft.world.level.levelgen.SurfaceRules$TestRule
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- net.minecraft.world.level.levelgen.SurfaceSystem
+ net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NoiseUtils
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
+ net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldDimensions
- net.minecraft.world.level.levelgen.WorldDimensions$1Entry
+ net.minecraft.world.level.levelgen.WorldDimensions$Complete
+ net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.WorldOptions
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
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
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.FlowingFluid$SpreadContext
- net.minecraft.world.level.redstone.DefaultRedstoneWireEvaluator
- net.minecraft.world.level.redstone.ExperimentalRedstoneWireEvaluator
+ net.minecraft.world.level.redstone.InstantNeighborUpdater
- net.minecraft.world.level.redstone.NeighborUpdater
- net.minecraft.world.level.redstone.Orientation$SideBias
+ net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.redstone.RedstoneWireEvaluator
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapDecorationLocation
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.ServerExplosion$StackCollector
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.FileNameDateFormatter
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelDataAndDimensions
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
- net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.ContainerComponentManipulator
+ net.minecraft.world.level.storage.loot.ContainerComponentManipulators
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$1
+ net.minecraft.world.level.storage.loot.ContainerComponentManipulators$2
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$3
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
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.EnchantedCountIncreaseFunction
- net.minecraft.world.level.storage.loot.functions.EnchantedCountIncreaseFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FilteredFunction
+ net.minecraft.world.level.storage.loot.functions.FunctionReference
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.ListOperation
+ net.minecraft.world.level.storage.loot.functions.ListOperation$Append
- net.minecraft.world.level.storage.loot.functions.ListOperation$Insert
+ net.minecraft.world.level.storage.loot.functions.ListOperation$ReplaceAll
- net.minecraft.world.level.storage.loot.functions.ListOperation$ReplaceSection
+ net.minecraft.world.level.storage.loot.functions.ListOperation$StandAlone
- net.minecraft.world.level.storage.loot.functions.ListOperation$Type
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.ModifyContainerContents
- net.minecraft.world.level.storage.loot.functions.package-info
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
- net.minecraft.world.level.storage.loot.functions.SetCustomModelDataFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetFireworkExplosionFunction
- net.minecraft.world.level.storage.loot.functions.SetFireworksFunction
+ net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Target
+ net.minecraft.world.level.storage.loot.functions.SetOminousBottleAmplifierFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
- net.minecraft.world.level.storage.loot.functions.SetWritableBookPagesFunction
+ net.minecraft.world.level.storage.loot.functions.SetWrittenBookPagesFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.ToggleTooltips
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips$ComponentToggle
+ net.minecraft.world.level.storage.loot.functions.ToggleTooltips$TooltipWither
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
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
- net.minecraft.world.level.storage.loot.predicates.EnchantmentActiveCheck
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
- net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.EnchantmentLevelProvider
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.StorageValue
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
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
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
- net.minecraft.WorldVersion
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.blaze3d.Blaze3D -2M
```
```
XXX.blaze3d.font.TrueTypeGlyphProvider +5M -1M | +1P -1P
```
```
XXX.blaze3d.pipeline.RenderTarget +3M -8M
```
```
XXX.blaze3d.platform.GlStateManager +1M -1M | +2P
```
```
XXX.minecraft.client.Minecraft$1 +2M -1M | +3P -1P
```
```
XXX.client.gui.GuiGraphics +13M -22M | -1P
```
```
XXX.components.debugchart.TpsDebugChart -3P
```
```
XXX.components.toasts.AdvancementToast +3M -1M | +1P
```
```
XXX.inventory.tooltip.ClientTooltipComponent +1M | +1P -1P
```
```
XXX.screens.options.AccessibilityOptionsScreen +1M
```
```
XXX.options.controls.KeyBindsList -1M
```
```
XXX.screens.recipebook.OverlayRecipeComponent +2M -2M | +1P -10P
```
```
XXX.client.model.ElytraModel +4M -4M | +2P
```
```
XXX.client.model.FrogModel +2M -2M
```
```
XXX.client.model.GiantZombieModel -2M
```
```
XXX.client.model.GuardianModel +3M -2M | +1P
```
```
XXX.client.model.LlamaSpitModel +1M -1M
```
```
XXX.client.model.Model +10M | +2P -1P
```
```
XXX.client.model.OcelotModel -5M | -30P
```
```
XXX.client.model.ParrotModel +6M -8M | -1P
```
```
XXX.client.model.PhantomModel +2M -2M
```
```
XXX.client.model.PiglinHeadModel +1M -1M
```
```
XXX.client.model.PlayerModel +6M -7M | +1P -5P
```
```
XXX.client.model.PufferfishBigModel +1M -1M
```
```
XXX.client.model.PufferfishSmallModel +1M -1M
```
```
XXX.client.model.RabbitModel +5M -9M | +3P -3P
```
```
XXX.client.model.RavagerModel +2M -4M
```
```
XXX.client.model.SheepFurModel +3M -4M | -1P
```
```
XXX.client.model.ShieldModel +1M -1M
```
```
XXX.client.model.ShulkerModel +5M -5M | +1P -1P
```
```
XXX.client.model.SkeletonModel +5M -6M
```
```
XXX.client.model.SnifferModel +3M -2M | +1P
```
```
XXX.client.model.SpiderModel +2M -1M
```
```
XXX.client.model.StriderModel +2M -2M
```
```
XXX.client.model.TridentModel +1M -1M
```
```
XXX.client.model.TropicalFishModelB +2M -1M
```
```
XXX.client.model.VexModel +3M -3M
```
```
XXX.client.model.VillagerModel +2M -1M | -1P
```
```
XXX.geom.builders.PartDefinition +4M
```
```
XXX.client.multiplayer.ClientLevel +9M -5M | +3P -1P
```
```
XXX.client.multiplayer.ClientLevel$ClientLevelData +1M -1M
```
```
XXX.client.multiplayer.ClientPacketListener +21M -15M | +3P -1P
```
```
XXX.client.multiplayer.MultiPlayerGameMode +2M -1M
```
```
XXX.client.multiplayer.PlayerInfo +2M | +1P
```
```
XXX.client.multiplayer.RegistryDataCollector$ContentsCollector -1M
```
```
XXX.client.player.AbstractClientPlayer +1M -1M | +2P
```
```
XXX.client.renderer.LightTexture +4M -2M | +4P -3P
```
```
XXX.block.model.BlockModelDefinition$Deserializer +1M -1M
```
```
XXX.block.model.FaceBakery +3M -3M
```
```
XXX.block.model.MultiVariant +5M -4M
```
```
XXX.model.multipart.AndCondition -2M
```
```
XXX.model.multipart.KeyValueCondition +1M -3M
```
```
XXX.model.multipart.MultiPart$Deserializer +2M -2M | -1P
```
```
XXX.renderer.entity.AllayRenderer +7M -2M
```
```
XXX.renderer.entity.ArmorStandRenderer +17M -9M | +2P
```
```
XXX.renderer.entity.AxolotlRenderer +7M -2M
```
```
XXX.renderer.entity.BeeRenderer +7M -2M
```
```
XXX.renderer.entity.BoatRenderer +10M -5M | +1P
```
```
XXX.renderer.entity.CodRenderer +5M -4M
```
```
XXX.renderer.entity.CreeperRenderer +11M -6M
```
```
XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer +11M -6M
```
```
XXX.renderer.entity.DolphinRenderer +7M -2M
```
```
XXX.renderer.entity.EndermiteRenderer +5M -4M
```
```
XXX.renderer.entity.EntityRenderer +11M -6M | +3P -1P
```
```
XXX.renderer.entity.EntityRendererProvider$Context +2M -2M | +1P -1P
```
```
XXX.renderer.entity.EvokerFangsRenderer +8M -4M
```
```
XXX.renderer.entity.EvokerRenderer$1 +4M -4M
```
```
XXX.renderer.entity.FallingBlockRenderer +10M -4M
```
```
XXX.renderer.entity.FishingHookRenderer +12M -4M
```
```
XXX.renderer.entity.FrogRenderer +7M -2M
```
```
XXX.renderer.entity.GiantMobRenderer +7M -4M | -1P
```
```
XXX.renderer.entity.GoatRenderer +7M -2M
```
```
XXX.renderer.entity.HoglinRenderer +8M -4M
```
```
XXX.renderer.entity.HumanoidMobRenderer +7M -1M
```
```
XXX.renderer.entity.IllagerRenderer +3M -2M
```
```
XXX.renderer.entity.IllusionerRenderer$1 +4M -4M
```
```
XXX.renderer.entity.ItemEntityRenderer +8M -4M
```
```
XXX.renderer.entity.ItemRenderer +5M
```
```
XXX.renderer.entity.LightningBoltRenderer +10M -4M
```
```
XXX.renderer.entity.MagmaCubeRenderer +12M -7M
```
```
XXX.renderer.entity.MobRenderer +5M -6M
```
```
XXX.renderer.entity.NoopRenderer +2M -1M
```
```
XXX.renderer.entity.OminousItemSpawnerRenderer +8M -4M
```
```
XXX.entity.layers.ArrowLayer +2M -3M | -1P
```
```
XXX.entity.layers.BreezeEyesLayer +2M -2M
```
```
XXX.entity.layers.CapeLayer +3M -3M | +1P
```
```
XXX.entity.layers.CatCollarLayer +2M -2M | +2P -1P
```
```
XXX.entity.layers.CrossedArmsItemLayer +3M -3M | +1P -1P
```
```
XXX.entity.layers.SlimeOuterLayer +2M -2M | +1P -1P
```
```
XXX.entity.layers.StuckInBodyLayer +5M -3M | +4P -2P
```
```
XXX.renderer.texture.AbstractTexture +1M | +1P -2P
```
```
XXX.renderer.texture.SimpleTexture +1M -1M
```
```
XXX.renderer.texture.SpriteContents$Ticker -1M
```
```
XXX.resources.model.ModelManager$ReloadState +2M -1M | +1P
```
```
XXX.resources.model.SimpleBakedModel$Builder +2P -2P
```
```
XXX.selector.options.EntitySelectorOptions +26M -24M
```
```
XXX.minecraft.core.Direction +8M -5M | +1P
```
```
XXX.minecraft.core.HolderLookup$Provider +2M | +1P -1P
```
```
XXX.minecraft.core.HolderLookup$Provider$2 +1M -1M
```
```
XXX.data.loot.BlockLootSubProvider +1M | -1P
```
```
XXX.recipes.packs.VanillaRecipeProvider +5M -5M
```
```
XXX.gametest.framework.StructureUtils +15M -13M
```
```
XXX.protocol.game.ClientGamePacketListener +4P -1P
```
```
XXX.protocol.game.ClientboundExplodePacket +8M -17M | +3P -11P
```
```
XXX.protocol.game.ServerboundMovePlayerPacket$Pos +1M -1M
```
```
XXX.protocol.game.ServerboundMovePlayerPacket$Rot +1M -1M
```
```
XXX.minecraft.recipebook.ServerPlaceRecipe +8M -7M | +6P -2P
```
```
XXX.minecraft.server.ReloadableServerRegistries +12M -10M
```
```
XXX.minecraft.server.WorldLoader -2M
```
```
XXX.server.commands.ScheduleCommand +2M -4M | +1P
```
```
XXX.server.commands.SetPlayerIdleTimeoutCommand +1M
```
```
XXX.server.dedicated.DedicatedServer +2M -3M | +1P -1P
```
```
XXX.server.dedicated.DedicatedServerProperties +1M -1M | +2P -2P
```
```
XXX.server.level.ChunkHolder +2M -2M
```
```
XXX.server.level.DistanceManager +8M -8M
```
```
XXX.server.level.TickingTracker +1M
```
```
XXX.server.network.ServerCommonPacketListenerImpl +1M
```
```
XXX.minecraft.tags.TagNetworkSerialization +3M -3M
```
```
XXX.util.datafix.ExtraDataFixUtils +11M -1M
```
```
XXX.datafix.fixes.EntityRenameFix +3M -2M
```
```
XXX.world.entity.Entity +12M -5M | +1P -4P
```
```
XXX.world.entity.LivingEntity +21M -10M | +2P -1P
```
```
XXX.world.entity.Mob +4M -3M | +1P
```
```
XXX.world.entity.TamableAnimal +1M -1M
```
```
XXX.ai.attributes.AttributeInstance +2M
```
```
XXX.ai.attributes.Attributes +1P
```
```
XXX.ai.goal.TemptGoal +1P -1P
```
```
XXX.ai.navigation.PathNavigation +3M | +1P
```
```
XXX.ai.sensing.Sensor +5M | +1P -1P
```
```
XXX.ai.sensing.TemptingSensor +1M -2M | -1P
```
```
XXX.animal.horse.AbstractHorse +1M -1M | +1P
```
```
XXX.animal.horse.Horse +1M -1M
```
```
XXX.animal.horse.Llama +1M -1M
```
```
XXX.animal.horse.ZombieHorse +1M -1M
```
```
XXX.boss.enderdragon.EnderDragon -2M | +1P -2P
```
```
XXX.boss.wither.WitherBoss +2M -2M
```
```
XXX.entity.decoration.PaintingVariant +3M -1M | +2P
```
```
XXX.entity.item.ItemEntity +2M -1M
```
```
XXX.entity.monster.AbstractIllager +1M -1M
```
```
XXX.entity.monster.CaveSpider +1M -1M
```
```
XXX.entity.monster.Endermite +1M -1M
```
```
XXX.entity.monster.Evoker +1M -1M
```
```
XXX.entity.monster.Illusioner +1M -2M
```
```
XXX.entity.monster.Monster +2M -2M
```
```
XXX.entity.monster.Shulker +2M -2M
```
```
XXX.entity.monster.Strider +2M -2M
```
```
XXX.entity.monster.Vindicator +1M -1M
```
```
XXX.entity.monster.WitherSkeleton +1M -1M
```
```
XXX.entity.monster.Zombie +2M -2M
```
```
XXX.entity.monster.ZombifiedPiglin +1M -1M
```
```
XXX.monster.breeze.LongJump +3P -1P
```
```
XXX.monster.piglin.PiglinBrute +1M -1M | +1P
```
```
XXX.entity.npc.Villager +1M -1M | -1P
```
```
XXX.entity.player.Inventory +5M -4M | -2P
```
```
XXX.entity.player.StackedContents +7M -12M | +1P -2P
```
```
XXX.entity.projectile.ThrowableProjectile -1M | +1P
```
```
XXX.entity.projectile.ThrownEnderpearl +2M -1M
```
```
XXX.entity.projectile.ThrownPotion +2M -2M
```
```
XXX.projectile.windcharge.WindCharge +1M | +1P
```
```
XXX.entity.vehicle.MinecartHopper +2M | +1P
```
```
XXX.world.inventory.AnvilMenu +1P
```
```
XXX.world.inventory.ChestMenu +1M | -1P
```
```
XXX.world.inventory.CraftingMenu +3M -8M | +3P -2P
```
```
XXX.world.inventory.InventoryMenu +3M -8M | +2P -2P
```
```
XXX.world.inventory.ItemCombinerMenu -1M | +1P -1P
```
```
XXX.world.inventory.RecipeBookMenu -3M | +2P -8P
```
```
XXX.world.item.BottleItem +1M -1M
```
```
XXX.world.item.BrushItem -1M
```
```
XXX.world.item.BundleItem +11M -3M | +7P -1P
```
```
XXX.world.item.CrossbowItem +1M -1M
```
```
XXX.world.item.EmptyMapItem +1M -1M
```
```
XXX.item.crafting.RecipeManager +7M -3M | +1P
```
```
XXX.item.crafting.ShapelessRecipe$Serializer +6M -10M
```
```
XXX.item.crafting.SingleItemRecipe +1M -1M | +1P
```
```
XXX.item.crafting.SmeltingRecipe +1M -1M
```
```
XXX.item.crafting.SmithingTransformRecipe$Serializer +7M -5M
```
```
XXX.item.crafting.SmithingTrimRecipe$Serializer +6M -5M
```
```
XXX.item.crafting.StonecutterRecipe +1M -1M
```
```
XXX.item.enchantment.EnchantmentHelper +3M -2M
```
```
XXX.world.level.Explosion +1M -25M | +7P -18P
```
```
XXX.world.level.ExplosionDamageCalculator +1M -1M
```
```
XXX.world.level.NaturalSpawner +2M -1M
```
```
XXX.world.level.NaturalSpawner$SpawnState +2M -1M
```
```
XXX.level.biome.BiomeGenerationSettings$Builder +1M -1M
```
```
XXX.level.block.AbstractCauldronBlock +1M -1M
```
```
XXX.level.block.AzaleaBlock +1M
```
```
XXX.level.block.BambooStalkBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +2M -1M
```
```
XXX.level.block.BellBlock +2M -2M
```
```
XXX.level.block.BigDripleafBlock +1M -1M
```
```
XXX.level.block.Block +3M -3M
```
```
XXX.block.entity.CrafterBlockEntity +1M -1M
```
```
XXX.block.entity.SmokerBlockEntity +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase$Cache -4P
```
```
XXX.block.state.StateHolder +2M
```
```
XXX.level.border.WorldBorder +2M
```
```
XXX.level.chunk.ChunkAccess +1M -2M | +1P -1P
```
```
XXX.level.chunk.ChunkGenerator +1P -1P
```
```
XXX.level.chunk.GlobalPalette +1M -1M
```
```
XXX.level.chunk.ImposterProtoChunk +3M -5M
```
```
XXX.level.chunk.PalettedContainer +1M
```
```
XXX.level.chunk.ProtoChunk +5M -6M | +1P -1P
```
```
XXX.chunk.storage.RecreatingChunkStorage +1M -1M
```
```
XXX.chunk.storage.SectionStorage +20M -13M | +7P -2P
```
```
XXX.level.dimension.DimensionDefaults +1P
```
```
XXX.level.entity.EntitySectionStorage +2P
```
```
XXX.level.levelgen.Aquifer$FluidStatus +5M
```
```
XXX.level.levelgen.DebugLevelSource +1M -1M
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M
```
```
XXX.levelgen.material.MaterialRuleList +2M -2M | +1P -1P
```
```
XXX.level.material.FluidState +1M -1M
```
```
XXX.level.material.MapColor +1M -1M
```
```
XXX.level.pathfinder.PathFinder +1M
```
```
XXX.level.redstone.CollectingNeighborUpdater +3M -3M
```
```
XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate +1M -1M | +1P
```
```
XXX.level.saveddata.SavedData +1M -2M | -1P
```
```
XXX.saveddata.maps.MapItemSavedData +6M
```
```
XXX.phys.shapes.EntityCollisionContext +2M -1M
```
```
XXX.phys.shapes.Shapes -1M
```
```
XXX.phys.shapes.VoxelShape +2M
```
```
XXX.world.ticks.LevelChunkTicks +1M -1M
```
```
XXX.world.ticks.ProtoChunkTicks +2M -2M
```

</details>
<details>
<summary>
com.mojang.blaze3d.Blaze3D
</summary>

```diff
+ void process(RenderPipeline,float)
+ void render(RenderPipeline,float)
```

</details>










<details>
<summary>
com.mojang.blaze3d.font.TrueTypeGlyphProvider
</summary>

```diff
+ float lambda$getGlyph$0(float)
- float lambda$loadGlyph$2(float)
- GlyphInfo getOrLoadGlyphInfo(int,TrueTypeGlyphProvider$GlyphEntry)
- GlyphInfo loadGlyph(int,FT_Face,int)
- TrueTypeGlyphProvider$GlyphEntry[] lambda$new$0(int)
- TrueTypeGlyphProvider$GlyphEntry[][] lambda$new$1(int)
```

</details>

<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
+ void _bindWrite(boolean)
+ void _resize(int,int,boolean)
- void clear()
+ void clear(boolean)
+ void createBuffers(int,int,boolean)
- void createBuffers(int,int)
+ void lambda$bindWrite$2(boolean)
+ void lambda$resize$1(int,int,boolean)
+ void lambda$unbindWrite$3()
+ void resize(int,int,boolean)
- void resize(int,int)
```

</details>



<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager
</summary>

```diff
+ void _clear(int,boolean)
- void _clear(int)
```

</details>





<details>
<summary>
net.minecraft.client.Minecraft$1
</summary>

```diff
+ void <clinit>()
- void <init>(Minecraft,GameConfig)
- void run()
```

</details>










<details>
<summary>
net.minecraft.client.gui.GuiGraphics
</summary>

```diff
- void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int,int,int)
- void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int,int)
- void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int,int)
- void blit(Function,ResourceLocation,int,int,float,float,int,int,int,int)
+ void blit(int,int,int,int,int,TextureAtlasSprite,float,float,float,float)
+ void blit(int,int,int,int,int,TextureAtlasSprite)
+ void blit(ResourceLocation,int,int,float,float,int,int,int,int)
+ void blit(ResourceLocation,int,int,int,float,float,int,int,int,int)
+ void blit(ResourceLocation,int,int,int,int,float,float,int,int,int,int)
+ void blit(ResourceLocation,int,int,int,int,int,int,int,float,float,int,int)
+ void blit(ResourceLocation,int,int,int,int,int,int)
- void blitNineSlicedSprite(Function,TextureAtlasSprite,GuiSpriteScaling$NineSlice,int,int,int,int,int)
+ void blitNineSlicedSprite(TextureAtlasSprite,GuiSpriteScaling$NineSlice,int,int,int,int,int)
- void blitSprite(Function,ResourceLocation,int,int,int,int,int,int,int,int)
- void blitSprite(Function,ResourceLocation,int,int,int,int,int)
- void blitSprite(Function,ResourceLocation,int,int,int,int)
- void blitSprite(Function,TextureAtlasSprite,int,int,int,int,int,int,int,int,int)
- void blitSprite(Function,TextureAtlasSprite,int,int,int,int,int)
- void blitSprite(Function,TextureAtlasSprite,int,int,int,int)
+ void blitSprite(ResourceLocation,int,int,int,int,int,int,int,int,int)
+ void blitSprite(ResourceLocation,int,int,int,int,int,int,int,int)
+ void blitSprite(ResourceLocation,int,int,int,int,int)
+ void blitSprite(ResourceLocation,int,int,int,int)
+ void blitSprite(TextureAtlasSprite,int,int,int,int,int,int,int,int,int)
+ void blitSprite(TextureAtlasSprite,int,int,int,int,int)
- void blitTiledSprite(Function,TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
+ void blitTiledSprite(TextureAtlasSprite,int,int,int,int,int,int,int,int,int,int,int)
+ void drawManaged(Runnable)
+ void flushIfManaged()
+ void flushIfUnmanaged()
- void innerBlit(Function,ResourceLocation,int,int,int,int,float,float,float,float,int)
+ void innerBlit(ResourceLocation,int,int,int,int,int,float,float,float,float,float,float,float,float)
+ void innerBlit(ResourceLocation,int,int,int,int,int,float,float,float,float)
+ void lambda$renderTooltipInternal$4(int,int,int,int)
+ void setColor(float,float,float,float)
```

</details>








<details>
<summary>
net.minecraft.client.gui.components.toasts.AdvancementToast
</summary>

```diff
- Toast$Visibility getWantedVisibility()
+ Toast$Visibility render(GuiGraphics,ToastComponent,long)
- void render(GuiGraphics,Font,long)
- void update(ToastManager,long)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
</summary>

```diff
- boolean showTooltipWithItemInHand()
```

</details>









<details>
<summary>
net.minecraft.client.gui.screens.options.AccessibilityOptionsScreen
</summary>

```diff
- boolean isMinecartOptionEnabled()
```

</details>







<details>
<summary>
net.minecraft.client.gui.screens.options.controls.KeyBindsList
</summary>

```diff
+ Minecraft access$800(KeyBindsList)
```

</details>









<details>
<summary>
net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
</summary>

```diff
+ void <init>()
- void <init>(SlotSelectTime,boolean)
+ void init(Minecraft,RecipeCollection,int,int,int,int,float)
- void init(RecipeCollection,boolean,int,int,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.model.ElytraModel
</summary>

```diff
+ Iterable bodyParts()
+ Iterable headParts()
- ModelPart root()
- void <clinit>()
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(HumanoidRenderState)
+ void setupAnim(LivingEntity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.FrogModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Frog,float,float,float,float,float)
- void setupAnim(FrogRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.GiantZombieModel
</summary>

```diff
+ boolean isAggressive(Giant)
+ boolean isAggressive(Monster)
```

</details>
<details>
<summary>
net.minecraft.client.model.GuardianModel
</summary>

```diff
- LayerDefinition createElderGuardianLayer()
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Guardian,float,float,float,float,float)
- void setupAnim(GuardianRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.LlamaSpitModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.Model
</summary>

```diff
- boolean lambda$getAnyDescendantWithName$0(String,ModelPart)
- ModelPart lambda$getAnyDescendantWithName$1(String,ModelPart)
- Optional getAnyDescendantWithName(String)
- void <clinit>()
- void animate(AnimationState,AnimationDefinition,float,float)
- void animate(AnimationState,AnimationDefinition,float)
- void animateWalk(AnimationDefinition,float,float,float,float)
- void applyStatic(AnimationDefinition)
- void lambda$animate$2(AnimationDefinition,float,float,AnimationState)
- void renderToBuffer(PoseStack,VertexConsumer,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.OcelotModel
</summary>

```diff
+ Iterable bodyParts()
+ Iterable headParts()
+ MeshDefinition createBodyMesh(CubeDeformation)
+ void prepareMobModel(Entity,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.ParrotModel
</summary>

```diff
- ParrotModel$Pose getPose(Parrot)
+ ParrotModel$State getState(Parrot)
- void prepare(ParrotModel$Pose)
+ void prepare(ParrotModel$State)
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(Parrot,float,float,float)
- void renderOnShoulder(PoseStack,VertexConsumer,int,int,float,float,float,float,float)
+ void renderOnShoulder(PoseStack,VertexConsumer,int,int,float,float,float,float,int)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Parrot,float,float,float,float,float)
- void setupAnim(ParrotModel$Pose,float,float,float,float,float,float)
+ void setupAnim(ParrotModel$State,int,float,float,float,float,float)
- void setupAnim(ParrotRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.PhantomModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Phantom,float,float,float,float,float)
- void setupAnim(PhantomRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.PiglinHeadModel
</summary>

```diff
- ModelPart root()
+ void renderToBuffer(PoseStack,VertexConsumer,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.PlayerModel
</summary>

```diff
+ boolean lambda$new$0(ModelPart)
- HumanoidModel$ArmPose getArmPose(HumanoidRenderState,HumanoidArm)
- HumanoidModel$ArmPose getArmPose(PlayerRenderState,HumanoidArm)
+ Iterable bodyParts()
- ModelPart getRandomBodyPart(RandomSource)
+ ModelPart getRandomModelPart(RandomSource)
+ void renderCloak(PoseStack,VertexConsumer,int,int)
+ void renderEars(PoseStack,VertexConsumer,int,int)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(HumanoidRenderState)
+ void setupAnim(LivingEntity,float,float,float,float,float)
- void setupAnim(PlayerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.PufferfishBigModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.PufferfishSmallModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.RabbitModel
</summary>

```diff
+ LayerDefinition createBodyLayer()
- LayerDefinition createBodyLayer(boolean)
- ModelPart root()
- void <clinit>()
+ void lambda$renderToBuffer$0(PoseStack,VertexConsumer,int,int,int,ModelPart)
+ void lambda$renderToBuffer$1(PoseStack,VertexConsumer,int,int,int,ModelPart)
+ void lambda$renderToBuffer$2(PoseStack,VertexConsumer,int,int,int,ModelPart)
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(Rabbit,float,float,float)
+ void renderToBuffer(PoseStack,VertexConsumer,int,int,int)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Rabbit,float,float,float,float,float)
- void setupAnim(RabbitRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.RavagerModel
</summary>

```diff
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(Ravager,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Ravager,float,float,float,float,float)
- void setupAnim(RavagerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.SheepFurModel
</summary>

```diff
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(Sheep,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(LivingEntityRenderState)
+ void setupAnim(Sheep,float,float,float,float,float)
- void setupAnim(SheepRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShieldModel
</summary>

```diff
- ModelPart root()
+ void renderToBuffer(PoseStack,VertexConsumer,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShulkerModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBoxLayer()
- MeshDefinition createShellMesh()
+ ModelPart getHead()
+ ModelPart getLid()
- ModelPart root()
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Shulker,float,float,float,float,float)
- void setupAnim(ShulkerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.SkeletonModel
</summary>

```diff
- HumanoidModel$ArmPose getArmPose(HumanoidRenderState,HumanoidArm)
- HumanoidModel$ArmPose getArmPose(SkeletonRenderState,HumanoidArm)
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(LivingEntity,float,float,float)
+ void prepareMobModel(Mob,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(HumanoidRenderState)
+ void setupAnim(LivingEntity,float,float,float,float,float)
+ void setupAnim(Mob,float,float,float,float,float)
- void setupAnim(SkeletonRenderState)
```

</details>

<details>
<summary>
net.minecraft.client.model.SnifferModel
</summary>

```diff
- void <clinit>()
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Sniffer,float,float,float,float,float)
- void setupAnim(SnifferRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.SpiderModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(LivingEntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.StriderModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Strider,float,float,float,float,float)
- void setupAnim(StriderRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.TridentModel
</summary>

```diff
- ModelPart root()
+ void renderToBuffer(PoseStack,VertexConsumer,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.TropicalFishModelB
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(TropicalFishRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
- void setArmsCharging(boolean,boolean,float)
+ void setArmsCharging(ItemStack,ItemStack,float)
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
+ void setupAnim(Vex,float,float,float,float,float)
- void setupAnim(VexRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.VillagerModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float)
- void setupAnim(EntityRenderState)
- void setupAnim(VillagerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.builders.PartDefinition
</summary>

```diff
- PartDefinition addOrReplaceChild(String,PartDefinition)
- PartDefinition clearChild(String)
- PartDefinition transformed(UnaryOperator)
- Set getChildren()
```

</details>








<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ boolean isLightUpdateQueueEmpty()
- boolean isTickingEntity(Entity)
- FuelValues fuelValues()
- int getCloudColor(float)
- int getSeaLevel()
- int getSkyColor(Vec3,float)
+ Vec3 getCloudColor(float)
+ Vec3 getSkyColor(Vec3,float)
+ Vec3 lambda$getSkyColor$12(BiomeManager,int,int,int)
- Vec3 lambda$getSkyColor$12(int,int,int)
- void <init>(ClientPacketListener,ClientLevel$ClientLevelData,ResourceKey,Holder,int,int,Supplier,LevelRenderer,boolean,long,int)
+ void <init>(ClientPacketListener,ClientLevel$ClientLevelData,ResourceKey,Holder,int,int,Supplier,LevelRenderer,boolean,long)
- void explode(Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Level$ExplosionInteraction,ParticleOptions,ParticleOptions,Holder)
- void setSectionRangeDirty(int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
</summary>

```diff
+ void <init>(Difficulty,boolean,boolean)
- void <init>(FeatureFlagSet,Difficulty,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- FuelValues fuelValues()
- Registry$PendingTags updateTags(ResourceKey,TagNetworkSerialization$NetworkPayload)
- void applyLightData(int,int,ClientboundLightUpdatePacketData,boolean)
+ void applyLightData(int,int,ClientboundLightUpdatePacketData)
- void broadcastClientInformation(ClientInformation)
- void handleMinecartAlongTrack(ClientboundMoveMinecartPacket)
+ void handleSetCarriedItem(ClientboundSetCarriedItemPacket)
- void handleSetCursorItem(ClientboundSetCursorItemPacket)
- void handleSetHeldSlot(ClientboundSetHeldSlotPacket)
- void handleSetPlayerInventory(ClientboundSetPlayerInventoryPacket)
- void lambda$handleAddOrRemoveRecipes$7(ClientRecipeBook,RecipeHolder)
- void lambda$handleAddOrRemoveRecipes$8(ClientRecipeBook,RecipeCollection)
+ void lambda$handleAddOrRemoveRecipes$8(ClientRecipeBook,RecipeHolder)
+ void lambda$handleAddOrRemoveRecipes$9(ClientRecipeBook,RecipeCollection)
- void lambda$handleBlockEntityData$4(ClientboundBlockEntityDataPacket,BlockEntity)
+ void lambda$handleBlockEntityData$5(ClientboundBlockEntityDataPacket,BlockEntity)
- void lambda$handleChunkBlocksUpdate$1(BlockPos,BlockState)
+ void lambda$handleChunkBlocksUpdate$2(BlockPos,BlockState)
- void lambda$handleGameEvent$6()
+ void lambda$handleGameEvent$7()
- void lambda$handleLevelChunkWithLight$2(int,int,ClientboundLightUpdatePacketData)
+ void lambda$handleLevelChunkWithLight$3(int,int,ClientboundLightUpdatePacketData)
+ void lambda$handleLogin$0(Optional)
+ void lambda$handlePlaceRecipe$11(AbstractContainerMenu,RecipeHolder)
- void lambda$handlePlaceRecipe$11(RecipeHolder)
- void lambda$handleRemoveEntities$0(int)
+ void lambda$handleRemoveEntities$1(int)
- void lambda$handleSetEquipment$5(LivingEntity,Pair)
+ void lambda$handleSetEquipment$6(LivingEntity,Pair)
- void lambda$handleUpdateTags$9(boolean,List,ResourceKey,TagNetworkSerialization$NetworkPayload)
- void lambda$queueLightRemoval$3(ChunkPos)
+ void lambda$queueLightRemoval$4(ChunkPos)
+ void lambda$tick$14(Optional)
- void prepareKeyPair()
- void readSectionList(int,int,LevelLightEngine,LightLayer,BitSet,BitSet,Iterator,boolean)
+ void readSectionList(int,int,LevelLightEngine,LightLayer,BitSet,BitSet,Iterator)
```

</details>





<details>
<summary>
net.minecraft.client.multiplayer.MultiPlayerGameMode
</summary>

```diff
- ItemStack lambda$useItem$5(Player,InteractionHand)
+ Packet lambda$useItem$5(InteractionHand,Player,MutableObject,int)
- Packet lambda$useItem$6(InteractionHand,Player,MutableObject,int)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.PlayerInfo
</summary>

```diff
- int getTabListOrder()
- void setTabListOrder(int)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.RegistryDataCollector$ContentsCollector
</summary>

```diff
+ RegistryAccess loadRegistries(ResourceProvider,RegistryAccess)
```

</details>




















































<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
+ float getFieldOfViewModifier()
- float getFieldOfViewModifier(boolean)
```

</details>

















<details>
<summary>
net.minecraft.client.renderer.LightTexture
</summary>

```diff
- float getBrightness(float,int)
+ float notGamma(float)
- int lightCoordsWithEmission(int,int)
- void <clinit>()
+ void clampColor(Vector3f)
- void loadShader(ResourceProvider)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
</summary>

```diff
+ MultiPart getMultiPart(JsonDeserializationContext,JsonObject)
- MultiPart$Definition getMultiPart(JsonDeserializationContext,JsonObject)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.FaceBakery
</summary>

```diff
- BakedQuad bakeQuad(Vector3f,Vector3f,BlockElementFace,TextureAtlasSprite,Direction,ModelState,BlockElementRotation,boolean,int)
+ BakedQuad bakeQuad(Vector3f,Vector3f,BlockElementFace,TextureAtlasSprite,Direction,ModelState,BlockElementRotation,boolean)
+ int[] makeVertices(BlockFaceUV,TextureAtlasSprite,Direction,float[],Transformation,BlockElementRotation,boolean)
- int[] makeVertices(BlockFaceUV,TextureAtlasSprite,Direction,float[],Transformation,BlockElementRotation)
+ void bakeVertex(int[],int,Direction,BlockFaceUV,float[],TextureAtlasSprite,Transformation,BlockElementRotation,boolean)
- void bakeVertex(int[],int,Direction,BlockFaceUV,float[],TextureAtlasSprite,Transformation,BlockElementRotation)
```

</details>







<details>
<summary>
net.minecraft.client.renderer.block.model.MultiVariant
</summary>

```diff
+ Collection getDependencies()
+ List getVariants()
- List variants()
- Object visualEqualityGroup(BlockState)
- String toString()
- void lambda$resolveDependencies$0(UnbakedModel$Resolver,Variant)
+ void lambda$resolveParents$0(Function,ResourceLocation)
- void resolveDependencies(UnbakedModel$Resolver,UnbakedModel$ResolutionContext)
+ void resolveParents(Function)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.AndCondition
</summary>

```diff
+ boolean lambda$getPredicate$1(BlockState,Predicate)
+ boolean lambda$getPredicate$2(List,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
</summary>

```diff
- boolean lambda$getBlockStatePredicate$1(Property,Optional,BlockState)
+ boolean lambda$getBlockStatePredicate$3(Property,Optional,BlockState)
+ boolean lambda$getPredicate$1(BlockState,Predicate)
+ boolean lambda$getPredicate$2(List,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
</summary>

```diff
+ MultiPart deserialize(JsonElement,Type,JsonDeserializationContext)
- MultiPart$Definition deserialize(JsonElement,Type,JsonDeserializationContext)
- void <init>()
+ void <init>(BlockModelDefinition$Context)
```

</details>





















<details>
<summary>
net.minecraft.client.renderer.entity.AllayRenderer
</summary>

```diff
- AllayRenderState createRenderState()
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Allay)
- ResourceLocation getTextureLocation(AllayRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Allay,AllayRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ArmorStandRenderer
</summary>

```diff
- ArmorStandRenderState createRenderState()
- boolean shouldShowName(ArmorStand,double)
+ boolean shouldShowName(ArmorStand)
- boolean shouldShowName(Entity,double)
+ boolean shouldShowName(Entity)
- boolean shouldShowName(LivingEntity,double)
+ boolean shouldShowName(LivingEntity)
- EntityRenderState createRenderState()
+ RenderType getRenderType(ArmorStand,boolean,boolean,boolean)
- RenderType getRenderType(ArmorStandRenderState,boolean,boolean,boolean)
+ RenderType getRenderType(LivingEntity,boolean,boolean,boolean)
- RenderType getRenderType(LivingEntityRenderState,boolean,boolean,boolean)
+ ResourceLocation getTextureLocation(ArmorStand)
- ResourceLocation getTextureLocation(ArmorStandRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(ArmorStand,ArmorStandRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
- void render(ArmorStandRenderState,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
- void render(LivingEntityRenderState,PoseStack,MultiBufferSource,int)
+ void setupRotations(ArmorStand,PoseStack,float,float,float,float)
- void setupRotations(ArmorStandRenderState,PoseStack,float,float)
+ void setupRotations(LivingEntity,PoseStack,float,float,float,float)
- void setupRotations(LivingEntityRenderState,PoseStack,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AxolotlRenderer
</summary>

```diff
- AxolotlRenderState createRenderState()
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Axolotl)
- ResourceLocation getTextureLocation(AxolotlRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Axolotl,AxolotlRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BeeRenderer
</summary>

```diff
- BeeRenderState createRenderState()
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Bee)
- ResourceLocation getTextureLocation(BeeRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Bee,BeeRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BoatRenderer
</summary>

```diff
- BoatRenderState createRenderState()
- EntityModel createBoatModel(EntityRendererProvider$Context,Boat$Type,boolean)
- EntityRenderState createRenderState()
+ ListModel createBoatModel(EntityRendererProvider$Context,Boat$Type,boolean)
- RenderType lambda$new$2(ResourceLocation)
+ ResourceLocation getTextureLocation(Boat)
- ResourceLocation getTextureLocation(BoatRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Boat,BoatRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
+ void render(Boat,float,float,PoseStack,MultiBufferSource,int)
- void render(BoatRenderState,PoseStack,MultiBufferSource,int)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CodRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- LivingEntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Cod)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- ResourceLocation getTextureLocation(LivingEntityRenderState)
+ void setupRotations(Cod,PoseStack,float,float,float,float)
+ void setupRotations(LivingEntity,PoseStack,float,float,float,float)
- void setupRotations(LivingEntityRenderState,PoseStack,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CreeperRenderer
</summary>

```diff
- CreeperRenderState createRenderState()
- EntityRenderState createRenderState()
+ float getWhiteOverlayProgress(Creeper,float)
- float getWhiteOverlayProgress(CreeperRenderState)
+ float getWhiteOverlayProgress(LivingEntity,float)
- float getWhiteOverlayProgress(LivingEntityRenderState)
+ ResourceLocation getTextureLocation(Creeper)
- ResourceLocation getTextureLocation(CreeperRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Creeper,CreeperRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
+ void scale(Creeper,PoseStack,float)
- void scale(CreeperRenderState,PoseStack)
+ void scale(LivingEntity,PoseStack,float)
- void scale(LivingEntityRenderState,PoseStack)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.DisplayRenderer$ItemDisplayRenderer
</summary>

```diff
- AABB getBoundingBoxForCulling(Entity)
- boolean affectedByCulling(Entity)
+ Display$ItemDisplay$ItemRenderState getSubState(Display$ItemDisplay)
- EntityRenderState createRenderState()
- ItemDisplayEntityRenderState createRenderState()
+ Object getSubState(Display)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Display,DisplayEntityRenderState,float)
- void extractRenderState(Display$ItemDisplay,ItemDisplayEntityRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void renderInner(Display,Object,PoseStack,MultiBufferSource,int,float)
+ void renderInner(Display$ItemDisplay,Display$ItemDisplay$ItemRenderState,PoseStack,MultiBufferSource,int,float)
- void renderInner(DisplayEntityRenderState,PoseStack,MultiBufferSource,int,float)
- void renderInner(ItemDisplayEntityRenderState,PoseStack,MultiBufferSource,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DolphinRenderer
</summary>

```diff
- DolphinRenderState createRenderState()
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Dolphin)
- ResourceLocation getTextureLocation(DolphinRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- void extractRenderState(Dolphin,DolphinRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndermiteRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- float getFlipDegrees()
+ float getFlipDegrees(Endermite)
+ float getFlipDegrees(LivingEntity)
- LivingEntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Endermite)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
- ResourceLocation getTextureLocation(LivingEntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderer
</summary>

```diff
- AABB getBoundingBoxForCulling(Entity)
- boolean affectedByCulling(Entity)
- boolean shouldShowName(Entity,double)
+ boolean shouldShowName(Entity)
- Component getNameTag(Entity)
- EntityRenderState createRenderState(Entity,float)
+ float getShadowRadius(Entity)
- float getShadowRadius(EntityRenderState)
+ Vec3 getRenderOffset(Entity,float)
- Vec3 getRenderOffset(EntityRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void renderLeash(Entity,float,PoseStack,MultiBufferSource,Entity)
- void renderLeash(PoseStack,MultiBufferSource,EntityRenderState$LeashState)
+ void renderNameTag(Entity,Component,PoseStack,MultiBufferSource,int,float)
- void renderNameTag(EntityRenderState,Component,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRendererProvider$Context
</summary>

```diff
+ ItemInHandRenderer getItemInHandRenderer()
- MapRenderer getMapRenderer()
+ void <init>(EntityRenderDispatcher,ItemRenderer,BlockRenderDispatcher,ItemInHandRenderer,ResourceManager,EntityModelSet,Font)
- void <init>(EntityRenderDispatcher,ItemRenderer,MapRenderer,BlockRenderDispatcher,ResourceManager,EntityModelSet,Font)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EvokerFangsRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- EvokerFangsRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(EvokerFangs)
- ResourceLocation getTextureLocation(EvokerFangsRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(EvokerFangs,EvokerFangsRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(EvokerFangs,float,float,PoseStack,MultiBufferSource,int)
- void render(EvokerFangsRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EvokerRenderer$1
</summary>

```diff
+ void <init>(EvokerRenderer,RenderLayerParent,ItemInHandRenderer)
- void <init>(EvokerRenderer,RenderLayerParent,ItemRenderer)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void render(PoseStack,MultiBufferSource,int,EvokerRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,SpellcasterIllager,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.FallingBlockRenderer
</summary>

```diff
- boolean shouldRender(Entity,Frustum,double,double,double)
- boolean shouldRender(FallingBlockEntity,Frustum,double,double,double)
- EntityRenderState createRenderState()
- FallingBlockRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(FallingBlockEntity)
- ResourceLocation getTextureLocation(FallingBlockRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(FallingBlockEntity,FallingBlockRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(FallingBlockEntity,float,float,PoseStack,MultiBufferSource,int)
- void render(FallingBlockRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.FishingHookRenderer
</summary>

```diff
- boolean affectedByCulling(Entity)
- boolean affectedByCulling(FishingHook)
- boolean shouldRender(Entity,Frustum,double,double,double)
- boolean shouldRender(FishingHook,Frustum,double,double,double)
- EntityRenderState createRenderState()
- FishingHookRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(FishingHook)
- ResourceLocation getTextureLocation(FishingHookRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(FishingHook,FishingHookRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(FishingHook,float,float,PoseStack,MultiBufferSource,int)
- void render(FishingHookRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.FrogRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- FrogRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(Frog)
- ResourceLocation getTextureLocation(FrogRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(Frog,FrogRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.GiantMobRenderer
</summary>

```diff
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(Giant)
- ResourceLocation getTextureLocation(ZombieRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(Giant,ZombieRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
+ void scale(Giant,PoseStack,float)
+ void scale(LivingEntity,PoseStack,float)
- ZombieRenderState createRenderState()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.GoatRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- GoatRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(Goat)
- ResourceLocation getTextureLocation(GoatRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(Goat,GoatRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.HoglinRenderer
</summary>

```diff
+ boolean isShaking(Hoglin)
- boolean isShaking(HoglinRenderState)
+ boolean isShaking(LivingEntity)
- boolean isShaking(LivingEntityRenderState)
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(Hoglin)
- ResourceLocation getTextureLocation(HoglinRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(Hoglin,HoglinRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
- void extractRenderState(Mob,HoglinRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.HumanoidMobRenderer
</summary>

```diff
- HumanoidArm getAttackArm(LivingEntity)
+ void <init>(EntityRendererProvider$Context,HumanoidModel,float,float,float,float)
- void <init>(EntityRendererProvider$Context,HumanoidModel,HumanoidModel,float,CustomHeadLayer$Transforms)
- void <init>(EntityRendererProvider$Context,HumanoidModel,HumanoidModel,float)
- void extractHumanoidRenderState(LivingEntity,HumanoidRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
- void extractRenderState(Mob,HumanoidRenderState,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.IllagerRenderer
</summary>

```diff
- void extractRenderState(AbstractIllager,IllagerRenderState,float)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
+ void scale(AbstractIllager,PoseStack,float)
+ void scale(LivingEntity,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.IllusionerRenderer$1
</summary>

```diff
+ void <init>(IllusionerRenderer,RenderLayerParent,ItemInHandRenderer)
- void <init>(IllusionerRenderer,RenderLayerParent,ItemRenderer)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,Illusioner,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,IllusionerRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ItemEntityRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- ItemEntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(ItemEntity)
- ResourceLocation getTextureLocation(ItemEntityRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(ItemEntity,ItemEntityRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(ItemEntity,float,float,PoseStack,MultiBufferSource,int)
- void render(ItemEntityRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ItemRenderer
</summary>

```diff
- BakedModel resolveItemModel(ItemStack,LivingEntity,ItemDisplayContext)
- ModelResourceLocation getBundleOpenBackModelLocation(BundleItem)
- ModelResourceLocation getBundleOpenFrontModelLocation(BundleItem)
- void renderBundleWithSelectedItem(ItemStack,ItemDisplayContext,boolean,PoseStack,MultiBufferSource,int,int,boolean)
- void renderItem(ItemStack,ItemDisplayContext,PoseStack,MultiBufferSource,int,int,BakedModel,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LightningBoltRenderer
</summary>

```diff
- boolean affectedByCulling(Entity)
- boolean affectedByCulling(LightningBolt)
- EntityRenderState createRenderState()
- LightningBoltRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(LightningBolt)
- ResourceLocation getTextureLocation(LightningBoltRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LightningBolt,LightningBoltRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(LightningBolt,float,float,PoseStack,MultiBufferSource,int)
- void render(LightningBoltRenderState,PoseStack,MultiBufferSource,int)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.entity.MagmaCubeRenderer
</summary>

```diff
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(MagmaCube)
- ResourceLocation getTextureLocation(SlimeRenderState)
- SlimeRenderState createRenderState()
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(LivingEntity,LivingEntityRenderState,float)
- void extractRenderState(MagmaCube,SlimeRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(LivingEntity,float,float,PoseStack,MultiBufferSource,int)
- void render(LivingEntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(MagmaCube,float,float,PoseStack,MultiBufferSource,int)
- void render(SlimeRenderState,PoseStack,MultiBufferSource,int)
+ void scale(LivingEntity,PoseStack,float)
- void scale(LivingEntityRenderState,PoseStack)
+ void scale(MagmaCube,PoseStack,float)
- void scale(SlimeRenderState,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.MobRenderer
</summary>

```diff
- boolean shouldShowName(Entity,double)
+ boolean shouldShowName(Entity)
- boolean shouldShowName(LivingEntity,double)
+ boolean shouldShowName(LivingEntity)
- boolean shouldShowName(Mob,double)
+ boolean shouldShowName(Mob)
+ float getShadowRadius(Entity)
- float getShadowRadius(EntityRenderState)
+ float getShadowRadius(LivingEntity)
- float getShadowRadius(LivingEntityRenderState)
+ float getShadowRadius(Mob)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.NoopRenderer
</summary>

```diff
- EntityRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.OminousItemSpawnerRenderer
</summary>

```diff
- EntityRenderState createRenderState()
- OminousItemSpawnerRenderState createRenderState()
+ ResourceLocation getTextureLocation(Entity)
- ResourceLocation getTextureLocation(EntityRenderState)
+ ResourceLocation getTextureLocation(OminousItemSpawner)
- ResourceLocation getTextureLocation(OminousItemSpawnerRenderState)
- void extractRenderState(Entity,EntityRenderState,float)
- void extractRenderState(OminousItemSpawner,OminousItemSpawnerRenderState,float)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(EntityRenderState,PoseStack,MultiBufferSource,int)
+ void render(OminousItemSpawner,float,float,PoseStack,MultiBufferSource,int)
- void render(OminousItemSpawnerRenderState,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.ArrowLayer
</summary>

```diff
+ int numStuck(LivingEntity)
- int numStuck(PlayerRenderState)
+ void <init>(EntityRendererProvider$Context,LivingEntityRenderer)
- void <init>(LivingEntityRenderer,EntityRendererProvider$Context)
+ void renderStuckItem(PoseStack,MultiBufferSource,int,Entity,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.BreezeEyesLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,Breeze,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,BreezeRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CapeLayer
</summary>

```diff
- void <init>(RenderLayerParent,EntityModelSet)
+ void <init>(RenderLayerParent)
+ void render(PoseStack,MultiBufferSource,int,AbstractClientPlayer,float,float,float,float,float,float)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
- void render(PoseStack,MultiBufferSource,int,PlayerRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CatCollarLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,Cat,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,CatRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
</summary>

```diff
+ void <init>(RenderLayerParent,ItemInHandRenderer)
- void <init>(RenderLayerParent,ItemRenderer)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntityRenderState,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
</summary>

```diff
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,SlimeRenderState,float,float)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
</summary>

```diff
- float snapToFace(float)
- void <init>(LivingEntityRenderer,Model,ResourceLocation,StuckInBodyLayer$PlacementStyle)
+ void <init>(LivingEntityRenderer)
+ void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EntityRenderState,float,float)
+ void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,PlayerRenderState,float,float)
- void renderStuckItem(PoseStack,MultiBufferSource,int,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.AbstractTexture
</summary>

```diff
- boolean getDefaultBlur()
```

</details>



<details>
<summary>
net.minecraft.client.renderer.texture.SimpleTexture
</summary>

```diff
+ void lambda$load$0(NativeImage,boolean,boolean)
- void lambda$load$0(NativeImage,boolean)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.texture.SpriteContents$Ticker
</summary>

```diff
+ void lambda$tickAndUpload$0(int,int)
```

</details>















































<details>
<summary>
net.minecraft.client.resources.model.ModelManager$ReloadState
</summary>

```diff
- Object2IntMap modelGroups()
+ void <init>(ModelBakery,BakedModel,Map,Map,CompletableFuture)
- void <init>(ModelBakery,Object2IntMap,BakedModel,Map,Map,CompletableFuture)
```

</details>






<details>
<summary>
net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
</summary>

```diff
+ boolean lambda$bootStrap$41(TagKey,boolean,Entity)
+ boolean lambda$bootStrap$43(EntityType,boolean,Entity)
- boolean lambda$bootStrap$43(TagKey,boolean,Entity)
+ boolean lambda$bootStrap$45(EntitySelectorParser)
- boolean lambda$bootStrap$45(EntityType,boolean,Entity)
+ boolean lambda$bootStrap$46(String,boolean,Entity)
- boolean lambda$bootStrap$47(EntitySelectorParser)
+ boolean lambda$bootStrap$48(EntitySelectorParser)
- boolean lambda$bootStrap$48(String,boolean,Entity)
+ boolean lambda$bootStrap$49(CompoundTag,boolean,Entity)
- boolean lambda$bootStrap$50(EntitySelectorParser)
- boolean lambda$bootStrap$51(CompoundTag,boolean,Entity)
+ boolean lambda$bootStrap$51(EntitySelectorParser)
+ boolean lambda$bootStrap$52(Map,Entity)
- boolean lambda$bootStrap$53(EntitySelectorParser)
+ boolean lambda$bootStrap$54(EntitySelectorParser)
- boolean lambda$bootStrap$54(Map,Entity)
+ boolean lambda$bootStrap$55(boolean,CriterionProgress)
- boolean lambda$bootStrap$56(EntitySelectorParser)
+ boolean lambda$bootStrap$56(Map,AdvancementProgress)
+ boolean lambda$bootStrap$57(boolean,AdvancementProgress)
- boolean lambda$bootStrap$57(boolean,CriterionProgress)
- boolean lambda$bootStrap$58(Map,AdvancementProgress)
+ boolean lambda$bootStrap$58(Map,Entity)
- boolean lambda$bootStrap$59(boolean,AdvancementProgress)
+ boolean lambda$bootStrap$60(EntitySelectorParser)
- boolean lambda$bootStrap$60(Map,Entity)
+ boolean lambda$bootStrap$61(ResourceKey,boolean,Entity)
- boolean lambda$bootStrap$62(EntitySelectorParser)
+ boolean lambda$bootStrap$63(EntitySelectorParser)
- boolean lambda$bootStrap$63(ResourceKey,boolean,Entity)
- boolean lambda$bootStrap$65(EntitySelectorParser)
+ CommandSyntaxException lambda$bootStrap$42(EntitySelectorParser,int,ResourceLocation)
- CommandSyntaxException lambda$bootStrap$44(EntitySelectorParser,int,ResourceLocation)
+ CompletableFuture lambda$bootStrap$40(EntitySelectorParser,SuggestionsBuilder,Consumer)
- CompletableFuture lambda$bootStrap$42(EntitySelectorParser,SuggestionsBuilder,Consumer)
- ResourceLocation lambda$bootStrap$40(HolderSet$Named)
- ResourceLocation lambda$bootStrap$41(HolderSet$Named)
+ void lambda$bootStrap$44(EntitySelectorParser)
- void lambda$bootStrap$46(EntitySelectorParser)
+ void lambda$bootStrap$47(EntitySelectorParser)
- void lambda$bootStrap$49(EntitySelectorParser)
+ void lambda$bootStrap$50(EntitySelectorParser)
- void lambda$bootStrap$52(EntitySelectorParser)
+ void lambda$bootStrap$53(EntitySelectorParser)
- void lambda$bootStrap$55(EntitySelectorParser)
+ void lambda$bootStrap$59(EntitySelectorParser)
- void lambda$bootStrap$61(EntitySelectorParser)
+ void lambda$bootStrap$62(EntitySelectorParser)
- void lambda$bootStrap$64(EntitySelectorParser)
```

</details>









































<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
+ Direction fromDelta(int,int,int)
- Direction getApproximateNearest(double,double,double)
- Direction getApproximateNearest(float,float,float)
- Direction getApproximateNearest(Vec3)
+ Direction getNearest(double,double,double)
+ Direction getNearest(float,float,float)
- Direction getNearest(int,int,int,Direction)
+ Direction getNearest(Vec3)
- Direction getNearest(Vec3i,Direction)
- float getYRot(Direction)
- Vec3 getUnitVec3()
+ Vec3i getNormal()
- Vec3i getUnitVec3i()
```

</details>








<details>
<summary>
net.minecraft.core.HolderLookup$Provider
</summary>

```diff
- Lifecycle allRegistriesLifecycle()
- Stream listRegistries()
```

</details>
<details>
<summary>
net.minecraft.core.HolderLookup$Provider$2
</summary>

```diff
+ Stream listRegistries()
- Stream listRegistryKeys()
```

</details>









<details>
<summary>
net.minecraft.data.loot.BlockLootSubProvider
</summary>

```diff
- LootItemCondition$Builder hasShears()
```

</details>


<details>
<summary>
net.minecraft.data.recipes.packs.VanillaRecipeProvider
</summary>

```diff
+ CompletableFuture run(CachedOutput,HolderLookup$Provider)
+ VanillaRecipeProvider$TrimTemplate lambda$smithingTrims$1(Item)
- VanillaRecipeProvider$TrimTemplate lambda$smithingTrims$2(Item)
- void <init>(HolderLookup$Provider,RecipeOutput)
+ void <init>(PackOutput,CompletableFuture)
- void buildRecipes()
+ void buildRecipes(RecipeOutput)
- void lambda$buildRecipes$0(Item)
+ void lambda$buildRecipes$0(RecipeOutput,VanillaRecipeProvider$TrimTemplate)
- void lambda$buildRecipes$1(VanillaRecipeProvider$TrimTemplate)
```

</details>











<details>
<summary>
net.minecraft.gametest.framework.StructureUtils
</summary>

```diff
- BlockPos getStartCorner(GameTestInfo,BlockPos,Rotation,ServerLevel)
+ boolean lambda$clearSpaceForStructure$5(Entity)
- boolean lambda$clearSpaceForStructure$6(Entity)
+ boolean lambda$findStructureBlockContainingPos$6(BlockPos,ServerLevel,BlockPos)
- boolean lambda$findStructureBlockContainingPos$7(BlockPos,ServerLevel,BlockPos)
+ boolean lambda$findStructureBlocks$10(ServerLevel,BlockPos)
- boolean lambda$findStructureBlocks$11(ServerLevel,BlockPos)
- boolean lambda$findStructureByTestFunction$10(String,StructureBlockEntity)
+ boolean lambda$findStructureByTestFunction$9(String,StructureBlockEntity)
+ boolean lambda$lookedAtStructureBlockPos$12(Vec3,Vec3,StructureBlockEntity)
- boolean lambda$lookedAtStructureBlockPos$13(Vec3,Vec3,StructureBlockEntity)
- IllegalStateException lambda$getStartCorner$0(GameTestInfo)
+ IllegalStateException lambda$prepareTestStructure$0(GameTestInfo)
- IllegalStateException lambda$prepareTestStructure$1(GameTestInfo)
+ int lambda$findNearestStructureBlock$7(BlockPos,BlockPos)
- int lambda$findNearestStructureBlock$8(BlockPos,BlockPos)
+ Optional lambda$lookedAtStructureBlockPos$11(ServerLevel,BlockPos)
- Optional lambda$lookedAtStructureBlockPos$12(ServerLevel,BlockPos)
+ StructureBlockEntity lambda$findStructureByTestFunction$8(ServerLevel,BlockPos)
- StructureBlockEntity lambda$findStructureByTestFunction$9(ServerLevel,BlockPos)
+ void lambda$clearSpaceForStructure$4(int,ServerLevel,BlockPos)
- void lambda$clearSpaceForStructure$5(int,ServerLevel,BlockPos)
+ void lambda$encaseStructure$1(BlockPos,BlockPos,boolean,ServerLevel,BlockPos)
- void lambda$encaseStructure$2(BlockPos,BlockPos,boolean,ServerLevel,BlockPos)
+ void lambda$forceLoadChunks$3(ServerLevel,ChunkPos)
- void lambda$forceLoadChunks$4(ServerLevel,ChunkPos)
+ void lambda$removeBarriers$2(BlockPos,BlockPos,ServerLevel,BlockPos)
- void lambda$removeBarriers$3(BlockPos,BlockPos,ServerLevel,BlockPos)
```

</details>
























































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundExplodePacket
</summary>

```diff
+ BlockPos lambda$new$0(int,int,int,FriendlyByteBuf)
- boolean equals(Object)
+ double getX()
+ double getY()
+ double getZ()
+ Explosion$BlockInteraction getBlockInteraction()
+ float getKnockbackX()
+ float getKnockbackY()
+ float getKnockbackZ()
+ float getPower()
- Holder explosionSound()
+ Holder getExplosionSound()
- int hashCode()
+ List getToBlow()
- Optional playerKnockback()
- ParticleOptions explosionParticle()
+ ParticleOptions getLargeExplosionParticles()
+ ParticleOptions getSmallExplosionParticles()
- String toString()
- Vec3 center()
+ void <init>(double,double,double,float,List,Vec3,Explosion$BlockInteraction,ParticleOptions,ParticleOptions,Holder)
+ void <init>(RegistryFriendlyByteBuf)
- void <init>(Vec3,Optional,ParticleOptions,Holder)
+ void lambda$write$1(int,int,int,FriendlyByteBuf,BlockPos)
+ void write(RegistryFriendlyByteBuf)
```

</details>





















<details>
<summary>
net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
</summary>

```diff
- void <init>(double,double,double,boolean,boolean)
+ void <init>(double,double,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
</summary>

```diff
- void <init>(float,float,boolean,boolean)
+ void <init>(float,float,boolean)
```

</details>








<details>
<summary>
net.minecraft.recipebook.ServerPlaceRecipe
</summary>

```diff
- int calculateAmountToCraft(int,boolean)
+ int getStackSize(boolean,int,boolean)
- int lambda$placeRecipe$0(Holder)
- int moveItemToGrid(Slot,Holder,int)
+ int moveItemToGrid(Slot,ItemStack,int)
- RecipeBookMenu$PostPlaceAction placeRecipe(ServerPlaceRecipe$CraftingMenuAccess,int,int,List,List,Inventory,RecipeHolder,boolean,boolean)
- RecipeBookMenu$PostPlaceAction tryPlaceRecipe(RecipeHolder,StackedItemContents)
+ void <init>(RecipeBookMenu)
- void <init>(ServerPlaceRecipe$CraftingMenuAccess,Inventory,boolean,int,int,List,List)
+ void addItemToSlot(Integer,int,int,int,int)
+ void addItemToSlot(Object,int,int,int,int)
+ void handleRecipeClicked(RecipeHolder,boolean)
- void lambda$placeRecipe$1(int,List,Optional,int,int,int)
- void placeRecipe(RecipeHolder,StackedItemContents)
+ void recipeClicked(ServerPlayer,RecipeHolder,boolean)
```

</details>















<details>
<summary>
net.minecraft.server.ReloadableServerRegistries
</summary>

```diff
- CompletableFuture reload(LayeredRegistryAccess,List,ResourceManager,Executor)
+ CompletableFuture reload(LayeredRegistryAccess,ResourceManager,Executor)
+ CompletableFuture scheduleElementParse(LootDataType,RegistryOps,ResourceManager,Executor)
- CompletableFuture scheduleRegistryLoad(LootDataType,RegistryOps,ResourceManager,Executor)
- HolderLookup$Provider concatenateLookups(HolderLookup$Provider,HolderLookup$Provider)
+ LayeredRegistryAccess apply(LayeredRegistryAccess,List)
+ LayeredRegistryAccess lambda$reload$1(LayeredRegistryAccess,List)
- ReloadableServerRegistries$LoadResult createAndValidateFullContext(LayeredRegistryAccess,HolderLookup$Provider,List)
- ReloadableServerRegistries$LoadResult lambda$reload$1(LayeredRegistryAccess,HolderLookup$Provider,List)
+ void lambda$apply$5(ValidationContext,RegistryAccess$Frozen,LootDataType)
+ void lambda$apply$6(String,String)
+ void lambda$scheduleElementParse$2(WritableRegistry,LootDataType,ResourceLocation,Object)
+ void lambda$scheduleElementParse$3(LootDataType,RegistryOps,WritableRegistry,ResourceLocation,JsonElement)
- void lambda$scheduleRegistryLoad$2(WritableRegistry,LootDataType,ResourceLocation,Object)
- void lambda$scheduleRegistryLoad$3(LootDataType,RegistryOps,WritableRegistry,ResourceLocation,JsonElement)
- void lambda$validateLootRegistries$5(ValidationContext,HolderLookup$Provider,LootDataType)
- void lambda$validateLootRegistries$6(String,String)
- void validateLootRegistries(HolderLookup$Provider)
- void validateRegistry(ValidationContext,LootDataType,HolderLookup$Provider)
+ void validateRegistry(ValidationContext,LootDataType,RegistryAccess)
+ WritableRegistry lambda$scheduleElementParse$4(LootDataType,ResourceManager,RegistryOps)
- WritableRegistry lambda$scheduleRegistryLoad$4(LootDataType,ResourceManager,RegistryOps)
```

</details>
<details>
<summary>
net.minecraft.server.WorldLoader
</summary>

```diff
+ LayeredRegistryAccess loadAndReplaceLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
+ RegistryAccess$Frozen loadLayer(ResourceManager,LayeredRegistryAccess,RegistryLayer,List)
```

</details>























































<details>
<summary>
net.minecraft.server.commands.ScheduleCommand
</summary>

```diff
+ Component lambda$remove$11(int,String)
- Component lambda$remove$9(int,String)
- Component lambda$schedule$8(ResourceLocation,int,long)
+ Component lambda$schedule$9(ResourceLocation,int,long)
+ void lambda$schedule$10(ResourceLocation,boolean,TimerQueue,long,CommandSourceStack,int,Collection)
+ void lambda$schedule$8(ResourceLocation,boolean,TimerQueue,long,CommandSourceStack,int,CommandFunction)
```

</details>



<details>
<summary>
net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
</summary>

```diff
- Component lambda$setIdleTimeout$3()
```

</details>




















<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
+ boolean areNpcsEnabled()
+ boolean isSpawningAnimals()
- int pauseWhileEmptySeconds()
+ void tickChildren(BooleanSupplier)
- void tickConnection()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- WorldDimensions createDimensions(HolderLookup$Provider)
+ WorldDimensions createDimensions(RegistryAccess)
```

</details>







<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
- boolean blockChanged(BlockPos)
- boolean sectionLightChanged(LightLayer,int)
+ void blockChanged(BlockPos)
+ void sectionLightChanged(LightLayer,int)
```

</details>










<details>
<summary>
net.minecraft.server.level.DistanceManager
</summary>

```diff
- boolean lambda$runAllUpdates$0(Ticket)
+ boolean lambda$runAllUpdates$2(Ticket)
- LongIterator getSpawnCandidateChunks()
- LongSet getTickingChunks()
- ObjectSet lambda$addPlayer$5(long)
+ ObjectSet lambda$addPlayer$7(long)
- SortedArraySet lambda$getTickets$4(long)
+ SortedArraySet lambda$getTickets$6(long)
+ void lambda$runAllUpdates$0(ChunkMap,ChunkHolder)
- void lambda$runAllUpdates$1()
+ void lambda$runAllUpdates$1(ChunkMap,ChunkHolder)
- void lambda$runAllUpdates$2(long)
+ void lambda$runAllUpdates$3()
- void lambda$runAllUpdates$3(long,ChunkResult)
+ void lambda$runAllUpdates$4(long)
+ void lambda$runAllUpdates$5(long,ChunkResult)
```

</details>








<details>
<summary>
net.minecraft.server.level.TickingTracker
</summary>

```diff
- LongSet getTickingChunks()
```

</details>







<details>
<summary>
net.minecraft.server.network.ServerCommonPacketListenerImpl
</summary>

```diff
- void onPacketError(Packet,Exception)
```

</details>








<details>
<summary>
net.minecraft.tags.TagNetworkSerialization
</summary>

```diff
- TagLoader$LoadResult deserializeTagsFromNetwork(Registry,TagNetworkSerialization$NetworkPayload)
+ void deserializeTagsFromNetwork(ResourceKey,Registry,TagNetworkSerialization$NetworkPayload,TagNetworkSerialization$TagOutput)
- void lambda$deserializeTagsFromNetwork$3(ResourceKey,Registry,Map,ResourceLocation,IntList)
+ void lambda$deserializeTagsFromNetwork$3(ResourceKey,Registry,TagNetworkSerialization$TagOutput,ResourceLocation,IntList)
- void lambda$serializeToNetwork$2(Registry,Map,HolderSet$Named)
+ void lambda$serializeToNetwork$2(Registry,Map,Pair)
```

</details>































<details>
<summary>
net.minecraft.util.datafix.ExtraDataFixUtils
</summary>

```diff
- Dynamic blockState(String,Map)
- Dynamic blockState(String)
- Dynamic fixStringField(Dynamic,String,UnaryOperator)
- Dynamic lambda$blockState$3(Dynamic,Map$Entry)
- Dynamic lambda$blockState$4(Dynamic,Map$Entry)
- Dynamic lambda$fixStringField$5(UnaryOperator,Dynamic,Dynamic)
- Function lambda$typePatcher$1(DynamicOps)
- Object lambda$typePatcher$0(Object)
- Type patchSubType(Type,Type,Type)
+ Typed lambda$chainAllFilters$0(Function[],Typed)
- Typed lambda$chainAllFilters$2(Function[],Typed)
- TypeRewriteRule typePatcher(Type,Type)
```

</details>




































<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$2(Function,TaggedChoice$TaggedChoiceType,DynamicOps)
+ Pair lambda$makeRule$0(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Pair lambda$makeRule$1(Function,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Type lambda$makeRule$0(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,String)
```

</details>




































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ AABB getBoundingBoxForCulling()
- boolean considersEntityAsAlly(Entity)
- boolean isAffectedByBlocks()
- boolean lambda$applyEffectsFromBlocks$0(BlockState)
+ boolean lambda$move$0(BlockState)
- boolean teleportTo(ServerLevel,double,double,double,Set,float,float,boolean)
+ boolean teleportTo(ServerLevel,double,double,double,Set,float,float)
- float getXRot(float)
- float getYRot(float)
- Vec3 oldPosition()
- void applyEffectsFromBlocks()
- void applyMovementEmissionAndPlaySound(Entity$MovementEmission,Vec3,BlockPos,BlockState)
- void checkInsideBlocks(Set)
- void setOnGroundWithMovement(boolean,boolean,Vec3)
+ void setOnGroundWithMovement(boolean,Vec3)
- void teleportSetPosition(DimensionTransition)
+ void tryCheckInsideBlocks()
```

</details>






<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ AABB getBoundingBoxForCulling()
- boolean canContinueToGlide(ItemStack)
+ Boolean lambda$checkBedExists$7(BlockPos)
- Boolean lambda$checkBedExists$8(BlockPos)
+ boolean lambda$createEquipmentSlotAccess$10(LivingEntity,EquipmentSlot,ItemStack)
- boolean lambda$createEquipmentSlotAccess$12(LivingEntity,EquipmentSlot,ItemStack)
+ boolean lambda$isHolding$3(Item,ItemStack)
- boolean lambda$isHolding$4(Item,ItemStack)
- double getEffectiveGravity()
- ItemStack getItemHeldByArm(HumanoidArm)
+ Map activeLocationDependentEnchantments()
- Map activeLocationDependentEnchantments(EquipmentSlot)
- Reference2ObjectMap lambda$activeLocationDependentEnchantments$3(EquipmentSlot)
- Vec3 lambda$dismountVehicle$5(double,Vec3)
+ Vec3 lambda$stopSleeping$8(BlockPos)
- Vec3 lambda$stopSleeping$9(BlockPos)
- Vec3 updateFallFlyingMovement(Vec3)
- void dropFromShearingLootTable(ResourceKey,Consumer)
- void handleFallFlyingCollisions(double,double)
+ void lambda$collectEquipmentChanges$4(AttributeMap,ItemStack,EquipmentSlot,Holder,AttributeModifier)
+ void lambda$collectEquipmentChanges$5(ItemStack,EquipmentSlot,Holder,AttributeModifier)
- void lambda$collectEquipmentChanges$6(Holder,AttributeModifier)
+ void lambda$handleEquipmentChanges$6(List,EquipmentSlot,ItemStack)
- void lambda$handleEquipmentChanges$7(List,EquipmentSlot,ItemStack)
- void lambda$stopLocationBasedEffects$11(AttributeMap,Holder,AttributeModifier)
- void lambda$stopSleeping$10(BlockPos)
+ void lambda$stopSleeping$9(BlockPos)
- void stopLocationBasedEffects(ItemStack,EquipmentSlot,AttributeMap)
- void travelFallFlying()
- void travelInAir(Vec3)
- void travelInFluid(Vec3)
```

</details>

<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean checkMobSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkMobSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- boolean checkSpawnRules(LevelAccessor,EntitySpawnReason)
+ boolean checkSpawnRules(LevelAccessor,MobSpawnType)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- void onAttributeUpdated(Holder)
```

</details>









<details>
<summary>
net.minecraft.world.entity.TamableAnimal
</summary>

```diff
- boolean considersEntityAsAlly(Entity)
+ boolean isAlliedTo(Entity)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeInstance
</summary>

```diff
- Set getPermanentModifiers()
- void addPermanentModifiers(Collection)
```

</details>































































































































<details>
<summary>
net.minecraft.world.entity.ai.navigation.PathNavigation
</summary>

```diff
- float getMaxPathLength()
- void setRequiredPathLength(float)
- void updatePathfinderMaxVisitedNodes()
```

</details>











<details>
<summary>
net.minecraft.world.entity.ai.sensing.Sensor
</summary>

```diff
- boolean lambda$rememberPositives$1(Predicate,AtomicInteger,int,Object)
- boolean lambda$wasEntityAttackableLastNTicks$0(LivingEntity,LivingEntity)
- Predicate rememberPositives(int,Predicate)
- Predicate wasEntityAttackableLastNTicks(LivingEntity,int)
- void updateTargetingConditionRanges(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.TemptingSensor
</summary>

```diff
+ boolean lambda$doTick$0(PathfinderMob,ServerPlayer)
- boolean lambda$doTick$0(TargetingConditions,PathfinderMob,ServerPlayer)
+ boolean lambda$doTick$2(PathfinderMob,ServerPlayer)
```

</details>
































<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>





<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
- boolean checkZombieHorseSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkZombieHorseSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>








<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
+ double[] getLatencyPos(int,float)
+ float getHeadPartYOffset(int,double[],double[])
```

</details>









<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
+ float getHeadXRot(int)
+ float getHeadYRot(int)
- float[] getHeadXRots()
- float[] getHeadYRots()
```

</details>





<details>
<summary>
net.minecraft.world.entity.decoration.PaintingVariant
</summary>

```diff
- Optional author()
- Optional title()
- void <init>(int,int,ResourceLocation,Optional,Optional)
+ void <init>(int,int,ResourceLocation)
```

</details>

<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- boolean ignoreExplosion(Explosion)
- float getSpin(float,float)
+ float getSpin(float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.AbstractIllager
</summary>

```diff
- boolean considersEntityAsAlly(Entity)
+ boolean isAlliedTo(Entity)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.CaveSpider
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>







<details>
<summary>
net.minecraft.world.entity.monster.Endermite
</summary>

```diff
- boolean checkEndermiteSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkEndermiteSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Evoker
</summary>

```diff
- boolean considersEntityAsAlly(Entity)
+ boolean isAlliedTo(Entity)
```

</details>







<details>
<summary>
net.minecraft.world.entity.monster.Illusioner
</summary>

```diff
+ AABB getBoundingBoxForCulling()
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Monster
</summary>

```diff
- boolean checkAnyLightMonsterSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkAnyLightMonsterSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- boolean checkMonsterSpawnRules(EntityType,ServerLevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkMonsterSpawnRules(EntityType,ServerLevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>







<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ Optional getRenderPosition(float)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
- Vec3 getRenderPosition(float)
```

</details>












<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- boolean checkStriderSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkStriderSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Vindicator
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.WitherSkeleton
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
+ boolean supportsBreakDoorGoal()
- EntityType getType()
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- boolean checkZombifiedPiglinSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
+ boolean checkZombifiedPiglinSpawnRules(EntityType,LevelAccessor,MobSpawnType,BlockPos,RandomSource)
```

</details>









<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinBrute
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>












<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
+ SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData)
```

</details>












<details>
<summary>
net.minecraft.world.entity.player.Inventory
</summary>

```diff
- boolean isUsableForCrafting(ItemStack)
- ClientboundSetPlayerInventoryPacket createInventoryUpdatePacket(int)
- int findSlotMatchingCraftingIngredient(Holder)
+ int findSlotMatchingUnusedItem(ItemStack)
+ void <clinit>()
+ void fillStackedContents(StackedContents)
- void fillStackedContents(StackedItemContents)
- void setSelectedHotbarSlot(int)
+ void swapPaint(double)
```

</details>




<details>
<summary>
net.minecraft.world.entity.player.StackedContents
</summary>

```diff
+ boolean canCraft(Recipe,IntList,int)
+ boolean canCraft(Recipe,IntList)
+ boolean has(int)
- boolean hasAnyAmount(Object)
- boolean hasAtLeast(Object,int)
- boolean tryPick(List,int,StackedContents$Output)
+ int getBiggestCraftableStack(RecipeHolder,int,IntList)
+ int getBiggestCraftableStack(RecipeHolder,IntList)
+ int getStackingIndex(ItemStack)
+ int take(int,int)
- int tryPickAll(List,int,StackedContents$Output)
+ ItemStack fromStackingIndex(int)
- void account(Object,int)
+ void accountSimpleStack(ItemStack)
+ void accountStack(ItemStack,int)
+ void accountStack(ItemStack)
+ void put(int,int)
- void put(Object,int)
- void take(Object,int)
```

</details>



<details>
<summary>
net.minecraft.world.entity.projectile.ThrowableProjectile
</summary>

```diff
+ void <init>(EntityType,LivingEntity,Level)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
- Entity findOwner(UUID)
- void <init>(Level,LivingEntity,ItemStack)
+ void <init>(Level,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownPotion
</summary>

```diff
- void <init>(Level,double,double,double,ItemStack)
+ void <init>(Level,double,double,double)
- void <init>(Level,LivingEntity,ItemStack)
+ void <init>(Level,LivingEntity)
```

</details>


<details>
<summary>
net.minecraft.world.entity.projectile.windcharge.WindCharge
</summary>

```diff
- boolean shouldRenderAtSqrDistance(double)
```

</details>











<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartHopper
</summary>

```diff
- double makeStepAlongTrack(BlockPos,RailShape,double)
- void tryConsumeItems()
```

</details>









<details>
<summary>
net.minecraft.world.inventory.ChestMenu
</summary>

```diff
- void addChestGrid(Container,int,int)
```

</details>





<details>
<summary>
net.minecraft.world.inventory.CraftingMenu
</summary>

```diff
+ boolean recipeMatches(RecipeHolder)
+ boolean shouldMoveToInventory(int)
+ int getGridHeight()
+ int getGridWidth()
+ int getResultSlotIndex()
+ int getSize()
- List getInputGridSlots()
- Player owner()
- Slot getResultSlot()
+ void clearCraftingContent()
+ void fillCraftSlotsStackedContents(StackedContents)
```

</details>










<details>
<summary>
net.minecraft.world.inventory.InventoryMenu
</summary>

```diff
+ boolean recipeMatches(RecipeHolder)
+ boolean shouldMoveToInventory(int)
+ int getGridHeight()
+ int getGridWidth()
+ int getResultSlotIndex()
+ int getSize()
- List getInputGridSlots()
- Player owner()
- Slot getResultSlot()
+ void clearCraftingContent()
+ void fillCraftSlotsStackedContents(StackedContents)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.ItemCombinerMenu
</summary>

```diff
+ void createInventorySlots(Inventory)
```

</details>











<details>
<summary>
net.minecraft.world.inventory.RecipeBookMenu
</summary>

```diff
+ void beginPlacingRecipe()
+ void finishPlacingRecipe(RecipeHolder)
+ void handlePlacement(boolean,RecipeHolder,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.item.BottleItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.item.BrushItem
</summary>

```diff
+ boolean lambda$calculateHitResult$0(Entity)
```

</details>

<details>
<summary>
net.minecraft.world.item.BundleItem
</summary>

```diff
- boolean hasSelectedItem(ItemStack)
- int getBarColor(Fraction)
- int getNumberOfItemsToShow(ItemStack)
- int getSelectedItem(ItemStack)
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
- ItemStack getSelectedItemStack(ItemStack)
- String getOpenBundleModelBackLocation()
- String getOpenBundleModelFrontLocation()
+ void <init>(Item$Properties)
- void <init>(String,String,Item$Properties)
+ void appendHoverText(ItemStack,Item$TooltipContext,List,TooltipFlag)
- void playInsertFailSound(Entity)
- void toggleSelectedItem(ItemStack,int)
```

</details>






<details>
<summary>
net.minecraft.world.item.CrossbowItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>





<details>
<summary>
net.minecraft.world.item.EmptyMapItem
</summary>

```diff
- InteractionResult use(Level,Player,InteractionHand)
+ InteractionResultHolder use(Level,Player,InteractionHand)
```

</details>



<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ boolean lambda$getRecipeFor$0(RecipeInput,Level,RecipeHolder)
- boolean lambda$getRecipeFor$1(RecipeInput,Level,RecipeHolder)
+ boolean lambda$getRecipesFor$1(RecipeInput,Level,RecipeHolder)
- boolean lambda$getRecipesFor$2(RecipeInput,Level,RecipeHolder)
- boolean lambda$getSynchronizedRecipes$4(RecipeHolder)
- Collection getSynchronizedRecipes()
+ String lambda$getRecipesFor$2(Level,RecipeHolder)
- String lambda$getRecipesFor$3(Level,RecipeHolder)
- void lambda$logImpossibleRecipes$0(RecipeHolder)
- void logImpossibleRecipes()
```

</details>





<details>
<summary>
net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$9(RecordCodecBuilder$Instance)
+ boolean lambda$static$3(Ingredient)
- CraftingBookCategory lambda$static$6(ShapelessRecipe)
+ DataResult lambda$static$7(List)
+ Ingredient lambda$fromNetwork$10(RegistryFriendlyByteBuf,Ingredient)
+ Ingredient[] lambda$static$4(int)
- ItemStack lambda$static$7(ShapelessRecipe)
- List lambda$static$3(ShapelessRecipe)
- List lambda$static$8(ShapelessRecipe)
+ NonNullList lambda$static$8(ShapelessRecipe)
+ ShapelessRecipe fromNetwork(RegistryFriendlyByteBuf)
+ String lambda$static$5()
- String lambda$static$5(ShapelessRecipe)
+ String lambda$static$6()
+ void toNetwork(RegistryFriendlyByteBuf,ShapelessRecipe)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.SingleItemRecipe
</summary>

```diff
+ NonNullList getIngredients()
- PlacementInfo placementInfo()
```

</details>

<details>
<summary>
net.minecraft.world.item.crafting.SmeltingRecipe
</summary>

```diff
- ItemStack getCategoryIconItem()
+ ItemStack getToastSymbol()
```

</details>

<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
</summary>

```diff
+ Ingredient lambda$static$0(SmithingTransformRecipe)
+ Ingredient lambda$static$1(SmithingTransformRecipe)
+ Ingredient lambda$static$2(SmithingTransformRecipe)
- ItemStack lambda$static$8(SmithingTransformRecipe)
- Optional lambda$static$0(SmithingTransformRecipe)
- Optional lambda$static$1(SmithingTransformRecipe)
- Optional lambda$static$2(SmithingTransformRecipe)
- Optional lambda$static$5(SmithingTransformRecipe)
- Optional lambda$static$6(SmithingTransformRecipe)
- Optional lambda$static$7(SmithingTransformRecipe)
+ SmithingTransformRecipe fromNetwork(RegistryFriendlyByteBuf)
+ void toNetwork(RegistryFriendlyByteBuf,SmithingTransformRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
</summary>

```diff
+ Ingredient lambda$static$0(SmithingTrimRecipe)
+ Ingredient lambda$static$1(SmithingTrimRecipe)
+ Ingredient lambda$static$2(SmithingTrimRecipe)
- Optional lambda$static$0(SmithingTrimRecipe)
- Optional lambda$static$1(SmithingTrimRecipe)
- Optional lambda$static$2(SmithingTrimRecipe)
- Optional lambda$static$4(SmithingTrimRecipe)
- Optional lambda$static$5(SmithingTrimRecipe)
- Optional lambda$static$6(SmithingTrimRecipe)
+ SmithingTrimRecipe fromNetwork(RegistryFriendlyByteBuf)
+ void toNetwork(RegistryFriendlyByteBuf,SmithingTrimRecipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.StonecutterRecipe
</summary>

```diff
- ItemStack getCategoryIconItem()
+ ItemStack getToastSymbol()
```

</details>



<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
- ItemStack createBook(EnchantmentInstance)
+ void lambda$onProjectileSpawned$20(ServerLevel,EnchantedItemInUse,AbstractArrow,Holder,int)
- void lambda$onProjectileSpawned$20(ServerLevel,EnchantedItemInUse,Projectile,Holder,int)
+ void onProjectileSpawned(ServerLevel,ItemStack,AbstractArrow,Consumer)
- void onProjectileSpawned(ServerLevel,ItemStack,Projectile,Consumer)
```

</details>








<details>
<summary>
net.minecraft.world.level.Explosion
</summary>

```diff
+ boolean canTriggerBlocks()
+ boolean interactsWithBlocks()
+ Entity getDirectSourceEntity()
+ Explosion$BlockInteraction getBlockInteraction()
+ ExplosionDamageCalculator makeDamageCalculator(Entity)
+ float getSeenPercent(Vec3,Entity)
+ float radius()
+ Holder getExplosionSound()
+ List getToBlow()
+ LivingEntity getIndirectSourceEntity()
- LivingEntity getIndirectSourceEntity(Entity)
+ LivingEntity getIndirectSourceEntityInternal(Entity)
+ Map getHitPlayers()
+ ParticleOptions getLargeExplosionParticles()
+ ParticleOptions getSmallExplosionParticles()
+ Vec3 center()
+ void <clinit>()
+ void <init>(Level,Entity,DamageSource,ExplosionDamageCalculator,double,double,double,float,boolean,Explosion$BlockInteraction,ParticleOptions,ParticleOptions,Holder)
+ void <init>(Level,Entity,double,double,double,float,boolean,Explosion$BlockInteraction,List)
+ void <init>(Level,Entity,double,double,double,float,boolean,Explosion$BlockInteraction)
+ void <init>(Level,Entity,double,double,double,float,List,Explosion$BlockInteraction,ParticleOptions,ParticleOptions,Holder)
+ void addOrAppendStack(List,ItemStack,BlockPos)
+ void clearToBlow()
+ void explode()
+ void finalizeExplosion(boolean)
+ void lambda$finalizeExplosion$0(List,ItemStack,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.ExplosionDamageCalculator
</summary>

```diff
- float getEntityDamageAmount(Explosion,Entity,float)
+ float getEntityDamageAmount(Explosion,Entity)
```

</details>














<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- List getFilteredSpawningCategories(NaturalSpawner$SpawnState,boolean,boolean,boolean)
+ void spawnForChunk(ServerLevel,LevelChunk,NaturalSpawner$SpawnState,boolean,boolean,boolean)
- void spawnForChunk(ServerLevel,LevelChunk,NaturalSpawner$SpawnState,List)
```

</details>

<details>
<summary>
net.minecraft.world.level.NaturalSpawner$SpawnState
</summary>

```diff
+ boolean canSpawnForCategory(MobCategory,ChunkPos)
- boolean canSpawnForCategoryGlobal(MobCategory)
- boolean canSpawnForCategoryLocal(MobCategory,ChunkPos)
```

</details>












<details>
<summary>
net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
</summary>

```diff
+ BiomeGenerationSettings$Builder addCarver(GenerationStep$Carving,ResourceKey)
- BiomeGenerationSettings$Builder addCarver(ResourceKey)
```

</details>























<details>
<summary>
net.minecraft.world.level.block.AbstractCauldronBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.AzaleaBlock
</summary>

```diff
- boolean isPathfindable(BlockState,PathComputationType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooStalkBlock
</summary>

```diff
+ boolean propagatesSkylightDown(BlockState,BlockGetter,BlockPos)
- boolean propagatesSkylightDown(BlockState)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ void updateEntityAfterFallOn(BlockGetter,Entity)
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- InteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ ItemInteractionResult useItemOn(ItemStack,BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- void onExplosionHit(BlockState,ServerLevel,BlockPos,Explosion,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
+ void onExplosionHit(BlockState,Level,BlockPos,Explosion,BiConsumer)
- void onExplosionHit(BlockState,ServerLevel,BlockPos,Explosion,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BigDripleafBlock
</summary>

```diff
+ void neighborChanged(BlockState,Level,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,Level,BlockPos,Block,Orientation,boolean)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ boolean shouldRenderFace(BlockState,BlockGetter,BlockPos,Direction,BlockPos)
- boolean shouldRenderFace(BlockState,BlockState,Direction)
+ void updateEntityAfterFallOn(BlockGetter,Entity)
- void updateEntityMovementAfterFallOn(BlockGetter,Entity)
+ void wasExploded(Level,BlockPos,Explosion)
- void wasExploded(ServerLevel,BlockPos,Explosion)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.entity.CrafterBlockEntity
</summary>

```diff
+ void fillStackedContents(StackedContents)
- void fillStackedContents(StackedItemContents)
```

</details>


















<details>
<summary>
net.minecraft.world.level.block.entity.SmokerBlockEntity
</summary>

```diff
- int getBurnDuration(FuelValues,ItemStack)
+ int getBurnDuration(ItemStack)
```

</details>
































<details>
<summary>
net.minecraft.world.level.block.state.StateHolder
</summary>

```diff
- Comparable getNullableValue(Property)
- Comparable getValueOrElse(Property,Comparable)
```

</details>























<details>
<summary>
net.minecraft.world.level.border.WorldBorder
</summary>

```diff
- Vec3 clampVec3ToBound(double,double,double)
- Vec3 clampVec3ToBound(Vec3)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ void addPackedPostProcess(short,int)
- void addPackedPostProcess(ShortList,int)
+ void setBlendingData(BlendingData)
```

</details>



<details>
<summary>
net.minecraft.world.level.chunk.GlobalPalette
</summary>

```diff
+ Palette copy()
- Palette copy(PaletteResize)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
- CarvingMask getCarvingMask()
+ CarvingMask getCarvingMask(GenerationStep$Carving)
- CarvingMask getOrCreateCarvingMask()
+ CarvingMask getOrCreateCarvingMask(GenerationStep$Carving)
- ChunkAccess$PackedTicks getTicksForSerialization(long)
+ ChunkAccess$TicksToSave getTicksForSerialization()
+ int getMaxLightLevel()
+ void setBlendingData(BlendingData)
```

</details>







<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
- void <init>(PalettedContainer)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- CarvingMask getCarvingMask()
+ CarvingMask getCarvingMask(GenerationStep$Carving)
- CarvingMask getOrCreateCarvingMask()
+ CarvingMask getOrCreateCarvingMask(GenerationStep$Carving)
+ CarvingMask lambda$getOrCreateCarvingMask$0(GenerationStep$Carving)
- ChunkAccess$PackedTicks getTicksForSerialization(long)
+ ChunkAccess$TicksToSave getTicksForSerialization()
+ void addPackedPostProcess(short,int)
- void addPackedPostProcess(ShortList,int)
- void setCarvingMask(CarvingMask)
+ void setCarvingMask(GenerationStep$Carving,CarvingMask)
```

</details>














<details>
<summary>
net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
</summary>

```diff
+ CompletableFuture write(ChunkPos,CompoundTag)
- CompletableFuture write(ChunkPos,Supplier)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
- CompletableFuture lambda$prefetch$2(ChunkPos,long)
- CompletableFuture lambda$unpackChunk$3(ChunkPos,long)
- CompletableFuture prefetch(ChunkPos)
- Dynamic writeChunk(ChunkPos,DynamicOps)
+ Dynamic writeColumn(ChunkPos,DynamicOps)
- Object lambda$unpackChunk$8(long,Object)
+ Optional lambda$readColumn$3(long,Dynamic)
+ Optional lambda$tryRead$1(ChunkPos,Throwable)
- Optional lambda$tryRead$5(RegistryOps,Optional)
- Optional lambda$tryRead$6(ChunkPos,Throwable)
- SectionStorage$PackedChunk lambda$tryRead$4(RegistryOps,CompoundTag)
- void <init>(SimpleRegionStorage,Codec,Function,BiFunction,Function,RegistryAccess,ChunkIOErrorReporter,LevelHeightAccessor)
+ void <init>(SimpleRegionStorage,Function,Function,RegistryAccess,ChunkIOErrorReporter,LevelHeightAccessor)
- void flushAll()
- void lambda$flushAll$0(long)
+ void lambda$getOrCreate$0(long)
- void lambda$getOrCreate$1(long)
+ void lambda$readColumn$2(long)
+ void lambda$readColumn$4(long,boolean,Object)
- void lambda$unpackChunk$7(long)
- void lambda$unpackChunk$9(long,boolean,Object)
- Void lambda$writeChunk$10(ChunkPos,Throwable)
- void lambda$writeChunk$11(Map,DynamicOps,String,Object)
+ Void lambda$writeColumn$5(ChunkPos,Throwable)
+ void lambda$writeColumn$6(long)
+ void lambda$writeColumn$7(Map,DynamicOps,String,Object)
+ void readColumn(ChunkPos,RegistryOps,CompoundTag)
+ void readColumn(ChunkPos)
- void unpackChunk(ChunkPos,SectionStorage$PackedChunk)
- void unpackChunk(ChunkPos)
- void unpackPendingLoads()
- void writeChunk(ChunkPos)
+ void writeColumn(ChunkPos)
```

</details>



































<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$FluidStatus
</summary>

```diff
- BlockState fluidType()
- boolean equals(Object)
- int fluidLevel()
- int hashCode()
- String toString()
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess)
```

</details>





















<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess)
```

</details>



















































































































<details>
<summary>
net.minecraft.world.level.levelgen.material.MaterialRuleList
</summary>

```diff
+ List materialRuleList()
- NoiseChunk$BlockStateFiller[] materialRuleList()
+ void <init>(List)
- void <init>(NoiseChunk$BlockStateFiller[])
```

</details>


<details>
<summary>
net.minecraft.world.level.material.FluidState
</summary>

```diff
- void tick(Level,BlockPos,BlockState)
+ void tick(Level,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.material.MapColor
</summary>

```diff
- int calculateARGBColor(MapColor$Brightness)
+ int calculateRGBColor(MapColor$Brightness)
```

</details>







<details>
<summary>
net.minecraft.world.level.pathfinder.PathFinder
</summary>

```diff
- void setMaxVisitedNodes(int)
```

</details>






<details>
<summary>
net.minecraft.world.level.redstone.CollectingNeighborUpdater
</summary>

```diff
+ void neighborChanged(BlockPos,Block,BlockPos)
- void neighborChanged(BlockPos,Block,Orientation)
+ void neighborChanged(BlockState,BlockPos,Block,BlockPos,boolean)
- void neighborChanged(BlockState,BlockPos,Block,Orientation,boolean)
- void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction,Orientation)
+ void updateNeighborsAtExceptFromFacing(BlockPos,Block,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
</summary>

```diff
+ void <init>(BlockPos,Block,Direction)
- void <init>(BlockPos,Block,Orientation,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.level.saveddata.SavedData
</summary>

```diff
- CompoundTag save(HolderLookup$Provider)
+ void <clinit>()
+ void save(File,HolderLookup$Provider)
```

</details>




<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- boolean isInsideMap(float,float)
- byte calculateRotation(LevelAccessor,double)
- byte clampMapCoordinate(float)
- Holder decorationTypeForPlayerOutsideMap(float,float)
- MapItemSavedData$MapDecorationLocation calculateDecorationLocationAndType(Holder,LevelAccessor,double,float,float)
- Pair playerDecorationTypeAndRotation(Holder,LevelAccessor,double,float,float)
```

</details>






<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
- boolean lambda$new$2(FluidState)
- void <init>(Entity,boolean)
+ void <init>(Entity)
```

</details>



<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
+ VoxelShape getFaceShape(VoxelShape,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.VoxelShape
</summary>

```diff
- boolean isCubeLike()
- boolean isCubeLikeAlong(Direction$Axis)
```

</details>














<details>
<summary>
net.minecraft.world.ticks.LevelChunkTicks
</summary>

```diff
- List pack(long)
+ Tag save(long,Function)
```

</details>

<details>
<summary>
net.minecraft.world.ticks.ProtoChunkTicks
</summary>

```diff
- List pack(long)
- ProtoChunkTicks load(List)
+ ProtoChunkTicks load(ListTag,Function,ChunkPos)
+ Tag save(long,Function)
```

</details>
</details>