<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w49a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w49a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-12-05T12:24:30+00:00</td></tr>
<tr><th>SHA1</th><td>7e37cc7f1f8c8d9cde81b7754fda64954578170a</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/7e37cc7f1f8c8d9cde81b7754fda64954578170a/18w49a.json">https://piston-meta.mojang.com/v1/packages/7e37cc7f1f8c8d9cde81b7754fda64954578170a/18w49a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/5b6eb767f6708d351e3d1009a44115bb033b854f/server.jar">https://piston-data.mojang.com/v1/objects/5b6eb767f6708d351e3d1009a44115bb033b854f/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/2a0b27ad8bd6cd2bb09e3a2210170fd0b5424c54/client.jar">https://piston-data.mojang.com/v1/objects/2a0b27ad8bd6cd2bb09e3a2210170fd0b5424c54/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w48b">18w48b</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/blocks/sweet_berry_bush.json
+  minecraft/loot_tables/chests/village/village_armorer.json
+  minecraft/loot_tables/chests/village/village_butcher.json
+  minecraft/loot_tables/chests/village/village_mason.json
+  minecraft/loot_tables/chests/village/village_shepherd.json
+  minecraft/structures/village/savanna
+  minecraft/structures/village/savanna/houses
+  minecraft/structures/village/savanna/houses/savanna_animal_pen_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_animal_pen_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_animal_pen_3.nbt
+  minecraft/structures/village/savanna/houses/savanna_armorer_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_butchers_shop_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_butchers_shop_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_cartographer_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_fisher_cottage_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_fletcher_house_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_large_farm_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_large_farm_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_library_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_mason_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_medium_house_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_medium_house_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_shepherd_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_farm.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_3.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_4.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_5.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_6.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_7.nbt
+  minecraft/structures/village/savanna/houses/savanna_small_house_8.nbt
+  minecraft/structures/village/savanna/houses/savanna_tannery_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_temple_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_temple_2.nbt
+  minecraft/structures/village/savanna/houses/savanna_tool_smith_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_weaponsmith_1.nbt
+  minecraft/structures/village/savanna/houses/savanna_weaponsmith_2.nbt
+  minecraft/structures/village/savanna/streets
+  minecraft/structures/village/savanna/streets/corner_01.nbt
+  minecraft/structures/village/savanna/streets/corner_03.nbt
+  minecraft/structures/village/savanna/streets/crossroad_02.nbt
+  minecraft/structures/village/savanna/streets/crossroad_03.nbt
+  minecraft/structures/village/savanna/streets/crossroad_04.nbt
+  minecraft/structures/village/savanna/streets/crossroad_05.nbt
+  minecraft/structures/village/savanna/streets/crossroad_06.nbt
+  minecraft/structures/village/savanna/streets/crossroad_07.nbt
+  minecraft/structures/village/savanna/streets/split_01.nbt
+  minecraft/structures/village/savanna/streets/split_02.nbt
+  minecraft/structures/village/savanna/streets/straight_02.nbt
+  minecraft/structures/village/savanna/streets/straight_04.nbt
+  minecraft/structures/village/savanna/streets/straight_05.nbt
+  minecraft/structures/village/savanna/streets/straight_06.nbt
+  minecraft/structures/village/savanna/streets/straight_08.nbt
+  minecraft/structures/village/savanna/streets/straight_09.nbt
+  minecraft/structures/village/savanna/streets/straight_10.nbt
+  minecraft/structures/village/savanna/streets/straight_11.nbt
+  minecraft/structures/village/savanna/streets/turn_01.nbt
+  minecraft/structures/village/savanna/terminators
+  minecraft/structures/village/savanna/terminators/terminator_05.nbt
+  minecraft/structures/village/savanna/town_centers
+  minecraft/structures/village/savanna/town_centers/savanna_meeting_point_1.nbt
+  minecraft/structures/village/savanna/town_centers/savanna_meeting_point_2.nbt
+  minecraft/structures/village/savanna/town_centers/savanna_meeting_point_3.nbt
+  minecraft/structures/village/savanna/town_centers/savanna_meeting_point_4.nbt
+  minecraft/structures/village/savanna/savanna_lamp_post_01.nbt
+  minecraft/structures/village/snowy
+  minecraft/structures/village/snowy/houses
+  minecraft/structures/village/snowy/houses/snowy_animal_pen_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_animal_pen_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_armorer_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_armorer_house_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_butchers_shop.nbt
+  minecraft/structures/village/snowy/houses/snowy_butchers_shop_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_butchers_shop_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_cartographer_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_farm_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_farm_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_fisher_cottage.nbt
+  minecraft/structures/village/snowy/houses/snowy_fletcher_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_library_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_masons_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_masons_house_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_medium_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_medium_house_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_medium_house_3.nbt
+  minecraft/structures/village/snowy/houses/snowy_shepherds_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_2.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_3.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_4.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_5.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_6.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_7.nbt
+  minecraft/structures/village/snowy/houses/snowy_small_house_8.nbt
+  minecraft/structures/village/snowy/houses/snowy_tannery_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_temple_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_tool_smith_1.nbt
+  minecraft/structures/village/snowy/houses/snowy_weapon_smith_1.nbt
+  minecraft/structures/village/snowy/streets
+  minecraft/structures/village/snowy/streets/corner_01.nbt
+  minecraft/structures/village/snowy/streets/corner_02.nbt
+  minecraft/structures/village/snowy/streets/corner_03.nbt
+  minecraft/structures/village/snowy/streets/crossroad_01.nbt
+  minecraft/structures/village/snowy/streets/crossroad_02.nbt
+  minecraft/structures/village/snowy/streets/crossroad_03.nbt
+  minecraft/structures/village/snowy/streets/crossroad_04.nbt
+  minecraft/structures/village/snowy/streets/crossroad_05.nbt
+  minecraft/structures/village/snowy/streets/crossroad_06.nbt
+  minecraft/structures/village/snowy/streets/square_01.nbt
+  minecraft/structures/village/snowy/streets/straight_01.nbt
+  minecraft/structures/village/snowy/streets/straight_02.nbt
+  minecraft/structures/village/snowy/streets/straight_03.nbt
+  minecraft/structures/village/snowy/streets/straight_04.nbt
+  minecraft/structures/village/snowy/streets/straight_06.nbt
+  minecraft/structures/village/snowy/streets/straight_08.nbt
+  minecraft/structures/village/snowy/streets/turn_01.nbt
+  minecraft/structures/village/snowy/town_centers
+  minecraft/structures/village/snowy/town_centers/snowy_meeting_point_1.nbt
+  minecraft/structures/village/snowy/town_centers/snowy_meeting_point_2.nbt
+  minecraft/structures/village/snowy/town_centers/snowy_meeting_point_3.nbt
+  minecraft/structures/village/snowy/snowy_lamp_post_01.nbt
+  minecraft/structures/village/snowy/snowy_lamp_post_02.nbt
+  minecraft/structures/village/snowy/snowy_lamp_post_03.nbt
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/sweet_berry_bush.json
+  minecraft/models/block/sweet_berry_bush_stage0.json
+  minecraft/models/block/sweet_berry_bush_stage1.json
+  minecraft/models/block/sweet_berry_bush_stage2.json
+  minecraft/models/block/sweet_berry_bush_stage3.json
+  minecraft/models/item/sweet_berries.json
+  minecraft/textures/block/sweet_berry_bush_stage0.png
+  minecraft/textures/block/sweet_berry_bush_stage1.png
+  minecraft/textures/block/sweet_berry_bush_stage2.png
+  minecraft/textures/block/sweet_berry_bush_stage3.png
+  minecraft/textures/item/sweet_berries.png
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
+ blocks/sweet_berry_bush.json
+ chests/village/village_armorer.json
+ chests/village/village_butcher.json
+ chests/village/village_mason.json
+ chests/village/village_shepherd.json
```

</details>

<details><summary>structures.txt</summary>

```diff
+ village/savanna/houses/savanna_animal_pen_1.nbt
+ village/savanna/houses/savanna_animal_pen_2.nbt
+ village/savanna/houses/savanna_animal_pen_3.nbt
+ village/savanna/houses/savanna_armorer_1.nbt
+ village/savanna/houses/savanna_butchers_shop_1.nbt
+ village/savanna/houses/savanna_butchers_shop_2.nbt
+ village/savanna/houses/savanna_cartographer_1.nbt
+ village/savanna/houses/savanna_fisher_cottage_1.nbt
+ village/savanna/houses/savanna_fletcher_house_1.nbt
+ village/savanna/houses/savanna_large_farm_1.nbt
+ village/savanna/houses/savanna_large_farm_2.nbt
+ village/savanna/houses/savanna_library_1.nbt
+ village/savanna/houses/savanna_mason_1.nbt
+ village/savanna/houses/savanna_medium_house_1.nbt
+ village/savanna/houses/savanna_medium_house_2.nbt
+ village/savanna/houses/savanna_shepherd_1.nbt
+ village/savanna/houses/savanna_small_farm.nbt
+ village/savanna/houses/savanna_small_house_1.nbt
+ village/savanna/houses/savanna_small_house_2.nbt
+ village/savanna/houses/savanna_small_house_3.nbt
+ village/savanna/houses/savanna_small_house_4.nbt
+ village/savanna/houses/savanna_small_house_5.nbt
+ village/savanna/houses/savanna_small_house_6.nbt
+ village/savanna/houses/savanna_small_house_7.nbt
+ village/savanna/houses/savanna_small_house_8.nbt
+ village/savanna/houses/savanna_tannery_1.nbt
+ village/savanna/houses/savanna_temple_1.nbt
+ village/savanna/houses/savanna_temple_2.nbt
+ village/savanna/houses/savanna_tool_smith_1.nbt
+ village/savanna/houses/savanna_weaponsmith_1.nbt
+ village/savanna/houses/savanna_weaponsmith_2.nbt
+ village/savanna/savanna_lamp_post_01.nbt
+ village/savanna/streets/corner_01.nbt
+ village/savanna/streets/corner_03.nbt
+ village/savanna/streets/crossroad_02.nbt
+ village/savanna/streets/crossroad_03.nbt
+ village/savanna/streets/crossroad_04.nbt
+ village/savanna/streets/crossroad_05.nbt
+ village/savanna/streets/crossroad_06.nbt
+ village/savanna/streets/crossroad_07.nbt
+ village/savanna/streets/split_01.nbt
+ village/savanna/streets/split_02.nbt
+ village/savanna/streets/straight_02.nbt
+ village/savanna/streets/straight_04.nbt
+ village/savanna/streets/straight_05.nbt
+ village/savanna/streets/straight_06.nbt
+ village/savanna/streets/straight_08.nbt
+ village/savanna/streets/straight_09.nbt
+ village/savanna/streets/straight_10.nbt
+ village/savanna/streets/straight_11.nbt
+ village/savanna/streets/turn_01.nbt
+ village/savanna/terminators/terminator_05.nbt
+ village/savanna/town_centers/savanna_meeting_point_1.nbt
+ village/savanna/town_centers/savanna_meeting_point_2.nbt
+ village/savanna/town_centers/savanna_meeting_point_3.nbt
+ village/savanna/town_centers/savanna_meeting_point_4.nbt
+ village/snowy/houses/snowy_animal_pen_1.nbt
+ village/snowy/houses/snowy_animal_pen_2.nbt
+ village/snowy/houses/snowy_armorer_house_1.nbt
+ village/snowy/houses/snowy_armorer_house_2.nbt
+ village/snowy/houses/snowy_butchers_shop.nbt
+ village/snowy/houses/snowy_butchers_shop_1.nbt
+ village/snowy/houses/snowy_butchers_shop_2.nbt
+ village/snowy/houses/snowy_cartographer_house_1.nbt
+ village/snowy/houses/snowy_farm_1.nbt
+ village/snowy/houses/snowy_farm_2.nbt
+ village/snowy/houses/snowy_fisher_cottage.nbt
+ village/snowy/houses/snowy_fletcher_house_1.nbt
+ village/snowy/houses/snowy_library_1.nbt
+ village/snowy/houses/snowy_masons_house_1.nbt
+ village/snowy/houses/snowy_masons_house_2.nbt
+ village/snowy/houses/snowy_medium_house_1.nbt
+ village/snowy/houses/snowy_medium_house_2.nbt
+ village/snowy/houses/snowy_medium_house_3.nbt
+ village/snowy/houses/snowy_shepherds_house_1.nbt
+ village/snowy/houses/snowy_small_house_1.nbt
+ village/snowy/houses/snowy_small_house_2.nbt
+ village/snowy/houses/snowy_small_house_3.nbt
+ village/snowy/houses/snowy_small_house_4.nbt
+ village/snowy/houses/snowy_small_house_5.nbt
+ village/snowy/houses/snowy_small_house_6.nbt
+ village/snowy/houses/snowy_small_house_7.nbt
+ village/snowy/houses/snowy_small_house_8.nbt
+ village/snowy/houses/snowy_tannery_1.nbt
+ village/snowy/houses/snowy_temple_1.nbt
+ village/snowy/houses/snowy_tool_smith_1.nbt
+ village/snowy/houses/snowy_weapon_smith_1.nbt
+ village/snowy/snowy_lamp_post_01.nbt
+ village/snowy/snowy_lamp_post_02.nbt
+ village/snowy/snowy_lamp_post_03.nbt
+ village/snowy/streets/corner_01.nbt
+ village/snowy/streets/corner_02.nbt
+ village/snowy/streets/corner_03.nbt
+ village/snowy/streets/crossroad_01.nbt
+ village/snowy/streets/crossroad_02.nbt
+ village/snowy/streets/crossroad_03.nbt
+ village/snowy/streets/crossroad_04.nbt
+ village/snowy/streets/crossroad_05.nbt
+ village/snowy/streets/crossroad_06.nbt
+ village/snowy/streets/square_01.nbt
+ village/snowy/streets/straight_01.nbt
+ village/snowy/streets/straight_02.nbt
+ village/snowy/streets/straight_03.nbt
+ village/snowy/streets/straight_04.nbt
+ village/snowy/streets/straight_06.nbt
+ village/snowy/streets/straight_08.nbt
+ village/snowy/streets/turn_01.nbt
+ village/snowy/town_centers/snowy_meeting_point_1.nbt
+ village/snowy/town_centers/snowy_meeting_point_2.nbt
+ village/snowy/town_centers/snowy_meeting_point_3.nbt
```

</details>

<details><summary>textures.txt</summary>

```diff
+ block/sweet_berry_bush_stage0.png
+ block/sweet_berry_bush_stage1.png
+ block/sweet_berry_bush_stage2.png
+ block/sweet_berry_bush_stage3.png
+ item/sweet_berries.png
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