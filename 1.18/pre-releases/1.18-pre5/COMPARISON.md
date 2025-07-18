## Comparison with [1.18-pre4](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre4)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18-pre4</th><th>1.18-pre5</th></tr><tr><td>World version</td><td><pre>2850</pre></td><td><pre>2851</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741876</pre></td><td><pre>1073741877</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18-pre4</th><th>1.18-pre5</th></tr><tr><td>com.mojang:authlib</td><td><pre>3.2.37</pre></td><td><pre>3.2.38</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block_predicate_type
</summary>

```diff
+ minecraft:has_sturdy_face
+ minecraft:matching_block_tag
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:has_sturdy_face
+ minecraft:matching_block_tag
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
+ minecraft/tags/blocks/azalea_grows_on.json
+ minecraft/tags/blocks/azalea_root_replaceable.json
+ minecraft/tags/blocks/replaceable_plants.json
+ minecraft/tags/blocks/terracotta.json
+ minecraft/tags/items/dirt.json
+ minecraft/tags/items/terracotta.json
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
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.QuartPos +1M
```
```
XXX.data.worldgen.SurfaceRuleData +2M
```
```
XXX.data.worldgen.TerrainProvider +2M
```
```
XXX.worldgen.features.CaveFeatures +7M -7M
```
```
XXX.worldgen.features.VegetationFeatures +2M -2M
```
```
XXX.minecraft.tags.BlockTags +4P
```
```
XXX.minecraft.tags.ItemTags +2P
```
```
XXX.minecraft.util.BitStorage +1P
```
```
XXX.level.chunk.PalettedContainer +5M -3M
```
```
XXX.level.levelgen.Aquifer +1M -1M
```
```
XXX.level.levelgen.Aquifer$NoiseBasedAquifer +1M -1M | -1P
```
```
XXX.level.levelgen.BelowZeroRetrogen +4M -3M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +2M -2M
```
```
XXX.level.levelgen.SurfaceRules +1M -1M
```
```
XXX.level.levelgen.SurfaceRules$Context +2M | +6P
```
```
XXX.level.levelgen.SurfaceSystem +1M -2M | -2P
```
```
XXX.levelgen.blockpredicates.BlockPredicate +4M
```

</details>
<details>
<summary>
net.minecraft.core.QuartPos
</summary>

```diff
- int quartLocal(int)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.SurfaceRuleData
</summary>

```diff
- SurfaceRules$RuleSource overworldLike(boolean,boolean,boolean)
- SurfaceRules$RuleSource[] lambda$overworldLike$0(int)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.TerrainProvider
</summary>

```diff
- TerrainShaper caves()
- TerrainShaper floatingIslands()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.CaveFeatures
</summary>

```diff
+ ConfiguredFeature lambda$static$10()
+ ConfiguredFeature lambda$static$11()
+ ConfiguredFeature lambda$static$12()
+ ConfiguredFeature lambda$static$13()
+ ConfiguredFeature lambda$static$3()
+ ConfiguredFeature lambda$static$4()
+ ConfiguredFeature lambda$static$9()
- PlacedFeature lambda$static$10()
- PlacedFeature lambda$static$11()
- PlacedFeature lambda$static$12()
- PlacedFeature lambda$static$13()
- PlacedFeature lambda$static$3()
- PlacedFeature lambda$static$4()
- PlacedFeature lambda$static$9()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.VegetationFeatures
</summary>

```diff
+ ConfiguredFeature lambda$static$12()
+ ConfiguredFeature lambda$static$13()
- PlacedFeature lambda$static$12()
- PlacedFeature lambda$static$13()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
- int lambda$read$6(IdMap,Palette,int)
+ int lambda$read$6(IdMap,Palette,SimpleBitStorage,int)
- int lambda$write$7(HashMapPalette,int)
+ void lambda$count$7(Int2IntMap,int)
- void lambda$count$8(Int2IntMap,int)
+ void lambda$count$8(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$count$9(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void swapPalette(int[],IntUnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,NoiseSampler,int,int,Aquifer$FluidPicker)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
</summary>

```diff
- void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
+ void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,NoiseSampler,int,int,Aquifer$FluidPicker)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.BelowZeroRetrogen
</summary>

