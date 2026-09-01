## Comparison with [26.3-snapshot-10](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-10)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-10</th><th>26.3-pre-1</th></tr><tr><td>DataPack version</td><td><pre>118.0</pre></td><td><pre>119.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>97.0</pre></td><td><pre>97.1</pre></td></tr><tr><td>World version</td><td><pre>5015</pre></td><td><pre>5017</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742156</pre></td><td><pre>1073742157</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ org.lwjgl:lwjgl-spng (natives-linux) V3.4.3
+ org.lwjgl:lwjgl-spng (natives-macos-arm64) V3.4.3
+ org.lwjgl:lwjgl-spng (natives-macos) V3.4.3
+ org.lwjgl:lwjgl-spng (natives-windows-arm64) V3.4.3
+ org.lwjgl:lwjgl-spng (natives-windows-x86) V3.4.3
+ org.lwjgl:lwjgl-spng (natives-windows) V3.4.3
+ org.lwjgl:lwjgl-spng V3.4.3
```

</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ context_float_provider_type.txt
+ context_int_provider_type.txt
- loot_number_provider_type.txt
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:context_float_provider
+ minecraft:context_int_provider
- minecraft:number_provider
```

</details>
<details>
<summary>
loot_condition_type
</summary>

```diff
+ minecraft:float_value_check
+ minecraft:int_value_check
- minecraft:value_check
```

</details>
<details>
<summary>
worldgen/block_state_provider_type
</summary>

```diff
+ minecraft:copy_properties
- minecraft:copy_properties_provider
+ minecraft:dual_noise
- minecraft:dual_noise_provider
+ minecraft:noise
- minecraft:noise_provider
+ minecraft:noise_threshold
- minecraft:noise_threshold_provider
+ minecraft:random_block
- minecraft:random_block_provider
+ minecraft:randomized_int
- minecraft:randomized_int_state_provider
+ minecraft:rotated
- minecraft:rotated_block_provider
+ minecraft:rule_based
- minecraft:rule_based_state_provider
+ minecraft:simple
- minecraft:simple_state_provider
+ minecraft:weighted
- minecraft:weighted_state_provider
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ universal_tags/context_float_provider_type.json
+ universal_tags/context_int_provider_type.json
- universal_tags/loot_number_provider_type.json
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:context_float_provider
+ minecraft:context_int_provider
- minecraft:number_provider
```

</details>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
+ minecraft:float_value_check
+ minecraft:int_value_check
- minecraft:value_check
```

</details>
<details>
<summary>
universal_tags/worldgen/block_state_provider_type.json
</summary>

```diff
+ minecraft:copy_properties
- minecraft:copy_properties_provider
+ minecraft:dual_noise
- minecraft:dual_noise_provider
+ minecraft:noise
- minecraft:noise_provider
+ minecraft:noise_threshold
- minecraft:noise_threshold_provider
+ minecraft:random_block
- minecraft:random_block_provider
+ minecraft:randomized_int
- minecraft:randomized_int_state_provider
+ minecraft:rotated
- minecraft:rotated_block_provider
+ minecraft:rule_based
- minecraft:rule_based_state_provider
+ minecraft:simple
- minecraft:simple_state_provider
+ minecraft:weighted
- minecraft:weighted_state_provider
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
compute
</summary>

```diff
- compute block <computePos: block_pos> <provider: number_provider> <scale: float>
- compute block <computePos: block_pos> <provider: number_provider> integer
+ compute block <computePos: block_pos> float <provider: context_float_provider> <scale: float>
+ compute block <computePos: block_pos> integer <provider: context_int_provider>
- compute default <provider: number_provider> <scale: float>
- compute default <provider: number_provider> integer
+ compute default float <provider: context_float_provider> <scale: float>
+ compute default integer <provider: context_int_provider>
- compute entity <computeTarget: entity> <provider: number_provider> <scale: float>
- compute entity <computeTarget: entity> <provider: number_provider> integer
+ compute entity <computeTarget: entity> float <provider: context_float_provider> <scale: float>
+ compute entity <computeTarget: entity> integer <provider: context_int_provider>
```

</details>
<details>
<summary>
data
</summary>

