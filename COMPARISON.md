## Comparison with [1.13-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.13-pre4)

- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

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
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ biome.minecraft.badlands_plateau: Badlands Plateau
+ biome.minecraft.badlands: Badlands
+ biome.minecraft.beach: Beach
- biome.minecraft.beaches: Beach
- biome.minecraft.cold_beach: Snowy Beach
+ biome.minecraft.dark_forest_hills: Dark Forest Hills
+ biome.minecraft.dark_forest: Dark Forest
+ biome.minecraft.desert_lakes: Desert Lakes
+ biome.minecraft.end_barrens: End Barrens
+ biome.minecraft.end_highlands: End Highlands
+ biome.minecraft.end_midlands: End Midlands
+ biome.minecraft.eroded_badlands: Eroded Badlands
- biome.minecraft.extreme_hills_with_trees: Wooded Mountains
- biome.minecraft.extreme_hills: Mountains
+ biome.minecraft.flower_forest: Flower Forest
- biome.minecraft.forest_hills: Wooded Hills
+ biome.minecraft.giant_spruce_taiga_hills: Giant Spruce Taiga Hills
+ biome.minecraft.giant_spruce_taiga: Giant Spruce Taiga
+ biome.minecraft.giant_tree_taiga_hills: Giant Tree Taiga Hills
+ biome.minecraft.giant_tree_taiga: Giant Tree Taiga
+ biome.minecraft.gravelly_mountains: Gravelly Mountains
- biome.minecraft.hell: Nether
- biome.minecraft.ice_flats: Snowy Tundra
- biome.minecraft.ice_mountains: Snowy Mountains
+ biome.minecraft.ice_spikes: Ice Spikes
- biome.minecraft.mesa_clear_rock: Badlands Plateau
- biome.minecraft.mesa_rock: Wooded Badlands Plateau
- biome.minecraft.mesa: Badlands
+ biome.minecraft.modified_badlands_plateau: Modified Badlands Plateau
+ biome.minecraft.modified_gravelly_mountains: Gravelly Mountains+
+ biome.minecraft.modified_jungle_edge: Modified Jungle Edge
+ biome.minecraft.modified_jungle: Modified Jungle
+ biome.minecraft.modified_wooded_badlands_plateau: Modified Wooded Badlands Plateau
+ biome.minecraft.mountain_edge: Mountain Edge
+ biome.minecraft.mountains: Mountains
+ biome.minecraft.mushroom_field_shore: Mushroom Field Shore
+ biome.minecraft.mushroom_fields: Mushroom Fields
- biome.minecraft.mushroom_island_shore: Mushroom Field Shore
- biome.minecraft.mushroom_island: Mushroom Fields
- biome.minecraft.mutated_birch_forest_hills: Tall Birch Hills
- biome.minecraft.mutated_birch_forest: Tall Birch Forest
- biome.minecraft.mutated_desert: Desert Lakes
- biome.minecraft.mutated_extreme_hills_with_trees: Gravelly Mountains+
- biome.minecraft.mutated_extreme_hills: Gravelly Mountains
- biome.minecraft.mutated_forest: Flower Forest
- biome.minecraft.mutated_ice_flats: Ice Spikes
- biome.minecraft.mutated_jungle_edge: Modified Jungle Edge
- biome.minecraft.mutated_jungle: Modified Jungle
- biome.minecraft.mutated_mesa_clear_rock: Modified Badlands Plateau
- biome.minecraft.mutated_mesa_rock: Modified Wooded Badlands Plateau
- biome.minecraft.mutated_mesa: Eroded Badlands
- biome.minecraft.mutated_plains: Sunflower Plains
- biome.minecraft.mutated_redwood_taiga_hills: Giant Spruce Taiga Hills
- biome.minecraft.mutated_redwood_taiga: Giant Spruce Taiga
- biome.minecraft.mutated_roofed_forest: Dark Forest Hills
- biome.minecraft.mutated_savanna_rock: Shattered Savanna Plateau
- biome.minecraft.mutated_savanna: Shattered Savanna
- biome.minecraft.mutated_swampland: Swamp Hills
- biome.minecraft.mutated_taiga_cold: Snowy Taiga Mountains
- biome.minecraft.mutated_taiga: Taiga Mountains
+ biome.minecraft.nether: Nether
- biome.minecraft.redwood_taiga_hills: Giant Tree Taiga Hills
- biome.minecraft.redwood_taiga: Giant Tree Taiga
- biome.minecraft.roofed_forest: Dark Forest
+ biome.minecraft.savanna_plateau: Savanna Plateau
- biome.minecraft.savanna_rock: Savanna Plateau
+ biome.minecraft.shattered_savanna_plateau: Shattered Savanna Plateau
+ biome.minecraft.shattered_savanna: Shattered Savanna
- biome.minecraft.sky_island_barren: End Barrens
- biome.minecraft.sky_island_high: End Highlands
- biome.minecraft.sky_island_low: Small End Islands
- biome.minecraft.sky_island_medium: End Midlands
- biome.minecraft.sky: The End
+ biome.minecraft.small_end_islands: Small End Islands
- biome.minecraft.smaller_extreme_hills: Mountain Edge
+ biome.minecraft.snowy_beach: Snowy Beach
+ biome.minecraft.snowy_mountains: Snowy Mountains
+ biome.minecraft.snowy_taiga_hills: Snowy Taiga Hills
+ biome.minecraft.snowy_taiga_mountains: Snowy Taiga Mountains
+ biome.minecraft.snowy_taiga: Snowy Taiga
+ biome.minecraft.snowy_tundra: Snowy Tundra
- biome.minecraft.stone_beach: Stone Shore
+ biome.minecraft.stone_shore: Stone Shore
+ biome.minecraft.sunflower_plains: Sunflower Plains
+ biome.minecraft.swamp_hills: Swamp Hills
+ biome.minecraft.swamp: Swamp
- biome.minecraft.swampland: Swamp
- biome.minecraft.taiga_cold_hills: Snowy Taiga Hills
- biome.minecraft.taiga_cold: Snowy Taiga
+ biome.minecraft.taiga_mountains: Taiga Mountains
+ biome.minecraft.tall_birch_forest: Tall Birch Forest
+ biome.minecraft.tall_birch_hills: Tall Birch Hills
+ biome.minecraft.the_end: The End
+ biome.minecraft.the_void: The Void
- biome.minecraft.void: The Void
+ biome.minecraft.wooded_badlands_plateau: Wooded Badlands Plateau
+ biome.minecraft.wooded_hills: Wooded Hills
+ biome.minecraft.wooded_mountains: Wooded Mountains
- block.minecraft.acacia_bark: Acacia Bark
+ block.minecraft.acacia_wood: Acacia Wood
- block.minecraft.birch_bark: Birch Bark
+ block.minecraft.birch_wood: Birch Wood
- block.minecraft.dark_oak_bark: Dark Oak Bark
+ block.minecraft.dark_oak_wood: Dark Oak Wood
- block.minecraft.jungle_bark: Jungle Bark
+ block.minecraft.jungle_wood: Jungle Wood
- block.minecraft.mob_spawner: Spawner
+ block.minecraft.nether_portal: Nether Portal
- block.minecraft.oak_bark: Oak Bark
+ block.minecraft.oak_wood: Oak Wood
- block.minecraft.portal: Portal
+ block.minecraft.spawner: Spawner
- block.minecraft.spruce_bark: Spruce Bark
+ block.minecraft.spruce_wood: Spruce Wood
- block.minecraft.stripped_acacia_bark: Stripped Acacia Bark
+ block.minecraft.stripped_acacia_wood: Stripped Acacia Wood
- block.minecraft.stripped_birch_bark: Stripped Birch Bark
+ block.minecraft.stripped_birch_wood: Stripped Birch Wood
- block.minecraft.stripped_dark_oak_bark: Stripped Dark Oak Bark
+ block.minecraft.stripped_dark_oak_wood: Stripped Dark Oak Wood
- block.minecraft.stripped_jungle_bark: Stripped Jungle Bark
+ block.minecraft.stripped_jungle_wood: Stripped Jungle Wood
- block.minecraft.stripped_oak_bark: Stripped Oak Bark
+ block.minecraft.stripped_oak_wood: Stripped Oak Wood
- block.minecraft.stripped_spruce_bark: Stripped Spruce Bark
+ block.minecraft.stripped_spruce_wood: Stripped Spruce Wood
- effect.absorption: Absorption
- effect.blindness: Blindness
- effect.conduit_power: Conduit Power
- effect.confusion: Nausea
- effect.damageBoost: Strength
- effect.digSlowDown: Mining Fatigue
- effect.digSpeed: Haste
- effect.dolphins_grace: Dolphin's Grace
- effect.fireResistance: Fire Resistance
- effect.glowing: Glowing
- effect.harm: Instant Damage
- effect.heal: Instant Health
- effect.healthBoost: Health Boost
- effect.hunger: Hunger
- effect.invisibility: Invisibility
- effect.jump: Jump Boost
- effect.levitation: Levitation
- effect.luck: Luck
+ effect.minecraft.absorption: Absorption
+ effect.minecraft.blindness: Blindness
+ effect.minecraft.conduit_power: Conduit Power
+ effect.minecraft.dolphins_grace: Dolphin's Grace
+ effect.minecraft.fire_resistance: Fire Resistance
+ effect.minecraft.glowing: Glowing
+ effect.minecraft.haste: Haste
+ effect.minecraft.health_boost: Health Boost
+ effect.minecraft.hunger: Hunger
+ effect.minecraft.instant_damage: Instant Damage
+ effect.minecraft.instant_health: Instant Health
+ effect.minecraft.invisibility: Invisibility
+ effect.minecraft.jump_boost: Jump Boost
+ effect.minecraft.levitation: Levitation
+ effect.minecraft.luck: Luck
+ effect.minecraft.mining_fatigue: Mining Fatigue
+ effect.minecraft.nausea: Nausea
+ effect.minecraft.night_vision: Night Vision
+ effect.minecraft.poison: Poison
+ effect.minecraft.regeneration: Regeneration
+ effect.minecraft.resistance: Resistance
+ effect.minecraft.saturation: Saturation
+ effect.minecraft.slow_falling: Slow Falling
+ effect.minecraft.slowness: Slowness
+ effect.minecraft.speed: Speed
+ effect.minecraft.strength: Strength
+ effect.minecraft.unluck: Bad Luck
+ effect.minecraft.water_breathing: Water Breathing
+ effect.minecraft.weakness: Weakness
+ effect.minecraft.wither: Wither
- effect.moveSlowdown: Slowness
- effect.moveSpeed: Speed
- effect.nightVision: Night Vision
- effect.poison: Poison
- effect.regeneration: Regeneration
- effect.resistance: Resistance
- effect.saturation: Saturation
- effect.slow_falling: Slow Falling
- effect.unluck: Bad Luck
- effect.waterBreathing: Water Breathing
- effect.weakness: Weakness
- effect.wither: Wither
- enchantment.arrowDamage: Power
- enchantment.arrowFire: Flame
- enchantment.arrowInfinite: Infinity
- enchantment.arrowKnockback: Punch
- enchantment.binding_curse: Curse of Binding
- enchantment.damage.all: Sharpness
- enchantment.damage.arthropods: Bane of Arthropods
- enchantment.damage.undead: Smite
- enchantment.digging: Efficiency
- enchantment.durability: Unbreaking
- enchantment.fire: Fire Aspect
- enchantment.fishingSpeed: Lure
- enchantment.frostWalker: Frost Walker
- enchantment.knockback: Knockback
- enchantment.lootBonus: Looting
- enchantment.lootBonusDigger: Fortune
- enchantment.lootBonusFishing: Luck of the Sea
- enchantment.mending: Mending
+ enchantment.minecraft.aqua_affinity: Aqua Affinity
+ enchantment.minecraft.bane_of_arthropods: Bane of Arthropods
+ enchantment.minecraft.binding_curse: Curse of Binding
+ enchantment.minecraft.blast_protection: Blast Protection
+ enchantment.minecraft.channeling: Channeling
+ enchantment.minecraft.depth_strider: Depth Strider
+ enchantment.minecraft.efficiency: Efficiency
+ enchantment.minecraft.feather_falling: Feather Falling
+ enchantment.minecraft.fire_aspect: Fire Aspect
+ enchantment.minecraft.fire_protection: Fire Protection
+ enchantment.minecraft.flame: Flame
+ enchantment.minecraft.fortune: Fortune
+ enchantment.minecraft.frost_walker: Frost Walker
+ enchantment.minecraft.impaling: Impaling
+ enchantment.minecraft.infinity: Infinity
+ enchantment.minecraft.knockback: Knockback
+ enchantment.minecraft.looting: Looting
+ enchantment.minecraft.loyalty: Loyalty
+ enchantment.minecraft.luck_of_the_sea: Luck of the Sea
+ enchantment.minecraft.lure: Lure
+ enchantment.minecraft.mending: Mending
+ enchantment.minecraft.power: Power
+ enchantment.minecraft.projectile_protection: Projectile Protection
+ enchantment.minecraft.protection: Protection
+ enchantment.minecraft.punch: Punch
+ enchantment.minecraft.respiration: Respiration
+ enchantment.minecraft.riptide: Riptide
+ enchantment.minecraft.sharpness: Sharpness
+ enchantment.minecraft.silk_touch: Silk Touch
+ enchantment.minecraft.smite: Smite
+ enchantment.minecraft.sweeping: Sweeping Edge
+ enchantment.minecraft.thorns: Thorns
+ enchantment.minecraft.unbreaking: Unbreaking
+ enchantment.minecraft.vanishing_curse: Curse of Vanishing
- enchantment.oxygen: Respiration
- enchantment.protect.all: Protection
- enchantment.protect.explosion: Blast Protection
- enchantment.protect.fall: Feather Falling
- enchantment.protect.fire: Fire Protection
- enchantment.protect.projectile: Projectile Protection
- enchantment.sweeping: Sweeping Edge
- enchantment.thorns: Thorns
- enchantment.trident_channeling: Channeling
- enchantment.trident_impaling: Impaling
- enchantment.trident_loyalty: Loyalty
- enchantment.trident_riptide: Riptide
- enchantment.untouching: Silk Touch
- enchantment.vanishing_curse: Curse of Vanishing
- enchantment.waterWalker: Depth Strider
- enchantment.waterWorker: Aqua Affinity
+ entity.minecraft.command_block_minecart: Minecart with Command Block
- entity.minecraft.commandblock_minecart: Minecart with Command Block
+ entity.minecraft.end_crystal: End Crystal
- entity.minecraft.ender_crystal: End Crystal
- entity.minecraft.evocation_fangs: Evocation Fangs
- entity.minecraft.evocation_illager: Evoker
+ entity.minecraft.evoker_fangs: Evoker Fangs
+ entity.minecraft.evoker: Evoker
+ entity.minecraft.experience_bottle: Thrown Bottle o' Enchanting
+ entity.minecraft.experience_orb: Experience Orb
- entity.minecraft.eye_of_ender_signal: Eye of Ender Signal
+ entity.minecraft.eye_of_ender: Eye of Ender
+ entity.minecraft.firework_rocket: Firework Rocket
- entity.minecraft.fireworks_rocket: Firework Rocket
- entity.minecraft.illusion_illager: Illusioner
+ entity.minecraft.illusioner: Illusioner
+ entity.minecraft.iron_golem: Iron Golem
+ entity.minecraft.snow_golem: Snow Golem
- entity.minecraft.snowman: Snow Golem
- entity.minecraft.villager_golem: Iron Golem
- entity.minecraft.vindication_illager: Vindicator
+ entity.minecraft.vindicator: Vindicator
- entity.minecraft.xp_bottle: Thrown Bottle o' Enchanting
- entity.minecraft.xp_orb: Experience Orb
- item.leaves.name: Leaves
- item.minecraft.chorus_fruit_popped: Popped Chorus Fruit
- item.minecraft.clownfish_bucket: Tropical Fish Bucket
- item.minecraft.clownfish: Tropical Fish
- item.minecraft.evocation_illager_spawn_egg: Evoker Spawn Egg
+ item.minecraft.evoker_spawn_egg: Evoker Spawn Egg
+ item.minecraft.popped_chorus_fruit: Popped Chorus Fruit
+ item.minecraft.tropical_fish_bucket: Bucket of Tropical Fish
+ item.minecraft.tropical_fish: Tropical Fish
- item.minecraft.vindication_illager_spawn_egg: Vindicator Spawn Egg
+ item.minecraft.vindicator_spawn_egg: Vindicator Spawn Egg
+ subtitles.block.note_block.note: Note Block plays
- subtitles.block.note.note: Note Block plays
+ subtitles.entity.armor_stand.fall: Something fell
- subtitles.entity.armorstand.fall: Something fell
- subtitles.entity.bobber.splash: Fishing hook splashes
- subtitles.entity.bobber.throw: Bobber thrown
- subtitles.entity.drowned.ambient_water: Drowned gurgles
- subtitles.entity.drowned.death_water: Drowned dies
- subtitles.entity.drowned.hurt_water: Drowned hurts
+ subtitles.entity.elder_guardian.ambient_land: Elder Guardian flaps
- subtitles.entity.elder_guardian.ambient.land: Elder Guardian flaps
- subtitles.entity.elder_guardian.attack: Elder Guardian shoots
+ subtitles.entity.ender_dragon.ambient: Dragon roars
+ subtitles.entity.ender_dragon.death: Dragon dies
+ subtitles.entity.ender_dragon.flap: Dragon flaps
+ subtitles.entity.ender_dragon.growl: Dragon growls
+ subtitles.entity.ender_dragon.hurt: Dragon hurts
+ subtitles.entity.ender_dragon.shoot: Dragon shoots
+ subtitles.entity.ender_eye.launch: Eye of Ender shoots
+ subtitles.entity.ender_pearl.throw: Ender Pearl flies
- subtitles.entity.enderdragon.ambient: Dragon roars
- subtitles.entity.enderdragon.death: Dragon dies
- subtitles.entity.enderdragon.flap: Dragon flaps
- subtitles.entity.enderdragon.growl: Dragon growls
- subtitles.entity.enderdragon.hurt: Dragon hurts
- subtitles.entity.enderdragon.shoot: Dragon shoots
- subtitles.entity.endereye.launch: Eye of Ender shoots
- subtitles.entity.enderpearl.throw: Ender Pearl flies
- subtitles.entity.evocation_fangs.attack: Fangs snap
- subtitles.entity.evocation_illager.ambient: Evoker murmurs
- subtitles.entity.evocation_illager.cast_spell: Evoker casts spell
- subtitles.entity.evocation_illager.death: Evoker dies
- subtitles.entity.evocation_illager.hurt: Evoker hurts
- subtitles.entity.evocation_illager.prepare_attack: Evoker prepares attack
- subtitles.entity.evocation_illager.prepare_summon: Evoker prepares summoning
- subtitles.entity.evocation_illager.prepare_wololo: Evoker prepares charming
+ subtitles.entity.evoker_fangs.attack: Fangs snap
+ subtitles.entity.evoker.ambient: Evoker murmurs
+ subtitles.entity.evoker.cast_spell: Evoker casts spell
+ subtitles.entity.evoker.death: Evoker dies
+ subtitles.entity.evoker.hurt: Evoker hurts
+ subtitles.entity.evoker.prepare_attack: Evoker prepares attack
+ subtitles.entity.evoker.prepare_summon: Evoker prepares summoning
+ subtitles.entity.evoker.prepare_wololo: Evoker prepares charming
+ subtitles.entity.firework_rocket.blast: Firework blasts
+ subtitles.entity.firework_rocket.launch: Firework launches
+ subtitles.entity.firework_rocket.twinkle: Firework twinkles
- subtitles.entity.firework.blast: Firework blasts
- subtitles.entity.firework.launch: Firework launches
- subtitles.entity.firework.twinkle: Firework twinkles
+ subtitles.entity.fishing_bobber.splash: Fishing Bobber splashes
+ subtitles.entity.fishing_bobber.throw: Bobber thrown
+ subtitles.entity.guardian.ambient_land: Guardian flaps
- subtitles.entity.guardian.ambient.land: Guardian flaps
- subtitles.entity.guardian.curse: Guardian curses
- subtitles.entity.illusion_illager.ambient: Illusioner murmurs
- subtitles.entity.illusion_illager.cast_spell: Illusioner casts spell
- subtitles.entity.illusion_illager.death: Illusioner dies
- subtitles.entity.illusion_illager.hurt: Illusioner hurts
- subtitles.entity.illusion_illager.mirror_move: Illusioner displaces
- subtitles.entity.illusion_illager.prepare_blindness: Illusioner prepares blindness
- subtitles.entity.illusion_illager.prepare_mirror: Illusioner prepares mirror image
+ subtitles.entity.illusioner.ambient: Illusioner murmurs
+ subtitles.entity.illusioner.cast_spell: Illusioner casts spell
+ subtitles.entity.illusioner.death: Illusioner dies
+ subtitles.entity.illusioner.hurt: Illusioner hurts
+ subtitles.entity.illusioner.mirror_move: Illusioner displaces
+ subtitles.entity.illusioner.prepare_blindness: Illusioner prepares blindness
+ subtitles.entity.illusioner.prepare_mirror: Illusioner prepares mirror image
+ subtitles.entity.item_frame.add_item: Item Frame fills
+ subtitles.entity.item_frame.break: Item Frame breaks
+ subtitles.entity.item_frame.place: Item Frame placed
+ subtitles.entity.item_frame.remove_item: Item Frame empties
+ subtitles.entity.item_frame.rotate_item: Item Frame clicks
- subtitles.entity.itemframe.add_item: Item Frame fills
- subtitles.entity.itemframe.break: Item Frame breaks
- subtitles.entity.itemframe.place: Item Frame placed
- subtitles.entity.itemframe.remove_item: Item Frame empties
- subtitles.entity.itemframe.rotate_item: Item Frame clicks
+ subtitles.entity.leash_knot.break: Leash knot breaks
+ subtitles.entity.leash_knot.place: Leash knot tied
- subtitles.entity.leashknot.break: Leash knot breaks
- subtitles.entity.leashknot.place: Leash knot tied
+ subtitles.entity.lightning_bolt.impact: Lightning strikes
+ subtitles.entity.lightning_bolt.thunder: Thunder roars
- subtitles.entity.lightning.impact: Lightning strikes
- subtitles.entity.lightning.thunder: Thunder roars
+ subtitles.entity.magma_cube.death: Magma Cube dies
+ subtitles.entity.magma_cube.hurt: Magma Cube hurts
+ subtitles.entity.magma_cube.squish: Magma Cube squishes
- subtitles.entity.magmacube.death: Magma Cube dies
- subtitles.entity.magmacube.hurt: Magma Cube hurts
- subtitles.entity.magmacube.squish: Magma Cube squishes
- subtitles.entity.parrot.imitate.cave_spider: Parrot hisses
+ subtitles.entity.parrot.imitate.ender_dragon: Parrot roars
- subtitles.entity.parrot.imitate.enderdragon: Parrot roars
- subtitles.entity.parrot.imitate.evocation_illager: Parrot murmurs
+ subtitles.entity.parrot.imitate.evoker: Parrot murmurs
- subtitles.entity.parrot.imitate.illusion_illager: Parrot murmurs
+ subtitles.entity.parrot.imitate.illusioner: Parrot murmurs
+ subtitles.entity.parrot.imitate.magma_cube: Parrot squishes
- subtitles.entity.parrot.imitate.magmacube: Parrot squishes
- subtitles.entity.parrot.imitate.vindication_illager: Parrot mutters
+ subtitles.entity.parrot.imitate.vindicator: Parrot mutters
+ subtitles.entity.polar_bear.ambient_baby: Polar Bear hums
- subtitles.entity.polar_bear.baby_ambient: Polar Bear hums
- subtitles.entity.skeleton_horse.water_ambient: Skeleton Horse cries
- subtitles.entity.skeleton_horse.water_gallop: Skeleton Horse gallops
- subtitles.entity.skeleton_horse.water_jump: Skeleton Horse jumps
+ subtitles.entity.snow_golem.death: Snow Golem dies
+ subtitles.entity.snow_golem.hurt: Snow Golem hurts
- subtitles.entity.snowman.death: Snow Golem dies
- subtitles.entity.snowman.hurt: Snow Golem hurts
+ subtitles.entity.villager.trade: Villager trades
- subtitles.entity.villager.trading: Villager trades
- subtitles.entity.vindication_illager.ambient: Vindicator mutters
- subtitles.entity.vindication_illager.death: Vindicator dies
- subtitles.entity.vindication_illager.hurt: Vindicator hurts
+ subtitles.entity.vindicator.ambient: Vindicator mutters
+ subtitles.entity.vindicator.death: Vindicator dies
+ subtitles.entity.vindicator.hurt: Vindicator hurts
- subtitles.item.shear: Shears click
+ subtitles.item.shears.shear: Shears click
```

</details>
<details>
<summary>
Changes
</summary>

```
item.minecraft.pufferfish_bucket: Bucket of Pufferfish Bucket
item.minecraft.salmon_bucket: Salmon BucketBucket of Salmon
item.minecraft.cod_bucket: Cod Bucket of Cod
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

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
<details>
<summary>
assets
</summary>

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
</details>