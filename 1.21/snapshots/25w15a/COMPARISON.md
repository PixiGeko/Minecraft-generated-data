## Comparison with [1.21.5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.5)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
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
<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>DataPack version</td><td><pre>71</pre></td><td><pre>72</pre></td></tr><tr><td>ResourcePack version</td><td><pre>55</pre></td><td><pre>56</pre></td></tr><tr><td>World version</td><td><pre>4325</pre></td><td><pre>4422</pre></td></tr><tr><td>Protocol version</td><td><pre>770</pre></td><td><pre>1073742069</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:camera_distance
+ minecraft:waypoint_receive_range
+ minecraft:waypoint_transmit_range
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:dried_ghast
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:dried_ghast
- minecraft:terracotta
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
entity_type
</summary>

```diff
+ minecraft:happy_ghast
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
+ minecraft:dried_ghast
+ minecraft:gray_harness
+ minecraft:green_harness
+ minecraft:happy_ghast_spawn_egg
+ minecraft:light_blue_harness
+ minecraft:light_gray_harness
+ minecraft:lime_harness
+ minecraft:magenta_harness
+ minecraft:orange_harness
+ minecraft:pink_harness
+ minecraft:purple_harness
+ minecraft:red_harness
+ minecraft:white_harness
+ minecraft:yellow_harness
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
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:dried_ghast
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:happy_ghast
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:happy_ghast
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:camera_distance
+ minecraft:waypoint_receive_range
+ minecraft:waypoint_transmit_range
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:dried_ghast
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:dried_ghast
- minecraft:terracotta
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
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:happy_ghast
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
+ minecraft:dried_ghast
+ minecraft:gray_harness
+ minecraft:green_harness
+ minecraft:happy_ghast_spawn_egg
+ minecraft:light_blue_harness
+ minecraft:light_gray_harness
+ minecraft:lime_harness
+ minecraft:magenta_harness
+ minecraft:orange_harness
+ minecraft:pink_harness
+ minecraft:purple_harness
+ minecraft:red_harness
+ minecraft:white_harness
+ minecraft:yellow_harness
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
+ dried_ghast.json
+ gray_harness.json
+ green_harness.json
+ happy_ghast_spawn_egg.json
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
carved_pumpkin
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
chainmail_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
creeper_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
diamond_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
diamond_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
diamond_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
dragon_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
golden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
golden_chestplate
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
iron_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
iron_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
iron_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
iron_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
iron_pickaxe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
leather_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
mace
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
netherite_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
netherite_boots
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
netherite_leggings
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
netherite_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
piglin_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
player_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
stone_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
stone_hoe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
stone_shovel
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
stone_sword
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
trident
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
turtle_helmet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
wither_skeleton_skull
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
wooden_axe
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[
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
zombie_head
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>minecraft:attribute_modifiers</td><td><pre>[]</pre></td><td><pre>[
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
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ dried_ghast.json
```

