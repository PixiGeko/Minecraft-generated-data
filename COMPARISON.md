## Comparison with [26.1.2](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1.2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1.2</th><th>26.2-snapshot-2</th></tr><tr><td>DataPack version</td><td><pre>101.1</pre></td><td><pre>101.2</pre></td></tr><tr><td>ResourcePack version</td><td><pre>84.0</pre></td><td><pre>85.0</pre></td></tr><tr><td>World version</td><td><pre>4790</pre></td><td><pre>4884</pre></td></tr><tr><td>Protocol version</td><td><pre>775</pre></td><td><pre>1073742132</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ org.lwjgl:lwjgl-shaderc (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-shaderc (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-shaderc V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-spvc (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-spvc V3.4.1
+ org.lwjgl:lwjgl-vma (natives-linux) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows-arm64) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows-x86) V3.4.1
+ org.lwjgl:lwjgl-vma (natives-windows) V3.4.1
+ org.lwjgl:lwjgl-vma V3.4.1
+ org.lwjgl:lwjgl-vulkan (natives-macos-arm64) V3.4.1
+ org.lwjgl:lwjgl-vulkan (natives-macos) V3.4.1
+ org.lwjgl:lwjgl-vulkan V3.4.1
```

</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:air_drag_modifier
+ minecraft:bounciness
+ minecraft:friction_modifier
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
```

</details>
<details>
<summary>
block_entity_type
</summary>

```diff
+ minecraft:potent_sulfur
```

</details>
<details>
<summary>
block_type
</summary>

```diff
+ minecraft:potent_sulfur
- minecraft:weathering_copper_trap_door
+ minecraft:weathering_copper_trapdoor
```

</details>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:sulfur_cube_content
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
game_event
</summary>

```diff
+ minecraft:bounce
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_cube_bucket
+ minecraft:sulfur_cube_spawn_egg
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:noxious_gas
+ minecraft:noxious_gas_cloud
+ minecraft:sulfur_bubbles
+ minecraft:sulfur_cube_goo
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.cinnabar.break
+ minecraft:block.cinnabar.fall
+ minecraft:block.cinnabar.hit
+ minecraft:block.cinnabar.place
+ minecraft:block.cinnabar.step
+ minecraft:block.potent_sulfur.break
+ minecraft:block.potent_sulfur.fall
+ minecraft:block.potent_sulfur.hit
+ minecraft:block.potent_sulfur.noxious_gas
+ minecraft:block.potent_sulfur.place
+ minecraft:block.potent_sulfur.step
+ minecraft:block.sulfur.break
+ minecraft:block.sulfur.fall
+ minecraft:block.sulfur.hit
+ minecraft:block.sulfur.place
+ minecraft:block.sulfur.step
+ minecraft:entity.small_sulfur_cube.death
+ minecraft:entity.small_sulfur_cube.hurt
+ minecraft:entity.small_sulfur_cube.jump
+ minecraft:entity.small_sulfur_cube.squish
+ minecraft:entity.sulfur_cube.absorb
+ minecraft:entity.sulfur_cube.bounce
+ minecraft:entity.sulfur_cube.death
+ minecraft:entity.sulfur_cube.eject
+ minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hurt
+ minecraft:entity.sulfur_cube.jump
+ minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.squish
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:pointed_dripstone
+ minecraft:sequence
+ minecraft:speleothem
+ minecraft:speleothem_cluster
+ minecraft:template
```

</details>
<details>
<summary>
worldgen/material_rule
</summary>

```diff
+ minecraft:noise_gradient
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
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:air_drag_modifier
+ minecraft:bounciness
+ minecraft:friction_modifier
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
```

</details>
<details>
<summary>
universal_tags/block_entity_type.json
</summary>

```diff
+ minecraft:potent_sulfur
```

</details>
<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:potent_sulfur
- minecraft:weathering_copper_trap_door
+ minecraft:weathering_copper_trapdoor
```

</details>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:sulfur_cube_content
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:sulfur_cube
```

