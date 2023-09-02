<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w44a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w44a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-10-31T15:29:16+00:00</td></tr>
<tr><th>SHA1</th><td>7bee20111c1cd50fb0e26b689ea648ff84989ae6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/7bee20111c1cd50fb0e26b689ea648ff84989ae6/18w44a.json">https://piston-meta.mojang.com/v1/packages/7bee20111c1cd50fb0e26b689ea648ff84989ae6/18w44a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/e70221701d85ad9ed8be35e042f4c8e52fb627ec/server.jar">https://piston-data.mojang.com/v1/objects/e70221701d85ad9ed8be35e042f4c8e52fb627ec/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/20ea61f07e34b3e81ca356b6a71cc98cc4e571a9/client.jar">https://piston-data.mojang.com/v1/objects/20ea61f07e34b3e81ca356b6a71cc98cc4e571a9/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w43c">18w43c</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/husbandry/complete_catalogue.json
+  minecraft/loot_tables/blocks/barrel.json
+  minecraft/loot_tables/blocks/bell.json
+  minecraft/loot_tables/blocks/blast_furnace.json
+  minecraft/loot_tables/blocks/cartography_table.json
+  minecraft/loot_tables/blocks/fletching_table.json
+  minecraft/loot_tables/blocks/grindstone.json
+  minecraft/loot_tables/blocks/lectern.json
+  minecraft/loot_tables/blocks/smithing_table.json
+  minecraft/loot_tables/blocks/smoker.json
+  minecraft/loot_tables/blocks/stonecutter.json
+  minecraft/loot_tables/entities/armor_stand.json
+  minecraft/loot_tables/entities/cat.json
+  minecraft/loot_tables/entities/cat_morning_gift.json
+  minecraft/loot_tables/entities/player.json
+  minecraft/loot_tables/entities/wither.json
+  minecraft/tags/blocks/beds.json
+  minecraft/tags/items/beds.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/barrel.json
+  minecraft/blockstates/bell.json
+  minecraft/blockstates/blast_furnace.json
+  minecraft/blockstates/cartography_table.json
+  minecraft/blockstates/fletching_table.json
+  minecraft/blockstates/grindstone.json
+  minecraft/blockstates/lectern.json
+  minecraft/blockstates/smithing_table.json
+  minecraft/blockstates/smoker.json
+  minecraft/blockstates/stonecutter.json
+  minecraft/models/block/barrel.json
+  minecraft/models/block/bell_ceiling.json
+  minecraft/models/block/bell_floor.json
+  minecraft/models/block/blast_furnace.json
+  minecraft/models/block/blast_furnace_on.json
+  minecraft/models/block/cartography_table.json
+  minecraft/models/block/fletching_table.json
+  minecraft/models/block/grindstone.json
+  minecraft/models/block/grindstone_inventory.json
+  minecraft/models/block/lectern.json
+  minecraft/models/block/smithing_table.json
+  minecraft/models/block/smoker.json
+  minecraft/models/block/smoker_on.json
+  minecraft/models/block/stonecutter.json
+  minecraft/models/item/barrel.json
+  minecraft/models/item/bell.json
+  minecraft/models/item/blast_furnace.json
+  minecraft/models/item/cartography_table.json
+  minecraft/models/item/cat_spawn_egg.json
+  minecraft/models/item/fletching_table.json
+  minecraft/models/item/grindstone.json
+  minecraft/models/item/lectern.json
+  minecraft/models/item/smithing_table.json
+  minecraft/models/item/smoker.json
+  minecraft/models/item/stonecutter.json
+  minecraft/textures/block/barrel_bottom.png
+  minecraft/textures/block/barrel_side.png
+  minecraft/textures/block/barrel_top.png
+  minecraft/textures/block/bell_bottom.png
+  minecraft/textures/block/bell_side.png
+  minecraft/textures/block/bell_top.png
+  minecraft/textures/block/blast_furnace_front.png
+  minecraft/textures/block/blast_furnace_front_on.png
+  minecraft/textures/block/blast_furnace_front_on.png.mcmeta
+  minecraft/textures/block/blast_furnace_side.png
+  minecraft/textures/block/blast_furnace_top.png
+  minecraft/textures/block/cartography_table_front.png
+  minecraft/textures/block/cartography_table_side.png
+  minecraft/textures/block/cartography_table_top.png
+  minecraft/textures/block/fletching_table_front.png
+  minecraft/textures/block/fletching_table_side.png
+  minecraft/textures/block/fletching_table_top.png
+  minecraft/textures/block/grindstone_pivot.png
+  minecraft/textures/block/grindstone_round.png
+  minecraft/textures/block/grindstone_side.png
+  minecraft/textures/block/lectern.png
+  minecraft/textures/block/lectern_base_sides.png
+  minecraft/textures/block/lectern_base_top.png
+  minecraft/textures/block/lectern_bottom.png
+  minecraft/textures/block/lectern_front.png
+  minecraft/textures/block/lectern_sides.png
+  minecraft/textures/block/lectern_top.png
+  minecraft/textures/block/lectern_top_sides.png
+  minecraft/textures/block/smithing_table_front.png
+  minecraft/textures/block/smithing_table_side.png
+  minecraft/textures/block/smithing_table_top.png
+  minecraft/textures/block/smoker_bottom.png
+  minecraft/textures/block/smoker_front.png
+  minecraft/textures/block/smoker_front_on.png
+  minecraft/textures/block/smoker_front_on.png.mcmeta
+  minecraft/textures/block/smoker_side.png
+  minecraft/textures/block/smoker_top.png
+  minecraft/textures/block/stonecutter_bottom.png
+  minecraft/textures/block/stonecutter_saw.png
+  minecraft/textures/block/stonecutter_side.png
+  minecraft/textures/block/stonecutter_top.png
+  minecraft/textures/entity/cat/all_black.png
+  minecraft/textures/entity/cat/british_shorthair.png
+  minecraft/textures/entity/cat/calico.png
+  minecraft/textures/entity/cat/cat_collar.png
+  minecraft/textures/entity/cat/persian.png
+  minecraft/textures/entity/cat/ragdoll.png
+  minecraft/textures/entity/cat/tabby.png
+  minecraft/textures/entity/cat/white.png
+  minecraft/textures/item/bell.png
```

</details>

## Commands

<details><summary>drop.txt</summary>

```diff
- drop block <targetPos: block_pos> distribute award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> replace award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> <count: integer> award <loot_table: resource_location>
- drop block <targetPos: block_pos> insert <slot: item_slot> <count: integer> replace award <loot_table: resource_location>
- drop entity <entities: entity> <slot: item_slot> award <loot_table: resource_location>
- drop entity <entities: entity> <slot: item_slot> <count: integer> award <loot_table: resource_location>
- drop player <players: entity> award <loot_table: resource_location>
- drop world <targetPos: vec3> award <loot_table: resource_location>
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/beds.json
+ items/beds.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
+ husbandry/complete_catalogue.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
+ blocks/barrel.json
+ blocks/bell.json
+ blocks/blast_furnace.json
+ blocks/cartography_table.json
+ blocks/fletching_table.json
+ blocks/grindstone.json
+ blocks/lectern.json
+ blocks/smithing_table.json
+ blocks/smoker.json
+ blocks/stonecutter.json
+ entities/armor_stand.json
+ entities/cat.json
+ entities/cat_morning_gift.json
+ entities/player.json
+ entities/wither.json
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/beds.json
+ items/beds.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ block/barrel_bottom.png
+ block/barrel_side.png
+ block/barrel_top.png
+ block/bell_bottom.png
+ block/bell_side.png
+ block/bell_top.png
+ block/blast_furnace_front.png
+ block/blast_furnace_front_on.png
+ block/blast_furnace_side.png
+ block/blast_furnace_top.png
+ block/cartography_table_front.png
+ block/cartography_table_side.png
+ block/cartography_table_top.png
+ block/fletching_table_front.png
+ block/fletching_table_side.png
+ block/fletching_table_top.png
+ block/grindstone_pivot.png
+ block/grindstone_round.png
+ block/grindstone_side.png
+ block/lectern.png
+ block/lectern_base_sides.png
+ block/lectern_base_top.png
+ block/lectern_bottom.png
+ block/lectern_front.png
+ block/lectern_sides.png
+ block/lectern_top.png
+ block/lectern_top_sides.png
+ block/smithing_table_front.png
+ block/smithing_table_side.png
+ block/smithing_table_top.png
+ block/smoker_bottom.png
+ block/smoker_front.png
+ block/smoker_front_on.png
+ block/smoker_side.png
+ block/smoker_top.png
+ block/stonecutter_bottom.png
+ block/stonecutter_saw.png
+ block/stonecutter_side.png
+ block/stonecutter_top.png
+ entity/cat/all_black.png
+ entity/cat/british_shorthair.png
+ entity/cat/calico.png
+ entity/cat/cat_collar.png
+ entity/cat/persian.png
+ entity/cat/ragdoll.png
+ entity/cat/tabby.png
+ entity/cat/white.png
+ item/bell.png
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