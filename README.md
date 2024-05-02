<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.17-pre5 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.17-pre5</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2021-06-03T17:01:28+00:00</td></tr>
<tr><th>SHA1</th><td>29bd60294ee8387f7ca7d9c1abd835484f71bbfc</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/29bd60294ee8387f7ca7d9c1abd835484f71bbfc/1.17-pre5.json">https://piston-meta.mojang.com/v1/packages/29bd60294ee8387f7ca7d9c1abd835484f71bbfc/1.17-pre5.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/31bb40019e8d6e64299abafd743f4d3e1a1a68b2/server.jar">https://piston-data.mojang.com/v1/objects/31bb40019e8d6e64299abafd743f4d3e1a1a68b2/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/4fd01412588c91fbc94fb36eb9b57275de0f6be9/server.txt">https://piston-data.mojang.com/v1/objects/4fd01412588c91fbc94fb36eb9b57275de0f6be9/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/ad51f4efbc250c15d84eaf07f600787246fa6cd6/client.jar">https://piston-data.mojang.com/v1/objects/ad51f4efbc250c15d84eaf07f600787246fa6cd6/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/d1ddc678fa5d248aa855cf4723089ef6f7624b67/client.txt">https://piston-data.mojang.com/v1/objects/d1ddc678fa5d248aa855cf4723089ef6f7624b67/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre4">1.17-pre4</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
+ net.minecraft.util.datafix.schemas.V1451_6$2
```

</details>


<details><summary>com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen</summary>

```diff
- void lambda$generationSelectionCallback$8(WorldGenerationInfo)
+ void lambda$generationSelectionCallback$9(WorldGenerationInfo)
+ void lambda$switchSlot$7(Runnable)
- void lambda$templateSelectionCallback$7(WorldTemplate)
+ void lambda$templateSelectionCallback$8(WorldTemplate)
```

</details>


<details><summary>net.minecraft.server.dedicated.DedicatedServerSettings</summary>

```diff
+ void <init>(Path)
- void <init>(RegistryAccess,Path)
```

</details>


<details><summary>net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix</summary>

```diff
- Function lambda$makeRule$2(DynamicOps)
- Pair lambda$makeRule$1(Pair)
+ Typed lambda$makeRule$1(Typed)
```

</details>


<details><summary>net.minecraft.util.datafix.schemas.V1451_6</summary>

```diff
+ Map createCriterionTypes(Schema)
+ TypeTemplate lambda$createCriterionTypes$3(Schema)
+ TypeTemplate lambda$createCriterionTypes$4(Schema)
+ TypeTemplate lambda$createCriterionTypes$5(Schema)
+ TypeTemplate lambda$createCriterionTypes$6()
+ TypeTemplate lambda$createCriterionTypes$7()
+ TypeTemplate lambda$registerTypes$2(Map)
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.util.datafix.schemas.V1460</summary>

```diff
+ TypeTemplate lambda$registerTypes$42(Map)
- TypeTemplate lambda$registerTypes$42(Schema)
- TypeTemplate lambda$registerTypes$44()
+ TypeTemplate lambda$registerTypes$44(Schema)
+ TypeTemplate lambda$registerTypes$46()
- TypeTemplate lambda$registerTypes$46(Schema)
+ TypeTemplate lambda$registerTypes$47(Schema)
```

</details>


<details><summary>net.minecraft.world.level.block.PointedDripstoneBlock</summary>

```diff
+ boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.state.BlockBehaviour</summary>

```diff
+ boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
+ net.minecraft.util.datafix.schemas.V1451_6$2
```

</details>


<details><summary>net.minecraft.server.dedicated.DedicatedServerSettings</summary>

```diff
+ void <init>(Path)
- void <init>(RegistryAccess,Path)
```

</details>


<details><summary>net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix</summary>

```diff
- Function lambda$makeRule$2(DynamicOps)
- Pair lambda$makeRule$1(Pair)
+ Typed lambda$makeRule$1(Typed)
```

</details>


<details><summary>net.minecraft.util.datafix.schemas.V1451_6</summary>

```diff
+ Map createCriterionTypes(Schema)
+ TypeTemplate lambda$createCriterionTypes$3(Schema)
+ TypeTemplate lambda$createCriterionTypes$4(Schema)
+ TypeTemplate lambda$createCriterionTypes$5(Schema)
+ TypeTemplate lambda$createCriterionTypes$6()
+ TypeTemplate lambda$createCriterionTypes$7()
+ TypeTemplate lambda$registerTypes$2(Map)
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.util.datafix.schemas.V1460</summary>

```diff
+ TypeTemplate lambda$registerTypes$42(Map)
- TypeTemplate lambda$registerTypes$42(Schema)
- TypeTemplate lambda$registerTypes$44()
+ TypeTemplate lambda$registerTypes$44(Schema)
+ TypeTemplate lambda$registerTypes$46()
- TypeTemplate lambda$registerTypes$46(Schema)
+ TypeTemplate lambda$registerTypes$47(Schema)
```

</details>


<details><summary>net.minecraft.world.level.block.PointedDripstoneBlock</summary>

```diff
+ boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.state.BlockBehaviour</summary>

```diff
+ boolean isCollisionShapeFullBlock(BlockState,BlockGetter,BlockPos)
```

</details>
