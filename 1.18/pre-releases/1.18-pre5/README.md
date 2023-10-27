<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.18-pre5 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.18-pre5</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2021-11-19T15:47:09+00:00</td></tr>
<tr><th>SHA1</th><td>1c7297b2645db73c3548d9c7bcec9d1f1daf9a3d</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/1c7297b2645db73c3548d9c7bcec9d1f1daf9a3d/1.18-pre5.json">https://piston-meta.mojang.com/v1/packages/1c7297b2645db73c3548d9c7bcec9d1f1daf9a3d/1.18-pre5.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json">https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/c29d03e9c6a21a3234a947e1025793c3cc40c13b/server.jar">https://piston-data.mojang.com/v1/objects/c29d03e9c6a21a3234a947e1025793c3cc40c13b/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/438bd2a54c066d09195c85c20cfd76818d725dde/server.txt">https://piston-data.mojang.com/v1/objects/438bd2a54c066d09195c85c20cfd76818d725dde/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/561446f5e8345f0d77b56f7874ce8aa71cdb1c62/client.jar">https://piston-data.mojang.com/v1/objects/561446f5e8345f0d77b56f7874ce8aa71cdb1c62/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/77225d67ef98f5af3990facda860d1e4fd7118b9/client.txt">https://piston-data.mojang.com/v1/objects/77225d67ef98f5af3990facda860d1e4fd7118b9/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre4">1.18-pre4</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
+ net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
- net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
```

</details>


<details><summary>net.minecraft.core.QuartPos</summary>

```diff
+ int quartLocal(int)
```

</details>


<details><summary>net.minecraft.data.worldgen.SurfaceRuleData</summary>

```diff
+ SurfaceRules$RuleSource overworldLike(boolean,boolean,boolean)
+ SurfaceRules$RuleSource[] lambda$overworldLike$0(int)
```

</details>


<details><summary>net.minecraft.data.worldgen.TerrainProvider</summary>

```diff
+ TerrainShaper caves()
+ TerrainShaper floatingIslands()
```

</details>


<details><summary>net.minecraft.data.worldgen.features.CaveFeatures</summary>

```diff
- ConfiguredFeature lambda$static$10()
- ConfiguredFeature lambda$static$11()
- ConfiguredFeature lambda$static$12()
- ConfiguredFeature lambda$static$13()
- ConfiguredFeature lambda$static$3()
- ConfiguredFeature lambda$static$4()
- ConfiguredFeature lambda$static$9()
+ PlacedFeature lambda$static$10()
+ PlacedFeature lambda$static$11()
+ PlacedFeature lambda$static$12()
+ PlacedFeature lambda$static$13()
+ PlacedFeature lambda$static$3()
+ PlacedFeature lambda$static$4()
+ PlacedFeature lambda$static$9()
```

</details>


<details><summary>net.minecraft.data.worldgen.features.VegetationFeatures</summary>

```diff
- ConfiguredFeature lambda$static$12()
- ConfiguredFeature lambda$static$13()
+ PlacedFeature lambda$static$12()
+ PlacedFeature lambda$static$13()
```

</details>


<details><summary>net.minecraft.util.SimpleBitStorage</summary>

```diff
+ void <init>(int,int,int[])
- void <init>(int,int,IntStream)
- void lambda$new$0(MutableInt,int)
+ void unpack(int[])
```

</details>


<details><summary>net.minecraft.util.ZeroBitStorage</summary>

```diff
+ void unpack(int[])
```

</details>


<details><summary>net.minecraft.world.entity.ai.goal.PanicGoal</summary>

```diff
- BlockPos lookForWater(BlockGetter,Entity,int,int)
+ BlockPos lookForWater(BlockGetter,Entity,int)
```

</details>


<details><summary>net.minecraft.world.level.chunk.PalettedContainer$Data</summary>

```diff
- void set(int,Object)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseChunk</summary>