</details>
<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
+ minecraft:bounce
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:chiseled_cinnabar
+ minecraft:chiseled_sulfur
+ minecraft:cinnabar
+ minecraft:cinnabar_brick_slab
+ minecraft:cinnabar_brick_stairs
+ minecraft:cinnabar_brick_wall
+ minecraft:cinnabar_bricks
+ minecraft:cinnabar_slab
+ minecraft:cinnabar_stairs
+ minecraft:cinnabar_wall
+ minecraft:polished_cinnabar
+ minecraft:polished_cinnabar_slab
+ minecraft:polished_cinnabar_stairs
+ minecraft:polished_cinnabar_wall
+ minecraft:polished_sulfur
+ minecraft:polished_sulfur_slab
+ minecraft:polished_sulfur_stairs
+ minecraft:polished_sulfur_wall
+ minecraft:potent_sulfur
+ minecraft:sulfur
+ minecraft:sulfur_brick_slab
+ minecraft:sulfur_brick_stairs
+ minecraft:sulfur_brick_wall
+ minecraft:sulfur_bricks
+ minecraft:sulfur_cube_bucket
+ minecraft:sulfur_cube_spawn_egg
+ minecraft:sulfur_slab
+ minecraft:sulfur_stairs
+ minecraft:sulfur_wall
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:noxious_gas
+ minecraft:noxious_gas_cloud
+ minecraft:sulfur_bubbles
+ minecraft:sulfur_cube_goo
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.cinnabar.break
+ minecraft:block.cinnabar.fall
+ minecraft:block.cinnabar.hit
+ minecraft:block.cinnabar.place
+ minecraft:block.cinnabar.step
+ minecraft:block.potent_sulfur.break
+ minecraft:block.potent_sulfur.fall
+ minecraft:block.potent_sulfur.hit
+ minecraft:block.potent_sulfur.noxious_gas
+ minecraft:block.potent_sulfur.place
+ minecraft:block.potent_sulfur.step
+ minecraft:block.sulfur.break
+ minecraft:block.sulfur.fall
+ minecraft:block.sulfur.hit
+ minecraft:block.sulfur.place
+ minecraft:block.sulfur.step
+ minecraft:entity.small_sulfur_cube.death
+ minecraft:entity.small_sulfur_cube.hurt
+ minecraft:entity.small_sulfur_cube.jump
+ minecraft:entity.small_sulfur_cube.squish
+ minecraft:entity.sulfur_cube.absorb
+ minecraft:entity.sulfur_cube.bounce
+ minecraft:entity.sulfur_cube.death
+ minecraft:entity.sulfur_cube.eject
+ minecraft:entity.sulfur_cube.hit
+ minecraft:entity.sulfur_cube.hurt
+ minecraft:entity.sulfur_cube.jump
+ minecraft:entity.sulfur_cube.push
+ minecraft:entity.sulfur_cube.squish
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:dripstone_cluster
- minecraft:pointed_dripstone
+ minecraft:sequence
+ minecraft:speleothem
+ minecraft:speleothem_cluster
+ minecraft:template
```

</details>
<details>
<summary>
universal_tags/worldgen/material_rule.json
</summary>

```diff
+ minecraft:noise_gradient
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
+ chiseled_cinnabar.json
+ chiseled_sulfur.json
+ cinnabar_brick_slab.json
+ cinnabar_brick_stairs.json
+ cinnabar_brick_wall.json
+ cinnabar_bricks.json
+ cinnabar_slab.json
+ cinnabar_stairs.json
+ cinnabar_wall.json
+ cinnabar.json
+ polished_cinnabar_slab.json
+ polished_cinnabar_stairs.json
+ polished_cinnabar_wall.json
+ polished_cinnabar.json
+ polished_sulfur_slab.json
+ polished_sulfur_stairs.json
+ polished_sulfur_wall.json
+ polished_sulfur.json
+ potent_sulfur.json
+ sulfur_brick_slab.json
+ sulfur_brick_stairs.json
+ sulfur_brick_wall.json
+ sulfur_bricks.json
+ sulfur_slab.json
+ sulfur_stairs.json
+ sulfur_wall.json
+ sulfur.json
```

</details>
<details>
<summary>
copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1.2</th><th>26.2-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1.2</th><th>26.2-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1.2</th><th>26.2-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_trapdoor
</summary>
<br/>
<b>DEFINITION</b>

<table><tr><th></th><th align="left">26.1.2</th><th>26.2-snapshot-2</th></tr><tr><td>type</td><td><pre>minecraft:weathering_copper_trap_door</pre></td><td><pre>minecraft:weathering_copper_trapdoor</pre></td></tr></table>
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
+ chiseled_cinnabar_from_cinnabar_stonecutting.json
+ chiseled_cinnabar.json
+ chiseled_sulfur_from_sulfur_stonecutting.json
+ chiseled_sulfur.json
+ cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_slab.json
+ cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_stairs.json
+ cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ cinnabar_brick_wall.json
+ cinnabar_bricks_from_cinnabar_stonecutting.json
+ cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ cinnabar_bricks.json
+ cinnabar_slab_from_cinnabar_stonecutting.json
+ cinnabar_slab.json
+ cinnabar_stairs_from_cinnabar_stonecutting.json
+ cinnabar_stairs.json
+ cinnabar_wall_from_cinnabar_stonecutting.json
+ cinnabar_wall.json
+ polished_cinnabar_from_cinnabar_stonecutting.json
+ polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_slab.json
+ polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_stairs.json
+ polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ polished_cinnabar_wall.json
+ polished_cinnabar.json
+ polished_sulfur_from_sulfur_stonecutting.json
+ polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ polished_sulfur_slab_from_sulfur_stonecutting.json
+ polished_sulfur_slab.json
+ polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ polished_sulfur_stairs_from_sulfur_stonecutting.json
+ polished_sulfur_stairs.json
+ polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ polished_sulfur_wall_from_sulfur_stonecutting.json
+ polished_sulfur_wall.json
+ polished_sulfur.json
+ potent_sulfur.json
+ sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_slab_from_sulfur_stonecutting.json
+ sulfur_brick_slab.json
+ sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_stairs_from_sulfur_stonecutting.json
+ sulfur_brick_stairs.json
+ sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ sulfur_brick_wall_from_sulfur_stonecutting.json
+ sulfur_brick_wall.json
+ sulfur_bricks_from_polished_sulfur_stonecutting.json
+ sulfur_bricks_from_sulfur_stonecutting.json
+ sulfur_bricks.json
+ sulfur_slab_from_sulfur_stonecutting.json
+ sulfur_slab.json
+ sulfur_stairs_from_sulfur_stonecutting.json
+ sulfur_stairs.json
+ sulfur_wall_from_sulfur_stonecutting.json
+ sulfur_wall.json
+ sulfur.json
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
+ minecraft:sulfur_cube_archetype
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
+ attribute.name.air_drag_modifier: Air Drag Modifier
+ attribute.name.bounciness: Bounciness
+ attribute.name.friction_modifier: Friction Modifier
+ biome.minecraft.sulfur_caves: Sulfur Caves
+ block.minecraft.chiseled_cinnabar: Chiseled Cinnabar
+ block.minecraft.chiseled_sulfur: Chiseled Sulfur
+ block.minecraft.cinnabar_brick_slab: Cinnabar Brick Slab
+ block.minecraft.cinnabar_brick_stairs: Cinnabar Brick Stairs
+ block.minecraft.cinnabar_brick_wall: Cinnabar Brick Wall
+ block.minecraft.cinnabar_bricks: Cinnabar Bricks
+ block.minecraft.cinnabar_slab: Cinnabar Slab
+ block.minecraft.cinnabar_stairs: Cinnabar Stairs
+ block.minecraft.cinnabar_wall: Cinnabar Wall
+ block.minecraft.cinnabar: Cinnabar
+ block.minecraft.polished_cinnabar_slab: Polished Cinnabar Slab
+ block.minecraft.polished_cinnabar_stairs: Polished Cinnabar Stairs
+ block.minecraft.polished_cinnabar_wall: Polished Cinnabar Wall
+ block.minecraft.polished_cinnabar: Polished Cinnabar
+ block.minecraft.polished_sulfur_slab: Polished Sulfur Slab
+ block.minecraft.polished_sulfur_stairs: Polished Sulfur Stairs
+ block.minecraft.polished_sulfur_wall: Polished Sulfur Wall
+ block.minecraft.polished_sulfur: Polished Sulfur Block
+ block.minecraft.potent_sulfur: Potent Sulfur
+ block.minecraft.sulfur_brick_slab: Sulfur Brick Slab
+ block.minecraft.sulfur_brick_stairs: Sulfur Brick Stairs
+ block.minecraft.sulfur_brick_wall: Sulfur Brick Wall
+ block.minecraft.sulfur_bricks: Sulfur Bricks
+ block.minecraft.sulfur_slab: Sulfur Slab
+ block.minecraft.sulfur_stairs: Sulfur Stairs
+ block.minecraft.sulfur_wall: Sulfur Wall
+ block.minecraft.sulfur: Sulfur
+ entity.minecraft.sulfur_cube: Sulfur Cube
+ entity.minecraft.sulfur_cube.content: Contains: %s
+ item.minecraft.sulfur_cube_bucket: Bucket of Sulfur Cube
+ item.minecraft.sulfur_cube_spawn_egg: Sulfur Cube Spawn Egg
+ options.graphicsApi: Graphics API
+ options.graphicsApi.default: Default
+ options.graphicsApi.opengl: Prefer OpenGL
+ options.graphicsApi.restart: You must restart your game to change the graphics API.
+ options.graphicsApi.tooltip: Which graphics API to use for rendering. Leave as Default unless you have a specific need to change this! Will take affect the next time you start the game.
+ options.graphicsApi.vulkan: Prefer Vulkan
+ subtitles.block.potent_sulfur.noxious_gas: Noxious gas appears
+ subtitles.entity.sulfur_cube.absorb: Sulfur Cube full
+ subtitles.entity.sulfur_cube.bounce: Sulfur Cube bounces
+ subtitles.entity.sulfur_cube.death: Sulfur Cube dies
+ subtitles.entity.sulfur_cube.eject: Block removed
+ subtitles.entity.sulfur_cube.hit: Sulfur Cube hit
+ subtitles.entity.sulfur_cube.hurt: Sulfur Cube hurts
+ subtitles.entity.sulfur_cube.push: Sulfur Cube pushed
+ subtitles.entity.sulfur_cube.squish: Sulfur Cube bounces
+ test.error.value_not_in_between: Expected %s to be in between %s and %s: was %s
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.1.2</th><th>26.2-snapshot-2</th></tr>
<tr><th align="left"><div style="width:290px">advancements.story.enter_the_nether.description</div></th><td>Build, light and enter a Nether Portal</td><td>Build, light, and enter a Nether Portal</td></tr>
<tr><th align="left"><div style="width:290px">argument.resource_or_id.invalid</div></th><td>Invalid id or tag</td><td>Invalid ID or tag</td></tr>
<tr><th align="left"><div style="width:290px">build.tooHigh</div></th><td>Height limit for building is %s</td><td>The height limit for building is %s</td></tr>
<tr><th align="left"><div style="width:290px">build.tooLow</div></th><td>Minimum height for building is %s</td><td>The minimum height for building is %s</td></tr>
<tr><th align="left"><div style="width:290px">command.failed</div></th><td>An unexpected error occurred trying to execute that command</td><td>An unexpected error occurred while trying to execute that command</td></tr>
<tr><th align="left"><div style="width:290px">commands.locate.biome.not_found</div></th><td>Could not find a biome of type "%s" within reasonable distance</td><td>Could not find a biome of type "%s" within a reasonable distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.locate.poi.not_found</div></th><td>Could not find a point of interest of type "%s" within reasonable distance</td><td>Could not find a point of interest of type "%s" within a reasonable distance</td></tr>
<tr><th align="left"><div style="width:290px">commands.place.template.invalid</div></th><td>There is no template with id "%s"</td><td>There is no template with ID "%s"</td></tr>
<tr><th align="left"><div style="width:290px">commands.profile_fetch.id.failure</div></th><td>Failed to resolved profile for id %s</td><td>Failed to resolve profile for ID %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.profile_fetch.id.success</div></th><td>Resolved profile for id %s: %s</td><td>Resolved profile for ID %s: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.schedule.cleared.failure</div></th><td>No schedules with id %s</td><td>No schedules with ID %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.schedule.cleared.success</div></th><td>Removed %s schedule(s) with id %s</td><td>Removed %s schedule(s) with ID %s</td></tr>
<tr><th align="left"><div style="width:290px">datapackFailure.title</div></th><td>Errors in currently selected data packs prevented the world from loading.

You can either try to load it with only the vanilla data pack ("safe mode"), or go back to the title screen and fix it manually.</td><td>Errors in the currently selected data pack(s) prevented the world from loading.

You can either try to load it with only the vanilla data pack ("Safe Mode"), or go back to the title screen and fix it manually.</td></tr>
<tr><th align="left"><div style="width:290px">filled_map.id</div></th><td>Id #%s</td><td>ID #%s</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.lavaSourceConversion.description</div></th><td>When flowing lava is surrounded on two sides by lava sources it converts into a source.</td><td>When flowing lava is surrounded on two sides by lava sources, it converts into a source.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalCreativeDelay</div></th><td>Player's Nether portal delay in creative mode</td><td>Player's Nether Portal delay in creative mode</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalCreativeDelay.description</div></th><td>Time (in ticks) that a creative mode player needs to stand in a Nether portal before changing dimensions.</td><td>Time (in ticks) that a creative mode player needs to stand in a Nether Portal before changing dimensions.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalDefaultDelay</div></th><td>Player's Nether portal delay in non-creative mode</td><td>Player's Nether Portal delay in non-creative mode</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.playersNetherPortalDefaultDelay.description</div></th><td>Time (in ticks) that a non-creative mode player needs to stand in a Nether portal before changing dimensions.</td><td>Time (in ticks) that a non-creative mode player needs to stand in a Nether Portal before changing dimensions.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.waterSourceConversion.description</div></th><td>When flowing water is surrounded on two sides by water sources it converts into a source.</td><td>When flowing water is surrounded on two sides by water sources, it converts into a source.</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.discard.title</div></th><td>Discard report and comments?</td><td>Discard Report and Comments?</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.draft.title</div></th><td>Edit draft chat report?</td><td>Edit Draft Chat Report?</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.error.title</div></th><td>Problem sending your report</td><td>Problem Sending Your Report</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.sending.title</div></th><td>Sending your report...</td><td>Sending Your Report...</td></tr>
<tr><th align="left"><div style="width:290px">gui.abuseReport.sent.title</div></th><td>Report sent</td><td>Report Sent</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.title.permanent</div></th><td>Account permanently banned</td><td>Account Permanently Banned</td></tr>
<tr><th align="left"><div style="width:290px">gui.banned.title.temporary</div></th><td>Account temporarily suspended</td><td>Account Temporarily Suspended</td></tr>
<tr><th align="left"><div style="width:290px">gui.chatReport.discard.title</div></th><td>Discard report and comments?</td><td>Discard Report and Comments?</td></tr>
<tr><th align="left"><div style="width:290px">gui.chatReport.draft.title</div></th><td>Edit draft chat report?</td><td>Edit Draft Chat Report?</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.leave.question.line1</div></th><td>If you leave this Realm you won't see it unless you are invited again</td><td>If you leave this Realm, you won't see it unless you are invited again</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.restore.download.question.line1</div></th><td>The world will be downloaded and added to your single player worlds.</td><td>The world will be downloaded and added to your singleplayer worlds.</td></tr>
<tr><th align="left"><div style="width:290px">mco.selectServer.popup</div></th><td>Realms is a safe, simple way to enjoy an online Minecraft world with up to ten friends at a time. It supports loads of minigames and plenty of custom worlds! Only the owner of the realm needs to pay.</td><td>Realms is a safe, simple way to enjoy an online Minecraft world with up to ten friends at a time. It supports loads of minigames and plenty of custom worlds! Only the owner of the Realm needs to pay.</td></tr>
<tr><th align="left"><div style="width:290px">options.allowServerListing.tooltip</div></th><td>Servers may list online players as part of their public status.

With this option off your name will not show up in such lists.</td><td>Servers may list online players as part of their public status.

With this option off, your name will not show up in such lists.</td></tr>
<tr><th align="left"><div style="width:290px">options.directionalAudio.on.tooltip</div></th><td>Uses HRTF-based directional audio to improve the simulation of 3D sound. Requires HRTF compatible audio hardware, and is best experienced with headphones.</td><td>Uses HRTF-based directional audio to improve the simulation of 3D sound. Requires HRTF-compatible audio hardware, and is best experienced with headphones.</td></tr>
<tr><th align="left"><div style="width:290px">options.screenEffectScale.tooltip</div></th><td>Strength of nausea and Nether portal screen distortion effects.

At lower values, the nausea effect is replaced with a green overlay.</td><td>Strength of Nausea and Nether Portal screen distortion effects.

At lower values, the Nausea effect is replaced with a green overlay.</td></tr>
<tr><th align="left"><div style="width:290px">options.textureFiltering.anisotropic.tooltip</div></th><td>A hardware based filtering method, but impacts performance and significantly impacts video memory usage. May not be supported on all hardware.</td><td>A hardware-based filtering method, but impacts performance and significantly impacts video memory usage. May not be supported on all hardware.</td></tr>
<tr><th align="left"><div style="width:290px">options.textureFiltering.rgss.tooltip</div></th><td>(Rotated Grid Super Sampling)

A shader based filtering method that improves texture quality with a moderate performance impact.</td><td>(Rotated Grid Super Sampling)

A shader-based filtering method that improves texture quality with a moderate performance impact.</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupJoinSkipButton</div></th><td>I know what I'm doing!</td><td>I Know What I'm Doing!</td></tr>
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
+ reports/minecraft/components/item/chiseled_cinnabar.json
+ reports/minecraft/components/item/chiseled_sulfur.json
+ reports/minecraft/components/item/cinnabar_brick_slab.json
+ reports/minecraft/components/item/cinnabar_brick_stairs.json
+ reports/minecraft/components/item/cinnabar_brick_wall.json
+ reports/minecraft/components/item/cinnabar_bricks.json
+ reports/minecraft/components/item/cinnabar_slab.json
+ reports/minecraft/components/item/cinnabar_stairs.json
+ reports/minecraft/components/item/cinnabar_wall.json
+ reports/minecraft/components/item/cinnabar.json
+ reports/minecraft/components/item/polished_cinnabar_slab.json
+ reports/minecraft/components/item/polished_cinnabar_stairs.json
+ reports/minecraft/components/item/polished_cinnabar_wall.json
+ reports/minecraft/components/item/polished_cinnabar.json
+ reports/minecraft/components/item/polished_sulfur_slab.json
+ reports/minecraft/components/item/polished_sulfur_stairs.json
+ reports/minecraft/components/item/polished_sulfur_wall.json
+ reports/minecraft/components/item/polished_sulfur.json
+ reports/minecraft/components/item/potent_sulfur.json
+ reports/minecraft/components/item/sulfur_brick_slab.json
+ reports/minecraft/components/item/sulfur_brick_stairs.json
+ reports/minecraft/components/item/sulfur_brick_wall.json
+ reports/minecraft/components/item/sulfur_bricks.json
+ reports/minecraft/components/item/sulfur_cube_bucket.json
+ reports/minecraft/components/item/sulfur_cube_spawn_egg.json
+ reports/minecraft/components/item/sulfur_slab.json
+ reports/minecraft/components/item/sulfur_stairs.json
+ reports/minecraft/components/item/sulfur_wall.json
+ reports/minecraft/components/item/sulfur.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/chiseled_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_cinnabar.json
+ minecraft/advancement/recipes/building_blocks/chiseled_sulfur_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/chiseled_sulfur.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_bricks.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_slab.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/cinnabar_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_cinnabar.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_sulfur.json
+ minecraft/advancement/recipes/building_blocks/potent_sulfur.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_bricks.json
+ minecraft/advancement/recipes/building_blocks/sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_slab.json
+ minecraft/advancement/recipes/building_blocks/sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/sulfur_stairs.json
+ minecraft/advancement/recipes/building_blocks/sulfur.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_brick_wall.json
+ minecraft/advancement/recipes/decorations/cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/cinnabar_wall.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_cinnabar_wall.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_sulfur_wall.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_brick_wall.json
+ minecraft/advancement/recipes/decorations/sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/advancement/recipes/decorations/sulfur_wall.json
+ minecraft/loot_table/blocks/chiseled_cinnabar.json
+ minecraft/loot_table/blocks/chiseled_sulfur.json
+ minecraft/loot_table/blocks/cinnabar_brick_slab.json
+ minecraft/loot_table/blocks/cinnabar_brick_stairs.json
+ minecraft/loot_table/blocks/cinnabar_brick_wall.json
+ minecraft/loot_table/blocks/cinnabar_bricks.json
+ minecraft/loot_table/blocks/cinnabar_slab.json
+ minecraft/loot_table/blocks/cinnabar_stairs.json
+ minecraft/loot_table/blocks/cinnabar_wall.json
+ minecraft/loot_table/blocks/cinnabar.json
+ minecraft/loot_table/blocks/polished_cinnabar_slab.json
+ minecraft/loot_table/blocks/polished_cinnabar_stairs.json
+ minecraft/loot_table/blocks/polished_cinnabar_wall.json
+ minecraft/loot_table/blocks/polished_cinnabar.json
+ minecraft/loot_table/blocks/polished_sulfur_slab.json
+ minecraft/loot_table/blocks/polished_sulfur_stairs.json
+ minecraft/loot_table/blocks/polished_sulfur_wall.json
+ minecraft/loot_table/blocks/polished_sulfur.json
+ minecraft/loot_table/blocks/potent_sulfur.json
+ minecraft/loot_table/blocks/sulfur_brick_slab.json
+ minecraft/loot_table/blocks/sulfur_brick_stairs.json
+ minecraft/loot_table/blocks/sulfur_brick_wall.json
+ minecraft/loot_table/blocks/sulfur_bricks.json
+ minecraft/loot_table/blocks/sulfur_slab.json
+ minecraft/loot_table/blocks/sulfur_stairs.json
+ minecraft/loot_table/blocks/sulfur_wall.json
+ minecraft/loot_table/blocks/sulfur.json
+ minecraft/loot_table/entities/sulfur_cube.json
+ minecraft/recipe/chiseled_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/recipe/chiseled_cinnabar.json
+ minecraft/recipe/chiseled_sulfur_from_sulfur_stonecutting.json
+ minecraft/recipe/chiseled_sulfur.json
+ minecraft/recipe/cinnabar_brick_slab_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_slab.json
+ minecraft/recipe/cinnabar_brick_stairs_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_stairs.json
+ minecraft/recipe/cinnabar_brick_wall_from_cinnabar_bricks_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_brick_wall.json
+ minecraft/recipe/cinnabar_bricks_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_bricks_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_bricks.json
+ minecraft/recipe/cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_slab.json
+ minecraft/recipe/cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_stairs.json
+ minecraft/recipe/cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/cinnabar_wall.json
+ minecraft/recipe/polished_cinnabar_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_slab.json
+ minecraft/recipe/polished_cinnabar_stairs_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_stairs_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_stairs.json
+ minecraft/recipe/polished_cinnabar_wall_from_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_wall_from_polished_cinnabar_stonecutting.json
+ minecraft/recipe/polished_cinnabar_wall.json
+ minecraft/recipe/polished_cinnabar.json
+ minecraft/recipe/polished_sulfur_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_slab.json
+ minecraft/recipe/polished_sulfur_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_stairs.json
+ minecraft/recipe/polished_sulfur_wall_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/polished_sulfur_wall.json
+ minecraft/recipe/polished_sulfur.json
+ minecraft/recipe/potent_sulfur.json
+ minecraft/recipe/sulfur_brick_slab_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_slab.json
+ minecraft/recipe/sulfur_brick_stairs_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_stairs.json
+ minecraft/recipe/sulfur_brick_wall_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall_from_sulfur_bricks_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_brick_wall.json
+ minecraft/recipe/sulfur_bricks_from_polished_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_bricks_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_bricks.json
+ minecraft/recipe/sulfur_slab_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_slab.json
+ minecraft/recipe/sulfur_stairs_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_stairs.json
+ minecraft/recipe/sulfur_wall_from_sulfur_stonecutting.json
+ minecraft/recipe/sulfur_wall.json
+ minecraft/recipe/sulfur.json
+ minecraft/structure/spring/sulfur_spring_extra_large_1.nbt
+ minecraft/structure/spring/sulfur_spring_large_1.nbt
+ minecraft/structure/spring/sulfur_spring_large_2.nbt
+ minecraft/structure/spring/sulfur_spring_medium_1.nbt
+ minecraft/structure/spring/sulfur_spring_medium_2.nbt
+ minecraft/structure/spring/sulfur_spring_medium_3.nbt
+ minecraft/structure/spring/sulfur_spring_small_1.nbt
+ minecraft/structure/spring/sulfur_spring_small_2.nbt
+ minecraft/structure/spring/sulfur_spring_small_3.nbt
+ minecraft/structure/spring/sulfur_spring_small_4.nbt
+ minecraft/sulfur_cube_archetype/bouncy.json
+ minecraft/sulfur_cube_archetype/fast_flat.json
+ minecraft/sulfur_cube_archetype/fast_sliding.json
+ minecraft/sulfur_cube_archetype/high_resistance.json
+ minecraft/sulfur_cube_archetype/light.json
+ minecraft/sulfur_cube_archetype/regular.json
+ minecraft/sulfur_cube_archetype/slow_flat.json
+ minecraft/sulfur_cube_archetype/slow_sliding.json
+ minecraft/sulfur_cube_archetype/sticky.json
- minecraft/tags/block/concrete_powder.json
+ minecraft/tags/block/concrete_powders.json
+ minecraft/tags/block/concrete.json
+ minecraft/tags/block/glazed_terracotta.json
+ minecraft/tags/block/shears_extreme_breaking_speed.json
+ minecraft/tags/block/shears_major_breaking_speed.json
+ minecraft/tags/block/shears_minor_breaking_speed.json
+ minecraft/tags/block/suppresses_bounce.json
+ minecraft/tags/damage_type/sulfur_cube_with_block_immune_to.json
+ minecraft/tags/item/concrete_powders.json
+ minecraft/tags/item/concrete.json
+ minecraft/tags/item/glazed_terracotta.json
+ minecraft/tags/item/sulfur_cube_archetype/bouncy.json
+ minecraft/tags/item/sulfur_cube_archetype/fast_flat.json
+ minecraft/tags/item/sulfur_cube_archetype/fast_sliding.json
+ minecraft/tags/item/sulfur_cube_archetype/high_resistance.json
+ minecraft/tags/item/sulfur_cube_archetype/light.json
+ minecraft/tags/item/sulfur_cube_archetype/regular.json
+ minecraft/tags/item/sulfur_cube_archetype/slow_flat.json
+ minecraft/tags/item/sulfur_cube_archetype/slow_sliding.json
+ minecraft/tags/item/sulfur_cube_archetype/sticky.json
+ minecraft/tags/item/sulfur_cube_food.json
+ minecraft/tags/item/sulfur_cube_swallowable.json
+ minecraft/worldgen/biome/sulfur_caves.json
+ minecraft/worldgen/configured_feature/rooted_sulfur_spring.json
+ minecraft/worldgen/configured_feature/sulfur_pool.json
+ minecraft/worldgen/configured_feature/sulfur_spring.json
+ minecraft/worldgen/noise/sulfur_cave_gradient.json
+ minecraft/worldgen/placed_feature/rooted_sulfur_spring.json
+ minecraft/worldgen/placed_feature/sulfur_pool.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/chiseled_cinnabar.json
+ minecraft/blockstates/chiseled_sulfur.json
+ minecraft/blockstates/cinnabar_brick_slab.json
+ minecraft/blockstates/cinnabar_brick_stairs.json
+ minecraft/blockstates/cinnabar_brick_wall.json
+ minecraft/blockstates/cinnabar_bricks.json
+ minecraft/blockstates/cinnabar_slab.json
+ minecraft/blockstates/cinnabar_stairs.json
+ minecraft/blockstates/cinnabar_wall.json
+ minecraft/blockstates/cinnabar.json
+ minecraft/blockstates/polished_cinnabar_slab.json
+ minecraft/blockstates/polished_cinnabar_stairs.json
+ minecraft/blockstates/polished_cinnabar_wall.json
+ minecraft/blockstates/polished_cinnabar.json
+ minecraft/blockstates/polished_sulfur_slab.json
+ minecraft/blockstates/polished_sulfur_stairs.json
+ minecraft/blockstates/polished_sulfur_wall.json
+ minecraft/blockstates/polished_sulfur.json
+ minecraft/blockstates/potent_sulfur.json
+ minecraft/blockstates/sulfur_brick_slab.json
+ minecraft/blockstates/sulfur_brick_stairs.json
+ minecraft/blockstates/sulfur_brick_wall.json
+ minecraft/blockstates/sulfur_bricks.json
+ minecraft/blockstates/sulfur_slab.json
+ minecraft/blockstates/sulfur_stairs.json
+ minecraft/blockstates/sulfur_wall.json
+ minecraft/blockstates/sulfur.json
+ minecraft/items/chiseled_cinnabar.json
+ minecraft/items/chiseled_sulfur.json
+ minecraft/items/cinnabar_brick_slab.json
+ minecraft/items/cinnabar_brick_stairs.json
+ minecraft/items/cinnabar_brick_wall.json
+ minecraft/items/cinnabar_bricks.json
+ minecraft/items/cinnabar_slab.json
+ minecraft/items/cinnabar_stairs.json
+ minecraft/items/cinnabar_wall.json
+ minecraft/items/cinnabar.json
+ minecraft/items/polished_cinnabar_slab.json
+ minecraft/items/polished_cinnabar_stairs.json
+ minecraft/items/polished_cinnabar_wall.json
+ minecraft/items/polished_cinnabar.json
+ minecraft/items/polished_sulfur_slab.json
+ minecraft/items/polished_sulfur_stairs.json
+ minecraft/items/polished_sulfur_wall.json
+ minecraft/items/polished_sulfur.json
+ minecraft/items/potent_sulfur.json
+ minecraft/items/sulfur_brick_slab.json
+ minecraft/items/sulfur_brick_stairs.json
+ minecraft/items/sulfur_brick_wall.json
+ minecraft/items/sulfur_bricks.json
+ minecraft/items/sulfur_cube_bucket.json
+ minecraft/items/sulfur_cube_spawn_egg.json
+ minecraft/items/sulfur_slab.json
+ minecraft/items/sulfur_stairs.json
+ minecraft/items/sulfur_wall.json
+ minecraft/items/sulfur.json
+ minecraft/models/block/chiseled_cinnabar.json
+ minecraft/models/block/chiseled_sulfur.json
+ minecraft/models/block/cinnabar_brick_slab_top.json
+ minecraft/models/block/cinnabar_brick_slab.json
+ minecraft/models/block/cinnabar_brick_stairs_inner.json
+ minecraft/models/block/cinnabar_brick_stairs_outer.json
+ minecraft/models/block/cinnabar_brick_stairs.json
+ minecraft/models/block/cinnabar_brick_wall_inventory.json
+ minecraft/models/block/cinnabar_brick_wall_post.json
+ minecraft/models/block/cinnabar_brick_wall_side_tall.json
+ minecraft/models/block/cinnabar_brick_wall_side.json
+ minecraft/models/block/cinnabar_bricks.json
+ minecraft/models/block/cinnabar_slab_top.json
+ minecraft/models/block/cinnabar_slab.json
+ minecraft/models/block/cinnabar_stairs_inner.json
+ minecraft/models/block/cinnabar_stairs_outer.json
+ minecraft/models/block/cinnabar_stairs.json
+ minecraft/models/block/cinnabar_wall_inventory.json
+ minecraft/models/block/cinnabar_wall_post.json
+ minecraft/models/block/cinnabar_wall_side_tall.json
+ minecraft/models/block/cinnabar_wall_side.json
+ minecraft/models/block/cinnabar.json
+ minecraft/models/block/polished_cinnabar_slab_top.json
+ minecraft/models/block/polished_cinnabar_slab.json
+ minecraft/models/block/polished_cinnabar_stairs_inner.json
+ minecraft/models/block/polished_cinnabar_stairs_outer.json
+ minecraft/models/block/polished_cinnabar_stairs.json
+ minecraft/models/block/polished_cinnabar_wall_inventory.json
+ minecraft/models/block/polished_cinnabar_wall_post.json
+ minecraft/models/block/polished_cinnabar_wall_side_tall.json
+ minecraft/models/block/polished_cinnabar_wall_side.json
+ minecraft/models/block/polished_cinnabar.json
+ minecraft/models/block/polished_sulfur_slab_top.json
+ minecraft/models/block/polished_sulfur_slab.json
+ minecraft/models/block/polished_sulfur_stairs_inner.json
+ minecraft/models/block/polished_sulfur_stairs_outer.json
+ minecraft/models/block/polished_sulfur_stairs.json
+ minecraft/models/block/polished_sulfur_wall_inventory.json
+ minecraft/models/block/polished_sulfur_wall_post.json
+ minecraft/models/block/polished_sulfur_wall_side_tall.json
+ minecraft/models/block/polished_sulfur_wall_side.json
+ minecraft/models/block/polished_sulfur.json
+ minecraft/models/block/potent_sulfur.json
+ minecraft/models/block/sulfur_brick_slab_top.json
+ minecraft/models/block/sulfur_brick_slab.json
+ minecraft/models/block/sulfur_brick_stairs_inner.json
+ minecraft/models/block/sulfur_brick_stairs_outer.json
+ minecraft/models/block/sulfur_brick_stairs.json
+ minecraft/models/block/sulfur_brick_wall_inventory.json
+ minecraft/models/block/sulfur_brick_wall_post.json
+ minecraft/models/block/sulfur_brick_wall_side_tall.json
+ minecraft/models/block/sulfur_brick_wall_side.json
+ minecraft/models/block/sulfur_bricks.json
+ minecraft/models/block/sulfur_slab_top.json
+ minecraft/models/block/sulfur_slab.json
+ minecraft/models/block/sulfur_stairs_inner.json
+ minecraft/models/block/sulfur_stairs_outer.json
+ minecraft/models/block/sulfur_stairs.json
+ minecraft/models/block/sulfur_wall_inventory.json
+ minecraft/models/block/sulfur_wall_post.json
+ minecraft/models/block/sulfur_wall_side_tall.json
+ minecraft/models/block/sulfur_wall_side.json
+ minecraft/models/block/sulfur.json
+ minecraft/models/item/sulfur_cube_bucket.json
+ minecraft/models/item/sulfur_cube_spawn_egg.json
+ minecraft/particles/noxious_gas.json
+ minecraft/particles/sulfur_bubbles.json
+ minecraft/particles/sulfur_cube_goo.json
- minecraft/shaders/core/rendertype_text_background_see_through.fsh
- minecraft/shaders/core/rendertype_text_background_see_through.vsh
- minecraft/shaders/core/rendertype_text_background.fsh
- minecraft/shaders/core/rendertype_text_background.vsh
- minecraft/shaders/core/rendertype_text_intensity_see_through.fsh
- minecraft/shaders/core/rendertype_text_intensity_see_through.vsh
- minecraft/shaders/core/rendertype_text_intensity.fsh
- minecraft/shaders/core/rendertype_text_intensity.vsh
- minecraft/shaders/core/rendertype_text_see_through.fsh
- minecraft/shaders/core/rendertype_text_see_through.vsh
- minecraft/shaders/core/rendertype_text.fsh
- minecraft/shaders/core/rendertype_text.vsh
+ minecraft/shaders/core/text_background.fsh
+ minecraft/shaders/core/text_background.vsh
+ minecraft/shaders/core/text.fsh
+ minecraft/shaders/core/text.vsh
+ minecraft/textures/block/chiseled_cinnabar.png
+ minecraft/textures/block/chiseled_sulfur.png
+ minecraft/textures/block/cinnabar_bricks.png
+ minecraft/textures/block/cinnabar.png
+ minecraft/textures/block/polished_cinnabar.png
+ minecraft/textures/block/polished_sulfur.png
+ minecraft/textures/block/potent_sulfur.png
+ minecraft/textures/block/sulfur_bricks.png
+ minecraft/textures/block/sulfur.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_inner.png
+ minecraft/textures/entity/sulfur_cube/sulfur_cube_outer.png
+ minecraft/textures/item/sulfur_cube_bucket.png
+ minecraft/textures/item/sulfur_cube_spawn_egg.png
+ minecraft/textures/particle/bubble_white.png
+ minecraft/textures/particle/noxious_gas_01.png
+ minecraft/textures/particle/noxious_gas_02.png
+ minecraft/textures/particle/noxious_gas_03.png
+ minecraft/textures/particle/noxious_gas_04.png
+ minecraft/textures/particle/noxious_gas_05.png
+ minecraft/textures/particle/noxious_gas_06.png
+ minecraft/textures/particle/noxious_gas_07.png
+ minecraft/textures/particle/noxious_gas_08.png
+ minecraft/textures/particle/sulfur_cube_goo.png
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
+ Now on Vulkan 1.2!
```

</details>
</details>
<hr/>