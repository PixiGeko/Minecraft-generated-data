## Comparison with [26.3-snapshot-5](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-5)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-5</th><th>26.3-snapshot-6</th></tr><tr><td>DataPack version</td><td><pre>112.0</pre></td><td><pre>113.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>93.0</pre></td><td><pre>94.0</pre></td></tr><tr><td>World version</td><td><pre>5004</pre></td><td><pre>5005</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742151</pre></td><td><pre>1073742152</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">26.3-snapshot-5</th><th>26.3-snapshot-6</th></tr><tr><td>io.netty:netty-buffer</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-codec-base</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-codec-compression</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-codec-http</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-common</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-handler</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-resolver</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-epoll</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-classes-kqueue</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-aarch_64)</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-epoll (linux-x86_64)</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-aarch_64)</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-kqueue (osx-x86_64)</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport-native-unix-common</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr><tr><td>io.netty:netty-transport</td><td><pre>4.2.15.Final</pre></td><td><pre>4.2.16.Final</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
+ minecraft:distance_to_point
- minecraft:end_islands
+ minecraft:end_outer_islands
+ minecraft:gradient
+ minecraft:log
+ minecraft:pow
+ minecraft:sign
+ minecraft:slice
+ minecraft:sqrt
- minecraft:y_clamped_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
+ minecraft:distance_to_point
- minecraft:end_islands
+ minecraft:end_outer_islands
+ minecraft:gradient
+ minecraft:log
+ minecraft:pow
+ minecraft:sign
+ minecraft:slice
+ minecraft:sqrt
- minecraft:y_clamped_gradient
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
publish
</summary>

```diff
- publish <allowCommands: bool> <gamemode: gamemode> <port: integer>
+ publish <allowCommands: bool> <port: integer>
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
black_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
black_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
black_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
blue_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
blue_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
blue_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
brown_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
brown_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
brown_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
cyan_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
cyan_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
cyan_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
gray_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
gray_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
gray_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
green_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
green_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
green_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
light_blue_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
light_blue_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
light_blue_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
light_gray_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
light_gray_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
light_gray_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
lime_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
lime_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
lime_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
magenta_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
magenta_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
magenta_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
orange_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
orange_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
orange_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
pink_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
pink_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
pink_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
purple_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
purple_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
purple_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
red_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
red_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
red_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
white_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
white_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
white_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
```

</details>
<details>
<summary>
yellow_carpet.json
</summary>

```
Group: carpet -> woolen_carpet
```

</details>
<details>
<summary>
yellow_wool_slab.json
</summary>

```
Group: none -> woolen_slab
```

</details>
<details>
<summary>
yellow_wool_stairs.json
</summary>

```
Group: none -> woolen_stairs
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
+ options.quitShortcuts: Quit Shortcuts
+ options.quitShortcuts.tooltip: Whether keyboard shortcuts can close the game. When off, Alt + F4 on Windows and Linux, and Cmd + Q and Cmd + W on macOS, will no longer quit the game.
+ options.worldOptions.allow_commands.disabled.demo.tooltip: Cannot allow commands in a demo world.
+ options.worldOptions.difficulty.disabled.hardcore.tooltip: Cannot change the difficulty in a hardcore world.
+ options.worldOptions.difficulty.disabled.locked.tooltip: Difficulty is locked.
+ options.worldOptions.difficulty.disabled.operator.tooltip: Changing the difficulty requires operator permissions.
+ options.worldOptions.general.title: General
+ options.worldOptions.guest.command_access: Command Access
+ options.worldOptions.guest.command_access.disabled.commands.tooltip: Cannot change the command access of players joining your world when commands are not allowed.
+ options.worldOptions.guest.command_access.disabled.scope.tooltip: Cannot change the command access of players joining your world when the world's multiplayer scope is set to "Off".
+ options.worldOptions.guest.command_access.tooltip: Controls whether players that join your world can use commands or not.
+ options.worldOptions.multiplayer.title: Multiplayer
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
+ minecraft/structure/abandoned_camp/camp/bamboo_jungle/campsite_bamboo_jungle_4.nbt
+ minecraft/structure/abandoned_camp/camp/birch_forest/campsite_birch_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/cherry_grove/campsite_cherry_grove_4.nbt
+ minecraft/structure/abandoned_camp/camp/dappled_forest/campsite_dappled_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/flower_forest/campsite_flower_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/forest/campsite_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/meadow/campsite_meadow_4.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_birch_forest/campsite_old_growth_birch_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_pine_taiga/campsite_old_growth_pine_taiga_4.nbt
+ minecraft/structure/abandoned_camp/camp/old_growth_spruce_taiga/campsite_old_growth_spruce_taiga_4.nbt
+ minecraft/structure/abandoned_camp/camp/pale_garden/campsite_pale_garden_4.nbt
+ minecraft/structure/abandoned_camp/camp/savanna/campsite_savanna_4.nbt
+ minecraft/structure/abandoned_camp/camp/snowy_taiga/campsite_snowy_taiga_4.nbt
+ minecraft/structure/abandoned_camp/camp/sparse_jungle/campsite_sparse_jungle_4.nbt
+ minecraft/structure/abandoned_camp/camp/swamp/campsite_swamp_4.nbt
+ minecraft/structure/abandoned_camp/camp/taiga/campsite_taiga_4.nbt
+ minecraft/structure/abandoned_camp/camp/windswept_forest/campsite_windswept_forest_4.nbt
+ minecraft/structure/abandoned_camp/camp/wooded_badlands/campsite_wooded_badlands_4.nbt
+ minecraft/worldgen/density_function/end/islands.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/shaders/include/terrainglobals.glsl
```

</details>
</details>
<hr/>