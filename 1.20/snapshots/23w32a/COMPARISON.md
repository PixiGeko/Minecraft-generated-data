## Comparison with [23w31a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w31a)

> [!TIP]
> - [Version data](#version-data)
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
<table><tr><th></th><th align="left">23w31a</th><th>23w32a</th></tr><tr><td>DataPack version</td><td><pre>16</pre></td><td><pre>17</pre></td></tr><tr><td>ResourcePack version</td><td><pre>16</pre></td><td><pre>17</pre></td></tr><tr><td>World version</td><td><pre>3567</pre></td><td><pre>3569</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741968</pre></td><td><pre>1073741969</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
game_event
</summary>

```diff
+ minecraft:unequip
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
+ minecraft:sequence
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
+ minecraft:unequip
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:sequence
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
+ chat.tag.error: Server sent invalid message.
+ chat.validation_error: Chat validation error
```

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
- minecraft/textures/gui/sprites/bundle/background.png.mcmeta
+ minecraft/textures/gui/sprites/container/bundle/background.png.mcmeta
+ minecraft/textures/gui/sprites/widget/scroller.png
+ minecraft/textures/gui/sprites/widget/scroller.png.mcmeta
+ minecraft/textures/gui/sprites/widget/text_field_highlighted.png
+ minecraft/textures/gui/sprites/widget/text_field_highlighted.png.mcmeta
+ minecraft/textures/gui/sprites/widget/text_field.png
+ minecraft/textures/gui/sprites/widget/text_field.png.mcmeta
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
- net.minecraft.package-info
+ XXX.advancements.critereon.EntitySubPredicate$Type
- XXX.advancements.critereon.EntitySubPredicate$Types
+ XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityVariantPredicate
- XXX.advancements.critereon.EntityVariantPredicate$SubPredicate
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingHookPredicate
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
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LightningBoltPredicate
+ XXX.advancements.critereon.LightningStrikeTrigger
- XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.MobEffectsPredicate$Builder
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.PickedUpItemTrigger
- XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.PlayerPredicate$StatMatcher
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.SlimePredicate
+ XXX.advancements.critereon.StartRidingTrigger
- XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BannerPatterns
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.BrushableBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.ChiseledBookShelfBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.ContainerOpenersCounter
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity$Decorations
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.HangingSignBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkShriekerBlockEntity
+ XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.AzaleaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.CherryTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.MangroveTreeGrower
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
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetFunction
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
- XXX.chunk.storage.ChunkScanAccess
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.DataCommands$StringProcessor
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
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
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.ScoreboardDisplaySlotFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsCounterFix$StatType
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
- XXX.datafix.schemas.package-info
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
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
+ XXX.datafix.schemas.V3448
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
+ XXX.dimension.end.DragonRespawnAnimation
- XXX.dimension.end.DragonRespawnAnimation$1
+ XXX.dimension.end.DragonRespawnAnimation$2
- XXX.dimension.end.DragonRespawnAnimation$3
+ XXX.dimension.end.DragonRespawnAnimation$4
- XXX.dimension.end.DragonRespawnAnimation$5
+ XXX.dimension.end.EndDragonFight
- XXX.dimension.end.EndDragonFight$Data
+ XXX.dimension.end.package-info
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
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.SculkPatchConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.CherryFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.rootplacers.AboveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacer
+ XXX.feature.rootplacers.package-info
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.AttachedToLeavesDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecorator$Context
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.CherryTrunkPlacer
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.gameevent.vibrations.VibrationSystem
- XXX.gameevent.vibrations.VibrationSystem$Data
+ XXX.gameevent.vibrations.VibrationSystem$Listener
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.gameevent.vibrations.VibrationSystem$User
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
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
- XXX.level.block.package-info
- XXX.level.block.SuspiciousEffectHolder$EffectEntry
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TorchflowerCropBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallHangingSignBlock
- XXX.level.block.WallHangingSignBlock$1
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$TicksToSave
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LevelChunkSection$1BlockCounter
+ XXX.level.chunk.LightChunk
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.MissingPaletteEntryException
+ XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
- XXX.level.chunk.Palette$Factory
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$Configuration
- XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PalettedContainer$Data
- XXX.level.chunk.PalettedContainer$Strategy
+ XXX.level.chunk.PalettedContainer$Strategy$1
- XXX.level.chunk.PalettedContainer$Strategy$2
+ XXX.level.chunk.PalettedContainerRO
- XXX.level.chunk.PalettedContainerRO$PackedData
+ XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.StructureAccess
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.dimension.BuiltinDimensionTypes
+ XXX.level.dimension.DimensionDefaults
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.DimensionType$MonsterSettings
- XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.LevelCallback
- XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.LevelEntityGetterAdapter
- XXX.level.entity.package-info
- XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
- XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager
- XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
- XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.DynamicGameEventListener
- XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EntityPositionSource$Type
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
- XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEvent$Context
- XXX.level.gameevent.GameEvent$ListenerInfo
+ XXX.level.gameevent.GameEventDispatcher
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListener$Holder
+ XXX.level.gameevent.GameEventListenerRegistry
- XXX.level.gameevent.GameEventListenerRegistry$1
+ XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$1
+ XXX.level.levelgen.DensityFunctions$Ap2
- XXX.level.levelgen.DensityFunctions$BeardifierMarker
+ XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
- XXX.level.levelgen.DensityFunctions$BlendAlpha
+ XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$BlendOffset
+ XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$Constant
+ XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.PositionalRandomFactory
- XXX.level.levelgen.RandomState
+ XXX.level.levelgen.RandomState$1
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$1Entry
+ XXX.level.levelgen.WorldDimensions$Complete
+ XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldOptions
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.ChunkSkyLightSources
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$SectionState
+ XXX.level.lighting.LayerLightSectionStorage$SectionType
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEngine
- XXX.level.lighting.LightEngine$QueueEntry
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightEngine$1
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.MapColor
- XXX.level.material.MapColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.Path$DebugData
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.portal.package-info
+ XXX.level.portal.PortalForcer
- XXX.level.portal.PortalInfo
+ XXX.level.portal.PortalShape
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.CollectingNeighborUpdater
- XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
+ XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
- XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
+ XXX.level.redstone.InstantNeighborUpdater
- XXX.level.redstone.NeighborUpdater
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
+ XXX.level.saveddata.SavedData
- XXX.level.saveddata.SavedData$Factory
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelSummary$SymlinkLevelSummary
+ XXX.level.storage.LevelVersion
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureCountTracker
+ XXX.levelgen.feature.FeatureCountTracker$1
- XXX.levelgen.feature.FeatureCountTracker$FeatureData
+ XXX.levelgen.feature.FeatureCountTracker$LevelData
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorPreset
- XXX.levelgen.flat.FlatLevelGeneratorPresets
+ XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
- XXX.levelgen.heightproviders.BiasedToBottomHeight
+ XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProvider
+ XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
- XXX.levelgen.heightproviders.TrapezoidHeight
+ XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
+ XXX.levelgen.heightproviders.WeightedListHeight
+ XXX.levelgen.material.MaterialRuleList
+ XXX.levelgen.material.package-info
- XXX.levelgen.material.WorldGenMaterialRule
+ XXX.levelgen.placement.BiomeFilter
- XXX.levelgen.placement.BlockPredicateFilter
+ XXX.levelgen.placement.CarvingMaskPlacement
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
+ XXX.levelgen.placement.HeightmapPlacement
- XXX.levelgen.placement.HeightRangePlacement
- XXX.levelgen.placement.InSquarePlacement
+ XXX.levelgen.placement.NoiseBasedCountPlacement
- XXX.levelgen.placement.NoiseThresholdCountPlacement
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacementContext
+ XXX.levelgen.placement.PlacementFilter
- XXX.levelgen.placement.PlacementModifier
+ XXX.levelgen.placement.PlacementModifierType
- XXX.levelgen.placement.RandomOffsetPlacement
+ XXX.levelgen.placement.RarityFilter
- XXX.levelgen.placement.RepeatingPlacement
+ XXX.levelgen.placement.SurfaceRelativeThresholdFilter
- XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.package-info
- XXX.levelgen.presets.WorldPreset
+ XXX.levelgen.presets.WorldPresets
- XXX.levelgen.presets.WorldPresets$Bootstrap
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
- XXX.levelgen.structure.Structure
+ XXX.levelgen.structure.Structure$GenerationContext
- XXX.levelgen.structure.Structure$GenerationStub
+ XXX.levelgen.structure.Structure$StructureSettings
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaType
+ XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FunctionReference
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetEnchantmentsFunction
- XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetEnchantmentsFunction$Serializer
+ XXX.loot.functions.SetInstrumentFunction$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.minecraft.network.BandwidthDebugMonitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.ClientPongPacketListener
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$1
+ XXX.minecraft.resources.RegistryOps$2
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Dummy
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.package-info
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext
+ XXX.minecraft.server.ServerFunctionManager$ExecutionContext$AbortingReturnValueConsumer
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
- XXX.minecraft.server.ServerInfo
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.Services
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.CatVariantTags
+ XXX.minecraft.tags.DamageTypeTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FlatLevelGeneratorPresetTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.InstrumentTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
- XXX.minecraft.tags.PaintingVariantTags
+ XXX.minecraft.tags.PoiTypeTags
- XXX.minecraft.tags.StructureTags
+ XXX.minecraft.tags.TagBuilder
- XXX.minecraft.tags.TagEntry
+ XXX.minecraft.tags.TagEntry$Lookup
- XXX.minecraft.tags.TagFile
+ XXX.minecraft.tags.TagKey
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagLoader$1
- XXX.minecraft.tags.TagLoader$EntryWithSource
+ XXX.minecraft.tags.TagLoader$SortingEntry
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.ArrayListDeque
- XXX.minecraft.util.ArrayListDeque$DescendingIterator
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
- XXX.minecraft.util.ByIdMap$1
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$RecursiveCodec
+ XXX.minecraft.util.FutureChain
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
- XXX.minecraft.util.ResourceLocationPattern
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
+ XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
- XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$Info
+ XXX.packs.repository.Pack$Position
- XXX.packs.repository.Pack$ResourcesSupplier
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackDetector
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.PackSource
+ XXX.packs.repository.PackSource$1
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
+ XXX.packs.resources.CloseableResourceManager
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
- XXX.packs.resources.FallbackResourceManager$EntryStack
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.FallbackResourceManager$PackEntry
+ XXX.packs.resources.FallbackResourceManager$ResourceWithSource
- XXX.packs.resources.IoSupplier
+ XXX.packs.resources.MultiPackResourceManager
- XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceFilterSection
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceMetadata
- XXX.packs.resources.ResourceMetadata$1
+ XXX.packs.resources.ResourceMetadata$2
- XXX.packs.resources.ResourceMetadata$Builder
+ XXX.packs.resources.ResourceMetadata$Builder$1
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
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
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
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
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntent$1
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
- XXX.protocol.login.ServerboundCustomQueryAnswerPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerboundLoginAcknowledgedPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$InlineSerializer
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
- XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.nbt.StorageNbtProvider$Serializer
+ XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$Serializer
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
+ XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ XXX.providers.score.FixedScoreboardNameProvider
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$CommandFunction
+ XXX.server.commands.CloneCommands$DimensionAndPosition
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DamageCommand
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugCommand$Tracer
+ XXX.server.commands.DebugConfigCommand
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
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$FunctionResult
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
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
- XXX.server.commands.PerfCommand
+ XXX.server.commands.PlaceCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RandomCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
+ XXX.server.commands.ReturnCommand
- XXX.server.commands.RideCommand
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
- XXX.server.commands.SpawnArmorTrimsCommand
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
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
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
- XXX.server.level.ChunkHolder$ChunkSaveDebug
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkLevel
- XXX.server.level.ChunkLevel$1
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FullChunkStatus
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$ChunkAndHolder
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TickingTracker
- XXX.server.level.WorldGenRegion
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.PlayerChunkSender
+ XXX.server.network.ServerCommonPacketListenerImpl
- XXX.server.network.ServerConfigurationPacketListenerImpl
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerGamePacketListenerImpl$2
+ XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilterClient
- XXX.server.network.TextFilterClient$IgnoreStrategy
+ XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
- XXX.server.network.TextFilterClient$MessageEncoder
+ XXX.server.network.TextFilterClient$PlayerContext
- XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
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
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockSetType
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ChestType$1
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntRange$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootDataManager$CompositePredicate
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.Serializer
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
- XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
+ XXX.structure.placement.StructurePlacement$FrequencyReducer
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
+ XXX.structure.placement.StructurePlacementType
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
+ XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidPiece
+ XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces
+ XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$2
+ XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$4
+ XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityPieces$SectionGenerator
+ XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces
+ XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.IglooStructure
+ XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JigsawStructure$1
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.package-info
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
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
- XXX.world.level.package-info
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +1P
```
```
XXX.minecraft.advancements.CriterionTriggerInstance +1P -1P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger +2M -2M
```
```
XXX.advancements.critereon.BlockPredicate +11M -4M | +6P -5P
```
```
XXX.advancements.critereon.BredAnimalsTrigger +2M -2M
```
```
XXX.advancements.critereon.BrewedPotionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger +2M -2M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger +2M -2M
```
```
XXX.advancements.critereon.ConstructBeaconTrigger +2M -2M
```
```
XXX.advancements.critereon.ConsumeItemTrigger +2M -2M
```
```
XXX.advancements.critereon.ContextAwarePredicate +4M -5M | +1P -2P
```
```
XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance +4M -2M | +2P -2P
```
```
XXX.advancements.critereon.DamagePredicate$Builder +1M -1M | +3P -3P
```
```
XXX.advancements.critereon.DamageSourcePredicate$Builder +1M -3M | +2P -2P
```
```
XXX.advancements.critereon.DistancePredicate +10M -1M | +1P -1P
```
```
XXX.advancements.critereon.DistanceTrigger$TriggerInstance +5M -3M | +2P -2P
```
```
XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance +6M -4M | +2P -2P
```
```
XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.EnterBlockTrigger +5M -4M
```
```
XXX.advancements.critereon.EntityEquipmentPredicate +12M -3M | +7P -7P
```
```
XXX.advancements.critereon.EntityFlagsPredicate +11M -5M | +6P -6P
```
```
XXX.advancements.critereon.EntityHurtPlayerTrigger +2M -2M
```
```
XXX.advancements.critereon.EntityPredicate +29M -7M | +14P -14P
```
```
XXX.advancements.critereon.EntitySubPredicate +1M -2M | +1P -2P
```
```
XXX.advancements.critereon.EntityTypePredicate +11M -3M | +2P -4P
```
```
XXX.advancements.critereon.LootTableTrigger +2M -2M
```
```
XXX.advancements.critereon.MinMaxBounds +8M -7M | +2P -2P
```
```
XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory +1P -1P
```
```
XXX.advancements.critereon.MinMaxBounds$Ints +15M -4M | +5P -2P
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance +3M -3M
```
```
XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance +3M -2M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.TameAnimalTrigger +2M -2M
```
```
XXX.advancements.critereon.TargetBlockTrigger +2M -2M
```
```
XXX.advancements.critereon.TradeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedEnderEyeTrigger +2M -2M
```
```
XXX.advancements.critereon.UsedTotemTrigger +2M -2M
```
```
XXX.advancements.critereon.UsingItemTrigger +2M -2M
```
```
XXX.advancements.critereon.WrappedMinMaxBounds +5M -2M
```
```
XXX.minecraft.core.HolderSet +1M -1M
```
```
XXX.minecraft.core.Registry -1M
```
```
XXX.core.registries.BuiltInRegistries +1M
```
```
XXX.data.recipes.RecipeProvider +3M
```
```
XXX.minecraft.nbt.TagParser +1M | +1P
```
```
XXX.minecraft.network.Connection +3M -4M | +1P
```
```
XXX.network.chat.RemoteChatSession +2M -1M
```
```
XXX.network.chat.SignedMessageValidator$KeyBased +2M -1M | +1P
```
```
XXX.world.effect.MobEffect +1M -3M | +1P
```
```
XXX.world.effect.MobEffects +1M -1M
```
```
XXX.world.entity.LivingEntity +1P
```
```
XXX.ai.attributes.AttributeModifier$Operation +2M -1M | +2P
```
```
XXX.entity.animal.MushroomCow +3M -1M | +2P -2P
```
```
XXX.world.inventory.AbstractFurnaceMenu +2M -2M
```
```
XXX.world.item.ItemStack +1M
```
```
XXX.storage.loot.LootDataManager -2M | +1P
```
```
XXX.storage.loot.LootPool +9M -2M | +4P -3P
```
```
XXX.loot.entries.AlternativesEntry$Builder +1P -1P
```
```
XXX.loot.entries.CompositeEntryBase +4M -2M | +2P -2P
```
```
XXX.loot.entries.LootPoolEntryContainer$Builder +1M -1M | +1P -1P
```
```
XXX.loot.entries.LootTableReference +7M -4M | +1P
```
```
XXX.loot.functions.ApplyBonusCount +10M -5M | +4P -1P
```
```
XXX.loot.functions.ApplyBonusCount$UniformBonusCount +6M -3M | +2P -1P
```
```
XXX.loot.functions.CopyNameFunction +5M -2M | +1P
```
```
XXX.loot.functions.EnchantWithLevelsFunction +5M -1M | +1P
```
```
XXX.loot.functions.FillPlayerHead +5M -2M | +1P
```
```
XXX.loot.functions.LootItemFunctions +5M -5M | +3P
```
```
XXX.loot.functions.SetAttributesFunction +6M -3M | +1P
```
```
XXX.loot.functions.SetBannerPatternFunction +5M -1M | +2P
```
```
XXX.loot.functions.SetContainerLootTable +8M -3M | +2P -1P
```
```
XXX.loot.functions.SetNameFunction +10M -5M | +3P -2P
```
```
XXX.loot.functions.SetPotionFunction +5M -2M | +2P -1P
```
```
XXX.loot.parameters.LootContextParamSets +6M -5M | +1P
```
```
XXX.loot.predicates.AllOfCondition$Builder +1M -1M
```
```
XXX.loot.predicates.ConditionReference +8M -3M | +1P
```
```
XXX.loot.predicates.EntityHasScoreCondition$Builder +1P -1P
```
```
XXX.loot.predicates.InvertedLootItemCondition +7M -1M | +1P
```
```
XXX.loot.predicates.LootItemBlockStatePropertyCondition +12M -1M | +3P -2P
```
```
XXX.loot.predicates.TimeCheck$Builder +1P -1P
```
```
XXX.loot.predicates.WeatherCheck +8M -1M | +3P -2P
```
```
XXX.providers.number.BinomialDistributionGenerator +7M | +1P
```
```
XXX.providers.number.UniformGenerator +7M | +1P
```
```
XXX.providers.score.LootScoreProviderType +5M -1M | +1P
```
```
XXX.providers.score.ScoreboardNameProviders +4M -2M | +2P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- BeeNestDestroyedTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ BlockPredicate fromJson(JsonElement)
- boolean equals(Object)
- int hashCode()
+ JsonElement serializeToJson()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- List lambda$static$0(HolderSet)
- Optional blocks()
- Optional nbt()
- Optional of(Optional,Optional,Optional,Optional)
- Optional properties()
- Optional tag()
- String toString()
- void <init>(Optional,Optional,Optional,Optional)
+ void <init>(TagKey,Set,StatePropertiesPredicate,NbtPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- BredAnimalsTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- BrewedPotionTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- ChangeDimensionTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- ChanneledLightningTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- ConstructBeaconTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- ConsumeItemTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ContextAwarePredicate
</summary>

```diff
+ ContextAwarePredicate fromElement(String,DeserializationContext,JsonElement,LootContextParamSet)
- JsonElement toJson()
+ JsonElement toJson(ContextAwarePredicate[],SerializationContext)
- JsonElement toJson(List)
+ JsonElement toJson(SerializationContext)
- Optional fromElement(String,DeserializationContext,JsonElement,LootContextParamSet)
+ void <clinit>()
- void <init>(List)
+ void <init>(LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate,ContextAwarePredicate)
- void <init>(Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
- void lambda$serializeToJson$1(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DamagePredicate$Builder
</summary>

```diff
+ DamagePredicate build()
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
</summary>

```diff
+ DamageSourcePredicate build()
+ DamageSourcePredicate$Builder direct(EntityPredicate)
+ DamageSourcePredicate$Builder source(EntityPredicate)
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DistancePredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ DistancePredicate fromJson(JsonElement)
- int hashCode()
- MinMaxBounds$Doubles absolute()
- MinMaxBounds$Doubles horizontal()
- MinMaxBounds$Doubles x()
- MinMaxBounds$Doubles y()
- MinMaxBounds$Doubles z()
- Optional fromJson(JsonElement)
- String toString()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DistanceTrigger$TriggerInstance
</summary>

```diff
+ DistanceTrigger$TriggerInstance fallFromHeight(EntityPredicate$Builder,DistancePredicate,LocationPredicate)
- DistanceTrigger$TriggerInstance fallFromHeight(EntityPredicate$Builder,DistancePredicate,LocationPredicate$Builder)
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ResourceLocation,ContextAwarePredicate,LocationPredicate,DistancePredicate)
- void <init>(ResourceLocation,Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,LocationPredicate)
- void lambda$serializeToJson$1(JsonObject,DistancePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
</summary>

```diff
+ EffectsChangedTrigger$TriggerInstance gotEffectsFrom(EntityPredicate)
- EffectsChangedTrigger$TriggerInstance gotEffectsFrom(Optional)
+ EffectsChangedTrigger$TriggerInstance hasEffects(MobEffectsPredicate)
- EffectsChangedTrigger$TriggerInstance hasEffects(MobEffectsPredicate$Builder)
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,MobEffectsPredicate,ContextAwarePredicate)
- void <init>(Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,MobEffectsPredicate)
- void lambda$serializeToJson$1(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ItemPredicate,MinMaxBounds$Ints)
- void <init>(Optional,Optional,MinMaxBounds$Ints)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnterBlockTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ boolean lambda$trigger$2(BlockState,EnterBlockTrigger$TriggerInstance)
- boolean lambda$trigger$3(BlockState,EnterBlockTrigger$TriggerInstance)
+ EnterBlockTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- EnterBlockTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ JsonSyntaxException lambda$deserializeBlock$1(ResourceLocation)
- JsonSyntaxException lambda$deserializeBlock$2(ResourceLocation)
- void lambda$createInstance$1(Block,StatePropertiesPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ EntityEquipmentPredicate fromJson(JsonElement)
- int hashCode()
+ JsonElement serializeToJson()
- Optional chest()
- Optional feet()
- Optional head()
- Optional legs()
- Optional mainhand()
- Optional of(Optional,Optional,Optional,Optional,Optional,Optional)
- Optional offhand()
- String toString()
+ void <init>(ItemPredicate,ItemPredicate,ItemPredicate,ItemPredicate,ItemPredicate,ItemPredicate)
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityFlagsPredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ Boolean getOptionalBoolean(JsonObject,String)
+ EntityFlagsPredicate fromJson(JsonElement)
- int hashCode()
+ JsonElement serializeToJson()
- Optional isBaby()
- Optional isCrouching()
- Optional isOnFire()
- Optional isSprinting()
- Optional isSwimming()
- Optional of(Optional,Optional,Optional,Optional,Optional)
- String toString()
+ void <init>(Boolean,Boolean,Boolean,Boolean,Boolean)
- void <init>(Optional,Optional,Optional,Optional,Optional)
+ void addOptionalBoolean(JsonObject,String,Boolean)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ EntityHurtPlayerTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- EntityHurtPlayerTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate
</summary>

```diff
- App lambda$static$0(Codec,RecordCodecBuilder$Instance)
- boolean equals(Object)
+ boolean lambda$matches$0(ServerLevel,Vec3,Entity)
- boolean lambda$matches$3(ServerLevel,Vec3,Entity)
- Codec lambda$static$1(Codec)
+ ContextAwarePredicate fromElement(String,DeserializationContext,JsonElement)
+ ContextAwarePredicate fromJson(JsonObject,String,DeserializationContext)
+ ContextAwarePredicate[] fromJsonArray(JsonObject,String,DeserializationContext)
+ EntityPredicate fromJson(JsonElement)
- int hashCode()
- List fromJsonArray(JsonObject,String,DeserializationContext)
- List wrap(EntityPredicate$Builder[])
- Optional distanceToPlayer()
- Optional effects()
- Optional entityType()
- Optional equipment()
- Optional flags()
- Optional fromElement(String,DeserializationContext,JsonElement)
- Optional fromJson(JsonElement)
- Optional fromJson(JsonObject,String,DeserializationContext)
- Optional location()
- Optional nbt()
- Optional of(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
- Optional passenger()
- Optional steppingOnLocation()
- Optional subPredicate()
- Optional targetedEntity()
- Optional team()
- Optional vehicle()
- Optional wrap(EntityPredicate$Builder)
- Optional wrap(Optional)
- Stream lambda$wrap$2(EntityPredicate$Builder)
- String toString()
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,EntitySubPredicate,EntityPredicate,EntityPredicate,EntityPredicate,String)
+ void <init>(EntityTypePredicate,DistancePredicate,LocationPredicate,LocationPredicate,MobEffectsPredicate,NbtPredicate,EntityFlagsPredicate,EntityEquipmentPredicate,EntitySubPredicate,String)
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntitySubPredicate
</summary>

```diff
- Codec lambda$static$0(EntitySubPredicate$Type)
+ EntitySubPredicate fromJson(JsonElement)
+ JsonElement serialize()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityTypePredicate
</summary>

```diff
- boolean equals(Object)
- boolean matches(EntityType)
- DataResult lambda$static$4(EntityTypePredicate)
+ EntityTypePredicate fromJson(JsonElement)
- EntityTypePredicate lambda$static$0(TagKey)
- EntityTypePredicate lambda$static$1(Holder)
- EntityTypePredicate lambda$static$2(Either)
- HolderSet types()
- int hashCode()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- String lambda$static$3(HolderSet)
- String toString()
+ void <init>()
- void <init>(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ LootTableTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- LootTableTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MinMaxBounds
</summary>

```diff
- App lambda$createCodec$0(Codec,MinMaxBounds$BoundsFactory,RecordCodecBuilder$Instance)
- Codec createCodec(Codec,MinMaxBounds$BoundsFactory)
- Either lambda$createCodec$4(MinMaxBounds)
+ JsonElement serializeToJson()
+ MinMaxBounds fromJson(JsonElement,MinMaxBounds,BiFunction,MinMaxBounds$BoundsFactory)
- MinMaxBounds lambda$createCodec$1(MinMaxBounds)
- MinMaxBounds lambda$createCodec$2(MinMaxBounds$BoundsFactory,Number)
- MinMaxBounds lambda$createCodec$3(MinMaxBounds$BoundsFactory,Either)
+ Number getMax()
+ Number getMin()
+ Number readNumber(StringReader,Function,Supplier)
+ Object optionallyFormat(Object,Function)
- Optional readNumber(StringReader,Function,Supplier)
- Optional unwrapPoint()
+ void <init>(Number,Number)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MinMaxBounds$Ints
</summary>

```diff
- boolean equals(Object)
- int hashCode()
+ Integer lambda$fromReader$0(Integer)
- Integer lambda$fromReader$2(Integer)
- JsonElement serializeToJson()
- Long lambda$new$1(Integer)
- Long lambda$squareOpt$0(Integer)
+ Long squareOpt(Integer)
+ MinMaxBounds$Ints create(StringReader,Integer,Integer)
- MinMaxBounds$Ints create(StringReader,Optional,Optional)
- Optional max()
- Optional maxSq()
- Optional min()
- Optional minSq()
- Optional squareOpt(Optional)
- String toString()
+ void <init>(Integer,Integer)
- void <init>(Optional,Optional,Optional,Optional)
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
+ PlayerTrigger$TriggerInstance located(EntityPredicate)
+ PlayerTrigger$TriggerInstance located(LocationPredicate)
- PlayerTrigger$TriggerInstance located(LocationPredicate$Builder)
- PlayerTrigger$TriggerInstance located(Optional)
+ void <init>(ResourceLocation,ContextAwarePredicate)
- void <init>(ResourceLocation,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
- Stream lambda$craftedItem$0(ItemPredicate$Builder)
+ void <init>(ContextAwarePredicate,ResourceLocation,List)
- void <init>(Optional,ResourceLocation,List)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ResourceLocation)
- void <init>(Optional,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TameAnimalTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ TameAnimalTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- TameAnimalTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TargetBlockTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ TargetBlockTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- TargetBlockTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TradeTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ TradeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- TradeTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedEnderEyeTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- UsedEnderEyeTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedTotemTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ UsedTotemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- UsedTotemTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsingItemTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ UsingItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- UsingItemTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.WrappedMinMaxBounds
</summary>

```diff
- boolean equals(Object)
+ Float getMax()
+ Float getMin()
- Float max()
- Float min()
- int hashCode()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.core.HolderSet
</summary>

```diff
- HolderSet$Direct direct(Function,Collection)
+ HolderSet$Direct direct(Function,List)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ Object registerMapping(Registry,int,String,Object)
```

</details>
<details>
<summary>
net.minecraft.core.registries.BuiltInRegistries
</summary>

```diff
- Registry registerSimpleWithIntrusiveHolders(ResourceKey,BuiltInRegistries$RegistryBootstrap)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- InventoryChangeTrigger$TriggerInstance inventoryTrigger(ItemPredicate$Builder[])
- ItemPredicate[] lambda$inventoryTrigger$25(int)
- Stream lambda$inventoryTrigger$24(ItemPredicate$Builder)
```

</details>
<details>
<summary>
net.minecraft.nbt.TagParser
</summary>

```diff
- DataResult lambda$static$3(String)
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
- Connection connectToServer(InetSocketAddress,boolean,SampleLogger)
+ Connection connectToServer(InetSocketAddress,boolean)
- void configureSerialization(ChannelPipeline,PacketFlow,BandwidthDebugMonitor)
+ void configureSerialization(ChannelPipeline,PacketFlow)
+ void sendNoFlush(Packet,PacketSendListener)
+ void sendNoFlush(Packet)
- void setBandwidthLogger(SampleLogger)
```

</details>
<details>
<summary>
net.minecraft.network.chat.RemoteChatSession
</summary>

```diff
- boolean lambda$createMessageValidator$0(Duration)
+ SignedMessageValidator createMessageValidator()
- SignedMessageValidator createMessageValidator(Duration)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator$KeyBased
</summary>

```diff
- boolean validate(PlayerChatMessage)
- void <init>(SignatureValidator,BooleanSupplier)
+ void <init>(SignatureValidator)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffect
</summary>

```diff
- Holder$Reference builtInRegistryHolder()
+ int getId(MobEffect)
+ int getIdFromNullable(MobEffect)
+ MobEffect byId(int)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffects
</summary>

```diff
+ MobEffect register(int,String,MobEffect)
- MobEffect register(String,MobEffect)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
</summary>

```diff
- String getSerializedName()
+ void <init>(String,int,int)
- void <init>(String,int,String,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.MushroomCow
</summary>

```diff
+ Optional getEffectFromItemStack(ItemStack)
- Optional getEffectsFromItemStack(ItemStack)
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
- void lambda$readAdditionalSaveData$2(List)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractFurnaceMenu
</summary>

```diff
- float getBurnProgress()
- float getLitProgress()
+ int getBurnProgress()
+ int getLitProgress()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- boolean is(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootDataManager
</summary>

```diff
+ LootItemCondition createComposite(LootItemCondition[])
+ LootItemFunction createComposite(LootItemFunction[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootPool
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- List lambda$static$0(LootPool)
- List lambda$static$1(LootPool)
- List lambda$static$2(LootPool)
- NumberProvider lambda$static$3(LootPool)
- NumberProvider lambda$static$4(LootPool)
- void <clinit>()
- void <init>(List,List,List,NumberProvider,NumberProvider)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[],LootItemFunction[],NumberProvider,NumberProvider)
+ void lambda$addRandomItem$0(LootContext,List,MutableInt,LootPoolEntry)
- void lambda$addRandomItem$6(LootContext,List,MutableInt,LootPoolEntry)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
</summary>

```diff
- App lambda$createCodec$1(CompositeEntryBase$CompositeEntryConstructor,RecordCodecBuilder$Instance)
- Codec createCodec(CompositeEntryBase$CompositeEntryConstructor)
- List lambda$createCodec$0(CompositeEntryBase)
+ LootPoolEntryContainer$Serializer createSerializer(CompositeEntryBase$CompositeEntryConstructor)
- void <init>(List,List)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
</summary>

```diff
- List getConditions()
+ LootItemCondition[] getConditions()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootTableReference
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ LootPoolSingletonContainer lambda$lootTableReference$2(ResourceLocation,int,int,LootItemCondition[],LootItemFunction[])
- LootPoolSingletonContainer lambda$lootTableReference$4(ResourceLocation,int,int,List,List)
- ResourceLocation lambda$static$0(LootTableReference)
- void <clinit>()
- void <init>(ResourceLocation,int,int,List,List)
+ void <init>(ResourceLocation,int,int,LootItemCondition[],LootItemFunction[])
+ void lambda$validate$0(ValidationContext,LootDataId,LootTable)
+ void lambda$validate$1(ValidationContext)
- void lambda$validate$2(ValidationContext,LootDataId,LootTable)
- void lambda$validate$3(ValidationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- ApplyBonusCount$Formula lambda$static$3(ApplyBonusCount)
- DataResult lambda$static$1(ResourceLocation)
- Holder lambda$static$2(ApplyBonusCount)
+ LootItemFunction lambda$addBonusBinomialDistributionCount$0(Enchantment,int,float,LootItemCondition[])
- LootItemFunction lambda$addBonusBinomialDistributionCount$5(Enchantment,int,float,List)
+ LootItemFunction lambda$addOreBonusCount$1(Enchantment,LootItemCondition[])
- LootItemFunction lambda$addOreBonusCount$6(Enchantment,List)
+ LootItemFunction lambda$addUniformBonusCount$2(Enchantment,LootItemCondition[])
+ LootItemFunction lambda$addUniformBonusCount$3(Enchantment,int,LootItemCondition[])
- LootItemFunction lambda$addUniformBonusCount$7(Enchantment,List)
- LootItemFunction lambda$addUniformBonusCount$8(Enchantment,int,List)
- String lambda$static$0(ResourceLocation)
- void <init>(List,Holder,ApplyBonusCount$Formula)
+ void <init>(LootItemCondition[],Enchantment,ApplyBonusCount$Formula)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ ApplyBonusCount$Formula deserialize(JsonObject,JsonDeserializationContext)
- ApplyBonusCount$FormulaType getType()
- boolean equals(Object)
- int bonusMultiplier()
- int hashCode()
+ ResourceLocation getType()
- String toString()
+ void serializeParams(JsonObject,JsonSerializationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNameFunction
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- CopyNameFunction$NameSource lambda$static$0(CopyNameFunction)
+ LootItemFunction lambda$copyName$0(CopyNameFunction$NameSource,LootItemCondition[])
- LootItemFunction lambda$copyName$2(CopyNameFunction$NameSource,List)
- void <clinit>()
- void <init>(List,CopyNameFunction$NameSource)
+ void <init>(LootItemCondition[],CopyNameFunction$NameSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(EnchantWithLevelsFunction)
- NumberProvider lambda$static$0(EnchantWithLevelsFunction)
- void <clinit>()
- void <init>(List,NumberProvider,boolean)
+ void <init>(LootItemCondition[],NumberProvider,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.FillPlayerHead
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- LootContext$EntityTarget lambda$static$0(FillPlayerHead)
+ LootItemFunction lambda$fillPlayerHead$0(LootContext$EntityTarget,LootItemCondition[])
- LootItemFunction lambda$fillPlayerHead$2(LootContext$EntityTarget,List)
- void <clinit>()
- void <init>(List,LootContext$EntityTarget)
+ void <init>(LootItemCondition[],LootContext$EntityTarget)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootItemFunctions
</summary>

```diff
+ BiFunction compose(BiFunction[])
- BiFunction compose(List)
- Codec lambda$static$1()
+ ItemStack lambda$compose$1(BiFunction,BiFunction,ItemStack,LootContext)
- ItemStack lambda$compose$2(BiFunction,BiFunction,ItemStack,LootContext)
+ ItemStack lambda$compose$2(BiFunction[],ItemStack,LootContext)
- ItemStack lambda$compose$3(List,ItemStack,LootContext)
- LootItemFunctionType register(String,Codec)
+ LootItemFunctionType register(String,Serializer)
+ Object createGsonAdapter()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- List lambda$static$0(SetAttributesFunction)
+ SetAttributesFunction$ModifierBuilder modifier(String,Attribute,AttributeModifier$Operation,NumberProvider)
- SetAttributesFunction$ModifierBuilder modifier(String,Holder,AttributeModifier$Operation,NumberProvider)
+ Stream lambda$getReferencedContextParams$0(SetAttributesFunction$Modifier)
- Stream lambda$getReferencedContextParams$2(SetAttributesFunction$Modifier)
- void <clinit>()
- void <init>(List,List)
+ void <init>(LootItemCondition[],List)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(SetBannerPatternFunction)
- List lambda$static$0(SetBannerPatternFunction)
- void <clinit>()
- void <init>(List,List,boolean)
+ void <init>(LootItemCondition[],List,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Holder lambda$static$2(SetContainerLootTable)
- Long lambda$static$1(SetContainerLootTable)
+ LootItemFunction lambda$withLootTable$0(ResourceLocation,BlockEntityType,LootItemCondition[])
+ LootItemFunction lambda$withLootTable$1(ResourceLocation,long,BlockEntityType,LootItemCondition[])
- LootItemFunction lambda$withLootTable$4(ResourceLocation,BlockEntityType,List)
- LootItemFunction lambda$withLootTable$5(ResourceLocation,long,BlockEntityType,List)
- ResourceLocation lambda$static$0(SetContainerLootTable)
- void <clinit>()
- void <init>(List,ResourceLocation,long,Holder)
+ void <init>(LootItemCondition[],ResourceLocation,long,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetNameFunction
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Component lambda$createResolver$0(CommandSourceStack,Entity,Component)
+ Component lambda$createResolver$1(Component)
- Component lambda$createResolver$4(CommandSourceStack,Entity,Component)
- Component lambda$createResolver$5(Component)
+ LootItemFunction lambda$setName$2(Component,LootItemCondition[])
+ LootItemFunction lambda$setName$3(Component,LootContext$EntityTarget,LootItemCondition[])
- LootItemFunction lambda$setName$7(Component,List)
- LootItemFunction lambda$setName$8(Component,LootContext$EntityTarget,List)
- Optional lambda$static$0(SetNameFunction)
- Optional lambda$static$1(SetNameFunction)
- Set lambda$getReferencedContextParams$3(LootContext$EntityTarget)
- void <init>(List,Optional,Optional)
+ void <init>(LootItemCondition[],Component,LootContext$EntityTarget)
- void lambda$run$6(ItemStack,LootContext,Component)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetPotionFunction
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- Holder lambda$static$0(SetPotionFunction)
+ LootItemFunction lambda$setPotion$0(Potion,LootItemCondition[])
- LootItemFunction lambda$setPotion$2(Potion,List)
- void <clinit>()
- void <init>(List,Holder)
+ void <init>(LootItemCondition[],Potion)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
</summary>

```diff
- DataResult lambda$static$1(ResourceLocation)
- DataResult lambda$static$2(ResourceLocation)
+ LootContextParamSet get(ResourceLocation)
+ ResourceLocation getKey(LootContextParamSet)
- String lambda$static$0(ResourceLocation)
+ void lambda$static$0(LootContextParamSet$Builder)
+ void lambda$static$1(LootContextParamSet$Builder)
- void lambda$static$14(LootContextParamSet$Builder)
- void lambda$static$15(LootContextParamSet$Builder)
- void lambda$static$16(LootContextParamSet$Builder)
+ void lambda$static$2(LootContextParamSet$Builder)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
</summary>

```diff
- LootItemCondition create(List)
+ LootItemCondition create(LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.ConditionReference
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
+ LootItemCondition lambda$conditionReference$2(ResourceLocation)
- LootItemCondition lambda$conditionReference$3(ResourceLocation)
- ResourceLocation name()
- String toString()
+ void lambda$validate$0(ValidationContext,LootDataId,LootItemCondition)
- void lambda$validate$1(ValidationContext,LootDataId,LootItemCondition)
+ void lambda$validate$1(ValidationContext)
- void lambda$validate$2(ValidationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
+ LootItemCondition lambda$invert$0(InvertedLootItemCondition)
- LootItemCondition lambda$invert$1(InvertedLootItemCondition)
- LootItemCondition term()
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- DataResult lambda$validate$3(LootItemBlockStatePropertyCondition,String)
- DataResult validate(LootItemBlockStatePropertyCondition)
- Holder block()
- int hashCode()
- Optional lambda$validate$1(LootItemBlockStatePropertyCondition,StatePropertiesPredicate)
- Optional properties()
- String lambda$validate$2(LootItemBlockStatePropertyCondition,String)
- String toString()
- void <clinit>()
+ void <init>(Block,StatePropertiesPredicate)
- void <init>(Holder,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.WeatherCheck
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
- Optional isRaining()
- Optional isThundering()
- String toString()
- void <clinit>()
+ void <init>(Boolean,Boolean)
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
- NumberProvider n()
- NumberProvider p()
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
- NumberProvider max()
- NumberProvider min()
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
</summary>

```diff
- boolean equals(Object)
- Codec codec()
- int hashCode()
- String toString()
- void <init>(Codec)
+ void <init>(Serializer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
</summary>

```diff
- Codec lambda$static$2()
- Either lambda$static$1(ScoreboardNameProvider)
- LootScoreProviderType register(String,Codec)
+ LootScoreProviderType register(String,Serializer)
+ Object createGsonAdapter()
- ScoreboardNameProvider lambda$static$0(Either)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
+ XXX.advancements.critereon.EntitySubPredicate$1
- XXX.advancements.critereon.EntitySubPredicate$Type
+ XXX.advancements.critereon.EntitySubPredicate$Types
- XXX.advancements.critereon.EntitySubPredicate$Types$1
+ XXX.advancements.critereon.EntityTypePredicate$1
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.EntityVariantPredicate
+ XXX.advancements.critereon.EntityVariantPredicate$1
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger
- XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LighthingBoltPredicate
- XXX.advancements.critereon.LightningStrikeTrigger
+ XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationPredicate$PositionPredicate
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.PickedUpItemTrigger
+ XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.SerializationContext
- XXX.advancements.critereon.ShotCrossbowTrigger
+ XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.SimpleCriterionTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.SlimePredicate
- XXX.advancements.critereon.StartRidingTrigger
+ XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedMatcher
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotBlockEntity$Decorations
+ XXX.block.entity.DecoratedPotPatterns
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.HangingSignBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkCatalystBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity$CatalystListener
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationUser
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.SculkShriekerBlockEntity$VibrationUser
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SignText
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.AzaleaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.CherryTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.MangroveTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetFunction
- XXX.block.state.BlockBehaviour$OffsetType
+ XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StateArgumentPredicate
+ XXX.block.state.BlockBehaviour$StatePredicate
- XXX.block.state.BlockState
- XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.block.state.StateHolder$1
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.client.gui.package-info
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$QuickPlayData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableHierarchicalModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AllayModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.AxolotlModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BookModel
+ XXX.client.model.CamelModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestBoatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChestRaftModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HierarchicalModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.OcelotModel
+ XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$1
+ XXX.client.model.ParrotModel$State
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RaftModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SkullModelBase
+ XXX.client.model.SlimeModel
- XXX.client.model.SnifferModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WaterPatchModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.AccountProfileKeyPairManager
+ XXX.client.multiplayer.ChunkReceiveSpeedAccumulator
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientCommonPacketListenerImpl
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
- XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.CommonListenerCookie
- XXX.client.multiplayer.LegacyServerPinger
+ XXX.client.multiplayer.LegacyServerPinger$Output
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.DataCommands$StringProcessor
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
- XXX.components.debugchart.BandwidthDebugChart
- XXX.components.debugchart.PingDebugChart
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.package-info
- XXX.components.tabs.Tab
+ XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar
+ XXX.components.tabs.TabNavigationBar$Builder
+ XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
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
- XXX.datafix.fixes.RandomSequenceSettingsFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemapChunkStatusFix
- XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.ScoreboardDisplaySlotFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsCounterFix$StatType
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
+ XXX.datafix.schemas.package-info
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
+ XXX.datafix.schemas.V3325
- XXX.datafix.schemas.V3326
+ XXX.datafix.schemas.V3327
- XXX.datafix.schemas.V3328
+ XXX.datafix.schemas.V3438
- XXX.datafix.schemas.V3448
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
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.EndDragonFight$Data
- XXX.dimension.end.package-info
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
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
+ XXX.feature.foliageplacers.CherryFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.package-info
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.AttachedToLeavesDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$Effect
- XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Definition
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
- XXX.font.providers.GlyphProviderDefinition
+ XXX.font.providers.GlyphProviderDefinition$Loader
- XXX.font.providers.GlyphProviderDefinition$Reference
+ XXX.font.providers.GlyphProviderType
- XXX.font.providers.package-info
- XXX.font.providers.ProviderReferenceDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ XXX.font.providers.UnihexProvider
- XXX.font.providers.UnihexProvider$ByteContents
+ XXX.font.providers.UnihexProvider$Definition
- XXX.font.providers.UnihexProvider$Dimensions
+ XXX.font.providers.UnihexProvider$Glyph
- XXX.font.providers.UnihexProvider$Glyph$1
+ XXX.font.providers.UnihexProvider$IntContents
- XXX.font.providers.UnihexProvider$LineData
+ XXX.font.providers.UnihexProvider$OverrideRange
- XXX.font.providers.UnihexProvider$ReaderOutput
+ XXX.font.providers.UnihexProvider$ShortContents
+ XXX.gameevent.vibrations.package-info
- XXX.gameevent.vibrations.VibrationInfo
+ XXX.gameevent.vibrations.VibrationSelector
- XXX.gameevent.vibrations.VibrationSystem
+ XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Listener
+ XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.gameevent.vibrations.VibrationSystem$User
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
- XXX.gui.components.package-info
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.CodepointMap
- XXX.gui.font.CodepointMap$Output
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$BuilderId
+ XXX.gui.font.FontManager$BuilderResult
- XXX.gui.font.FontManager$FontDefinitionFile
+ XXX.gui.font.FontManager$Preparation
- XXX.gui.font.FontManager$UnresolvedBuilderBundle
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
+ XXX.gui.font.GlyphRenderTypes
- XXX.gui.font.GlyphRenderTypes$1
+ XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.layouts.AbstractLayout
- XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
+ XXX.gui.layouts.EqualSpacingLayout
- XXX.gui.layouts.EqualSpacingLayout$1
+ XXX.gui.layouts.EqualSpacingLayout$ChildContainer
- XXX.gui.layouts.EqualSpacingLayout$Orientation
+ XXX.gui.layouts.FrameLayout
- XXX.gui.layouts.FrameLayout$ChildContainer
+ XXX.gui.layouts.GridLayout
- XXX.gui.layouts.GridLayout$CellInhabitant
+ XXX.gui.layouts.GridLayout$RowHelper
- XXX.gui.layouts.HeaderAndFooterLayout
+ XXX.gui.layouts.Layout
- XXX.gui.layouts.LayoutElement
+ XXX.gui.layouts.LayoutSettings
- XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
+ XXX.gui.layouts.LinearLayout
- XXX.gui.layouts.LinearLayout$1
+ XXX.gui.layouts.LinearLayout$Orientation
+ XXX.gui.layouts.package-info
- XXX.gui.layouts.SpacerElement
- XXX.gui.narration.NarratableEntry
+ XXX.gui.narration.NarratableEntry$NarrationPriority
- XXX.gui.narration.NarratedElementType
+ XXX.gui.narration.NarrationElementOutput
- XXX.gui.narration.NarrationSupplier
+ XXX.gui.narration.NarrationThunk
+ XXX.gui.narration.package-info
- XXX.gui.narration.ScreenNarrationCollector
+ XXX.gui.narration.ScreenNarrationCollector$1
- XXX.gui.narration.ScreenNarrationCollector$EntryKey
+ XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
- XXX.gui.narration.ScreenNarrationCollector$Output
- XXX.gui.navigation.CommonInputs
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenAxis$1
+ XXX.gui.navigation.ScreenDirection
- XXX.gui.navigation.ScreenDirection$1
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.BanNoticeScreen
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.CreditsAndAttributionScreen
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DeathScreen$TitleConfirmScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.FaviconTexture
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.NoticeWithLinkScreen
- XXX.gui.screens.OnlineOptionsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PopupScreen
+ XXX.gui.screens.PopupScreen$ButtonOption
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.Screen$DeferredTooltipRendering
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$WarningLabel
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
+ XXX.gui.spectator.package-info
+ XXX.gui.spectator.PlayerMenuItem
- XXX.gui.spectator.RootSpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenu
- XXX.gui.spectator.SpectatorMenu$1
+ XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
- XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
+ XXX.gui.spectator.SpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenuItem
+ XXX.gui.spectator.SpectatorMenuListener
- XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.ClientBundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.ClientTooltipPositioner
- XXX.inventory.tooltip.DefaultTooltipPositioner
+ XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipRenderUtil
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
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimeStamped
+ XXX.level.block.package-info
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TorchflowerCropBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallHangingSignBlock
+ XXX.level.block.WallHangingSignBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BlockColumn
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.CarvingMask
+ XXX.level.chunk.CarvingMask$Mask
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkAccess$TicksToSave
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$PostLoadProcessor
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LevelChunkSection$1BlockCounter
- XXX.level.chunk.LightChunk
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$Configuration
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.LevelStem
+ XXX.level.dimension.package-info
- XXX.level.entity.ChunkEntities
+ XXX.level.entity.ChunkStatusUpdateListener
- XXX.level.entity.EntityAccess
+ XXX.level.entity.EntityInLevelCallback
- XXX.level.entity.EntityInLevelCallback$1
+ XXX.level.entity.EntityLookup
- XXX.level.entity.EntityPersistentStorage
+ XXX.level.entity.EntitySection
- XXX.level.entity.EntitySectionStorage
+ XXX.level.entity.EntityTickList
- XXX.level.entity.EntityTypeTest
+ XXX.level.entity.EntityTypeTest$1
- XXX.level.entity.LevelCallback
+ XXX.level.entity.LevelEntityGetter
- XXX.level.entity.LevelEntityGetterAdapter
+ XXX.level.entity.package-info
+ XXX.level.entity.PersistentEntitySectionManager
- XXX.level.entity.PersistentEntitySectionManager$Callback
+ XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- XXX.level.entity.TransientEntitySectionManager
+ XXX.level.entity.TransientEntitySectionManager$Callback
- XXX.level.entity.Visibility
- XXX.level.gameevent.BlockPositionSource
+ XXX.level.gameevent.BlockPositionSource$Type
- XXX.level.gameevent.DynamicGameEventListener
+ XXX.level.gameevent.EntityPositionSource
- XXX.level.gameevent.EntityPositionSource$Type
+ XXX.level.gameevent.EuclideanGameEventListenerRegistry
- XXX.level.gameevent.EuclideanGameEventListenerRegistry$OnEmptyAction
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListener$Holder
- XXX.level.gameevent.GameEventListenerRegistry
+ XXX.level.gameevent.GameEventListenerRegistry$1
- XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
+ XXX.level.gameevent.package-info
+ XXX.level.gameevent.PositionSource
- XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.Aquifer
+ XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$FluidPicker
+ XXX.level.levelgen.Aquifer$FluidStatus
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Beardifier$1
+ XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.BelowZeroRetrogen
+ XXX.level.levelgen.BelowZeroRetrogen$1
- XXX.level.levelgen.BitRandomSource
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Density
+ XXX.level.levelgen.DensityFunction
- XXX.level.levelgen.DensityFunction$ContextProvider
+ XXX.level.levelgen.DensityFunction$FunctionContext
- XXX.level.levelgen.DensityFunction$NoiseHolder
+ XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$SinglePointContext
+ XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions
+ XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$HolderHolder
- XXX.level.levelgen.DensityFunctions$Mapped
+ XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker
+ XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MarkerOrMarked
+ XXX.level.levelgen.DensityFunctions$MulOrAdd
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
+ XXX.level.levelgen.DensityFunctions$Noise
- XXX.level.levelgen.DensityFunctions$PureTransformer
+ XXX.level.levelgen.DensityFunctions$RangeChoice
- XXX.level.levelgen.DensityFunctions$Shift
+ XXX.level.levelgen.DensityFunctions$ShiftA
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
+ XXX.level.levelgen.DensityFunctions$ShiftNoise
+ XXX.level.levelgen.DensityFunctions$Spline
- XXX.level.levelgen.DensityFunctions$Spline$Coordinate
+ XXX.level.levelgen.DensityFunctions$Spline$Point
- XXX.level.levelgen.DensityFunctions$TransformerWithContext
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ XXX.level.levelgen.DensityFunctions$YClampedGradient
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
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
+ XXX.level.levelgen.WorldDimensions$1Entry
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.WorldOptions
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.ChunkSkyLightSources
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$SectionState
- XXX.level.lighting.LayerLightSectionStorage$SectionType
- XXX.level.lighting.LeveledPriorityQueue
+ XXX.level.lighting.LeveledPriorityQueue$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEngine
+ XXX.level.lighting.LightEngine$QueueEntry
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightEngine$1
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.MapColor
+ XXX.level.material.MapColor$Brightness
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.AmphibiousNodeEvaluator
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.Path$DebugData
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
+ XXX.level.saveddata.SavedData$Factory
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DataVersion
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelCandidates
+ XXX.level.storage.LevelStorageSource$LevelDirectory
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelSummary$BackupStatus
+ XXX.level.storage.LevelSummary$SymlinkLevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.package-info
+ XXX.levelgen.blockpredicates.AllOfPredicate
- XXX.levelgen.blockpredicates.AnyOfPredicate
+ XXX.levelgen.blockpredicates.BlockPredicate
- XXX.levelgen.blockpredicates.BlockPredicateType
+ XXX.levelgen.blockpredicates.CombiningPredicate
- XXX.levelgen.blockpredicates.HasSturdyFacePredicate
+ XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ XXX.levelgen.blockpredicates.MatchingBlocksPredicate
- XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
- XXX.levelgen.blockpredicates.MatchingFluidsPredicate
+ XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
- XXX.levelgen.blockpredicates.ReplaceablePredicate
+ XXX.levelgen.blockpredicates.SolidPredicate
- XXX.levelgen.blockpredicates.StateTestingPredicate
+ XXX.levelgen.blockpredicates.TrueBlockPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TreeFeature$1
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CarvingMaskPlacement
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CountOnEveryLayerPlacement
+ XXX.levelgen.placement.CountPlacement
- XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureType
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.TerrainAdjustment
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount$1
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Path
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionReference
+ XXX.loot.functions.FunctionReference$Serializer
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
+ XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetPotionFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SmeltItemFunction
+ XXX.loot.predicates.AllOfCondition$Serializer
- XXX.loot.predicates.AnyOfCondition
+ XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.CompositeLootItemCondition
- XXX.loot.predicates.CompositeLootItemCondition$Builder
+ XXX.loot.predicates.CompositeLootItemCondition$Serializer
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$Serializer
+ XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
- XXX.minecraft.network.BandwidthDebugMonitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.ClientPongPacketListener
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.FileToIdConverter
+ XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader
+ XXX.minecraft.resources.RegistryDataLoader$1
- XXX.minecraft.resources.RegistryDataLoader$Loader
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$1
- XXX.minecraft.resources.RegistryOps$2
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Dummy
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.package-info
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$ExecutionContext
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext$AbortingReturnValueConsumer
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
+ XXX.minecraft.server.ServerInfo
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.DamageTypeTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagLoader$SortingEntry
+ XXX.minecraft.tags.TagManager
- XXX.minecraft.tags.TagManager$LoadResult
+ XXX.minecraft.tags.TagNetworkSerialization
- XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
+ XXX.minecraft.tags.TagNetworkSerialization$TagOutput
- XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer
+ XXX.minecraft.util.AbortableIterationConsumer$Continuation
- XXX.minecraft.util.ArrayListDeque
+ XXX.minecraft.util.ArrayListDeque$DescendingIterator
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.Brightness
- XXX.minecraft.util.ByIdMap
+ XXX.minecraft.util.ByIdMap$1
- XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.CommonColors
+ XXX.minecraft.util.CommonLinks
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
+ XXX.minecraft.util.Crypt$SaltSignaturePair
- XXX.minecraft.util.Crypt$SaltSupplier
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$CoordinateVisitor
+ XXX.minecraft.util.CubicSpline$Multipoint
- XXX.minecraft.util.DebugBuffer
+ XXX.minecraft.util.DependencySorter
- XXX.minecraft.util.DependencySorter$Entry
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
- XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
+ XXX.minecraft.util.ExtraCodecs$2
- XXX.minecraft.util.ExtraCodecs$3
+ XXX.minecraft.util.ExtraCodecs$4
- XXX.minecraft.util.ExtraCodecs$EitherCodec
+ XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
- XXX.minecraft.util.ExtraCodecs$StrictOptionalFieldCodec
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
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
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.package-info
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.ResourceLocationPattern
- XXX.minecraft.util.SampleLogger
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.package-info
- XXX.model.geom.EntityModelSet
+ XXX.model.geom.LayerDefinitions
- XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelLayers
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.ModelPart$Visitor
- XXX.model.geom.package-info
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.network.config.JoinWorldTask
- XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
+ XXX.packs.linkfs.DummyFileAttributes
- XXX.packs.linkfs.LinkFileSystem
+ XXX.packs.linkfs.LinkFileSystem$Builder
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
+ XXX.packs.linkfs.LinkFSPath
- XXX.packs.linkfs.LinkFSPath$1
+ XXX.packs.linkfs.LinkFSPath$2
- XXX.packs.linkfs.LinkFSPath$3
+ XXX.packs.linkfs.LinkFSProvider
- XXX.packs.linkfs.LinkFSProvider$1
+ XXX.packs.linkfs.LinkFSProvider$2
- XXX.packs.linkfs.package-info
+ XXX.packs.linkfs.PathContents
- XXX.packs.linkfs.PathContents$1
+ XXX.packs.linkfs.PathContents$2
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.linkfs.PathContents$FileContents
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.MetadataSectionType$1
- XXX.packs.metadata.package-info
- XXX.packs.repository.BuiltInPackSource
+ XXX.packs.repository.BuiltInPackSource$1
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.FolderRepositorySource$FolderPackDetector
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Info
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
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
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
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
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntent$1
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
- XXX.protocol.login.ServerboundCustomQueryAnswerPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerboundLoginAcknowledgedPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.ContextNbtProvider$Serializer
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.StorageNbtProvider
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
- XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$InlineSerializer
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$Serializer
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.MapItemSavedData$MapPatch
+ XXX.saveddata.maps.package-info
- XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementTabType$Sprites
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.AdvancementWidgetType$1
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.KeyBindsList
- XXX.screens.controls.KeyBindsList$CategoryEntry
+ XXX.screens.controls.KeyBindsList$CategoryEntry$1
- XXX.screens.controls.KeyBindsList$Entry
+ XXX.screens.controls.KeyBindsList$KeyEntry
- XXX.screens.controls.KeyBindsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.debug.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AbstractSignEditScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconButton
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.CyclingSlotBackground
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectRenderingInventoryScreen
- XXX.screens.inventory.EnchantmentNames
+ XXX.screens.inventory.EnchantmentScreen
- XXX.screens.inventory.FurnaceScreen
+ XXX.screens.inventory.GrindstoneScreen
- XXX.screens.inventory.HangingSignEditScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
+ XXX.screens.inventory.LecternScreen
- XXX.screens.inventory.LecternScreen$1
+ XXX.screens.inventory.LoomScreen
- XXX.screens.inventory.MenuAccess
+ XXX.screens.inventory.MerchantScreen
- XXX.screens.inventory.MerchantScreen$TradeOfferButton
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
+ XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.Realms32bitWarningScreen
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerReconfigScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ XXX.screens.multiplayer.WarningScreen
- XXX.screens.packs.package-info
- XXX.screens.packs.PackSelectionModel
+ XXX.screens.packs.PackSelectionModel$Entry
- XXX.screens.packs.PackSelectionModel$EntryBase
+ XXX.screens.packs.PackSelectionModel$SelectedPackEntry
- XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
+ XXX.screens.packs.PackSelectionScreen
- XXX.screens.packs.PackSelectionScreen$1
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
- XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ XXX.screens.worldselection.CreateWorldScreen$GameTab
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.ExperimentsScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.PresetEditor
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.SwitchGrid
- XXX.screens.worldselection.SwitchGrid$Builder
+ XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- XXX.screens.worldselection.SwitchGrid$LabeledSwitch
+ XXX.screens.worldselection.SwitchGrid$SwitchBuilder
- XXX.screens.worldselection.WorldCreationContext
+ XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
- XXX.screens.worldselection.WorldCreationContext$OptionsModifier
+ XXX.screens.worldselection.WorldCreationUiState
- XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- XXX.screens.worldselection.WorldOpenFlows
+ XXX.screens.worldselection.WorldOpenFlows$1Data
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$Entry
- XXX.screens.worldselection.WorldSelectionList$LoadingHeader
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.chase.ChaseClient
+ XXX.server.chase.ChaseClient$TeleportTarget
- XXX.server.chase.ChaseServer
+ XXX.server.chase.ChaseServer$PlayerPosition
- XXX.server.chase.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ChaseCommand
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugConfigCommand
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
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.FunctionCommand$FunctionResult
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.ItemCommands
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
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
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RandomCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ResetChunksCommand
- XXX.server.commands.ReturnCommand
+ XXX.server.commands.RideCommand
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
+ XXX.server.commands.SpawnArmorTrimsCommand
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
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
- XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
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
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TickingTracker
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.ConfigurationTask
- XXX.server.network.ConfigurationTask$Type
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.ServerCommonPacketListenerImpl
+ XXX.server.network.ServerConfigurationPacketListenerImpl
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$MessageEncoder
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.BuiltInMetadata
+ XXX.server.packs.CompositePackResources
- XXX.server.packs.FeatureFlagsMetadataSection
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FilePackResources$FileResourcesSupplier
+ XXX.server.packs.FilePackResources$SharedZipFileAccess
- XXX.server.packs.OverlayMetadataSection
+ XXX.server.packs.OverlayMetadataSection$OverlayEntry
+ XXX.server.packs.package-info
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackType
+ XXX.server.packs.PathPackResources
- XXX.server.packs.PathPackResources$PathResourcesSupplier
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResourcesBuilder
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
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
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockSetType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ChestType$1
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.NoteBlockInstrument$Type
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.RotationSegment
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$InlineSerializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootDataManager$FunctionSequence
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.SerializerType
+ XXX.structure.pieces.package-info
+ XXX.structure.pieces.PieceGenerator
- XXX.structure.pieces.PieceGenerator$Context
+ XXX.structure.pieces.PieceGeneratorSupplier
- XXX.structure.pieces.PieceGeneratorSupplier$Context
+ XXX.structure.pieces.PiecesContainer
- XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceSerializationContext
+ XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$ContextlessType
+ XXX.structure.pieces.StructurePieceType$StructureTemplateType
- XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
+ XXX.structure.placement.RandomSpreadStructurePlacement
- XXX.structure.placement.RandomSpreadType
+ XXX.structure.placement.RandomSpreadType$1
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
+ XXX.structure.pools.FeaturePoolElement
- XXX.structure.pools.JigsawJunction
+ XXX.structure.pools.JigsawPlacement
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JungleTemplePiece
+ XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.JungleTempleStructure
+ XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$1
+ XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftCrossing
+ XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftRoom
+ XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure
+ XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces
+ XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeCrossing
+ XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$BridgeStraight
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
+ XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
+ XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$RoomCrossing
+ XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressPieces$StartPiece
+ XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces
+ XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.NetherFossilStructure
+ XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$1
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
+ XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentPieces$RoomDefinition
+ XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces
+ XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
+ XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.OceanRuinStructure$Type
+ XXX.structure.structures.package-info
+ XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$Properties
+ XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure
+ XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces
+ XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.ShipwreckStructure
+ XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$1
+ XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$3
+ XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FillerCorridor
+ XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$LeftTurn
+ XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PieceWeight
+ XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$PrisonHall
+ XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$RoomCrossing
+ XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StairsDown
+ XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$Straight
+ XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdPieces$Turn
+ XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutPiece
+ XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces
+ XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.structure.structures.WoodlandMansionStructure
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.CappedProcessor
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.package-info
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
+ XXX.util.profiling.ProfileCollector
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
+ XXX.world.level.package-info
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry +5M
```
```
XXX.gui.screens.RealmsConfigureWorldScreen +5M -4M
```
```
XXX.gui.screens.RealmsResetNormalWorldScreen +4M -5M
```
```
XXX.advancements.critereon.AbstractCriterionTriggerInstance +4M -3M | +1P -1P
```
```
XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.BlockPredicate$Builder +3M -3M | +4P -4P
```
```
XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance +7M -3M | +3P -3P
```
```
XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance +3M -4M | +1P -1P
```
```
XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.CuredZombieVillagerTrigger +2M -2M
```
```
XXX.advancements.critereon.DamagePredicate +14M -4M | +3P -4P
```
```
XXX.advancements.critereon.DamageSourcePredicate +10M -2M | +3P -3P
```
```
XXX.advancements.critereon.DeserializationContext +1M -1M | -1P
```
```
XXX.advancements.critereon.DistanceTrigger +2M -2M
```
```
XXX.advancements.critereon.EffectsChangedTrigger +2M -2M
```
```
XXX.advancements.critereon.EnchantedItemTrigger +2M -2M
```
```
XXX.advancements.critereon.EnchantmentPredicate +7M -5M | +2P -3P
```
```
XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.EntityEquipmentPredicate$Builder +7M -7M | +6P -6P
```
```
XXX.advancements.critereon.EntityFlagsPredicate$Builder +1M -1M | +5P -5P
```
```
XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.EntityPredicate$Builder +9M -8M | +13P -13P
```
```
XXX.advancements.critereon.LootTableTrigger$TriggerInstance +2M -2M
```
```
XXX.advancements.critereon.MinMaxBounds$BoundsFactory +1P -1P
```
```
XXX.advancements.critereon.MinMaxBounds$Doubles +14M -4M | +5P -2P
```
```
XXX.advancements.critereon.MobEffectsPredicate +5M -5M | +2P -2P
```
```
XXX.advancements.critereon.PlayerTrigger +2M -2M
```
```
XXX.advancements.critereon.RecipeCraftedTrigger +2M -2M
```
```
XXX.advancements.critereon.RecipeUnlockedTrigger +2M -2M
```
```
XXX.advancements.critereon.SummonedEntityTrigger +2M -2M
```
```
XXX.advancements.critereon.TagPredicate +7M -2M
```
```
XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance +4M -3M | +1P -1P
```
```
XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance +4M -3M | +1P -1P
```
```
XXX.advancements.critereon.TradeTrigger$TriggerInstance +4M -2M | +2P -2P
```
```
XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance +1M -1M
```
```
XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.advancements.critereon.UsingItemTrigger$TriggerInstance +3M -2M | +1P -1P
```
```
XXX.minecraft.client.Minecraft +56M -53M | +5P -3P
```
```
XXX.minecraft.client.User -1M
```
```
XXX.gui.components.AbstractSelectionList +1M | +2P
```
```
XXX.gui.components.AbstractSliderButton -1P
```
```
XXX.gui.components.EditBox +1M | +1P -3P
```
```
XXX.client.multiplayer.PlayerInfo -3M
```
```
XXX.multiplayer.chat.ChatListener +4M -1M | +1P
```
```
XXX.client.renderer.RenderType +2M
```
```
XXX.client.resources.SkinManager -1M
```
```
XXX.metadata.gui.GuiSpriteScaling$NineSlice +3M
```
```
XXX.minecraft.core.HolderSet +1M -1M
```
```
XXX.minecraft.core.Registry -1M
```
```
XXX.core.registries.BuiltInRegistries +1M
```
```
XXX.data.recipes.RecipeProvider +3M
```
```
XXX.minecraft.nbt.TagParser +1M | +1P
```
```
XXX.minecraft.network.Connection +3M -4M | +1P
```
```
XXX.network.chat.RemoteChatSession +2M -1M
```
```
XXX.network.chat.SignedMessageValidator$KeyBased +2M -1M | +1P
```
```
XXX.world.effect.MobEffectInstance +8P
```
```
XXX.world.entity.AreaEffectCloud +1P
```
```
XXX.world.entity.EntityType +1M
```
```
XXX.world.entity.EquipmentSlot +1M | +1P
```
```
XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald +1M | +1P -2P
```
```
XXX.entity.player.ProfilePublicKey +1M -1M
```
```
XXX.world.inventory.BeaconMenu +2M | +1P
```
```
XXX.world.item.SuspiciousStewItem +7M -1M | -2P
```
```
XXX.item.alchemy.Potion +1M | +1P
```
```
XXX.item.enchantment.Enchantment +1M | +1P
```
```
XXX.level.block.FlowerBlock +1M -2M | +1P -2P
```
```
XXX.level.block.SuspiciousEffectHolder +1P -2P
```
```
XXX.storage.loot.IntRange +16M -8M | +2P
```
```
XXX.storage.loot.LootDataType +4M -10M | +1P -2P
```
```
XXX.storage.loot.LootPool$Builder +3P -3P
```
```
XXX.loot.entries.AlternativesEntry +4M -3M | +1P
```
```
XXX.loot.entries.EmptyLootItem +3M -1M | +1P
```
```
XXX.loot.entries.LootPoolEntries +1M -2M | +1P
```
```
XXX.loot.entries.LootPoolEntryContainer +3M -1M | +1P -1P
```
```
XXX.loot.functions.ApplyExplosionDecay +3M -1M | +1P
```
```
XXX.loot.functions.CopyNameFunction$NameSource +1M -1M | +1P
```
```
XXX.loot.functions.LimitCount +5M -2M | +1P
```
```
XXX.loot.functions.LootItemFunctionType +5M -1M | +1P
```
```
XXX.loot.functions.LootingEnchantFunction +5M -1M | +1P
```
```
XXX.loot.functions.SetInstrumentFunction +5M -2M | +1P
```
```
XXX.loot.functions.SetItemDamageFunction +6M -3M | +1P
```
```
XXX.loot.predicates.AllOfCondition +3M -1M | +2P
```
```
XXX.loot.predicates.BonusLevelTableCondition +9M -2M | +3P -2P
```
```
XXX.loot.predicates.EntityHasScoreCondition +8M -1M | +1P
```
```
XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder +2P -2P
```
```
XXX.loot.predicates.LootItemKilledByPlayerCondition +1P
```
```
XXX.loot.predicates.LootItemRandomChanceWithLootingCondition +8M -1M | +1P
```
```
XXX.loot.predicates.TimeCheck +8M -1M | +2P -1P
```
```
XXX.loot.predicates.WeatherCheck$Builder +2M -2M | +2P -2P
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$ServerEntry
</summary>

```diff
- Component lambda$renderStatusLights$0()
- Component lambda$renderStatusLights$1()
- Component lambda$renderStatusLights$2(RealmsServer)
- Component lambda$renderStatusLights$3()
- void drawRealmStatus(GuiGraphics,int,int,int,int,ResourceLocation,Supplier)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
</summary>

```diff
- Component lambda$drawServerStatus$24()
- Component lambda$drawServerStatus$25()
- Component lambda$drawServerStatus$26()
- Component lambda$drawServerStatus$27()
+ void drawClose(GuiGraphics,int,int,int,int)
+ void drawExpired(GuiGraphics,int,int,int,int)
+ void drawExpiring(GuiGraphics,int,int,int,int,int)
+ void drawOpen(GuiGraphics,int,int,int,int)
- void drawRealmStatus(GuiGraphics,int,int,int,int,ResourceLocation,Supplier)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
</summary>

```diff
- void lambda$init$0(CycleButton,LevelType)
+ void lambda$init$0(LayoutSettings)
- void lambda$init$1(CycleButton,Boolean)
+ void lambda$init$1(CycleButton,LevelType)
- void lambda$init$2(Button)
+ void lambda$init$2(CycleButton,Boolean)
+ void lambda$init$4(Button)
- void lambda$init$4(RealmsResetNormalWorldScreen,GuiEventListener)
+ void lambda$init$5(RealmsResetNormalWorldScreen,GuiEventListener)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
</summary>

```diff
+ ContextAwarePredicate getPlayerPredicate()
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
- Optional getPlayerPredicate()
+ void <init>(ResourceLocation,ContextAwarePredicate)
- void <init>(ResourceLocation,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,Block,ItemPredicate,MinMaxBounds$Ints)
- void <init>(Optional,Block,Optional,MinMaxBounds$Ints)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BlockPredicate$Builder
</summary>

```diff
+ BlockPredicate build()
- BlockPredicate$Builder of(Collection)
+ BlockPredicate$Builder of(Iterable)
+ BlockPredicate$Builder setProperties(StatePropertiesPredicate)
- BlockPredicate$Builder setProperties(StatePropertiesPredicate$Builder)
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
</summary>

```diff
- boolean matches(Optional,LootContext)
+ BredAnimalsTrigger$TriggerInstance bredAnimals(EntityPredicate,EntityPredicate,EntityPredicate)
- BredAnimalsTrigger$TriggerInstance bredAnimals(Optional,Optional,Optional)
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate,ContextAwarePredicate,ContextAwarePredicate)
- void <init>(Optional,Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
- void lambda$serializeToJson$1(JsonObject,ContextAwarePredicate)
- void lambda$serializeToJson$2(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,Potion)
- void <init>(Optional,Potion)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ResourceKey,ResourceKey)
- void <init>(Optional,ResourceKey,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
</summary>

```diff
+ ChanneledLightningTrigger$TriggerInstance channeledLightning(EntityPredicate[])
- ChanneledLightningTrigger$TriggerInstance channeledLightning(EntityPredicate$Builder[])
+ ContextAwarePredicate[] lambda$channeledLightning$0(int)
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate[])
- void <init>(Optional,List)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,MinMaxBounds$Ints)
- void <init>(Optional,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ItemPredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ CuredZombieVillagerTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- CuredZombieVillagerTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DamagePredicate
</summary>

```diff
- boolean equals(Object)
+ DamagePredicate fromJson(JsonElement)
- int hashCode()
- MinMaxBounds$Doubles dealtDamage()
- MinMaxBounds$Doubles takenDamage()
- Optional blocked()
- Optional fromJson(JsonElement)
- Optional of(MinMaxBounds$Doubles,MinMaxBounds$Doubles,Optional,Optional,Optional)
- Optional sourceEntity()
- Optional type()
- String toString()
+ void <clinit>()
+ void <init>()
+ void <init>(MinMaxBounds$Doubles,MinMaxBounds$Doubles,EntityPredicate,Boolean,DamageSourcePredicate)
- void <init>(MinMaxBounds$Doubles,MinMaxBounds$Doubles,Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,EntityPredicate)
- void lambda$serializeToJson$1(JsonObject,DamageSourcePredicate)
- void lambda$serializeToJson$2(JsonObject,Boolean)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DamageSourcePredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ DamageSourcePredicate fromJson(JsonElement)
- int hashCode()
- List tags()
- Optional directEntity()
- Optional fromJson(JsonElement)
- Optional of(List,Optional,Optional)
- Optional sourceEntity()
- String toString()
+ void <init>(List,EntityPredicate,EntityPredicate)
- void <init>(List,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DeserializationContext
</summary>

```diff
- List deserializeConditions(JsonArray,String,LootContextParamSet)
+ LootItemCondition[] deserializeConditions(JsonArray,String,LootContextParamSet)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DistanceTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ DistanceTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- DistanceTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EffectsChangedTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ EffectsChangedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- EffectsChangedTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnchantedItemTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ EnchantedItemTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- EnchantedItemTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnchantmentPredicate
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
+ EnchantmentPredicate fromJson(JsonElement)
+ EnchantmentPredicate[] fromJsonArray(JsonElement)
- int hashCode()
+ JsonElement serializeToJson()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- MinMaxBounds$Ints level()
- Optional enchantment()
- String toString()
+ void <init>()
- void <init>(Optional,MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,Block,StatePropertiesPredicate)
- void <init>(Optional,Block,Optional)
- void lambda$serializeToJson$0(JsonObject,StatePropertiesPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
</summary>

```diff
+ EntityEquipmentPredicate build()
+ EntityEquipmentPredicate$Builder chest(ItemPredicate)
- EntityEquipmentPredicate$Builder chest(ItemPredicate$Builder)
+ EntityEquipmentPredicate$Builder feet(ItemPredicate)
- EntityEquipmentPredicate$Builder feet(ItemPredicate$Builder)
+ EntityEquipmentPredicate$Builder head(ItemPredicate)
- EntityEquipmentPredicate$Builder head(ItemPredicate$Builder)
+ EntityEquipmentPredicate$Builder legs(ItemPredicate)
- EntityEquipmentPredicate$Builder legs(ItemPredicate$Builder)
+ EntityEquipmentPredicate$Builder mainhand(ItemPredicate)
- EntityEquipmentPredicate$Builder mainhand(ItemPredicate$Builder)
+ EntityEquipmentPredicate$Builder offhand(ItemPredicate)
- EntityEquipmentPredicate$Builder offhand(ItemPredicate$Builder)
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
</summary>

```diff
+ EntityFlagsPredicate build()
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,DamagePredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,DamagePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityPredicate$Builder
</summary>

```diff
+ EntityPredicate build()
+ EntityPredicate$Builder effects(MobEffectsPredicate)
- EntityPredicate$Builder effects(MobEffectsPredicate$Builder)
- EntityPredicate$Builder equipment(EntityEquipmentPredicate$Builder)
+ EntityPredicate$Builder flags(EntityFlagsPredicate)
- EntityPredicate$Builder flags(EntityFlagsPredicate$Builder)
+ EntityPredicate$Builder located(LocationPredicate)
- EntityPredicate$Builder located(LocationPredicate$Builder)
+ EntityPredicate$Builder passenger(EntityPredicate)
- EntityPredicate$Builder passenger(EntityPredicate$Builder)
+ EntityPredicate$Builder steppingOn(LocationPredicate)
- EntityPredicate$Builder steppingOn(LocationPredicate$Builder)
+ EntityPredicate$Builder targetedEntity(EntityPredicate)
- EntityPredicate$Builder targetedEntity(EntityPredicate$Builder)
+ EntityPredicate$Builder vehicle(EntityPredicate)
- EntityPredicate$Builder vehicle(EntityPredicate$Builder)
- Optional build()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ResourceLocation)
- void <init>(Optional,ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MinMaxBounds$Doubles
</summary>

```diff
- boolean equals(Object)
+ Double lambda$fromReader$0(Double)
- Double lambda$fromReader$1(Double)
- Double lambda$squareOpt$0(Double)
+ Double squareOpt(Double)
- int hashCode()
- JsonElement serializeToJson()
+ MinMaxBounds$Doubles create(StringReader,Double,Double)
- MinMaxBounds$Doubles create(StringReader,Optional,Optional)
- Optional max()
- Optional maxSq()
- Optional min()
- Optional minSq()
- Optional squareOpt(Optional)
- String toString()
+ void <init>(Double,Double)
- void <init>(Optional,Optional,Optional,Optional)
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MobEffectsPredicate
</summary>

```diff
- boolean equals(Object)
- int hashCode()
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- Map effectMap()
+ MobEffectsPredicate and(MobEffect,MobEffectsPredicate$MobEffectInstancePredicate)
+ MobEffectsPredicate and(MobEffect)
+ MobEffectsPredicate effects()
+ MobEffectsPredicate fromJson(JsonElement)
- Optional fromJson(JsonElement)
- String toString()
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ PlayerTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- PlayerTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeCraftedTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ RecipeCraftedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- RecipeCraftedTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.RecipeUnlockedTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ RecipeUnlockedTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- RecipeUnlockedTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SummonedEntityTrigger
</summary>

```diff
+ AbstractCriterionTriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- AbstractCriterionTriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
+ SummonedEntityTrigger$TriggerInstance createInstance(JsonObject,ContextAwarePredicate,DeserializationContext)
- SummonedEntityTrigger$TriggerInstance createInstance(JsonObject,Optional,DeserializationContext)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TagPredicate
</summary>

```diff
- App lambda$codec$0(ResourceKey,RecordCodecBuilder$Instance)
- boolean equals(Object)
- boolean expected()
- Codec codec(ResourceKey)
- int hashCode()
+ JsonElement serializeToJson()
- String toString()
- TagKey tag()
+ TagPredicate fromJson(JsonElement,ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ TameAnimalTrigger$TriggerInstance tamedAnimal(EntityPredicate)
- TameAnimalTrigger$TriggerInstance tamedAnimal(Optional)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ TargetBlockTrigger$TriggerInstance targetHit(MinMaxBounds$Ints,ContextAwarePredicate)
- TargetBlockTrigger$TriggerInstance targetHit(MinMaxBounds$Ints,Optional)
+ void <init>(ContextAwarePredicate,MinMaxBounds$Ints,ContextAwarePredicate)
- void <init>(Optional,MinMaxBounds$Ints,Optional)
- void lambda$serializeToJson$0(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ContextAwarePredicate,ItemPredicate)
- void <init>(Optional,Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
- void lambda$serializeToJson$1(JsonObject,ContextAwarePredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
</summary>

```diff
+ void <init>(ContextAwarePredicate,MinMaxBounds$Doubles)
- void <init>(Optional,MinMaxBounds$Doubles)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ItemPredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.UsingItemTrigger$TriggerInstance
</summary>

```diff
- JsonObject serializeToJson()
+ JsonObject serializeToJson(SerializationContext)
+ void <init>(ContextAwarePredicate,ItemPredicate)
- void <init>(Optional,Optional)
- void lambda$serializeToJson$0(JsonObject,ItemPredicate)
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- boolean isGameLoadFinished()
+ boolean lambda$createSearchTrees$14(String)
- boolean lambda$createSearchTrees$15(String)
+ boolean lambda$createSearchTrees$6(String)
- boolean lambda$createSearchTrees$7(String)
+ boolean lambda$tick$39()
- boolean lambda$tick$40()
+ ChunkProgressListener lambda$doWorldLoad$40(int)
- ChunkProgressListener lambda$doWorldLoad$41(int)
+ CompletionStage lambda$delayTextureReload$51(CompletableFuture)
- CompletionStage lambda$delayTextureReload$52(CompletableFuture)
+ CrashReport lambda$delayCrash$20(CrashReport)
- CrashReport lambda$delayCrash$21(CrashReport)
+ CrashReport lambda$delayCrashRaw$21(CrashReport)
- CrashReport lambda$delayCrashRaw$22(CrashReport)
+ FrameTimer getFrameTimer()
- GameProfile getGameProfile()
- GameProfile lambda$new$1()
+ IntegratedServer lambda$doWorldLoad$41(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
- IntegratedServer lambda$doWorldLoad$42(LevelStorageSource$LevelStorageAccess,PackRepository,WorldStem,Services,Thread)
+ PropertyMap getProfileProperties()
- RefreshableSearchTree lambda$createSearchTrees$10(List)
+ RefreshableSearchTree lambda$createSearchTrees$11(List)
- RefreshableSearchTree lambda$createSearchTrees$12(List)
+ RefreshableSearchTree lambda$createSearchTrees$18(List)
- RefreshableSearchTree lambda$createSearchTrees$19(List)
+ RefreshableSearchTree lambda$createSearchTrees$9(List)
+ ResourceLocation lambda$createSearchTrees$16(RecipeCollection,Recipe)
- ResourceLocation lambda$createSearchTrees$17(RecipeCollection,Recipe)
- SampleLogger getFrameTimeLogger()
+ Stream lambda$createSearchTrees$10(ItemStack)
- Stream lambda$createSearchTrees$11(ItemStack)
+ Stream lambda$createSearchTrees$12(RecipeCollection,Recipe)
- Stream lambda$createSearchTrees$13(RecipeCollection,Recipe)
+ Stream lambda$createSearchTrees$15(RecipeCollection)
- Stream lambda$createSearchTrees$16(RecipeCollection)
+ Stream lambda$createSearchTrees$17(RecipeCollection)
- Stream lambda$createSearchTrees$18(RecipeCollection)
+ Stream lambda$createSearchTrees$7(ItemStack)
- Stream lambda$createSearchTrees$9(ItemStack)
+ String lambda$createSearchTrees$13(Component)
- String lambda$createSearchTrees$14(Component)
+ String lambda$createSearchTrees$5(Component)
- String lambda$createSearchTrees$6(Component)
+ String lambda$doWorldLoad$42(WorldStem)
- String lambda$doWorldLoad$43(WorldStem)
+ String lambda$fillSystemReport$44(String)
+ String lambda$fillSystemReport$45(Minecraft)
- String lambda$fillSystemReport$45(String)
+ String lambda$fillSystemReport$46()
- String lambda$fillSystemReport$46(Minecraft)
- String lambda$fillSystemReport$49()
+ String lambda$fillSystemReport$49(Options)
+ String lambda$fillSystemReport$50(LanguageManager)
- String lambda$fillSystemReport$50(Options)
- String lambda$fillSystemReport$51(LanguageManager)
+ Style lambda$debugClientMetricsStart$30(Path,Style)
- Style lambda$debugClientMetricsStart$31(Path,Style)
+ Style lambda$grabHugeScreenshot$54(File,Style)
- Style lambda$grabHugeScreenshot$55(File,Style)
+ Style lambda$grabPanoramixScreenshot$53(File,Style)
- Style lambda$grabPanoramixScreenshot$54(File,Style)
+ void lambda$clearResourcePacksOnError$4(Component)
- void lambda$clearResourcePacksOnError$5(Component)
+ void lambda$createSearchTrees$19(List)
- void lambda$createSearchTrees$20(List)
+ void lambda$debugClientMetricsStart$28(Consumer,double,int)
- void lambda$debugClientMetricsStart$29(Consumer,double,int)
+ void lambda$debugClientMetricsStart$29(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$30(Consumer,ProfileResults)
+ void lambda$debugClientMetricsStart$31(Consumer,Component)
- void lambda$debugClientMetricsStart$32(Consumer,Component)
+ void lambda$debugClientMetricsStart$32(Consumer,Path)
- void lambda$debugClientMetricsStart$33(Consumer,Path)
+ void lambda$debugClientMetricsStart$33(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$34(Consumer,Path)
- void lambda$debugClientMetricsStart$34(SystemReport,Consumer,List)
+ void lambda$debugClientMetricsStart$35(Consumer,CompletableFuture,CompletableFuture)
- void lambda$debugClientMetricsStart$35(Consumer,Path)
- void lambda$debugClientMetricsStart$36(Consumer,CompletableFuture,CompletableFuture)
+ void lambda$debugClientMetricsStart$36(ProfileResults)
+ void lambda$debugClientMetricsStart$37(Consumer,ProfileResults)
- void lambda$debugClientMetricsStart$37(ProfileResults)
- void lambda$debugClientMetricsStart$38(Consumer,ProfileResults)
+ void lambda$doWorldLoad$43(Component)
- void lambda$doWorldLoad$44(Component)
+ void lambda$grabPanoramixScreenshot$52(Component)
- void lambda$grabPanoramixScreenshot$53(Component)
+ void lambda$new$1()
- void lambda$new$2()
+ void lambda$new$2(Optional)
- void lambda$new$3(Optional)
+ void lambda$new$3(RealmsClient,ReloadInstance,GameConfig,boolean)
- void lambda$new$4(RealmsClient,ReloadInstance,GameConfig,boolean)
+ void lambda$openChatScreen$25(boolean)
- void lambda$openChatScreen$26(boolean)
+ void lambda$reloadResourcePacks$22(boolean,Throwable)
- void lambda$reloadResourcePacks$23(boolean,Throwable)
+ void lambda$reloadResourcePacks$23(CompletableFuture)
+ void lambda$reloadResourcePacks$24(boolean,CompletableFuture,Optional)
- void lambda$reloadResourcePacks$24(CompletableFuture)
- void lambda$reloadResourcePacks$25(boolean,CompletableFuture,Optional)
+ void lambda$runTick$26(CompletableFuture)
- void lambda$runTick$27(CompletableFuture)
+ void lambda$runTick$27(TimerQuery)
- void lambda$runTick$28(TimerQuery)
+ void lambda$tick$38()
- void lambda$tick$39()
- void onResourceLoadFinished()
```

</details>
<details>
<summary>
net.minecraft.client.User
</summary>

```diff
+ GameProfile getGameProfile()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.AbstractSelectionList
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.EditBox
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.PlayerInfo
</summary>

```diff
+ CompletableFuture loadSkin(GameProfile,SkinManager,MinecraftSessionService)
+ GameProfile fillProfileProperties(GameProfile,MinecraftSessionService)
+ GameProfile lambda$loadSkin$3(GameProfile,MinecraftSessionService)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.chat.ChatListener
</summary>

```diff
- boolean lambda$handleChatMessageError$2(UUID,ChatType$Bound)
+ boolean lambda$handleDisguisedChatMessage$2(ChatType$Bound,Component,Instant)
- boolean lambda$handleDisguisedChatMessage$3(ChatType$Bound,Component,Instant)
- void <clinit>()
- void handleChatMessageError(UUID,ChatType$Bound)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
- RenderType createArmorDecalCutoutNoCull(ResourceLocation)
- RenderType$CompositeRenderType createArmorCutoutNoCull(String,ResourceLocation,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.resources.SkinManager
</summary>

```diff
+ boolean hasSecureTextureData(GameProfile)
```

</details>
<details>
<summary>
net.minecraft.client.resources.metadata.gui.GuiSpriteScaling$NineSlice
</summary>

```diff
- DataResult validate(GuiSpriteScaling$NineSlice)
- String lambda$validate$1(GuiSpriteScaling$NineSlice$Border,GuiSpriteScaling$NineSlice)
- String lambda$validate$2(GuiSpriteScaling$NineSlice$Border,GuiSpriteScaling$NineSlice)
```

</details>
<details>
<summary>
net.minecraft.core.HolderSet
</summary>

```diff
- HolderSet$Direct direct(Function,Collection)
+ HolderSet$Direct direct(Function,List)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ Object registerMapping(Registry,int,String,Object)
```

</details>
<details>
<summary>
net.minecraft.core.registries.BuiltInRegistries
</summary>

```diff
- Registry registerSimpleWithIntrusiveHolders(ResourceKey,BuiltInRegistries$RegistryBootstrap)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- InventoryChangeTrigger$TriggerInstance inventoryTrigger(ItemPredicate$Builder[])
- ItemPredicate[] lambda$inventoryTrigger$25(int)
- Stream lambda$inventoryTrigger$24(ItemPredicate$Builder)
```

</details>
<details>
<summary>
net.minecraft.nbt.TagParser
</summary>

```diff
- DataResult lambda$static$3(String)
```

</details>
<details>
<summary>
net.minecraft.network.Connection
</summary>

```diff
- Connection connectToServer(InetSocketAddress,boolean,SampleLogger)
+ Connection connectToServer(InetSocketAddress,boolean)
- void configureSerialization(ChannelPipeline,PacketFlow,BandwidthDebugMonitor)
+ void configureSerialization(ChannelPipeline,PacketFlow)
+ void sendNoFlush(Packet,PacketSendListener)
+ void sendNoFlush(Packet)
- void setBandwidthLogger(SampleLogger)
```

</details>
<details>
<summary>
net.minecraft.network.chat.RemoteChatSession
</summary>

```diff
- boolean lambda$createMessageValidator$0(Duration)
+ SignedMessageValidator createMessageValidator()
- SignedMessageValidator createMessageValidator(Duration)
```

</details>
<details>
<summary>
net.minecraft.network.chat.SignedMessageValidator$KeyBased
</summary>

```diff
- boolean validate(PlayerChatMessage)
- void <init>(SignatureValidator,BooleanSupplier)
+ void <init>(SignatureValidator)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
- boolean is(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.world.entity.EquipmentSlot
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
</summary>

```diff
- void <init>(List,int,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.ProfilePublicKey
</summary>

```diff
+ ProfilePublicKey createValidated(SignatureValidator,UUID,ProfilePublicKey$Data,Duration)
- ProfilePublicKey createValidated(SignatureValidator,UUID,ProfilePublicKey$Data)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.BeaconMenu
</summary>

```diff
- int encodeEffect(MobEffect)
- MobEffect decodeEffect(int)
```

</details>
<details>
<summary>
net.minecraft.world.item.SuspiciousStewItem
</summary>

```diff
- void appendMobEffects(ItemStack,List)
- void lambda$appendHoverText$3(List,SuspiciousEffectHolder$EffectEntry)
- void lambda$appendMobEffects$1(CompoundTag,Tag)
- void lambda$finishUsingItem$4(LivingEntity,SuspiciousEffectHolder$EffectEntry)
- void lambda$listPotionEffects$2(Consumer,List)
- void lambda$saveMobEffects$0(CompoundTag,Tag)
+ void saveMobEffect(ItemStack,MobEffect,int)
- void saveMobEffects(ItemStack,List)
```

</details>
<details>
<summary>
net.minecraft.world.item.alchemy.Potion
</summary>

```diff
- Holder$Reference builtInRegistryHolder()
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.Enchantment
</summary>

```diff
- Holder$Reference builtInRegistryHolder()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerBlock
</summary>

```diff
+ int getEffectDuration()
- List getSuspiciousEffects()
+ MobEffect getSuspiciousEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.IntRange
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ boolean lambda$new$1(LootContext,int)
- boolean lambda$new$10(NumberProvider,LootContext,int)
- boolean lambda$new$12(NumberProvider,NumberProvider,LootContext,int)
+ boolean lambda$new$3(NumberProvider,LootContext,int)
+ boolean lambda$new$5(NumberProvider,LootContext,int)
- boolean lambda$new$6(LootContext,int)
+ boolean lambda$new$7(NumberProvider,NumberProvider,LootContext,int)
- boolean lambda$new$8(NumberProvider,LootContext,int)
- Either lambda$static$4(IntRange)
+ int lambda$new$0(LootContext,int)
- int lambda$new$11(NumberProvider,NumberProvider,LootContext,int)
+ int lambda$new$2(NumberProvider,LootContext,int)
+ int lambda$new$4(NumberProvider,LootContext,int)
- int lambda$new$5(LootContext,int)
+ int lambda$new$6(NumberProvider,NumberProvider,LootContext,int)
- int lambda$new$7(NumberProvider,LootContext,int)
- int lambda$new$9(NumberProvider,LootContext,int)
- IntRange lambda$static$3(Either)
- Optional lambda$static$0(IntRange)
- Optional lambda$static$1(IntRange)
- OptionalInt unpackExact()
- void <clinit>()
- void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.LootDataType
</summary>

```diff
+ BiFunction createSingleDeserialiser(Class)
+ BiFunction createSingleOrMultipleDeserialiser(Class,Function)
+ BiFunction lambda$createSingleDeserialiser$1(Class,Gson,String)
+ BiFunction lambda$createSingleOrMultipleDeserialiser$3(Class,Function,Class,Gson,String)
+ Gson parser()
+ Optional lambda$createSingleDeserialiser$0(Gson,Class,String,ResourceLocation,JsonElement)
+ Optional lambda$createSingleOrMultipleDeserialiser$2(Gson,Class,Function,Class,String,ResourceLocation,JsonElement)
- void <init>(Codec,String,LootDataType$Validator)
+ void <init>(Gson,BiFunction,String,LootDataType$Validator)
- void lambda$createLootTableValidator$2(ValidationContext,LootDataId,LootTable)
+ void lambda$createLootTableValidator$5(ValidationContext,LootDataId,LootTable)
- void lambda$createSimpleValidator$1(ValidationContext,LootDataId,LootContextUser)
+ void lambda$createSimpleValidator$4(ValidationContext,LootDataId,LootContextUser)
- void lambda$deserialize$0(ResourceLocation,DataResult$PartialResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.AlternativesEntry
</summary>

```diff
+ boolean lambda$compose$0(ComposableEntryContainer[],LootContext,Consumer)
- boolean lambda$compose$0(List,LootContext,Consumer)
+ ComposableEntryContainer compose(ComposableEntryContainer[])
- ComposableEntryContainer compose(List)
- void <clinit>()
- void <init>(List,List)
+ void <init>(LootPoolEntryContainer[],LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.EmptyLootItem
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- void <clinit>()
- void <init>(int,int,List,List)
+ void <init>(int,int,LootItemCondition[],LootItemFunction[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolEntries
</summary>

```diff
- LootPoolEntryType register(String,Codec)
+ LootPoolEntryType register(String,Serializer)
+ Object createGsonAdapter()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
</summary>

```diff
- List lambda$commonFields$0(LootPoolEntryContainer)
- Products$P1 commonFields(RecordCodecBuilder$Instance)
- void <init>(List)
+ void <init>(LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- void <clinit>()
- void <init>(List)
+ void <init>(LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
</summary>

```diff
+ CopyNameFunction$NameSource getByName(String)
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LimitCount
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
- IntRange lambda$static$0(LimitCount)
+ LootItemFunction lambda$limitCount$0(IntRange,LootItemCondition[])
- LootItemFunction lambda$limitCount$2(IntRange,List)
- void <clinit>()
- void <init>(List,IntRange)
+ void <init>(LootItemCondition[],IntRange)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootItemFunctionType
</summary>

```diff
- boolean equals(Object)
- Codec codec()
- int hashCode()
- String toString()
- void <init>(Codec)
+ void <init>(Serializer)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Integer lambda$static$1(LootingEnchantFunction)
- NumberProvider lambda$static$0(LootingEnchantFunction)
- void <clinit>()
- void <init>(List,NumberProvider,int)
+ void <init>(LootItemCondition[],NumberProvider,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetInstrumentFunction
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ LootItemFunction lambda$setInstrumentOptions$0(TagKey,LootItemCondition[])
- LootItemFunction lambda$setInstrumentOptions$2(TagKey,List)
- TagKey lambda$static$0(SetInstrumentFunction)
- void <clinit>()
- void <init>(List,TagKey)
+ void <init>(LootItemCondition[],TagKey)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Boolean lambda$static$1(SetItemDamageFunction)
+ LootItemFunction lambda$setDamage$0(NumberProvider,LootItemCondition[])
+ LootItemFunction lambda$setDamage$1(NumberProvider,boolean,LootItemCondition[])
- LootItemFunction lambda$setDamage$3(NumberProvider,List)
- LootItemFunction lambda$setDamage$4(NumberProvider,boolean,List)
- NumberProvider lambda$static$0(SetItemDamageFunction)
- void <init>(List,NumberProvider,boolean)
+ void <init>(LootItemCondition[],NumberProvider,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.AllOfCondition
</summary>

```diff
- AllOfCondition allOf(List)
- void <clinit>()
- void <init>(List)
+ void <init>(LootItemCondition[])
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- Holder enchantment()
- int hashCode()
- List values()
+ LootItemCondition lambda$bonusLevelFlatChance$0(Enchantment,float[])
- LootItemCondition lambda$bonusLevelFlatChance$1(Enchantment,List)
- String toString()
- void <clinit>()
+ void <init>(Enchantment,float[])
- void <init>(Holder,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
- LootContext$EntityTarget entityTarget()
- Map scores()
+ Stream lambda$getReferencedContextParams$0(IntRange)
- Stream lambda$getReferencedContextParams$1(IntRange)
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- float lootingMultiplier()
- float percent()
- int hashCode()
+ LootItemCondition lambda$randomChanceAndLootingBoost$0(float,float)
- LootItemCondition lambda$randomChanceAndLootingBoost$1(float,float)
- String toString()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.TimeCheck
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- boolean equals(Object)
- int hashCode()
- IntRange value()
- Optional period()
- String toString()
- void <clinit>()
+ void <init>(Long,IntRange)
- void <init>(Optional,IntRange)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
</summary>

```diff
- WeatherCheck$Builder setRaining(boolean)
+ WeatherCheck$Builder setRaining(Boolean)
- WeatherCheck$Builder setThundering(boolean)
+ WeatherCheck$Builder setThundering(Boolean)
```

</details>
</details>
<hr/>