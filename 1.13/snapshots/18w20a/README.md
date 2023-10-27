<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w20a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w20a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-05-15T14:02:25+00:00</td></tr>
<tr><th>SHA1</th><td>a287a82f4f84e9529f8d387f3f23c680d262cf6a</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/a287a82f4f84e9529f8d387f3f23c680d262cf6a/18w20a.json">https://piston-meta.mojang.com/v1/packages/a287a82f4f84e9529f8d387f3f23c680d262cf6a/18w20a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/108a051216637e0145f6b0e66182b48736595fc3/server.jar">https://piston-data.mojang.com/v1/objects/108a051216637e0145f6b0e66182b48736595fc3/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/89843d397a9b0fd42bea26ada6890ebc693ad288/client.jar">https://piston-data.mojang.com/v1/objects/89843d397a9b0fd42bea26ada6890ebc693ad288/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w19b">18w19b</a>

# Folder structure

<details><summary>data/</summary>

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


<details><summary>assets/</summary>

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


# Commands

<details><summary>team.txt</summary>

```diff
+ team option <team: team> prefix <prefix: component>
+ team option <team: team> suffix <suffix: component>
```

</details>


# Tags

<details><summary>blocks/slabs.json</summary>

```diff
+ minecraft:prismarine_brick_slab
- minecraft:prismarine_bricks_slab
```

</details>


<details><summary>blocks/stairs.json</summary>

```diff
+ minecraft:prismarine_brick_stairs
- minecraft:prismarine_bricks_stairs
```

</details>


<details><summary>items/slabs.json</summary>

```diff
+ minecraft:prismarine_brick_slab
- minecraft:prismarine_bricks_slab
```

</details>


<details><summary>items/stairs.json</summary>

```diff
+ minecraft:prismarine_brick_stairs
- minecraft:prismarine_bricks_stairs
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ block.minecraft.kelp_plant
- block.minecraft.kelp_top
+ block.minecraft.prismarine_brick_slab
+ block.minecraft.prismarine_brick_stairs
- block.minecraft.prismarine_bricks_slab
- block.minecraft.prismarine_bricks_stairs
+ commands.team.option.prefix.success
+ commands.team.option.suffix.success
+ entity.minecraft.cod_mob
+ entity.minecraft.salmon_mob
+ entity.minecraft.tropical_fish
- item.minecraft.cod_mob_spawn_egg
+ item.minecraft.cod_spawn_egg
+ item.minecraft.debug_stick.empty
+ item.minecraft.debug_stick.select
+ item.minecraft.debug_stick.update
- item.minecraft.salmon_mob_spawn_egg
+ item.minecraft.salmon_spawn_egg
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/building_blocks/prismarine_brick_slab.json
+ recipes/building_blocks/prismarine_brick_stairs.json
- recipes/building_blocks/prismarine_bricks_slab.json
- recipes/building_blocks/prismarine_bricks_stairs.json
```

</details>


<details><summary>loot_tables.txt</summary>

```diff
- entities/cod_mob.json
+ entities/cod.json
- entities/salmon_mob.json
+ entities/salmon.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
+ prismarine_brick_slab.json
+ prismarine_brick_stairs.json
- prismarine_bricks_slab.json
- prismarine_bricks_stairs.json
```

</details>


<details><summary>structures.txt</summary>

