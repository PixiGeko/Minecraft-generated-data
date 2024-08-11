## Comparison with [1.16.4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.4)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.16.4</th><th>20w45a</th></tr><tr><td>DataPack version</td><td><code>-</code></td><td><code>6</code></td></tr><tr><td>ResourcePack version</td><td><code>-</code></td><td><code>7</code></td></tr><tr><td>World version</td><td><code>2584</code></td><td><code>2681</code></td></tr><tr><td>Protocol version</td><td><code>754</code></td><td><code>1073741829</code></td></tr></table>
</details>
<details><summary>Registries</summary>
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
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
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
item.txt
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:amethyst_shard
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
+ minecraft:purple_candle
+ minecraft:red_candle
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
loot_function_type.txt
</summary>

```diff
+ minecraft:set_banner_pattern
```

</details>





<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:small_flame
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
+ minecraft:block.large_amethyst_bud.break
+ minecraft:block.large_amethyst_bud.place
+ minecraft:block.medium_amethyst_bud.break
+ minecraft:block.medium_amethyst_bud.place
+ minecraft:block.small_amethyst_bud.break
+ minecraft:block.small_amethyst_bud.place
+ minecraft:block.tuff.break
+ minecraft:block.tuff.fall
+ minecraft:block.tuff.hit
+ minecraft:block.tuff.place
+ minecraft:block.tuff.step
+ minecraft:entity.minecart.inside.underwater
+ minecraft:item.spyglass.stop_using
+ minecraft:item.spyglass.use
```

</details>









<details>
<summary>
worldgen/feature.txt
</summary>

```diff
+ minecraft:geode
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:budding_amethyst
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
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
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
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:budding_amethyst
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
+ minecraft:purple_candle
+ minecraft:purple_candle_cake
+ minecraft:red_candle
+ minecraft:red_candle_cake
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
universal_tags/item.json
</summary>

```diff
+ minecraft:amethyst_block
+ minecraft:amethyst_cluster
+ minecraft:amethyst_shard
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
+ minecraft:purple_candle
+ minecraft:red_candle
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
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:set_banner_pattern
```

</details>





<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:small_flame
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
+ minecraft:block.large_amethyst_bud.break
+ minecraft:block.large_amethyst_bud.place
+ minecraft:block.medium_amethyst_bud.break
+ minecraft:block.medium_amethyst_bud.place
+ minecraft:block.small_amethyst_bud.break
+ minecraft:block.small_amethyst_bud.place
+ minecraft:block.tuff.break
+ minecraft:block.tuff.fall
+ minecraft:block.tuff.hit
+ minecraft:block.tuff.place
+ minecraft:block.tuff.step
+ minecraft:entity.minecart.inside.underwater
+ minecraft:item.spyglass.stop_using
+ minecraft:item.spyglass.use
```

</details>









<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:geode
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
+ firework_rocket_simple.json
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
+ waxed_cut_copper_from_waxed_block.json
+ waxed_cut_copper_slab_from_waxed_block.json
+ waxed_cut_copper_stairs_from_waxed_block.json
+ waxed_lightly_weathered_copper.json
+ waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_from_waxed_block.json
+ waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_slab_from_waxed_block.json
+ waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ waxed_lightly_weathered_cut_copper_stairs_from_waxed_block.json
+ waxed_semi_weathered_copper.json
+ waxed_semi_weathered_cut_copper_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_from_waxed_block.json
+ waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_slab_from_waxed_block.json
+ waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ waxed_semi_weathered_cut_copper_stairs_from_waxed_block.json
+ weathered_cut_copper_slab.json
+ weathered_cut_copper_stairs.json
+ weathered_cut_copper.json
+ white_candle.json
+ yellow_candle.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ argument.angle.invalid: Invalid angle
+ block.minecraft.amethyst_block: Block of Amethyst
+ block.minecraft.amethyst_cluster: Amethyst Cluster
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
+ block.minecraft.purple_candle_cake: Purple Candle Cake
+ block.minecraft.purple_candle: Purple Candle
+ block.minecraft.red_candle_cake: Red Candle Cake
+ block.minecraft.red_candle: Red Candle
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
+ dataPack.vanilla.description: The default data for Minecraft
+ item.minecraft.amethyst_shard: Amethyst Shard
+ item.minecraft.bundle: Bundle
+ item.minecraft.copper_ingot: Copper Ingot
+ item.minecraft.spyglass: Spyglass
+ multiplayer.requiredTexturePrompt.disconnect: Server requires a custom resource pack
+ multiplayer.requiredTexturePrompt.line1: This server requires the use of a custom resource pack.
+ multiplayer.requiredTexturePrompt.line2: Rejecting a custom resource pack will disconnect you from this server.
+ resourcePack.vanilla.description: The default resources for Minecraft
+ subtitles.block.cake.add_candle: Cake squishes
+ subtitles.block.candle.crackle: Candle crackles
+ subtitles.item.spyglass.stop_using: Spyglass retracts
+ subtitles.item.spyglass.use: Spyglass expands
```

