## Comparison with [24w09a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w09a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">24w09a</th><th>24w10a</th></tr><tr><td>DataPack version</td><td><code>33</code></td><td><code>34</code></td></tr><tr><td>World version</td><td><code>3819</code></td><td><code>3821</code></td></tr><tr><td>Protocol version</td><td><code>1073742002</code></td><td><code>1073742003</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
- banner_pattern.txt
```

</details>









<details>
<summary>
command_argument_type.txt
</summary>

```diff
+ minecraft:item_slots
```

</details>


<details>
<summary>
data_component_type.txt
</summary>

```diff
- minecraft:lodestone_target
+ minecraft:lodestone_tracker
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
- universal_tags/banner_pattern.json
```

</details>















<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:item_slots
```

</details>


<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
- minecraft:lodestone_target
+ minecraft:lodestone_tracker
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
execute
</summary>

```diff
+ execute if items block <pos: block_pos> <slots: item_slots> <item_predicate: item_predicate>
+ execute if items entity <entities: entity> <slots: item_slots> <item_predicate: item_predicate>
+ execute unless items block <pos: block_pos> <slots: item_slots> <item_predicate: item_predicate>
+ execute unless items entity <entities: entity> <slots: item_slots> <item_predicate: item_predicate>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ arguments.item.component.repeated: Item component '%s' was repeated, but only one value can be specified
+ slot.only_single_allowed: Only single slots allowed, got '%s'
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/banner_pattern/base.json
+ minecraft/banner_pattern/border.json
+ minecraft/banner_pattern/bricks.json
+ minecraft/banner_pattern/circle.json
+ minecraft/banner_pattern/creeper.json
+ minecraft/banner_pattern/cross.json
+ minecraft/banner_pattern/curly_border.json
+ minecraft/banner_pattern/diagonal_left.json
+ minecraft/banner_pattern/diagonal_right.json
+ minecraft/banner_pattern/diagonal_up_left.json
+ minecraft/banner_pattern/diagonal_up_right.json
+ minecraft/banner_pattern/flower.json
+ minecraft/banner_pattern/globe.json
+ minecraft/banner_pattern/gradient_up.json
+ minecraft/banner_pattern/gradient.json
+ minecraft/banner_pattern/half_horizontal_bottom.json
+ minecraft/banner_pattern/half_horizontal.json
+ minecraft/banner_pattern/half_vertical_right.json
+ minecraft/banner_pattern/half_vertical.json
+ minecraft/banner_pattern/mojang.json
+ minecraft/banner_pattern/piglin.json
+ minecraft/banner_pattern/rhombus.json
+ minecraft/banner_pattern/skull.json
+ minecraft/banner_pattern/small_stripes.json
+ minecraft/banner_pattern/square_bottom_left.json
+ minecraft/banner_pattern/square_bottom_right.json
+ minecraft/banner_pattern/square_top_left.json
+ minecraft/banner_pattern/square_top_right.json
+ minecraft/banner_pattern/straight_cross.json
+ minecraft/banner_pattern/stripe_bottom.json
+ minecraft/banner_pattern/stripe_center.json
+ minecraft/banner_pattern/stripe_downleft.json
+ minecraft/banner_pattern/stripe_downright.json
+ minecraft/banner_pattern/stripe_left.json
+ minecraft/banner_pattern/stripe_middle.json
+ minecraft/banner_pattern/stripe_right.json
+ minecraft/banner_pattern/stripe_top.json
+ minecraft/banner_pattern/triangle_bottom.json
+ minecraft/banner_pattern/triangle_top.json
+ minecraft/banner_pattern/triangles_bottom.json
+ minecraft/banner_pattern/triangles_top.json
+ minecraft/wolf_variant/ashen.json
+ minecraft/wolf_variant/black.json
+ minecraft/wolf_variant/chestnut.json
+ minecraft/wolf_variant/pale.json
+ minecraft/wolf_variant/rusty.json
+ minecraft/wolf_variant/snowy.json
+ minecraft/wolf_variant/spotted.json
+ minecraft/wolf_variant/striped.json
+ minecraft/wolf_variant/woods.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/entity/wolf/wolf_ashen_angry.png
+ minecraft/textures/entity/wolf/wolf_ashen_tame.png
+ minecraft/textures/entity/wolf/wolf_ashen.png
+ minecraft/textures/entity/wolf/wolf_black_angry.png
+ minecraft/textures/entity/wolf/wolf_black_tame.png
+ minecraft/textures/entity/wolf/wolf_black.png
+ minecraft/textures/entity/wolf/wolf_chestnut_angry.png
+ minecraft/textures/entity/wolf/wolf_chestnut_tame.png
+ minecraft/textures/entity/wolf/wolf_chestnut.png
+ minecraft/textures/entity/wolf/wolf_rusty_angry.png
+ minecraft/textures/entity/wolf/wolf_rusty_tame.png
+ minecraft/textures/entity/wolf/wolf_rusty.png
+ minecraft/textures/entity/wolf/wolf_snowy_angry.png
+ minecraft/textures/entity/wolf/wolf_snowy_tame.png
+ minecraft/textures/entity/wolf/wolf_snowy.png
+ minecraft/textures/entity/wolf/wolf_spotted_angry.png
+ minecraft/textures/entity/wolf/wolf_spotted_tame.png
+ minecraft/textures/entity/wolf/wolf_spotted.png
+ minecraft/textures/entity/wolf/wolf_striped_angry.png
+ minecraft/textures/entity/wolf/wolf_striped_tame.png
+ minecraft/textures/entity/wolf/wolf_striped.png
+ minecraft/textures/entity/wolf/wolf_woods_angry.png
+ minecraft/textures/entity/wolf/wolf_woods_tame.png
+ minecraft/textures/entity/wolf/wolf_woods.png
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:item_slots
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
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.StartRidingTrigger
+ net.minecraft.advancements.critereon.StartRidingTrigger$TriggerInstance
- net.minecraft.advancements.critereon.StatePropertiesPredicate
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
- net.minecraft.advancements.critereon.SummonedEntityTrigger
+ net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TagPredicate
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsingItemTrigger
- net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.package-info
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.ArgumentSignatures
- net.minecraft.commands.arguments.ArgumentSignatures$Entry
+ net.minecraft.commands.arguments.ArgumentSignatures$Signer
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Info
- net.minecraft.commands.arguments.EntityArgument$Info$Template
+ net.minecraft.commands.arguments.GameModeArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
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
- net.minecraft.commands.arguments.ResourceArgument
+ net.minecraft.commands.arguments.ResourceArgument$Info
- net.minecraft.commands.arguments.ResourceArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
- net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.SignedArgument
- net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CacheableFunction
- net.minecraft.commands.CommandBuildContext
+ net.minecraft.commands.CommandBuildContext$1
- net.minecraft.commands.CommandResultCallback
+ net.minecraft.commands.CommandResultCallback$1
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$1
- net.minecraft.commands.Commands$1$1
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSigningContext
+ net.minecraft.commands.CommandSigningContext$1
- net.minecraft.commands.CommandSigningContext$SignedArguments
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.ExecutionCommandSource
- net.minecraft.commands.FunctionInstantiationException
+ net.minecraft.commands.ParserUtils
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ net.minecraft.util.datafix.fixes.ItemStackComponentizationFix
- net.minecraft.util.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- net.minecraft.util.datafix.fixes.ItemStackComponentRemainderFix
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
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerHeadBlockProfileFix
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
- net.minecraft.util.datafix.fixes.PrimedTntBlockStateFixer
+ net.minecraft.util.datafix.fixes.RandomSequenceSettingsFix
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RemapChunkStatusFix
+ net.minecraft.util.datafix.fixes.RemoveGolemGossipFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.RenameEnchantmentsFix
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
+ net.minecraft.util.datafix.fixes.TippedArrowPotionToItemFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VariantRenameFix
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.schemas.NamespacedSchema
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
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
- net.minecraft.util.datafix.schemas.V1451_6$1
+ net.minecraft.util.datafix.schemas.V1451_6$2
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V3076
+ net.minecraft.util.datafix.schemas.V3078
- net.minecraft.util.datafix.schemas.V3081
+ net.minecraft.util.datafix.schemas.V3082
- net.minecraft.util.datafix.schemas.V3083
+ net.minecraft.util.datafix.schemas.V3202
- net.minecraft.util.datafix.schemas.V3203
+ net.minecraft.util.datafix.schemas.V3204
- net.minecraft.util.datafix.schemas.V3325
+ net.minecraft.util.datafix.schemas.V3326
- net.minecraft.util.datafix.schemas.V3327
+ net.minecraft.util.datafix.schemas.V3328
- net.minecraft.util.datafix.schemas.V3438
+ net.minecraft.util.datafix.schemas.V3448
- net.minecraft.util.datafix.schemas.V3682
+ net.minecraft.util.datafix.schemas.V3683
- net.minecraft.util.datafix.schemas.V3685
+ net.minecraft.util.datafix.schemas.V3689
- net.minecraft.util.datafix.schemas.V3799
+ net.minecraft.util.datafix.schemas.V3807
- net.minecraft.util.datafix.schemas.V3808
+ net.minecraft.util.datafix.schemas.V3808_1
- net.minecraft.util.datafix.schemas.V3816
+ net.minecraft.util.datafix.schemas.V3818
- net.minecraft.util.datafix.schemas.V3818_3
+ net.minecraft.util.datafix.schemas.V3818_4
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.debugchart.AbstractSampleLogger
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
+ net.minecraft.util.debugchart.LocalSampleLogger
- net.minecraft.util.debugchart.RemoteDebugSampleType
+ net.minecraft.util.debugchart.RemoteSampleLogger
- net.minecraft.util.debugchart.SampleLogger
+ net.minecraft.util.debugchart.SampleStorage
- net.minecraft.util.debugchart.TpsDebugDimensions
+ net.minecraft.util.eventlog.EventLogDirectory
- net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
+ net.minecraft.util.eventlog.EventLogDirectory$File
- net.minecraft.util.eventlog.EventLogDirectory$FileId
+ net.minecraft.util.eventlog.EventLogDirectory$FileList
- net.minecraft.util.eventlog.EventLogDirectory$RawFile
+ net.minecraft.util.eventlog.JsonEventLog
- net.minecraft.util.eventlog.JsonEventLog$1
+ net.minecraft.util.eventlog.JsonEventLogReader
- net.minecraft.util.eventlog.JsonEventLogReader$1
+ net.minecraft.util.eventlog.package-info
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.ChunkIdentification
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.IoSummary
- net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.PacketIdentification
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
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
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
+ net.minecraft.world.damagesource.CombatEntry
- net.minecraft.world.damagesource.CombatRules
+ net.minecraft.world.damagesource.CombatTracker
- net.minecraft.world.damagesource.DamageEffects
+ net.minecraft.world.damagesource.DamageScaling
- net.minecraft.world.damagesource.DamageSource
+ net.minecraft.world.damagesource.DamageSource$1
- net.minecraft.world.damagesource.DamageSources
+ net.minecraft.world.damagesource.DamageType
- net.minecraft.world.damagesource.DamageTypes
+ net.minecraft.world.damagesource.DeathMessageType
- net.minecraft.world.damagesource.FallLocation
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsorptionMobEffect
+ net.minecraft.world.effect.BadOmenMobEffect
- net.minecraft.world.effect.HealOrHarmMobEffect
+ net.minecraft.world.effect.HungerMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$AttributeTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$BlendState
- net.minecraft.world.effect.MobEffectInstance$Details
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
+ net.minecraft.world.effect.PoisonMobEffect
- net.minecraft.world.effect.RegenerationMobEffect
+ net.minecraft.world.effect.SaturationMobEffect
- net.minecraft.world.effect.WitherMobEffect
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorControl
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
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
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
+ net.minecraft.world.entity.ai.behavior.LongJumpUtil
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
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
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
+ net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.MobSensor
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
+ net.minecraft.world.entity.animal.Animal
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
+ net.minecraft.world.entity.animal.FrogVariant
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.MushroomCow
- net.minecraft.world.entity.animal.MushroomCow$MushroomType
+ net.minecraft.world.entity.animal.Ocelot
- net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
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
+ net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
- net.minecraft.world.entity.animal.Parrot$Variant
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
- net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
- net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
+ net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
- net.minecraft.world.entity.animal.Rabbit$Variant
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Base
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
- net.minecraft.world.entity.animal.TropicalFish$Variant
+ net.minecraft.world.entity.animal.Turtle
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
- net.minecraft.world.entity.animal.Wolf$WolfPackData
- net.minecraft.world.entity.animal.WolfVariant
- net.minecraft.world.entity.AnimationState
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Attackable
+ net.minecraft.world.entity.Crackiness
- net.minecraft.world.entity.Crackiness$Level
+ net.minecraft.world.entity.Display
- net.minecraft.world.entity.Display$1
+ net.minecraft.world.entity.Display$BillboardConstraints
- net.minecraft.world.entity.Display$BlockDisplay
+ net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
- net.minecraft.world.entity.Display$ColorInterpolator
+ net.minecraft.world.entity.Display$FloatInterpolator
- net.minecraft.world.entity.Display$GenericInterpolator
+ net.minecraft.world.entity.Display$IntInterpolator
- net.minecraft.world.entity.Display$ItemDisplay
+ net.minecraft.world.entity.Display$ItemDisplay$1
- net.minecraft.world.entity.Display$ItemDisplay$ItemRenderState
+ net.minecraft.world.entity.Display$LinearFloatInterpolator
- net.minecraft.world.entity.Display$LinearIntInterpolator
+ net.minecraft.world.entity.Display$PosRotInterpolationTarget
- net.minecraft.world.entity.Display$RenderState
+ net.minecraft.world.entity.Display$TextDisplay
- net.minecraft.world.entity.Display$TextDisplay$Align
+ net.minecraft.world.entity.Display$TextDisplay$CachedInfo
- net.minecraft.world.entity.Display$TextDisplay$CachedLine
+ net.minecraft.world.entity.Display$TextDisplay$LineSplitter
- net.minecraft.world.entity.Display$TextDisplay$TextRenderState
+ net.minecraft.world.entity.Display$TransformationInterpolator
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityAttachment
- net.minecraft.world.entity.EntityAttachment$Fallback
+ net.minecraft.world.entity.EntityAttachments
- net.minecraft.world.entity.EntityAttachments$Builder
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
+ net.minecraft.world.entity.EquipmentSlotGroup
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
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
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacementType
+ net.minecraft.world.entity.SpawnPlacementTypes
- net.minecraft.world.entity.SpawnPlacementTypes$1
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.entity.Targeting
- net.minecraft.world.entity.TraceableEntity
+ net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.SlotRange
- net.minecraft.world.inventory.SlotRanges
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
- net.minecraft.world.item.AdventureModePredicate
+ net.minecraft.world.item.AirItem
- net.minecraft.world.item.alchemy.package-info
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.PotionContents
+ net.minecraft.world.item.alchemy.Potions
- net.minecraft.world.item.AnimalArmorItem
+ net.minecraft.world.item.AnimalArmorItem$BodyType
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterial$Layer
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.armortrim.ArmorTrim
- net.minecraft.world.item.armortrim.package-info
- net.minecraft.world.item.armortrim.TrimMaterial
+ net.minecraft.world.item.armortrim.TrimMaterials
- net.minecraft.world.item.armortrim.TrimPattern
+ net.minecraft.world.item.armortrim.TrimPatterns
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BoneMealItem$1
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
+ net.minecraft.world.item.component.BlockItemStateProperties
- net.minecraft.world.item.component.BundleContents
+ net.minecraft.world.item.component.BundleContents$Mutable
- net.minecraft.world.item.component.ChargedProjectiles
+ net.minecraft.world.item.component.CustomData
- net.minecraft.world.item.component.CustomModelData
+ net.minecraft.world.item.component.DebugStickState
- net.minecraft.world.item.component.DyedItemColor
+ net.minecraft.world.item.component.FireworkExplosion
- net.minecraft.world.item.component.FireworkExplosion$Shape
+ net.minecraft.world.item.component.Fireworks
- net.minecraft.world.item.component.ItemAttributeModifiers
+ net.minecraft.world.item.component.ItemAttributeModifiers$1
- net.minecraft.world.item.component.ItemAttributeModifiers$Builder
+ net.minecraft.world.item.component.ItemAttributeModifiers$Entry
- net.minecraft.world.item.component.ItemContainerContents
+ net.minecraft.world.item.component.ItemContainerContents$Slot
- net.minecraft.world.item.component.ItemLore
+ net.minecraft.world.item.component.LodestoneTarget
- net.minecraft.world.item.component.MapDecorations
+ net.minecraft.world.item.component.MapDecorations$Entry
- net.minecraft.world.item.component.MapItemColor
+ net.minecraft.world.item.component.MapPostProcessing
- net.minecraft.world.item.component.package-info
- net.minecraft.world.item.component.ResolvableProfile
+ net.minecraft.world.item.component.SeededContainerLoot
- net.minecraft.world.item.component.SuspiciousStewEffects
+ net.minecraft.world.item.component.SuspiciousStewEffects$Entry
- net.minecraft.world.item.component.TooltipProvider
+ net.minecraft.world.item.component.Unbreakable
- net.minecraft.world.item.component.WritableBookContent
+ net.minecraft.world.item.component.WrittenBookContent
+ net.minecraft.world.item.context.BlockPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext$1
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.AbstractCookingRecipe$Factory
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingBookCategory
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.DecoratedPotRecipe
- net.minecraft.world.item.crafting.FireworkRocketRecipe
+ net.minecraft.world.item.crafting.FireworkStarFadeRecipe
- net.minecraft.world.item.crafting.FireworkStarRecipe
+ net.minecraft.world.item.crafting.Ingredient
- net.minecraft.world.item.crafting.Ingredient$ItemValue
+ net.minecraft.world.item.crafting.Ingredient$TagValue
- net.minecraft.world.item.crafting.Ingredient$Value
+ net.minecraft.world.item.crafting.MapCloningRecipe
- net.minecraft.world.item.crafting.MapExtendingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeCache
+ net.minecraft.world.item.crafting.RecipeCache$Entry
- net.minecraft.world.item.crafting.RecipeHolder
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeManager$1
+ net.minecraft.world.item.crafting.RecipeManager$CachedCheck
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapedRecipePattern
+ net.minecraft.world.item.crafting.ShapedRecipePattern$Data
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Factory
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmithingRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
- net.minecraft.world.item.crafting.SmithingTrimRecipe
+ net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
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
+ net.minecraft.world.item.DyeColor
- net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
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
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.ItemEnchantments
- net.minecraft.world.item.enchantment.ItemEnchantments$Mutable
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
- net.minecraft.world.item.FireworkStarItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.GlowInkSacItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HangingSignItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HoneycombItem
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
+ net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$1
+ net.minecraft.world.item.ItemStack$2
- net.minecraft.world.item.ItemStackLinkedSet
+ net.minecraft.world.item.ItemStackLinkedSet$1
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MapItem$1
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
+ net.minecraft.world.item.SmithingTemplateItem
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
+ net.minecraft.world.item.trading.ItemCost
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.WindChargeItem
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.ItemInteractionResult
- net.minecraft.world.ItemInteractionResult$1
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
- net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSources
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.Climate
+ net.minecraft.world.level.biome.Climate$DistanceMetric
- net.minecraft.world.level.biome.Climate$Parameter
+ net.minecraft.world.level.biome.Climate$ParameterList
- net.minecraft.world.level.biome.Climate$ParameterPoint
+ net.minecraft.world.level.biome.Climate$RTree
- net.minecraft.world.level.biome.Climate$RTree$Leaf
+ net.minecraft.world.level.biome.Climate$RTree$Node
- net.minecraft.world.level.biome.Climate$RTree$SubTree
+ net.minecraft.world.level.biome.Climate$Sampler
- net.minecraft.world.level.biome.Climate$SpawnFinder
+ net.minecraft.world.level.biome.Climate$SpawnFinder$Result
- net.minecraft.world.level.biome.Climate$TargetPoint
+ net.minecraft.world.level.biome.FeatureSorter
- net.minecraft.world.level.biome.FeatureSorter$1FeatureData
+ net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
- net.minecraft.world.level.biome.OverworldBiomeBuilder
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AmethystBlock
+ net.minecraft.world.level.block.AmethystClusterBlock
- net.minecraft.world.level.block.AmethystClusterBlock$1
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.AzaleaBlock
- net.minecraft.world.level.block.BambooSaplingBlock
+ net.minecraft.world.level.block.BambooStalkBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BaseTorchBlock
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BlockTypes
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BonemealableBlock$1
+ net.minecraft.world.level.block.BonemealableBlock$Type
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BrushableBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CalibratedSculkSensorBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CandleBlock
+ net.minecraft.world.level.block.CandleCakeBlock
- net.minecraft.world.level.block.CarpetBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.CaveVines
- net.minecraft.world.level.block.CaveVinesBlock
+ net.minecraft.world.level.block.CaveVinesPlantBlock
- net.minecraft.world.level.block.CeilingHangingSignBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
- net.minecraft.world.level.block.CherryLeavesBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChiseledBookShelfBlock
- net.minecraft.world.level.block.ChiseledBookShelfBlock$1
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.ColoredFallingBlock
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CopperBulbBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CrafterBlock
- net.minecraft.world.level.block.CrafterBlock$1
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DecoratedPotBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.DirtPathBlock
- net.minecraft.world.level.block.DispenserBlock
+ net.minecraft.world.level.block.DoorBlock
- net.minecraft.world.level.block.DoorBlock$1
+ net.minecraft.world.level.block.DoubleBlockCombiner
- net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
+ net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ net.minecraft.world.level.block.DoublePlantBlock
- net.minecraft.world.level.block.DragonEggBlock
+ net.minecraft.world.level.block.DropExperienceBlock
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
+ net.minecraft.world.level.block.entity.BannerPatternLayers
- net.minecraft.world.level.block.entity.BannerPatternLayers$Builder
+ net.minecraft.world.level.block.entity.BannerPatternLayers$Layer
- net.minecraft.world.level.block.entity.BannerPatterns
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$Occupant
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
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity$WobbleStyle
+ net.minecraft.world.level.block.entity.DecoratedPotPatterns
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.HangingSignBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.PotDecorations
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
+ net.minecraft.world.level.block.entity.trialspawner.package-info
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$1
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$2
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawner$StateAccessor
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerData
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$1
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$LightLevel
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$SpinningMob
- net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
- net.minecraft.world.level.block.entity.vault.package-info
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
+ net.minecraft.world.level.block.entity.vault.VaultClientData
- net.minecraft.world.level.block.entity.vault.VaultConfig
+ net.minecraft.world.level.block.entity.vault.VaultServerData
- net.minecraft.world.level.block.entity.vault.VaultSharedData
+ net.minecraft.world.level.block.entity.vault.VaultState
- net.minecraft.world.level.block.entity.vault.VaultState$1
+ net.minecraft.world.level.block.entity.vault.VaultState$2
- net.minecraft.world.level.block.entity.vault.VaultState$3
+ net.minecraft.world.level.block.entity.vault.VaultState$4
- net.minecraft.world.level.block.entity.vault.VaultState$5
+ net.minecraft.world.level.block.entity.vault.VaultState$LightLevel
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.EquipableCarvedPumpkinBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrogspawnBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GameMasterBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.TreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HangingRootsBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.InfestedRotatedPillarBlock
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
+ net.minecraft.world.level.block.LightBlock
- net.minecraft.world.level.block.LightningRodBlock
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MangroveLeavesBlock
- net.minecraft.world.level.block.MangrovePropaguleBlock
+ net.minecraft.world.level.block.MangroveRootsBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MudBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MultifaceSpreader
- net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
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
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PiglinWallSkullBlock
- net.minecraft.world.level.block.PinkPetalsBlock
+ net.minecraft.world.level.block.PipeBlock
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
- net.minecraft.world.level.block.PitcherCropBlock
+ net.minecraft.world.level.block.PitcherCropBlock$PosAndState
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootedDirtBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
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
- net.minecraft.world.level.block.SnifferEggBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
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
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SuspiciousEffectHolder
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TorchflowerCropBlock
- net.minecraft.world.level.block.TransparentBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TrialSpawnerBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VaultBlock
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
- net.minecraft.world.level.block.WaterloggedTransparentBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperBulbBlock
- net.minecraft.world.level.block.WeatheringCopperDoorBlock
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperGrateBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WeatheringCopperTrapDoorBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
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
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LevelChunkSection$1BlockCounter
- net.minecraft.world.level.chunk.LightChunk
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.MissingPaletteEntryException
- net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.Palette$Factory
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$Configuration
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PalettedContainer$Data
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
- net.minecraft.world.level.chunk.PalettedContainerRO
+ net.minecraft.world.level.chunk.PalettedContainerRO$PackedData
- net.minecraft.world.level.chunk.PalettedContainerRO$Unpacker
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.SingleValuePalette
+ net.minecraft.world.level.chunk.status.ChunkStatus
- net.minecraft.world.level.chunk.status.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.status.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.status.ChunkStatusTasks
+ net.minecraft.world.level.chunk.status.ChunkType
- net.minecraft.world.level.chunk.status.package-info
- net.minecraft.world.level.chunk.status.ToFullChunk
+ net.minecraft.world.level.chunk.status.WorldGenContext
+ net.minecraft.world.level.chunk.storage.ChunkScanAccess
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkSerializer$ChunkReadException
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
- net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.RegionStorageInfo
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.storage.SimpleRegionStorage
+ net.minecraft.world.level.chunk.StructureAccess
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
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
- net.minecraft.world.level.EmptyBlockGetter
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
+ net.minecraft.world.level.entity.EntityTypeTest$2
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.gameevent.BlockPositionSource
+ net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.DynamicGameEventListener
+ net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
+ net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
- net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEvent$Context
+ net.minecraft.world.level.gameevent.GameEvent$ListenerInfo
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListener$DeliveryMode
+ net.minecraft.world.level.gameevent.GameEventListener$Provider
- net.minecraft.world.level.gameevent.GameEventListenerRegistry
+ net.minecraft.world.level.gameevent.GameEventListenerRegistry$1
- net.minecraft.world.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ net.minecraft.world.level.gameevent.package-info
+ net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationInfo
+ net.minecraft.world.level.gameevent.vibrations.VibrationSelector
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Data
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Listener
+ net.minecraft.world.level.gameevent.vibrations.VibrationSystem$Ticker
- net.minecraft.world.level.gameevent.vibrations.VibrationSystem$User
- net.minecraft.world.level.GameRules
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
- net.minecraft.world.level.Level$2
+ net.minecraft.world.level.Level$ExplosionInteraction
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.Aquifer
+ net.minecraft.world.level.levelgen.Aquifer$1
- net.minecraft.world.level.levelgen.Aquifer$FluidPicker
+ net.minecraft.world.level.levelgen.Aquifer$FluidStatus
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.Beardifier$1
+ net.minecraft.world.level.levelgen.Beardifier$Rigid
- net.minecraft.world.level.levelgen.BelowZeroRetrogen
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
- net.minecraft.world.level.levelgen.BitRandomSource
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
+ net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
- net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
+ net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
- net.minecraft.world.level.levelgen.blending.BlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
- net.minecraft.world.level.levelgen.blending.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
+ net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
- net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.package-info
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
- net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.DensityFunction
- net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
+ net.minecraft.world.level.levelgen.DensityFunction$FunctionContext
- net.minecraft.world.level.levelgen.DensityFunction$NoiseHolder
+ net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
- net.minecraft.world.level.levelgen.DensityFunction$SinglePointContext
+ net.minecraft.world.level.levelgen.DensityFunction$Visitor
- net.minecraft.world.level.levelgen.DensityFunctions
+ net.minecraft.world.level.levelgen.DensityFunctions$1
- net.minecraft.world.level.levelgen.DensityFunctions$Ap2
+ net.minecraft.world.level.levelgen.DensityFunctions$BeardifierMarker
- net.minecraft.world.level.levelgen.DensityFunctions$BeardifierOrMarker
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendAlpha
- net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
+ net.minecraft.world.level.levelgen.DensityFunctions$BlendOffset
- net.minecraft.world.level.levelgen.DensityFunctions$Clamp
+ net.minecraft.world.level.levelgen.DensityFunctions$Constant
- net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ net.minecraft.world.level.levelgen.DensityFunctions$HolderHolder
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped
+ net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Marker
+ net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
- net.minecraft.world.level.levelgen.DensityFunctions$MarkerOrMarked
+ net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$Noise
- net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
+ net.minecraft.world.level.levelgen.DensityFunctions$RangeChoice
- net.minecraft.world.level.levelgen.DensityFunctions$Shift
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftA
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$ShiftNoise
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline
- net.minecraft.world.level.levelgen.DensityFunctions$Spline$Coordinate
+ net.minecraft.world.level.levelgen.DensityFunctions$Spline$Point
- net.minecraft.world.level.levelgen.DensityFunctions$TransformerWithContext
+ net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- net.minecraft.world.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ net.minecraft.world.level.levelgen.DensityFunctions$YClampedGradient
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
+ net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
- net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskFeature
+ net.minecraft.world.level.levelgen.feature.DripstoneClusterFeature
- net.minecraft.world.level.levelgen.feature.DripstoneUtils
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$1
+ net.minecraft.world.level.levelgen.feature.FeatureCountTracker$FeatureData
- net.minecraft.world.level.levelgen.feature.FeatureCountTracker$LevelData
+ net.minecraft.world.level.levelgen.feature.FeaturePlaceContext
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.CherryFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.FossilFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.GeodeFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature$Configuration
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.rootplacers.AboveRootPlacement
- net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacement
+ net.minecraft.world.level.levelgen.feature.rootplacers.MangroveRootPlacer
- net.minecraft.world.level.levelgen.feature.rootplacers.package-info
- net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacer
+ net.minecraft.world.level.levelgen.feature.rootplacers.RootPlacerType
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.AttachedToLeavesDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator$Context
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TreeFeature$1
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.CherryTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
- net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
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
+ net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
+ net.minecraft.world.level.levelgen.heightproviders.HeightProvider
- net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
+ net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
- net.minecraft.world.level.levelgen.heightproviders.UniformHeight
+ net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$1
- net.minecraft.world.level.levelgen.NoiseChunk$2
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
+ net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseRouter
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
+ net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BiomeFilter
+ net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
- net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
+ net.minecraft.world.level.levelgen.placement.CaveSurface
- net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
+ net.minecraft.world.level.levelgen.placement.CountPlacement
- net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
- net.minecraft.world.level.levelgen.placement.HeightmapPlacement
+ net.minecraft.world.level.levelgen.placement.HeightRangePlacement
+ net.minecraft.world.level.levelgen.placement.InSquarePlacement
- net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
+ net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.PlacedFeature
+ net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementFilter
+ net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.PlacementModifierType
+ net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
- net.minecraft.world.level.levelgen.placement.RarityFilter
+ net.minecraft.world.level.levelgen.placement.RepeatingPlacement
- net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
+ net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
- net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.presets.package-info
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
+ net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuiltinStructures
+ net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
+ net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
- net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
- net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.package-info
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.alias.Direct
+ net.minecraft.world.level.levelgen.structure.pools.alias.package-info
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBinding
+ net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasBindings
- net.minecraft.world.level.levelgen.structure.pools.alias.PoolAliasLookup
+ net.minecraft.world.level.levelgen.structure.pools.alias.Random
- net.minecraft.world.level.levelgen.structure.pools.alias.RandomGroup
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
+ net.minecraft.world.level.levelgen.structure.Structure
- net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.Structure$StructureSettings
+ net.minecraft.world.level.levelgen.structure.StructureCheck
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructurePieceAccessor
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.structures.IglooStructure
+ net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure$1
+ net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece
- net.minecraft.world.level.levelgen.structure.structures.JungleTemplePiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$1
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.structures.MineshaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
- net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure$Type
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.structures.NetherFortressPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.structures.NetherFortressStructure
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces
- net.minecraft.world.level.levelgen.structure.structures.NetherFossilPieces$NetherFossilPiece
+ net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.structures.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.structures.OceanMonumentStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure
+ net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
- net.minecraft.world.level.levelgen.structure.structures.package-info
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$Properties
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalPiece$VerticalPlacement
+ net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
- net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure$Setup
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.structures.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
- net.minecraft.world.level.levelgen.structure.structures.StrongholdStructure
+ net.minecraft.world.level.levelgen.structure.structures.SwampHutPiece
- net.minecraft.world.level.levelgen.structure.structures.SwampHutStructure
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
- net.minecraft.world.level.levelgen.structure.StructureSet
+ net.minecraft.world.level.levelgen.structure.StructureSet$StructureSelectionEntry
- net.minecraft.world.level.levelgen.structure.StructureSpawnOverride
+ net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureType
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.CappedProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LavaSubmergedBlockProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProtectedBlockProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendLoot
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.AppendStatic
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Clear
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.Passthrough
- net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifier
+ net.minecraft.world.level.levelgen.structure.templatesystem.rule.blockentity.RuleBlockEntityModifierType
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplateManager$Source
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.TerrainAdjustment
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
+ net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldDimensions
+ net.minecraft.world.level.levelgen.WorldDimensions$1Entry
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.WorldOptions
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.ChunkSkyLightSources
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionState
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$SectionType
+ net.minecraft.world.level.lighting.LeveledPriorityQueue
- net.minecraft.world.level.lighting.LeveledPriorityQueue$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEngine
- net.minecraft.world.level.lighting.LightEngine$QueueEntry
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightEngine$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
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
+ net.minecraft.world.level.material.MapColor
- net.minecraft.world.level.material.MapColor$Brightness
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.Path$DebugData
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.PathfindingContext
- net.minecraft.world.level.pathfinder.PathType
+ net.minecraft.world.level.pathfinder.PathTypeCache
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
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
+ net.minecraft.world.level.saveddata.maps.MapId
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.saveddata.SavedData$Factory
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.Spawner
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DataVersion
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.FileNameDateFormatter
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
+ net.minecraft.world.level.storage.loot.entries.NestedLootTable
- net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Path
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FunctionReference
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SequenceFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetComponentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetCustomDataFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
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
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
+ net.minecraft.world.level.WorldDataConfiguration
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
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
+ net.minecraft.world.RandomizableContainer
- net.minecraft.world.RandomSequence
+ net.minecraft.world.RandomSequences
- net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerScoreEntry
- net.minecraft.world.scores.PlayerScores
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.ReadOnlyScoreInfo
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.ScoreAccess
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.Scoreboard$1
+ net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.ScoreHolder
- net.minecraft.world.scores.ScoreHolder$1
+ net.minecraft.world.scores.ScoreHolder$2
- net.minecraft.world.scores.ScoreHolder$3
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.TickRateManager
+ net.minecraft.world.ticks.BlackholeTickAccess
- net.minecraft.world.ticks.BlackholeTickAccess$1
+ net.minecraft.world.ticks.BlackholeTickAccess$2
- net.minecraft.world.ticks.ContainerSingleItem
+ net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
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
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.EntityEquipmentPredicate +1M | -1P
```
```
XXX.advancements.critereon.EntityPredicate +2M -1M | +1P
```
```
XXX.commands.arguments.StringRepresentableArgument +1M -1M
```
```
XXX.minecraft.core.HolderSet$Direct +2M
```
```
XXX.minecraft.nbt.NbtUtils -2M
```
```
XXX.minecraft.resources.HolderSetCodec +10M -5M
```
```
XXX.minecraft.util.ExtraCodecs +10M -9M
```
```
XXX.minecraft.util.ExtraCodecs$7 +10M -9M
```
```
XXX.world.inventory.InventoryMenu +2P
```
```
XXX.world.inventory.LoomMenu +1P
```

