<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w34a ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w34a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-08-22T12:06:21+00:00</td></tr>
<tr><th>SHA1</th><td>79310fef2c7bb69085e9459568152049f706e52d</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/79310fef2c7bb69085e9459568152049f706e52d/19w34a.json">https://piston-meta.mojang.com/v1/packages/79310fef2c7bb69085e9459568152049f706e52d/19w34a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json">https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/288962c67d083e35d4313cf0eba8ad1e27173d17/server.jar">https://piston-data.mojang.com/v1/objects/288962c67d083e35d4313cf0eba8ad1e27173d17/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/9d74a00192ffc6b83c8b3c754619d057a9353754/client.jar">https://piston-data.mojang.com/v1/objects/9d74a00192ffc6b83c8b3c754619d057a9353754/client.jar</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.14.4">1.14.4</a>
## File structure

<details><summary>data/</summary>

```diff
+  minecraft/advancements/recipes/decorations/bee_hive.json
-  minecraft/advancements/recipes/misc/sugar.json
+  minecraft/advancements/recipes/misc/sugar_from_honey_bottle.json
+  minecraft/advancements/recipes/misc/sugar_from_sugar_cane.json
+  minecraft/loot_tables/blocks/bee_hive.json
+  minecraft/loot_tables/blocks/bee_nest.json
+  minecraft/loot_tables/entities/bee.json
+  minecraft/recipes/bee_hive.json
-  minecraft/recipes/sugar.json
+  minecraft/recipes/sugar_from_honey_bottle.json
+  minecraft/recipes/sugar_from_sugar_cane.json
+  minecraft/tags/blocks/bee_growables.json
+  minecraft/tags/blocks/beehives.json
+  minecraft/tags/blocks/crops.json
+  minecraft/tags/blocks/flowers.json
+  minecraft/tags/blocks/tall_flowers.json
+  minecraft/tags/items/flowers.json
+  minecraft/tags/items/tall_flowers.json
```

</details>

<details><summary>assets/</summary>

```diff
+  minecraft/blockstates/bee_hive.json
+  minecraft/blockstates/bee_nest.json
+  minecraft/models/block/bee_hive.json
+  minecraft/models/block/bee_hive_honey.json
+  minecraft/models/block/bee_nest.json
+  minecraft/models/block/bee_nest_honey.json
+  minecraft/models/item/bee_hive.json
+  minecraft/models/item/bee_nest.json
+  minecraft/models/item/bee_spawn_egg.json
+  minecraft/models/item/honey_bottle.json
+  minecraft/models/item/honeycomb.json
+  minecraft/particles/dripping_honey.json
+  minecraft/particles/falling_honey.json
+  minecraft/particles/falling_nectar.json
+  minecraft/particles/landing_honey.json
+  minecraft/textures/block/bee_hive_bottom.png
+  minecraft/textures/block/bee_hive_front.png
+  minecraft/textures/block/bee_hive_front_honey.png
+  minecraft/textures/block/bee_hive_side.png
+  minecraft/textures/block/bee_hive_top.png
+  minecraft/textures/block/bee_nest_bottom.png
+  minecraft/textures/block/bee_nest_front.png
+  minecraft/textures/block/bee_nest_front_honey.png
+  minecraft/textures/block/bee_nest_side.png
+  minecraft/textures/block/bee_nest_top.png
+  minecraft/textures/block/wax_block.png
+  minecraft/textures/entity/bee
+  minecraft/textures/entity/bee/bee.png
+  minecraft/textures/entity/bee/bee_angry.png
+  minecraft/textures/entity/bee/bee_angry_nectar.png
+  minecraft/textures/entity/bee/bee_nectar.png
+  minecraft/textures/entity/bee/bee_stinger.png
+  minecraft/textures/item/crystallized_honey.png
+  minecraft/textures/item/honey_bottle.png
+  minecraft/textures/item/honeycomb.png
```

</details>

## Registries

<details><summary>block.txt</summary>

```diff
+ minecraft:bee_nest
+ minecraft:bee_hive
```

</details>

<details><summary>block_entity_type.txt</summary>

```diff
+ minecraft:beehive
```

</details>

<details><summary>entity_type.txt</summary>

```diff
+ minecraft:bee
```

</details>

<details><summary>item.txt</summary>

```diff
+ minecraft:bee_spawn_egg
+ minecraft:honeycomb
+ minecraft:bee_nest
+ minecraft:bee_hive
+ minecraft:honey_bottle
```

</details>

<details><summary>menu.txt</summary>

```diff
- minecraft:cartography
+ minecraft:cartography_table
```

</details>

<details><summary>particle_type.txt</summary>

```diff
+ minecraft:dripping_honey
+ minecraft:falling_honey
+ minecraft:landing_honey
+ minecraft:falling_nectar
```

</details>

<details><summary>point_of_interest_type.txt</summary>

```diff
+ minecraft:bee_hive
+ minecraft:bee_nest
```