</details>
</details>
<details><summary>File structure</summary>
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
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_waxed_block.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper.json
+ minecraft/advancements/recipes/decorations/black_candle.json
+ minecraft/advancements/recipes/decorations/blue_candle.json
+ minecraft/advancements/recipes/decorations/brown_candle.json
+ minecraft/advancements/recipes/decorations/candle.json
+ minecraft/advancements/recipes/decorations/cyan_candle.json
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
+ minecraft/loot_tables/blocks/purple_candle_cake.json
+ minecraft/loot_tables/blocks/purple_candle.json
+ minecraft/loot_tables/blocks/red_candle_cake.json
+ minecraft/loot_tables/blocks/red_candle.json
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
+ minecraft/recipes/firework_rocket_simple.json
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
+ minecraft/recipes/waxed_cut_copper_from_waxed_block.json
+ minecraft/recipes/waxed_cut_copper_slab_from_waxed_block.json
+ minecraft/recipes/waxed_cut_copper_stairs_from_waxed_block.json
+ minecraft/recipes/waxed_lightly_weathered_copper.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_from_waxed_block.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_waxed_block.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_waxed_block.json
+ minecraft/recipes/waxed_semi_weathered_copper.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_from_waxed_block.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_waxed_block.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_waxed_block.json
+ minecraft/recipes/weathered_cut_copper_slab.json
+ minecraft/recipes/weathered_cut_copper_stairs.json
+ minecraft/recipes/weathered_cut_copper.json
+ minecraft/recipes/white_candle.json
+ minecraft/recipes/yellow_candle.json
+ minecraft/tags/blocks/candle_cakes.json
+ minecraft/tags/blocks/candles.json
+ minecraft/tags/blocks/cauldrons.json
+ minecraft/tags/blocks/crystal_sound_blocks.json
+ minecraft/tags/items/candles.json
+ minecraft/tags/items/ignored_by_piglin_babies.json
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
+ minecraft/blockstates/purple_candle_cake.json
+ minecraft/blockstates/purple_candle.json
+ minecraft/blockstates/red_candle_cake.json
+ minecraft/blockstates/red_candle.json
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
+ minecraft/models/block/template_four_candles.json
+ minecraft/models/block/template_three_candles.json
+ minecraft/models/block/template_two_candles.json
+ minecraft/models/block/tinted_glass.json
+ minecraft/models/block/tuff.json
+ minecraft/models/block/water_cauldron_level1.json
+ minecraft/models/block/water_cauldron_level2.json
+ minecraft/models/block/water_cauldron.json
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
+ minecraft/models/item/purple_candle.json
+ minecraft/models/item/red_candle.json
+ minecraft/models/item/semi_weathered_copper_block.json
+ minecraft/models/item/semi_weathered_cut_copper_slab.json
+ minecraft/models/item/semi_weathered_cut_copper_stairs.json
+ minecraft/models/item/semi_weathered_cut_copper.json
+ minecraft/models/item/small_amethyst_bud.json
+ minecraft/models/item/spyglass_in_use.json
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
+ minecraft/particles/small_flame.json
+ minecraft/textures/block/amethyst_block.png
+ minecraft/textures/block/amethyst_cluster.png
+ minecraft/textures/block/black_candle.png
+ minecraft/textures/block/blue_candle.png
+ minecraft/textures/block/brown_candle.png
+ minecraft/textures/block/budding_amethyst.png
+ minecraft/textures/block/calcite.png
+ minecraft/textures/block/candle.png
+ minecraft/textures/block/copper_block.png
+ minecraft/textures/block/copper_ore.png
+ minecraft/textures/block/cut_copper.png
+ minecraft/textures/block/cyan_candle.png
+ minecraft/textures/block/dirt_path_side.png
+ minecraft/textures/block/dirt_path_top.png
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
+ minecraft/textures/block/purple_candle.png
+ minecraft/textures/block/red_candle.png
+ minecraft/textures/block/semi_weathered_copper_block.png
+ minecraft/textures/block/semi_weathered_cut_copper.png
+ minecraft/textures/block/small_amethyst_bud.png
+ minecraft/textures/block/tinted_glass.png
+ minecraft/textures/block/tuff.png
+ minecraft/textures/block/weathered_copper_block.png
+ minecraft/textures/block/weathered_cut_copper.png
+ minecraft/textures/block/white_candle.png
+ minecraft/textures/block/yellow_candle.png
+ minecraft/textures/item/amethyst_shard.png
+ minecraft/textures/item/black_candle.png
+ minecraft/textures/item/blue_candle.png
+ minecraft/textures/item/brown_candle.png
+ minecraft/textures/item/bundle_filled.png
+ minecraft/textures/item/bundle.png
+ minecraft/textures/item/candle.png
+ minecraft/textures/item/copper_ingot.png
+ minecraft/textures/item/cyan_candle.png
+ minecraft/textures/item/gray_candle.png
+ minecraft/textures/item/green_candle.png
+ minecraft/textures/item/light_blue_candle.png
+ minecraft/textures/item/light_gray_candle.png
+ minecraft/textures/item/lime_candle.png
+ minecraft/textures/item/magenta_candle.png
+ minecraft/textures/item/orange_candle.png
+ minecraft/textures/item/pink_candle.png
+ minecraft/textures/item/purple_candle.png
+ minecraft/textures/item/red_candle.png
+ minecraft/textures/item/spyglass.png
+ minecraft/textures/item/white_candle.png
+ minecraft/textures/item/yellow_candle.png
+ minecraft/textures/misc/spyglass_scope.png
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
- net.minecraft.commands.arguments.selector.EntitySelectorParser
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$1
+ net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Modifier
- net.minecraft.commands.arguments.selector.options.EntitySelectorOptions$Option
+ net.minecraft.commands.arguments.selector.options.package-info
- net.minecraft.commands.arguments.selector.package-info
+ net.minecraft.commands.exceptions.package-info
- net.minecraft.commands.package-info
+ net.minecraft.commands.synchronization.ArgumentSerializer
- net.minecraft.commands.synchronization.ArgumentTypes
+ net.minecraft.commands.synchronization.ArgumentTypes$1
- net.minecraft.commands.synchronization.ArgumentTypes$Entry
- net.minecraft.commands.synchronization.brigadier.BrigadierArgumentSerializers
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.FloatArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.LongArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.package-info
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.EmptyArgumentSerializer
- net.minecraft.commands.synchronization.package-info
- net.minecraft.commands.synchronization.SuggestionProviders
+ net.minecraft.commands.synchronization.SuggestionProviders$Wrapper
+ net.minecraft.core.AxisCycle
- net.minecraft.core.AxisCycle$1
+ net.minecraft.core.AxisCycle$2
- net.minecraft.core.AxisCycle$3
+ net.minecraft.core.BlockMath
- net.minecraft.core.BlockPos
+ net.minecraft.core.BlockPos$1
- net.minecraft.core.BlockPos$2
+ net.minecraft.core.BlockPos$3
- net.minecraft.core.BlockPos$4
+ net.minecraft.core.BlockPos$5
- net.minecraft.core.BlockPos$MutableBlockPos
+ net.minecraft.core.BlockSource
- net.minecraft.core.BlockSourceImpl
+ net.minecraft.core.Cursor3D
- net.minecraft.core.DefaultedRegistry
+ net.minecraft.core.Direction
- net.minecraft.core.Direction$1
+ net.minecraft.core.Direction$Axis
- net.minecraft.core.Direction$Axis$1
+ net.minecraft.core.Direction$Axis$2
- net.minecraft.core.Direction$Axis$3
+ net.minecraft.core.Direction$AxisDirection
- net.minecraft.core.Direction$Plane
+ net.minecraft.core.Direction8
- net.minecraft.core.FrontAndTop
+ net.minecraft.core.GlobalPos
- net.minecraft.core.IdMap
+ net.minecraft.core.IdMapper
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.MappedRegistry$RegistryEntry
- net.minecraft.core.NonNullList
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
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
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
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
- net.minecraft.server.level.ServerLevel$1
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
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
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
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
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
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
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
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
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
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
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.HumanoidArm
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
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
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
+ net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
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
+ net.minecraft.world.item.package-info
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
- net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.ChangeOverTimeFullBlock
- net.minecraft.world.level.block.ChangeOverTimeStairBlock
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
- net.minecraft.world.level.block.DropperBlock
+ net.minecraft.world.level.block.EnchantmentTableBlock
- net.minecraft.world.level.block.EndGatewayBlock
+ net.minecraft.world.level.block.EndPortalBlock
- net.minecraft.world.level.block.EndPortalFrameBlock
+ net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.TickableBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.Lantern
- net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.RodBlock
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
- net.minecraft.world.level.block.WaterCauldronBlock
+ net.minecraft.world.level.block.WeepingVinesPlant
- net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
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
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
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
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
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
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
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
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlideSettings
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.StructureSettings
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
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
- net.minecraft.world.ShulkerSharedHelper
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.Snooper
- net.minecraft.world.Snooper$1
+ net.minecraft.world.SnooperPopulator
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
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
XXX.advancements.critereon.BredAnimalsTrigger +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.minecraft.commands.CommandFunction$Entry +1P -1P
```
```
XXX.arguments.selector.EntitySelector +1M | +2P -1P
```
```
XXX.data.loot.BlockLoot +4M -1M
```
```
XXX.data.models.BlockModelGenerators +7M -4M
```
```
XXX.models.model.TextureMapping +2M
```
```
XXX.data.recipes.RecipeProvider +2M -1M
```
```
XXX.data.structures.NbtToSnbt +1M
```
```
XXX.minecraft.nbt.ByteArrayTag +1M -1M
```
```
XXX.minecraft.nbt.ByteTag +1M -2M
```
```
XXX.minecraft.nbt.CompoundTag +1M -2M | -1P
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
XXX.protocol.game.ClientboundLightUpdatePacket +4M -4M | +4P -4P
```
```
XXX.protocol.game.ClientboundResourcePackPacket +2M -1M | +1P
```
```
XXX.protocol.game.ServerboundInteractPacket +1M -1M
```
```
XXX.minecraft.server.MinecraftServer +1M
```
```
XXX.server.level.ChunkHolder +8M -3M | +2P
```
```
XXX.server.level.ServerPlayer +1M -1M
```
```
XXX.server.level.WorldGenRegion +3M -1M
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
XXX.minecraft.tags.ItemTags +3P
```
```
XXX.minecraft.util.Mth +2M -1M
```
```
XXX.util.datafix.DataFixTypes +1P
```
```
XXX.datafix.fixes.BlockStateData +16M
```
```
XXX.world.entity.EntityType +4M
```
```
XXX.ai.util.RandomPos +6M -14M
```
```
XXX.village.poi.PoiType +1P
```
```
XXX.entity.animal.Bee +4M -4M
```
```
XXX.entity.animal.Cat +2M -2M
```
```
XXX.entity.animal.Chicken +2M -2M
```
```
XXX.entity.animal.Cow +2M -2M
```
```
XXX.entity.animal.Fox +2M -2M
```
```
XXX.entity.animal.MushroomCow +3M -3M
```
```
XXX.entity.animal.Ocelot +2M -2M
```
```
XXX.entity.animal.Panda$PandaLookAtPlayerGoal +1M
```
```
XXX.entity.animal.Parrot +1M -1M
```
```
XXX.entity.animal.Pig +2M -2M
```
```
XXX.entity.animal.Rabbit +3M -3M
```
```
XXX.entity.animal.Turtle +1M -1M
```
```
XXX.animal.horse.AbstractHorse +2M -2M
```
```
XXX.animal.horse.Horse +1M -1M
```
```
XXX.animal.horse.Llama +2M -2M
```
```
XXX.animal.horse.Mule +1M -1M
```
```
XXX.animal.horse.ZombieHorse +1M -1M
```
```
XXX.entity.boss.EnderDragonPart +1M
```
```
XXX.boss.enderdragon.EnderDragon -1M
```
```
XXX.entity.item.ItemEntity +1M
```
```
XXX.entity.monster.Pillager +1M -1M
```
```
XXX.entity.monster.Slime +1M -1M
```
```
XXX.monster.hoglin.Hoglin +1M -1M
```
```
XXX.entity.npc.WanderingTrader +1M -1M
```
```
XXX.entity.player.Player +5M -1M
```
```
XXX.entity.projectile.FishingHook +5M -3M
```
```
XXX.entity.projectile.LlamaSpit +1M -2M
```
```
XXX.entity.projectile.ThrowableProjectile -1M
```
```
XXX.entity.projectile.ThrownEnderpearl -1M
```
```
XXX.entity.projectile.WitherSkull -1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M
```
```
XXX.entity.vehicle.Boat +2M
```
```
XXX.entity.vehicle.MinecartHopper -1M
```
```
XXX.entity.vehicle.MinecartSpawner$1 +1M -3M
```
```
XXX.world.inventory.AbstractContainerMenu +1M -1M | +1P -1P
```
```
XXX.world.item.FireworkRocketItem +1M
```
```
XXX.world.item.Item +7M -1M | +1P -1P
```
```
XXX.world.item.ItemStack +9M
```
```
XXX.world.item.ItemUtils +1M -1M
```
```
XXX.world.item.PickaxeItem +1M | +1P
```
```
XXX.world.level.PathNavigationRegion +2M
```
```
XXX.world.level.ServerTickList +1P -1P
```
```
XXX.level.biome.BiomeManager$NoiseBiomeSource +1M
```
```
XXX.level.block.CampfireBlock +2M -1M
```
```
XXX.level.block.CauldronBlock +2M -11M | -3P
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +2M -1M
```
```
XXX.level.block.DaylightDetectorBlock +3M -1M
```
```
XXX.level.block.DetectorRailBlock +2M
```
```
XXX.level.block.EnderChestBlock +3M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.MushroomBlock +1M -1M | +1P
```
```
XXX.level.block.RedStoneWireBlock +1M
```
```
XXX.level.block.ShulkerBoxBlock +2M -1M
```
```
XXX.level.block.SignBlock +1M -1M
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
XXX.block.entity.AbstractFurnaceBlockEntity +10M -10M
```
```
XXX.block.entity.BannerBlockEntity +5M -6M
```
```
XXX.block.entity.BannerPattern$Builder +1M
```
```
XXX.block.entity.BlastFurnaceBlockEntity +1M -1M
```
```
XXX.block.entity.BrewingStandBlockEntity +5M -5M
```
```
XXX.block.entity.CampfireBlockEntity +6M -6M
```
```
XXX.block.entity.CommandBlockEntity +2M -3M
```
```
XXX.block.entity.ConduitBlockEntity +13M -14M
```
```
XXX.block.entity.FurnaceBlockEntity +1M -1M
```
```
XXX.block.entity.HopperBlockEntity +13M -13M
```
```
XXX.block.entity.LecternBlockEntity +2M -2M
```
```
XXX.block.entity.RandomizableContainerBlockEntity +1M -1M
```
```
XXX.block.entity.SignBlockEntity +2M -2M
```
```
XXX.block.entity.SmokerBlockEntity +1M -1M
```
```
XXX.block.entity.SpawnerBlockEntity$1 +2M -4M
```
```
XXX.block.entity.TheEndGatewayBlockEntity +11M -8M
```
```
XXX.block.piston.PistonMovingBlockEntity +8M -8M
```
```
XXX.block.piston.PistonStructureResolver +2M -2M
```
```
XXX.block.state.BlockBehaviour -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.LevelChunk +27M -22M | +2P -3P
```
```
XXX.chunk.storage.IOWorker +2M -1M
```
```
XXX.chunk.storage.IOWorker$Priority +3P -2P
```
```
XXX.chunk.storage.RegionFile +2M
```
```
XXX.chunk.storage.SectionStorage +1M -1M | +1P
```
```
XXX.levelgen.feature.IcebergFeature +1M -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +3M
```
```
XXX.levelgen.placement.DecorationContext +2M
```
```
XXX.structure.templatesystem.BlockAgeProcessor +1P
```
```
XXX.level.lighting.SkyLightSectionStorage +1M -1M
```
```
XXX.saveddata.maps.MapBanner -1M
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
XXX.loot.functions.LootItemFunctions +1P
```
```
XXX.phys.shapes.DiscreteCubeMerger +1M | +2P -3P
```
```
XXX.phys.shapes.EntityCollisionContext +1M -1M | +1P -1P
```
```
XXX.phys.shapes.IdenticalMerger +1M
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
net.minecraft.commands.arguments.selector.EntitySelector
</summary>

