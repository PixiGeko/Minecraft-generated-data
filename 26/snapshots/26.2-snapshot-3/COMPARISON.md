## Comparison with [26.2-snapshot-2](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.2-snapshot-2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.2-snapshot-2</th><th>26.2-snapshot-3</th></tr><tr><td>DataPack version</td><td><pre>101.2</pre></td><td><pre>102.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>85.0</pre></td><td><pre>86.0</pre></td></tr><tr><td>World version</td><td><pre>4884</pre></td><td><pre>4886</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742132</pre></td><td><pre>1073742133</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.2-snapshot-2</th><th>26.2-snapshot-3</th></tr><tr><td>com.mojang:text2speech</td><td><pre>1.18.11</pre></td><td><pre>1.19.12</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:sulfur_spike
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
- minecraft:bed
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:sulfur_spike
```

</details>
<details>
<summary>
entity_sub_predicate_type
</summary>

```diff
+ minecraft:components
+ minecraft:distance
+ minecraft:effects
+ minecraft:entity_tags
+ minecraft:entity_type
+ minecraft:equipment
- minecraft:fishing_hook
+ minecraft:flags
- minecraft:lightning
+ minecraft:location
+ minecraft:movement
+ minecraft:movement_affected_by
+ minecraft:nbt
+ minecraft:passenger
+ minecraft:periodic_tick
- minecraft:player
+ minecraft:predicates
- minecraft:raider
- minecraft:sheep
- minecraft:slime
+ minecraft:slots
+ minecraft:stepping_on
+ minecraft:targeted_entity
+ minecraft:team
+ minecraft:type_specific/fishing_hook
+ minecraft:type_specific/lightning
+ minecraft:type_specific/player
+ minecraft:type_specific/raider
+ minecraft:type_specific/sheep
+ minecraft:type_specific/slime
+ minecraft:vehicle
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:sulfur_spike
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
+ minecraft:sulfur_spike
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:sulfur_spike
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
- minecraft:bed
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:sulfur_spike
```

</details>
<details>
<summary>
universal_tags/entity_sub_predicate_type.json
</summary>

```diff
+ minecraft:components
+ minecraft:distance
+ minecraft:effects
+ minecraft:entity_tags
+ minecraft:entity_type
+ minecraft:equipment
- minecraft:fishing_hook
+ minecraft:flags
- minecraft:lightning
+ minecraft:location
+ minecraft:movement
+ minecraft:movement_affected_by
+ minecraft:nbt
+ minecraft:passenger
+ minecraft:periodic_tick
- minecraft:player
+ minecraft:predicates
- minecraft:raider
- minecraft:sheep
- minecraft:slime
+ minecraft:slots
+ minecraft:stepping_on
+ minecraft:targeted_entity
+ minecraft:team
+ minecraft:type_specific/fishing_hook
+ minecraft:type_specific/lightning
+ minecraft:type_specific/player
+ minecraft:type_specific/raider
+ minecraft:type_specific/sheep
+ minecraft:type_specific/slime
+ minecraft:vehicle
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:sulfur_spike
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
+ sulfur_spike.json
```

</details>
<details>
<summary>
pointed_dripstone
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.2-snapshot-2</th><th>26.2-snapshot-3</th></tr><tr><td>block_to_grow_on</td><td><pre>/</pre></td><td><pre>{
  "Name": "minecraft:dripstone_block"
}</pre></td></tr></table>
<br/>
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
+ sulfur_from_sulfur_spikes.json
- sulfur.json
```

</details>
<details>
<summary>
potent_sulfur.json
</summary>

