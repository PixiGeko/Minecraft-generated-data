## Comparison with [18w49a](https://github.com/PixiGeko/Minecraft-generated-data/tree/18w49a)

> [!TIP]
> - [Version data](#version-data)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">18w49a</th><th>18w50a</th></tr><tr><td>World version</td><td><pre>1916</pre></td><td><pre>1919</pre></td></tr><tr><td>Protocol version</td><td><pre>450</pre></td><td><pre>451</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

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
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ entity.minecraft.villager.mason: Mason
- entity.minecraft.villager.tool_smith: Tool Smith
+ entity.minecraft.villager.toolsmith: Toolsmith
- entity.minecraft.villager.weapon_smith: Weapon Smith
+ entity.minecraft.villager.weaponsmith: Weaponsmith
+ gui.recipebook.toggleRecipes.blastable: Showing blastable
+ gui.recipebook.toggleRecipes.smokable: Showing smokable
+ stat.minecraft.open_barrel: Barrels Opened
+ subtitles.block.bell.use: Bell rings
- subtitles.event.raid.horn_distant: Ominous horn echos far away
- subtitles.event.raid.horn_local: Ominous horn blares
+ subtitles.event.raid.horn: Ominous horn blares
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>18w49a</th><th>18w50a</th></tr>
<tr><th align="left"><div style="width:290px">container.blast_furnace</div></th><td>blast_furnace</td><td>Blast Furnace</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
- reports/items.json
+ reports/registries.json
```

</details>
<details>
<summary>
data
</summary>

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
<details>
<summary>
assets
</summary>

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
</details>
<hr/>