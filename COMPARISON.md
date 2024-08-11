## Comparison with [21w15a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w15a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">21w15a</th><th>21w16a</th></tr><tr><td>World version</td><td><code>2709</code></td><td><code>2711</code></td></tr><tr><td>Protocol version</td><td><code>1073741846</code></td><td><code>1073741847</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
custom_stat.txt
</summary>

```diff
- minecraft:play_one_minute
+ minecraft:play_time
+ minecraft:total_world_time
```

</details>






































<details>
<summary>
worldgen/feature.txt
</summary>

```diff
- minecraft:emerald_ore
+ minecraft:replace_single_block
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
- minecraft:play_one_minute
+ minecraft:play_time
+ minecraft:total_world_time
```

</details>






































<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:emerald_ore
+ minecraft:replace_single_block
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
dried_kelp_block.json
</summary>

```
Type: minecraft:crafting_shapeless -> minecraft:crafting_shaped
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ multiplayer.applyingPack: Applying resource pack
- stat.minecraft.play_one_minute: Time Played
+ stat.minecraft.play_time: Time Played
+ stat.minecraft.total_world_time: Time with World Open
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
- minecraft/tags/blocks/lush_plants_replaceable.json
+ minecraft/tags/blocks/moss_replaceable.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/shaders/core/rendertype_text_intensity_see_through.fsh
+ minecraft/shaders/core/rendertype_text_intensity_see_through.json
+ minecraft/shaders/core/rendertype_text_intensity_see_through.vsh
+ minecraft/shaders/core/rendertype_text_intensity.fsh
+ minecraft/shaders/core/rendertype_text_intensity.json
+ minecraft/shaders/core/rendertype_text_intensity.vsh
- minecraft/textures/block/root_vines_head.png
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
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BarrelBlockEntity$1
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
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
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
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
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
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
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
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
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkSensorBlock
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
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SupportType
- net.minecraft.world.level.block.SupportType$1
+ net.minecraft.world.level.block.SupportType$2
- net.minecraft.world.level.block.SupportType$3
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrassBlock
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TintedGlassBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVinesBlock
- net.minecraft.world.level.block.TwistingVinesPlantBlock
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WeatheringCopper
+ net.minecraft.world.level.block.WeatheringCopper$WeatherState
- net.minecraft.world.level.block.WeatheringCopperFullBlock
+ net.minecraft.world.level.block.WeatheringCopperSlabBlock
- net.minecraft.world.level.block.WeatheringCopperStairBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVinesBlock
+ net.minecraft.world.level.block.WeepingVinesPlantBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.levelgen.Aquifer$1
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
+ net.minecraft.world.level.levelgen.BaseStoneSource
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.Cavifier
- net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Column
- net.minecraft.world.level.levelgen.Column$Line
+ net.minecraft.world.level.levelgen.Column$Range
- net.minecraft.world.level.levelgen.Column$Ray
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.Decoratable
+ net.minecraft.world.level.levelgen.DepthBasedReplacingBaseStoneSource
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
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.data.models.BlockModelGenerators +1M
```
```
XXX.data.recipes.RecipeProvider +12M -3M
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M | -1P
```
```
XXX.data.worldgen.BiomeDefaultFeatures +1M
```
```
XXX.data.worldgen.Features$States +3P
```
```
XXX.minecraft.stats.ServerStatsCounter -2P
```
```
XXX.minecraft.stats.Stats +2P -1P
```
```
XXX.level.block.AzaleaBlock +4M -1M | +2P -1P
```
```
XXX.level.block.InfestedBlock +6M -1M | +2P
```
```
XXX.level.levelgen.NoiseGeneratorSettings +2M -1M | +1P
```
```
XXX.levelgen.carver.CanyonCarverConfiguration +1M -1M
```
```
XXX.levelgen.carver.CanyonWorldCarver +3M -3M
```
```
XXX.levelgen.carver.CarverDebugSettings +6M -1M | +3P
```
```
XXX.levelgen.carver.CaveCarverConfiguration +2M -2M
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +1M -1M
```
```
XXX.levelgen.carver.UnderwaterCanyonWorldCarver +2M -2M
```
```
XXX.levelgen.carver.WorldCarver +4M -3M | +2P -1P
```
```
XXX.levelgen.structure.StructurePiece +1M -1M
```

