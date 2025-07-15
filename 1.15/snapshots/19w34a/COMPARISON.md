## Comparison with [1.14.4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.14.4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.14.4</th><th>19w34a</th></tr><tr><td>World version</td><td><pre>1976</pre></td><td><pre>2200</pre></td></tr><tr><td>Protocol version</td><td><pre>498</pre></td><td><pre>550</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.14.4</th><th>19w34a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:beehive
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:bee
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
+ minecraft:bee_spawn_egg
+ minecraft:honey_bottle
+ minecraft:honeycomb
```

</details>
<details>
<summary>
menu
</summary>

```diff
- minecraft:cartography
+ minecraft:cartography_table
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:dripping_honey
+ minecraft:falling_honey
+ minecraft:falling_nectar
+ minecraft:landing_honey
```

</details>
<details>
<summary>
point_of_interest_type
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.beehive.drip
+ minecraft:block.beehive.enter
+ minecraft:block.beehive.exit
+ minecraft:block.beehive.shear
+ minecraft:block.beehive.work
+ minecraft:entity.bee.death
+ minecraft:entity.bee.hurt
+ minecraft:entity.bee.loop
+ minecraft:entity.bee.loop_aggressive
+ minecraft:entity.bee.pollinate
+ minecraft:entity.bee.sting
+ minecraft:item.honey_bottle.drink
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
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:bee
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:bee
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:beehive
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:bee
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
+ minecraft:bee_spawn_egg
+ minecraft:honey_bottle
+ minecraft:honeycomb
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
- minecraft:cartography
+ minecraft:cartography_table
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:dripping_honey
+ minecraft:falling_honey
+ minecraft:falling_nectar
+ minecraft:landing_honey
```

</details>
<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.beehive.drip
+ minecraft:block.beehive.enter
+ minecraft:block.beehive.exit
+ minecraft:block.beehive.shear
+ minecraft:block.beehive.work
+ minecraft:entity.bee.death
+ minecraft:entity.bee.hurt
+ minecraft:entity.bee.loop
+ minecraft:entity.bee.loop_aggressive
+ minecraft:entity.bee.pollinate
+ minecraft:entity.bee.sting
+ minecraft:item.honey_bottle.drink
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
+ bee_hive.json
+ bee_nest.json
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
+ bee_hive.json
+ sugar_from_honey_bottle.json
+ sugar_from_sugar_cane.json
- sugar.json
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
+ block.minecraft.bee_hive: Bee hive
+ block.minecraft.bee_nest: Bee nest
+ death.attack.sting: %1$s was stung to death
+ death.attack.sting.player: %1$s was stung to death by %2$s
+ entity.minecraft.bee: Bee
+ item.minecraft.bee_spawn_egg: Bee Spawn Egg
+ item.minecraft.honey_bottle: Honey Bottle
+ item.minecraft.honeycomb: Honeycomb
+ subtitles.block.beehive.drip: Honey drips
+ subtitles.block.beehive.enter: Bee enters hive
+ subtitles.block.beehive.exit: Bee leaves hive
+ subtitles.block.beehive.shear: Shears scrape
+ subtitles.block.beehive.work: Bees work
+ subtitles.entity.bee.ambient: Bee buzzes
+ subtitles.entity.bee.death: Bee dies
+ subtitles.entity.bee.hurt: Bee hurts
+ subtitles.entity.bee.loop_aggressive: Bee buzzes angrily
+ subtitles.entity.bee.loop: Bee buzzes
+ subtitles.entity.bee.pollinate: Bee buzzes happily
+ subtitles.entity.bee.sting: Bee stings
+ subtitles.item.honey_bottle.drink: Honey gulping
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
+ minecraft/advancements/recipes/decorations/bee_hive.json
+ minecraft/advancements/recipes/misc/sugar_from_honey_bottle.json
+ minecraft/advancements/recipes/misc/sugar_from_sugar_cane.json
- minecraft/advancements/recipes/misc/sugar.json
+ minecraft/loot_tables/blocks/bee_hive.json
+ minecraft/loot_tables/blocks/bee_nest.json
+ minecraft/loot_tables/entities/bee.json
+ minecraft/recipes/bee_hive.json
+ minecraft/recipes/sugar_from_honey_bottle.json
+ minecraft/recipes/sugar_from_sugar_cane.json
- minecraft/recipes/sugar.json
+ minecraft/tags/blocks/bee_growables.json
+ minecraft/tags/blocks/beehives.json
+ minecraft/tags/blocks/crops.json
+ minecraft/tags/blocks/flowers.json
+ minecraft/tags/blocks/tall_flowers.json
+ minecraft/tags/items/flowers.json
+ minecraft/tags/items/tall_flowers.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/bee_hive.json
+ minecraft/blockstates/bee_nest.json
+ minecraft/models/block/bee_hive_honey.json
+ minecraft/models/block/bee_hive.json
+ minecraft/models/block/bee_nest_honey.json
+ minecraft/models/block/bee_nest.json
+ minecraft/models/item/bee_hive.json
+ minecraft/models/item/bee_nest.json
+ minecraft/models/item/bee_spawn_egg.json
+ minecraft/models/item/honey_bottle.json
+ minecraft/models/item/honeycomb.json
+ minecraft/particles/dripping_honey.json
+ minecraft/particles/falling_honey.json
+ minecraft/particles/falling_nectar.json
+ minecraft/particles/landing_honey.json
+ minecraft/textures/block/bee_hive_bottom.png
+ minecraft/textures/block/bee_hive_front_honey.png
+ minecraft/textures/block/bee_hive_front.png
+ minecraft/textures/block/bee_hive_side.png
+ minecraft/textures/block/bee_hive_top.png
+ minecraft/textures/block/bee_nest_bottom.png
+ minecraft/textures/block/bee_nest_front_honey.png
+ minecraft/textures/block/bee_nest_front.png
+ minecraft/textures/block/bee_nest_side.png
+ minecraft/textures/block/bee_nest_top.png
+ minecraft/textures/block/wax_block.png
+ minecraft/textures/entity/bee/bee_angry_nectar.png
+ minecraft/textures/entity/bee/bee_angry.png
+ minecraft/textures/entity/bee/bee_nectar.png
+ minecraft/textures/entity/bee/bee_stinger.png
+ minecraft/textures/entity/bee/bee.png
+ minecraft/textures/item/crystallized_honey.png
+ minecraft/textures/item/honey_bottle.png
+ minecraft/textures/item/honeycomb.png
```

</details>
</details>
<hr/>