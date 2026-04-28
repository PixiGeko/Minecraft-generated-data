## Comparison with [26.2-snapshot-4](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-4)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-4</th><th>26.2-snapshot-5</th></tr><tr><td>DataPack version</td><td><pre>103.0</pre></td><td><pre>104.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>86.1</pre></td><td><pre>86.2</pre></td></tr><tr><td>World version</td><td><pre>4887</pre></td><td><pre>4889</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742134</pre></td><td><pre>1073742135</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:name_tag_distance
- minecraft:nameplate_distance
```

</details>
<details>
<summary>
block_predicate_type
</summary>

```diff
+ minecraft:matching_biomes
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
- minecraft:color
+ minecraft:team_color
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:geyser
+ minecraft:geyser_base
+ minecraft:geyser_plume
+ minecraft:geyser_poof
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.potent_sulfur.geyser_eruption
+ minecraft:block.potent_sulfur.geyser_eruption_active
+ minecraft:block.sulfur_spike.break
+ minecraft:block.sulfur_spike.fall
+ minecraft:block.sulfur_spike.hit
+ minecraft:block.sulfur_spike.land
+ minecraft:block.sulfur_spike.place
+ minecraft:block.sulfur_spike.step
```

</details>
<details>
<summary>
test_environment_definition_type
</summary>

```diff
+ minecraft:difficulty
```

</details>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
+ minecraft:interval_select
- minecraft:weird_scaled_sampler
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:name_tag_distance
- minecraft:nameplate_distance
```

</details>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:matching_biomes
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
- minecraft:color
+ minecraft:team_color
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:geyser
+ minecraft:geyser_base
+ minecraft:geyser_plume
+ minecraft:geyser_poof
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.potent_sulfur.geyser_eruption
+ minecraft:block.potent_sulfur.geyser_eruption_active
+ minecraft:block.sulfur_spike.break
+ minecraft:block.sulfur_spike.fall
+ minecraft:block.sulfur_spike.hit
+ minecraft:block.sulfur_spike.land
+ minecraft:block.sulfur_spike.place
+ minecraft:block.sulfur_spike.step
```

</details>
<details>
<summary>
universal_tags/test_environment_definition_type.json
</summary>

```diff
+ minecraft:difficulty
```

</details>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
+ minecraft:interval_select
- minecraft:weird_scaled_sampler
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
- team modify <team: team> color <value: color>
+ team modify <team: team> color <value: team_color>
+ team modify <team: team> color reset
```

</details>
<details>
<summary>
waypoint
</summary>

