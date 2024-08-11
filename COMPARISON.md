## Comparison with [20w13b](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w13b)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">20w13b</th><th>20w14a</th></tr><tr><td>World version</td><td><code>2521</code></td><td><code>2524</code></td></tr><tr><td>Protocol version</td><td><code>709</code></td><td><code>710</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ attributes.txt
+ trunk_placer_type.txt
```

</details>














<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:zoglin
```

</details>
<details>
<summary>
feature.txt
</summary>

```diff
- minecraft:acacia_tree
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:zoglin_spawn_egg
```

</details>
<details>
<summary>
memory_module_type.txt
</summary>

```diff
- minecraft:nearest_visible_adult_hoglin
+ minecraft:nearest_visible_huntable_hoglin
+ minecraft:nearest_visible_zombified
- minecraft:nearest_visible_zombified_piglin
```

</details>












<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:entity.hoglin.converted_to_zombified
+ minecraft:entity.zoglin.ambient
+ minecraft:entity.zoglin.angry
+ minecraft:entity.zoglin.attack
+ minecraft:entity.zoglin.death
+ minecraft:entity.zoglin.hurt
+ minecraft:entity.zoglin.step
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/attributes.json
+ universal_tags/trunk_placer_type.json
```

</details>



<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:zoglin
```

</details>
















<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:zoglin
```

</details>
<details>
<summary>
universal_tags/feature.json
</summary>

```diff
- minecraft:acacia_tree
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:zoglin_spawn_egg
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
- minecraft:nearest_visible_adult_hoglin
+ minecraft:nearest_visible_huntable_hoglin
+ minecraft:nearest_visible_zombified
- minecraft:nearest_visible_zombified_piglin
```

</details>












<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.hoglin.converted_to_zombified
+ minecraft:entity.zoglin.ambient
+ minecraft:entity.zoglin.angry
+ minecraft:entity.zoglin.attack
+ minecraft:entity.zoglin.death
+ minecraft:entity.zoglin.hurt
+ minecraft:entity.zoglin.step
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ attribute.name.generic.armor_toughness: Armor Toughness
- attribute.name.generic.armorToughness: Armor Toughness
+ attribute.name.generic.attack_damage: Attack Damage
+ attribute.name.generic.attack_knockback: Attack Knockback
+ attribute.name.generic.attack_speed: Attack Speed
- attribute.name.generic.attackDamage: Attack Damage
- attribute.name.generic.attackSpeed: Attack Speed
+ attribute.name.generic.flying_speed: Flying Speed
+ attribute.name.generic.follow_range: Mob Follow Range
- attribute.name.generic.followRange: Mob Follow Range
+ attribute.name.generic.knockback_resistance: Knockback Resistance
- attribute.name.generic.knockbackResistance: Knockback Resistance
+ attribute.name.generic.max_health: Max Health
- attribute.name.generic.maxHealth: Max Health
+ attribute.name.generic.movement_speed: Speed
- attribute.name.generic.movementSpeed: Speed
+ attribute.name.horse.jump_strength: Horse Jump Strength
- attribute.name.horse.jumpStrength: Horse Jump Strength
+ attribute.name.zombie.spawn_reinforcements: Zombie Reinforcements
- attribute.name.zombie.spawnReinforcements: Zombie Reinforcements
+ entity.minecraft.zoglin: Zoglin
+ item.minecraft.zoglin_spawn_egg: Zoglin Spawn Egg
+ selectWorld.access_failure: Failed to access level
+ selectWorld.delete_failure: Failed to delete level
+ selectWorld.locked: Locked by another running instance of Minecraft
+ subtitles.block.beacon.activate: Beacon activates
+ subtitles.block.beacon.ambient: Beacon hums
+ subtitles.block.beacon.deactivate: Beacon deactivates
+ subtitles.block.beacon.power_select: Beacon power selected
+ subtitles.block.conduit.activate: Conduit activates
+ subtitles.block.conduit.ambient: Conduit pulses
+ subtitles.block.conduit.attack.target: Conduit attacks
+ subtitles.block.conduit.deactivate: Conduit deactivates
+ subtitles.block.enchantment_table.use: Enchanting table used
+ subtitles.block.end_portal_frame.fill: Eye of Ender attaches
+ subtitles.block.end_portal.spawn: End Portal opens!
+ subtitles.block.pumpkin.carve: Shears carve
+ subtitles.block.smithing_table.use: Smithing Table used
+ subtitles.entity.boat.paddle_land: Rowing
+ subtitles.entity.boat.paddle_water: Rowing
+ subtitles.entity.cat.beg_for_food: Cat begs
+ subtitles.entity.cat.eat: Cat eats
+ subtitles.entity.cat.hiss: Cat hisses
+ subtitles.entity.drowned.ambient_water: Drowned gurgles
+ subtitles.entity.ender_eye.death: Eye of Ender falls
+ subtitles.entity.fishing_bobber.retrieve: Bobber retrieved
+ subtitles.entity.hoglin.converted_to_zombified: Hoglin converts to Zoglin
+ subtitles.entity.horse.land: Horse lands
+ subtitles.entity.parrot.fly: Parrot flutters
+ subtitles.entity.player.attack.crit: Critical attack
+ subtitles.entity.player.attack.knockback: Knockback attack
+ subtitles.entity.player.attack.strong: Strong attack
+ subtitles.entity.player.attack.sweep: Sweeping attack
+ subtitles.entity.player.attack.weak: Weak attack
+ subtitles.entity.player.hurt_drown: Player drowning
+ subtitles.entity.player.hurt_on_fire: Player burns
+ subtitles.entity.strider.death: Strider dies
+ subtitles.entity.strider.eat: Strider eats
+ subtitles.entity.strider.happy: Strider warbles
+ subtitles.entity.strider.hurt: Strider hurts
+ subtitles.entity.strider.idle: Strider chirps
+ subtitles.entity.strider.retreat: Strider retreats
+ subtitles.entity.tropical_fish.death: Tropical Fish dies
+ subtitles.entity.tropical_fish.flop: Tropical Fish flops
+ subtitles.entity.tropical_fish.hurt: Tropical Fish hurts
+ subtitles.entity.wandering_trader.disappeared: Wandering Trader disappears
+ subtitles.entity.wandering_trader.drink_milk: Wandering Trader drinks milk
+ subtitles.entity.wandering_trader.drink_potion: Wandering Trader drinks potion
+ subtitles.entity.wandering_trader.reappeared: Wandering Trader appears
+ subtitles.entity.zoglin.ambient: Zoglin growls
+ subtitles.entity.zoglin.angry: Zoglin growls angrily
+ subtitles.entity.zoglin.attack: Zoglin attacks
+ subtitles.entity.zoglin.death: Zoglin dies
+ subtitles.entity.zoglin.hurt: Zoglin hurts
+ subtitles.entity.zoglin.step: Zoglin steps
+ subtitles.entity.zombie.destroy_egg: Turtle Egg stomped
+ subtitles.item.bottle.empty: Bottle empties
+ subtitles.item.bucket.fill_fish: Fish captured
```

