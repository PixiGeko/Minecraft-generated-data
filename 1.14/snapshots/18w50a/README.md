<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w50a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w50a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-12-12T14:58:13+00:00</td></tr>
<tr><th>SHA1</th><td>307a38d1f592a92fcff056165ef05323cb499bfc</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/307a38d1f592a92fcff056165ef05323cb499bfc/18w50a.json">https://piston-meta.mojang.com/v1/packages/307a38d1f592a92fcff056165ef05323cb499bfc/18w50a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json">https://piston-meta.mojang.com/v1/packages/43b2f3021fe9f7d768378de95538e22da3ee8301/1.14.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/de0577900a9071758d7f1172dd283bdbe88b7431/server.jar">https://piston-data.mojang.com/v1/objects/de0577900a9071758d7f1172dd283bdbe88b7431/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/865a610fe77eb9d2fea48de1a02229526a391249/client.jar">https://piston-data.mojang.com/v1/objects/865a610fe77eb9d2fea48de1a02229526a391249/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w49a">18w49a</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/advancements/recipes/decorations/barrel.json
+ minecraft/advancements/recipes/decorations/blast_furnace.json
+ minecraft/advancements/recipes/decorations/smoker.json
+ minecraft/advancements/recipes/food/baked_potato_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_beef_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_chicken_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_cod_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_mutton_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_porkchop_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_rabbit_from_smoking.json
+ minecraft/advancements/recipes/food/cooked_salmon_from_smoking.json
+ minecraft/advancements/recipes/food/dried_kelp_from_smoking.json
+ minecraft/advancements/recipes/misc/coal_from_blasting.json
+ minecraft/advancements/recipes/misc/diamond_from_blasting.json
+ minecraft/advancements/recipes/misc/emerald_from_blasting.json
+ minecraft/advancements/recipes/misc/gold_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/gold_nugget_from_blasting.json
+ minecraft/advancements/recipes/misc/iron_ingot_from_blasting.json
+ minecraft/advancements/recipes/misc/iron_nugget_from_blasting.json
+ minecraft/advancements/recipes/misc/lapis_from_blasting.json
+ minecraft/advancements/recipes/misc/quartz_from_blasting.json
+ minecraft/advancements/recipes/redstone/redstone_from_blasting.json
+ minecraft/loot_tables/chests/village/village_fletcher.json
+ minecraft/loot_tables/chests/village/village_temple.json
+ minecraft/loot_tables/chests/village/village_toolsmith.json
+ minecraft/recipes/baked_potato_from_smoking.json
+ minecraft/recipes/barrel.json
+ minecraft/recipes/blast_furnace.json
+ minecraft/recipes/coal_from_blasting.json
+ minecraft/recipes/cooked_beef_from_smoking.json
+ minecraft/recipes/cooked_chicken_from_smoking.json
+ minecraft/recipes/cooked_cod_from_smoking.json
+ minecraft/recipes/cooked_mutton_from_smoking.json
+ minecraft/recipes/cooked_porkchop_from_smoking.json
+ minecraft/recipes/cooked_rabbit_from_smoking.json
+ minecraft/recipes/cooked_salmon_from_smoking.json
+ minecraft/recipes/diamond_from_blasting.json
+ minecraft/recipes/dried_kelp_from_smoking.json
+ minecraft/recipes/emerald_from_blasting.json
+ minecraft/recipes/gold_ingot_from_blasting.json
+ minecraft/recipes/gold_nugget_from_blasting.json
+ minecraft/recipes/iron_ingot_from_blasting.json
+ minecraft/recipes/iron_nugget_from_blasting.json
+ minecraft/recipes/lapis_from_blasting.json
+ minecraft/recipes/quartz_from_blasting.json
+ minecraft/recipes/redstone_from_blasting.json
+ minecraft/recipes/smoker.json
+ minecraft/structures/village/common/animals/cat_black.nbt
+ minecraft/structures/village/common/animals/cat_british.nbt
+ minecraft/structures/village/common/animals/cat_calico.nbt
+ minecraft/structures/village/common/animals/cat_jellie.nbt
+ minecraft/structures/village/common/animals/cat_persian.nbt
+ minecraft/structures/village/common/animals/cat_ragdoll.nbt
+ minecraft/structures/village/common/animals/cat_red.nbt
+ minecraft/structures/village/common/animals/cat_siamese.nbt
+ minecraft/structures/village/common/animals/cat_tabby.nbt
+ minecraft/structures/village/common/animals/cat_white.nbt
+ minecraft/structures/village/desert/desert_lamp_1.nbt
+ minecraft/structures/village/desert/houses/desert_animal_pen_1.nbt
+ minecraft/structures/village/desert/houses/desert_animal_pen_2.nbt
+ minecraft/structures/village/desert/houses/desert_armorer_1.nbt
+ minecraft/structures/village/desert/houses/desert_blacksmith_1.nbt
+ minecraft/structures/village/desert/houses/desert_butcher_shop_1.nbt
+ minecraft/structures/village/desert/houses/desert_cartographer_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_farm_1.nbt
+ minecraft/structures/village/desert/houses/desert_farm_2.nbt
+ minecraft/structures/village/desert/houses/desert_fisher_1.nbt
+ minecraft/structures/village/desert/houses/desert_fletcher_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_large_farm_1.nbt
+ minecraft/structures/village/desert/houses/desert_library_1.nbt
+ minecraft/structures/village/desert/houses/desert_mason_1.nbt
+ minecraft/structures/village/desert/houses/desert_medium_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_medium_house_2.nbt
+ minecraft/structures/village/desert/houses/desert_sheperd_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_shepherd_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_1.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_2.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_3.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_4.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_5.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_6.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_7.nbt
+ minecraft/structures/village/desert/houses/desert_small_house_8.nbt
+ minecraft/structures/village/desert/houses/desert_tannery_1.nbt
+ minecraft/structures/village/desert/houses/desert_temple_1.nbt
+ minecraft/structures/village/desert/houses/desert_temple_2.nbt
+ minecraft/structures/village/desert/houses/desert_tool_smith_1.nbt
+ minecraft/structures/village/desert/houses/desert_weaponsmith_1.nbt
+ minecraft/structures/village/desert/streets/corner_01.nbt
+ minecraft/structures/village/desert/streets/corner_02.nbt
+ minecraft/structures/village/desert/streets/crossroad_01.nbt
+ minecraft/structures/village/desert/streets/crossroad_02.nbt
+ minecraft/structures/village/desert/streets/crossroad_03.nbt
+ minecraft/structures/village/desert/streets/square_01.nbt
+ minecraft/structures/village/desert/streets/square_02.nbt
+ minecraft/structures/village/desert/streets/straight_01.nbt
+ minecraft/structures/village/desert/streets/straight_02.nbt
+ minecraft/structures/village/desert/streets/straight_03.nbt
+ minecraft/structures/village/desert/streets/turn_01.nbt
+ minecraft/structures/village/desert/terminators/terminator_01.nbt
+ minecraft/structures/village/desert/terminators/terminator_02.nbt
+ minecraft/structures/village/desert/town_centers/desert_meeting_point_1.nbt
+ minecraft/structures/village/desert/town_centers/desert_meeting_point_2.nbt
+ minecraft/structures/village/desert/town_centers/desert_meeting_point_3.nbt
+ minecraft/structures/village/taiga/houses/taiga_animal_pen_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_armorer_2.nbt
+ minecraft/structures/village/taiga/houses/taiga_armorer_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_armorer_house_2.nbt
+ minecraft/structures/village/taiga/houses/taiga_butcher_shop_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_cartographer_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_decoration_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_fisher_cottage_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_fletcher_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_lamp_post_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_large_farm_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_large_farm_2.nbt
+ minecraft/structures/village/taiga/houses/taiga_library_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_masons_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_medium_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_medium_house_2.nbt
+ minecraft/structures/village/taiga/houses/taiga_medium_house_3.nbt
+ minecraft/structures/village/taiga/houses/taiga_meeting_point_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_sheperds_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_shepherds_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_farm_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_house_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_house_2.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_house_3.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_house_4.nbt
+ minecraft/structures/village/taiga/houses/taiga_small_house_5.nbt
+ minecraft/structures/village/taiga/houses/taiga_tannery_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_temple_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_tool_smith_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_weapon_smith_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_weaponsmith_1.nbt
+ minecraft/structures/village/taiga/houses/taiga_weaponsmith_2.nbt
+ minecraft/structures/village/taiga/streets/corner_01.nbt
+ minecraft/structures/village/taiga/streets/corner_02.nbt
+ minecraft/structures/village/taiga/streets/corner_03.nbt
+ minecraft/structures/village/taiga/streets/crossroad_01.nbt
+ minecraft/structures/village/taiga/streets/crossroad_02.nbt
+ minecraft/structures/village/taiga/streets/crossroad_03.nbt
+ minecraft/structures/village/taiga/streets/crossroad_04.nbt
+ minecraft/structures/village/taiga/streets/crossroad_05.nbt
+ minecraft/structures/village/taiga/streets/crossroad_06.nbt
+ minecraft/structures/village/taiga/streets/straight_01.nbt
+ minecraft/structures/village/taiga/streets/straight_02.nbt
+ minecraft/structures/village/taiga/streets/straight_03.nbt
+ minecraft/structures/village/taiga/streets/straight_04.nbt
+ minecraft/structures/village/taiga/streets/straight_05.nbt
+ minecraft/structures/village/taiga/streets/straight_06.nbt
+ minecraft/structures/village/taiga/streets/turn_01.nbt
+ minecraft/structures/village/taiga/taiga_decoration_1.nbt
+ minecraft/structures/village/taiga/taiga_decoration_2.nbt
+ minecraft/structures/village/taiga/taiga_decoration_3.nbt
+ minecraft/structures/village/taiga/taiga_decoration_4.nbt
+ minecraft/structures/village/taiga/taiga_lamp_post_1.nbt
+ minecraft/structures/village/taiga/town_centers/taiga_meeting_point_1.nbt
+ minecraft/structures/village/taiga/town_centers/taiga_meeting_point_2.nbt
```

</details>


<details><summary>assets/</summary>

```diff
+ minecraft/models/block/bell_between_walls.json
+ minecraft/models/block/bell_wall.json
+ minecraft/textures/entity/bell/bell_body.png
+ minecraft/textures/entity/cat/jellie.png
- minecraft/textures/entity/villager/butcher.png
- minecraft/textures/entity/villager/farmer.png
- minecraft/textures/entity/villager/librarian.png
- minecraft/textures/entity/villager/priest.png
+ minecraft/textures/entity/villager/profession_level/diamond.png
+ minecraft/textures/entity/villager/profession_level/emerald.png
+ minecraft/textures/entity/villager/profession_level/gold.png
+ minecraft/textures/entity/villager/profession_level/iron.png
+ minecraft/textures/entity/villager/profession_level/stone.png
+ minecraft/textures/entity/villager/profession/armorer.png
+ minecraft/textures/entity/villager/profession/butcher.png
+ minecraft/textures/entity/villager/profession/butcher.png.mcmeta
+ minecraft/textures/entity/villager/profession/cartographer.png
+ minecraft/textures/entity/villager/profession/cleric.png
+ minecraft/textures/entity/villager/profession/farmer.png
+ minecraft/textures/entity/villager/profession/farmer.png.mcmeta
+ minecraft/textures/entity/villager/profession/fisherman.png
+ minecraft/textures/entity/villager/profession/fisherman.png.mcmeta
+ minecraft/textures/entity/villager/profession/fletcher.png
+ minecraft/textures/entity/villager/profession/fletcher.png.mcmeta
+ minecraft/textures/entity/villager/profession/leatherworker.png
+ minecraft/textures/entity/villager/profession/librarian.png
+ minecraft/textures/entity/villager/profession/librarian.png.mcmeta
+ minecraft/textures/entity/villager/profession/mason.png
+ minecraft/textures/entity/villager/profession/nitwit.png
+ minecraft/textures/entity/villager/profession/shepherd.png
+ minecraft/textures/entity/villager/profession/shepherd.png.mcmeta
+ minecraft/textures/entity/villager/profession/toolsmith.png
+ minecraft/textures/entity/villager/profession/weaponsmith.png
- minecraft/textures/entity/villager/smith.png
+ minecraft/textures/entity/villager/type/desert.png
+ minecraft/textures/entity/villager/type/desert.png.mcmeta
+ minecraft/textures/entity/villager/type/jungle.png
+ minecraft/textures/entity/villager/type/plains.png
+ minecraft/textures/entity/villager/type/savanna.png
+ minecraft/textures/entity/villager/type/snow.png
+ minecraft/textures/entity/villager/type/snow.png.mcmeta
+ minecraft/textures/entity/villager/type/swamp.png
+ minecraft/textures/entity/villager/type/taiga.png
+ minecraft/textures/entity/zombie_villager/profession_level/diamond.png
+ minecraft/textures/entity/zombie_villager/profession_level/emerald.png
+ minecraft/textures/entity/zombie_villager/profession_level/gold.png
+ minecraft/textures/entity/zombie_villager/profession_level/iron.png
+ minecraft/textures/entity/zombie_villager/profession_level/stone.png
+ minecraft/textures/entity/zombie_villager/profession/armorer.png
+ minecraft/textures/entity/zombie_villager/profession/butcher.png
+ minecraft/textures/entity/zombie_villager/profession/butcher.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/cartographer.png
+ minecraft/textures/entity/zombie_villager/profession/cleric.png
+ minecraft/textures/entity/zombie_villager/profession/farmer.png
+ minecraft/textures/entity/zombie_villager/profession/farmer.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/fisherman.png
+ minecraft/textures/entity/zombie_villager/profession/fisherman.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/fletcher.png
+ minecraft/textures/entity/zombie_villager/profession/fletcher.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/leatherworker.png
+ minecraft/textures/entity/zombie_villager/profession/librarian.png
+ minecraft/textures/entity/zombie_villager/profession/librarian.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/mason.png
+ minecraft/textures/entity/zombie_villager/profession/nitwit.png
+ minecraft/textures/entity/zombie_villager/profession/shepherd.png
+ minecraft/textures/entity/zombie_villager/profession/shepherd.png.mcmeta
+ minecraft/textures/entity/zombie_villager/profession/toolsmith.png
+ minecraft/textures/entity/zombie_villager/profession/weaponsmith.png
+ minecraft/textures/entity/zombie_villager/type/desert.png
+ minecraft/textures/entity/zombie_villager/type/jungle.png
+ minecraft/textures/entity/zombie_villager/type/plains.png
+ minecraft/textures/entity/zombie_villager/type/savanna.png
+ minecraft/textures/entity/zombie_villager/type/snow.png
+ minecraft/textures/entity/zombie_villager/type/swamp.png
+ minecraft/textures/entity/zombie_villager/type/taiga.png
- minecraft/textures/entity/zombie_villager/zombie_butcher.png
- minecraft/textures/entity/zombie_villager/zombie_farmer.png
- minecraft/textures/entity/zombie_villager/zombie_librarian.png
- minecraft/textures/entity/zombie_villager/zombie_priest.png
- minecraft/textures/entity/zombie_villager/zombie_smith.png
+ minecraft/textures/gui/container/blast_furnace.png
+ minecraft/textures/gui/container/smoker.png
```

</details>


<details><summary>minecraft-generated/</summary>

```diff
- reports/items.json
+ reports/registries.json
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ entity.minecraft.villager.mason
- entity.minecraft.villager.tool_smith
+ entity.minecraft.villager.toolsmith
- entity.minecraft.villager.weapon_smith
+ entity.minecraft.villager.weaponsmith
+ gui.recipebook.toggleRecipes.blastable
+ gui.recipebook.toggleRecipes.smokable
+ stat.minecraft.open_barrel
+ subtitles.block.bell.use
+ subtitles.event.raid.horn
- subtitles.event.raid.horn_distant
- subtitles.event.raid.horn_local
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
+ recipes/decorations/barrel.json
+ recipes/decorations/blast_furnace.json
+ recipes/decorations/smoker.json
+ recipes/food/baked_potato_from_smoking.json
+ recipes/food/cooked_beef_from_smoking.json
+ recipes/food/cooked_chicken_from_smoking.json
+ recipes/food/cooked_cod_from_smoking.json
+ recipes/food/cooked_mutton_from_smoking.json
+ recipes/food/cooked_porkchop_from_smoking.json
+ recipes/food/cooked_rabbit_from_smoking.json
+ recipes/food/cooked_salmon_from_smoking.json
+ recipes/food/dried_kelp_from_smoking.json
+ recipes/misc/coal_from_blasting.json
+ recipes/misc/diamond_from_blasting.json
+ recipes/misc/emerald_from_blasting.json
+ recipes/misc/gold_ingot_from_blasting.json
+ recipes/misc/gold_nugget_from_blasting.json
+ recipes/misc/iron_ingot_from_blasting.json
+ recipes/misc/iron_nugget_from_blasting.json
+ recipes/misc/lapis_from_blasting.json
+ recipes/misc/quartz_from_blasting.json
+ recipes/redstone/redstone_from_blasting.json
```

</details>


<details><summary>loot_tables.txt</summary>

```diff
+ chests/village/village_fletcher.json
+ chests/village/village_temple.json
+ chests/village/village_toolsmith.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
+ baked_potato_from_smoking.json
+ barrel.json
+ blast_furnace.json
+ coal_from_blasting.json
+ cooked_beef_from_smoking.json
+ cooked_chicken_from_smoking.json
+ cooked_cod_from_smoking.json
+ cooked_mutton_from_smoking.json
+ cooked_porkchop_from_smoking.json
+ cooked_rabbit_from_smoking.json
+ cooked_salmon_from_smoking.json
+ diamond_from_blasting.json
+ dried_kelp_from_smoking.json
+ emerald_from_blasting.json
+ gold_ingot_from_blasting.json
+ gold_nugget_from_blasting.json
+ iron_ingot_from_blasting.json
+ iron_nugget_from_blasting.json
+ lapis_from_blasting.json
+ quartz_from_blasting.json
+ redstone_from_blasting.json
+ smoker.json
```

</details>


<details><summary>structures.txt</summary>

```diff
+ village/common/animals/cat_black.nbt
+ village/common/animals/cat_british.nbt
+ village/common/animals/cat_calico.nbt
+ village/common/animals/cat_jellie.nbt
+ village/common/animals/cat_persian.nbt
+ village/common/animals/cat_ragdoll.nbt
+ village/common/animals/cat_red.nbt
+ village/common/animals/cat_siamese.nbt
+ village/common/animals/cat_tabby.nbt
+ village/common/animals/cat_white.nbt
+ village/desert/desert_lamp_1.nbt
+ village/desert/houses/desert_animal_pen_1.nbt
+ village/desert/houses/desert_animal_pen_2.nbt
+ village/desert/houses/desert_armorer_1.nbt
+ village/desert/houses/desert_blacksmith_1.nbt
+ village/desert/houses/desert_butcher_shop_1.nbt
+ village/desert/houses/desert_cartographer_house_1.nbt
+ village/desert/houses/desert_farm_1.nbt
+ village/desert/houses/desert_farm_2.nbt
+ village/desert/houses/desert_fisher_1.nbt
+ village/desert/houses/desert_fletcher_house_1.nbt
+ village/desert/houses/desert_large_farm_1.nbt
+ village/desert/houses/desert_library_1.nbt
+ village/desert/houses/desert_mason_1.nbt
+ village/desert/houses/desert_medium_house_1.nbt
+ village/desert/houses/desert_medium_house_2.nbt
+ village/desert/houses/desert_sheperd_house_1.nbt
+ village/desert/houses/desert_shepherd_house_1.nbt
+ village/desert/houses/desert_small_house_1.nbt
+ village/desert/houses/desert_small_house_2.nbt
+ village/desert/houses/desert_small_house_3.nbt
+ village/desert/houses/desert_small_house_4.nbt
+ village/desert/houses/desert_small_house_5.nbt
+ village/desert/houses/desert_small_house_6.nbt
+ village/desert/houses/desert_small_house_7.nbt
+ village/desert/houses/desert_small_house_8.nbt
+ village/desert/houses/desert_tannery_1.nbt
+ village/desert/houses/desert_temple_1.nbt
+ village/desert/houses/desert_temple_2.nbt
+ village/desert/houses/desert_tool_smith_1.nbt
+ village/desert/houses/desert_weaponsmith_1.nbt
+ village/desert/streets/corner_01.nbt
+ village/desert/streets/corner_02.nbt
+ village/desert/streets/crossroad_01.nbt
+ village/desert/streets/crossroad_02.nbt
+ village/desert/streets/crossroad_03.nbt
+ village/desert/streets/square_01.nbt
+ village/desert/streets/square_02.nbt
+ village/desert/streets/straight_01.nbt
+ village/desert/streets/straight_02.nbt
+ village/desert/streets/straight_03.nbt
+ village/desert/streets/turn_01.nbt
+ village/desert/terminators/terminator_01.nbt
+ village/desert/terminators/terminator_02.nbt
+ village/desert/town_centers/desert_meeting_point_1.nbt
+ village/desert/town_centers/desert_meeting_point_2.nbt
+ village/desert/town_centers/desert_meeting_point_3.nbt
+ village/taiga/houses/taiga_animal_pen_1.nbt
+ village/taiga/houses/taiga_armorer_2.nbt
+ village/taiga/houses/taiga_armorer_house_1.nbt
+ village/taiga/houses/taiga_armorer_house_2.nbt
+ village/taiga/houses/taiga_butcher_shop_1.nbt
+ village/taiga/houses/taiga_cartographer_house_1.nbt
+ village/taiga/houses/taiga_decoration_1.nbt
+ village/taiga/houses/taiga_fisher_cottage_1.nbt
+ village/taiga/houses/taiga_fletcher_house_1.nbt
+ village/taiga/houses/taiga_lamp_post_1.nbt
+ village/taiga/houses/taiga_large_farm_1.nbt
+ village/taiga/houses/taiga_large_farm_2.nbt
+ village/taiga/houses/taiga_library_1.nbt
+ village/taiga/houses/taiga_masons_house_1.nbt
+ village/taiga/houses/taiga_medium_house_1.nbt
+ village/taiga/houses/taiga_medium_house_2.nbt
+ village/taiga/houses/taiga_medium_house_3.nbt
+ village/taiga/houses/taiga_meeting_point_1.nbt
+ village/taiga/houses/taiga_sheperds_house_1.nbt
+ village/taiga/houses/taiga_shepherds_house_1.nbt
+ village/taiga/houses/taiga_small_farm_1.nbt
+ village/taiga/houses/taiga_small_house_1.nbt
+ village/taiga/houses/taiga_small_house_2.nbt
+ village/taiga/houses/taiga_small_house_3.nbt
+ village/taiga/houses/taiga_small_house_4.nbt
+ village/taiga/houses/taiga_small_house_5.nbt
+ village/taiga/houses/taiga_tannery_1.nbt
+ village/taiga/houses/taiga_temple_1.nbt
+ village/taiga/houses/taiga_tool_smith_1.nbt
+ village/taiga/houses/taiga_weapon_smith_1.nbt
+ village/taiga/houses/taiga_weaponsmith_1.nbt
+ village/taiga/houses/taiga_weaponsmith_2.nbt
+ village/taiga/streets/corner_01.nbt
+ village/taiga/streets/corner_02.nbt
+ village/taiga/streets/corner_03.nbt
+ village/taiga/streets/crossroad_01.nbt
+ village/taiga/streets/crossroad_02.nbt
+ village/taiga/streets/crossroad_03.nbt
+ village/taiga/streets/crossroad_04.nbt
+ village/taiga/streets/crossroad_05.nbt
+ village/taiga/streets/crossroad_06.nbt
+ village/taiga/streets/straight_01.nbt
+ village/taiga/streets/straight_02.nbt
+ village/taiga/streets/straight_03.nbt
+ village/taiga/streets/straight_04.nbt
+ village/taiga/streets/straight_05.nbt
+ village/taiga/streets/straight_06.nbt
+ village/taiga/streets/turn_01.nbt
+ village/taiga/taiga_decoration_1.nbt
+ village/taiga/taiga_decoration_2.nbt
+ village/taiga/taiga_decoration_3.nbt
+ village/taiga/taiga_decoration_4.nbt
+ village/taiga/taiga_lamp_post_1.nbt
+ village/taiga/town_centers/taiga_meeting_point_1.nbt
+ village/taiga/town_centers/taiga_meeting_point_2.nbt
```

</details>


<details><summary>textures.txt</summary>

```diff
+ entity/bell/bell_body.png
+ entity/cat/jellie.png
- entity/villager/butcher.png
- entity/villager/farmer.png
- entity/villager/librarian.png
- entity/villager/priest.png
+ entity/villager/profession_level/diamond.png
+ entity/villager/profession_level/emerald.png
+ entity/villager/profession_level/gold.png
+ entity/villager/profession_level/iron.png
+ entity/villager/profession_level/stone.png
+ entity/villager/profession/armorer.png
+ entity/villager/profession/butcher.png
+ entity/villager/profession/cartographer.png
+ entity/villager/profession/cleric.png
+ entity/villager/profession/farmer.png
+ entity/villager/profession/fisherman.png
+ entity/villager/profession/fletcher.png
+ entity/villager/profession/leatherworker.png
+ entity/villager/profession/librarian.png
+ entity/villager/profession/mason.png
+ entity/villager/profession/nitwit.png
+ entity/villager/profession/shepherd.png
+ entity/villager/profession/toolsmith.png
+ entity/villager/profession/weaponsmith.png
- entity/villager/smith.png
+ entity/villager/type/desert.png
+ entity/villager/type/jungle.png
+ entity/villager/type/plains.png
+ entity/villager/type/savanna.png
+ entity/villager/type/snow.png
+ entity/villager/type/swamp.png
+ entity/villager/type/taiga.png
+ entity/zombie_villager/profession_level/diamond.png
+ entity/zombie_villager/profession_level/emerald.png
+ entity/zombie_villager/profession_level/gold.png
+ entity/zombie_villager/profession_level/iron.png
+ entity/zombie_villager/profession_level/stone.png
+ entity/zombie_villager/profession/armorer.png
+ entity/zombie_villager/profession/butcher.png
+ entity/zombie_villager/profession/cartographer.png
+ entity/zombie_villager/profession/cleric.png
+ entity/zombie_villager/profession/farmer.png
+ entity/zombie_villager/profession/fisherman.png
+ entity/zombie_villager/profession/fletcher.png
+ entity/zombie_villager/profession/leatherworker.png
+ entity/zombie_villager/profession/librarian.png
+ entity/zombie_villager/profession/mason.png
+ entity/zombie_villager/profession/nitwit.png
+ entity/zombie_villager/profession/shepherd.png
+ entity/zombie_villager/profession/toolsmith.png
+ entity/zombie_villager/profession/weaponsmith.png
+ entity/zombie_villager/type/desert.png
+ entity/zombie_villager/type/jungle.png
+ entity/zombie_villager/type/plains.png
+ entity/zombie_villager/type/savanna.png
+ entity/zombie_villager/type/snow.png
+ entity/zombie_villager/type/swamp.png
+ entity/zombie_villager/type/taiga.png
- entity/zombie_villager/zombie_butcher.png
- entity/zombie_villager/zombie_farmer.png
- entity/zombie_villager/zombie_librarian.png
- entity/zombie_villager/zombie_priest.png
- entity/zombie_villager/zombie_smith.png
+ gui/container/blast_furnace.png
+ gui/container/smoker.png
```

</details>
