## Comparison with [19w44a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w44a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w44a</th><th>19w45a</th></tr><tr><td>World version</td><td><pre>2213</pre></td><td><pre>2214</pre></td></tr><tr><td>Protocol version</td><td><pre>560</pre></td><td><pre>561</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w44a</th><th>19w45a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
- minecraft:entity.parrot.imitate.enderman
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
- minecraft:entity.parrot.imitate.enderman
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
composter.json
</summary>

```
A: #planks
B: #wooden_fences
C: #wooden_slabs

Previous pattern:
[B |   | B]
[B |   | B]
[A | A | A]

New pattern:
[C |   | C]
[C |   | C]
[C | C | C]
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
- subtitles.entity.parrot.imitate.enderman: Parrot vwoops
```

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
+ minecraft/tags/entity_types/arrows.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/gui/presets/chaos.png
- minecraft/textures/gui/presets/delight.png
- minecraft/textures/gui/presets/drought.png
- minecraft/textures/gui/presets/luck.png
- minecraft/textures/gui/presets/madness.png
- minecraft/textures/gui/presets/water.png
- realms/textures/gui/realms/images/balloon_trip.png
- realms/textures/gui/realms/images/desert.png
- realms/textures/gui/realms/images/dornenstein_estate.png
- realms/textures/gui/realms/images/escher_tunnel.png
- realms/textures/gui/realms/images/factory_floor.png
- realms/textures/gui/realms/images/flower_mountain.png
- realms/textures/gui/realms/images/gray.png
- realms/textures/gui/realms/images/halloween_woods.png
- realms/textures/gui/realms/images/imperium.png
- realms/textures/gui/realms/images/ludo.png
- realms/textures/gui/realms/images/makersspleef.png
- realms/textures/gui/realms/images/negentropy.png
- realms/textures/gui/realms/images/pumpkin_party.png
- realms/textures/gui/realms/images/sand_castle.png
- realms/textures/gui/realms/images/sparrenhout.png
- realms/textures/gui/realms/images/spindlewood.png
- realms/textures/gui/realms/images/tree_houses.png
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
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.AbstractStateHolder
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockState
+ XXX.block.state.BlockState$1
- XXX.block.state.BlockState$Cache
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$1
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.OldChunkStorage
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.dimension.end.TheEndDimension
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
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
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
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
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
+ XXX.level.biome.BadlandsBiome
- XXX.level.biome.BadlandsPlateauBiome
+ XXX.level.biome.BambooJungleBiome
- XXX.level.biome.BambooJungleHillsBiome
+ XXX.level.biome.BeachBiome
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$BiomeTempCategory
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$SpawnerData
+ XXX.level.biome.BiomeDefaultFeatures
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSourceSettings
- XXX.level.biome.BiomeSourceType
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestBiome
- XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.CheckerboardBiomeSourceSettings
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
- XXX.level.biome.DarkForestBiome
+ XXX.level.biome.DarkForestHillsBiome
- XXX.level.biome.DeepColdOceanBiome
+ XXX.level.biome.DeepFrozenOceanBiome
- XXX.level.biome.DeepLukeWarmOceanBiome
+ XXX.level.biome.DeepOceanBiome
- XXX.level.biome.DeepWarmOceanBiome
+ XXX.level.biome.DesertBiome
- XXX.level.biome.DesertHillsBiome
+ XXX.level.biome.DesertLakesBiome
- XXX.level.biome.EndBarrensBiome
+ XXX.level.biome.EndHighlandsBiome
- XXX.level.biome.EndMidlandsBiome
+ XXX.level.biome.ErodedBadlandsBiome
- XXX.level.biome.FixedBiomeSource
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
+ XXX.level.biome.MushroomFieldsBiome
- XXX.level.biome.MushroomFieldsShoreBiome
+ XXX.level.biome.NearestNeighborBiomeZoomer
- XXX.level.biome.NetherBiome
+ XXX.level.biome.OceanBiome
- XXX.level.biome.OverworldBiomeSource
+ XXX.level.biome.OverworldBiomeSourceSettings
- XXX.level.biome.package-info
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
- XXX.level.biome.TheEndBiomeSourceSettings
+ XXX.level.biome.TheVoidBiome
- XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WoodedBadlandsBiome
- XXX.level.biome.WoodedHillsBiome
+ XXX.level.biome.WoodedMountainBiome
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.BambooBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BedrockBlock
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$3
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Block$OffsetType
- XXX.level.block.Block$Properties
+ XXX.level.block.Blocks
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$ChestSearchCallback
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
+ XXX.level.block.EndRodBlock$1
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrassPathBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.Lantern
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LogBlock
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherPortalBlock$PortalShape
- XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShearableDoublePlantBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulsandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.Dimension
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.NetherDimension
+ XXX.level.dimension.NetherDimension$1
- XXX.level.dimension.NormalDimension
- XXX.level.dimension.package-info
+ XXX.level.levelgen.ChunkGeneratorSettings
- XXX.level.levelgen.DebugGeneratorSettings
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.NetherGeneratorSettings
+ XXX.level.levelgen.NetherLevelSource
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.TheEndGeneratorSettings
- XXX.level.levelgen.TheEndLevelSource
+ XXX.level.levelgen.WorldgenRandom
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
- XXX.level.storage.LevelStorage
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerIO
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
- XXX.levelgen.carver.HellCaveWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.AbstractSmallTreeFeature
+ XXX.levelgen.feature.AbstractTreeFeature
- XXX.levelgen.feature.AcaciaFeature
+ XXX.levelgen.feature.BambooFeature
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
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomRandomFeature
- XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlockFeature
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
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces
- XXX.levelgen.feature.VillagePieces$VillagePiece
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
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
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
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
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
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
+ XXX.minecraft.world.package-info
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.HellFireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.DebugVillagerNameGenerator
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPattern$PortalInfo
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AbstractProperty
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
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
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.world.level.BlockAndBiomeGetter
- XXX.world.level.BlockAndTintGetter
- XXX.world.level.ColorResolver
+ XXX.world.level.CustomSpawner
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelConflictException
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
+ XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PortalForcer
- XXX.world.level.ServerTickList
+ XXX.world.level.SpawnData
- XXX.world.level.TickList
+ XXX.world.level.TickNextTickData
- XXX.world.level.TickPriority
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
XXX.mojang.math.Matrix3f +1M -2M
```
```
XXX.minecraft.core.Direction -1M
```
```
XXX.protocol.game.ClientboundCustomPayloadPacket +2P
```
```
XXX.server.packs.FileResourcePack +1M -1M
```
```
XXX.server.packs.Pack +1P -1P
```
```
XXX.minecraft.sounds.SoundEvents -1P
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.world.entity.Entity +2M -1M
```
```
XXX.world.entity.LivingEntity +1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.ai.goal.Goal +1M
```
```
XXX.entity.animal.Bee$1 +1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +4M
```
```
XXX.entity.animal.Bee$BeePollinateGoal +5M | +1P
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.monster.MagmaCube +1M -1M
```
```
XXX.entity.monster.Phantom +1M
```
```
XXX.entity.monster.Vex +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -1M
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -1M
```
```
XXX.entity.projectile.EyeOfEnder +1M -1M
```
```
XXX.entity.projectile.ShulkerBullet +2M -1M
```
```
XXX.entity.projectile.ThrownTrident +2M -1M | +1P
```
```
XXX.world.level.BaseCommandBlock +1P
```

</details>
<details>
<summary>
com.mojang.math.Matrix3f
</summary>

```diff
- Matrix3f copy()
+ void <init>(float[],boolean)
+ void <init>(Matrix3f,boolean)
```

</details>
<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
+ Direction getNearest(float,float)
```