</details>
<details>
<summary>
black_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_terracotta
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">1.21.5</th><th>25w15a</th></tr><tr><td>type</td><td><pre>minecraft:terracotta</pre></td><td><pre>minecraft:block</pre></td></tr></table>
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
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.heart_transplanter.description: Place a Creaking Heart with the correct alignment between two Pale Oak Log blocks
+ advancements.adventure.heart_transplanter.title: Heart Transplanter
+ advancements.husbandry.place_dried_ghast_in_water.description: Place a Dried Ghast block into water
+ advancements.husbandry.place_dried_ghast_in_water.title: Stay Hydrated!
+ argument.hexcolor.invalid: Invalid hex color code '%s'
+ argument.waypoint.invalid: Selected entity is not a waypoint
+ attribute.name.camera_distance: Camera Distance
+ attribute.name.waypoint_receive_range: Waypoint Receive Range
+ attribute.name.waypoint_transmit_range: Waypoint Transmit Range
+ block.minecraft.dried_ghast: Dried Ghast
+ commands.datapack.create.already_exists: Pack with name '%s' already exists
+ commands.datapack.create.invalid_name: Invalid characters in new pack name '%s'
+ commands.datapack.create.io_failure: Can't create pack with name '%s', check logs
+ commands.datapack.create.metadata_encode_failure: Failed to encode metadata for pack with name '%s': %s
+ commands.datapack.create.success: Created new empty pack with name '%s'
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
+ dataPack.locator_bar.description: Show the direction of other players in multiplayer
+ dataPack.locator_bar.name: Locator Bar
+ debug.version.header: Client version info:
+ debug.version.help: F3 + V = Client version info
+ entity.minecraft.happy_ghast: Happy Ghast
+ gamerule.useLocatorBar: Use player Locator Bar
+ gamerule.useLocatorBar.description: When enabled, a bar is shown on the screen to indicate the direction of players.
+ gui.experience.level: %s
+ item.minecraft.black_harness: Black Harness
+ item.minecraft.blue_harness: Blue Harness
+ item.minecraft.brown_harness: Brown Harness
+ item.minecraft.cyan_harness: Cyan Harness
+ item.minecraft.gray_harness: Gray Harness
+ item.minecraft.green_harness: Green Harness
+ item.minecraft.happy_ghast_spawn_egg: Happy Ghast Spawn Egg
+ item.minecraft.harness: Harness
+ item.minecraft.light_blue_harness: Light Blue Harness
+ item.minecraft.light_gray_harness: Light Gray Harness
+ item.minecraft.lime_harness: Lime Harness
+ item.minecraft.magenta_harness: Magenta Harness
+ item.minecraft.orange_harness: Orange Harness
+ item.minecraft.pink_harness: Pink Harness
+ item.minecraft.purple_harness: Purple Harness
+ item.minecraft.red_harness: Red Harness
+ item.minecraft.white_harness: White Harness
+ item.minecraft.yellow_harness: Yellow Harness
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
```

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
+ minecraft:waypoint
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
+ minecraft/advancement/adventure/heart_transplanter.json
+ minecraft/advancement/husbandry/place_dried_ghast_in_water.json
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
+ minecraft/datapacks/locator_bar/pack.mcmeta
+ minecraft/loot_table/blocks/dried_ghast.json
+ minecraft/loot_table/entities/happy_ghast.json
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
- minecraft/tags/block/plays_ambient_desert_block_sounds.json
+ minecraft/tags/block/triggers_ambient_desert_dry_vegetation_block_sounds.json
+ minecraft/tags/block/triggers_ambient_desert_sand_block_sounds.json
+ minecraft/tags/entity_type/can_equip_harness.json
+ minecraft/tags/entity_type/followable_friendly_mobs.json
+ minecraft/tags/item/happy_ghast_food.json
+ minecraft/tags/item/happy_ghast_tempt_items.json
+ minecraft/tags/item/harnesses.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/dried_ghast.json
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
+ minecraft/items/black_harness.json
+ minecraft/items/blue_harness.json
+ minecraft/items/brown_harness.json
+ minecraft/items/cyan_harness.json
+ minecraft/items/dried_ghast.json
+ minecraft/items/gray_harness.json
+ minecraft/items/green_harness.json
+ minecraft/items/happy_ghast_spawn_egg.json
+ minecraft/items/light_blue_harness.json
+ minecraft/items/light_gray_harness.json
+ minecraft/items/lime_harness.json
+ minecraft/items/magenta_harness.json
+ minecraft/items/orange_harness.json
+ minecraft/items/pink_harness.json
+ minecraft/items/purple_harness.json
+ minecraft/items/red_harness.json
+ minecraft/items/white_harness.json
+ minecraft/items/yellow_harness.json
+ minecraft/models/block/dried_ghast_hydration_0.json
+ minecraft/models/block/dried_ghast_hydration_1.json
+ minecraft/models/block/dried_ghast_hydration_2.json
+ minecraft/models/block/dried_ghast_hydration_3.json
+ minecraft/models/block/dried_ghast.json
+ minecraft/models/item/black_harness.json
+ minecraft/models/item/blue_harness.json
+ minecraft/models/item/brown_harness.json
+ minecraft/models/item/cyan_harness.json
+ minecraft/models/item/gray_harness.json
+ minecraft/models/item/green_harness.json
+ minecraft/models/item/happy_ghast_spawn_egg.json
+ minecraft/models/item/light_blue_harness.json
+ minecraft/models/item/light_gray_harness.json
+ minecraft/models/item/lime_harness.json
+ minecraft/models/item/magenta_harness.json
+ minecraft/models/item/orange_harness.json
+ minecraft/models/item/pink_harness.json
+ minecraft/models/item/purple_harness.json
+ minecraft/models/item/red_harness.json
+ minecraft/models/item/white_harness.json
+ minecraft/models/item/yellow_harness.json
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
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_down.png
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_down.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_up.png
+ minecraft/textures/gui/sprites/hud/locator_bar_arrow_up.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_background.png
+ minecraft/textures/gui/sprites/hud/locator_bar_background.png.mcmeta
+ minecraft/textures/gui/sprites/hud/locator_bar_player.png
- minecraft/textures/gui/title/edition.png.mcmeta
- minecraft/textures/gui/title/minceraft.png.mcmeta
- minecraft/textures/gui/title/minecraft.png.mcmeta
- minecraft/textures/gui/title/realms.png.mcmeta
+ minecraft/textures/item/black_harness.png
+ minecraft/textures/item/blue_harness.png
+ minecraft/textures/item/brown_harness.png
+ minecraft/textures/item/cyan_harness.png
+ minecraft/textures/item/gray_harness.png
+ minecraft/textures/item/green_harness.png
+ minecraft/textures/item/happy_ghast_spawn_egg.png
+ minecraft/textures/item/light_blue_harness.png
+ minecraft/textures/item/light_gray_harness.png
+ minecraft/textures/item/lime_harness.png
+ minecraft/textures/item/magenta_harness.png
+ minecraft/textures/item/orange_harness.png
+ minecraft/textures/item/pink_harness.png
+ minecraft/textures/item/purple_harness.png
+ minecraft/textures/item/red_harness.png
+ minecraft/textures/item/white_harness.png
+ minecraft/textures/item/yellow_harness.png
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
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.Attribute$Sentiment
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.AttributeReceiver
- XXX.ai.goal.package-info
- XXX.ai.goal.TemptGoal$ForNonPathfinders
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
- XXX.ai.sensing.AdultSensorAnyType
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
- XXX.commands.arguments.HexColorArgument
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
- XXX.datafix.schemas.V3439_1
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
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
- XXX.entity.ai.package-info
- XXX.entity.animal.HappyGhast
- XXX.entity.animal.HappyGhast$HappyGhastBodyRotationControl
- XXX.entity.animal.HappyGhast$HappyGhastLookControl
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
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
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
- XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$Type
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
- XXX.item.component.package-info
+ XXX.item.component.ProvidesTrimMaterial
- XXX.item.component.ResolvableProfile
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
+ XXX.level.block.package-info
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
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
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
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.package-info
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
+ XXX.minecraft.server.ServerScoreboard$Method
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
+ XXX.minecraft.world.package-info
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
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
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
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
- XXX.protocol.game.package-info
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
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundPlayerLoadedPacket
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
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
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
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
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
+ XXX.server.commands.package-info
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
- XXX.server.commands.VersionCommand
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
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
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
+ XXX.world.item.package-info
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
- XXX.world.level.package-info
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
net.minecraft.SharedConstants +1P
```
```
XXX.minecraft.data.Main +1M
```
```
XXX.advancements.packs.VanillaAdventureAdvancements +8M -5M
```
```
XXX.server.commands.CloneCommands$CloneBlockInfo +2M -1M | +1P
```
```
XXX.server.commands.DataPackCommand +32M -24M | +5P
```
```
XXX.world.entity.Entity +5M -1M | +1P
```
```
XXX.world.entity.EntityType +1P
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
XXX.ai.sensing.SensorType +1M | +2P
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
XXX.world.flag.FeatureFlags +1P
```
```
XXX.world.item.Items +18M -16M | +18P
```
```
XXX.level.block.DryVegetationBlock -2P
```
```
XXX.level.block.ShortDryGrassBlock +1M
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
net.minecraft.data.Main
</summary>

```diff
- PackMetadataGenerator lambda$addServerProviders$8(PackOutput)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
</summary>

