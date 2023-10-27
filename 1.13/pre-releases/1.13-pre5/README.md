<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.13-pre5 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.13-pre5</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2018-06-28T13:58:53+00:00</td></tr>
<tr><th>SHA1</th><td>f0500efb357283322169d38fd52d24e195d56e05</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/f0500efb357283322169d38fd52d24e195d56e05/1.13-pre5.json">https://piston-meta.mojang.com/v1/packages/f0500efb357283322169d38fd52d24e195d56e05/1.13-pre5.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/6d9ede222df5726059aba1b01f99c328bc16f1a5/server.jar">https://piston-data.mojang.com/v1/objects/6d9ede222df5726059aba1b01f99c328bc16f1a5/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/f3262055c586a075fc84f9d4bc76b3cf1a72d69c/client.jar">https://piston-data.mojang.com/v1/objects/f3262055c586a075fc84f9d4bc76b3cf1a72d69c/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre4">1.13-pre4</a>

# Folder structure

<details><summary>data/</summary>

```diff
- minecraft/advancements/recipes/building_blocks/acacia_bark.json
+ minecraft/advancements/recipes/building_blocks/acacia_wood.json
- minecraft/advancements/recipes/building_blocks/birch_bark.json
+ minecraft/advancements/recipes/building_blocks/birch_wood.json
- minecraft/advancements/recipes/building_blocks/dark_oak_bark.json
+ minecraft/advancements/recipes/building_blocks/dark_oak_wood.json
- minecraft/advancements/recipes/building_blocks/jungle_bark.json
+ minecraft/advancements/recipes/building_blocks/jungle_wood.json
- minecraft/advancements/recipes/building_blocks/oak_bark.json
+ minecraft/advancements/recipes/building_blocks/oak_wood.json
- minecraft/advancements/recipes/building_blocks/spruce_bark.json
+ minecraft/advancements/recipes/building_blocks/spruce_wood.json
- minecraft/advancements/recipes/misc/chorus_fruit_popped.json
+ minecraft/advancements/recipes/misc/popped_chorus_fruit.json
- minecraft/loot_tables/entities/evocation_illager.json
+ minecraft/loot_tables/entities/evoker.json
+ minecraft/loot_tables/entities/snow_golem.json
- minecraft/loot_tables/entities/snowman.json
- minecraft/loot_tables/entities/vindication_illager.json
+ minecraft/loot_tables/entities/vindicator.json
- minecraft/recipes/acacia_bark.json
+ minecraft/recipes/acacia_wood.json
- minecraft/recipes/birch_bark.json
+ minecraft/recipes/birch_wood.json
- minecraft/recipes/chorus_fruit_popped.json
- minecraft/recipes/dark_oak_bark.json
+ minecraft/recipes/dark_oak_wood.json
- minecraft/recipes/jungle_bark.json
+ minecraft/recipes/jungle_wood.json
- minecraft/recipes/oak_bark.json
+ minecraft/recipes/oak_wood.json
+ minecraft/recipes/popped_chorus_fruit.json
- minecraft/recipes/spruce_bark.json
+ minecraft/recipes/spruce_wood.json
```

</details>


<details><summary>assets/</summary>

