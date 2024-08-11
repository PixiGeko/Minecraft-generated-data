## Comparison with [21w03a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w03a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">21w03a</th><th>21w05a</th></tr><tr><td>World version</td><td><code>2689</code></td><td><code>2690</code></td></tr><tr><td>Protocol version</td><td><code>1073741835</code></td><td><code>1073741836</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:azalea
+ minecraft:azalea_leaves
+ minecraft:azalea_leaves_flowers
+ minecraft:big_dripleaf
+ minecraft:big_dripleaf_stem
+ minecraft:cave_vines_body
+ minecraft:cave_vines_head
+ minecraft:exposed_copper_block
+ minecraft:exposed_cut_copper
+ minecraft:exposed_cut_copper_slab
+ minecraft:exposed_cut_copper_stairs
+ minecraft:flowering_azalea
+ minecraft:hanging_roots
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:moss_block
+ minecraft:moss_carpet
+ minecraft:oxidized_copper_block
+ minecraft:oxidized_cut_copper
+ minecraft:oxidized_cut_copper_slab
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:rooted_dirt
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_dripleaf
+ minecraft:spore_blossom
+ minecraft:waxed_exposed_copper
+ minecraft:waxed_exposed_cut_copper
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:waxed_weathered_copper
+ minecraft:waxed_weathered_cut_copper
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_weathered_cut_copper_stairs
```

</details>






<details>
<summary>
game_event.txt
</summary>

```diff
- minecraft:armor_stand_add_item
+ minecraft:block_change
+ minecraft:drinking_finish
+ minecraft:eat
- minecraft:eating_finish
+ minecraft:entity_damaged
- minecraft:entity_hit
+ minecraft:entity_killed
+ minecraft:entity_place
+ minecraft:equip
- minecraft:flint_and_steel_use
+ minecraft:minecart_moving
+ minecraft:mob_interact
+ minecraft:prime_fuse
+ minecraft:ravager_roar
+ minecraft:ring_bell
+ minecraft:shear
+ minecraft:shulker_close
+ minecraft:shulker_open
```

</details>
<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:azalea
+ minecraft:azalea_leaves
+ minecraft:azalea_leaves_flowers
+ minecraft:big_dripleaf
+ minecraft:exposed_copper_block
+ minecraft:exposed_cut_copper
+ minecraft:exposed_cut_copper_slab
+ minecraft:exposed_cut_copper_stairs
+ minecraft:flowering_azalea
+ minecraft:glow_berries
+ minecraft:hanging_roots
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:moss_block
+ minecraft:moss_carpet
+ minecraft:oxidized_copper_block
+ minecraft:oxidized_cut_copper
+ minecraft:oxidized_cut_copper_slab
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:rooted_dirt
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_dripleaf
+ minecraft:spore_blossom
+ minecraft:waxed_exposed_copper
+ minecraft:waxed_exposed_cut_copper
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:waxed_weathered_copper
+ minecraft:waxed_weathered_cut_copper
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_weathered_cut_copper_stairs
```

</details>










<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:falling_spore_blossom
+ minecraft:spore_blossom_air
```

</details>









<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.azalea_leaves.break
+ minecraft:block.azalea_leaves.fall
+ minecraft:block.azalea_leaves.hit
+ minecraft:block.azalea_leaves.place
+ minecraft:block.azalea_leaves.step
+ minecraft:block.azalea.break
+ minecraft:block.azalea.fall
+ minecraft:block.azalea.hit
+ minecraft:block.azalea.place
+ minecraft:block.azalea.step
+ minecraft:block.big_dripleaf.break
+ minecraft:block.big_dripleaf.fall
+ minecraft:block.big_dripleaf.hit
+ minecraft:block.big_dripleaf.place
+ minecraft:block.big_dripleaf.step
+ minecraft:block.big_dripleaf.tilt_down
+ minecraft:block.big_dripleaf.tilt_up
+ minecraft:block.cave_vines.break
+ minecraft:block.cave_vines.fall
+ minecraft:block.cave_vines.hit
+ minecraft:block.cave_vines.pick_berries
+ minecraft:block.cave_vines.place
+ minecraft:block.cave_vines.step
+ minecraft:block.flowering_azalea.break
+ minecraft:block.flowering_azalea.fall
+ minecraft:block.flowering_azalea.hit
+ minecraft:block.flowering_azalea.place
+ minecraft:block.flowering_azalea.step
+ minecraft:block.hanging_roots.break
+ minecraft:block.hanging_roots.fall
+ minecraft:block.hanging_roots.hit
+ minecraft:block.hanging_roots.place
+ minecraft:block.hanging_roots.step
+ minecraft:block.moss_carpet.break
+ minecraft:block.moss_carpet.fall
+ minecraft:block.moss_carpet.hit
+ minecraft:block.moss_carpet.place
+ minecraft:block.moss_carpet.step
+ minecraft:block.moss.break
+ minecraft:block.moss.fall
+ minecraft:block.moss.hit
+ minecraft:block.moss.place
+ minecraft:block.moss.step
+ minecraft:block.rooted_dirt.break
+ minecraft:block.rooted_dirt.fall
+ minecraft:block.rooted_dirt.hit
+ minecraft:block.rooted_dirt.place
+ minecraft:block.rooted_dirt.step
+ minecraft:block.small_dripleaf.break
+ minecraft:block.small_dripleaf.fall
+ minecraft:block.small_dripleaf.hit
+ minecraft:block.small_dripleaf.place
+ minecraft:block.small_dripleaf.step
+ minecraft:block.spore_blossom.break
+ minecraft:block.spore_blossom.fall
+ minecraft:block.spore_blossom.hit
+ minecraft:block.spore_blossom.place
+ minecraft:block.spore_blossom.step
+ minecraft:block.vine.break
+ minecraft:block.vine.fall
+ minecraft:block.vine.hit
+ minecraft:block.vine.place
+ minecraft:entity.skeleton.converted_to_stray
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:big_dripleaf_stem
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:azalea
+ minecraft:azalea_leaves
+ minecraft:azalea_leaves_flowers
+ minecraft:big_dripleaf
+ minecraft:cave_vines_body
+ minecraft:cave_vines_head
+ minecraft:exposed_copper_block
+ minecraft:exposed_cut_copper
+ minecraft:exposed_cut_copper_slab
+ minecraft:exposed_cut_copper_stairs
+ minecraft:flowering_azalea
+ minecraft:hanging_roots
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:moss_block
+ minecraft:moss_carpet
+ minecraft:oxidized_copper_block
+ minecraft:oxidized_cut_copper
+ minecraft:oxidized_cut_copper_slab
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:rooted_dirt
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_dripleaf
+ minecraft:spore_blossom
+ minecraft:waxed_exposed_copper
+ minecraft:waxed_exposed_cut_copper
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:waxed_weathered_copper
+ minecraft:waxed_weathered_cut_copper
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_weathered_cut_copper_stairs
```

</details>



<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:big_dripleaf_stem
```

</details>


<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:azalea
+ minecraft:azalea_leaves
+ minecraft:azalea_leaves_flowers
+ minecraft:big_dripleaf
+ minecraft:big_dripleaf_stem
+ minecraft:cave_vines_body
+ minecraft:cave_vines_head
+ minecraft:exposed_copper_block
+ minecraft:exposed_cut_copper
+ minecraft:exposed_cut_copper_slab
+ minecraft:exposed_cut_copper_stairs
+ minecraft:flowering_azalea
+ minecraft:hanging_roots
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:moss_block
+ minecraft:moss_carpet
+ minecraft:oxidized_copper_block
+ minecraft:oxidized_cut_copper
+ minecraft:oxidized_cut_copper_slab
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:rooted_dirt
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_dripleaf
+ minecraft:spore_blossom
+ minecraft:waxed_exposed_copper
+ minecraft:waxed_exposed_cut_copper
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:waxed_weathered_copper
+ minecraft:waxed_weathered_cut_copper
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_weathered_cut_copper_stairs
```

</details>






<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
- minecraft:armor_stand_add_item
+ minecraft:block_change
+ minecraft:drinking_finish
+ minecraft:eat
- minecraft:eating_finish
+ minecraft:entity_damaged
- minecraft:entity_hit
+ minecraft:entity_killed
+ minecraft:entity_place
+ minecraft:equip
- minecraft:flint_and_steel_use
+ minecraft:minecart_moving
+ minecraft:mob_interact
+ minecraft:prime_fuse
+ minecraft:ravager_roar
+ minecraft:ring_bell
+ minecraft:shear
+ minecraft:shulker_close
+ minecraft:shulker_open
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:azalea
+ minecraft:azalea_leaves
+ minecraft:azalea_leaves_flowers
+ minecraft:big_dripleaf
+ minecraft:exposed_copper_block
+ minecraft:exposed_cut_copper
+ minecraft:exposed_cut_copper_slab
+ minecraft:exposed_cut_copper_stairs
+ minecraft:flowering_azalea
+ minecraft:glow_berries
+ minecraft:hanging_roots
- minecraft:lightly_weathered_copper_block
- minecraft:lightly_weathered_cut_copper
- minecraft:lightly_weathered_cut_copper_slab
- minecraft:lightly_weathered_cut_copper_stairs
+ minecraft:moss_block
+ minecraft:moss_carpet
+ minecraft:oxidized_copper_block
+ minecraft:oxidized_cut_copper
+ minecraft:oxidized_cut_copper_slab
+ minecraft:oxidized_cut_copper_stairs
+ minecraft:rooted_dirt
- minecraft:semi_weathered_copper_block
- minecraft:semi_weathered_cut_copper
- minecraft:semi_weathered_cut_copper_slab
- minecraft:semi_weathered_cut_copper_stairs
+ minecraft:small_dripleaf
+ minecraft:spore_blossom
+ minecraft:waxed_exposed_copper
+ minecraft:waxed_exposed_cut_copper
+ minecraft:waxed_exposed_cut_copper_slab
+ minecraft:waxed_exposed_cut_copper_stairs
- minecraft:waxed_lightly_weathered_copper
- minecraft:waxed_lightly_weathered_cut_copper
- minecraft:waxed_lightly_weathered_cut_copper_slab
- minecraft:waxed_lightly_weathered_cut_copper_stairs
- minecraft:waxed_semi_weathered_copper
- minecraft:waxed_semi_weathered_cut_copper
- minecraft:waxed_semi_weathered_cut_copper_slab
- minecraft:waxed_semi_weathered_cut_copper_stairs
+ minecraft:waxed_weathered_copper
+ minecraft:waxed_weathered_cut_copper
+ minecraft:waxed_weathered_cut_copper_slab
+ minecraft:waxed_weathered_cut_copper_stairs
```

</details>










<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:falling_spore_blossom
+ minecraft:spore_blossom_air
```

</details>