</details>
<details>
<summary>
Changes
</summary>

```
subtitles.block.iron_trapdoor.close: Trapdoor opencloses
subtitles.block.iron_trapdoor.open: Trapdoor closeopens
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/entities/zoglin.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/zoglin_spawn_egg.json
+ minecraft/textures/entity/hoglin/zoglin.png
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
+ net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.TagManager$Preparations
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.Deserializer
- net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringUtil
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgableMob
- net.minecraft.world.entity.AgableMob$AgableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.BaseAttribute
+ net.minecraft.world.entity.ai.attributes.ModifiableAttributeInstance
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.BlockPosWrapper
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PositionWrapper
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveCallback
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.fishing.FishingHook$1
+ net.minecraft.world.entity.fishing.FishingHook$OpenWaterType
+ net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.global.LightningBolt
- net.minecraft.world.entity.global.package-info
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerableMount
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
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
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
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.SharedMonsterAttributes
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.level.levelgen.feature.AcaciaFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
+ net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DarkOakFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertVillagePools
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.GroundBushFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaTreeFeature
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
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.PlainVillagePools
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.SavannaVillagePools
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SnowyVillagePools
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
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.TaigaVillagePools
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.VillagePieces
- net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelType
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PortalForcer
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.storage.LevelStorageSource$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.ShulkerSharedHelper
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.Snooper
- net.minecraft.world.Snooper$1
+ net.minecraft.world.SnooperPopulator
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.FishingRodHookedTrigger +2M -2M
```
```
XXX.arguments.item.FunctionArgument +1M -1M
```
```
XXX.arguments.item.FunctionArgument$2 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior +1M
```
```
XXX.models.model.TextureSlot +4M -4M | -1P
```
```
XXX.data.tags.EntityTypeTagsProvider -1M
```
```
XXX.data.tags.ItemTagsProvider +2M -5M | +1P -1P
```
```
XXX.gametest.framework.GameTestServer +1M -1M
```
```
XXX.server.dedicated.DedicatedServer +3M -1M
```
```
XXX.server.level.WorldGenRegion +2P
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.BlockTags +1M -4M | +74P -75P
```
```
XXX.minecraft.tags.FluidTags +1M -4M | +3P -4P
```
```
XXX.minecraft.tags.Tag$Builder +8M -9M | +1P -2P
```
```
XXX.minecraft.tags.Tag$TagEntry +3M -5M | -1P
```
```
XXX.minecraft.tags.TagCollection +8M -6M | +2P -2P
```
```
XXX.minecraft.util.Mth +1M -1M
```
```
XXX.ai.attributes.AttributeModifier +3M -2M | +1P -1P
```
```
XXX.ai.attributes.RangedAttribute +1M -3M | -1P
```
```
XXX.ai.behavior.LookAtTargetSink +2M -2M
```
```
XXX.ai.memory.MemoryModuleType +2P -2P
```
```
XXX.ai.memory.WalkTarget +2M -2M | +1P -1P
```
```
XXX.ai.navigation.PathNavigation -1P
```
```
XXX.entity.animal.Bee +1M -1M
```
```
XXX.entity.animal.Cat +1M -1M
```
```
XXX.entity.animal.Chicken +1M -1M
```
```
XXX.entity.animal.Cow +1M -1M
```
```
XXX.entity.animal.Fox +1M -1M
```
```
XXX.entity.animal.IronGolem +1M -1M
```
```
XXX.entity.animal.Ocelot +1M -1M
```
```
XXX.entity.animal.Parrot +1M -1M
```
```
XXX.entity.animal.Pig +1M -1M
```
```
XXX.entity.animal.Rabbit +1M -1M
```
```
XXX.entity.animal.Squid +1M -1M
```
```
XXX.entity.animal.Turtle +1M -1M
```
```
XXX.animal.horse.AbstractHorse +2M -2M | -1P
```
```
XXX.animal.horse.Horse +1M -1M
```
```
XXX.animal.horse.Llama +1M -1M
```
```
XXX.animal.horse.SkeletonHorse +2M -1M
```
```
XXX.animal.horse.ZombieHorse +2M -1M
```
```
XXX.boss.enderdragon.EnderDragon +1M -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.monster.Silverfish +1M -1M
```
```
XXX.entity.monster.Slime -1M
```
```
XXX.entity.monster.Spider +1M -1M
```
```
XXX.entity.monster.Vindicator +1M -1M
```
```
XXX.entity.monster.Witch +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -1M | -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M | -1P
```
```
XXX.entity.projectile.FireworkRocketEntity -1M
```
```
XXX.entity.projectile.Projectile +6M | +2P
```
```
XXX.entity.projectile.ShulkerBullet +1M
```
```
XXX.world.item.ArmorItem +1P
```
```
XXX.world.item.DiggerItem +1P -1P
```
```
XXX.world.item.ItemStack +4M -5M
```
```
XXX.item.crafting.Ingredient +9M -9M | -1P
```
```
XXX.item.enchantment.EnchantmentCategory +1P -1P
```
```
XXX.item.enchantment.EnchantmentCategory$14 +2M
```
```
XXX.world.level.LevelAccessor +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M
```
```
XXX.block.grower.AbstractMegaTreeGrower +2M -2M
```
```
XXX.level.chunk.ChunkGenerator +5M -5M | +1P -1P
```
```
XXX.chunk.storage.ChunkStorage +1M -1M
```
```
XXX.chunk.storage.RegionFileStorage +2M -1M | +1P
```
```
XXX.level.levelgen.FlatLevelSource +2M -2M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +2M -1M
```
```
XXX.level.levelgen.OverworldLevelSource +1M -1M
```
```
XXX.levelgen.feature.AbstractFlowerFeature +1M -1M
```
```
XXX.levelgen.feature.AbstractSmallTreeFeature +1M -2M
```
```
XXX.levelgen.placement.ConfiguredDecorator +1M -1M
```
```
XXX.levelgen.structure.DesertPyramidPiece +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftStairs +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleEntrance +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$MonsterThrone +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$StairsRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom +1M -1M
```
```
XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece +1M -1M
```
```
XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$FillerCorridor +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$LeftTurn +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$PrisonHall +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$RoomCrossing +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StairsDown +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$Straight +1M -1M
```
```
XXX.levelgen.structure.StructureStart +1M -1M
```
```
XXX.levelgen.structure.SwamplandHutPiece +1M -1M
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```
```
XXX.loot.functions.SetAttributesFunction +1M -1M
```
```
XXX.loot.functions.SetAttributesFunction$ModifierBuilder +1M -1M | +1P -1P
```

