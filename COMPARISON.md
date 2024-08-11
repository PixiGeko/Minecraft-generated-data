## Comparison with [18w47b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w47b)

- [Version data](#version-data)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">18w47b</th><th>18w48a</th></tr><tr><td>World version</td><td><code>1913</code></td><td><code>1914</code></td></tr><tr><td>Protocol version</td><td><code>447</code></td><td><code>448</code></td></tr></table>
</details>
<details><summary>Commands</summary>
<details>
<summary>
locate
</summary>

```diff
+ locate New_Village
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ grindstone.json
- repair_item.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ container.grindstone_title: Repair & Disenchant
+ subtitles.block.grindstone.use: Grindstone used
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/decorations/grindstone.json
- minecraft/loot_tables/chests/village_blacksmith.json
+ minecraft/loot_tables/chests/village/village_cartographer.json
+ minecraft/loot_tables/chests/village/village_desert_house.json
+ minecraft/loot_tables/chests/village/village_plains_house.json
+ minecraft/loot_tables/chests/village/village_savanna_house.json
+ minecraft/loot_tables/chests/village/village_snowy_house.json
+ minecraft/loot_tables/chests/village/village_taiga_house.json
+ minecraft/loot_tables/chests/village/village_tannery.json
+ minecraft/loot_tables/chests/village/village_weaponsmith.json
+ minecraft/recipes/grindstone.json
- minecraft/recipes/repair_item.json
+ minecraft/structures/village/common/animals/cows_1.nbt
+ minecraft/structures/village/common/animals/horses_1.nbt
+ minecraft/structures/village/common/animals/horses_2.nbt
+ minecraft/structures/village/common/animals/horses_3.nbt
+ minecraft/structures/village/common/animals/horses_4.nbt
+ minecraft/structures/village/common/animals/horses_5.nbt
+ minecraft/structures/village/common/animals/pigs_1.nbt
+ minecraft/structures/village/common/animals/sheep_1.nbt
+ minecraft/structures/village/common/animals/sheep_2.nbt
+ minecraft/structures/village/common/well_bottom.nbt
+ minecraft/structures/village/decays/grass_11x13.nbt
+ minecraft/structures/village/decays/grass_16x16.nbt
+ minecraft/structures/village/decays/grass_9x9.nbt
+ minecraft/structures/village/plains/houses/plains_accessory_1.nbt
+ minecraft/structures/village/plains/houses/plains_animal_pen_1.nbt
+ minecraft/structures/village/plains/houses/plains_animal_pen_2.nbt
+ minecraft/structures/village/plains/houses/plains_animal_pen_3.nbt
+ minecraft/structures/village/plains/houses/plains_armorer_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_big_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_butcher_shop_1.nbt
+ minecraft/structures/village/plains/houses/plains_butcher_shop_2.nbt
+ minecraft/structures/village/plains/houses/plains_cartographer_1.nbt
+ minecraft/structures/village/plains/houses/plains_fisher_cottage_1.nbt
+ minecraft/structures/village/plains/houses/plains_fletcher_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_large_farm_1.nbt
+ minecraft/structures/village/plains/houses/plains_library_1.nbt
+ minecraft/structures/village/plains/houses/plains_library_2.nbt
+ minecraft/structures/village/plains/houses/plains_masons_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_medium_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_medium_house_2.nbt
+ minecraft/structures/village/plains/houses/plains_meeting_point_4.nbt
+ minecraft/structures/village/plains/houses/plains_meeting_point_5.nbt
+ minecraft/structures/village/plains/houses/plains_shepherds_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_small_farm_1.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_1.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_2.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_3.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_4.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_5.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_6.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_7.nbt
+ minecraft/structures/village/plains/houses/plains_small_house_8.nbt
+ minecraft/structures/village/plains/houses/plains_stable_1.nbt
+ minecraft/structures/village/plains/houses/plains_stable_2.nbt
+ minecraft/structures/village/plains/houses/plains_tannery_1.nbt
+ minecraft/structures/village/plains/houses/plains_temple_3.nbt
+ minecraft/structures/village/plains/houses/plains_temple_4.nbt
+ minecraft/structures/village/plains/houses/plains_tool_smith_1.nbt
+ minecraft/structures/village/plains/houses/plains_weaponsmith_1.nbt
+ minecraft/structures/village/plains/plains_lamp_1.nbt
+ minecraft/structures/village/plains/streets/corner_01.nbt
+ minecraft/structures/village/plains/streets/corner_02.nbt
+ minecraft/structures/village/plains/streets/corner_03.nbt
+ minecraft/structures/village/plains/streets/crossroad_01.nbt
+ minecraft/structures/village/plains/streets/crossroad_02.nbt
+ minecraft/structures/village/plains/streets/crossroad_03.nbt
+ minecraft/structures/village/plains/streets/crossroad_04.nbt
+ minecraft/structures/village/plains/streets/crossroad_05.nbt
+ minecraft/structures/village/plains/streets/crossroad_06.nbt
+ minecraft/structures/village/plains/streets/straight_01.nbt
+ minecraft/structures/village/plains/streets/straight_02.nbt
+ minecraft/structures/village/plains/streets/straight_03.nbt
+ minecraft/structures/village/plains/streets/straight_04.nbt
+ minecraft/structures/village/plains/streets/straight_05.nbt
+ minecraft/structures/village/plains/streets/straight_06.nbt
+ minecraft/structures/village/plains/streets/turn_01.nbt
+ minecraft/structures/village/plains/terminators/terminator_01.nbt
+ minecraft/structures/village/plains/terminators/terminator_02.nbt
+ minecraft/structures/village/plains/terminators/terminator_03.nbt
+ minecraft/structures/village/plains/terminators/terminator_04.nbt
+ minecraft/structures/village/plains/town_centers/plains_fountain_01.nbt
+ minecraft/structures/village/plains/town_centers/plains_meeting_point_1.nbt
+ minecraft/structures/village/plains/town_centers/plains_meeting_point_2.nbt
+ minecraft/structures/village/plains/town_centers/plains_meeting_point_3.nbt
+ minecraft/structures/village/plains/villagers/armorer.nbt
+ minecraft/structures/village/plains/villagers/butcher.nbt
+ minecraft/structures/village/plains/villagers/cartographer.nbt
+ minecraft/structures/village/plains/villagers/cleric.nbt
+ minecraft/structures/village/plains/villagers/farmer.nbt
+ minecraft/structures/village/plains/villagers/fishermen.nbt
+ minecraft/structures/village/plains/villagers/fletcher.nbt
+ minecraft/structures/village/plains/villagers/leatherworker.nbt
+ minecraft/structures/village/plains/villagers/librarian.nbt
+ minecraft/structures/village/plains/villagers/nitwit.nbt
+ minecraft/structures/village/plains/villagers/shepherd.nbt
+ minecraft/structures/village/plains/villagers/toolsmith.nbt
+ minecraft/structures/village/plains/villagers/unemployed.nbt
+ minecraft/structures/village/plains/villagers/weaponsmith.nbt
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/container/grindstone.png
```

</details>
</details>