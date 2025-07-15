## Comparison with [23w04a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w04a)

> [!TIP]
> - [Version data](#version-data)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w04a</th><th>23w05a</th></tr><tr><td>World version</td><td><pre>3321</pre></td><td><pre>3323</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741940</pre></td><td><pre>1073741941</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
effect
</summary>

```diff
+ effect give <targets: entity> <effect: resource> infinite <amplifier: integer> <hideParticles: bool>
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
<br/>
<table>
<tr><th>Name</th><th>23w04a</th><th>23w05a</th></tr>
<tr><th align="left"><div style="width:290px">item.minecraft.smithing_template.netherite_upgrade.additions_slot_description</div></th><td>Put Netherite Ingot here</td><td>Put a Netherite Ingot here</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingFieldsRenameFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntityShulkerRotationFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimpleRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VariantRenameFix
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V501
+ XXX.datafix.schemas.V700
- XXX.datafix.schemas.V701
+ XXX.datafix.schemas.V702
- XXX.datafix.schemas.V703
+ XXX.datafix.schemas.V704
- XXX.datafix.schemas.V704$1
+ XXX.datafix.schemas.V705
- XXX.datafix.schemas.V705$1
+ XXX.datafix.schemas.V808
- XXX.datafix.schemas.V99
+ XXX.datafix.schemas.V99$1
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.NetworkPacketSummary
+ XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.jfr.stats.TimeStamped
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
+ XXX.minecraft.util.package-info
- XXX.minecraft.world.BossEvent
+ XXX.minecraft.world.BossEvent$BossBarColor
- XXX.minecraft.world.BossEvent$BossBarOverlay
+ XXX.minecraft.world.Clearable
- XXX.minecraft.world.CompoundContainer
+ XXX.minecraft.world.Container
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
+ XXX.util.datafix.package-info
+ XXX.util.eventlog.EventLogDirectory
- XXX.util.eventlog.EventLogDirectory$CompressedFile
+ XXX.util.eventlog.EventLogDirectory$File
- XXX.util.eventlog.EventLogDirectory$FileId
+ XXX.util.eventlog.EventLogDirectory$FileList
- XXX.util.eventlog.EventLogDirectory$RawFile
+ XXX.util.eventlog.JsonEventLog
- XXX.util.eventlog.JsonEventLog$1
+ XXX.util.eventlog.JsonEventLogReader
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.util.eventlog.package-info
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
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
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.world.damagesource.BadRespawnPointDamage
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.EntityDamageSource
+ XXX.world.damagesource.IndirectEntityDamageSource
+ XXX.world.damagesource.package-info
- XXX.world.damagesource.PointDamageSource
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$FactorData
+ XXX.world.effect.MobEffects
- XXX.world.effect.MobEffects$1
- XXX.world.effect.MobEffectUtil
+ XXX.world.effect.package-info
- XXX.world.entity.AgeableMob
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
- XXX.world.entity.AnimationState
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MobType
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.RelativeMovement
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.RiderShieldingMount
- XXX.world.entity.Saddleable
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.TraceableEntity
+ XXX.world.entity.VariantHolder
- XXX.world.entity.WalkAnimationState
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar$Builder
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingFieldsRenameFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.SavedDataVillageCropFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimpleRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WeaponSmithChestLootTableFix
+ XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_6$1
+ XXX.datafix.schemas.V1451_6$2
- XXX.datafix.schemas.V1451_7
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V2571
+ XXX.datafix.schemas.V2684
- XXX.datafix.schemas.V2686
+ XXX.datafix.schemas.V2688
- XXX.datafix.schemas.V2704
+ XXX.datafix.schemas.V2707
- XXX.datafix.schemas.V2831
+ XXX.datafix.schemas.V2832
- XXX.datafix.schemas.V2842
+ XXX.datafix.schemas.V3076
- XXX.datafix.schemas.V3078
+ XXX.datafix.schemas.V3081
- XXX.datafix.schemas.V3082
+ XXX.datafix.schemas.V3083
- XXX.datafix.schemas.V3202
+ XXX.datafix.schemas.V3203
- XXX.datafix.schemas.V3204
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
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.CommonButtons
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabOrderedElement
- XXX.gui.components.TextAndImageButton$Builder
- XXX.gui.screens.package-info
- XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipRenderUtil
- XXX.inventory.tooltip.TooltipRenderUtil$BlitPainter
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.NetworkPacketSummary
- XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
- XXX.jfr.stats.package-info
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
+ XXX.jfr.stats.TimeStamped
- XXX.metrics.profiling.ActiveMetricsRecorder
+ XXX.metrics.profiling.InactiveMetricsRecorder
- XXX.metrics.profiling.MetricsRecorder
+ XXX.metrics.profiling.package-info
+ XXX.metrics.profiling.ProfilerSamplerAdapter
- XXX.metrics.profiling.ServerMetricsSamplersProvider
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$1
- XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- XXX.metrics.storage.MetricsPersister
- XXX.metrics.storage.package-info
+ XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.util.package-info
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
- XXX.minecraft.world.SimpleContainer
+ XXX.minecraft.world.SimpleMenuProvider
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
+ XXX.profiling.metrics.MetricCategory
- XXX.profiling.metrics.MetricSampler
+ XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metrics.MetricSampler$SamplerResult
+ XXX.profiling.metrics.MetricSampler$ThresholdTest
- XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ XXX.profiling.metrics.MetricsRegistry
- XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ XXX.profiling.metrics.MetricsSamplerProvider
+ XXX.profiling.metrics.package-info
- XXX.profiling.metrics.ProfilerMeasured
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.Realms32bitWarningScreen
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$Entry
+ XXX.screens.multiplayer.ServerSelectionList$LANHeader
- XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.multiplayer.WarningScreen
- XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel
- XXX.screens.packs.PackSelectionModel$Entry
+ XXX.screens.packs.PackSelectionModel$EntryBase
- XXX.screens.packs.PackSelectionModel$SelectedPackEntry
+ XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
- XXX.screens.packs.PackSelectionScreen
+ XXX.screens.packs.PackSelectionScreen$Watcher
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
+ XXX.screens.reporting.ChatReportScreen
- XXX.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ XXX.screens.reporting.ChatSelectionLogFiller
- XXX.screens.reporting.ChatSelectionLogFiller$Output
+ XXX.screens.reporting.ChatSelectionScreen
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- XXX.screens.reporting.package-info
+ XXX.screens.reporting.ReportReasonSelectionScreen
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerEntry$3
+ XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsPlayerList
+ XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$1
+ XXX.screens.social.SocialInteractionsScreen$2
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.screens.telemetry.package-info
- XXX.screens.telemetry.TelemetryEventWidget
+ XXX.screens.telemetry.TelemetryEventWidget$Content
- XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ XXX.screens.telemetry.TelemetryInfoScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
- XXX.screens.worldselection.SwitchGrid
- XXX.screens.worldselection.SwitchGrid$LabeledSwitch
- XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
- XXX.util.datafix.package-info
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.random.package-info
- XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.SimpleWeightedRandomList$Builder
- XXX.util.random.Weight
+ XXX.util.random.WeightedEntry
- XXX.util.random.WeightedEntry$IntrusiveBase
+ XXX.util.random.WeightedEntry$Wrapper
- XXX.util.random.WeightedRandom
+ XXX.util.random.WeightedRandomList
+ XXX.util.thread.BlockableEventLoop
- XXX.util.thread.NamedThreadFactory
+ XXX.util.thread.package-info
+ XXX.util.thread.ProcessorHandle
- XXX.util.thread.ProcessorHandle$1
+ XXX.util.thread.ProcessorMailbox
- XXX.util.thread.ReentrantBlockableEventLoop
+ XXX.util.thread.StrictQueue
- XXX.util.thread.StrictQueue$FixedPriorityQueue
+ XXX.util.thread.StrictQueue$IntRunnable
- XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.BiasedToBottomInt
+ XXX.util.valueproviders.ClampedInt
- XXX.util.valueproviders.ClampedNormalFloat
+ XXX.util.valueproviders.ClampedNormalInt
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
- XXX.util.valueproviders.MultipliedFloats
- XXX.util.valueproviders.package-info
+ XXX.util.valueproviders.SampledFloat
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.world.damagesource.BadRespawnPointDamage
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.EntityDamageSource
- XXX.world.damagesource.IndirectEntityDamageSource
- XXX.world.damagesource.package-info
+ XXX.world.damagesource.PointDamageSource
+ XXX.world.effect.AbsoptionMobEffect
- XXX.world.effect.AttackDamageMobEffect
+ XXX.world.effect.HealthBoostMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffectCategory
+ XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffectInstance$FactorData
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Entity
- XXX.world.entity.Entity$1
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LerpingModel
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.RelativeMovement
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.RiderShieldingMount
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
+ XXX.world.entity.TraceableEntity
- XXX.world.entity.VariantHolder
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
<hr/>