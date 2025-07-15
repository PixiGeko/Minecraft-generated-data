## Comparison with [1.18-pre8](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18-pre8)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18-pre8</th><th>1.18-rc1</th></tr><tr><td>World version</td><td><pre>2855</pre></td><td><pre>2856</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741880</pre></td><td><pre>1073741881</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18-pre8</th><th>1.18-rc1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.server.level.ChunkHolder +8M -6M
```
```
XXX.level.chunk.PalettedContainer +1M -1M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
- ChunkAccess lambda$addSaveDependency$2(ChunkAccess,Object)
+ ChunkAccess lambda$updateChunkToSave$2(ChunkAccess)
+ ChunkAccess lambda$updateChunkToSave$3(ChunkAccess,ChunkHolder$ChunkLoadingFailure)
- ChunkAccess lambda$updateChunkToSave$3(ChunkAccess)
- ChunkAccess lambda$updateChunkToSave$4(ChunkAccess,ChunkHolder$ChunkLoadingFailure)
+ ChunkAccess lambda$updateChunkToSave$4(ChunkAccess,Either)
- ChunkAccess lambda$updateChunkToSave$5(ChunkAccess,Either)
- void addSaveDependency(String,CompletableFuture)
+ void lambda$scheduleFullChunkPromotion$5(ChunkMap,ChunkHolder$FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$6(ChunkMap,ChunkHolder$FullChunkStatus)
+ void lambda$scheduleFullChunkPromotion$6(CompletableFuture,LevelChunk)
+ void lambda$scheduleFullChunkPromotion$7(CompletableFuture,Either)
- void lambda$scheduleFullChunkPromotion$7(CompletableFuture,LevelChunk)
- void lambda$scheduleFullChunkPromotion$8(CompletableFuture,Either)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
+ void lambda$count$8(Int2IntMap,int)
- void lambda$count$8(Int2IntOpenHashMap,int)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderChunkRegion$RenderChunk
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.client.resources.ClientPackSource +1P -1P
```
```
XXX.server.level.ChunkHolder +8M -6M
```
```
XXX.level.chunk.PalettedContainer +1M -1M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkHolder
</summary>

```diff
- ChunkAccess lambda$addSaveDependency$2(ChunkAccess,Object)
+ ChunkAccess lambda$updateChunkToSave$2(ChunkAccess)
+ ChunkAccess lambda$updateChunkToSave$3(ChunkAccess,ChunkHolder$ChunkLoadingFailure)
- ChunkAccess lambda$updateChunkToSave$3(ChunkAccess)
- ChunkAccess lambda$updateChunkToSave$4(ChunkAccess,ChunkHolder$ChunkLoadingFailure)
+ ChunkAccess lambda$updateChunkToSave$4(ChunkAccess,Either)
- ChunkAccess lambda$updateChunkToSave$5(ChunkAccess,Either)
- void addSaveDependency(String,CompletableFuture)
+ void lambda$scheduleFullChunkPromotion$5(ChunkMap,ChunkHolder$FullChunkStatus)
- void lambda$scheduleFullChunkPromotion$6(ChunkMap,ChunkHolder$FullChunkStatus)
+ void lambda$scheduleFullChunkPromotion$6(CompletableFuture,LevelChunk)
+ void lambda$scheduleFullChunkPromotion$7(CompletableFuture,Either)
- void lambda$scheduleFullChunkPromotion$7(CompletableFuture,LevelChunk)
- void lambda$scheduleFullChunkPromotion$8(CompletableFuture,Either)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
+ void lambda$count$8(Int2IntMap,int)
- void lambda$count$8(Int2IntOpenHashMap,int)
```

</details>
</details>
<hr/>