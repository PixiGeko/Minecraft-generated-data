## Comparison with [20w19a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w19a)

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
<table><tr><th></th><th align="left">20w19a</th><th>20w20a</th></tr><tr><td>World version</td><td><pre>2534</pre></td><td><pre>2536</pre></td></tr><tr><td>Protocol version</td><td><pre>715</pre></td><td><pre>716</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w19a</th><th>20w20a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
- chunk_generator_type.txt
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
- universal_tags/chunk_generator_type.json
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
- advancements.husbandry.break_diamond_hoe.description: Completely use up a diamond hoe, and then reevaluate your life choices
- advancements.husbandry.break_diamond_hoe.title: Serious Dedication
+ advancements.husbandry.netherite_hoe.description: Use a Netherite ingot to upgrade a hoe, and then reevaluate your life choices
+ advancements.husbandry.netherite_hoe.title: Serious Dedication
+ advancements.nether.charge_respawn_anchor.description: Charge a Respawn Anchor to the maximum
+ advancements.nether.charge_respawn_anchor.title: Not Quite "Nine" Lives
+ advancements.nether.distract_piglin.description: Distract Piglins with gold
+ advancements.nether.distract_piglin.title: Oh Shiny
+ advancements.nether.explore_nether.description: Explore all Nether biomes
+ advancements.nether.explore_nether.title: Hot Tourist Destinations
+ advancements.nether.find_bastion.description: Enter a Bastion Remnant
+ advancements.nether.find_bastion.title: Those Were the Days
+ advancements.nether.loot_bastion.description: Loot a chest in a Bastion Remnant
+ advancements.nether.loot_bastion.title: War Pigs
+ advancements.nether.netherite_armor.description: Get a full suit of Netherite armor
+ advancements.nether.netherite_armor.title: Cover Me in Debris
+ advancements.nether.obtain_ancient_debris.description: Obtain Ancient Debris
+ advancements.nether.obtain_ancient_debris.title: Hidden in the Depths
+ advancements.nether.obtain_crying_obsidian.description: Obtain Crying Obsidian
+ advancements.nether.obtain_crying_obsidian.title: Who Is Cutting Onions?
+ advancements.nether.ride_strider.description: Ride a Strider with a Warped Fungus on a Stick
+ advancements.nether.ride_strider.title: This Boat Has Legs
+ advancements.nether.use_lodestone.description: Use a Compass on a Lodestone
+ advancements.nether.use_lodestone.title: Country Lode, Take Me Home
+ debug.gamemodes.error: Unable to open game mode switcher, no permission
+ debug.gamemodes.help: F3 + F4 = Open game mode switcher
+ debug.gamemodes.press_f4: F4
+ debug.gamemodes.select_next: Next
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>20w19a</th><th>20w20a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.adventure.bullseye.description</div></th><td>Hit the bullseye of a Target block with an arrow</td><td>Hit the bullseye of a Target block from at least 30 meters away</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.deflect_arrow.description</div></th><td>Deflect an arrow or trident with a shield</td><td>Deflect a projectile with a shield</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.form_obsidian.description</div></th><td>Form and mine a block of obsidian</td><td>Obtain a block of obsidian</td></tr>
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
+ minecraft/advancements/nether/charge_respawn_anchor.json
+ minecraft/advancements/nether/distract_piglin.json
+ minecraft/advancements/nether/explore_nether.json
+ minecraft/advancements/nether/find_bastion.json
+ minecraft/advancements/nether/loot_bastion.json
+ minecraft/advancements/nether/netherite_armor.json
+ minecraft/advancements/nether/obtain_ancient_debris.json
+ minecraft/advancements/nether/obtain_crying_obsidian.json
+ minecraft/advancements/nether/ride_strider.json
+ minecraft/advancements/nether/use_lodestone.json
+ minecraft/tags/items/piglin_loved.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/container/gamemode_switcher.png
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
+ net.minecraft.package-info
- XXX.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
- XXX.advancements.critereon.LootTableTrigger
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedBlockEntityInjecter
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehivePoiRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockRenameFixWithJigsaw
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
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
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration$Builder
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration$Builder
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.JigsawConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MineshaftConfiguration
+ XXX.feature.configurations.MultiJigsawConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RandomRandomFeatureConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSpheroidConfiguration
+ XXX.feature.configurations.ReplaceSpheroidConfiguration$Builder
- XXX.feature.configurations.RuinedPortalConfiguration
+ XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
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
+ XXX.feature.structures.LegacySinglePoolElement
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.package-info
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
+ XXX.layer.traits.AreaTransformer0
- XXX.layer.traits.AreaTransformer1
+ XXX.layer.traits.AreaTransformer2
- XXX.layer.traits.BishopTransformer
+ XXX.layer.traits.C0Transformer
- XXX.layer.traits.C1Transformer
+ XXX.layer.traits.CastleTransformer
- XXX.layer.traits.DimensionOffset0Transformer
+ XXX.layer.traits.DimensionOffset1Transformer
- XXX.layer.traits.DimensionTransformer
- XXX.layer.traits.package-info
+ XXX.layer.traits.PixelTransformer
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSourceSettings
- XXX.level.biome.BiomeSourceType
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$1
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeZoomer
- XXX.level.biome.BirchForestBiome
+ XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.FixedBiomeSourceSettings
- XXX.level.biome.ForestBiome
+ XXX.level.biome.ForestFlowerBiome
- XXX.level.biome.FrozenOceanBiome
+ XXX.level.biome.FrozenRiverBiome
- XXX.level.biome.FuzzyOffsetBiomeZoomer
+ XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
- XXX.level.biome.GiantSpruceTaigaBiome
+ XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
- XXX.level.biome.GiantTreeTaigaBiome
+ XXX.level.biome.GiantTreeTaigaHillsBiome
- XXX.level.biome.GravellyMountainsBiome
+ XXX.level.biome.IceSpikesBiome
- XXX.level.biome.JungleBiome
+ XXX.level.biome.JungleEdgeBiome
- XXX.level.biome.JungleHillsBiome
+ XXX.level.biome.LukeWarmOceanBiome
- XXX.level.biome.ModifiedBadlandsPlateauBiome
+ XXX.level.biome.ModifiedGravellyMountainsBiome
- XXX.level.biome.ModifiedJungleBiome
+ XXX.level.biome.ModifiedJungleEdgeBiome
- XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
+ XXX.level.biome.MountainBiome
- XXX.level.biome.MountainEdgeBiome
+ XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.OverworldBiomeSourceSettings
- XXX.level.biome.PlainsBiome
+ XXX.level.biome.RiverBiome
- XXX.level.biome.SavannaBiome
+ XXX.level.biome.SavannaPlateauBiome
- XXX.level.biome.ShatteredSavannaBiome
+ XXX.level.biome.ShatteredSavannaPlateauBiome
- XXX.level.biome.SmallEndIslandsBiome
+ XXX.level.biome.SnowyBeachBiome
- XXX.level.biome.SnowyMountainsBiome
+ XXX.level.biome.SnowyTaigaBiome
- XXX.level.biome.SnowyTaigaHillsBiome
+ XXX.level.biome.SnowyTaigaMountainsBiome
- XXX.level.biome.SnowyTundraBiome
+ XXX.level.biome.SoulSandValleyBiome
- XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SunflowerPlainsBiome
- XXX.level.biome.SwampBiome
+ XXX.level.biome.SwampHillsBiome
- XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaHillsBiome
- XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchForestBiome
- XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.TheEndBiome
- XXX.level.biome.TheEndBiomeSource
+ XXX.level.biome.TheEndBiomeSourceSettings
+ XXX.level.chunk.ChunkGeneratorType
+ XXX.level.levelgen.ChunkGeneratorProvider
- XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.DebugGeneratorSettings
- XXX.level.levelgen.OverworldGeneratorSettings
+ XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldGenSettings$1
- XXX.level.levelgen.WorldGenSettings$LevelType
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.FlatDataLayer
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
- XXX.level.material.Fluids
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.TurtleNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SaveDataDirtyRunnable
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$1
- XXX.level.timers.TimerQueue$Event
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BastionBridgePools
+ XXX.levelgen.feature.BastionFeature
- XXX.levelgen.feature.BastionFeature$FeatureStart
+ XXX.levelgen.feature.BastionHoglinStablePools
- XXX.levelgen.feature.BastionHousingUnitsPools
+ XXX.levelgen.feature.BastionPieces
- XXX.levelgen.feature.BastionPieces$BastionPiece
+ XXX.levelgen.feature.BastionSharedPools
- XXX.levelgen.feature.BastionTreasureRoomPools
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertVillagePools
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskReplaceFeature
- XXX.levelgen.feature.EndCityFeature
+ XXX.levelgen.feature.EndCityFeature$EndCityStart
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.GlowstoneFeature
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
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.NoSurfaceOreFeature
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomRandomFeature
- XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckFeature
+ XXX.levelgen.feature.ShipwreckFeature$FeatureStart
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SimulatedFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SnowyVillagePools
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaVillagePools
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
- XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
- XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
- XXX.levelgen.placement.CountChanceHeightmapDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDepthAverageDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
- XXX.levelgen.placement.CountHeight64Decorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
- XXX.levelgen.placement.CountHeightmapDecorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountVeryBiasedRangeDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.ForestRockPlacementDecorator
+ XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.FrequencyDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
- XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
+ XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecoratorConfiguration
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
- XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
+ XXX.levelgen.structure.BeardedStructureStart
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilFeature$FeatureStart
- XXX.levelgen.structure.NetherFossilPieces
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$Properties
- XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.CompositeEntryBase$Serializer
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$1
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntries$Serializer
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$1
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$1
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$1
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$1
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$DataSource
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$1
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$1
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
- XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunction$Serializer
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctions$Serializer
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$1
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$1
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$1
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$1
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$1
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$1
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$1
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$1
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$1
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemCondition$Serializer
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditions$Serializer
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$1
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$1
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagTypes
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$1
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$1
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.ConsoleInputSource
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.server.MinecraftServer$3
+ XXX.minecraft.server.package-info
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.TickTask
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$1
+ XXX.minecraft.tags.StaticTagHelper$Wrapper
- XXX.minecraft.tags.SynchronizableTagCollection
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$1
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagManager
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.Deserializer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LimitedCapacityList
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RewindableStream
- XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.Serializable
- XXX.minecraft.util.Serializer
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$1
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.WeighedRandom
- XXX.minecraft.util.WeighedRandom$WeighedRandomItem
- XXX.minecraft.world.package-info
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$ContentConsumer
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.Component$StyledContentConsumer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.KeybindComponent
- XXX.network.chat.MutableComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
- XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.TextColor
+ XXX.network.chat.TextComponent
- XXX.network.chat.TranslatableComponent
+ XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
- XXX.newbiome.area.Area
+ XXX.newbiome.area.AreaFactory
- XXX.newbiome.area.LazyArea
+ XXX.newbiome.area.package-info
- XXX.newbiome.context.BigContext
+ XXX.newbiome.context.Context
- XXX.newbiome.context.LazyAreaContext
+ XXX.newbiome.context.package-info
- XXX.newbiome.layer.AddDeepOceanLayer
+ XXX.newbiome.layer.AddEdgeLayer
- XXX.newbiome.layer.AddEdgeLayer$CoolWarm
+ XXX.newbiome.layer.AddEdgeLayer$HeatIce
- XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ XXX.newbiome.layer.AddIslandLayer
- XXX.newbiome.layer.AddMushroomIslandLayer
+ XXX.newbiome.layer.AddSnowLayer
- XXX.newbiome.layer.BiomeEdgeLayer
+ XXX.newbiome.layer.BiomeInitLayer
- XXX.newbiome.layer.IslandLayer
+ XXX.newbiome.layer.Layer
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.OceanLayer
- XXX.newbiome.layer.OceanMixerLayer
- XXX.newbiome.layer.package-info
+ XXX.newbiome.layer.RareBiomeLargeLayer
- XXX.newbiome.layer.RareBiomeSpotLayer
+ XXX.newbiome.layer.RegionHillsLayer
- XXX.newbiome.layer.RemoveTooMuchOceanLayer
+ XXX.newbiome.layer.RiverInitLayer
- XXX.newbiome.layer.RiverLayer
+ XXX.newbiome.layer.RiverMixerLayer
- XXX.newbiome.layer.ShoreLayer
+ XXX.newbiome.layer.SmoothLayer
- XXX.newbiome.layer.ZoomLayer
+ XXX.newbiome.layer.ZoomLayer$1
+ XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
- XXX.packs.repository.UnopenedPack
+ XXX.packs.repository.UnopenedPack$Position
- XXX.packs.repository.UnopenedPack$UnopenedPackConstructor
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.IntPointRange
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.phys.shapes.WorldRegionIndirectVoxelShape
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddGlobalEntityPacket
+ XXX.protocol.game.ClientboundAddMobPacket
- XXX.protocol.game.ClientboundAddPaintingPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockBreakAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChatPacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$1
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerAckPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket$1
- XXX.protocol.game.ClientboundPlayerCombatPacket$Event
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetBorderPacket
+ XXX.protocol.game.ClientboundSetBorderPacket$1
- XXX.protocol.game.ClientboundSetBorderPacket$Type
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquippedItemPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesPacket
+ XXX.protocol.game.ClientboundSetTitlesPacket$Type
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerAckPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$1
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateBiomeCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ReplaceItemCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.SeedCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServer$2
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$1
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DerivedServerLevel
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FeatureSimulator
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.packs.AbstractResourcePack
+ XXX.server.packs.FileResourcePack
- XXX.server.packs.FolderResourcePack
+ XXX.server.packs.Pack
- XXX.server.packs.package-info
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPack
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$2
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.GameProfileCache$Serializer
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.IntLimiter
- XXX.storage.loot.IntLimiter$1
+ XXX.storage.loot.IntLimiter$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$1
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.OminousBannerBlockEntityRenameFix
- XXX.util.datafix.OminousBannerRenameFix
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
+ XXX.world.level.StructureFeatureManager
- XXX.world.level.TickList
+ XXX.world.level.TickNextTickData
- XXX.world.level.TickPriority
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.PosAndRot
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.advancements.CriteriaTriggers +3P -1P
```
```
XXX.advancements.critereon.EntityPredicate +2M -2M | +2P
```
```
XXX.advancements.critereon.EntityPredicate$Builder +2M | +2P
```
```
XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance +1M
```
```
XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance +2M -2M | +1P -2P
```
```
XXX.advancements.critereon.LocationPredicate +1M -1M | +1P
```
```
XXX.data.structures.StructureUpdater +2M -1M | +1P
```
```
XXX.world.entity.Mob +1M
```
```
XXX.entity.raid.Raids +1M -1M
```
```
XXX.world.level.Level +3M -4M | +1P -1P
```
```
XXX.world.level.LevelReader +1P
```
```
XXX.level.biome.CheckerboardColumnBiomeSource +2M -1M
```
```
XXX.level.chunk.ChunkGenerator +5M -6M | +1P -3P
```
```
XXX.level.dimension.DimensionType +3M -1M | +2P
```
```
XXX.dimension.end.EndDragonFight +1P
```
```
XXX.level.levelgen.FlatLevelSource +4M -1M | +1P
```
```
XXX.level.levelgen.NetherGeneratorSettings +1M -1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M | +2P
```
```
XXX.level.levelgen.TheEndLevelSource +2M -2M | +1P -1P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,EntityPredicate,EntityPredicate,String,ResourceLocation,EntityPredicate$1)
- void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,EntityPredicate,EntityPredicate,String,ResourceLocation)
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation,EntityPredicate$1)
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate$Builder
</summary>

