## Comparison with [23w42a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w42a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">23w42a</th><th>23w43a</th></tr><tr><td>DataPack version</td><td><code>21</code></td><td><code>22</code></td></tr><tr><td>ResourcePack version</td><td><code>19</code></td><td><code>20</code></td></tr><tr><td>World version</td><td><code>3684</code></td><td><code>3686</code></td></tr><tr><td>Protocol version</td><td><code>1073741981</code></td><td><code>1073741983</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>


<details>
<summary>
block_type.txt
</summary>

```diff
+ minecraft:copper_bulb_block
- minecraft:glass
+ minecraft:transparent
+ minecraft:weathering_copper_bulb
+ minecraft:weathering_copper_door
+ minecraft:weathering_copper_grate
+ minecraft:weathering_copper_trap_door
```

</details>















<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>





















<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.copper_bulb.break
+ minecraft:block.copper_bulb.fall
+ minecraft:block.copper_bulb.hit
+ minecraft:block.copper_bulb.place
+ minecraft:block.copper_bulb.step
+ minecraft:block.copper_bulb.turn_off
+ minecraft:block.copper_bulb.turn_on
+ minecraft:block.copper_door.close
+ minecraft:block.copper_door.open
+ minecraft:block.copper_grate.break
+ minecraft:block.copper_grate.fall
+ minecraft:block.copper_grate.hit
+ minecraft:block.copper_grate.place
+ minecraft:block.copper_grate.step
+ minecraft:block.copper_trapdoor.close
+ minecraft:block.copper_trapdoor.open
+ minecraft:block.polished_tuff.break
+ minecraft:block.polished_tuff.fall
+ minecraft:block.polished_tuff.hit
+ minecraft:block.polished_tuff.place
+ minecraft:block.polished_tuff.step
+ minecraft:block.tuff_bricks.break
+ minecraft:block.tuff_bricks.fall
+ minecraft:block.tuff_bricks.hit
+ minecraft:block.tuff_bricks.place
+ minecraft:block.tuff_bricks.step
+ minecraft:entity.player.teleport
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>




<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>



<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>


<details>
<summary>
universal_tags/block_type.json
</summary>

```diff
+ minecraft:copper_bulb_block
- minecraft:glass
+ minecraft:transparent
+ minecraft:weathering_copper_bulb
+ minecraft:weathering_copper_door
+ minecraft:weathering_copper_grate
+ minecraft:weathering_copper_trap_door
```

</details>















<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:chiseled_copper
+ minecraft:chiseled_tuff
+ minecraft:chiseled_tuff_bricks
+ minecraft:copper_bulb
+ minecraft:copper_door
+ minecraft:copper_grate
+ minecraft:copper_trapdoor
+ minecraft:exposed_chiseled_copper
+ minecraft:exposed_copper_bulb
+ minecraft:exposed_copper_door
+ minecraft:exposed_copper_grate
+ minecraft:exposed_copper_trapdoor
+ minecraft:oxidized_chiseled_copper
+ minecraft:oxidized_copper_bulb
+ minecraft:oxidized_copper_door
+ minecraft:oxidized_copper_grate
+ minecraft:oxidized_copper_trapdoor
+ minecraft:polished_tuff
+ minecraft:polished_tuff_slab
+ minecraft:polished_tuff_stairs
+ minecraft:polished_tuff_wall
+ minecraft:tuff_brick_slab
+ minecraft:tuff_brick_stairs
+ minecraft:tuff_brick_wall
+ minecraft:tuff_bricks
+ minecraft:tuff_slab
+ minecraft:tuff_stairs
+ minecraft:tuff_wall
+ minecraft:waxed_chiseled_copper
+ minecraft:waxed_copper_bulb
+ minecraft:waxed_copper_door
+ minecraft:waxed_copper_grate
+ minecraft:waxed_copper_trapdoor
+ minecraft:waxed_exposed_chiseled_copper
+ minecraft:waxed_exposed_copper_bulb
+ minecraft:waxed_exposed_copper_door
+ minecraft:waxed_exposed_copper_grate
+ minecraft:waxed_exposed_copper_trapdoor
+ minecraft:waxed_oxidized_chiseled_copper
+ minecraft:waxed_oxidized_copper_bulb
+ minecraft:waxed_oxidized_copper_door
+ minecraft:waxed_oxidized_copper_grate
+ minecraft:waxed_oxidized_copper_trapdoor
+ minecraft:waxed_weathered_chiseled_copper
+ minecraft:waxed_weathered_copper_bulb
+ minecraft:waxed_weathered_copper_door
+ minecraft:waxed_weathered_copper_grate
+ minecraft:waxed_weathered_copper_trapdoor
+ minecraft:weathered_chiseled_copper
+ minecraft:weathered_copper_bulb
+ minecraft:weathered_copper_door
+ minecraft:weathered_copper_grate
+ minecraft:weathered_copper_trapdoor
```

</details>





















<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.copper_bulb.break
+ minecraft:block.copper_bulb.fall
+ minecraft:block.copper_bulb.hit
+ minecraft:block.copper_bulb.place
+ minecraft:block.copper_bulb.step
+ minecraft:block.copper_bulb.turn_off
+ minecraft:block.copper_bulb.turn_on
+ minecraft:block.copper_door.close
+ minecraft:block.copper_door.open
+ minecraft:block.copper_grate.break
+ minecraft:block.copper_grate.fall
+ minecraft:block.copper_grate.hit
+ minecraft:block.copper_grate.place
+ minecraft:block.copper_grate.step
+ minecraft:block.copper_trapdoor.close
+ minecraft:block.copper_trapdoor.open
+ minecraft:block.polished_tuff.break
+ minecraft:block.polished_tuff.fall
+ minecraft:block.polished_tuff.hit
+ minecraft:block.polished_tuff.place
+ minecraft:block.polished_tuff.step
+ minecraft:block.tuff_bricks.break
+ minecraft:block.tuff_bricks.fall
+ minecraft:block.tuff_bricks.hit
+ minecraft:block.tuff_bricks.place
+ minecraft:block.tuff_bricks.step
+ minecraft:entity.player.teleport
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ tick.json
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ chiseled_copper.json
+ chiseled_tuff_bricks.json
+ chiseled_tuff.json
+ copper_door.json
+ copper_trapdoor.json
+ exposed_chiseled_copper.json
+ exposed_copper_door.json
+ exposed_copper_trapdoor.json
+ oxidized_chiseled_copper.json
+ oxidized_copper_door.json
+ oxidized_copper_trapdoor.json
+ polished_tuff_slab.json
+ polished_tuff_stairs.json
+ polished_tuff_wall.json
+ polished_tuff.json
+ tuff_brick_slab.json
+ tuff_brick_stairs.json
+ tuff_brick_wall.json
+ tuff_bricks.json
+ tuff_slab.json
+ tuff_stairs.json
+ tuff_wall.json
+ waxed_chiseled_copper_from_honeycomb.json
+ waxed_chiseled_copper.json
+ waxed_copper_bulb_from_honeycomb.json
+ waxed_copper_door_from_honeycomb.json
+ waxed_copper_door.json
+ waxed_copper_grate_from_honeycomb.json
+ waxed_copper_trapdoor_from_honeycomb.json
+ waxed_copper_trapdoor.json
+ waxed_exposed_chiseled_copper_from_honeycomb.json
+ waxed_exposed_chiseled_copper.json
+ waxed_exposed_copper_bulb_from_honeycomb.json
+ waxed_exposed_copper_door_from_honeycomb.json
+ waxed_exposed_copper_door.json
+ waxed_exposed_copper_grate_from_honeycomb.json
+ waxed_exposed_copper_trapdoor_from_honeycomb.json
+ waxed_exposed_copper_trapdoor.json
+ waxed_oxidized_chiseled_copper_from_honeycomb.json
+ waxed_oxidized_chiseled_copper.json
+ waxed_oxidized_copper_bulb_from_honeycomb.json
+ waxed_oxidized_copper_door_from_honeycomb.json
+ waxed_oxidized_copper_door.json
+ waxed_oxidized_copper_grate_from_honeycomb.json
+ waxed_oxidized_copper_trapdoor_from_honeycomb.json
+ waxed_oxidized_copper_trapdoor.json
+ waxed_weathered_chiseled_copper_from_honeycomb.json
+ waxed_weathered_chiseled_copper.json
+ waxed_weathered_copper_bulb_from_honeycomb.json
+ waxed_weathered_copper_door_from_honeycomb.json
+ waxed_weathered_copper_door.json
+ waxed_weathered_copper_grate_from_honeycomb.json
+ waxed_weathered_copper_trapdoor_from_honeycomb.json
+ waxed_weathered_copper_trapdoor.json
+ weathered_chiseled_copper.json
+ weathered_copper_door.json
+ weathered_copper_trapdoor.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.chiseled_copper: Chiseled Copper
+ block.minecraft.chiseled_tuff_bricks: Chiseled Tuff Bricks
+ block.minecraft.chiseled_tuff: Chiseled Tuff
+ block.minecraft.copper_bulb: Copper Bulb
+ block.minecraft.copper_door: Copper Door
+ block.minecraft.copper_grate: Copper Grate
+ block.minecraft.copper_trapdoor: Copper Trapdoor
+ block.minecraft.exposed_chiseled_copper: Exposed Chiseled Copper
+ block.minecraft.exposed_copper_bulb: Exposed Copper Bulb
+ block.minecraft.exposed_copper_door: Exposed Copper Door
+ block.minecraft.exposed_copper_grate: Exposed Copper Grate
+ block.minecraft.exposed_copper_trapdoor: Exposed Copper Trapdoor
+ block.minecraft.oxidized_chiseled_copper: Oxidized Chiseled Copper
+ block.minecraft.oxidized_copper_bulb: Oxidized Copper Bulb
+ block.minecraft.oxidized_copper_door: Oxidized Copper Door
+ block.minecraft.oxidized_copper_grate: Oxidized Copper Grate
+ block.minecraft.oxidized_copper_trapdoor: Oxidized Copper Trapdoor
+ block.minecraft.polished_tuff_slab: Polished Tuff Slab
+ block.minecraft.polished_tuff_stairs: Polished Tuff Stairs
+ block.minecraft.polished_tuff_wall: Polished Tuff Wall
+ block.minecraft.polished_tuff: Polished Tuff
+ block.minecraft.tuff_brick_slab: Tuff Brick Slab
+ block.minecraft.tuff_brick_stairs: Tuff Brick Stairs
+ block.minecraft.tuff_brick_wall: Tuff Brick Wall
+ block.minecraft.tuff_bricks: Tuff Bricks
+ block.minecraft.tuff_slab: Tuff Slab
+ block.minecraft.tuff_stairs: Tuff Stairs
+ block.minecraft.tuff_wall: Tuff Wall
+ block.minecraft.waxed_chiseled_copper: Waxed Chiseled Copper
+ block.minecraft.waxed_copper_bulb: Waxed Copper Bulb
+ block.minecraft.waxed_copper_door: Waxed Copper Door
+ block.minecraft.waxed_copper_grate: Waxed Copper Grate
+ block.minecraft.waxed_copper_trapdoor: Waxed Copper Trapdoor
+ block.minecraft.waxed_exposed_chiseled_copper: Waxed Exposed Chiseled Copper
+ block.minecraft.waxed_exposed_copper_bulb: Waxed Exposed Copper Bulb
+ block.minecraft.waxed_exposed_copper_door: Waxed Exposed Copper Door
+ block.minecraft.waxed_exposed_copper_grate: Waxed Exposed Copper Grate
+ block.minecraft.waxed_exposed_copper_trapdoor: Waxed Exposed Copper Trapdoor
+ block.minecraft.waxed_oxidized_chiseled_copper: Waxed Oxidized Chiseled Copper
+ block.minecraft.waxed_oxidized_copper_bulb: Waxed Oxidized Copper Bulb
+ block.minecraft.waxed_oxidized_copper_door: Waxed Oxidized Copper Door
+ block.minecraft.waxed_oxidized_copper_grate: Waxed Oxidized Copper Grate
+ block.minecraft.waxed_oxidized_copper_trapdoor: Waxed Oxidized Copper Trapdoor
+ block.minecraft.waxed_weathered_chiseled_copper: Waxed Weathered Chiseled Copper
+ block.minecraft.waxed_weathered_copper_bulb: Waxed Weathered Copper Bulb
+ block.minecraft.waxed_weathered_copper_door: Waxed Weathered Copper Door
+ block.minecraft.waxed_weathered_copper_grate: Waxed Weathered Copper Grate
+ block.minecraft.waxed_weathered_copper_trapdoor: Waxed Weathered Copper Trapdoor
+ block.minecraft.weathered_chiseled_copper: Weathered Chiseled Copper
+ block.minecraft.weathered_copper_bulb: Weathered Copper Bulb
+ block.minecraft.weathered_copper_door: Weathered Copper Door
+ block.minecraft.weathered_copper_grate: Weathered Copper Grate
+ block.minecraft.weathered_copper_trapdoor: Weathered Copper Trapdoor
+ commands.tick.query.percentiles: Percentiles: P50: %sms P95: %sms P99: %sms, sample: %s
+ commands.tick.query.rate.running: Target tick rate: %s per second.
Average time per tick: %sms (Target: %sms)
+ commands.tick.query.rate.sprinting: Target tick rate: %s per second (ingored, reference only).
Average time per tick: %sms
+ commands.tick.rate.success: Set the target tick rate to %s per second
+ commands.tick.sprint.report: Sprint completed with %s ticks per second, or %s ms per tick
+ commands.tick.sprint.stop.fail: No tick sprint in progress
+ commands.tick.sprint.stop.success: A tick sprint interrupted
+ commands.tick.status.frozen: The game is frozen
+ commands.tick.status.running: The game runs normally
+ commands.tick.status.sprinting: The game is sprinting
+ commands.tick.step.fail: Unable to step the game - the game must be frozen first
+ commands.tick.step.stop.fail: No tick step in progress
+ commands.tick.step.stop.success: A tick step interrupted
+ commands.tick.step.success: Stepping %s tick(s)
+ jigsaw_block.placement_priority: Placement Priority:
+ jigsaw_block.placement_priority.tooltip: When this Jigsaw block connects to a piece, this is the order in which that piece is processed for connections in the wider structure.

Pieces will be processed in descending priority with insertion order breaking ties.
+ jigsaw_block.selection_priority: Selection Priority:
+ jigsaw_block.selection_priority.tooltip: When the parent piece is being processed for connections, this is the order in which this Jigsaw block attempts to connect to its target piece.

Jigsaws will be processed in descending priority with random ordering breaking ties.
+ subtitles.entity.player.teleport: Player teleports
+ telemetry_info.opt_in.description: I consent to sending optional telemetry data
+ telemetry.event.optional.disabled: %s (Optional) - Disabled
```

</details>
<details>
<summary>
Changes
</summary>