<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.azalea_leaves.break
+ minecraft:block.azalea_leaves.fall
+ minecraft:block.azalea_leaves.hit
+ minecraft:block.azalea_leaves.place
+ minecraft:block.azalea_leaves.step
+ minecraft:block.azalea.break
+ minecraft:block.azalea.fall
+ minecraft:block.azalea.hit
+ minecraft:block.azalea.place
+ minecraft:block.azalea.step
+ minecraft:block.big_dripleaf.break
+ minecraft:block.big_dripleaf.fall
+ minecraft:block.big_dripleaf.hit
+ minecraft:block.big_dripleaf.place
+ minecraft:block.big_dripleaf.step
+ minecraft:block.big_dripleaf.tilt_down
+ minecraft:block.big_dripleaf.tilt_up
+ minecraft:block.cave_vines.break
+ minecraft:block.cave_vines.fall
+ minecraft:block.cave_vines.hit
+ minecraft:block.cave_vines.pick_berries
+ minecraft:block.cave_vines.place
+ minecraft:block.cave_vines.step
+ minecraft:block.flowering_azalea.break
+ minecraft:block.flowering_azalea.fall
+ minecraft:block.flowering_azalea.hit
+ minecraft:block.flowering_azalea.place
+ minecraft:block.flowering_azalea.step
+ minecraft:block.hanging_roots.break
+ minecraft:block.hanging_roots.fall
+ minecraft:block.hanging_roots.hit
+ minecraft:block.hanging_roots.place
+ minecraft:block.hanging_roots.step
+ minecraft:block.moss_carpet.break
+ minecraft:block.moss_carpet.fall
+ minecraft:block.moss_carpet.hit
+ minecraft:block.moss_carpet.place
+ minecraft:block.moss_carpet.step
+ minecraft:block.moss.break
+ minecraft:block.moss.fall
+ minecraft:block.moss.hit
+ minecraft:block.moss.place
+ minecraft:block.moss.step
+ minecraft:block.rooted_dirt.break
+ minecraft:block.rooted_dirt.fall
+ minecraft:block.rooted_dirt.hit
+ minecraft:block.rooted_dirt.place
+ minecraft:block.rooted_dirt.step
+ minecraft:block.small_dripleaf.break
+ minecraft:block.small_dripleaf.fall
+ minecraft:block.small_dripleaf.hit
+ minecraft:block.small_dripleaf.place
+ minecraft:block.small_dripleaf.step
+ minecraft:block.spore_blossom.break
+ minecraft:block.spore_blossom.fall
+ minecraft:block.spore_blossom.hit
+ minecraft:block.spore_blossom.place
+ minecraft:block.spore_blossom.step
+ minecraft:block.vine.break
+ minecraft:block.vine.fall
+ minecraft:block.vine.hit
+ minecraft:block.vine.place
+ minecraft:entity.skeleton.converted_to_stray
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ cut_copper_from_copper_block_stonecutting.json
+ cut_copper_slab_from_copper_block_stonecutting.json
+ cut_copper_slab_from_cut_copper_stonecutting.json
+ cut_copper_stairs_from_copper_block_stonecutting.json
+ cut_copper_stairs_from_cut_copper_stonecutting.json
+ exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_slab_from_exposed_cut_copper_stonecutting.json
+ exposed_cut_copper_slab.json
+ exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ exposed_cut_copper_stairs_from_exposed_cut_copper_stonecutting.json
+ exposed_cut_copper_stairs.json
+ exposed_cut_copper.json
- lightly_weathered_cut_copper_slab.json
- lightly_weathered_cut_copper_stairs.json
- lightly_weathered_cut_copper.json
+ moss_carpet.json
+ oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_slab_from_oxidized_cut_copper_stonecutting.json
+ oxidized_cut_copper_slab.json
+ oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ oxidized_cut_copper_stairs_from_oxidized_cut_copper_stonecutting.json
+ oxidized_cut_copper_stairs.json
+ oxidized_cut_copper.json
- semi_weathered_cut_copper_slab.json
- semi_weathered_cut_copper_stairs.json
- semi_weathered_cut_copper.json
+ waxed_cut_copper_from_waxed_copper_stonecutting.json
+ waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ waxed_cut_copper_slab_from_waxed_cut_copper_stonecutting.json
+ waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
+ waxed_cut_copper_stairs_from_waxed_cut_copper_stonecutting.json
+ waxed_exposed_copper.json
+ waxed_exposed_cut_copper_from_honeycomb.json
+ waxed_exposed_cut_copper_from_waxed_exposed_copper_stonecutting.json
+ waxed_exposed_cut_copper_slab_from_honeycomb.json
+ waxed_exposed_cut_copper_slab_from_waxed_exposed_copper_stonecutting.json
+ waxed_exposed_cut_copper_slab_from_waxed_exposed_cut_copper_stonecutting.json
+ waxed_exposed_cut_copper_slab.json
+ waxed_exposed_cut_copper_stairs_from_honeycomb.json
+ waxed_exposed_cut_copper_stairs_from_waxed_exposed_copper_stonecutting.json
+ waxed_exposed_cut_copper_stairs_from_waxed_exposed_cut_copper_stonecutting.json
+ waxed_exposed_cut_copper_stairs.json
+ waxed_exposed_cut_copper.json
- waxed_lightly_weathered_copper.json
- waxed_lightly_weathered_cut_copper_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_slab.json
- waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- waxed_lightly_weathered_cut_copper_stairs.json
- waxed_lightly_weathered_cut_copper.json
- waxed_semi_weathered_copper.json
- waxed_semi_weathered_cut_copper_from_honeycomb.json
- waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- waxed_semi_weathered_cut_copper_slab.json
- waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- waxed_semi_weathered_cut_copper_stairs.json
- waxed_semi_weathered_cut_copper.json
+ waxed_weathered_copper.json
+ waxed_weathered_cut_copper_from_honeycomb.json
+ waxed_weathered_cut_copper_from_waxed_weathered_copper_stonecutting.json
+ waxed_weathered_cut_copper_slab_from_honeycomb.json
+ waxed_weathered_cut_copper_slab_from_waxed_weathered_copper_stonecutting.json
+ waxed_weathered_cut_copper_slab_from_waxed_weathered_cut_copper_stonecutting.json
+ waxed_weathered_cut_copper_slab.json
+ waxed_weathered_cut_copper_stairs_from_honeycomb.json
+ waxed_weathered_cut_copper_stairs_from_waxed_weathered_copper_stonecutting.json
+ waxed_weathered_cut_copper_stairs_from_waxed_weathered_cut_copper_stonecutting.json
+ waxed_weathered_cut_copper_stairs.json
+ waxed_weathered_cut_copper.json
+ weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_slab_from_weathered_cut_copper_stonecutting.json
+ weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ weathered_cut_copper_stairs_from_weathered_cut_copper_stonecutting.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.azalea_leaves_flowers: Flowering Azalea Leaves
+ block.minecraft.azalea_leaves: Azalea Leaves
+ block.minecraft.azalea: Azalea
+ block.minecraft.big_dripleaf_stem: Big Dripleaf Stem
+ block.minecraft.big_dripleaf: Big Dripleaf
+ block.minecraft.cave_vines_body: Cave Vines
+ block.minecraft.cave_vines_head: Cave Vines
+ block.minecraft.exposed_copper_block: Exposed Copper Block
+ block.minecraft.exposed_cut_copper_slab: Exposed Cut Copper Slab
+ block.minecraft.exposed_cut_copper_stairs: Exposed Cut Copper Stairs
+ block.minecraft.exposed_cut_copper: Exposed Cut Copper
+ block.minecraft.flowering_azalea: Flowering Azalea
+ block.minecraft.hanging_roots: Hanging Roots
- block.minecraft.lightly_weathered_copper_block: Lightly Weathered Copper Block
- block.minecraft.lightly_weathered_cut_copper_slab: Lightly Weathered Cut Copper Slab
- block.minecraft.lightly_weathered_cut_copper_stairs: Lightly Weathered Cut Copper Stairs
- block.minecraft.lightly_weathered_cut_copper: Lightly Weathered Cut Copper
+ block.minecraft.moss_block: Moss Block
+ block.minecraft.moss_carpet: Moss Carpet
+ block.minecraft.oxidized_copper_block: Oxidized Copper Block
+ block.minecraft.oxidized_cut_copper_slab: Oxidized Cut Copper Slab
+ block.minecraft.oxidized_cut_copper_stairs: Oxidized Cut Copper Stairs
+ block.minecraft.oxidized_cut_copper: Oxidized Cut Copper
+ block.minecraft.rooted_dirt: Rooted Dirt
- block.minecraft.semi_weathered_copper_block: Semi-Weathered Copper Block
- block.minecraft.semi_weathered_cut_copper_slab: Semi Weathered Cut Copper Slab
- block.minecraft.semi_weathered_cut_copper_stairs: Semi-Weathered Cut Copper Stairs
- block.minecraft.semi_weathered_cut_copper: Semi-Weathered Cut Copper
+ block.minecraft.small_dripleaf: Small Dripleaf
+ block.minecraft.spore_blossom: Spore Blossom
+ block.minecraft.waxed_exposed_copper_block: Waxed Exposed Copper Block
+ block.minecraft.waxed_exposed_copper: Waxed Exposed Copper
+ block.minecraft.waxed_exposed_cut_copper_slab: Waxed Exposed Cut Copper Slab
+ block.minecraft.waxed_exposed_cut_copper_stairs: Waxed Exposed Cut Copper Stairs
+ block.minecraft.waxed_exposed_cut_copper: Waxed Exposed Cut Copper
- block.minecraft.waxed_lightly_weathered_copper_block: Waxed Lightly Weathered Copper Block
- block.minecraft.waxed_lightly_weathered_copper: Waxed Lightly Weathered Copper
- block.minecraft.waxed_lightly_weathered_cut_copper_slab: Waxed Lightly Weathered Cut Copper Slab
- block.minecraft.waxed_lightly_weathered_cut_copper_stairs: Waxed Lightly Weathered Cut Copper Stairs
- block.minecraft.waxed_lightly_weathered_cut_copper: Waxed Lightly Weathered Cut Copper
- block.minecraft.waxed_semi_weathered_copper_block: Waxed Semi-Weathered Copper Block
- block.minecraft.waxed_semi_weathered_copper: Waxed Semi-Weathered Copper
- block.minecraft.waxed_semi_weathered_cut_copper_slab: Waxed Semi Weathered Cut Copper Slab
- block.minecraft.waxed_semi_weathered_cut_copper_stairs: Waxed Semi-Weathered Cut Copper Stairs
- block.minecraft.waxed_semi_weathered_cut_copper: Waxed Semi-Weathered Cut Copper
+ block.minecraft.waxed_weathered_copper_block: Waxed Weathered Copper Block
+ block.minecraft.waxed_weathered_copper: Waxed Weathered Copper
+ block.minecraft.waxed_weathered_cut_copper_slab: Waxed Weathered Cut Copper Slab
+ block.minecraft.waxed_weathered_cut_copper_stairs: Waxed Weathered Cut Copper Stairs
+ block.minecraft.waxed_weathered_cut_copper: Waxed Weathered Cut Copper
+ item.minecraft.glow_berries: Glow Berries
+ subtitles.block.big_dripleaf.tilt_down: Dripleaf tilts down
+ subtitles.block.big_dripleaf.tilt_up: Dripleaf tilts up
+ subtitles.entity.skeleton.converted_to_stray: Skeleton converts to Stray
+ tutorial.bundleInsert.description: Right Click to add items
+ tutorial.bundleInsert.title: Use a Bundle
```

</details>
<details>
<summary>
Changes
</summary>

```
block.minecraft.weathered_copper_block: Weathered Copper BlocKk
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/cut_copper_from_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_slab_from_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_slab_from_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_stairs_from_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/cut_copper_stairs_from_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_slab_from_exposed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_stairs_from_exposed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/exposed_cut_copper.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/lightly_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_slab_from_oxidized_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_stairs_from_oxidized_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/oxidized_cut_copper.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/semi_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_from_waxed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_slab_from_waxed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_cut_copper_stairs_from_waxed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_from_waxed_exposed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_slab_from_waxed_exposed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_slab_from_waxed_exposed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_stairs_from_waxed_exposed_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_stairs_from_waxed_exposed_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_exposed_cut_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/waxed_lightly_weathered_cut_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_copper.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_slab.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/advancements/recipes/building_blocks/waxed_semi_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_copper.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_from_waxed_weathered_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_slab_from_waxed_weathered_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_slab_from_waxed_weathered_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_slab.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_stairs_from_waxed_weathered_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_stairs_from_waxed_weathered_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper_stairs.json
+ minecraft/advancements/recipes/building_blocks/waxed_weathered_cut_copper.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_slab_from_weathered_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ minecraft/advancements/recipes/building_blocks/weathered_cut_copper_stairs_from_weathered_cut_copper_stonecutting.json
+ minecraft/advancements/recipes/decorations/moss_carpet.json
+ minecraft/loot_tables/blocks/azalea_leaves_flowers.json
+ minecraft/loot_tables/blocks/azalea_leaves.json
+ minecraft/loot_tables/blocks/azalea.json
+ minecraft/loot_tables/blocks/big_dripleaf_stem.json
+ minecraft/loot_tables/blocks/big_dripleaf.json
+ minecraft/loot_tables/blocks/cave_vines_body.json
+ minecraft/loot_tables/blocks/cave_vines_head.json
+ minecraft/loot_tables/blocks/exposed_copper_block.json
+ minecraft/loot_tables/blocks/exposed_cut_copper_slab.json
+ minecraft/loot_tables/blocks/exposed_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/exposed_cut_copper.json
+ minecraft/loot_tables/blocks/flowering_azalea.json
+ minecraft/loot_tables/blocks/hanging_roots.json
- minecraft/loot_tables/blocks/lightly_weathered_copper_block.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/lightly_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/moss_block.json
+ minecraft/loot_tables/blocks/moss_carpet.json
+ minecraft/loot_tables/blocks/oxidized_copper_block.json
+ minecraft/loot_tables/blocks/oxidized_cut_copper_slab.json
+ minecraft/loot_tables/blocks/oxidized_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/oxidized_cut_copper.json
+ minecraft/loot_tables/blocks/rooted_dirt.json
- minecraft/loot_tables/blocks/semi_weathered_copper_block.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/semi_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/small_dripleaf.json
+ minecraft/loot_tables/blocks/spore_blossom.json
+ minecraft/loot_tables/blocks/waxed_exposed_copper.json
+ minecraft/loot_tables/blocks/waxed_exposed_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_exposed_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_exposed_cut_copper.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_copper.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/waxed_lightly_weathered_cut_copper.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_copper.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_slab.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/loot_tables/blocks/waxed_semi_weathered_cut_copper.json
+ minecraft/loot_tables/blocks/waxed_weathered_copper.json
+ minecraft/loot_tables/blocks/waxed_weathered_cut_copper_slab.json
+ minecraft/loot_tables/blocks/waxed_weathered_cut_copper_stairs.json
+ minecraft/loot_tables/blocks/waxed_weathered_cut_copper.json
+ minecraft/recipes/cut_copper_from_copper_block_stonecutting.json
+ minecraft/recipes/cut_copper_slab_from_copper_block_stonecutting.json
+ minecraft/recipes/cut_copper_slab_from_cut_copper_stonecutting.json
+ minecraft/recipes/cut_copper_stairs_from_copper_block_stonecutting.json
+ minecraft/recipes/cut_copper_stairs_from_cut_copper_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_slab_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_slab_from_exposed_cut_copper_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_slab.json
+ minecraft/recipes/exposed_cut_copper_stairs_from_exposed_copper_block_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_stairs_from_exposed_cut_copper_stonecutting.json
+ minecraft/recipes/exposed_cut_copper_stairs.json
+ minecraft/recipes/exposed_cut_copper.json
- minecraft/recipes/lightly_weathered_cut_copper_slab.json
- minecraft/recipes/lightly_weathered_cut_copper_stairs.json
- minecraft/recipes/lightly_weathered_cut_copper.json
+ minecraft/recipes/moss_carpet.json
+ minecraft/recipes/oxidized_cut_copper_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_slab_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_slab_from_oxidized_cut_copper_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_slab.json
+ minecraft/recipes/oxidized_cut_copper_stairs_from_oxidized_copper_block_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_stairs_from_oxidized_cut_copper_stonecutting.json
+ minecraft/recipes/oxidized_cut_copper_stairs.json
+ minecraft/recipes/oxidized_cut_copper.json
- minecraft/recipes/semi_weathered_cut_copper_slab.json
- minecraft/recipes/semi_weathered_cut_copper_stairs.json
- minecraft/recipes/semi_weathered_cut_copper.json
+ minecraft/recipes/waxed_cut_copper_from_waxed_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_slab_from_waxed_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_slab_from_waxed_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_stairs_from_waxed_copper_stonecutting.json
+ minecraft/recipes/waxed_cut_copper_stairs_from_waxed_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_copper.json
+ minecraft/recipes/waxed_exposed_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_cut_copper_from_waxed_exposed_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_cut_copper_slab_from_waxed_exposed_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_cut_copper_slab_from_waxed_exposed_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_cut_copper_slab.json
+ minecraft/recipes/waxed_exposed_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_exposed_cut_copper_stairs_from_waxed_exposed_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_cut_copper_stairs_from_waxed_exposed_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_exposed_cut_copper_stairs.json
+ minecraft/recipes/waxed_exposed_cut_copper.json
- minecraft/recipes/waxed_lightly_weathered_copper.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/recipes/waxed_lightly_weathered_cut_copper.json
- minecraft/recipes/waxed_semi_weathered_copper.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_slab_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_slab.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_stairs_from_honeycomb.json
- minecraft/recipes/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/recipes/waxed_semi_weathered_cut_copper.json
+ minecraft/recipes/waxed_weathered_copper.json
+ minecraft/recipes/waxed_weathered_cut_copper_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_cut_copper_from_waxed_weathered_copper_stonecutting.json
+ minecraft/recipes/waxed_weathered_cut_copper_slab_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_cut_copper_slab_from_waxed_weathered_copper_stonecutting.json
+ minecraft/recipes/waxed_weathered_cut_copper_slab_from_waxed_weathered_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_weathered_cut_copper_slab.json
+ minecraft/recipes/waxed_weathered_cut_copper_stairs_from_honeycomb.json
+ minecraft/recipes/waxed_weathered_cut_copper_stairs_from_waxed_weathered_copper_stonecutting.json
+ minecraft/recipes/waxed_weathered_cut_copper_stairs_from_waxed_weathered_cut_copper_stonecutting.json
+ minecraft/recipes/waxed_weathered_cut_copper_stairs.json
+ minecraft/recipes/waxed_weathered_cut_copper.json
+ minecraft/recipes/weathered_cut_copper_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_slab_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_slab_from_weathered_cut_copper_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_stairs_from_weathered_copper_block_stonecutting.json
+ minecraft/recipes/weathered_cut_copper_stairs_from_weathered_cut_copper_stonecutting.json
+ minecraft/tags/blocks/azalea_log_replaceable.json
+ minecraft/tags/blocks/cave_vines.json
+ minecraft/tags/blocks/lush_plants_replaceable.json
+ minecraft/tags/game_events/ignore_vibrations_sneaking.json
- minecraft/tags/game_events/ignore_vibrations_stepping_carefully.json
+ minecraft/tags/items/fox_food.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/azalea_leaves_flowers.json
+ minecraft/blockstates/azalea_leaves.json
+ minecraft/blockstates/azalea.json
+ minecraft/blockstates/big_dripleaf_stem.json
+ minecraft/blockstates/big_dripleaf.json
+ minecraft/blockstates/cave_vines_body.json
+ minecraft/blockstates/cave_vines_head.json
+ minecraft/blockstates/exposed_copper_block.json
+ minecraft/blockstates/exposed_cut_copper_slab.json
+ minecraft/blockstates/exposed_cut_copper_stairs.json
+ minecraft/blockstates/exposed_cut_copper.json
+ minecraft/blockstates/flowering_azalea.json
+ minecraft/blockstates/hanging_roots.json
- minecraft/blockstates/lightly_weathered_copper_block.json
- minecraft/blockstates/lightly_weathered_cut_copper_slab.json
- minecraft/blockstates/lightly_weathered_cut_copper_stairs.json
- minecraft/blockstates/lightly_weathered_cut_copper.json
+ minecraft/blockstates/moss_block.json
+ minecraft/blockstates/moss_carpet.json
+ minecraft/blockstates/oxidized_copper_block.json
+ minecraft/blockstates/oxidized_cut_copper_slab.json
+ minecraft/blockstates/oxidized_cut_copper_stairs.json
+ minecraft/blockstates/oxidized_cut_copper.json
+ minecraft/blockstates/rooted_dirt.json
- minecraft/blockstates/semi_weathered_copper_block.json
- minecraft/blockstates/semi_weathered_cut_copper_slab.json
- minecraft/blockstates/semi_weathered_cut_copper_stairs.json
- minecraft/blockstates/semi_weathered_cut_copper.json
+ minecraft/blockstates/small_dripleaf.json
+ minecraft/blockstates/spore_blossom.json
+ minecraft/blockstates/waxed_exposed_copper.json
+ minecraft/blockstates/waxed_exposed_cut_copper_slab.json
+ minecraft/blockstates/waxed_exposed_cut_copper_stairs.json
+ minecraft/blockstates/waxed_exposed_cut_copper.json
- minecraft/blockstates/waxed_lightly_weathered_copper.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/blockstates/waxed_lightly_weathered_cut_copper.json
- minecraft/blockstates/waxed_semi_weathered_copper.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper_slab.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/blockstates/waxed_semi_weathered_cut_copper.json
+ minecraft/blockstates/waxed_weathered_copper.json
+ minecraft/blockstates/waxed_weathered_cut_copper_slab.json
+ minecraft/blockstates/waxed_weathered_cut_copper_stairs.json
+ minecraft/blockstates/waxed_weathered_cut_copper.json
+ minecraft/models/block/azalea_leaves_flowers.json
+ minecraft/models/block/azalea_leaves.json
+ minecraft/models/block/azalea.json
+ minecraft/models/block/big_dripleaf_full_tilt.json
+ minecraft/models/block/big_dripleaf_partial_tilt.json
+ minecraft/models/block/big_dripleaf_stem.json
+ minecraft/models/block/big_dripleaf.json
+ minecraft/models/block/cave_vines_body_lit.json
+ minecraft/models/block/cave_vines_body.json
+ minecraft/models/block/cave_vines_head_lit.json
+ minecraft/models/block/cave_vines_head.json
+ minecraft/models/block/exposed_copper_block.json
+ minecraft/models/block/exposed_cut_copper_slab_top.json
+ minecraft/models/block/exposed_cut_copper_slab.json
+ minecraft/models/block/exposed_cut_copper_stairs_inner.json
+ minecraft/models/block/exposed_cut_copper_stairs_outer.json
+ minecraft/models/block/exposed_cut_copper_stairs.json
+ minecraft/models/block/exposed_cut_copper.json
+ minecraft/models/block/flowering_azalea.json
+ minecraft/models/block/hanging_roots.json
- minecraft/models/block/lightly_weathered_copper_block.json
- minecraft/models/block/lightly_weathered_cut_copper_slab_top.json
- minecraft/models/block/lightly_weathered_cut_copper_slab.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs_inner.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs_outer.json
- minecraft/models/block/lightly_weathered_cut_copper_stairs.json
- minecraft/models/block/lightly_weathered_cut_copper.json
+ minecraft/models/block/moss_block.json
+ minecraft/models/block/moss_carpet.json
+ minecraft/models/block/oxidized_copper_block.json
+ minecraft/models/block/oxidized_cut_copper_slab_top.json
+ minecraft/models/block/oxidized_cut_copper_slab.json
+ minecraft/models/block/oxidized_cut_copper_stairs_inner.json
+ minecraft/models/block/oxidized_cut_copper_stairs_outer.json
+ minecraft/models/block/oxidized_cut_copper_stairs.json
+ minecraft/models/block/oxidized_cut_copper.json
+ minecraft/models/block/rooted_dirt.json
- minecraft/models/block/semi_weathered_copper_block.json
- minecraft/models/block/semi_weathered_cut_copper_slab_top.json
- minecraft/models/block/semi_weathered_cut_copper_slab.json
- minecraft/models/block/semi_weathered_cut_copper_stairs_inner.json
- minecraft/models/block/semi_weathered_cut_copper_stairs_outer.json
- minecraft/models/block/semi_weathered_cut_copper_stairs.json
- minecraft/models/block/semi_weathered_cut_copper.json
+ minecraft/models/block/small_dripleaf_bottom.json
+ minecraft/models/block/small_dripleaf_top.json
+ minecraft/models/block/spore_blossom.json
+ minecraft/models/block/template_azalea.json
+ minecraft/models/item/azalea_leaves_flowers.json
+ minecraft/models/item/azalea_leaves.json
+ minecraft/models/item/azalea.json
+ minecraft/models/item/big_dripleaf.json
+ minecraft/models/item/exposed_copper_block.json
+ minecraft/models/item/exposed_cut_copper_slab.json
+ minecraft/models/item/exposed_cut_copper_stairs.json
+ minecraft/models/item/exposed_cut_copper.json
+ minecraft/models/item/flowering_azalea.json
+ minecraft/models/item/glow_berries.json
+ minecraft/models/item/hanging_roots.json
- minecraft/models/item/lightly_weathered_copper_block.json
- minecraft/models/item/lightly_weathered_cut_copper_slab.json
- minecraft/models/item/lightly_weathered_cut_copper_stairs.json
- minecraft/models/item/lightly_weathered_cut_copper.json
+ minecraft/models/item/moss_block.json
+ minecraft/models/item/moss_carpet.json
+ minecraft/models/item/oxidized_copper_block.json
+ minecraft/models/item/oxidized_cut_copper_slab.json
+ minecraft/models/item/oxidized_cut_copper_stairs.json
+ minecraft/models/item/oxidized_cut_copper.json
+ minecraft/models/item/rooted_dirt.json
- minecraft/models/item/semi_weathered_copper_block.json
- minecraft/models/item/semi_weathered_cut_copper_slab.json
- minecraft/models/item/semi_weathered_cut_copper_stairs.json
- minecraft/models/item/semi_weathered_cut_copper.json
+ minecraft/models/item/small_dripleaf.json
+ minecraft/models/item/spore_blossom.json
+ minecraft/models/item/waxed_exposed_copper.json
+ minecraft/models/item/waxed_exposed_cut_copper_slab.json
+ minecraft/models/item/waxed_exposed_cut_copper_stairs.json
+ minecraft/models/item/waxed_exposed_cut_copper.json
- minecraft/models/item/waxed_lightly_weathered_copper.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper_slab.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper_stairs.json
- minecraft/models/item/waxed_lightly_weathered_cut_copper.json
- minecraft/models/item/waxed_semi_weathered_copper.json
- minecraft/models/item/waxed_semi_weathered_cut_copper_slab.json
- minecraft/models/item/waxed_semi_weathered_cut_copper_stairs.json
- minecraft/models/item/waxed_semi_weathered_cut_copper.json
+ minecraft/models/item/waxed_weathered_copper.json
+ minecraft/models/item/waxed_weathered_cut_copper_slab.json
+ minecraft/models/item/waxed_weathered_cut_copper_stairs.json
+ minecraft/models/item/waxed_weathered_cut_copper.json
+ minecraft/particles/falling_spore_blossom.json
+ minecraft/particles/spore_blossom_air.json
+ minecraft/textures/block/azalea_leaves_flowers.png
+ minecraft/textures/block/azalea_leaves.png
+ minecraft/textures/block/azalea_plant.png
+ minecraft/textures/block/azalea_side.png
+ minecraft/textures/block/azalea_top.png
+ minecraft/textures/block/big_dripleaf_side.png
+ minecraft/textures/block/big_dripleaf_stem.png
+ minecraft/textures/block/big_dripleaf_tip.png
+ minecraft/textures/block/big_dripleaf_top.png
+ minecraft/textures/block/cave_vines_body_lit.png
+ minecraft/textures/block/cave_vines_body.png
+ minecraft/textures/block/cave_vines_head_lit.png
+ minecraft/textures/block/cave_vines_head.png
+ minecraft/textures/block/exposed_copper_block.png
+ minecraft/textures/block/exposed_cut_copper.png
+ minecraft/textures/block/flowering_azalea_side.png
+ minecraft/textures/block/flowering_azalea_top.png
+ minecraft/textures/block/hanging_roots.png
- minecraft/textures/block/lightly_weathered_copper_block.png
- minecraft/textures/block/lightly_weathered_cut_copper.png
+ minecraft/textures/block/moss_block.png
+ minecraft/textures/block/oxidized_copper_block.png
+ minecraft/textures/block/oxidized_cut_copper.png
+ minecraft/textures/block/root_vines_head.png
+ minecraft/textures/block/rooted_dirt.png
- minecraft/textures/block/semi_weathered_copper_block.png
- minecraft/textures/block/semi_weathered_cut_copper.png
+ minecraft/textures/block/small_dripleaf_side.png
+ minecraft/textures/block/small_dripleaf_top.png
+ minecraft/textures/block/spore_blossom_base.png
+ minecraft/textures/block/spore_blossom.png
+ minecraft/textures/item/glow_berries.png
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
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BitStorageAlignFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
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
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GossipUUIDFix
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenameBiomesFix
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.SwimStatsRenameFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1460$1
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.UniformFloat
+ net.minecraft.util.UniformInt
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
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
+ net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.RandomSwim
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
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
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
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
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
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
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HostilesSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
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
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.axolotl.Axolotl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
- net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
+ net.minecraft.world.entity.animal.axolotl.AxolotlAi
- net.minecraft.world.entity.animal.axolotl.package-info
- net.minecraft.world.entity.animal.axolotl.PlayDead
+ net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Bucketable
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
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
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$1
- net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
+ net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
- net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
+ net.minecraft.world.entity.animal.horse.Markings
- net.minecraft.world.entity.animal.horse.Mule
+ net.minecraft.world.entity.animal.horse.package-info
+ net.minecraft.world.entity.animal.horse.SkeletonHorse
- net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
+ net.minecraft.world.entity.animal.horse.TraderLlama
- net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ net.minecraft.world.entity.animal.horse.Variant
- net.minecraft.world.entity.animal.horse.ZombieHorse
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
- net.minecraft.world.entity.animal.package-info
- net.minecraft.world.entity.animal.Panda
+ net.minecraft.world.entity.animal.Panda$Gene
- net.minecraft.world.entity.animal.Panda$PandaAttackGoal
+ net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
- net.minecraft.world.entity.animal.Panda$PandaBreedGoal
+ net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
- net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
+ net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
- net.minecraft.world.entity.animal.Panda$PandaMoveControl
+ net.minecraft.world.entity.animal.Panda$PandaPanicGoal
- net.minecraft.world.entity.animal.Panda$PandaRollGoal
+ net.minecraft.world.entity.animal.Panda$PandaSitGoal
- net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
+ net.minecraft.world.entity.animal.Parrot
- net.minecraft.world.entity.animal.Parrot$1
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$1
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$1
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$1
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
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
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
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
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
+ net.minecraft.world.entity.monster.Evoker$1
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$1
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$1
+ net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
+ net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$1
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
+ net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
- net.minecraft.world.entity.monster.Witch
+ net.minecraft.world.entity.monster.WitherSkeleton
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
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
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$1
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
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
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
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
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
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
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$1
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleRecipeSerializer
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$1
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
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
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$1
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$1
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CaveVinesBlock
- net.minecraft.world.level.block.CaveVinesHeadBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
+ net.minecraft.world.level.block.ChangeOverTimeSlabBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
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
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
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
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.LanternBlock
+ net.minecraft.world.level.block.LavaCauldronBlock
- net.minecraft.world.level.block.LayeredCauldronBlock
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
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
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$1
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SculkSensorPhase
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.properties.Tilt
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ChunkTickList$1
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$1
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Decoratable
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
+ net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
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
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.GlowLichenFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JigsawFeature
- net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$1
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
+ net.minecraft.world.level.levelgen.feature.StructureFeature
- net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
+ net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.GeodeBlockSettings
+ net.minecraft.world.level.levelgen.GeodeCrackSettings
- net.minecraft.world.level.levelgen.GeodeLayerSettings
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountDecorator
+ net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.DecorationContext
+ net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
- net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
+ net.minecraft.world.level.levelgen.placement.EdgeDecorator
- net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.FeatureDecorator
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.HeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
+ net.minecraft.world.level.levelgen.placement.nether.FireDecorator
- net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.RangeDecorator
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.Spread32Decorator
+ net.minecraft.world.level.levelgen.placement.SquareDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
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
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.SectionPos +2M
```
```
XXX.core.particles.ParticleTypes +2P
```
```
XXX.data.loot.BlockLoot +4M -1M
```
```
XXX.data.models.BlockModelGenerators +5M -1M
```
```
XXX.minecraft.tags.GameEventTags +1P -1P
```
```
XXX.minecraft.util.LazyLoadedValue -1P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.level.block.GrowingPlantHeadBlock +2M
```
```
XXX.level.block.MultifaceBlock -1M
```
```
XXX.level.chunk.ChunkGenerator +3M -3M | +2P -2P
```
```
XXX.level.entity.EntitySectionStorage -1M
```
```
XXX.level.levelgen.WorldgenRandom +2M -1M | +1P
```
```
XXX.levelgen.feature.AbstractHugeMushroomFeature +1M -2M
```
```
XXX.levelgen.feature.BasaltColumnsFeature +1M -2M
```
```
XXX.levelgen.feature.BaseDiskFeature +1M -2M
```
```
XXX.levelgen.feature.BlockBlobFeature +1M -2M
```
```
XXX.levelgen.feature.BlueIceFeature +1M -2M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +2M -2M
```
```
XXX.levelgen.feature.ChorusPlantFeature +1M -2M
```
```
XXX.levelgen.feature.ConfiguredStructureFeature +1M -1M
```
```
XXX.levelgen.feature.CoralFeature +1M -2M
```
```
XXX.levelgen.feature.DesertWellFeature +1M -2M
```
```
XXX.levelgen.feature.DripstoneClusterFeature +1M -2M
```
```
XXX.levelgen.feature.EndCityFeature +4M -4M
```
```
XXX.levelgen.feature.EndGatewayFeature +1M -2M
```
```
XXX.levelgen.feature.EndPodiumFeature +1M -2M
```
```
XXX.levelgen.synth.ImprovedNoise +5M -2M
```
```
XXX.levelgen.synth.PerlinNoise +6M -6M
```
```
XXX.levelgen.synth.SimplexNoise +1M -1M
```
```
XXX.phys.shapes.VoxelShape +2M
```

</details>

















































































































































































<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- long asLong(BlockPos)
- SectionPos bottomOf(ChunkAccess)
```

