## Comparison with [1.18-pre6](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre6)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18-pre6</th><th>1.18-pre7</th></tr><tr><td>World version</td><td><pre>2853</pre></td><td><pre>2854</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741878</pre></td><td><pre>1073741879</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18-pre6</th><th>1.18-pre7</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.server.level.ChunkMap +27M -26M
```
```
XXX.datafix.fixes.ChunkRenamesFix +5M -4M
```
```
XXX.level.chunk.PalettedContainer +1P -2P
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
+ ChunkAccess lambda$protoChunkToFullChunk$26(ChunkHolder,ChunkAccess)
- ChunkAccess lambda$protoChunkToFullChunk$27(ChunkHolder,ChunkAccess)
+ ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$25(ChunkHolder)
- ChunkHolder$FullChunkStatus lambda$protoChunkToFullChunk$26(ChunkHolder)
+ ChunkStatus lambda$prepareTickingChunk$29(int)
- ChunkStatus lambda$prepareTickingChunk$30(int)
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
- void lambda$scheduleChunkGeneration$19(CrashReport)
+ void lambda$setViewDistance$40(ChunkPos,int,MutableObject,ServerPlayer)
- void lambda$setViewDistance$41(ChunkPos,int,MutableObject,ServerPlayer)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkRenamesFix
</summary>

```diff
+ DataResult lambda$mergeRemainders$3(DynamicOps,Dynamic,MapLike)
- DataResult lambda$mergeRemainders$4(DynamicOps,Dynamic,MapLike)
- Dynamic lambda$makeRule$1(Dynamic)
+ Dynamic lambda$mergeRemainders$4(DynamicOps,Object)
- Dynamic lambda$mergeRemainders$5(DynamicOps,Object)
+ Dynamic lambda$renameField$2(String,Dynamic)
- Dynamic lambda$renameField$3(String,Dynamic)
+ Typed lambda$makeRule$1(OpticFinder,OpticFinder,Type,Typed)
- Typed lambda$makeRule$2(OpticFinder,OpticFinder,Type,Typed)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.util.ThreadingDetector +6M -4M | +6P
```
```
XXX.world.level.ChunkPos +1P
```

</details>
<details>
<summary>
net.minecraft.util.ThreadingDetector
</summary>

```diff
+ ReportedException makeThreadingException(String,DebugBuffer)
- ReportedException makeThreadingException(String,Thread)
+ String lambda$makeThreadingException$0(Thread)
- String stackTrace(Thread)
- void <clinit>()
+ void <init>()
- void <init>(String)
- void checkAndLock()
+ void checkAndLock(Semaphore,DebugBuffer,String)
- void checkAndUnlock()
```

</details>
</details>
<hr/>