```diff
- AllOfCondition$Builder lambda$placedBlockActivatesCreakingHeart$4(HolderGetter,TagKey,Direction)
+ boolean lambda$smithingWithStyle$4(Set,VanillaRecipeProvider$TrimTemplate)
- boolean lambda$smithingWithStyle$6(Set,VanillaRecipeProvider$TrimTemplate)
- Criterion placedBlockActivatesCreakingHeart(HolderGetter,TagKey)
- LootItemCondition$Builder[] lambda$placedBlockActivatesCreakingHeart$5(int)
- void lambda$addMobsToKill$10(Advancement$Builder,HolderGetter,EntityType)
+ void lambda$addMobsToKill$8(Advancement$Builder,HolderGetter,EntityType)
+ void lambda$craftingANewLook$6(Advancement$Builder,ResourceKey)
- void lambda$craftingANewLook$8(Advancement$Builder,ResourceKey)
+ void lambda$respectingTheRemnantsCriterions$7(Advancement$Builder,Pair)
- void lambda$respectingTheRemnantsCriterions$9(Advancement$Builder,Pair)
+ void lambda$smithingWithStyle$5(Advancement$Builder,VanillaRecipeProvider$TrimTemplate)
- void lambda$smithingWithStyle$7(Advancement$Builder,VanillaRecipeProvider$TrimTemplate)
```

