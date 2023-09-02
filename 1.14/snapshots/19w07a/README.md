<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w07a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w07a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-02-13T16:12:08+00:00</td></tr>
<tr><th>SHA1</th><td>0be11f1e510a44d0042ad471a72371e7633c9777</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/0be11f1e510a44d0042ad471a72371e7633c9777/19w07a.json">https://piston-meta.mojang.com/v1/packages/0be11f1e510a44d0042ad471a72371e7633c9777/19w07a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/d370db01d591576477c3efc940a42926f43bc98f/server.jar">https://piston-data.mojang.com/v1/objects/d370db01d591576477c3efc940a42926f43bc98f/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/656fcedd90336e82678d260e4fa20df958926474/client.jar">https://piston-data.mojang.com/v1/objects/656fcedd90336e82678d260e4fa20df958926474/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w06a">19w06a</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/loot_tables/chests/village/village_fisher.json
-  minecraft/loot_tables/entities/cat_morning_gift.json
+  minecraft/loot_tables/entities/fox.json
+  minecraft/loot_tables/gameplay/cat_morning_gift.json
-  minecraft/structures/village/desert/houses/desert_sheperd_house_1.nbt
+  minecraft/structures/village/plains/zombie
+  minecraft/structures/village/plains/zombie/houses
+  minecraft/structures/village/plains/zombie/houses/plains_animal_pen_3.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_big_house_1.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_butcher_shop_2.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_fletcher_house_1.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_medium_house_1.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_medium_house_2.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_meeting_point_4.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_meeting_point_5.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_shepherds_house_1.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_1.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_2.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_3.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_4.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_5.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_6.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_7.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_small_house_8.nbt
+  minecraft/structures/village/plains/zombie/houses/plains_stable_1.nbt
+  minecraft/structures/village/plains/zombie/streets
+  minecraft/structures/village/plains/zombie/streets/corner_01.nbt
+  minecraft/structures/village/plains/zombie/streets/corner_02.nbt
+  minecraft/structures/village/plains/zombie/streets/corner_03.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_01.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_02.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_03.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_04.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_05.nbt
+  minecraft/structures/village/plains/zombie/streets/crossroad_06.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_01.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_02.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_03.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_04.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_05.nbt
+  minecraft/structures/village/plains/zombie/streets/straight_06.nbt
+  minecraft/structures/village/plains/zombie/streets/turn_01.nbt
+  minecraft/structures/village/plains/zombie/town_centers
+  minecraft/structures/village/plains/zombie/town_centers/plains_fountain_01.nbt
+  minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_1.nbt
+  minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_2.nbt
+  minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_3.nbt
+  minecraft/structures/village/plains/zombie/villagers
+  minecraft/structures/village/plains/zombie/villagers/armorer.nbt
+  minecraft/structures/village/plains/zombie/villagers/butcher.nbt
+  minecraft/structures/village/plains/zombie/villagers/cartographer.nbt
+  minecraft/structures/village/plains/zombie/villagers/cleric.nbt
+  minecraft/structures/village/plains/zombie/villagers/farmer.nbt
+  minecraft/structures/village/plains/zombie/villagers/fishermen.nbt
+  minecraft/structures/village/plains/zombie/villagers/fletcher.nbt
+  minecraft/structures/village/plains/zombie/villagers/leatherworker.nbt
+  minecraft/structures/village/plains/zombie/villagers/librarian.nbt
+  minecraft/structures/village/plains/zombie/villagers/nitwit.nbt
+  minecraft/structures/village/plains/zombie/villagers/shepherd.nbt
+  minecraft/structures/village/plains/zombie/villagers/toolsmith.nbt
+  minecraft/structures/village/plains/zombie/villagers/unemployed.nbt
+  minecraft/structures/village/plains/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/savanna/zombie
+  minecraft/structures/village/savanna/zombie/houses
+  minecraft/structures/village/savanna/zombie/houses/savanna_animal_pen_2.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_animal_pen_3.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_large_farm_2.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_medium_house_1.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_medium_house_2.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_1.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_2.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_3.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_4.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_5.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_6.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_7.nbt
+  minecraft/structures/village/savanna/zombie/houses/savanna_small_house_8.nbt
+  minecraft/structures/village/savanna/zombie/streets
+  minecraft/structures/village/savanna/zombie/streets/corner_01.nbt
+  minecraft/structures/village/savanna/zombie/streets/corner_03.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_02.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_03.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_04.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_05.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_06.nbt
+  minecraft/structures/village/savanna/zombie/streets/crossroad_07.nbt
+  minecraft/structures/village/savanna/zombie/streets/split_01.nbt
+  minecraft/structures/village/savanna/zombie/streets/split_02.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_02.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_04.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_05.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_06.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_08.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_09.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_10.nbt
+  minecraft/structures/village/savanna/zombie/streets/straight_11.nbt
+  minecraft/structures/village/savanna/zombie/streets/turn_01.nbt
+  minecraft/structures/village/savanna/zombie/terminators
+  minecraft/structures/village/savanna/zombie/terminators/terminator_05.nbt
+  minecraft/structures/village/savanna/zombie/town_centers
+  minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_1.nbt
+  minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_2.nbt
+  minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_3.nbt
+  minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_4.nbt
+  minecraft/structures/village/savanna/zombie/villagers
+  minecraft/structures/village/savanna/zombie/villagers/armorer.nbt
+  minecraft/structures/village/savanna/zombie/villagers/butcher.nbt
+  minecraft/structures/village/savanna/zombie/villagers/cartographer.nbt
+  minecraft/structures/village/savanna/zombie/villagers/cleric.nbt
+  minecraft/structures/village/savanna/zombie/villagers/farmer.nbt
+  minecraft/structures/village/savanna/zombie/villagers/fishermen.nbt
+  minecraft/structures/village/savanna/zombie/villagers/fletcher.nbt
+  minecraft/structures/village/savanna/zombie/villagers/leatherworker.nbt
+  minecraft/structures/village/savanna/zombie/villagers/librarian.nbt
+  minecraft/structures/village/savanna/zombie/villagers/nitwit.nbt
+  minecraft/structures/village/savanna/zombie/villagers/shepherd.nbt
+  minecraft/structures/village/savanna/zombie/villagers/toolsmith.nbt
+  minecraft/structures/village/savanna/zombie/villagers/unemployed.nbt
+  minecraft/structures/village/savanna/zombie/villagers/weaponsmith.nbt
+  minecraft/structures/village/snowy/zombie
+  minecraft/structures/village/snowy/zombie/houses
+  minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_1.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_2.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_3.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_1.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_2.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_3.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_4.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_5.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_6.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_7.nbt
+  minecraft/structures/village/snowy/zombie/houses/snowy_small_house_8.nbt
+  minecraft/structures/village/snowy/zombie/streets
+  minecraft/structures/village/snowy/zombie/streets/corner_01.nbt
+  minecraft/structures/village/snowy/zombie/streets/corner_02.nbt
+  minecraft/structures/village/snowy/zombie/streets/corner_03.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_01.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_02.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_03.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_04.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_05.nbt
+  minecraft/structures/village/snowy/zombie/streets/crossroad_06.nbt
+  minecraft/structures/village/snowy/zombie/streets/square_01.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_01.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_02.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_03.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_04.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_06.nbt
+  minecraft/structures/village/snowy/zombie/streets/straight_08.nbt
+  minecraft/structures/village/snowy/zombie/streets/turn_01.nbt
+  minecraft/structures/village/snowy/zombie/town_centers
+  minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_1.nbt
+  minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_2.nbt
+  minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_3.nbt
+  minecraft/structures/village/snowy/zombie/villagers
+  minecraft/structures/village/snowy/zombie/villagers/armorer.nbt
+  minecraft/structures/village/snowy/zombie/villagers/butcher.nbt
+  minecraft/structures/village/snowy/zombie/villagers/cartographer.nbt
+  minecraft/structures/village/snowy/zombie/villagers/cleric.nbt
+  minecraft/structures/village/snowy/zombie/villagers/farmer.nbt
+  minecraft/structures/village/snowy/zombie/villagers/fishermen.nbt
+  minecraft/structures/village/snowy/zombie/villagers/fletcher.nbt
+  minecraft/structures/village/snowy/zombie/villagers/leatherworker.nbt
+  minecraft/structures/village/snowy/zombie/villagers/librarian.nbt
+  minecraft/structures/village/snowy/zombie/villagers/nitwit.nbt
+  minecraft/structures/village/snowy/zombie/villagers/shepherd.nbt
+  minecraft/structures/village/snowy/zombie/villagers/toolsmith.nbt
+  minecraft/structures/village/snowy/zombie/villagers/unemployed.nbt
+  minecraft/structures/village/snowy/zombie/villagers/weaponsmith.nbt
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/models/block/barrel_open.json
+  minecraft/models/item/fox_spawn_egg.json
+  minecraft/textures/block/barrel_top_open.png
+  minecraft/textures/entity/fox
+  minecraft/textures/entity/fox/fox.png
+  minecraft/textures/entity/fox/fox_sleep.png
+  minecraft/textures/entity/fox/snow_fox.png
+  minecraft/textures/entity/fox/snow_fox_sleep.png
+  minecraft/textures/painting/alban.png
+  minecraft/textures/painting/aztec.png
+  minecraft/textures/painting/aztec2.png
+  minecraft/textures/painting/back.png
+  minecraft/textures/painting/bomb.png
+  minecraft/textures/painting/burning_skull.png
+  minecraft/textures/painting/bust.png
+  minecraft/textures/painting/courbet.png
+  minecraft/textures/painting/creebet.png
+  minecraft/textures/painting/donkey_kong.png
+  minecraft/textures/painting/fighters.png
+  minecraft/textures/painting/graham.png
+  minecraft/textures/painting/kebab.png
+  minecraft/textures/painting/match.png
-  minecraft/textures/painting/paintings_kristoffer_zetterstrand.png
+  minecraft/textures/painting/pigscene.png
+  minecraft/textures/painting/plant.png
+  minecraft/textures/painting/pointer.png
+  minecraft/textures/painting/pool.png
+  minecraft/textures/painting/sea.png
+  minecraft/textures/painting/skeleton.png
+  minecraft/textures/painting/skull_and_roses.png
+  minecraft/textures/painting/stage.png
+  minecraft/textures/painting/sunset.png
+  minecraft/textures/painting/void.png
+  minecraft/textures/painting/wanderer.png
+  minecraft/textures/painting/wasteland.png
+  minecraft/textures/painting/wither.png
```

</details>

## Registries

<details><summary>entity_type.txt</summary>

```diff
+ minecraft:fox
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:fox_spawn_egg
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:entity.fox.aggro
+ minecraft:entity.fox.ambient
+ minecraft:entity.fox.bark
+ minecraft:entity.fox.bite
+ minecraft:entity.fox.death
+ minecraft:entity.fox.eat
+ minecraft:entity.fox.hurt
+ minecraft:entity.fox.sleep
+ minecraft:entity.fox.sniff
+ minecraft:entity.fox.spit
```

</details>

## Misc

<details><summary>loot_tables.txt</summary>

```diff
- entities/cat_morning_gift.json
+ chests/village/village_fisher.json
+ entities/fox.json
+ gameplay/cat_morning_gift.json
```

</details>

<details><summary>structures.txt</summary>

```diff
- village/desert/houses/desert_sheperd_house_1.nbt
+ village/plains/zombie/houses/plains_animal_pen_3.nbt
+ village/plains/zombie/houses/plains_big_house_1.nbt
+ village/plains/zombie/houses/plains_butcher_shop_2.nbt
+ village/plains/zombie/houses/plains_fletcher_house_1.nbt
+ village/plains/zombie/houses/plains_medium_house_1.nbt
+ village/plains/zombie/houses/plains_medium_house_2.nbt
+ village/plains/zombie/houses/plains_meeting_point_4.nbt
+ village/plains/zombie/houses/plains_meeting_point_5.nbt
+ village/plains/zombie/houses/plains_shepherds_house_1.nbt
+ village/plains/zombie/houses/plains_small_house_1.nbt
+ village/plains/zombie/houses/plains_small_house_2.nbt
+ village/plains/zombie/houses/plains_small_house_3.nbt
+ village/plains/zombie/houses/plains_small_house_4.nbt
+ village/plains/zombie/houses/plains_small_house_5.nbt
+ village/plains/zombie/houses/plains_small_house_6.nbt
+ village/plains/zombie/houses/plains_small_house_7.nbt
+ village/plains/zombie/houses/plains_small_house_8.nbt
+ village/plains/zombie/houses/plains_stable_1.nbt
+ village/plains/zombie/streets/corner_01.nbt
+ village/plains/zombie/streets/corner_02.nbt
+ village/plains/zombie/streets/corner_03.nbt
+ village/plains/zombie/streets/crossroad_01.nbt
+ village/plains/zombie/streets/crossroad_02.nbt
+ village/plains/zombie/streets/crossroad_03.nbt
+ village/plains/zombie/streets/crossroad_04.nbt
+ village/plains/zombie/streets/crossroad_05.nbt
+ village/plains/zombie/streets/crossroad_06.nbt
+ village/plains/zombie/streets/straight_01.nbt
+ village/plains/zombie/streets/straight_02.nbt
+ village/plains/zombie/streets/straight_03.nbt
+ village/plains/zombie/streets/straight_04.nbt
+ village/plains/zombie/streets/straight_05.nbt
+ village/plains/zombie/streets/straight_06.nbt
+ village/plains/zombie/streets/turn_01.nbt
+ village/plains/zombie/town_centers/plains_fountain_01.nbt
+ village/plains/zombie/town_centers/plains_meeting_point_1.nbt
+ village/plains/zombie/town_centers/plains_meeting_point_2.nbt
+ village/plains/zombie/town_centers/plains_meeting_point_3.nbt
+ village/plains/zombie/villagers/armorer.nbt
+ village/plains/zombie/villagers/butcher.nbt
+ village/plains/zombie/villagers/cartographer.nbt
+ village/plains/zombie/villagers/cleric.nbt
+ village/plains/zombie/villagers/farmer.nbt
+ village/plains/zombie/villagers/fishermen.nbt
+ village/plains/zombie/villagers/fletcher.nbt
+ village/plains/zombie/villagers/leatherworker.nbt
+ village/plains/zombie/villagers/librarian.nbt
+ village/plains/zombie/villagers/nitwit.nbt
+ village/plains/zombie/villagers/shepherd.nbt
+ village/plains/zombie/villagers/toolsmith.nbt
+ village/plains/zombie/villagers/unemployed.nbt
+ village/plains/zombie/villagers/weaponsmith.nbt
+ village/savanna/zombie/houses/savanna_animal_pen_2.nbt
+ village/savanna/zombie/houses/savanna_animal_pen_3.nbt
+ village/savanna/zombie/houses/savanna_large_farm_2.nbt
+ village/savanna/zombie/houses/savanna_medium_house_1.nbt
+ village/savanna/zombie/houses/savanna_medium_house_2.nbt
+ village/savanna/zombie/houses/savanna_small_house_1.nbt
+ village/savanna/zombie/houses/savanna_small_house_2.nbt
+ village/savanna/zombie/houses/savanna_small_house_3.nbt
+ village/savanna/zombie/houses/savanna_small_house_4.nbt
+ village/savanna/zombie/houses/savanna_small_house_5.nbt
+ village/savanna/zombie/houses/savanna_small_house_6.nbt
+ village/savanna/zombie/houses/savanna_small_house_7.nbt
+ village/savanna/zombie/houses/savanna_small_house_8.nbt
+ village/savanna/zombie/streets/corner_01.nbt
+ village/savanna/zombie/streets/corner_03.nbt
+ village/savanna/zombie/streets/crossroad_02.nbt
+ village/savanna/zombie/streets/crossroad_03.nbt
+ village/savanna/zombie/streets/crossroad_04.nbt
+ village/savanna/zombie/streets/crossroad_05.nbt
+ village/savanna/zombie/streets/crossroad_06.nbt
+ village/savanna/zombie/streets/crossroad_07.nbt
+ village/savanna/zombie/streets/split_01.nbt
+ village/savanna/zombie/streets/split_02.nbt
+ village/savanna/zombie/streets/straight_02.nbt
+ village/savanna/zombie/streets/straight_04.nbt
+ village/savanna/zombie/streets/straight_05.nbt
+ village/savanna/zombie/streets/straight_06.nbt
+ village/savanna/zombie/streets/straight_08.nbt
+ village/savanna/zombie/streets/straight_09.nbt
+ village/savanna/zombie/streets/straight_10.nbt
+ village/savanna/zombie/streets/straight_11.nbt
+ village/savanna/zombie/streets/turn_01.nbt
+ village/savanna/zombie/terminators/terminator_05.nbt
+ village/savanna/zombie/town_centers/savanna_meeting_point_1.nbt
+ village/savanna/zombie/town_centers/savanna_meeting_point_2.nbt
+ village/savanna/zombie/town_centers/savanna_meeting_point_3.nbt
+ village/savanna/zombie/town_centers/savanna_meeting_point_4.nbt
+ village/savanna/zombie/villagers/armorer.nbt
+ village/savanna/zombie/villagers/butcher.nbt
+ village/savanna/zombie/villagers/cartographer.nbt
+ village/savanna/zombie/villagers/cleric.nbt
+ village/savanna/zombie/villagers/farmer.nbt
+ village/savanna/zombie/villagers/fishermen.nbt
+ village/savanna/zombie/villagers/fletcher.nbt
+ village/savanna/zombie/villagers/leatherworker.nbt
+ village/savanna/zombie/villagers/librarian.nbt
+ village/savanna/zombie/villagers/nitwit.nbt
+ village/savanna/zombie/villagers/shepherd.nbt
+ village/savanna/zombie/villagers/toolsmith.nbt
+ village/savanna/zombie/villagers/unemployed.nbt
+ village/savanna/zombie/villagers/weaponsmith.nbt
+ village/snowy/zombie/houses/snowy_medium_house_1.nbt
+ village/snowy/zombie/houses/snowy_medium_house_2.nbt
+ village/snowy/zombie/houses/snowy_medium_house_3.nbt
+ village/snowy/zombie/houses/snowy_small_house_1.nbt
+ village/snowy/zombie/houses/snowy_small_house_2.nbt
+ village/snowy/zombie/houses/snowy_small_house_3.nbt
+ village/snowy/zombie/houses/snowy_small_house_4.nbt
+ village/snowy/zombie/houses/snowy_small_house_5.nbt
+ village/snowy/zombie/houses/snowy_small_house_6.nbt
+ village/snowy/zombie/houses/snowy_small_house_7.nbt
+ village/snowy/zombie/houses/snowy_small_house_8.nbt
+ village/snowy/zombie/streets/corner_01.nbt
+ village/snowy/zombie/streets/corner_02.nbt
+ village/snowy/zombie/streets/corner_03.nbt
+ village/snowy/zombie/streets/crossroad_01.nbt
+ village/snowy/zombie/streets/crossroad_02.nbt
+ village/snowy/zombie/streets/crossroad_03.nbt
+ village/snowy/zombie/streets/crossroad_04.nbt
+ village/snowy/zombie/streets/crossroad_05.nbt
+ village/snowy/zombie/streets/crossroad_06.nbt
+ village/snowy/zombie/streets/square_01.nbt
+ village/snowy/zombie/streets/straight_01.nbt
+ village/snowy/zombie/streets/straight_02.nbt
+ village/snowy/zombie/streets/straight_03.nbt
+ village/snowy/zombie/streets/straight_04.nbt
+ village/snowy/zombie/streets/straight_06.nbt
+ village/snowy/zombie/streets/straight_08.nbt
+ village/snowy/zombie/streets/turn_01.nbt
+ village/snowy/zombie/town_centers/snowy_meeting_point_1.nbt
+ village/snowy/zombie/town_centers/snowy_meeting_point_2.nbt
+ village/snowy/zombie/town_centers/snowy_meeting_point_3.nbt
+ village/snowy/zombie/villagers/armorer.nbt
+ village/snowy/zombie/villagers/butcher.nbt
+ village/snowy/zombie/villagers/cartographer.nbt
+ village/snowy/zombie/villagers/cleric.nbt
+ village/snowy/zombie/villagers/farmer.nbt
+ village/snowy/zombie/villagers/fishermen.nbt
+ village/snowy/zombie/villagers/fletcher.nbt
+ village/snowy/zombie/villagers/leatherworker.nbt
+ village/snowy/zombie/villagers/librarian.nbt
+ village/snowy/zombie/villagers/nitwit.nbt
+ village/snowy/zombie/villagers/shepherd.nbt
+ village/snowy/zombie/villagers/toolsmith.nbt
+ village/snowy/zombie/villagers/unemployed.nbt
+ village/snowy/zombie/villagers/weaponsmith.nbt
```

</details>

<details><summary>textures.txt</summary>

```diff
- painting/paintings_kristoffer_zetterstrand.png
+ block/barrel_top_open.png
+ entity/fox/fox.png
+ entity/fox/fox_sleep.png
+ entity/fox/snow_fox.png
+ entity/fox/snow_fox_sleep.png
+ painting/alban.png
+ painting/aztec.png
+ painting/aztec2.png
+ painting/back.png
+ painting/bomb.png
+ painting/burning_skull.png
+ painting/bust.png
+ painting/courbet.png
+ painting/creebet.png
+ painting/donkey_kong.png
+ painting/fighters.png
+ painting/graham.png
+ painting/kebab.png
+ painting/match.png
+ painting/pigscene.png
+ painting/plant.png
+ painting/pointer.png
+ painting/pool.png
+ painting/sea.png
+ painting/skeleton.png
+ painting/skull_and_roses.png
+ painting/stage.png
+ painting/sunset.png
+ painting/void.png
+ painting/wanderer.png
+ painting/wasteland.png
+ painting/wither.png
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