```
gamerule.commandModificationBlockLimit: Command Mmodification Bblock Llimit
mco.snapshot.description: Paired with "%s"
mco.snapshot.friendsRealm.upgrade: %s needs to upgrade their Realm before you can play from this Snapshotversion
mco.snapshot.paired: This Snapshot Realm is paired with "%s"
recover_world.message: The following issues occurred while trying to read world folder "%s".\nIt might be possible to restore the world from an older state or you can report this issue on the bug tracker.
recover_world.no_fallback: No state to recover from availiable
selectWorld.incompatible.description: This world can not be opened in this version.\nIt was last played in version %s.
selectWorld.incompatible.tooltip: This world can not be opened because it was created by an incompatible version.
subtitles.block.crafter.craft: Crafter crafteds
subtitles.block.crafter.fail: Crafter faileds crafting
telemetry_info.button.show_data: OpenView My Data
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/chiseled_tuff_bricks.json
+ minecraft/advancements/recipes/building_blocks/chiseled_tuff.json
+ minecraft/advancements/recipes/building_blocks/exposed_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/oxidized_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/polished_tuff_slab.json
+ minecraft/advancements/recipes/building_blocks/polished_tuff_stairs.json
+ minecraft/advancements/recipes/building_blocks/polished_tuff.json
+ minecraft/advancements/recipes/building_blocks/tuff_brick_slab.json
+ minecraft/advancements/recipes/building_blocks/tuff_brick_stairs.json
+ minecraft/advancements/recipes/building_blocks/tuff_bricks.json
+ minecraft/advancements/recipes/building_blocks/tuff_slab.json
+ minecraft/advancements/recipes/building_blocks/tuff_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_chiseled_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_bulb_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_door_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_grate_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_copper_trapdoor_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_chiseled_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_bulb_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_door_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_grate_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_trapdoor_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_chiseled_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_bulb_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_door_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_grate_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_trapdoor_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_chiseled_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_chiseled_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_bulb_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_door_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_grate_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_trapdoor_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/weathered_chiseled_copper.json
+ minecraft/advancements/recipes/decorations/polished_tuff_wall.json
+ minecraft/advancements/recipes/decorations/tuff_brick_wall.json
+ minecraft/advancements/recipes/decorations/tuff_wall.json
+ minecraft/advancements/recipes/redstone/copper_door.json
+ minecraft/advancements/recipes/redstone/copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/exposed_copper_door.json
+ minecraft/advancements/recipes/redstone/exposed_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/oxidized_copper_door.json
+ minecraft/advancements/recipes/redstone/oxidized_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/waxed_copper_door.json
+ minecraft/advancements/recipes/redstone/waxed_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/waxed_exposed_copper_door.json
+ minecraft/advancements/recipes/redstone/waxed_exposed_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/waxed_oxidized_copper_door.json
+ minecraft/advancements/recipes/redstone/waxed_oxidized_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/waxed_weathered_copper_door.json
+ minecraft/advancements/recipes/redstone/waxed_weathered_copper_trapdoor.json
+ minecraft/advancements/recipes/redstone/weathered_copper_door.json
+ minecraft/advancements/recipes/redstone/weathered_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/chiseled_copper_from_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/chiseled_tuff_bricks_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/chiseled_tuff_bricks_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/chiseled_tuff_bricks_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/chiseled_tuff_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/copper_grate_from_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/exposed_chiseled_copper_from_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/exposed_copper_grate_from_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/oxidized_chiseled_copper_from_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/oxidized_copper_grate_from_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/polished_tuff_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/polished_tuff_slab_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/polished_tuff_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/polished_tuff_stairs_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/polished_tuff_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_slab_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_slab_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_stairs_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_stairs_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_brick_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_bricks_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_bricks_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/tuff_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_chiseled_copper_from_waxed_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_copper_grate_from_waxed_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_exposed_chiseled_copper_from_waxed_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_grate_from_waxed_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_oxidized_chiseled_copper_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_grate_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_weathered_chiseled_copper_from_waxed_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_grate_from_waxed_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/waxed_weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/weathered_chiseled_copper_from_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/weathered_copper_grate_from_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/building_blocks/weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/polished_tuff_wall_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/polished_tuff_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/tuff_brick_wall_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/tuff_brick_wall_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/tuff_brick_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/decorations/tuff_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/waxed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/waxed_exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/waxed_oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/waxed_weathered_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/recipes/redstone/weathered_copper_bulb.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/chat.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/emote_command.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/msg_command_incoming.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/msg_command_outgoing.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/say_command.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/team_msg_command_incoming.json
- minecraft/datapacks/update_1_21/data/minecraft/chat_type/team_msg_command_outgoing.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/arrow.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/bad_respawn_point.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/cactus.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/cramming.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/dragon_breath.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/drown.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/dry_out.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/explosion.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/fall.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/falling_anvil.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/falling_block.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/falling_stalactite.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/fireball.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/fireworks.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/fly_into_wall.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/freeze.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/generic_kill.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/generic.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/hot_floor.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/in_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/in_wall.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/indirect_magic.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/lava.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/lightning_bolt.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/magic.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/mob_attack_no_aggro.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/mob_attack.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/mob_projectile.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/on_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/out_of_world.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/outside_border.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/player_attack.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/player_explosion.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/sonic_boom.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/stalagmite.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/starve.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/sting.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/sweet_berry_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/thorns.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/thrown.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/trident.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/unattributed_fireball.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/wither_skull.json
- minecraft/datapacks/update_1_21/data/minecraft/damage_type/wither.json
- minecraft/datapacks/update_1_21/data/minecraft/dimension_type/overworld_caves.json
- minecraft/datapacks/update_1_21/data/minecraft/dimension_type/overworld.json
- minecraft/datapacks/update_1_21/data/minecraft/dimension_type/the_end.json
- minecraft/datapacks/update_1_21/data/minecraft/dimension_type/the_nether.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/chiseled_tuff_bricks.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/chiseled_tuff.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/exposed_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/exposed_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/exposed_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/oxidized_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/oxidized_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/oxidized_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/polished_tuff_slab.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/polished_tuff_stairs.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/polished_tuff_wall.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/polished_tuff.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_brick_slab.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_brick_stairs.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_brick_wall.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_bricks.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_slab.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_stairs.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/tuff_wall.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_exposed_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_exposed_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_exposed_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_oxidized_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_oxidized_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_oxidized_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_weathered_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_weathered_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_weathered_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/waxed_weathered_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/weathered_chiseled_copper.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/weathered_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/weathered_copper_door.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/blocks/weathered_copper_trapdoor.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/chiseled_copper_from_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/chiseled_tuff_bricks_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/chiseled_tuff_bricks_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/chiseled_tuff_bricks_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/chiseled_tuff_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/copper_grate_from_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/exposed_chiseled_copper_from_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/exposed_copper_grate_from_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/oxidized_chiseled_copper_from_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/oxidized_copper_grate_from_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_slab_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_stairs_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_wall_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/polished_tuff_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_slab_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_slab_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_stairs_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_stairs_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_wall_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_wall_from_tuff_bricks_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_brick_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_bricks_from_polished_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_bricks_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_slab_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_stairs_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/tuff_wall_from_tuff_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_chiseled_copper_from_waxed_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_copper_grate_from_waxed_copper_block_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_exposed_chiseled_copper_from_waxed_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_exposed_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_exposed_copper_grate_from_waxed_exposed_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_exposed_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_oxidized_chiseled_copper_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_oxidized_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_oxidized_copper_grate_from_waxed_oxidized_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_oxidized_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_weathered_chiseled_copper_from_waxed_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_weathered_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_weathered_copper_grate_from_waxed_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/waxed_weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/weathered_chiseled_copper_from_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/weathered_copper_bulb.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/weathered_copper_grate_from_weathered_copper_stonecutting.json
+ minecraft/datapacks/update_1_21/data/minecraft/recipes/weathered_copper_grate.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/blocks/slabs.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/blocks/stairs.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/blocks/walls.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/blocks/wooden_doors.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/slabs.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/stairs.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/amethyst.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/copper.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/diamond.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/emerald.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/gold.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/iron.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/lapis.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/netherite.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/quartz.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_material/redstone.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/coast.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/dune.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/eye.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/host.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/raiser.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/rib.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/sentry.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/shaper.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/silence.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/snout.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/spire.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/tide.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/vex.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/ward.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/wayfinder.json
- minecraft/datapacks/update_1_21/data/minecraft/trim_pattern/wild.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/bamboo_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/basalt_deltas.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/beach.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/birch_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/cherry_grove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/cold_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/crimson_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/dark_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/deep_cold_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/deep_dark.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/deep_frozen_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/deep_lukewarm_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/deep_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/dripstone_caves.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/end_barrens.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/end_highlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/end_midlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/eroded_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/flower_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/frozen_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/frozen_peaks.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/frozen_river.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/grove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/ice_spikes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/jagged_peaks.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/lukewarm_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/lush_caves.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/mangrove_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/meadow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/mushroom_fields.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/nether_wastes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/old_growth_birch_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/old_growth_pine_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/old_growth_spruce_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/river.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/savanna_plateau.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/small_end_islands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/snowy_beach.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/snowy_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/snowy_slopes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/snowy_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/soul_sand_valley.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/sparse_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/stony_peaks.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/stony_shore.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/sunflower_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/the_end.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/the_void.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/warm_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/warped_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/windswept_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/windswept_gravelly_hills.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/windswept_hills.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/windswept_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/biome/wooded_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_carver/canyon.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_carver/cave_extra_underground.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_carver/cave.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_carver/nether_cave.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/acacia.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/amethyst_geode.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/azalea_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/bamboo_no_podzol.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/bamboo_some_podzol.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/bamboo_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/basalt_blobs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/basalt_pillar.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/birch_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/birch_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/birch_bees_005.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/birch_tall.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/birch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/blackstone_blobs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/blue_ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/bonus_chest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/cave_vine_in_moss.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/cave_vine.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/cherry_bees_005.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/cherry.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/chorus_plant.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/clay_pool_with_dripleaves.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/clay_with_dripleaves.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/crimson_forest_vegetation_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/crimson_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/crimson_fungus_planted.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/crimson_fungus.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/dark_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/dark_oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/delta.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/desert_well.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/disk_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/disk_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/disk_gravel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/disk_sand.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/dripleaf.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/dripstone_cluster.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/end_gateway_delayed.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/end_gateway_return.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/end_island.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/end_spike.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fancy_oak_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fancy_oak_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fancy_oak_bees_005.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fancy_oak_bees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fancy_oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_cherry.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_default.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_flower_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_meadow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_plain.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/flower_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/forest_flowers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/forest_rock.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fossil_coal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/fossil_diamonds.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/freeze_top_layer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/glow_lichen.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/glowstone_extra.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/huge_brown_mushroom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/huge_red_mushroom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ice_patch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ice_spike.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/iceberg_blue.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/iceberg_packed.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/jungle_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/jungle_tree_no_vine.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/jungle_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/kelp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/lake_lava.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/large_basalt_columns.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/large_dripstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/lush_caves_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mangrove_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mangrove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/meadow_trees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mega_jungle_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mega_pine.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mega_spruce.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/monster_room.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/moss_patch_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/moss_patch_ceiling.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/moss_patch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/moss_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/mushroom_island_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/nether_sprouts_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/nether_sprouts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/oak_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/oak_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/oak_bees_005.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_ancient_debris_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_ancient_debris_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_andesite.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_blackstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_coal_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_coal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_copper_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_copper_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_diamond_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_diamond_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_diamond_medium.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_diamond_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_diorite.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_dirt.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_emerald.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_gold_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_gold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_granite.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_gravel_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_gravel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_infested.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_iron_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_iron.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_lapis_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_lapis.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_magma.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_nether_gold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_quartz.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_redstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_soul_sand.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/ore_tuff.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_berry_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_brown_mushroom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_cactus.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_crimson_roots.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_dead_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_grass_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_large_fern.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_melon.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_pumpkin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_red_mushroom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_soul_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_sugar_cane.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_sunflower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_taiga_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_tall_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/patch_waterlily.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pile_hay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pile_ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pile_melon.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pile_pumpkin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pile_snow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pine.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/pointed_dripstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/rooted_azalea_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/sculk_vein.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/sea_pickle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/seagrass_mid.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/seagrass_short.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/seagrass_simple.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/seagrass_slightly_less_short.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/seagrass_tall.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/single_piece_of_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/small_basalt_columns.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spore_blossom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_lava_frozen.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_lava_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_lava_overworld.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_nether_closed.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_nether_open.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spring_water.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/spruce.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/super_birch_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/super_birch_bees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/swamp_oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/tall_mangrove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_birch_and_oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_flower_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_grove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_old_growth_pine_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_old_growth_spruce_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_sparse_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_water.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/trees_windswept_hills.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/twisting_vines_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/twisting_vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/underwater_magma.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/void_start_platform.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/warm_ocean_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/warped_forest_vegetation_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/warped_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/warped_fungus_planted.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/warped_fungus.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/configured_feature/weeping_vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/end/base_3d_noise.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/end/sloped_cheese.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/nether/base_3d_noise.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_amplified/depth.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_amplified/factor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_amplified/jaggedness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_amplified/offset.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_amplified/sloped_cheese.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/continents.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/depth.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/erosion.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/factor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/jaggedness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/offset.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld_large_biomes/sloped_cheese.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/base_3d_noise.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/entrances.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/noodle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/pillars.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d_thickness_modulator.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/spaghetti_2d.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/caves/spaghetti_roughness_function.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/continents.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/depth.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/erosion.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/factor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/jaggedness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/offset.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/ridges_folded.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/ridges.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/overworld/sloped_cheese.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/shift_x.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/shift_z.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/y.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/density_function/zero.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/bottomless_pit.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/classic_flat.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/overworld.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/redstone_ready.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/snowy_kingdom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/the_void.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/tunnelers_dream.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/flat_level_generator_preset/water_world.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/multi_noise_biome_source_parameter_list/nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/multi_noise_biome_source_parameter_list/overworld.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/amplified.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/caves.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/end.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/floating_islands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/large_biomes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise_settings/overworld.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/aquifer_barrier.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/aquifer_fluid_level_floodedness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/aquifer_fluid_level_spread.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/aquifer_lava.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/badlands_pillar_roof.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/badlands_pillar.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/badlands_surface.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/calcite.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/cave_cheese.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/cave_entrance.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/cave_layer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/clay_bands_offset.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/continentalness_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/continentalness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/erosion_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/erosion.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/gravel_layer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/gravel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/iceberg_pillar_roof.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/iceberg_pillar.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/iceberg_surface.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/jagged.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/nether_state_selector.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/nether_wart.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/netherrack.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/noodle_ridge_a.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/noodle_ridge_b.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/noodle_thickness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/noodle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/offset.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ore_gap.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ore_vein_a.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ore_vein_b.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ore_veininess.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/packed_ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/patch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/pillar_rareness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/pillar_thickness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/pillar.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/powder_snow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/ridge.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/soul_sand_layer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_2d_elevation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_2d_modulator.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_2d_thickness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_2d.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_3d_1.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_3d_2.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_3d_rarity.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_3d_thickness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_roughness_modulator.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/spaghetti_roughness.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/surface_secondary.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/surface_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/surface.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/temperature_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/temperature.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/vegetation_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/noise/vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/acacia_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/acacia.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/amethyst_geode.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/bamboo_light.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/bamboo_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/bamboo.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/basalt_blobs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/basalt_pillar.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/birch_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/birch_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/birch_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/birch_tall.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/blackstone_blobs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/blue_ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/brown_mushroom_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/brown_mushroom_normal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/brown_mushroom_old_growth.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/brown_mushroom_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/brown_mushroom_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/cave_vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/cherry_bees_005.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/cherry_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/chorus_plant.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/classic_vines_cave_feature.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/crimson_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/crimson_fungi.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/dark_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/dark_oak_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/delta.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/desert_well.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/disk_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/disk_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/disk_gravel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/disk_sand.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/dripstone_cluster.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/end_gateway_return.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/end_island_decorated.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/end_spike.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fancy_oak_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fancy_oak_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fancy_oak_bees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fancy_oak_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_cherry.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_default.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_flower_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_forest_flowers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_meadow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_plain.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/flower_warm.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/forest_flowers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/forest_rock.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fossil_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/fossil_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/freeze_top_layer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/glow_lichen.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/glowstone_extra.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/glowstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/grass_bonemeal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ice_patch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ice_spike.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/iceberg_blue.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/iceberg_packed.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/jungle_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/jungle_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/kelp_cold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/kelp_warm.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/lake_lava_surface.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/lake_lava_underground.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/large_basalt_columns.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/large_dripstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/lush_caves_ceiling_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/lush_caves_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/lush_caves_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/mangrove_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/mega_jungle_tree_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/mega_pine_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/mega_spruce_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/monster_room_deep.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/monster_room.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/mushroom_island_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/nether_sprouts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/oak_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/oak_bees_002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/oak_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_ancient_debris_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_andesite_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_andesite_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_blackstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_clay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_coal_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_coal_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_copper_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_copper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_debris_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diamond_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diamond_large.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diamond_medium.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diamond.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diorite_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_diorite_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_dirt.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_emerald.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gold_deltas.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gold_extra.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gold_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gold_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_granite_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_granite_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gravel_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_gravel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_infested.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_iron_middle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_iron_small.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_iron_upper.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_lapis_buried.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_lapis.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_magma.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_quartz_deltas.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_quartz_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_redstone_lower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_redstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_soul_sand.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/ore_tuff.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_berry_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_berry_common.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_berry_rare.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_cactus_decorated.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_cactus_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_cactus.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_crimson_roots.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_dead_bush_2.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_dead_bush_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_dead_bush.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_normal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_plain.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_taiga_2.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_grass_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_large_fern.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_melon_sparse.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_melon.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_pumpkin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_soul_fire.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_sugar_cane_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_sugar_cane_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_sugar_cane_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_sugar_cane.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_sunflower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_taiga_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_tall_grass_2.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_tall_grass.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/patch_waterlily.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pile_hay.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pile_ice.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pile_melon.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pile_pumpkin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pile_snow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pine_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pine_on_snow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pine.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/pointed_dripstone.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/red_mushroom_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/red_mushroom_normal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/red_mushroom_old_growth.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/red_mushroom_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/red_mushroom_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/rooted_azalea_tree.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/sculk_vein.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/sea_pickle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_cold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_deep_cold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_deep_warm.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_deep.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_normal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_river.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_simple.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/seagrass_warm.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/small_basalt_columns.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spore_blossom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_closed_double.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_closed.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_delta.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_lava_frozen.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_lava.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_open.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spring_water.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spruce_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spruce_on_snow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/spruce.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/super_birch_bees_0002.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/super_birch_bees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/tall_mangrove_checked.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_badlands.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_birch_and_oak.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_birch.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_cherry.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_flower_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_grove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_mangrove.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_meadow.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_old_growth_pine_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_old_growth_spruce_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_snowy.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_sparse_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_water.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_windswept_forest.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_windswept_hills.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/trees_windswept_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/twisting_vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/underwater_magma.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/void_start_platform.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/warm_ocean_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/warped_forest_vegetation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/warped_fungi.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/placed_feature/weeping_vines.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/ancient_city_start_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/bastion_generic_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/bottom_rampart.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/bridge.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/empty.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/entrance_replacement.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/farm_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/farm_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/farm_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/farm_snowy.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/farm_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/fossil_coal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/fossil_diamonds.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/fossil_rot.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/high_rampart.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/high_wall.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/housing.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/mossify_10_percent.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/mossify_20_percent.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/mossify_70_percent.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/outpost_rot.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/rampart_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/roof.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/side_wall_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/stable_degradation.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/street_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/street_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/street_snowy_or_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/trail_ruins_houses_archaeology.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/trail_ruins_roads_archaeology.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/trail_ruins_tower_top_archaeology.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/treasure_rooms.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/zombie_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/zombie_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/zombie_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/zombie_snowy.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/processor_list/zombie_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/ancient_cities.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/buried_treasures.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/desert_pyramids.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/end_cities.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/igloos.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/jungle_temples.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/mineshafts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/nether_complexes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/nether_fossils.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/ocean_monuments.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/ocean_ruins.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/pillager_outposts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/ruined_portals.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/shipwrecks.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/strongholds.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/swamp_huts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/trail_ruins.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/villages.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure_set/woodland_mansions.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ancient_city.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/bastion_remnant.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/buried_treasure.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/desert_pyramid.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/end_city.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/fortress.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/igloo.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/jungle_pyramid.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/mansion.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/mineshaft_mesa.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/mineshaft.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/monument.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/nether_fossil.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ocean_ruin_cold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ocean_ruin_warm.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/pillager_outpost.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_jungle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_mountain.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_nether.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_ocean.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal_swamp.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/ruined_portal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/shipwreck_beached.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/shipwreck.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/stronghold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/swamp_hut.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/trail_ruins.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/village_desert.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/village_plains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/village_savanna.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/village_snowy.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/structure/village_taiga.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/city_center.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/city/entrance.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/sculk.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/structures.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/blocks/gold.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/bridge_pieces.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/connectors.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/legs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/rampart_plates.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/ramparts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/starting_pieces.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/bridge/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/connectors.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/inner.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/large_stables/outer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/mirrored_starting_pieces.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/posts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/rampart_plates.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/ramparts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/inner.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/small_stables/outer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/stairs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/starting_pieces.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/wall_bases.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/hoglin_stable/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/mobs/hoglin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/mobs/piglin_melee.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/mobs/piglin.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/starts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/bases.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/bases/centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/brains.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/connectors.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/corners/bottom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/corners/edges.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/corners/middle.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/corners/top.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/entrances.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/extensions/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/extensions/large_pool.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/extensions/small_pool.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/ramparts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/roofs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/stairs.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/walls.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/walls/bottom.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/walls/mid.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/walls/outer.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/treasure/walls/top.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/center_pieces.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/edge_wall_units.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/edges.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/fillers/stage_0.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/large_ramparts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/pathways.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/rampart_plates.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/ramparts.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/stages/rot/stage_1.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/stages/stage_0.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/stages/stage_1.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/stages/stage_2.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/stages/stage_3.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/wall_units.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/bastion/units/walls/wall_bases.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/empty.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/pillager_outpost/base_plates.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/pillager_outpost/feature_plates.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/pillager_outpost/features.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/pillager_outpost/towers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/buildings.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/buildings/grouped.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/roads.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/tower.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/tower/additions.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trail_ruins/tower/tower_top.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/animals.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/butcher_animals.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/cats.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/iron_golem.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/sheep.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/common/well_bottoms.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/camel.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/town_centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/zombie/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/zombie/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/zombie/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/zombie/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/desert/zombie/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/town_centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/trees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/zombie/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/zombie/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/zombie/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/plains/zombie/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/town_centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/trees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/zombie/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/zombie/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/zombie/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/zombie/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/savanna/zombie/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/town_centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/trees.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/zombie/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/zombie/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/zombie/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/snowy/zombie/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/terminators.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/town_centers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/zombie/decor.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/zombie/houses.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/zombie/streets.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/village/taiga/zombie/villagers.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/amplified.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/debug_all_block_states.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/flat.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/large_biomes.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/normal.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/world_preset/single_biome_surface.json
+ minecraft/loot_tables/blocks/chiseled_copper.json
+ minecraft/loot_tables/blocks/chiseled_tuff_bricks.json
+ minecraft/loot_tables/blocks/chiseled_tuff.json
+ minecraft/loot_tables/blocks/copper_bulb.json
+ minecraft/loot_tables/blocks/copper_door.json
+ minecraft/loot_tables/blocks/copper_grate.json
+ minecraft/loot_tables/blocks/copper_trapdoor.json
+ minecraft/loot_tables/blocks/exposed_chiseled_copper.json
+ minecraft/loot_tables/blocks/exposed_copper_bulb.json
+ minecraft/loot_tables/blocks/exposed_copper_door.json
+ minecraft/loot_tables/blocks/exposed_copper_grate.json
+ minecraft/loot_tables/blocks/exposed_copper_trapdoor.json
+ minecraft/loot_tables/blocks/oxidized_chiseled_copper.json
+ minecraft/loot_tables/blocks/oxidized_copper_bulb.json
+ minecraft/loot_tables/blocks/oxidized_copper_door.json
+ minecraft/loot_tables/blocks/oxidized_copper_grate.json
+ minecraft/loot_tables/blocks/oxidized_copper_trapdoor.json
+ minecraft/loot_tables/blocks/polished_tuff_slab.json
+ minecraft/loot_tables/blocks/polished_tuff_stairs.json
+ minecraft/loot_tables/blocks/polished_tuff_wall.json
+ minecraft/loot_tables/blocks/polished_tuff.json
+ minecraft/loot_tables/blocks/tuff_brick_slab.json
+ minecraft/loot_tables/blocks/tuff_brick_stairs.json
+ minecraft/loot_tables/blocks/tuff_brick_wall.json
+ minecraft/loot_tables/blocks/tuff_bricks.json
+ minecraft/loot_tables/blocks/tuff_slab.json
+ minecraft/loot_tables/blocks/tuff_stairs.json
+ minecraft/loot_tables/blocks/tuff_wall.json
+ minecraft/loot_tables/blocks/waxed_chiseled_copper.json
+ minecraft/loot_tables/blocks/waxed_copper_bulb.json
+ minecraft/loot_tables/blocks/waxed_copper_door.json
+ minecraft/loot_tables/blocks/waxed_copper_grate.json
+ minecraft/loot_tables/blocks/waxed_copper_trapdoor.json
+ minecraft/loot_tables/blocks/waxed_exposed_chiseled_copper.json
+ minecraft/loot_tables/blocks/waxed_exposed_copper_bulb.json
+ minecraft/loot_tables/blocks/waxed_exposed_copper_door.json
+ minecraft/loot_tables/blocks/waxed_exposed_copper_grate.json
+ minecraft/loot_tables/blocks/waxed_exposed_copper_trapdoor.json
+ minecraft/loot_tables/blocks/waxed_oxidized_chiseled_copper.json
+ minecraft/loot_tables/blocks/waxed_oxidized_copper_bulb.json
+ minecraft/loot_tables/blocks/waxed_oxidized_copper_door.json
+ minecraft/loot_tables/blocks/waxed_oxidized_copper_grate.json
+ minecraft/loot_tables/blocks/waxed_oxidized_copper_trapdoor.json
+ minecraft/loot_tables/blocks/waxed_weathered_chiseled_copper.json
+ minecraft/loot_tables/blocks/waxed_weathered_copper_bulb.json
+ minecraft/loot_tables/blocks/waxed_weathered_copper_door.json
+ minecraft/loot_tables/blocks/waxed_weathered_copper_grate.json
+ minecraft/loot_tables/blocks/waxed_weathered_copper_trapdoor.json
+ minecraft/loot_tables/blocks/weathered_chiseled_copper.json
+ minecraft/loot_tables/blocks/weathered_copper_bulb.json
+ minecraft/loot_tables/blocks/weathered_copper_door.json
+ minecraft/loot_tables/blocks/weathered_copper_grate.json
+ minecraft/loot_tables/blocks/weathered_copper_trapdoor.json
+ minecraft/recipes/chiseled_copper.json
+ minecraft/recipes/chiseled_tuff_bricks.json
+ minecraft/recipes/chiseled_tuff.json
+ minecraft/recipes/copper_door.json
+ minecraft/recipes/copper_trapdoor.json
+ minecraft/recipes/exposed_chiseled_copper.json
+ minecraft/recipes/exposed_copper_door.json
+ minecraft/recipes/exposed_copper_trapdoor.json
+ minecraft/recipes/oxidized_chiseled_copper.json
+ minecraft/recipes/oxidized_copper_door.json
+ minecraft/recipes/oxidized_copper_trapdoor.json
+ minecraft/recipes/polished_tuff_slab.json
+ minecraft/recipes/polished_tuff_stairs.json
+ minecraft/recipes/polished_tuff_wall.json
+ minecraft/recipes/polished_tuff.json
+ minecraft/recipes/tuff_brick_slab.json
+ minecraft/recipes/tuff_brick_stairs.json
+ minecraft/recipes/tuff_brick_wall.json
+ minecraft/recipes/tuff_bricks.json
+ minecraft/recipes/tuff_slab.json
+ minecraft/recipes/tuff_stairs.json
+ minecraft/recipes/tuff_wall.json
+ minecraft/recipes/waxed_chiseled_copper_from_honeycomb.json
+ minecraft/recipes/waxed_chiseled_copper.json
+ minecraft/recipes/waxed_copper_bulb_from_honeycomb.json
+ minecraft/recipes/waxed_copper_door_from_honeycomb.json
+ minecraft/recipes/waxed_copper_door.json
+ minecraft/recipes/waxed_copper_grate_from_honeycomb.json
+ minecraft/recipes/waxed_copper_trapdoor_from_honeycomb.json
+ minecraft/recipes/waxed_copper_trapdoor.json
+ minecraft/recipes/waxed_exposed_chiseled_copper_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_chiseled_copper.json
+ minecraft/recipes/waxed_exposed_copper_bulb_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_copper_door_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_copper_door.json
+ minecraft/recipes/waxed_exposed_copper_grate_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_copper_trapdoor_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_copper_trapdoor.json
+ minecraft/recipes/waxed_oxidized_chiseled_copper_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_chiseled_copper.json
+ minecraft/recipes/waxed_oxidized_copper_bulb_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_copper_door_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_copper_door.json
+ minecraft/recipes/waxed_oxidized_copper_grate_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_copper_trapdoor_from_honeycomb.json
+ minecraft/recipes/waxed_oxidized_copper_trapdoor.json
+ minecraft/recipes/waxed_weathered_chiseled_copper_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_chiseled_copper.json
+ minecraft/recipes/waxed_weathered_copper_bulb_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_copper_door_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_copper_door.json
+ minecraft/recipes/waxed_weathered_copper_grate_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_copper_trapdoor_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_copper_trapdoor.json
+ minecraft/recipes/weathered_chiseled_copper.json
+ minecraft/recipes/weathered_copper_door.json
+ minecraft/recipes/weathered_copper_trapdoor.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/chiseled_copper.json
+ minecraft/blockstates/chiseled_tuff_bricks.json
+ minecraft/blockstates/chiseled_tuff.json
+ minecraft/blockstates/copper_bulb.json
+ minecraft/blockstates/copper_door.json
+ minecraft/blockstates/copper_grate.json
+ minecraft/blockstates/copper_trapdoor.json
+ minecraft/blockstates/exposed_chiseled_copper.json
+ minecraft/blockstates/exposed_copper_bulb.json
+ minecraft/blockstates/exposed_copper_door.json
+ minecraft/blockstates/exposed_copper_grate.json
+ minecraft/blockstates/exposed_copper_trapdoor.json
+ minecraft/blockstates/oxidized_chiseled_copper.json
+ minecraft/blockstates/oxidized_copper_bulb.json
+ minecraft/blockstates/oxidized_copper_door.json
+ minecraft/blockstates/oxidized_copper_grate.json
+ minecraft/blockstates/oxidized_copper_trapdoor.json
+ minecraft/blockstates/polished_tuff_slab.json
+ minecraft/blockstates/polished_tuff_stairs.json
+ minecraft/blockstates/polished_tuff_wall.json
+ minecraft/blockstates/polished_tuff.json
+ minecraft/blockstates/tuff_brick_slab.json
+ minecraft/blockstates/tuff_brick_stairs.json
+ minecraft/blockstates/tuff_brick_wall.json
+ minecraft/blockstates/tuff_bricks.json
+ minecraft/blockstates/tuff_slab.json
+ minecraft/blockstates/tuff_stairs.json
+ minecraft/blockstates/tuff_wall.json
+ minecraft/blockstates/waxed_chiseled_copper.json
+ minecraft/blockstates/waxed_copper_bulb.json
+ minecraft/blockstates/waxed_copper_door.json
+ minecraft/blockstates/waxed_copper_grate.json
+ minecraft/blockstates/waxed_copper_trapdoor.json
+ minecraft/blockstates/waxed_exposed_chiseled_copper.json
+ minecraft/blockstates/waxed_exposed_copper_bulb.json
+ minecraft/blockstates/waxed_exposed_copper_door.json
+ minecraft/blockstates/waxed_exposed_copper_grate.json
+ minecraft/blockstates/waxed_exposed_copper_trapdoor.json
+ minecraft/blockstates/waxed_oxidized_chiseled_copper.json
+ minecraft/blockstates/waxed_oxidized_copper_bulb.json
+ minecraft/blockstates/waxed_oxidized_copper_door.json
+ minecraft/blockstates/waxed_oxidized_copper_grate.json
+ minecraft/blockstates/waxed_oxidized_copper_trapdoor.json
+ minecraft/blockstates/waxed_weathered_chiseled_copper.json
+ minecraft/blockstates/waxed_weathered_copper_bulb.json
+ minecraft/blockstates/waxed_weathered_copper_door.json
+ minecraft/blockstates/waxed_weathered_copper_grate.json
+ minecraft/blockstates/waxed_weathered_copper_trapdoor.json
+ minecraft/blockstates/weathered_chiseled_copper.json
+ minecraft/blockstates/weathered_copper_bulb.json
+ minecraft/blockstates/weathered_copper_door.json
+ minecraft/blockstates/weathered_copper_grate.json
+ minecraft/blockstates/weathered_copper_trapdoor.json
+ minecraft/models/block/chiseled_copper.json
+ minecraft/models/block/chiseled_tuff_bricks.json
+ minecraft/models/block/chiseled_tuff.json
+ minecraft/models/block/copper_bulb_lit_powered.json
+ minecraft/models/block/copper_bulb_lit.json
+ minecraft/models/block/copper_bulb_powered.json
+ minecraft/models/block/copper_bulb.json
+ minecraft/models/block/copper_door_bottom_left_open.json
+ minecraft/models/block/copper_door_bottom_left.json
+ minecraft/models/block/copper_door_bottom_right_open.json
+ minecraft/models/block/copper_door_bottom_right.json
+ minecraft/models/block/copper_door_top_left_open.json
+ minecraft/models/block/copper_door_top_left.json
+ minecraft/models/block/copper_door_top_right_open.json
+ minecraft/models/block/copper_door_top_right.json
+ minecraft/models/block/copper_grate.json
+ minecraft/models/block/copper_trapdoor_bottom.json
+ minecraft/models/block/copper_trapdoor_open.json
+ minecraft/models/block/copper_trapdoor_top.json
+ minecraft/models/block/exposed_chiseled_copper.json
+ minecraft/models/block/exposed_copper_bulb_lit_powered.json
+ minecraft/models/block/exposed_copper_bulb_lit.json
+ minecraft/models/block/exposed_copper_bulb_powered.json
+ minecraft/models/block/exposed_copper_bulb.json
+ minecraft/models/block/exposed_copper_door_bottom_left_open.json
+ minecraft/models/block/exposed_copper_door_bottom_left.json
+ minecraft/models/block/exposed_copper_door_bottom_right_open.json
+ minecraft/models/block/exposed_copper_door_bottom_right.json
+ minecraft/models/block/exposed_copper_door_top_left_open.json
+ minecraft/models/block/exposed_copper_door_top_left.json
+ minecraft/models/block/exposed_copper_door_top_right_open.json
+ minecraft/models/block/exposed_copper_door_top_right.json
+ minecraft/models/block/exposed_copper_grate.json
+ minecraft/models/block/exposed_copper_trapdoor_bottom.json
+ minecraft/models/block/exposed_copper_trapdoor_open.json
+ minecraft/models/block/exposed_copper_trapdoor_top.json
+ minecraft/models/block/oxidized_chiseled_copper.json
+ minecraft/models/block/oxidized_copper_bulb_lit_powered.json
+ minecraft/models/block/oxidized_copper_bulb_lit.json
+ minecraft/models/block/oxidized_copper_bulb_powered.json
+ minecraft/models/block/oxidized_copper_bulb.json
+ minecraft/models/block/oxidized_copper_door_bottom_left_open.json
+ minecraft/models/block/oxidized_copper_door_bottom_left.json
+ minecraft/models/block/oxidized_copper_door_bottom_right_open.json
+ minecraft/models/block/oxidized_copper_door_bottom_right.json
+ minecraft/models/block/oxidized_copper_door_top_left_open.json
+ minecraft/models/block/oxidized_copper_door_top_left.json
+ minecraft/models/block/oxidized_copper_door_top_right_open.json
+ minecraft/models/block/oxidized_copper_door_top_right.json
+ minecraft/models/block/oxidized_copper_grate.json
+ minecraft/models/block/oxidized_copper_trapdoor_bottom.json
+ minecraft/models/block/oxidized_copper_trapdoor_open.json
+ minecraft/models/block/oxidized_copper_trapdoor_top.json
+ minecraft/models/block/polished_tuff_slab_top.json
+ minecraft/models/block/polished_tuff_slab.json
+ minecraft/models/block/polished_tuff_stairs_inner.json
+ minecraft/models/block/polished_tuff_stairs_outer.json
+ minecraft/models/block/polished_tuff_stairs.json
+ minecraft/models/block/polished_tuff_wall_inventory.json
+ minecraft/models/block/polished_tuff_wall_post.json
+ minecraft/models/block/polished_tuff_wall_side_tall.json
+ minecraft/models/block/polished_tuff_wall_side.json
+ minecraft/models/block/polished_tuff.json
+ minecraft/models/block/tuff_brick_slab_top.json
+ minecraft/models/block/tuff_brick_slab.json
+ minecraft/models/block/tuff_brick_stairs_inner.json
+ minecraft/models/block/tuff_brick_stairs_outer.json
+ minecraft/models/block/tuff_brick_stairs.json
+ minecraft/models/block/tuff_brick_wall_inventory.json
+ minecraft/models/block/tuff_brick_wall_post.json
+ minecraft/models/block/tuff_brick_wall_side_tall.json
+ minecraft/models/block/tuff_brick_wall_side.json
+ minecraft/models/block/tuff_bricks.json
+ minecraft/models/block/tuff_slab_top.json
+ minecraft/models/block/tuff_slab.json
+ minecraft/models/block/tuff_stairs_inner.json
+ minecraft/models/block/tuff_stairs_outer.json
+ minecraft/models/block/tuff_stairs.json
+ minecraft/models/block/tuff_wall_inventory.json
+ minecraft/models/block/tuff_wall_post.json
+ minecraft/models/block/tuff_wall_side_tall.json
+ minecraft/models/block/tuff_wall_side.json
+ minecraft/models/block/weathered_chiseled_copper.json
+ minecraft/models/block/weathered_copper_bulb_lit_powered.json
+ minecraft/models/block/weathered_copper_bulb_lit.json
+ minecraft/models/block/weathered_copper_bulb_powered.json
+ minecraft/models/block/weathered_copper_bulb.json
+ minecraft/models/block/weathered_copper_door_bottom_left_open.json
+ minecraft/models/block/weathered_copper_door_bottom_left.json
+ minecraft/models/block/weathered_copper_door_bottom_right_open.json
+ minecraft/models/block/weathered_copper_door_bottom_right.json
+ minecraft/models/block/weathered_copper_door_top_left_open.json
+ minecraft/models/block/weathered_copper_door_top_left.json
+ minecraft/models/block/weathered_copper_door_top_right_open.json
+ minecraft/models/block/weathered_copper_door_top_right.json
+ minecraft/models/block/weathered_copper_grate.json
+ minecraft/models/block/weathered_copper_trapdoor_bottom.json
+ minecraft/models/block/weathered_copper_trapdoor_open.json
+ minecraft/models/block/weathered_copper_trapdoor_top.json
+ minecraft/models/item/chiseled_copper.json
+ minecraft/models/item/chiseled_tuff_bricks.json
+ minecraft/models/item/chiseled_tuff.json
+ minecraft/models/item/copper_bulb.json
+ minecraft/models/item/copper_door.json
+ minecraft/models/item/copper_grate.json
+ minecraft/models/item/copper_trapdoor.json
+ minecraft/models/item/exposed_chiseled_copper.json
+ minecraft/models/item/exposed_copper_bulb.json
+ minecraft/models/item/exposed_copper_door.json
+ minecraft/models/item/exposed_copper_grate.json
+ minecraft/models/item/exposed_copper_trapdoor.json
+ minecraft/models/item/oxidized_chiseled_copper.json
+ minecraft/models/item/oxidized_copper_bulb.json
+ minecraft/models/item/oxidized_copper_door.json
+ minecraft/models/item/oxidized_copper_grate.json
+ minecraft/models/item/oxidized_copper_trapdoor.json
+ minecraft/models/item/polished_tuff_slab.json
+ minecraft/models/item/polished_tuff_stairs.json
+ minecraft/models/item/polished_tuff_wall.json
+ minecraft/models/item/polished_tuff.json
+ minecraft/models/item/tuff_brick_slab.json
+ minecraft/models/item/tuff_brick_stairs.json
+ minecraft/models/item/tuff_brick_wall.json
+ minecraft/models/item/tuff_bricks.json
+ minecraft/models/item/tuff_slab.json
+ minecraft/models/item/tuff_stairs.json
+ minecraft/models/item/tuff_wall.json
+ minecraft/models/item/waxed_chiseled_copper.json
+ minecraft/models/item/waxed_copper_bulb.json
+ minecraft/models/item/waxed_copper_door.json
+ minecraft/models/item/waxed_copper_grate.json
+ minecraft/models/item/waxed_copper_trapdoor.json
+ minecraft/models/item/waxed_exposed_chiseled_copper.json
+ minecraft/models/item/waxed_exposed_copper_bulb.json
+ minecraft/models/item/waxed_exposed_copper_door.json
+ minecraft/models/item/waxed_exposed_copper_grate.json
+ minecraft/models/item/waxed_exposed_copper_trapdoor.json
+ minecraft/models/item/waxed_oxidized_chiseled_copper.json
+ minecraft/models/item/waxed_oxidized_copper_bulb.json
+ minecraft/models/item/waxed_oxidized_copper_door.json
+ minecraft/models/item/waxed_oxidized_copper_grate.json
+ minecraft/models/item/waxed_oxidized_copper_trapdoor.json
+ minecraft/models/item/waxed_weathered_chiseled_copper.json
+ minecraft/models/item/waxed_weathered_copper_bulb.json
+ minecraft/models/item/waxed_weathered_copper_door.json
+ minecraft/models/item/waxed_weathered_copper_grate.json
+ minecraft/models/item/waxed_weathered_copper_trapdoor.json
+ minecraft/models/item/weathered_chiseled_copper.json
+ minecraft/models/item/weathered_copper_bulb.json
+ minecraft/models/item/weathered_copper_door.json
+ minecraft/models/item/weathered_copper_grate.json
+ minecraft/models/item/weathered_copper_trapdoor.json
+ minecraft/textures/block/chiseled_copper.png
+ minecraft/textures/block/chiseled_tuff_bricks_top.png
+ minecraft/textures/block/chiseled_tuff_bricks.png
+ minecraft/textures/block/chiseled_tuff_top.png
+ minecraft/textures/block/chiseled_tuff.png
+ minecraft/textures/block/copper_bulb_lit_powered.png
+ minecraft/textures/block/copper_bulb_lit.png
+ minecraft/textures/block/copper_bulb_powered.png
+ minecraft/textures/block/copper_bulb.png
+ minecraft/textures/block/copper_door_bottom.png
+ minecraft/textures/block/copper_door_top.png
+ minecraft/textures/block/copper_grate.png
+ minecraft/textures/block/copper_trapdoor.png
+ minecraft/textures/block/exposed_chiseled_copper.png
+ minecraft/textures/block/exposed_copper_bulb_lit_powered.png
+ minecraft/textures/block/exposed_copper_bulb_lit.png
+ minecraft/textures/block/exposed_copper_bulb_powered.png
+ minecraft/textures/block/exposed_copper_bulb.png
+ minecraft/textures/block/exposed_copper_door_bottom.png
+ minecraft/textures/block/exposed_copper_door_top.png
+ minecraft/textures/block/exposed_copper_grate.png
+ minecraft/textures/block/exposed_copper_trapdoor.png
+ minecraft/textures/block/oxidized_chiseled_copper.png
+ minecraft/textures/block/oxidized_copper_bulb_lit_powered.png
+ minecraft/textures/block/oxidized_copper_bulb_lit.png
+ minecraft/textures/block/oxidized_copper_bulb_powered.png
+ minecraft/textures/block/oxidized_copper_bulb.png
+ minecraft/textures/block/oxidized_copper_door_bottom.png
+ minecraft/textures/block/oxidized_copper_door_top.png
+ minecraft/textures/block/oxidized_copper_grate.png
+ minecraft/textures/block/oxidized_copper_trapdoor.png
+ minecraft/textures/block/polished_tuff.png
+ minecraft/textures/block/tuff_bricks.png
+ minecraft/textures/block/weathered_chiseled_copper.png
+ minecraft/textures/block/weathered_copper_bulb_lit_powered.png
+ minecraft/textures/block/weathered_copper_bulb_lit.png
+ minecraft/textures/block/weathered_copper_bulb_powered.png
+ minecraft/textures/block/weathered_copper_bulb.png
+ minecraft/textures/block/weathered_copper_door_bottom.png
+ minecraft/textures/block/weathered_copper_door_top.png
+ minecraft/textures/block/weathered_copper_grate.png
+ minecraft/textures/block/weathered_copper_trapdoor.png
+ minecraft/textures/item/copper_door.png
+ minecraft/textures/item/exposed_copper_door.png
+ minecraft/textures/item/oxidized_copper_door.png
+ minecraft/textures/item/weathered_copper_door.png
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
- net.minecraft.data.registries.package-info
- net.minecraft.data.registries.UpdateOneTwentyOneRegistries
+ net.minecraft.data.registries.VanillaRegistries
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtDatafixer
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BannerPatternTagsProvider
- net.minecraft.data.tags.BiomeTagsProvider
+ net.minecraft.data.tags.CatVariantTagsProvider
- net.minecraft.data.tags.DamageTypeTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.InstrumentTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.PaintingVariantTagsProvider
- net.minecraft.data.tags.PoiTypeTagsProvider
+ net.minecraft.data.tags.StructureTagsProvider
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$1CombinedData
- net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.tags.TagsProvider$TagLookup
- net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneBlockTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneItemTagsProvider
+ net.minecraft.data.tags.VanillaBlockTagsProvider
- net.minecraft.data.tags.VanillaItemTagsProvider
+ net.minecraft.data.tags.WorldPresetTagsProvider
+ net.minecraft.data.worldgen.AncientCityStructurePieces
- net.minecraft.data.worldgen.AncientCityStructurePools
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.biome.BiomeData
+ net.minecraft.data.worldgen.biome.EndBiomes
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.BootstapContext
+ net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.DesertVillagePools
+ net.minecraft.data.worldgen.DimensionTypes
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
- net.minecraft.data.worldgen.NoiseData
- net.minecraft.data.worldgen.package-info
+ net.minecraft.data.worldgen.PillagerOutpostPools
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
- net.minecraft.data.worldgen.PlainVillagePools
+ net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.ProcessorLists
+ net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.Structures
+ net.minecraft.data.worldgen.StructureSets
+ net.minecraft.data.worldgen.SurfaceRuleData
- net.minecraft.data.worldgen.TaigaVillagePools
+ net.minecraft.data.worldgen.TerrainProvider
- net.minecraft.data.worldgen.TrailRuinsStructurePools
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
+ net.minecraft.gametest.framework.GameTestHelper$2
- net.minecraft.gametest.framework.GameTestHelper$3
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
- net.minecraft.gametest.framework.ReportGameListener
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.StructureUtils$1
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.network.protocol.game.ClientboundTickingStatePacket
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$CommandFunction
+ net.minecraft.server.commands.CloneCommands$DimensionAndPosition
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugConfigCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandGetter
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$2
+ net.minecraft.server.commands.FunctionCommand$3
- net.minecraft.server.commands.FunctionCommand$4
+ net.minecraft.server.commands.FunctionCommand$5
- net.minecraft.server.commands.FunctionCommand$Callbacks
+ net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PerfCommand
+ net.minecraft.server.commands.PlaceCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RandomCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
+ net.minecraft.server.commands.ReturnCommand
- net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.util.datafix.ComponentDataFixUtils
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.DataFixTypes$1
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractPoiSectionFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlendingDataFix
- net.minecraft.util.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityRenameFix
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
+ net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- net.minecraft.util.datafix.fixes.ChunkDeleteLightFix
+ net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ net.minecraft.util.datafix.fixes.ChunkRenamesFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.CriteriaRenameFix
- net.minecraft.util.datafix.fixes.DecoratedPotFieldRenameFix
+ net.minecraft.util.datafix.fixes.DropInvalidSignDataFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EffectDurationFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityVariantFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.FeatureFlagRemoveFix
+ net.minecraft.util.datafix.fixes.FilteredBooksFix
- net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.FixProjectileStoredItem$SubFixer
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GoatHornIdFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
+ net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
- net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemapChunkStatusFix
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VariantRenameFix
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.datafix.schemas.V2568
- net.minecraft.util.datafix.schemas.V2571
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
+ net.minecraft.util.datafix.schemas.V3325
- net.minecraft.util.datafix.schemas.V3326
+ net.minecraft.util.datafix.schemas.V3327
- net.minecraft.util.datafix.schemas.V3328
+ net.minecraft.util.datafix.schemas.V3438
- net.minecraft.util.datafix.schemas.V3448
+ net.minecraft.util.datafix.schemas.V3682
- net.minecraft.util.datafix.schemas.V3683
- net.minecraft.util.SignatureUpdater
+ net.minecraft.util.SignatureUpdater$Output
- net.minecraft.util.SignatureValidator
+ net.minecraft.util.Signer
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SingleKeyCache
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.SpawnUtil
+ net.minecraft.util.SpawnUtil$Strategy
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$EnumCodec
- net.minecraft.util.StringRepresentable$StringRepresentableCodec
+ net.minecraft.util.StringUtil
- net.minecraft.util.TaskChainer
+ net.minecraft.util.TaskChainer$1
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeSource
- net.minecraft.util.TimeSource$NanoTimeSource
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.ToFloatFunction$1
- net.minecraft.util.ToFloatFunction$2
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.ZeroBitStorage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.AttributeModifierTemplate
+ net.minecraft.world.effect.BadOmenMobEffect
- net.minecraft.world.effect.HealOrHarmMobEffect
+ net.minecraft.world.effect.HungerMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$MobEffectAttributeModifierTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$FactorData
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RegenerationMobEffect
- net.minecraft.world.effect.SaturationMobEffect
+ net.minecraft.world.effect.WitherMobEffect
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.BehaviorControl
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
+ net.minecraft.world.entity.ai.behavior.declarative.package-info
- net.minecraft.world.entity.ai.behavior.declarative.Trigger
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToTargetLocation
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.OneShot
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
+ net.minecraft.world.entity.ai.behavior.RandomLookAround
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TriggerGate
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.Allay
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.Allay$VibrationUser
+ net.minecraft.world.entity.animal.allay.AllayAi
- net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.camel.Camel
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.CatVariant
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
+ net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Llama$Variant
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Parrot$Variant
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Rabbit$Variant
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.sniffer.Sniffer
+ net.minecraft.world.entity.animal.sniffer.Sniffer$1
- net.minecraft.world.entity.animal.sniffer.Sniffer$State
+ net.minecraft.world.entity.animal.sniffer.SnifferAi
- net.minecraft.world.entity.animal.sniffer.SnifferAi$1
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$2
- net.minecraft.world.entity.animal.sniffer.SnifferAi$3
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Digging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$FeelingHappy
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$FinishedDigging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Scenting
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Searching
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Sniffing
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Base
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.TropicalFish$Variant
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
- net.minecraft.world.entity.Display
+ net.minecraft.world.entity.Display$1
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.Display$ItemDisplay$1
+ net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
- net.minecraft.world.entity.Display$LinearFloatInterpolator
+ net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$PosRotInterpolationTarget
+ net.minecraft.world.entity.Display$RenderState
- net.minecraft.world.entity.Display$TextDisplay
+ net.minecraft.world.entity.Display$TextDisplay$Align
- net.minecraft.world.entity.Display$TextDisplay$CachedInfo
+ net.minecraft.world.entity.Display$TextDisplay$CachedLine
- net.minecraft.world.entity.Display$TextDisplay$LineSplitter
+ net.minecraft.world.entity.Display$TextDisplay$TextRenderState
- net.minecraft.world.entity.Display$TransformationInterpolator
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
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.LivingEntity$Fallsounds
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
+ net.minecraft.world.entity.monster.Silverfish
- net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- net.minecraft.world.entity.monster.Skeleton
+ net.minecraft.world.entity.monster.Slime
- net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
+ net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
- net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ net.minecraft.world.entity.monster.Slime$SlimeMoveControl
- net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager
- net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ net.minecraft.world.entity.monster.Spider
- net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
+ net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
- net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
+ net.minecraft.world.entity.monster.Stray
- net.minecraft.world.entity.monster.Strider
+ net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
- net.minecraft.world.entity.monster.Strider$StriderPathNavigation
+ net.minecraft.world.entity.monster.Vex
- net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
+ net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
- net.minecraft.world.entity.monster.Vex$VexMoveControl
+ net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
- net.minecraft.world.entity.monster.Vindicator
+ net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.Warden$VibrationUser
- net.minecraft.world.entity.monster.warden.WardenAi
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.entity.vehicle.VehicleEntity
+ net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.flag.FeatureElement
+ net.minecraft.world.flag.FeatureFlag
- net.minecraft.world.flag.FeatureFlagRegistry
+ net.minecraft.world.flag.FeatureFlagRegistry$Builder
- net.minecraft.world.flag.FeatureFlags
- net.minecraft.world.flag.FeatureFlagSet
+ net.minecraft.world.flag.FeatureFlagUniverse
+ net.minecraft.world.flag.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CrafterMenu
+ net.minecraft.world.inventory.CrafterSlot
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu$3
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.NonInteractiveResultSlot
- net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeCraftingHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.inventory.TransientCraftingContainer
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.armortrim.ArmorTrim
+ net.minecraft.world.item.armortrim.package-info
+ net.minecraft.world.item.armortrim.TrimMaterial
- net.minecraft.world.item.armortrim.TrimMaterials
+ net.minecraft.world.item.armortrim.TrimPattern
- net.minecraft.world.item.armortrim.TrimPatterns
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingBookCategory
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CraftingRecipeCodecs
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.DecoratedPotRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeCache
- net.minecraft.world.item.crafting.RecipeCache$Entry
+ net.minecraft.world.item.crafting.RecipeHolder
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer$RawShapedRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmithingRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
+ net.minecraft.world.item.crafting.SmithingTrimRecipe
- net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$Builder
+ net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
- net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.CreativeModeTab$Output
+ net.minecraft.world.item.CreativeModeTab$Row
- net.minecraft.world.item.CreativeModeTab$TabVisibility
+ net.minecraft.world.item.CreativeModeTab$Type
- net.minecraft.world.item.CreativeModeTabs
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeableArmorItem
- net.minecraft.world.item.DyeableHorseArmorItem
+ net.minecraft.world.item.DyeableLeatherItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
- net.minecraft.world.item.EggItem
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.SwiftSneakEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.Equipable
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.GlowInkSacItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.InkSacItem
- net.minecraft.world.item.Instrument
+ net.minecraft.world.item.InstrumentItem
- net.minecraft.world.item.Instruments
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemDisplayContext
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemStackLinkedSet
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.package-info
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
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
+ net.minecraft.world.item.SignApplicator
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SmithingTemplateItem
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
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
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
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CrafterBlock
+ net.minecraft.world.level.block.CrafterBlock$1
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DecoratedPotBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BannerPatterns
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
- net.minecraft.world.level.block.entity.BrushableBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.CrafterBlockEntity
+ net.minecraft.world.level.block.entity.CrafterBlockEntity$1
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
- net.minecraft.world.level.block.entity.DecoratedPotPatterns
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SignText
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity$1
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
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
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
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
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockSetType
+ net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ChestType$1
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.RotationSegment
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.TransparentBlock
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
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperBulbBlock
- net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockCollisions
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
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
+ net.minecraft.world.level.chunk.ChunkGenerators
- net.minecraft.world.level.chunk.ChunkGeneratorStructureState
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
+ net.minecraft.world.level.chunk.LightChunk
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.MissingPaletteEntryException
+ net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.Palette$Factory
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$Configuration
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PalettedContainer$Data
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
+ net.minecraft.world.level.chunk.PalettedContainerRO
- net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
+ net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.SingleValuePalette
- net.minecraft.world.level.chunk.storage.ChunkScanAccess
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.StructureAccess
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.dimension.BuiltinDimensionTypes
+ net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.DimensionType$MonsterSettings
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.EndDragonFight$Data
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
+ net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
+ net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback
+ net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityLookup
+ net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySection
+ net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTickList
+ net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.EntityTypeTest$1
+ net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetter
+ net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
+ net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
+ net.minecraft.world.level.gameevent.DynamicGameEventListener
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- net.minecraft.world.level.gameevent.GameEvent
+ net.minecraft.world.level.gameevent.GameEvent$Context
- net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
+ net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListener$Holder
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationInfo
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.Level$2
- net.minecraft.world.level.Level$ExplosionInteraction
+ net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Beardifier$1
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen
- net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
+ net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.package-info
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
- net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Density
- net.minecraft.world.level.levelgen.DensityFunction
+ net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
+ net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
+ net.minecraft.world.level.levelgen.DensityFunctions
- net.minecraft.world.level.levelgen.DensityFunctions$1
+ net.minecraft.world.level.levelgen.DensityFunctions$Ap2
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
- net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
+ net.minecraft.world.level.levelgen.DensityFunctions$Clamp
- net.minecraft.world.level.levelgen.DensityFunctions$Constant
+ net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
- net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker
- net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Noise
+ net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
- net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
+ net.minecraft.world.level.levelgen.DensityFunctions$Shift
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
- net.minecraft.world.level.levelgen.DensityFunctions$Spline
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
+ net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockColumnFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneUtils
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
- net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.package-info
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature$1
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
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
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.material.MaterialRuleList
+ net.minecraft.world.level.levelgen.material.package-info
- net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
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
- net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BiomeFilter
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
+ net.minecraft.world.level.levelgen.placement.HeightmapPlacement
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
+ net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.PlacedFeature
- net.minecraft.world.level.levelgen.placement.PlacementContext
+ net.minecraft.world.level.levelgen.placement.PlacementFilter
- net.minecraft.world.level.levelgen.placement.PlacementModifier
+ net.minecraft.world.level.levelgen.placement.PlacementModifierType
- net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
+ net.minecraft.world.level.levelgen.placement.RarityFilter
- net.minecraft.world.level.levelgen.placement.RepeatingPlacement
+ net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
- net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
+ net.minecraft.world.level.levelgen.presets.package-info
- net.minecraft.world.level.levelgen.presets.WorldPreset
+ net.minecraft.world.level.levelgen.presets.WorldPresets
- net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.RandomState
+ net.minecraft.world.level.levelgen.RandomState$1
- net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
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
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.pools.alias.Direct
- net.minecraft.world.level.levelgen.structure.pools.alias.package-info
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
- net.minecraft.world.level.levelgen.structure.pools.alias.Random
+ net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.package-info
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
- net.minecraft.world.level.levelgen.SurfaceRules
+ net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
- net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$Condition
+ net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$Context
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Hole
- net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$StateRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Steep
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Temperature
- net.minecraft.world.level.levelgen.SurfaceRules$TestRule
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- net.minecraft.world.level.levelgen.SurfaceSystem
+ net.minecraft.world.level.levelgen.SurfaceSystem$1
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
- net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldDimensions
- net.minecraft.world.level.levelgen.WorldDimensions$1Entry
+ net.minecraft.world.level.levelgen.WorldDimensions$Complete
+ net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.WorldOptions
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelHeightAccessor$1
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.ChunkSkyLightSources
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
- net.minecraft.world.level.lighting.LeveledPriorityQueue
+ net.minecraft.world.level.lighting.LeveledPriorityQueue$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEngine
+ net.minecraft.world.level.lighting.LightEngine$QueueEntry
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightEngine$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.LocalMobCapCalculator
- net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.MapColor
+ net.minecraft.world.level.material.MapColor$Brightness
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.InstantNeighborUpdater
+ net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelDataAndDimensions
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
- net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootParams
+ net.minecraft.world.level.storage.loot.LootParams$Builder
- net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureManager
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
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.level.WorldDataConfiguration
+ net.minecraft.world.level.WorldGenLevel
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
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
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
+ net.minecraft.world.ticks.ContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +1M -1M
```
```
XXX.loot.packs.UpdateOneTwentyOneBlockLoot +11M
```
```
XXX.data.models.BlockModelGenerators$BlockFamilyProvider +1M -1M | +1P
```
```
XXX.data.recipes.RecipeProvider +2M
```
```
XXX.gametest.framework.TestCommand +1M
```
```
XXX.protocol.game.ServerboundSetJigsawBlockPacket +3M -1M | +2P
```
```
XXX.server.gui.StatsComponent -1M
```
```
XXX.minecraft.sounds.SoundEvents +27P
```
```
XXX.level.block.ChangeOverTimeBlock +3M -3M
```

