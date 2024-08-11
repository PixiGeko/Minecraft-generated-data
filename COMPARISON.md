## Comparison with [19w06a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w06a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w06a</th><th>19w07a</th></tr><tr><td>World version</td><td><code>1931</code></td><td><code>1932</code></td></tr><tr><td>Protocol version</td><td><code>459</code></td><td><code>460</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:fox
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:fox_spawn_egg
```

</details>








<details>
<summary>
sound_event.txt
</summary>

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
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:fox
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:cat_morning_gift
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:fox
```

</details>












<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:fox
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:fox_spawn_egg
```

</details>








<details>
<summary>
universal_tags/sound_event.json
</summary>

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
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ entity.minecraft.fox: Fox
+ gui.narrate.button: %s button
+ gui.narrate.slider: %s slider
+ item.minecraft.fox_spawn_egg: Fox Spawn Egg
+ subtitles.entity.fox.aggro: Fox angers
+ subtitles.entity.fox.ambient: Fox squeaks
+ subtitles.entity.fox.bark: Fox barks
+ subtitles.entity.fox.bite: Fox bites
+ subtitles.entity.fox.death: Fox dies
+ subtitles.entity.fox.eat: Fox eats
+ subtitles.entity.fox.hurt: Fox hurts
+ subtitles.entity.fox.sleep: Fox snores
+ subtitles.entity.fox.sniff: Fox sniffs
+ subtitles.entity.fox.spit: Fox spits
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/chests/village/village_fisher.json
- minecraft/loot_tables/entities/cat_morning_gift.json
+ minecraft/loot_tables/entities/fox.json
+ minecraft/loot_tables/gameplay/cat_morning_gift.json
- minecraft/structures/village/desert/houses/desert_sheperd_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_animal_pen_3.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_big_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_butcher_shop_2.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_fletcher_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_medium_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_medium_house_2.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_meeting_point_4.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_meeting_point_5.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_shepherds_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_1.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_2.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_3.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_4.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_5.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_6.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_7.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_small_house_8.nbt
+ minecraft/structures/village/plains/zombie/houses/plains_stable_1.nbt
+ minecraft/structures/village/plains/zombie/streets/corner_01.nbt
+ minecraft/structures/village/plains/zombie/streets/corner_02.nbt
+ minecraft/structures/village/plains/zombie/streets/corner_03.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_01.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_02.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_03.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_04.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_05.nbt
+ minecraft/structures/village/plains/zombie/streets/crossroad_06.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_01.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_02.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_03.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_04.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_05.nbt
+ minecraft/structures/village/plains/zombie/streets/straight_06.nbt
+ minecraft/structures/village/plains/zombie/streets/turn_01.nbt
+ minecraft/structures/village/plains/zombie/town_centers/plains_fountain_01.nbt
+ minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_1.nbt
+ minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_2.nbt
+ minecraft/structures/village/plains/zombie/town_centers/plains_meeting_point_3.nbt
+ minecraft/structures/village/plains/zombie/villagers/armorer.nbt
+ minecraft/structures/village/plains/zombie/villagers/butcher.nbt
+ minecraft/structures/village/plains/zombie/villagers/cartographer.nbt
+ minecraft/structures/village/plains/zombie/villagers/cleric.nbt
+ minecraft/structures/village/plains/zombie/villagers/farmer.nbt
+ minecraft/structures/village/plains/zombie/villagers/fishermen.nbt
+ minecraft/structures/village/plains/zombie/villagers/fletcher.nbt
+ minecraft/structures/village/plains/zombie/villagers/leatherworker.nbt
+ minecraft/structures/village/plains/zombie/villagers/librarian.nbt
+ minecraft/structures/village/plains/zombie/villagers/nitwit.nbt
+ minecraft/structures/village/plains/zombie/villagers/shepherd.nbt
+ minecraft/structures/village/plains/zombie/villagers/toolsmith.nbt
+ minecraft/structures/village/plains/zombie/villagers/unemployed.nbt
+ minecraft/structures/village/plains/zombie/villagers/weaponsmith.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_animal_pen_2.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_animal_pen_3.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_large_farm_2.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_medium_house_1.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_medium_house_2.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_1.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_2.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_3.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_4.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_5.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_6.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_7.nbt
+ minecraft/structures/village/savanna/zombie/houses/savanna_small_house_8.nbt
+ minecraft/structures/village/savanna/zombie/streets/corner_01.nbt
+ minecraft/structures/village/savanna/zombie/streets/corner_03.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_02.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_03.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_04.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_05.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_06.nbt
+ minecraft/structures/village/savanna/zombie/streets/crossroad_07.nbt
+ minecraft/structures/village/savanna/zombie/streets/split_01.nbt
+ minecraft/structures/village/savanna/zombie/streets/split_02.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_02.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_04.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_05.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_06.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_08.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_09.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_10.nbt
+ minecraft/structures/village/savanna/zombie/streets/straight_11.nbt
+ minecraft/structures/village/savanna/zombie/streets/turn_01.nbt
+ minecraft/structures/village/savanna/zombie/terminators/terminator_05.nbt
+ minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_1.nbt
+ minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_2.nbt
+ minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_3.nbt
+ minecraft/structures/village/savanna/zombie/town_centers/savanna_meeting_point_4.nbt
+ minecraft/structures/village/savanna/zombie/villagers/armorer.nbt
+ minecraft/structures/village/savanna/zombie/villagers/butcher.nbt
+ minecraft/structures/village/savanna/zombie/villagers/cartographer.nbt
+ minecraft/structures/village/savanna/zombie/villagers/cleric.nbt
+ minecraft/structures/village/savanna/zombie/villagers/farmer.nbt
+ minecraft/structures/village/savanna/zombie/villagers/fishermen.nbt
+ minecraft/structures/village/savanna/zombie/villagers/fletcher.nbt
+ minecraft/structures/village/savanna/zombie/villagers/leatherworker.nbt
+ minecraft/structures/village/savanna/zombie/villagers/librarian.nbt
+ minecraft/structures/village/savanna/zombie/villagers/nitwit.nbt
+ minecraft/structures/village/savanna/zombie/villagers/shepherd.nbt
+ minecraft/structures/village/savanna/zombie/villagers/toolsmith.nbt
+ minecraft/structures/village/savanna/zombie/villagers/unemployed.nbt
+ minecraft/structures/village/savanna/zombie/villagers/weaponsmith.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_1.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_2.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_medium_house_3.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_1.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_2.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_3.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_4.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_5.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_6.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_7.nbt
+ minecraft/structures/village/snowy/zombie/houses/snowy_small_house_8.nbt
+ minecraft/structures/village/snowy/zombie/streets/corner_01.nbt
+ minecraft/structures/village/snowy/zombie/streets/corner_02.nbt
+ minecraft/structures/village/snowy/zombie/streets/corner_03.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_01.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_02.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_03.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_04.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_05.nbt
+ minecraft/structures/village/snowy/zombie/streets/crossroad_06.nbt
+ minecraft/structures/village/snowy/zombie/streets/square_01.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_01.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_02.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_03.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_04.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_06.nbt
+ minecraft/structures/village/snowy/zombie/streets/straight_08.nbt
+ minecraft/structures/village/snowy/zombie/streets/turn_01.nbt
+ minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_1.nbt
+ minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_2.nbt
+ minecraft/structures/village/snowy/zombie/town_centers/snowy_meeting_point_3.nbt
+ minecraft/structures/village/snowy/zombie/villagers/armorer.nbt
+ minecraft/structures/village/snowy/zombie/villagers/butcher.nbt
+ minecraft/structures/village/snowy/zombie/villagers/cartographer.nbt
+ minecraft/structures/village/snowy/zombie/villagers/cleric.nbt
+ minecraft/structures/village/snowy/zombie/villagers/farmer.nbt
+ minecraft/structures/village/snowy/zombie/villagers/fishermen.nbt
+ minecraft/structures/village/snowy/zombie/villagers/fletcher.nbt
+ minecraft/structures/village/snowy/zombie/villagers/leatherworker.nbt
+ minecraft/structures/village/snowy/zombie/villagers/librarian.nbt
+ minecraft/structures/village/snowy/zombie/villagers/nitwit.nbt
+ minecraft/structures/village/snowy/zombie/villagers/shepherd.nbt
+ minecraft/structures/village/snowy/zombie/villagers/toolsmith.nbt
+ minecraft/structures/village/snowy/zombie/villagers/unemployed.nbt
+ minecraft/structures/village/snowy/zombie/villagers/weaponsmith.nbt
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/block/barrel_open.json
+ minecraft/models/item/fox_spawn_egg.json
+ minecraft/textures/block/barrel_top_open.png
+ minecraft/textures/entity/fox/fox_sleep.png
+ minecraft/textures/entity/fox/fox.png
+ minecraft/textures/entity/fox/snow_fox_sleep.png
+ minecraft/textures/entity/fox/snow_fox.png
+ minecraft/textures/painting/alban.png
+ minecraft/textures/painting/aztec.png
+ minecraft/textures/painting/aztec2.png
+ minecraft/textures/painting/back.png
+ minecraft/textures/painting/bomb.png
+ minecraft/textures/painting/burning_skull.png
+ minecraft/textures/painting/bust.png
+ minecraft/textures/painting/courbet.png
+ minecraft/textures/painting/creebet.png
+ minecraft/textures/painting/donkey_kong.png
+ minecraft/textures/painting/fighters.png
+ minecraft/textures/painting/graham.png
+ minecraft/textures/painting/kebab.png
+ minecraft/textures/painting/match.png
- minecraft/textures/painting/paintings_kristoffer_zetterstrand.png
+ minecraft/textures/painting/pigscene.png
+ minecraft/textures/painting/plant.png
+ minecraft/textures/painting/pointer.png
+ minecraft/textures/painting/pool.png
+ minecraft/textures/painting/sea.png
+ minecraft/textures/painting/skeleton.png
+ minecraft/textures/painting/skull_and_roses.png
+ minecraft/textures/painting/stage.png
+ minecraft/textures/painting/sunset.png
+ minecraft/textures/painting/void.png
+ minecraft/textures/painting/wanderer.png
+ minecraft/textures/painting/wasteland.png
+ minecraft/textures/painting/wither.png
```

</details>
</details>