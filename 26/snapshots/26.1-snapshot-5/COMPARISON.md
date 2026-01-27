## Comparison with [26.1-snapshot-4](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-4)

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
<table><tr><th></th><th align="left">26.1-snapshot-4</th><th>26.1-snapshot-5</th></tr><tr><td>DataPack version</td><td><pre>97.1</pre></td><td><pre>98.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>78.1</pre></td><td><pre>79.0</pre></td></tr><tr><td>World version</td><td><pre>4768</pre></td><td><pre>4770</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742114</pre></td><td><pre>1073742115</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.1-snapshot-4</th><th>26.1-snapshot-5</th></tr><tr><td>com.mojang:authlib</td><td><pre>7.0.61</pre></td><td><pre>7.0.62</pre></td></tr></table>
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
+ minecraft:golden_dandelion
+ minecraft:potted_golden_dandelion
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:dye
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:golden_dandelion
```

</details>
<details>
<summary>
recipe_serializer
</summary>

```diff
+ minecraft:crafting_dye
+ minecraft:crafting_imbue
- minecraft:crafting_special_armordye
- minecraft:crafting_special_mapcloning
- minecraft:crafting_special_tippedarrow
```

</details>
<details>
<summary>
slot_display
</summary>

```diff
+ minecraft:dyed
+ minecraft:only_with_component
+ minecraft:with_any_potion
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.baby_chicken.ambient
+ minecraft:entity.baby_chicken.death
+ minecraft:entity.baby_chicken.hurt
+ minecraft:item.golden_dandelion.unuse
+ minecraft:item.golden_dandelion.use
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
+ minecraft:golden_dandelion
+ minecraft:potted_golden_dandelion
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:golden_dandelion
+ minecraft:potted_golden_dandelion
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:dye
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:golden_dandelion
```

</details>
<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
+ minecraft:crafting_dye
+ minecraft:crafting_imbue
- minecraft:crafting_special_armordye
- minecraft:crafting_special_mapcloning
- minecraft:crafting_special_tippedarrow
```

</details>
<details>
<summary>
universal_tags/slot_display.json
</summary>

```diff
+ minecraft:dyed
+ minecraft:only_with_component
+ minecraft:with_any_potion
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.baby_chicken.ambient
+ minecraft:entity.baby_chicken.death
+ minecraft:entity.baby_chicken.hurt
+ minecraft:item.golden_dandelion.unuse
+ minecraft:item.golden_dandelion.use
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
+ golden_dandelion.json
+ potted_golden_dandelion.json
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
- armor_dye.json
- banner_duplicate.json
+ black_banner_duplicate.json
+ blue_banner_duplicate.json
+ brown_banner_duplicate.json
+ chiseled_stone_bricks_from_stone_stonecutting.json
- chiseled_stone_bricks_stone_from_stonecutting.json
+ cyan_banner_duplicate.json
- end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+ end_stone_brick_slab_from_end_stone_bricks_stonecutting.json
- end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+ end_stone_brick_stairs_from_end_stone_bricks_stonecutting.json
- end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ end_stone_brick_wall_from_end_stone_bricks_stonecutting.json
+ golden_dandelion.json
+ gray_banner_duplicate.json
+ green_banner_duplicate.json
+ leather_boots_dyed.json
+ leather_chestplate_dyed.json
+ leather_helmet_dyed.json
+ leather_horse_armor_dyed.json
+ leather_leggings_dyed.json
+ light_blue_banner_duplicate.json
+ light_gray_banner_duplicate.json
+ lime_banner_duplicate.json
+ magenta_banner_duplicate.json
- mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+ mossy_stone_brick_slab_from_mossy_stone_bricks_stonecutting.json
- mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+ mossy_stone_brick_stairs_from_mossy_stone_bricks_stonecutting.json
- mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ mossy_stone_brick_wall_from_mossy_stone_bricks_stonecutting.json
+ orange_banner_duplicate.json
+ pink_banner_duplicate.json
+ prismarine_brick_slab_from_prismarine_bricks_stonecutting.json
- prismarine_brick_slab_from_prismarine_stonecutting.json
+ prismarine_brick_stairs_from_prismarine_bricks_stonecutting.json
- prismarine_brick_stairs_from_prismarine_stonecutting.json
+ purple_banner_duplicate.json
+ quartz_slab_from_quartz_block_stonecutting.json
- quartz_slab_from_stonecutting.json
+ red_banner_duplicate.json
+ stone_brick_wall_from_stone_stonecutting.json
- stone_brick_walls_from_stone_stonecutting.json
+ suspicious_stew_from_golden_dandelion.json
+ white_banner_duplicate.json
+ wolf_armor_dyed.json
+ yellow_banner_duplicate.json
+ yellow_dye_from_golden_dandelion.json
```

