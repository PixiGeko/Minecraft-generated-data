## Comparison with [26.3-snapshot-6](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-6)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-6</th><th>26.3-snapshot-7</th></tr><tr><td>DataPack version</td><td><pre>113.0</pre></td><td><pre>115.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>94.0</pre></td><td><pre>95.0</pre></td></tr><tr><td>World version</td><td><pre>5005</pre></td><td><pre>5009</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742152</pre></td><td><pre>1073742153</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:black_concrete_slab
+ minecraft:black_concrete_stairs
+ minecraft:blue_concrete_slab
+ minecraft:blue_concrete_stairs
+ minecraft:brown_concrete_slab
+ minecraft:brown_concrete_stairs
+ minecraft:cyan_concrete_slab
+ minecraft:cyan_concrete_stairs
+ minecraft:gray_concrete_slab
+ minecraft:gray_concrete_stairs
+ minecraft:green_concrete_slab
+ minecraft:green_concrete_stairs
+ minecraft:light_blue_concrete_slab
+ minecraft:light_blue_concrete_stairs
+ minecraft:light_gray_concrete_slab
+ minecraft:light_gray_concrete_stairs
+ minecraft:lime_concrete_slab
+ minecraft:lime_concrete_stairs
+ minecraft:magenta_concrete_slab
+ minecraft:magenta_concrete_stairs
+ minecraft:orange_concrete_slab
+ minecraft:orange_concrete_stairs
+ minecraft:pink_concrete_slab
+ minecraft:pink_concrete_stairs
+ minecraft:purple_concrete_slab
+ minecraft:purple_concrete_stairs
+ minecraft:red_concrete_slab
+ minecraft:red_concrete_stairs
+ minecraft:white_concrete_slab
+ minecraft:white_concrete_stairs
+ minecraft:yellow_concrete_slab
+ minecraft:yellow_concrete_stairs
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:swing_animation
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:attack_animation
+ minecraft:interact_animation
- minecraft:map_color
- minecraft:swing_animation
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:abandoned_campsite_map
+ minecraft:ancient_city_map
+ minecraft:black_concrete_slab
+ minecraft:black_concrete_stairs
+ minecraft:blue_concrete_slab
+ minecraft:blue_concrete_stairs
+ minecraft:brown_concrete_slab
+ minecraft:brown_concrete_stairs
+ minecraft:buried_treasure_map
+ minecraft:cyan_concrete_slab
+ minecraft:cyan_concrete_stairs
+ minecraft:desert_pyramid_map
+ minecraft:desert_village_map
+ minecraft:gray_concrete_slab
+ minecraft:gray_concrete_stairs
+ minecraft:green_concrete_slab
+ minecraft:green_concrete_stairs
+ minecraft:jungle_explorer_map
+ minecraft:light_blue_concrete_slab
+ minecraft:light_blue_concrete_stairs
+ minecraft:light_gray_concrete_slab
+ minecraft:light_gray_concrete_stairs
+ minecraft:lime_concrete_slab
+ minecraft:lime_concrete_stairs
+ minecraft:magenta_concrete_slab
+ minecraft:magenta_concrete_stairs
+ minecraft:mineshaft_map
+ minecraft:ocean_explorer_map
+ minecraft:orange_concrete_slab
+ minecraft:orange_concrete_stairs
+ minecraft:pink_concrete_slab
+ minecraft:pink_concrete_stairs
+ minecraft:plains_village_map
+ minecraft:purple_concrete_slab
+ minecraft:purple_concrete_stairs
+ minecraft:red_concrete_slab
+ minecraft:red_concrete_stairs
+ minecraft:savanna_village_map
+ minecraft:snowy_village_map
+ minecraft:swamp_explorer_map
+ minecraft:taiga_village_map
+ minecraft:trial_explorer_map
+ minecraft:warm_ocean_ruins_map
+ minecraft:white_concrete_slab
+ minecraft:white_concrete_stairs
+ minecraft:woodland_explorer_map
+ minecraft:yellow_concrete_slab
+ minecraft:yellow_concrete_stairs
```

</details>
<details>
<summary>
map_decoration_type
</summary>

```diff
+ minecraft:abandoned_camp
+ minecraft:ancient_city
+ minecraft:desert_pyramid
+ minecraft:mineshaft
+ minecraft:ocean_ruin_warm
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
- minecraft:is_tempted
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:black_concrete_slab
+ minecraft:black_concrete_stairs
+ minecraft:blue_concrete_slab
+ minecraft:blue_concrete_stairs
+ minecraft:brown_concrete_slab
+ minecraft:brown_concrete_stairs
+ minecraft:cyan_concrete_slab
+ minecraft:cyan_concrete_stairs
+ minecraft:gray_concrete_slab
+ minecraft:gray_concrete_stairs
+ minecraft:green_concrete_slab
+ minecraft:green_concrete_stairs
+ minecraft:light_blue_concrete_slab
+ minecraft:light_blue_concrete_stairs
+ minecraft:light_gray_concrete_slab
+ minecraft:light_gray_concrete_stairs
+ minecraft:lime_concrete_slab
+ minecraft:lime_concrete_stairs
+ minecraft:magenta_concrete_slab
+ minecraft:magenta_concrete_stairs
+ minecraft:orange_concrete_slab
+ minecraft:orange_concrete_stairs
+ minecraft:pink_concrete_slab
+ minecraft:pink_concrete_stairs
+ minecraft:purple_concrete_slab
+ minecraft:purple_concrete_stairs
+ minecraft:red_concrete_slab
+ minecraft:red_concrete_stairs
+ minecraft:white_concrete_slab
+ minecraft:white_concrete_stairs
+ minecraft:yellow_concrete_slab
+ minecraft:yellow_concrete_stairs
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:black_concrete_slab
+ minecraft:black_concrete_stairs
+ minecraft:blue_concrete_slab
+ minecraft:blue_concrete_stairs
+ minecraft:brown_concrete_slab
+ minecraft:brown_concrete_stairs
+ minecraft:cyan_concrete_slab
+ minecraft:cyan_concrete_stairs
+ minecraft:gray_concrete_slab
+ minecraft:gray_concrete_stairs
+ minecraft:green_concrete_slab
+ minecraft:green_concrete_stairs
+ minecraft:light_blue_concrete_slab
+ minecraft:light_blue_concrete_stairs
+ minecraft:light_gray_concrete_slab
+ minecraft:light_gray_concrete_stairs
+ minecraft:lime_concrete_slab
+ minecraft:lime_concrete_stairs
+ minecraft:magenta_concrete_slab
+ minecraft:magenta_concrete_stairs
+ minecraft:orange_concrete_slab
+ minecraft:orange_concrete_stairs
+ minecraft:pink_concrete_slab
+ minecraft:pink_concrete_stairs
+ minecraft:purple_concrete_slab
+ minecraft:purple_concrete_stairs
+ minecraft:red_concrete_slab
+ minecraft:red_concrete_stairs
+ minecraft:white_concrete_slab
+ minecraft:white_concrete_stairs
+ minecraft:yellow_concrete_slab
+ minecraft:yellow_concrete_stairs
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:swing_animation
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:attack_animation
+ minecraft:interact_animation
- minecraft:map_color
- minecraft:swing_animation
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:abandoned_campsite_map
+ minecraft:ancient_city_map
+ minecraft:black_concrete_slab
+ minecraft:black_concrete_stairs
+ minecraft:blue_concrete_slab
+ minecraft:blue_concrete_stairs
+ minecraft:brown_concrete_slab
+ minecraft:brown_concrete_stairs
+ minecraft:buried_treasure_map
+ minecraft:cyan_concrete_slab
+ minecraft:cyan_concrete_stairs
+ minecraft:desert_pyramid_map
+ minecraft:desert_village_map
+ minecraft:gray_concrete_slab
+ minecraft:gray_concrete_stairs
+ minecraft:green_concrete_slab
+ minecraft:green_concrete_stairs
+ minecraft:jungle_explorer_map
+ minecraft:light_blue_concrete_slab
+ minecraft:light_blue_concrete_stairs
+ minecraft:light_gray_concrete_slab
+ minecraft:light_gray_concrete_stairs
+ minecraft:lime_concrete_slab
+ minecraft:lime_concrete_stairs
+ minecraft:magenta_concrete_slab
+ minecraft:magenta_concrete_stairs
+ minecraft:mineshaft_map
+ minecraft:ocean_explorer_map
+ minecraft:orange_concrete_slab
+ minecraft:orange_concrete_stairs
+ minecraft:pink_concrete_slab
+ minecraft:pink_concrete_stairs
+ minecraft:plains_village_map
+ minecraft:purple_concrete_slab
+ minecraft:purple_concrete_stairs
+ minecraft:red_concrete_slab
+ minecraft:red_concrete_stairs
+ minecraft:savanna_village_map
+ minecraft:snowy_village_map
+ minecraft:swamp_explorer_map
+ minecraft:taiga_village_map
+ minecraft:trial_explorer_map
+ minecraft:warm_ocean_ruins_map
+ minecraft:white_concrete_slab
+ minecraft:white_concrete_stairs
+ minecraft:woodland_explorer_map
+ minecraft:yellow_concrete_slab
+ minecraft:yellow_concrete_stairs
```

</details>
<details>
<summary>
universal_tags/map_decoration_type.json
</summary>

```diff
+ minecraft:abandoned_camp
+ minecraft:ancient_city
+ minecraft:desert_pyramid
+ minecraft:mineshaft
+ minecraft:ocean_ruin_warm
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
- minecraft:is_tempted
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ black_concrete_slab.json
+ black_concrete_stairs.json
+ blue_concrete_slab.json
+ blue_concrete_stairs.json
+ brown_concrete_slab.json
+ brown_concrete_stairs.json
+ cyan_concrete_slab.json
+ cyan_concrete_stairs.json
+ gray_concrete_slab.json
+ gray_concrete_stairs.json
+ green_concrete_slab.json
+ green_concrete_stairs.json
+ light_blue_concrete_slab.json
+ light_blue_concrete_stairs.json
+ light_gray_concrete_slab.json
+ light_gray_concrete_stairs.json
+ lime_concrete_slab.json
+ lime_concrete_stairs.json
+ magenta_concrete_slab.json
+ magenta_concrete_stairs.json
+ orange_concrete_slab.json
+ orange_concrete_stairs.json
+ pink_concrete_slab.json
+ pink_concrete_stairs.json
+ purple_concrete_slab.json
+ purple_concrete_stairs.json
+ red_concrete_slab.json
+ red_concrete_stairs.json
+ white_concrete_slab.json
+ white_concrete_stairs.json
+ yellow_concrete_slab.json
+ yellow_concrete_stairs.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
swing
</summary>

