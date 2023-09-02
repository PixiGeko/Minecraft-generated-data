<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w48a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w48a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-11-29T13:11:38+00:00</td></tr>
<tr><th>SHA1</th><td>fff0948616360b5545f236e5900af4c7c6da5d86</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/fff0948616360b5545f236e5900af4c7c6da5d86/18w48a.json">https://piston-meta.mojang.com/v1/packages/fff0948616360b5545f236e5900af4c7c6da5d86/18w48a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/f0f04983d197388b05a4647f7a7cf8b5fbbac5d3/server.jar">https://piston-data.mojang.com/v1/objects/f0f04983d197388b05a4647f7a7cf8b5fbbac5d3/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/8c2c778a22201836bf482a8ed06e1b1f994c61e3/client.jar">https://piston-data.mojang.com/v1/objects/8c2c778a22201836bf482a8ed06e1b1f994c61e3/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w47b">18w47b</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/decorations/grindstone.json
+  minecraft/loot_tables/chests/village
+  minecraft/loot_tables/chests/village/village_cartographer.json
+  minecraft/loot_tables/chests/village/village_desert_house.json
+  minecraft/loot_tables/chests/village/village_plains_house.json
+  minecraft/loot_tables/chests/village/village_savanna_house.json
+  minecraft/loot_tables/chests/village/village_snowy_house.json
+  minecraft/loot_tables/chests/village/village_taiga_house.json
+  minecraft/loot_tables/chests/village/village_tannery.json
+  minecraft/loot_tables/chests/village/village_weaponsmith.json
-  minecraft/loot_tables/chests/village_blacksmith.json
+  minecraft/recipes/grindstone.json
-  minecraft/recipes/repair_item.json
+  minecraft/structures/village
+  minecraft/structures/village/common
+  minecraft/structures/village/common/animals
+  minecraft/structures/village/common/animals/cows_1.nbt
+  minecraft/structures/village/common/animals/horses_1.nbt
+  minecraft/structures/village/common/animals/horses_2.nbt
+  minecraft/structures/village/common/animals/horses_3.nbt
+  minecraft/structures/village/common/animals/horses_4.nbt
+  minecraft/structures/village/common/animals/horses_5.nbt
+  minecraft/structures/village/common/animals/pigs_1.nbt
+  minecraft/structures/village/common/animals/sheep_1.nbt
+  minecraft/structures/village/common/animals/sheep_2.nbt
+  minecraft/structures/village/common/well_bottom.nbt
+  minecraft/structures/village/decays
+  minecraft/structures/village/decays/grass_11x13.nbt
+  minecraft/structures/village/decays/grass_16x16.nbt
+  minecraft/structures/village/decays/grass_9x9.nbt
+  minecraft/structures/village/plains
+  minecraft/structures/village/plains/houses
+  minecraft/structures/village/plains/houses/plains_accessory_1.nbt
+  minecraft/structures/village/plains/houses/plains_animal_pen_1.nbt
+  minecraft/structures/village/plains/houses/plains_animal_pen_2.nbt
+  minecraft/structures/village/plains/houses/plains_animal_pen_3.nbt
+  minecraft/structures/village/plains/houses/plains_armorer_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_big_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_butcher_shop_1.nbt
+  minecraft/structures/village/plains/houses/plains_butcher_shop_2.nbt
+  minecraft/structures/village/plains/houses/plains_cartographer_1.nbt
+  minecraft/structures/village/plains/houses/plains_fisher_cottage_1.nbt
+  minecraft/structures/village/plains/houses/plains_fletcher_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_large_farm_1.nbt
+  minecraft/structures/village/plains/houses/plains_library_1.nbt
+  minecraft/structures/village/plains/houses/plains_library_2.nbt
+  minecraft/structures/village/plains/houses/plains_masons_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_medium_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_medium_house_2.nbt
+  minecraft/structures/village/plains/houses/plains_meeting_point_4.nbt
+  minecraft/structures/village/plains/houses/plains_meeting_point_5.nbt
+  minecraft/structures/village/plains/houses/plains_shepherds_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_small_farm_1.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_1.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_2.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_3.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_4.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_5.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_6.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_7.nbt
+  minecraft/structures/village/plains/houses/plains_small_house_8.nbt
+  minecraft/structures/village/plains/houses/plains_stable_1.nbt
+  minecraft/structures/village/plains/houses/plains_stable_2.nbt
+  minecraft/structures/village/plains/houses/plains_tannery_1.nbt
+  minecraft/structures/village/plains/houses/plains_temple_3.nbt
+  minecraft/structures/village/plains/houses/plains_temple_4.nbt
+  minecraft/structures/village/plains/houses/plains_tool_smith_1.nbt
+  minecraft/structures/village/plains/houses/plains_weaponsmith_1.nbt
+  minecraft/structures/village/plains/streets
+  minecraft/structures/village/plains/streets/corner_01.nbt
+  minecraft/structures/village/plains/streets/corner_02.nbt
+  minecraft/structures/village/plains/streets/corner_03.nbt
+  minecraft/structures/village/plains/streets/crossroad_01.nbt
+  minecraft/structures/village/plains/streets/crossroad_02.nbt
+  minecraft/structures/village/plains/streets/crossroad_03.nbt
+  minecraft/structures/village/plains/streets/crossroad_04.nbt
+  minecraft/structures/village/plains/streets/crossroad_05.nbt
+  minecraft/structures/village/plains/streets/crossroad_06.nbt
+  minecraft/structures/village/plains/streets/straight_01.nbt
+  minecraft/structures/village/plains/streets/straight_02.nbt
+  minecraft/structures/village/plains/streets/straight_03.nbt
+  minecraft/structures/village/plains/streets/straight_04.nbt
+  minecraft/structures/village/plains/streets/straight_05.nbt
+  minecraft/structures/village/plains/streets/straight_06.nbt
+  minecraft/structures/village/plains/streets/turn_01.nbt
+  minecraft/structures/village/plains/terminators
+  minecraft/structures/village/plains/terminators/terminator_01.nbt
+  minecraft/structures/village/plains/terminators/terminator_02.nbt
+  minecraft/structures/village/plains/terminators/terminator_03.nbt
+  minecraft/structures/village/plains/terminators/terminator_04.nbt
+  minecraft/structures/village/plains/town_centers
+  minecraft/structures/village/plains/town_centers/plains_fountain_01.nbt
+  minecraft/structures/village/plains/town_centers/plains_meeting_point_1.nbt
+  minecraft/structures/village/plains/town_centers/plains_meeting_point_2.nbt
+  minecraft/structures/village/plains/town_centers/plains_meeting_point_3.nbt
+  minecraft/structures/village/plains/villagers
+  minecraft/structures/village/plains/villagers/armorer.nbt
+  minecraft/structures/village/plains/villagers/butcher.nbt
+  minecraft/structures/village/plains/villagers/cartographer.nbt
+  minecraft/structures/village/plains/villagers/cleric.nbt
+  minecraft/structures/village/plains/villagers/farmer.nbt
+  minecraft/structures/village/plains/villagers/fishermen.nbt
+  minecraft/structures/village/plains/villagers/fletcher.nbt
+  minecraft/structures/village/plains/villagers/leatherworker.nbt
+  minecraft/structures/village/plains/villagers/librarian.nbt
+  minecraft/structures/village/plains/villagers/nitwit.nbt
+  minecraft/structures/village/plains/villagers/shepherd.nbt
+  minecraft/structures/village/plains/villagers/toolsmith.nbt
+  minecraft/structures/village/plains/villagers/unemployed.nbt
+  minecraft/structures/village/plains/villagers/weaponsmith.nbt
+  minecraft/structures/village/plains/plains_lamp_1.nbt
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/textures/gui/container/grindstone.png
```

</details>

## Commands

<details><summary>locate.txt</summary>

```diff
+ locate New_Village
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/decorations/grindstone.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
- chests/village_blacksmith.json
+ chests/village/village_cartographer.json
+ chests/village/village_desert_house.json
+ chests/village/village_plains_house.json
+ chests/village/village_savanna_house.json
+ chests/village/village_snowy_house.json
+ chests/village/village_taiga_house.json
+ chests/village/village_tannery.json
+ chests/village/village_weaponsmith.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- repair_item.json
+ grindstone.json
```

</details>

<details><summary>structures.txt</summary>

```diff
+ village/common/animals/cows_1.nbt
+ village/common/animals/horses_1.nbt
+ village/common/animals/horses_2.nbt
+ village/common/animals/horses_3.nbt
+ village/common/animals/horses_4.nbt
+ village/common/animals/horses_5.nbt
+ village/common/animals/pigs_1.nbt
+ village/common/animals/sheep_1.nbt
+ village/common/animals/sheep_2.nbt
+ village/common/well_bottom.nbt
+ village/decays/grass_11x13.nbt
+ village/decays/grass_16x16.nbt
+ village/decays/grass_9x9.nbt
+ village/plains/houses/plains_accessory_1.nbt
+ village/plains/houses/plains_animal_pen_1.nbt
+ village/plains/houses/plains_animal_pen_2.nbt
+ village/plains/houses/plains_animal_pen_3.nbt
+ village/plains/houses/plains_armorer_house_1.nbt
+ village/plains/houses/plains_big_house_1.nbt
+ village/plains/houses/plains_butcher_shop_1.nbt
+ village/plains/houses/plains_butcher_shop_2.nbt
+ village/plains/houses/plains_cartographer_1.nbt
+ village/plains/houses/plains_fisher_cottage_1.nbt
+ village/plains/houses/plains_fletcher_house_1.nbt
+ village/plains/houses/plains_large_farm_1.nbt
+ village/plains/houses/plains_library_1.nbt
+ village/plains/houses/plains_library_2.nbt
+ village/plains/houses/plains_masons_house_1.nbt
+ village/plains/houses/plains_medium_house_1.nbt
+ village/plains/houses/plains_medium_house_2.nbt
+ village/plains/houses/plains_meeting_point_4.nbt
+ village/plains/houses/plains_meeting_point_5.nbt
+ village/plains/houses/plains_shepherds_house_1.nbt
+ village/plains/houses/plains_small_farm_1.nbt
+ village/plains/houses/plains_small_house_1.nbt
+ village/plains/houses/plains_small_house_2.nbt
+ village/plains/houses/plains_small_house_3.nbt
+ village/plains/houses/plains_small_house_4.nbt
+ village/plains/houses/plains_small_house_5.nbt
+ village/plains/houses/plains_small_house_6.nbt
+ village/plains/houses/plains_small_house_7.nbt
+ village/plains/houses/plains_small_house_8.nbt
+ village/plains/houses/plains_stable_1.nbt
+ village/plains/houses/plains_stable_2.nbt
+ village/plains/houses/plains_tannery_1.nbt
+ village/plains/houses/plains_temple_3.nbt
+ village/plains/houses/plains_temple_4.nbt
+ village/plains/houses/plains_tool_smith_1.nbt
+ village/plains/houses/plains_weaponsmith_1.nbt
+ village/plains/plains_lamp_1.nbt
+ village/plains/streets/corner_01.nbt
+ village/plains/streets/corner_02.nbt
+ village/plains/streets/corner_03.nbt
+ village/plains/streets/crossroad_01.nbt
+ village/plains/streets/crossroad_02.nbt
+ village/plains/streets/crossroad_03.nbt
+ village/plains/streets/crossroad_04.nbt
+ village/plains/streets/crossroad_05.nbt
+ village/plains/streets/crossroad_06.nbt
+ village/plains/streets/straight_01.nbt
+ village/plains/streets/straight_02.nbt
+ village/plains/streets/straight_03.nbt
+ village/plains/streets/straight_04.nbt
+ village/plains/streets/straight_05.nbt
+ village/plains/streets/straight_06.nbt
+ village/plains/streets/turn_01.nbt
+ village/plains/terminators/terminator_01.nbt
+ village/plains/terminators/terminator_02.nbt
+ village/plains/terminators/terminator_03.nbt
+ village/plains/terminators/terminator_04.nbt
+ village/plains/town_centers/plains_fountain_01.nbt
+ village/plains/town_centers/plains_meeting_point_1.nbt
+ village/plains/town_centers/plains_meeting_point_2.nbt
+ village/plains/town_centers/plains_meeting_point_3.nbt
+ village/plains/villagers/armorer.nbt
+ village/plains/villagers/butcher.nbt
+ village/plains/villagers/cartographer.nbt
+ village/plains/villagers/cleric.nbt
+ village/plains/villagers/farmer.nbt
+ village/plains/villagers/fishermen.nbt
+ village/plains/villagers/fletcher.nbt
+ village/plains/villagers/leatherworker.nbt
+ village/plains/villagers/librarian.nbt
+ village/plains/villagers/nitwit.nbt
+ village/plains/villagers/shepherd.nbt
+ village/plains/villagers/toolsmith.nbt
+ village/plains/villagers/unemployed.nbt
+ village/plains/villagers/weaponsmith.nbt
```

</details>

<details><summary>textures.txt</summary>

```diff
+ gui/container/grindstone.png
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
+ com.mojang:javabridge:1.0.22
```

</details>

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>