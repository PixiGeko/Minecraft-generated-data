## Comparison with [19w09a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w09a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w09a</th><th>19w11a</th></tr><tr><td>World version</td><td><pre>1935</pre></td><td><pre>1937</pre></td></tr><tr><td>Protocol version</td><td><pre>463</pre></td><td><pre>464</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w09a</th><th>19w11a</th></tr><tr><td>com.mojang:text2speech</td><td><pre>1.10.3</pre></td><td><pre>1.11.2</pre></td></tr><tr><td>com.mojang:text2speech</td><td><pre>1.10.3</pre></td><td><pre>1.11.2</pre></td></tr></table>
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
+ activity.txt
+ memory_module_type.txt
+ point_of_interest_type.txt
+ schedule.txt
+ sensor_type.txt
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:globe_banner_pattern
```

</details>
<details>
<summary>
menu
</summary>

```diff
+ minecraft:generic_9x1
+ minecraft:generic_9x2
+ minecraft:generic_9x4
+ minecraft:generic_9x5
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.parrot.imitate.guardian
+ minecraft:entity.parrot.imitate.panda
+ minecraft:entity.parrot.imitate.pillager
+ minecraft:entity.parrot.imitate.ravager
+ minecraft:entity.villager.work_armorer
+ minecraft:entity.villager.work_butcher
+ minecraft:entity.villager.work_cartographer
+ minecraft:entity.villager.work_cleric
+ minecraft:entity.villager.work_farmer
+ minecraft:entity.villager.work_fisherman
+ minecraft:entity.villager.work_fletcher
+ minecraft:entity.villager.work_leatherworker
+ minecraft:entity.villager.work_librarian
+ minecraft:entity.villager.work_mason
+ minecraft:entity.villager.work_shepherd
+ minecraft:entity.villager.work_toolsmith
+ minecraft:entity.villager.work_weaponsmith
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
+ universal_tags/activity.json
+ universal_tags/memory_module_type.json
+ universal_tags/point_of_interest_type.json
+ universal_tags/schedule.json
+ universal_tags/sensor_type.json
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:globe_banner_pattern
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
+ minecraft:generic_9x1
+ minecraft:generic_9x2
+ minecraft:generic_9x4
+ minecraft:generic_9x5
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.parrot.imitate.guardian
+ minecraft:entity.parrot.imitate.panda
+ minecraft:entity.parrot.imitate.pillager
+ minecraft:entity.parrot.imitate.ravager
+ minecraft:entity.villager.work_armorer
+ minecraft:entity.villager.work_butcher
+ minecraft:entity.villager.work_cartographer
+ minecraft:entity.villager.work_cleric
+ minecraft:entity.villager.work_farmer
+ minecraft:entity.villager.work_fisherman
+ minecraft:entity.villager.work_fletcher
+ minecraft:entity.villager.work_leatherworker
+ minecraft:entity.villager.work_librarian
+ minecraft:entity.villager.work_mason
+ minecraft:entity.villager.work_shepherd
+ minecraft:entity.villager.work_toolsmith
+ minecraft:entity.villager.work_weaponsmith
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
+ fletching_table.json
+ smithing_table.json
```

</details>
<details>
<summary>
cartography_table.json
</summary>

```
A: #planks
B: paper

Previous pattern:
[B | B]
[A | A]

