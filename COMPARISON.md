## Comparison with [1.16.5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.5)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.16.5</th><th>21w03a</th></tr><tr><td>DataPack version</td><td><code>-</code></td><td><code>7</code></td></tr><tr><td>ResourcePack version</td><td><code>-</code></td><td><code>7</code></td></tr><tr><td>World version</td><td><code>2586</code></td><td><code>2689</code></td></tr><tr><td>Protocol version</td><td><code>754</code></td><td><code>1073741835</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ game_event.txt
+ loot_nbt_provider_type.txt
+ loot_number_provider_type.txt
+ loot_score_provider_type.txt
+ position_source_type.txt
```

</details>
<details>
<summary>
activity.txt
</summary>

```diff
+ minecraft:play_dead
```

</details>

<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:black_candle
+ minecraft:black_candle_cake
+ minecraft:blue_candle
+ minecraft:blue_candle_cake
+ minecraft:brown_candle
+ minecraft:brown_candle_cake
+ minecraft:budding_amethyst
+ minecraft:calcite
+ minecraft:candle
+ minecraft:candle_cake
+ minecraft:copper_block
+ minecraft:copper_ore
+ minecraft:cut_copper
+ minecraft:cut_copper_slab
+ minecraft:cut_copper_stairs
+ minecraft:cyan_candle
+ minecraft:cyan_candle_cake
+ minecraft:dirt_path
+ minecraft:dripstone_block
+ minecraft:glow_lichen
- minecraft:grass_path
+ minecraft:gray_candle
+ minecraft:gray_candle_cake
+ minecraft:green_candle
+ minecraft:green_candle_cake
+ minecraft:large_amethyst_bud
+ minecraft:lava_cauldron
+ minecraft:light_blue_candle
+ minecraft:light_blue_candle_cake
+ minecraft:light_gray_candle
+ minecraft:light_gray_candle_cake
+ minecraft:lightly_weathered_copper_block
+ minecraft:lightly_weathered_cut_copper
+ minecraft:lightly_weathered_cut_copper_slab
+ minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:lightning_rod
+ minecraft:lime_candle
+ minecraft:lime_candle_cake
+ minecraft:magenta_candle
+ minecraft:magenta_candle_cake
+ minecraft:medium_amethyst_bud
+ minecraft:orange_candle
+ minecraft:orange_candle_cake
+ minecraft:pink_candle
+ minecraft:pink_candle_cake
+ minecraft:pointed_dripstone
+ minecraft:powder_snow
+ minecraft:powder_snow_cauldron
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
+ minecraft:sculk_sensor
+ minecraft:semi_weathered_copper_block
+ minecraft:semi_weathered_cut_copper
+ minecraft:semi_weathered_cut_copper_slab
+ minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_amethyst_bud
+ minecraft:tinted_glass
+ minecraft:tuff
+ minecraft:water_cauldron
+ minecraft:waxed_copper
+ minecraft:waxed_cut_copper
+ minecraft:waxed_cut_copper_slab
+ minecraft:waxed_cut_copper_stairs
+ minecraft:waxed_lightly_weathered_copper
+ minecraft:waxed_lightly_weathered_cut_copper
+ minecraft:waxed_lightly_weathered_cut_copper_slab
+ minecraft:waxed_lightly_weathered_cut_copper_stairs
+ minecraft:waxed_semi_weathered_copper
+ minecraft:waxed_semi_weathered_cut_copper
+ minecraft:waxed_semi_weathered_cut_copper_slab
+ minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:weathered_copper_block
+ minecraft:weathered_cut_copper
+ minecraft:weathered_cut_copper_slab
+ minecraft:weathered_cut_copper_stairs
+ minecraft:white_candle
+ minecraft:white_candle_cake
+ minecraft:yellow_candle
+ minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
block_entity_type.txt
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>



<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:axolotl
+ minecraft:glow_item_frame
+ minecraft:glow_squid
```

</details>

<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:amethyst_shard
+ minecraft:axolotl_bucket
+ minecraft:axolotl_spawn_egg
+ minecraft:black_candle
+ minecraft:blue_candle
+ minecraft:brown_candle
+ minecraft:budding_amethyst
+ minecraft:bundle
+ minecraft:calcite
+ minecraft:candle
+ minecraft:copper_block
+ minecraft:copper_ingot
+ minecraft:copper_ore
+ minecraft:cut_copper
+ minecraft:cut_copper_slab
+ minecraft:cut_copper_stairs
+ minecraft:cyan_candle
+ minecraft:dirt_path
+ minecraft:dripstone_block
+ minecraft:glow_ink_sac
+ minecraft:glow_item_frame
+ minecraft:glow_lichen
+ minecraft:glow_squid_spawn_egg
- minecraft:grass_path
+ minecraft:gray_candle
+ minecraft:green_candle
+ minecraft:large_amethyst_bud
+ minecraft:light_blue_candle
+ minecraft:light_gray_candle
+ minecraft:lightly_weathered_copper_block
+ minecraft:lightly_weathered_cut_copper
+ minecraft:lightly_weathered_cut_copper_slab
+ minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:lightning_rod
+ minecraft:lime_candle
+ minecraft:magenta_candle
+ minecraft:medium_amethyst_bud
+ minecraft:orange_candle
+ minecraft:pink_candle
+ minecraft:pointed_dripstone
+ minecraft:powder_snow_bucket
+ minecraft:purple_candle
+ minecraft:red_candle
+ minecraft:sculk_sensor
+ minecraft:semi_weathered_copper_block
+ minecraft:semi_weathered_cut_copper
+ minecraft:semi_weathered_cut_copper_slab
+ minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_amethyst_bud
+ minecraft:spyglass
+ minecraft:tinted_glass
+ minecraft:tuff
+ minecraft:waxed_copper
+ minecraft:waxed_cut_copper
+ minecraft:waxed_cut_copper_slab
+ minecraft:waxed_cut_copper_stairs
+ minecraft:waxed_lightly_weathered_copper
+ minecraft:waxed_lightly_weathered_cut_copper
+ minecraft:waxed_lightly_weathered_cut_copper_slab
+ minecraft:waxed_lightly_weathered_cut_copper_stairs
+ minecraft:waxed_semi_weathered_copper
+ minecraft:waxed_semi_weathered_cut_copper
+ minecraft:waxed_semi_weathered_cut_copper_slab
+ minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:weathered_copper_block
+ minecraft:weathered_cut_copper
+ minecraft:weathered_cut_copper_slab
+ minecraft:weathered_cut_copper_stairs
+ minecraft:white_candle
+ minecraft:yellow_candle
```

</details>
<details>
<summary>
loot_condition_type.txt
</summary>

```diff
+ minecraft:value_check
```

</details>
<details>
<summary>
loot_function_type.txt
</summary>

```diff
+ minecraft:set_banner_pattern
+ minecraft:set_enchantments
```

</details>

<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:is_tempted
+ minecraft:play_dead_ticks
+ minecraft:temptation_cooldown_ticks
+ minecraft:tempting_player
```

</details>



<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:dripping_dripstone_lava
+ minecraft:dripping_dripstone_water
+ minecraft:dust_color_transition
+ minecraft:falling_dripstone_lava
+ minecraft:falling_dripstone_water
+ minecraft:glow
+ minecraft:glow_squid_ink
+ minecraft:small_flame
+ minecraft:snowflake
+ minecraft:vibration
```

</details>
<details>
<summary>
point_of_interest_type.txt
</summary>

```diff
+ minecraft:lightning_rod
```

</details>






<details>
<summary>
sensor_type.txt
</summary>

```diff
+ minecraft:axolotl_hostiles
+ minecraft:axolotl_temptations
```

</details>
<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.amethyst_block.break
+ minecraft:block.amethyst_block.chime
+ minecraft:block.amethyst_block.fall
+ minecraft:block.amethyst_block.hit
+ minecraft:block.amethyst_block.place
+ minecraft:block.amethyst_block.step
+ minecraft:block.amethyst_cluster.break
+ minecraft:block.amethyst_cluster.fall
+ minecraft:block.amethyst_cluster.hit
+ minecraft:block.amethyst_cluster.place
+ minecraft:block.amethyst_cluster.step
+ minecraft:block.cake.add_candle
+ minecraft:block.calcite.break
+ minecraft:block.calcite.fall
+ minecraft:block.calcite.hit
+ minecraft:block.calcite.place
+ minecraft:block.calcite.step
+ minecraft:block.candle.ambient
+ minecraft:block.candle.break
+ minecraft:block.candle.extinguish
+ minecraft:block.candle.fall
+ minecraft:block.candle.hit
+ minecraft:block.candle.place
+ minecraft:block.candle.step
+ minecraft:block.copper.break
+ minecraft:block.copper.fall
+ minecraft:block.copper.hit
+ minecraft:block.copper.place
+ minecraft:block.copper.step
+ minecraft:block.dripstone_block.break
+ minecraft:block.dripstone_block.fall
+ minecraft:block.dripstone_block.hit
+ minecraft:block.dripstone_block.place
+ minecraft:block.dripstone_block.step
+ minecraft:block.large_amethyst_bud.break
+ minecraft:block.large_amethyst_bud.place
+ minecraft:block.medium_amethyst_bud.break
+ minecraft:block.medium_amethyst_bud.place
+ minecraft:block.pointed_dripstone.break
+ minecraft:block.pointed_dripstone.drip_lava
+ minecraft:block.pointed_dripstone.drip_lava_into_cauldron
+ minecraft:block.pointed_dripstone.drip_water
+ minecraft:block.pointed_dripstone.drip_water_into_cauldron
+ minecraft:block.pointed_dripstone.fall
+ minecraft:block.pointed_dripstone.hit
+ minecraft:block.pointed_dripstone.land
+ minecraft:block.pointed_dripstone.place
+ minecraft:block.pointed_dripstone.step
+ minecraft:block.powder_snow.break
+ minecraft:block.powder_snow.fall
+ minecraft:block.powder_snow.hit
+ minecraft:block.powder_snow.place
+ minecraft:block.powder_snow.step
+ minecraft:block.sculk_sensor.break
+ minecraft:block.sculk_sensor.clicking
+ minecraft:block.sculk_sensor.clicking_stop
+ minecraft:block.sculk_sensor.fall
+ minecraft:block.sculk_sensor.hit
+ minecraft:block.sculk_sensor.place
+ minecraft:block.sculk_sensor.step
+ minecraft:block.small_amethyst_bud.break
+ minecraft:block.small_amethyst_bud.place
+ minecraft:block.tuff.break
+ minecraft:block.tuff.fall
+ minecraft:block.tuff.hit
+ minecraft:block.tuff.place
+ minecraft:block.tuff.step
+ minecraft:entity.axolotl.attack
+ minecraft:entity.axolotl.death
+ minecraft:entity.axolotl.hurt
+ minecraft:entity.axolotl.idle_air
+ minecraft:entity.axolotl.idle_water
+ minecraft:entity.axolotl.splash
+ minecraft:entity.axolotl.swim
+ minecraft:entity.glow_squid.ambient
+ minecraft:entity.glow_squid.death
+ minecraft:entity.glow_squid.hurt
+ minecraft:entity.glow_squid.squirt
+ minecraft:entity.minecart.inside.underwater
+ minecraft:entity.player.hurt_freeze
+ minecraft:item.bucket.empty_axolotl
+ minecraft:item.bucket.empty_powder_snow
+ minecraft:item.bucket.fill_axolotl
+ minecraft:item.bucket.fill_powder_snow
+ minecraft:item.dye.use
+ minecraft:item.glow_ink_sac.use
+ minecraft:item.ink_sac.use
+ minecraft:item.spyglass.stop_using
+ minecraft:item.spyglass.use
```

</details>









<details>
<summary>
worldgen/feature.txt
</summary>

```diff
+ minecraft:dripstone_cluster
+ minecraft:geode
+ minecraft:glow_lichen
+ minecraft:large_dripstone
+ minecraft:small_dripstone
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/game_event.json
+ universal_tags/loot_nbt_provider_type.json
+ universal_tags/loot_number_provider_type.json
+ universal_tags/loot_score_provider_type.json
+ universal_tags/position_source_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:budding_amethyst
+ minecraft:powder_snow
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:black_candle
+ minecraft:black_candle_cake
+ minecraft:blue_candle
+ minecraft:blue_candle_cake
+ minecraft:brown_candle
+ minecraft:brown_candle_cake
+ minecraft:calcite
+ minecraft:candle
+ minecraft:candle_cake
+ minecraft:copper_block
+ minecraft:copper_ore
+ minecraft:cut_copper
+ minecraft:cut_copper_slab
+ minecraft:cut_copper_stairs
+ minecraft:cyan_candle
+ minecraft:cyan_candle_cake
+ minecraft:dirt_path
+ minecraft:dripstone_block
+ minecraft:glow_lichen
- minecraft:grass_path
+ minecraft:gray_candle
+ minecraft:gray_candle_cake
+ minecraft:green_candle
+ minecraft:green_candle_cake
+ minecraft:large_amethyst_bud
+ minecraft:lava_cauldron
+ minecraft:light_blue_candle
+ minecraft:light_blue_candle_cake
+ minecraft:light_gray_candle
+ minecraft:light_gray_candle_cake
+ minecraft:lightly_weathered_copper_block
+ minecraft:lightly_weathered_cut_copper
+ minecraft:lightly_weathered_cut_copper_slab
+ minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:lightning_rod
+ minecraft:lime_candle
+ minecraft:lime_candle_cake
+ minecraft:magenta_candle
+ minecraft:magenta_candle_cake
+ minecraft:medium_amethyst_bud
+ minecraft:orange_candle
+ minecraft:orange_candle_cake
+ minecraft:pink_candle
+ minecraft:pink_candle_cake
+ minecraft:pointed_dripstone
+ minecraft:powder_snow_cauldron
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
+ minecraft:sculk_sensor
+ minecraft:semi_weathered_copper_block
+ minecraft:semi_weathered_cut_copper
+ minecraft:semi_weathered_cut_copper_slab
+ minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_amethyst_bud
+ minecraft:tinted_glass
+ minecraft:tuff
+ minecraft:water_cauldron
+ minecraft:waxed_copper
+ minecraft:waxed_cut_copper
+ minecraft:waxed_cut_copper_slab
+ minecraft:waxed_cut_copper_stairs
+ minecraft:waxed_lightly_weathered_copper
+ minecraft:waxed_lightly_weathered_cut_copper
+ minecraft:waxed_lightly_weathered_cut_copper_slab
+ minecraft:waxed_lightly_weathered_cut_copper_stairs
+ minecraft:waxed_semi_weathered_copper
+ minecraft:waxed_semi_weathered_cut_copper
+ minecraft:waxed_semi_weathered_cut_copper_slab
+ minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:weathered_copper_block
+ minecraft:weathered_cut_copper
+ minecraft:weathered_cut_copper_slab
+ minecraft:weathered_cut_copper_stairs
+ minecraft:white_candle
+ minecraft:white_candle_cake
+ minecraft:yellow_candle
+ minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:axolotl
+ minecraft:glow_item_frame
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:glow_squid
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:axolotl
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:budding_amethyst
+ minecraft:powder_snow
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:play_dead
```

</details>

<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:black_candle
+ minecraft:black_candle_cake
+ minecraft:blue_candle
+ minecraft:blue_candle_cake
+ minecraft:brown_candle
+ minecraft:brown_candle_cake
+ minecraft:budding_amethyst
+ minecraft:calcite
+ minecraft:candle
+ minecraft:candle_cake
+ minecraft:copper_block
+ minecraft:copper_ore
+ minecraft:cut_copper
+ minecraft:cut_copper_slab
+ minecraft:cut_copper_stairs
+ minecraft:cyan_candle
+ minecraft:cyan_candle_cake
+ minecraft:dirt_path
+ minecraft:dripstone_block
+ minecraft:glow_lichen
- minecraft:grass_path
+ minecraft:gray_candle
+ minecraft:gray_candle_cake
+ minecraft:green_candle
+ minecraft:green_candle_cake
+ minecraft:large_amethyst_bud
+ minecraft:lava_cauldron
+ minecraft:light_blue_candle
+ minecraft:light_blue_candle_cake
+ minecraft:light_gray_candle
+ minecraft:light_gray_candle_cake
+ minecraft:lightly_weathered_copper_block
+ minecraft:lightly_weathered_cut_copper
+ minecraft:lightly_weathered_cut_copper_slab
+ minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:lightning_rod
+ minecraft:lime_candle
+ minecraft:lime_candle_cake
+ minecraft:magenta_candle
+ minecraft:magenta_candle_cake
+ minecraft:medium_amethyst_bud
+ minecraft:orange_candle
+ minecraft:orange_candle_cake
+ minecraft:pink_candle
+ minecraft:pink_candle_cake
+ minecraft:pointed_dripstone
+ minecraft:powder_snow
+ minecraft:powder_snow_cauldron
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
+ minecraft:sculk_sensor
+ minecraft:semi_weathered_copper_block
+ minecraft:semi_weathered_cut_copper
+ minecraft:semi_weathered_cut_copper_slab
+ minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_amethyst_bud
+ minecraft:tinted_glass
+ minecraft:tuff
+ minecraft:water_cauldron
+ minecraft:waxed_copper
+ minecraft:waxed_cut_copper
+ minecraft:waxed_cut_copper_slab
+ minecraft:waxed_cut_copper_stairs
+ minecraft:waxed_lightly_weathered_copper
+ minecraft:waxed_lightly_weathered_cut_copper
+ minecraft:waxed_lightly_weathered_cut_copper_slab
+ minecraft:waxed_lightly_weathered_cut_copper_stairs
+ minecraft:waxed_semi_weathered_copper
+ minecraft:waxed_semi_weathered_cut_copper
+ minecraft:waxed_semi_weathered_cut_copper_slab
+ minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:weathered_copper_block
+ minecraft:weathered_cut_copper
+ minecraft:weathered_cut_copper_slab
+ minecraft:weathered_cut_copper_stairs
+ minecraft:white_candle
+ minecraft:white_candle_cake
+ minecraft:yellow_candle
+ minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:sculk_sensor
```

</details>



<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:axolotl
+ minecraft:glow_item_frame
+ minecraft:glow_squid
```

</details>

<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:amethyst_shard
+ minecraft:axolotl_bucket
+ minecraft:axolotl_spawn_egg
+ minecraft:black_candle
+ minecraft:blue_candle
+ minecraft:brown_candle
+ minecraft:budding_amethyst
+ minecraft:bundle
+ minecraft:calcite
+ minecraft:candle
+ minecraft:copper_block
+ minecraft:copper_ingot
+ minecraft:copper_ore
+ minecraft:cut_copper
+ minecraft:cut_copper_slab
+ minecraft:cut_copper_stairs
+ minecraft:cyan_candle
+ minecraft:dirt_path
+ minecraft:dripstone_block
+ minecraft:glow_ink_sac
+ minecraft:glow_item_frame
+ minecraft:glow_lichen
+ minecraft:glow_squid_spawn_egg
- minecraft:grass_path
+ minecraft:gray_candle
+ minecraft:green_candle
+ minecraft:large_amethyst_bud
+ minecraft:light_blue_candle
+ minecraft:light_gray_candle
+ minecraft:lightly_weathered_copper_block
+ minecraft:lightly_weathered_cut_copper
+ minecraft:lightly_weathered_cut_copper_slab
+ minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:lightning_rod
+ minecraft:lime_candle
+ minecraft:magenta_candle
+ minecraft:medium_amethyst_bud
+ minecraft:orange_candle
+ minecraft:pink_candle
+ minecraft:pointed_dripstone
+ minecraft:powder_snow_bucket
+ minecraft:purple_candle
+ minecraft:red_candle
+ minecraft:sculk_sensor
+ minecraft:semi_weathered_copper_block
+ minecraft:semi_weathered_cut_copper
+ minecraft:semi_weathered_cut_copper_slab
+ minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_amethyst_bud
+ minecraft:spyglass
+ minecraft:tinted_glass
+ minecraft:tuff
+ minecraft:waxed_copper
+ minecraft:waxed_cut_copper
+ minecraft:waxed_cut_copper_slab
+ minecraft:waxed_cut_copper_stairs
+ minecraft:waxed_lightly_weathered_copper
+ minecraft:waxed_lightly_weathered_cut_copper
+ minecraft:waxed_lightly_weathered_cut_copper_slab
+ minecraft:waxed_lightly_weathered_cut_copper_stairs
+ minecraft:waxed_semi_weathered_copper
+ minecraft:waxed_semi_weathered_cut_copper
+ minecraft:waxed_semi_weathered_cut_copper_slab
+ minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:weathered_copper_block
+ minecraft:weathered_cut_copper
+ minecraft:weathered_cut_copper_slab
+ minecraft:weathered_cut_copper_stairs
+ minecraft:white_candle
+ minecraft:yellow_candle
```

</details>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
+ minecraft:value_check
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:set_banner_pattern
+ minecraft:set_enchantments
```

</details>

<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:is_tempted
+ minecraft:play_dead_ticks
+ minecraft:temptation_cooldown_ticks
+ minecraft:tempting_player
```

</details>



<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:dripping_dripstone_lava
+ minecraft:dripping_dripstone_water
+ minecraft:dust_color_transition
+ minecraft:falling_dripstone_lava
+ minecraft:falling_dripstone_water
+ minecraft:glow
+ minecraft:glow_squid_ink
+ minecraft:small_flame
+ minecraft:snowflake
+ minecraft:vibration
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
+ minecraft:lightning_rod
```

</details>






<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:axolotl_hostiles
+ minecraft:axolotl_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.amethyst_block.break
+ minecraft:block.amethyst_block.chime
+ minecraft:block.amethyst_block.fall
+ minecraft:block.amethyst_block.hit
+ minecraft:block.amethyst_block.place
+ minecraft:block.amethyst_block.step
+ minecraft:block.amethyst_cluster.break
+ minecraft:block.amethyst_cluster.fall
+ minecraft:block.amethyst_cluster.hit
+ minecraft:block.amethyst_cluster.place
+ minecraft:block.amethyst_cluster.step
+ minecraft:block.cake.add_candle
+ minecraft:block.calcite.break
+ minecraft:block.calcite.fall
+ minecraft:block.calcite.hit
+ minecraft:block.calcite.place
+ minecraft:block.calcite.step
+ minecraft:block.candle.ambient
+ minecraft:block.candle.break
+ minecraft:block.candle.extinguish
+ minecraft:block.candle.fall
+ minecraft:block.candle.hit
+ minecraft:block.candle.place
+ minecraft:block.candle.step
+ minecraft:block.copper.break
+ minecraft:block.copper.fall
+ minecraft:block.copper.hit
+ minecraft:block.copper.place
+ minecraft:block.copper.step
+ minecraft:block.dripstone_block.break
+ minecraft:block.dripstone_block.fall
+ minecraft:block.dripstone_block.hit
+ minecraft:block.dripstone_block.place
+ minecraft:block.dripstone_block.step
+ minecraft:block.large_amethyst_bud.break
+ minecraft:block.large_amethyst_bud.place
+ minecraft:block.medium_amethyst_bud.break
+ minecraft:block.medium_amethyst_bud.place
+ minecraft:block.pointed_dripstone.break
+ minecraft:block.pointed_dripstone.drip_lava
+ minecraft:block.pointed_dripstone.drip_lava_into_cauldron
+ minecraft:block.pointed_dripstone.drip_water
+ minecraft:block.pointed_dripstone.drip_water_into_cauldron
+ minecraft:block.pointed_dripstone.fall
+ minecraft:block.pointed_dripstone.hit
+ minecraft:block.pointed_dripstone.land
+ minecraft:block.pointed_dripstone.place
+ minecraft:block.pointed_dripstone.step
+ minecraft:block.powder_snow.break
+ minecraft:block.powder_snow.fall
+ minecraft:block.powder_snow.hit
+ minecraft:block.powder_snow.place
+ minecraft:block.powder_snow.step
+ minecraft:block.sculk_sensor.break
+ minecraft:block.sculk_sensor.clicking
+ minecraft:block.sculk_sensor.clicking_stop
+ minecraft:block.sculk_sensor.fall
+ minecraft:block.sculk_sensor.hit
+ minecraft:block.sculk_sensor.place
+ minecraft:block.sculk_sensor.step
+ minecraft:block.small_amethyst_bud.break
+ minecraft:block.small_amethyst_bud.place
+ minecraft:block.tuff.break
+ minecraft:block.tuff.fall
+ minecraft:block.tuff.hit
+ minecraft:block.tuff.place
+ minecraft:block.tuff.step
+ minecraft:entity.axolotl.attack
+ minecraft:entity.axolotl.death
+ minecraft:entity.axolotl.hurt
+ minecraft:entity.axolotl.idle_air
+ minecraft:entity.axolotl.idle_water
+ minecraft:entity.axolotl.splash
+ minecraft:entity.axolotl.swim
+ minecraft:entity.glow_squid.ambient
+ minecraft:entity.glow_squid.death
+ minecraft:entity.glow_squid.hurt
+ minecraft:entity.glow_squid.squirt
+ minecraft:entity.minecart.inside.underwater
+ minecraft:entity.player.hurt_freeze
+ minecraft:item.bucket.empty_axolotl
+ minecraft:item.bucket.empty_powder_snow
+ minecraft:item.bucket.fill_axolotl
+ minecraft:item.bucket.fill_powder_snow
+ minecraft:item.dye.use
+ minecraft:item.glow_ink_sac.use
+ minecraft:item.ink_sac.use
+ minecraft:item.spyglass.stop_using
+ minecraft:item.spyglass.use
```

</details>









<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:dripstone_cluster
+ minecraft:geode
+ minecraft:glow_lichen
+ minecraft:large_dripstone
+ minecraft:small_dripstone
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ item.json
- replaceitem.json
```

</details>






















<details>
<summary>
gamerule
</summary>

```diff
+ gamerule freezeDamage <value: bool>
+ gamerule playersSleepingPercentage <value: integer>
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ amethyst_block.json
+ black_candle.json
+ blue_candle.json
+ brown_candle.json
+ bundle.json
+ candle.json
+ copper_block.json
+ copper_ingot_from_blasting.json
+ copper_ingot_from_copper_block.json
+ copper_ingot.json
+ cut_copper_slab.json
+ cut_copper_stairs.json
+ cut_copper.json
+ cyan_candle.json
+ dripstone_block.json
+ firework_rocket_simple.json
+ glow_item_frame.json
+ gray_candle.json
+ green_candle.json
+ light_blue_candle.json
+ light_gray_candle.json
+ lightly_weathered_cut_copper_slab.json
+ lightly_weathered_cut_copper_stairs.json
+ lightly_weathered_cut_copper.json
+ lightning_rod.json
+ lime_candle.json
+ magenta_candle.json
+ orange_candle.json
+ pink_candle.json
+ purple_candle.json
+ red_candle.json
+ semi_weathered_cut_copper_slab.json
+ semi_weathered_cut_copper_stairs.json
+ semi_weathered_cut_copper.json
+ spyglass.json
+ tinted_glass.json
+ waxed_copper_cut_slab_from_honeycomb.json
+ waxed_copper_cut_stairs_from_honeycomb.json
+ waxed_copper.json
+ waxed_cut_copper_from_honeycomb.json
+ waxed_cut_copper_slab.json
+ waxed_cut_copper_stairs.json
+ waxed_cut_copper.json
+ waxed_lightly_weathered_copper.json
+ waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_slab.json
+ waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_stairs.json
+ waxed_lightly_weathered_cut_copper.json
+ waxed_semi_weathered_copper.json
+ waxed_semi_weathered_cut_copper_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_slab.json
+ waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_stairs.json
+ waxed_semi_weathered_cut_copper.json
+ weathered_cut_copper_slab.json
+ weathered_cut_copper_stairs.json
+ weathered_cut_copper.json
+ white_candle.json
+ yellow_candle.json
```

</details>







<details>
<summary>
acacia_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>































<details>
<summary>
birch_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>



















































































































































<details>
<summary>
crimson_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>


































<details>
<summary>
dark_oak_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>





































































































































































<details>
<summary>
jungle_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>












































































































































<details>
<summary>
oak_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>








































































































































































































































<details>
<summary>
spruce_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>



























































<details>
<summary>
warped_sign.json
</summary>

