## Comparison with [20w51a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w51a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w51a</th><th>1.16.5-rc1</th></tr><tr><td>DataPack version</td><td><pre>7</pre></td><td><pre>/</pre></td></tr><tr><td>ResourcePack version</td><td><pre>7</pre></td><td><pre>/</pre></td></tr><tr><td>World version</td><td><pre>2687</pre></td><td><pre>2585</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741833</pre></td><td><pre>1073741834</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w51a</th><th>1.16.5-rc1</th></tr><tr><td>com.mojang:javabridge</td><td><pre>1.1.23</pre></td><td><pre>1.0.22</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
- game_event.txt
- loot_nbt_provider_type.txt
- loot_number_provider_type.txt
- loot_score_provider_type.txt
- position_source_type.txt
```

</details>
<details>
<summary>
activity
</summary>

```diff
- minecraft:play_dead
```

</details>
<details>
<summary>
block
</summary>

```diff
- minecraft:amethyst_block
- minecraft:amethyst_cluster
- minecraft:black_candle
- minecraft:black_candle_cake
- minecraft:blue_candle
- minecraft:blue_candle_cake
- minecraft:brown_candle
- minecraft:brown_candle_cake
- minecraft:budding_amethyst
- minecraft:calcite
- minecraft:candle
- minecraft:candle_cake
- minecraft:copper_block
- minecraft:copper_ore
- minecraft:cut_copper
- minecraft:cut_copper_slab
- minecraft:cut_copper_stairs
- minecraft:cyan_candle
- minecraft:cyan_candle_cake
- minecraft:dirt_path
- minecraft:dripstone_block
+ minecraft:grass_path
- minecraft:gray_candle
- minecraft:gray_candle_cake
- minecraft:green_candle
- minecraft:green_candle_cake
- minecraft:large_amethyst_bud
- minecraft:lava_cauldron
- minecraft:light_blue_candle
- minecraft:light_blue_candle_cake
- minecraft:light_gray_candle
- minecraft:light_gray_candle_cake
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:lightning_rod
- minecraft:lime_candle
- minecraft:lime_candle_cake
- minecraft:magenta_candle
- minecraft:magenta_candle_cake
- minecraft:medium_amethyst_bud
- minecraft:orange_candle
- minecraft:orange_candle_cake
- minecraft:pink_candle
- minecraft:pink_candle_cake
- minecraft:pointed_dripstone
- minecraft:powder_snow
- minecraft:powder_snow_cauldron
- minecraft:purple_candle
- minecraft:purple_candle_cake
- minecraft:red_candle
- minecraft:red_candle_cake
- minecraft:sculk_sensor
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:small_amethyst_bud
- minecraft:tinted_glass
- minecraft:tuff
- minecraft:water_cauldron
- minecraft:waxed_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:weathered_copper_block
- minecraft:weathered_cut_copper
- minecraft:weathered_cut_copper_slab
- minecraft:weathered_cut_copper_stairs
- minecraft:white_candle
- minecraft:white_candle_cake
- minecraft:yellow_candle
- minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
- minecraft:sculk_sensor
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:axolotl
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:amethyst_block
- minecraft:amethyst_cluster
- minecraft:amethyst_shard
- minecraft:axolotl_bucket
- minecraft:axolotl_spawn_egg
- minecraft:black_candle
- minecraft:blue_candle
- minecraft:brown_candle
- minecraft:budding_amethyst
- minecraft:bundle
- minecraft:calcite
- minecraft:candle
- minecraft:copper_block
- minecraft:copper_ingot
- minecraft:copper_ore
- minecraft:cut_copper
- minecraft:cut_copper_slab
- minecraft:cut_copper_stairs
- minecraft:cyan_candle
- minecraft:dirt_path
- minecraft:dripstone_block
+ minecraft:grass_path
- minecraft:gray_candle
- minecraft:green_candle
- minecraft:large_amethyst_bud
- minecraft:light_blue_candle
- minecraft:light_gray_candle
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:lightning_rod
- minecraft:lime_candle
- minecraft:magenta_candle
- minecraft:medium_amethyst_bud
- minecraft:orange_candle
- minecraft:pink_candle
- minecraft:pointed_dripstone
- minecraft:powder_snow_bucket
- minecraft:purple_candle
- minecraft:red_candle
- minecraft:sculk_sensor
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:small_amethyst_bud
- minecraft:spyglass
- minecraft:tinted_glass
- minecraft:tuff
- minecraft:waxed_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:weathered_copper_block
- minecraft:weathered_cut_copper
- minecraft:weathered_cut_copper_slab
- minecraft:weathered_cut_copper_stairs
- minecraft:white_candle
- minecraft:yellow_candle
```

</details>
<details>
<summary>
loot_condition_type
</summary>

```diff
- minecraft:value_check
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
- minecraft:set_banner_pattern
- minecraft:set_enchantments
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
- minecraft:is_tempted
- minecraft:play_dead_ticks
- minecraft:temptation_cooldown_ticks
- minecraft:tempting_player
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
- minecraft:dripping_dripstone_lava
- minecraft:dripping_dripstone_water
- minecraft:dust_color_transition
- minecraft:falling_dripstone_lava
- minecraft:falling_dripstone_water
- minecraft:small_flame
- minecraft:snowflake
- minecraft:vibration
```

</details>
<details>
<summary>
point_of_interest_type
</summary>

```diff
- minecraft:lightning_rod
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
- minecraft:axolotl_hostiles
- minecraft:axolotl_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
- minecraft:block.amethyst_block.break
- minecraft:block.amethyst_block.chime
- minecraft:block.amethyst_block.fall
- minecraft:block.amethyst_block.hit
- minecraft:block.amethyst_block.place
- minecraft:block.amethyst_block.step
- minecraft:block.amethyst_cluster.break
- minecraft:block.amethyst_cluster.fall
- minecraft:block.amethyst_cluster.hit
- minecraft:block.amethyst_cluster.place
- minecraft:block.amethyst_cluster.step
- minecraft:block.cake.add_candle
- minecraft:block.calcite.break
- minecraft:block.calcite.fall
- minecraft:block.calcite.hit
- minecraft:block.calcite.place
- minecraft:block.calcite.step
- minecraft:block.candle.ambient
- minecraft:block.candle.break
- minecraft:block.candle.extinguish
- minecraft:block.candle.fall
- minecraft:block.candle.hit
- minecraft:block.candle.place
- minecraft:block.candle.step
- minecraft:block.copper.break
- minecraft:block.copper.fall
- minecraft:block.copper.hit
- minecraft:block.copper.place
- minecraft:block.copper.step
- minecraft:block.dripstone_block.break
- minecraft:block.dripstone_block.fall
- minecraft:block.dripstone_block.hit
- minecraft:block.dripstone_block.place
- minecraft:block.dripstone_block.step
- minecraft:block.large_amethyst_bud.break
- minecraft:block.large_amethyst_bud.place
- minecraft:block.medium_amethyst_bud.break
- minecraft:block.medium_amethyst_bud.place
- minecraft:block.pointed_dripstone.break
- minecraft:block.pointed_dripstone.drip_lava
- minecraft:block.pointed_dripstone.drip_lava_into_cauldron
- minecraft:block.pointed_dripstone.drip_water
- minecraft:block.pointed_dripstone.drip_water_into_cauldron
- minecraft:block.pointed_dripstone.fall
- minecraft:block.pointed_dripstone.hit
- minecraft:block.pointed_dripstone.land
- minecraft:block.pointed_dripstone.place
- minecraft:block.pointed_dripstone.step
- minecraft:block.powder_snow.break
- minecraft:block.powder_snow.fall
- minecraft:block.powder_snow.hit
- minecraft:block.powder_snow.place
- minecraft:block.powder_snow.step
- minecraft:block.sculk_sensor.break
- minecraft:block.sculk_sensor.clicking
- minecraft:block.sculk_sensor.clicking_stop
- minecraft:block.sculk_sensor.fall
- minecraft:block.sculk_sensor.hit
- minecraft:block.sculk_sensor.place
- minecraft:block.sculk_sensor.step
- minecraft:block.small_amethyst_bud.break
- minecraft:block.small_amethyst_bud.place
- minecraft:block.tuff.break
- minecraft:block.tuff.fall
- minecraft:block.tuff.hit
- minecraft:block.tuff.place
- minecraft:block.tuff.step
- minecraft:entity.axolotl.attack
- minecraft:entity.axolotl.death
- minecraft:entity.axolotl.hurt
- minecraft:entity.axolotl.idle_air
- minecraft:entity.axolotl.idle_water
- minecraft:entity.axolotl.splash
- minecraft:entity.axolotl.swim
- minecraft:entity.minecart.inside.underwater
- minecraft:entity.player.hurt_freeze
- minecraft:item.bucket.empty_axolotl
- minecraft:item.bucket.empty_powder_snow
- minecraft:item.bucket.fill_axolotl
- minecraft:item.bucket.fill_powder_snow
- minecraft:item.spyglass.stop_using
- minecraft:item.spyglass.use
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:geode
- minecraft:large_dripstone
- minecraft:small_dripstone
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
- universal_tags/game_event.json
- universal_tags/loot_nbt_provider_type.json
- universal_tags/loot_number_provider_type.json
- universal_tags/loot_score_provider_type.json
- universal_tags/position_source_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:budding_amethyst
- minecraft:powder_snow
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:amethyst_block
- minecraft:amethyst_cluster
- minecraft:black_candle
- minecraft:black_candle_cake
- minecraft:blue_candle
- minecraft:blue_candle_cake
- minecraft:brown_candle
- minecraft:brown_candle_cake
- minecraft:calcite
- minecraft:candle
- minecraft:candle_cake
- minecraft:copper_block
- minecraft:copper_ore
- minecraft:cut_copper
- minecraft:cut_copper_slab
- minecraft:cut_copper_stairs
- minecraft:cyan_candle
- minecraft:cyan_candle_cake
- minecraft:dirt_path
- minecraft:dripstone_block
+ minecraft:grass_path
- minecraft:gray_candle
- minecraft:gray_candle_cake
- minecraft:green_candle
- minecraft:green_candle_cake
- minecraft:large_amethyst_bud
- minecraft:lava_cauldron
- minecraft:light_blue_candle
- minecraft:light_blue_candle_cake
- minecraft:light_gray_candle
- minecraft:light_gray_candle_cake
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:lightning_rod
- minecraft:lime_candle
- minecraft:lime_candle_cake
- minecraft:magenta_candle
- minecraft:magenta_candle_cake
- minecraft:medium_amethyst_bud
- minecraft:orange_candle
- minecraft:orange_candle_cake
- minecraft:pink_candle
- minecraft:pink_candle_cake
- minecraft:pointed_dripstone
- minecraft:powder_snow_cauldron
- minecraft:purple_candle
- minecraft:purple_candle_cake
- minecraft:red_candle
- minecraft:red_candle_cake
- minecraft:sculk_sensor
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:small_amethyst_bud
- minecraft:tinted_glass
- minecraft:tuff
- minecraft:water_cauldron
- minecraft:waxed_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:weathered_copper_block
- minecraft:weathered_cut_copper
- minecraft:weathered_cut_copper_slab
- minecraft:weathered_cut_copper_stairs
- minecraft:white_candle
- minecraft:white_candle_cake
- minecraft:yellow_candle
- minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
- minecraft:axolotl
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
- minecraft:axolotl
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
- minecraft:budding_amethyst
- minecraft:powder_snow
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
- minecraft:play_dead
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:amethyst_block
- minecraft:amethyst_cluster
- minecraft:black_candle
- minecraft:black_candle_cake
- minecraft:blue_candle
- minecraft:blue_candle_cake
- minecraft:brown_candle
- minecraft:brown_candle_cake
- minecraft:budding_amethyst
- minecraft:calcite
- minecraft:candle
- minecraft:candle_cake
- minecraft:copper_block
- minecraft:copper_ore
- minecraft:cut_copper
- minecraft:cut_copper_slab
- minecraft:cut_copper_stairs
- minecraft:cyan_candle
- minecraft:cyan_candle_cake
- minecraft:dirt_path
- minecraft:dripstone_block
+ minecraft:grass_path
- minecraft:gray_candle
- minecraft:gray_candle_cake
- minecraft:green_candle
- minecraft:green_candle_cake
- minecraft:large_amethyst_bud
- minecraft:lava_cauldron
- minecraft:light_blue_candle
- minecraft:light_blue_candle_cake
- minecraft:light_gray_candle
- minecraft:light_gray_candle_cake
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:lightning_rod
- minecraft:lime_candle
- minecraft:lime_candle_cake
- minecraft:magenta_candle
- minecraft:magenta_candle_cake
- minecraft:medium_amethyst_bud
- minecraft:orange_candle
- minecraft:orange_candle_cake
- minecraft:pink_candle
- minecraft:pink_candle_cake
- minecraft:pointed_dripstone
- minecraft:powder_snow
- minecraft:powder_snow_cauldron
- minecraft:purple_candle
- minecraft:purple_candle_cake
- minecraft:red_candle
- minecraft:red_candle_cake
- minecraft:sculk_sensor
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:small_amethyst_bud
- minecraft:tinted_glass
- minecraft:tuff
- minecraft:water_cauldron
- minecraft:waxed_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:weathered_copper_block
- minecraft:weathered_cut_copper
- minecraft:weathered_cut_copper_slab
- minecraft:weathered_cut_copper_stairs
- minecraft:white_candle
- minecraft:white_candle_cake
- minecraft:yellow_candle
- minecraft:yellow_candle_cake
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
- minecraft:sculk_sensor
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:axolotl
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:amethyst_block
- minecraft:amethyst_cluster
- minecraft:amethyst_shard
- minecraft:axolotl_bucket
- minecraft:axolotl_spawn_egg
- minecraft:black_candle
- minecraft:blue_candle
- minecraft:brown_candle
- minecraft:budding_amethyst
- minecraft:bundle
- minecraft:calcite
- minecraft:candle
- minecraft:copper_block
- minecraft:copper_ingot
- minecraft:copper_ore
- minecraft:cut_copper
- minecraft:cut_copper_slab
- minecraft:cut_copper_stairs
- minecraft:cyan_candle
- minecraft:dirt_path
- minecraft:dripstone_block
+ minecraft:grass_path
- minecraft:gray_candle
- minecraft:green_candle
- minecraft:large_amethyst_bud
- minecraft:light_blue_candle
- minecraft:light_gray_candle
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
- minecraft:lightning_rod
- minecraft:lime_candle
- minecraft:magenta_candle
- minecraft:medium_amethyst_bud
- minecraft:orange_candle
- minecraft:pink_candle
- minecraft:pointed_dripstone
- minecraft:powder_snow_bucket
- minecraft:purple_candle
- minecraft:red_candle
- minecraft:sculk_sensor
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
- minecraft:small_amethyst_bud
- minecraft:spyglass
- minecraft:tinted_glass
- minecraft:tuff
- minecraft:waxed_copper
- minecraft:waxed_cut_copper
- minecraft:waxed_cut_copper_slab
- minecraft:waxed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
- minecraft:weathered_copper_block
- minecraft:weathered_cut_copper
- minecraft:weathered_cut_copper_slab
- minecraft:weathered_cut_copper_stairs
- minecraft:white_candle
- minecraft:yellow_candle
```

</details>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
- minecraft:value_check
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
- minecraft:set_banner_pattern
- minecraft:set_enchantments
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
- minecraft:is_tempted
- minecraft:play_dead_ticks
- minecraft:temptation_cooldown_ticks
- minecraft:tempting_player
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
- minecraft:dripping_dripstone_lava
- minecraft:dripping_dripstone_water
- minecraft:dust_color_transition
- minecraft:falling_dripstone_lava
- minecraft:falling_dripstone_water
- minecraft:small_flame
- minecraft:snowflake
- minecraft:vibration
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
- minecraft:lightning_rod
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
- minecraft:axolotl_hostiles
- minecraft:axolotl_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
- minecraft:block.amethyst_block.break
- minecraft:block.amethyst_block.chime
- minecraft:block.amethyst_block.fall
- minecraft:block.amethyst_block.hit
- minecraft:block.amethyst_block.place
- minecraft:block.amethyst_block.step
- minecraft:block.amethyst_cluster.break
- minecraft:block.amethyst_cluster.fall
- minecraft:block.amethyst_cluster.hit
- minecraft:block.amethyst_cluster.place
- minecraft:block.amethyst_cluster.step
- minecraft:block.cake.add_candle
- minecraft:block.calcite.break
- minecraft:block.calcite.fall
- minecraft:block.calcite.hit
- minecraft:block.calcite.place
- minecraft:block.calcite.step
- minecraft:block.candle.ambient
- minecraft:block.candle.break
- minecraft:block.candle.extinguish
- minecraft:block.candle.fall
- minecraft:block.candle.hit
- minecraft:block.candle.place
- minecraft:block.candle.step
- minecraft:block.copper.break
- minecraft:block.copper.fall
- minecraft:block.copper.hit
- minecraft:block.copper.place
- minecraft:block.copper.step
- minecraft:block.dripstone_block.break
- minecraft:block.dripstone_block.fall
- minecraft:block.dripstone_block.hit
- minecraft:block.dripstone_block.place
- minecraft:block.dripstone_block.step
- minecraft:block.large_amethyst_bud.break
- minecraft:block.large_amethyst_bud.place
- minecraft:block.medium_amethyst_bud.break
- minecraft:block.medium_amethyst_bud.place
- minecraft:block.pointed_dripstone.break
- minecraft:block.pointed_dripstone.drip_lava
- minecraft:block.pointed_dripstone.drip_lava_into_cauldron
- minecraft:block.pointed_dripstone.drip_water
- minecraft:block.pointed_dripstone.drip_water_into_cauldron
- minecraft:block.pointed_dripstone.fall
- minecraft:block.pointed_dripstone.hit
- minecraft:block.pointed_dripstone.land
- minecraft:block.pointed_dripstone.place
- minecraft:block.pointed_dripstone.step
- minecraft:block.powder_snow.break
- minecraft:block.powder_snow.fall
- minecraft:block.powder_snow.hit
- minecraft:block.powder_snow.place
- minecraft:block.powder_snow.step
- minecraft:block.sculk_sensor.break
- minecraft:block.sculk_sensor.clicking
- minecraft:block.sculk_sensor.clicking_stop
- minecraft:block.sculk_sensor.fall
- minecraft:block.sculk_sensor.hit
- minecraft:block.sculk_sensor.place
- minecraft:block.sculk_sensor.step
- minecraft:block.small_amethyst_bud.break
- minecraft:block.small_amethyst_bud.place
- minecraft:block.tuff.break
- minecraft:block.tuff.fall
- minecraft:block.tuff.hit
- minecraft:block.tuff.place
- minecraft:block.tuff.step
- minecraft:entity.axolotl.attack
- minecraft:entity.axolotl.death
- minecraft:entity.axolotl.hurt
- minecraft:entity.axolotl.idle_air
- minecraft:entity.axolotl.idle_water
- minecraft:entity.axolotl.splash
- minecraft:entity.axolotl.swim
- minecraft:entity.minecart.inside.underwater
- minecraft:entity.player.hurt_freeze
- minecraft:item.bucket.empty_axolotl
- minecraft:item.bucket.empty_powder_snow
- minecraft:item.bucket.fill_axolotl
- minecraft:item.bucket.fill_powder_snow
- minecraft:item.spyglass.stop_using
- minecraft:item.spyglass.use
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:geode
- minecraft:large_dripstone
- minecraft:small_dripstone
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
- amethyst_block.json
- amethyst_cluster.json
- black_candle_cake.json
- black_candle.json
- blue_candle_cake.json
- blue_candle.json
- brown_candle_cake.json
- brown_candle.json
- budding_amethyst.json
- calcite.json
- candle_cake.json
- candle.json
- copper_block.json
- copper_ore.json
- cut_copper_slab.json
- cut_copper_stairs.json
- cut_copper.json
- cyan_candle_cake.json
- cyan_candle.json
- dirt_path.json
- dripstone_block.json
+ grass_path.json
- gray_candle_cake.json
- gray_candle.json
- green_candle_cake.json
- green_candle.json
- large_amethyst_bud.json
- lava_cauldron.json
- light_blue_candle_cake.json
- light_blue_candle.json
- light_gray_candle_cake.json
- light_gray_candle.json
- lightly_weathered_copper_block.json
- lightly_weathered_cut_copper_slab.json
- lightly_weathered_cut_copper_stairs.json
- lightly_weathered_cut_copper.json
- lightning_rod.json
- lime_candle_cake.json
- lime_candle.json
- magenta_candle_cake.json
- magenta_candle.json
- medium_amethyst_bud.json
- orange_candle_cake.json
- orange_candle.json
- pink_candle_cake.json
- pink_candle.json
- pointed_dripstone.json
- powder_snow_cauldron.json
- powder_snow.json
- purple_candle_cake.json
- purple_candle.json
- red_candle_cake.json
- red_candle.json
- sculk_sensor.json
- semi_weathered_copper_block.json
- semi_weathered_cut_copper_slab.json
- semi_weathered_cut_copper_stairs.json
- semi_weathered_cut_copper.json
- small_amethyst_bud.json
- tinted_glass.json
- tuff.json
- water_cauldron.json
- waxed_copper.json
- waxed_cut_copper_slab.json
- waxed_cut_copper_stairs.json
- waxed_cut_copper.json
- waxed_lightly_weathered_copper.json
- waxed_lightly_weathered_cut_copper_slab.json
- waxed_lightly_weathered_cut_copper_stairs.json
- waxed_lightly_weathered_cut_copper.json
- waxed_semi_weathered_copper.json
- waxed_semi_weathered_cut_copper_slab.json
- waxed_semi_weathered_cut_copper_stairs.json
- waxed_semi_weathered_cut_copper.json
- weathered_copper_block.json
- weathered_cut_copper_slab.json
- weathered_cut_copper_stairs.json
- weathered_cut_copper.json
- white_candle_cake.json
- white_candle.json
- yellow_candle_cake.json
- yellow_candle.json
```

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
- item.txt
+ replaceitem.txt
```

</details>
<details>
<summary>
gamerule
</summary>

```diff
- gamerule freezeDamage <value: bool>
- gamerule playersSleepingPercentage <value: integer>
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
- amethyst_block.json
- black_candle.json
- blue_candle.json
- brown_candle.json
- bundle.json
- candle.json
- copper_block.json
- copper_ingot_from_blasting.json
- copper_ingot_from_copper_block.json
- copper_ingot.json
- cut_copper_slab.json
- cut_copper_stairs.json
- cut_copper.json
- cyan_candle.json
- firework_rocket_simple.json
- gray_candle.json
- green_candle.json
- light_blue_candle.json
- light_gray_candle.json
- lightly_weathered_cut_copper_slab.json
- lightly_weathered_cut_copper_stairs.json
- lightly_weathered_cut_copper.json
- lightning_rod.json
- lime_candle.json
- magenta_candle.json
- orange_candle.json
- pink_candle.json
- purple_candle.json
- red_candle.json
- semi_weathered_cut_copper_slab.json
- semi_weathered_cut_copper_stairs.json
- semi_weathered_cut_copper.json
- spyglass.json
- tinted_glass.json
- waxed_copper_cut_slab_from_honeycomb.json
- waxed_copper_cut_stairs_from_honeycomb.json
- waxed_copper.json
- waxed_cut_copper_from_honeycomb.json
- waxed_cut_copper_from_waxed_block.json
- waxed_cut_copper_slab.json
- waxed_cut_copper_stairs.json
- waxed_lightly_weathered_copper.json
- waxed_lightly_weathered_cut_copper_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_from_waxed_block.json
- waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_slab.json
- waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_stairs.json
- waxed_semi_weathered_copper.json
- waxed_semi_weathered_cut_copper_from_honeycomb.json
- waxed_semi_weathered_cut_copper_from_waxed_block.json
- waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- waxed_semi_weathered_cut_copper_slab.json
- waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- waxed_semi_weathered_cut_copper_stairs.json
- weathered_cut_copper_slab.json
- weathered_cut_copper_stairs.json
- weathered_cut_copper.json
- white_candle.json
- yellow_candle.json
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
- advMode.mode: Mode
- advMode.trackOutput: Track output
- advMode.triggering: Triggering
- advMode.type: Type
- argument.angle.invalid: Invalid angle
- biome.minecraft.dripstone_caves: Dripstone caves
- block.minecraft.amethyst_block: Block of Amethyst
- block.minecraft.amethyst_cluster: Amethyst Cluster
- block.minecraft.banner.base.black: Fully Black Field
- block.minecraft.banner.base.blue: Fully Blue Field
- block.minecraft.banner.base.brown: Fully Brown Field
- block.minecraft.banner.base.cyan: Fully Cyan Field
- block.minecraft.banner.base.gray: Fully Gray Field
- block.minecraft.banner.base.green: Fully Green Field
- block.minecraft.banner.base.light_blue: Fully Light Blue Field
- block.minecraft.banner.base.light_gray: Fully Light Gray Field
- block.minecraft.banner.base.lime: Fully Lime Field
- block.minecraft.banner.base.magenta: Fully Magenta Field
- block.minecraft.banner.base.orange: Fully Orange Field
- block.minecraft.banner.base.pink: Fully Pink Field
- block.minecraft.banner.base.purple: Fully Purple Field
- block.minecraft.banner.base.red: Fully Red Field
- block.minecraft.banner.base.white: Fully White Field
- block.minecraft.banner.base.yellow: Fully Yellow Field
- block.minecraft.black_candle_cake: Black Candle Cake
- block.minecraft.black_candle: Black Candle
- block.minecraft.blue_candle_cake: Blue Candle Cake
- block.minecraft.blue_candle: Blue Candle
- block.minecraft.brown_candle_cake: Brown Candle Cake
- block.minecraft.brown_candle: Brown Candle
- block.minecraft.budding_amethyst: Budding Amethyst
- block.minecraft.calcite: Calcite
- block.minecraft.candle_cake: Candle Cake
- block.minecraft.candle: Candle
- block.minecraft.copper_block: Copper Block
- block.minecraft.copper_ore: Copper Ore
- block.minecraft.cut_copper_slab: Cut Copper Slab
- block.minecraft.cut_copper_stairs: Cut Copper Stairs
- block.minecraft.cut_copper: Cut Copper
- block.minecraft.cyan_candle_cake: Cyan Candle Cake
- block.minecraft.cyan_candle: Cyan Candle
- block.minecraft.dirt_path: Dirt Path
- block.minecraft.dripstone_block: Dripstone Block
+ block.minecraft.grass_path: Grass Path
- block.minecraft.gray_candle_cake: Gray Candle Cake
- block.minecraft.gray_candle: Gray Candle
- block.minecraft.green_candle_cake: Green Candle Cake
- block.minecraft.green_candle: Green Candle
- block.minecraft.large_amethyst_bud: Large Amethyst Bud
- block.minecraft.lava_cauldron: Lava Cauldron
- block.minecraft.light_blue_candle_cake: Light Blue Candle Cake
- block.minecraft.light_blue_candle: Light Blue Candle
- block.minecraft.light_gray_candle_cake: Light Gray Candle Cake
- block.minecraft.light_gray_candle: Light Gray Candle
- block.minecraft.lightly_weathered_copper_block: Lightly Weathered Copper Block
- block.minecraft.lightly_weathered_cut_copper_slab: Lightly Weathered Cut Copper Slab
- block.minecraft.lightly_weathered_cut_copper_stairs: Lightly Weathered Cut Copper Stairs
- block.minecraft.lightly_weathered_cut_copper: Lightly Weathered Cut Copper
- block.minecraft.lightning_rod: Lightning Rod
- block.minecraft.lime_candle_cake: Lime Candle Cake
- block.minecraft.lime_candle: Lime Candle
- block.minecraft.magenta_candle_cake: Magenta Candle Cake
- block.minecraft.magenta_candle: Magenta Candle
- block.minecraft.medium_amethyst_bud: Medium Amethyst Bud
- block.minecraft.orange_candle_cake: Orange Candle Cake
- block.minecraft.orange_candle: Orange Candle
- block.minecraft.pink_candle_cake: Pink Candle Cake
- block.minecraft.pink_candle: Pink Candle
- block.minecraft.pointed_dripstone: Pointed Dripstone
- block.minecraft.powder_snow_cauldron: Powder Snow Cauldron
- block.minecraft.powder_snow: Powder Snow
- block.minecraft.purple_candle_cake: Purple Candle Cake
- block.minecraft.purple_candle: Purple Candle
- block.minecraft.red_candle_cake: Red Candle Cake
- block.minecraft.red_candle: Red Candle
- block.minecraft.sculk_sensor: Sculk Sensor
- block.minecraft.semi_weathered_copper_block: Semi-Weathered Copper Block
- block.minecraft.semi_weathered_cut_copper_slab: Semi Weathered Cut Copper Slab
- block.minecraft.semi_weathered_cut_copper_stairs: Semi-Weathered Cut Copper Stairs
- block.minecraft.semi_weathered_cut_copper: Semi-Weathered Cut Copper
- block.minecraft.small_amethyst_bud: Small Amethyst Bud
- block.minecraft.tinted_glass: Tinted Glass
- block.minecraft.tuff: Tuff
- block.minecraft.water_cauldron: Water Cauldron
- block.minecraft.waxed_copper: Waxed Copper
- block.minecraft.waxed_cut_copper_slab: Waxed Cut Copper Slab
- block.minecraft.waxed_cut_copper_stairs: Waxed Cut Copper Stairs
- block.minecraft.waxed_cut_copper: Waxed Cut Copper
- block.minecraft.waxed_lightly_weathered_copper_block: Waxed Lightly Weathered Copper Block
- block.minecraft.waxed_lightly_weathered_copper: Waxed Lightly Weathered Copper
- block.minecraft.waxed_lightly_weathered_cut_copper_slab: Waxed Lightly Weathered Cut Copper Slab
- block.minecraft.waxed_lightly_weathered_cut_copper_stairs: Waxed Lightly Weathered Cut Copper Stairs
- block.minecraft.waxed_lightly_weathered_cut_copper: Waxed Lightly Weathered Cut Copper
- block.minecraft.waxed_semi_weathered_copper_block: Waxed Semi-Weathered Copper Block
- block.minecraft.waxed_semi_weathered_copper: Waxed Semi-Weathered Copper
- block.minecraft.waxed_semi_weathered_cut_copper_slab: Waxed Semi Weathered Cut Copper Slab
- block.minecraft.waxed_semi_weathered_cut_copper_stairs: Waxed Semi-Weathered Cut Copper Stairs
- block.minecraft.waxed_semi_weathered_cut_copper: Waxed Semi-Weathered Cut Copper
- block.minecraft.weathered_copper_block: Weathered Copper BlocK
- block.minecraft.weathered_cut_copper_slab: Weathered Cut Copper Slab
- block.minecraft.weathered_cut_copper_stairs: Weathered Cut Copper Stairs
- block.minecraft.weathered_cut_copper: Weathered Cut Copper
- block.minecraft.white_candle_cake: White Candle Cake
- block.minecraft.white_candle: White Candle
- block.minecraft.yellow_candle_cake: Yellow Candle Cake
- block.minecraft.yellow_candle: Yellow Candle
- commands.item.block.set.success: Replaced a slot at %s, %s, %s with %s
- commands.item.entity.set.success.multiple: Replaced a slot on %s entities with %s
- commands.item.entity.set.success.single: Replaced a slot on %s with %s
- commands.item.source.no_such_slot: The source does not have slot %s
- commands.item.source.not_a_container: Source position %s, %s, %s is not a container
- commands.item.target.no_changed.known_item: No targets accepted item %s into slot %s
- commands.item.target.no_changes: No targets accepted item into slot %s
- commands.item.target.no_such_slot: The target does not have slot %s
- commands.item.target.not_a_container: Target position %s, %s, %s is not a container
+ commands.replaceitem.block.failed: The target block is not a container
+ commands.replaceitem.block.success: Replaced a slot at %s, %s, %s with %s
+ commands.replaceitem.entity.failed: Could not put %s in slot %s
+ commands.replaceitem.entity.success.multiple: Replaced a slot on %s entities with %s
+ commands.replaceitem.entity.success.single: Replaced a slot on %s with %s
+ commands.replaceitem.slot.inapplicable: The target does not have slot %s
- dataPack.vanilla.description: The default data for Minecraft
- death.attack.fallingStalactite: %1$s was skewered by a falling stalactite
- death.attack.fallingStalactite.player: %1$s was skewered by a falling stalactite whilst fighting %2$s
- death.attack.freeze: %1$s froze to death
- death.attack.freeze.player: %1$s was frozen to death by %2$s
- entity.minecraft.axolotl: Axolotl
- gamerule.freezeDamage: Deal freeze damage
- gamerule.playersSleepingPercentage: Sleep percentage
- gamerule.playersSleepingPercentage.description: The percentage of players who must be sleeping to skip the night.
- item_modifier.unknown: Unknown item modifier: %s
- item.minecraft.amethyst_shard: Amethyst Shard
- item.minecraft.axolotl_bucket: Bucket of Axolotl
- item.minecraft.axolotl_spawn_egg: Axolotl Spawn Egg
- item.minecraft.bundle: Bundle
- item.minecraft.bundle.fullness: %s/%s
- item.minecraft.copper_ingot: Copper Ingot
- item.minecraft.powder_snow_bucket: Powder Snow Bucket
- item.minecraft.spyglass: Spyglass
- mirror.front_back: ↑ ↓
- mirror.left_right: ← →
- mirror.none: |
- multiplayer.requiredTexturePrompt.disconnect: Server requires a custom resource pack
- multiplayer.requiredTexturePrompt.line1: This server requires the use of a custom resource pack.
- multiplayer.requiredTexturePrompt.line2: Rejecting a custom resource pack will disconnect you from this server.
+ options.fovEffectScale.off: Off
+ options.screenEffectScale.off: Off
+ options.vbo: Use VBOs
- resourcePack.vanilla.description: The default resources for Minecraft
- sleep.not_possible: No amount of rest can pass this night
- sleep.players_sleeping: %s/%s players sleeping
- sleep.skipping_night: Sleeping through this night
- subtitles.block.cake.add_candle: Cake squishes
- subtitles.block.candle.crackle: Candle crackles
- subtitles.block.pointed_dripstone.drip_lava_into_cauldron: Lava drips into cauldron
- subtitles.block.pointed_dripstone.drip_lava: Lava drips
- subtitles.block.pointed_dripstone.drip_water_into_cauldron: Water drips into cauldron
- subtitles.block.pointed_dripstone.drip_water: Water drips
- subtitles.block.pointed_dripstone.land: Stalactite crashes down
- subtitles.block.sculk_sensor.clicking_stop: Sculk Sensor stops clicking
- subtitles.block.sculk_sensor.clicking: Sculk Sensor starts clicking
- subtitles.entity.axolotl.attack: Axolotl attacks
- subtitles.entity.axolotl.death: Axolotl dies
- subtitles.entity.axolotl.hurt: Axolotl hurts
- subtitles.entity.axolotl.idle_air: Axolotl chirps
- subtitles.entity.axolotl.idle_water: Axolotl chirps
- subtitles.entity.axolotl.splash: Axolotl splashes
- subtitles.entity.axolotl.swim: Axolotl swims
- subtitles.entity.player.freeze_hurt: Player freezes
- subtitles.item.bucket.fill_axolotl: Axolotl scooped
- subtitles.item.spyglass.stop_using: Spyglass retracts
- subtitles.item.spyglass.use: Spyglass expands
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>20w51a</th><th>1.16.5-rc1</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.mapType</div></th><td>World Type</td><td>World Type:</td></tr>
<tr><th align="left"><div style="width:290px">options.vsync</div></th><td>VSync</td><td>Use VSync</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.lapis_block</div></th><td>Block of Lapis Lazuli</td><td>Lapis Lazuli Block</td></tr>
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
- reports/biomes/dripstone_caves.json
```

</details>
<details>
<summary>
data
</summary>

```diff
- minecraft/advancements/recipes/building_blocks/amethyst_block.json
- minecraft/advancements/recipes/building_blocks/copper_block.json
- minecraft/advancements/recipes/building_blocks/cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/cut_copper.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper.json
- minecraft/advancements/recipes/building_blocks/tinted_glass.json
- minecraft/advancements/recipes/building_blocks/waxed_copper_cut_slab_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_copper_cut_stairs_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_block.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_waxed_block.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_waxed_block.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper.json
- minecraft/advancements/recipes/decorations/black_candle.json
- minecraft/advancements/recipes/decorations/blue_candle.json
- minecraft/advancements/recipes/decorations/brown_candle.json
- minecraft/advancements/recipes/decorations/candle.json
- minecraft/advancements/recipes/decorations/cyan_candle.json
- minecraft/advancements/recipes/decorations/gray_candle.json
- minecraft/advancements/recipes/decorations/green_candle.json
- minecraft/advancements/recipes/decorations/light_blue_candle.json
- minecraft/advancements/recipes/decorations/light_gray_candle.json
- minecraft/advancements/recipes/decorations/lime_candle.json
- minecraft/advancements/recipes/decorations/magenta_candle.json
- minecraft/advancements/recipes/decorations/orange_candle.json
- minecraft/advancements/recipes/decorations/pink_candle.json
- minecraft/advancements/recipes/decorations/purple_candle.json
- minecraft/advancements/recipes/decorations/red_candle.json
- minecraft/advancements/recipes/decorations/white_candle.json
- minecraft/advancements/recipes/decorations/yellow_candle.json
- minecraft/advancements/recipes/misc/copper_ingot_from_blasting.json
- minecraft/advancements/recipes/misc/copper_ingot_from_copper_block.json
- minecraft/advancements/recipes/misc/copper_ingot.json
- minecraft/advancements/recipes/misc/firework_rocket_simple.json
- minecraft/advancements/recipes/redstone/lightning_rod.json
- minecraft/advancements/recipes/tools/bundle.json
- minecraft/advancements/recipes/tools/spyglass.json
- minecraft/loot_tables/blocks/amethyst_block.json
- minecraft/loot_tables/blocks/amethyst_cluster.json
- minecraft/loot_tables/blocks/black_candle_cake.json
- minecraft/loot_tables/blocks/black_candle.json
- minecraft/loot_tables/blocks/blue_candle_cake.json
- minecraft/loot_tables/blocks/blue_candle.json
- minecraft/loot_tables/blocks/brown_candle_cake.json
- minecraft/loot_tables/blocks/brown_candle.json
- minecraft/loot_tables/blocks/budding_amethyst.json
- minecraft/loot_tables/blocks/calcite.json
- minecraft/loot_tables/blocks/candle_cake.json
- minecraft/loot_tables/blocks/candle.json
- minecraft/loot_tables/blocks/copper_block.json
- minecraft/loot_tables/blocks/copper_ore.json
- minecraft/loot_tables/blocks/cut_copper_slab.json
- minecraft/loot_tables/blocks/cut_copper_stairs.json
- minecraft/loot_tables/blocks/cut_copper.json
- minecraft/loot_tables/blocks/cyan_candle_cake.json
- minecraft/loot_tables/blocks/cyan_candle.json
- minecraft/loot_tables/blocks/dirt_path.json
- minecraft/loot_tables/blocks/dripstone_block.json
+ minecraft/loot_tables/blocks/grass_path.json
- minecraft/loot_tables/blocks/gray_candle_cake.json
- minecraft/loot_tables/blocks/gray_candle.json
- minecraft/loot_tables/blocks/green_candle_cake.json
- minecraft/loot_tables/blocks/green_candle.json
- minecraft/loot_tables/blocks/large_amethyst_bud.json
- minecraft/loot_tables/blocks/lava_cauldron.json
- minecraft/loot_tables/blocks/light_blue_candle_cake.json
- minecraft/loot_tables/blocks/light_blue_candle.json
- minecraft/loot_tables/blocks/light_gray_candle_cake.json
- minecraft/loot_tables/blocks/light_gray_candle.json
- minecraft/loot_tables/blocks/lightly_weathered_copper_block.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper.json
- minecraft/loot_tables/blocks/lightning_rod.json
- minecraft/loot_tables/blocks/lime_candle_cake.json
- minecraft/loot_tables/blocks/lime_candle.json
- minecraft/loot_tables/blocks/magenta_candle_cake.json
- minecraft/loot_tables/blocks/magenta_candle.json
- minecraft/loot_tables/blocks/medium_amethyst_bud.json
- minecraft/loot_tables/blocks/orange_candle_cake.json
- minecraft/loot_tables/blocks/orange_candle.json
- minecraft/loot_tables/blocks/pink_candle_cake.json
- minecraft/loot_tables/blocks/pink_candle.json
- minecraft/loot_tables/blocks/pointed_dripstone.json
- minecraft/loot_tables/blocks/powder_snow_cauldron.json
- minecraft/loot_tables/blocks/powder_snow.json
- minecraft/loot_tables/blocks/purple_candle_cake.json
- minecraft/loot_tables/blocks/purple_candle.json
- minecraft/loot_tables/blocks/red_candle_cake.json
- minecraft/loot_tables/blocks/red_candle.json
- minecraft/loot_tables/blocks/sculk_sensor.json
- minecraft/loot_tables/blocks/semi_weathered_copper_block.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper.json
- minecraft/loot_tables/blocks/small_amethyst_bud.json
- minecraft/loot_tables/blocks/tinted_glass.json
- minecraft/loot_tables/blocks/tuff.json
- minecraft/loot_tables/blocks/water_cauldron.json
- minecraft/loot_tables/blocks/waxed_copper.json
- minecraft/loot_tables/blocks/waxed_cut_copper_slab.json
- minecraft/loot_tables/blocks/waxed_cut_copper_stairs.json
- minecraft/loot_tables/blocks/waxed_cut_copper.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_copper.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_copper.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper.json
- minecraft/loot_tables/blocks/weathered_copper_block.json
- minecraft/loot_tables/blocks/weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/weathered_cut_copper.json
- minecraft/loot_tables/blocks/white_candle_cake.json
- minecraft/loot_tables/blocks/white_candle.json
- minecraft/loot_tables/blocks/yellow_candle_cake.json
- minecraft/loot_tables/blocks/yellow_candle.json
- minecraft/loot_tables/entities/axolotl.json
- minecraft/recipes/amethyst_block.json
- minecraft/recipes/black_candle.json
- minecraft/recipes/blue_candle.json
- minecraft/recipes/brown_candle.json
- minecraft/recipes/bundle.json
- minecraft/recipes/candle.json
- minecraft/recipes/copper_block.json
- minecraft/recipes/copper_ingot_from_blasting.json
- minecraft/recipes/copper_ingot_from_copper_block.json
- minecraft/recipes/copper_ingot.json
- minecraft/recipes/cut_copper_slab.json
- minecraft/recipes/cut_copper_stairs.json
- minecraft/recipes/cut_copper.json
- minecraft/recipes/cyan_candle.json
- minecraft/recipes/firework_rocket_simple.json
- minecraft/recipes/gray_candle.json
- minecraft/recipes/green_candle.json
- minecraft/recipes/light_blue_candle.json
- minecraft/recipes/light_gray_candle.json
- minecraft/recipes/lightly_weathered_cut_copper_slab.json
- minecraft/recipes/lightly_weathered_cut_copper_stairs.json
- minecraft/recipes/lightly_weathered_cut_copper.json
- minecraft/recipes/lightning_rod.json
- minecraft/recipes/lime_candle.json
- minecraft/recipes/magenta_candle.json
- minecraft/recipes/orange_candle.json
- minecraft/recipes/pink_candle.json
- minecraft/recipes/purple_candle.json
- minecraft/recipes/red_candle.json
- minecraft/recipes/semi_weathered_cut_copper_slab.json
- minecraft/recipes/semi_weathered_cut_copper_stairs.json
- minecraft/recipes/semi_weathered_cut_copper.json
- minecraft/recipes/spyglass.json
- minecraft/recipes/tinted_glass.json
- minecraft/recipes/waxed_copper_cut_slab_from_honeycomb.json
- minecraft/recipes/waxed_copper_cut_stairs_from_honeycomb.json
- minecraft/recipes/waxed_copper.json
- minecraft/recipes/waxed_cut_copper_from_honeycomb.json
- minecraft/recipes/waxed_cut_copper_from_waxed_block.json
- minecraft/recipes/waxed_cut_copper_slab.json
- minecraft/recipes/waxed_cut_copper_stairs.json
- minecraft/recipes/waxed_lightly_weathered_copper.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_from_waxed_block.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/recipes/waxed_semi_weathered_copper.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_from_waxed_block.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_slab.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/recipes/weathered_cut_copper_slab.json
- minecraft/recipes/weathered_cut_copper_stairs.json
- minecraft/recipes/weathered_cut_copper.json
- minecraft/recipes/white_candle.json
- minecraft/recipes/yellow_candle.json
- minecraft/tags/blocks/candle_cakes.json
- minecraft/tags/blocks/candles.json
- minecraft/tags/blocks/cauldrons.json
- minecraft/tags/blocks/crystal_sound_blocks.json
- minecraft/tags/blocks/dripstone_replaceable_blocks.json
- minecraft/tags/blocks/inside_step_sound_blocks.json
- minecraft/tags/blocks/occludes_vibration_signals.json
- minecraft/tags/entity_types/axolotl_always_hostiles.json
- minecraft/tags/entity_types/axolotl_tempted_hostiles.json
- minecraft/tags/entity_types/powder_snow_walkable_mobs.json
- minecraft/tags/game_events/ignore_vibrations_stepping_carefully.json
- minecraft/tags/game_events/vibrations.json
- minecraft/tags/items/axolotl_tempt_items.json
- minecraft/tags/items/candles.json
- minecraft/tags/items/freeze_immune_wearables.json
- minecraft/tags/items/ignored_by_piglin_babies.json
- minecraft/tags/items/occludes_vibration_signals.json
- minecraft/tags/items/piglin_food.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/amethyst_block.json
- minecraft/blockstates/amethyst_cluster.json
- minecraft/blockstates/black_candle_cake.json
- minecraft/blockstates/black_candle.json
- minecraft/blockstates/blue_candle_cake.json
- minecraft/blockstates/blue_candle.json
- minecraft/blockstates/brown_candle_cake.json
- minecraft/blockstates/brown_candle.json
- minecraft/blockstates/budding_amethyst.json
- minecraft/blockstates/calcite.json
- minecraft/blockstates/candle_cake.json
- minecraft/blockstates/candle.json
- minecraft/blockstates/copper_block.json
- minecraft/blockstates/copper_ore.json
- minecraft/blockstates/cut_copper_slab.json
- minecraft/blockstates/cut_copper_stairs.json
- minecraft/blockstates/cut_copper.json
- minecraft/blockstates/cyan_candle_cake.json
- minecraft/blockstates/cyan_candle.json
- minecraft/blockstates/dirt_path.json
- minecraft/blockstates/dripstone_block.json
+ minecraft/blockstates/grass_path.json
- minecraft/blockstates/gray_candle_cake.json
- minecraft/blockstates/gray_candle.json
- minecraft/blockstates/green_candle_cake.json
- minecraft/blockstates/green_candle.json
- minecraft/blockstates/large_amethyst_bud.json
- minecraft/blockstates/lava_cauldron.json
- minecraft/blockstates/light_blue_candle_cake.json
- minecraft/blockstates/light_blue_candle.json
- minecraft/blockstates/light_gray_candle_cake.json
- minecraft/blockstates/light_gray_candle.json
- minecraft/blockstates/lightly_weathered_copper_block.json
- minecraft/blockstates/lightly_weathered_cut_copper_slab.json
- minecraft/blockstates/lightly_weathered_cut_copper_stairs.json
- minecraft/blockstates/lightly_weathered_cut_copper.json
- minecraft/blockstates/lightning_rod.json
- minecraft/blockstates/lime_candle_cake.json
- minecraft/blockstates/lime_candle.json
- minecraft/blockstates/magenta_candle_cake.json
- minecraft/blockstates/magenta_candle.json
- minecraft/blockstates/medium_amethyst_bud.json
- minecraft/blockstates/orange_candle_cake.json
- minecraft/blockstates/orange_candle.json
- minecraft/blockstates/pink_candle_cake.json
- minecraft/blockstates/pink_candle.json
- minecraft/blockstates/pointed_dripstone.json
- minecraft/blockstates/powder_snow_cauldron.json
- minecraft/blockstates/powder_snow.json
- minecraft/blockstates/purple_candle_cake.json
- minecraft/blockstates/purple_candle.json
- minecraft/blockstates/red_candle_cake.json
- minecraft/blockstates/red_candle.json
- minecraft/blockstates/sculk_sensor.json
- minecraft/blockstates/semi_weathered_copper_block.json
- minecraft/blockstates/semi_weathered_cut_copper_slab.json
- minecraft/blockstates/semi_weathered_cut_copper_stairs.json
- minecraft/blockstates/semi_weathered_cut_copper.json
- minecraft/blockstates/small_amethyst_bud.json
- minecraft/blockstates/tinted_glass.json
- minecraft/blockstates/tuff.json
- minecraft/blockstates/water_cauldron.json
- minecraft/blockstates/waxed_copper.json
- minecraft/blockstates/waxed_cut_copper_slab.json
- minecraft/blockstates/waxed_cut_copper_stairs.json
- minecraft/blockstates/waxed_cut_copper.json
- minecraft/blockstates/waxed_lightly_weathered_copper.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper.json
- minecraft/blockstates/waxed_semi_weathered_copper.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper_slab.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper.json
- minecraft/blockstates/weathered_copper_block.json
- minecraft/blockstates/weathered_cut_copper_slab.json
- minecraft/blockstates/weathered_cut_copper_stairs.json
- minecraft/blockstates/weathered_cut_copper.json
- minecraft/blockstates/white_candle_cake.json
- minecraft/blockstates/white_candle.json
- minecraft/blockstates/yellow_candle_cake.json
- minecraft/blockstates/yellow_candle.json
- minecraft/models/block/amethyst_block.json
- minecraft/models/block/amethyst_cluster.json
- minecraft/models/block/black_candle_cake.json
- minecraft/models/block/black_candle_four_candles.json
- minecraft/models/block/black_candle_one_candle.json
- minecraft/models/block/black_candle_three_candles.json
- minecraft/models/block/black_candle_two_candles.json
- minecraft/models/block/blue_candle_cake.json
- minecraft/models/block/blue_candle_four_candles.json
- minecraft/models/block/blue_candle_one_candle.json
- minecraft/models/block/blue_candle_three_candles.json
- minecraft/models/block/blue_candle_two_candles.json
- minecraft/models/block/brown_candle_cake.json
- minecraft/models/block/brown_candle_four_candles.json
- minecraft/models/block/brown_candle_one_candle.json
- minecraft/models/block/brown_candle_three_candles.json
- minecraft/models/block/brown_candle_two_candles.json
- minecraft/models/block/budding_amethyst.json
- minecraft/models/block/calcite.json
- minecraft/models/block/candle_cake.json
- minecraft/models/block/candle_four_candles.json
- minecraft/models/block/candle_one_candle.json
- minecraft/models/block/candle_three_candles.json
- minecraft/models/block/candle_two_candles.json
+ minecraft/models/block/cauldron_level1.json
+ minecraft/models/block/cauldron_level2.json
+ minecraft/models/block/cauldron_level3.json
- minecraft/models/block/copper_block.json
- minecraft/models/block/copper_ore.json
- minecraft/models/block/cut_copper_slab_top.json
- minecraft/models/block/cut_copper_slab.json
- minecraft/models/block/cut_copper_stairs_inner.json
- minecraft/models/block/cut_copper_stairs_outer.json
- minecraft/models/block/cut_copper_stairs.json
- minecraft/models/block/cut_copper.json
- minecraft/models/block/cyan_candle_cake.json
- minecraft/models/block/cyan_candle_four_candles.json
- minecraft/models/block/cyan_candle_one_candle.json
- minecraft/models/block/cyan_candle_three_candles.json
- minecraft/models/block/cyan_candle_two_candles.json
- minecraft/models/block/dirt_path.json
- minecraft/models/block/dripstone_block.json
+ minecraft/models/block/grass_path.json
- minecraft/models/block/gray_candle_cake.json
- minecraft/models/block/gray_candle_four_candles.json
- minecraft/models/block/gray_candle_one_candle.json
- minecraft/models/block/gray_candle_three_candles.json
- minecraft/models/block/gray_candle_two_candles.json
- minecraft/models/block/green_candle_cake.json
- minecraft/models/block/green_candle_four_candles.json
- minecraft/models/block/green_candle_one_candle.json
- minecraft/models/block/green_candle_three_candles.json
- minecraft/models/block/green_candle_two_candles.json
- minecraft/models/block/large_amethyst_bud.json
- minecraft/models/block/lava_cauldron.json
- minecraft/models/block/light_blue_candle_cake.json
- minecraft/models/block/light_blue_candle_four_candles.json
- minecraft/models/block/light_blue_candle_one_candle.json
- minecraft/models/block/light_blue_candle_three_candles.json
- minecraft/models/block/light_blue_candle_two_candles.json
- minecraft/models/block/light_gray_candle_cake.json
- minecraft/models/block/light_gray_candle_four_candles.json
- minecraft/models/block/light_gray_candle_one_candle.json
- minecraft/models/block/light_gray_candle_three_candles.json
- minecraft/models/block/light_gray_candle_two_candles.json
- minecraft/models/block/lightly_weathered_copper_block.json
- minecraft/models/block/lightly_weathered_cut_copper_slab_top.json
- minecraft/models/block/lightly_weathered_cut_copper_slab.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs_inner.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs_outer.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs.json
- minecraft/models/block/lightly_weathered_cut_copper.json
- minecraft/models/block/lightning_rod.json
- minecraft/models/block/lime_candle_cake.json
- minecraft/models/block/lime_candle_four_candles.json
- minecraft/models/block/lime_candle_one_candle.json
- minecraft/models/block/lime_candle_three_candles.json
- minecraft/models/block/lime_candle_two_candles.json
- minecraft/models/block/magenta_candle_cake.json
- minecraft/models/block/magenta_candle_four_candles.json
- minecraft/models/block/magenta_candle_one_candle.json
- minecraft/models/block/magenta_candle_three_candles.json
- minecraft/models/block/magenta_candle_two_candles.json
- minecraft/models/block/medium_amethyst_bud.json
- minecraft/models/block/orange_candle_cake.json
- minecraft/models/block/orange_candle_four_candles.json
- minecraft/models/block/orange_candle_one_candle.json
- minecraft/models/block/orange_candle_three_candles.json
- minecraft/models/block/orange_candle_two_candles.json
- minecraft/models/block/pink_candle_cake.json
- minecraft/models/block/pink_candle_four_candles.json
- minecraft/models/block/pink_candle_one_candle.json
- minecraft/models/block/pink_candle_three_candles.json
- minecraft/models/block/pink_candle_two_candles.json
- minecraft/models/block/pointed_dripstone_down_base.json
- minecraft/models/block/pointed_dripstone_down_frustum.json
- minecraft/models/block/pointed_dripstone_down_middle.json
- minecraft/models/block/pointed_dripstone_down_tip_merge.json
- minecraft/models/block/pointed_dripstone_down_tip.json
- minecraft/models/block/pointed_dripstone_up_base.json
- minecraft/models/block/pointed_dripstone_up_frustum.json
- minecraft/models/block/pointed_dripstone_up_middle.json
- minecraft/models/block/pointed_dripstone_up_tip_merge.json
- minecraft/models/block/pointed_dripstone_up_tip.json
- minecraft/models/block/pointed_dripstone.json
- minecraft/models/block/powder_snow_cauldron_full.json
- minecraft/models/block/powder_snow_cauldron_level1.json
- minecraft/models/block/powder_snow_cauldron_level2.json
- minecraft/models/block/powder_snow.json
- minecraft/models/block/purple_candle_cake.json
- minecraft/models/block/purple_candle_four_candles.json
- minecraft/models/block/purple_candle_one_candle.json
- minecraft/models/block/purple_candle_three_candles.json
- minecraft/models/block/purple_candle_two_candles.json
- minecraft/models/block/red_candle_cake.json
- minecraft/models/block/red_candle_four_candles.json
- minecraft/models/block/red_candle_one_candle.json
- minecraft/models/block/red_candle_three_candles.json
- minecraft/models/block/red_candle_two_candles.json
- minecraft/models/block/sculk_sensor_active.json
- minecraft/models/block/sculk_sensor_inactive.json
- minecraft/models/block/sculk_sensor.json
- minecraft/models/block/semi_weathered_copper_block.json
- minecraft/models/block/semi_weathered_cut_copper_slab_top.json
- minecraft/models/block/semi_weathered_cut_copper_slab.json
- minecraft/models/block/semi_weathered_cut_copper_stairs_inner.json
- minecraft/models/block/semi_weathered_cut_copper_stairs_outer.json
- minecraft/models/block/semi_weathered_cut_copper_stairs.json
- minecraft/models/block/semi_weathered_cut_copper.json
- minecraft/models/block/small_amethyst_bud.json
- minecraft/models/block/template_cake_with_candle.json
- minecraft/models/block/template_candle.json
- minecraft/models/block/template_cauldron_full.json
- minecraft/models/block/template_cauldron_level1.json
- minecraft/models/block/template_cauldron_level2.json
- minecraft/models/block/template_four_candles.json
- minecraft/models/block/template_three_candles.json
- minecraft/models/block/template_two_candles.json
- minecraft/models/block/tinted_glass.json
- minecraft/models/block/tuff.json
- minecraft/models/block/water_cauldron_full.json
- minecraft/models/block/water_cauldron_level1.json
- minecraft/models/block/water_cauldron_level2.json
- minecraft/models/block/weathered_copper_block.json
- minecraft/models/block/weathered_cut_copper_slab_top.json
- minecraft/models/block/weathered_cut_copper_slab.json
- minecraft/models/block/weathered_cut_copper_stairs_inner.json
- minecraft/models/block/weathered_cut_copper_stairs_outer.json
- minecraft/models/block/weathered_cut_copper_stairs.json
- minecraft/models/block/weathered_cut_copper.json
- minecraft/models/block/white_candle_cake.json
- minecraft/models/block/white_candle_four_candles.json
- minecraft/models/block/white_candle_one_candle.json
- minecraft/models/block/white_candle_three_candles.json
- minecraft/models/block/white_candle_two_candles.json
- minecraft/models/block/yellow_candle_cake.json
- minecraft/models/block/yellow_candle_four_candles.json
- minecraft/models/block/yellow_candle_one_candle.json
- minecraft/models/block/yellow_candle_three_candles.json
- minecraft/models/block/yellow_candle_two_candles.json
- minecraft/models/item/amethyst_block.json
- minecraft/models/item/amethyst_cluster.json
- minecraft/models/item/amethyst_shard.json
- minecraft/models/item/axolotl_bucket.json
- minecraft/models/item/axolotl_spawn_egg.json
- minecraft/models/item/black_candle.json
- minecraft/models/item/blue_candle.json
- minecraft/models/item/brown_candle.json
- minecraft/models/item/budding_amethyst.json
- minecraft/models/item/bundle_filled.json
- minecraft/models/item/bundle.json
- minecraft/models/item/calcite.json
- minecraft/models/item/candle.json
- minecraft/models/item/copper_block.json
- minecraft/models/item/copper_ingot.json
- minecraft/models/item/copper_ore.json
- minecraft/models/item/cut_copper_slab.json
- minecraft/models/item/cut_copper_stairs.json
- minecraft/models/item/cut_copper.json
- minecraft/models/item/cyan_candle.json
- minecraft/models/item/dirt_path.json
- minecraft/models/item/dripstone_block.json
+ minecraft/models/item/grass_path.json
- minecraft/models/item/gray_candle.json
- minecraft/models/item/green_candle.json
- minecraft/models/item/large_amethyst_bud.json
- minecraft/models/item/light_blue_candle.json
- minecraft/models/item/light_gray_candle.json
- minecraft/models/item/lightly_weathered_copper_block.json
- minecraft/models/item/lightly_weathered_cut_copper_slab.json
- minecraft/models/item/lightly_weathered_cut_copper_stairs.json
- minecraft/models/item/lightly_weathered_cut_copper.json
- minecraft/models/item/lightning_rod.json
- minecraft/models/item/lime_candle.json
- minecraft/models/item/magenta_candle.json
- minecraft/models/item/medium_amethyst_bud.json
- minecraft/models/item/orange_candle.json
- minecraft/models/item/pink_candle.json
- minecraft/models/item/pointed_dripstone.json
- minecraft/models/item/powder_snow_bucket.json
- minecraft/models/item/purple_candle.json
- minecraft/models/item/red_candle.json
- minecraft/models/item/sculk_sensor.json
- minecraft/models/item/semi_weathered_copper_block.json
- minecraft/models/item/semi_weathered_cut_copper_slab.json
- minecraft/models/item/semi_weathered_cut_copper_stairs.json
- minecraft/models/item/semi_weathered_cut_copper.json
- minecraft/models/item/small_amethyst_bud.json
- minecraft/models/item/spyglass.json
- minecraft/models/item/tinted_glass.json
- minecraft/models/item/tuff.json
- minecraft/models/item/waxed_copper.json
- minecraft/models/item/waxed_cut_copper_slab.json
- minecraft/models/item/waxed_cut_copper_stairs.json
- minecraft/models/item/waxed_cut_copper.json
- minecraft/models/item/waxed_lightly_weathered_copper.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper.json
- minecraft/models/item/waxed_semi_weathered_copper.json
- minecraft/models/item/waxed_semi_weathered_cut_copper_slab.json
- minecraft/models/item/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/models/item/waxed_semi_weathered_cut_copper.json
- minecraft/models/item/weathered_copper_block.json
- minecraft/models/item/weathered_cut_copper_slab.json
- minecraft/models/item/weathered_cut_copper_stairs.json
- minecraft/models/item/weathered_cut_copper.json
- minecraft/models/item/white_candle.json
- minecraft/models/item/yellow_candle.json
- minecraft/particles/dripping_dripstone_lava.json
- minecraft/particles/dripping_dripstone_water.json
- minecraft/particles/dust_color_transition.json
- minecraft/particles/falling_dripstone_lava.json
- minecraft/particles/falling_dripstone_water.json
- minecraft/particles/small_flame.json
- minecraft/particles/snowflake.json
- minecraft/particles/vibration.json
- minecraft/textures/block/amethyst_block.png
- minecraft/textures/block/amethyst_cluster.png
- minecraft/textures/block/black_candle.png
- minecraft/textures/block/blue_candle.png
- minecraft/textures/block/brown_candle.png
- minecraft/textures/block/budding_amethyst.png
- minecraft/textures/block/calcite.png
- minecraft/textures/block/calibrated_sculk_sensor_side.png
- minecraft/textures/block/calibrated_sculk_sensor_top.png
- minecraft/textures/block/candle.png
- minecraft/textures/block/copper_block.png
- minecraft/textures/block/copper_ore.png
- minecraft/textures/block/cut_copper.png
- minecraft/textures/block/cyan_candle.png
- minecraft/textures/block/dirt_path_side.png
- minecraft/textures/block/dirt_path_top.png
- minecraft/textures/block/dripstone_block.png
+ minecraft/textures/block/grass_path_side.png
+ minecraft/textures/block/grass_path_top.png
- minecraft/textures/block/gray_candle.png
- minecraft/textures/block/green_candle.png
- minecraft/textures/block/large_amethyst_bud.png
- minecraft/textures/block/light_blue_candle.png
- minecraft/textures/block/light_gray_candle.png
- minecraft/textures/block/lightly_weathered_copper_block.png
- minecraft/textures/block/lightly_weathered_cut_copper.png
- minecraft/textures/block/lightning_rod.png
- minecraft/textures/block/lime_candle.png
- minecraft/textures/block/magenta_candle.png
- minecraft/textures/block/medium_amethyst_bud.png
- minecraft/textures/block/orange_candle.png
- minecraft/textures/block/pink_candle.png
- minecraft/textures/block/pointed_dripstone_down_base.png
- minecraft/textures/block/pointed_dripstone_down_frustum.png
- minecraft/textures/block/pointed_dripstone_down_middle.png
- minecraft/textures/block/pointed_dripstone_down_tip_merge.png
- minecraft/textures/block/pointed_dripstone_down_tip.png
- minecraft/textures/block/pointed_dripstone_up_base.png
- minecraft/textures/block/pointed_dripstone_up_frustum.png
- minecraft/textures/block/pointed_dripstone_up_middle.png
- minecraft/textures/block/pointed_dripstone_up_tip_merge.png
- minecraft/textures/block/pointed_dripstone_up_tip.png
- minecraft/textures/block/powder_snow.png
- minecraft/textures/block/purple_candle.png
- minecraft/textures/block/red_candle.png
- minecraft/textures/block/sculk_sensor_bottom.png
- minecraft/textures/block/sculk_sensor_side.png
- minecraft/textures/block/sculk_sensor_tendril_active.png
- minecraft/textures/block/sculk_sensor_tendril_active.png.mcmeta
- minecraft/textures/block/sculk_sensor_tendril_inactive.png
- minecraft/textures/block/sculk_sensor_tendril_inactive.png.mcmeta
- minecraft/textures/block/sculk_sensor_top.png
- minecraft/textures/block/semi_weathered_copper_block.png
- minecraft/textures/block/semi_weathered_cut_copper.png
- minecraft/textures/block/small_amethyst_bud.png
- minecraft/textures/block/tinted_glass.png
- minecraft/textures/block/tuff.png
- minecraft/textures/block/weathered_copper_block.png
- minecraft/textures/block/weathered_cut_copper.png
- minecraft/textures/block/white_candle.png
- minecraft/textures/block/yellow_candle.png
- minecraft/textures/entity/axolotl/axolotl_blue.png
- minecraft/textures/entity/axolotl/axolotl_cyan.png
- minecraft/textures/entity/axolotl/axolotl_gold.png
- minecraft/textures/entity/axolotl/axolotl_lucy.png
- minecraft/textures/entity/axolotl/axolotl_wild.png
- minecraft/textures/gui/container/bundle.png
- minecraft/textures/item/amethyst_shard.png
- minecraft/textures/item/axolotl_bucket.png
- minecraft/textures/item/black_candle.png
- minecraft/textures/item/blue_candle.png
- minecraft/textures/item/brown_candle.png
- minecraft/textures/item/bundle_filled.png
- minecraft/textures/item/bundle.png
- minecraft/textures/item/candle.png
- minecraft/textures/item/copper_ingot.png
- minecraft/textures/item/cyan_candle.png
- minecraft/textures/item/gray_candle.png
- minecraft/textures/item/green_candle.png
- minecraft/textures/item/light_blue_candle.png
- minecraft/textures/item/light_gray_candle.png
- minecraft/textures/item/lime_candle.png
- minecraft/textures/item/magenta_candle.png
- minecraft/textures/item/orange_candle.png
- minecraft/textures/item/pink_candle.png
- minecraft/textures/item/pointed_dripstone.png
- minecraft/textures/item/powder_snow_bucket.png
- minecraft/textures/item/purple_candle.png
- minecraft/textures/item/red_candle.png
- minecraft/textures/item/spyglass.png
- minecraft/textures/item/white_candle.png
- minecraft/textures/item/yellow_candle.png
- minecraft/textures/misc/powder_snow_outline.png
- minecraft/textures/misc/spyglass_scope.png
- minecraft/textures/particle/vibration.png
- minecraft/textures/particle/vibration.png.mcmeta
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
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
+ XXX.ai.behavior.RandomSwim
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunIf
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.RunSometimes
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.control.DolphinLookControl
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
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
- XXX.ai.goal.MoveIndoorsGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.package-info
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.PlayGoal
+ XXX.ai.goal.RandomLookAroundGoal
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
- XXX.ai.goal.TakeFlowerGoal
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$1
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
+ XXX.ai.memory.package-info
- XXX.ai.memory.WalkTarget
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
+ XXX.ai.util.AirRandomPos
+ XXX.ai.util.GoalUtils
+ XXX.ai.util.LandRandomPos
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.animal.axolotl.Axolotl
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
+ XXX.animal.axolotl.Axolotl$AxolotlPathNavigation
+ XXX.animal.axolotl.AxolotlAi
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.Donkey
- XXX.animal.horse.Horse
+ XXX.animal.horse.Horse$HorseGroupData
- XXX.animal.horse.Llama
+ XXX.animal.horse.Llama$1
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Markings
- XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.Variant
- XXX.animal.horse.ZombieHorse
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$1
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
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
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ItemPredicate
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateArgument$TagPredicate
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
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
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.OldChunkStorage$1
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
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
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.ScoreHolderArgument$Serializer
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TimeArgument
- XXX.commands.arguments.UuidArgument
+ XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.HusbandryAdvancements
- XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.package-info
+ XXX.data.advancements.StoryAdvancements
- XXX.data.advancements.TheEndAdvancements
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLoot
+ XXX.data.loot.ChestLoot
- XXX.data.loot.EntityLoot
+ XXX.data.loot.FishingLoot
- XXX.data.loot.GiftLoot
+ XXX.data.loot.LootTableProvider
+ XXX.data.loot.package-info
- XXX.data.loot.PiglinBarterLoot
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.recipes.UpgradeRecipeBuilder
- XXX.data.recipes.UpgradeRecipeBuilder$Result
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1
- XXX.data.tags.TagsProvider$TagAppender
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.Features
- XXX.data.worldgen.Features$Configs
+ XXX.data.worldgen.Features$Decorators
- XXX.data.worldgen.Features$States
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.StructureFeatures
- XXX.data.worldgen.SurfaceBuilders
+ XXX.data.worldgen.TaigaVillagePools
- XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedBlockEntityInjecter
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehivePoiRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
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
+ XXX.datafix.schemas.V2686
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
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
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$1
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
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.IronGolem$Crackiness
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
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$1
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$1
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$1
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTemptGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.Motive
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
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
+ XXX.entity.monster.Evoker$1
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
- XXX.entity.monster.Illusioner$1
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
- XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$1
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
+ XXX.entity.monster.Ravager$1
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$1
+ XXX.entity.monster.Shulker$ShulkerAttackGoal
- XXX.entity.monster.Shulker$ShulkerBodyRotationControl
+ XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
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
- XXX.entity.monster.Strider$1
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
+ XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
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
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
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
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
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
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
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
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NoiseDependantDecoratorConfiguration
- XXX.feature.configurations.NoneDecoratorConfiguration
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OceanRuinConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration$1
- XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ XXX.feature.configurations.RangeDecoratorConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RuinedPortalConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.foliageplacers.FoliagePlacer$Factory
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ XXX.gametest.framework.AfterBatch
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
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.ReportGameListener
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
+ XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.Potions
+ XXX.item.alchemy.PotionUtils
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$1
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
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
+ XXX.item.crafting.SimpleRecipeSerializer
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.SuspiciousStewRecipe
+ XXX.item.crafting.TippedArrowRecipe
- XXX.item.crafting.UpgradeRecipe
+ XXX.item.crafting.UpgradeRecipe$Serializer
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
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.ProtectionEnchantment
- XXX.item.enchantment.ProtectionEnchantment$Type
+ XXX.item.enchantment.QuickChargeEnchantment
- XXX.item.enchantment.SoulSpeedEnchantment
+ XXX.item.enchantment.SweepingEdgeEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
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
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$ClimateParameters
+ XXX.level.biome.Biome$ClimateSettings
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$TemperatureModifier
- XXX.level.biome.Biome$TemperatureModifier$1
+ XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeGenerationSettings
+ XXX.level.biome.BiomeGenerationSettings$1
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$1
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.CheckerboardColumnBiomeSource
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$1
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSource$1
- XXX.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ XXX.level.biome.MultiNoiseBiomeSource$Preset
- XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
+ XXX.level.biome.NearestNeighborBiomeZoomer
- XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.package-info
+ XXX.level.biome.TheEndBiomeSource
+ XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCauldronBlock
- XXX.level.block.AbstractChestBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock$1
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChainBlock
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.ChangeOverTimeSlabBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.GameMasterBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GrassBlock
- XXX.level.block.Lantern
+ XXX.level.block.LanternBlock
+ XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
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
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PowderSnowBlock
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
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlant
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlant
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
+ XXX.level.entity.EntityAccess
+ XXX.level.entity.EntityInLevelCallback$1
+ XXX.level.entity.EntityPersistentStorage
+ XXX.level.entity.EntitySectionStorage
+ XXX.level.entity.EntityTypeTest
+ XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.PersistentEntitySectionManager$1
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager$1
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EuclideanGameEventDispatcher
+ XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
+ XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseSamplingSettings
+ XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.NoiseSlideSettings
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.StructureSettings
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldGenSettings
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.FlatDataLayer
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
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SaveDataDirtyRunnable
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$1
+ XXX.level.storage.package-info
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$1
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BaseDiskFeature
- XXX.levelgen.feature.BastionFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$1
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.SimulatedFeature
+ XXX.levelgen.feature.SmallDripstoneFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.BaseHeightmapDecorator
- XXX.levelgen.placement.BiasedRangeDecorator
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
+ XXX.levelgen.placement.ChanceDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountNoiseDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratedDecorator
+ XXX.levelgen.placement.DecoratedDecoratorConfiguration
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.DepthAverageDecorator
+ XXX.levelgen.placement.EdgeDecorator
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
+ XXX.levelgen.placement.HeightmapDoubleDecorator
+ XXX.levelgen.placement.HeightMapWorldSurfaceDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.NoiseBasedDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecorator
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.Spread32Decorator
+ XXX.levelgen.placement.SquareDecorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.VeryBiasedRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.NetherFossilFeature
- XXX.levelgen.structure.NetherFossilFeature$FeatureStart
+ XXX.levelgen.structure.NetherFossilPieces
- XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.RuinedPortalPiece
- XXX.levelgen.structure.RuinedPortalPiece$Properties
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ XXX.levelgen.structure.StrongholdPieces
- XXX.levelgen.structure.StrongholdPieces$1
+ XXX.levelgen.structure.StrongholdPieces$2
- XXX.levelgen.structure.StrongholdPieces$3
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
- XXX.levelgen.structure.StrongholdPieces$FillerCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
- XXX.levelgen.structure.StrongholdPieces$LeftTurn
+ XXX.levelgen.structure.StrongholdPieces$Library
- XXX.levelgen.structure.StrongholdPieces$PieceWeight
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
- XXX.levelgen.structure.StrongholdPieces$PrisonHall
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
- XXX.levelgen.structure.StrongholdPieces$RoomCrossing
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- XXX.levelgen.structure.StrongholdPieces$StairsDown
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
- XXX.levelgen.structure.StrongholdPieces$Straight
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$1
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$1
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
- XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction$1
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$1
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$1
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$1
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$1
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$1
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$1
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$1
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$1
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$1
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$1
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition$1
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryData
+ XXX.minecraft.core.RegistryAccess$RegistryHolder
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableUUID
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.BuiltinRegistries
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
- XXX.minecraft.obfuscate.KeepAfterObfuscation
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerResources
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.TickTask
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.SerializationTags
- XXX.minecraft.tags.SetTag
+ XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$1
+ XXX.minecraft.tags.StaticTagHelper$Wrapper
- XXX.minecraft.tags.StaticTags
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$1
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagCollection$NetworkPayload
+ XXX.minecraft.tags.TagContainer$CollectionConsumer
+ XXX.minecraft.tags.TagManager$LoaderInfo
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.IntRange
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LimitedCapacityList
+ XXX.minecraft.util.UniformInt
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
- XXX.minecraft.world.package-info
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$1
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$1
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
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
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
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
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
- XXX.phys.shapes.IntPointRange
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.GlowstoneDecorator
+ XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockBreakAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$1
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerAckPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
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
- XXX.protocol.game.ClientboundPlayerCombatPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket$1
- XXX.protocol.game.ClientboundPlayerCombatPacket$Event
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetBorderPacket
- XXX.protocol.game.ClientboundSetBorderPacket$1
+ XXX.protocol.game.ClientboundSetBorderPacket$Type
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
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesPacket
- XXX.protocol.game.ClientboundSetTitlesPacket$Type
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerAckPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
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
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$DefaultSerializer
+ XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue$1
+ XXX.providers.number.ConstantValue$Serializer
+ XXX.providers.number.NumberProvider
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator$1
+ XXX.providers.score.ContextScoreboardNameProvider$1
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider$1
+ XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.ScoreboardNameProviders
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$1
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$1
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
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
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.SeedCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$1
- XXX.server.level.FeatureSimulator
- XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$1
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.WorldGenRegion
+ XXX.server.level.WorldGenTickList
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
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
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.package-info
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.IntLimiter
- XXX.storage.loot.IntLimiter$Serializer
+ XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$Serializer
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
+ XXX.storage.loot.package-info
- XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomValueBounds
- XXX.storage.threaded.package-info
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructureManager
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
- XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
- XXX.world.entity.AgableMob
+ XXX.world.entity.AgeableMob
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.package-info
+ XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$3
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
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
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
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
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$11
- XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$2
- XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$4
- XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$6
- XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$8
- XXX.world.item.CreativeModeTab$9
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$1
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.package-info
- XXX.world.item.ProjectileWeaponItem$Type
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
+ XXX.world.item.SnowballItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.item.WaterLilyBlockItem
+ XXX.world.item.Wearable
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ChunkTickList
+ XXX.world.level.ChunkTickList$1
- XXX.world.level.ChunkTickList$ScheduledTick
+ XXX.world.level.ClipBlockStateContext
+ XXX.world.level.LevelHeightAccessor
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.ServerTickList
+ XXX.world.level.SpawnData
- XXX.world.level.StructureFeatureManager
+ XXX.world.level.TickList
- XXX.world.level.TickNextTickData
+ XXX.world.level.TickPriority
- XXX.world.level.WorldGenLevel
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
+ XXX.worldgen.biome.BiomeReport
- XXX.worldgen.biome.Biomes
- XXX.worldgen.biome.package-info
+ XXX.worldgen.biome.VanillaBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.DetectedVersion +1M -1M | +1P -2P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger +2M -2M
```
```
XXX.advancements.critereon.BlockPredicate -2M
```
```
XXX.advancements.critereon.BredAnimalsTrigger +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.advancements.critereon.FluidPredicate -2M
```
```
XXX.advancements.critereon.ItemPredicate -2M
```
```
XXX.minecraft.commands.CommandFunction$Entry +1P -1P
```
```
XXX.minecraft.core.BlockMath +2P -2P
```
```
XXX.minecraft.core.BlockSource +1P
```
```
XXX.minecraft.core.Direction -1M
```
```
XXX.minecraft.core.Direction8 +1M | +8P
```
```
XXX.core.particles.DustParticleOptions +11M -3M | +4P -1P
```
```
XXX.data.structures.StructureUpdater -1M
```
```
XXX.minecraft.nbt.ByteArrayTag +1M -1M
```
```
XXX.minecraft.nbt.ByteTag +2M -1M
```
```
XXX.minecraft.nbt.CompoundTag +4M -1M | +2P
```
```
XXX.minecraft.nbt.DoubleTag +2M -1M
```
```
XXX.minecraft.nbt.EndTag +1M -1M
```
```
XXX.minecraft.nbt.FloatTag +2M -1M
```
```
XXX.minecraft.nbt.IntArrayTag +1M -1M
```
```
XXX.minecraft.nbt.IntTag +2M -1M
```
```
XXX.minecraft.nbt.NbtUtils -20M | -4P
```
```
XXX.minecraft.nbt.ShortTag +2M -1M
```
```
XXX.minecraft.network.Connection -1M
```
```
XXX.network.chat.CommonComponents -1M
```
```
XXX.server.dedicated.DedicatedPlayerList +2M
```
```
XXX.server.level.ChunkHolder +3M -8M | +2P -4P
```
```
XXX.server.packs.PackType +1M -2M | -1P
```
```
XXX.server.packs.VanillaPackResources +1M -1M | -1P
```
```
XXX.packs.repository.Pack +1M -1M | +1P
```
```
XXX.packs.repository.PackRepository +2M -3M
```
```
XXX.server.rcon.RconConsoleSource +1P -1P
```
```
XXX.rcon.thread.GenericThread +1P
```
```
XXX.minecraft.sounds.SoundSource +2M | +1P
```
```
XXX.minecraft.tags.EntityTypeTags +1M | -3P
```
```
XXX.minecraft.tags.TagContainer$1 +5M -2M | +4P -3P
```
```
XXX.minecraft.tags.TagManager +3M -10M | +4P -2P
```
```
XXX.minecraft.util.Mth +1M -7M
```
```
XXX.datafix.fixes.References -1M | -1P
```
```
XXX.datafix.schemas.V1460 -1M
```
```
XXX.minecraft.world.BossEvent +2M -2M | +1P -1P
```
```
XXX.minecraft.world.SimpleContainer +1M
```
```
XXX.world.entity.AreaEffectCloud +3M -1M
```
```
XXX.world.entity.LightningBolt -1M
```
```
XXX.ai.behavior.BabyFollowAdult +3M -5M | +1P -1P
```
```
XXX.ai.behavior.MeleeAttack +1M -1M
```
```
XXX.entity.animal.Cat +3M -3M
```
```
XXX.entity.animal.Chicken +2M -2M
```
```
XXX.entity.animal.Cow +2M -2M
```
```
XXX.animal.horse.AbstractHorse +5M -6M
```
```
XXX.entity.boss.EnderDragonPart -1M
```
```
XXX.boss.enderdragon.EnderDragon +1M
```
```
XXX.entity.decoration.ItemFrame$1 +1M -3M | +1P -1P
```
```
XXX.entity.vehicle.Boat -2M
```
```
XXX.entity.vehicle.MinecartHopper +1M
```
```
XXX.entity.vehicle.MinecartSpawner$1 +3M -1M
```
```
XXX.world.inventory.AbstractContainerMenu +4M -1M | +1P -1P
```
```
XXX.world.item.BucketItem +1M -2M
```
```
XXX.world.item.FireworkRocketItem -1M
```
```
XXX.world.item.PickaxeItem -1M | -1P
```
```
XXX.world.level.EntityGetter +3M -3M | +1P -1P
```
```
XXX.world.level.GameRules +1M | -2P
```
```
XXX.world.level.GameType +1M -4M | +1P -3P
```
```
XXX.level.block.AttachedStemBlock +2M -1M | -1P
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.BaseEntityBlock -1M
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M
```
```
XXX.level.block.BeaconBlock +1M -2M
```
```
XXX.level.block.Block +7M -3M
```
```
XXX.level.block.Blocks +15M -24M | +1P -81P
```
```
XXX.level.block.BrewingStandBlock +1M -2M
```
```
XXX.level.block.BucketPickup +1P -2P
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EnchantmentTableBlock +1M -2M
```
```
XXX.level.block.EndPortalBlock +1M -1M
```
```
XXX.level.block.EndRodBlock +5M | +3P
```
```
XXX.level.block.FallingBlock +2M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -2M
```
```
XXX.level.block.SignBlock +1M -1M
```
```
XXX.level.block.SpawnerBlock +1M -2M
```
```
XXX.level.block.StemBlock +2M -1M | -1P
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
XXX.block.entity.BlockEntityType +3M -3M | +1P -2P
```
```
XXX.block.entity.DispenserBlockEntity +3M -3M
```
```
XXX.block.entity.EnchantmentTableBlockEntity +3M -3M
```
```
XXX.block.entity.SignBlockEntity +2M -2M
```
```
XXX.block.entity.SmokerBlockEntity +1M -1M
```
```
XXX.block.entity.SpawnerBlockEntity$1 +4M -2M
```
```
XXX.level.chunk.LevelChunk +20M -29M | +3P -3P
```
```
XXX.chunk.storage.IOWorker +1M -2M
```
```
XXX.chunk.storage.IOWorker$Priority +2P -3P
```
```
XXX.level.levelgen.Decoratable +1M -1M
```
```
XXX.levelgen.feature.IcebergFeature +1M -1M
```
```
XXX.levelgen.feature.TreeFeature +4M -2M
```
```
XXX.level.material.LavaFluid -1M
```
```
XXX.level.storage.DerivedLevelData +1M -1M
```
```
XXX.level.storage.LevelData +2M -2M
```
```
XXX.level.storage.ServerLevelData +1M -1M
```
```
XXX.storage.loot.LootPool +5M -5M | +2P -2P
```
```
XXX.storage.loot.LootPool$Builder +2M -2M | +2P -2P
```
```
XXX.loot.entries.TagEntry$Serializer -2M
```
```
XXX.phys.shapes.SubShape +1M -2M
```

</details>
<details>
<summary>
net.minecraft.DetectedVersion
</summary>

```diff
- int getPackVersion()
+ int getPackVersion(PackType)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
- boolean lambda$trigger$1(Block,ItemStack,int,BeeNestDestroyedTrigger$TriggerInstance)
+ boolean lambda$trigger$1(BlockState,ItemStack,int,BeeNestDestroyedTrigger$TriggerInstance)
- void trigger(ServerPlayer,Block,ItemStack,int)
+ void trigger(ServerPlayer,BlockState,ItemStack,int)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
+ IllegalStateException lambda$serializeToJson$1()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
- void trigger(ServerPlayer,Animal,Animal,AgableMob)
+ void trigger(ServerPlayer,Animal,Animal,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
- boolean lambda$trigger$0(BeaconBlockEntity,ConstructBeaconTrigger$TriggerInstance)
+ boolean lambda$trigger$0(int,ConstructBeaconTrigger$TriggerInstance)
- void trigger(ServerPlayer,BeaconBlockEntity)
+ void trigger(ServerPlayer,int)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.FluidPredicate
</summary>

```diff
+ IllegalStateException lambda$serializeToJson$1()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemPredicate
</summary>

```diff
+ IllegalStateException lambda$serializeToJson$3()
+ JsonSyntaxException lambda$fromJson$2(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
+ Direction getFacingAxis(Entity,Direction$Axis)
```

</details>
<details>
<summary>
net.minecraft.core.Direction8
</summary>

```diff
- int getSideMask(boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustParticleOptions
</summary>

```diff
+ App lambda$static$2(RecordCodecBuilder$Instance)
- App lambda$static$4(RecordCodecBuilder$Instance)
- float getB()
- float getG()
- float getR()
- float getScale()
- Float lambda$null$0(DustParticleOptions)
- Float lambda$null$2(DustParticleOptions)
- Float lambda$null$3(DustParticleOptions)
- String writeToString()
+ Vec3 lambda$null$0(DustParticleOptions)
- void <init>(float,float,float,float)
+ void <init>(Vec3,float)
- void writeToNetwork(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.data.structures.StructureUpdater
</summary>

```diff
+ CompoundTag update(String,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteArrayTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- Component handleEscapePretty(String)
- String handleEscape(String)
+ void accept(TagVisitor)
- void stripEmptyChildren()
```

</details>
<details>
<summary>
net.minecraft.nbt.DoubleTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.EndTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.FloatTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.IntArrayTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.IntTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
+ Component toPrettyComponent(Tag)
+ CompoundTag packStructureTemplate(CompoundTag)
+ CompoundTag snbtToStructure(String)
+ CompoundTag unpackBlockState(String)
+ CompoundTag unpackStructureTemplate(CompoundTag)
+ double lambda$static$3(ListTag)
+ double lambda$static$4(ListTag)
+ double lambda$static$5(ListTag)
+ int lambda$static$0(ListTag)
+ int lambda$static$1(ListTag)
+ int lambda$static$2(ListTag)
+ ListTag lambda$packStructureTemplate$7(CompoundTag)
+ ListTag lambda$packStructureTemplate$8(CompoundTag)
+ ListTag lambda$unpackStructureTemplate$10(Map,CompoundTag)
+ String lambda$packBlockState$11(CompoundTag,String)
+ String packBlockState(CompoundTag)
+ String structureToSnbt(CompoundTag)
+ void lambda$packStructureTemplate$6(ListTag,ListTag,ListTag)
+ void lambda$packStructureTemplate$9(ListTag,CompoundTag)
+ void lambda$unpackBlockState$12(CompoundTag,String,String)
```

</details>
<details>
<summary>
net.minecraft.nbt.ShortTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
+ ConnectionProtocol getCurrentProtocol()
```

</details>
<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
+ MutableComponent optionNameValue(Component,Component)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
- void blackList(GameProfile)
- void whiteList(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
- Either lambda$updateFutures$5(ChunkMap,Either)
+ Either lambda$updateFutures$8(ChunkMap,Either)
+ void <init>(ChunkPos,int,LevelHeightAccessor,LevelLightEngine,ChunkHolder$LevelChangeListener,ChunkHolder$PlayerProvider)
- void <init>(ChunkPos,int,LevelLightEngine,ChunkHolder$LevelChangeListener,ChunkHolder$PlayerProvider)
+ void demoteFullChunk(ChunkMap,ChunkHolder$FullChunkStatus)
+ void lambda$null$6(CompletableFuture,LevelChunk)
+ void lambda$scheduleFullChunkPromotion$5(ChunkMap,ChunkHolder$FullChunkStatus)
+ void lambda$scheduleFullChunkPromotion$7(CompletableFuture,Either)
+ void scheduleFullChunkPromotion(ChunkMap,CompletableFuture,Executor,ChunkHolder$FullChunkStatus)
+ void updateFutures(ChunkMap,Executor)
- void updateFutures(ChunkMap)
```

</details>
<details>
<summary>
net.minecraft.server.packs.PackType
</summary>

```diff
+ int getVersion(GameVersion)
+ void <init>(String,int,String,PackType)
- void <init>(String,int,String)
```

</details>
<details>
<summary>
net.minecraft.server.packs.VanillaPackResources
</summary>

```diff
+ void <init>(PackMetadataSection,String[])
- void <init>(String[])
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.Pack
</summary>

```diff
- void <init>(String,boolean,Supplier,PackResources,PackMetadataSection,Pack$Position,PackSource)
+ void <init>(String,Component,boolean,Supplier,PackMetadataSection,PackType,Pack$Position,PackSource)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.PackRepository
</summary>

```diff
+ Pack lambda$new$0(PackType,String,Component,boolean,Supplier,PackMetadataSection,Pack$Position,PackSource)
+ void <init>(PackType,RepositorySource[])
- void <init>(RepositorySource[])
- void lambda$discoverAvailable$0(Map,Pack)
+ void lambda$discoverAvailable$1(Map,Pack)
```

</details>
<details>
<summary>
net.minecraft.sounds.SoundSource
</summary>

```diff
- Set getNames()
- SoundSource byName(String)
```

</details>
<details>
<summary>
net.minecraft.tags.EntityTypeTags
</summary>

```diff
- List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.TagContainer$1
</summary>

```diff
- TagCollection getBlocks()
- TagCollection getEntityTypes()
- TagCollection getFluids()
- TagCollection getItems()
- void <init>(TagCollection,TagCollection,TagCollection,TagCollection)
+ void <init>(TagContainer,RegistryAccess,Map)
+ void accept(ResourceKey,TagCollection)
```

</details>
<details>
<summary>
net.minecraft.tags.TagManager
</summary>

```diff
+ CompletableFuture lambda$reload$1(TagManager$LoaderInfo)
+ CompletableFuture[] lambda$reload$2(int)
- String lambda$null$0(Map$Entry)
+ String lambda$null$4(Map$Entry)
+ TagCollection lambda$createLoader$6(TagLoader,ResourceManager)
+ TagManager$LoaderInfo createLoader(ResourceManager,Executor,StaticTagHelper)
+ void <clinit>()
- void <init>()
+ void <init>(RegistryAccess)
+ void lambda$null$3(TagContainer$Builder,TagManager$LoaderInfo)
+ void lambda$reload$0(ResourceManager,Executor,List,StaticTagHelper)
- void lambda$reload$1(CompletableFuture,CompletableFuture,CompletableFuture,CompletableFuture,Void)
+ void lambda$reload$5(List,Void)
```

</details>
<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
+ double clampedMap(double,double,double,double,double)
+ double map(double,double,double,double,double)
+ double wobble(double)
+ float normal(Random,float,float)
+ float randomBetween(Random,float,float)
+ int randomBetweenInclusive(Random,int,int)
+ int roundToward(int,int)
- int roundUp(int,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.References
</summary>

```diff
+ String lambda$static$25()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1460
</summary>

```diff
+ TypeTemplate lambda$registerTypes$46(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.BossEvent
</summary>

```diff
- float getPercent()
+ float getProgress()
- void setPercent(float)
+ void setProgress(float)
```

</details>
<details>
<summary>
net.minecraft.world.SimpleContainer
</summary>

```diff
- boolean isSameItem(ItemStack,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.AreaEffectCloud
</summary>

```diff
- boolean canUse()
+ boolean lambda$tick$0(Map$Entry)
- List getEffects()
- void use()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LightningBolt
</summary>

```diff
+ void powerLightningRod()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.BabyFollowAdult
</summary>

```diff
- AgableMob getNearestAdult(AgableMob)
+ AgeableMob getNearestAdult(AgeableMob)
- boolean checkExtraStartConditions(ServerLevel,AgableMob)
+ boolean checkExtraStartConditions(ServerLevel,AgeableMob)
+ Float lambda$new$0(float,LivingEntity)
+ void <init>(IntRange,Function)
- void start(ServerLevel,AgableMob,long)
+ void start(ServerLevel,AgeableMob,long)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.MeleeAttack
</summary>

```diff
- boolean lambda$isHoldingUsableProjectileWeapon$0(Mob,Item)
+ boolean lambda$isHoldingUsableProjectileWeapon$0(Mob,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
- AgableMob getBreedOffspring(ServerLevel,AgableMob)
+ AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- Cat getBreedOffspring(ServerLevel,AgableMob)
+ Cat getBreedOffspring(ServerLevel,AgeableMob)
+ void usePlayerItem(Player,InteractionHand,ItemStack)
- void usePlayerItem(Player,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
- AgableMob getBreedOffspring(ServerLevel,AgableMob)
+ AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- Chicken getBreedOffspring(ServerLevel,AgableMob)
+ Chicken getBreedOffspring(ServerLevel,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
- AgableMob getBreedOffspring(ServerLevel,AgableMob)
+ AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
- Cow getBreedOffspring(ServerLevel,AgableMob)
+ Cow getBreedOffspring(ServerLevel,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- AgableMob getBreedOffspring(ServerLevel,AgableMob)
+ AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ boolean lambda$getSlot$1(ItemStack)
+ boolean lambda$getSlot$2(ItemStack)
- boolean setSlot(int,ItemStack)
- float getJumpRidingScale()
+ SlotAccess createEquipmentSlotAccess(int,Predicate)
+ SlotAccess getSlot(int)
- void setJumpRidingScale(float)
- void setOffspringAttributes(AgableMob,AbstractHorse)
+ void setOffspringAttributes(AgeableMob,AbstractHorse)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.EnderDragonPart
</summary>

```diff
+ boolean shouldBeSaved()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
- void dropExperience(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame$1
</summary>

```diff
+ boolean set(ItemStack)
+ ItemStack get()
- void <clinit>()
+ void <init>(ItemFrame)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
+ boolean lambda$tickBubbleColumn$0(Entity)
+ ItemStack getPickResult()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartHopper
</summary>

```diff
- Level getLevel()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner$1
</summary>

```diff
- BlockPos getPos()
- Level getLevel()
- void broadcastEvent(int)
+ void broadcastEvent(Level,BlockPos,int)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
- boolean consideredTheSameItem(ItemStack,ItemStack)
- Slot getSlotFor(Container,int)
- void addItem(int,ItemStack)
+ void clearContainer(Player,Container)
- void clearContainer(Player,Level,Container)
```

</details>
<details>
<summary>
net.minecraft.world.item.BucketItem
</summary>

```diff
- boolean emptyBucket(Player,Level,BlockPos,BlockHitResult)
+ boolean emptyContents(Player,Level,BlockPos,BlockHitResult)
+ void lambda$use$0(Player,SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.world.item.FireworkRocketItem
</summary>

```diff
+ ItemStack getDefaultInstance()
```

</details>
<details>
<summary>
net.minecraft.world.item.PickaxeItem
</summary>

```diff
+ void lambda$static$0(Object2IntOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
+ boolean lambda$getNearbyEntities$2(LivingEntity)
+ boolean lambda$getNearestEntity$1(LivingEntity)
+ List getEntitiesOfClass(Class,AABB,Predicate)
- List getLoadedEntitiesOfClass(Class,AABB,Predicate)
- List getLoadedEntitiesOfClass(Class,AABB)
- LivingEntity getNearestLoadedEntity(Class,TargetingConditions,LivingEntity,double,double,double,AABB)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
- void <init>(GameRules,MinecraftServer)
```

</details>
<details>
<summary>
net.minecraft.world.level.GameType
</summary>

```diff
- Component getDisplayName()
+ Component getLongDisplayName()
+ Component getShortDisplayName()
+ GameType byNullableId(int)
+ int getNullableId(GameType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AttachedStemBlock
</summary>

```diff
- Item getSeedItem()
- void <init>(StemGrownBlock,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseEntityBlock
</summary>

```diff
+ BlockEntityTicker createTickerHelper(BlockEntityType,BlockEntityType,BlockEntityTicker)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
+ void checkPressed(Entity,Level,BlockPos,BlockState,int)
- void checkPressed(Level,BlockPos,BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- boolean is(Block)
- boolean is(Tag)
- boolean isExceptionForConnection(Block)
+ boolean isExceptionForConnection(BlockState)
+ boolean shouldRenderFace(BlockState,BlockGetter,BlockPos,Direction,BlockPos)
- boolean shouldRenderFace(BlockState,BlockGetter,BlockPos,Direction)
- int getTickDelay(LevelReader)
+ void handlePrecipitation(BlockState,Level,BlockPos,Biome$Precipitation)
- void handleRain(Level,BlockPos)
- void prepareRender(BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
- BlockEntityType lambda$static$12()
+ BlockEntityType lambda$static$14()
- boolean lambda$static$13(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$15(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$28(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$30(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$35(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$37(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$48(BlockState,BlockGetter,BlockPos)
- ConfiguredFeature lambda$static$35()
- ConfiguredFeature lambda$static$36()
+ ConfiguredFeature lambda$static$42()
+ ConfiguredFeature lambda$static$43()
+ ConfiguredFeature lambda$static$8()
+ ConfiguredFeature lambda$static$9()
+ int lambda$static$12(BlockState)
+ int lambda$static$13(BlockState)
- int lambda$static$14(BlockState)
- int lambda$static$15(BlockState)
- int lambda$static$21(BlockState)
- int lambda$static$22(BlockState)
- int lambda$static$23(BlockState)
- int lambda$static$24(BlockState)
+ int lambda$static$28(BlockState)
+ int lambda$static$30(BlockState)
+ int lambda$static$36(BlockState)
- int lambda$static$37(BlockState)
+ int lambda$static$40(BlockState)
+ int lambda$static$41(BlockState)
+ int lambda$static$44(BlockState)
+ int lambda$static$45(BlockState)
+ int lambda$static$46(BlockState)
+ int lambda$static$47(BlockState)
- int lambda$static$8(BlockState)
- int lambda$static$9(BlockState)
+ Item lambda$static$21()
+ Item lambda$static$22()
+ Item lambda$static$23()
+ Item lambda$static$24()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndPortalBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
- BlockState mirror(BlockState,Mirror)
- BlockState rotate(BlockState,Rotation)
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- void <clinit>()
- VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FallingBlock
</summary>

```diff
- void onBroken(Level,BlockPos,FallingBlockEntity)
- void onLand(Level,BlockPos,BlockState,BlockState,FallingBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
- boolean isSameFence(Block)
+ boolean isSameFence(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
+ boolean isEmpty()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
+ boolean canAttachTo(BlockState)
- boolean canAttachToBlock(Block)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SpawnerBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StemBlock
</summary>

```diff
- Item getSeedItem()
- void <init>(StemGrownBlock,BlockBehaviour$Properties)
+ void <init>(StemGrownBlock,Supplier,BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BaseContainerBlockEntity
</summary>

```diff
+ void <init>(BlockEntityType,BlockPos,BlockState)
- void <init>(BlockEntityType)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BedBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState,DyeColor)
+ void <init>(BlockPos,BlockState)
- void <init>(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BlockEntityType
</summary>

```diff
- BlockEntity create()
+ BlockEntity create(BlockPos,BlockState)
- boolean isValid(Block)
+ boolean isValid(BlockState)
+ void <init>(BlockEntityType$BlockEntitySupplier,Set,Type)
- void <init>(Supplier,Set,Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DispenserBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockEntityType,BlockPos,BlockState)
- void <init>(BlockEntityType)
+ void <init>(BlockPos,BlockState)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void bookAnimationTick(Level,BlockPos,BlockState,EnchantmentTableBlockEntity)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SmokerBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
</summary>

```diff
- BlockPos getPos()
- Level getLevel()
- void broadcastEvent(int)
+ void broadcastEvent(Level,BlockPos,int)
+ void setNextSpawnData(Level,BlockPos,SpawnData)
- void setNextSpawnData(SpawnData)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
+ Block lambda$unpackTicks$8(BlockPos)
- Block lambda$unpackTicks$9(BlockPos)
+ boolean access$200(LevelChunk,BlockPos)
+ boolean isInLevel()
+ boolean isPositionInSection(int,BlockPos)
+ boolean isTicking(BlockPos)
+ boolean lambda$getLights$5(BlockPos)
- boolean lambda$getLights$6(BlockPos)
- boolean lambda$replaceWithPacketData$4(BlockPos)
+ boolean lambda$replaceWithPacketData$4(int,BlockEntity)
- boolean lambda$replaceWithPacketData$5(int,BlockPos)
- ClassInstanceMultiMap[] getEntitySections()
- Entity lambda$new$0(Entity)
- Fluid lambda$unpackTicks$10(BlockPos)
+ Fluid lambda$unpackTicks$9(BlockPos)
+ GameEventDispatcher getEventDispatcher(int)
+ GameEventDispatcher lambda$getEventDispatcher$0(int)
+ int getHeight()
+ int getMinBuildHeight()
+ Level access$300(LevelChunk)
+ LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$11(BlockEntity,BlockEntityTicker,BlockPos,LevelChunk$RebindableTickingBlockEntityWrapper)
- LevelLightEngine getLightEngine()
+ Logger access$400()
+ LongSet lambda$addReferenceForFeature$7(StructureFeature)
- LongSet lambda$addReferenceForFeature$8(StructureFeature)
+ LongSet lambda$getReferencesForFeature$6(StructureFeature)
- LongSet lambda$getReferencesForFeature$7(StructureFeature)
+ TickingBlockEntity createTicker(BlockEntity,BlockEntityTicker)
- void <init>(Level,ProtoChunk)
+ void <init>(ServerLevel,ProtoChunk,Consumer)
+ void addAndRegisterBlockEntity(BlockEntity)
- void addBlockEntity(BlockEntity)
+ void addGameEventListener(BlockEntity)
- void getEntities(Entity,AABB,List,Predicate)
- void getEntities(EntityType,AABB,List,Predicate)
- void getEntitiesOfClass(Class,AABB,List,Predicate)
+ void invalidateAllBlockEntities()
+ void lambda$registerAllBlockEntitiesAfterLevelLoad$10(BlockEntity)
+ void onBlockEntityRemove(BlockEntity)
+ void registerAllBlockEntitiesAfterLevelLoad()
+ void removeBlockEntityTicker(BlockPos)
- void removeEntity(Entity,int)
- void removeEntity(Entity)
+ void removeGameEventListener(BlockEntity)
+ void setBlockEntity(BlockEntity)
- void setBlockEntity(BlockPos,BlockEntity)
- void setLastSaveHadEntities(boolean)
- void setLastSaveTime(long)
+ void updateBlockEntityTicker(BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker
</summary>

```diff
+ CompletableFuture loadAsync(ChunkPos)
- Either lambda$load$2(ChunkPos)
+ Either lambda$loadAsync$2(ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Decoratable
</summary>

```diff
- Object chance(int)
+ Object rarity(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.IcebergFeature
</summary>

```diff
- boolean isIcebergBlock(Block)
+ boolean isIcebergState(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(WorldGenLevel,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
- void lambda$doPlace$6(TreeConfiguration,LevelSimulatedRW,Random,int,int,int,Set,BoundingBox,FoliagePlacer$FoliageAttachment)
+ void lambda$doPlace$6(TreeConfiguration,WorldGenLevel,Random,int,int,int,Set,BoundingBox,FoliagePlacer$FoliageAttachment)
- void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.material.LavaFluid
</summary>

```diff
+ Optional getPickupSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.LevelData
</summary>

```diff
- String lambda$fillCrashReportCategory$0()
+ String lambda$fillCrashReportCategory$0(LevelHeightAccessor)
+ void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.ServerLevelData
</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
- LootPoolEntryContainer[] access$200(LootPool)
+ LootPoolEntryContainer[] access$300(LootPool)
+ NumberProvider access$100(LootPool)
+ NumberProvider access$200(LootPool)
- RandomIntGenerator access$100(LootPool)
- RandomValueBounds access$300(LootPool)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider,LootPool$1)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider)
- void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],RandomIntGenerator,RandomValueBounds,LootPool$1)
- void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],RandomIntGenerator,RandomValueBounds)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool$Builder
</summary>

```diff
+ LootPool$Builder setBonusRolls(NumberProvider)
- LootPool$Builder setBonusRolls(RandomValueBounds)
+ LootPool$Builder setRolls(NumberProvider)
- LootPool$Builder setRolls(RandomIntGenerator)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
</summary>

```diff
+ IllegalStateException lambda$serializeCustom$0()
+ JsonParseException lambda$deserialize$1(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.SubShape
</summary>

```diff
+ int clampToShape(Direction$Axis,int)
+ void fill(int,int,int)
- void setFull(int,int,int,boolean,boolean)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
+ XXX.ai.behavior.CountDownTemptationTicks
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TryFindWater
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
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
+ XXX.ai.goal.MoveIndoorsGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.PlayGoal
- XXX.ai.goal.RandomLookAroundGoal
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
+ XXX.ai.goal.TakeFlowerGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$1
- XXX.ai.gossip.GossipContainer$EntityGossips
+ XXX.ai.gossip.GossipContainer$GossipEntry
- XXX.ai.gossip.GossipType
+ XXX.ai.gossip.package-info
- XXX.ai.memory.ExpirableValue
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlHostileSensor
+ XXX.ai.sensing.HostilesSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.PiglinBruteSpecificSensor
+ XXX.ai.sensing.PiglinSpecificSensor
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.TemptingSensor
+ XXX.ai.util.AirAndWaterRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
+ XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.package-info
+ XXX.animal.axolotl.PlayDead
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractChestedHorse$1
+ XXX.animal.horse.AbstractHorse$1
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$1
+ XXX.animal.horse.Llama$LlamaAttackWolfGoal
- XXX.animal.horse.Llama$LlamaGroupData
+ XXX.animal.horse.Llama$LlamaHurtByTargetGoal
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$1
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
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
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ItemPredicate
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.ItemPredicateArgument$TagPredicate
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$State
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$1
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.SheetedDecalTextureGenerator
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexBuffer
+ XXX.blaze3d.vertex.VertexConsumer
- XXX.blaze3d.vertex.VertexFormat
+ XXX.blaze3d.vertex.VertexFormat$1
+ XXX.blaze3d.vertex.VertexFormat$Mode
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
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
+ XXX.block.model.ItemOverrides
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.ItemTransforms$TransformType
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
+ XXX.block.statemap.package-info
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.OldChunkStorage$OldLevelChunk
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.client.gui.package-info
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BookModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HumanoidHeadModel
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
+ XXX.client.model.PiglinModel
- XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
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
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ServerAddress
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$1
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BarrierParticle
- XXX.client.particle.BarrierParticle$1
+ XXX.client.particle.BarrierParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$1
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$1
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$1
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$1
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$1
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$1
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$1
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$1
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$DripstoneLavaFallProvider
+ XXX.client.particle.DripParticle$DripstoneWaterFallProvider
+ XXX.client.particle.DustColorTransitionParticle$Provider
- XXX.client.particle.DustParticle$1
+ XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.FlameParticle$SmallFlameProvider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$1
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$1
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
- XXX.client.particle.HugeExplosionSeedParticle$1
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$1
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$1
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$1
- XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.Particle
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$1
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$1
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$1
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$1
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$1
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$1
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$1
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$1
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$1
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$1
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.VibrationSignalParticle
+ XXX.client.particle.VibrationSignalParticle$Provider
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$1
- XXX.client.renderer.LevelRenderer$RenderChunkInfo
+ XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$1
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$AlphaStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ XXX.client.renderer.RenderStateShard$FogStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$PortalTexturingStateShard
+ XXX.client.renderer.RenderStateShard$ShadeModelStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$1
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.commands.arguments.NbtPathArgument$ListElementFunction
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
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.UuidArgument
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$1
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
+ XXX.core.cauldron.CauldronInteraction
+ XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.recipes.UpgradeRecipeBuilder
+ XXX.data.recipes.UpgradeRecipeBuilder$Result
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1
+ XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.Features
+ XXX.data.worldgen.Features$Configs
- XXX.data.worldgen.Features$Decorators
+ XXX.data.worldgen.Features$States
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.StructureFeatures
+ XXX.data.worldgen.SurfaceBuilders
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.schemas.V2684
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
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
- XXX.entity.animal.Dolphin$DolphinMoveControl
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$1
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
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
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
+ XXX.entity.animal.Pig
- XXX.entity.animal.PolarBear
+ XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- XXX.entity.animal.PolarBear$PolarBearPanicGoal
+ XXX.entity.animal.Pufferfish
- XXX.entity.animal.Pufferfish$PufferfishPuffGoal
+ XXX.entity.animal.Rabbit
- XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
+ XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
- XXX.entity.animal.Rabbit$RabbitGroupData
+ XXX.entity.animal.Rabbit$RabbitJumpControl
- XXX.entity.animal.Rabbit$RabbitMoveControl
+ XXX.entity.animal.Rabbit$RabbitPanicGoal
- XXX.entity.animal.Rabbit$RaidGardenGoal
+ XXX.entity.animal.Salmon
- XXX.entity.animal.Sheep
+ XXX.entity.animal.Sheep$1
- XXX.entity.animal.Sheep$2
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$1
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$1
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.Turtle
- XXX.entity.animal.Turtle$1
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTemptGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.boss.BossMob
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Motive
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
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
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
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
- XXX.entity.monster.Evoker$1
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
+ XXX.entity.monster.Illusioner$1
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$1
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
- XXX.entity.monster.Ravager$1
+ XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
- XXX.entity.monster.Ravager$RavagerNavigation
+ XXX.entity.monster.Ravager$RavagerNodeEvaluator
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$1
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
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
+ XXX.entity.monster.Strider$1
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
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
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
+ XXX.entity.vehicle.AbstractMinecartContainer$1
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RangeDecoratorConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RuinedPortalConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SmallDripstoneConfiguration
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.MissingGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.WhiteGlyph
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$1
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.GlyphProviderBuilder
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.LegacyUnicodeBitmapsProvider
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$1
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
+ XXX.gameevent.vibrations.VibrationListener
+ XXX.gameevent.vibrations.VibrationPath
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
+ XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.UVPair
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
+ XXX.gui.components.CycleButton
+ XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$TooltipSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.OptionButton
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$1
+ XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
- XXX.gui.components.SliderButton
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TickableWidget
+ XXX.gui.components.TooltipAccessor
- XXX.gui.components.VolumeSlider
+ XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$1
+ XXX.gui.font.FontTexture$Node
+ XXX.gui.font.package-info
- XXX.gui.font.TextFieldHelper
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$1
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.GenericDirtMessageScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PopupScreen
- XXX.gui.screens.PopupScreen$ButtonOption
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.RealmsResetWorldScreen$2
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsResetWorldScreen$ResetType
- XXX.gui.screens.RealmsScreenWithCallback
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.package-info
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
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
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$1
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleRecipeSerializer
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.UpgradeRecipe
- XXX.item.crafting.UpgradeRecipe$Serializer
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
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
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$BiomeCategory
+ XXX.level.biome.Biome$ClimateParameters
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$1
+ XXX.level.biome.BiomeGenerationSettings$Builder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$1
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.BiomeZoomer
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.FuzzyOffsetBiomeZoomer
+ XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$1
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSource$1
+ XXX.level.biome.MultiNoiseBiomeSource$NoiseParameters
- XXX.level.biome.MultiNoiseBiomeSource$Preset
+ XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.OverworldBiomeSource
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
+ XXX.level.block.AmethystClusterBlock
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
+ XXX.level.block.CandleCakeBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeFullBlock
+ XXX.level.block.ChangeOverTimeStairBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
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
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DirtPathBlock
+ XXX.level.block.EnderChestBlock
- XXX.level.block.EndRodBlock$1
- XXX.level.block.EntityBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrassPathBlock
+ XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
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
- XXX.level.block.OreBlock
+ XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
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
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkSensorBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeagrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVines
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVines
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
+ XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
+ XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
- XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$1
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.LevelStem
+ XXX.level.dimension.package-info
+ XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityLookup
+ XXX.level.entity.EntitySection
+ XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEventDispatcher$1
+ XXX.level.gameevent.GameEventListenerRegistrar
+ XXX.level.gameevent.PositionSourceType
+ XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseSamplingSettings
- XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.NoiseSlideSettings
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.StructureSettings
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.TurtleNodeEvaluator
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.package-info
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$1
+ XXX.level.timers.TimerQueue$Event
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BaseDiskFeature
+ XXX.levelgen.feature.BastionFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.ConfiguredStructureFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndCityFeature
+ XXX.levelgen.feature.EndCityFeature$EndCityStart
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.package-info
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
- XXX.levelgen.placement.BaseHeightmapDecorator
+ XXX.levelgen.placement.BiasedRangeDecorator
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.ChanceDecorator
+ XXX.levelgen.placement.ChanceDecoratorConfiguration
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountDecorator
- XXX.levelgen.placement.CountNoiseDecorator
+ XXX.levelgen.placement.CountWithExtraChanceDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DecoratedDecorator
- XXX.levelgen.placement.DecoratedDecoratorConfiguration
+ XXX.levelgen.placement.DecorationContext
- XXX.levelgen.placement.DepthAverageConfigation
+ XXX.levelgen.placement.DepthAverageDecorator
- XXX.levelgen.placement.EdgeDecorator
+ XXX.levelgen.placement.EmeraldPlacementDecorator
- XXX.levelgen.placement.EndGatewayPlacementDecorator
+ XXX.levelgen.placement.EndIslandPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.HeightmapDecorator
- XXX.levelgen.placement.HeightmapDoubleDecorator
- XXX.levelgen.placement.HeightMapWorldSurfaceDecorator
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeLavaPlacementDecorator
+ XXX.levelgen.placement.LakeWaterPlacementDecorator
- XXX.levelgen.placement.NoiseBasedDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecorator
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.SquareDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.VeryBiasedRangeDecorator
+ XXX.levelgen.structure.BeardedStructureStart
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilFeature$FeatureStart
- XXX.levelgen.structure.NetherFossilPieces
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$Properties
- XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
- XXX.loot.functions.CopyNbtFunction$DataSource
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$1
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$1
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$1
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction$1
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$1
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$1
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$1
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$1
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$1
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$1
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$1
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$1
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$1
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$1
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$1
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$1
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$1
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$Serializer
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.CloudStatus
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.CycleOption
+ XXX.minecraft.client.CycleOption$OptionSetter
+ XXX.minecraft.client.package-info
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.RegistryAccess
+ XXX.minecraft.core.RegistryAccess$RegistryData
- XXX.minecraft.core.RegistryAccess$RegistryHolder
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableUUID
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.BuiltinRegistries
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.TextComponentTagVisitor
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.NarrationHelper
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsBridge
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RealmsServerAddress
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerResources
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.SerializationTags
+ XXX.minecraft.tags.SetTag
- XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.StaticTagHelper$1
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.StaticTags
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$1
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$OptionalElementEntry
- XXX.minecraft.tags.Tag$OptionalTagEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagCollection
+ XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagContainer$Builder
+ XXX.minecraft.tags.TagManager$1
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.UniformFloat
- XXX.minecraft.util.UniformInt
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.WeighedRandom
- XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.package-info
+ XXX.model.geom.EntityModelSet
+ XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelPart$Visitor
+ XXX.model.geom.PartPose
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
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
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
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
+ XXX.network.protocol.package-info
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
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
- XXX.phys.shapes.package-info
+ XXX.placement.nether.CountMultiLayerDecorator
- XXX.placement.nether.FireDecorator
+ XXX.placement.nether.GlowstoneDecorator
- XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
+ XXX.protocol.game.ClientboundAddVibrationSignalPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockBreakAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$1
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerAckPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
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
+ XXX.protocol.game.ClientboundPlayerCombatPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket$1
+ XXX.protocol.game.ClientboundPlayerCombatPacket$Event
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetBorderPacket
+ XXX.protocol.game.ClientboundSetBorderPacket$1
- XXX.protocol.game.ClientboundSetBorderPacket$Type
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesPacket
+ XXX.protocol.game.ClientboundSetTitlesPacket$Type
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerAckPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
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
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
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
+ XXX.protocol.game.ServerGamePacketListener
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
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider$1
+ XXX.providers.number.BinomialDistributionGenerator$1
+ XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$DefaultSerializer
+ XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProviders
+ XXX.providers.number.ScoreboardValue$1
+ XXX.providers.number.UniformGenerator
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$DefaultSerializer
+ XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$1
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$1
- XXX.realmsclient.util.SkinProcessor
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.realmsclient.util.WorldGenerationInfo
- XXX.renderer.banner.package-info
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
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
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.debug.GameEventListenerRenderer
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AreaEffectCloudRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.EntityRendererProvider$Context
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.GhastRenderer
- XXX.renderer.entity.GiantMobRenderer
+ XXX.renderer.entity.GuardianRenderer
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
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$1
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlList
- XXX.screens.controls.ControlList$1
+ XXX.screens.controls.ControlList$CategoryEntry
- XXX.screens.controls.ControlList$Entry
+ XXX.screens.controls.ControlList$KeyEntry
- XXX.screens.controls.ControlList$KeyEntry$1
+ XXX.screens.controls.ControlList$KeyEntry$2
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.worldselection.CreateWorldScreen$2
- XXX.screens.worldselection.CreateWorldScreen$4
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.WorldGenSettingsComponent
- XXX.screens.worldselection.WorldGenSettingsComponent$1
- XXX.screens.worldselection.WorldGenSettingsComponent$3
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
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
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
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
- XXX.server.commands.ReplaceItemCommand
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
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
+ XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.package-info
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.ConstantIntValue$Serializer
- XXX.storage.loot.IntLimiter$1
+ XXX.storage.loot.IntRange$1
+ XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.ItemModifierManager
- XXX.storage.loot.package-info
- XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.threaded.package-info
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
- XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
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
+ XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.PackedBitStorage
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.world.entity.AgableMob$AgableMobGroupData
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
+ XXX.world.entity.package-info
+ XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$2
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
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
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$10
- XXX.world.item.CreativeModeTab$11
+ XXX.world.item.CreativeModeTab$12
- XXX.world.item.CreativeModeTab$2
+ XXX.world.item.CreativeModeTab$3
- XXX.world.item.CreativeModeTab$4
+ XXX.world.item.CreativeModeTab$5
- XXX.world.item.CreativeModeTab$6
+ XXX.world.item.CreativeModeTab$7
- XXX.world.item.CreativeModeTab$8
+ XXX.world.item.CreativeModeTab$9
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.FishBucketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$1
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
+ XXX.world.item.package-info
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
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
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkTickList
- XXX.world.level.ChunkTickList$1
+ XXX.world.level.ChunkTickList$ScheduledTick
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
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
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
+ XXX.world.level.StructureFeatureManager
- XXX.world.level.TickList
+ XXX.world.level.TickNextTickData
- XXX.world.level.TickPriority
+ XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
- XXX.worldgen.biome.BiomeReport
+ XXX.worldgen.biome.Biomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.biome.VanillaBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.systems.RenderSystem +74M -77M | -2P
```
```
XXX.mojang.math.Matrix4f -1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen +12M -14M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry +1M -1M
```
```
XXX.gui.screens.RealmsBackupInfoScreen -1M | -1P
```
```
XXX.gui.screens.RealmsResetWorldScreen +8M -7M | +3P
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen +4M -3M | +1P -1P
```
```
XXX.util.task.GetServerDetailsTask +4M -7M
```
```
net.minecraft.CrashReportCategory +5M -5M
```
```
net.minecraft.Util -2M
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.EntityTypePredicate -1M
```
```
XXX.advancements.critereon.EntityTypePredicate$TagPredicate -1M
```
```
XXX.minecraft.client.Minecraft$1 +1P
```
```
XXX.client.gui.GuiComponent -1M
```
```
XXX.gui.components.BossHealthOverlay +1M
```
```
XXX.gui.components.LerpingBossEvent +2M -2M
```
```
XXX.screens.inventory.LoomScreen -1M
```
```
XXX.screens.worldselection.CreateWorldScreen +28M -25M | +6P -5P
```
```
XXX.gui.spectator.PlayerMenuItem +1P -1P
```
```
XXX.client.model.ArmorStandModel +2M -2M | +2P -2P
```
```
XXX.client.model.HoglinModel +1M -2M | +4P -4P
```
```
XXX.client.model.SnowGolemModel +2M -3M | +4P -4P
```
```
XXX.client.model.SquidModel +2M -5M | +2P -1P
```
```
XXX.client.model.TridentModel +1M -2M | +1P -1P
```
```
XXX.client.model.TropicalFishModelB +2M -3M | +5P -1P
```
```
XXX.client.model.VexModel +1M -2M
```
```
XXX.client.model.VillagerModel +3M -3M | +5P -3P
```
```
XXX.client.model.WitherBossModel +3M -4M | +3P -6P
```
```
XXX.client.model.ZombieModel +2M -1M
```
```
XXX.model.dragon.DragonHeadModel +1M -2M
```
```
XXX.model.geom.ModelPart +15M -9M | +7P -2P
```
```
XXX.client.multiplayer.ClientAdvancements +1M
```
```
XXX.client.multiplayer.ClientChunkCache +2M -1M
```
```
XXX.client.multiplayer.ClientLevel +14M -18M | +1P -2P
```
```
XXX.client.multiplayer.ClientLevel$ClientLevelData +1M -1M
```
```
XXX.client.player.AbstractClientPlayer +1M
```
```
XXX.client.renderer.GameRenderer +1M -2M
```
```
XXX.renderer.blockentity.ChestRenderer +1M -4M
```
```
XXX.renderer.blockentity.EnchantTableRenderer +1M -1M
```
```
XXX.renderer.blockentity.PistonHeadRenderer +1M -1M
```
```
XXX.renderer.blockentity.SignRenderer +3M -7M | +1P -2P
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
XXX.renderer.chunk.VisGraph +1M
```
```
XXX.renderer.debug.DebugRenderer -1P
```
```
XXX.renderer.entity.BeeRenderer +1M -1M
```
```
XXX.renderer.entity.BoatRenderer +2M -3M | +2P -1P
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
XXX.renderer.entity.EndCrystalRenderer +1M -2M
```
```
XXX.renderer.entity.EnderDragonRenderer$DragonModel +1M -1M
```
```
XXX.renderer.entity.EndermiteRenderer +1M -1M
```
```
XXX.renderer.entity.EntityRenderer +2M -1M | -1P
```
```
XXX.entity.layers.SheepFurLayer +1M -1M
```
```
XXX.entity.layers.SlimeOuterLayer +1M -1M
```
```
XXX.entity.layers.StrayClothingLayer +1M -1M
```
```
XXX.entity.layers.TropicalFishPatternLayer +1M -1M
```
```
XXX.renderer.item.ItemProperties$1 +1M -1M
```
```
XXX.client.resources.DefaultClientPackResources +1M -1M
```
```
XXX.metadata.animation.AnimationMetadataSection +1M
```
```
XXX.resources.sounds.AbstractSoundInstance +1M | +1P
```
```
XXX.client.server.LanServer +1M
```
```
XXX.minecraft.commands.CommandFunction$CommandEntry +1M -1M
```
```
XXX.minecraft.commands.CommandFunction$FunctionEntry +2M -2M
```
```
XXX.commands.arguments.AngleArgument -1P
```
```
XXX.minecraft.core.BlockPos +1M -1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +3M -6M
```
```
XXX.minecraft.core.BlockSourceImpl +1M
```
```
XXX.gametest.framework.GameTestSequence +4M -6M
```
```
XXX.gametest.framework.GameTestServer +2M -1M
```
```
XXX.gametest.framework.GameTestTicker +1P -1P
```
```
XXX.gametest.framework.StructureUtils +4M -7M | -1P
```
```
XXX.gametest.framework.TestFunction -4M | -2P
```
```
XXX.minecraft.nbt.ListTag +2M -1M | +1P
```
```
XXX.minecraft.nbt.LongArrayTag +1M -1M
```
```
XXX.minecraft.nbt.LongTag +2M -1M
```
```
XXX.minecraft.nbt.NumericTag -1M
```
```
XXX.minecraft.nbt.Tag +4M | +5P -1P
```
```
XXX.protocol.game.ClientGamePacketListener -1P
```
```
XXX.server.commands.SpreadPlayersCommand$Position +4M -3M
```
```
XXX.server.dedicated.DedicatedServer +1M -2M
```
```
XXX.server.dedicated.DedicatedServerProperties +1M | +1P -1P
```
```
XXX.server.level.ChunkMap +26M -27M | -1P
```
```
XXX.server.level.DemoMode +1M -1M
```
```
XXX.packs.repository.Pack$PackConstructor +1P -1P
```
```
XXX.packs.repository.PackCompatibility +1M -2M
```
```
XXX.packs.repository.ServerPacksSource -1M | -1P
```
```
XXX.packs.resources.ReloadableResourceManager +2P -1P
```
```
XXX.packs.resources.SimpleReloadableResourceManager +4M -2M | +1P
```
```
XXX.server.players.PlayerList +4M -1M | +1P
```
```
XXX.server.players.ServerOpList +2M -1M
```
```
XXX.server.players.UserBanList +1M -1M
```
```
XXX.server.players.UserWhiteList +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents -82P
```
```
XXX.minecraft.stats.StatType +1M
```
```
XXX.minecraft.tags.BlockTags +1M | -7P
```
```
XXX.minecraft.tags.FluidTags +1M -1M | -1P
```
```
XXX.minecraft.tags.TagContainer +3M -14M | +4P -2P
```
```
XXX.minecraft.tags.TagLoader +8M -20M | +1P
```
```
XXX.datafix.fixes.JigsawRotationFix +1P -1P
```
```
XXX.datafix.schemas.V99 +4M -5M
```
```
XXX.minecraft.world.Difficulty +1M
```
```
XXX.world.damagesource.DamageSource -2M | -3P
```
```
XXX.world.effect.MobEffectInstance +1M | +1P
```
```
XXX.world.entity.Entity +16M -43M | +9P -7P
```
```
XXX.world.entity.EquipmentSlot -1M
```
```
XXX.world.entity.ExperienceOrb +1M -8M | +3P -1P
```
```
XXX.world.entity.LivingEntity +1M -10M | +1P -1P
```
```
XXX.world.entity.Mob +3M -2M
```
```
XXX.world.entity.NeutralMob +1M -1M
```
```
XXX.world.entity.PlayerRideableJumping +2P
```
```
XXX.ai.behavior.BehaviorUtils +5M -7M
```
```
XXX.ai.behavior.GiveGiftToHero +1P -1P
```
```
XXX.ai.behavior.RandomStroll -1M
```
```
XXX.ai.behavior.VillagerMakeLove +1M -1M
```
```
XXX.ai.sensing.VillagerHostilesSensor +6M -1M
```
```
XXX.boss.enderdragon.EndCrystal -1M
```
```
XXX.entity.decoration.ArmorStand +1M -1M
```
```
XXX.entity.decoration.ItemFrame +1M -3M
```
```
XXX.entity.vehicle.MinecartSpawner -3M | -1P
```
```
XXX.world.inventory.AbstractFurnaceMenu +1M -1M
```
```
XXX.world.item.ArmorItem -1M
```
```
XXX.world.item.BlockItem -2M
```
```
XXX.world.item.DyeColor +1M | +2P
```
```
XXX.world.item.ElytraItem -1M
```
```
XXX.world.level.EmptyBlockGetter -2M
```
```
XXX.world.level.ForcedChunksSavedData +1M -2M
```
```
XXX.world.level.Level +14M -8M | +6P -6P
```
```
XXX.world.level.LevelAccessor +1M -4M | -1P
```
```
XXX.level.block.AnvilBlock +1M -2M
```
```
XXX.level.block.BaseRailBlock -2M | -1P
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -2M
```
```
XXX.level.block.BellBlock +1M -2M
```
```
XXX.level.block.BlastFurnaceBlock +1M -2M
```
```
XXX.level.block.BubbleColumnBlock +1M -2M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.DropperBlock +1M -1M
```
```
XXX.level.block.EndGatewayBlock +1M -2M
```
```
XXX.level.block.FurnaceBlock +1M -2M
```
```
XXX.level.block.GrowingPlantBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -2M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.KelpPlantBlock -1M
```
```
XXX.level.block.SimpleWaterloggedBlock +1M -2M
```
```
XXX.level.block.SmokerBlock +1M -2M
```
```
XXX.level.block.SoulFireBlock +1M -1M
```
```
XXX.level.block.SoundType -13P
```
```
XXX.level.block.StairBlock +1M
```
```
XXX.block.entity.BeaconBlockEntity +7M -7M
```
```
XXX.block.entity.BeehiveBlockEntity +6M -5M
```
```
XXX.block.entity.BellBlockEntity +9M -12M
```
```
XXX.block.entity.DaylightDetectorBlockEntity +2M -1M
```
```
XXX.block.entity.DropperBlockEntity +1M -1M
```
```
XXX.block.entity.EnderChestBlockEntity +5M -5M | +4P -2P
```
```
XXX.block.entity.ShulkerBoxBlockEntity +9M -9M | +1P
```
```
XXX.block.entity.SkullBlockEntity +3M -3M
```
```
XXX.block.entity.SpawnerBlockEntity +3M -4M
```
```
XXX.block.entity.StructureBlockEntity +4M -2M
```
```
XXX.level.chunk.ImposterProtoChunk +3M -1M
```
```
XXX.chunk.storage.OldChunkStorage -1M | -1P
```
```
XXX.level.levelgen.DebugLevelSource +1M -1M
```
```
XXX.level.levelgen.FlatLevelSource +1M -1M
```
```
XXX.levelgen.feature.RuinedPortalFeature +2M -1M
```
```
XXX.level.material.Material -3P
```
```
XXX.level.material.WaterFluid -1M
```
```
XXX.newbiome.context.BigContext +1P
```
```
XXX.newbiome.context.LazyAreaContext +1M
```
```
XXX.saveddata.maps.MapItemSavedData$HoldingPlayer +2M -8M | -1P
```
```
XXX.level.storage.CommandStorage$Container +2M -4M
```
```
XXX.level.storage.DimensionDataStorage +4M -5M
```
```
XXX.level.storage.PrimaryLevelData +2M -2M
```
```
XXX.loot.functions.CopyNbtFunction +9M -6M | +3P -1P
```
```
XXX.loot.functions.CopyNbtFunction$Builder +2M -2M | +1P -1P
```
```
XXX.phys.shapes.Shapes -1M
```
```
XXX.phys.shapes.VoxelShape +2M -1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ Logger access$200()
+ RenderSystem$AutoStorageIndexBuffer getSequentialBuffer(VertexFormat$Mode,int)
- void drawArrays(int,int,int)
+ void drawElements(int,int,int)
- void lambda$activeTexture$22(int)
+ void lambda$activeTexture$23(int)
- void lambda$alphaFunc$0(int,float)
+ void lambda$alphaFunc$1(int,float)
- void lambda$bindTexture$25(int)
+ void lambda$bindTexture$26(int)
- void lambda$blendColor$11(float,float,float,float)
+ void lambda$blendColor$12(float,float,float,float)
- void lambda$blendEquation$10(int)
+ void lambda$blendEquation$11(int)
- void lambda$blendFunc$6(GlStateManager$SourceFactor,GlStateManager$DestFactor)
+ void lambda$blendFunc$7(GlStateManager$SourceFactor,GlStateManager$DestFactor)
- void lambda$blendFunc$7(int,int)
+ void lambda$blendFunc$8(int,int)
+ void lambda$blendFuncSeparate$10(int,int,int,int)
- void lambda$blendFuncSeparate$8(GlStateManager$SourceFactor,GlStateManager$DestFactor,GlStateManager$SourceFactor,GlStateManager$DestFactor)
+ void lambda$blendFuncSeparate$9(GlStateManager$SourceFactor,GlStateManager$DestFactor,GlStateManager$SourceFactor,GlStateManager$DestFactor)
- void lambda$blendFuncSeparate$9(int,int,int,int)
- void lambda$clear$35(int,boolean)
+ void lambda$clear$36(int,boolean)
- void lambda$clearColor$33(float,float,float,float)
+ void lambda$clearColor$34(float,float,float,float)
- void lambda$clearDepth$32(double)
+ void lambda$clearDepth$33(double)
- void lambda$clearStencil$34(int)
+ void lambda$clearStencil$35(int)
- void lambda$color3f$45(float,float,float)
+ void lambda$color3f$46(float,float,float)
- void lambda$color4f$44(float,float,float,float)
+ void lambda$color4f$45(float,float,float,float)
- void lambda$colorMask$28(boolean,boolean,boolean,boolean)
+ void lambda$colorMask$29(boolean,boolean,boolean,boolean)
- void lambda$colorMaterial$1(int,int)
+ void lambda$colorMaterial$2(int,int)
- void lambda$deleteTexture$24(int)
+ void lambda$deleteTexture$25(int)
- void lambda$depthFunc$4(int)
+ void lambda$depthFunc$5(int)
- void lambda$depthMask$5(boolean)
+ void lambda$depthMask$6(boolean)
- void lambda$drawArrays$46(int,int,int)
+ void lambda$drawElements$47(int,int,int)
- void lambda$enableScissor$3(int,int,int,int)
+ void lambda$enableScissor$4(int,int,int,int)
- void lambda$fog$17(int,float,float,float,float)
+ void lambda$fog$18(int,float,float,float,float)
- void lambda$fogDensity$14(float)
+ void lambda$fogDensity$15(float)
- void lambda$fogEnd$16(float)
+ void lambda$fogEnd$17(float)
- void lambda$fogi$18(int,int)
+ void lambda$fogi$19(int,int)
- void lambda$fogMode$12(GlStateManager$FogMode)
+ void lambda$fogMode$13(GlStateManager$FogMode)
- void lambda$fogMode$13(int)
+ void lambda$fogMode$14(int)
- void lambda$fogStart$15(float)
+ void lambda$fogStart$16(float)
- void lambda$getString$51(int,Consumer)
+ void lambda$getString$52(int,Consumer)
- void lambda$glBindBuffer$54(int,Supplier)
+ void lambda$glBindBuffer$55(int,Supplier)
- void lambda$glDeleteBuffers$55(int)
+ void lambda$glDeleteBuffers$56(int)
- void lambda$glGenBuffers$72(Consumer)
+ void lambda$glGenBuffers$73(Consumer)
- void lambda$glMultiTexCoord2f$53(int,float,float)
+ void lambda$glMultiTexCoord2f$54(int,float,float)
- void lambda$glUniform1$57(int,IntBuffer)
+ void lambda$glUniform1$58(int,IntBuffer)
- void lambda$glUniform1$61(int,FloatBuffer)
+ void lambda$glUniform1$62(int,FloatBuffer)
- void lambda$glUniform1i$56(int,int)
+ void lambda$glUniform1i$57(int,int)
- void lambda$glUniform2$58(int,IntBuffer)
+ void lambda$glUniform2$59(int,IntBuffer)
- void lambda$glUniform2$62(int,FloatBuffer)
+ void lambda$glUniform2$63(int,FloatBuffer)
- void lambda$glUniform3$59(int,IntBuffer)
+ void lambda$glUniform3$60(int,IntBuffer)
- void lambda$glUniform3$63(int,FloatBuffer)
+ void lambda$glUniform3$64(int,FloatBuffer)
- void lambda$glUniform4$60(int,IntBuffer)
+ void lambda$glUniform4$61(int,IntBuffer)
- void lambda$glUniform4$64(int,FloatBuffer)
+ void lambda$glUniform4$65(int,FloatBuffer)
- void lambda$glUniformMatrix2$65(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix2$66(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix3$66(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix3$67(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix4$67(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix4$68(int,boolean,FloatBuffer)
- void lambda$lineWidth$47(float)
+ void lambda$lineWidth$48(float)
- void lambda$logicOp$21(GlStateManager$LogicOp)
+ void lambda$logicOp$22(GlStateManager$LogicOp)
- void lambda$matrixMode$36(int)
+ void lambda$matrixMode$37(int)
- void lambda$multMatrix$43(Matrix4f)
+ void lambda$multMatrix$44(Matrix4f)
- void lambda$normal3f$2(float,float,float)
+ void lambda$normal3f$3(float,float,float)
- void lambda$ortho$37(double,double,double,double,double,double)
+ void lambda$ortho$38(double,double,double,double,double,double)
- void lambda$pixelStore$48(int,int)
+ void lambda$pixelStore$49(int,int)
- void lambda$pixelTransfer$49(int,float)
+ void lambda$pixelTransfer$50(int,float)
- void lambda$polygonMode$19(int,int)
+ void lambda$polygonMode$20(int,int)
- void lambda$polygonOffset$20(float,float)
+ void lambda$polygonOffset$21(float,float)
- void lambda$readPixels$50(int,int,int,int,int,int,ByteBuffer)
+ void lambda$readPixels$51(int,int,int,int,int,int,ByteBuffer)
- void lambda$renderCrosshair$52(int)
+ void lambda$renderCrosshair$53(int)
- void lambda$rotatef$38(float,float,float,float)
+ void lambda$rotatef$39(float,float,float,float)
- void lambda$scaled$40(double,double,double)
+ void lambda$scaled$41(double,double,double)
- void lambda$scalef$39(float,float,float)
+ void lambda$scalef$40(float,float,float)
- void lambda$setupGui3DDiffuseLighting$71(Vector3f,Vector3f)
+ void lambda$setupGui3DDiffuseLighting$72(Vector3f,Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$70(Vector3f,Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$71(Vector3f,Vector3f)
- void lambda$setupLevelDiffuseLighting$69(Vector3f,Vector3f,Matrix4f)
+ void lambda$setupLevelDiffuseLighting$70(Vector3f,Vector3f,Matrix4f)
- void lambda$setupOverlayColor$68(IntSupplier,int)
+ void lambda$setupOverlayColor$69(IntSupplier,int)
- void lambda$shadeModel$26(int)
+ void lambda$shadeModel$27(int)
+ void lambda$static$0(IntConsumer,int)
- void lambda$stencilFunc$29(int,int,int)
+ void lambda$stencilFunc$30(int,int,int)
- void lambda$stencilMask$30(int)
+ void lambda$stencilMask$31(int)
- void lambda$stencilOp$31(int,int,int)
+ void lambda$stencilOp$32(int,int,int)
- void lambda$texParameter$23(int,int,int)
+ void lambda$texParameter$24(int,int,int)
- void lambda$translated$42(double,double,double)
+ void lambda$translated$43(double,double,double)
- void lambda$translatef$41(float,float,float)
+ void lambda$translatef$42(float,float,float)
- void lambda$viewport$27(int,int,int,int)
+ void lambda$viewport$28(int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.math.Matrix4f
</summary>

```diff
+ void multiplyWithTranslation(float,float,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
- boolean access$7800(RealmsMainScreen)
- boolean access$7802(RealmsMainScreen,boolean)
+ boolean access$8000(RealmsMainScreen)
+ boolean access$8002(RealmsMainScreen,boolean)
+ Component access$7600()
+ Component access$7700()
- int access$8200(RealmsMainScreen)
- int access$8300(RealmsMainScreen)
+ int access$8400(RealmsMainScreen)
+ int access$8500(RealmsMainScreen)
- Minecraft access$8500(RealmsMainScreen)
+ Minecraft access$8700(RealmsMainScreen)
- ResourceLocation access$8400()
+ ResourceLocation access$8600()
- String access$8000(RealmsMainScreen)
+ String access$8200(RealmsMainScreen)
- void access$7600(RealmsMainScreen,PoseStack,int,int,int,int,boolean,boolean)
- void access$7700(RealmsMainScreen,Button)
+ void access$7800(RealmsMainScreen,PoseStack,int,int,int,int,boolean,boolean)
+ void access$7900(RealmsMainScreen,Button)
- void access$7900(RealmsMainScreen,PoseStack,int,int,boolean,int,int,boolean,boolean)
+ void access$8100(RealmsMainScreen,PoseStack,int,int,boolean,int,int,boolean,boolean)
- void access$8100(RealmsMainScreen,PoseStack,int,int,int,int,boolean)
+ void access$8300(RealmsMainScreen,PoseStack,int,int,int,int,boolean)
- void access$8600(RealmsMainScreen)
+ void access$8800(RealmsMainScreen)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$ServerEntry
</summary>

```diff
- RealmsServer access$8700(RealmsMainScreen$ServerEntry)
+ RealmsServer access$8900(RealmsMainScreen$ServerEntry)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
</summary>

```diff
+ void <clinit>()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
+ void access$600(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
- void access$900(RealmsResetWorldScreen,PoseStack,int,int,Component,ResourceLocation,boolean,boolean)
- void callback(WorldTemplate)
+ void generationSelectionCallback(WorldGenerationInfo)
+ void lambda$generationSelectionCallback$8(WorldGenerationInfo)
- void lambda$switchSlot$7()
+ void lambda$templateSelectionCallback$7(WorldTemplate)
- void resetWorld(RealmsResetWorldScreen$ResetWorldInfo)
+ void resetWorld(Runnable)
- void resetWorld(String,WorldTemplate,int,boolean)
- void resetWorldWithTemplate(WorldTemplate)
+ void startTask(LongRunningTask)
- void switchSlot()
+ void templateSelectionCallback(WorldTemplate)
- void triggerResetWorld(RealmsResetWorldScreen$ResetWorldInfo)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
</summary>

```diff
- boolean keyPressed(int,int,int)
+ void <init>(Consumer,RealmsServer$WorldType,WorldTemplatePaginatedList)
+ void <init>(Consumer,RealmsServer$WorldType)
- void <init>(RealmsScreenWithCallback,RealmsServer$WorldType,WorldTemplatePaginatedList)
- void <init>(RealmsScreenWithCallback,RealmsServer$WorldType)
- void backButtonClicked()
+ void onClose()
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.task.GetServerDetailsTask
</summary>

```diff
+ CompletableFuture scheduleResourcePackDownload(RealmsServerAddress)
+ RealmsLongConfirmationScreen resourcePackDownloadConfirmationScreen(RealmsServerAddress,Function)
+ RealmsLongRunningMcoTaskScreen connectScreen(RealmsServerAddress)
+ RealmsServerAddress fetchServerAddress()
+ void lambda$null$0(Function,RealmsServerAddress)
- Void lambda$null$0(Throwable)
- void lambda$null$1(RealmsServerAddress)
+ Void lambda$null$1(Throwable)
+ void lambda$resourcePackDownloadConfirmationScreen$2(RealmsServerAddress,Function,boolean)
- void lambda$run$2(RealmsServerAddress,boolean)
- void sleep(int)
```

</details>
<details>
<summary>
net.minecraft.CrashReportCategory
</summary>

```diff
- String formatLocation(BlockPos)
- String formatLocation(double,double,double)
- String formatLocation(int,int,int)
+ String formatLocation(LevelHeightAccessor,BlockPos)
+ String formatLocation(LevelHeightAccessor,double,double,double)
+ String formatLocation(LevelHeightAccessor,int,int,int)
- String lambda$populateBlockDetails$0(BlockPos)
+ String lambda$populateBlockDetails$0(LevelHeightAccessor,BlockPos)
- void populateBlockDetails(CrashReportCategory,BlockPos,BlockState)
+ void populateBlockDetails(CrashReportCategory,LevelHeightAccessor,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ DataResult fixedSize(DoubleStream,int)
+ Object getRandom(List,Random)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
</summary>

```diff
- boolean matches(Block,ItemStack,int)
+ boolean matches(BlockState,ItemStack,int)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
</summary>

```diff
- boolean matches(BeaconBlockEntity)
+ boolean matches(int)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
+ JsonSyntaxException lambda$fromJson$1(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
</summary>

```diff
+ IllegalStateException lambda$serializeToJson$0()
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
+ void fillGradient(PoseStack,int,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay
</summary>

```diff
- boolean hasBoss()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.LerpingBossEvent
</summary>

```diff
- float getPercent()
+ float getProgress()
- void setPercent(float)
+ void setProgress(float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.LoomScreen
</summary>

```diff
+ void init()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
- boolean access$700(CreateWorldScreen)
- boolean lambda$copyTempDataPackDirToNewWorld$18(Path)
+ boolean lambda$copyTempDataPackDirToNewWorld$20(Path)
- boolean lambda$createTempDataPackDirFromExistingWorld$20(Path,Path)
+ boolean lambda$createTempDataPackDirFromExistingWorld$22(Path,Path)
- boolean lambda$tryApplyNewDataPacks$11(List,String)
+ boolean lambda$tryApplyNewDataPacks$13(List,String)
- Component access$100()
- Component access$400(CreateWorldScreen)
- Component access$500(CreateWorldScreen)
- CreateWorldScreen$SelectedGameMode access$200(CreateWorldScreen)
- Difficulty access$600(CreateWorldScreen)
+ Difficulty getEffectiveDifficulty()
+ MutableComponent lambda$init$1(CycleButton)
+ MutableComponent lambda$init$4(CycleButton)
- Object lambda$tryApplyNewDataPacks$16(DataPackConfig,ServerResources,Throwable)
+ Object lambda$tryApplyNewDataPacks$18(DataPackConfig,ServerResources,Throwable)
- void lambda$copyTempDataPackDirToNewWorld$19(Path,Path)
+ void lambda$copyTempDataPackDirToNewWorld$21(Path,Path)
- void lambda$createTempDataPackDirFromExistingWorld$21(MutableObject,Path,Path)
+ void lambda$createTempDataPackDirFromExistingWorld$23(MutableObject,Path,Path)
- void lambda$init$1(Button)
+ void lambda$init$11(Button)
+ void lambda$init$12(Button)
- void lambda$init$2(Button)
+ void lambda$init$2(CycleButton,CreateWorldScreen$SelectedGameMode)
- void lambda$init$3(Button)
+ void lambda$init$3(CycleButton,Difficulty)
- void lambda$init$4(Button)
+ void lambda$init$5(CycleButton,Boolean)
+ void lambda$init$6(Button)
- void lambda$init$7(Button)
- void lambda$init$8(Button)
- void lambda$null$13(boolean)
- void lambda$null$14()
+ void lambda$null$15(boolean)
- void lambda$null$15(DataPackConfig,ServerResources)
+ void lambda$null$16()
+ void lambda$null$17(DataPackConfig,ServerResources)
- void lambda$null$5(GameRules)
- void lambda$null$6(Optional)
+ void lambda$null$7(GameRules)
+ void lambda$null$8(Optional)
- void lambda$removeTempDataPackDir$17(Path)
+ void lambda$removeTempDataPackDir$19(Path)
- void lambda$tryApplyNewDataPacks$12()
+ void lambda$tryApplyNewDataPacks$14()
+ void refreshWorldGenSettingsVisibility()
- void setDisplayOptions(boolean)
+ void setWorldGenSettingsVisible(boolean)
- void toggleDisplayOptions()
+ void toggleWorldGenSettingsVisibility()
- void updateDisplayOptions()
```

</details>
<details>
<summary>
net.minecraft.client.model.ArmorStandModel
</summary>

```diff
+ LayerDefinition createBodyLayer()
- void <init>()
- void <init>(float)
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.HoglinModel
</summary>

```diff
+ LayerDefinition createBodyLayer()
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.SnowGolemModel
</summary>

```diff
- Iterable parts()
+ LayerDefinition createBodyLayer()
+ ModelPart root()
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.SquidModel
</summary>

```diff
- Iterable parts()
+ LayerDefinition createBodyLayer()
+ ModelPart lambda$new$0(ModelPart,int)
+ ModelPart root()
+ String createTentacleName(int)
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.TridentModel
</summary>

```diff
+ LayerDefinition createLayer()
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.TropicalFishModelB
</summary>

```diff
- Iterable parts()
+ LayerDefinition createBodyLayer(CubeDeformation)
+ ModelPart root()
- void <init>(float)
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
+ LayerDefinition createBodyLayer()
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.VillagerModel
</summary>

```diff
- Iterable parts()
+ MeshDefinition createBodyModel()
+ ModelPart root()
- void <init>(float,int,int)
- void <init>(float)
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.WitherBossModel
</summary>

```diff
- ImmutableList parts()
- Iterable parts()
+ LayerDefinition createBodyLayer(CubeDeformation)
+ ModelPart root()
- void <init>(float)
+ void <init>(ModelPart)
+ void setupHeadRotation(WitherBoss,ModelPart,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.ZombieModel
</summary>

```diff
- void <init>(float,boolean)
- void <init>(float,float,int,int)
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.dragon.DragonHeadModel
</summary>

```diff
+ LayerDefinition createHeadLayer()
- void <init>(float)
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart
</summary>

```diff
+ boolean isEmpty()
- ModelPart addBox(float,float,float,float,float,float,boolean)
- ModelPart addBox(float,float,float,float,float,float)
- ModelPart addBox(String,float,float,float,int,int,int,float,int,int)
- ModelPart createShallowCopy()
+ ModelPart getChild(String)
- ModelPart setTexSize(int,int)
- ModelPart texOffs(int,int)
+ PartPose storePose()
+ Stream getAllParts()
- void <init>()
- void <init>(int,int,int,int)
+ void <init>(List,Map)
- void <init>(Model,int,int)
- void <init>(Model)
- void addBox(float,float,float,float,float,float,float,boolean)
- void addBox(float,float,float,float,float,float,float,float,float)
- void addBox(float,float,float,float,float,float,float)
- void addBox(int,int,float,float,float,float,float,float,float,float,float,boolean,boolean)
- void addChild(ModelPart)
+ void lambda$visit$0(PoseStack,ModelPart$Visitor,String,String,ModelPart)
+ void loadPose(PartPose)
+ void visit(PoseStack,ModelPart$Visitor,String)
+ void visit(PoseStack,ModelPart$Visitor)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientAdvancements
</summary>

```diff
- Map getProgress()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
- boolean isEntityTickingChunk(Entity)
- LevelChunk replaceWithPacketData(int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int,boolean)
+ LevelChunk replaceWithPacketData(int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ EntityTickList access$100(ClientLevel)
- int lambda$getBlockTint$7(BlockPos,ColorResolver)
+ int lambda$getBlockTint$9(BlockPos,ColorResolver)
+ LevelEntityGetter getEntities()
+ List access$200(ClientLevel)
+ String gatherChunkSourceStats()
- String lambda$fillReportDetails$5()
+ String lambda$fillReportDetails$7()
- String lambda$tickNonPassenger$1(Entity)
+ String lambda$tickNonPassenger$2(Entity)
- Vec3 getSkyColor(BlockPos,float)
+ Vec3 getSkyColor(Vec3,float)
+ Vec3 lambda$getSkyColor$8(BiomeManager,int,int,int)
+ void addDestroyBlockEffect(BlockPos,BlockState)
+ void gameEvent(Entity,GameEvent,BlockPos)
- void lambda$clearTintCaches$3(ColorResolver,BlockTintCache)
+ void lambda$clearTintCaches$4(ColorResolver,BlockTintCache)
- void lambda$doAnimateTick$4(BlockPos$MutableBlockPos,AmbientParticleSettings)
+ void lambda$doAnimateTick$5(BlockPos$MutableBlockPos,AmbientParticleSettings)
- void lambda$onChunkLoaded$2(int,int,ColorResolver,BlockTintCache)
+ void lambda$onChunkLoaded$3(ChunkPos,ColorResolver,BlockTintCache)
+ void lambda$tickEntities$1(Entity)
+ void onChunkLoaded(ChunkPos)
- void onChunkLoaded(int,int)
- void onEntityRemoved(Entity)
- void reAddEntitiesToChunk(LevelChunk)
- void removeAllPendingEntityRemovals()
+ void removeEntity(int,Entity$RemovalReason)
- void removeEntity(int)
- void setMapData(MapItemSavedData)
+ void setMapData(String,MapItemSavedData)
- void updateChunkPos(Entity)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
</summary>

```diff
+ void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
- ResourceLocation getSkullPath(String)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
+ float getDepthFar()
- Matrix4f getProjectionMatrix(Camera,float,boolean)
+ Matrix4f getProjectionMatrix(double)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.ChestRenderer
</summary>

```diff
+ LayerDefinition createDoubleBodyLeftLayer()
+ LayerDefinition createDoubleBodyRightLayer()
+ LayerDefinition createSingleBodyLayer()
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.EnchantTableRenderer
</summary>

```diff
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.PistonHeadRenderer
</summary>

```diff
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
- FormattedCharSequence lambda$render$0(Font,Component)
+ FormattedCharSequence lambda$render$2(Component)
+ LayerDefinition createSignLayer()
- Material getMaterial(Block)
+ SignRenderer$SignModel createSignModel(EntityModelSet,WoodType)
+ SignRenderer$SignModel lambda$new$1(BlockEntityRendererProvider$Context,WoodType)
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
+ WoodType getWoodType(Block)
+ WoodType lambda$new$0(WoodType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SkullBlockRenderer
</summary>

```diff
+ Map createSkullRenderers(EntityModelSet)
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
- void lambda$static$1(HashMap)
+ void renderSkull(Direction,float,float,PoseStack,MultiBufferSource,int,SkullModelBase,RenderType)
- void renderSkull(Direction,float,SkullBlock$Type,GameProfile,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.StructureBlockRenderer
</summary>

```diff
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
- void <init>(BlockEntityRenderDispatcher)
+ void <init>(BlockEntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.VisGraph
</summary>

```diff
- Set floodFill(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BeeRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BoatRenderer
</summary>

```diff
+ Boat$Type lambda$new$0(Boat$Type)
+ Pair lambda$new$1(EntityRendererProvider$Context,Boat$Type)
- void <clinit>()
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CaveSpiderRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ChickenRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.CowRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DolphinRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.DrownedRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndCrystalRenderer
</summary>

```diff
+ LayerDefinition createBodyLayer()
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
</summary>

```diff
- void <init>()
+ void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndermiteRenderer
</summary>

```diff
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderer
</summary>

```diff
- EntityRenderDispatcher getDispatcher()
- void <init>(EntityRenderDispatcher)
+ void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SheepFurLayer
</summary>

```diff
+ void <init>(RenderLayerParent,EntityModelSet)
- void <init>(RenderLayerParent)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
</summary>

```diff
+ void <init>(RenderLayerParent,EntityModelSet)
- void <init>(RenderLayerParent)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.StrayClothingLayer
</summary>

```diff
+ void <init>(RenderLayerParent,EntityModelSet)
- void <init>(RenderLayerParent)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
</summary>

```diff
+ void <init>(RenderLayerParent,EntityModelSet)
- void <init>(RenderLayerParent)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemProperties$1
</summary>

```diff
+ float call(ItemStack,ClientLevel,LivingEntity,int)
- float call(ItemStack,ClientLevel,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.client.resources.DefaultClientPackResources
</summary>

```diff
- void <init>(AssetIndex)
+ void <init>(PackMetadataSection,AssetIndex)
```

</details>
<details>
<summary>
net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
</summary>

```diff
- boolean hasCustomFrameTime(int)
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.AbstractSoundInstance
</summary>

```diff
- boolean hasPriority()
```

</details>
<details>
<summary>
net.minecraft.client.server.LanServer
</summary>

```diff
- boolean isUpToDate()
```

</details>
<details>
<summary>
net.minecraft.commands.CommandFunction$CommandEntry
</summary>

```diff
- void execute(ServerFunctionManager,CommandSourceStack,ArrayDeque,int)
+ void execute(ServerFunctionManager,CommandSourceStack,Deque,int)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandFunction$FunctionEntry
</summary>

```diff
- void execute(ServerFunctionManager,CommandSourceStack,ArrayDeque,int)
+ void execute(ServerFunctionManager,CommandSourceStack,Deque,int)
- void lambda$execute$0(int,ArrayDeque,ServerFunctionManager,CommandSourceStack,CommandFunction)
+ void lambda$execute$0(int,Deque,ServerFunctionManager,CommandSourceStack,CommandFunction)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
+ BlockPos atY(int)
- boolean isOutsideBuildHeight(long)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
+ BlockPos$MutableBlockPos setX(int)
+ BlockPos$MutableBlockPos setY(int)
+ BlockPos$MutableBlockPos setZ(int)
+ Vec3i setX(int)
+ Vec3i setY(int)
+ Vec3i setZ(int)
- void setX(int)
- void setY(int)
- void setZ(int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockSourceImpl
</summary>

```diff
- Material getMaterial()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestSequence
</summary>

```diff
+ GameTestSequence thenExecuteFor(int,Runnable)
- GameTestSequence thenWait(long,Runnable)
- GameTestSequence thenWait(Runnable)
+ GameTestSequence thenWaitUntil(long,Runnable)
+ GameTestSequence thenWaitUntil(Runnable)
+ void lambda$thenExecuteFor$3(int,Runnable)
- void lambda$thenFail$3(Supplier)
+ void lambda$thenFail$4(Supplier)
- void lambda$thenTrigger$4(GameTestSequence$Condition)
+ void lambda$thenTrigger$5(GameTestSequence$Condition)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
- boolean publishServer(GameType,boolean,int)
+ void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,ServerResources,Collection,BlockPos,RegistryAccess$RegistryHolder,Registry,Registry)
- void <init>(Thread,LevelStorageSource$LevelStorageAccess,PackRepository,ServerResources,Collection,BlockPos,RegistryAccess$RegistryHolder,Registry,WritableRegistry)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.StructureUtils
</summary>

```diff
- boolean lambda$clearSpaceForStructure$1(Entity)
+ boolean lambda$clearSpaceForStructure$3(Entity)
- boolean lambda$findStructureBlockContainingPos$2(BlockPos,ServerLevel,BlockPos)
+ boolean lambda$findStructureBlockContainingPos$4(BlockPos,ServerLevel,BlockPos)
+ boolean lambda$main$0(Path)
- int lambda$findNearestStructureBlock$3(BlockPos,BlockPos)
+ int lambda$findNearestStructureBlock$5(BlockPos,BlockPos)
- void lambda$clearSpaceForStructure$0(int,ServerLevel,BlockPos)
+ void lambda$clearSpaceForStructure$2(int,ServerLevel,BlockPos)
+ void lambda$main$1(Path)
+ void main(String[])
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestFunction
</summary>

```diff
+ boolean isFlaky()
+ int getMaxAttempts()
+ int getRequiredSuccesses()
+ void <init>(String,String,String,Rotation,int,long,boolean,int,int,Consumer)
```

</details>
<details>
<summary>
net.minecraft.nbt.ListTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
+ void accept(TagVisitor)
- void stripEmptyChildren()
```

</details>
<details>
<summary>
net.minecraft.nbt.LongArrayTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
- Component getPrettyDisplay(String,int)
- String toString()
+ void accept(TagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.NumericTag
</summary>

```diff
+ String toString()
```

</details>
<details>
<summary>
net.minecraft.nbt.Tag
</summary>

```diff
- boolean isEmpty()
- Component getPrettyDisplay()
- void <clinit>()
- void stripEmptyChildren()
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand$Position
</summary>

```diff
- double access$000(SpreadPlayersCommand$Position)
- double access$002(SpreadPlayersCommand$Position,double)
+ double access$200(SpreadPlayersCommand$Position)
+ double access$202(SpreadPlayersCommand$Position,double)
- void <init>(double,double)
+ void <init>(SpreadPlayersCommand$1)
- void set(double,double)
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
+ boolean isResourcePackRequired()
- boolean publishServer(GameType,boolean,int)
+ GameType getForcedGameType()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- Integer lambda$new$2(Integer)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- ChunkAccess lambda$null$25(ChunkHolder,ChunkAccess)
+ ChunkAccess lambda$null$26(ChunkHolder,ChunkAccess)
- ChunkHolder$FullChunkStatus lambda$null$24(ChunkHolder)
+ ChunkHolder$FullChunkStatus lambda$null$25(ChunkHolder)
- ChunkMap$DistanceManager getDistanceManager()
- ChunkStatus lambda$getEntityTickingRangeFuture$2(int)
- ChunkStatus lambda$postProcess$28(int)
+ ChunkStatus lambda$prepareEntityTickingChunk$2(int)
+ ChunkStatus lambda$prepareTickingChunk$29(int)
- CompletableFuture getEntityTickingRangeFuture(ChunkPos)
- CompletableFuture postProcess(ChunkHolder)
+ CompletableFuture prepareAccessibleChunk(ChunkHolder)
+ CompletableFuture prepareEntityTickingChunk(ChunkPos)
+ CompletableFuture prepareTickingChunk(ChunkHolder)
- CompletableFuture unpackTicks(ChunkHolder)
+ DistanceManager getDistanceManager()
- Either lambda$getEntityTickingRangeFuture$4(Either)
- Either lambda$null$29(List)
+ Either lambda$null$30(List)
- Either lambda$null$33(ChunkPos,LevelChunk)
- Either lambda$postProcess$30(Either)
+ Either lambda$prepareAccessibleChunk$38(Either)
+ Either lambda$prepareEntityTickingChunk$4(Either)
+ Either lambda$prepareTickingChunk$31(Either)
- Either lambda$protoChunkToFullChunk$26(ChunkHolder,Either)
+ Either lambda$protoChunkToFullChunk$27(ChunkHolder,Either)
- Either lambda$unpackTicks$37(Either)
- int access$700(ChunkPos,ServerPlayer,boolean)
- Integer lambda$dumpChunks$41(LevelChunk)
- LevelChunk lambda$null$36(ChunkAccess)
+ LevelChunk lambda$null$37(List)
- Optional lambda$dumpChunks$40(ChunkAccess)
+ Optional lambda$dumpChunks$41(ChunkAccess)
+ void <init>(ServerLevel,LevelStorageSource$LevelStorageAccess,DataFixer,StructureManager,Executor,BlockableEventLoop,LightChunkGetter,ChunkGenerator,ChunkProgressListener,ChunkStatusUpdateListener,Supplier,int,boolean)
- void <init>(ServerLevel,LevelStorageSource$LevelStorageAccess,DataFixer,StructureManager,Executor,BlockableEventLoop,LightChunkGetter,ChunkGenerator,ChunkProgressListener,Supplier,int,boolean)
+ void lambda$null$24(ProtoChunk,LevelChunk)
- void lambda$null$32(Packet[],LevelChunk,ServerPlayer)
+ void lambda$null$33(Packet[],LevelChunk,ServerPlayer)
+ void lambda$null$34(ChunkPos,LevelChunk)
- void lambda$postProcess$31(ChunkHolder,Runnable)
- void lambda$postProcess$34(ChunkPos,Either)
- void lambda$postProcess$35(ChunkHolder,Runnable)
+ void lambda$prepareAccessibleChunk$39(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$32(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$35(ChunkPos,Either)
+ void lambda$prepareTickingChunk$36(ChunkHolder,Runnable)
- void lambda$protoChunkToFullChunk$27(ChunkHolder,Runnable)
+ void lambda$protoChunkToFullChunk$28(ChunkHolder,Runnable)
- void lambda$setViewDistance$39(ChunkPos,int,Packet[],ServerPlayer)
+ void lambda$setViewDistance$40(ChunkPos,int,Packet[],ServerPlayer)
- void lambda$unpackTicks$38(ChunkHolder,Runnable)
+ void onFullChunkStatusChange(ChunkPos,ChunkHolder$FullChunkStatus)
+ void postLoadProtoChunk(ServerLevel,List)
```

</details>
<details>
<summary>
net.minecraft.server.level.DemoMode
</summary>

```diff
- void <init>(ServerLevel)
+ void <init>(ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.PackCompatibility
</summary>

```diff
+ PackCompatibility forFormat(int,PackType)
- PackCompatibility forFormat(int)
+ PackCompatibility forMetadata(PackMetadataSection,PackType)
```

</details>
<details>
<summary>
net.minecraft.server.packs.repository.ServerPacksSource
</summary>

```diff
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.SimpleReloadableResourceManager
</summary>

```diff
- Object lambda$createFullReload$0(List)
+ Object lambda$createReload$0(List)
- ReloadInstance createFullReload(Executor,Executor,CompletableFuture,List)
- ReloadInstance createQueuedReload(Executor,Executor,CompletableFuture)
+ ReloadInstance createReload(Executor,Executor,CompletableFuture,List)
- ReloadInstance createReload(Executor,Executor,List,CompletableFuture)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- void blackList(GameProfile)
+ void lambda$remove$1(Entity)
- void setOverrideGameMode(GameType)
- void updatePlayerGameMode(ServerPlayer,ServerPlayer,ServerLevel)
- void whiteList(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.server.players.ServerOpList
</summary>

```diff
- GameProfile find(String)
- int getOpLevel(GameProfile)
+ String[] lambda$getUserList$0(int)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserBanList
</summary>

```diff
- GameProfile find(String)
+ String[] lambda$getUserList$0(int)
```

</details>
<details>
<summary>
net.minecraft.server.players.UserWhiteList
</summary>

```diff
- GameProfile find(String)
+ String[] lambda$getUserList$0(int)
```

</details>
<details>
<summary>
net.minecraft.stats.StatType
</summary>

```diff
- int size()
```

</details>
<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
- List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
+ List getStaticTags()
- List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.tags.TagContainer
</summary>

```diff
+ Logger access$000()
+ Map serializeToNetwork(RegistryAccess)
+ ResourceLocation getIdOrThrow(ResourceKey,Tag,Supplier)
+ Tag getTagOrThrow(ResourceKey,ResourceLocation,Function)
+ TagCollection get(ResourceKey)
+ TagCollection getOrEmpty(ResourceKey)
- TagContainer deserializeFromNetwork(FriendlyByteBuf)
+ TagContainer deserializeFromNetwork(RegistryAccess,Map)
- TagContainer of(TagCollection,TagCollection,TagCollection,TagCollection)
+ void <init>(Map,TagContainer$1)
+ void <init>(Map)
+ void acceptCap(TagContainer$CollectionConsumer,ResourceKey,TagCollection)
+ void addTagsFromPayload(RegistryAccess,TagContainer$Builder,ResourceKey,TagCollection$NetworkPayload)
+ void getAll(TagContainer$CollectionConsumer)
+ void lambda$deserializeFromNetwork$1(RegistryAccess,TagContainer$Builder,ResourceKey,TagCollection$NetworkPayload)
+ void lambda$getAll$0(TagContainer$CollectionConsumer,ResourceKey,TagCollection)
- void serializeToNetwork(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.tags.TagLoader
</summary>

```diff
+ boolean isCyclic(Multimap,ResourceLocation,ResourceLocation)
+ boolean lambda$isCyclic$3(Multimap,ResourceLocation,ResourceLocation)
+ boolean lambda$load$0(String)
- boolean lambda$null$0(String)
- CompletableFuture prepare(ResourceManager,Executor)
- Map lambda$prepare$2(ResourceManager)
+ Map load(ResourceManager)
+ Object lambda$build$4(ResourceLocation)
- Object lambda$load$3(ResourceLocation)
+ Tag$Builder lambda$load$1(ResourceLocation)
- Tag$Builder lambda$null$1(ResourceLocation)
+ TagCollection build(Map)
- TagCollection load(Map)
+ TagCollection loadAndBuild(ResourceManager)
- void <init>(Function,String,String)
+ void <init>(Function,String)
+ void addDependencyIfNotCyclic(Multimap,ResourceLocation,ResourceLocation)
+ void lambda$build$12(Map,Multimap,Set,Function,Function,Map,ResourceLocation)
+ void lambda$build$6(Multimap,ResourceLocation,Tag$Builder)
+ void lambda$build$8(Multimap,ResourceLocation,Tag$Builder)
- void lambda$load$4(Function,Function,ResourceLocation,Tag$Builder)
+ void lambda$null$10(Map,ResourceLocation,Tag)
+ void lambda$null$11(Function,Function,Map,ResourceLocation,Tag$Builder)
+ void lambda$null$5(Multimap,ResourceLocation,ResourceLocation)
+ void lambda$null$7(Multimap,ResourceLocation,ResourceLocation)
+ void lambda$null$9(ResourceLocation,Collection)
+ void lambda$visitDependenciesAndElement$2(Map,Multimap,Set,BiConsumer,ResourceLocation)
+ void visitDependenciesAndElement(Map,Multimap,Set,ResourceLocation,BiConsumer)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
- Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
+ Dynamic lambda$addNames$36(Dynamic,Map,String,Dynamic)
- Dynamic lambda$null$33(Dynamic,Map,Dynamic)
+ Dynamic lambda$null$34(Dynamic,Map,Dynamic)
- Dynamic lambda$null$34(Dynamic,String,Dynamic)
+ Dynamic lambda$null$35(Dynamic,String,Dynamic)
+ TypeTemplate lambda$registerTypes$32(Schema)
- void lambda$static$32(HashMap)
+ void lambda$static$33(HashMap)
```

</details>
<details>
<summary>
net.minecraft.world.Difficulty
</summary>

```diff
- Difficulty nextById()
```

</details>
<details>
<summary>
net.minecraft.world.damagesource.DamageSource
</summary>

```diff
+ boolean isDamageHelmet()
+ DamageSource damageHelmet()
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
- void setSplash(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ boolean canFreeze()
- boolean checkAndResetForcedChunkAdditionFlag()
- boolean checkAndResetUpdateChunkPos()
+ boolean hasExactlyOnePlayerPassenger()
- boolean hasOnePlayerPassenger()
- boolean hasPassenger(Class)
+ boolean hasPassenger(Predicate)
+ boolean isAlwaysTicking()
+ boolean isFullyFrozen()
+ boolean isRemoved()
+ boolean lambda$hasExactlyOnePlayerPassenger$13(Entity)
+ boolean lambda$hasIndirectPassenger$14(Entity,Entity)
- boolean lambda$null$3(BlockState,BlockPos)
+ boolean lambda$null$4(BlockState,BlockPos)
+ boolean lambda$removePassenger$3(Entity,Entity)
+ boolean occludesVibrations()
- boolean setSlot(int,ItemStack)
+ boolean shouldBeSaved()
+ ChunkPos chunkPosition()
- Collection getIndirectPassengers()
+ Entity getFirstPassenger()
+ Entity$RemovalReason getRemovalReason()
+ float getPercentFrozen()
+ GameEventListenerRegistrar getGameEventListenerRegistrar()
+ int getBlockX()
+ int getBlockY()
+ int getBlockZ()
+ int getTicksFrozen()
+ int getTicksRequiredToFreeze()
+ ItemStack getPickResult()
+ Iterable getIndirectPassengers()
+ Iterator lambda$getIndirectPassengers$12()
- PortalInfo lambda$findDimensionEntryPoint$4(ServerLevel,BlockUtil$FoundRectangle)
+ PortalInfo lambda$findDimensionEntryPoint$5(ServerLevel,BlockUtil$FoundRectangle)
+ SlotAccess getSlot(int)
+ Stream getIndirectPassengersStream()
+ Stream getPassengersAndSelf()
- String lambda$fillCrashReportCategory$5()
+ String lambda$fillCrashReportCategory$9()
+ Style lambda$getDisplayName$10(Style)
- Style lambda$getDisplayName$9(Style)
- void burn(int)
+ void checkOutOfWorld()
+ void discard()
- void fillIndirectPassengers(boolean,Set)
+ void gameEvent(Entity,GameEvent)
+ void gameEvent(GameEvent)
- void lambda$teleportTo$10(ServerLevel,Entity)
+ void lambda$teleportTo$11(Entity)
+ void recreateFromPacket(ClientboundAddEntityPacket)
- void remove()
+ void remove(Entity$RemovalReason)
+ void setBodyIsInPowderSnow(boolean)
- void setDropContainerContent(boolean)
- void setLevel(Level)
+ void setLevelCallback(EntityInLevelCallback)
+ void setRemoved(Entity$RemovalReason)
+ void setTicksFrozen(int)
+ void unsetRemoved()
```

</details>
<details>
<summary>
net.minecraft.world.entity.EquipmentSlot
</summary>

```diff
+ int getIndex(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
+ boolean canMerge(ExperienceOrb,int,int)
+ boolean canMerge(ExperienceOrb)
+ boolean lambda$tryMergeToExisting$0(int,int,ExperienceOrb)
+ boolean tryMergeToExisting(ServerLevel,Vec3,int)
+ SoundSource getSoundSource()
+ void award(ServerLevel,Vec3,int)
- void burn(int)
+ void merge(ExperienceOrb)
+ void scanForEntities()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ boolean canBeTargeted()
+ boolean canFreeze()
+ boolean lambda$createEquipmentSlotAccess$11(EquipmentSlot,ItemStack)
- boolean lambda$isHolding$5(Item,Item)
+ boolean lambda$isHolding$5(Item,ItemStack)
+ EquipmentSlot getEquipmentSlot(int)
+ EquipmentSlot getEquipmentSlotForItem(ItemStack)
+ SlotAccess createEquipmentSlotAccess(LivingEntity,EquipmentSlot)
+ SlotAccess getSlot(int)
+ void removeFrost()
+ void tryAddFrost()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean isValidSlotForItem(EquipmentSlot,ItemStack)
- boolean setSlot(int,ItemStack)
+ double getMeleeAttackRangeSqr(LivingEntity)
- EquipmentSlot getEquipmentSlotForItem(ItemStack)
+ ItemStack getPickResult()
```

</details>
<details>
<summary>
net.minecraft.world.entity.NeutralMob
</summary>

```diff
+ void readPersistentAngerSaveData(Level,CompoundTag)
- void readPersistentAngerSaveData(ServerLevel,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
- boolean isWithinMeleeAttackRange(LivingEntity,LivingEntity)
+ boolean isWithinMeleeAttackRange(Mob,LivingEntity)
- boolean lambda$null$5(Villager,LivingEntity)
+ boolean lambda$null$6(Villager,LivingEntity)
+ Entity lambda$getLivingEntityFromUUIDMemory$4(LivingEntity,UUID)
- LivingEntity lambda$getLivingEntityFromUUIDMemory$4(LivingEntity,UUID)
+ LivingEntity lambda$getLivingEntityFromUUIDMemory$5(Entity)
- Stream lambda$getNearbyVillagersWithCondition$7(Villager,Predicate,List)
+ Stream lambda$getNearbyVillagersWithCondition$8(Villager,Predicate,List)
+ Vec3 getRandomSwimmablePos(PathfinderMob,int,int)
- Villager lambda$null$6(LivingEntity)
+ Villager lambda$null$7(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.RandomStroll
</summary>

```diff
+ Vec3 getTargetPos(PathfinderMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.VillagerMakeLove
</summary>

```diff
- boolean lambda$isBreedingPossible$0(AgableMob)
+ boolean lambda$isBreedingPossible$0(AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
</summary>

```diff
- int compareMobDistance(LivingEntity,LivingEntity,LivingEntity)
- int lambda$null$1(LivingEntity,LivingEntity,LivingEntity)
- Optional getVisibleEntities(LivingEntity)
+ Optional lambda$getNearestHostile$1(LivingEntity,List)
- Optional lambda$getNearestHostile$2(LivingEntity,List)
- Set requires()
- void doTick(ServerLevel,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EndCrystal
</summary>

```diff
+ ItemStack getPickResult()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- boolean setSlot(int,ItemStack)
+ ItemStack getPickResult()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
- boolean setSlot(int,ItemStack)
+ ItemStack getPickResult()
+ SlotAccess getSlot(int)
+ void recreateFromPacket(ClientboundAddEntityPacket)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner
</summary>

```diff
+ Runnable createTicker(Level)
+ void lambda$createTicker$0(Level)
+ void lambda$createTicker$1(Level)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu
</summary>

```diff
+ boolean shouldMoveToInventory(int)
- void handlePlacement(boolean,Recipe,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.world.item.ArmorItem
</summary>

```diff
+ SoundEvent getEquipSound()
```

</details>
<details>
<summary>
net.minecraft.world.item.BlockItem
</summary>

```diff
+ boolean canFitInsideContainerItems()
+ void onDestroyed(ItemEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.DyeColor
</summary>

```diff
- int getTextureDiffuseColorBGR()
```

</details>
<details>
<summary>
net.minecraft.world.item.ElytraItem
</summary>

```diff
+ SoundEvent getEquipSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
+ int getHeight()
+ int getMinBuildHeight()
```

</details>
<details>
<summary>
net.minecraft.world.level.ForcedChunksSavedData
</summary>

```diff
+ ForcedChunksSavedData load(CompoundTag)
+ void <init>(LongSet)
- void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- BlockEntity getPendingBlockEntityAt(BlockPos)
- BlockState getTopBlockState(BlockPos)
- boolean addBlockEntity(BlockEntity)
- boolean isOutsideBuildHeight(BlockPos)
- boolean isOutsideBuildHeight(int)
- List getEntities(EntityType,AABB,Predicate)
+ List getEntities(EntityTypeTest,AABB,Predicate)
- List getEntitiesOfClass(Class,AABB,Predicate)
- List getLoadedEntitiesOfClass(Class,AABB,Predicate)
- Object lambda$addBlockEntity$1(BlockEntity)
- String gatherChunkSourceStats()
- String lambda$tickBlockEntities$2(BlockEntity)
- void addAllPendingBlockEntities(Collection)
+ void addBlockEntityTicker(TickingBlockEntity)
+ void addDestroyBlockEffect(BlockPos,BlockState)
- void blockEntityChanged(BlockPos,BlockEntity)
+ void blockEntityChanged(BlockPos)
+ void lambda$getEntities$1(Entity,Predicate,List,Entity)
+ void lambda$getEntities$2(Predicate,List,EntityTypeTest,Entity)
+ void postGameEventInRadius(Entity,GameEvent,BlockPos,int)
+ void setBlockEntity(BlockEntity)
- void setBlockEntity(BlockPos,BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
- int getHeight()
+ int getLogicalHeight()
+ void gameEvent(Entity,GameEvent,Entity)
+ void gameEvent(GameEvent,BlockPos)
+ void gameEvent(GameEvent,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ DamageSource getFallDamageSource()
- void onBroken(Level,BlockPos,FallingBlockEntity)
+ void onBrokenAfterFall(Level,BlockPos,FallingBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ BlockState updateShape(BlockState,Direction,BlockState,LevelAccessor,BlockPos,BlockPos)
+ FluidState getFluidState(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BlastFurnaceBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BubbleColumnBlock
</summary>

```diff
- Fluid takeLiquid(LevelAccessor,BlockPos,BlockState)
+ ItemStack pickupBlock(LevelAccessor,BlockPos,BlockState)
+ Optional getPickupSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ void setOpen(Entity,Level,BlockState,BlockPos,boolean)
- void setOpen(Level,BlockState,BlockPos,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DropperBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndGatewayBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FurnaceBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBlock
</summary>

```diff
+ boolean canAttachTo(BlockState)
- boolean canAttachToBlock(Block)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpPlantBlock
</summary>

```diff
+ boolean canAttachTo(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SimpleWaterloggedBlock
</summary>

```diff
- Fluid takeLiquid(LevelAccessor,BlockPos,BlockState)
+ ItemStack pickupBlock(LevelAccessor,BlockPos,BlockState)
+ Optional getPickupSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SmokerBlock
</summary>

```diff
- BlockEntity newBlockEntity(BlockGetter)
+ BlockEntity newBlockEntity(BlockPos,BlockState)
+ BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SoulFireBlock
</summary>

```diff
- boolean canSurviveOnBlock(Block)
+ boolean canSurviveOnBlock(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StairBlock
</summary>

```diff
- void prepareRender(BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BeaconBlockEntity
</summary>

```diff
- int getLevels()
+ int updateBase(Level,int,int,int)
- void <init>()
+ void <init>(BlockPos,BlockState)
- void applyEffects()
+ void applyEffects(Level,BlockPos,int,MobEffect,MobEffect)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
+ void playSound(Level,BlockPos,SoundEvent)
- void playSound(SoundEvent)
+ void setLevel(Level)
- void tick()
+ void tick(Level,BlockPos,BlockState,BeaconBlockEntity)
- void updateBase(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BeehiveBlockEntity
</summary>

```diff
- boolean releaseOccupant(BlockState,BeehiveBlockEntity$BeeData,List,BeehiveBlockEntity$BeeReleaseStatus)
+ boolean releaseOccupant(Level,BlockPos,BlockState,BeehiveBlockEntity$BeeData,List,BeehiveBlockEntity$BeeReleaseStatus,BlockPos)
- void <init>()
+ void <init>(BlockPos,BlockState)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
- void sendDebugPackets()
+ void serverTick(Level,BlockPos,BlockState,BeehiveBlockEntity)
- void tick()
- void tickOccupants()
+ void tickOccupants(Level,BlockPos,BlockState,List,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BellBlockEntity
</summary>

```diff
- boolean areRaidersNearby()
+ boolean areRaidersNearby(BlockPos,List)
+ boolean isRaiderWithinRange(BlockPos,LivingEntity)
- boolean isRaiderWithinRange(LivingEntity)
+ boolean lambda$makeRaidersGlow$0(BlockPos,LivingEntity)
- boolean lambda$showBellParticles$0(BlockPos,LivingEntity)
+ boolean lambda$showBellParticles$1(BlockPos,LivingEntity)
+ boolean lambda$showBellParticles$2(BlockPos,LivingEntity)
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void clientTick(Level,BlockPos,BlockState,BellBlockEntity)
- void lambda$showBellParticles$1(BlockPos,int,MutableInt,Level,LivingEntity)
+ void lambda$showBellParticles$3(BlockPos,int,MutableInt,Level,LivingEntity)
+ void makeRaidersGlow(Level,BlockPos,List)
- void makeRaidersGlow(Level)
- void playResonateSound()
+ void serverTick(Level,BlockPos,BlockState,BellBlockEntity)
+ void showBellParticles(Level,BlockPos,List)
- void showBellParticles(Level)
- void tick()
+ void tick(Level,BlockPos,BlockState,BellBlockEntity,BellBlockEntity$ResonationEndAction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DropperBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.EnderChestBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void lidAnimateTick(Level,BlockPos,BlockState,EnderChestBlockEntity)
+ void recheckOpen()
- void setRemoved()
- void startOpen()
+ void startOpen(Player)
- void stopOpen()
+ void stopOpen(Player)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
</summary>

```diff
+ AABB getBoundingBox(Direction,float)
- AABB getBoundingBox(Direction)
+ AABB getTopBoundingBox(Direction,float)
- AABB getTopBoundingBox(Direction)
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void <init>(DyeColor,BlockPos,BlockState)
- void <init>(DyeColor)
- void doNeighborUpdates()
+ void doNeighborUpdates(Level,BlockPos,BlockState)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
- void moveCollidedEntities()
+ void moveCollidedEntities(Level,BlockPos,BlockState,float)
- void tick()
+ void tick(Level,BlockPos,BlockState,ShulkerBoxBlockEntity)
- void updateAnimation()
+ void updateAnimation(Level,BlockPos,BlockState,ShulkerBoxBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void dragonHeadAnimation(Level,BlockPos,BlockState,SkullBlockEntity)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SpawnerBlockEntity
</summary>

```diff
- void <init>()
+ void <init>(BlockPos,BlockState)
+ void clientTick(Level,BlockPos,BlockState,SpawnerBlockEntity)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
+ void serverTick(Level,BlockPos,BlockState,SpawnerBlockEntity)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.StructureBlockEntity
</summary>

```diff
- Component getDisplayName()
- void <init>()
+ void <init>(BlockPos,BlockState)
- void load(BlockState,CompoundTag)
+ void load(CompoundTag)
- void nextMode()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
- LevelLightEngine getLightEngine()
+ void setBlockEntity(BlockEntity)
- void setBlockEntity(BlockPos,BlockEntity)
- void setLastSaveTime(long)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.OldChunkStorage
</summary>

```diff
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
+ NoiseColumn getBaseColumn(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
- BlockGetter getBaseColumn(int,int)
+ NoiseColumn getBaseColumn(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
</summary>

```diff
- BlockGetter lambda$findSuitableY$0(ChunkGenerator,BlockPos)
- int randomIntInclusive(Random,int,int)
+ NoiseColumn lambda$findSuitableY$0(ChunkGenerator,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.material.WaterFluid
</summary>

```diff
+ Optional getPickupSound()
```

</details>
<details>
<summary>
net.minecraft.world.level.newbiome.context.LazyAreaContext
</summary>

```diff
- long getMixedSeed()
```

</details>
<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
</summary>

```diff
+ MapItemSavedData$MapPatch createPatch()
+ Packet access$200(MapItemSavedData$HoldingPlayer,int)
+ Packet nextUpdatePacket(int)
- Packet nextUpdatePacket(ItemStack)
+ void <init>(MapItemSavedData,Player,MapItemSavedData$1)
+ void access$300(MapItemSavedData$HoldingPlayer,int,int)
+ void access$400(MapItemSavedData$HoldingPlayer)
+ void markColorsDirty(int,int)
+ void markDecorationsDirty()
- void markDirty(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.CommandStorage$Container
</summary>

```diff
+ CommandStorage$Container access$100(CommandStorage$Container,CompoundTag)
+ CommandStorage$Container load(CompoundTag)
+ void <init>()
+ void <init>(CommandStorage$1)
- void <init>(String)
- void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DimensionDataStorage
</summary>

```diff
+ SavedData computeIfAbsent(Function,Supplier,String)
- SavedData computeIfAbsent(Supplier,String)
+ SavedData get(Function,String)
- SavedData get(Supplier,String)
+ SavedData readSavedData(Function,String)
- SavedData readSavedData(Supplier,String)
+ void lambda$save$0(String,SavedData)
- void set(SavedData)
+ void set(String,SavedData)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.PrimaryLevelData
</summary>

```diff
- void <init>(DataFixer,int,CompoundTag,boolean,int,int,int,float,long,long,int,int,int,boolean,int,boolean,boolean,boolean,WorldBorder$Settings,int,int,UUID,LinkedHashSet,TimerQueue,CompoundTag,CompoundTag,LevelSettings,WorldGenSettings,Lifecycle)
+ void <init>(DataFixer,int,CompoundTag,boolean,int,int,int,float,long,long,int,int,int,boolean,int,boolean,boolean,boolean,WorldBorder$Settings,int,int,UUID,Set,TimerQueue,CompoundTag,CompoundTag,LevelSettings,WorldGenSettings,Lifecycle)
+ void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
- void fillCrashReportCategory(CrashReportCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
</summary>

```diff
- CopyNbtFunction$Builder copyData(CopyNbtFunction$DataSource)
+ CopyNbtFunction$Builder copyData(LootContext$EntityTarget)
+ CopyNbtFunction$Builder copyData(NbtProvider)
- CopyNbtFunction$DataSource access$800(CopyNbtFunction)
- Function access$600()
- Function access$700()
+ List access$700(CopyNbtFunction)
- List access$900(CopyNbtFunction)
+ NbtProvider access$600(CopyNbtFunction)
- Tag lambda$static$1(BlockEntity)
- void <clinit>()
- void <init>(LootItemCondition[],CopyNbtFunction$DataSource,List,CopyNbtFunction$1)
- void <init>(LootItemCondition[],CopyNbtFunction$DataSource,List)
+ void <init>(LootItemCondition[],NbtProvider,List,CopyNbtFunction$1)
+ void <init>(LootItemCondition[],NbtProvider,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
</summary>

```diff
- void <init>(CopyNbtFunction$DataSource,CopyNbtFunction$1)
- void <init>(CopyNbtFunction$DataSource)
+ void <init>(NbtProvider,CopyNbtFunction$1)
+ void <init>(NbtProvider)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
+ VoxelShape create(double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.VoxelShape
</summary>

```diff
- boolean isFullWide(double,double,double)
- boolean lambda$findIndex$4(Direction$Axis,double,int)
+ boolean lambda$findIndex$4(double,Direction$Axis,int)
```

</details>
</details>
<hr/>