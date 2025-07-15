## Comparison with [25w09a](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w09a)

> [!TIP]
> - [Version data](#version-data)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w09a</th><th>25w09b</th></tr><tr><td>World version</td><td><pre>4317</pre></td><td><pre>4318</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742060</pre></td><td><pre>1073742061</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.buffers.GpuBuffer +1P
```
```
XXX.opengl.dsa.CoreDsa +1M -1M
```
```
XXX.opengl.dsa.EmulatedDsa +1M -1M
```
```
XXX.blaze3d.systems.GpuDevice +1P
```
```
XXX.blaze3d.systems.RenderSystem -1M
```
```
XXX.minecraft.client.Minecraft +7M -6M
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.dsa.CoreDsa
</summary>

```diff
- void bindFrameBufferTextures(int,int,int,int,boolean)
+ void bindFrameBufferTextures(int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.opengl.dsa.EmulatedDsa
</summary>

```diff
- void bindFrameBufferTextures(int,int,int,int,boolean)
+ void bindFrameBufferTextures(int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ String getCapsString()
```

</details>
<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
+ CompletionStage lambda$delayTextureReload$53(CompletableFuture)
- CompletionStage lambda$delayTextureReload$54(CompletableFuture)
- String lambda$fillSystemReport$48()
+ String lambda$fillSystemReport$48(Minecraft)
+ String lambda$fillSystemReport$50(LanguageManager)
- String lambda$fillSystemReport$50(Minecraft)
+ String lambda$fillSystemReport$51()
- String lambda$fillSystemReport$51(LanguageManager)
- String lambda$fillSystemReport$53()
+ Style lambda$grabPanoramixScreenshot$55(File,Style)
- Style lambda$grabPanoramixScreenshot$56(File,Style)
+ void lambda$grabPanoramixScreenshot$54(Component)
- void lambda$grabPanoramixScreenshot$55(Component)
```

</details>
</details>
<hr/>