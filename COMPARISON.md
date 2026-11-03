## Comparison with [26.4-snapshot-6](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-6)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.4-snapshot-6</th><th>26.4-snapshot-7</th></tr><tr><td>DataPack version</td><td><pre>125.1</pre></td><td><pre>126.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>101.0</pre></td><td><pre>102.0</pre></td></tr><tr><td>World version</td><td><pre>5126</pre></td><td><pre>5127</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742168</pre></td><td><pre>1073742169</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:calcite_pillar
+ minecraft:calcite_slab
+ minecraft:calcite_stairs
+ minecraft:calcite_wall
+ minecraft:chiseled_soulshale
+ minecraft:polished_calcite
+ minecraft:polished_calcite_brick_slab
+ minecraft:polished_calcite_brick_stairs
+ minecraft:polished_calcite_brick_wall
+ minecraft:polished_calcite_bricks
+ minecraft:polished_calcite_slab
+ minecraft:polished_calcite_stairs
+ minecraft:polished_calcite_wall
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:calcite_pillar
+ minecraft:calcite_slab
+ minecraft:calcite_stairs
+ minecraft:calcite_wall
+ minecraft:chiseled_soulshale
+ minecraft:music_disc_flurry
+ minecraft:polished_calcite
+ minecraft:polished_calcite_brick_slab
+ minecraft:polished_calcite_brick_stairs
+ minecraft:polished_calcite_brick_wall
+ minecraft:polished_calcite_bricks
+ minecraft:polished_calcite_slab
+ minecraft:polished_calcite_stairs
+ minecraft:polished_calcite_wall
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.chiseled_soulshale.break
+ minecraft:block.chiseled_soulshale.fall
+ minecraft:block.chiseled_soulshale.hit
+ minecraft:block.chiseled_soulshale.place
+ minecraft:block.chiseled_soulshale.step
+ minecraft:entity.parrot.imitate.frostbite
+ minecraft:music_disc.flurry
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
+ minecraft:calcite_pillar
+ minecraft:calcite_slab
+ minecraft:calcite_stairs
+ minecraft:calcite_wall
+ minecraft:chiseled_soulshale
+ minecraft:polished_calcite
+ minecraft:polished_calcite_brick_slab
+ minecraft:polished_calcite_brick_stairs
+ minecraft:polished_calcite_brick_wall
+ minecraft:polished_calcite_bricks
+ minecraft:polished_calcite_slab
+ minecraft:polished_calcite_stairs
+ minecraft:polished_calcite_wall
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:calcite_pillar
+ minecraft:calcite_slab
+ minecraft:calcite_stairs
+ minecraft:calcite_wall
+ minecraft:chiseled_soulshale
+ minecraft:polished_calcite
+ minecraft:polished_calcite_brick_slab
+ minecraft:polished_calcite_brick_stairs
+ minecraft:polished_calcite_brick_wall
+ minecraft:polished_calcite_bricks
+ minecraft:polished_calcite_slab
+ minecraft:polished_calcite_stairs
+ minecraft:polished_calcite_wall
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:calcite_pillar
+ minecraft:calcite_slab
+ minecraft:calcite_stairs
+ minecraft:calcite_wall
+ minecraft:chiseled_soulshale
+ minecraft:music_disc_flurry
+ minecraft:polished_calcite
+ minecraft:polished_calcite_brick_slab
+ minecraft:polished_calcite_brick_stairs
+ minecraft:polished_calcite_brick_wall
+ minecraft:polished_calcite_bricks
+ minecraft:polished_calcite_slab
+ minecraft:polished_calcite_stairs
+ minecraft:polished_calcite_wall
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.chiseled_soulshale.break
+ minecraft:block.chiseled_soulshale.fall
+ minecraft:block.chiseled_soulshale.hit
+ minecraft:block.chiseled_soulshale.place
+ minecraft:block.chiseled_soulshale.step
+ minecraft:entity.parrot.imitate.frostbite
+ minecraft:music_disc.flurry
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
+ calcite_pillar.json
+ calcite_slab.json
+ calcite_stairs.json
+ calcite_wall.json
+ chiseled_soulshale.json
+ polished_calcite_brick_slab.json
+ polished_calcite_brick_stairs.json
+ polished_calcite_brick_wall.json
+ polished_calcite_bricks.json
+ polished_calcite_slab.json
+ polished_calcite_stairs.json
+ polished_calcite_wall.json
+ polished_calcite.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
effect
</summary>