```
Type: minecraft:crafting_shaped -> minecraft:crafting_shapeless
Group: potent_sulfur -> none
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
+ block.minecraft.sulfur_spike: Sulfur Spike
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.2-snapshot-2</th><th>26.2-snapshot-3</th></tr>
<tr><th align="left"><div style="width:290px">block.minecraft.polished_sulfur</div></th><td>Polished Sulfur Block</td><td>Polished Sulfur</td></tr>
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
+ reports/minecraft/components/item/sulfur_spike.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/sulfur_from_sulfur_spikes.json
- minecraft/advancement/recipes/building_blocks/sulfur.json
+ minecraft/loot_table/blocks/sulfur_spike.json
+ minecraft/recipe/sulfur_from_sulfur_spikes.json
- minecraft/recipe/sulfur.json
+ minecraft/tags/block/speleothems.json
+ minecraft/tags/block/sulfur_spike_replaceable_blocks.json
+ minecraft/villager_trade/wandering_trader/emerald_sulfur_spike.json
+ minecraft/worldgen/configured_feature/sulfur_spike_cluster.json
+ minecraft/worldgen/configured_feature/sulfur_spike.json
+ minecraft/worldgen/placed_feature/sulfur_spike_cluster.json
+ minecraft/worldgen/placed_feature/sulfur_spike.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/sulfur_spike.json
+ minecraft/items/sulfur_spike.json
+ minecraft/models/block/bed_foot.json
+ minecraft/models/block/bed_head.json
- minecraft/models/block/bed.json
+ minecraft/models/block/black_bed_foot.json
+ minecraft/models/block/black_bed_head.json
+ minecraft/models/block/blue_bed_foot.json
+ minecraft/models/block/blue_bed_head.json
+ minecraft/models/block/brown_bed_foot.json
+ minecraft/models/block/brown_bed_head.json
+ minecraft/models/block/cyan_bed_foot.json
+ minecraft/models/block/cyan_bed_head.json
+ minecraft/models/block/gray_bed_foot.json
+ minecraft/models/block/gray_bed_head.json
+ minecraft/models/block/green_bed_foot.json
+ minecraft/models/block/green_bed_head.json
+ minecraft/models/block/light_blue_bed_foot.json
+ minecraft/models/block/light_blue_bed_head.json
+ minecraft/models/block/light_gray_bed_foot.json
+ minecraft/models/block/light_gray_bed_head.json
+ minecraft/models/block/lime_bed_foot.json
+ minecraft/models/block/lime_bed_head.json
+ minecraft/models/block/magenta_bed_foot.json
+ minecraft/models/block/magenta_bed_head.json
+ minecraft/models/block/orange_bed_foot.json
+ minecraft/models/block/orange_bed_head.json
+ minecraft/models/block/pink_bed_foot.json
+ minecraft/models/block/pink_bed_head.json
+ minecraft/models/block/purple_bed_foot.json
+ minecraft/models/block/purple_bed_head.json
+ minecraft/models/block/red_bed_foot.json
+ minecraft/models/block/red_bed_head.json
+ minecraft/models/block/sulfur_spike_down_base.json
+ minecraft/models/block/sulfur_spike_down_frustum.json
+ minecraft/models/block/sulfur_spike_down_middle.json
+ minecraft/models/block/sulfur_spike_down_tip_merge.json
+ minecraft/models/block/sulfur_spike_down_tip.json
+ minecraft/models/block/sulfur_spike_up_base.json
+ minecraft/models/block/sulfur_spike_up_frustum.json
+ minecraft/models/block/sulfur_spike_up_middle.json
+ minecraft/models/block/sulfur_spike_up_tip_merge.json
+ minecraft/models/block/sulfur_spike_up_tip.json
+ minecraft/models/block/template_bed.json
+ minecraft/models/block/white_bed_foot.json
+ minecraft/models/block/white_bed_head.json
+ minecraft/models/block/yellow_bed_foot.json
+ minecraft/models/block/yellow_bed_head.json
- minecraft/models/item/black_bed.json
- minecraft/models/item/blue_bed.json
- minecraft/models/item/brown_bed.json
- minecraft/models/item/cyan_bed.json
- minecraft/models/item/gray_bed.json
- minecraft/models/item/green_bed.json
- minecraft/models/item/light_blue_bed.json
- minecraft/models/item/light_gray_bed.json
- minecraft/models/item/lime_bed.json
- minecraft/models/item/magenta_bed.json
- minecraft/models/item/orange_bed.json
- minecraft/models/item/pink_bed.json
- minecraft/models/item/purple_bed.json
- minecraft/models/item/red_bed.json
+ minecraft/models/item/sulfur_spike.json
- minecraft/models/item/template_bed.json
- minecraft/models/item/white_bed.json
- minecraft/models/item/yellow_bed.json
+ minecraft/textures/block/bed_down.png
+ minecraft/textures/block/bed_head_north.png
+ minecraft/textures/block/black_bed_foot_east.png
+ minecraft/textures/block/black_bed_foot_south.png
+ minecraft/textures/block/black_bed_foot_up.png
+ minecraft/textures/block/black_bed_foot_west.png
+ minecraft/textures/block/black_bed_head_east.png
+ minecraft/textures/block/black_bed_head_up.png
+ minecraft/textures/block/black_bed_head_west.png
+ minecraft/textures/block/blue_bed_foot_east.png
+ minecraft/textures/block/blue_bed_foot_south.png
+ minecraft/textures/block/blue_bed_foot_up.png
+ minecraft/textures/block/blue_bed_foot_west.png
+ minecraft/textures/block/blue_bed_head_east.png
+ minecraft/textures/block/blue_bed_head_up.png
+ minecraft/textures/block/blue_bed_head_west.png
+ minecraft/textures/block/brown_bed_foot_east.png
+ minecraft/textures/block/brown_bed_foot_south.png
+ minecraft/textures/block/brown_bed_foot_up.png
+ minecraft/textures/block/brown_bed_foot_west.png
+ minecraft/textures/block/brown_bed_head_east.png
+ minecraft/textures/block/brown_bed_head_up.png
+ minecraft/textures/block/brown_bed_head_west.png
+ minecraft/textures/block/cyan_bed_foot_east.png
+ minecraft/textures/block/cyan_bed_foot_south.png
+ minecraft/textures/block/cyan_bed_foot_up.png
+ minecraft/textures/block/cyan_bed_foot_west.png
+ minecraft/textures/block/cyan_bed_head_east.png
+ minecraft/textures/block/cyan_bed_head_up.png
+ minecraft/textures/block/cyan_bed_head_west.png
+ minecraft/textures/block/gray_bed_foot_east.png
+ minecraft/textures/block/gray_bed_foot_south.png
+ minecraft/textures/block/gray_bed_foot_up.png
+ minecraft/textures/block/gray_bed_foot_west.png
+ minecraft/textures/block/gray_bed_head_east.png
+ minecraft/textures/block/gray_bed_head_up.png
+ minecraft/textures/block/gray_bed_head_west.png
+ minecraft/textures/block/green_bed_foot_east.png
+ minecraft/textures/block/green_bed_foot_south.png
+ minecraft/textures/block/green_bed_foot_up.png
+ minecraft/textures/block/green_bed_foot_west.png
+ minecraft/textures/block/green_bed_head_east.png
+ minecraft/textures/block/green_bed_head_up.png
+ minecraft/textures/block/green_bed_head_west.png
+ minecraft/textures/block/light_blue_bed_foot_east.png
+ minecraft/textures/block/light_blue_bed_foot_south.png
+ minecraft/textures/block/light_blue_bed_foot_up.png
+ minecraft/textures/block/light_blue_bed_foot_west.png
+ minecraft/textures/block/light_blue_bed_head_east.png
+ minecraft/textures/block/light_blue_bed_head_up.png
+ minecraft/textures/block/light_blue_bed_head_west.png
+ minecraft/textures/block/light_gray_bed_foot_east.png
+ minecraft/textures/block/light_gray_bed_foot_south.png
+ minecraft/textures/block/light_gray_bed_foot_up.png
+ minecraft/textures/block/light_gray_bed_foot_west.png
+ minecraft/textures/block/light_gray_bed_head_east.png
+ minecraft/textures/block/light_gray_bed_head_up.png
+ minecraft/textures/block/light_gray_bed_head_west.png
+ minecraft/textures/block/lime_bed_foot_east.png
+ minecraft/textures/block/lime_bed_foot_south.png
+ minecraft/textures/block/lime_bed_foot_up.png
+ minecraft/textures/block/lime_bed_foot_west.png
+ minecraft/textures/block/lime_bed_head_east.png
+ minecraft/textures/block/lime_bed_head_up.png
+ minecraft/textures/block/lime_bed_head_west.png
+ minecraft/textures/block/magenta_bed_foot_east.png
+ minecraft/textures/block/magenta_bed_foot_south.png
+ minecraft/textures/block/magenta_bed_foot_up.png
+ minecraft/textures/block/magenta_bed_foot_west.png
+ minecraft/textures/block/magenta_bed_head_east.png
+ minecraft/textures/block/magenta_bed_head_up.png
+ minecraft/textures/block/magenta_bed_head_west.png
+ minecraft/textures/block/orange_bed_foot_east.png
+ minecraft/textures/block/orange_bed_foot_south.png
+ minecraft/textures/block/orange_bed_foot_up.png
+ minecraft/textures/block/orange_bed_foot_west.png
+ minecraft/textures/block/orange_bed_head_east.png
+ minecraft/textures/block/orange_bed_head_up.png
+ minecraft/textures/block/orange_bed_head_west.png
+ minecraft/textures/block/pink_bed_foot_east.png
+ minecraft/textures/block/pink_bed_foot_south.png
+ minecraft/textures/block/pink_bed_foot_up.png
+ minecraft/textures/block/pink_bed_foot_west.png
+ minecraft/textures/block/pink_bed_head_east.png
+ minecraft/textures/block/pink_bed_head_up.png
+ minecraft/textures/block/pink_bed_head_west.png
+ minecraft/textures/block/purple_bed_foot_east.png
+ minecraft/textures/block/purple_bed_foot_south.png
+ minecraft/textures/block/purple_bed_foot_up.png
+ minecraft/textures/block/purple_bed_foot_west.png
+ minecraft/textures/block/purple_bed_head_east.png
+ minecraft/textures/block/purple_bed_head_up.png
+ minecraft/textures/block/purple_bed_head_west.png
+ minecraft/textures/block/red_bed_foot_east.png
+ minecraft/textures/block/red_bed_foot_south.png
+ minecraft/textures/block/red_bed_foot_up.png
+ minecraft/textures/block/red_bed_foot_west.png
+ minecraft/textures/block/red_bed_head_east.png
+ minecraft/textures/block/red_bed_head_up.png
+ minecraft/textures/block/red_bed_head_west.png
+ minecraft/textures/block/sulfur_spike_down_base.png
+ minecraft/textures/block/sulfur_spike_down_frustum.png
+ minecraft/textures/block/sulfur_spike_down_middle.png
+ minecraft/textures/block/sulfur_spike_down_tip_merge.png
+ minecraft/textures/block/sulfur_spike_down_tip.png
+ minecraft/textures/block/sulfur_spike_up_base.png
+ minecraft/textures/block/sulfur_spike_up_frustum.png
+ minecraft/textures/block/sulfur_spike_up_middle.png
+ minecraft/textures/block/sulfur_spike_up_tip_merge.png
+ minecraft/textures/block/sulfur_spike_up_tip.png
+ minecraft/textures/block/white_bed_foot_east.png
+ minecraft/textures/block/white_bed_foot_south.png
+ minecraft/textures/block/white_bed_foot_up.png
+ minecraft/textures/block/white_bed_foot_west.png
+ minecraft/textures/block/white_bed_head_east.png
+ minecraft/textures/block/white_bed_head_up.png
+ minecraft/textures/block/white_bed_head_west.png
+ minecraft/textures/block/yellow_bed_foot_east.png
+ minecraft/textures/block/yellow_bed_foot_south.png
+ minecraft/textures/block/yellow_bed_foot_up.png
+ minecraft/textures/block/yellow_bed_foot_west.png
+ minecraft/textures/block/yellow_bed_head_east.png
+ minecraft/textures/block/yellow_bed_head_up.png
+ minecraft/textures/block/yellow_bed_head_west.png
- minecraft/textures/entity/bed/black.png
- minecraft/textures/entity/bed/blue.png
- minecraft/textures/entity/bed/brown.png
- minecraft/textures/entity/bed/cyan.png
- minecraft/textures/entity/bed/gray.png
- minecraft/textures/entity/bed/green.png
- minecraft/textures/entity/bed/light_blue.png
- minecraft/textures/entity/bed/light_gray.png
- minecraft/textures/entity/bed/lime.png
- minecraft/textures/entity/bed/magenta.png
- minecraft/textures/entity/bed/orange.png
- minecraft/textures/entity/bed/pink.png
- minecraft/textures/entity/bed/purple.png
- minecraft/textures/entity/bed/red.png
- minecraft/textures/entity/bed/white.png
- minecraft/textures/entity/bed/yellow.png
+ minecraft/textures/item/sulfur_spike.png
```

</details>
</details>
<hr/>