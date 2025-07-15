## Comparison with [22w06a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w06a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">22w06a</th><th>22w07a</th></tr><tr><td>World version</td><td><pre>2968</pre></td><td><pre>2969</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741891</pre></td><td><pre>1073741892</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">22w06a</th><th>22w07a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.StructureFeatures
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
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
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
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
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.GlowLichenConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.JigsawConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RangeConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.RuinedPortalConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2$Type
- XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$Shift0
- XXX.level.levelgen.DensityFunctions$Shift2
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$TerrainShaperSpline
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseFiller
+ XXX.level.levelgen.NoiseChunk$Sampler
- XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseSampler
+ XXX.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.TerrainInfo
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.StructurePieceType$ContextlessType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.feature.WoodlandMansionFeature
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagKey
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagManager
- XXX.minecraft.tags.TagManager$LoadResult
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$EitherCodec
+ XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TelemetryConstants
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.structure.pieces.package-info
+ XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement$PieceFactory
- XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
- XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructureTemplatePool
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$TagAppender
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.NoiseData
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.StructureFeatures
+ XXX.data.worldgen.StructureFeatures$StructureConfigConsumer
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
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
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
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
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.GlowLichenConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.JigsawConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.RangeConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.RuinedPortalConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2$Type
- XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$Shift0
- XXX.level.levelgen.DensityFunctions$Shift2
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$TerrainShaperSpline
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseFiller
+ XXX.level.levelgen.NoiseChunk$Sampler
- XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseSampler
+ XXX.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.TerrainInfo
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.StructurePieceType$ContextlessType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.feature.WoodlandMansionFeature
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagKey
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagManager
- XXX.minecraft.tags.TagManager$LoadResult
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$EitherCodec
+ XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TelemetryConstants
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
- XXX.structure.pieces.package-info
+ XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement$PieceFactory
- XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
- XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructureTemplatePool
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
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
<hr/>