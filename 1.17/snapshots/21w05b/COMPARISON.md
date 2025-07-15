## Comparison with [21w05a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w05a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">21w05a</th><th>21w05b</th></tr><tr><td>World version</td><td><pre>2690</pre></td><td><pre>2692</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741836</pre></td><td><pre>1073741837</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">21w05a</th><th>21w05b</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ minecraft:exposed_copper
- minecraft:exposed_copper_block
+ minecraft:oxidized_copper
- minecraft:oxidized_copper_block
- minecraft:waxed_copper
+ minecraft:waxed_copper_block
+ minecraft:weathered_copper
- minecraft:weathered_copper_block
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:exposed_copper
- minecraft:exposed_copper_block
+ minecraft:oxidized_copper
- minecraft:oxidized_copper_block
- minecraft:waxed_copper
+ minecraft:waxed_copper_block
+ minecraft:weathered_copper
- minecraft:weathered_copper_block
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
+ minecraft:exposed_copper
- minecraft:exposed_copper_block
+ minecraft:oxidized_copper
- minecraft:oxidized_copper_block
- minecraft:waxed_copper
+ minecraft:waxed_copper_block
+ minecraft:weathered_copper
- minecraft:weathered_copper_block
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:exposed_copper
- minecraft:exposed_copper_block
+ minecraft:oxidized_copper
- minecraft:oxidized_copper_block
- minecraft:waxed_copper
+ minecraft:waxed_copper_block
+ minecraft:weathered_copper
- minecraft:weathered_copper_block
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:exposed_copper
- minecraft:exposed_copper_block
+ minecraft:oxidized_copper
- minecraft:oxidized_copper_block
- minecraft:waxed_copper
+ minecraft:waxed_copper_block
+ minecraft:weathered_copper
- minecraft:weathered_copper_block
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
- exposed_copper_block.json
+ exposed_copper.json
- oxidized_copper_block.json
+ oxidized_copper.json
+ waxed_copper_block.json
- waxed_copper.json
- weathered_copper_block.json
+ weathered_copper.json
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
- exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_from_exposed_copper_stonecutting.json
- exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_slab_from_exposed_copper_stonecutting.json
- exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_stairs_from_exposed_copper_stonecutting.json
- oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_from_oxidized_copper_stonecutting.json
- oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_slab_from_oxidized_copper_stonecutting.json
- oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_stairs_from_oxidized_copper_stonecutting.json
+ waxed_copper_block.json
- waxed_copper.json
+ waxed_cut_copper_from_waxed_copper_block_stonecutting.json
- waxed_cut_copper_from_waxed_copper_stonecutting.json
+ waxed_cut_copper_slab_from_waxed_copper_block_stonecutting.json
- waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ waxed_cut_copper_stairs_from_waxed_copper_block_stonecutting.json
- waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
- weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_from_weathered_copper_stonecutting.json
- weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_slab_from_weathered_copper_stonecutting.json
- weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_stairs_from_weathered_copper_stonecutting.json
```

</details>
<details>
<summary>
exposed_cut_copper.json
</summary>

```
A: exposed_copper
B: exposed_copper_block

Previous pattern:
[B | B]
[B | B]

New pattern:
[A | A]
[A | A]
```

</details>
<details>
<summary>
oxidized_cut_copper.json
</summary>

```
A: oxidized_copper
B: oxidized_copper_block

Previous pattern:
[B | B]
[B | B]

New pattern:
[A | A]
[A | A]
```

</details>
<details>
<summary>
waxed_cut_copper.json
</summary>

```
A: waxed_copper
B: waxed_copper_block

Previous pattern:
[A | A]
[A | A]

New pattern:
[B | B]
[B | B]
```

</details>
<details>
<summary>
waxed_exposed_copper.json
</summary>

```
Ingredients
 exposed_copper x1
 exposed_copper_block x1
 honeycomb x1
```

</details>
<details>
<summary>
waxed_weathered_copper.json
</summary>

```
Ingredients
 honeycomb x1
 weathered_copper x1
 weathered_copper_block x1
```

</details>
<details>
<summary>
weathered_cut_copper.json
</summary>

```
A: weathered_copper
B: weathered_copper_block

Previous pattern:
[B | B]
[B | B]

