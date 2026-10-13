## Comparison with [26.4-snapshot-3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.4-snapshot-3</th><th>26.4-snapshot-4</th></tr><tr><td>DataPack version</td><td><pre>123.0</pre></td><td><pre>124.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>100.0</pre></td><td><pre>100.1</pre></td></tr><tr><td>World version</td><td><pre>5122</pre></td><td><pre>5124</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742165</pre></td><td><pre>1073742166</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.4-snapshot-3</th><th>26.4-snapshot-4</th></tr><tr><td>com.mojang:authlib</td><td><pre>10.0.77</pre></td><td><pre>11.0.80</pre></td></tr><tr><td>com.mojang:datafixerupper</td><td><pre>10.0.21</pre></td><td><pre>11.0.22</pre></td></tr></table>
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
+ minecraft:brittle_ice
```

</details>
<details>
<summary>
fluid
</summary>

```diff
- minecraft:flowing_lava
- minecraft:flowing_water
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:brittle_ice
```

</details>
<details>
<summary>
menu
</summary>

```diff
+ minecraft:jukebox
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.blue_ice.break
+ minecraft:block.blue_ice.fall
+ minecraft:block.blue_ice.hit
+ minecraft:block.blue_ice.place
+ minecraft:block.blue_ice.step
+ minecraft:block.brittle_ice.break
+ minecraft:block.brittle_ice.crack
+ minecraft:block.brittle_ice.fall
+ minecraft:block.brittle_ice.hit
+ minecraft:block.brittle_ice.place
+ minecraft:block.brittle_ice.step
+ minecraft:block.frosted_ice.break
+ minecraft:block.frosted_ice.fall
+ minecraft:block.frosted_ice.hit
+ minecraft:block.frosted_ice.place
+ minecraft:block.frosted_ice.step
+ minecraft:block.packed_ice.break
+ minecraft:block.packed_ice.fall
+ minecraft:block.packed_ice.hit
+ minecraft:block.packed_ice.place
+ minecraft:block.packed_ice.step
+ minecraft:entity.chicken_picky.step
+ minecraft:entity.drowned.converted_to_zombie
- minecraft:intentionally_empty
```

</details>
<details>
<summary>
worldgen/feature_type
</summary>

```diff
+ minecraft:crevasse
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
+ minecraft:brittle_ice
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:brittle_ice
```

</details>
<details>
<summary>
universal_tags/fluid.json
</summary>

```diff
- minecraft:flowing_lava
- minecraft:flowing_water
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:brittle_ice
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
+ minecraft:jukebox
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.blue_ice.break
+ minecraft:block.blue_ice.fall
+ minecraft:block.blue_ice.hit
+ minecraft:block.blue_ice.place
+ minecraft:block.blue_ice.step
+ minecraft:block.brittle_ice.break
+ minecraft:block.brittle_ice.crack
+ minecraft:block.brittle_ice.fall
+ minecraft:block.brittle_ice.hit
+ minecraft:block.brittle_ice.place
+ minecraft:block.brittle_ice.step
+ minecraft:block.frosted_ice.break
+ minecraft:block.frosted_ice.fall
+ minecraft:block.frosted_ice.hit
+ minecraft:block.frosted_ice.place
+ minecraft:block.frosted_ice.step
+ minecraft:block.packed_ice.break
+ minecraft:block.packed_ice.fall
+ minecraft:block.packed_ice.hit
+ minecraft:block.packed_ice.place
+ minecraft:block.packed_ice.step
+ minecraft:entity.chicken_picky.step
+ minecraft:entity.drowned.converted_to_zombie
- minecraft:intentionally_empty
```

</details>
<details>
<summary>
universal_tags/worldgen/feature_type.json
</summary>

```diff
+ minecraft:crevasse
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
+ brittle_ice.json
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
+ block.minecraft.brittle_ice: Brittle Ice
+ record.playingNext: Playing Next
+ subtitles.block.brittle_ice.crack: Brittle Ice cracks
+ subtitles.block.icicle.land: Icicle crashes down
+ subtitles.block.sulfur_spike.land: Sulfur Spike crashes down
+ subtitles.entity.drowned.converted_to_zombie: Drowned converts to Zombie
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.4-snapshot-3</th><th>26.4-snapshot-4</th></tr>
<tr><th align="left"><div style="width:290px">key.debug.fpsCharts</div></th><td>Fps Charts</td><td>FPS Charts</td></tr>
<tr><th align="left"><div style="width:290px">options.framerate</div></th><td>%s fps</td><td>%s FPS</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.pointed_dripstone.land</div></th><td>Stalactite crashes down</td><td>Pointed Dripstone crashes down</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.frostbite.hurt</div></th><td>Frostbite hurts</td><td>Frostbite is hurt</td></tr>
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
+ reports/minecraft/components/item/brittle_ice.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/block_sound_set/amethyst_block.json
- minecraft/block_sound_set/amethyst.json
+ minecraft/block_sound_set/blue_ice.json
+ minecraft/block_sound_set/brittle_ice.json
+ minecraft/block_sound_set/frosted_ice.json
+ minecraft/block_sound_set/packed_ice.json
+ minecraft/loot_table/blocks/brittle_ice.json
+ minecraft/tags/block/face_occluding_ice_blocks.json
+ minecraft/tags/block/ice_crevasse_replaceables.json
+ minecraft/tags/block/jukebox_containers.json
+ minecraft/tags/damage_type/no_hurt_sound.json
+ minecraft/tags/entity_type/does_not_break_brittle_ice.json
+ minecraft/tags/item/jukebox_containers.json
+ minecraft/worldgen/feature/ice_crevasse.json
+ minecraft/worldgen/placed_feature/ice_crevasse.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/brittle_ice.json
+ minecraft/items/brittle_ice.json
+ minecraft/models/block/brittle_ice_0.json
+ minecraft/models/block/brittle_ice_1.json
+ minecraft/models/block/brittle_ice_2.json
+ minecraft/models/block/brittle_ice_3.json
+ minecraft/textures/block/brittle_ice_0.png
+ minecraft/textures/block/brittle_ice_1.png
+ minecraft/textures/block/brittle_ice_2.png
+ minecraft/textures/block/brittle_ice_3.png
+ minecraft/textures/block/jukebox_bottom.png
```

</details>
</details>
<hr/>