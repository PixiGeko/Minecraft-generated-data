## Comparison with [26.1-snapshot-2](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-2)

> [!TIP]
> - [Version data](#version-data)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-2</th><th>26.1-snapshot-3</th></tr><tr><td>DataPack version</td><td><pre>96.0</pre></td><td><pre>97.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>77.0</pre></td><td><pre>78.0</pre></td></tr><tr><td>World version</td><td><pre>4765</pre></td><td><pre>4767</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742112</pre></td><td><pre>1073742113</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ commands.time.no_default_clock: There is no default clock in dimension %s
+ commands.time.no_time_marker_found: Time marker %s does not exist for clock %s
+ commands.time.pause: Paused clock %s
+ commands.time.query.absolute: Clock %s is at %s tick(s)
+ commands.time.query.gametime: The game time is %s tick(s)
+ commands.time.query.timeline: Timeline %s is at %s tick(s)
+ commands.time.query.timeline.repetitions: Timeline %s has passed %s repetition(s)
+ commands.time.resume: Resumed clock %s
+ commands.time.set.absolute: Set %s to %s tick(s)
+ commands.time.set.time_marker: Set %s to time marker %s
+ commands.time.wrong_timeline_for_clock: Timeline %s is not valid for clock %s
+ editGamerule.inGame.button: Edit Game Rules...
+ editGamerule.inGame.disabled.tooltip: Updating game rules requires operator permissions.
+ editGamerule.inGame.discardChanges.message: Are you sure you want to discard your pending game rule changes?
+ editGamerule.inGame.discardChanges.title: Game rule Changes
+ editGamerule.inGame.downloadingGamerules: Retrieving game rules...
+ gui.game_rule.search: Search...
+ options.worldOptions.button: World Options...
+ options.worldOptions.title: World Options
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
- minecraft/tags/block/bamboo_plantable_on.json
- minecraft/tags/block/big_dripleaf_placeable.json
+ minecraft/tags/block/cannot_support_kelp.json
+ minecraft/tags/block/cannot_support_seagrass.json
+ minecraft/tags/block/cannot_support_snow_layer.json
- minecraft/tags/block/dry_vegetation_may_place_on.json
+ minecraft/tags/block/enables_bubble_column_drag_down.json
+ minecraft/tags/block/enables_bubble_column_push_up.json
+ minecraft/tags/block/grows_crops.json
- minecraft/tags/block/mushroom_grow_block.json
+ minecraft/tags/block/overrides_mushroom_light_requirement.json
- minecraft/tags/block/small_dripleaf_placeable.json
- minecraft/tags/block/snow_layer_can_survive_on.json
- minecraft/tags/block/snow_layer_cannot_survive_on.json
+ minecraft/tags/block/support_override_cactus_flower.json
+ minecraft/tags/block/support_override_snow_layer.json
+ minecraft/tags/block/supports_azalea.json
+ minecraft/tags/block/supports_bamboo.json
+ minecraft/tags/block/supports_big_dripleaf.json
+ minecraft/tags/block/supports_cactus.json
+ minecraft/tags/block/supports_chorus_flower.json
+ minecraft/tags/block/supports_chorus_plant.json
+ minecraft/tags/block/supports_cocoa.json
+ minecraft/tags/block/supports_crimson_fungus.json
+ minecraft/tags/block/supports_crimson_roots.json
+ minecraft/tags/block/supports_crops.json
+ minecraft/tags/block/supports_dry_vegetation.json
+ minecraft/tags/block/supports_frogspawn.json
+ minecraft/tags/block/supports_hanging_mangrove_propagule.json
+ minecraft/tags/block/supports_lily_pad.json
+ minecraft/tags/block/supports_mangrove_propagule.json
+ minecraft/tags/block/supports_melon_stem.json
+ minecraft/tags/block/supports_nether_sprouts.json
+ minecraft/tags/block/supports_nether_wart.json
+ minecraft/tags/block/supports_pumpkin_stem.json
+ minecraft/tags/block/supports_small_dripleaf.json
+ minecraft/tags/block/supports_stem_crops.json
+ minecraft/tags/block/supports_sugar_cane_adjacently.json
+ minecraft/tags/block/supports_sugar_cane.json
+ minecraft/tags/block/supports_vegetation.json
+ minecraft/tags/block/supports_warped_fungus.json
+ minecraft/tags/block/supports_warped_roots.json
+ minecraft/tags/block/supports_wither_rose.json
+ minecraft/tags/fluid/bubble_column_can_occupy.json
+ minecraft/tags/fluid/supports_frogspawn.json
+ minecraft/tags/fluid/supports_lily_pad.json
+ minecraft/tags/fluid/supports_sugar_cane_adjacently.json
+ minecraft/world_clock/overworld.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/block/tripwire.png.mcmeta
```

</details>
</details>
<hr/>