New pattern:
[A | A]
[A | A]
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
- block.minecraft.exposed_copper_block: Exposed Copper Block
+ block.minecraft.exposed_copper: Exposed Copper
- block.minecraft.oxidized_copper_block: Oxidized Copper Block
+ block.minecraft.oxidized_copper: Oxidized Copper
+ block.minecraft.waxed_copper_block: Waxed Block of Copper
- block.minecraft.waxed_copper: Waxed Copper
- block.minecraft.waxed_exposed_copper_block: Waxed Exposed Copper Block
- block.minecraft.waxed_weathered_copper_block: Waxed Weathered Copper Block
- block.minecraft.weathered_copper_block: Weathered Copper Block
+ block.minecraft.weathered_copper: Weathered Copper
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>21w05a</th><th>21w05b</th></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.copper_block</div></th><td>Copper Block</td><td>Block of Copper</td></tr>
</table>
<br/>
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
- minecraft/advancements/recipes/building_blocks/exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_from_exposed_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_slab_from_exposed_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_stairs_from_exposed_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_from_oxidized_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_slab_from_oxidized_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_stairs_from_oxidized_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_block.json
- minecraft/advancements/recipes/building_blocks/waxed_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_copper_block_stonecutting.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab_from_waxed_copper_block_stonecutting.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs_from_waxed_copper_block_stonecutting.json
- minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_from_weathered_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab_from_weathered_copper_stonecutting.json
- minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs_from_weathered_copper_stonecutting.json
- minecraft/loot_tables/blocks/exposed_copper_block.json
+ minecraft/loot_tables/blocks/exposed_copper.json
- minecraft/loot_tables/blocks/oxidized_copper_block.json
+ minecraft/loot_tables/blocks/oxidized_copper.json
+ minecraft/loot_tables/blocks/waxed_copper_block.json
- minecraft/loot_tables/blocks/waxed_copper.json
- minecraft/loot_tables/blocks/weathered_copper_block.json
+ minecraft/loot_tables/blocks/weathered_copper.json
- minecraft/recipes/exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_from_exposed_copper_stonecutting.json
- minecraft/recipes/exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_slab_from_exposed_copper_stonecutting.json
- minecraft/recipes/exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_stairs_from_exposed_copper_stonecutting.json
- minecraft/recipes/oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_from_oxidized_copper_stonecutting.json
- minecraft/recipes/oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_slab_from_oxidized_copper_stonecutting.json
- minecraft/recipes/oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_stairs_from_oxidized_copper_stonecutting.json
+ minecraft/recipes/waxed_copper_block.json
- minecraft/recipes/waxed_copper.json
+ minecraft/recipes/waxed_cut_copper_from_waxed_copper_block_stonecutting.json
- minecraft/recipes/waxed_cut_copper_from_waxed_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_slab_from_waxed_copper_block_stonecutting.json
- minecraft/recipes/waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_stairs_from_waxed_copper_block_stonecutting.json
- minecraft/recipes/waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
- minecraft/recipes/weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_from_weathered_copper_stonecutting.json
- minecraft/recipes/weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_slab_from_weathered_copper_stonecutting.json
- minecraft/recipes/weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_stairs_from_weathered_copper_stonecutting.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/exposed_copper_block.json
+ minecraft/blockstates/exposed_copper.json
- minecraft/blockstates/oxidized_copper_block.json
+ minecraft/blockstates/oxidized_copper.json
+ minecraft/blockstates/waxed_copper_block.json
- minecraft/blockstates/waxed_copper.json
- minecraft/blockstates/weathered_copper_block.json
+ minecraft/blockstates/weathered_copper.json
- minecraft/models/block/exposed_copper_block.json
+ minecraft/models/block/exposed_copper.json
- minecraft/models/block/oxidized_copper_block.json
+ minecraft/models/block/oxidized_copper.json
- minecraft/models/block/weathered_copper_block.json
+ minecraft/models/block/weathered_copper.json
- minecraft/models/item/exposed_copper_block.json
+ minecraft/models/item/exposed_copper.json
- minecraft/models/item/oxidized_copper_block.json
+ minecraft/models/item/oxidized_copper.json
+ minecraft/models/item/waxed_copper_block.json
- minecraft/models/item/waxed_copper.json
- minecraft/models/item/weathered_copper_block.json
+ minecraft/models/item/weathered_copper.json
- minecraft/textures/block/exposed_copper_block.png
+ minecraft/textures/block/exposed_copper.png
- minecraft/textures/block/oxidized_copper_block.png
+ minecraft/textures/block/oxidized_copper.png
- minecraft/textures/block/weathered_copper_block.png
+ minecraft/textures/block/weathered_copper.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.level.block.Blocks +4P -4P
```
```
XXX.world.phys.AABB -1M
```

</details>
<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
+ AABB minmax(Iterable)
```

</details>
</details>
<hr/>