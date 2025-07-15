## Comparison with [1.18-pre5](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre5)

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
<table><tr><th></th><th align="left">1.18-pre5</th><th>1.18-pre6</th></tr><tr><td>World version</td><td><pre>2851</pre></td><td><pre>2853</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741877</pre></td><td><pre>1073741878</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18-pre5</th><th>1.18-pre6</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_melon_sparse.json
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
XXX.server.level.ChunkMap +35M -35M | +1P
```
```
XXX.server.level.ServerLevel +1M
```
```
XXX.world.entity.Entity +2M -3M
```
```
XXX.levelgen.blockpredicates.BlockPredicate +1M
```
```
XXX.phys.shapes.EntityCollisionContext +1M -2M | -1P
```
```
XXX.phys.shapes.Shapes -3M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- boolean saveChunkIfNeeded(ChunkHolder)
- ChunkAccess lambda$protoChunkToFullChunk$26(ChunkHolder,ChunkAccess)
+ ChunkAccess lambda$protoChunkToFullChunk$27(ChunkHolder,ChunkAccess)
- ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$25(ChunkHolder)
+ ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$26(ChunkHolder)
- ChunkStatus lambda$prepareTickingChunk$29(int)
+ ChunkStatus lambda$prepareTickingChunk$30(int)
- ChunkStatus lambda$scheduleChunkGeneration$15(ChunkStatus,int)
+ ChunkStatus lambda$scheduleChunkGeneration$16(ChunkStatus,int)
- CompletableFuture lambda$schedule$13(ChunkHolder,ChunkAccess)
+ CompletableFuture lambda$schedule$14(ChunkHolder,ChunkAccess)
- CompletableFuture lambda$scheduleChunkGeneration$18(ChunkHolder,ChunkAccess)
+ CompletableFuture lambda$scheduleChunkGeneration$19(ChunkHolder,ChunkAccess)
- CompletableFuture lambda$scheduleChunkGeneration$19(ChunkPos,ChunkHolder,ChunkStatus,Executor,List)
+ CompletableFuture lambda$scheduleChunkGeneration$20(ChunkPos,ChunkHolder,ChunkStatus,Executor,List)
- CompletableFuture lambda$scheduleChunkGeneration$20(ChunkPos,ChunkHolder$ChunkLoadingFailure)
+ CompletableFuture lambda$scheduleChunkGeneration$21(ChunkPos,ChunkHolder$ChunkLoadingFailure)
- CompletionStage lambda$scheduleChunkGeneration$21(ChunkPos,ChunkHolder,ChunkStatus,Executor,Either)
+ CompletionStage lambda$scheduleChunkGeneration$22(ChunkPos,ChunkHolder,ChunkStatus,Executor,Either)
- Either lambda$prepareAccessibleChunk$38(Either)
+ Either lambda$prepareAccessibleChunk$39(Either)
- Either lambda$prepareTickingChunk$30(List)
- Either lambda$prepareTickingChunk$31(Either)
+ Either lambda$prepareTickingChunk$31(List)
+ Either lambda$prepareTickingChunk$32(Either)
- Either lambda$protoChunkToFullChunk$27(ChunkHolder,Either)
+ Either lambda$protoChunkToFullChunk$28(ChunkHolder,Either)
- Either lambda$scheduleChunkLoad$14(ChunkPos)
+ Either lambda$scheduleChunkLoad$15(ChunkPos)
- Integer lambda$dumpChunks$42(LevelChunk)
+ Integer lambda$dumpChunks$45(LevelChunk)
- LevelChunk lambda$prepareAccessibleChunk$37(List)
+ LevelChunk lambda$prepareAccessibleChunk$38(List)
- Optional lambda$dumpChunks$41(ChunkAccess)
+ Optional lambda$dumpChunks$42(ChunkAccess)
- String lambda$printFuture$45(LevelChunk)
- String lambda$printFuture$46(ChunkHolder$ChunkLoadingFailure)
+ String lambda$printFuture$46(LevelChunk)
+ String lambda$printFuture$47(ChunkHolder$ChunkLoadingFailure)
- String lambda$releaseLightTicket$23(ChunkPos)
+ String lambda$releaseLightTicket$24(ChunkPos)
- String lambda$scheduleChunkGeneration$16(ChunkStatus)
+ String lambda$scheduleChunkGeneration$17(ChunkStatus)
- void lambda$prepareAccessibleChunk$39(ChunkHolder,Runnable)
+ void lambda$prepareAccessibleChunk$40(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$32(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$33(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$33(MutableObject,LevelChunk,ServerPlayer)
- void lambda$prepareTickingChunk$34(ChunkPos,LevelChunk)
+ void lambda$prepareTickingChunk$34(MutableObject,LevelChunk,ServerPlayer)
- void lambda$prepareTickingChunk$35(ChunkPos,Either)
+ void lambda$prepareTickingChunk$35(ChunkPos,LevelChunk)
- void lambda$prepareTickingChunk$36(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$36(ChunkPos,Either)
+ void lambda$prepareTickingChunk$37(ChunkHolder,Runnable)
- void lambda$protoChunkToFullChunk$24(ProtoChunk,LevelChunk)
+ void lambda$protoChunkToFullChunk$25(ProtoChunk,LevelChunk)
- void lambda$protoChunkToFullChunk$28(ChunkHolder,Runnable)
+ void lambda$protoChunkToFullChunk$29(ChunkHolder,Runnable)
- void lambda$releaseLightTicket$22(ChunkPos)
+ void lambda$releaseLightTicket$23(ChunkPos)
+ void lambda$saveAllChunks$11(ChunkHolder)
- void lambda$scheduleChunkGeneration$17(ChunkHolder,Runnable)
+ void lambda$scheduleChunkGeneration$18(ChunkHolder,Runnable)
- void lambda$scheduleUnload$11(ChunkHolder,CompletableFuture,long,ChunkAccess)
+ void lambda$scheduleUnload$12(ChunkHolder,CompletableFuture,long,ChunkAccess)
- void lambda$scheduleUnload$12(ChunkHolder,Void,Throwable)
+ void lambda$scheduleUnload$13(ChunkHolder,Void,Throwable)
- void lambda$setViewDistance$40(ChunkPos,int,MutableObject,ServerPlayer)
+ void lambda$setViewDistance$41(ChunkPos,int,MutableObject,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- void lambda$onStructureStartsAvailable$23(ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- Vec3 collideBoundingBox(Entity,Vec3,AABB,Level,List)
+ Vec3 collideBoundingBox(Vec3,AABB,LevelReader,CollisionContext,List)
+ Vec3 collideBoundingBoxHeuristically(Entity,Vec3,AABB,Level,CollisionContext,List)
+ Vec3 collideBoundingBoxLegacy(Vec3,AABB,List)
- Vec3 collideWithShapes(Vec3,AABB,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
</summary>

```diff
- BlockPredicate hasSturdyFace(Direction)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
+ boolean hasItemOnFeet(Item)
+ void <init>(boolean,double,ItemStack,ItemStack,Predicate,Entity)
- void <init>(boolean,double,ItemStack,Predicate,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.Shapes
</summary>

```diff
+ double collide(AABB,LevelReader,double,CollisionContext,AxisCycle,Iterable)
+ double collide(Direction$Axis,AABB,LevelReader,double,CollisionContext,Iterable)
+ int lastC(double,double,double)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.GlStateManager +1P
```
```
net.minecraft.SharedConstants -1P
```
```
XXX.level.biome.Biome +4M -1M
```
```
XXX.levelgen.blending.BlendingData -1P
```
```
XXX.phys.shapes.CollisionContext -1P
```
```
XXX.phys.shapes.EntityCollisionContext$1 +1M -1M
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
- boolean coldEnoughToSnow(BlockPos)
+ boolean isColdEnoughToSnow(BlockPos)
- boolean shouldMeltFrozenOceanIcebergSlightly(BlockPos)
- boolean shouldSnowGolemBurn(BlockPos)
- boolean warmEnoughToRain(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext$1
</summary>

```diff
+ void <init>(boolean,double,ItemStack,ItemStack,Predicate,Entity)
- void <init>(boolean,double,ItemStack,Predicate,Entity)
```

</details>
</details>
<hr/>