</details>




















































<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate
</summary>

```diff
- EntityEquipmentPredicate captainPredicate(HolderGetter)
```

</details>


<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- Optional slots()
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>






































<details>
<summary>
net.minecraft.commands.arguments.StringRepresentableArgument
</summary>

```diff
+ CommandSyntaxException lambda$parse$1(String)
- CommandSyntaxException lambda$parse$1(StringReader,String)
```

</details>
















































































<details>
<summary>
net.minecraft.core.HolderSet$Direct
</summary>

```diff
- boolean equals(Object)
- int hashCode()
```

</details>














































































































































































































































<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
+ CompoundTag writeGameProfile(CompoundTag,GameProfile)
+ GameProfile readGameProfile(CompoundTag)
```

</details>




































































































































































































































































































<details>
<summary>
net.minecraft.resources.HolderSetCodec
</summary>

```diff
- DataResult lambda$decode$3(HolderGetter,TagKey)
- DataResult lambda$decode$4(List)
- DataResult lambda$decode$6(HolderGetter,Pair)
- DataResult lambda$decodeWithoutRegistry$11(Pair)
+ DataResult lambda$decodeWithoutRegistry$7(Pair)
- DataResult lambda$lookupTag$8(TagKey)
- DataResult lookupTag(HolderGetter,TagKey)
+ HolderSet lambda$decode$3(HolderGetter,Either)
+ Pair lambda$decode$4(HolderGetter,Pair)
- Pair lambda$decode$5(Pair,HolderSet)
- String lambda$decodeWithoutRegistry$10(Holder)
+ String lambda$decodeWithoutRegistry$6(Holder)
+ String lambda$encode$5(HolderSet)
- String lambda$encode$9(HolderSet)
- String lambda$lookupTag$7(TagKey)
```

</details>


















































































































































































































































































<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ DataResult lambda$sizeLimitedList$89(int,List)
- DataResult lambda$sizeLimitedList$90(int,List)
+ DataResult lambda$sizeLimitedMap$91(int,Map)
- DataResult lambda$sizeLimitedMap$92(int,Map)
+ DataResult lambda$static$93(String)
- DataResult lambda$static$94(String)
- List lambda$sizeLimitedList$89(List,int)
+ Object lambda$withAlternative$94(Object)
+ Object lambda$withAlternative$96(Either)
- Object lambda$withAlternative$96(Object)
- Object lambda$withAlternative$97(Either)
+ Object lambda$withAlternative$97(Object)
+ Object lambda$withAlternative$98(Function,Either)
- Object lambda$withAlternative$98(Object)
- Object lambda$withAlternative$99(Function,Either)
+ String lambda$sizeLimitedMap$90(Map,int)
- String lambda$sizeLimitedMap$91(Map,int)
+ String lambda$static$92(String)
- String lambda$static$93(String)
```

