## Comparison with [18w50a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w50a)

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

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">18w50a</th><th>19w02a</th></tr><tr><td>World version</td><td><pre>1919</pre></td><td><pre>1921</pre></td></tr><tr><td>Protocol version</td><td><pre>451</pre></td><td><pre>452</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">18w50a</th><th>19w02a</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>1.0.21</pre></td><td><pre>2.0.23</pre></td></tr></table>
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
+ menu.txt
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
custom_stat
</summary>

```diff
+ minecraft:interact_with_campfire
+ minecraft:interact_with_lectern
```

</details>
<details>
<summary>
feature
</summary>

```diff
- minecraft:new_village
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:campfire_cosy_smoke
+ minecraft:campfire_signal_smoke
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.campfire.crackle
+ minecraft:item.book.page_turn
+ minecraft:item.book.put
+ minecraft:ui.cartography_table.take_result
```

</details>
<details>
<summary>
structure_feature
</summary>

```diff
- minecraft:new_village
```

</details>
<details>
<summary>
structure_piece
</summary>

```diff
- minecraft:vibh
- minecraft:vidf
- minecraft:vif
- minecraft:vil
- minecraft:viph
- minecraft:vis
- minecraft:vish
- minecraft:vismh
- minecraft:visr
- minecraft:vist
- minecraft:vistart
- minecraft:vitrh
- minecraft:viw
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
+ universal_tags/menu.json
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
+ minecraft:interact_with_campfire
+ minecraft:interact_with_lectern
```

</details>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
- minecraft:new_village
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:campfire_cosy_smoke
+ minecraft:campfire_signal_smoke
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.campfire.crackle
+ minecraft:item.book.page_turn
+ minecraft:item.book.put
+ minecraft:ui.cartography_table.take_result
```

</details>
<details>
<summary>
universal_tags/structure_feature.json
</summary>

```diff
- minecraft:new_village
```

</details>
<details>
<summary>
universal_tags/structure_piece.json
</summary>

```diff
- minecraft:vibh
- minecraft:vidf
- minecraft:vif
- minecraft:vil
- minecraft:viph
- minecraft:vis
- minecraft:vish
- minecraft:vismh
- minecraft:visr
- minecraft:vist
- minecraft:vistart
- minecraft:vitrh
- minecraft:viw
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
+ campfire.json
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
+ teammsg.txt
+ tm.txt
```

</details>
<details>
<summary>
data
</summary>

```diff
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify block <targetPos: block_pos> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify block <targetPos: block_pos> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> from entity <source: entity> <sourcePath: nbt_path>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> value <value: nbt_tag>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert after <index: integer> value <value: nbt_tag>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from block <sourcePos: block_pos> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> from entity <source: entity> <sourcePath: nbt_path>
- data modify entity <target: entity> <targetPath: nbt_path> insert before <index: integer> value <value: nbt_tag>
```

</details>
<details>
<summary>
locate
</summary>

```diff
- locate New_Village
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
+ baked_potato_from_campfire.json
+ campfire.json
+ cartography_table.json
+ cooked_beef_from_campfire.json
+ cooked_chicken_from_campfire.json
+ cooked_cod_from_campfire.json
+ cooked_mutton_from_campfire.json
+ cooked_porkchop_from_campfire.json
+ cooked_rabbit_from_campfire.json
+ cooked_salmon_from_campfire.json
+ dried_kelp_from_campfire.json
+ lectern.json
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
+ block.minecraft.campfire: Campfire
+ chat.type.team.hover: Message Team
+ chat.type.team.sent: -> %s <%s> %s
+ chat.type.team.text: %s <%s> %s
+ commands.data.modify.invalid_index: Invalid list index: %s
+ commands.teammsg.failed.noteam: You must be on a team to message your team
+ container.cartography_table: Cartography Table
+ container.lectern: Lectern
+ filled_map.locked: Locked
+ lectern.take_book: Take book
+ stat.minecraft.interact_with_blast_furnace: Interactions with Blast Furnace
+ stat.minecraft.interact_with_campfire: Interactions with Campfire
+ stat.minecraft.interact_with_lectern: Interactions with Lectern
+ stat.minecraft.interact_with_smoker: Interactions with Smoker
+ subtitles.block.campfire.crackle: Campfire crackles
+ subtitles.item.book.page_turn: Page rustles
+ subtitles.item.book.put: Book thumps
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w50a</th><th>19w02a</th></tr>
<tr><th align="left"><div style="width:290px">menu.preparingSpawn</div></th><td>Preparing spawn area</td><td>Preparing spawn area: %s%%</td></tr>
<tr><th align="left"><div style="width:290px">stat.minecraft.clean_shulker_box</div></th><td>Shulker Box Cleaned</td><td>Shulker Boxes Cleaned</td></tr>
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
+ minecraft/advancements/recipes/decorations/campfire.json
+ minecraft/advancements/recipes/decorations/cartography_table.json
+ minecraft/advancements/recipes/food/baked_potato_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_beef_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_chicken_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_cod_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_mutton_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_porkchop_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_rabbit_from_campfire.json
+ minecraft/advancements/recipes/food/cooked_salmon_from_campfire.json
+ minecraft/advancements/recipes/food/dried_kelp_from_campfire.json
+ minecraft/advancements/recipes/redstone/lectern.json
+ minecraft/loot_tables/blocks/campfire.json
+ minecraft/recipes/baked_potato_from_campfire.json
+ minecraft/recipes/campfire.json
+ minecraft/recipes/cartography_table.json
+ minecraft/recipes/cooked_beef_from_campfire.json
+ minecraft/recipes/cooked_chicken_from_campfire.json
+ minecraft/recipes/cooked_cod_from_campfire.json
+ minecraft/recipes/cooked_mutton_from_campfire.json
+ minecraft/recipes/cooked_porkchop_from_campfire.json
+ minecraft/recipes/cooked_rabbit_from_campfire.json
+ minecraft/recipes/cooked_salmon_from_campfire.json
+ minecraft/recipes/dried_kelp_from_campfire.json
+ minecraft/recipes/lectern.json
+ minecraft/tags/items/coals.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/campfire.json
+ minecraft/models/block/campfire_on.json
+ minecraft/models/block/campfire.json
+ minecraft/models/item/campfire.json
+ minecraft/textures/block/campfire_fire.png
+ minecraft/textures/block/campfire_fire.png.mcmeta
+ minecraft/textures/block/campfire_side.png
+ minecraft/textures/block/campfire_top_on.png
+ minecraft/textures/block/campfire_top_on.png.mcmeta
+ minecraft/textures/block/campfire_top.png
+ minecraft/textures/gui/container/cartography_table.png
```

</details>
</details>
<hr/>