</details>
<details>
<summary>
book_cloning.json
</summary>

```
Category: misc -> none
Result:  x1 -> written_book x1
```

</details>
<details>
<summary>
decorated_pot.json
</summary>

```
Category: misc -> none
Result:  x1 -> decorated_pot x1
```

</details>
<details>
<summary>
firework_rocket.json
</summary>

```
Category: misc -> none
Result:  x1 -> firework_rocket x3
```

</details>
<details>
<summary>
firework_star.json
</summary>

```
Category: misc -> none
Result:  x1 -> firework_star x1
```

</details>
<details>
<summary>
firework_star_fade.json
</summary>

```
Category: misc -> none
Result:  x1 -> firework_star x1
```

</details>
<details>
<summary>
map_cloning.json
</summary>

```
Type: minecraft:crafting_special_mapcloning -> minecraft:crafting_transmute
Group: none -> map_cloning
Result:  x1 -> filled_map x1
```

</details>
<details>
<summary>
map_extending.json
</summary>

```
Category: misc -> none
Result:  x1 -> filled_map x1
```

</details>
<details>
<summary>
repair_item.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
shield_decoration.json
</summary>

```
Category: misc -> none
Result:  x1 -> shield x1
```

</details>
<details>
<summary>
tipped_arrow.json
</summary>

