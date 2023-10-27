<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.18.2-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.18.2-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2022-02-23T15:23:12+00:00</td></tr>
<tr><th>SHA1</th><td>c93d7580baf1b292763fa14a379516ffe5822967</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/c93d7580baf1b292763fa14a379516ffe5822967/1.18.2-pre3.json">https://piston-meta.mojang.com/v1/packages/c93d7580baf1b292763fa14a379516ffe5822967/1.18.2-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json">https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/1c898afff0449eed08ad8036aaa4c652952035de/server.jar">https://piston-data.mojang.com/v1/objects/1c898afff0449eed08ad8036aaa4c652952035de/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/f023bea3f6cde2dbfa340649d19e163de93224e8/server.txt">https://piston-data.mojang.com/v1/objects/f023bea3f6cde2dbfa340649d19e163de93224e8/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/8dcc197b6dca3dfa2f6a0d5d3f0ff79de39b4700/client.jar">https://piston-data.mojang.com/v1/objects/8dcc197b6dca3dfa2f6a0d5d3f0ff79de39b4700/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/abfe02738e7fc3d2155dd258ec66c8e25f033c5e/client.txt">https://piston-data.mojang.com/v1/objects/abfe02738e7fc3d2155dd258ec66c8e25f033c5e/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.2-pre2">1.18.2-pre2</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
- net.minecraft.commands.arguments.AngleArgument
+ net.minecraft.commands.arguments.AngleArgument$SingleAngle
- net.minecraft.commands.arguments.ColorArgument
+ net.minecraft.commands.arguments.ComponentArgument
- net.minecraft.commands.arguments.CompoundTagArgument
+ net.minecraft.commands.arguments.DimensionArgument
- net.minecraft.commands.arguments.EntityAnchorArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
- net.minecraft.commands.arguments.EntityArgument
+ net.minecraft.commands.arguments.EntityArgument$Serializer
- net.minecraft.commands.arguments.EntitySummonArgument
+ net.minecraft.commands.arguments.GameProfileArgument
- net.minecraft.commands.arguments.GameProfileArgument$Result
+ net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
- net.minecraft.commands.arguments.ItemEnchantmentArgument
+ net.minecraft.commands.arguments.MessageArgument
- net.minecraft.commands.arguments.MessageArgument$Message
+ net.minecraft.commands.arguments.MessageArgument$Part
- net.minecraft.commands.arguments.MobEffectArgument
+ net.minecraft.commands.arguments.NbtPathArgument
- net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
+ net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
- net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$NbtPath
+ net.minecraft.commands.arguments.NbtPathArgument$Node
- net.minecraft.commands.arguments.NbtTagArgument
+ net.minecraft.commands.arguments.ObjectiveArgument
- net.minecraft.commands.arguments.ObjectiveCriteriaArgument
+ net.minecraft.commands.arguments.OperationArgument
- net.minecraft.commands.arguments.OperationArgument$Operation
+ net.minecraft.commands.arguments.OperationArgument$SimpleOperation
- net.minecraft.commands.arguments.ParticleArgument
+ net.minecraft.commands.arguments.RangeArgument
- net.minecraft.commands.arguments.RangeArgument$Floats
+ net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceKeyArgument$Serializer
- net.minecraft.commands.arguments.ResourceLocationArgument
+ net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientSuggestionProvider</summary>

```diff
- CompletableFuture customSuggestion(CommandContext,SuggestionsBuilder)
+ CompletableFuture customSuggestion(CommandContext)
+ CompletableFuture lambda$suggestRegistryElements$0(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
+ CompletableFuture lambda$suggestRegistryElements$1(CommandContext)
+ CompletableFuture suggestRegistryElements(ResourceKey,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,CommandContext)
```

</details>


<details><summary>net.minecraft.commands.CommandSourceStack</summary>

```diff
- CompletableFuture customSuggestion(CommandContext,SuggestionsBuilder)
+ CompletableFuture customSuggestion(CommandContext)
+ CompletableFuture lambda$suggestRegistryElements$1(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
+ CompletableFuture suggestRegistryElements(ResourceKey,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,CommandContext)
```

</details>


<details><summary>net.minecraft.commands.SharedSuggestionProvider</summary>

```diff
+ void suggestRegistryElements(Registry,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder)
```

</details>


<details><summary>net.minecraft.commands.arguments.ResourceOrTagLocationArgument</summary>

```diff
- void lambda$listSuggestions$3(SuggestionsBuilder,Registry)
```

</details>


<details><summary>net.minecraft.server.commands.PlaceFeatureCommand</summary>

```diff
+ int placeFeature(CommandSourceStack,Holder,BlockPos)
- int placeFeature(CommandSourceStack,ResourceLocationArgument$LocatedResource,BlockPos)
+ String lambda$placeFeature$3(ResourceKey)
```

</details>


<details><summary>net.minecraft.server.network.TextFilterClient</summary>

```diff
+ URL getEndpoint(URI,JsonObject,String,String)
- void <init>(URI,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
+ void <init>(URL,URL,URL,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
```