</details>


































































































































































































































<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- void createInfestedDeepslate()
```

</details>
























<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- String getBlastingRecipeName(ItemLike)
+ String getBlockName(ItemLike)
- String getConversionRecipeName(ItemLike,ItemLike)
+ String getFromName(ItemLike,ItemLike)
- String getItemName(ItemLike)
- String getSimpleRecipeName(ItemLike)
- String getSmeltingRecipeName(ItemLike)
+ void compactMaterialRecipes(Consumer,ItemLike,ItemLike)
- void nineBlockStorageRecipes(Consumer,ItemLike,ItemLike,String,String,String,String)
- void nineBlockStorageRecipes(Consumer,ItemLike,ItemLike)
- void nineBlockStorageRecipesRecipesWithCustomUnpacking(Consumer,ItemLike,ItemLike,String,String)
- void nineBlockStorageRecipesWithCustomPacking(Consumer,ItemLike,ItemLike,String,String)
- void oneToOneConversionRecipe(Consumer,ItemLike,ItemLike,String,int)
- void oneToOneConversionRecipe(Consumer,ItemLike,ItemLike,String)
- void simpleCookingRecipe(Consumer,String,SimpleCookingSerializer,int,ItemLike,ItemLike,float)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,List,Map,Advancement$Builder,ResourceLocation)
+ void <init>(ShapedRecipeBuilder,ResourceLocation,Item,int,String,List,Map,Advancement$Builder,ResourceLocation)
```

</details>
















<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
- void addDefaultUndergroundVariety(BiomeGenerationSettings$Builder,boolean)
```

</details>




























































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.AzaleaBlock
</summary>

```diff
- boolean isBonemealSuccess(Level,Random,BlockPos,BlockState)
- boolean isValidBonemealTarget(BlockGetter,BlockPos,BlockState,boolean)
- void performBonemeal(ServerLevel,Random,BlockPos,BlockState)
+ VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
- VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>







































































<details>
<summary>
net.minecraft.world.level.block.InfestedBlock
</summary>

```diff
- BlockState getNewStateWithProperties(Map,BlockState,Supplier)
- BlockState hostStateByInfested(BlockState)
- BlockState infestedStateByHost(BlockState)
- BlockState lambda$getNewStateWithProperties$2(Supplier,BlockState)
- BlockState lambda$hostStateByInfested$1()
- BlockState lambda$infestedStateByHost$0(BlockState)
+ BlockState stateByHostBlock(Block)
```

</details>



































































































<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
- boolean isOreVeinsEnabled()
- void <init>(StructureSettings,NoiseSettings,BlockState,BlockState,int,int,int,int,boolean,boolean,boolean,boolean,boolean)
+ void <init>(StructureSettings,NoiseSettings,BlockState,BlockState,int,int,int,int,boolean,boolean,boolean,boolean)
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
</summary>

