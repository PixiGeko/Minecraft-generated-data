## Comparison with [19w11b](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w11b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w11b</th><th>19w12a</th></tr><tr><td>World version</td><td><pre>1938</pre></td><td><pre>1940</pre></td></tr><tr><td>Protocol version</td><td><pre>465</pre></td><td><pre>466</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- com.paulscode:codecjorbis V20101023
- com.paulscode:codecwav V20101023
- com.paulscode:libraryjavasound V20101123
- com.paulscode:soundsystem V20120107
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w11b</th><th>19w12a</th></tr><tr><td>com.mojang:realms</td><td><pre>1.14.1</pre></td><td><pre>1.14.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
activity
</summary>

```diff
+ minecraft:play
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:cut_red_sandstone_slab
+ minecraft:cut_sandstone_slab
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:cut_red_sandstone_slab
+ minecraft:cut_sandstone_slab
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:golem_spawn_conditions
+ minecraft:secondary_job_site
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:secondary_pois
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
+ minecraft:cut_red_sandstone_slab
+ minecraft:cut_sandstone_slab
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:play
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:cut_red_sandstone_slab
+ minecraft:cut_sandstone_slab
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:cut_red_sandstone_slab
+ minecraft:cut_sandstone_slab
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:golem_spawn_conditions
+ minecraft:secondary_job_site
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:secondary_pois
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
+ cut_red_sandstone_slab.json
+ cut_sandstone_slab.json
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
+ cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+ cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+ cut_red_sandstone_slab.json
+ cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+ cut_sandstone_slab_from_sandstone_stonecutting.json
+ cut_sandstone_slab.json
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
+ block.minecraft.cut_red_sandstone_slab: Cut Red Sandstone Slab
+ block.minecraft.cut_sandstone_slab: Cut Sandstone Slab
- selectWorld.newWorld.copyOf: Copy of %s
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
+ minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_red_sandstone_slab.json
+ minecraft/advancements/recipes/building_blocks/cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_sandstone_slab_from_sandstone_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_sandstone_slab.json
+ minecraft/loot_tables/blocks/cut_red_sandstone_slab.json
+ minecraft/loot_tables/blocks/cut_sandstone_slab.json
+ minecraft/recipes/cut_red_sandstone_slab_from_cut_red_sandstone_stonecutting.json
+ minecraft/recipes/cut_red_sandstone_slab_from_red_sandstone_stonecutting.json
+ minecraft/recipes/cut_red_sandstone_slab.json
+ minecraft/recipes/cut_sandstone_slab_from_cut_sandstone_stonecutting.json
+ minecraft/recipes/cut_sandstone_slab_from_sandstone_stonecutting.json
+ minecraft/recipes/cut_sandstone_slab.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/cut_red_sandstone_slab.json
+ minecraft/blockstates/cut_sandstone_slab.json
+ minecraft/models/block/cut_red_sandstone_slab_top.json
+ minecraft/models/block/cut_red_sandstone_slab.json
+ minecraft/models/block/cut_sandstone_slab_top.json
+ minecraft/models/block/cut_sandstone_slab.json
+ minecraft/models/item/cut_red_sandstone_slab.json
+ minecraft/models/item/cut_sandstone_slab.json
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
- Hobo humping slobo babe!
```

</details>
</details>
<hr/>