</details>

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:entity.bee.death
+ minecraft:entity.bee.hurt
+ minecraft:entity.bee.loop_aggressive
+ minecraft:entity.bee.loop
+ minecraft:entity.bee.sting
+ minecraft:entity.bee.pollinate
+ minecraft:block.beehive.drip
+ minecraft:block.beehive.enter
+ minecraft:block.beehive.exit
+ minecraft:block.beehive.shear
+ minecraft:block.beehive.work
+ minecraft:item.honey_bottle.drink
```

</details>

## Tags

<details><summary>list</summary>

```diff
+ blocks/beehives.json
+ blocks/bee_growables.json
+ blocks/crops.json
+ blocks/flowers.json
+ blocks/tall_flowers.json
+ items/flowers.json
+ items/tall_flowers.json
```

</details>

## Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/misc/sugar.json
+ recipes/decorations/bee_hive.json
+ recipes/misc/sugar_from_honey_bottle.json
+ recipes/misc/sugar_from_sugar_cane.json
```

</details>

<details><summary>languages.txt</summary>

```diff
- got_de.json
- kab_kab.json
- moh_ca.json
- nuk.json
- oj_ca.json
- scn.json
- swg.json
- tzl_tzl.json
- realms/lang/got_de.json
- realms/lang/kab_kab.json
- realms/lang/moh_ca.json
- realms/lang/nuk.json
- realms/lang/oj_ca.json
- realms/lang/scn.json
- realms/lang/swg.json
- realms/lang/tzl_tzl.json
+ lmo.json
+ lzh.json
+ rpr.json
+ zh_hk.json
+ realms/lang/lmo.json
+ realms/lang/lzh.json
+ realms/lang/rpr.json
+ realms/lang/zh_hk.json
```

</details>

<details><summary>loot_tables.txt</summary>

```diff
+ blocks/bee_hive.json
+ blocks/bee_nest.json
+ entities/bee.json
```

</details>

<details><summary>particles.txt</summary>

```diff
+ dripping_honey.json
+ falling_honey.json
+ falling_nectar.json
+ landing_honey.json
```

</details>

<details><summary>recipes.txt</summary>

```diff
- sugar.json
+ bee_hive.json
+ sugar_from_honey_bottle.json
+ sugar_from_sugar_cane.json
```

</details>

<details><summary>sounds.txt</summary>

```diff
+ block/beehive/drip1.ogg
+ block/beehive/drip2.ogg
+ block/beehive/drip3.ogg
+ block/beehive/drip4.ogg
+ block/beehive/drip5.ogg
+ block/beehive/drip6.ogg
+ block/beehive/enter.ogg
+ block/beehive/exit.ogg
+ block/beehive/shear.ogg
+ block/beehive/work1.ogg
+ block/beehive/work2.ogg
+ block/beehive/work3.ogg
+ block/beehive/work4.ogg
+ block/honeyblock/break1.ogg
+ block/honeyblock/break2.ogg
+ block/honeyblock/break3.ogg
+ block/honeyblock/break4.ogg
+ block/honeyblock/break5.ogg
+ block/honeyblock/slide1.ogg
+ block/honeyblock/slide2.ogg
+ block/honeyblock/slide3.ogg
+ block/honeyblock/slide4.ogg
+ block/honeyblock/step1.ogg
+ block/honeyblock/step2.ogg
+ block/honeyblock/step3.ogg
+ block/honeyblock/step4.ogg
+ block/honeyblock/step5.ogg
+ item/bottle/drink_honey1.ogg
+ item/bottle/drink_honey2.ogg
+ item/bottle/drink_honey3.ogg
+ mob/bee/aggressive1.ogg
+ mob/bee/aggressive2.ogg
+ mob/bee/aggressive3.ogg
+ mob/bee/death1.ogg
+ mob/bee/death2.ogg
+ mob/bee/hurt1.ogg
+ mob/bee/hurt2.ogg
+ mob/bee/hurt3.ogg
+ mob/bee/loop1.ogg
+ mob/bee/loop2.ogg
+ mob/bee/loop3.ogg
+ mob/bee/loop4.ogg
+ mob/bee/loop5.ogg
+ mob/bee/pollinate1.ogg
+ mob/bee/pollinate2.ogg
+ mob/bee/pollinate3.ogg
+ mob/bee/pollinate4.ogg
+ mob/bee/sting.ogg
+ mob/irongolem/damage1.ogg
+ mob/irongolem/damage2.ogg
+ mob/irongolem/repair.ogg
```

</details>

<details><summary>tags.txt</summary>

```diff
+ blocks/beehives.json
+ blocks/bee_growables.json
+ blocks/crops.json
+ blocks/flowers.json
+ blocks/tall_flowers.json
+ items/flowers.json
+ items/tall_flowers.json
```

</details>

<details><summary>textures.txt</summary>

```diff
+ block/bee_hive_bottom.png
+ block/bee_hive_front.png
+ block/bee_hive_front_honey.png
+ block/bee_hive_side.png
+ block/bee_hive_top.png
+ block/bee_nest_bottom.png
+ block/bee_nest_front.png
+ block/bee_nest_front_honey.png
+ block/bee_nest_side.png
+ block/bee_nest_top.png
+ block/wax_block.png
+ entity/bee/bee.png
+ entity/bee/bee_angry.png
+ entity/bee/bee_angry_nectar.png
+ entity/bee/bee_nectar.png
+ entity/bee/bee_stinger.png
+ item/crystallized_honey.png
+ item/honeycomb.png
+ item/honey_bottle.png
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