</details>



<details>
<summary>
net.minecraft.util.ExtraCodecs$7
</summary>

```diff
- DataResult lambda$decode$10(Codec,DynamicOps,Function,Object,MapLike)
+ DataResult lambda$decode$4(Codec,DynamicOps,Function,ImmutableMap$Builder,Stream$Builder,DataResult,Pair)
- DataResult lambda$decode$5(Codec,DynamicOps,Function,Map,Stream$Builder,DataResult,Pair)
+ DataResult lambda$decode$6(DataResult,DataResult)
- DataResult lambda$decode$7(DataResult,DataResult)
+ DataResult lambda$decode$9(Codec,DynamicOps,Function,Object,MapLike)
+ Pair lambda$decode$7(Map,Object,Unit)
- Pair lambda$decode$8(Map,Object,Unit)
- String lambda$decode$3(Optional)
+ String lambda$decode$8(Object,String)
- String lambda$decode$9(Object,String)
- Unit lambda$decode$2(Unit,Object)
+ Unit lambda$decode$3(Unit,Pair)
- Unit lambda$decode$4(Unit,Pair)
+ Unit lambda$decode$5(Unit,Unit)
- Unit lambda$decode$6(Unit,Unit)
+ void lambda$decode$1(ImmutableMap$Builder,Pair)
- void lambda$decode$1(String)
+ void lambda$decode$2(Stream$Builder,Pair,DataResult$PartialResult)
```

