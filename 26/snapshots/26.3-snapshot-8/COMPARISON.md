## Comparison with [26.3-snapshot-7](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-7)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-7</th><th>26.3-snapshot-8</th></tr><tr><td>DataPack version</td><td><pre>115.0</pre></td><td><pre>116.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>95.0</pre></td><td><pre>96.0</pre></td></tr><tr><td>World version</td><td><pre>5009</pre></td><td><pre>5010</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742153</pre></td><td><pre>1073742154</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block_predicate_type
</summary>

```diff
+ minecraft:volume_match
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:abandoned_camp_map
- minecraft:abandoned_campsite_map
- minecraft:ancient_city_map
+ minecraft:buried_ancient_city_map
+ minecraft:buried_mineshaft_map
- minecraft:mineshaft_map
```

</details>
<details>
<summary>
worldgen/feature_type
</summary>

```diff
- minecraft:desert_well
```

</details>
<details>
<summary>
worldgen/placement_modifier_type
</summary>

```diff
+ minecraft:randomly_selected
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:volume_match
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:abandoned_camp_map
- minecraft:abandoned_campsite_map
- minecraft:ancient_city_map
+ minecraft:buried_ancient_city_map
+ minecraft:buried_mineshaft_map
- minecraft:mineshaft_map
```

</details>
<details>
<summary>
universal_tags/worldgen/feature_type.json
</summary>

```diff
- minecraft:desert_well
```

</details>
<details>
<summary>
universal_tags/worldgen/placement_modifier_type.json
</summary>

