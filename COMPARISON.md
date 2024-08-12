## Comparison with [22w06a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w06a)

- [Version data](#version-data)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">22w06a</th><th>22w07a</th></tr><tr><td>World version</td><td><code>2968</code></td><td><code>2969</code></td></tr><tr><td>Protocol version</td><td><code>1073741891</code></td><td><code>1073741892</code></td></tr></table>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/worldgen/biome/has_structure/bastion_remnant.json
+ minecraft/tags/worldgen/biome/has_structure/buried_treasure.json
+ minecraft/tags/worldgen/biome/has_structure/desert_pyramid.json
+ minecraft/tags/worldgen/biome/has_structure/end_city.json
+ minecraft/tags/worldgen/biome/has_structure/igloo.json
+ minecraft/tags/worldgen/biome/has_structure/jungle_temple.json
+ minecraft/tags/worldgen/biome/has_structure/mineshaft_mesa.json
+ minecraft/tags/worldgen/biome/has_structure/mineshaft.json
+ minecraft/tags/worldgen/biome/has_structure/nether_fortress.json
+ minecraft/tags/worldgen/biome/has_structure/nether_fossil.json
+ minecraft/tags/worldgen/biome/has_structure/ocean_monument.json
+ minecraft/tags/worldgen/biome/has_structure/ocean_ruin_cold.json
+ minecraft/tags/worldgen/biome/has_structure/ocean_ruin_warm.json
+ minecraft/tags/worldgen/biome/has_structure/pillager_outpost.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_desert.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_jungle.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_mountain.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_nether.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_ocean.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_standard.json
+ minecraft/tags/worldgen/biome/has_structure/ruined_portal_swamp.json
+ minecraft/tags/worldgen/biome/has_structure/shipwreck_beached.json
+ minecraft/tags/worldgen/biome/has_structure/shipwreck.json
+ minecraft/tags/worldgen/biome/has_structure/stronghold.json
+ minecraft/tags/worldgen/biome/has_structure/swamp_hut.json
+ minecraft/tags/worldgen/biome/has_structure/village_desert.json
+ minecraft/tags/worldgen/biome/has_structure/village_plains.json
+ minecraft/tags/worldgen/biome/has_structure/village_savanna.json
+ minecraft/tags/worldgen/biome/has_structure/village_snowy.json
+ minecraft/tags/worldgen/biome/has_structure/village_taiga.json
+ minecraft/tags/worldgen/biome/has_structure/woodland_mansion.json
+ minecraft/tags/worldgen/biome/is_badlands.json
+ minecraft/tags/worldgen/biome/is_beach.json
+ minecraft/tags/worldgen/biome/is_deep_ocean.json
+ minecraft/tags/worldgen/biome/is_forest.json
+ minecraft/tags/worldgen/biome/is_hill.json
+ minecraft/tags/worldgen/biome/is_jungle.json
+ minecraft/tags/worldgen/biome/is_mountain.json
+ minecraft/tags/worldgen/biome/is_nether.json
+ minecraft/tags/worldgen/biome/is_ocean.json
+ minecraft/tags/worldgen/biome/is_river.json
+ minecraft/tags/worldgen/biome/is_taiga.json
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
- net.minecraft.data.tags.BiomeTagsProvider
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.GameEventTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.data.worldgen.BastionBridgePools
- net.minecraft.data.worldgen.BastionHoglinStablePools
+ net.minecraft.data.worldgen.BastionHousingUnitsPools
- net.minecraft.data.worldgen.BastionPieces
+ net.minecraft.data.worldgen.BastionSharedPools
- net.minecraft.data.worldgen.BastionTreasureRoomPools
+ net.minecraft.data.worldgen.BiomeDefaultFeatures
- net.minecraft.data.worldgen.Carvers
+ net.minecraft.data.worldgen.DesertVillagePools
- net.minecraft.data.worldgen.NoiseData
+ net.minecraft.data.worldgen.PillagerOutpostPools
- net.minecraft.data.worldgen.PlainVillagePools
+ net.minecraft.data.worldgen.Pools
- net.minecraft.data.worldgen.ProcessorLists
+ net.minecraft.data.worldgen.SavannaVillagePools
- net.minecraft.data.worldgen.SnowyVillagePools
+ net.minecraft.data.worldgen.StructureFeatures
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoadResult
+ net.minecraft.tags.TagNetworkSerialization
- net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.CubicSpline
+ net.minecraft.util.CubicSpline$1Point
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.CubicSpline$Multipoint
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
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- net.minecraft.util.ExtraCodecs$2
+ net.minecraft.util.ExtraCodecs$3
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$LazyInitializedCodec
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastBufferedInputStream
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
+ net.minecraft.util.Mth
- net.minecraft.util.NativeModuleLister
+ net.minecraft.util.NativeModuleLister$NativeModuleInfo
- net.minecraft.util.NativeModuleLister$NativeModuleVersion
+ net.minecraft.util.ParticleUtils
- net.minecraft.util.ProgressListener
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
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
- net.minecraft.world.level.levelgen.DensityFunctions$1
- net.minecraft.world.level.levelgen.DensityFunctions$Ap2$Type
- net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
- net.minecraft.world.level.levelgen.DensityFunctions$Clamp
- net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
- net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
- net.minecraft.world.level.levelgen.DensityFunctions$Shift0
- net.minecraft.world.level.levelgen.DensityFunctions$Shift2
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
- net.minecraft.world.level.levelgen.DensityFunctions$TerrainShaperSpline
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
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
+ net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RangeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
- net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
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
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StructurePieceType$ContextlessType
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
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
- net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Sampler
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseSampler
+ net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.structure.pieces.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
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
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.HolderSet$Named +2M -1M | +1P
```
```
XXX.minecraft.core.Registry +2M -2M
```
```
XXX.world.inventory.AbstractContainerMenu +2M | +1P
```
```
XXX.world.level.Level -1M
```
```
XXX.level.biome.BiomeSource +2M -2M
```
```
XXX.level.biome.Climate$Sampler +12M | +7P -1P
```
```
XXX.level.chunk.UpgradeData +12M -1M | +2P
```
```
XXX.level.levelgen.Aquifer +1M -1M | +1P -1P
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer +3M -4M | +4P -4P
```
```
XXX.level.levelgen.NoiseSlider +7M -1M
```
```
XXX.levelgen.feature.ConfiguredStructureFeature +2M -1M | +1P
```
```
XXX.levelgen.feature.StructureFeature +4M -3M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +2M -2M
```
```
XXX.levelgen.structure.ScatteredFeaturePiece +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$StairsDown +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$Turn +2M -2M
```
```
XXX.levelgen.structure.StructurePiece +3M -3M | +1P -1P
```
```
XXX.levelgen.structure.TemplateStructurePiece +2M -2M
```
```
XXX.levelgen.synth.NormalNoise +1M | +1P
```
```
XXX.levelgen.synth.PerlinNoise +3M | +1P
```
```
XXX.world.ticks.SavedTick +3M -1M
```

</details>



















































































































































































<details>
<summary>
net.minecraft.core.HolderSet$Named
</summary>

```diff
- boolean isValidInRegistry(Registry)
- void <init>(Registry,TagKey)
+ void <init>(TagKey)
```

</details>



<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ StructurePieceType lambda$static$43(Registry)
- StructurePieceType lambda$static$43(Registry)
+ StructurePoolElementType lambda$static$53(Registry)
- StructurePoolElementType lambda$static$53(Registry)
```

</details>






















































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
- boolean isValidSlotIndex(int)
- void <clinit>()
```

</details>























































































































































































<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean shouldDelayFallingBlockEntityRemoval(Entity$RemovalReason)
```

</details>






















<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
- Set possibleBiomes()
+ Stream possibleBiomes()
- void addDebugInfo(List,BlockPos,Climate$Sampler)
+ void addMultinoiseDebugInfo(List,BlockPos,Climate$Sampler)
```

</details>









<details>
<summary>
net.minecraft.world.level.biome.Climate$Sampler
</summary>

```diff
- boolean equals(Object)
- Climate$TargetPoint sample(int,int,int)
- DensityFunction continentalness()
- DensityFunction depth()
- DensityFunction erosion()
- DensityFunction humidity()
- DensityFunction temperature()
- DensityFunction weirdness()
- int hashCode()
- List spawnTarget()
- String toString()
- void <init>(DensityFunction,DensityFunction,DensityFunction,DensityFunction,DensityFunction,DensityFunction,List)
```

</details>












































































































































































































































































<details>
<summary>
net.minecraft.world.level.chunk.UpgradeData
</summary>

```diff
- Optional lambda$new$0()
- Optional lambda$new$1(String)
- Optional lambda$new$2()
- Optional lambda$new$3(String)
- String lambda$write$7(Block)
- String lambda$write$9(Fluid)
+ void lambda$upgrade$0(Level,UpgradeData$BlockFixer)
- void lambda$upgrade$4(Level,SavedTick)
- void lambda$upgrade$5(Level,SavedTick)
- void lambda$upgrade$6(Level,UpgradeData$BlockFixer)
- void lambda$write$10(ListTag,SavedTick)
- void lambda$write$8(ListTag,SavedTick)
- void loadTicks(CompoundTag,String,Function,List)
```

</details>





































<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- Aquifer create(NoiseChunk,ChunkPos,DensityFunction,DensityFunction,DensityFunction,DensityFunction,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
</summary>

```diff
- BlockState computeSubstance(DensityFunction$FunctionContext,double)
+ BlockState computeSubstance(int,int,int,double,double)
+ BlockState getFluidType(int,int,int,Aquifer$FluidStatus,int)
- double calculatePressure(DensityFunction$FunctionContext,MutableDouble,Aquifer$FluidStatus,Aquifer$FluidStatus)
+ double calculatePressure(int,int,int,MutableDouble,Aquifer$FluidStatus,Aquifer$FluidStatus)
- void <init>(NoiseChunk,ChunkPos,DensityFunction,DensityFunction,DensityFunction,DensityFunction,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSlider
</summary>

```diff
- boolean equals(Object)
- double applySlide(double,double)
+ double applySlide(double,int)
- double target()
- int hashCode()
- int offset()
- int size()
- String toString()
```

</details>


















































<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
</summary>

```diff
- HolderSet biomes()
- void <init>(StructureFeature,FeatureConfiguration,HolderSet)
+ void <init>(StructureFeature,FeatureConfiguration)
```

</details>




































<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- App lambda$new$2(Codec,RecordCodecBuilder$Instance)
- ConfiguredStructureFeature configured(FeatureConfiguration,TagKey)
+ ConfiguredStructureFeature configured(FeatureConfiguration)
+ ConfiguredStructureFeature lambda$new$0(FeatureConfiguration)
- ConfiguredStructureFeature lambda$new$1(FeatureConfiguration,HolderSet)
- FeatureConfiguration lambda$new$0(ConfiguredStructureFeature)
+ FeatureConfiguration lambda$new$1(ConfiguredStructureFeature)
```

</details>








































<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
- void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
```

</details>





























<details>
<summary>
net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,int,int,int,int,int,Direction)
- void <init>(StructurePieceType,int,int,int,int,int,int,Direction)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,int,int,Direction)
- void <init>(StructurePieceType,int,int,int,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructurePiece
</summary>

```diff
+ StructurePieceType getType()
- StructurePieceType getType()
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag,StructureManager,Function)
- void <init>(StructurePieceType,CompoundTag,StructureManager,Function)
+ void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
- void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.synth.NormalNoise
</summary>

```diff
- double maxValue()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.PerlinNoise
</summary>

```diff
- double edgeValue(double)
- double maxBrokenValue(double)
- double maxValue()
```

</details>





































































































































































































<details>
<summary>
net.minecraft.world.ticks.SavedTick
</summary>

```diff
- Optional loadTick(CompoundTag,Function)
- SavedTick lambda$loadTick$1(CompoundTag,Object)
+ void lambda$loadTickList$0(CompoundTag,long,Consumer,Object)
- void lambda$loadTickList$0(long,Consumer,SavedTick)
```

</details>




<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.GameEventTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.data.worldgen.BastionBridgePools
+ net.minecraft.data.worldgen.BastionHoglinStablePools
- net.minecraft.data.worldgen.BastionHousingUnitsPools
+ net.minecraft.data.worldgen.BastionPieces
- net.minecraft.data.worldgen.BastionSharedPools
+ net.minecraft.data.worldgen.BastionTreasureRoomPools
- net.minecraft.data.worldgen.BiomeDefaultFeatures
+ net.minecraft.data.worldgen.Carvers
- net.minecraft.data.worldgen.DesertVillagePools
+ net.minecraft.data.worldgen.NoiseData
- net.minecraft.data.worldgen.PillagerOutpostPools
+ net.minecraft.data.worldgen.PlainVillagePools
- net.minecraft.data.worldgen.Pools
+ net.minecraft.data.worldgen.ProcessorLists
- net.minecraft.data.worldgen.SavannaVillagePools
+ net.minecraft.data.worldgen.SnowyVillagePools
- net.minecraft.data.worldgen.StructureFeatures
+ net.minecraft.data.worldgen.StructureFeatures$StructureConfigConsumer
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
- net.minecraft.tags.package-info
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$BuilderEntry
- net.minecraft.tags.Tag$ElementEntry
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagKey
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoadResult
+ net.minecraft.tags.TagNetworkSerialization
- net.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ net.minecraft.tags.TagNetworkSerialization$TagOutput
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CryptException
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.CubicSampler
+ net.minecraft.util.CubicSampler$Vec3Fetcher
- net.minecraft.util.CubicSpline
+ net.minecraft.util.CubicSpline$1Point
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.CubicSpline$Multipoint
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
- net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.PackedBitStorage
+ net.minecraft.util.DebugBuffer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.ExtraCodecs
- net.minecraft.util.ExtraCodecs$1
+ net.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- net.minecraft.util.ExtraCodecs$2
+ net.minecraft.util.ExtraCodecs$3
- net.minecraft.util.ExtraCodecs$EitherCodec
+ net.minecraft.util.ExtraCodecs$LazyInitializedCodec
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastBufferedInputStream
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
+ net.minecraft.util.Mth
- net.minecraft.util.NativeModuleLister
+ net.minecraft.util.NativeModuleLister$NativeModuleInfo
- net.minecraft.util.NativeModuleLister$NativeModuleVersion
+ net.minecraft.util.ParticleUtils
- net.minecraft.util.ProgressListener
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
+ net.minecraft.util.ThreadingDetector
- net.minecraft.util.TimeUtil
+ net.minecraft.util.ToFloatFunction
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.DensityFunction$ContextProvider
- net.minecraft.world.level.levelgen.DensityFunction$SimpleFunction
- net.minecraft.world.level.levelgen.DensityFunction$Visitor
- net.minecraft.world.level.levelgen.DensityFunctions$1
- net.minecraft.world.level.levelgen.DensityFunctions$Ap2$Type
- net.minecraft.world.level.levelgen.DensityFunctions$BlendDensity
- net.minecraft.world.level.levelgen.DensityFunctions$Clamp
- net.minecraft.world.level.levelgen.DensityFunctions$EndIslandDensityFunction
- net.minecraft.world.level.levelgen.DensityFunctions$Mapped$Type
- net.minecraft.world.level.levelgen.DensityFunctions$Marker$Type
- net.minecraft.world.level.levelgen.DensityFunctions$MulOrAdd$Type
- net.minecraft.world.level.levelgen.DensityFunctions$PureTransformer
- net.minecraft.world.level.levelgen.DensityFunctions$Shift0
- net.minecraft.world.level.levelgen.DensityFunctions$Shift2
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftB
- net.minecraft.world.level.levelgen.DensityFunctions$ShiftedNoise
- net.minecraft.world.level.levelgen.DensityFunctions$TerrainShaperSpline
- net.minecraft.world.level.levelgen.DensityFunctions$WeirdScaledSampler
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
+ net.minecraft.world.level.levelgen.feature.configurations.GlowLichenConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RangeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
- net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
+ net.minecraft.world.level.levelgen.feature.featuresize.package-info
+ net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
- net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
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
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.StructurePieceType$ContextlessType
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
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
- net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Sampler
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseSampler
+ net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.structure.pieces.package-info
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
- net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
- net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
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
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.realmsclient.gui.RealmsDataFetcher +1M -1M
```
```
XXX.minecraft.core.HolderSet +1P
```
```
XXX.minecraft.core.HolderSet$ListBacked +1M
```
```
XXX.minecraft.core.MappedRegistry +10M -7M | +2P -1P
```
```
XXX.data.info.RegistryDumpReport +2M -1M
```
```
XXX.world.inventory.AbstractContainerMenu +2M | +1P
```
```
XXX.world.level.Level -1M
```
```
XXX.level.biome.BiomeSource +2M -2M
```
```
XXX.level.biome.Climate$Sampler +12M | +7P -1P
```
```
XXX.level.chunk.UpgradeData +12M -1M | +2P
```
```
XXX.level.levelgen.Aquifer +1M -1M | +1P -1P
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer +3M -4M | +4P -4P
```
```
XXX.level.levelgen.NoiseSlider +7M -1M
```
```
XXX.levelgen.feature.ConfiguredStructureFeature +2M -1M | +1P
```
```
XXX.levelgen.feature.StructureFeature +4M -3M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +2M -2M
```
```
XXX.levelgen.structure.ScatteredFeaturePiece +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$StairsDown +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$StrongholdPiece +2M -2M
```
```
XXX.levelgen.structure.StrongholdPieces$Turn +2M -2M
```
```
XXX.levelgen.structure.StructurePiece +3M -3M | +1P -1P
```
```
XXX.levelgen.structure.TemplateStructurePiece +2M -2M
```
```
XXX.levelgen.synth.NormalNoise +1M | +1P
```
```
XXX.levelgen.synth.PerlinNoise +3M | +1P
```
```
XXX.world.ticks.SavedTick +3M -1M
```

</details>












































































































<details>
<summary>
com.mojang.realmsclient.gui.RealmsDataFetcher
</summary>

```diff
- List removeItem(RealmsServer)
+ void removeItem(RealmsServer)
```

</details>






















































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.core.HolderSet$ListBacked
</summary>

```diff
- boolean isValidInRegistry(Registry)
```

</details>

<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
- boolean lambda$freeze$4(Map$Entry)
- boolean lambda$freeze$5(Holder$Reference)
+ boolean lambda$freeze$5(Map$Entry)
+ boolean lambda$freeze$6(Holder$Reference)
- Holder$Reference lambda$createIntrusiveHolder$6(Object)
+ Holder$Reference lambda$createIntrusiveHolder$7(Object)
- HolderSet$Named createTag(TagKey)
- List holdersInOrder()
- Pair lambda$getTags$3(Map$Entry)
+ Pair lambda$getTags$4(Map$Entry)
- String lambda$bindTags$9(TagKey)
- void <clinit>()
- void lambda$bindTags$7(Map,Holder$Reference)
+ void lambda$bindTags$8(Map,Holder$Reference)
- void lambda$bindTags$8(Map,TagKey,List)
+ void lambda$bindTags$9(Map,TagKey,List)
+ void lambda$iterator$3(Holder$Reference,Consumer)
```

</details>


















































<details>
<summary>
net.minecraft.data.info.RegistryDumpReport
</summary>

```diff
- void lambda$dumpRegistry$1(Registry,JsonObject,Holder$Reference)
- void lambda$run$0(JsonObject,Holder$Reference)
+ void lambda$run$0(JsonObject,ResourceLocation)
```

</details>










































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
- boolean isValidSlotIndex(int)
- void <clinit>()
```

</details>























































































































































































<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean shouldDelayFallingBlockEntityRemoval(Entity$RemovalReason)
```

</details>






















<details>
<summary>
net.minecraft.world.level.biome.BiomeSource
</summary>

```diff
- Set possibleBiomes()
+ Stream possibleBiomes()
- void addDebugInfo(List,BlockPos,Climate$Sampler)
+ void addMultinoiseDebugInfo(List,BlockPos,Climate$Sampler)
```

</details>









<details>
<summary>
net.minecraft.world.level.biome.Climate$Sampler
</summary>

```diff
- boolean equals(Object)
- Climate$TargetPoint sample(int,int,int)
- DensityFunction continentalness()
- DensityFunction depth()
- DensityFunction erosion()
- DensityFunction humidity()
- DensityFunction temperature()
- DensityFunction weirdness()
- int hashCode()
- List spawnTarget()
- String toString()
- void <init>(DensityFunction,DensityFunction,DensityFunction,DensityFunction,DensityFunction,DensityFunction,List)
```

</details>












































































































































































































































































<details>
<summary>
net.minecraft.world.level.chunk.UpgradeData
</summary>

```diff
- Optional lambda$new$0()
- Optional lambda$new$1(String)
- Optional lambda$new$2()
- Optional lambda$new$3(String)
- String lambda$write$7(Block)
- String lambda$write$9(Fluid)
+ void lambda$upgrade$0(Level,UpgradeData$BlockFixer)
- void lambda$upgrade$4(Level,SavedTick)
- void lambda$upgrade$5(Level,SavedTick)
- void lambda$upgrade$6(Level,UpgradeData$BlockFixer)
- void lambda$write$10(ListTag,SavedTick)
- void lambda$write$8(ListTag,SavedTick)
- void loadTicks(CompoundTag,String,Function,List)
```

</details>





































<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- Aquifer create(NoiseChunk,ChunkPos,DensityFunction,DensityFunction,DensityFunction,DensityFunction,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
</summary>

```diff
- BlockState computeSubstance(DensityFunction$FunctionContext,double)
+ BlockState computeSubstance(int,int,int,double,double)
+ BlockState getFluidType(int,int,int,Aquifer$FluidStatus,int)
- double calculatePressure(DensityFunction$FunctionContext,MutableDouble,Aquifer$FluidStatus,Aquifer$FluidStatus)
+ double calculatePressure(int,int,int,MutableDouble,Aquifer$FluidStatus,Aquifer$FluidStatus)
- void <init>(NoiseChunk,ChunkPos,DensityFunction,DensityFunction,DensityFunction,DensityFunction,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSlider
</summary>

```diff
- boolean equals(Object)
- double applySlide(double,double)
+ double applySlide(double,int)
- double target()
- int hashCode()
- int offset()
- int size()
- String toString()
```

</details>


















































<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
</summary>

```diff
- HolderSet biomes()
- void <init>(StructureFeature,FeatureConfiguration,HolderSet)
+ void <init>(StructureFeature,FeatureConfiguration)
```

</details>




































<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- App lambda$new$2(Codec,RecordCodecBuilder$Instance)
- ConfiguredStructureFeature configured(FeatureConfiguration,TagKey)
+ ConfiguredStructureFeature configured(FeatureConfiguration)
+ ConfiguredStructureFeature lambda$new$0(FeatureConfiguration)
- ConfiguredStructureFeature lambda$new$1(FeatureConfiguration,HolderSet)
- FeatureConfiguration lambda$new$0(ConfiguredStructureFeature)
+ FeatureConfiguration lambda$new$1(ConfiguredStructureFeature)
```

</details>








































<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
- void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
```

</details>





























<details>
<summary>
net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,int,int,int,int,int,Direction)
- void <init>(StructurePieceType,int,int,int,int,int,int,Direction)
```

</details>








<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,int,int,Direction)
- void <init>(StructurePieceType,int,int,int,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructurePiece
</summary>

```diff
+ StructurePieceType getType()
- StructurePieceType getType()
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,CompoundTag)
+ void <init>(StructurePieceType,int,BoundingBox)
- void <init>(StructurePieceType,int,BoundingBox)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
</summary>

```diff
+ void <init>(StructurePieceType,CompoundTag,StructureManager,Function)
- void <init>(StructurePieceType,CompoundTag,StructureManager,Function)
+ void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
- void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.synth.NormalNoise
</summary>

```diff
- double maxValue()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.synth.PerlinNoise
</summary>

```diff
- double edgeValue(double)
- double maxBrokenValue(double)
- double maxValue()
```

</details>





































































































































































































<details>
<summary>
net.minecraft.world.ticks.SavedTick
</summary>

```diff
- Optional loadTick(CompoundTag,Function)
- SavedTick lambda$loadTick$1(CompoundTag,Object)
+ void lambda$loadTickList$0(CompoundTag,long,Consumer,Object)
- void lambda$loadTickList$0(long,Consumer,SavedTick)
```

</details>
</details>