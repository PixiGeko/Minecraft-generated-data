<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.18-pre7 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.18-pre7</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2021-11-23T16:37:41+00:00</td></tr>
<tr><th>SHA1</th><td>14c6eee2ef0b2ec4dd66d21a45288df9ea445853</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/14c6eee2ef0b2ec4dd66d21a45288df9ea445853/1.18-pre7.json">https://piston-meta.mojang.com/v1/packages/14c6eee2ef0b2ec4dd66d21a45288df9ea445853/1.18-pre7.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json">https://piston-meta.mojang.com/v1/packages/d31a2e85ae149dd1b1a7070b22cb8887892fda6c/1.18.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/fe08544bb92ebe53070ec4a5f161ac19d8e9e4bb/server.jar">https://piston-data.mojang.com/v1/objects/fe08544bb92ebe53070ec4a5f161ac19d8e9e4bb/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/174842d495ca5ae1eb68037012820052744b76ac/server.txt">https://piston-data.mojang.com/v1/objects/174842d495ca5ae1eb68037012820052744b76ac/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/04f78760e28f823365430bf1126a49ac30d7db6c/client.jar">https://piston-data.mojang.com/v1/objects/04f78760e28f823365430bf1126a49ac30d7db6c/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/06d045d733b33a5de8952c8328dd82e61f938638/client.txt">https://piston-data.mojang.com/v1/objects/06d045d733b33a5de8952c8328dd82e61f938638/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre6">1.18-pre6</a>

# Mappings

### Client




<details><summary>net.minecraft.util.ThreadingDetector</summary>

```diff
- ReportedException makeThreadingException(String,DebugBuffer)
+ ReportedException makeThreadingException(String,Thread)
- String lambda$makeThreadingException$0(Thread)
+ String stackTrace(Thread)
+ void <clinit>()
- void <init>()
+ void <init>(String)
+ void checkAndLock()
- void checkAndLock(Semaphore,DebugBuffer,String)
+ void checkAndUnlock()
```

</details>


### Server




<details><summary>net.minecraft.server.level.ChunkMap</summary>

```diff
- ChunkAccess lambda$protoChunkToFullChunk$26(ChunkHolder,ChunkAccess)
+ ChunkAccess lambda$protoChunkToFullChunk$27(ChunkHolder,ChunkAccess)
- ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$25(ChunkHolder)
+ ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$26(ChunkHolder)
- ChunkStatus lambda$prepareTickingChunk$29(int)
+ ChunkStatus lambda$prepareTickingChunk$30(int)
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
+ void lambda$scheduleChunkGeneration$19(CrashReport)
- void lambda$setViewDistance$40(ChunkPos,int,MutableObject,ServerPlayer)
+ void lambda$setViewDistance$41(ChunkPos,int,MutableObject,ServerPlayer)
```

</details>


<details><summary>net.minecraft.util.datafix.fixes.ChunkRenamesFix</summary>

```diff
- DataResult lambda$mergeRemainders$3(DynamicOps,Dynamic,MapLike)
+ DataResult lambda$mergeRemainders$4(DynamicOps,Dynamic,MapLike)
+ Dynamic lambda$makeRule$1(Dynamic)
- Dynamic lambda$mergeRemainders$4(DynamicOps,Object)
+ Dynamic lambda$mergeRemainders$5(DynamicOps,Object)
- Dynamic lambda$renameField$2(String,Dynamic)
+ Dynamic lambda$renameField$3(String,Dynamic)
- Typed lambda$makeRule$1(OpticFinder,OpticFinder,Type,Typed)
+ Typed lambda$makeRule$2(OpticFinder,OpticFinder,Type,Typed)
```

</details>
