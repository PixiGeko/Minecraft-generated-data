## Comparison with [1.18.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.2)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.18.2</th><th>22w11a</th></tr><tr><td>DataPack version</td><td><code>9</code></td><td><code>10</code></td></tr><tr><td>ResourcePack version</td><td><code>8</code></td><td><code>9</code></td></tr><tr><td>World version</td><td><code>2975</code></td><td><code>3080</code></td></tr><tr><td>Protocol version</td><td><code>758</code></td><td><code>1073741898</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ command_argument_type.txt
- worldgen/structure_feature.txt
+ worldgen/structure_type.txt
```

</details>
<details>
<summary>
activity.txt
</summary>

```diff
+ minecraft:lay_spawn
+ minecraft:swim
+ minecraft:tongue
```

</details>

<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:frogspawn
+ minecraft:mangrove_button
+ minecraft:mangrove_door
+ minecraft:mangrove_fence
+ minecraft:mangrove_fence_gate
+ minecraft:mangrove_leaves
+ minecraft:mangrove_log
+ minecraft:mangrove_planks
+ minecraft:mangrove_pressure_plate
+ minecraft:mangrove_propagule
+ minecraft:mangrove_roots
+ minecraft:mangrove_sign
+ minecraft:mangrove_slab
+ minecraft:mangrove_stairs
+ minecraft:mangrove_trapdoor
+ minecraft:mangrove_wall_sign
+ minecraft:mangrove_wood
+ minecraft:mud
+ minecraft:mud_brick_slab
+ minecraft:mud_brick_stairs
+ minecraft:mud_brick_wall
+ minecraft:mud_bricks
+ minecraft:muddy_mangrove_roots
+ minecraft:ochre_froglight
+ minecraft:packed_mud
+ minecraft:pearlescent_froglight
+ minecraft:potted_mangrove_propagule
+ minecraft:sculk
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
+ minecraft:sculk_vein
+ minecraft:stripped_mangrove_log
+ minecraft:stripped_mangrove_wood
+ minecraft:verdant_froglight
```

</details>
<details>
<summary>
block_entity_type.txt
</summary>

```diff
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
```

</details>




<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:frog
+ minecraft:tadpole
```

</details>


<details>
<summary>
game_event.txt
</summary>

```diff
+ minecraft:entity_dying
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:frog_spawn_egg
+ minecraft:frogspawn
+ minecraft:mangrove_boat
+ minecraft:mangrove_button
+ minecraft:mangrove_door
+ minecraft:mangrove_fence
+ minecraft:mangrove_fence_gate
+ minecraft:mangrove_leaves
+ minecraft:mangrove_log
+ minecraft:mangrove_planks
+ minecraft:mangrove_pressure_plate
+ minecraft:mangrove_propagule
+ minecraft:mangrove_roots
+ minecraft:mangrove_sign
+ minecraft:mangrove_slab
+ minecraft:mangrove_stairs
+ minecraft:mangrove_trapdoor
+ minecraft:mangrove_wood
+ minecraft:mud
+ minecraft:mud_brick_slab
+ minecraft:mud_brick_stairs
+ minecraft:mud_brick_wall
+ minecraft:mud_bricks
+ minecraft:muddy_mangrove_roots
+ minecraft:ochre_froglight
+ minecraft:packed_mud
+ minecraft:pearlescent_froglight
+ minecraft:sculk
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
+ minecraft:sculk_vein
+ minecraft:stripped_mangrove_log
+ minecraft:stripped_mangrove_wood
+ minecraft:tadpole_bucket
+ minecraft:tadpole_spawn_egg
+ minecraft:verdant_froglight
```

</details>






<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:is_in_water
+ minecraft:is_pregnant
```

</details>



<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:sculk_charge
+ minecraft:sculk_charge_pop
+ minecraft:sculk_soul
```

</details>








<details>
<summary>
sensor_type.txt
</summary>

```diff
+ minecraft:frog_attackables
+ minecraft:frog_temptations
+ minecraft:is_in_water
```

</details>
<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.froglight.break
+ minecraft:block.froglight.fall
+ minecraft:block.froglight.hit
+ minecraft:block.froglight.place
+ minecraft:block.froglight.step
+ minecraft:block.frogspawn.break
+ minecraft:block.frogspawn.fall
+ minecraft:block.frogspawn.hatch
+ minecraft:block.frogspawn.hit
+ minecraft:block.frogspawn.place
+ minecraft:block.frogspawn.step
+ minecraft:block.mangrove_roots.break
+ minecraft:block.mangrove_roots.fall
+ minecraft:block.mangrove_roots.hit
+ minecraft:block.mangrove_roots.place
+ minecraft:block.mangrove_roots.step
+ minecraft:block.mud_bricks.break
+ minecraft:block.mud_bricks.fall
+ minecraft:block.mud_bricks.hit
+ minecraft:block.mud_bricks.place
+ minecraft:block.mud_bricks.step
+ minecraft:block.mud.break
+ minecraft:block.mud.fall
+ minecraft:block.mud.hit
+ minecraft:block.mud.place
+ minecraft:block.mud.step
+ minecraft:block.muddy_mangrove_roots.break
+ minecraft:block.muddy_mangrove_roots.fall
+ minecraft:block.muddy_mangrove_roots.hit
+ minecraft:block.muddy_mangrove_roots.place
+ minecraft:block.muddy_mangrove_roots.step
+ minecraft:block.packed_mud.break
+ minecraft:block.packed_mud.fall
+ minecraft:block.packed_mud.hit
+ minecraft:block.packed_mud.place
+ minecraft:block.packed_mud.step
+ minecraft:block.sculk_catalyst.bloom
+ minecraft:block.sculk_catalyst.break
+ minecraft:block.sculk_catalyst.fall
+ minecraft:block.sculk_catalyst.hit
+ minecraft:block.sculk_catalyst.place
+ minecraft:block.sculk_catalyst.step
+ minecraft:block.sculk_shrieker.break
+ minecraft:block.sculk_shrieker.fall
+ minecraft:block.sculk_shrieker.hit
+ minecraft:block.sculk_shrieker.place
+ minecraft:block.sculk_shrieker.step
+ minecraft:block.sculk_vein.break
+ minecraft:block.sculk_vein.fall
+ minecraft:block.sculk_vein.hit
+ minecraft:block.sculk_vein.place
+ minecraft:block.sculk_vein.step
+ minecraft:block.sculk.break
+ minecraft:block.sculk.charge
+ minecraft:block.sculk.fall
+ minecraft:block.sculk.hit
+ minecraft:block.sculk.place
+ minecraft:block.sculk.spread
+ minecraft:block.sculk.step
+ minecraft:entity.frog.ambient
+ minecraft:entity.frog.death
+ minecraft:entity.frog.eat
+ minecraft:entity.frog.hurt
+ minecraft:entity.frog.lay_spawn
+ minecraft:entity.frog.long_jump
+ minecraft:entity.frog.step
+ minecraft:entity.frog.tounge
+ minecraft:entity.tadpole.death
+ minecraft:entity.tadpole.eat
+ minecraft:entity.tadpole.flop
+ minecraft:entity.tadpole.grow_up
+ minecraft:entity.tadpole.hurt
+ minecraft:entity.tadpole.step
+ minecraft:item.bucket.empty_tadpole
+ minecraft:item.bucket.fill_tadpole
+ minecraft:music.overworld.deep_dark
```

</details>







<details>
<summary>
worldgen/density_function_type.txt
</summary>

```diff
- minecraft:terrain_shaper_spline
```

</details>
<details>
<summary>
worldgen/feature.txt
</summary>

```diff
+ minecraft:sculk_patch
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/command_argument_type.json
- universal_tags/worldgen/structure_feature.json
+ universal_tags/worldgen/structure_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:frogspawn
+ minecraft:mangrove_wall_sign
+ minecraft:sculk_shrieker
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:mangrove_button
+ minecraft:mangrove_door
+ minecraft:mangrove_fence
+ minecraft:mangrove_fence_gate
+ minecraft:mangrove_leaves
+ minecraft:mangrove_log
+ minecraft:mangrove_planks
+ minecraft:mangrove_pressure_plate
+ minecraft:mangrove_propagule
+ minecraft:mangrove_roots
+ minecraft:mangrove_sign
+ minecraft:mangrove_slab
+ minecraft:mangrove_stairs
+ minecraft:mangrove_trapdoor
+ minecraft:mangrove_wood
+ minecraft:mud
+ minecraft:mud_brick_slab
+ minecraft:mud_brick_stairs
+ minecraft:mud_brick_wall
+ minecraft:mud_bricks
+ minecraft:muddy_mangrove_roots
+ minecraft:ochre_froglight
+ minecraft:packed_mud
+ minecraft:pearlescent_froglight
+ minecraft:potted_mangrove_propagule
+ minecraft:sculk
+ minecraft:sculk_catalyst
+ minecraft:sculk_vein
+ minecraft:stripped_mangrove_log
+ minecraft:stripped_mangrove_wood
+ minecraft:verdant_froglight
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:frog
+ minecraft:tadpole
```

</details>

<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:frog
+ minecraft:tadpole
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:sculk_shrieker
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:lay_spawn
+ minecraft:swim
+ minecraft:tongue
```

</details>

<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:frogspawn
+ minecraft:mangrove_button
+ minecraft:mangrove_door
+ minecraft:mangrove_fence
+ minecraft:mangrove_fence_gate
+ minecraft:mangrove_leaves
+ minecraft:mangrove_log
+ minecraft:mangrove_planks
+ minecraft:mangrove_pressure_plate
+ minecraft:mangrove_propagule
+ minecraft:mangrove_roots
+ minecraft:mangrove_sign
+ minecraft:mangrove_slab
+ minecraft:mangrove_stairs
+ minecraft:mangrove_trapdoor
+ minecraft:mangrove_wall_sign
+ minecraft:mangrove_wood
+ minecraft:mud
+ minecraft:mud_brick_slab
+ minecraft:mud_brick_stairs
+ minecraft:mud_brick_wall
+ minecraft:mud_bricks
+ minecraft:muddy_mangrove_roots
+ minecraft:ochre_froglight
+ minecraft:packed_mud
+ minecraft:pearlescent_froglight
+ minecraft:potted_mangrove_propagule
+ minecraft:sculk
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
+ minecraft:sculk_vein
+ minecraft:stripped_mangrove_log
+ minecraft:stripped_mangrove_wood
+ minecraft:verdant_froglight
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
```

</details>




<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:frog
+ minecraft:tadpole
```

</details>


<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
+ minecraft:entity_dying
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:frog_spawn_egg
+ minecraft:frogspawn
+ minecraft:mangrove_boat
+ minecraft:mangrove_button
+ minecraft:mangrove_door
+ minecraft:mangrove_fence
+ minecraft:mangrove_fence_gate
+ minecraft:mangrove_leaves
+ minecraft:mangrove_log
+ minecraft:mangrove_planks
+ minecraft:mangrove_pressure_plate
+ minecraft:mangrove_propagule
+ minecraft:mangrove_roots
+ minecraft:mangrove_sign
+ minecraft:mangrove_slab
+ minecraft:mangrove_stairs
+ minecraft:mangrove_trapdoor
+ minecraft:mangrove_wood
+ minecraft:mud
+ minecraft:mud_brick_slab
+ minecraft:mud_brick_stairs
+ minecraft:mud_brick_wall
+ minecraft:mud_bricks
+ minecraft:muddy_mangrove_roots
+ minecraft:ochre_froglight
+ minecraft:packed_mud
+ minecraft:pearlescent_froglight
+ minecraft:sculk
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
+ minecraft:sculk_vein
+ minecraft:stripped_mangrove_log
+ minecraft:stripped_mangrove_wood
+ minecraft:tadpole_bucket
+ minecraft:tadpole_spawn_egg
+ minecraft:verdant_froglight
```

</details>






<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:is_in_water
+ minecraft:is_pregnant
```

</details>



<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:sculk_charge
+ minecraft:sculk_charge_pop
+ minecraft:sculk_soul
```

</details>








<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:frog_attackables
+ minecraft:frog_temptations
+ minecraft:is_in_water
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.froglight.break
+ minecraft:block.froglight.fall
+ minecraft:block.froglight.hit
+ minecraft:block.froglight.place
+ minecraft:block.froglight.step
+ minecraft:block.frogspawn.break
+ minecraft:block.frogspawn.fall
+ minecraft:block.frogspawn.hatch
+ minecraft:block.frogspawn.hit
+ minecraft:block.frogspawn.place
+ minecraft:block.frogspawn.step
+ minecraft:block.mangrove_roots.break
+ minecraft:block.mangrove_roots.fall
+ minecraft:block.mangrove_roots.hit
+ minecraft:block.mangrove_roots.place
+ minecraft:block.mangrove_roots.step
+ minecraft:block.mud_bricks.break
+ minecraft:block.mud_bricks.fall
+ minecraft:block.mud_bricks.hit
+ minecraft:block.mud_bricks.place
+ minecraft:block.mud_bricks.step
+ minecraft:block.mud.break
+ minecraft:block.mud.fall
+ minecraft:block.mud.hit
+ minecraft:block.mud.place
+ minecraft:block.mud.step
+ minecraft:block.muddy_mangrove_roots.break
+ minecraft:block.muddy_mangrove_roots.fall
+ minecraft:block.muddy_mangrove_roots.hit
+ minecraft:block.muddy_mangrove_roots.place
+ minecraft:block.muddy_mangrove_roots.step
+ minecraft:block.packed_mud.break
+ minecraft:block.packed_mud.fall
+ minecraft:block.packed_mud.hit
+ minecraft:block.packed_mud.place
+ minecraft:block.packed_mud.step
+ minecraft:block.sculk_catalyst.bloom
+ minecraft:block.sculk_catalyst.break
+ minecraft:block.sculk_catalyst.fall
+ minecraft:block.sculk_catalyst.hit
+ minecraft:block.sculk_catalyst.place
+ minecraft:block.sculk_catalyst.step
+ minecraft:block.sculk_shrieker.break
+ minecraft:block.sculk_shrieker.fall
+ minecraft:block.sculk_shrieker.hit
+ minecraft:block.sculk_shrieker.place
+ minecraft:block.sculk_shrieker.step
+ minecraft:block.sculk_vein.break
+ minecraft:block.sculk_vein.fall
+ minecraft:block.sculk_vein.hit
+ minecraft:block.sculk_vein.place
+ minecraft:block.sculk_vein.step
+ minecraft:block.sculk.break
+ minecraft:block.sculk.charge
+ minecraft:block.sculk.fall
+ minecraft:block.sculk.hit
+ minecraft:block.sculk.place
+ minecraft:block.sculk.spread
+ minecraft:block.sculk.step
+ minecraft:entity.frog.ambient
+ minecraft:entity.frog.death
+ minecraft:entity.frog.eat
+ minecraft:entity.frog.hurt
+ minecraft:entity.frog.lay_spawn
+ minecraft:entity.frog.long_jump
+ minecraft:entity.frog.step
+ minecraft:entity.frog.tounge
+ minecraft:entity.tadpole.death
+ minecraft:entity.tadpole.eat
+ minecraft:entity.tadpole.flop
+ minecraft:entity.tadpole.grow_up
+ minecraft:entity.tadpole.hurt
+ minecraft:entity.tadpole.step
+ minecraft:item.bucket.empty_tadpole
+ minecraft:item.bucket.fill_tadpole
+ minecraft:music.overworld.deep_dark
```

</details>







<details>
<summary>
universal_tags/worldgen/density_function_type.json
</summary>

```diff
- minecraft:terrain_shaper_spline
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:sculk_patch
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ mangrove_boat.json
+ mangrove_button.json
+ mangrove_door.json
+ mangrove_fence_gate.json
+ mangrove_fence.json
+ mangrove_planks.json
+ mangrove_pressure_plate.json
+ mangrove_sign.json
+ mangrove_slab.json
+ mangrove_stairs.json
+ mangrove_trapdoor.json
+ mangrove_wood.json
+ mud_brick_slab_from_mud_bricks_stonecutting.json
+ mud_brick_slab.json
+ mud_brick_stairs_from_mud_bricks_stonecutting.json
+ mud_brick_stairs.json
+ mud_brick_wall_from_mud_bricks_stonecutting.json
+ mud_brick_wall.json
+ mud_bricks.json
+ muddy_mangrove_roots.json
+ packed_mud.json
+ stripped_mangrove_wood.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ biome.minecraft.deep_dark: Deep Dark
+ block.minecraft.frogspawn: Frogspawn
+ block.minecraft.mangrove_button: Mangrove Button
+ block.minecraft.mangrove_door: Mangrove Door
+ block.minecraft.mangrove_fence_gate: Mangrove Fence Gate
+ block.minecraft.mangrove_fence: Mangrove Fence
+ block.minecraft.mangrove_leaves: Mangrove Leaves
+ block.minecraft.mangrove_log: Mangrove Log
+ block.minecraft.mangrove_planks: Mangrove Planks
+ block.minecraft.mangrove_pressure_plate: Mangrove Pressure Plate
+ block.minecraft.mangrove_propagule: Mangrove Propagule
+ block.minecraft.mangrove_roots: Mangrove Roots
+ block.minecraft.mangrove_sign: Mangrove Sign
+ block.minecraft.mangrove_slab: Mangrove Slab
+ block.minecraft.mangrove_stairs: Mangrove Stairs
+ block.minecraft.mangrove_trapdoor: Mangrove Trapdoor
+ block.minecraft.mangrove_wall_sign: Mangrove Wall Sign
+ block.minecraft.mangrove_wood: Mangrove Wood
+ block.minecraft.mud_brick_slab: Mud Brick Slab
+ block.minecraft.mud_brick_stairs: Mud Brick Stairs
+ block.minecraft.mud_brick_wall: Mud Brick Wall
+ block.minecraft.mud_bricks: Mud Bricks
+ block.minecraft.mud: Mud
+ block.minecraft.muddy_mangrove_roots: Muddy Mangrove Roots
+ block.minecraft.ochre_froglight: Ochre Froglight
+ block.minecraft.packed_mud: Packed Mud
+ block.minecraft.pearlescent_froglight: Pearlescent Froglight
+ block.minecraft.potted_mangrove_propagule: Potted Mangrove Propagule
+ block.minecraft.sculk_catalyst: Sculk Catalyst
+ block.minecraft.sculk_shrieker: Sculk Shrieker
+ block.minecraft.sculk_vein: Sculk Vein
+ block.minecraft.sculk: Sculk
+ block.minecraft.stripped_mangrove_log: Stripped Mangrove Log
+ block.minecraft.stripped_mangrove_wood: Stripped Mangrove Wood
+ block.minecraft.verdant_froglight: Verdant Froglight
- createWorld.customize.preset.bottomless_pit: Bottomless Pit
- createWorld.customize.preset.classic_flat: Classic Flat
- createWorld.customize.preset.desert: Desert
- createWorld.customize.preset.overworld: Overworld
- createWorld.customize.preset.redstone_ready: Redstone Ready
- createWorld.customize.preset.snowy_kingdom: Snowy Kingdom
- createWorld.customize.preset.the_void: The Void
- createWorld.customize.preset.tunnelers_dream: Tunnelers' Dream
- createWorld.customize.preset.water_world: Water World
+ entity.minecraft.frog: Frog
+ entity.minecraft.tadpole: Tadpole
+ flat_world_preset.minecraft.bottomless_pit: Bottomless Pit
+ flat_world_preset.minecraft.classic_flat: Classic Flat
+ flat_world_preset.minecraft.desert: Desert
+ flat_world_preset.minecraft.overworld: Overworld
+ flat_world_preset.minecraft.redstone_ready: Redstone Ready
+ flat_world_preset.minecraft.snowy_kingdom: Snowy Kingdom
+ flat_world_preset.minecraft.the_void: The Void
+ flat_world_preset.minecraft.tunnelers_dream: Tunnelers' Dream
+ flat_world_preset.minecraft.water_world: Water World
+ flat_world_preset.unknown: ???
- generator.amplified: AMPLIFIED
- generator.amplified.info: Notice: Just for fun! Requires a beefy computer.
- generator.debug_all_block_states: Debug Mode
- generator.default: Default
- generator.flat: Superflat
- generator.large_biomes: Large Biomes
+ generator.minecraft.amplified: AMPLIFIED
+ generator.minecraft.amplified.info: Notice: Just for fun! Requires a beefy computer.
+ generator.minecraft.debug_all_block_states: Debug Mode
+ generator.minecraft.flat: Superflat
+ generator.minecraft.large_biomes: Large Biomes
+ generator.minecraft.normal: Default
+ generator.minecraft.single_biome_surface: Single Biome
- generator.single_biome_surface: Single Biome
+ item.minecraft.frog_spawn_egg: Frog Spawn Egg
+ item.minecraft.mangrove_boat: Mangrove Boat
+ item.minecraft.tadpole_bucket: Bucket of Tadpole
+ item.minecraft.tadpole_spawn_egg: Tadpole Spawn Egg
+ options.directionalAudio: Directional Audio
+ options.directionalAudio.off.tooltip: Classic Stereo sound
+ options.directionalAudio.on.tooltip: Uses HRTF-based directional audio to improve the simulation of 3D sound. Requires HRTF compatible audio hardware, and is best experienced with headphones.
+ outOfMemory.message: Minecraft has run out of memory.