```diff
- minecraft/blockstates/acacia_bark.json
+ minecraft/blockstates/acacia_wood.json
- minecraft/blockstates/birch_bark.json
+ minecraft/blockstates/birch_wood.json
- minecraft/blockstates/dark_oak_bark.json
+ minecraft/blockstates/dark_oak_wood.json
- minecraft/blockstates/jungle_bark.json
+ minecraft/blockstates/jungle_wood.json
- minecraft/blockstates/mob_spawner.json
+ minecraft/blockstates/nether_portal.json
- minecraft/blockstates/oak_bark.json
+ minecraft/blockstates/oak_wood.json
- minecraft/blockstates/portal.json
+ minecraft/blockstates/spawner.json
- minecraft/blockstates/spruce_bark.json
+ minecraft/blockstates/spruce_wood.json
- minecraft/blockstates/stripped_acacia_bark.json
+ minecraft/blockstates/stripped_acacia_wood.json
- minecraft/blockstates/stripped_birch_bark.json
+ minecraft/blockstates/stripped_birch_wood.json
- minecraft/blockstates/stripped_dark_oak_bark.json
+ minecraft/blockstates/stripped_dark_oak_wood.json
- minecraft/blockstates/stripped_jungle_bark.json
+ minecraft/blockstates/stripped_jungle_wood.json
- minecraft/blockstates/stripped_oak_bark.json
+ minecraft/blockstates/stripped_oak_wood.json
- minecraft/blockstates/stripped_spruce_bark.json
+ minecraft/blockstates/stripped_spruce_wood.json
- minecraft/models/block/acacia_bark.json
+ minecraft/models/block/acacia_wood.json
- minecraft/models/block/birch_bark.json
+ minecraft/models/block/birch_wood.json
- minecraft/models/block/dark_oak_bark.json
+ minecraft/models/block/dark_oak_wood.json
- minecraft/models/block/jungle_bark.json
+ minecraft/models/block/jungle_wood.json
- minecraft/models/block/mob_spawner.json
+ minecraft/models/block/nether_portal_ew.json
+ minecraft/models/block/nether_portal_ns.json
- minecraft/models/block/oak_bark.json
+ minecraft/models/block/oak_wood.json
- minecraft/models/block/portal_ew.json
- minecraft/models/block/portal_ns.json
+ minecraft/models/block/spawner.json
- minecraft/models/block/spruce_bark.json
+ minecraft/models/block/spruce_wood.json
- minecraft/models/block/stripped_acacia_bark.json
+ minecraft/models/block/stripped_acacia_wood.json
- minecraft/models/block/stripped_birch_bark.json
+ minecraft/models/block/stripped_birch_wood.json
- minecraft/models/block/stripped_dark_oak_bark.json
+ minecraft/models/block/stripped_dark_oak_wood.json
- minecraft/models/block/stripped_jungle_bark.json
+ minecraft/models/block/stripped_jungle_wood.json
- minecraft/models/block/stripped_oak_bark.json
+ minecraft/models/block/stripped_oak_wood.json
- minecraft/models/block/stripped_spruce_bark.json
+ minecraft/models/block/stripped_spruce_wood.json
- minecraft/models/item/acacia_bark.json
+ minecraft/models/item/acacia_wood.json
- minecraft/models/item/birch_bark.json
+ minecraft/models/item/birch_wood.json
- minecraft/models/item/chorus_fruit_popped.json
- minecraft/models/item/clownfish_bucket.json
- minecraft/models/item/clownfish.json
- minecraft/models/item/dark_oak_bark.json
+ minecraft/models/item/dark_oak_wood.json
- minecraft/models/item/evocation_illager_spawn_egg.json
+ minecraft/models/item/evoker_spawn_egg.json
- minecraft/models/item/jungle_bark.json
+ minecraft/models/item/jungle_wood.json
- minecraft/models/item/mob_spawner.json
- minecraft/models/item/oak_bark.json
+ minecraft/models/item/oak_wood.json
+ minecraft/models/item/popped_chorus_fruit.json
+ minecraft/models/item/spawner.json
- minecraft/models/item/spruce_bark.json
+ minecraft/models/item/spruce_wood.json
- minecraft/models/item/stripped_acacia_bark.json
+ minecraft/models/item/stripped_acacia_wood.json
- minecraft/models/item/stripped_birch_bark.json
+ minecraft/models/item/stripped_birch_wood.json
- minecraft/models/item/stripped_dark_oak_bark.json
+ minecraft/models/item/stripped_dark_oak_wood.json
- minecraft/models/item/stripped_jungle_bark.json
+ minecraft/models/item/stripped_jungle_wood.json
- minecraft/models/item/stripped_oak_bark.json
+ minecraft/models/item/stripped_oak_wood.json
- minecraft/models/item/stripped_spruce_bark.json
+ minecraft/models/item/stripped_spruce_wood.json
+ minecraft/models/item/tropical_fish_bucket.json
+ minecraft/models/item/tropical_fish.json
- minecraft/models/item/vindication_illager_spawn_egg.json
+ minecraft/models/item/vindicator_spawn_egg.json
- minecraft/textures/block/mob_spawner.png
+ minecraft/textures/block/nether_portal.png
+ minecraft/textures/block/nether_portal.png.mcmeta
- minecraft/textures/block/portal.png
- minecraft/textures/block/portal.png.mcmeta
+ minecraft/textures/block/spawner.png
+ minecraft/textures/entity/end_crystal/end_crystal_beam.png
+ minecraft/textures/entity/end_crystal/end_crystal.png
- minecraft/textures/entity/endercrystal/endercrystal_beam.png
- minecraft/textures/entity/endercrystal/endercrystal.png
+ minecraft/textures/entity/illager/evoker_fangs.png
- minecraft/textures/entity/illager/fangs.png
+ minecraft/textures/entity/illager/illusioner.png
- minecraft/textures/entity/illager/illusionist.png
+ minecraft/textures/entity/snow_golem.png
- minecraft/textures/entity/snowman.png
- minecraft/textures/item/chorus_fruit_popped.png
- minecraft/textures/item/clownfish_bucket.png
- minecraft/textures/item/clownfish.png
+ minecraft/textures/item/popped_chorus_fruit.png
+ minecraft/textures/item/tropical_fish_bucket.png
+ minecraft/textures/item/tropical_fish.png
```