```diff
- EntityPredicate$Builder targetedEntity(EntityPredicate)
- EntityPredicate$Builder vehicle(EntityPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
</summary>

```diff
+ InventoryChangeTrigger$TriggerInstance hasItem(ItemLike[])
+ InventoryChangeTrigger$TriggerInstance hasItem(ItemPredicate[])
- InventoryChangeTrigger$TriggerInstance hasItems(ItemLike[])
- InventoryChangeTrigger$TriggerInstance hasItems(ItemPredicate[])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
</summary>

```diff
- ItemDurabilityTrigger$TriggerInstance changedDurability(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
</summary>

```diff
- ItemUsedOnBlockTrigger$TriggerInstance itemUsedOnBlock(LocationPredicate$Builder,ItemPredicate$Builder)
+ ItemUsedOnBlockTrigger$TriggerInstance safelyHarvestedHoney(BlockPredicate$Builder,ItemPredicate$Builder)
- void <init>(EntityPredicate$Composite,LocationPredicate,ItemPredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite,BlockPredicate,StatePropertiesPredicate,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,LightPredicate,BlockPredicate,FluidPredicate)
```

</details>
<details>
<summary>
net.minecraft.data.structures.StructureUpdater
</summary>

```diff
+ CompoundTag updateStructure(CompoundTag)
- CompoundTag updateStructure(String,CompoundTag)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- void onItemPickup(ItemEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.raid.Raids
</summary>

```diff
+ String getFileId(Dimension)
- String getFileId(DimensionType)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- boolean isDebug()
+ ChunkSource getChunkSource()
- DimensionType dimensionType()
+ LevelType getGeneratorType()
+ long getSeed()
+ void <init>(WritableLevelData,DimensionType,BiFunction,Supplier,boolean)
- void <init>(WritableLevelData,DimensionType,Supplier,boolean,boolean,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
</summary>

```diff
- BiomeSource withSeed(long)
- void <init>(Biome[],int)
+ void <init>(CheckerboardBiomeSourceSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ DimensionType getDimensionType()
- int getSpawnHeight()
- List getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
+ List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
+ long getSeed()
- void <init>(BiomeSource,ChunkGeneratorSettings)
+ void <init>(LevelAccessor,BiomeSource,ChunkGeneratorSettings)
+ void applyCarvers(BiomeManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(long,BiomeManager,ChunkAccess,GenerationStep$Carving)
- void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager,long)
+ void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.DimensionType
</summary>

```diff
- boolean hasCeiling()
- boolean ultraWarm()
+ void <init>(int,String,String,BiFunction,boolean,BiomeZoomer)
- void <init>(int,String,String,BiFunction,boolean,boolean,boolean,BiomeZoomer)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
- BlockState lambda$getBaseColumn$0(BlockState)
- BlockState[] lambda$getBaseColumn$1(int)
- ChunkGenerator withSeed(long)
- void <init>(FlatLevelGeneratorSettings)
+ void <init>(LevelAccessor,BiomeSource,FlatLevelGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NetherGeneratorSettings
</summary>

```diff
+ void <init>()
- void <init>(ChunkGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
- void <init>(BiomeSource,long,NoiseGeneratorSettings,int,int,int,boolean)
+ void <init>(LevelAccessor,BiomeSource,int,int,int,ChunkGeneratorSettings,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.TheEndLevelSource
</summary>

```diff
+ BlockPos getDimensionSpawnPosition()
- ChunkGenerator withSeed(long)
- void <init>(BiomeSource,long,NoiseGeneratorSettings)
+ void <init>(LevelAccessor,BiomeSource,TheEndGeneratorSettings)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
- XXX.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
- XXX.advancements.critereon.LootTableTrigger
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
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
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
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
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration$Builder
- XXX.feature.configurations.CountFeatureConfiguration
+ XXX.feature.configurations.CountRangeDecoratorConfiguration
- XXX.feature.configurations.DecoratedFeatureConfiguration
+ XXX.feature.configurations.DecoratorConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration$Builder
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.FeatureRadiusConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.JigsawConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.MultiJigsawConfiguration
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
+ XXX.feature.configurations.ReplaceSpheroidConfiguration
- XXX.feature.configurations.ReplaceSpheroidConfiguration$Builder
+ XXX.feature.configurations.RuinedPortalConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
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
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.LegacySinglePoolElement
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
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
- XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$1
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestBiome
- XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.CheckerboardBiomeSourceSettings
+ XXX.level.biome.ForestBiome
- XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenOceanBiome
- XXX.level.biome.FrozenRiverBiome
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaBiome
- XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaBiome
- XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.GravellyMountainsBiome
- XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleBiome
- XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.JungleHillsBiome
- XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedBadlandsPlateauBiome
- XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleBiome
- XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.level.biome.MountainBiome
+ XXX.level.biome.MountainEdgeBiome
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceSettings
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.SoulSandValleyBiome
+ XXX.level.biome.StoneShoreBiome
- XXX.level.biome.SunflowerPlainsBiome
+ XXX.level.biome.SwampBiome
- XXX.level.biome.SwampHillsBiome
+ XXX.level.biome.TaigaBiome
- XXX.level.biome.TaigaHillsBiome
+ XXX.level.biome.TaigaMountainsBiome
- XXX.level.biome.TallBirchForestBiome
+ XXX.level.biome.TallBirchHillsBiome
- XXX.level.biome.TheEndBiome
+ XXX.level.biome.TheEndBiomeSource
+ XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.levelgen.ChunkGeneratorSettings
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.OverworldLevelSource
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldGenSettings$BuffetGeneratorType
- XXX.level.levelgen.WorldGenSettings$Preset
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
+ XXX.level.material.Fluids
+ XXX.level.material.FluidState
- XXX.level.material.FluidStateImpl
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.TurtleNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SaveDataDirtyRunnable
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$1
+ XXX.level.timers.TimerQueue$Event
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BastionBridgePools
- XXX.levelgen.feature.BastionFeature
+ XXX.levelgen.feature.BastionFeature$FeatureStart
- XXX.levelgen.feature.BastionHoglinStablePools
+ XXX.levelgen.feature.BastionHousingUnitsPools
- XXX.levelgen.feature.BastionPieces
+ XXX.levelgen.feature.BastionPieces$BastionPiece
- XXX.levelgen.feature.BastionSharedPools
+ XXX.levelgen.feature.BastionTreasureRoomPools
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
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
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
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.IglooFeature
- XXX.levelgen.feature.IglooFeature$FeatureStart
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
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
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RuinedPortalFeature
- XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
+ XXX.levelgen.feature.RuinedPortalFeature$Type
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
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
+ XXX.levelgen.placement.ChanceDecoratorConfiguration
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DepthAverageConfigation
+ XXX.levelgen.placement.EmeraldPlacementDecorator
- XXX.levelgen.placement.EndGatewayPlacementDecorator
+ XXX.levelgen.placement.EndIslandPlacementDecorator
- XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.ForestRockPlacementDecorator
- XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyDecoratorConfiguration
- XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeLavaPlacementDecorator
+ XXX.levelgen.placement.LakeWaterPlacementDecorator
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- XXX.levelgen.placement.NoiseHeightmap32Decorator
+ XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
- XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.RangeDecoratorConfiguration
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.NetherFossilFeature
- XXX.levelgen.structure.NetherFossilFeature$FeatureStart
+ XXX.levelgen.structure.NetherFossilPieces
- XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.RuinedPortalPiece
- XXX.levelgen.structure.RuinedPortalPiece$Properties
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ XXX.levelgen.structure.StrongholdPieces
- XXX.levelgen.structure.StrongholdPieces$1
+ XXX.levelgen.structure.StrongholdPieces$2
- XXX.levelgen.structure.StrongholdPieces$3
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
- XXX.levelgen.structure.StrongholdPieces$FillerCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
- XXX.levelgen.structure.StrongholdPieces$LeftTurn
+ XXX.levelgen.structure.StrongholdPieces$Library
- XXX.levelgen.structure.StrongholdPieces$PieceWeight
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
- XXX.levelgen.structure.StrongholdPieces$PrisonHall
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
- XXX.levelgen.structure.StrongholdPieces$RoomCrossing
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- XXX.levelgen.structure.StrongholdPieces$StairsDown
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
- XXX.levelgen.structure.StrongholdPieces$Straight
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.StrongholdPieces$Turn
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructureFeatureIO
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.CompositeEntryBase$Serializer
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntries$Serializer
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$1
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$1
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$DataSource
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$1
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$1
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$1
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunction$Serializer
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctions$Serializer
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$1
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$1
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$1
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$1
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$1
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$1
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$1
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$1
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemCondition$Serializer
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditions$Serializer
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$1
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$1
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$1
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
- XXX.minecraft.obfuscate.KeepAfterObfuscation
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.NarrationHelper
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsBridge
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RealmsServerAddress
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$1
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.MinecraftServer$3
- XXX.minecraft.server.package-info
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.StaticTagHelper$1
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.SynchronizableTagCollection
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$1
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagCollection
+ XXX.minecraft.tags.TagManager
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
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InsensitiveStringMap
- XXX.minecraft.util.IntRange
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LimitedCapacityList
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RewindableStream
+ XXX.minecraft.util.RewindableStream$1
- XXX.minecraft.util.Serializable
+ XXX.minecraft.util.Serializer
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
+ XXX.minecraft.world.package-info
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$ContentConsumer
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.Component$StyledContentConsumer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.MutableComponent
- XXX.network.chat.NbtComponent
+ XXX.network.chat.NbtComponent$BlockNbtComponent
- XXX.network.chat.NbtComponent$EntityNbtComponent
+ XXX.network.chat.NbtComponent$StorageNbtComponent
+ XXX.network.chat.package-info
- XXX.network.chat.ScoreComponent
+ XXX.network.chat.SelectorComponent
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.TextColor
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.Layers
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
- XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.package-info
- XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
+ XXX.packs.repository.UnopenedPack
- XXX.packs.repository.UnopenedPack$Position
+ XXX.packs.repository.UnopenedPack$UnopenedPackConstructor
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$1
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadableResourceManager
+ XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.packs.resources.SimpleResource
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.IntPointRange
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.FireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddGlobalEntityPacket
- XXX.protocol.game.ClientboundAddMobPacket
+ XXX.protocol.game.ClientboundAddPaintingPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockBreakAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$1
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerAckPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket$1
+ XXX.protocol.game.ClientboundPlayerCombatPacket$Event
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetBorderPacket
- XXX.protocol.game.ClientboundSetBorderPacket$1
+ XXX.protocol.game.ClientboundSetBorderPacket$Type
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquippedItemPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesPacket
- XXX.protocol.game.ClientboundSetTitlesPacket$Type
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerAckPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.worldselection.CreateWorldScreen$7
+ XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList
- XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
+ XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.WorldGenSettingsComponent
- XXX.screens.worldselection.WorldGenSettingsComponent$2
- XXX.screens.worldselection.WorldGenSettingsComponent$PresetEditor
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateBiomeCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ReplaceItemCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServer$2
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
- XXX.server.dedicated.Settings$1
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$1
- XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
- XXX.server.level.ChunkHolder$FullChunkStatus
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$1
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DerivedServerLevel
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FeatureSimulator
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$1
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.WorldGenRegion
+ XXX.server.level.WorldGenTickList
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.packs.AbstractResourcePack
- XXX.server.packs.FileResourcePack
+ XXX.server.packs.FolderResourcePack
- XXX.server.packs.Pack
+ XXX.server.packs.package-info
+ XXX.server.packs.PackType
- XXX.server.packs.ResourcePackFileNotFoundException
+ XXX.server.packs.VanillaPack
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$2
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.GameProfileCache$Serializer
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.IntLimiter
+ XXX.storage.loot.IntLimiter$1
- XXX.storage.loot.IntLimiter$Serializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$1
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$1
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructureManager
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.OminousBannerBlockEntityRenameFix
+ XXX.util.datafix.OminousBannerRenameFix
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PortalForcer
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerTickList
+ XXX.world.level.SpawnData
- XXX.world.level.StructureFeatureManager
+ XXX.world.level.TickList
- XXX.world.level.TickNextTickData
+ XXX.world.level.TickPriority
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.PosAndRot
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.advancements.CriteriaTriggers +3P -1P
```
```
XXX.advancements.critereon.EntityPredicate +2M -2M | +2P
```
```
XXX.advancements.critereon.EntityPredicate$Builder +2M | +2P
```
```
XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance +1M
```
```
XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance +2M -2M | +1P -2P
```
```
XXX.advancements.critereon.LocationPredicate +1M -1M | +1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen +2M -6M | +3P -3P
```
```
XXX.gui.screens.CreateBuffetWorldScreen$BiomeList +2M -2M
```
```
XXX.gui.screens.CreateFlatWorldScreen +1M -1M | +2P -1P
```
```
XXX.screens.worldselection.CreateWorldScreen$5 +1M -3M | +1P -1P
```
```
XXX.client.model.ListModel +1M
```
```
XXX.client.multiplayer.ClientLevel +11M -10M | +2P
```
```
XXX.client.multiplayer.ClientLevel$ClientLevelData +3M -4M | +1P -2P
```
```
XXX.client.multiplayer.MultiPlayerGameMode +1M | +1P
```
```
XXX.client.renderer.FogRenderer +1M -1M
```
```
XXX.client.renderer.RenderType +2M
```
```
XXX.renderer.entity.ShulkerRenderer -2M
```
```
XXX.minecraft.core.Registry +24M -25M | -1P
```
```
XXX.data.advancements.AdventureAdvancements +1M -1M
```
```
XXX.data.advancements.NetherAdvancements +1M | +1P
```
```
XXX.data.structures.SnbtToNbt +1P
```
```
XXX.data.structures.SnbtToNbt$TaskResult +3M -2M | +1P
```
```
XXX.entity.monster.Shulker -1M
```
```
XXX.monster.piglin.PiglinAi -1P
```
```
XXX.world.level.LevelAccessor -1P
```
```
XXX.world.level.LevelSettings +2M -8M | +1P -4P
```
```
XXX.level.biome.Biome +1M -1M
```
```
XXX.level.biome.BiomeManager +1M
```
```
XXX.level.biome.BiomeSource +1P
```
```
XXX.level.biome.FixedBiomeSource +2M -1M
```
```
XXX.level.biome.OverworldBiomeSource +2M -1M | +2P
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.chunk.storage.ChunkSerializer +1M -1M
```
```
XXX.level.dimension.Dimension -7M | +2P -8P
```
```
XXX.level.dimension.NetherDimension +2M -5M
```
```
XXX.level.dimension.NormalDimension +2M -5M
```
```
XXX.dimension.end.TheEndDimension +2M -8M
```
```
XXX.level.levelgen.DebugLevelSource +3M -3M | +1P
```
```
XXX.level.levelgen.NetherLevelSource +3M -3M | +1P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,EntityPredicate,EntityPredicate,String,ResourceLocation,EntityPredicate$1)
- void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,EntityPredicate,EntityPredicate,String,ResourceLocation)
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation,EntityPredicate$1)
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,PlayerPredicate,FishingHookPredicate,String,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate$Builder
</summary>

```diff
- EntityPredicate$Builder targetedEntity(EntityPredicate)
- EntityPredicate$Builder vehicle(EntityPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
</summary>

```diff
+ InventoryChangeTrigger$TriggerInstance hasItem(ItemLike[])
+ InventoryChangeTrigger$TriggerInstance hasItem(ItemPredicate[])
- InventoryChangeTrigger$TriggerInstance hasItems(ItemLike[])
- InventoryChangeTrigger$TriggerInstance hasItems(ItemPredicate[])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
</summary>

```diff
- ItemDurabilityTrigger$TriggerInstance changedDurability(EntityPredicate$Composite,ItemPredicate,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
</summary>

```diff
- ItemUsedOnBlockTrigger$TriggerInstance itemUsedOnBlock(LocationPredicate$Builder,ItemPredicate$Builder)
+ ItemUsedOnBlockTrigger$TriggerInstance safelyHarvestedHoney(BlockPredicate$Builder,ItemPredicate$Builder)
- void <init>(EntityPredicate$Composite,LocationPredicate,ItemPredicate)
+ void <init>(ResourceLocation,EntityPredicate$Composite,BlockPredicate,StatePropertiesPredicate,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,LightPredicate,BlockPredicate,FluidPredicate)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
+ boolean lambda$loadOptions$4(ResourceLocation,CreateBuffetWorldScreen$BiomeList$Entry)
- boolean lambda$new$0(Biome,CreateBuffetWorldScreen$BiomeList$Entry)
+ boolean lambda$static$0(ResourceLocation)
+ Component createGeneratorString(int)
+ CompoundTag saveOptions()
+ void <init>(CreateWorldScreen,ChunkGeneratorProvider)
- void <init>(Screen,Consumer,Pair)
+ void loadOptions()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
</summary>

```diff
- String lambda$new$0(Biome)
+ String lambda$new$0(ResourceLocation)
- void lambda$new$1(Biome)
+ void lambda$new$1(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen
</summary>

```diff
+ void <init>(CreateWorldScreen,ChunkGeneratorProvider)
- void <init>(Screen,Consumer,FlatLevelGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$5
</summary>

```diff
+ Component getMessage()
+ MutableComponent createNarrationMessage()
- void <clinit>()
+ void <init>(CreateWorldScreen,int,int,int,int,Component,Button$OnPress)
```

</details>
<details>
<summary>
net.minecraft.client.model.ListModel
</summary>

```diff
- void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ ChunkSource lambda$new$1(int,Level,Dimension)
- ClientLevel$ClientLevelData getLevelData()
- DimensionSpecialEffects effects()
+ double getHorizonHeight()
- int lambda$getBlockTint$8(BlockPos,ColorResolver)
+ int lambda$getBlockTint$9(BlockPos,ColorResolver)
- LevelData getLevelData()
- String lambda$fillReportDetails$6()
+ String lambda$fillReportDetails$8()
- String lambda$tickNonPassenger$2(Entity)
+ String lambda$tickNonPassenger$3(Entity)
- void <init>(ClientPacketListener,ClientLevel$ClientLevelData,DimensionType,int,Supplier,LevelRenderer,boolean,long)
+ void <init>(ClientPacketListener,ClientLevel$ClientLevelData,DimensionType,int,Supplier,LevelRenderer)
- void lambda$clearTintCaches$4(ColorResolver,BlockTintCache)
+ void lambda$clearTintCaches$5(ColorResolver,BlockTintCache)
- void lambda$doAnimateTick$5(BlockPos$MutableBlockPos,AmbientParticleSettings)
+ void lambda$doAnimateTick$6(BlockPos$MutableBlockPos,AmbientParticleSettings)
- void lambda$onChunkLoaded$3(int,int,ColorResolver,BlockTintCache)
+ void lambda$onChunkLoaded$4(int,int,ColorResolver,BlockTintCache)
- void lambda$tickEntities$1(Entity)
+ void lambda$tickEntities$2(Entity)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
</summary>

```diff
+ ChunkGeneratorProvider getGeneratorProvider()
- double getClearColorScale()
- double getHorizonHeight()
+ LevelType getGeneratorType()
+ long getSeed()
- void <init>(Difficulty,boolean,boolean)
+ void <init>(long,Difficulty,boolean,ChunkGeneratorProvider)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.MultiPlayerGameMode
</summary>

```diff
- GameType getPrevPlayerMode()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FogRenderer
</summary>

```diff
- Vec3 lambda$setupColor$0(ClientLevel,BiomeManager,float,int,int,int)
+ Vec3 lambda$setupColor$0(Dimension,BiomeManager,float,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
- RenderType entityCutoutNoCullZOffset(ResourceLocation,boolean)
- RenderType entityCutoutNoCullZOffset(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ShulkerRenderer
</summary>

```diff
+ void scale(LivingEntity,PoseStack,float)
+ void scale(Shulker,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
- Activity lambda$static$43()
+ Activity lambda$static$44()
- Attribute lambda$static$35()
+ Attribute lambda$static$36()
+ ChunkGeneratorType lambda$static$22()
- ChunkStatus lambda$static$25()
+ ChunkStatus lambda$static$26()
- DimensionType lambda$static$22()
+ DimensionType lambda$static$23()
- MemoryModuleType lambda$static$40()
+ MemoryModuleType lambda$static$41()
- MenuType lambda$static$32()
+ MenuType lambda$static$33()
- Motive lambda$static$23()
+ Motive lambda$static$24()
- PoiType lambda$static$39()
+ PoiType lambda$static$40()
- PosRuleTestType lambda$static$29()
+ PosRuleTestType lambda$static$30()
- RecipeSerializer lambda$static$34()
+ RecipeSerializer lambda$static$35()
- RecipeType lambda$static$33()
+ RecipeType lambda$static$34()
- ResourceLocation lambda$static$24()
+ ResourceLocation lambda$static$25()
- RuleTestType lambda$static$28()
+ RuleTestType lambda$static$29()
- Schedule lambda$static$42()
+ Schedule lambda$static$43()
- SensorType lambda$static$41()
+ SensorType lambda$static$42()
- StatType lambda$static$36()
+ StatType lambda$static$37()
- StructureFeature lambda$static$26()
+ StructureFeature lambda$static$27()
- StructurePieceType lambda$static$27()
+ StructurePieceType lambda$static$28()
- StructurePoolElementType lambda$static$31()
+ StructurePoolElementType lambda$static$32()
- StructureProcessorType lambda$static$30()
+ StructureProcessorType lambda$static$31()
- VillagerProfession lambda$static$38()
+ VillagerProfession lambda$static$39()
- VillagerType lambda$static$37()
+ VillagerType lambda$static$38()
- void lambda$static$44(Map$Entry)
+ void lambda$static$45(Map$Entry)
- void lambda$static$45(WritableRegistry)
+ void lambda$static$46(WritableRegistry)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.AdventureAdvancements
</summary>

```diff
- Advancement$Builder addBiomes(Advancement$Builder,Biome[])
+ Advancement$Builder addBiomes(Advancement$Builder)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.NetherAdvancements
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.data.structures.SnbtToNbt$TaskResult
</summary>

```diff
+ byte[] access$200(SnbtToNbt$TaskResult)
- byte[] access$300(SnbtToNbt$TaskResult)
- String access$200(SnbtToNbt$TaskResult)
- void <init>(String,byte[],String,String)
+ void <init>(String,byte[],String)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ SpawnGroupData finalizeSpawn(LevelAccessor,DifficultyInstance,MobSpawnType,SpawnGroupData,CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.world.level.LevelSettings
</summary>

```diff
+ boolean hasStartingBonusItems()
+ boolean shouldGenerateMapFeatures()
+ ChunkGeneratorProvider getGeneratorProvider()
+ LevelSettings enableSinglePlayerCommands()
+ LevelSettings enableStartingBonusItems()
+ long getSeed()
- void <init>(String,GameType,boolean,Difficulty,boolean,GameRules,WorldGenSettings)
+ void <init>(String,long,GameType,boolean,boolean,Difficulty,ChunkGeneratorProvider,GameRules)
+ void <init>(String,long,GameType,boolean,boolean,Difficulty,ChunkGeneratorProvider)
- WorldGenSettings worldGenSettings()
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ void generate(GenerationStep$Decoration,StructureFeatureManager,ChunkGenerator,LevelAccessor,long,WorldgenRandom,BlockPos)
- void generate(GenerationStep$Decoration,StructureFeatureManager,ChunkGenerator,WorldGenLevel,long,WorldgenRandom,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeManager
</summary>

```diff
- long obfuscateSeed(long)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.FixedBiomeSource
</summary>

```diff
- BiomeSource withSeed(long)
- void <init>(Biome)
+ void <init>(FixedBiomeSourceSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.OverworldBiomeSource
</summary>

```diff
- BiomeSource withSeed(long)
- void <init>(long,boolean,int)
+ void <init>(OverworldBiomeSourceSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ boolean isSmokeyPos(Level,BlockPos,int)
- boolean isSmokeyPos(Level,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.ChunkSerializer
</summary>

```diff
+ Map unpackStructureStart(ChunkGenerator,StructureManager,CompoundTag)
- Map unpackStructureStart(StructureManager,CompoundTag,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.Dimension
</summary>

```diff
+ boolean hasGround()
+ boolean isHasCeiling()
+ boolean isHasSkyLight()
+ boolean isUltraWarm()
+ double getClearColorScale()
+ float getCloudHeight()
+ float[] getSunriseColor(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.NetherDimension
</summary>

```diff
+ BlockPos getSpawnPosInChunk(ChunkPos,boolean)
- BlockPos getSpawnPosInChunk(long,ChunkPos,boolean)
+ BlockPos getValidSpawnPosition(int,int,boolean)
- BlockPos getValidSpawnPosition(long,int,int,boolean)
+ boolean isFoggyAt(int,int)
+ ChunkGenerator createRandomLevelGenerator()
+ Vec3 getBrightnessDependentFogColor(Vec3,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.NormalDimension
</summary>

```diff
+ BlockPos getSpawnPosInChunk(ChunkPos,boolean)
- BlockPos getSpawnPosInChunk(long,ChunkPos,boolean)
+ BlockPos getValidSpawnPosition(int,int,boolean)
- BlockPos getValidSpawnPosition(long,int,int,boolean)
+ boolean isFoggyAt(int,int)
+ ChunkGenerator createRandomLevelGenerator()
+ Vec3 getBrightnessDependentFogColor(Vec3,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.end.TheEndDimension
</summary>

```diff
+ BlockPos getSpawnPosInChunk(ChunkPos,boolean)
- BlockPos getSpawnPosInChunk(long,ChunkPos,boolean)
+ BlockPos getValidSpawnPosition(int,int,boolean)
- BlockPos getValidSpawnPosition(long,int,int,boolean)
+ boolean hasGround()
+ boolean isFoggyAt(int,int)
+ ChunkGenerator createRandomLevelGenerator()
+ float getCloudHeight()
+ float[] getSunriseColor(float,float)
+ Vec3 getBrightnessDependentFogColor(Vec3,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- ChunkGenerator withSeed(long)
+ int getSpawnHeight()
- void <init>()
+ void <init>(LevelAccessor,BiomeSource,DebugGeneratorSettings)
+ void applyCarvers(BiomeManager,ChunkAccess,GenerationStep$Carving)
- void applyCarvers(long,BiomeManager,ChunkAccess,GenerationStep$Carving)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NetherLevelSource
</summary>

```diff
- ChunkGenerator withSeed(long)
+ int getSpawnHeight()
- List getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
+ List getMobsAt(StructureFeatureManager,MobCategory,BlockPos)
- void <init>(BiomeSource,long,NetherGeneratorSettings)
+ void <init>(LevelAccessor,BiomeSource,NetherGeneratorSettings)
```

</details>
</details>
<hr/>