```diff
+ end_city/base_floor.nbt
+ end_city/base_roof.nbt
+ end_city/bridge_end.nbt
+ end_city/bridge_gentle_stairs.nbt
+ end_city/bridge_piece.nbt
+ end_city/bridge_steep_stairs.nbt
+ end_city/fat_tower_base.nbt
+ end_city/fat_tower_middle.nbt
+ end_city/fat_tower_top.nbt
+ end_city/second_floor_1.nbt
+ end_city/second_floor_2.nbt
+ end_city/second_roof.nbt
+ end_city/ship.nbt
+ end_city/third_floor_1.nbt
+ end_city/third_floor_2.nbt
+ end_city/third_roof.nbt
+ end_city/tower_base.nbt
+ end_city/tower_floor.nbt
+ end_city/tower_piece.nbt
+ end_city/tower_top.nbt
- endcity/base_floor.nbt
- endcity/base_roof.nbt
- endcity/bridge_end.nbt
- endcity/bridge_gentle_stairs.nbt
- endcity/bridge_piece.nbt
- endcity/bridge_steep_stairs.nbt
- endcity/fat_tower_base.nbt
- endcity/fat_tower_middle.nbt
- endcity/fat_tower_top.nbt
- endcity/second_floor_2.nbt
- endcity/second_floor.nbt
- endcity/second_roof.nbt
- endcity/ship.nbt
- endcity/third_floor_b.nbt
- endcity/third_floor_c.nbt
- endcity/third_floor.nbt
- endcity/third_roof.nbt
- endcity/tower_base.nbt
- endcity/tower_floor.nbt
- endcity/tower_piece.nbt
- endcity/tower_top.nbt
+ fossil/skull_1_coal.nbt
+ fossil/skull_1.nbt
+ fossil/skull_2_coal.nbt
+ fossil/skull_2.nbt
+ fossil/skull_3_coal.nbt
+ fossil/skull_3.nbt
+ fossil/skull_4_coal.nbt
+ fossil/skull_4.nbt
+ fossil/spine_1_coal.nbt
+ fossil/spine_1.nbt
+ fossil/spine_2_coal.nbt
+ fossil/spine_2.nbt
+ fossil/spine_3_coal.nbt
+ fossil/spine_3.nbt
+ fossil/spine_4_coal.nbt
+ fossil/spine_4.nbt
- fossils/fossil_skull_01_coal.nbt
- fossils/fossil_skull_01.nbt
- fossils/fossil_skull_02_coal.nbt
- fossils/fossil_skull_02.nbt
- fossils/fossil_skull_03_coal.nbt
- fossils/fossil_skull_03.nbt
- fossils/fossil_skull_04_coal.nbt
- fossils/fossil_skull_04.nbt
- fossils/fossil_spine_01_coal.nbt
- fossils/fossil_spine_01.nbt
- fossils/fossil_spine_02_coal.nbt
- fossils/fossil_spine_02.nbt
- fossils/fossil_spine_03_coal.nbt
- fossils/fossil_spine_03.nbt
- fossils/fossil_spine_04_coal.nbt
- fossils/fossil_spine_04.nbt
+ igloo/bottom.nbt
- igloo/igloo_bottom.nbt
- igloo/igloo_middle.nbt
- igloo/igloo_top.nbt
+ igloo/middle.nbt
+ igloo/top.nbt
- mansion/1x1_a1.nbt
- mansion/1x1_a2.nbt
- mansion/1x1_a3.nbt
- mansion/1x1_a4.nbt
- mansion/1x1_a5.nbt
- mansion/1x1_as1.nbt
- mansion/1x1_as2.nbt
- mansion/1x1_as3.nbt
- mansion/1x1_as4.nbt
- mansion/1x1_b1.nbt
- mansion/1x1_b2.nbt
- mansion/1x1_b3.nbt
- mansion/1x1_b4.nbt
- mansion/1x1_b5.nbt
- mansion/1x2_a1.nbt
- mansion/1x2_a2.nbt
- mansion/1x2_a3.nbt
- mansion/1x2_a4.nbt
- mansion/1x2_a5.nbt
- mansion/1x2_a6.nbt
- mansion/1x2_a7.nbt
- mansion/1x2_a8.nbt
- mansion/1x2_a9.nbt
- mansion/1x2_b1.nbt
- mansion/1x2_b2.nbt
- mansion/1x2_b3.nbt
- mansion/1x2_b4.nbt
- mansion/1x2_b5.nbt
- mansion/1x2_c_stairs.nbt
- mansion/1x2_c1.nbt
- mansion/1x2_c2.nbt
- mansion/1x2_c3.nbt
- mansion/1x2_c4.nbt
- mansion/1x2_d_stairs.nbt
- mansion/1x2_d1.nbt
- mansion/1x2_d2.nbt
- mansion/1x2_d3.nbt
- mansion/1x2_d4.nbt
- mansion/1x2_d5.nbt
- mansion/1x2_s1.nbt
- mansion/1x2_s2.nbt
- mansion/1x2_se1.nbt
- mansion/2x2_a1.nbt
- mansion/2x2_a2.nbt
- mansion/2x2_a3.nbt
- mansion/2x2_a4.nbt
- mansion/2x2_b1.nbt
- mansion/2x2_b2.nbt
- mansion/2x2_b3.nbt
- mansion/2x2_b4.nbt
- mansion/2x2_b5.nbt
- mansion/2x2_s1.nbt
- mansion/carpet_east.nbt
- mansion/carpet_north.nbt
- mansion/carpet_south_2.nbt
- mansion/carpet_south.nbt
- mansion/carpet_west_2.nbt
- mansion/carpet_west.nbt
- mansion/corridor_floor.nbt
- mansion/entrance.nbt
- mansion/indoors_door_2.nbt
- mansion/indoors_door.nbt
- mansion/indoors_wall_2.nbt
- mansion/indoors_wall.nbt
- mansion/roof_corner.nbt
- mansion/roof_front.nbt
- mansion/roof_inner_corner.nbt
- mansion/roof.nbt
- mansion/small_wall_corner.nbt
- mansion/small_wall.nbt
- mansion/wall_corner.nbt
- mansion/wall_flat.nbt
- mansion/wall_window.nbt
- ruin/big_ruin_warm4.nbt
- ruin/big_ruin_warm5.nbt
- ruin/big_ruin_warm6.nbt
- ruin/big_ruin_warm7.nbt
- ruin/big_ruin1_brick.nbt
- ruin/big_ruin1_cracked.nbt
- ruin/big_ruin1_mossy.nbt
- ruin/big_ruin2_brick.nbt
- ruin/big_ruin2_cracked.nbt
- ruin/big_ruin2_mossy.nbt
- ruin/big_ruin3_brick.nbt
- ruin/big_ruin3_cracked.nbt
- ruin/big_ruin3_mossy.nbt
- ruin/big_ruin8_brick.nbt
- ruin/big_ruin8_cracked.nbt
- ruin/big_ruin8_mossy.nbt
- ruin/ruin_warm1.nbt
- ruin/ruin_warm2.nbt
- ruin/ruin_warm3.nbt
- ruin/ruin_warm4.nbt
- ruin/ruin_warm5.nbt
- ruin/ruin_warm6.nbt
- ruin/ruin_warm7.nbt
- ruin/ruin_warm8.nbt
- ruin/ruin1_brick.nbt
- ruin/ruin1_cracked.nbt
- ruin/ruin1_mossy.nbt
- ruin/ruin2_brick.nbt
- ruin/ruin2_cracked.nbt
- ruin/ruin2_mossy.nbt
- ruin/ruin3_brick.nbt
- ruin/ruin3_cracked.nbt
- ruin/ruin3_mossy.nbt
- ruin/ruin4_brick.nbt
- ruin/ruin4_cracked.nbt
- ruin/ruin4_mossy.nbt
- ruin/ruin5_brick.nbt
- ruin/ruin5_cracked.nbt
- ruin/ruin5_mossy.nbt
- ruin/ruin6_brick.nbt
- ruin/ruin6_cracked.nbt
- ruin/ruin6_mossy.nbt
- ruin/ruin7_brick.nbt
- ruin/ruin7_cracked.nbt
- ruin/ruin7_mossy.nbt
- ruin/ruin8_brick.nbt
- ruin/ruin8_cracked.nbt
- ruin/ruin8_mossy.nbt
+ underwater_ruin/big_brick_1.nbt
+ underwater_ruin/big_brick_2.nbt
+ underwater_ruin/big_brick_3.nbt
+ underwater_ruin/big_brick_8.nbt
+ underwater_ruin/big_cracked_1.nbt
+ underwater_ruin/big_cracked_2.nbt
+ underwater_ruin/big_cracked_3.nbt
+ underwater_ruin/big_cracked_8.nbt
+ underwater_ruin/big_mossy_1.nbt
+ underwater_ruin/big_mossy_2.nbt
+ underwater_ruin/big_mossy_3.nbt
+ underwater_ruin/big_mossy_8.nbt
+ underwater_ruin/big_warm_4.nbt
+ underwater_ruin/big_warm_5.nbt
+ underwater_ruin/big_warm_6.nbt
+ underwater_ruin/big_warm_7.nbt
+ underwater_ruin/brick_1.nbt
+ underwater_ruin/brick_2.nbt
+ underwater_ruin/brick_3.nbt
+ underwater_ruin/brick_4.nbt
+ underwater_ruin/brick_5.nbt
+ underwater_ruin/brick_6.nbt
+ underwater_ruin/brick_7.nbt
+ underwater_ruin/brick_8.nbt
+ underwater_ruin/cracked_1.nbt
+ underwater_ruin/cracked_2.nbt
+ underwater_ruin/cracked_3.nbt
+ underwater_ruin/cracked_4.nbt
+ underwater_ruin/cracked_5.nbt
+ underwater_ruin/cracked_6.nbt
+ underwater_ruin/cracked_7.nbt
+ underwater_ruin/cracked_8.nbt
+ underwater_ruin/mossy_1.nbt
+ underwater_ruin/mossy_2.nbt
+ underwater_ruin/mossy_3.nbt
+ underwater_ruin/mossy_4.nbt
+ underwater_ruin/mossy_5.nbt
+ underwater_ruin/mossy_6.nbt
+ underwater_ruin/mossy_7.nbt
+ underwater_ruin/mossy_8.nbt
+ underwater_ruin/warm_1.nbt
+ underwater_ruin/warm_2.nbt
+ underwater_ruin/warm_3.nbt
+ underwater_ruin/warm_4.nbt
+ underwater_ruin/warm_5.nbt
+ underwater_ruin/warm_6.nbt
+ underwater_ruin/warm_7.nbt
+ underwater_ruin/warm_8.nbt
+ woodland_mansion/1x1_a1.nbt
+ woodland_mansion/1x1_a2.nbt
+ woodland_mansion/1x1_a3.nbt
+ woodland_mansion/1x1_a4.nbt
+ woodland_mansion/1x1_a5.nbt
+ woodland_mansion/1x1_as1.nbt
+ woodland_mansion/1x1_as2.nbt
+ woodland_mansion/1x1_as3.nbt
+ woodland_mansion/1x1_as4.nbt
+ woodland_mansion/1x1_b1.nbt
+ woodland_mansion/1x1_b2.nbt
+ woodland_mansion/1x1_b3.nbt
+ woodland_mansion/1x1_b4.nbt
+ woodland_mansion/1x1_b5.nbt
+ woodland_mansion/1x2_a1.nbt
+ woodland_mansion/1x2_a2.nbt
+ woodland_mansion/1x2_a3.nbt
+ woodland_mansion/1x2_a4.nbt
+ woodland_mansion/1x2_a5.nbt
+ woodland_mansion/1x2_a6.nbt
+ woodland_mansion/1x2_a7.nbt
+ woodland_mansion/1x2_a8.nbt
+ woodland_mansion/1x2_a9.nbt
+ woodland_mansion/1x2_b1.nbt
+ woodland_mansion/1x2_b2.nbt
+ woodland_mansion/1x2_b3.nbt
+ woodland_mansion/1x2_b4.nbt
+ woodland_mansion/1x2_b5.nbt
+ woodland_mansion/1x2_c_stairs.nbt
+ woodland_mansion/1x2_c1.nbt
+ woodland_mansion/1x2_c2.nbt
+ woodland_mansion/1x2_c3.nbt
+ woodland_mansion/1x2_c4.nbt
+ woodland_mansion/1x2_d_stairs.nbt
+ woodland_mansion/1x2_d1.nbt
+ woodland_mansion/1x2_d2.nbt
+ woodland_mansion/1x2_d3.nbt
+ woodland_mansion/1x2_d4.nbt
+ woodland_mansion/1x2_d5.nbt
+ woodland_mansion/1x2_s1.nbt
+ woodland_mansion/1x2_s2.nbt
+ woodland_mansion/1x2_se1.nbt
+ woodland_mansion/2x2_a1.nbt
+ woodland_mansion/2x2_a2.nbt
+ woodland_mansion/2x2_a3.nbt
+ woodland_mansion/2x2_a4.nbt
+ woodland_mansion/2x2_b1.nbt
+ woodland_mansion/2x2_b2.nbt
+ woodland_mansion/2x2_b3.nbt
+ woodland_mansion/2x2_b4.nbt
+ woodland_mansion/2x2_b5.nbt
+ woodland_mansion/2x2_s1.nbt
+ woodland_mansion/carpet_east.nbt
+ woodland_mansion/carpet_north.nbt
+ woodland_mansion/carpet_south_1.nbt
+ woodland_mansion/carpet_south_2.nbt
+ woodland_mansion/carpet_west_1.nbt
+ woodland_mansion/carpet_west_2.nbt
+ woodland_mansion/corridor_floor.nbt
+ woodland_mansion/entrance.nbt
+ woodland_mansion/indoors_door_1.nbt
+ woodland_mansion/indoors_door_2.nbt
+ woodland_mansion/indoors_wall_1.nbt
+ woodland_mansion/indoors_wall_2.nbt
+ woodland_mansion/roof_corner.nbt
+ woodland_mansion/roof_front.nbt
+ woodland_mansion/roof_inner_corner.nbt
+ woodland_mansion/roof.nbt
+ woodland_mansion/small_wall_corner.nbt
+ woodland_mansion/small_wall.nbt
+ woodland_mansion/wall_corner.nbt
+ woodland_mansion/wall_flat.nbt
+ woodland_mansion/wall_window.nbt
```