</details>


# Tags

<details><summary>blocks/acacia_logs.json</summary>

```diff
- minecraft:acacia_bark
+ minecraft:acacia_wood
- minecraft:stripped_acacia_bark
+ minecraft:stripped_acacia_wood
```

</details>


<details><summary>blocks/birch_logs.json</summary>

```diff
- minecraft:birch_bark
+ minecraft:birch_wood
- minecraft:stripped_birch_bark
+ minecraft:stripped_birch_wood
```

</details>


<details><summary>blocks/dark_oak_logs.json</summary>

```diff
- minecraft:dark_oak_bark
+ minecraft:dark_oak_wood
- minecraft:stripped_dark_oak_bark
+ minecraft:stripped_dark_oak_wood
```

</details>


<details><summary>blocks/jungle_logs.json</summary>

```diff
- minecraft:jungle_bark
+ minecraft:jungle_wood
- minecraft:stripped_jungle_bark
+ minecraft:stripped_jungle_wood
```

</details>


<details><summary>blocks/oak_logs.json</summary>

```diff
- minecraft:oak_bark
+ minecraft:oak_wood
- minecraft:stripped_oak_bark
+ minecraft:stripped_oak_wood
```

</details>


<details><summary>blocks/spruce_logs.json</summary>

```diff
- minecraft:spruce_bark
+ minecraft:spruce_wood
- minecraft:stripped_spruce_bark
+ minecraft:stripped_spruce_wood
```

</details>


<details><summary>items/acacia_logs.json</summary>

```diff
- minecraft:acacia_bark
+ minecraft:acacia_wood
- minecraft:stripped_acacia_bark
+ minecraft:stripped_acacia_wood
```

</details>


<details><summary>items/birch_logs.json</summary>

```diff
- minecraft:birch_bark
+ minecraft:birch_wood
- minecraft:stripped_birch_bark
+ minecraft:stripped_birch_wood
```

</details>


<details><summary>items/dark_oak_logs.json</summary>

```diff
- minecraft:dark_oak_bark
+ minecraft:dark_oak_wood
- minecraft:stripped_dark_oak_bark
+ minecraft:stripped_dark_oak_wood
```

</details>


<details><summary>items/fishes.json</summary>

```diff
- minecraft:clownfish
+ minecraft:tropical_fish
```

</details>


<details><summary>items/jungle_logs.json</summary>

```diff
- minecraft:jungle_bark
+ minecraft:jungle_wood
- minecraft:stripped_jungle_bark
+ minecraft:stripped_jungle_wood
```

</details>


<details><summary>items/oak_logs.json</summary>