</details>
<details>
<summary>
net.minecraft.server.packs.FileResourcePack
</summary>

```diff
+ Collection getResources(PackType,String,int,Predicate)
- Collection getResources(PackType,String,String,int,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
- void checkDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- void createWitherRose(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean shouldDespawnInPeaceful()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.Goal
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$1
</summary>

```diff
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
- boolean lambda$findNearestHives$2(PoiType)
- boolean lambda$start$0(BlockPos)
- Stream findNearestHives(int)
- void lambda$start$1(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
- boolean access$400(Bee$BeePollinateGoal)
- float getOffset()
- void access$500(Bee$BeePollinateGoal)
- void setWantedPos()
- void stopPollinating()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.MagmaCube
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- boolean shouldDespawnInPeaceful()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ void checkDespawn()
- void tickDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.EyeOfEnder
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ShulkerBullet
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
- void checkDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownTrident
</summary>

```diff
- boolean isFoil()
+ void checkDespawn()
- void tickDespawn()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.ChatFormatting
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$IdentityStrategy
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
- XXX.advancements.critereon.AbstractCriterionTriggerInstance
+ XXX.advancements.critereon.BlockPredicate
- XXX.advancements.critereon.BlockPredicate$Builder
+ XXX.advancements.critereon.BredAnimalsTrigger
- XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ XXX.advancements.critereon.BrewedPotionTrigger
- XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChangeDimensionTrigger
- XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChanneledLightningTrigger
- XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.EffectsChangedTrigger
+ XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantedItemTrigger
+ XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantmentPredicate
+ XXX.advancements.critereon.EnterBlockTrigger
- XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityEquipmentPredicate
- XXX.advancements.critereon.EntityEquipmentPredicate$Builder
+ XXX.advancements.critereon.EntityFlagsPredicate
- XXX.advancements.critereon.EntityFlagsPredicate$Builder
+ XXX.advancements.critereon.EntityHurtPlayerTrigger
- XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityPredicate
- XXX.advancements.critereon.EntityPredicate$1
+ XXX.advancements.critereon.EntityPredicate$Builder
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$1
- XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LocationTrigger
- XXX.advancements.critereon.LocationTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Floats
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.NetherTravelTrigger
- XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
+ XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PlacedBlockTrigger
- XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$1
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.RecipeUnlockedTrigger
- XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$1
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TickTrigger
+ XXX.advancements.critereon.TickTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$State
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$1
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexConsumer
+ XXX.blaze3d.vertex.VertexFormat
- XXX.blaze3d.vertex.VertexFormatElement
+ XXX.blaze3d.vertex.VertexFormatElement$Type
- XXX.blaze3d.vertex.VertexFormatElement$Usage
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$1
+ XXX.block.model.BlockModel$Bookkeep
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$LoopException
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$Context
- XXX.block.model.BlockModelDefinition$Deserializer
+ XXX.block.model.BlockModelDefinition$MissingVariantException
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$1
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemOverride
+ XXX.block.model.ItemOverride$Deserializer
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.ItemTransforms$TransformType
+ XXX.block.model.MultiVariant
- XXX.block.model.MultiVariant$Deserializer
- XXX.block.model.package-info
+ XXX.block.model.Variant
- XXX.block.model.Variant$Deserializer
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.AbstractStateHolder
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockState
+ XXX.block.state.BlockState$1
- XXX.block.state.BlockState$Cache
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
- XXX.block.statemap.package-info
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$1
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.OldChunkStorage
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.MultiPlayerLevel
+ XXX.client.renderer.BiomeColors$ColorResolver
- XXX.client.renderer.ChunkBufferBuilderPack
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.EffectInstance
+ XXX.client.renderer.EntityBlockRenderer
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$1
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$1
+ XXX.client.renderer.LevelRenderer$RenderChunkInfo
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$1
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$AlphaStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ XXX.client.renderer.RenderStateShard$FogStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$PortalTexturingStateShard
+ XXX.client.renderer.RenderStateShard$ShadeModelStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$1
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeState
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.dimension.end.TheEndDimension
+ XXX.entity.layers.AbstractArmorLayer
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer
- XXX.entity.layers.HumanoidArmorLayer$1
+ XXX.entity.layers.IronGolemCrackinessLayer
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.package-info
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PigSaddleLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.player.package-info
- XXX.entity.player.PlayerRenderer
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
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
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
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
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
- XXX.gui.screens.RealmsBackupInfoScreen
+ XXX.gui.screens.RealmsBackupInfoScreen$1
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
+ XXX.gui.screens.RealmsBackupScreen
- XXX.gui.screens.RealmsBackupScreen$1
+ XXX.gui.screens.RealmsBackupScreen$2
- XXX.gui.screens.RealmsBackupScreen$3
+ XXX.gui.screens.RealmsBackupScreen$4
- XXX.gui.screens.RealmsBackupScreen$5
+ XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionListEntry
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsBrokenWorldScreen$1
+ XXX.gui.screens.RealmsBrokenWorldScreen$2
- XXX.gui.screens.RealmsBrokenWorldScreen$DownloadButton
+ XXX.gui.screens.RealmsBrokenWorldScreen$PlayButton
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsClientOutdatedScreen$1
- XXX.gui.screens.RealmsConfigureWorldScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen$1
- XXX.gui.screens.RealmsConfigureWorldScreen$2
+ XXX.gui.screens.RealmsConfigureWorldScreen$3
- XXX.gui.screens.RealmsConfigureWorldScreen$4
+ XXX.gui.screens.RealmsConfigureWorldScreen$5
- XXX.gui.screens.RealmsConfigureWorldScreen$6
+ XXX.gui.screens.RealmsConfigureWorldScreen$7
- XXX.gui.screens.RealmsConfigureWorldScreen$8
+ XXX.gui.screens.RealmsConfigureWorldScreen$9
- XXX.gui.screens.RealmsConfirmScreen
+ XXX.gui.screens.RealmsConfirmScreen$1
- XXX.gui.screens.RealmsConfirmScreen$2
+ XXX.gui.screens.RealmsCreateRealmScreen
- XXX.gui.screens.RealmsCreateRealmScreen$1
+ XXX.gui.screens.RealmsCreateRealmScreen$2
- XXX.gui.screens.RealmsCreateTrialScreen
+ XXX.gui.screens.RealmsCreateTrialScreen$1
- XXX.gui.screens.RealmsCreateTrialScreen$2
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$1
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
- XXX.gui.screens.RealmsGenericErrorScreen
+ XXX.gui.screens.RealmsGenericErrorScreen$1
- XXX.gui.screens.RealmsInviteScreen
+ XXX.gui.screens.RealmsInviteScreen$1
- XXX.gui.screens.RealmsInviteScreen$2
+ XXX.gui.screens.RealmsLongConfirmationScreen
- XXX.gui.screens.RealmsLongConfirmationScreen$1
+ XXX.gui.screens.RealmsLongConfirmationScreen$2
- XXX.gui.screens.RealmsLongConfirmationScreen$3
+ XXX.gui.screens.RealmsLongConfirmationScreen$Type
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen$1
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen$2
+ XXX.gui.screens.RealmsNotificationsScreen
- XXX.gui.screens.RealmsNotificationsScreen$1
+ XXX.gui.screens.RealmsParentalConsentScreen
- XXX.gui.screens.RealmsParentalConsentScreen$1
+ XXX.gui.screens.RealmsParentalConsentScreen$2
- XXX.gui.screens.RealmsParentalConsentScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$1
+ XXX.gui.screens.RealmsPendingInvitesScreen$2
- XXX.gui.screens.RealmsPendingInvitesScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen$4
- XXX.gui.screens.RealmsPendingInvitesScreen$5
+ XXX.gui.screens.RealmsPendingInvitesScreen$6
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$RejectRowButton
- XXX.gui.screens.RealmsPlayerScreen
+ XXX.gui.screens.RealmsPlayerScreen$1
- XXX.gui.screens.RealmsPlayerScreen$2
+ XXX.gui.screens.RealmsPlayerScreen$3
- XXX.gui.screens.RealmsPlayerScreen$4
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionListEntry
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetNormalWorldScreen$1
+ XXX.gui.screens.RealmsResetNormalWorldScreen$2
- XXX.gui.screens.RealmsResetNormalWorldScreen$3
+ XXX.gui.screens.RealmsResetNormalWorldScreen$4
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$2
+ XXX.gui.screens.RealmsResetWorldScreen$3
- XXX.gui.screens.RealmsResetWorldScreen$4
+ XXX.gui.screens.RealmsResetWorldScreen$5
- XXX.gui.screens.RealmsResetWorldScreen$6
+ XXX.gui.screens.RealmsResetWorldScreen$7
- XXX.gui.screens.RealmsResetWorldScreen$8
+ XXX.gui.screens.RealmsResetWorldScreen$9
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
+ XXX.gui.screens.RealmsResetWorldScreen$ResetType
- XXX.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
+ XXX.gui.screens.RealmsResourcePackScreen
- XXX.gui.screens.RealmsScreenWithCallback
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$1
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$2
- XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldListEntry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$2
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$3
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$4
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$5
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionListEntry
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSettingsScreen$1
- XXX.gui.screens.RealmsSettingsScreen$2
+ XXX.gui.screens.RealmsSettingsScreen$3
- XXX.gui.screens.RealmsSlotOptionsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen$1
- XXX.gui.screens.RealmsSlotOptionsScreen$10
+ XXX.gui.screens.RealmsSlotOptionsScreen$2
- XXX.gui.screens.RealmsSlotOptionsScreen$3
+ XXX.gui.screens.RealmsSlotOptionsScreen$4
- XXX.gui.screens.RealmsSlotOptionsScreen$5
+ XXX.gui.screens.RealmsSlotOptionsScreen$6
- XXX.gui.screens.RealmsSlotOptionsScreen$7
+ XXX.gui.screens.RealmsSlotOptionsScreen$8
- XXX.gui.screens.RealmsSlotOptionsScreen$9
+ XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- XXX.gui.screens.RealmsSubscriptionInfoScreen
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$1
- XXX.gui.screens.RealmsSubscriptionInfoScreen$2
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$3
- XXX.gui.screens.RealmsSubscriptionInfoScreen$4
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsTermsScreen$1
+ XXX.gui.screens.RealmsTermsScreen$2
- XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.RealmsUploadScreen$1
- XXX.gui.screens.RealmsUploadScreen$2
+ XXX.gui.screens.RealmsUploadScreen$Unit
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
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
+ XXX.level.biome.BadlandsBiome
- XXX.level.biome.BadlandsPlateauBiome
+ XXX.level.biome.BambooJungleBiome
- XXX.level.biome.BambooJungleHillsBiome
+ XXX.level.biome.BeachBiome
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$BiomeCategory
- XXX.level.biome.Biome$BiomeTempCategory
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$SpawnerData
+ XXX.level.biome.BiomeDefaultFeatures
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSourceSettings
- XXX.level.biome.BiomeSourceType
+ XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestBiome
- XXX.level.biome.BirchForestHillsBiome
+ XXX.level.biome.CheckerboardBiomeSourceSettings
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
- XXX.level.biome.DarkForestBiome
+ XXX.level.biome.DarkForestHillsBiome
- XXX.level.biome.DeepColdOceanBiome
+ XXX.level.biome.DeepFrozenOceanBiome
- XXX.level.biome.DeepLukeWarmOceanBiome
+ XXX.level.biome.DeepOceanBiome
- XXX.level.biome.DeepWarmOceanBiome
+ XXX.level.biome.DesertBiome
- XXX.level.biome.DesertHillsBiome
+ XXX.level.biome.DesertLakesBiome
- XXX.level.biome.EndBarrensBiome
+ XXX.level.biome.EndHighlandsBiome
- XXX.level.biome.EndMidlandsBiome
+ XXX.level.biome.ErodedBadlandsBiome
- XXX.level.biome.FixedBiomeSource
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
+ XXX.level.biome.MushroomFieldsBiome
- XXX.level.biome.MushroomFieldsShoreBiome
+ XXX.level.biome.NearestNeighborBiomeZoomer
- XXX.level.biome.NetherBiome
+ XXX.level.biome.OceanBiome
- XXX.level.biome.OverworldBiomeSource
+ XXX.level.biome.OverworldBiomeSourceSettings
- XXX.level.biome.package-info
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
- XXX.level.biome.TheEndBiomeSourceSettings
+ XXX.level.biome.TheVoidBiome
- XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WoodedBadlandsBiome
- XXX.level.biome.WoodedHillsBiome
+ XXX.level.biome.WoodedMountainBiome
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.BambooBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BedrockBlock
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$3
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Block$OffsetType
- XXX.level.block.Block$Properties
+ XXX.level.block.Blocks
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$ChestSearchCallback
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
+ XXX.level.block.EndRodBlock$1
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
+ XXX.level.block.FireBlock
- XXX.level.block.FletchingTableBlock
+ XXX.level.block.FlowerBlock
- XXX.level.block.FlowerPotBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FurnaceBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GrassBlock
- XXX.level.block.GrassPathBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.Lantern
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LogBlock
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherPortalBlock$PortalShape
- XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShearableDoublePlantBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulsandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.Dimension
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.NetherDimension
+ XXX.level.dimension.NetherDimension$1
- XXX.level.dimension.NormalDimension
- XXX.level.dimension.package-info
+ XXX.level.levelgen.ChunkGeneratorSettings
- XXX.level.levelgen.DebugGeneratorSettings
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.NetherGeneratorSettings
+ XXX.level.levelgen.NetherLevelSource
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.OverworldGeneratorSettings
- XXX.level.levelgen.OverworldLevelSource
+ XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.TheEndGeneratorSettings
- XXX.level.levelgen.TheEndLevelSource
+ XXX.level.levelgen.WorldgenRandom
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
- XXX.level.storage.LevelStorage
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerIO
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
- XXX.levelgen.carver.HellCaveWorldCarver
+ XXX.levelgen.carver.NoneCarverConfiguration
+ XXX.levelgen.carver.package-info
- XXX.levelgen.carver.UnderwaterCanyonWorldCarver
+ XXX.levelgen.carver.UnderwaterCaveWorldCarver
- XXX.levelgen.carver.WorldCarver
- XXX.levelgen.feature.AbstractFlowerFeature
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.AbstractSmallTreeFeature
+ XXX.levelgen.feature.AbstractTreeFeature
- XXX.levelgen.feature.AcaciaFeature
+ XXX.levelgen.feature.BambooFeature
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
+ XXX.levelgen.feature.NetherFortressFeature
- XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomRandomFeature
- XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlockFeature
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
+ XXX.levelgen.feature.VillageFeature
- XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces
- XXX.levelgen.feature.VillagePieces$VillagePiece
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
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
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
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
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
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
- XXX.minecraft.advancements.Advancement
+ XXX.minecraft.advancements.Advancement$1
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementList
- XXX.minecraft.advancements.AdvancementList$Listener
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementProgress$Serializer
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.AdvancementRewards$Deserializer
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.FrameType
- XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.RequirementsStrategy
+ XXX.minecraft.advancements.TreeNodePosition
+ XXX.minecraft.client.AmbientOcclusionStatus
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.BooleanOption
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.CycleOption
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.FullscreenResolutionProgressOption
+ XXX.minecraft.client.Game
- XXX.minecraft.client.Game$Metrics
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.KeyMapping$1
+ XXX.minecraft.client.LogaritmicProgressOption
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$2
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.Option
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.ProgressOption
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.Session
- XXX.minecraft.client.Timer
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
+ XXX.minecraft.world.package-info
+ XXX.model.multipart.AndCondition
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.MultiPart
+ XXX.model.multipart.MultiPart$Deserializer
- XXX.model.multipart.OrCondition
+ XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.model.multipart.Selector$Deserializer
+ XXX.mojang.math.Matrix3f
- XXX.mojang.math.Matrix4f
+ XXX.mojang.math.Quaternion
- XXX.mojang.math.Transformation
+ XXX.mojang.math.Vector3d
- XXX.mojang.math.Vector3f
+ XXX.mojang.math.Vector4f
- XXX.mojang.realmsclient.KeyCombo
+ XXX.mojang.realmsclient.RealmsMainScreen
- XXX.mojang.realmsclient.RealmsMainScreen$1
+ XXX.mojang.realmsclient.RealmsMainScreen$10
- XXX.mojang.realmsclient.RealmsMainScreen$11
+ XXX.mojang.realmsclient.RealmsMainScreen$12
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$3
- XXX.mojang.realmsclient.RealmsMainScreen$4
+ XXX.mojang.realmsclient.RealmsMainScreen$5
- XXX.mojang.realmsclient.RealmsMainScreen$6
+ XXX.mojang.realmsclient.RealmsMainScreen$7
- XXX.mojang.realmsclient.RealmsMainScreen$8
+ XXX.mojang.realmsclient.RealmsMainScreen$9
- XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
+ XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
- XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionListEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionListTrialEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.HellFireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
- XXX.protocol.game.DebugMobNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.realmsclient.client.FileDownload
- XXX.realmsclient.client.FileDownload$1
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
- XXX.realmsclient.client.Ping
+ XXX.realmsclient.client.Ping$Region
- XXX.realmsclient.client.RealmsClient
+ XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
- XXX.realmsclient.client.RealmsClient$Environment
+ XXX.realmsclient.client.RealmsClientConfig
- XXX.realmsclient.client.RealmsError
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.Ops
- XXX.realmsclient.dto.PendingInvite
+ XXX.realmsclient.dto.PendingInvitesList
- XXX.realmsclient.dto.PingResult
+ XXX.realmsclient.dto.PlayerInfo
- XXX.realmsclient.dto.RealmsDescriptionDto
+ XXX.realmsclient.dto.RealmsNews
- XXX.realmsclient.dto.RealmsServer
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPing
+ XXX.realmsclient.dto.RealmsServerPlayerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsWorldOptions
- XXX.realmsclient.dto.RealmsWorldResetDto
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.ServerActivity
+ XXX.realmsclient.dto.ServerActivityList
- XXX.realmsclient.dto.Subscription
+ XXX.realmsclient.dto.Subscription$SubscriptionType
- XXX.realmsclient.dto.UploadInfo
+ XXX.realmsclient.dto.ValueObject
- XXX.realmsclient.dto.WorldDownload
+ XXX.realmsclient.dto.WorldTemplate
- XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
+ XXX.realmsclient.dto.WorldTemplatePaginatedList
- XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ XXX.realmsclient.exception.RealmsHttpException
- XXX.realmsclient.exception.RealmsServiceException
+ XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.ChatFormatting
+ XXX.realmsclient.gui.LongRunningTask
- XXX.realmsclient.gui.RealmsConstants
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsDataFetcher$1
+ XXX.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
- XXX.realmsclient.gui.RealmsDataFetcher$PendingInviteUpdateTask
+ XXX.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
- XXX.realmsclient.gui.RealmsDataFetcher$Task
+ XXX.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
- XXX.realmsclient.gui.RealmsDataFetcher$UnreadNewsTask
+ XXX.realmsclient.gui.RealmsWorldSlotButton
- XXX.realmsclient.gui.RealmsWorldSlotButton$Action
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Listener
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$1
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTasks
+ XXX.realmsclient.util.RealmsTasks$CloseServerTask
- XXX.realmsclient.util.RealmsTasks$DownloadTask
+ XXX.realmsclient.util.RealmsTasks$OpenServerTask
- XXX.realmsclient.util.RealmsTasks$RealmsConnectTask
+ XXX.realmsclient.util.RealmsTasks$RealmsGetServerDetailsTask
- XXX.realmsclient.util.RealmsTasks$ResettingWorldTask
+ XXX.realmsclient.util.RealmsTasks$RestoreTask
- XXX.realmsclient.util.RealmsTasks$SwitchMinigameTask
+ XXX.realmsclient.util.RealmsTasks$SwitchSlotTask
- XXX.realmsclient.util.RealmsTasks$TrialCreationTask
+ XXX.realmsclient.util.RealmsTasks$WorldCreationTask
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$1
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.RealmsUtil$1
+ XXX.realmsclient.util.SkinProcessor
- XXX.realmsclient.util.TextRenderingUtils
+ XXX.realmsclient.util.TextRenderingUtils$Line
- XXX.realmsclient.util.TextRenderingUtils$LineSegment
+ XXX.realmsclient.util.UploadTokenCache
+ XXX.renderer.banner.BannerTextures$1
+ XXX.renderer.banner.BannerTextures$TimestampedBannerTexture
- XXX.renderer.banner.package-info
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.block.package-info
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ChestRenderer$1
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BeeDebugRenderer$HiveInfo
+ XXX.renderer.debug.CaveDebugRenderer
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer$1
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.LightDebugRenderer
+ XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.SolidFaceRenderer
+ XXX.renderer.debug.StructureRenderer
- XXX.renderer.debug.VillageDebugRenderer
+ XXX.renderer.debug.VillageDebugRenderer$BrainDump
- XXX.renderer.debug.VillageDebugRenderer$PoiInfo
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AreaEffectCloudRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChestedHorseRenderer
- XXX.renderer.entity.ChickenRenderer
+ XXX.renderer.entity.CodRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EnderDragonRenderer$DragonModel
+ XXX.renderer.entity.EndermanRenderer
- XXX.renderer.entity.EndermiteRenderer
+ XXX.renderer.entity.EntityRenderDispatcher
- XXX.renderer.entity.EntityRenderer
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.GhastRenderer
- XXX.renderer.entity.GiantMobRenderer
+ XXX.renderer.entity.GuardianRenderer
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
+ XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PigZombieRenderer
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
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZombieRenderer
- XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.DynamicTexture
+ XXX.renderer.texture.HttpTexture
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPattern$PortalInfo
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AbstractProperty
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
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
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.world.level.BlockAndBiomeGetter
- XXX.world.level.BlockAndTintGetter
- XXX.world.level.ColorResolver
+ XXX.world.level.CustomSpawner
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelConflictException
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelType
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
+ XXX.world.level.package-info
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PortalForcer
- XXX.world.level.ServerTickList
+ XXX.world.level.SpawnData
- XXX.world.level.TickList
+ XXX.world.level.TickNextTickData
- XXX.world.level.TickPriority
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
XXX.blaze3d.vertex.BreakingTextureGenerator +1M -1M
```
```
XXX.screens.inventory.InventoryScreen +1M -1M
```
```
XXX.client.model.ArmorStandArmorModel +3M -3M
```
```
XXX.client.model.BatModel +2M -2M
```
```
XXX.client.model.BlazeModel +1M -1M
```
```
XXX.client.model.ChestedHorseModel +3M -3M
```
```
XXX.client.model.CodModel +1M -1M
```
```
XXX.client.model.CreeperModel +1M -1M
```
```
XXX.client.model.DrownedModel +4M -4M
```
```
XXX.client.model.EndermanModel +2M -2M
```
```
XXX.client.model.EntityModel +1P -1P
```
```
XXX.client.model.FoxModel +2M -2M
```
```
XXX.client.model.IllagerModel +3M -3M
```
```
XXX.client.model.LavaSlimeModel +2M -2M
```
```
XXX.client.model.LlamaSpitModel +1M -1M
```
```
XXX.client.model.OcelotModel +1M -1M
```
```
XXX.client.model.ParrotModel +4M -4M
```
```
XXX.client.model.PolarBearModel +2M -2M
```
```
XXX.client.model.PufferfishMidModel +1M -1M
```
```
XXX.client.model.QuadrupedModel +1M -1M
```
```
XXX.client.model.RavagerModel +2M -2M
```
```
XXX.client.model.SheepFurModel +2M -2M
```
```
XXX.client.model.ShieldModel +2M
```
```
XXX.client.model.ShulkerModel +2M -2M
```
```
XXX.client.model.SkeletonModel +4M -4M
```
```
XXX.client.model.SlimeModel +1M -1M
```
```
XXX.client.model.SpiderModel +1M -1M
```
```
XXX.client.model.TropicalFishModelB +1M -1M
```
```
XXX.client.model.VexModel +3M -3M
```
```
XXX.client.model.VillagerModel +1M -1M
```
```
XXX.client.model.WitherBossModel +2M -2M
```
```
XXX.model.geom.ModelPart +4M -4M
```
```
XXX.client.multiplayer.ClientChunkCache +3M -3M | +1P -1P
```
```
XXX.client.particle.DripParticle -1M
```
```
XXX.client.particle.EnchantmentTableParticle -1M
```
```
XXX.client.particle.FireworkParticles$SparkParticle +1M -1M
```
```
XXX.client.particle.ItemPickupParticle +1M -1M
```
```
XXX.client.particle.MobAppearanceParticle +1M -1M
```
```
XXX.client.particle.SimpleAnimatedParticle -1M
```
```
XXX.client.player.AbstractClientPlayer +1M -1M | +1P -1P
```
```
XXX.renderer.blockentity.StructureBlockRenderer +2M -2M
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +3M -3M
```
```
XXX.renderer.texture.TextureAtlasSprite +2M
```
```
XXX.client.resources.AssetIndex +3M -4M | +2P -1P
```
```
XXX.client.resources.LegacyResourcePackAdapter +1M -1M
```
```
XXX.resources.model.ModelBakery +2P
```
```
XXX.client.tutorial.FindTreeTutorialStepInstance +1M -1M
```
```
XXX.client.tutorial.Tutorial +2M -2M
```
```
XXX.minecraft.core.Vec3i +1M
```
```
XXX.server.packs.FileResourcePack +1M -1M
```
```
XXX.server.packs.Pack +1P -1P
```
```
XXX.minecraft.sounds.SoundEvents -1P
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.world.entity.Entity +2M -1M
```
```
XXX.world.entity.LivingEntity +1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.ai.goal.Goal +1M
```
```
XXX.entity.animal.Bee$1 +1M
```
```
XXX.entity.animal.Bee$BeeLocateHiveGoal +4M
```
```
XXX.entity.animal.Bee$BeePollinateGoal +5M | +1P
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.monster.MagmaCube +1M -1M
```
```
XXX.entity.monster.Phantom +1M
```
```
XXX.entity.monster.Vex +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +1M -1M
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -1M
```
```
XXX.entity.projectile.EyeOfEnder +1M -1M
```
```
XXX.entity.projectile.ShulkerBullet +2M -1M
```
```
XXX.entity.projectile.ThrownTrident +2M -1M | +1P
```
```
XXX.world.level.BaseCommandBlock +1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.BreakingTextureGenerator
</summary>

```diff
+ void <init>(VertexConsumer,Matrix4f)
- void <init>(VertexConsumer,PoseStack$Pose)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.InventoryScreen
</summary>

```diff
- void renderEntityInInventory(int,int,int,float,float,LivingEntity)
+ void renderPlayerModel(int,int,int,float,float,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.client.model.ArmorStandArmorModel
</summary>

```diff
+ void setupAnim(ArmorStand,float,float,float,float,float,float)
- void setupAnim(ArmorStand,float,float,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(LivingEntity,float,float,float,float,float,float)
- void setupAnim(LivingEntity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.BatModel
</summary>

```diff
+ void setupAnim(Bat,float,float,float,float,float,float)
- void setupAnim(Bat,float,float,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.BlazeModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.ChestedHorseModel
</summary>

```diff
+ void setupAnim(AbstractChestedHorse,float,float,float,float,float,float)
- void setupAnim(AbstractChestedHorse,float,float,float,float,float)
+ void setupAnim(AbstractHorse,float,float,float,float,float,float)
- void setupAnim(AbstractHorse,float,float,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.CodModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.CreeperModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.DrownedModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(LivingEntity,float,float,float,float,float,float)
- void setupAnim(LivingEntity,float,float,float,float,float)
+ void setupAnim(Monster,float,float,float,float,float,float)
- void setupAnim(Monster,float,float,float,float,float)
+ void setupAnim(Zombie,float,float,float,float,float,float)
- void setupAnim(Zombie,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.EndermanModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(LivingEntity,float,float,float,float,float,float)
- void setupAnim(LivingEntity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.FoxModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Fox,float,float,float,float,float,float)
- void setupAnim(Fox,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.IllagerModel
</summary>

```diff
+ void setupAnim(AbstractIllager,float,float,float,float,float,float)
- void setupAnim(AbstractIllager,float,float,float,float,float)
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void translateToHand(float,HumanoidArm,PoseStack)
- void translateToHand(HumanoidArm,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.LavaSlimeModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Slime,float,float,float,float,float,float)
- void setupAnim(Slime,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.LlamaSpitModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.OcelotModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.ParrotModel
</summary>

```diff
+ void lambda$renderOnShoulder$0(PoseStack,VertexConsumer,float,int,int,ModelPart)
- void lambda$renderOnShoulder$0(PoseStack,VertexConsumer,int,int,ModelPart)
+ void renderOnShoulder(PoseStack,VertexConsumer,int,int,float,float,float,float,float,int)
- void renderOnShoulder(PoseStack,VertexConsumer,int,int,float,float,float,float,int)
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Parrot,float,float,float,float,float,float)
- void setupAnim(Parrot,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.PolarBearModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(PolarBear,float,float,float,float,float,float)
- void setupAnim(PolarBear,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.PufferfishMidModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.QuadrupedModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.RavagerModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Ravager,float,float,float,float,float,float)
- void setupAnim(Ravager,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.SheepFurModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Sheep,float,float,float,float,float,float)
- void setupAnim(Sheep,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShieldModel
</summary>

```diff
- ModelPart handle()
- ModelPart plate()
```

</details>
<details>
<summary>
net.minecraft.client.model.ShulkerModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(Shulker,float,float,float,float,float,float)
- void setupAnim(Shulker,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.SkeletonModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(LivingEntity,float,float,float,float,float,float)
- void setupAnim(LivingEntity,float,float,float,float,float)
+ void setupAnim(Mob,float,float,float,float,float,float)
- void setupAnim(Mob,float,float,float,float,float)
+ void translateToHand(float,HumanoidArm,PoseStack)
- void translateToHand(HumanoidArm,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.SlimeModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.SpiderModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.TropicalFishModelB
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(LivingEntity,float,float,float,float,float,float)
- void setupAnim(LivingEntity,float,float,float,float,float)
+ void setupAnim(Vex,float,float,float,float,float,float)
- void setupAnim(Vex,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.VillagerModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.WitherBossModel
</summary>

```diff
+ void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float)
+ void setupAnim(WitherBoss,float,float,float,float,float,float)
- void setupAnim(WitherBoss,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart
</summary>

```diff
+ void compile(Matrix4f,VertexConsumer,float,int,int,TextureAtlasSprite,float,float,float)
- void compile(PoseStack$Pose,VertexConsumer,int,int,TextureAtlasSprite,float,float,float)
+ void render(PoseStack,VertexConsumer,float,int,int,TextureAtlasSprite,float,float,float)
+ void render(PoseStack,VertexConsumer,float,int,int,TextureAtlasSprite)
- void render(PoseStack,VertexConsumer,int,int,TextureAtlasSprite,float,float,float)
- void render(PoseStack,VertexConsumer,int,int,TextureAtlasSprite)
+ void translateAndRotate(PoseStack,float)
- void translateAndRotate(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientChunkCache
</summary>

```diff
- ClientLevel access$800(ClientChunkCache)
- LevelChunk replaceWithPacketData(int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int)
+ LevelChunk replaceWithPacketData(Level,int,int,ChunkBiomeContainer,FriendlyByteBuf,CompoundTag,int)
+ MultiPlayerLevel access$800(ClientChunkCache)
- void <init>(ClientLevel,int)
+ void <init>(MultiPlayerLevel,int)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle
</summary>

```diff
+ float getBrightness(float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.EnchantmentTableParticle
</summary>

```diff
+ float getBrightness(float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FireworkParticles$SparkParticle
</summary>

```diff
+ void render(VertexConsumer,Camera,float,float,float,float,float,float)
- void render(VertexConsumer,Camera,float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ItemPickupParticle
</summary>

```diff
+ void render(VertexConsumer,Camera,float,float,float,float,float,float)
- void render(VertexConsumer,Camera,float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.MobAppearanceParticle
</summary>

```diff
+ void render(VertexConsumer,Camera,float,float,float,float,float,float)
- void render(VertexConsumer,Camera,float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SimpleAnimatedParticle
</summary>

```diff
+ float getBrightness(float)
```

</details>
<details>
<summary>
net.minecraft.client.player.AbstractClientPlayer
</summary>

```diff
- void <init>(ClientLevel,GameProfile)
+ void <init>(MultiPlayerLevel,GameProfile)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.StructureBlockRenderer
</summary>

```diff
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
- void render(BlockEntity,float,PoseStack,MultiBufferSource,int,int)
+ void render(StructureBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
- void render(StructureBlockEntity,float,PoseStack,MultiBufferSource,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
- void render(BlockEntity,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndGatewayBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
- void render(TheEndGatewayBlockEntity,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
- void render(TheEndPortalBlockEntity,float,PoseStack,MultiBufferSource,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.texture.TextureAtlasSprite
</summary>

```diff
- float atlasSize()
- float uvShrinkRatio()
```

</details>
<details>
<summary>
net.minecraft.client.resources.AssetIndex
</summary>

```diff
- boolean lambda$getFiles$0(String,String,Predicate,ResourceLocation)
+ boolean lambda$getFiles$0(String)
+ boolean lambda$getFiles$1(String,String)
+ Collection getFiles(String,int,Predicate)
- Collection getFiles(String,String,int,Predicate)
+ File getFile(String)
- File getRootFile(String)
```

</details>
<details>
<summary>
net.minecraft.client.resources.LegacyResourcePackAdapter
</summary>

```diff
+ Collection getResources(PackType,String,int,Predicate)
- Collection getResources(PackType,String,String,int,Predicate)
```

</details>
<details>
<summary>
net.minecraft.client.tutorial.FindTreeTutorialStepInstance
</summary>

```diff
- void onLookAt(ClientLevel,HitResult)
+ void onLookAt(MultiPlayerLevel,HitResult)
```

</details>
<details>
<summary>
net.minecraft.client.tutorial.Tutorial
</summary>

```diff
- void onDestroyBlock(ClientLevel,BlockPos,BlockState,float)
+ void onDestroyBlock(MultiPlayerLevel,BlockPos,BlockState,float)
- void onLookAt(ClientLevel,HitResult)
+ void onLookAt(MultiPlayerLevel,HitResult)
```

</details>
<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- String toShortString()
```

</details>
<details>
<summary>
net.minecraft.server.packs.FileResourcePack
</summary>

```diff
+ Collection getResources(PackType,String,int,Predicate)
- Collection getResources(PackType,String,String,int,Predicate)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
- void checkDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- void createWitherRose(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean shouldDespawnInPeaceful()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.Goal
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$1
</summary>

```diff
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
</summary>

```diff
- boolean lambda$findNearestHives$2(PoiType)
- boolean lambda$start$0(BlockPos)
- Stream findNearestHives(int)
- void lambda$start$1(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeePollinateGoal
</summary>

```diff
- boolean access$400(Bee$BeePollinateGoal)
- float getOffset()
- void access$500(Bee$BeePollinateGoal)
- void setWantedPos()
- void stopPollinating()
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.MagmaCube
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Phantom
</summary>

```diff
- boolean shouldDespawnInPeaceful()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ void checkDespawn()
- void tickDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.EyeOfEnder
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ShulkerBullet
</summary>

```diff
- int getBlockLightLevel()
+ int getLightColor()
- void checkDespawn()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownTrident
</summary>

```diff
- boolean isFoil()
+ void checkDespawn()
- void tickDespawn()
```

</details>
</details>
<hr/>