```diff
- waypoint modify <waypoint: entity> color <color: color>
+ waypoint modify <waypoint: entity> color <color: team_color>
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
acacia_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
acacia_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
acacia_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
acacia_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
acacia_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
acacia_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
activator_rail.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
andesite_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
anvil.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
armor_stand.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_chest_raft.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_mosaic.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_raft.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bamboo_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
barrel.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
beacon.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
beehive.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
beetroot_soup.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
birch_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blackstone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_dye_from_wither_rose.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
black_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blast_furnace.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blaze_powder.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_dye_from_cornflower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
blue_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bolt_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bone_meal.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bone_meal_from_bone_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
book.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bordure_indented_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bowl.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bread.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brewing_stand.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
brown_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
bucket.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cake.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
campfire.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
carrot_on_a_stick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cartography_table.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cauldron.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
charcoal.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cherry_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
chest.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
chest_minecart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cinnabar_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cinnabar_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coal.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coal_from_blasting_coal_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coal_from_blasting_deepslate_coal_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coal_from_smelting_coal_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coal_from_smelting_deepslate_coal_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
coast_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cobbled_deepslate_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cobblestone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
composter.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
conduit.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cookie.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_bars.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_chain.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_chest.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_blasting_copper_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_blasting_deepslate_copper_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_blasting_raw_copper.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_nuggets.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_smelting_copper_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_smelting_deepslate_copper_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_smelting_raw_copper.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_ingot_from_waxed_copper_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_lantern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_nugget.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_nugget_from_blasting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_nugget_from_smelting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
copper_torch.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
crafting_table.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
creaking_heart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
creeper_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
crimson_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
crimson_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
crimson_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
crimson_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_dye_from_pitcher_plant.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
cyan_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dark_oak_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
decorated_pot_simple.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
deepslate_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
deepslate_tile_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
detector_rail.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diamond.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diamond_from_blasting_deepslate_diamond_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diamond_from_blasting_diamond_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diamond_from_smelting_deepslate_diamond_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diamond_from_smelting_diamond_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
diorite_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dried_kelp.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dune_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_black_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_black_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_blue_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_blue_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_brown_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_brown_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_cyan_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_cyan_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_gray_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_gray_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_green_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_green_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_light_blue_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_light_blue_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_light_gray_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_light_gray_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_lime_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_lime_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_magenta_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_magenta_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_orange_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_orange_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_pink_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_pink_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_purple_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_purple_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_red_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_red_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_white_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_white_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_yellow_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
dye_yellow_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
emerald.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
emerald_from_blasting_deepslate_emerald_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
emerald_from_blasting_emerald_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
emerald_from_smelting_deepslate_emerald_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
emerald_from_smelting_emerald_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
enchanting_table.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
ender_chest.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
ender_eye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
end_crystal.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
end_rod.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
end_stone_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
eye_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
fermented_spider_eye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
field_masoned_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
firework_rocket_simple.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
fire_charge.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
fletching_table.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
flower_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
flower_pot.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
flow_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
furnace.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
furnace_minecart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
glass_bottle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
glistering_melon_slice.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
glow_item_frame.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
golden_apple.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
golden_carrot.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
golden_dandelion.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_blasting_deepslate_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_blasting_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_blasting_nether_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_blasting_raw_gold.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_gold_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_nuggets.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_smelting_deepslate_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_smelting_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_smelting_nether_gold_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_ingot_from_smelting_raw_gold.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_nugget.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_nugget_from_blasting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gold_nugget_from_smelting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
granite_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_dye_from_closed_eyeblossom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
gray_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
green_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
grindstone.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
honeycomb_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
honey_bottle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
hopper_minecart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
host_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_bars.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_chain.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_blasting_deepslate_iron_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_blasting_iron_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_blasting_raw_iron.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_iron_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_nuggets.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_smelting_deepslate_iron_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_smelting_iron_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_ingot_from_smelting_raw_iron.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_nugget.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_nugget_from_blasting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
iron_nugget_from_smelting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
item_frame.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jukebox.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
jungle_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
ladder.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lantern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lapis_lazuli.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_deepslate_lapis_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lapis_lazuli_from_blasting_lapis_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_deepslate_lapis_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lapis_lazuli_from_smelting_lapis_ore.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_boots_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_chestplate_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_helmet_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_horse_armor.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_horse_armor_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
leather_leggings_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_dye_from_blue_orchid.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_dye_from_blue_white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_blue_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_dye_from_azure_bluet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_dye_from_black_white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_dye_from_gray_white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_dye_from_oxeye_daisy.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_dye_from_white_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
light_gray_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_dye_from_smelting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lime_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
lodestone.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
loom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_dye_from_allium.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_dye_from_blue_red_pink.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_dye_from_blue_red_white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_dye_from_lilac.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_dye_from_purple_and_pink.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magenta_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
magma_cream.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mangrove_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
map.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
map_cloning.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
melon_seeds.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
minecart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mojang_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mossy_cobblestone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mossy_stone_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
moss_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mud_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
mushroom_stew.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
music_disc_5.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
netherite_ingot.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
netherite_ingot_from_netherite_block.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
netherite_scrap.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
netherite_scrap_from_blasting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
netherite_upgrade_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
nether_brick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
nether_brick_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
nether_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
oak_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_dye_from_open_eyeblossom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_dye_from_orange_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_dye_from_red_yellow.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_dye_from_torchflower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
orange_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
painting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_moss_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pale_oak_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
paper.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_dye_from_cactus_flower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_dye_from_peony.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_dye_from_pink_petals.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_dye_from_pink_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_dye_from_red_white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pink_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_blackstone_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_blackstone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_cinnabar_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_deepslate_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_sulfur_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
polished_tuff_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
popped_chorus_fruit.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
powered_rail.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
prismarine_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pumpkin_pie.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
pumpkin_seeds.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
purple_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
quartz.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
quartz_from_blasting.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
rabbit_stew_from_brown_mushroom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
rabbit_stew_from_red_mushroom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
rail.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
raiser_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
raw_copper.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
raw_gold.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
raw_iron.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_dye_from_beetroot.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_dye_from_poppy.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_dye_from_rose_bush.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_dye_from_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_nether_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_sandstone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
red_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
resin_brick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
resin_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
resin_clump.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
respawn_anchor.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
rib_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sandstone_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
scaffolding.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sentry_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
shaper_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
silence_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
skull_banner_pattern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
slime_ball.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
smithing_table.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
smoker.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
snout_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
snow.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
soul_campfire.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
soul_lantern.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
soul_torch.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spire_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_chest_boat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
spruce_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
stick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
stick_from_bamboo_item.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
stonecutter.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
stone_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sugar_from_honey_bottle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sugar_from_sugar_cane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sulfur_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
sulfur_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_allium.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_azure_bluet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_blue_orchid.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_closed_eyeblossom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_cornflower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_dandelion.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_golden_dandelion.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_lily_of_the_valley.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_open_eyeblossom.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_orange_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_oxeye_daisy.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_pink_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_poppy.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_red_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_torchflower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_white_tulip.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
suspicious_stew_from_wither_rose.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
tide_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
tipped_arrow.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
tnt_minecart.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
torch.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
tuff_brick_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
tuff_wall.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
vex_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
ward_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
warped_fence.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
warped_fungus_on_a_stick.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
warped_hanging_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
warped_shelf.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
warped_sign.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
wayfinder_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
wheat.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_dye.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_dye_from_lily_of_the_valley.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
white_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
wild_armor_trim_smithing_template.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
wind_charge.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
wolf_armor_dyed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
writable_book.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_banner.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_bed.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_candle.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_carpet.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_dye_from_dandelion.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_dye_from_golden_dandelion.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_dye_from_sunflower.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_dye_from_wildflowers.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_shulker_box.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_stained_glass_pane.json
</summary>

```
Category: misc -> none
```

</details>
<details>
<summary>
yellow_stained_glass_pane_from_glass_pane.json
</summary>

```
Category: misc -> none
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
+ commands.team.option.color.clear.success: Cleared the color for team %s
+ subtitles.block.potent_sulfur.geyser_eruption: Sulfur spring bursts
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.2-snapshot-4</th><th>26.2-snapshot-5</th></tr>
<tr><th align="left"><div style="width:290px">attribute.name.below_name_distance</div></th><td>Nameplate Score Distance</td><td>Name Tag Score Distance</td></tr>
<tr><th align="left"><div style="width:290px">attribute.name.nameplate_distance</div></th><td>Nameplate Distance</td><td>Name Tag Distance</td></tr>
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
+ minecraft/sulfur_cube_archetype/explosive.json
+ minecraft/tags/block/default_immune_to.json
+ minecraft/tags/block/fox_immune_to.json
+ minecraft/tags/block/polar_bear_immune_to.json
+ minecraft/tags/block/snow_golem_immune_to.json
+ minecraft/tags/block/stray_immune_to.json
+ minecraft/tags/block/wither_immune_to.json
+ minecraft/tags/block/wither_skeleton_immune_to.json
+ minecraft/tags/item/sulfur_cube_archetype/explosive.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/particles/geyser_base.json
+ minecraft/particles/geyser_plume.json
+ minecraft/particles/geyser_poof.json
+ minecraft/textures/particle/geyser_base_01.png
+ minecraft/textures/particle/geyser_base_02.png
+ minecraft/textures/particle/geyser_base_03.png
+ minecraft/textures/particle/geyser_base_04.png
+ minecraft/textures/particle/geyser_base_05.png
+ minecraft/textures/particle/geyser_base_06.png
+ minecraft/textures/particle/geyser_base_07.png
+ minecraft/textures/particle/geyser_base_08.png
+ minecraft/textures/particle/geyser_plume_01.png
+ minecraft/textures/particle/geyser_plume_02.png
+ minecraft/textures/particle/geyser_plume_03.png
+ minecraft/textures/particle/geyser_plume_04.png
+ minecraft/textures/particle/geyser_plume_05.png
+ minecraft/textures/particle/geyser_plume_06.png
+ minecraft/textures/particle/geyser_plume_07.png
+ minecraft/textures/particle/geyser_plume_08.png
+ minecraft/textures/particle/geyser_poof_01.png
+ minecraft/textures/particle/geyser_poof_02.png
+ minecraft/textures/particle/geyser_poof_03.png
+ minecraft/textures/particle/geyser_poof_04.png
+ minecraft/textures/particle/geyser_poof_05.png
+ minecraft/textures/particle/geyser_poof_06.png
+ minecraft/textures/particle/geyser_poof_07.png
+ minecraft/textures/particle/geyser_poof_08.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
- minecraft:color
+ minecraft:team_color
```

</details>
</details>
<hr/>