```diff
- minecraft:oak_bark
+ minecraft:oak_wood
- minecraft:stripped_oak_bark
+ minecraft:stripped_oak_wood
```

</details>


<details><summary>items/spruce_logs.json</summary>

```diff
- minecraft:spruce_bark
+ minecraft:spruce_wood
- minecraft:stripped_spruce_bark
+ minecraft:stripped_spruce_wood
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ biome.minecraft.badlands
+ biome.minecraft.badlands_plateau
+ biome.minecraft.beach
- biome.minecraft.beaches
- biome.minecraft.cold_beach
+ biome.minecraft.dark_forest
+ biome.minecraft.dark_forest_hills
+ biome.minecraft.desert_lakes
+ biome.minecraft.end_barrens
+ biome.minecraft.end_highlands
+ biome.minecraft.end_midlands
+ biome.minecraft.eroded_badlands
- biome.minecraft.extreme_hills
- biome.minecraft.extreme_hills_with_trees
+ biome.minecraft.flower_forest
- biome.minecraft.forest_hills
+ biome.minecraft.giant_spruce_taiga
+ biome.minecraft.giant_spruce_taiga_hills
+ biome.minecraft.giant_tree_taiga
+ biome.minecraft.giant_tree_taiga_hills
+ biome.minecraft.gravelly_mountains
- biome.minecraft.hell
- biome.minecraft.ice_flats
- biome.minecraft.ice_mountains
+ biome.minecraft.ice_spikes
- biome.minecraft.mesa
- biome.minecraft.mesa_clear_rock
- biome.minecraft.mesa_rock
+ biome.minecraft.modified_badlands_plateau
+ biome.minecraft.modified_gravelly_mountains
+ biome.minecraft.modified_jungle
+ biome.minecraft.modified_jungle_edge
+ biome.minecraft.modified_wooded_badlands_plateau
+ biome.minecraft.mountain_edge
+ biome.minecraft.mountains
+ biome.minecraft.mushroom_field_shore
+ biome.minecraft.mushroom_fields
- biome.minecraft.mushroom_island
- biome.minecraft.mushroom_island_shore
- biome.minecraft.mutated_birch_forest
- biome.minecraft.mutated_birch_forest_hills
- biome.minecraft.mutated_desert
- biome.minecraft.mutated_extreme_hills
- biome.minecraft.mutated_extreme_hills_with_trees
- biome.minecraft.mutated_forest
- biome.minecraft.mutated_ice_flats
- biome.minecraft.mutated_jungle
- biome.minecraft.mutated_jungle_edge
- biome.minecraft.mutated_mesa
- biome.minecraft.mutated_mesa_clear_rock
- biome.minecraft.mutated_mesa_rock
- biome.minecraft.mutated_plains
- biome.minecraft.mutated_redwood_taiga
- biome.minecraft.mutated_redwood_taiga_hills
- biome.minecraft.mutated_roofed_forest
- biome.minecraft.mutated_savanna
- biome.minecraft.mutated_savanna_rock
- biome.minecraft.mutated_swampland
- biome.minecraft.mutated_taiga
- biome.minecraft.mutated_taiga_cold
+ biome.minecraft.nether
- biome.minecraft.redwood_taiga
- biome.minecraft.redwood_taiga_hills
- biome.minecraft.roofed_forest
+ biome.minecraft.savanna_plateau
- biome.minecraft.savanna_rock
+ biome.minecraft.shattered_savanna
+ biome.minecraft.shattered_savanna_plateau
- biome.minecraft.sky
- biome.minecraft.sky_island_barren
- biome.minecraft.sky_island_high
- biome.minecraft.sky_island_low
- biome.minecraft.sky_island_medium
+ biome.minecraft.small_end_islands
- biome.minecraft.smaller_extreme_hills
+ biome.minecraft.snowy_beach
+ biome.minecraft.snowy_mountains
+ biome.minecraft.snowy_taiga
+ biome.minecraft.snowy_taiga_hills
+ biome.minecraft.snowy_taiga_mountains
+ biome.minecraft.snowy_tundra
- biome.minecraft.stone_beach
+ biome.minecraft.stone_shore
+ biome.minecraft.sunflower_plains
+ biome.minecraft.swamp
+ biome.minecraft.swamp_hills
- biome.minecraft.swampland
- biome.minecraft.taiga_cold
- biome.minecraft.taiga_cold_hills
+ biome.minecraft.taiga_mountains
+ biome.minecraft.tall_birch_forest
+ biome.minecraft.tall_birch_hills
+ biome.minecraft.the_end
+ biome.minecraft.the_void
- biome.minecraft.void
+ biome.minecraft.wooded_badlands_plateau
+ biome.minecraft.wooded_hills
+ biome.minecraft.wooded_mountains
- block.minecraft.acacia_bark
+ block.minecraft.acacia_wood
- block.minecraft.birch_bark
+ block.minecraft.birch_wood
- block.minecraft.dark_oak_bark
+ block.minecraft.dark_oak_wood
- block.minecraft.jungle_bark
+ block.minecraft.jungle_wood
- block.minecraft.mob_spawner
+ block.minecraft.nether_portal
- block.minecraft.oak_bark
+ block.minecraft.oak_wood
- block.minecraft.portal
+ block.minecraft.spawner
- block.minecraft.spruce_bark
+ block.minecraft.spruce_wood
- block.minecraft.stripped_acacia_bark
+ block.minecraft.stripped_acacia_wood
- block.minecraft.stripped_birch_bark
+ block.minecraft.stripped_birch_wood
- block.minecraft.stripped_dark_oak_bark
+ block.minecraft.stripped_dark_oak_wood
- block.minecraft.stripped_jungle_bark
+ block.minecraft.stripped_jungle_wood
- block.minecraft.stripped_oak_bark
+ block.minecraft.stripped_oak_wood
- block.minecraft.stripped_spruce_bark
+ block.minecraft.stripped_spruce_wood
- effect.absorption
- effect.blindness
- effect.conduit_power
- effect.confusion
- effect.damageBoost
- effect.digSlowDown
- effect.digSpeed
- effect.dolphins_grace
- effect.fireResistance
- effect.glowing
- effect.harm
- effect.heal
- effect.healthBoost
- effect.hunger
- effect.invisibility
- effect.jump
- effect.levitation
- effect.luck
+ effect.minecraft.absorption
+ effect.minecraft.blindness
+ effect.minecraft.conduit_power
+ effect.minecraft.dolphins_grace
+ effect.minecraft.fire_resistance
+ effect.minecraft.glowing
+ effect.minecraft.haste
+ effect.minecraft.health_boost
+ effect.minecraft.hunger
+ effect.minecraft.instant_damage
+ effect.minecraft.instant_health
+ effect.minecraft.invisibility
+ effect.minecraft.jump_boost
+ effect.minecraft.levitation
+ effect.minecraft.luck
+ effect.minecraft.mining_fatigue
+ effect.minecraft.nausea
+ effect.minecraft.night_vision
+ effect.minecraft.poison
+ effect.minecraft.regeneration
+ effect.minecraft.resistance
+ effect.minecraft.saturation
+ effect.minecraft.slow_falling
+ effect.minecraft.slowness
+ effect.minecraft.speed
+ effect.minecraft.strength
+ effect.minecraft.unluck
+ effect.minecraft.water_breathing
+ effect.minecraft.weakness
+ effect.minecraft.wither
- effect.moveSlowdown
- effect.moveSpeed
- effect.nightVision
- effect.poison
- effect.regeneration
- effect.resistance
- effect.saturation
- effect.slow_falling
- effect.unluck
- effect.waterBreathing
- effect.weakness
- effect.wither
- enchantment.arrowDamage
- enchantment.arrowFire
- enchantment.arrowInfinite
- enchantment.arrowKnockback
- enchantment.binding_curse
- enchantment.damage.all
- enchantment.damage.arthropods
- enchantment.damage.undead
- enchantment.digging
- enchantment.durability
- enchantment.fire
- enchantment.fishingSpeed
- enchantment.frostWalker
- enchantment.knockback
- enchantment.lootBonus
- enchantment.lootBonusDigger
- enchantment.lootBonusFishing
- enchantment.mending
+ enchantment.minecraft.aqua_affinity
+ enchantment.minecraft.bane_of_arthropods
+ enchantment.minecraft.binding_curse
+ enchantment.minecraft.blast_protection
+ enchantment.minecraft.channeling
+ enchantment.minecraft.depth_strider
+ enchantment.minecraft.efficiency
+ enchantment.minecraft.feather_falling
+ enchantment.minecraft.fire_aspect
+ enchantment.minecraft.fire_protection
+ enchantment.minecraft.flame
+ enchantment.minecraft.fortune
+ enchantment.minecraft.frost_walker
+ enchantment.minecraft.impaling
+ enchantment.minecraft.infinity
+ enchantment.minecraft.knockback
+ enchantment.minecraft.looting
+ enchantment.minecraft.loyalty
+ enchantment.minecraft.luck_of_the_sea
+ enchantment.minecraft.lure
+ enchantment.minecraft.mending
+ enchantment.minecraft.power
+ enchantment.minecraft.projectile_protection
+ enchantment.minecraft.protection
+ enchantment.minecraft.punch
+ enchantment.minecraft.respiration
+ enchantment.minecraft.riptide
+ enchantment.minecraft.sharpness
+ enchantment.minecraft.silk_touch
+ enchantment.minecraft.smite
+ enchantment.minecraft.sweeping
+ enchantment.minecraft.thorns
+ enchantment.minecraft.unbreaking
+ enchantment.minecraft.vanishing_curse
- enchantment.oxygen
- enchantment.protect.all
- enchantment.protect.explosion
- enchantment.protect.fall
- enchantment.protect.fire
- enchantment.protect.projectile
- enchantment.sweeping
- enchantment.thorns
- enchantment.trident_channeling
- enchantment.trident_impaling
- enchantment.trident_loyalty
- enchantment.trident_riptide
- enchantment.untouching
- enchantment.vanishing_curse
- enchantment.waterWalker
- enchantment.waterWorker
+ entity.minecraft.command_block_minecart
- entity.minecraft.commandblock_minecart
+ entity.minecraft.end_crystal
- entity.minecraft.ender_crystal
- entity.minecraft.evocation_fangs
- entity.minecraft.evocation_illager
+ entity.minecraft.evoker
+ entity.minecraft.evoker_fangs
+ entity.minecraft.experience_bottle
+ entity.minecraft.experience_orb
+ entity.minecraft.eye_of_ender
- entity.minecraft.eye_of_ender_signal
+ entity.minecraft.firework_rocket
- entity.minecraft.fireworks_rocket
- entity.minecraft.illusion_illager
+ entity.minecraft.illusioner
+ entity.minecraft.iron_golem
+ entity.minecraft.snow_golem
- entity.minecraft.snowman
- entity.minecraft.villager_golem
- entity.minecraft.vindication_illager
+ entity.minecraft.vindicator
- entity.minecraft.xp_bottle
- entity.minecraft.xp_orb
- item.leaves.name
- item.minecraft.chorus_fruit_popped
- item.minecraft.clownfish
- item.minecraft.clownfish_bucket
- item.minecraft.evocation_illager_spawn_egg
+ item.minecraft.evoker_spawn_egg
+ item.minecraft.popped_chorus_fruit
+ item.minecraft.tropical_fish
+ item.minecraft.tropical_fish_bucket
- item.minecraft.vindication_illager_spawn_egg
+ item.minecraft.vindicator_spawn_egg
+ subtitles.block.note_block.note
- subtitles.block.note.note
+ subtitles.entity.armor_stand.fall
- subtitles.entity.armorstand.fall
- subtitles.entity.bobber.splash
- subtitles.entity.bobber.throw
- subtitles.entity.drowned.ambient_water
- subtitles.entity.drowned.death_water
- subtitles.entity.drowned.hurt_water
+ subtitles.entity.elder_guardian.ambient_land
- subtitles.entity.elder_guardian.ambient.land
- subtitles.entity.elder_guardian.attack
+ subtitles.entity.ender_dragon.ambient
+ subtitles.entity.ender_dragon.death
+ subtitles.entity.ender_dragon.flap
+ subtitles.entity.ender_dragon.growl
+ subtitles.entity.ender_dragon.hurt
+ subtitles.entity.ender_dragon.shoot
+ subtitles.entity.ender_eye.launch
+ subtitles.entity.ender_pearl.throw
- subtitles.entity.enderdragon.ambient
- subtitles.entity.enderdragon.death
- subtitles.entity.enderdragon.flap
- subtitles.entity.enderdragon.growl
- subtitles.entity.enderdragon.hurt
- subtitles.entity.enderdragon.shoot
- subtitles.entity.endereye.launch
- subtitles.entity.enderpearl.throw
- subtitles.entity.evocation_fangs.attack
- subtitles.entity.evocation_illager.ambient
- subtitles.entity.evocation_illager.cast_spell
- subtitles.entity.evocation_illager.death
- subtitles.entity.evocation_illager.hurt
- subtitles.entity.evocation_illager.prepare_attack
- subtitles.entity.evocation_illager.prepare_summon
- subtitles.entity.evocation_illager.prepare_wololo
+ subtitles.entity.evoker_fangs.attack
+ subtitles.entity.evoker.ambient
+ subtitles.entity.evoker.cast_spell
+ subtitles.entity.evoker.death
+ subtitles.entity.evoker.hurt
+ subtitles.entity.evoker.prepare_attack
+ subtitles.entity.evoker.prepare_summon
+ subtitles.entity.evoker.prepare_wololo
+ subtitles.entity.firework_rocket.blast
+ subtitles.entity.firework_rocket.launch
+ subtitles.entity.firework_rocket.twinkle
- subtitles.entity.firework.blast
- subtitles.entity.firework.launch
- subtitles.entity.firework.twinkle
+ subtitles.entity.fishing_bobber.splash
+ subtitles.entity.fishing_bobber.throw
+ subtitles.entity.guardian.ambient_land
- subtitles.entity.guardian.ambient.land
- subtitles.entity.guardian.curse
- subtitles.entity.illusion_illager.ambient
- subtitles.entity.illusion_illager.cast_spell
- subtitles.entity.illusion_illager.death
- subtitles.entity.illusion_illager.hurt
- subtitles.entity.illusion_illager.mirror_move
- subtitles.entity.illusion_illager.prepare_blindness
- subtitles.entity.illusion_illager.prepare_mirror
+ subtitles.entity.illusioner.ambient
+ subtitles.entity.illusioner.cast_spell
+ subtitles.entity.illusioner.death
+ subtitles.entity.illusioner.hurt
+ subtitles.entity.illusioner.mirror_move
+ subtitles.entity.illusioner.prepare_blindness
+ subtitles.entity.illusioner.prepare_mirror
+ subtitles.entity.item_frame.add_item
+ subtitles.entity.item_frame.break
+ subtitles.entity.item_frame.place
+ subtitles.entity.item_frame.remove_item
+ subtitles.entity.item_frame.rotate_item
- subtitles.entity.itemframe.add_item
- subtitles.entity.itemframe.break
- subtitles.entity.itemframe.place
- subtitles.entity.itemframe.remove_item
- subtitles.entity.itemframe.rotate_item
+ subtitles.entity.leash_knot.break
+ subtitles.entity.leash_knot.place
- subtitles.entity.leashknot.break
- subtitles.entity.leashknot.place
+ subtitles.entity.lightning_bolt.impact
+ subtitles.entity.lightning_bolt.thunder
- subtitles.entity.lightning.impact
- subtitles.entity.lightning.thunder
+ subtitles.entity.magma_cube.death
+ subtitles.entity.magma_cube.hurt
+ subtitles.entity.magma_cube.squish
- subtitles.entity.magmacube.death
- subtitles.entity.magmacube.hurt
- subtitles.entity.magmacube.squish
- subtitles.entity.parrot.imitate.cave_spider
+ subtitles.entity.parrot.imitate.ender_dragon
- subtitles.entity.parrot.imitate.enderdragon
- subtitles.entity.parrot.imitate.evocation_illager
+ subtitles.entity.parrot.imitate.evoker
- subtitles.entity.parrot.imitate.illusion_illager
+ subtitles.entity.parrot.imitate.illusioner
+ subtitles.entity.parrot.imitate.magma_cube
- subtitles.entity.parrot.imitate.magmacube
- subtitles.entity.parrot.imitate.vindication_illager
+ subtitles.entity.parrot.imitate.vindicator
+ subtitles.entity.polar_bear.ambient_baby
- subtitles.entity.polar_bear.baby_ambient
- subtitles.entity.skeleton_horse.water_ambient
- subtitles.entity.skeleton_horse.water_gallop
- subtitles.entity.skeleton_horse.water_jump
+ subtitles.entity.snow_golem.death
+ subtitles.entity.snow_golem.hurt
- subtitles.entity.snowman.death
- subtitles.entity.snowman.hurt
+ subtitles.entity.villager.trade
- subtitles.entity.villager.trading
- subtitles.entity.vindication_illager.ambient
- subtitles.entity.vindication_illager.death
- subtitles.entity.vindication_illager.hurt
+ subtitles.entity.vindicator.ambient
+ subtitles.entity.vindicator.death
+ subtitles.entity.vindicator.hurt
- subtitles.item.shear
+ subtitles.item.shears.shear
```