</details>


<details><summary>net.minecraft.world.item.MapItem</summary>

```diff
- boolean isBiomeWatery(boolean[],int,int,int)
+ boolean isBiomeWatery(boolean[],int,int)
```

</details>


<details><summary>net.minecraft.world.level.chunk.ChunkGenerator</summary>

```diff
- boolean hasFeatureChunkInRange(ResourceKey,int,int,int)
+ boolean hasFeatureChunkInRange(ResourceKey,long,int,int,int)
- long seed()
- void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,ChunkPos,RegistryAccess,StructureManager,long,Holder)
+ void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,long,ChunkPos,RegistryAccess,StructureManager,Holder)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseRouterData</summary>

```diff
- DensityFunction finalDensity(NoiseSettings,boolean,boolean,boolean)
- DensityFunction noiseGradientDensity(DensityFunction,DensityFunction,DensityFunction)
+ DensityFunction noiseGradientDensity(DensityFunction,DensityFunction)
+ DensityFunction postProcess(NoiseSettings,DensityFunction)
- int lambda$noiseRouter$0(OreVeinifier$VeinType)
- int lambda$noiseRouter$1(OreVeinifier$VeinType)
+ int lambda$overworldWithNewCaves$0(OreVeinifier$VeinType)
+ int lambda$overworldWithNewCaves$1(OreVeinifier$VeinType)
- NoiseRouterWithOnlyNoises noiseRouter(NoiseSettings,boolean,boolean)
+ NoiseRouterWithOnlyNoises noNewCaves(NoiseSettings)
+ NoiseRouterWithOnlyNoises overworld(NoiseSettings,boolean)
- NoiseRouterWithOnlyNoises overworld(NoiseSettings)
+ NoiseRouterWithOnlyNoises overworldWithNewCaves(NoiseSettings,boolean)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseSettings</summary>

