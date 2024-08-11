## Comparison with [18w50a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w50a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">18w50a</th><th>19w02a</th></tr><tr><td>World version</td><td><code>1919</code></td><td><code>1921</code></td></tr><tr><td>Protocol version</td><td><code>451</code></td><td><code>452</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ menu.txt
```

</details>


<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:campfire
```

</details>
<details>
<summary>
block_entity_type.txt
</summary>

```diff
+ minecraft:campfire
```

</details>



<details>
<summary>
custom_stat.txt
</summary>

```diff
+ minecraft:interact_with_campfire
+ minecraft:interact_with_lectern
```

</details>




<details>
<summary>
feature.txt
</summary>

```diff
- minecraft:new_village
```

</details>

<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:campfire
```

</details>


<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:campfire_cosy_smoke
+ minecraft:campfire_signal_smoke
```

</details>


<details>
<summary>
sound_event.txt
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
structure_feature.txt
</summary>

```diff
- minecraft:new_village
```

</details>
<details>
<summary>
structure_piece.txt
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
<details><summary>Tags</summary>
<details>
<summary>
List
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
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ teammsg.json
+ tm.json
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
<details><summary>Recipes</summary>
<details>
<summary>
List
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
<details><summary>Translations</summary>
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

```
menu.preparingSpawn: Preparing spawn area: %s%%
stat.minecraft.clean_shulker_box: Shulker Boxes Cleaned
```

</details>
</details>
<details><summary>File structure</summary>
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