</details>














































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.StartRidingTrigger
+ net.minecraft.advancements.critereon.StartRidingTrigger$TriggerInstance
- net.minecraft.advancements.critereon.StatePropertiesPredicate
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ValueMatcher
- net.minecraft.advancements.critereon.SummonedEntityTrigger
+ net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TagPredicate
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TargetBlockTrigger
- net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsingItemTrigger
- net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.package-info
+ net.minecraft.client.animation.AnimationChannel
- net.minecraft.client.animation.AnimationChannel$Interpolation
+ net.minecraft.client.animation.AnimationChannel$Interpolations
- net.minecraft.client.animation.AnimationChannel$Target
+ net.minecraft.client.animation.AnimationChannel$Targets
- net.minecraft.client.animation.AnimationDefinition
+ net.minecraft.client.animation.AnimationDefinition$Builder
- net.minecraft.client.animation.definitions.ArmadilloAnimation
+ net.minecraft.client.animation.definitions.BatAnimation
- net.minecraft.client.animation.definitions.BreezeAnimation
+ net.minecraft.client.animation.definitions.CamelAnimation
- net.minecraft.client.animation.definitions.FrogAnimation
+ net.minecraft.client.animation.definitions.package-info
+ net.minecraft.client.animation.definitions.SnifferAnimation
- net.minecraft.client.animation.definitions.WardenAnimation
- net.minecraft.client.animation.Keyframe
+ net.minecraft.client.animation.KeyframeAnimations
- net.minecraft.client.animation.package-info
- net.minecraft.client.AttackIndicatorStatus
+ net.minecraft.client.Camera
- net.minecraft.client.Camera$NearPlane
+ net.minecraft.client.CameraType
- net.minecraft.client.ClientBrandRetriever
+ net.minecraft.client.ClientRecipeBook
- net.minecraft.client.ClientRecipeBook$1
+ net.minecraft.client.CloudStatus
+ net.minecraft.client.color.block.BlockColor
- net.minecraft.client.color.block.BlockColors
+ net.minecraft.client.color.block.BlockTintCache
- net.minecraft.client.color.block.BlockTintCache$CacheData
+ net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
- net.minecraft.client.color.block.package-info
+ net.minecraft.client.color.item.ItemColor
- net.minecraft.client.color.item.ItemColors
+ net.minecraft.client.color.item.package-info
- net.minecraft.client.CommandHistory
+ net.minecraft.client.ComponentCollector
- net.minecraft.client.DebugQueryHandler
+ net.minecraft.client.GameNarrator
- net.minecraft.client.GameNarrator$NarratorInitException
+ net.minecraft.client.GraphicsStatus
- net.minecraft.client.GraphicsStatus$1
- net.minecraft.client.gui.ComponentPath
+ net.minecraft.client.gui.ComponentPath$Leaf
- net.minecraft.client.gui.ComponentPath$Path
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractContainerWidget
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractScrollWidget
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$1
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractStringWidget
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$Builder
+ net.minecraft.client.gui.components.Button$CreateNarration
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.Checkbox$Builder
+ net.minecraft.client.gui.components.Checkbox$OnValueChange
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.CommonButtons
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$1
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
- net.minecraft.client.gui.components.debugchart.AbstractDebugChart
+ net.minecraft.client.gui.components.debugchart.BandwidthDebugChart
- net.minecraft.client.gui.components.debugchart.FpsDebugChart
+ net.minecraft.client.gui.components.debugchart.PingDebugChart
- net.minecraft.client.gui.components.debugchart.TpsDebugChart
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
- net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.FittingMultiLineTextWidget
- net.minecraft.client.gui.components.FocusableTextWidget
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.ImageWidget
+ net.minecraft.client.gui.components.ImageWidget$Sprite
- net.minecraft.client.gui.components.ImageWidget$Texture
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LoadingDotsWidget
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.LogoRenderer
- net.minecraft.client.gui.components.MultiLineEditBox
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.MultilineTextField
- net.minecraft.client.gui.components.MultilineTextField$1
+ net.minecraft.client.gui.components.MultilineTextField$StringView
+ net.minecraft.client.gui.components.MultiLineTextWidget
- net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlainTextButton
+ net.minecraft.client.gui.components.PlayerFaceRenderer
- net.minecraft.client.gui.components.PlayerSkinWidget
+ net.minecraft.client.gui.components.PlayerSkinWidget$Model
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
- net.minecraft.client.gui.components.PlayerTabOverlay$ScoreDisplayEntry
+ net.minecraft.client.gui.components.PopupScreen
- net.minecraft.client.gui.components.PopupScreen$Builder
+ net.minecraft.client.gui.components.PopupScreen$ButtonOption
- net.minecraft.client.gui.components.Renderable
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
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
- net.minecraft.client.gui.components.tabs.GridLayoutTab
+ net.minecraft.client.gui.components.tabs.package-info
+ net.minecraft.client.gui.components.tabs.Tab
- net.minecraft.client.gui.components.tabs.TabManager
+ net.minecraft.client.gui.components.tabs.TabNavigationBar
- net.minecraft.client.gui.components.tabs.TabNavigationBar$Builder
- net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastId
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.Tooltip
+ net.minecraft.client.gui.components.Whence
- net.minecraft.client.gui.components.WidgetSprites
+ net.minecraft.client.gui.components.WidgetTooltipHolder
+ net.minecraft.client.gui.Font
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.CodepointMap
+ net.minecraft.client.gui.font.CodepointMap$Output
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$BuilderId
- net.minecraft.client.gui.font.FontManager$BuilderResult
+ net.minecraft.client.gui.font.FontManager$FontDefinitionFile
- net.minecraft.client.gui.font.FontManager$Preparation
+ net.minecraft.client.gui.font.FontManager$UnresolvedBuilderBundle
- net.minecraft.client.gui.font.FontOption
+ net.minecraft.client.gui.font.FontOption$Filter
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontSet$GlyphInfoFilter
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.GlyphRenderTypes
+ net.minecraft.client.gui.font.GlyphRenderTypes$1
+ net.minecraft.client.gui.font.glyphs.BakedGlyph
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs$1
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$Definition
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.FreeTypeUtil
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Conditional
- net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Loader
+ net.minecraft.client.gui.font.providers.GlyphProviderDefinition$Reference
- net.minecraft.client.gui.font.providers.GlyphProviderType
+ net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.ProviderReferenceDefinition
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderDefinition$Shift
- net.minecraft.client.gui.font.providers.UnihexProvider
+ net.minecraft.client.gui.font.providers.UnihexProvider$ByteContents
- net.minecraft.client.gui.font.providers.UnihexProvider$Definition
+ net.minecraft.client.gui.font.providers.UnihexProvider$Dimensions
- net.minecraft.client.gui.font.providers.UnihexProvider$Glyph
+ net.minecraft.client.gui.font.providers.UnihexProvider$Glyph$1
- net.minecraft.client.gui.font.providers.UnihexProvider$IntContents
+ net.minecraft.client.gui.font.providers.UnihexProvider$LineData
- net.minecraft.client.gui.font.providers.UnihexProvider$OverrideRange
+ net.minecraft.client.gui.font.providers.UnihexProvider$ReaderOutput
- net.minecraft.client.gui.font.providers.UnihexProvider$ShortContents
- net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.font.TextFieldHelper$1
- net.minecraft.client.gui.font.TextFieldHelper$CursorStep
- net.minecraft.client.gui.Font$DisplayMode
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.Gui$1DisplayEntry
- net.minecraft.client.gui.Gui$HeartType
+ net.minecraft.client.gui.GuiGraphics
- net.minecraft.client.gui.GuiGraphics$ScissorStack
+ net.minecraft.client.gui.GuiSpriteManager
- net.minecraft.client.gui.LayeredDraw
+ net.minecraft.client.gui.LayeredDraw$Layer
- net.minecraft.client.gui.layouts.AbstractLayout
+ net.minecraft.client.gui.layouts.AbstractLayout$AbstractChildWrapper
- net.minecraft.client.gui.layouts.CommonLayouts
+ net.minecraft.client.gui.layouts.EqualSpacingLayout
- net.minecraft.client.gui.layouts.EqualSpacingLayout$1
+ net.minecraft.client.gui.layouts.EqualSpacingLayout$ChildContainer
- net.minecraft.client.gui.layouts.EqualSpacingLayout$Orientation
+ net.minecraft.client.gui.layouts.FrameLayout
- net.minecraft.client.gui.layouts.FrameLayout$ChildContainer
+ net.minecraft.client.gui.layouts.GridLayout
- net.minecraft.client.gui.layouts.GridLayout$CellInhabitant
+ net.minecraft.client.gui.layouts.GridLayout$RowHelper
- net.minecraft.client.gui.layouts.HeaderAndFooterLayout
+ net.minecraft.client.gui.layouts.Layout
- net.minecraft.client.gui.layouts.LayoutElement
+ net.minecraft.client.gui.layouts.LayoutSettings
- net.minecraft.client.gui.layouts.LayoutSettings$LayoutSettingsImpl
+ net.minecraft.client.gui.layouts.LinearLayout
- net.minecraft.client.gui.layouts.LinearLayout$1
+ net.minecraft.client.gui.layouts.LinearLayout$Orientation
+ net.minecraft.client.gui.layouts.package-info
- net.minecraft.client.gui.layouts.SpacerElement
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$MapInstance
- net.minecraft.client.gui.narration.NarratableEntry
+ net.minecraft.client.gui.narration.NarratableEntry$NarrationPriority
- net.minecraft.client.gui.narration.NarratedElementType
+ net.minecraft.client.gui.narration.NarrationElementOutput
- net.minecraft.client.gui.narration.NarrationSupplier
+ net.minecraft.client.gui.narration.NarrationThunk
+ net.minecraft.client.gui.narration.package-info
- net.minecraft.client.gui.narration.ScreenNarrationCollector
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$1
- net.minecraft.client.gui.narration.ScreenNarrationCollector$EntryKey
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$NarrationEntry
- net.minecraft.client.gui.narration.ScreenNarrationCollector$Output
- net.minecraft.client.gui.navigation.CommonInputs
+ net.minecraft.client.gui.navigation.FocusNavigationEvent
- net.minecraft.client.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$InitialFocus
- net.minecraft.client.gui.navigation.FocusNavigationEvent$TabNavigation
+ net.minecraft.client.gui.navigation.package-info
+ net.minecraft.client.gui.navigation.ScreenAxis
- net.minecraft.client.gui.navigation.ScreenAxis$1
+ net.minecraft.client.gui.navigation.ScreenDirection
- net.minecraft.client.gui.navigation.ScreenDirection$1
+ net.minecraft.client.gui.navigation.ScreenPosition
- net.minecraft.client.gui.navigation.ScreenPosition$1
+ net.minecraft.client.gui.navigation.ScreenRectangle
- net.minecraft.client.gui.navigation.ScreenRectangle$1
- net.minecraft.client.gui.package-info
+ net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
- net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$Sprites
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType$1
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.AlertScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
- net.minecraft.client.gui.screens.BanNoticeScreens
+ net.minecraft.client.gui.screens.ChatOptionsScreen
- net.minecraft.client.gui.screens.ChatScreen
+ net.minecraft.client.gui.screens.ChatScreen$1
- net.minecraft.client.gui.screens.ConfirmLinkScreen
+ net.minecraft.client.gui.screens.ConfirmScreen
- net.minecraft.client.gui.screens.ConnectScreen
+ net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.ConnectScreen$2
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
+ net.minecraft.client.gui.screens.FontOptionsScreen
- net.minecraft.client.gui.screens.GenericMessageScreen
+ net.minecraft.client.gui.screens.GenericWaitingScreen
- net.minecraft.client.gui.screens.InBedChatScreen
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
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CrafterScreen
+ net.minecraft.client.gui.screens.inventory.CrafterScreen$1
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.CyclingSlotBackground
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmithingScreen
+ net.minecraft.client.gui.screens.inventory.SmokerScreen
- net.minecraft.client.gui.screens.inventory.StonecutterScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTextTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipPositioner
+ net.minecraft.client.gui.screens.inventory.tooltip.DefaultTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.MenuTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingDotsText
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
- net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.Realms32bitWarningScreen
+ net.minecraft.client.gui.screens.multiplayer.SafetyScreen
- net.minecraft.client.gui.screens.multiplayer.ServerReconfigScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$1
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ net.minecraft.client.gui.screens.multiplayer.WarningScreen
+ net.minecraft.client.gui.screens.NoticeWithLinkScreen
- net.minecraft.client.gui.screens.OnlineOptionsScreen
+ net.minecraft.client.gui.screens.OptionsScreen
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
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
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
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
+ net.minecraft.client.gui.screens.RecoverWorldDataScreen
+ net.minecraft.client.gui.screens.reporting.AbstractReportScreen
- net.minecraft.client.gui.screens.reporting.AbstractReportScreen$DiscardReportWarningScreen
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen
- net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller
+ net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller$Output
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- net.minecraft.client.gui.screens.reporting.NameReportScreen
- net.minecraft.client.gui.screens.reporting.package-info
+ net.minecraft.client.gui.screens.reporting.ReportPlayerScreen
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ net.minecraft.client.gui.screens.reporting.SkinReportScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$DeferredTooltipRendering
- net.minecraft.client.gui.screens.Screen$NarratableSearchResult
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SimpleOptionsSubScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.social.package-info
+ net.minecraft.client.gui.screens.social.PlayerEntry
- net.minecraft.client.gui.screens.social.PlayerEntry$1
+ net.minecraft.client.gui.screens.social.PlayerEntry$2
- net.minecraft.client.gui.screens.social.PlayerEntry$3
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
- net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.telemetry.package-info
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget
+ net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$Content
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ net.minecraft.client.gui.screens.telemetry.TelemetryInfoScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.TitleScreen$WarningLabel
+ net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen
- net.minecraft.client.gui.screens.UnsupportedGraphicsWarningScreen$ButtonOption
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.WinScreen$CreditsReader
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$GameTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$MoreTab
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$1
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$2
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
- net.minecraft.client.gui.screens.worldselection.EditWorldScreen
+ net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
- net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
- net.minecraft.client.gui.screens.worldselection.package-info
+ net.minecraft.client.gui.screens.worldselection.PresetEditor
- net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$Builder
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$LabeledSwitch
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$SwitchBuilder
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext
+ net.minecraft.client.gui.screens.worldselection.WorldCreationContext$DimensionsUpdater
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext$OptionsModifier
+ net.minecraft.client.gui.screens.worldselection.WorldCreationUiState
- net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- net.minecraft.client.gui.screens.worldselection.WorldOpenFlows
+ net.minecraft.client.gui.screens.worldselection.WorldOpenFlows$1Data
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$Entry
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$LoadingHeader
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
+ net.minecraft.client.GuiMessage
- net.minecraft.client.GuiMessage$Line
+ net.minecraft.client.GuiMessageTag
- net.minecraft.client.GuiMessageTag$Icon
+ net.minecraft.client.HotbarManager
- net.minecraft.client.InputType
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
+ net.minecraft.client.KeyMapping
- net.minecraft.client.main.GameConfig
+ net.minecraft.client.main.GameConfig$FolderData
- net.minecraft.client.main.GameConfig$GameData
+ net.minecraft.client.main.GameConfig$QuickPlayData
- net.minecraft.client.main.GameConfig$UserData
+ net.minecraft.client.main.Main
- net.minecraft.client.main.Main$1
+ net.minecraft.client.main.Main$2
- net.minecraft.client.main.Main$3
- net.minecraft.client.main.package-info
+ net.minecraft.client.main.SilentInitException
- net.minecraft.client.Minecraft
+ net.minecraft.client.Minecraft$1
- net.minecraft.client.Minecraft$ChatStatus
+ net.minecraft.client.Minecraft$ChatStatus$1
- net.minecraft.client.Minecraft$ChatStatus$2
+ net.minecraft.client.Minecraft$ChatStatus$3
- net.minecraft.client.Minecraft$ChatStatus$4
+ net.minecraft.client.Minecraft$GameLoadCookie
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableHierarchicalModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AllayModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmadilloModel
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
- net.minecraft.client.model.AxolotlModel
+ net.minecraft.client.model.BatModel
- net.minecraft.client.model.BeeModel
+ net.minecraft.client.model.BlazeModel
- net.minecraft.client.model.BoatModel
+ net.minecraft.client.model.BoggedModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.BreezeModel
- net.minecraft.client.model.CamelModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestBoatModel
- net.minecraft.client.model.ChestedHorseModel
+ net.minecraft.client.model.ChestRaftModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
- net.minecraft.client.model.ColorableHierarchicalModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.dragon.DragonHeadModel
+ net.minecraft.client.model.dragon.package-info
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
+ net.minecraft.client.model.FrogModel
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
- net.minecraft.client.model.GhastModel
+ net.minecraft.client.model.GiantZombieModel
- net.minecraft.client.model.GoatModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HierarchicalModel
- net.minecraft.client.model.HoglinModel
+ net.minecraft.client.model.HorseModel
- net.minecraft.client.model.HumanoidArmorModel
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
+ net.minecraft.client.model.package-info
+ net.minecraft.client.model.PandaModel
- net.minecraft.client.model.ParrotModel
+ net.minecraft.client.model.ParrotModel$1
- net.minecraft.client.model.ParrotModel$State
+ net.minecraft.client.model.PhantomModel
+ net.minecraft.client.model.PiglinHeadModel
- net.minecraft.client.model.PiglinModel
- net.minecraft.client.model.PigModel
+ net.minecraft.client.model.PlayerModel
- net.minecraft.client.model.PolarBearModel
+ net.minecraft.client.model.PufferfishBigModel
- net.minecraft.client.model.PufferfishMidModel
+ net.minecraft.client.model.PufferfishSmallModel
- net.minecraft.client.model.QuadrupedModel
+ net.minecraft.client.model.RabbitModel
- net.minecraft.client.model.RaftModel
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
+ net.minecraft.client.model.SnifferModel
- net.minecraft.client.model.SnowGolemModel
+ net.minecraft.client.model.SpiderModel
- net.minecraft.client.model.SquidModel
+ net.minecraft.client.model.StriderModel
- net.minecraft.client.model.TadpoleModel
+ net.minecraft.client.model.TridentModel
- net.minecraft.client.model.TropicalFishModelA
+ net.minecraft.client.model.TropicalFishModelB
- net.minecraft.client.model.TurtleModel
+ net.minecraft.client.model.VexModel
- net.minecraft.client.model.VillagerHeadModel
+ net.minecraft.client.model.VillagerModel
- net.minecraft.client.model.WardenModel
+ net.minecraft.client.model.WaterPatchModel
- net.minecraft.client.model.WindChargeModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.MouseHandler
- net.minecraft.client.multiplayer.AccountProfileKeyPairManager
+ net.minecraft.client.multiplayer.chat.ChatListener
- net.minecraft.client.multiplayer.chat.ChatListener$Message
+ net.minecraft.client.multiplayer.chat.ChatLog
- net.minecraft.client.multiplayer.chat.ChatTrustLevel
+ net.minecraft.client.multiplayer.chat.ChatTrustLevel$1
- net.minecraft.client.multiplayer.chat.LoggedChatEvent
+ net.minecraft.client.multiplayer.chat.LoggedChatEvent$Type
- net.minecraft.client.multiplayer.chat.LoggedChatMessage
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage$Player
- net.minecraft.client.multiplayer.chat.LoggedChatMessage$System
+ net.minecraft.client.multiplayer.chat.package-info
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$1
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender$SendException
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$Services
- net.minecraft.client.multiplayer.chat.report.BanReason
+ net.minecraft.client.multiplayer.chat.report.ChatReport
- net.minecraft.client.multiplayer.chat.report.ChatReport$Builder
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Collector
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Handler
- net.minecraft.client.multiplayer.chat.report.NameReport
+ net.minecraft.client.multiplayer.chat.report.NameReport$Builder
+ net.minecraft.client.multiplayer.chat.report.package-info
- net.minecraft.client.multiplayer.chat.report.Report
+ net.minecraft.client.multiplayer.chat.report.Report$Builder
- net.minecraft.client.multiplayer.chat.report.Report$CannotBuildReason
+ net.minecraft.client.multiplayer.chat.report.Report$Result
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$Realm
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$ThirdParty
- net.minecraft.client.multiplayer.chat.report.ReportingContext
- net.minecraft.client.multiplayer.chat.report.ReportReason
+ net.minecraft.client.multiplayer.chat.report.ReportType
+ net.minecraft.client.multiplayer.chat.report.SkinReport
- net.minecraft.client.multiplayer.chat.report.SkinReport$Builder
+ net.minecraft.client.multiplayer.ChunkBatchSizeCalculator
- net.minecraft.client.multiplayer.ClientAdvancements
+ net.minecraft.client.multiplayer.ClientAdvancements$Listener
- net.minecraft.client.multiplayer.ClientChunkCache
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl
+ net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
- net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
+ net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
- net.minecraft.client.multiplayer.ClientConfigurationPacketListenerImpl
+ net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl$State
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
- net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
+ net.minecraft.client.multiplayer.ClientPacketListener
- net.minecraft.client.multiplayer.ClientPacketListener$1
+ net.minecraft.client.multiplayer.ClientRegistryLayer
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.ClientSuggestionProvider$1
- net.minecraft.client.multiplayer.CommonListenerCookie
+ net.minecraft.client.multiplayer.DebugSampleSubscriber
- net.minecraft.client.multiplayer.KnownPacksManager
+ net.minecraft.client.multiplayer.LegacyServerPinger
- net.minecraft.client.multiplayer.LegacyServerPinger$Output
+ net.minecraft.client.multiplayer.LevelLoadStatusManager
- net.minecraft.client.multiplayer.LevelLoadStatusManager$1
+ net.minecraft.client.multiplayer.LevelLoadStatusManager$Status
- net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PingDebugMonitor
- net.minecraft.client.multiplayer.PlayerInfo
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- net.minecraft.client.multiplayer.prediction.package-info
+ net.minecraft.client.multiplayer.prediction.PredictiveAction
+ net.minecraft.client.multiplayer.ProfileKeyPairManager
- net.minecraft.client.multiplayer.ProfileKeyPairManager$1
+ net.minecraft.client.multiplayer.RegistryDataCollector
- net.minecraft.client.multiplayer.RegistryDataCollector$ContentsCollector
+ net.minecraft.client.multiplayer.resolver.AddressCheck
- net.minecraft.client.multiplayer.resolver.AddressCheck$1
+ net.minecraft.client.multiplayer.resolver.package-info
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
+ net.minecraft.client.multiplayer.resolver.ServerAddress
- net.minecraft.client.multiplayer.resolver.ServerAddressResolver
+ net.minecraft.client.multiplayer.resolver.ServerNameResolver
- net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerData$State
- net.minecraft.client.multiplayer.ServerData$Type
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.TagCollector
- net.minecraft.client.multiplayer.TransferState
+ net.minecraft.client.NarratorStatus
- net.minecraft.client.OptionInstance
+ net.minecraft.client.OptionInstance$AltEnum
- net.minecraft.client.OptionInstance$CaptionBasedToString
+ net.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
- net.minecraft.client.OptionInstance$CycleableValueSet
+ net.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
- net.minecraft.client.OptionInstance$Enum
+ net.minecraft.client.OptionInstance$IntRange
- net.minecraft.client.OptionInstance$IntRangeBase
+ net.minecraft.client.OptionInstance$IntRangeBase$1
- net.minecraft.client.OptionInstance$LazyEnum
+ net.minecraft.client.OptionInstance$OptionInstanceSliderButton
- net.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ net.minecraft.client.OptionInstance$SliderableValueSet
- net.minecraft.client.OptionInstance$TooltipSupplier
+ net.minecraft.client.OptionInstance$UnitDouble
- net.minecraft.client.OptionInstance$UnitDouble$1
+ net.minecraft.client.OptionInstance$ValueSet
- net.minecraft.client.Options
+ net.minecraft.client.Options$1
- net.minecraft.client.Options$2
+ net.minecraft.client.Options$3
- net.minecraft.client.Options$4
+ net.minecraft.client.Options$5
- net.minecraft.client.Options$FieldAccess
+ net.minecraft.client.Options$OptionAccess
- net.minecraft.client.package-info
+ net.minecraft.client.particle.AshParticle
- net.minecraft.client.particle.AshParticle$Provider
+ net.minecraft.client.particle.AttackSweepParticle
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BaseAshSmokeParticle
- net.minecraft.client.particle.BlockMarker
+ net.minecraft.client.particle.BlockMarker$Provider
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
+ net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
- net.minecraft.client.particle.BubbleColumnUpParticle
+ net.minecraft.client.particle.BubbleColumnUpParticle$Provider
- net.minecraft.client.particle.BubbleParticle
+ net.minecraft.client.particle.BubbleParticle$Provider
- net.minecraft.client.particle.BubblePopParticle
+ net.minecraft.client.particle.BubblePopParticle$Provider
- net.minecraft.client.particle.CampfireSmokeParticle
+ net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
- net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
+ net.minecraft.client.particle.CherryParticle
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
+ net.minecraft.client.particle.DripParticle$FallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallingParticle
+ net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
- net.minecraft.client.particle.DustColorTransitionParticle
+ net.minecraft.client.particle.DustColorTransitionParticle$Provider
- net.minecraft.client.particle.DustParticle
+ net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.DustParticleBase
+ net.minecraft.client.particle.DustPlumeParticle
- net.minecraft.client.particle.DustPlumeParticle$Provider
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
+ net.minecraft.client.particle.FlyTowardsPositionParticle
- net.minecraft.client.particle.FlyTowardsPositionParticle$EnchantProvider
+ net.minecraft.client.particle.FlyTowardsPositionParticle$NautilusProvider
- net.minecraft.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
+ net.minecraft.client.particle.GlowParticle
- net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
+ net.minecraft.client.particle.GlowParticle$GlowSquidProvider
- net.minecraft.client.particle.GlowParticle$ScrapeProvider
+ net.minecraft.client.particle.GlowParticle$WaxOffProvider
- net.minecraft.client.particle.GlowParticle$WaxOnProvider
+ net.minecraft.client.particle.GustParticle
- net.minecraft.client.particle.GustParticle$Provider
+ net.minecraft.client.particle.GustSeedParticle
- net.minecraft.client.particle.GustSeedParticle$Provider
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
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.Particle$LifetimeAlpha
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
- net.minecraft.client.particle.ParticleEngine$1ParticleDefinition
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleProvider$Sprite
+ net.minecraft.client.particle.ParticleRenderType
- net.minecraft.client.particle.ParticleRenderType$1
+ net.minecraft.client.particle.ParticleRenderType$2
- net.minecraft.client.particle.ParticleRenderType$3
+ net.minecraft.client.particle.ParticleRenderType$4
- net.minecraft.client.particle.ParticleRenderType$5
+ net.minecraft.client.particle.ParticleRenderType$6
- net.minecraft.client.particle.PlayerCloudParticle
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.PortalParticle$Provider
+ net.minecraft.client.particle.ReversePortalParticle
- net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
+ net.minecraft.client.particle.RisingParticle
- net.minecraft.client.particle.SculkChargeParticle
+ net.minecraft.client.particle.SculkChargeParticle$Provider
- net.minecraft.client.particle.SculkChargePopParticle
+ net.minecraft.client.particle.SculkChargePopParticle$Provider
- net.minecraft.client.particle.ShriekParticle
+ net.minecraft.client.particle.ShriekParticle$Provider
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SingleQuadParticle$FacingCameraMode
+ net.minecraft.client.particle.SmokeParticle
- net.minecraft.client.particle.SmokeParticle$Provider
+ net.minecraft.client.particle.SnowflakeParticle
- net.minecraft.client.particle.SnowflakeParticle$Provider
+ net.minecraft.client.particle.SonicBoomParticle
- net.minecraft.client.particle.SonicBoomParticle$Provider
+ net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$EmissiveProvider
+ net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$AmbientMobProvider
- net.minecraft.client.particle.SpellParticle$InstantProvider
+ net.minecraft.client.particle.SpellParticle$MobProvider
- net.minecraft.client.particle.SpellParticle$Provider
+ net.minecraft.client.particle.SpellParticle$WitchProvider
- net.minecraft.client.particle.SpitParticle
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$Provider
- net.minecraft.client.particle.SpriteSet
+ net.minecraft.client.particle.SquidInkParticle
- net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.SuspendedParticle
+ net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
- net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
- net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ net.minecraft.client.particle.SuspendedTownParticle$EggCrackProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.TrialSpawnerDetectionParticle
+ net.minecraft.client.particle.TrialSpawnerDetectionParticle$Provider
- net.minecraft.client.particle.VibrationSignalParticle
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
- net.minecraft.client.particle.WhiteSmokeParticle
+ net.minecraft.client.particle.WhiteSmokeParticle$Provider
- net.minecraft.client.ParticleStatus
+ net.minecraft.client.PeriodicNotificationManager
- net.minecraft.client.PeriodicNotificationManager$Notification
+ net.minecraft.client.PeriodicNotificationManager$NotificationTask
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
- net.minecraft.client.PrioritizeChunkUpdates
+ net.minecraft.client.profiling.ClientMetricsSamplersProvider
- net.minecraft.client.profiling.package-info
+ net.minecraft.client.quickplay.package-info
+ net.minecraft.client.quickplay.QuickPlay
- net.minecraft.client.quickplay.QuickPlayLog
+ net.minecraft.client.quickplay.QuickPlayLog$1
- net.minecraft.client.quickplay.QuickPlayLog$QuickPlayEntry
+ net.minecraft.client.quickplay.QuickPlayLog$QuickPlayWorld
- net.minecraft.client.quickplay.QuickPlayLog$Type
+ net.minecraft.client.Realms32BitWarningStatus
- net.minecraft.client.RecipeBookCategories
+ net.minecraft.client.RecipeBookCategories$1
- net.minecraft.client.renderer.BiomeColors
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.LiquidBlockRenderer$1
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverride$Predicate
+ net.minecraft.client.renderer.block.model.ItemOverrides
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
+ net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.AndCondition
- net.minecraft.client.renderer.block.model.multipart.Condition
+ net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
- net.minecraft.client.renderer.block.model.multipart.MultiPart
+ net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
+ net.minecraft.client.renderer.block.model.MultiVariant
- net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
- net.minecraft.client.renderer.block.model.package-info
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
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
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ net.minecraft.client.renderer.blockentity.LecternRenderer
- net.minecraft.client.renderer.blockentity.package-info
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.blockentity.SkullBlockRenderer
+ net.minecraft.client.renderer.blockentity.SpawnerRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
- net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
+ net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
- net.minecraft.client.renderer.blockentity.TrialSpawnerRenderer
+ net.minecraft.client.renderer.blockentity.VaultRenderer
+ net.minecraft.client.renderer.BlockEntityWithoutLevelRenderer
+ net.minecraft.client.renderer.chunk.package-info
+ net.minecraft.client.renderer.chunk.RenderChunk
- net.minecraft.client.renderer.chunk.RenderChunkRegion
+ net.minecraft.client.renderer.chunk.RenderRegionCache
- net.minecraft.client.renderer.chunk.RenderRegionCache$ChunkInfo
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$CompiledSection
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask$CompileResults
- net.minecraft.client.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
+ net.minecraft.client.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
- net.minecraft.client.renderer.chunk.VisGraph
+ net.minecraft.client.renderer.chunk.VisGraph$1
- net.minecraft.client.renderer.chunk.VisibilitySet
- net.minecraft.client.renderer.CubeMap
- net.minecraft.client.renderer.culling.Frustum
+ net.minecraft.client.renderer.culling.package-info
- net.minecraft.client.renderer.debug.BeeDebugRenderer
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveDebugInfo
- net.minecraft.client.renderer.debug.BrainDebugRenderer
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
- net.minecraft.client.renderer.debug.BreezeDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkBorderRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer
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
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.HeightMapRenderer$1
- net.minecraft.client.renderer.debug.LightDebugRenderer
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer
- net.minecraft.client.renderer.debug.LightSectionDebugRenderer$1
+ net.minecraft.client.renderer.debug.LightSectionDebugRenderer$SectionData
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
+ net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.SupportBlockRenderer
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
- net.minecraft.client.renderer.entity.AllayRenderer
+ net.minecraft.client.renderer.entity.ArmadilloRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.entity.BoggedRenderer
- net.minecraft.client.renderer.entity.BreezeRenderer
+ net.minecraft.client.renderer.entity.CamelRenderer
- net.minecraft.client.renderer.entity.CatRenderer
+ net.minecraft.client.renderer.entity.CaveSpiderRenderer
- net.minecraft.client.renderer.entity.ChestedHorseRenderer
+ net.minecraft.client.renderer.entity.ChickenRenderer
- net.minecraft.client.renderer.entity.CodRenderer
+ net.minecraft.client.renderer.entity.CowRenderer
- net.minecraft.client.renderer.entity.CreeperRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$1
+ net.minecraft.client.renderer.entity.DisplayRenderer$BlockDisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$ItemDisplayRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer$TextDisplayRenderer
- net.minecraft.client.renderer.entity.DolphinRenderer
+ net.minecraft.client.renderer.entity.DragonFireballRenderer
- net.minecraft.client.renderer.entity.DrownedRenderer
+ net.minecraft.client.renderer.entity.ElderGuardianRenderer
- net.minecraft.client.renderer.entity.EndCrystalRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
+ net.minecraft.client.renderer.entity.EndermanRenderer
- net.minecraft.client.renderer.entity.EndermiteRenderer
+ net.minecraft.client.renderer.entity.EntityRenderDispatcher
- net.minecraft.client.renderer.entity.EntityRenderer
+ net.minecraft.client.renderer.entity.EntityRendererProvider
- net.minecraft.client.renderer.entity.EntityRendererProvider$Context
+ net.minecraft.client.renderer.entity.EntityRenderers
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
- net.minecraft.client.renderer.entity.FrogRenderer
+ net.minecraft.client.renderer.entity.GhastRenderer
- net.minecraft.client.renderer.entity.GiantMobRenderer
+ net.minecraft.client.renderer.entity.GlowSquidRenderer
- net.minecraft.client.renderer.entity.GoatRenderer
+ net.minecraft.client.renderer.entity.GuardianRenderer
- net.minecraft.client.renderer.entity.HoglinRenderer
+ net.minecraft.client.renderer.entity.HorseRenderer
- net.minecraft.client.renderer.entity.HumanoidMobRenderer
+ net.minecraft.client.renderer.entity.HuskRenderer
- net.minecraft.client.renderer.entity.IllagerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer$1
+ net.minecraft.client.renderer.entity.IronGolemRenderer
- net.minecraft.client.renderer.entity.ItemEntityRenderer
+ net.minecraft.client.renderer.entity.ItemFrameRenderer
- net.minecraft.client.renderer.entity.ItemRenderer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.BreezeEyesLayer
- net.minecraft.client.renderer.entity.layers.BreezeWindLayer
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
- net.minecraft.client.renderer.entity.layers.package-info
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SaddleLayer
- net.minecraft.client.renderer.entity.layers.SheepFurLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
- net.minecraft.client.renderer.entity.layers.SkeletonClothingLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
- net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer$1
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$AlphaFunction
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$DrawSelector
- net.minecraft.client.renderer.entity.layers.WitchItemLayer
+ net.minecraft.client.renderer.entity.layers.WitherArmorLayer
- net.minecraft.client.renderer.entity.layers.WolfArmorLayer
+ net.minecraft.client.renderer.entity.layers.WolfCollarLayer
+ net.minecraft.client.renderer.entity.LeashKnotRenderer
- net.minecraft.client.renderer.entity.LightningBoltRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer$1
+ net.minecraft.client.renderer.entity.LlamaRenderer
- net.minecraft.client.renderer.entity.LlamaRenderer$1
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.NoopRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
+ net.minecraft.client.renderer.entity.package-info
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer$1
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer$1
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnifferRenderer
- net.minecraft.client.renderer.entity.SnowGolemRenderer
+ net.minecraft.client.renderer.entity.SpectralArrowRenderer
- net.minecraft.client.renderer.entity.SpiderRenderer
+ net.minecraft.client.renderer.entity.SquidRenderer
- net.minecraft.client.renderer.entity.StrayRenderer
+ net.minecraft.client.renderer.entity.StriderRenderer
- net.minecraft.client.renderer.entity.TadpoleRenderer
+ net.minecraft.client.renderer.entity.ThrownItemRenderer
- net.minecraft.client.renderer.entity.ThrownTridentRenderer
+ net.minecraft.client.renderer.entity.TippableArrowRenderer
- net.minecraft.client.renderer.entity.TntMinecartRenderer
+ net.minecraft.client.renderer.entity.TntRenderer
- net.minecraft.client.renderer.entity.TropicalFishRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer$1
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WardenRenderer
- net.minecraft.client.renderer.entity.WindChargeRenderer
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZoglinRenderer
+ net.minecraft.client.renderer.entity.ZombieRenderer
- net.minecraft.client.renderer.entity.ZombieVillagerRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
- net.minecraft.client.renderer.FogRenderer$DarknessFogFunction
+ net.minecraft.client.renderer.FogRenderer$FogData
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.FogRenderer$MobEffectFogFunction
- net.minecraft.client.renderer.GameRenderer
+ net.minecraft.client.renderer.GameRenderer$1
- net.minecraft.client.renderer.GameRenderer$ResourceCache
+ net.minecraft.client.renderer.GpuWarnlistManager
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
- net.minecraft.client.renderer.item.ClampedItemPropertyFunction
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction
- net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassTarget
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassWobble
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
+ net.minecraft.client.renderer.PanoramaRenderer
- net.minecraft.client.renderer.PostChain
+ net.minecraft.client.renderer.PostPass
- net.minecraft.client.renderer.Rect2i
+ net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
- net.minecraft.client.renderer.RenderStateShard$ColorLogicStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.SectionBufferBuilderPack
+ net.minecraft.client.renderer.SectionBufferBuilderPool
- net.minecraft.client.renderer.SectionOcclusionGraph
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphEvents
- net.minecraft.client.renderer.SectionOcclusionGraph$GraphState
+ net.minecraft.client.renderer.SectionOcclusionGraph$GraphStorage
- net.minecraft.client.renderer.SectionOcclusionGraph$Node
+ net.minecraft.client.renderer.SectionOcclusionGraph$SectionToNodeMap
- net.minecraft.client.renderer.ShaderInstance
+ net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.texture.AbstractTexture
+ net.minecraft.client.renderer.texture.atlas.package-info
- net.minecraft.client.renderer.texture.atlas.sources.DirectoryLister
+ net.minecraft.client.renderer.texture.atlas.sources.LazyLoadedImage
+ net.minecraft.client.renderer.texture.atlas.sources.package-info
- net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations
+ net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
- net.minecraft.client.renderer.texture.atlas.sources.SingleFile
+ net.minecraft.client.renderer.texture.atlas.sources.SourceFilter
- net.minecraft.client.renderer.texture.atlas.sources.Unstitcher
+ net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$Region
- net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$RegionInstance
+ net.minecraft.client.renderer.texture.atlas.SpriteResourceLoader
- net.minecraft.client.renderer.texture.atlas.SpriteSource
+ net.minecraft.client.renderer.texture.atlas.SpriteSource$Output
- net.minecraft.client.renderer.texture.atlas.SpriteSource$SpriteSupplier
+ net.minecraft.client.renderer.texture.atlas.SpriteSourceList
- net.minecraft.client.renderer.texture.atlas.SpriteSourceList$1
- net.minecraft.client.renderer.texture.atlas.SpriteSources
+ net.minecraft.client.renderer.texture.atlas.SpriteSourceType
- net.minecraft.client.renderer.texture.Dumpable
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
- net.minecraft.client.renderer.texture.package-info
- net.minecraft.client.renderer.texture.PreloadedTexture
+ net.minecraft.client.renderer.texture.SimpleTexture
- net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
+ net.minecraft.client.renderer.texture.SpriteContents
- net.minecraft.client.renderer.texture.SpriteContents$AnimatedTexture
+ net.minecraft.client.renderer.texture.SpriteContents$FrameInfo
- net.minecraft.client.renderer.texture.SpriteContents$InterpolationData
+ net.minecraft.client.renderer.texture.SpriteContents$Ticker
- net.minecraft.client.renderer.texture.SpriteLoader
+ net.minecraft.client.renderer.texture.SpriteLoader$Preparations
- net.minecraft.client.renderer.texture.SpriteTicker
+ net.minecraft.client.renderer.texture.Stitcher
- net.minecraft.client.renderer.texture.Stitcher$Entry
+ net.minecraft.client.renderer.texture.Stitcher$Holder
- net.minecraft.client.renderer.texture.Stitcher$Region
+ net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
- net.minecraft.client.renderer.texture.StitcherException
+ net.minecraft.client.renderer.texture.TextureAtlas
- net.minecraft.client.renderer.texture.TextureAtlasSprite
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$1
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Ticker
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.ResourceLoadStateTracker
+ net.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
- net.minecraft.client.ResourceLoadStateTracker$ReloadReason
+ net.minecraft.client.ResourceLoadStateTracker$ReloadState
+ net.minecraft.client.resources.ClientPackSource
- net.minecraft.client.resources.DefaultPlayerSkin
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.IndexedAssetSource
- net.minecraft.client.resources.language.ClientLanguage
+ net.minecraft.client.resources.language.FormattedBidiReorder
- net.minecraft.client.resources.language.I18n
+ net.minecraft.client.resources.language.LanguageInfo
- net.minecraft.client.resources.language.LanguageManager
+ net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyStuffWrapper
- net.minecraft.client.resources.metadata.animation.AnimationFrame
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.animation.FrameSize
+ net.minecraft.client.resources.metadata.animation.package-info
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
- net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
- net.minecraft.client.resources.metadata.gui.GuiMetadataSection
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice$Border
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Stretch
+ net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Tile
- net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$Type
+ net.minecraft.client.resources.metadata.gui.package-info
- net.minecraft.client.resources.metadata.language.LanguageMetadataSection
+ net.minecraft.client.resources.metadata.language.package-info
- net.minecraft.client.resources.metadata.package-info
+ net.minecraft.client.resources.metadata.texture.package-info
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSection
- net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
- net.minecraft.client.resources.model.AtlasSet
+ net.minecraft.client.resources.model.AtlasSet$AtlasEntry
- net.minecraft.client.resources.model.AtlasSet$StitchResult
+ net.minecraft.client.resources.model.BakedModel
- net.minecraft.client.resources.model.BlockModelRotation
+ net.minecraft.client.resources.model.BuiltInModel
- net.minecraft.client.resources.model.Material
+ net.minecraft.client.resources.model.ModelBaker
- net.minecraft.client.resources.model.ModelBakery
+ net.minecraft.client.resources.model.ModelBakery$BakedCacheKey
- net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
+ net.minecraft.client.resources.model.ModelBakery$LoadedJson
- net.minecraft.client.resources.model.ModelBakery$ModelBakerImpl
+ net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
- net.minecraft.client.resources.model.ModelManager
+ net.minecraft.client.resources.model.ModelManager$ReloadState
- net.minecraft.client.resources.model.ModelResourceLocation
+ net.minecraft.client.resources.model.ModelState
- net.minecraft.client.resources.model.MultiPartBakedModel
+ net.minecraft.client.resources.model.MultiPartBakedModel$Builder
+ net.minecraft.client.resources.model.package-info
- net.minecraft.client.resources.model.SimpleBakedModel
+ net.minecraft.client.resources.model.SimpleBakedModel$Builder
- net.minecraft.client.resources.model.UnbakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel
- net.minecraft.client.resources.model.WeightedBakedModel$Builder
- net.minecraft.client.resources.package-info
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.PlayerSkin
- net.minecraft.client.resources.PlayerSkin$Model
+ net.minecraft.client.resources.server.DownloadedPackSource
- net.minecraft.client.resources.server.DownloadedPackSource$1
+ net.minecraft.client.resources.server.DownloadedPackSource$2
- net.minecraft.client.resources.server.DownloadedPackSource$3
+ net.minecraft.client.resources.server.DownloadedPackSource$4
- net.minecraft.client.resources.server.DownloadedPackSource$5
+ net.minecraft.client.resources.server.DownloadedPackSource$6
- net.minecraft.client.resources.server.DownloadedPackSource$7
+ net.minecraft.client.resources.server.DownloadedPackSource$8
+ net.minecraft.client.resources.server.package-info
- net.minecraft.client.resources.server.PackDownloader
+ net.minecraft.client.resources.server.PackLoadFeedback
- net.minecraft.client.resources.server.PackLoadFeedback$FinalResult
+ net.minecraft.client.resources.server.PackLoadFeedback$Update
- net.minecraft.client.resources.server.PackReloadConfig
+ net.minecraft.client.resources.server.PackReloadConfig$Callbacks
- net.minecraft.client.resources.server.PackReloadConfig$IdAndPath
+ net.minecraft.client.resources.server.ServerPackManager
- net.minecraft.client.resources.server.ServerPackManager$1
+ net.minecraft.client.resources.server.ServerPackManager$2
- net.minecraft.client.resources.server.ServerPackManager$ActivationStatus
+ net.minecraft.client.resources.server.ServerPackManager$PackDownloadStatus
- net.minecraft.client.resources.server.ServerPackManager$PackPromptStatus
+ net.minecraft.client.resources.server.ServerPackManager$RemovalReason
- net.minecraft.client.resources.server.ServerPackManager$ServerPackData
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$2
- net.minecraft.client.resources.SkinManager$CacheKey
+ net.minecraft.client.resources.SkinManager$TextureCache
- net.minecraft.client.resources.sounds.AbstractSoundInstance
+ net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
- net.minecraft.client.resources.sounds.AmbientSoundHandler
+ net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
- net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
+ net.minecraft.client.resources.sounds.BeeSoundInstance
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
+ net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
- net.minecraft.client.resources.sounds.EntityBoundSoundInstance
+ net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
- net.minecraft.client.resources.sounds.MinecartSoundInstance
+ net.minecraft.client.resources.sounds.package-info
+ net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
- net.minecraft.client.resources.sounds.SimpleSoundInstance
+ net.minecraft.client.resources.sounds.SnifferSoundInstance
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
- net.minecraft.client.resources.SplashManager
+ net.minecraft.client.resources.TextureAtlasHolder
- net.minecraft.client.Screenshot
- net.minecraft.client.searchtree.FullTextSearchTree
+ net.minecraft.client.searchtree.IdSearchTree
- net.minecraft.client.searchtree.IntersectionIterator
+ net.minecraft.client.searchtree.MergingUniqueIterator
+ net.minecraft.client.searchtree.package-info
- net.minecraft.client.searchtree.PlainTextSearchTree
+ net.minecraft.client.searchtree.RefreshableSearchTree
- net.minecraft.client.searchtree.ResourceLocationSearchTree
+ net.minecraft.client.searchtree.ResourceLocationSearchTree$1
- net.minecraft.client.searchtree.ResourceLocationSearchTree$2
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchRegistry$TreeBuilderSupplier
- net.minecraft.client.searchtree.SearchRegistry$TreeEntry
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
- net.minecraft.client.server.IntegratedPlayerList
+ net.minecraft.client.server.IntegratedServer
- net.minecraft.client.server.LanServer
+ net.minecraft.client.server.LanServerDetection
- net.minecraft.client.server.LanServerDetection$LanServerDetector
+ net.minecraft.client.server.LanServerDetection$LanServerList
- net.minecraft.client.server.LanServerPinger
+ net.minecraft.client.server.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
+ net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
- net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
+ net.minecraft.client.sounds.SoundBufferLibrary
- net.minecraft.client.sounds.SoundEngine
+ net.minecraft.client.sounds.SoundEngine$DeviceCheckState
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
- net.minecraft.client.telemetry.ClientTelemetryManager
- net.minecraft.client.telemetry.events.AggregatedTelemetryEvent
+ net.minecraft.client.telemetry.events.GameLoadTimesEvent
- net.minecraft.client.telemetry.events.GameLoadTimesEvent$Measurement
- net.minecraft.client.telemetry.events.package-info
+ net.minecraft.client.telemetry.events.PerformanceMetricsEvent
- net.minecraft.client.telemetry.events.WorldLoadEvent
+ net.minecraft.client.telemetry.events.WorldLoadEvent$1
- net.minecraft.client.telemetry.events.WorldLoadTimesEvent
+ net.minecraft.client.telemetry.events.WorldUnloadEvent
+ net.minecraft.client.telemetry.package-info
+ net.minecraft.client.telemetry.TelemetryEventInstance
- net.minecraft.client.telemetry.TelemetryEventLog
+ net.minecraft.client.telemetry.TelemetryEventLogger
- net.minecraft.client.telemetry.TelemetryEventSender
+ net.minecraft.client.telemetry.TelemetryEventType
- net.minecraft.client.telemetry.TelemetryEventType$Builder
+ net.minecraft.client.telemetry.TelemetryLogManager
- net.minecraft.client.telemetry.TelemetryProperty
+ net.minecraft.client.telemetry.TelemetryProperty$Exporter
- net.minecraft.client.telemetry.TelemetryProperty$GameMode
+ net.minecraft.client.telemetry.TelemetryProperty$ServerType
- net.minecraft.client.telemetry.TelemetryPropertyMap
+ net.minecraft.client.telemetry.TelemetryPropertyMap$1
- net.minecraft.client.telemetry.TelemetryPropertyMap$Builder
+ net.minecraft.client.telemetry.WorldSessionTelemetryManager
+ net.minecraft.client.Timer
- net.minecraft.client.ToggleKeyMapping
- net.minecraft.client.tutorial.BundleTutorial
+ net.minecraft.client.tutorial.CompletedTutorialStepInstance
- net.minecraft.client.tutorial.CraftPlanksTutorialStep
+ net.minecraft.client.tutorial.FindTreeTutorialStepInstance
- net.minecraft.client.tutorial.MovementTutorialStepInstance
+ net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
- net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
+ net.minecraft.client.tutorial.Tutorial
- net.minecraft.client.tutorial.Tutorial$TimedToast
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
+ net.minecraft.client.User
- net.minecraft.client.User$Type
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.ArgumentSignatures
- net.minecraft.commands.arguments.ArgumentSignatures$Entry
+ net.minecraft.commands.arguments.ArgumentSignatures$Signer
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Info
- net.minecraft.commands.arguments.EntityArgument$Info$Template
+ net.minecraft.commands.arguments.GameModeArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.HeightmapTypeArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
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
- net.minecraft.commands.arguments.ResourceArgument
+ net.minecraft.commands.arguments.ResourceArgument$Info
- net.minecraft.commands.arguments.ResourceArgument$Info$Template
+ net.minecraft.commands.arguments.ResourceKeyArgument
- net.minecraft.commands.arguments.ResourceKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.arguments.ResourceOrTagArgument
- net.minecraft.commands.arguments.ResourceOrTagArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagArgument$TagResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ net.minecraft.commands.arguments.ResourceOrTagKeyArgument$Result
- net.minecraft.commands.arguments.ResourceOrTagKeyArgument$TagResult
- net.minecraft.commands.arguments.ScoreboardSlotArgument
+ net.minecraft.commands.arguments.ScoreHolderArgument
- net.minecraft.commands.arguments.ScoreHolderArgument$Info
+ net.minecraft.commands.arguments.ScoreHolderArgument$Info$Template
- net.minecraft.commands.arguments.ScoreHolderArgument$Result
+ net.minecraft.commands.arguments.ScoreHolderArgument$SelectorResult
+ net.minecraft.commands.arguments.SignedArgument
- net.minecraft.commands.arguments.SlotArgument
- net.minecraft.commands.BrigadierExceptions
+ net.minecraft.commands.CacheableFunction
- net.minecraft.commands.CommandBuildContext
+ net.minecraft.commands.CommandBuildContext$1
- net.minecraft.commands.CommandResultCallback
+ net.minecraft.commands.CommandResultCallback$1
- net.minecraft.commands.Commands
+ net.minecraft.commands.Commands$1
- net.minecraft.commands.Commands$1$1
+ net.minecraft.commands.Commands$CommandSelection
- net.minecraft.commands.Commands$ParseFunction
- net.minecraft.commands.CommandSigningContext
+ net.minecraft.commands.CommandSigningContext$1
- net.minecraft.commands.CommandSigningContext$SignedArguments
+ net.minecraft.commands.CommandSource
- net.minecraft.commands.CommandSource$1
+ net.minecraft.commands.CommandSourceStack
+ net.minecraft.commands.ExecutionCommandSource
- net.minecraft.commands.FunctionInstantiationException
+ net.minecraft.commands.ParserUtils
- net.minecraft.commands.SharedSuggestionProvider
+ net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- net.minecraft.util.datafix.fixes.ItemStackComponentizationFix
+ net.minecraft.util.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTagFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemStackUUIDFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.JigsawPropertiesFix
+ net.minecraft.util.datafix.fixes.JigsawRotationFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LegacyDragonFightFix
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.LevelUUIDFix
- net.minecraft.util.datafix.fixes.LodestoneCompassComponentFix
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
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.RenameEnchantmentsFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.ScoreboardDisplaySlotFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StatsCounterFix$StatType
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TippedArrowPotionToItemFix
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
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
+ net.minecraft.util.datafix.schemas.package-info
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
+ net.minecraft.util.datafix.schemas.V3685
- net.minecraft.util.datafix.schemas.V3689
+ net.minecraft.util.datafix.schemas.V3799
- net.minecraft.util.datafix.schemas.V3807
+ net.minecraft.util.datafix.schemas.V3808
- net.minecraft.util.datafix.schemas.V3808_1
+ net.minecraft.util.datafix.schemas.V3816
- net.minecraft.util.datafix.schemas.V3818
+ net.minecraft.util.datafix.schemas.V3818_3
- net.minecraft.util.datafix.schemas.V3818_4
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
- net.minecraft.util.debugchart.AbstractSampleLogger
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- net.minecraft.util.debugchart.LocalSampleLogger
+ net.minecraft.util.debugchart.RemoteDebugSampleType
- net.minecraft.util.debugchart.RemoteSampleLogger
+ net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.debugchart.SampleStorage
+ net.minecraft.util.debugchart.TpsDebugDimensions
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
+ net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
- net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.ChunkIdentification
- net.minecraft.util.profiling.jfr.stats.CpuLoadStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
- net.minecraft.util.profiling.jfr.stats.IoSummary
+ net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.PacketIdentification
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.MultipliedFloats
- net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.SampledFloat
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
+ net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
+ net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
+ net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
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
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.BadOmenMobEffect
+ net.minecraft.world.effect.HealOrHarmMobEffect
- net.minecraft.world.effect.HungerMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffect$AttributeTemplate
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffectInstance$BlendState
+ net.minecraft.world.effect.MobEffectInstance$Details
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
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
- net.minecraft.world.entity.ai.behavior.declarative.package-info
+ net.minecraft.world.entity.ai.behavior.declarative.Trigger
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
- net.minecraft.world.entity.ai.behavior.LongJumpUtil
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.OneShot
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
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
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TriggerGate
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.warden.Digging
+ net.minecraft.world.entity.ai.behavior.warden.Emerging
- net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
+ net.minecraft.world.entity.ai.behavior.warden.package-info
+ net.minecraft.world.entity.ai.behavior.warden.Roar
- net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
+ net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
- net.minecraft.world.entity.ai.behavior.warden.Sniffing
+ net.minecraft.world.entity.ai.behavior.warden.SonicBoom
- net.minecraft.world.entity.ai.behavior.warden.TryToSniff
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
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
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
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
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStandGoal
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
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.BreezeAttackEntitySensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.MobSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
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
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
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
- net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.poi.PoiTypes
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
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
- net.minecraft.world.entity.animal.CatVariant
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
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
- net.minecraft.world.entity.animal.FrogVariant
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
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
- net.minecraft.world.entity.animal.WolfVariants
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
+ net.minecraft.world.entity.Attackable
- net.minecraft.world.entity.Crackiness
+ net.minecraft.world.entity.Crackiness$Level
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
- net.minecraft.world.entity.EntityAttachment
+ net.minecraft.world.entity.EntityAttachment$Fallback
- net.minecraft.world.entity.EntityAttachments
+ net.minecraft.world.entity.EntityAttachments$Builder
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
- net.minecraft.world.entity.EquipmentSlotGroup
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
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
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Player$2
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacementType
- net.minecraft.world.entity.SpawnPlacementTypes
+ net.minecraft.world.entity.SpawnPlacementTypes$1
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
+ net.minecraft.world.entity.WalkAnimationState
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.SlotRange$1
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.inventory.TransientCraftingContainer
+ net.minecraft.world.item.AdventureModePredicate
- net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
+ net.minecraft.world.item.alchemy.PotionContents
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.AnimalArmorItem
- net.minecraft.world.item.AnimalArmorItem$BodyType
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorItem$Type
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterial$Layer
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
- net.minecraft.world.item.BoneMealItem$1
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BrushItem
- net.minecraft.world.item.BrushItem$1
+ net.minecraft.world.item.BrushItem$DustParticlesDelta
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.component.BlockItemStateProperties
+ net.minecraft.world.item.component.BundleContents
- net.minecraft.world.item.component.BundleContents$Mutable
+ net.minecraft.world.item.component.ChargedProjectiles
- net.minecraft.world.item.component.CustomData
+ net.minecraft.world.item.component.CustomModelData
- net.minecraft.world.item.component.DebugStickState
+ net.minecraft.world.item.component.DyedItemColor
- net.minecraft.world.item.component.FireworkExplosion
+ net.minecraft.world.item.component.FireworkExplosion$Shape
- net.minecraft.world.item.component.Fireworks
+ net.minecraft.world.item.component.ItemAttributeModifiers
- net.minecraft.world.item.component.ItemAttributeModifiers$1
+ net.minecraft.world.item.component.ItemAttributeModifiers$Builder
- net.minecraft.world.item.component.ItemAttributeModifiers$Entry
+ net.minecraft.world.item.component.ItemContainerContents
- net.minecraft.world.item.component.ItemContainerContents$Slot
+ net.minecraft.world.item.component.ItemLore
- net.minecraft.world.item.component.LodestoneTracker
+ net.minecraft.world.item.component.MapDecorations
- net.minecraft.world.item.component.MapDecorations$Entry
+ net.minecraft.world.item.component.MapItemColor
- net.minecraft.world.item.component.MapPostProcessing
+ net.minecraft.world.item.component.package-info
+ net.minecraft.world.item.component.ResolvableProfile
- net.minecraft.world.item.component.SeededContainerLoot
+ net.minecraft.world.item.component.SuspiciousStewEffects
- net.minecraft.world.item.component.SuspiciousStewEffects$Entry
+ net.minecraft.world.item.component.TooltipProvider
- net.minecraft.world.item.component.Unbreakable
+ net.minecraft.world.item.component.WritableBookContent
- net.minecraft.world.item.component.WrittenBookContent
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.AbstractCookingRecipe$Factory
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CookingBookCategory
+ net.minecraft.world.item.crafting.CraftingBookCategory
- net.minecraft.world.item.crafting.CraftingRecipe
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
+ net.minecraft.world.item.crafting.ShapedRecipePattern
- net.minecraft.world.item.crafting.ShapedRecipePattern$Data
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
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
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$Builder
- net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
+ net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTab$Row
+ net.minecraft.world.item.CreativeModeTab$TabVisibility
- net.minecraft.world.item.CreativeModeTab$Type
+ net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
+ net.minecraft.world.item.DiscFragmentItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
- net.minecraft.world.item.EggItem
+ net.minecraft.world.item.ElytraItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
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
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.ItemEnchantments
+ net.minecraft.world.item.enchantment.ItemEnchantments$Mutable
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.SwiftSneakEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.Equipable
- net.minecraft.world.item.ExperienceBottleItem
+ net.minecraft.world.item.FireChargeItem
- net.minecraft.world.item.FireworkRocketItem
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
- net.minecraft.world.item.InkSacItem
+ net.minecraft.world.item.Instrument
- net.minecraft.world.item.InstrumentItem
+ net.minecraft.world.item.Instruments
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemDisplayContext
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$1
- net.minecraft.world.item.ItemStack$2
+ net.minecraft.world.item.ItemStackLinkedSet
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MapItem$1
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlaceOnWaterBlockItem
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
- net.minecraft.world.item.SignApplicator
+ net.minecraft.world.item.SignItem
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
- net.minecraft.world.item.trading.ItemCost
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.WindChargeItem
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.ItemInteractionResult
+ net.minecraft.world.ItemInteractionResult$1
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
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BambooStalkBlock
+ net.minecraft.world.level.block.BannerBlock
- net.minecraft.world.level.block.BarrelBlock
+ net.minecraft.world.level.block.BarrierBlock
- net.minecraft.world.level.block.BaseCoralFanBlock
+ net.minecraft.world.level.block.BaseCoralPlantBlock
- net.minecraft.world.level.block.BaseCoralPlantTypeBlock
+ net.minecraft.world.level.block.BaseCoralWallFanBlock
- net.minecraft.world.level.block.BaseEntityBlock
+ net.minecraft.world.level.block.BaseFireBlock
- net.minecraft.world.level.block.BasePressurePlateBlock
+ net.minecraft.world.level.block.BaseRailBlock
- net.minecraft.world.level.block.BaseRailBlock$1
+ net.minecraft.world.level.block.BaseTorchBlock
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BigDripleafBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock
- net.minecraft.world.level.block.BigDripleafStemBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BlockTypes
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BonemealableBlock$1
- net.minecraft.world.level.block.BonemealableBlock$Type
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BrushableBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BuddingAmethystBlock
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CalibratedSculkSensorBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVines
+ net.minecraft.world.level.block.CaveVinesBlock
- net.minecraft.world.level.block.CaveVinesPlantBlock
+ net.minecraft.world.level.block.CeilingHangingSignBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChainBlock$1
- net.minecraft.world.level.block.ChangeOverTimeBlock
+ net.minecraft.world.level.block.CherryLeavesBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChiseledBookShelfBlock
+ net.minecraft.world.level.block.ChiseledBookShelfBlock$1
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.ColoredFallingBlock
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CopperBulbBlock
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
- net.minecraft.world.level.block.entity.BannerPatternLayers
+ net.minecraft.world.level.block.entity.BannerPatternLayers$Builder
- net.minecraft.world.level.block.entity.BannerPatternLayers$Layer
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
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$Occupant
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
+ net.minecraft.world.level.block.entity.BrushableBlockEntity
- net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.CrafterBlockEntity
- net.minecraft.world.level.block.entity.CrafterBlockEntity$1
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DecoratedPotBlockEntity
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
+ net.minecraft.world.level.block.entity.PotDecorations
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
- net.minecraft.world.level.block.entity.SculkCatalystBlockEntity$CatalystListener
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.SculkShriekerBlockEntity
- net.minecraft.world.level.block.entity.SculkShriekerBlockEntity$VibrationUser
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SignText
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity$1
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.entity.trialspawner.package-info
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector
+ net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$1
- net.minecraft.world.level.block.entity.trialspawner.PlayerDetector$EntitySelector$2
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawner
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawner$StateAccessor
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerConfig
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerData
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$1
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$LightLevel
- net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$ParticleEmission
+ net.minecraft.world.level.block.entity.trialspawner.TrialSpawnerState$SpinningMob
+ net.minecraft.world.level.block.entity.TrialSpawnerBlockEntity
+ net.minecraft.world.level.block.entity.vault.package-info
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity
- net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Client
+ net.minecraft.world.level.block.entity.vault.VaultBlockEntity$Server
- net.minecraft.world.level.block.entity.vault.VaultClientData
+ net.minecraft.world.level.block.entity.vault.VaultConfig
- net.minecraft.world.level.block.entity.vault.VaultServerData
+ net.minecraft.world.level.block.entity.vault.VaultSharedData
- net.minecraft.world.level.block.entity.vault.VaultState
+ net.minecraft.world.level.block.entity.vault.VaultState$1
- net.minecraft.world.level.block.entity.vault.VaultState$2
+ net.minecraft.world.level.block.entity.vault.VaultState$3
- net.minecraft.world.level.block.entity.vault.VaultState$4
+ net.minecraft.world.level.block.entity.vault.VaultState$5
- net.minecraft.world.level.block.entity.vault.VaultState$LightLevel
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
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GlowLichenBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.TreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.InfestedRotatedPillarBlock
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
- net.minecraft.world.level.block.LightBlock
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MangroveLeavesBlock
+ net.minecraft.world.level.block.MangrovePropaguleBlock
- net.minecraft.world.level.block.MangroveRootsBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MudBlock
+ net.minecraft.world.level.block.MultifaceBlock
- net.minecraft.world.level.block.MultifaceSpreader
+ net.minecraft.world.level.block.MultifaceSpreader$DefaultSpreaderConfig
- net.minecraft.world.level.block.MultifaceSpreader$SpreadConfig
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadPos
- net.minecraft.world.level.block.MultifaceSpreader$SpreadPredicate
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$1
+ net.minecraft.world.level.block.MultifaceSpreader$SpreadType$2
- net.minecraft.world.level.block.MultifaceSpreader$SpreadType$3
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PiglinWallSkullBlock
+ net.minecraft.world.level.block.PinkPetalsBlock
- net.minecraft.world.level.block.PipeBlock
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
+ net.minecraft.world.level.block.PitcherCropBlock
- net.minecraft.world.level.block.PitcherCropBlock$PosAndState
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkBehaviour
+ net.minecraft.world.level.block.SculkBehaviour$1
- net.minecraft.world.level.block.SculkBlock
+ net.minecraft.world.level.block.SculkCatalystBlock
- net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SculkShriekerBlock
- net.minecraft.world.level.block.SculkSpreader
+ net.minecraft.world.level.block.SculkSpreader$ChargeCursor
- net.minecraft.world.level.block.SculkVeinBlock
+ net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnifferEggBlock
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
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetFunction
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
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockSetType
- net.minecraft.world.level.block.state.properties.BlockSetType$PressurePlateSensitivity
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ChestType$1
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument$Type
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.Property$Value
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.RotationSegment
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SuspiciousEffectHolder
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TorchflowerCropBlock
+ net.minecraft.world.level.block.TransparentBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TrialSpawnerBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VaultBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallHangingSignBlock
- net.minecraft.world.level.block.WallHangingSignBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WaterloggedTransparentBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperBulbBlock
+ net.minecraft.world.level.block.WeatheringCopperDoorBlock
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperGrateBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
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
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.CarvingMask$Mask
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkGenerators
+ net.minecraft.world.level.chunk.ChunkGeneratorStructureState
+ net.minecraft.world.level.chunk.ChunkSource
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
- net.minecraft.world.level.chunk.status.ChunkStatus
+ net.minecraft.world.level.chunk.status.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.status.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.status.ChunkStatusTasks
- net.minecraft.world.level.chunk.status.ChunkType
+ net.minecraft.world.level.chunk.status.package-info
+ net.minecraft.world.level.chunk.status.ToFullChunk
- net.minecraft.world.level.chunk.status.WorldGenContext
- net.minecraft.world.level.chunk.storage.ChunkScanAccess
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkSerializer$ChunkReadException
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RecreatingChunkStorage
+ net.minecraft.world.level.chunk.storage.RecreatingSimpleRegionStorage
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.RegionStorageInfo
- net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.storage.SimpleRegionStorage
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
+ net.minecraft.world.level.dimension.BuiltinDimensionTypes
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.DimensionType$MonsterSettings
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.EndDragonFight$Data
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.EntityTypeTest$2
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
- net.minecraft.world.level.gameevent.GameEventListener$Provider
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
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.AmphibiousNodeEvaluator
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.Path$DebugData
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.PathfindingContext
+ net.minecraft.world.level.pathfinder.PathType
- net.minecraft.world.level.pathfinder.PathTypeCache
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator$1
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.portal.package-info
+ net.minecraft.world.level.portal.PortalForcer
- net.minecraft.world.level.portal.PortalInfo
+ net.minecraft.world.level.portal.PortalShape
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ net.minecraft.world.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- net.minecraft.world.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ net.minecraft.world.level.redstone.InstantNeighborUpdater
- net.minecraft.world.level.redstone.NeighborUpdater
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapId
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$MapPatch
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.saveddata.SavedData$Factory
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.SignalGetter
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.Spawner
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DataVersion
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.FileNameDateFormatter
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelDataAndDimensions
+ net.minecraft.world.level.storage.LevelResource
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$LevelCandidates
+ net.minecraft.world.level.storage.LevelStorageSource$LevelDirectory
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
+ net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$1
- net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess$2
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.LevelSummary$BackupStatus
+ net.minecraft.world.level.storage.LevelSummary$CorruptedLevelSummary
- net.minecraft.world.level.storage.LevelSummary$SymlinkLevelSummary
+ net.minecraft.world.level.storage.LevelVersion
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.NestedLootTable
+ net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Path
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
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
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetComponentsFunction
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetEnchantmentsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetPotionFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataId
- net.minecraft.world.level.storage.loot.LootDataManager
+ net.minecraft.world.level.storage.loot.LootDataManager$1
- net.minecraft.world.level.storage.loot.LootDataResolver
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootParams
- net.minecraft.world.level.storage.loot.LootParams$Builder
+ net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
+ net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
- net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
+ net.minecraft.world.level.storage.loot.providers.score.package-info
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.PrimaryLevelData$SpecialWorldProperty
+ net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureManager
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.level.validation.ContentValidationException
- net.minecraft.world.level.validation.DirectoryValidator
+ net.minecraft.world.level.validation.DirectoryValidator$1
- net.minecraft.world.level.validation.ForbiddenSymlinkInfo
- net.minecraft.world.level.validation.package-info
+ net.minecraft.world.level.validation.PathAllowList
- net.minecraft.world.level.validation.PathAllowList$ConfigEntry
+ net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.level.WorldDataConfiguration
+ net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.DisplaySlot
- net.minecraft.world.scores.DisplaySlot$1
+ net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerScoreEntry
+ net.minecraft.world.scores.PlayerScores
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.ReadOnlyScoreInfo
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.ScoreAccess
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.Scoreboard$1
- net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.ScoreHolder
+ net.minecraft.world.scores.ScoreHolder$1
- net.minecraft.world.scores.ScoreHolder$2
+ net.minecraft.world.scores.ScoreHolder$3
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
- net.minecraft.world.ticks.BlackholeTickAccess
+ net.minecraft.world.ticks.BlackholeTickAccess$1
- net.minecraft.world.ticks.BlackholeTickAccess$2
+ net.minecraft.world.ticks.ContainerSingleItem
- net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
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
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.EntityEquipmentPredicate +1M | -1P
```
```
XXX.advancements.critereon.EntityPredicate +2M -1M | +1P
```
```
XXX.commands.arguments.StringRepresentableArgument +1M -1M
```
```
XXX.minecraft.core.HolderSet$Direct +2M
```
```
XXX.minecraft.nbt.NbtUtils -2M
```
```
XXX.server.commands.ClearInventoryCommands +1M
```
```
XXX.server.commands.ExecuteCommand +33M -27M
```
```
XXX.entity.player.Player +2P
```
```
XXX.entity.raid.Raid +1M -1M
```
```
XXX.world.inventory.GrindstoneMenu +7M -5M
```

</details>

























































































































































































































<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate
</summary>

```diff
- EntityEquipmentPredicate captainPredicate(HolderGetter)
```

</details>


<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- Optional slots()
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>






































<details>
<summary>
net.minecraft.commands.arguments.StringRepresentableArgument
</summary>

```diff
+ CommandSyntaxException lambda$parse$1(String)
- CommandSyntaxException lambda$parse$1(StringReader,String)
```

</details>
















































































<details>
<summary>
net.minecraft.core.HolderSet$Direct
</summary>

```diff
- boolean equals(Object)
- int hashCode()
```

</details>














































































































































































































































<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
+ CompoundTag writeGameProfile(CompoundTag,GameProfile)
+ GameProfile readGameProfile(CompoundTag)
```