```
Group: sign -> wooden_sign
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advMode.mode: Mode
+ advMode.trackOutput: Track output
+ advMode.triggering: Triggering
+ advMode.type: Type
+ argument.angle.invalid: Invalid angle
+ biome.minecraft.dripstone_caves: Dripstone Caves
+ block.minecraft.amethyst_block: Block of Amethyst
+ block.minecraft.amethyst_cluster: Amethyst Cluster
+ block.minecraft.banner.base.black: Fully Black Field
+ block.minecraft.banner.base.blue: Fully Blue Field
+ block.minecraft.banner.base.brown: Fully Brown Field
+ block.minecraft.banner.base.cyan: Fully Cyan Field
+ block.minecraft.banner.base.gray: Fully Gray Field
+ block.minecraft.banner.base.green: Fully Green Field
+ block.minecraft.banner.base.light_blue: Fully Light Blue Field
+ block.minecraft.banner.base.light_gray: Fully Light Gray Field
+ block.minecraft.banner.base.lime: Fully Lime Field
+ block.minecraft.banner.base.magenta: Fully Magenta Field
+ block.minecraft.banner.base.orange: Fully Orange Field
+ block.minecraft.banner.base.pink: Fully Pink Field
+ block.minecraft.banner.base.purple: Fully Purple Field
+ block.minecraft.banner.base.red: Fully Red Field
+ block.minecraft.banner.base.white: Fully White Field
+ block.minecraft.banner.base.yellow: Fully Yellow Field
+ block.minecraft.black_candle_cake: Black Candle Cake
+ block.minecraft.black_candle: Black Candle
+ block.minecraft.blue_candle_cake: Blue Candle Cake
+ block.minecraft.blue_candle: Blue Candle
+ block.minecraft.brown_candle_cake: Brown Candle Cake
+ block.minecraft.brown_candle: Brown Candle
+ block.minecraft.budding_amethyst: Budding Amethyst
+ block.minecraft.calcite: Calcite
+ block.minecraft.candle_cake: Candle Cake
+ block.minecraft.candle: Candle
+ block.minecraft.copper_block: Copper Block
+ block.minecraft.copper_ore: Copper Ore
+ block.minecraft.cut_copper_slab: Cut Copper Slab
+ block.minecraft.cut_copper_stairs: Cut Copper Stairs
+ block.minecraft.cut_copper: Cut Copper
+ block.minecraft.cyan_candle_cake: Cyan Candle Cake
+ block.minecraft.cyan_candle: Cyan Candle
+ block.minecraft.dirt_path: Dirt Path
+ block.minecraft.dripstone_block: Dripstone Block
+ block.minecraft.glow_lichen: Glow Lichen
- block.minecraft.grass_path: Grass Path
+ block.minecraft.gray_candle_cake: Gray Candle Cake
+ block.minecraft.gray_candle: Gray Candle
+ block.minecraft.green_candle_cake: Green Candle Cake
+ block.minecraft.green_candle: Green Candle
+ block.minecraft.large_amethyst_bud: Large Amethyst Bud
+ block.minecraft.lava_cauldron: Lava Cauldron
+ block.minecraft.light_blue_candle_cake: Light Blue Candle Cake
+ block.minecraft.light_blue_candle: Light Blue Candle
+ block.minecraft.light_gray_candle_cake: Light Gray Candle Cake
+ block.minecraft.light_gray_candle: Light Gray Candle
+ block.minecraft.lightly_weathered_copper_block: Lightly Weathered Copper Block
+ block.minecraft.lightly_weathered_cut_copper_slab: Lightly Weathered Cut Copper Slab
+ block.minecraft.lightly_weathered_cut_copper_stairs: Lightly Weathered Cut Copper Stairs
+ block.minecraft.lightly_weathered_cut_copper: Lightly Weathered Cut Copper
+ block.minecraft.lightning_rod: Lightning Rod
+ block.minecraft.lime_candle_cake: Lime Candle Cake
+ block.minecraft.lime_candle: Lime Candle
+ block.minecraft.magenta_candle_cake: Magenta Candle Cake
+ block.minecraft.magenta_candle: Magenta Candle
+ block.minecraft.medium_amethyst_bud: Medium Amethyst Bud
+ block.minecraft.orange_candle_cake: Orange Candle Cake
+ block.minecraft.orange_candle: Orange Candle
+ block.minecraft.pink_candle_cake: Pink Candle Cake
+ block.minecraft.pink_candle: Pink Candle
+ block.minecraft.pointed_dripstone: Pointed Dripstone
+ block.minecraft.powder_snow_cauldron: Powder Snow Cauldron
+ block.minecraft.powder_snow: Powder Snow
+ block.minecraft.purple_candle_cake: Purple Candle Cake
+ block.minecraft.purple_candle: Purple Candle
+ block.minecraft.red_candle_cake: Red Candle Cake
+ block.minecraft.red_candle: Red Candle
+ block.minecraft.sculk_sensor: Sculk Sensor
+ block.minecraft.semi_weathered_copper_block: Semi-Weathered Copper Block
+ block.minecraft.semi_weathered_cut_copper_slab: Semi Weathered Cut Copper Slab
+ block.minecraft.semi_weathered_cut_copper_stairs: Semi-Weathered Cut Copper Stairs
+ block.minecraft.semi_weathered_cut_copper: Semi-Weathered Cut Copper
+ block.minecraft.small_amethyst_bud: Small Amethyst Bud
+ block.minecraft.tinted_glass: Tinted Glass
+ block.minecraft.tuff: Tuff
+ block.minecraft.water_cauldron: Water Cauldron
+ block.minecraft.waxed_copper: Waxed Copper
+ block.minecraft.waxed_cut_copper_slab: Waxed Cut Copper Slab
+ block.minecraft.waxed_cut_copper_stairs: Waxed Cut Copper Stairs
+ block.minecraft.waxed_cut_copper: Waxed Cut Copper
+ block.minecraft.waxed_lightly_weathered_copper_block: Waxed Lightly Weathered Copper Block
+ block.minecraft.waxed_lightly_weathered_copper: Waxed Lightly Weathered Copper
+ block.minecraft.waxed_lightly_weathered_cut_copper_slab: Waxed Lightly Weathered Cut Copper Slab
+ block.minecraft.waxed_lightly_weathered_cut_copper_stairs: Waxed Lightly Weathered Cut Copper Stairs
+ block.minecraft.waxed_lightly_weathered_cut_copper: Waxed Lightly Weathered Cut Copper
+ block.minecraft.waxed_semi_weathered_copper_block: Waxed Semi-Weathered Copper Block
+ block.minecraft.waxed_semi_weathered_copper: Waxed Semi-Weathered Copper
+ block.minecraft.waxed_semi_weathered_cut_copper_slab: Waxed Semi Weathered Cut Copper Slab
+ block.minecraft.waxed_semi_weathered_cut_copper_stairs: Waxed Semi-Weathered Cut Copper Stairs
+ block.minecraft.waxed_semi_weathered_cut_copper: Waxed Semi-Weathered Cut Copper
+ block.minecraft.weathered_copper_block: Weathered Copper BlocK
+ block.minecraft.weathered_cut_copper_slab: Weathered Cut Copper Slab
+ block.minecraft.weathered_cut_copper_stairs: Weathered Cut Copper Stairs
+ block.minecraft.weathered_cut_copper: Weathered Cut Copper
+ block.minecraft.white_candle_cake: White Candle Cake
+ block.minecraft.white_candle: White Candle
+ block.minecraft.yellow_candle_cake: Yellow Candle Cake
+ block.minecraft.yellow_candle: Yellow Candle
+ commands.item.block.set.success: Replaced a slot at %s, %s, %s with %s
+ commands.item.entity.set.success.multiple: Replaced a slot on %s entities with %s
+ commands.item.entity.set.success.single: Replaced a slot on %s with %s
+ commands.item.source.no_such_slot: The source does not have slot %s
+ commands.item.source.not_a_container: Source position %s, %s, %s is not a container
+ commands.item.target.no_changed.known_item: No targets accepted item %s into slot %s
+ commands.item.target.no_changes: No targets accepted item into slot %s
+ commands.item.target.no_such_slot: The target does not have slot %s
+ commands.item.target.not_a_container: Target position %s, %s, %s is not a container
- commands.replaceitem.block.failed: The target block is not a container
- commands.replaceitem.block.success: Replaced a slot at %s, %s, %s with %s
- commands.replaceitem.entity.failed: Could not put %s in slot %s
- commands.replaceitem.entity.success.multiple: Replaced a slot on %s entities with %s
- commands.replaceitem.entity.success.single: Replaced a slot on %s with %s
- commands.replaceitem.slot.inapplicable: The target does not have slot %s
+ dataPack.vanilla.description: The default data for Minecraft
+ death.attack.fallingStalactite: %1$s was skewered by a falling stalactite
+ death.attack.fallingStalactite.player: %1$s was skewered by a falling stalactite whilst fighting %2$s
+ death.attack.freeze: %1$s froze to death
+ death.attack.freeze.player: %1$s was frozen to death by %2$s
+ death.attack.stalagmite: %1$s was impaled on a stalagmite
+ death.attack.stalagmite.player: %1$s was impaled on a stalagmite whilst fighting %2$s
+ entity.minecraft.axolotl: Axolotl
+ entity.minecraft.glow_item_frame: Glow Item Frame
+ entity.minecraft.glow_squid: Glow Squid
+ gamerule.freezeDamage: Deal freeze damage
+ gamerule.playersSleepingPercentage: Sleep percentage
+ gamerule.playersSleepingPercentage.description: The percentage of players who must be sleeping to skip the night.
+ item_modifier.unknown: Unknown item modifier: %s
+ item.minecraft.amethyst_shard: Amethyst Shard
+ item.minecraft.axolotl_bucket: Bucket of Axolotl
+ item.minecraft.axolotl_spawn_egg: Axolotl Spawn Egg
+ item.minecraft.bundle: Bundle
+ item.minecraft.bundle.fullness: %s/%s
+ item.minecraft.copper_ingot: Copper Ingot
+ item.minecraft.glow_ink_sac: Glow Ink Sac
+ item.minecraft.glow_item_frame: Glow Item Frame
+ item.minecraft.glow_squid_spawn_egg: Glow Squid Spawn Egg
+ item.minecraft.powder_snow_bucket: Powder Snow Bucket
+ item.minecraft.spyglass: Spyglass
+ mirror.front_back: ↑ ↓
+ mirror.left_right: ← →
+ mirror.none: |
+ multiplayer.requiredTexturePrompt.disconnect: Server requires a custom resource pack
+ multiplayer.requiredTexturePrompt.line1: This server requires the use of a custom resource pack.
+ multiplayer.requiredTexturePrompt.line2: Rejecting a custom resource pack will disconnect you from this server.
- options.fovEffectScale.off: Off
- options.screenEffectScale.off: Off
- options.vbo: Use VBOs
+ resourcePack.vanilla.description: The default resources for Minecraft
- selectWorld.backupQuestion: Do you really want to load this world?
+ selectWorld.backupQuestion.downgrade: Downgrading a world is not supported
+ selectWorld.backupQuestion.snapshot: Do you really want to load this world?
- selectWorld.backupWarning: This world was last played in version %s; you are on version %s. Please make a backup in case you experience world corruptions!
+ selectWorld.backupWarning.downgrade: This world was last played in version %s; you are on version %s. Downgrading a world could cause corruption - we cannot guarantee that it will load or work. If you still want to continue, please make a backup!
+ selectWorld.backupWarning.snapshot: This world was last played in version %s; you are on version %s. Please make a backup in case you experience world corruptions!
+ sleep.not_possible: No amount of rest can pass this night
+ sleep.players_sleeping: %s/%s players sleeping
+ sleep.skipping_night: Sleeping through this night
+ subtitles.block.cake.add_candle: Cake squishes
+ subtitles.block.candle.crackle: Candle crackles
+ subtitles.block.pointed_dripstone.drip_lava_into_cauldron: Lava drips into Cauldron
+ subtitles.block.pointed_dripstone.drip_lava: Lava drips
+ subtitles.block.pointed_dripstone.drip_water_into_cauldron: Water drips into Cauldron
+ subtitles.block.pointed_dripstone.drip_water: Water drips
+ subtitles.block.pointed_dripstone.land: Stalactite crashes down
+ subtitles.block.sculk_sensor.clicking_stop: Sculk Sensor stops clicking
+ subtitles.block.sculk_sensor.clicking: Sculk Sensor starts clicking
+ subtitles.entity.axolotl.attack: Axolotl attacks
+ subtitles.entity.axolotl.death: Axolotl dies
+ subtitles.entity.axolotl.hurt: Axolotl hurts
+ subtitles.entity.axolotl.idle_air: Axolotl chirps
+ subtitles.entity.axolotl.idle_water: Axolotl chirps
+ subtitles.entity.axolotl.splash: Axolotl splashes
+ subtitles.entity.axolotl.swim: Axolotl swims
+ subtitles.entity.glow_squid.ambient: Glow Squid swims
+ subtitles.entity.glow_squid.death: Glow Squid dies
+ subtitles.entity.glow_squid.hurt: Glow Squid hurts
+ subtitles.entity.glow_squid.squirt: Glow Squid shoots ink
+ subtitles.entity.player.freeze_hurt: Player freezes
+ subtitles.item.bucket.fill_axolotl: Axolotl scooped
+ subtitles.item.dye.use: Dye stains
+ subtitles.item.glow_ink_sac.use: Glow Ink Sac splotches
+ subtitles.item.ink_sac.use: Ink Sac splotches
+ subtitles.item.spyglass.stop_using: Spyglass retracts
+ subtitles.item.spyglass.use: Spyglass expands
```

</details>
<details>
<summary>
Changes
</summary>