```diff
- data modify block <target: block_pos> <targetPath: nbt_path> append compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> append compute default <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute default float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute default integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> append compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> append compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute default <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute default float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute default integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> merge compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> merge compute default <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute default float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute default integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> merge compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> merge compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> prepend compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> prepend compute default <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute default float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute default integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> set compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> set compute default <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute default float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute default integer <provider: context_int_provider>
- data modify block <target: block_pos> <targetPath: nbt_path> set compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify block <target: block_pos> <targetPath: nbt_path> set compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> append compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> append compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> append compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> append compute default <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> append compute default float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> append compute default integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> append compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> append compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> append compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute default <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute default float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute default integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> merge compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> merge compute default <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute default float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute default integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> merge compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> merge compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> prepend compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> prepend compute default <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute default float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute default integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> set compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> set compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> set compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> set compute default <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> set compute default float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> set compute default integer <provider: context_int_provider>
- data modify entity <target: entity> <targetPath: nbt_path> set compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify entity <target: entity> <targetPath: nbt_path> set compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify entity <target: entity> <targetPath: nbt_path> set compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> append compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> append compute default <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute default float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute default integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> append compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> append compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute default <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute default float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute default integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> insert <index: integer> compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> merge compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> merge compute default <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute default float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute default integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> merge compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> merge compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute default <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute default float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute default integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> prepend compute entity <computeTarget: entity> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> set compute block <computePos: block_pos> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute block <computePos: block_pos> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute block <computePos: block_pos> integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> set compute default <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute default float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute default integer <provider: context_int_provider>
- data modify storage <target: resource_location> <targetPath: nbt_path> set compute entity <computeTarget: entity> <provider: number_provider> integer
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute entity <computeTarget: entity> float <provider: context_float_provider>
+ data modify storage <target: resource_location> <targetPath: nbt_path> set compute entity <computeTarget: entity> integer <provider: context_int_provider>
```

</details>
</details>
<hr/>
<details><summary><b><ins>DATAPACKS</ins></b><a name="datapacks"></a></summary>
<br/>
<details>
<summary>
[registries] List
</summary>

```diff
+ minecraft:context_float_provider
+ minecraft:context_float_provider_type
+ minecraft:context_int_provider
+ minecraft:context_int_provider_type
- minecraft:loot_number_provider_type
- minecraft:number_provider
+ minecraft:worldgen/block_state_provider
```

