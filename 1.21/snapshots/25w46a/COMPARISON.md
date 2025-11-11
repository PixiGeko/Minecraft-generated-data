## Comparison with [25w45a](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w45a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 93,
  "minor": 0
}</pre></td><td><pre>{
  "major": 93,
  "minor": 1
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 73,
  "minor": 0
}</pre></td><td><pre>{
  "major": 74,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4660</pre></td><td><pre>4662</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742101</pre></td><td><pre>1073742102</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.zombie_horse.eat
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.zombie_horse.eat
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
cod_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:food</td><td><pre>/</pre></td><td><pre>{
  "nutrition": 2,
  "saturation": 0.4
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
copper_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:damage_resistant</td><td><pre>/</pre></td><td><pre>{
  "types": "#minecraft:is_fire"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
netherite_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pufferfish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:food</td><td><pre>/</pre></td><td><pre>{
  "nutrition": 1,
  "saturation": 0.2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
salmon_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:food</td><td><pre>/</pre></td><td><pre>{
  "nutrition": 2,
  "saturation": 0.4
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
stone_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
tropical_fish_bucket
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:consumable</td><td><pre>/</pre></td><td><pre>{}</pre></td></tr><tr><td>minecraft:food</td><td><pre>/</pre></td><td><pre>{
  "nutrition": 1,
  "saturation": 0.2
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wooden_spear
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w45a</th><th>25w46a</th></tr><tr><td>minecraft:use_effects</td><td><pre>{
  "can_sprint": true,
  "speed_multiplier": 1
}</pre></td><td><pre>{
  "can_sprint": true,
  "interact_vibrations": false,
  "speed_multiplier": 1
}</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
copper_bulb.json
</summary>

```
Group: none -> copper_bulb
```

</details>
<details>
<summary>
copper_grate.json
</summary>

```
Group: none -> copper_grate
```

</details>
<details>
<summary>
exposed_copper_bulb.json
</summary>

```
Group: none -> exposed_copper_bulb
```

</details>
<details>
<summary>
exposed_copper_grate.json
</summary>

```
Group: none -> exposed_copper_grate
```

</details>
<details>
<summary>
oxidized_copper_bulb.json
</summary>

```
Group: none -> oxidized_copper_bulb
```

</details>
<details>
<summary>
oxidized_copper_grate.json
</summary>

```
Group: none -> oxidized_copper_grate
```

</details>
<details>
<summary>
waxed_chiseled_copper.json
</summary>

```
Group: waxed_cut_copper_chiseled -> waxed_chiseled_copper
Result: waxed_chiseled_copper x1 -> waxed_chiseled_copper x2
```
```
A: waxed_cut_copper_slab

Previous pattern:
[A]
[A]

New pattern:
[  | A |  ]
[  | A |  ]
```

</details>
<details>
<summary>
waxed_copper_bars_from_honeycomb.json
</summary>

```
Group: waxed_copper_bars -> waxed_copper_bar
```

</details>
<details>
<summary>
waxed_copper_bulb.json
</summary>

```
Group: none -> waxed_copper_bulb
```

</details>
<details>
<summary>
waxed_copper_bulb_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_copper_door_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_copper_grate.json
</summary>

```
Group: none -> waxed_copper_grate
```

</details>
<details>
<summary>
waxed_copper_trapdoor_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_exposed_chiseled_copper.json
</summary>

```
Group: waxed_exposed_cut_copper_chiseled -> waxed_exposed_chiseled_copper
Result: waxed_exposed_chiseled_copper x1 -> waxed_exposed_chiseled_copper x2
```
```
A: waxed_exposed_cut_copper_slab

Previous pattern:
[A]
[A]

New pattern:
[  | A |  ]
[  | A |  ]
```

</details>
<details>
<summary>
waxed_exposed_copper_bars_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper_bars -> waxed_copper_bar
```

</details>
<details>
<summary>
waxed_exposed_copper_bulb.json
</summary>

```
Group: none -> waxed_exposed_copper_bulb
```

</details>
<details>
<summary>
waxed_exposed_copper_bulb_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_exposed_copper_chain_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper_chain -> waxed_copper_chain
```

</details>
<details>
<summary>
waxed_exposed_copper_chest_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper_chest -> waxed_copper_chest
```

</details>
<details>
<summary>
waxed_exposed_copper_door_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_exposed_copper_door -> waxed_copper_door
```

</details>
<details>
<summary>
waxed_exposed_copper_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper -> waxed_copper_block
```

</details>
<details>
<summary>
waxed_exposed_copper_golem_statue_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper_golem_statue -> waxed_copper_golem_statue
```

</details>
<details>
<summary>
waxed_exposed_copper_grate.json
</summary>

```
Group: none -> waxed_exposed_copper_grate
```

</details>
<details>
<summary>
waxed_exposed_copper_lantern_from_honeycomb.json
</summary>

```
Group: waxed_exposed_copper_lantern -> waxed_copper_lantern
```

</details>
<details>
<summary>
waxed_exposed_copper_trapdoor_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_exposed_copper_trapdoor -> waxed_copper_trapdoor
```

</details>
<details>
<summary>
waxed_exposed_lightning_rod_from_honeycomb.json
</summary>

```
Group: waxed_exposed_lightning_rod -> waxed_lightning_rod
```

</details>
<details>
<summary>
waxed_oxidized_chiseled_copper.json
</summary>

```
Group: waxed_oxidized_cut_copper_chiseled -> waxed_oxidized_chiseled_copper
Result: waxed_oxidized_chiseled_copper x1 -> waxed_oxidized_chiseled_copper x2
```
```
A: waxed_oxidized_cut_copper_slab

Previous pattern:
[A]
[A]

New pattern:
[  | A |  ]
[  | A |  ]
```

</details>
<details>
<summary>
waxed_oxidized_copper_bars_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper_bars -> waxed_copper_bar
```

</details>
<details>
<summary>
waxed_oxidized_copper_bulb.json
</summary>

```
Group: none -> waxed_oxidized_copper_bulb
```

</details>
<details>
<summary>
waxed_oxidized_copper_bulb_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_oxidized_copper_chain_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper_chain -> waxed_copper_chain
```

</details>
<details>
<summary>
waxed_oxidized_copper_chest_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper_chest -> waxed_copper_chest
```

</details>
<details>
<summary>
waxed_oxidized_copper_door_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_oxidized_copper_door -> waxed_copper_door
```

</details>
<details>
<summary>
waxed_oxidized_copper_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper -> waxed_copper_block
```

</details>
<details>
<summary>
waxed_oxidized_copper_golem_statue_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper_golem_statue -> waxed_copper_golem_statue
```

</details>
<details>
<summary>
waxed_oxidized_copper_grate.json
</summary>

```
Group: none -> waxed_oxidized_copper_grate
```

</details>
<details>
<summary>
waxed_oxidized_copper_lantern_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_copper_lantern -> waxed_copper_lantern
```

</details>
<details>
<summary>
waxed_oxidized_copper_trapdoor_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_oxidized_copper_trapdoor -> waxed_copper_trapdoor
```

</details>
<details>
<summary>
waxed_oxidized_lightning_rod_from_honeycomb.json
</summary>

```
Group: waxed_oxidized_lightning_rod -> waxed_lightning_rod
```

</details>
<details>
<summary>
waxed_weathered_chiseled_copper.json
</summary>

```
Group: waxed_weathered_cut_copper_chiseled -> waxed_weathered_chiseled_copper
Result: waxed_weathered_chiseled_copper x1 -> waxed_weathered_chiseled_copper x2
```
```
A: waxed_weathered_cut_copper_slab

Previous pattern:
[A]
[A]

New pattern:
[  | A |  ]
[  | A |  ]
```

</details>
<details>
<summary>
waxed_weathered_copper_bars_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper_bars -> waxed_copper_bar
```

</details>
<details>
<summary>
waxed_weathered_copper_bulb.json
</summary>

```
Group: none -> waxed_weathered_copper_bulb
```

</details>
<details>
<summary>
waxed_weathered_copper_bulb_from_honeycomb.json
</summary>

```
Category: building -> redstone
```

</details>
<details>
<summary>
waxed_weathered_copper_chain_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper_chain -> waxed_copper_chain
```

</details>
<details>
<summary>
waxed_weathered_copper_chest_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper_chest -> waxed_copper_chest
```

</details>
<details>
<summary>
waxed_weathered_copper_door_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_weathered_copper_door -> waxed_copper_door
```

</details>
<details>
<summary>
waxed_weathered_copper_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper -> waxed_copper_block
```

</details>
<details>
<summary>
waxed_weathered_copper_golem_statue_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper_golem_statue -> waxed_copper_golem_statue
```

</details>
<details>
<summary>
waxed_weathered_copper_grate.json
</summary>

```
Group: none -> waxed_weathered_copper_grate
```

</details>
<details>
<summary>
waxed_weathered_copper_lantern_from_honeycomb.json
</summary>

```
Group: waxed_weathered_copper_lantern -> waxed_copper_lantern
```

</details>
<details>
<summary>
waxed_weathered_copper_trapdoor_from_honeycomb.json
</summary>

```
Category: building -> redstone
Group: waxed_weathered_copper_trapdoor -> waxed_copper_trapdoor
```

</details>
<details>
<summary>
waxed_weathered_lightning_rod_from_honeycomb.json
</summary>

```
Group: waxed_weathered_lightning_rod -> waxed_lightning_rod
```

</details>
<details>
<summary>
weathered_copper_bulb.json
</summary>

```
Group: none -> weathered_copper_bulb
```

</details>
<details>
<summary>
weathered_copper_grate.json
</summary>

```
Group: none -> weathered_copper_grate
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
+ gui.recipebook.next_page: Next Page
+ gui.recipebook.previous_page: Previous Page
+ options.musicToast: Music Toast
+ options.musicToast.never: Never
+ options.musicToast.never.tooltip: No music toast is shown.
+ options.musicToast.pauseMenu: Pause Menu
+ options.musicToast.pauseMenu.tooltip: A music toast is constantly displayed in the in-game pause menu while a song is playing.
+ options.musicToast.pauseMenuAndToast: Pause Menu and Toast
+ options.musicToast.pauseMenuAndToast.tooltip: Displays a toast when a song starts playing. The same toast is constantly displayed in the in-game pause menu while a song is playing.
+ subtitles.entity.zombie_horse.eat: Zombie Horse eats
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>25w45a</th><th>25w46a</th></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.parched.ambient</div></th><td>Parched rattles</td><td>Parched crackles</td></tr>
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
- minecraft:horse_screen_open
+ minecraft:mount_screen_open
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
- minecraft/advancement/recipes/building_blocks/waxed_copper_bulb_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_copper_door_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_copper_trapdoor_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_exposed_copper_bulb_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_exposed_copper_door_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_exposed_copper_trapdoor_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_oxidized_copper_bulb_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_oxidized_copper_door_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_oxidized_copper_trapdoor_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_weathered_copper_bulb_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_weathered_copper_door_from_honeycomb.json
- minecraft/advancement/recipes/building_blocks/waxed_weathered_copper_trapdoor_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_copper_bulb_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_copper_door_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_copper_trapdoor_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_exposed_copper_bulb_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_exposed_copper_door_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_exposed_copper_trapdoor_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_oxidized_copper_bulb_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_oxidized_copper_door_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_oxidized_copper_trapdoor_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_weathered_copper_bulb_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_weathered_copper_door_from_honeycomb.json
+ minecraft/advancement/recipes/redstone/waxed_weathered_copper_trapdoor_from_honeycomb.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/container/nautilus.png
+ minecraft/textures/gui/sprites/container/slot/nautilus_armor_inventory.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
+ One does not simply walk to the Far Lands
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Llama$Variant
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
+ XXX.animal.nautilus.AbstractNautilus
- XXX.animal.nautilus.Nautilus
+ XXX.animal.nautilus.NautilusAi
- XXX.animal.nautilus.package-info
- XXX.animal.nautilus.ZombieNautilus
+ XXX.animal.nautilus.ZombieNautilusAi
- XXX.animal.sheep.package-info
- XXX.animal.sheep.Sheep
+ XXX.animal.sheep.SheepColorSpawnRules
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
+ XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
+ XXX.animal.sniffer.SnifferAi$2
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.animal.wolf.package-info
- XXX.animal.wolf.Wolf
+ XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
- XXX.animal.wolf.Wolf$WolfPackData
+ XXX.animal.wolf.WolfSoundVariant
- XXX.animal.wolf.WolfSoundVariants
+ XXX.animal.wolf.WolfSoundVariants$SoundSet
- XXX.animal.wolf.WolfVariant
+ XXX.animal.wolf.WolfVariant$AssetInfo
- XXX.animal.wolf.WolfVariants
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPatternLayers
+ XXX.block.entity.BannerPatternLayers$Builder
- XXX.block.entity.BannerPatternLayers$Layer
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBeamOwner
- XXX.block.entity.BeaconBeamOwner$Section
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BeehiveBlockEntity$Occupant
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntity$1
+ XXX.block.entity.BlockEntity$BlockEntityPathElement
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BoundingBoxRenderable
- XXX.block.entity.BoundingBoxRenderable$Mode
+ XXX.block.entity.BoundingBoxRenderable$RenderableBox
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.CopperGolemStatueBlockEntity
+ XXX.block.entity.CrafterBlockEntity
- XXX.block.entity.CrafterBlockEntity$1
+ XXX.block.entity.CreakingHeartBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPattern
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantingTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FuelValues
+ XXX.block.entity.FuelValues$Builder
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.HangingSignBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.ListBackedContainer
+ XXX.block.entity.package-info
- XXX.block.entity.PotDecorations
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShelfBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TestBlockEntity
+ XXX.block.entity.TestInstanceBlockEntity
- XXX.block.entity.TestInstanceBlockEntity$1
+ XXX.block.entity.TestInstanceBlockEntity$Data
- XXX.block.entity.TestInstanceBlockEntity$ErrorMarker
+ XXX.block.entity.TestInstanceBlockEntity$Status
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
- XXX.block.entity.TrialSpawnerBlockEntity
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
- XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.sounds.AmbientDesertBlockSoundsPlayer
+ XXX.block.sounds.package-info
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetFunction
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chunk.status.ChunkDependencies
- XXX.chunk.status.ChunkPyramid
+ XXX.chunk.status.ChunkPyramid$Builder
- XXX.chunk.status.ChunkStatus
+ XXX.chunk.status.ChunkStatusTask
- XXX.chunk.status.ChunkStatusTasks
+ XXX.chunk.status.ChunkStep
- XXX.chunk.status.ChunkStep$Builder
+ XXX.chunk.status.ChunkType
+ XXX.chunk.status.package-info
- XXX.chunk.status.WorldGenContext
- XXX.chunk.storage.ChunkIOErrorReporter
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.IOWorker$ThrowingSupplier
+ XXX.chunk.storage.LegacyTagFixer
+ XXX.chunk.storage.package-info
- XXX.chunk.storage.RecreatingSimpleRegionStorage
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.RegionStorageInfo
+ XXX.chunk.storage.SectionStorage
- XXX.chunk.storage.SectionStorage$PackedChunk
+ XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$ChunkReadException
+ XXX.chunk.storage.SerializableChunkData$SectionData
- XXX.chunk.storage.SimpleRegionStorage
- XXX.crafting.display.DisplayContentsFactory
+ XXX.crafting.display.DisplayContentsFactory$ForRemainders
- XXX.crafting.display.DisplayContentsFactory$ForStacks
+ XXX.crafting.display.FurnaceRecipeDisplay
- XXX.crafting.display.package-info
- XXX.crafting.display.RecipeDisplay
+ XXX.crafting.display.RecipeDisplay$Type
- XXX.crafting.display.RecipeDisplayEntry
+ XXX.crafting.display.RecipeDisplayId
- XXX.crafting.display.RecipeDisplays
+ XXX.crafting.display.ShapedCraftingRecipeDisplay
- XXX.crafting.display.ShapelessCraftingRecipeDisplay
+ XXX.crafting.display.SlotDisplay
- XXX.crafting.display.SlotDisplay$AnyFuel
+ XXX.crafting.display.SlotDisplay$Composite
- XXX.crafting.display.SlotDisplay$Empty
+ XXX.crafting.display.SlotDisplay$ItemSlotDisplay
- XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
+ XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
- XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
+ XXX.crafting.display.SlotDisplay$TagSlotDisplay
- XXX.crafting.display.SlotDisplay$Type
+ XXX.crafting.display.SlotDisplay$WithRemainder
- XXX.crafting.display.SlotDisplayContext
+ XXX.crafting.display.SlotDisplays
- XXX.crafting.display.SmithingRecipeDisplay
+ XXX.crafting.display.StonecutterRecipeDisplay
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractBlockPropertyFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFieldFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributeIdPrefixFix
- XXX.datafix.fixes.AttributeModifierIdFix
+ XXX.datafix.fixes.AttributesRenameFix
- XXX.datafix.fixes.AttributesRenameLegacy
+ XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
- XXX.datafix.fixes.BannerPatternFormatFix
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehiveFieldRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockPropertyRenameAndFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.BoatSplitFix
- XXX.datafix.fixes.CarvingStepRemoveFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkDeleteLightFix
+ XXX.datafix.fixes.ChunkHeightAndBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkTicketUnpackPosFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
+ XXX.datafix.fixes.CopperGolemWeatherStateFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.CustomModelDataExpandFix
- XXX.datafix.fixes.DataComponentRemainderFix
+ XXX.datafix.fixes.DebugProfileOverlayReferenceFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GameRuleRegistryFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.InlineBlockPosFormatFix
- XXX.datafix.fixes.InvalidBlockEntityLockFix
+ XXX.datafix.fixes.InvalidLockComponentFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDimensionIdFix
+ XXX.datafix.fixes.LegacyDragonFightFix
- XXX.datafix.fixes.LegacyHoverEventFix
+ XXX.datafix.fixes.LegacyWorldBorderFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsFancyGraphicsToGraphicsModeFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsGraphicsModeSplitFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyEntityImpulse
+ XXX.enchantment.effects.ApplyExhaustion
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
+ XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.ScaleExponentially
+ XXX.enchantment.effects.SetBlockProperties
- XXX.enchantment.effects.SetValue
+ XXX.enchantment.effects.SpawnParticlesEffect
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
+ XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
- XXX.enchantment.effects.SummonEntityEffect
+ XXX.enchantment.providers.EnchantmentProvider
- XXX.enchantment.providers.EnchantmentProviderTypes
+ XXX.enchantment.providers.EnchantmentsByCost
- XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
- XXX.enchantment.providers.package-info
+ XXX.enchantment.providers.SingleEnchantment
- XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
+ XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.animal.package-info
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$ArmorStandPose
+ XXX.entity.decoration.BlockAttachedEntity
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Mannequin
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
+ XXX.entity.decoration.PaintingVariant
- XXX.entity.decoration.PaintingVariants
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
+ XXX.entity.item.PrimedTnt$1
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.Bogged
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Husk$HuskGroupData
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
- XXX.entity.monster.package-info
+ XXX.entity.monster.Parched
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Witch
+ XXX.entity.monster.WitherSkeleton
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.Abilities$Packed
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerEquipment
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.PlayerModelType
- XXX.entity.player.PlayerSkin
+ XXX.entity.player.PlayerSkin$Patch
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.package-info
- XXX.entity.trialspawner.package-info
- XXX.entity.trialspawner.PlayerDetector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
- XXX.entity.trialspawner.TrialSpawner
+ XXX.entity.trialspawner.TrialSpawner$FlameParticle
- XXX.entity.trialspawner.TrialSpawner$FullConfig
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerConfig$Builder
- XXX.entity.trialspawner.TrialSpawnerConfigs
+ XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
- XXX.entity.trialspawner.TrialSpawnerStateData
+ XXX.entity.trialspawner.TrialSpawnerStateData$Packed
- XXX.entity.variant.BiomeCheck
+ XXX.entity.variant.ModelAndTexture
- XXX.entity.variant.MoonBrightnessCheck
+ XXX.entity.variant.package-info
+ XXX.entity.variant.PriorityProvider
- XXX.entity.variant.PriorityProvider$Selector
+ XXX.entity.variant.PriorityProvider$SelectorCondition
- XXX.entity.variant.PriorityProvider$UnpackedEntry
+ XXX.entity.variant.SpawnCondition
- XXX.entity.variant.SpawnConditions
+ XXX.entity.variant.SpawnContext
- XXX.entity.variant.SpawnPrioritySelectors
+ XXX.entity.variant.StructureCheck
- XXX.entity.variant.VariantUtils
- XXX.entity.vault.package-info
+ XXX.entity.vault.VaultBlockEntity
- XXX.entity.vault.VaultBlockEntity$Client
+ XXX.entity.vault.VaultBlockEntity$Server
- XXX.entity.vault.VaultClientData
+ XXX.entity.vault.VaultConfig
- XXX.entity.vault.VaultServerData
+ XXX.entity.vault.VaultSharedData
- XXX.entity.vault.VaultState
+ XXX.entity.vault.VaultState$1
- XXX.entity.vault.VaultState$2
+ XXX.entity.vault.VaultState$3
- XXX.entity.vault.VaultState$4
+ XXX.entity.vault.VaultState$LightLevel
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.MaterialAssetGroup
- XXX.equipment.trim.MaterialAssetGroup$AssetInfo
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FallenTreeConfiguration
+ XXX.feature.configurations.FallenTreeConfiguration$FallenTreeConfigurationBuilder
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.CherryFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.package-info
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.AttachedToLeavesDecorator
- XXX.feature.treedecorators.AttachedToLogsDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.CreakingHeartDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.PaleMossDecorator
- XXX.feature.treedecorators.PlaceOnGroundDecorator
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.KineticWeapon
+ XXX.item.component.KineticWeapon$Condition
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
+ XXX.item.component.package-info
- XXX.item.component.PiercingWeapon
+ XXX.item.component.ProvidesTrimMaterial
- XXX.item.component.ResolvableProfile
+ XXX.item.component.ResolvableProfile$Dynamic
- XXX.item.component.ResolvableProfile$Partial
+ XXX.item.component.ResolvableProfile$Static
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SuspiciousStewEffects
- XXX.item.component.SuspiciousStewEffects$Entry
+ XXX.item.component.SwingAnimation
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.TypedEntityData
+ XXX.item.component.TypedEntityData$1
- XXX.item.component.UseCooldown
+ XXX.item.component.UseEffects
- XXX.item.component.UseRemainder
+ XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.component.Weapon
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect$Type
+ XXX.item.consume_effects.package-info
- XXX.item.consume_effects.PlaySoundConsumeEffect
+ XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
+ XXX.item.crafting.AbstractCookingRecipe$Serializer
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BlastingRecipe$1
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CraftingRecipe$1
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.CustomRecipe$Serializer
- XXX.item.crafting.CustomRecipe$Serializer$Factory
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.ExtendedRecipeBookCategory
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
+ XXX.item.crafting.PlacementInfo
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeAccess
- XXX.item.crafting.RecipeBookCategories
+ XXX.item.crafting.RecipeBookCategory
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeInput
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeManager$IngredientCollector
- XXX.item.crafting.RecipeManager$IngredientExtractor
+ XXX.item.crafting.RecipeManager$ServerDisplayInfo
- XXX.item.crafting.RecipeMap
+ XXX.item.crafting.RecipePropertySet
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.SelectableRecipe
+ XXX.item.crafting.SelectableRecipe$SingleInputEntry
- XXX.item.crafting.SelectableRecipe$SingleInputSet
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapedRecipePattern
- XXX.item.crafting.ShapedRecipePattern$Data
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Factory
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleRecipeInput
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmeltingRecipe$1
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingRecipeInput
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.TransmuteRecipe
- XXX.item.crafting.TransmuteRecipe$Serializer
+ XXX.item.crafting.TransmuteResult
- XXX.item.enchantment.ConditionalEffect
+ XXX.item.enchantment.Enchantable
- XXX.item.enchantment.EnchantedItemInUse
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$1
+ XXX.item.enchantment.Enchantment$Builder
- XXX.item.enchantment.Enchantment$Cost
+ XXX.item.enchantment.Enchantment$EnchantmentDefinition
- XXX.item.enchantment.EnchantmentEffectComponents
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.EnchantmentTarget
+ XXX.item.enchantment.ItemEnchantments
- XXX.item.enchantment.ItemEnchantments$Mutable
+ XXX.item.enchantment.LevelBasedValue
- XXX.item.enchantment.LevelBasedValue$Clamped
+ XXX.item.enchantment.LevelBasedValue$Constant
- XXX.item.enchantment.LevelBasedValue$Exponent
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
+ XXX.item.equipment.AllowedEntitiesProvider
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.slot.CompositeSlotSource
- XXX.item.slot.ContentsSlotSource
+ XXX.item.slot.EmptySlotSource
- XXX.item.slot.FilteredSlotSource
+ XXX.item.slot.GroupSlotSource
- XXX.item.slot.LimitSlotSource
+ XXX.item.slot.package-info
+ XXX.item.slot.RangeSlotSource
- XXX.item.slot.SlotCollection
+ XXX.item.slot.SlotCollection$Filtered
- XXX.item.slot.SlotCollection$FlatMapped
+ XXX.item.slot.SlotCollection$Limited
- XXX.item.slot.SlotSource
+ XXX.item.slot.SlotSources
- XXX.item.slot.TransformedSlotSource
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
- XXX.level.block.AmethystClusterBlock
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BambooStalkBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BaseRailBlock$1
- XXX.level.block.BaseTorchBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$ShapePairKey
+ XXX.level.block.Block$UpdateFlags
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$Type
- XXX.level.block.BonemealableFeaturePlacerBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.CactusBlock
+ XXX.level.block.CactusFlowerBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CalibratedSculkSensorBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
- XXX.level.block.CandleCakeBlock
+ XXX.level.block.CarpetBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.CaveVines
+ XXX.level.block.CaveVinesBlock
- XXX.level.block.CaveVinesPlantBlock
+ XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChiseledBookShelfBlock
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.ColoredFallingBlock
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CopperBulbBlock
- XXX.level.block.CopperChestBlock
+ XXX.level.block.CopperGolemStatueBlock
- XXX.level.block.CopperGolemStatueBlock$Pose
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CrafterBlock
- XXX.level.block.CrafterBlock$1
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CreakingHeartBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DirtPathBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoubleBlockCombiner
+ XXX.level.block.DoubleBlockCombiner$BlockType
- XXX.level.block.DoubleBlockCombiner$Combiner
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DriedGhastBlock
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.DryVegetationBlock
- XXX.level.block.EnchantingTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.EyeblossomBlock
- XXX.level.block.EyeblossomBlock$Type
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FireflyBushBlock
+ XXX.level.block.FlowerBedBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingMossBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HeavyCoreBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeafLitterBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.Mirror
- XXX.level.block.MossyCarpetBlock
+ XXX.level.block.MossyCarpetBlock$1
- XXX.level.block.MudBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MultifaceSpreadeableBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.package-info
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PipeBlock
+ XXX.level.block.PitcherCropBlock
- XXX.level.block.PitcherCropBlock$1
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$1
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.Portal
- XXX.level.block.Portal$Transition
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkBehaviour
+ XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkBlock
+ XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkSensorBlock
+ XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader
+ XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock
+ XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
- XXX.level.block.SegmentableBlock
+ XXX.level.block.SelectableSlotContainer
- XXX.level.block.SelectableSlotContainer$1
+ XXX.level.block.ShelfBlock
- XXX.level.block.ShortDryGrassBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SideChainPartBlock
- XXX.level.block.SideChainPartBlock$EmptyNeighbor
+ XXX.level.block.SideChainPartBlock$Neighbor
- XXX.level.block.SideChainPartBlock$Neighbors
+ XXX.level.block.SideChainPartBlock$SideChainNeighbor
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnifferEggBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SuspiciousEffectHolder
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallDryGrassBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TestBlock
- XXX.level.block.TestInstanceBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TintedParticleLeavesBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TorchflowerCropBlock
- XXX.level.block.TransparentBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TrialSpawnerBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.UntintedParticleLeavesBlock
- XXX.level.block.VaultBlock
+ XXX.level.block.VegetationBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WaterloggedTransparentBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperBarsBlock
- XXX.level.block.WeatheringCopperBlocks
+ XXX.level.block.WeatheringCopperBulbBlock
- XXX.level.block.WeatheringCopperChainBlock
+ XXX.level.block.WeatheringCopperChestBlock
- XXX.level.block.WeatheringCopperDoorBlock
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperGolemStatueBlock
+ XXX.level.block.WeatheringCopperGrateBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WeatheringCopperTrapDoorBlock
+ XXX.level.block.WeatheringLanternBlock
- XXX.level.block.WeatheringLightningRodBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$ChunkPathElement
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.Configuration
- XXX.level.chunk.Configuration$Global
+ XXX.level.chunk.Configuration$Simple
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunk$UnsavedListener
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunk
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainerFactory
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.Strategy
+ XXX.level.chunk.Strategy$1
- XXX.level.chunk.Strategy$2
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.DimensionType$CardinalLightType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.DimensionType$Skybox
- XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.EntityTypeTest$2
- XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetter
- XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.UniquelyIdentifyable
- XXX.level.entity.UUIDLookup
- XXX.level.entity.Visibility
- XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.BlockPositionSource$Type
- XXX.level.gameevent.DynamicGameEventListener
+ XXX.level.gameevent.EntityPositionSource
- XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry
- XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListener$Provider
- XXX.level.gameevent.GameEventListenerRegistry
+ XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
- XXX.level.gamerules.GameRule
+ XXX.level.gamerules.GameRuleCategory
- XXX.level.gamerules.GameRuleMap
+ XXX.level.gamerules.GameRuleMap$Builder
- XXX.level.gamerules.GameRules
+ XXX.level.gamerules.GameRules$VisitorCaller
- XXX.level.gamerules.GameRuleType
+ XXX.level.gamerules.GameRuleTypeVisitor
- XXX.level.gamerules.package-info
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$FindTopSurface
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
+ XXX.level.levelgen.WorldDimensions$1Entry
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.WorldOptions
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.ChunkSkyLightSources
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$SectionState
+ XXX.level.lighting.LayerLightSectionStorage$SectionType
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEngine
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.FlowingFluid$BlockStatePairKey
+ XXX.level.material.FlowingFluid$SpreadContext
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.Path$DebugData
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.PathfindingContext
- XXX.level.pathfinder.PathType
+ XXX.level.pathfinder.PathTypeCache
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator$1
- XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalShape
- XXX.level.portal.TeleportTransition
+ XXX.level.portal.TeleportTransition$PostTeleportTransition
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.DefaultRedstoneWireEvaluator
- XXX.level.redstone.ExperimentalRedstoneUtils
+ XXX.level.redstone.ExperimentalRedstoneWireEvaluator
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.Orientation
+ XXX.level.redstone.Orientation$SideBias
- XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.redstone.RedstoneWireEvaluator
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedDataType
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.FileNameDateFormatter
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelData$RespawnData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.TagValueInput
- XXX.level.storage.TagValueInput$CompoundListWrapper
+ XXX.level.storage.TagValueInput$CompoundListWrapper$1
- XXX.level.storage.TagValueInput$DecodeFromFieldFailedProblem
+ XXX.level.storage.TagValueInput$DecodeFromListFailedProblem
- XXX.level.storage.TagValueInput$DecodeFromMapFailedProblem
+ XXX.level.storage.TagValueInput$ListWrapper
- XXX.level.storage.TagValueInput$ListWrapper$1
+ XXX.level.storage.TagValueInput$TypedListWrapper
- XXX.level.storage.TagValueInput$TypedListWrapper$1
+ XXX.level.storage.TagValueInput$UnexpectedListElementTypeProblem
- XXX.level.storage.TagValueInput$UnexpectedNonNumberProblem
+ XXX.level.storage.TagValueInput$UnexpectedTypeProblem
- XXX.level.storage.TagValueOutput
+ XXX.level.storage.TagValueOutput$EncodeToFieldFailedProblem
- XXX.level.storage.TagValueOutput$EncodeToListFailedProblem
+ XXX.level.storage.TagValueOutput$EncodeToMapFailedProblem
- XXX.level.storage.TagValueOutput$ListWrapper
+ XXX.level.storage.TagValueOutput$TypedListWrapper
- XXX.level.storage.ValueInput
+ XXX.level.storage.ValueInput$TypedInputList
- XXX.level.storage.ValueInput$ValueInputList
+ XXX.level.storage.ValueInputContextHelper
- XXX.level.storage.ValueInputContextHelper$1
+ XXX.level.storage.ValueInputContextHelper$2
- XXX.level.storage.ValueInputContextHelper$3
+ XXX.level.storage.ValueOutput
- XXX.level.storage.ValueOutput$TypedOutputList
+ XXX.level.storage.ValueOutput$ValueOutputList
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.level.validation.ContentValidationException
- XXX.level.validation.DirectoryValidator
+ XXX.level.validation.DirectoryValidator$1
- XXX.level.validation.ForbiddenSymlinkInfo
- XXX.level.validation.package-info
+ XXX.level.validation.PathAllowList
- XXX.level.validation.PathAllowList$ConfigEntry
+ XXX.level.validation.PathAllowList$EntryType
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.BlendingData$Packed
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.UnobstructedPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPlatformFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.FallenTreeFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TreeFeature$1
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.FixedPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.Structure$StructureSettings$Builder
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$1
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.NestedLootTable
- XXX.loot.entries.NestedLootTable$1
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.SlotLoot
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyComponentsFunction
+ XXX.loot.functions.CopyComponentsFunction$BlockEntitySource
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$DirectSource
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.DiscardItem
+ XXX.loot.functions.EnchantedCountIncreaseFunction
- XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.FilteredFunction$Builder
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.ListOperation
- XXX.loot.functions.ListOperation$Append
+ XXX.loot.functions.ListOperation$Insert
- XXX.loot.functions.ListOperation$ReplaceAll
+ XXX.loot.functions.ListOperation$ReplaceSection
- XXX.loot.functions.ListOperation$StandAlone
+ XXX.loot.functions.ListOperation$Type
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.ModifyContainerContents
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
+ XXX.loot.functions.SetCustomModelDataFunction
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetFireworkExplosionFunction
+ XXX.loot.functions.SetFireworksFunction
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
+ XXX.loot.predicates.AllOfCondition$Builder
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.EnchantmentActiveCheck
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$1
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
+ XXX.minecraft.stats.ServerRecipeBook$Packed
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.DamageTypeTags
+ XXX.minecraft.tags.DialogTags
- XXX.minecraft.tags.EnchantmentTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$ElementLookup
- XXX.minecraft.tags.TagLoader$EntryWithSource
+ XXX.minecraft.tags.TagLoader$LoadResult
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TimelineTags
- XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.AbstractListBuilder
- XXX.minecraft.util.ARGB
- XXX.minecraft.util.ArrayListDeque
+ XXX.minecraft.util.ArrayListDeque$DescendingIterator
- XXX.minecraft.util.ArrayListDeque$ReversedView
+ XXX.minecraft.util.BinaryAnimator
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.BlockUtil
- XXX.minecraft.util.BlockUtil$FoundRectangle
+ XXX.minecraft.util.BlockUtil$IntBounds
- XXX.minecraft.util.BoundedFloatFunction
+ XXX.minecraft.util.BoundedFloatFunction$1
- XXX.minecraft.util.BoundedFloatFunction$2
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.ClassTreeIdRegistry
- XXX.minecraft.util.ColorRGBA
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DelegateDataOutput
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.Ease
+ XXX.minecraft.util.EasingType
- XXX.minecraft.util.EasingType$CubicBezier
+ XXX.minecraft.util.EasingType$CubicBezier$CubicCurve
- XXX.minecraft.util.EasingType$CubicBezierControls
+ XXX.minecraft.util.EncoderCache
- XXX.minecraft.util.EncoderCache$1
+ XXX.minecraft.util.EncoderCache$2
- XXX.minecraft.util.EncoderCache$Key
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$5
+ XXX.minecraft.util.ExtraCodecs$6
- XXX.minecraft.util.ExtraCodecs$7
+ XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
- XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FileSystemUtil
- XXX.minecraft.util.FileUtil
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.GsonHelper$CountedAppendable
- XXX.minecraft.util.HashOps
+ XXX.minecraft.util.HashOps$ListHashBuilder
- XXX.minecraft.util.HashOps$MapHashBuilder
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.IdentifierPattern
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.Keyframe
+ XXX.minecraft.util.KeyframeTrack
- XXX.minecraft.util.KeyframeTrack$Builder
+ XXX.minecraft.util.KeyframeTrackSampler
- XXX.minecraft.util.KeyframeTrackSampler$Segment
+ XXX.minecraft.util.LenientJsonParser
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.ListAndDeque
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.NullOps
- XXX.minecraft.util.NullOps$1
+ XXX.minecraft.util.NullOps$NullListBuilder
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.SegmentedAnglePrecision
+ XXX.minecraft.util.SequencedPriorityIterator
- XXX.minecraft.util.SignatureUpdater
+ XXX.minecraft.util.SignatureUpdater$Output
- XXX.minecraft.util.SignatureValidator
+ XXX.minecraft.util.Signer
- XXX.minecraft.util.SimpleBitStorage
+ XXX.minecraft.util.SimpleBitStorage$InitializationException
- XXX.minecraft.util.SingleKeyCache
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.SpawnUtil$Strategy
- XXX.minecraft.util.SpecialDates
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StrictJsonParser
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.Util
- XXX.minecraft.util.Util$1
+ XXX.minecraft.util.Util$10
- XXX.minecraft.util.Util$11
+ XXX.minecraft.util.Util$2
- XXX.minecraft.util.Util$3
+ XXX.minecraft.util.Util$4
- XXX.minecraft.util.Util$5
+ XXX.minecraft.util.Util$6
- XXX.minecraft.util.Util$7
+ XXX.minecraft.util.Util$8
- XXX.minecraft.util.Util$9
+ XXX.minecraft.util.Util$OS
- XXX.minecraft.util.Util$OS$1
+ XXX.minecraft.util.Util$OS$2
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.package-info
- XXX.monster.breeze.Breeze
+ XXX.monster.breeze.Breeze$1
- XXX.monster.breeze.BreezeAi
+ XXX.monster.breeze.BreezeAi$SlideToTargetSink
- XXX.monster.breeze.BreezeUtil
+ XXX.monster.breeze.LongJump
+ XXX.monster.breeze.package-info
- XXX.monster.breeze.Shoot
+ XXX.monster.breeze.ShootWhenStuck
- XXX.monster.breeze.Slide
- XXX.monster.creaking.Creaking
+ XXX.monster.creaking.Creaking$CreakingBodyRotationControl
- XXX.monster.creaking.Creaking$CreakingJumpControl
+ XXX.monster.creaking.Creaking$CreakingLookControl
- XXX.monster.creaking.Creaking$CreakingMoveControl
+ XXX.monster.creaking.Creaking$CreakingPathNavigation
- XXX.monster.creaking.Creaking$HomeNodeEvaluator
+ XXX.monster.creaking.CreakingAi
- XXX.monster.creaking.CreakingAi$1
+ XXX.monster.creaking.package-info
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$Empty
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.MinecartCollisionContext
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.pools.alias.DirectPoolAlias
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.RandomGroupPoolAlias
+ XXX.pools.alias.RandomPoolAlias
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$BlockEntitySource
+ XXX.providers.nbt.ContextNbtProvider$EntitySource
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.ConstantValue
+ XXX.providers.number.EnchantmentLevelProvider
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.server.permissions.package-info
- XXX.server.permissions.Permissions
- XXX.server.permissions.PermissionSetUnion
+ XXX.server.permissions.PermissionTypes
- XXX.server.players.BanListEntry
+ XXX.server.players.CachedUserNameToIdResolver
- XXX.server.players.CachedUserNameToIdResolver$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.NameAndId
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.PlayerList$2
- XXX.server.players.ProfileResolver
+ XXX.server.players.ProfileResolver$Cached
- XXX.server.players.ProfileResolver$Cached$1
+ XXX.server.players.ProfileResolver$Cached$2
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserNameToIdResolver
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.server.waypoints.package-info
+ XXX.server.waypoints.ServerWaypointManager
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockSetType
- XXX.state.properties.BlockSetType$PressurePlateSensitivity
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.CreakingHeartState
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SideChainPart
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.TestBlockMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators
+ XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$2
+ XXX.storage.loot.ContainerComponentManipulators$3
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$BlockEntityTarget
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$ItemStackTarget
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextArg
- XXX.storage.loot.LootContextArg$ArgCodecBuilder
+ XXX.storage.loot.LootContextArg$Getter
- XXX.storage.loot.LootContextArg$SimpleGetter
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootParams
+ XXX.storage.loot.LootParams$Builder
- XXX.storage.loot.LootParams$DynamicDrop
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
+ XXX.storage.loot.ValidationContext
- XXX.storage.loot.ValidationContext$MissingReferenceProblem
+ XXX.storage.loot.ValidationContext$ParametersNotProvidedProblem
- XXX.storage.loot.ValidationContext$RecursiveReferenceProblem
+ XXX.storage.loot.ValidationContext$ReferenceNotAllowedProblem
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.DimensionPadding
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JigsawStructure$MaxDistance
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.LiquidSettings
+ XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.context.ContextKey
+ XXX.util.context.ContextKeySet
- XXX.util.context.ContextKeySet$Builder
+ XXX.util.context.ContextMap
- XXX.util.context.ContextMap$Builder
+ XXX.util.context.package-info
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.datafix.PackedBitStorage
- XXX.world.entity.package-info
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.NautilusInventoryMenu$1
- XXX.world.inventory.NonInteractiveResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.RemoteSlot
+ XXX.world.inventory.RemoteSlot$1
- XXX.world.inventory.RemoteSlot$Synchronized
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SlotRange
- XXX.world.inventory.SlotRange$1
+ XXX.world.inventory.SlotRanges
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.inventory.TransientCraftingContainer
+ XXX.world.item.AdventureModePredicate
- XXX.world.item.AirItem
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.BundleItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.CrossbowItem$ChargeType
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
+ XXX.world.item.Item$TooltipContext$1
- XXX.world.item.Item$TooltipContext$2
+ XXX.world.item.Item$TooltipContext$3
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUseAnimation
- XXX.world.item.ItemUtils
- XXX.world.item.JukeboxPlayable
+ XXX.world.item.JukeboxSong
- XXX.world.item.JukeboxSongPlayer
+ XXX.world.item.JukeboxSongPlayer$OnSongChanged
- XXX.world.item.JukeboxSongs
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MaceItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
+ XXX.world.item.MinecartItem
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.package-info
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileItem
- XXX.world.item.ProjectileItem$DispenseConfig
+ XXX.world.item.ProjectileItem$DispenseConfig$Builder
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SwingAnimationType
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WeatheringCopperItems
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.LocalMobCapCalculator
+ XXX.world.level.LocalMobCapCalculator$MobCounts
- XXX.world.level.MoonPhase
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ScheduledTickAccess
+ XXX.world.level.ServerExplosion
- XXX.world.level.ServerExplosion$StackCollector
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SimpleExplosionDamageCalculator
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.TicketStorage
+ XXX.world.level.TicketStorage$ChunkUpdated
- XXX.world.level.TicketStorage$TicketPredicate
+ XXX.world.level.WorldDataConfiguration
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.AABB$Builder
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.phys.Vec3$1
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
- XXX.world.scores.Objective$Packed
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.PlayerTeam$Packed
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.Score$Packed
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.Scoreboard$PackedScore
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreboardSaveData$Packed
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
+ XXX.world.timeline.AttributeTrack
- XXX.world.timeline.AttributeTrackSampler
- XXX.world.timeline.package-info
+ XXX.world.timeline.Timeline
- XXX.world.timeline.Timeline$Builder
+ XXX.world.timeline.Timelines
- XXX.world.waypoints.package-info
+ XXX.world.waypoints.PartialTickSupplier
- XXX.world.waypoints.TrackedWaypoint
+ XXX.world.waypoints.TrackedWaypoint$AzimuthWaypoint
- XXX.world.waypoints.TrackedWaypoint$Camera
+ XXX.world.waypoints.TrackedWaypoint$ChunkWaypoint
- XXX.world.waypoints.TrackedWaypoint$EmptyWaypoint
+ XXX.world.waypoints.TrackedWaypoint$PitchDirection
- XXX.world.waypoints.TrackedWaypoint$Projector
+ XXX.world.waypoints.TrackedWaypoint$Type
- XXX.world.waypoints.TrackedWaypoint$Vec3iWaypoint
+ XXX.world.waypoints.TrackedWaypointManager
- XXX.world.waypoints.Waypoint
+ XXX.world.waypoints.Waypoint$Icon
- XXX.world.waypoints.WaypointManager
+ XXX.world.waypoints.WaypointStyleAsset
- XXX.world.waypoints.WaypointStyleAssets
+ XXX.world.waypoints.WaypointTransmitter
- XXX.world.waypoints.WaypointTransmitter$BlockConnection
+ XXX.world.waypoints.WaypointTransmitter$ChunkConnection
- XXX.world.waypoints.WaypointTransmitter$Connection
+ XXX.world.waypoints.WaypointTransmitter$EntityAzimuthConnection
- XXX.world.waypoints.WaypointTransmitter$EntityBlockConnection
+ XXX.world.waypoints.WaypointTransmitter$EntityChunkConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.BlockPos -1P
```
```
XXX.gametest.framework.GameTestHelper +2M -1M
```
```
XXX.protocol.game.GamePacketTypes +1P -1P
```
```
XXX.server.level.ServerPlayer +1M
```
```
XXX.server.permissions.LevelBasedPermissionSet +1M
```
```
XXX.server.permissions.PermissionSet -1M
```
```
XXX.world.effect.MobEffectUtil +1M
```
```
XXX.ai.behavior.ChargeAttack +1M -1M | +1P
```
```
XXX.animal.camel.CamelAi$CamelPanic +3M
```
```
XXX.animal.camel.CamelHusk +1M
```
```
XXX.animal.frog.ShootTongue -1P
```
```
XXX.animal.horse.AbstractHorse -1M
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- Direction getAbsoluteDirection(Direction)
+ void assertEntityPosition(Entity,AABB,Component)
- void assertEntityPresent(EntityType,AABB,Component)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void openNautilusInventory(AbstractNautilus,Container)
```

</details>
<details>
<summary>
net.minecraft.server.permissions.LevelBasedPermissionSet
</summary>

```diff
- PermissionSet union(PermissionSet)
```

</details>
<details>
<summary>
net.minecraft.server.permissions.PermissionSet
</summary>

```diff
+ boolean lambda$union$2(PermissionSet,Permission)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectUtil
</summary>

```diff
- boolean shouldEffectsRefillAirsupply(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.ChargeAttack
</summary>

```diff
- void <init>(int,TargetingConditions,float,float,double,double,SoundEvent)
+ void <init>(int,TargetingConditions,float,float,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
</summary>

```diff
- boolean checkExtraStartConditions(ServerLevel,Camel)
- boolean checkExtraStartConditions(ServerLevel,LivingEntity)
- boolean checkExtraStartConditions(ServerLevel,PathfinderMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.CamelHusk
</summary>

```diff
- boolean canFallInLove()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ int getInventorySize(int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.IdentifierException
+ net.minecraft.Optionull
+ net.minecraft.ReportedException
- net.minecraft.ReportType
- net.minecraft.SharedConstants
+ net.minecraft.SuppressForbidden
- net.minecraft.SystemReport
+ net.minecraft.TracingExecutor
- net.minecraft.WorldVersion
+ net.minecraft.WorldVersion$1
- net.minecraft.WorldVersion$Simple
+ XXX.advancements.criterion.AnyBlockInteractionTrigger
- XXX.advancements.criterion.AnyBlockInteractionTrigger$TriggerInstance
+ XXX.advancements.criterion.BeeNestDestroyedTrigger
- XXX.advancements.criterion.BeeNestDestroyedTrigger$TriggerInstance
+ XXX.advancements.criterion.BlockPredicate
- XXX.advancements.criterion.BlockPredicate$Builder
+ XXX.advancements.criterion.BredAnimalsTrigger
- XXX.advancements.criterion.BredAnimalsTrigger$TriggerInstance
+ XXX.advancements.criterion.BrewedPotionTrigger
- XXX.advancements.criterion.BrewedPotionTrigger$TriggerInstance
+ XXX.advancements.criterion.ChangeDimensionTrigger
- XXX.advancements.criterion.ChangeDimensionTrigger$TriggerInstance
+ XXX.advancements.criterion.ChanneledLightningTrigger
- XXX.advancements.criterion.ChanneledLightningTrigger$TriggerInstance
+ XXX.advancements.criterion.CollectionContentsPredicate
- XXX.advancements.criterion.CollectionContentsPredicate$Multiple
+ XXX.advancements.criterion.CollectionContentsPredicate$Single
- XXX.advancements.criterion.CollectionContentsPredicate$Zero
+ XXX.advancements.criterion.CollectionCountsPredicate
- XXX.advancements.criterion.CollectionCountsPredicate$Entry
+ XXX.advancements.criterion.CollectionCountsPredicate$Multiple
- XXX.advancements.criterion.CollectionCountsPredicate$Single
+ XXX.advancements.criterion.CollectionCountsPredicate$Zero
- XXX.advancements.criterion.CollectionPredicate
+ XXX.advancements.criterion.ConstructBeaconTrigger
- XXX.advancements.criterion.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.criterion.ConsumeItemTrigger
- XXX.advancements.criterion.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.criterion.ContextAwarePredicate
- XXX.advancements.criterion.CriterionValidator
+ XXX.advancements.criterion.CuredZombieVillagerTrigger
- XXX.advancements.criterion.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.criterion.DamagePredicate
- XXX.advancements.criterion.DamagePredicate$Builder
+ XXX.advancements.criterion.DamageSourcePredicate
- XXX.advancements.criterion.DamageSourcePredicate$Builder
+ XXX.advancements.criterion.DataComponentMatchers
- XXX.advancements.criterion.DataComponentMatchers$Builder
+ XXX.advancements.criterion.DefaultBlockInteractionTrigger
- XXX.advancements.criterion.DefaultBlockInteractionTrigger$TriggerInstance
+ XXX.advancements.criterion.DistancePredicate
- XXX.advancements.criterion.DistanceTrigger
+ XXX.advancements.criterion.DistanceTrigger$TriggerInstance
- XXX.advancements.criterion.EffectsChangedTrigger
+ XXX.advancements.criterion.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.criterion.EnchantedItemTrigger
+ XXX.advancements.criterion.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.criterion.EnchantmentPredicate
+ XXX.advancements.criterion.EnterBlockTrigger
- XXX.advancements.criterion.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.criterion.EntityEquipmentPredicate
- XXX.advancements.criterion.EntityEquipmentPredicate$Builder
+ XXX.advancements.criterion.EntityFlagsPredicate
- XXX.advancements.criterion.EntityFlagsPredicate$Builder
+ XXX.advancements.criterion.EntityHurtPlayerTrigger
- XXX.advancements.criterion.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.criterion.EntityPredicate
- XXX.advancements.criterion.EntityPredicate$Builder
+ XXX.advancements.criterion.EntityPredicate$LocationWrapper
- XXX.advancements.criterion.EntitySubPredicate
+ XXX.advancements.criterion.EntitySubPredicates
- XXX.advancements.criterion.EntityTypePredicate
+ XXX.advancements.criterion.FallAfterExplosionTrigger
- XXX.advancements.criterion.FallAfterExplosionTrigger$TriggerInstance
+ XXX.advancements.criterion.FilledBucketTrigger
- XXX.advancements.criterion.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.criterion.FishingHookPredicate
- XXX.advancements.criterion.FishingRodHookedTrigger
+ XXX.advancements.criterion.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.criterion.FluidPredicate
+ XXX.advancements.criterion.FluidPredicate$Builder
- XXX.advancements.criterion.GameTypePredicate
+ XXX.advancements.criterion.ImpossibleTrigger
- XXX.advancements.criterion.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.criterion.InputPredicate
- XXX.advancements.criterion.InventoryChangeTrigger
+ XXX.advancements.criterion.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.criterion.InventoryChangeTrigger$TriggerInstance$Slots
+ XXX.advancements.criterion.ItemDurabilityTrigger
- XXX.advancements.criterion.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.criterion.ItemPredicate
- XXX.advancements.criterion.ItemPredicate$Builder
+ XXX.advancements.criterion.ItemUsedOnLocationTrigger
- XXX.advancements.criterion.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.criterion.KilledByArrowTrigger
- XXX.advancements.criterion.KilledByArrowTrigger$TriggerInstance
+ XXX.advancements.criterion.KilledTrigger
- XXX.advancements.criterion.KilledTrigger$TriggerInstance
+ XXX.advancements.criterion.LevitationTrigger
- XXX.advancements.criterion.LevitationTrigger$TriggerInstance
+ XXX.advancements.criterion.LightningBoltPredicate
- XXX.advancements.criterion.LightningStrikeTrigger
+ XXX.advancements.criterion.LightningStrikeTrigger$TriggerInstance
+ XXX.advancements.criterion.LightPredicate
- XXX.advancements.criterion.LightPredicate$Builder
- XXX.advancements.criterion.LocationPredicate
+ XXX.advancements.criterion.LocationPredicate$Builder
- XXX.advancements.criterion.LocationPredicate$PositionPredicate
+ XXX.advancements.criterion.LootTableTrigger
- XXX.advancements.criterion.LootTableTrigger$TriggerInstance
+ XXX.advancements.criterion.MinMaxBounds
- XXX.advancements.criterion.MinMaxBounds$Bounds
+ XXX.advancements.criterion.MinMaxBounds$Bounds$1
- XXX.advancements.criterion.MinMaxBounds$Doubles
+ XXX.advancements.criterion.MinMaxBounds$FloatDegrees
- XXX.advancements.criterion.MinMaxBounds$Ints
+ XXX.advancements.criterion.MobEffectsPredicate
- XXX.advancements.criterion.MobEffectsPredicate$Builder
+ XXX.advancements.criterion.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.criterion.MovementPredicate
+ XXX.advancements.criterion.NbtPredicate
- XXX.advancements.criterion.package-info
- XXX.advancements.criterion.PickedUpItemTrigger
+ XXX.advancements.criterion.PickedUpItemTrigger$TriggerInstance
- XXX.advancements.criterion.PlayerHurtEntityTrigger
+ XXX.advancements.criterion.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.criterion.PlayerInteractTrigger
+ XXX.advancements.criterion.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.criterion.PlayerPredicate
+ XXX.advancements.criterion.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.criterion.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.criterion.PlayerPredicate$AdvancementPredicate
- XXX.advancements.criterion.PlayerPredicate$Builder
+ XXX.advancements.criterion.PlayerPredicate$StatMatcher
- XXX.advancements.criterion.PlayerTrigger
+ XXX.advancements.criterion.PlayerTrigger$TriggerInstance
- XXX.advancements.criterion.RaiderPredicate
+ XXX.advancements.criterion.RecipeCraftedTrigger
- XXX.advancements.criterion.RecipeCraftedTrigger$TriggerInstance
+ XXX.advancements.criterion.RecipeUnlockedTrigger
- XXX.advancements.criterion.RecipeUnlockedTrigger$TriggerInstance
+ XXX.advancements.criterion.SheepPredicate
- XXX.advancements.criterion.ShotCrossbowTrigger
+ XXX.advancements.criterion.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.criterion.SimpleCriterionTrigger
+ XXX.advancements.criterion.SimpleCriterionTrigger$SimpleInstance
- XXX.advancements.criterion.SingleComponentItemPredicate
+ XXX.advancements.criterion.SlideDownBlockTrigger
- XXX.advancements.criterion.SlideDownBlockTrigger$TriggerInstance
+ XXX.advancements.criterion.SlimePredicate
- XXX.advancements.criterion.SlotsPredicate
+ XXX.advancements.criterion.SpearMobsTrigger
- XXX.advancements.criterion.SpearMobsTrigger$TriggerInstance
+ XXX.advancements.criterion.StartRidingTrigger
- XXX.advancements.criterion.StartRidingTrigger$TriggerInstance
+ XXX.advancements.criterion.StatePropertiesPredicate
- XXX.advancements.criterion.StatePropertiesPredicate$Builder
+ XXX.advancements.criterion.StatePropertiesPredicate$ExactMatcher
- XXX.advancements.criterion.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.criterion.StatePropertiesPredicate$RangedMatcher
- XXX.advancements.criterion.StatePropertiesPredicate$ValueMatcher
+ XXX.advancements.criterion.SummonedEntityTrigger
- XXX.advancements.criterion.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.criterion.TagPredicate
- XXX.advancements.criterion.TameAnimalTrigger
+ XXX.advancements.criterion.TameAnimalTrigger$TriggerInstance
- XXX.advancements.criterion.TargetBlockTrigger
+ XXX.advancements.criterion.TargetBlockTrigger$TriggerInstance
- XXX.advancements.criterion.TradeTrigger
+ XXX.advancements.criterion.TradeTrigger$TriggerInstance
- XXX.advancements.criterion.UsedEnderEyeTrigger
+ XXX.advancements.criterion.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.criterion.UsedTotemTrigger
+ XXX.advancements.criterion.UsedTotemTrigger$TriggerInstance
- XXX.advancements.criterion.UsingItemTrigger
+ XXX.advancements.criterion.UsingItemTrigger$TriggerInstance
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Llama$Variant
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
+ XXX.animal.nautilus.AbstractNautilus
- XXX.animal.nautilus.Nautilus
+ XXX.animal.nautilus.NautilusAi
- XXX.animal.nautilus.package-info
- XXX.animal.nautilus.ZombieNautilus
+ XXX.animal.nautilus.ZombieNautilusAi
- XXX.animal.sheep.package-info
- XXX.animal.sheep.Sheep
+ XXX.animal.sheep.SheepColorSpawnRules
- XXX.animal.sheep.SheepColorSpawnRules$SheepColorProvider
+ XXX.animal.sheep.SheepColorSpawnRules$SheepColorSpawnConfiguration
+ XXX.animal.sniffer.package-info
+ XXX.animal.sniffer.Sniffer
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
+ XXX.animal.sniffer.SnifferAi$2
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.animal.wolf.package-info
- XXX.animal.wolf.Wolf
+ XXX.animal.wolf.Wolf$WolfAvoidEntityGoal
- XXX.animal.wolf.Wolf$WolfPackData
+ XXX.animal.wolf.WolfSoundVariant
- XXX.animal.wolf.WolfSoundVariants
+ XXX.animal.wolf.WolfSoundVariants$SoundSet
- XXX.animal.wolf.WolfVariant
+ XXX.animal.wolf.WolfVariant$AssetInfo
- XXX.animal.wolf.WolfVariants
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPatternLayers
+ XXX.block.entity.BannerPatternLayers$Builder
- XXX.block.entity.BannerPatternLayers$Layer
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBeamOwner
- XXX.block.entity.BeaconBeamOwner$Section
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BeehiveBlockEntity$Occupant
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntity$1
+ XXX.block.entity.BlockEntity$BlockEntityPathElement
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BoundingBoxRenderable
- XXX.block.entity.BoundingBoxRenderable$Mode
+ XXX.block.entity.BoundingBoxRenderable$RenderableBox
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.CopperGolemStatueBlockEntity
+ XXX.block.entity.CrafterBlockEntity
- XXX.block.entity.CrafterBlockEntity$1
+ XXX.block.entity.CreakingHeartBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ XXX.block.entity.DecoratedPotPattern
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantingTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FuelValues
+ XXX.block.entity.FuelValues$Builder
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.HangingSignBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.ListBackedContainer
+ XXX.block.entity.package-info
- XXX.block.entity.PotDecorations
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShelfBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TestBlockEntity
+ XXX.block.entity.TestInstanceBlockEntity
- XXX.block.entity.TestInstanceBlockEntity$1
+ XXX.block.entity.TestInstanceBlockEntity$Data
- XXX.block.entity.TestInstanceBlockEntity$ErrorMarker
+ XXX.block.entity.TestInstanceBlockEntity$Status
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
- XXX.block.entity.TrialSpawnerBlockEntity
- XXX.block.grower.package-info
+ XXX.block.grower.TreeGrower
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementFace$UVs
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockElementRotation$EulerXYZRotation
- XXX.block.model.BlockElementRotation$SingleAxisRotation
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$MultiPartDefinition
+ XXX.block.model.BlockModelDefinition$SimpleModelSelectors
- XXX.block.model.BlockModelPart
+ XXX.block.model.BlockModelPart$Unbaked
- XXX.block.model.BlockStateModel
+ XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot
- XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot$1
+ XXX.block.model.BlockStateModel$Unbaked
- XXX.block.model.BlockStateModel$UnbakedRoot
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$SideDirection
+ XXX.block.model.ItemModelGenerator$SideFace
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.package-info
+ XXX.block.model.SimpleModelWrapper
- XXX.block.model.SimpleUnbakedGeometry
+ XXX.block.model.SingleVariant
- XXX.block.model.SingleVariant$Unbaked
+ XXX.block.model.TextureSlots
- XXX.block.model.TextureSlots$Data
+ XXX.block.model.TextureSlots$Data$Builder
- XXX.block.model.TextureSlots$Reference
+ XXX.block.model.TextureSlots$Resolver
- XXX.block.model.TextureSlots$SlotContents
+ XXX.block.model.TextureSlots$Value
- XXX.block.model.Variant
+ XXX.block.model.Variant$SimpleModelState
- XXX.block.model.VariantMutator
+ XXX.block.model.VariantMutator$VariantProperty
- XXX.block.model.VariantSelector
- XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.sounds.AmbientDesertBlockSoundsPlayer
+ XXX.block.sounds.package-info
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetFunction
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
- XXX.blockentity.state.BannerRenderState
+ XXX.blockentity.state.BeaconRenderState
- XXX.blockentity.state.BeaconRenderState$Section
+ XXX.blockentity.state.BedRenderState
- XXX.blockentity.state.BellRenderState
+ XXX.blockentity.state.BlockEntityRenderState
- XXX.blockentity.state.BlockEntityWithBoundingBoxRenderState
+ XXX.blockentity.state.BlockEntityWithBoundingBoxRenderState$InvisibleBlockType
- XXX.blockentity.state.BrushableBlockRenderState
+ XXX.blockentity.state.CampfireRenderState
- XXX.blockentity.state.ChestRenderState
+ XXX.blockentity.state.ChestRenderState$ChestMaterialType
- XXX.blockentity.state.CondiutRenderState
+ XXX.blockentity.state.CopperGolemStatueRenderState
- XXX.blockentity.state.DecoratedPotRenderState
+ XXX.blockentity.state.EnchantTableRenderState
- XXX.blockentity.state.EndGatewayRenderState
+ XXX.blockentity.state.EndPortalRenderState
- XXX.blockentity.state.LecternRenderState
+ XXX.blockentity.state.package-info
+ XXX.blockentity.state.PistonHeadRenderState
- XXX.blockentity.state.ShelfRenderState
+ XXX.blockentity.state.ShulkerBoxRenderState
- XXX.blockentity.state.SignRenderState
+ XXX.blockentity.state.SkullBlockRenderState
- XXX.blockentity.state.SpawnerRenderState
+ XXX.blockentity.state.TestInstanceRenderState
- XXX.blockentity.state.VaultRenderState
+ XXX.boss.enderdragon.DragonFlightHistory
- XXX.boss.enderdragon.DragonFlightHistory$Sample
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chunk.status.ChunkDependencies
- XXX.chunk.status.ChunkPyramid
+ XXX.chunk.status.ChunkPyramid$Builder
- XXX.chunk.status.ChunkStatus
+ XXX.chunk.status.ChunkStatusTask
- XXX.chunk.status.ChunkStatusTasks
+ XXX.chunk.status.ChunkStep
- XXX.chunk.status.ChunkStep$Builder
+ XXX.chunk.status.ChunkType
+ XXX.chunk.status.package-info
- XXX.chunk.status.WorldGenContext
- XXX.chunk.storage.ChunkIOErrorReporter
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.IOWorker$ThrowingSupplier
+ XXX.chunk.storage.LegacyTagFixer
+ XXX.chunk.storage.package-info
- XXX.chunk.storage.RecreatingSimpleRegionStorage
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.RegionStorageInfo
+ XXX.chunk.storage.SectionStorage
- XXX.chunk.storage.SectionStorage$PackedChunk
+ XXX.chunk.storage.SerializableChunkData
- XXX.chunk.storage.SerializableChunkData$ChunkReadException
+ XXX.chunk.storage.SerializableChunkData$SectionData
- XXX.chunk.storage.SimpleRegionStorage
- XXX.client.renderer.LevelTargetBundle
+ XXX.client.renderer.LightTexture
+ XXX.client.renderer.MappableRingBuffer
- XXX.client.renderer.MapRenderer
- XXX.client.renderer.MaterialMapper
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.Octree
- XXX.client.renderer.Octree$AxisSorting
+ XXX.client.renderer.Octree$Branch
- XXX.client.renderer.Octree$Leaf
+ XXX.client.renderer.Octree$Node
- XXX.client.renderer.Octree$OctreeVisitor
+ XXX.client.renderer.OrderedSubmitNodeCollector
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PanoramicScreenshotParameters
- XXX.client.renderer.PerspectiveProjectionMatrixBuffer
+ XXX.client.renderer.PlayerSkinRenderCache
- XXX.client.renderer.PlayerSkinRenderCache$1
+ XXX.client.renderer.PlayerSkinRenderCache$2
- XXX.client.renderer.PlayerSkinRenderCache$RenderInfo
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostChain$TargetBundle
+ XXX.client.renderer.PostChain$TargetBundle$1
- XXX.client.renderer.PostChainConfig
+ XXX.client.renderer.PostChainConfig$Input
- XXX.client.renderer.PostChainConfig$InternalTarget
+ XXX.client.renderer.PostChainConfig$Pass
- XXX.client.renderer.PostChainConfig$TargetInput
+ XXX.client.renderer.PostChainConfig$TextureInput
- XXX.client.renderer.PostPass
+ XXX.client.renderer.PostPass$Input
- XXX.client.renderer.PostPass$InputTexture
+ XXX.client.renderer.PostPass$TargetInput
- XXX.client.renderer.PostPass$TextureInput
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderPipelines
- XXX.client.renderer.RunningTrimmedMean
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.SectionBufferBuilderPack
+ XXX.client.renderer.SectionBufferBuilderPool
- XXX.client.renderer.SectionOcclusionGraph
+ XXX.client.renderer.SectionOcclusionGraph$GraphEvents
- XXX.client.renderer.SectionOcclusionGraph$GraphState
+ XXX.client.renderer.SectionOcclusionGraph$GraphStorage
- XXX.client.renderer.SectionOcclusionGraph$Node
+ XXX.client.renderer.SectionOcclusionGraph$SectionToNodeMap
- XXX.client.renderer.ShaderDefines
+ XXX.client.renderer.ShaderDefines$Builder
- XXX.client.renderer.ShaderManager
+ XXX.client.renderer.ShaderManager$1
- XXX.client.renderer.ShaderManager$CompilationCache
+ XXX.client.renderer.ShaderManager$CompilationException
- XXX.client.renderer.ShaderManager$Configs
+ XXX.client.renderer.ShaderManager$ShaderSourceKey
- XXX.client.renderer.ShapeRenderer
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SkyRenderer
- XXX.client.renderer.SpecialBlockModelRenderer
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.SubmitNodeCollection
+ XXX.client.renderer.SubmitNodeCollector
- XXX.client.renderer.SubmitNodeCollector$CustomGeometryRenderer
+ XXX.client.renderer.SubmitNodeCollector$ParticleGroupRenderer
- XXX.client.renderer.SubmitNodeStorage
+ XXX.client.renderer.SubmitNodeStorage$BlockModelSubmit
- XXX.client.renderer.SubmitNodeStorage$BlockSubmit
+ XXX.client.renderer.SubmitNodeStorage$CustomGeometrySubmit
- XXX.client.renderer.SubmitNodeStorage$FlameSubmit
+ XXX.client.renderer.SubmitNodeStorage$ItemSubmit
- XXX.client.renderer.SubmitNodeStorage$LeashSubmit
+ XXX.client.renderer.SubmitNodeStorage$ModelPartSubmit
- XXX.client.renderer.SubmitNodeStorage$ModelSubmit
+ XXX.client.renderer.SubmitNodeStorage$MovingBlockSubmit
- XXX.client.renderer.SubmitNodeStorage$NameTagSubmit
+ XXX.client.renderer.SubmitNodeStorage$ShadowSubmit
- XXX.client.renderer.SubmitNodeStorage$TextSubmit
+ XXX.client.renderer.SubmitNodeStorage$TranslucentModelSubmit
- XXX.client.renderer.UniformValue
+ XXX.client.renderer.UniformValue$FloatUniform
+ XXX.client.renderer.UniformValue$IntUniform
- XXX.client.renderer.UniformValue$IVec3Uniform
- XXX.client.renderer.UniformValue$Matrix4x4Uniform
+ XXX.client.renderer.UniformValue$Type
- XXX.client.renderer.UniformValue$Vec2Uniform
+ XXX.client.renderer.UniformValue$Vec3Uniform
- XXX.client.renderer.UniformValue$Vec4Uniform
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.client.renderer.WeatherEffectRenderer
- XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
+ XXX.client.renderer.WorldBorderRenderer
- XXX.components.debug.DebugEntryBiome
+ XXX.components.debug.DebugEntryCategory
- XXX.components.debug.DebugEntryChunkGeneration
+ XXX.components.debug.DebugEntryChunkRenderStats
- XXX.components.debug.DebugEntryChunkSourceStats
+ XXX.components.debug.DebugEntryEntityRenderStats
- XXX.components.debug.DebugEntryFps
+ XXX.components.debug.DebugEntryGpuUtilization
- XXX.components.debug.DebugEntryHeightmap
+ XXX.components.debug.DebugEntryLight
- XXX.components.debug.DebugEntryLocalDifficulty
+ XXX.components.debug.DebugEntryLookingAtBlock
- XXX.components.debug.DebugEntryLookingAtEntity
+ XXX.components.debug.DebugEntryLookingAtFluid
- XXX.components.debug.DebugEntryMemory
+ XXX.components.debug.DebugEntryMemory$AllocationRateCalculator
- XXX.components.debug.DebugEntryNoop
+ XXX.components.debug.DebugEntryParticleRenderStats
- XXX.components.debug.DebugEntryPosition
+ XXX.components.debug.DebugEntryPosition$1
- XXX.components.debug.DebugEntryPostEffect
+ XXX.components.debug.DebugEntrySectionPosition
- XXX.components.debug.DebugEntrySimplePerformanceImpactors
+ XXX.components.debug.DebugEntrySoundMood
- XXX.components.debug.DebugEntrySpawnCounts
+ XXX.components.debug.DebugEntrySystemSpecs
- XXX.components.debug.DebugEntryTps
+ XXX.components.debug.DebugEntryVersion
- XXX.components.debug.DebugScreenDisplayer
+ XXX.components.debug.DebugScreenEntries
- XXX.components.debug.DebugScreenEntry
+ XXX.components.debug.DebugScreenEntryList
- XXX.components.debug.DebugScreenEntryList$SerializedOptions
+ XXX.components.debug.DebugScreenEntryStatus
- XXX.components.debug.DebugScreenProfile
+ XXX.components.debug.package-info
- XXX.components.debugchart.AbstractDebugChart
+ XXX.components.debugchart.BandwidthDebugChart
- XXX.components.debugchart.FpsDebugChart
- XXX.components.debugchart.package-info
+ XXX.components.debugchart.PingDebugChart
- XXX.components.debugchart.ProfilerPieChart
+ XXX.components.debugchart.TpsDebugChart
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.tabs.GridLayoutTab
+ XXX.components.tabs.LoadingTab
- XXX.components.tabs.package-info
- XXX.components.tabs.Tab
+ XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar
+ XXX.components.tabs.TabNavigationBar$Builder
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.NowPlayingToast
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.RecipeToast$Entry
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastId
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastManager
- XXX.components.toasts.ToastManager$1
- XXX.crafting.display.DisplayContentsFactory
+ XXX.crafting.display.DisplayContentsFactory$ForRemainders
- XXX.crafting.display.DisplayContentsFactory$ForStacks
+ XXX.crafting.display.FurnaceRecipeDisplay
- XXX.crafting.display.package-info
- XXX.crafting.display.RecipeDisplay
+ XXX.crafting.display.RecipeDisplay$Type
- XXX.crafting.display.RecipeDisplayEntry
+ XXX.crafting.display.RecipeDisplayId
- XXX.crafting.display.RecipeDisplays
+ XXX.crafting.display.ShapedCraftingRecipeDisplay
- XXX.crafting.display.ShapelessCraftingRecipeDisplay
+ XXX.crafting.display.SlotDisplay
- XXX.crafting.display.SlotDisplay$AnyFuel
+ XXX.crafting.display.SlotDisplay$Composite
- XXX.crafting.display.SlotDisplay$Empty
+ XXX.crafting.display.SlotDisplay$ItemSlotDisplay
- XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
+ XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
- XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
+ XXX.crafting.display.SlotDisplay$TagSlotDisplay
- XXX.crafting.display.SlotDisplay$Type
+ XXX.crafting.display.SlotDisplay$WithRemainder
- XXX.crafting.display.SlotDisplayContext
+ XXX.crafting.display.SlotDisplays
- XXX.crafting.display.SmithingRecipeDisplay
+ XXX.crafting.display.StonecutterRecipeDisplay
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractBlockPropertyFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFieldFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
- XXX.datafix.fixes.AreaEffectCloudPotionFix
+ XXX.datafix.fixes.AttributeIdPrefixFix
- XXX.datafix.fixes.AttributeModifierIdFix
+ XXX.datafix.fixes.AttributesRenameFix
- XXX.datafix.fixes.AttributesRenameLegacy
+ XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
- XXX.datafix.fixes.BannerPatternFormatFix
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehiveFieldRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockPosFormatAndRenamesFix
- XXX.datafix.fixes.BlockPropertyRenameAndFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.BoatSplitFix
- XXX.datafix.fixes.CarvingStepRemoveFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkDeleteLightFix
+ XXX.datafix.fixes.ChunkHeightAndBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkTicketUnpackPosFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
+ XXX.datafix.fixes.CopperGolemWeatherStateFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.CustomModelDataExpandFix
- XXX.datafix.fixes.DataComponentRemainderFix
+ XXX.datafix.fixes.DebugProfileOverlayReferenceFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GameRuleRegistryFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.InlineBlockPosFormatFix
- XXX.datafix.fixes.InvalidBlockEntityLockFix
+ XXX.datafix.fixes.InvalidLockComponentFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackComponentizationFix
- XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTagRemainderFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LegacyDimensionIdFix
+ XXX.datafix.fixes.LegacyDragonFightFix
- XXX.datafix.fixes.LegacyHoverEventFix
+ XXX.datafix.fixes.LegacyWorldBorderFix
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsFancyGraphicsToGraphicsModeFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsGraphicsModeSplitFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyEntityImpulse
+ XXX.enchantment.effects.ApplyExhaustion
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
+ XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.ScaleExponentially
+ XXX.enchantment.effects.SetBlockProperties
- XXX.enchantment.effects.SetValue
+ XXX.enchantment.effects.SpawnParticlesEffect
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
+ XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
- XXX.enchantment.effects.SummonEntityEffect
+ XXX.enchantment.providers.EnchantmentProvider
- XXX.enchantment.providers.EnchantmentProviderTypes
+ XXX.enchantment.providers.EnchantmentsByCost
- XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
- XXX.enchantment.providers.package-info
+ XXX.enchantment.providers.SingleEnchantment
- XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
+ XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.animal.package-info
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$ArmorStandPose
+ XXX.entity.decoration.BlockAttachedEntity
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Mannequin
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
+ XXX.entity.decoration.PaintingVariant
- XXX.entity.decoration.PaintingVariants
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
+ XXX.entity.item.PrimedTnt$1
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.BlockDecorationLayer
- XXX.entity.layers.BreezeEyesLayer
+ XXX.entity.layers.BreezeWindLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.CustomHeadLayer$Transforms
+ XXX.entity.layers.Deadmau5EarsLayer
- XXX.entity.layers.DolphinCarryingItemLayer
+ XXX.entity.layers.DrownedOuterLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EquipmentLayerRenderer
+ XXX.entity.layers.EquipmentLayerRenderer$LayerTextureKey
- XXX.entity.layers.EquipmentLayerRenderer$TrimSpriteKey
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.IronGolemCrackinessLayer
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LivingEntityEmissiveLayer
+ XXX.entity.layers.LivingEntityEmissiveLayer$AlphaFunction
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.package-info
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.RopesLayer
- XXX.entity.layers.SheepWoolLayer
+ XXX.entity.layers.SheepWoolUndercoatLayer
- XXX.entity.layers.SimpleEquipmentLayer
+ XXX.entity.layers.SkeletonClothingLayer
- XXX.entity.layers.SlimeOuterLayer
+ XXX.entity.layers.SnowGolemHeadLayer
- XXX.entity.layers.SpiderEyesLayer
+ XXX.entity.layers.SpinAttackEffectLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.StuckInBodyLayer$PlacementStyle
- XXX.entity.layers.TropicalFishPatternLayer
+ XXX.entity.layers.TropicalFishPatternLayer$1
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WingsLayer
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.Bogged
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Husk$HuskGroupData
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
- XXX.entity.monster.package-info
+ XXX.entity.monster.Parched
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Witch
+ XXX.entity.monster.WitherSkeleton
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$FailureItemListing
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerTrades$TypeSpecificTrade
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.Abilities$Packed
- XXX.entity.player.AvatarRenderer
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Input
+ XXX.entity.player.Input$1
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$2
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerEquipment
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.PlayerModelType
- XXX.entity.player.PlayerSkin
+ XXX.entity.player.PlayerSkin$Patch
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.package-info
- XXX.entity.state.AllayRenderState
+ XXX.entity.state.ArmadilloRenderState
- XXX.entity.state.ArmedEntityRenderState
+ XXX.entity.state.ArmorStandRenderState
- XXX.entity.state.ArrowRenderState
+ XXX.entity.state.AvatarRenderState
- XXX.entity.state.AxolotlRenderState
+ XXX.entity.state.BatRenderState
- XXX.entity.state.BeeRenderState
+ XXX.entity.state.BlockDisplayEntityRenderState
- XXX.entity.state.BoatRenderState
+ XXX.entity.state.BoggedRenderState
- XXX.entity.state.BreezeRenderState
+ XXX.entity.state.CamelRenderState
- XXX.entity.state.CatRenderState
+ XXX.entity.state.ChickenRenderState
- XXX.entity.state.CopperGolemRenderState
+ XXX.entity.state.CowRenderState
- XXX.entity.state.CreakingRenderState
+ XXX.entity.state.CreeperRenderState
- XXX.entity.state.DisplayEntityRenderState
+ XXX.entity.state.DolphinRenderState
- XXX.entity.state.DonkeyRenderState
+ XXX.entity.state.EndCrystalRenderState
- XXX.entity.state.EnderDragonRenderState
+ XXX.entity.state.EndermanRenderState
- XXX.entity.state.EntityRenderState
+ XXX.entity.state.EntityRenderState$LeashState
- XXX.entity.state.EntityRenderState$ShadowPiece
+ XXX.entity.state.EquineRenderState
- XXX.entity.state.EvokerFangsRenderState
+ XXX.entity.state.EvokerRenderState
- XXX.entity.state.ExperienceOrbRenderState
+ XXX.entity.state.FallingBlockRenderState
- XXX.entity.state.FelineRenderState
+ XXX.entity.state.FireworkRocketRenderState
- XXX.entity.state.FishingHookRenderState
+ XXX.entity.state.FoxRenderState
- XXX.entity.state.FrogRenderState
+ XXX.entity.state.GhastRenderState
- XXX.entity.state.GoatRenderState
+ XXX.entity.state.GuardianRenderState
- XXX.entity.state.HappyGhastRenderState
+ XXX.entity.state.HitboxRenderState
- XXX.entity.state.HoglinRenderState
+ XXX.entity.state.HoldingEntityRenderState
- XXX.entity.state.HorseRenderState
+ XXX.entity.state.HumanoidRenderState
- XXX.entity.state.IllagerRenderState
+ XXX.entity.state.IllusionerRenderState
- XXX.entity.state.IronGolemRenderState
+ XXX.entity.state.ItemClusterRenderState
- XXX.entity.state.ItemDisplayEntityRenderState
+ XXX.entity.state.ItemEntityRenderState
- XXX.entity.state.ItemFrameRenderState
+ XXX.entity.state.LightningBoltRenderState
- XXX.entity.state.LivingEntityRenderState
+ XXX.entity.state.LlamaRenderState
- XXX.entity.state.LlamaSpitRenderState
+ XXX.entity.state.MinecartRenderState
- XXX.entity.state.MinecartTntRenderState
+ XXX.entity.state.MushroomCowRenderState
- XXX.entity.state.NautilusRenderState
- XXX.entity.state.package-info
+ XXX.entity.state.PaintingRenderState
- XXX.entity.state.PandaRenderState
+ XXX.entity.state.ParrotRenderState
- XXX.entity.state.PhantomRenderState
- XXX.entity.state.PiglinRenderState
+ XXX.entity.state.PigRenderState
+ XXX.entity.state.PolarBearRenderState
- XXX.entity.state.PufferfishRenderState
+ XXX.entity.state.RabbitRenderState
- XXX.entity.state.RavagerRenderState
+ XXX.entity.state.SalmonRenderState
- XXX.entity.state.SheepRenderState
+ XXX.entity.state.ShulkerBulletRenderState
- XXX.entity.state.ShulkerRenderState
+ XXX.entity.state.SkeletonRenderState
- XXX.entity.state.SlimeRenderState
+ XXX.entity.state.SnifferRenderState
- XXX.entity.state.SnowGolemRenderState
+ XXX.entity.state.SquidRenderState
- XXX.entity.state.StriderRenderState
+ XXX.entity.state.TextDisplayEntityRenderState
- XXX.entity.state.ThrownItemRenderState
+ XXX.entity.state.ThrownTridentRenderState
- XXX.entity.state.TippableArrowRenderState
+ XXX.entity.state.TntRenderState
- XXX.entity.state.TropicalFishRenderState
+ XXX.entity.state.TurtleRenderState
- XXX.entity.state.UndeadRenderState
+ XXX.entity.state.VexRenderState
- XXX.entity.state.VillagerDataHolderRenderState
+ XXX.entity.state.VillagerRenderState
- XXX.entity.state.WardenRenderState
+ XXX.entity.state.WitchRenderState
- XXX.entity.state.WitherRenderState
+ XXX.entity.state.WitherSkullRenderState
- XXX.entity.state.WolfRenderState
+ XXX.entity.state.ZombieRenderState
- XXX.entity.state.ZombieVillagerRenderState
+ XXX.entity.state.ZombifiedPiglinRenderState
- XXX.entity.trialspawner.package-info
- XXX.entity.trialspawner.PlayerDetector
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector
- XXX.entity.trialspawner.PlayerDetector$EntitySelector$1
+ XXX.entity.trialspawner.PlayerDetector$EntitySelector$2
- XXX.entity.trialspawner.TrialSpawner
+ XXX.entity.trialspawner.TrialSpawner$FlameParticle
- XXX.entity.trialspawner.TrialSpawner$FullConfig
+ XXX.entity.trialspawner.TrialSpawner$StateAccessor
- XXX.entity.trialspawner.TrialSpawnerConfig
+ XXX.entity.trialspawner.TrialSpawnerConfig$Builder
- XXX.entity.trialspawner.TrialSpawnerConfigs
+ XXX.entity.trialspawner.TrialSpawnerConfigs$Keys
- XXX.entity.trialspawner.TrialSpawnerState
+ XXX.entity.trialspawner.TrialSpawnerState$LightLevel
- XXX.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ XXX.entity.trialspawner.TrialSpawnerState$SpinningMob
- XXX.entity.trialspawner.TrialSpawnerStateData
+ XXX.entity.trialspawner.TrialSpawnerStateData$Packed
- XXX.entity.variant.BiomeCheck
+ XXX.entity.variant.ModelAndTexture
- XXX.entity.variant.MoonBrightnessCheck
+ XXX.entity.variant.package-info
+ XXX.entity.variant.PriorityProvider
- XXX.entity.variant.PriorityProvider$Selector
+ XXX.entity.variant.PriorityProvider$SelectorCondition
- XXX.entity.variant.PriorityProvider$UnpackedEntry
+ XXX.entity.variant.SpawnCondition
- XXX.entity.variant.SpawnConditions
+ XXX.entity.variant.SpawnContext
- XXX.entity.variant.SpawnPrioritySelectors
+ XXX.entity.variant.StructureCheck
- XXX.entity.variant.VariantUtils
- XXX.entity.vault.package-info
+ XXX.entity.vault.VaultBlockEntity
- XXX.entity.vault.VaultBlockEntity$Client
+ XXX.entity.vault.VaultBlockEntity$Server
- XXX.entity.vault.VaultClientData
+ XXX.entity.vault.VaultConfig
- XXX.entity.vault.VaultServerData
+ XXX.entity.vault.VaultSharedData
- XXX.entity.vault.VaultState
+ XXX.entity.vault.VaultState$1
- XXX.entity.vault.VaultState$2
+ XXX.entity.vault.VaultState$3
- XXX.entity.vault.VaultState$4
+ XXX.entity.vault.VaultState$LightLevel
- XXX.entity.vehicle.AbstractBoat
+ XXX.entity.vehicle.AbstractBoat$Status
- XXX.entity.vehicle.AbstractChestBoat
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestRaft
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartBehavior
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.NewMinecartBehavior
- XXX.entity.vehicle.NewMinecartBehavior$1
+ XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
- XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
+ XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
- XXX.entity.vehicle.OldMinecartBehavior
+ XXX.entity.vehicle.OldMinecartBehavior$1
- XXX.entity.vehicle.package-info
- XXX.entity.vehicle.Raft
+ XXX.entity.vehicle.VehicleEntity
- XXX.equipment.trim.ArmorTrim
+ XXX.equipment.trim.MaterialAssetGroup
- XXX.equipment.trim.MaterialAssetGroup$AssetInfo
+ XXX.equipment.trim.package-info
+ XXX.equipment.trim.TrimMaterial
- XXX.equipment.trim.TrimMaterials
+ XXX.equipment.trim.TrimPattern
- XXX.equipment.trim.TrimPatterns
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FallenTreeConfiguration
+ XXX.feature.configurations.FallenTreeConfiguration$FallenTreeConfigurationBuilder
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.CherryFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.package-info
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.AttachedToLeavesDecorator
- XXX.feature.treedecorators.AttachedToLogsDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.CreakingHeartDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.PaleMossDecorator
- XXX.feature.treedecorators.PlaceOnGroundDecorator
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ XXX.fog.environment.AtmosphericFogEnvironment
- XXX.fog.environment.BlindnessFogEnvironment
+ XXX.fog.environment.DarknessFogEnvironment
- XXX.fog.environment.FogEnvironment
+ XXX.fog.environment.LavaFogEnvironment
- XXX.fog.environment.MobEffectFogEnvironment
+ XXX.fog.environment.package-info
+ XXX.fog.environment.PowderedSnowFogEnvironment
- XXX.fog.environment.WaterFogEnvironment
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
- XXX.gui.components.CycleButton$DisplayState
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$SpriteSupplier
+ XXX.gui.components.package-info
+ XXX.gui.components.StringWidget
- XXX.gui.components.StringWidget$TextOverflow
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$SoundPlayedAt
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabButton
+ XXX.gui.components.TabOrderedElement
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.components.WidgetSprites
+ XXX.gui.components.WidgetTooltipHolder
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.KineticWeapon
+ XXX.item.component.KineticWeapon$Condition
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
+ XXX.item.component.package-info
- XXX.item.component.PiercingWeapon
+ XXX.item.component.ProvidesTrimMaterial
- XXX.item.component.ResolvableProfile
+ XXX.item.component.ResolvableProfile$Dynamic
- XXX.item.component.ResolvableProfile$Partial
+ XXX.item.component.ResolvableProfile$Static
- XXX.item.component.SeededContainerLoot
+ XXX.item.component.SuspiciousStewEffects
- XXX.item.component.SuspiciousStewEffects$Entry
+ XXX.item.component.SwingAnimation
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.TypedEntityData
+ XXX.item.component.TypedEntityData$1
- XXX.item.component.UseCooldown
+ XXX.item.component.UseEffects
- XXX.item.component.UseRemainder
+ XXX.item.component.UseRemainder$OnExtraCreatedRemainder
- XXX.item.component.Weapon
+ XXX.item.component.WritableBookContent
- XXX.item.component.WrittenBookContent
- XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
- XXX.item.consume_effects.ConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect$Type
+ XXX.item.consume_effects.package-info
- XXX.item.consume_effects.PlaySoundConsumeEffect
+ XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
- XXX.item.consume_effects.TeleportRandomlyConsumeEffect
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.AbstractCookingRecipe$Factory
+ XXX.item.crafting.AbstractCookingRecipe$Serializer
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BlastingRecipe$1
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingInput
+ XXX.item.crafting.CraftingInput$Positioned
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CraftingRecipe$1
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.CustomRecipe$Serializer
- XXX.item.crafting.CustomRecipe$Serializer$Factory
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.ExtendedRecipeBookCategory
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
+ XXX.item.crafting.PlacementInfo
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeAccess
- XXX.item.crafting.RecipeBookCategories
+ XXX.item.crafting.RecipeBookCategory
- XXX.item.crafting.RecipeCache
+ XXX.item.crafting.RecipeCache$Entry
- XXX.item.crafting.RecipeHolder
+ XXX.item.crafting.RecipeInput
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeManager$IngredientCollector
- XXX.item.crafting.RecipeManager$IngredientExtractor
+ XXX.item.crafting.RecipeManager$ServerDisplayInfo
- XXX.item.crafting.RecipeMap
+ XXX.item.crafting.RecipePropertySet
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.SelectableRecipe
+ XXX.item.crafting.SelectableRecipe$SingleInputEntry
- XXX.item.crafting.SelectableRecipe$SingleInputSet
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapedRecipePattern
- XXX.item.crafting.ShapedRecipePattern$Data
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Factory
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleRecipeInput
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmeltingRecipe$1
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingRecipeInput
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.TippedArrowRecipe
+ XXX.item.crafting.TransmuteRecipe
- XXX.item.crafting.TransmuteRecipe$Serializer
+ XXX.item.crafting.TransmuteResult
- XXX.item.enchantment.ConditionalEffect
+ XXX.item.enchantment.Enchantable
- XXX.item.enchantment.EnchantedItemInUse
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$1
+ XXX.item.enchantment.Enchantment$Builder
- XXX.item.enchantment.Enchantment$Cost
+ XXX.item.enchantment.Enchantment$EnchantmentDefinition
- XXX.item.enchantment.EnchantmentEffectComponents
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.EnchantmentTarget
+ XXX.item.enchantment.ItemEnchantments
- XXX.item.enchantment.ItemEnchantments$Mutable
+ XXX.item.enchantment.LevelBasedValue
- XXX.item.enchantment.LevelBasedValue$Clamped
+ XXX.item.enchantment.LevelBasedValue$Constant
- XXX.item.enchantment.LevelBasedValue$Exponent
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
+ XXX.item.equipment.AllowedEntitiesProvider
- XXX.item.equipment.ArmorMaterial
+ XXX.item.equipment.ArmorMaterials
- XXX.item.equipment.ArmorType
+ XXX.item.equipment.EquipmentAsset
- XXX.item.equipment.EquipmentAssets
+ XXX.item.equipment.Equippable
- XXX.item.equipment.Equippable$Builder
+ XXX.item.equipment.package-info
+ XXX.item.slot.CompositeSlotSource
- XXX.item.slot.ContentsSlotSource
+ XXX.item.slot.EmptySlotSource
- XXX.item.slot.FilteredSlotSource
+ XXX.item.slot.GroupSlotSource
- XXX.item.slot.LimitSlotSource
+ XXX.item.slot.package-info
+ XXX.item.slot.RangeSlotSource
- XXX.item.slot.SlotCollection
+ XXX.item.slot.SlotCollection$Filtered
- XXX.item.slot.SlotCollection$FlatMapped
+ XXX.item.slot.SlotCollection$Limited
- XXX.item.slot.SlotSource
+ XXX.item.slot.SlotSources
- XXX.item.slot.TransformedSlotSource
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
- XXX.level.block.AmethystClusterBlock
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BambooStalkBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BaseRailBlock$1
- XXX.level.block.BaseTorchBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$ShapePairKey
+ XXX.level.block.Block$UpdateFlags
+ XXX.level.block.Blocks
- XXX.level.block.BlockTypes
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BonemealableBlock$Type
- XXX.level.block.BonemealableFeaturePlacerBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.CactusBlock
+ XXX.level.block.CactusFlowerBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CalibratedSculkSensorBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
- XXX.level.block.CandleCakeBlock
+ XXX.level.block.CarpetBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.CaveVines
+ XXX.level.block.CaveVinesBlock
- XXX.level.block.CaveVinesPlantBlock
+ XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChiseledBookShelfBlock
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.ColoredFallingBlock
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CopperBulbBlock
- XXX.level.block.CopperChestBlock
+ XXX.level.block.CopperGolemStatueBlock
- XXX.level.block.CopperGolemStatueBlock$Pose
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CrafterBlock
- XXX.level.block.CrafterBlock$1
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CreakingHeartBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DirtPathBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoubleBlockCombiner
+ XXX.level.block.DoubleBlockCombiner$BlockType
- XXX.level.block.DoubleBlockCombiner$Combiner
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DriedGhastBlock
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.DryVegetationBlock
- XXX.level.block.EnchantingTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.EyeblossomBlock
- XXX.level.block.EyeblossomBlock$Type
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FireflyBushBlock
+ XXX.level.block.FlowerBedBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GlowLichenBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrowingPlantBlock
- XXX.level.block.GrowingPlantBodyBlock
+ XXX.level.block.GrowingPlantHeadBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HangingMossBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HeavyCoreBlock
+ XXX.level.block.HoneyBlock
- XXX.level.block.HopperBlock
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeafLitterBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.Mirror
- XXX.level.block.MossyCarpetBlock
+ XXX.level.block.MossyCarpetBlock$1
- XXX.level.block.MudBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MultifaceSpreadeableBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.package-info
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PipeBlock
+ XXX.level.block.PitcherCropBlock
- XXX.level.block.PitcherCropBlock$1
+ XXX.level.block.PitcherCropBlock$PosAndState
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$1
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.Portal
- XXX.level.block.Portal$Transition
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkBehaviour
+ XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkBlock
+ XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkSensorBlock
+ XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader
+ XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock
+ XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
- XXX.level.block.SegmentableBlock
+ XXX.level.block.SelectableSlotContainer
- XXX.level.block.SelectableSlotContainer$1
+ XXX.level.block.ShelfBlock
- XXX.level.block.ShortDryGrassBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SideChainPartBlock
- XXX.level.block.SideChainPartBlock$EmptyNeighbor
+ XXX.level.block.SideChainPartBlock$Neighbor
- XXX.level.block.SideChainPartBlock$Neighbors
+ XXX.level.block.SideChainPartBlock$SideChainNeighbor
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnifferEggBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SuspiciousEffectHolder
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallDryGrassBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TestBlock
- XXX.level.block.TestInstanceBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TintedParticleLeavesBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TorchflowerCropBlock
- XXX.level.block.TransparentBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TrialSpawnerBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.UntintedParticleLeavesBlock
- XXX.level.block.VaultBlock
+ XXX.level.block.VegetationBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WaterloggedTransparentBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperBarsBlock
- XXX.level.block.WeatheringCopperBlocks
+ XXX.level.block.WeatheringCopperBulbBlock
- XXX.level.block.WeatheringCopperChainBlock
+ XXX.level.block.WeatheringCopperChestBlock
- XXX.level.block.WeatheringCopperDoorBlock
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperGolemStatueBlock
+ XXX.level.block.WeatheringCopperGrateBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WeatheringCopperTrapDoorBlock
+ XXX.level.block.WeatheringLanternBlock
- XXX.level.block.WeatheringLightningRodBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$ChunkPathElement
- XXX.level.chunk.ChunkAccess$PackedTicks
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.Configuration
- XXX.level.chunk.Configuration$Global
+ XXX.level.chunk.Configuration$Simple
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunk$UnsavedListener
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunk
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainerFactory
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.Strategy
+ XXX.level.chunk.Strategy$1
- XXX.level.chunk.Strategy$2
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.DimensionType$CardinalLightType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.DimensionType$Skybox
- XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.EntityTypeTest$2
- XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetter
- XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.UniquelyIdentifyable
- XXX.level.entity.UUIDLookup
- XXX.level.entity.Visibility
- XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.BlockPositionSource$Type
- XXX.level.gameevent.DynamicGameEventListener
+ XXX.level.gameevent.EntityPositionSource
- XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry
- XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListener$Provider
- XXX.level.gameevent.GameEventListenerRegistry
+ XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
- XXX.level.gamerules.GameRule
+ XXX.level.gamerules.GameRuleCategory
- XXX.level.gamerules.GameRuleMap
+ XXX.level.gamerules.GameRuleMap$Builder
- XXX.level.gamerules.GameRules
+ XXX.level.gamerules.GameRules$VisitorCaller
- XXX.level.gamerules.GameRuleType
+ XXX.level.gamerules.GameRuleTypeVisitor
- XXX.level.gamerules.package-info
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$FindTopSurface
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
+ XXX.level.levelgen.WorldDimensions$1Entry
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.WorldOptions
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.ChunkSkyLightSources
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$SectionState
+ XXX.level.lighting.LayerLightSectionStorage$SectionType
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEngine
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.FlowingFluid$BlockStatePairKey
+ XXX.level.material.FlowingFluid$SpreadContext
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.Path$DebugData
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.PathfindingContext
- XXX.level.pathfinder.PathType
+ XXX.level.pathfinder.PathTypeCache
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator$1
- XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalShape
- XXX.level.portal.TeleportTransition
+ XXX.level.portal.TeleportTransition$PostTeleportTransition
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.DefaultRedstoneWireEvaluator
- XXX.level.redstone.ExperimentalRedstoneUtils
+ XXX.level.redstone.ExperimentalRedstoneWireEvaluator
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.Orientation
+ XXX.level.redstone.Orientation$SideBias
- XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.redstone.RedstoneWireEvaluator
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedDataType
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.FileNameDateFormatter
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelData$RespawnData
+ XXX.level.storage.LevelDataAndDimensions
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$CorruptedLevelSummary
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.TagValueInput
- XXX.level.storage.TagValueInput$CompoundListWrapper
+ XXX.level.storage.TagValueInput$CompoundListWrapper$1
- XXX.level.storage.TagValueInput$DecodeFromFieldFailedProblem
+ XXX.level.storage.TagValueInput$DecodeFromListFailedProblem
- XXX.level.storage.TagValueInput$DecodeFromMapFailedProblem
+ XXX.level.storage.TagValueInput$ListWrapper
- XXX.level.storage.TagValueInput$ListWrapper$1
+ XXX.level.storage.TagValueInput$TypedListWrapper
- XXX.level.storage.TagValueInput$TypedListWrapper$1
+ XXX.level.storage.TagValueInput$UnexpectedListElementTypeProblem
- XXX.level.storage.TagValueInput$UnexpectedNonNumberProblem
+ XXX.level.storage.TagValueInput$UnexpectedTypeProblem
- XXX.level.storage.TagValueOutput
+ XXX.level.storage.TagValueOutput$EncodeToFieldFailedProblem
- XXX.level.storage.TagValueOutput$EncodeToListFailedProblem
+ XXX.level.storage.TagValueOutput$EncodeToMapFailedProblem
- XXX.level.storage.TagValueOutput$ListWrapper
+ XXX.level.storage.TagValueOutput$TypedListWrapper
- XXX.level.storage.ValueInput
+ XXX.level.storage.ValueInput$TypedInputList
- XXX.level.storage.ValueInput$ValueInputList
+ XXX.level.storage.ValueInputContextHelper
- XXX.level.storage.ValueInputContextHelper$1
+ XXX.level.storage.ValueInputContextHelper$2
- XXX.level.storage.ValueInputContextHelper$3
+ XXX.level.storage.ValueOutput
- XXX.level.storage.ValueOutput$TypedOutputList
+ XXX.level.storage.ValueOutput$ValueOutputList
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.level.validation.ContentValidationException
- XXX.level.validation.DirectoryValidator
+ XXX.level.validation.DirectoryValidator$1
- XXX.level.validation.ForbiddenSymlinkInfo
- XXX.level.validation.package-info
+ XXX.level.validation.PathAllowList
- XXX.level.validation.PathAllowList$ConfigEntry
+ XXX.level.validation.PathAllowList$EntryType
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.BlendingData$Packed
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.UnobstructedPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPlatformFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.FallenTreeFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TreeFeature$1
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.FixedPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.Structure$StructureSettings$Builder
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$1
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.NestedLootTable
- XXX.loot.entries.NestedLootTable$1
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.SlotLoot
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyComponentsFunction
+ XXX.loot.functions.CopyComponentsFunction$BlockEntitySource
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$DirectSource
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.DiscardItem
+ XXX.loot.functions.EnchantedCountIncreaseFunction
- XXX.loot.functions.EnchantedCountIncreaseFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.FilteredFunction$Builder
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.ListOperation
- XXX.loot.functions.ListOperation$Append
+ XXX.loot.functions.ListOperation$Insert
- XXX.loot.functions.ListOperation$ReplaceAll
+ XXX.loot.functions.ListOperation$ReplaceSection
- XXX.loot.functions.ListOperation$StandAlone
+ XXX.loot.functions.ListOperation$Type
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.ModifyContainerContents
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
+ XXX.loot.functions.SetCustomModelDataFunction
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetFireworkExplosionFunction
+ XXX.loot.functions.SetFireworksFunction
- XXX.loot.functions.SetInstrumentFunction
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AllOfCondition
+ XXX.loot.predicates.AllOfCondition$Builder
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.EnchantmentActiveCheck
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithEnchantedBonusCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementHolder
- XXX.minecraft.advancements.AdvancementNode
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementRequirements
+ XXX.minecraft.advancements.AdvancementRequirements$Strategy
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.AdvancementTree
+ XXX.minecraft.advancements.AdvancementTree$Listener
- XXX.minecraft.advancements.AdvancementType
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.Camera$NearPlane
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBootstrap
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.CommandHistory
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.DeltaTracker
- XXX.minecraft.client.DeltaTracker$DefaultValue
+ XXX.minecraft.client.DeltaTracker$Timer
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GameNarrator$NarratorInitException
- XXX.minecraft.client.GraphicsPreset
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.InactivityFpsLimit
+ XXX.minecraft.client.InputType
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.KeyMapping$Category
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$2
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.Minecraft$GameLoadCookie
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.MouseHandler$LastClick
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$1
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
+ XXX.minecraft.stats.ServerRecipeBook$Packed
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.DamageTypeTags
+ XXX.minecraft.tags.DialogTags
- XXX.minecraft.tags.EnchantmentTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$ElementLookup
- XXX.minecraft.tags.TagLoader$EntryWithSource
+ XXX.minecraft.tags.TagLoader$LoadResult
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TimelineTags
- XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.AbstractListBuilder
- XXX.minecraft.util.ARGB
- XXX.minecraft.util.ArrayListDeque
+ XXX.minecraft.util.ArrayListDeque$DescendingIterator
- XXX.minecraft.util.ArrayListDeque$ReversedView
+ XXX.minecraft.util.BinaryAnimator
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.BlockUtil
- XXX.minecraft.util.BlockUtil$FoundRectangle
+ XXX.minecraft.util.BlockUtil$IntBounds
- XXX.minecraft.util.BoundedFloatFunction
+ XXX.minecraft.util.BoundedFloatFunction$1
- XXX.minecraft.util.BoundedFloatFunction$2
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.ClassTreeIdRegistry
- XXX.minecraft.util.ColorRGBA
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DelegateDataOutput
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.Ease
+ XXX.minecraft.util.EasingType
- XXX.minecraft.util.EasingType$CubicBezier
+ XXX.minecraft.util.EasingType$CubicBezier$CubicCurve
- XXX.minecraft.util.EasingType$CubicBezierControls
+ XXX.minecraft.util.EncoderCache
- XXX.minecraft.util.EncoderCache$1
+ XXX.minecraft.util.EncoderCache$2
- XXX.minecraft.util.EncoderCache$Key
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$5
+ XXX.minecraft.util.ExtraCodecs$6
- XXX.minecraft.util.ExtraCodecs$7
+ XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
- XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.FastBufferedInputStream
+ XXX.minecraft.util.FileSystemUtil
- XXX.minecraft.util.FileUtil
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.GsonHelper$CountedAppendable
- XXX.minecraft.util.HashOps
+ XXX.minecraft.util.HashOps$ListHashBuilder
- XXX.minecraft.util.HashOps$MapHashBuilder
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.IdentifierPattern
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.Keyframe
+ XXX.minecraft.util.KeyframeTrack
- XXX.minecraft.util.KeyframeTrack$Builder
+ XXX.minecraft.util.KeyframeTrackSampler
- XXX.minecraft.util.KeyframeTrackSampler$Segment
+ XXX.minecraft.util.LenientJsonParser
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.ListAndDeque
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.NullOps
- XXX.minecraft.util.NullOps$1
+ XXX.minecraft.util.NullOps$NullListBuilder
- XXX.minecraft.util.NullOps$NullMapBuilder
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.SegmentedAnglePrecision
+ XXX.minecraft.util.SequencedPriorityIterator
- XXX.minecraft.util.SignatureUpdater
+ XXX.minecraft.util.SignatureUpdater$Output
- XXX.minecraft.util.SignatureValidator
+ XXX.minecraft.util.Signer
- XXX.minecraft.util.SimpleBitStorage
+ XXX.minecraft.util.SimpleBitStorage$InitializationException
- XXX.minecraft.util.SingleKeyCache
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.SpawnUtil$Strategy
- XXX.minecraft.util.SpecialDates
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StrictJsonParser
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.Util
- XXX.minecraft.util.Util$1
+ XXX.minecraft.util.Util$10
- XXX.minecraft.util.Util$11
+ XXX.minecraft.util.Util$2
- XXX.minecraft.util.Util$3
+ XXX.minecraft.util.Util$4
- XXX.minecraft.util.Util$5
+ XXX.minecraft.util.Util$6
- XXX.minecraft.util.Util$7
+ XXX.minecraft.util.Util$8
- XXX.minecraft.util.Util$9
+ XXX.minecraft.util.Util$OS
- XXX.minecraft.util.Util$OS$1
+ XXX.minecraft.util.Util$OS$2
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.package-info
+ XXX.model.multipart.CombinedCondition
- XXX.model.multipart.CombinedCondition$Operation
+ XXX.model.multipart.CombinedCondition$Operation$1
- XXX.model.multipart.CombinedCondition$Operation$2
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.KeyValueCondition$Term
- XXX.model.multipart.KeyValueCondition$Terms
+ XXX.model.multipart.MultiPartModel
- XXX.model.multipart.MultiPartModel$Selector
+ XXX.model.multipart.MultiPartModel$SharedBakedState
- XXX.model.multipart.MultiPartModel$Unbaked
+ XXX.model.multipart.MultiPartModel$Unbaked$1
- XXX.model.multipart.MultiPartModel$Unbaked$1Key
- XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.monster.breeze.Breeze
+ XXX.monster.breeze.Breeze$1
- XXX.monster.breeze.BreezeAi
+ XXX.monster.breeze.BreezeAi$SlideToTargetSink
- XXX.monster.breeze.BreezeUtil
+ XXX.monster.breeze.LongJump
+ XXX.monster.breeze.package-info
- XXX.monster.breeze.Shoot
+ XXX.monster.breeze.ShootWhenStuck
- XXX.monster.breeze.Slide
- XXX.monster.creaking.Creaking
+ XXX.monster.creaking.Creaking$CreakingBodyRotationControl
- XXX.monster.creaking.Creaking$CreakingJumpControl
+ XXX.monster.creaking.Creaking$CreakingLookControl
- XXX.monster.creaking.Creaking$CreakingMoveControl
+ XXX.monster.creaking.Creaking$CreakingPathNavigation
- XXX.monster.creaking.Creaking$HomeNodeEvaluator
+ XXX.monster.creaking.CreakingAi
- XXX.monster.creaking.CreakingAi$1
+ XXX.monster.creaking.package-info
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.Warden$VibrationUser
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$Empty
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.MinecartCollisionContext
- XXX.phys.shapes.MinecartCollisionContext$1
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.pools.alias.DirectPoolAlias
- XXX.pools.alias.package-info
+ XXX.pools.alias.PoolAliasBinding
- XXX.pools.alias.PoolAliasBindings
+ XXX.pools.alias.PoolAliasLookup
- XXX.pools.alias.RandomGroupPoolAlias
+ XXX.pools.alias.RandomPoolAlias
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
+ XXX.protocol.game.ClientboundHurtAnimationPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundLevelChunkPacketData
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- XXX.protocol.game.ClientboundLevelChunkWithLightPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLightUpdatePacketData
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMountScreenOpenPacket
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$BlockEntitySource
+ XXX.providers.nbt.ContextNbtProvider$EntitySource
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.ConstantValue
+ XXX.providers.number.EnchantmentLevelProvider
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$RealmsIoConsumer
- XXX.realmsclient.util.RealmsUtil$RealmsIoFunction
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionRenderStorage
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$CommonRenderStorage
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.MovingBlockRenderState
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.AbstractEndPortalRenderer
- XXX.renderer.blockentity.AbstractSignRenderer
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider
- XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.blockentity.BlockEntityRenderers
- XXX.renderer.blockentity.BlockEntityWithBoundingBoxRenderer
+ XXX.renderer.blockentity.BrightnessCombiner
- XXX.renderer.blockentity.BrushableBlockRenderer
+ XXX.renderer.blockentity.BrushableBlockRenderer$1
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ChestRenderer$1
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.CopperGolemStatueBlockRenderer
+ XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
+ XXX.renderer.blockentity.HangingSignRenderer$ModelKey
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShelfRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$Models
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SkullBlockRenderer$1
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.TestInstanceRenderer
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.blockentity.TrialSpawnerRenderer
- XXX.renderer.blockentity.VaultRenderer
- XXX.renderer.chunk.ChunkSectionLayer
+ XXX.renderer.chunk.ChunkSectionLayerGroup
- XXX.renderer.chunk.ChunkSectionsToRender
- XXX.renderer.chunk.CompiledSectionMesh
+ XXX.renderer.chunk.CompiledSectionMesh$1
- XXX.renderer.chunk.CompiledSectionMesh$2
+ XXX.renderer.chunk.CompileTaskDynamicQueue
- XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderSectionRegion
+ XXX.renderer.chunk.SectionBuffers
- XXX.renderer.chunk.SectionCompiler
+ XXX.renderer.chunk.SectionCompiler$Results
- XXX.renderer.chunk.SectionCopy
+ XXX.renderer.chunk.SectionMesh
- XXX.renderer.chunk.SectionRenderDispatcher
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
+ XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
- XXX.renderer.chunk.TranslucencyPointOfView
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BreezeDebugRenderer
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkCullingDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.EntityBlockIntersectionDebugRenderer
- XXX.renderer.debug.EntityHitboxDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$ListenerVisitor
+ XXX.renderer.debug.GameTestBlockHighlightRenderer
- XXX.renderer.debug.GameTestBlockHighlightRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.LightSectionDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer$SectionData
+ XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer$LastUpdate
+ XXX.renderer.debug.OctreeDebugRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.PoiDebugRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.RedstoneWireOrientationsRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.SupportBlockRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.entity.AbstractBoatRenderer
+ XXX.renderer.entity.AbstractHoglinRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractMinecartRenderer
- XXX.renderer.entity.AbstractSkeletonRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AgeableMobRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmadilloRenderer
+ XXX.renderer.entity.ArmorModelSet
- XXX.renderer.entity.ArmorModelSet$1
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.BoggedRenderer
+ XXX.renderer.entity.BreezeRenderer
- XXX.renderer.entity.CamelHuskRenderer
+ XXX.renderer.entity.CamelRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CopperGolemRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreakingRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$1
- XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DonkeyRenderer
+ XXX.renderer.entity.DonkeyRenderer$Type
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EndermanRenderer
- XXX.renderer.entity.EndermiteRenderer
+ XXX.renderer.entity.EntityRenderDispatcher
- XXX.renderer.entity.EntityRenderer
+ XXX.renderer.entity.EntityRendererProvider
- XXX.renderer.entity.EntityRendererProvider$Context
+ XXX.renderer.entity.EntityRenderers
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
- XXX.renderer.entity.FrogRenderer
+ XXX.renderer.entity.GhastRenderer
- XXX.renderer.entity.GiantMobRenderer
+ XXX.renderer.entity.GlowSquidRenderer
- XXX.renderer.entity.GoatRenderer
+ XXX.renderer.entity.GuardianRenderer
- XXX.renderer.entity.HappyGhastRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaRenderer$1
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NautilusRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.OminousItemSpawnerRenderer
+ XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PaintingRenderer$1
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParchedRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RabbitRenderer$1
+ XXX.renderer.entity.RaftRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SalmonRenderer$1
- XXX.renderer.entity.SheepRenderer
+ XXX.renderer.entity.ShulkerBulletRenderer
- XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.SilverfishRenderer
- XXX.renderer.entity.SkeletonRenderer
+ XXX.renderer.entity.SlimeRenderer
- XXX.renderer.entity.SnifferRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.TadpoleRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TropicalFishRenderer$1
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.UndeadHorseRenderer$Type
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WardenRenderer
- XXX.renderer.entity.WindChargeRenderer
+ XXX.renderer.entity.WitchRenderer
- XXX.renderer.entity.WitherBossRenderer
+ XXX.renderer.entity.WitherSkeletonRenderer
- XXX.renderer.entity.WitherSkullRenderer
+ XXX.renderer.entity.WolfRenderer
- XXX.renderer.entity.ZoglinRenderer
+ XXX.renderer.entity.ZombieNautilusRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.renderer.entity.ZombifiedPiglinRenderer
+ XXX.renderer.feature.BlockFeatureRenderer
- XXX.renderer.feature.CustomFeatureRenderer
+ XXX.renderer.feature.CustomFeatureRenderer$Storage
- XXX.renderer.feature.FeatureRenderDispatcher
+ XXX.renderer.feature.FlameFeatureRenderer
- XXX.renderer.feature.ItemFeatureRenderer
+ XXX.renderer.feature.LeashFeatureRenderer
- XXX.renderer.feature.ModelFeatureRenderer
+ XXX.renderer.feature.ModelFeatureRenderer$CrumblingOverlay
- XXX.renderer.feature.ModelFeatureRenderer$Storage
+ XXX.renderer.feature.ModelPartFeatureRenderer
- XXX.renderer.feature.ModelPartFeatureRenderer$Storage
+ XXX.renderer.feature.NameTagFeatureRenderer
- XXX.renderer.feature.NameTagFeatureRenderer$Storage
+ XXX.renderer.feature.package-info
+ XXX.renderer.feature.ParticleFeatureRenderer
- XXX.renderer.feature.ParticleFeatureRenderer$ParticleBufferCache
+ XXX.renderer.feature.ShadowFeatureRenderer
- XXX.renderer.feature.TextFeatureRenderer
- XXX.renderer.fog.FogData
+ XXX.renderer.fog.FogRenderer
- XXX.renderer.fog.FogRenderer$FogMode
- XXX.renderer.fog.package-info
+ XXX.renderer.gizmos.DrawableGizmoPrimitives
- XXX.renderer.gizmos.DrawableGizmoPrimitives$Group
- XXX.resources.model.ModelBaker$PartCache
+ XXX.resources.model.ModelBaker$SharedOperationKey
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BakingResult
- XXX.resources.model.ModelBakery$MissingModels
+ XXX.resources.model.ModelBakery$MissingModels$1
- XXX.resources.model.ModelBakery$ModelBakerImpl
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecorationType
+ XXX.saveddata.maps.MapDecorationTypes
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapId
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapDecorationLocation
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.screens.inventory.AbstractRecipeBookScreen
+ XXX.screens.inventory.AbstractSignEditScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconButton
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookSignScreen
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CrafterScreen
+ XXX.screens.inventory.CrafterScreen$1
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.CyclingSlotBackground
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectsInInventory
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HangingSignEditScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.server.permissions.package-info
- XXX.server.permissions.Permissions
- XXX.server.permissions.PermissionSetUnion
+ XXX.server.permissions.PermissionTypes
- XXX.server.players.BanListEntry
+ XXX.server.players.CachedUserNameToIdResolver
- XXX.server.players.CachedUserNameToIdResolver$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.NameAndId
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.PlayerList$2
- XXX.server.players.ProfileResolver
+ XXX.server.players.ProfileResolver$Cached
- XXX.server.players.ProfileResolver$Cached$1
+ XXX.server.players.ProfileResolver$Cached$2
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserNameToIdResolver
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.server.waypoints.package-info
+ XXX.server.waypoints.ServerWaypointManager
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockSetType
- XXX.state.properties.BlockSetType$PressurePlateSensitivity
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.CreakingHeartState
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SideChainPart
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.TestBlockMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators
+ XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$2
+ XXX.storage.loot.ContainerComponentManipulators$3
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$BlockEntityTarget
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$ItemStackTarget
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextArg
- XXX.storage.loot.LootContextArg$ArgCodecBuilder
+ XXX.storage.loot.LootContextArg$Getter
- XXX.storage.loot.LootContextArg$SimpleGetter
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootDataType$Validator
- XXX.storage.loot.LootParams
+ XXX.storage.loot.LootParams$Builder
- XXX.storage.loot.LootParams$DynamicDrop
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
+ XXX.storage.loot.ValidationContext
- XXX.storage.loot.ValidationContext$MissingReferenceProblem
+ XXX.storage.loot.ValidationContext$ParametersNotProvidedProblem
- XXX.storage.loot.ValidationContext$RecursiveReferenceProblem
+ XXX.storage.loot.ValidationContext$ReferenceNotAllowedProblem
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.DimensionPadding
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JigsawStructure$MaxDistance
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.LiquidSettings
+ XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$JigsawBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.context.ContextKey
+ XXX.util.context.ContextKeySet
- XXX.util.context.ContextKeySet$Builder
+ XXX.util.context.ContextMap
- XXX.util.context.ContextMap$Builder
+ XXX.util.context.package-info
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.DataFixTypes$1
+ XXX.util.datafix.ExtraDataFixUtils
- XXX.util.datafix.LegacyComponentDataFixUtils
+ XXX.util.datafix.PackedBitStorage
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
- XXX.util.task.package-info
- XXX.util.task.RealmCreationTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
- XXX.world.entity.package-info
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractCraftingMenu
- XXX.world.inventory.AbstractCraftingMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.NautilusInventoryMenu$1
- XXX.world.inventory.NonInteractiveResultSlot
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookMenu$PostPlaceAction
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeCraftingHolder
- XXX.world.inventory.RemoteSlot
+ XXX.world.inventory.RemoteSlot$1
- XXX.world.inventory.RemoteSlot$Synchronized
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SlotRange
- XXX.world.inventory.SlotRange$1
+ XXX.world.inventory.SlotRanges
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.inventory.TransientCraftingContainer
+ XXX.world.item.AdventureModePredicate
- XXX.world.item.AirItem
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BoneMealItem$1
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.BundleItem$1
- XXX.world.item.CompassItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.CrossbowItem$ChargeType
+ XXX.world.item.CrossbowItem$ChargingSounds
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.EitherHolder
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$Properties
- XXX.world.item.Item$TooltipContext
+ XXX.world.item.Item$TooltipContext$1
- XXX.world.item.Item$TooltipContext$2
+ XXX.world.item.Item$TooltipContext$3
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$1
- XXX.world.item.ItemStack$2
+ XXX.world.item.ItemStack$3
- XXX.world.item.ItemStack$4
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUseAnimation
- XXX.world.item.ItemUtils
- XXX.world.item.JukeboxPlayable
+ XXX.world.item.JukeboxSong
- XXX.world.item.JukeboxSongPlayer
+ XXX.world.item.JukeboxSongPlayer$OnSongChanged
- XXX.world.item.JukeboxSongs
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MaceItem
+ XXX.world.item.MapItem
- XXX.world.item.MapItem$1
+ XXX.world.item.MinecartItem
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameTagItem
- XXX.world.item.package-info
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileItem
- XXX.world.item.ProjectileItem$DispenseConfig
+ XXX.world.item.ProjectileItem$DispenseConfig$Builder
- XXX.world.item.ProjectileItem$PositionFunction
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SwingAnimationType
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WeatheringCopperItems
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.LocalMobCapCalculator
+ XXX.world.level.LocalMobCapCalculator$MobCounts
- XXX.world.level.MoonPhase
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ScheduledTickAccess
+ XXX.world.level.ServerExplosion
- XXX.world.level.ServerExplosion$StackCollector
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SimpleExplosionDamageCalculator
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.Spawner
+ XXX.world.level.StructureManager
- XXX.world.level.TicketStorage
+ XXX.world.level.TicketStorage$ChunkUpdated
- XXX.world.level.TicketStorage$TicketPredicate
+ XXX.world.level.WorldDataConfiguration
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.AABB$Builder
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.phys.Vec3$1
+ XXX.world.scores.DisplaySlot
- XXX.world.scores.DisplaySlot$1
+ XXX.world.scores.Objective
- XXX.world.scores.Objective$Packed
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.PlayerTeam$Packed
+ XXX.world.scores.ReadOnlyScoreInfo
- XXX.world.scores.Score
+ XXX.world.scores.Score$Packed
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.Scoreboard$PackedScore
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreboardSaveData$Packed
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
+ XXX.world.timeline.AttributeTrack
- XXX.world.timeline.AttributeTrackSampler
- XXX.world.timeline.package-info
+ XXX.world.timeline.Timeline
- XXX.world.timeline.Timeline$Builder
+ XXX.world.timeline.Timelines
- XXX.world.waypoints.package-info
+ XXX.world.waypoints.PartialTickSupplier
- XXX.world.waypoints.TrackedWaypoint
+ XXX.world.waypoints.TrackedWaypoint$AzimuthWaypoint
- XXX.world.waypoints.TrackedWaypoint$Camera
+ XXX.world.waypoints.TrackedWaypoint$ChunkWaypoint
- XXX.world.waypoints.TrackedWaypoint$EmptyWaypoint
+ XXX.world.waypoints.TrackedWaypoint$PitchDirection
- XXX.world.waypoints.TrackedWaypoint$Projector
+ XXX.world.waypoints.TrackedWaypoint$Type
- XXX.world.waypoints.TrackedWaypoint$Vec3iWaypoint
+ XXX.world.waypoints.TrackedWaypointManager
- XXX.world.waypoints.Waypoint
+ XXX.world.waypoints.Waypoint$Icon
- XXX.world.waypoints.WaypointManager
+ XXX.world.waypoints.WaypointStyleAsset
- XXX.world.waypoints.WaypointStyleAssets
+ XXX.world.waypoints.WaypointTransmitter
- XXX.world.waypoints.WaypointTransmitter$BlockConnection
+ XXX.world.waypoints.WaypointTransmitter$ChunkConnection
- XXX.world.waypoints.WaypointTransmitter$Connection
+ XXX.world.waypoints.WaypointTransmitter$EntityAzimuthConnection
- XXX.world.waypoints.WaypointTransmitter$EntityBlockConnection
+ XXX.world.waypoints.WaypointTransmitter$EntityChunkConnection
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.opengl.GlTextureView +2M -1M | +3P
```
```
XXX.mojang.math.OctahedralGroup +1M -3M | +9P -1P
```
```
XXX.mojang.math.Quadrant +3M -1M | +3P
```
```
XXX.screens.configuration.RealmsPreferredRegionSelectionScreen +1M
```
```
XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry +1M
```
```
XXX.minecraft.client.Options +9M -7M | +1P -2P
```
```
XXX.gui.components.AbstractButton +1M | +1P
```
```
XXX.gui.components.CycleButton +1M -1M | +2P -1P
```
```
XXX.screens.advancements.AdvancementTab +1M -1M
```
```
XXX.screens.advancements.AdvancementsScreen +1M -1M
```
```
XXX.screens.debug.GameModeSwitcherScreen +1M
```
```
XXX.screens.inventory.AbstractContainerScreen +2M -2M
```
```
XXX.screens.recipebook.FurnaceRecipeBookComponent +1M -1M
```
```
XXX.screens.recipebook.RecipeBookComponent +11M -7M | +2P -2P
```
```
XXX.screens.recipebook.RecipeBookPage +2M | +6P -2P
```
```
XXX.client.model.HumanoidModel$ArmPose$1 +1M -1M
```
```
XXX.geom.builders.UVPair +5M
```
```
XXX.client.multiplayer.ClientPacketListener +1M -1M
```
```
XXX.client.player.LocalPlayer +1M -1M | -1P
```
```
XXX.client.renderer.FaceInfo +1M -1M | +1P -1P
```
```
XXX.client.renderer.FaceInfo$VertexInfo +8M -1M | +3P -3P
```
```
XXX.client.renderer.ItemInHandRenderer +1M -1M | -1P
```
```
XXX.client.renderer.LevelRenderer +1M | +1P
```
```
XXX.renderer.item.ItemStackRenderState$LayerRenderState +1M -1M | +1P -1P
```
```
XXX.renderer.rendertype.RenderTypes +1M | +1P
```
```
XXX.renderer.special.BannerSpecialRenderer +1M -1M
```
```
XXX.renderer.special.BedSpecialRenderer +1M -1M
```
```
XXX.renderer.special.ChestSpecialRenderer +1M -1M
```
```
XXX.renderer.special.ConduitSpecialRenderer +1M -1M
```
```
XXX.renderer.special.CopperGolemStatueSpecialRenderer +1M -1M
```
```
XXX.renderer.special.DecoratedPotSpecialRenderer +1M -1M
```
```
XXX.renderer.special.HangingSignSpecialRenderer +1M -1M
```
```
XXX.renderer.special.StandingSignSpecialRenderer +1M -1M
```
```
XXX.renderer.special.TridentSpecialRenderer +1M -1M
```
```
XXX.renderer.texture.TextureAtlas +2M -1M
```
```
XXX.resources.model.AtlasManager +2M | +1P
```
```
XXX.resources.model.ModelManager +2M -3M
```
```
XXX.data.recipes.RecipeProvider +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.server.level.ServerPlayer +1M
```
```
XXX.server.permissions.LevelBasedPermissionSet +1M
```
```
XXX.server.permissions.PermissionSet -1M
```
```
XXX.world.effect.MobEffectUtil +1M
```
```
XXX.ai.behavior.ChargeAttack +1M -1M | +1P
```
```
XXX.animal.camel.CamelAi$CamelPanic +3M
```
```
XXX.animal.camel.CamelHusk +1M
```
```
XXX.animal.frog.ShootTongue -1P
```
```
XXX.animal.horse.AbstractHorse -1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.GlTextureView
</summary>

```diff
- int createFbo(DirectStateAccess,int)
+ int lambda$getFbo$0(DirectStateAccess,int,int)
- int lambda$getFbo$0(DirectStateAccess,int)
```

</details>
<details>
<summary>
com.mojang.math.OctahedralGroup
</summary>

```diff
- Direction lambda$rotate$5(Direction)
+ Direction lambda$rotate$6(Direction)
+ OctahedralGroup fromXYAngles(Quadrant,Quadrant)
+ void lambda$static$5(OctahedralGroup[][])
```

</details>
<details>
<summary>
com.mojang.math.Quadrant
</summary>

```diff
- OctahedralGroup fromXYAngles(Quadrant,Quadrant)
- OctahedralGroup fromXYZAngles(Quadrant,Quadrant,Quadrant)
- void <init>(String,int,int,OctahedralGroup,OctahedralGroup,OctahedralGroup)
+ void <init>(String,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.configuration.RealmsPreferredRegionSelectionScreen
</summary>

```diff
- void onDone()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry
</summary>

```diff
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.Options
</summary>

```diff
+ Component lambda$new$121(Component,Integer)
- Component lambda$new$121(Component,MusicToastDisplayState)
- Component lambda$new$125(Component,Integer)
- OptionInstance musicToast()
+ OptionInstance showNowPlayingToast()
+ String lambda$dumpOptionsForReport$127(Pair)
- String lambda$dumpOptionsForReport$129(Pair)
- Tooltip lambda$new$120(MusicToastDisplayState)
+ void lambda$load$125(CompoundTag,String)
+ void lambda$load$126(String)
- void lambda$load$127(CompoundTag,String)
- void lambda$load$128(String)
+ void lambda$new$120(Boolean)
+ void lambda$new$122(Integer)
- void lambda$new$122(MusicToastDisplayState)
- void lambda$new$126(Integer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.AbstractButton
</summary>

```diff
- void setOverrideRenderHighlightedSprite(Supplier)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CycleButton
</summary>

```diff
+ void <init>(int,int,int,int,Component,Component,int,Object,Supplier,CycleButton$ValueListSupplier,Function,Function,CycleButton$OnValueChange,OptionInstance$TooltipSupplier,boolean)
- void <init>(int,int,int,int,Component,Component,int,Object,Supplier,CycleButton$ValueListSupplier,Function,Function,CycleButton$OnValueChange,OptionInstance$TooltipSupplier,CycleButton$DisplayState,CycleButton$SpriteSupplier)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementTab
</summary>

```diff
+ void drawTab(GuiGraphics,int,int,boolean)
- void drawTab(GuiGraphics,int,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementsScreen
</summary>

```diff
- void renderWindow(GuiGraphics,int,int,int,int)
+ void renderWindow(GuiGraphics,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
</summary>

```diff
- boolean mouseReleased(MouseButtonEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
- void renderSlot(GuiGraphics,Slot,int,int)
+ void renderSlot(GuiGraphics,Slot)
- void renderSlots(GuiGraphics,int,int)
+ void renderSlots(GuiGraphics)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.FurnaceRecipeBookComponent
</summary>

```diff
+ void initFilterButtonTextures()
- WidgetSprites getFilterButtonTextures()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
</summary>

```diff
+ boolean lambda$initVisuals$1(RecipeBookTabButton)
- boolean lambda$initVisuals$4(RecipeBookTabButton)
+ boolean lambda$updateCollections$2(RecipeCollection)
+ boolean lambda$updateCollections$3(ObjectSet,RecipeCollection)
+ boolean lambda$updateCollections$4(RecipeCollection)
- boolean lambda$updateCollections$5(RecipeCollection)
- boolean lambda$updateCollections$6(ObjectSet,RecipeCollection)
- boolean lambda$updateCollections$7(RecipeCollection)
+ boolean toggleFiltering()
- Identifier lambda$initVisuals$2(CycleButton,Boolean)
- Tooltip lambda$initVisuals$1(Boolean)
- void lambda$initVisuals$3(CycleButton,Boolean)
+ void lambda$updateNarration$5(List,AbstractWidget)
- void lambda$updateNarration$8(List,AbstractWidget)
- void onTabButtonPress(Button)
- void replaceSelected(RecipeBookTabButton)
- void toggleFiltering()
+ void updateFilterButtonTooltip()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookPage
</summary>

```diff
- void lambda$init$0(Button)
- void lambda$init$1(Button)
```

</details>
<details>
<summary>
net.minecraft.client.model.HumanoidModel$ArmPose$1
</summary>

```diff
- void <init>(String,int,boolean,boolean)
+ void <init>(String,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.builders.UVPair
</summary>

```diff
- boolean equals(Object)
- float unpackU(long)
- float unpackV(long)
- int hashCode()
- long pack(float,float)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ void handleHorseScreenOpen(ClientboundHorseScreenOpenPacket)
- void handleMountScreenOpen(ClientboundMountScreenOpenPacket)
```

</details>
<details>
<summary>
net.minecraft.client.player.LocalPlayer
</summary>

```diff
- void setExperienceDisplayStartTickToTickCount()
+ void setExperienceDisplayStartTickToTickCount(float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FaceInfo
</summary>

```diff
- void lambda$static$0(EnumMap)
+ void lambda$static$0(FaceInfo[])
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FaceInfo$VertexInfo
</summary>

```diff
- boolean equals(Object)
- FaceInfo$Extent xFace()
- FaceInfo$Extent yFace()
- FaceInfo$Extent zFace()
- int hashCode()
- String toString()
- Vector3f select(Vector3fc,Vector3fc)
- void <init>(FaceInfo$Extent,FaceInfo$Extent,FaceInfo$Extent)
+ void <init>(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ItemInHandRenderer
</summary>

```diff
- void <init>(Minecraft,EntityRenderDispatcher,ItemModelResolver)
+ void <init>(Minecraft,EntityRenderDispatcher,ItemRenderer,ItemModelResolver)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer
</summary>

```diff
- void finalizeGizmoCollection()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemStackRenderState$LayerRenderState
</summary>

```diff
+ Vector3f[] lambda$static$0()
- Vector3fc[] lambda$static$0()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.rendertype.RenderTypes
</summary>

```diff
- RenderType linesTranslucent()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.BannerSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.BedSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ChestSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.ConduitSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.CopperGolemStatueSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.DecoratedPotSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.HangingSignSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.StandingSignSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.TridentSpecialRenderer
</summary>

```diff
- void getExtents(Consumer)
+ void getExtents(Set)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlas
</summary>

```diff
+ String lambda$cycleAnimationFrames$6()
- String lambda$uploadAnimationFrames$6()
- void uploadAnimationFrames()
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.AtlasManager
</summary>

```diff
- void lambda$updateSpriteMaps$6(Map,Material,TextureAtlasSprite)
- void updateSpriteMaps(AtlasManager$PendingStitchResults)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelManager
</summary>

```diff
- EntityModelSet lambda$entityModels$16()
+ EntityModelSet lambda$entityModels$17()
+ SpecialBlockModelRenderer lambda$specialBlockModelRenderer$16()
- SpecialBlockModelRenderer specialBlockModelRenderer()
+ Supplier specialBlockModelRenderer()
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- void waxedChiseled(Block,Block)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void openNautilusInventory(AbstractNautilus,Container)
```

</details>
<details>
<summary>
net.minecraft.server.permissions.LevelBasedPermissionSet
</summary>

```diff
- PermissionSet union(PermissionSet)
```

</details>
<details>
<summary>
net.minecraft.server.permissions.PermissionSet
</summary>

```diff
+ boolean lambda$union$2(PermissionSet,Permission)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectUtil
</summary>

```diff
- boolean shouldEffectsRefillAirsupply(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.ChargeAttack
</summary>

```diff
- void <init>(int,TargetingConditions,float,float,double,double,SoundEvent)
+ void <init>(int,TargetingConditions,float,float,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
</summary>

```diff
- boolean checkExtraStartConditions(ServerLevel,Camel)
- boolean checkExtraStartConditions(ServerLevel,LivingEntity)
- boolean checkExtraStartConditions(ServerLevel,PathfinderMob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.camel.CamelHusk
</summary>

```diff
- boolean canFallInLove()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ int getInventorySize(int)
```

</details>
</details>
<hr/>