```diff
+ boolean hasAllBedrockMissing()
- boolean hasBedrockHole(int,int)
- boolean hasBedrockHoles()
- void applyBedrockMask(ProtoChunk)
- void lambda$applyBedrockMask$6(ProtoChunk,BlockPos)
+ void lambda$removeBedrock$6(ProtoChunk,BlockPos)
+ void removeBedrock(ProtoChunk)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ Aquifer$FluidStatus lambda$new$5(Aquifer$FluidStatus,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
- Aquifer$FluidStatus lambda$new$5(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
+ BlockState debugPreliminarySurfaceLevel(int,int,int,BlockState)
- BlockState debugPreliminarySurfaceLevel(NoiseChunk,int,int,int,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules
</summary>

```diff
+ SurfaceRules$RuleSource sequence(SurfaceRules$RuleSource,SurfaceRules$RuleSource[])
- SurfaceRules$RuleSource sequence(SurfaceRules$RuleSource[])
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceRules$Context
</summary>

```diff
- int blockCoordToSurfaceCell(int)
- int surfaceCellToBlockCoord(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.SurfaceSystem
</summary>

```diff
+ int getMinSurfaceLevel(NoiseChunk,int,int)
+ void <init>(NoiseSampler,Registry,BlockState,int,long,WorldgenRandom$Algorithm)
- void <init>(Registry,BlockState,int,long,WorldgenRandom$Algorithm)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
</summary>

```diff
- BlockPredicate hasSturdyFace(Vec3i,Direction)
- BlockPredicate matchesBlocks(List)
- BlockPredicate matchesTag(Tag,Vec3i)
- BlockPredicate matchesTag(Tag)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.levelgen.blockpredicates.HasSturdyFacePredicate
+ XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.QuartPos +1M
```
```
XXX.data.worldgen.SurfaceRuleData +2M
```
```
XXX.data.worldgen.TerrainProvider +2M
```
```
XXX.worldgen.features.CaveFeatures +7M -7M
```
```
XXX.worldgen.features.VegetationFeatures +2M -2M
```
```
XXX.minecraft.util.SimpleBitStorage +2M -2M
```
```
XXX.minecraft.util.ZeroBitStorage +1M
```
```
XXX.ai.goal.PanicGoal +1M -1M | +1P
```
```
XXX.level.chunk.PalettedContainer$Data -1M
```
```
XXX.level.levelgen.NoiseChunk +8M -9M | +2P -1P
```
```
XXX.level.levelgen.NoiseGeneratorSettings +6M -4M | -1P
```
```
XXX.levelgen.blending.BlendingData +3M -1M | +2P
```
```
XXX.levelgen.blockpredicates.BlockPredicateType +2P
```
```
XXX.levelgen.feature.RootSystemFeature +1M -1M
```
```
XXX.feature.configurations.RootSystemConfiguration +3M -2M | +1P
```
```
XXX.levelgen.heightproviders.UniformHeight +1P
```

</details>
<details>
<summary>
net.minecraft.core.QuartPos
</summary>

```diff
- int quartLocal(int)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.SurfaceRuleData
</summary>

```diff
- SurfaceRules$RuleSource overworldLike(boolean,boolean,boolean)
- SurfaceRules$RuleSource[] lambda$overworldLike$0(int)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.TerrainProvider
</summary>

```diff
- TerrainShaper caves()
- TerrainShaper floatingIslands()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.CaveFeatures
</summary>

```diff
+ ConfiguredFeature lambda$static$10()
+ ConfiguredFeature lambda$static$11()
+ ConfiguredFeature lambda$static$12()
+ ConfiguredFeature lambda$static$13()
+ ConfiguredFeature lambda$static$3()
+ ConfiguredFeature lambda$static$4()
+ ConfiguredFeature lambda$static$9()
- PlacedFeature lambda$static$10()
- PlacedFeature lambda$static$11()
- PlacedFeature lambda$static$12()
- PlacedFeature lambda$static$13()
- PlacedFeature lambda$static$3()
- PlacedFeature lambda$static$4()
- PlacedFeature lambda$static$9()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.features.VegetationFeatures
</summary>