</details>
<details>
<summary>
[registries] minecraft:advancement
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-10</th><th>26.3-pre-1</th></tr><tr><td>tags</td><td><pre>false</pre></td><td><pre>true</pre></td></tr></table>
</details>
<details>
<summary>
[registries] minecraft:recipe
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-10</th><th>26.3-pre-1</th></tr><tr><td>tags</td><td><pre>false</pre></td><td><pre>true</pre></td></tr></table>
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
+ command.compute.result.named.invalid: %s returned invalid value (%s)
+ command.compute.result.unnamed.invalid: Number provider returned invalid value (%s)
+ mco.selectServer.joinCode.select: Join Realm
+ options.macFullscreenMenuVisibility: Menu/Dock Visibility
+ options.macFullscreenMenuVisibility.tooltip: Whether the macOS Menu bar and Dock can be revealed by moving the mouse to the edge of the screen while in non-exclusive fullscreen.
```

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
+ minecraft/context_float_provider/brewing/speed_default.json
+ minecraft/context_float_provider/cooking/fast_speed_multiplier.json
+ minecraft/context_float_provider/cooking/normal_speed_multiplier.json
+ minecraft/context_float_provider/cooking/speed_default.json
+ minecraft/context_int_provider/brewing/uses_default.json
+ minecraft/context_int_provider/compostable/always_add_one.json
+ minecraft/context_int_provider/compostable/low_medium.json
+ minecraft/context_int_provider/compostable/low.json
+ minecraft/context_int_provider/compostable/medium_high.json
+ minecraft/context_int_provider/compostable/medium.json
+ minecraft/context_int_provider/cooking/fast_burn_time_reduction_factor.json
+ minecraft/context_int_provider/cooking/normal_burn_time_reduction_factor.json
+ minecraft/context_int_provider/cooking/time_bamboo.json
+ minecraft/context_int_provider/cooking/time_blaze_rod.json
+ minecraft/context_int_provider/cooking/time_boats.json
+ minecraft/context_int_provider/cooking/time_coal_block.json
+ minecraft/context_int_provider/cooking/time_coal.json
+ minecraft/context_int_provider/cooking/time_dried_kelp_block.json
+ minecraft/context_int_provider/cooking/time_dry_plants.json
+ minecraft/context_int_provider/cooking/time_hanging_signs.json
+ minecraft/context_int_provider/cooking/time_lava_bucket.json
+ minecraft/context_int_provider/cooking/time_roots.json
+ minecraft/context_int_provider/cooking/time_wood_blocks.json
+ minecraft/context_int_provider/cooking/time_wood_items_extra_small.json
+ minecraft/context_int_provider/cooking/time_wood_items_large.json
+ minecraft/context_int_provider/cooking/time_wood_items_small.json
+ minecraft/context_int_provider/cooking/time_wood_slabs.json
+ minecraft/context_int_provider/cooking/time_wool_carpets.json
+ minecraft/context_int_provider/cooking/time_wool_slabs.json
+ minecraft/context_int_provider/cooking/time_wool.json
- minecraft/number_provider/brewing/speed_default.json
- minecraft/number_provider/brewing/uses_default.json
- minecraft/number_provider/compostable/always_add_one.json
- minecraft/number_provider/compostable/low_medium.json
- minecraft/number_provider/compostable/low.json
- minecraft/number_provider/compostable/medium_high.json
- minecraft/number_provider/compostable/medium.json
- minecraft/number_provider/cooking/fast_burn_time_multiplier.json
- minecraft/number_provider/cooking/fast_speed_multiplier.json
- minecraft/number_provider/cooking/normal_burn_time_multiplier.json
- minecraft/number_provider/cooking/normal_speed_multiplier.json
- minecraft/number_provider/cooking/speed_default.json
- minecraft/number_provider/cooking/time_bamboo.json
- minecraft/number_provider/cooking/time_blaze_rod.json
- minecraft/number_provider/cooking/time_boats.json
- minecraft/number_provider/cooking/time_coal_block.json
- minecraft/number_provider/cooking/time_coal.json
- minecraft/number_provider/cooking/time_dried_kelp_block.json
- minecraft/number_provider/cooking/time_dry_plants.json
- minecraft/number_provider/cooking/time_hanging_signs.json
- minecraft/number_provider/cooking/time_lava_bucket.json
- minecraft/number_provider/cooking/time_roots.json
- minecraft/number_provider/cooking/time_wood_blocks.json
- minecraft/number_provider/cooking/time_wood_items_extra_small.json
- minecraft/number_provider/cooking/time_wood_items_large.json
- minecraft/number_provider/cooking/time_wood_items_small.json
- minecraft/number_provider/cooking/time_wood_slabs.json
- minecraft/number_provider/cooking/time_wool_carpets.json
- minecraft/number_provider/cooking/time_wool_slabs.json
- minecraft/number_provider/cooking/time_wool.json
+ minecraft/tags/item/furnace_fuel_bottom_takeable.json
+ minecraft/worldgen/block_state_provider/cave_vines_body.json
+ minecraft/worldgen/block_state_provider/cave_vines_head.json
+ minecraft/worldgen/block_state_provider/flower_flower_forest.json
+ minecraft/worldgen/block_state_provider/flower_meadow.json
+ minecraft/worldgen/block_state_provider/flower_plain.json
+ minecraft/worldgen/block_state_provider/mangrove_propagule.json
+ minecraft/worldgen/block_state_provider/podzol_beneath_tree.json
+ minecraft/worldgen/block_state_provider/soil_beneath_tree.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/shaders/core/blit_depth.fsh
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
+ minecraft:context_float_provider
+ minecraft:context_int_provider
- minecraft:number_provider
```

</details>
</details>
<hr/>