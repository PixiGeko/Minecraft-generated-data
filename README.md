<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.15-pre4 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.15-pre4</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2019-12-03T12:24:24+00:00</td></tr>
<tr><th>SHA1</th><td>b4ca2162a7a098e4e4f7dce619666d0aa6f3e2fc</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/b4ca2162a7a098e4e4f7dce619666d0aa6f3e2fc/1.15-pre4.json">https://piston-meta.mojang.com/v1/packages/b4ca2162a7a098e4e4f7dce619666d0aa6f3e2fc/1.15-pre4.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json">https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/8f9e23414a01d21e2cd313b2595b164ccfda56aa/server.jar">https://piston-data.mojang.com/v1/objects/8f9e23414a01d21e2cd313b2595b164ccfda56aa/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/35c640792a7f5618142e687cd8be41546c280acd/server.txt">https://piston-data.mojang.com/v1/objects/35c640792a7f5618142e687cd8be41546c280acd/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/6868a5c87243707f7936c21a4e52d076e3d73234/client.jar">https://piston-data.mojang.com/v1/objects/6868a5c87243707f7936c21a4e52d076e3d73234/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/07a4257ccae96f0740a586f3652dfc5ffc0d5743/client.txt">https://piston-data.mojang.com/v1/objects/07a4257ccae96f0740a586f3652dfc5ffc0d5743/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.15-pre3">1.15-pre3</a>

# Mappings

### Client




<details><summary>com.mojang.blaze3d.platform.Lighting</summary>

```diff
- void <clinit>()
- void setupGui(Matrix4f)
```

</details>


<details><summary>net.minecraft.client.model.ArmorStandModel</summary>

```diff
+ void prepareMobModel(ArmorStand,float,float,float)
+ void prepareMobModel(Entity,float,float,float)
+ void prepareMobModel(LivingEntity,float,float,float)
```

</details>


<details><summary>net.minecraft.client.renderer.LevelRenderer</summary>

```diff
+ double lambda$setupRender$0(BlockPos,LevelRenderer$RenderChunkInfo)
- SortedSet lambda$destroyBlockProgress$4(long)
+ SortedSet lambda$destroyBlockProgress$5(long)
- String lambda$addParticle$3(double,double,double)
+ String lambda$addParticle$4(double,double,double)
- String lambda$renderChunkLayer$1(RenderType)
+ String lambda$renderChunkLayer$2(RenderType)
- VertexConsumer lambda$renderLevel$0(MultiBufferSource$BufferSource,VertexConsumer,RenderType)
+ VertexConsumer lambda$renderLevel$1(MultiBufferSource$BufferSource,VertexConsumer,RenderType)
- void lambda$renderShape$2(VertexConsumer,Matrix4f,double,double,double,float,float,float,float,double,double,double,double,double,double)
+ void lambda$renderShape$3(VertexConsumer,Matrix4f,double,double,double,float,float,float,float,double,double,double,double,double,double)
```

</details>


<details><summary>net.minecraft.client.renderer.ScreenEffectRenderer</summary>

```diff
+ BlockState getViewBlockingState(Player)
```

</details>


<details><summary>net.minecraft.gametest.framework.GameTestHelper</summary>

```diff
+ void assertItemEntityPresent(Item,BlockPos,double)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal</summary>

```diff
+ void setTarget(LivingEntity)
```

</details>


<details><summary>net.minecraft.world.level.biome.Biome</summary>

```diff
+ int calculateSkyColor()
```

</details>


<details><summary>net.minecraft.world.level.block.AbstractGlassBlock</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.FarmBlock</summary>

```diff
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.LeavesBlock</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.SoulsandBlock</summary>

```diff
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.piston.MovingPistonBlock</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


### Server




<details><summary>net.minecraft.gametest.framework.GameTestHelper</summary>

```diff
+ void assertItemEntityPresent(Item,BlockPos,double)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Panda</summary>

```diff
- boolean access$1400(Panda)
- boolean access$1500(Panda)
+ boolean access$1600(Panda)
+ boolean access$1700(Panda)
+ Panda$PandaLookAtPlayerGoal access$600(Panda)
- Predicate access$500()
+ Predicate access$700()
- Random access$1000(Panda)
+ Random access$1400(Panda)
+ Random access$1500(Panda)
- Random access$600(Panda)
- Random access$700(Panda)
+ Random access$800(Panda)
+ TargetingConditions access$500()
+ void access$1000(Panda)
- void access$800(Panda)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Panda$PandaBreedGoal</summary>

```diff
- void <clinit>()
- void <init>(Panda,double)
+ void <init>(Panda,Panda,double)
```

</details>


<details><summary>net.minecraft.world.level.Explosion</summary>

```diff
+ void addBlockDrops(ObjectArrayList,ItemStack,BlockPos)
- void addBlockDrops(ObjectArrayList,ItemStack)
+ void lambda$finalizeExplosion$0(ObjectArrayList,BlockPos,ItemStack)
- void lambda$finalizeExplosion$0(ObjectArrayList,ItemStack)
```

</details>


<details><summary>net.minecraft.world.level.block.Block</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.GrassPathBlock</summary>

```diff
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.ShulkerBoxBlock</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.piston.PistonBaseBlock</summary>

```diff
+ boolean isSuffocating(BlockState,BlockGetter,BlockPos)
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.block.state.BlockState</summary>

```diff
+ boolean isSuffocating(BlockGetter,BlockPos)
```

</details>


<details><summary>net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint</summary>

```diff
- void lambda$removeIf$0(LongPredicate,long)
+ void lambda$removeIf$0(LongPredicate,LongList,long)
```

</details>


# Folder structure

<details><summary>assets/</summary>

```diff
+ minecraft/textures/map/map_background_checkerboard.png
```

</details>


# Misc

<details><summary>textures.txt</summary>

```diff
+ map/map_background_checkerboard.png
```

</details>