This could be caused by a bug in the game or by the Java Virtual Machine not being allocated enough memory.

To prevent level corruption, the current game has quit. We've tried to free up enough memory to let you go back to the main menu and back to playing, but this may not have worked.

Please restart the game if you see this message again.
+ outOfMemory.title: Out of memory!
+ subtitles.block.frogspawn.hatch: Frog hatches
+ subtitles.entity.frog.ambient: Frog croaks
+ subtitles.entity.frog.death: Frog dies
+ subtitles.entity.frog.eat: Frog eats
+ subtitles.entity.frog.hurt: Frog hurts
+ subtitles.entity.frog.lay_spawn: Frog lays spawn
+ subtitles.entity.frog.long_jump: Frog jumps
+ subtitles.entity.tadpole.death: Tadpole dies
+ subtitles.entity.tadpole.flop: Tadpole flops
+ subtitles.entity.tadpole.hurt: Tadpole hurts
```

</details>
<details>
<summary>
Changes
</summary>

```
narration.recipe: Reciple for %s
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
+ reports/biome_parameters/minecraft/nether.json
+ reports/biome_parameters/minecraft/overworld.json
- reports/worldgen/minecraft/dimension/overworld.json
- reports/worldgen/minecraft/dimension/the_end.json
- reports/worldgen/minecraft/dimension/the_nether.json
+ reports/worldgen/minecraft/worldgen/biome/deep_dark.json
+ reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch.json
+ reports/worldgen/minecraft/worldgen/configured_feature/sculk_vein.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/bastion_remnant.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/buried_treasure.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/desert_pyramid.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/end_city.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/fortress.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/igloo.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/jungle_pyramid.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/mansion.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/mineshaft_mesa.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/mineshaft.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/monument.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/nether_fossil.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ocean_ruin_cold.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ocean_ruin_warm.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/pillager_outpost.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_desert.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_jungle.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_mountain.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_nether.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_ocean.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal_swamp.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/ruined_portal.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/shipwreck_beached.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/shipwreck.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/stronghold.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/swamp_hut.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/village_desert.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/village_plains.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/village_savanna.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/village_snowy.json
- reports/worldgen/minecraft/worldgen/configured_structure_feature/village_taiga.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/depth.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/factor.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/offset.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld_large_biomes/offset.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld/jaggedness.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld/offset.json
+ reports/worldgen/minecraft/worldgen/density_function/overworld/ridges_folded.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/classic_flat.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/desert.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/overworld.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/the_void.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
+ reports/worldgen/minecraft/worldgen/flat_level_generator_preset/water_world.json
+ reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch.json
+ reports/worldgen/minecraft/worldgen/placed_feature/sculk_vein.json
+ reports/worldgen/minecraft/worldgen/structure/bastion_remnant.json
+ reports/worldgen/minecraft/worldgen/structure/buried_treasure.json
+ reports/worldgen/minecraft/worldgen/structure/desert_pyramid.json
+ reports/worldgen/minecraft/worldgen/structure/end_city.json
+ reports/worldgen/minecraft/worldgen/structure/fortress.json
+ reports/worldgen/minecraft/worldgen/structure/igloo.json
+ reports/worldgen/minecraft/worldgen/structure/jungle_pyramid.json
+ reports/worldgen/minecraft/worldgen/structure/mansion.json
+ reports/worldgen/minecraft/worldgen/structure/mineshaft_mesa.json
+ reports/worldgen/minecraft/worldgen/structure/mineshaft.json
+ reports/worldgen/minecraft/worldgen/structure/monument.json
+ reports/worldgen/minecraft/worldgen/structure/nether_fossil.json
+ reports/worldgen/minecraft/worldgen/structure/ocean_ruin_cold.json
+ reports/worldgen/minecraft/worldgen/structure/ocean_ruin_warm.json
+ reports/worldgen/minecraft/worldgen/structure/pillager_outpost.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_desert.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_jungle.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_mountain.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_nether.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_ocean.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal_swamp.json
+ reports/worldgen/minecraft/worldgen/structure/ruined_portal.json
+ reports/worldgen/minecraft/worldgen/structure/shipwreck_beached.json
+ reports/worldgen/minecraft/worldgen/structure/shipwreck.json
+ reports/worldgen/minecraft/worldgen/structure/stronghold.json
+ reports/worldgen/minecraft/worldgen/structure/swamp_hut.json
+ reports/worldgen/minecraft/worldgen/structure/village_desert.json
+ reports/worldgen/minecraft/worldgen/structure/village_plains.json
+ reports/worldgen/minecraft/worldgen/structure/village_savanna.json
+ reports/worldgen/minecraft/worldgen/structure/village_snowy.json
+ reports/worldgen/minecraft/worldgen/structure/village_taiga.json
+ reports/worldgen/minecraft/worldgen/world_preset/amplified.json
+ reports/worldgen/minecraft/worldgen/world_preset/debug_all_block_states.json
+ reports/worldgen/minecraft/worldgen/world_preset/flat.json
+ reports/worldgen/minecraft/worldgen/world_preset/large_biomes.json
+ reports/worldgen/minecraft/worldgen/world_preset/normal.json
+ reports/worldgen/minecraft/worldgen/world_preset/single_biome_surface.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/mangrove_fence_gate.json
+ minecraft/advancements/recipes/building_blocks/mangrove_fence.json
+ minecraft/advancements/recipes/building_blocks/mangrove_planks.json
+ minecraft/advancements/recipes/building_blocks/mangrove_slab.json
+ minecraft/advancements/recipes/building_blocks/mangrove_stairs.json
+ minecraft/advancements/recipes/building_blocks/mangrove_wood.json
+ minecraft/advancements/recipes/building_blocks/mud_brick_slab_from_mud_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/mud_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/mud_brick_stairs_from_mud_bricks_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/mud_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/mud_bricks.json
+ minecraft/advancements/recipes/building_blocks/muddy_mangrove_roots.json
+ minecraft/advancements/recipes/building_blocks/packed_mud.json
+ minecraft/advancements/recipes/building_blocks/stripped_mangrove_wood.json
+ minecraft/advancements/recipes/decorations/mangrove_sign.json
+ minecraft/advancements/recipes/decorations/mud_brick_wall_from_mud_bricks_stonecutting.json
+ minecraft/advancements/recipes/decorations/mud_brick_wall.json
+ minecraft/advancements/recipes/redstone/mangrove_button.json
+ minecraft/advancements/recipes/redstone/mangrove_door.json
+ minecraft/advancements/recipes/redstone/mangrove_pressure_plate.json
+ minecraft/advancements/recipes/redstone/mangrove_trapdoor.json
+ minecraft/advancements/recipes/transportation/mangrove_boat.json
+ minecraft/loot_tables/blocks/mangrove_button.json
+ minecraft/loot_tables/blocks/mangrove_door.json
+ minecraft/loot_tables/blocks/mangrove_fence_gate.json
+ minecraft/loot_tables/blocks/mangrove_fence.json
+ minecraft/loot_tables/blocks/mangrove_leaves.json
+ minecraft/loot_tables/blocks/mangrove_log.json
+ minecraft/loot_tables/blocks/mangrove_planks.json
+ minecraft/loot_tables/blocks/mangrove_pressure_plate.json
+ minecraft/loot_tables/blocks/mangrove_propagule.json
+ minecraft/loot_tables/blocks/mangrove_roots.json
+ minecraft/loot_tables/blocks/mangrove_sign.json
+ minecraft/loot_tables/blocks/mangrove_slab.json
+ minecraft/loot_tables/blocks/mangrove_stairs.json
+ minecraft/loot_tables/blocks/mangrove_trapdoor.json
+ minecraft/loot_tables/blocks/mangrove_wood.json
+ minecraft/loot_tables/blocks/mud_brick_slab.json
+ minecraft/loot_tables/blocks/mud_brick_stairs.json
+ minecraft/loot_tables/blocks/mud_brick_wall.json
+ minecraft/loot_tables/blocks/mud_bricks.json
+ minecraft/loot_tables/blocks/mud.json
+ minecraft/loot_tables/blocks/muddy_mangrove_roots.json
+ minecraft/loot_tables/blocks/ochre_froglight.json
+ minecraft/loot_tables/blocks/packed_mud.json
+ minecraft/loot_tables/blocks/pearlescent_froglight.json
+ minecraft/loot_tables/blocks/potted_mangrove_propagule.json
+ minecraft/loot_tables/blocks/sculk_catalyst.json
+ minecraft/loot_tables/blocks/sculk_shrieker.json
+ minecraft/loot_tables/blocks/sculk_vein.json
+ minecraft/loot_tables/blocks/sculk.json
+ minecraft/loot_tables/blocks/stripped_mangrove_log.json
+ minecraft/loot_tables/blocks/stripped_mangrove_wood.json
+ minecraft/loot_tables/blocks/verdant_froglight.json
+ minecraft/loot_tables/entities/frog.json
+ minecraft/loot_tables/entities/tadpole.json
+ minecraft/recipes/mangrove_boat.json
+ minecraft/recipes/mangrove_button.json
+ minecraft/recipes/mangrove_door.json
+ minecraft/recipes/mangrove_fence_gate.json
+ minecraft/recipes/mangrove_fence.json
+ minecraft/recipes/mangrove_planks.json
+ minecraft/recipes/mangrove_pressure_plate.json
+ minecraft/recipes/mangrove_sign.json
+ minecraft/recipes/mangrove_slab.json
+ minecraft/recipes/mangrove_stairs.json
+ minecraft/recipes/mangrove_trapdoor.json
+ minecraft/recipes/mangrove_wood.json
+ minecraft/recipes/mud_brick_slab_from_mud_bricks_stonecutting.json
+ minecraft/recipes/mud_brick_slab.json
+ minecraft/recipes/mud_brick_stairs_from_mud_bricks_stonecutting.json
+ minecraft/recipes/mud_brick_stairs.json
+ minecraft/recipes/mud_brick_wall_from_mud_bricks_stonecutting.json
+ minecraft/recipes/mud_brick_wall.json
+ minecraft/recipes/mud_bricks.json
+ minecraft/recipes/muddy_mangrove_roots.json
+ minecraft/recipes/packed_mud.json
+ minecraft/recipes/stripped_mangrove_wood.json
+ minecraft/tags/blocks/convertable_to_mud.json
+ minecraft/tags/blocks/dragon_transparent.json
+ minecraft/tags/blocks/frog_prefer_jump_to.json
+ minecraft/tags/blocks/mangrove_logs.json
+ minecraft/tags/blocks/polar_bears_spawnable_on_alternate.json
- minecraft/tags/blocks/polar_bears_spawnable_on_in_frozen_ocean.json
+ minecraft/tags/blocks/sculk_replaceable_world_gen.json
+ minecraft/tags/blocks/sculk_replaceable.json
+ minecraft/tags/items/mangrove_logs.json
+ minecraft/tags/worldgen/biome/allows_surface_slime_spawns.json
+ minecraft/tags/worldgen/biome/allows_tropical_fish_spawns_at_any_height.json
+ minecraft/tags/worldgen/biome/has_closer_water_fog.json
+ minecraft/tags/worldgen/biome/is_end.json
+ minecraft/tags/worldgen/biome/is_overworld.json
+ minecraft/tags/worldgen/biome/is_savanna.json
+ minecraft/tags/worldgen/biome/more_frequent_drowned_spawns.json
+ minecraft/tags/worldgen/biome/only_allows_snow_and_gold_rabbits.json
+ minecraft/tags/worldgen/biome/plays_underwater_music.json
+ minecraft/tags/worldgen/biome/polar_bears_spawn_on_alternate_blocks.json
+ minecraft/tags/worldgen/biome/produces_corals_from_bonemeal.json
+ minecraft/tags/worldgen/biome/reduce_water_ambient_spawns.json
+ minecraft/tags/worldgen/biome/required_ocean_monument_surrounding.json
+ minecraft/tags/worldgen/biome/spawns_cold_variant_frogs.json
+ minecraft/tags/worldgen/biome/spawns_warm_variant_frogs.json
+ minecraft/tags/worldgen/biome/stronghold_biased_to.json
+ minecraft/tags/worldgen/biome/water_on_map_outlines.json
+ minecraft/tags/worldgen/biome/without_patrol_spawns.json
+ minecraft/tags/worldgen/biome/without_wandering_trader_spawns.json
+ minecraft/tags/worldgen/biome/without_zombie_sieges.json
- minecraft/tags/worldgen/configured_structure_feature/dolphin_located.json
- minecraft/tags/worldgen/configured_structure_feature/eye_of_ender_located.json
- minecraft/tags/worldgen/configured_structure_feature/mineshaft.json
- minecraft/tags/worldgen/configured_structure_feature/ocean_ruin.json
- minecraft/tags/worldgen/configured_structure_feature/on_ocean_explorer_maps.json
- minecraft/tags/worldgen/configured_structure_feature/on_treasure_maps.json
- minecraft/tags/worldgen/configured_structure_feature/on_woodland_explorer_maps.json
- minecraft/tags/worldgen/configured_structure_feature/ruined_portal.json
- minecraft/tags/worldgen/configured_structure_feature/shipwreck.json
- minecraft/tags/worldgen/configured_structure_feature/village.json
+ minecraft/tags/worldgen/flat_level_generator_preset/visible.json
+ minecraft/tags/worldgen/structure/cats_spawn_as_black.json
+ minecraft/tags/worldgen/structure/cats_spawn_in.json
+ minecraft/tags/worldgen/structure/dolphin_located.json
+ minecraft/tags/worldgen/structure/eye_of_ender_located.json
+ minecraft/tags/worldgen/structure/mineshaft.json
+ minecraft/tags/worldgen/structure/ocean_ruin.json
+ minecraft/tags/worldgen/structure/on_ocean_explorer_maps.json
+ minecraft/tags/worldgen/structure/on_treasure_maps.json
+ minecraft/tags/worldgen/structure/on_woodland_explorer_maps.json
+ minecraft/tags/worldgen/structure/ruined_portal.json
+ minecraft/tags/worldgen/structure/shipwreck.json
+ minecraft/tags/worldgen/structure/village.json
+ minecraft/tags/worldgen/world_preset/extended.json
+ minecraft/tags/worldgen/world_preset/normal.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/frogspawn.json
+ minecraft/blockstates/mangrove_button.json
+ minecraft/blockstates/mangrove_door.json
+ minecraft/blockstates/mangrove_fence_gate.json
+ minecraft/blockstates/mangrove_fence.json
+ minecraft/blockstates/mangrove_leaves.json
+ minecraft/blockstates/mangrove_log.json
+ minecraft/blockstates/mangrove_planks.json
+ minecraft/blockstates/mangrove_pressure_plate.json
+ minecraft/blockstates/mangrove_propagule.json
+ minecraft/blockstates/mangrove_roots.json
+ minecraft/blockstates/mangrove_sign.json
+ minecraft/blockstates/mangrove_slab.json
+ minecraft/blockstates/mangrove_stairs.json
+ minecraft/blockstates/mangrove_trapdoor.json
+ minecraft/blockstates/mangrove_wall_sign.json
+ minecraft/blockstates/mangrove_wood.json
+ minecraft/blockstates/mud_brick_slab.json
+ minecraft/blockstates/mud_brick_stairs.json
+ minecraft/blockstates/mud_brick_wall.json
+ minecraft/blockstates/mud_bricks.json
+ minecraft/blockstates/mud.json
+ minecraft/blockstates/muddy_mangrove_roots.json
+ minecraft/blockstates/ochre_froglight.json
+ minecraft/blockstates/packed_mud.json
+ minecraft/blockstates/pearlescent_froglight.json
+ minecraft/blockstates/potted_mangrove_propagule.json
+ minecraft/blockstates/sculk_catalyst.json
+ minecraft/blockstates/sculk_shrieker.json
+ minecraft/blockstates/sculk_vein.json
+ minecraft/blockstates/sculk.json
+ minecraft/blockstates/stripped_mangrove_log.json
+ minecraft/blockstates/stripped_mangrove_wood.json
+ minecraft/blockstates/verdant_froglight.json
- minecraft/models/block/acacia_door_bottom_hinge.json
+ minecraft/models/block/acacia_door_bottom_left_open.json
+ minecraft/models/block/acacia_door_bottom_left.json
+ minecraft/models/block/acacia_door_bottom_right_open.json
+ minecraft/models/block/acacia_door_bottom_right.json
- minecraft/models/block/acacia_door_bottom.json
- minecraft/models/block/acacia_door_top_hinge.json
+ minecraft/models/block/acacia_door_top_left_open.json
+ minecraft/models/block/acacia_door_top_left.json
+ minecraft/models/block/acacia_door_top_right_open.json
+ minecraft/models/block/acacia_door_top_right.json
- minecraft/models/block/acacia_door_top.json
- minecraft/models/block/birch_door_bottom_hinge.json
+ minecraft/models/block/birch_door_bottom_left_open.json
+ minecraft/models/block/birch_door_bottom_left.json
+ minecraft/models/block/birch_door_bottom_right_open.json
+ minecraft/models/block/birch_door_bottom_right.json
- minecraft/models/block/birch_door_bottom.json
- minecraft/models/block/birch_door_top_hinge.json
+ minecraft/models/block/birch_door_top_left_open.json
+ minecraft/models/block/birch_door_top_left.json
+ minecraft/models/block/birch_door_top_right_open.json
+ minecraft/models/block/birch_door_top_right.json
- minecraft/models/block/birch_door_top.json
- minecraft/models/block/crimson_door_bottom_hinge.json
+ minecraft/models/block/crimson_door_bottom_left_open.json
+ minecraft/models/block/crimson_door_bottom_left.json
+ minecraft/models/block/crimson_door_bottom_right_open.json
+ minecraft/models/block/crimson_door_bottom_right.json
- minecraft/models/block/crimson_door_bottom.json
- minecraft/models/block/crimson_door_top_hinge.json
+ minecraft/models/block/crimson_door_top_left_open.json
+ minecraft/models/block/crimson_door_top_left.json
+ minecraft/models/block/crimson_door_top_right_open.json
+ minecraft/models/block/crimson_door_top_right.json
- minecraft/models/block/crimson_door_top.json
+ minecraft/models/block/cube_north_west_mirrored_all.json
+ minecraft/models/block/cube_north_west_mirrored.json
- minecraft/models/block/dark_oak_door_bottom_hinge.json
+ minecraft/models/block/dark_oak_door_bottom_left_open.json
+ minecraft/models/block/dark_oak_door_bottom_left.json
+ minecraft/models/block/dark_oak_door_bottom_right_open.json
+ minecraft/models/block/dark_oak_door_bottom_right.json
- minecraft/models/block/dark_oak_door_bottom.json
- minecraft/models/block/dark_oak_door_top_hinge.json
+ minecraft/models/block/dark_oak_door_top_left_open.json
+ minecraft/models/block/dark_oak_door_top_left.json
+ minecraft/models/block/dark_oak_door_top_right_open.json
+ minecraft/models/block/dark_oak_door_top_right.json
- minecraft/models/block/dark_oak_door_top.json
+ minecraft/models/block/door_bottom_left_open.json
+ minecraft/models/block/door_bottom_left.json
- minecraft/models/block/door_bottom_rh.json
+ minecraft/models/block/door_bottom_right_open.json
+ minecraft/models/block/door_bottom_right.json
- minecraft/models/block/door_bottom.json
+ minecraft/models/block/door_top_left_open.json
+ minecraft/models/block/door_top_left.json
- minecraft/models/block/door_top_rh.json
+ minecraft/models/block/door_top_right_open.json
+ minecraft/models/block/door_top_right.json
- minecraft/models/block/door_top.json
+ minecraft/models/block/frogspawn.json
- minecraft/models/block/iron_door_bottom_hinge.json
+ minecraft/models/block/iron_door_bottom_left_open.json
+ minecraft/models/block/iron_door_bottom_left.json
+ minecraft/models/block/iron_door_bottom_right_open.json
+ minecraft/models/block/iron_door_bottom_right.json
- minecraft/models/block/iron_door_bottom.json
- minecraft/models/block/iron_door_top_hinge.json
+ minecraft/models/block/iron_door_top_left_open.json
+ minecraft/models/block/iron_door_top_left.json
+ minecraft/models/block/iron_door_top_right_open.json
+ minecraft/models/block/iron_door_top_right.json
- minecraft/models/block/iron_door_top.json
- minecraft/models/block/jungle_door_bottom_hinge.json
+ minecraft/models/block/jungle_door_bottom_left_open.json
+ minecraft/models/block/jungle_door_bottom_left.json
+ minecraft/models/block/jungle_door_bottom_right_open.json
+ minecraft/models/block/jungle_door_bottom_right.json
- minecraft/models/block/jungle_door_bottom.json
- minecraft/models/block/jungle_door_top_hinge.json
+ minecraft/models/block/jungle_door_top_left_open.json
+ minecraft/models/block/jungle_door_top_left.json
+ minecraft/models/block/jungle_door_top_right_open.json
+ minecraft/models/block/jungle_door_top_right.json
- minecraft/models/block/jungle_door_top.json
+ minecraft/models/block/mangrove_button_inventory.json
+ minecraft/models/block/mangrove_button_pressed.json
+ minecraft/models/block/mangrove_button.json
+ minecraft/models/block/mangrove_door_bottom_left_open.json
+ minecraft/models/block/mangrove_door_bottom_left.json
+ minecraft/models/block/mangrove_door_bottom_right_open.json
+ minecraft/models/block/mangrove_door_bottom_right.json
+ minecraft/models/block/mangrove_door_top_left_open.json
+ minecraft/models/block/mangrove_door_top_left.json
+ minecraft/models/block/mangrove_door_top_right_open.json
+ minecraft/models/block/mangrove_door_top_right.json
+ minecraft/models/block/mangrove_fence_gate_open.json
+ minecraft/models/block/mangrove_fence_gate_wall_open.json
+ minecraft/models/block/mangrove_fence_gate_wall.json
+ minecraft/models/block/mangrove_fence_gate.json
+ minecraft/models/block/mangrove_fence_inventory.json
+ minecraft/models/block/mangrove_fence_post.json
+ minecraft/models/block/mangrove_fence_side.json
+ minecraft/models/block/mangrove_leaves.json
+ minecraft/models/block/mangrove_log_horizontal.json
+ minecraft/models/block/mangrove_log.json
+ minecraft/models/block/mangrove_planks.json
+ minecraft/models/block/mangrove_pressure_plate_down.json
+ minecraft/models/block/mangrove_pressure_plate.json
+ minecraft/models/block/mangrove_propagule_hanging_0.json
+ minecraft/models/block/mangrove_propagule_hanging_1.json
+ minecraft/models/block/mangrove_propagule_hanging_2.json
+ minecraft/models/block/mangrove_propagule_hanging_3.json
+ minecraft/models/block/mangrove_propagule_hanging_4.json
+ minecraft/models/block/mangrove_propagule.json
+ minecraft/models/block/mangrove_roots.json
+ minecraft/models/block/mangrove_sign.json
+ minecraft/models/block/mangrove_slab_top.json
+ minecraft/models/block/mangrove_slab.json
+ minecraft/models/block/mangrove_stairs_inner.json
+ minecraft/models/block/mangrove_stairs_outer.json
+ minecraft/models/block/mangrove_stairs.json
+ minecraft/models/block/mangrove_trapdoor_bottom.json
+ minecraft/models/block/mangrove_trapdoor_open.json
+ minecraft/models/block/mangrove_trapdoor_top.json
+ minecraft/models/block/mangrove_wood.json
+ minecraft/models/block/mud_brick_slab_top.json
+ minecraft/models/block/mud_brick_slab.json
+ minecraft/models/block/mud_brick_stairs_inner.json
+ minecraft/models/block/mud_brick_stairs_outer.json
+ minecraft/models/block/mud_brick_stairs.json
+ minecraft/models/block/mud_brick_wall_inventory.json
+ minecraft/models/block/mud_brick_wall_post.json
+ minecraft/models/block/mud_brick_wall_side_tall.json
+ minecraft/models/block/mud_brick_wall_side.json
+ minecraft/models/block/mud_bricks_north_west_mirrored.json
+ minecraft/models/block/mud_bricks.json
+ minecraft/models/block/mud.json
+ minecraft/models/block/muddy_mangrove_roots.json
- minecraft/models/block/oak_door_bottom_hinge.json
+ minecraft/models/block/oak_door_bottom_left_open.json
+ minecraft/models/block/oak_door_bottom_left.json
+ minecraft/models/block/oak_door_bottom_right_open.json
+ minecraft/models/block/oak_door_bottom_right.json
- minecraft/models/block/oak_door_bottom.json
- minecraft/models/block/oak_door_top_hinge.json
+ minecraft/models/block/oak_door_top_left_open.json
+ minecraft/models/block/oak_door_top_left.json
+ minecraft/models/block/oak_door_top_right_open.json
+ minecraft/models/block/oak_door_top_right.json
- minecraft/models/block/oak_door_top.json
+ minecraft/models/block/ochre_froglight_horizontal.json
+ minecraft/models/block/ochre_froglight.json
+ minecraft/models/block/packed_mud.json
+ minecraft/models/block/pearlescent_froglight_horizontal.json
+ minecraft/models/block/pearlescent_froglight.json
+ minecraft/models/block/potted_mangrove_propagule.json
+ minecraft/models/block/sculk_catalyst_bloom.json
+ minecraft/models/block/sculk_catalyst.json
+ minecraft/models/block/sculk_mirrored.json
+ minecraft/models/block/sculk_shrieker.json
+ minecraft/models/block/sculk_vein.json
+ minecraft/models/block/sculk.json
- minecraft/models/block/spruce_door_bottom_hinge.json
+ minecraft/models/block/spruce_door_bottom_left_open.json
+ minecraft/models/block/spruce_door_bottom_left.json
+ minecraft/models/block/spruce_door_bottom_right_open.json
+ minecraft/models/block/spruce_door_bottom_right.json
- minecraft/models/block/spruce_door_bottom.json
- minecraft/models/block/spruce_door_top_hinge.json
+ minecraft/models/block/spruce_door_top_left_open.json
+ minecraft/models/block/spruce_door_top_left.json
+ minecraft/models/block/spruce_door_top_right_open.json
+ minecraft/models/block/spruce_door_top_right.json
- minecraft/models/block/spruce_door_top.json
+ minecraft/models/block/stripped_mangrove_log_horizontal.json
+ minecraft/models/block/stripped_mangrove_log.json
+ minecraft/models/block/stripped_mangrove_wood.json
+ minecraft/models/block/verdant_froglight_horizontal.json
+ minecraft/models/block/verdant_froglight.json
- minecraft/models/block/warped_door_bottom_hinge.json
+ minecraft/models/block/warped_door_bottom_left_open.json
+ minecraft/models/block/warped_door_bottom_left.json
+ minecraft/models/block/warped_door_bottom_right_open.json
+ minecraft/models/block/warped_door_bottom_right.json
- minecraft/models/block/warped_door_bottom.json
- minecraft/models/block/warped_door_top_hinge.json
+ minecraft/models/block/warped_door_top_left_open.json
+ minecraft/models/block/warped_door_top_left.json
+ minecraft/models/block/warped_door_top_right_open.json
+ minecraft/models/block/warped_door_top_right.json
- minecraft/models/block/warped_door_top.json
+ minecraft/models/item/frog_spawn_egg.json
+ minecraft/models/item/frogspawn.json
+ minecraft/models/item/mangrove_boat.json
+ minecraft/models/item/mangrove_button.json
+ minecraft/models/item/mangrove_door.json
+ minecraft/models/item/mangrove_fence_gate.json
+ minecraft/models/item/mangrove_fence.json
+ minecraft/models/item/mangrove_leaves.json
+ minecraft/models/item/mangrove_log.json
+ minecraft/models/item/mangrove_planks.json
+ minecraft/models/item/mangrove_pressure_plate.json
+ minecraft/models/item/mangrove_propagule.json
+ minecraft/models/item/mangrove_roots.json
+ minecraft/models/item/mangrove_sign.json
+ minecraft/models/item/mangrove_slab.json
+ minecraft/models/item/mangrove_stairs.json
+ minecraft/models/item/mangrove_trapdoor.json
+ minecraft/models/item/mangrove_wood.json
+ minecraft/models/item/mud_brick_slab.json
+ minecraft/models/item/mud_brick_stairs.json
+ minecraft/models/item/mud_brick_wall.json
+ minecraft/models/item/mud_bricks.json
+ minecraft/models/item/mud.json
+ minecraft/models/item/muddy_mangrove_roots.json
+ minecraft/models/item/ochre_froglight.json
+ minecraft/models/item/packed_mud.json
+ minecraft/models/item/pearlescent_froglight.json
+ minecraft/models/item/sculk_catalyst.json
+ minecraft/models/item/sculk_shrieker.json
+ minecraft/models/item/sculk_vein.json
+ minecraft/models/item/sculk.json
+ minecraft/models/item/stripped_mangrove_log.json
+ minecraft/models/item/stripped_mangrove_wood.json
+ minecraft/models/item/tadpole_bucket.json
+ minecraft/models/item/tadpole_spawn_egg.json
+ minecraft/models/item/verdant_froglight.json
+ minecraft/particles/sculk_charge_pop.json
+ minecraft/particles/sculk_charge.json
+ minecraft/particles/sculk_soul.json
+ minecraft/textures/block/frogspawn.png
+ minecraft/textures/block/mangrove_door_bottom.png
+ minecraft/textures/block/mangrove_door_top.png
+ minecraft/textures/block/mangrove_leaves.png
+ minecraft/textures/block/mangrove_log_top.png
+ minecraft/textures/block/mangrove_log.png
+ minecraft/textures/block/mangrove_planks.png
+ minecraft/textures/block/mangrove_propagule_hanging.png
+ minecraft/textures/block/mangrove_propagule.png
+ minecraft/textures/block/mangrove_roots_side.png
+ minecraft/textures/block/mangrove_roots_top.png
+ minecraft/textures/block/mangrove_trapdoor.png
+ minecraft/textures/block/mud_bricks.png
+ minecraft/textures/block/mud.png
+ minecraft/textures/block/muddy_mangrove_roots_side.png
+ minecraft/textures/block/muddy_mangrove_roots_top.png
+ minecraft/textures/block/ochre_froglight_side.png
+ minecraft/textures/block/ochre_froglight_top.png
+ minecraft/textures/block/packed_mud.png
+ minecraft/textures/block/pearlescent_froglight_side.png
+ minecraft/textures/block/pearlescent_froglight_top.png
+ minecraft/textures/block/sculk_catalyst_bottom.png
+ minecraft/textures/block/sculk_catalyst_side_bloom.png
+ minecraft/textures/block/sculk_catalyst_side_bloom.png.mcmeta
+ minecraft/textures/block/sculk_catalyst_side.png
+ minecraft/textures/block/sculk_catalyst_top_bloom.png
+ minecraft/textures/block/sculk_catalyst_top_bloom.png.mcmeta
+ minecraft/textures/block/sculk_catalyst_top.png
+ minecraft/textures/block/sculk_shrieker_bottom.png
+ minecraft/textures/block/sculk_shrieker_inner_top.png
+ minecraft/textures/block/sculk_shrieker_inner_top.png.mcmeta
+ minecraft/textures/block/sculk_shrieker_side.png
+ minecraft/textures/block/sculk_shrieker_top.png
+ minecraft/textures/block/sculk_vein.png
+ minecraft/textures/block/sculk_vein.png.mcmeta
+ minecraft/textures/block/sculk.png
+ minecraft/textures/block/sculk.png.mcmeta
+ minecraft/textures/block/stripped_mangrove_log_top.png
+ minecraft/textures/block/stripped_mangrove_log.png
+ minecraft/textures/block/verdant_froglight_side.png
+ minecraft/textures/block/verdant_froglight_top.png
+ minecraft/textures/entity/boat/mangrove.png
+ minecraft/textures/entity/frog/cold_frog.png
+ minecraft/textures/entity/frog/temperate_frog.png
+ minecraft/textures/entity/frog/warm_frog.png
+ minecraft/textures/entity/signs/mangrove.png
+ minecraft/textures/entity/tadpole/tadpole.png
+ minecraft/textures/item/mangrove_boat.png
+ minecraft/textures/item/mangrove_door.png
+ minecraft/textures/item/mangrove_propagule.png
+ minecraft/textures/item/mangrove_sign.png
+ minecraft/textures/item/tadpole_bucket.png
+ minecraft/textures/particle/sculk_charge_0.png
+ minecraft/textures/particle/sculk_charge_1.png
+ minecraft/textures/particle/sculk_charge_2.png
+ minecraft/textures/particle/sculk_charge_3.png
+ minecraft/textures/particle/sculk_charge_4.png
+ minecraft/textures/particle/sculk_charge_5.png
+ minecraft/textures/particle/sculk_charge_6.png
+ minecraft/textures/particle/sculk_charge_pop_0.png
+ minecraft/textures/particle/sculk_charge_pop_1.png
+ minecraft/textures/particle/sculk_charge_pop_2.png
+ minecraft/textures/particle/sculk_charge_pop_3.png
+ minecraft/textures/particle/sculk_soul_0.png
+ minecraft/textures/particle/sculk_soul_1.png
+ minecraft/textures/particle/sculk_soul_10.png
+ minecraft/textures/particle/sculk_soul_2.png
+ minecraft/textures/particle/sculk_soul_3.png
+ minecraft/textures/particle/sculk_soul_4.png
+ minecraft/textures/particle/sculk_soul_5.png
+ minecraft/textures/particle/sculk_soul_6.png
+ minecraft/textures/particle/sculk_soul_7.png
+ minecraft/textures/particle/sculk_soul_8.png
+ minecraft/textures/particle/sculk_soul_9.png
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
splashes
</summary>

