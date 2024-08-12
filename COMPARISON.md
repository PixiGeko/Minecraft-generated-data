## Comparison with [23w04a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w04a)

- [Version data](#version-data)
- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">23w04a</th><th>23w05a</th></tr><tr><td>World version</td><td><code>3321</code></td><td><code>3323</code></td></tr><tr><td>Protocol version</td><td><code>1073741940</code></td><td><code>1073741941</code></td></tr></table>
</details>
<details><summary>Commands</summary>
<details>
<summary>
effect
</summary>

```diff
+ effect give <targets: entity> <effect: resource> infinite <amplifier: integer> <hideParticles: bool>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ createWorld.tab.game.title: Game
+ createWorld.tab.more.title: More...
+ createWorld.tab.world.title: World
+ effect.duration.infinite: ∞
+ gui.narrate.tab: %s tab
+ options.difficulty.easy.info: Hostile mobs spawn but deal less damage. Hunger bar depletes and drains health down to 5 hearts.
+ options.difficulty.hard.info: Hostile mobs spawn and deal more damage. Hunger bar depletes and drains all health.
+ options.difficulty.normal.info: Hostile mobs spawn and deal standard damage. Hunger bar depletes and drains health down to half a heart.
+ options.difficulty.peaceful.info: No hostile mobs and only some neutral mobs spawn. Hunger bar doesn't deplete and health replenishes over time.
+ options.glintSpeed: Glint Speed
+ options.glintSpeed.tooltip: Controls how fast the visual glint shimmers across enchanted items.
+ options.glintStrength: Glint Strength
+ options.glintStrength.tooltip: Controls how transparent the visual glint is on enchanted items.
+ selectWorld.gameMode.adventure.info: Same as Survival Mode, but blocks can't be added or removed
+ selectWorld.gameMode.creative.info: Create, build, and explore without limits. You can fly, have endless materials, and can't be hurt by monsters.
+ selectWorld.gameMode.hardcore.info: Survival mode locked to 'Hard' difficulty. You can't respawn if you die.
+ selectWorld.gameMode.spectator.info: You can look but don't touch
+ selectWorld.gameMode.survival.info: Explore a mysterious world where you build, collect, craft, and fight monsters.
```

</details>
<details>
<summary>
Changes
</summary>

```
item.minecraft.smithing_template.netherite_upgrade.additions_slot_description: Put a Netherite Ingot here
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/models/item/diamond_boots_diamond_darker_trim.json
+ minecraft/models/item/diamond_chestplate_diamond_darker_trim.json
+ minecraft/models/item/diamond_helmet_diamond_darker_trim.json
+ minecraft/models/item/diamond_leggings_diamond_darker_trim.json
+ minecraft/models/item/golden_boots_gold_darker_trim.json
+ minecraft/models/item/golden_chestplate_gold_darker_trim.json
+ minecraft/models/item/golden_helmet_gold_darker_trim.json
+ minecraft/models/item/golden_leggings_gold_darker_trim.json
+ minecraft/models/item/iron_boots_iron_darker_trim.json
+ minecraft/models/item/iron_chestplate_iron_darker_trim.json
+ minecraft/models/item/iron_helmet_iron_darker_trim.json
+ minecraft/models/item/iron_leggings_iron_darker_trim.json
+ minecraft/models/item/leather_boots_amethyst_trim.json
+ minecraft/models/item/leather_boots_copper_trim.json
+ minecraft/models/item/leather_boots_diamond_trim.json
+ minecraft/models/item/leather_boots_emerald_trim.json
+ minecraft/models/item/leather_boots_gold_trim.json
+ minecraft/models/item/leather_boots_iron_trim.json
+ minecraft/models/item/leather_boots_lapis_trim.json
+ minecraft/models/item/leather_boots_netherite_trim.json
+ minecraft/models/item/leather_boots_quartz_trim.json
+ minecraft/models/item/leather_boots_redstone_trim.json
+ minecraft/models/item/leather_chestplate_amethyst_trim.json
+ minecraft/models/item/leather_chestplate_copper_trim.json
+ minecraft/models/item/leather_chestplate_diamond_trim.json
+ minecraft/models/item/leather_chestplate_emerald_trim.json
+ minecraft/models/item/leather_chestplate_gold_trim.json
+ minecraft/models/item/leather_chestplate_iron_trim.json
+ minecraft/models/item/leather_chestplate_lapis_trim.json
+ minecraft/models/item/leather_chestplate_netherite_trim.json
+ minecraft/models/item/leather_chestplate_quartz_trim.json
+ minecraft/models/item/leather_chestplate_redstone_trim.json
+ minecraft/models/item/leather_helmet_amethyst_trim.json
+ minecraft/models/item/leather_helmet_copper_trim.json
+ minecraft/models/item/leather_helmet_diamond_trim.json
+ minecraft/models/item/leather_helmet_emerald_trim.json
+ minecraft/models/item/leather_helmet_gold_trim.json
+ minecraft/models/item/leather_helmet_iron_trim.json
+ minecraft/models/item/leather_helmet_lapis_trim.json
+ minecraft/models/item/leather_helmet_netherite_trim.json
+ minecraft/models/item/leather_helmet_quartz_trim.json
+ minecraft/models/item/leather_helmet_redstone_trim.json
+ minecraft/models/item/leather_leggings_amethyst_trim.json
+ minecraft/models/item/leather_leggings_copper_trim.json
+ minecraft/models/item/leather_leggings_diamond_trim.json
+ minecraft/models/item/leather_leggings_emerald_trim.json
+ minecraft/models/item/leather_leggings_gold_trim.json
+ minecraft/models/item/leather_leggings_iron_trim.json
+ minecraft/models/item/leather_leggings_lapis_trim.json
+ minecraft/models/item/leather_leggings_netherite_trim.json
+ minecraft/models/item/leather_leggings_quartz_trim.json
+ minecraft/models/item/leather_leggings_redstone_trim.json
+ minecraft/models/item/netherite_boots_netherite_darker_trim.json
+ minecraft/models/item/netherite_chestplate_netherite_darker_trim.json
+ minecraft/models/item/netherite_helmet_netherite_darker_trim.json
+ minecraft/models/item/netherite_leggings_netherite_darker_trim.json
+ minecraft/textures/trims/color_palettes/diamond_darker.png
+ minecraft/textures/trims/color_palettes/gold_darker.png
+ minecraft/textures/trims/color_palettes/iron_darker.png
+ minecraft/textures/trims/color_palettes/netherite_darker.png
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
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
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
- net.minecraft.util.datafix.fixes.EntityVariantFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.FilteredBooksFix
- net.minecraft.util.datafix.fixes.FilteredSignsFix
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
+ net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
+ net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.package-info
+ net.minecraft.util.datafix.fixes.PlayerUUIDFix
- net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
+ net.minecraft.util.datafix.fixes.PoiTypeRenameFix
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
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimpleRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
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
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.package-info
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
+ net.minecraft.util.datafix.schemas.V1451_7
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
- net.minecraft.util.profiling.jfr.stats.CpuLoadStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.stats.TimeStamped
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
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.world.BossEvent
+ net.minecraft.world.BossEvent$BossBarColor
- net.minecraft.world.BossEvent$BossBarOverlay
+ net.minecraft.world.Clearable
- net.minecraft.world.CompoundContainer
+ net.minecraft.world.Container
- net.minecraft.world.ContainerHelper
+ net.minecraft.world.ContainerListener
- net.minecraft.world.Containers
+ net.minecraft.world.damagesource.BadRespawnPointDamage
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.EntityDamageSource
+ net.minecraft.world.damagesource.IndirectEntityDamageSource
+ net.minecraft.world.damagesource.package-info
- net.minecraft.world.damagesource.PointDamageSource
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
- net.minecraft.world.effect.AbsoptionMobEffect
+ net.minecraft.world.effect.AttackDamageMobEffect
- net.minecraft.world.effect.HealthBoostMobEffect
+ net.minecraft.world.effect.InstantenousMobEffect
- net.minecraft.world.effect.MobEffect
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$FactorData
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.AnimationState
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Entity
+ net.minecraft.world.entity.Entity$1
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
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
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
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
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.RiderShieldingMount
- net.minecraft.world.entity.Saddleable
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
- net.minecraft.world.entity.TraceableEntity
+ net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.WalkAnimationState
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.WorldlyContainer
- net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.data.models.ItemModelGenerators$TrimModelData +3M -2M | +1P -1P
```
```
XXX.models.model.TextureMapping +1M
```
```
XXX.network.chat.CommonComponents +1M -1M
```
```
XXX.minecraft.util.FastColor$ABGR32 +2M -1M
```
```
XXX.animal.camel.Camel +3M -1M | -1P
```
```
XXX.animal.frog.Frog +1M -2M | -2P
```
```
XXX.entity.monster.Drowned +1M
```
```
XXX.entity.projectile.Arrow +1M
```
```
XXX.entity.projectile.ThrownPotion +1M
```
```
XXX.world.item.ArmorMaterials +1M -2M | -1P
```
```
XXX.item.armortrim.ArmorTrim +5M -4M | +2P -2P
```
```
XXX.item.armortrim.TrimMaterials +2M -1M
```

</details>










































































































































































































































































































<details>
<summary>
net.minecraft.data.models.ItemModelGenerators$TrimModelData
</summary>

```diff
- Map overrideArmorMaterials()
+ Optional incompatibleArmorMaterial()
- String name(ArmorMaterial)
- void <init>(String,float,Map)
+ void <init>(String,float,Optional)
```

</details>















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping layered(ResourceLocation,ResourceLocation,ResourceLocation)
```

</details>









































































































































<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
+ MutableComponent joinForNarration(Component,Component)
- MutableComponent joinForNarration(Component[])
```

</details>



























































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.FastColor$ABGR32
</summary>

```diff
+ int bgr(int)
- int opaque(int)
- int transparent(int)
```

</details>
































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
- boolean isCamelVisuallySitting()
+ boolean isSittingDown()
- boolean isVisuallySittingDown()
- void updateWalkAnimation(float)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.frog.Frog
</summary>

```diff
+ boolean isMovingInWater()
+ boolean isMovingOnLand()
- void updateWalkAnimation(float)
```

</details>











































<details>
<summary>
net.minecraft.world.entity.monster.Drowned
</summary>

```diff
- boolean isVisuallySwimming()
```

</details>





















































































<details>
<summary>
net.minecraft.world.entity.projectile.Arrow
</summary>

```diff
- int lambda$doPostHurtEffects$0(int)
```

</details>











<details>
<summary>
net.minecraft.world.entity.projectile.ThrownPotion
</summary>

```diff
- int lambda$applySplash$1(double,int)
```

</details>
















































































<details>
<summary>
net.minecraft.world.item.ArmorMaterials
</summary>

```diff
+ boolean canHaveTrims()
+ void <init>(String,int,String,int,EnumMap,int,SoundEvent,float,float,Supplier,boolean)
- void <init>(String,int,String,int,EnumMap,int,SoundEvent,float,float,Supplier)
```

</details>

































































<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
+ ResourceLocation innerTexture()
- ResourceLocation innerTexture(ArmorMaterial)
- ResourceLocation lambda$new$2(Holder,ArmorMaterial)
+ ResourceLocation lambda$new$2(Holder,Holder)
- ResourceLocation lambda$new$4(Holder,ArmorMaterial)
+ ResourceLocation lambda$new$4(Holder,Holder)
+ ResourceLocation outerTexture()
- ResourceLocation outerTexture(ArmorMaterial)
- String getColorPaletteSuffix(ArmorMaterial)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.TrimMaterials
</summary>

```diff
- void register(BootstapContext,ResourceKey,Item,Style,float,Map)
+ void register(BootstapContext,ResourceKey,Item,Style,float,Optional)
- void register(BootstapContext,ResourceKey,Item,Style,float)
```

</details>
























































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.CommonButtons
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TabOrderedElement
- net.minecraft.client.gui.components.tabs.GridLayoutTab
- net.minecraft.client.gui.components.tabs.TabManager
- net.minecraft.client.gui.components.tabs.TabNavigationBar$Builder
- net.minecraft.client.gui.components.TextAndImageButton$Builder
- net.minecraft.client.gui.screens.inventory.tooltip.MenuTooltipPositioner
+ net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
- net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil$BlitPainter
- net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
+ net.minecraft.client.gui.screens.multiplayer.package-info
+ net.minecraft.client.gui.screens.multiplayer.Realms32bitWarningScreen
- net.minecraft.client.gui.screens.multiplayer.SafetyScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.multiplayer.WarningScreen
- net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.packs.package-info
+ net.minecraft.client.gui.screens.packs.PackSelectionModel
- net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
- net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionScreen
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
- net.minecraft.client.gui.screens.packs.TransferableSelectionList
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
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
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen
- net.minecraft.client.gui.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller
- net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller$Output
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- net.minecraft.client.gui.screens.reporting.package-info
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
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
- net.minecraft.client.gui.screens.telemetry.package-info
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget
+ net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$Content
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ net.minecraft.client.gui.screens.telemetry.TelemetryInfoScreen
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$MoreTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$1
- net.minecraft.client.gui.screens.worldselection.SwitchGrid
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$LabeledSwitch
- net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$SelectedGameMode
- net.minecraft.util.datafix.fixes.EffectDurationFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
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
- net.minecraft.util.datafix.fixes.FilteredBooksFix
+ net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GoatHornIdFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
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
+ net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.PlayerUUIDFix
+ net.minecraft.util.datafix.fixes.PoiTypeRemoveFix
- net.minecraft.util.datafix.fixes.PoiTypeRenameFix
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
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimpleRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
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
+ net.minecraft.util.datafix.schemas.package-info
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
- net.minecraft.util.datafix.schemas.V1451_7
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
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.stats.TimeStamped
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
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.damagesource.PointDamageSource
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
- net.minecraft.world.effect.MobEffectInstance$FactorData
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffects$1
+ net.minecraft.world.effect.MobEffectUtil
- net.minecraft.world.effect.package-info
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
+ net.minecraft.world.entity.AnimationState
- net.minecraft.world.entity.AreaEffectCloud
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
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.RiderShieldingMount
+ net.minecraft.world.entity.Saddleable
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
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.VariantHolder
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.LockCode
- net.minecraft.world.MenuProvider
+ net.minecraft.world.Nameable
- net.minecraft.world.SimpleContainer
+ net.minecraft.world.SimpleMenuProvider
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.systems.RenderSystem +50M -45M | +1P
```
```
XXX.mojang.realmsclient.RealmsMainScreen$CloseButton +1M -1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton +1M -1M
```
```
XXX.realmsclient.gui.RealmsWorldSlotButton +1M -1M
```
```
XXX.minecraft.client.Options +21M -16M | +4P
```
```
XXX.client.gui.GuiComponent +3M
```
```
XXX.gui.components.AbstractSliderButton -1P
```
```
XXX.gui.components.AccessibilityOnboardingTextWidget +1M -1M
```
```
XXX.gui.components.EditBox +1M -1M
```
```
XXX.gui.components.StateSwitchingButton +1M -1M
```
```
XXX.components.events.ContainerEventHandler +2M -1M
```
```
XXX.gui.screens.TitleScreen -1P
```
```
XXX.screens.advancements.AdvancementWidget -2M
```
```
XXX.screens.inventory.SmithingScreen +1M
```
```
XXX.screens.worldselection.EditGameRulesScreen +1M
```
```
XXX.screens.worldselection.EditWorldScreen +2M -5M | -1P
```
```
XXX.client.model.CamelModel +1P -2P
```
```
XXX.client.renderer.RenderStateShard +1P
```
```
XXX.data.models.ItemModelGenerators$TrimModelData +3M -2M | +1P -1P
```
```
XXX.models.model.TextureMapping +1M
```
```
XXX.network.chat.CommonComponents +1M -1M
```
```
XXX.server.commands.EffectCommands +3M
```
```
XXX.world.item.ArmorMaterial -1P
```
```
XXX.world.item.Wearable +1M
```
```
XXX.item.armortrim.TrimMaterial +3M -3M | +1P -1P
```
```
XXX.item.crafting.SmithingTrimRecipe -1M
```

</details>














































<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- float getShaderGlintAlpha()
- void _setShaderGlintAlpha(float)
+ void lambda$applyModelViewMatrix$68(Matrix4f)
- void lambda$applyModelViewMatrix$69(Matrix4f)
+ void lambda$backupProjectionMatrix$69()
- void lambda$backupProjectionMatrix$70()
+ void lambda$drawElements$32(int,int,int)
- void lambda$drawElements$33(int,int,int)
+ void lambda$getString$36(int,Consumer)
- void lambda$getString$37(int,Consumer)
+ void lambda$glBindBuffer$38(int,IntSupplier)
- void lambda$glBindBuffer$39(int,IntSupplier)
+ void lambda$glBindVertexArray$39(Supplier)
- void lambda$glBindVertexArray$40(Supplier)
+ void lambda$glDeleteBuffers$40(int)
- void lambda$glDeleteBuffers$41(int)
+ void lambda$glDeleteVertexArrays$41(int)
- void lambda$glDeleteVertexArrays$42(int)
+ void lambda$glGenBuffers$59(Consumer)
- void lambda$glGenBuffers$60(Consumer)
+ void lambda$glGenVertexArrays$60(Consumer)
- void lambda$glGenVertexArrays$61(Consumer)
+ void lambda$glUniform1$43(int,IntBuffer)
- void lambda$glUniform1$44(int,IntBuffer)
+ void lambda$glUniform1$47(int,FloatBuffer)
- void lambda$glUniform1$48(int,FloatBuffer)
+ void lambda$glUniform1i$42(int,int)
- void lambda$glUniform1i$43(int,int)
+ void lambda$glUniform2$44(int,IntBuffer)
- void lambda$glUniform2$45(int,IntBuffer)
+ void lambda$glUniform2$48(int,FloatBuffer)
- void lambda$glUniform2$49(int,FloatBuffer)
+ void lambda$glUniform3$45(int,IntBuffer)
- void lambda$glUniform3$46(int,IntBuffer)
+ void lambda$glUniform3$49(int,FloatBuffer)
- void lambda$glUniform3$50(int,FloatBuffer)
+ void lambda$glUniform4$46(int,IntBuffer)
- void lambda$glUniform4$47(int,IntBuffer)
+ void lambda$glUniform4$50(int,FloatBuffer)
- void lambda$glUniform4$51(int,FloatBuffer)
+ void lambda$glUniformMatrix2$51(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix2$52(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix3$52(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix3$53(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix4$53(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix4$54(int,boolean,FloatBuffer)
+ void lambda$lineWidth$33(float)
- void lambda$lineWidth$34(float)
+ void lambda$pixelStore$34(int,int)
- void lambda$pixelStore$35(int,int)
+ void lambda$readPixels$35(int,int,int,int,int,int,ByteBuffer)
- void lambda$readPixels$36(int,int,int,int,int,int,ByteBuffer)
+ void lambda$renderCrosshair$37(int)
- void lambda$renderCrosshair$38(int)
+ void lambda$resetTextureMatrix$67()
- void lambda$resetTextureMatrix$68()
+ void lambda$restoreProjectionMatrix$70()
- void lambda$restoreProjectionMatrix$71()
+ void lambda$setInverseViewRotationMatrix$65(Matrix3f)
- void lambda$setInverseViewRotationMatrix$66(Matrix3f)
+ void lambda$setProjectionMatrix$64(Matrix4f)
- void lambda$setProjectionMatrix$65(Matrix4f)
+ void lambda$setShader$61(Supplier)
- void lambda$setShader$62(Supplier)
+ void lambda$setShaderColor$31(float,float,float,float)
- void lambda$setShaderColor$32(float,float,float,float)
+ void lambda$setShaderFogColor$28(float,float,float,float)
- void lambda$setShaderFogColor$29(float,float,float,float)
+ void lambda$setShaderFogEnd$27(float)
- void lambda$setShaderFogEnd$28(float)
+ void lambda$setShaderFogShape$29(FogShape)
- void lambda$setShaderFogShape$30(FogShape)
+ void lambda$setShaderGameTime$71(float)
- void lambda$setShaderGameTime$72(float)
- void lambda$setShaderGlintAlpha$27(float)
+ void lambda$setShaderLights$30(Vector3f,Vector3f)
- void lambda$setShaderLights$31(Vector3f,Vector3f)
+ void lambda$setShaderTexture$62(int,ResourceLocation)
+ void lambda$setShaderTexture$63(int,int)
- void lambda$setShaderTexture$63(int,ResourceLocation)
- void lambda$setShaderTexture$64(int,int)
+ void lambda$setTextureMatrix$66(Matrix4f)
- void lambda$setTextureMatrix$67(Matrix4f)
+ void lambda$setupGui3DDiffuseLighting$58(Vector3f,Vector3f)
- void lambda$setupGui3DDiffuseLighting$59(Vector3f,Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$57(Vector3f,Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$58(Vector3f,Vector3f)
+ void lambda$setupLevelDiffuseLighting$56(Vector3f,Vector3f,Matrix4f)
- void lambda$setupLevelDiffuseLighting$57(Vector3f,Vector3f,Matrix4f)
+ void lambda$setupOverlayColor$54(IntSupplier)
- void lambda$setupOverlayColor$55(IntSupplier)
+ void lambda$teardownOverlayColor$55()
- void lambda$teardownOverlayColor$56()
- void setShaderGlintAlpha(double)
- void setShaderGlintAlpha(float)
```

</details>


























<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$CloseButton
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>

<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>

































<details>
<summary>
com.mojang.realmsclient.gui.RealmsWorldSlotButton
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>












































































































































































<details>
<summary>
net.minecraft.client.Options
</summary>

```diff
- Component lambda$new$100(Component,Integer)
- Component lambda$new$85(Component,Double)
+ Component lambda$new$85(Component,Integer)
- Component lambda$new$86(Component,Double)
- Component lambda$new$88(Component,Integer)
+ Component lambda$new$89(Component,NarratorStatus)
+ Component lambda$new$91(Component,String)
- Component lambda$new$92(Component,NarratorStatus)
- Component lambda$new$94(Component,String)
+ Component lambda$new$95(Component,Integer)
+ Component lambda$new$97(Component,Integer)
- Component lambda$new$98(Component,Integer)
+ int lambda$new$86()
- int lambda$new$89()
+ List lambda$new$92()
- List lambda$new$95()
+ Optional lambda$new$93(String)
- Optional lambda$new$96(String)
- OptionInstance glintSpeed()
- OptionInstance glintStrength()
+ String lambda$dumpOptionsForReport$100(Pair)
- String lambda$dumpOptionsForReport$103(Pair)
- void lambda$load$102(CompoundTag,String)
+ void lambda$load$99(CompoundTag,String)
- void lambda$new$101(Integer)
- void lambda$new$87(Double)
+ void lambda$new$87(Integer)
+ void lambda$new$88(ParticleStatus)
- void lambda$new$90(Integer)
+ void lambda$new$90(NarratorStatus)
- void lambda$new$91(ParticleStatus)
- void lambda$new$93(NarratorStatus)
+ void lambda$new$94(String)
+ void lambda$new$96(Integer)
- void lambda$new$97(String)
+ void lambda$new$98(Integer)
- void lambda$new$99(Integer)
```

</details>






























<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
- void blitNineSliced(PoseStack,int,int,int,int,int,int,int,int,int,int,int,int)
- void blitNineSliced(PoseStack,int,int,int,int,int,int,int,int,int)
- void blitRepeating(PoseStack,int,int,int,int,int,int,int,int)
```

</details>





<details>
<summary>
net.minecraft.client.gui.components.AccessibilityOnboardingTextWidget
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>









<details>
<summary>
net.minecraft.client.gui.components.EditBox
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>











<details>
<summary>
net.minecraft.client.gui.components.StateSwitchingButton
</summary>

```diff
+ void renderButton(PoseStack,int,int,float)
- void renderWidget(PoseStack,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.components.events.ContainerEventHandler
</summary>

```diff
- int lambda$handleTabNavigation$2(GuiEventListener)
+ Integer lambda$nextFocusPathInDirection$2(ScreenDirection,GuiEventListener)
- Integer lambda$nextFocusPathInDirection$4(ScreenDirection,GuiEventListener)
```

</details>



















































































<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementWidget
</summary>

```diff
+ void render9Sprite(PoseStack,int,int,int,int,int,int,int,int,int)
+ void renderRepeating(PoseStack,int,int,int,int,int,int,int,int)
```

</details>






































<details>
<summary>
net.minecraft.client.gui.screens.inventory.SmithingScreen
</summary>

```diff
- void updateArmorStandPreview(ItemStack)
```

</details>







<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
</summary>

```diff
- void lambda$init$2(EditGameRulesScreen,GuiEventListener)
```

</details>




<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditWorldScreen
</summary>

```diff
- boolean lambda$init$10(Path)
+ boolean lambda$init$13(Path)
+ DataResult lambda$init$9(JsonElement)
+ void lambda$init$10(DataResult$PartialResult)
+ void lambda$init$11(Button)
+ void lambda$init$12(Button)
- void lambda$init$9(Button)
```

</details>














































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.data.models.ItemModelGenerators$TrimModelData
</summary>

```diff
- Map overrideArmorMaterials()
+ Optional incompatibleArmorMaterial()
- String name(ArmorMaterial)
- void <init>(String,float,Map)
+ void <init>(String,float,Optional)
```

</details>















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping layered(ResourceLocation,ResourceLocation,ResourceLocation)
```

</details>









































































































































<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
+ MutableComponent joinForNarration(Component,Component)
- MutableComponent joinForNarration(Component[])
```

</details>































































































































































































































<details>
<summary>
net.minecraft.server.commands.EffectCommands
</summary>

```diff
- int lambda$register$10(CommandContext)
- int lambda$register$8(CommandContext)
- int lambda$register$9(CommandContext)
```

</details>
































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.item.Wearable
</summary>

```diff
- InteractionResultHolder swapWithEquipmentSlot(Item,Level,Player,InteractionHand)
```

</details>




<details>
<summary>
net.minecraft.world.item.armortrim.TrimMaterial
</summary>

```diff
- Map overrideArmorMaterials()
+ Optional incompatibleArmorMaterial()
- TrimMaterial create(String,Item,float,Component,Map)
+ TrimMaterial create(String,Item,float,Optional,Component)
- void <init>(String,Holder,float,Map,Component)
+ void <init>(String,Holder,float,Optional,Component)
```

</details>



























<details>
<summary>
net.minecraft.world.item.crafting.SmithingTrimRecipe
</summary>

```diff
+ boolean isArmorMaterialIncompatible(ItemStack,TrimMaterial)
```

</details>
</details>