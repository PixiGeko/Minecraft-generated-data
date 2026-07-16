## Comparison with [26.3-snapshot-3](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.3-snapshot-3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.3-snapshot-3</th><th>26.3-snapshot-4</th></tr><tr><td>DataPack version</td><td><pre>110.0</pre></td><td><pre>111.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>91.0</pre></td><td><pre>92.0</pre></td></tr><tr><td>World version</td><td><pre>5001</pre></td><td><pre>5003</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742149</pre></td><td><pre>1073742150</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
- org.lwjgl:lwjgl-glfw (natives-linux) V3.4.1
- org.lwjgl:lwjgl-glfw (natives-macos-arm64) V3.4.1
- org.lwjgl:lwjgl-glfw (natives-macos) V3.4.1
- org.lwjgl:lwjgl-glfw (natives-windows-arm64) V3.4.1
- org.lwjgl:lwjgl-glfw (natives-windows-x86) V3.4.1
- org.lwjgl:lwjgl-glfw (natives-windows) V3.4.1
- org.lwjgl:lwjgl-glfw V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-sdl (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-sdl V3.4.1
```

</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute_type
</summary>

```diff
+ minecraft:mob_spawn_settings
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:brewing_fuel
+ minecraft:cooking_fuel
+ minecraft:cushion/color
+ minecraft:mob_visibility
+ minecraft:sign_text_back
+ minecraft:sign_text_front
+ minecraft:villager_food
+ minecraft:waxed
```

</details>
<details>
<summary>
environment_attribute
</summary>

```diff
+ minecraft:gameplay/creature_world_gen_spawn_probability
+ minecraft:gameplay/natural_mob_spawns
```

</details>
<details>
<summary>
loot_condition_type
</summary>

```diff
- minecraft:block_state_property
+ minecraft:match_block
- minecraft:reference
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
- minecraft:reference
```

</details>
<details>
<summary>
slot_source_type
</summary>

```diff
- minecraft:reference
```

</details>
<details>
<summary>
test_environment_definition_type
</summary>

```diff
- minecraft:dimension
```

</details>
<details>
<summary>
worldgen/density_function_type
</summary>

```diff
+ minecraft:ceil
+ minecraft:div
+ minecraft:floor
- minecraft:invert
+ minecraft:lerp
+ minecraft:negate
+ minecraft:reciprocal
+ minecraft:round
+ minecraft:sub
+ minecraft:truncate
```

</details>
<details>
<summary>
worldgen/feature_type
</summary>

```diff
- minecraft:nether_forest_vegetation
- minecraft:twisting_vines
- minecraft:weeping_vines
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/attribute_type.json
</summary>

```diff
+ minecraft:mob_spawn_settings
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:brewing_fuel
+ minecraft:cooking_fuel
+ minecraft:cushion/color
+ minecraft:mob_visibility
+ minecraft:sign_text_back
+ minecraft:sign_text_front
+ minecraft:villager_food
+ minecraft:waxed
```

</details>
<details>
<summary>
universal_tags/environment_attribute.json
</summary>

```diff
+ minecraft:gameplay/creature_world_gen_spawn_probability
+ minecraft:gameplay/natural_mob_spawns
```

</details>
<details>
<summary>
universal_tags/loot_condition_type.json
</summary>

```diff
- minecraft:block_state_property
+ minecraft:match_block
- minecraft:reference
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
- minecraft:reference
```

</details>
<details>
<summary>
universal_tags/slot_source_type.json
</summary>

```diff
- minecraft:reference
```

</details>
<details>
<summary>
universal_tags/test_environment_definition_type.json
</summary>

```diff
- minecraft:dimension
```

</details>
<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
+ minecraft:ceil
+ minecraft:div
+ minecraft:floor
- minecraft:invert
+ minecraft:lerp
+ minecraft:negate
+ minecraft:reciprocal
+ minecraft:round
+ minecraft:sub
+ minecraft:truncate
```

</details>
<details>
<summary>
universal_tags/worldgen/feature_type.json
</summary>

```diff
- minecraft:nether_forest_vegetation
- minecraft:twisting_vines
- minecraft:weeping_vines
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
+ options.debugGuiScale.tooltip: Overrides the debug overlay with a different GUI scale than the rest of the game
+ options.debugGuiScale.unchanged: Unchanged
+ options.fullscreen.exclusive.mode: Exclusive Fullscreen Mode
+ sign.back_text: Back Text:
+ sign.click_actions_disabled: Click actions are disabled for this sign
+ sign.front_text: Front Text:
+ spectator.cannot_teleport: Unable to teleport. The other side is not generated yet.
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.3-snapshot-3</th><th>26.3-snapshot-4</th></tr>
<tr><th align="left"><div style="width:290px">advancements.story.iron_tools.title</div></th><td>Isn't It Iron Pick</td><td>Isn't It Iron Pick?</td></tr>
<tr><th align="left"><div style="width:290px">advMode.trackOutput</div></th><td>Track output</td><td>Track Output</td></tr>
<tr><th align="left"><div style="width:290px">argument.enum.invalid</div></th><td>Invalid value "%s"</td><td>Invalid value '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.pos.outofbounds</div></th><td>That position is outside the allowed boundaries.</td><td>That position is outside the allowed boundaries</td></tr>
<tr><th align="left"><div style="width:290px">chat_restriction.disabled_by_launcher</div></th><td>Chat is restricted by the launcher</td><td>Chat is restricted by the launcher.</td></tr>
<tr><th align="left"><div style="width:290px">commands.kick.owner.failed</div></th><td>Cannot kick server owner in LAN game</td><td>Cannot kick the server owner in a LAN game</td></tr>
<tr><th align="left"><div style="width:290px">commands.op.failed</div></th><td>Nothing changed. The player already is an operator</td><td>Nothing changed. The player is already an operator</td></tr>
<tr><th align="left"><div style="width:290px">commands.perf.started</div></th><td>Started 10 second performance profiling run (use '/perf stop' to stop early)</td><td>Started 10-second performance profiling run (use '/perf stop' to stop early)</td></tr>
<tr><th align="left"><div style="width:290px">commands.stopwatch.create.success</div></th><td>Created Stopwatch '%s'</td><td>Created stopwatch '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.stopwatch.remove.success</div></th><td>Removed Stopwatch '%s'</td><td>Removed stopwatch '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.stopwatch.restart.success</div></th><td>Restarted Stopwatch '%s'</td><td>Restarted stopwatch '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.worldborder.set.grow</div></th><td>Growing the world border to %s blocks wide over %s seconds</td><td>Growing the world border to %s blocks wide over %s second(s)</td></tr>
<tr><th align="left"><div style="width:290px">datapackFailure.safeMode.failed.title</div></th><td>Failed to load world in Safe Mode.</td><td>Failed to load world in Safe Mode</td></tr>
<tr><th align="left"><div style="width:290px">editGamerule.inGame.discardChanges.title</div></th><td>Game rule Changes</td><td>Game Rule Changes</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.doEntityDrops.description</div></th><td>Controls drops from minecarts (including inventories), item frames, boats, etc.</td><td>Controls drops from Minecarts (including inventories), Item Frames, Boats, etc.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.minecraft.fire_spread_radius_around_player.description</div></th><td>The radius in blocks around a player in which fire can spread</td><td>The radius in blocks around a player in which fire can spread.</td></tr>
<tr><th align="left"><div style="width:290px">gui.friends.error.unauthorized</div></th><td>Invalid token supplied. Restart your game and launcher, then try again</td><td>Invalid token supplied. Restart your game and launcher, then try again.</td></tr>
<tr><th align="left"><div style="width:290px">gui.report_to_server</div></th><td>Report To Server</td><td>Report to Server</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.close.question.line1</div></th><td>You can temporarily close your Realm, preventing play while you make adjustments. Open it back up when you're ready. 



This does not cancel your Realms Subscription.</td><td>You can temporarily close your Realm, preventing play while you make adjustments. Open it back up when you're ready.



This does not cancel your Realms subscription.</td></tr>
<tr><th align="left"><div style="width:290px">mco.errorMessage.6002</div></th><td>Terms of service not accepted</td><td>Terms of Service not accepted</td></tr>
<tr><th align="left"><div style="width:290px">mco.snapshot.subscription.info</div></th><td>This is a Snapshot Realm that is paired to the subscription of your Realm '%s'. It will stay active for as long as its paired Realm is.</td><td>This is a Snapshot Realm that is paired with the subscription of your Realm '%s'. It will stay active for as long as its paired Realm is.</td></tr>
<tr><th align="left"><div style="width:290px">mount.onboard</div></th><td>Press %1$s to Dismount</td><td>Press %1$s to dismount</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.confirm_command.signature_required</div></th><td>You are trying to execute a command that will send chat messages using your name.

It can only be run from the chat screen

Command: %s</td><td>You are trying to execute a command that will send chat messages using your name.

It can only be run from the chat screen.

Command: %s</td></tr>
<tr><th align="left"><div style="width:290px">pack.dropRejected.message</div></th><td>The following entries were not valid packs and were not copied:

 %s</td><td>The following entries were not valid packs and were not copied:

%s</td></tr>
<tr><th align="left"><div style="width:290px">quickplay.error.invalid_identifier</div></th><td>Could not find world with the provided identifier</td><td>Could not find a world with the provided identifier</td></tr>
<tr><th align="left"><div style="width:290px">quickplay.error.realm_connect</div></th><td>Could not connect to Realm</td><td>Could not connect to this Realm</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.edit.backupSize</div></th><td>size: %s MB</td><td>Size: %s MB</td></tr>
<tr><th align="left"><div style="width:290px">structure_block.position.x</div></th><td>relative Position x</td><td>relative position x</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.bubble_column.upwards_inside</div></th><td>Bubbles woosh</td><td>Bubbles whoosh</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.copper_golem.no_item_get</div></th><td>Copper Golem is picking up item</td><td>Copper Golem is picking up an item</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.copper_golem.no_item_no_get</div></th><td>Copper Golem can't pick up item</td><td>Copper Golem can't pick up an item</td></tr>
<tr><th align="left"><div style="width:290px">telemetry.event.performance_metrics.description</div></th><td>Knowing the overall performance profile of Minecraft helps us tune and optimize the game for a wide range of machine specifications and operating systems. 

Game version is included to help us compare the performance profile for new versions of Minecraft.</td><td>Knowing the overall performance profile of Minecraft helps us tune and optimize the game for a wide range of machine specifications and operating systems.

Game version is included to help us compare the performance profile for new versions of Minecraft.</td></tr>
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
+ minecraft/number_provider/brewing/speed_default.json
+ minecraft/number_provider/brewing/uses_default.json
+ minecraft/number_provider/cooking/speed_default.json
+ minecraft/number_provider/cooking/time_bamboo.json
+ minecraft/number_provider/cooking/time_blaze_rod.json
+ minecraft/number_provider/cooking/time_boats.json
+ minecraft/number_provider/cooking/time_coal_block.json
+ minecraft/number_provider/cooking/time_coal.json
+ minecraft/number_provider/cooking/time_dried_kelp_block.json
+ minecraft/number_provider/cooking/time_dry_plants.json
+ minecraft/number_provider/cooking/time_hanging_signs.json
+ minecraft/number_provider/cooking/time_lava_bucket.json
+ minecraft/number_provider/cooking/time_roots.json
+ minecraft/number_provider/cooking/time_wood_blocks.json
+ minecraft/number_provider/cooking/time_wood_items_extra_small.json
+ minecraft/number_provider/cooking/time_wood_items_large.json
+ minecraft/number_provider/cooking/time_wood_items_small.json
+ minecraft/number_provider/cooking/time_wood_slabs.json
+ minecraft/number_provider/cooking/time_wool_carpets.json
+ minecraft/number_provider/cooking/time_wool_slabs.json
+ minecraft/number_provider/cooking/time_wool.json
+ minecraft/predicate/block/fast_cooking.json
+ minecraft/tags/block/cushion_uses_collision_shape.json
- minecraft/tags/item/brewing_fuel.json
+ minecraft/worldgen/density_function/overworld_amplified/preliminary_surface_level.json
+ minecraft/worldgen/density_function/overworld_large_biomes/preliminary_surface_level.json
+ minecraft/worldgen/density_function/overworld/ore_vein/copper_density.json
+ minecraft/worldgen/density_function/overworld/ore_vein/gap.json
+ minecraft/worldgen/density_function/overworld/ore_vein/iron_density.json
+ minecraft/worldgen/density_function/overworld/ore_vein/mask.json
+ minecraft/worldgen/density_function/overworld/ore_vein/richness.json
+ minecraft/worldgen/density_function/overworld/ore_vein/toggle.json
+ minecraft/worldgen/density_function/overworld/preliminary_surface_level.json
+ minecraft/worldgen/feature/coral/block_decoration.json
+ minecraft/worldgen/feature/coral/brain_block.json
+ minecraft/worldgen/feature/coral/bubble_block.json
+ minecraft/worldgen/feature/coral/fire_block.json
+ minecraft/worldgen/feature/coral/horn_block.json
+ minecraft/worldgen/feature/coral/tube_block.json
- minecraft/worldgen/feature/crimson_forest_vegetation_bonemeal.json
- minecraft/worldgen/feature/nether_sprouts_bonemeal.json
+ minecraft/worldgen/feature/nylium_bonemeal.json
- minecraft/worldgen/feature/twisting_vines_bonemeal.json
- minecraft/worldgen/feature/warped_forest_vegetation_bonemeal.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/shaders/core/integrate_depth.fsh
+ minecraft/shaders/core/oit_depth_bounds_cull.fsh
```

</details>
</details>
<hr/>