```diff
+ int computePreliminarySurfaceLevel(long)
+ int preliminarySurfaceLevel(int,int)
- TerrainInfo lambda$terrainInfoWide$1(NoiseSampler,long)
- TerrainInfo terrainInfoInterpolated(int,int)
- TerrainInfo terrainInfoWide(NoiseSampler,int,int)
+ void lambda$advanceCellX$2(int,NoiseChunk$NoiseInterpolator)
- void lambda$advanceCellX$3(int,NoiseChunk$NoiseInterpolator)
+ void lambda$initializeForFirstCellX$1(NoiseChunk$NoiseInterpolator)
- void lambda$initializeForFirstCellX$2(NoiseChunk$NoiseInterpolator)
+ void lambda$selectCellYZ$3(int,int,NoiseChunk$NoiseInterpolator)
- void lambda$selectCellYZ$4(int,int,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForX$5(double,NoiseChunk$NoiseInterpolator)
- void lambda$updateForX$6(double,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForY$4(double,NoiseChunk$NoiseInterpolator)
- void lambda$updateForY$5(double,NoiseChunk$NoiseInterpolator)
+ void lambda$updateForZ$6(double,NoiseChunk$NoiseInterpolator)
- void lambda$updateForZ$7(double,NoiseChunk$NoiseInterpolator)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseGeneratorSettings</summary>

```diff
+ NoiseGeneratorSettings caves()
+ NoiseGeneratorSettings end()
- NoiseGeneratorSettings endLikePreset(StructureSettings,BlockState,BlockState,boolean,boolean)
+ NoiseGeneratorSettings floatingIslands()
+ NoiseGeneratorSettings nether()
- NoiseGeneratorSettings netherLikePreset(StructureSettings,BlockState,BlockState)
+ NoiseGeneratorSettings overworld(boolean,boolean)
- NoiseGeneratorSettings overworld(StructureSettings,boolean,boolean)
- NoiseGeneratorSettings register(ResourceKey,NoiseGeneratorSettings)
+ void register(ResourceKey,NoiseGeneratorSettings)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.blending.BlendingData</summary>

```diff
+ double read1(ChunkAccess,BlockPos$MutableBlockPos)
+ double read7(ChunkAccess,BlockPos$MutableBlockPos)
+ double[] getDensityColumn(ChunkAccess,int,int,int)
- double[] getDensityColumn(ChunkAccess,int,int)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.RootSystemFeature</summary>

```diff
- boolean tryPlaceAzaleaTree(WorldGenLevel,ChunkGenerator,RootSystemConfiguration,Random,BlockPos)
+ void placeDirt(BlockPos,int,WorldGenLevel,RootSystemConfiguration,Random)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration</summary>

```diff
- App lambda$static$12(RecordCodecBuilder$Instance)
+ App lambda$static$13(RecordCodecBuilder$Instance)
+ BlockPredicate lambda$static$12(RootSystemConfiguration)
+ void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int,int,BlockPredicate)
- void <init>(Supplier,int,int,ResourceLocation,BlockStateProvider,int,int,int,int,BlockStateProvider,int,int)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
```

</details>


<details><summary>net.minecraft.core.QuartPos</summary>

```diff
+ int quartLocal(int)
```

</details>


<details><summary>net.minecraft.data.worldgen.SurfaceRuleData</summary>

```diff
+ SurfaceRules$RuleSource overworldLike(boolean,boolean,boolean)
+ SurfaceRules$RuleSource[] lambda$overworldLike$0(int)
```

</details>


<details><summary>net.minecraft.data.worldgen.TerrainProvider</summary>

```diff
+ TerrainShaper caves()
+ TerrainShaper floatingIslands()
```

</details>


<details><summary>net.minecraft.data.worldgen.features.CaveFeatures</summary>

```diff
- ConfiguredFeature lambda$static$10()
- ConfiguredFeature lambda$static$11()
- ConfiguredFeature lambda$static$12()
- ConfiguredFeature lambda$static$13()
- ConfiguredFeature lambda$static$3()
- ConfiguredFeature lambda$static$4()
- ConfiguredFeature lambda$static$9()
+ PlacedFeature lambda$static$10()
+ PlacedFeature lambda$static$11()
+ PlacedFeature lambda$static$12()
+ PlacedFeature lambda$static$13()
+ PlacedFeature lambda$static$3()
+ PlacedFeature lambda$static$4()
+ PlacedFeature lambda$static$9()
```

</details>


<details><summary>net.minecraft.data.worldgen.features.VegetationFeatures</summary>

```diff
- ConfiguredFeature lambda$static$12()
- ConfiguredFeature lambda$static$13()
+ PlacedFeature lambda$static$12()
+ PlacedFeature lambda$static$13()
```

</details>


