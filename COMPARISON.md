## Comparison with [1.18-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre2)

- [Version data](#version-data)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.18-pre2</th><th>1.18-pre3</th></tr><tr><td>World version</td><td><code>2848</code></td><td><code>2849</code></td></tr><tr><td>Protocol version</td><td><code>1073741874</code></td><td><code>1073741875</code></td></tr></table>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.nbt.CompoundTag$2
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
- net.minecraft.nbt.TagType$StaticSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
- net.minecraft.nbt.visitors.CollectFields$WantedField
- net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
- net.minecraft.util.datafix.fixes.AbstractUUIDFix
+ net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.AdvancementsRenameFix
+ net.minecraft.util.datafix.fixes.AttributesRename
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
+ net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
- net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkProtoTickListFix
+ net.minecraft.util.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- net.minecraft.util.datafix.fixes.ChunkRenamesFix
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
- net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
+ net.minecraft.util.datafix.fixes.SavedDataUUIDFix
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.fixes.TeamDisplayNameFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ net.minecraft.util.datafix.fixes.VillagerDataFix
- net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
+ net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
- net.minecraft.util.datafix.fixes.VillagerTradeFix
+ net.minecraft.util.datafix.fixes.WallPropertyFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.PackedBitStorage
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
- net.minecraft.util.FastColor
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FileZipper
+ net.minecraft.util.FormattedCharSequence
- net.minecraft.util.FormattedCharSink
+ net.minecraft.util.FrameTimer
- net.minecraft.util.Graph
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InclusiveRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.MemoryReserve
+ net.minecraft.util.ModCheck
- net.minecraft.util.ModCheck$Confidence
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
+ net.minecraft.util.Mth
- net.minecraft.util.NativeModuleLister
+ net.minecraft.util.NativeModuleLister$NativeModuleInfo
- net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.package-info
+ net.minecraft.util.ParticleUtils
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
- net.minecraft.util.ProgressListener
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
+ net.minecraft.util.SimpleBitStorage
- net.minecraft.util.SimpleBitStorage$InitializationException
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringUtil
- net.minecraft.util.TelemetryConstants
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
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
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
- net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.VisibleForDebug
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.ZeroBitStorage
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
+ net.minecraft.world.entity.AgeableMob
- net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
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
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
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
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
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
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
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
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
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
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
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
+ net.minecraft.world.entity.animal.goat.Goat
- net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
+ net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
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
+ net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
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
+ net.minecraft.world.entity.animal.Squid$SquidFleeGoal
- net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
+ net.minecraft.world.entity.animal.TropicalFish
- net.minecraft.world.entity.animal.TropicalFish$Pattern
+ net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
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
+ net.minecraft.world.entity.AreaEffectCloud
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
+ net.minecraft.world.entity.decoration.Motive
+ net.minecraft.world.entity.decoration.package-info
- net.minecraft.world.entity.decoration.Painting
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
- net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.item.FallingBlockEntity
+ net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
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
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
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
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.Ravager$RavagerNavigation
+ net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
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
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
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
- net.minecraft.world.entity.projectile.AbstractArrow$1
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
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
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
- net.minecraft.world.food.FoodProperties$Builder
+ net.minecraft.world.food.Foods
- net.minecraft.world.food.package-info
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
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
- net.minecraft.world.inventory.ContainerSynchronizer
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
+ net.minecraft.world.item.AdventureModeCheck
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
- net.minecraft.world.item.HoneycombItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
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
- net.minecraft.world.item.package-info
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
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.Vanishable
+ net.minecraft.world.item.WaterLilyBlockItem
- net.minecraft.world.item.Wearable
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$BiomeCategory
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSource$1FeatureData
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockCollisions
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.FeatureAccess
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.EntityStorage
+ net.minecraft.world.level.chunk.storage.IOWorker
- net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
+ net.minecraft.world.level.chunk.storage.IOWorker$Priority
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
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
+ net.minecraft.world.level.dimension.DimensionDefaults
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.LevelStem
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
+ net.minecraft.world.level.gameevent.EntityPositionSource
- net.minecraft.world.level.gameevent.EntityPositionSource$Type
+ net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
- net.minecraft.world.level.gameevent.GameEvent
+ net.minecraft.world.level.gameevent.GameEventDispatcher
- net.minecraft.world.level.gameevent.GameEventDispatcher$1
+ net.minecraft.world.level.gameevent.GameEventListener
- net.minecraft.world.level.gameevent.GameEventListenerRegistrar
+ net.minecraft.world.level.gameevent.package-info
+ net.minecraft.world.level.gameevent.PositionSource
- net.minecraft.world.level.gameevent.PositionSourceType
+ net.minecraft.world.level.gameevent.vibrations.package-info
- net.minecraft.world.level.gameevent.vibrations.VibrationListener
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
- net.minecraft.world.level.gameevent.vibrations.VibrationPath
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
+ net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.Aquifer
+ net.minecraft.world.level.levelgen.Aquifer$1
- net.minecraft.world.level.levelgen.Aquifer$FluidPicker
+ net.minecraft.world.level.levelgen.Aquifer$FluidStatus
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.BelowZeroRetrogen
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
- net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Density
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
+ net.minecraft.world.level.levelgen.LegacyRandomSource
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseChunk$Sampler
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSampler
+ net.minecraft.world.level.levelgen.NoiseSampler$FlatNoiseData
- net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.NoiseSampler$VeinType
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlider
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.PositionalRandomFactory
+ net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.StructureCheck
+ net.minecraft.world.level.levelgen.StructureSettings
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
- net.minecraft.world.level.levelgen.TerrainInfo
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
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
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.LocalMobCapCalculator
- net.minecraft.world.level.LocalMobCapCalculator$MobCounts
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
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.WorldGenLevel
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
XXX.minecraft.nbt.ByteArrayTag +1M
```
```
XXX.minecraft.nbt.ByteTag +1M
```
```
XXX.minecraft.nbt.CompoundTag +1M
```
```
XXX.minecraft.nbt.LongArrayTag$1 +2M
```
```
XXX.minecraft.nbt.LongTag$1 +2M
```
```
XXX.minecraft.nbt.NbtIo +1M
```
```
XXX.minecraft.nbt.StringTag +2M
```
```
XXX.minecraft.nbt.TagType$1 +4M
```
```
XXX.server.level.ServerChunkCache +1M
```
```
XXX.server.level.ServerLevel +1M | +1P
```
```
XXX.level.chunk.CarvingMask +3M -1M | +1P
```
```
XXX.level.chunk.PalettedContainer +6M -4M
```
```
XXX.levelgen.feature.DesertPyramidFeature +2M -1M
```
```
XXX.levelgen.feature.IglooFeature +1M -1M
```
```
XXX.levelgen.feature.JunglePyramidFeature +2M -1M
```
```
XXX.levelgen.feature.OceanMonumentFeature +1M -3M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -2M
```
```
XXX.levelgen.feature.RuinedPortalFeature +3M -2M
```
```
XXX.levelgen.feature.StructureFeature +3M -3M | +1P -1P
```
```
XXX.levelgen.feature.SwamplandHutFeature +1M -1M
```
```
XXX.feature.configurations.GlowLichenConfiguration -2M
```
```
XXX.feature.structures.JigsawPlacement +2M -1M
```
```
XXX.levelgen.structure.NoiseAffectingStructureFeature +2M -2M
```
```
XXX.structure.pieces.PieceGenerator$Context +2M -6M | +1P -2P
```
```
XXX.world.ticks.ScheduledTick -1M
```

</details>























































































































































































































































































































<details>
<summary>
net.minecraft.nbt.ByteArrayTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>

<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongArrayTag$1
</summary>

```diff
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
- void skip(DataInput)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag$1
</summary>

```diff
- int size()
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
```

</details>

<details>
<summary>
net.minecraft.nbt.NbtIo
</summary>

```diff
- void parse(DataInput,StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
- void skipString(DataInput)
```

</details>


<details>
<summary>
net.minecraft.nbt.TagType$1
</summary>

```diff
- IOException createException()
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
- void skip(DataInput,int)
- void skip(DataInput)
```

</details>





































































































































































































































































<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
- ChunkScanAccess chunkScanner()
```

</details>

<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- void onStructureStartsAvailable(ChunkAccess)
```

</details>





































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.chunk.CarvingMask
</summary>

```diff
+ BlockPos lambda$stream$0(ChunkPos,int)
- BlockPos lambda$stream$1(ChunkPos,int)
- boolean lambda$new$0(int,int,int)
- void setAdditionalMask(CarvingMask$Mask)
```

</details>




<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
+ int lambda$read$4(int,Object)
+ int lambda$read$5(IdMap,Palette,SimpleBitStorage,int)
- int lambda$read$5(int,Object)
- int lambda$read$6(IdMap,Palette,SimpleBitStorage,int)
- void getAll(Consumer)
+ void lambda$count$6(Int2IntMap,int)
- void lambda$count$7(Int2IntMap,int)
+ void lambda$count$7(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$count$8(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$getAll$4(Consumer,GlobalPalette,int)
```

</details>




































<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.feature.IglooFeature
</summary>

```diff
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
</summary>

```diff
+ NoiseColumn lambda$findSuitableY$0(ChunkGenerator,LevelHeightAccessor,BlockPos)
- NoiseColumn lambda$findSuitableY$1(ChunkGenerator,LevelHeightAccessor,BlockPos)
- Optional pieceGeneratorSupplier(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,RuinedPortalConfiguration,PieceGenerator$Context)
- void lambda$pieceGeneratorSupplier$0(RuinedPortalConfiguration,RuinedPortalPiece$Properties,BlockPos,PieceGeneratorSupplier$Context,RuinedPortalPiece$VerticalPlacement,ResourceLocation,StructureTemplate,Rotation,Mirror,BlockPos,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- boolean canGenerate(RegistryAccess,ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor,Predicate)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ void <init>(Codec,PieceGenerator,PostPlacementProcessor)
+ void <init>(Codec,PieceGenerator)
- void <init>(Codec,PieceGeneratorSupplier,PostPlacementProcessor)
- void <init>(Codec,PieceGeneratorSupplier)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
</summary>

```diff
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
</summary>

```diff
+ boolean canBePlacedOn(Block)
+ boolean lambda$canBePlacedOn$7(Block,BlockState)
```

</details>

































<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
</summary>

```diff
- Optional addPieces(PieceGeneratorSupplier$Context,JigsawPlacement$PieceFactory,BlockPos,boolean,boolean)
+ void addPieces(RegistryAccess,JigsawConfiguration,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,BlockPos,StructurePieceAccessor,Random,boolean,boolean,LevelHeightAccessor,Predicate)
- void lambda$addPieces$0(PoolElementStructurePiece,JigsawConfiguration,int,int,int,Registry,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,WorldgenRandom,BoundingBox,boolean,LevelHeightAccessor,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>

























































<details>
<summary>
net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureFeature
</summary>

```diff
+ void <init>(Codec,PieceGenerator,PostPlacementProcessor)
+ void <init>(Codec,PieceGenerator)
- void <init>(Codec,PieceGeneratorSupplier,PostPlacementProcessor)
- void <init>(Codec,PieceGeneratorSupplier)
```

</details>







































<details>
<summary>
net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
</summary>

```diff
+ boolean validBiomeOnTop(Heightmap$Types)
- FeatureConfiguration config()
+ int getLowestY(int,int)
+ int[] getCornerHeights(int,int,int,int)
+ Predicate validBiome()
+ RegistryAccess registryAccess()
- void <init>(FeatureConfiguration,ChunkGenerator,StructureManager,ChunkPos,LevelHeightAccessor,WorldgenRandom,long)
+ void <init>(RegistryAccess,ChunkGenerator,StructureManager,ChunkPos,Predicate,LevelHeightAccessor,WorldgenRandom,long)
```

</details>





























































































































































































































<details>
<summary>
net.minecraft.world.ticks.ScheduledTick
</summary>

```diff
+ ScheduledTick worldgen(Object,BlockPos,long)
```

</details>



<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.nbt.CompoundTag$2
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.NbtOps
+ net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
- net.minecraft.nbt.TagType$StaticSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
- net.minecraft.nbt.visitors.CollectFields$WantedField
- net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
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
- net.minecraft.util.datafix.fixes.CavesAndCliffsRenames
+ net.minecraft.util.datafix.fixes.ChunkBedBlockEntityInjecterFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
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
+ net.minecraft.util.datafix.fixes.SavedDataFeaturePoolElementFix
- net.minecraft.util.datafix.fixes.SavedDataUUIDFix
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.SpawnerDataFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ net.minecraft.util.datafix.fixes.WriteAndReadFix
- net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
- net.minecraft.util.datafix.package-info
+ net.minecraft.util.datafix.PackedBitStorage
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
- net.minecraft.util.FastBufferedInputStream
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.Graph
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InclusiveRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.ModCheck
+ net.minecraft.util.ModCheck$Confidence
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
+ net.minecraft.util.package-info
- net.minecraft.util.ParticleUtils
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
+ net.minecraft.util.ProgressListener
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SimpleBitStorage$InitializationException
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringUtil
+ net.minecraft.util.TelemetryConstants
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
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
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
+ net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
+ net.minecraft.util.VisibleForDebug
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.util.ZeroBitStorage
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
- net.minecraft.world.damagesource.package-info
+ net.minecraft.world.Difficulty
- net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsoptionMobEffect
- net.minecraft.world.effect.AttackDamageMobEffect
+ net.minecraft.world.effect.HealthBoostMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffectCategory
+ net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffects
- net.minecraft.world.effect.MobEffects$1
- net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.package-info
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
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
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
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
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
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
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
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
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
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
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
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
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
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
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
- net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
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
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
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
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
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
- net.minecraft.world.entity.AreaEffectCloud
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
+ net.minecraft.world.entity.decoration.GlowItemFrame
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
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
+ net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
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
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
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
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
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
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
+ net.minecraft.world.InteractionHand
- net.minecraft.world.InteractionResult
+ net.minecraft.world.InteractionResultHolder
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
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
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
+ net.minecraft.world.item.package-info
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
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSource$1FeatureData
- net.minecraft.world.level.biome.BiomeSource$StepFeatureData
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.chunk.CarvingMask$Mask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkAccess$TicksToSave
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$1
- net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunk$PostLoadProcessor
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
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
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
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ net.minecraft.world.level.gameevent.vibrations.VibrationPath
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
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.BelowZeroRetrogen
- net.minecraft.world.level.levelgen.BelowZeroRetrogen$1
+ net.minecraft.world.level.levelgen.BitRandomSource
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Density
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
- net.minecraft.world.level.levelgen.LegacyRandomSource
+ net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.MarsagliaPolarGaussian
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseChunk$Sampler
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.NoiseSampler$FlatNoiseData
+ net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.NoiseSampler$VeinType
+ net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.NoiseSlider
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomSource
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
- net.minecraft.world.level.levelgen.structure.StructureCheckResult
- net.minecraft.world.level.levelgen.StructureSettings
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
+ net.minecraft.world.level.levelgen.TerrainInfo
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
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
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
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
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.WorldGenLevel
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
XXX.minecraft.client.Minecraft -1P
```
```
XXX.client.multiplayer.ClientLevel +1M
```
```
XXX.minecraft.nbt.ByteArrayTag +1M
```
```
XXX.minecraft.nbt.ByteTag +1M
```
```
XXX.minecraft.nbt.CompoundTag +1M
```
```
XXX.minecraft.nbt.LongArrayTag$1 +2M
```
```
XXX.minecraft.nbt.LongTag$1 +2M
```
```
XXX.minecraft.nbt.NbtIo +1M
```
```
XXX.minecraft.nbt.StringTag +2M
```
```
XXX.minecraft.nbt.TagType$1 +4M
```
```
XXX.minecraft.server.Bootstrap +3M
```
```
XXX.levelgen.blending.BlendingData +1M -1M
```
```
XXX.levelgen.feature.BastionFeature +1M -2M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +2M -3M
```
```
XXX.levelgen.feature.EndCityFeature +2M -3M
```
```
XXX.levelgen.feature.JigsawFeature +2M -2M
```
```
XXX.levelgen.feature.MineshaftFeature +2M -3M
```
```
XXX.levelgen.feature.NetherFortressFeature +2M -3M
```
```
XXX.levelgen.feature.ShipwreckFeature +2M -1M
```
```
XXX.levelgen.feature.StrongholdFeature +2M -3M
```
```
XXX.levelgen.feature.VillageFeature +1M
```
```
XXX.levelgen.feature.WoodlandMansionFeature +2M -1M
```
```
XXX.levelgen.placement.PlacedFeature +1M
```
```
XXX.levelgen.structure.NetherFossilFeature +2M -1M
```
```
XXX.levelgen.structure.OceanRuinFeature +1M -1M
```
```
XXX.structure.pieces.PieceGenerator +1P -1P
```
```
XXX.level.storage.LevelStorageSource$LevelStorageAccess +1M -1M
```

</details>































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- void setLightReady(int,int)
```

</details>




































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.nbt.ByteArrayTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>

<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongArrayTag$1
</summary>

```diff
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
- void skip(DataInput)
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag$1
</summary>

```diff
- int size()
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
```

</details>

<details>
<summary>
net.minecraft.nbt.NbtIo
</summary>

```diff
- void parse(DataInput,StreamTagVisitor)
```

</details>
<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
- StreamTagVisitor$ValueResult accept(StreamTagVisitor)
- void skipString(DataInput)
```

</details>


<details>
<summary>
net.minecraft.nbt.TagType$1
</summary>

```diff
- IOException createException()
- StreamTagVisitor$ValueResult parse(DataInput,StreamTagVisitor)
- void skip(DataInput,int)
- void skip(DataInput)
```

</details>











































































































































































<details>
<summary>
net.minecraft.server.Bootstrap
</summary>

```diff
- void lambda$validateThatAllBiomeFeaturesHaveBiomeFilter$4(Supplier)
- void lambda$validateThatAllBiomeFeaturesHaveBiomeFilter$5(Biome)
- void validateThatAllBiomeFeaturesHaveBiomeFilter()
```

</details>


















































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.blending.BlendingData
</summary>

```diff
+ Set getSidesWithNewGen(WorldGenRegion,int,int)
- Set sideByGenerationAge(WorldGenLevel,int,int,boolean)
```

</details>


















<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,JigsawConfiguration,LevelHeightAccessor)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,ProbabilityFeatureConfiguration,LevelHeightAccessor)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
+ void generatePieces(StructurePiecesBuilder,ProbabilityFeatureConfiguration,PieceGenerator$Context)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature
</summary>

```diff
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
- Optional pieceGeneratorSupplier(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void lambda$pieceGeneratorSupplier$0(BlockPos,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
- Optional lambda$new$0(Predicate,int,boolean,boolean,PieceGeneratorSupplier$Context)
- void <init>(Codec,int,boolean,boolean,Predicate)
+ void <init>(Codec,int,boolean,boolean)
+ void lambda$new$0(int,boolean,boolean,StructurePiecesBuilder,JigsawConfiguration,PieceGenerator$Context)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.MineshaftFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,MineshaftConfiguration,LevelHeightAccessor)
+ void generatePieces(StructurePiecesBuilder,MineshaftConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
+ void generatePieces(StructurePiecesBuilder,ShipwreckConfiguration,PieceGenerator$Context)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature
</summary>

```diff
- boolean checkLocation(PieceGeneratorSupplier$Context)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,FeatureConfiguration,LevelHeightAccessor)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,ChunkPos,NoneFeatureConfiguration,LevelHeightAccessor)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.VillageFeature
</summary>

```diff
- boolean lambda$new$0(PieceGeneratorSupplier$Context)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
</summary>

```diff
- Optional pieceGeneratorSupplier(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,NoneFeatureConfiguration,PieceGenerator$Context)
- void lambda$pieceGeneratorSupplier$0(BlockPos,Rotation,WorldgenRandom,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>





































































<details>
<summary>
net.minecraft.world.level.levelgen.placement.PlacedFeature
</summary>

```diff
- List getPlacement()
```

</details>


























<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature
</summary>

```diff
- Optional pieceGeneratorSupplier(PieceGeneratorSupplier$Context)
+ void generatePieces(StructurePiecesBuilder,RangeConfiguration,PieceGenerator$Context)
- void lambda$pieceGeneratorSupplier$0(PieceGeneratorSupplier$Context,WorldgenRandom,BlockPos,StructurePiecesBuilder,PieceGenerator$Context)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature
</summary>

```diff
+ void generatePieces(StructurePiecesBuilder,OceanRuinConfiguration,PieceGenerator$Context)
- void generatePieces(StructurePiecesBuilder,PieceGenerator$Context)
```

</details>




























































































<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
</summary>

```diff
+ File getDimensionPath(ResourceKey)
- Path getDimensionPath(ResourceKey)
```

</details>
</details>