```diff
+ Croak team!
+ Flower forest TM perfume
+ Hat Fridays!
+ Nooooooooooooo!
+ RIBBIT!
+ Shriek like a Sculk Shrieker!
+ Who let the frogs out?
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$2
- net.minecraft.commands.arguments.blocks.BlockStateParser$BlockResult
- net.minecraft.commands.arguments.EntityArgument$Info$Template
+ net.minecraft.commands.arguments.EntitySummonArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.item.ItemParser$TagResult
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$ItemPredicate
- net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$TagPredicate
+ net.minecraft.commands.arguments.ItemEnchantmentArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.MobEffectArgument
- net.minecraft.commands.arguments.NbtPathArgument
+ net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
- net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
+ net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info
- net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Serializer
- net.minecraft.commands.arguments.ResourceOrTagLocationArgument$TagResult
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
- net.minecraft.commands.CommandBuildContext$1
- net.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
+ net.minecraft.commands.synchronization.ArgumentSerializer
- net.minecraft.commands.synchronization.ArgumentTypeInfo
- net.minecraft.commands.synchronization.ArgumentTypeInfos
+ net.minecraft.commands.synchronization.ArgumentTypes$Entry
+ net.minecraft.commands.synchronization.brigadier.BrigadierArgumentSerializers
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.FloatArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo
+ net.minecraft.commands.synchronization.brigadier.LongArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$Template
- net.minecraft.commands.synchronization.SingletonArgumentInfo
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$7$1
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$8$1
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.HolderLookup$RegistryLookup
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustColorTransitionOptions$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
- net.minecraft.core.particles.ItemParticleOption$1
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleGroup
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption
- net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
+ net.minecraft.data.BlockFamily$Variant
- net.minecraft.data.BuiltinRegistries
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.info.BiomeParametersDumpReport
- net.minecraft.data.Main
+ net.minecraft.data.tags.ConfiguredStructureTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.WorldPresetTagsProvider
+ net.minecraft.data.worldgen.biome.Biomes
- net.minecraft.data.worldgen.biome.EndBiomes
+ net.minecraft.data.worldgen.biome.NetherBiomes
- net.minecraft.data.worldgen.biome.OverworldBiomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.features.AquaticFeatures
+ net.minecraft.data.worldgen.features.CaveFeatures
- net.minecraft.data.worldgen.features.EndFeatures
+ net.minecraft.data.worldgen.features.FeatureUtils
- net.minecraft.data.worldgen.features.MiscOverworldFeatures
+ net.minecraft.data.worldgen.features.NetherFeatures
- net.minecraft.data.worldgen.features.OreFeatures
- net.minecraft.data.worldgen.features.package-info
+ net.minecraft.data.worldgen.features.PileFeatures
- net.minecraft.data.worldgen.features.TreeFeatures
+ net.minecraft.data.worldgen.features.VegetationFeatures
- net.minecraft.data.worldgen.NoiseData
+ net.minecraft.data.worldgen.package-info
+ net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.placement.AquaticPlacements
+ net.minecraft.data.worldgen.placement.CavePlacements
- net.minecraft.data.worldgen.placement.EndPlacements
+ net.minecraft.data.worldgen.placement.MiscOverworldPlacements
- net.minecraft.data.worldgen.placement.NetherPlacements
+ net.minecraft.data.worldgen.placement.OrePlacements
- net.minecraft.data.worldgen.placement.package-info
- net.minecraft.data.worldgen.placement.PlacementUtils
+ net.minecraft.data.worldgen.placement.TreePlacements
- net.minecraft.data.worldgen.placement.VegetationPlacements
+ net.minecraft.data.worldgen.placement.VillagePlacements
- net.minecraft.data.worldgen.PlainVillagePools
+ net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.ProcessorLists
+ net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.data.worldgen.Structures
+ net.minecraft.data.worldgen.SurfaceRuleData
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.data.worldgen.TerrainProvider
- net.minecraft.data.worldgen.VillagePools
+ net.minecraft.gametest.framework.AfterBatch
- net.minecraft.gametest.framework.BeforeBatch
+ net.minecraft.gametest.framework.ExhaustedAttemptsException
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestHelper$1
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$NbtRecordBuilder
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
+ net.minecraft.nbt.SnbtPrinterTagVisitor
- net.minecraft.nbt.StreamTagVisitor
+ net.minecraft.nbt.StreamTagVisitor$EntryResult
- net.minecraft.nbt.StreamTagVisitor$ValueResult
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
+ net.minecraft.nbt.StringTagVisitor
- net.minecraft.nbt.Tag
+ net.minecraft.nbt.TagParser
- net.minecraft.nbt.TagType
+ net.minecraft.nbt.TagType$1
- net.minecraft.nbt.TagType$2
+ net.minecraft.nbt.TagType$StaticSize
- net.minecraft.nbt.TagType$VariableSize
+ net.minecraft.nbt.TagTypes
- net.minecraft.nbt.TagVisitor
+ net.minecraft.nbt.TextComponentTagVisitor
+ net.minecraft.nbt.visitors.CollectFields
- net.minecraft.nbt.visitors.CollectToTag
+ net.minecraft.nbt.visitors.FieldSelector
- net.minecraft.nbt.visitors.FieldTree
- net.minecraft.nbt.visitors.package-info
+ net.minecraft.nbt.visitors.SkipAll
- net.minecraft.nbt.visitors.SkipAll$1
+ net.minecraft.nbt.visitors.SkipFields
+ net.minecraft.network.chat.BaseComponent
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.CommonComponents
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.FormattedText
+ net.minecraft.network.chat.FormattedText$1
- net.minecraft.network.chat.FormattedText$2
+ net.minecraft.network.chat.FormattedText$3
- net.minecraft.network.chat.FormattedText$4
+ net.minecraft.network.chat.FormattedText$ContentConsumer
- net.minecraft.network.chat.FormattedText$StyledContentConsumer
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.KeybindComponent
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.TextComponent
+ net.minecraft.network.chat.TranslatableComponent
- net.minecraft.network.chat.TranslatableFormatException
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$PacketHolder
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.ConnectionProtocol$PacketSet
- net.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ net.minecraft.network.FriendlyByteBuf
- net.minecraft.network.package-info
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddMobPacket
- net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
- net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
+ net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPingPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundPongPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$10
+ net.minecraft.network.syncher.EntityDataSerializers$11
- net.minecraft.network.syncher.EntityDataSerializers$12
+ net.minecraft.network.syncher.EntityDataSerializers$13
- net.minecraft.network.syncher.EntityDataSerializers$14
+ net.minecraft.network.syncher.EntityDataSerializers$15
- net.minecraft.network.syncher.EntityDataSerializers$16
+ net.minecraft.network.syncher.EntityDataSerializers$17
- net.minecraft.network.syncher.EntityDataSerializers$18
+ net.minecraft.network.syncher.EntityDataSerializers$19
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.EntityDataSerializers$8
+ net.minecraft.network.syncher.EntityDataSerializers$9
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.HolderSetCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryLoader
- net.minecraft.resources.RegistryLoader$Bound
+ net.minecraft.resources.RegistryLoader$ReadCache
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryResourceAccess
- net.minecraft.resources.RegistryResourceAccess$1
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceFilterSection$ResourceLocationPattern
- net.minecraft.server.packs.resources.ResourceThunk$ResourceSupplier
- net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.server.WorldStem$InitConfig
+ net.minecraft.tags.ConfiguredStructureTags
- net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagKey
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$LoadResult
- net.minecraft.tags.TagNetworkSerialization
+ net.minecraft.tags.TagNetworkSerialization$NetworkPayload
- net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.ToFloatFunction$2
- net.minecraft.Util$11
+ net.minecraft.Util$2
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.RandomSwim
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
- net.minecraft.world.entity.animal.frog.ShootTongue$1
- net.minecraft.world.entity.animal.frog.Tadpole
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSource$1FeatureData
- net.minecraft.world.level.biome.BiomeSource$StepFeatureData
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.TerrainShaper
+ net.minecraft.world.level.biome.TerrainShaper$CoordinateCustom
+ net.minecraft.world.level.biome.TerrainShaper$PointCustom
- net.minecraft.world.level.block.DropperBlock
+ net.minecraft.world.level.block.EnchantmentTableBlock
- net.minecraft.world.level.block.EnderChestBlock
- net.minecraft.world.level.block.EndGatewayBlock
+ net.minecraft.world.level.block.EndPortalBlock
- net.minecraft.world.level.block.EndPortalFrameBlock
+ net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrogspawnBlock
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.AzaleaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangroveRootsBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.SculkBehaviour$1
- net.minecraft.world.level.block.SculkCatalystBlock
- net.minecraft.world.level.block.SculkShriekerBlock
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SporeBlossomBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.BlockColumn
- net.minecraft.world.level.chunk.BulkSectionAccess
+ net.minecraft.world.level.chunk.CarvingMask
- net.minecraft.world.level.chunk.CarvingMask$Mask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.storage.ChunkScanAccess
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
+ net.minecraft.world.level.levelgen.DensityFunctions$TerrainShaperSpline$Spline
+ net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
+ net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NoiseEffect
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeCrackSettings
+ net.minecraft.world.level.levelgen.GeodeLayerSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$1
+ net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouter
+ net.minecraft.world.level.levelgen.NoiseRouterData
- net.minecraft.world.level.levelgen.NoiseRouterData$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.NoiseRouterWithOnlyNoises
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlider
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.StructureCheck
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.package-info
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NoiseUtils
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
+ net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FogType
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.MaterialColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.Deserializers
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$InlineSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.Serializer
- net.minecraft.world.level.storage.loot.SerializerType
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.StructureManager
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.LevelChunkTicks
- net.minecraft.world.ticks.LevelTickAccess
+ net.minecraft.world.ticks.LevelTicks
- net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
+ net.minecraft.world.ticks.package-info
+ net.minecraft.world.ticks.ProtoChunkTicks
- net.minecraft.world.ticks.SavedTick
+ net.minecraft.world.ticks.SavedTick$1
- net.minecraft.world.ticks.ScheduledTick
+ net.minecraft.world.ticks.ScheduledTick$1
- net.minecraft.world.ticks.SerializableTickContainer
+ net.minecraft.world.ticks.TickAccess
- net.minecraft.world.ticks.TickContainerAccess
+ net.minecraft.world.ticks.TickPriority
- net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util$5 +1M -1M | +2P -1P
```
```
net.minecraft.Util$9 +2M -3M | -2P
```
```
XXX.advancements.critereon.LocationPredicate$Builder +1M -1M | +1P -1P
```
```
XXX.minecraft.commands.Commands +8M -8M
```
```
XXX.commands.arguments.EntityArgument -2P
```
```
XXX.arguments.blocks.BlockPredicateArgument +5M -3M | +1P -1P
```
```
XXX.arguments.blocks.BlockPredicateArgument$Result -1P
```
```
XXX.arguments.blocks.BlockStateArgument +2M -2M | +1P
```
```
XXX.arguments.item.ItemArgument +2M -2M | +1P
```
```
XXX.arguments.item.ItemParser +15M -11M | +6P -6P
```
```
XXX.minecraft.core.Registry +3M -3M | +8P -3P
```
```
XXX.data.models.BlockModelGenerators +13M -6M
```
```
XXX.data.tags.BiomeTagsProvider +2M -1M
```
```
XXX.data.tags.FluidTagsProvider -1M
```
```
XXX.data.tags.ItemTagsProvider -1M
```
```
XXX.data.worldgen.BiomeDefaultFeatures +1M
```
```
XXX.protocol.game.ClientboundCommandsPacket$Entry +4M -3M | +2P -3P
```
```
XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage +6M -4M
```
```
XXX.minecraft.resources.ResourceLocation +2M
```
```
XXX.minecraft.server.ReloadableServerResources +5M -4M | +1P
```
```
XXX.server.commands.CloneCommands +1M -1M
```
```
XXX.server.commands.FillCommand +1M -1M
```
```
XXX.server.commands.LootCommand +2M -2M
```
```
XXX.server.commands.SetBlockCommand +1M -1M
```
```
XXX.server.dedicated.DedicatedServer +1M
```
```
XXX.server.dedicated.DedicatedServerProperties +1M | +2P
```
```
XXX.server.level.DemoMode +1M -1M
```
```
XXX.server.level.ThreadedLevelLightEngine +10M -6M
```
```
XXX.server.network.ServerGamePacketListenerImpl +1M | +3P
```
```
XXX.server.packs.FolderPackResources +2M -2M
```
```
XXX.server.packs.VanillaPackResources +3M -3M
```
```
XXX.packs.resources.ResourceManager$Empty +3M -2M
```
```
XXX.packs.resources.SimpleResource -2M | -1P
```
```
XXX.minecraft.sounds.SoundEvents +76P
```
```
XXX.minecraft.tags.BiomeTags +20P
```
```
XXX.minecraft.tags.ItemTags +1P
```
```
XXX.minecraft.util.CubicSpline -2P
```
```
XXX.minecraft.util.CubicSpline$Builder +2M -1M
```
```
XXX.minecraft.util.CubicSpline$CoordinateVisitor +1P -1P
```
```
XXX.minecraft.util.ExtraCodecs +1M | +1P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.minecraft.util.ParticleUtils +5M -2M
```
```
XXX.minecraft.util.ToFloatFunction +4M | +3P
```
```
XXX.metrics.profiling.ActiveMetricsRecorder +2M
```
```
XXX.metrics.profiling.MetricsRecorder +1P
```
```
XXX.monster.hoglin.Hoglin +1M -1M
```
```
XXX.monster.piglin.Piglin +1M -1M
```
```
XXX.entity.player.Player +1M -1M
```
```
XXX.entity.schedule.Activity +3P
```
```
XXX.world.inventory.BeaconMenu +1M -1M
```
```
XXX.world.item.Items +36P
```
```
XXX.level.block.MultifaceBlock +6M -14M | +1P
```
```
XXX.level.chunk.ImposterProtoChunk +4M -4M
```
```
XXX.level.dimension.LevelStem +4M -1M
```
```
XXX.level.gameevent.EuclideanGameEventDispatcher +3P
```
```
XXX.level.levelgen.Beardifier +2M -3M
```
```
XXX.level.levelgen.DebugLevelSource +7M -9M
```
```
XXX.level.levelgen.DensityFunctions +1M -1M
```
```
XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction +1M | +1P
```
```
XXX.level.levelgen.DensityFunctions$Spline +2M -3M | +1P -2P
```
```
XXX.levelgen.carver.CarvingContext +2M -1M | +2P -1P
```
```
XXX.structure.pools.FeaturePoolElement +4M -4M
```
```
XXX.structure.pools.JigsawPlacement +3M -3M
```
```
XXX.structure.pools.SinglePoolElement +6M -6M
```

