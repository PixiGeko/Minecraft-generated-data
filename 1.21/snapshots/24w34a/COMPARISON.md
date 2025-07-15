## Comparison with [24w33a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w33a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Datapacks](#datapacks)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>DataPack version</td><td><pre>49</pre></td><td><pre>50</pre></td></tr><tr><td>ResourcePack version</td><td><pre>35</pre></td><td><pre>36</pre></td></tr><tr><td>World version</td><td><pre>4058</pre></td><td><pre>4060</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742029</pre></td><td><pre>1073742030</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ consume_effect_type.txt
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:consumable
+ minecraft:use_cooldown
+ minecraft:use_remainder
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
+ universal_tags/consume_effect_type.json
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:consumable
+ minecraft:use_cooldown
+ minecraft:use_remainder
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
baked_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
beetroot_soup
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:bowl"
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 6,
  "saturation": 7.2000003,
  "using_converts_to": {
    "id": "minecraft:bowl"
  }
}</pre></td><td><pre>{
  "nutrition": 6,
  "saturation": 7.2000003
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
bread
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 12
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 12
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 12
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chainmail_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 12
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "duration": 600,
          "id": "minecraft:hunger",
          "show_icon": true
        }
      ],
      "probability": 0.3
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "effects": [
    {
      "effect": {
        "duration": 600,
        "id": "minecraft:hunger",
        "show_icon": true
      },
      "probability": 0.3
    }
  ],
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
chorus_fruit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:teleport_randomly"
    }
  ]
}</pre></td></tr><tr><td>minecraft:use_cooldown</td><td><pre>/</pre></td><td><pre>{
  "seconds": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_beef
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_chicken
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_cod
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cooked_salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cookie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 10
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
dried_kelp
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "consume_seconds": 0.8
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "eat_seconds": 0.8,
  "nutrition": 1,
  "saturation": 0.6
}</pre></td><td><pre>{
  "nutrition": 1,
  "saturation": 0.6
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
enchanted_golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "amplifier": 1,
          "duration": 400,
          "id": "minecraft:regeneration",
          "show_icon": true
        },
        {
          "duration": 6000,
          "id": "minecraft:resistance",
          "show_icon": true
        },
        {
          "duration": 6000,
          "id": "minecraft:fire_resistance",
          "show_icon": true
        },
        {
          "amplifier": 3,
          "duration": 2400,
          "id": "minecraft:absorption",
          "show_icon": true
        }
      ]
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "can_always_eat": true,
  "effects": [
    {
      "effect": {
        "amplifier": 1,
        "duration": 400,
        "id": "minecraft:regeneration",
        "show_icon": true
      }
    },
    {
      "effect": {
        "duration": 6000,
        "id": "minecraft:resistance",
        "show_icon": true
      }
    },
    {
      "effect": {
        "duration": 6000,
        "id": "minecraft:fire_resistance",
        "show_icon": true
      }
    },
    {
      "effect": {
        "amplifier": 3,
        "duration": 2400,
        "id": "minecraft:absorption",
        "show_icon": true
      }
    }
  ],
  "nutrition": 4,
  "saturation": 9.6
}</pre></td><td><pre>{
  "can_always_eat": true,
  "nutrition": 4,
  "saturation": 9.6
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
glow_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_apple
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "amplifier": 1,
          "duration": 100,
          "id": "minecraft:regeneration",
          "show_icon": true
        },
        {
          "duration": 2400,
          "id": "minecraft:absorption",
          "show_icon": true
        }
      ]
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "can_always_eat": true,
  "effects": [
    {
      "effect": {
        "amplifier": 1,
        "duration": 100,
        "id": "minecraft:regeneration",
        "show_icon": true
      }
    },
    {
      "effect": {
        "duration": 2400,
        "id": "minecraft:absorption",
        "show_icon": true
      }
    }
  ],
  "nutrition": 4,
  "saturation": 9.6
}</pre></td><td><pre>{
  "can_always_eat": true,
  "nutrition": 4,
  "saturation": 9.6
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 25
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_carrot
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 25
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 25
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 25
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
honey_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "animation": "drink",
  "consume_seconds": 2,
  "has_consume_particles": false,
  "on_consume_effects": [
    {
      "type": "minecraft:remove_effects",
      "effects": "minecraft:poison"
    }
  ],
  "sound": "minecraft:item.honey_bottle.drink"
}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:glass_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 9
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 9
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 9
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 9
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
melon_slice
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
milk_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "animation": "drink",
  "has_consume_particles": false,
  "on_consume_effects": [
    {
      "type": "minecraft:clear_all_effects"
    }
  ],
  "sound": "minecraft:entity.generic.drink"
}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:bucket"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mushroom_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:bowl"
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 6,
  "saturation": 7.2000003,
  "using_converts_to": {
    "id": "minecraft:bowl"
  }
}</pre></td><td><pre>{
  "nutrition": 6,
  "saturation": 7.2000003
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
mutton
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 15
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
ominous_bottle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "animation": "drink",
  "has_consume_particles": false,
  "on_consume_effects": [
    {
      "type": "minecraft:play_sound",
      "sound": "minecraft:item.ominous_bottle.dispose"
    }
  ],
  "sound": "minecraft:entity.generic.drink"
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 1,
  "saturation": 0.2
}</pre></td><td><pre>/</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
poisonous_potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "duration": 100,
          "id": "minecraft:poison",
          "show_icon": true
        }
      ],
      "probability": 0.6
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "effects": [
    {
      "effect": {
        "duration": 100,
        "id": "minecraft:poison",
        "show_icon": true
      },
      "probability": 0.6
    }
  ],
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
porkchop
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potato
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
potion
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "animation": "drink",
  "has_consume_particles": false,
  "sound": "minecraft:entity.generic.drink"
}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:glass_bottle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "amplifier": 1,
          "duration": 1200,
          "id": "minecraft:poison",
          "show_icon": true
        },
        {
          "amplifier": 2,
          "duration": 300,
          "id": "minecraft:hunger",
          "show_icon": true
        },
        {
          "duration": 300,
          "id": "minecraft:nausea",
          "show_icon": true
        }
      ]
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "effects": [
    {
      "effect": {
        "amplifier": 1,
        "duration": 1200,
        "id": "minecraft:poison",
        "show_icon": true
      }
    },
    {
      "effect": {
        "amplifier": 2,
        "duration": 300,
        "id": "minecraft:hunger",
        "show_icon": true
      }
    },
    {
      "effect": {
        "duration": 300,
        "id": "minecraft:nausea",
        "show_icon": true
      }
    }
  ],
  "nutrition": 1,
  "saturation": 0.2
}</pre></td><td><pre>{
  "nutrition": 1,
  "saturation": 0.2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pumpkin_pie
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rabbit_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:bowl"
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "nutrition": 10,
  "saturation": 12,
  "using_converts_to": {
    "id": "minecraft:bowl"
  }
}</pre></td><td><pre>{
  "nutrition": 10,
  "saturation": 12
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
rotten_flesh
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "duration": 600,
          "id": "minecraft:hunger",
          "show_icon": true
        }
      ],
      "probability": 0.8
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "effects": [
    {
      "effect": {
        "duration": 600,
        "id": "minecraft:hunger",
        "show_icon": true
      },
      "probability": 0.8
    }
  ],
  "nutrition": 4,
  "saturation": 0.8
}</pre></td><td><pre>{
  "nutrition": 4,
  "saturation": 0.8
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
spider_eye
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{
  "on_consume_effects": [
    {
      "type": "minecraft:apply_effects",
      "effects": [
        {
          "duration": 100,
          "id": "minecraft:poison",
          "show_icon": true
        }
      ]
    }
  ]
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "effects": [
    {
      "effect": {
        "duration": 100,
        "id": "minecraft:poison",
        "show_icon": true
      }
    }
  ],
  "nutrition": 2,
  "saturation": 3.2
}</pre></td><td><pre>{
  "nutrition": 2,
  "saturation": 3.2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
suspicious_stew
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:use_remainder</td><td><pre>/</pre></td><td><pre>{
  "count": 1,
  "id": "minecraft:bowl"
}</pre></td></tr><tr><td>minecraft:food</td><td><pre>{
  "can_always_eat": true,
  "nutrition": 6,
  "saturation": 7.2000003,
  "using_converts_to": {
    "id": "minecraft:bowl"
  }
}</pre></td><td><pre>{
  "can_always_eat": true,
  "nutrition": 6,
  "saturation": 7.2000003
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
sweet_berries
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">24w33a</th><th>24w34a</th></tr><tr><td>minecraft:enchantable</td><td><pre>/</pre></td><td><pre>{
  "value": 9
}</pre></td></tr></table>
<br/>
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
+ minecraft:consume_effect_type
```

</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/post_effect/blur.json
+ minecraft/post_effect/creeper.json
+ minecraft/post_effect/entity_outline.json
+ minecraft/post_effect/invert.json
+ minecraft/post_effect/spider.json
+ minecraft/post_effect/transparency.json
+ minecraft/shaders/core/entity.fsh
+ minecraft/shaders/core/entity.vsh
+ minecraft/shaders/core/glint.fsh
+ minecraft/shaders/core/glint.vsh
+ minecraft/shaders/core/gui.fsh
+ minecraft/shaders/core/gui.vsh
- minecraft/shaders/core/rendertype_armor_cutout_no_cull.fsh
- minecraft/shaders/core/rendertype_armor_cutout_no_cull.vsh
- minecraft/shaders/core/rendertype_armor_entity_glint.fsh
- minecraft/shaders/core/rendertype_armor_entity_glint.vsh
- minecraft/shaders/core/rendertype_breeze_wind.fsh
- minecraft/shaders/core/rendertype_breeze_wind.vsh
- minecraft/shaders/core/rendertype_cutout_mipped.fsh
- minecraft/shaders/core/rendertype_cutout_mipped.vsh
- minecraft/shaders/core/rendertype_cutout.fsh
- minecraft/shaders/core/rendertype_cutout.vsh
- minecraft/shaders/core/rendertype_energy_swirl.fsh
- minecraft/shaders/core/rendertype_energy_swirl.vsh
- minecraft/shaders/core/rendertype_entity_cutout_no_cull_z_offset.fsh
- minecraft/shaders/core/rendertype_entity_cutout_no_cull_z_offset.vsh
- minecraft/shaders/core/rendertype_entity_cutout_no_cull.fsh
- minecraft/shaders/core/rendertype_entity_cutout_no_cull.vsh
- minecraft/shaders/core/rendertype_entity_cutout.fsh
- minecraft/shaders/core/rendertype_entity_cutout.vsh
- minecraft/shaders/core/rendertype_entity_glint_direct.fsh
- minecraft/shaders/core/rendertype_entity_glint_direct.json
- minecraft/shaders/core/rendertype_entity_glint_direct.vsh
- minecraft/shaders/core/rendertype_entity_glint.fsh
- minecraft/shaders/core/rendertype_entity_glint.vsh
- minecraft/shaders/core/rendertype_entity_no_outline.fsh
- minecraft/shaders/core/rendertype_entity_no_outline.vsh
- minecraft/shaders/core/rendertype_entity_smooth_cutout.fsh
- minecraft/shaders/core/rendertype_entity_smooth_cutout.vsh
- minecraft/shaders/core/rendertype_entity_solid.fsh
- minecraft/shaders/core/rendertype_entity_solid.vsh
- minecraft/shaders/core/rendertype_entity_translucent_cull.fsh
- minecraft/shaders/core/rendertype_entity_translucent_cull.json
- minecraft/shaders/core/rendertype_entity_translucent_cull.vsh
- minecraft/shaders/core/rendertype_entity_translucent_emissive.fsh
- minecraft/shaders/core/rendertype_entity_translucent_emissive.vsh
- minecraft/shaders/core/rendertype_entity_translucent.fsh
- minecraft/shaders/core/rendertype_entity_translucent.vsh
- minecraft/shaders/core/rendertype_eyes.fsh
- minecraft/shaders/core/rendertype_eyes.vsh
- minecraft/shaders/core/rendertype_glint_translucent.fsh
- minecraft/shaders/core/rendertype_glint_translucent.vsh
- minecraft/shaders/core/rendertype_glint.fsh
- minecraft/shaders/core/rendertype_glint.vsh
- minecraft/shaders/core/rendertype_gui_ghost_recipe_overlay.fsh
- minecraft/shaders/core/rendertype_gui_ghost_recipe_overlay.vsh
- minecraft/shaders/core/rendertype_gui_overlay.fsh
- minecraft/shaders/core/rendertype_gui_overlay.vsh
- minecraft/shaders/core/rendertype_gui_text_highlight.fsh
- minecraft/shaders/core/rendertype_gui_text_highlight.vsh
- minecraft/shaders/core/rendertype_gui.fsh
- minecraft/shaders/core/rendertype_gui.vsh
- minecraft/shaders/core/rendertype_solid.fsh
- minecraft/shaders/core/rendertype_solid.vsh
- minecraft/shaders/core/rendertype_translucent.fsh
- minecraft/shaders/core/rendertype_translucent.vsh
- minecraft/shaders/core/rendertype_tripwire.fsh
- minecraft/shaders/core/rendertype_tripwire.vsh
+ minecraft/shaders/core/terrain.fsh
+ minecraft/shaders/core/terrain.vsh
+ minecraft/shaders/post/bits.fsh
+ minecraft/shaders/post/bits.json
+ minecraft/shaders/post/blit.fsh
+ minecraft/shaders/post/blit.json
+ minecraft/shaders/post/blit.vsh
- minecraft/shaders/post/blur.json
+ minecraft/shaders/post/blur.vsh
+ minecraft/shaders/post/box_blur.fsh
+ minecraft/shaders/post/box_blur.json
+ minecraft/shaders/post/color_convolve.fsh
+ minecraft/shaders/post/color_convolve.json
- minecraft/shaders/post/creeper.json
+ minecraft/shaders/post/entity_outline_box_blur.fsh
+ minecraft/shaders/post/entity_outline_box_blur.json
+ minecraft/shaders/post/entity_sobel.fsh
+ minecraft/shaders/post/invert.fsh
+ minecraft/shaders/post/invert.vsh
+ minecraft/shaders/post/rotscale.vsh
+ minecraft/shaders/post/screenquad.vsh
+ minecraft/shaders/post/sobel.vsh
+ minecraft/shaders/post/spiderclip.fsh
+ minecraft/shaders/post/transparency.fsh
- minecraft/shaders/program/bits.fsh
- minecraft/shaders/program/bits.json
- minecraft/shaders/program/blit.fsh
- minecraft/shaders/program/blit.json
- minecraft/shaders/program/blit.vsh
- minecraft/shaders/program/blur.vsh
- minecraft/shaders/program/box_blur.fsh
- minecraft/shaders/program/box_blur.json
- minecraft/shaders/program/color_convolve.fsh
- minecraft/shaders/program/color_convolve.json
- minecraft/shaders/program/entity_outline_box_blur.fsh
- minecraft/shaders/program/entity_outline_box_blur.json
- minecraft/shaders/program/entity_outline.json
- minecraft/shaders/program/entity_sobel.fsh
- minecraft/shaders/program/invert.fsh
- minecraft/shaders/program/invert.json
- minecraft/shaders/program/invert.vsh
- minecraft/shaders/program/rotscale.vsh
- minecraft/shaders/program/screenquad.vsh
- minecraft/shaders/program/sobel.vsh
- minecraft/shaders/program/spider.json
- minecraft/shaders/program/spiderclip.fsh
- minecraft/shaders/program/transparency.fsh
- minecraft/shaders/program/transparency.json
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
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
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
- XXX.ai.behavior.LongJumpUtil
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.OneShot
+ XXX.ai.behavior.package-info
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
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
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
+ XXX.ai.goal.package-info
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
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
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
- XXX.animal.horse.AbstractHorse$1
+ XXX.animal.horse.AbstractHorse$2
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
- XXX.boss.enderdragon.DragonFlightHistory
+ XXX.boss.enderdragon.DragonFlightHistory$Sample
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
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
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
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
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
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
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.DecoratedPotFieldRenameFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingFieldsRenameFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntityShulkerRotationFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.package-info
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
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
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
+ XXX.datafix.schemas.V3816
- XXX.datafix.schemas.V3818
+ XXX.datafix.schemas.V3818_3
- XXX.datafix.schemas.V3818_4
+ XXX.datafix.schemas.V3818_5
- XXX.datafix.schemas.V3825
+ XXX.datafix.schemas.V3938
- XXX.datafix.schemas.V4059
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
+ XXX.entity.ai.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
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
- XXX.entity.animal.Fox$Variant
+ XXX.entity.animal.FrogVariant
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
- XXX.entity.animal.Sheep
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
- XXX.entity.animal.Wolf$WolfPackData
+ XXX.entity.animal.WolfVariant
- XXX.entity.animal.WolfVariants
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
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
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.Bogged
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
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
- XXX.entity.player.package-info
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
- XXX.entity.player.StackedContents$IngredientInfo
+ XXX.entity.player.StackedContents$Output
- XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.player.StackedItemContents
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
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
- XXX.entity.projectile.package-info
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
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
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
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.component.Consumable
- XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.Consumables
+ XXX.item.component.CustomData
- XXX.item.component.CustomModelData
+ XXX.item.component.DebugStickState
- XXX.item.component.DyedItemColor
+ XXX.item.component.FireworkExplosion
- XXX.item.component.FireworkExplosion$Shape
+ XXX.item.component.Fireworks
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Entry
- XXX.item.component.ItemContainerContents
+ XXX.item.component.ItemContainerContents$Slot
- XXX.item.component.ItemLore
+ XXX.item.component.LodestoneTracker
- XXX.item.component.MapDecorations
+ XXX.item.component.MapDecorations$Entry
- XXX.item.component.MapItemColor
+ XXX.item.component.MapPostProcessing
- XXX.item.component.OminousBottleAmplifier
- XXX.item.component.UseRemainder
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.ChunkRegionIoEvent
- XXX.jfr.event.ChunkRegionIoEvent$Fields
+ XXX.jfr.event.ChunkRegionReadEvent
- XXX.jfr.event.ChunkRegionWriteEvent
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
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.IoSummary
+ XXX.jfr.stats.IoSummary$CountAndSize
- XXX.jfr.stats.package-info
- XXX.jfr.stats.PacketIdentification
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metrics.profiling.ActiveMetricsRecorder
+ XXX.metrics.profiling.InactiveMetricsRecorder
- XXX.metrics.profiling.MetricsRecorder
+ XXX.metrics.profiling.package-info
+ XXX.metrics.profiling.ProfilerSamplerAdapter
- XXX.metrics.profiling.ServerMetricsSamplersProvider
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$1
- XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- XXX.metrics.storage.MetricsPersister
- XXX.metrics.storage.package-info
+ XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
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
- XXX.minecraft.server.ServerScoreboard$Method
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
+ XXX.minecraft.tags.EnchantmentTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FlatLevelGeneratorPresetTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.InstrumentTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
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
- XXX.minecraft.tags.TagLoader$EntryWithSource
+ XXX.minecraft.tags.TagLoader$LoadResult
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer
+ XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.ARGB
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
- XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
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
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
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
+ XXX.minecraft.world.InteractionResult$Fail
- XXX.minecraft.world.InteractionResult$ItemContext
+ XXX.minecraft.world.InteractionResult$Pass
- XXX.minecraft.world.InteractionResult$Success
+ XXX.minecraft.world.InteractionResult$SwingSource
- XXX.minecraft.world.InteractionResult$TryEmptyHandInteraction
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
+ XXX.minecraft.world.RandomizableContainer
- XXX.minecraft.world.RandomSequence
+ XXX.minecraft.world.RandomSequences
- XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.TickRateManager
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
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
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
- XXX.packrat.commands.Grammar
+ XXX.packrat.commands.package-info
+ XXX.packrat.commands.ResourceLocationParseRule
- XXX.packrat.commands.ResourceLookupRule
+ XXX.packrat.commands.ResourceSuggestion
- XXX.packrat.commands.StringReaderParserState
+ XXX.packrat.commands.StringReaderTerms
- XXX.packrat.commands.StringReaderTerms$TerminalCharacter
+ XXX.packrat.commands.StringReaderTerms$TerminalWord
- XXX.packrat.commands.TagParseRule
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
- XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.MetadataSectionType$1
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
+ XXX.parsing.packrat.Atom
- XXX.parsing.packrat.Control
+ XXX.parsing.packrat.Dictionary
- XXX.parsing.packrat.ErrorCollector
+ XXX.parsing.packrat.ErrorCollector$LongestOnly
- XXX.parsing.packrat.ErrorEntry
- XXX.parsing.packrat.package-info
+ XXX.parsing.packrat.ParseState
- XXX.parsing.packrat.ParseState$CacheEntry
+ XXX.parsing.packrat.ParseState$CacheKey
- XXX.parsing.packrat.Rule
+ XXX.parsing.packrat.Rule$RuleAction
- XXX.parsing.packrat.Rule$SimpleRuleAction
+ XXX.parsing.packrat.Rule$WrappedTerm
- XXX.parsing.packrat.Scope
+ XXX.parsing.packrat.SuggestionSupplier
- XXX.parsing.packrat.Term
+ XXX.parsing.packrat.Term$1
- XXX.parsing.packrat.Term$2
+ XXX.parsing.packrat.Term$Alternative
- XXX.parsing.packrat.Term$Marker
+ XXX.parsing.packrat.Term$Maybe
- XXX.parsing.packrat.Term$Reference
+ XXX.parsing.packrat.Term$Sequence
- XXX.phys.shapes.MinecartCollisionContext
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
+ XXX.profiling.metrics.MetricCategory
- XXX.profiling.metrics.MetricSampler
+ XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metrics.MetricSampler$SamplerResult
+ XXX.profiling.metrics.MetricSampler$ThresholdTest
- XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ XXX.profiling.metrics.MetricsRegistry
- XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ XXX.profiling.metrics.MetricsSamplerProvider
+ XXX.profiling.metrics.package-info
- XXX.profiling.metrics.ProfilerMeasured
+ XXX.projectile.windcharge.AbstractWindCharge
- XXX.projectile.windcharge.BreezeWindCharge
- XXX.projectile.windcharge.package-info
+ XXX.projectile.windcharge.WindCharge
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
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
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$CommandFunction
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
- XXX.server.commands.ExecuteCommand$CommandGetter
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- XXX.server.commands.ExecuteCommand$IntBiPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
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
+ XXX.server.commands.package-info
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
- XXX.server.commands.TeleportCommand$LookAtEntity
+ XXX.server.commands.TeleportCommand$LookAtPosition
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TickCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TransferCommand
+ XXX.server.commands.TriggerCommand
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
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
+ XXX.server.level.package-info
- XXX.server.level.ParticleStatus
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$ChunkAndHolder
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$1
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$RespawnPosAngle
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
+ XXX.util.datafix.ComponentDataFixUtils
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.FixWolfHealth
- XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
- XXX.util.debugchart.package-info
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
+ XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.random.package-info
- XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.SimpleWeightedRandomList$Builder
- XXX.util.random.Weight
+ XXX.util.random.WeightedEntry
- XXX.util.random.WeightedEntry$IntrusiveBase
+ XXX.util.random.WeightedEntry$Wrapper
- XXX.util.random.WeightedRandom
+ XXX.util.random.WeightedRandomList
+ XXX.util.thread.BlockableEventLoop
- XXX.util.thread.NamedThreadFactory
+ XXX.util.thread.package-info
+ XXX.util.thread.ProcessorHandle
- XXX.util.thread.ProcessorHandle$1
+ XXX.util.thread.ProcessorMailbox
- XXX.util.thread.ReentrantBlockableEventLoop
+ XXX.util.thread.StrictQueue
- XXX.util.thread.StrictQueue$FixedPriorityQueue
+ XXX.util.thread.StrictQueue$IntRunnable
- XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.BiasedToBottomInt
+ XXX.util.valueproviders.ClampedInt
- XXX.util.valueproviders.ClampedNormalFloat
+ XXX.util.valueproviders.ClampedNormalInt
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
- XXX.util.valueproviders.MultipliedFloats
- XXX.util.valueproviders.package-info
+ XXX.util.valueproviders.SampledFloat
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.valueproviders.WeightedListInt
+ XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
+ XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
- XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
+ XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
- XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
+ XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
- XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
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
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffect$AttributeTemplate
- XXX.world.effect.MobEffectCategory
+ XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffectInstance$BlendState
+ XXX.world.effect.MobEffectInstance$Details
+ XXX.world.effect.MobEffects
- XXX.world.effect.MobEffectUtil
- XXX.world.effect.OozingMobEffect
+ XXX.world.effect.OozingMobEffect$NearbySlimes
+ XXX.world.effect.package-info
- XXX.world.effect.PoisonMobEffect
+ XXX.world.effect.RaidOmenMobEffect
- XXX.world.effect.RegenerationMobEffect
+ XXX.world.effect.SaturationMobEffect
- XXX.world.effect.WeavingMobEffect
+ XXX.world.effect.WindChargedMobEffect
- XXX.world.effect.WitherMobEffect
- XXX.world.entity.AgeableMob
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
- XXX.world.entity.AnimationState
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Attackable
+ XXX.world.entity.Crackiness
- XXX.world.entity.Crackiness$Level
+ XXX.world.entity.Display
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$BlockDisplay$BlockRenderState
+ XXX.world.entity.Display$ColorInterpolator
- XXX.world.entity.Display$FloatInterpolator
+ XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$IntInterpolator
+ XXX.world.entity.Display$ItemDisplay
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
- XXX.world.entity.ElytraAnimationState
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityAttachment
+ XXX.world.entity.EntityAttachment$Fallback
- XXX.world.entity.EntityAttachments
+ XXX.world.entity.EntityAttachments$Builder
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntitySpawnReason
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.EquipmentSlotGroup
- XXX.world.entity.EquipmentSlotGroup$1
+ XXX.world.entity.EquipmentTable
- XXX.world.entity.EquipmentUser
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
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
+ XXX.world.entity.MobCategory
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OminousItemSpawner
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.package-info
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.PortalProcessor
- XXX.world.entity.Pose
+ XXX.world.entity.RelativeMovement
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
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
+ XXX.world.entity.VariantHolder
- XXX.world.entity.WalkAnimationState
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.ArmorSlot
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
- XXX.world.inventory.CrafterMenu
+ XXX.world.inventory.CrafterSlot
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
+ XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
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
+ XXX.world.item.AnimalArmorItem
- XXX.world.item.AnimalArmorItem$BodyType
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterial$Layer
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
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
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
- XXX.world.item.ItemNameBlockItem
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.core.component.DataComponents +3M | +3P
```
```
XXX.entity.vehicle.NewMinecartBehavior +6M -1M | +1P -1P
```
```
XXX.world.food.FoodProperties$Builder -3M | -3P
```
```
XXX.world.item.CrossbowItem +1M -1M
```
```
XXX.world.item.ServerItemCooldowns +2M -2M
```
```
XXX.world.item.ShieldItem +1M -1M
```
```
XXX.world.item.SpyglassItem +1M -1M
```
```
XXX.item.alchemy.PotionContents +4M -1M
```
```
XXX.world.level.EmptyBlockAndTintGetter +1M -1M
```
```
XXX.world.level.LevelHeightAccessor$1 +1M -1M | +1P -1P
```
```
XXX.world.level.PathNavigationRegion +1M -1M
```
```
XXX.level.block.Block +1P
```
```
XXX.level.block.RedStoneWireBlock +1M -1M
```
```
XXX.state.properties.RailShape +1M -1M
```
```
XXX.level.chunk.ChunkAccess +1M -1M
```
```
XXX.level.levelgen.BelowZeroRetrogen$1 +1M -1M
```
```
XXX.level.lighting.LevelLightEngine +1M -1M
```
```
XXX.level.redstone.DefaultRedstoneWireEvaluator +1M -1M
```
```
XXX.level.redstone.ExperimentalRedstoneWireEvaluator +1M -1M
```
```
XXX.level.redstone.RedstoneWireEvaluator +1P -1P
```
```
XXX.phys.shapes.EntityCollisionContext +1M
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponents
</summary>

```diff
- DataComponentType$Builder lambda$static$59(DataComponentType$Builder)
- DataComponentType$Builder lambda$static$60(DataComponentType$Builder)
- DataComponentType$Builder lambda$static$61(DataComponentType$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.NewMinecartBehavior
</summary>

```diff
- boolean pickupEntities(AABB)
- boolean pushAndPickupEntities()
- boolean pushEntities(AABB)
- boolean restAtVShape(RailShape,RailShape)
- void adjustToRails(BlockPos,BlockState,boolean)
+ void adjustToRails(BlockPos,BlockState)
- void setRotation(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.food.FoodProperties$Builder
</summary>

```diff
+ FoodProperties$Builder effect(MobEffectInstance,float)
+ FoodProperties$Builder fast()
+ FoodProperties$Builder usingConvertsTo(ItemLike)
```

</details>
<details>
<summary>
net.minecraft.world.item.CrossbowItem
</summary>

```diff
- ItemUseAnimation getUseAnimation(ItemStack)
+ UseAnim getUseAnimation(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ServerItemCooldowns
</summary>

```diff
+ void onCooldownEnded(Item)
- void onCooldownEnded(ResourceLocation)
+ void onCooldownStarted(Item,int)
- void onCooldownStarted(ResourceLocation,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.ShieldItem
</summary>

```diff
- ItemUseAnimation getUseAnimation(ItemStack)
+ UseAnim getUseAnimation(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.SpyglassItem
</summary>

```diff
- ItemUseAnimation getUseAnimation(ItemStack)
+ UseAnim getUseAnimation(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.PotionContents
</summary>

```diff
- void applyToLivingEntity(LivingEntity)
+ void lambda$addPotionTooltip$1(List,Holder,AttributeModifier)
- void lambda$addPotionTooltip$2(List,Holder,AttributeModifier)
- void lambda$applyToLivingEntity$1(Player,LivingEntity,MobEffectInstance)
- void onConsume(Level,LivingEntity,ItemStack,Consumable)
```

</details>
<details>
<summary>
net.minecraft.world.level.EmptyBlockAndTintGetter
</summary>

```diff
+ int getMinBuildHeight()
- int getMinY()
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelHeightAccessor$1
</summary>

```diff
+ int getMinBuildHeight()
- int getMinY()
```

</details>
<details>
<summary>
net.minecraft.world.level.PathNavigationRegion
</summary>

```diff
+ int getMinBuildHeight()
- int getMinY()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
- void updatePowerStrength(Level,BlockPos,BlockState,Orientation,boolean)
+ void updatePowerStrength(Level,BlockPos,BlockState,Orientation)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.RailShape
</summary>

```diff
+ boolean isAscending()
- boolean isSlope()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ int getMinBuildHeight()
- int getMinY()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
</summary>

```diff
+ int getMinBuildHeight()
- int getMinY()
```

</details>
<details>
<summary>
net.minecraft.world.level.lighting.LevelLightEngine
</summary>

```diff
- boolean lightOnInColumn(long)
+ boolean lightOnInSection(SectionPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.redstone.DefaultRedstoneWireEvaluator
</summary>

```diff
- void updatePowerStrength(Level,BlockPos,BlockState,Orientation,boolean)
+ void updatePowerStrength(Level,BlockPos,BlockState,Orientation)
```

</details>
<details>
<summary>
net.minecraft.world.level.redstone.ExperimentalRedstoneWireEvaluator
</summary>

```diff
- void updatePowerStrength(Level,BlockPos,BlockState,Orientation,boolean)
+ void updatePowerStrength(Level,BlockPos,BlockState,Orientation)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
- VoxelShape getCollisionShape(BlockState,CollisionGetter,BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.advancements.packs.package-info
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
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
- XXX.blaze3d.shaders.CompiledShader$Type
+ XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.EffectProgram$1
+ XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.ProgramManager
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
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntity$1
- XXX.block.entity.BlockEntity$ComponentHelper
+ XXX.block.entity.BlockEntity$DataComponentInput
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
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
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
- XXX.block.entity.TrialSpawnerBlockEntity
+ XXX.block.grower.package-info
- XXX.block.grower.TreeGrower
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
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
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
+ XXX.block.model.MultiVariant
- XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
+ XXX.block.model.UnbakedBlockStateModel
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.block.model.VariantSelector
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
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.DataSource$Type
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
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
- XXX.client.renderer.CompiledShaderProgram
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogParameters
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$BlindnessFogFunction
- XXX.client.renderer.FogRenderer$DarknessFogFunction
+ XXX.client.renderer.FogRenderer$FogData
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.FogRenderer$MobEffectFogFunction
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.GameRenderer$1
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelEventHandler
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$1
+ XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.LevelTargetBundle
+ XXX.client.renderer.LightTexture
- XXX.client.renderer.MapRenderer
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.Octree$AxisSorting
- XXX.client.renderer.Octree$Leaf
- XXX.client.renderer.Octree$OctreeVisitor
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
+ XXX.client.renderer.PanoramaRenderer
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostChain$TargetBundle
- XXX.client.renderer.PostChain$TargetBundle$1
+ XXX.client.renderer.PostChainConfig
- XXX.client.renderer.PostChainConfig$FixedSizedTarget
+ XXX.client.renderer.PostChainConfig$FullScreenTarget
- XXX.client.renderer.PostChainConfig$Input
+ XXX.client.renderer.PostChainConfig$InternalTarget
- XXX.client.renderer.PostChainConfig$Pass
+ XXX.client.renderer.PostChainConfig$TargetInput
- XXX.client.renderer.PostChainConfig$TextureInput
+ XXX.client.renderer.PostChainConfig$Uniform
- XXX.client.renderer.PostPass
+ XXX.client.renderer.PostPass$Input
- XXX.client.renderer.PostPass$TargetInput
+ XXX.client.renderer.PostPass$TextureInput
- XXX.client.renderer.Rect2i
+ XXX.client.renderer.RenderBuffers
- XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$ColorLogicStateShard
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
- XXX.client.renderer.SectionBufferBuilderPack
+ XXX.client.renderer.SectionBufferBuilderPool
- XXX.client.renderer.SectionOcclusionGraph
+ XXX.client.renderer.SectionOcclusionGraph$GraphEvents
- XXX.client.renderer.SectionOcclusionGraph$GraphState
+ XXX.client.renderer.SectionOcclusionGraph$GraphStorage
- XXX.client.renderer.SectionOcclusionGraph$Node
+ XXX.client.renderer.SectionOcclusionGraph$SectionToNodeMap
- XXX.client.renderer.ShaderDefines
+ XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.ShaderManager
- XXX.client.renderer.ShaderManager$CompilationException
- XXX.client.renderer.ShaderManager$ShaderCompilationKey
- XXX.client.renderer.ShaderProgram
- XXX.client.renderer.ShaderProgramConfig$Sampler
- XXX.client.renderer.ShapeRenderer
+ XXX.client.renderer.ShapeRenderer$1
- XXX.client.renderer.Sheets
+ XXX.client.renderer.Sheets$1
- XXX.client.renderer.SkyRenderer
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.client.renderer.WeatherEffectRenderer
+ XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
- XXX.client.renderer.WorldBorderRenderer
+ XXX.client.resources.ClientPackSource
- XXX.client.resources.DefaultPlayerSkin
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
- XXX.client.searchtree.FullTextSearchTree
+ XXX.client.searchtree.IdSearchTree
- XXX.client.searchtree.IntersectionIterator
+ XXX.client.searchtree.MergingUniqueIterator
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.ResourceLocationSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree$1
- XXX.client.searchtree.ResourceLocationSearchTree$2
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
+ XXX.client.sounds.ChunkedSampleByteBuf
- XXX.client.sounds.FiniteAudioStream
+ XXX.client.sounds.FloatSampleSource
- XXX.client.sounds.JOrbisAudioStream
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
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.CauldronInteraction$InteractionMap
- XXX.core.cauldron.package-info
+ XXX.core.component.DataComponentHolder
- XXX.core.component.DataComponentMap
+ XXX.core.component.DataComponentMap$1
- XXX.core.component.DataComponentMap$2
+ XXX.core.component.DataComponentMap$3
- XXX.core.component.DataComponentMap$Builder
+ XXX.core.component.DataComponentMap$Builder$SimpleMap
- XXX.core.component.DataComponentPatch
+ XXX.core.component.DataComponentPatch$1
- XXX.core.component.DataComponentPatch$Builder
+ XXX.core.component.DataComponentPatch$PatchKey
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
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$9
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
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.ScalableParticleOptionsBase
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.ShriekParticleOption
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.VibrationParticleOption
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
- XXX.data.info.DatapackStructureReport
+ XXX.data.info.DatapackStructureReport$CustomPackEntry
- XXX.data.info.DatapackStructureReport$Entry
+ XXX.data.info.DatapackStructureReport$Format
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
- XXX.data.tags.CatVariantTagsProvider
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
- XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1CombinedData
- XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.tags.TagsProvider$TagLookup
- XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
+ XXX.data.tags.TradeRebalanceStructureTagsProvider
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
- XXX.data.worldgen.TrailRuinsStructurePools
+ XXX.data.worldgen.TrialChambersStructurePools
- XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
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
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackComponentRemainderFix
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LegacyDragonFightFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LodestoneCompassComponentFix
+ XXX.datafix.fixes.MapBannerBlockPosFormatFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobEffectIdFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
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
+ XXX.datafix.fixes.ParticleUnflatteningFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.ProjectileStoredWeaponFix
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
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
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
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TippedArrowPotionToItemFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.TrialSpawnerConfigFix
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerSetCanPickUpLootFix
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
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.DamageItem
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
+ XXX.entity.layers.CustomHeadLayer$Transforms
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepWoolLayer
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
- XXX.entity.layers.WardenEmissiveLayer
+ XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
- XXX.entity.layers.WardenEmissiveLayer$DrawSelector
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfArmorLayer
- XXX.entity.layers.WolfCollarLayer
- XXX.entity.player.package-info
+ XXX.entity.player.PlayerRenderer
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
+ XXX.entity.state.AllayRenderState
- XXX.entity.state.ArmadilloRenderState
+ XXX.entity.state.ArmorStandRenderState
- XXX.entity.state.ArrowRenderState
+ XXX.entity.state.AxolotlRenderState
- XXX.entity.state.BatRenderState
+ XXX.entity.state.BeeRenderState
- XXX.entity.state.BlockDisplayEntityRenderState
+ XXX.entity.state.BoatRenderState
- XXX.entity.state.BoggedRenderState
+ XXX.entity.state.BreezeRenderState
- XXX.entity.state.CamelRenderState
+ XXX.entity.state.CatRenderState
- XXX.entity.state.ChickenRenderState
+ XXX.entity.state.CreeperRenderState
- XXX.entity.state.DisplayEntityRenderState
+ XXX.entity.state.DolphinRenderState
- XXX.entity.state.DonkeyRenderState
+ XXX.entity.state.EndCrystalRenderState
- XXX.entity.state.EnderDragonRenderState
+ XXX.entity.state.EndermanRenderState
- XXX.entity.state.EntityRenderState
+ XXX.entity.state.EntityRenderState$LeashState
- XXX.entity.state.EquineRenderState
+ XXX.entity.state.EvokerFangsRenderState
- XXX.entity.state.EvokerRenderState
+ XXX.entity.state.ExperienceOrbRenderState
- XXX.entity.state.FallingBlockRenderState
+ XXX.entity.state.FelineRenderState
- XXX.entity.state.FireworkRocketRenderState
+ XXX.entity.state.FishingHookRenderState
- XXX.entity.state.FoxRenderState
+ XXX.entity.state.FrogRenderState
- XXX.entity.state.GhastRenderState
+ XXX.entity.state.GoatRenderState
- XXX.entity.state.GuardianRenderState
+ XXX.entity.state.HoglinRenderState
- XXX.entity.state.HorseRenderState
+ XXX.entity.state.HumanoidRenderState
- XXX.entity.state.IllagerRenderState
+ XXX.entity.state.IllusionerRenderState
- XXX.entity.state.IronGolemRenderState
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
+ XXX.entity.state.OminousItemSpawnerRenderState
- XXX.entity.state.package-info
- XXX.entity.state.PaintingRenderState
+ XXX.entity.state.PandaRenderState
- XXX.entity.state.ParrotRenderState
+ XXX.entity.state.PhantomRenderState
+ XXX.entity.state.PiglinRenderState
- XXX.entity.state.PigRenderState
- XXX.entity.state.PlayerRenderState
+ XXX.entity.state.PlayerRenderState$HandState
- XXX.entity.state.PolarBearRenderState
+ XXX.entity.state.PufferfishRenderState
- XXX.entity.state.RabbitRenderState
+ XXX.entity.state.RavagerRenderState
- XXX.entity.state.SaddleableRenderState
+ XXX.entity.state.SalmonRenderState
- XXX.entity.state.SheepRenderState
+ XXX.entity.state.ShulkerBulletRenderState
- XXX.entity.state.ShulkerRenderState
+ XXX.entity.state.SkeletonRenderState
- XXX.entity.state.SlimeRenderState
+ XXX.entity.state.SnifferRenderState
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
- XXX.entity.trialspawner.PlayerDetector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
- XXX.entity.trialspawner.TrialSpawner
+ XXX.entity.trialspawner.TrialSpawner$FlameParticle
- XXX.entity.trialspawner.TrialSpawner$StateAccessor
+ XXX.entity.trialspawner.TrialSpawnerConfig
- XXX.entity.trialspawner.TrialSpawnerData
+ XXX.entity.trialspawner.TrialSpawnerState
- XXX.entity.trialspawner.TrialSpawnerState$LightLevel
+ XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
- XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
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
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestBoat$1
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
+ XXX.entity.vehicle.package-info
- XXX.entity.vehicle.VehicleEntity
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
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchFactory
+ XXX.gametest.framework.GameTestBatchListener
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestHelper$3
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
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.armortrim.ArmorTrim
+ XXX.item.armortrim.package-info
+ XXX.item.armortrim.TrimMaterial
- XXX.item.armortrim.TrimMaterials
+ XXX.item.armortrim.TrimPattern
- XXX.item.armortrim.TrimPatterns
- XXX.item.component.BlockItemStateProperties
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
- XXX.item.component.Consumable$Builder
- XXX.item.component.ConsumableListener
- XXX.item.component.package-info
- XXX.item.component.ResolvableProfile
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipProvider
+ XXX.item.component.Unbreakable
- XXX.item.component.UseCooldown
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.PlacementInfo$SlotInfo
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeCache
- XXX.item.crafting.RecipeCache$Entry
+ XXX.item.crafting.RecipeHolder
- XXX.item.crafting.RecipeInput
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleRecipeInput
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingRecipeInput
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.TippedArrowRecipe
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
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
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
- XXX.level.biome.BiomeGenerationSettings$PlainBuilder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeResolver
- XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSources
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$Builder
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
- XXX.level.block.BaseTorchBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BigDripleafBlock
- XXX.level.block.BigDripleafStemBlock
+ XXX.level.block.BigDripleafStemBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Block$ShapePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$Type
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BrushableBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BuddingAmethystBlock
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
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
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.CherryLeavesBlock
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
- XXX.level.block.CocoaBlock$1
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
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantingTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.EquipableCarvedPumpkinBlock
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
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingRootsBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HeavyCoreBlock
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
+ XXX.level.block.Mirror
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
- XXX.level.block.package-info
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PinkPetalsBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
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
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
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
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
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
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.block.WallHangingSignBlock$1
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
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
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
- XXX.level.levelgen.package-info
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
- XXX.level.portal.DimensionTransition
+ XXX.level.portal.DimensionTransition$PostDimensionTransition
- XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalShape
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
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Factory
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
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
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
+ XXX.loot.functions.ToggleTooltips$ComponentToggle
- XXX.loot.functions.ToggleTooltips$TooltipWither
+ XXX.loot.packs.LootData
- XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.VanillaArchaeologyLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChestLoot
+ XXX.loot.packs.VanillaEntityLoot
- XXX.loot.packs.VanillaEquipmentLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
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
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
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
+ XXX.minecraft.commands.package-info
+ XXX.minecraft.commands.ParserUtils
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
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
+ XXX.minecraft.core.MappedRegistry$3
- XXX.minecraft.core.MappedRegistry$4
+ XXX.minecraft.core.MappedRegistry$TagSet
- XXX.minecraft.core.MappedRegistry$TagSet$1
+ XXX.minecraft.core.MappedRegistry$TagSet$2
- XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
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
- XXX.minecraft.data.package-info
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.locale.DeprecatedTranslationsInfo
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
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
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
+ XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ReportedNbtException
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.SnbtPrinterTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor$EntryResult
+ XXX.minecraft.nbt.StreamTagVisitor$ValueResult
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagType$2
- XXX.minecraft.nbt.TagType$StaticSize
+ XXX.minecraft.nbt.TagType$VariableSize
- XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.nbt.TagVisitor
- XXX.minecraft.nbt.TextComponentTagVisitor
- XXX.minecraft.network.BandwidthDebugMonitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.ClientboundPacketListener
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$3
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.DisconnectionDetails
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.HandlerNames
+ XXX.minecraft.network.MonitorFrameDecoder
- XXX.minecraft.network.NoOpFrameDecoder
+ XXX.minecraft.network.NoOpFrameEncoder
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
- XXX.minecraft.network.ProtocolInfo
+ XXX.minecraft.network.ProtocolInfo$Unbound
- XXX.minecraft.network.ProtocolInfo$Unbound$PacketVisitor
+ XXX.minecraft.network.ProtocolSwapHandler
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.RegistryFriendlyByteBuf
- XXX.minecraft.network.ServerboundPacketListener
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.UnconfiguredPipelineHandler
- XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
- XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
- XXX.minecraft.network.Utf8String
+ XXX.minecraft.network.VarInt
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.network.VarLong
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
+ XXX.minecraft.recipebook.PlaceRecipeHelper
- XXX.minecraft.recipebook.PlaceRecipeHelper$Output
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe$CraftingMenuAccess
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.references.package-info
- XXX.minecraft.world.package-info
+ XXX.model.multipart.AndCondition
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.MultiPart
+ XXX.model.multipart.MultiPart$1Key
- XXX.model.multipart.MultiPart$Definition
+ XXX.model.multipart.MultiPart$Deserializer
- XXX.model.multipart.MultiPart$InstantiatedSelector
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
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.Component$SerializerAdapter
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$Type
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
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
+ XXX.network.chat.package-info
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
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
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
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketType
- XXX.network.protocol.PacketUtils
+ XXX.network.protocol.ProtocolCodecBuilder
- XXX.network.protocol.ProtocolInfoBuilder
+ XXX.network.protocol.ProtocolInfoBuilder$1
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
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
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
+ XXX.pools.alias.Direct
+ XXX.pools.alias.package-info
- XXX.pools.alias.PoolAliasBinding
+ XXX.pools.alias.PoolAliasBindings
- XXX.pools.alias.PoolAliasLookup
+ XXX.pools.alias.Random
- XXX.pools.alias.RandomGroup
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
+ XXX.protocol.game.ClientboundMoveMinecartPacket
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
+ XXX.protocol.game.ClientboundProjectilePowerPacket
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
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
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
+ XXX.protocol.game.package-info
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
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
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
+ XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.BundleRecipeProvider$Runner
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$Runner
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
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
- XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$Models
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.StructureBlockRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer$1
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.blockentity.TrialSpawnerRenderer
+ XXX.renderer.blockentity.VaultRenderer
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
+ XXX.renderer.entity.AbstractHoglinRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractMinecartRenderer
- XXX.renderer.entity.AbstractSkeletonRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AgeableMobRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmadilloRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.BoatRenderer$1
+ XXX.renderer.entity.BoggedRenderer
- XXX.renderer.entity.BreezeRenderer
+ XXX.renderer.entity.CamelRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$1
- XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DonkeyRenderer
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
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
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaRenderer$1
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NoopRenderer
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.OminousItemSpawnerRenderer
- XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PaintingRenderer$1
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RabbitRenderer$1
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
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WardenRenderer
+ XXX.renderer.entity.WindChargeRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.renderer.entity.ZombifiedPiglinRenderer
+ XXX.renderer.item.ClampedItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
- XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
+ XXX.renderer.item.ItemProperties
- XXX.renderer.item.ItemProperties$1
+ XXX.renderer.item.ItemPropertyFunction
- XXX.renderer.item.package-info
- XXX.renderer.state.MapRenderState
+ XXX.renderer.state.MapRenderState$MapDecorationRenderState
- XXX.renderer.state.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.Dumpable
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
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
- XXX.resources.model.BlockStateModelLoader
+ XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
- XXX.resources.model.BlockStateModelLoader$LoadedModel
+ XXX.resources.model.BlockStateModelLoader$LoadedModels
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.MissingBlockModel
+ XXX.resources.model.ModelBaker
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BakedCacheKey
- XXX.resources.model.ModelBakery$ModelBakerImpl
+ XXX.resources.model.ModelBakery$TextureGetter
- XXX.resources.model.ModelDiscovery
+ XXX.resources.model.ModelDiscovery$ResolverImpl
- XXX.resources.model.ModelGroupCollector
+ XXX.resources.model.ModelGroupCollector$GroupKey
- XXX.resources.model.ModelManager
+ XXX.resources.model.ModelManager$ReloadState
- XXX.resources.model.ModelResourceLocation
+ XXX.resources.model.ModelState
- XXX.resources.model.MultiPartBakedModel
+ XXX.resources.model.MultiPartBakedModel$Builder
- XXX.resources.model.package-info
- XXX.resources.model.SimpleBakedModel
+ XXX.resources.model.SimpleBakedModel$Builder
- XXX.resources.model.SpecialModels
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.UnbakedModel$ResolutionContext
+ XXX.resources.model.UnbakedModel$Resolver
- XXX.resources.model.WeightedBakedModel
+ XXX.resources.model.WeightedBakedModel$Builder
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
+ XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
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
+ XXX.texture.atlas.SpriteResourceLoader
- XXX.texture.atlas.SpriteSource
+ XXX.texture.atlas.SpriteSource$Output
- XXX.texture.atlas.SpriteSource$SpriteSupplier
+ XXX.texture.atlas.SpriteSourceList
- XXX.texture.atlas.SpriteSourceList$1
- XXX.texture.atlas.SpriteSources
+ XXX.texture.atlas.SpriteSourceType
+ XXX.util.debugchart.AbstractSampleLogger
- XXX.util.debugchart.DebugSampleSubscriptionTracker
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ XXX.util.debugchart.LocalSampleLogger
- XXX.util.debugchart.RemoteDebugSampleType
+ XXX.util.debugchart.RemoteSampleLogger
- XXX.util.debugchart.SampleLogger
+ XXX.util.debugchart.SampleStorage
- XXX.util.debugchart.TpsDebugDimensions
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
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
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
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
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
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
+ XXX.world.item.Items
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
+ XXX.world.item.MilkBucketItem
+ XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileItem
- XXX.world.item.ProjectileItem$DispenseConfig
+ XXX.world.item.ProjectileItem$DispenseConfig$Builder
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
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
+ XXX.world.item.SuspiciousStewItem
+ XXX.world.item.UseAnim
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockAndTintGetter
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
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerExplosion
+ XXX.world.level.ServerExplosion$StackCollector
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SignalGetter
- XXX.world.level.SimpleExplosionDamageCalculator
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.Spawner
- XXX.world.level.StructureManager
+ XXX.world.level.WorldDataConfiguration
- XXX.world.level.WorldGenLevel
+ XXX.world.phys.AABB
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
XXX.blaze3d.pipeline.RenderTarget +1M -2M
```
```
XXX.blaze3d.platform.GlStateManager +1M -1M
```
```
XXX.blaze3d.shaders.Uniform +1M -3M | -2P
```
```
XXX.blaze3d.systems.RenderSystem +5M -4M | +1P -1P
```
```
XXX.blaze3d.vertex.VertexFormat +1M
```
```
XXX.gui.components.AbstractWidget +1M
```
```
XXX.screens.inventory.InventoryScreen -1M
```
```
XXX.client.multiplayer.ClientChunkCache$Storage +4M -1M | +1P
```
```
XXX.client.multiplayer.ClientLevel +1M
```
```
XXX.client.player.AbstractClientPlayer +1M -1M
```
```
XXX.renderer.chunk.SectionRenderDispatcher -1M | +1P -4P
```
```
XXX.renderer.chunk.SectionRenderDispatcher$RenderSection +6M -6M | +1P -2P
```
```
XXX.minecraft.resources.RegistryDataLoader +9M -5M | +1P
```
```
XXX.minecraft.util.ExtraCodecs +46M -42M | +1P
```
```
XXX.minecraft.util.RandomSource +1M
```
```
XXX.world.entity.EntityType +4M -4M
```
```
XXX.world.entity.LivingEntity +2M -8M | -2P
```
```
XXX.entity.projectile.AbstractArrow +1M
```
```
XXX.world.food.Foods -1P
```
```
XXX.world.item.AnimalArmorItem -1M
```
```
XXX.world.item.ArmorItem -1M
```
```
XXX.world.item.BrushItem +1M -1M
```
```
XXX.world.item.Item$Properties +3M
```
```
XXX.world.item.ItemCooldowns$CooldownInstance +5M
```
```
XXX.world.item.ItemStack +2M -3M
```

</details>
<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
+ void _blitToScreen(int,int,boolean)
- void blitAndBlendToScreen(int,int)
+ void blitToScreen(int,int,boolean)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager
</summary>

```diff
+ void glShaderSource(int,List)
- void glShaderSource(int,String)
```

</details>
<details>
<summary>
com.mojang.blaze3d.shaders.Uniform
</summary>

```diff
+ int glGetAttribLocation(int,CharSequence)
+ void <init>(String,int,int,Shader)
- void <init>(String,int,int)
+ void glBindAttribLocation(int,int,CharSequence)
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- CompiledShaderProgram getShader()
- CompiledShaderProgram setShader(ShaderProgram)
+ ShaderInstance getShader()
- void clearShader()
+ void runAsFancy(Runnable)
- void setShader(CompiledShaderProgram)
+ void setShader(Supplier)
- void setupShaderLights(CompiledShaderProgram)
+ void setupShaderLights(ShaderInstance)
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexFormat
</summary>

```diff
- void bindAttributes(int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.AbstractWidget
</summary>

```diff
- void playButtonClickSound(SoundManager)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.InventoryScreen
</summary>

```diff
+ void lambda$renderEntityInInventory$1(EntityRenderDispatcher,LivingEntity,GuiGraphics)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache$Storage
</summary>

```diff
+ LevelChunk replace(int,LevelChunk,LevelChunk)
- void addEmptySections(LevelChunk)
- void drop(int,LevelChunk)
- void dropEmptySections(LevelChunk)
- void onSectionEmptinessChanged(int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- void onSectionBecomingNonEmpty(long)
```

</details>
<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
- float getFieldOfViewModifier(boolean,float)
+ float getFieldOfViewModifier(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.SectionRenderDispatcher
</summary>

```diff
+ SectionRenderDispatcher$RenderSection$CompileTask pollTask()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection
</summary>

```diff
+ BlockPos getRelativeOrigin(Direction)
+ boolean cancelTasks()
+ boolean doesChunkExistAt(BlockPos)
- boolean doesChunkExistAt(long)
- long getNeighborSectionNode(Direction)
- long getSectionNode()
+ void <init>(SectionRenderDispatcher,int,int,int,int)
- void <init>(SectionRenderDispatcher,int,long)
- void cancelTasks()
+ void lambda$new$2(BlockPos$MutableBlockPos[])
+ void setOrigin(int,int,int)
- void setSectionNode(long)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryDataLoader
</summary>

```diff
- ReportedException createReportWithBriefInfo(Map)
- ReportedException logErrors(Map)
+ ResourceLocation lambda$logErrors$10(Map$Entry)
+ ResourceLocation lambda$logErrors$9(Map$Entry)
- ResourceLocation lambda$printFullDetailsToLog$10(Map$Entry)
- ResourceLocation lambda$printFullDetailsToLog$9(Map$Entry)
- String lambda$createReportWithBriefInfo$14(Map)
- void lambda$createReportWithBriefInfo$13(StringBuilder,Map$Entry)
+ void lambda$logErrors$11(PrintWriter,Map$Entry)
+ void lambda$logErrors$12(PrintWriter,Map$Entry)
- void lambda$printFullDetailsToLog$11(PrintWriter,Map$Entry)
- void lambda$printFullDetailsToLog$12(PrintWriter,Map$Entry)
+ void logErrors(Map)
- void printFullDetailsToLog(Map)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ App lambda$static$64(RecordCodecBuilder$Instance)
- App lambda$static$67(RecordCodecBuilder$Instance)
+ App lambda$static$72(RecordCodecBuilder$Instance)
- App lambda$static$78(RecordCodecBuilder$Instance)
+ BitSet lambda$static$60(LongStream)
- BitSet lambda$static$63(LongStream)
- Codec floatRangeMinInclusiveWithMessage(float,float,Function)
+ DataResult lambda$ensureHomogenous$47(Function,Collection)
- DataResult lambda$ensureHomogenous$50(Function,Collection)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$40(float,float,Function,Float)
- DataResult lambda$floatRangeMinExclusiveWithMessage$42(float,float,Function,Float)
- DataResult lambda$floatRangeMinInclusiveWithMessage$40(float,float,Function,Float)
+ DataResult lambda$nonEmptyHolderSet$45(HolderSet)
- DataResult lambda$nonEmptyHolderSet$48(HolderSet)
+ DataResult lambda$nonEmptyList$43(List)
- DataResult lambda$nonEmptyList$46(List)
+ DataResult lambda$sizeLimitedMap$81(int,Map)
- DataResult lambda$sizeLimitedMap$84(int,Map)
+ DataResult lambda$static$49(String)
+ DataResult lambda$static$54(String)
- DataResult lambda$static$55(String)
- DataResult lambda$static$60(String)
+ DataResult lambda$static$71(String)
- DataResult lambda$static$74(String)
+ DataResult lambda$static$77(String)
+ DataResult lambda$static$79(String)
- DataResult lambda$static$80(String)
- DataResult lambda$static$82(String)
+ DataResult lambda$static$83(String)
- DataResult lambda$static$86(String)
+ DataResult lambda$temporalCodec$50(DateTimeFormatter,String)
- DataResult lambda$temporalCodec$53(DateTimeFormatter,String)
+ Either lambda$static$69(PropertyMap)
- Either lambda$static$72(PropertyMap)
+ ExtraCodecs$TagOrElementLocation lambda$static$55(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$56(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$58(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$59(ResourceLocation)
+ GameProfile lambda$static$74(GameProfile,PropertyMap)
- GameProfile lambda$static$77(GameProfile,PropertyMap)
+ LongStream lambda$static$61(BitSet)
- LongStream lambda$static$64(BitSet)
+ Optional lambda$static$59(OptionalLong)
- Optional lambda$static$62(OptionalLong)
+ Optional lambda$static$62(Property)
- Optional lambda$static$65(Property)
+ OptionalLong lambda$static$58(Optional)
- OptionalLong lambda$static$61(Optional)
+ Property lambda$static$63(String,String,Optional)
- Property lambda$static$66(String,String,Optional)
+ PropertyMap lambda$static$68(Either)
- PropertyMap lambda$static$71(Either)
+ String lambda$ensureHomogenous$46(Object,Object,Object)
- String lambda$ensureHomogenous$49(Object,Object,Object)
+ String lambda$floatRangeMinExclusiveWithMessage$39(Function,Float)
- String lambda$floatRangeMinExclusiveWithMessage$41(Function,Float)
- String lambda$floatRangeMinInclusiveWithMessage$39(Function,Float)
+ String lambda$nonEmptyHolderSet$44()
- String lambda$nonEmptyHolderSet$47()
+ String lambda$nonEmptyList$42()
- String lambda$nonEmptyList$45()
+ String lambda$sizeLimitedMap$80(Map,int)
- String lambda$sizeLimitedMap$83(Map,int)
+ String lambda$static$41(Float)
- String lambda$static$43(Float)
- String lambda$static$44(Float)
+ String lambda$static$48(String,PatternSyntaxException)
+ String lambda$static$51()
- String lambda$static$51(String,PatternSyntaxException)
+ String lambda$static$53(byte[])
- String lambda$static$54()
- String lambda$static$56(byte[])
+ String lambda$static$70(String)
- String lambda$static$73(String)
+ String lambda$static$76()
+ String lambda$static$78(String)
- String lambda$static$79()
- String lambda$static$81(String)
+ String lambda$static$82(String)
- String lambda$static$85(String)
+ void lambda$static$65(PropertyMap,String,List)
+ void lambda$static$66(PropertyMap,Map)
+ void lambda$static$67(PropertyMap,List)
- void lambda$static$68(PropertyMap,String,List)
- void lambda$static$69(PropertyMap,Map)
- void lambda$static$70(PropertyMap,List)
+ void lambda$static$73(GameProfile,String,Property)
- void lambda$static$76(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.RandomSource
</summary>

```diff
- float triangle(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
- Consumer appendCustomEntityStackConfig(Consumer,Level,ItemStack,Player)
+ Consumer appendCustomEntityStackConfig(Consumer,ServerLevel,ItemStack,Player)
- Consumer appendDefaultStackConfig(Consumer,Level,ItemStack,Player)
+ Consumer appendDefaultStackConfig(Consumer,ServerLevel,ItemStack,Player)
- Consumer createDefaultStackConfig(Level,ItemStack,Player)
+ Consumer createDefaultStackConfig(ServerLevel,ItemStack,Player)
- void lambda$appendCustomEntityStackConfig$3(Level,Player,CustomData,Entity)
+ void lambda$appendCustomEntityStackConfig$3(ServerLevel,Player,CustomData,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ boolean shouldTriggerItemUseEffects()
+ ItemStack eat(Level,ItemStack,FoodProperties)
+ ItemStack eat(Level,ItemStack)
- ItemStack getItemBlockingWith()
+ SoundEvent getDrinkingSound(ItemStack)
+ SoundEvent getEatingSound(ItemStack)
+ void addEatEffect(FoodProperties)
+ void onEffectRemoved(MobEffectInstance)
- void onEffectsRemoved(Collection)
+ void triggerItemUseEffects(ItemStack,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- boolean shouldBounceOnWorldBorder()
```

</details>
<details>
<summary>
net.minecraft.world.item.AnimalArmorItem
</summary>

```diff
+ boolean isEnchantable(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
+ int getEnchantmentValue()
```

</details>
<details>
<summary>
net.minecraft.world.item.BrushItem
</summary>

```diff
- ItemUseAnimation getUseAnimation(ItemStack)
+ UseAnim getUseAnimation(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.Item$Properties
</summary>

```diff
- Item$Properties food(FoodProperties,Consumable)
- Item$Properties useCooldown(float)
- Item$Properties usingConvertsTo(Item)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemCooldowns$CooldownInstance
</summary>

```diff
- boolean equals(Object)
- int endTime()
- int hashCode()
- int startTime()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- ItemStack applyAfterUseComponentSideEffects(LivingEntity,ItemStack)
- ItemUseAnimation getUseAnimation()
+ SoundEvent getDrinkingSound()
+ SoundEvent getEatingSound()
+ UseAnim getUseAnimation()
```

</details>
</details>
<hr/>