## Comparison with [26.4-snapshot-5](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-5)

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
<table><tr><th></th><th align="left">26.4-snapshot-5</th><th>26.4-snapshot-6</th></tr><tr><td>DataPack version</td><td><pre>125.0</pre></td><td><pre>125.1</pre></td></tr><tr><td>ResourcePack version</td><td><pre>100.2</pre></td><td><pre>101.0</pre></td></tr><tr><td>World version</td><td><pre>5125</pre></td><td><pre>5126</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742167</pre></td><td><pre>1073742168</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ com.github.oshi:oshi-common V7.7.2
- com.github.oshi:oshi-core V6.9.0
+ com.github.oshi:oshi-core-ffm V7.7.2
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.4-snapshot-5</th><th>26.4-snapshot-6</th></tr><tr><td>at.yawk.lz4:lz4-java</td><td><pre>1.10.1</pre></td><td><pre>1.12.1</pre></td></tr><tr><td>io.netty:netty-buffer</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-codec-base</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-codec-compression</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-codec-http</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-common</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-handler</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-resolver</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-epoll</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-kqueue</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-aarch_64)</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-x86_64)</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-aarch_64)</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-x86_64)</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-unix-common</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>io.netty:netty-transport</td><td><pre>4.2.16.Final</pre></td><td><pre>4.2.19.Final</pre></td></tr><tr><td>net.java.dev.jna:jna-platform</td><td><pre>5.17.0</pre></td><td><pre>5.19.1</pre></td></tr><tr><td>net.java.dev.jna:jna</td><td><pre>5.17.0</pre></td><td><pre>5.19.1</pre></td></tr><tr><td>org.slf4j:slf4j-api</td><td><pre>2.0.17</pre></td><td><pre>2.0.20</pre></td></tr></table>
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
+ minecraft:snow_brick_slab
+ minecraft:snow_brick_stairs
+ minecraft:snow_brick_wall
+ minecraft:snow_bricks
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:snow_brick_slab
+ minecraft:snow_brick_stairs
+ minecraft:snow_brick_wall
+ minecraft:snow_bricks
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.ice_crystal.ambient
```

</details>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
+ minecraft:domain_warp
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
+ minecraft:snow_brick_slab
+ minecraft:snow_brick_stairs
+ minecraft:snow_brick_wall
+ minecraft:snow_bricks
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:snow_brick_slab
+ minecraft:snow_brick_stairs
+ minecraft:snow_brick_wall
+ minecraft:snow_bricks
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:snow_brick_slab
+ minecraft:snow_brick_stairs
+ minecraft:snow_brick_wall
+ minecraft:snow_bricks
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.ice_crystal.ambient
```

</details>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
+ minecraft:domain_warp
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
+ snow_brick_slab.json
+ snow_brick_stairs.json
+ snow_brick_wall.json
+ snow_bricks.json
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
+ snow_brick_slab.json
+ snow_brick_stairs.json
+ snow_brick_wall.json
+ snow_bricks.json
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
+ block.minecraft.snow_brick_slab: Snow Brick Slab
+ block.minecraft.snow_brick_stairs: Snow Brick Stairs
+ block.minecraft.snow_brick_wall: Snow Brick Wall
+ block.minecraft.snow_bricks: Snow Bricks
+ subtitles.block.ice_crystal.ambient: Ice Crystal chimes
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.4-snapshot-5</th><th>26.4-snapshot-6</th></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.discard.draft.overwrite</div></th><td>You already have a report draft saved. Saving a new draft will permanently overwrite it.</td><td>You already have a draft report saved. Saving a new draft will permanently overwrite it.</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.draft.restart</div></th><td>Discard and Start New Report</td><td>Discard and Create New Report</td></tr>
<tr><th align="left"><div style="width:290px">gui.player_options.unfriend.confirm</div></th><td>This player will be removed from your Friends.</td><td>This player will be removed from your Friends List.</td></tr>
<tr><th align="left"><div style="width:290px">mco.selectServer.joinCode</div></th><td>Join Code</td><td>Invite Code</td></tr>
<tr><th align="left"><div style="width:290px">mco.selectServer.joinCode.hint</div></th><td>Enter join code</td><td>Enter invite code</td></tr>
<tr><th align="left"><div style="width:290px">mco.selectServer.joinCode.title</div></th><td>Enter Join Code</td><td>Enter Invite Code</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.other_players.not_available</div></th><td>Other Players only available in Multiplayer worlds</td><td>The Other Players screen is only available in multiplayer worlds</td></tr>
<tr><th align="left"><div style="width:290px">options.hideMatchedNames.tooltip</div></th><td>Third-party servers may send chat messages in non-standard formats.

With this option on, hidden players will be matched based on chat sender names.</td><td>Third-party servers may send chat messages in non-standard formats.

With this option on, muted players will be matched based on chat sender names.</td></tr>
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
+ reports/minecraft/components/item/snow_brick_slab.json
+ reports/minecraft/components/item/snow_brick_stairs.json
+ reports/minecraft/components/item/snow_brick_wall.json
+ reports/minecraft/components/item/snow_bricks.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/snow_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/snow_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/snow_bricks.json
+ minecraft/advancement/recipes/decorations/snow_brick_wall.json
+ minecraft/loot_table/blocks/snow_brick_slab.json
+ minecraft/loot_table/blocks/snow_brick_stairs.json
+ minecraft/loot_table/blocks/snow_brick_wall.json
+ minecraft/loot_table/blocks/snow_bricks.json
+ minecraft/recipe/snow_brick_slab.json
+ minecraft/recipe/snow_brick_stairs.json
+ minecraft/recipe/snow_brick_wall.json
+ minecraft/recipe/snow_bricks.json
+ minecraft/sulfur_cube_archetype/cold.json
+ minecraft/tags/entity_type/flying.json
+ minecraft/tags/entity_type/swimming.json
+ minecraft/tags/fluid/swimmable.json
+ minecraft/tags/item/sulfur_cube_archetype/cold.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/snow_brick_slab.json
+ minecraft/blockstates/snow_brick_stairs.json
+ minecraft/blockstates/snow_brick_wall.json
+ minecraft/blockstates/snow_bricks.json
+ minecraft/items/snow_brick_slab.json
+ minecraft/items/snow_brick_stairs.json
+ minecraft/items/snow_brick_wall.json
+ minecraft/items/snow_bricks.json
- minecraft/models/block/cube_top.json
+ minecraft/models/block/snow_brick_slab_top.json
+ minecraft/models/block/snow_brick_slab.json
+ minecraft/models/block/snow_brick_stairs_inner.json
+ minecraft/models/block/snow_brick_stairs_outer.json
+ minecraft/models/block/snow_brick_stairs.json
+ minecraft/models/block/snow_brick_wall_inventory.json
+ minecraft/models/block/snow_brick_wall_post.json
+ minecraft/models/block/snow_brick_wall_side_tall.json
+ minecraft/models/block/snow_brick_wall_side.json
+ minecraft/models/block/snow_bricks.json
+ minecraft/textures/block/snow_bricks.png
```

</details>
</details>
<hr/>