```diff
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,boolean,CarverDebugSettings,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
+ void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,CarverDebugSettings,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,Random,Aquifer,ChunkPos,BitSet)
+ boolean carve(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- boolean carve(CarvingContext,CarverConfiguration,ChunkAccess,Function,Random,Aquifer,ChunkPos,BitSet)
+ boolean carve(CarvingContext,CarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- void doCarve(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,long,Aquifer,double,double,double,float,float,float,int,int,double,BitSet)
+ void doCarve(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,float,float,int,int,double,BitSet)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverDebugSettings
</summary>

```diff
- BlockState getBarrierState()
- BlockState getLavaState()
- BlockState getWaterState()
- CarverDebugSettings of(BlockState,BlockState,BlockState,BlockState)
- CarverDebugSettings of(boolean,BlockState,BlockState,BlockState,BlockState)
- void <init>(boolean,BlockState,BlockState,BlockState,BlockState)
+ void <init>(boolean,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
</summary>

```diff
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,boolean,CarverDebugSettings,FloatProvider,FloatProvider,FloatProvider)
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,boolean,FloatProvider,FloatProvider,FloatProvider)
+ void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,CarverDebugSettings,FloatProvider,FloatProvider,FloatProvider)
+ void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,FloatProvider,FloatProvider,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,ChunkAccess,Function,Random,Aquifer,ChunkPos,BitSet)
+ boolean carve(CarvingContext,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
</summary>

```diff
- boolean carveBlock(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CanyonCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
- boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
- BlockState getCarveState(CarvingContext,CarverConfiguration,BlockPos,Aquifer)
+ BlockState getCaveAirState(CarverConfiguration)
- BlockState getDebugState(CarverConfiguration,BlockState)
- boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
- boolean carveEllipsoid(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,Aquifer,double,double,double,double,double,BitSet,WorldCarver$CarveSkipChecker)
+ boolean carveEllipsoid(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,BitSet,WorldCarver$CarveSkipChecker)
```

</details>






































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructurePiece
</summary>

```diff
+ void maybeGenerateBlock(WorldGenLevel,BoundingBox,Random,float,int,int,int,BlockState,boolean)
- void maybeGenerateBlock(WorldGenLevel,BoundingBox,Random,float,int,int,int,BlockState)
```

</details>





























































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.Camera$NearPlane
- net.minecraft.util.datafix.fixes.StatsRenameFix
+ net.minecraft.util.datafix.fixes.StriderGravityFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.SwimStatsRenameFix
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
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
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity$1
+ net.minecraft.world.level.block.entity.ChestLidController
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.ContainerOpenersCounter
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.SculkSensorBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickingBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.AzaleaTreeGrower
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
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MossBlock
+ net.minecraft.world.level.block.MultifaceBlock
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
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
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
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
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
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.BaseStoneSource
+ net.minecraft.world.level.levelgen.Beardifier
- net.minecraft.world.level.levelgen.Cavifier
+ net.minecraft.world.level.levelgen.Cavifier$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.DepthBasedReplacingBaseStoneSource
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
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator$OreVeinNoiseSource
- net.minecraft.world.level.levelgen.OreVeinifier
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.GlConst +2P -3P
```
```
net.minecraft.SharedConstants +5P -1P
```
```
XXX.minecraft.client.Camera +1M
```
```
XXX.client.renderer.GameRenderer +2M | +2P
```
```
XXX.client.renderer.RenderType +4M | +2P
```
```
XXX.renderer.entity.FishingHookRenderer +1P
```
```
XXX.client.resources.ClientPackSource +8M -7M | +1P
```
```
XXX.client.server.IntegratedServer +1M
```
```
XXX.data.recipes.RecipeBuilder +3M | +2P -1P
```
```
XXX.data.recipes.ShapedRecipeBuilder +1M -3M | -1P
```
```
XXX.data.recipes.ShapelessRecipeBuilder +1M -3M | -1P
```
```
XXX.data.recipes.SimpleCookingRecipeBuilder +3M -2M
```
```
XXX.data.recipes.SingleItemRecipeBuilder +4M -2M
```
```
XXX.data.worldgen.Carvers +1P -1P
```
```
XXX.data.worldgen.Features +3P
```
```
XXX.minecraft.tags.BlockTags +1P -1P
```
```
XXX.minecraft.util.StringUtil +1M | +1P
```
```
XXX.minecraft.world.InteractionResult +1M | +1P
```
```
XXX.world.entity.Entity +3M -2M | +1P -1P
```
```
XXX.world.entity.LivingEntity +2M
```
```
XXX.world.item.DebugStickItem +1M -1M
```
```
XXX.level.chunk.ChunkGenerator +1M
```
```
XXX.level.levelgen.Aquifer +2M -14M | +3P -24P
```
```
XXX.level.levelgen.NoiseInterpolator +1M -1M
```
```
XXX.level.levelgen.SingleBaseStoneSource +1M -1M
```
```
XXX.levelgen.carver.CarverConfiguration +4M -3M | +1P
```
```
XXX.levelgen.carver.CaveWorldCarver +4M -4M
```
```
XXX.levelgen.carver.NetherWorldCarver +2M -2M
```
```
XXX.levelgen.carver.UnderwaterCaveWorldCarver +3M -3M
```
```
XXX.levelgen.feature.Feature +1P -1P
```
```
XXX.levelgen.feature.RootSystemFeature +1M
```
```
XXX.levelgen.feature.StructureFeature +1M
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +3M -3M | +1P -2P
```
```
XXX.feature.configurations.RootSystemConfiguration +3M -2M | +1P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor +2M -1M
```
```
XXX.level.material.MaterialColor +1P
```

</details>




























































































































































































































































<details>
<summary>
net.minecraft.client.Camera
</summary>

```diff
- Camera$NearPlane getNearPlane()
```

</details>




























































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
- ShaderInstance getRendertypeTextIntensitySeeThroughShader()
- ShaderInstance getRendertypeTextIntensityShader()
```

</details>





















<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
- RenderType lambda$static$18(ResourceLocation)
- RenderType lambda$static$19(ResourceLocation)
- RenderType textIntensity(ResourceLocation)
- RenderType textIntensitySeeThrough(ResourceLocation)
```

</details>












































































































































































<details>
<summary>
net.minecraft.client.resources.ClientPackSource
</summary>

```diff
- CompletableFuture downloadAndSelectResourcePack(String,String,boolean)
+ CompletableFuture downloadAndSelectResourcePack(String,String)
+ CompletionStage lambda$downloadAndSelectResourcePack$2(String,File,Object)
- CompletionStage lambda$downloadAndSelectResourcePack$3(String,File,boolean,Object)
+ PackResources lambda$createProgrammerArtPack$7(File)
- PackResources lambda$createProgrammerArtPack$9(File)
+ PackResources lambda$setServerPack$6(File)
- PackResources lambda$setServerPack$7(File)
+ void lambda$downloadAndSelectResourcePack$5(File,Void,Throwable)
- void lambda$downloadAndSelectResourcePack$6(File,Void,Throwable)
- void lambda$null$2(boolean,Minecraft)
+ void lambda$null$3(Minecraft,boolean)
- void lambda$null$4(Minecraft,boolean)
+ void lambda$null$4(Minecraft)
- void lambda$null$5(Minecraft)
```

</details>
















































<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- void tickPaused()
```

</details>











































































































































































<details>
<summary>
net.minecraft.data.recipes.RecipeBuilder
</summary>

```diff
- ResourceLocation getDefaultRecipeId(ItemLike)
- void save(Consumer,String)
- void save(Consumer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder
</summary>

```diff
- Item getResult()
+ void <clinit>()
+ void save(Consumer,String)
+ void save(Consumer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapelessRecipeBuilder
</summary>

```diff
- Item getResult()
+ void <clinit>()
+ void save(Consumer,String)
+ void save(Consumer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SimpleCookingRecipeBuilder
</summary>

```diff
- Item getResult()
- RecipeBuilder group(String)
- RecipeBuilder unlockedBy(String,CriterionTriggerInstance)
+ void save(Consumer,String)
+ void save(Consumer)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.SingleItemRecipeBuilder
</summary>

```diff
- Item getResult()
- RecipeBuilder group(String)
- RecipeBuilder unlockedBy(String,CriterionTriggerInstance)
- SingleItemRecipeBuilder unlockedBy(String,CriterionTriggerInstance)
+ SingleItemRecipeBuilder unlocks(String,CriterionTriggerInstance)
+ void save(Consumer,String)
```

</details>






























































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.StringUtil
</summary>

```diff
- boolean endsWithNewLine(String)
```

</details>























































































































































<details>
<summary>
net.minecraft.world.InteractionResult
</summary>

```diff
- boolean shouldAwardStats()
```

</details>
















<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean hasGlowingTag()
- boolean isCurrentlyGlowing()
+ boolean isGlowing()
+ void setGlowing(boolean)
- void setGlowingTag(boolean)
```

</details>










<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean isCurrentlyGlowing()
- void updateGlowingStatus()
```

</details>






















































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.item.DebugStickItem
</summary>

```diff
- boolean handleInteraction(Player,BlockState,LevelAccessor,BlockPos,boolean,ItemStack)
+ void handleInteraction(Player,BlockState,LevelAccessor,BlockPos,boolean,ItemStack)
```

</details>

























































































































































































































































































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
- Aquifer createAquifer(ChunkAccess)
```

</details>






















































<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- Aquifer create(ChunkPos,NormalNoise,NormalNoise,NormalNoise,NoiseGeneratorSettings,NoiseSampler,int,int)
- Aquifer createDisabled(int,BlockState)
+ boolean isLavaLevel(int)
+ boolean shouldScheduleWaterUpdate()
+ double calculatePressure(int,double,int,int)
+ double getLastBarrierDensity()
+ double similarity(int,int)
+ int computeAquifer(int,int,int)
+ int getIndex(int,int,int)
+ int getLastWaterLevel()
+ int getWaterLevel(long)
+ int gridX(int)
+ int gridY(int)
+ int gridZ(int)
+ void <init>(int,int,NormalNoise,NormalNoise,NoiseGeneratorSettings,NoiseSampler,int,int)
+ void computeAt(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseInterpolator
</summary>

```diff
- void <init>(int,int,int,ChunkPos,int,NoiseInterpolator$NoiseColumnFiller)
+ void <init>(int,int,int,int,int,int,NoiseInterpolator$NoiseColumnFiller)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.SingleBaseStoneSource
</summary>

```diff
- BlockState getBaseBlock(int,int,int)
+ BlockState getBaseStone(int,int,int)
```

</details>





<details>
<summary>
net.minecraft.world.level.levelgen.carver.CarverConfiguration
</summary>

```diff
+ App lambda$static$5(RecordCodecBuilder$Instance)
- App lambda$static$6(RecordCodecBuilder$Instance)
- Boolean lambda$null$4(CarverConfiguration)
+ CarverDebugSettings lambda$null$4(CarverConfiguration)
- CarverDebugSettings lambda$null$5(CarverConfiguration)
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,boolean,CarverDebugSettings)
+ void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,CarverDebugSettings)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,CarverConfiguration,ChunkAccess,Function,Random,Aquifer,ChunkPos,BitSet)
+ boolean carve(CarvingContext,CarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- boolean carve(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,Random,Aquifer,ChunkPos,BitSet)
+ boolean carve(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- void createRoom(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,Aquifer,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
+ void createRoom(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
- void createTunnel(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,Aquifer,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
+ void createTunnel(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NetherWorldCarver
</summary>

```diff
- boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
- boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
</summary>

```diff
- boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
- boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer,MutableBoolean)
+ boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
- boolean carveBlock(WorldCarver,ChunkAccess,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,Aquifer)
+ boolean carveBlock(WorldCarver,ChunkAccess,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int)
```

</details>









































<details>
<summary>
net.minecraft.world.level.levelgen.feature.RootSystemFeature
</summary>

```diff
- boolean isAllowedTreeSpace(BlockState,int,int)
```

</details>









<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- WeightedRandomList getSpecialUndergroundWaterAnimals()
```

</details>




























<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ App lambda$static$2(RecordCodecBuilder$Instance)
+ BlockState lambda$null$0(ReplaceBlockConfiguration)
+ BlockState lambda$null$1(ReplaceBlockConfiguration)
- List lambda$null$0(ReplaceBlockConfiguration)
- void <init>(List)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ App lambda$static$11(RecordCodecBuilder$Instance)
- App lambda$static$12(RecordCodecBuilder$Instance)
- Integer lambda$null$11(RootSystemConfiguration)
- void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int,int)
+ void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int)
```

</details>








































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
</summary>

```diff
- boolean hasSturdyNeighbours(WorldGenLevel,BoundingBox,int,int,int,int)
- void maybePlaceCobWeb(WorldGenLevel,BoundingBox,Random,float,int,int,int)
+ void placeCobWeb(WorldGenLevel,BoundingBox,Random,float,int,int,int)
```

</details>
</details>