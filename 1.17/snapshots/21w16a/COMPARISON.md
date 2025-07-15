## Comparison with [21w15a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w15a)

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
<table><tr><th></th><th align="left">21w15a</th><th>21w16a</th></tr><tr><td>World version</td><td><pre>2709</pre></td><td><pre>2711</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741846</pre></td><td><pre>1073741847</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">21w15a</th><th>21w16a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
custom_stat
</summary>

```diff
- minecraft:play_one_minute
+ minecraft:play_time
+ minecraft:total_world_time
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:emerald_ore
+ minecraft:replace_single_block
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
dried_kelp_block.json
</summary>

```
Type: minecraft:crafting_shapeless -> minecraft:crafting_shaped
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
+ multiplayer.applyingPack: Applying resource pack
- stat.minecraft.play_one_minute: Time Played
+ stat.minecraft.play_time: Time Played
+ stat.minecraft.total_world_time: Time with World Open
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
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$1
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
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.ContainerOpenersCounter
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FurnaceBlockEntity
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
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
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
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MossBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
- XXX.level.block.NetherrackBlock
+ XXX.level.block.NetherSproutsBlock
- XXX.level.block.NetherVines
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkSensorBlock
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SporeBlossomBlock
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
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
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
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
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
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer$AquiferStatus
+ XXX.level.levelgen.BaseStoneSource
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Cavifier
- XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Decoratable
+ XXX.level.levelgen.DepthBasedReplacingBaseStoneSource
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
- XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.OreVeinifier$VeinType
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
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
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
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
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
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
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.SwimStatsRenameFix
- XXX.level.block.InfestedRotatedPillarBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.LanternBlock
+ XXX.level.block.LavaCauldronBlock
- XXX.level.block.LayeredCauldronBlock
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LightBlock
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
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
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RodBlock
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkSensorBlock
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
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
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StemGrownBlock
- XXX.level.block.StoneButtonBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
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
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.BaseStoneSource
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Cavifier
+ XXX.level.levelgen.Cavifier$QuantizedSpaghettiRarity
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Decoratable
- XXX.level.levelgen.DepthBasedReplacingBaseStoneSource
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
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseBasedChunkGenerator$OreVeinNoiseSource
- XXX.level.levelgen.OreVeinifier
- XXX.minecraft.client.Camera$NearPlane
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
<hr/>