```diff
- swing <targets: entity> mainhand
+ swing <targets: entity> mainhand <animation: swing_animation> <duration: time>
- swing <targets: entity> offhand
+ swing <targets: entity> offhand <animation: swing_animation> <duration: time>
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
+ black_concrete_slab.json
+ black_concrete_stairs.json
+ blue_concrete_slab.json
+ blue_concrete_stairs.json
+ brown_concrete_slab.json
+ brown_concrete_stairs.json
+ cyan_concrete_slab.json
+ cyan_concrete_stairs.json
+ gray_concrete_slab.json
+ gray_concrete_stairs.json
+ green_concrete_slab.json
+ green_concrete_stairs.json
+ light_blue_concrete_slab.json
+ light_blue_concrete_stairs.json
+ light_gray_concrete_slab.json
+ light_gray_concrete_stairs.json
+ lime_concrete_slab.json
+ lime_concrete_stairs.json
+ magenta_concrete_slab.json
+ magenta_concrete_stairs.json
+ orange_concrete_slab.json
+ orange_concrete_stairs.json
+ pink_concrete_slab.json
+ pink_concrete_stairs.json
+ purple_concrete_slab.json
+ purple_concrete_stairs.json
+ red_concrete_slab.json
+ red_concrete_stairs.json
+ white_concrete_slab.json
+ white_concrete_stairs.json
+ yellow_concrete_slab.json
+ yellow_concrete_stairs.json
```