```diff
- void <clinit>()
```

</details>

































<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder createCandleCakeDrops(Block)
- LootTable$Builder createCandleDrops(Block)
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
+ BlockStateGenerator access$300(Block,ResourceLocation,ResourceLocation)
- BlockStateGenerator access$400(Block,ResourceLocation,ResourceLocation)
- void access$300(BlockModelGenerators,Block,ResourceLocation)
+ void access$400(BlockModelGenerators,Block,ResourceLocation)
- void createAmethystCluster(Block)
- void createAmethystClusters()
- void createCandleAndCandleCake(Block,Block)
+ void createCauldron()
- void createCauldrons()
- void createDirtPath()
+ void createGrassPath()
```

</details>



















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping candleCake(Block)
- TextureMapping cauldron(Block)
```

</details>



<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- void buildCraftingRecipes(Consumer)
+ void buildShapelessRecipes(Consumer)
- void candle(Consumer,ItemLike,ItemLike)
```

</details>






<details>
<summary>
net.minecraft.data.structures.NbtToSnbt
</summary>

```diff
- void writeSnbt(Path,String)
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
- void accept(TagVisitor)
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
net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
</summary>

```diff
+ int getBlockYMask()
+ int getEmptyBlockYMask()
+ int getEmptySkyYMask()
+ int getSkyYMask()
- long getBlockYMask()
- long getEmptyBlockYMask()
- long getEmptySkyYMask()
- long getSkyYMask()
```

</details>













<details>
<summary>
net.minecraft.network.protocol.game.ClientboundResourcePackPacket
</summary>

```diff
- boolean isRequired()
- void <init>(String,String,boolean)
+ void <init>(String,String)
```

</details>




























<details>
<summary>
net.minecraft.network.protocol.game.ServerboundInteractPacket
</summary>

```diff
+ Entity getTarget(Level)
- Entity getTarget(ServerLevel)
```

</details>































































<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- boolean isResourcePackRequired()
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
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void sendTexturePack(String,String,boolean)
+ void sendTexturePack(String,String)
```

</details>


<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- int getMinSection()
- int getSectionsCount()
- List getEntities(EntityTypeTest,AABB,Predicate)
+ List getEntitiesOfClass(Class,AABB,Predicate)
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
net.minecraft.util.Mth
</summary>

```diff
- double wobble(double)
- int roundToward(int,int)
+ int roundUp(int,int)
```

</details>
























<details>
<summary>
net.minecraft.util.datafix.fixes.BlockStateData
</summary>

```diff
- void bootstrap0()
- void bootstrap1()
- void bootstrap10()
- void bootstrap11()
- void bootstrap12()
- void bootstrap13()
- void bootstrap14()
- void bootstrap15()
- void bootstrap2()
- void bootstrap3()
- void bootstrap4()
- void bootstrap5()
- void bootstrap6()
- void bootstrap7()
- void bootstrap8()
- void bootstrap9()
```

</details>



<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
- Class getBaseClass()
- Entity tryCast(Entity)
- Object tryCast(Object)
- Stream loadEntitiesRecursive(List,Level)
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
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Bee getBreedOffspring(ServerLevel,AgableMob)
- Bee getBreedOffspring(ServerLevel,AgeableMob)
- PathNavigation access$3900(Bee)
+ PathNavigation access$4000(Bee)
+ Random access$3900(Bee)
- Random access$4000(Bee)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Cat getBreedOffspring(ServerLevel,AgableMob)
- Cat getBreedOffspring(ServerLevel,AgeableMob)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Chicken getBreedOffspring(ServerLevel,AgableMob)
- Chicken getBreedOffspring(ServerLevel,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Cow getBreedOffspring(ServerLevel,AgableMob)
- Cow getBreedOffspring(ServerLevel,AgeableMob)
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
+ boolean isTemptingItem(Item)
- boolean isTemptingItem(ItemStack)
+ Rabbit getBreedOffspring(ServerLevel,AgableMob)
- Rabbit getBreedOffspring(ServerLevel,AgeableMob)
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
+ void setOffspringAttributes(AgableMob,AbstractHorse)
- void setOffspringAttributes(AgeableMob,AbstractHorse)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
+ Llama getBreedOffspring(ServerLevel,AgableMob)
- Llama getBreedOffspring(ServerLevel,AgeableMob)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.Mule
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
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
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- SoundSource getSoundSource()
```

</details>































<details>
<summary>
net.minecraft.world.entity.monster.Pillager
</summary>

```diff
+ boolean wantsItem(Item)
- boolean wantsItem(ItemStack)
```

</details>








<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
+ void remove()
- void remove(Entity$RemovalReason)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.npc.WanderingTrader
</summary>

```diff
+ AgableMob getBreedOffspring(ServerLevel,AgableMob)
- AgeableMob getBreedOffspring(ServerLevel,AgeableMob)
```

</details>



<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- Abilities getAbilities()
- boolean isAlwaysTicking()
- boolean isScoping()
- Inventory getInventory()
+ void remove()
- void remove(Entity$RemovalReason)
```

</details>







<details>
<summary>
net.minecraft.world.entity.projectile.FishingHook
</summary>

```diff
- void <init>(EntityType,Level,int,int)
- void <init>(EntityType,Level)
+ void <init>(Level,Player,double,double,double)
+ void <init>(Level,Player,int,int)
- void recreateFromPacket(ClientboundAddEntityPacket)
+ void remove()
- void remove(Entity$RemovalReason)
- void setOwner(Entity)
```

</details>


<details>
<summary>
net.minecraft.world.entity.projectile.LlamaSpit
</summary>

```diff
+ Packet getAddEntityPacket()
+ void <init>(Level,double,double,double,double,double,double)
- void recreateFromPacket(ClientboundAddEntityPacket)
```

</details>



<details>
<summary>
net.minecraft.world.entity.projectile.ThrowableProjectile
</summary>

```diff
+ Packet getAddEntityPacket()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
+ void <init>(Level,double,double,double)
```

</details>

<details>
<summary>
net.minecraft.world.entity.projectile.WitherSkull
</summary>

```diff
+ void <init>(Level,double,double,double,double,double,double)
```

</details>









<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
- ItemStack getPickResult()
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
- void clearContainer(Player,Container)
+ void clearContainer(Player,Level,Container)
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
net.minecraft.world.item.Item
</summary>

```diff
- boolean canFitInsideContainerItems()
+ boolean is(Tag)
- boolean isBarVisible(ItemStack)
- boolean overrideOtherStackedOnMe(ItemStack,ItemStack,ClickAction,Inventory)
- boolean overrideStackedOnOther(ItemStack,ItemStack,ClickAction,Inventory)
- int getBarColor(ItemStack)
- int getBarWidth(ItemStack)
- SoundEvent getEquipSound()
```

</details>



<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- boolean is(Item)
- boolean is(Tag)
- boolean isBarVisible()
- boolean isSameItemSameTags(ItemStack,ItemStack)
- boolean overrideOtherStackedOnMe(ItemStack,ClickAction,Inventory)
- boolean overrideStackedOnOther(ItemStack,ClickAction,Inventory)
- int getBarColor()
- int getBarWidth()
- SoundEvent getEquipSound()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemUtils
</summary>

```diff
- InteractionResultHolder startUsingInstantly(Level,Player,InteractionHand)
+ InteractionResultHolder useDrink(Level,Player,InteractionHand)
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
net.minecraft.world.level.PathNavigationRegion
</summary>

