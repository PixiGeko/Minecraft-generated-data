## Comparison with [1.16.2-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.2-pre2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16.2-pre2</th><th>1.16.2-pre3</th></tr><tr><td>World version</td><td><pre>2574</pre></td><td><pre>2575</pre></td></tr><tr><td>Protocol version</td><td><pre>746</pre></td><td><pre>748</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16.2-pre2</th><th>1.16.2-pre3</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.server.MinecraftServer +9M -11M
```
```
XXX.world.entity.Entity +1M
```
```
XXX.entity.animal.Wolf +1M
```
```
XXX.entity.decoration.ArmorStand +2M | +2P
```
```
XXX.world.level.Level +1M -2M | -1P
```
```
XXX.level.levelgen.DebugLevelSource +3M -3M | +1P -1P
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- boolean lambda$getSelectedPacks$11(Collection,String)
+ boolean lambda$getSelectedPacks$13(Collection,String)
- boolean lambda$setInitialSpawn$2(Biome)
+ boolean lambda$setInitialSpawn$4(Biome)
- boolean lambda$waitUntilNextTick$3()
+ boolean lambda$waitUntilNextTick$5()
+ CompletionStage lambda$reloadResources$11(ImmutableList)
- CompletionStage lambda$reloadResources$9(ImmutableList)
+ IllegalStateException lambda$createLevels$2(DimensionType)
+ IllegalStateException lambda$createLevels$3(DimensionType)
+ ImmutableList lambda$reloadResources$10(Collection)
- ImmutableList lambda$reloadResources$8(Collection)
- String lambda$fillReport$5()
- String lambda$fillReport$6()
+ String lambda$fillReport$8()
+ String lambda$fillReport$9()
- String lambda$tickChildren$4(ServerLevel)
+ String lambda$tickChildren$6(ServerLevel)
- void lambda$reloadResources$10(Collection,ServerResources)
+ void lambda$reloadResources$12(Collection,ServerResources)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- Vec3 getLightProbePosition(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Wolf
</summary>

```diff
- void cancelShake()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- EntityDimensions getDimensionsMarker(boolean)
- Vec3 getLightProbePosition(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ ResourceKey dimensionTypeKey()
- void <init>(WritableLevelData,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
+ void <init>(WritableLevelData,ResourceKey,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ DebugLevelSource lambda$static$0()
- Registry biomes()
- Stream lambda$static$0(Block)
+ Stream lambda$static$1(Block)
+ void <init>()
- void <init>(Registry)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.realmsclient.RealmsMainScreen$5 +1M -1M
```
```
XXX.client.multiplayer.ClientPacketListener +10M -9M
```
```
XXX.minecraft.server.MinecraftServer +9M -11M
```
```
XXX.world.entity.Entity +1M
```
```
XXX.entity.animal.Wolf +1M
```
```
XXX.entity.decoration.ArmorStand +2M | +2P
```
```
XXX.world.level.Level +1M -2M | -1P
```
```
XXX.level.levelgen.DebugLevelSource +3M -3M | +1P -1P
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$5
</summary>

```diff
+ boolean lambda$run$0(RealmsMainScreen$Entry)
- void lambda$run$0(RealmsServer)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ void lambda$downloadCallback$6()
- void lambda$downloadCallback$7()
+ Void lambda$downloadCallback$7(Throwable)
- Void lambda$downloadCallback$8(Throwable)
+ void lambda$handleAddOrRemoveRecipes$2(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,RecipeCollection)
- void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
- void lambda$handleChunkBlocksUpdate$0(int,BlockPos,BlockState)
+ void lambda$handleGameEvent$1()
- void lambda$handleGameEvent$2()
+ void lambda$handlePlaceRecipe$8(AbstractContainerMenu,Recipe)
- void lambda$handlePlaceRecipe$9(AbstractContainerMenu,Recipe)
+ void lambda$handleResourcePack$5(String,String)
- void lambda$handleResourcePack$6(String,String)
+ void lambda$handleSetEquipment$0(Entity,Pair)
- void lambda$handleSetEquipment$1(Entity,Pair)
+ void lambda$null$4(String,String,boolean)
- void lambda$null$5(String,String,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- boolean lambda$getSelectedPacks$11(Collection,String)
+ boolean lambda$getSelectedPacks$13(Collection,String)
- boolean lambda$setInitialSpawn$2(Biome)
+ boolean lambda$setInitialSpawn$4(Biome)
- boolean lambda$waitUntilNextTick$3()
+ boolean lambda$waitUntilNextTick$5()
+ CompletionStage lambda$reloadResources$11(ImmutableList)
- CompletionStage lambda$reloadResources$9(ImmutableList)
+ IllegalStateException lambda$createLevels$2(DimensionType)
+ IllegalStateException lambda$createLevels$3(DimensionType)
+ ImmutableList lambda$reloadResources$10(Collection)
- ImmutableList lambda$reloadResources$8(Collection)
- String lambda$fillReport$5()
- String lambda$fillReport$6()
+ String lambda$fillReport$8()
+ String lambda$fillReport$9()
- String lambda$tickChildren$4(ServerLevel)
+ String lambda$tickChildren$6(ServerLevel)
- void lambda$reloadResources$10(Collection,ServerResources)
+ void lambda$reloadResources$12(Collection,ServerResources)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- Vec3 getLightProbePosition(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Wolf
</summary>

```diff
- void cancelShake()
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- EntityDimensions getDimensionsMarker(boolean)
- Vec3 getLightProbePosition(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ ResourceKey dimensionTypeKey()
- void <init>(WritableLevelData,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
+ void <init>(WritableLevelData,ResourceKey,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
+ DebugLevelSource lambda$static$0()
- Registry biomes()
- Stream lambda$static$0(Block)
+ Stream lambda$static$1(Block)
+ void <init>()
- void <init>(Registry)
```

</details>
</details>
<hr/>