</details>
<details>
<summary>
map_cloning.json
</summary>

```
Result: filled_map x1 ->  x1
```

</details>
<details>
<summary>
map_extending.json
</summary>

```
Result: filled_map x1 ->  x1
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
+ argument.swing_animation.invalid: Unknown swing animation type: %s
+ block.minecraft.black_concrete_slab: Black Concrete Slab
+ block.minecraft.black_concrete_stairs: Black Concrete Stairs
+ block.minecraft.blue_concrete_slab: Blue Concrete Slab
+ block.minecraft.blue_concrete_stairs: Blue Concrete Stairs
+ block.minecraft.brown_concrete_slab: Brown Concrete Slab
+ block.minecraft.brown_concrete_stairs: Brown Concrete Stairs
+ block.minecraft.cyan_concrete_slab: Cyan Concrete Slab
+ block.minecraft.cyan_concrete_stairs: Cyan Concrete Stairs
+ block.minecraft.gray_concrete_slab: Gray Concrete Slab
+ block.minecraft.gray_concrete_stairs: Gray Concrete Stairs
+ block.minecraft.green_concrete_slab: Green Concrete Slab
+ block.minecraft.green_concrete_stairs: Green Concrete Stairs
+ block.minecraft.light_blue_concrete_slab: Light Blue Concrete Slab
+ block.minecraft.light_blue_concrete_stairs: Light Blue Concrete Stairs
+ block.minecraft.light_gray_concrete_slab: Light Gray Concrete Slab
+ block.minecraft.light_gray_concrete_stairs: Light Gray Concrete Stairs
+ block.minecraft.lime_concrete_slab: Lime Concrete Slab
+ block.minecraft.lime_concrete_stairs: Lime Concrete Stairs
+ block.minecraft.magenta_concrete_slab: Magenta Concrete Slab
+ block.minecraft.magenta_concrete_stairs: Magenta Concrete Stairs
+ block.minecraft.orange_concrete_slab: Orange Concrete Slab
+ block.minecraft.orange_concrete_stairs: Orange Concrete Stairs
+ block.minecraft.pink_concrete_slab: Pink Concrete Slab
+ block.minecraft.pink_concrete_stairs: Pink Concrete Stairs
+ block.minecraft.purple_concrete_slab: Purple Concrete Slab
+ block.minecraft.purple_concrete_stairs: Purple Concrete Stairs
+ block.minecraft.red_concrete_slab: Red Concrete Slab
+ block.minecraft.red_concrete_stairs: Red Concrete Stairs
+ block.minecraft.white_concrete_slab: White Concrete Slab
+ block.minecraft.white_concrete_stairs: White Concrete Stairs
+ block.minecraft.yellow_concrete_slab: Yellow Concrete Slab
+ block.minecraft.yellow_concrete_stairs: Yellow Concrete Stairs
+ filled_map.bamboo_jungle_abandoned_camp: Bamboo Jungle Abandoned Camp Map
+ filled_map.birch_forest_abandoned_camp: Birch Forest Abandoned Camp Map
+ filled_map.cherry_grove_abandoned_camp: Cherry Grove Abandoned Camp Map
+ filled_map.dappled_forest_abandoned_camp: Dappled Forest Abandoned Camp Map
+ filled_map.flower_forest_abandoned_camp: Flower Forest Abandoned Camp Map
+ filled_map.jungle_temple: Jungle Temple Map
+ filled_map.pale_garden_abandoned_camp: Pale Garden Abandoned Camp Map
+ filled_map.swamp_abandoned_camp: Swamp Abandoned Camp Map
+ filled_map.windswept_forest_abandoned_camp: Windswept Forest Abandoned Camp Map
+ item.minecraft.abandoned_campsite_map: Abandoned Campsite Map
+ item.minecraft.ancient_city_map: Ancient City Map
+ item.minecraft.buried_treasure_map: Buried Treasure Map
+ item.minecraft.desert_pyramid_map: Desert Pyramid Map
+ item.minecraft.desert_village_map: Desert Village Map
+ item.minecraft.jungle_explorer_map: Jungle Pyramid Explorer Map
+ item.minecraft.mineshaft_map: Mineshaft Map
+ item.minecraft.ocean_explorer_map: Ocean Monument Explorer Map
+ item.minecraft.plains_village_map: Plains Village Map
+ item.minecraft.savanna_village_map: Savanna Village Map
+ item.minecraft.snowy_village_map: Snowy Village Map
+ item.minecraft.swamp_explorer_map: Swamp Hut Explorer Map
+ item.minecraft.taiga_village_map: Taiga Village Map
+ item.minecraft.trial_explorer_map: Trial Chambers Explorer Map
+ item.minecraft.warm_ocean_ruins_map: Warm Ocean Ruins Map
+ item.minecraft.woodland_explorer_map: Woodland Mansion Explorer Map
+ key.keyboard.again: Again
+ key.keyboard.application: Menu
+ key.keyboard.copy: Copy
+ key.keyboard.cut: Cut
+ key.keyboard.find: Find
+ key.keyboard.help: Help
+ key.keyboard.keypad.comma: Keypad ,
+ key.keyboard.keypad.left.parenthesis: Keypad (
+ key.keyboard.keypad.period: Keypad .
+ key.keyboard.keypad.plus.minus: Keypad ±
+ key.keyboard.keypad.right.parenthesis: Keypad )
+ key.keyboard.left.command: Left Command
+ key.keyboard.left.option: Left Option
+ key.keyboard.left.windows: Left Win
+ key.keyboard.media.play.pause: Play/Pause
+ key.keyboard.mute: Mute
+ key.keyboard.new: New
+ key.keyboard.paste: Paste
+ key.keyboard.right.command: Right Command
+ key.keyboard.right.option: Right Option
+ key.keyboard.right.windows: Right Win
+ key.keyboard.save: Save
+ key.keyboard.stop: Stop
+ key.keyboard.undo: Undo
+ key.keyboard.volume.down: Volume Down
+ key.keyboard.volume.up: Volume Up
+ options.improvedTransparency.oit.tooltip: An experimental approach that uses an order-independent transparency algorithm to avoid graphical issues normally present when looking through multiple layers of translucent objects.
This will impact performance.
+ options.language.empty_or_missing_translation: Translation file for %s was empty or missing. Restart your game and launcher, then try again.
+ options.language.load_translations_failed: Loading translations failed
+ realms.configuration.region.canada_central: Canada
+ realms.configuration.region.mexico_central: Mexico
+ realms.configuration.region.south_africa_north: South Africa
+ realms.configuration.region.west_us_3: Arizona, USA
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3-snapshot-6</th><th>26.3-snapshot-7</th></tr>
<tr><th align="left"><div style="width:290px">key.keyboard.left.win</div></th><td>Left Win</td><td>Left Meta</td></tr>
<tr><th align="left"><div style="width:290px">key.keyboard.right.win</div></th><td>Right Win</td><td>Right Meta</td></tr>
<tr><th align="left"><div style="width:290px">options.improvedTransparency.tooltip</div></th><td>An experimental approach that uses an order-independent transparency algorithm to avoid graphical issues normally present when looking through multiple layers of translucent objects.

This will impact performance.</td><td>An experimental approach that uses screen shaders for drawing weather, clouds, and particles behind translucent blocks and water.

This will impact GPU performance.</td></tr>
<tr><th align="left"><div style="width:290px">options.quitShortcuts.tooltip</div></th><td>Whether keyboard shortcuts can close the game. When off, Alt + F4 on Windows and Linux, and Cmd + Q and Cmd + W on macOS, will no longer quit the game.</td><td>Whether keyboard shortcuts can close the game. When off, Alt + F4 on Windows and Linux, and Cmd + Q on macOS, will no longer quit the game.</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>PACKETS</ins></b><a name="packets"></a></summary>
<br/>
<details>
<summary>
[client] play
</summary>

```diff
+ minecraft:swing_animation
```

</details>
<details>
<summary>
[server] play
</summary>

```diff
+ minecraft:punch
- minecraft:swing
```

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
+ reports/minecraft/components/item/abandoned_campsite_map.json
+ reports/minecraft/components/item/ancient_city_map.json
+ reports/minecraft/components/item/black_concrete_slab.json
+ reports/minecraft/components/item/black_concrete_stairs.json
+ reports/minecraft/components/item/blue_concrete_slab.json
+ reports/minecraft/components/item/blue_concrete_stairs.json
+ reports/minecraft/components/item/brown_concrete_slab.json
+ reports/minecraft/components/item/brown_concrete_stairs.json
+ reports/minecraft/components/item/buried_treasure_map.json
+ reports/minecraft/components/item/cyan_concrete_slab.json
+ reports/minecraft/components/item/cyan_concrete_stairs.json
+ reports/minecraft/components/item/desert_pyramid_map.json
+ reports/minecraft/components/item/desert_village_map.json
+ reports/minecraft/components/item/gray_concrete_slab.json
+ reports/minecraft/components/item/gray_concrete_stairs.json
+ reports/minecraft/components/item/green_concrete_slab.json
+ reports/minecraft/components/item/green_concrete_stairs.json
+ reports/minecraft/components/item/jungle_explorer_map.json
+ reports/minecraft/components/item/light_blue_concrete_slab.json
+ reports/minecraft/components/item/light_blue_concrete_stairs.json
+ reports/minecraft/components/item/light_gray_concrete_slab.json
+ reports/minecraft/components/item/light_gray_concrete_stairs.json
+ reports/minecraft/components/item/lime_concrete_slab.json
+ reports/minecraft/components/item/lime_concrete_stairs.json
+ reports/minecraft/components/item/magenta_concrete_slab.json
+ reports/minecraft/components/item/magenta_concrete_stairs.json
+ reports/minecraft/components/item/mineshaft_map.json
+ reports/minecraft/components/item/ocean_explorer_map.json
+ reports/minecraft/components/item/orange_concrete_slab.json
+ reports/minecraft/components/item/orange_concrete_stairs.json
+ reports/minecraft/components/item/pink_concrete_slab.json
+ reports/minecraft/components/item/pink_concrete_stairs.json
+ reports/minecraft/components/item/plains_village_map.json
+ reports/minecraft/components/item/purple_concrete_slab.json
+ reports/minecraft/components/item/purple_concrete_stairs.json
+ reports/minecraft/components/item/red_concrete_slab.json
+ reports/minecraft/components/item/red_concrete_stairs.json
+ reports/minecraft/components/item/savanna_village_map.json
+ reports/minecraft/components/item/snowy_village_map.json
+ reports/minecraft/components/item/swamp_explorer_map.json
+ reports/minecraft/components/item/taiga_village_map.json
+ reports/minecraft/components/item/trial_explorer_map.json
+ reports/minecraft/components/item/warm_ocean_ruins_map.json
+ reports/minecraft/components/item/white_concrete_slab.json
+ reports/minecraft/components/item/white_concrete_stairs.json
+ reports/minecraft/components/item/woodland_explorer_map.json
+ reports/minecraft/components/item/yellow_concrete_slab.json
+ reports/minecraft/components/item/yellow_concrete_stairs.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/black_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/black_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/blue_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/blue_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/brown_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/brown_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/cyan_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/cyan_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/gray_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/gray_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/green_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/green_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/light_blue_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/light_blue_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/light_gray_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/light_gray_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/lime_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/lime_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/magenta_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/magenta_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/orange_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/orange_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/pink_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/pink_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/purple_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/purple_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/red_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/red_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/white_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/white_concrete_stairs.json
+ minecraft/advancement/recipes/building_blocks/yellow_concrete_slab.json
+ minecraft/advancement/recipes/building_blocks/yellow_concrete_stairs.json
+ minecraft/loot_table/blocks/black_concrete_slab.json
+ minecraft/loot_table/blocks/black_concrete_stairs.json
+ minecraft/loot_table/blocks/blue_concrete_slab.json
+ minecraft/loot_table/blocks/blue_concrete_stairs.json
+ minecraft/loot_table/blocks/brown_concrete_slab.json
+ minecraft/loot_table/blocks/brown_concrete_stairs.json
+ minecraft/loot_table/blocks/cyan_concrete_slab.json
+ minecraft/loot_table/blocks/cyan_concrete_stairs.json
+ minecraft/loot_table/blocks/gray_concrete_slab.json
+ minecraft/loot_table/blocks/gray_concrete_stairs.json
+ minecraft/loot_table/blocks/green_concrete_slab.json
+ minecraft/loot_table/blocks/green_concrete_stairs.json
+ minecraft/loot_table/blocks/light_blue_concrete_slab.json
+ minecraft/loot_table/blocks/light_blue_concrete_stairs.json
+ minecraft/loot_table/blocks/light_gray_concrete_slab.json
+ minecraft/loot_table/blocks/light_gray_concrete_stairs.json
+ minecraft/loot_table/blocks/lime_concrete_slab.json
+ minecraft/loot_table/blocks/lime_concrete_stairs.json
+ minecraft/loot_table/blocks/magenta_concrete_slab.json
+ minecraft/loot_table/blocks/magenta_concrete_stairs.json
+ minecraft/loot_table/blocks/orange_concrete_slab.json
+ minecraft/loot_table/blocks/orange_concrete_stairs.json
+ minecraft/loot_table/blocks/pink_concrete_slab.json
+ minecraft/loot_table/blocks/pink_concrete_stairs.json
+ minecraft/loot_table/blocks/purple_concrete_slab.json
+ minecraft/loot_table/blocks/purple_concrete_stairs.json
+ minecraft/loot_table/blocks/red_concrete_slab.json
+ minecraft/loot_table/blocks/red_concrete_stairs.json
+ minecraft/loot_table/blocks/white_concrete_slab.json
+ minecraft/loot_table/blocks/white_concrete_stairs.json
+ minecraft/loot_table/blocks/yellow_concrete_slab.json
+ minecraft/loot_table/blocks/yellow_concrete_stairs.json
+ minecraft/recipe/black_concrete_slab.json
+ minecraft/recipe/black_concrete_stairs.json
+ minecraft/recipe/blue_concrete_slab.json
+ minecraft/recipe/blue_concrete_stairs.json
+ minecraft/recipe/brown_concrete_slab.json
+ minecraft/recipe/brown_concrete_stairs.json
+ minecraft/recipe/cyan_concrete_slab.json
+ minecraft/recipe/cyan_concrete_stairs.json
+ minecraft/recipe/gray_concrete_slab.json
+ minecraft/recipe/gray_concrete_stairs.json
+ minecraft/recipe/green_concrete_slab.json
+ minecraft/recipe/green_concrete_stairs.json
+ minecraft/recipe/light_blue_concrete_slab.json
+ minecraft/recipe/light_blue_concrete_stairs.json
+ minecraft/recipe/light_gray_concrete_slab.json
+ minecraft/recipe/light_gray_concrete_stairs.json
+ minecraft/recipe/lime_concrete_slab.json
+ minecraft/recipe/lime_concrete_stairs.json
+ minecraft/recipe/magenta_concrete_slab.json
+ minecraft/recipe/magenta_concrete_stairs.json
+ minecraft/recipe/orange_concrete_slab.json
+ minecraft/recipe/orange_concrete_stairs.json
+ minecraft/recipe/pink_concrete_slab.json
+ minecraft/recipe/pink_concrete_stairs.json
+ minecraft/recipe/purple_concrete_slab.json
+ minecraft/recipe/purple_concrete_stairs.json
+ minecraft/recipe/red_concrete_slab.json
+ minecraft/recipe/red_concrete_stairs.json
+ minecraft/recipe/white_concrete_slab.json
+ minecraft/recipe/white_concrete_stairs.json
+ minecraft/recipe/yellow_concrete_slab.json
+ minecraft/recipe/yellow_concrete_stairs.json
+ minecraft/tags/block/concrete_slabs.json
+ minecraft/tags/block/concrete_stairs.json
+ minecraft/tags/item/clonable_maps.json
+ minecraft/tags/item/concrete_slabs.json
+ minecraft/tags/item/concrete_stairs.json
+ minecraft/tags/item/extendable_maps.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_bamboo_jungle.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_birch_forest.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_cherry_grove.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_dappled_forest.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_flower_forest.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_pale_garden.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_swamp.json
+ minecraft/tags/worldgen/structure/on_abandoned_camp_windswept.json
+ minecraft/tags/worldgen/structure/on_ancient_city_maps.json
+ minecraft/tags/worldgen/structure/on_desert_pyramid_maps.json
+ minecraft/tags/worldgen/structure/on_mineshaft_maps.json
+ minecraft/tags/worldgen/structure/on_ocean_ruin_warm_maps.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/black_concrete_slab.json
+ minecraft/blockstates/black_concrete_stairs.json
+ minecraft/blockstates/blue_concrete_slab.json
+ minecraft/blockstates/blue_concrete_stairs.json
+ minecraft/blockstates/brown_concrete_slab.json
+ minecraft/blockstates/brown_concrete_stairs.json
+ minecraft/blockstates/cyan_concrete_slab.json
+ minecraft/blockstates/cyan_concrete_stairs.json
+ minecraft/blockstates/gray_concrete_slab.json
+ minecraft/blockstates/gray_concrete_stairs.json
+ minecraft/blockstates/green_concrete_slab.json
+ minecraft/blockstates/green_concrete_stairs.json
+ minecraft/blockstates/light_blue_concrete_slab.json
+ minecraft/blockstates/light_blue_concrete_stairs.json
+ minecraft/blockstates/light_gray_concrete_slab.json
+ minecraft/blockstates/light_gray_concrete_stairs.json
+ minecraft/blockstates/lime_concrete_slab.json
+ minecraft/blockstates/lime_concrete_stairs.json
+ minecraft/blockstates/magenta_concrete_slab.json
+ minecraft/blockstates/magenta_concrete_stairs.json
+ minecraft/blockstates/orange_concrete_slab.json
+ minecraft/blockstates/orange_concrete_stairs.json
+ minecraft/blockstates/pink_concrete_slab.json
+ minecraft/blockstates/pink_concrete_stairs.json
+ minecraft/blockstates/purple_concrete_slab.json
+ minecraft/blockstates/purple_concrete_stairs.json
+ minecraft/blockstates/red_concrete_slab.json
+ minecraft/blockstates/red_concrete_stairs.json
+ minecraft/blockstates/white_concrete_slab.json
+ minecraft/blockstates/white_concrete_stairs.json
+ minecraft/blockstates/yellow_concrete_slab.json
+ minecraft/blockstates/yellow_concrete_stairs.json
+ minecraft/items/abandoned_campsite_map.json
+ minecraft/items/ancient_city_map.json
+ minecraft/items/black_concrete_slab.json
+ minecraft/items/black_concrete_stairs.json
+ minecraft/items/blue_concrete_slab.json
+ minecraft/items/blue_concrete_stairs.json
+ minecraft/items/brown_concrete_slab.json
+ minecraft/items/brown_concrete_stairs.json
+ minecraft/items/buried_treasure_map.json
+ minecraft/items/cyan_concrete_slab.json
+ minecraft/items/cyan_concrete_stairs.json
+ minecraft/items/desert_pyramid_map.json
+ minecraft/items/desert_village_map.json
+ minecraft/items/gray_concrete_slab.json
+ minecraft/items/gray_concrete_stairs.json
+ minecraft/items/green_concrete_slab.json
+ minecraft/items/green_concrete_stairs.json
+ minecraft/items/jungle_explorer_map.json
+ minecraft/items/light_blue_concrete_slab.json
+ minecraft/items/light_blue_concrete_stairs.json
+ minecraft/items/light_gray_concrete_slab.json
+ minecraft/items/light_gray_concrete_stairs.json
+ minecraft/items/lime_concrete_slab.json
+ minecraft/items/lime_concrete_stairs.json
+ minecraft/items/magenta_concrete_slab.json
+ minecraft/items/magenta_concrete_stairs.json
+ minecraft/items/mineshaft_map.json
+ minecraft/items/ocean_explorer_map.json
+ minecraft/items/orange_concrete_slab.json
+ minecraft/items/orange_concrete_stairs.json
+ minecraft/items/pink_concrete_slab.json
+ minecraft/items/pink_concrete_stairs.json
+ minecraft/items/plains_village_map.json
+ minecraft/items/purple_concrete_slab.json
+ minecraft/items/purple_concrete_stairs.json
+ minecraft/items/red_concrete_slab.json
+ minecraft/items/red_concrete_stairs.json
+ minecraft/items/savanna_village_map.json
+ minecraft/items/snowy_village_map.json
+ minecraft/items/swamp_explorer_map.json
+ minecraft/items/taiga_village_map.json
+ minecraft/items/trial_explorer_map.json
+ minecraft/items/warm_ocean_ruins_map.json
+ minecraft/items/white_concrete_slab.json
+ minecraft/items/white_concrete_stairs.json
+ minecraft/items/woodland_explorer_map.json
+ minecraft/items/yellow_concrete_slab.json
+ minecraft/items/yellow_concrete_stairs.json
+ minecraft/models/block/black_concrete_slab_top.json
+ minecraft/models/block/black_concrete_slab.json
+ minecraft/models/block/black_concrete_stairs_inner.json
+ minecraft/models/block/black_concrete_stairs_outer.json
+ minecraft/models/block/black_concrete_stairs.json
+ minecraft/models/block/blue_concrete_slab_top.json
+ minecraft/models/block/blue_concrete_slab.json
+ minecraft/models/block/blue_concrete_stairs_inner.json
+ minecraft/models/block/blue_concrete_stairs_outer.json
+ minecraft/models/block/blue_concrete_stairs.json
+ minecraft/models/block/brown_concrete_slab_top.json
+ minecraft/models/block/brown_concrete_slab.json
+ minecraft/models/block/brown_concrete_stairs_inner.json
+ minecraft/models/block/brown_concrete_stairs_outer.json
+ minecraft/models/block/brown_concrete_stairs.json
+ minecraft/models/block/cyan_concrete_slab_top.json
+ minecraft/models/block/cyan_concrete_slab.json
+ minecraft/models/block/cyan_concrete_stairs_inner.json
+ minecraft/models/block/cyan_concrete_stairs_outer.json
+ minecraft/models/block/cyan_concrete_stairs.json
+ minecraft/models/block/gray_concrete_slab_top.json
+ minecraft/models/block/gray_concrete_slab.json
+ minecraft/models/block/gray_concrete_stairs_inner.json
+ minecraft/models/block/gray_concrete_stairs_outer.json
+ minecraft/models/block/gray_concrete_stairs.json
+ minecraft/models/block/green_concrete_slab_top.json
+ minecraft/models/block/green_concrete_slab.json
+ minecraft/models/block/green_concrete_stairs_inner.json
+ minecraft/models/block/green_concrete_stairs_outer.json
+ minecraft/models/block/green_concrete_stairs.json
+ minecraft/models/block/light_blue_concrete_slab_top.json
+ minecraft/models/block/light_blue_concrete_slab.json
+ minecraft/models/block/light_blue_concrete_stairs_inner.json
+ minecraft/models/block/light_blue_concrete_stairs_outer.json
+ minecraft/models/block/light_blue_concrete_stairs.json
+ minecraft/models/block/light_gray_concrete_slab_top.json
+ minecraft/models/block/light_gray_concrete_slab.json
+ minecraft/models/block/light_gray_concrete_stairs_inner.json
+ minecraft/models/block/light_gray_concrete_stairs_outer.json
+ minecraft/models/block/light_gray_concrete_stairs.json
+ minecraft/models/block/lime_concrete_slab_top.json
+ minecraft/models/block/lime_concrete_slab.json
+ minecraft/models/block/lime_concrete_stairs_inner.json
+ minecraft/models/block/lime_concrete_stairs_outer.json
+ minecraft/models/block/lime_concrete_stairs.json
+ minecraft/models/block/magenta_concrete_slab_top.json
+ minecraft/models/block/magenta_concrete_slab.json
+ minecraft/models/block/magenta_concrete_stairs_inner.json
+ minecraft/models/block/magenta_concrete_stairs_outer.json
+ minecraft/models/block/magenta_concrete_stairs.json
+ minecraft/models/block/orange_concrete_slab_top.json
+ minecraft/models/block/orange_concrete_slab.json
+ minecraft/models/block/orange_concrete_stairs_inner.json
+ minecraft/models/block/orange_concrete_stairs_outer.json
+ minecraft/models/block/orange_concrete_stairs.json
+ minecraft/models/block/pink_concrete_slab_top.json
+ minecraft/models/block/pink_concrete_slab.json
+ minecraft/models/block/pink_concrete_stairs_inner.json
+ minecraft/models/block/pink_concrete_stairs_outer.json
+ minecraft/models/block/pink_concrete_stairs.json
+ minecraft/models/block/purple_concrete_slab_top.json
+ minecraft/models/block/purple_concrete_slab.json
+ minecraft/models/block/purple_concrete_stairs_inner.json
+ minecraft/models/block/purple_concrete_stairs_outer.json
+ minecraft/models/block/purple_concrete_stairs.json
+ minecraft/models/block/red_concrete_slab_top.json
+ minecraft/models/block/red_concrete_slab.json
+ minecraft/models/block/red_concrete_stairs_inner.json
+ minecraft/models/block/red_concrete_stairs_outer.json
+ minecraft/models/block/red_concrete_stairs.json
+ minecraft/models/block/white_concrete_slab_top.json
+ minecraft/models/block/white_concrete_slab.json
+ minecraft/models/block/white_concrete_stairs_inner.json
+ minecraft/models/block/white_concrete_stairs_outer.json
+ minecraft/models/block/white_concrete_stairs.json
+ minecraft/models/block/yellow_concrete_slab_top.json
+ minecraft/models/block/yellow_concrete_slab.json
+ minecraft/models/block/yellow_concrete_stairs_inner.json
+ minecraft/models/block/yellow_concrete_stairs_outer.json
+ minecraft/models/block/yellow_concrete_stairs.json
+ minecraft/models/item/abandoned_campsite_map.json
+ minecraft/models/item/ancient_city_map.json
+ minecraft/models/item/buried_treasure_map.json
+ minecraft/models/item/desert_pyramid_map.json
+ minecraft/models/item/desert_village_map.json
+ minecraft/models/item/jungle_explorer_map.json
+ minecraft/models/item/mineshaft_map.json
+ minecraft/models/item/ocean_explorer_map.json
+ minecraft/models/item/plains_village_map.json
+ minecraft/models/item/savanna_village_map.json
+ minecraft/models/item/snowy_village_map.json
+ minecraft/models/item/swamp_explorer_map.json
+ minecraft/models/item/taiga_village_map.json
+ minecraft/models/item/trial_explorer_map.json
+ minecraft/models/item/warm_ocean_ruins_map.json
+ minecraft/models/item/woodland_explorer_map.json
- minecraft/textures/block/straw_bed_head.json
+ minecraft/textures/item/abandoned_campsite_map.png
+ minecraft/textures/item/ancient_city_map.png
+ minecraft/textures/item/buried_treasure_map.png
+ minecraft/textures/item/desert_pyramid_map.png
+ minecraft/textures/item/desert_village_map.png
- minecraft/textures/item/filled_map_markings.png
+ minecraft/textures/item/jungle_temple_map.png
+ minecraft/textures/item/mineshaft_map.png
+ minecraft/textures/item/ocean_monument_map.png
+ minecraft/textures/item/plains_village_map.png
+ minecraft/textures/item/savanna_village_map.png
+ minecraft/textures/item/snowy_village_map.png
+ minecraft/textures/item/swamp_hut_map.png
+ minecraft/textures/item/taiga_village_map.png
+ minecraft/textures/item/trial_chamber_map.png
+ minecraft/textures/item/warm_ocean_ruins_map.png
+ minecraft/textures/item/woodland_mansion_map.png
+ minecraft/textures/map/decorations/abandoned_camp.png
+ minecraft/textures/map/decorations/ancient_city.png
+ minecraft/textures/map/decorations/desert_pyramid.png
+ minecraft/textures/map/decorations/mineshaft.png
+ minecraft/textures/map/decorations/warm_ocean_ruins.png
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
+ minecraft:swing_animation
```

</details>
</details>
<hr/>