<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.18-pre6 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.18-pre6</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2021-11-22T17:09:05+00:00</td></tr>
<tr><th>SHA1</th><td>881f1e388c66a0a27f1e39759d594aba7fc827cc</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/881f1e388c66a0a27f1e39759d594aba7fc827cc/1.18-pre6.json">https://piston-meta.mojang.com/v1/packages/881f1e388c66a0a27f1e39759d594aba7fc827cc/1.18-pre6.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json">https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/97b1c53df11cb8b973f4b522c8f4963b7e31495e/server.jar">https://piston-data.mojang.com/v1/objects/97b1c53df11cb8b973f4b522c8f4963b7e31495e/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/664893998f7e6d307c7e3f307e59d7f1220c6c87/server.txt">https://piston-data.mojang.com/v1/objects/664893998f7e6d307c7e3f307e59d7f1220c6c87/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/86dc60a6e7e9f1bbb877ce2c950de3d1c3cafb89/client.jar">https://piston-data.mojang.com/v1/objects/86dc60a6e7e9f1bbb877ce2c950de3d1c3cafb89/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/f50ffba6205ca0cff1fbfeb3709b4aae1b66d409/client.txt">https://piston-data.mojang.com/v1/objects/f50ffba6205ca0cff1fbfeb3709b4aae1b66d409/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre5">1.18-pre5</a>

# Mappings

### Client




<details><summary>net.minecraft.world.level.biome.Biome</summary>

```diff
+ boolean coldEnoughToSnow(BlockPos)
- boolean isColdEnoughToSnow(BlockPos)
+ boolean shouldMeltFrozenOceanIcebergSlightly(BlockPos)
+ boolean shouldSnowGolemBurn(BlockPos)
+ boolean warmEnoughToRain(BlockPos)
```

</details>


<details><summary>net.minecraft.world.phys.shapes.EntityCollisionContext$1</summary>

```diff
- void <init>(boolean,double,ItemStack,ItemStack,Predicate,Entity)
+ void <init>(boolean,double,ItemStack,Predicate,Entity)
```

</details>


### Server




<details><summary>net.minecraft.server.level.ChunkMap</summary>

