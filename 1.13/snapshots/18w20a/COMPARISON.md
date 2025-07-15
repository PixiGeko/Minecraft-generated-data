## Comparison with [18w19b](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w19b)

> [!TIP]
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ kelp_plant.json
- kelp_top.json
+ prismarine_brick_slab.json
+ prismarine_brick_stairs.json
- prismarine_bricks_slab.json
- prismarine_bricks_stairs.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
team
</summary>

```diff
+ team option <team: team> prefix <prefix: component>
+ team option <team: team> suffix <suffix: component>
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
+ prismarine_brick_slab.json
+ prismarine_brick_stairs.json
- prismarine_bricks_slab.json
- prismarine_bricks_stairs.json
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
+ block.minecraft.kelp_plant: Kelp Plant
- block.minecraft.kelp_top: Kelp
+ block.minecraft.prismarine_brick_slab: Prismarine Brick Slab
+ block.minecraft.prismarine_brick_stairs: Prismarine Brick Stairs
- block.minecraft.prismarine_bricks_slab: Prismarine Bricks Slab
- block.minecraft.prismarine_bricks_stairs: Prismarine Bricks Stairs
+ commands.team.option.prefix.success: Team prefix set to %s
+ commands.team.option.suffix.success: Team suffix set to %s
+ entity.minecraft.cod_mob: Cod
+ entity.minecraft.salmon_mob: Salmon
+ entity.minecraft.tropical_fish: Tropical Fish
- item.minecraft.cod_mob_spawn_egg: Spawn Cod
+ item.minecraft.cod_spawn_egg: Cod Spawn Egg
+ item.minecraft.debug_stick.empty: %s has no properties
+ item.minecraft.debug_stick.select: selected "%s" (%s)
+ item.minecraft.debug_stick.update: "%s" to %s
- item.minecraft.salmon_mob_spawn_egg: Spawn Salmon
+ item.minecraft.salmon_spawn_egg: Salmon Spawn Egg
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w19b</th><th>18w20a</th></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.kelp</div></th><td>Kelp Base</td><td>Kelp</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.light_weighted_pressure_plate</div></th><td>Weighted Pressure Plate (Light)</td><td>Light Weighted Pressure Plate</td></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.heavy_weighted_pressure_plate</div></th><td>Weighted Pressure Plate (Heavy)</td><td>Heavy Weighted Pressure Plate</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.wheat_seeds</div></th><td>Seeds</td><td>Wheat Seeds</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.chainmail_helmet</div></th><td>Chain Helmet</td><td>Chainmail Helmet</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.chainmail_chestplate</div></th><td>Chain Chestplate</td><td>Chainmail Chestplate</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.chainmail_leggings</div></th><td>Chain Leggings</td><td>Chainmail Leggings</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.chainmail_boots</div></th><td>Chain Boots</td><td>Chainmail Boots</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.milk_bucket</div></th><td>Milk</td><td>Milk Bucket</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.bat_spawn_egg</div></th><td>Spawn Bat</td><td>Bat Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.blaze_spawn_egg</div></th><td>Spawn Blaze</td><td>Blaze Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.cave_spider_spawn_egg</div></th><td>Spawn Cave Spider</td><td>Cave Spider Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.chicken_spawn_egg</div></th><td>Spawn Chicken</td><td>Chicken Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.cow_spawn_egg</div></th><td>Spawn Cow</td><td>Cow Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.creeper_spawn_egg</div></th><td>Spawn Creeper</td><td>Creeper Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.dolphin_spawn_egg</div></th><td>Spawn Dolphin</td><td>Dolphin Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.donkey_spawn_egg</div></th><td>Spawn Donkey</td><td>Donkey Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.drowned_spawn_egg</div></th><td>Spawn Drowned</td><td>Drowned Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.elder_guardian_spawn_egg</div></th><td>Spawn Elder Guardian</td><td>Elder Guardian Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.enderman_spawn_egg</div></th><td>Spawn Enderman</td><td>Enderman Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.endermite_spawn_egg</div></th><td>Spawn Endermite</td><td>Endermite Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.evocation_illager_spawn_egg</div></th><td>Spawn Evoker</td><td>Evoker Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.ghast_spawn_egg</div></th><td>Spawn Ghast</td><td>Ghast Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.guardian_spawn_egg</div></th><td>Spawn Guardian</td><td>Guardian Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.horse_spawn_egg</div></th><td>Spawn Horse</td><td>Horse Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.husk_spawn_egg</div></th><td>Spawn Husk</td><td>Husk Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.llama_spawn_egg</div></th><td>Spawn Llama</td><td>Llama Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.magma_cube_spawn_egg</div></th><td>Spawn Magma Cube</td><td>Magma Cube Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.mooshroom_spawn_egg</div></th><td>Spawn Mooshroom</td><td>Mooshroom Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.mule_spawn_egg</div></th><td>Spawn Mule</td><td>Mule Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.ocelot_spawn_egg</div></th><td>Spawn Ocelot</td><td>Ocelot Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.parrot_spawn_egg</div></th><td>Spawn Parrot</td><td>Parrot Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.pig_spawn_egg</div></th><td>Spawn Pig</td><td>Pig Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.phantom_spawn_egg</div></th><td>Spawn Phantom</td><td>Phantom Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.polar_bear_spawn_egg</div></th><td>Spawn Polar Bear</td><td>Polar Bear Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.pufferfish_spawn_egg</div></th><td>Spawn Pufferfish</td><td>Pufferfish Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.rabbit_spawn_egg</div></th><td>Spawn Rabbit</td><td>Rabbit Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.sheep_spawn_egg</div></th><td>Spawn Sheep</td><td>Sheep Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.shulker_spawn_egg</div></th><td>Spawn Shulker</td><td>Shulker Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.silverfish_spawn_egg</div></th><td>Spawn Silverfish</td><td>Silverfish Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.skeleton_spawn_egg</div></th><td>Spawn Skeleton</td><td>Skeleton Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.skeleton_horse_spawn_egg</div></th><td>Spawn Skeleton Horse</td><td>Skeleton Horse Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.slime_spawn_egg</div></th><td>Spawn Slime</td><td>Slime Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.spider_spawn_egg</div></th><td>Spawn Spider</td><td>Spider Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.squid_spawn_egg</div></th><td>Spawn Squid</td><td>Squid Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.stray_spawn_egg</div></th><td>Spawn Stray</td><td>Stray Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.tropical_fish_spawn_egg</div></th><td>Spawn Tropical Fish</td><td>Tropical Fish Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.turtle_spawn_egg</div></th><td>Spawn Turtle</td><td>Turtle Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.vex_spawn_egg</div></th><td>Spawn Vex</td><td>Vex Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.villager_spawn_egg</div></th><td>Spawn Villager</td><td>Villager Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.vindication_illager_spawn_egg</div></th><td>Spawn Vindicator</td><td>Vindicator Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.witch_spawn_egg</div></th><td>Spawn Witch</td><td>Witch Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.wither_skeleton_spawn_egg</div></th><td>Spawn Wither Skeleton</td><td>Wither Skeleton Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.wolf_spawn_egg</div></th><td>Spawn Wolf</td><td>Wolf Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.zombie_spawn_egg</div></th><td>Spawn Zombie</td><td>Zombie Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.zombie_horse_spawn_egg</div></th><td>Spawn Zombie Horse</td><td>Zombie Horse Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.zombie_pigman_spawn_egg</div></th><td>Spawn Zombie Pigman</td><td>Zombie Pigman Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.zombie_villager_spawn_egg</div></th><td>Spawn Zombie Villager</td><td>Zombie Villager Spawn Egg</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.golden_horse_armor</div></th><td>Gold Horse Armor</td><td>Golden Horse Armor</td></tr>
<tr><th align="left"><div style="width:290px">entity.minecraft.lightning_bolt</div></th><td>Bolt of Lightning</td><td>Lightning Bolt</td></tr>
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
+ minecraft/advancements/recipes/building_blocks/prismarine_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/prismarine_brick_stairs.json
- minecraft/advancements/recipes/building_blocks/prismarine_bricks_slab.json
- minecraft/advancements/recipes/building_blocks/prismarine_bricks_stairs.json
- minecraft/loot_tables/entities/cod_mob.json
+ minecraft/loot_tables/entities/cod.json
- minecraft/loot_tables/entities/salmon_mob.json
+ minecraft/loot_tables/entities/salmon.json
+ minecraft/recipes/prismarine_brick_slab.json
+ minecraft/recipes/prismarine_brick_stairs.json
- minecraft/recipes/prismarine_bricks_slab.json
- minecraft/recipes/prismarine_bricks_stairs.json
+ minecraft/structures/end_city/base_floor.nbt
+ minecraft/structures/end_city/base_roof.nbt
+ minecraft/structures/end_city/bridge_end.nbt
+ minecraft/structures/end_city/bridge_gentle_stairs.nbt
+ minecraft/structures/end_city/bridge_piece.nbt
+ minecraft/structures/end_city/bridge_steep_stairs.nbt
+ minecraft/structures/end_city/fat_tower_base.nbt
+ minecraft/structures/end_city/fat_tower_middle.nbt
+ minecraft/structures/end_city/fat_tower_top.nbt
+ minecraft/structures/end_city/second_floor_1.nbt
+ minecraft/structures/end_city/second_floor_2.nbt
+ minecraft/structures/end_city/second_roof.nbt
+ minecraft/structures/end_city/ship.nbt
+ minecraft/structures/end_city/third_floor_1.nbt
+ minecraft/structures/end_city/third_floor_2.nbt
+ minecraft/structures/end_city/third_roof.nbt
+ minecraft/structures/end_city/tower_base.nbt
+ minecraft/structures/end_city/tower_floor.nbt
+ minecraft/structures/end_city/tower_piece.nbt
+ minecraft/structures/end_city/tower_top.nbt
- minecraft/structures/endcity/base_floor.nbt
- minecraft/structures/endcity/base_roof.nbt
- minecraft/structures/endcity/bridge_end.nbt
- minecraft/structures/endcity/bridge_gentle_stairs.nbt
- minecraft/structures/endcity/bridge_piece.nbt
- minecraft/structures/endcity/bridge_steep_stairs.nbt
- minecraft/structures/endcity/fat_tower_base.nbt
- minecraft/structures/endcity/fat_tower_middle.nbt
- minecraft/structures/endcity/fat_tower_top.nbt
- minecraft/structures/endcity/second_floor_2.nbt
- minecraft/structures/endcity/second_floor.nbt
- minecraft/structures/endcity/second_roof.nbt
- minecraft/structures/endcity/ship.nbt
- minecraft/structures/endcity/third_floor_b.nbt
- minecraft/structures/endcity/third_floor_c.nbt
- minecraft/structures/endcity/third_floor.nbt
- minecraft/structures/endcity/third_roof.nbt
- minecraft/structures/endcity/tower_base.nbt
- minecraft/structures/endcity/tower_floor.nbt
- minecraft/structures/endcity/tower_piece.nbt
- minecraft/structures/endcity/tower_top.nbt
+ minecraft/structures/fossil/skull_1_coal.nbt
+ minecraft/structures/fossil/skull_1.nbt
+ minecraft/structures/fossil/skull_2_coal.nbt
+ minecraft/structures/fossil/skull_2.nbt
+ minecraft/structures/fossil/skull_3_coal.nbt
+ minecraft/structures/fossil/skull_3.nbt
+ minecraft/structures/fossil/skull_4_coal.nbt
+ minecraft/structures/fossil/skull_4.nbt
+ minecraft/structures/fossil/spine_1_coal.nbt
+ minecraft/structures/fossil/spine_1.nbt
+ minecraft/structures/fossil/spine_2_coal.nbt
+ minecraft/structures/fossil/spine_2.nbt
+ minecraft/structures/fossil/spine_3_coal.nbt
+ minecraft/structures/fossil/spine_3.nbt
+ minecraft/structures/fossil/spine_4_coal.nbt
+ minecraft/structures/fossil/spine_4.nbt
- minecraft/structures/fossils/fossil_skull_01_coal.nbt
- minecraft/structures/fossils/fossil_skull_01.nbt
- minecraft/structures/fossils/fossil_skull_02_coal.nbt
- minecraft/structures/fossils/fossil_skull_02.nbt
- minecraft/structures/fossils/fossil_skull_03_coal.nbt
- minecraft/structures/fossils/fossil_skull_03.nbt
- minecraft/structures/fossils/fossil_skull_04_coal.nbt
- minecraft/structures/fossils/fossil_skull_04.nbt
- minecraft/structures/fossils/fossil_spine_01_coal.nbt
- minecraft/structures/fossils/fossil_spine_01.nbt
- minecraft/structures/fossils/fossil_spine_02_coal.nbt
- minecraft/structures/fossils/fossil_spine_02.nbt
- minecraft/structures/fossils/fossil_spine_03_coal.nbt
- minecraft/structures/fossils/fossil_spine_03.nbt
- minecraft/structures/fossils/fossil_spine_04_coal.nbt
- minecraft/structures/fossils/fossil_spine_04.nbt
+ minecraft/structures/igloo/bottom.nbt
- minecraft/structures/igloo/igloo_bottom.nbt
- minecraft/structures/igloo/igloo_middle.nbt
- minecraft/structures/igloo/igloo_top.nbt
+ minecraft/structures/igloo/middle.nbt
+ minecraft/structures/igloo/top.nbt
- minecraft/structures/mansion/1x1_a1.nbt
- minecraft/structures/mansion/1x1_a2.nbt
- minecraft/structures/mansion/1x1_a3.nbt
- minecraft/structures/mansion/1x1_a4.nbt
- minecraft/structures/mansion/1x1_a5.nbt
- minecraft/structures/mansion/1x1_as1.nbt
- minecraft/structures/mansion/1x1_as2.nbt
- minecraft/structures/mansion/1x1_as3.nbt
- minecraft/structures/mansion/1x1_as4.nbt
- minecraft/structures/mansion/1x1_b1.nbt
- minecraft/structures/mansion/1x1_b2.nbt
- minecraft/structures/mansion/1x1_b3.nbt
- minecraft/structures/mansion/1x1_b4.nbt
- minecraft/structures/mansion/1x1_b5.nbt
- minecraft/structures/mansion/1x2_a1.nbt
- minecraft/structures/mansion/1x2_a2.nbt
- minecraft/structures/mansion/1x2_a3.nbt
- minecraft/structures/mansion/1x2_a4.nbt
- minecraft/structures/mansion/1x2_a5.nbt
- minecraft/structures/mansion/1x2_a6.nbt
- minecraft/structures/mansion/1x2_a7.nbt
- minecraft/structures/mansion/1x2_a8.nbt
- minecraft/structures/mansion/1x2_a9.nbt
- minecraft/structures/mansion/1x2_b1.nbt
- minecraft/structures/mansion/1x2_b2.nbt
- minecraft/structures/mansion/1x2_b3.nbt
- minecraft/structures/mansion/1x2_b4.nbt
- minecraft/structures/mansion/1x2_b5.nbt
- minecraft/structures/mansion/1x2_c_stairs.nbt
- minecraft/structures/mansion/1x2_c1.nbt
- minecraft/structures/mansion/1x2_c2.nbt
- minecraft/structures/mansion/1x2_c3.nbt
- minecraft/structures/mansion/1x2_c4.nbt
- minecraft/structures/mansion/1x2_d_stairs.nbt
- minecraft/structures/mansion/1x2_d1.nbt
- minecraft/structures/mansion/1x2_d2.nbt
- minecraft/structures/mansion/1x2_d3.nbt
- minecraft/structures/mansion/1x2_d4.nbt
- minecraft/structures/mansion/1x2_d5.nbt
- minecraft/structures/mansion/1x2_s1.nbt
- minecraft/structures/mansion/1x2_s2.nbt
- minecraft/structures/mansion/1x2_se1.nbt
- minecraft/structures/mansion/2x2_a1.nbt
- minecraft/structures/mansion/2x2_a2.nbt
- minecraft/structures/mansion/2x2_a3.nbt
- minecraft/structures/mansion/2x2_a4.nbt
- minecraft/structures/mansion/2x2_b1.nbt
- minecraft/structures/mansion/2x2_b2.nbt
- minecraft/structures/mansion/2x2_b3.nbt
- minecraft/structures/mansion/2x2_b4.nbt
- minecraft/structures/mansion/2x2_b5.nbt
- minecraft/structures/mansion/2x2_s1.nbt
- minecraft/structures/mansion/carpet_east.nbt
- minecraft/structures/mansion/carpet_north.nbt
- minecraft/structures/mansion/carpet_south_2.nbt
- minecraft/structures/mansion/carpet_south.nbt
- minecraft/structures/mansion/carpet_west_2.nbt
- minecraft/structures/mansion/carpet_west.nbt
- minecraft/structures/mansion/corridor_floor.nbt
- minecraft/structures/mansion/entrance.nbt
- minecraft/structures/mansion/indoors_door_2.nbt
- minecraft/structures/mansion/indoors_door.nbt
- minecraft/structures/mansion/indoors_wall_2.nbt
- minecraft/structures/mansion/indoors_wall.nbt
- minecraft/structures/mansion/roof_corner.nbt
- minecraft/structures/mansion/roof_front.nbt
- minecraft/structures/mansion/roof_inner_corner.nbt
- minecraft/structures/mansion/roof.nbt
- minecraft/structures/mansion/small_wall_corner.nbt
- minecraft/structures/mansion/small_wall.nbt
- minecraft/structures/mansion/wall_corner.nbt
- minecraft/structures/mansion/wall_flat.nbt
- minecraft/structures/mansion/wall_window.nbt
- minecraft/structures/ruin/big_ruin_warm4.nbt
- minecraft/structures/ruin/big_ruin_warm5.nbt
- minecraft/structures/ruin/big_ruin_warm6.nbt
- minecraft/structures/ruin/big_ruin_warm7.nbt
- minecraft/structures/ruin/big_ruin1_brick.nbt
- minecraft/structures/ruin/big_ruin1_cracked.nbt
- minecraft/structures/ruin/big_ruin1_mossy.nbt
- minecraft/structures/ruin/big_ruin2_brick.nbt
- minecraft/structures/ruin/big_ruin2_cracked.nbt
- minecraft/structures/ruin/big_ruin2_mossy.nbt
- minecraft/structures/ruin/big_ruin3_brick.nbt
- minecraft/structures/ruin/big_ruin3_cracked.nbt
- minecraft/structures/ruin/big_ruin3_mossy.nbt
- minecraft/structures/ruin/big_ruin8_brick.nbt
- minecraft/structures/ruin/big_ruin8_cracked.nbt
- minecraft/structures/ruin/big_ruin8_mossy.nbt
- minecraft/structures/ruin/ruin_warm1.nbt
- minecraft/structures/ruin/ruin_warm2.nbt
- minecraft/structures/ruin/ruin_warm3.nbt
- minecraft/structures/ruin/ruin_warm4.nbt
- minecraft/structures/ruin/ruin_warm5.nbt
- minecraft/structures/ruin/ruin_warm6.nbt
- minecraft/structures/ruin/ruin_warm7.nbt
- minecraft/structures/ruin/ruin_warm8.nbt
- minecraft/structures/ruin/ruin1_brick.nbt
- minecraft/structures/ruin/ruin1_cracked.nbt
- minecraft/structures/ruin/ruin1_mossy.nbt
- minecraft/structures/ruin/ruin2_brick.nbt
- minecraft/structures/ruin/ruin2_cracked.nbt
- minecraft/structures/ruin/ruin2_mossy.nbt
- minecraft/structures/ruin/ruin3_brick.nbt
- minecraft/structures/ruin/ruin3_cracked.nbt
- minecraft/structures/ruin/ruin3_mossy.nbt
- minecraft/structures/ruin/ruin4_brick.nbt
- minecraft/structures/ruin/ruin4_cracked.nbt
- minecraft/structures/ruin/ruin4_mossy.nbt
- minecraft/structures/ruin/ruin5_brick.nbt
- minecraft/structures/ruin/ruin5_cracked.nbt
- minecraft/structures/ruin/ruin5_mossy.nbt
- minecraft/structures/ruin/ruin6_brick.nbt
- minecraft/structures/ruin/ruin6_cracked.nbt
- minecraft/structures/ruin/ruin6_mossy.nbt
- minecraft/structures/ruin/ruin7_brick.nbt
- minecraft/structures/ruin/ruin7_cracked.nbt
- minecraft/structures/ruin/ruin7_mossy.nbt
- minecraft/structures/ruin/ruin8_brick.nbt
- minecraft/structures/ruin/ruin8_cracked.nbt
- minecraft/structures/ruin/ruin8_mossy.nbt
+ minecraft/structures/underwater_ruin/big_brick_1.nbt
+ minecraft/structures/underwater_ruin/big_brick_2.nbt
+ minecraft/structures/underwater_ruin/big_brick_3.nbt
+ minecraft/structures/underwater_ruin/big_brick_8.nbt
+ minecraft/structures/underwater_ruin/big_cracked_1.nbt
+ minecraft/structures/underwater_ruin/big_cracked_2.nbt
+ minecraft/structures/underwater_ruin/big_cracked_3.nbt
+ minecraft/structures/underwater_ruin/big_cracked_8.nbt
+ minecraft/structures/underwater_ruin/big_mossy_1.nbt
+ minecraft/structures/underwater_ruin/big_mossy_2.nbt
+ minecraft/structures/underwater_ruin/big_mossy_3.nbt
+ minecraft/structures/underwater_ruin/big_mossy_8.nbt
+ minecraft/structures/underwater_ruin/big_warm_4.nbt
+ minecraft/structures/underwater_ruin/big_warm_5.nbt
+ minecraft/structures/underwater_ruin/big_warm_6.nbt
+ minecraft/structures/underwater_ruin/big_warm_7.nbt
+ minecraft/structures/underwater_ruin/brick_1.nbt
+ minecraft/structures/underwater_ruin/brick_2.nbt
+ minecraft/structures/underwater_ruin/brick_3.nbt
+ minecraft/structures/underwater_ruin/brick_4.nbt
+ minecraft/structures/underwater_ruin/brick_5.nbt
+ minecraft/structures/underwater_ruin/brick_6.nbt
+ minecraft/structures/underwater_ruin/brick_7.nbt
+ minecraft/structures/underwater_ruin/brick_8.nbt
+ minecraft/structures/underwater_ruin/cracked_1.nbt
+ minecraft/structures/underwater_ruin/cracked_2.nbt
+ minecraft/structures/underwater_ruin/cracked_3.nbt
+ minecraft/structures/underwater_ruin/cracked_4.nbt
+ minecraft/structures/underwater_ruin/cracked_5.nbt
+ minecraft/structures/underwater_ruin/cracked_6.nbt
+ minecraft/structures/underwater_ruin/cracked_7.nbt
+ minecraft/structures/underwater_ruin/cracked_8.nbt
+ minecraft/structures/underwater_ruin/mossy_1.nbt
+ minecraft/structures/underwater_ruin/mossy_2.nbt
+ minecraft/structures/underwater_ruin/mossy_3.nbt
+ minecraft/structures/underwater_ruin/mossy_4.nbt
+ minecraft/structures/underwater_ruin/mossy_5.nbt
+ minecraft/structures/underwater_ruin/mossy_6.nbt
+ minecraft/structures/underwater_ruin/mossy_7.nbt
+ minecraft/structures/underwater_ruin/mossy_8.nbt
+ minecraft/structures/underwater_ruin/warm_1.nbt
+ minecraft/structures/underwater_ruin/warm_2.nbt
+ minecraft/structures/underwater_ruin/warm_3.nbt
+ minecraft/structures/underwater_ruin/warm_4.nbt
+ minecraft/structures/underwater_ruin/warm_5.nbt
+ minecraft/structures/underwater_ruin/warm_6.nbt
+ minecraft/structures/underwater_ruin/warm_7.nbt
+ minecraft/structures/underwater_ruin/warm_8.nbt
+ minecraft/structures/woodland_mansion/1x1_a1.nbt
+ minecraft/structures/woodland_mansion/1x1_a2.nbt
+ minecraft/structures/woodland_mansion/1x1_a3.nbt
+ minecraft/structures/woodland_mansion/1x1_a4.nbt
+ minecraft/structures/woodland_mansion/1x1_a5.nbt
+ minecraft/structures/woodland_mansion/1x1_as1.nbt
+ minecraft/structures/woodland_mansion/1x1_as2.nbt
+ minecraft/structures/woodland_mansion/1x1_as3.nbt
+ minecraft/structures/woodland_mansion/1x1_as4.nbt
+ minecraft/structures/woodland_mansion/1x1_b1.nbt
+ minecraft/structures/woodland_mansion/1x1_b2.nbt
+ minecraft/structures/woodland_mansion/1x1_b3.nbt
+ minecraft/structures/woodland_mansion/1x1_b4.nbt
+ minecraft/structures/woodland_mansion/1x1_b5.nbt
+ minecraft/structures/woodland_mansion/1x2_a1.nbt
+ minecraft/structures/woodland_mansion/1x2_a2.nbt
+ minecraft/structures/woodland_mansion/1x2_a3.nbt
+ minecraft/structures/woodland_mansion/1x2_a4.nbt
+ minecraft/structures/woodland_mansion/1x2_a5.nbt
+ minecraft/structures/woodland_mansion/1x2_a6.nbt
+ minecraft/structures/woodland_mansion/1x2_a7.nbt
+ minecraft/structures/woodland_mansion/1x2_a8.nbt
+ minecraft/structures/woodland_mansion/1x2_a9.nbt
+ minecraft/structures/woodland_mansion/1x2_b1.nbt
+ minecraft/structures/woodland_mansion/1x2_b2.nbt
+ minecraft/structures/woodland_mansion/1x2_b3.nbt
+ minecraft/structures/woodland_mansion/1x2_b4.nbt
+ minecraft/structures/woodland_mansion/1x2_b5.nbt
+ minecraft/structures/woodland_mansion/1x2_c_stairs.nbt
+ minecraft/structures/woodland_mansion/1x2_c1.nbt
+ minecraft/structures/woodland_mansion/1x2_c2.nbt
+ minecraft/structures/woodland_mansion/1x2_c3.nbt
+ minecraft/structures/woodland_mansion/1x2_c4.nbt
+ minecraft/structures/woodland_mansion/1x2_d_stairs.nbt
+ minecraft/structures/woodland_mansion/1x2_d1.nbt
+ minecraft/structures/woodland_mansion/1x2_d2.nbt
+ minecraft/structures/woodland_mansion/1x2_d3.nbt
+ minecraft/structures/woodland_mansion/1x2_d4.nbt
+ minecraft/structures/woodland_mansion/1x2_d5.nbt
+ minecraft/structures/woodland_mansion/1x2_s1.nbt
+ minecraft/structures/woodland_mansion/1x2_s2.nbt
+ minecraft/structures/woodland_mansion/1x2_se1.nbt
+ minecraft/structures/woodland_mansion/2x2_a1.nbt
+ minecraft/structures/woodland_mansion/2x2_a2.nbt
+ minecraft/structures/woodland_mansion/2x2_a3.nbt
+ minecraft/structures/woodland_mansion/2x2_a4.nbt
+ minecraft/structures/woodland_mansion/2x2_b1.nbt
+ minecraft/structures/woodland_mansion/2x2_b2.nbt
+ minecraft/structures/woodland_mansion/2x2_b3.nbt
+ minecraft/structures/woodland_mansion/2x2_b4.nbt
+ minecraft/structures/woodland_mansion/2x2_b5.nbt
+ minecraft/structures/woodland_mansion/2x2_s1.nbt
+ minecraft/structures/woodland_mansion/carpet_east.nbt
+ minecraft/structures/woodland_mansion/carpet_north.nbt
+ minecraft/structures/woodland_mansion/carpet_south_1.nbt
+ minecraft/structures/woodland_mansion/carpet_south_2.nbt
+ minecraft/structures/woodland_mansion/carpet_west_1.nbt
+ minecraft/structures/woodland_mansion/carpet_west_2.nbt
+ minecraft/structures/woodland_mansion/corridor_floor.nbt
+ minecraft/structures/woodland_mansion/entrance.nbt
+ minecraft/structures/woodland_mansion/indoors_door_1.nbt
+ minecraft/structures/woodland_mansion/indoors_door_2.nbt
+ minecraft/structures/woodland_mansion/indoors_wall_1.nbt
+ minecraft/structures/woodland_mansion/indoors_wall_2.nbt
+ minecraft/structures/woodland_mansion/roof_corner.nbt
+ minecraft/structures/woodland_mansion/roof_front.nbt
+ minecraft/structures/woodland_mansion/roof_inner_corner.nbt
+ minecraft/structures/woodland_mansion/roof.nbt
+ minecraft/structures/woodland_mansion/small_wall_corner.nbt
+ minecraft/structures/woodland_mansion/small_wall.nbt
+ minecraft/structures/woodland_mansion/wall_corner.nbt
+ minecraft/structures/woodland_mansion/wall_flat.nbt
+ minecraft/structures/woodland_mansion/wall_window.nbt
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/bubble_column.json
- minecraft/blockstates/conduit.json
+ minecraft/blockstates/kelp_plant.json
- minecraft/blockstates/kelp_top.json
+ minecraft/blockstates/prismarine_brick_slab.json
+ minecraft/blockstates/prismarine_brick_stairs.json
- minecraft/blockstates/prismarine_bricks_slab.json
- minecraft/blockstates/prismarine_bricks_stairs.json
- minecraft/models/block/bubble_column.json
- minecraft/models/block/cobblestone_wall_mossy_inventory.json
- minecraft/models/block/conduit.json
- minecraft/models/block/half_slab_acacia.json
- minecraft/models/block/half_slab_birch.json
- minecraft/models/block/half_slab_brick.json
- minecraft/models/block/half_slab_cobblestone.json
- minecraft/models/block/half_slab_dark_oak.json
- minecraft/models/block/half_slab_dark_prismarine.json
- minecraft/models/block/half_slab_jungle.json
- minecraft/models/block/half_slab_nether_brick.json
- minecraft/models/block/half_slab_oak.json
- minecraft/models/block/half_slab_prismarine_bricks.json
- minecraft/models/block/half_slab_prismarine.json
- minecraft/models/block/half_slab_purpur.json
- minecraft/models/block/half_slab_quartz.json
- minecraft/models/block/half_slab_red_sandstone.json
- minecraft/models/block/half_slab_sandstone.json
- minecraft/models/block/half_slab_spruce.json
- minecraft/models/block/half_slab_stone_brick.json
- minecraft/models/block/half_slab_stone.json
+ minecraft/models/block/kelp_plant.json
- minecraft/models/block/kelp_top.json
+ minecraft/models/block/mossy_cobblestone_wall_inventory.json
- minecraft/models/block/piston_inventory_normal.json
- minecraft/models/block/piston_inventory_sticky.json
+ minecraft/models/block/prismarine_brick_slab_top.json
+ minecraft/models/block/prismarine_brick_slab.json
+ minecraft/models/block/prismarine_brick_stairs_inner.json
+ minecraft/models/block/prismarine_brick_stairs_outer.json
+ minecraft/models/block/prismarine_brick_stairs.json
- minecraft/models/block/prismarine_bricks_slab_top.json
- minecraft/models/block/prismarine_bricks_slab.json
- minecraft/models/block/prismarine_bricks_stairs_inner.json
- minecraft/models/block/prismarine_bricks_stairs_outer.json
- minecraft/models/block/prismarine_bricks_stairs.json
+ minecraft/models/block/redstone_dust_dot.json
+ minecraft/models/block/redstone_dust_side_alt.json
+ minecraft/models/block/redstone_dust_side_alt0.json
+ minecraft/models/block/redstone_dust_side_alt1.json
+ minecraft/models/block/redstone_dust_side.json
+ minecraft/models/block/redstone_dust_side0.json
+ minecraft/models/block/redstone_dust_side1.json
+ minecraft/models/block/redstone_dust_up.json
- minecraft/models/block/redstone_lamp_off.json
+ minecraft/models/block/redstone_lamp_on.json
- minecraft/models/block/redstone_wire_dot.json
- minecraft/models/block/redstone_wire_side_alt.json
- minecraft/models/block/redstone_wire_side_alt0.json
- minecraft/models/block/redstone_wire_side_alt1.json
- minecraft/models/block/redstone_wire_side.json
- minecraft/models/block/redstone_wire_side0.json
- minecraft/models/block/redstone_wire_side1.json
- minecraft/models/block/redstone_wire_up.json
+ minecraft/models/block/sticky_piston_inventory.json
- minecraft/models/item/cod_mob_spawn_egg.json
+ minecraft/models/item/cod_spawn_egg.json
- minecraft/models/item/kelp_top.json
+ minecraft/models/item/kelp.json
+ minecraft/models/item/prismarine_brick_slab.json
+ minecraft/models/item/prismarine_brick_stairs.json
- minecraft/models/item/prismarine_bricks_slab.json
- minecraft/models/item/prismarine_bricks_stairs.json
- minecraft/models/item/salmon_mob_spawn_egg.json
+ minecraft/models/item/salmon_spawn_egg.json
- minecraft/models/item/spawn_egg.json
+ minecraft/models/item/template_spawn_egg.json
+ minecraft/models/piston_inventory.json
+ minecraft/textures/blocks/acacia_door_bottom.png
- minecraft/textures/blocks/acacia_door_lower.png
+ minecraft/textures/blocks/acacia_door_top.png
- minecraft/textures/blocks/acacia_door_upper.png
+ minecraft/textures/blocks/birch_door_bottom.png
- minecraft/textures/blocks/birch_door_lower.png
+ minecraft/textures/blocks/birch_door_top.png
- minecraft/textures/blocks/birch_door_upper.png
+ minecraft/textures/blocks/black_shulker_box_top.png
+ minecraft/textures/blocks/blue_shulker_box_top.png
- minecraft/textures/blocks/brick.png
+ minecraft/textures/blocks/bricks.png
+ minecraft/textures/blocks/brown_shulker_box_top.png
+ minecraft/textures/blocks/carved_pumpkin.png
+ minecraft/textures/blocks/cyan_shulker_box_top.png
+ minecraft/textures/blocks/dark_oak_door_bottom.png
- minecraft/textures/blocks/dark_oak_door_lower.png
+ minecraft/textures/blocks/dark_oak_door_top.png
- minecraft/textures/blocks/dark_oak_door_upper.png
- minecraft/textures/blocks/dried_kelp_side_mirror.png
+ minecraft/textures/blocks/farmland_moist.png
- minecraft/textures/blocks/farmland_wet.png
+ minecraft/textures/blocks/fire_0.png
+ minecraft/textures/blocks/fire_0.png.mcmeta
+ minecraft/textures/blocks/fire_1.png
+ minecraft/textures/blocks/fire_1.png.mcmeta
- minecraft/textures/blocks/fire_layer_0.png
- minecraft/textures/blocks/fire_layer_0.png.mcmeta
- minecraft/textures/blocks/fire_layer_1.png
- minecraft/textures/blocks/fire_layer_1.png.mcmeta
+ minecraft/textures/blocks/granite.png
+ minecraft/textures/blocks/gray_shulker_box_top.png
+ minecraft/textures/blocks/green_shulker_box_top.png
+ minecraft/textures/blocks/iron_door_bottom.png
- minecraft/textures/blocks/iron_door_lower.png
+ minecraft/textures/blocks/iron_door_top.png
- minecraft/textures/blocks/iron_door_upper.png
+ minecraft/textures/blocks/item_frame.png
- minecraft/textures/blocks/itemframe_background.png
+ minecraft/textures/blocks/jack_o_lantern.png
+ minecraft/textures/blocks/jungle_door_bottom.png
- minecraft/textures/blocks/jungle_door_lower.png
+ minecraft/textures/blocks/jungle_door_top.png
- minecraft/textures/blocks/jungle_door_upper.png
- minecraft/textures/blocks/kelp_top.png
- minecraft/textures/blocks/kelp_top.png.mcmeta
+ minecraft/textures/blocks/kelp.png
+ minecraft/textures/blocks/kelp.png.mcmeta
+ minecraft/textures/blocks/light_blue_shulker_box_top.png
+ minecraft/textures/blocks/light_gray_shulker_box_top.png
+ minecraft/textures/blocks/lime_shulker_box_top.png
+ minecraft/textures/blocks/magenta_shulker_box_top.png
- minecraft/textures/blocks/nether_brick.png
+ minecraft/textures/blocks/nether_bricks.png
+ minecraft/textures/blocks/nether_quartz_ore.png
+ minecraft/textures/blocks/oak_door_bottom.png
- minecraft/textures/blocks/oak_door_lower.png
+ minecraft/textures/blocks/oak_door_top.png
- minecraft/textures/blocks/oak_door_upper.png
+ minecraft/textures/blocks/orange_shulker_box_top.png
+ minecraft/textures/blocks/pink_shulker_box_top.png
- minecraft/textures/blocks/pumpkin_face_on.png
- minecraft/textures/blocks/pumpkin_face.png
+ minecraft/textures/blocks/purple_shulker_box_top.png
- minecraft/textures/blocks/quartz_ore.png
- minecraft/textures/blocks/red_nether_brick.png
+ minecraft/textures/blocks/red_nether_bricks.png
+ minecraft/textures/blocks/red_shulker_box_top.png
- minecraft/textures/blocks/redstone_lamp_off.png
+ minecraft/textures/blocks/redstone_lamp.png
+ minecraft/textures/blocks/shulker_box_top.png
- minecraft/textures/blocks/shulker_top_black.png
- minecraft/textures/blocks/shulker_top_blue.png
- minecraft/textures/blocks/shulker_top_brown.png
- minecraft/textures/blocks/shulker_top_cyan.png
- minecraft/textures/blocks/shulker_top_gray.png
- minecraft/textures/blocks/shulker_top_green.png
- minecraft/textures/blocks/shulker_top_light_blue.png
- minecraft/textures/blocks/shulker_top_light_gray.png
- minecraft/textures/blocks/shulker_top_lime.png
- minecraft/textures/blocks/shulker_top_magenta.png
- minecraft/textures/blocks/shulker_top_orange.png
- minecraft/textures/blocks/shulker_top_pink.png
- minecraft/textures/blocks/shulker_top_purple.png
- minecraft/textures/blocks/shulker_top_red.png
- minecraft/textures/blocks/shulker_top_white.png
- minecraft/textures/blocks/shulker_top_yellow.png
- minecraft/textures/blocks/shulker_top.png
+ minecraft/textures/blocks/spruce_door_bottom.png
- minecraft/textures/blocks/spruce_door_lower.png
+ minecraft/textures/blocks/spruce_door_top.png
- minecraft/textures/blocks/spruce_door_upper.png
- minecraft/textures/blocks/stone_granite.png
- minecraft/textures/blocks/trip_wire_hook.png
- minecraft/textures/blocks/trip_wire.png
+ minecraft/textures/blocks/tripwire_hook.png
+ minecraft/textures/blocks/tripwire.png
- minecraft/textures/blocks/turtle_egg_not_cracked.png
+ minecraft/textures/blocks/turtle_egg.png
+ minecraft/textures/blocks/white_shulker_box_top.png
+ minecraft/textures/blocks/yellow_shulker_box_top.png
+ minecraft/textures/entity/boat/acacia.png
+ minecraft/textures/entity/boat/birch.png
- minecraft/textures/entity/boat/boat_acacia.png
- minecraft/textures/entity/boat/boat_birch.png
- minecraft/textures/entity/boat/boat_darkoak.png
- minecraft/textures/entity/boat/boat_jungle.png
- minecraft/textures/entity/boat/boat_oak.png
- minecraft/textures/entity/boat/boat_spruce.png
+ minecraft/textures/entity/boat/dark_oak.png
+ minecraft/textures/entity/boat/jungle.png
+ minecraft/textures/entity/boat/oak.png
+ minecraft/textures/entity/boat/spruce.png
- minecraft/textures/entity/fish/cod_mob.png
+ minecraft/textures/entity/fish/cod.png
- minecraft/textures/entity/fish/salmon_mob.png
+ minecraft/textures/entity/fish/salmon.png
+ minecraft/textures/entity/llama/brown.png
+ minecraft/textures/entity/llama/creamy.png
+ minecraft/textures/entity/llama/decor/black.png
+ minecraft/textures/entity/llama/decor/blue.png
+ minecraft/textures/entity/llama/decor/brown.png
+ minecraft/textures/entity/llama/decor/cyan.png
- minecraft/textures/entity/llama/decor/decor_black.png
- minecraft/textures/entity/llama/decor/decor_blue.png
- minecraft/textures/entity/llama/decor/decor_brown.png
- minecraft/textures/entity/llama/decor/decor_cyan.png
- minecraft/textures/entity/llama/decor/decor_gray.png
- minecraft/textures/entity/llama/decor/decor_green.png
- minecraft/textures/entity/llama/decor/decor_light_blue.png
- minecraft/textures/entity/llama/decor/decor_light_gray.png
- minecraft/textures/entity/llama/decor/decor_lime.png
- minecraft/textures/entity/llama/decor/decor_magenta.png
- minecraft/textures/entity/llama/decor/decor_orange.png
- minecraft/textures/entity/llama/decor/decor_pink.png
- minecraft/textures/entity/llama/decor/decor_purple.png
- minecraft/textures/entity/llama/decor/decor_red.png
- minecraft/textures/entity/llama/decor/decor_white.png
- minecraft/textures/entity/llama/decor/decor_yellow.png
+ minecraft/textures/entity/llama/decor/gray.png
+ minecraft/textures/entity/llama/decor/green.png
+ minecraft/textures/entity/llama/decor/light_blue.png
+ minecraft/textures/entity/llama/decor/light_gray.png
+ minecraft/textures/entity/llama/decor/lime.png
+ minecraft/textures/entity/llama/decor/magenta.png
+ minecraft/textures/entity/llama/decor/orange.png
+ minecraft/textures/entity/llama/decor/pink.png
+ minecraft/textures/entity/llama/decor/purple.png
+ minecraft/textures/entity/llama/decor/red.png
+ minecraft/textures/entity/llama/decor/white.png
+ minecraft/textures/entity/llama/decor/yellow.png
+ minecraft/textures/entity/llama/gray.png
- minecraft/textures/entity/llama/llama_brown.png
- minecraft/textures/entity/llama/llama_creamy.png
- minecraft/textures/entity/llama/llama_gray.png
- minecraft/textures/entity/llama/llama_white.png
- minecraft/textures/entity/llama/llama.png
+ minecraft/textures/entity/llama/white.png
+ minecraft/textures/items/filled_map_markings.png
+ minecraft/textures/items/filled_map.png
- minecraft/textures/items/fish_pufferfish_raw.png
- minecraft/textures/items/map_filled_markings.png
- minecraft/textures/items/map_filled.png
```

</details>
</details>
<hr/>