</details>


















<details>
<summary>
net.minecraft.Util$5
</summary>

```diff
- void <init>(Path,Path)
+ void <init>(Path)
```

</details>

<details>
<summary>
net.minecraft.Util$9
</summary>

```diff
+ Object apply(Object)
+ String toString()
+ void <init>(Function)
- void <init>(String)
- void run()
```

</details>


















































<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate$Builder
</summary>

```diff
+ LocationPredicate$Builder setFeature(ResourceKey)
- LocationPredicate$Builder setStructure(ResourceKey)
```

</details>

































<details>
<summary>
net.minecraft.commands.Commands
</summary>

```diff
- boolean lambda$createValidator$5(Commands$ParseFunction,String)
+ boolean lambda$createValidator$6(Commands$ParseFunction,String)
- boolean lambda$fillUsableCommands$3(SharedSuggestionProvider)
+ boolean lambda$fillUsableCommands$4(SharedSuggestionProvider)
- int lambda$fillUsableCommands$4(CommandContext)
+ int lambda$fillUsableCommands$5(CommandContext)
- Style lambda$performCommand$1(String,Style)
- Style lambda$performCommand$2(MutableComponent,Style)
+ Style lambda$performCommand$2(String,Style)
+ Style lambda$performCommand$3(MutableComponent,Style)
- void <init>(Commands$CommandSelection,CommandBuildContext)
+ void <init>(Commands$CommandSelection)
- void lambda$new$0(CommandContext,boolean,int)
+ void lambda$new$0(CommandNode,CommandNode,CommandNode,Collection)
+ void lambda$new$1(CommandContext,boolean,int)
- void lambda$validate$6(CommandDispatcher,CommandNode,CommandNode,CommandNode,Collection)
```

</details>












<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument
</summary>

```diff
+ BlockPredicateArgument blockPredicate()
- BlockPredicateArgument blockPredicate(CommandBuildContext)
- BlockPredicateArgument$Result lambda$parse$0(BlockStateParser$BlockResult)
- BlockPredicateArgument$Result lambda$parse$1(BlockStateParser$TagResult)
- BlockPredicateArgument$Result parse(HolderLookup,StringReader)
+ Message lambda$static$0(Object)
+ void <init>()
- void <init>(CommandBuildContext)
```

</details>

<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockStateArgument
</summary>

```diff
+ BlockStateArgument block()
- BlockStateArgument block(CommandBuildContext)
+ void <init>()
- void <init>(CommandBuildContext)
```

</details>








<details>
<summary>
net.minecraft.commands.arguments.item.ItemArgument
</summary>

```diff
+ ItemArgument item()
- ItemArgument item(CommandBuildContext)
+ void <init>()
- void <init>(CommandBuildContext)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemParser
</summary>

```diff
+ CommandSyntaxException lambda$readItem$2(int,ResourceLocation)
- CommandSyntaxException lambda$readItem$5(int,ResourceLocation)
- CommandSyntaxException lambda$readTag$6(int,ResourceLocation)
- CompletableFuture fillSuggestions(HolderLookup,SuggestionsBuilder,boolean)
+ CompletableFuture fillSuggestions(SuggestionsBuilder,Registry)
+ CompletableFuture lambda$static$1(SuggestionsBuilder,Registry)
- CompletableFuture suggestItem(SuggestionsBuilder)
+ CompletableFuture suggestItemIdOrTag(SuggestionsBuilder,Registry)
- CompletableFuture suggestItemIdOrTag(SuggestionsBuilder)
+ CompletableFuture suggestOpenNbt(SuggestionsBuilder,Registry)
- CompletableFuture suggestOpenNbt(SuggestionsBuilder)
+ CompletableFuture suggestTag(SuggestionsBuilder,Registry)
- CompletableFuture suggestTag(SuggestionsBuilder)
+ CompoundTag getNbt()
- Either parseForTesting(HolderLookup,StringReader)
- IllegalStateException lambda$parseForItem$2()
+ Item getItem()
+ ItemParser parse()
- ItemParser$ItemResult lambda$parseForTesting$3(ItemParser,Holder)
- ItemParser$ItemResult parseForItem(HolderLookup,StringReader)
- ItemParser$TagResult lambda$parseForTesting$4(ItemParser,HolderSet)
- Message lambda$static$1(Object)
+ TagKey getTag()
- void <init>(HolderLookup,StringReader,boolean)
+ void <init>(StringReader,boolean)
- void parse()
```

</details>




























<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ StructureFeature lambda$static$41(Registry)
- StructurePieceType lambda$static$42(Registry)
+ StructurePieceType lambda$static$43(Registry)
- StructurePlacementType lambda$static$41(Registry)
+ StructurePlacementType lambda$static$42(Registry)
- StructureType lambda$static$43(Registry)
```

</details>




