```
selectWorld.mapType: World Type:
disconnect.loginFailedInfo.serversUnavailable: The authentication servers are currently down for maintenancenot reachable. Please try again.
options.vsync: Use VSync
block.minecraft.lapis_block: Block of Lapis Lazuli Block
subtitles.entity.shulker_bullet.hit: Shulker bBullet explodes
subtitles.entity.shulker_bullet.hurt: Shulker bBullet breaks
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
+ reports/biomes/dripstone_caves.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/amethyst_block.json
+ minecraft/advancements/recipes/building_blocks/copper_block.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/cut_copper.json
+ minecraft/advancements/recipes/building_blocks/dripstone_block.json
+ minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/tinted_glass.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_cut_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_cut_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper.json
+ minecraft/advancements/recipes/decorations/black_candle.json
+ minecraft/advancements/recipes/decorations/blue_candle.json
+ minecraft/advancements/recipes/decorations/brown_candle.json
+ minecraft/advancements/recipes/decorations/candle.json
+ minecraft/advancements/recipes/decorations/cyan_candle.json
+ minecraft/advancements/recipes/decorations/glow_item_frame.json
+ minecraft/advancements/recipes/decorations/gray_candle.json
+ minecraft/advancements/recipes/decorations/green_candle.json
+ minecraft/advancements/recipes/decorations/light_blue_candle.json
+ minecraft/advancements/recipes/decorations/light_gray_candle.json
+ minecraft/advancements/recipes/decorations/lime_candle.json
+ minecraft/advancements/recipes/decorations/magenta_candle.json
+ minecraft/advancements/recipes/decorations/orange_candle.json
+ minecraft/advancements/recipes/decorations/pink_candle.json
+ minecraft/advancements/recipes/decorations/purple_candle.json
+ minecraft/advancements/recipes/decorations/red_candle.json
+ minecraft/advancements/recipes/decorations/white_candle.json
+ minecraft/advancements/recipes/decorations/yellow_candle.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/copper_ingot_from_copper_block.json
+ minecraft/advancements/recipes/misc/copper_ingot.json
+ minecraft/advancements/recipes/misc/firework_rocket_simple.json
+ minecraft/advancements/recipes/redstone/lightning_rod.json
+ minecraft/advancements/recipes/tools/bundle.json
+ minecraft/advancements/recipes/tools/spyglass.json
+ minecraft/loot_tables/blocks/amethyst_block.json
+ minecraft/loot_tables/blocks/amethyst_cluster.json
+ minecraft/loot_tables/blocks/black_candle_cake.json
+ minecraft/loot_tables/blocks/black_candle.json
+ minecraft/loot_tables/blocks/blue_candle_cake.json
+ minecraft/loot_tables/blocks/blue_candle.json
+ minecraft/loot_tables/blocks/brown_candle_cake.json
+ minecraft/loot_tables/blocks/brown_candle.json
+ minecraft/loot_tables/blocks/budding_amethyst.json
+ minecraft/loot_tables/blocks/calcite.json
+ minecraft/loot_tables/blocks/candle_cake.json
+ minecraft/loot_tables/blocks/candle.json
+ minecraft/loot_tables/blocks/copper_block.json
+ minecraft/loot_tables/blocks/copper_ore.json
+ minecraft/loot_tables/blocks/cut_copper_slab.json
+ minecraft/loot_tables/blocks/cut_copper_stairs.json
+ minecraft/loot_tables/blocks/cut_copper.json
+ minecraft/loot_tables/blocks/cyan_candle_cake.json
+ minecraft/loot_tables/blocks/cyan_candle.json
+ minecraft/loot_tables/blocks/dirt_path.json
+ minecraft/loot_tables/blocks/dripstone_block.json
+ minecraft/loot_tables/blocks/glow_lichen.json
- minecraft/loot_tables/blocks/grass_path.json
+ minecraft/loot_tables/blocks/gray_candle_cake.json
+ minecraft/loot_tables/blocks/gray_candle.json
+ minecraft/loot_tables/blocks/green_candle_cake.json
+ minecraft/loot_tables/blocks/green_candle.json
+ minecraft/loot_tables/blocks/large_amethyst_bud.json
+ minecraft/loot_tables/blocks/lava_cauldron.json
+ minecraft/loot_tables/blocks/light_blue_candle_cake.json
+ minecraft/loot_tables/blocks/light_blue_candle.json
+ minecraft/loot_tables/blocks/light_gray_candle_cake.json
+ minecraft/loot_tables/blocks/light_gray_candle.json
+ minecraft/loot_tables/blocks/lightly_weathered_copper_block.json
+ minecraft/loot_tables/blocks/lightly_weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/lightly_weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/lightly_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/lightning_rod.json
+ minecraft/loot_tables/blocks/lime_candle_cake.json
+ minecraft/loot_tables/blocks/lime_candle.json
+ minecraft/loot_tables/blocks/magenta_candle_cake.json
+ minecraft/loot_tables/blocks/magenta_candle.json
+ minecraft/loot_tables/blocks/medium_amethyst_bud.json
+ minecraft/loot_tables/blocks/orange_candle_cake.json
+ minecraft/loot_tables/blocks/orange_candle.json
+ minecraft/loot_tables/blocks/pink_candle_cake.json
+ minecraft/loot_tables/blocks/pink_candle.json
+ minecraft/loot_tables/blocks/pointed_dripstone.json
+ minecraft/loot_tables/blocks/powder_snow_cauldron.json
+ minecraft/loot_tables/blocks/powder_snow.json
+ minecraft/loot_tables/blocks/purple_candle_cake.json
+ minecraft/loot_tables/blocks/purple_candle.json
+ minecraft/loot_tables/blocks/red_candle_cake.json
+ minecraft/loot_tables/blocks/red_candle.json
+ minecraft/loot_tables/blocks/sculk_sensor.json
+ minecraft/loot_tables/blocks/semi_weathered_copper_block.json
+ minecraft/loot_tables/blocks/semi_weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/semi_weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/semi_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/small_amethyst_bud.json
+ minecraft/loot_tables/blocks/tinted_glass.json
+ minecraft/loot_tables/blocks/tuff.json
+ minecraft/loot_tables/blocks/water_cauldron.json
+ minecraft/loot_tables/blocks/waxed_copper.json
+ minecraft/loot_tables/blocks/waxed_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_cut_copper.json
+ minecraft/loot_tables/blocks/waxed_lightly_weathered_copper.json
+ minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/waxed_semi_weathered_copper.json
+ minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/weathered_copper_block.json
+ minecraft/loot_tables/blocks/weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/weathered_cut_copper.json
+ minecraft/loot_tables/blocks/white_candle_cake.json
+ minecraft/loot_tables/blocks/white_candle.json
+ minecraft/loot_tables/blocks/yellow_candle_cake.json
+ minecraft/loot_tables/blocks/yellow_candle.json
+ minecraft/loot_tables/entities/axolotl.json
+ minecraft/loot_tables/entities/glow_squid.json
+ minecraft/recipes/amethyst_block.json
+ minecraft/recipes/black_candle.json
+ minecraft/recipes/blue_candle.json
+ minecraft/recipes/brown_candle.json
+ minecraft/recipes/bundle.json
+ minecraft/recipes/candle.json
+ minecraft/recipes/copper_block.json
+ minecraft/recipes/copper_ingot_from_blasting.json
+ minecraft/recipes/copper_ingot_from_copper_block.json
+ minecraft/recipes/copper_ingot.json
+ minecraft/recipes/cut_copper_slab.json
+ minecraft/recipes/cut_copper_stairs.json
+ minecraft/recipes/cut_copper.json
+ minecraft/recipes/cyan_candle.json
+ minecraft/recipes/dripstone_block.json
+ minecraft/recipes/firework_rocket_simple.json
+ minecraft/recipes/glow_item_frame.json
+ minecraft/recipes/gray_candle.json
+ minecraft/recipes/green_candle.json
+ minecraft/recipes/light_blue_candle.json
+ minecraft/recipes/light_gray_candle.json
+ minecraft/recipes/lightly_weathered_cut_copper_slab.json
+ minecraft/recipes/lightly_weathered_cut_copper_stairs.json
+ minecraft/recipes/lightly_weathered_cut_copper.json
+ minecraft/recipes/lightning_rod.json
+ minecraft/recipes/lime_candle.json
+ minecraft/recipes/magenta_candle.json
+ minecraft/recipes/orange_candle.json
+ minecraft/recipes/pink_candle.json
+ minecraft/recipes/purple_candle.json
+ minecraft/recipes/red_candle.json
+ minecraft/recipes/semi_weathered_cut_copper_slab.json
+ minecraft/recipes/semi_weathered_cut_copper_stairs.json
+ minecraft/recipes/semi_weathered_cut_copper.json
+ minecraft/recipes/spyglass.json
+ minecraft/recipes/tinted_glass.json
+ minecraft/recipes/waxed_copper_cut_slab_from_honeycomb.json
+ minecraft/recipes/waxed_copper_cut_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_copper.json
+ minecraft/recipes/waxed_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_cut_copper_slab.json
+ minecraft/recipes/waxed_cut_copper_stairs.json
+ minecraft/recipes/waxed_cut_copper.json
+ minecraft/recipes/waxed_lightly_weathered_copper.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_slab.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper.json
+ minecraft/recipes/waxed_semi_weathered_copper.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_slab.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_stairs.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper.json
+ minecraft/recipes/weathered_cut_copper_slab.json
+ minecraft/recipes/weathered_cut_copper_stairs.json
+ minecraft/recipes/weathered_cut_copper.json
+ minecraft/recipes/white_candle.json
+ minecraft/recipes/yellow_candle.json
+ minecraft/tags/blocks/candle_cakes.json
+ minecraft/tags/blocks/candles.json
+ minecraft/tags/blocks/cauldrons.json
+ minecraft/tags/blocks/crystal_sound_blocks.json
+ minecraft/tags/blocks/dripstone_replaceable_blocks.json
+ minecraft/tags/blocks/inside_step_sound_blocks.json
+ minecraft/tags/blocks/occludes_vibration_signals.json
+ minecraft/tags/entity_types/axolotl_always_hostiles.json
+ minecraft/tags/entity_types/axolotl_tempted_hostiles.json
+ minecraft/tags/entity_types/powder_snow_walkable_mobs.json
+ minecraft/tags/game_events/ignore_vibrations_stepping_carefully.json
+ minecraft/tags/game_events/vibrations.json
+ minecraft/tags/items/axolotl_tempt_items.json
+ minecraft/tags/items/candles.json
+ minecraft/tags/items/freeze_immune_wearables.json
+ minecraft/tags/items/ignored_by_piglin_babies.json
+ minecraft/tags/items/occludes_vibration_signals.json
+ minecraft/tags/items/piglin_food.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/amethyst_block.json
+ minecraft/blockstates/amethyst_cluster.json
+ minecraft/blockstates/black_candle_cake.json
+ minecraft/blockstates/black_candle.json
+ minecraft/blockstates/blue_candle_cake.json
+ minecraft/blockstates/blue_candle.json
+ minecraft/blockstates/brown_candle_cake.json
+ minecraft/blockstates/brown_candle.json
+ minecraft/blockstates/budding_amethyst.json
+ minecraft/blockstates/calcite.json
+ minecraft/blockstates/candle_cake.json
+ minecraft/blockstates/candle.json
+ minecraft/blockstates/copper_block.json
+ minecraft/blockstates/copper_ore.json
+ minecraft/blockstates/cut_copper_slab.json
+ minecraft/blockstates/cut_copper_stairs.json
+ minecraft/blockstates/cut_copper.json
+ minecraft/blockstates/cyan_candle_cake.json
+ minecraft/blockstates/cyan_candle.json
+ minecraft/blockstates/dirt_path.json
+ minecraft/blockstates/dripstone_block.json
+ minecraft/blockstates/glow_item_frame.json
+ minecraft/blockstates/glow_lichen.json
- minecraft/blockstates/grass_path.json
+ minecraft/blockstates/gray_candle_cake.json
+ minecraft/blockstates/gray_candle.json
+ minecraft/blockstates/green_candle_cake.json
+ minecraft/blockstates/green_candle.json
+ minecraft/blockstates/large_amethyst_bud.json
+ minecraft/blockstates/lava_cauldron.json
+ minecraft/blockstates/light_blue_candle_cake.json
+ minecraft/blockstates/light_blue_candle.json
+ minecraft/blockstates/light_gray_candle_cake.json
+ minecraft/blockstates/light_gray_candle.json
+ minecraft/blockstates/lightly_weathered_copper_block.json
+ minecraft/blockstates/lightly_weathered_cut_copper_slab.json
+ minecraft/blockstates/lightly_weathered_cut_copper_stairs.json
+ minecraft/blockstates/lightly_weathered_cut_copper.json
+ minecraft/blockstates/lightning_rod.json
+ minecraft/blockstates/lime_candle_cake.json
+ minecraft/blockstates/lime_candle.json
+ minecraft/blockstates/magenta_candle_cake.json
+ minecraft/blockstates/magenta_candle.json
+ minecraft/blockstates/medium_amethyst_bud.json
+ minecraft/blockstates/orange_candle_cake.json
+ minecraft/blockstates/orange_candle.json
+ minecraft/blockstates/pink_candle_cake.json
+ minecraft/blockstates/pink_candle.json
+ minecraft/blockstates/pointed_dripstone.json
+ minecraft/blockstates/powder_snow_cauldron.json
+ minecraft/blockstates/powder_snow.json
+ minecraft/blockstates/purple_candle_cake.json
+ minecraft/blockstates/purple_candle.json
+ minecraft/blockstates/red_candle_cake.json
+ minecraft/blockstates/red_candle.json
+ minecraft/blockstates/sculk_sensor.json
+ minecraft/blockstates/semi_weathered_copper_block.json
+ minecraft/blockstates/semi_weathered_cut_copper_slab.json
+ minecraft/blockstates/semi_weathered_cut_copper_stairs.json
+ minecraft/blockstates/semi_weathered_cut_copper.json
+ minecraft/blockstates/small_amethyst_bud.json
+ minecraft/blockstates/tinted_glass.json
+ minecraft/blockstates/tuff.json
+ minecraft/blockstates/water_cauldron.json
+ minecraft/blockstates/waxed_copper.json
+ minecraft/blockstates/waxed_cut_copper_slab.json
+ minecraft/blockstates/waxed_cut_copper_stairs.json
+ minecraft/blockstates/waxed_cut_copper.json
+ minecraft/blockstates/waxed_lightly_weathered_copper.json
+ minecraft/blockstates/waxed_lightly_weathered_cut_copper_slab.json
+ minecraft/blockstates/waxed_lightly_weathered_cut_copper_stairs.json
+ minecraft/blockstates/waxed_lightly_weathered_cut_copper.json
+ minecraft/blockstates/waxed_semi_weathered_copper.json
+ minecraft/blockstates/waxed_semi_weathered_cut_copper_slab.json
+ minecraft/blockstates/waxed_semi_weathered_cut_copper_stairs.json
+ minecraft/blockstates/waxed_semi_weathered_cut_copper.json
+ minecraft/blockstates/weathered_copper_block.json
+ minecraft/blockstates/weathered_cut_copper_slab.json
+ minecraft/blockstates/weathered_cut_copper_stairs.json
+ minecraft/blockstates/weathered_cut_copper.json
+ minecraft/blockstates/white_candle_cake.json
+ minecraft/blockstates/white_candle.json
+ minecraft/blockstates/yellow_candle_cake.json
+ minecraft/blockstates/yellow_candle.json
+ minecraft/models/block/amethyst_block.json
+ minecraft/models/block/amethyst_cluster.json
+ minecraft/models/block/black_candle_cake.json
+ minecraft/models/block/black_candle_four_candles.json
+ minecraft/models/block/black_candle_one_candle.json
+ minecraft/models/block/black_candle_three_candles.json
+ minecraft/models/block/black_candle_two_candles.json
+ minecraft/models/block/blue_candle_cake.json
+ minecraft/models/block/blue_candle_four_candles.json
+ minecraft/models/block/blue_candle_one_candle.json
+ minecraft/models/block/blue_candle_three_candles.json
+ minecraft/models/block/blue_candle_two_candles.json
+ minecraft/models/block/brown_candle_cake.json
+ minecraft/models/block/brown_candle_four_candles.json
+ minecraft/models/block/brown_candle_one_candle.json
+ minecraft/models/block/brown_candle_three_candles.json
+ minecraft/models/block/brown_candle_two_candles.json
+ minecraft/models/block/budding_amethyst.json
+ minecraft/models/block/calcite.json
+ minecraft/models/block/candle_cake.json
+ minecraft/models/block/candle_four_candles.json
+ minecraft/models/block/candle_one_candle.json
+ minecraft/models/block/candle_three_candles.json
+ minecraft/models/block/candle_two_candles.json
- minecraft/models/block/cauldron_level1.json
- minecraft/models/block/cauldron_level2.json
- minecraft/models/block/cauldron_level3.json
+ minecraft/models/block/copper_block.json
+ minecraft/models/block/copper_ore.json
+ minecraft/models/block/cut_copper_slab_top.json
+ minecraft/models/block/cut_copper_slab.json
+ minecraft/models/block/cut_copper_stairs_inner.json
+ minecraft/models/block/cut_copper_stairs_outer.json
+ minecraft/models/block/cut_copper_stairs.json
+ minecraft/models/block/cut_copper.json
+ minecraft/models/block/cyan_candle_cake.json
+ minecraft/models/block/cyan_candle_four_candles.json
+ minecraft/models/block/cyan_candle_one_candle.json
+ minecraft/models/block/cyan_candle_three_candles.json
+ minecraft/models/block/cyan_candle_two_candles.json
+ minecraft/models/block/dirt_path.json
+ minecraft/models/block/dripstone_block.json
+ minecraft/models/block/glow_item_frame_map.json
+ minecraft/models/block/glow_item_frame.json
+ minecraft/models/block/glow_lichen.json
- minecraft/models/block/grass_path.json
+ minecraft/models/block/gray_candle_cake.json
+ minecraft/models/block/gray_candle_four_candles.json
+ minecraft/models/block/gray_candle_one_candle.json
+ minecraft/models/block/gray_candle_three_candles.json
+ minecraft/models/block/gray_candle_two_candles.json
+ minecraft/models/block/green_candle_cake.json
+ minecraft/models/block/green_candle_four_candles.json
+ minecraft/models/block/green_candle_one_candle.json
+ minecraft/models/block/green_candle_three_candles.json
+ minecraft/models/block/green_candle_two_candles.json
+ minecraft/models/block/large_amethyst_bud.json
+ minecraft/models/block/lava_cauldron.json
+ minecraft/models/block/light_blue_candle_cake.json
+ minecraft/models/block/light_blue_candle_four_candles.json
+ minecraft/models/block/light_blue_candle_one_candle.json
+ minecraft/models/block/light_blue_candle_three_candles.json
+ minecraft/models/block/light_blue_candle_two_candles.json
+ minecraft/models/block/light_gray_candle_cake.json
+ minecraft/models/block/light_gray_candle_four_candles.json
+ minecraft/models/block/light_gray_candle_one_candle.json
+ minecraft/models/block/light_gray_candle_three_candles.json
+ minecraft/models/block/light_gray_candle_two_candles.json
+ minecraft/models/block/lightly_weathered_copper_block.json
+ minecraft/models/block/lightly_weathered_cut_copper_slab_top.json
+ minecraft/models/block/lightly_weathered_cut_copper_slab.json
+ minecraft/models/block/lightly_weathered_cut_copper_stairs_inner.json
+ minecraft/models/block/lightly_weathered_cut_copper_stairs_outer.json
+ minecraft/models/block/lightly_weathered_cut_copper_stairs.json
+ minecraft/models/block/lightly_weathered_cut_copper.json
+ minecraft/models/block/lightning_rod.json
+ minecraft/models/block/lime_candle_cake.json
+ minecraft/models/block/lime_candle_four_candles.json
+ minecraft/models/block/lime_candle_one_candle.json
+ minecraft/models/block/lime_candle_three_candles.json
+ minecraft/models/block/lime_candle_two_candles.json
+ minecraft/models/block/magenta_candle_cake.json
+ minecraft/models/block/magenta_candle_four_candles.json
+ minecraft/models/block/magenta_candle_one_candle.json
+ minecraft/models/block/magenta_candle_three_candles.json
+ minecraft/models/block/magenta_candle_two_candles.json
+ minecraft/models/block/medium_amethyst_bud.json
+ minecraft/models/block/orange_candle_cake.json
+ minecraft/models/block/orange_candle_four_candles.json
+ minecraft/models/block/orange_candle_one_candle.json
+ minecraft/models/block/orange_candle_three_candles.json
+ minecraft/models/block/orange_candle_two_candles.json
+ minecraft/models/block/pink_candle_cake.json
+ minecraft/models/block/pink_candle_four_candles.json
+ minecraft/models/block/pink_candle_one_candle.json
+ minecraft/models/block/pink_candle_three_candles.json
+ minecraft/models/block/pink_candle_two_candles.json
+ minecraft/models/block/pointed_dripstone_down_base.json
+ minecraft/models/block/pointed_dripstone_down_frustum.json
+ minecraft/models/block/pointed_dripstone_down_middle.json
+ minecraft/models/block/pointed_dripstone_down_tip_merge.json
+ minecraft/models/block/pointed_dripstone_down_tip.json
+ minecraft/models/block/pointed_dripstone_up_base.json
+ minecraft/models/block/pointed_dripstone_up_frustum.json
+ minecraft/models/block/pointed_dripstone_up_middle.json
+ minecraft/models/block/pointed_dripstone_up_tip_merge.json
+ minecraft/models/block/pointed_dripstone_up_tip.json
+ minecraft/models/block/pointed_dripstone.json
+ minecraft/models/block/powder_snow_cauldron_full.json
+ minecraft/models/block/powder_snow_cauldron_level1.json
+ minecraft/models/block/powder_snow_cauldron_level2.json
+ minecraft/models/block/powder_snow.json
+ minecraft/models/block/purple_candle_cake.json
+ minecraft/models/block/purple_candle_four_candles.json
+ minecraft/models/block/purple_candle_one_candle.json
+ minecraft/models/block/purple_candle_three_candles.json
+ minecraft/models/block/purple_candle_two_candles.json
+ minecraft/models/block/red_candle_cake.json
+ minecraft/models/block/red_candle_four_candles.json
+ minecraft/models/block/red_candle_one_candle.json
+ minecraft/models/block/red_candle_three_candles.json
+ minecraft/models/block/red_candle_two_candles.json
+ minecraft/models/block/sculk_sensor_active.json
+ minecraft/models/block/sculk_sensor_inactive.json
+ minecraft/models/block/sculk_sensor.json
+ minecraft/models/block/semi_weathered_copper_block.json
+ minecraft/models/block/semi_weathered_cut_copper_slab_top.json
+ minecraft/models/block/semi_weathered_cut_copper_slab.json
+ minecraft/models/block/semi_weathered_cut_copper_stairs_inner.json
+ minecraft/models/block/semi_weathered_cut_copper_stairs_outer.json
+ minecraft/models/block/semi_weathered_cut_copper_stairs.json
+ minecraft/models/block/semi_weathered_cut_copper.json
+ minecraft/models/block/small_amethyst_bud.json
+ minecraft/models/block/template_cake_with_candle.json
+ minecraft/models/block/template_candle.json
+ minecraft/models/block/template_cauldron_full.json
+ minecraft/models/block/template_cauldron_level1.json
+ minecraft/models/block/template_cauldron_level2.json
+ minecraft/models/block/template_four_candles.json
+ minecraft/models/block/template_item_frame_map.json
+ minecraft/models/block/template_item_frame.json
+ minecraft/models/block/template_three_candles.json
+ minecraft/models/block/template_two_candles.json
+ minecraft/models/block/tinted_glass.json
+ minecraft/models/block/tuff.json
- minecraft/models/block/vine_1.json
- minecraft/models/block/vine_1u.json
- minecraft/models/block/vine_2_opposite.json
- minecraft/models/block/vine_2.json
- minecraft/models/block/vine_2u_opposite.json
- minecraft/models/block/vine_2u.json
- minecraft/models/block/vine_3.json
- minecraft/models/block/vine_3u.json
- minecraft/models/block/vine_4.json
- minecraft/models/block/vine_4u.json
- minecraft/models/block/vine_u.json
+ minecraft/models/block/vine.json
+ minecraft/models/block/water_cauldron_full.json
+ minecraft/models/block/water_cauldron_level1.json
+ minecraft/models/block/water_cauldron_level2.json
+ minecraft/models/block/weathered_copper_block.json
+ minecraft/models/block/weathered_cut_copper_slab_top.json
+ minecraft/models/block/weathered_cut_copper_slab.json
+ minecraft/models/block/weathered_cut_copper_stairs_inner.json
+ minecraft/models/block/weathered_cut_copper_stairs_outer.json
+ minecraft/models/block/weathered_cut_copper_stairs.json
+ minecraft/models/block/weathered_cut_copper.json
+ minecraft/models/block/white_candle_cake.json
+ minecraft/models/block/white_candle_four_candles.json
+ minecraft/models/block/white_candle_one_candle.json
+ minecraft/models/block/white_candle_three_candles.json
+ minecraft/models/block/white_candle_two_candles.json
+ minecraft/models/block/yellow_candle_cake.json
+ minecraft/models/block/yellow_candle_four_candles.json
+ minecraft/models/block/yellow_candle_one_candle.json
+ minecraft/models/block/yellow_candle_three_candles.json
+ minecraft/models/block/yellow_candle_two_candles.json
+ minecraft/models/item/amethyst_block.json
+ minecraft/models/item/amethyst_cluster.json
+ minecraft/models/item/amethyst_shard.json
+ minecraft/models/item/axolotl_bucket.json
+ minecraft/models/item/axolotl_spawn_egg.json
+ minecraft/models/item/black_candle.json
+ minecraft/models/item/blue_candle.json
+ minecraft/models/item/brown_candle.json
+ minecraft/models/item/budding_amethyst.json
+ minecraft/models/item/bundle_filled.json
+ minecraft/models/item/bundle.json
+ minecraft/models/item/calcite.json
+ minecraft/models/item/candle.json
+ minecraft/models/item/copper_block.json
+ minecraft/models/item/copper_ingot.json
+ minecraft/models/item/copper_ore.json
+ minecraft/models/item/cut_copper_slab.json
+ minecraft/models/item/cut_copper_stairs.json
+ minecraft/models/item/cut_copper.json
+ minecraft/models/item/cyan_candle.json
+ minecraft/models/item/dirt_path.json
+ minecraft/models/item/dripstone_block.json
+ minecraft/models/item/glow_ink_sac.json
+ minecraft/models/item/glow_item_frame.json
+ minecraft/models/item/glow_lichen.json
+ minecraft/models/item/glow_squid_spawn_egg.json
- minecraft/models/item/grass_path.json
+ minecraft/models/item/gray_candle.json
+ minecraft/models/item/green_candle.json
+ minecraft/models/item/large_amethyst_bud.json
+ minecraft/models/item/light_blue_candle.json
+ minecraft/models/item/light_gray_candle.json
+ minecraft/models/item/lightly_weathered_copper_block.json
+ minecraft/models/item/lightly_weathered_cut_copper_slab.json
+ minecraft/models/item/lightly_weathered_cut_copper_stairs.json
+ minecraft/models/item/lightly_weathered_cut_copper.json
+ minecraft/models/item/lightning_rod.json
+ minecraft/models/item/lime_candle.json
+ minecraft/models/item/magenta_candle.json
+ minecraft/models/item/medium_amethyst_bud.json
+ minecraft/models/item/orange_candle.json
+ minecraft/models/item/pink_candle.json
+ minecraft/models/item/pointed_dripstone.json
+ minecraft/models/item/powder_snow_bucket.json
+ minecraft/models/item/purple_candle.json
+ minecraft/models/item/red_candle.json
+ minecraft/models/item/sculk_sensor.json
+ minecraft/models/item/semi_weathered_copper_block.json
+ minecraft/models/item/semi_weathered_cut_copper_slab.json
+ minecraft/models/item/semi_weathered_cut_copper_stairs.json
+ minecraft/models/item/semi_weathered_cut_copper.json
+ minecraft/models/item/small_amethyst_bud.json
+ minecraft/models/item/spyglass.json
+ minecraft/models/item/tinted_glass.json
+ minecraft/models/item/tuff.json
+ minecraft/models/item/waxed_copper.json
+ minecraft/models/item/waxed_cut_copper_slab.json
+ minecraft/models/item/waxed_cut_copper_stairs.json
+ minecraft/models/item/waxed_cut_copper.json
+ minecraft/models/item/waxed_lightly_weathered_copper.json
+ minecraft/models/item/waxed_lightly_weathered_cut_copper_slab.json
+ minecraft/models/item/waxed_lightly_weathered_cut_copper_stairs.json
+ minecraft/models/item/waxed_lightly_weathered_cut_copper.json
+ minecraft/models/item/waxed_semi_weathered_copper.json
+ minecraft/models/item/waxed_semi_weathered_cut_copper_slab.json
+ minecraft/models/item/waxed_semi_weathered_cut_copper_stairs.json
+ minecraft/models/item/waxed_semi_weathered_cut_copper.json
+ minecraft/models/item/weathered_copper_block.json
+ minecraft/models/item/weathered_cut_copper_slab.json
+ minecraft/models/item/weathered_cut_copper_stairs.json
+ minecraft/models/item/weathered_cut_copper.json
+ minecraft/models/item/white_candle.json
+ minecraft/models/item/yellow_candle.json
+ minecraft/particles/dripping_dripstone_lava.json
+ minecraft/particles/dripping_dripstone_water.json
+ minecraft/particles/dust_color_transition.json
+ minecraft/particles/falling_dripstone_lava.json
+ minecraft/particles/falling_dripstone_water.json
+ minecraft/particles/glow_squid_ink.json
+ minecraft/particles/glow.json
+ minecraft/particles/small_flame.json
+ minecraft/particles/snowflake.json
+ minecraft/particles/vibration.json
+ minecraft/textures/block/amethyst_block.png
+ minecraft/textures/block/amethyst_cluster.png
+ minecraft/textures/block/black_candle.png
+ minecraft/textures/block/blue_candle.png
+ minecraft/textures/block/brown_candle.png
+ minecraft/textures/block/budding_amethyst.png
+ minecraft/textures/block/calcite.png
+ minecraft/textures/block/calibrated_sculk_sensor_side.png
+ minecraft/textures/block/calibrated_sculk_sensor_top.png
+ minecraft/textures/block/candle.png
+ minecraft/textures/block/copper_block.png
+ minecraft/textures/block/copper_ore.png
+ minecraft/textures/block/cut_copper.png
+ minecraft/textures/block/cyan_candle.png
+ minecraft/textures/block/dirt_path_side.png
+ minecraft/textures/block/dirt_path_top.png
+ minecraft/textures/block/dripstone_block.png
+ minecraft/textures/block/glow_item_frame.png
+ minecraft/textures/block/glow_lichen.png
- minecraft/textures/block/grass_path_side.png
- minecraft/textures/block/grass_path_top.png
+ minecraft/textures/block/gray_candle.png
+ minecraft/textures/block/green_candle.png
+ minecraft/textures/block/large_amethyst_bud.png
+ minecraft/textures/block/light_blue_candle.png
+ minecraft/textures/block/light_gray_candle.png
+ minecraft/textures/block/lightly_weathered_copper_block.png
+ minecraft/textures/block/lightly_weathered_cut_copper.png
+ minecraft/textures/block/lightning_rod.png
+ minecraft/textures/block/lime_candle.png
+ minecraft/textures/block/magenta_candle.png
+ minecraft/textures/block/medium_amethyst_bud.png
+ minecraft/textures/block/orange_candle.png
+ minecraft/textures/block/pink_candle.png
+ minecraft/textures/block/pointed_dripstone_down_base.png
+ minecraft/textures/block/pointed_dripstone_down_frustum.png
+ minecraft/textures/block/pointed_dripstone_down_middle.png
+ minecraft/textures/block/pointed_dripstone_down_tip_merge.png
+ minecraft/textures/block/pointed_dripstone_down_tip.png
+ minecraft/textures/block/pointed_dripstone_up_base.png
+ minecraft/textures/block/pointed_dripstone_up_frustum.png
+ minecraft/textures/block/pointed_dripstone_up_middle.png
+ minecraft/textures/block/pointed_dripstone_up_tip_merge.png
+ minecraft/textures/block/pointed_dripstone_up_tip.png
+ minecraft/textures/block/powder_snow.png
+ minecraft/textures/block/purple_candle.png
+ minecraft/textures/block/red_candle.png
+ minecraft/textures/block/sculk_sensor_bottom.png
+ minecraft/textures/block/sculk_sensor_side.png
+ minecraft/textures/block/sculk_sensor_tendril_active.png
+ minecraft/textures/block/sculk_sensor_tendril_active.png.mcmeta
+ minecraft/textures/block/sculk_sensor_tendril_inactive.png
+ minecraft/textures/block/sculk_sensor_tendril_inactive.png.mcmeta
+ minecraft/textures/block/sculk_sensor_top.png
+ minecraft/textures/block/semi_weathered_copper_block.png
+ minecraft/textures/block/semi_weathered_cut_copper.png
+ minecraft/textures/block/small_amethyst_bud.png
+ minecraft/textures/block/tinted_glass.png
+ minecraft/textures/block/tuff.png
+ minecraft/textures/block/weathered_copper_block.png
+ minecraft/textures/block/weathered_cut_copper.png
+ minecraft/textures/block/white_candle.png
+ minecraft/textures/block/yellow_candle.png
+ minecraft/textures/entity/axolotl/axolotl_blue.png
+ minecraft/textures/entity/axolotl/axolotl_cyan.png
+ minecraft/textures/entity/axolotl/axolotl_gold.png
+ minecraft/textures/entity/axolotl/axolotl_lucy.png
+ minecraft/textures/entity/axolotl/axolotl_wild.png
- minecraft/textures/entity/squid.png
+ minecraft/textures/entity/squid/glow_squid.png
+ minecraft/textures/entity/squid/squid.png
+ minecraft/textures/gui/container/bundle.png
+ minecraft/textures/item/amethyst_shard.png
+ minecraft/textures/item/axolotl_bucket.png
+ minecraft/textures/item/black_candle.png
+ minecraft/textures/item/blue_candle.png
+ minecraft/textures/item/brown_candle.png
+ minecraft/textures/item/bundle_filled.png
+ minecraft/textures/item/bundle.png
+ minecraft/textures/item/candle.png
+ minecraft/textures/item/copper_ingot.png
+ minecraft/textures/item/cyan_candle.png
+ minecraft/textures/item/glow_ink_sac.png
+ minecraft/textures/item/glow_item_frame.png
+ minecraft/textures/item/gray_candle.png
+ minecraft/textures/item/green_candle.png
+ minecraft/textures/item/light_blue_candle.png
+ minecraft/textures/item/light_gray_candle.png
+ minecraft/textures/item/lime_candle.png
+ minecraft/textures/item/magenta_candle.png
+ minecraft/textures/item/orange_candle.png
+ minecraft/textures/item/pink_candle.png
+ minecraft/textures/item/pointed_dripstone.png
+ minecraft/textures/item/powder_snow_bucket.png
+ minecraft/textures/item/purple_candle.png
+ minecraft/textures/item/red_candle.png
+ minecraft/textures/item/spyglass.png
+ minecraft/textures/item/white_candle.png
+ minecraft/textures/item/yellow_candle.png
+ minecraft/textures/misc/powder_snow_outline.png
+ minecraft/textures/misc/spyglass_scope.png
+ minecraft/textures/particle/glow.png
+ minecraft/textures/particle/vibration.png
+ minecraft/textures/particle/vibration.png.mcmeta
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
- net.minecraft.commands.arguments.blocks.BlockInput
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.blocks.BlockStateArgument
+ net.minecraft.commands.arguments.blocks.BlockStateParser
- net.minecraft.commands.arguments.blocks.package-info
+ net.minecraft.commands.arguments.coordinates.BlockPosArgument
- net.minecraft.commands.arguments.coordinates.ColumnPosArgument
+ net.minecraft.commands.arguments.coordinates.Coordinates
- net.minecraft.commands.arguments.coordinates.LocalCoordinates
+ net.minecraft.commands.arguments.coordinates.package-info
+ net.minecraft.commands.arguments.coordinates.RotationArgument
- net.minecraft.commands.arguments.coordinates.SwizzleArgument
+ net.minecraft.commands.arguments.coordinates.Vec2Argument
- net.minecraft.commands.arguments.coordinates.Vec3Argument
+ net.minecraft.commands.arguments.coordinates.WorldCoordinate
- net.minecraft.commands.arguments.coordinates.WorldCoordinates
- net.minecraft.commands.arguments.item.FunctionArgument
+ net.minecraft.commands.arguments.item.FunctionArgument$1
- net.minecraft.commands.arguments.item.FunctionArgument$2
+ net.minecraft.commands.arguments.item.FunctionArgument$Result
- net.minecraft.commands.arguments.item.ItemArgument
+ net.minecraft.commands.arguments.item.ItemInput
- net.minecraft.commands.arguments.item.ItemParser
+ net.minecraft.commands.arguments.item.ItemPredicateArgument
- net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.package-info
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
+ net.minecraft.commands.arguments.selector.EntitySelector
- net.minecraft.commands.arguments.selector.EntitySelector$1
- net.minecraft.commands.arguments.SlotArgument
+ net.minecraft.commands.arguments.TeamArgument
- net.minecraft.commands.arguments.TimeArgument
+ net.minecraft.commands.arguments.UuidArgument
- net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.QuartPos
+ net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess
+ net.minecraft.core.RegistryAccess$RegistryData
- net.minecraft.core.RegistryAccess$RegistryHolder
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
- net.minecraft.core.SerializableUUID
+ net.minecraft.core.Vec3i
- net.minecraft.core.WritableRegistry
- net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapedRecipeBuilder$Result
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder$1
- net.minecraft.data.recipes.UpgradeRecipeBuilder
+ net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BiomeReport
+ net.minecraft.data.worldgen.biome.Biomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.biome.VanillaBiomes
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.Features
+ net.minecraft.data.worldgen.Features$Configs
- net.minecraft.data.worldgen.Features$Decorators
+ net.minecraft.data.worldgen.Features$States
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.StructureFeatures
+ net.minecraft.data.worldgen.SurfaceBuilders
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.AfterBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
- net.minecraft.nbt.TagVisitor
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerAckPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResourcePackPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerAckPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$1
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.Eula
+ net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
- net.minecraft.tags.GameEventTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.SerializationTags
+ net.minecraft.tags.SetTag
- net.minecraft.tags.StaticTagHelper
+ net.minecraft.tags.StaticTagHelper$1
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$1
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$Named
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.IntRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LimitedCapacityList
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
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
- net.minecraft.util.UniformInt
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.entity.AgableMob
- net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.WeightedList
- net.minecraft.world.entity.ai.behavior.WeightedList$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.DolphinLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HostilesSensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$1
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$1
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
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
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
- net.minecraft.world.entity.monster.Ravager$1
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$1
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
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
+ net.minecraft.world.entity.monster.Strider$1
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
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
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
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
- net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
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
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$1
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
- net.minecraft.world.item.CreativeModeTab$11
+ net.minecraft.world.item.CreativeModeTab$12
- net.minecraft.world.item.CreativeModeTab$2
+ net.minecraft.world.item.CreativeModeTab$3
- net.minecraft.world.item.CreativeModeTab$4
+ net.minecraft.world.item.CreativeModeTab$5
- net.minecraft.world.item.CreativeModeTab$6
+ net.minecraft.world.item.CreativeModeTab$7
- net.minecraft.world.item.CreativeModeTab$8
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$1
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.ProjectileWeaponItem$Type
- net.minecraft.world.item.Rarity
+ net.minecraft.world.item.RecordItem
- net.minecraft.world.item.SaddleItem
+ net.minecraft.world.item.ScaffoldingBlockItem
- net.minecraft.world.item.ServerItemCooldowns
+ net.minecraft.world.item.ShearsItem
- net.minecraft.world.item.ShieldItem
+ net.minecraft.world.item.ShovelItem
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$BiomeCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$1
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.BiomeZoomer
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
+ net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$1
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.OverworldBiomeSource
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.ChangeOverTimeSlabBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickableBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.Lantern
- net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.MultifaceBlock
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
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
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
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlant
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlant
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.OldDataLayer
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$1
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$1
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.PersistentEntitySectionManager$1
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager$1
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BaseDiskFeature
+ net.minecraft.world.level.levelgen.feature.BastionFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JigsawFeature
+ net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlideSettings
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountDecorator
- net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
- net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.DecorationContext
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EdgeDecorator
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.structure.BeardedStructureStart
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
- net.minecraft.world.level.levelgen.structure.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.IglooPieces
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureStart$1
- net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.StructureSettings
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
- net.minecraft.world.level.lighting.FlatDataLayer
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$1
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$1
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
+ net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.ConstantIntValue
+ net.minecraft.world.level.storage.loot.Deserializers
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$1
- net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootTableReference
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$1
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$DefaultSerializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
+ net.minecraft.world.level.storage.loot.IntLimiter
+ net.minecraft.world.level.storage.loot.IntLimiter$Serializer
- net.minecraft.world.level.storage.loot.IntRange$1
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.ItemModifierManager
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$1
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$1
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$1
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.LootTable$Serializer
+ net.minecraft.world.level.storage.loot.LootTables
- net.minecraft.world.level.storage.loot.PredicateManager
+ net.minecraft.world.level.storage.loot.PredicateManager$1
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$1
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.RandomIntGenerator
+ net.minecraft.world.level.storage.loot.RandomValueBounds
+ net.minecraft.world.level.storage.loot.Serializer
- net.minecraft.world.level.storage.loot.SerializerType
+ net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.TickList
+ net.minecraft.world.level.TickNextTickData
- net.minecraft.world.level.TickPriority
+ net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
+ net.minecraft.world.phys.shapes.IntPointRange
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.DetectedVersion +1M -1M | +2P -1P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger +2M -2M
```
```
XXX.advancements.critereon.BlockPredicate +2M
```
```
XXX.advancements.critereon.BredAnimalsTrigger +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.advancements.critereon.FluidPredicate +2M
```
```
XXX.advancements.critereon.ItemPredicate +2M
```
```
XXX.minecraft.commands.CommandFunction$Entry +1P -1P
```
```
XXX.minecraft.core.BlockMath +2P -2P
```
```
XXX.minecraft.core.BlockSource -1P
```
```
XXX.minecraft.core.Direction +1M
```
```
XXX.minecraft.core.Direction8 -1M | -8P
```
```
XXX.core.particles.DustParticleOptions +3M -11M | +1P -4P
```
```
XXX.data.loot.BlockLoot +6M -3M
```
```
XXX.data.models.BlockModelGenerators +75M -52M | +5P
```
```
XXX.models.model.TextureMapping +2M
```
```
XXX.data.structures.StructureUpdater +1M
```
```
XXX.minecraft.nbt.ByteArrayTag +1M -1M
```
```
XXX.minecraft.nbt.ByteTag +1M -2M
```
```
XXX.minecraft.nbt.CompoundTag +1M -4M | -2P
```
```
XXX.minecraft.nbt.DoubleTag +1M -2M
```
```
XXX.minecraft.nbt.EndTag +1M -1M
```
```
XXX.minecraft.nbt.FloatTag +1M -2M
```
```
XXX.minecraft.nbt.IntArrayTag +1M -1M
```
```
XXX.minecraft.nbt.IntTag +1M -2M
```
```
XXX.minecraft.nbt.NbtUtils +20M | +4P
```
```
XXX.minecraft.nbt.ShortTag +1M -2M
```
```
XXX.minecraft.network.Connection +1M
```
```
XXX.minecraft.network.FriendlyByteBuf +2M
```
```
XXX.network.chat.CommonComponents +1M
```
```
XXX.server.dedicated.DedicatedPlayerList -2M
```
```
XXX.server.level.ChunkHolder +8M -3M | +4P -2P
```
```
XXX.server.packs.PackType +2M -1M | +1P
```
```
XXX.server.packs.VanillaPackResources +1M -1M | +1P
```
```
XXX.packs.repository.Pack +1M -1M | -1P
```
```
XXX.packs.repository.PackRepository +3M -2M
```
```
XXX.server.rcon.RconConsoleSource +1P -1P
```
```
XXX.rcon.thread.GenericThread -1P
```
```
XXX.minecraft.sounds.SoundSource -2M | -1P
```
```
XXX.minecraft.tags.EntityTypeTags -1M | +3P
```
```
XXX.minecraft.tags.TagContainer$1 +2M -5M | +3P -4P
```
```
XXX.minecraft.tags.TagManager +10M -3M | +2P -4P
```
```
XXX.minecraft.util.Mth +7M -1M
```
```
XXX.datafix.fixes.References +1M | +1P
```
```
XXX.datafix.schemas.V1460 +1M
```
```
XXX.minecraft.world.SimpleContainer -1M
```
```
XXX.world.entity.AreaEffectCloud +1M -3M
```
```
XXX.world.entity.FlyingMob +1M -1M
```
```
XXX.ai.control.MoveControl -1M
```
```
XXX.ai.goal.LookAtPlayerGoal +1M
```
```
XXX.goal.target.NearestAttackableTargetGoal +1M
```
```
XXX.ai.memory.MemoryModuleType +4P
```
```
XXX.ai.util.RandomPos +6M -14M
```
```
XXX.village.poi.PoiType +1P
```
```
XXX.entity.animal.AbstractGolem +1M -1M
```
```
XXX.entity.animal.Bee +5M -5M
```
```
XXX.entity.animal.Fox +3M -3M
```
```
XXX.entity.animal.MushroomCow +3M -3M
```
```
XXX.entity.animal.Ocelot +3M -4M
```
```
XXX.entity.animal.Panda$PandaLookAtPlayerGoal +1M
```
```
XXX.entity.animal.Parrot +2M -2M
```
```
XXX.entity.animal.Pig +2M -2M
```
```
XXX.entity.animal.Rabbit +3M -4M
```
```
XXX.entity.animal.Squid +2M
```
```
XXX.entity.animal.Turtle +1M -1M | +1P
```
```
XXX.animal.horse.AbstractHorse +8M -6M
```
```
XXX.entity.boss.EnderDragonPart +1M
```
```
XXX.boss.enderdragon.EnderDragon -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.decoration.ItemFrame$1 +3M -1M | +1P -1P
```
```
XXX.entity.vehicle.Boat +2M
```
```
XXX.entity.vehicle.DismountHelper +1M -1M
```
```
XXX.entity.vehicle.MinecartHopper -1M
```
```
XXX.entity.vehicle.MinecartSpawner$1 +1M -3M
```
```
XXX.world.inventory.AbstractContainerMenu +1M -4M | +1P -1P
```
```
XXX.world.item.BucketItem +2M -1M
```
```
XXX.world.item.FireworkRocketItem +1M
```
```
XXX.world.item.PickaxeItem +1M | +1P
```
```
XXX.world.item.SpawnEggItem +2P -2P
```
```
XXX.world.level.EntityGetter +3M -3M | +1P -1P
```
```
XXX.world.level.GameRules -1M | +2P
```
```
XXX.world.level.GameType +4M -1M | +3P -1P
```
```
XXX.level.block.AttachedStemBlock +1M -2M | +1P
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.BaseEntityBlock +1M
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M
```
```
XXX.level.block.BeaconBlock +2M -1M
```
```
XXX.level.block.Block +3M -7M
```
```
XXX.level.block.Blocks +25M -15M | +82P -1P
```
```
XXX.level.block.BrewingStandBlock +2M -1M
```
```
XXX.level.block.BucketPickup +2P -1P
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EnchantmentTableBlock +2M -1M
```
```
XXX.level.block.EndPortalBlock +1M -1M
```
```
XXX.level.block.EndRodBlock -5M | -3P
```
```
XXX.level.block.FallingBlock -2M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M
```
```
XXX.level.block.GrassBlock +1M
```
```
XXX.level.block.Mirror +2M -1M | +1P
```
```
XXX.level.block.ShulkerBoxBlock +3M -1M
```
```
XXX.level.block.SignBlock +1M -1M | +1P
```
```
XXX.level.block.SpawnerBlock +2M -1M
```
```
XXX.level.block.StemBlock +1M -2M | +1P
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.block.entity.BaseContainerBlockEntity +2M -2M
```
```
XXX.block.entity.BedBlockEntity +2M -2M
```
```
XXX.block.entity.BlockEntityType +3M -3M | +2P -1P
```
```
XXX.block.entity.DispenserBlockEntity +3M -3M
```
```
XXX.block.entity.EnchantmentTableBlockEntity +3M -3M
```
```
XXX.block.entity.SignBlockEntity +3M -2M
```
```
XXX.block.entity.SmokerBlockEntity +1M -1M
```
```
XXX.block.entity.SpawnerBlockEntity$1 +2M -4M
```
```
XXX.level.chunk.LevelChunk +29M -21M | +3P -3P
```
```
XXX.chunk.storage.IOWorker +2M -1M
```
```
XXX.chunk.storage.IOWorker$Priority +3P -2P
```
```
XXX.level.levelgen.Decoratable +1M -1M
```
```
XXX.level.material.LavaFluid +1M
```
```
XXX.level.storage.DerivedLevelData +1M -1M
```
```
XXX.level.storage.LevelData +2M -2M
```
```
XXX.loot.functions.LimitCount +6M -5M | +1P -1P
```
```
XXX.loot.functions.LootItemFunctions +2P
```
```
XXX.loot.functions.SetAttributesFunction$Modifier +3M -3M | +1P -1P
```
```
XXX.loot.functions.SetItemCountFunction +9M -5M | +2P -1P
```
```
XXX.loot.predicates.LootItemConditions +1P
```
```
XXX.loot.predicates.TimeCheck +5M -4M | +1P -1P
```
```
XXX.loot.predicates.TimeCheck$Builder +1M -1M | +1P -1P
```
```
XXX.phys.shapes.DiscreteCubeMerger +1M | +2P -3P
```
```
XXX.phys.shapes.EntityCollisionContext +3M -1M | +3P -1P
```
```
XXX.phys.shapes.IdenticalMerger +1M
```
```
XXX.world.scores.Score -1M
```
```
XXX.world.scores.ScoreboardSaveData +2M -4M | -2P
```
```
XXX.world.scores.Team$CollisionRule -1M
```

