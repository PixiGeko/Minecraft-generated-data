## Comparison with [1.21.2-rc1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.21.2-rc1)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.21.2-rc1</th><th>1.21.2-rc2</th></tr><tr><td>World version</td><td><pre>4078</pre></td><td><pre>4079</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742042</pre></td><td><pre>1073742043</pre></td></tr></table>
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
XXX.server.level.ChunkMap +2M -2M
```
```
XXX.server.level.ServerChunkCache +1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- void lambda$prepareTickingChunk$24(ChunkHolder,LevelChunk,Object)
+ void lambda$prepareTickingChunk$24(LevelChunk,Object)
- void onChunkReadyToSend(ChunkHolder,LevelChunk)
+ void onChunkReadyToSend(LevelChunk)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
- void onChunkReadyToSend(ChunkHolder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
- void applyEffectsFromBlocks()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.server.level.ChunkMap +2M -2M
```
```
XXX.server.level.ServerChunkCache +1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- void lambda$prepareTickingChunk$24(ChunkHolder,LevelChunk,Object)
+ void lambda$prepareTickingChunk$24(LevelChunk,Object)
- void onChunkReadyToSend(ChunkHolder,LevelChunk)
+ void onChunkReadyToSend(LevelChunk)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
- void onChunkReadyToSend(ChunkHolder)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
- void applyEffectsFromBlocks()
```

</details>
</details>
<hr/>