<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- BlockStateGenerator createDoor(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ BlockStateGenerator createDoor(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
- BlockStateGenerator createNorthWestMirroredCubeGenerator(Block,ResourceLocation,TextureMapping,BiConsumer)
- PropertyDispatch$C4 configureDoorHalf(PropertyDispatch$C4,DoubleBlockHalf,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ PropertyDispatch$C4 configureDoorHalf(PropertyDispatch$C4,DoubleBlockHalf,ResourceLocation,ResourceLocation)
+ Variant lambda$createJigsaw$47(FrontAndTop)
- Variant lambda$createJigsaw$48(FrontAndTop)
+ Variant lambda$createRespawnAnchor$46(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$47(ResourceLocation[],Integer)
- Variant lambda$createSculkCatalyst$46(ResourceLocation,ResourceLocation,Boolean)
- void createFrogspawnBlock()
- void createMangrovePropagule()
- void createMuddyMangroveRoots()
- void createSculkCatalyst()
- void createSculkShrieker()
+ void lambda$run$48(BlockFamily)
- void lambda$run$49(BlockFamily)
+ void lambda$run$49(SpawnEggItem)
- void lambda$run$50(SpawnEggItem)
```

</details>

































<details>
<summary>
net.minecraft.data.tags.BiomeTagsProvider
</summary>

```diff
+ String getName()
- void lambda$addTags$0(TagsProvider$TagAppender,ResourceKey)
- void lambda$addTags$1(TagsProvider$TagAppender,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.data.tags.FluidTagsProvider
</summary>

```diff
+ String getName()
```

</details>
<details>
<summary>
net.minecraft.data.tags.ItemTagsProvider
</summary>

```diff
+ String getName()
```

</details>



<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
- void addSculk(BiomeGenerationSettings$Builder)
```

</details>

<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
</summary>

```diff
+ boolean build(List)
- boolean canBuild(IntSet)
- boolean canResolve(IntSet)
+ int lambda$build$0(CommandContext)
+ void <init>(ArgumentBuilder,byte,int,int[])
- void <init>(ClientboundCommandsPacket$NodeStub,int,int,int[])
- void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
</summary>

```diff
- boolean lambda$listResources$0(ResourceKey,Map$Entry)
+ Collection listResources(ResourceKey)
- DataResult lambda$getResource$3(DataResult,DynamicOps,Decoder)
- Map listResources(ResourceKey)
- Optional getResource(ResourceKey)
+ Optional parseElement(DynamicOps,ResourceKey,ResourceKey,Decoder)
- RegistryResourceAccess$EntryThunk lambda$listResources$2(Map$Entry)
+ RegistryResourceAccess$ParsedEntry lambda$parseElement$1(RegistryResourceAccess$InMemoryStorage$Entry,Object)
- ResourceKey lambda$listResources$1(Map$Entry)
+ Stream lambda$listResources$0(ResourceKey,ResourceKey)
```

</details>

<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
- String toLanguageKey()
- String toLanguageKey(String)
```

</details>









<details>
<summary>
net.minecraft.server.ReloadableServerResources
</summary>

```diff
+ List lambda$updateRegistryTags$3(Map$Entry)
- List lambda$updateRegistryTags$4(Map$Entry)
+ ReloadableServerResources lambda$loadResources$0(ReloadableServerResources,Object)
- ReloadableServerResources lambda$loadResources$1(ReloadableServerResources,Object)
+ TagKey lambda$updateRegistryTags$2(ResourceKey,Map$Entry)
- TagKey lambda$updateRegistryTags$3(ResourceKey,Map$Entry)
- void lambda$loadResources$0(ReloadableServerResources,Object,Throwable)
+ void lambda$updateRegistryTags$1(RegistryAccess,TagManager$LoadResult)
- void lambda$updateRegistryTags$2(RegistryAccess,TagManager$LoadResult)
```

</details>















<details>
<summary>
net.minecraft.server.commands.CloneCommands
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>









<details>
<summary>
net.minecraft.server.commands.FillCommand
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>







<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ ArgumentBuilder lambda$register$14(ArgumentBuilder,LootCommand$DropConsumer)
- ArgumentBuilder lambda$register$14(CommandBuildContext,ArgumentBuilder,LootCommand$DropConsumer)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>











<details>
<summary>
net.minecraft.server.commands.SetBlockCommand
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>


















<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- int getMaxChainedNeighborUpdates()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- void <clinit>()
```

</details>
















<details>
<summary>
net.minecraft.server.level.DemoMode
</summary>

```diff
- void handleBlockBreakAction(BlockPos,ServerboundPlayerActionPacket$Action,Direction,int,int)
+ void handleBlockBreakAction(BlockPos,ServerboundPlayerActionPacket$Action,Direction,int)
```

</details>









<details>
<summary>
net.minecraft.server.level.ThreadedLevelLightEngine
</summary>

```diff
+ ChunkAccess lambda$lightChunk$20(ChunkAccess,ChunkPos)
- ChunkAccess lambda$lightChunk$23(ChunkAccess,ChunkPos)
- ChunkAccess lambda$retainData$17(ChunkPos,ChunkAccess)
- CompletableFuture retainData(ChunkAccess)
+ String lambda$lightChunk$19(ChunkPos,boolean)
- String lambda$lightChunk$22(ChunkPos,boolean)
- String lambda$retainData$18(ChunkPos)
+ void lambda$lightChunk$17(ChunkAccess,BlockPos)
+ void lambda$lightChunk$18(ChunkAccess,ChunkPos,boolean)
- void lambda$lightChunk$20(ChunkAccess,BlockPos)
- void lambda$lightChunk$21(ChunkAccess,ChunkPos,boolean)
+ void lambda$lightChunk$21(ChunkPos,Runnable)
- void lambda$lightChunk$24(ChunkPos,Runnable)
- void lambda$retainData$19(ChunkPos,Runnable)
+ void lambda$tryScheduleUpdate$22()
- void lambda$tryScheduleUpdate$25()
```

</details>









<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void ackBlockChangesUpTo(int)
```

</details>










<details>
<summary>
net.minecraft.server.packs.FolderPackResources
</summary>

```diff
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
+ void listResources(File,int,String,List,String,Predicate)
- void listResources(File,String,List,String,Predicate)
```

</details>

<details>
<summary>
net.minecraft.server.packs.VanillaPackResources
</summary>

```diff
- boolean lambda$getResources$1(Path)
+ boolean lambda$getResources$1(Predicate,Path)
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
+ void getResources(Collection,int,String,Path,String,Predicate)
- void getResources(Collection,String,Path,String,Predicate)
```

</details>









<details>
<summary>
net.minecraft.server.packs.resources.ResourceManager$Empty
</summary>

```diff
+ Collection listResources(String,Predicate)
+ List getResources(ResourceLocation)
- List getResourceStack(ResourceLocation)
- Map listResources(String,Predicate)
- Map listResourceStacks(String,Predicate)
```

</details>



<details>
<summary>
net.minecraft.server.packs.resources.SimpleResource
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
```

</details>



































<details>
<summary>
net.minecraft.util.CubicSpline$Builder
</summary>

```diff
- CubicSpline$Builder addPoint(float,CubicSpline)
- CubicSpline$Builder addPoint(float,float)
+ float lambda$new$0(Float)
```

</details>



<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- DataResult lambda$static$27(String)
```

</details>












<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float catmullrom(float,float,float,float,float)
```

</details>

<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
- Vec3 getRandomSpeedRanges(Random)
- Vec3 lambda$spawnParticlesOnBlockFaces$0(Level)
- void spawnParticleOnFace(Level,BlockPos,Direction,ParticleOptions,Vec3,double)
+ void spawnParticleOnFace(Level,BlockPos,Direction,ParticleOptions)
- void spawnParticlesOnBlockFace(Level,BlockPos,ParticleOptions,IntProvider,Direction,Supplier,double)
- void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,IntProvider)
+ void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,UniformInt)
```

</details>






<details>
<summary>
net.minecraft.util.ToFloatFunction
</summary>

```diff
- float lambda$static$0(float)
- ToFloatFunction comap(Function)
- ToFloatFunction createUnlimited(Float2FloatFunction)
- void <clinit>()
```

</details>























































































































































<details>
<summary>
net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
</summary>

```diff
- void cancel()
- void cleanup(Collection)
```

</details>



































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>




















<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>











































<details>
<summary>
net.minecraft.world.inventory.BeaconMenu
</summary>

```diff
+ void updateEffects(int,int)
- void updateEffects(MobEffect,MobEffect)
```

</details>






































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.MultifaceBlock
</summary>

```diff
+ boolean canSpread(BlockState,BlockGetter,BlockPos,Direction)
+ boolean canSpreadInto(BlockState)
+ boolean canSpreadToFace(BlockGetter,BlockPos,Direction)
- boolean isValidStateForPlacement(BlockGetter,BlockState,BlockPos,Direction)
+ boolean lambda$canSpread$5(BlockState,BlockGetter,BlockPos,Direction,Direction)
- boolean lambda$hasAnyFace$2(BlockState,Direction)
+ boolean lambda$hasAnyFace$6(BlockState,Direction)
- boolean lambda$hasAnyVacantFace$3(BlockState,Direction)
+ boolean lambda$hasAnyVacantFace$7(BlockState,Direction)
+ boolean lambda$spreadFromFaceTowardRandomDirection$4(BlockState,LevelAccessor,BlockPos,Direction,boolean,Direction)
+ boolean lambda$spreadFromRandomFaceTowardRandomDirection$2(BlockState,Direction)
+ boolean lambda$spreadFromRandomFaceTowardRandomDirection$3(BlockState,ServerLevel,BlockPos,Random,Direction)
+ boolean spreadFromFaceTowardDirection(BlockState,LevelAccessor,BlockPos,Direction,Direction,boolean)
+ boolean spreadFromFaceTowardRandomDirection(BlockState,LevelAccessor,BlockPos,Direction,Random,boolean)
+ boolean spreadFromRandomFaceTowardRandomDirection(BlockState,ServerLevel,BlockPos,Random)
+ boolean spreadToFace(LevelAccessor,BlockPos,Direction,boolean)
- byte pack(Collection)
+ Optional getSpreadFromFaceTowardDirection(BlockState,BlockGetter,BlockPos,Direction,Direction)
- Set availableFaces(BlockState)
- Set unpack(byte)
```

</details>






















<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
+ LongSet getReferencesForFeature(ConfiguredStructureFeature)
- LongSet getReferencesForStructure(Structure)
+ StructureStart getStartForFeature(ConfiguredStructureFeature)
- StructureStart getStartForStructure(Structure)
+ void addReferenceForFeature(ConfiguredStructureFeature,long)
- void addReferenceForStructure(Structure,long)
+ void setStartForFeature(ConfiguredStructureFeature,StructureStart)
- void setStartForStructure(Structure,StructureStart)
```

</details>













<details>
<summary>
net.minecraft.world.level.dimension.LevelStem
</summary>

```diff
- boolean lambda$keysInOrder$1(ResourceKey)
+ boolean stable(long,Registry)
- boolean stable(Registry)
- Stream keysInOrder(Stream)
- void lambda$sortMap$2(Registry,WritableRegistry,ResourceKey)
```

</details>


























<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
+ boolean lambda$new$1(ConfiguredStructureFeature)
+ void <init>(StructureFeatureManager,ChunkAccess)
- void <init>(StructureManager,ChunkAccess)
- void lambda$new$1(ChunkPos,int,int,StructureStart)
+ void lambda$new$2(ChunkPos,int,int,StructureStart)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ ChunkGenerator withSeed(long)
+ Climate$Sampler climateSampler()
- CompletableFuture fillFromNoise(Executor,Blender,RandomState,StructureManager,ChunkAccess)
+ CompletableFuture fillFromNoise(Executor,Blender,StructureFeatureManager,ChunkAccess)
- int getBaseHeight(int,int,Heightmap$Types,LevelHeightAccessor,RandomState)
+ int getBaseHeight(int,int,Heightmap$Types,LevelHeightAccessor)
- NoiseColumn getBaseColumn(int,int,LevelHeightAccessor,RandomState)
+ NoiseColumn getBaseColumn(int,int,LevelHeightAccessor)
+ void addDebugScreenInfo(List,BlockPos)
- void addDebugScreenInfo(List,RandomState,BlockPos)
+ void applyBiomeDecoration(WorldGenLevel,ChunkAccess,StructureFeatureManager)
- void applyBiomeDecoration(WorldGenLevel,ChunkAccess,StructureManager)
+ void applyCarvers(WorldGenRegion,long,BiomeManager,StructureFeatureManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess,GenerationStep$Carving)
+ void buildSurface(WorldGenRegion,StructureFeatureManager,ChunkAccess)
- void buildSurface(WorldGenRegion,StructureManager,RandomState,ChunkAccess)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions
</summary>

```diff
- DensityFunction spline(CubicSpline)
+ DensityFunction terrainShaperSpline(DensityFunction,DensityFunction,DensityFunction,DensityFunctions$TerrainShaperSpline$SplineType,double,double)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
</summary>

```diff
- float getHeightValue(SimplexNoise,int,int)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions$Spline
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- DensityFunctions$Spline$Coordinate lambda$mapAll$0(DensityFunction$Visitor,DensityFunctions$Spline$Coordinate)
+ ToFloatFunction lambda$mapAll$1(DensityFunction$Visitor,ToFloatFunction)
+ void <init>(CubicSpline,double,double)
- void <init>(CubicSpline)
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarvingContext
</summary>

```diff
- RandomState randomState()
- void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk,RandomState,SurfaceRules$RuleSource)
+ void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk)
```

</details>
















































<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
</summary>

```diff
+ boolean place(StructureManager,WorldGenLevel,StructureFeatureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
- boolean place(StructureTemplateManager,WorldGenLevel,StructureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
+ BoundingBox getBoundingBox(StructureManager,BlockPos,Rotation)
- BoundingBox getBoundingBox(StructureTemplateManager,BlockPos,Rotation)
+ List getShuffledJigsawBlocks(StructureManager,BlockPos,Rotation,Random)
- List getShuffledJigsawBlocks(StructureTemplateManager,BlockPos,Rotation,Random)
+ Vec3i getSize(StructureManager,Rotation)
- Vec3i getSize(StructureTemplateManager,Rotation)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
</summary>

```diff
+ Optional addPieces(PieceGeneratorSupplier$Context,JigsawPlacement$PieceFactory,BlockPos,boolean,boolean)
- Optional addPieces(Structure$GenerationContext,Holder,int,JigsawPlacement$PieceFactory,BlockPos,boolean,Optional)
+ void addPieces(RegistryAccess,PoolElementStructurePiece,int,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,List,Random,LevelHeightAccessor)
- void addPieces(RegistryAccess,PoolElementStructurePiece,int,JigsawPlacement$PieceFactory,ChunkGenerator,StructureTemplateManager,List,Random,LevelHeightAccessor,RandomState)
- void lambda$addPieces$0(PoolElementStructurePiece,int,int,int,int,Registry,JigsawPlacement$PieceFactory,ChunkGenerator,StructureTemplateManager,WorldgenRandom,BoundingBox,boolean,LevelHeightAccessor,Structure$GenerationContext,StructurePiecesBuilder)
+ void lambda$addPieces$0(PoolElementStructurePiece,JigsawConfiguration,int,int,int,Registry,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,WorldgenRandom,BoundingBox,boolean,LevelHeightAccessor,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
</summary>

```diff
+ boolean place(StructureManager,WorldGenLevel,StructureFeatureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
- boolean place(StructureTemplateManager,WorldGenLevel,StructureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
+ BoundingBox getBoundingBox(StructureManager,BlockPos,Rotation)
- BoundingBox getBoundingBox(StructureTemplateManager,BlockPos,Rotation)
+ List getDataMarkers(StructureManager,BlockPos,Rotation,boolean)
- List getDataMarkers(StructureTemplateManager,BlockPos,Rotation,boolean)
+ List getShuffledJigsawBlocks(StructureManager,BlockPos,Rotation,Random)
- List getShuffledJigsawBlocks(StructureTemplateManager,BlockPos,Rotation,Random)
+ StructureTemplate getTemplate(StructureManager)
- StructureTemplate getTemplate(StructureTemplateManager)
+ Vec3i getSize(StructureManager,Rotation)
- Vec3i getSize(StructureTemplateManager,Rotation)
```

</details>







<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.blaze3d.font.package-info
+ com.mojang.blaze3d.font.RawGlyph
- com.mojang.blaze3d.font.SheetGlyphInfo
- com.mojang.blaze3d.font.SpaceProvider$SpaceGlyphInfo
+ com.mojang.blaze3d.package-info
- com.mojang.blaze3d.pipeline.MainTarget
+ com.mojang.blaze3d.pipeline.MainTarget$AttachmentState
- com.mojang.blaze3d.pipeline.MainTarget$Dimension
+ com.mojang.blaze3d.pipeline.package-info
+ com.mojang.blaze3d.pipeline.RenderCall
- com.mojang.blaze3d.pipeline.RenderPipeline
+ com.mojang.blaze3d.pipeline.RenderTarget
- com.mojang.blaze3d.pipeline.TextureTarget
- com.mojang.blaze3d.platform.ClipboardManager
+ com.mojang.blaze3d.platform.DebugMemoryUntracker
- com.mojang.blaze3d.platform.DisplayData
- com.mojang.blaze3d.platform.GlConst
+ com.mojang.blaze3d.platform.GlDebug
- com.mojang.blaze3d.platform.GlDebug$LogEntry
+ com.mojang.blaze3d.platform.GlStateManager
- com.mojang.blaze3d.platform.GlStateManager$BlendState
+ com.mojang.blaze3d.platform.GlStateManager$BooleanState
- com.mojang.blaze3d.platform.GlStateManager$ColorLogicState
+ com.mojang.blaze3d.platform.GlStateManager$ColorMask
- com.mojang.blaze3d.platform.GlStateManager$CullState
+ com.mojang.blaze3d.platform.GlStateManager$DepthState
- com.mojang.blaze3d.platform.GlStateManager$DestFactor
+ com.mojang.blaze3d.platform.GlStateManager$LogicOp
- com.mojang.blaze3d.platform.GlStateManager$PolygonOffsetState
+ com.mojang.blaze3d.platform.GlStateManager$ScissorState
- com.mojang.blaze3d.platform.GlStateManager$SourceFactor
+ com.mojang.blaze3d.platform.GlStateManager$StencilFunc
- com.mojang.blaze3d.platform.GlStateManager$StencilState
+ com.mojang.blaze3d.platform.GlStateManager$TextureState
- com.mojang.blaze3d.platform.GlStateManager$Viewport
+ com.mojang.blaze3d.platform.GlUtil
+ com.mojang.blaze3d.platform.GLX
- com.mojang.blaze3d.platform.InputConstants
+ com.mojang.blaze3d.platform.InputConstants$Key
- com.mojang.blaze3d.platform.InputConstants$Type
+ com.mojang.blaze3d.platform.Lighting
- com.mojang.blaze3d.platform.MacosUtil
+ com.mojang.blaze3d.platform.MemoryTracker
- com.mojang.blaze3d.platform.Monitor
+ com.mojang.blaze3d.platform.MonitorCreator
- com.mojang.blaze3d.platform.NativeImage
+ com.mojang.blaze3d.platform.NativeImage$Format
- com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
+ com.mojang.blaze3d.platform.NativeImage$WriteCallback
- com.mojang.blaze3d.platform.package-info
- com.mojang.blaze3d.platform.PngInfo
+ com.mojang.blaze3d.platform.PngInfo$StbReader
- com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ com.mojang.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
- com.mojang.blaze3d.platform.ScreenManager
+ com.mojang.blaze3d.platform.TextureUtil
- com.mojang.blaze3d.platform.VideoMode
+ com.mojang.blaze3d.platform.Window
- com.mojang.blaze3d.platform.Window$WindowInitFailed
+ com.mojang.blaze3d.platform.WindowEventHandler
+ com.mojang.blaze3d.preprocessor.GlslPreprocessor
- com.mojang.blaze3d.preprocessor.GlslPreprocessor$Context
+ com.mojang.blaze3d.preprocessor.package-info
- com.mojang.blaze3d.shaders.AbstractUniform
+ com.mojang.blaze3d.shaders.BlendMode
- com.mojang.blaze3d.shaders.Effect
+ com.mojang.blaze3d.shaders.EffectProgram
- com.mojang.blaze3d.shaders.EffectProgram$1
+ com.mojang.blaze3d.shaders.FogShape
+ com.mojang.blaze3d.shaders.package-info
- com.mojang.blaze3d.shaders.Program
+ com.mojang.blaze3d.shaders.Program$Type
- com.mojang.blaze3d.shaders.ProgramManager
+ com.mojang.blaze3d.shaders.Shader
- com.mojang.blaze3d.shaders.Uniform
- com.mojang.blaze3d.systems.RenderSystem
+ com.mojang.blaze3d.systems.RenderSystem$1
- com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ com.mojang.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- com.mojang.blaze3d.systems.TimerQuery
- com.mojang.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
- net.minecraft.client.animation.AnimationChannel
- net.minecraft.client.animation.AnimationChannel$Interpolations
- net.minecraft.client.animation.AnimationChannel$Targets
- net.minecraft.client.animation.AnimationDefinition$Builder
- net.minecraft.client.animation.definitions.package-info
- net.minecraft.client.animation.KeyframeAnimations
+ net.minecraft.client.Game
- net.minecraft.client.Game$Metrics
+ net.minecraft.client.GraphicsStatus
- net.minecraft.client.GraphicsStatus$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlainTextButton
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.SliderButton
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.StateSwitchingButton
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.TooltipAccessor
+ net.minecraft.client.gui.components.VolumeSlider
- net.minecraft.client.gui.components.Widget
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$1
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
+ net.minecraft.client.gui.font.glyphs.WhiteGlyph
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.achievement.StatsUpdateListener
+ net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
- net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.KeyBindsList
+ net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
- net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry$1
+ net.minecraft.client.gui.screens.controls.KeyBindsList$Entry
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
+ net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.KeyBindsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.debug.package-info
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AnvilScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen$1
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
- net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
+ net.minecraft.client.gui.screens.inventory.BookViewScreen
- net.minecraft.client.gui.screens.inventory.BookViewScreen$1
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
- net.minecraft.client.gui.screens.inventory.BrewingStandScreen
+ net.minecraft.client.gui.screens.inventory.CartographyTableScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.ContainerScreen
+ net.minecraft.client.gui.screens.inventory.CraftingScreen
- net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HopperScreen
- net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
+ net.minecraft.client.gui.screens.inventory.InventoryScreen
- net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.LecternScreen
- net.minecraft.client.gui.screens.inventory.LecternScreen$1
+ net.minecraft.client.gui.screens.inventory.LoomScreen
- net.minecraft.client.gui.screens.inventory.MenuAccess
+ net.minecraft.client.gui.screens.inventory.MerchantScreen
- net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
+ net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.package-info
- net.minecraft.client.gui.screens.inventory.PageButton
+ net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
- net.minecraft.client.gui.screens.inventory.SignEditScreen
+ net.minecraft.client.gui.screens.inventory.SmithingScreen
- net.minecraft.client.gui.screens.inventory.SmokerScreen
+ net.minecraft.client.gui.screens.inventory.StonecutterScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTextTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.Realms32bitWarningScreen
+ net.minecraft.client.gui.screens.multiplayer.SafetyScreen
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ net.minecraft.client.gui.screens.multiplayer.WarningScreen
+ net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.packs.package-info
- net.minecraft.client.gui.screens.packs.PackSelectionModel
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen
- net.minecraft.client.gui.screens.packs.PackSelectionScreen$1
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
- net.minecraft.client.gui.screens.packs.TransferableSelectionList
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe
- net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- net.minecraft.client.gui.screens.recipebook.package-info
+ net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.RecipeBookPage
+ net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
- net.minecraft.client.gui.screens.recipebook.RecipeButton
+ net.minecraft.client.gui.screens.recipebook.RecipeCollection
- net.minecraft.client.gui.screens.recipebook.RecipeShownListener
+ net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
- net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$NarratableSearchResult
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SimpleOptionsSubScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.social.package-info
+ net.minecraft.client.gui.screens.social.PlayerEntry
- net.minecraft.client.gui.screens.social.PlayerEntry$1
+ net.minecraft.client.gui.screens.social.PlayerEntry$2
- net.minecraft.client.gui.screens.social.PlayerEntry$3
+ net.minecraft.client.gui.screens.social.PlayerEntry$4
- net.minecraft.client.gui.screens.social.PlayerSocialManager
+ net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.TitleScreen$1
- net.minecraft.client.gui.screens.TitleScreen$Warning32Bit
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.WinScreen$CreditsReader
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$OperationFailedException
+ net.minecraft.client.gui.screens.worldselection.package-info
- net.minecraft.client.gui.screens.worldselection.PresetEditor
+ net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext$Updater
- net.minecraft.client.gui.screens.worldselection.WorldOpenFlows
+ net.minecraft.client.gui.screens.worldselection.WorldPreset
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$2
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$4
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$6
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
+ net.minecraft.client.gui.spectator.categories.package-info
+ net.minecraft.client.gui.spectator.categories.SpectatorPage
- net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- net.minecraft.client.gui.spectator.package-info
- net.minecraft.client.gui.spectator.PlayerMenuItem
+ net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenu
+ net.minecraft.client.gui.spectator.SpectatorMenu$1
- net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenuItem
- net.minecraft.client.gui.spectator.SpectatorMenuListener
+ net.minecraft.client.GuiMessage
- net.minecraft.client.HotbarManager
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
+ net.minecraft.client.KeyMapping
+ net.minecraft.client.main.GameConfig
- net.minecraft.client.main.GameConfig$FolderData
+ net.minecraft.client.main.GameConfig$GameData
- net.minecraft.client.main.GameConfig$ServerData
+ net.minecraft.client.main.GameConfig$UserData
- net.minecraft.client.main.Main
+ net.minecraft.client.main.Main$1
- net.minecraft.client.main.Main$2
+ net.minecraft.client.main.Main$3
+ net.minecraft.client.main.package-info
- net.minecraft.client.main.SilentInitException
- net.minecraft.client.model.AbstractZombieModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AnimationUtils
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.AxolotlModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BookModel
- net.minecraft.client.model.CatModel
+ net.minecraft.client.model.ChestedHorseModel
- net.minecraft.client.model.ChickenModel
+ net.minecraft.client.model.CodModel
- net.minecraft.client.model.ColorableAgeableListModel
+ net.minecraft.client.model.ColorableHierarchicalModel
- net.minecraft.client.model.CowModel
+ net.minecraft.client.model.CreeperModel
- net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.dragon.DragonHeadModel
+ net.minecraft.client.model.dragon.package-info
+ net.minecraft.client.model.DrownedModel
- net.minecraft.client.model.ElytraModel
+ net.minecraft.client.model.EndermanModel
- net.minecraft.client.model.EndermiteModel
+ net.minecraft.client.model.EntityModel
- net.minecraft.client.model.EvokerFangsModel
+ net.minecraft.client.model.FoxModel
- net.minecraft.client.model.FrogModel
+ net.minecraft.client.model.geom.builders.CubeDefinition
- net.minecraft.client.model.geom.builders.CubeDeformation
+ net.minecraft.client.model.geom.builders.CubeListBuilder
- net.minecraft.client.model.geom.builders.LayerDefinition
+ net.minecraft.client.model.geom.builders.MaterialDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
+ net.minecraft.client.model.geom.builders.package-info
+ net.minecraft.client.model.geom.builders.PartDefinition
- net.minecraft.client.model.geom.builders.UVPair
- net.minecraft.client.model.geom.EntityModelSet
+ net.minecraft.client.model.geom.LayerDefinitions
- net.minecraft.client.model.geom.ModelLayerLocation
+ net.minecraft.client.model.geom.ModelLayers
- net.minecraft.client.model.geom.ModelPart
+ net.minecraft.client.model.geom.ModelPart$Cube
- net.minecraft.client.model.geom.ModelPart$Polygon
+ net.minecraft.client.model.geom.ModelPart$Vertex
- net.minecraft.client.model.geom.ModelPart$Visitor
- net.minecraft.client.model.geom.package-info
+ net.minecraft.client.model.geom.PartNames
- net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.package-info
- net.minecraft.client.model.TridentModel
+ net.minecraft.client.model.TropicalFishModelA
- net.minecraft.client.model.TropicalFishModelB
+ net.minecraft.client.model.TurtleModel
- net.minecraft.client.model.VexModel
+ net.minecraft.client.model.VillagerHeadModel
- net.minecraft.client.model.VillagerModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
+ net.minecraft.client.MouseHandler
- net.minecraft.client.multiplayer.ClientAdvancements
+ net.minecraft.client.multiplayer.ClientAdvancements$Listener
- net.minecraft.client.multiplayer.ClientChunkCache
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
- net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
+ net.minecraft.client.multiplayer.ClientPacketListener
- net.minecraft.client.multiplayer.ClientPacketListener$1
+ net.minecraft.client.multiplayer.ClientSuggestionProvider
- net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
- net.minecraft.client.multiplayer.prediction.PredictiveAction
- net.minecraft.client.multiplayer.resolver.AddressCheck
+ net.minecraft.client.multiplayer.resolver.AddressCheck$1
- net.minecraft.client.multiplayer.resolver.package-info
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
- net.minecraft.client.multiplayer.resolver.ServerAddress
+ net.minecraft.client.multiplayer.resolver.ServerAddressResolver
- net.minecraft.client.multiplayer.resolver.ServerNameResolver
+ net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
- net.minecraft.client.NarratorStatus
+ net.minecraft.client.Option
- net.minecraft.client.Option$1
- net.minecraft.client.OptionInstance
- net.minecraft.client.OptionInstance$IntRange
- net.minecraft.client.OptionInstance$OptionInstanceSliderButton
- net.minecraft.client.OptionInstance$UnitDouble
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BlockMarker
- net.minecraft.client.particle.BlockMarker$Provider
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
- net.minecraft.client.particle.CritParticle$MagicProvider
+ net.minecraft.client.particle.CritParticle$Provider
- net.minecraft.client.particle.DragonBreathParticle
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
- net.minecraft.client.particle.DripParticle$DripHangParticle
+ net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
+ net.minecraft.client.particle.DripParticle$DripstoneLavaFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneLavaHangProvider
+ net.minecraft.client.particle.DripParticle$DripstoneWaterFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneWaterHangProvider
+ net.minecraft.client.particle.DripParticle$FallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallingParticle
+ net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
- net.minecraft.client.particle.DripParticle$HoneyFallProvider
+ net.minecraft.client.particle.DripParticle$HoneyHangProvider
- net.minecraft.client.particle.DripParticle$HoneyLandProvider
+ net.minecraft.client.particle.DripParticle$LavaFallProvider
- net.minecraft.client.particle.DripParticle$LavaHangProvider
+ net.minecraft.client.particle.DripParticle$LavaLandProvider
- net.minecraft.client.particle.DripParticle$NectarFallProvider
+ net.minecraft.client.particle.DripParticle$ObsidianTearFallProvider
- net.minecraft.client.particle.DripParticle$ObsidianTearHangProvider
+ net.minecraft.client.particle.DripParticle$ObsidianTearLandProvider
- net.minecraft.client.particle.DripParticle$SporeBlossomFallProvider
+ net.minecraft.client.particle.DripParticle$WaterFallProvider
- net.minecraft.client.particle.DripParticle$WaterHangProvider
+ net.minecraft.client.particle.DustColorTransitionParticle
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.DustParticleBase
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
- net.minecraft.client.particle.EnchantmentTableParticle$Provider
+ net.minecraft.client.particle.EndRodParticle
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$Provider
+ net.minecraft.client.particle.FireworkParticles
- net.minecraft.client.particle.FireworkParticles$1
+ net.minecraft.client.particle.FireworkParticles$FlashProvider
- net.minecraft.client.particle.FireworkParticles$OverlayParticle
+ net.minecraft.client.particle.FireworkParticles$SparkParticle
- net.minecraft.client.particle.FireworkParticles$SparkProvider
+ net.minecraft.client.particle.FireworkParticles$Starter
- net.minecraft.client.particle.FlameParticle
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
+ net.minecraft.client.particle.GlowParticle
- net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
+ net.minecraft.client.particle.GlowParticle$GlowSquidProvider
- net.minecraft.client.particle.GlowParticle$ScrapeProvider
+ net.minecraft.client.particle.GlowParticle$WaxOffProvider
- net.minecraft.client.particle.GlowParticle$WaxOnProvider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.ParticleDescription
- net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleRenderType
+ net.minecraft.client.particle.ParticleRenderType$1
- net.minecraft.client.particle.ParticleRenderType$2
+ net.minecraft.client.particle.ParticleRenderType$3
- net.minecraft.client.particle.ParticleRenderType$4
+ net.minecraft.client.particle.ParticleRenderType$5
- net.minecraft.client.particle.ParticleRenderType$6
+ net.minecraft.client.particle.PlayerCloudParticle
- net.minecraft.client.particle.PlayerCloudParticle$Provider
+ net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
- net.minecraft.client.particle.PortalParticle
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
- net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SculkChargeParticle$Provider
- net.minecraft.client.particle.SculkChargePopParticle$Provider
+ net.minecraft.client.particle.SimpleAnimatedParticle
- net.minecraft.client.particle.SingleQuadParticle
+ net.minecraft.client.particle.SmokeParticle
- net.minecraft.client.particle.SmokeParticle$Provider
+ net.minecraft.client.particle.SnowflakeParticle
- net.minecraft.client.particle.SnowflakeParticle$Provider
+ net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$EmissiveProvider
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GlowSquidRenderer
+ net.minecraft.client.renderer.entity.GoatRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.NoopRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.commands.arguments.blocks.BlockPredicateArgument$1
- net.minecraft.commands.arguments.blocks.BlockStateParser$TagResult
- net.minecraft.commands.arguments.EntityArgument$Info
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.item.ItemParser$ItemResult
+ net.minecraft.commands.arguments.item.ItemPredicateArgument$Result
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
- net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceKeyArgument$Serializer
- net.minecraft.commands.arguments.ResourceOrTagLocationArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceOrTagLocationArgument$TagResult
- net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
+ net.minecraft.commands.arguments.ScoreHolderArgument$Result
- net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.ScoreHolderArgument$Serializer
- net.minecraft.commands.CommandBuildContext
- net.minecraft.commands.CommandBuildContext$2
- net.minecraft.commands.synchronization.ArgumentTypeInfo$Template
+ net.minecraft.commands.synchronization.ArgumentTypes
- net.minecraft.commands.synchronization.ArgumentUtils
- net.minecraft.commands.synchronization.brigadier.DoubleArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.DoubleArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.FloatArgumentInfo$Template
- net.minecraft.commands.synchronization.brigadier.IntegerArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.IntegerArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.LongArgumentInfo$Template
+ net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer
- net.minecraft.commands.synchronization.brigadier.StringArgumentSerializer$1
+ net.minecraft.commands.synchronization.EmptyArgumentSerializer
- net.minecraft.commands.synchronization.SingletonArgumentInfo$Template
- net.minecraft.core.dispenser.DispenseItemBehavior$27
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShearsDispenseItemBehavior
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.HolderLookup
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
- net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.DustColorTransitionOptions
- net.minecraft.core.particles.DustColorTransitionOptions$1
+ net.minecraft.core.particles.DustParticleOptions
- net.minecraft.core.particles.DustParticleOptions$1
+ net.minecraft.core.particles.DustParticleOptionsBase
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleGroup
+ net.minecraft.core.particles.ParticleOptions
- net.minecraft.core.particles.ParticleOptions$Deserializer
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.particles.VibrationParticleOption
+ net.minecraft.core.particles.VibrationParticleOption$1
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.BuiltinRegistries
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.Main
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.biome.Biomes
+ net.minecraft.data.worldgen.biome.EndBiomes
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.DimensionTypes
+ net.minecraft.data.worldgen.features.AquaticFeatures
- net.minecraft.data.worldgen.features.CaveFeatures
+ net.minecraft.data.worldgen.features.EndFeatures
- net.minecraft.data.worldgen.features.FeatureUtils
+ net.minecraft.data.worldgen.features.MiscOverworldFeatures
- net.minecraft.data.worldgen.features.NetherFeatures
+ net.minecraft.data.worldgen.features.OreFeatures
+ net.minecraft.data.worldgen.features.package-info
- net.minecraft.data.worldgen.features.PileFeatures
+ net.minecraft.data.worldgen.features.TreeFeatures
- net.minecraft.data.worldgen.features.VegetationFeatures
+ net.minecraft.data.worldgen.NoiseData
- net.minecraft.data.worldgen.package-info
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.placement.AquaticPlacements
- net.minecraft.data.worldgen.placement.CavePlacements
+ net.minecraft.data.worldgen.placement.EndPlacements
- net.minecraft.data.worldgen.placement.MiscOverworldPlacements
+ net.minecraft.data.worldgen.placement.NetherPlacements
- net.minecraft.data.worldgen.placement.OrePlacements
+ net.minecraft.data.worldgen.placement.package-info
+ net.minecraft.data.worldgen.placement.PlacementUtils
- net.minecraft.data.worldgen.placement.TreePlacements
+ net.minecraft.data.worldgen.placement.VegetationPlacements
- net.minecraft.data.worldgen.placement.VillagePlacements
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.SurfaceRuleData
+ net.minecraft.data.worldgen.TaigaVillagePools
- net.minecraft.data.worldgen.TerrainProvider
+ net.minecraft.data.worldgen.VillagePools
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.GlobalTestReporter
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.MultipleTestTracker$1
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.Language$1
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.CompoundTag$2
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.ListTag$2
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtIo$1
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StreamTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
+ net.minecraft.nbt.StreamTagVisitor$ValueResult
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagType$2
- net.minecraft.nbt.TagType$StaticSize
+ net.minecraft.nbt.TagType$VariableSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
+ net.minecraft.nbt.visitors.CollectToTag
- net.minecraft.nbt.visitors.FieldSelector
+ net.minecraft.nbt.visitors.FieldTree
+ net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.nbt.visitors.SkipAll$1
- net.minecraft.nbt.visitors.SkipFields
- net.minecraft.network.chat.BaseComponent
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.TextComponent
- net.minecraft.network.chat.TranslatableComponent
+ net.minecraft.network.chat.TranslatableFormatException
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$PacketHolder
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
+ net.minecraft.network.protocol.game.ClientboundAddVibrationSignalPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPingPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$2
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$3
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$4
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action$5
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResourcePackPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundPongPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.game.ServerPacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.HolderSetCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryLoader
- net.minecraft.resources.RegistryLoader$Bound
+ net.minecraft.resources.RegistryLoader$ReadCache
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryResourceAccess
- net.minecraft.resources.RegistryResourceAccess$1
- net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceFilterSection
- net.minecraft.server.packs.resources.ResourceFilterSection$ResourceLocationPattern
- net.minecraft.server.packs.resources.ResourceThunk$ResourceSupplier
- net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.server.WorldStem$InitConfig
+ net.minecraft.tags.ConfiguredStructureTags
- net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$OptionalElementEntry
- net.minecraft.tags.Tag$OptionalTagEntry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.TagKey
+ net.minecraft.tags.TagLoader
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$LoadResult
- net.minecraft.tags.TagNetworkSerialization
+ net.minecraft.tags.TagNetworkSerialization$NetworkPayload
- net.minecraft.tags.TagNetworkSerialization$TagOutput
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.ToFloatFunction$2
- net.minecraft.Util$11
+ net.minecraft.Util$2
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.RandomSwim
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
- net.minecraft.world.entity.animal.frog.ShootTongue$1
- net.minecraft.world.entity.animal.frog.Tadpole
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Entity
- net.minecraft.world.entity.Entity$1
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSource$1FeatureData
- net.minecraft.world.level.biome.BiomeSource$StepFeatureData
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.TerrainShaper
+ net.minecraft.world.level.biome.TerrainShaper$CoordinateCustom
+ net.minecraft.world.level.biome.TerrainShaper$PointCustom
- net.minecraft.world.level.block.DropperBlock
+ net.minecraft.world.level.block.EnchantmentTableBlock
- net.minecraft.world.level.block.EnderChestBlock
- net.minecraft.world.level.block.EndGatewayBlock
+ net.minecraft.world.level.block.EndPortalBlock
- net.minecraft.world.level.block.EndPortalFrameBlock
+ net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityTicker
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrogspawnBlock
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.AzaleaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangroveRootsBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.SculkBehaviour$1
- net.minecraft.world.level.block.SculkCatalystBlock
- net.minecraft.world.level.block.SculkShriekerBlock
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SporeBlossomBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$Settings
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.BlockColumn
- net.minecraft.world.level.chunk.BulkSectionAccess
+ net.minecraft.world.level.chunk.CarvingMask
- net.minecraft.world.level.chunk.CarvingMask$Mask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.storage.ChunkScanAccess
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
+ net.minecraft.world.level.levelgen.DensityFunctions$TerrainShaperSpline$Spline
+ net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
+ net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NoiseEffect
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.GeodeBlockSettings
- net.minecraft.world.level.levelgen.GeodeCrackSettings
+ net.minecraft.world.level.levelgen.GeodeLayerSettings
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$1
+ net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouter
+ net.minecraft.world.level.levelgen.NoiseRouterData
- net.minecraft.world.level.levelgen.NoiseRouterData$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.NoiseRouterWithOnlyNoises
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlider
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.StructureCheck
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.package-info
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NoiseUtils
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
+ net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FogType
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.MaterialColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.Deserializers
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.GsonAdapterFactory
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$Builder
- net.minecraft.world.level.storage.loot.GsonAdapterFactory$InlineSerializer
+ net.minecraft.world.level.storage.loot.GsonAdapterFactory$JsonAdapter
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.IntRange$Serializer
- net.minecraft.world.level.storage.loot.ItemModifierManager
+ net.minecraft.world.level.storage.loot.ItemModifierManager$FunctionSequence
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.PredicateManager$CompositePredicate
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue$InlineSerializer
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue$Serializer
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue$Serializer
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator$Serializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$InlineSerializer
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider$Serializer
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.Serializer
- net.minecraft.world.level.storage.loot.SerializerType
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.StructureManager
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.LevelChunkTicks
- net.minecraft.world.ticks.LevelTickAccess
+ net.minecraft.world.ticks.LevelTicks
- net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
+ net.minecraft.world.ticks.package-info
+ net.minecraft.world.ticks.ProtoChunkTicks
- net.minecraft.world.ticks.SavedTick
+ net.minecraft.world.ticks.SavedTick$1
- net.minecraft.world.ticks.ScheduledTick
+ net.minecraft.world.ticks.ScheduledTick$1
- net.minecraft.world.ticks.SerializableTickContainer
+ net.minecraft.world.ticks.TickAccess
- net.minecraft.world.ticks.TickContainerAccess
+ net.minecraft.world.ticks.TickPriority
- net.minecraft.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.font.GlyphInfo -2M | +1P
```
```
XXX.blaze3d.font.TrueTypeGlyphProvider$Glyph +1M -7M
```
```
XXX.mojang.realmsclient.RealmsMainScreen +1M -1M
```
```
net.minecraft.Util$5 +1M -1M | +2P -1P
```
```
net.minecraft.Util$9 +2M -3M | -2P
```
```
XXX.advancements.critereon.LocationPredicate$Builder +1M -1M | +1P -1P
```
```
XXX.minecraft.client.CycleOption +8M -10M
```
```
XXX.minecraft.client.Minecraft +34M -43M | +3P
```
```
XXX.minecraft.client.Options +44M -7M | +16P -10P
```
```
XXX.minecraft.client.Options$4 +1P
```
```
XXX.gui.components.BossHealthOverlay +1M
```
```
XXX.gui.components.CycleButton +1M -1M | +1P -1P
```
```
XXX.gui.screens.AccessibilityOptionsScreen +1M -1M | -1P
```
```
XXX.gui.screens.ChatOptionsScreen -1M | -1P
```
```
XXX.gui.screens.MouseSettingsScreen +1M -1M | -1P
```
```
XXX.gui.screens.OptionsScreen -1M | -1P
```
```
XXX.gui.screens.OutOfMemoryScreen +1P
```
```
XXX.client.model.HierarchicalModel +3M
```
```
XXX.client.resources.AssetIndex +1M -1M
```
```
XXX.client.resources.DefaultClientPackResources +1M -1M
```
```
XXX.client.resources.DirectAssetIndex +2M -3M
```
```
XXX.client.resources.PackResourcesAdapterV4 +1M -1M
```
```
XXX.commands.arguments.ResourceOrTagLocationArgument +1M -1M
```
```
XXX.arguments.blocks.BlockPredicateArgument$TagPredicate +2M -1M | +1P -1P
```
```
XXX.arguments.blocks.BlockStateParser +28M -24M | +6P -4P
```
```
XXX.arguments.item.ItemInput +3M -1M | +1P -1P
```
```
XXX.arguments.item.ItemPredicateArgument +8M -5M | +1P -1P
```
```
XXX.minecraft.core.Direction +2M
```
```
XXX.minecraft.core.Direction8 +2M | +1P
```
```
XXX.minecraft.core.MappedRegistry +1M
```
```
XXX.models.model.ModelTemplates +9P -4P
```
```
XXX.data.tags.BlockTagsProvider -1M
```
```
XXX.data.tags.GameEventTagsProvider -1M
```
```
XXX.minecraft.resources.RegistryResourceAccess$InMemoryStorage +6M -4M
```
```
XXX.minecraft.resources.ResourceLocation +2M
```
```
XXX.minecraft.server.ReloadableServerResources +5M -4M | +1P
```
```
XXX.server.commands.CloneCommands +1M -1M
```
```
XXX.server.commands.FillCommand +1M -1M
```
```
XXX.server.commands.LootCommand +2M -2M
```
```
XXX.server.commands.SetBlockCommand +1M -1M
```
```
XXX.server.dedicated.DedicatedServer +1M
```
```
XXX.server.dedicated.DedicatedServerProperties +1M | +2P
```
```
XXX.server.level.DemoMode +1M -1M
```
```
XXX.server.level.ThreadedLevelLightEngine +10M -6M
```
```
XXX.server.network.ServerGamePacketListenerImpl +1M | +3P
```
```
XXX.server.packs.FolderPackResources +2M -2M
```
```
XXX.server.packs.VanillaPackResources +3M -3M
```
```
XXX.packs.resources.ResourceManager$Empty +3M -2M
```
```
XXX.packs.resources.SimpleResource -2M | -1P
```
```
XXX.minecraft.sounds.SoundEvents +76P
```
```
XXX.minecraft.tags.BiomeTags +20P
```
```
XXX.minecraft.tags.ItemTags +1P
```
```
XXX.minecraft.util.CubicSpline -2P
```
```
XXX.minecraft.util.CubicSpline$Builder +2M -1M
```
```
XXX.minecraft.util.CubicSpline$CoordinateVisitor +1P -1P
```
```
XXX.minecraft.util.ExtraCodecs +1M | +1P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.minecraft.util.ParticleUtils +5M -2M
```
```
XXX.minecraft.util.ToFloatFunction +4M | +3P
```
```
XXX.metrics.profiling.ActiveMetricsRecorder +2M
```
```
XXX.metrics.profiling.MetricsRecorder +1P
```
```
XXX.monster.hoglin.Hoglin +1M -1M
```
```
XXX.monster.piglin.Piglin +1M -1M
```
```
XXX.entity.player.Player +1M -1M
```
```
XXX.entity.schedule.Activity +3P
```
```
XXX.world.inventory.BeaconMenu +1M -1M
```
```
XXX.world.item.Items +36P
```
```
XXX.level.block.MultifaceBlock +6M -14M | +1P
```
```
XXX.level.chunk.ImposterProtoChunk +4M -4M
```
```
XXX.level.dimension.LevelStem +4M -1M
```
```
XXX.level.gameevent.EuclideanGameEventDispatcher +3P
```
```
XXX.level.levelgen.Beardifier +2M -3M
```
```
XXX.level.levelgen.DebugLevelSource +7M -9M
```
```
XXX.level.levelgen.DensityFunctions +1M -1M
```
```
XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction +1M | +1P
```
```
XXX.level.levelgen.DensityFunctions$Spline +2M -3M | +1P -2P
```
```
XXX.levelgen.carver.CarvingContext +2M -1M | +2P -1P
```
```
XXX.structure.pools.FeaturePoolElement +4M -4M
```
```
XXX.structure.pools.JigsawPlacement +3M -3M
```
```
XXX.structure.pools.SinglePoolElement +6M -6M
```

</details>








<details>
<summary>
com.mojang.blaze3d.font.GlyphInfo
</summary>

```diff
+ float getBearingX()
+ float getBearingY()
```

</details>
<details>
<summary>
com.mojang.blaze3d.font.TrueTypeGlyphProvider$Glyph
</summary>

```diff
- BakedGlyph bake(Function)
+ boolean isColored()
+ float getBearingX()
+ float getBearingY()
+ float getOversample()
+ int getPixelHeight()
+ int getPixelWidth()
+ void upload(int,int)
```

</details>





















<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
- boolean lambda$updateTeaserImages$14(ResourceLocation)
+ boolean lambda$updateTeaserImages$14(String)
```

</details>


































































































<details>
<summary>
net.minecraft.Util$5
</summary>

```diff
- void <init>(Path,Path)
+ void <init>(Path)
```

</details>

<details>
<summary>
net.minecraft.Util$9
</summary>

```diff
+ Object apply(Object)
+ String toString()
+ void <init>(Function)
- void <init>(String)
- void run()
```

</details>


















































<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate$Builder
</summary>

```diff
+ LocationPredicate$Builder setFeature(ResourceKey)
- LocationPredicate$Builder setStructure(ResourceKey)
```

</details>


































<details>
<summary>
net.minecraft.client.CycleOption
</summary>

```diff
- CycleButton$Builder lambda$create$0(Function,List)
- CycleButton$Builder lambda$create$1(Function,Supplier)
- CycleButton$Builder lambda$create$2(Function,BooleanSupplier,List,List)
+ CycleButton$Builder lambda$create$2(Function,List)
- CycleButton$Builder lambda$create$3(Function,Object[])
+ CycleButton$Builder lambda$create$3(Function,Supplier)
+ CycleButton$Builder lambda$create$4(Function,BooleanSupplier,List,List)
+ CycleButton$Builder lambda$create$5(Function,Object[])
- CycleButton$Builder lambda$createBinaryOption$4(Component,Component)
+ CycleButton$Builder lambda$createBinaryOption$6(Component,Component)
+ CycleButton$TooltipSupplier lambda$createOnOff$8(Component,Minecraft)
+ CycleButton$TooltipSupplier lambda$new$1(Minecraft)
- List lambda$createOnOff$5(List,Boolean)
+ List lambda$createOnOff$7(List,Boolean)
+ List lambda$new$0(Object)
- Option$TooltipSupplier lambda$createOnOff$6(Component,Minecraft)
- void lambda$createButton$7(Options,CycleButton,Object)
+ void lambda$createButton$9(Options,CycleButton,Object)
```

</details>

<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ boolean lambda$tick$30()
- boolean lambda$tick$31()
+ ChunkProgressListener lambda$doLoadLevel$37(int)
- ChunkProgressListener lambda$doWorldLoad$32(int)
- CompletionStage lambda$delayTextureReload$43(CompletableFuture)
+ CompletionStage lambda$delayTextureReload$49(CompletableFuture)
+ DataResult lambda$createLevel$32(DynamicOps,JsonElement)
- double getGpuUtilization()
+ IntegratedServer lambda$doLoadLevel$38(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,MinecraftSessionService,GameProfileRepository,GameProfileCache,Thread)
- IntegratedServer lambda$doWorldLoad$33(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,MinecraftSessionService,GameProfileRepository,GameProfileCache,Thread)
+ PackRepository createPackRepository(LevelStorageSource$LevelStorageAccess)
- PackResources lambda$adaptV3$47(Supplier)
+ PackResources lambda$adaptV3$53(Supplier)
- PackResources lambda$adaptV4$48(Supplier)
+ PackResources lambda$adaptV4$54(Supplier)
+ Pair lambda$createLevel$33(RegistryAccess,WorldGenSettings,LevelSettings,ResourceManager,DataPackConfig)
- String lambda$doWorldLoad$34(WorldStem)
- String lambda$fillSystemReport$36(String)
- String lambda$fillSystemReport$37(Minecraft)
- String lambda$fillSystemReport$38()
- String lambda$fillSystemReport$39()
- String lambda$fillSystemReport$40()
- String lambda$fillSystemReport$41(Options)
- String lambda$fillSystemReport$42(LanguageManager)
+ String lambda$fillSystemReport$42(String)
+ String lambda$fillSystemReport$43(Minecraft)
+ String lambda$fillSystemReport$44()
+ String lambda$fillSystemReport$45()
+ String lambda$fillSystemReport$46()
+ String lambda$fillSystemReport$47(Options)
+ String lambda$fillSystemReport$48(LanguageManager)
+ Style lambda$debugClientMetricsStart$21(Path,Style)
- Style lambda$debugClientMetricsStart$22(Path,Style)
- Style lambda$grabHugeScreenshot$46(File,Style)
+ Style lambda$grabHugeScreenshot$52(File,Style)
- Style lambda$grabPanoramixScreenshot$45(File,Style)
+ Style lambda$grabPanoramixScreenshot$51(File,Style)
+ void createLevel(String,LevelSettings,RegistryAccess,WorldGenSettings)
- void debugClientMetricsCancel()
+ void displayExperimentalConfirmationDialog(Minecraft$ExperimentalDialogType,String,boolean,Runnable)
+ void doLoadLevel(String,Function,Function,boolean,Minecraft$ExperimentalDialogType)
- void doWorldLoad(String,LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem)
+ void lambda$debugClientMetricsStart$19(Consumer,double,int)
- void lambda$debugClientMetricsStart$20(Consumer,double,int)
+ void lambda$debugClientMetricsStart$20(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$21(Consumer,ProfileResults)
+ void lambda$debugClientMetricsStart$22(Consumer,Component)
- void lambda$debugClientMetricsStart$23(Consumer,Component)
+ void lambda$debugClientMetricsStart$23(Consumer,Path)
- void lambda$debugClientMetricsStart$24(Consumer,Path)
+ void lambda$debugClientMetricsStart$24(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$25(Consumer,Path)
- void lambda$debugClientMetricsStart$25(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$26(Consumer,CompletableFuture,CompletableFuture)
- void lambda$debugClientMetricsStart$26(Consumer,Path)
- void lambda$debugClientMetricsStart$27(Consumer,CompletableFuture,CompletableFuture)
+ void lambda$debugClientMetricsStart$27(ProfileResults)
+ void lambda$debugClientMetricsStart$28(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$28(ProfileResults)
- void lambda$debugClientMetricsStart$29(Consumer,ProfileResults)
+ void lambda$displayExperimentalConfirmationDialog$40(String,Runnable,boolean,boolean)
+ void lambda$displayExperimentalConfirmationDialog$41(Runnable,String,boolean)
+ void lambda$doLoadLevel$35(String,Function,Function,Minecraft$ExperimentalDialogType)
+ void lambda$doLoadLevel$36(String,Function,Function,boolean)
+ void lambda$doLoadLevel$39(Component)
- void lambda$doWorldLoad$35(Component)
- void lambda$grabPanoramixScreenshot$44(Component)
+ void lambda$grabPanoramixScreenshot$50(Component)
- void lambda$runTick$19(TimerQuery)
+ void lambda$tick$29()
- void lambda$tick$30()
+ void loadLevel(String)
- WorldOpenFlows createWorldOpenFlows()
+ WorldStem makeWorldStem(LevelStorageSource$LevelStorageAccess,boolean)
+ WorldStem makeWorldStem(PackRepository,boolean,WorldStem$DataPackConfigSupplier,WorldStem$WorldDataSupplier)
+ WorldStem$DataPackConfigSupplier lambda$createLevel$31(LevelSettings,LevelStorageSource$LevelStorageAccess)
+ WorldStem$WorldDataSupplier lambda$createLevel$34(RegistryAccess,WorldGenSettings,LevelSettings,LevelStorageSource$LevelStorageAccess)
```

</details>



<details>
<summary>
net.minecraft.client.Options
</summary>

```diff
+ boolean lambda$new$1()
+ boolean lambda$new$2()
- boolean lambda$new$20()
- boolean lambda$new$21()
- Component genericValueLabel(Component,Component)
- Component genericValueLabel(Component,int)
- Component lambda$new$10(Double)
- Component lambda$new$12(Double)
- Component lambda$new$15(Integer)
- Component lambda$new$17(Double)
- Component lambda$new$22(Integer)
- Component lambda$new$4(AmbientOcclusionStatus)
- Component lambda$new$8(PrioritizeChunkUpdates)
- Component percentValueLabel(Component,double)
- Component pixelValueLabel(Component,int)
- double logMouse(int)
- Float lambda$processOptions$25(Options$FieldAccess,SoundSource,Float)
+ Float lambda$processOptions$4(Options$FieldAccess,SoundSource,Float)
- int unlogMouse(double)
- List lambda$new$0(List,Boolean)
- List lambda$new$2(List,Boolean)
- List lambda$new$6(Minecraft,PrioritizeChunkUpdates)
- Option$TooltipSupplier lambda$new$1(Minecraft)
- Option$TooltipSupplier lambda$new$3(Minecraft)
- Option$TooltipSupplier lambda$new$7(Minecraft)
- OptionInstance ambientOcclusion()
- OptionInstance biomeBlendRadius()
- OptionInstance chatHeightFocused()
- OptionInstance chatHeightUnfocused()
- OptionInstance darkMojangStudiosBackground()
- OptionInstance fov()
- OptionInstance hideLightningFlash()
- OptionInstance mouseWheelSensitivity()
- OptionInstance prioritizeChunkUpdates()
- OptionInstance rawMouseInput()
- String lambda$dumpOptionsForReport$27(Pair)
+ String lambda$dumpOptionsForReport$6(Pair)
- String lambda$processOptions$24(AmbientOcclusionStatus)
+ String lambda$processOptions$3(AmbientOcclusionStatus)
- void lambda$load$26(CompoundTag,String)
+ void lambda$load$5(CompoundTag,String)
+ void lambda$new$0(Object2FloatOpenHashMap)
- void lambda$new$11(Double)
- void lambda$new$13(Double)
- void lambda$new$14(Object2FloatOpenHashMap)
- void lambda$new$16(Integer)
- void lambda$new$18(Double)
- void lambda$new$19(Boolean)
- void lambda$new$23(Integer)
- void lambda$new$5(AmbientOcclusionStatus)
- void lambda$new$9(PrioritizeChunkUpdates)
```

</details>






























<details>
<summary>
net.minecraft.client.gui.components.BossHealthOverlay
</summary>

```diff
- void drawBar(PoseStack,int,int,BossEvent,int,int)
```

</details>





<details>
<summary>
net.minecraft.client.gui.components.CycleButton
</summary>

```diff
+ void <init>(int,int,int,int,Component,Component,int,Object,CycleButton$ValueListSupplier,Function,Function,CycleButton$OnValueChange,CycleButton$TooltipSupplier,boolean)
- void <init>(int,int,int,int,Component,Component,int,Object,CycleButton$ValueListSupplier,Function,Function,CycleButton$OnValueChange,Option$TooltipSupplier,boolean)
```

</details>










<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOptionsScreen
</summary>

```diff
- Option[] options(Options)
+ void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.ChatOptionsScreen
</summary>

```diff
+ void <clinit>()
```

</details>














<details>
<summary>
net.minecraft.client.gui.screens.MouseSettingsScreen
</summary>

```diff
- Option[] options(Options)
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.OptionsScreen
</summary>

```diff
+ void <clinit>()
```

</details>











<details>
<summary>
net.minecraft.client.model.HierarchicalModel
</summary>

```diff
- boolean lambda$getAnyDescendantWithName$0(String,ModelPart)
- ModelPart lambda$getAnyDescendantWithName$1(String,ModelPart)
- Optional getAnyDescendantWithName(String)
```

</details>
































































































































































































































<details>
<summary>
net.minecraft.client.resources.AssetIndex
</summary>

```diff
+ Collection getFiles(String,String,int,Predicate)
- Collection getFiles(String,String,Predicate)
```

</details>

<details>
<summary>
net.minecraft.client.resources.DefaultClientPackResources
</summary>

```diff
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
```

</details>
<details>
<summary>
net.minecraft.client.resources.DirectAssetIndex
</summary>

```diff
+ boolean lambda$getFiles$2(Predicate,Path)
+ Collection getFiles(String,String,int,Predicate)
- Collection getFiles(String,String,Predicate)
- ResourceLocation lambda$getFiles$2(String,Path,Path)
+ ResourceLocation lambda$getFiles$3(String,Path,Path)
```

</details>


<details>
<summary>
net.minecraft.client.resources.PackResourcesAdapterV4
</summary>

```diff
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
```

</details>










































































<details>
<summary>
net.minecraft.commands.arguments.ResourceOrTagLocationArgument
</summary>

```diff
- ResourceOrTagLocationArgument$Result getStructure(CommandContext,String)
+ ResourceOrTagLocationArgument$Result getStructureFeature(CommandContext,String)
```

</details>





<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockPredicateArgument$TagPredicate
</summary>

```diff
- boolean requiresNbt()
- void <init>(HolderSet,Map,CompoundTag)
+ void <init>(TagKey,Map,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.blocks.BlockStateParser
</summary>

```diff
+ BlockState getState()
+ BlockStateParser parse(boolean)
- BlockStateParser$BlockResult parseForBlock(HolderLookup,StringReader,boolean)
- BlockStateParser$BlockResult parseForBlock(Registry,String,boolean)
- BlockStateParser$BlockResult parseForBlock(Registry,StringReader,boolean)
- boolean hasBlockEntity()
+ boolean hasBlockEntity(Registry)
- CommandSyntaxException lambda$readTag$7(int,ResourceLocation)
- CompletableFuture fillSuggestions(HolderLookup,SuggestionsBuilder,boolean,boolean)
+ CompletableFuture fillSuggestions(SuggestionsBuilder,Registry)
+ CompletableFuture lambda$readProperties$7(Property,SuggestionsBuilder,Registry)
- CompletableFuture lambda$readProperties$8(Property,SuggestionsBuilder)
+ CompletableFuture lambda$readVagueProperties$8(String,SuggestionsBuilder,Registry)
- CompletableFuture lambda$readVagueProperties$9(String,SuggestionsBuilder)
+ CompletableFuture lambda$static$5(SuggestionsBuilder,Registry)
+ CompletableFuture suggestBlockIdOrTag(SuggestionsBuilder,Registry)
- CompletableFuture suggestBlockIdOrTag(SuggestionsBuilder)
+ CompletableFuture suggestEquals(SuggestionsBuilder,Registry)
- CompletableFuture suggestEquals(SuggestionsBuilder)
- CompletableFuture suggestItem(SuggestionsBuilder)
+ CompletableFuture suggestNextPropertyOrEnd(SuggestionsBuilder,Registry)
- CompletableFuture suggestNextPropertyOrEnd(SuggestionsBuilder)
+ CompletableFuture suggestOpenNbt(SuggestionsBuilder,Registry)
- CompletableFuture suggestOpenNbt(SuggestionsBuilder)
+ CompletableFuture suggestOpenPropertiesOrNbt(SuggestionsBuilder,Registry)
- CompletableFuture suggestOpenPropertiesOrNbt(SuggestionsBuilder)
+ CompletableFuture suggestOpenVaguePropertiesOrNbt(SuggestionsBuilder,Registry)
- CompletableFuture suggestOpenVaguePropertiesOrNbt(SuggestionsBuilder)
+ CompletableFuture suggestPropertyName(SuggestionsBuilder,Registry)
- CompletableFuture suggestPropertyName(SuggestionsBuilder)
+ CompletableFuture suggestPropertyNameOrEnd(SuggestionsBuilder,Registry)
- CompletableFuture suggestPropertyNameOrEnd(SuggestionsBuilder)
+ CompletableFuture suggestTag(SuggestionsBuilder,Registry)
- CompletableFuture suggestTag(SuggestionsBuilder)
+ CompletableFuture suggestVaguePropertyName(SuggestionsBuilder,Registry)
- CompletableFuture suggestVaguePropertyName(SuggestionsBuilder)
+ CompletableFuture suggestVaguePropertyNameOrEnd(SuggestionsBuilder,Registry)
- CompletableFuture suggestVaguePropertyNameOrEnd(SuggestionsBuilder)
+ CompletableFuture suggestVaguePropertyValue(SuggestionsBuilder,Registry,String)
- CompletableFuture suggestVaguePropertyValue(SuggestionsBuilder,String)
+ CompoundTag getNbt()
- Either parseForTesting(HolderLookup,StringReader,boolean)
- Either parseForTesting(Registry,String,boolean)
- Either parseForTesting(Registry,StringReader,boolean)
+ Map getProperties()
+ Map getVagueProperties()
- Message lambda$static$5(Object)
- String lambda$serialize$10(ResourceKey)
+ TagKey getTag()
- void <init>(HolderLookup,StringReader,boolean,boolean)
+ void <init>(StringReader,boolean)
- void parse()
```

</details>








<details>
<summary>
net.minecraft.commands.arguments.item.ItemInput
</summary>

```diff
- Object lambda$getItemName$1()
- String getItemName()
- void <init>(Holder,CompoundTag)
+ void <init>(Item,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemPredicateArgument
</summary>

```diff
- boolean lambda$createResult$3(Predicate,CompoundTag,ItemStack)
- boolean lambda$createResult$4(Predicate,ItemStack)
- boolean lambda$parse$0(ItemParser$ItemResult,Holder)
+ ItemPredicateArgument itemPredicate()
- ItemPredicateArgument itemPredicate(CommandBuildContext)
- ItemPredicateArgument$Result createResult(Predicate,CompoundTag)
- ItemPredicateArgument$Result lambda$parse$1(ItemParser$ItemResult)
- ItemPredicateArgument$Result lambda$parse$2(ItemParser$TagResult)
+ Message lambda$static$0(Object)
+ Predicate lambda$parse$1(ItemPredicateArgument$ItemPredicate,CommandContext)
+ Predicate lambda$parse$2(TagKey,ItemParser,CommandContext)
+ void <init>()
- void <init>(CommandBuildContext)
```

</details>
















<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- Collection allShuffled(Random)
- Stream stream()
```

</details>



<details>
<summary>
net.minecraft.core.Direction8
</summary>

```diff
- int getStepX()
- int getStepZ()
```

</details>






<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- Set registryKeySet()
```

</details>

































































<details>
<summary>
net.minecraft.data.tags.BlockTagsProvider
</summary>

```diff
+ String getName()
```

</details>
<details>
<summary>
net.minecraft.data.tags.GameEventTagsProvider
</summary>

```diff
+ String getName()
```

</details>






<details>
<summary>
net.minecraft.resources.RegistryResourceAccess$InMemoryStorage
</summary>

```diff
- boolean lambda$listResources$0(ResourceKey,Map$Entry)
+ Collection listResources(ResourceKey)
- DataResult lambda$getResource$3(DataResult,DynamicOps,Decoder)
- Map listResources(ResourceKey)
- Optional getResource(ResourceKey)
+ Optional parseElement(DynamicOps,ResourceKey,ResourceKey,Decoder)
- RegistryResourceAccess$EntryThunk lambda$listResources$2(Map$Entry)
+ RegistryResourceAccess$ParsedEntry lambda$parseElement$1(RegistryResourceAccess$InMemoryStorage$Entry,Object)
- ResourceKey lambda$listResources$1(Map$Entry)
+ Stream lambda$listResources$0(ResourceKey,ResourceKey)
```

</details>

<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
- String toLanguageKey()
- String toLanguageKey(String)
```

</details>









<details>
<summary>
net.minecraft.server.ReloadableServerResources
</summary>

```diff
+ List lambda$updateRegistryTags$3(Map$Entry)
- List lambda$updateRegistryTags$4(Map$Entry)
+ ReloadableServerResources lambda$loadResources$0(ReloadableServerResources,Object)
- ReloadableServerResources lambda$loadResources$1(ReloadableServerResources,Object)
+ TagKey lambda$updateRegistryTags$2(ResourceKey,Map$Entry)
- TagKey lambda$updateRegistryTags$3(ResourceKey,Map$Entry)
- void lambda$loadResources$0(ReloadableServerResources,Object,Throwable)
+ void lambda$updateRegistryTags$1(RegistryAccess,TagManager$LoadResult)
- void lambda$updateRegistryTags$2(RegistryAccess,TagManager$LoadResult)
```

</details>















<details>
<summary>
net.minecraft.server.commands.CloneCommands
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>









<details>
<summary>
net.minecraft.server.commands.FillCommand
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>







<details>
<summary>
net.minecraft.server.commands.LootCommand
</summary>

```diff
+ ArgumentBuilder lambda$register$14(ArgumentBuilder,LootCommand$DropConsumer)
- ArgumentBuilder lambda$register$14(CommandBuildContext,ArgumentBuilder,LootCommand$DropConsumer)
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>











<details>
<summary>
net.minecraft.server.commands.SetBlockCommand
</summary>

```diff
- void register(CommandDispatcher,CommandBuildContext)
+ void register(CommandDispatcher)
```

</details>


















<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- int getMaxChainedNeighborUpdates()
```

</details>
<details>
<summary>
net.minecraft.server.dedicated.DedicatedServerProperties
</summary>

```diff
- void <clinit>()
```

</details>
















<details>
<summary>
net.minecraft.server.level.DemoMode
</summary>

```diff
- void handleBlockBreakAction(BlockPos,ServerboundPlayerActionPacket$Action,Direction,int,int)
+ void handleBlockBreakAction(BlockPos,ServerboundPlayerActionPacket$Action,Direction,int)
```

</details>









<details>
<summary>
net.minecraft.server.level.ThreadedLevelLightEngine
</summary>

```diff
+ ChunkAccess lambda$lightChunk$20(ChunkAccess,ChunkPos)
- ChunkAccess lambda$lightChunk$23(ChunkAccess,ChunkPos)
- ChunkAccess lambda$retainData$17(ChunkPos,ChunkAccess)
- CompletableFuture retainData(ChunkAccess)
+ String lambda$lightChunk$19(ChunkPos,boolean)
- String lambda$lightChunk$22(ChunkPos,boolean)
- String lambda$retainData$18(ChunkPos)
+ void lambda$lightChunk$17(ChunkAccess,BlockPos)
+ void lambda$lightChunk$18(ChunkAccess,ChunkPos,boolean)
- void lambda$lightChunk$20(ChunkAccess,BlockPos)
- void lambda$lightChunk$21(ChunkAccess,ChunkPos,boolean)
+ void lambda$lightChunk$21(ChunkPos,Runnable)
- void lambda$lightChunk$24(ChunkPos,Runnable)
- void lambda$retainData$19(ChunkPos,Runnable)
+ void lambda$tryScheduleUpdate$22()
- void lambda$tryScheduleUpdate$25()
```

</details>









<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void ackBlockChangesUpTo(int)
```

</details>










<details>
<summary>
net.minecraft.server.packs.FolderPackResources
</summary>

```diff
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
+ void listResources(File,int,String,List,String,Predicate)
- void listResources(File,String,List,String,Predicate)
```

</details>

<details>
<summary>
net.minecraft.server.packs.VanillaPackResources
</summary>

```diff
- boolean lambda$getResources$1(Path)
+ boolean lambda$getResources$1(Predicate,Path)
+ Collection getResources(PackType,String,String,int,Predicate)
- Collection getResources(PackType,String,String,Predicate)
+ void getResources(Collection,int,String,Path,String,Predicate)
- void getResources(Collection,String,Path,String,Predicate)
```

</details>









<details>
<summary>
net.minecraft.server.packs.resources.ResourceManager$Empty
</summary>

```diff
+ Collection listResources(String,Predicate)
+ List getResources(ResourceLocation)
- List getResourceStack(ResourceLocation)
- Map listResources(String,Predicate)
- Map listResourceStacks(String,Predicate)
```

</details>



<details>
<summary>
net.minecraft.server.packs.resources.SimpleResource
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
```

</details>



































<details>
<summary>
net.minecraft.util.CubicSpline$Builder
</summary>

```diff
- CubicSpline$Builder addPoint(float,CubicSpline)
- CubicSpline$Builder addPoint(float,float)
+ float lambda$new$0(Float)
```

</details>



<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
- DataResult lambda$static$27(String)
```

</details>












<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float catmullrom(float,float,float,float,float)
```

</details>

<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
- Vec3 getRandomSpeedRanges(Random)
- Vec3 lambda$spawnParticlesOnBlockFaces$0(Level)
- void spawnParticleOnFace(Level,BlockPos,Direction,ParticleOptions,Vec3,double)
+ void spawnParticleOnFace(Level,BlockPos,Direction,ParticleOptions)
- void spawnParticlesOnBlockFace(Level,BlockPos,ParticleOptions,IntProvider,Direction,Supplier,double)
- void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,IntProvider)
+ void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,UniformInt)
```

</details>






<details>
<summary>
net.minecraft.util.ToFloatFunction
</summary>

```diff
- float lambda$static$0(float)
- ToFloatFunction comap(Function)
- ToFloatFunction createUnlimited(Float2FloatFunction)
- void <clinit>()
```

</details>























































































































































<details>
<summary>
net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
</summary>

```diff
- void cancel()
- void cleanup(Collection)
```

</details>



































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>




















<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- int getExperienceReward()
+ int getExperienceReward(Player)
```

</details>











































<details>
<summary>
net.minecraft.world.inventory.BeaconMenu
</summary>

```diff
+ void updateEffects(int,int)
- void updateEffects(MobEffect,MobEffect)
```

</details>






































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.MultifaceBlock
</summary>

```diff
+ boolean canSpread(BlockState,BlockGetter,BlockPos,Direction)
+ boolean canSpreadInto(BlockState)
+ boolean canSpreadToFace(BlockGetter,BlockPos,Direction)
- boolean isValidStateForPlacement(BlockGetter,BlockState,BlockPos,Direction)
+ boolean lambda$canSpread$5(BlockState,BlockGetter,BlockPos,Direction,Direction)
- boolean lambda$hasAnyFace$2(BlockState,Direction)
+ boolean lambda$hasAnyFace$6(BlockState,Direction)
- boolean lambda$hasAnyVacantFace$3(BlockState,Direction)
+ boolean lambda$hasAnyVacantFace$7(BlockState,Direction)
+ boolean lambda$spreadFromFaceTowardRandomDirection$4(BlockState,LevelAccessor,BlockPos,Direction,boolean,Direction)
+ boolean lambda$spreadFromRandomFaceTowardRandomDirection$2(BlockState,Direction)
+ boolean lambda$spreadFromRandomFaceTowardRandomDirection$3(BlockState,ServerLevel,BlockPos,Random,Direction)
+ boolean spreadFromFaceTowardDirection(BlockState,LevelAccessor,BlockPos,Direction,Direction,boolean)
+ boolean spreadFromFaceTowardRandomDirection(BlockState,LevelAccessor,BlockPos,Direction,Random,boolean)
+ boolean spreadFromRandomFaceTowardRandomDirection(BlockState,ServerLevel,BlockPos,Random)
+ boolean spreadToFace(LevelAccessor,BlockPos,Direction,boolean)
- byte pack(Collection)
+ Optional getSpreadFromFaceTowardDirection(BlockState,BlockGetter,BlockPos,Direction,Direction)
- Set availableFaces(BlockState)
- Set unpack(byte)
```

</details>






















<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
+ LongSet getReferencesForFeature(ConfiguredStructureFeature)
- LongSet getReferencesForStructure(Structure)
+ StructureStart getStartForFeature(ConfiguredStructureFeature)
- StructureStart getStartForStructure(Structure)
+ void addReferenceForFeature(ConfiguredStructureFeature,long)
- void addReferenceForStructure(Structure,long)
+ void setStartForFeature(ConfiguredStructureFeature,StructureStart)
- void setStartForStructure(Structure,StructureStart)
```

</details>













<details>
<summary>
net.minecraft.world.level.dimension.LevelStem
</summary>

```diff
- boolean lambda$keysInOrder$1(ResourceKey)
+ boolean stable(long,Registry)
- boolean stable(Registry)
- Stream keysInOrder(Stream)
- void lambda$sortMap$2(Registry,WritableRegistry,ResourceKey)
```

</details>


























<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
+ boolean lambda$new$1(ConfiguredStructureFeature)
+ void <init>(StructureFeatureManager,ChunkAccess)
- void <init>(StructureManager,ChunkAccess)
- void lambda$new$1(ChunkPos,int,int,StructureStart)
+ void lambda$new$2(ChunkPos,int,int,StructureStart)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ ChunkGenerator withSeed(long)
+ Climate$Sampler climateSampler()
- CompletableFuture fillFromNoise(Executor,Blender,RandomState,StructureManager,ChunkAccess)
+ CompletableFuture fillFromNoise(Executor,Blender,StructureFeatureManager,ChunkAccess)
- int getBaseHeight(int,int,Heightmap$Types,LevelHeightAccessor,RandomState)
+ int getBaseHeight(int,int,Heightmap$Types,LevelHeightAccessor)
- NoiseColumn getBaseColumn(int,int,LevelHeightAccessor,RandomState)
+ NoiseColumn getBaseColumn(int,int,LevelHeightAccessor)
+ void addDebugScreenInfo(List,BlockPos)
- void addDebugScreenInfo(List,RandomState,BlockPos)
+ void applyBiomeDecoration(WorldGenLevel,ChunkAccess,StructureFeatureManager)
- void applyBiomeDecoration(WorldGenLevel,ChunkAccess,StructureManager)
+ void applyCarvers(WorldGenRegion,long,BiomeManager,StructureFeatureManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(WorldGenRegion,long,RandomState,BiomeManager,StructureManager,ChunkAccess,GenerationStep$Carving)
+ void buildSurface(WorldGenRegion,StructureFeatureManager,ChunkAccess)
- void buildSurface(WorldGenRegion,StructureManager,RandomState,ChunkAccess)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions
</summary>

```diff
- DensityFunction spline(CubicSpline)
+ DensityFunction terrainShaperSpline(DensityFunction,DensityFunction,DensityFunction,DensityFunctions$TerrainShaperSpline$SplineType,double,double)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
</summary>

```diff
- float getHeightValue(SimplexNoise,int,int)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.DensityFunctions$Spline
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- DensityFunctions$Spline$Coordinate lambda$mapAll$0(DensityFunction$Visitor,DensityFunctions$Spline$Coordinate)
+ ToFloatFunction lambda$mapAll$1(DensityFunction$Visitor,ToFloatFunction)
+ void <init>(CubicSpline,double,double)
- void <init>(CubicSpline)
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarvingContext
</summary>

```diff
- RandomState randomState()
- void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk,RandomState,SurfaceRules$RuleSource)
+ void <init>(NoiseBasedChunkGenerator,RegistryAccess,LevelHeightAccessor,NoiseChunk)
```

</details>
















































<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
</summary>

```diff
+ boolean place(StructureManager,WorldGenLevel,StructureFeatureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
- boolean place(StructureTemplateManager,WorldGenLevel,StructureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
+ BoundingBox getBoundingBox(StructureManager,BlockPos,Rotation)
- BoundingBox getBoundingBox(StructureTemplateManager,BlockPos,Rotation)
+ List getShuffledJigsawBlocks(StructureManager,BlockPos,Rotation,Random)
- List getShuffledJigsawBlocks(StructureTemplateManager,BlockPos,Rotation,Random)
+ Vec3i getSize(StructureManager,Rotation)
- Vec3i getSize(StructureTemplateManager,Rotation)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
</summary>

```diff
+ Optional addPieces(PieceGeneratorSupplier$Context,JigsawPlacement$PieceFactory,BlockPos,boolean,boolean)
- Optional addPieces(Structure$GenerationContext,Holder,int,JigsawPlacement$PieceFactory,BlockPos,boolean,Optional)
+ void addPieces(RegistryAccess,PoolElementStructurePiece,int,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,List,Random,LevelHeightAccessor)
- void addPieces(RegistryAccess,PoolElementStructurePiece,int,JigsawPlacement$PieceFactory,ChunkGenerator,StructureTemplateManager,List,Random,LevelHeightAccessor,RandomState)
- void lambda$addPieces$0(PoolElementStructurePiece,int,int,int,int,Registry,JigsawPlacement$PieceFactory,ChunkGenerator,StructureTemplateManager,WorldgenRandom,BoundingBox,boolean,LevelHeightAccessor,Structure$GenerationContext,StructurePiecesBuilder)
+ void lambda$addPieces$0(PoolElementStructurePiece,JigsawConfiguration,int,int,int,Registry,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,WorldgenRandom,BoundingBox,boolean,LevelHeightAccessor,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
</summary>

```diff
+ boolean place(StructureManager,WorldGenLevel,StructureFeatureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
- boolean place(StructureTemplateManager,WorldGenLevel,StructureManager,ChunkGenerator,BlockPos,BlockPos,Rotation,BoundingBox,Random,boolean)
+ BoundingBox getBoundingBox(StructureManager,BlockPos,Rotation)
- BoundingBox getBoundingBox(StructureTemplateManager,BlockPos,Rotation)
+ List getDataMarkers(StructureManager,BlockPos,Rotation,boolean)
- List getDataMarkers(StructureTemplateManager,BlockPos,Rotation,boolean)
+ List getShuffledJigsawBlocks(StructureManager,BlockPos,Rotation,Random)
- List getShuffledJigsawBlocks(StructureTemplateManager,BlockPos,Rotation,Random)
+ StructureTemplate getTemplate(StructureManager)
- StructureTemplate getTemplate(StructureTemplateManager)
+ Vec3i getSize(StructureManager,Rotation)
- Vec3i getSize(StructureTemplateManager,Rotation)
```

</details>
</details>