</details>


<details><summary>textures.txt</summary>

```diff
+ blocks/acacia_door_bottom.png
- blocks/acacia_door_lower.png
+ blocks/acacia_door_top.png
- blocks/acacia_door_upper.png
+ blocks/birch_door_bottom.png
- blocks/birch_door_lower.png
+ blocks/birch_door_top.png
- blocks/birch_door_upper.png
+ blocks/black_shulker_box_top.png
+ blocks/blue_shulker_box_top.png
- blocks/brick.png
+ blocks/bricks.png
+ blocks/brown_shulker_box_top.png
+ blocks/carved_pumpkin.png
+ blocks/cyan_shulker_box_top.png
+ blocks/dark_oak_door_bottom.png
- blocks/dark_oak_door_lower.png
+ blocks/dark_oak_door_top.png
- blocks/dark_oak_door_upper.png
- blocks/dried_kelp_side_mirror.png
+ blocks/farmland_moist.png
- blocks/farmland_wet.png
+ blocks/fire_0.png
+ blocks/fire_1.png
- blocks/fire_layer_0.png
- blocks/fire_layer_1.png
+ blocks/granite.png
+ blocks/gray_shulker_box_top.png
+ blocks/green_shulker_box_top.png
+ blocks/iron_door_bottom.png
- blocks/iron_door_lower.png
+ blocks/iron_door_top.png
- blocks/iron_door_upper.png
+ blocks/item_frame.png
- blocks/itemframe_background.png
+ blocks/jack_o_lantern.png
+ blocks/jungle_door_bottom.png
- blocks/jungle_door_lower.png
+ blocks/jungle_door_top.png
- blocks/jungle_door_upper.png
- blocks/kelp_top.png
+ blocks/kelp.png
+ blocks/light_blue_shulker_box_top.png
+ blocks/light_gray_shulker_box_top.png
+ blocks/lime_shulker_box_top.png
+ blocks/magenta_shulker_box_top.png
- blocks/nether_brick.png
+ blocks/nether_bricks.png
+ blocks/nether_quartz_ore.png
+ blocks/oak_door_bottom.png
- blocks/oak_door_lower.png
+ blocks/oak_door_top.png
- blocks/oak_door_upper.png
+ blocks/orange_shulker_box_top.png
+ blocks/pink_shulker_box_top.png
- blocks/pumpkin_face_on.png
- blocks/pumpkin_face.png
+ blocks/purple_shulker_box_top.png
- blocks/quartz_ore.png
- blocks/red_nether_brick.png
+ blocks/red_nether_bricks.png
+ blocks/red_shulker_box_top.png
- blocks/redstone_lamp_off.png
+ blocks/redstone_lamp.png
+ blocks/shulker_box_top.png
- blocks/shulker_top_black.png
- blocks/shulker_top_blue.png
- blocks/shulker_top_brown.png
- blocks/shulker_top_cyan.png
- blocks/shulker_top_gray.png
- blocks/shulker_top_green.png
- blocks/shulker_top_light_blue.png
- blocks/shulker_top_light_gray.png
- blocks/shulker_top_lime.png
- blocks/shulker_top_magenta.png
- blocks/shulker_top_orange.png
- blocks/shulker_top_pink.png
- blocks/shulker_top_purple.png
- blocks/shulker_top_red.png
- blocks/shulker_top_white.png
- blocks/shulker_top_yellow.png
- blocks/shulker_top.png
+ blocks/spruce_door_bottom.png
- blocks/spruce_door_lower.png
+ blocks/spruce_door_top.png
- blocks/spruce_door_upper.png
- blocks/stone_granite.png
- blocks/trip_wire_hook.png
- blocks/trip_wire.png
+ blocks/tripwire_hook.png
+ blocks/tripwire.png
- blocks/turtle_egg_not_cracked.png
+ blocks/turtle_egg.png
+ blocks/white_shulker_box_top.png
+ blocks/yellow_shulker_box_top.png
+ entity/boat/acacia.png
+ entity/boat/birch.png
- entity/boat/boat_acacia.png
- entity/boat/boat_birch.png
- entity/boat/boat_darkoak.png
- entity/boat/boat_jungle.png
- entity/boat/boat_oak.png
- entity/boat/boat_spruce.png
+ entity/boat/dark_oak.png
+ entity/boat/jungle.png
+ entity/boat/oak.png
+ entity/boat/spruce.png
- entity/fish/cod_mob.png
+ entity/fish/cod.png
- entity/fish/salmon_mob.png
+ entity/fish/salmon.png
+ entity/llama/brown.png
+ entity/llama/creamy.png
+ entity/llama/decor/black.png
+ entity/llama/decor/blue.png
+ entity/llama/decor/brown.png
+ entity/llama/decor/cyan.png
- entity/llama/decor/decor_black.png
- entity/llama/decor/decor_blue.png
- entity/llama/decor/decor_brown.png
- entity/llama/decor/decor_cyan.png
- entity/llama/decor/decor_gray.png
- entity/llama/decor/decor_green.png
- entity/llama/decor/decor_light_blue.png
- entity/llama/decor/decor_light_gray.png
- entity/llama/decor/decor_lime.png
- entity/llama/decor/decor_magenta.png
- entity/llama/decor/decor_orange.png
- entity/llama/decor/decor_pink.png
- entity/llama/decor/decor_purple.png
- entity/llama/decor/decor_red.png
- entity/llama/decor/decor_white.png
- entity/llama/decor/decor_yellow.png
+ entity/llama/decor/gray.png
+ entity/llama/decor/green.png
+ entity/llama/decor/light_blue.png
+ entity/llama/decor/light_gray.png
+ entity/llama/decor/lime.png
+ entity/llama/decor/magenta.png
+ entity/llama/decor/orange.png
+ entity/llama/decor/pink.png
+ entity/llama/decor/purple.png
+ entity/llama/decor/red.png
+ entity/llama/decor/white.png
+ entity/llama/decor/yellow.png
+ entity/llama/gray.png
- entity/llama/llama_brown.png
- entity/llama/llama_creamy.png
- entity/llama/llama_gray.png
- entity/llama/llama_white.png
- entity/llama/llama.png
+ entity/llama/white.png
+ items/filled_map_markings.png
+ items/filled_map.png
- items/fish_pufferfish_raw.png
- items/map_filled_markings.png
- items/map_filled.png
```

</details>