```diff
- int getMinSection()
- int getSectionsCount()
```

</details>













<details>
<summary>
net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
</summary>

```diff
- Biome getPrimaryBiome(int,int)
```

</details>



















<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
+ boolean hasAnalogOutputSignal(BlockState)
+ boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
- boolean shouldHandleRain(Level,BlockPos)
+ int getAnalogOutputSignal(BlockState,Level,BlockPos)
+ InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
+ void <clinit>()
+ void createBlockStateDefinition(StateDefinition$Builder)
+ void entityInside(BlockState,Level,BlockPos,Entity)
- void handleRain(BlockState,Level,BlockPos)
+ void handleRain(Level,BlockPos)
+ void setWaterLevel(Level,BlockPos,BlockState,int)
+ VoxelShape getInteractionShape(BlockState,BlockGetter,BlockPos)
+ VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
- void tickEntity(Level,BlockPos,BlockState,DaylightDetectorBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DetectorRailBlock
</summary>

```diff
- boolean lambda$checkPressed$0(Entity)
- boolean lambda$getAnalogOutputSignal$1(Entity)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
- void tick(BlockState,ServerLevel,BlockPos,Random)
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
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
- boolean canAttachTo(BlockState)
+ boolean canAttachToBlock(Block)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.MushroomBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,Supplier)
+ void <init>(BlockBehaviour$Properties)
```

</details>













<details>
<summary>
net.minecraft.world.level.block.RedStoneWireBlock
</summary>

```diff
- void lambda$static$0(Vector3f[])
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
net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
</summary>

```diff
- boolean burn(Recipe,NonNullList,int)
- boolean canBurn(Recipe,NonNullList,int)
+ boolean canBurn(Recipe)
+ int getTotalCookTime()
- int getTotalCookTime(Level,RecipeType,Container)
+ List getRecipesToAwardAndPopExperience(Level,Vec3)
- List getRecipesToAwardAndPopExperience(ServerLevel,Vec3)
- void <init>(BlockEntityType,BlockPos,BlockState,RecipeType)
+ void <init>(BlockEntityType,RecipeType)
+ void awardUsedRecipesAndPopExperience(Player)
- void awardUsedRecipesAndPopExperience(ServerPlayer)
+ void burn(Recipe)
+ void createExperience(Level,Vec3,int,float)
- void createExperience(ServerLevel,Vec3,int,float)
+ void lambda$getRecipesToAwardAndPopExperience$1(List,Level,Vec3,Object2IntMap$Entry,Recipe)
- void lambda$getRecipesToAwardAndPopExperience$1(List,ServerLevel,Vec3,Object2IntMap$Entry,Recipe)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void serverTick(Level,BlockPos,BlockState,AbstractFurnaceBlockEntity)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerBlockEntity
</summary>

```diff
+ BlockState lambda$getItem$0(BlockState)
- DyeColor getBaseColor()
+ DyeColor getBaseColor(Supplier)
- ItemStack getItem()
+ ItemStack getItem(BlockState)
+ void <init>()
- void <init>(BlockPos,BlockState,DyeColor)
- void <init>(BlockPos,BlockState)
+ void <init>(DyeColor)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BannerPattern$Builder
</summary>

```diff
- BannerPattern$Builder addPattern(Pair)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BrewingStandBlockEntity
</summary>

```diff
+ boolean isBrewable()
- boolean isBrewable(NonNullList)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void doBrew()
- void doBrew(Level,BlockPos,NonNullList)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void serverTick(Level,BlockPos,BlockState,BrewingStandBlockEntity)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CampfireBlockEntity
</summary>

```diff
+ ItemStack lambda$cook$0(Container,CampfireCookingRecipe)
- ItemStack lambda$cookTick$0(Container,CampfireCookingRecipe)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void cook()
- void cookTick(Level,BlockPos,BlockState,CampfireBlockEntity)
- void cooldownTick(Level,BlockPos,BlockState,CampfireBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void makeParticles()
- void particleTick(Level,BlockPos,BlockState,CampfireBlockEntity)
+ void tick()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CommandBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void clearRemoved()
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.ConduitBlockEntity
</summary>

```diff
+ AABB getDestroyRangeAABB()
- AABB getDestroyRangeAABB(BlockPos)
+ boolean lambda$findDestroyTarget$1(LivingEntity)
- boolean lambda$findDestroyTarget$1(UUID,LivingEntity)
+ boolean updateShape()
- boolean updateShape(Level,BlockPos,List)
+ LivingEntity findDestroyTarget()
- LivingEntity findDestroyTarget(Level,BlockPos,UUID)
+ void <init>()
+ void <init>(BlockEntityType)
- void <init>(BlockPos,BlockState)
+ void animationTick()
- void animationTick(Level,BlockPos,List,Entity,int)
+ void applyEffects()
- void applyEffects(Level,BlockPos,List)
- void clientTick(Level,BlockPos,BlockState,ConduitBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void playSound(SoundEvent)
- void serverTick(Level,BlockPos,BlockState,ConduitBlockEntity)
+ void setActive(boolean)
+ void tick()
+ void updateClientTarget()
- void updateClientTarget(Level,BlockPos,ConduitBlockEntity)
+ void updateDestroyTarget()
- void updateDestroyTarget(Level,BlockPos,BlockState,List,ConduitBlockEntity)
- void updateHunting(ConduitBlockEntity,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.FurnaceBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.HopperBlockEntity
</summary>

```diff
+ boolean ejectItems()
- boolean ejectItems(Level,BlockPos,BlockState,Container)
+ Boolean lambda$entityInside$5(Entity)
- boolean lambda$entityInside$5(HopperBlockEntity,Entity)
- boolean lambda$pushItemsTick$0(Level,HopperBlockEntity)
+ Boolean lambda$tick$0()
+ boolean suckInItems(Hopper)
- boolean suckInItems(Level,Hopper)
- boolean tryMoveItems(Level,BlockPos,BlockState,HopperBlockEntity,BooleanSupplier)
+ boolean tryMoveItems(Supplier)
+ Container getAttachedContainer()
- Container getAttachedContainer(Level,BlockPos,BlockState)
+ Container getSourceContainer(Hopper)
- Container getSourceContainer(Level,Hopper)
+ List getItemsAtAndAbove(Hopper)
- List getItemsAtAndAbove(Level,Hopper)
+ Stream lambda$getItemsAtAndAbove$4(Hopper,AABB)
- Stream lambda$getItemsAtAndAbove$4(Level,Hopper,AABB)
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void entityInside(Entity)
- void entityInside(Level,BlockPos,BlockState,Entity,HopperBlockEntity)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void pushItemsTick(Level,BlockPos,BlockState,HopperBlockEntity)
+ void tick()
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.LecternBlockEntity
</summary>

```diff
+ void <init>()
- void <init>(BlockPos,BlockState)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
</summary>

```diff
- void <init>(BlockEntityType,BlockPos,BlockState)
+ void <init>(BlockEntityType)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
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
net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
</summary>

```diff
+ BlockPos findExitPosition()
- BlockPos findExitPosition(Level,BlockPos)
- BlockPos findOrCreateValidTeleportPos(ServerLevel,BlockPos)
- boolean isChunkEmpty(ServerLevel,Vec3)
- Vec3 findExitPortalXZPosTentative(ServerLevel,BlockPos)
+ void <init>()
- void <init>(BlockPos,BlockState)
- void beamAnimationTick(Level,BlockPos,BlockState,TheEndGatewayBlockEntity)
+ void createExitPortal(ServerLevel,BlockPos)
+ void findExitPortal(ServerLevel)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
- void spawnGatewayPortal(ServerLevel,BlockPos,EndGatewayConfiguration)
+ void teleportEntity(Entity)
- void teleportEntity(Level,BlockPos,BlockState,Entity,TheEndGatewayBlockEntity)
- void teleportTick(Level,BlockPos,BlockState,TheEndGatewayBlockEntity)
+ void tick()
+ void triggerCooldown()
- void triggerCooldown(Level,BlockPos,BlockState,TheEndGatewayBlockEntity)
```

</details>









<details>
<summary>
net.minecraft.world.level.block.piston.PistonMovingBlockEntity
</summary>

```diff
+ AABB moveByPositionAndProgress(AABB)
- AABB moveByPositionAndProgress(BlockPos,AABB,PistonMovingBlockEntity)
+ void <init>()
- void <init>(BlockPos,BlockState,BlockState,Direction,boolean,boolean)
- void <init>(BlockPos,BlockState)
+ void <init>(BlockState,Direction,boolean,boolean)
- void fixEntityWithinPistonBase(BlockPos,Entity,Direction,double)
+ void fixEntityWithinPistonBase(Entity,Direction,double)
+ void load(BlockState,CompoundTag)
- void load(CompoundTag)
+ void moveCollidedEntities(float)
- void moveCollidedEntities(Level,BlockPos,float,PistonMovingBlockEntity)
+ void moveStuckEntities(float)
- void moveStuckEntities(Level,BlockPos,float,PistonMovingBlockEntity)
+ void tick()
- void tick(Level,BlockPos,BlockState,PistonMovingBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonStructureResolver
</summary>

```diff
+ boolean canStickToEachOther(Block,Block)
- boolean canStickToEachOther(BlockState,BlockState)
+ boolean isSticky(Block)
- boolean isSticky(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean isEntityBlock()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- BlockEntityTicker getTicker(Level,BlockEntityType)
- boolean hasBlockEntity()
```

</details>





































<details>
<summary>
net.minecraft.world.level.chunk.LevelChunk
</summary>

```diff
- Block lambda$unpackTicks$7(BlockPos)
+ Block lambda$unpackTicks$9(BlockPos)
- boolean access$200(LevelChunk,BlockPos)
- boolean isInLevel()
- boolean isPositionInSection(int,BlockPos)
- boolean isTicking(BlockPos)
- boolean lambda$getLights$4(BlockPos)
+ boolean lambda$getLights$6(BlockPos)
- boolean lambda$replaceWithPacketData$3(int,BlockEntity)
+ boolean lambda$replaceWithPacketData$4(BlockPos)
+ boolean lambda$replaceWithPacketData$5(int,BlockPos)
+ ClassInstanceMultiMap[] getEntitySections()
+ Entity lambda$new$0(Entity)
+ Fluid lambda$unpackTicks$10(BlockPos)
- Fluid lambda$unpackTicks$8(BlockPos)
- Heightmap lambda$getOrCreateHeightmapUnprimed$0(Heightmap$Types)
+ Heightmap lambda$getOrCreateHeightmapUnprimed$1(Heightmap$Types)
- int getMinSection()
- int getSectionsCount()
- Level access$300(LevelChunk)
- LevelChunk$RebindableTickingBlockEntityWrapper lambda$updateBlockEntityTicker$9(BlockEntity,BlockEntityTicker,BlockPos,LevelChunk$RebindableTickingBlockEntityWrapper)
- Logger access$400()
- LongSet lambda$addReferenceForFeature$6(StructureFeature)
+ LongSet lambda$addReferenceForFeature$8(StructureFeature)
- LongSet lambda$getReferencesForFeature$5(StructureFeature)
+ LongSet lambda$getReferencesForFeature$7(StructureFeature)
- String lambda$getBlockState$1(int,int,int)
+ String lambda$getBlockState$2(int,int,int)
- String lambda$getFluidState$2(int,int,int)
+ String lambda$getFluidState$3(int,int,int)
- TickingBlockEntity createTicker(BlockEntity,BlockEntityTicker)
+ void <init>(Level,ProtoChunk)
- void <init>(ServerLevel,ProtoChunk,Consumer)
- void addAndRegisterBlockEntity(BlockEntity)
+ void addBlockEntity(BlockEntity)
+ void getEntities(Entity,AABB,List,Predicate)
+ void getEntities(EntityType,AABB,List,Predicate)
+ void getEntitiesOfClass(Class,AABB,List,Predicate)
- void invalidateAllBlockEntities()
- void onBlockEntityRemove(BlockEntity)
- void registerAllBlockEntitiesAfterLevelLoad()
- void removeBlockEntityTicker(BlockPos)
+ void removeEntity(Entity,int)
+ void removeEntity(Entity)
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
net.minecraft.world.level.chunk.storage.RegionFile
</summary>

```diff
- int getTimestamp()
- void clear(ChunkPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
- void <init>(File,Function,Function,DataFixer,DataFixTypes,boolean,LevelHeightAccessor)
+ void <init>(File,Function,Function,DataFixer,DataFixTypes,boolean)
```

</details>












<details>
<summary>
net.minecraft.world.level.levelgen.feature.IcebergFeature
</summary>

```diff
+ boolean isIcebergBlock(Block)
- boolean isIcebergState(BlockState)
```

</details>































































<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- int getLayerIndex(int)
- int getMinSection()
- int getSectionsCount()
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.placement.DecorationContext
</summary>

```diff
- int getMinSection()
- int getSectionsCount()
```

</details>





















































































































<details>
<summary>
net.minecraft.world.level.lighting.SkyLightSectionStorage
</summary>

```diff
+ boolean hasLightSource(long)
- int getLightValue(long,boolean)
```

</details>














































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapBanner
</summary>

```diff
+ BlockState lambda$fromWorld$0(BlockGetter,BlockPos)
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
net.minecraft.world.level.storage.ServerLevelData
</summary>

```diff
- void fillCrashReportCategory(CrashReportCategory,LevelHeightAccessor)
+ void fillCrashReportCategory(CrashReportCategory)
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
+ void <init>(boolean,double,Item,Predicate)
- void <init>(boolean,double,ItemStack,Predicate)
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
+ net.minecraft.client.model.dragon.DragonHeadModel
- net.minecraft.client.model.dragon.package-info
- net.minecraft.client.model.geom.builders.CubeDefinition
- net.minecraft.client.model.geom.builders.CubeListBuilder
- net.minecraft.client.model.geom.builders.MaterialDefinition
- net.minecraft.client.model.geom.builders.package-info
- net.minecraft.client.model.geom.builders.PartDefinition
- net.minecraft.client.model.geom.LayerDefinitions
- net.minecraft.client.model.geom.ModelLayers
+ net.minecraft.client.model.geom.ModelPart
- net.minecraft.client.model.geom.ModelPart$Cube
+ net.minecraft.client.model.geom.ModelPart$Polygon
- net.minecraft.client.model.geom.ModelPart$Vertex
+ net.minecraft.client.model.geom.package-info
- net.minecraft.client.model.geom.PartNames
- net.minecraft.client.model.HierarchicalModel
+ net.minecraft.client.model.HoglinModel
- net.minecraft.client.model.HorseModel
+ net.minecraft.client.model.HumanoidHeadModel
- net.minecraft.client.model.package-info
- net.minecraft.client.model.SlimeModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.StriderModel
+ net.minecraft.client.model.TridentModel
- net.minecraft.client.model.TropicalFishModelA
+ net.minecraft.client.model.TropicalFishModelB
- net.minecraft.client.model.TurtleModel
+ net.minecraft.client.model.VexModel
- net.minecraft.client.model.VillagerHeadModel
+ net.minecraft.client.model.VillagerModel
- net.minecraft.client.model.WitchModel
+ net.minecraft.client.model.WitherBossModel
- net.minecraft.client.model.WolfModel
+ net.minecraft.client.model.ZombieModel
- net.minecraft.client.model.ZombieVillagerModel
+ net.minecraft.client.multiplayer.ClientAdvancements
- net.minecraft.client.multiplayer.ClientAdvancements$Listener
+ net.minecraft.client.multiplayer.ClientChunkCache
- net.minecraft.client.multiplayer.ClientChunkCache$1
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
- net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$1
+ net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
- net.minecraft.client.particle.HeartParticle$Provider
+ net.minecraft.client.particle.HugeExplosionParticle
- net.minecraft.client.particle.HugeExplosionParticle$1
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$1
- net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
+ net.minecraft.client.particle.ItemPickupParticle
- net.minecraft.client.particle.LargeSmokeParticle
+ net.minecraft.client.particle.LargeSmokeParticle$Provider
- net.minecraft.client.particle.LavaParticle
+ net.minecraft.client.particle.LavaParticle$1
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$1
+ net.minecraft.client.particle.MobAppearanceParticle$Provider
- net.minecraft.client.particle.NoRenderParticle
+ net.minecraft.client.particle.NoteParticle
- net.minecraft.client.particle.NoteParticle$1
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.ParticleDescription
- net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.ParticleEngine$1
- net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
+ net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
- net.minecraft.client.particle.ParticleProvider
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.particle.PlayerCloudParticle
+ net.minecraft.client.particle.PlayerCloudParticle$1
- net.minecraft.client.particle.PlayerCloudParticle$Provider
+ net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
- net.minecraft.client.particle.PortalParticle
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.ReversePortalParticle$1
- net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
+ net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SmokeParticle
+ net.minecraft.client.particle.SmokeParticle$Provider
- net.minecraft.client.particle.SoulParticle
+ net.minecraft.client.particle.SoulParticle$1
- net.minecraft.client.particle.SoulParticle$Provider
+ net.minecraft.client.particle.SpellParticle
- net.minecraft.client.particle.SpellParticle$1
+ net.minecraft.client.particle.SpellParticle$AmbientMobProvider
- net.minecraft.client.particle.SpellParticle$InstantProvider
+ net.minecraft.client.particle.SpellParticle$MobProvider
- net.minecraft.client.particle.SpellParticle$Provider
+ net.minecraft.client.particle.SpellParticle$WitchProvider
- net.minecraft.client.particle.SpitParticle
+ net.minecraft.client.particle.SpitParticle$1
- net.minecraft.client.particle.SpitParticle$Provider
+ net.minecraft.client.particle.SplashParticle
- net.minecraft.client.particle.SplashParticle$1
+ net.minecraft.client.particle.SplashParticle$Provider
- net.minecraft.client.particle.SpriteSet
+ net.minecraft.client.particle.SquidInkParticle
- net.minecraft.client.particle.SquidInkParticle$1
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
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$1
- net.minecraft.client.particle.WakeParticle$Provider
+ net.minecraft.client.particle.WaterCurrentDownParticle
- net.minecraft.client.particle.WaterCurrentDownParticle$1
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.renderer.banner.package-info
+ net.minecraft.client.renderer.BiomeColors
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
- net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
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
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
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
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$1
+ net.minecraft.client.renderer.FaceInfo$Constants
- net.minecraft.client.renderer.FaceInfo$VertexInfo
+ net.minecraft.client.renderer.FogRenderer
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.GameRenderer
- net.minecraft.client.renderer.GpuWarnlistManager
+ net.minecraft.client.renderer.GpuWarnlistManager$1
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemProperties$2
+ net.minecraft.client.renderer.item.ItemProperties$CompassWobble
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
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
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.animation.package-info
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
- net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.LanguageMetadataSection
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
- net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.BakedModel
- net.minecraft.client.resources.model.BlockModelRotation
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
+ net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
- net.minecraft.client.resources.model.ModelManager
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
+ net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
- net.minecraft.client.resources.package-info
+ net.minecraft.client.resources.PackResourcesAdapterV4
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$SkinTextureCallback
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
+ net.minecraft.client.resources.sounds.package-info
- net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
+ net.minecraft.client.resources.sounds.SimpleSoundInstance
- net.minecraft.client.resources.sounds.Sound
+ net.minecraft.client.resources.sounds.Sound$Type
- net.minecraft.client.resources.sounds.SoundEventRegistration
+ net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
- net.minecraft.client.resources.sounds.SoundInstance
+ net.minecraft.client.resources.sounds.SoundInstance$Attenuation
- net.minecraft.client.resources.sounds.TickableSoundInstance
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- net.minecraft.client.resources.SplashManager
+ net.minecraft.client.resources.TextureAtlasHolder
- net.minecraft.client.searchtree.MutableSearchTree
- net.minecraft.client.searchtree.package-info
+ net.minecraft.client.searchtree.ReloadableIdSearchTree
- net.minecraft.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
+ net.minecraft.client.searchtree.ReloadableSearchTree
- net.minecraft.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
+ net.minecraft.client.searchtree.SuffixArray$1
+ net.minecraft.client.server.IntegratedPlayerList
- net.minecraft.client.server.IntegratedServer
+ net.minecraft.client.server.LanServer
- net.minecraft.client.server.LanServerDetection
+ net.minecraft.client.server.LanServerDetection$LanServerDetector
- net.minecraft.client.server.LanServerDetection$LanServerList
+ net.minecraft.client.server.LanServerPinger
- net.minecraft.client.server.package-info
+ net.minecraft.client.skins.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$1
+ net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
- net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
+ net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
- net.minecraft.client.sounds.SoundBufferLibrary
+ net.minecraft.client.sounds.SoundEngine
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
- net.minecraft.client.tutorial.CompletedTutorialStepInstance
+ net.minecraft.client.tutorial.CraftPlanksTutorialStep
- net.minecraft.client.tutorial.FindTreeTutorialStepInstance
+ net.minecraft.client.tutorial.MovementTutorialStepInstance
- net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
+ net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
- net.minecraft.client.tutorial.Tutorial
+ net.minecraft.client.tutorial.Tutorial$1
- net.minecraft.client.tutorial.Tutorial$TimedToast
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$1
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.blocks.BlockInput
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$Result
- net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.blocks.BlockStateArgument
- net.minecraft.commands.arguments.blocks.BlockStateParser
+ net.minecraft.commands.arguments.blocks.package-info
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
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
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
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
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
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
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CommandFunction
- net.minecraft.commands.CommandFunction$CacheableFunction
+ net.minecraft.commands.CommandFunction$CommandEntry
- net.minecraft.commands.CommandFunction$Entry
+ net.minecraft.commands.CommandFunction$FunctionEntry
- net.minecraft.commands.CommandRuntimeException
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.SharedSuggestionProvider
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
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
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$23
- net.minecraft.core.dispenser.DispenseItemBehavior$24
+ net.minecraft.core.dispenser.DispenseItemBehavior$25
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
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
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BuiltinRegistries
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLoot
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.FishingLoot
- net.minecraft.data.loot.GiftLoot
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.PiglinBarterLoot
- net.minecraft.data.Main
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$1
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$1
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
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
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
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagTypes
- net.minecraft.nbt.TagVisitor
- net.minecraft.network.chat.BaseComponent
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.TextComponent
- net.minecraft.network.chat.TranslatableComponent
+ net.minecraft.network.chat.TranslatableFormatException
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$PacketHolder
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.ConnectionProtocol$1
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
+ net.minecraft.network.protocol.game.ClientGamePacketListener
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
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
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
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
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
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataPackCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryLookupCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$1
- net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
+ net.minecraft.resources.RegistryWriteOps
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$1
- net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
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
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateBiomeCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
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
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.ConsoleInputSource
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$1
+ net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.Eula
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FeatureSimulator
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
- net.minecraft.server.network.package-info
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
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.TextFilter
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$1
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.FilePackResources
- net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackResources
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
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
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
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
+ net.minecraft.tags.TagContainer
- net.minecraft.tags.TagContainer$1
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
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
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HeapDumper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InsensitiveStringMap
- net.minecraft.util.IntRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LimitedCapacityList
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.Mth
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$2
- net.minecraft.util.StringUtil
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.AgableMob$AgableMobGroupData
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
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
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
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
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse
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
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
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
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$1
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$1
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$1
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTemptGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.BossMob
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
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
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
- net.minecraft.world.entity.package-info
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
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$1
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.AnvilMenu$1
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
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
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
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeableArmorItem
- net.minecraft.world.item.DyeableHorseArmorItem
+ net.minecraft.world.item.DyeableLeatherItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
- net.minecraft.world.item.EggItem
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.ExperienceBottleItem
+ net.minecraft.world.item.FireChargeItem
- net.minecraft.world.item.FireworkRocketItem
+ net.minecraft.world.item.FireworkRocketItem$Shape
- net.minecraft.world.item.FireworkStarItem
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
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlayerHeadItem
- net.minecraft.world.item.PotionItem
+ net.minecraft.world.item.ProjectileWeaponItem
- net.minecraft.world.item.ProjectileWeaponItem$Type
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
- net.minecraft.world.item.SpawnEggItem
+ net.minecraft.world.item.SpectralArrowItem
- net.minecraft.world.item.SplashPotionItem
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
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
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
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
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
+ net.minecraft.world.level.block.PotatoBlock
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
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
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
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
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
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.WaterCauldronBlock
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
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
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
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.package-info
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
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.GeodeFeature
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
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
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
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
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
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.package-info
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
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.newbiome.area.Area
- net.minecraft.world.level.newbiome.area.AreaFactory
+ net.minecraft.world.level.newbiome.area.LazyArea
- net.minecraft.world.level.newbiome.area.package-info
+ net.minecraft.world.level.newbiome.context.BigContext
- net.minecraft.world.level.newbiome.context.Context
+ net.minecraft.world.level.newbiome.context.LazyAreaContext
- net.minecraft.world.level.newbiome.context.package-info
+ net.minecraft.world.level.newbiome.layer.AddDeepOceanLayer
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$CoolWarm
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$HeatIce
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- net.minecraft.world.level.newbiome.layer.AddIslandLayer
+ net.minecraft.world.level.newbiome.layer.AddMushroomIslandLayer
- net.minecraft.world.level.newbiome.layer.AddSnowLayer
+ net.minecraft.world.level.newbiome.layer.BiomeEdgeLayer
- net.minecraft.world.level.newbiome.layer.BiomeInitLayer
+ net.minecraft.world.level.newbiome.layer.IslandLayer
- net.minecraft.world.level.newbiome.layer.Layer
+ net.minecraft.world.level.newbiome.layer.LayerBiomes
- net.minecraft.world.level.newbiome.layer.Layers
+ net.minecraft.world.level.newbiome.layer.Layers$Category
- net.minecraft.world.level.newbiome.layer.OceanLayer
+ net.minecraft.world.level.newbiome.layer.OceanMixerLayer
+ net.minecraft.world.level.newbiome.layer.package-info
- net.minecraft.world.level.newbiome.layer.RareBiomeLargeLayer
+ net.minecraft.world.level.newbiome.layer.RareBiomeSpotLayer
- net.minecraft.world.level.newbiome.layer.RegionHillsLayer
+ net.minecraft.world.level.newbiome.layer.RemoveTooMuchOceanLayer
- net.minecraft.world.level.newbiome.layer.RiverInitLayer
+ net.minecraft.world.level.newbiome.layer.RiverLayer
- net.minecraft.world.level.newbiome.layer.RiverMixerLayer
+ net.minecraft.world.level.newbiome.layer.ShoreLayer
- net.minecraft.world.level.newbiome.layer.SmoothLayer
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer0
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer1
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer2
+ net.minecraft.world.level.newbiome.layer.traits.BishopTransformer
- net.minecraft.world.level.newbiome.layer.traits.C0Transformer
+ net.minecraft.world.level.newbiome.layer.traits.C1Transformer
- net.minecraft.world.level.newbiome.layer.traits.CastleTransformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionOffset0Transformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionOffset1Transformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionTransformer
+ net.minecraft.world.level.newbiome.layer.traits.package-info
- net.minecraft.world.level.newbiome.layer.traits.PixelTransformer
+ net.minecraft.world.level.newbiome.layer.ZoomLayer
- net.minecraft.world.level.newbiome.layer.ZoomLayer$1
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
+ net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.ConstantIntValue
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
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
- net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$1
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$1
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$DefaultSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
- net.minecraft.world.level.storage.loot.IntLimiter
+ net.minecraft.world.level.storage.loot.IntLimiter$1
- net.minecraft.world.level.storage.loot.IntLimiter$Serializer
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
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$1
+ net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$1
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$1
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.RandomIntGenerator
+ net.minecraft.world.level.storage.loot.RandomIntGenerators
- net.minecraft.world.level.storage.loot.RandomValueBounds
+ net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
- net.minecraft.world.level.storage.loot.Serializer
+ net.minecraft.world.level.storage.loot.SerializerType
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.threaded.package-info
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$1
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
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
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
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
net.minecraft.CrashReportCategory +5M -5M
```
```
net.minecraft.Util +1M
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance +1M -1M
```
```
XXX.minecraft.client.Minecraft$1 -1P
```
```
XXX.screens.inventory.EnchantmentScreen +1M | +1P -1P
```
```
XXX.screens.inventory.LoomScreen +1M
```
```
XXX.client.model.ArmorStandModel +2M -2M | +2P -2P
```
```
XXX.client.model.BeeModel +2M -1M | -1P
```
```
XXX.client.model.BoatModel +3M -3M | +2P -1P
```
```
XXX.client.model.CatModel +1M -1M
```
```
XXX.client.model.ChickenModel +2M -1M | +4P -4P
```
```
XXX.client.model.CowModel +2M -1M
```
```
XXX.client.model.DolphinModel +3M -2M | +1P
```
```
XXX.client.model.ElytraModel +2M -1M
```
```
XXX.client.model.EndermiteModel +4M -2M | +1P -1P
```
```
XXX.client.model.EvokerFangsModel +3M -2M | +1P
```
```
XXX.client.model.GhastModel +4M -2M | +1P -1P
```
```
XXX.client.model.GuardianModel +8M -2M | +1P
```
```
XXX.client.model.IllagerModel +3M -2M | +1P -1P
```
```
XXX.client.model.LavaSlimeModel +5M -3M | +1P -2P
```
```
XXX.client.model.LlamaSpitModel +3M -3M | +1P -1P
```
```
XXX.client.model.Model -2M | -2P
```
```
XXX.client.model.OcelotModel +2M -1M | +4P -4P
```
```
XXX.client.model.ParrotModel +3M -3M | +5P -7P
```
```
XXX.client.model.PigModel +2M -2M
```
```
XXX.client.model.PlayerModel +3M -3M | +1P -1P
```
```
XXX.client.model.PufferfishBigModel +3M -2M | +3P -13P
```
```
XXX.client.model.PufferfishSmallModel +3M -2M | +3P -6P
```
```
XXX.client.model.RabbitModel +2M -2M | +8P -8P
```
```
XXX.client.model.SalmonModel +3M -2M | +1P -4P
```
```
XXX.client.model.SheepModel +2M -1M
```
```
XXX.client.model.ShulkerBulletModel +3M -2M | +1P
```
```
XXX.client.model.SilverfishModel +7M -3M | +1P -2P
```
```
XXX.client.model.SkullModel +4M -2M | +1P
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
XXX.renderer.entity.AbstractHorseRenderer +1M -1M
```
```
XXX.renderer.entity.AreaEffectCloudRenderer +1M -1M
```
```
XXX.renderer.entity.ArrowRenderer +1M -1M
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
XXX.minecraft.core.BlockPos -1M
```
```
XXX.minecraft.core.SectionPos +3M -1M
```
```
XXX.data.worldgen.Features +2P
```
```
XXX.gametest.framework.GameTestBatch +2M -1M | +1P
```
```
XXX.gametest.framework.GameTestBatchRunner$1 +2M -1M | +3P
```
```
XXX.gametest.framework.GameTestRunner +3M -18M | -1P
```
```
XXX.minecraft.nbt.StringTag +1M -1M
```
```
XXX.datafix.fixes.JigsawRotationFix +1P -1P
```
```
XXX.datafix.schemas.V99 +5M -4M
```
```
XXX.world.entity.Entity +31M -13M | +5P -8P
```
```
XXX.world.entity.ExperienceOrb +8M | +1P -3P
```
```
XXX.world.entity.LivingEntity +1M -1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.world.entity.NeutralMob +1M -1M
```
```
XXX.ai.behavior.BehaviorUtils +5M -4M
```
```
XXX.ai.behavior.GiveGiftToHero +1P -1P
```
```
XXX.ai.behavior.VillagerMakeLove +1M -1M
```
```
XXX.ai.goal.AvoidEntityGoal +1M
```
```
XXX.ai.sensing.AdultSensor +6M -6M
```
```
XXX.world.inventory.MerchantMenu -1M
```
```
XXX.world.inventory.PlayerEnderChestContainer +1M
```
```
XXX.world.item.ArmorItem +1M
```
```
XXX.world.item.BlockItem +1M
```
```
XXX.item.crafting.Recipe +2M
```
```
XXX.item.crafting.ShapedRecipe +4M -1M
```
```
XXX.world.level.BlockGetter -1M
```
```
XXX.world.level.EmptyBlockGetter +2M
```
```
XXX.world.level.Level +10M -13M | +5P -5P
```
```
XXX.world.level.LevelAccessor +1M -1M
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
XXX.level.block.DropperBlock +1M -1M
```
```
XXX.level.block.EndGatewayBlock +2M -1M
```
```
XXX.level.block.TrappedChestBlock +1M -1M
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
XXX.level.chunk.ProtoTickList +2M -2M | +1P
```
```
XXX.phys.shapes.Shapes +1M
```
```
XXX.phys.shapes.VoxelShape +1M -2M
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
- Object getRandom(List,Random)
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
net.minecraft.client.gui.screens.inventory.EnchantmentScreen
</summary>

```diff
- void init()
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
net.minecraft.client.model.BeeModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.BoatModel
</summary>

```diff
- LayerDefinition createBodyModel()
+ ModelPart makePaddle(boolean)
+ void <init>()
- void <init>(ModelPart)
+ void animatePaddle(Boat,int,float)
- void animatePaddle(Boat,int,ModelPart,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.CatModel
</summary>

```diff
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.ChickenModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>

<details>
<summary>
net.minecraft.client.model.CowModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.DolphinModel
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
net.minecraft.client.model.ElytraModel
</summary>

```diff
- LayerDefinition createLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.EndermiteModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
- String createSegmentName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.EvokerFangsModel
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
net.minecraft.client.model.GhastModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
- String createTentacleName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.GuardianModel
</summary>

```diff
- float getSpikeOffset(int,float,float)
- float getSpikeX(int,float,float)
- float getSpikeY(int,float,float)
- float getSpikeZ(int,float,float)
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
- String createSpikeName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>

<details>
<summary>
net.minecraft.client.model.IllagerModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
+ void <init>(float,float,int,int)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.LavaSlimeModel
</summary>

```diff
+ ImmutableList parts()
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart lambda$new$0(ModelPart,int)
- ModelPart root()
- String getSegmentName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>

<details>
<summary>
net.minecraft.client.model.LlamaSpitModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
+ void <init>()
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.Model
</summary>

```diff
+ void accept(ModelPart)
+ void accept(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.OcelotModel
</summary>

```diff
- MeshDefinition createBodyMesh(CubeDeformation)
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.ParrotModel
</summary>

```diff
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart root()
+ void <init>()
- void <init>(ModelPart)
+ void lambda$renderOnShoulder$0(PoseStack,VertexConsumer,int,int,ModelPart)
```

</details>

<details>
<summary>
net.minecraft.client.model.PigModel
</summary>

```diff
- LayerDefinition createBodyLayer(CubeDeformation)
+ void <init>()
+ void <init>(float)
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.PlayerModel
</summary>

```diff
- boolean lambda$new$0(ModelPart)
- MeshDefinition createMesh(CubeDeformation,boolean)
+ void <init>(float,boolean)
- void <init>(ModelPart,boolean)
+ void accept(ModelPart)
+ void accept(Object)
```

</details>
<details>
<summary>
net.minecraft.client.model.PufferfishBigModel
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
net.minecraft.client.model.PufferfishSmallModel
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
net.minecraft.client.model.RabbitModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
+ void setRotation(ModelPart,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.SalmonModel
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
net.minecraft.client.model.SheepModel
</summary>

```diff
- LayerDefinition createBodyLayer()
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShulkerBulletModel
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
net.minecraft.client.model.SilverfishModel
</summary>

```diff
+ ImmutableList parts()
+ Iterable parts()
- LayerDefinition createBodyLayer()
- ModelPart lambda$new$0(ModelPart,int)
- ModelPart lambda$new$1(ModelPart,int)
- ModelPart root()
- String getLayerName(int)
- String getSegmentName(int)
+ void <init>()
- void <init>(ModelPart)
```

</details>
<details>
<summary>
net.minecraft.client.model.SkullModel
</summary>

```diff
- LayerDefinition createHumanoidHeadLayer()
- LayerDefinition createMobHeadLayer()
- MeshDefinition createHeadModel()
+ void <init>()
+ void <init>(int,int,int,int)
- void <init>(ModelPart)
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
net.minecraft.client.renderer.entity.AbstractHorseRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher,HorseModel,float)
- void <init>(EntityRendererProvider$Context,HorseModel,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ArrowRenderer
</summary>

```diff
+ void <init>(EntityRenderDispatcher)
- void <init>(EntityRendererProvider$Context)
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
net.minecraft.core.BlockPos
</summary>

```diff
+ boolean isOutsideBuildHeight(long)
```

</details>
















<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- int posToSectionCoord(double)
- int sectionToBlockCoord(int,int)
- Stream aroundChunk(ChunkPos,int,int,int)
+ Stream aroundChunk(ChunkPos,int)
```

</details>






















<details>
<summary>
net.minecraft.gametest.framework.GameTestBatch
</summary>

```diff
- void <init>(String,Collection,Consumer,Consumer)
+ void <init>(String,Collection,Consumer)
- void runAfterBatchFunction(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestBatchRunner$1
</summary>

```diff
- void <init>(GameTestBatchRunner,MultipleTestTracker,GameTestBatch,int)
+ void <init>(GameTestBatchRunner)
- void testCompleted()
```

</details>



<details>
<summary>
net.minecraft.gametest.framework.GameTestRunner
</summary>

```diff
- boolean lambda$clearAllTests$4(ServerLevel,BlockPos)
+ boolean lambda$clearAllTests$7(ServerLevel,BlockPos)
+ boolean lambda$say$5(ServerPlayer)
+ GameTestBatch lambda$null$2(String,MutableInt,Collection,Consumer,List)
- GameTestBatch lambda$null$2(String,MutableInt,Consumer,Consumer,List)
+ ItemStack createBook(String,boolean,String)
+ void <clinit>()
+ void access$000(GameTestInfo,Block)
+ void access$100(GameTestInfo)
+ void access$200(GameTestInfo,String)
+ void access$300(GameTestInfo)
- void lambda$clearAllTests$5(ServerLevel,BlockPos)
+ void lambda$clearAllTests$8(ServerLevel,BlockPos)
+ void lambda$createBook$4(StringBuffer,String)
+ void lambda$say$6(String,ChatFormatting,ServerPlayer)
+ void say(ServerLevel,ChatFormatting,String)
+ void showRedBox(ServerLevel,BlockPos,String)
+ void spawnBeacon(GameTestInfo,Block)
+ void spawnLectern(GameTestInfo,String)
+ void visualizeFailedTest(GameTestInfo)
+ void visualizePassedTest(GameTestInfo)
```

</details>


<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
+ Component getPrettyDisplay(String,int)
- void accept(TagVisitor)
```

</details>


























































































<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
+ Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
- Dynamic lambda$addNames$36(Dynamic,Map,String,Dynamic)
+ Dynamic lambda$null$33(Dynamic,Map,Dynamic)
- Dynamic lambda$null$34(Dynamic,Map,Dynamic)
+ Dynamic lambda$null$34(Dynamic,String,Dynamic)
- Dynamic lambda$null$35(Dynamic,String,Dynamic)
- TypeTemplate lambda$registerTypes$32(Schema)
+ void lambda$static$32(HashMap)
- void lambda$static$33(HashMap)
```

</details>








































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ boolean checkAndResetForcedChunkAdditionFlag()
+ boolean checkAndResetUpdateChunkPos()
- boolean hasExactlyOnePlayerPassenger()
+ boolean hasOnePlayerPassenger()
+ boolean hasPassenger(Class)
- boolean hasPassenger(Predicate)
- boolean isAlwaysTicking()
- boolean isRemoved()
- boolean lambda$hasExactlyOnePlayerPassenger$13(Entity)
- boolean lambda$hasIndirectPassenger$14(Entity,Entity)
+ boolean lambda$null$3(BlockState,BlockPos)
- boolean lambda$null$4(BlockState,BlockPos)
- boolean lambda$removePassenger$3(Entity,Entity)
- boolean shouldBeSaved()
- ChunkPos chunkPosition()
+ Collection getIndirectPassengers()
- Entity getFirstPassenger()
- Entity$RemovalReason getRemovalReason()
- int getBlockX()
- int getBlockY()
- int getBlockZ()
- ItemStack getPickResult()
- Iterable getIndirectPassengers()
- Iterator lambda$getIndirectPassengers$12()
+ PortalInfo lambda$findDimensionEntryPoint$4(ServerLevel,BlockUtil$FoundRectangle)
- PortalInfo lambda$findDimensionEntryPoint$5(ServerLevel,BlockUtil$FoundRectangle)
- Stream getIndirectPassengersStream()
- Stream getPassengersAndSelf()
+ String lambda$fillCrashReportCategory$5()
- String lambda$fillCrashReportCategory$9()
- Style lambda$getDisplayName$10(Style)
+ Style lambda$getDisplayName$9(Style)
- void checkOutOfWorld()
- void discard()
+ void fillIndirectPassengers(boolean,Set)
+ void lambda$teleportTo$10(ServerLevel,Entity)
- void lambda$teleportTo$11(Entity)
- void recreateFromPacket(ClientboundAddEntityPacket)
+ void remove()
- void remove(Entity$RemovalReason)
+ void setDropContainerContent(boolean)
- void setLevelCallback(EntityInLevelCallback)
- void setRemoved(Entity$RemovalReason)
- void unsetRemoved()
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
- void merge(ExperienceOrb)
- void scanForEntities()
```

</details>


<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ boolean lambda$isHolding$5(Item,Item)
- boolean lambda$isHolding$5(Item,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- ItemStack getPickResult()
```

</details>


<details>
<summary>
net.minecraft.world.entity.NeutralMob
</summary>

```diff
- void readPersistentAngerSaveData(Level,CompoundTag)
+ void readPersistentAngerSaveData(ServerLevel,CompoundTag)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
+ boolean lambda$null$5(Villager,LivingEntity)
- boolean lambda$null$6(Villager,LivingEntity)
- Entity lambda$getLivingEntityFromUUIDMemory$4(LivingEntity,UUID)
+ LivingEntity lambda$getLivingEntityFromUUIDMemory$4(LivingEntity,UUID)
- LivingEntity lambda$getLivingEntityFromUUIDMemory$5(Entity)
+ Stream lambda$getNearbyVillagersWithCondition$7(Villager,Predicate,List)
- Stream lambda$getNearbyVillagersWithCondition$8(Villager,Predicate,List)
+ Villager lambda$null$6(LivingEntity)
- Villager lambda$null$7(LivingEntity)
```

</details>




































<details>
<summary>
net.minecraft.world.entity.ai.behavior.VillagerMakeLove
</summary>

```diff
+ boolean lambda$isBreedingPossible$0(AgableMob)
- boolean lambda$isBreedingPossible$0(AgeableMob)
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
net.minecraft.world.inventory.MerchantMenu
</summary>

```diff
+ boolean isSameItem(ItemStack,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.PlayerEnderChestContainer
</summary>

```diff
- boolean isActiveChest(EnderChestBlockEntity)
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
```

</details>


























<details>
<summary>
net.minecraft.world.item.crafting.Recipe
</summary>

```diff
- boolean isIncomplete()
- boolean lambda$isIncomplete$0(Ingredient)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe
</summary>

```diff
- boolean isIncomplete()
- boolean lambda$isIncomplete$0(Ingredient)
- boolean lambda$isIncomplete$1(Ingredient)
+ JsonSyntaxException lambda$itemFromJson$0(String)
- JsonSyntaxException lambda$itemFromJson$2(String)
```

</details>








































<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
+ int getMaxBuildHeight()
```

</details>







<details>
<summary>
net.minecraft.world.level.EmptyBlockGetter
</summary>

```diff
- int getMinSection()
- int getSectionsCount()
```

</details>










<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ BlockEntity getPendingBlockEntityAt(BlockPos)
+ boolean addBlockEntity(BlockEntity)
+ boolean isOutsideBuildHeight(BlockPos)
+ boolean isOutsideBuildHeight(int)
- int getMinSection()
- int getSectionsCount()
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
- void onBlockEntityAdd(BlockEntity)
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
net.minecraft.world.level.block.TrappedChestBlock
</summary>

```diff
+ BlockEntity newBlockEntity(BlockGetter)
- BlockEntity newBlockEntity(BlockPos,BlockState)
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
net.minecraft.world.level.chunk.ProtoTickList
</summary>

```diff
- void <init>(Predicate,ChunkPos,LevelHeightAccessor)
- void <init>(Predicate,ChunkPos,ListTag,LevelHeightAccessor)
+ void <init>(Predicate,ChunkPos,ListTag)
+ void <init>(Predicate,ChunkPos)
```

</details>























































<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
- VoxelShape create(double,double,double,double,double,double)
```

</details>

<details>
<summary>
net.minecraft.world.phys.shapes.VoxelShape
</summary>

```diff
+ boolean isFullWide(double,double,double)
+ boolean lambda$findIndex$4(Direction$Axis,double,int)
- boolean lambda$findIndex$4(double,Direction$Axis,int)
```

</details>
</details>