</details>
















































<details>
<summary>
net.minecraft.advancements.critereon.FishingRodHookedTrigger
</summary>

```diff
+ boolean lambda$trigger$0(ServerPlayer,ItemStack,FishingHook,Collection,FishingRodHookedTrigger$TriggerInstance)
- boolean lambda$trigger$0(ServerPlayer,ItemStack,FishingHook,Collection,FishingRodHookedTrigger$TriggerInstance)
+ void trigger(ServerPlayer,ItemStack,FishingHook,Collection)
- void trigger(ServerPlayer,ItemStack,FishingHook,Collection)
```

</details>















































































<details>
<summary>
net.minecraft.commands.arguments.item.FunctionArgument
</summary>

```diff
+ Either getFunctionOrTag(CommandContext,String)
- Pair getFunctionOrTag(CommandContext,String)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.FunctionArgument$2
</summary>

```diff
+ Either unwrap(CommandContext)
- Pair unwrap(CommandContext)
```

</details>









































<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior
</summary>

```diff
- void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>





















































<details>
<summary>
net.minecraft.data.models.model.TextureSlot
</summary>

```diff
- String toString()
- TextureSlot create(String,TextureSlot)
- TextureSlot create(String)
+ TextureSlot valueOf(String)
+ TextureSlot[] values()
+ void <init>(String,int,String,TextureSlot)
+ void <init>(String,int,String)
- void <init>(String,TextureSlot)
```

</details>












<details>
<summary>
net.minecraft.data.tags.EntityTypeTagsProvider
</summary>

```diff
+ void useTags(TagCollection)
```

</details>
<details>
<summary>
net.minecraft.data.tags.ItemTagsProvider
</summary>

```diff
+ Tag$Entry copy(Tag$Entry)
+ void <clinit>()
- void <init>(DataGenerator,BlockTagsProvider)
+ void <init>(DataGenerator)
+ void copy(Tag,Tag)
- void copy(Tag$Named,Tag$Named)
+ void useTags(TagCollection)
```

</details>









<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ void <init>(File,String,Collection,BlockPos)
- void <init>(LevelStorageSource$LevelStorageAccess,Collection,BlockPos)
```

</details>










































































































































































































































<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- boolean forceSynchronousWrites()
- String getLevelIdName()
+ void <init>(File,DedicatedServerSettings,DataFixer,YggdrasilAuthenticationService,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory,String)
- void <init>(LevelStorageSource$LevelStorageAccess,DedicatedServerSettings,DataFixer,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
```

</details>























































































<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
+ int access$000()
+ Optional lambda$static$0(ResourceLocation)
+ Tag bind(String)
- Tag$Named bind(String)
+ TagCollection access$100()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
+ int access$000()
+ Optional lambda$static$0(ResourceLocation)
+ Tag bind(String)
- Tag$Named bind(String)
+ TagCollection access$100()
```

</details>
<details>
<summary>
net.minecraft.tags.Tag$Builder
</summary>

```diff
+ boolean canBuild(Function)
- boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$Entry)
- JsonObject serializeToJson()
+ JsonParseException lambda$addFromJson$0(ResourceLocation)
- Optional build(Function,Function)
- Stream getEntries()
- Stream getUnresolvedEntries(Function,Function)
+ Tag build(ResourceLocation)
+ Tag$Builder add(Collection)
+ Tag$Builder add(Object)
+ Tag$Builder add(Object[])
- Tag$Builder addElement(ResourceLocation)
+ Tag$Builder addFromJson(Function,JsonObject)
- Tag$Builder addFromJson(JsonObject)
+ Tag$Builder addTag(Tag)
+ Tag$Builder keepOrder(boolean)
- void lambda$null$0(Object)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag$TagEntry
</summary>

```diff
- boolean build(Function,Function,Consumer)
+ boolean canBuild(Function)
+ ResourceLocation getId()
- String toString()
+ void <init>(Tag)
+ void build(Collection)
+ void serializeTo(JsonArray,Function)
- void serializeTo(JsonArray)
```

</details>
<details>
<summary>
net.minecraft.tags.TagCollection
</summary>

```diff
- Map lambda$prepare$2(ResourceManager)
+ Map lambda$prepare$3(ResourceManager)
- Object lambda$load$3(ResourceLocation)
- ResourceLocation getId(Tag)
- ResourceLocation getId(Tag$Named)
- ResourceLocation getIdOrThrow(Tag)
- Tag$Builder lambda$null$1(ResourceLocation)
+ Tag$Builder lambda$null$2(ResourceLocation)
+ void <init>(Function,String,boolean,String)
- void <init>(Function,String,String)
- void lambda$load$4(Function,Function,ResourceLocation,Tag$Builder)
+ void lambda$load$4(ResourceLocation,Tag$Builder)
+ void lambda$load$5(Map,ResourceLocation,Tag$Builder)
+ void lambda$null$1(Tag$Builder)
```