New pattern:
[B | B]
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
+ block.minecraft.bed.obstructed: This bed is obstructed
- createWorld.customize.flat.addLayer: Add Layer
- createWorld.customize.flat.editLayer: Edit Layer
+ entity.minecraft.villager.none: Villager
+ item.minecraft.crossbow.projectile: Projectile:
+ item.minecraft.globe_banner_pattern: Globe Pattern
+ item.minecraft.globe_banner_pattern.desc: Globe
+ merchant.current_level: Trader's current level
+ merchant.level.1: Novice
+ merchant.level.2: Apprentice
+ merchant.level.3: Journeyman
+ merchant.level.4: Expert
+ merchant.level.5: Master
+ merchant.next_level: Trader's next level
+ options.accessibility.text_background_opacity: Text Background Opacity
+ options.accessibility.text_background: Text Background
+ options.accessibility.text_background.chat: Chat
+ options.accessibility.text_background.everywhere: Everywhere
+ options.accessibility.title: Accessibility Settings...
+ selectWorld.edit.backupFailed: Backup failed
+ subtitles.entity.parrot.imitate.guardian: Parrot moans
+ subtitles.entity.parrot.imitate.panda: Parrot pants
+ subtitles.entity.parrot.imitate.pillager: Parrot murmurs
+ subtitles.entity.parrot.imitate.ravager: Parrot grunts
+ subtitles.entity.villager.work_armorer: Armorer works
+ subtitles.entity.villager.work_butcher: Butcher works
+ subtitles.entity.villager.work_cartographer: Cartographer works
+ subtitles.entity.villager.work_cleric: Cleric works
+ subtitles.entity.villager.work_farmer: Farmer works
+ subtitles.entity.villager.work_fisherman: Fisherman works
+ subtitles.entity.villager.work_fletcher: Fletcher works
+ subtitles.entity.villager.work_leatherworker: Leatherworker works
+ subtitles.entity.villager.work_librarian: Librarian works
+ subtitles.entity.villager.work_mason: Mason works
+ subtitles.entity.villager.work_shepherd: Shepherd works
+ subtitles.entity.villager.work_toolsmith: Toolsmith works
+ subtitles.entity.villager.work_weaponsmith: Weaponsmith works
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>19w09a</th><th>19w11a</th></tr>
<tr><th align="left"><div style="width:290px">options.chat.opacity</div></th><td>Opacity</td><td>Chat Opacity</td></tr>
<tr><th align="left"><div style="width:290px">merchant.deprecated</div></th><td>Trade something else to unlock!</td><td>Villagers restock up to two times per day.</td></tr>
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
- minecraft/advancements/recipes/building_blocks/andesite_wall_from_andesite_stonecutting.json
- minecraft/advancements/recipes/building_blocks/andesite_wall.json
- minecraft/advancements/recipes/building_blocks/brick_wall_from_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/brick_wall.json
- minecraft/advancements/recipes/building_blocks/diorite_wall_from_diorite_stonecutting.json
- minecraft/advancements/recipes/building_blocks/diorite_wall.json
- minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
- minecraft/advancements/recipes/building_blocks/end_stone_brick_wall_from_end_stone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/end_stone_brick_wall.json
- minecraft/advancements/recipes/building_blocks/granite_wall_from_granite_stonecutting.json
- minecraft/advancements/recipes/building_blocks/granite_wall.json
- minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
- minecraft/advancements/recipes/building_blocks/mossy_stone_brick_wall.json
- minecraft/advancements/recipes/building_blocks/nether_brick_wall_from_nether_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/nether_brick_wall.json
- minecraft/advancements/recipes/building_blocks/prismarine_wall_from_prismarine_stonecutting.json
- minecraft/advancements/recipes/building_blocks/prismarine_wall.json
- minecraft/advancements/recipes/building_blocks/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/red_nether_brick_wall.json
- minecraft/advancements/recipes/building_blocks/red_sandstone_wall_from_red_sandstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/red_sandstone_wall.json
- minecraft/advancements/recipes/building_blocks/sandstone_wall_from_sandstone_stonecutting.json
- minecraft/advancements/recipes/building_blocks/sandstone_wall.json
- minecraft/advancements/recipes/building_blocks/stone_brick_wall_from_stone_bricks_stonecutting.json
- minecraft/advancements/recipes/building_blocks/stone_brick_wall.json
- minecraft/advancements/recipes/building_blocks/stone_brick_walls_from_stone_stonecutting.json
+ minecraft/advancements/recipes/decorations/andesite_wall_from_andesite_stonecutting.json
+ minecraft/advancements/recipes/decorations/andesite_wall.json
+ minecraft/advancements/recipes/decorations/brick_wall_from_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/brick_wall.json
+ minecraft/advancements/recipes/decorations/diorite_wall_from_diorite_stonecutting.json
+ minecraft/advancements/recipes/decorations/diorite_wall.json
+ minecraft/advancements/recipes/decorations/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ minecraft/advancements/recipes/decorations/end_stone_brick_wall_from_end_stone_stonecutting.json
+ minecraft/advancements/recipes/decorations/end_stone_brick_wall.json
+ minecraft/advancements/recipes/decorations/fletching_table.json
+ minecraft/advancements/recipes/decorations/granite_wall_from_granite_stonecutting.json
+ minecraft/advancements/recipes/decorations/granite_wall.json
+ minecraft/advancements/recipes/decorations/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ minecraft/advancements/recipes/decorations/mossy_stone_brick_wall.json
+ minecraft/advancements/recipes/decorations/nether_brick_wall_from_nether_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/nether_brick_wall.json
+ minecraft/advancements/recipes/decorations/prismarine_wall_from_prismarine_stonecutting.json
+ minecraft/advancements/recipes/decorations/prismarine_wall.json
+ minecraft/advancements/recipes/decorations/red_nether_brick_wall_from_red_nether_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/red_nether_brick_wall.json
+ minecraft/advancements/recipes/decorations/red_sandstone_wall_from_red_sandstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/red_sandstone_wall.json
+ minecraft/advancements/recipes/decorations/sandstone_wall_from_sandstone_stonecutting.json
+ minecraft/advancements/recipes/decorations/sandstone_wall.json
+ minecraft/advancements/recipes/decorations/smithing_table.json
+ minecraft/advancements/recipes/decorations/stone_brick_wall_from_stone_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/stone_brick_wall.json
+ minecraft/advancements/recipes/decorations/stone_brick_walls_from_stone_stonecutting.json
+ minecraft/recipes/fletching_table.json
+ minecraft/recipes/smithing_table.json
+ minecraft/structures/village/desert/villagers/nitwit.nbt
+ minecraft/structures/village/desert/villagers/unemployed.nbt
- minecraft/structures/village/desert/zombie/villagers/armorer.nbt
- minecraft/structures/village/desert/zombie/villagers/butcher.nbt
- minecraft/structures/village/desert/zombie/villagers/cartographer.nbt
- minecraft/structures/village/desert/zombie/villagers/cleric.nbt
- minecraft/structures/village/desert/zombie/villagers/farmer.nbt
- minecraft/structures/village/desert/zombie/villagers/fishermen.nbt
- minecraft/structures/village/desert/zombie/villagers/fletcher.nbt
- minecraft/structures/village/desert/zombie/villagers/leatherworker.nbt
- minecraft/structures/village/desert/zombie/villagers/librarian.nbt
- minecraft/structures/village/desert/zombie/villagers/shepherd.nbt
- minecraft/structures/village/desert/zombie/villagers/toolsmith.nbt
- minecraft/structures/village/desert/zombie/villagers/weaponsmith.nbt
- minecraft/structures/village/plains/villagers/armorer.nbt
- minecraft/structures/village/plains/villagers/butcher.nbt
- minecraft/structures/village/plains/villagers/cartographer.nbt
- minecraft/structures/village/plains/villagers/cleric.nbt
- minecraft/structures/village/plains/villagers/farmer.nbt
- minecraft/structures/village/plains/villagers/fishermen.nbt
- minecraft/structures/village/plains/villagers/fletcher.nbt
- minecraft/structures/village/plains/villagers/leatherworker.nbt
- minecraft/structures/village/plains/villagers/librarian.nbt
- minecraft/structures/village/plains/villagers/shepherd.nbt
- minecraft/structures/village/plains/villagers/toolsmith.nbt
- minecraft/structures/village/plains/villagers/weaponsmith.nbt
- minecraft/structures/village/plains/zombie/villagers/armorer.nbt
- minecraft/structures/village/plains/zombie/villagers/butcher.nbt
- minecraft/structures/village/plains/zombie/villagers/cartographer.nbt
- minecraft/structures/village/plains/zombie/villagers/cleric.nbt
- minecraft/structures/village/plains/zombie/villagers/farmer.nbt
- minecraft/structures/village/plains/zombie/villagers/fishermen.nbt
- minecraft/structures/village/plains/zombie/villagers/fletcher.nbt
- minecraft/structures/village/plains/zombie/villagers/leatherworker.nbt
- minecraft/structures/village/plains/zombie/villagers/librarian.nbt
- minecraft/structures/village/plains/zombie/villagers/shepherd.nbt
- minecraft/structures/village/plains/zombie/villagers/toolsmith.nbt
- minecraft/structures/village/plains/zombie/villagers/weaponsmith.nbt
+ minecraft/structures/village/savanna/villagers/nitwit.nbt
+ minecraft/structures/village/savanna/villagers/unemployed.nbt
- minecraft/structures/village/savanna/zombie/villagers/armorer.nbt
- minecraft/structures/village/savanna/zombie/villagers/butcher.nbt
- minecraft/structures/village/savanna/zombie/villagers/cartographer.nbt
- minecraft/structures/village/savanna/zombie/villagers/cleric.nbt
- minecraft/structures/village/savanna/zombie/villagers/farmer.nbt
- minecraft/structures/village/savanna/zombie/villagers/fishermen.nbt
- minecraft/structures/village/savanna/zombie/villagers/fletcher.nbt
- minecraft/structures/village/savanna/zombie/villagers/leatherworker.nbt
- minecraft/structures/village/savanna/zombie/villagers/librarian.nbt
- minecraft/structures/village/savanna/zombie/villagers/shepherd.nbt
- minecraft/structures/village/savanna/zombie/villagers/toolsmith.nbt
- minecraft/structures/village/savanna/zombie/villagers/weaponsmith.nbt
+ minecraft/structures/village/snowy/villagers/nitwit.nbt
+ minecraft/structures/village/snowy/villagers/unemployed.nbt
- minecraft/structures/village/snowy/zombie/villagers/armorer.nbt
- minecraft/structures/village/snowy/zombie/villagers/butcher.nbt
- minecraft/structures/village/snowy/zombie/villagers/cartographer.nbt
- minecraft/structures/village/snowy/zombie/villagers/cleric.nbt
- minecraft/structures/village/snowy/zombie/villagers/farmer.nbt
- minecraft/structures/village/snowy/zombie/villagers/fishermen.nbt
- minecraft/structures/village/snowy/zombie/villagers/fletcher.nbt
- minecraft/structures/village/snowy/zombie/villagers/leatherworker.nbt
- minecraft/structures/village/snowy/zombie/villagers/librarian.nbt
- minecraft/structures/village/snowy/zombie/villagers/shepherd.nbt
- minecraft/structures/village/snowy/zombie/villagers/toolsmith.nbt
- minecraft/structures/village/snowy/zombie/villagers/weaponsmith.nbt
+ minecraft/structures/village/taiga/villagers/nitwit.nbt
+ minecraft/structures/village/taiga/villagers/unemployed.nbt
- minecraft/structures/village/taiga/zombie/villagers/armorer.nbt
- minecraft/structures/village/taiga/zombie/villagers/butcher.nbt
- minecraft/structures/village/taiga/zombie/villagers/cartographer.nbt
- minecraft/structures/village/taiga/zombie/villagers/cleric.nbt
- minecraft/structures/village/taiga/zombie/villagers/farmer.nbt
- minecraft/structures/village/taiga/zombie/villagers/fishermen.nbt
- minecraft/structures/village/taiga/zombie/villagers/fletcher.nbt
- minecraft/structures/village/taiga/zombie/villagers/leatherworker.nbt
- minecraft/structures/village/taiga/zombie/villagers/librarian.nbt
- minecraft/structures/village/taiga/zombie/villagers/shepherd.nbt
- minecraft/structures/village/taiga/zombie/villagers/toolsmith.nbt
- minecraft/structures/village/taiga/zombie/villagers/weaponsmith.nbt
+ minecraft/tags/blocks/armorer_poi.json
+ minecraft/tags/blocks/butcher_poi.json
+ minecraft/tags/blocks/cartographer_poi.json
+ minecraft/tags/blocks/cleric_poi.json
+ minecraft/tags/blocks/farmer_poi.json
+ minecraft/tags/blocks/fisherman_poi.json
+ minecraft/tags/blocks/fletcher_poi.json
+ minecraft/tags/blocks/job_site_poi.json
+ minecraft/tags/blocks/leatherworker_poi.json
+ minecraft/tags/blocks/librarian_poi.json
+ minecraft/tags/blocks/mason_poi.json
+ minecraft/tags/blocks/meeting_site_poi.json
+ minecraft/tags/blocks/points_of_interest.json
+ minecraft/tags/blocks/shepherd_poi.json
+ minecraft/tags/blocks/toolsmith_poi.json
+ minecraft/tags/blocks/weaponsmith_poi.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/globe_banner_pattern.json
+ minecraft/textures/entity/banner/globe.png
+ minecraft/textures/item/globe_banner_pattern.png
```

</details>
</details>
<hr/>