```diff
+ ConfiguredFeature lambda$static$12()
+ ConfiguredFeature lambda$static$13()
- PlacedFeature lambda$static$12()
- PlacedFeature lambda$static$13()
```

</details>
<details>
<summary>
net.minecraft.util.SimpleBitStorage
</summary>

```diff
- void <init>(int,int,int[])
+ void <init>(int,int,IntStream)
+ void lambda$new$0(MutableInt,int)
- void unpack(int[])
```

</details>
<details>
<summary>
net.minecraft.util.ZeroBitStorage
</summary>

```diff
- void unpack(int[])
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.PanicGoal
</summary>

```diff
+ BlockPos lookForWater(BlockGetter,Entity,int,int)
- BlockPos lookForWater(BlockGetter,Entity,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer$Data
</summary>

```diff
+ void set(int,Object)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseChunk
</summary>

```diff
- int computePreliminarySurfaceLevel(long)
- int preliminarySurfaceLevel(int,int)
+ TerrainInfo lambda$terrainInfoWide$1(NoiseSampler,long)
+ TerrainInfo terrainInfoInterpolated(int,int)
+ TerrainInfo terrainInfoWide(NoiseSampler,int,int)
- void lambda$advanceCellX$2(int,NoiseChunk$NoiseInterpolator)
+ void lambda$advanceCellX$3(int,NoiseChunk$NoiseInterpolator)
- void lambda$initializeForFirstCellX$1(NoiseChunk$NoiseInterpolator)
+ void lambda$initializeForFirstCellX$2(NoiseChunk$NoiseInterpolator)
- void lambda$selectCellYZ$3(int,int,NoiseChunk$NoiseInterpolator)
+ void lambda$selectCellYZ$4(int,int,NoiseChunk$NoiseInterpolator)
- void lambda$updateForX$5(double,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForX$6(double,NoiseChunk$NoiseInterpolator)
- void lambda$updateForY$4(double,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForY$5(double,NoiseChunk$NoiseInterpolator)
- void lambda$updateForZ$6(double,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForZ$7(double,NoiseChunk$NoiseInterpolator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
- NoiseGeneratorSettings caves()
- NoiseGeneratorSettings end()
+ NoiseGeneratorSettings endLikePreset(StructureSettings,BlockState,BlockState,boolean,boolean)
- NoiseGeneratorSettings floatingIslands()
- NoiseGeneratorSettings nether()
+ NoiseGeneratorSettings netherLikePreset(StructureSettings,BlockState,BlockState)
- NoiseGeneratorSettings overworld(boolean,boolean)
+ NoiseGeneratorSettings overworld(StructureSettings,boolean,boolean)
+ NoiseGeneratorSettings register(ResourceKey,NoiseGeneratorSettings)
- void register(ResourceKey,NoiseGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blending.BlendingData
</summary>

```diff
- double read1(ChunkAccess,BlockPos$MutableBlockPos)
- double read7(ChunkAccess,BlockPos$MutableBlockPos)
- double[] getDensityColumn(ChunkAccess,int,int,int)
+ double[] getDensityColumn(ChunkAccess,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RootSystemFeature
</summary>

```diff
+ boolean tryPlaceAzaleaTree(WorldGenLevel,ChunkGenerator,RootSystemConfiguration,Random,BlockPos)
- void placeDirt(BlockPos,int,WorldGenLevel,RootSystemConfiguration,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
</summary>

```diff
+ App lambda$static$12(RecordCodecBuilder$Instance)
- App lambda$static$13(RecordCodecBuilder$Instance)
- BlockPredicate lambda$static$12(RootSystemConfiguration)
- void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int,int,BlockPredicate)
+ void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int,int)
```

</details>
</details>
<hr/>