```diff
- boolean isAmplified()
- boolean islandNoiseOverride()
- boolean largeBiomes()
- NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
+ NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
- NoiseSettings overworldNoiseSettings(boolean,boolean)
+ NoiseSettings overworldNoiseSettings(boolean)
- void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
+ void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature</summary>

```diff
- ConfiguredStructureFeature lambda$static$1()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,int,int)
+ boolean isFeatureChunk(ChunkGenerator,long,int,int)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.commands.arguments.AngleArgument
- net.minecraft.commands.arguments.AngleArgument$SingleAngle
+ net.minecraft.commands.arguments.ColorArgument
- net.minecraft.commands.arguments.ComponentArgument
+ net.minecraft.commands.arguments.CompoundTagArgument
- net.minecraft.commands.arguments.DimensionArgument
+ net.minecraft.commands.arguments.EntityAnchorArgument
- net.minecraft.commands.arguments.EntityAnchorArgument$Anchor
+ net.minecraft.commands.arguments.EntityArgument
- net.minecraft.commands.arguments.EntityArgument$Serializer
+ net.minecraft.commands.arguments.EntitySummonArgument
- net.minecraft.commands.arguments.GameProfileArgument
+ net.minecraft.commands.arguments.GameProfileArgument$Result
- net.minecraft.commands.arguments.GameProfileArgument$SelectorResult
+ net.minecraft.commands.arguments.ItemEnchantmentArgument
- net.minecraft.commands.arguments.MessageArgument
+ net.minecraft.commands.arguments.MessageArgument$Message
- net.minecraft.commands.arguments.MessageArgument$Part
+ net.minecraft.commands.arguments.MobEffectArgument
- net.minecraft.commands.arguments.NbtPathArgument
+ net.minecraft.commands.arguments.NbtPathArgument$AllElementsNode
- net.minecraft.commands.arguments.NbtPathArgument$CompoundChildNode
+ net.minecraft.commands.arguments.NbtPathArgument$IndexedElementNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchElementNode
+ net.minecraft.commands.arguments.NbtPathArgument$MatchObjectNode
- net.minecraft.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ net.minecraft.commands.arguments.NbtPathArgument$NbtPath
- net.minecraft.commands.arguments.NbtPathArgument$Node
+ net.minecraft.commands.arguments.NbtTagArgument
- net.minecraft.commands.arguments.ObjectiveArgument
+ net.minecraft.commands.arguments.ObjectiveCriteriaArgument
- net.minecraft.commands.arguments.OperationArgument
+ net.minecraft.commands.arguments.OperationArgument$Operation
- net.minecraft.commands.arguments.OperationArgument$SimpleOperation
+ net.minecraft.commands.arguments.ParticleArgument
- net.minecraft.commands.arguments.RangeArgument
+ net.minecraft.commands.arguments.RangeArgument$Floats
- net.minecraft.commands.arguments.RangeArgument$Ints
+ net.minecraft.commands.arguments.ResourceKeyArgument
+ net.minecraft.commands.arguments.ResourceLocationArgument
- net.minecraft.commands.arguments.ResourceLocationArgument$LocatedResource
+ net.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- net.minecraft.commands.SharedSuggestionProvider$TextCoordinates
```

</details>


<details><summary>net.minecraft.commands.synchronization.SuggestionProviders</summary>

```diff
- CompletableFuture lambda$static$3(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$4(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$static$5(CommandContext,SuggestionsBuilder)
+ Message lambda$static$3(EntityType)
- Message lambda$static$4(EntityType)
```

</details>


<details><summary>net.minecraft.server.commands.PlaceFeatureCommand</summary>

```diff
+ int placeFeature(CommandSourceStack,Holder,BlockPos)
- int placeFeature(CommandSourceStack,ResourceLocationArgument$LocatedResource,BlockPos)
+ String lambda$placeFeature$3(ResourceKey)
```

</details>


<details><summary>net.minecraft.server.network.TextFilterClient</summary>

```diff
+ URL getEndpoint(URI,JsonObject,String,String)
- void <init>(URI,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
+ void <init>(URL,URL,URL,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
```

</details>


<details><summary>net.minecraft.world.item.MapItem</summary>

```diff
- boolean isBiomeWatery(boolean[],int,int,int)
+ boolean isBiomeWatery(boolean[],int,int)
```

</details>


<details><summary>net.minecraft.world.level.chunk.ChunkGenerator</summary>

```diff
- boolean hasFeatureChunkInRange(ResourceKey,int,int,int)
+ boolean hasFeatureChunkInRange(ResourceKey,long,int,int,int)
- long seed()
- void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,ChunkPos,RegistryAccess,StructureManager,long,Holder)
+ void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,long,ChunkPos,RegistryAccess,StructureManager,Holder)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseRouterData</summary>

```diff
- DensityFunction finalDensity(NoiseSettings,boolean,boolean,boolean)
- DensityFunction noiseGradientDensity(DensityFunction,DensityFunction,DensityFunction)
+ DensityFunction noiseGradientDensity(DensityFunction,DensityFunction)
+ DensityFunction postProcess(NoiseSettings,DensityFunction)
- int lambda$noiseRouter$0(OreVeinifier$VeinType)
- int lambda$noiseRouter$1(OreVeinifier$VeinType)
+ int lambda$overworldWithNewCaves$0(OreVeinifier$VeinType)
+ int lambda$overworldWithNewCaves$1(OreVeinifier$VeinType)
- NoiseRouterWithOnlyNoises noiseRouter(NoiseSettings,boolean,boolean)
+ NoiseRouterWithOnlyNoises noNewCaves(NoiseSettings)
+ NoiseRouterWithOnlyNoises overworld(NoiseSettings,boolean)
- NoiseRouterWithOnlyNoises overworld(NoiseSettings)
+ NoiseRouterWithOnlyNoises overworldWithNewCaves(NoiseSettings,boolean)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.NoiseSettings</summary>

```diff
- boolean isAmplified()
- boolean islandNoiseOverride()
- boolean largeBiomes()
- NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
+ NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
- NoiseSettings overworldNoiseSettings(boolean,boolean)
+ NoiseSettings overworldNoiseSettings(boolean)
- void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
+ void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature</summary>

```diff
- ConfiguredStructureFeature lambda$static$1()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,int,int)
+ boolean isFeatureChunk(ChunkGenerator,long,int,int)
```

</details>


# Commands

<details><summary>attribute.txt</summary>

```diff
- attribute <target: entity> <attribute: resource_location> base get <scale: double>
- attribute <target: entity> <attribute: resource_location> base set <value: double>
- attribute <target: entity> <attribute: resource_location> get <scale: double>
- attribute <target: entity> <attribute: resource_location> modifier add <uuid: uuid> <name: string> <value: double> add
- attribute <target: entity> <attribute: resource_location> modifier add <uuid: uuid> <name: string> <value: double> multiply
- attribute <target: entity> <attribute: resource_location> modifier add <uuid: uuid> <name: string> <value: double> multiply_base
- attribute <target: entity> <attribute: resource_location> modifier remove <uuid: uuid>
- attribute <target: entity> <attribute: resource_location> modifier value get <uuid: uuid> <scale: double>
+ attribute <target: entity> <attribute: resource> base get <scale: double>
+ attribute <target: entity> <attribute: resource> base set <value: double>
+ attribute <target: entity> <attribute: resource> get <scale: double>
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> add
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> multiply
+ attribute <target: entity> <attribute: resource> modifier add <uuid: uuid> <name: string> <value: double> multiply_base
+ attribute <target: entity> <attribute: resource> modifier remove <uuid: uuid>
+ attribute <target: entity> <attribute: resource> modifier value get <uuid: uuid> <scale: double>
```

</details>


<details><summary>placefeature.txt</summary>

```diff
- placefeature <feature: resource_location> <pos: block_pos>
+ placefeature <feature: resource> <pos: block_pos>
```

</details>


# Misc

<details><summary>parsers.txt</summary>

```diff
+ minecraft:resource
```

</details>