```diff
+ minecraft:randomly_selected
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
+ black_concrete_slab_from_black_concrete_stonecutting.json
+ black_concrete_stairs_from_black_concrete_stonecutting.json
+ blue_concrete_slab_from_blue_concrete_stonecutting.json
+ blue_concrete_stairs_from_blue_concrete_stonecutting.json
+ brown_concrete_slab_from_brown_concrete_stonecutting.json
+ brown_concrete_stairs_from_brown_concrete_stonecutting.json
+ cyan_concrete_slab_from_cyan_concrete_stonecutting.json
+ cyan_concrete_stairs_from_cyan_concrete_stonecutting.json
+ gray_concrete_slab_from_gray_concrete_stonecutting.json
+ gray_concrete_stairs_from_gray_concrete_stonecutting.json
+ green_concrete_slab_from_green_concrete_stonecutting.json
+ green_concrete_stairs_from_green_concrete_stonecutting.json
+ light_blue_concrete_slab_from_light_blue_concrete_stonecutting.json
+ light_blue_concrete_stairs_from_light_blue_concrete_stonecutting.json
+ light_gray_concrete_slab_from_light_gray_concrete_stonecutting.json
+ light_gray_concrete_stairs_from_light_gray_concrete_stonecutting.json
+ lime_concrete_slab_from_lime_concrete_stonecutting.json
+ lime_concrete_stairs_from_lime_concrete_stonecutting.json
+ magenta_concrete_slab_from_magenta_concrete_stonecutting.json
+ magenta_concrete_stairs_from_magenta_concrete_stonecutting.json
+ orange_concrete_slab_from_orange_concrete_stonecutting.json
+ orange_concrete_stairs_from_orange_concrete_stonecutting.json
+ pink_concrete_slab_from_pink_concrete_stonecutting.json
+ pink_concrete_stairs_from_pink_concrete_stonecutting.json
+ purple_concrete_slab_from_purple_concrete_stonecutting.json
+ purple_concrete_stairs_from_purple_concrete_stonecutting.json
+ red_concrete_slab_from_red_concrete_stonecutting.json
+ red_concrete_stairs_from_red_concrete_stonecutting.json
+ white_concrete_slab_from_white_concrete_stonecutting.json
+ white_concrete_stairs_from_white_concrete_stonecutting.json
+ yellow_concrete_slab_from_yellow_concrete_stonecutting.json
+ yellow_concrete_stairs_from_yellow_concrete_stonecutting.json
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
+ filled_map.bamboo_camp_map: Bamboo Camp Map
- filled_map.bamboo_jungle_abandoned_camp: Bamboo Jungle Abandoned Camp Map
- filled_map.birch_forest_abandoned_camp: Birch Forest Abandoned Camp Map
+ filled_map.birch_forest_camp_map: Birch Forest Camp Map
- filled_map.cherry_grove_abandoned_camp: Cherry Grove Abandoned Camp Map
+ filled_map.cherry_grove_camp_map: Cherry Grove Camp Map
- filled_map.dappled_forest_abandoned_camp: Dappled Forest Abandoned Camp Map
+ filled_map.dappled_forest_camp_map: Dappled Forest Camp Map
- filled_map.flower_forest_abandoned_camp: Flower Forest Abandoned Camp Map
+ filled_map.flower_forest_camp_map: Flower Forest Camp Map
- filled_map.pale_garden_abandoned_camp: Pale Garden Abandoned Camp Map
+ filled_map.pale_garden_camp_map: Pale Garden Camp Map
- filled_map.swamp_abandoned_camp: Swamp Abandoned Camp Map
+ filled_map.swamp_camp_map: Swamp Camp Map
- filled_map.windswept_forest_abandoned_camp: Windswept Forest Abandoned Camp Map
+ filled_map.windswept_forest_camp_map: Windswept Forest Camp Map
+ item.minecraft.abandoned_camp_map: Abandoned Camp Map
- item.minecraft.abandoned_campsite_map: Abandoned Campsite Map
- item.minecraft.ancient_city_map: Ancient City Map
+ item.minecraft.buried_ancient_city_map: Buried Ancient City Map
+ item.minecraft.buried_mineshaft_map: Buried Mineshaft Map
- item.minecraft.mineshaft_map: Mineshaft Map
+ mco.configure.world.buttons.invite_codes: Invite Codes
+ mco.configure.world.invite_codes.copy: Copy
+ mco.configure.world.invite_codes.create: Create Invite Code
+ mco.configure.world.invite_codes.delete: Delete
+ mco.configure.world.invite_codes.edit: Edit
+ mco.configure.world.invite_codes.edit.active: Active
+ mco.configure.world.invite_codes.edit.expiration_date: Expiration Date
+ mco.configure.world.invite_codes.edit.expires: Expires: %s
+ mco.configure.world.invite_codes.edit.title: Edit Invite Code
+ mco.configure.world.invite_codes.expiration.1_day: 1 day
+ mco.configure.world.invite_codes.expiration.1_hour: 1 hour
+ mco.configure.world.invite_codes.expiration.12_hours: 12 hours
+ mco.configure.world.invite_codes.expiration.30_minutes: 30 minutes
+ mco.configure.world.invite_codes.expiration.6_hours: 6 hours
+ mco.configure.world.invite_codes.expiration.7_days: 7 days
+ mco.configure.world.invite_codes.expiration.never: Never
+ mco.configure.world.invite_codes.loading: Loading invite codes
+ mco.configure.world.invite_codes.subtitle: You can add up to %s invite codes and share them so people can join your Realm
+ mco.configure.world.invite_codes.title: Invite Codes (%s/%s)
+ mco.selectServer.joinCode: Join Code
+ mco.selectServer.joinCode.hint: Enter join code
+ mco.selectServer.joinCode.invalid: The code you entered is invalid.
+ mco.selectServer.joinCode.title: Enter Join Code
+ mco.selectServer.joinCode.validating: Validating code
+ mco.selectServer.joinRealm: Join Realm
+ options.worldOptions.allow_commands.tooltip: Allows the use of commands in this world.
+ options.worldOptions.game_mode: Default Game Mode
+ options.worldOptions.game_mode.tooltip: Changes the default game mode of the world.
+ options.worldOptions.guest.force_game_mode: Force Game Mode
+ options.worldOptions.guest.force_game_mode.off.commands.tooltip: Other players can set their own game mode through commands.
+ options.worldOptions.guest.force_game_mode.off.tooltip: Other players will retain their current game mode regardless of the world's default game mode.
+ options.worldOptions.guest.force_game_mode.on.tooltip: Other players will be forced to play the world's default game mode.
+ options.worldOptions.personal_game_mode: Personal Game Mode
+ options.worldOptions.personal_game_mode.tooltip: Changes your game mode in this world.
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3-snapshot-7</th><th>26.3-snapshot-8</th></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.jungle_explorer_map</div></th><td>Jungle Pyramid Explorer Map</td><td>Jungle Explorer Map</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.ocean_explorer_map</div></th><td>Ocean Monument Explorer Map</td><td>Ocean Explorer Map</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.swamp_explorer_map</div></th><td>Swamp Hut Explorer Map</td><td>Swamp Explorer Map</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.trial_explorer_map</div></th><td>Trial Chambers Explorer Map</td><td>Trial Explorer Map</td></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.woodland_explorer_map</div></th><td>Woodland Mansion Explorer Map</td><td>Woodland Explorer Map</td></tr>
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
+ reports/minecraft/components/item/abandoned_camp_map.json
- reports/minecraft/components/item/abandoned_campsite_map.json
- reports/minecraft/components/item/ancient_city_map.json
+ reports/minecraft/components/item/buried_ancient_city_map.json
+ reports/minecraft/components/item/buried_mineshaft_map.json
- reports/minecraft/components/item/mineshaft_map.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/black_concrete_slab_from_black_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/black_concrete_stairs_from_black_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/blue_concrete_slab_from_blue_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/blue_concrete_stairs_from_blue_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/brown_concrete_slab_from_brown_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/brown_concrete_stairs_from_brown_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cyan_concrete_slab_from_cyan_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cyan_concrete_stairs_from_cyan_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/gray_concrete_slab_from_gray_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/gray_concrete_stairs_from_gray_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/green_concrete_slab_from_green_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/green_concrete_stairs_from_green_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/light_blue_concrete_slab_from_light_blue_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/light_blue_concrete_stairs_from_light_blue_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/light_gray_concrete_slab_from_light_gray_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/light_gray_concrete_stairs_from_light_gray_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/lime_concrete_slab_from_lime_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/lime_concrete_stairs_from_lime_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/magenta_concrete_slab_from_magenta_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/magenta_concrete_stairs_from_magenta_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/orange_concrete_slab_from_orange_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/orange_concrete_stairs_from_orange_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/pink_concrete_slab_from_pink_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/pink_concrete_stairs_from_pink_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/purple_concrete_slab_from_purple_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/purple_concrete_stairs_from_purple_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/red_concrete_slab_from_red_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/red_concrete_stairs_from_red_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/white_concrete_slab_from_white_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/white_concrete_stairs_from_white_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/yellow_concrete_slab_from_yellow_concrete_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/yellow_concrete_stairs_from_yellow_concrete_stonecutting.json
+ minecraft/recipe/black_concrete_slab_from_black_concrete_stonecutting.json
+ minecraft/recipe/black_concrete_stairs_from_black_concrete_stonecutting.json
+ minecraft/recipe/blue_concrete_slab_from_blue_concrete_stonecutting.json
+ minecraft/recipe/blue_concrete_stairs_from_blue_concrete_stonecutting.json
+ minecraft/recipe/brown_concrete_slab_from_brown_concrete_stonecutting.json
+ minecraft/recipe/brown_concrete_stairs_from_brown_concrete_stonecutting.json
+ minecraft/recipe/cyan_concrete_slab_from_cyan_concrete_stonecutting.json
+ minecraft/recipe/cyan_concrete_stairs_from_cyan_concrete_stonecutting.json
+ minecraft/recipe/gray_concrete_slab_from_gray_concrete_stonecutting.json
+ minecraft/recipe/gray_concrete_stairs_from_gray_concrete_stonecutting.json
+ minecraft/recipe/green_concrete_slab_from_green_concrete_stonecutting.json
+ minecraft/recipe/green_concrete_stairs_from_green_concrete_stonecutting.json
+ minecraft/recipe/light_blue_concrete_slab_from_light_blue_concrete_stonecutting.json
+ minecraft/recipe/light_blue_concrete_stairs_from_light_blue_concrete_stonecutting.json
+ minecraft/recipe/light_gray_concrete_slab_from_light_gray_concrete_stonecutting.json
+ minecraft/recipe/light_gray_concrete_stairs_from_light_gray_concrete_stonecutting.json
+ minecraft/recipe/lime_concrete_slab_from_lime_concrete_stonecutting.json
+ minecraft/recipe/lime_concrete_stairs_from_lime_concrete_stonecutting.json
+ minecraft/recipe/magenta_concrete_slab_from_magenta_concrete_stonecutting.json
+ minecraft/recipe/magenta_concrete_stairs_from_magenta_concrete_stonecutting.json
+ minecraft/recipe/orange_concrete_slab_from_orange_concrete_stonecutting.json
+ minecraft/recipe/orange_concrete_stairs_from_orange_concrete_stonecutting.json
+ minecraft/recipe/pink_concrete_slab_from_pink_concrete_stonecutting.json
+ minecraft/recipe/pink_concrete_stairs_from_pink_concrete_stonecutting.json
+ minecraft/recipe/purple_concrete_slab_from_purple_concrete_stonecutting.json
+ minecraft/recipe/purple_concrete_stairs_from_purple_concrete_stonecutting.json
+ minecraft/recipe/red_concrete_slab_from_red_concrete_stonecutting.json
+ minecraft/recipe/red_concrete_stairs_from_red_concrete_stonecutting.json
+ minecraft/recipe/white_concrete_slab_from_white_concrete_stonecutting.json
+ minecraft/recipe/white_concrete_stairs_from_white_concrete_stonecutting.json
+ minecraft/recipe/yellow_concrete_slab_from_yellow_concrete_stonecutting.json
+ minecraft/recipe/yellow_concrete_stairs_from_yellow_concrete_stonecutting.json
+ minecraft/structure/desert_well/suspicious_sand.nbt
+ minecraft/structure/desert_well/well.nbt
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/items/abandoned_camp_map.json
- minecraft/items/abandoned_campsite_map.json
- minecraft/items/ancient_city_map.json
+ minecraft/items/buried_ancient_city_map.json
+ minecraft/items/buried_mineshaft_map.json
- minecraft/items/mineshaft_map.json
+ minecraft/models/item/abandoned_camp_map.json
- minecraft/models/item/abandoned_campsite_map.json
- minecraft/models/item/ancient_city_map.json
+ minecraft/models/item/buried_ancient_city_map.json
+ minecraft/models/item/buried_mineshaft_map.json
- minecraft/models/item/mineshaft_map.json
- minecraft/shaders/core/text_background.fsh
- minecraft/shaders/core/text_background.vsh
+ minecraft/textures/block/orange_poplar_leaves.png.mcmeta
+ minecraft/textures/block/red_poplar_leaves.png.mcmeta
+ minecraft/textures/block/yellow_poplar_leaves.png.mcmeta
+ minecraft/textures/item/abandoned_camp_map.png
- minecraft/textures/item/abandoned_campsite_map.png
- minecraft/textures/item/ancient_city_map.png
+ minecraft/textures/item/buried_ancient_city_map.png
+ minecraft/textures/item/buried_mineshaft_map.png
- minecraft/textures/item/mineshaft_map.png
```

</details>
</details>
<hr/>