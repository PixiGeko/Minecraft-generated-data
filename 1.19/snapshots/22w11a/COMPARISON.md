## Comparison with [1.18.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18.2</th><th>22w11a</th></tr><tr><td>DataPack version</td><td><pre>9</pre></td><td><pre>10</pre></td></tr><tr><td>ResourcePack version</td><td><pre>8</pre></td><td><pre>9</pre></td></tr><tr><td>World version</td><td><pre>2975</pre></td><td><pre>3080</pre></td></tr><tr><td>Protocol version</td><td><pre>758</pre></td><td><pre>1073741898</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18.2</th><th>22w11a</th></tr><tr><td>ca.weblite:java-objc-bridge</td><td><pre>1.0.0</pre></td><td><pre>1.1</pre></td></tr><tr><td>com.mojang:text2speech</td><td><pre>1.12.4</pre></td><td><pre>1.13.9</pre></td></tr><tr><td>com.mojang:text2speech</td><td><pre>1.12.4</pre></td><td><pre>1.13.9</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ command_argument_type.txt
- worldgen/structure_feature.txt
+ worldgen/structure_type.txt
```

</details>
<details>
<summary>
activity
</summary>

```diff
+ minecraft:lay_spawn
+ minecraft:swim
+ minecraft:tongue
```

</details>
<details>
<summary>
block
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
block_entity_type
</summary>

```diff
+ minecraft:sculk_catalyst
+ minecraft:sculk_shrieker
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:frog
+ minecraft:tadpole
```

</details>
<details>
<summary>
game_event
</summary>

```diff
+ minecraft:entity_dying
```

</details>
<details>
<summary>
item
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
memory_module_type
</summary>

```diff
+ minecraft:is_in_water
+ minecraft:is_pregnant
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:sculk_charge
+ minecraft:sculk_charge_pop
+ minecraft:sculk_soul
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:frog_attackables
+ minecraft:frog_temptations
+ minecraft:is_in_water
```

</details>
<details>
<summary>
sound_event
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
worldgen/density_function_type
</summary>

```diff
- minecraft:terrain_shaper_spline
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
+ minecraft:sculk_patch
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ frogspawn.json
+ mangrove_button.json
+ mangrove_door.json
+ mangrove_fence_gate.json
+ mangrove_fence.json
+ mangrove_leaves.json
+ mangrove_log.json
+ mangrove_planks.json
+ mangrove_pressure_plate.json
+ mangrove_propagule.json
+ mangrove_roots.json
+ mangrove_sign.json
+ mangrove_slab.json
+ mangrove_stairs.json
+ mangrove_trapdoor.json
+ mangrove_wall_sign.json
+ mangrove_wood.json
+ mud_brick_slab.json
+ mud_brick_stairs.json
+ mud_brick_wall.json
+ mud_bricks.json
+ mud.json
+ muddy_mangrove_roots.json
+ ochre_froglight.json
+ packed_mud.json
+ pearlescent_froglight.json
+ potted_mangrove_propagule.json
+ sculk_catalyst.json
+ sculk_shrieker.json
+ sculk_vein.json
+ sculk.json
+ stripped_mangrove_log.json
+ stripped_mangrove_wood.json
+ verdant_froglight.json
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<br/>
<table>
<tr><th>Name</th><th>1.18.2</th><th>22w11a</th></tr>
<tr><th align="left"><div style="width:290px">narration.recipe</div></th><td>Reciple for %s</td><td>Recipe for %s</td></tr>
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
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- net.minecraft.Util$11
+ net.minecraft.Util$2
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AnimalPanic
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CountDownCooldownTicks
- XXX.ai.behavior.Croak
- XXX.ai.behavior.LongJumpToRandomPos
+ XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.RandomSwim
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunIf
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.RunSometimes
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
- XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue$1
- XXX.animal.frog.Tadpole
+ XXX.arguments.blocks.BlockPredicateArgument$2
- XXX.arguments.blocks.BlockStateParser$BlockResult
- XXX.arguments.item.ItemParser$TagResult
+ XXX.arguments.item.ItemPredicateArgument$ItemPredicate
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateArgument$TagPredicate
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
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
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.commands.arguments.EntityArgument$Info$Template
+ XXX.commands.arguments.EntitySummonArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.ItemEnchantmentArgument
- XXX.commands.arguments.MessageArgument
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.MobEffectArgument
- XXX.commands.arguments.NbtPathArgument
+ XXX.commands.arguments.NbtPathArgument$AllElementsNode
- XXX.commands.arguments.NbtPathArgument$CompoundChildNode
+ XXX.commands.arguments.NbtPathArgument$IndexedElementNode
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
+ XXX.commands.arguments.ResourceKeyArgument
- XXX.commands.arguments.ResourceKeyArgument$Info
- XXX.commands.arguments.ResourceOrTagLocationArgument$Info
+ XXX.commands.arguments.ResourceOrTagLocationArgument$Serializer
- XXX.commands.arguments.ResourceOrTagLocationArgument$TagResult
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.synchronization.ArgumentSerializer
- XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfos
+ XXX.commands.synchronization.ArgumentTypes$Entry
- XXX.commands.synchronization.SingletonArgumentInfo
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustColorTransitionOptions$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.DustParticleOptionsBase
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption
- XXX.core.particles.VibrationParticleOption$1
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.HusbandryAdvancements
- XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.package-info
+ XXX.data.advancements.StoryAdvancements
- XXX.data.advancements.TheEndAdvancements
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.tags.ConfiguredStructureTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.WorldPresetTagsProvider
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.package-info
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.StructureFeatures
- XXX.data.worldgen.Structures
+ XXX.data.worldgen.SurfaceRuleData
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.TerrainProvider
- XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.schemas.V3076
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSource$1FeatureData
- XXX.level.biome.BiomeSource$StepFeatureData
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
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSource$Preset
+ XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
- XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.TerrainShaper
+ XXX.level.biome.TerrainShaper$CoordinateCustom
+ XXX.level.biome.TerrainShaper$PointCustom
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
- XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
- XXX.level.block.MultifaceSpreader$SpreadType
- XXX.level.block.MultifaceSpreader$SpreadType$2
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
+ XXX.level.block.OreBlock
+ XXX.level.block.package-info
- XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SporeBlossomBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$TicksToSave
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.package-info
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TerrainShaperSpline$Spline
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$1NoiseWiringHelper
+ XXX.level.levelgen.NoiseRouterWithOnlyNoises
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSamplingSettings
+ XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.NoiseSlider
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomSource
- XXX.level.levelgen.RandomState
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
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.MaterialColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
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
+ XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NoiseEffect
+ XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.feature.WoodlandMansionFeature
- XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.presets.WorldPresets
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces$1
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationStub
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
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
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetPotionFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.minecraft.commands.CommandBuildContext$1
- XXX.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
- XXX.minecraft.core.HolderLookup$RegistryLookup
+ XXX.minecraft.core.package-info
- XXX.minecraft.data.BlockFamilies
+ XXX.minecraft.data.BlockFamily
- XXX.minecraft.data.BlockFamily$Builder
+ XXX.minecraft.data.BlockFamily$Variant
- XXX.minecraft.data.BuiltinRegistries
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.Main
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryLoader
- XXX.minecraft.resources.RegistryLoader$Bound
+ XXX.minecraft.resources.RegistryLoader$ReadCache
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryResourceAccess
- XXX.minecraft.resources.RegistryResourceAccess$1
- XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
+ XXX.minecraft.server.WorldStem$InitConfig
+ XXX.minecraft.tags.ConfiguredStructureTags
- XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$OptionalElementEntry
- XXX.minecraft.tags.Tag$OptionalTagEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
- XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.world.package-info
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.KeybindComponent
- XXX.network.chat.MutableComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
+ XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.packs.resources.FallbackResourceManager$EntryStack
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
- XXX.packs.resources.ResourceFilterSection$ResourceLocationPattern
- XXX.packs.resources.ResourceThunk$ResourceSupplier
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddMobPacket
- XXX.protocol.game.ClientboundAddPaintingPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
- XXX.protocol.game.ClientboundAddVibrationSignalPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockBreakAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChatPacket
- XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
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
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPingPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerCombatEndPacket
+ XXX.protocol.game.ClientboundPlayerCombatEnterPacket
- XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$2
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$3
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$4
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$5
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundPongPacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
- XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
- XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
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
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.synchronization.brigadier.BrigadierArgumentSerializers
- XXX.synchronization.brigadier.DoubleArgumentInfo
- XXX.synchronization.brigadier.FloatArgumentInfo
+ XXX.synchronization.brigadier.FloatArgumentSerializer
- XXX.synchronization.brigadier.IntegerArgumentInfo
- XXX.synchronization.brigadier.LongArgumentInfo
+ XXX.synchronization.brigadier.LongArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer
+ XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.synchronization.brigadier.StringArgumentSerializer$Template
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MobType
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.Saddleable
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.level.package-info
+ XXX.world.level.StructureFeatureManager
- XXX.world.level.StructureManager
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
+ XXX.worldgen.biome.Biomes
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.features.AquaticFeatures
+ XXX.worldgen.features.CaveFeatures
- XXX.worldgen.features.EndFeatures
+ XXX.worldgen.features.FeatureUtils
- XXX.worldgen.features.MiscOverworldFeatures
+ XXX.worldgen.features.NetherFeatures
- XXX.worldgen.features.OreFeatures
- XXX.worldgen.features.package-info
+ XXX.worldgen.features.PileFeatures
- XXX.worldgen.features.TreeFeatures
+ XXX.worldgen.features.VegetationFeatures
- XXX.worldgen.placement.AquaticPlacements
+ XXX.worldgen.placement.CavePlacements
- XXX.worldgen.placement.EndPlacements
+ XXX.worldgen.placement.MiscOverworldPlacements
- XXX.worldgen.placement.NetherPlacements
+ XXX.worldgen.placement.OrePlacements
- XXX.worldgen.placement.package-info
- XXX.worldgen.placement.PlacementUtils
+ XXX.worldgen.placement.TreePlacements
- XXX.worldgen.placement.VegetationPlacements
+ XXX.worldgen.placement.VillagePlacements
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
- net.minecraft.Util$11
+ net.minecraft.Util$2
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AnimalPanic
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CountDownCooldownTicks
- XXX.ai.behavior.Croak
- XXX.ai.behavior.LongJumpToRandomPos
+ XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.RandomSwim
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunIf
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.RunSometimes
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
- XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
- XXX.animal.frog.ShootTongue$1
- XXX.animal.frog.Tadpole
- XXX.animation.definitions.package-info
+ XXX.arguments.blocks.BlockPredicateArgument$1
- XXX.arguments.blocks.BlockStateParser$TagResult
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.blaze3d.font.package-info
+ XXX.blaze3d.font.RawGlyph
- XXX.blaze3d.font.SheetGlyphInfo
- XXX.blaze3d.font.SpaceProvider$SpaceGlyphInfo
- XXX.blaze3d.pipeline.MainTarget
+ XXX.blaze3d.pipeline.MainTarget$AttachmentState
- XXX.blaze3d.pipeline.MainTarget$Dimension
+ XXX.blaze3d.pipeline.package-info
+ XXX.blaze3d.pipeline.RenderCall
- XXX.blaze3d.pipeline.RenderPipeline
+ XXX.blaze3d.pipeline.RenderTarget
- XXX.blaze3d.pipeline.TextureTarget
- XXX.blaze3d.platform.ClipboardManager
+ XXX.blaze3d.platform.DebugMemoryUntracker
- XXX.blaze3d.platform.DisplayData
- XXX.blaze3d.platform.GlConst
+ XXX.blaze3d.platform.GlDebug
- XXX.blaze3d.platform.GlDebug$LogEntry
+ XXX.blaze3d.platform.GlStateManager
- XXX.blaze3d.platform.GlStateManager$BlendState
+ XXX.blaze3d.platform.GlStateManager$BooleanState
- XXX.blaze3d.platform.GlStateManager$ColorLogicState
+ XXX.blaze3d.platform.GlStateManager$ColorMask
- XXX.blaze3d.platform.GlStateManager$CullState
+ XXX.blaze3d.platform.GlStateManager$DepthState
- XXX.blaze3d.platform.GlStateManager$DestFactor
+ XXX.blaze3d.platform.GlStateManager$LogicOp
- XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.platform.GlStateManager$ScissorState
- XXX.blaze3d.platform.GlStateManager$SourceFactor
+ XXX.blaze3d.platform.GlStateManager$StencilFunc
- XXX.blaze3d.platform.GlStateManager$StencilState
+ XXX.blaze3d.platform.GlStateManager$TextureState
- XXX.blaze3d.platform.GlStateManager$Viewport
+ XXX.blaze3d.platform.GlUtil
+ XXX.blaze3d.platform.GLX
- XXX.blaze3d.platform.InputConstants
+ XXX.blaze3d.platform.InputConstants$Key
- XXX.blaze3d.platform.InputConstants$Type
+ XXX.blaze3d.platform.Lighting
- XXX.blaze3d.platform.MacosUtil
+ XXX.blaze3d.platform.MemoryTracker
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.platform.PngInfo
+ XXX.blaze3d.platform.PngInfo$StbReader
- XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ XXX.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.Window$WindowInitFailed
+ XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.preprocessor.GlslPreprocessor
- XXX.blaze3d.preprocessor.GlslPreprocessor$Context
+ XXX.blaze3d.preprocessor.package-info
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.BlendMode
- XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.EffectProgram
- XXX.blaze3d.shaders.EffectProgram$1
+ XXX.blaze3d.shaders.FogShape
+ XXX.blaze3d.shaders.package-info
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Shader
- XXX.blaze3d.shaders.Uniform
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.systems.RenderSystem$1
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
- XXX.blaze3d.systems.TimerQuery
- XXX.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
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
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.KeyframeAnimations
+ XXX.client.main.GameConfig
- XXX.client.main.GameConfig$FolderData
+ XXX.client.main.GameConfig$GameData
- XXX.client.main.GameConfig$ServerData
+ XXX.client.main.GameConfig$UserData
- XXX.client.main.Main
+ XXX.client.main.Main$1
- XXX.client.main.Main$2
+ XXX.client.main.Main$3
+ XXX.client.main.package-info
- XXX.client.main.SilentInitException
- XXX.client.model.AbstractZombieModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BlazeModel
- XXX.client.model.BoatModel
+ XXX.client.model.BookModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.package-info
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientLevel$ClientLevelData
- XXX.client.multiplayer.ClientLevel$EntityCallbacks
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
+ XXX.client.particle.DripParticle$DripstoneLavaFallProvider
- XXX.client.particle.DripParticle$DripstoneLavaHangProvider
+ XXX.client.particle.DripParticle$DripstoneWaterFallProvider
- XXX.client.particle.DripParticle$DripstoneWaterHangProvider
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DripParticle$HoneyFallProvider
+ XXX.client.particle.DripParticle$HoneyHangProvider
- XXX.client.particle.DripParticle$HoneyLandProvider
+ XXX.client.particle.DripParticle$LavaFallProvider
- XXX.client.particle.DripParticle$LavaHangProvider
+ XXX.client.particle.DripParticle$LavaLandProvider
- XXX.client.particle.DripParticle$NectarFallProvider
+ XXX.client.particle.DripParticle$ObsidianTearFallProvider
- XXX.client.particle.DripParticle$ObsidianTearHangProvider
+ XXX.client.particle.DripParticle$ObsidianTearLandProvider
- XXX.client.particle.DripParticle$SporeBlossomFallProvider
+ XXX.client.particle.DripParticle$WaterFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$NautilusProvider
- XXX.client.particle.EnchantmentTableParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
+ XXX.client.particle.FireworkParticles
- XXX.client.particle.FireworkParticles$1
+ XXX.client.particle.FireworkParticles$FlashProvider
- XXX.client.particle.FireworkParticles$OverlayParticle
+ XXX.client.particle.FireworkParticles$SparkParticle
- XXX.client.particle.FireworkParticles$SparkProvider
+ XXX.client.particle.FireworkParticles$Starter
- XXX.client.particle.FlameParticle
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.Particle
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$Provider
+ XXX.client.particle.PlayerCloudParticle$SneezeProvider
- XXX.client.particle.PortalParticle
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
- XXX.client.particle.SculkChargeParticle$Provider
- XXX.client.particle.SculkChargePopParticle$Provider
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
- XXX.commands.arguments.EntityArgument$Info
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceKeyArgument
- XXX.commands.arguments.ResourceKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceKeyArgument$Serializer
- XXX.commands.arguments.ResourceOrTagLocationArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagLocationArgument$TagResult
- XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypes
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.EmptyArgumentSerializer
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastIds
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
- XXX.core.dispenser.DispenseItemBehavior$27
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleGroup
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
- XXX.core.particles.VibrationParticleOption
+ XXX.core.particles.VibrationParticleOption$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$TagAppender
- XXX.data.worldgen.DimensionTypes
+ XXX.data.worldgen.NoiseData
- XXX.data.worldgen.package-info
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.SurfaceRuleData
+ XXX.data.worldgen.TaigaVillagePools
- XXX.data.worldgen.TerrainProvider
+ XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.schemas.V3076
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$1
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.glyphs.WhiteGlyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.package-info
+ XXX.gui.components.PlainTextButton
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
- XXX.gui.components.SliderButton
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TooltipAccessor
+ XXX.gui.components.VolumeSlider
- XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
+ XXX.gui.font.TextFieldHelper
+ XXX.gui.screens.package-info
+ XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$1
- XXX.gui.screens.TitleScreen$Warning32Bit
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.screens.WinScreen$CreditsReader
- XXX.gui.spectator.package-info
- XXX.gui.spectator.PlayerMenuItem
+ XXX.gui.spectator.RootSpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenu
+ XXX.gui.spectator.SpectatorMenu$1
- XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
- XXX.gui.spectator.SpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenuItem
- XXX.gui.spectator.SpectatorMenuListener
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
- XXX.inventory.tooltip.ClientTextTooltip
+ XXX.inventory.tooltip.ClientTooltipComponent
- XXX.inventory.tooltip.package-info
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSource$1FeatureData
- XXX.level.biome.BiomeSource$StepFeatureData
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
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSource$Preset
+ XXX.level.biome.MultiNoiseBiomeSource$PresetInstance
- XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.TerrainShaper
+ XXX.level.biome.TerrainShaper$CoordinateCustom
+ XXX.level.biome.TerrainShaper$PointCustom
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
- XXX.level.block.MangroveLeavesBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
- XXX.level.block.MultifaceSpreader$SpreadType
- XXX.level.block.MultifaceSpreader$SpreadType$2
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
+ XXX.level.block.OreBlock
+ XXX.level.block.package-info
- XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SporeBlossomBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$TicksToSave
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.package-info
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TerrainShaperSpline$Spline
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$1NoiseWiringHelper
+ XXX.level.levelgen.NoiseRouterWithOnlyNoises
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSamplingSettings
+ XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.NoiseSlider
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomSource
- XXX.level.levelgen.RandomState
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
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.MaterialColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelVersion
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
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
+ XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NoiseEffect
+ XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.feature.WoodlandMansionFeature
- XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.presets.WorldPresets
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces$1
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationStub
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
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
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetPotionFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.minecraft.client.Game
- XXX.minecraft.client.Game$Metrics
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.Option
- XXX.minecraft.client.Option$1
- XXX.minecraft.client.OptionInstance
- XXX.minecraft.client.OptionInstance$IntRange
- XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
- XXX.minecraft.client.OptionInstance$UnitDouble
+ XXX.minecraft.client.package-info
- XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$2
- XXX.minecraft.core.HolderLookup
- XXX.minecraft.core.package-info
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.BuiltinRegistries
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.CompoundTag$2
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.ListTag$2
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.SnbtPrinterTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor$EntryResult
+ XXX.minecraft.nbt.StreamTagVisitor$ValueResult
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagType$2
- XXX.minecraft.nbt.TagType$StaticSize
+ XXX.minecraft.nbt.TagType$VariableSize
- XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.nbt.TagVisitor
- XXX.minecraft.nbt.TextComponentTagVisitor
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryLoader
- XXX.minecraft.resources.RegistryLoader$Bound
+ XXX.minecraft.resources.RegistryLoader$ReadCache
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryResourceAccess
- XXX.minecraft.resources.RegistryResourceAccess$1
- XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
+ XXX.minecraft.server.WorldStem$InitConfig
+ XXX.minecraft.tags.ConfiguredStructureTags
- XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$OptionalElementEntry
- XXX.minecraft.tags.Tag$OptionalTagEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
- XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.world.package-info
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.package-info
- XXX.model.geom.EntityModelSet
+ XXX.model.geom.LayerDefinitions
- XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelLayers
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.ModelPart$Visitor
- XXX.model.geom.package-info
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
+ XXX.mojang.blaze3d.package-info
- XXX.multiplayer.prediction.BlockStatePredictionHandler
- XXX.multiplayer.prediction.PredictiveAction
- XXX.multiplayer.resolver.AddressCheck
+ XXX.multiplayer.resolver.AddressCheck$1
- XXX.multiplayer.resolver.package-info
- XXX.multiplayer.resolver.ResolvedServerAddress
+ XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddress
+ XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerNameResolver
+ XXX.multiplayer.resolver.ServerRedirectHandler
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.MutableComponent
- XXX.network.chat.NbtComponent
+ XXX.network.chat.NbtComponent$BlockNbtComponent
- XXX.network.chat.NbtComponent$EntityNbtComponent
+ XXX.network.chat.NbtComponent$StorageNbtComponent
- XXX.network.chat.package-info
- XXX.network.chat.ScoreComponent
+ XXX.network.chat.SelectorComponent
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.TextComponent
- XXX.network.chat.TranslatableComponent
+ XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
- XXX.packs.resources.FallbackResourceManager$EntryStack
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
- XXX.packs.resources.ResourceFilterSection$ResourceLocationPattern
- XXX.packs.resources.ResourceThunk$ResourceSupplier
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddMobPacket
+ XXX.protocol.game.ClientboundAddPaintingPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAddVibrationSignalPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockChangedAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$AddOperation
- XXX.protocol.game.ClientboundBossEventPacket$Handler
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundBossEventPacket$OperationType
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
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
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPingPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$2
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$3
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action$4
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action$5
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetActionBarTextPacket
+ XXX.protocol.game.ClientboundSetBorderCenterPacket
- XXX.protocol.game.ClientboundSetBorderLerpSizePacket
+ XXX.protocol.game.ClientboundSetBorderSizePacket
- XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
+ XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetSimulationDistancePacket
+ XXX.protocol.game.ClientboundSetSubtitleTextPacket
- XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesAnimationPacket
+ XXX.protocol.game.ClientboundSetTitleTextPacket
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
- XXX.providers.nbt.ContextNbtProvider$Serializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.BinomialDistributionGenerator
- XXX.providers.number.BinomialDistributionGenerator$Serializer
+ XXX.providers.number.ConstantValue
- XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator
- XXX.providers.number.UniformGenerator$Serializer
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
- XXX.providers.score.ContextScoreboardNameProvider$Serializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
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
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.KeyBindsList
+ XXX.screens.controls.KeyBindsList$CategoryEntry
- XXX.screens.controls.KeyBindsList$CategoryEntry$1
+ XXX.screens.controls.KeyBindsList$Entry
- XXX.screens.controls.KeyBindsList$KeyEntry
+ XXX.screens.controls.KeyBindsList$KeyEntry$1
- XXX.screens.controls.KeyBindsList$KeyEntry$2
+ XXX.screens.controls.KeyBindsScreen
- XXX.screens.controls.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
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
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
+ XXX.screens.inventory.LecternScreen
- XXX.screens.inventory.LecternScreen$1
+ XXX.screens.inventory.LoomScreen
- XXX.screens.inventory.MenuAccess
+ XXX.screens.inventory.MerchantScreen
- XXX.screens.inventory.MerchantScreen$TradeOfferButton
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.package-info
- XXX.screens.multiplayer.Realms32bitWarningScreen
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ XXX.screens.multiplayer.WarningScreen
- XXX.screens.packs.package-info
- XXX.screens.packs.PackSelectionModel
+ XXX.screens.packs.PackSelectionModel$Entry
- XXX.screens.packs.PackSelectionModel$EntryBase
+ XXX.screens.packs.PackSelectionModel$SelectedPackEntry
- XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
+ XXX.screens.packs.PackSelectionScreen
- XXX.screens.packs.PackSelectionScreen$1
+ XXX.screens.packs.PackSelectionScreen$Watcher
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
- XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerEntry$3
+ XXX.screens.social.PlayerEntry$4
- XXX.screens.social.PlayerSocialManager
+ XXX.screens.social.SocialInteractionsPlayerList
- XXX.screens.social.SocialInteractionsScreen
+ XXX.screens.social.SocialInteractionsScreen$1
- XXX.screens.social.SocialInteractionsScreen$2
+ XXX.screens.social.SocialInteractionsScreen$Page
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$1
+ XXX.screens.worldselection.CreateWorldScreen$OperationFailedException
+ XXX.screens.worldselection.package-info
- XXX.screens.worldselection.PresetEditor
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.WorldCreationContext
- XXX.screens.worldselection.WorldCreationContext$Updater
- XXX.screens.worldselection.WorldOpenFlows
+ XXX.screens.worldselection.WorldPreset
+ XXX.screens.worldselection.WorldPreset$2
+ XXX.screens.worldselection.WorldPreset$4
+ XXX.screens.worldselection.WorldPreset$6
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntRange
+ XXX.storage.loot.IntRange$IntChecker
- XXX.storage.loot.IntRange$IntLimiter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
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
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.TagMatchTest
- XXX.synchronization.brigadier.DoubleArgumentInfo$Template
+ XXX.synchronization.brigadier.DoubleArgumentSerializer
- XXX.synchronization.brigadier.FloatArgumentInfo$Template
- XXX.synchronization.brigadier.IntegerArgumentInfo$Template
+ XXX.synchronization.brigadier.IntegerArgumentSerializer
- XXX.synchronization.brigadier.LongArgumentInfo$Template
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MobType
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.Saddleable
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.level.package-info
+ XXX.world.level.StructureFeatureManager
- XXX.world.level.StructureManager
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
- XXX.world.ticks.BlackholeTickAccess
+ XXX.world.ticks.BlackholeTickAccess$1
- XXX.world.ticks.BlackholeTickAccess$2
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
- XXX.worldgen.biome.Biomes
+ XXX.worldgen.biome.EndBiomes
- XXX.worldgen.biome.NetherBiomes
+ XXX.worldgen.biome.OverworldBiomes
- XXX.worldgen.biome.package-info
+ XXX.worldgen.features.AquaticFeatures
- XXX.worldgen.features.CaveFeatures
+ XXX.worldgen.features.EndFeatures
- XXX.worldgen.features.FeatureUtils
+ XXX.worldgen.features.MiscOverworldFeatures
- XXX.worldgen.features.NetherFeatures
+ XXX.worldgen.features.OreFeatures
+ XXX.worldgen.features.package-info
- XXX.worldgen.features.PileFeatures
+ XXX.worldgen.features.TreeFeatures
- XXX.worldgen.features.VegetationFeatures
+ XXX.worldgen.placement.AquaticPlacements
- XXX.worldgen.placement.CavePlacements
+ XXX.worldgen.placement.EndPlacements
- XXX.worldgen.placement.MiscOverworldPlacements
+ XXX.worldgen.placement.NetherPlacements
- XXX.worldgen.placement.OrePlacements
+ XXX.worldgen.placement.package-info
+ XXX.worldgen.placement.PlacementUtils
- XXX.worldgen.placement.TreePlacements
+ XXX.worldgen.placement.VegetationPlacements
- XXX.worldgen.placement.VillagePlacements
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
<hr/>