<details><summary>net.minecraft.world.level.chunk.PalettedContainer</summary>

```diff
+ int lambda$read$6(IdMap,Palette,int)
- int lambda$read$6(IdMap,Palette,SimpleBitStorage,int)
+ int lambda$write$7(HashMapPalette,int)
- void lambda$count$7(Int2IntMap,int)
+ void lambda$count$8(Int2IntMap,int)
- void lambda$count$8(PalettedContainer$CountConsumer,Int2IntMap$Entry)
+ void lambda$count$9(PalettedContainer$CountConsumer,Int2IntMap$Entry)
+ void swapPalette(int[],IntUnaryOperator)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.Aquifer</summary>

```diff
+ Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
- Aquifer create(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,NoiseSampler,int,int,Aquifer$FluidPicker)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer</summary>

```diff
+ void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,int,int,Aquifer$FluidPicker)
- void <init>(NoiseChunk,ChunkPos,NormalNoise,NormalNoise,NormalNoise,NormalNoise,PositionalRandomFactory,NoiseSampler,int,int,Aquifer$FluidPicker)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.BelowZeroRetrogen</summary>

```diff
- boolean hasAllBedrockMissing()
+ boolean hasBedrockHole(int,int)
+ boolean hasBedrockHoles()
+ void applyBedrockMask(ProtoChunk)
+ void lambda$applyBedrockMask$6(ProtoChunk,BlockPos)
- void lambda$removeBedrock$6(ProtoChunk,BlockPos)
- void removeBedrock(ProtoChunk)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator</summary>

```diff
- Aquifer$FluidStatus lambda$new$5(Aquifer$FluidStatus,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
+ Aquifer$FluidStatus lambda$new$5(Aquifer$FluidStatus,int,Aquifer$FluidStatus,Aquifer$FluidStatus,int,int,int)
- BlockState debugPreliminarySurfaceLevel(int,int,int,BlockState)
+ BlockState debugPreliminarySurfaceLevel(NoiseChunk,int,int,int,BlockState)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.SurfaceRules</summary>

```diff
- SurfaceRules$RuleSource sequence(SurfaceRules$RuleSource,SurfaceRules$RuleSource[])
+ SurfaceRules$RuleSource sequence(SurfaceRules$RuleSource[])
```

</details>


<details><summary>net.minecraft.world.level.levelgen.SurfaceRules$Context</summary>

```diff
+ int blockCoordToSurfaceCell(int)
+ int surfaceCellToBlockCoord(int)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.SurfaceSystem</summary>

```diff
- int getMinSurfaceLevel(NoiseChunk,int,int)
- void <init>(NoiseSampler,Registry,BlockState,int,long,WorldgenRandom$Algorithm)
+ void <init>(Registry,BlockState,int,long,WorldgenRandom$Algorithm)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate</summary>

```diff
+ BlockPredicate hasSturdyFace(Vec3i,Direction)
+ BlockPredicate matchesBlocks(List)
+ BlockPredicate matchesTag(Tag,Vec3i)
+ BlockPredicate matchesTag(Tag)
```

</details>


# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/tags/blocks/azalea_grows_on.json
+ minecraft/tags/blocks/azalea_root_replaceable.json
+ minecraft/tags/blocks/replaceable_plants.json
+ minecraft/tags/blocks/terracotta.json
+ minecraft/tags/items/dirt.json
+ minecraft/tags/items/terracotta.json
```

</details>


# Registries

<details><summary>block_predicate_type.txt</summary>

```diff
+ minecraft:has_sturdy_face
+ minecraft:matching_block_tag
```

</details>


# Tags

<details><summary>List</summary>

```diff
+ blocks/azalea_grows_on.json
+ blocks/azalea_root_replaceable.json
+ blocks/replaceable_plants.json
+ blocks/terracotta.json
+ items/dirt.json
+ items/terracotta.json
```

</details>


<details><summary>blocks/mineable/axe.json</summary>

```diff
- #minecraft:flowers
```

</details>


# Misc

<details><summary>tags.txt</summary>

```diff
+ blocks/azalea_grows_on.json
+ blocks/azalea_root_replaceable.json
+ blocks/replaceable_plants.json
+ blocks/terracotta.json
+ items/dirt.json
+ items/terracotta.json
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:authlib:3.2.37
+ com.mojang:authlib:3.2.38
```

</details>