</details>





<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- double inverseLerp(double,double,double)
+ double pct(double,double,double)
```

</details>

























































































<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeModifier
</summary>

```diff
- AttributeModifier load(CompoundTag)
+ AttributeModifier setSerialize(boolean)
+ boolean isSerializable()
- CompoundTag save()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.RangedAttribute
</summary>

```diff
+ RangedAttribute importLegacyName(String)
+ String getImportLegacyName()
+ void <init>(Attribute,String,double,double,double)
- void <init>(String,double,double,double)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.ai.behavior.LookAtTargetSink
</summary>

```diff
- boolean lambda$canStillUse$0(Mob,PositionTracker)
+ boolean lambda$canStillUse$0(Mob,PositionWrapper)
- void lambda$tick$1(Mob,PositionTracker)
+ void lambda$tick$1(Mob,PositionWrapper)
```

</details>







































































<details>
<summary>
net.minecraft.world.entity.ai.memory.WalkTarget
</summary>

```diff
- PositionTracker getTarget()
+ PositionWrapper getTarget()
- void <init>(PositionTracker,float,int)
+ void <init>(PositionWrapper,float,int)
```

</details>

























<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Fox
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>











<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- AttributeSupplier$Builder createBaseHorseAttributes()
+ boolean hurt(DamageSource,float)
- void randomizeAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- void randomizeAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.SkeletonHorse
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- void randomizeAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- void randomizeAttributes()
+ void registerAttributes()
```

</details>


<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>









<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>









<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
+ void registerAttributes()
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Spider
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.monster.Vindicator
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Witch
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
























