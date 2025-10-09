## Comparison with [1.21.10](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.10)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 88,
  "minor": 0
}</pre></td><td><pre>{
  "major": 89,
  "minor": 0
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 69,
  "minor": 0
}</pre></td><td><pre>{
  "major": 70,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4556</pre></td><td><pre>4653</pre></td></tr><tr><td>Protocol version</td><td><pre>773</pre></td><td><pre>1073742097</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ permission_check_type.txt
+ permission_type.txt
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:damage_type
+ minecraft:kinetic_weapon
+ minecraft:minimum_attack_charge
+ minecraft:piercing_weapon
+ minecraft:swing_animation
+ minecraft:use_effects
```

</details>
<details>
<summary>
enchantment_effect_component_type
</summary>

```diff
+ minecraft:post_piercing_attack
```

</details>
<details>
<summary>
enchantment_entity_effect_type
</summary>

```diff
+ minecraft:apply_impulse
```

</details>
<details>
<summary>
enchantment_level_based_value_type
</summary>

```diff
+ minecraft:exponent
```

</details>
<details>
<summary>
enchantment_value_effect_type
</summary>

```diff
+ minecraft:exponential
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:nautilus
+ minecraft:zombie_nautilus
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:copper_nautilus_armor
+ minecraft:copper_spear
+ minecraft:diamond_nautilus_armor
+ minecraft:diamond_spear
+ minecraft:golden_nautilus_armor
+ minecraft:golden_spear
+ minecraft:iron_nautilus_armor
+ minecraft:iron_spear
+ minecraft:nautilus_spawn_egg
+ minecraft:netherite_nautilus_armor
+ minecraft:netherite_spear
+ minecraft:stone_spear
+ minecraft:wooden_spear
+ minecraft:zombie_nautilus_spawn_egg
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:attack_target_cooldown
+ minecraft:charge_cooldown_ticks
```

</details>
<details>
<summary>
mob_effect
</summary>

```diff
+ minecraft:breath_of_the_nautilus
```

</details>
<details>
<summary>
outgoing_rpc_methods
</summary>

```diff
+ minecraft:notification/server/activity
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:nautilus_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.baby_nautilus.ambient
+ minecraft:entity.baby_nautilus.death
+ minecraft:entity.baby_nautilus.eat
+ minecraft:entity.baby_nautilus.hurt
+ minecraft:entity.baby_nautilus.swim
+ minecraft:entity.nautilus.ambient
+ minecraft:entity.nautilus.dash
+ minecraft:entity.nautilus.dash_ready
+ minecraft:entity.nautilus.death
+ minecraft:entity.nautilus.eat
+ minecraft:entity.nautilus.hurt
+ minecraft:entity.nautilus.swim
+ minecraft:entity.zombie_horse.angry
+ minecraft:entity.zombie_nautilus.ambient
+ minecraft:entity.zombie_nautilus.dash
+ minecraft:entity.zombie_nautilus.dash_ready
+ minecraft:entity.zombie_nautilus.death
+ minecraft:entity.zombie_nautilus.eat
+ minecraft:entity.zombie_nautilus.hurt
+ minecraft:entity.zombie_nautilus.swim
+ minecraft:item.armor.equip_nautilus
+ minecraft:item.armor.unequip_nautilus
+ minecraft:item.spear_wood.attack
+ minecraft:item.spear_wood.hit
+ minecraft:item.spear_wood.use
+ minecraft:item.spear.attack
+ minecraft:item.spear.hit
+ minecraft:item.spear.lunge_1
+ minecraft:item.spear.lunge_2
+ minecraft:item.spear.lunge_3
+ minecraft:item.spear.use
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
+ universal_tags/permission_check_type.json
+ universal_tags/permission_type.json
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:nautilus
+ minecraft:zombie_nautilus
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:damage_type
+ minecraft:kinetic_weapon
+ minecraft:minimum_attack_charge
+ minecraft:piercing_weapon
+ minecraft:swing_animation
+ minecraft:use_effects
```

</details>
<details>
<summary>
universal_tags/enchantment_effect_component_type.json
</summary>

```diff
+ minecraft:post_piercing_attack
```

</details>
<details>
<summary>
universal_tags/enchantment_entity_effect_type.json
</summary>

```diff
+ minecraft:apply_impulse
```

</details>
<details>
<summary>
universal_tags/enchantment_level_based_value_type.json
</summary>

```diff
+ minecraft:exponent
```

</details>
<details>
<summary>
universal_tags/enchantment_value_effect_type.json
</summary>

```diff
+ minecraft:exponential
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:nautilus
+ minecraft:zombie_nautilus
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:copper_nautilus_armor
+ minecraft:copper_spear
+ minecraft:diamond_nautilus_armor
+ minecraft:diamond_spear
+ minecraft:golden_nautilus_armor
+ minecraft:golden_spear
+ minecraft:iron_nautilus_armor
+ minecraft:iron_spear
+ minecraft:nautilus_spawn_egg
+ minecraft:netherite_nautilus_armor
+ minecraft:netherite_spear
+ minecraft:stone_spear
+ minecraft:wooden_spear
+ minecraft:zombie_nautilus_spawn_egg
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:attack_target_cooldown
+ minecraft:charge_cooldown_ticks
```

</details>
<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
+ minecraft:breath_of_the_nautilus
```

</details>
<details>
<summary>
universal_tags/outgoing_rpc_methods.json
</summary>

```diff
+ minecraft:notification/server/activity
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:nautilus_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.baby_nautilus.ambient
+ minecraft:entity.baby_nautilus.death
+ minecraft:entity.baby_nautilus.eat
+ minecraft:entity.baby_nautilus.hurt
+ minecraft:entity.baby_nautilus.swim
+ minecraft:entity.nautilus.ambient
+ minecraft:entity.nautilus.dash
+ minecraft:entity.nautilus.dash_ready
+ minecraft:entity.nautilus.death
+ minecraft:entity.nautilus.eat
+ minecraft:entity.nautilus.hurt
+ minecraft:entity.nautilus.swim
+ minecraft:entity.zombie_horse.angry
+ minecraft:entity.zombie_nautilus.ambient
+ minecraft:entity.zombie_nautilus.dash
+ minecraft:entity.zombie_nautilus.dash_ready
+ minecraft:entity.zombie_nautilus.death
+ minecraft:entity.zombie_nautilus.eat
+ minecraft:entity.zombie_nautilus.hurt
+ minecraft:entity.zombie_nautilus.swim
+ minecraft:item.armor.equip_nautilus
+ minecraft:item.armor.unequip_nautilus
+ minecraft:item.spear_wood.attack
+ minecraft:item.spear_wood.hit
+ minecraft:item.spear_wood.use
+ minecraft:item.spear.attack
+ minecraft:item.spear.hit
+ minecraft:item.spear.lunge_1
+ minecraft:item.spear.lunge_2
+ minecraft:item.spear.lunge_3
+ minecraft:item.spear.use
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
+ copper_nautilus_armor.json
+ copper_spear.json
+ diamond_nautilus_armor.json
+ diamond_spear.json
+ golden_nautilus_armor.json
+ golden_spear.json
+ iron_nautilus_armor.json
+ iron_spear.json
+ nautilus_spawn_egg.json
+ netherite_nautilus_armor.json
+ netherite_spear.json
+ stone_spear.json
+ wooden_spear.json
+ zombie_nautilus_spawn_egg.json
```

</details>
<details>
<summary>
acacia_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
activator_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
air
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allay_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
allium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_cluster
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
amethyst_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ancient_debris
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
andesite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
angler_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
archer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armadillo_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
armor_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arms_up_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
axolotl_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
azure_bluet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
baked_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_chest_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_mosaic_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_raft
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bamboo_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
barrier
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beacon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bedrock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beehive
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_soup
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_nest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bee_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
big_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blade_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blast_furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blaze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_orchid
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bogged_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bolt_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bone_meal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bordure_indented_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bowl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bread
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
breeze_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brewing_stand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
budding_amethyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
burn_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cactus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cake
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calcite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
calibrated_sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
camel_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cartography_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carved_pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cauldron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cave_spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chain_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
charcoal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chest_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chipped_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_bookshelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chiseled_tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_flower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chorus_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clay_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
clock
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
closed_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coarse_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
coast_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobbled_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cobweb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cocoa_beans
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
command_block_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
comparator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
composter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
conduit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cookie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cornflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cow_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crafting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_heart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creaking_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
creeper_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crimson_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crossbow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
crying_obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cut_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
damaged_anvil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dandelion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
danger_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dark_prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
daylight_detector
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_brain_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bubble_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dead_tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
debug_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
decorated_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_coal_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_copper_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tiles
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
deepslate_tile_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
detector_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diorite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dirt_path
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
disc_fragment_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dispenser
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dolphin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
donkey_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_breath
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_ghast
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dripstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dropper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
drowned_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dune_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
echo_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elder_guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
elytra
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
emerald_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanting_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enderman_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
endermite_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_dragon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ender_pearl
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_crystal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_portal_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
end_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
evoker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
experience_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
explorer_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
eye_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
farmland
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
feather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fermented_spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
field_masoned_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
filled_map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firefly_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_rocket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
firework_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fire_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fishing_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fletching_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flint_and_steel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flowering_azalea_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flower_pot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
flow_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
fox_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
friend_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frogspawn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
frog_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
furnace_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ghast_tear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gilded_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glistering_melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
globe_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glowstone_dust
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_lichen
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_horn
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
goat_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
granite_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grass_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
grindstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guardian_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gunpowder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
guster_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hanging_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
happy_ghast_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hay_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heartbreak_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_of_the_sea
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heart_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_core
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
heavy_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honeycomb_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
hopper_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horn_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
host_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
howl_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
husk_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_chiseled_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_cracked_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
infested_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ink_sac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_nugget
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
item_frame
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jack_o_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jigsaw
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jukebox
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
knowledge_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ladder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_lazuli
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lapis_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
large_fern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lava_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lead
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leaf_litter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lectern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lever
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_weighted_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lilac
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_of_the_valley
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lily_pad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lingering_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lodestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
loom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cream
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magma_cube_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_propagule
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
map
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
medium_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
milk_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
miner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mojang_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mooshroom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_cobblestone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mossy_stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mourner_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
muddy_mangrove_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mud_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mule_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_11
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_13
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_5
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_blocks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_cat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_chirp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_creator_music_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_far
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_lava_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_mellohi
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_otherside
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_pigstep
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_precipice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_relic
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_stal
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_strad
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_tears
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_wait
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
music_disc_ward
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mycelium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
name_tag
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nautilus_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_ingot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_scrap
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_upgrade_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherrack
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_gold_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_quartz_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_sprouts
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_star
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
nether_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
note_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
observer
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
obsidian
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ocelot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ochre_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
open_eyeblossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxeye_daisy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_ice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
packed_mud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
painting
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_hanging_moss
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_moss_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
panda_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
paper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
parrot_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pearlescent_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
peony
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
petrified_oak_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_membrane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
phantom_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_brute_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pig_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pillager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_petals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_plant
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pitcher_pod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
player_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
plenty_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
podzol
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poisonous_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polar_bear_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_andesite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_blackstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_deepslate_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_diorite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_granite_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
polished_tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
popped_chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poppy
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powder_snow_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
powered_rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_crystals
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_shard
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prismarine_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
prize_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_pie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purpur_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_pillar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_foot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_hide
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rail
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raiser_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ravager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_gold_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
raw_iron_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
recovery_compass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_lamp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_ore
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
redstone_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_mushroom_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_nether_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
reinforced_deepslate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeater
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
repeating_command_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
resin_clump
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
respawn_anchor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rib_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rooted_dirt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rose_bush
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rotten_flesh
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
saddle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sandstone_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scaffolding
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
scrape_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_catalyst
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_sensor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_shrieker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sculk_vein
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
seagrass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sea_pickle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sentry_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shaper_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheaf_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shears
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sheep_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shelter_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shield
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
short_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shroomlight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_shell
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
shulker_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silence_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
silverfish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_banner_pattern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
skull_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_ball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
slime_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_amethyst_bud
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
small_dripleaf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smithing_table
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smoker
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_basalt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_quartz_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_red_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_sandstone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
smooth_stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sniffer_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snort_pottery_sherd
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snout_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snowball
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
snow_golem_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_campfire
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_soil
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
soul_torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spectral_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spire_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
splash_potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spore_blossom
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_chest_boat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_leaves
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sapling
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spyglass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
squid_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sticky_piston
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stonecutter
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stray_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
strider_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
string
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_acacia_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_bamboo_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_birch_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_cherry_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_crimson_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_dark_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_jungle_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_mangrove_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_pale_oak_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_log
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_spruce_wood
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stripped_warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
structure_void
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sugar_cane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sunflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_gravel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_sand
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tadpole_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_dry_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tall_grass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
target
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
test_instance_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tide_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tinted_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tipped_arrow
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tnt_minecart
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torch
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
torchflower_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
totem_of_undying
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trader_llama_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trapped_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_key
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trial_spawner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tripwire_hook
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tube_coral_fan
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_bricks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_brick_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tuff_wall
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_scute
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
twisting_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vault
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
verdant_froglight
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vex_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vindicator_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
vine
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wandering_trader_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warden_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ward_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_button
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fence_gate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_fungus_on_a_stick
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hanging_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_hyphae
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_nylium
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_planks
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_pressure_plate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_roots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_shelf
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_sign
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_stem
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
warped_wart_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
water_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_block
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_chiseled_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bars
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_bulb
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_chain
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_chest
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_door
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_grate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_lantern
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_slab
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_cut_copper_stairs
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_lightning_rod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weeping_vines
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wet_sponge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wheat_seeds
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_tulip
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wildflowers
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wild_armor_trim_smithing_template
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wind_charge
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
witch_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_rose
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_skeleton_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wither_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
writable_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
written_book
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_banner
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bed
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_bundle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_candle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_concrete_powder
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_dye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_glazed_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_shulker_box
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_stained_glass_pane
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_wool
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zoglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_horse_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombie_villager_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
zombified_piglin_spawn_egg
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.10</th><th>25w41a</th></tr><tr><td>minecraft:swing_animation</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_effects</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
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
+ stopwatch.txt
```

</details>
<details>
<summary>
execute
</summary>

```diff
+ execute if stopwatch <id: resource_location> <range: float_range>
+ execute unless stopwatch <id: resource_location> <range: float_range>
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
+ copper_spear.json
+ diamond_spear.json
+ golden_spear.json
+ iron_spear.json
+ netherite_nautilus_armor_smithing.json
+ netherite_spear_smithing.json
+ stone_spear.json
+ wooden_spear.json
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
+ minecraft:permission_check_type
+ minecraft:permission_type
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
+ advMode.setCommand.disabled: Command set: %s, but command blocks are still disabled
+ commands.stopwatch.already_exists: Stopwatch '%s' already exists
+ commands.stopwatch.create.success: Created Stopwatch '%s'
+ commands.stopwatch.does_not_exist: Stopwatch '%s' does not exist
+ commands.stopwatch.query: Stopwatch '%s' has run for %ss
+ commands.stopwatch.remove.success: Removed Stopwatch '%s'
+ commands.stopwatch.restart.success: Restarted Stopwatch '%s'
+ death.attack.spear: %1$s was speared by %2$s
+ death.attack.spear.item: %1$s was speared by %2$s using %3$s
+ debug.crash.message.rebindable: %s + %s is held down. This will crash the game unless released.
+ debug.entry.currently.inOverlay: %s: Currently only in debug overlay
+ debug.entry.overlay: In overlay
+ debug.profiling.start.rebindable: Profiling started for %s seconds. Use %s + %s to stop early
+ effect.minecraft.breath_of_the_nautilus: Breath of the Nautilus
+ enchantment.minecraft.lunge: Lunge
+ entity.minecraft.nautilus: Nautilus
+ entity.minecraft.zombie_nautilus: Zombie Nautilus
+ item.intangible: Intangible
+ item.minecraft.copper_nautilus_armor: Copper Nautilus Armor
+ item.minecraft.copper_spear: Copper Spear
+ item.minecraft.diamond_nautilus_armor: Diamond Nautilus Armor
+ item.minecraft.diamond_spear: Diamond Spear
+ item.minecraft.golden_nautilus_armor: Golden Nautilus Armor
+ item.minecraft.golden_spear: Golden Spear
+ item.minecraft.iron_nautilus_armor: Iron Nautilus Armor
+ item.minecraft.iron_spear: Iron Spear
+ item.minecraft.nautilus_spawn_egg: Nautilus Spawn Egg
+ item.minecraft.netherite_nautilus_armor: Netherite Nautilus Armor
+ item.minecraft.netherite_spear: Netherite Spear
+ item.minecraft.stone_spear: Stone Spear
+ item.minecraft.wooden_spear: Wooden Spear
+ item.minecraft.zombie_nautilus_spawn_egg: Zombie Nautilus Spawn Egg
+ key.category.minecraft.debug: Debug
+ key.debug.clearChat: Clear chat
+ key.debug.copyLocation: Copy location
+ key.debug.copyRecreateCommand: Copy data
+ key.debug.crash: Debug crash
+ key.debug.debugOptions: Debug options
+ key.debug.dumpDynamicTextures: Dump dynamic textures
+ key.debug.dumpVersion: Dump version info
+ key.debug.focusPause: Toggle lost focus pause
+ key.debug.fpsCharts: FPS charts
+ key.debug.modifier: Debug modifier key
+ key.debug.networkCharts: Network charts
+ key.debug.overlay: Toggle overlay
+ key.debug.profiling: Start/stop profiling
+ key.debug.profilingChart: Profiling chart
+ key.debug.reloadChunk: Reload chunks
+ key.debug.reloadResourcePacks: Reload resource packs
+ key.debug.showAdvancedTooltips: Show advanced tooltips
+ key.debug.showChunkBorders: Show chunk boundaries
+ key.debug.showHitboxes: Show hitboxes
+ key.debug.spectate: Cycle spectator
+ key.debug.switchGameMode: Game mode switcher
+ key.toggleGui: Toggle GUI
+ key.toggleSpectatorShaderEffects: Toggle Spectator Shader Effects
+ mco.configure.world.name.validation.whitespace: Must not start or end with whitespace
+ narration.checkbox.usage.focused.check: Press Enter to check
+ narration.checkbox.usage.focused.uncheck: Press Enter to uncheck
+ narration.checkbox.usage.hovered.check: Left click to check
+ narration.checkbox.usage.hovered.uncheck: Left click to uncheck
+ options.blocks: %s Blocks
+ options.cutoutLeaves: See-Through Leaves
+ options.cutoutLeaves.tooltip: Allows to see through gaps in leaves. Disabling may improve performance.
+ options.graphics.custom: Custom
+ options.graphics.preset: Preset
+ options.graphics.preset.tooltip: Sets "Quality & Performance" settings to reasonable defaults corresponding to the desired quality.
+ options.improvedTransparency: Improved Transparency
+ options.improvedTransparency.tooltip: An experimental approach that uses screen shaders for drawing weather, clouds, and particles behind translucent blocks and water.
This will impact GPU performance.
+ options.video.display.header: Display
+ options.video.interface.header: Interface
+ options.video.quality.header: Quality & Performance
+ options.vignette: Show Vignette
+ options.vignette.tooltip: This is a subtle texture over the game screen used for reducing brightness towards the edges of the screen and warning about the world border.
+ options.weatherRadius: Weather Effect Radius
+ options.weatherRadius.tooltip: Radius of the area where rain and snow effects are visible. Very low performance impact.
+ subtitles.entity.baby_nautilus.ambient: Baby Nautilus chitters
+ subtitles.entity.baby_nautilus.death: Baby Nautilus dies
+ subtitles.entity.baby_nautilus.eat: Baby Nauilus eats
+ subtitles.entity.baby_nautilus.hurt: Baby Nautilus hurts
+ subtitles.entity.baby_nautilus.swim: Baby Nautilus swims
+ subtitles.entity.nautilus.ambient: Nautilus clacks
+ subtitles.entity.nautilus.dash_ready: Nautilus recovers
+ subtitles.entity.nautilus.dash: Nautilus jets
+ subtitles.entity.nautilus.death: Nautilus dies
+ subtitles.entity.nautilus.eat: Nauilus eats
+ subtitles.entity.nautilus.hurt: Nautilus hurts
+ subtitles.entity.nautilus.swim: Nautilus swims
+ subtitles.entity.zombie_horse.angry: Zombie Horse neighs
+ subtitles.entity.zombie_nautilus.ambient: Zombie Nautilus burbles
+ subtitles.entity.zombie_nautilus.dash_ready: Zombie Nautilus recovers
+ subtitles.entity.zombie_nautilus.dash: Zombie Nautilus jets
+ subtitles.entity.zombie_nautilus.death: Zombie Nautilus dies
+ subtitles.entity.zombie_nautilus.eat: Zombie Nautilus eats
+ subtitles.entity.zombie_nautilus.hurt: Zombie Nautilus hurts
+ subtitles.entity.zombie_nautilus.swim: Zombie Nautilus swims
+ subtitles.item.armor.equip_nautilus: Nautilus Armor equips
+ subtitles.item.armor.unequip_nautilus: Nautilus Armor unequips
+ subtitles.item.spear_wood.attack: Spear jabs
+ subtitles.item.spear_wood.hit: Spear hits
+ subtitles.item.spear_wood.use: Charges with Spear
+ subtitles.item.spear.attack: Spear jabs
+ subtitles.item.spear.hit: Spear hits
+ subtitles.item.spear.lunge: Spear lunges
+ subtitles.item.spear.use: Charges with Spear
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/combat/copper_spear.json
+ minecraft/advancement/recipes/combat/diamond_spear.json
+ minecraft/advancement/recipes/combat/golden_spear.json
+ minecraft/advancement/recipes/combat/iron_spear.json
+ minecraft/advancement/recipes/combat/netherite_nautilus_armor_smithing.json
+ minecraft/advancement/recipes/combat/netherite_spear_smithing.json
+ minecraft/advancement/recipes/combat/stone_spear.json
+ minecraft/advancement/recipes/combat/wooden_spear.json
+ minecraft/damage_type/spear.json
+ minecraft/enchantment/lunge.json
+ minecraft/loot_table/entities/nautilus.json
+ minecraft/loot_table/entities/zombie_nautilus.json
+ minecraft/recipe/copper_spear.json
+ minecraft/recipe/diamond_spear.json
+ minecraft/recipe/golden_spear.json
+ minecraft/recipe/iron_spear.json
+ minecraft/recipe/netherite_nautilus_armor_smithing.json
+ minecraft/recipe/netherite_spear_smithing.json
+ minecraft/recipe/stone_spear.json
+ minecraft/recipe/wooden_spear.json
+ minecraft/tags/block/can_glide_through.json
+ minecraft/tags/enchantment/exclusive_set/lunge.json
+ minecraft/tags/entity_type/burn_in_daylight.json
+ minecraft/tags/entity_type/can_wear_nautilus_armor.json
+ minecraft/tags/entity_type/nautilus_hostiles.json
+ minecraft/tags/item/enchantable/lunge.json
+ minecraft/tags/item/enchantable/melee_weapon.json
+ minecraft/tags/item/enchantable/sweeping.json
- minecraft/tags/item/enchantable/sword.json
+ minecraft/tags/item/nautilus_bucket_food.json
+ minecraft/tags/item/nautilus_food.json
+ minecraft/tags/item/nautilus_taming_items.json
+ minecraft/tags/item/spears.json
+ minecraft/tags/item/zombie_horse_food.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/atlases/celestials.json
+ minecraft/items/copper_nautilus_armor.json
+ minecraft/items/copper_spear.json
+ minecraft/items/diamond_nautilus_armor.json
+ minecraft/items/diamond_spear.json
+ minecraft/items/golden_nautilus_armor.json
+ minecraft/items/golden_spear.json
+ minecraft/items/iron_nautilus_armor.json
+ minecraft/items/iron_spear.json
+ minecraft/items/nautilus_spawn_egg.json
+ minecraft/items/netherite_nautilus_armor.json
+ minecraft/items/netherite_spear.json
+ minecraft/items/stone_spear.json
+ minecraft/items/wooden_spear.json
+ minecraft/items/zombie_nautilus_spawn_egg.json
+ minecraft/models/item/copper_nautilus_armor.json
+ minecraft/models/item/copper_spear_in_hand.json
+ minecraft/models/item/copper_spear.json
+ minecraft/models/item/diamond_nautilus_armor.json
+ minecraft/models/item/diamond_spear_in_hand.json
+ minecraft/models/item/diamond_spear.json
+ minecraft/models/item/golden_nautilus_armor.json
+ minecraft/models/item/golden_spear_in_hand.json
+ minecraft/models/item/golden_spear.json
+ minecraft/models/item/iron_nautilus_armor.json
+ minecraft/models/item/iron_spear_in_hand.json
+ minecraft/models/item/iron_spear.json
+ minecraft/models/item/nautilus_spawn_egg.json
+ minecraft/models/item/netherite_nautilus_armor.json
+ minecraft/models/item/netherite_spear_in_hand.json
+ minecraft/models/item/netherite_spear.json
+ minecraft/models/item/spear_in_hand.json
+ minecraft/models/item/stone_spear_in_hand.json
+ minecraft/models/item/stone_spear.json
+ minecraft/models/item/wooden_spear_in_hand.json
+ minecraft/models/item/wooden_spear.json
+ minecraft/models/item/zombie_nautilus_spawn_egg.json
+ minecraft/shaders/core/debug_point.vsh
+ minecraft/textures/block/acacia_leaves.png.mcmeta
+ minecraft/textures/block/azalea_leaves.png.mcmeta
+ minecraft/textures/block/birch_leaves.png.mcmeta
+ minecraft/textures/block/cherry_leaves.png.mcmeta
+ minecraft/textures/block/dark_oak_leaves.png.mcmeta
+ minecraft/textures/block/flowering_azalea_leaves.png.mcmeta
+ minecraft/textures/block/jungle_leaves.png.mcmeta
+ minecraft/textures/block/mangrove_leaves.png.mcmeta
+ minecraft/textures/block/mangrove_roots_side.png.mcmeta
+ minecraft/textures/block/mangrove_roots_top.png.mcmeta
+ minecraft/textures/block/oak_leaves.png.mcmeta
+ minecraft/textures/block/pale_oak_leaves.png.mcmeta
+ minecraft/textures/block/spruce_leaves.png.mcmeta
+ minecraft/textures/entity/equipment/nautilus_body/copper.png
+ minecraft/textures/entity/equipment/nautilus_body/diamond.png
+ minecraft/textures/entity/equipment/nautilus_body/gold.png
+ minecraft/textures/entity/equipment/nautilus_body/iron.png
+ minecraft/textures/entity/equipment/nautilus_body/netherite.png
+ minecraft/textures/entity/equipment/nautilus_saddle/saddle.png
+ minecraft/textures/entity/nautilus/nautilus_baby.png
+ minecraft/textures/entity/nautilus/nautilus.png
+ minecraft/textures/entity/nautilus/zombie_nautilus.png
+ minecraft/textures/environment/celestial/end_flash.png
+ minecraft/textures/environment/celestial/moon/first_quarter.png
+ minecraft/textures/environment/celestial/moon/full_moon.png
+ minecraft/textures/environment/celestial/moon/new_moon.png
+ minecraft/textures/environment/celestial/moon/third_quarter.png
+ minecraft/textures/environment/celestial/moon/waning_crescent.png
+ minecraft/textures/environment/celestial/moon/waning_gibbous.png
+ minecraft/textures/environment/celestial/moon/waxing_crescent.png
+ minecraft/textures/environment/celestial/moon/waxing_gibbous.png
+ minecraft/textures/environment/celestial/sun.png
- minecraft/textures/environment/end_flash.png
- minecraft/textures/environment/moon_phases.png
- minecraft/textures/environment/sun.png
+ minecraft/textures/gui/sprites/container/inventory/effect_background_ambient.png
+ minecraft/textures/gui/sprites/container/inventory/effect_background_ambient.png.mcmeta
- minecraft/textures/gui/sprites/container/inventory/effect_background_large.png
- minecraft/textures/gui/sprites/container/inventory/effect_background_small.png
+ minecraft/textures/gui/sprites/container/inventory/effect_background.png
+ minecraft/textures/gui/sprites/container/inventory/effect_background.png.mcmeta
+ minecraft/textures/gui/sprites/container/slot/nautilus_armor.png
+ minecraft/textures/gui/sprites/container/slot/spear.png
+ minecraft/textures/item/copper_nautilus_armor.png
+ minecraft/textures/item/copper_spear_in_hand.png
+ minecraft/textures/item/copper_spear.png
+ minecraft/textures/item/diamond_nautilus_armor.png
+ minecraft/textures/item/diamond_spear_in_hand.png
+ minecraft/textures/item/diamond_spear.png
+ minecraft/textures/item/golden_nautilus_armor.png
+ minecraft/textures/item/golden_spear_in_hand.png
+ minecraft/textures/item/golden_spear.png
+ minecraft/textures/item/iron_nautilus_armor.png
+ minecraft/textures/item/iron_spear_in_hand.png
+ minecraft/textures/item/iron_spear.png
+ minecraft/textures/item/nautilus_spawn_egg.png
+ minecraft/textures/item/netherite_nautilus_armor.png
+ minecraft/textures/item/netherite_spear_in_hand.png
+ minecraft/textures/item/netherite_spear.png
+ minecraft/textures/item/stone_spear_in_hand.png
+ minecraft/textures/item/stone_spear.png
+ minecraft/textures/item/wooden_spear_in_hand.png
+ minecraft/textures/item/wooden_spear.png
+ minecraft/textures/item/zombie_nautilus_spawn_egg.png
+ minecraft/textures/mob_effect/breath_of_the_nautilus.png
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
+ minecraft:float_range
```

</details>
<details>
<summary>
rpc-api-methods
</summary>

```diff
+ minecraft:notification/server/activity
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
- XXX.ai.behavior.ChargeAttack
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
- XXX.ai.behavior.LongJumpUtil
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.OneShot
- XXX.ai.behavior.package-info
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetEntityLookTargetSometimes
- XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartAttacking$StartAttackingCondition
- XXX.ai.behavior.StartAttacking$TargetFinder
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TransportItemsBetweenContainers
+ XXX.ai.behavior.TransportItemsBetweenContainers$ContainerInteractionState
- XXX.ai.behavior.TransportItemsBetweenContainers$OnTargetReachedInteraction
+ XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemState
- XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemTarget
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
- XXX.ai.goal.SpearUseGoal
- XXX.animal.nautilus.AbstractNautilus
- XXX.animal.nautilus.NautilusAi
- XXX.animal.nautilus.ZombieNautilusAi
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
- XXX.block.entity.BlockEntity$BlockEntityPathElement
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
+ XXX.block.entity.CopperGolemStatueBlockEntity
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
- XXX.block.entity.ListBackedContainer
- XXX.block.entity.package-info
+ XXX.block.entity.PotDecorations
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
+ XXX.block.entity.ShelfBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
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
+ XXX.block.entity.TestInstanceBlockEntity$ErrorMarker
- XXX.block.entity.TestInstanceBlockEntity$Status
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.entity.TrialSpawnerBlockEntity
+ XXX.block.grower.package-info
- XXX.block.grower.TreeGrower
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
- XXX.block.sounds.package-info
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
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.ObjectContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
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
- XXX.common.custom.BrandPayload
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.package-info
- XXX.component.predicates.AnyValue
+ XXX.component.predicates.AttributeModifiersPredicate
- XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
+ XXX.component.predicates.BundlePredicate
- XXX.component.predicates.ContainerPredicate
+ XXX.component.predicates.CustomDataPredicate
- XXX.component.predicates.DamagePredicate
+ XXX.component.predicates.DataComponentPredicate
- XXX.component.predicates.DataComponentPredicate$AnyValueType
- XXX.component.predicates.DataComponentPredicate$Single
+ XXX.component.predicates.DataComponentPredicate$Type
- XXX.component.predicates.DataComponentPredicate$TypeBase
- XXX.contents.data.BlockDataSource
+ XXX.contents.data.DataSource
- XXX.contents.data.DataSources
+ XXX.contents.data.EntityDataSource
+ XXX.contents.data.package-info
- XXX.contents.data.StorageDataSource
- XXX.contents.objects.AtlasSprite
+ XXX.contents.objects.ObjectInfo
- XXX.contents.objects.ObjectInfos
- XXX.contents.objects.package-info
+ XXX.contents.objects.PlayerSprite
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractBlockPropertyFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFieldFix
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
+ XXX.datafix.fixes.CopperGolemWeatherStateFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.CustomModelDataExpandFix
- XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsSetGraphicsPresetToCustomFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerEquipmentFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerRespawnDataFix
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
+ XXX.datafix.fixes.RemoveBlockEntityTagFix
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
+ XXX.datafix.fixes.SignTextStrictJsonFix
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
- XXX.datafix.fixes.TridentAnimationFix
- XXX.datafix.schemas.package-info
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
- XXX.dialog.action.Action
+ XXX.dialog.action.Action$ValueGetter
- XXX.dialog.action.Action$ValueGetter$1
+ XXX.dialog.action.Action$ValueGetter$2
- XXX.dialog.action.ActionTypes
+ XXX.dialog.action.CommandTemplate
- XXX.dialog.action.CustomAll
+ XXX.dialog.action.package-info
+ XXX.dialog.action.ParsedTemplate
- XXX.dialog.action.StaticAction
- XXX.dialog.body.DialogBody
+ XXX.dialog.body.DialogBodyTypes
- XXX.dialog.body.ItemBody
- XXX.dialog.body.package-info
+ XXX.dialog.body.PlainMessage
+ XXX.dialog.input.BooleanInput
- XXX.dialog.input.InputControl
+ XXX.dialog.input.InputControlTypes
- XXX.dialog.input.NumberRangeInput
+ XXX.dialog.input.NumberRangeInput$RangeInfo
- XXX.dialog.input.package-info
- XXX.dialog.input.SingleOptionInput
+ XXX.dialog.input.SingleOptionInput$Entry
- XXX.dialog.input.TextInput
+ XXX.dialog.input.TextInput$MultilineOptions
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyEntityImpulse
- XXX.enchantment.effects.package-info
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
+ XXX.entity.trialspawner.package-info
+ XXX.entity.trialspawner.PlayerDetector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
+ XXX.entity.trialspawner.TrialSpawner
- XXX.entity.trialspawner.TrialSpawner$FlameParticle
+ XXX.entity.trialspawner.TrialSpawner$FullConfig
- XXX.entity.trialspawner.TrialSpawner$StateAccessor
+ XXX.entity.trialspawner.TrialSpawnerConfig
- XXX.entity.trialspawner.TrialSpawnerConfig$Builder
+ XXX.entity.trialspawner.TrialSpawnerConfigs
- XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
+ XXX.entity.trialspawner.TrialSpawnerState
- XXX.entity.trialspawner.TrialSpawnerState$LightLevel
+ XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
- XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
+ XXX.entity.trialspawner.TrialSpawnerStateData
- XXX.entity.trialspawner.TrialSpawnerStateData$Packed
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
+ XXX.equipment.trim.ArmorTrim
- XXX.equipment.trim.MaterialAssetGroup
+ XXX.equipment.trim.MaterialAssetGroup$AssetInfo
- XXX.equipment.trim.package-info
- XXX.equipment.trim.TrimMaterial
+ XXX.equipment.trim.TrimMaterials
- XXX.equipment.trim.TrimPattern
+ XXX.equipment.trim.TrimPatterns
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
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
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
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.KineticWeapon
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
- XXX.item.component.PiercingWeapon
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.TypedEntityData
+ XXX.item.component.TypedEntityData$1
- XXX.item.component.UseCooldown
- XXX.item.enchantment.LevelBasedValue$Exponent
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
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.ChunkRegionIoEvent
- XXX.jfr.event.ChunkRegionIoEvent$Fields
+ XXX.jfr.event.ChunkRegionReadEvent
- XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.ClientFpsEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.StructureGenerationEvent
+ XXX.jfr.event.StructureGenerationEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.ChunkIdentification
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
- XXX.jsonrpc.api.MethodInfo
+ XXX.jsonrpc.api.MethodInfo$Named
- XXX.jsonrpc.api.package-info
- XXX.jsonrpc.api.ParamInfo
+ XXX.jsonrpc.api.PlayerDto
- XXX.jsonrpc.api.ReferenceUtil
+ XXX.jsonrpc.api.ResultInfo
- XXX.jsonrpc.api.Schema
+ XXX.jsonrpc.api.SchemaComponent
+ XXX.jsonrpc.dataprovider.JsonRpcApiSchema
- XXX.jsonrpc.dataprovider.package-info
+ XXX.jsonrpc.internalapi.GameRules
- XXX.jsonrpc.internalapi.MinecraftAllowListService
+ XXX.jsonrpc.internalapi.MinecraftAllowListServiceImpl
- XXX.jsonrpc.internalapi.MinecraftApi
+ XXX.jsonrpc.internalapi.MinecraftBanListService
- XXX.jsonrpc.internalapi.MinecraftBanListServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftExecutorService
- XXX.jsonrpc.internalapi.MinecraftExecutorServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftGameRuleService
- XXX.jsonrpc.internalapi.MinecraftGameRuleServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftOperatorListService
- XXX.jsonrpc.internalapi.MinecraftOperatorListServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftPlayerListService
- XXX.jsonrpc.internalapi.MinecraftPlayerListServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftServerSettingsService
- XXX.jsonrpc.internalapi.MinecraftServerSettingsServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftServerStateService
- XXX.jsonrpc.internalapi.MinecraftServerStateServiceImpl
+ XXX.jsonrpc.internalapi.package-info
- XXX.jsonrpc.methods.AllowlistService
+ XXX.jsonrpc.methods.BanlistService
- XXX.jsonrpc.methods.BanlistService$UserBan
+ XXX.jsonrpc.methods.BanlistService$UserBanDto
- XXX.jsonrpc.methods.ClientInfo
+ XXX.jsonrpc.methods.DiscoveryService
- XXX.jsonrpc.methods.DiscoveryService$DiscoverComponents
+ XXX.jsonrpc.methods.DiscoveryService$DiscoverInfo
- XXX.jsonrpc.methods.DiscoveryService$DiscoverResponse
+ XXX.jsonrpc.methods.EncodeJsonRpcException
- XXX.jsonrpc.methods.GameRulesService
+ XXX.jsonrpc.methods.GameRulesService$RuleType
- XXX.jsonrpc.methods.GameRulesService$TypedRule
+ XXX.jsonrpc.methods.GameRulesService$UntypedRule
- XXX.jsonrpc.methods.IllegalMethodDefinitionException
+ XXX.jsonrpc.methods.InvalidParameterJsonRpcException
- XXX.jsonrpc.methods.InvalidRequestJsonRpcException
+ XXX.jsonrpc.methods.IpBanlistService
- XXX.jsonrpc.methods.IpBanlistService$IncomingIpBanDto
+ XXX.jsonrpc.methods.IpBanlistService$IpBan
- XXX.jsonrpc.methods.IpBanlistService$IpBanDto
+ XXX.jsonrpc.methods.Message
- XXX.jsonrpc.methods.MethodNotFoundJsonRpcException
+ XXX.jsonrpc.methods.OperatorService
- XXX.jsonrpc.methods.OperatorService$Op
+ XXX.jsonrpc.methods.OperatorService$OperatorDto
+ XXX.jsonrpc.methods.package-info
- XXX.jsonrpc.methods.PlayerService
+ XXX.jsonrpc.methods.PlayerService$KickDto
- XXX.jsonrpc.methods.RemoteRpcErrorException
+ XXX.jsonrpc.methods.ServerSettingsService
- XXX.jsonrpc.methods.ServerStateService
+ XXX.jsonrpc.methods.ServerStateService$ServerState
- XXX.jsonrpc.methods.ServerStateService$SystemMessage
+ XXX.jsonrpc.security.AuthenticationHandler
- XXX.jsonrpc.security.AuthenticationHandler$SecurityCheckResult
+ XXX.jsonrpc.security.JsonRpcSslContextProvider
+ XXX.jsonrpc.security.package-info
- XXX.jsonrpc.security.SecurityConfig
- XXX.jsonrpc.websocket.JsonToWebSocketEncoder
- XXX.jsonrpc.websocket.package-info
+ XXX.jsonrpc.websocket.WebSocketToJsonCodec
- XXX.level.block.Block$UpdateFlags
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
+ XXX.level.block.CopperChestBlock
- XXX.level.block.CopperGolemStatueBlock
+ XXX.level.block.CopperGolemStatueBlock$Pose
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
+ XXX.level.block.DriedGhastBlock
- XXX.level.block.DropExperienceBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.DryVegetationBlock
+ XXX.level.block.EnchantingTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.EyeblossomBlock
+ XXX.level.block.EyeblossomBlock$Type
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FireflyBushBlock
- XXX.level.block.FlowerBedBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrogspawnBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FungusBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingMossBlock
+ XXX.level.block.HangingRootsBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HeavyCoreBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
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
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeafLitterBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
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
- XXX.level.block.package-info
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
- XXX.level.block.SelectableSlotContainer
+ XXX.level.block.SelectableSlotContainer$1
- XXX.level.block.ShelfBlock
+ XXX.level.block.ShortDryGrassBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SideChainPartBlock
+ XXX.level.block.SideChainPartBlock$EmptyNeighbor
- XXX.level.block.SideChainPartBlock$Neighbor
+ XXX.level.block.SideChainPartBlock$Neighbors
- XXX.level.block.SideChainPartBlock$SideChainNeighbor
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
- XXX.level.block.StonecutterBlock
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
+ XXX.level.block.TallDryGrassBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
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
- XXX.level.block.WeatheringCopperBarsBlock
+ XXX.level.block.WeatheringCopperBlocks
- XXX.level.block.WeatheringCopperBulbBlock
+ XXX.level.block.WeatheringCopperChainBlock
- XXX.level.block.WeatheringCopperChestBlock
+ XXX.level.block.WeatheringCopperDoorBlock
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperGolemStatueBlock
- XXX.level.block.WeatheringCopperGrateBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WeatheringCopperTrapDoorBlock
- XXX.level.block.WeatheringLanternBlock
+ XXX.level.block.WeatheringLightningRodBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
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
- XXX.level.chunk.ChunkAccess$ChunkPathElement
+ XXX.level.chunk.ChunkAccess$PackedTicks
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.Configuration
+ XXX.level.chunk.Configuration$Global
- XXX.level.chunk.Configuration$Simple
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
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
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainerFactory
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
+ XXX.level.chunk.Strategy
- XXX.level.chunk.Strategy$1
+ XXX.level.chunk.Strategy$2
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
- XXX.level.levelgen.DensityFunctions$FindTopSurface
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
- XXX.level.levelgen.package-info
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
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Context
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
+ XXX.levelgen.feature.package-info
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
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackFormat
+ XXX.metadata.pack.PackFormat$1
- XXX.metadata.pack.PackFormat$IntermediaryFormat
+ XXX.metadata.pack.PackFormat$IntermediaryFormatHolder
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSection$1
+ XXX.minecraft.commands.PermissionSource
- XXX.minecraft.gizmos.CircleGizmo
- XXX.minecraft.gizmos.Gizmo
- XXX.minecraft.gizmos.GizmoPrimitives
- XXX.minecraft.gizmos.Gizmos$TemporaryCollection
- XXX.minecraft.gizmos.GizmoStyle
- XXX.minecraft.gizmos.PointGizmo
- XXX.minecraft.gizmos.RectGizmo$1
- XXX.minecraft.gizmos.SimpleGizmoCollector$GizmoInstance
- XXX.minecraft.gizmos.TextGizmo$Style
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
- XXX.minecraft.nbt.CollectionTag$1
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
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$GenericListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.PrimitiveTag
+ XXX.minecraft.nbt.ReportedNbtException
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtGrammar
- XXX.minecraft.nbt.SnbtGrammar$1
+ XXX.minecraft.nbt.SnbtGrammar$2
- XXX.minecraft.nbt.SnbtGrammar$3
+ XXX.minecraft.nbt.SnbtGrammar$4
- XXX.minecraft.nbt.SnbtGrammar$5
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
+ XXX.minecraft.nbt.SnbtGrammar$Base
- XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
+ XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
- XXX.minecraft.nbt.SnbtGrammar$Sign
+ XXX.minecraft.nbt.SnbtGrammar$Signed
- XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
+ XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
- XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
+ XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$1
+ XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$3
+ XXX.minecraft.nbt.SnbtOperations$BuiltinKey
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
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
- XXX.minecraft.network.HashedPatchMap
+ XXX.minecraft.network.HashedPatchMap$HashGenerator
- XXX.minecraft.network.HashedStack
+ XXX.minecraft.network.HashedStack$1
- XXX.minecraft.network.HashedStack$ActualItem
+ XXX.minecraft.network.HiddenByteBuf
- XXX.minecraft.network.LocalFrameDecoder
+ XXX.minecraft.network.LocalFrameEncoder
- XXX.minecraft.network.LpVec3
+ XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketProcessor
- XXX.minecraft.network.PacketProcessor$ListenerAndPacket
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.ProtocolInfo
+ XXX.minecraft.network.ProtocolInfo$Details
- XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
+ XXX.minecraft.network.ProtocolInfo$DetailsProvider
- XXX.minecraft.network.ProtocolSwapHandler
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.RegistryFriendlyByteBuf
+ XXX.minecraft.network.ServerboundPacketListener
- XXX.minecraft.network.SkipPacketDecoderException
+ XXX.minecraft.network.SkipPacketEncoderException
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
+ XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.package-info
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
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerTickRateManager
+ XXX.minecraft.server.Services
- XXX.minecraft.server.SuppressedExceptionCollector
+ XXX.minecraft.server.SuppressedExceptionCollector$LongEntry
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
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$1
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
- XXX.minecraft.stats.ServerRecipeBook$Packed
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
- XXX.minecraft.tags.DialogTags
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
- XXX.minecraft.util.BoundedFloatFunction
+ XXX.minecraft.util.BoundedFloatFunction$1
- XXX.minecraft.util.BoundedFloatFunction$2
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
- XXX.minecraft.util.Ease
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
+ XXX.minecraft.util.LenientJsonParser
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.ListAndDeque
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.NullOps
- XXX.minecraft.util.NullOps$1
+ XXX.minecraft.util.NullOps$NullListBuilder
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.package-info
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.PlaceholderLookupProvider
- XXX.minecraft.util.PlaceholderLookupProvider$1
+ XXX.minecraft.util.PlaceholderLookupProvider$2
- XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
+ XXX.minecraft.util.PngInfo
- XXX.minecraft.util.ProblemReporter
+ XXX.minecraft.util.ProblemReporter$1
- XXX.minecraft.util.ProblemReporter$Collector
+ XXX.minecraft.util.ProblemReporter$Collector$Entry
- XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
+ XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
- XXX.minecraft.util.ProblemReporter$FieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedPathElement
+ XXX.minecraft.util.ProblemReporter$PathElement
- XXX.minecraft.util.ProblemReporter$Problem
+ XXX.minecraft.util.ProblemReporter$RootElementPathElement
- XXX.minecraft.util.ProblemReporter$RootFieldPathElement
+ XXX.minecraft.util.ProblemReporter$ScopedCollector
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
- XXX.minecraft.util.StrictJsonParser
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
+ XXX.minecraft.util.TriState
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.Stopwatches
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.CollectToTag$CompoundBuilder
- XXX.nbt.visitors.CollectToTag$ContainerBuilder
+ XXX.nbt.visitors.CollectToTag$ListBuilder
- XXX.nbt.visitors.CollectToTag$RootBuilder
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
- XXX.network.chat.ClickEvent$ChangePage
+ XXX.network.chat.ClickEvent$CopyToClipboard
- XXX.network.chat.ClickEvent$Custom
+ XXX.network.chat.ClickEvent$OpenFile
- XXX.network.chat.ClickEvent$OpenUrl
+ XXX.network.chat.ClickEvent$RunCommand
- XXX.network.chat.ClickEvent$ShowDialog
+ XXX.network.chat.ClickEvent$SuggestCommand
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FontDescription
+ XXX.network.chat.FontDescription$AtlasSprite
- XXX.network.chat.FontDescription$PlayerSprite
+ XXX.network.chat.FontDescription$Resource
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
- XXX.network.chat.HoverEvent$ShowEntity
+ XXX.network.chat.HoverEvent$ShowItem
- XXX.network.chat.HoverEvent$ShowText
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ValidationException
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
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
+ XXX.network.codec.ByteBufCodecs$29
- XXX.network.codec.ByteBufCodecs$3
+ XXX.network.codec.ByteBufCodecs$30
- XXX.network.codec.ByteBufCodecs$31
+ XXX.network.codec.ByteBufCodecs$32
- XXX.network.codec.ByteBufCodecs$33
+ XXX.network.codec.ByteBufCodecs$34
- XXX.network.codec.ByteBufCodecs$35
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
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
- XXX.network.codec.StreamCodec$17
- XXX.network.codec.StreamCodec$19
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
+ XXX.network.syncher.package-info
- XXX.network.syncher.SyncedDataHolder
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$Builder
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
+ XXX.packrat.commands.CommandArgumentParser
- XXX.packrat.commands.CommandArgumentParser$1
+ XXX.packrat.commands.CommandArgumentParser$2
- XXX.packrat.commands.Grammar
+ XXX.packrat.commands.GreedyPatternParseRule
- XXX.packrat.commands.GreedyPredicateParseRule
+ XXX.packrat.commands.NumberRunParseRule
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ParserBasedArgument
+ XXX.packrat.commands.ResourceLocationParseRule
- XXX.packrat.commands.ResourceLookupRule
+ XXX.packrat.commands.ResourceSuggestion
- XXX.packrat.commands.StringReaderParserState
+ XXX.packrat.commands.StringReaderTerms
- XXX.packrat.commands.StringReaderTerms$1
+ XXX.packrat.commands.StringReaderTerms$2
- XXX.packrat.commands.StringReaderTerms$TerminalCharacters
+ XXX.packrat.commands.StringReaderTerms$TerminalWord
- XXX.packrat.commands.TagParseRule
+ XXX.packrat.commands.UnquotedStringParseRule
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
+ XXX.packs.metadata.MetadataSectionType$WithValue
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
+ XXX.packs.resources.PreparableReloadListener$SharedState
- XXX.packs.resources.PreparableReloadListener$StateKey
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
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.CachedParseState
- XXX.parsing.packrat.CachedParseState$CacheEntry
+ XXX.parsing.packrat.CachedParseState$PositionCache
- XXX.parsing.packrat.CachedParseState$Silent
+ XXX.parsing.packrat.CachedParseState$SimpleControl
- XXX.parsing.packrat.Control
+ XXX.parsing.packrat.Control$1
- XXX.parsing.packrat.DelayedException
+ XXX.parsing.packrat.Dictionary
- XXX.parsing.packrat.Dictionary$Entry
+ XXX.parsing.packrat.Dictionary$Reference
- XXX.parsing.packrat.ErrorCollector
+ XXX.parsing.packrat.ErrorCollector$LongestOnly
- XXX.parsing.packrat.ErrorCollector$LongestOnly$MutableErrorEntry
+ XXX.parsing.packrat.ErrorCollector$Nop
- XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.NamedRule
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.Scope$1
+ XXX.parsing.packrat.SuggestionSupplier
- XXX.parsing.packrat.Term
+ XXX.parsing.packrat.Term$1
- XXX.parsing.packrat.Term$2
+ XXX.parsing.packrat.Term$3
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$LookAhead
- XXX.parsing.packrat.Term$Marker
+ XXX.parsing.packrat.Term$Maybe
- XXX.parsing.packrat.Term$Repeated
+ XXX.parsing.packrat.Term$RepeatedWithSeparator
- XXX.parsing.packrat.Term$Sequence
+ XXX.pools.alias.DirectPoolAlias
+ XXX.pools.alias.package-info
- XXX.pools.alias.PoolAliasBinding
+ XXX.pools.alias.PoolAliasBindings
- XXX.pools.alias.PoolAliasLookup
+ XXX.pools.alias.RandomGroupPoolAlias
- XXX.pools.alias.RandomPoolAlias
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JfrProfiler$3
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
+ XXX.protocol.common.ClientboundShowDialogPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomClickActionPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundCodeOfConductPacket
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
- XXX.protocol.configuration.ConfigurationPacketTypes
+ XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
+ XXX.protocol.configuration.ServerboundAcceptCodeOfConductPacket
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
- XXX.protocol.configuration.ServerConfigurationPacketListener
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
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
+ XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
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
- XXX.protocol.game.ClientboundDebugBlockValuePacket
+ XXX.protocol.game.ClientboundDebugChunkValuePacket
- XXX.protocol.game.ClientboundDebugEntityValuePacket
+ XXX.protocol.game.ClientboundDebugEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundGameTestHighlightPosPacket
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
+ XXX.protocol.game.ClientboundTrackedWaypointPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChangeGameModePacket
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
+ XXX.protocol.game.ServerboundDebugSubscriptionRequestPacket
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
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
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
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
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
- XXX.server.commands.DialogCommand
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
- XXX.server.commands.FetchProfileCommand
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$1UpdatedPosition
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
+ XXX.server.commands.package-info
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PerfCommand
+ XXX.server.commands.PermissionCheck
- XXX.server.commands.StopwatchCommand
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
- XXX.server.commands.VersionCommand
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WaypointCommand
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
+ XXX.server.dialog.ActionButton
- XXX.server.dialog.ButtonListDialog
+ XXX.server.dialog.CommonButtonData
- XXX.server.dialog.CommonDialogData
+ XXX.server.dialog.ConfirmationDialog
- XXX.server.dialog.Dialog
+ XXX.server.dialog.DialogAction
- XXX.server.dialog.DialogListDialog
- XXX.server.dialog.Dialogs
+ XXX.server.dialog.DialogTypes
+ XXX.server.dialog.Input
- XXX.server.dialog.MultiActionDialog
+ XXX.server.dialog.NoticeDialog
+ XXX.server.dialog.package-info
- XXX.server.dialog.ServerLinksDialog
+ XXX.server.dialog.SimpleDialog
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.jsonrpc.Connection
+ XXX.server.jsonrpc.IncomingRpcMethod
- XXX.server.jsonrpc.IncomingRpcMethod$Attributes
+ XXX.server.jsonrpc.IncomingRpcMethod$Factory
- XXX.server.jsonrpc.IncomingRpcMethod$IncomingRpcMethodBuilder
+ XXX.server.jsonrpc.IncomingRpcMethod$Method
- XXX.server.jsonrpc.IncomingRpcMethod$ParameterlessMethod
+ XXX.server.jsonrpc.IncomingRpcMethod$ParameterlessRpcMethodFunction
- XXX.server.jsonrpc.IncomingRpcMethod$RpcMethodFunction
+ XXX.server.jsonrpc.IncomingRpcMethods
- XXX.server.jsonrpc.JsonRPCErrors
- XXX.server.jsonrpc.JsonRpcLogger
+ XXX.server.jsonrpc.JsonRpcNotificationService
+ XXX.server.jsonrpc.JsonRPCUtils
- XXX.server.jsonrpc.ManagementServer
+ XXX.server.jsonrpc.ManagementServer$1
- XXX.server.jsonrpc.OutgoingRpcMethod
+ XXX.server.jsonrpc.OutgoingRpcMethod$Attributes
- XXX.server.jsonrpc.OutgoingRpcMethod$Factory
+ XXX.server.jsonrpc.OutgoingRpcMethod$Method
- XXX.server.jsonrpc.OutgoingRpcMethod$Notification
+ XXX.server.jsonrpc.OutgoingRpcMethod$OutgoingRpcMethodBuilder
- XXX.server.jsonrpc.OutgoingRpcMethod$ParameterlessMethod
+ XXX.server.jsonrpc.OutgoingRpcMethod$ParmeterlessNotification
- XXX.server.jsonrpc.OutgoingRpcMethods
- XXX.server.jsonrpc.package-info
+ XXX.server.jsonrpc.PendingRpcRequest
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkGenerationTask
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkLoadCounter
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
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.GeneratingChunkMap
- XXX.server.level.GenerationChunkHolder
+ XXX.server.level.LoadingChunkTracker
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerSpawnFinder
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerEntity$Synchronizer
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
- XXX.server.level.ServerPlayer$SavedPosition
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.SimulationChunkTracker
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.ThrottlingChunkTaskDispatcher
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TicketType$Flags
- XXX.server.notifications.package-info
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
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$1
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.OverlayMetadataSection$OverlayEntry$IntermediateEntry
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
- XXX.server.permissions.LevelBasedPermissionSet
- XXX.server.permissions.LevelBasedPermissionSet$2
- XXX.server.permissions.package-info
- XXX.server.permissions.Permission$Atom
- XXX.server.permissions.PermissionCheck
- XXX.server.permissions.PermissionCheck$Require
- XXX.server.permissions.PermissionLevel
- XXX.server.permissions.PermissionSet
- XXX.server.permissions.PermissionTypes
+ XXX.server.players.package-info
- XXX.server.players.PlayerList$2
+ XXX.server.players.ProfileResolver
- XXX.server.players.ProfileResolver$Cached
+ XXX.server.players.ProfileResolver$Cached$1
- XXX.server.players.ProfileResolver$Cached$2
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserNameToIdResolver
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
+ XXX.server.waypoints.package-info
- XXX.server.waypoints.ServerWaypointManager
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
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.RotationSegment
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SideChainPart
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.TestBlockMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
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
+ XXX.structure.structures.JigsawStructure$MaxDistance
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
- XXX.structure.templatesystem.package-info
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
+ XXX.structure.templatesystem.TagMatchTest
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
+ XXX.util.datafix.PackedBitStorage
+ XXX.util.debug.DebugBeeInfo
- XXX.util.debug.DebugBrainDump
+ XXX.util.debug.DebugBreezeInfo
- XXX.util.debug.DebugEntityBlockIntersection
+ XXX.util.debug.DebugGameEventInfo
- XXX.util.debug.DebugGameEventListenerInfo
+ XXX.util.debug.DebugGoalInfo
- XXX.util.debug.DebugGoalInfo$DebugGoal
+ XXX.util.debug.DebugHiveInfo
- XXX.util.debug.DebugPathInfo
+ XXX.util.debug.DebugPoiInfo
- XXX.util.debug.DebugStructureInfo
+ XXX.util.debug.DebugStructureInfo$Piece
- XXX.util.debug.DebugSubscription
+ XXX.util.debug.DebugSubscription$Event
- XXX.util.debug.DebugSubscription$Update
+ XXX.util.debug.DebugSubscriptions
- XXX.util.debug.DebugValueAccess
+ XXX.util.debug.DebugValueAccess$EventVisitor
- XXX.util.debug.DebugValueSource
+ XXX.util.debug.DebugValueSource$Registration
- XXX.util.debug.DebugValueSource$ValueGetter
+ XXX.util.debug.LevelDebugSynchronizers
- XXX.util.debug.LevelDebugSynchronizers$1
+ XXX.util.debug.LevelDebugSynchronizers$2
- XXX.util.debug.LevelDebugSynchronizers$3
+ XXX.util.debug.package-info
+ XXX.util.debug.ServerDebugSubscribers
- XXX.util.debug.TrackingDebugSynchronizer
+ XXX.util.debug.TrackingDebugSynchronizer$PoiSynchronizer
- XXX.util.debug.TrackingDebugSynchronizer$SourceSynchronizer
+ XXX.util.debug.TrackingDebugSynchronizer$ValueSource
- XXX.util.debug.TrackingDebugSynchronizer$VillageSectionSynchronizer
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.package-info
- XXX.util.debugchart.RemoteDebugSampleType
+ XXX.util.debugchart.RemoteSampleLogger
- XXX.util.debugchart.SampleLogger
+ XXX.util.debugchart.SampleStorage
- XXX.util.debugchart.TpsDebugDimensions
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
- XXX.util.profiling.ProfileCollector
- XXX.util.profiling.Profiler
+ XXX.util.profiling.Profiler$Scope
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.profiling.TracyZoneFiller
- XXX.util.profiling.TracyZoneFiller$PlotAndValue
+ XXX.util.profiling.Zone
+ XXX.world.item.package-info
- XXX.world.item.SwingAnimationType
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WeatheringCopperItems
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
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
- XXX.world.level.MoonPhase
+ XXX.world.level.package-info
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.math.SymmetricGroup3 +11M -3M | +4P -2P
```
```
net.minecraft.SharedConstants -8P
```
```
XXX.advancements.critereon.EntityFlagsPredicate +3M -1M | +2P
```
```
XXX.minecraft.commands.CommandSourceStack +5M -5M | +1P -1P
```
```
XXX.arguments.selector.EntitySelectorParser +1M
```
```
XXX.commands.synchronization.ArgumentUtils +2M -1M
```
```
XXX.core.component.DataComponentType +1P
```
```
XXX.core.component.DataComponentType$Builder$SimpleType +2M -1M | +1P
```
```
XXX.gametest.framework.GameTestHelper +4M -2M
```
```
XXX.gametest.framework.GameTestServer +2M -4M
```
```
XXX.server.network.ServerGamePacketListenerImpl +1M | +1P
```
```
XXX.server.network.ServerLoginPacketListenerImpl +1P
```
```
XXX.server.notifications.EmptyNotificationService +1M
```
```
XXX.server.notifications.NotificationService +1P
```
```
XXX.server.players.PlayerList +1M -1M
```
```
XXX.minecraft.world.RandomSequences +13M -15M | +1P -1P
```
```
XXX.world.effect.MobEffects +1P
```
```
XXX.world.entity.EntityType +2P
```
```
XXX.world.entity.NeutralMob +1M | +7P -5P
```
```
XXX.ai.attributes.Attributes +1P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.ai.sensing.SensorType +1M | +1P
```
```
XXX.ai.util.GoalUtils +1M -1M
```
```
XXX.ai.util.LandRandomPos +4M -3M
```
```
XXX.entity.animal.Bee +4M -4M | +2P -2P
```
```
XXX.entity.animal.IronGolem +4M -4M | +2P -2P
```
```
XXX.animal.horse.AbstractHorse +1M
```
```
XXX.animal.horse.ZombieHorse +10M -1M | +5P
```
```
XXX.entity.monster.Zombie +3M -4M
```
```
XXX.entity.monster.ZombifiedPiglin +4M -4M | +2P -2P
```
```
XXX.entity.npc.Villager +3M -3M | +1P -1P
```
```
XXX.entity.npc.VillagerTrades$EmeraldForItems +1M -1M
```
```
XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds +1M -1M
```
```
XXX.entity.npc.VillagerTrades$FailureItemListing +1M -1M
```
```
XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems +2M -2M
```
```
XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald +1M -1M
```
```
XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds +1M -1M
```
```
XXX.entity.player.Player +21M -6M
```
```
XXX.entity.projectile.ProjectileUtil +7M
```
```
XXX.entity.vehicle.MinecartCommandBlock +1M -1M
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.item.Item +1M -1M
```
```
XXX.world.item.ItemStack +7M | +1P
```
```
XXX.world.item.MaceItem +1M -1M
```
```
XXX.world.item.SmithingTemplateItem +2P
```
```
XXX.item.enchantment.EnchantmentEffectComponents +1M | +1P
```
```
XXX.item.enchantment.Enchantments +1P
```
```
XXX.enchantment.effects.PlaySoundEffect +2M -2M | +1P -1P
```
```
XXX.level.biome.AmbientMoodSettings +7M -4M
```
```
XXX.level.storage.DimensionDataStorage +1M -1M | -1P
```
```
XXX.phys.shapes.DiscreteVoxelShape +1M
```
```
XXX.world.scores.Scoreboard +3M
```
```
XXX.world.scores.ScoreboardSaveData$Packed +1P
```

</details>
<details>
<summary>
com.mojang.math.SymmetricGroup3
</summary>

```diff
- boolean lambda$static$0(int,int,int,SymmetricGroup3)
+ boolean lambda$static$0(int[],SymmetricGroup3)
- boolean lambda$static$2(SymmetricGroup3,SymmetricGroup3)
- Direction$Axis permuteAxis(Direction$Axis)
+ int permutation(int)
- int permute(int)
- SymmetricGroup3 inverse()
- SymmetricGroup3 lambda$static$3(SymmetricGroup3)
- SymmetricGroup3[] lambda$static$4(int)
- SymmetricGroup3[] lambda$static$5()
- SymmetricGroup3[][] lambda$static$1()
- Vector3f permuteVector(Vector3f)
- Vector3i permuteVector(Vector3i)
+ void lambda$static$1(SymmetricGroup3[][])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityFlagsPredicate
</summary>

```diff
- Optional isFallFlying()
- Optional isInWater()
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ boolean hasPermission(int)
+ CommandSourceStack withMaximumPermission(int)
- CommandSourceStack withMaximumPermission(PermissionSet)
+ CommandSourceStack withPermission(int)
- CommandSourceStack withPermission(PermissionSet)
- PermissionSet permissions()
+ void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity,boolean,CommandResultCallback,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer)
+ void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity)
- void <init>(CommandSource,Vec3,Vec2,ServerLevel,PermissionSet,String,Component,MinecraftServer,Entity,boolean,CommandResultCallback,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer)
- void <init>(CommandSource,Vec3,Vec2,ServerLevel,PermissionSet,String,Component,MinecraftServer,Entity)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
- boolean allowSelectors(PermissionSetSupplier)
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.ArgumentUtils
</summary>

```diff
- IllegalStateException lambda$serializeNodeToJson$0(String)
+ void lambda$findUsedArgumentTypes$0(Set,Set,CommandNode)
- void lambda$findUsedArgumentTypes$1(Set,Set,CommandNode)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentType$Builder$SimpleType
</summary>

```diff
- boolean ignoreSwapAnimation()
- void <init>(Codec,StreamCodec,boolean)
+ void <init>(Codec,StreamCodec)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- Entity spawn(EntityType,Vec3,EntitySpawnReason)
- Mob spawn(EntityType,int,int,int,EntitySpawnReason)
- void assertFalse(boolean,String)
- void assertTrue(boolean,String)
+ void setDayTime(int)
+ void setNight()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ boolean isCommandBlockEnabled()
+ boolean isSpawnerBlockEnabled()
+ int getFunctionCompilationLevel()
+ int operatorUserPermissionLevel()
- LevelBasedPermissionSet operatorUserPermissions()
- PermissionSet getFunctionCompilationPermissions()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void resetFlyingTicks()
```

</details>
<details>
<summary>
net.minecraft.server.notifications.EmptyNotificationService
</summary>

```diff
- void serverActivityOccured()
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ void sendPlayerPermissionLevel(ServerPlayer,int)
- void sendPlayerPermissionLevel(ServerPlayer,LevelBasedPermissionSet)
```

</details>
<details>
<summary>
net.minecraft.world.RandomSequences
</summary>

```diff
+ App lambda$codec$6(long,RecordCodecBuilder$Instance)
- App lambda$static$1(RecordCodecBuilder$Instance)
- boolean includeSequenceId()
- boolean includeWorldSeed()
+ Boolean lambda$codec$3(RandomSequences)
+ Boolean lambda$codec$4(RandomSequences)
+ Codec codec(long)
+ Codec lambda$static$1(SavedData$Context)
- int salt()
+ Integer lambda$codec$2(RandomSequences)
+ Map lambda$codec$5(RandomSequences)
- Map lambda$static$0(RandomSequences)
+ RandomSequence createSequence(ResourceLocation,int,boolean,boolean)
- RandomSequence createSequence(ResourceLocation,long,int,boolean,boolean)
- RandomSequence createSequence(ResourceLocation,long)
+ RandomSequence createSequence(ResourceLocation)
- RandomSequence lambda$get$2(long,ResourceLocation)
+ RandomSequences lambda$static$0(SavedData$Context)
- RandomSource get(ResourceLocation,long)
+ RandomSource get(ResourceLocation)
- void <init>()
- void <init>(int,boolean,boolean,Map)
+ void <init>(long,int,boolean,boolean,Map)
+ void <init>(long)
+ void reset(ResourceLocation,int,boolean,boolean)
- void reset(ResourceLocation,long,int,boolean,boolean)
- void reset(ResourceLocation,long)
+ void reset(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.entity.NeutralMob
</summary>

```diff
- void setTimeToRemainAngry(long)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.SensorType
</summary>

```diff
- TemptingSensor lambda$static$8()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.GoalUtils
</summary>

```diff
- boolean mobRestricted(PathfinderMob,double)
+ boolean mobRestricted(PathfinderMob,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.LandRandomPos
</summary>

```diff
- BlockPos generateRandomPosTowardDirection(PathfinderMob,double,boolean,BlockPos)
+ BlockPos generateRandomPosTowardDirection(PathfinderMob,int,boolean,BlockPos)
- BlockPos lambda$getPosInDirection$1(PathfinderMob,double,double,int,Vec3,boolean)
+ BlockPos lambda$getPosInDirection$1(PathfinderMob,int,int,Vec3,boolean)
- Vec3 getPosAway(PathfinderMob,double,double,int,Vec3)
- Vec3 getPosInDirection(PathfinderMob,double,double,int,Vec3,boolean)
+ Vec3 getPosInDirection(PathfinderMob,int,int,Vec3,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean isMobControlled()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
+ boolean checkZombieHorseSpawnRules(EntityType,LevelAccessor,EntitySpawnReason,BlockPos,RandomSource)
- boolean isFood(ItemStack)
- boolean isMobControlled()
- boolean lambda$addBehaviourGoals$0(ItemStack)
- boolean removeWhenFarAway(double)
- boolean requiresCustomPersistence()
- double generateZombieHorseJumpStrength(DoubleSupplier)
- double generateZombieHorseSpeed(DoubleSupplier)
- EquipmentSlot sunProtectionSlot()
- SoundEvent getAngrySound()
- SpawnGroupData finalizeSpawn(ServerLevelAccessor,DifficultyInstance,EntitySpawnReason,SpawnGroupData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
+ void aiStep()
+ void convertToZombieType(EntityType)
- void convertToZombieType(ServerLevel,EntityType)
+ void doUnderWaterConversion()
- void doUnderWaterConversion(ServerLevel)
- void lambda$convertToZombieType$1(ServerLevel,Zombie)
+ void lambda$convertToZombieType$1(Zombie)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean shouldRestock()
- boolean shouldRestock(ServerLevel)
+ void increaseMerchantCareer()
- void increaseMerchantCareer(ServerLevel)
+ void updateTrades()
- void updateTrades(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
+ void lambda$getOffer$0(ItemStack,Level,Entity,RandomSource,ResourceKey)
- void lambda$getOffer$0(ItemStack,ServerLevel,Entity,RandomSource,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean canCriticalAttack(Entity)
- boolean cannotAttack(Entity)
- boolean cannotAttackWithItem(ItemStack,int)
- boolean deflectProjectile(Entity)
+ boolean hasPermissions(int)
- boolean isSweepAttack(boolean,boolean,boolean)
- boolean stabAttack(EquipmentSlot,Entity,float,boolean,boolean,boolean)
- DamageSource createAttackSource(ItemStack)
- DamageSource lambda$createAttackSource$1()
- float getItemSwapScale(float)
- float getVoicePitch()
+ int getPermissionLevel()
+ OptionalInt lambda$convertParrotVariant$2(Parrot$Variant)
- OptionalInt lambda$convertParrotVariant$3(Parrot$Variant)
- PermissionSet permissions()
+ Style lambda$decorateDisplayNameComponent$1(String,Style)
- Style lambda$decorateDisplayNameComponent$2(String,Style)
- void attackVisualEffects(Entity,boolean,boolean,boolean,float)
- void causeExtraKnockback(Entity,float,Vec3)
- void damageStatsAndHearts(Entity,float)
- void doSweepAttack(Entity,float,DamageSource,float)
- void itemAttackInteraction(Entity,ItemStack,DamageSource)
- void onAttack()
+ void openMinecartCommandBlock(BaseCommandBlock)
- void openMinecartCommandBlock(MinecartCommandBlock)
- void resetOnlyAttackStrengthTicker()
+ void sweepAttack()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ProjectileUtil
</summary>

```diff
- Collection getHitEntitiesAlong(LivingEntity,float,float,float,Predicate)
- Collection getManyEntityHitResult(Level,Entity,Vec3,Vec3,AABB,Predicate,float)
- Collection getManyEntityHitResult(Level,Entity,Vec3,Vec3,AABB,Predicate)
- Collection lambda$getHitEntitiesAlong$0(BlockHitResult)
- Collection lambda$getHitEntitiesAlong$1(Collection)
- Either getHitEntitiesAlong(Vec3,Entity,Predicate,Vec3,float,ClipContext$Block)
- void lambda$getManyEntityHitResult$2(List,Entity,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartCommandBlock
</summary>

```diff
+ void activateMinecart(int,int,int,boolean)
- void activateMinecart(ServerLevel,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
+ void activateMinecart(int,int,int,boolean)
- void activateMinecart(ServerLevel,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item
</summary>

```diff
+ DamageSource getDamageSource(LivingEntity)
- DamageSource getItemDamageSource(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- boolean matchesIgnoringComponents(ItemStack,ItemStack,Predicate)
- DamageSource getDamageSource(LivingEntity,Supplier)
- DamageSource lambda$getDamageSource$22(LivingEntity,Holder)
- Optional lambda$getDamageSource$21(LivingEntity,EitherHolder)
- Optional lambda$getDamageSource$23(LivingEntity)
- SwingAnimation getSwingAnimation()
- void addUnitComponentToTooltip(DataComponentType,Component,TooltipDisplay,Consumer)
```

</details>
<details>
<summary>
net.minecraft.world.item.MaceItem
</summary>

```diff
+ DamageSource getDamageSource(LivingEntity)
- DamageSource getItemDamageSource(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentEffectComponents
</summary>

```diff
- DataComponentType$Builder lambda$static$31(DataComponentType$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.effects.PlaySoundEffect
</summary>

```diff
+ Holder soundEvent()
- List soundEvents()
+ void <init>(Holder,FloatProvider,FloatProvider)
- void <init>(List,FloatProvider,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
- boolean equals(Object)
+ double getSoundPositionOffset()
- double soundPositionOffset()
+ Holder getSoundEvent()
- Holder soundEvent()
- int blockSearchExtent()
+ int getBlockSearchExtent()
+ int getTickDelay()
- int hashCode()
- int tickDelay()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DimensionDataStorage
</summary>

```diff
- void <init>(Path,DataFixer,HolderLookup$Provider)
+ void <init>(SavedData$Context,Path,DataFixer,HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.DiscreteVoxelShape
</summary>

```diff
- int fixupCoordinate(Vector3i,int)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Scoreboard
</summary>

```diff
- List packObjectives()
- List packPlayerTeams()
- Map packDisplaySlots()
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
- net.minecraft.package-info
- net.minecraft.ReportedException
+ net.minecraft.ReportType
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.SuppressForbidden
- net.minecraft.SystemReport
+ net.minecraft.TracingExecutor
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$10
+ net.minecraft.Util$11
- net.minecraft.Util$2
+ net.minecraft.Util$3
- net.minecraft.Util$4
+ net.minecraft.Util$5
- net.minecraft.Util$6
+ net.minecraft.Util$7
- net.minecraft.Util$8
+ net.minecraft.Util$9
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.WorldVersion
- net.minecraft.WorldVersion$1
+ net.minecraft.WorldVersion$Simple
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
+ XXX.advancements.critereon.MinMaxBounds$Bounds
- XXX.advancements.critereon.MinMaxBounds$Bounds$1
+ XXX.advancements.critereon.MinMaxBounds$Doubles
- XXX.advancements.critereon.MinMaxBounds$FloatDegrees
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$Builder
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.MovementPredicate
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
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
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
+ XXX.ai.behavior.package-info
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
- XXX.ai.behavior.StartAttacking$StartAttackingCondition
+ XXX.ai.behavior.StartAttacking$TargetFinder
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopAttackingIfTargetInvalid$StopAttackCondition
- XXX.ai.behavior.StopAttackingIfTargetInvalid$TargetErasedCallback
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TransportItemsBetweenContainers
- XXX.ai.behavior.TransportItemsBetweenContainers$ContainerInteractionState
+ XXX.ai.behavior.TransportItemsBetweenContainers$OnTargetReachedInteraction
- XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemState
+ XXX.ai.behavior.TransportItemsBetweenContainers$TransportItemTarget
- XXX.ai.behavior.TriggerGate
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VillageBoundRandomStroll
+ XXX.ai.behavior.VillagerCalmDown
- XXX.ai.behavior.VillagerGoalPackages
+ XXX.ai.behavior.VillagerMakeLove
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
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
- XXX.animal.nautilus.Nautilus
- XXX.animal.nautilus.package-info
- XXX.animal.nautilus.ZombieNautilus
- XXX.animation.definitions.package-info
- XXX.animation.definitions.SnifferAnimation
+ XXX.animation.definitions.WardenAnimation
+ XXX.behavior.declarative.BehaviorBuilder
- XXX.behavior.declarative.BehaviorBuilder$1
+ XXX.behavior.declarative.BehaviorBuilder$Constant
- XXX.behavior.declarative.BehaviorBuilder$Constant$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance
- XXX.behavior.declarative.BehaviorBuilder$Instance$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance$2
- XXX.behavior.declarative.BehaviorBuilder$Instance$3
+ XXX.behavior.declarative.BehaviorBuilder$Instance$4
- XXX.behavior.declarative.BehaviorBuilder$Instance$5
+ XXX.behavior.declarative.BehaviorBuilder$Instance$Mu
- XXX.behavior.declarative.BehaviorBuilder$Mu
+ XXX.behavior.declarative.BehaviorBuilder$PureMemory
- XXX.behavior.declarative.BehaviorBuilder$PureMemory$1
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWithResult
- XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- XXX.behavior.declarative.MemoryAccessor
+ XXX.behavior.declarative.MemoryCondition
- XXX.behavior.declarative.MemoryCondition$Absent
+ XXX.behavior.declarative.MemoryCondition$Present
- XXX.behavior.declarative.MemoryCondition$Registered
- XXX.behavior.declarative.package-info
+ XXX.behavior.declarative.Trigger
- XXX.behavior.warden.Digging
+ XXX.behavior.warden.Emerging
- XXX.behavior.warden.ForceUnmount
+ XXX.behavior.warden.package-info
+ XXX.behavior.warden.Roar
- XXX.behavior.warden.SetRoarTarget
+ XXX.behavior.warden.SetWardenLookTarget
- XXX.behavior.warden.Sniffing
+ XXX.behavior.warden.SonicBoom
- XXX.behavior.warden.TryToSniff
- XXX.blaze3d.buffers.GpuBufferSlice
+ XXX.blaze3d.buffers.GpuFence
- XXX.blaze3d.buffers.package-info
- XXX.blaze3d.buffers.Std140Builder
+ XXX.blaze3d.buffers.Std140SizeCalculator
+ XXX.blaze3d.font.GlyphBitmap
- XXX.blaze3d.font.GlyphInfo
+ XXX.blaze3d.font.GlyphProvider
- XXX.blaze3d.font.GlyphProvider$Conditional
+ XXX.blaze3d.font.package-info
+ XXX.blaze3d.font.SpaceProvider
- XXX.blaze3d.font.SpaceProvider$Definition
+ XXX.blaze3d.font.TrueTypeGlyphProvider
- XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph
+ XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph$1
- XXX.blaze3d.font.TrueTypeGlyphProvider$GlyphEntry
+ XXX.blaze3d.font.UnbakedGlyph
- XXX.blaze3d.font.UnbakedGlyph$Stitcher
- XXX.blaze3d.framegraph.FrameGraphBuilder
+ XXX.blaze3d.framegraph.FrameGraphBuilder$ExternalResource
- XXX.blaze3d.framegraph.FrameGraphBuilder$Handle
+ XXX.blaze3d.framegraph.FrameGraphBuilder$Inspector
- XXX.blaze3d.framegraph.FrameGraphBuilder$Inspector$1
+ XXX.blaze3d.framegraph.FrameGraphBuilder$InternalVirtualResource
- XXX.blaze3d.framegraph.FrameGraphBuilder$Pass
+ XXX.blaze3d.framegraph.FrameGraphBuilder$VirtualResource
- XXX.blaze3d.framegraph.FramePass
+ XXX.blaze3d.framegraph.package-info
- XXX.blaze3d.opengl.BufferStorage
+ XXX.blaze3d.opengl.BufferStorage$Immutable
- XXX.blaze3d.opengl.BufferStorage$Mutable
+ XXX.blaze3d.opengl.DirectStateAccess
- XXX.blaze3d.opengl.DirectStateAccess$Core
+ XXX.blaze3d.opengl.DirectStateAccess$Emulated
- XXX.blaze3d.opengl.GlBuffer
+ XXX.blaze3d.opengl.GlBuffer$GlMappedView
- XXX.blaze3d.opengl.GlCommandEncoder
+ XXX.blaze3d.opengl.GlCommandEncoder$1
- XXX.blaze3d.opengl.GlConst
+ XXX.blaze3d.opengl.GlConst$1
- XXX.blaze3d.opengl.GlDebug
+ XXX.blaze3d.opengl.GlDebug$LogEntry
- XXX.blaze3d.opengl.GlDebugLabel
+ XXX.blaze3d.opengl.GlDebugLabel$Core
- XXX.blaze3d.opengl.GlDebugLabel$Empty
+ XXX.blaze3d.opengl.GlDebugLabel$Ext
- XXX.blaze3d.opengl.GlDevice
+ XXX.blaze3d.opengl.GlDevice$ShaderCompilationKey
- XXX.blaze3d.opengl.GlFence
+ XXX.blaze3d.opengl.GlProgram
- XXX.blaze3d.opengl.GlProgram$1
+ XXX.blaze3d.opengl.GlRenderPass
- XXX.blaze3d.opengl.GlRenderPass$TextureViewAndSampler
- XXX.blaze3d.opengl.GlSampler
+ XXX.blaze3d.opengl.GlTexture$1
- XXX.blaze3d.opengl.GlTextureView
- XXX.blaze3d.opengl.package-info
+ XXX.blaze3d.opengl.Uniform
- XXX.blaze3d.opengl.Uniform$Sampler
+ XXX.blaze3d.opengl.Uniform$Ubo
- XXX.blaze3d.opengl.Uniform$Utb
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
- XXX.blaze3d.platform.InputConstants$Value
- XXX.blaze3d.systems.RenderSystem$TextureAndSampler
- XXX.blaze3d.textures.GpuTexture
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
+ XXX.block.entity.BlockEntity$BlockEntityPathElement
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
- XXX.block.entity.CopperGolemStatueBlockEntity
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
+ XXX.block.entity.ListBackedContainer
+ XXX.block.entity.package-info
- XXX.block.entity.PotDecorations
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShelfBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
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
- XXX.block.entity.TestInstanceBlockEntity$ErrorMarker
+ XXX.block.entity.TestInstanceBlockEntity$Status
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
- XXX.block.entity.TrialSpawnerBlockEntity
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
- XXX.block.model.BlockElementRotation$1
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
+ XXX.block.sounds.package-info
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
- XXX.blockentity.state.BannerRenderState
+ XXX.blockentity.state.BeaconRenderState
- XXX.blockentity.state.BeaconRenderState$Section
+ XXX.blockentity.state.BedRenderState
- XXX.blockentity.state.BellRenderState
+ XXX.blockentity.state.BlockEntityRenderState
- XXX.blockentity.state.BlockEntityWithBoundingBoxRenderState
+ XXX.blockentity.state.BlockEntityWithBoundingBoxRenderState$InvisibleBlockType
- XXX.blockentity.state.BrushableBlockRenderState
+ XXX.blockentity.state.CampfireRenderState
- XXX.blockentity.state.ChestRenderState
+ XXX.blockentity.state.ChestRenderState$ChestMaterialType
- XXX.blockentity.state.CondiutRenderState
+ XXX.blockentity.state.CopperGolemStatueRenderState
- XXX.blockentity.state.DecoratedPotRenderState
+ XXX.blockentity.state.EnchantTableRenderState
- XXX.blockentity.state.EndGatewayRenderState
+ XXX.blockentity.state.EndPortalRenderState
- XXX.blockentity.state.LecternRenderState
+ XXX.blockentity.state.package-info
+ XXX.blockentity.state.PistonHeadRenderState
- XXX.blockentity.state.ShelfRenderState
+ XXX.blockentity.state.ShulkerBoxRenderState
- XXX.blockentity.state.SignRenderState
+ XXX.blockentity.state.SkullBlockRenderState
- XXX.blockentity.state.SpawnerRenderState
+ XXX.blockentity.state.TestInstanceRenderState
- XXX.blockentity.state.VaultRenderState
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.ObjectContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
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
+ XXX.client.animation.package-info
- XXX.client.color.ColorLerper
+ XXX.client.color.ColorLerper$Type
+ XXX.client.color.package-info
- XXX.client.data.AtlasProvider
+ XXX.client.data.Main
- XXX.client.data.package-info
+ XXX.client.entity.ClientAvatarEntity
- XXX.client.entity.ClientAvatarState
+ XXX.client.entity.ClientMannequin
- XXX.client.entity.package-info
+ XXX.client.gui.BundleMouseActions
- XXX.client.gui.ComponentPath
+ XXX.client.gui.ComponentPath$Leaf
- XXX.client.gui.ComponentPath$Path
+ XXX.client.gui.Font
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$GlyphVisitor
- XXX.client.gui.Font$GlyphVisitor$1
+ XXX.client.gui.Font$PreparedText
- XXX.client.gui.Font$PreparedTextBuilder
+ XXX.client.gui.Font$Provider
- XXX.client.gui.GlyphSource
+ XXX.client.gui.Gui
- XXX.client.gui.Gui$1DisplayEntry
+ XXX.client.gui.Gui$ContextualInfo
- XXX.client.gui.Gui$HeartType
+ XXX.client.gui.Gui$RenderFunction
- XXX.client.gui.GuiGraphics
+ XXX.client.gui.GuiGraphics$OutlineBox
- XXX.client.input.InputWithModifiers$Modifiers
+ XXX.client.input.KeyEvent
- XXX.client.input.KeyEvent$Action
- XXX.client.input.MouseButtonInfo$MouseButton
- XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.NautilusModel
- XXX.client.model.OcelotModel
+ XXX.client.model.package-info
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
+ XXX.client.model.SkullModelBase$State
- XXX.client.model.SlimeModel
+ XXX.client.model.SnifferModel
- XXX.client.model.SnowGolemModel
- XXX.client.model.SpearAnimations$UseParams
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
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$CommonDialogAccess
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
- XXX.client.multiplayer.ClientConfigurationPacketListenerImpl$1
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl$2
- XXX.client.multiplayer.ClientDebugSubscriber
+ XXX.client.multiplayer.ClientDebugSubscriber$1
- XXX.client.multiplayer.ClientDebugSubscriber$ValueMap
- XXX.client.multiplayer.ClientDebugSubscriber$ValueMaps
+ XXX.client.multiplayer.ClientDebugSubscriber$ValueMapType
+ XXX.client.multiplayer.ClientDebugSubscriber$ValueWrapper
- XXX.client.multiplayer.ClientExplosionTracker
+ XXX.client.multiplayer.ClientExplosionTracker$ExplosionInfo
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientPacketListener$2
+ XXX.client.multiplayer.ClientPacketListener$3
- XXX.client.multiplayer.ClientPacketListener$CommandCheckResult
+ XXX.client.multiplayer.ClientRecipeContainer
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.CommonListenerCookie
- XXX.client.multiplayer.KnownPacksManager
+ XXX.client.multiplayer.LegacyServerPinger
- XXX.client.multiplayer.LegacyServerPinger$Output
+ XXX.client.multiplayer.LevelLoadTracker
- XXX.client.multiplayer.LevelLoadTracker$ClientLevelReady
+ XXX.client.multiplayer.LevelLoadTracker$ClientState
- XXX.client.multiplayer.LevelLoadTracker$WaitingForPlayerChunk
+ XXX.client.multiplayer.LevelLoadTracker$WaitingForServer
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
- XXX.client.particle.DripParticle$DripstoneLavaFallProvider
+ XXX.client.particle.DripParticle$DripstoneLavaHangProvider
- XXX.client.particle.DripParticle$DripstoneWaterFallProvider
+ XXX.client.particle.DripParticle$DripstoneWaterHangProvider
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DripParticle$HoneyFallProvider
- XXX.client.particle.DripParticle$HoneyHangProvider
+ XXX.client.particle.DripParticle$HoneyLandProvider
- XXX.client.particle.DripParticle$LavaFallProvider
+ XXX.client.particle.DripParticle$LavaHangProvider
- XXX.client.particle.DripParticle$LavaLandProvider
+ XXX.client.particle.DripParticle$NectarFallProvider
- XXX.client.particle.DripParticle$ObsidianTearFallProvider
+ XXX.client.particle.DripParticle$ObsidianTearHangProvider
- XXX.client.particle.DripParticle$ObsidianTearLandProvider
+ XXX.client.particle.DripParticle$SporeBlossomFallProvider
- XXX.client.particle.DripParticle$WaterFallProvider
+ XXX.client.particle.DripParticle$WaterHangProvider
- XXX.client.particle.DustColorTransitionParticle
+ XXX.client.particle.DustColorTransitionParticle$Provider
- XXX.client.particle.DustParticle
+ XXX.client.particle.DustParticle$Provider
- XXX.client.particle.DustParticleBase
+ XXX.client.particle.DustPlumeParticle
- XXX.client.particle.DustPlumeParticle$Provider
+ XXX.client.particle.ElderGuardianParticle
- XXX.client.particle.ElderGuardianParticle$Provider
+ XXX.client.particle.ElderGuardianParticleGroup
- XXX.client.particle.ElderGuardianParticleGroup$ElderGuardianParticleRenderState
+ XXX.client.particle.ElderGuardianParticleGroup$State
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
+ XXX.client.particle.ItemPickupParticleGroup
- XXX.client.particle.ItemPickupParticleGroup$ParticleInstance
+ XXX.client.particle.ItemPickupParticleGroup$State
- XXX.client.particle.LargeSmokeParticle
+ XXX.client.particle.LargeSmokeParticle$Provider
- XXX.client.particle.LavaParticle
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.NoRenderParticle
+ XXX.client.particle.NoRenderParticleGroup
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.Particle$LifetimeAlpha
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleGroup
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleProvider$Sprite
+ XXX.client.particle.ParticleRenderType
- XXX.client.particle.ParticleResources
+ XXX.client.particle.ParticleResources$1ParticleDefinition
- XXX.client.particle.ParticleResources$MutableSpriteSet
+ XXX.client.particle.ParticleResources$SpriteParticleRegistration
- XXX.client.particle.PlayerCloudParticle
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.QuadParticleGroup
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
- XXX.client.particle.SingleQuadParticle$Layer
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
+ XXX.client.player.LocalPlayerResolver
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
- XXX.client.renderer.CachedOrthoProjectionMatrixBuffer
+ XXX.client.renderer.CachedPerspectiveProjectionMatrixBuffer
- XXX.client.renderer.CloudRenderer
+ XXX.client.renderer.CloudRenderer$RelativeCameraPos
- XXX.client.renderer.CloudRenderer$TextureData
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.DynamicUniforms
- XXX.client.renderer.DynamicUniforms$Transform
+ XXX.client.renderer.DynamicUniformStorage
- XXX.client.renderer.DynamicUniformStorage$DynamicUniform
+ XXX.client.renderer.EndFlashState
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.GlobalSettingsUniform
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemBlockRenderTypes$2
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
- XXX.client.renderer.LevelEventHandler
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$1
+ XXX.client.renderer.LevelRenderer$BrightnessGetter
- XXX.client.renderer.LevelTargetBundle
+ XXX.client.renderer.LightTexture
+ XXX.client.renderer.MappableRingBuffer
- XXX.client.renderer.MapRenderer
- XXX.client.renderer.MaterialMapper
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.Octree
- XXX.client.renderer.Octree$AxisSorting
+ XXX.client.renderer.Octree$Branch
- XXX.client.renderer.Octree$Leaf
+ XXX.client.renderer.Octree$Node
- XXX.client.renderer.Octree$OctreeVisitor
+ XXX.client.renderer.OrderedSubmitNodeCollector
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PerspectiveProjectionMatrixBuffer
- XXX.client.renderer.PlayerSkinRenderCache
+ XXX.client.renderer.PlayerSkinRenderCache$1
- XXX.client.renderer.PlayerSkinRenderCache$2
+ XXX.client.renderer.PlayerSkinRenderCache$RenderInfo
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostChain$TargetBundle
- XXX.client.renderer.PostChain$TargetBundle$1
+ XXX.client.renderer.PostChainConfig
- XXX.client.renderer.PostChainConfig$Input
+ XXX.client.renderer.PostChainConfig$InternalTarget
- XXX.client.renderer.PostChainConfig$Pass
+ XXX.client.renderer.PostChainConfig$TargetInput
- XXX.client.renderer.PostChainConfig$TextureInput
+ XXX.client.renderer.PostPass
- XXX.client.renderer.PostPass$Input
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SkyRenderer
- XXX.client.renderer.SpecialBlockModelRenderer
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.SubmitNodeCollection
+ XXX.client.renderer.SubmitNodeCollector
- XXX.client.renderer.SubmitNodeCollector$CustomGeometryRenderer
+ XXX.client.renderer.SubmitNodeCollector$ParticleGroupRenderer
- XXX.client.renderer.SubmitNodeStorage
+ XXX.client.renderer.SubmitNodeStorage$BlockModelSubmit
- XXX.client.renderer.SubmitNodeStorage$BlockSubmit
+ XXX.client.renderer.SubmitNodeStorage$CustomGeometrySubmit
- XXX.client.renderer.SubmitNodeStorage$FlameSubmit
+ XXX.client.renderer.SubmitNodeStorage$HitboxSubmit
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
- XXX.color.item.GrassColorSource
+ XXX.color.item.ItemTintSource
- XXX.color.item.ItemTintSources
+ XXX.color.item.MapColor
- XXX.color.item.package-info
- XXX.color.item.Potion
+ XXX.color.item.TeamColor
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
- XXX.common.custom.BrandPayload
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.package-info
- XXX.component.predicates.AnyValue
+ XXX.component.predicates.AttributeModifiersPredicate
- XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
+ XXX.component.predicates.BundlePredicate
- XXX.component.predicates.ContainerPredicate
+ XXX.component.predicates.CustomDataPredicate
- XXX.component.predicates.DamagePredicate
+ XXX.component.predicates.DataComponentPredicate
- XXX.component.predicates.DataComponentPredicate$AnyValueType
- XXX.component.predicates.DataComponentPredicate$Single
+ XXX.component.predicates.DataComponentPredicate$Type
- XXX.component.predicates.DataComponentPredicate$TypeBase
- XXX.contents.data.BlockDataSource
+ XXX.contents.data.DataSource
- XXX.contents.data.DataSources
+ XXX.contents.data.EntityDataSource
+ XXX.contents.data.package-info
- XXX.contents.data.StorageDataSource
- XXX.contents.objects.AtlasSprite
+ XXX.contents.objects.ObjectInfo
- XXX.contents.objects.ObjectInfos
- XXX.contents.objects.package-info
+ XXX.contents.objects.PlayerSprite
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ XXX.data.models.BlockModelGenerators$PlantType
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.EquipmentAssetProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ItemModelGenerators$TrimMaterialData
- XXX.data.models.ItemModelOutput
+ XXX.data.models.ModelProvider
- XXX.data.models.ModelProvider$BlockStateGeneratorCollector
+ XXX.data.models.ModelProvider$ItemInfoCollector
- XXX.data.models.ModelProvider$SimpleModelCollector
+ XXX.data.models.MultiVariant
+ XXX.data.models.package-info
- XXX.data.models.WaypointStyleProvider
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractBlockPropertyFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFieldFix
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
- XXX.datafix.fixes.CopperGolemWeatherStateFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.CustomModelDataExpandFix
+ XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.DebugProfileOverlayReferenceFix
- XXX.datafix.fixes.OptionsFancyGraphicsToGraphicsModeFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsGraphicsModeSplitFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.ParticleUnflatteningFix
- XXX.datafix.fixes.PlayerEquipmentFix
+ XXX.datafix.fixes.PlayerHeadBlockProfileFix
- XXX.datafix.fixes.PlayerRespawnDataFix
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
- XXX.datafix.fixes.RemoveBlockEntityTagFix
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
- XXX.datafix.fixes.SignTextStrictJsonFix
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
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V4648
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
+ XXX.dialog.action.Action
- XXX.dialog.action.Action$ValueGetter
+ XXX.dialog.action.Action$ValueGetter$1
- XXX.dialog.action.Action$ValueGetter$2
+ XXX.dialog.action.ActionTypes
- XXX.dialog.action.CommandTemplate
+ XXX.dialog.action.CustomAll
- XXX.dialog.action.package-info
- XXX.dialog.action.ParsedTemplate
+ XXX.dialog.action.StaticAction
+ XXX.dialog.body.DialogBody
- XXX.dialog.body.DialogBodyTypes
+ XXX.dialog.body.ItemBody
+ XXX.dialog.body.package-info
- XXX.dialog.body.PlainMessage
- XXX.dialog.input.BooleanInput
+ XXX.dialog.input.InputControl
- XXX.dialog.input.InputControlTypes
+ XXX.dialog.input.NumberRangeInput
- XXX.dialog.input.NumberRangeInput$RangeInfo
+ XXX.dialog.input.package-info
+ XXX.dialog.input.SingleOptionInput
- XXX.dialog.input.SingleOptionInput$Entry
+ XXX.dialog.input.TextInput
- XXX.dialog.input.TextInput$MultilineOptions
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
- XXX.enchantment.effects.AddValue
+ XXX.enchantment.effects.AllOf
- XXX.enchantment.effects.AllOf$EntityEffects
+ XXX.enchantment.effects.AllOf$LocationBasedEffects
- XXX.enchantment.effects.AllOf$ValueEffects
+ XXX.enchantment.effects.package-info
- XXX.enchantment.effects.ScaleExponentially
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
+ XXX.entity.state.HitboxesRenderState
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
- XXX.entity.state.NautilusRenderState
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
- XXX.entity.state.UndeadRenderState
- XXX.entity.trialspawner.package-info
- XXX.entity.trialspawner.PlayerDetector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
- XXX.entity.trialspawner.TrialSpawner
+ XXX.entity.trialspawner.TrialSpawner$FlameParticle
- XXX.entity.trialspawner.TrialSpawner$FullConfig
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerConfig$Builder
- XXX.entity.trialspawner.TrialSpawnerConfigs
+ XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
- XXX.entity.trialspawner.TrialSpawnerStateData
+ XXX.entity.trialspawner.TrialSpawnerStateData$Packed
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
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.MaterialAssetGroup
- XXX.equipment.trim.MaterialAssetGroup$AssetInfo
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
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
+ XXX.fog.environment.AirBasedFogEnvironment
- XXX.fog.environment.AtmosphericFogEnvironment
+ XXX.fog.environment.BlindnessFogEnvironment
- XXX.fog.environment.DarknessFogEnvironment
+ XXX.fog.environment.DimensionOrBossFogEnvironment
- XXX.fog.environment.FogEnvironment
+ XXX.fog.environment.LavaFogEnvironment
- XXX.fog.environment.MobEffectFogEnvironment
+ XXX.fog.environment.package-info
+ XXX.fog.environment.PowderedSnowFogEnvironment
- XXX.fog.environment.WaterFogEnvironment
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
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
- XXX.gui.components.FocusableTextWidget$Builder
+ XXX.gui.components.ImageButton
- XXX.gui.components.ImageWidget
+ XXX.gui.components.ImageWidget$Sprite
- XXX.gui.components.ImageWidget$Texture
+ XXX.gui.components.ItemDisplayWidget
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LoadingDotsWidget
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.LogoRenderer
+ XXX.gui.components.MultiLineEditBox
- XXX.gui.components.MultiLineEditBox$Builder
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$Align
+ XXX.gui.components.MultiLineLabel$Align$1
- XXX.gui.components.MultiLineLabel$Align$2
+ XXX.gui.components.MultiLineLabel$Align$3
- XXX.gui.components.MultiLineLabel$TextAndWidth
+ XXX.gui.components.MultilineTextField
- XXX.gui.components.MultilineTextField$1
+ XXX.gui.components.MultilineTextField$StringView
+ XXX.gui.components.MultiLineTextWidget
- XXX.gui.components.MultiLineTextWidget$CacheKey
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$OptionEntry
+ XXX.gui.components.PlainTextButton
- XXX.gui.components.PlayerFaceRenderer
+ XXX.gui.components.PlayerSkinWidget
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$HealthState
- XXX.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ XXX.gui.components.PopupScreen
- XXX.gui.components.PopupScreen$Builder
+ XXX.gui.components.PopupScreen$ButtonOption
- XXX.gui.components.Renderable
- XXX.gui.screens.AddRealmPopupScreen
- XXX.gui.screens.package-info
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsGenericErrorScreen$ErrorMessage
+ XXX.gui.screens.RealmsLongRunningMcoConnectTaskScreen
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen
+ XXX.gui.screens.RealmsNotificationsScreen
- XXX.gui.screens.RealmsNotificationsScreen$1
+ XXX.gui.screens.RealmsNotificationsScreen$2
- XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
+ XXX.gui.screens.RealmsParentalConsentScreen
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPopups
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsUploadScreen
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
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
+ XXX.item.component.ItemAttributeModifiers$Display$Default
- XXX.item.component.ItemAttributeModifiers$Display$Hidden
+ XXX.item.component.ItemAttributeModifiers$Display$OverrideText
- XXX.item.component.ItemAttributeModifiers$Display$Type
+ XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents
+ XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.ItemLore
- XXX.item.component.KineticWeapon$Condition
+ XXX.item.component.LodestoneTracker
- XXX.item.component.MapDecorations
+ XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapItemColor
+ XXX.item.component.MapPostProcessing
- XXX.item.component.OminousBottleAmplifier
- XXX.item.component.SwingAnimation
+ XXX.item.component.Tool
- XXX.item.component.Tool$Rule
+ XXX.item.component.TooltipDisplay
- XXX.item.component.TooltipProvider
+ XXX.item.component.TypedEntityData
- XXX.item.component.TypedEntityData$1
+ XXX.item.component.UseCooldown
- XXX.item.component.UseEffects
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
- XXX.jfr.event.ClientFpsEvent
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
+ XXX.jfr.event.StructureGenerationEvent
- XXX.jfr.event.StructureGenerationEvent$Fields
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
- XXX.jfr.stats.FpsStat
+ XXX.jsonrpc.api.MethodInfo
- XXX.jsonrpc.api.MethodInfo$Named
+ XXX.jsonrpc.api.package-info
+ XXX.jsonrpc.api.ParamInfo
- XXX.jsonrpc.api.PlayerDto
+ XXX.jsonrpc.api.ReferenceUtil
- XXX.jsonrpc.api.ResultInfo
+ XXX.jsonrpc.api.Schema
- XXX.jsonrpc.api.SchemaComponent
- XXX.jsonrpc.dataprovider.JsonRpcApiSchema
+ XXX.jsonrpc.dataprovider.package-info
- XXX.jsonrpc.internalapi.GameRules
+ XXX.jsonrpc.internalapi.MinecraftAllowListService
- XXX.jsonrpc.internalapi.MinecraftAllowListServiceImpl
+ XXX.jsonrpc.internalapi.MinecraftApi
- XXX.jsonrpc.internalapi.MinecraftBanListService
+ XXX.jsonrpc.internalapi.MinecraftBanListServiceImpl
- XXX.jsonrpc.internalapi.MinecraftExecutorService
+ XXX.jsonrpc.internalapi.MinecraftExecutorServiceImpl
- XXX.jsonrpc.internalapi.MinecraftGameRuleService
+ XXX.jsonrpc.internalapi.MinecraftGameRuleServiceImpl
- XXX.jsonrpc.internalapi.MinecraftOperatorListService
+ XXX.jsonrpc.internalapi.MinecraftOperatorListServiceImpl
- XXX.jsonrpc.internalapi.MinecraftPlayerListService
+ XXX.jsonrpc.internalapi.MinecraftPlayerListServiceImpl
- XXX.jsonrpc.internalapi.MinecraftServerSettingsService
+ XXX.jsonrpc.internalapi.MinecraftServerSettingsServiceImpl
- XXX.jsonrpc.internalapi.MinecraftServerStateService
+ XXX.jsonrpc.internalapi.MinecraftServerStateServiceImpl
- XXX.jsonrpc.internalapi.package-info
+ XXX.jsonrpc.methods.AllowlistService
- XXX.jsonrpc.methods.BanlistService
+ XXX.jsonrpc.methods.BanlistService$UserBan
- XXX.jsonrpc.methods.BanlistService$UserBanDto
+ XXX.jsonrpc.methods.ClientInfo
- XXX.jsonrpc.methods.DiscoveryService
+ XXX.jsonrpc.methods.DiscoveryService$DiscoverComponents
- XXX.jsonrpc.methods.DiscoveryService$DiscoverInfo
+ XXX.jsonrpc.methods.DiscoveryService$DiscoverResponse
- XXX.jsonrpc.methods.EncodeJsonRpcException
+ XXX.jsonrpc.methods.GameRulesService
- XXX.jsonrpc.methods.GameRulesService$RuleType
+ XXX.jsonrpc.methods.GameRulesService$TypedRule
- XXX.jsonrpc.methods.GameRulesService$UntypedRule
+ XXX.jsonrpc.methods.IllegalMethodDefinitionException
- XXX.jsonrpc.methods.InvalidParameterJsonRpcException
+ XXX.jsonrpc.methods.InvalidRequestJsonRpcException
- XXX.jsonrpc.methods.IpBanlistService
+ XXX.jsonrpc.methods.IpBanlistService$IncomingIpBanDto
- XXX.jsonrpc.methods.IpBanlistService$IpBan
+ XXX.jsonrpc.methods.IpBanlistService$IpBanDto
- XXX.jsonrpc.methods.Message
+ XXX.jsonrpc.methods.MethodNotFoundJsonRpcException
- XXX.jsonrpc.methods.OperatorService
+ XXX.jsonrpc.methods.OperatorService$Op
- XXX.jsonrpc.methods.OperatorService$OperatorDto
- XXX.jsonrpc.methods.package-info
+ XXX.jsonrpc.methods.PlayerService
- XXX.jsonrpc.methods.PlayerService$KickDto
+ XXX.jsonrpc.methods.RemoteRpcErrorException
- XXX.jsonrpc.methods.ServerSettingsService
+ XXX.jsonrpc.methods.ServerStateService
- XXX.jsonrpc.methods.ServerStateService$ServerState
+ XXX.jsonrpc.methods.ServerStateService$SystemMessage
- XXX.jsonrpc.security.AuthenticationHandler
+ XXX.jsonrpc.security.AuthenticationHandler$SecurityCheckResult
- XXX.jsonrpc.security.JsonRpcSslContextProvider
- XXX.jsonrpc.security.package-info
+ XXX.jsonrpc.security.SecurityConfig
+ XXX.jsonrpc.websocket.JsonToWebSocketEncoder
+ XXX.jsonrpc.websocket.package-info
- XXX.jsonrpc.websocket.WebSocketToJsonCodec
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
- XXX.level.block.CopperChestBlock
+ XXX.level.block.CopperGolemStatueBlock
- XXX.level.block.CopperGolemStatueBlock$Pose
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
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.DryVegetationBlock
- XXX.level.block.EnchantingTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.EyeblossomBlock
- XXX.level.block.EyeblossomBlock$Type
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FireflyBushBlock
+ XXX.level.block.FlowerBedBlock
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
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingMossBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HeavyCoreBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
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
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeafLitterBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.Mirror
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
+ XXX.level.block.package-info
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
+ XXX.level.block.SelectableSlotContainer
- XXX.level.block.SelectableSlotContainer$1
+ XXX.level.block.ShelfBlock
- XXX.level.block.ShortDryGrassBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SideChainPartBlock
- XXX.level.block.SideChainPartBlock$EmptyNeighbor
+ XXX.level.block.SideChainPartBlock$Neighbor
- XXX.level.block.SideChainPartBlock$Neighbors
+ XXX.level.block.SideChainPartBlock$SideChainNeighbor
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnifferEggBlock
- XXX.level.block.SnowLayerBlock
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
- XXX.level.block.TallDryGrassBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
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
+ XXX.level.block.WeatheringCopperBarsBlock
- XXX.level.block.WeatheringCopperBlocks
+ XXX.level.block.WeatheringCopperBulbBlock
- XXX.level.block.WeatheringCopperChainBlock
+ XXX.level.block.WeatheringCopperChestBlock
- XXX.level.block.WeatheringCopperDoorBlock
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperGolemStatueBlock
+ XXX.level.block.WeatheringCopperGrateBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WeatheringCopperTrapDoorBlock
+ XXX.level.block.WeatheringLanternBlock
- XXX.level.block.WeatheringLightningRodBlock
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
+ XXX.level.chunk.ChunkAccess$ChunkPathElement
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.Configuration
- XXX.level.chunk.Configuration$Global
+ XXX.level.chunk.Configuration$Simple
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
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainerFactory
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.Strategy
+ XXX.level.chunk.Strategy$1
- XXX.level.chunk.Strategy$2
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
+ XXX.level.levelgen.DensityFunctions$FindTopSurface
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
+ XXX.level.saveddata.SavedData
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
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
+ XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackFormat
- XXX.metadata.pack.PackFormat$1
+ XXX.metadata.pack.PackFormat$IntermediaryFormat
- XXX.metadata.pack.PackFormat$IntermediaryFormatHolder
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSection$1
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
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.KeyMapping$Category
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
- XXX.minecraft.client.OptionInstance$SliderableEnum
- XXX.minecraft.client.package-info
+ XXX.minecraft.commands.PermissionSource
- XXX.minecraft.gizmos.CircleGizmo
- XXX.minecraft.gizmos.Gizmo
- XXX.minecraft.gizmos.GizmoPrimitives
- XXX.minecraft.gizmos.Gizmos$TemporaryCollection
- XXX.minecraft.gizmos.GizmoStyle
- XXX.minecraft.gizmos.PointGizmo
- XXX.minecraft.gizmos.RectGizmo$1
- XXX.minecraft.gizmos.SimpleGizmoCollector$GizmoInstance
- XXX.minecraft.gizmos.TextGizmo$Style
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
- XXX.minecraft.nbt.CollectionTag$1
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
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$GenericListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.PrimitiveTag
+ XXX.minecraft.nbt.ReportedNbtException
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtGrammar
- XXX.minecraft.nbt.SnbtGrammar$1
+ XXX.minecraft.nbt.SnbtGrammar$2
- XXX.minecraft.nbt.SnbtGrammar$3
+ XXX.minecraft.nbt.SnbtGrammar$4
- XXX.minecraft.nbt.SnbtGrammar$5
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
+ XXX.minecraft.nbt.SnbtGrammar$Base
- XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
+ XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
- XXX.minecraft.nbt.SnbtGrammar$Sign
+ XXX.minecraft.nbt.SnbtGrammar$Signed
- XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
+ XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
- XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
+ XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$1
+ XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$3
+ XXX.minecraft.nbt.SnbtOperations$BuiltinKey
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
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
- XXX.minecraft.network.HashedPatchMap
+ XXX.minecraft.network.HashedPatchMap$HashGenerator
- XXX.minecraft.network.HashedStack
+ XXX.minecraft.network.HashedStack$1
- XXX.minecraft.network.HashedStack$ActualItem
+ XXX.minecraft.network.HiddenByteBuf
- XXX.minecraft.network.LocalFrameDecoder
+ XXX.minecraft.network.LocalFrameEncoder
- XXX.minecraft.network.LpVec3
+ XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketProcessor
- XXX.minecraft.network.PacketProcessor$ListenerAndPacket
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.ProtocolInfo
+ XXX.minecraft.network.ProtocolInfo$Details
- XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
+ XXX.minecraft.network.ProtocolInfo$DetailsProvider
- XXX.minecraft.network.ProtocolSwapHandler
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.RegistryFriendlyByteBuf
+ XXX.minecraft.network.ServerboundPacketListener
- XXX.minecraft.network.SkipPacketDecoderException
+ XXX.minecraft.network.SkipPacketEncoderException
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
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.package-info
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
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerTickRateManager
- XXX.minecraft.server.Services
+ XXX.minecraft.server.SuppressedExceptionCollector
- XXX.minecraft.server.SuppressedExceptionCollector$LongEntry
+ XXX.minecraft.server.SuppressedExceptionCollector$ShortEntry
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
+ XXX.minecraft.stats.RecipeBookSettings$1
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
+ XXX.minecraft.stats.ServerRecipeBook$Packed
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
+ XXX.minecraft.tags.DialogTags
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
+ XXX.minecraft.util.BoundedFloatFunction
- XXX.minecraft.util.BoundedFloatFunction$1
+ XXX.minecraft.util.BoundedFloatFunction$2
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
- XXX.minecraft.util.LenientJsonParser
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.ListAndDeque
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.NullOps
+ XXX.minecraft.util.NullOps$1
- XXX.minecraft.util.NullOps$NullListBuilder
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
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
+ XXX.minecraft.util.StrictJsonParser
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
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
- XXX.minecraft.world.Stopwatch
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
+ XXX.models.blockstates.BlockModelDefinitionGenerator
- XXX.models.blockstates.ConditionBuilder
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.MultiVariantGenerator$Empty
+ XXX.models.blockstates.MultiVariantGenerator$Entry
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyValueList
- XXX.models.model.DelegatedModel
+ XXX.models.model.ItemModelUtils
- XXX.models.model.ModelInstance
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
+ XXX.mojang.blaze3d.package-info
+ XXX.mojang.realmsclient.package-info
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
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
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.CollectToTag$CompoundBuilder
- XXX.nbt.visitors.CollectToTag$ContainerBuilder
+ XXX.nbt.visitors.CollectToTag$ListBuilder
- XXX.nbt.visitors.CollectToTag$RootBuilder
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
- XXX.network.chat.ClickEvent$ChangePage
+ XXX.network.chat.ClickEvent$CopyToClipboard
- XXX.network.chat.ClickEvent$Custom
+ XXX.network.chat.ClickEvent$OpenFile
- XXX.network.chat.ClickEvent$OpenUrl
+ XXX.network.chat.ClickEvent$RunCommand
- XXX.network.chat.ClickEvent$ShowDialog
+ XXX.network.chat.ClickEvent$SuggestCommand
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FontDescription
+ XXX.network.chat.FontDescription$AtlasSprite
- XXX.network.chat.FontDescription$PlayerSprite
+ XXX.network.chat.FontDescription$Resource
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
- XXX.network.chat.HoverEvent$ShowEntity
+ XXX.network.chat.HoverEvent$ShowItem
- XXX.network.chat.HoverEvent$ShowText
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ValidationException
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
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
+ XXX.network.codec.ByteBufCodecs$29
- XXX.network.codec.ByteBufCodecs$3
+ XXX.network.codec.ByteBufCodecs$30
- XXX.network.codec.ByteBufCodecs$31
+ XXX.network.codec.ByteBufCodecs$32
- XXX.network.codec.ByteBufCodecs$33
+ XXX.network.codec.ByteBufCodecs$34
- XXX.network.codec.ByteBufCodecs$35
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
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
- XXX.network.codec.StreamCodec$17
- XXX.network.codec.StreamCodec$19
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
+ XXX.network.syncher.package-info
- XXX.network.syncher.SyncedDataHolder
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$Builder
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packrat.commands.CommandArgumentParser
+ XXX.packrat.commands.CommandArgumentParser$1
- XXX.packrat.commands.CommandArgumentParser$2
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.GreedyPatternParseRule
+ XXX.packrat.commands.GreedyPredicateParseRule
- XXX.packrat.commands.NumberRunParseRule
+ XXX.packrat.commands.package-info
+ XXX.packrat.commands.ParserBasedArgument
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$1
- XXX.packrat.commands.StringReaderTerms$2
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacters
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
- XXX.packrat.commands.UnquotedStringParseRule
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
- XXX.packs.metadata.MetadataSectionType$WithValue
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
- XXX.packs.resources.PreparableReloadListener$SharedState
+ XXX.packs.resources.PreparableReloadListener$StateKey
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
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.parsing.packrat.Atom
- XXX.parsing.packrat.CachedParseState
+ XXX.parsing.packrat.CachedParseState$CacheEntry
- XXX.parsing.packrat.CachedParseState$PositionCache
+ XXX.parsing.packrat.CachedParseState$Silent
- XXX.parsing.packrat.CachedParseState$SimpleControl
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Control$1
+ XXX.parsing.packrat.DelayedException
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.Dictionary$Entry
- XXX.parsing.packrat.Dictionary$Reference
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorCollector$LongestOnly$MutableErrorEntry
- XXX.parsing.packrat.ErrorCollector$Nop
+ XXX.parsing.packrat.ErrorEntry
- XXX.parsing.packrat.NamedRule
- XXX.parsing.packrat.package-info
+ XXX.parsing.packrat.ParseState
- XXX.parsing.packrat.Rule
+ XXX.parsing.packrat.Rule$RuleAction
- XXX.parsing.packrat.Rule$SimpleRuleAction
+ XXX.parsing.packrat.Rule$WrappedTerm
- XXX.parsing.packrat.Scope
+ XXX.parsing.packrat.Scope$1
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$3
+ XXX.parsing.packrat.Term$Alternative
- XXX.parsing.packrat.Term$LookAhead
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Repeated
- XXX.parsing.packrat.Term$RepeatedWithSeparator
+ XXX.parsing.packrat.Term$Sequence
+ XXX.player.inventory.Hotbar
- XXX.player.inventory.package-info
- XXX.pools.alias.DirectPoolAlias
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.RandomGroupPoolAlias
+ XXX.pools.alias.RandomPoolAlias
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JfrProfiler$2
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
+ XXX.protocol.common.ClientboundShowDialogPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomClickActionPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundCodeOfConductPacket
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
- XXX.protocol.configuration.ConfigurationPacketTypes
+ XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
+ XXX.protocol.configuration.ServerboundAcceptCodeOfConductPacket
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
- XXX.protocol.configuration.ServerConfigurationPacketListener
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
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
+ XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
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
- XXX.protocol.game.ClientboundDebugBlockValuePacket
+ XXX.protocol.game.ClientboundDebugChunkValuePacket
- XXX.protocol.game.ClientboundDebugEntityValuePacket
+ XXX.protocol.game.ClientboundDebugEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundGameTestHighlightPosPacket
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
+ XXX.protocol.game.ClientboundTrackedWaypointPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChangeGameModePacket
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
+ XXX.protocol.game.ServerboundDebugSubscriptionRequestPacket
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
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
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
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
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
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.realmsclient.dto.package-info
- XXX.realmsclient.dto.PendingInvite
+ XXX.realmsclient.dto.PendingInvitesList
- XXX.realmsclient.dto.PingResult
+ XXX.realmsclient.dto.PlayerInfo
- XXX.realmsclient.dto.PreferredRegionsDto
+ XXX.realmsclient.dto.RealmsConfigurationDto
- XXX.realmsclient.dto.RealmsDescriptionDto
+ XXX.realmsclient.dto.RealmsJoinInformation
- XXX.realmsclient.dto.RealmsJoinInformation$RegionData
+ XXX.realmsclient.dto.RealmsNews
- XXX.realmsclient.dto.RealmsNotification
+ XXX.realmsclient.dto.RealmsNotification$InfoPopup
- XXX.realmsclient.dto.RealmsNotification$UrlButton
+ XXX.realmsclient.dto.RealmsNotification$VisitUrl
- XXX.realmsclient.dto.RealmsRegion
+ XXX.realmsclient.dto.RealmsRegion$RealmsRegionJsonAdapter
- XXX.realmsclient.dto.RealmsServer
+ XXX.realmsclient.dto.RealmsServer$Compatibility
- XXX.realmsclient.dto.RealmsServer$McoServerComparator
+ XXX.realmsclient.dto.RealmsServer$State
- XXX.realmsclient.dto.RealmsServer$WorldType
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsSetting
- XXX.realmsclient.dto.RealmsSlot
+ XXX.realmsclient.dto.RealmsSlot$RealmsWorldOptionsJsonAdapter
- XXX.realmsclient.dto.RealmsSlotUpdateDto
+ XXX.realmsclient.dto.RealmsText
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionDataDto
- XXX.realmsclient.dto.RegionPingResult
+ XXX.realmsclient.dto.RegionSelectionPreference
- XXX.realmsclient.dto.RegionSelectionPreference$RegionSelectionPreferenceJsonAdapter
+ XXX.realmsclient.dto.RegionSelectionPreferenceDto
+ XXX.realmsclient.dto.ServerActivityList
- XXX.realmsclient.dto.ServiceQuality
+ XXX.realmsclient.dto.ServiceQuality$RealmsServiceQualityJsonAdapter
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
+ XXX.realmsclient.gui.package-info
- XXX.realmsclient.gui.RealmsDataFetcher
+ XXX.realmsclient.gui.RealmsDataFetcher$ServerListData
- XXX.realmsclient.gui.RealmsNewsManager
+ XXX.realmsclient.gui.RealmsServerList
- XXX.realmsclient.gui.RealmsWorldSlotButton
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$RealmsIoConsumer
- XXX.realmsclient.util.RealmsUtil$RealmsIoFunction
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.AbstractEndPortalRenderer
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
- XXX.renderer.blockentity.ChestRenderer$1
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.CopperGolemStatueBlockRenderer
+ XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
+ XXX.renderer.blockentity.HangingSignRenderer$ModelKey
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShelfRenderer
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
- XXX.renderer.chunk.ChunkSectionLayer
+ XXX.renderer.chunk.ChunkSectionLayerGroup
- XXX.renderer.chunk.ChunkSectionsToRender
- XXX.renderer.chunk.CompiledSectionMesh
+ XXX.renderer.chunk.CompiledSectionMesh$1
- XXX.renderer.chunk.CompiledSectionMesh$2
+ XXX.renderer.chunk.CompileTaskDynamicQueue
- XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderSectionRegion
+ XXX.renderer.chunk.SectionBuffers
- XXX.renderer.chunk.SectionCompiler
+ XXX.renderer.chunk.SectionCompiler$Results
- XXX.renderer.chunk.SectionCopy
+ XXX.renderer.chunk.SectionMesh
- XXX.renderer.chunk.SectionRenderDispatcher
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
+ XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
- XXX.renderer.chunk.TranslucencyPointOfView
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BreezeDebugRenderer
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkCullingDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.EntityBlockIntersectionDebugRenderer
- XXX.renderer.debug.EntityHitboxDebugRenderer
- XXX.renderer.entity.NautilusRenderer
+ XXX.renderer.feature.HitboxFeatureRenderer
- XXX.renderer.feature.ItemFeatureRenderer
+ XXX.renderer.feature.LeashFeatureRenderer
- XXX.renderer.feature.ModelFeatureRenderer
+ XXX.renderer.feature.ModelFeatureRenderer$CrumblingOverlay
- XXX.renderer.feature.ModelFeatureRenderer$Storage
+ XXX.renderer.feature.ModelPartFeatureRenderer
- XXX.renderer.feature.ModelPartFeatureRenderer$Storage
+ XXX.renderer.feature.NameTagFeatureRenderer
- XXX.renderer.feature.NameTagFeatureRenderer$Storage
+ XXX.renderer.feature.package-info
+ XXX.renderer.feature.ParticleFeatureRenderer
- XXX.renderer.feature.ParticleFeatureRenderer$ParticleBufferCache
+ XXX.renderer.feature.ShadowFeatureRenderer
- XXX.renderer.feature.TextFeatureRenderer
- XXX.renderer.fog.FogData
+ XXX.renderer.fog.FogRenderer
- XXX.renderer.fog.FogRenderer$FogMode
- XXX.renderer.fog.package-info
- XXX.renderer.gizmos.DrawableGizmoPrimitives$Line
- XXX.renderer.gizmos.DrawableGizmoPrimitives$Quad
- XXX.renderer.gizmos.DrawableGizmoPrimitives$TriangleFan
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.screens.configuration.package-info
- XXX.screens.configuration.RealmsBackupInfoScreen
+ XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoList
- XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoListEntry
+ XXX.screens.configuration.RealmsBackupScreen
- XXX.screens.configuration.RealmsBackupScreen$1
+ XXX.screens.configuration.RealmsBackupScreen$BackupObjectSelectionList
- XXX.screens.configuration.RealmsBackupScreen$Entry
+ XXX.screens.configuration.RealmsConfigurationTab
- XXX.screens.configuration.RealmsConfigureWorldScreen
+ XXX.screens.configuration.RealmsInviteScreen
- XXX.screens.configuration.RealmsPlayersTab
+ XXX.screens.configuration.RealmsPlayersTab$Entry
- XXX.screens.configuration.RealmsPlayersTab$HeaderEntry
+ XXX.screens.configuration.RealmsPlayersTab$InvitedObjectSelectionList
- XXX.screens.configuration.RealmsPlayersTab$PlayerEntry
+ XXX.screens.configuration.RealmsPreferredRegionSelectionScreen
- XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList
+ XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry
- XXX.screens.configuration.RealmsSettingsTab
+ XXX.screens.configuration.RealmsSettingsTab$RegionSelection
- XXX.screens.configuration.RealmsSlotOptionsScreen
+ XXX.screens.configuration.RealmsSlotOptionsScreen$SettingsSlider
- XXX.screens.configuration.RealmsSubscriptionTab
+ XXX.screens.configuration.RealmsWorldsTab
- XXX.screens.configuration.RealmsWorldsTab$1
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
+ XXX.server.commands.DialogCommand
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
+ XXX.server.commands.FetchProfileCommand
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$1UpdatedPosition
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
- XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
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
+ XXX.server.commands.VersionCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WaypointCommand
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
- XXX.server.dialog.ActionButton
+ XXX.server.dialog.ButtonListDialog
- XXX.server.dialog.CommonButtonData
+ XXX.server.dialog.CommonDialogData
- XXX.server.dialog.ConfirmationDialog
+ XXX.server.dialog.Dialog
- XXX.server.dialog.DialogAction
+ XXX.server.dialog.DialogListDialog
+ XXX.server.dialog.Dialogs
- XXX.server.dialog.DialogTypes
- XXX.server.dialog.Input
+ XXX.server.dialog.MultiActionDialog
- XXX.server.dialog.NoticeDialog
- XXX.server.dialog.package-info
+ XXX.server.dialog.ServerLinksDialog
- XXX.server.dialog.SimpleDialog
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.jsonrpc.Connection
- XXX.server.jsonrpc.IncomingRpcMethod
+ XXX.server.jsonrpc.IncomingRpcMethod$Attributes
- XXX.server.jsonrpc.IncomingRpcMethod$Factory
+ XXX.server.jsonrpc.IncomingRpcMethod$IncomingRpcMethodBuilder
- XXX.server.jsonrpc.IncomingRpcMethod$Method
+ XXX.server.jsonrpc.IncomingRpcMethod$ParameterlessMethod
- XXX.server.jsonrpc.IncomingRpcMethod$ParameterlessRpcMethodFunction
+ XXX.server.jsonrpc.IncomingRpcMethod$RpcMethodFunction
- XXX.server.jsonrpc.IncomingRpcMethods
+ XXX.server.jsonrpc.JsonRPCErrors
+ XXX.server.jsonrpc.JsonRpcLogger
- XXX.server.jsonrpc.JsonRpcNotificationService
- XXX.server.jsonrpc.JsonRPCUtils
+ XXX.server.jsonrpc.ManagementServer
- XXX.server.jsonrpc.ManagementServer$1
+ XXX.server.jsonrpc.OutgoingRpcMethod
- XXX.server.jsonrpc.OutgoingRpcMethod$Attributes
+ XXX.server.jsonrpc.OutgoingRpcMethod$Factory
- XXX.server.jsonrpc.OutgoingRpcMethod$Method
+ XXX.server.jsonrpc.OutgoingRpcMethod$Notification
- XXX.server.jsonrpc.OutgoingRpcMethod$OutgoingRpcMethodBuilder
+ XXX.server.jsonrpc.OutgoingRpcMethod$ParameterlessMethod
- XXX.server.jsonrpc.OutgoingRpcMethod$ParmeterlessNotification
+ XXX.server.jsonrpc.OutgoingRpcMethods
+ XXX.server.jsonrpc.package-info
- XXX.server.jsonrpc.PendingRpcRequest
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkGenerationTask
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkLevel
- XXX.server.level.ChunkLevel$1
+ XXX.server.level.ChunkLoadCounter
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
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
- XXX.server.level.LoadingChunkTracker
+ XXX.server.level.ParticleStatus
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerSpawnFinder
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerEntity$Synchronizer
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
+ XXX.server.level.ServerPlayer$SavedPosition
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.SimulationChunkTracker
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.ThrottlingChunkTaskDispatcher
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.notifications.package-info
- XXX.server.notifications.ServerActivityMonitor
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
+ XXX.server.packs.OverlayMetadataSection$1
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry$IntermediateEntry
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
- XXX.server.permissions.LevelBasedPermissionSet$1
- XXX.server.permissions.Permission
- XXX.server.permissions.Permission$HasCommandLevel
- XXX.server.permissions.PermissionCheck$AlwaysPass
- XXX.server.permissions.PermissionCheckTypes
- XXX.server.permissions.PermissionProviderCheck
- XXX.server.permissions.Permissions
- XXX.server.permissions.PermissionSetSupplier
- XXX.server.players.package-info
- XXX.server.players.ProfileResolver
+ XXX.server.players.ProfileResolver$Cached
- XXX.server.players.ProfileResolver$Cached$1
+ XXX.server.players.ProfileResolver$Cached$2
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserNameToIdResolver
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.server.waypoints.package-info
+ XXX.server.waypoints.ServerWaypointManager
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
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SideChainPart
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.TestBlockMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
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
- XXX.structure.structures.JigsawStructure$MaxDistance
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
+ XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.TagMatchTest
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
- XXX.util.datafix.PackedBitStorage
- XXX.util.debug.DebugBeeInfo
+ XXX.util.debug.DebugBrainDump
- XXX.util.debug.DebugBreezeInfo
+ XXX.util.debug.DebugEntityBlockIntersection
- XXX.util.debug.DebugGameEventInfo
+ XXX.util.debug.DebugGameEventListenerInfo
- XXX.util.debug.DebugGoalInfo
+ XXX.util.debug.DebugGoalInfo$DebugGoal
- XXX.util.debug.DebugHiveInfo
+ XXX.util.debug.DebugPathInfo
- XXX.util.debug.DebugPoiInfo
+ XXX.util.debug.DebugStructureInfo
- XXX.util.debug.DebugStructureInfo$Piece
+ XXX.util.debug.DebugSubscription
- XXX.util.debug.DebugSubscription$Event
+ XXX.util.debug.DebugSubscription$Update
- XXX.util.debug.DebugSubscriptions
+ XXX.util.debug.DebugValueAccess
- XXX.util.debug.DebugValueAccess$EventVisitor
+ XXX.util.debug.DebugValueSource
- XXX.util.debug.DebugValueSource$Registration
+ XXX.util.debug.DebugValueSource$ValueGetter
- XXX.util.debug.LevelDebugSynchronizers
+ XXX.util.debug.LevelDebugSynchronizers$1
- XXX.util.debug.LevelDebugSynchronizers$2
+ XXX.util.debug.LevelDebugSynchronizers$3
- XXX.util.debug.package-info
- XXX.util.debug.ServerDebugSubscribers
+ XXX.util.debug.TrackingDebugSynchronizer
- XXX.util.debug.TrackingDebugSynchronizer$PoiSynchronizer
+ XXX.util.debug.TrackingDebugSynchronizer$SourceSynchronizer
- XXX.util.debug.TrackingDebugSynchronizer$ValueSource
+ XXX.util.debug.TrackingDebugSynchronizer$VillageSectionSynchronizer
+ XXX.util.debugchart.AbstractSampleLogger
- XXX.util.debugchart.LocalSampleLogger
- XXX.util.debugchart.package-info
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
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
- XXX.util.parsing.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.Profiler
- XXX.util.profiling.Profiler$Scope
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.profiling.TracyZoneFiller
+ XXX.util.profiling.TracyZoneFiller$PlotAndValue
- XXX.util.profiling.Zone
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
- XXX.util.task.package-info
- XXX.util.task.RealmCreationTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
- XXX.world.item.package-info
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.TippedArrowItem
- XXX.world.item.ToolMaterial
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.WeatheringCopperItems
+ XXX.world.item.WindChargeItem
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
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
- XXX.world.level.package-info
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.systems.RenderPass +1P -1P
```
```
XXX.blaze3d.vertex.SheetedDecalTextureGenerator +2M
```
```
XXX.blaze3d.vertex.VertexConsumer -1M | +2P
```
```
XXX.blaze3d.vertex.VertexFormat$Mode +1P -1P
```
```
XXX.blaze3d.vertex.VertexMultiConsumer$Multiple +9M -5M
```
```
XXX.mojang.math.SymmetricGroup3 +11M -3M | +4P -2P
```
```
XXX.realmsclient.client.RealmsClient -1M | -2P
```
```
XXX.realmsclient.dto.BackupList +5M -1M
```
```
XXX.realmsclient.dto.Ops +6M -1M | +1P
```
```
XXX.minecraft.client.OptionInstance$SliderableValueSet +2M
```
```
XXX.minecraft.client.Options$5 -1P
```
```
XXX.gui.components.CycleButton$Builder +1M -2M | +1P -2P
```
```
XXX.gui.components.FocusableTextWidget +12M -4M | +1P
```
```
XXX.gui.components.StringWidget +1M -1M
```
```
XXX.components.debug.DebugScreenEntries +9P
```
```
XXX.components.debug.DebugScreenEntryList +3M -3M | +3P -1P
```
```
XXX.components.debug.DebugScreenEntryStatus +1P -1P
```
```
XXX.gui.screens.ChatScreen +1M -1M
```
```
XXX.gui.screens.DirectJoinServerScreen +1M -1M
```
```
XXX.gui.screens.ManageServerScreen +1M -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +1M -1M
```
```
XXX.screens.inventory.AnvilScreen +1M -1M
```
```
XXX.screens.inventory.CreativeModeInventoryScreen +1M -1M
```
```
XXX.screens.inventory.EffectsInInventory +4M -5M | +6P -3P
```
```
XXX.screens.inventory.JigsawBlockEditScreen +1M -1M
```
```
XXX.screens.inventory.MinecartCommandBlockEditScreen +2M -2M | +1P -1P
```
```
XXX.screens.options.OptionsSubScreen +1M
```
```
XXX.client.input.InputQuirks -2P
```
```
XXX.client.model.HumanoidModel +3M -3M
```
```
XXX.client.renderer.PostPass$TargetInput -1M
```
```
XXX.client.renderer.RenderPipelines +1P -5P
```
```
XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder -1M | -1P
```
```
XXX.client.renderer.ShapeRenderer +2M -9M
```
```
XXX.client.renderer.UniformValue$IVec3Uniform +2M -2M | +1P -1P
```
```
XXX.client.renderer.UniformValue$Vec2Uniform +2M -2M | +1P -1P
```
```
XXX.client.renderer.UniformValue$Vec4Uniform +2M -2M | +1P -1P
```
```
XXX.renderer.debug.GameTestBlockHighlightRenderer$Marker -4M
```
```
XXX.renderer.debug.HeightMapRenderer +1M -1M
```
```
XXX.renderer.debug.LightDebugRenderer +2M -2M | +2P
```
```
XXX.renderer.debug.PathfindingRenderer +6M -6M
```
```
XXX.renderer.debug.RaidDebugRenderer +4M -4M
```
```
XXX.renderer.debug.SolidFaceRenderer +2M -1M
```
```
XXX.renderer.debug.SupportBlockRenderer +6M -6M
```
```
XXX.renderer.debug.WaterDebugRenderer +1M -1M
```
```
XXX.renderer.entity.DrownedRenderer +1M
```
```
XXX.renderer.entity.EntityRenderers +3M -1M
```
```
XXX.entity.state.ArmedEntityRenderState +5M -2M | +6P -2P
```
```
XXX.entity.state.EntityRenderState -2P
```
```
XXX.renderer.feature.FeatureRenderDispatcher -1P
```
```
XXX.renderer.texture.AbstractTexture +1M -3M | +1P
```
```
XXX.renderer.texture.MipmapGenerator +6M -2M | +1P
```
```
XXX.renderer.texture.OverlayTexture +1P
```
```
XXX.renderer.texture.SpriteContents +2M -2M | +2P
```
```
XXX.resources.model.BlockModelRotation +2M -7M | +2P -21P
```
```
XXX.resources.model.EquipmentClientInfo$LayerType +2P
```
```
XXX.client.server.IntegratedServer +4M -2M | +2P
```
```
XXX.minecraft.commands.CommandSourceStack +5M -5M | +1P -1P
```
```
XXX.arguments.selector.EntitySelectorParser +1M
```
```
XXX.commands.synchronization.ArgumentUtils +2M -1M
```
```
XXX.core.component.DataComponentType +1P
```
```
XXX.core.component.DataComponentType$Builder$SimpleType +2M -1M | +1P
```
```
XXX.gametest.framework.GameTestHelper +4M -2M
```
```
XXX.gametest.framework.GameTestServer +2M -4M
```
```
XXX.server.notifications.NotificationManager +1M
```
```
XXX.jfr.stats.TimedStatSummary +1M -1M
```
```
XXX.world.damagesource.DamageTypes +1P
```
```
XXX.world.entity.Entity +1M
```
```
XXX.world.entity.LivingEntity +18M -8M | +4P -2P
```
```
XXX.world.entity.Mob +8M -6M
```
```
XXX.world.entity.PlayerRideableJumping +1M
```
```
XXX.ai.util.RandomPos +2M -2M
```
```
XXX.entity.animal.Cat$CatRelaxOnOwnerGoal +1M
```
```
XXX.entity.animal.PolarBear +4M -4M | +2P -2P
```
```
XXX.animal.wolf.Wolf +4M -4M | +2P -2P
```
```
XXX.entity.monster.AbstractSkeleton -1M
```
```
XXX.entity.monster.Drowned +2M | +2P
```
```
XXX.entity.monster.EnderMan +4M -4M | +2P -2P
```
```
XXX.entity.monster.Husk +1M -1M
```
```
XXX.entity.monster.Phantom -1M
```
```
XXX.monster.creaking.Creaking -3M
```
```
XXX.entity.npc.AbstractVillager +1M -1M | +1P -1P
```
```
XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds +1M -1M
```
```
XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem +1M -1M
```
```
XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds +1M -1M
```
```
XXX.entity.npc.VillagerTrades$ItemListing +1P -1P
```
```
XXX.entity.npc.VillagerTrades$ItemsForEmeralds +2M -2M
```
```
XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds +2M -2M
```
```
XXX.entity.npc.VillagerTrades$TypeSpecificTrade +1M -1M
```
```
XXX.entity.npc.WanderingTrader +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +4M -1M
```
```
XXX.entity.raid.Raid -1P
```
```
XXX.entity.vehicle.AbstractMinecart +1M -1M
```
```
XXX.entity.vehicle.Minecart +1M -1M
```
```
XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase +2M -5M
```
```
XXX.entity.vehicle.MinecartHopper +1M -1M
```
```
XXX.world.item.Item$Properties +2M
```
```
XXX.world.item.ItemUseAnimation +2M | +2P
```
```
XXX.world.item.Items +14P
```
```
XXX.item.enchantment.Enchantment +9M -7M
```
```
XXX.item.enchantment.EnchantmentHelper +34M -32M
```
```
XXX.world.level.ServerLevelAccessor +1P
```
```
XXX.level.biome.AmbientAdditionsSettings +5M -2M
```
```
XXX.level.biome.AmbientParticleSettings +5M -1M
```
```
XXX.level.saveddata.SavedDataType +2M -5M | +2P -2P
```
```
XXX.world.phys.Vec3 +5M -1M
```
```
XXX.phys.shapes.Shapes +1M -1M
```
```
XXX.world.scores.ScoreboardSaveData +5M -4M | +2P -2P
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
</summary>

```diff
- VertexConsumer setColor(int)
- VertexConsumer setLineWidth(float)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexConsumer
</summary>

```diff
+ VertexConsumer setColor(int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexMultiConsumer$Multiple
</summary>

```diff
- VertexConsumer setColor(int)
- VertexConsumer setLineWidth(float)
+ void lambda$addVertex$6(float,float,float,int,float,float,int,int,float,float,float,VertexConsumer)
- void lambda$addVertex$8(float,float,float,int,float,float,int,int,float,float,float,VertexConsumer)
- void lambda$setColor$2(int,VertexConsumer)
- void lambda$setLineWidth$7(float,VertexConsumer)
+ void lambda$setNormal$5(float,float,float,VertexConsumer)
- void lambda$setNormal$6(float,float,float,VertexConsumer)
+ void lambda$setUv$2(float,float,VertexConsumer)
- void lambda$setUv$3(float,float,VertexConsumer)
+ void lambda$setUv1$3(int,int,VertexConsumer)
- void lambda$setUv1$4(int,int,VertexConsumer)
+ void lambda$setUv2$4(int,int,VertexConsumer)
- void lambda$setUv2$5(int,int,VertexConsumer)
```

</details>
<details>
<summary>
com.mojang.math.SymmetricGroup3
</summary>

```diff
- boolean lambda$static$0(int,int,int,SymmetricGroup3)
+ boolean lambda$static$0(int[],SymmetricGroup3)
- boolean lambda$static$2(SymmetricGroup3,SymmetricGroup3)
- Direction$Axis permuteAxis(Direction$Axis)
+ int permutation(int)
- int permute(int)
- SymmetricGroup3 inverse()
- SymmetricGroup3 lambda$static$3(SymmetricGroup3)
- SymmetricGroup3[] lambda$static$4(int)
- SymmetricGroup3[] lambda$static$5()
- SymmetricGroup3[][] lambda$static$1()
- Vector3f permuteVector(Vector3f)
- Vector3i permuteVector(Vector3i)
+ void lambda$static$1(SymmetricGroup3[][])
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.RealmsClient
</summary>

```diff
+ ServerActivityList getActivity(long)
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.BackupList
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- List backups()
- String toString()
+ void <init>()
- void <init>(List)
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.Ops
</summary>

```diff
- boolean equals(Object)
- int hashCode()
- Set ops()
- String toString()
- void <clinit>()
+ void <init>()
- void <init>(Set)
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$SliderableValueSet
</summary>

```diff
- Optional next(Object)
- Optional previous(Object)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CycleButton$Builder
</summary>

```diff
+ CycleButton$Builder withInitialValue(Object)
- void <init>(Function,Supplier)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.FocusableTextWidget
</summary>

```diff
- FocusableTextWidget$Builder builder(Component,Font,int)
- FocusableTextWidget$Builder builder(Component,Font)
- int getHeight()
- int getPadding()
- int getTextX()
- int getTextY()
- int getWidth()
- MultiLineTextWidget setMaxWidth(int)
- void <init>(Component,Font,int,int,FocusableTextWidget$BackgroundFill,boolean)
+ void <init>(int,Component,Font,boolean,FocusableTextWidget$BackgroundFill,int)
+ void <init>(int,Component,Font,int)
+ void <init>(int,Component,Font)
+ void containWithin(int)
- void setMessage(Component)
- void updateHeight()
- void updateWidth()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.StringWidget
</summary>

```diff
- FormattedCharSequence clipText(Component,Font,int)
+ FormattedCharSequence clipText(Component,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.debug.DebugScreenEntryList
</summary>

```diff
+ boolean isF3Visible()
- boolean isOverlayVisible()
+ void setF3Visible(boolean)
- void setOverlayVisible(boolean)
- void toggleDebugOverlay()
+ void toggleF3Visible()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ChatScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DirectJoinServerScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ManageServerScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AnvilScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.EffectsInInventory
</summary>

```diff
- int renderBackground(GuiGraphics,Font,Component,int,int,boolean,int)
- void render(GuiGraphics,int,int)
+ void renderBackgrounds(GuiGraphics,int,int,Iterable,boolean)
- void renderEffects(GuiGraphics,Collection,int,int,int,int,int)
+ void renderEffects(GuiGraphics,int,int)
+ void renderIcons(GuiGraphics,int,int,Iterable,boolean)
+ void renderLabels(GuiGraphics,int,int,Iterable)
- void renderText(GuiGraphics,MobEffectInstance,Component,Font,int,int,int,int,int,int)
+ void renderTooltip(GuiGraphics,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
</summary>

```diff
- void resize(int,int)
+ void resize(Minecraft,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
</summary>

```diff
+ void <init>(BaseCommandBlock)
- void <init>(MinecartCommandBlock)
- void populateAndSendPacket()
+ void populateAndSendPacket(BaseCommandBlock)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.OptionsSubScreen
</summary>

```diff
- void resetOption(OptionInstance)
```

</details>
<details>
<summary>
net.minecraft.client.model.HumanoidModel
</summary>

```diff
+ void poseLeftArm(HumanoidRenderState,HumanoidModel$ArmPose)
- void poseLeftArm(HumanoidRenderState)
+ void poseRightArm(HumanoidRenderState,HumanoidModel$ArmPose)
- void poseRightArm(HumanoidRenderState)
+ void setupAttackAnimation(HumanoidRenderState,float)
- void setupAttackAnimation(HumanoidRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.PostPass$TargetInput
</summary>

```diff
+ void cleanup(Map)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
</summary>

```diff
+ RenderType$CompositeState$CompositeStateBuilder setLineState(RenderStateShard$LineStateShard)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ShapeRenderer
</summary>

```diff
+ void addChainedFilledBoxVertices(PoseStack,VertexConsumer,double,double,double,double,double,double,float,float,float,float)
+ void addChainedFilledBoxVertices(PoseStack,VertexConsumer,float,float,float,float,float,float,float,float,float,float)
+ void lambda$renderShape$0(VertexConsumer,PoseStack$Pose,double,double,double,int,double,double,double,double,double,double)
- void lambda$renderShape$0(VertexConsumer,PoseStack$Pose,double,double,double,int,float,double,double,double,double,double,double)
+ void renderFace(Matrix4f,VertexConsumer,Direction,float,float,float,float,float,float,float,float,float,float)
+ void renderLineBox(PoseStack$Pose,VertexConsumer,AABB,float,float,float,float)
+ void renderLineBox(PoseStack$Pose,VertexConsumer,double,double,double,double,double,double,float,float,float,float,float,float,float)
+ void renderLineBox(PoseStack$Pose,VertexConsumer,double,double,double,double,double,double,float,float,float,float)
- void renderShape(PoseStack,VertexConsumer,VoxelShape,double,double,double,int,float)
+ void renderShape(PoseStack,VertexConsumer,VoxelShape,double,double,double,int)
+ void renderVector(PoseStack,VertexConsumer,Vector3f,Vec3,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.UniformValue$IVec3Uniform
</summary>

```diff
+ Vector3i value()
- Vector3ic value()
+ void <init>(Vector3i)
- void <init>(Vector3ic)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.UniformValue$Vec2Uniform
</summary>

```diff
+ Vector2f value()
- Vector2fc value()
+ void <init>(Vector2f)
- void <init>(Vector2fc)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.UniformValue$Vec4Uniform
</summary>

```diff
+ Vector4f value()
- Vector4fc value()
+ void <init>(Vector4f)
- void <init>(Vector4fc)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.GameTestBlockHighlightRenderer$Marker
</summary>

```diff
+ float getA()
+ float getB()
+ float getG()
+ float getR()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.HeightMapRenderer
</summary>

```diff
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.LightDebugRenderer
</summary>

```diff
- void <init>(Minecraft,boolean,boolean)
+ void <init>(Minecraft)
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.PathfindingRenderer
</summary>

```diff
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
- void lambda$emitGizmos$0(DebugValueAccess,double,double,double,Entity)
- void lambda$emitGizmos$1(double,double,double,Entity,DebugPathInfo)
+ void lambda$render$0(DebugValueAccess,PoseStack,MultiBufferSource,double,double,double,Entity)
+ void lambda$render$1(PoseStack,MultiBufferSource,double,double,double,Entity,DebugPathInfo)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
- void renderPath(double,double,double,Path,float)
- void renderPath(Path,float,boolean,boolean,double,double,double)
+ void renderPath(PoseStack,MultiBufferSource,double,double,double,Path,float)
+ void renderPath(PoseStack,MultiBufferSource,Path,float,boolean,boolean,double,double,double)
- void renderPathLine(Path,double,double,double)
+ void renderPathLine(PoseStack,VertexConsumer,Path,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.RaidDebugRenderer
</summary>

```diff
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
- void highlightRaidCenter(BlockPos)
+ void highlightRaidCenter(PoseStack,MultiBufferSource,BlockPos)
- void lambda$emitGizmos$0(BlockPos,ChunkPos,List)
+ void lambda$render$0(BlockPos,PoseStack,MultiBufferSource,ChunkPos,List)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
+ void renderTextOverBlock(PoseStack,MultiBufferSource,String,BlockPos,int)
- void renderTextOverBlock(String,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.SolidFaceRenderer
</summary>

```diff
- void addFaceIfSturdy(BlockPos,BlockState,BlockGetter,Direction,Vec3,Vec3,int)
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.SupportBlockRenderer
</summary>

```diff
- double lambda$emitGizmos$0()
- double lambda$emitGizmos$1(Entity)
+ double lambda$render$0()
+ double lambda$render$1(Entity)
- void drawHighlights(Entity,DoubleSupplier,int)
+ void drawHighlights(PoseStack,MultiBufferSource,double,double,double,Entity,DoubleSupplier,float,float,float)
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
- void highlightPosition(BlockPos,double,int)
+ void highlightPosition(BlockPos,PoseStack,double,double,double,MultiBufferSource,double,float,float,float)
- void lambda$drawHighlights$2(DoubleSupplier,Entity,int,BlockPos)
+ void lambda$drawHighlights$2(DoubleSupplier,Entity,PoseStack,double,double,double,MultiBufferSource,float,float,float,BlockPos)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.debug.WaterDebugRenderer
</summary>

```diff
- void emitGizmos(double,double,double,DebugValueAccess,Frustum,float)
+ void render(PoseStack,MultiBufferSource,double,double,double,DebugValueAccess,Frustum)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DrownedRenderer
</summary>

```diff
- HumanoidModel$ArmPose getArmPose(Zombie,HumanoidArm)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderers
</summary>

```diff
- EntityRenderer lambda$static$41(EntityRendererProvider$Context)
- EntityRenderer lambda$static$42(EntityRendererProvider$Context)
+ void lambda$createEntityRenderers$41(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
- void lambda$createEntityRenderers$43(ImmutableMap$Builder,EntityRendererProvider$Context,EntityType,EntityRendererProvider)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.state.ArmedEntityRenderState
</summary>

```diff
- float ticksUsingItem(HumanoidArm)
- ItemStack getMainHandItemStack()
- ItemStack getUseItemStackForArm(HumanoidArm)
+ ItemStackRenderState getMainHandItem()
- ItemStackRenderState getMainHandItemState()
- void extractArmedEntityRenderState(LivingEntity,ArmedEntityRenderState,ItemModelResolver,float)
+ void extractArmedEntityRenderState(LivingEntity,ArmedEntityRenderState,ItemModelResolver)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.AbstractTexture
</summary>

```diff
- GpuSampler getSampler()
+ void setClamp(boolean)
+ void setFilter(boolean,boolean)
+ void setUseMipmaps(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.MipmapGenerator
</summary>

```diff
- float getInversePow22(float)
+ int alphaBlend(int,int,int,int,boolean)
- int alphaBlend(int,int,int,int)
- int darkenedAlphaBlend(int,int,int,int)
- int gammaBlend(int,int,int,int)
- NativeImage[] generateMipLevels(NativeImage[],int,boolean)
+ NativeImage[] generateMipLevels(NativeImage[],int)
- void accumulate(int,float[])
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.SpriteContents
</summary>

```diff
- void <init>(ResourceLocation,FrameSize,NativeImage,Optional,List,boolean)
+ void <init>(ResourceLocation,FrameSize,NativeImage,Optional,List)
- void upload(int,int,int,int,NativeImage[],GpuTexture,int)
+ void upload(int,int,int,int,NativeImage[],GpuTexture)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.BlockModelRotation
</summary>

```diff
+ BlockModelRotation by(Quadrant,Quadrant)
- BlockModelRotation get(OctahedralGroup)
+ BlockModelRotation valueOf(String)
+ BlockModelRotation[] $values()
+ BlockModelRotation[] values()
+ OctahedralGroup actualRotation()
- void <init>(OctahedralGroup)
+ void <init>(String,int,Quadrant,Quadrant)
+ void lambda$static$0(BlockModelRotation[][])
```

</details>
<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- Collection getPerTickGizmos()
+ int getFunctionCompilationLevel()
+ int operatorUserPermissionLevel()
- LevelBasedPermissionSet getFunctionCompilationPermissions()
- LevelBasedPermissionSet operatorUserPermissions()
- PermissionSet getFunctionCompilationPermissions()
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ boolean hasPermission(int)
+ CommandSourceStack withMaximumPermission(int)
- CommandSourceStack withMaximumPermission(PermissionSet)
+ CommandSourceStack withPermission(int)
- CommandSourceStack withPermission(PermissionSet)
- PermissionSet permissions()
+ void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity,boolean,CommandResultCallback,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer)
+ void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity)
- void <init>(CommandSource,Vec3,Vec2,ServerLevel,PermissionSet,String,Component,MinecraftServer,Entity,boolean,CommandResultCallback,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer)
- void <init>(CommandSource,Vec3,Vec2,ServerLevel,PermissionSet,String,Component,MinecraftServer,Entity)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
- boolean allowSelectors(PermissionSetSupplier)
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.ArgumentUtils
</summary>

```diff
- IllegalStateException lambda$serializeNodeToJson$0(String)
+ void lambda$findUsedArgumentTypes$0(Set,Set,CommandNode)
- void lambda$findUsedArgumentTypes$1(Set,Set,CommandNode)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentType$Builder$SimpleType
</summary>

```diff
- boolean ignoreSwapAnimation()
- void <init>(Codec,StreamCodec,boolean)
+ void <init>(Codec,StreamCodec)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- Entity spawn(EntityType,Vec3,EntitySpawnReason)
- Mob spawn(EntityType,int,int,int,EntitySpawnReason)
- void assertFalse(boolean,String)
- void assertTrue(boolean,String)
+ void setDayTime(int)
+ void setNight()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ boolean isCommandBlockEnabled()
+ boolean isSpawnerBlockEnabled()
+ int getFunctionCompilationLevel()
+ int operatorUserPermissionLevel()
- LevelBasedPermissionSet operatorUserPermissions()
- PermissionSet getFunctionCompilationPermissions()
```

</details>
<details>
<summary>
net.minecraft.server.notifications.NotificationManager
</summary>

```diff
- void serverActivityOccured()
```

</details>
<details>
<summary>
net.minecraft.util.profiling.jfr.stats.TimedStatSummary
</summary>

```diff
- Optional summary(List)
+ TimedStatSummary summary(List)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- Vec3 getHeadLookAngle()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ Boolean lambda$checkBedExists$20(BlockPos)
- Boolean lambda$checkBedExists$21(BlockPos)
+ boolean lambda$createEquipmentSlotAccess$24(LivingEntity,EquipmentSlot,ItemStack)
- boolean lambda$createEquipmentSlotAccess$25(LivingEntity,EquipmentSlot,ItemStack)
+ boolean lambda$updateFallFlying$19(EquipmentSlot)
- boolean lambda$updateFallFlying$20(EquipmentSlot)
- boolean stabAttack(EquipmentSlot,Entity,float,boolean,boolean,boolean)
- boolean wasRecentlyStabbed(Entity)
- DamageSource lambda$stabAttack$17()
- float getTicksUsingItem(float)
+ Vec3 lambda$stopSleeping$21(BlockPos)
- Vec3 lambda$stopSleeping$22(BlockPos)
- void causeExtraKnockback(Entity,float,Vec3)
+ void lambda$collectEquipmentChanges$17(Holder,AttributeModifier)
- void lambda$collectEquipmentChanges$18(Holder,AttributeModifier)
+ void lambda$handleEquipmentChanges$18(List,EquipmentSlot,ItemStack)
- void lambda$handleEquipmentChanges$19(List,EquipmentSlot,ItemStack)
+ void lambda$stopLocationBasedEffects$23(AttributeMap,Holder,AttributeModifier)
- void lambda$stopLocationBasedEffects$24(AttributeMap,Holder,AttributeModifier)
+ void lambda$stopSleeping$22(BlockPos)
- void lambda$stopSleeping$23(BlockPos)
- void lungeForwardMaybe()
- void onAttack()
- void playAttackSound()
- void rememberStabbedEntity(Entity)
- void updateDirtyEffects()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
+ boolean lambda$removeFreeWill$3(Goal)
- boolean lambda$removeFreeWill$4(Goal)
- DamageSource lambda$doHurtTarget$3()
+ DebugBrainDump lambda$registerDebugValues$7(ServerLevel)
- DebugBrainDump lambda$registerDebugValues$8(ServerLevel)
+ DebugGoalInfo lambda$registerDebugValues$6()
- DebugGoalInfo lambda$registerDebugValues$7()
+ DebugPathInfo lambda$registerDebugValues$4()
- DebugPathInfo lambda$registerDebugValues$5()
- EquipmentSlot sunProtectionSlot()
- void burnUndead()
+ void lambda$registerDebugValues$5(List,WrappedGoal)
- void lambda$registerDebugValues$6(List,WrappedGoal)
+ void playAttackSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.PlayerRideableJumping
</summary>

```diff
- float getPlayerJumpPendingScale(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.RandomPos
</summary>

```diff
- BlockPos generateRandomDirectionWithinRadians(RandomSource,double,double,int,int,double,double,double)
+ BlockPos generateRandomDirectionWithinRadians(RandomSource,int,int,int,double,double,double)
- BlockPos generateRandomPosTowardDirection(PathfinderMob,double,RandomSource,BlockPos)
+ BlockPos generateRandomPosTowardDirection(PathfinderMob,int,RandomSource,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
</summary>

```diff
- boolean isMorning()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.PolarBear
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.wolf.Wolf
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
+ void aiStep()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
- void <clinit>()
- void rideTick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan
</summary>

```diff
- EntityReference getPersistentAngerTarget()
+ int getRemainingPersistentAngerTime()
- long getPersistentAngerEndTime()
+ UUID getPersistentAngerTarget()
- void setPersistentAngerEndTime(long)
- void setPersistentAngerTarget(EntityReference)
+ void setPersistentAngerTarget(UUID)
+ void setRemainingPersistentAngerTime(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Husk
</summary>

```diff
+ void doUnderWaterConversion()
- void doUnderWaterConversion(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
+ void aiStep()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.creaking.Creaking
</summary>

```diff
+ boolean canAddPassenger(Entity)
+ boolean couldAcceptPassenger()
+ void addPassenger(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ void addOffersFromItemListings(MerchantOffers,VillagerTrades$ItemListing[],int)
- void addOffersFromItemListings(ServerLevel,MerchantOffers,VillagerTrades$ItemListing[],int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
+ void lambda$getOffer$0(ItemStack,Level,Entity,RandomSource,ResourceKey)
- void lambda$getOffer$0(ItemStack,ServerLevel,Entity,RandomSource,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
</summary>

```diff
+ boolean lambda$getOffer$0(Entity,Holder$Reference)
- boolean lambda$getOffer$0(ServerLevel,Holder$Reference)
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource)
- MerchantOffer getOffer(ServerLevel,Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.WanderingTrader
</summary>

```diff
+ void updateTrades()
- void updateTrades(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- Collection findHitEntities(Vec3,Vec3)
- double lambda$stepMoveAndHit$0(Vec3,EntityHitResult)
- ProjectileDeflection hitTargetsOrDeflectSelf(Collection)
+ void lambda$hitBlockEnchantmentEffects$0(Item)
- void lambda$hitBlockEnchantmentEffects$1(Item)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
+ void activateMinecart(int,int,int,boolean)
- void activateMinecart(ServerLevel,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Minecart
</summary>

```diff
+ void activateMinecart(int,int,int,boolean)
- void activateMinecart(ServerLevel,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
</summary>

```diff
+ CommandSourceStack createCommandSourceStack(CommandSource)
- CommandSourceStack createCommandSourceStack(ServerLevel,CommandSource)
+ MinecartCommandBlock getMinecart()
+ ServerLevel getLevel()
+ Vec3 getPosition()
+ void onUpdated()
- void onUpdated(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartHopper
</summary>

```diff
+ void activateMinecart(int,int,int,boolean)
- void activateMinecart(ServerLevel,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
- Item$Properties nautilusArmor(ArmorMaterial)
- Item$Properties spear(ToolMaterial,float,float,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemUseAnimation
</summary>

```diff
- boolean hasCustomArmTransform()
- void <init>(String,int,int,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.Enchantment
</summary>

```diff
- void doLunge(ServerLevel,int,EnchantedItemInUse,Entity)
- void lambda$doLunge$2(ServerLevel,int,EnchantedItemInUse,Entity,EnchantmentEntityEffect)
+ void lambda$modifyDamageFilteredValue$7(MutableFloat,int,Entity,EnchantmentValueEffect)
- void lambda$modifyDamageFilteredValue$8(MutableFloat,int,Entity,EnchantmentValueEffect)
+ void lambda$modifyEntityFilteredValue$6(MutableFloat,int,Entity,EnchantmentValueEffect)
- void lambda$modifyEntityFilteredValue$7(MutableFloat,int,Entity,EnchantmentValueEffect)
+ void lambda$modifyItemFilteredCount$5(MutableFloat,int,ServerLevel,EnchantmentValueEffect)
- void lambda$modifyItemFilteredCount$6(MutableFloat,int,ServerLevel,EnchantmentValueEffect)
+ void lambda$onHitBlock$4(ServerLevel,int,EnchantedItemInUse,Entity,Vec3,EnchantmentEntityEffect)
- void lambda$onHitBlock$5(ServerLevel,int,EnchantedItemInUse,Entity,Vec3,EnchantmentEntityEffect)
+ void lambda$onProjectileSpawned$3(ServerLevel,int,EnchantedItemInUse,Entity,EnchantmentEntityEffect)
- void lambda$onProjectileSpawned$4(ServerLevel,int,EnchantedItemInUse,Entity,EnchantmentEntityEffect)
+ void lambda$runLocationChangedEffects$8(EnchantedItemInUse,LivingEntity,int,EnchantmentLocationBasedEffect)
- void lambda$runLocationChangedEffects$9(EnchantedItemInUse,LivingEntity,int,EnchantmentLocationBasedEffect)
+ void lambda$tick$2(ServerLevel,int,EnchantedItemInUse,Entity,EnchantmentEntityEffect)
- void lambda$tick$3(ServerLevel,int,EnchantedItemInUse,Entity,EnchantmentEntityEffect)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentHelper
</summary>

```diff
+ boolean lambda$filterCompatibleEnchantments$41(EnchantmentInstance,EnchantmentInstance)
- boolean lambda$filterCompatibleEnchantments$42(EnchantmentInstance,EnchantmentInstance)
+ boolean lambda$getAvailableEnchantmentResults$42(ItemStack,boolean,Holder)
- boolean lambda$getAvailableEnchantmentResults$43(ItemStack,boolean,Holder)
+ Holder lambda$enchantItem$39(Holder$Reference)
- Holder lambda$enchantItem$40(Holder$Reference)
+ Stream lambda$enchantItem$40(RegistryAccess)
- Stream lambda$enchantItem$41(RegistryAccess)
- void doLungeEffects(ServerLevel,Entity)
- void lambda$doLungeEffects$10(ServerLevel,Entity,Holder,int,EnchantedItemInUse)
+ void lambda$doPostAttackEffectsWithItemSourceOnBreak$10(ServerLevel,Entity,DamageSource,Holder,int,EnchantedItemInUse)
+ void lambda$doPostAttackEffectsWithItemSourceOnBreak$12(ServerLevel,EnchantedItemInUse,Entity,DamageSource,Holder,int)
- void lambda$doPostAttackEffectsWithItemSourceOnBreak$12(ServerLevel,Entity,DamageSource,Holder,int,EnchantedItemInUse)
- void lambda$doPostAttackEffectsWithItemSourceOnBreak$13(ServerLevel,EnchantedItemInUse,Entity,DamageSource,Holder,int)
+ void lambda$enchantItemFromProvider$44(EnchantmentProvider,ItemStack,RandomSource,DifficultyInstance,ItemEnchantments$Mutable)
- void lambda$enchantItemFromProvider$45(EnchantmentProvider,ItemStack,RandomSource,DifficultyInstance,ItemEnchantments$Mutable)
+ void lambda$forEachModifier$28(Holder,EquipmentSlotGroup,BiConsumer,int,EnchantmentAttributeEffect)
+ void lambda$forEachModifier$29(EquipmentSlotGroup,BiConsumer,Holder,int)
- void lambda$forEachModifier$29(Holder,EquipmentSlotGroup,BiConsumer,int,EnchantmentAttributeEffect)
- void lambda$forEachModifier$30(EquipmentSlotGroup,BiConsumer,Holder,int)
+ void lambda$forEachModifier$30(Holder,EquipmentSlot,BiConsumer,int,EnchantmentAttributeEffect)
+ void lambda$forEachModifier$31(EquipmentSlot,BiConsumer,Holder,int)
- void lambda$forEachModifier$31(Holder,EquipmentSlot,BiConsumer,int,EnchantmentAttributeEffect)
- void lambda$forEachModifier$32(EquipmentSlot,BiConsumer,Holder,int)
+ void lambda$getAvailableEnchantmentResults$43(int,List,Holder)
- void lambda$getAvailableEnchantmentResults$44(int,List,Holder)
+ void lambda$getFishingLuckBonus$32(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
- void lambda$getFishingLuckBonus$33(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
+ void lambda$getFishingTimeReduction$33(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
- void lambda$getFishingTimeReduction$34(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
+ void lambda$getHighestLevel$38(MutableObject,DataComponentType,Holder,int)
- void lambda$getHighestLevel$39(MutableObject,DataComponentType,Holder,int)
+ void lambda$getPiercingCount$20(ServerLevel,ItemStack,MutableFloat,Holder,int)
- void lambda$getPiercingCount$21(ServerLevel,ItemStack,MutableFloat,Holder,int)
+ void lambda$getTridentReturnToOwnerAcceleration$34(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
- void lambda$getTridentReturnToOwnerAcceleration$35(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
+ void lambda$getTridentSpinAttackStrength$36(LivingEntity,MutableFloat,Holder,int)
- void lambda$getTridentSpinAttackStrength$37(LivingEntity,MutableFloat,Holder,int)
+ void lambda$has$37(DataComponentType,MutableBoolean,Holder,int)
- void lambda$has$38(DataComponentType,MutableBoolean,Holder,int)
+ void lambda$modifyCrossbowChargingTime$35(LivingEntity,MutableFloat,Holder,int)
- void lambda$modifyCrossbowChargingTime$36(LivingEntity,MutableFloat,Holder,int)
+ void lambda$modifyDurabilityToRepairFromXp$23(ServerLevel,ItemStack,MutableFloat,Holder,int)
- void lambda$modifyDurabilityToRepairFromXp$24(ServerLevel,ItemStack,MutableFloat,Holder,int)
+ void lambda$onHitBlock$22(ServerLevel,EnchantedItemInUse,Entity,Vec3,BlockState,Holder,int)
- void lambda$onHitBlock$23(ServerLevel,EnchantedItemInUse,Entity,Vec3,BlockState,Holder,int)
+ void lambda$onProjectileSpawned$21(ServerLevel,EnchantedItemInUse,Projectile,Holder,int)
- void lambda$onProjectileSpawned$22(ServerLevel,EnchantedItemInUse,Projectile,Holder,int)
+ void lambda$processEquipmentDropChance$24(LootContext,MutableFloat,int,RandomSource,TargetedConditionalEffect)
- void lambda$processEquipmentDropChance$25(LootContext,MutableFloat,int,RandomSource,TargetedConditionalEffect)
+ void lambda$processEquipmentDropChance$25(ServerLevel,LivingEntity,DamageSource,MutableFloat,RandomSource,Holder,int,EnchantedItemInUse)
+ void lambda$processEquipmentDropChance$26(LootContext,MutableFloat,int,RandomSource,TargetedConditionalEffect)
- void lambda$processEquipmentDropChance$26(ServerLevel,LivingEntity,DamageSource,MutableFloat,RandomSource,Holder,int,EnchantedItemInUse)
- void lambda$processEquipmentDropChance$27(LootContext,MutableFloat,int,RandomSource,TargetedConditionalEffect)
+ void lambda$processEquipmentDropChance$27(ServerLevel,LivingEntity,DamageSource,MutableFloat,RandomSource,Holder,int,EnchantedItemInUse)
- void lambda$processEquipmentDropChance$28(ServerLevel,LivingEntity,DamageSource,MutableFloat,RandomSource,Holder,int,EnchantedItemInUse)
+ void lambda$processProjectileCount$18(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
- void lambda$processProjectileCount$19(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
+ void lambda$processProjectileSpread$19(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
- void lambda$processProjectileSpread$20(ServerLevel,ItemStack,Entity,MutableFloat,Holder,int)
+ void lambda$runLocationChangedEffects$13(ServerLevel,LivingEntity,Holder,int,EnchantedItemInUse)
- void lambda$runLocationChangedEffects$15(ServerLevel,LivingEntity,Holder,int,EnchantedItemInUse)
+ void lambda$stopLocationBasedEffects$15(LivingEntity,Holder,int,EnchantedItemInUse)
- void lambda$stopLocationBasedEffects$17(LivingEntity,Holder,int,EnchantedItemInUse)
+ void lambda$tickEffects$17(ServerLevel,LivingEntity,Holder,int,EnchantedItemInUse)
- void lambda$tickEffects$18(ServerLevel,LivingEntity,Holder,int,EnchantedItemInUse)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.AmbientAdditionsSettings
</summary>

```diff
- boolean equals(Object)
+ double getTickChance()
- double tickChance()
+ Holder getSoundEvent()
- Holder soundEvent()
- int hashCode()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.AmbientParticleSettings
</summary>

```diff
- boolean equals(Object)
- float probability()
- int hashCode()
+ ParticleOptions getOptions()
- ParticleOptions options()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.SavedDataType
</summary>

```diff
- Codec codec()
+ Codec lambda$new$1(Codec,SavedData$Context)
+ Function codec()
+ Function constructor()
+ SavedData lambda$new$0(Supplier,SavedData$Context)
- Supplier constructor()
+ void <init>(String,Function,Function,DataFixTypes)
```

</details>
<details>
<summary>
net.minecraft.world.phys.Vec3
</summary>

```diff
- Vec2 rotation()
- Vec3 addLocalCoordinates(Vec3)
- Vec3 applyLocalCoordinatesToRotation(Vec2,Vec3)
- Vec3 offsetRandomXZ(RandomSource,float)
+ void <init>(Vector3f)
- void <init>(Vector3fc)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- DoubleList flipAxisIfNeeded(DoubleList,boolean,double,double)
+ DoubleList makeAxis(DoubleList,boolean,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.scores.ScoreboardSaveData
</summary>

```diff
- ScoreboardSaveData$Packed getData()
+ ScoreboardSaveData$Packed pack()
- void <clinit>()
- void <init>()
+ void <init>(Scoreboard)
- void <init>(ScoreboardSaveData$Packed)
+ void lambda$loadFrom$0(DisplaySlot,String)
+ void loadFrom(ScoreboardSaveData$Packed)
- void setData(ScoreboardSaveData$Packed)
```

</details>
</details>
<hr/>