</details>










<details>
<summary>
net.minecraft.DetectedVersion
</summary>

```diff
+ int getPackVersion()
- int getPackVersion(PackType)
```

</details>


















<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
+ boolean lambda$trigger$1(Block,ItemStack,int,BeeNestDestroyedTrigger$TriggerInstance)
- boolean lambda$trigger$1(BlockState,ItemStack,int,BeeNestDestroyedTrigger$TriggerInstance)
+ void trigger(ServerPlayer,Block,ItemStack,int)
- void trigger(ServerPlayer,BlockState,ItemStack,int)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
- IllegalStateException lambda$serializeToJson$1()
- JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
+ void trigger(ServerPlayer,Animal,Animal,AgableMob)
- void trigger(ServerPlayer,Animal,Animal,AgeableMob)
```

</details>



<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
+ boolean lambda$trigger$0(BeaconBlockEntity,ConstructBeaconTrigger$TriggerInstance)
- boolean lambda$trigger$0(int,ConstructBeaconTrigger$TriggerInstance)
+ void trigger(ServerPlayer,BeaconBlockEntity)
- void trigger(ServerPlayer,int)
```

</details>


















<details>
<summary>
net.minecraft.advancements.critereon.FluidPredicate
</summary>

```diff
- IllegalStateException lambda$serializeToJson$1()
- JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>




<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate
</summary>

```diff
- IllegalStateException lambda$serializeToJson$3()
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
```

</details>











































































<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Direction getFacingAxis(Entity,Direction$Axis)
```

</details>



<details>
<summary>
net.minecraft.core.Direction8
</summary>

```diff
+ int getSideMask(boolean,boolean,boolean,boolean)
```

</details>























<details>
<summary>
net.minecraft.core.particles.DustParticleOptions
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ float getB()
+ float getG()
+ float getR()
+ float getScale()
+ Float lambda$null$0(DustParticleOptions)
+ Float lambda$null$2(DustParticleOptions)
+ Float lambda$null$3(DustParticleOptions)
+ String writeToString()
- Vector3f lambda$null$0(DustParticleOptions)
+ void <init>(float,float,float,float)
- void <init>(Vector3f,float)
+ void writeToNetwork(FriendlyByteBuf)
```

</details>








<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder createCandleCakeDrops(Block)
- LootTable$Builder createCandleDrops(Block)
- LootTable$Builder createSingleItemTable(ItemLike,NumberProvider)
+ LootTable$Builder createSingleItemTable(ItemLike,RandomIntGenerator)
- LootTable$Builder createSingleItemTableWithSilkTouch(Block,ItemLike,NumberProvider)
+ LootTable$Builder createSingleItemTableWithSilkTouch(Block,ItemLike,RandomIntGenerator)
- LootTable$Builder lambda$accept$73(Block)
+ LootTable$Builder lambda$dropPottedContents$73(Block)
- LootTable$Builder lambda$dropPottedContents$74(Block)
```

</details>