</details>
<details>
<summary>
net.minecraft.server.commands.CloneCommands$CloneBlockInfo
</summary>

```diff
- BlockState previousStateAtDestination()
- void <init>(BlockPos,BlockState,CloneCommands$CloneBlockEntityInfo,BlockState)
+ void <init>(BlockPos,BlockState,CloneCommands$CloneBlockEntityInfo)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DataPackCommand
</summary>

```diff
+ boolean lambda$listAvailablePacks$25(Collection,FeatureFlagSet,Pack)
- boolean lambda$listAvailablePacks$32(Collection,FeatureFlagSet,Pack)
- boolean lambda$register$13(CommandSourceStack)
- boolean lambda$register$27(CommandSourceStack)
+ boolean lambda$register$9(CommandSourceStack)
- boolean lambda$static$10(FeatureFlagSet,Pack)
- boolean lambda$static$11(Collection,String)
+ boolean lambda$static$6(FeatureFlagSet,Pack)
+ boolean lambda$static$7(Collection,String)
- CompletableFuture lambda$static$12(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$5(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$8(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$static$9(CommandContext,SuggestionsBuilder)
- Component lambda$createPack$29(String)
+ Component lambda$disablePack$24(Pack)
- Component lambda$disablePack$31(Pack)
+ Component lambda$enablePack$23(Pack)
- Component lambda$enablePack$30(Pack)
+ Component lambda$listAvailablePacks$26()
+ Component lambda$listAvailablePacks$27(Pack)
+ Component lambda$listAvailablePacks$28(List)
- Component lambda$listAvailablePacks$33()
- Component lambda$listAvailablePacks$34(Pack)
- Component lambda$listAvailablePacks$35(List)
+ Component lambda$listEnabledPacks$29()
+ Component lambda$listEnabledPacks$30(Pack)
+ Component lambda$listEnabledPacks$31(Collection)
- Component lambda$listEnabledPacks$36()
- Component lambda$listEnabledPacks$37(Pack)
- Component lambda$listEnabledPacks$38(Collection)
- int createPack(CommandSourceStack,String,Component)
+ int lambda$register$11(CommandContext)
+ int lambda$register$13(CommandContext)
+ int lambda$register$16(CommandContext)
- int lambda$register$17(CommandContext)
+ int lambda$register$18(CommandContext)
+ int lambda$register$21(CommandContext)
- int lambda$register$23(CommandContext)
- int lambda$register$24(CommandContext)
- int lambda$register$25(CommandContext)
- int lambda$register$26(CommandContext)
- int lambda$register$28(CommandContext)
- Message lambda$static$5(Object)
- Message lambda$static$6(Object)
- Message lambda$static$7(Object,Object)
- Message lambda$static$8(Object)
+ void lambda$register$10(List,Pack)
+ void lambda$register$12(CommandContext,List,Pack)
+ void lambda$register$14(CommandContext,List,Pack)
- void lambda$register$14(List,Pack)
- void lambda$register$16(CommandContext,List,Pack)
+ void lambda$register$17(List,Pack)
- void lambda$register$18(CommandContext,List,Pack)
- void lambda$register$21(List,Pack)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
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
net.minecraft.world.entity.ai.sensing.SensorType
</summary>

```diff
- TemptingSensor lambda$static$7()
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
net.minecraft.world.item.Items
</summary>

```diff
+ Item lambda$createBlockItemWithCustomItemName$249(Block,Item$Properties)
- Item lambda$createBlockItemWithCustomItemName$251(Block,Item$Properties)
+ Item lambda$registerBlock$250(UnaryOperator,Block,Item$Properties)
+ Item lambda$registerBlock$251(BiFunction,Block,Item$Properties)
- Item lambda$registerBlock$252(UnaryOperator,Block,Item$Properties)
- Item lambda$registerBlock$253(BiFunction,Block,Item$Properties)
- Item lambda$static$109(Block,Item$Properties)
+ Item lambda$static$109(Item$Properties)
- Item lambda$static$135(Item$Properties)
+ Item lambda$static$137(Item$Properties)
+ Item lambda$static$220(Block,Item$Properties)
- Item lambda$static$220(Item$Properties)
+ Item lambda$static$221(Block,Item$Properties)
- Item lambda$static$221(Item$Properties)
- Item lambda$static$227(Block,Item$Properties)
+ Item lambda$static$227(Item$Properties)
+ Item lambda$static$229(Block,Item$Properties)
- Item lambda$static$229(Item$Properties)
+ Item lambda$static$24(Block,Item$Properties)
- Item lambda$static$244(Block,Item$Properties)
- Item lambda$static$245(Block,Item$Properties)
- Item lambda$static$35(Block,Item$Properties)
+ Item lambda$static$39(Item$Properties)
+ Item lambda$static$85(Block,Item$Properties)
- Item lambda$static$85(Item$Properties)
+ Item$Properties lambda$static$135(Item$Properties)
- Item$Properties lambda$static$137(Item$Properties)
- Item$Properties lambda$static$24(Item$Properties)
+ Item$Properties lambda$static$244(Item$Properties)
+ Item$Properties lambda$static$245(Item$Properties)
- Item$Properties lambda$static$249(Item$Properties)
- Item$Properties lambda$static$250(Item$Properties)
+ Item$Properties lambda$static$35(Item$Properties)
- Item$Properties lambda$static$39(Item$Properties)
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- net.minecraft.WorldVersion$Simple
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.Attribute$Sentiment
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.goal.package-info
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
- XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiGraphics$ScissorStack
+ XXX.client.gui.GuiSpriteManager
- XXX.client.gui.ItemSlotMouseAction
+ XXX.client.gui.LayeredDraw
+ XXX.client.gui.package-info
- XXX.client.model.HappyGhastModel
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
- XXX.client.waypoints.ClientWaypointManager
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
- XXX.commands.arguments.WaypointArgument
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
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.ai.package-info
- XXX.entity.animal.HappyGhast$BabyFlyingPathNavigation
- XXX.entity.animal.HappyGhast$HappyGhastFloatGoal
- XXX.entity.animal.HappyGhastAi
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
+ XXX.entity.layers.package-info
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
- XXX.entity.player.package-info
+ XXX.entity.player.PlayerRenderer
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
- XXX.entity.state.HappyGhastRenderState
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
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
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
- XXX.gui.render.GuiLayer
- XXX.gui.render.GuiRenderer$AtlasPosition
- XXX.gui.render.TextureSetup
- XXX.item.component.ItemAttributeModifiers$Display$Default
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
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
+ XXX.item.trading.ItemCost
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
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
- XXX.level.block.package-info
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
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
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
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.package-info
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
- XXX.minecraft.world.package-info
+ XXX.mojang.blaze3d.package-info
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
+ XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
+ XXX.network.config.SynchronizeRegistriesTask
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
- XXX.pools.alias.DirectPoolAlias
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.RandomGroupPoolAlias
+ XXX.pools.alias.RandomPoolAlias
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
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
+ XXX.protocol.game.GameProtocols$1
- XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
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
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
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
- XXX.render.pip.GuiBannerResultRenderer
- XXX.render.pip.GuiEntityRenderer
- XXX.render.pip.GuiSignRenderer
- XXX.render.pip.PictureInPictureRenderer
- XXX.render.state.BlitRenderState
- XXX.render.state.GlyphRenderState
- XXX.render.state.GuiItemRenderState
- XXX.render.state.GuiTextRenderState
- XXX.render.state.package-info
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
- XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
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
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
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
- XXX.server.commands.package-info
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
- XXX.server.waypoints.ServerWaypointManager$NullWaypointManager
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.pip.GuiBookModelRenderState
- XXX.state.pip.GuiProfilerChartRenderState
- XXX.state.pip.GuiSkinRenderState
- XXX.state.pip.package-info
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
- XXX.telemetry.events.AggregatedTelemetryEvent
+ XXX.telemetry.events.GameLoadTimesEvent
- XXX.telemetry.events.GameLoadTimesEvent$Measurement
- XXX.telemetry.events.package-info
+ XXX.telemetry.events.PerformanceMetricsEvent
- XXX.telemetry.events.WorldLoadEvent
+ XXX.telemetry.events.WorldLoadEvent$1
- XXX.telemetry.events.WorldLoadTimesEvent
+ XXX.telemetry.events.WorldUnloadEvent
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
- XXX.world.item.package-info
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
+ XXX.world.level.package-info
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
net.minecraft.WorldVersion +7P -7P
```
```
XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance +4M
```
```
XXX.minecraft.client.KeyboardHandler +5M -4M
```
```
XXX.minecraft.client.NarratorStatus +1M
```
```
XXX.data.models.BlockModelGenerators +18M -15M
```
```
XXX.data.models.ItemModelGenerators +1M -1M
```
```
XXX.models.model.ModelTemplates +1P
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
XXX.client.gui.GuiGraphics +44M -39M | +6P -5P
```
```
XXX.components.debugchart.ProfilerPieChart -1M | +1P -1P
```
```
XXX.gui.screens.LoadingOverlay -2M
```
```
XXX.screens.advancements.AdvancementsScreen +1M -1M
```
```
XXX.screens.inventory.AbstractSignEditScreen -1M | +1P
```
```
XXX.screens.inventory.HangingSignEditScreen +1M -1M
```
```
XXX.screens.inventory.SignEditScreen +1M -2M
```
```
XXX.inventory.tooltip.ClientTooltipComponent +1M -1M
```
```
XXX.inventory.tooltip.TooltipRenderUtil +1M -1M
```
```
XXX.screens.recipebook.GhostSlots +1M -1M
```
```
XXX.client.renderer.CloudRenderer -1P
```
```
XXX.client.renderer.DimensionSpecialEffects +1M -3M | -2P
```
```
XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Entry +1M -2M | -1P
```
```
XXX.client.renderer.RenderStateShard$TextureStateShard +2M -2M | -1P
```
```
XXX.client.renderer.RenderType +3M -21M | -12P
```
```
XXX.client.renderer.ScreenEffectRenderer +6M -2M | +7P
```
```
XXX.renderer.item.BlockModelWrapper +1P
```
```
XXX.renderer.texture.AbstractTexture +1M -1M | -1P
```
```
XXX.renderer.texture.SkinTextureDownloader +1M -1M
```
```
XXX.renderer.texture.TextureAtlasSprite +1M | +1P
```
```
XXX.resources.model.EquipmentClientInfo$LayerType +1P
```
```
XXX.data.recipes.RecipeProvider +3M -1M
```
```
XXX.minecraft.network.FriendlyByteBuf +4M
```
```
XXX.network.codec.ByteBufCodecs +1P
```
```
XXX.network.codec.ByteBufCodecs$32 +5M -1M | -1P
```
```
XXX.world.entity.AreaEffectCloud +2M -2M | +1P
```
```
XXX.ai.attributes.Attributes +3P
```
```
XXX.ai.control.MoveControl +1M
```
```
XXX.ai.goal.TemptGoal +4M | +3P -1P
```
```
XXX.entity.animal.Fox -1M
```
```
XXX.animal.horse.AbstractHorse -1M
```
```
XXX.entity.monster.Ghast$GhastLookGoal +1M -1M | +1P -1P
```
```
XXX.world.item.ItemStack +4M -4M
```
```
XXX.item.component.ItemAttributeModifiers +1M
```
```
XXX.item.component.ItemAttributeModifiers$Builder +1M
```
```
XXX.level.block.SoundType +1P
```
```
XXX.level.block.TallDryGrassBlock +1M
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
net.minecraft.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
</summary>

```diff
- Criterion placedBlockWithProperties(Block,Property,boolean)
- Criterion placedBlockWithProperties(Block,Property,Comparable)
- Criterion placedBlockWithProperties(Block,Property,int)
- Criterion placedBlockWithProperties(Block,Property,String)
```

</details>
<details>
<summary>
net.minecraft.client.KeyboardHandler
</summary>

```diff
- Component decorateDebugComponent(ChatFormatting,Component)
+ void debugComponent(ChatFormatting,Component)
+ void debugFeedback(String,Object[])
- void debugFeedbackFormatted(String,Object[])
+ void debugFeedbackTranslated(String,Object[])
- void debugFeedbackTranslated(String)
- void debugWarningComponent(Component)
+ void debugWarningTranslated(String,Object[])
- void showDebugChat(Component)
```

</details>
<details>
<summary>
net.minecraft.client.NarratorStatus
</summary>

```diff
- boolean shouldNarrateSystemOrChat()
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
- void createDriedGhastBlock()
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
net.minecraft.client.gui.components.debugchart.ProfilerPieChart
</summary>

```diff
+ void lambda$render$0(List,GuiGraphics,int,int,MultiBufferSource)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ RenderType lambda$render$1(ResourceLocation)
+ RenderType lambda$render$2(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementsScreen
</summary>

```diff
+ void renderInside(GuiGraphics,int,int,int,int)
- void renderInside(GuiGraphics,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
</summary>

```diff
+ void offsetSign(GuiGraphics,BlockState)
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
net.minecraft.client.gui.screens.inventory.SignEditScreen
</summary>

```diff
- float getSignYOffset()
+ void lambda$renderSignBackground$0(GuiGraphics,MultiBufferSource)
+ void offsetSign(GuiGraphics,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
</summary>

```diff
+ void renderText(Font,int,int,Matrix4f,MultiBufferSource$BufferSource)
- void renderText(GuiGraphics,Font,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
</summary>

```diff
+ void renderTooltipBackground(GuiGraphics,int,int,int,int,int,ResourceLocation)
- void renderTooltipBackground(GuiGraphics,int,int,int,int,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.GhostSlots
</summary>

```diff
+ void lambda$render$0(boolean,GuiGraphics,Minecraft,Slot,GhostSlots$GhostSlot)
- void lambda$render$0(GuiGraphics,boolean,Minecraft,Slot,GhostSlots$GhostSlot)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.DimensionSpecialEffects
</summary>

```diff
+ boolean hasGround()
+ float getCloudHeight()
- void <init>(DimensionSpecialEffects$SkyType,boolean,boolean)
+ void <init>(float,boolean,DimensionSpecialEffects$SkyType,boolean,boolean)
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
net.minecraft.client.renderer.RenderStateShard$TextureStateShard
</summary>

```diff
- void <init>(ResourceLocation,boolean)
+ void <init>(ResourceLocation,TriState,boolean)
- void lambda$new$0(ResourceLocation,boolean)
+ void lambda$new$0(ResourceLocation,TriState,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
+ RenderType crosshair(ResourceLocation)
+ RenderType debugLine(double)
+ RenderType gui()
+ RenderType guiGhostRecipeOverlay()
+ RenderType guiNauseaOverlay()
+ RenderType guiOpaqueTexturedBackground(ResourceLocation)
+ RenderType guiOverlay()
+ RenderType guiTextHighlight()
+ RenderType guiTextured(ResourceLocation)
+ RenderType guiTexturedOverlay(ResourceLocation)
- RenderType lambda$createWeather$27(RenderPipeline,ResourceLocation)
+ RenderType lambda$createWeather$28(RenderPipeline,ResourceLocation)
- RenderType lambda$static$25(ResourceLocation)
+ RenderType lambda$static$27(ResourceLocation)
- RenderType lambda$static$28(ResourceLocation)
+ RenderType lambda$static$31(ResourceLocation)
+ RenderType lambda$static$32(ResourceLocation)
+ RenderType lambda$static$33(ResourceLocation)
+ RenderType lambda$static$34(ResourceLocation)
+ RenderType lambda$static$35(ResourceLocation)
+ RenderType lambda$static$36(ResourceLocation)
+ RenderType mojangLogo()
+ RenderType vignette(ResourceLocation)
+ RenderType$CompositeRenderType lambda$static$25(Double)
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
net.minecraft.client.renderer.texture.AbstractTexture
</summary>

```diff
+ void setFilter(TriState,boolean)
- void setUseMipmaps(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.SkinTextureDownloader
</summary>

```diff
+ ResourceLocation lambda$registerTextureInManager$2(Minecraft,ResourceLocation,NativeImage)
- ResourceLocation lambda$registerTextureInManager$2(ResourceLocation,NativeImage,Minecraft)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite
</summary>

```diff
- boolean isAnimated()
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
+ void colorBlockWithDye(List,List,String)
- void colorItemWithDye(List,List,String)
- void dryGhast(ItemLike)
- void harness(ItemLike,ItemLike)
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
net.minecraft.world.entity.ai.control.MoveControl
</summary>

```diff
- void setWait()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.TemptGoal
</summary>

```diff
- void <init>(Mob,double,Predicate,boolean,double)
- void <init>(PathfinderMob,double,Predicate,boolean,double)
- void navigateTowards(Player)
- void stopNavigation()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Fox
</summary>

```diff
+ boolean isJumping()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ boolean isJumping()
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
net.minecraft.world.item.ItemStack
</summary>

```diff
+ Style lambda$getDisplayName$20(Style)
- Style lambda$getDisplayName$21(Style)
+ void addModifierTooltip(Consumer,Player,Holder,AttributeModifier)
+ void forEachModifier(EquipmentSlotGroup,BiConsumer)
- void forEachModifier(EquipmentSlotGroup,TriConsumer)
- void lambda$addAttributeTooltips$18(MutableBoolean,Consumer,EquipmentSlotGroup,Player,Holder,AttributeModifier,ItemAttributeModifiers$Display)
+ void lambda$addAttributeTooltips$18(MutableBoolean,Consumer,EquipmentSlotGroup,Player,Holder,AttributeModifier)
- void lambda$forEachModifier$20(TriConsumer,Holder,AttributeModifier)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.ItemAttributeModifiers
</summary>

```diff
- void forEach(EquipmentSlotGroup,TriConsumer)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.ItemAttributeModifiers$Builder
</summary>

```diff
- ItemAttributeModifiers$Builder add(Holder,AttributeModifier,EquipmentSlotGroup,ItemAttributeModifiers$Display)
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
</details>
<hr/>