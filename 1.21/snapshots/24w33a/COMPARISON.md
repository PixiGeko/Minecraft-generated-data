## Comparison with [1.21.1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.1)

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
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>DataPack version</td><td><pre>48</pre></td><td><pre>49</pre></td></tr><tr><td>ResourcePack version</td><td><pre>34</pre></td><td><pre>35</pre></td></tr><tr><td>World version</td><td><pre>3955</pre></td><td><pre>4058</pre></td></tr><tr><td>Protocol version</td><td><pre>767</pre></td><td><pre>1073742029</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ com.fasterxml.jackson.core:jackson-annotations V2.13.4
+ com.fasterxml.jackson.core:jackson-core V2.13.4
+ com.fasterxml.jackson.core:jackson-databind V2.13.4.2
+ com.github.stephenc.jcip:jcip-annotations V1.0-1
+ com.microsoft.azure:msal4j V1.15.0
+ com.nimbusds:content-type V2.3
+ com.nimbusds:lang-tag V1.7
+ com.nimbusds:nimbus-jose-jwt V9.37.3
+ com.nimbusds:oauth2-oidc-sdk V11.9.1
+ net.minidev:accessors-smart V2.5.0
+ net.minidev:json-smart V2.5.0
+ org.ow2.asm:asm V9.3
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>com.mojang:authlib</td><td><pre>6.0.54</pre></td><td><pre>6.0.55</pre></td></tr></table>
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
- instrument.txt
```

</details>
<details>
<summary>
attribute
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
data_component_type
</summary>

```diff
+ minecraft:enchantable
+ minecraft:repairable
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:bordure_indented_banner_pattern
+ minecraft:field_masoned_banner_pattern
```

</details>
<details>
<summary>
recipe_serializer
</summary>

```diff
- minecraft:crafting_special_suspiciousstew
```

</details>
<details>
<summary>
sound_event
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
worldgen/placement_modifier_type
</summary>

```diff
- minecraft:carving_mask
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
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ bordure_indented_banner_pattern.json
+ field_masoned_banner_pattern.json
```

</details>
<details>
<summary>
angler_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
archer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arms_up_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blade_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bolt_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
burn_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coast_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crossbow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
danger_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:diamond_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 8,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:diamond_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": 0,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:diamond_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 4,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:diamond_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 4.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:diamond_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 6,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
disc_fragment_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>uncommon</pre></td><td><pre>epic</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dune_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
echo_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elytra
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "minecraft:phantom_membrane"
}</pre></td></tr><tr><td>minecraft:rarity</td><td><pre>uncommon</pre></td><td><pre>epic</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>epic</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:container</td><td><pre>[]</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_crystal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>common</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
explorer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
eye_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fishing_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
friend_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_horn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>common</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 22
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:gold_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 6,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 22
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:gold_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 22
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:gold_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 1,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 22
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:gold_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 1.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 22
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:gold_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 3,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heartbreak_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
host_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
howl_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 14
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:iron_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 8,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3.0999999046325684,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 14
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:iron_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -1,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 14
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:iron_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 3,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 14
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:iron_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 3.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 14
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:iron_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "minecraft:breeze_rod"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
miner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mojang_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>epic</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mourner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_11
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_13
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_blocks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_cat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_chirp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator_music_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_far
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mellohi
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_precipice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_relic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_stal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_strad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_wait
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_ward
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>rare</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nautilus_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:netherite_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 9,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:netherite_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": 0,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:netherite_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:netherite_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 5.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:netherite_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 7,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_upgrade_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>uncommon</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
plenty_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prize_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raiser_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
recovery_compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rib_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scrape_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sentry_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shaper_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheaf_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelter_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shield
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silence_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>epic</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>uncommon</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snort_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snout_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spire_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 5
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:stone_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 8,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3.200000047683716,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 5
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:stone_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 5
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:stone_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 2,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 5
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:stone_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 2.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 5
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:stone_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 4,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tide_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 1
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 8,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.9000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr><tr><td>minecraft:rarity</td><td><pre>epic</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ward_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wild_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>common</pre></td><td><pre>uncommon</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:rarity</td><td><pre>uncommon</pre></td><td><pre>rare</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 6,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3.200000047683716,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 0,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 1,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.799999952316284,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 1.5,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -3,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr><tr><td>minecraft:repairable</td><td><pre>/</pre></td><td><pre>{
  "items": "#minecraft:wooden_tool_materials"
}</pre></td></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>{
  "modifiers": [
    {
      "type": "minecraft:generic.attack_damage",
      "amount": 3,
      "id": "minecraft:base_attack_damage",
      "operation": "add_value",
      "slot": "mainhand"
    },
    {
      "type": "minecraft:generic.attack_speed",
      "amount": -2.4000000953674316,
      "id": "minecraft:base_attack_speed",
      "operation": "add_value",
      "slot": "mainhand"
    }
  ]
}</pre></td><td><pre>{
  "modifiers": [
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
  ]
}</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>brush_completed_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.gravel.complete</pre></td></tr><tr><td>brush_comleted_sound</td><td><pre>minecraft:item.brush.brushing.gravel.complete</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.1</th><th>24w33a</th></tr><tr><td>brush_completed_sound</td><td><pre>/</pre></td><td><pre>minecraft:item.brush.brushing.sand.complete</pre></td></tr><tr><td>brush_comleted_sound</td><td><pre>minecraft:item.brush.brushing.sand.complete</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<br/>
<table>
<tr><th>Name</th><th>1.21.1</th><th>24w33a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.trim_with_any_armor_pattern.description</div></th><td>Craft a trimmed armor at a Smithing Table</td><td>Craft trimmed armor at a Smithing Table</td></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.repair_wolf_armor.description</div></th><td>Repair a damaged Wolf Armor using Armadillo Scutes</td><td>Fully repair damaged Wolf Armor using Armadillo Scutes</td></tr>
<tr><th align="left"><div style="width:290px">chat.queue</div></th><td>[+%s pending lines]</td><td>[+%s pending line(s)]</td></tr>
<tr><th align="left"><div style="width:290px">commands.debug.stopped</div></th><td>Stopped tick profiling after %s seconds and %s ticks (%s ticks per second)</td><td>Stopped tick profiling after %s second(s) and %s tick(s) (%s tick(s) per second)</td></tr>
<tr><th align="left"><div style="width:290px">commands.schedule.created.tag</div></th><td>Scheduled tag '%s' in %s ticks at gametime %s</td><td>Scheduled tag '%s' in %s tick(s) at gametime %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.spreadplayers.success.entities</div></th><td>Spread %s player(s) around %s, %s with an average distance of %s blocks apart</td><td>Spread %s entity/entities around %s, %s with an average distance of %s block(s) apart</td></tr>
<tr><th align="left"><div style="width:290px">commands.spreadplayers.success.teams</div></th><td>Spread %s team(s) around %s, %s with an average distance of %s blocks apart</td><td>Spread %s team(s) around %s, %s with an average distance of %s block(s) apart</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.name.title</div></th><td>Report Player Name</td><td>Report Inappropriate Player Name</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.report_sent_msg</div></th><td>We’ve successfully received your report. Thank you!



Our team will review it as soon as possible.</td><td>We've successfully received your report. Thank you!



Our team will review it as soon as possible.</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.description.permanent</div></th><td>Your account is permanently banned, which means you can’t play online or join Realms.</td><td>Your account is permanently banned, which means you can't play online or join Realms.</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.description.temporary</div></th><td>%s Until then, you can’t play online or join Realms.</td><td>%s Until then, you can't play online or join Realms.</td></tr>
<tr><th align="left"><div style="width:290px">gui.chatReport.report_sent_msg</div></th><td>We’ve successfully received your report. Thank you!



Our team will review it as soon as possible.</td><td>We've successfully received your report. Thank you!



Our team will review it as soon as possible.</td></tr>
<tr><th align="left"><div style="width:290px">gui.fileDropFailure.detail</div></th><td>Rejected %d files</td><td>Rejected %s files</td></tr>
<tr><th align="left"><div style="width:290px">key.back</div></th><td>Walk Backwards</td><td>Walk Backward</td></tr>
<tr><th align="left"><div style="width:290px">key.forward</div></th><td>Walk Forwards</td><td>Walk Forward</td></tr>
<tr><th align="left"><div style="width:290px">mco.account.privacy.information</div></th><td>Mojang implements certain procedures to help protect children and their privacy including complying with the Children’s Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).



You may need to obtain parental consent before accessing your Realms account.</td><td>Mojang implements certain procedures to help protect children and their privacy including complying with the Children's Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).



You may need to obtain parental consent before accessing your Realms account.</td></tr>
<tr><th align="left"><div style="width:290px">mco.account.privacyinfo</div></th><td>Mojang implements certain procedures to help protect children and their privacy including complying with the Children’s Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).



You may need to obtain parental consent before accessing your Realms account.



If you have an older Minecraft account (you log in with your username), you need to migrate the account to a Mojang account in order to access Realms.</td><td>Mojang implements certain procedures to help protect children and their privacy including complying with the Children's Online Privacy Protection Act (COPPA) and General Data Protection Regulation (GDPR).



You may need to obtain parental consent before accessing your Realms account.



If you have an older Minecraft account (you log in with your username), you need to migrate the account to a Mojang account in order to access Realms.</td></tr>
<tr><th align="left"><div style="width:290px">narration.suggestion</div></th><td>Selected suggestion %d out of %d: %s</td><td>Selected suggestion %s out of %s: %s</td></tr>
<tr><th align="left"><div style="width:290px">narration.suggestion.tooltip</div></th><td>Selected suggestion %d out of %d: %s (%s)</td><td>Selected suggestion %s out of %s: %s (%s)</td></tr>
<tr><th align="left"><div style="width:290px">options.chat.delay</div></th><td>Chat Delay: %s seconds</td><td>Chat Delay: %s second(s)</td></tr>
<tr><th align="left"><div style="width:290px">telemetry.event.world_load_times.description</div></th><td>It’s important for us to understand how long it takes to join a world, and how that changes over time. For example, when we add new features or do larger technical changes, we need to see what impact that had on load times.</td><td>It's important for us to understand how long it takes to join a world, and how that changes over time. For example, when we add new features or do larger technical changes, we need to see what impact that had on load times.</td></tr>
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
+ minecraft:move_minecart_along_track
- minecraft:set_carried_item
+ minecraft:set_cursor_item
+ minecraft:set_held_slot
+ minecraft:set_player_inventory
```

