<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.16.2-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.16.2-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2020-08-06T16:44:52+00:00</td></tr>
<tr><th>SHA1</th><td>3df6469e9cc759a1ac0a8f6690289922d547f97b</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/3df6469e9cc759a1ac0a8f6690289922d547f97b/1.16.2-pre3.json">https://piston-meta.mojang.com/v1/packages/3df6469e9cc759a1ac0a8f6690289922d547f97b/1.16.2-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json">https://piston-meta.mojang.com/v1/packages/f3c4aa96e12951cd2781b3e1c0e8ab82bf719cf2/1.16.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/bd47f78f185a525388e446aa44975c147057ebbd/server.jar">https://piston-data.mojang.com/v1/objects/bd47f78f185a525388e446aa44975c147057ebbd/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/22d40c5fbd5c97d7df94369c13bc72f28ff2bd61/server.txt">https://piston-data.mojang.com/v1/objects/22d40c5fbd5c97d7df94369c13bc72f28ff2bd61/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/8cfa861961862c263ff80f2f6478535fd1ed7d8b/client.jar">https://piston-data.mojang.com/v1/objects/8cfa861961862c263ff80f2f6478535fd1ed7d8b/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/45b157e878b41c45187fa0a3acee6d2e7ae8a782/client.txt">https://piston-data.mojang.com/v1/objects/45b157e878b41c45187fa0a3acee6d2e7ae8a782/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.2-pre2">1.16.2-pre2</a>

# Mappings

### Client




<details><summary>com.mojang.realmsclient.RealmsMainScreen$5</summary>

```diff
- boolean lambda$run$0(RealmsMainScreen$Entry)
+ void lambda$run$0(RealmsServer)
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientPacketListener</summary>

```diff
- void lambda$downloadCallback$6()
+ void lambda$downloadCallback$7()
- Void lambda$downloadCallback$7(Throwable)
+ Void lambda$downloadCallback$8(Throwable)
- void lambda$handleAddOrRemoveRecipes$2(ClientRecipeBook,Recipe)
+ void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,Recipe)
- void lambda$handleAddOrRemoveRecipes$3(ClientRecipeBook,RecipeCollection)
+ void lambda$handleAddOrRemoveRecipes$4(ClientRecipeBook,RecipeCollection)
+ void lambda$handleChunkBlocksUpdate$0(int,BlockPos,BlockState)
- void lambda$handleGameEvent$1()
+ void lambda$handleGameEvent$2()
- void lambda$handlePlaceRecipe$8(AbstractContainerMenu,Recipe)
+ void lambda$handlePlaceRecipe$9(AbstractContainerMenu,Recipe)
- void lambda$handleResourcePack$5(String,String)
+ void lambda$handleResourcePack$6(String,String)
- void lambda$handleSetEquipment$0(Entity,Pair)
+ void lambda$handleSetEquipment$1(Entity,Pair)
- void lambda$null$4(String,String,boolean)
+ void lambda$null$5(String,String,boolean)
```

</details>


<details><summary>net.minecraft.server.MinecraftServer</summary>

```diff
+ boolean lambda$getSelectedPacks$11(Collection,String)
- boolean lambda$getSelectedPacks$13(Collection,String)
+ boolean lambda$setInitialSpawn$2(Biome)
- boolean lambda$setInitialSpawn$4(Biome)
+ boolean lambda$waitUntilNextTick$3()
- boolean lambda$waitUntilNextTick$5()
- CompletionStage lambda$reloadResources$11(ImmutableList)
+ CompletionStage lambda$reloadResources$9(ImmutableList)
- IllegalStateException lambda$createLevels$2(DimensionType)
- IllegalStateException lambda$createLevels$3(DimensionType)
- ImmutableList lambda$reloadResources$10(Collection)
+ ImmutableList lambda$reloadResources$8(Collection)
+ String lambda$fillReport$5()
+ String lambda$fillReport$6()
- String lambda$fillReport$8()
- String lambda$fillReport$9()
+ String lambda$tickChildren$4(ServerLevel)
- String lambda$tickChildren$6(ServerLevel)
+ void lambda$reloadResources$10(Collection,ServerResources)
- void lambda$reloadResources$12(Collection,ServerResources)
```

</details>


<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ Vec3 getLightProbePosition(float)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Wolf</summary>

```diff
+ void cancelShake()
```

</details>


<details><summary>net.minecraft.world.entity.decoration.ArmorStand</summary>

```diff
+ EntityDimensions getDimensionsMarker(boolean)
+ Vec3 getLightProbePosition(float)
```

</details>


<details><summary>net.minecraft.world.level.Level</summary>

```diff
- ResourceKey dimensionTypeKey()
+ void <init>(WritableLevelData,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
- void <init>(WritableLevelData,ResourceKey,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.DebugLevelSource</summary>

```diff
- DebugLevelSource lambda$static$0()
+ Registry biomes()
+ Stream lambda$static$0(Block)
- Stream lambda$static$1(Block)
- void <init>()
+ void <init>(Registry)
```

</details>


### Server




<details><summary>net.minecraft.server.MinecraftServer</summary>

```diff
+ boolean lambda$getSelectedPacks$11(Collection,String)
- boolean lambda$getSelectedPacks$13(Collection,String)
+ boolean lambda$setInitialSpawn$2(Biome)
- boolean lambda$setInitialSpawn$4(Biome)
+ boolean lambda$waitUntilNextTick$3()
- boolean lambda$waitUntilNextTick$5()
- CompletionStage lambda$reloadResources$11(ImmutableList)
+ CompletionStage lambda$reloadResources$9(ImmutableList)
- IllegalStateException lambda$createLevels$2(DimensionType)
- IllegalStateException lambda$createLevels$3(DimensionType)
- ImmutableList lambda$reloadResources$10(Collection)
+ ImmutableList lambda$reloadResources$8(Collection)
+ String lambda$fillReport$5()
+ String lambda$fillReport$6()
- String lambda$fillReport$8()
- String lambda$fillReport$9()
+ String lambda$tickChildren$4(ServerLevel)
- String lambda$tickChildren$6(ServerLevel)
+ void lambda$reloadResources$10(Collection,ServerResources)
- void lambda$reloadResources$12(Collection,ServerResources)
```

</details>


<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ Vec3 getLightProbePosition(float)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Wolf</summary>

```diff
+ void cancelShake()
```

</details>


<details><summary>net.minecraft.world.entity.decoration.ArmorStand</summary>

```diff
+ EntityDimensions getDimensionsMarker(boolean)
+ Vec3 getLightProbePosition(float)
```

</details>


<details><summary>net.minecraft.world.level.Level</summary>

```diff
- ResourceKey dimensionTypeKey()
+ void <init>(WritableLevelData,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
- void <init>(WritableLevelData,ResourceKey,ResourceKey,DimensionType,Supplier,boolean,boolean,long)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.DebugLevelSource</summary>

```diff
- DebugLevelSource lambda$static$0()
+ Registry biomes()
+ Stream lambda$static$0(Block)
- Stream lambda$static$1(Block)
- void <init>()
+ void <init>(Registry)
```

</details>