</details>


# Misc

<details><summary>advancements.txt</summary>

```diff
- recipes/building_blocks/acacia_bark.json
+ recipes/building_blocks/acacia_wood.json
- recipes/building_blocks/birch_bark.json
+ recipes/building_blocks/birch_wood.json
- recipes/building_blocks/dark_oak_bark.json
+ recipes/building_blocks/dark_oak_wood.json
- recipes/building_blocks/jungle_bark.json
+ recipes/building_blocks/jungle_wood.json
- recipes/building_blocks/oak_bark.json
+ recipes/building_blocks/oak_wood.json
- recipes/building_blocks/spruce_bark.json
+ recipes/building_blocks/spruce_wood.json
- recipes/misc/chorus_fruit_popped.json
+ recipes/misc/popped_chorus_fruit.json
```

</details>


<details><summary>loot_tables.txt</summary>

```diff
- entities/evocation_illager.json
+ entities/evoker.json
+ entities/snow_golem.json
- entities/snowman.json
- entities/vindication_illager.json
+ entities/vindicator.json
```

</details>


<details><summary>recipes.txt</summary>

```diff
- acacia_bark.json
+ acacia_wood.json
- birch_bark.json
+ birch_wood.json
- chorus_fruit_popped.json
- dark_oak_bark.json
+ dark_oak_wood.json
- jungle_bark.json
+ jungle_wood.json
- oak_bark.json
+ oak_wood.json
+ popped_chorus_fruit.json
- spruce_bark.json
+ spruce_wood.json
```

</details>


<details><summary>textures.txt</summary>

```diff
- block/mob_spawner.png
+ block/nether_portal.png
- block/portal.png
+ block/spawner.png
+ entity/end_crystal/end_crystal_beam.png
+ entity/end_crystal/end_crystal.png
- entity/endercrystal/endercrystal_beam.png
- entity/endercrystal/endercrystal.png
+ entity/illager/evoker_fangs.png
- entity/illager/fangs.png
+ entity/illager/illusioner.png
- entity/illager/illusionist.png
+ entity/snow_golem.png
- entity/snowman.png
- item/chorus_fruit_popped.png
- item/clownfish_bucket.png
- item/clownfish.png
+ item/popped_chorus_fruit.png
+ item/tropical_fish_bucket.png
+ item/tropical_fish.png
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
+ com.mojang:datafixerupper:1.0.3
+ io.netty:netty-all:4.1.25.Final
- io.netty:netty-all:4.1.9.Final
```

</details>
