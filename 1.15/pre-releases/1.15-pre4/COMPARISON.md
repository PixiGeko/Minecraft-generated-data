## Comparison with [1.15-pre3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.15-pre3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.15-pre3</th><th>1.15-pre4</th></tr><tr><td>World version</td><td><pre>2220</pre></td><td><pre>2221</pre></td></tr><tr><td>Protocol version</td><td><pre>567</pre></td><td><pre>569</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.15-pre3</th><th>1.15-pre4</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/map/map_background_checkerboard.png
```

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
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.entity.animal.Panda +9M -7M | +2P
```
```
XXX.entity.animal.Panda$PandaBreedGoal +1M -2M | +1P -1P
```
```
XXX.world.level.Explosion +2M -2M
```
```
XXX.level.block.Block +1M
```
```
XXX.level.block.GrassPathBlock +1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.block.piston.PistonBaseBlock +1M -1M
```
```
XXX.block.state.BlockState +1M
```
```
XXX.level.lighting.DynamicGraphMinFixedPoint +1M -1M
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertItemEntityPresent(Item,BlockPos,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Panda
</summary>

```diff
+ boolean access$1400(Panda)
+ boolean access$1500(Panda)
- boolean access$1600(Panda)
- boolean access$1700(Panda)
- Panda$PandaLookAtPlayerGoal access$600(Panda)
+ Predicate access$500()
- Predicate access$700()
+ Random access$1000(Panda)
- Random access$1400(Panda)
- Random access$1500(Panda)
+ Random access$600(Panda)
+ Random access$700(Panda)
- Random access$800(Panda)
- TargetingConditions access$500()
- void access$1000(Panda)
+ void access$800(Panda)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Panda$PandaBreedGoal
</summary>

```diff
+ void <clinit>()
+ void <init>(Panda,double)
- void <init>(Panda,Panda,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.Explosion
</summary>

```diff
- void addBlockDrops(ObjectArrayList,ItemStack,BlockPos)
+ void addBlockDrops(ObjectArrayList,ItemStack)
- void lambda$finalizeExplosion$0(ObjectArrayList,BlockPos,ItemStack)
+ void lambda$finalizeExplosion$0(ObjectArrayList,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrassPathBlock
</summary>

```diff
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockState
</summary>

```diff
- boolean isSuffocating(BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
</summary>

```diff
+ void lambda$removeIf$0(LongPredicate,long)
- void lambda$removeIf$0(LongPredicate,LongList,long)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.Lighting -2M | -2P
```
```
XXX.client.model.ArmorStandModel +3M
```
```
XXX.client.renderer.LevelRenderer +6M -5M | +1P -1P
```
```
XXX.client.renderer.ScreenEffectRenderer +1M
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.entity.animal.Panda$PandaLookAtPlayerGoal +1M
```
```
XXX.level.biome.Biome +1M | +1P
```
```
XXX.level.block.AbstractGlassBlock +1M -1M
```
```
XXX.level.block.FarmBlock +1M
```
```
XXX.level.block.LeavesBlock +1M -1M
```
```
XXX.level.block.SoulsandBlock +1M
```
```
XXX.block.piston.MovingPistonBlock +1M -1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.Lighting
</summary>

```diff
+ void <clinit>()
+ void setupGui(Matrix4f)
```

</details>
<details>
<summary>
net.minecraft.client.model.ArmorStandModel
</summary>

```diff
- void prepareMobModel(ArmorStand,float,float,float)
- void prepareMobModel(Entity,float,float,float)
- void prepareMobModel(LivingEntity,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LevelRenderer
</summary>

```diff
- double lambda$setupRender$0(BlockPos,LevelRenderer$RenderChunkInfo)
+ SortedSet lambda$destroyBlockProgress$4(long)
- SortedSet lambda$destroyBlockProgress$5(long)
+ String lambda$addParticle$3(double,double,double)
- String lambda$addParticle$4(double,double,double)
+ String lambda$renderChunkLayer$1(RenderType)
- String lambda$renderChunkLayer$2(RenderType)
+ VertexConsumer lambda$renderLevel$0(MultiBufferSource$BufferSource,VertexConsumer,RenderType)
- VertexConsumer lambda$renderLevel$1(MultiBufferSource$BufferSource,VertexConsumer,RenderType)
+ void lambda$renderShape$2(VertexConsumer,Matrix4f,double,double,double,float,float,float,float,double,double,double,double,double,double)
- void lambda$renderShape$3(VertexConsumer,Matrix4f,double,double,double,float,float,float,float,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ScreenEffectRenderer
</summary>

```diff
- BlockState getViewBlockingState(Player)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertItemEntityPresent(Item,BlockPos,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
</summary>

```diff
- void setTarget(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- int calculateSkyColor()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractGlassBlock
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FarmBlock
</summary>

```diff
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeavesBlock
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SoulsandBlock
</summary>

```diff
- boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
- boolean isSuffocating(BlockState,BlockGetter,BlockPos)
+ boolean isViewBlocking(BlockState,BlockGetter,BlockPos)
```

</details>
</details>
<hr/>