</details>



















































































































































































































































































































































<details>
<summary>
net.minecraft.server.commands.ClearInventoryCommands
</summary>

```diff
- int clearUnlimited(CommandSourceStack,Collection,Predicate)
```

</details>










<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
+ ArgumentBuilder lambda$addConditionals$58(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$addConditionals$62(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
+ boolean lambda$expandOneToManyEntityRelation$74(Entity)
- boolean lambda$expandOneToManyEntityRelation$78(Entity)
+ boolean lambda$expandOneToOneEntityRelation$71(Entity)
- boolean lambda$expandOneToOneEntityRelation$75(Entity)
+ Collection lambda$addConditional$63(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- Collection lambda$addConditional$67(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- Collection lambda$addConditionals$56(boolean,CommandContext)
+ Collection lambda$addConditionals$56(boolean,DataCommands$DataProvider,CommandContext)
- Collection lambda$addConditionals$58(boolean,CommandContext)
- Collection lambda$addConditionals$60(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$addIfBlocksConditional$66(boolean,boolean,CommandContext)
- Collection lambda$addIfBlocksConditional$70(boolean,boolean,CommandContext)
+ Collection lambda$expandOneToManyEntityRelation$75(Function,CommandContext)
- Collection lambda$expandOneToManyEntityRelation$79(Function,CommandContext)
+ Collection lambda$expandOneToOneEntityRelation$73(Function,CommandContext)
- Collection lambda$expandOneToOneEntityRelation$77(Function,CommandContext)
+ Component lambda$addConditional$64()
- Component lambda$addConditional$68()
+ Component lambda$checkIfRegions$69(OptionalInt)
- Component lambda$checkIfRegions$73(OptionalInt)
+ Component lambda$checkUnlessRegions$70()
- Component lambda$checkUnlessRegions$74()
+ Component lambda$createNumericConditionalHandler$59(int)
+ Component lambda$createNumericConditionalHandler$61()
- Component lambda$createNumericConditionalHandler$63(int)
- Component lambda$createNumericConditionalHandler$65()
- int countItems(CommandSourceStack,BlockPos,SlotRange,Predicate)
- int countItems(Iterable,SlotRange,Predicate)
+ int lambda$addConditional$65(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- int lambda$addConditional$69(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- int lambda$addConditionals$57(CommandContext)
+ int lambda$addConditionals$57(DataCommands$DataProvider,CommandContext)
- int lambda$addConditionals$59(CommandContext)
- int lambda$addConditionals$61(DataCommands$DataProvider,CommandContext)
+ int lambda$addIfBlocksConditional$67(boolean,CommandContext)
+ int lambda$addIfBlocksConditional$68(boolean,CommandContext)
- int lambda$addIfBlocksConditional$71(boolean,CommandContext)
- int lambda$addIfBlocksConditional$72(boolean,CommandContext)
+ int lambda$createNumericConditionalHandler$60(ExecuteCommand$CommandNumericPredicate,CommandContext)
+ int lambda$createNumericConditionalHandler$62(ExecuteCommand$CommandNumericPredicate,CommandContext)
- int lambda$createNumericConditionalHandler$64(ExecuteCommand$CommandNumericPredicate,CommandContext)
- int lambda$createNumericConditionalHandler$66(ExecuteCommand$CommandNumericPredicate,CommandContext)
+ List lambda$expandOneToOneEntityRelation$72(CommandSourceStack,Entity)
- List lambda$expandOneToOneEntityRelation$76(CommandSourceStack,Entity)
+ Optional lambda$createRelationOperations$76(Entity)
+ Optional lambda$createRelationOperations$77(Entity)
+ Optional lambda$createRelationOperations$78(Entity)
+ Optional lambda$createRelationOperations$79(Entity)
- Optional lambda$createRelationOperations$83(Entity)
- Optional lambda$createRelationOperations$84(Entity)
- Optional lambda$createRelationOperations$85(Entity)
- Optional lambda$createRelationOperations$86(Entity)
+ Stream lambda$createRelationOperations$83(Entity)
- Stream lambda$createRelationOperations$87(Entity)
+ void lambda$scheduleFunctionConditionsAndTest$84(IntPredicate,List,ExecutionCommandSource,boolean,int)
+ void lambda$scheduleFunctionConditionsAndTest$85(List,ExecutionCommandSource,ExecutionControl)
- void lambda$scheduleFunctionConditionsAndTest$88(IntPredicate,List,ExecutionCommandSource,boolean,int)
- void lambda$scheduleFunctionConditionsAndTest$89(List,ExecutionCommandSource,ExecutionControl)
```

</details>








































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.raid.Raid
</summary>

```diff
+ ItemStack getLeaderBannerInstance()
- ItemStack getLeaderBannerInstance(HolderGetter)
```

</details>

















































<details>
<summary>
net.minecraft.world.inventory.GrindstoneMenu
</summary>

```diff
+ boolean lambda$removeNonCurses$1(Holder)
- boolean lambda$removeNonCursesFrom$1(Holder)
- ItemStack computeResult(ItemStack,ItemStack)
+ ItemStack mergeEnchants(ItemStack,ItemStack)
- ItemStack mergeItems(ItemStack,ItemStack)
+ ItemStack removeNonCurses(ItemStack,int,int)
- ItemStack removeNonCursesFrom(ItemStack)
+ void lambda$mergeEnchants$0(ItemStack,ItemEnchantments$Mutable)
- void lambda$mergeEnchantsFrom$0(ItemStack,ItemEnchantments$Mutable)
+ void lambda$removeNonCurses$2(ItemEnchantments$Mutable)
- void lambda$removeNonCursesFrom$2(ItemEnchantments$Mutable)
- void mergeEnchantsFrom(ItemStack,ItemStack)
```

</details>
</details>