```
Type: minecraft:crafting_special_tippedarrow -> minecraft:crafting_imbue
Result:  x1 -> tipped_arrow x8
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
+ block.minecraft.golden_dandelion: Golden Dandelion
+ block.minecraft.potted_golden_dandelion: Potted Golden Dandelion
+ subtitles.entity.baby_chicken.ambient: Chick peeps
+ subtitles.entity.baby_chicken.death: Chick dies
+ subtitles.entity.baby_chicken.hurts: Chick hurts
+ subtitles.entity.baby_horse.ambient: Foal neighs
+ subtitles.entity.baby_horse.angry: Foal neighs
+ subtitles.entity.baby_horse.breathe: Foal breathes
+ subtitles.entity.baby_horse.death: Foal dies
+ subtitles.entity.baby_horse.eat: Foal eats
+ subtitles.entity.baby_horse.hurt: Foal hurts
+ subtitles.item.golden_dandelion.unuse: Golden Dandelion starts aging
+ subtitles.item.golden_dandelion.use: Golden Dandelion halts aging
```

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
+ reports/minecraft/components/block/golden_dandelion.json
+ reports/minecraft/components/block/potted_golden_dandelion.json
+ reports/minecraft/components/data_component_type/dye.json
+ reports/minecraft/components/item/golden_dandelion.json
+ reports/minecraft/components/recipe_serializer/crafting_dye.json
+ reports/minecraft/components/recipe_serializer/crafting_imbue.json
- reports/minecraft/components/recipe_serializer/crafting_special_armordye.json
- reports/minecraft/components/recipe_serializer/crafting_special_mapcloning.json
- reports/minecraft/components/recipe_serializer/crafting_special_tippedarrow.json
+ reports/minecraft/components/slot_display/dyed.json
+ reports/minecraft/components/slot_display/only_with_component.json
+ reports/minecraft/components/slot_display/with_any_potion.json
+ reports/minecraft/components/sound_event/entity.baby_chicken.ambient.json
+ reports/minecraft/components/sound_event/entity.baby_chicken.death.json
+ reports/minecraft/components/sound_event/entity.baby_chicken.hurt.json
+ reports/minecraft/components/sound_event/item.golden_dandelion.unuse.json
+ reports/minecraft/components/sound_event/item.golden_dandelion.use.json
+ reports/minecraft/components/villager_trade/wandering_trader/emerald_golden_dandelion.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/chiseled_stone_bricks_from_stone_stonecutting.json
- minecraft/advancement/recipes/building_blocks/chiseled_stone_bricks_stone_from_stonecutting.json
- minecraft/advancement/recipes/building_blocks/end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/end_stone_brick_slab_from_end_stone_bricks_stonecutting.json
- minecraft/advancement/recipes/building_blocks/end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/end_stone_brick_stairs_from_end_stone_bricks_stonecutting.json
- minecraft/advancement/recipes/building_blocks/mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/mossy_stone_brick_slab_from_mossy_stone_bricks_stonecutting.json
- minecraft/advancement/recipes/building_blocks/mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/mossy_stone_brick_stairs_from_mossy_stone_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/prismarine_brick_slab_from_prismarine_bricks_stonecutting.json
- minecraft/advancement/recipes/building_blocks/prismarine_brick_slab_from_prismarine_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/prismarine_brick_stairs_from_prismarine_bricks_stonecutting.json
- minecraft/advancement/recipes/building_blocks/prismarine_brick_stairs_from_prismarine_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/quartz_slab_from_quartz_block_stonecutting.json
- minecraft/advancement/recipes/building_blocks/quartz_slab_from_stonecutting.json
- minecraft/advancement/recipes/decorations/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/decorations/end_stone_brick_wall_from_end_stone_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/golden_dandelion.json
- minecraft/advancement/recipes/decorations/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ minecraft/advancement/recipes/decorations/mossy_stone_brick_wall_from_mossy_stone_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/stone_brick_wall_from_stone_stonecutting.json
- minecraft/advancement/recipes/decorations/stone_brick_walls_from_stone_stonecutting.json
+ minecraft/advancement/recipes/food/suspicious_stew_from_golden_dandelion.json
+ minecraft/advancement/recipes/misc/leather_boots_dyed.json
+ minecraft/advancement/recipes/misc/leather_chestplate_dyed.json
+ minecraft/advancement/recipes/misc/leather_helmet_dyed.json
+ minecraft/advancement/recipes/misc/leather_horse_armor_dyed.json
+ minecraft/advancement/recipes/misc/leather_leggings_dyed.json
+ minecraft/advancement/recipes/misc/map_cloning.json
+ minecraft/advancement/recipes/misc/tipped_arrow.json
+ minecraft/advancement/recipes/misc/wolf_armor_dyed.json
+ minecraft/advancement/recipes/misc/yellow_dye_from_golden_dandelion.json
+ minecraft/loot_table/blocks/golden_dandelion.json
+ minecraft/loot_table/blocks/potted_golden_dandelion.json
- minecraft/recipe/armor_dye.json
- minecraft/recipe/banner_duplicate.json
+ minecraft/recipe/black_banner_duplicate.json
+ minecraft/recipe/blue_banner_duplicate.json
+ minecraft/recipe/brown_banner_duplicate.json
+ minecraft/recipe/chiseled_stone_bricks_from_stone_stonecutting.json
- minecraft/recipe/chiseled_stone_bricks_stone_from_stonecutting.json
+ minecraft/recipe/cyan_banner_duplicate.json
- minecraft/recipe/end_stone_brick_slab_from_end_stone_brick_stonecutting.json
+ minecraft/recipe/end_stone_brick_slab_from_end_stone_bricks_stonecutting.json
- minecraft/recipe/end_stone_brick_stairs_from_end_stone_brick_stonecutting.json
+ minecraft/recipe/end_stone_brick_stairs_from_end_stone_bricks_stonecutting.json
- minecraft/recipe/end_stone_brick_wall_from_end_stone_brick_stonecutting.json
+ minecraft/recipe/end_stone_brick_wall_from_end_stone_bricks_stonecutting.json
+ minecraft/recipe/golden_dandelion.json
+ minecraft/recipe/gray_banner_duplicate.json
+ minecraft/recipe/green_banner_duplicate.json
+ minecraft/recipe/leather_boots_dyed.json
+ minecraft/recipe/leather_chestplate_dyed.json
+ minecraft/recipe/leather_helmet_dyed.json
+ minecraft/recipe/leather_horse_armor_dyed.json
+ minecraft/recipe/leather_leggings_dyed.json
+ minecraft/recipe/light_blue_banner_duplicate.json
+ minecraft/recipe/light_gray_banner_duplicate.json
+ minecraft/recipe/lime_banner_duplicate.json
+ minecraft/recipe/magenta_banner_duplicate.json
- minecraft/recipe/mossy_stone_brick_slab_from_mossy_stone_brick_stonecutting.json
+ minecraft/recipe/mossy_stone_brick_slab_from_mossy_stone_bricks_stonecutting.json
- minecraft/recipe/mossy_stone_brick_stairs_from_mossy_stone_brick_stonecutting.json
+ minecraft/recipe/mossy_stone_brick_stairs_from_mossy_stone_bricks_stonecutting.json
- minecraft/recipe/mossy_stone_brick_wall_from_mossy_stone_brick_stonecutting.json
+ minecraft/recipe/mossy_stone_brick_wall_from_mossy_stone_bricks_stonecutting.json
+ minecraft/recipe/orange_banner_duplicate.json
+ minecraft/recipe/pink_banner_duplicate.json
+ minecraft/recipe/prismarine_brick_slab_from_prismarine_bricks_stonecutting.json
- minecraft/recipe/prismarine_brick_slab_from_prismarine_stonecutting.json
+ minecraft/recipe/prismarine_brick_stairs_from_prismarine_bricks_stonecutting.json
- minecraft/recipe/prismarine_brick_stairs_from_prismarine_stonecutting.json
+ minecraft/recipe/purple_banner_duplicate.json
+ minecraft/recipe/quartz_slab_from_quartz_block_stonecutting.json
- minecraft/recipe/quartz_slab_from_stonecutting.json
+ minecraft/recipe/red_banner_duplicate.json
+ minecraft/recipe/stone_brick_wall_from_stone_stonecutting.json
- minecraft/recipe/stone_brick_walls_from_stone_stonecutting.json
+ minecraft/recipe/suspicious_stew_from_golden_dandelion.json
+ minecraft/recipe/white_banner_duplicate.json
+ minecraft/recipe/wolf_armor_dyed.json
+ minecraft/recipe/yellow_banner_duplicate.json
+ minecraft/recipe/yellow_dye_from_golden_dandelion.json
+ minecraft/tags/entity_type/cannot_be_age_locked.json
+ minecraft/tags/item/cat_collar_dyes.json
+ minecraft/tags/item/cauldron_can_remove_dye.json
- minecraft/tags/item/dyeable.json
+ minecraft/tags/item/dyes.json
+ minecraft/tags/item/loom_dyes.json
+ minecraft/tags/item/loom_patterns.json
+ minecraft/tags/item/wolf_collar_dyes.json
+ minecraft/villager_trade/wandering_trader/emerald_golden_dandelion.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/golden_dandelion.json
+ minecraft/blockstates/potted_golden_dandelion.json
+ minecraft/items/golden_dandelion.json
+ minecraft/models/block/golden_dandelion.json
+ minecraft/models/block/potted_golden_dandelion.json
+ minecraft/models/item/golden_dandelion.json
+ minecraft/textures/block/golden_dandelion.png
+ minecraft/textures/entity/axolotl/axolotl_blue_baby.png
+ minecraft/textures/entity/axolotl/axolotl_cyan_baby.png
+ minecraft/textures/entity/axolotl/axolotl_gold_baby.png
+ minecraft/textures/entity/axolotl/axolotl_lucy_baby.png
+ minecraft/textures/entity/axolotl/axolotl_wild_baby.png
+ minecraft/textures/entity/dolphin/dolphin_baby.png
+ minecraft/textures/entity/squid/glow_squid_baby.png
+ minecraft/textures/entity/squid/squid_baby.png
+ minecraft/textures/entity/turtle/turtle_baby.png
- minecraft/textures/gui/demo_background.png
```

</details>
</details>
<hr/>