</details>
<details>
<summary>
[server] play
</summary>

```diff
+ minecraft:bundle_item_selected
+ minecraft:client_tick_end
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.Attribute$Sentiment
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorControl
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CountDownCooldownTicks
- XXX.ai.behavior.Croak
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.GoToPotentialJobSite
+ XXX.ai.behavior.GoToTargetLocation
- XXX.ai.behavior.GoToWantedItem
+ XXX.ai.behavior.HarvestFarmland
- XXX.ai.behavior.InsideBrownianWalk
+ XXX.ai.behavior.InteractWith
- XXX.ai.behavior.InteractWithDoor
+ XXX.ai.behavior.JumpOnBed
- XXX.ai.behavior.LocateHidingPlace
+ XXX.ai.behavior.LongJumpMidJump
- XXX.ai.behavior.LongJumpToPreferredBlock
+ XXX.ai.behavior.LongJumpToRandomPos
- XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
+ XXX.ai.behavior.LongJumpUtil
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
+ XXX.arguments.selector.package-info
- XXX.arguments.selector.SelectorPattern
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
+ XXX.block.entity.DecoratedPotPattern
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantingTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FuelValues
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
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.entity.TrialSpawnerBlockEntity
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
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
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
+ XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
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
- XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$SectionData
+ XXX.chunk.storage.SimpleRegionStorage
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
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.data.info.DatapackStructureReport
- XXX.data.info.DatapackStructureReport$Entry
- XXX.data.info.DatapackStructureReport$Report
+ XXX.data.info.ItemListReport
- XXX.data.info.package-info
- XXX.data.info.PacketReport
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$SubProviderEntry
+ XXX.data.loot.LootTableSubProvider
- XXX.data.loot.package-info
+ XXX.data.recipes.RecipeProvider$1
- XXX.data.recipes.RecipeProvider$FamilyRecipeProvider
- XXX.data.recipes.RecipeProvider$Runner$1
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
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
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CarvingStepRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropInvalidSignDataFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EffectDurationFix
- XXX.datafix.fixes.EmptyItemInHotbarFix
+ XXX.datafix.fixes.EmptyItemInVillagerTradeFix
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
+ XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
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
- XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
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
- XXX.entity.animal.Bee$ValidateHiveGoal
- XXX.entity.animal.package-info
- XXX.entity.animal.Salmon$Variant
+ XXX.entity.animal.Sheep
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$1
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
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.Bogged
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
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$ShulkerAttackGoal
- XXX.entity.monster.Shulker$ShulkerBodyRotationControl
+ XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
- XXX.entity.monster.Shulker$ShulkerLookControl
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Strider
+ XXX.entity.monster.Strider$StriderGoToLavaGoal
- XXX.entity.monster.Strider$StriderPathNavigation
+ XXX.entity.monster.Vex
- XXX.entity.monster.Vex$VexChargeAttackGoal
+ XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
- XXX.entity.monster.Vex$VexMoveControl
+ XXX.entity.monster.Vex$VexRandomMoveGoal
- XXX.entity.monster.Vindicator
+ XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
- XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
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
- XXX.entity.npc.VillagerTrades$FailureItemListing
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerTrades$TypeSpecificTrade
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
+ XXX.entity.projectile.package-info
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
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
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
- XXX.entity.trialspawner.package-info
+ XXX.entity.trialspawner.PlayerDetector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
+ XXX.entity.trialspawner.TrialSpawner
- XXX.entity.trialspawner.TrialSpawner$FlameParticle
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerData
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
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
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior$1
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
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
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
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestRunner$Builder
- XXX.gametest.framework.GameTestRunner$GameTestBatcher
+ XXX.gametest.framework.GameTestRunner$StructureSpawner
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
- XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.RetryOptions
+ XXX.gametest.framework.StructureBlockPosFinder
- XXX.gametest.framework.StructureGridSpawner
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$Runner
- XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFinder
+ XXX.gametest.framework.TestFinder$Builder
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestFunctionFinder
+ XXX.gametest.framework.TestReporter
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
+ XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.PlacementInfo$SlotInfo
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeInput
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapedRecipePattern
- XXX.item.crafting.ShapedRecipePattern$Data
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCraftingRecipeSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Factory
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleRecipeInput
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingRecipeInput
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
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
+ XXX.level.block.AmethystClusterBlock$1
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
- XXX.level.block.Block$ShapePairKey
+ XXX.level.block.package-info
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$TicksToSave
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
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
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
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
+ XXX.level.levelgen.package-info
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
+ XXX.level.portal.DimensionTransition
- XXX.level.portal.DimensionTransition$PostDimensionTransition
+ XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalShape
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
- XXX.level.redstone.ExperimentalRedstoneWireEvaluator
- XXX.level.redstone.Orientation$SideBias
+ XXX.level.redstone.package-info
- XXX.level.redstone.RedstoneWireEvaluator
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Factory
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
+ XXX.minecraft.commands.package-info
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
+ XXX.minecraft.core.HolderLookup$Provider$2
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
- XXX.minecraft.core.MappedRegistry$4
- XXX.minecraft.core.MappedRegistry$TagSet$1
+ XXX.minecraft.core.Registry$2
- XXX.minecraft.core.Registry$PendingTags
- XXX.minecraft.network.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.PlaceRecipeHelper
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.package-info
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
+ XXX.minecraft.resources.ResourceLocation$Serializer
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
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$Data
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerRegistries
+ XXX.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- XXX.minecraft.server.ReloadableServerRegistries$LoadResult
+ XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- XXX.minecraft.server.SuppressedExceptionCollector
- XXX.minecraft.server.SuppressedExceptionCollector$ShortEntry
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
- XXX.minecraft.tags.TagLoader$LoadResult
+ XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.ARGB
+ XXX.minecraft.util.ArrayListDeque
- XXX.minecraft.util.ArrayListDeque$DescendingIterator
+ XXX.minecraft.util.ArrayListDeque$ReversedView
- XXX.minecraft.util.BinaryAnimator
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
+ XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FastColor$ABGR32
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.InteractionResult$Fail
- XXX.minecraft.world.InteractionResult$Pass
- XXX.minecraft.world.InteractionResult$SwingSource
+ XXX.minecraft.world.InteractionResultHolder
+ XXX.monster.breeze.Breeze
- XXX.monster.breeze.Breeze$1
+ XXX.monster.breeze.BreezeAi
- XXX.monster.breeze.BreezeAi$SlideToTargetSink
+ XXX.monster.breeze.BreezeUtil
- XXX.monster.breeze.LongJump
- XXX.monster.breeze.package-info
+ XXX.monster.breeze.Shoot
- XXX.monster.breeze.ShootWhenStuck
+ XXX.monster.breeze.Slide
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
+ XXX.monster.warden.Warden$VibrationUser
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
- XXX.network.codec.ByteBufCodecs$29
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
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
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
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketType
- XXX.network.protocol.PacketUtils
+ XXX.network.protocol.ProtocolCodecBuilder
- XXX.network.protocol.ProtocolInfoBuilder
+ XXX.network.protocol.ProtocolInfoBuilder$1
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
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
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
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
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
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
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetHeldSlotPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientGamePacketListener
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
- XXX.protocol.game.ServerboundSelectBundleItemPacket
- XXX.recipes.packs.BundleRecipeProvider$Runner
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$Runner
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
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
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
+ XXX.server.commands.CloneCommands$CloneBlockEntityInfo
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
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
+ XXX.server.commands.ExecuteCommand$CommandGetter
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
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
- XXX.server.commands.ItemCommands
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.package-info
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
- XXX.server.commands.SetBlockCommand$Filter
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
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TeleportCommand$LookAtEntity
- XXX.server.commands.TeleportCommand$LookAtPosition
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TickCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TransferCommand
- XXX.server.commands.TriggerCommand
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
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.GeneratingChunkMap
- XXX.server.level.GenerationChunkHolder
- XXX.server.level.package-info
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayer$RespawnPosAngle
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TickingTracker
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.CommonListenerCookie
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.LegacyTextFilter
- XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
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
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.ServerTextFilter
- XXX.server.network.ServerTextFilter$MessageEncoder
- XXX.server.network.ServerTextFilter$RequestFailedException
+ XXX.server.network.TextFilterClient$IgnoreStrategy
+ XXX.server.network.TextFilterClient$MessageEncoder
+ XXX.server.network.TextFilterClient$RequestFailedException
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
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.NoteBlockInstrument$Type
- XXX.state.properties.package-info
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
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
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
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiRecord$Packed
- XXX.village.poi.PoiSection$Packed
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityAttachment
- XXX.world.entity.EntityAttachment$Fallback
+ XXX.world.entity.EntityAttachments
- XXX.world.entity.EntityAttachments$Builder
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
+ XXX.world.entity.package-info
+ XXX.world.entity.PowerableMob
- XXX.world.entity.RelativeMovement
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.Saddleable
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
- XXX.world.entity.VariantHolder
+ XXX.world.entity.WalkAnimationState
- XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
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
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
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
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
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
- XXX.world.inventory.NonInteractiveResultSlot
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
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
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
+ XXX.world.item.TieredItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
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
+ XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerExplosion$StackCollector
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SimpleExplosionDamageCalculator
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
- XXX.world.phys.package-info
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.ScoreboardSaveData
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.Optionull
- net.minecraft.package-info
+ net.minecraft.ReportedException
- net.minecraft.ReportType
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
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
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
- net.minecraft.WorldVersion
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
- XXX.advancements.critereon.GameTypePredicate
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
- XXX.advancements.critereon.ItemAttributeModifiersPredicate
+ XXX.advancements.critereon.ItemAttributeModifiersPredicate$EntryPredicate
- XXX.advancements.critereon.ItemBundlePredicate
+ XXX.advancements.critereon.ItemContainerPredicate
- XXX.advancements.critereon.ItemCustomDataPredicate
+ XXX.advancements.critereon.ItemDamagePredicate
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemEnchantmentsPredicate
+ XXX.advancements.critereon.ItemEnchantmentsPredicate$Enchantments
- XXX.advancements.critereon.ItemEnchantmentsPredicate$StoredEnchantments
+ XXX.advancements.critereon.ItemFireworkExplosionPredicate
- XXX.advancements.critereon.ItemFireworkExplosionPredicate$FireworkPredicate
+ XXX.advancements.critereon.ItemFireworksPredicate
- XXX.advancements.critereon.ItemJukeboxPlayablePredicate
+ XXX.advancements.critereon.ItemPotionsPredicate
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemSubPredicate
+ XXX.advancements.critereon.ItemSubPredicate$Type
- XXX.advancements.critereon.ItemSubPredicates
+ XXX.advancements.critereon.ItemTrimPredicate
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- XXX.advancements.critereon.ItemWritableBookPredicate
+ XXX.advancements.critereon.ItemWritableBookPredicate$PagePredicate
- XXX.advancements.critereon.ItemWrittenBookPredicate
+ XXX.advancements.critereon.ItemWrittenBookPredicate$PagePredicate
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
- XXX.advancements.critereon.MovementPredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.package-info
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
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
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
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
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
- XXX.blaze3d.font.package-info
- XXX.blaze3d.framegraph.FrameGraphBuilder$ExternalResource
- XXX.blaze3d.framegraph.FrameGraphBuilder$Inspector
- XXX.blaze3d.framegraph.FrameGraphBuilder$InternalVirtualResource
- XXX.blaze3d.framegraph.FrameGraphBuilder$VirtualResource
- XXX.blaze3d.framegraph.package-info
- XXX.blaze3d.pipeline.MainTarget
+ XXX.blaze3d.pipeline.MainTarget$AttachmentState
- XXX.blaze3d.pipeline.MainTarget$Dimension
+ XXX.blaze3d.pipeline.RenderCall
- XXX.blaze3d.platform.ClipboardManager
+ XXX.blaze3d.platform.DebugMemoryUntracker
- XXX.blaze3d.platform.DisplayData
- XXX.blaze3d.platform.GlStateManager$FramebufferState
+ XXX.blaze3d.platform.GlStateManager$LogicOp
- XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.platform.GlStateManager$ScissorState
- XXX.blaze3d.platform.GlStateManager$SourceFactor
+ XXX.blaze3d.platform.GlStateManager$StencilFunc
- XXX.blaze3d.platform.GlStateManager$StencilState
+ XXX.blaze3d.platform.GlStateManager$TextureState
- XXX.blaze3d.platform.GlStateManager$Viewport
+ XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.IconSet
+ XXX.blaze3d.platform.InputConstants
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.MacosUtil
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.Window$WindowInitFailed
+ XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.preprocessor.GlslPreprocessor
- XXX.blaze3d.preprocessor.GlslPreprocessor$Context
+ XXX.blaze3d.preprocessor.package-info
- XXX.blaze3d.resource.CrossFrameResourcePool
- XXX.blaze3d.resource.GraphicsResourceAllocator
- XXX.blaze3d.resource.RenderTargetDescriptor
- XXX.blaze3d.resource.ResourceHandle
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.BlendMode
- XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.EffectProgram
- XXX.blaze3d.shaders.EffectProgram$1
+ XXX.blaze3d.shaders.FogShape
+ XXX.blaze3d.shaders.package-info
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Shader
- XXX.blaze3d.shaders.Uniform
+ XXX.blaze3d.systems.package-info
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.systems.RenderSystem$1
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- XXX.blaze3d.systems.TimerQuery
+ XXX.blaze3d.systems.TimerQuery$FrameProfile
- XXX.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- XXX.blaze3d.vertex.BufferBuilder
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.ByteBufferBuilder
+ XXX.blaze3d.vertex.ByteBufferBuilder$Result
- XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.MeshData
- XXX.blaze3d.vertex.MeshData$1
+ XXX.blaze3d.vertex.MeshData$DrawState
- XXX.blaze3d.vertex.MeshData$SortState
+ XXX.blaze3d.vertex.package-info
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$Pose
+ XXX.blaze3d.vertex.SheetedDecalTextureGenerator
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexBuffer$Usage
+ XXX.blaze3d.vertex.VertexConsumer
- XXX.blaze3d.vertex.VertexFormat
+ XXX.blaze3d.vertex.VertexFormat$Builder
- XXX.blaze3d.vertex.VertexFormat$IndexType
+ XXX.blaze3d.vertex.VertexFormat$Mode
- XXX.blaze3d.vertex.VertexFormatElement
+ XXX.blaze3d.vertex.VertexFormatElement$Type
- XXX.blaze3d.vertex.VertexFormatElement$Usage
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
+ XXX.blaze3d.vertex.VertexSorting
- XXX.blaze3d.vertex.VertexSorting$DistanceFunction
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
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
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
- XXX.block.entity.BlockEntity$DataComponentInput
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.FuelValues
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
- XXX.block.model.package-info
- XXX.block.model.UnbakedBlockStateModel
+ XXX.block.model.Variant
- XXX.block.model.Variant$Deserializer
- XXX.boss.enderdragon.DragonFlightHistory$Sample
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.DataSource$Type
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
- XXX.chat.numbers.BlankFormat
+ XXX.chat.numbers.BlankFormat$1
- XXX.chat.numbers.FixedFormat
+ XXX.chat.numbers.FixedFormat$1
- XXX.chat.numbers.NumberFormat
+ XXX.chat.numbers.NumberFormatType
- XXX.chat.numbers.NumberFormatTypes
+ XXX.chat.numbers.package-info
+ XXX.chat.numbers.StyledFormat
- XXX.chat.numbers.StyledFormat$1
+ XXX.chat.report.package-info
- XXX.chat.report.ReportingContext
- XXX.chat.report.ReportReason$1
+ XXX.chat.report.ReportType
+ XXX.chat.report.SkinReport
- XXX.chat.report.SkinReport$Builder
+ XXX.chunk.storage.ChunkSerializer$ChunkReadException
- XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$SectionData
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
- XXX.client.animation.package-info
- XXX.client.gui.BundleMouseActions
- XXX.client.gui.LayeredDraw
+ XXX.client.gui.LayeredDraw$Layer
+ XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
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
- XXX.client.model.AbstractPiglinModel
+ XXX.client.model.AbstractZombieModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AllayModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmadilloModel
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.ArrowModel
- XXX.client.model.BabyModelTransform
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
- XXX.client.model.BellModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BoggedModel
- XXX.client.model.BookModel
+ XXX.client.model.BreezeModel
- XXX.client.model.CamelModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestModel
+ XXX.client.model.ChestRaftModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.CowModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DonkeyModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FelineModel
+ XXX.client.model.HierarchicalModel
- XXX.client.model.HoglinModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidArmorModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.PlayerCapeModel
+ XXX.client.model.WaterPatchModel
- XXX.client.model.WindChargeModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.model.ZombifiedPiglinModel
- XXX.client.multiplayer.package-info
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
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BaseAshSmokeParticle
- XXX.client.particle.BlockMarker
+ XXX.client.particle.BlockMarker$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$CobwebProvider
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
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
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
- XXX.client.particle.ParticleRenderType$1
+ XXX.client.particle.ParticleRenderType$2
- XXX.client.particle.ParticleRenderType$3
+ XXX.client.particle.ParticleRenderType$4
- XXX.client.particle.ParticleRenderType$5
+ XXX.client.particle.ParticleRenderType$6
- XXX.client.renderer.CloudRenderer$RelativeCameraPos
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
- XXX.client.renderer.FogParameters
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$1
- XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostChain$TargetBundle
- XXX.client.renderer.PostChainConfig
- XXX.client.renderer.PostChainConfig$FullScreenTarget
- XXX.client.renderer.PostChainConfig$InternalTarget
- XXX.client.renderer.PostChainConfig$TargetInput
- XXX.client.renderer.PostChainConfig$Uniform
- XXX.client.renderer.PostPass$Input
- XXX.client.renderer.PostPass$TextureInput
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$BooleanStateShard
+ XXX.client.renderer.RenderStateShard$ColorLogicStateShard
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
+ XXX.client.renderer.SectionBufferBuilderPack
- XXX.client.renderer.SectionBufferBuilderPool
+ XXX.client.renderer.SectionOcclusionGraph
- XXX.client.renderer.SectionOcclusionGraph$GraphEvents
+ XXX.client.renderer.SectionOcclusionGraph$GraphState
- XXX.client.renderer.SectionOcclusionGraph$GraphStorage
+ XXX.client.renderer.SectionOcclusionGraph$Node
- XXX.client.renderer.SectionOcclusionGraph$SectionToNodeMap
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.ShapeRenderer$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
- XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
- XXX.client.resources.MapTextureManager$MapInstance
- XXX.client.resources.package-info
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
+ XXX.client.sounds.MusicManager
- XXX.client.sounds.package-info
- XXX.client.sounds.SoundBufferLibrary
+ XXX.client.sounds.SoundEngine
- XXX.client.sounds.SoundEngine$DeviceCheckState
+ XXX.client.sounds.SoundEngineExecutor
- XXX.client.sounds.SoundEventListener
+ XXX.client.sounds.SoundManager
- XXX.client.sounds.SoundManager$1
+ XXX.client.sounds.SoundManager$2
- XXX.client.sounds.SoundManager$Preparations
+ XXX.client.sounds.SoundManager$Preparations$1
- XXX.client.sounds.WeighedSoundEvents
+ XXX.client.sounds.Weighted
+ XXX.client.telemetry.ClientTelemetryManager
- XXX.client.telemetry.package-info
- XXX.client.telemetry.TelemetryEventInstance
+ XXX.client.telemetry.TelemetryEventLog
- XXX.client.telemetry.TelemetryEventLogger
+ XXX.client.telemetry.TelemetryEventSender
- XXX.client.telemetry.TelemetryEventType
+ XXX.client.telemetry.TelemetryEventType$Builder
- XXX.client.telemetry.TelemetryLogManager
+ XXX.client.telemetry.TelemetryProperty
- XXX.client.telemetry.TelemetryProperty$Exporter
+ XXX.client.telemetry.TelemetryProperty$GameMode
- XXX.client.telemetry.TelemetryProperty$ServerType
+ XXX.client.telemetry.TelemetryPropertyMap
- XXX.client.telemetry.TelemetryPropertyMap$1
+ XXX.client.telemetry.TelemetryPropertyMap$Builder
- XXX.client.telemetry.WorldSessionTelemetryManager
+ XXX.client.tutorial.BundleTutorial
- XXX.client.tutorial.package-info
+ XXX.client.tutorial.Tutorial$TimedToast
- XXX.client.tutorial.TutorialStepInstance
+ XXX.client.tutorial.TutorialSteps
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
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
- XXX.common.custom.RedstoneWireOrientationsDebugPayload
+ XXX.components.debugchart.AbstractDebugChart
- XXX.components.debugchart.BandwidthDebugChart
+ XXX.components.debugchart.FpsDebugChart
- XXX.components.debugchart.PingDebugChart
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast$RecipeDisplayItems
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastId
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastManager$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.CauldronInteraction$InteractionMap
+ XXX.core.cauldron.package-info
- XXX.core.component.DataComponentHolder
+ XXX.core.component.DataComponentMap
- XXX.core.component.DataComponentMap$1
+ XXX.core.component.DataComponentMap$2
- XXX.core.component.DataComponentMap$3
+ XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentMap$Builder$SimpleMap
+ XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$1
+ XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPatch$PatchKey
+ XXX.core.component.DataComponentPatch$SplitResult
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
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$9
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
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.ScalableParticleOptionsBase
+ XXX.core.particles.SculkChargeParticleOptions
- XXX.core.particles.ShriekParticleOption
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.VibrationParticleOption
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
- XXX.data.info.DatapackStructureReport$CustomPackEntry
- XXX.data.info.DatapackStructureReport$Format
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
- XXX.data.recipes.RecipeProvider$Runner
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
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
+ XXX.data.tags.CatVariantTagsProvider
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
+ XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
- XXX.data.tags.TradeRebalanceStructureTagsProvider
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
+ XXX.data.worldgen.NoiseData
- XXX.data.worldgen.package-info
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
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
+ XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AttributeModifierIdFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.AttributesRenameLegacy
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
- XXX.datafix.fixes.package-info
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerHeadBlockProfileFix
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.PrimedTntBlockStateFixer
- XXX.datafix.fixes.ProjectileStoredWeaponFix
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
+ XXX.datafix.schemas.package-info
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
+ XXX.datafix.schemas.V3327
- XXX.datafix.schemas.V3328
+ XXX.datafix.schemas.V3438
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
- XXX.datafix.schemas.V3816
+ XXX.datafix.schemas.V3818
- XXX.datafix.schemas.V3818_3
+ XXX.datafix.schemas.V3818_4
- XXX.datafix.schemas.V3818_5
+ XXX.datafix.schemas.V3825
- XXX.datafix.schemas.V3938
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.DamageEntity
- XXX.enchantment.effects.DamageImmunity
+ XXX.enchantment.effects.DamageItem
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
- XXX.entity.animal.Bee$ValidateHiveGoal
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
+ XXX.entity.animal.Sheep$1
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
- XXX.entity.animal.WolfVariant
+ XXX.entity.animal.WolfVariants
- XXX.entity.layers.CustomHeadLayer$Transforms
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
- XXX.entity.layers.package-info
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SaddleLayer
- XXX.entity.layers.SheepWoolLayer
+ XXX.entity.layers.ShulkerHeadLayer
- XXX.entity.layers.TropicalFishPatternLayer
+ XXX.entity.layers.TropicalFishPatternLayer$1
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WardenEmissiveLayer
- XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
+ XXX.entity.layers.WardenEmissiveLayer$DrawSelector
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.player.package-info
+ XXX.entity.player.package-info
- XXX.entity.player.PlayerRenderer
- XXX.entity.player.StackedContents$Output
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
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
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.state.AllayRenderState
- XXX.entity.state.ArmorStandRenderState
- XXX.entity.state.AxolotlRenderState
- XXX.entity.state.BeeRenderState
- XXX.entity.state.BoatRenderState
- XXX.entity.state.BreezeRenderState
- XXX.entity.state.CatRenderState
- XXX.entity.state.CreeperRenderState
- XXX.entity.state.DolphinRenderState
- XXX.entity.state.EndCrystalRenderState
- XXX.entity.state.EndermanRenderState
- XXX.entity.state.EntityRenderState$LeashState
- XXX.entity.state.EvokerFangsRenderState
- XXX.entity.state.ExperienceOrbRenderState
- XXX.entity.state.FelineRenderState
- XXX.entity.state.FishingHookRenderState
- XXX.entity.state.FrogRenderState
- XXX.entity.state.GoatRenderState
- XXX.entity.state.HoglinRenderState
- XXX.entity.state.HumanoidRenderState
- XXX.entity.state.IllusionerRenderState
- XXX.entity.state.ItemDisplayEntityRenderState
- XXX.entity.state.ItemFrameRenderState
- XXX.entity.state.LivingEntityRenderState
- XXX.entity.state.LlamaSpitRenderState
- XXX.entity.state.MinecartTntRenderState
- XXX.entity.state.OminousItemSpawnerRenderState
- XXX.entity.state.PandaRenderState
- XXX.entity.state.PhantomRenderState
- XXX.entity.state.PiglinRenderState
- XXX.entity.state.PlayerRenderState$HandState
- XXX.entity.state.PufferfishRenderState
- XXX.entity.state.RavagerRenderState
- XXX.entity.state.SalmonRenderState
- XXX.entity.state.ShulkerBulletRenderState
- XXX.entity.state.SkeletonRenderState
- XXX.entity.state.SnifferRenderState
- XXX.entity.state.StriderRenderState
- XXX.entity.state.ThrownItemRenderState
- XXX.entity.state.TippableArrowRenderState
- XXX.entity.state.TropicalFishRenderState
- XXX.entity.state.VexRenderState
- XXX.entity.state.VillagerRenderState
- XXX.entity.state.WitchRenderState
- XXX.entity.state.WitherSkullRenderState
- XXX.entity.state.ZombieRenderState
- XXX.entity.state.ZombifiedPiglinRenderState
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestBoat$1
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.VehicleEntity
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Definition
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.FreeTypeUtil
- XXX.font.providers.GlyphProviderDefinition
+ XXX.font.providers.GlyphProviderDefinition$Conditional
- XXX.font.providers.GlyphProviderDefinition$Loader
+ XXX.font.providers.GlyphProviderDefinition$Reference
- XXX.font.providers.GlyphProviderType
+ XXX.font.providers.package-info
+ XXX.font.providers.ProviderReferenceDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
- XXX.font.providers.UnihexProvider
+ XXX.font.providers.UnihexProvider$ByteContents
- XXX.font.providers.UnihexProvider$Definition
+ XXX.font.providers.UnihexProvider$Dimensions
- XXX.font.providers.UnihexProvider$Glyph
+ XXX.font.providers.UnihexProvider$Glyph$1
- XXX.font.providers.UnihexProvider$IntContents
+ XXX.font.providers.UnihexProvider$LineData
- XXX.font.providers.UnihexProvider$OverrideRange
+ XXX.font.providers.UnihexProvider$ReaderOutput
- XXX.font.providers.UnihexProvider$ShortContents
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchFactory
- XXX.gametest.framework.GameTestBatchListener
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestHelper$2
- XXX.gametest.framework.GameTestHelper$3
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
- XXX.gui.components.AbstractButton
+ XXX.gui.components.AbstractContainerWidget
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollWidget
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractStringWidget
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
+ XXX.gui.components.SubtitleOverlay$SoundPlayedAt
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TabButton
- XXX.gui.components.TabOrderedElement
+ XXX.gui.components.Tooltip
- XXX.gui.components.Whence
+ XXX.gui.components.WidgetSprites
- XXX.gui.components.WidgetTooltipHolder
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
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$CursorStep
- XXX.gui.layouts.AbstractLayout
+ XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
- XXX.gui.layouts.CommonLayouts
+ XXX.gui.layouts.EqualSpacingLayout
- XXX.gui.layouts.EqualSpacingLayout$ChildContainer
+ XXX.gui.layouts.EqualSpacingLayout$Orientation
- XXX.gui.layouts.FrameLayout
+ XXX.gui.layouts.FrameLayout$ChildContainer
- XXX.gui.layouts.GridLayout
+ XXX.gui.layouts.GridLayout$CellInhabitant
- XXX.gui.layouts.GridLayout$RowHelper
+ XXX.gui.layouts.HeaderAndFooterLayout
- XXX.gui.layouts.Layout
+ XXX.gui.layouts.LayoutElement
- XXX.gui.layouts.LayoutSettings
+ XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
- XXX.gui.layouts.LinearLayout
+ XXX.gui.layouts.LinearLayout$Orientation
+ XXX.gui.layouts.package-info
- XXX.gui.layouts.SpacerElement
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
- XXX.gui.navigation.CommonInputs
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenDirection
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.screens.AccessibilityOnboardingScreen
+ XXX.gui.screens.AddRealmPopupScreen
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
- XXX.gui.screens.RealmsBackupInfoScreen
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ XXX.gui.screens.RealmsBackupScreen
- XXX.gui.screens.RealmsBackupScreen$1
+ XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- XXX.gui.screens.RealmsBackupScreen$Entry
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen
- XXX.gui.screens.RealmsConfigureWorldScreen$1
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsGenericErrorScreen$ErrorMessage
+ XXX.gui.screens.RealmsInviteScreen
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen
+ XXX.gui.screens.RealmsLongRunningMcoTickTaskScreen
- XXX.gui.screens.RealmsNotificationsScreen
+ XXX.gui.screens.RealmsNotificationsScreen$1
- XXX.gui.screens.RealmsNotificationsScreen$2
+ XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- XXX.gui.screens.RealmsPlayerScreen
+ XXX.gui.screens.RealmsPlayerScreen$Entry
- XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ XXX.gui.screens.RealmsPopups
- XXX.gui.screens.RealmsResetNormalWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen$1
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsSelectFileToUploadScreen
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
- XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
+ XXX.gui.screens.RealmsSettingsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- XXX.gui.screens.RealmsSubscriptionInfoScreen
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$1
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.ReceivingLevelScreen$Reason
+ XXX.gui.screens.RecoverWorldDataScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$DeferredTooltipRendering
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.TitleScreen
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
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
+ XXX.gui.task.DataFetcher
- XXX.gui.task.DataFetcher$ComputationResult
+ XXX.gui.task.DataFetcher$SubscribedTask
- XXX.gui.task.DataFetcher$Subscription
+ XXX.gui.task.DataFetcher$SuccessfulComputationResult
- XXX.gui.task.DataFetcher$Task
- XXX.gui.task.package-info
+ XXX.gui.task.RepeatedDelayStrategy
- XXX.gui.task.RepeatedDelayStrategy$1
+ XXX.gui.task.RepeatedDelayStrategy$2
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.ClientActivePlayersTooltip
+ XXX.inventory.tooltip.ClientActivePlayersTooltip$ActivePlayersTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Builder
+ XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.PotionContents
+ XXX.item.alchemy.Potions
+ XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
- XXX.item.armortrim.TrimMaterial
+ XXX.item.armortrim.TrimMaterials
- XXX.item.armortrim.TrimPattern
+ XXX.item.armortrim.TrimPatterns
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
+ XXX.item.component.SuspiciousStewEffects
- XXX.item.component.SuspiciousStewEffects$Entry
+ XXX.item.component.Tool
- XXX.item.component.Tool$Rule
+ XXX.item.component.TooltipProvider
- XXX.item.component.Unbreakable
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
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
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo$SlotInfo
+ XXX.item.crafting.TippedArrowRecipe
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.TargetedConditionalEffect
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
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
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.level.block.Block$ShapePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BlockTypes
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BonemealableBlock$Type
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
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
+ XXX.level.block.ChainBlock$1
- XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.CherryLeavesBlock
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
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DecoratedPotBlock
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
- XXX.level.block.EnchantingTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.EquipableCarvedPumpkinBlock
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
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HeavyCoreBlock
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
- XXX.level.block.Mirror
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
- XXX.level.block.PiglinWallSkullBlock
+ XXX.level.block.PinkPetalsBlock
- XXX.level.block.PipeBlock
+ XXX.level.block.PitcherCropBlock
- XXX.level.block.PitcherCropBlock$PosAndState
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
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
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
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
- XXX.level.block.SnifferEggBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
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
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
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
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VaultBlock
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
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
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
- XXX.level.material.FlowingFluid$SpreadContext
- XXX.level.redstone.DefaultRedstoneWireEvaluator
- XXX.level.redstone.ExperimentalRedstoneWireEvaluator
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.Orientation$SideBias
+ XXX.level.redstone.Redstone
- XXX.level.redstone.RedstoneWireEvaluator
+ XXX.level.saveddata.package-info
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
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.placement.CarvingMaskPlacement
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
- XXX.loot.functions.ToggleTooltips$ComponentToggle
+ XXX.loot.functions.ToggleTooltips$TooltipWither
- XXX.loot.packs.LootData
+ XXX.loot.packs.package-info
+ XXX.loot.packs.TradeRebalanceChestLoot
- XXX.loot.packs.TradeRebalanceLootTableProvider
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaEquipmentLoot
- XXX.loot.packs.VanillaFishingLoot
+ XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
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
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
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
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementHolder
- XXX.minecraft.advancements.AdvancementNode
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementRequirements
+ XXX.minecraft.advancements.AdvancementRequirements$Strategy
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.AdvancementTree
+ XXX.minecraft.advancements.AdvancementTree$Listener
- XXX.minecraft.advancements.AdvancementType
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.Camera$NearPlane
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.ClientRecipeBook$1
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
- XXX.minecraft.client.package-info
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
- XXX.minecraft.commands.ParserUtils
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.MappedRegistry$3
- XXX.minecraft.core.MappedRegistry$TagSet
- XXX.minecraft.core.MappedRegistry$TagSet$2
+ XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.RegistrationInfo
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Registry$1
+ XXX.minecraft.core.Registry$2
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
+ XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
- XXX.minecraft.locale.DeprecatedTranslationsInfo
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
+ XXX.minecraft.nbt.NbtAccounterException
- XXX.minecraft.nbt.NbtException
+ XXX.minecraft.nbt.NbtFormatException
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
+ XXX.minecraft.nbt.NbtOps$HomogenousListCollector
- XXX.minecraft.nbt.NbtOps$InitialListCollector
+ XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
+ XXX.minecraft.nbt.NbtOps$LongListCollector
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ReportedNbtException
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
+ XXX.minecraft.network.BandwidthDebugMonitor
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.ClientboundPacketListener
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$3
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.DisconnectionDetails
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.HandlerNames
- XXX.minecraft.network.MonitorFrameDecoder
+ XXX.minecraft.network.NoOpFrameDecoder
- XXX.minecraft.network.NoOpFrameEncoder
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.PacketSendListener$1
- XXX.minecraft.network.PacketSendListener$2
+ XXX.minecraft.network.ProtocolInfo
- XXX.minecraft.network.ProtocolInfo$Unbound
+ XXX.minecraft.network.ProtocolInfo$Unbound$PacketVisitor
- XXX.minecraft.network.ProtocolSwapHandler
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.RegistryFriendlyByteBuf
+ XXX.minecraft.network.ServerboundPacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.UnconfiguredPipelineHandler
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ XXX.minecraft.network.Utf8String
- XXX.minecraft.network.VarInt
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.network.VarLong
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipeHelper
+ XXX.minecraft.references.Blocks
- XXX.minecraft.references.Items
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.FileToIdConverter
+ XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.RegistryDataLoader
+ XXX.minecraft.resources.RegistryDataLoader$1
- XXX.minecraft.resources.RegistryDataLoader$Loader
+ XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
- XXX.minecraft.resources.RegistryDataLoader$NetworkedRegistryData
- XXX.minecraft.server.package-info
+ XXX.minecraft.server.ReloadableServerRegistries$Holder
- XXX.minecraft.server.ReloadableServerRegistries$LoadResult
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
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
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.ServerTickRateManager
+ XXX.minecraft.server.Services
- XXX.minecraft.server.SuppressedExceptionCollector
- XXX.minecraft.server.SuppressedExceptionCollector$ShortEntry
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.CatVariantTags
+ XXX.minecraft.tags.DamageTypeTags
- XXX.minecraft.tags.EnchantmentTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
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
- XXX.minecraft.tags.TagLoader$LoadResult
+ XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagNetworkSerialization$TagOutput
- XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.ARGB
- XXX.minecraft.util.BinaryAnimator
+ XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FutureChain
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
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
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$Collector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
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
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResult$Fail
- XXX.minecraft.world.InteractionResult$Pass
- XXX.minecraft.world.InteractionResult$SwingSource
+ XXX.minecraft.world.ItemInteractionResult
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
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
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
- XXX.model.multipart.MultiPart$1Key
- XXX.model.multipart.OrCondition
+ XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.model.multipart.Selector$Deserializer
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
+ XXX.mojang.blaze3d.package-info
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
+ XXX.mojang.realmsclient.package-info
- XXX.mojang.realmsclient.RealmsAvailability
+ XXX.mojang.realmsclient.RealmsAvailability$Result
- XXX.mojang.realmsclient.RealmsAvailability$Type
+ XXX.mojang.realmsclient.RealmsMainScreen
- XXX.mojang.realmsclient.RealmsMainScreen$1
+ XXX.mojang.realmsclient.RealmsMainScreen$2
- XXX.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ButtonEntry
- XXX.mojang.realmsclient.RealmsMainScreen$CrossButton
+ XXX.mojang.realmsclient.RealmsMainScreen$EmptyEntry
- XXX.mojang.realmsclient.RealmsMainScreen$Entry
+ XXX.mojang.realmsclient.RealmsMainScreen$LayoutState
- XXX.mojang.realmsclient.RealmsMainScreen$NotificationButton
+ XXX.mojang.realmsclient.RealmsMainScreen$NotificationMessageEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ParentEntry
- XXX.mojang.realmsclient.RealmsMainScreen$RealmsCall
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.Unit
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
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
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.Component$SerializerAdapter
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$Type
- XXX.network.chat.ComponentSerialization
+ XXX.network.chat.ComponentSerialization$1
- XXX.network.chat.ComponentSerialization$FuzzyCodec
+ XXX.network.chat.ComponentSerialization$StrictEither
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
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
- XXX.network.chat.package-info
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.RemoteChatSession
- XXX.network.chat.RemoteChatSession$Data
+ XXX.network.chat.SignableCommand
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
+ XXX.network.chat.SignedMessageChain
- XXX.network.chat.SignedMessageChain$1
+ XXX.network.chat.SignedMessageChain$DecodeException
- XXX.network.chat.SignedMessageChain$Decoder
+ XXX.network.chat.SignedMessageChain$Encoder
- XXX.network.chat.SignedMessageLink
+ XXX.network.chat.SignedMessageValidator
- XXX.network.chat.SignedMessageValidator$KeyBased
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$1Collector
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.ThrowingComponent
+ XXX.network.codec.ByteBufCodecs
- XXX.network.codec.ByteBufCodecs$1
+ XXX.network.codec.ByteBufCodecs$10
- XXX.network.codec.ByteBufCodecs$11
+ XXX.network.codec.ByteBufCodecs$12
- XXX.network.codec.ByteBufCodecs$13
+ XXX.network.codec.ByteBufCodecs$14
- XXX.network.codec.ByteBufCodecs$15
+ XXX.network.codec.ByteBufCodecs$16
- XXX.network.codec.ByteBufCodecs$17
+ XXX.network.codec.ByteBufCodecs$18
- XXX.network.codec.ByteBufCodecs$19
+ XXX.network.codec.ByteBufCodecs$2
- XXX.network.codec.ByteBufCodecs$20
+ XXX.network.codec.ByteBufCodecs$21
- XXX.network.codec.ByteBufCodecs$22
+ XXX.network.codec.ByteBufCodecs$23
- XXX.network.codec.ByteBufCodecs$24
+ XXX.network.codec.ByteBufCodecs$25
- XXX.network.codec.ByteBufCodecs$26
+ XXX.network.codec.ByteBufCodecs$27
- XXX.network.codec.ByteBufCodecs$28
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
- XXX.network.protocol.package-info
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
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacter
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
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
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.ParseState$CacheEntry
- XXX.parsing.packrat.ParseState$CacheKey
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Reference
- XXX.parsing.packrat.Term$Sequence
- XXX.pools.alias.Direct
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.Random
+ XXX.pools.alias.RandomGroup
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
- XXX.protocol.game.ClientboundMoveMinecartPacket
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
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
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
- XXX.protocol.game.ClientboundSetCursorItemPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
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
+ XXX.protocol.game.ClientboundTickingStatePacket
- XXX.protocol.game.ClientboundTickingStepPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
- XXX.protocol.game.package-info
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
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntent
- XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.HandshakePacketTypes
- XXX.protocol.handshake.HandshakeProtocols
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.realmsclient.client.FileDownload
- XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ XXX.realmsclient.client.FileDownload$ProgressListener
- XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
+ XXX.realmsclient.client.FileUpload
- XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
- XXX.realmsclient.client.package-info
+ XXX.realmsclient.client.Ping
- XXX.realmsclient.client.Ping$Region
+ XXX.realmsclient.client.RealmsClient
- XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ XXX.realmsclient.client.RealmsClient$Environment
- XXX.realmsclient.client.RealmsClientConfig
+ XXX.realmsclient.client.RealmsError
- XXX.realmsclient.client.RealmsError$AuthenticationError
+ XXX.realmsclient.client.RealmsError$CustomError
- XXX.realmsclient.client.RealmsError$ErrorWithJsonPayload
+ XXX.realmsclient.client.RealmsError$ErrorWithRawPayload
- XXX.realmsclient.client.Request
+ XXX.realmsclient.client.Request$Delete
- XXX.realmsclient.client.Request$Get
+ XXX.realmsclient.client.Request$Post
- XXX.realmsclient.client.Request$Put
+ XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.GuardedSerializer
- XXX.realmsclient.dto.Ops
- XXX.realmsclient.dto.package-info
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsNotification
- XXX.realmsclient.dto.RealmsNotification$InfoPopup
+ XXX.realmsclient.dto.RealmsNotification$UrlButton
- XXX.realmsclient.dto.RealmsNotification$VisitUrl
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$Compatibility
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsText
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.ServerActivity
+ XXX.realmsclient.dto.ServerActivityList
- XXX.realmsclient.dto.Subscription
+ XXX.realmsclient.dto.Subscription$SubscriptionType
- XXX.realmsclient.dto.UploadInfo
+ XXX.realmsclient.dto.ValueObject
- XXX.realmsclient.dto.WorldDownload
+ XXX.realmsclient.dto.WorldTemplate
- XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
+ XXX.realmsclient.dto.WorldTemplatePaginatedList
+ XXX.realmsclient.exception.package-info
+ XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- XXX.realmsclient.exception.RealmsHttpException
+ XXX.realmsclient.exception.RealmsServiceException
- XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.package-info
- XXX.realmsclient.gui.RealmsDataFetcher
+ XXX.realmsclient.gui.RealmsDataFetcher$ServerListData
- XXX.realmsclient.gui.RealmsNewsManager
+ XXX.realmsclient.gui.RealmsServerList
- XXX.realmsclient.gui.RealmsWorldSlotButton
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
- XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.realmsclient.util.WorldGenerationInfo
- XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
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
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BlockEntityRendererProvider
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
- XXX.renderer.blockentity.BlockEntityRenderers
+ XXX.renderer.blockentity.BrightnessCombiner
- XXX.renderer.blockentity.BrushableBlockRenderer
+ XXX.renderer.blockentity.BrushableBlockRenderer$1
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
- XXX.renderer.blockentity.SignRenderer$Models
+ XXX.renderer.blockentity.SignRenderer$SignModel
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
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.RedstoneWireOrientationsRenderer
- XXX.renderer.entity.AbstractHoglinRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractMinecartRenderer
- XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.BoggedRenderer
+ XXX.renderer.entity.BreezeRenderer
- XXX.renderer.entity.CamelRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
+ XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer$1
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.ParrotRenderer$1
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
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
- XXX.renderer.item.ClampedItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
+ XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
- XXX.renderer.item.ItemProperties
+ XXX.renderer.item.ItemProperties$1
- XXX.renderer.item.ItemPropertyFunction
+ XXX.renderer.item.package-info
- XXX.renderer.state.MapRenderState$MapDecorationRenderState
+ XXX.resources.model.BlockStateModelLoader$BlockStateDefinitionException
- XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
+ XXX.resources.model.BlockStateModelLoader$LoadedModel
- XXX.resources.model.BlockStateModelLoader$LoadedModels
+ XXX.resources.model.BuiltInModel
- XXX.resources.model.Material
- XXX.resources.model.ModelDiscovery$ResolverImpl
- XXX.resources.model.ModelGroupCollector$GroupKey
+ XXX.resources.model.package-info
- XXX.resources.model.UnbakedModel
- XXX.resources.model.UnbakedModel$Resolver
+ XXX.resources.model.WeightedBakedModel
- XXX.resources.model.WeightedBakedModel$Builder
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
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
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
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
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
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.CraftingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostSlots
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeCollection$CraftableStatus
+ XXX.screens.recipebook.SmokingRecipeBookComponent
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
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
- XXX.screens.worldselection.CreateWorldScreen$GameTab
+ XXX.screens.worldselection.CreateWorldScreen$MoreTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
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
- XXX.screens.worldselection.ExperimentsScreen
+ XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.package-info
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
- XXX.screens.worldselection.WorldCreationUiState
+ XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
- XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
+ XXX.screens.worldselection.WorldOpenFlows
- XXX.screens.worldselection.WorldOpenFlows$1Data
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$Entry
+ XXX.screens.worldselection.WorldSelectionList$LoadingHeader
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
- XXX.server.network.LegacyTextFilter
- XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
- XXX.server.network.ServerTextFilter
- XXX.server.network.ServerTextFilter$MessageEncoder
- XXX.server.network.ServerTextFilter$RequestFailedException
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$PlayerContext
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
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
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
+ XXX.telemetry.events.AggregatedTelemetryEvent
- XXX.telemetry.events.GameLoadTimesEvent
+ XXX.telemetry.events.GameLoadTimesEvent$Measurement
+ XXX.telemetry.events.package-info
- XXX.telemetry.events.PerformanceMetricsEvent
+ XXX.telemetry.events.WorldLoadEvent
- XXX.telemetry.events.WorldLoadEvent$1
+ XXX.telemetry.events.WorldLoadTimesEvent
- XXX.telemetry.events.WorldUnloadEvent
+ XXX.util.datafix.package-info
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.DebugSampleSubscriptionTracker
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.parsing.package-info
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
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.CreateSnapshotRealmTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
+ XXX.util.task.package-info
- XXX.util.task.RealmCreationTask
+ XXX.util.task.ResettingGeneratedWorldTask
- XXX.util.task.ResettingTemplateWorldTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
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
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- XXX.village.poi.PoiRecord$Packed
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiSection$Packed
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.BadOmenMobEffect
+ XXX.world.effect.HealOrHarmMobEffect
- XXX.world.effect.HungerMobEffect
+ XXX.world.effect.InfestedMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.OozingMobEffect
- XXX.world.effect.OozingMobEffect$NearbySlimes
- XXX.world.effect.package-info
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RaidOmenMobEffect
+ XXX.world.effect.RegenerationMobEffect
- XXX.world.effect.SaturationMobEffect
+ XXX.world.effect.WeavingMobEffect
- XXX.world.effect.WindChargedMobEffect
+ XXX.world.effect.WitherMobEffect
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Attackable
- XXX.world.entity.Crackiness
+ XXX.world.entity.Crackiness$Level
- XXX.world.entity.Display
+ XXX.world.entity.Display$BillboardConstraints
- XXX.world.entity.Display$BlockDisplay
+ XXX.world.entity.Display$BlockDisplay$BlockRenderState
- XXX.world.entity.Display$ColorInterpolator
+ XXX.world.entity.Display$FloatInterpolator
- XXX.world.entity.Display$GenericInterpolator
+ XXX.world.entity.Display$IntInterpolator
- XXX.world.entity.Display$ItemDisplay
+ XXX.world.entity.Display$ItemDisplay$ItemRenderState
- XXX.world.entity.Display$LinearFloatInterpolator
+ XXX.world.entity.Display$LinearIntInterpolator
- XXX.world.entity.Display$PosRotInterpolationTarget
+ XXX.world.entity.Display$RenderState
- XXX.world.entity.Display$TextDisplay
+ XXX.world.entity.Display$TextDisplay$Align
- XXX.world.entity.Display$TextDisplay$CachedInfo
+ XXX.world.entity.Display$TextDisplay$CachedLine
- XXX.world.entity.Display$TextDisplay$LineSplitter
+ XXX.world.entity.Display$TextDisplay$TextRenderState
- XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.EquipmentSlotGroup
+ XXX.world.entity.EquipmentSlotGroup$1
- XXX.world.entity.EquipmentTable
+ XXX.world.entity.EquipmentUser
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.Leashable
- XXX.world.entity.Leashable$LeashData
+ XXX.world.entity.LerpingModel
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OminousItemSpawner
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.PortalProcessor
+ XXX.world.entity.Pose
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
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.package-info
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
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.Equipable
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
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
+ XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
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
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.OminousBottleItem
- XXX.world.item.package-info
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
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
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
+ XXX.world.item.Tiers
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
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
- XXX.world.level.EmptyBlockAndTintGetter
- XXX.world.level.ServerExplosion$StackCollector
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
- XXX.worldgen.biome.BiomeData
+ XXX.worldgen.biome.EndBiomes
- XXX.worldgen.biome.NetherBiomes
+ XXX.worldgen.biome.OverworldBiomes
- XXX.worldgen.biome.package-info
+ XXX.worldgen.features.AquaticFeatures
- XXX.worldgen.features.CaveFeatures
+ XXX.worldgen.features.EndFeatures
- XXX.worldgen.features.FeatureUtils
+ XXX.worldgen.features.MiscOverworldFeatures
- XXX.worldgen.features.NetherFeatures
+ XXX.worldgen.features.OreFeatures
+ XXX.worldgen.features.package-info
- XXX.worldgen.features.PileFeatures
+ XXX.worldgen.features.TreeFeatures
- XXX.worldgen.features.VegetationFeatures
+ XXX.worldgen.placement.AquaticPlacements
- XXX.worldgen.placement.CavePlacements
+ XXX.worldgen.placement.EndPlacements
- XXX.worldgen.placement.MiscOverworldPlacements
+ XXX.worldgen.placement.NetherPlacements
- XXX.worldgen.placement.OrePlacements
+ XXX.worldgen.placement.package-info
+ XXX.worldgen.placement.PlacementUtils
- XXX.worldgen.placement.TreePlacements
+ XXX.worldgen.placement.VegetationPlacements
- XXX.worldgen.placement.VillagePlacements
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
<hr/>