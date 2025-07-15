## Comparison with [1.18.2-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.2-pre2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Commands](#commands)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18.2-pre2</th><th>1.18.2-pre3</th></tr><tr><td>World version</td><td><pre>2972</pre></td><td><pre>2973</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741895</pre></td><td><pre>1073741896</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18.2-pre2</th><th>1.18.2-pre3</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
attribute
</summary>

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
<details>
<summary>
placefeature
</summary>

```diff
- placefeature <feature: resource_location> <pos: block_pos>
+ placefeature <feature: resource> <pos: block_pos>
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:resource
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
- XXX.commands.arguments.AngleArgument
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceKeyArgument
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ResourceLocationArgument$LocatedResource
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.commands.synchronization.SuggestionProviders +2M -3M | -1P
```
```
XXX.server.commands.PlaceFeatureCommand +2M -1M
```
```
XXX.server.network.TextFilterClient +2M -1M
```
```
XXX.world.item.MapItem +1M -1M
```
```
XXX.level.chunk.ChunkGenerator +2M -3M | +1P -1P
```
```
XXX.level.levelgen.NoiseRouterData +7M -6M
```
```
XXX.level.levelgen.NoiseSettings +3M -6M | -3P
```
```
XXX.levelgen.feature.ConfiguredStructureFeature -1M | -1P
```
```
XXX.structure.placement.ConcentricRingsStructurePlacement +1M -1M
```
```
XXX.structure.placement.StructurePlacement +1P -1P
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders
</summary>

```diff
+ CompletableFuture lambda$static$3(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$static$4(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$5(CommandContext,SuggestionsBuilder)
- Message lambda$static$3(EntityType)
+ Message lambda$static$4(EntityType)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PlaceFeatureCommand
</summary>

```diff
- int placeFeature(CommandSourceStack,Holder,BlockPos)
+ int placeFeature(CommandSourceStack,ResourceLocationArgument$LocatedResource,BlockPos)
- String lambda$placeFeature$3(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.server.network.TextFilterClient
</summary>

```diff
- URL getEndpoint(URI,JsonObject,String,String)
+ void <init>(URI,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
- void <init>(URL,URL,URL,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ boolean isBiomeWatery(boolean[],int,int,int)
- boolean isBiomeWatery(boolean[],int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ boolean hasFeatureChunkInRange(ResourceKey,int,int,int)
- boolean hasFeatureChunkInRange(ResourceKey,long,int,int,int)
+ long seed()
+ void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,ChunkPos,RegistryAccess,StructureManager,long,Holder)
- void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,long,ChunkPos,RegistryAccess,StructureManager,Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
+ DensityFunction finalDensity(NoiseSettings,boolean,boolean,boolean)
+ DensityFunction noiseGradientDensity(DensityFunction,DensityFunction,DensityFunction)
- DensityFunction noiseGradientDensity(DensityFunction,DensityFunction)
- DensityFunction postProcess(NoiseSettings,DensityFunction)
+ int lambda$noiseRouter$0(OreVeinifier$VeinType)
+ int lambda$noiseRouter$1(OreVeinifier$VeinType)
- int lambda$overworldWithNewCaves$0(OreVeinifier$VeinType)
- int lambda$overworldWithNewCaves$1(OreVeinifier$VeinType)
+ NoiseRouterWithOnlyNoises noiseRouter(NoiseSettings,boolean,boolean)
- NoiseRouterWithOnlyNoises noNewCaves(NoiseSettings)
- NoiseRouterWithOnlyNoises overworld(NoiseSettings,boolean)
+ NoiseRouterWithOnlyNoises overworld(NoiseSettings)
- NoiseRouterWithOnlyNoises overworldWithNewCaves(NoiseSettings,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSettings
</summary>

```diff
+ boolean isAmplified()
+ boolean islandNoiseOverride()
+ boolean largeBiomes()
+ NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
- NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
+ NoiseSettings overworldNoiseSettings(boolean,boolean)
- NoiseSettings overworldNoiseSettings(boolean)
+ void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
- void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
</summary>

```diff
+ ConfiguredStructureFeature lambda$static$1()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
</summary>

```diff
+ boolean isFeatureChunk(ChunkGenerator,int,int)
- boolean isFeatureChunk(ChunkGenerator,long,int,int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ XXX.commands.arguments.AngleArgument
- XXX.commands.arguments.AngleArgument$SingleAngle
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionArgument
+ XXX.commands.arguments.EntityAnchorArgument
- XXX.commands.arguments.EntityAnchorArgument$Anchor
+ XXX.commands.arguments.EntityArgument
- XXX.commands.arguments.EntityArgument$Serializer
+ XXX.commands.arguments.EntitySummonArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.ItemEnchantmentArgument
- XXX.commands.arguments.MessageArgument
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.MobEffectArgument
- XXX.commands.arguments.NbtPathArgument
+ XXX.commands.arguments.NbtPathArgument$AllElementsNode
- XXX.commands.arguments.NbtPathArgument$CompoundChildNode
+ XXX.commands.arguments.NbtPathArgument$IndexedElementNode
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceKeyArgument$Serializer
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen +1P -1P
```
```
XXX.components.events.GuiEventListener +1P
```
```
XXX.screens.inventory.BookEditScreen -1P
```
```
XXX.client.multiplayer.ClientSuggestionProvider +4M -1M
```
```
XXX.minecraft.commands.CommandSourceStack +3M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1M | +2P -1P
```
```
XXX.commands.arguments.ResourceOrTagLocationArgument -1M
```
```
XXX.server.commands.PlaceFeatureCommand +2M -1M
```
```
XXX.server.network.TextFilterClient +2M -1M
```
```
XXX.world.item.MapItem +1M -1M
```
```
XXX.level.chunk.ChunkGenerator +2M -3M | +1P -1P
```
```
XXX.level.levelgen.NoiseRouterData +7M -6M
```
```
XXX.level.levelgen.NoiseSettings +3M -6M | -3P
```
```
XXX.levelgen.feature.ConfiguredStructureFeature -1M | -1P
```
```
XXX.structure.placement.ConcentricRingsStructurePlacement +1M -1M
```
```
XXX.structure.placement.StructurePlacement +1P -1P
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientSuggestionProvider
</summary>

```diff
+ CompletableFuture customSuggestion(CommandContext,SuggestionsBuilder)
- CompletableFuture customSuggestion(CommandContext)
- CompletableFuture lambda$suggestRegistryElements$0(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
- CompletableFuture lambda$suggestRegistryElements$1(CommandContext)
- CompletableFuture suggestRegistryElements(ResourceKey,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ CompletableFuture customSuggestion(CommandContext,SuggestionsBuilder)
- CompletableFuture customSuggestion(CommandContext)
- CompletableFuture lambda$suggestRegistryElements$1(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
- CompletableFuture suggestRegistryElements(ResourceKey,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.commands.SharedSuggestionProvider
</summary>

```diff
- void suggestRegistryElements(Registry,SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ResourceOrTagLocationArgument
</summary>

```diff
+ void lambda$listSuggestions$3(SuggestionsBuilder,Registry)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PlaceFeatureCommand
</summary>

```diff
- int placeFeature(CommandSourceStack,Holder,BlockPos)
+ int placeFeature(CommandSourceStack,ResourceLocationArgument$LocatedResource,BlockPos)
- String lambda$placeFeature$3(ResourceKey)
```

</details>
<details>
<summary>
net.minecraft.server.network.TextFilterClient
</summary>

```diff
- URL getEndpoint(URI,JsonObject,String,String)
+ void <init>(URI,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
- void <init>(URL,URL,URL,String,int,String,String,TextFilterClient$IgnoreStrategy,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ boolean isBiomeWatery(boolean[],int,int,int)
- boolean isBiomeWatery(boolean[],int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ boolean hasFeatureChunkInRange(ResourceKey,int,int,int)
- boolean hasFeatureChunkInRange(ResourceKey,long,int,int,int)
+ long seed()
+ void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,ChunkPos,RegistryAccess,StructureManager,long,Holder)
- void lambda$createStructures$20(StructureFeatureManager,SectionPos,ChunkAccess,long,ChunkPos,RegistryAccess,StructureManager,Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
+ DensityFunction finalDensity(NoiseSettings,boolean,boolean,boolean)
+ DensityFunction noiseGradientDensity(DensityFunction,DensityFunction,DensityFunction)
- DensityFunction noiseGradientDensity(DensityFunction,DensityFunction)
- DensityFunction postProcess(NoiseSettings,DensityFunction)
+ int lambda$noiseRouter$0(OreVeinifier$VeinType)
+ int lambda$noiseRouter$1(OreVeinifier$VeinType)
- int lambda$overworldWithNewCaves$0(OreVeinifier$VeinType)
- int lambda$overworldWithNewCaves$1(OreVeinifier$VeinType)
+ NoiseRouterWithOnlyNoises noiseRouter(NoiseSettings,boolean,boolean)
- NoiseRouterWithOnlyNoises noNewCaves(NoiseSettings)
- NoiseRouterWithOnlyNoises overworld(NoiseSettings,boolean)
+ NoiseRouterWithOnlyNoises overworld(NoiseSettings)
- NoiseRouterWithOnlyNoises overworldWithNewCaves(NoiseSettings,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseSettings
</summary>

```diff
+ boolean isAmplified()
+ boolean islandNoiseOverride()
+ boolean largeBiomes()
+ NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
- NoiseSettings create(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
+ NoiseSettings overworldNoiseSettings(boolean,boolean)
- NoiseSettings overworldNoiseSettings(boolean)
+ void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,boolean,boolean,boolean,TerrainShaper)
- void <init>(int,int,NoiseSamplingSettings,NoiseSlider,NoiseSlider,int,int,TerrainShaper)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
</summary>

```diff
+ ConfiguredStructureFeature lambda$static$1()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
</summary>

```diff
+ boolean isFeatureChunk(ChunkGenerator,int,int)
- boolean isFeatureChunk(ChunkGenerator,long,int,int)
```

</details>
</details>
<hr/>