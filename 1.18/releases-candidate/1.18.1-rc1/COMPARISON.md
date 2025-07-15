## Comparison with [1.18.1-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.18.1-pre1)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.18.1-pre1</th><th>1.18.1-rc1</th></tr><tr><td>World version</td><td><pre>2861</pre></td><td><pre>2862</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741885</pre></td><td><pre>1073741886</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.18.1-pre1</th><th>1.18.1-rc1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
XXX.server.level.ChunkMap +2M -5M
```
```
XXX.datafix.fixes.ChunkToProtochunkFix -3M
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
+ boolean isChunkInEuclideanRange(ChunkPos,int,int,int)
+ boolean isChunkInEuclideanRange(ChunkPos,ServerPlayer,boolean,int)
+ boolean isChunkInEuclideanRange(int,int,int,int,int)
- boolean isChunkInRange(int,int,int,int,int)
+ boolean isChunkOnEuclideanBorder(ChunkPos,ServerPlayer,boolean,int)
+ boolean isChunkOnEuclideanBorder(int,int,int,int,int)
- boolean isChunkOnRangeBorder(int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
</summary>

```diff
+ Dynamic createEmptyChunk(Dynamic)
+ void lambda$createEmptyChunk$8(ImmutableMap$Builder,Dynamic,Dynamic)
+ void lambda$createEmptyChunk$9(ImmutableMap$Builder,Dynamic,Dynamic)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.shaders.Uniform +1M
```
```
XXX.blaze3d.systems.RenderSystem +9M -6M | +1P
```
```
net.minecraft.Util +1M
```
```
XXX.server.level.ChunkMap +2M -5M
```
```
XXX.datafix.fixes.ChunkToProtochunkFix -3M
```

</details>
<details>
<summary>
com.mojang.blaze3d.shaders.Uniform
</summary>

```diff
- void set(Matrix3f)
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- Matrix3f getInverseViewRotationMatrix()
+ void lambda$applyModelViewMatrix$66(Matrix4f)
- void lambda$applyModelViewMatrix$67(Matrix4f)
+ void lambda$backupProjectionMatrix$67()
- void lambda$backupProjectionMatrix$68()
+ void lambda$resetTextureMatrix$65()
- void lambda$resetTextureMatrix$66()
+ void lambda$restoreProjectionMatrix$68()
- void lambda$restoreProjectionMatrix$69()
- void lambda$setInverseViewRotationMatrix$64(Matrix3f)
+ void lambda$setShaderGameTime$69(float)
- void lambda$setShaderGameTime$70(float)
+ void lambda$setTextureMatrix$64(Matrix4f)
- void lambda$setTextureMatrix$65(Matrix4f)
- void setInverseViewRotationMatrix(Matrix3f)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
- void logAndPauseIfInIde(String,Throwable)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
+ boolean isChunkInEuclideanRange(ChunkPos,int,int,int)
+ boolean isChunkInEuclideanRange(ChunkPos,ServerPlayer,boolean,int)
+ boolean isChunkInEuclideanRange(int,int,int,int,int)
- boolean isChunkInRange(int,int,int,int,int)
+ boolean isChunkOnEuclideanBorder(ChunkPos,ServerPlayer,boolean,int)
+ boolean isChunkOnEuclideanBorder(int,int,int,int,int)
- boolean isChunkOnRangeBorder(int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
</summary>

```diff
+ Dynamic createEmptyChunk(Dynamic)
+ void lambda$createEmptyChunk$8(ImmutableMap$Builder,Dynamic,Dynamic)
+ void lambda$createEmptyChunk$9(ImmutableMap$Builder,Dynamic,Dynamic)
```

</details>
</details>
<hr/>