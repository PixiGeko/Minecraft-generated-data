## Comparison with [1.17.1-rc1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17.1-rc1)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17.1-rc1</th><th>1.17.1-rc2</th></tr><tr><td>World version</td><td><pre>2728</pre></td><td><pre>2729</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741863</pre></td><td><pre>1073741864</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17.1-rc1</th><th>1.17.1-rc2</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.chunk.storage.EntityStorage +1M -1M | +1P -1P
```
```
XXX.level.entity.EntityPersistentStorage +1P -1P
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.EntityStorage
</summary>

```diff
+ void flush()
- void flush(boolean)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.renderer.chunk.RenderChunkRegion -1P
```
```
XXX.server.level.ChunkMap +1M | +1P -1P
```
```
XXX.util.thread.ProcessorMailbox +2M
```
```
XXX.chunk.storage.IOWorker +7M -5M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- String getStorageName()
```

</details>
<details>
<summary>
net.minecraft.util.thread.ProcessorMailbox
</summary>

```diff
- boolean lambda$runAll$1(int)
- void runAll()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.storage.IOWorker
</summary>

```diff
+ CompletableFuture synchronize()
- CompletableFuture synchronize(boolean)
- CompletionStage lambda$synchronize$9(Void)
- Either lambda$synchronize$8()
+ StrictQueue$IntRunnable lambda$close$11(ProcessorHandle)
- StrictQueue$IntRunnable lambda$close$13(ProcessorHandle)
- StrictQueue$IntRunnable lambda$submitTask$11(Supplier,ProcessorHandle)
+ StrictQueue$IntRunnable lambda$submitTask$9(Supplier,ProcessorHandle)
+ void lambda$close$10(ProcessorHandle)
- void lambda$close$12(ProcessorHandle)
- void lambda$submitTask$10(ProcessorHandle,Supplier)
+ void lambda$submitTask$8(ProcessorHandle,Supplier)
```

</details>
</details>
<hr/>