<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- boolean canHitEntity(Entity)
+ boolean lambda$findHitEntity$0(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- boolean canHitEntity(Entity)
```

</details>


<details>
<summary>
net.minecraft.world.entity.projectile.FireworkRocketEntity
</summary>

```diff
+ boolean lambda$tick$1(Entity)
```

</details>

<details>
<summary>
net.minecraft.world.entity.projectile.Projectile
</summary>

```diff
- boolean canHitEntity(Entity)
- boolean checkLeftOwner()
- boolean lambda$checkLeftOwner$0(Entity)
- float lerpRotation(float,float)
- void tick()
- void updateRotation()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ShulkerBullet
</summary>

```diff
- boolean canHitEntity(Entity)
```

</details>














































































































<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
+ Component lambda$expandBlockState$1(Component)
- Component lambda$expandBlockState$2(Component)
+ DecimalFormat getAttributeDecimalFormat()
- void addAttributeModifier(Attribute,AttributeModifier,EquipmentSlot)
+ void addAttributeModifier(String,AttributeModifier,EquipmentSlot)
+ void lambda$appendEnchantmentNames$0(List,CompoundTag,Enchantment)
- void lambda$appendEnchantmentNames$1(List,CompoundTag,Enchantment)
+ void lambda$getAttributeModifiers$2(AttributeModifier)
- void lambda$static$0(DecimalFormat)
```

</details>






























<details>
<summary>
net.minecraft.world.item.crafting.Ingredient
</summary>

```diff
- boolean lambda$of$3(ItemStack)
+ boolean lambda$static$0(Ingredient$Value)
- Ingredient of(Stream)
- Ingredient$ItemValue lambda$fromNetwork$5(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$fromNetwork$6(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$of$4(ItemLike)
- Ingredient$ItemValue lambda$of$4(ItemStack)
+ Ingredient$ItemValue lambda$of$5(ItemStack)
- Ingredient$Value lambda$fromJson$6(JsonElement)
+ Ingredient$Value lambda$fromJson$7(JsonElement)
- Ingredient$Value[] lambda$new$0(int)
+ Ingredient$Value[] lambda$new$1(int)
- ItemStack[] lambda$dissolve$2(int)
+ ItemStack[] lambda$dissolve$3(int)
- JsonSyntaxException lambda$valueFromJson$7(ResourceLocation)
+ JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
- Stream lambda$dissolve$1(Ingredient$Value)
+ Stream lambda$dissolve$2(Ingredient$Value)
```

</details>























<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory$14
</summary>

```diff
- boolean lambda$canEnchant$0(EnchantmentCategory)
- boolean lambda$canEnchant$1(Item,EnchantmentCategory)
```

</details>






































<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
- Stream getEntityCollisions(Entity,AABB,Predicate)
+ Stream getEntityCollisions(Entity,AABB,Set)
```

</details>







































































<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- Direction getRandomOffset(Random)
```

</details>



























































































































































<details>
<summary>
net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
</summary>

```diff
+ boolean growTree(LevelAccessor,ChunkGenerator,BlockPos,BlockState,Random)
- boolean growTree(ServerLevel,ChunkGenerator,BlockPos,BlockState,Random)
+ boolean placeMega(LevelAccessor,ChunkGenerator,BlockPos,BlockState,Random,int,int)
- boolean placeMega(ServerLevel,ChunkGenerator,BlockPos,BlockState,Random,int,int)
```

</details>










































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ BlockPos findNearestMapFeature(Level,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ List getMobsAt(MobCategory,BlockPos)
- List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
- void applyBiomeDecoration(WorldGenRegion,StructureFeatureManager)
+ void applyBiomeDecoration(WorldGenRegion)
+ void createReferences(LevelAccessor,ChunkAccess)
- void createReferences(LevelAccessor,StructureFeatureManager,ChunkAccess)
+ void createStructures(BiomeManager,ChunkAccess,ChunkGenerator,StructureManager)
- void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager)
```

</details>


















<details>
<summary>
net.minecraft.world.level.chunk.storage.ChunkStorage
</summary>

```diff
- void <init>(File,DataFixer,boolean)
+ void <init>(File,DataFixer)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFileStorage
</summary>

```diff
- void <init>(File,boolean)
+ void <init>(File)
- void flush()
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ BlockPos findNearestMapFeature(Level,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ void fillFromNoise(LevelAccessor,ChunkAccess)
- void fillFromNoise(LevelAccessor,StructureFeatureManager,ChunkAccess)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ void fillFromNoise(LevelAccessor,ChunkAccess)
- void fillFromNoise(LevelAccessor,StructureFeatureManager,ChunkAccess)
- void lambda$fillFromNoise$1(ChunkPos,ObjectList,int,int,ObjectList,StructureStart)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.OverworldLevelSource
</summary>

```diff
+ List getMobsAt(MobCategory,BlockPos)
- List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
</summary>

```diff
- Optional getProjectedOrigin(LevelSimulatedRW,int,int,BlockPos,SmallTreeConfiguration)
+ Optional getProjectedOrigin(LevelSimulatedRW,int,int,int,BlockPos,SmallTreeConfiguration)
+ void placeTrunk(LevelSimulatedRW,Random,int,BlockPos,int,Set,BoundingBox,SmallTreeConfiguration)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ConfiguredFeature)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,ConfiguredFeature)
```

</details>























<details>
<summary>
net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart
</summary>

```diff
+ void postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos)
- void postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>































































































<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
- boolean convertLevel(LevelStorageSource$LevelStorageAccess,ProgressListener)
+ boolean convertLevel(Path,DataFixer,String,ProgressListener)
- void makeMcrLevelDatBackup(File)
+ void makeMcrLevelDatBackup(Path,String)
```

</details>

































































<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
- SetAttributesFunction$ModifierBuilder modifier(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
+ SetAttributesFunction$ModifierBuilder modifier(String,String,AttributeModifier$Operation,RandomValueBounds)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
</summary>

```diff
- void <init>(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
+ void <init>(String,String,AttributeModifier$Operation,RandomValueBounds)
```

</details>














































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
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
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
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
- net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.PaintingRenderer
- net.minecraft.client.renderer.entity.PandaRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
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
+ net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
- net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.TagManager$Preparations
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.Deserializer
- net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$1
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringUtil
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.BadRespawnPointDamage
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.EntityDamageSource
- net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgableMob
- net.minecraft.world.entity.AgableMob$AgableMobGroupData
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.BaseAttribute
+ net.minecraft.world.entity.ai.attributes.ModifiableAttributeInstance
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.BlockPosWrapper
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PositionWrapper
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveCallback
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.fishing.FishingHook$1
+ net.minecraft.world.entity.fishing.FishingHook$OpenWaterType
+ net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.global.LightningBolt
- net.minecraft.world.entity.global.package-info
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerableMount
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
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$1
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
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
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$1
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.SharedMonsterAttributes
- net.minecraft.world.entity.monster.Zoglin
+ net.minecraft.world.entity.monster.Zombie
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ net.minecraft.world.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.level.levelgen.feature.AcaciaFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
+ net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DarkOakFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertVillagePools
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.GroundBushFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaTreeFeature
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
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.PlainVillagePools
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.SavannaVillagePools
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SnowyVillagePools
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
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.TaigaVillagePools
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.VillagePieces
- net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelType
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PortalForcer
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.storage.LevelStorageSource$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.ShulkerSharedHelper
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.Snooper
- net.minecraft.world.Snooper$1
+ net.minecraft.world.SnooperPopulator
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.FishingRodHookedTrigger +2M -2M
```
```
XXX.minecraft.client.Minecraft +1M
```
```
XXX.components.toasts.SystemToast +3M
```
```
XXX.gui.screens.TitleScreen +1P
```
```
XXX.screens.worldselection.OptimizeWorldScreen +3M -1M
```
```
XXX.renderer.debug.CollisionBoxRenderer +1M
```
```
XXX.client.server.IntegratedServer +2M -2M
```
```
XXX.arguments.item.FunctionArgument +1M -1M
```
```
XXX.arguments.item.FunctionArgument$2 +1M -1M
```
```
XXX.core.dispenser.DispenseItemBehavior +1M
```
```
XXX.models.model.TextureSlot +4M -4M | -1P
```
```
XXX.data.tags.EntityTypeTagsProvider -1M
```
```
XXX.data.tags.ItemTagsProvider +2M -5M | +1P -1P
```
```
XXX.gametest.framework.GameTestServer +1M -1M
```
```
XXX.server.dedicated.DedicatedServer +3M -1M
```
```
XXX.server.level.WorldGenRegion +2P
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.BlockTags +1M -4M | +74P -75P
```
```
XXX.minecraft.tags.FluidTags +1M -4M | +3P -4P
```
```
XXX.minecraft.tags.Tag$Builder +8M -9M | +1P -2P
```
```
XXX.minecraft.tags.Tag$TagEntry +3M -5M | -1P
```
```
XXX.minecraft.tags.TagCollection +8M -6M | +2P -2P
```
```
XXX.minecraft.util.Mth +1M -1M
```
```
XXX.ai.attributes.AttributeModifier +3M -2M | +1P -1P
```
```
XXX.ai.attributes.RangedAttribute +1M -3M | -1P
```
```
XXX.ai.behavior.LookAtTargetSink +2M -2M
```
```
XXX.ai.memory.MemoryModuleType +2P -2P
```
```
XXX.ai.memory.WalkTarget +2M -2M | +1P -1P
```
```
XXX.ai.navigation.PathNavigation -1P
```
```
XXX.entity.animal.Bee +1M -1M
```
```
XXX.entity.animal.Cat +1M -1M
```
```
XXX.entity.animal.Chicken +1M -1M
```
```
XXX.entity.animal.Cow +1M -1M
```
```
XXX.entity.animal.Fox +1M -1M
```
```
XXX.entity.animal.IronGolem +1M -1M
```
```
XXX.entity.animal.Ocelot +1M -1M
```
```
XXX.entity.animal.Parrot +1M -1M
```
```
XXX.entity.animal.Pig +1M -1M
```
```
XXX.entity.animal.Rabbit +1M -1M
```
```
XXX.entity.animal.Squid +1M -1M
```
```
XXX.entity.animal.Turtle +1M -1M
```
```
XXX.animal.horse.AbstractHorse +2M -2M | -1P
```
```
XXX.animal.horse.Horse +1M -1M
```
```
XXX.animal.horse.Llama +1M -1M
```
```
XXX.animal.horse.SkeletonHorse +2M -1M
```
```
XXX.animal.horse.ZombieHorse +2M -1M
```
```
XXX.boss.enderdragon.EnderDragon +1M -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.monster.Silverfish +1M -1M
```
```
XXX.entity.monster.Slime -1M
```
```
XXX.entity.monster.Spider +1M -1M
```
```
XXX.entity.monster.Vindicator +1M -1M
```
```
XXX.entity.monster.Witch +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -1M | -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M | -1P
```
```
XXX.entity.projectile.FireworkRocketEntity -1M
```
```
XXX.entity.projectile.Projectile +6M | +2P
```
```
XXX.entity.projectile.ShulkerBullet +1M
```
```
XXX.world.item.ArmorItem +1P
```
```
XXX.world.item.DiggerItem +1P -1P
```
```
XXX.world.item.ItemStack +4M -5M
```
```
XXX.item.crafting.Ingredient +9M -9M | -1P
```
```
XXX.item.enchantment.EnchantmentCategory +1P -1P
```
```
XXX.item.enchantment.EnchantmentCategory$14 +2M
```
```
XXX.world.level.LevelAccessor +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M
```
```
XXX.block.grower.AbstractMegaTreeGrower +2M -2M
```
```
XXX.level.chunk.ChunkGenerator +5M -5M | +1P -1P
```
```
XXX.chunk.storage.ChunkStorage +1M -1M
```
```
XXX.chunk.storage.RegionFileStorage +2M -1M | +1P
```
```
XXX.level.levelgen.FlatLevelSource +2M -2M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +2M -1M
```
```
XXX.level.levelgen.OverworldLevelSource +1M -1M
```
```
XXX.levelgen.feature.AbstractFlowerFeature +1M -1M
```
```
XXX.levelgen.feature.AbstractSmallTreeFeature +1M -2M
```
```
XXX.levelgen.placement.ConfiguredDecorator +1M -1M
```
```
XXX.levelgen.structure.DesertPyramidPiece +1M -1M
```
```
XXX.levelgen.structure.JunglePyramidPiece +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftStairs +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleEntrance +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$MonsterThrone +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces$StairsRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom +1M -1M
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom +1M -1M
```
```
XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece +1M -1M
```
```
XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$FillerCorridor +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$LeftTurn +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$PrisonHall +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$RoomCrossing +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$StairsDown +1M -1M
```
```
XXX.levelgen.structure.StrongholdPieces$Straight +1M -1M
```
```
XXX.levelgen.structure.StructureStart +1M -1M
```
```
XXX.levelgen.structure.SwamplandHutPiece +1M -1M
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```
```
XXX.loot.functions.SetAttributesFunction +1M -1M
```
```
XXX.loot.functions.SetAttributesFunction$ModifierBuilder +1M -1M | +1P -1P
```

</details>


























































































































































































<details>
<summary>
net.minecraft.advancements.critereon.FishingRodHookedTrigger
</summary>

```diff
+ boolean lambda$trigger$0(ServerPlayer,ItemStack,FishingHook,Collection,FishingRodHookedTrigger$TriggerInstance)
- boolean lambda$trigger$0(ServerPlayer,ItemStack,FishingHook,Collection,FishingRodHookedTrigger$TriggerInstance)
+ void trigger(ServerPlayer,ItemStack,FishingHook,Collection)
- void trigger(ServerPlayer,ItemStack,FishingHook,Collection)
```

</details>















































<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- boolean shouldEntityAppearGlowing(Entity)
```

</details>












































<details>
<summary>
net.minecraft.client.gui.components.toasts.SystemToast
</summary>

```diff
- void add(ToastComponent,SystemToast$SystemToastIds,Component,Component)
- void onWorldAccessFailure(Minecraft,String)
- void onWorldDeleteFailure(Minecraft,String)
```

</details>
















































































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
</summary>

```diff
- OptimizeWorldScreen create(BooleanConsumer,LevelStorageSource$LevelStorageAccess,boolean)
- void <init>(BooleanConsumer,LevelStorageSource$LevelStorageAccess,LevelData,boolean)
+ void <init>(BooleanConsumer,String,LevelStorageSource,boolean)
- void onClose()
```

</details>


































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.debug.CollisionBoxRenderer
</summary>

```diff
- boolean lambda$render$0(Entity)
```

</details>


























































































<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- void <init>(Minecraft,LevelStorageSource$LevelStorageAccess,String,LevelSettings,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
+ void <init>(Minecraft,String,String,LevelSettings,YggdrasilAuthenticationService,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
- void loadLevel(String,long,ChunkGeneratorProvider)
+ void loadLevel(String,String,long,ChunkGeneratorProvider)
```

</details>




























































<details>
<summary>
net.minecraft.commands.arguments.item.FunctionArgument
</summary>

```diff
+ Either getFunctionOrTag(CommandContext,String)
- Pair getFunctionOrTag(CommandContext,String)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.FunctionArgument$2
</summary>

```diff
+ Either unwrap(CommandContext)
- Pair unwrap(CommandContext)
```

</details>









































<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior
</summary>

```diff
- void setEntityPokingOutOfBlock(BlockSource,Entity,Direction)
```

</details>





















































<details>
<summary>
net.minecraft.data.models.model.TextureSlot
</summary>

```diff
- String toString()
- TextureSlot create(String,TextureSlot)
- TextureSlot create(String)
+ TextureSlot valueOf(String)
+ TextureSlot[] values()
+ void <init>(String,int,String,TextureSlot)
+ void <init>(String,int,String)
- void <init>(String,TextureSlot)
```

</details>












<details>
<summary>
net.minecraft.data.tags.EntityTypeTagsProvider
</summary>

```diff
+ void useTags(TagCollection)
```

</details>
<details>
<summary>
net.minecraft.data.tags.ItemTagsProvider
</summary>

```diff
+ Tag$Entry copy(Tag$Entry)
+ void <clinit>()
- void <init>(DataGenerator,BlockTagsProvider)
+ void <init>(DataGenerator)
+ void copy(Tag,Tag)
- void copy(Tag$Named,Tag$Named)
+ void useTags(TagCollection)
```

</details>









<details>
<summary>
net.minecraft.gametest.framework.GameTestServer
</summary>

```diff
+ void <init>(File,String,Collection,BlockPos)
- void <init>(LevelStorageSource$LevelStorageAccess,Collection,BlockPos)
```

</details>
















































































































































































































































<details>
<summary>
net.minecraft.server.dedicated.DedicatedServer
</summary>

```diff
- boolean forceSynchronousWrites()
- String getLevelIdName()
+ void <init>(File,DedicatedServerSettings,DataFixer,YggdrasilAuthenticationService,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory,String)
- void <init>(LevelStorageSource$LevelStorageAccess,DedicatedServerSettings,DataFixer,MinecraftSessionService,GameProfileRepository,GameProfileCache,ChunkProgressListenerFactory)
```

</details>























































































<details>
<summary>
net.minecraft.tags.BlockTags
</summary>

```diff
+ int access$000()
+ Optional lambda$static$0(ResourceLocation)
+ Tag bind(String)
- Tag$Named bind(String)
+ TagCollection access$100()
```

</details>
<details>
<summary>
net.minecraft.tags.FluidTags
</summary>

```diff
+ int access$000()
+ Optional lambda$static$0(ResourceLocation)
+ Tag bind(String)
- Tag$Named bind(String)
+ TagCollection access$100()
```

</details>
<details>
<summary>
net.minecraft.tags.Tag$Builder
</summary>

```diff
+ boolean canBuild(Function)
- boolean lambda$getUnresolvedEntries$1(Function,Function,Tag$Entry)
- JsonObject serializeToJson()
+ JsonParseException lambda$addFromJson$0(ResourceLocation)
- Optional build(Function,Function)
- Stream getEntries()
- Stream getUnresolvedEntries(Function,Function)
+ Tag build(ResourceLocation)
+ Tag$Builder add(Collection)
+ Tag$Builder add(Object)
+ Tag$Builder add(Object[])
- Tag$Builder addElement(ResourceLocation)
+ Tag$Builder addFromJson(Function,JsonObject)
- Tag$Builder addFromJson(JsonObject)
+ Tag$Builder addTag(Tag)
+ Tag$Builder keepOrder(boolean)
- void lambda$null$0(Object)
```

</details>
<details>
<summary>
net.minecraft.tags.Tag$TagEntry
</summary>

```diff
- boolean build(Function,Function,Consumer)
+ boolean canBuild(Function)
+ ResourceLocation getId()
- String toString()
+ void <init>(Tag)
+ void build(Collection)
+ void serializeTo(JsonArray,Function)
- void serializeTo(JsonArray)
```

</details>
<details>
<summary>
net.minecraft.tags.TagCollection
</summary>

```diff
- Map lambda$prepare$2(ResourceManager)
+ Map lambda$prepare$3(ResourceManager)
- Object lambda$load$3(ResourceLocation)
- ResourceLocation getId(Tag)
- ResourceLocation getId(Tag$Named)
- ResourceLocation getIdOrThrow(Tag)
- Tag$Builder lambda$null$1(ResourceLocation)
+ Tag$Builder lambda$null$2(ResourceLocation)
+ void <init>(Function,String,boolean,String)
- void <init>(Function,String,String)
- void lambda$load$4(Function,Function,ResourceLocation,Tag$Builder)
+ void lambda$load$4(ResourceLocation,Tag$Builder)
+ void lambda$load$5(Map,ResourceLocation,Tag$Builder)
+ void lambda$null$1(Tag$Builder)
```

</details>





<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- double inverseLerp(double,double,double)
+ double pct(double,double,double)
```

</details>

























































































<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeModifier
</summary>

```diff
- AttributeModifier load(CompoundTag)
+ AttributeModifier setSerialize(boolean)
+ boolean isSerializable()
- CompoundTag save()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.RangedAttribute
</summary>

```diff
+ RangedAttribute importLegacyName(String)
+ String getImportLegacyName()
+ void <init>(Attribute,String,double,double,double)
- void <init>(String,double,double,double)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.ai.behavior.LookAtTargetSink
</summary>

```diff
- boolean lambda$canStillUse$0(Mob,PositionTracker)
+ boolean lambda$canStillUse$0(Mob,PositionWrapper)
- void lambda$tick$1(Mob,PositionTracker)
+ void lambda$tick$1(Mob,PositionWrapper)
```

</details>







































































<details>
<summary>
net.minecraft.world.entity.ai.memory.WalkTarget
</summary>

```diff
- PositionTracker getTarget()
+ PositionWrapper getTarget()
- void <init>(PositionTracker,float,int)
+ void <init>(PositionWrapper,float,int)
```

</details>

























<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Cat
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Fox
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>











<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Turtle
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- AttributeSupplier$Builder createBaseHorseAttributes()
+ boolean hurt(DamageSource,float)
- void randomizeAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- void randomizeAttributes()
+ void registerAttributes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.SkeletonHorse
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- void randomizeAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.horse.ZombieHorse
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
- void randomizeAttributes()
+ void registerAttributes()
```

</details>


<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>









<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>









<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Slime
</summary>

```diff
+ void registerAttributes()
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Spider
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>






<details>
<summary>
net.minecraft.world.entity.monster.Vindicator
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.Witch
</summary>

```diff
- AttributeSupplier$Builder createAttributes()
+ void registerAttributes()
```

</details>
























<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- boolean canHitEntity(Entity)
+ boolean lambda$findHitEntity$0(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- boolean canHitEntity(Entity)
```

</details>


<details>
<summary>
net.minecraft.world.entity.projectile.FireworkRocketEntity
</summary>

```diff
+ boolean lambda$tick$1(Entity)
```

</details>

<details>
<summary>
net.minecraft.world.entity.projectile.Projectile
</summary>

```diff
- boolean canHitEntity(Entity)
- boolean checkLeftOwner()
- boolean lambda$checkLeftOwner$0(Entity)
- float lerpRotation(float,float)
- void tick()
- void updateRotation()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ShulkerBullet
</summary>

```diff
- boolean canHitEntity(Entity)
```

</details>














































































































<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
+ Component lambda$expandBlockState$1(Component)
- Component lambda$expandBlockState$2(Component)
+ DecimalFormat getAttributeDecimalFormat()
- void addAttributeModifier(Attribute,AttributeModifier,EquipmentSlot)
+ void addAttributeModifier(String,AttributeModifier,EquipmentSlot)
+ void lambda$appendEnchantmentNames$0(List,CompoundTag,Enchantment)
- void lambda$appendEnchantmentNames$1(List,CompoundTag,Enchantment)
+ void lambda$getAttributeModifiers$2(AttributeModifier)
- void lambda$static$0(DecimalFormat)
```

</details>






























<details>
<summary>
net.minecraft.world.item.crafting.Ingredient
</summary>

```diff
- boolean lambda$of$3(ItemStack)
+ boolean lambda$static$0(Ingredient$Value)
- Ingredient of(Stream)
- Ingredient$ItemValue lambda$fromNetwork$5(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$fromNetwork$6(FriendlyByteBuf)
+ Ingredient$ItemValue lambda$of$4(ItemLike)
- Ingredient$ItemValue lambda$of$4(ItemStack)
+ Ingredient$ItemValue lambda$of$5(ItemStack)
- Ingredient$Value lambda$fromJson$6(JsonElement)
+ Ingredient$Value lambda$fromJson$7(JsonElement)
- Ingredient$Value[] lambda$new$0(int)
+ Ingredient$Value[] lambda$new$1(int)
- ItemStack[] lambda$dissolve$2(int)
+ ItemStack[] lambda$dissolve$3(int)
- JsonSyntaxException lambda$valueFromJson$7(ResourceLocation)
+ JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
- Stream lambda$dissolve$1(Ingredient$Value)
+ Stream lambda$dissolve$2(Ingredient$Value)
```

</details>























<details>
<summary>
net.minecraft.world.item.enchantment.EnchantmentCategory$14
</summary>

```diff
- boolean lambda$canEnchant$0(EnchantmentCategory)
- boolean lambda$canEnchant$1(Item,EnchantmentCategory)
```

</details>






































<details>
<summary>
net.minecraft.world.level.LevelAccessor
</summary>

```diff
- Stream getEntityCollisions(Entity,AABB,Predicate)
+ Stream getEntityCollisions(Entity,AABB,Set)
```

</details>







































































<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- Direction getRandomOffset(Random)
```

</details>



























































































































































<details>
<summary>
net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
</summary>

```diff
+ boolean growTree(LevelAccessor,ChunkGenerator,BlockPos,BlockState,Random)
- boolean growTree(ServerLevel,ChunkGenerator,BlockPos,BlockState,Random)
+ boolean placeMega(LevelAccessor,ChunkGenerator,BlockPos,BlockState,Random,int,int)
- boolean placeMega(ServerLevel,ChunkGenerator,BlockPos,BlockState,Random,int,int)
```

</details>










































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ BlockPos findNearestMapFeature(Level,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ List getMobsAt(MobCategory,BlockPos)
- List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
- void applyBiomeDecoration(WorldGenRegion,StructureFeatureManager)
+ void applyBiomeDecoration(WorldGenRegion)
+ void createReferences(LevelAccessor,ChunkAccess)
- void createReferences(LevelAccessor,StructureFeatureManager,ChunkAccess)
+ void createStructures(BiomeManager,ChunkAccess,ChunkGenerator,StructureManager)
- void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager)
```

</details>


















<details>
<summary>
net.minecraft.world.level.chunk.storage.ChunkStorage
</summary>

```diff
- void <init>(File,DataFixer,boolean)
+ void <init>(File,DataFixer)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.storage.RegionFileStorage
</summary>

```diff
- void <init>(File,boolean)
+ void <init>(File)
- void flush()
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ BlockPos findNearestMapFeature(Level,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ void fillFromNoise(LevelAccessor,ChunkAccess)
- void fillFromNoise(LevelAccessor,StructureFeatureManager,ChunkAccess)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ void fillFromNoise(LevelAccessor,ChunkAccess)
- void fillFromNoise(LevelAccessor,StructureFeatureManager,ChunkAccess)
- void lambda$fillFromNoise$1(ChunkPos,ObjectList,int,int,ObjectList,StructureStart)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.OverworldLevelSource
</summary>

```diff
+ List getMobsAt(MobCategory,BlockPos)
- List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
</summary>

```diff
- Optional getProjectedOrigin(LevelSimulatedRW,int,int,BlockPos,SmallTreeConfiguration)
+ Optional getProjectedOrigin(LevelSimulatedRW,int,int,int,BlockPos,SmallTreeConfiguration)
+ void placeTrunk(LevelSimulatedRW,Random,int,BlockPos,int,Set,BoundingBox,SmallTreeConfiguration)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ConfiguredFeature)
- boolean place(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BlockPos,ConfiguredFeature)
```

</details>























<details>
<summary>
net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart
</summary>

```diff
+ void postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos)
- void postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
</summary>

```diff
+ boolean postProcess(LevelAccessor,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
- boolean postProcess(LevelAccessor,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos,BlockPos)
```

</details>































































































<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
- boolean convertLevel(LevelStorageSource$LevelStorageAccess,ProgressListener)
+ boolean convertLevel(Path,DataFixer,String,ProgressListener)
- void makeMcrLevelDatBackup(File)
+ void makeMcrLevelDatBackup(Path,String)
```

</details>

































































<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
- SetAttributesFunction$ModifierBuilder modifier(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
+ SetAttributesFunction$ModifierBuilder modifier(String,String,AttributeModifier$Operation,RandomValueBounds)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
</summary>

```diff
- void <init>(String,Attribute,AttributeModifier$Operation,RandomValueBounds)
+ void <init>(String,String,AttributeModifier$Operation,RandomValueBounds)
```

</details>
</details>