</details>
















<details>
<summary>
net.minecraft.Util
</summary>

```diff
- void shuffle(List,RandomSource)
+ void shuffle(ObjectArrayList,RandomSource)
```

</details>































































































































































































































































































<details>
<summary>
net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
</summary>

```diff
- LootTable$Builder lambda$generate$0(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$1(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$10(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$2(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$3(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$4(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$5(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$6(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$7(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$8(UpdateOneTwentyOneBlockLoot,Block)
- LootTable$Builder lambda$generate$9(UpdateOneTwentyOneBlockLoot,Block)
```

</details>







<details>
<summary>
net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
</summary>

```diff
- BlockModelGenerators$BlockFamilyProvider donateModelTo(Block,Block)
+ BlockModelGenerators$BlockFamilyProvider fullBlockCopies(Block[])
```

</details>

























<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- void copperBulb(RecipeOutput,Block,Block)
- void grate(RecipeOutput,Block,Block)
```

</details>











<details>
<summary>
net.minecraft.gametest.framework.TestCommand
</summary>

```diff
- BlockPos createTestPositionAround(CommandSourceStack)
```

</details>









































































































































































































































<details>
<summary>
net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
</summary>

```diff
- int getPlacementPriority()
- int getSelectionPriority()
- void <init>(BlockPos,ResourceLocation,ResourceLocation,ResourceLocation,String,JigsawBlockEntity$JointType,int,int)
+ void <init>(BlockPos,ResourceLocation,ResourceLocation,ResourceLocation,String,JigsawBlockEntity$JointType)
```

</details>











































































<details>
<summary>
net.minecraft.server.gui.StatsComponent
</summary>

```diff
+ double getAverage(long[])
```

</details>








































































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.ChangeOverTimeBlock
</summary>

```diff
- Optional getNextState(BlockState,ServerLevel,BlockPos,RandomSource)
+ void applyChangeOverTime(BlockState,ServerLevel,BlockPos,RandomSource)
- void changeOverTime(BlockState,ServerLevel,BlockPos,RandomSource)
+ void lambda$applyChangeOverTime$0(ServerLevel,BlockPos,BlockState)
- void lambda$changeOverTime$0(ServerLevel,BlockPos,BlockState)
+ void onRandomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>


































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.animation.definitions.CamelAnimation
+ net.minecraft.client.animation.definitions.FrogAnimation
- net.minecraft.client.animation.definitions.package-info
- net.minecraft.client.animation.definitions.SnifferAnimation
+ net.minecraft.client.animation.definitions.WardenAnimation
+ net.minecraft.client.animation.package-info
- net.minecraft.client.color.block.BlockColor
+ net.minecraft.client.color.block.BlockColors
- net.minecraft.client.color.block.BlockTintCache
+ net.minecraft.client.color.block.BlockTintCache$CacheData
- net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
+ net.minecraft.client.color.block.package-info
- net.minecraft.client.color.item.ItemColor
+ net.minecraft.client.color.item.ItemColors
- net.minecraft.client.color.item.package-info
+ net.minecraft.client.gui.ComponentPath
- net.minecraft.client.gui.ComponentPath$Leaf
+ net.minecraft.client.gui.ComponentPath$Path
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractOptionSliderButton
- net.minecraft.client.gui.components.AbstractScrollWidget
+ net.minecraft.client.gui.components.AbstractSelectionList
- net.minecraft.client.gui.components.AbstractSelectionList$1
+ net.minecraft.client.gui.components.AbstractSelectionList$Entry
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractStringWidget
+ net.minecraft.client.gui.components.AbstractWidget
- net.minecraft.client.gui.components.BossHealthOverlay
+ net.minecraft.client.gui.components.BossHealthOverlay$1
- net.minecraft.client.gui.components.Button
+ net.minecraft.client.gui.components.Button$Builder
- net.minecraft.client.gui.components.Button$CreateNarration
+ net.minecraft.client.gui.components.Button$OnPress
- net.minecraft.client.gui.components.ChatComponent
+ net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
- net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.Checkbox$OnValueChange
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.CommonButtons
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$1
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.CycleButton
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.debugchart.AbstractDebugChart
- net.minecraft.client.gui.components.debugchart.BandwidthDebugChart
+ net.minecraft.client.gui.components.debugchart.FpsDebugChart
- net.minecraft.client.gui.components.debugchart.PingDebugChart
+ net.minecraft.client.gui.components.debugchart.TpsDebugChart
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
- net.minecraft.client.gui.components.FittingMultiLineTextWidget
+ net.minecraft.client.gui.components.FocusableTextWidget
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.ImageWidget
- net.minecraft.client.gui.components.ImageWidget$Sprite
+ net.minecraft.client.gui.components.ImageWidget$Texture
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LoadingDotsWidget
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.LogoRenderer
+ net.minecraft.client.gui.components.MultiLineEditBox
- net.minecraft.client.gui.components.MultiLineLabel
+ net.minecraft.client.gui.components.MultiLineLabel$1
- net.minecraft.client.gui.components.MultiLineLabel$2
+ net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
- net.minecraft.client.gui.components.MultilineTextField
+ net.minecraft.client.gui.components.MultilineTextField$1
- net.minecraft.client.gui.components.MultilineTextField$StringView
- net.minecraft.client.gui.components.MultiLineTextWidget
+ net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlainTextButton
- net.minecraft.client.gui.components.PlayerFaceRenderer
+ net.minecraft.client.gui.components.PlayerSkinWidget
- net.minecraft.client.gui.components.PlayerSkinWidget$Model
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
+ net.minecraft.client.gui.components.PopupScreen
- net.minecraft.client.gui.components.PopupScreen$Builder
+ net.minecraft.client.gui.components.PopupScreen$ButtonOption
- net.minecraft.client.gui.components.Renderable
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.SplashRenderer
- net.minecraft.client.gui.components.SpriteIconButton
+ net.minecraft.client.gui.components.SpriteIconButton$Builder
- net.minecraft.client.gui.components.SpriteIconButton$CenteredIcon
+ net.minecraft.client.gui.components.SpriteIconButton$TextAndIcon
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.StringWidget
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TabButton
+ net.minecraft.client.gui.components.TabOrderedElement
+ net.minecraft.client.gui.components.tabs.GridLayoutTab
- net.minecraft.client.gui.components.tabs.package-info
- net.minecraft.client.gui.components.tabs.Tab
+ net.minecraft.client.gui.components.tabs.TabManager
- net.minecraft.client.gui.components.tabs.TabNavigationBar
+ net.minecraft.client.gui.components.tabs.TabNavigationBar$Builder
+ net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.Tooltip
+ net.minecraft.client.gui.components.Whence
- net.minecraft.client.gui.components.WidgetSprites
- net.minecraft.client.gui.Font
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.CodepointMap
- net.minecraft.client.gui.font.CodepointMap$Output
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$BuilderId
+ net.minecraft.client.gui.font.FontManager$BuilderResult
- net.minecraft.client.gui.font.FontManager$FontDefinitionFile
+ net.minecraft.client.gui.font.FontManager$Preparation
- net.minecraft.client.gui.font.FontManager$UnresolvedBuilderBundle
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontSet$GlyphInfoFilter
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.GlyphRenderTypes
- net.minecraft.client.gui.font.GlyphRenderTypes$1
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
- net.minecraft.client.gui.font.glyphs.package-info
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$1
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
+ net.minecraft.client.gui.font.package-info
- net.minecraft.client.gui.font.providers.BitmapProvider
+ net.minecraft.client.gui.font.providers.BitmapProvider$Definition
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Loader
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Reference
+ net.minecraft.client.gui.font.providers.GlyphProviderType
- net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.ProviderReferenceDefinition
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ net.minecraft.client.gui.font.providers.UnihexProvider
- net.minecraft.client.gui.font.providers.UnihexProvider$ByteContents
+ net.minecraft.client.gui.font.providers.UnihexProvider$Definition
- net.minecraft.client.gui.font.providers.UnihexProvider$Dimensions
+ net.minecraft.client.gui.font.providers.UnihexProvider$Glyph
- net.minecraft.client.gui.font.providers.UnihexProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.UnihexProvider$IntContents
- net.minecraft.client.gui.font.providers.UnihexProvider$LineData
+ net.minecraft.client.gui.font.providers.UnihexProvider$OverrideRange
- net.minecraft.client.gui.font.providers.UnihexProvider$ReaderOutput
+ net.minecraft.client.gui.font.providers.UnihexProvider$ShortContents
+ net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.font.TextFieldHelper$1
+ net.minecraft.client.gui.font.TextFieldHelper$CursorStep
+ net.minecraft.client.gui.Font$DisplayMode
- net.minecraft.client.gui.Font$StringRenderOutput
+ net.minecraft.client.gui.Gui
- net.minecraft.client.gui.Gui$HeartType
+ net.minecraft.client.gui.GuiGraphics
- net.minecraft.client.gui.GuiGraphics$ScissorStack
+ net.minecraft.client.gui.GuiSpriteManager
+ net.minecraft.client.gui.layouts.AbstractLayout
- net.minecraft.client.gui.layouts.AbstractLayout$AbstractChildWrapper
+ net.minecraft.client.gui.layouts.CommonLayouts
- net.minecraft.client.gui.layouts.EqualSpacingLayout
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$1
- net.minecraft.client.gui.layouts.EqualSpacingLayout$ChildContainer
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$Orientation
- net.minecraft.client.gui.layouts.FrameLayout
+ net.minecraft.client.gui.layouts.FrameLayout$ChildContainer
- net.minecraft.client.gui.layouts.GridLayout
+ net.minecraft.client.gui.layouts.GridLayout$CellInhabitant
- net.minecraft.client.gui.layouts.GridLayout$RowHelper
+ net.minecraft.client.gui.layouts.HeaderAndFooterLayout
- net.minecraft.client.gui.layouts.Layout
+ net.minecraft.client.gui.layouts.LayoutElement
- net.minecraft.client.gui.layouts.LayoutSettings
+ net.minecraft.client.gui.layouts.LayoutSettings$LayoutSettingsImpl
- net.minecraft.client.gui.layouts.LinearLayout
+ net.minecraft.client.gui.layouts.LinearLayout$1
- net.minecraft.client.gui.layouts.LinearLayout$Orientation
- net.minecraft.client.gui.layouts.package-info
+ net.minecraft.client.gui.layouts.SpacerElement
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$MapInstance
+ net.minecraft.client.gui.narration.NarratableEntry
- net.minecraft.client.gui.narration.NarratableEntry$NarrationPriority
+ net.minecraft.client.gui.narration.NarratedElementType
- net.minecraft.client.gui.narration.NarrationElementOutput
+ net.minecraft.client.gui.narration.NarrationSupplier
- net.minecraft.client.gui.narration.NarrationThunk
- net.minecraft.client.gui.narration.package-info
+ net.minecraft.client.gui.narration.ScreenNarrationCollector
- net.minecraft.client.gui.narration.ScreenNarrationCollector$1
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$EntryKey
- net.minecraft.client.gui.narration.ScreenNarrationCollector$NarrationEntry
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$Output
+ net.minecraft.client.gui.navigation.CommonInputs
- net.minecraft.client.gui.navigation.FocusNavigationEvent
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$ArrowNavigation
- net.minecraft.client.gui.navigation.FocusNavigationEvent$InitialFocus
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$TabNavigation
- net.minecraft.client.gui.navigation.package-info
- net.minecraft.client.gui.navigation.ScreenAxis
+ net.minecraft.client.gui.navigation.ScreenAxis$1
- net.minecraft.client.gui.navigation.ScreenDirection
+ net.minecraft.client.gui.navigation.ScreenDirection$1
- net.minecraft.client.gui.navigation.ScreenPosition
+ net.minecraft.client.gui.navigation.ScreenPosition$1
- net.minecraft.client.gui.navigation.ScreenRectangle
+ net.minecraft.client.gui.navigation.ScreenRectangle$1
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
+ net.minecraft.client.gui.screens.achievement.StatsScreen
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$Sprites
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType$1
+ net.minecraft.client.gui.screens.advancements.package-info
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.BanNoticeScreens
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlsScreen
+ net.minecraft.client.gui.screens.controls.KeyBindsList
- net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry$1
- net.minecraft.client.gui.screens.controls.KeyBindsList$Entry
+ net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
- net.minecraft.client.gui.screens.controls.KeyBindsScreen
+ net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.CreditsAndAttributionScreen
- net.minecraft.client.gui.screens.DatapackLoadFailureScreen
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.DeathScreen$TitleConfirmScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
- net.minecraft.client.gui.screens.debug.package-info
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.FaviconTexture
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.GenericWaitingScreen
+ net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
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
+ net.minecraft.client.gui.screens.inventory.CrafterScreen
- net.minecraft.client.gui.screens.inventory.CrafterScreen$1
- net.minecraft.client.gui.screens.LanguageSelectScreen
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ net.minecraft.client.gui.screens.LevelLoadingScreen
- net.minecraft.client.gui.screens.LoadingDotsText
+ net.minecraft.client.gui.screens.LoadingOverlay
- net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
+ net.minecraft.client.gui.screens.MenuScreens
- net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
+ net.minecraft.client.gui.screens.MouseSettingsScreen
- net.minecraft.client.gui.screens.NoticeWithLinkScreen
+ net.minecraft.client.gui.screens.OnlineOptionsScreen
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.RecoverWorldDataScreen
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.Screen$DeferredTooltipRendering
+ net.minecraft.client.gui.screens.Screen$NarratableSearchResult
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SimpleOptionsSubScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.TitleScreen$WarningLabel
- net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen
+ net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen$ButtonOption
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
- net.minecraft.client.gui.screens.WinScreen$CreditsReader
+ net.minecraft.data.registries.package-info
- net.minecraft.data.registries.RegistryPatchGenerator
+ net.minecraft.data.registries.UpdateOneTwentyOneRegistries
- net.minecraft.data.registries.VanillaRegistries
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtDatafixer
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BannerPatternTagsProvider
+ net.minecraft.data.tags.BiomeTagsProvider
- net.minecraft.data.tags.CatVariantTagsProvider
+ net.minecraft.data.tags.DamageTypeTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FlatLevelGeneratorPresetTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.InstrumentTagsProvider
+ net.minecraft.data.tags.IntrinsicHolderTagsProvider
- net.minecraft.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.PaintingVariantTagsProvider
+ net.minecraft.data.tags.PoiTypeTagsProvider
- net.minecraft.data.tags.StructureTagsProvider
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1CombinedData
+ net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.tags.TagsProvider$TagLookup
+ net.minecraft.data.tags.TradeRebalanceStructureTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneBlockTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneItemTagsProvider
- net.minecraft.data.tags.VanillaBlockTagsProvider
+ net.minecraft.data.tags.VanillaItemTagsProvider
- net.minecraft.data.tags.WorldPresetTagsProvider
- net.minecraft.data.worldgen.AncientCityStructurePieces
+ net.minecraft.data.worldgen.AncientCityStructurePools
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.biome.BiomeData
- net.minecraft.data.worldgen.biome.EndBiomes
+ net.minecraft.data.worldgen.biome.NetherBiomes
- net.minecraft.data.worldgen.biome.OverworldBiomes
+ net.minecraft.data.worldgen.biome.package-info
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.BootstapContext
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.DimensionTypes
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
+ net.minecraft.data.worldgen.NoiseData
+ net.minecraft.data.worldgen.package-info
- net.minecraft.data.worldgen.PillagerOutpostPools
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
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.Structures
- net.minecraft.data.worldgen.StructureSets
- net.minecraft.data.worldgen.SurfaceRuleData
+ net.minecraft.data.worldgen.TaigaVillagePools
- net.minecraft.data.worldgen.TerrainProvider
+ net.minecraft.data.worldgen.TrailRuinsStructurePools
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
- net.minecraft.gametest.framework.GameTestHelper$2
+ net.minecraft.gametest.framework.GameTestHelper$3
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
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.network.protocol.game.ClientboundTickingStepPacket
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$CommandFunction
+ net.minecraft.server.commands.CloneCommands$DimensionAndPosition
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugConfigCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandGetter
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$2
+ net.minecraft.server.commands.FunctionCommand$3
- net.minecraft.server.commands.FunctionCommand$4
+ net.minecraft.server.commands.FunctionCommand$5
- net.minecraft.server.commands.FunctionCommand$Callbacks
+ net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PerfCommand
+ net.minecraft.server.commands.PlaceCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RandomCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
+ net.minecraft.server.commands.ReturnCommand
- net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.util.datafix.ComponentDataFixUtils
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.DataFixTypes$1
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractPoiSectionFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlendingDataFix
- net.minecraft.util.datafix.fixes.BlendingDataRemoveFromNetherEndFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityRenameFix
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.CauldronRenameFix
- net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
+ net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- net.minecraft.util.datafix.fixes.ChunkDeleteLightFix
+ net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ net.minecraft.util.datafix.fixes.ChunkRenamesFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.CriteriaRenameFix
- net.minecraft.util.datafix.fixes.DecoratedPotFieldRenameFix
+ net.minecraft.util.datafix.fixes.DropInvalidSignDataFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EffectDurationFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityUUIDFix
+ net.minecraft.util.datafix.fixes.EntityVariantFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.FeatureFlagRemoveFix
+ net.minecraft.util.datafix.fixes.FilteredBooksFix
- net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.FixProjectileStoredItem$SubFixer
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GoatHornIdFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
+ net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
- net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemapChunkStatusFix
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VariantRenameFix
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.datafix.schemas.V2568
- net.minecraft.util.datafix.schemas.V2571
+ net.minecraft.util.datafix.schemas.V2684
- net.minecraft.util.datafix.schemas.V2686
+ net.minecraft.util.datafix.schemas.V2688
- net.minecraft.util.datafix.schemas.V2704
+ net.minecraft.util.datafix.schemas.V2707
- net.minecraft.util.datafix.schemas.V2831
+ net.minecraft.util.datafix.schemas.V2832
- net.minecraft.util.datafix.schemas.V2842
+ net.minecraft.util.datafix.schemas.V3076
- net.minecraft.util.datafix.schemas.V3078
+ net.minecraft.util.datafix.schemas.V3081
- net.minecraft.util.datafix.schemas.V3082
+ net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.datafix.schemas.V3202
+ net.minecraft.util.datafix.schemas.V3203
- net.minecraft.util.datafix.schemas.V3204
+ net.minecraft.util.datafix.schemas.V3325
- net.minecraft.util.datafix.schemas.V3326
+ net.minecraft.util.datafix.schemas.V3327
- net.minecraft.util.datafix.schemas.V3328
+ net.minecraft.util.datafix.schemas.V3438
- net.minecraft.util.datafix.schemas.V3448
+ net.minecraft.util.datafix.schemas.V3682
- net.minecraft.util.datafix.schemas.V3683
- net.minecraft.util.SignatureUpdater
+ net.minecraft.util.SignatureUpdater$Output
- net.minecraft.util.SignatureValidator
+ net.minecraft.util.Signer
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SingleKeyCache
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.SpawnUtil
+ net.minecraft.util.SpawnUtil$Strategy
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$EnumCodec
- net.minecraft.util.StringRepresentable$StringRepresentableCodec
+ net.minecraft.util.StringUtil
- net.minecraft.util.TaskChainer
+ net.minecraft.util.TaskChainer$1
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeSource
- net.minecraft.util.TimeSource$NanoTimeSource
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.ToFloatFunction$1
- net.minecraft.util.ToFloatFunction$2
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.ZeroBitStorage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.AttributeModifierTemplate
+ net.minecraft.world.effect.BadOmenMobEffect
- net.minecraft.world.effect.HealOrHarmMobEffect
+ net.minecraft.world.effect.HungerMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$MobEffectAttributeModifierTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$FactorData
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RegenerationMobEffect
- net.minecraft.world.effect.SaturationMobEffect
+ net.minecraft.world.effect.WitherMobEffect
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.BehaviorControl
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
+ net.minecraft.world.entity.ai.behavior.declarative.package-info
- net.minecraft.world.entity.ai.behavior.declarative.Trigger
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToTargetLocation
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.OneShot
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
+ net.minecraft.world.entity.ai.behavior.RandomLookAround
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TriggerGate
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.Allay
+ net.minecraft.world.entity.animal.allay.Allay$JukeboxListener
- net.minecraft.world.entity.animal.allay.Allay$VibrationUser
+ net.minecraft.world.entity.animal.allay.AllayAi
- net.minecraft.world.entity.animal.allay.package-info
+ net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.camel.Camel
+ net.minecraft.world.entity.animal.camel.Camel$CamelBodyRotationControl
- net.minecraft.world.entity.animal.camel.Camel$CamelLookControl
+ net.minecraft.world.entity.animal.camel.Camel$CamelMoveControl
- net.minecraft.world.entity.animal.camel.CamelAi
+ net.minecraft.world.entity.animal.camel.CamelAi$CamelPanic
- net.minecraft.world.entity.animal.camel.CamelAi$RandomSitting
+ net.minecraft.world.entity.animal.camel.package-info
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.CatVariant
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.frog.Frog
+ net.minecraft.world.entity.animal.frog.Frog$FrogLookControl
- net.minecraft.world.entity.animal.frog.Frog$FrogNodeEvaluator
+ net.minecraft.world.entity.animal.frog.Frog$FrogPathNavigation
- net.minecraft.world.entity.animal.frog.FrogAi
- net.minecraft.world.entity.animal.frog.package-info
+ net.minecraft.world.entity.animal.frog.ShootTongue
- net.minecraft.world.entity.animal.frog.ShootTongue$1
+ net.minecraft.world.entity.animal.frog.ShootTongue$State
- net.minecraft.world.entity.animal.frog.Tadpole
+ net.minecraft.world.entity.animal.frog.TadpoleAi
+ net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.GoatAi
+ net.minecraft.world.entity.animal.goat.package-info
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Llama$Variant
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Parrot$Variant
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Rabbit$Variant
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.sniffer.Sniffer
+ net.minecraft.world.entity.animal.sniffer.Sniffer$1
- net.minecraft.world.entity.animal.sniffer.Sniffer$State
+ net.minecraft.world.entity.animal.sniffer.SnifferAi
- net.minecraft.world.entity.animal.sniffer.SnifferAi$1
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$2
- net.minecraft.world.entity.animal.sniffer.SnifferAi$3
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Digging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$FeelingHappy
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$FinishedDigging
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Scenting
+ net.minecraft.world.entity.animal.sniffer.SnifferAi$Searching
- net.minecraft.world.entity.animal.sniffer.SnifferAi$Sniffing
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Base
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.TropicalFish$Variant
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
- net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
- net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
+ net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
- net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
- net.minecraft.world.entity.animal.WaterAnimal
+ net.minecraft.world.entity.animal.Wolf
- net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
- net.minecraft.world.entity.boss.enderdragon.EndCrystal
+ net.minecraft.world.entity.boss.enderdragon.EnderDragon
- net.minecraft.world.entity.boss.enderdragon.package-info
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
+ net.minecraft.world.entity.boss.enderdragon.phases.package-info
+ net.minecraft.world.entity.boss.EnderDragonPart
- net.minecraft.world.entity.boss.package-info
+ net.minecraft.world.entity.boss.wither.package-info
+ net.minecraft.world.entity.boss.wither.WitherBoss
- net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
- net.minecraft.world.entity.decoration.ArmorStand
+ net.minecraft.world.entity.decoration.ArmorStand$1
- net.minecraft.world.entity.decoration.GlowItemFrame
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
- net.minecraft.world.entity.Display
+ net.minecraft.world.entity.Display$1
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.Display$ItemDisplay$1
+ net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
- net.minecraft.world.entity.Display$LinearFloatInterpolator
+ net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$PosRotInterpolationTarget
+ net.minecraft.world.entity.Display$RenderState
- net.minecraft.world.entity.Display$TextDisplay
+ net.minecraft.world.entity.Display$TextDisplay$Align
- net.minecraft.world.entity.Display$TextDisplay$CachedInfo
+ net.minecraft.world.entity.Display$TextDisplay$CachedLine
- net.minecraft.world.entity.Display$TextDisplay$LineSplitter
+ net.minecraft.world.entity.Display$TextDisplay$TextRenderState
- net.minecraft.world.entity.Display$TransformationInterpolator
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
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.LivingEntity$Fallsounds
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
+ net.minecraft.world.entity.monster.Silverfish
- net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- net.minecraft.world.entity.monster.Skeleton
+ net.minecraft.world.entity.monster.Slime
- net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
+ net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
- net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ net.minecraft.world.entity.monster.Slime$SlimeMoveControl
- net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager
- net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ net.minecraft.world.entity.monster.Spider
- net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
+ net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
- net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
+ net.minecraft.world.entity.monster.Stray
- net.minecraft.world.entity.monster.Strider
+ net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
- net.minecraft.world.entity.monster.Strider$StriderPathNavigation
+ net.minecraft.world.entity.monster.Vex
- net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
+ net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
- net.minecraft.world.entity.monster.Vex$VexMoveControl
+ net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
- net.minecraft.world.entity.monster.Vindicator
+ net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.Warden$VibrationUser
- net.minecraft.world.entity.monster.warden.WardenAi
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$FailureItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TypeSpecificTrade
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
- net.minecraft.world.entity.vehicle.ChestBoat
+ net.minecraft.world.entity.vehicle.ChestBoat$1
- net.minecraft.world.entity.vehicle.ContainerEntity
+ net.minecraft.world.entity.vehicle.ContainerEntity$1
- net.minecraft.world.entity.vehicle.DismountHelper
+ net.minecraft.world.entity.vehicle.Minecart
- net.minecraft.world.entity.vehicle.MinecartChest
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock
- net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ net.minecraft.world.entity.vehicle.MinecartFurnace
- net.minecraft.world.entity.vehicle.MinecartHopper
+ net.minecraft.world.entity.vehicle.MinecartSpawner
- net.minecraft.world.entity.vehicle.MinecartSpawner$1
+ net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.entity.vehicle.VehicleEntity
+ net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.flag.FeatureElement
+ net.minecraft.world.flag.FeatureFlag
- net.minecraft.world.flag.FeatureFlagRegistry
+ net.minecraft.world.flag.FeatureFlagRegistry$Builder
- net.minecraft.world.flag.FeatureFlags
- net.minecraft.world.flag.FeatureFlagSet
+ net.minecraft.world.flag.FeatureFlagUniverse
+ net.minecraft.world.flag.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CrafterMenu
+ net.minecraft.world.inventory.CrafterSlot
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu$3
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.NonInteractiveResultSlot
- net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeCraftingHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.inventory.TransientCraftingContainer
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.armortrim.ArmorTrim
+ net.minecraft.world.item.armortrim.package-info
+ net.minecraft.world.item.armortrim.TrimMaterial
- net.minecraft.world.item.armortrim.TrimMaterials
+ net.minecraft.world.item.armortrim.TrimPattern
- net.minecraft.world.item.armortrim.TrimPatterns
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingBookCategory
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CraftingRecipeCodecs
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.DecoratedPotRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeCache
- net.minecraft.world.item.crafting.RecipeCache$Entry
+ net.minecraft.world.item.crafting.RecipeHolder
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer$RawShapedRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmithingRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
+ net.minecraft.world.item.crafting.SmithingTrimRecipe
- net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$Builder
+ net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
- net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.CreativeModeTab$Output
+ net.minecraft.world.item.CreativeModeTab$Row
- net.minecraft.world.item.CreativeModeTab$TabVisibility
+ net.minecraft.world.item.CreativeModeTab$Type
- net.minecraft.world.item.CreativeModeTabs
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
+ net.minecraft.world.item.DyeableArmorItem
- net.minecraft.world.item.DyeableHorseArmorItem
+ net.minecraft.world.item.DyeableLeatherItem
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
- net.minecraft.world.item.EggItem
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.SwiftSneakEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.Equipable
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.GlowInkSacItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.InkSacItem
- net.minecraft.world.item.Instrument
+ net.minecraft.world.item.InstrumentItem
- net.minecraft.world.item.Instruments
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemDisplayContext
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemStackLinkedSet
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.package-info
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
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
+ net.minecraft.world.item.SignApplicator
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SmithingTemplateItem
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
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
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
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CrafterBlock
+ net.minecraft.world.level.block.CrafterBlock$1
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DecoratedPotBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DirtPathBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropExperienceBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BannerPatterns
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
- net.minecraft.world.level.block.entity.BrushableBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.CrafterBlockEntity
+ net.minecraft.world.level.block.entity.CrafterBlockEntity$1
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$Decorations
+ net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
- net.minecraft.world.level.block.entity.DecoratedPotPatterns
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.HangingSignBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SignText
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity$1
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
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
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
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
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockSetType
+ net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ChestType$1
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.DripstoneThickness
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.RotationSegment
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.properties.WallSide
- net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.TransparentBlock
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
- net.minecraft.world.level.block.WallHangingSignBlock
+ net.minecraft.world.level.block.WallHangingSignBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperBulbBlock
- net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockCollisions
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
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
+ net.minecraft.world.level.chunk.ChunkGenerators
- net.minecraft.world.level.chunk.ChunkGeneratorStructureState
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
- net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
+ net.minecraft.world.level.chunk.LightChunk
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.MissingPaletteEntryException
+ net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.Palette$Factory
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$Configuration
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PalettedContainer$Data
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
+ net.minecraft.world.level.chunk.PalettedContainerRO
- net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
+ net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.SingleValuePalette
- net.minecraft.world.level.chunk.storage.ChunkScanAccess
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.StructureAccess
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.dimension.BuiltinDimensionTypes
+ net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.DimensionType$MonsterSettings
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.EndDragonFight$Data
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
- net.minecraft.world.level.dimension.package-info
+ net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.entity.ChunkEntities
- net.minecraft.world.level.entity.ChunkStatusUpdateListener
+ net.minecraft.world.level.entity.EntityAccess
- net.minecraft.world.level.entity.EntityInLevelCallback
+ net.minecraft.world.level.entity.EntityInLevelCallback$1
- net.minecraft.world.level.entity.EntityLookup
+ net.minecraft.world.level.entity.EntityPersistentStorage
- net.minecraft.world.level.entity.EntitySection
+ net.minecraft.world.level.entity.EntitySectionStorage
- net.minecraft.world.level.entity.EntityTickList
+ net.minecraft.world.level.entity.EntityTypeTest
- net.minecraft.world.level.entity.EntityTypeTest$1
+ net.minecraft.world.level.entity.LevelCallback
- net.minecraft.world.level.entity.LevelEntityGetter
+ net.minecraft.world.level.entity.LevelEntityGetterAdapter
- net.minecraft.world.level.entity.package-info
- net.minecraft.world.level.entity.PersistentEntitySectionManager
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
- net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ net.minecraft.world.level.entity.TransientEntitySectionManager
- net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
+ net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.gameevent.BlockPositionSource
- net.minecraft.world.level.gameevent.BlockPositionSource$Type
+ net.minecraft.world.level.gameevent.DynamicGameEventListener
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- net.minecraft.world.level.gameevent.GameEvent
+ net.minecraft.world.level.gameevent.GameEvent$Context
- net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
+ net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
- net.minecraft.world.level.gameevent.GameEventListener$Holder
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationInfo
- net.minecraft.world.level.gameevent.vibrations.VibrationSelector
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.Level$2
- net.minecraft.world.level.Level$ExplosionInteraction
+ net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Beardifier$1
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen
- net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
+ net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.package-info
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
- net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Density
- net.minecraft.world.level.levelgen.DensityFunction
+ net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
+ net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
+ net.minecraft.world.level.levelgen.DensityFunctions
- net.minecraft.world.level.levelgen.DensityFunctions$1
+ net.minecraft.world.level.levelgen.DensityFunctions$Ap2
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
- net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
+ net.minecraft.world.level.levelgen.DensityFunctions$Clamp
- net.minecraft.world.level.levelgen.DensityFunctions$Constant
+ net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
- net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker
- net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Noise
+ net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
- net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
+ net.minecraft.world.level.levelgen.DensityFunctions$Shift
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
- net.minecraft.world.level.levelgen.DensityFunctions$Spline
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
+ net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockColumnFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskFeature
- net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneUtils
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
- net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.package-info
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature$1
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
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
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.material.MaterialRuleList
+ net.minecraft.world.level.levelgen.material.package-info
- net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
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
- net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.BiomeFilter
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
+ net.minecraft.world.level.levelgen.placement.HeightmapPlacement
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
+ net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.PlacedFeature
- net.minecraft.world.level.levelgen.placement.PlacementContext
+ net.minecraft.world.level.levelgen.placement.PlacementFilter
- net.minecraft.world.level.levelgen.placement.PlacementModifier
+ net.minecraft.world.level.levelgen.placement.PlacementModifierType
- net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
+ net.minecraft.world.level.levelgen.placement.RarityFilter
- net.minecraft.world.level.levelgen.placement.RepeatingPlacement
+ net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
- net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
+ net.minecraft.world.level.levelgen.presets.package-info
- net.minecraft.world.level.levelgen.presets.WorldPreset
+ net.minecraft.world.level.levelgen.presets.WorldPresets
- net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.RandomState
+ net.minecraft.world.level.levelgen.RandomState$1
- net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
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
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.pools.alias.Direct
- net.minecraft.world.level.levelgen.structure.pools.alias.package-info
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
- net.minecraft.world.level.levelgen.structure.pools.alias.Random
+ net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
+ net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
+ net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.package-info
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
- net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
+ net.minecraft.world.level.levelgen.structure.StructureSet
- net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureType
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
- net.minecraft.world.level.levelgen.SurfaceRules
+ net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
- net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$Condition
+ net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$Context
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Hole
- net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$StateRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Steep
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Temperature
- net.minecraft.world.level.levelgen.SurfaceRules$TestRule
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- net.minecraft.world.level.levelgen.SurfaceSystem
+ net.minecraft.world.level.levelgen.SurfaceSystem$1
- net.minecraft.world.level.levelgen.synth.BlendedNoise
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NoiseUtils
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise$NoiseParameters
- net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldDimensions
- net.minecraft.world.level.levelgen.WorldDimensions$1Entry
+ net.minecraft.world.level.levelgen.WorldDimensions$Complete
+ net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.WorldOptions
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelHeightAccessor$1
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.ChunkSkyLightSources
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
- net.minecraft.world.level.lighting.LeveledPriorityQueue
+ net.minecraft.world.level.lighting.LeveledPriorityQueue$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEngine
+ net.minecraft.world.level.lighting.LightEngine$QueueEntry
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightEngine$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.LocalMobCapCalculator
- net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FogType
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.MapColor
+ net.minecraft.world.level.material.MapColor$Brightness
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.portal.package-info
- net.minecraft.world.level.portal.PortalForcer
+ net.minecraft.world.level.portal.PortalInfo
- net.minecraft.world.level.portal.PortalShape
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.redstone.CollectingNeighborUpdater
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- net.minecraft.world.level.redstone.InstantNeighborUpdater
+ net.minecraft.world.level.redstone.NeighborUpdater
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelDataAndDimensions
- net.minecraft.world.level.storage.LevelResource
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
- net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.LevelSummary$BackupStatus
- net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
+ net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Path
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FunctionReference
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.IntRange
+ net.minecraft.world.level.storage.loot.IntRange$IntChecker
- net.minecraft.world.level.storage.loot.IntRange$IntLimiter
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootDataId
+ net.minecraft.world.level.storage.loot.LootDataManager
- net.minecraft.world.level.storage.loot.LootDataManager$1
+ net.minecraft.world.level.storage.loot.LootDataResolver
- net.minecraft.world.level.storage.loot.LootDataType
+ net.minecraft.world.level.storage.loot.LootDataType$Validator
- net.minecraft.world.level.storage.loot.LootParams
+ net.minecraft.world.level.storage.loot.LootParams$Builder
- net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
- net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
- net.minecraft.world.level.storage.loot.providers.nbt.package-info
+ net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
+ net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.providers.number.ConstantValue
+ net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
- net.minecraft.world.level.storage.loot.providers.number.NumberProvider
+ net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
- net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
- net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureManager
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
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.level.WorldDataConfiguration
+ net.minecraft.world.level.WorldGenLevel
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
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
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
+ net.minecraft.world.ticks.ContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen$1 +1M -2M
```
```
XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry +1M
```
```
net.minecraft.Util +1M -1M
```
```
XXX.minecraft.client.Timer +1M -1M | +1P
```
```
XXX.screens.telemetry.TelemetryEventWidget +3M -2M | +1P
```
```
XXX.client.model.BatModel +1M | +1P
```
```
XXX.client.renderer.GameRenderer +1P -1P
```
```
XXX.renderer.debug.DebugRenderer +1M
```
```
XXX.minecraft.data.BlockFamilies +3P
```
```
XXX.data.models.BlockModelGenerators +31M -25M
```
```
XXX.models.model.ModelTemplate +1M
```
```
XXX.protocol.game.ClientGamePacketListener +2P
```
```
XXX.server.gui.StatsComponent -1M
```
```
XXX.minecraft.sounds.SoundEvents +27P
```
```
XXX.level.block.ChangeOverTimeBlock +3M -3M
```

</details>











































































<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$1
</summary>

```diff
+ void lambda$run$0(RealmsServer)
- void lambda$run$0(RealmsServiceException)
+ void lambda$run$1(RealmsServiceException)
```

</details>















































<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
</summary>

```diff
- boolean mouseClicked(double,double,int)
```

</details>
























































<details>
<summary>
net.minecraft.Util
</summary>

```diff
- void shuffle(List,RandomSource)
+ void shuffle(ObjectArrayList,RandomSource)
```

</details>































































































































<details>
<summary>
net.minecraft.client.Timer
</summary>

```diff
- void <init>(float,long,FloatUnaryOperator)
+ void <init>(float,long)
```

</details>

































































<details>
<summary>
net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget
</summary>

```diff
- Component grayOutIfDisabled(Component,boolean)
- void addEventType(TelemetryEventWidget$ContentBuilder,TelemetryEventType,boolean)
+ void addEventType(TelemetryEventWidget$ContentBuilder,TelemetryEventType)
- void addEventTypeProperties(TelemetryEventType,TelemetryEventWidget$ContentBuilder,boolean)
+ void addEventTypeProperties(TelemetryEventType,TelemetryEventWidget$ContentBuilder)
```

</details>









































<details>
<summary>
net.minecraft.client.model.BatModel
</summary>

```diff
- void applyHeadRotation(float,float)
```

</details>










































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.debug.DebugRenderer
</summary>

```diff
- void renderFilledUnitCube(PoseStack,MultiBufferSource,BlockPos,float,float,float,float)
```

</details>













































































































































































































































































































































































































































<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- BlockStateGenerator createCopperBulb(Block,ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation)
+ List lambda$createTurtleEgg$40(Integer,Integer)
- List lambda$createTurtleEgg$41(Integer,Integer)
+ ResourceLocation lambda$addBookSlotModel$54(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
- ResourceLocation lambda$addBookSlotModel$55(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
+ ResourceLocation lambda$createSnifferEgg$41(Integer)
- ResourceLocation lambda$createSnifferEgg$42(Integer)
+ Variant lambda$createCalibratedSculkSensor$34(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createCalibratedSculkSensor$35(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createCopperBulb$19(ResourceLocation,ResourceLocation,ResourceLocation,ResourceLocation,Boolean,Boolean)
+ Variant lambda$createFire$20(Variant)
- Variant lambda$createFire$26(Variant)
+ Variant lambda$createJigsaw$56(FrontAndTop)
- Variant lambda$createJigsaw$57(FrontAndTop)
+ Variant lambda$createRepeater$35(Integer,Boolean,Boolean)
- Variant lambda$createRepeater$36(Integer,Boolean,Boolean)
+ Variant lambda$createRespawnAnchor$55(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$56(ResourceLocation[],Integer)
+ Variant lambda$createSculkCatalyst$51(ResourceLocation,ResourceLocation,Boolean)
- Variant lambda$createSculkCatalyst$52(ResourceLocation,ResourceLocation,Boolean)
+ Variant lambda$createSculkSensor$33(ResourceLocation,ResourceLocation,SculkSensorPhase)
- Variant lambda$createSculkSensor$34(ResourceLocation,ResourceLocation,SculkSensorPhase)
+ Variant lambda$createSnifferEgg$42(Function,Integer)
- Variant lambda$createSnifferEgg$43(Function,Integer)
+ Variant lambda$createSnowBlocks$36(ResourceLocation,Integer)
- Variant lambda$createSnowBlocks$37(ResourceLocation,Integer)
+ Variant lambda$createSoulFire$26(Variant)
- Variant lambda$createSoulFire$31(Variant)
+ Variant lambda$createStructureBlock$37(StructureMode)
- Variant lambda$createStructureBlock$38(StructureMode)
+ Variant lambda$createSweetBerryBush$38(Integer)
- Variant lambda$createSweetBerryBush$39(Integer)
+ Variant lambda$createTripwireHook$39(Boolean,Boolean)
- Variant lambda$createTripwireHook$40(Boolean,Boolean)
+ Variant lambda$static$43(ResourceLocation)
- Variant lambda$static$49(ResourceLocation)
+ Variant lambda$wrapModels$19(ResourceLocation)
- Variant lambda$wrapModels$20(ResourceLocation)
- void copyCopperBulbModel(Block,Block)
- void copyDoorModel(Block,Block)
- void copyTrapdoorModel(Block,Block)
- void createCopperBulb(Block)
+ void lambda$addSlotStateAndRotationVariants$53(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,Pair)
- void lambda$addSlotStateAndRotationVariants$54(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,Pair)
+ void lambda$createChiseledBookshelf$52(MultiPartGenerator,ResourceLocation,Direction,VariantProperties$Rotation)
- void lambda$createChiseledBookshelf$53(MultiPartGenerator,ResourceLocation,Direction,VariantProperties$Rotation)
+ void lambda$createGrassBlocks$31(ResourceLocation,TextureMapping)
- void lambda$createGrassBlocks$33(ResourceLocation,TextureMapping)
+ void lambda$createMultiface$49(Block,Condition$TerminalCondition,BooleanProperty)
- void lambda$createMultiface$50(Block,Condition$TerminalCondition,BooleanProperty)
+ void lambda$createMultiface$50(Block,Condition$TerminalCondition)
- void lambda$createMultiface$51(Block,Condition$TerminalCondition)
+ void lambda$run$57(BlockFamily)
- void lambda$run$58(BlockFamily)
+ void lambda$run$58(SpawnEggItem)
- void lambda$run$59(SpawnEggItem)
```

</details>


















<details>
<summary>
net.minecraft.data.models.model.ModelTemplate
</summary>

```diff
- ResourceLocation getDefaultModelLocation(Block)
```

</details>














































































































































































































































































































































<details>
<summary>
net.minecraft.server.gui.StatsComponent
</summary>

```diff
+ double getAverage(long[])
```

</details>








































































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.ChangeOverTimeBlock
</summary>

```diff
- Optional getNextState(BlockState,ServerLevel,BlockPos,RandomSource)
+ void applyChangeOverTime(BlockState,ServerLevel,BlockPos,RandomSource)
- void changeOverTime(BlockState,ServerLevel,BlockPos,RandomSource)
+ void lambda$applyChangeOverTime$0(ServerLevel,BlockPos,BlockState)
- void lambda$changeOverTime$0(ServerLevel,BlockPos,BlockState)
+ void onRandomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>
</details>