</details>








































<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder createCaveVinesDrop(Block)
- LootTable$Builder lambda$accept$74(Block)
- LootTable$Builder lambda$accept$75(Block)
+ LootTable$Builder lambda$dropPottedContents$74(Block)
- LootTable$Builder lambda$dropPottedContents$76(Block)
```

</details>



<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- void createAzalea(Block)
- void createBigDripLeafBlock()
- void createCaveVines()
- void createFullAndCarpetBlocks(Block,Block)
- void createSmallDripleaf()
+ void createWoolBlocks(Block,Block)
```

</details>


























































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- double smoothstepDerivative(double)
```

</details>























































































































<details>
<summary>
net.minecraft.world.level.block.GrowingPlantHeadBlock
</summary>

```diff
- BlockState getGrowIntoState(BlockState,Random)
- BlockState updateBodyAfterConvertedFromHead(BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.MultifaceBlock
</summary>

```diff
+ ImmutableMap getShapes(StateDefinition)
```

</details>





























































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
- int getFirstFreeHeight(int,int,Heightmap$Types,LevelHeightAccessor)
+ int getFirstFreeHeight(int,int,Heightmap$Types)
- int getFirstOccupiedHeight(int,int,Heightmap$Types,LevelHeightAccessor)
+ int getFirstOccupiedHeight(int,int,Heightmap$Types)
- void createStructure(ConfiguredStructureFeature,RegistryAccess,StructureFeatureManager,ChunkAccess,StructureManager,long,Biome)
+ void createStructure(ConfiguredStructureFeature,RegistryAccess,StructureFeatureManager,ChunkAccess,StructureManager,long,ChunkPos,Biome)
```

</details>





































<details>
<summary>
net.minecraft.world.level.entity.EntitySectionStorage
</summary>

```diff
+ long entityPosToSectionKey(BlockPos)
```

</details>



















<details>
<summary>
net.minecraft.world.level.levelgen.WorldgenRandom
</summary>

```diff
- int getCount()
- int next(int)
+ void consumeCount(int)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,HugeMushroomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ColumnFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BaseDiskFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,DiskConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockBlobFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,BlockStateConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlueIceFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,ProbabilityFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
</summary>

```diff
- StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,Biome,int,StructureFeatureConfiguration,LevelHeightAccessor)
+ StructureStart generate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,Biome,int,StructureFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.CoralFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertWellFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,DripstoneClusterConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
- int access$000(int,int,ChunkGenerator,LevelHeightAccessor)
+ int access$000(int,int,ChunkGenerator)
- int getYPositionForFeature(int,int,ChunkGenerator,LevelHeightAccessor)
+ int getYPositionForFeature(int,int,ChunkGenerator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndGatewayFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,EndGatewayConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndPodiumFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.ImprovedNoise
</summary>

```diff
- double noise(double,double,double)
- double noiseWithDerivative(double,double,double,double[])
+ double sampleAndLerp(int,int,int,double,double,double,double,double,double)
- double sampleAndLerp(int,int,int,double,double,double,double)
- double sampleWithDerivative(int,int,int,double,double,double,double[])
+ void <init>(Random)
- void <init>(RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.PerlinNoise
</summary>

```diff
- PerlinNoise create(RandomSource,int,double[])
- PerlinNoise create(RandomSource,int,DoubleList)
+ PerlinNoise create(WorldgenRandom,int,double[])
+ PerlinNoise create(WorldgenRandom,int,DoubleList)
- void <init>(RandomSource,IntSortedSet)
- void <init>(RandomSource,IntStream)
- void <init>(RandomSource,List)
- void <init>(RandomSource,Pair)
+ void <init>(WorldgenRandom,IntSortedSet)
+ void <init>(WorldgenRandom,IntStream)
+ void <init>(WorldgenRandom,List)
+ void <init>(WorldgenRandom,Pair)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.SimplexNoise
</summary>

```diff
+ void <init>(Random)
- void <init>(RandomSource)
```

</details>













































































































































































































































<details>
<summary>
net.minecraft.world.phys.shapes.VoxelShape
</summary>

```diff
- Optional closestPointTo(Vec3)
- void lambda$closestPointTo$5(Vec3,Vec3[],double,double,double,double,double,double)
```

</details>






<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$1
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
+ net.minecraft.client.gui.chat.ChatListener
- net.minecraft.client.gui.chat.NarratorChatListener
+ net.minecraft.client.gui.chat.OverlayChatListener
+ net.minecraft.client.gui.chat.package-info
- net.minecraft.client.gui.chat.StandardChatListener
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractOptionSliderButton
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$SelectionDirection
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.Button
+ net.minecraft.client.gui.components.Button$OnPress
- net.minecraft.client.gui.components.Button$OnTooltip
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$1
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$1
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$TooltipSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LerpingBossEvent$1
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
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$1
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.SliderButton
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.StateSwitchingButton
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TickableWidget
+ net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$1
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
+ net.minecraft.client.gui.components.TooltipAccessor
- net.minecraft.client.gui.components.VolumeSlider
+ net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.Font
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$1
+ net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.glyphs.BakedGlyph
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
- net.minecraft.client.gui.font.glyphs.MissingGlyph
- net.minecraft.client.gui.font.glyphs.package-info
+ net.minecraft.client.gui.font.glyphs.WhiteGlyph
+ net.minecraft.client.gui.font.package-info
- net.minecraft.client.gui.font.providers.BitmapProvider
+ net.minecraft.client.gui.font.providers.BitmapProvider$1
- net.minecraft.client.gui.font.providers.BitmapProvider$Builder
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.GlyphProviderBuilder
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
- net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.GuiComponent
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$1
- net.minecraft.client.gui.MapRenderer$MapInstance
- net.minecraft.client.gui.package-info
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
+ net.minecraft.client.gui.screens.achievement.package-info
+ net.minecraft.client.gui.screens.achievement.StatsScreen
- net.minecraft.client.gui.screens.achievement.StatsScreen$1
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
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
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.ChatOptionsScreen
- net.minecraft.client.gui.screens.ChatScreen
+ net.minecraft.client.gui.screens.ChatScreen$1
- net.minecraft.client.gui.screens.ConfirmLinkScreen
+ net.minecraft.client.gui.screens.ConfirmScreen
- net.minecraft.client.gui.screens.ConnectScreen
+ net.minecraft.client.gui.screens.ConnectScreen$1
+ net.minecraft.client.gui.screens.controls.ControlList
- net.minecraft.client.gui.screens.controls.ControlList$1
+ net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
- net.minecraft.client.gui.screens.controls.ControlList$Entry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
- net.minecraft.client.gui.screens.controls.ControlsScreen
+ net.minecraft.client.gui.screens.controls.package-info
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- net.minecraft.client.gui.screens.DatapackLoadFailureScreen
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AnvilScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen$1
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
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
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingOverlay
- net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.mco.package-info
+ net.minecraft.client.gui.screens.MenuScreens
- net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
+ net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.SafetyScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.package-info
+ net.minecraft.client.gui.screens.packs.package-info
- net.minecraft.client.gui.screens.packs.PackSelectionModel
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen
- net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList
- net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PopupScreen
- net.minecraft.client.gui.screens.PopupScreen$ButtonOption
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.GhostRecipe
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ net.minecraft.client.gui.screens.recipebook.package-info
- net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.RecipeBookPage
- net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
+ net.minecraft.client.gui.screens.recipebook.RecipeButton
- net.minecraft.client.gui.screens.recipebook.RecipeCollection
+ net.minecraft.client.gui.screens.recipebook.RecipeShownListener
- net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
+ net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SimpleOptionsSubScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.social.package-info
- net.minecraft.client.gui.screens.social.PlayerEntry
+ net.minecraft.client.gui.screens.social.PlayerEntry$1
- net.minecraft.client.gui.screens.social.PlayerEntry$2
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.stream.package-info
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$OperationFailedException
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
- net.minecraft.client.gui.screens.worldselection.EditWorldScreen
+ net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
- net.minecraft.client.gui.screens.worldselection.package-info
- net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
- net.minecraft.client.gui.screens.worldselection.WorldPreset
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$1
- net.minecraft.client.gui.screens.worldselection.WorldPreset$2
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$3
- net.minecraft.client.gui.screens.worldselection.WorldPreset$4
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$5
- net.minecraft.client.gui.screens.worldselection.WorldPreset$6
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$7
- net.minecraft.client.gui.screens.worldselection.WorldPreset$8
+ net.minecraft.client.gui.screens.worldselection.WorldPreset$PresetEditor
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
- net.minecraft.client.gui.spectator.categories.package-info
- net.minecraft.client.gui.spectator.categories.SpectatorPage
+ net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ net.minecraft.client.gui.spectator.package-info
+ net.minecraft.client.gui.spectator.PlayerMenuItem
- net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenu
- net.minecraft.client.gui.spectator.SpectatorMenu$1
+ net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
- net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuListener
- net.minecraft.client.main.GameConfig
+ net.minecraft.client.main.GameConfig$FolderData
- net.minecraft.client.main.GameConfig$GameData
+ net.minecraft.client.main.GameConfig$ServerData
- net.minecraft.client.main.GameConfig$UserData
+ net.minecraft.client.main.Main
- net.minecraft.client.main.Main$1
+ net.minecraft.client.main.Main$2
- net.minecraft.client.main.Main$3
- net.minecraft.client.main.package-info
+ net.minecraft.client.main.SilentInitException
+ net.minecraft.client.map.Map
- net.minecraft.client.map.Map$1
+ net.minecraft.client.map.Map$2
- net.minecraft.client.map.Map$3
+ net.minecraft.client.map.package-info
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
+ net.minecraft.client.model.dragon.DragonHeadModel
- net.minecraft.client.model.dragon.package-info
+ net.minecraft.client.model.DrownedModel
- net.minecraft.client.model.ElytraModel
+ net.minecraft.client.model.EndermanModel
- net.minecraft.client.model.EndermiteModel
+ net.minecraft.client.model.EntityModel
- net.minecraft.client.model.EvokerFangsModel
+ net.minecraft.client.model.FoxModel
- net.minecraft.client.model.geom.builders.CubeDefinition
+ net.minecraft.client.model.geom.builders.CubeDeformation
- net.minecraft.client.model.geom.builders.CubeListBuilder
+ net.minecraft.client.model.geom.builders.LayerDefinition
- net.minecraft.client.model.geom.builders.MaterialDefinition
+ net.minecraft.client.model.geom.builders.MeshDefinition
- net.minecraft.client.model.geom.builders.package-info
- net.minecraft.client.model.geom.builders.PartDefinition
+ net.minecraft.client.model.geom.builders.UVPair
+ net.minecraft.client.model.geom.EntityModelSet
- net.minecraft.client.model.geom.LayerDefinitions
+ net.minecraft.client.model.geom.ModelLayerLocation
- net.minecraft.client.model.geom.ModelLayers
+ net.minecraft.client.model.geom.ModelPart
- net.minecraft.client.model.geom.ModelPart$Cube
+ net.minecraft.client.model.geom.ModelPart$Polygon
- net.minecraft.client.model.geom.ModelPart$Vertex
+ net.minecraft.client.model.geom.ModelPart$Visitor
+ net.minecraft.client.model.geom.package-info
- net.minecraft.client.model.geom.PartNames
+ net.minecraft.client.model.geom.PartPose
- net.minecraft.client.model.GhastModel
+ net.minecraft.client.model.GiantZombieModel
- net.minecraft.client.model.GuardianModel
+ net.minecraft.client.model.HeadedModel
- net.minecraft.client.model.HierarchicalModel
+ net.minecraft.client.model.HoglinModel
- net.minecraft.client.model.HorseModel
+ net.minecraft.client.model.HumanoidModel
- net.minecraft.client.model.HumanoidModel$1
+ net.minecraft.client.model.HumanoidModel$ArmPose
- net.minecraft.client.model.IllagerModel
+ net.minecraft.client.model.IronGolemModel
- net.minecraft.client.model.LavaSlimeModel
+ net.minecraft.client.model.LeashKnotModel
- net.minecraft.client.model.ListModel
+ net.minecraft.client.model.LlamaModel
- net.minecraft.client.model.LlamaSpitModel
+ net.minecraft.client.model.MinecartModel
- net.minecraft.client.model.Model
+ net.minecraft.client.model.ModelUtils
- net.minecraft.client.model.OcelotModel
- net.minecraft.client.model.package-info
+ net.minecraft.client.model.PandaModel
- net.minecraft.client.model.ParrotModel
+ net.minecraft.client.model.ParrotModel$1
- net.minecraft.client.model.ParrotModel$State
+ net.minecraft.client.model.PhantomModel
+ net.minecraft.client.model.PiglinModel
- net.minecraft.client.model.PigModel
- net.minecraft.client.model.PlayerModel
+ net.minecraft.client.model.PolarBearModel
- net.minecraft.client.model.PufferfishBigModel
+ net.minecraft.client.model.PufferfishMidModel
- net.minecraft.client.model.PufferfishSmallModel
+ net.minecraft.client.model.QuadrupedModel
- net.minecraft.client.model.RabbitModel
+ net.minecraft.client.model.RavagerModel
- net.minecraft.client.model.SalmonModel
+ net.minecraft.client.model.SheepFurModel
- net.minecraft.client.model.SheepModel
+ net.minecraft.client.model.ShieldModel
- net.minecraft.client.model.ShulkerBulletModel
+ net.minecraft.client.model.ShulkerModel
- net.minecraft.client.model.SilverfishModel
+ net.minecraft.client.model.SkeletonModel
- net.minecraft.client.model.SkullModel
+ net.minecraft.client.model.SkullModelBase
- net.minecraft.client.model.SlimeModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.StriderModel
+ net.minecraft.client.model.TridentModel
- net.minecraft.client.model.TropicalFishModelA
+ net.minecraft.client.model.TropicalFishModelB
- net.minecraft.client.model.TurtleModel
+ net.minecraft.client.model.VexModel
- net.minecraft.client.model.VillagerHeadModel
+ net.minecraft.client.model.VillagerModel
- net.minecraft.client.model.WitchModel
+ net.minecraft.client.model.WitherBossModel
- net.minecraft.client.model.WolfModel
+ net.minecraft.client.model.ZombieModel
- net.minecraft.client.model.ZombieVillagerModel
+ net.minecraft.client.multiplayer.ClientAdvancements
- net.minecraft.client.multiplayer.ClientAdvancements$Listener
+ net.minecraft.client.multiplayer.ClientChunkCache
- net.minecraft.client.multiplayer.ClientChunkCache$1
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
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ServerAddress
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.ServerStatusPinger$2$1
- net.minecraft.client.Options$3
- net.minecraft.client.Options$FieldAccess
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$1
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BarrierParticle
- net.minecraft.client.particle.BarrierParticle$1
+ net.minecraft.client.particle.BarrierParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$1
+ net.minecraft.client.particle.BreakingItemParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
+ net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
- net.minecraft.client.particle.BubbleColumnUpParticle
+ net.minecraft.client.particle.BubbleColumnUpParticle$1
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$1
+ net.minecraft.client.particle.BubbleParticle$Provider
- net.minecraft.client.particle.BubblePopParticle
+ net.minecraft.client.particle.BubblePopParticle$1
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$1
+ net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
- net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
+ net.minecraft.client.particle.CritParticle
- net.minecraft.client.particle.CritParticle$1
+ net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
- net.minecraft.client.particle.CritParticle$MagicProvider
+ net.minecraft.client.particle.CritParticle$Provider
- net.minecraft.client.particle.DragonBreathParticle
+ net.minecraft.client.particle.DragonBreathParticle$1
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
- net.minecraft.client.particle.DripParticle$1
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
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$1
- net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
+ net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$1
+ net.minecraft.client.particle.TotemParticle$Provider
- net.minecraft.client.particle.TrackingEmitter
+ net.minecraft.client.particle.VibrationSignalParticle
- net.minecraft.client.particle.VibrationSignalParticle$1
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$1
- net.minecraft.client.particle.WakeParticle$Provider
+ net.minecraft.client.particle.WaterCurrentDownParticle
- net.minecraft.client.particle.WaterCurrentDownParticle$1
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
+ net.minecraft.client.ParticleStatus
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
- net.minecraft.client.ProgressOption
+ net.minecraft.client.RecipeBookCategories
- net.minecraft.client.RecipeBookCategories$1
- net.minecraft.client.renderer.banner.package-info
+ net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
- net.minecraft.client.renderer.block.model.BakedQuad
+ net.minecraft.client.renderer.block.model.BlockElement
- net.minecraft.client.renderer.block.model.BlockElement$1
+ net.minecraft.client.renderer.block.model.BlockElement$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementFace
+ net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
- net.minecraft.client.renderer.block.model.BlockElementRotation
+ net.minecraft.client.renderer.block.model.BlockFaceUV
- net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel
- net.minecraft.client.renderer.block.model.BlockModel$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModel$GuiLight
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
- net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
+ net.minecraft.client.renderer.block.model.FaceBakery
- net.minecraft.client.renderer.block.model.FaceBakery$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator
- net.minecraft.client.renderer.block.model.ItemModelGenerator$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
- net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
+ net.minecraft.client.renderer.block.model.ItemOverride
- net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
- net.minecraft.client.renderer.block.model.multipart.AndCondition
+ net.minecraft.client.renderer.block.model.multipart.Condition
- net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
+ net.minecraft.client.renderer.block.model.multipart.MultiPart
- net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.OrCondition
- net.minecraft.client.renderer.block.model.multipart.package-info
- net.minecraft.client.renderer.block.model.multipart.Selector
+ net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.MultiVariant
+ net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
+ net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.Variant
+ net.minecraft.client.renderer.block.model.Variant$Deserializer
+ net.minecraft.client.renderer.block.ModelBlockRenderer
- net.minecraft.client.renderer.block.ModelBlockRenderer$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
+ net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.block.statemap.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.EnchantTableRenderer
- net.minecraft.client.renderer.blockentity.LecternRenderer
+ net.minecraft.client.renderer.blockentity.package-info
+ net.minecraft.client.renderer.blockentity.PistonHeadRenderer
- net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
+ net.minecraft.client.renderer.blockentity.SkullBlockRenderer
- net.minecraft.client.renderer.blockentity.SpawnerRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
+ net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
- net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunkRegion
+ net.minecraft.client.renderer.chunk.VisGraph
- net.minecraft.client.renderer.chunk.VisGraph$1
+ net.minecraft.client.renderer.chunk.VisibilitySet
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
+ net.minecraft.client.renderer.culling.Frustum
- net.minecraft.client.renderer.culling.package-info
+ net.minecraft.client.renderer.debug.BeeDebugRenderer
- net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
- net.minecraft.client.renderer.debug.BrainDebugRenderer
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
- net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
+ net.minecraft.client.renderer.debug.CaveDebugRenderer
- net.minecraft.client.renderer.debug.ChunkBorderRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer$1
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
- net.minecraft.client.renderer.debug.CollisionBoxRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer
- net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
- net.minecraft.client.renderer.debug.GameTestDebugRenderer
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
- net.minecraft.client.renderer.debug.PathfindingRenderer
+ net.minecraft.client.renderer.debug.RaidDebugRenderer
- net.minecraft.client.renderer.debug.SolidFaceRenderer
+ net.minecraft.client.renderer.debug.StructureRenderer
- net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
+ net.minecraft.client.renderer.debug.WaterDebugRenderer
- net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.DimensionSpecialEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$EndEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
- net.minecraft.client.renderer.entity.AbstractHorseRenderer
+ net.minecraft.client.renderer.entity.AbstractZombieRenderer
- net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
+ net.minecraft.client.renderer.entity.ArmorStandRenderer
- net.minecraft.client.renderer.entity.ArrowRenderer
+ net.minecraft.client.renderer.entity.AxolotlRenderer
- net.minecraft.client.renderer.entity.BatRenderer
+ net.minecraft.client.renderer.entity.BeeRenderer
- net.minecraft.client.renderer.entity.BlazeRenderer
+ net.minecraft.client.renderer.entity.BoatRenderer
- net.minecraft.client.renderer.entity.CatRenderer
+ net.minecraft.client.renderer.entity.CaveSpiderRenderer
- net.minecraft.client.renderer.entity.ChestedHorseRenderer
+ net.minecraft.client.renderer.entity.ChickenRenderer
- net.minecraft.client.renderer.entity.CodRenderer
+ net.minecraft.client.renderer.entity.CowRenderer
- net.minecraft.client.renderer.entity.CreeperRenderer
+ net.minecraft.client.renderer.entity.DolphinRenderer
- net.minecraft.client.renderer.entity.DragonFireballRenderer
+ net.minecraft.client.renderer.entity.DrownedRenderer
- net.minecraft.client.renderer.entity.ElderGuardianRenderer
+ net.minecraft.client.renderer.entity.EndCrystalRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
- net.minecraft.client.renderer.entity.EndermanRenderer
+ net.minecraft.client.renderer.entity.EndermiteRenderer
- net.minecraft.client.renderer.entity.EntityRenderDispatcher
+ net.minecraft.client.renderer.entity.EntityRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider
+ net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EntityRenderers
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.GhastRenderer
- net.minecraft.client.renderer.entity.GiantMobRenderer
+ net.minecraft.client.renderer.entity.GlowSquidRenderer
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
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.CustomHeadLayer
+ net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
- net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
+ net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
- net.minecraft.client.renderer.entity.layers.ElytraLayer
+ net.minecraft.client.renderer.entity.layers.EnderEyesLayer
- net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
+ net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SaddleLayer
- net.minecraft.client.renderer.entity.layers.SheepFurLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
- net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
+ net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
- net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
+ net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
- net.minecraft.client.renderer.entity.layers.StrayClothingLayer
+ net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
+ net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
- net.minecraft.client.renderer.entity.layers.WitchItemLayer
+ net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.layers.WolfCollarLayer
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
- net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.package-info
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
- net.minecraft.client.renderer.entity.player.package-info
+ net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.RenderLayerParent
+ net.minecraft.client.renderer.entity.SalmonRenderer
- net.minecraft.client.renderer.entity.SheepRenderer
+ net.minecraft.client.renderer.entity.ShulkerBulletRenderer
- net.minecraft.client.renderer.entity.ShulkerRenderer
+ net.minecraft.client.renderer.entity.SilverfishRenderer
- net.minecraft.client.renderer.entity.SkeletonRenderer
+ net.minecraft.client.renderer.entity.SlimeRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$1
+ net.minecraft.client.renderer.FaceInfo$Constants
- net.minecraft.client.renderer.FaceInfo$VertexInfo
+ net.minecraft.client.renderer.FogRenderer
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.GameRenderer
- net.minecraft.client.renderer.GpuWarnlistManager
+ net.minecraft.client.renderer.GpuWarnlistManager$1
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
+ net.minecraft.client.renderer.item.ItemProperties
- net.minecraft.client.renderer.item.ItemProperties$1
+ net.minecraft.client.renderer.item.ItemProperties$2
- net.minecraft.client.renderer.item.ItemProperties$CompassWobble
+ net.minecraft.client.renderer.item.ItemPropertyFunction
- net.minecraft.client.renderer.item.package-info
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$1
- net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
+ net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$1
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ net.minecraft.client.renderer.package-info
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
+ net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
+ net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
- net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ net.minecraft.client.renderer.RenderStateShard$FogStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$PortalTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
+ net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
+ net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
- net.minecraft.client.renderer.RenderType
+ net.minecraft.client.renderer.RenderType$1
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.RenderType$OutlineProperty
+ net.minecraft.client.renderer.RunningTrimmedMean
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.Sheets
- net.minecraft.client.renderer.Sheets$1
+ net.minecraft.client.renderer.SpriteCoordinateExpander
- net.minecraft.client.renderer.texture.AbstractTexture
+ net.minecraft.client.renderer.texture.AtlasSet
- net.minecraft.client.renderer.texture.DynamicTexture
+ net.minecraft.client.renderer.texture.HttpTexture
- net.minecraft.client.renderer.texture.MipmapGenerator
+ net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
- net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
+ net.minecraft.client.renderer.texture.PreloadedTexture
- net.minecraft.client.renderer.texture.SimpleTexture
+ net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
- net.minecraft.client.renderer.texture.Stitcher
+ net.minecraft.client.renderer.texture.Stitcher$Holder
- net.minecraft.client.renderer.texture.Stitcher$Region
+ net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
- net.minecraft.client.renderer.texture.StitcherException
+ net.minecraft.client.renderer.texture.TextureAtlas
- net.minecraft.client.renderer.texture.TextureAtlas$Preparations
+ net.minecraft.client.renderer.texture.TextureAtlasSprite
- net.minecraft.client.renderer.texture.TextureAtlasSprite$1
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$AnimatedTexture
- net.minecraft.client.renderer.texture.TextureAtlasSprite$FrameInfo
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$Info
- net.minecraft.client.renderer.texture.TextureAtlasSprite$InterpolationData
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
- net.minecraft.client.renderer.ViewArea
+ net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.resources.AssetIndex
+ net.minecraft.client.resources.ClientPackSource
- net.minecraft.client.resources.ClientPackSource$1
+ net.minecraft.client.resources.ClientPackSource$2
- net.minecraft.client.resources.DefaultClientPackResources
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DirectAssetIndex
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.language.ClientLanguage
- net.minecraft.client.resources.language.FormattedBidiReorder
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.LanguageInfo
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.package-info
+ net.minecraft.client.resources.LegacyPackResourcesAdapter
- net.minecraft.client.resources.LegacyStuffWrapper
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.animation.package-info
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
- net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.LanguageMetadataSection
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSectionSerializer
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.BakedModel
- net.minecraft.client.resources.model.BlockModelRotation
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
+ net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
- net.minecraft.client.resources.model.ModelManager
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
+ net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.model.WeightedBakedModel$WeightedModel
- net.minecraft.client.resources.package-info
- net.minecraft.client.resources.PackResourcesAdapterV4
+ net.minecraft.client.resources.PaintingTextureManager
- net.minecraft.client.resources.SkinManager
+ net.minecraft.client.resources.SkinManager$1
- net.minecraft.client.resources.SkinManager$SkinTextureCallback
+ net.minecraft.client.resources.sounds.AbstractSoundInstance
- net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
+ net.minecraft.client.resources.sounds.AmbientSoundHandler
- net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
+ net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
- net.minecraft.client.resources.sounds.BeeSoundInstance
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
- net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
+ net.minecraft.client.resources.sounds.EntityBoundSoundInstance
- net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
+ net.minecraft.client.resources.sounds.MinecartSoundInstance
+ net.minecraft.client.resources.sounds.package-info
- net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
+ net.minecraft.client.resources.sounds.SimpleSoundInstance
- net.minecraft.client.resources.sounds.Sound
+ net.minecraft.client.resources.sounds.Sound$Type
- net.minecraft.client.resources.sounds.SoundEventRegistration
+ net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
- net.minecraft.client.resources.sounds.SoundInstance
+ net.minecraft.client.resources.sounds.SoundInstance$Attenuation
- net.minecraft.client.resources.sounds.TickableSoundInstance
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
+ net.minecraft.client.Screenshot
- net.minecraft.client.searchtree.MutableSearchTree
- net.minecraft.client.searchtree.package-info
+ net.minecraft.client.searchtree.ReloadableIdSearchTree
- net.minecraft.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
+ net.minecraft.client.searchtree.ReloadableSearchTree
- net.minecraft.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
+ net.minecraft.client.searchtree.SuffixArray$1
+ net.minecraft.client.server.IntegratedPlayerList
- net.minecraft.client.server.IntegratedServer
+ net.minecraft.client.server.LanServer
- net.minecraft.client.server.LanServerDetection
+ net.minecraft.client.server.LanServerDetection$LanServerDetector
- net.minecraft.client.server.LanServerDetection$LanServerList
+ net.minecraft.client.server.LanServerPinger
- net.minecraft.client.server.package-info
- net.minecraft.client.Session
+ net.minecraft.client.skins.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$1
+ net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
- net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
+ net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
- net.minecraft.client.sounds.SoundBufferLibrary
+ net.minecraft.client.sounds.SoundEngine
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
+ net.minecraft.client.StringSplitter
- net.minecraft.client.StringSplitter$1
+ net.minecraft.client.StringSplitter$FlatComponents
- net.minecraft.client.StringSplitter$LineBreakFinder
+ net.minecraft.client.StringSplitter$LineComponent
- net.minecraft.client.StringSplitter$LinePosConsumer
+ net.minecraft.client.StringSplitter$WidthLimitedCharSink
- net.minecraft.client.StringSplitter$WidthProvider
+ net.minecraft.client.Timer
- net.minecraft.client.ToggleKeyMapping
- net.minecraft.client.tutorial.BundleTutorial
+ net.minecraft.client.User
- net.minecraft.client.User$Type
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
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
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
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
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.FurnaceRecipeFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
- net.minecraft.util.datafix.fixes.MissingDimensionFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
- net.minecraft.util.datafix.fixes.RenameBiomesFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.SwimStatsRenameFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
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
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.UniformFloat
- net.minecraft.util.UniformInt
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
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
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownTemptationTicks
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
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
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.WeightedList
- net.minecraft.world.entity.ai.behavior.WeightedList$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
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
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.PlayGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
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
- net.minecraft.world.entity.ai.goal.TakeFlowerGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$1
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlHostileSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HostilesSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
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
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
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
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
- net.minecraft.world.entity.animal.horse.AbstractHorse
+ net.minecraft.world.entity.animal.horse.AbstractHorse$1
- net.minecraft.world.entity.animal.horse.Donkey
+ net.minecraft.world.entity.animal.horse.Horse
- net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
+ net.minecraft.world.entity.animal.horse.Llama
- net.minecraft.world.entity.animal.horse.Llama$1
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
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
- net.minecraft.world.entity.animal.Pig
+ net.minecraft.world.entity.animal.PolarBear
- net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
- net.minecraft.world.entity.animal.Pufferfish
+ net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
- net.minecraft.world.entity.animal.Rabbit
+ net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Salmon
+ net.minecraft.world.entity.animal.Sheep
- net.minecraft.world.entity.animal.Sheep$1
+ net.minecraft.world.entity.animal.Sheep$2
- net.minecraft.world.entity.animal.ShoulderRidingEntity
+ net.minecraft.world.entity.animal.SnowGolem
- net.minecraft.world.entity.animal.Squid
+ net.minecraft.world.entity.animal.Squid$1
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$1
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.Turtle
+ net.minecraft.world.entity.animal.Turtle$1
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.HangingEntity
- net.minecraft.world.entity.decoration.HangingEntity$1
+ net.minecraft.world.entity.decoration.ItemFrame
- net.minecraft.world.entity.decoration.ItemFrame$1
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$1
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
+ net.minecraft.world.entity.monster.Illusioner$1
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$1
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
- net.minecraft.world.entity.monster.Ravager$1
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
- net.minecraft.world.entity.monster.Shulker
+ net.minecraft.world.entity.monster.Shulker$1
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
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
+ net.minecraft.world.entity.monster.Strider$1
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
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
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspisciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
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
+ net.minecraft.world.entity.vehicle.AbstractMinecart
- net.minecraft.world.entity.vehicle.AbstractMinecart$1
+ net.minecraft.world.entity.vehicle.AbstractMinecart$Type
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
- net.minecraft.world.entity.vehicle.Boat
+ net.minecraft.world.entity.vehicle.Boat$1
- net.minecraft.world.entity.vehicle.Boat$Status
+ net.minecraft.world.entity.vehicle.Boat$Type
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
- net.minecraft.world.entity.vehicle.package-info
+ net.minecraft.world.food.FoodConstants
- net.minecraft.world.food.FoodData
+ net.minecraft.world.food.FoodProperties
- net.minecraft.world.food.FoodProperties$1
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.AnvilMenu$1
- net.minecraft.world.inventory.BeaconMenu
+ net.minecraft.world.inventory.BeaconMenu$1
- net.minecraft.world.inventory.BeaconMenu$PaymentSlot
+ net.minecraft.world.inventory.BlastFurnaceMenu
- net.minecraft.world.inventory.BrewingStandMenu
+ net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
- net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
+ net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
- net.minecraft.world.inventory.CartographyTableMenu
+ net.minecraft.world.inventory.CartographyTableMenu$1
- net.minecraft.world.inventory.CartographyTableMenu$2
+ net.minecraft.world.inventory.CartographyTableMenu$3
- net.minecraft.world.inventory.CartographyTableMenu$4
+ net.minecraft.world.inventory.CartographyTableMenu$5
- net.minecraft.world.inventory.ChestMenu
+ net.minecraft.world.inventory.ClickAction
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
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
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.alchemy.PotionUtils
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
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
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$1
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$10
- net.minecraft.world.item.CreativeModeTab$11
+ net.minecraft.world.item.CreativeModeTab$12
- net.minecraft.world.item.CreativeModeTab$2
+ net.minecraft.world.item.CreativeModeTab$3
- net.minecraft.world.item.CreativeModeTab$4
+ net.minecraft.world.item.CreativeModeTab$5
- net.minecraft.world.item.CreativeModeTab$6
+ net.minecraft.world.item.CreativeModeTab$7
- net.minecraft.world.item.CreativeModeTab$8
+ net.minecraft.world.item.CreativeModeTab$9
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
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
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.ExperienceBottleItem
+ net.minecraft.world.item.FireChargeItem
- net.minecraft.world.item.FireworkRocketItem
+ net.minecraft.world.item.FireworkRocketItem$Shape
- net.minecraft.world.item.FireworkStarItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$1
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
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
+ net.minecraft.world.item.package-info
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlayerHeadItem
- net.minecraft.world.item.PotionItem
+ net.minecraft.world.item.ProjectileWeaponItem
- net.minecraft.world.item.Rarity
+ net.minecraft.world.item.RecordItem
- net.minecraft.world.item.SaddleItem
+ net.minecraft.world.item.ScaffoldingBlockItem
- net.minecraft.world.item.ServerItemCooldowns
+ net.minecraft.world.item.ShearsItem
- net.minecraft.world.item.ShieldItem
+ net.minecraft.world.item.ShovelItem
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SimpleFoiledItem
- net.minecraft.world.item.SnowballItem
+ net.minecraft.world.item.SolidBucketItem
- net.minecraft.world.item.SpawnEggItem
+ net.minecraft.world.item.SpectralArrowItem
- net.minecraft.world.item.SplashPotionItem
+ net.minecraft.world.item.SpyglassItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$BiomeCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$1
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.BiomeZoomer
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
+ net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$1
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$NoiseParameters
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.OverworldBiomeSource
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractCandleBlock
- net.minecraft.world.level.block.AbstractCauldronBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
+ net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CaveVinesBodyBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeBlock
+ net.minecraft.world.level.block.ChangeOverTimeFullBlock
+ net.minecraft.world.level.block.ChangeOverTimeStairBlock
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
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LavaCauldronBlock
+ net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
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
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$1
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopperFullBlock
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
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$1
+ net.minecraft.world.level.ChunkTickList$ScheduledTick
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.CollisionSpliterator
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EmptyTickList
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$1
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
+ net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
+ net.minecraft.world.level.levelgen.feature.blockplacers.package-info
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GeodeFeature
+ net.minecraft.world.level.levelgen.feature.GlowLichenFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JigsawFeature
+ net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$1
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
+ net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SmallDripstoneFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
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
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
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
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.placement.BaseHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.BiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountDecorator
- net.minecraft.world.level.levelgen.placement.CountNoiseDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceDecorator
- net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratedDecorator
- net.minecraft.world.level.levelgen.placement.DecoratedDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.DecorationContext
- net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
+ net.minecraft.world.level.levelgen.placement.DepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.EdgeDecorator
+ net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
- net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
- net.minecraft.world.level.levelgen.placement.FeatureDecorator
+ net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.HeightmapDecorator
- net.minecraft.world.level.levelgen.placement.HeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.HeightMapWorldSurfaceDecorator
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
- net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountMultiLayerDecorator
- net.minecraft.world.level.levelgen.placement.nether.FireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.GlowstoneDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.NoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.RangeDecorator
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.Spread32Decorator
- net.minecraft.world.level.levelgen.placement.SquareDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.VeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.SimpleRandomSource
+ net.minecraft.world.level.levelgen.structure.BeardedStructureStart
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
- net.minecraft.world.level.levelgen.structure.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.IglooPieces
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
- net.minecraft.world.level.levelgen.structure.NetherFossilFeature
+ net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
- net.minecraft.world.level.levelgen.structure.NetherFossilPieces
+ net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureStart$1
- net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorList
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.BlendedNoise
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.TickList
+ net.minecraft.world.level.TickNextTickData
- net.minecraft.world.level.TickPriority
+ net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.client.particle.HeartParticle -1M
```
```
XXX.client.particle.NoteParticle -1M
```
```
XXX.client.particle.RisingParticle -1M
```
```
XXX.block.model.ItemOverrides +4M -1M | +2P -2P
```
```
XXX.minecraft.data.BlockFamilies +4P -4P
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.data.recipes.RecipeProvider +5M -1M
```
```
XXX.protocol.game.ClientboundPlayerPositionPacket +2M -1M | +1P
```
```
XXX.minecraft.server.MinecraftServer +1M -1M
```
```
XXX.server.level.ServerPlayer +1M
```
```
XXX.server.level.WorldGenRegion +1M -2M | +1P -2P
```
```
XXX.server.network.ServerGamePacketListenerImpl +2M
```
```
XXX.minecraft.sounds.SoundEvents +63P
```
```
XXX.minecraft.tags.BlockTags +3P
```
```
XXX.minecraft.tags.ItemTags +1P
```
```
XXX.world.entity.Entity +14M -7M | +4P -2P
```
```
XXX.level.block.BaseFireBlock +1M
```
```
XXX.level.block.BellBlock +1M
```
```
XXX.level.block.GrowingPlantBodyBlock +1M
```
```
XXX.level.chunk.PalettedContainer +2M -3M
```
```
XXX.chunk.storage.SectionStorage +2M -1M
```
```
XXX.level.gameevent.GameEvent +1M | +15P -4P
```
```
XXX.levelgen.feature.AbstractFlowerFeature +1M -1M
```
```
XXX.levelgen.feature.BambooFeature +1M -2M
```
```
XXX.levelgen.feature.BasaltPillarFeature +1M -2M
```
```
XXX.levelgen.feature.BastionFeature +2M -2M
```
```
XXX.levelgen.feature.BlockPileFeature +1M -2M
```
```
XXX.levelgen.feature.BonusChestFeature +1M -2M
```
```
XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart +2M -2M
```
```
XXX.levelgen.feature.DecoratedFeature +2M -3M
```
```
XXX.levelgen.feature.DeltaFeature +1M -2M
```
```
XXX.levelgen.feature.DesertPyramidFeature$FeatureStart +2M -2M
```
```
XXX.levelgen.feature.DiskReplaceFeature +1M -2M
```
```
XXX.levelgen.feature.EndCityFeature$EndCityStart +2M -2M
```
```
XXX.levelgen.feature.EndIslandFeature +1M -2M
```
```
XXX.levelgen.feature.Feature +1P -1P
```
```
XXX.levelgen.synth.NormalNoise +3M -3M
```
```
XXX.levelgen.synth.PerlinSimplexNoise +3M -3M
```
```
XXX.level.material.FluidState +1M
```
```
XXX.world.phys.AABB +1M -1M
```

</details>














































































































































































































































































<details>
<summary>
net.minecraft.client.particle.HeartParticle
</summary>

```diff
+ void tick()
```

</details>









<details>
<summary>
net.minecraft.client.particle.NoteParticle
</summary>

```diff
+ void tick()
```

</details>












<details>
<summary>
net.minecraft.client.particle.RisingParticle
</summary>

```diff
+ void tick()
```

</details>















<details>
<summary>
net.minecraft.client.renderer.block.model.ItemOverrides
</summary>

```diff
- BakedModel bakeModel(ModelBakery,BlockModel,Function,ItemOverride)
+ BakedModel lambda$new$0(Function,BlockModel,ModelBakery,ItemOverride)
- ItemOverrides$PropertyMatcher lambda$new$1(Object2IntMap,ItemOverride$Predicate)
- ItemOverrides$PropertyMatcher[] lambda$new$2(int)
- ResourceLocation[] lambda$new$0(int)
```

</details>





























































































































































<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- String getBlockName(ItemLike)
- String getFromName(ItemLike,ItemLike)
- void carpet(Consumer,ItemLike,ItemLike)
+ void carpetFromWool(Consumer,ItemLike,ItemLike)
- void stonecutterResultFromBase(Consumer,ItemLike,ItemLike,int)
- void stonecutterResultFromBase(Consumer,ItemLike,ItemLike)
```

</details>








































































































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
</summary>

```diff
- boolean requestDismountVehicle()
- void <init>(double,double,double,float,float,Set,int,boolean)
+ void <init>(double,double,double,float,float,Set,int)
```

</details>




































































































<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
+ void setInitialSpawn(ServerLevel,ServerLevelData,boolean,boolean,boolean)
- void setInitialSpawn(ServerLevel,ServerLevelData,boolean,boolean)
```

</details>























































































<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- void dismountTo(double,double,double)
```

</details>


<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
- ChunkPos getCenter()
+ int getCenterX()
+ int getCenterZ()
```

</details>







<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- void dismount(double,double,double,float,float)
- void teleport(double,double,double,float,float,Set,boolean)
```

</details>

























































































































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockPos eyeBlockPosition()
- boolean isFlapping()
+ boolean isMovementNoisy()
+ boolean lambda$refreshDimensions$12(BlockState,BlockPos)
+ boolean makeFlySound()
- Entity$MovementEmission getMovementEmission()
+ float playFlySound(float)
- Vec3 getEyePosition()
- void dismountTo(double,double,double)
+ void gameEvent(Entity,GameEvent)
- void gameEvent(GameEvent,BlockPos)
- void gameEvent(GameEvent,Entity,BlockPos)
- void gameEvent(GameEvent,Entity)
- void lambda$refreshDimensions$12(EntityDimensions,Vec3)
- void onFlap()
- void processFlappingMovement()
+ void resetPos()
+ void setBodyIsInPowderSnow(boolean)
- void setIsInPowderSnow(boolean)
- void setPos(Vec3)
- void setSharedFlagOnFire(boolean)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
- void spawnDestroyParticles(Level,Player,BlockPos,BlockState)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
- boolean attemptToRing(Entity,Level,BlockPos,Direction)
```

</details>








































<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
- BlockState updateHeadAfterConvertedFromBody(BlockState,BlockState)
```

</details>











































































<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
+ String lambda$acquire$1(Thread)
- void lambda$count$1(Int2IntMap,int)
+ void lambda$count$2(Int2IntMap,int)
- void lambda$count$2(PalettedContainer$CountConsumer,Int2IntMap$Entry)
+ void lambda$count$3(PalettedContainer$CountConsumer,Int2IntMap$Entry)
```

</details>














<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
- boolean outsideStoredRange(long)
+ boolean outsideStoredRange(SectionPos)
- long getKey(ChunkPos,int)
```

</details>




















<details>
<summary>
net.minecraft.world.level.gameevent.GameEvent
</summary>

```diff
- String toString()
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BambooFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ProbabilityFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockPileFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,BlockPileConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BonusChestFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
</summary>

```diff
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ProbabilityFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ProbabilityFeatureConfiguration)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.DecoratedFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,DecoratedFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- void lambda$place$0(ConfiguredFeature,WorldGenLevel,ChunkGenerator,Random,MutableBoolean,BlockPos)
+ void lambda$place$0(DecoratedFeatureConfiguration,WorldGenLevel,ChunkGenerator,Random,MutableBoolean,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DeltaFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,DeltaFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
</summary>

```diff
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,DiskConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
</summary>

```diff
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndIslandFeature
</summary>

```diff
- boolean place(FeaturePlaceContext)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.synth.NormalNoise
</summary>

```diff
- NormalNoise create(RandomSource,int,double[])
- NormalNoise create(RandomSource,int,DoubleList)
+ NormalNoise create(WorldgenRandom,int,double[])
+ NormalNoise create(WorldgenRandom,int,DoubleList)
- void <init>(RandomSource,int,DoubleList)
+ void <init>(WorldgenRandom,int,DoubleList)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
</summary>

```diff
- void <init>(RandomSource,IntSortedSet)
- void <init>(RandomSource,IntStream)
- void <init>(RandomSource,List)
+ void <init>(WorldgenRandom,IntSortedSet)
+ void <init>(WorldgenRandom,IntStream)
+ void <init>(WorldgenRandom,List)
```

</details>














<details>
<summary>
net.minecraft.world.level.material.FluidState
</summary>

```diff
- boolean isSourceOfType(Fluid)
```

</details>















































































































































































































<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
+ AABB ofSize(double,double,double)
- AABB ofSize(Vec3,double,double,double)
```

</details>
</details>