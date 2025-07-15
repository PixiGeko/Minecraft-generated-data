## Comparison with [18w05a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w05a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">18w05a</th><th>18w06a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>0.1.23</pre></td><td><pre>0.1.24</pre></td></tr></table>
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
+ cave_air.json
+ void_air.json
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
+ enchant.txt
```

</details>
<details>
<summary>
locate
</summary>

```diff
+ locate Desert_Pyramid
+ locate Igloo
+ locate Jungle_Pyramid
+ locate Swamp_Hut
- locate Temple
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
+ baked_potato.json
+ black_glazed_terracotta.json
+ blue_glazed_terracotta.json
+ brick.json
+ brown_glazed_terracotta.json
+ charcoal.json
+ chorus_fruit_popped.json
+ coal_from_smelting.json
+ cooked_beef.json
+ cooked_chicken.json
+ cooked_cod.json
+ cooked_mutton.json
+ cooked_porkchop.json
+ cooked_rabbit.json
+ cooked_salmon.json
+ cracked_stone_bricks.json
+ cyan_glazed_terracotta.json
+ diamond_from_smelting.json
+ emerald_from_smelting.json
+ glass.json
+ gold_ingot.json
+ gold_nugget_from_smelting.json
+ gray_glazed_terracotta.json
+ green_glazed_terracotta.json
+ iron_ingot.json
+ iron_nugget_from_smelting.json
+ lapis_from_smelting.json
+ light_blue_glazed_terracotta.json
+ light_gray_glazed_terracotta.json
+ lime_glazed_terracotta.json
+ magenta_glazed_terracotta.json
+ nether_brick.json
+ orange_glazed_terracotta.json
+ pink_glazed_terracotta.json
+ purple_glazed_terracotta.json
+ quartz.json
+ red_glazed_terracotta.json
+ redstone_from_smelting.json
+ sponge.json
+ stone.json
+ terracotta.json
+ white_glazed_terracotta.json
+ yellow_glazed_terracotta.json
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
+ argument.entity.options.advancements.description: Players with advancements
+ argument.entity.options.distance.description: Distance to entity
+ argument.entity.options.dx.description: Entities between x and dx
+ argument.entity.options.dy.description: Entities between y and dy
+ argument.entity.options.dz.description: Entities between z and dz
+ argument.entity.options.gamemode.description: Players with gamemode
+ argument.entity.options.level.description: Experience level
+ argument.entity.options.limit.description: Maximum number of entities to return
+ argument.entity.options.name.description: Entity name
+ argument.entity.options.nbt.description: Entities with NBT
+ argument.entity.options.scores.description: Entities with scores
+ argument.entity.options.sort.description: Sort the entities
+ argument.entity.options.tag.description: Entities with tag
+ argument.entity.options.team.description: Entities on team
+ argument.entity.options.type.description: Entities of type
+ argument.entity.options.x_rotation.description: Entity's x rotation
+ argument.entity.options.x.description: x position
+ argument.entity.options.y_rotation.description: Entity's y rotation
+ argument.entity.options.y.description: y position
+ argument.entity.options.z.description: z position
+ argument.entity.selector.allEntities: All entities
+ argument.entity.selector.allPlayers: All players
+ argument.entity.selector.nearestPlayer: Nearest player
+ argument.entity.selector.randomPlayer: Random player
+ argument.entity.selector.self: Current entity
+ block.minecraft.cave_air: Cave Air
+ block.minecraft.void_air: Void Air
+ commands.enchant.success.multiple: Applied enchantment %s to %s entities
+ commands.enchant.success.single: Applied enchantment %s to %s's item
+ entity.minecraft.fishing_bobber: Fishing Bobber
+ entity.minecraft.lightning_bolt: Bolt of Lightning
+ entity.minecraft.player: Player
+ selectWorld.tooltip.unsupported: This world is no longer supported and can only be played in %s
+ selectWorld.unsupported.customized.text: Unfortunately, we cannot support Customized Worlds in this version of Minecraft. Please downgrade to %s to play this world. We are sorry for the inconvenience.
+ selectWorld.unsupported.customized.title: Unsupported world!
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
+ minecraft/advancements/recipes/building_blocks/cracked_stone_bricks.json
+ minecraft/advancements/recipes/building_blocks/glass.json
+ minecraft/advancements/recipes/building_blocks/sponge.json
+ minecraft/advancements/recipes/building_blocks/stone.json
+ minecraft/advancements/recipes/building_blocks/terracotta.json
+ minecraft/advancements/recipes/decorations/black_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/blue_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/brown_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/cyan_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/gray_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/green_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/light_blue_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/light_gray_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/lime_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/magenta_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/orange_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/pink_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/purple_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/red_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/white_glazed_terracotta.json
+ minecraft/advancements/recipes/decorations/yellow_glazed_terracotta.json
+ minecraft/advancements/recipes/food/baked_potato.json
+ minecraft/advancements/recipes/food/cooked_beef.json
+ minecraft/advancements/recipes/food/cooked_chicken.json
+ minecraft/advancements/recipes/food/cooked_cod.json
+ minecraft/advancements/recipes/food/cooked_mutton.json
+ minecraft/advancements/recipes/food/cooked_porkchop.json
+ minecraft/advancements/recipes/food/cooked_rabbit.json
+ minecraft/advancements/recipes/food/cooked_salmon.json
+ minecraft/advancements/recipes/misc/brick.json
+ minecraft/advancements/recipes/misc/charcoal.json
+ minecraft/advancements/recipes/misc/chorus_fruit_popped.json
+ minecraft/advancements/recipes/misc/coal_from_smelting.json
+ minecraft/advancements/recipes/misc/diamond_from_smelting.json
+ minecraft/advancements/recipes/misc/emerald_from_smelting.json
+ minecraft/advancements/recipes/misc/gold_ingot.json
+ minecraft/advancements/recipes/misc/gold_nugget_from_smelting.json
+ minecraft/advancements/recipes/misc/iron_ingot.json
+ minecraft/advancements/recipes/misc/iron_nugget_from_smelting.json
+ minecraft/advancements/recipes/misc/lapis_from_smelting.json
+ minecraft/advancements/recipes/misc/nether_brick.json
+ minecraft/advancements/recipes/misc/quartz.json
+ minecraft/advancements/recipes/redstone/redstone_from_smelting.json
+ minecraft/recipes/baked_potato.json
+ minecraft/recipes/black_glazed_terracotta.json
+ minecraft/recipes/blue_glazed_terracotta.json
+ minecraft/recipes/brick.json
+ minecraft/recipes/brown_glazed_terracotta.json
+ minecraft/recipes/charcoal.json
+ minecraft/recipes/chorus_fruit_popped.json
+ minecraft/recipes/coal_from_smelting.json
+ minecraft/recipes/cooked_beef.json
+ minecraft/recipes/cooked_chicken.json
+ minecraft/recipes/cooked_cod.json
+ minecraft/recipes/cooked_mutton.json
+ minecraft/recipes/cooked_porkchop.json
+ minecraft/recipes/cooked_rabbit.json
+ minecraft/recipes/cooked_salmon.json
+ minecraft/recipes/cracked_stone_bricks.json
+ minecraft/recipes/cyan_glazed_terracotta.json
+ minecraft/recipes/diamond_from_smelting.json
+ minecraft/recipes/emerald_from_smelting.json
+ minecraft/recipes/glass.json
+ minecraft/recipes/gold_ingot.json
+ minecraft/recipes/gold_nugget_from_smelting.json
+ minecraft/recipes/gray_glazed_terracotta.json
+ minecraft/recipes/green_glazed_terracotta.json
+ minecraft/recipes/iron_ingot.json
+ minecraft/recipes/iron_nugget_from_smelting.json
+ minecraft/recipes/lapis_from_smelting.json
+ minecraft/recipes/light_blue_glazed_terracotta.json
+ minecraft/recipes/light_gray_glazed_terracotta.json
+ minecraft/recipes/lime_glazed_terracotta.json
+ minecraft/recipes/magenta_glazed_terracotta.json
+ minecraft/recipes/nether_brick.json
+ minecraft/recipes/orange_glazed_terracotta.json
+ minecraft/recipes/pink_glazed_terracotta.json
+ minecraft/recipes/purple_glazed_terracotta.json
+ minecraft/recipes/quartz.json
+ minecraft/recipes/red_glazed_terracotta.json
+ minecraft/recipes/redstone_from_smelting.json
+ minecraft/recipes/sponge.json
+ minecraft/recipes/stone.json
+ minecraft/recipes/terracotta.json
+ minecraft/recipes/white_glazed_terracotta.json
+ minecraft/recipes/yellow_glazed_terracotta.json
+ minecraft/tags/blocks/banners.json
+ minecraft/tags/blocks/wooden_pressure_plates.json
+ minecraft/tags/blocks/wooden_slabs.json
+ minecraft/tags/blocks/wooden_stairs.json
+ minecraft/tags/items/banners.json
+ minecraft/tags/items/boats.json
+ minecraft/tags/items/wooden_pressure_plates.json
+ minecraft/tags/items/wooden_slabs.json
+ minecraft/tags/items/wooden_stairs.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/gui/container/recipe_background.png
+ minecraft/textures/gui/recipe_button.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:item_enchantment
```

</details>
</details>
<hr/>