<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ BlockModelGenerators$BlockFamilyProvider family(Block,TexturedModel)
+ BlockModelGenerators$BlockFamilyProvider family(Block,TexturedModel$Provider)
+ BlockModelGenerators$BlockFamilyProvider family(TextureMapping)
- BlockStateGenerator access$1000(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1100(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1200(Block,ResourceLocation,ResourceLocation,ResourceLocation)
- BlockStateGenerator access$1300(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1300(Block,ResourceLocation)
- BlockStateGenerator access$1400(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$1400(Block,ResourceLocation,ResourceLocation)
- BlockStateGenerator access$2000(Block,ResourceLocation)
- BlockStateGenerator access$2100(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$300(Block,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$500(Block,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator access$700(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
- BlockStateGenerator access$700(Block,ResourceLocation,ResourceLocation,ResourceLocation)
- BlockStateGenerator access$900(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ Consumer access$200(BlockModelGenerators)
- Consumer access$300(BlockModelGenerators)
- List access$100(BlockModelGenerators)
- List access$1600(BlockModelGenerators)
+ List lambda$createTurtleEgg$29(Integer,Integer)
- List lambda$createTurtleEgg$34(Integer,Integer)
- Map access$1900()
+ MultiVariantGenerator access$100(Block,ResourceLocation)
- MultiVariantGenerator access$200(Block,ResourceLocation,ResourceLocation)
- MultiVariantGenerator access$400(Block,ResourceLocation)
- ResourceLocation lambda$null$10(Block,int,int)
+ ResourceLocation lambda$null$6(Block,int,int)
+ ResourceLocation lambda$run$33(TextureMapping)
- TextureMapping lambda$createChorusFlower$13(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createChorusFlower$9(TextureMapping,ResourceLocation)
+ TextureMapping lambda$createCommandBlock$2(TextureMapping,ResourceLocation)
- TextureMapping lambda$createCommandBlock$6(TextureMapping,ResourceLocation)
- Variant createPointedDripstoneVariant(Direction,DripstoneThickness)
+ Variant lambda$createActiveRail$1(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
- Variant lambda$createActiveRail$5(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,RailShape)
+ Variant lambda$createBambooModels$3(String,int)
- Variant lambda$createBambooModels$7(String,int)
- Variant lambda$createCropBlock$11(int[],Int2ObjectMap,Block,Integer)
+ Variant lambda$createCropBlock$7(int[],Int2ObjectMap,Block,Integer)
+ Variant lambda$createEmptyOrFullDispatch$5(Comparable,Variant,Variant,Comparable)
- Variant lambda$createEmptyOrFullDispatch$9(Comparable,Variant,Variant,Comparable)
+ Variant lambda$createFire$11(Variant)
+ Variant lambda$createFire$12(Variant)
+ Variant lambda$createFire$13(Variant)
+ Variant lambda$createFire$14(Variant)
- Variant lambda$createFire$17(Variant)
- Variant lambda$createFire$18(Variant)
- Variant lambda$createFire$19(Variant)
- Variant lambda$createFire$20(Variant)
+ Variant lambda$createJigsaw$31(FrontAndTop)
- Variant lambda$createJigsaw$44(FrontAndTop)
+ Variant lambda$createRepeater$24(Integer,Boolean,Boolean)
- Variant lambda$createRepeater$29(Integer,Boolean,Boolean)
+ Variant lambda$createRespawnAnchor$30(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$43(ResourceLocation[],Integer)
- Variant lambda$createSculkSensor$28(ResourceLocation,ResourceLocation,SculkSensorPhase)
+ Variant lambda$createSnowBlocks$25(ResourceLocation,Integer)
- Variant lambda$createSnowBlocks$30(ResourceLocation,Integer)
+ Variant lambda$createSoulFire$17(Variant)
+ Variant lambda$createSoulFire$18(Variant)
+ Variant lambda$createSoulFire$19(Variant)
+ Variant lambda$createSoulFire$20(Variant)
- Variant lambda$createSoulFire$22(Variant)
- Variant lambda$createSoulFire$23(Variant)
- Variant lambda$createSoulFire$24(Variant)
- Variant lambda$createSoulFire$25(Variant)
+ Variant lambda$createStems$0(Block,TextureMapping,Integer)
- Variant lambda$createStems$4(Block,TextureMapping,Integer)
+ Variant lambda$createStructureBlock$26(StructureMode)
- Variant lambda$createStructureBlock$31(StructureMode)
+ Variant lambda$createSweetBerryBush$27(Integer)
- Variant lambda$createSweetBerryBush$32(Integer)
+ Variant lambda$createTripwireHook$28(Boolean,Boolean)
- Variant lambda$createTripwireHook$33(Boolean,Boolean)
- Variant lambda$null$35(ResourceLocation)
- Variant lambda$null$36(ResourceLocation)
- Variant lambda$null$37(ResourceLocation)
- Variant lambda$null$38(ResourceLocation)
- Variant lambda$null$39(ResourceLocation)
- Variant lambda$null$40(ResourceLocation)
+ Variant lambda$wrapModels$10(ResourceLocation)
- Variant lambda$wrapModels$14(ResourceLocation)
- void <clinit>()
+ void access$1000(BlockModelGenerators,Block)
- void access$1100(BlockModelGenerators,Item)
- void access$1200(BlockModelGenerators,Block)
- void access$1500(BlockModelGenerators,Block)
- void access$1700(BlockModelGenerators,Block)
- void access$1800(BlockModelGenerators,Block)
+ void access$400(BlockModelGenerators,Block,ResourceLocation)
- void access$500(BlockModelGenerators,Block,ResourceLocation)
+ void access$900(BlockModelGenerators,Item)
- void createAmethystCluster(Block)
- void createAmethystClusters()
- void createCandleAndCandleCake(Block,Block)
+ void createCauldron()
- void createCauldrons()
- void createDirtPath()
+ void createGrassPath()
- void createMultiface(Block)
- void createPetrifiedOakSlab()
- void createPointedDripstone()
- void createSculkSensor()
+ void createVine()
+ void lambda$createBarrel$4(ResourceLocation,TextureMapping)
- void lambda$createBarrel$8(ResourceLocation,TextureMapping)
- void lambda$createFurnace$12(ResourceLocation,TextureMapping)
+ void lambda$createFurnace$8(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$22(ResourceLocation,TextureMapping)
+ void lambda$createGrassBlocks$23(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$26(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$27(ResourceLocation,TextureMapping)
- void lambda$createMultiface$42(Block,MultiPartGenerator,ResourceLocation,BooleanProperty,Function)
- void lambda$new$0(TextureMapping)
- void lambda$new$1(TextureMapping)
+ void lambda$run$32(TextureMapping)
+ void lambda$run$34(TextureMapping)
+ void lambda$run$35(TextureMapping)
+ void lambda$run$36(SpawnEggItem)
- void lambda$run$45(BlockFamily)
- void lambda$run$46(TextureMapping)
- void lambda$run$47(SpawnEggItem)
- void lambda$static$2(Object,Block)
- void lambda$static$3(Object,Block)
- void lambda$static$41(HashMap)
```

</details>



















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping candleCake(Block)
- TextureMapping cauldron(ResourceLocation)
```

</details>



<details>
<summary>
net.minecraft.data.structures.StructureUpdater
</summary>

```diff
- CompoundTag update(String,CompoundTag)
```

</details>











<details>
<summary>
net.minecraft.nbt.ByteArrayTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>

<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ Component handleEscapePretty(String)
+ String handleEscape(String)
- void accept(TagVisitor)
+ void stripEmptyChildren()
```

</details>
<details>
<summary>
net.minecraft.nbt.DoubleTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.EndTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.FloatTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.IntArrayTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.IntTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>







<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
- Component toPrettyComponent(Tag)
- CompoundTag packStructureTemplate(CompoundTag)
- CompoundTag snbtToStructure(String)
- CompoundTag unpackBlockState(String)
- CompoundTag unpackStructureTemplate(CompoundTag)
- double lambda$static$3(ListTag)
- double lambda$static$4(ListTag)
- double lambda$static$5(ListTag)
- int lambda$static$0(ListTag)
- int lambda$static$1(ListTag)
- int lambda$static$2(ListTag)
- ListTag lambda$packStructureTemplate$7(CompoundTag)
- ListTag lambda$packStructureTemplate$8(CompoundTag)
- ListTag lambda$unpackStructureTemplate$10(Map,CompoundTag)
- String lambda$packBlockState$11(CompoundTag,String)
- String packBlockState(CompoundTag)
- String structureToSnbt(CompoundTag)
- void lambda$packStructureTemplate$6(ListTag,ListTag,ListTag)
- void lambda$packStructureTemplate$9(ListTag,CompoundTag)
- void lambda$unpackBlockState$12(CompoundTag,String,String)
```

</details>
<details>
<summary>
net.minecraft.nbt.ShortTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>






<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
- ConnectionProtocol getCurrentProtocol()
```

</details>



<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- BitSet readBitSet()
- void writeBitSet(BitSet)
```

</details>





<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
- MutableComponent optionNameValue(Component,Component)
```

</details>
























































<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
+ void blackList(GameProfile)
+ void whiteList(GameProfile)
```

</details>








<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
+ Either lambda$updateFutures$5(ChunkMap,Either)
- Either lambda$updateFutures$8(ChunkMap,Either)
- void <init>(ChunkPos,int,LevelHeightAccessor,LevelLightEngine,ChunkHolder$LevelChangeListener,ChunkHolder$PlayerProvider)
+ void <init>(ChunkPos,int,LevelLightEngine,ChunkHolder$LevelChangeListener,ChunkHolder$PlayerProvider)
- void demoteFullChunk(ChunkMap,ChunkHolder$FullChunkStatus)
- void lambda$null$6(CompletableFuture,LevelChunk)
- void lambda$scheduleFullChunkPromotion$5(ChunkMap,ChunkHolder$FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$7(CompletableFuture,Either)
- void scheduleFullChunkPromotion(ChunkMap,CompletableFuture,Executor,ChunkHolder$FullChunkStatus)
- void updateFutures(ChunkMap,Executor)
+ void updateFutures(ChunkMap)
```

</details>

















<details>
<summary>
net.minecraft.server.packs.PackType
</summary>

```diff
- int getVersion(GameVersion)
- void <init>(String,int,String,PackType)
+ void <init>(String,int,String)
```

</details>
<details>
<summary>
net.minecraft.server.packs.VanillaPackResources
</summary>

```diff
- void <init>(PackMetadataSection,String[])
+ void <init>(String[])
```

</details>



<details>
<summary>
net.minecraft.server.packs.repository.Pack
</summary>

```diff
+ void <init>(String,boolean,Supplier,PackResources,PackMetadataSection,Pack$Position,PackSource)
- void <init>(String,Component,boolean,Supplier,PackMetadataSection,PackType,Pack$Position,PackSource)
```

</details>

<details>
<summary>
net.minecraft.server.packs.repository.PackRepository
</summary>

```diff
- Pack lambda$new$0(PackType,String,Component,boolean,Supplier,PackMetadataSection,Pack$Position,PackSource)
- void <init>(PackType,RepositorySource[])
+ void <init>(RepositorySource[])
+ void lambda$discoverAvailable$0(Map,Pack)
- void lambda$discoverAvailable$1(Map,Pack)
```

</details>
































<details>
<summary>
net.minecraft.sounds.SoundSource
</summary>

```diff
+ Set getNames()
+ SoundSource byName(String)
```

</details>






<details>
<summary>
net.minecraft.tags.EntityTypeTags
</summary>

```diff
+ List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.TagContainer$1
</summary>

```diff
+ TagCollection getBlocks()
+ TagCollection getEntityTypes()
+ TagCollection getFluids()
+ TagCollection getItems()
+ void <init>(TagCollection,TagCollection,TagCollection,TagCollection)
- void <init>(TagContainer,RegistryAccess,Map)
- void accept(ResourceKey,TagCollection)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager
</summary>

```diff
- CompletableFuture lambda$reload$1(TagManager$LoaderInfo)
- CompletableFuture[] lambda$reload$2(int)
+ String lambda$null$0(Map$Entry)
- String lambda$null$4(Map$Entry)
- TagCollection lambda$createLoader$6(TagLoader,ResourceManager)
- TagManager$LoaderInfo createLoader(ResourceManager,Executor,StaticTagHelper)
- void <clinit>()
+ void <init>()
- void <init>(RegistryAccess)
- void lambda$null$3(TagContainer$Builder,TagManager$LoaderInfo)
- void lambda$reload$0(ResourceManager,Executor,List,StaticTagHelper)
+ void lambda$reload$1(CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,Void)
- void lambda$reload$5(List,Void)
```

</details>












<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- double clampedMap(double,double,double,double,double)
- double map(double,double,double,double,double)
- double wobble(double)
- float normal(Random,float,float)
- float randomBetween(Random,float,float)
- int randomBetweenInclusive(Random,int,int)
- int roundToward(int,int)
+ int roundUp(int,int)
```

</details>
























































<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
- String lambda$static$25()
```

</details>






















<details>
<summary>
net.minecraft.util.datafix.schemas.V1460
</summary>

```diff
- TypeTemplate lambda$registerTypes$46(Schema)
```

</details>












<details>
<summary>
net.minecraft.world.SimpleContainer
</summary>

```diff
+ boolean isSameItem(ItemStack,ItemStack)
```

</details>












<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
+ boolean canUse()
- boolean lambda$tick$0(Map$Entry)
+ List getEffects()
+ void use()
```

</details>



<details>
<summary>
net.minecraft.world.entity.FlyingMob
</summary>

```diff
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>


















<details>
<summary>
net.minecraft.world.entity.ai.control.MoveControl
</summary>

```diff
+ void copyFrom(MoveControl)
```

</details>















<details>
<summary>
net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
</summary>

```diff
- boolean lambda$canUse$1(LivingEntity)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
</summary>

```diff
- boolean lambda$findTarget$0(LivingEntity)
```

</details>


















<details>
<summary>
net.minecraft.world.entity.ai.util.RandomPos
</summary>

```diff
- BlockPos generateRandomDirection(Random,int,int)
- BlockPos generateRandomDirectionWithinRadians(Random,int,int,int,double,double,double)
- BlockPos generateRandomPosTowardDirection(PathfinderMob,int,Random,BlockPos)
+ BlockPos getRandomDelta(Random,int,int,int,Vec3,double)
- BlockPos moveUpOutOfSolid(BlockPos,int,Predicate)
+ boolean lambda$generateRandomPos$0(PathfinderMob,BlockPos)
+ Vec3 generateRandomPos(PathfinderMob,int,int,int,Vec3,boolean,double,ToDoubleFunction,boolean,int,int,boolean)
- Vec3 generateRandomPos(PathfinderMob,Supplier)
- Vec3 generateRandomPos(Supplier,ToDoubleFunction)
+ Vec3 getAboveLandPos(PathfinderMob,int,int,Vec3,float,int,int)
+ Vec3 getAirPos(PathfinderMob,int,int,int,Vec3,double)
+ Vec3 getAirPosTowards(PathfinderMob,int,int,int,Vec3,double)
+ Vec3 getLandPos(PathfinderMob,int,int,ToDoubleFunction)
+ Vec3 getLandPos(PathfinderMob,int,int)
+ Vec3 getLandPosAvoid(PathfinderMob,int,int,Vec3)
+ Vec3 getLandPosTowards(PathfinderMob,int,int,Vec3)
+ Vec3 getPos(PathfinderMob,int,int)
+ Vec3 getPosAvoid(PathfinderMob,int,int,Vec3)
+ Vec3 getPosTowards(PathfinderMob,int,int,Vec3,double)
+ Vec3 getPosTowards(PathfinderMob,int,int,Vec3)
```

</details>









<details>
<summary>
net.minecraft.world.entity.animal.AbstractGolem
</summary>

```diff
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Bee getBreedOffspring(ServerLevel,AgableMob)
- Bee getBreedOffspring(ServerLevel,AgeableMob)
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
- PathNavigation access$3900(Bee)
+ PathNavigation access$4000(Bee)
+ Random access$3900(Bee)
- Random access$4000(Bee)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.Fox
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Fox getBreedOffspring(ServerLevel,AgableMob)
- Fox getBreedOffspring(ServerLevel,AgeableMob)
- void usePlayerItem(Player,InteractionHand,ItemStack)
+ void usePlayerItem(Player,ItemStack)
```

</details>












<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Cow getBreedOffspring(ServerLevel,AgableMob)
- Cow getBreedOffspring(ServerLevel,AgeableMob)
+ MushroomCow getBreedOffspring(ServerLevel,AgableMob)
- MushroomCow getBreedOffspring(ServerLevel,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
+ boolean hurt(DamageSource,float)
+ Ocelot getBreedOffspring(ServerLevel,AgableMob)
- Ocelot getBreedOffspring(ServerLevel,AgeableMob)
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
</summary>

```diff
- boolean lambda$canUse$0(LivingEntity)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Pig getBreedOffspring(ServerLevel,AgableMob)
- Pig getBreedOffspring(ServerLevel,AgeableMob)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ boolean hurt(DamageSource,float)
+ boolean isTemptingItem(Item)
- boolean isTemptingItem(ItemStack)
+ Rabbit getBreedOffspring(ServerLevel,AgableMob)
- Rabbit getBreedOffspring(ServerLevel,AgeableMob)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- ParticleOptions getInkParticle()
- SoundEvent getSquirtSound()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>




<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
- boolean hasInventoryChanged(Container)
- boolean lambda$getSlot$1(ItemStack)
- boolean lambda$getSlot$2(ItemStack)
+ boolean setSlot(int,ItemStack)
+ float getJumpRidingScale()
- SlotAccess createEquipmentSlotAccess(int,Predicate)
- SlotAccess getSlot(int)
+ void setJumpRidingScale(float)
+ void setOffspringAttributes(AgableMob,AbstractHorse)
- void setOffspringAttributes(AgeableMob,AbstractHorse)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.EnderDragonPart
</summary>

```diff
- boolean shouldBeSaved()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
+ void dropExperience(int)
```

</details>









<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame$1
</summary>

```diff
- boolean set(ItemStack)
- ItemStack get()
+ void <clinit>()
- void <init>(ItemFrame)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
- boolean lambda$tickBubbleColumn$0(Entity)
- ItemStack getPickResult()
```

</details>

<details>
<summary>
net.minecraft.world.entity.vehicle.DismountHelper
</summary>

```diff
- boolean canDismountTo(CollisionGetter,Vec3,LivingEntity,Pose)
+ Vec3 findDismountLocation(CollisionGetter,double,double,double,LivingEntity,Pose)
```

</details>


<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartHopper
</summary>

```diff
+ Level getLevel()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner$1
</summary>

```diff
+ BlockPos getPos()
+ Level getLevel()
+ void broadcastEvent(int)
- void broadcastEvent(Level,BlockPos,int)
```

</details>




<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
+ boolean consideredTheSameItem(ItemStack,ItemStack)
+ Slot getSlotFor(Container,int)
+ void addItem(int,ItemStack)
- void clearContainer(Player,Container)
+ void clearContainer(Player,Level,Container)
```

</details>


















<details>
<summary>
net.minecraft.world.item.BucketItem
</summary>

```diff
+ boolean emptyBucket(Player,Level,BlockPos,BlockHitResult)
- boolean emptyContents(Player,Level,BlockPos,BlockHitResult)
- void lambda$use$0(Player,SoundEvent)
```

</details>








<details>
<summary>
net.minecraft.world.item.FireworkRocketItem
</summary>

```diff
- ItemStack getDefaultInstance()
```

</details>

<details>
<summary>
net.minecraft.world.item.PickaxeItem
</summary>

```diff
- void lambda$static$0(Object2IntOpenHashMap)
```

</details>









<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
- boolean lambda$getNearbyEntities$2(LivingEntity)
- boolean lambda$getNearestEntity$1(LivingEntity)
- List getEntitiesOfClass(Class,AABB,Predicate)
+ List getLoadedEntitiesOfClass(Class,AABB,Predicate)
+ List getLoadedEntitiesOfClass(Class,AABB)
+ LivingEntity getNearestLoadedEntity(Class,TargetingConditions,LivingEntity,double,double,double,AABB)
```

</details>


<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
+ void <init>(GameRules,MinecraftServer)
```

</details>




<details>
<summary>
net.minecraft.world.level.GameType
</summary>

```diff
+ Component getDisplayName()
- Component getLongDisplayName()
- Component getShortDisplayName()
- GameType byNullableId(int)
- int getNullableId(GameType)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.AttachedStemBlock
</summary>

```diff
+ Item getSeedItem()
+ void <init>(StemGrownBlock,BlockBehaviour$Properties)
- void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.BaseEntityBlock
</summary>

```diff
- BlockEntityTicker createTickerHelper(BlockEntityType,BlockEntityType,BlockEntityTicker)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
- void checkPressed(Entity,Level,BlockPos,BlockState,int)
+ void checkPressed(Level,BlockPos,BlockState,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ boolean is(Block)
+ boolean is(Tag)
+ boolean isExceptionForConnection(Block)
- boolean isExceptionForConnection(BlockState)
- boolean shouldRenderFace(BlockState,BlockGetter,BlockPos,Direction,BlockPos)
+ boolean shouldRenderFace(BlockState,BlockGetter,BlockPos,Direction)
+ int getTickDelay(LevelReader)
- void handlePrecipitation(BlockState,Level,BlockPos,Biome$Precipitation)
+ void handleRain(Level,BlockPos)
+ void prepareRender(BlockGetter,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ BlockEntityType lambda$static$12()
- BlockEntityType lambda$static$14()
+ boolean lambda$static$13(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$15(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$28(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$30(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$35(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$37(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$48(BlockState,BlockGetter,BlockPos)
+ ConfiguredFeature lambda$static$35()
+ ConfiguredFeature lambda$static$36()
- ConfiguredFeature lambda$static$42()
- ConfiguredFeature lambda$static$43()
- ConfiguredFeature lambda$static$8()
- ConfiguredFeature lambda$static$9()
- int lambda$static$12(BlockState)
- int lambda$static$13(BlockState)
+ int lambda$static$14(BlockState)
+ int lambda$static$15(BlockState)
+ int lambda$static$21(BlockState)
+ int lambda$static$22(BlockState)
+ int lambda$static$23(BlockState)
+ int lambda$static$24(BlockState)
- int lambda$static$28(BlockState)
- int lambda$static$30(BlockState)
- int lambda$static$36(BlockState)
+ int lambda$static$37(BlockState)
- int lambda$static$40(BlockState)
- int lambda$static$41(BlockState)
- int lambda$static$44(BlockState)
- int lambda$static$45(BlockState)
- int lambda$static$46(BlockState)
- int lambda$static$47(BlockState)
- int lambda$static$49(BlockState)
+ int lambda$static$8(BlockState)
+ int lambda$static$9(BlockState)
- Item lambda$static$21()
- Item lambda$static$22()
- Item lambda$static$23()
- Item lambda$static$24()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ BlockState mirror(BlockState,Mirror)
+ BlockState rotate(BlockState,Rotation)
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
+ void <clinit>()
+ VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FallingBlock
</summary>

```diff
+ void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ boolean isSameFence(Block)
- boolean isSameFence(BlockState)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
- boolean isEmpty()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.GrassBlock
</summary>

```diff
- BlockState getBlockState(Random,BlockPos,ConfiguredFeature)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.Mirror
</summary>

```diff
- Component symbol()
- void <init>(String,int,Component,OctahedralGroup)
+ void <init>(String,int,OctahedralGroup)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
- boolean canOpen(BlockState,Level,BlockPos,ShulkerBoxBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
+ Item getSeedItem()
+ void <init>(StemGrownBlock,BlockBehaviour$Properties)
- void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.entity.BaseContainerBlockEntity
</summary>

```diff
- void <init>(BlockEntityType,BlockPos,BlockState)
+ void <init>(BlockEntityType)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.BedBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState,DyeColor)
- void <init>(BlockPos,BlockState)
+ void <init>(DyeColor)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntityType
</summary>

```diff
+ BlockEntity create()
- BlockEntity create(BlockPos,BlockState)
+ boolean isValid(Block)
- boolean isValid(BlockState)
- void <init>(BlockEntityType$BlockEntitySupplier,Set,Type)
+ void <init>(Supplier,Set,Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DispenserBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockEntityType,BlockPos,BlockState)
+ void <init>(BlockEntityType)
- void <init>(BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
- void bookAnimationTick(Level,BlockPos,BlockState,EnchantmentTableBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void tick()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
- Component deserializeTextSafe(String)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SmokerBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
</summary>

```diff
+ BlockPos getPos()
+ Level getLevel()
+ void broadcastEvent(int)
- void broadcastEvent(Level,BlockPos,int)
- void setNextSpawnData(Level,BlockPos,SpawnData)
+ void setNextSpawnData(SpawnData)
```

</details>







<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
- Block lambda$unpackTicks$8(BlockPos)
+ Block lambda$unpackTicks$9(BlockPos)
- boolean access$200(LevelChunk,BlockPos)
- boolean isInLevel()
- boolean isTicking(BlockPos)
- boolean lambda$getLights$5(BlockPos)
+ boolean lambda$getLights$6(BlockPos)
- boolean lambda$replaceWithPacketData$4(BitSet,BlockEntity)
+ boolean lambda$replaceWithPacketData$4(BlockPos)
+ boolean lambda$replaceWithPacketData$5(int,BlockPos)
+ ClassInstanceMultiMap[] getEntitySections()
+ Entity lambda$new$0(Entity)
+ Fluid lambda$unpackTicks$10(BlockPos)
- Fluid lambda$unpackTicks$9(BlockPos)
- GameEventDispatcher getEventDispatcher(int)
- GameEventDispatcher lambda$getEventDispatcher$0(int)
- int getHeight()
- int getMinBuildHeight()
- Level access$300(LevelChunk)
- LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$11(BlockEntity,BlockEntityTicker,BlockPos,LevelChunk$RebindableTickingBlockEntityWrapper)
+ LevelLightEngine getLightEngine()
- Logger access$400()
- LongSet lambda$addReferenceForFeature$7(StructureFeature)
+ LongSet lambda$addReferenceForFeature$8(StructureFeature)
- LongSet lambda$getReferencesForFeature$6(StructureFeature)
+ LongSet lambda$getReferencesForFeature$7(StructureFeature)
- TickingBlockEntity createTicker(BlockEntity,BlockEntityTicker)
+ void <init>(Level,ProtoChunk)
- void <init>(ServerLevel,ProtoChunk,Consumer)
- void addAndRegisterBlockEntity(BlockEntity)
+ void addBlockEntity(BlockEntity)
- void addGameEventListener(BlockEntity)
+ void getEntities(Entity,AABB,List,Predicate)
+ void getEntities(EntityType,AABB,List,Predicate)
+ void getEntitiesOfClass(Class,AABB,List,Predicate)
- void invalidateAllBlockEntities()
- void lambda$registerAllBlockEntitiesAfterLevelLoad$10(BlockEntity)
- void onBlockEntityRemove(BlockEntity)
- void registerAllBlockEntitiesAfterLevelLoad()
- void removeBlockEntityTicker(BlockPos)
+ void removeEntity(Entity,int)
+ void removeEntity(Entity)
- void removeGameEventListener(BlockEntity)
- void replaceWithPacketData(ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,BitSet)
+ void replaceWithPacketData(ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int)
- void setBlockEntity(BlockEntity)
+ void setBlockEntity(BlockPos,BlockEntity)
+ void setLastSaveHadEntities(boolean)
+ void setLastSaveTime(long)
- void updateBlockEntityTicker(BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker
</summary>

```diff
- CompletableFuture loadAsync(ChunkPos)
+ Either lambda$load$2(ChunkPos)
- Either lambda$loadAsync$2(ChunkPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.Decoratable
</summary>

```diff
+ Object chance(int)
- Object rarity(int)
```

</details>













<details>
<summary>
net.minecraft.world.level.material.LavaFluid
</summary>

```diff
- Optional getPickupSound()
```

</details>


































<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
- void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
+ void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelData
</summary>

```diff
+ String lambda$fillCrashReportCategory$0()
- String lambda$fillCrashReportCategory$0(LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
+ void fillCrashReportCategory(CrashReportCategory)
```

</details>













<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LimitCount
</summary>

```diff
+ IntLimiter access$000(LimitCount)
- IntRange access$000(LimitCount)
+ LootItemConditionalFunction$Builder limitCount(IntLimiter)
- LootItemConditionalFunction$Builder limitCount(IntRange)
+ LootItemFunction lambda$limitCount$0(IntLimiter,LootItemCondition[])
- LootItemFunction lambda$limitCount$0(IntRange,LootItemCondition[])
- Set getReferencedContextParams()
+ void <init>(LootItemCondition[],IntLimiter,LimitCount$1)
+ void <init>(LootItemCondition[],IntLimiter)
- void <init>(LootItemCondition[],IntRange,LimitCount$1)
- void <init>(LootItemCondition[],IntRange)
```

</details>








<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
</summary>

```diff
- NumberProvider access$400(SetAttributesFunction$Modifier)
+ RandomValueBounds access$400(SetAttributesFunction$Modifier)
- void <init>(String,Attribute,AttributeModifier$Operation,NumberProvider,EquipmentSlot[],UUID,SetAttributesFunction$1)
- void <init>(String,Attribute,AttributeModifier$Operation,NumberProvider,EquipmentSlot[],UUID)
+ void <init>(String,Attribute,AttributeModifier$Operation,RandomValueBounds,EquipmentSlot[],UUID,SetAttributesFunction$1)
+ void <init>(String,Attribute,AttributeModifier$Operation,RandomValueBounds,EquipmentSlot[],UUID)
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
</summary>

```diff
- boolean access$100(SetItemCountFunction)
- LootItemConditionalFunction$Builder setCount(NumberProvider,boolean)
- LootItemConditionalFunction$Builder setCount(NumberProvider)
+ LootItemConditionalFunction$Builder setCount(RandomIntGenerator)
- LootItemFunction lambda$setCount$0(NumberProvider,LootItemCondition[])
+ LootItemFunction lambda$setCount$0(RandomIntGenerator,LootItemCondition[])
- LootItemFunction lambda$setCount$1(NumberProvider,boolean,LootItemCondition[])
- NumberProvider access$000(SetItemCountFunction)
+ RandomIntGenerator access$000(SetItemCountFunction)
- Set getReferencedContextParams()
- void <init>(LootItemCondition[],NumberProvider,boolean,SetItemCountFunction$1)
- void <init>(LootItemCondition[],NumberProvider,boolean)
+ void <init>(LootItemCondition[],RandomIntGenerator,SetItemCountFunction$1)
+ void <init>(LootItemCondition[],RandomIntGenerator)
```

</details>






































<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.TimeCheck
</summary>

```diff
- IntRange access$200(TimeCheck)
+ RandomValueBounds access$200(TimeCheck)
- Set getReferencedContextParams()
- TimeCheck$Builder time(IntRange)
+ TimeCheck$Builder time(RandomValueBounds)
- void <init>(Long,IntRange,TimeCheck$1)
- void <init>(Long,IntRange)
+ void <init>(Long,RandomValueBounds,TimeCheck$1)
+ void <init>(Long,RandomValueBounds)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
</summary>

```diff
- void <init>(IntRange)
+ void <init>(RandomValueBounds)
```

</details>














<details>
<summary>
net.minecraft.world.phys.shapes.DiscreteCubeMerger
</summary>

```diff
- int size()
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
- boolean hasItemOnFeet(Item)
- Optional getEntity()
+ void <init>(boolean,double,Item,Predicate)
- void <init>(boolean,double,ItemStack,ItemStack,Predicate,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.IdenticalMerger
</summary>

```diff
- int size()
```

</details>


<details>
<summary>
net.minecraft.world.scores.Score
</summary>

```diff
+ void remove(int)
```

</details>
<details>
<summary>
net.minecraft.world.scores.ScoreboardSaveData
</summary>

```diff
- ScoreboardSaveData load(CompoundTag)
+ void <clinit>()
+ void <init>()
- void <init>(Scoreboard)
+ void load(CompoundTag)
+ void setScoreboard(Scoreboard)
```

</details>
<details>
<summary>
net.minecraft.world.scores.Team$CollisionRule
</summary>

```diff
+ String[] getAllNames()
```

</details>


<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferBuilder$1
- com.mojang.blaze3d.vertex.BufferBuilder$DrawState
+ com.mojang.blaze3d.vertex.BufferBuilder$State
- com.mojang.blaze3d.vertex.BufferUploader
+ com.mojang.blaze3d.vertex.BufferVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultedVertexConsumer
- com.mojang.blaze3d.vertex.DefaultVertexFormat
- com.mojang.blaze3d.vertex.PoseStack
+ com.mojang.blaze3d.vertex.PoseStack$1
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
- com.mojang.blaze3d.vertex.Tesselator
+ com.mojang.blaze3d.vertex.VertexBuffer
- com.mojang.blaze3d.vertex.VertexConsumer
+ com.mojang.blaze3d.vertex.VertexFormat
- com.mojang.blaze3d.vertex.VertexFormat$1
- com.mojang.blaze3d.vertex.VertexFormat$Mode
+ com.mojang.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
+ com.mojang.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
+ com.mojang.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$2
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetType
+ com.mojang.realmsclient.gui.screens.RealmsScreenWithCallback
- com.mojang.realmsclient.gui.task.IntervalBasedStartupDelay
- com.mojang.realmsclient.gui.task.RepeatableTask
- com.mojang.realmsclient.util.RealmsPersistence
+ com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- com.mojang.realmsclient.util.RealmsTextureManager
+ com.mojang.realmsclient.util.RealmsTextureManager$1
- com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
+ com.mojang.realmsclient.util.RealmsUtil
- com.mojang.realmsclient.util.RealmsUtil$1
+ com.mojang.realmsclient.util.SkinProcessor
- com.mojang.realmsclient.util.task.ResettingTemplateWorldTask
- com.mojang.realmsclient.util.TextRenderingUtils
+ com.mojang.realmsclient.util.TextRenderingUtils$Line
- com.mojang.realmsclient.util.TextRenderingUtils$LineSegment
+ com.mojang.realmsclient.util.UploadTokenCache
- com.mojang.realmsclient.util.WorldGenerationInfo
+ net.minecraft.client.Camera
- net.minecraft.client.CameraType
+ net.minecraft.client.ClientBrandRetriever
- net.minecraft.client.ClientRecipeBook
+ net.minecraft.client.CloudStatus
- net.minecraft.client.ComponentCollector
+ net.minecraft.client.CycleOption
- net.minecraft.client.CycleOption$OptionSetter
- net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$TooltipSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.OptionButton
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$1
- net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ net.minecraft.client.gui.components.SliderButton
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.SubtitleOverlay
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.TickableWidget
- net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$1
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.TooltipAccessor
+ net.minecraft.client.gui.components.VolumeSlider
- net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$1
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$1
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.MissingGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.WhiteGlyph
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$1
+ net.minecraft.client.gui.font.providers.BitmapProvider$Builder
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$1
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.AlertScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.controls.ControlList$1
- net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.ControlList$Entry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DatapackLoadFailureScreen
- net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
- net.minecraft.client.gui.screens.inventory.BookViewScreen
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$1
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.DispenserScreen
+ net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
- net.minecraft.client.gui.screens.inventory.EnchantmentNames
+ net.minecraft.client.gui.screens.inventory.EnchantmentScreen
- net.minecraft.client.gui.screens.inventory.FurnaceScreen
+ net.minecraft.client.gui.screens.inventory.GrindstoneScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.LanguageSelectScreen
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ net.minecraft.client.gui.screens.LevelLoadingScreen
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.OptionsScreen
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PopupScreen
+ net.minecraft.client.gui.screens.PopupScreen$ButtonOption
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SimpleOptionsSubScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$2
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$4
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
+ net.minecraft.client.gui.screens.worldselection.EditWorldScreen
- net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
+ net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
- net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$1
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$3
- net.minecraft.client.model.BatModel
+ net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BlazeModel
+ net.minecraft.client.model.BoatModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestedHorseModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
- net.minecraft.client.model.ColorableHierarchicalModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
- net.minecraft.client.model.geom.builders.CubeDeformation
- net.minecraft.client.model.geom.builders.LayerDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
- net.minecraft.client.model.geom.builders.UVPair
- net.minecraft.client.model.geom.EntityModelSet
- net.minecraft.client.model.geom.ModelLayerLocation
- net.minecraft.client.model.geom.ModelPart$Visitor
- net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HumanoidHeadModel
- net.minecraft.client.model.HumanoidModel
+ net.minecraft.client.model.HumanoidModel$1
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.LlamaModel
+ net.minecraft.client.model.LlamaSpitModel
- net.minecraft.client.model.MinecartModel
+ net.minecraft.client.model.Model
- net.minecraft.client.model.ModelUtils
+ net.minecraft.client.model.OcelotModel
- net.minecraft.client.model.PandaModel
+ net.minecraft.client.model.ParrotModel
- net.minecraft.client.model.ParrotModel$1
+ net.minecraft.client.model.ParrotModel$State
- net.minecraft.client.model.PhantomModel
- net.minecraft.client.model.PiglinModel
+ net.minecraft.client.model.PigModel
+ net.minecraft.client.model.PlayerModel
- net.minecraft.client.model.PolarBearModel
+ net.minecraft.client.model.PufferfishBigModel
- net.minecraft.client.model.PufferfishMidModel
+ net.minecraft.client.model.PufferfishSmallModel
- net.minecraft.client.model.QuadrupedModel
+ net.minecraft.client.model.RabbitModel
- net.minecraft.client.model.RavagerModel
+ net.minecraft.client.model.SalmonModel
- net.minecraft.client.model.SheepFurModel
+ net.minecraft.client.model.SheepModel
- net.minecraft.client.model.ShieldModel
+ net.minecraft.client.model.ShulkerBulletModel
- net.minecraft.client.model.ShulkerModel
+ net.minecraft.client.model.SilverfishModel
- net.minecraft.client.model.SkeletonModel
+ net.minecraft.client.model.SkullModel
- net.minecraft.client.model.SkullModelBase
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
- net.minecraft.client.multiplayer.PlayerInfo
+ net.minecraft.client.multiplayer.ServerAddress
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$1
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BarrierParticle
+ net.minecraft.client.particle.BarrierParticle$1
- net.minecraft.client.particle.BarrierParticle$Provider
+ net.minecraft.client.particle.BaseAshSmokeParticle
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$1
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$1
+ net.minecraft.client.particle.BubbleColumnUpParticle$Provider
- net.minecraft.client.particle.BubbleParticle
+ net.minecraft.client.particle.BubbleParticle$1
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$1
+ net.minecraft.client.particle.BubblePopParticle$Provider
- net.minecraft.client.particle.CampfireSmokeParticle
+ net.minecraft.client.particle.CampfireSmokeParticle$1
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$1
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$1
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$1
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$DripstoneLavaFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneWaterFallProvider
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle$1
- net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
- net.minecraft.client.particle.GlowParticle$1
- net.minecraft.client.particle.SnowflakeParticle$Provider
- net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.SuspendedParticle
+ net.minecraft.client.particle.SuspendedParticle$1
- net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
+ net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
- net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
+ net.minecraft.client.particle.SuspendedTownParticle
- net.minecraft.client.particle.SuspendedTownParticle$1
+ net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
- net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
- net.minecraft.client.particle.SuspendedTownParticle$Provider
+ net.minecraft.client.particle.TerrainParticle
- net.minecraft.client.particle.TerrainParticle$Provider
+ net.minecraft.client.particle.TextureSheetParticle
- net.minecraft.client.particle.TotemParticle
+ net.minecraft.client.particle.TotemParticle$1
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.VibrationSignalParticle
- net.minecraft.client.particle.VibrationSignalParticle$Provider
+ net.minecraft.client.renderer.banner.package-info
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverrides
+ net.minecraft.client.renderer.block.model.ItemTransform
- net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms
- net.minecraft.client.renderer.block.model.ItemTransforms$1
+ net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
+ net.minecraft.client.renderer.block.model.multipart.AndCondition
- net.minecraft.client.renderer.block.model.multipart.Condition
+ net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
- net.minecraft.client.renderer.block.model.multipart.MultiPart
+ net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
+ net.minecraft.client.renderer.block.model.MultiVariant
- net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
- net.minecraft.client.renderer.block.model.package-info
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
- net.minecraft.client.renderer.block.statemap.package-info
+ net.minecraft.client.renderer.blockentity.BannerRenderer
- net.minecraft.client.renderer.blockentity.BeaconRenderer
+ net.minecraft.client.renderer.blockentity.BedRenderer
- net.minecraft.client.renderer.blockentity.BellRenderer
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
- net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ net.minecraft.client.renderer.debug.HeightMapRenderer
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GlowSquidRenderer
- net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.RenderLayer
- net.minecraft.client.renderer.entity.layers.SaddleLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StrayClothingLayer
- net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WitchItemLayer
- net.minecraft.client.renderer.entity.layers.WitherArmorLayer
+ net.minecraft.client.renderer.entity.layers.WolfCollarLayer
+ net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemProperties$2
+ net.minecraft.client.renderer.item.ItemProperties$CompassWobble
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
- net.minecraft.client.renderer.ItemModelShaper
+ net.minecraft.client.renderer.LevelRenderer
- net.minecraft.client.renderer.LevelRenderer$1
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
+ net.minecraft.client.renderer.LightTexture
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$1
- net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
+ net.minecraft.client.renderer.PanoramaRenderer
- net.minecraft.client.renderer.PostChain
+ net.minecraft.client.renderer.PostPass
- net.minecraft.client.renderer.Rect2i
+ net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
- net.minecraft.client.renderer.RenderStateShard$FogStateShard
+ net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
+ net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$OutputStateShard
- net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
+ net.minecraft.client.renderer.RenderStateShard$PortalTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$1
+ net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.AtlasSet
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
- net.minecraft.client.renderer.texture.package-info
- net.minecraft.client.renderer.texture.PreloadedTexture
+ net.minecraft.client.renderer.texture.SimpleTexture
- net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
+ net.minecraft.client.renderer.texture.Stitcher
- net.minecraft.client.renderer.texture.Stitcher$Holder
+ net.minecraft.client.renderer.texture.Stitcher$Region
- net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
+ net.minecraft.client.renderer.texture.StitcherException
- net.minecraft.client.renderer.texture.TextureAtlas
+ net.minecraft.client.renderer.texture.TextureAtlas$Preparations
- net.minecraft.client.renderer.texture.TextureAtlasSprite
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$1
- net.minecraft.client.renderer.texture.TextureAtlasSprite$AnimatedTexture
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
- net.minecraft.client.renderer.texture.TextureManager
+ net.minecraft.client.renderer.texture.Tickable
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
+ net.minecraft.client.resources.AssetIndex
- net.minecraft.client.resources.ClientPackSource
+ net.minecraft.client.resources.ClientPackSource$1
- net.minecraft.client.resources.ClientPackSource$2
+ net.minecraft.client.resources.DefaultClientPackResources
- net.minecraft.client.resources.DefaultPlayerSkin
+ net.minecraft.client.resources.DirectAssetIndex
- net.minecraft.client.resources.FoliageColorReloadListener
+ net.minecraft.client.resources.GrassColorReloadListener
- net.minecraft.client.resources.language.ClientLanguage
+ net.minecraft.client.resources.language.FormattedBidiReorder
- net.minecraft.client.resources.language.I18n
+ net.minecraft.client.resources.language.LanguageInfo
- net.minecraft.client.resources.language.LanguageManager
+ net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyPackResourcesAdapter
+ net.minecraft.client.resources.LegacyStuffWrapper
- net.minecraft.client.resources.metadata.animation.AnimationFrame
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.PackResourcesAdapterV4
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$SkinTextureCallback
- net.minecraft.client.resources.SplashManager
+ net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
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
+ net.minecraft.commands.arguments.item.FunctionArgument
- net.minecraft.commands.arguments.item.FunctionArgument$1
+ net.minecraft.commands.arguments.item.FunctionArgument$2
- net.minecraft.commands.arguments.item.FunctionArgument$Result
+ net.minecraft.commands.arguments.item.ItemArgument
- net.minecraft.commands.arguments.item.ItemInput
+ net.minecraft.commands.arguments.item.ItemParser
- net.minecraft.commands.arguments.item.ItemPredicateArgument
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
- net.minecraft.commands.arguments.item.package-info
+ net.minecraft.commands.arguments.NbtPathArgument$ListElementFunction
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
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ScoreboardSlotArgument
- net.minecraft.commands.arguments.ScoreHolderArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.arguments.selector.EntitySelector
+ net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.arguments.TeamArgument
+ net.minecraft.commands.arguments.TimeArgument
- net.minecraft.commands.arguments.UuidArgument
- net.minecraft.core.cauldron.CauldronInteraction
- net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.core.Registry
+ net.minecraft.core.RegistryAccess
- net.minecraft.core.RegistryAccess$RegistryData
+ net.minecraft.core.RegistryAccess$RegistryHolder
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableUUID
- net.minecraft.core.Vec3i
+ net.minecraft.core.WritableRegistry
- net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily$1
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapedRecipeBuilder$Result
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder$1
+ net.minecraft.data.recipes.UpgradeRecipeBuilder
- net.minecraft.data.recipes.UpgradeRecipeBuilder$Result
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$1
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.biome.BiomeReport
- net.minecraft.data.worldgen.biome.Biomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.biome.VanillaBiomes
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.DesertVillagePools
+ net.minecraft.data.worldgen.Features
- net.minecraft.data.worldgen.Features$Configs
+ net.minecraft.data.worldgen.Features$Decorators
- net.minecraft.data.worldgen.Features$States
+ net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.PlainVillagePools
+ net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.ProcessorLists
+ net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.data.worldgen.SurfaceBuilders
+ net.minecraft.data.worldgen.TaigaVillagePools
- net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestHelper$1
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerAckPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerAckPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
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
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$10
+ net.minecraft.network.syncher.EntityDataSerializers$11
- net.minecraft.network.syncher.EntityDataSerializers$12
+ net.minecraft.network.syncher.EntityDataSerializers$13
- net.minecraft.network.syncher.EntityDataSerializers$14
+ net.minecraft.network.syncher.EntityDataSerializers$15
- net.minecraft.network.syncher.EntityDataSerializers$16
+ net.minecraft.network.syncher.EntityDataSerializers$17
- net.minecraft.network.syncher.EntityDataSerializers$18
+ net.minecraft.network.syncher.EntityDataSerializers$19
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.EntityDataSerializers$8
+ net.minecraft.network.syncher.EntityDataSerializers$9
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.NarrationHelper
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsBridge
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.ReplaceItemCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.Eula
- net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$1
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerResources
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$1
+ net.minecraft.tags.StaticTagHelper$Wrapper
- net.minecraft.tags.StaticTags
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$1
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
- net.minecraft.tags.TagContainer$Builder
- net.minecraft.tags.TagManager$1
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2688
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
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.InsensitiveStringMap
- net.minecraft.util.IntRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$1
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$1
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.UniformFloat
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.entity.AgableMob$AgableMobGroupData
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
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
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
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
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.BossMob
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
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
+ net.minecraft.world.entity.monster.Evoker$1
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$1
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$1
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
+ net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
- net.minecraft.world.entity.monster.Witch
+ net.minecraft.world.entity.monster.WitherSkeleton
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
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
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
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
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.FishBucketItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$1
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$1
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeFullBlock
- net.minecraft.world.level.block.ChangeOverTimeStairBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
- net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndRodBlock$1
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassPathBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
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
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
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
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVines
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationPath
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BaseDiskFeature
- net.minecraft.world.level.levelgen.feature.BastionFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
+ net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowLichenFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JigsawFeature
- net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$1
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
+ net.minecraft.world.level.levelgen.feature.StructureFeature
- net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
+ net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlideSettings
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
+ net.minecraft.world.level.levelgen.placement.EdgeDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
+ net.minecraft.world.level.levelgen.placement.SquareDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.StructureSettings
- net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.FlatDataLayer
- net.minecraft.world.level.lighting.LayerLightEngine
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.LightLayer
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
- net.minecraft.world.level.storage.loot.Deserializers
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootItem$1
+ net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.LootTableReference$1
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
+ net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$1
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$InlineSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
+ net.minecraft.world.level.storage.loot.IntLimiter$1
- net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$1
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$1
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootPool$Serializer
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$1
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$1
+ net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$1
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$1
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$1
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.RandomIntGenerators
+ net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
- net.minecraft.world.level.storage.loot.Serializer
+ net.minecraft.world.level.storage.loot.SerializerType
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.McRegionUpgrader
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.ShulkerSharedHelper
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.systems.RenderSystem +77M -74M | +2P
```
```
XXX.mojang.math.Matrix4f +1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen +14M -12M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry +1M -1M
```
```
XXX.realmsclient.gui.RealmsDataFetcher +9M -10M | +8P -5P
```
```
XXX.gui.screens.RealmsBackupInfoScreen +1M | +1P
```
```
XXX.gui.screens.RealmsResetWorldScreen +7M -8M | -3P
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen +3M -4M | +1P -1P
```
```
XXX.util.task.GetServerDetailsTask +7M -4M
```
```
net.minecraft.CrashReportCategory +5M -5M
```
```
net.minecraft.Util +4M
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.EntityTypePredicate +1M
```
```
XXX.advancements.critereon.EntityTypePredicate$TagPredicate +1M
```
```
XXX.minecraft.client.Minecraft$1 -1P
```
```
XXX.client.gui.GuiComponent +1M
```
```
XXX.gui.components.BossHealthOverlay -1M
```
```
XXX.gui.components.LerpingBossEvent +2M -2M
```
```
XXX.screens.inventory.LoomScreen +1M
```
```
XXX.screens.worldselection.CreateWorldScreen +25M -28M | +5P -6P
```
```
XXX.gui.spectator.PlayerMenuItem +1P -1P
```
```
XXX.client.model.ArmorStandModel +2M -2M | +2P -2P
```
```
XXX.client.model.HoglinModel +2M -1M | +4P -4P
```
```
XXX.client.model.SnowGolemModel +3M -2M | +4P -4P
```
```
XXX.client.model.SquidModel +5M -2M | +1P -2P
```
```
XXX.client.model.TridentModel +2M -1M | +1P -1P
```
```
XXX.client.model.TropicalFishModelB +3M -2M | +1P -5P
```
```
XXX.client.model.VexModel +2M -1M
```
```
XXX.client.model.VillagerModel +3M -3M | +3P -5P
```
```
XXX.client.model.WitherBossModel +4M -3M | +6P -3P
```
```
XXX.client.model.ZombieModel +1M -2M
```
```
XXX.model.dragon.DragonHeadModel +2M -1M
```
```
XXX.model.geom.ModelPart +10M -15M | +2P -7P
```
```
XXX.client.multiplayer.ClientAdvancements -1M
```
```
XXX.client.multiplayer.ClientChunkCache +1M -2M
```
```
XXX.client.multiplayer.ClientLevel +18M -14M | +2P -1P
```
```
XXX.client.multiplayer.ClientLevel$ClientLevelData +1M -1M
```
```
XXX.client.particle.SquidInkParticle +2M -2M
```
```
XXX.client.player.AbstractClientPlayer -1M
```
```
XXX.client.renderer.GameRenderer +2M -1M
```
```
XXX.renderer.blockentity.ChestRenderer +4M -1M
```
```
XXX.renderer.blockentity.EnchantTableRenderer +1M -1M
```
```
XXX.renderer.blockentity.PistonHeadRenderer +1M -1M
```
```
XXX.renderer.blockentity.SignRenderer +7M -3M | +2P -1P
```
```
XXX.renderer.blockentity.SkullBlockRenderer +3M -3M | +1P -1P
```
```
XXX.renderer.blockentity.StructureBlockRenderer +1M -1M
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +1M -1M
```
```
XXX.renderer.chunk.VisGraph -1M
```
```
XXX.renderer.debug.DebugRenderer +1P
```
```
XXX.renderer.entity.BeeRenderer +1M -1M
```
```
XXX.renderer.entity.BoatRenderer +3M -2M | +1P -2P
```
```
XXX.renderer.entity.CaveSpiderRenderer +1M -1M
```
```
XXX.renderer.entity.ChickenRenderer +1M -1M
```
```
XXX.renderer.entity.CowRenderer +1M -1M
```
```
XXX.renderer.entity.DolphinRenderer +1M -1M
```
```
XXX.renderer.entity.DrownedRenderer +1M -1M
```
```
XXX.renderer.entity.EndCrystalRenderer +2M -1M
```
```
XXX.renderer.entity.EnderDragonRenderer$DragonModel +1M -1M
```
```
XXX.renderer.entity.EndermiteRenderer +1M -1M
```
```
XXX.renderer.entity.EntityRenderer +1M -2M | +1P
```
```
XXX.renderer.entity.HoglinRenderer +1M -1M
```
```
XXX.renderer.entity.HumanoidMobRenderer +2M -2M
```
```
XXX.renderer.entity.IllagerRenderer +1M -1M
```
```
XXX.renderer.entity.ItemEntityRenderer +1M -1M
```
```
XXX.renderer.entity.ItemRenderer +7M -6M | +1P
```
```
XXX.renderer.entity.LightningBoltRenderer +1M -1M
```
```
XXX.renderer.entity.LlamaSpitRenderer +1M -1M
```
```
XXX.renderer.entity.MinecartRenderer +1M -1M
```
```
XXX.renderer.entity.MushroomCowRenderer +1M -1M
```
```
XXX.renderer.entity.PaintingRenderer +1M -1M
```
```
XXX.renderer.entity.ParrotRenderer +1M -1M
```
```
XXX.renderer.entity.PigRenderer +1M -1M
```
```
XXX.renderer.entity.PillagerRenderer +1M -1M
```
```
XXX.renderer.entity.PufferfishRenderer +1M -1M | +3P -3P
```
```
XXX.renderer.entity.RavagerRenderer +1M -1M
```
```
XXX.renderer.entity.SalmonRenderer +1M -1M
```
```
XXX.renderer.entity.ShulkerBulletRenderer +1M -1M
```
```
XXX.renderer.entity.SilverfishRenderer +1M -1M
```
```
XXX.renderer.entity.SlimeRenderer +1M -1M
```
```
XXX.renderer.entity.SpectralArrowRenderer +1M -1M
```
```
XXX.renderer.entity.SquidRenderer +1M -1M
```
```
XXX.renderer.entity.StriderRenderer +1M -1M
```
```
XXX.renderer.entity.ThrownTridentRenderer +1M -1M
```
```
XXX.renderer.entity.TntMinecartRenderer +1M -1M
```
```
XXX.renderer.entity.TropicalFishRenderer +1M -1M | +2P -2P
```
```
XXX.renderer.entity.UndeadHorseRenderer +1M -1M
```
```
XXX.renderer.entity.VillagerRenderer +1M -1M
```
```
XXX.renderer.entity.WitchRenderer +1M -1M
```
```
XXX.renderer.entity.WitherSkeletonRenderer +1M -1M
```
```
XXX.renderer.entity.WolfRenderer +1M -1M
```
```
XXX.renderer.entity.ZombieRenderer +2M -1M
```
```
XXX.entity.layers.ArrowLayer +1M -1M | -1P
```
```
XXX.entity.layers.CatCollarLayer +1M -1M
```
```
XXX.entity.layers.DrownedOuterLayer +1M -1M
```
```
XXX.entity.layers.HorseArmorLayer +1M -1M
```
```
XXX.entity.layers.ParrotOnShoulderLayer +1M -1M
```
```
XXX.resources.sounds.AbstractSoundInstance -1M | -1P
```
```
XXX.client.server.LanServer -1M
```
```
XXX.minecraft.commands.CommandFunction$CommandEntry +1M -1M
```
```
XXX.minecraft.commands.CommandFunction$FunctionEntry +2M -2M
```
```
XXX.commands.arguments.AngleArgument +1P
```
```
XXX.minecraft.core.BlockPos +1M -1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +6M -3M
```
```
XXX.minecraft.core.BlockSourceImpl -1M
```
```
XXX.data.models.BlockModelGenerators$BlockFamilyProvider +10M -2M | +2P
```
```
XXX.models.model.ModelTemplates +9P
```
```
XXX.models.model.TextureSlot +3P
```
```
XXX.gametest.framework.GameTestSequence +6M -4M
```
```
XXX.gametest.framework.GameTestServer +1M -2M
```
```
XXX.gametest.framework.GameTestTicker +1P -1P
```
```
XXX.gametest.framework.StructureUtils +7M -4M | +1P
```
```
XXX.gametest.framework.TestFunction +4M | +2P
```
```
XXX.minecraft.nbt.ListTag +1M -2M | -1P
```
```
XXX.minecraft.nbt.LongArrayTag +1M -1M
```
```
XXX.minecraft.nbt.LongTag +1M -2M
```
```
XXX.minecraft.nbt.NumericTag +1M
```
```
XXX.minecraft.nbt.Tag -4M | +1P -5P
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.server.commands.SpreadPlayersCommand$Position +3M -4M
```
```
XXX.server.dedicated.DedicatedServer +2M -1M
```
```
XXX.server.dedicated.DedicatedServerProperties -1M | +1P -1P
```
```
XXX.server.level.ChunkMap +27M -26M | +1P
```
```
XXX.server.level.DemoMode +1M -1M
```
```
XXX.packs.repository.Pack$PackConstructor +1P -1P
```
```
XXX.packs.repository.PackCompatibility +2M -1M
```
```
XXX.packs.repository.ServerPacksSource +1M | +1P
```
```
XXX.packs.resources.ReloadableResourceManager +1P -2P
```
```
XXX.packs.resources.SimpleReloadableResourceManager +2M -4M | -1P
```
```
XXX.server.players.PlayerList +1M -4M | -1P
```
```
XXX.server.players.ServerOpList +1M -2M
```
```
XXX.server.players.UserBanList +1M -1M
```
```
XXX.server.players.UserWhiteList +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents +89P
```
```
XXX.minecraft.stats.StatType -1M
```
```
XXX.minecraft.tags.BlockTags -1M | +7P
```
```
XXX.minecraft.tags.FluidTags +1M -1M | +1P
```
```
XXX.minecraft.tags.TagContainer +14M -3M | +2P -4P
```
```
XXX.minecraft.tags.TagLoader +20M -8M | -1P
```
```
XXX.datafix.fixes.JigsawRotationFix +1P -1P
```
```
XXX.world.damagesource.DamageSource +4M | +5P
```
```
XXX.world.effect.MobEffectInstance -1M | -1P
```
```
XXX.world.entity.Entity +47M -19M | +7P -9P
```
```
XXX.world.entity.EquipmentSlot +1M
```
```
XXX.world.entity.ExperienceOrb +8M -1M | +1P -3P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +2M | +1P -1P
```
```
XXX.ai.behavior.SetWalkTargetFromLookTarget +2M | +1P -1P
```
```
XXX.ai.goal.AvoidEntityGoal +1M
```
```
XXX.ai.goal.TemptGoal +1M -2M | +1P
```
```
XXX.ai.sensing.AdultSensor +6M -6M
```
```
XXX.ai.sensing.SensorType +1M | +2P
```
```
XXX.ai.util.GoalUtils +7M
```
```
XXX.village.poi.PoiManager +1M -1M
```
```
XXX.entity.ambient.Bat +1M -1M
```
```
XXX.entity.animal.AbstractFish +1M
```
```
XXX.entity.animal.Animal +1M -1M
```
```
XXX.entity.animal.Panda +1M -1M
```
```
XXX.entity.animal.PolarBear +1M -1M
```
```
XXX.entity.animal.Sheep +2M -2M
```
```
XXX.boss.enderdragon.EndCrystal +1M
```
```
XXX.entity.decoration.ArmorStand +1M -1M
```
```
XXX.entity.decoration.ItemFrame +6M -1M
```
```
XXX.entity.vehicle.MinecartSpawner +3M | +1P
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.inventory.AbstractFurnaceMenu +1M -1M
```
```
XXX.world.item.ArmorItem +1M
```
```
XXX.world.item.BlockItem +2M
```
```
XXX.world.item.DyeColor -1M | -2P
```
```
XXX.world.item.ElytraItem +1M
```
```
XXX.world.level.EmptyBlockGetter +2M
```
```
XXX.world.level.ForcedChunksSavedData +2M -1M
```
```
XXX.world.level.Level +8M -14M | +6P -6P
```
```
XXX.world.level.LevelAccessor +4M -1M | +1P
```
```
XXX.level.block.AnvilBlock +2M -1M
```
```
XXX.level.block.BaseRailBlock +2M | +1P
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +2M -1M
```
```
XXX.level.block.BellBlock +2M -1M
```
```
XXX.level.block.BlastFurnaceBlock +2M -1M
```
```
XXX.level.block.BubbleColumnBlock +2M -1M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.DropperBlock +1M -1M
```
```
XXX.level.block.EndGatewayBlock +2M -1M
```
```
XXX.level.block.FurnaceBlock +2M -1M
```
```
XXX.level.block.LiquidBlock +2M -1M
```
```
XXX.level.block.SimpleWaterloggedBlock +2M -1M
```
```
XXX.level.block.SmokerBlock +2M -1M
```
```
XXX.level.block.SoulFireBlock +1M -1M
```
```
XXX.level.block.SoundType +14P
```
```
XXX.level.block.StairBlock -1M
```
```
XXX.block.entity.BeaconBlockEntity +7M -7M
```
```
XXX.block.entity.BeehiveBlockEntity +5M -6M
```
```
XXX.block.entity.BellBlockEntity +12M -9M
```
```
XXX.block.entity.DaylightDetectorBlockEntity +1M -2M
```
```
XXX.block.entity.DropperBlockEntity +1M -1M
```
```
XXX.block.entity.EnderChestBlockEntity +5M -5M | +2P -4P
```
```
XXX.block.entity.ShulkerBoxBlockEntity +7M -9M | -1P
```
```
XXX.block.entity.SkullBlockEntity +3M -3M
```
```
XXX.block.entity.SpawnerBlockEntity +4M -3M
```
```
XXX.block.entity.StructureBlockEntity +2M -4M
```
```
XXX.level.chunk.ImposterProtoChunk +1M -3M
```
```
XXX.chunk.storage.OldChunkStorage +1M | +1P
```
```
XXX.level.levelgen.DebugLevelSource +1M -1M
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M
```
```
XXX.level.material.Material +3P
```
```
XXX.level.material.WaterFluid +1M
```
```
XXX.newbiome.context.BigContext -1P
```
```
XXX.newbiome.context.LazyAreaContext -1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer +8M -2M | +1P
```
```
XXX.level.storage.CommandStorage$Container +4M -2M
```
```
XXX.level.storage.DimensionDataStorage +5M -4M
```
```
XXX.level.storage.LevelSummary +1M -1M
```
```
XXX.loot.functions.EnchantWithLevelsFunction +5M -4M | +1P -1P
```
```
XXX.loot.functions.EnchantWithLevelsFunction$Builder +1M -1M | +1P -1P
```
```
XXX.loot.functions.LootingEnchantFunction +4M -4M | +1P -1P
```
```
XXX.loot.functions.LootingEnchantFunction$Builder +1M -1M | +1P -1P
```
```
XXX.loot.functions.SetAttributesFunction +3M -1M
```
```
XXX.loot.functions.SetAttributesFunction$ModifierBuilder +1M -1M | +1P -1P
```
```
XXX.loot.functions.SetItemDamageFunction +9M -5M | +2P -1P
```
```
XXX.loot.functions.SetStewEffectFunction +2M
```
```
XXX.loot.functions.SetStewEffectFunction$Builder +1M -1M
```
```
XXX.loot.predicates.EntityHasScoreCondition +2M -1M
```
```
XXX.loot.predicates.EntityHasScoreCondition$Builder +1M -1M
```
```
XXX.world.phys.AABB -3M
```
```
XXX.world.phys.Vec3 +3M | +1P
```
```
XXX.phys.shapes.BitSetDiscreteVoxelShape +6M -3M
```
```
XXX.phys.shapes.CollisionContext +1P
```
```
XXX.phys.shapes.DiscreteVoxelShape -3M | +1P -1P
```
```
XXX.phys.shapes.EntityCollisionContext$1 +1M -1M
```
```
XXX.phys.shapes.IndexMerger +1P
```
```
XXX.phys.shapes.IndirectMerger +2M | +5P -3P
```

</details>












































<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- Logger access$200()
- RenderSystem$AutoStorageIndexBuffer getSequentialBuffer(VertexFormat$Mode,int)
+ void drawArrays(int,int,int)
- void drawElements(int,int,int)
+ void lambda$activeTexture$22(int)
- void lambda$activeTexture$23(int)
+ void lambda$alphaFunc$0(int,float)
- void lambda$alphaFunc$1(int,float)
+ void lambda$bindTexture$25(int)
- void lambda$bindTexture$26(int)
+ void lambda$blendColor$11(float,float,float,float)
- void lambda$blendColor$12(float,float,float,float)
+ void lambda$blendEquation$10(int)
- void lambda$blendEquation$11(int)
+ void lambda$blendFunc$6(GlStateManager$SourceFactor,GlStateManager$DestFactor)
- void lambda$blendFunc$7(GlStateManager$SourceFactor,GlStateManager$DestFactor)
+ void lambda$blendFunc$7(int,int)
- void lambda$blendFunc$8(int,int)
- void lambda$blendFuncSeparate$10(int,int,int,int)
+ void lambda$blendFuncSeparate$8(GlStateManager$SourceFactor,GlStateManager$DestFactor,GlStateManager$SourceFactor,GlStateManager$DestFactor)
- void lambda$blendFuncSeparate$9(GlStateManager$SourceFactor,GlStateManager$DestFactor,GlStateManager$SourceFactor,GlStateManager$DestFactor)
+ void lambda$blendFuncSeparate$9(int,int,int,int)
+ void lambda$clear$35(int,boolean)
- void lambda$clear$36(int,boolean)
+ void lambda$clearColor$33(float,float,float,float)
- void lambda$clearColor$34(float,float,float,float)
+ void lambda$clearDepth$32(double)
- void lambda$clearDepth$33(double)
+ void lambda$clearStencil$34(int)
- void lambda$clearStencil$35(int)
+ void lambda$color3f$45(float,float,float)
- void lambda$color3f$46(float,float,float)
+ void lambda$color4f$44(float,float,float,float)
- void lambda$color4f$45(float,float,float,float)
+ void lambda$colorMask$28(boolean,boolean,boolean,boolean)
- void lambda$colorMask$29(boolean,boolean,boolean,boolean)
+ void lambda$colorMaterial$1(int,int)
- void lambda$colorMaterial$2(int,int)
+ void lambda$deleteTexture$24(int)
- void lambda$deleteTexture$25(int)
+ void lambda$depthFunc$4(int)
- void lambda$depthFunc$5(int)
+ void lambda$depthMask$5(boolean)
- void lambda$depthMask$6(boolean)
+ void lambda$drawArrays$46(int,int,int)
- void lambda$drawElements$47(int,int,int)
+ void lambda$enableScissor$3(int,int,int,int)
- void lambda$enableScissor$4(int,int,int,int)
+ void lambda$fog$17(int,float,float,float,float)
- void lambda$fog$18(int,float,float,float,float)
+ void lambda$fogDensity$14(float)
- void lambda$fogDensity$15(float)
+ void lambda$fogEnd$16(float)
- void lambda$fogEnd$17(float)
+ void lambda$fogi$18(int,int)
- void lambda$fogi$19(int,int)
+ void lambda$fogMode$12(GlStateManager$FogMode)
- void lambda$fogMode$13(GlStateManager$FogMode)
+ void lambda$fogMode$13(int)
- void lambda$fogMode$14(int)
+ void lambda$fogStart$15(float)
- void lambda$fogStart$16(float)
+ void lambda$getString$51(int,Consumer)
- void lambda$getString$52(int,Consumer)
+ void lambda$glBindBuffer$54(int,Supplier)
- void lambda$glBindBuffer$55(int,Supplier)
+ void lambda$glDeleteBuffers$55(int)
- void lambda$glDeleteBuffers$56(int)
+ void lambda$glGenBuffers$72(Consumer)
- void lambda$glGenBuffers$73(Consumer)
+ void lambda$glMultiTexCoord2f$53(int,float,float)
- void lambda$glMultiTexCoord2f$54(int,float,float)
+ void lambda$glUniform1$57(int,IntBuffer)
- void lambda$glUniform1$58(int,IntBuffer)
+ void lambda$glUniform1$61(int,FloatBuffer)
- void lambda$glUniform1$62(int,FloatBuffer)
+ void lambda$glUniform1i$56(int,int)
- void lambda$glUniform1i$57(int,int)
+ void lambda$glUniform2$58(int,IntBuffer)
- void lambda$glUniform2$59(int,IntBuffer)
+ void lambda$glUniform2$62(int,FloatBuffer)
- void lambda$glUniform2$63(int,FloatBuffer)
+ void lambda$glUniform3$59(int,IntBuffer)
- void lambda$glUniform3$60(int,IntBuffer)
+ void lambda$glUniform3$63(int,FloatBuffer)
- void lambda$glUniform3$64(int,FloatBuffer)
+ void lambda$glUniform4$60(int,IntBuffer)
- void lambda$glUniform4$61(int,IntBuffer)
+ void lambda$glUniform4$64(int,FloatBuffer)
- void lambda$glUniform4$65(int,FloatBuffer)
+ void lambda$glUniformMatrix2$65(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix2$66(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix3$66(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix3$67(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix4$67(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix4$68(int,boolean,FloatBuffer)
+ void lambda$lineWidth$47(float)
- void lambda$lineWidth$48(float)
+ void lambda$logicOp$21(GlStateManager$LogicOp)
- void lambda$logicOp$22(GlStateManager$LogicOp)
+ void lambda$matrixMode$36(int)
- void lambda$matrixMode$37(int)
+ void lambda$multMatrix$43(Matrix4f)
- void lambda$multMatrix$44(Matrix4f)
+ void lambda$normal3f$2(float,float,float)
- void lambda$normal3f$3(float,float,float)
+ void lambda$ortho$37(double,double,double,double,double,double)
- void lambda$ortho$38(double,double,double,double,double,double)
+ void lambda$pixelStore$48(int,int)
- void lambda$pixelStore$49(int,int)
+ void lambda$pixelTransfer$49(int,float)
- void lambda$pixelTransfer$50(int,float)
+ void lambda$polygonMode$19(int,int)
- void lambda$polygonMode$20(int,int)
+ void lambda$polygonOffset$20(float,float)
- void lambda$polygonOffset$21(float,float)
+ void lambda$readPixels$50(int,int,int,int,int,int,ByteBuffer)
- void lambda$readPixels$51(int,int,int,int,int,int,ByteBuffer)
+ void lambda$renderCrosshair$52(int)
- void lambda$renderCrosshair$53(int)
+ void lambda$rotatef$38(float,float,float,float)
- void lambda$rotatef$39(float,float,float,float)
+ void lambda$scaled$40(double,double,double)
- void lambda$scaled$41(double,double,double)
+ void lambda$scalef$39(float,float,float)
- void lambda$scalef$40(float,float,float)
+ void lambda$setupGui3DDiffuseLighting$71(Vector3f,Vector3f)
- void lambda$setupGui3DDiffuseLighting$72(Vector3f,Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$70(Vector3f,Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$71(Vector3f,Vector3f)
+ void lambda$setupLevelDiffuseLighting$69(Vector3f,Vector3f,Matrix4f)
- void lambda$setupLevelDiffuseLighting$70(Vector3f,Vector3f,Matrix4f)
+ void lambda$setupOverlayColor$68(IntSupplier,int)
- void lambda$setupOverlayColor$69(IntSupplier,int)
+ void lambda$shadeModel$26(int)
- void lambda$shadeModel$27(int)
- void lambda$static$0(IntConsumer,int)
+ void lambda$stencilFunc$29(int,int,int)
- void lambda$stencilFunc$30(int,int,int)
+ void lambda$stencilMask$30(int)
- void lambda$stencilMask$31(int)
+ void lambda$stencilOp$31(int,int,int)
- void lambda$stencilOp$32(int,int,int)
+ void lambda$texParameter$23(int,int,int)
- void lambda$texParameter$24(int,int,int)
+ void lambda$translated$42(double,double,double)
- void lambda$translated$43(double,double,double)
+ void lambda$translatef$41(float,float,float)
- void lambda$translatef$42(float,float,float)
+ void lambda$viewport$27(int,int,int,int)
- void lambda$viewport$28(int,int,int,int)
```

</details>



<details>
<summary>
com.mojang.math.Matrix4f
</summary>

```diff
- void multiplyWithTranslation(float,float,float)
```

</details>




<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ boolean access$7800(RealmsMainScreen)
+ boolean access$7802(RealmsMainScreen,boolean)
- boolean access$8000(RealmsMainScreen)
- boolean access$8002(RealmsMainScreen,boolean)
- Component access$7600()
- Component access$7700()
+ int access$8200(RealmsMainScreen)
+ int access$8300(RealmsMainScreen)
- int access$8400(RealmsMainScreen)
- int access$8500(RealmsMainScreen)
+ Minecraft access$8500(RealmsMainScreen)
- Minecraft access$8700(RealmsMainScreen)
+ ResourceLocation access$8400()
- ResourceLocation access$8600()
+ String access$8000(RealmsMainScreen)
- String access$8200(RealmsMainScreen)
+ void access$7600(RealmsMainScreen,PoseStack,int,int,int,int,boolean,boolean)
+ void access$7700(RealmsMainScreen,Button)
- void access$7800(RealmsMainScreen,PoseStack,int,int,int,int,boolean,boolean)
- void access$7900(RealmsMainScreen,Button)
+ void access$7900(RealmsMainScreen,PoseStack,int,int,boolean,int,int,boolean,boolean)
- void access$8100(RealmsMainScreen,PoseStack,int,int,boolean,int,int,boolean,boolean)
+ void access$8100(RealmsMainScreen,PoseStack,int,int,int,int,boolean)
- void access$8300(RealmsMainScreen,PoseStack,int,int,int,int,boolean)
+ void access$8600(RealmsMainScreen)
- void access$8800(RealmsMainScreen)
```

</details>





<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$ServerEntry
</summary>

```diff
+ RealmsServer access$8700(RealmsMainScreen$ServerEntry)
- RealmsServer access$8900(RealmsMainScreen$ServerEntry)
```

</details>





























<details>
<summary>
com.mojang.realmsclient.gui.RealmsDataFetcher
</summary>

```diff
+ boolean access$1002(RealmsDataFetcher,boolean)
+ boolean access$1202(RealmsDataFetcher,boolean)
+ boolean access$500(RealmsDataFetcher)
- Boolean lambda$markClean$0(RealmsDataFetcher$Task,Boolean)
+ int access$902(RealmsDataFetcher,int)
+ Logger access$800()
+ Map access$700(RealmsDataFetcher)
- RealmsPersistence$RealmsPersistenceData fetchAndUpdateNewsStorage()
+ RealmsServerPlayerLists access$1102(RealmsDataFetcher,RealmsServerPlayerLists)
+ String access$1302(RealmsDataFetcher,String)
+ void <init>()
- void <init>(Minecraft,RealmsClient)
+ void access$600(RealmsDataFetcher,List)
- void lambda$cancelTasks$1(ScheduledFuture)
- void updateLiveStats()
- void updatePendingInvites()
- void updateServersList()
- void updateTrialAvailable()
- void updateUnreadNews()
```

</details>


<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
</summary>

```diff
- void <clinit>()
```

</details>

















<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
- void access$600(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
+ void access$900(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
+ void callback(WorldTemplate)
- void generationSelectionCallback(WorldGenerationInfo)
- void lambda$generationSelectionCallback$8(WorldGenerationInfo)
+ void lambda$switchSlot$7()
- void lambda$templateSelectionCallback$7(WorldTemplate)
+ void resetWorld(RealmsResetWorldScreen$ResetWorldInfo)
- void resetWorld(Runnable)
+ void resetWorld(String,WorldTemplate,int,boolean)
+ void resetWorldWithTemplate(WorldTemplate)
- void startTask(LongRunningTask)
+ void switchSlot()
- void templateSelectionCallback(WorldTemplate)
+ void triggerResetWorld(RealmsResetWorldScreen$ResetWorldInfo)
```

</details>

<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- void <init>(Consumer,RealmsServer$WorldType,WorldTemplatePaginatedList)
- void <init>(Consumer,RealmsServer$WorldType)
+ void <init>(RealmsScreenWithCallback,RealmsServer$WorldType,WorldTemplatePaginatedList)
+ void <init>(RealmsScreenWithCallback,RealmsServer$WorldType)
+ void backButtonClicked()
- void onClose()
```

</details>








<details>
<summary>
com.mojang.realmsclient.util.task.GetServerDetailsTask
</summary>

```diff
- CompletableFuture scheduleResourcePackDownload(RealmsServerAddress)
- RealmsLongConfirmationScreen resourcePackDownloadConfirmationScreen(RealmsServerAddress,Function)
- RealmsLongRunningMcoTaskScreen connectScreen(RealmsServerAddress)
- RealmsServerAddress fetchServerAddress()
- void lambda$null$0(Function,RealmsServerAddress)
+ Void lambda$null$0(Throwable)
+ void lambda$null$1(RealmsServerAddress)
- Void lambda$null$1(Throwable)
- void lambda$resourcePackDownloadConfirmationScreen$2(RealmsServerAddress,Function,boolean)
+ void lambda$run$2(RealmsServerAddress,boolean)
+ void sleep(int)
```

</details>






<details>
<summary>
net.minecraft.CrashReportCategory
</summary>

```diff
+ String formatLocation(BlockPos)
+ String formatLocation(double,double,double)
+ String formatLocation(int,int,int)
- String formatLocation(LevelHeightAccessor,BlockPos)
- String formatLocation(LevelHeightAccessor,double,double,double)
- String formatLocation(LevelHeightAccessor,int,int,int)
+ String lambda$populateBlockDetails$0(BlockPos)
- String lambda$populateBlockDetails$0(LevelHeightAccessor,BlockPos)
+ void populateBlockDetails(CrashReportCategory,BlockPos,BlockState)
- void populateBlockDetails(CrashReportCategory,LevelHeightAccessor,BlockPos,BlockState)
```

</details>





<details>
<summary>
net.minecraft.Util
</summary>

```diff
- DataResult fixedSize(DoubleStream,int)
- Object getRandom(List,Random)
- void doPause()
- void logAndPauseIfInIde(String)
```

</details>















<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(Block,ItemStack,int)
- boolean matches(BlockState,ItemStack,int)
```

</details>





<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(BeaconBlockEntity)
- boolean matches(int)
```

</details>













<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
- JsonSyntaxException lambda$fromJson$1(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
</summary>

```diff
- IllegalStateException lambda$serializeToJson$0()
```

</details>







































































<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
- void fillGradient(PoseStack,int,int,int,int,int,int,int)
```

</details>








<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay
</summary>

```diff
+ boolean hasBoss()
```

</details>







<details>
<summary>
net.minecraft.client.gui.components.LerpingBossEvent
</summary>

```diff
+ float getPercent()
- float getProgress()
+ void setPercent(float)
- void setProgress(float)
```

</details>





<details>
<summary>
net.minecraft.client.gui.screens.inventory.LoomScreen
</summary>

```diff
- void init()
```

</details>































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ boolean access$700(CreateWorldScreen)
+ boolean lambda$copyTempDataPackDirToNewWorld$18(Path)
- boolean lambda$copyTempDataPackDirToNewWorld$20(Path)
+ boolean lambda$createTempDataPackDirFromExistingWorld$20(Path,Path)
- boolean lambda$createTempDataPackDirFromExistingWorld$22(Path,Path)
+ boolean lambda$tryApplyNewDataPacks$11(List,String)
- boolean lambda$tryApplyNewDataPacks$13(List,String)
+ Component access$100()
+ Component access$400(CreateWorldScreen)
+ Component access$500(CreateWorldScreen)
+ CreateWorldScreen$SelectedGameMode access$200(CreateWorldScreen)
+ Difficulty access$600(CreateWorldScreen)
- Difficulty getEffectiveDifficulty()
- MutableComponent lambda$init$1(CycleButton)
- MutableComponent lambda$init$4(CycleButton)
+ Object lambda$tryApplyNewDataPacks$16(DataPackConfig,ServerResources,Throwable)
- Object lambda$tryApplyNewDataPacks$18(DataPackConfig,ServerResources,Throwable)
+ void lambda$copyTempDataPackDirToNewWorld$19(Path,Path)
- void lambda$copyTempDataPackDirToNewWorld$21(Path,Path)
+ void lambda$createTempDataPackDirFromExistingWorld$21(MutableObject,Path,Path)
- void lambda$createTempDataPackDirFromExistingWorld$23(MutableObject,Path,Path)
+ void lambda$init$1(Button)
- void lambda$init$11(Button)
- void lambda$init$12(Button)
+ void lambda$init$2(Button)
- void lambda$init$2(CycleButton,CreateWorldScreen$SelectedGameMode)
+ void lambda$init$3(Button)
- void lambda$init$3(CycleButton,Difficulty)
+ void lambda$init$4(Button)
- void lambda$init$5(CycleButton,Boolean)
- void lambda$init$6(Button)
+ void lambda$init$7(Button)
+ void lambda$init$8(Button)
+ void lambda$null$13(boolean)
+ void lambda$null$14()
- void lambda$null$15(boolean)
+ void lambda$null$15(DataPackConfig,ServerResources)
- void lambda$null$16()
- void lambda$null$17(DataPackConfig,ServerResources)
+ void lambda$null$5(GameRules)
+ void lambda$null$6(Optional)
- void lambda$null$7(GameRules)
- void lambda$null$8(Optional)
+ void lambda$removeTempDataPackDir$17(Path)
- void lambda$removeTempDataPackDir$19(Path)
+ void lambda$tryApplyNewDataPacks$12()
- void lambda$tryApplyNewDataPacks$14()
- void refreshWorldGenSettingsVisibility()
+ void setDisplayOptions(boolean)
- void setWorldGenSettingsVisible(boolean)
+ void toggleDisplayOptions()
- void toggleWorldGenSettingsVisibility()
+ void updateDisplayOptions()
```

</details>


























<details>
<summary>
net.minecraft.client.model.ArmorStandModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.HoglinModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.SnowGolemModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.SquidModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart lambda$new$0(ModelPart,int)
- ModelPart root()
- String createTentacleName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.TridentModel
</summary>

```diff
- LayerDefinition createLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.TropicalFishModelB
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer(CubeDeformation)
- ModelPart root()
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.VillagerModel
</summary>

```diff
+ Iterable parts()
- MeshDefinition createBodyModel()
- ModelPart root()
+ void <init>(float,int,int)
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.WitherBossModel
</summary>

```diff
+ ImmutableList parts()
+ Iterable parts()
- LayerDefinition createBodyLayer(CubeDeformation)
- ModelPart root()
+ void <init>(float)
- void <init>(ModelPart)
- void setupHeadRotation(WitherBoss,ModelPart,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.ZombieModel
</summary>

```diff
+ void <init>(float,boolean)
+ void <init>(float,float,int,int)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.dragon.DragonHeadModel
</summary>

```diff
- LayerDefinition createHeadLayer()
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart
</summary>

```diff
- boolean isEmpty()
+ ModelPart addBox(float,float,float,float,float,float,boolean)
+ ModelPart addBox(float,float,float,float,float,float)
+ ModelPart addBox(String,float,float,float,int,int,int,float,int,int)
+ ModelPart createShallowCopy()
- ModelPart getChild(String)
+ ModelPart setTexSize(int,int)
+ ModelPart texOffs(int,int)
- PartPose storePose()
- Stream getAllParts()
+ void <init>()
+ void <init>(int,int,int,int)
- void <init>(List,Map)
+ void <init>(Model,int,int)
+ void <init>(Model)
+ void addBox(float,float,float,float,float,float,float,boolean)
+ void addBox(float,float,float,float,float,float,float,float,float)
+ void addBox(float,float,float,float,float,float,float)
+ void addBox(int,int,float,float,float,float,float,float,float,float,float,boolean,boolean)
+ void addChild(ModelPart)
- void lambda$visit$0(PoseStack,ModelPart$Visitor,String,String,ModelPart)
- void loadPose(PartPose)
- void setRotation(float,float,float)
- void visit(PoseStack,ModelPart$Visitor,String)
- void visit(PoseStack,ModelPart$Visitor)
```

</details>


<details>
<summary>
net.minecraft.client.multiplayer.ClientAdvancements
</summary>

```diff
+ Map getProgress()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
+ boolean isEntityTickingChunk(Entity)
- LevelChunk replaceWithPacketData(int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,BitSet)
+ LevelChunk replaceWithPacketData(int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int,boolean)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- EntityTickList access$100(ClientLevel)
+ int lambda$getBlockTint$7(BlockPos,ColorResolver)
- int lambda$getBlockTint$9(BlockPos,ColorResolver)
- LevelEntityGetter getEntities()
- List access$200(ClientLevel)
- String gatherChunkSourceStats()
+ String lambda$fillReportDetails$5()
- String lambda$fillReportDetails$7()
+ String lambda$tickNonPassenger$1(Entity)
- String lambda$tickNonPassenger$2(Entity)
+ Vec3 getSkyColor(BlockPos,float)
- Vec3 getSkyColor(Vec3,float)
- Vec3 lambda$getSkyColor$8(BiomeManager,int,int,int)
- void addDestroyBlockEffect(BlockPos,BlockState)
- void gameEvent(Entity,GameEvent,BlockPos)
+ void lambda$clearTintCaches$3(ColorResolver,BlockTintCache)
- void lambda$clearTintCaches$4(ColorResolver,BlockTintCache)
+ void lambda$doAnimateTick$4(BlockPos$MutableBlockPos,AmbientParticleSettings)
- void lambda$doAnimateTick$5(BlockPos$MutableBlockPos,AmbientParticleSettings)
+ void lambda$onChunkLoaded$2(int,int,ColorResolver,BlockTintCache)
- void lambda$onChunkLoaded$3(ChunkPos,ColorResolver,BlockTintCache)
- void lambda$tickEntities$1(Entity)
- void onChunkLoaded(ChunkPos)
+ void onChunkLoaded(int,int)
+ void onEntityRemoved(Entity)
+ void reAddEntitiesToChunk(LevelChunk)
+ void removeAllPendingEntityRemovals()
- void removeEntity(int,Entity$RemovalReason)
+ void removeEntity(int)
+ void setMapData(MapItemSavedData)
- void setMapData(String,MapItemSavedData)
+ void updateChunkPos(Entity)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
</summary>

```diff
- void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
+ void fillCrashReportCategory(CrashReportCategory)
```

</details>





















































<details>
<summary>
net.minecraft.client.particle.SquidInkParticle
</summary>

```diff
- void <init>(ClientLevel,double,double,double,double,double,double,int,SpriteSet,SquidInkParticle$1)
- void <init>(ClientLevel,double,double,double,double,double,double,int,SpriteSet)
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet,SquidInkParticle$1)
+ void <init>(ClientLevel,double,double,double,double,double,double,SpriteSet)
```

</details>





<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
+ ResourceLocation getSkullPath(String)
```

</details>











<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
- float getDepthFar()
+ Matrix4f getProjectionMatrix(Camera,float,boolean)
- Matrix4f getProjectionMatrix(double)
```

</details>




<details>
<summary>
net.minecraft.client.renderer.blockentity.ChestRenderer
</summary>

```diff
- LayerDefinition createDoubleBodyLeftLayer()
- LayerDefinition createDoubleBodyRightLayer()
- LayerDefinition createSingleBodyLayer()
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.EnchantTableRenderer
</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.PistonHeadRenderer
</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
+ FormattedCharSequence lambda$render$0(Font,Component)
- FormattedCharSequence lambda$render$2(Component)
- LayerDefinition createSignLayer()
+ Material getMaterial(Block)
- SignRenderer$SignModel createSignModel(EntityModelSet,WoodType)
- SignRenderer$SignModel lambda$new$1(BlockEntityRendererProvider$Context,WoodType)
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
- WoodType getWoodType(Block)
- WoodType lambda$new$0(WoodType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SkullBlockRenderer
</summary>

```diff
- Map createSkullRenderers(EntityModelSet)
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
+ void lambda$static$1(HashMap)
- void renderSkull(Direction,float,float,PoseStack,MultiBufferSource,int,SkullModelBase,RenderType)
+ void renderSkull(Direction,float,SkullBlock$Type,GameProfile,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.StructureBlockRenderer
</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
+ void <init>(BlockEntityRenderDispatcher)
- void <init>(BlockEntityRendererProvider$Context)
```

</details>





<details>
<summary>
net.minecraft.client.renderer.chunk.VisGraph
</summary>

```diff
+ Set floodFill(BlockPos)
```

</details>









<details>
<summary>
net.minecraft.client.renderer.entity.BeeRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BoatRenderer
</summary>

```diff
- Boat$Type lambda$new$0(Boat$Type)
- Pair lambda$new$1(EntityRendererProvider$Context,Boat$Type)
+ void <clinit>()
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CaveSpiderRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ChickenRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CowRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DolphinRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DrownedRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndCrystalRenderer
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
</summary>

```diff
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndermiteRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderer
</summary>

```diff
+ EntityRenderDispatcher getDispatcher()
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.HoglinRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.HumanoidMobRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher,HumanoidModel,float,float,float,float)
+ void <init>(EntityRenderDispatcher,HumanoidModel,float)
- void <init>(EntityRendererProvider$Context,HumanoidModel,float,float,float,float)
- void <init>(EntityRendererProvider$Context,HumanoidModel,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.IllagerRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher,IllagerModel,float)
- void <init>(EntityRendererProvider$Context,IllagerModel,float)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.ItemEntityRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher,ItemRenderer)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ItemRenderer
</summary>

```diff
- BakedModel getModel(ItemStack,Level,LivingEntity,int)
+ BakedModel getModel(ItemStack,Level,LivingEntity)
- void <init>(TextureManager,ModelManager,ItemColors,BlockEntityWithoutLevelRenderer)
+ void <init>(TextureManager,ModelManager,ItemColors)
- void renderAndDecorateItem(ItemStack,int,int,int)
- void renderAndDecorateItem(LivingEntity,ItemStack,int,int,int)
+ void renderAndDecorateItem(LivingEntity,ItemStack,int,int)
- void renderStatic(ItemStack,ItemTransforms$TransformType,int,int,PoseStack,MultiBufferSource,int)
+ void renderStatic(ItemStack,ItemTransforms$TransformType,int,int,PoseStack,MultiBufferSource)
- void renderStatic(LivingEntity,ItemStack,ItemTransforms$TransformType,boolean,PoseStack,MultiBufferSource,Level,int,int,int)
+ void renderStatic(LivingEntity,ItemStack,ItemTransforms$TransformType,boolean,PoseStack,MultiBufferSource,Level,int,int)
- void tryRenderGuiItem(LivingEntity,ItemStack,int,int,int)
+ void tryRenderGuiItem(LivingEntity,ItemStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LightningBoltRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.LlamaSpitRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.MinecartRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context,ModelLayerLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.MushroomCowRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PaintingRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ParrotRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PigRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PillagerRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PufferfishRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.RavagerRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SalmonRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ShulkerBulletRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SilverfishRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SlimeRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SpectralArrowRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SquidRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context,SquidModel)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.StriderRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ThrownTridentRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TntMinecartRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TropicalFishRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.UndeadHorseRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context,ModelLayerLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.VillagerRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher,ReloadableResourceManager)
- void <init>(EntityRendererProvider$Context)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.WitchRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WitherSkeletonRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WolfRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ZombieRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context,ModelLayerLocation,ModelLayerLocation,ModelLayerLocation)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.ArrowLayer
</summary>

```diff
- void <init>(EntityRendererProvider$Context,LivingEntityRenderer)
+ void <init>(LivingEntityRenderer)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.entity.layers.CatCollarLayer
</summary>

```diff
- void <init>(RenderLayerParent,EntityModelSet)
+ void <init>(RenderLayerParent)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
</summary>

```diff
- void <init>(RenderLayerParent,EntityModelSet)
+ void <init>(RenderLayerParent)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.entity.layers.HorseArmorLayer
</summary>

```diff
- void <init>(RenderLayerParent,EntityModelSet)
+ void <init>(RenderLayerParent)
```

</details>




<details>
<summary>
net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
</summary>

```diff
- void <init>(RenderLayerParent,EntityModelSet)
+ void <init>(RenderLayerParent)
```

</details>
















<details>
<summary>
net.minecraft.client.resources.sounds.AbstractSoundInstance
</summary>

```diff
+ boolean hasPriority()
```

</details>



















<details>
<summary>
net.minecraft.client.server.LanServer
</summary>

```diff
+ boolean isUpToDate()
```

</details>




















<details>
<summary>
net.minecraft.commands.CommandFunction$CommandEntry
</summary>

```diff
+ void execute(ServerFunctionManager,CommandSourceStack,ArrayDeque,int)
- void execute(ServerFunctionManager,CommandSourceStack,Deque,int)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandFunction$FunctionEntry
</summary>

```diff
+ void execute(ServerFunctionManager,CommandSourceStack,ArrayDeque,int)
- void execute(ServerFunctionManager,CommandSourceStack,Deque,int)
+ void lambda$execute$0(int,ArrayDeque,ServerFunctionManager,CommandSourceStack,CommandFunction)
- void lambda$execute$0(int,Deque,ServerFunctionManager,CommandSourceStack,CommandFunction)
```

</details>































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- BlockPos atY(int)
+ boolean isOutsideBuildHeight(long)
```

</details>


<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
- BlockPos$MutableBlockPos setX(int)
- BlockPos$MutableBlockPos setY(int)
- BlockPos$MutableBlockPos setZ(int)
- Vec3i setX(int)
- Vec3i setY(int)
- Vec3i setZ(int)
+ void setX(int)
+ void setY(int)
+ void setZ(int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockSourceImpl
</summary>

```diff
+ Material getMaterial()
```

</details>











































<details>
<summary>
net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
</summary>

```diff
- BlockModelGenerators$BlockFamilyProvider access$2300(BlockModelGenerators$BlockFamilyProvider,Block)
- BlockModelGenerators$BlockFamilyProvider door(Block)
+ BlockModelGenerators$BlockFamilyProvider fullBlock(Function)
- BlockModelGenerators$BlockFamilyProvider fullBlockCopies(Block[])
- BlockModelGenerators$BlockFamilyProvider generateFor(BlockFamily)
+ BlockModelGenerators$BlockFamilyProvider sign(Block,Block)
- BlockModelGenerators$BlockFamilyProvider sign(Block)
- ResourceLocation getOrCreateModel(ModelTemplate,Block)
- ResourceLocation lambda$getOrCreateModel$0(Block,ModelTemplate)
- void access$2200(BlockModelGenerators$BlockFamilyProvider,Block)
- void lambda$generateFor$1(BlockFamily$Variant,Block)
- void trapdoor(Block)
```

</details>


























<details>
<summary>
net.minecraft.gametest.framework.GameTestSequence
</summary>

```diff
- GameTestSequence thenExecuteFor(int,Runnable)
+ GameTestSequence thenWait(long,Runnable)
+ GameTestSequence thenWait(Runnable)
- GameTestSequence thenWaitUntil(long,Runnable)
- GameTestSequence thenWaitUntil(Runnable)
- void lambda$thenExecuteFor$3(int,Runnable)
+ void lambda$thenFail$3(Supplier)
- void lambda$thenFail$4(Supplier)
+ void lambda$thenTrigger$4(GameTestSequence$Condition)
- void lambda$thenTrigger$5(GameTestSequence$Condition)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ boolean publishServer(GameType,boolean,int)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,ServerResources,Collection,BlockPos,RegistryAccess$RegistryHolder,Registry,Registry)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,ServerResources,Collection,BlockPos,RegistryAccess$RegistryHolder,Registry,WritableRegistry)
```

</details>

<details>
<summary>
net.minecraft.gametest.framework.StructureUtils
</summary>

```diff
+ boolean lambda$clearSpaceForStructure$1(Entity)
- boolean lambda$clearSpaceForStructure$3(Entity)
+ boolean lambda$findStructureBlockContainingPos$2(BlockPos,ServerLevel,BlockPos)
- boolean lambda$findStructureBlockContainingPos$4(BlockPos,ServerLevel,BlockPos)
- boolean lambda$main$0(Path)
+ int lambda$findNearestStructureBlock$3(BlockPos,BlockPos)
- int lambda$findNearestStructureBlock$5(BlockPos,BlockPos)
+ void lambda$clearSpaceForStructure$0(int,ServerLevel,BlockPos)
- void lambda$clearSpaceForStructure$2(int,ServerLevel,BlockPos)
- void lambda$main$1(Path)
- void main(String[])
```

</details>


<details>
<summary>
net.minecraft.gametest.framework.TestFunction
</summary>

```diff
- boolean isFlaky()
- int getMaxAttempts()
- int getRequiredSuccesses()
- void <init>(String,String,String,Rotation,int,long,boolean,int,int,Consumer)
```

</details>












<details>
<summary>
net.minecraft.nbt.ListTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
+ void stripEmptyChildren()
```

</details>
<details>
<summary>
net.minecraft.nbt.LongArrayTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
+ String toString()
- void accept(TagVisitor)
```

</details>




<details>
<summary>
net.minecraft.nbt.NumericTag
</summary>

```diff
- String toString()
```

</details>

<details>
<summary>
net.minecraft.nbt.Tag
</summary>

```diff
+ boolean isEmpty()
+ Component getPrettyDisplay()
+ void <clinit>()
+ void stripEmptyChildren()
```

</details>
























































<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand$Position
</summary>

```diff
+ double access$000(SpreadPlayersCommand$Position)
+ double access$002(SpreadPlayersCommand$Position,double)
- double access$200(SpreadPlayersCommand$Position)
- double access$202(SpreadPlayersCommand$Position,double)
+ void <init>(double,double)
- void <init>(SpreadPlayersCommand$1)
+ void set(double,double)
```

</details>














<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- boolean isResourcePackRequired()
+ boolean publishServer(GameType,boolean,int)
- GameType getForcedGameType()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
+ Integer lambda$new$2(Integer)
```

</details>










<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
+ ChunkAccess lambda$null$25(ChunkHolder,ChunkAccess)
- ChunkAccess lambda$null$26(ChunkHolder,ChunkAccess)
+ ChunkHolder$FullChunkStatus lambda$null$24(ChunkHolder)
- ChunkHolder$FullChunkStatus lambda$null$25(ChunkHolder)
+ ChunkMap$DistanceManager getDistanceManager()
+ ChunkStatus lambda$getEntityTickingRangeFuture$2(int)
+ ChunkStatus lambda$postProcess$28(int)
- ChunkStatus lambda$prepareEntityTickingChunk$2(int)
- ChunkStatus lambda$prepareTickingChunk$29(int)
+ CompletableFuture getEntityTickingRangeFuture(ChunkPos)
+ CompletableFuture postProcess(ChunkHolder)
- CompletableFuture prepareAccessibleChunk(ChunkHolder)
- CompletableFuture prepareEntityTickingChunk(ChunkPos)
- CompletableFuture prepareTickingChunk(ChunkHolder)
+ CompletableFuture unpackTicks(ChunkHolder)
- DistanceManager getDistanceManager()
+ Either lambda$getEntityTickingRangeFuture$4(Either)
+ Either lambda$null$29(List)
- Either lambda$null$30(List)
+ Either lambda$null$33(ChunkPos,LevelChunk)
+ Either lambda$postProcess$30(Either)
- Either lambda$prepareAccessibleChunk$38(Either)
- Either lambda$prepareEntityTickingChunk$4(Either)
- Either lambda$prepareTickingChunk$31(Either)
+ Either lambda$protoChunkToFullChunk$26(ChunkHolder,Either)
- Either lambda$protoChunkToFullChunk$27(ChunkHolder,Either)
+ Either lambda$unpackTicks$37(Either)
+ int access$700(ChunkPos,ServerPlayer,boolean)
+ Integer lambda$dumpChunks$41(LevelChunk)
+ LevelChunk lambda$null$36(ChunkAccess)
- LevelChunk lambda$null$37(List)
+ Optional lambda$dumpChunks$40(ChunkAccess)
- Optional lambda$dumpChunks$41(ChunkAccess)
- void <init>(ServerLevel,LevelStorageSource$LevelStorageAccess,DataFixer,StructureManager,Executor,BlockableEventLoop,LightChunkGetter,ChunkGenerator,ChunkProgressListener,ChunkStatusUpdateListener,Supplier,int,boolean)
+ void <init>(ServerLevel,LevelStorageSource$LevelStorageAccess,DataFixer,StructureManager,Executor,BlockableEventLoop,LightChunkGetter,ChunkGenerator,ChunkProgressListener,Supplier,int,boolean)
- void lambda$null$24(ProtoChunk,LevelChunk)
+ void lambda$null$32(Packet[],LevelChunk,ServerPlayer)
- void lambda$null$33(Packet[],LevelChunk,ServerPlayer)
- void lambda$null$34(ChunkPos,LevelChunk)
+ void lambda$postProcess$31(ChunkHolder,Runnable)
+ void lambda$postProcess$34(ChunkPos,Either)
+ void lambda$postProcess$35(ChunkHolder,Runnable)
- void lambda$prepareAccessibleChunk$39(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$32(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$35(ChunkPos,Either)
- void lambda$prepareTickingChunk$36(ChunkHolder,Runnable)
+ void lambda$protoChunkToFullChunk$27(ChunkHolder,Runnable)
- void lambda$protoChunkToFullChunk$28(ChunkHolder,Runnable)
+ void lambda$setViewDistance$39(ChunkPos,int,Packet[],ServerPlayer)
- void lambda$setViewDistance$40(ChunkPos,int,Packet[],ServerPlayer)
+ void lambda$unpackTicks$38(ChunkHolder,Runnable)
- void onFullChunkStatusChange(ChunkPos,ChunkHolder$FullChunkStatus)
- void postLoadProtoChunk(ServerLevel,List)
```

</details>





<details>
<summary>
net.minecraft.server.level.DemoMode
</summary>

```diff
+ void <init>(ServerLevel)
- void <init>(ServerPlayer)
```

</details>















<details>
<summary>
net.minecraft.server.packs.repository.PackCompatibility
</summary>

```diff
- PackCompatibility forFormat(int,PackType)
+ PackCompatibility forFormat(int)
- PackCompatibility forMetadata(PackMetadataSection,PackType)
```

</details>

<details>
<summary>
net.minecraft.server.packs.repository.ServerPacksSource
</summary>

```diff
- void <clinit>()
```

</details>









<details>
<summary>
net.minecraft.server.packs.resources.SimpleReloadableResourceManager
</summary>

```diff
+ Object lambda$createFullReload$0(List)
- Object lambda$createReload$0(List)
+ ReloadInstance createFullReload(Executor,Executor,CompletableFuture,List)
+ ReloadInstance createQueuedReload(Executor,Executor,CompletableFuture)
- ReloadInstance createReload(Executor,Executor,CompletableFuture,List)
+ ReloadInstance createReload(Executor,Executor,List,CompletableFuture)
```

</details>








<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ void blackList(GameProfile)
- void lambda$remove$1(Entity)
+ void setOverrideGameMode(GameType)
+ void updatePlayerGameMode(ServerPlayer,ServerPlayer,ServerLevel)
+ void whiteList(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.players.ServerOpList
</summary>

```diff
+ GameProfile find(String)
+ int getOpLevel(GameProfile)
- String[] lambda$getUserList$0(int)
```

</details>

<details>
<summary>
net.minecraft.server.players.UserBanList
</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserWhiteList
</summary>

```diff
+ GameProfile find(String)
- String[] lambda$getUserList$0(int)
```

</details>












<details>
<summary>
net.minecraft.stats.StatType
</summary>

```diff
+ int size()
```

</details>

<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
+ List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
- List getStaticTags()
+ List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.TagContainer
</summary>

```diff
- Logger access$000()
- Map serializeToNetwork(RegistryAccess)
- ResourceLocation getIdOrThrow(ResourceKey,Tag,Supplier)
- Tag getTagOrThrow(ResourceKey,ResourceLocation,Function)
- TagCollection get(ResourceKey)
- TagCollection getOrEmpty(ResourceKey)
+ TagContainer deserializeFromNetwork(FriendlyByteBuf)
- TagContainer deserializeFromNetwork(RegistryAccess,Map)
+ TagContainer of(TagCollection,TagCollection,TagCollection,TagCollection)
- void <init>(Map,TagContainer$1)
- void <init>(Map)
- void acceptCap(TagContainer$CollectionConsumer,ResourceKey,TagCollection)
- void addTagsFromPayload(RegistryAccess,TagContainer$Builder,ResourceKey,TagCollection$NetworkPayload)
- void getAll(TagContainer$CollectionConsumer)
- void lambda$deserializeFromNetwork$1(RegistryAccess,TagContainer$Builder,ResourceKey,TagCollection$NetworkPayload)
- void lambda$getAll$0(TagContainer$CollectionConsumer,ResourceKey,TagCollection)
+ void serializeToNetwork(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.tags.TagLoader
</summary>

```diff
- boolean isCyclic(Multimap,ResourceLocation,ResourceLocation)
- boolean lambda$isCyclic$3(Multimap,ResourceLocation,ResourceLocation)
- boolean lambda$load$0(String)
+ boolean lambda$null$0(String)
+ CompletableFuture prepare(ResourceManager,Executor)
+ Map lambda$prepare$2(ResourceManager)
- Map load(ResourceManager)
- Object lambda$build$4(ResourceLocation)
+ Object lambda$load$3(ResourceLocation)
- Tag$Builder lambda$load$1(ResourceLocation)
+ Tag$Builder lambda$null$1(ResourceLocation)
- TagCollection build(Map)
+ TagCollection load(Map)
- TagCollection loadAndBuild(ResourceManager)
+ void <init>(Function,String,String)
- void <init>(Function,String)
- void addDependencyIfNotCyclic(Multimap,ResourceLocation,ResourceLocation)
- void lambda$build$12(Map,Multimap,Set,Function,Function,Map,ResourceLocation)
- void lambda$build$6(Multimap,ResourceLocation,Tag$Builder)
- void lambda$build$8(Multimap,ResourceLocation,Tag$Builder)
+ void lambda$load$4(Function,Function,ResourceLocation,Tag$Builder)
- void lambda$null$10(Map,ResourceLocation,Tag)
- void lambda$null$11(Function,Function,Map,ResourceLocation,Tag$Builder)
- void lambda$null$5(Multimap,ResourceLocation,ResourceLocation)
- void lambda$null$7(Multimap,ResourceLocation,ResourceLocation)
- void lambda$null$9(ResourceLocation,Collection)
- void lambda$visitDependenciesAndElement$2(Map,Multimap,Set,BiConsumer,ResourceLocation)
- void visitDependenciesAndElement(Map,Multimap,Set,ResourceLocation,BiConsumer)
```

</details>














































































































<details>
<summary>
net.minecraft.world.damagesource.DamageSource
</summary>

```diff
- boolean isDamageHelmet()
- boolean isFall()
- DamageSource damageHelmet()
- DamageSource setIsFall()
```

</details>




<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
+ void setSplash(boolean)
```

</details>


<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- AABB makeBoundingBox()
- boolean canFreeze()
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
+ boolean checkAndResetForcedChunkAdditionFlag()
+ boolean checkAndResetUpdateChunkPos()
- boolean hasExactlyOnePlayerPassenger()
+ boolean hasOnePlayerPassenger()
+ boolean hasPassenger(Class)
- boolean hasPassenger(Predicate)
- boolean isAlwaysTicking()
- boolean isFullyFrozen()
- boolean isRemoved()
- boolean lambda$hasExactlyOnePlayerPassenger$14(Entity)
- boolean lambda$hasIndirectPassenger$15(Entity,Entity)
+ boolean lambda$null$3(BlockState,BlockPos)
- boolean lambda$null$4(BlockState,BlockPos)
- boolean lambda$refreshDimensions$12(BlockState,BlockPos)
- boolean lambda$removePassenger$3(Entity,Entity)
- boolean occludesVibrations()
+ boolean setSlot(int,ItemStack)
- boolean shouldBeSaved()
- ChunkPos chunkPosition()
+ Collection getIndirectPassengers()
- Entity getFirstPassenger()
- Entity$RemovalReason getRemovalReason()
- float getPercentFrozen()
- GameEventListenerRegistrar getGameEventListenerRegistrar()
- int getBlockX()
- int getBlockY()
- int getBlockZ()
- int getTicksFrozen()
- int getTicksRequiredToFreeze()
- ItemStack getPickResult()
- Iterable getIndirectPassengers()
- Iterator lambda$getIndirectPassengers$13()
+ PortalInfo lambda$findDimensionEntryPoint$4(ServerLevel,BlockUtil$FoundRectangle)
- PortalInfo lambda$findDimensionEntryPoint$5(ServerLevel,BlockUtil$FoundRectangle)
- SlotAccess getSlot(int)
- Stream getIndirectPassengersStream()
- Stream getPassengersAndSelf()
+ String lambda$fillCrashReportCategory$5()
- String lambda$fillCrashReportCategory$9()
- Style lambda$getDisplayName$10(Style)
+ Style lambda$getDisplayName$9(Style)
+ void burn(int)
- void checkOutOfWorld()
- void discard()
+ void fillIndirectPassengers(boolean,Set)
- void gameEvent(Entity,GameEvent)
- void gameEvent(GameEvent)
+ void lambda$teleportTo$10(ServerLevel,Entity)
- void lambda$teleportTo$11(Entity)
- void recreateFromPacket(ClientboundAddEntityPacket)
+ void remove()
- void remove(Entity$RemovalReason)
- void setBodyIsInPowderSnow(boolean)
+ void setDropContainerContent(boolean)
+ void setLevel(Level)
- void setLevelCallback(EntityInLevelCallback)
+ void setLocationFromBoundingbox()
- void setOldPosAndRot()
+ void setPosAndOldPos(double,double,double)
- void setRemoved(Entity$RemovalReason)
- void setTicksFrozen(int)
- void unsetRemoved()
```

</details>


<details>
<summary>
net.minecraft.world.entity.EquipmentSlot
</summary>

```diff
- int getIndex(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
- boolean canMerge(ExperienceOrb,int,int)
- boolean canMerge(ExperienceOrb)
- boolean lambda$tryMergeToExisting$0(int,int,ExperienceOrb)
- boolean tryMergeToExisting(ServerLevel,Vec3,int)
- SoundSource getSoundSource()
- void award(ServerLevel,Vec3,int)
+ void burn(int)
- void merge(ExperienceOrb)
- void scanForEntities()
```

</details>









<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
</summary>

```diff
- Float lambda$new$0(float,LivingEntity)
- void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
</summary>

```diff
- Float lambda$new$0(float,LivingEntity)
- void <init>(Function,int)
```

</details>









<details>
<summary>
net.minecraft.world.entity.ai.goal.AvoidEntityGoal
</summary>

```diff
- boolean lambda$canUse$2(LivingEntity)
```

</details>




























<details>
<summary>
net.minecraft.world.entity.ai.goal.TemptGoal
</summary>

```diff
- boolean shouldFollow(LivingEntity)
+ boolean shouldFollowItem(ItemStack)
+ void <init>(PathfinderMob,double,boolean,Ingredient)
```

</details>


















<details>
<summary>
net.minecraft.world.entity.ai.sensing.AdultSensor
</summary>

```diff
+ AgableMob lambda$setNearestVisibleAdult$2(LivingEntity)
- AgeableMob lambda$setNearestVisibleAdult$2(LivingEntity)
+ boolean lambda$setNearestVisibleAdult$1(AgableMob,LivingEntity)
- boolean lambda$setNearestVisibleAdult$1(AgeableMob,LivingEntity)
+ boolean lambda$setNearestVisibleAdult$3(AgableMob)
- boolean lambda$setNearestVisibleAdult$3(AgeableMob)
+ void doTick(ServerLevel,AgableMob)
- void doTick(ServerLevel,AgeableMob)
+ void lambda$doTick$0(AgableMob,List)
- void lambda$doTick$0(AgeableMob,List)
+ void setNearestVisibleAdult(AgableMob,List)
- void setNearestVisibleAdult(AgeableMob,List)
```

</details>





<details>
<summary>
net.minecraft.world.entity.ai.sensing.SensorType
</summary>

```diff
- TemptingSensor lambda$static$0()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.util.GoalUtils
</summary>

```diff
- boolean hasMalus(PathfinderMob,BlockPos)
- boolean isNotStable(PathNavigation,BlockPos)
- boolean isOutsideLimits(BlockPos,PathfinderMob)
- boolean isRestricted(boolean,PathfinderMob,BlockPos)
- boolean isSolid(PathfinderMob,BlockPos)
- boolean isWater(PathfinderMob,BlockPos)
- boolean mobRestricted(PathfinderMob,int)
```

</details>



<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiManager
</summary>

```diff
- void <init>(File,DataFixer,boolean,LevelHeightAccessor)
+ void <init>(File,DataFixer,boolean)
```

</details>



<details>
<summary>
net.minecraft.world.entity.ambient.Bat
</summary>

```diff
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.AbstractFish
</summary>

```diff
- ItemStack lambda$mobInteract$0()
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.Animal
</summary>

```diff
- void usePlayerItem(Player,InteractionHand,ItemStack)
+ void usePlayerItem(Player,ItemStack)
```

</details>
























<details>
<summary>
net.minecraft.world.entity.animal.Panda
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.PolarBear
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Sheep
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Sheep getBreedOffspring(ServerLevel,AgableMob)
- Sheep getBreedOffspring(ServerLevel,AgeableMob)
```

</details>











<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EndCrystal
</summary>

```diff
- ItemStack getPickResult()
```

</details>











<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
+ boolean setSlot(int,ItemStack)
- ItemStack getPickResult()
```

</details>

<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
- boolean isGlowFrame()
+ boolean setSlot(int,ItemStack)
- ItemStack getFrameItemStack()
- ItemStack getPickResult()
- SlotAccess getSlot(int)
- void <init>(EntityType,Level,BlockPos,Direction)
- void recreateFromPacket(ClientboundAddEntityPacket)
```

</details>





<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner
</summary>

```diff
- Runnable createTicker(Level)
- void lambda$createTicker$0(Level)
- void lambda$createTicker$1(Level)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- boolean causeFallDamage(float,float,DamageSource)
+ boolean causeFallDamage(float,float)
```

</details>




<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu
</summary>

```diff
- boolean shouldMoveToInventory(int)
+ void handlePlacement(boolean,Recipe,ServerPlayer)
```

</details>








<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
- SoundEvent getEquipSound()
```

</details>




<details>
<summary>
net.minecraft.world.item.BlockItem
</summary>

```diff
- boolean canFitInsideContainerItems()
- void onDestroyed(ItemEntity)
```

</details>



<details>
<summary>
net.minecraft.world.item.DyeColor
</summary>

```diff
+ int getTextureDiffuseColorBGR()
```

</details>


<details>
<summary>
net.minecraft.world.item.ElytraItem
</summary>

```diff
- SoundEvent getEquipSound()
```

</details>














<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
- int getHeight()
- int getMinBuildHeight()
```

</details>



<details>
<summary>
net.minecraft.world.level.ForcedChunksSavedData
</summary>

```diff
- ForcedChunksSavedData load(CompoundTag)
- void <init>(LongSet)
+ void load(CompoundTag)
```

</details>






<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ BlockEntity getPendingBlockEntityAt(BlockPos)
+ BlockState getTopBlockState(BlockPos)
+ boolean addBlockEntity(BlockEntity)
+ boolean isOutsideBuildHeight(BlockPos)
+ boolean isOutsideBuildHeight(int)
+ List getEntities(EntityType,AABB,Predicate)
- List getEntities(EntityTypeTest,AABB,Predicate)
+ List getEntitiesOfClass(Class,AABB,Predicate)
+ List getLoadedEntitiesOfClass(Class,AABB,Predicate)
+ Object lambda$addBlockEntity$1(BlockEntity)
+ String gatherChunkSourceStats()
+ String lambda$tickBlockEntities$2(BlockEntity)
+ void addAllPendingBlockEntities(Collection)
- void addBlockEntityTicker(TickingBlockEntity)
- void addDestroyBlockEffect(BlockPos,BlockState)
+ void blockEntityChanged(BlockPos,BlockEntity)
- void blockEntityChanged(BlockPos)
- void lambda$getEntities$1(Entity,Predicate,List,Entity)
- void lambda$getEntities$2(Predicate,List,EntityTypeTest,Entity)
- void postGameEventInRadius(Entity,GameEvent,BlockPos,int)
- void setBlockEntity(BlockEntity)
+ void setBlockEntity(BlockPos,BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
+ int getHeight()
- int getLogicalHeight()
- void gameEvent(Entity,GameEvent,Entity)
- void gameEvent(GameEvent,BlockPos)
- void gameEvent(GameEvent,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
- DamageSource getFallDamageSource()
+ void onBroken(Level,BlockPos,FallingBlockEntity)
- void onBrokenAfterFall(Level,BlockPos,FallingBlockEntity)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
- BlockState updateShape(BlockState,Direction,BlockState,LevelAccessor,BlockPos,BlockPos)
- FluidState getFluidState(BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BlastFurnaceBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.BubbleColumnBlock
</summary>

```diff
+ Fluid takeLiquid(LevelAccessor,BlockPos,BlockState)
- ItemStack pickupBlock(LevelAccessor,BlockPos,BlockState)
- Optional getPickupSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
- void setOpen(Entity,Level,BlockState,BlockPos,boolean)
+ void setOpen(Level,BlockState,BlockPos,boolean)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.DropperBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndGatewayBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.FurnaceBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LiquidBlock
</summary>

```diff
+ Fluid takeLiquid(LevelAccessor,BlockPos,BlockState)
- ItemStack pickupBlock(LevelAccessor,BlockPos,BlockState)
- Optional getPickupSound()
```

</details>





<details>
<summary>
net.minecraft.world.level.block.SimpleWaterloggedBlock
</summary>

```diff
+ Fluid takeLiquid(LevelAccessor,BlockPos,BlockState)
- ItemStack pickupBlock(LevelAccessor,BlockPos,BlockState)
- Optional getPickupSound()
```

</details>



<details>
<summary>
net.minecraft.world.level.block.SmokerBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SoulFireBlock
</summary>

```diff
+ boolean canSurviveOnBlock(Block)
- boolean canSurviveOnBlock(BlockState)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.StairBlock
</summary>

```diff
+ void prepareRender(BlockGetter,BlockPos)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.entity.BeaconBlockEntity
</summary>

```diff
+ int getLevels()
- int updateBase(Level,int,int,int)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void applyEffects()
- void applyEffects(Level,BlockPos,int,MobEffect,MobEffect)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void playSound(Level,BlockPos,SoundEvent)
+ void playSound(SoundEvent)
- void setLevel(Level)
+ void tick()
- void tick(Level,BlockPos,BlockState,BeaconBlockEntity)
+ void updateBase(int,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.BeehiveBlockEntity
</summary>

```diff
+ boolean releaseOccupant(BlockState,BeehiveBlockEntity$BeeData,List,BeehiveBlockEntity$BeeReleaseStatus)
- boolean releaseOccupant(Level,BlockPos,BlockState,BeehiveBlockEntity$BeeData,List,BeehiveBlockEntity$BeeReleaseStatus,BlockPos)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void sendDebugPackets()
- void serverTick(Level,BlockPos,BlockState,BeehiveBlockEntity)
+ void tick()
+ void tickOccupants()
- void tickOccupants(Level,BlockPos,BlockState,List,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.BellBlockEntity
</summary>

```diff
+ boolean areRaidersNearby()
- boolean areRaidersNearby(BlockPos,List)
- boolean isRaiderWithinRange(BlockPos,LivingEntity)
+ boolean isRaiderWithinRange(LivingEntity)
- boolean lambda$makeRaidersGlow$0(BlockPos,LivingEntity)
+ boolean lambda$showBellParticles$0(BlockPos,LivingEntity)
- boolean lambda$showBellParticles$1(BlockPos,LivingEntity)
- boolean lambda$showBellParticles$2(BlockPos,LivingEntity)
+ void <init>()
- void <init>(BlockPos,BlockState)
- void clientTick(Level,BlockPos,BlockState,BellBlockEntity)
+ void lambda$showBellParticles$1(BlockPos,int,MutableInt,Level,LivingEntity)
- void lambda$showBellParticles$3(BlockPos,int,MutableInt,Level,LivingEntity)
- void makeRaidersGlow(Level,BlockPos,List)
+ void makeRaidersGlow(Level)
+ void playResonateSound()
- void serverTick(Level,BlockPos,BlockState,BellBlockEntity)
- void showBellParticles(Level,BlockPos,List)
+ void showBellParticles(Level)
+ void tick()
- void tick(Level,BlockPos,BlockState,BellBlockEntity,BellBlockEntity$ResonationEndAction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DropperBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.EnderChestBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
- void lidAnimateTick(Level,BlockPos,BlockState,EnderChestBlockEntity)
- void recheckOpen()
+ void setRemoved()
+ void startOpen()
- void startOpen(Player)
+ void stopOpen()
- void stopOpen(Player)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
+ AABB getBoundingBox(Direction)
+ AABB getTopBoundingBox(Direction)
+ void <init>()
- void <init>(BlockPos,BlockState)
- void <init>(DyeColor,BlockPos,BlockState)
+ void <init>(DyeColor)
+ void doNeighborUpdates()
- void doNeighborUpdates(Level,BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void moveCollidedEntities()
- void moveCollidedEntities(Level,BlockPos,BlockState)
+ void tick()
- void tick(Level,BlockPos,BlockState,ShulkerBoxBlockEntity)
+ void updateAnimation()
- void updateAnimation(Level,BlockPos,BlockState)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
- void dragonHeadAnimation(Level,BlockPos,BlockState,SkullBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
- void clientTick(Level,BlockPos,BlockState,SpawnerBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void serverTick(Level,BlockPos,BlockState,SpawnerBlockEntity)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
+ Component getDisplayName()
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void nextMode()
```

</details>






<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
+ LevelLightEngine getLightEngine()
- void setBlockEntity(BlockEntity)
+ void setBlockEntity(BlockPos,BlockEntity)
+ void setLastSaveTime(long)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.OldChunkStorage
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ BlockGetter getBaseColumn(int,int)
- NoiseColumn getBaseColumn(int,int)
```

</details>















<details>
<summary>
net.minecraft.world.level.material.WaterFluid
</summary>

```diff
- Optional getPickupSound()
```

</details>




<details>
<summary>
net.minecraft.world.level.newbiome.context.LazyAreaContext
</summary>

```diff
+ long getMixedSeed()
```

</details>

























<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
- MapItemSavedData$MapPatch createPatch()
- Packet access$200(MapItemSavedData$HoldingPlayer,int)
- Packet nextUpdatePacket(int)
+ Packet nextUpdatePacket(ItemStack)
- void <init>(MapItemSavedData,Player,MapItemSavedData$1)
- void access$300(MapItemSavedData$HoldingPlayer,int,int)
- void access$400(MapItemSavedData$HoldingPlayer)
- void markColorsDirty(int,int)
- void markDecorationsDirty()
+ void markDirty(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.CommandStorage$Container
</summary>

```diff
- CommandStorage$Container access$100(CommandStorage$Container,CompoundTag)
- CommandStorage$Container load(CompoundTag)
- void <init>()
- void <init>(CommandStorage$1)
+ void <init>(String)
+ void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DimensionDataStorage
</summary>

```diff
- SavedData computeIfAbsent(Function,Supplier,String)
+ SavedData computeIfAbsent(Supplier,String)
- SavedData get(Function,String)
+ SavedData get(Supplier,String)
- SavedData readSavedData(Function,String)
+ SavedData readSavedData(Supplier,String)
- void lambda$save$0(String,SavedData)
+ void set(SavedData)
- void set(String,SavedData)
```

</details>



<details>
<summary>
net.minecraft.world.level.storage.LevelSummary
</summary>

```diff
+ boolean shouldBackup()
- LevelSummary$BackupStatus backupStatus()
```

</details>




<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
</summary>

```diff
- EnchantWithLevelsFunction$Builder enchantWithLevels(NumberProvider)
+ EnchantWithLevelsFunction$Builder enchantWithLevels(RandomIntGenerator)
- NumberProvider access$100(EnchantWithLevelsFunction)
+ RandomIntGenerator access$100(EnchantWithLevelsFunction)
- Set getReferencedContextParams()
- void <init>(LootItemCondition[],NumberProvider,boolean,EnchantWithLevelsFunction$1)
- void <init>(LootItemCondition[],NumberProvider,boolean)
+ void <init>(LootItemCondition[],RandomIntGenerator,boolean,EnchantWithLevelsFunction$1)
+ void <init>(LootItemCondition[],RandomIntGenerator,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
</summary>

```diff
- void <init>(NumberProvider)
+ void <init>(RandomIntGenerator)
```

</details>









<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
- LootingEnchantFunction$Builder lootingMultiplier(NumberProvider)
+ LootingEnchantFunction$Builder lootingMultiplier(RandomValueBounds)
- NumberProvider access$100(LootingEnchantFunction)
+ RandomValueBounds access$100(LootingEnchantFunction)
- void <init>(LootItemCondition[],NumberProvider,int,LootingEnchantFunction$1)
- void <init>(LootItemCondition[],NumberProvider,int)
+ void <init>(LootItemCondition[],RandomValueBounds,int,LootingEnchantFunction$1)
+ void <init>(LootItemCondition[],RandomValueBounds,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
</summary>

```diff
- void <init>(NumberProvider)
+ void <init>(RandomValueBounds)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
- Set getReferencedContextParams()
- SetAttributesFunction$ModifierBuilder modifier(String,Attribute,AttributeModifier$Operation,NumberProvider)
+ SetAttributesFunction$ModifierBuilder modifier(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
- Stream lambda$getReferencedContextParams$0(SetAttributesFunction$Modifier)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
</summary>

```diff
- void <init>(String,Attribute,AttributeModifier$Operation,NumberProvider)
+ void <init>(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
```

</details>





<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
- boolean access$100(SetItemDamageFunction)
- LootItemConditionalFunction$Builder setDamage(NumberProvider,boolean)
- LootItemConditionalFunction$Builder setDamage(NumberProvider)
+ LootItemConditionalFunction$Builder setDamage(RandomValueBounds)
- LootItemFunction lambda$setDamage$0(NumberProvider,LootItemCondition[])
+ LootItemFunction lambda$setDamage$0(RandomValueBounds,LootItemCondition[])
- LootItemFunction lambda$setDamage$1(NumberProvider,boolean,LootItemCondition[])
- NumberProvider access$000(SetItemDamageFunction)
+ RandomValueBounds access$000(SetItemDamageFunction)
- Set getReferencedContextParams()
- void <init>(LootItemCondition[],NumberProvider,boolean,SetItemDamageFunction$1)
- void <init>(LootItemCondition[],NumberProvider,boolean)
+ void <init>(LootItemCondition[],RandomValueBounds,SetItemDamageFunction$1)
+ void <init>(LootItemCondition[],RandomValueBounds)
```

</details>





<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
</summary>

```diff
- Set getReferencedContextParams()
- Stream lambda$getReferencedContextParams$0(NumberProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
</summary>

```diff
- SetStewEffectFunction$Builder withEffect(MobEffect,NumberProvider)
+ SetStewEffectFunction$Builder withEffect(MobEffect,RandomValueBounds)
```

</details>













<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
+ boolean hasScore(Entity,Scoreboard,String,RandomValueBounds)
- boolean hasScore(LootContext,Entity,Scoreboard,String,IntRange)
- Stream lambda$getReferencedContextParams$0(IntRange)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
</summary>

```diff
- EntityHasScoreCondition$Builder withScore(String,IntRange)
+ EntityHasScoreCondition$Builder withScore(String,RandomValueBounds)
```

</details>
























<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
+ double clipXCollide(AABB,double)
+ double clipYCollide(AABB,double)
+ double clipZCollide(AABB,double)
```

</details>


<details>
<summary>
net.minecraft.world.phys.Vec3
</summary>

```diff
- DataResult lambda$static$1(DoubleStream)
- DoubleStream lambda$static$2(Vec3)
- Vec3 lambda$null$0(double[])
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
</summary>

```diff
- BitSetDiscreteVoxelShape withFilledBounds(int,int,int,int,int,int,int,int,int)
- boolean isXZRectangleFull(int,int,int,int,int)
+ void <init>(int,int,int,int,int,int,int,int,int)
- void clearZStrip(int,int,int,int)
- void fill(int,int,int)
- void fillUpdateBounds(int,int,int,boolean)
- void forAllBoxes(DiscreteVoxelShape,DiscreteVoxelShape$IntLineConsumer,boolean)
+ void setFull(int,int,int,boolean,boolean)
+ void setZStrip(int,int,int,int,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.phys.shapes.DiscreteVoxelShape
</summary>

```diff
+ boolean isXZRectangleFull(int,int,int,int,int)
+ boolean isZStripFull(int,int,int,int)
+ void setZStrip(int,int,int,int,boolean)
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext$1
</summary>

```diff
+ void <init>(boolean,double,Item,Predicate)
- void <init>(boolean,double,ItemStack,ItemStack,Predicate,Optional)
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.IndirectMerger
</summary>

```diff
- int size()
- void <clinit>()
```

</details>
</details>