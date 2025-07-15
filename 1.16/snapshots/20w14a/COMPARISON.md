## Comparison with [20w13b](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w13b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w13b</th><th>20w14a</th></tr><tr><td>World version</td><td><pre>2521</pre></td><td><pre>2524</pre></td></tr><tr><td>Protocol version</td><td><pre>709</pre></td><td><pre>710</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w13b</th><th>20w14a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ attributes.txt
+ trunk_placer_type.txt
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:zoglin
```

</details>
<details>
<summary>
feature
</summary>

```diff
- minecraft:acacia_tree
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:zoglin_spawn_egg
```

</details>
<details>
<summary>
memory_module_type
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
sound_event
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
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<br/>
<table>
<tr><th>Name</th><th>20w13b</th><th>20w14a</th></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.iron_trapdoor.close</div></th><td>Trapdoor opens</td><td>Trapdoor closes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.iron_trapdoor.open</div></th><td>Trapdoor closes</td><td>Trapdoor opens</td></tr>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.BaseAttribute
+ XXX.ai.attributes.ModifiableAttributeInstance
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.BlockPosWrapper
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PositionWrapper
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
- XXX.entity.ai.Brain
+ XXX.entity.fishing.FishingHook$1
+ XXX.entity.fishing.FishingHook$OpenWaterType
+ XXX.entity.global.LightningBolt
- XXX.entity.global.package-info
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$1
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$1
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Ravager$1
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.SharedMonsterAttributes
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.feature.blockplacers.BlockPlacer
- XXX.feature.blockplacers.BlockPlacerType
+ XXX.feature.blockplacers.ColumnPlacer
- XXX.feature.blockplacers.DoublePlantPlacer
- XXX.feature.blockplacers.package-info
+ XXX.feature.blockplacers.SimpleBlockPlacer
+ XXX.feature.configurations.BlockBlobConfiguration
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.BuriedTreasureConfiguration
+ XXX.feature.configurations.ChanceRangeDecoratorConfiguration
- XXX.feature.configurations.CountFeatureConfiguration
+ XXX.feature.configurations.CountRangeDecoratorConfiguration
- XXX.feature.configurations.DecoratedFeatureConfiguration
+ XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.FeatureRadiusConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MegaTreeConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NoiseDependantDecoratorConfiguration
- XXX.feature.configurations.NoneDecoratorConfiguration
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OceanRuinConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$Predicates
- XXX.feature.configurations.package-info
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration$1
- XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ XXX.feature.configurations.RandomRandomFeatureConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration
- XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.VillageConfiguration
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.levelgen.feature.AcaciaFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature
+ XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.NoSurfaceOreFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowyVillagePools
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
- XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces
- XXX.levelgen.feature.VillagePieces$VillagePiece
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedConfiguredFeature
+ XXX.levelgen.feature.WoodlandMansionFeature
- XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.TagManager$Preparations
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.Deserializer
- XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.package-info
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
- XXX.minecraft.world.ShulkerSharedHelper
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.OminousBannerBlockEntityRenameFix
+ XXX.util.datafix.OminousBannerRenameFix
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$1
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.world.damagesource.BadRespawnPointDamage
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.EntityDamageSource
- XXX.world.damagesource.IndirectEntityDamageSource
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgableMob
- XXX.world.entity.AgableMob$AgableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveCallback
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerableMount
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.BaseAttribute
+ XXX.ai.attributes.ModifiableAttributeInstance
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.BlockPosWrapper
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PositionWrapper
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
- XXX.entity.ai.Brain
+ XXX.entity.fishing.FishingHook$1
+ XXX.entity.fishing.FishingHook$OpenWaterType
+ XXX.entity.global.LightningBolt
- XXX.entity.global.package-info
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$1
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$1
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Ravager$1
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.SharedMonsterAttributes
- XXX.entity.monster.Zoglin
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.feature.blockplacers.BlockPlacer
- XXX.feature.blockplacers.BlockPlacerType
+ XXX.feature.blockplacers.ColumnPlacer
- XXX.feature.blockplacers.DoublePlantPlacer
- XXX.feature.blockplacers.package-info
+ XXX.feature.blockplacers.SimpleBlockPlacer
+ XXX.feature.configurations.BlockBlobConfiguration
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.BuriedTreasureConfiguration
+ XXX.feature.configurations.ChanceRangeDecoratorConfiguration
- XXX.feature.configurations.CountFeatureConfiguration
+ XXX.feature.configurations.CountRangeDecoratorConfiguration
- XXX.feature.configurations.DecoratedFeatureConfiguration
+ XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.FeatureRadiusConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MegaTreeConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NoiseDependantDecoratorConfiguration
- XXX.feature.configurations.NoneDecoratorConfiguration
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OceanRuinConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$Predicates
- XXX.feature.configurations.package-info
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration$1
- XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
+ XXX.feature.configurations.RandomRandomFeatureConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration
- XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.VillageConfiguration
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.ForestFlowerProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.PlainFlowerProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.levelgen.feature.AcaciaFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature
+ XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.NoSurfaceOreFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowyVillagePools
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
- XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces
- XXX.levelgen.feature.VillagePieces$VillagePiece
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedConfiguredFeature
+ XXX.levelgen.feature.WoodlandMansionFeature
- XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.TagManager$Preparations
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.Deserializer
- XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.package-info
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
- XXX.minecraft.world.ShulkerSharedHelper
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AreaEffectCloudRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
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
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SheepRenderer
+ XXX.renderer.entity.ShulkerBulletRenderer
- XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.SilverfishRenderer
- XXX.renderer.entity.SkeletonRenderer
+ XXX.renderer.entity.SlimeRenderer
- XXX.renderer.entity.SnowGolemRenderer
+ XXX.renderer.entity.SpectralArrowRenderer
- XXX.renderer.entity.SpiderRenderer
+ XXX.renderer.entity.SquidRenderer
- XXX.renderer.entity.StrayRenderer
+ XXX.renderer.entity.StriderRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WitchRenderer
- XXX.renderer.entity.WitherBossRenderer
+ XXX.renderer.entity.WitherSkeletonRenderer
- XXX.renderer.entity.WitherSkullRenderer
+ XXX.renderer.entity.WolfRenderer
- XXX.renderer.entity.ZoglinRenderer
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.OminousBannerBlockEntityRenameFix
+ XXX.util.datafix.OminousBannerRenameFix
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$1
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.world.damagesource.BadRespawnPointDamage
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.EntityDamageSource
- XXX.world.damagesource.IndirectEntityDamageSource
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgableMob
- XXX.world.entity.AgableMob$AgableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveCallback
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerableMount
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
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
<hr/>