```diff
+ boolean saveChunkIfNeeded(ChunkHolder)
+ ChunkAccess lambda$protoChunkToFullChunk$26(ChunkHolder,ChunkAccess)
- ChunkAccess lambda$protoChunkToFullChunk$27(ChunkHolder,ChunkAccess)
+ ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$25(ChunkHolder)
- ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$26(ChunkHolder)
+ ChunkStatus lambda$prepareTickingChunk$29(int)
- ChunkStatus lambda$prepareTickingChunk$30(int)
+ ChunkStatus lambda$scheduleChunkGeneration$15(ChunkStatus,int)
- ChunkStatus lambda$scheduleChunkGeneration$16(ChunkStatus,int)
+ CompletableFuture lambda$schedule$13(ChunkHolder,ChunkAccess)
- CompletableFuture lambda$schedule$14(ChunkHolder,ChunkAccess)
+ CompletableFuture lambda$scheduleChunkGeneration$18(ChunkHolder,ChunkAccess)
- CompletableFuture lambda$scheduleChunkGeneration$19(ChunkHolder,ChunkAccess)
+ CompletableFuture lambda$scheduleChunkGeneration$19(ChunkPos,ChunkHolder,ChunkStatus,Executor,List)
- CompletableFuture lambda$scheduleChunkGeneration$20(ChunkPos,ChunkHolder,ChunkStatus,Executor,List)
+ CompletableFuture lambda$scheduleChunkGeneration$20(ChunkPos,ChunkHolder$ChunkLoadingFailure)
- CompletableFuture lambda$scheduleChunkGeneration$21(ChunkPos,ChunkHolder$ChunkLoadingFailure)
+ CompletionStage lambda$scheduleChunkGeneration$21(ChunkPos,ChunkHolder,ChunkStatus,Executor,Either)
- CompletionStage lambda$scheduleChunkGeneration$22(ChunkPos,ChunkHolder,ChunkStatus,Executor,Either)
+ Either lambda$prepareAccessibleChunk$38(Either)
- Either lambda$prepareAccessibleChunk$39(Either)
+ Either lambda$prepareTickingChunk$30(List)
+ Either lambda$prepareTickingChunk$31(Either)
- Either lambda$prepareTickingChunk$31(List)
- Either lambda$prepareTickingChunk$32(Either)
+ Either lambda$protoChunkToFullChunk$27(ChunkHolder,Either)
- Either lambda$protoChunkToFullChunk$28(ChunkHolder,Either)
+ Either lambda$scheduleChunkLoad$14(ChunkPos)
- Either lambda$scheduleChunkLoad$15(ChunkPos)
+ Integer lambda$dumpChunks$42(LevelChunk)
- Integer lambda$dumpChunks$45(LevelChunk)
+ LevelChunk lambda$prepareAccessibleChunk$37(List)
- LevelChunk lambda$prepareAccessibleChunk$38(List)
+ Optional lambda$dumpChunks$41(ChunkAccess)
- Optional lambda$dumpChunks$42(ChunkAccess)
+ String lambda$printFuture$45(LevelChunk)
+ String lambda$printFuture$46(ChunkHolder$ChunkLoadingFailure)
- String lambda$printFuture$46(LevelChunk)
- String lambda$printFuture$47(ChunkHolder$ChunkLoadingFailure)
+ String lambda$releaseLightTicket$23(ChunkPos)
- String lambda$releaseLightTicket$24(ChunkPos)
+ String lambda$scheduleChunkGeneration$16(ChunkStatus)
- String lambda$scheduleChunkGeneration$17(ChunkStatus)
+ void lambda$prepareAccessibleChunk$39(ChunkHolder,Runnable)
- void lambda$prepareAccessibleChunk$40(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$32(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$33(ChunkHolder,Runnable)
+ void lambda$prepareTickingChunk$33(MutableObject,LevelChunk,ServerPlayer)
+ void lambda$prepareTickingChunk$34(ChunkPos,LevelChunk)
- void lambda$prepareTickingChunk$34(MutableObject,LevelChunk,ServerPlayer)
+ void lambda$prepareTickingChunk$35(ChunkPos,Either)
- void lambda$prepareTickingChunk$35(ChunkPos,LevelChunk)
+ void lambda$prepareTickingChunk$36(ChunkHolder,Runnable)
- void lambda$prepareTickingChunk$36(ChunkPos,Either)
- void lambda$prepareTickingChunk$37(ChunkHolder,Runnable)
+ void lambda$protoChunkToFullChunk$24(ProtoChunk,LevelChunk)
- void lambda$protoChunkToFullChunk$25(ProtoChunk,LevelChunk)
+ void lambda$protoChunkToFullChunk$28(ChunkHolder,Runnable)
- void lambda$protoChunkToFullChunk$29(ChunkHolder,Runnable)
+ void lambda$releaseLightTicket$22(ChunkPos)
- void lambda$releaseLightTicket$23(ChunkPos)
- void lambda$saveAllChunks$11(ChunkHolder)
+ void lambda$scheduleChunkGeneration$17(ChunkHolder,Runnable)
- void lambda$scheduleChunkGeneration$18(ChunkHolder,Runnable)
+ void lambda$scheduleUnload$11(ChunkHolder,CompletableFuture,long,ChunkAccess)
- void lambda$scheduleUnload$12(ChunkHolder,CompletableFuture,long,ChunkAccess)
+ void lambda$scheduleUnload$12(ChunkHolder,Void,Throwable)
- void lambda$scheduleUnload$13(ChunkHolder,Void,Throwable)
+ void lambda$setViewDistance$40(ChunkPos,int,MutableObject,ServerPlayer)
- void lambda$setViewDistance$41(ChunkPos,int,MutableObject,ServerPlayer)
```

</details>


<details><summary>net.minecraft.server.level.ServerLevel</summary>

```diff
+ void lambda$onStructureStartsAvailable$23(ChunkAccess)
```

</details>


<details><summary>net.minecraft.world.entity.Entity</summary>

```diff
+ Vec3 collideBoundingBox(Entity,Vec3,AABB,Level,List)
- Vec3 collideBoundingBox(Vec3,AABB,LevelReader,CollisionContext,List)
- Vec3 collideBoundingBoxHeuristically(Entity,Vec3,AABB,Level,CollisionContext,List)
- Vec3 collideBoundingBoxLegacy(Vec3,AABB,List)
+ Vec3 collideWithShapes(Vec3,AABB,List)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate</summary>

```diff
+ BlockPredicate hasSturdyFace(Direction)
```

</details>


<details><summary>net.minecraft.world.phys.shapes.EntityCollisionContext</summary>

```diff
- boolean hasItemOnFeet(Item)
- void <init>(boolean,double,ItemStack,ItemStack,Predicate,Entity)
+ void <init>(boolean,double,ItemStack,Predicate,Entity)
```

</details>


<details><summary>net.minecraft.world.phys.shapes.Shapes</summary>

```diff
- double collide(AABB,LevelReader,double,CollisionContext,AxisCycle,Iterable)
- double collide(Direction$Axis,AABB,LevelReader,double,CollisionContext,Iterable)
- int lastC(double,double,double)
```

</details>


# Folder structure

<details><summary>minecraft-generated/</summary>

```diff
+ reports/worldgen/minecraft/worldgen/placed_feature/patch_melon_sparse.json
```

</details>