```diff
+ effect clear <targets: entity> <effect: resource_or_tag>
- effect clear <targets: entity> <effect: resource>
+ effect give <targets: entity> <effect: resource_or_tag> <seconds: integer> <amplifier: integer> <hideParticles: bool>
+ effect give <targets: entity> <effect: resource_or_tag> infinite <amplifier: integer> <hideParticles: bool>
- effect give <targets: entity> <effect: resource> <seconds: integer> <amplifier: integer> <hideParticles: bool>
- effect give <targets: entity> <effect: resource> infinite <amplifier: integer> <hideParticles: bool>
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
+ calcite_pillar_from_calcite_stonecutting.json
+ calcite_pillar.json
+ calcite_slab_from_calcite_stonecutting.json
+ calcite_slab.json
+ calcite_stairs_from_calcite_stonecutting.json
+ calcite_stairs.json
+ calcite_wall_from_calcite_stonecutting.json
+ calcite_wall.json
+ polished_calcite_brick_slab_from_calcite_stonecutting.json
+ polished_calcite_brick_slab_from_polished_calcite_bricks_stonecutting.json
+ polished_calcite_brick_slab_from_polished_calcite_stonecutting.json
+ polished_calcite_brick_slab.json
+ polished_calcite_brick_stairs_from_calcite_stonecutting.json
+ polished_calcite_brick_stairs_from_polished_calcite_bricks_stonecutting.json
+ polished_calcite_brick_stairs_from_polished_calcite_stonecutting.json
+ polished_calcite_brick_stairs.json
+ polished_calcite_brick_wall_from_calcite_stonecutting.json
+ polished_calcite_brick_wall_from_polished_calcite_bricks_stonecutting.json
+ polished_calcite_brick_wall_from_polished_calcite_stonecutting.json
+ polished_calcite_brick_wall.json
+ polished_calcite_bricks_from_calcite_stonecutting.json
+ polished_calcite_bricks_from_polished_calcite_stonecutting.json
+ polished_calcite_bricks.json
+ polished_calcite_from_calcite_stonecutting.json
+ polished_calcite_slab_from_calcite_stonecutting.json
+ polished_calcite_slab_from_polished_calcite_stonecutting.json
+ polished_calcite_slab.json
+ polished_calcite_stairs_from_calcite_stonecutting.json
+ polished_calcite_stairs_from_polished_calcite_stonecutting.json
+ polished_calcite_stairs.json
+ polished_calcite_wall_from_calcite_stonecutting.json
+ polished_calcite_wall_from_polished_calcite_stonecutting.json
+ polished_calcite_wall.json
+ polished_calcite.json
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
+ argument.time.tick_count_too_high: The tick count must not be greater than %s: found %s
+ block.minecraft.calcite_pillar: Calcite Pillar
+ block.minecraft.calcite_slab: Calcite Slab
+ block.minecraft.calcite_stairs: Calcite Stairs
+ block.minecraft.calcite_wall: Calcite Wall
+ block.minecraft.chiseled_soulshale: Chiseled Soulshale
+ block.minecraft.polished_calcite_brick_slab: Polished Calcite Brick Slab
+ block.minecraft.polished_calcite_brick_stairs: Polished Calcite Brick Stairs
+ block.minecraft.polished_calcite_brick_wall: Polished Calcite Brick Wall
+ block.minecraft.polished_calcite_bricks: Polished Calcite Bricks
+ block.minecraft.polished_calcite_slab: Polished Calcite Slab
+ block.minecraft.polished_calcite_stairs: Polished Calcite Stairs
+ block.minecraft.polished_calcite_wall: Polished Calcite Wall
+ block.minecraft.polished_calcite: Polished Calcite
+ commands.effect.clear.specific.failed.multiple: %s targets don't have the requested effect(s)
+ commands.effect.clear.specific.failed.single: %s doesn't have the requested effect(s)
+ commands.effect.clear.specific.success.multiple.new: Removed %s effect(s) from %s targets
+ commands.effect.clear.specific.success.single.new: Removed %s effect(s) from %s
+ commands.effect.give.failed.multiple: Unable to apply %s effect(s) (%s targets are either immune to effects, or have something stronger)
+ commands.effect.give.failed.single: Unable to apply %s effect(s) (%s is either immune to effects, or has something stronger)
+ commands.effect.give.success.multiple.new: Applied %s effect(s) to %s targets
+ commands.effect.give.success.single.new: Applied %s effect(s) to %s
+ gui.recipebook.tooltip: Recipe Book
+ item.minecraft.music_disc_flurry: Music Disc
+ item.minecraft.music_disc_flurry.desc: Hyper Potions - flurry
+ jukebox_song.minecraft.flurry: Hyper Potions - flurry
+ mco.upload.error.block_list_failed: The upload could not be finalized.
+ mco.upload.error.block_upload_failed: Part of the world archive could not be uploaded.
+ mco.upload.error.block_upload_unsupported: This world is too large for the available upload method.
+ mco.upload.error.complete_failed: The upload service could not finish the transfer.
+ mco.upload.error.file_too_large: This world is too large to upload.
+ mco.upload.error.invalid_archive: The world archive is unavailable or changed during upload.
+ mco.upload.error.invalid_session_response: The upload service returned an invalid session.
+ mco.upload.error.processing_failed: The upload service could not process the world.
+ mco.upload.error.renew_failed: The upload session could not be renewed.
+ mco.upload.error.session_create_failed: The upload session could not be created.
+ mco.upload.error.single_upload_failed: The world archive could not be uploaded.
+ mco.upload.error.unexpected_processing_status: The upload service returned an unexpected status.
+ mco.upload.error.unsupported_archive_format: This world archive format is not supported.
+ mco.upload.processing: Processing your world
+ narration.button.state.closed: Closed
+ narration.button.state.open: Open
+ narration.button.usage.focused.close: Press Enter to close
+ narration.button.usage.focused.open: Press Enter to open
+ narration.button.usage.hovered.close: Left-click to close
+ narration.button.usage.hovered.open: Left-click to open
+ narration.count_and_item: %s %s
+ narration.crafter_slot.disabled: Disabled
+ narration.crafter_slot.usage.focused.disable: Press Enter to disable slot
+ narration.crafter_slot.usage.focused.enable: Press Enter to enable slot
+ narration.crafter_slot.usage.hovered.disable: Left-click to disable slot
+ narration.crafter_slot.usage.hovered.enable: Left-click to enable slot
+ narration.group_navigation.usage.direction.any: the arrow keys
+ narration.group_navigation.usage.direction.horizontal: the left or right arrow keys
+ narration.group_navigation.usage.direction.vertical: the up or down arrow keys
+ narration.group_navigation.usage.enchantment: Press %s to go to another enchantment
+ narration.group_navigation.usage.pattern: Press %s to go to another pattern
+ narration.group_navigation.usage.recipe: Press %s to go to another recipe
+ narration.group_navigation.usage.slot: Press %s to go to another slot
+ narration.group_navigation.usage.trade: Press %s to go to another trade
+ narration.slot_group.equipment: Equipment
+ narration.slot_group.fuel: Fuel
+ narration.slot_group.hotbar: Hotbar
+ narration.slot_group.input: Input
+ narration.slot_group.inventory: Inventory
+ narration.slot_group.result: Result
+ narration.slot_group.second_input: Second input
+ narration.slot.empty: Empty
+ narration.slot.name.body: Armor
+ narration.slot.name.carpet: Carpet
+ narration.slot.name.chest: Chestplate
+ narration.slot.name.feet: Boots
+ narration.slot.name.fuel: Fuel
+ narration.slot.name.head: Helmet
+ narration.slot.name.ingredient: Ingredient
+ narration.slot.name.legs: Leggings
+ narration.slot.name.offhand: Offhand
+ narration.slot.name.potion: Potion
+ narration.slot.name.result: Result
+ narration.slot.name.saddle: Saddle
+ narration.slot.title: %s, slot
+ narration.slot.title.named: %s, %s slot
+ narration.slot.title.named.located: %s, %s slot, %s
+ narration.slot.usage.focused.pick_up: Press Enter to pick up
+ narration.slot.usage.focused.place: Press Enter to place %s
+ narration.slot.usage.hovered.pick_up: Left-click to pick up
+ narration.slot.usage.hovered.place: Left-click to place %s
+ narration.trade_offer.one_cost: Trade offer: %s for %s
+ narration.trade_offer.out_of_stock: %s, out of stock
+ narration.trade_offer.two_costs: Trade offer: %s and %s for %s
+ narrator.button.recipe_book: Recipe Book
+ narrator.position.grid: Column %s of %s, row %s of %s
+ narrator.position.slot: %s out of %s
+ subtitles.entity.parrot.imitate.frostbite: Parrot groans
```

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
+ reports/minecraft/components/item/calcite_pillar.json
+ reports/minecraft/components/item/calcite_slab.json
+ reports/minecraft/components/item/calcite_stairs.json
+ reports/minecraft/components/item/calcite_wall.json
+ reports/minecraft/components/item/chiseled_soulshale.json
+ reports/minecraft/components/item/music_disc_flurry.json
+ reports/minecraft/components/item/polished_calcite_brick_slab.json
+ reports/minecraft/components/item/polished_calcite_brick_stairs.json
+ reports/minecraft/components/item/polished_calcite_brick_wall.json
+ reports/minecraft/components/item/polished_calcite_bricks.json
+ reports/minecraft/components/item/polished_calcite_slab.json
+ reports/minecraft/components/item/polished_calcite_stairs.json
+ reports/minecraft/components/item/polished_calcite_wall.json
+ reports/minecraft/components/item/polished_calcite.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancement/recipes/building_blocks/calcite_pillar_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/calcite_pillar.json
+ minecraft/advancement/recipes/building_blocks/calcite_slab_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/calcite_slab.json
+ minecraft/advancement/recipes/building_blocks/calcite_stairs_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/calcite_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_slab_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_slab_from_polished_calcite_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_slab_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_stairs_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_stairs_from_polished_calcite_bricks_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_stairs_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_brick_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_bricks_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_bricks_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_bricks.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_slab_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_slab_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_slab.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_stairs_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_stairs_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite_stairs.json
+ minecraft/advancement/recipes/building_blocks/polished_calcite.json
+ minecraft/advancement/recipes/decorations/calcite_wall_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/decorations/calcite_wall.json
+ minecraft/advancement/recipes/decorations/polished_calcite_brick_wall_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_calcite_brick_wall_from_polished_calcite_bricks_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_calcite_brick_wall_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_calcite_brick_wall.json
+ minecraft/advancement/recipes/decorations/polished_calcite_wall_from_calcite_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_calcite_wall_from_polished_calcite_stonecutting.json
+ minecraft/advancement/recipes/decorations/polished_calcite_wall.json
+ minecraft/block_sound_set/chiseled_soulshale.json
- minecraft/block_sound_set/twisting_vines.json
+ minecraft/jukebox_song/flurry.json
+ minecraft/loot_table/blocks/calcite_pillar.json
+ minecraft/loot_table/blocks/calcite_slab.json
+ minecraft/loot_table/blocks/calcite_stairs.json
+ minecraft/loot_table/blocks/calcite_wall.json
+ minecraft/loot_table/blocks/chiseled_soulshale.json
+ minecraft/loot_table/blocks/polished_calcite_brick_slab.json
+ minecraft/loot_table/blocks/polished_calcite_brick_stairs.json
+ minecraft/loot_table/blocks/polished_calcite_brick_wall.json
+ minecraft/loot_table/blocks/polished_calcite_bricks.json
+ minecraft/loot_table/blocks/polished_calcite_slab.json
+ minecraft/loot_table/blocks/polished_calcite_stairs.json
+ minecraft/loot_table/blocks/polished_calcite_wall.json
+ minecraft/loot_table/blocks/polished_calcite.json
+ minecraft/recipe/calcite_pillar_from_calcite_stonecutting.json
+ minecraft/recipe/calcite_pillar.json
+ minecraft/recipe/calcite_slab_from_calcite_stonecutting.json
+ minecraft/recipe/calcite_slab.json
+ minecraft/recipe/calcite_stairs_from_calcite_stonecutting.json
+ minecraft/recipe/calcite_stairs.json
+ minecraft/recipe/calcite_wall_from_calcite_stonecutting.json
+ minecraft/recipe/calcite_wall.json
+ minecraft/recipe/polished_calcite_brick_slab_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_slab_from_polished_calcite_bricks_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_slab_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_slab.json
+ minecraft/recipe/polished_calcite_brick_stairs_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_stairs_from_polished_calcite_bricks_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_stairs_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_stairs.json
+ minecraft/recipe/polished_calcite_brick_wall_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_wall_from_polished_calcite_bricks_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_wall_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_brick_wall.json
+ minecraft/recipe/polished_calcite_bricks_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_bricks_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_bricks.json
+ minecraft/recipe/polished_calcite_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_slab_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_slab_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_slab.json
+ minecraft/recipe/polished_calcite_stairs_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_stairs_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_stairs.json
+ minecraft/recipe/polished_calcite_wall_from_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_wall_from_polished_calcite_stonecutting.json
+ minecraft/recipe/polished_calcite_wall.json
+ minecraft/recipe/polished_calcite.json
- minecraft/tags/entity_type/flying.json
- minecraft/tags/entity_type/swimming.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/calcite_pillar.json
+ minecraft/blockstates/calcite_slab.json
+ minecraft/blockstates/calcite_stairs.json
+ minecraft/blockstates/calcite_wall.json
+ minecraft/blockstates/chiseled_soulshale.json
+ minecraft/blockstates/polished_calcite_brick_slab.json
+ minecraft/blockstates/polished_calcite_brick_stairs.json
+ minecraft/blockstates/polished_calcite_brick_wall.json
+ minecraft/blockstates/polished_calcite_bricks.json
+ minecraft/blockstates/polished_calcite_slab.json
+ minecraft/blockstates/polished_calcite_stairs.json
+ minecraft/blockstates/polished_calcite_wall.json
+ minecraft/blockstates/polished_calcite.json
+ minecraft/items/calcite_pillar.json
+ minecraft/items/calcite_slab.json
+ minecraft/items/calcite_stairs.json
+ minecraft/items/calcite_wall.json
+ minecraft/items/chiseled_soulshale.json
+ minecraft/items/music_disc_flurry.json
+ minecraft/items/polished_calcite_brick_slab.json
+ minecraft/items/polished_calcite_brick_stairs.json
+ minecraft/items/polished_calcite_brick_wall.json
+ minecraft/items/polished_calcite_bricks.json
+ minecraft/items/polished_calcite_slab.json
+ minecraft/items/polished_calcite_stairs.json
+ minecraft/items/polished_calcite_wall.json
+ minecraft/items/polished_calcite.json
+ minecraft/models/block/calcite_pillar_horizontal.json
+ minecraft/models/block/calcite_pillar.json
+ minecraft/models/block/calcite_slab_top.json
+ minecraft/models/block/calcite_slab.json
+ minecraft/models/block/calcite_stairs_inner.json
+ minecraft/models/block/calcite_stairs_outer.json
+ minecraft/models/block/calcite_stairs.json
+ minecraft/models/block/calcite_wall_inventory.json
+ minecraft/models/block/calcite_wall_post.json
+ minecraft/models/block/calcite_wall_side_tall.json
+ minecraft/models/block/calcite_wall_side.json
+ minecraft/models/block/chiseled_soulshale.json
+ minecraft/models/block/icicle_base_base.json
+ minecraft/models/block/icicle_base_frustum.json
+ minecraft/models/block/icicle_base_middle.json
+ minecraft/models/block/icicle_base_tip_merge.json
+ minecraft/models/block/icicle_base_tip.json
+ minecraft/models/block/icicle_base.json
- minecraft/models/block/icicle_down_base_base.json
- minecraft/models/block/icicle_down_base.json
- minecraft/models/block/icicle_down_frustum_base.json
- minecraft/models/block/icicle_down_frustum.json
- minecraft/models/block/icicle_down_middle_base.json
- minecraft/models/block/icicle_down_middle.json
- minecraft/models/block/icicle_down_tip_base.json
- minecraft/models/block/icicle_down_tip_merge_base.json
- minecraft/models/block/icicle_down_tip_merge.json
- minecraft/models/block/icicle_down_tip.json
+ minecraft/models/block/icicle_frustum.json
+ minecraft/models/block/icicle_middle.json
+ minecraft/models/block/icicle_tip_merge.json
+ minecraft/models/block/icicle_tip.json
+ minecraft/models/block/polished_calcite_brick_slab_top.json
+ minecraft/models/block/polished_calcite_brick_slab.json
+ minecraft/models/block/polished_calcite_brick_stairs_inner.json
+ minecraft/models/block/polished_calcite_brick_stairs_outer.json
+ minecraft/models/block/polished_calcite_brick_stairs.json
+ minecraft/models/block/polished_calcite_brick_wall_inventory.json
+ minecraft/models/block/polished_calcite_brick_wall_post.json
+ minecraft/models/block/polished_calcite_brick_wall_side_tall.json
+ minecraft/models/block/polished_calcite_brick_wall_side.json
+ minecraft/models/block/polished_calcite_bricks.json
+ minecraft/models/block/polished_calcite_slab_double.json
+ minecraft/models/block/polished_calcite_slab_top.json
+ minecraft/models/block/polished_calcite_slab.json
+ minecraft/models/block/polished_calcite_stairs_inner.json
+ minecraft/models/block/polished_calcite_stairs_outer.json
+ minecraft/models/block/polished_calcite_stairs.json
+ minecraft/models/block/polished_calcite_wall_inventory.json
+ minecraft/models/block/polished_calcite_wall_post.json
+ minecraft/models/block/polished_calcite_wall_side_tall.json
+ minecraft/models/block/polished_calcite_wall_side.json
+ minecraft/models/block/polished_calcite.json
+ minecraft/models/item/music_disc_flurry.json
+ minecraft/textures/block/calcite_pillar_side.png
+ minecraft/textures/block/calcite_pillar_top.png
+ minecraft/textures/block/chiseled_soulshale.png
+ minecraft/textures/block/icicle_base.png
- minecraft/textures/block/icicle_down_base.png
- minecraft/textures/block/icicle_down_frustum.png
- minecraft/textures/block/icicle_down_middle.png
- minecraft/textures/block/icicle_down_tip_merge.png
- minecraft/textures/block/icicle_down_tip.png
+ minecraft/textures/block/icicle_frustum.png
+ minecraft/textures/block/icicle_middle.png
+ minecraft/textures/block/icicle_tip_merge.png
+ minecraft/textures/block/icicle_tip.png
+ minecraft/textures/block/polished_calcite_bricks.png
+ minecraft/textures/block/polished_calcite_slab_side.png
+ minecraft/textures/block/polished_calcite.png
+ minecraft/textures/item/music_disc_flurry.png
```

</details>
</details>
<hr/>